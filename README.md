#  MARKDOWN
## El Lenguaje de documentación usado en GITHUB.

[![aledc.com](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/aledc.com.svg)](https://aledc.com)
[![License](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/mit-license.svg)](https://aledc.com)
[![GitHub release](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/release.svg)](https://aledc.com)
[![Dependencies](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/dependencias-none.svg)](https://aledc.com)




## vamos a los bifes y veamos todo lo que se puede hacer con el lenguaje MARKDOWN




### Este es el Lenguaje MARKDOWN que vamos a utilizar en la clase de hoy 19-06-2018 para SAP.

#### Resumen de la sintaxis Markdown

Markdown es un lenguaje de marcado ligero creado originalmente por John Gruber y Aaron Swartz que trata de conseguir la máxima legibilidad y "publicabilidad" tanto en sus forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano. Markdown convierte el texto marcado en documentos XHTML bien formados.

Nota: Este documento es una traducción del sitio oficial que está en Inglés daringfireball : basics.






# Titulo 1 <h1>
## Titulo 2 <h2>
### Titulo 3 <h3>
#### Titulo 4 <h4>
##### Titulo 5 <h5>
###### Titulo 6 <h6>

```
# Titulo 1 <h1>
## Titulo 2 <h2>
### Titulo 3 <h3>
#### Titulo 4 <h4>
##### Titulo 5 <h5>
###### Titulo 6 <h6>
```



  
  
  *Este texto estará en itálica*
_Este texto también estará en itálica_

**Este texto estará en negritas**
__Este texto también estará en negritas__

*Incluso **puedes** combinarlos*

```
  *Este texto estará en itálica*
_Este texto también estará en itálica_

**Este texto estará en negritas**
__Este texto también estará en negritas__

*Incluso **puedes** combinarlos*
```



Listas desordenadas

* Item 1
* Item 2
    * Item 2a
    * Item 2b
```
* Item 1
* Item 2
    * Item 2a
    * Item 2b
```
    
    
    
    
Listas Ordenadas

1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b
    
```
1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b
```

        
    
    Manejo de Imágenes:
    
    
![GitHub Logo](/images/logo.png)![GitHub]

```    
![GitHub Logo](/images/logo.png)![GitHub]
```


Manejo de Links

1. http://github.com - ¡link automático!

2. [GitHub](http://github.com)

3. [GitHub][id]

4. [GitHub][]

```

1. http://github.com - ¡link automático!

2. [GitHub](http://github.com)

3. [GitHub][id]

4. [GitHub][]
```


Link automático - Cualquier dirección explicita será convertida en un link.
Link en-línea - [Texto del Link](url).
Link por-referencia - [Texto del Link][id]. el id necesitará ser declarado en otra parte del documento así: [id]: url.
Link por-referencia automática - El id es el "Texto del Link", y también necesita ser declarado en otra parte del documento de igual manera que el "link por-referencia".

```
Link automático - Cualquier dirección explicita será convertida en un link.
Link en-línea - [Texto del Link](url).
Link por-referencia - [Texto del Link][id]. el id necesitará ser declarado en otra parte del documento así: [id]: url.
Link por-referencia automática - El id es el "Texto del Link", y también necesita ser declarado en otra parte del documento de igual manera que el "link por-referencia".
```





CITAS:

Esto es un párrafo normal:

> Y aquí está la cita que puede
> seguir en varios renglones, y tener anidado más
> > citas así, con un doble signo mayor-que.

```
> Y aquí está la cita que puede
> seguir en varios renglones, y tener anidado más
> > citas así, con un doble signo mayor-que.
```




Código en Linea

Creo que debería utilizar una etiqueta `<addr>` aquí.

```
Creo que debería utilizar una etiqueta `<addr>` aquí.
```



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
    
```
     function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
```
 



Lista de Tareas

- [x] Soporte de @menciones, #referencias, [links](), **formateo**, y de <del>etiquetas</del>
- [x] lista de sintaxis requerida (cualquier lista des-ordenada y ordenada es soportada)
- [x] esta es una tarea completa
- [ ] esta es una tarea incompleta

```
- [x] Soporte de @menciones, #referencias, [links](), **formateo**, y de <del>etiquetas</del>
- [x] lista de sintaxis requerida (cualquier lista des-ordenada y ordenada es soportada)
- [x] esta es una tarea completa
- [ ] esta es una tarea incompleta
```



Para referenciar los famosos SHA:

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

```
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```


###### Como incluír imágenes:


Inline-style: 
![alt text](https://github.com/aledc7/MARKDOWN/blob/master/aleicon-150x150.jpg "Sacame el mouse de encima por favor")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/aledc7/MARKDOWN/blob/master/aleicon-150x150.jpg "Sacame el mouse de encima por favor"

```
Inline-style: 
![alt text](https://github.com/aledc7/MARKDOWN/blob/master/aleicon-150x150.jpg "Sacame el mouse de encima por favor")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/aledc7/MARKDOWN/blob/master/aleicon-150x150.jpg "Sacame el mouse de encima por favor"

```





#### Manejo de Tablas:

Colons can be used to align columns.

| las tablas    | Estan         | joya  |
| ------------- |:-------------:| -----:|
| una fila      | right-aligned | $1600 |
| otra fil      | centered      |   $12 |
| una mas       | are neat      |    $1 |


```

| las tablas    | Estan         | joya  |
| ------------- |:-------------:| -----:|
| una fila      | right-aligned | $1600 |
| otra fil      | centered      |   $12 |
| una mas       | are neat      |    $1 |
```

Debe haber al menos 3 guiones que separan cada celda de encabezado.
Los pipes exteriores (|) son opcionales, y no es necesario que la línea de renglon sea perfecta.


Markdown | mas  | feo
--- | --- | ---
*Destacar* | `renders` | **lindo**
1 | 2 | 3

```
Markdown | mas  | feo
--- | --- | ---
*Destacar* | `renders` | **lindo**
1 | 2 | 3
```









