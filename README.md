| Elemento              | Descripción |
|------------------------|-------------|
| **Subir video**        | Como guía quiero poder subir un video desde la aplicación web para compartirlo con otros usuarios y que aparezca en la galería de videos. |
| **Criterios de aceptación** | |
|                        | Debe existir un botón visible con el texto **"Subir video"** en la sección de galería, ubicado al final de la lista de videos o en una posición destacada. |
|                        | Al hacer clic en el botón, se abrirá un formulario o modal donde el guía podrá: seleccionar el archivo de video desde su dispositivo e ingresar un título para el video. |
|                        | El formulario debe validar que el título no esté vacío y que el video sea de un formato y tamaño permitido. |
|                        | Una vez completado, el usuario podrá confirmar la carga presionando un botón de **"Subir"**. |


| Criterio     | Revisión |
|--------------|----------|
| **Independiente** | La HU se centra únicamente en la funcionalidad de subir videos a la galería, sin depender de que otras HU estén implementadas. |
| **Negociable**    | Se pueden negociar aspectos como los campos obligatorios del formulario (por ejemplo, si la miniatura es opcional) o los formatos y tamaños permitidos. |
| **Valiosa**       | Aporta valor al permitir que los guías agreguen contenido nuevo a la galería, aumentando el dinamismo y la interacción en la plataforma. |
| **Estimable**     | El alcance es claro y permite estimar un tiempo de desarrollo ajustado, que podría ser de unos pocos días dependiendo de la validación y el procesamiento de archivos. |
| **Pequeña**       | Está acotada para que se pueda desarrollar de manera independiente y sin abarcar procesos demasiado extensos, facilitando su entrega rápida. |
| **Testeable**     | Es fácil de probar subiendo videos de distintos formatos y tamaños, verificando que se guarden correctamente y aparezcan en la galería. |


| Elemento              | Descripción |
|------------------------|-------------|
| **Código**             | HUG - 02 |
| **Responder preguntas** | Como guía quiero poder responder preguntas dentro del blog para comunicarme de manera clara y rápida con otros usuarios. |
| **Criterios de aceptación** | |
|                        | La interfaz del blog debe mostrar las preguntas hechas por los usuarios. |
|                        | Cada pregunta debe incluir el texto del mensaje y, opcionalmente, la hora en la que fue enviado. |
|                        | La interfaz debe actualizarse con las nuevas preguntas cada vez que se recargue la página. |
|                        | Al lado de cada pregunta debe de haber un botón para que el guía pueda responder. |
|                        | Al presionar el botón para responder preguntas, debe aparecer un formulario en el cual se encuentra un cuadro de texto para responder. |
|                        | Al enviar la respuesta, esta debe aparecer debajo de la imagen en el blog. |


| Criterio     | Revisión |
|--------------|----------|
| **Independiente** | La HU se enfoca exclusivamente en la funcionalidad de responder preguntas en el blog, sin depender de otras funcionalidades como adjuntar archivos. |
| **Negociable**    | Se pueden negociar aspectos como la actualización de las preguntas en tiempo real, mostrar u ocultar la hora de cada pregunta o soportar mensajes multimedia. |
| **Valiosa**       | Aporta valor al permitir una comunicación directa, mejorando la interacción entre usuarios y guías. |
| **Estimable**     | El alcance es claro y puede estimarse en un plazo corto. |
| **Pequeña**       | Está acotada para desarrollarse de forma independiente, sin involucrar funcionalidades complejas de otras HU, lo que facilita su entrega incremental. |
| **Testeable**     | Puede probarse fácilmente enviando y respondiendo preguntas, validando su aparición inmediata en la interfaz y comprobando la adaptación a distintos dispositivos. |


| Elemento              | Descripción |
|------------------------|-------------|
| **Código**             | HUG - 03 |
| **Crear blog**         | Yo como guía quiero poder crear blogs para documentar, organizar y compartir las experiencias o actividades con los usuarios, añadiendo entradas, modificando información y publicando el contenido cuando esté listo. |
| **Criterios de aceptación** | |
|                        | Debe existir una sección con el título **“Crear blog”** que muestre tres botones: Publicar, Nueva entrada y Modificar información. |
|                        | El botón **Publicar** debe permitir al guía publicar el blog completo y mostrar un mensaje de confirmación o error según el resultado. |
|                        | El botón **Modificar información** debe permitir al guía editar detalles como el título, descripción, etiquetas o imagen de portada del blog. |
|                        | El sistema debe validar que un vlog tenga al menos una entrada y un título antes de poder publicarlo. |
|                        | Al guardar cambios (ya sea una entrada nueva o la información editada), estos deben reflejarse inmediatamente en la vista previa del vlog. |


| Criterio     | Revisión |
|--------------|----------|
| **Independiente** | La HU se centra únicamente en que el guía pueda crear, editar y publicar vlogs, sin depender de otras funcionalidades como gestión de usuarios o galería de videos. |
| **Negociable**    | Se pueden negociar detalles como el tipo de contenido permitido en las entradas (solo texto, o incluir imágenes y videos) y los campos que sean obligatorios antes de publicar. |
| **Valiosa**       | Aporta valor al permitir que el guía documente y comparta experiencias con los usuarios, enriqueciendo el contenido disponible en la plataforma. |
| **Estimable**     | El alcance de la HU es claro y puede estimarse para ser desarrollado en un plazo de pocos días, dependiendo del nivel de personalización del editor y validaciones. |
| **Pequeña**       | Está acotada para implementarse de forma independiente y entregarse en un único sprint sin sobrecargar el flujo de trabajo. |
| **Testeable**     | Se puede probar fácilmente creando vlogs de prueba, agregando entradas, modificando información y publicando, verificando que el contenido aparezca correctamente en la plataforma. |


| Elemento                     | Descripción |
|-----------------------------|-------------|
| **Código**                  | HUG - 04 |
| **Subir mapas interpretativos** | Yo como guía quiero poder subir mapas interpretativos a los blogs, para complementar la información de las publicaciones con recursos visuales que ayuden a los visitantes a orientarse y entender mejor el recorrido. |
| **Criterios de aceptación** | |
|                             | El sistema debe permitir al guía seleccionar un archivo de imagen (ej. PNG, JPG) desde su dispositivo y subirlo al blog. |
|                             | Al subirlo, el mapa debe quedar asociado a una entrada de blog específica. |
|                             | El guía debe poder reemplazar el mapa existente por uno nuevo en caso de actualización. |
|                             | El guía debe poder eliminar el mapa interpretativo si ya no es necesario. |
|                             | Solo los usuarios con rol de guía pueden subir, modificar o eliminar mapas interpretativos. |
|                             | Los visitantes solo podrán visualizar el mapa, no gestionarlo. |



| Criterio     | Revisión                                                                                                                                                                                                 |
|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Independiente | No depende directamente de otras (por ejemplo, puede existir aunque aún no estén las funciones de comentarios o de videos). Sin embargo, se relaciona con la gestión de blogs, ya que el mapa debe estar vinculado a una entrada de blog. |
| Negociable    | El alcance es flexible: se puede acordar si el mapa será interactivo (zoom, mover) o si inicialmente solo será una imagen estática. También se puede negociar si los visitantes podrán descargar el mapa. |
| Valiosa       | Aporta un valor directo tanto al guía (que puede enriquecer sus publicaciones) como a los visitantes (que entienden mejor el territorio y se orientan en el recorrido).                                |
| Estimable     | Es posible estimar el esfuerzo en función de tareas claras                                                                                                                                             |
| Pequeña       | Se centra en una única funcionalidad concreta (subida y gestión de mapas), que puede completarse dentro de un sprint sin dividirla aún más.                                                             |
| Testeable     | Los criterios de aceptación permiten verificar fácilmente. El guía puede subir un mapa. El visitante lo ve en la entrada.                                                                              |


