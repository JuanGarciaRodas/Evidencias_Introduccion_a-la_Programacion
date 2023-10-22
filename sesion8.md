<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->



# **Actividad: Aplicando estilos con selectores CSS**

**El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.**

### Pasos:

**Crea el esqueleto de una página web simple con la siguiente estructura:**

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>


**Aplica los siguientes estilos usando selectores de etiqueta:**

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>

**Aplica los siguientes estilos usando seleccionadores de clase:**

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

**Aplica los siguientes estilos usando seleccionadores de ID:**

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

**Aplica los siguientes estilos usando seleccionadores descendientes:**

- Color gris a los párrafos dentro de un <div>
- Centrar el contenido de la sección <section>


# SOLUCION


```css
     .destacado {
     background-color: green;
     font-weight: bold;
     }


     .parrafo-grande {
     font-size: 20px;
      }
 ```

 ```html
      <!DOCTYPE html>
     <html lang="en">

      <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <link rel="stylesheet" type="text/css" href="estilos.css">
     <title>Document</title>
     <style>
        img {border: 10px solid black; }
        p {color: blue;}
        h1 {color: red;}
        #pricipal {background-color: yellow;}
        #sombras {
            box-shadow: 5px 5px 10px 2px rgba(0, 0, 0, 0.5);}
            #contenedor {
            color: gray;}
            section {width: 70%; margin: 0; text-align: center;}
     </style>
     </head>

     <body>
     <section>
     <header>
        <h1>Zeno Sama El dios supremo</h1>
     </header>

      <div id="pricipal"> <p class="destacado">El Rey de Todo (全ぜん王おう, Zen’ō), también conocido como Zen Oo (Zeno Sama en España y Zen Oo Sama en
        Hispanoamerica) y apodado por Son Goku como Todito (全ぜんちゃん, Zen-chan), es el gobernante y dios absoluto de todos
        los universos y el máximo soberano de todo lo existente en Dragon Ball</p>
     </div>

     <p class="parrafo-grande">Es un tierno humanoide de muy baja estatura, teniendo una cabeza con forma ovalada, tiene secciones de rayas
        color celeste y purpura en su cara, no posee nariz alguna. Viste una túnica rosa con bordes de color amarillo,
        en su torso posee una vestimenta con los dos kanji de (全) que significa 'todo' (uno de ellos invertido para solo
        darle significado al kanji (王) que significa 'rey') y tacones rosas con medias doradas, por último sus dos
        orejas son como la mitad de una esfera con una parte plana de color gris..</p>


     <p id="sombras">Presenta una personalidad de buenos modales y amable, habla de manera muy respetuosa y no le ofende la presencia
        despreocupada de Son Goku, tanto así que él mismo pidió a Son Goku que fuera su amigo y fuese a su palacio a
        jugar con él, a lo que él accedió; ha demostrado ser bastante paciente cuando se trata de pedirle a Son Goku que
        vaya a jugar con él, ya que comprendió perfectamente cuando Son Goku le dijo que en aquel momento no podía
        porque tenía otras cosas que hacer. No obstante puede ser impredecible, caprichoso y de un temperamento frágil
        ya que este destruyó 6 de los 18 universos que habían anteriormente en un ataque de ira. Esta actitud sumada a
        un carácter algo infantil e irresponsable hace que el Rey de Todo dé un mal uso de sus poderes. Por esta razón
        es temido entre los dioses de todos los universos, temor nacido de sus berrinches.</p>

     <img src="https://sm.ign.com/ign_latam/screenshot/default/hakai2_c7su.jpg" alt="Zeno sama">

     <footer>
        <p>JUAN CARLOS GARCIA &copy;CESDDE 2023</p>
     </footer>
      </section>  
     </body>

     </html>
 ```


