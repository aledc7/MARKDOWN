# SAP-TFI-UAI-
Desarsrollo de la clase de GIT y GITHUB en la que se explicará que es GIT, que es GITHUB, ALternativas a GITHUB y Manejo de GIT.

Al finalizar esta clase cada uno deberá tener subido a git su proyecto y enviarlo por mail a SAPTFIUAI@GMAIL.COM


## Ejemplos de todo lo que se puede hacer con el lenguaje de github MARKDOWN




### Este es el Lenguaje MARKDOWN que vamos a utilizar en la clase de hoy 19-06-2018 para SAP.

####Resumen de la sintaxis Markdown

Markdown es un lenguaje de marcado ligero creado originalmente por John Gruber y Aaron Swartz que trata de conseguir la máxima legibilidad y "publicabilidad" tanto en sus forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano. Markdown convierte el texto marcado en documentos XHTML bien formados.

Nota: Este documento es una traducción del sitio oficial que está en Inglés daringfireball : basics.






# Titulo 1 <h1>
## Titulo 2 <h2>
### Titulo 3 <h3>
#### Titulo 4
##### Titulo 5 <h5>
###### Titulo 6 <h6>
  
  
  
  *Este texto estará en itálica*
_Este texto también estará en itálica_

**Este texto estará en negritas**
__Este texto también estará en negritas__

*Incluso **puedes** combinarlos*



Listas desordenadas

* Item 1
* Item 2
    * Item 2a
    * Item 2b
    
    
    
    
Listas Ordenadas

1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b
    
    
    
    
    Manejo de Imágenes:
    
    
![GitHub Logo](/images/logo.png)![GitHub




Manejo de Links

1. http://github.com - ¡link automático!

2. [GitHub](http://github.com)

3. [GitHub][id]

4. [GitHub][]



Link automático - Cualquier dirección explicita será convertida en un link.
Link en-línea - [Texto del Link](url).
Link por-referencia - [Texto del Link][id]. el id necesitará ser declarado en otra parte del documento así: [id]: url.
Link por-referencia automática - El id es el "Texto del Link", y también necesita ser declarado en otra parte del documento de igual manera que el "link por-referencia".



CITAS:

Esto es un párrafo normal:

> Y aquí está la cita que puede
> seguir en varios renglones, y tener anidado más
> > citas así, con un doble signo mayor-que.




Código en Linea

Creo que debería utilizar una etiqueta `<addr>` aquí.



MANEJO DE SINTAXIS


```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```


Identación estilo Python

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }



Lista de Tareas

- [x] Soporte de @menciones, #referencias, [links](), **formateo**, y de <del>etiquetas</del>
- [x] lista de sintaxis requerida (cualquier lista des-ordenada y ordenada es soportada)
- [x] esta es una tarea completa
- [ ] esta es una tarea incompleta



Para referenciar los famosos SHA:

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac





aca un tuto mucho ams completo sobre MARKDOWN:

https://github.com/ricval/Documentacion/blob/master/Markdown/daringfireball/basics.md










# PROFUNDIZANDO EN MARKDOWN


Markdown: Lo Básico
Resumen de la sintaxis Markdown
Párrafos, Encabezados, Blockquotes
Frases Enfatizadas
Listas
Links
Imágenes
Código
Resumen de la sintaxis Markdown
Markdown es un lenguaje de marcado ligero creado originalmente por John Gruber y Aaron Swartz que trata de conseguir la máxima legibilidad y "publicabilidad" tanto en sus forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano. Markdown convierte el texto marcado en documentos XHTML bien formados.

Nota: Este documento es una traducción del sitio oficial que está en Inglés daringfireball : basics.

Párrafos, Encabezados, Blockquotes
Un párrafo es una o más líneas de texto consecutivas, separadas por uno o más líneas en blanco. (Una línea en blanco es cualquier línea que se vea como una línea en blanco -- una línea que no contiene nada pero los espacios o tabulaciones son considerados espacios en blanco.) Un párrafo normal no debería ser identando con espacios o tabulaciones.

Markdown ofrece dos estilos de encabezados: Setext y atx. Encabezados estilo-Setext para <h1> y <h2> son creados "subrayando" con los caracteres de igual (=) o de guión (-), respectivamente. Para crear un encabezado estilo-atx, necesitas poner de 1-6 caracteres hash (#) al principio y final de la linea -- el número de caracteres hash equivale al nivel de encabezado HTML resultante.

Los Blockquotes son indicados usando estilo-email '>' carácter de mayor-que.

Markdown:

    Primer Nivel de Encabezado
    ==========================

    Segundo Nivel de Encabezado
    ---------------------------

    Ahora es el momento para todos los hombres
    buenos de venir a ayudar a su país. Este es
    sólo un párrafo normal.

    El ágil zorro café brinco sobre el lomo
    de un perro perezoso.

    ### Encabezado 3

    > Éste es un blockquote.
    >
    > Éste es el segundo párrafo en el blockquote.
    >
    > ## Éste es un H2 en un blockquote
Salida en código HTML:

    <h1>Primer Nivel de Encabezado</h1>

    <h2>Segundo Nivel de Encabezado</h2>

    <p>Ahora es el momento para todos los hombres
    buenos de venir a ayudar a su país. Este es
    solo un párrafo normal.</p>

    <p>El ágil zorro café brinco sobre el lomo
    de perro perezoso.</p>

    <h3>Encabezado 3</h3>

    <blockquote>
        <p>Éste es un blockquote.</p>

        <p>Éste es el segundo párrafo en el blockquote.</p>

        <h2>Éste es un H2 en un blockquote</h2>
    </blockquote>
Salida Renderizada:

Primer Nivel de Encabezado
Segundo Nivel de Encabezado
Ahora es el momento para todos los hombres buenos de venir a ayudar a su país. Este es sólo un párrafo normal.

El ágil zorro café brinco sobre el lomo de un perro perezoso.

Encabezado 3
Éste es un blockquote.

Éste es el segundo párrafo en el blockquote.

Éste es un H2 en un blockquote
Frases Enfatizadas
Markdown utiliza el asterisco * y el guión-bajo _ para indicar segmentos enfatizados.

Markdown:

    Algo de esas palabras *son enfatizadas*.
    Algo de esas palabras _son enfatizadas también_.

    Utilice dos asteriscos para **un enfatizado mayor**.
    O, si prefiere, __utilice dos guiones-bajos en su lugar__.
Salida HTML:

    <p>Algo de esas palabras <em>son enfatizadas</em>.
    Algo de esas palabras <em>son enfatizadas también</em>.</p>

    <p>Utilice dos asteriscos para <strong>strong emphasis</strong>.
    O, si prefiere, <strong>utilice dos guiones-bajos en su lugar</strong>.</p>
Salida Renderizada:

Algo de esas palabras son enfatizadas. Algo de esas palabras son enfatizadas también.

Utilice dos asteriscos para un enfatizado mayor. O, si prefiere, utilice dos guiones-bajos en su lugar.

Listas
Listados sin orden (viñetas) utilizan asteriscos, signos de suma y resta (*, +, y -) como marcas de listado. Estos tres marcadores son intercambiables; así:

*   Caramelo.
*   Chicle.
*   Chocolate.
así:

+   Caramelo.
+   Chicle.
+   Chocolate.
y así:

-   Caramelo.
-   Chicle.
-   Chocolate.
todos producen la misma salida:

    <ul>         
    <li>Caramelo.</li>
    <li>Chicle.</li>
    <li>Chocolate.</li>
    </ul>
Render:

Caramelo.
Chicle.
Chocolate.
Las listas ordenadas (numeradas) utilizan normalmente números, seguidos por un punto, como marcadores de lista:

1.  Rojo
2.  Verde
3.  Azul
Salida HTML:

    <ol>
    <li>Rojo</li>
    <li>Verde</li>
    <li>Azul</li>
    </ol>
Render:

Rojo
Verde
Azul
Si colocas líneas en blanco entre los items, obtendrás una etiqueta <p> para el texto de ese item. Puedes crear una lista de items multi-párrafo para los párrafos identados a 4 espacios ó 1 tab:

*   Un item de la lista.

    Con múltiples párrafos.

*   Otro item en la lista.
Salida HTML:

    <ul>
    <li><p>Un item de la lista.</p>
    <p>Con múltiples párrafos.</p></li>
    <li><p>Otro item en la lista.</p></li>
    </ul>
Render:

Un item de la lista.

Con múltiples párrafos.

Otro item en la lista.

Links
Markdown soporta dos tipos para crear links: en-línea y por-referencia. Con ambos estilos, se utilizan los paréntesis cuadrados para delimitar el texto que quieras convertir en link.

Los links estilo en-línea utilizan los paréntesis normales inmediatamente después del texto del link. Por ejemplo:

Markdown:

    Este es un [ejemplo de un link](http://ejemplo.com).
Salida HTML:

    <p>Este es un <a href="http://ejemplo.com/">ejemplo de un link</a>.</p>
Render:

Este es un ejemplo de un link.

Opcionalmente, puedes incluir un atributo título en el paréntesis:

    Este es un [ejemplo de un link](http://ejemplo.com "Con un Título").
Salida:

    <p>Este es un <a href="http://ejemplo.com/" title="Con un Título">
    ejemplo de un link</a>.</p>
Los links estilo por-referencia te permiten hacer referencia a tus links por nombres, que defines en otra parte de tu documento:

    Obtengo 10 veces más trafico de [Google][1] que de [Yahoo][2] o [MSN][3].

    [1]: http://google.com/        "Google"
    [2]: http://search.yahoo.com/  "Yahoo Search"
    [3]: http://search.msn.com/    "MSN Search"
Salida HTML:

    <p>Obtengo 10 veces más trafico de <a href="http://google.com/"
    title="Google">Google</a> que de <a href="http://search.yahoo.com/"
    title="Yahoo Search">Yahoo</a> o <a href="http://search.msn.com/"
    title="MSN Search">MSN</a>.</p>
El atributo title es opcional. Los nombres de los links pueden contener letras, números y espacios, perno no son sensibles mayúsculas o minúsculas.

Markdown:

    He comenzado mi día con una taza de café y con
    [El New York Times][NY Times].

    [ny times]: http://www.nytimes.com/
Salida HTML:

    <p>He comenzado mi día con una taza de café y con
    <a href="http://www.nytimes.com/">El New York Times</a>.</p>
Imágenes
La sintaxis para imágenes es muy similar a la de los links.

En-línea (los títulos son opcionales):

    ![texto alternativo](/path/to/img.jpg "Título")
Por-referencia:

    ![texto alternativo][id]

    [id]: /path/to/img.jpg "Título"
Ambos ejemplos de arriba producen la misma salida HTML:

    <img src="/path/to/img.jpg" alt="texto alternativo" title="Título" />
Código
En un párrafo regular, puedes crear secciones de código encomillado un texto. Cualquier amperson (&) y paréntesis triangular (< o >) automáticamente será transformado en código HTML. Esto hace fácil el uso de Markdown para escribir acerca de ejemplos de código HTML:

Markdown:

    Recomiendo fuertemente no utilizar la etiqueta `<blink>`.

    Espero que SmartyPants utilice un nombrado de entidades como `&mdash;`
    en lugar de entidades codificado-decimal como `&#8212;`.
Salida:

    <p>Recomiendo fuertemente no utilizar la etiqueta
    <code>&lt;blink&gt;</code>.</p>
    
    <p>Espero que SmartyPants utilice un nombrado de entidades como
    <code>&amp;mdash;</code> en lugar de entidades codificado-decimal
    como <code>&amp;#8212;</code>.</p>
Render:

Recomiendo fuertemente no utilizar la etiqueta <blink>.

Espero que SmartyPants utilice un nombrado de entidades como &mdash; en lugar de entidades codificado-decimal como &#8212;.

Para especificar un bloque entero de código pre-formateado, coloque una sangría en cada linea del bloque a 4 espacios o 1 tab. Al igual que con los segmentos de código, los caracteres &, < y > serán escapados automáticamente.

Markdown:

Si quieres que esta pagina sea validada por XHTML 1.0 Strict, tienes que
poner las etiquetas de párrafo en blockquotes:

<blockquote>
    <p>Por ejemplo.</p>
</blockquote>
Salida HTML:

    <p>Si quieres que esta pagina sea validada por XHTML 1.0 Strict,
    tienes que poner las etiquetas de párrafo en blockquotes:</p>
    
    <pre><code>&lt;blockquote&gt;
        &lt;p&gt;Por ejemplo.&lt;/p&gt;
    &lt;/blockquote&gt;
    </code></pre>
Render:

Si quieres que esta pagina sea validada por XHTML 1.0 Strict, tienes que poner las etiquetas de párrafo en blockquotes:

<blockquote>
    <p>Por ejemplo.</p>
</blockquote>

