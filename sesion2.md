<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

 # Actividad: Creando mi primer sitio web

### Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

**Las páginas del sitio serán:**

- Index o página de inicio
- Acerca
- Contacto

## Solucion

### index.html

 ```html

      <!DOCTYPE html>
     <html lang="en">
     <head>
     <title>MI PRIMER SITIO WEB</title>
     </head>
     <body>

     <header>
        <h1>Mi SITIO WEB</h1>
     </header>
     <nav>
        <a href="Acerca.html">Acerca</a>
        <a href="Contacto.html">Contacto</a>
     </nav>
     <main>
        <p>Bienvenidos a mi sitio web sobre empresas XYZ</p>
        <p>Aqui encontraras informacion sobre nuestros servicios y productos</p>
     </main>
     <footer>
        <p>Copyright 2023 - Juan Garcia</p>
        <p>jcagarcia210215@gmail.com</p>
     </footer>
     <meta name> <strong>JUAN CARLOS GARCIA</strong>


     </body>
     </html>

 ```

 ### about.html

 ```html

     <!DOCTYPE html>
     <html lang="en">
      <head>
     <title>Sobre nosotros</title>
     </head>
     <body>
        <header>
        <h1>Sobre nosotros</h1>
     </header>
     <nav>
        <a href="Index.html">Inicio</a>
        <a href="Contacto.html">Contacto</a>
     </nav>
     <section>
        <h2>Hsitoria</h2>
        <p>Fundada en 2010...</p>
        <article>
            <h3>Mision y Vision</h3>
            <p>Nuestra mision es ...</p>
        </article>
     </section>
     <footer>
        <p>Copyright 2023 - Juan Garcia</p>
     </footer>
    
      </body>
     </html>

 ```

### contact.html

 ```html

     <!DOCTYPE html>
     <html lang="en">
     <head>
     <title>Contacto</title>
     </head>
     <body>
     <header>
        <h1>Cotacto</h1>
     </header>
     <nav>
        <a href="Index.html">Inicio</a>
        <a href="Acerca.html">Acerca</a>
     </nav>
     <main>
        <form>
            <label for="Nombre">Nombre</label>
            <input type="text" id="Nombre"><br>

            <label for="email">Email:</label>
            <input type="email" id="Email"><br>

            <label for="mensaje">mensaje</label><br>
            <textarea id="mensaje"></textarea><br>

        </form>
        <aside>
            <h3>Ubicacion</h3>
            <p>calle falsa 123 </p>
        </aside>

     </main>
     <footer>
        <p>Copyright 2023 Juan Garcia</p>
     </footer>
     </body>
     </html>

 ```
