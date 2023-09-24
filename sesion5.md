<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

# Actividad: Diseñar un formulario de pedido de un producto

**Objetivo:**

**Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.**

**Instrucciones:**

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.


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
     <form action=""></form>
     <h1>Formulario de pedido de un Producto</h1>
     <br>
     <div>
        <label for="idproducto">Nombre del Producto</label>
        <input type="text" id="idproducto" autofocus required placeholder="digita el nombre del producto">
     </div>
     <br>
     <div>
        <label for="idUnidades">Unidades</label>
        <input type="number" required name="Unidades" min="1" value="1" id="idUnidades" placeholder="cantidad">
     </div>
     <br>
     <div>
        <label for="idPrecio unitario">Precio por unidad</label>
        <input type="number" name="Precio unidad" id="idPrecio unitario" placeholder="Precio unitario">
     </div>
     <br>
     <div>
        <label for="idPrecio total">Precio Total</label>
        <input type="number" name="Precio Total" id="idPrecio total" placeholder="Valor Total">
     </div>
     <br>
     <div>
        <label for="idDireccion de envio">Direccion de envio</label>
        <input type="text" name="Tu Direccion" required id="idDireccion de envio" placeholder="Direccion de entrega">
     </div>
     <br>
     <br>
     <h2>INFORMACION DE CONTACTO</h2>
     <br>
     <div> <label for="idNombre Completo">Nombre Completo</label>
        <input type="text" id="idNombre Completo" required placeholder="Ingrese su nombre Completo">
     </div>
     <br>
     <div> <label for="idCorreo electronico">Correo electronico</label>
        <input type="email" id="idCorreo electronico" placeholder="digita tu correo electronico">
     </div>
     <br>
     <div> <label for="idNumero de Telefono">Telefono de Contacto</label>
        <input type="tel" id="idNumero de Telefono" required placeholder="Ingrese su numero de Contacto">
     </div>
     <br>

     <h2>Termina tu Compra</h2>

     <div>
        <h4>METODOS DE PAGO</h4>
        <input type="radio" id="Efectivo" name="Metodos de Pagos" value="Efectivo">
        <label for="Efectivo">Efectivo</label>
        <input type="radio" id="Tarjeta de Credito" name="Metodos de Pagos" value="Tarjeta de Credito">
        <label for="Tarjeta de Credito">Tarjeta de Credito</label>
        <input type="radio" id="PSE" name="Metodos de Pagos" value="PSE">
        <label for="PSE">PSE</label>
        <input type="radio" id="Transferencia" name="Metodos de Pagos" value="Transferencia">
        <label for="Transferencia">Transferencia</label>

     </div>
     <br>
     <div>
        <label for="fecha de Entrega">Fecha de Entrega</label><br>
        <input type="date" name="fecha de Entrega" id="fecha de entrega">
        
     </div>
     <br>
     <div>
        <label for="comentarios">Comentarios</label><br>
        <textarea name="comentarios" id="comentarios" placeholder="Ingrese sus comentarios aquí" rows="5"
            cols="30"></textarea>
            
     </div>
     <br>
     <div>
     <button type="submit">Enviar</button>
     </div>
    
     </body>

     </html>

 ```

