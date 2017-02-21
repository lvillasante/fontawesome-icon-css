Font Awesome CSS content values
===============

Introducir iconos de la libreria Font Awesome a la hoja de estilos CSS 

## Ejemplo práctico


```
.element {
    position: relative;
}
 
/*replace the content value with the
corresponding value from the list below*/
 
.element:before {
    content: "\f000";
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    text-decoration: inherit;
/*--adjust as necessary--*/
    color: #000;
    font-size: 18px;
    padding-right: 0.5em;
    position: absolute;
    top: 10px;
    left: 0;
}
```

