# Version del curso
Version actual v1.2.2

# cabeceras
# cabecera H1
## cabecera H2
### cabecera H3
#### cabecera H4
##### cabecera H5
###### cabecera H6


# underlines
underline 1
-----------

underline 2
==========

# formatos de enfasis

 - formato *italica* de la primer forma.
 - formato _italica_ de la segunda forma.
 - formato **bold o strong** primer forma
 - formato __bold o strong__ segunda forma
 - formato ~~tachado~~.

# listas
1. esto es un item de lista ordenada
2. esto es un item de lista ordenada
3. esto es un item de lista ordenada

- esto es un item de lista desordenada
- esto es un item de lista desordenada
- esto es un item de lista desordenada

# Links
- <a href="http://google.com"> Esto es un link HTML </a>
- [Esto es un link en Markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://image.flaticon.com/icons/png/512/25/25231.png)

# code snippets
codigo en json
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
codigo en javascript
```javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| nombre | apellido | documento |
|--------| ---------| ----------|
| Goku   | Son      | 564561754 |
| Gon    | Freeks   | 456456456 |

# Citas
Esto es un texto referente a una cita que se pondra debajo:
> Esto es una cita.

Otro texto para poner otra cita:
>Esto es otra cita.

# Lineas divisoras
Esto es un texto que sera dividido por guiones.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro dividido por guion bajo.

___
# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.