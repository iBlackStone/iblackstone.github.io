---
layout: default
title: "Guía de uso del mostrador de tejido"
lang: es
---

## Descripción general

Se trata de un contador con memoria diseñado específicamente para tejer y que consta de dos componentes principales:
1. **Contador externo**: Se utiliza principalmente para contar filas con PDF o patrones basados ​​en imágenes.
2. **Contador interno**: Diseñado para patrones creados con el editor de patrones integrado de la aplicación, que ofrece funciones más completas, como recuento simultáneo de filas y puntadas.

Cuando se utiliza dentro de un proyecto de tejido, el contador calcula automáticamente el consumo y el costo del hilo una vez que se ingresan los detalles del hilo.

### Explicación del documento

Este documento sigue el diseño de la interfaz de usuario del contador y explica las funciones de arriba a abajo.

### Agregar (Crear una nueva pestaña)

Utilice esta función para agregar una pestaña personalizable. Un único proyecto de tejido se puede dividir en varias pestañas, cada una completamente independiente, compartiendo solo los botones de control en la parte inferior de la página. Todos los datos específicos de las pestañas (recuentos de filas/puntadas, registros, patrones, etc.) permanecen separados entre pestañas.

### Área de pestañas (debajo de la barra de navegación, encima del interruptor de modo)

#### Botón Editar
- Ubicado en el extremo derecho de la barra de pestañas, se usa para cambiar el nombre o eliminar pestañas.
- **La eliminación es irreversible**: todos los datos asociados con la pestaña se eliminarán permanentemente. Proceda con precaución.

#### Área de visualización de patrones
Muestra patrones de tejido en dos formatos:
- **Patrones internos**: creado utilizando el editor de patrones integrado de la aplicación.
- **Patrones externos**: imágenes importadas o archivos PDF desde el álbum de fotos o el almacenamiento del dispositivo.

##### Área de patrón externo
> Acceso a través de: Barra de funciones → Seleccione el botón "Patrón externo"

- **Botón en forma de cruz (arriba a la derecha)**: toque para mostrar una guía en forma de cruz centrada para navegar por patrones complejos.
- **Marcadores de fila (lado izquierdo)**: navegación de fila simple para patrones externos. Admite desplazamiento y toque; la fila actual se indica en texto rojo en la parte inferior.

##### Área de patrón interno
> Acceso a través de: Barra de funciones → Seleccione el botón "Patrón interno"

Esencialmente un lienzo del editor interno (sin controles de edición). A diferencia de los marcadores de hileras virtuales para patrones externos, el posicionamiento de hileras y puntadas aquí es preciso y exacto.

### Área de exhibición del mostrador

Muestra recuentos de hileras y puntadas con las siguientes características:
- Admite el conteo en **Modo estable**.
- Admite conteo en **modo variable** (el recuento de puntadas cambia con las filas).
- Establecimiento de objetivos: la pantalla parpadea y vibra ligeramente cuando se alcanza la fila objetivo, lo que indica la finalización de una fase.
- Fila inicial personalizable: por defecto es la fila 0, pero se puede configurar para que comience en la fila 1 para adaptarse a diferentes hábitos de conteo.

### Cambiar pestañas

Como sugiere el nombre, seleccionar una pestaña determina qué recuento (fila o puntada) se modificará. No se necesita más explicación aquí.

### Área de registro

Registra registros de cambios en el recuento de filas/puntadas desencadenados por operaciones del usuario:
- [S] = Modo estable; [C] = Modo variable.
- **Botón Nota [M] (lado derecho)**: agregue notas a los registros para rastrear errores.
- Tamaño ajustable: el área de registro se minimiza de forma predeterminada, pero se puede ampliar cuando se necesita una revisión detallada.
- Toque las entradas registradas con notas para ver las notas.
- [+] las operaciones se registran en negro; [-] operaciones en rojo.

### Área del modo de tejido

- **Modo estable**: recuento constante de puntadas por hilera (tejiendo a un ritmo constante).
- **Modo variable**: el recuento de puntadas cambia gradualmente por fila (tejiendo con diferentes frecuencias de puntadas).

#### Modo estable
Después de seleccionar el Modo estable, toque [Configuración] para abrir un cuadro de diálogo de configuración que requiere dos parámetros:
- **Puntadas máximas por fila**: Número de puntadas necesarias por fila.
- **Total de hileras a tejer**: Número objetivo de hileras.

Una vez configurado, la pantalla del contador muestra:
- Parte superior de la pantalla: "Puntadas por fila: 10 | Filas objetivo: 20"
- Parte inferior de la pantalla: modo actual y unidad de cambio para grifos [+]/[-].
- Lado derecho de la pantalla: progreso de la tarea (puede exceder el 100 % si se teje más allá del objetivo, por ejemplo, 30 filas cuando el objetivo es 20).
- La pantalla parpadea y el dispositivo vibra ligeramente cuando se alcanza el objetivo.

#### Modo variable
Después de seleccionar el modo variable, toque [Configuración] para abrir una página de configuración dedicada (debido al mayor número de parámetros).

**Configurador de modo**
- Los parámetros de configuración se detallan con instrucciones en la aplicación en la parte inferior de la página; No hay repetición aquí.

Una vez configurado, la pantalla del contador muestra:
- Parte superior de la pantalla: "Disminuir 1 punto cada 3 hileras | Repetir 4 veces"
- Parte inferior de la pantalla: modo actual, recuento de repeticiones actual y unidad de cambio.
- Lado derecho de la pantalla: Progreso de la tarea (puede exceder el 100 % si se teje más allá del objetivo).
- La pantalla parpadea y el dispositivo vibra ligeramente cuando es necesario cambiar las puntadas o se alcanza el objetivo.

### Barra de funciones

Para usuarios veteranos: anteriormente, los botones de control estaban dispersos por toda la página. A medida que las funciones se ampliaron, centralizar y categorizar los controles se convirtió en una prioridad, lo que dio como resultado la barra de funciones actual.

#### Botones de la primera fila

##### Análisis de gráficos
Genera gráficos visuales basados ​​en registros de recuento. Para los usuarios que disfrutan de la visualización de datos, revisar estos gráficos puede brindarles una sensación de logro al seguir el proceso de tejido.

Cuando se utiliza dentro de un proyecto, Chart Analysis ofrece funciones mejoradas:
- Enlaces a la sección Registro de hilos: seleccione los hilos utilizados, realice un seguimiento del consumo de peso y calcule automáticamente los costos en función de los precios almacenados.
- Sincronización de datos bidireccional con la sección Yarn.
- Seguimiento completo del historial del proyecto a través de puntos de datos vinculados.
- Función Project回溯 (Retrospección): vea los detalles del proyecto en formato tabular.

> La sección Proyecto es un trabajo de amor por parte del desarrollador. El contador es solo una fase del seguimiento del proyecto; recomendamos utilizar la sección Proyecto para una experiencia de tejido más gratificante.

##### Patrón interno
Al seleccionar este botón, el área de visualización del patrón superior cambia a un patrón interno, con controles que incluyen:
- **Importar proyecto**: elija un patrón de destino (por ejemplo, diseño de isla justa). Si no se importa ningún proyecto inicialmente, hay un botón de importación rápida disponible en el área de visualización del patrón (seleccione de la lista de proyectos, procedente de la sección Herramientas de la aplicación).
- **Configuración de estilo**: acceda al editor de patrones para personalizar los estilos de visualización (consulte la explicación del "Modo de conteo" del editor para obtener más detalles).
- **Recuento central**: controla la posición de las filas (habilitado de forma predeterminada). Cuando está habilitado, la fila actual permanece centrada en el área de visualización del patrón; cuando está deshabilitado, las filas no se centran automáticamente.
- **Puntada +/-**: Ajuste manual de la posición de la puntada (aún no vinculado al recuento de puntadas). Envíe sus comentarios si necesita esta función.

##### Patrón externo
Al seleccionar este botón, el área de visualización del patrón superior cambia a un patrón externo, con controles que incluyen:
- **Patrón de importación**: admite importaciones desde el álbum de fotos o archivos de iCloud. Nota: Los archivos PDF suelen ofrecer mayor claridad que las imágenes, pero la aplicación utiliza representación vectorial para mejorar la calidad de la imagen.
- **Configuración de enlace**: debido a la variedad de formatos de patrones externos, la aplicación no calcula automáticamente las alturas de las filas virtuales. Los usuarios pueden personalizar la configuración de vinculación (habilitada de forma predeterminada). Las reglas de uso detalladas se proporcionan en la ventana emergente; No hay repetición aquí.

#### Botones del área de control
- **Tamaño de registro**: ajusta el tamaño de visualización del registro (minimizado de forma predeterminada; expanda para una revisión detallada).
- **Borrar registros**: elimina todos los registros de la pestaña actual (irreversible). Las notas asociadas y los datos de los gráficos también se restablecerán.
- **Restablecer recuentos**: restablece rápidamente el recuento seleccionado (fila o puntada). Para restablecer ambos, realice la acción dos veces. Todos los restablecimientos requieren una confirmación secundaria para proteger los datos del usuario.

### Botones de control inferiores
- [-]: Disminuye el conteo seleccionado (fila o puntada).
- [+]: aumenta el recuento seleccionado (fila o puntada).
- **Selector de unidad (medio)**: ajusta la unidad de incremento/disminución. Nota: Si desplaza rápidamente el selector de unidades y toca [+]/[-] antes de que finalice la animación, se utilizará la unidad anterior. Consulte siempre la unidad que se muestra en la parte inferior del contador; esta es la unidad utilizada para los cálculos.

### Secciones vinculadas

Ninguna sección de la Aplicación funciona de forma independiente; todos están estrechamente integrados en torno al tejido. El contador actual es una subfunción de los proyectos de tejido, diseñado para ayudar a contar durante el proceso de tejido.

> Algunas funciones de contador están restringidas a usuarios permanentes o suscritos. Mantener una aplicación compleja y actualizada periódicamente requiere tiempo y esfuerzo continuos por parte del desarrollador.
