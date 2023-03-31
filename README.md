# ROCAS by 0wulf
## Propósito
Este proyecto tiene como objetivo presentar una colección de rocas y minerales de una manera simple pero a la vez artística. Así, el usuario puede navegar por la colección y ver las características de cada roca o mineral.
## Connsideraciones de diseño
- Se agregó un archivo `main.css` para el estilo general de la página.
- Forzadamente no se utilizó ni Bootstrap ni Bulma.
- Asimismo, no se utilizó JavaScript.
## Uso de cada _feature_ y navegación
<p style="text-align: justify;">
El usuario entra al sitio a través de la página principal <code>index.html</code>. En esta página se muestran tres de las fotos de rocas y minerales. Al hacer click en cualquiera de ellas, no pasa nada. Al hacer hover sobre los textos que la acompañan hay un efecto de cambio de color y sobreado naranja.
</p>
<p style="text-align: justify;">
 Al hacer click en el texto no pasa nada. Fijada arriba relativamente, se encontrará en todas las vistas la navbar. Al hacer click en Inicio, conduce a <code>index.html</code>, al hacer click en Acerca de se dirige a <code>about.html</code>. Al hacer click en Rocas conduce a <code>rocks.html</code>. Los <i>anchors</i> cambian de <code>background-color</code> en hover. 
</p>
<p style="text-align: justify;">
La página <code>rocks.html</code> muestra una tabla de cartas de rocas y minerales. Cada carta muestra el nombre que le he puesto a la roca, los minerales que creo reconocer y una imágen de la misma. Borde y sombreado. Al hacer hover en la imagen esta aumenta de <code>height</code> y muestra mejor la imagen. Los estilos css de la página contienen media queries para asegurar la responsividad de la página hasta un ancho de 450px como máximo aproximado.
</p>

## Instalación
No es necesario instalar nada para poder ver el sitio. Se puede ver en cualquier navegador web que soporte HTML5 y CSS3.
