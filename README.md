# SAP-TFI-UAI-
Desarsrollo de la clase de GIT y GITHUB en la que se explicará que es GIT, que es GITHUB, ALternativas a GITHUB y Manejo de GIT desde la terminal.

## FECHA CLASE 19-06-2018 - Git Avanzado y 

Al finalizar esta clase cada uno debería tener subido a git su proyecto y enviar la url del mismo por mail a alejandro.decastro@uai.edu.ar.

Según las palabras del jefe de cátedra, esta tarea no es obligatória, pero a la hora de corrección se dará prioridad a los alumnos que cumplan con este jercicio.



# APRENDIENDO MARKDOWN, El Lenguaje de documentación que usa GITHUB.



## vamos a los bifes y veamos todo lo que se puede hacer con el lenguaje MARKDOWN




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



###### Como incluír imágenes:


Inline-style: 
![alt text](https://github.com/aledc7/MARKDOWN/blob/master/aleicon-150x150.jpg "Sacame el mouse de encima por favor")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/aledc7/MARKDOWN/blob/master/aleicon-150x150.jpg "Sacame el mouse de encima por favor"





aca un tuto mucho ams completo sobre MARKDOWN:

https://github.com/ricval/Documentacion/blob/master/Markdown/daringfireball/basics.md








