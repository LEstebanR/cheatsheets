# HTML

<hr>
## Vincular elementos

Vincular archivo CSS:  
`<link rel="stylesheet" href="<ruta del archivo>">`

Imagen:  
`<img src="<ruta de la imagen>">`

<hr>
## Listas y tablas

* Lista no ordenada:   


```html
<ul>
    <li>Items de la lista</li>
</ul>
```

* Lista ordenada:   


```html
<ol>
    <li>Items de la lista</li>
</ol>
```

* Tabla

  ```html
  <table>
      <tr>
          <th>Encabezado columna 1</th>
          <th>Encabezado columna 2</th>
      </tr>
      <tr>
          <td>Elemento en fila 1 col 1</td>
          <td>Elemento en fila 1 col 2</td>
      </tr>
  </table>
  ```

  Para que una celda ocupe más de dos columnas se agrega la propiedad colspan 
  `<td colspan="2">Ocupa dos columnas</td>`

  Para que una celda ocupe más de una fila se agrega la propiedad rowspan  
  `<td rowspan="2">Ocupa 2 columnas</td>`


<hr>

## Agrupar elementos:  

`<div>Elementos que se van a agrupar</div>`  
`<span>Texto que se va a agrupar dentro del párrafo</span>`

<hr>
## Formularios

Los formularios se crean con la etiqueta `<form></form>`  
Campo de texto: `<input type ="text">`  
Campo de contraseña: `<input type="password"`  
Casilla de verificación: `<input type="checkbox"> mensaje`  
Botón de envío: `<input type="submit" value="Enviar">`  
Lista de selección:  

```html
 <select name="genero">
    <option value="masculino">Masculino</option>
    <option value="femenino">Femenino</option>
  </select>
```

<hr>

## Etiquetas

Titulos:  


```html
<h1>Titulo 1</h1>
<h2>Titulo 2</h2>
<h3>Titulo 3</h3>
<h4>Titulo 4</h4>
<h5>Titulo 5</h5>
<h6>Titulo 6</h6>

<!-- El número de acuerdo a la importancia del título 1 el más importante -->

```

Párrafo:  `<p></p>`  
Negrilla: `<strong></strong>`  
Enfasis `<em></em>`  
Salto de linea `<br>`   
Hacer una linea horizontal: `<hr>`  







