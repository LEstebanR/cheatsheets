# CSS



<hr>

## Notas

Las clases se seleccionan con .clase
Los Ids se seleccionan con #

<hr>

## Propiedades 

Color de la fuente `color`  
Tamaño del texto `font-size`  
Fuente `font-family`  
Grosor de la fuente `font-weight`  
Color del fondo `background-color`  
Borde alrededor `border`  


<hr>

## Tablas

Agregar bordes a una tabla:  

```css
table, th, td
{
    border: 1px solid black;
}
```

Uniendo los bordes de la tabla:  

```css
table, th, td
{
    border: 1px solid black;
    border-collapse: collapse;
}
```

Agregar espacio entre las celdas:

```css
th, td
{
    padding: 15px;
}
```

<hr>

## Posicionamineto

El orden de las posiciones es: superior, derecho, inferior, izquierdo

Margin-Border-Padding

La propiedad CSS `position` define el tipo de posicionamiento para el elemento. Los posibles valores son:

- `static`: el valor por defecto.
- `relative`: relativo a su ubicación normal.
- `fixed`: fijo en la ventana del navegador.
- `absolute`: relativa el ancestro más cercano con posición `relative` o a la ventana del navegador.

Los valores `relative`, `fixed` y `absolute` se utilizan generalmente en conjunto con las propiedades `top`, `left`, `bottom` y `right`.

<hr>

# Pseudo clases

Nos permiten seleccionar elementos por su estado actual.

Por ejemplo los vínculos que ya han sido visitados, los checkboxes que están seleccionados, los elementos sobre los que está pasando el mouse, etc.

Por ejemplo, los vínculos pueden estar en varios estados:



```
/* no visitado */
a:link {
    color: #FF0000;
}

/* visitado */
a:visited {
    color: #00FF00;
}

/* mouse sobre el vínculo */
a:hover {
    color: #FF00FF;
}

/* seleccionado */
a:active {
    color: #0000FF;
}
```

