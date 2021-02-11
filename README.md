# Programa 01. CSS3

## Pasos a seguir

1. Clone su repositorio asignado usando **git clone** en la carpeta donde usted desee

2. Modifique el contenido del repositorio de acuerdo a lo indicado en la secciones de Instrucciones para Inicializar el Proyecto e Instrucciones para Completar el Proyecto

3. Conforme vaya realizando los cambios indicados en la sección Instrucciones para Completar el Proyecto, registre tales cambios de manera atómica usando **git add** y **git commit**. Recuerde que un commit es atómico si solo incluye el archivo donde se hizo el cambio y no incluye en el mismo commit varias modificaciones. Al hacer los commit especifique un mensaje breve que deje claro el trabajo realizado.

4. Al final, haga push de sus cambios al repositorio remoto usando **git push**. Si desea, puede estar haciendo push esporádicamente aunque no haya finalizado su trabajo para mantener una copia de su trabajo en el repositorio remoto.

## Instrucciones Para Inicializar el Proyecto

Para esta programa, se conjuntará el trabaja realizado en las actividades 02 y 03, y se agregará un archivo CSS que defina las reglas de estilo a aplicarse a todos los archivos HTML. 

1. Copiar en la carpeta de este repositorio los archivos **index.html**, **estudios.html**, **favoritas.html**, **intereses.html** así como la carpeta **imagenes** (incluyendo la foto propia que de contener) que realizó para la actividad 03.
2. Copiar en la carpeta de este repositorio el archivo **catalogopeliculas.html** que realizó en la actividad 04
3. Edite el archivo **index.html** para que le agregue un hiperenlace que le lleve al archivo **catalogopeliculas.html** y que tenga como texto `Catálogo de Películas`
4. Haga un commit con que incluya estos archivos 5 archivos y la carpeta imágenes con el mensaje `Inicialización de Archivos para Programa 01`

## Instrucciones Para Completar el Proyecto

1. En los archivos **estudios.html**, **favoritas.html**, **intereses.html** y **catalogopeliculas.html**, agregue justo del final del **body**, una liga(hiperenlace) a la página index.html, con el texto **Inicio**. Tal hiperenlace deberá estar contenido dentro de una etiqueta div que sea de clase **retorno**.

2. Debe agregar los estilos a las 5 páginas HTML de acuerdo a las siguientes indicaciones:
   - Todas las páginas deben tener en la esquina superior izquierda el texto `Desarrollado por XYZ` donde X, Y y Z son las iniciales del primer nombre, apellido paterno y apellido materno del autor de la página. Este texto deberá estar contenido dentro de una etiqueta div con un id `autor`. La ubicación de este texto deberá ser siempre el mismo, es decir, independientemente de que se hiciera scrolling en la página, siempre debe mantenerse en la esquina superior izquierda (verifique que así es reduciendo el tamaño del navegador hasta que pueda hacer scrolling), por lo que su posicionamiento deberá ser controlado con propiedades CSS. Esta parte implica investigar en Internet como lograr este tipo de posicionamiento.
   - Genere un documento CSS externo de nombre **estilos.css** (a colocarse en la carpeta **estilos**) que será aplicado a todas las páginas HTML y que contendrá las siguientes reglas:
     a) Los elementos **h1** deben ser con tipo de letra Arial, estilo itálico, en negrita y de tamaño 220% del normal
     b) Los elementos **h2** deben ser con tipo de letra Arial, en negrita y de tamaño 180% del normal
     c) Las imágenes deben tener un borde de 2 pixeles de color azul con estilo dashed
     d) Los hiperenlaces deben comportarse de la siguiente manera:
        - Normalmente deben ser de color azul
        - Al pasar el mouse encima del hiperenlace debe desaparecer el subrayado del hiperenlace y cambiar a color verde
        - Un enlace visitado debe ser de color rojo y con texto itálico
        - Al dar click en un hiperenlace, este debe cambiar a color amarillo y debe aparecer un borde de 1 pixel de grueso de color negro de estilo dotted
     e) En las listas de definiciones, el término debe aparecer con letra negrita y subrayado y las definiciones con letra itálica 
     f) En las listas ordenadas, el número de cada elemento debe estar en romano
     g) En las listas sin orden, la viñeta a la derecha de cada elemento debe ser un cuadrado
     h) Los elementos de clase **retorno** deberán tener un color de fondo gris y con un borde rojo de 1 pixel estilo double, y el texto deberá estar centrado y de tamaño 85% del normal.
     i) Los bordes de la etiqueta **table** deberán ser de color negro, de 2 pixeles de grueso estilo solid
     j) Los bordes de la etiqueta **th** deberán ser de color azul, de 2 pixeles de grueso estilo solid
     k) Los bordes de la etiqueta **td** deberán ser de color negro, de 1 pixel de grueso estilo dotted
     l) Los elementos de la clase **centrado** deberán estar centrados horizontalmente
     m) Las formas deberán tener un borde negro de estilo solid de 3 pixeles de ancho
     n) El elemento con id `autor` deberá tener las siguientes características:
        - un color de fondo formado a partir de los datos de su fecha de nacimiento, así, si por ejemplo su fecha es el 17 de mayo de 1991, el color debería ser #170591 donde los primeros dos dígitos son el día (17), los siguientes dos son el mes (05) y los últimos dos son los últimos dos dígitos del año de nacimiento (91)
        - el color del texto deberá ser formado de tal manera que haga contraste con el color de fondo resultante y pueda ser visible
        - el texto en esta clase deberá estar alineado a la izquierda, de tamaño 50% del normal y subrayado
        - el borde deberá ser del mismo color que el texto, con una anchura de 1 pixel y de estilo dashed
        - la posición será siempre en la esquina superior izquierda de la ventana, por lo cual deberá usar ciertas propiedades de CSS que deberá investigar.
     o) Las páginas deberán sólo abarcar el 90% del ancho del navegador de páginas y esta área deberá estar centrada en el navegador
3. Asegúrese que todos los archivos (los HTML y el CSS) contengan su nombre y matrícula como comentario (recuerde que los comentarios son distintos en HTML que en CSS)

4. Todas las páginas HTML5 deben haber sido validadas (use el validador que se encuentra en https://validator.w3.org/), es decir, el validador no debe reportar errores en las páginas
5. El archivo estilos.css debe haber sido validado usando https://jigsaw.w3.org/css-validator, es decir, el validador no debe reportar errores en el archivo estilos.css

