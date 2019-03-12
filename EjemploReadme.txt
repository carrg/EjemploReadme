Ejemplos
Texto
Es bastante sencillo convertir algunas palabras en **negritas** y otras en *italicas* con Markdown. Incluso puedes hacer un [link a Google](http://google.com\).
Es bastante sencillo convertir algunas palabras en negritas y otras en italicas con Markdown. Incluso puedes hacer un link a Google.
Sintaxis básica
Aquí un resumen de la sintaxis de Markdown que puedes utilizar en cualquier lugar de GitHub.com o en tus archivos de texto.

Encabezados
# Este es una etiqueta <h1>
## Este es una etiqueta <h2>
###### Este es una etiqueta <h6>
Énfasis
*Este texto estará en itálica*
_Este texto también estará en itálica_

**Este texto estará en negritas**
__Este texto también estará en negritas__

*Incluso **puedes** combinarlos*
Listas
Desordenadas
* Item 1
* Item 2
    * Item 2a
    * Item 2b
Ordenadas
1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b
Imágenes
![GitHub Logo](/images/logo.png)
Formato:

![Atributo Alt](url "Atributo title Opcional")
Links
1. http://github.com - ¡link automático!

2. [GitHub](http://github.com)

3. [GitHub][id]

4. [GitHub][]
Link automático - Cualquier dirección explicita será convertida en un link.
Link en-línea - [Texto del Link](url).
Link por-referencia - [Texto del Link][id]. el id necesitará ser declarado en otra parte del documento así: [id]: url.
Link por-referencia automática - El id es el "Texto del Link", y también necesita ser declarado en otra parte del documento de igual manera que el "link por-referencia".
Citas
Esto es un párrafo normal:

> Y aquí está la cita que puede
> seguir en varios renglones, y tener anidado más
> > citas así, con un doble signo mayor-que.
Código en-línea
Creo que debería utilizar una etiqueta `<addr>` aquí.