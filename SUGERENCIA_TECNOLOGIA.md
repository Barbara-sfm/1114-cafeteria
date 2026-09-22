# Sugerencia de tecnología para el MVP

## Propuesta de las autoras

La documentación del proyecto propone usar **HTML5, CSS3, JavaScript y Python**. También menciona Flask como una posible tecnología para conectar un frontend con un backend.

## Recomendación para el primer incremento

Para el MVP se recomienda comenzar con **HTML, CSS y JavaScript**:

- **HTML5**: estructura del menú, formulario del cliente, carrito y ticket.
- **CSS3**: diseño visual y adaptación a celular.
- **JavaScript**: catálogo de productos, carrito, cantidades, total y generación del ticket en el navegador.

Esta decisión permite construir y comprobar el flujo completo de pedido sin introducir todavía un servidor ni una base de datos.

## Python y Flask: siguiente incremento

**Python con Flask** queda recomendado para una segunda etapa, cuando el proyecto necesite guardar pedidos, administrar productos o consultar historial. En ese punto también se podrá evaluar SQLite como base de datos local.

## Límite del MVP

El MVP genera un ticket para que el cliente pague en caja. No debe procesar tarjetas, pagos en línea ni almacenar información financiera.

## Ruta de aprendizaje

1. Crear una página estática con menú y categorías.
2. Implementar el carrito y el cálculo del total con JavaScript.
3. Generar el ticket con nombre, mesa y productos.
4. Probar cantidades, eliminación de productos y total.
5. Añadir Python, Flask y almacenamiento solo cuando el flujo local funcione correctamente.
