---
layout: default
title: "Simulador de muestras"
lang: es
---

## Valor de referencia

### Nota de referencia de datos
Los datos proporcionados son sólo para referencia. Debido a las variaciones en la tensión y los patrones de costura de los tejedores, la densidad de las muestras puede diferir incluso cuando se usa el mismo hilo y tamaño de aguja. Por lo tanto, para tejer a mano, se recomienda tejer primero una muestra, lavarla y bloquearla, luego medir la densidad real para determinar el número final de puntadas y filas del proyecto, evitando desviaciones en el tamaño del producto terminado.

### I. Objetivo central
Desde una perspectiva de programación, implemente un **simulador de muestras de tejido/ganchillo basado en cuadrícula**, con el objetivo principal de **asignar parámetros físicos del hilo a parámetros visuales de la cuadrícula, donde cada puntada se asigna a una celda de la cuadrícula**.

#### Flujo de trabajo técnico principal
```
Parámetros de entrada (Diámetro del hilo/Número/Capas, etc.) → Calcular el calibre estándar (Puntadas/Filas por 10 cm) → Convertir a filas/columnas de cuadrícula para una muestra de 10 cm → Adaptar el estilo de la cuadrícula a las técnicas de tejido/ganchillo → Representar la cuadrícula en la aplicación
```

### II. Estándares de datos básicos
Todas las fórmulas de cálculo se basan en los siguientes estándares industriales/internacionales para garantizar la precisión de los datos:

| Número estándar | Nombre estándar | Escenario de aplicación principal |
| :---------------------- | :--------------------------------------------- | :------------------------------------------------- |
| ISO 2314:2010 | Textiles - Determinación del título del hilo | Conversión entre título, diámetro y largo del hilo |
| ASTM D2253-19 | Método de prueba estándar para masa por unidad de área y densidad de tejidos de punto | Punto de referencia para calcular el calibre (puntadas/filas) |
| JIS L1096:2010 | Métodos de ensayo para tejidos y tejidos de punto | Rango de referencia de la industria para calibre de tejido/ganchillo |
| Normas de la IWTO (Organización Internacional de Textiles de Lana) | Correlación entre el diámetro del hilo de lana y el cabo | Corrección del diámetro real según el número de capas |

### III. Cálculo de calibre (estándar ASTM D2253)
El calibre (puntadas por 10 cm) es el núcleo del mapeo de la cuadrícula, calculado en base al **diámetro real del hilo + tipo de artesanía**, con referencia al rango de densidad especificado en JIS L1096.

| Diámetro real del hilo (mm) | Calibre de tejido (puntadas/10 cm) | Calibre de crochet (puntadas/10 cm) | Hileras de tejer/10 cm | Hileras de crochet/10 cm |
| :----------------------- | :----------------------------------- | :---------------------------- | :----------------- | :---------------- |
| 0,2~0,3 | 27~32 (Hilo fino) | 25~30 | 23~26 | 18~21 |
| 0,3~0,5 | 21~26 (Hilo medio-fino) | 20~25 | 19~22 | 15~18 |
| 0,5~0,8 | 16~20 (hilo peinado) | 15~20 | 15~18 | 12~15 |
| 0,8~1,2 | 12~15 (hilo voluminoso) | 10~15 | 11~14 | 8~11 |
| >1,2 | 7~11 (hilo súper voluminoso) | 7~10 | 7~10 | 5~8 |

**Ejemplo**: Diámetro real del hilo 0,25 mm (hilo fino de 2 cabos) → Calibre de tejido = 29 puntos/10 cm → Hileras de tejido = 29 × 0,8 = 23,2 hileras/10 cm

#### 1. Definiciones básicas
Calibre = **Calibre de ancho (puntadas por 10 cm)** / **Calibre de altura (filas por 10 cm)** dentro de la dimensión especificada (10 cm)
- Medidor de ancho: Número de puntadas dentro de 10 cm de ancho (determina el ancho del producto terminado);
- Medidor de altura: Número de filas dentro de 10 cm de altura (determina la longitud del producto terminado).

#### 2. Procedimientos de prueba estándar
ASTM D2253 requiere "tejido de muestras + medición estandarizada" para garantizar la precisión, con los siguientes pasos:
1. **Tejer la muestra**:
- Utilice el hilo y las agujas reales del proyecto para tejer una muestra de al menos 15 cm × 15 cm (para evitar que la deformación del borde afecte la medición);
- El patrón de punto debe coincidir con el producto terminado (la densidad varía significativamente entre diferentes puntos, como el punto jersey y el punto brioche).
2. **Bloqueo de Steam (paso crítico)**:
- Planchar con vapor la muestra según el material del hilo (lana/algodón/fibra sintética) (solo vapor, sin presionar ni estirar);
- Mida después del secado natural (las muestras desbloqueadas pueden encogerse, lo que provocará errores en el cálculo del calibre).
3. **Medición precisa**:
- Horizontal: Mida 10 cm en la zona central de la muestra (evitando 2-3 cm de los bordes) y cuente el número de puntos (se permiten puntos fraccionados, por ejemplo, 18,5 puntos);
- Vertical: Mide 10cm en la misma zona central y cuenta el número de hileras;
- Repita la medición 2-3 veces y tome el promedio (para mejorar la precisión).
4. **Calcular resultados**:
Ejemplo: 18 puntos horizontalmente y 24 filas verticalmente dentro de 10 cm → El calibre es "18 puntos × 24 filas / 10 cm".

### IV. Tejer versus crochet
Las categorías de puntadas secundarias se identifican uniformemente como "Corto/Medio/Largo".

| Grado de puntada universal | Correlación de tejido | Correlación de crochet | Característica de densidad del núcleo | Factor de corrección |
|:-----------------------|:---------------------|:--------------------|:---------------------------|:-----------------|
| Corto | Punto Jersey | Punto bajo (SC) | Más compacto (línea de base) | 1.0 |
| Medio | Punto Jersey Revés | Medio punto alto (HDC) | Moderadamente suelto | 0,85 |
| Largo | Punto Brioche | Ganchillo doble (DC) | Extremadamente suelto | 0,7 |
