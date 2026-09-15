
Menú Interactivo para Cafetería

Descripción general

El proyecto consiste en el desarrollo de una aplicación web interactiva diseñada para mejorar y agilizar la experiencia de los clientes dentro de una cafetería.

La plataforma permitirá a los usuarios consultar el menú digital, visualizar los productos disponibles junto con sus precios y detalles, seleccionar los productos que desean consumir y agregarlos a un carrito de compras.

El cliente podrá modificar las cantidades de los productos, eliminar elementos del carrito y revisar el valor total de su pedido antes de confirmarlo.

Una vez confirmado el pedido, el sistema generará un **ticket o resumen de compra** que mostrará los productos seleccionados, sus cantidades, precios, subtotal y total a pagar. Este ticket podrá ser presentado en caja para completar el pago.

La solución busca reducir los tiempos de espera, evitar filas innecesarias y mejorar la organización del proceso de pedidos

 Objetivo general

Desarrollar una aplicación web interactiva para una cafetería que permita a los clientes consultar el menú, seleccionar productos, gestionar un carrito de compras y generar un ticket con el resumen del pedido, facilitando y agilizando el proceso de atención.

 Objetivos específicos

* Crear una interfaz visual atractiva, intuitiva y fácil de utilizar.
* Permitir la visualización de las diferentes categorías de productos.
* Mostrar información relevante de cada producto, como nombre, imagen, descripción y precio.
* Implementar un sistema de carrito de compras.
* Permitir agregar productos al carrito.
* Permitir aumentar o disminuir la cantidad de cada producto.
* Permitir eliminar productos del carrito.
* Calcular automáticamente el subtotal y el total del pedido.
* Implementar una opción para confirmar el pedido.
* Generar un ticket con el resumen completo de la compra.
* Reducir el tiempo que los clientes deben pasar realizando un pedido en caja.

 Usuarios del sistema:
 
 Cliente

El cliente será el usuario principal de la aplicación.

Podrá:

* Consultar el menú.
* Explorar las categorías.
* Visualizar productos.
* Consultar precios y descripciones.
* Agregar productos al carrito.
* Modificar las cantidades.
* Eliminar productos.
* Confirmar su pedido.
* Visualizar y presentar el ticket generado.

Administrador

Inicialmente, el sistema puede funcionar sin un panel administrativo. Sin embargo, como mejora futura se podrá implementar un rol de administrador.

El administrador podría:

* Agregar productos.
* Editar productos.
* Eliminar productos.
* Modificar precios.
* Administrar el inventario.
* Consultar pedidos.
* Visualizar estadísticas de ventas.

Funcionalidades principales

Visualización del menú

La página deberá mostrar los productos disponibles en la cafetería.

Cada producto podrá incluir:

* Imagen.
* Nombre.
* Descripción.
* Precio.
* Botón para agregar al carrito.
* personalizarlo al gusto.

Ejemplo:

| Producto       | Descripción             | Precio |
| -------------- | ----------------------- | -----: |
| Café Americano | Café negro tradicional  | $5.000 |
| Capuchino      | Café con leche y espuma | $7.000 |
| Latte          | Café espresso con leche | $8.000 |
| Croissant      | Panadería tradicional   | $6.000 |
| Muffin         | Pastel individual       | $5.500 |

 Categorías de productos

Los productos podrán organizarse por categorías para facilitar la navegación.

Por ejemplo:

* Cafés
* Bebidas frías
* Panadería
* Postres
* Snacks

El usuario podrá seleccionar una categoría y visualizar únicamente los productos correspondientes.

Carrito de compras

El sistema deberá incluir un carrito donde se almacenen temporalmente los productos seleccionados.

El carrito mostrará:

* Nombre del producto.
* Precio individual.
* Cantidad seleccionada.
* Subtotal del producto.
* Botón para aumentar cantidad.
* Botón para disminuir cantidad.
* Botón para eliminar.

Ejemplo:

| Producto  | Precio | Cantidad | Subtotal |
| --------- | -----: | -------: | -------: |
| Capuchino | $7.000 |        2 |  $14.000 |
| Croissant | $6.000 |        1 |   $6.000 |
total: $20.000**
 Modificación de cantidades

El usuario podrá modificar la cantidad de cada producto.

Se utilizarán botones para:

* Aumentar la cantidad.
* Disminuir la cantidad.

Si la cantidad llega a cero, el producto podrá eliminarse automáticamente del carrito.

 Eliminación de productos

Cada producto del carrito tendrá un botón para eliminarlo completamente.

Después de eliminar un producto, el sistema actualizará automáticamente el subtotal y el total.

 Cálculo automático

El sistema calculará automáticamente los valores del pedido.

Cada vez que el usuario agregue, elimine o modifique un producto, el total deberá actualizarse automáticamente.


Generación del ticket

Después de confirmar el pedido, el sistema generará un ticket.

El ticket incluirá:

* Nombre de la cafetería.
* Número del pedido.
* Fecha.
* Hora.
* Lista de productos.
* Cantidades.
* Precio de cada producto.
* Subtotal.
* Total.
* Mensaje de agradecimiento.

Ejemplo:
================================
        ARTEMIS COFFEE
================================

Pedido #001

Fecha: 15/09/2026
Hora: 10:30 AM

--------------------------------
Producto        Cant.    Precio
--------------------------------

Capuchino         2     $14.000
Croissant         1      $6.000

--------------------------------

TOTAL:                   $20.000

Gracias por tu compra.

Presenta este ticket en caja.
================================


 Flujo de uso del sistema

1. El cliente ingresa a la página web.
2. Visualiza el menú principal.
3. Explora las diferentes categorías de productos.
4. Selecciona los productos que desea consumir.
5. Agrega los productos al carrito.
6. Revisa los productos seleccionados.
7. Modifica las cantidades si es necesario.
8. Elimina productos que ya no desea.
9. El sistema calcula automáticamente el total.
10. El cliente confirma el pedido.
11. El sistema genera un ticket.
12. El cliente presenta el ticket en caja.
13. Se realiza el pago.

Tecnologías utilizadas

| Tecnología | Uso                                           |
| ---------- | --------------------------------------------- |
| HTML5      | Estructura de la página web                   |
| CSS3       | Diseño y estilos de la interfaz               |
| JavaScript | Interactividad, carrito y cálculo de pedidos  |
| Python     | Lógica del servidor y procesamiento           |
| Flask      | Framework para conectar frontend y backend    |
| JSON       | Posible almacenamiento de productos           |
| SQLite     | Posible almacenamiento de productos y pedidos |

 Resultado esperado

Al finalizar el proyecto se espera contar con una aplicación web funcional que permita digitalizar el proceso básico de pedidos de una cafetería.

El cliente podrá realizar el proceso completo desde la selección de productos hasta la generación de un ticket, mientras que la cafetería podrá ofrecer una experiencia más rápida, organizada y moderna.

El proyecto permitirá aplicar conocimientos de **HTML5, CSS3, JavaScript y Python**, integrando elementos de desarrollo frontend y backend.

En conclusión, la aplicación funcionará como un sistema de **menú digital, carrito de compras y generación de pedidos**, orientado a agilizar la atención de los clientes y reducir los tiempos de espera en caja.
