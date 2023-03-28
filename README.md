# ROCAS by 0wulf
## Propósito
Este proyecto tiene como objetivo presentar una colección de rocas y minerales de una manera simple pero a la vez artística. Así, el usuario puede navegar por la colección y ver las características de cada roca o mineral.
## Connsideraciones de diseño
- Iterando, encontré más atractivo utilizar una disposición de fichas de tipo `table` en vez de `grid` o `flexbox`. De todas formas, `grid` se utiliza en `index.html`.
- Se agregó un archivo `main.css` para el estilo general de la página.
- Forzadamente no se utilizó ni Bootstrap ni Bulma.
- Asimismo, no se utilizó JavaScript.
## Uso de cada _feature_ y navegación
El usuario entra al sitio a través de la página principal `index.html`. En esta página se muestran tres de las fotos de rocas y minerales. Al hacer click en cualquiera de ellas, no pasa nada. Al hacer hover sobre los textos que la acompañan hay un efecto de cambio de color y sobreado naranja. Al hacer click en el texto no pasa nada. Fijada arriba relativamente, se encontrará en todas las vistas la navbar. Al hacer click en Inicio, conduce a `index.html`, al hacer click en Acerca de se dirige a `about.html`. Al hacer click en Rocas conduce a `rocks.html`. Los _anchors_ cambian de `background-color` en hover. La página `rocks.html` muestra una tabla de cartas de rocas y minerales. Cada carta muestra el nombre que le he puesto a la roca, los minerales que creo reconocer y una imágen de la misma. Borde y sombreado. Al hacer hover en la imagen esta aumenta de `height` y muestra mejor la imagen. Los estilos css de la página contienen media queries para asegurar la responsividad de la página hasta un ancho de 450px como máximo aproximado.

## Instalación
No es necesario instalar nada para poder ver el sitio. Se puede ver en cualquier navegador web que soporte HTML5 y CSS3.