# Documentación con MarkDown

## Selectores CSS

Los selectores de CSS se utilizan para seleccionar los elementos HTML que quieres modificar.

Podemos dividir los selectores de CSS en cinco categorías:

| Selectores | Definición |
|------------|------------|
| Selectores simples | seleccionar elementos basados en nombre(body por ejemplo), id(#), clase(.) |
| Selectores combinadores | seleccionar elementos en función de una relación específica entre ellos |
| Selectores de pseudoclase | seleccionar elementos en función de un determinado estado |
| Selectores de pseudoelementos | seleccionar y diseñar una parte de un elemento |
| Selectores de atributos | seleccionar elementos en función de un atributo o valor de atributo |

_Este es un Selector de CSS de clase_

![](https://github.com/IkerCG2003/markdown/blob/main/css%20clase.png)

_Este es un Selector de CSS de ID_

![](https://github.com/IkerCG2003/markdown/blob/main/css%20id.png)

_Este es un Selector de CSS de nombre_

![](https://github.com/IkerCG2003/markdown/blob/main/css%20nombre.png)

_Descendiente (espacio)_

Se aplica a los elementos que están dentro de otro elemento (o más exactamente, un elemento que es descendiente de otro elemento). 

![](https://github.com/IkerCG2003/markdown/blob/main/descendiente.jpg)

_Hijo directo (<)_

Este selector actúa sobre todos aquellos elementos que sean hijos de otro elemento especificado, pero que se encuentren en el primer nivel, es decir, si están dentro de otro elemento hijo de ese mismo padre, no serán tomados en cuenta.

![](https://github.com/IkerCG2003/markdown/blob/main/hijo%20directo.png)

_Elemento adyacente (+)_

Este selector afecta a los elementos que, teniendo el mismo elemento como padre, estén inmediatamente seguidos uno de otro, esta relación se representa con el símbolo + entre los selectores. 

![](https://github.com/IkerCG2003/markdown/blob/main/adyacente.png)

_Elemento hermano (~)_

Este selector actúa sobre aquellos elementos que se encuentren precedidos por un elemento específico y que tengan como padre al mismo elemento, y se representa con el símbolo ~ entre los dos selectores.

![](https://github.com/IkerCG2003/markdown/blob/main/hermano.png)

# HTML file paths (indicar rutas de archivos)

Vamos a indicar una ruta partiendo del directorio principal del proyecto (.), y a partir de ahí indicamos la ruta siguiendo la estructura de carpetas. Debajo voy a poner un par de ejemplos.

| Ruta | Descripción |
|------|-------------|
| href="./css/styles.css" | indicamos que el archivo styles.css está dentro de la carpeta css |
| img src="images/picture.jpg" | indicamos que la imagen picture.jpg está dentro de la carpeta images |

# Navbar horizontal (Menú de navegación)

Este menú tiene un float:left para que los elementos **li** de la lista estén alineados a la izquierda.

![](https://github.com/IkerCG2003/markdown/blob/main/menu%20horizontal.png)

# Navbar vertical

Este menú sirve para viajar a ciertos puntos de una página web con un solo clic. Para hacerlo vamos a crear un índice con una lista ordenada (ol y li). Para hacer el vínculo ponemos dentro de la etiqueta **li** una **a** y el id de la parte a la que queremos ir con un nombre.
  
![](https://github.com/IkerCG2003/markdown/blob/main/men%C3%BA%20vertical.png)

Las clases que tiene ese html con para darle el formato que queremos al menú, pero no afectan en su funcionalidad.

# Alinea elementos

## Alinear elementos al centro

### Alinear texto al centro:

Para alinear el texto al centro tenemos que utilizar la regla text-align:center. También se pueden utilizar las reglas que se van a mostrar a coninuación para alinear items al centro.

![](https://github.com/IkerCG2003/markdown/blob/main/alinear%20texto%20al%20centro.png)

### Alinear imaágenes al centro:

Para alinear las imagenes se ponen las siguientes reglas para que esté correctamente sin desconfiguraciones.

![](https://github.com/IkerCG2003/markdown/blob/main/alinear%20imagen%20al%20centro.png)

# Smooth Scrolling (Desplazamiento Suave)

El desplazamiento suave se utiliza en los menús. Su principal función es que haya un efecto suave en lo que la página viaja de un punto a otro, y no vaya de golpe.

A continuación adjunto un video con un tutorial que explica como hacerlo. [clica para ver el video aquí](https://www.youtube.com/watch?v=MNNr7TU7XcU).

# 

