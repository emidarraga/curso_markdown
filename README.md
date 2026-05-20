# Curso de Markdown
Es un lenguaje de marcado ligero creado en 2004 para dar formato a docuemtos de texto plano de manera sencilla, legigle y rapida sin usar menus complejos


- [Curso de Markdown](#curso-de-markdown)
  - [Parrafos 🔼](#parrafos-)
  - [Formato de texto 🔼](#formato-de-texto-)
    - [Negrita](#negrita)
    - [Cursiva](#cursiva)
  - [Encabezados 🔼](#encabezados-)
  - [Enlaces 🔼](#enlaces-)
  - [Imagenes 🔼](#imagenes-)
  - [Diviciones 🔼](#diviciones-)
  - [Listas 🔼](#listas-)
    - [Listas ordenadas](#listas-ordenadas)
    - [Lista de viñetas](#lista-de-viñetas)
  - [Citas 🔼](#citas-)
    - [Citas en linea](#citas-en-linea)
    - [Cita de bloque](#cita-de-bloque)
  - [Tablas 🔼](#tablas-)
  - [Codigo 🔼](#codigo-)
    - [Codigo de una linea](#codigo-de-una-linea)
    - [Codigo de bloque](#codigo-de-bloque)
  - [Escribiendo en HTML 🔼](#escribiendo-en-html-)
  - [Comentarios 🔼](#comentarios-)
  - [Escapando caracteres 🔼](#escapando-caracteres-)

## Parrafos [🔼](#curso-de-markdown)
En Markdown, un párrafo se crea simplemente dejando una línea en blanco entre bloques de texto.

```
Esto es un parrafo

Esto es otro parrafo
```

## Formato de texto [🔼](#curso-de-markdown)

### Negrita
Se usa poniedo el texto entre dos asteriscos

```
** texto en negrita **
```

**soy un texto en negrita**

### Cursiva
Se usa poniedo el texto entre dos guines bajo

```
_texto en negrita_
```

_soy un texto en cursiva_

## Encabezados [🔼](#curso-de-markdown)
Estos son parcedidos a los de html van de 1 a 6 siendo 1 el mas importante, tambien funcionan como anclas.


```
# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6
```

## Enlaces [🔼](#curso-de-markdown)

```
[Texto que se ve](link local o externo)
```

[Ir a Youtube](https://www.youtube.com/)

## Imagenes [🔼](#curso-de-markdown)

```
![Alt de la img](direccion de la imagen, local o externa)

```
![Markdown logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQvs5lafIDysV5Gfs-Xa_Kdve_gPAWHoj39PA&s)

## Diviciones [🔼](#curso-de-markdown)
Separaciones de texto

```
Forma 1:
---
```

## Listas [🔼](#curso-de-markdown)

### Listas ordenadas

```
1. Item
1. Item
1. Item
```

1. Item
1. Item
1. Item

### Lista de viñetas
```
Forma 1:
* Item
* Item
* Item

Forma 2:
- Item
- Item
- Item

```

* Item
* Item
* Item

## Citas [🔼](#curso-de-markdown)

### Citas en linea

```
> Siempre tienes opcion de no tener opinion
```

> Siempre tienes opcion de no tener opinion - Marco aurelio

### Cita de bloque

> La diferencia entre quien eres y quien quieres 
> 
> llegar a ser está en lo que haces cada día
>
> **Bill Philips**
>

## Tablas [🔼](#curso-de-markdown)

```
| Head | Head | Head |
| --- | --- | --- |
| data | data | data |
| data | data | data |
| data | data | data |
```

| Nombre | Edad | Correo |
| --- | --- | --- |
| Bob | 23 | b.esponja@gmail.com |
| Paticio | 21 | p.estrella@gmail.com |
| Arenia | 25 | arenita@gmail.com |

## Codigo [🔼](#curso-de-markdown)
### Codigo de una linea


```
`let name = "Esteban"`
```

`let name = "Esteban"`

### Codigo de bloque
```py
def sum(num1, num2):
  return num1 + num2
```

## Escribiendo en HTML [🔼](#curso-de-markdown)
Marckdown permite usar etiquetas de HTML5 

<form>
  <label>
    Buscar: <input type="text">
  </label>

  <label for="nombre"> Nombre: </label>
  <input type="text" id="nombre" name="nombre">
</form>

## Comentarios [🔼](#curso-de-markdown)
Los comentarios usan la misma sintaxis que en HTML

```
<!-- Soy un comentario -->
```

## Escapando caracteres [🔼](#curso-de-markdown)
Al igual que en un lenguaje de programcion se usa un \\ para escapar un carcter

\*\*negrita\*\*
