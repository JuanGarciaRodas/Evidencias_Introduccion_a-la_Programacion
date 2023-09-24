<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->


# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

# Solucion

 ```html

     <!DOCTYPE html>
     <html lang="en">

     <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Document</title>
     </head>

     <body>
     <table border="3" cellpadding="4" cellspacing="3">
     <thead>

      <tr>
        <th>Codigo</th>
        <th>Nombre</th>
        <th>Descripcion</th>
        <th>Precio</th>
        <th>Stock</th>
        <th>Fecha de creacion</th>
      </tr>
     </thead>
     <tbody>
      <tr>
        <td rowspan="2">001</td>
        <td rowspan="2">Redlemon Cuaderno Inteligente</td>
        <td>Cuaderno Inteligente Reutilizable de 50 Hojas, Borrable con Agua y con Calor, Sube Archivos y Anotaciones a
          la Nube. Ecológico, Incluye 3 Plumas de Tinta Borrable </td>
        <td>1.195.000$</td>
        <td>50</td>
        <td>21-02-2015</td>
      </tr>
      <tr>
        <td>FABRICADO CON MATERIALES DURADEROS: Cada una de las páginas está fabricada con materiales de la mejor
          calidad, por lo que son suaves y agradables al tacto, tan delgadas como el papel común pero mucho más
          resistentes, no se desprenden ni se rasgan fácilmente</td>
        <td>$399.00</td>
      </tr>

      <tr>
        <td rowspan="2">002</td>
        <td rowspan="2">Smartwatch Pulsera Inteligente</td>
        <td>Reloj Inteligente Deportivo, Reloj Deportivo Pantalla Táctil Impermeable IP67 monitores de actividad con
          Pulsómetro y Presión Arterial, Monitor de Calorías, Sueño, Podómetro, GPS Monitor de Pasos, Reloj para Mujeres
          y Hombres Pago sin contacto y notificación por teléfono inteligente Smartwatch </td>
        <td>1.435.000$</td>
        <td>120</td>
        <td>18-10-2019</td>
      </tr>
      <tr>
        <td>pantalla táctil completa de 1.72 pulgadas cubierta con un marco de aleación de aluminio, tan elegante y
          ligero de llevar, pero resistente y antiarañazos. El reloj inteligente contiene 5 diales fácilmente
          disponibles para elegir junto con otros 30 diales más dentro de la aplicación. </td>
        <td>$466.00</td>
      </tr>

      <tr>
        <td rowspan="2">003</td>
        <td rowspan="2">Bewinner Raton Portatil Inalambrico</td>
        <td>Alta Sensibilidad 1200DPI Tecnología Inalámbrica de 2.4GHz Casi sin Ruido-Wireless Touch Mouse
          Posicionamiento Preciso para Laptop Mouse Inalambrico</td>
        <td>350.000$</td>
        <td>258</td>
        <td>23-05-2021</td>
      </tr>
      <tr>
        <td>Tecnología inalámbrica de 2.4GHz -- este mouse inalámbrico con tecnología inalámbrica de 2.4GHz garantiza
          una respuesta rápida sin demora. El ratón de la computadora ergonómica con receptor USB libre, solo enchufe el
          receptor USB en la computadora, después de instalar la batería en el mouse, entonces puede fácilmente Utilice
          este mouse táctil inalámbrico </td>
        <td>$95.00</td>
      </tr>

      <tr>
        <td rowspan="2">004</td>
        <td rowspan="2">Disco Duro Externo HDD 4 TB</td>
        <td>ADATA Disco Duro Externo HDD HD710P,4 TB, Resistente a golpes,agua y polvo, certificación grado militar,
          Color Negro</td>
        <td>548.250$</td>
        <td>105</td>
        <td>28-01-2011</td>
      </tr>
      <tr>
        <td>El armazón de cama de plataforma doble ofrece una base de apoyo silenciosa, sin ruidos para un colchón; no
          se necesita somier
          Fácil de usar
          Brinda espacio de almacenamiento adicional debajo de la cama con un espacio libre vertical de aproximadamente
          13 pulgadas </td>
        <td>$115.00</td>
      </tr>
      <tr>
        <td rowspan="2">005</td>
        <td rowspan="2">ROKU - Dispositivo de transmisión HD Express</td>
        <td>(Nuevo, 2022) con Cable HDMI de Alta Velocidad y Control Remoto Simple, configuración guiada y Wi-Fi rápido
        </td>
        <td>287.451$</td>
        <td>234</td>
        <td>12-03-2020</td>
      </tr>
      <tr>
        <td>Rápido y potente EDM. Ahora más rápido que nunca, Roku Express ofrece una experiencia de transmisión HD
          perfecta para nuevos usuarios pero lo suficientemente potente para profesionales experimentados
          Configuración guiada rápida: Simplemente conéctalo y conéctalo a Internet para empezar a transmitir, es así de
          fácil </td>
        <td>$86.90</td>
      </tr>
      <tr>
        <td rowspan="2">006</td>
        <td rowspan="2">CHEELOM Audifonos Inalambricos</td>
        <td>Audifonos Blouethotth 5.2, Audifonos Inalambricos Deportivos, 30 Horas de Tiempo de Reproducción,IPX5 a
          Prueba de Agua, para Correr,Hacer Deportes y Ejercicio
        </td>
        <td>625.211$</td>
        <td>369</td>
        <td>06-05-2019</td>
      </tr>
      <tr>
        <td>Control de un solo botón con Encendido y conexión automáticos: Con el botón multifuncional en cada audífono
          puede gestionar reproducción de audio o llamadas sin esfuerzo. Audifonos Inalambricos Deportivos se encienden
          y se conectan a su dispositivo automáticamente,simplemente al retirarlos del estuche, para un uso rápido y
          fácil. Con los audífonos puestos en el estuche, se apagarán y comenzarán a recargaerse. </td>
        <td>$214.54</td>
      </tr>
      <tr>
        <td rowspan="2">007</td>
        <td rowspan="2">Bocina inteligente con reloj y Alexa</td>
        <td>Echo Dot con reloj (5ta generación, modelo 2022)MANTÉN UN AMBIENTE ACOGEDOR EN TU CASA - Controla
          dispositivos de Casa Inteligente compatibles con la voz y rutinas que activan acciones utilizando los sensores
          integrados de temperatura interior y movimiento
        </td>
        <td>1.985.687$</td>
        <td>84</td>
        <td>19-06-2022</td>
      </tr>
      <tr>
        <td>NUESTRO ECHO DOT CON EN EL MEJOR SONIDO HASTA LA FECHA - Disfruta de una experiencia de audio superior a los
          Echo Dot anteriores con Alexa, en la que obtendrás voces más nítidas, graves más profundos y sonido vibrante
          en cualquier habitación.
          MIRA EL CLIMA Y MÁS DE UN VISTAZO - El indicador LED mejorado muestra el clima, títulos de canciones y más.
        </td>
        <td>$429.90</td>
      </tr>
      <tr>
        <td rowspan="2">008</td>
        <td rowspan="2">PlayStation 5 Marvel’ Spider-Man 2 Edición de Colección</td>
        <td>Juega con dos Spider-Men Alterna rápidamente entre ambos Spider-Men mientras exploras una Nueva York de
          Marvel más amplia. Usa las habilidades del nuevo simbionte de Peter y los explosivos poderes de veneno
          bioeléctricos de Miles,
        </td>
        <td>2.489.112$</td>
        <td>589</td>
        <td>28-10-2020</td>
      </tr>
      <tr>
        <td>Juego completo para consola PS5 y DLC de contenido digital. Beneficios de preventa:* Acceso anticipado al
          Traje del Caballero araña para Peter (incluye tres variantes de color). Acceso anticipado al Traje de Araña de
          las sombras para Miles (incluye tres variantes de color). Acceso anticipado al accesorio Telaraña de captura.
          +3 puntos de habilidad. </td>
        <td>$1.254.00</td>
      </tr>
      <tr>
        <td rowspan="2">009</td>
        <td rowspan="2">Portatil Gamer
          Razer Blade 16 QHD</td>
        <td>Intel® Core ™ i9-13950HX 5.6 GH de 13.a generación.
          Almacenamiento: 1TB PCIe® 4.0 NVMe™ M.2 SSD
          GPU: RTX™ 4070, 8GB GDDR6 VRAM.
          Memoria RAM: 16GB DDR5-5600MHz
        </td>
        <td>17.125.100$</td>
        <td>25</td>
        <td>25-03-2023</td>
      </tr>
      <tr>
        <td>En este espectro más selecto de portátiles para gaming encontramos el MSI GP76 Leopard, que además se
          encuentra justo en el límite (1.999 €), y que es uno de los mejores portátiles gaming del mundo,
          específicamente pensado para los gamers. La nueva arquitectura NVIDIA Ampere presenta nuevos núcleos de
          trazado de rayos de segunda generación y núcleos de tensor de tercera generación con mayor rendimiento. </td>
        <td>$4.124.00</td>
      </tr>
      <tr>
        <td rowspan="2">010</td>
        <td rowspan="2">Tesla Model 3 2023</td>
        <td>El Tesla Model 3 es una berlina de dimensiones compactas y 100% eléctrica, del segmento D, fabricada por
          Tesla desde 2016
        </td>
        <td>368,856,000$</td>
        <td>14</td>
        <td>08-08-2023</td>
      </tr>
      <tr>
        <td>La tercera versión, denominada «Performance», cuenta con 513 CV, acelera hasta los 100 km/h en 3,3 segundos
          (una cifra más propia de un deportivo), 547 km de autonomía y una velocidad punta de 261 km/h. Esta versión
          añade un alerón de fibra de carbono, llantas de 20″, pedales de aluminio y la función exclusiva «Track Mode».
        </td>
        <td>$85.487.00</td>
      </tr>
     </body>

     </html>

 ```



