---
title: Ayuda de notas de tejido
lang: es
---

Knitting Notes le permite importar y leer patrones PDF, luego agregar reglas, texto, imágenes, pines de información, pinceladas y contadores. Agregar elementos de página o dibujos no modifica directamente el PDF original.

## Navegación rápida

- [Create and Open a Project](#create-and-open-a-project)
- [Editor Layout](#editor-layout)
- [Bottom Toolbar](#bottom-toolbar)
- [Pages and Labels](#pages-and-labels)
- [Add Page Components](#add-page-components)
- [Chart Grid Calibration](#chart-grid-segmentation)
- [Edit and Lock Components](#edit-page-components)
- [Brushes and Eraser](#brushes-and-eraser)
- [Counters](#counters)
- [Time spent](#time-spent)
- [Elements](#elements)
- [Save and Multiple Devices](#save-undo-and-restore)
- [Frequently Asked Questions](#frequently-asked-questions)

## Crear y abrir un proyecto

1. Abra Herramientas y seleccione **Notas de tejido**.
2. Elija el archivo PDF que desea importar.
3. El archivo importado aparece en la lista de proyectos de Knitting Notes.
4. Toque el proyecto para continuar desde su posición de lectura y estado de edición anteriores.

Los usuarios gratuitos pueden crear hasta un proyecto de Knitting Notes. La eliminación de un proyecto no se puede deshacer, así que primero confirma que ya no lo necesitas.

## Diseño del editor

### Barra de herramientas superior

- **Cerrar**: regresa a la lista de proyectos y guarda el estado de lectura actual.
- **Deshacer**: deshace la última operación de componente o pincel admitida.
- **Rehacer**: Restaura la operación que se acaba de deshacer.
- **Guía del usuario**: toque `?` para abrir esta página de ayuda en cualquier momento.
- **Más**: cambie el nombre, guarde o elimine el proyecto actual.

### Mostrar u ocultar barras de herramientas

Toque un área vacía del PDF para ocultar las barras de herramientas superior e inferior y ganar más espacio de lectura. Utilice los pequeños botones en los bordes de la pantalla para mostrarlos nuevamente.

En el tema oscuro, el área de lectura de PDF reduce el brillo de las páginas blancas de forma predeterminada. Las barras de herramientas superior e inferior permanecen negras y los colores originales del PDF no se invierten. Para ver el brillo original, desactive **Reducir brillo de PDF** en el menú Más de la parte superior derecha.

### Gestos básicos de lectura

- Desliza un dedo para explorar el PDF.
- Pellizca con dos dedos para hacer zoom.
- Toque un componente de la página para seleccionarlo y mostrar sus controles flotantes.
- Al desplazarse o hacer zoom en el PDF se borra la selección de componente actual.

## Barra de herramientas inferior

| Herramienta | Propósito |
|---|---|
| Páginas | Mostrar miniaturas de páginas y etiquetas de páginas para una navegación rápida |
| Componentes | Elija una imagen, marcador de información, enlace de gráfico, texto o regla |
| Mover | Volver a lectura, desplazamiento y zoom de PDF |
| Pincel | Seleccione un pincel y dibuje en la página PDF actual |
| Borrador | Borrar pinceladas |
| Mostrador | Mostrar u ocultar contadores de proyectos |
| Temporizador | Realizar un seguimiento manual del tiempo dedicado a esta sesión |
| Más | Abrir elementos, color predeterminado, administrador de pinceles y administrador de reglas |

## Páginas y etiquetas

Toca **Páginas** para abrir el panel de miniaturas:

- Toque una miniatura para saltar a esa página.
- Utilice la lista de etiquetas en la parte superior para saltar directamente a las páginas etiquetadas.
- Aparece una etiqueta de página en la parte inferior de su miniatura.
- Toque `...` en la miniatura seleccionada para agregar, editar o eliminar una etiqueta.
- Cada página puede tener una etiqueta.

Los usuarios gratuitos pueden crear hasta dos etiquetas de página. Las etiquetas existentes aún se pueden editar o eliminar.

## Agregar componentes de página

1. Toca **Componentes**.
2. Elija un componente.
3. El botón del componente cambia para mostrar el elemento seleccionado.
4. Toque la posición de destino en el PDF. El componente se coloca con el punto de contacto en su centro.
5. El editor vuelve automáticamente al modo Mover.

Para agregar nuevos componentes de página es necesario ser miembro. Los componentes existentes permanecen disponibles para su visualización y edición.

### Componentes disponibles

#### gobernantes

Utilice reglas para seguir la fila o columna actual. Se proporcionan ajustes preestablecidos de regla horizontal, vertical y de 45 grados. Los ajustes preestablecidos se pueden ajustar en el Administrador de reglas.

#### Texto

Los componentes de texto admiten varias líneas. Al ampliar el cuadro de texto se revela más contenido. La configuración de texto incluye color de texto, tamaño de fuente, alineación, copiar y pegar.

#### Imágenes

Las imágenes se pueden seleccionar desde la cámara, Archivos o Fotos. Se insertan utilizando su relación de aspecto original y admiten escalado y rotación proporcionales, pero no estiramiento de bordes independiente.

#### Pin de información

Aparece un pin de información como un icono `i` de tamaño fijo. Tócalo para leer la nota. Toque dos veces el área de texto en la ventana emergente para editar el contenido.

#### Enlace al gráfico

Un enlace de gráfico conecta el PDF a un gráfico de tejido existente en la aplicación. Una vez vinculado, puede mostrar una miniatura y abrir directamente la tabla de tejido relacionada.

<a id="chart-grid-segmentation"></a>
#### Calibración de cuadrícula de gráficos

Chart Grid Calibration convierte un gráfico de píxeles o un gráfico de tejido ya impreso en un PDF en una fuente de cuadrícula reutilizable con información de filas y columnas.

1. Elija **Cuadrícula de gráfico** en Componentes y luego toque el área del gráfico para colocar el marco.
2. Arrastra el área vacía dentro del marco para posicionarla. Utilice las manijas exteriores para cambiar su tamaño o rotarlo.
3. La guía horizontal comienza en la parte superior y la guía vertical comienza en la izquierda. Mueva cada guía y ajuste su grosor hasta que ambos bordes de la guía coincidan con dos líneas de cuadrícula vecinas.
4. Toque **Alinear** para ajustar ambos ejes a su período completo más cercano. Los ajustes casi exactos también se realizan automáticamente y brindan retroalimentación háptica.
5. Rojo significa que la cuadrícula aún necesita atención. Un marco y una cuadrícula confirmados se vuelven verdes y muestran **Alineado**. Mover, cambiar el tamaño o rotar el marco requiere alineación nuevamente.
6. **Lock Frame** protege solo el marco exterior y mantiene ambas guías editables. La acción **Bloquear** posterior bloquea todo el componente.
7. **Vista previa de imagen de cuadrícula** comprueba el resultado extraído sin crear un proyecto de tejido.
8. **Crear gráfico de contador** crea y une un gráfico de tejido. Posteriormente, la misma entrada abre o sincroniza ese gráfico en lugar de crear una nueva copia cada vez.
9. **Más** cambia entre las guías de calibración y la cuadrícula completa, y cambia la dirección de lectura de filas o columnas. Un componente no seleccionado mantiene un pequeño marcador de cuadrícula; toque dos veces uno vinculado para abrir su gráfico.

Después de abrir el editor de tejido, cambie entre **Píxel** y **Dibujo de símbolo**. El dibujo de píxeles muestra los colores de las celdas calibradas y le permite ajustar, fusionar, dividir o ignorar grupos de colores en **Confirmar plan de dibujo**. Dibujo de símbolos agrupa cada imagen de celda y abre **Confirmar símbolos**, donde puede comparar el recorte de origen, la puntada y el fondo de la celda. El texto de la leyenda del PDF y los símbolos previamente confirmados se utilizan como pistas de reconocimiento y se recuerdan las correcciones del usuario. Ambas rutas crean primero una vista previa temporal; toque **Aplicar al lienzo** solo después de marcarlo. Verifique todos los bordes, el recuento de filas y columnas y las instrucciones de lectura antes de su uso.

## Editar componentes de página

Toque un componente para mostrar su marco de selección discontinuo, identificadores y controles flotantes. Las acciones disponibles dependen del tipo de componente:

- Arrastre dentro del componente para moverlo.
- Arrastre un controlador de borde para cambiar el ancho o el alto.
- Arrastre el controlador superior derecho para escalar proporcionalmente.
- Arrastre el controlador superior para girar.
- Utilice Color para cambiar el color del componente.
- Utilice Opacidad para ajustar la transparencia del fondo.
- Utilice Transformar para ángulos rápidos y ajustes de escala.
- Utilice Eliminar para eliminar el componente.

No todos los componentes respaldan todas las acciones. Por ejemplo, las imágenes no pueden estirar los bordes individuales, mientras que los pines de información y los enlaces de los gráficos no pueden rotar ni escalar.

### Bloquear y desbloquear

- Cuando está bloqueada, la barra de herramientas flotante se contrae en un solo botón **Desbloquear**.
- Una regla bloqueada aún se puede mover, pero no se le puede cambiar el tamaño, escalar, rotar ni cambiar el estilo.
- **Bloquear marco** en una cuadrícula de gráfico solo evita cambios accidentales en el marco exterior; las guías internas siguen siendo editables. Utilice la acción normal **Bloquear** para congelar todo el componente.
- El texto, las imágenes, los pines de información, los enlaces de gráficos y otros componentes bloqueados no se pueden mover ni editar.
- Toca **Desbloquear** para restaurar los controles y manijas completos.

## Pinceles y borrador

Seleccione un pincel de **Pincel** y dibuje en la página actual.

- Un ajuste preestablecido de pincel contiene su forma, tamaño, color y opacidad.
- Brush Manager te permite agregar, editar, eliminar y reordenar ajustes preestablecidos.
- Los ajustes preestablecidos que se encuentran cerca de la parte superior de la lista se muestran primero en el editor.
- El borrador elimina únicamente las pinceladas. No elimina reglas, texto, imágenes u otros componentes.
- Elimine componentes usando su botón flotante Eliminar o Elementos.

Para agregar nuevos ajustes preestablecidos de pincel es necesario ser miembro. Los pinceles predeterminados y existentes siguen siendo utilizables.

## tiempo invertido

El temporizador inferior está separado de los contadores de fila. Después de iniciarlo manualmente, al descartar la hoja se mantiene en funcionamiento; Al dejar Notas del proyecto o enviar la aplicación a un segundo plano, se detiene y la guarda. Las notas abiertas desde un proyecto asignan la sesión a ese proyecto, mientras que las notas independientes mantienen un historial de solo notas.

## Contadores

Cada proyecto de Knitting Notes contiene al menos un contador.

- Toque el número para agregar 1.
- Toque `-` para restar 1.
- Toque Restablecer para devolver el valor a 0.
- Toque `...` o mantenga presionado un contador para abrir su menú.
- El menú admite edición, entrada directa de números, color, cambio de nombre y eliminación.
- Filas define el valor máximo. Una vez superado el máximo, el conteo se reinicia desde 0.
- El primer contador de un proyecto no se puede eliminar.

Cada página de contador horizontal muestra hasta tres contadores. Desliza horizontalmente cuando haya más de tres; Aparece un indicador de página en la parte superior. Utilice el botón superior derecho para cambiar entre altura completa y compacta.

Los usuarios gratuitos pueden utilizar hasta tres contadores.

## Elementos

Abra **Más > Elementos** para administrar componentes y notas de pincel en un solo lugar.

- La vista previa de la izquierda ayuda a identificar el elemento y su contorno.
- Toque un elemento para ubicarlo en su página PDF.
- Bloquear o desbloquear componentes.
- Eliminar elementos que ya no sean necesarios.
- Las pinceladas cercanas se agrupan en una vista previa de nota más reconocible.

## Ajustes preestablecidos de color, pinceles y reglas predeterminados

El menú inferior **Más** contiene configuraciones compartidas:

- **Color predeterminado** afecta a los componentes agregados posteriormente.
- **Administrador de pinceles** administra los ajustes preestablecidos de pincel compartidos por todos los proyectos de Knitting Notes.
- **Administrador de reglas** administra los ajustes preestablecidos de reglas compartidos por todos los proyectos de Knitting Notes.

Cambiar un ajuste preestablecido compartido no altera automáticamente los componentes o trazos que ya se han agregado.

## Guardar, deshacer y restaurar

- La posición de lectura, las etiquetas de las páginas, los contadores y la mayoría de las ediciones se almacenan con el proyecto.
- Para guardar inmediatamente, use **Arriba Más > Guardar**.
- Deshacer y Rehacer se aplican a las operaciones de pincel y componentes admitidas en la sesión de edición actual.
- Es posible que el historial de deshacer no permanezca después de abandonar y reabrir un proyecto, pero se restaura el contenido de la página guardada.

## iCloud y múltiples dispositivos

Las copias de seguridad de Knitting Notes incluyen la base de datos del proyecto, archivos PDF y recursos de imágenes relacionados con PDF. El proyecto completo aparece en otro dispositivo solo después de que finaliza la sincronización o restauración de iCloud de la aplicación.

Tenga en cuenta:

- La copia de seguridad de iCloud no es una colaboración en tiempo real.
- Los archivos PDF grandes pueden tardar más en cargarse y restaurarse.
- No elimine el proyecto o PDF del dispositivo original antes de que finalice la restauración.
- Es posible que las copias de seguridad más antiguas de bases de datos no contengan el PDF original.

## Preguntas frecuentes

### ¿Por qué no puedo desplazarme por el PDF después de seleccionar un componente?

Los gestos de los componentes tienen prioridad dentro del área de impacto del componente. Toque un área vacía, cambie al modo Mover o comience a hacer zoom en el PDF para borrar la selección.

### ¿Por qué el borrador no puede eliminar una regla o un texto?

El borrador solo maneja pinceladas. Utilice el botón Eliminar del componente o Elementos para otros elementos.

### ¿Por qué una regla bloqueada aún puede moverse?

Es necesario reposicionar las reglas siguiendo un patrón. El bloqueo conserva su tamaño, ángulo y estilo, mientras que otros componentes bloqueados permanecen completamente fijos.

### ¿Por qué toco la página después de elegir un componente?

El flujo de trabajo de elegir y colocar agrega el componente exactamente donde se necesita y evita moverlo posteriormente del centro de la página.

### ¿Por qué algunas funciones muestran un mensaje de membresía?

La versión gratuita admite importación básica, lectura y uso limitado. Las acciones avanzadas, como agregar componentes de página o crear más ajustes preestablecidos de pincel, requieren membresía.
