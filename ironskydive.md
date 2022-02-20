# Elementos de línea

## Objetivos

Después de ésta lección aprenderás a:

* Entender perfectamente los elementos de línea
* Conocer el uso de la etiqueta `<span>`

## Introducción

Los elementos HTML son los componentes básicos de cualquier página web. En la mayoría de los casos, tendrá cientos de estos componentes en una sola página.

Estas páginas están compuestas de elementos de línea y de elementos de bloque.

En esta lección, aprenderás a utilizar los elementos en línea.

## Elementos de línea

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_204ec773d202cb71b80805ea60a3269f.png)

Los elementos en línea se "despliegan" como texto continuo. No comienzan una nueva línea y se muestran justo al lado del elemento anterior.

<iframe height='265' scrolling='no' title='ERqmNb' src='//codepen.io/HarlandLohora/embed/ERqmNb/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/HarlandLohora/pen/ERqmNb/'>ERqmNb</a> by Harland Yatzet Lohora Espinoza (<a href='https://codepen.io/HarlandLohora'>@HarlandLohora</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Además, un elemento en línea ocupará solo el tamaño de su contenido:

<iframe height='265' scrolling='no' title='span' src='//codepen.io/HarlandLohora/embed/xzvdPj/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/HarlandLohora/pen/xzvdPj/'>span</a> by Harland Yatzet Lohora Espinoza (<a href='https://codepen.io/HarlandLohora'>@HarlandLohora</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## Etiqueta `<img>` para imagenes


La etiqueta de imagen (<img src = "some_img.png">) es un elemento que representa una imagen en el HTML.

### Atributos

- alt : Texto que se mostrará en caso de poder encontrar la imagen.
- src : Es la ruta o URL de la imagen que se desea mostrar. La URL puede apuntar a alguna imagen local o externa.

<iframe height='265' scrolling='no' title='Ironhack <img>' src='//codepen.io/HarlandLohora/embed/KeOmxW/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/HarlandLohora/pen/KeOmxW/'>Ironhack &lt;img&rt;</a> by Harland Yatzet Lohora Espinoza (<a href='https://codepen.io/HarlandLohora'>@HarlandLohora</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Si se desea usar una imagen local debera ser:

> <img src="ironhack.png">

## Etiqueta de enlace


Las etiquetas de enlace son el fundamento del Internet. Fueron una de las primeras etiquetas en la especificación HTML original, y son vitales para desarrollar una aplicación web de calidad porque vinculan al usuario de un documento o URL a otro.

Un ejemplo de etiqueta de enlace al sitio web de Ironhack.

> <a href="https://www.ironhack.com/es" alt="Ironhack"/>Ir a IronHack</a>

- `<a></a>` es la etiqueta de enlace, por si misma no hace mucho ya que requiere de la siguiente propiedad.

- href, contiene el hiperenlace, es decir, la ubicación o URL a la cual se dirigirá.

- "Ir a Ironhack" es el texto azul el cual al darle click nos llevará al sitio de Ironhack.

Los enlaces pueden hiperlazar a:

- Archivos en la computadora.
- Direcciones URL internas o externas del servidor.
- Una sección específica del mismo sitio web.

Veamos las primeras dos:

<iframe height='265' scrolling='no' title='QBLZOw' src='//codepen.io/HarlandLohora/embed/QBLZOw/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/HarlandLohora/pen/QBLZOw/'>QBLZOw</a> by Harland Yatzet Lohora Espinoza (<a href='https://codepen.io/HarlandLohora'>@HarlandLohora</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>


Y por último, haciendo referencia a los elementos en el mismo sitio web utilizando los id:

<iframe height='265' scrolling='no' title='Enlaces mismo sitio' src='//codepen.io/HarlandLohora/embed/RBbedd/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/HarlandLohora/pen/RBbedd/'>Enlaces mismo sitio</a> by Harland Yatzet Lohora Espinoza (<a href='https://codepen.io/HarlandLohora'>@HarlandLohora</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## Etiqueta `<span>`

La etiqueta `<span>` es una etiqueta de linea, la cual encierra texto. Es muy usado para dar estilo específico a ciertas partes del texto. La etiqueta `<span>` no tiene sentido semántico.

<iframe height='265' scrolling='no' title='span' src='//codepen.io/HarlandLohora/embed/NBKEGr/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/HarlandLohora/pen/NBKEGr/'>span</a> by Harland Yatzet Lohora Espinoza (<a href='https://codepen.io/HarlandLohora'>@HarlandLohora</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>


Otras etiquetas de HTML en línea son <strong>, <i> y <button> los cuales tienen un significado semántico, ayudan a que algún elemento adquiera propiedades dependiendo de la etiqueta.

Por ejemplo, `<strong>` es una etiqueta que acentúa algún texto: "Este contenido es <strong>muy importante</strong>".

`<em>`, pone énfasis en el texto que encierre.

## Elementos en línea

|Nombre|Descripción|
|---|---|
|a|
Es un enlace utilizado para navegar a diferentes páginas, o a un lugar diferente en la misma página.|
|br|
Denota un salto de línea que es parte del contenido. Por ejemplo, en un poema donde una línea siempre debe romperse después de otra.
|em|Texto en cursiva que pretende enfatizar el texto contenido.|
|small|
Se usa para comentarios laterales o texto de letra pequeña.|
|i|Texto en cursiva|
|b|
Texto en negrita. No está destinado a poner un significado semántico en el texto, es simplemente estilístico. Un ejemplo común es el nombre de un producto en un sitio de comercio electrónico.|
|strong|
Indica que el contenido contenido dentro es muy importante.|

## Ejercicio IronSkydive | Elementos de línea

En la segunda iteración del ejercicio, vas a trabajar con los elementos en línea que acabas de aprender. Has visto que se usan diferentes etiquetas con diferentes objetivos. Recuerda, esta es la estructura de proyecto actual:

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)


Vas a agregar diferentes elementos en línea a todas las secciones que ya tenemos. Abre el Codepen que haz usó para crear la primera iteración del proyecto, y hagamos las diferentes secciones que tenemos.

## Nav


La etiqueta <nav> se usa para ajustar los enlaces de nuestros sitios web. Ahora mismo solo tenemos una lista de elementos. Cambiemos esto, agregando enlaces en cada elemento de la lista.


Debe crear tres enlaces diferentes, que apuntarán a #plandeldia, #equipo y #programa, respectivamente:

> <a href='#plandeldia'>Plan del día</a>

## Encabezado

El encabezado del proyecto está incompleto. En primer lugar, deberás agregar un logotipo al encabezado. Además, agrega una cita de relleno.

Primero el logo. Agrega una imagen dentro del `<h1>` cargando la siguiente imagen `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironhack-skydive-logo.png` Recuerde agregar un texto alternativo descriptivo, en caso de que la imagen no se cargue. Una buena opción sería "IronSkydive Logo".


Es muy común encontrar citas en cursiva en diferentes lugares, así que esto es lo que vamos a hacer. Agregue la cita en cursiva (usando elementos en línea) dentro del elemento <aside>, con el texto "La mejor experiencia de nuestras vidas". En una nueva línea, otra vez usando elementos en línea, agregue el nombre del autor. En este caso, el nombre será "Ariel Quiónes y Gonzalo Manrique, fundadores de Ironhack".

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_0f0563ef2d64bd9a7bdf5d401bca9c16.png)

## Sección 1

En la primera sección del sitio web, tenemos tres artículos diferentes. Cada uno tiene una etiqueta <h3> y una etiqueta <p> dentro. Agreguemos un enlace debajo de cada párrafo. Este enlace no necesita apuntar a ningún lado.

> Ahora podemos crear un link sin un enlace específico o URL agregando un # en el href

> <a href='#'>Texto de enlace</a>

Agrega tres enlaces, uno en cada sección, en el siguiente orden:

- Aprender Más
- Ver video
- Registrarse

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_016b92205b14c5a93d86d324547cf86e.png)

## Sección 2

En esta sección, tenemos cuatro artículos diferentes que contienen la información sobre cómo se estructura un día típico en IronSkydive. Agreguemos algunos iconos descriptivos a cada sección.

Los diferentes iconos, que deberás agregar en el siguiente orden son:

* https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-training.png
* https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-get-ready.png
* https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-fly.png
* https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-jump.png


Recuerde agregar un texto descriptivo alternativo en el atributo alt. Cada una de las secciones será así:

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_815ec56a50d81eaa3d603c173f907178.png)

## Sección 3

Agreguemos la información del equipo en la sección. Deberías tener tres artículos diferentes sin ninguna información. Dentro de cada artículo agregará el nombre del miembro del equipo en negrita. Debajo del nombre, tendrá que agregar la foto del miembro del equipo. Puedes encontrar las imágenes aquí:

* Harold Rothstein, https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/team-1.jpg
* Susan Phillips, https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/team-2.jpg
* Taylor Roberts, https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/team-3.jpg

Las imágenes son enormes, ahora agregaremos dos atributos

* width, especifíca el ancho de la imagen. Especifícalo al 100%.
* height, especifíca la altura. Configuralo en 250px.

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_7eb630f4b03d10e2ddcccb77b86385c8.png)

Para finalizar con esta sección, agreguemos un <hr> entre el párrafo y la información de los miembros del equipo.

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ca525285c56161e0941bf1b103de89e2.png)

## Sección 4

No hay nada que hacer aquí.

Pié de página

Primero, agregaremos la dirección. En este momento, toda la información está en una línea. Usemos etiquetas <br> para separar las diferentes líneas de la dirección.

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cf1a7806a1a921e018aa46c428d67a17.png)

Finalmente, agregue enlaces a las redes sociales donde los usuarios pueden seguir a IronSkydive. Puedes crear enlaces vacíos (con el hash # en el atributo href) o agregar enlaces a las redes sociales. En ambos casos, se debe abrir una nueva pestaña cuando los usuarios hacen clic en los enlaces.

> Utiliza el atributo target para abrir una ventana nueva

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_27057afe7732d2b6f26ce69eb00a63ec.png)

/Diviertete codeando

## Resumen

En esta lección, ha aprendido más sobre los elementos en línea y cómo fluyen en la página HTML, y que estos elementos tendrán el mismo tamaño que su contenido.

También viste cómo insertar imágenes y una amplia variedad de etiquetas HTML semánticas.
