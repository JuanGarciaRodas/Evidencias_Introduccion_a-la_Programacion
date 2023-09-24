<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->
# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

### Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame

**Utiliza encabezados para títulos en cada elemento (<h1>...<h6>).**

**Crea una descripción para cada elemento utilizando párrafos (<p>).**

*Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:*

- Usa <strong> para resaltar texto importante.
- Utiliza <br> para insertar saltos de línea si es necesario.
- Agrega <span> para aplicar estilos específicos a porciones de texto.
- Emplea <i> para enfatizar o dar énfasis a palabras o frases.
- Utiliza <u> para subrayar texto cuando sea necesario.
- Considera el uso de <div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

## Plantilla Inicial

 ```html

     <!DOCTYPE html>
     <html>

     <head>
     <title>Etiquetas Multimedia HTML5</title>
     <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
     </style>
     </head>

     <body>

     <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
     </header>

     <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
     </section>

     <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
      </section>

     <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

     </section>

     <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
     </section>

     <footer>
        Nombre Completo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
     </footer>

     </body>

     </html>

 ```

 
## Semántica y Estructura de la Plantilla


El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

<!DOCTYPE html>: Esto define el tipo de documento como HTML5.

html: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

head: Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque <style> para agregar reglas de estilo CSS.

title: Establece el título de la página en la pestaña del navegador.

style: Contiene reglas de estilo CSS que afectan al diseño y la apariencia del sitio.

body: Aquí se coloca el contenido principal visible de la página.

header: Sección de encabezado que contiene el título principal y un subtítulo.

h1 y h3: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

section: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

h2: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

p: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

footer: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea <br> para separar las líneas de texto.

En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

- La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.

- El encabezado (<header>) tiene un fondo oscuro, texto blanco y un espacio de relleno.

- Cada sección (<section>) tiene un borde, un espacio de relleno y un margen inferior.

- Los encabezados de nivel 1 y 3 están centrados.

- Los encabezados de nivel 2 (<h2>) tienen color azul.

- El pie de página (<footer>) tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.

- Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido. El estilo CSS proporciona una apariencia visual coherente y agradable.


# Solucion

Lin para ingresar a la pagina [link](file:///C:/Users/Juan%20Carlos/OneDrive/Escritorio/Actividad%204%20Juan%20Carlos%20Garcia/index.html).

 ```html

     <!DOCTYPE html>
     <html>

     <head>
     <title>Etiquetas Multimedia HTML5</title>
     <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #330fd3;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(255, 0, 64);
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
     </style>
     </head>

     <body>

     <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
     </header>

     <section>
        <h2>FUTBOL CLUB BARCELONA</h2>

        <p>El Fútbol Club Barcelona, conocido popularmente como Barça, ​ es una entidad polideportiva con sede en
            Barcelona, Cataluña, España. Fue fundado como club de fútbol el 29 de noviembre de 1899 y registrado
            oficialmente el 5 de enero de 1903 <br><br>
            Joan Gamper, fundador del Club, fue su ánima e impulsor durante los primeros 25 años de vida
            La aventura de la creación del FC Barcelona en 1899 por un grupo de jóvenes, extranjeros y catalanes que
            vivían en Barcelona, ​​fue la consecuencia de un proceso de expansión de la práctica del fútbol y otros
            deportes de origen británico en el continente europeo. Esto explica la naturaleza intercultural del Club, su
            vocación polideportiva y la voluntad de arraigo en una ciudad y en un país. Gamper, fundador del Club, fue
            el alma y el impulsor durante los primeros 25 años. Su compromiso con el FC Barcelona va más allá de sus
            facetas como jugador, directivo y presidente. <br><br>
            <strong>FUNDACIÓN DEL CLUB</strong> <br><br>
            Hans Gamper (Winterthur, Suiza, 1877 - Barcelona, ​​1930) llegó a Barcelona en 1898 por motivos
            profesionales. En los ratos de ocio jugaba al fútbol con un grupo de compañeros en las calles de la capital
            catalana.<br>
            El 22 de octubre de 1899 Gamper publica un anuncio en la revista Los Deportes haciendo un llamamiento para
            formar un equipo de fútbol.<br>
            El 29 de noviembre, Gamper y once hombres más (los suizos Otto Kunzle y Walter Wild, los ingleses John y
            William Parsons, el alemán Otto Maier y los catalanes Lluís d'Ossó, Bartomeu Terrades, Enrique Ducay, Pere
            Cabot, Carles Pujol y Josep Llobet) se reúnen en el Gimnàs Solé para formar una asociación que llevará el
            nombre y el escudo de la ciudad: el FC Barcelona.<br><br>
            <strong>GAMPER Y LOS VALORES PRIMIGENIOS DEL BARÇA</strong> <br><br>
            Gamper, enamorado del deporte -además de fútbol, ​​era practicante de atletismo, ciclismo, rugby y golf, lo
            concebía como un factor determinante para ensalzar las virtudes del ser humano.<br>
            Deseó una entidad abierta a todos, sin tener en cuenta la procedencia de las personas. Se imaginó un club
            integrador en el que todo el mundo pudiera decir la suya, y apostó por una sociedad democrática, regida
            libremente por sus asociados. Y, agradecido con el país que lo había acogido, Catalunya, no dudó, a partir
            del año 1908, a dar al FC Barcelona un sentido que lo marcará universalmente: el compromiso con la
            catalanidad. <a href="https://www.fcbarcelona.es/es/ficha/643865/1899-09-nacimiento-y-supervivencia"
                target="_blank" rel="noopener noreferrer">Conoce mas historia del club</a>
        </p>
        <img src="Archivos/Barcelona.jpeg" alt="FC BARCELONA" width="1400">

        <h2>ESCUDO</h2>
        <p>Era el escudo de la ciudad de Barcelona, embaldosado con cuatro cuartos. Arriba lucía una corona y un
            murciélago, y estaba rodeado por dos ramas, una de laurel y otra de palmera. Era una forma de expresar,
            desde buen principio, la vinculación del club con la ciudad que le vio nacer. <br><br>

            Este escudo estuvo vigente hasta el año 1910. Después de que Gamper salvara el club de la profunda crisis de
            1908, los intentos de proporcionarle a la entidad un escudo propio y diferenciado dieron sus frutos. En
            1910, el Barça convocó un concurso abierto a todos los socios que tuvieran propuestas. Ganó el dibujo de
            Santiago Femenia, que había jugado a fútbol en Internacional y Barça, y era socio del club. Así nació el
            escudo que el club ha lucido desde entonces, con pocas variaciones. <br><br>

            Se trata de un escudo con forma de olla que mantenía en los cuartos superiores la Creu de Sant Jordi y las
            cuatro barras, elementos representativos de Barcelona y Catalunya, respectivamente. En el centro del escudo,
            en una franja, aparecen las iniciales del club, F.C.B., y en la parte inferior los colores azul y grana con
            un balón de fútbol. En definitiva, un escudo que reflejaba la dimensión deportiva y la vinculación del club
            a la ciudad y el país. <br><br>

            Desde 1910, los cambios introducidos en el escudo han sido mínimos, la mayoría de carácter estético, con
            pequeñas modificaciones en el trazo de su perfil. Los más importantes son los que se tuvieron que hacer
            debido a condicionantes políticos. Con la instauración del franquismo, las siglas F.C.B. fueron sustituidas
            por C.F.B., en consonancia con la castellanización de la denominación del club. La dictadura también obligó
            a sustituir las cuatro barras del cuarto superior, que quedaron limitadas a dos, y la bandera catalana quedó
            eliminada del escudo. Aprovechando los actos del 50 aniversario del club, en 1949, se recuperaron las cuatro
            barras. Las siglas originales no se recuperaron hasta finales de 1974, de modo que el escudo volvió al
            contenido original de 1910. <a href="https://www.fcbarcelona.es/es/club/identidad/escudo" target="_blank"
                rel="noopener noreferrer">MAS DETALLES DE NUESTRO ESCUDO</a></p>
        <img src="Archivos/ESCUDOS.png" alt="escudo fcbarcelona">

        <h2>ESTADIO SPOTIFY CAMP NOU</h2>

        <p><strong>El Spotify Camp Nou</strong> acoge los partidos de fútbol del primer equipo del Club desde septiembre
            de 1957. <br><br>

            El nuevo estadio del Barça sustituyó el antiguo campo de Les Corts, que a pesar de que tenía una capacidad
            para 48.000 espectadores (después de varias ampliaciones) se quedó pequeño con la gran expansión de la
            afición azulgrana experimentada a finales de la década de los cuarenta. <br><br>

            Los arquitectos Francesc Mitjans Miró y Josep Soteras Mauri (con la colaboración de Lorenzo García Barbón)
            diseñaron el Estadio, que se construyó entre 1955 y 1957 a base de hormigón y hierro. La obra costó unos 288
            millones de pesetas y supuso el endeudamiento del Club durante unos años.<br><br>

            Aunque inicialmente no tenía nombre, una encuesta entre los socios celebrada en septiembre de 1965
            estableció como nombre oficial Estadio del CF Barcelona. De todos modos, popularmente desde 1957 se bautizó
            como <u>Camp Nou</u> , ya que el estadio sustituía el antiguo campo de Les Corts, el campo viejo. En abril
            de 2001
            se oficializó el nombre de <u>Camp Nou</u> después de una consulta popular, a través del correo, entre los
            socios
            de la Entidad. De las 29.102 respuestas que se remitieron al Club, un total de 19.861 (el 68.25%) apostaron
            por <u>Camp Nou</u> en lugar de Estadio del FC Barcelona. <br><br>

            El Estadio tiene una altura máxima de 49,67 metros y una superficie de 58.760 metros cuadrados (260 metros
            de longitud y 226 de anchura). Siguiendo la normativa de la UEFA, el terreno de juego hace 105 m x 68 m.
            <br><br>

            Con una capacidad de 99.354 personas, actualmente es el estadio más grande de toda Europa. La capacidad del
            Estadio, sin embargo, ha sufrido varios cambios, debido a las diferentes ampliaciones que se han hecho.
            Inicialmente, en 1957 cabían 99.053 espectadores, cifra que llegó hasta los 115.000 en 1982, coincidiendo
            con la celebración del Mundial de fútbol. Posteriormente, en aplicación de la normativa que obligaba a
            eliminar las localidades de pie, el aforo se situó nuevamente, a finales de los años 90, en la raya de los
            99.000 espectadores. <a href="https://www.fcbarcelona.es/es/club/instalaciones/spotify-camp-nou"
                target="_blank" rel="noopener noreferrer">Detalles del Camp Nou</a>
        </p>
        <img src="Archivos/Camp-nou-1.webp" alt="Estadio" width="600">
        <img src="Archivos/Camp-Nou-2.webp" alt="" width="600">
        <img src="Archivos/Camp-Nou-3.webp" alt="" width="600">
        <img src="Archivos/Camp-Nou-4.webp" alt="" width="600">

        <h2>TITULOS OBTENIDOS POR EL CLUB</h2>
        <p>El <u><strong>FC Barcelona</strong></u> es uno de los equipos más grandes de España y el mundo; su nombre se
            asocia a prestigio e
            historia. <br><br>Su éxito como club se lo debe a todos los trofeos que ganó desde que inició a competir,
            tanto en
            el país, como en Europa y en el planeta. <br> A continuación un repaso por los 98 títulos que han ganado los
            Blaugranas en 123 años de historia. <br> El Barcelona suma un total de 75 trofeos españoles divididos entre
            Ligas, Copas del Rey, Supercopas, Copa de la Liga y Copa Eva Duarte. <br>El Barcelona es el segundo club más
            ganador del principal torneo de España con 27 conquistas, solo por detrás de las 35 del Real Madrid, y fue
            el campeón de la temporada 1928-1929, la inaugural. <br> La máxima hegemonía Blaugrana fue durante 1990 y
            1994,
            en donde obtuvo un tetracampeonato, la mejor racha del club. En la segunda competencia en importancia en
            España, el Barcelona es el Rey ya que los culés tienen 31 trofeos en 42 finales disputadas y son los máximos
            ganadores, por delante del Athletic (23) y el Real Madrid (19). La última conquista fue el 17 de abril de
            2021 cuando en la final derrotó justamente al Athletic por 4-0. <a
                href="https://www.sportingnews.com/us-es/f%C3%BAtbol/news/cuantos-titulos-tiene-barcelona-palmares-historia/dyfeetilblusyuw2toy2ukzm"
                target="_blank" rel="noopener noreferrer">MAS SOBRE NUESTROS TITULOS</a></p>
        <img src="Archivos/Titulos.png" alt="Copas" width="600">
        <img src="Archivos/mini_WEB.webp" alt="" width="500">

     </section>

     <section>
        <h2>RENOVACION DEL ESTADIO SPOTIFY CAMP NOU</h2>
        <p>Estamos construyendo un nuevo espacio para seguir ganando.
            Ganando apertura en el barrio y en la ciudad, ganando comodidad para los socios, socias y toda la afición,
            ganando en visibilidad internacional en el ámbito del deporte y del entretenimiento, con la reforma del
            Spotify Camp Nou. <a href="https://www.youtube.com/@FCBarcelona/videos" target="_blank"
                rel="noopener noreferrer">Mira mas videos de las obras</a></p>
        <video src="Archivos/TRABAJOS EN EL ESTADIO SPOTIFY CAMP NOU.mp4" controls width="600"></video>
        <video src="Archivos/The NEW CAMP NOU (OFFICIAL).mp4" controls width="600"></video>

        <h2>LEYENDAS DEL FC BARCELONA</h2>
        <p>Desde su fundación como club de fútbol el 29 de noviembre de 1899 hasta la actualidad, miles de jugadores
            vistieron los colores Blaugranas <br><br> Respeto, esfuerzo, ambición, trabajo en equipo y humildad. Los
            cinco
            principales valores que describen el espíritu de Barcelona y así lo hace saber el club catalán a través de
            su página oficial de internet. Estos valores han sido transmitidos a lo largo de la historia del club por
            sus grandes leyendas, aquellos jugadores que han dejado su huella en el campo y han demostrado una
            dedicación inquebrantable al equipo. <br><br>
            Cada uno de ellos ha personificado estos valores de diferentes maneras,
            pero todos han dejado una marca duradera en el legado del Barça.El respeto ha sido un valor fundamental en
            la filosofía del club desde sus primeros días. Jugadores como <strong>Johan Cruyff y Carles Puyol</strong>
            siempre han
            mostrado respeto hacia sus oponentes, compañeros de equipo y aficionados. <br><br>
            El respeto por el juego limpio y
            el fair play ha sido una parte integral de la historia del Barça. <br>
            El esfuerzo es otro valor que ha sido una
            parte importante del espíritu del Barça. <u><strong>Lionel Messi</strong></u> , el máximo goleador de la
            historia del club, ha
            demostrado una determinación incansable para superar sus propias marcas y ayudar al equipo a ganar. <br>
            Otros
            jugadores, como <u><strong>Xavi Hernández y Andrés Iniesta</strong></u>, han trabajado duro día tras día
            para mejorar sus
            habilidades y convertirse en jugadores excepcionales. <br>
            La ambición es otra característica fundamental del
            espíritu del Barça. <br>
            La pasión por ganar ha impulsado a jugadores como <u><strong>Ronaldinho y Luis Suárez</strong></u> a dar lo
            mejor de sí en cada partido. El Barça siempre ha demostrado un deseo de ser el mejor, de superar a sus
            rivales y de lograr grandes cosas. <br>

            El trabajo en equipo es un valor que se refleja en la filosofía del juego del Barça. Pep Guardiola, el
            entrenador más exitoso en la historia del club, siempre ha enfatizado la importancia de trabajar juntos como
            un equipo unido. Jugadores como Andoni Zubizarreta y Gerard Piqué han demostrado una gran habilidad para
            trabajar en equipo, mientras que otros como Luis Enrique y Paulino Alcántara han sido fundamentales para la
            construcción de un equipo unido y cohesivo. <a
                href="https://bolavip.com/futbol/Las-34-grandes-leyendas-de-Barcelona-20230308-0056.html"
                target="_blank" rel="noopener noreferrer">Presiona aqui para mas Info sobre nuestras leyendas</a></p>
        <video src="Archivos/Top 10 Máximas Leyendas del Barcelona.mp4" controls width="800"></video>

     </section>

     <section>
        <h2>HIMNO DEL FC BARCELONA</h2>
        <p>El <strong>‘Canto del Barça’</strong>, compuesto en 1974, es el actual himno del Club. <br>
            Fue escrito con motivo del 75º
            aniversario de la entidad por los escritores Josep M. Espinàs y Jaume Picas, con música de Manuel Valls, y
            es todavía plenamente vigente. <br>
            Es un himno con mucha fuerza, rítmico, y con un contenido de afirmación
            (“tenemos un nombre, lo sabe todo el mundo”), pero sobre todo de integración (“somos la gente azulgrana, no
            importa de donde venimos”, “una bandera nos hermana”) y de persistencia (“se ha demostrado que nunca nadie
            nos podrá torcer”) <a href="https://www.fcbarcelona.es/es/club/identidad/himno" target="_blank"
                rel="noopener noreferrer">Conoce la letra de nuestro himno</a></p>
        <audio src="Archivos/HimnoFCB-CORAL-SANT-JORDI-.mp3" controls></audio>

        <h2>CANTICOS DE LOS HINCHAS AZULGRANA</h2>
        <p><strong>Un cántico de fútbol o cántico de grada</strong> es una canción cantada por la hinchada de un club de
            fútbol. <br>
            Pueden ser históricas (con orígenes en la fecha de creación del club), adaptaciones de canciones populares o
            reacciones espontáneas ante sucesos en el terreno de juego. <br>
            Suelen ser repetitivas. Aunque su finalidad
            puede ser de muchos tipos dependiendo del país o incluso del equipo, suelen ser cantadas animar a los
            jugadores propios, intimidar a los rivales o insultar al oponente, tanto a los jugadores, como a la afición
            al propio equipo como institución. <br>
            Además, también suelen surgir cánticos contra componentes del propio
            equipo (por ejemplo, los directivos) si la hinchada no está contenta en algún aspecto con ellos. <br><br>
            Desde hace algunos años, en cada partido que juega el Barcelona en el Camp Nou, no sólo se escucha el himno
            del conjunto azulgrana. Cada vez que el cuadro culé juega en casa, se esucha el mismo grito en el minuto 17
            (minuto 17 y 14 segundos, exactamente).</p>

        <audio src="Archivos/Canticos Del Barça _ _ Perico dime lo que se siente _ (128 kbps).mp3" controls></audio>
        <audio src="Archivos/Un altre dia de Partit - Barça vs Chelsea (128 kbps).mp3" controls></audio>


        <h2>ENTREVISTA A LIONEL MESSI</h2>
        <p>En esta entrevista el astro argentino nos cuenta lo dificil que fue para el irse del Barcelona. <br>
            <strong>Lionel Messi</strong> habló en exclusiva con Mundo Deportivo y Sport. <br> La Pulga dice que vivió
            momentos muy feos
            cuando tuvo que irse del Barcelona en el 2021 y dice que no quería volver a pasar por eso. Leo dice que lo
            económico nunca fue un factor para él y que no podía esperar por una respuesta del <strong>Barça</strong>.
            <br>
            Messi no cierra la
            puerta de algún día volver a "aportar algo al club".
        </p>
        <audio src="Archivos/Messi habla (128 kbps).mp3" controls></audio>

     </section>

     <section>
        <h2>PAGINA OFICIAL DEL FC BARCELONA</h2>
        <p> Web oficial del FC Barcelona. <br>
            Todas las noticias relacionadas con el Barça, venta de entradas, servicios al
            socio y las peñas e información, es una pagina donde podras encontrar todo lo relacionado con club y sus
            diferentes desempeños dia a dia. <br><br>
            Ingresa al mundo <strong>Cule</strong> </p>
        <iframe src="https://www.fcbarcelona.es/es/" width="1250" height="1000" frameborder="0"></iframe>


        <h2>DEPOR OFICIAL SITE</h2>
        <p>Visita <strong>DEPOR</strong> para ver las noticias, marcadores, calendarios, estadísticas, rumores y más del
            <u>FC Barcelona</u> . <br><br>
            Ademas puedes encontrar toda la informacion actualizada de todos los deportes a nivel mundial en este
            maravilloso sitio.
        </p>
        <iframe src="https://depor.com/noticias/fc-barcelona/" width="1250" height="1000" frameborder="0"></iframe>


     </section>

     <footer>
        <strong>JUAN CARLOS GARCIA RODAS</strong>
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
     </footer>

     </body>

     </html>

 ```




