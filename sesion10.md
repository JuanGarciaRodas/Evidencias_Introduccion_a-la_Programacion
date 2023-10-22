<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

# Actividad: Propiedades de posicionamiento de CSS
**Objetivo:**

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

**Instrucciones:**

- Crea un nuevo archivo HTML y CSS.
- En el archivo HTML, crea una estructura básica de página web con dos elementos div.
- En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

### Preguntas:

- ¿Cuál es la diferencia entre los valores position: absolute y position: relative?

- ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?

- ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?



# **SOLUCION**

- Crea un nuevo archivo HTML y CSS.
- En el archivo HTML, crea una estructura básica de página web con dos elementos div.
- En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

 ```css
     .elemento1{
      position: absolute;
     top: 1200px;
     left: 1200px;
      background-color: red;}

     .elemento2 {
      position: relative;
      top: 1200px;
      left: 1200px;
      background-color: green;
     }
 
 ```

 ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
     <meta charset="UTF-8">
     <title>Document</title>
     <link rel="stylesheet" href="style.css">
     <style>
        .elemento-1 {
          position: absolute;
          top: 1200px;
          left: 1100px;
          background-color: red;
        }
    
        .elemento-2 {
          position: relative;
          top: 1200px;
          left: 1200px;
          background-color: green;
        }
      </style>
      </head>
      <body>
     <div class="elemento-1"></div>
     <div class="elemento-2"></div>
     </body>
     </html>
 ```




- **¿Cuál es la diferencia entre los valores position: absolute y position: relative?**

La propiedad CSS position se utiliza para especificar cómo se posiciona un elemento en el documento. Los valores posibles son static, relative, absolute, fixed y sticky.

**position relative:** posiciona el elemento relativo a su posición original. Las propiedades top, right, bottom y left especifican el desplazamiento vertical y horizontal desde su posición original.

**position absolute:** posiciona el elemento relativo a su bloque contenedor. Las propiedades top, right, bottom y left especifican el desplazamiento desde los bordes del bloque contenedor del elemento.

- **¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?**

La propiedad CSS z-index se utiliza para controlar el orden de apilamiento de los elementos posicionados. 
El valor de z-index especifica la posición de un elemento en el eje z, que es perpendicular al plano de la pantalla.
 Los elementos con un valor de z-index más alto se superponen a los elementos con un valor de z-index más bajo.

Para utilizar la propiedad z-index, primero debes establecer la posición del elemento utilizando la propiedad position. Los elementos con una posición diferente a static se pueden apilar utilizando z-index.


Por ejemplo, si tienes dos elementos superpuestos, puedes utilizar la propiedad z-index para controlar cuál aparece encima del otro. Si el primer elemento tiene un valor de z-index de 1 y el segundo elemento tiene un valor de z-index de 2, entonces el segundo elemento aparecerá encima del primero.


- **¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?**

La propiedad CSS display se utiliza para controlar cómo se muestra un elemento en una página web.
 Esta propiedad especifica si un elemento debe ser tratado como un elemento de bloque o de línea, y el diseño utilizado por sus hijos, como el diseño de flujo, cuadrícula o flexible Formalmente, la propiedad display establece los tipos de visualización interna y externa de un elemento.

Los valores posibles para la propiedad display son los siguientes:

**block:** El elemento se muestra como un bloque, ocupando todo el ancho disponible Los elementos que aparecen después del bloque se muestran en la siguiente línea.

**inline:** El elemento se muestra como una línea en el flujo del texto. Los elementos que aparecen después del elemento en línea se muestran en la misma línea.

**inline-block:** El elemento se muestra como una línea en el flujo del texto, pero también permite establecer un ancho y una altura.

**none:** El elemento no se muestra en la página web Los elementos que aparecen después del elemento oculto se muestran como si el elemento no existiera.

**table:** El elemento se muestra como una tabla.

**table-row:** El elemento se muestra como una fila de una tabla.

**table-cell**: El elemento se muestra como una celda de una tabla.

**flex:** El elemento se muestra como un contenedor flexible.

**grid:** El elemento se muestra como un contenedor de cuadrícula.


