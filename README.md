

¿Qué es el Frontend?
Toda la parte visible por el usuario está abarcada por el Frontend. Podemos iniciar desde simples Mockups hasta con prototipos en Figma. 
Acá incluso pueden intervenir personas expertas en UX/UI para ayudarnos a diseñar la mejor interfaz. 

Los lenguajes más básicos que se deben dominar en el Frontend son los tres lenguajes estrella: 
- HTML
- CSS
- JS

¿Qués HTML? Lenguaje de Marcado de Hipertexto
Código que te ayuda a estructurar. 
Es el lenguaje con el cual le dices a tu computadora que ponga algo en tu navegador. HTML es la parte sencilla, puedes aprender su sintáxis y las diversas etiquetas que lo conforma. Gracias a HTML puedes definir la estructura de cualquier página. Pero no solo basta con aprenderse las etiquetas de HTML. También necesitamos aprender sobre accesibilidad, ya que una página web debe poder ser usada por cualquier usuario. 
También debemos aprender a cómo escribir HTML semántico, es decir, HTML que tenga sentido. Aprender a usar las etiquetas correctas en el lugar correcto es fundamental.

¿Qués es CSS? - Hojas de estilo en cascada
Lenguaje que le da vida a tu esqueletito: colores, tamaños, ubicaciones y más.
Lo más importante es aprender a cómo seleccionar elementos de tu HTML desde CSS. Tenemos varios tipos de selectores, y podemos combinarlos. Es importante aprender sobre ciertas técnicas de alineación con CSS, y una de las más comunes es FlexBox y CSS Grid.
![Screen Shot 2023-08-07 at 18 19 49](https://github.com/Amairanicr15/curso-1er-pagweb/assets/99575046/96c250a9-6730-4e47-81eb-5d06f4457e75)# curso-1er-pagweb

Y una de las mejores cosas que tiene CSS es la posibilidad de crear transiciones y animaciones, esto le da un plus a nuestra página y la hace más dinámica para el usuario.
Responsive tu página también debe adaptarse a cualquier tamaño de pantalla, es por ello que el responsive design es muy importante, sobre todo trabajar con Mobile First.

JavaScript es un universo gigante. 

Motores de renderizado - 
Son programas que traducen nuestro código en un lenguaje que entienda el navegador, de esta manera el programa sabrá que es lo que tiene que mostrar por pantalla al usuario.
Los navegadores tienen sus propios motores:
Navegador ----------> Motor
Chrome ----------> Blink
Edge ----------> Edge HTML
Safari ----------> Webkit
Firefox ----------> Gecko
Todos realizan esta compilación de manera diferente, pero con el mismo resultado, es decir, convierten los archivos a píxeles.

PROCESO DE RENDERIZADO DEL MOTOR DEL NAVEGADOR
El motor del navegador realiza 5 pasos o procesos para compilar nuestro código hasta el renderizado por pantalla. Estos pasos son los siguientes:
1. Transforma los archivos a un árbol de objetos HTML o CSS, estos se denominan DOM(Document Object Model) y CSSDOM(Cascade Style Sheet Object Model), respectivamente. Cada nodo en el árbol es un representación de los elementos que contiene el archivo HTML o CSS. 
2. Calcula el estilo correspondiente a cada nodo DOM relacionado al CSSDOM
3. Calcula las dimensiones de cada nodo y donde va en la pantalla
4. Pinta o renderiza las diferentes elementos como cajas o contenedores.
5. Agrupa todas las cajas en diferentes capas para convertirlas en una imagen que se renderiza en pantalla.



ANATOMÍA DE UN DOCUMENTO HTML Y SUS ELEMENTOS 
Los elementos son cada una de las partes que conforman un archivo HTML. Su estructura contiene:
* Etiquetas: es la representación de un elemento HTML. Se dividen en etiquetas de apertura, representadas por <etiqueta> y etiquetas de cierre, representados por </etiqueta>
* Contenido: es el texto o elementos encerrados por la etiqueta, este valor es opcional en algunas de ellas.

Los atributos HTML son propiedades en la etiqueta de apertura que manejan el comportamiento del elemento. Su valor está envuelto en comillas.

Los elementos vacíos son aquellos que únicamente se representan en una etiqueta de apertura. Por ejemplo, la etiqueta <img...> Estas etiquetas pueden cerrarse en la misma etiqueta de apertura, utilizando la barra inclinada "/" al final: <img.../>

El anidamiento de elementos HTML consiste en envolver varias etiquetas en otras etiquetas.

Interpreta a cada elemento HTML como una caja onde puedes guardar diferentes elementos u otras cajas. Estas cajas tendrán diferentes tamaños y estarán colocadas junto a otras. 

/* Aquellas etiquetas que envuelven a otras se las denomina "padres". Es decir, <section> es padre del h1, p, ul, y a su vez ul es padre de 3 etiquetas li. */

Las etiquetas que son el contenido de otras, se las denomina "hijos". Es decir, las etiquetas h1, p, ul son hijos de section, y a su vez las etiquetas li son hijos de ul.

La estructura básica de un documento HTML está configurado por las siguientes etiquetas principales:
* Etiqueta Doctype - La etiqueta <!DOCTYPE html> especifica que el archivo se maneje con la versión 5 de HTML. 
* Etiqueta html - La etiqueta <html> define el elemento raíz de un documento HTML. Todos los demás elementos deben estar contenidos dentro de este elemento raíz. En esta etiqueta se especifica el lenguaje de la página web mediante la propiedad lang.
* Etiqueta head - La etiqueta <head> define la metainformación, es decir, toda información que no es contenido como tal de la página web. Por ejemplo, los enlaces a archivos CSS y JavaScript, el titulo y la imagen que aparecen en la pestaña del navegador. Eso es importante para motores de búsqueda como Google.
* Etiqueta body - La etiqueta <body> define el contenido de la página web. Debe ser hijo cercano de <html> y padre de todas las etiquetas HTML, exepto por aquellas que definan metainformación.
* Los comentarios de HTML consisten en señalar algo que se ignorará. Para establecer un comentario HTML se lo envuelve entre <!--- y --->, independiente de la cantidad de líneas.
              <!-- Este es un comentario de una línea -->
              <!-- Este es un comentario de varias lineas
              -->
¿QUÉ ES HTML SEMÁNTICO?
El HTML semático consiste en que cada elemento tenga. supropia etiqueta que lo defina correctamente. Sin utilizar etiquetas muy generales, como <div> o <span>.

El problema con la etiqueta div - define un bloque genérico de contenido, que no tiene ningún valor semántico. Se utiliza para elementos de diseño como contenedores. 

Las etiquetas semánticas para definir una interfaz de una página web son:
- <header>: define el encabezado de la página (noo confundir con <head>).
- <nav>: define una barra de navegación que incluye enlaces.
- <section>: define una sección de la página 
- <footer>: define un pie de página o de sección 
- <article>: define un articulo, el cual puede tener su propio encabezado, navegación, sección o pie de página. 

                *Evitar el uso excesivo de <div>*
Las ventajas de utilizar un HTML semántico son:
* Ayuda a tu sitio a ser accesible
* Mejora tu posicionamiento (SEO)
* Código más claro, legible y mantenible
* Ayuda a buscadpres (como Google) a encontrar tu página

Las etiquetas más utilizadas 
                                                 <div>
Layout:        Textos:           Formularios:      Enlaces:     Imágenes y video:     Listas:
- Header       - h1.... h6       -Form             - a           - img                 - ul
- Nav          - p                                               - svg                 - li
- Section      - span                                            - iFrame              - ol
- Article                                                         - Video    
- Aside          
- Footer

*** Una página para ver más etiquetas https://htmlreference.io/      
                 
** Para crear un archivo desde la terminal podemos usar el comando touch nombre.html
** Para ver la ruta donde estamos utilizamos el comando pwd
** Para hacer una carpeta desde la terminal usas take nombre

ANATOMÍA DE UNA DECLARACIÓN CSS: SELECTORES, PROPIEDADES Y VALORES 
Una declaración de CSS es un bloque que especifica el conjunto de estilos que se añadirán a un elemento HTML. Su estructura contiene lo siguiente: 
- Selector: define el elemento o conjunto de elementos a los cuales se añadiran los estilos.
- Propiedad: es el nombre del estilo de CSS
- Valor: es el valor que tomará la propiedad.

Los comentarios de CSS consisten en señalar algo que se ignorará. Para establecer un comentario CSS se lo envuelve entre /* y */, independiente de la cantidad de líneas.
      /* Este es un comentario de una línea */
      /*
      Este es un comentario de varias líneas 
      */
Propiedades iniciales de CSS 
- color: establece el color del texto de un elemento
- background-color: establece un color de fondo al elemento
- font-size: establece el tamaño de la fuente
- width: establece la anchura de un elemento
- height: establece la altura de un elemento

Las medidas iniciales para establecer tamaños de elementos o de tipografia:
- px: establece una longitud de pixelex
- ‰: establece un porcentaje con respecto a una medida base

TIPOS DE SELECTORES Y COMBINADORES
El selector define el elemento o conjunto de elementos HTML a los cuales se añadiran estilos. Existen nombres de colores propios de CSS que puedes expllorar.
Un selector básico es la mínima exxpresión CSS para colocar estilos. 
selector {
    /* Estilos */
}
- de tipo: div {...} - Selecciona todos los elementos que coincidan con el nombre de la etiqueta HTML
- de clase: .elemento{...} - Selecciona todos los elementos que coincidan con las eituqyetas HTML que contengan el atributo class
- de id: #id-del-elemento - Selecciona el único elemento que coincida con la etiqueta HTML que contenga el atributo id. Solo puede existir un valor id para todo el documento.
- de atributo: a[href="..."]{...} - Selecciona los elementos que coincidan con la etiqueta HTML que contenga el atributo y valor especificado
- universal: *{...} - Selecciona todos los elementos del coumento mediante un asterisco *.

Selectores combinadores 
* Descendientes - div p Selecciona todos los elementos del selector de la derecha que son hijos del selector de la izquierda, independientemente de la profundidad. Estos selectores están separados por un espacio. 
* Hijo directo - div > p Selecciona todos los elementos del selector de la derecha que son hijos directos del selector de la izquierda. Estos selectores están separados por >.
* Elemento adyacente - div + p Selecciona todos los elementos del selector de la derecha que están adyacente al selector de la izquierda. Estos selectores están separados por +.
* General de Hermanos - div ~ p Selecciona todos los elementos del selector de la derecha que son hermanos del selector de la izquierda. Estos selectores están separados por ~.


SELECTORES PSEUDOCLASES Y PSEUDOELEMENTOS 
Existen otros tipso de selectores, además de los selectores básicos y combinadores, capaces de cambiar un estado o añadir algo más al elemento. Estos son denominados pseudoclases o pseudoelementos. 

Los pseudoclases define el estilo de un estado especial de un elemento.
Sintaxis 
          selector : pseudoclase {
          propiedad: valor;
          }
- :hover representa el estado en el cual el cursor está encima del elemento
- :active Representa el estado de un elemento que no ha sido visitado
- :visited Representa el estado de un elemento que ya ha sido visitado
- :not() Representa el estado en el cual no coinciden los selectores que se indiquen
- :nth-child() Representa el estado en el cual coinciden los hijos del elemento según el valor indicado
      Valores de palabras clave
      * old: los elementos hijos en posiciones impares
      * even: los elementos hijos en posiciones pares
  Fórmula matemática: An+B donde A y B son número enteros

  Los pseudoelementos define el estilo de una parte específica de un elemento.
  Sintaxis
            selector : pseudo-elemento {
            propiedad: valor;
            }
- ::before Sirve para agregar un contenido antes del elemento. El contenido es agregado mediante la propiedad content de CSS.
- ::after Sirve para agregar un contenido después del elemento. El contenido es agregado mediante la propiedad content de CSS
- ::first.letter Sirve para añadir estilos a la primera letra del texto de cualquier elemento.

CASCADA Y ESPECIFICIDAD CSS
La cascada es el concepto que determina qué estilos se colocan sobre otros, priorizando a aquellos que se encuentran más abajo del código. CSS es la abreviación de Cascade Style Sheets, que traducido es hojas de estilos e Cascada.
C - Cascading: significa que el orden de las reglas en CSS importa
S - Style
S - Sheet

La especificidad consiste en dar un vaalor a una regla CSS sobre qué tan específico es el estilo, esto para que los navegadores puedan saber qué estilos aplicar sobre otros, independientemente de dónde se encuentren en el código. El estilo se apliará donde la especificidad sea mayor. 
Existen 6 tipos de especificidad con su respectivo valor, donde x es la cantidad de estilos que lo contienen.
1. !important Es un valor de toda propiedad CSS que provee una especificidad de 10000, por lo que se aplicará ante otros estilos. Esto es una mala practica: h1 { color: red !important; }
2. estilos en línea Son las propiedades CSS escritas en el HTML a través de la propiedad style de toda etiqueta. Mala práctica; h1 style="color: blue;">Especificidad</h1
3. #id Son más especificos que las clases, atributos y pseudoclases. Estas últimas son más específicas que los elementos y pseudoelementos. El selector universal tiene una especificidad de 0.
4. clases, atributos y pseudoclases
5. elementos y pseudoelementos
6. selector universal

La propiedad display establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos.
Hay etiquetas que por defecto su display ya está determinado, como la etiqueta div que tiene display block, span tiene display inline y button tiene display inline-block 

-Visualización en bloque (block): establece que un elemento ocupará todo el espacio disponible por defecto y el siguiente elemento a este se situará por debajo. Es posible añadir medidas de anchura width y altura height a estos elementos. Tambien es posible agregar todas las propiedades del modelo de caja.
-Visualización en línea (inline): El display inline establece que un elemento ocupará el espacio del contenido del mismo y el siguiente elemento se situará a la derecha. No es posible añadir medidas de anchura width y altura height a estos elementos. También, no es posible agregar todas las propiedades del modelo de caja, únicamente funcionará la propiedad margin en el eje horizontal. 
- Visualización de bloque y línea (inline-block): El display inline-block combina las ventajas de bloque de colocar medidades al elemento y propiedades del modelo de caja correctamente, con las ventajas de inline de color un elemento seguido de otro en el mismo espacio. Si el elemento excede el contenido total, se coloca en la siguiente línea por debajo.
- Visualización nula (none): El display none desactiva la visualización de un elemento, como si el elemento no existiera.
- 

El display flex y grid son formas de visualización de elementos recientes y cada uno tienen sus propias características para crear interfaces de manera efectiva efectiva, a partir de un contenedor padre que dotará a los elementos hijos de superpoderes del posicionamiento. 
Ambas son herramientas muy útiles en el desarrollo , especialmente para la creación de interfaces amigables al usuario y aptas para cualquier dispositivo, que este último se le conoce como responsive design. 

FLEXBOX
Consiste en el ordenamiento de elementos hijos en un solo eje, por defecto horizontalmente. El elemento padre. ocontenedor deberá contener la propiedad display con el valor flex. A partir de aqui, ya puedes ordenar los hijos según sea necesario.


MODELO DE CAJA 
