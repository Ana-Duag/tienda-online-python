# Tienda online.Simulación de e-commerce en Python para la gestión de inventarios, clientes, compras y ventas.

### Proyecto desarrollado por **Ana Dueñas**, Agosto 2025.

---

## Contenido

Clase `TiendaOnline` para la gestión de:

- Inventario de productos.
- Registro de clientes.
- Compras y ventas.

### Métodos implementados

- Agregar, buscar, actualizar y eliminar productos.
- Calcular valor del inventario y ventas totales.
- Registrar clientes y ver su historial de compras.
- Realizar compras y procesar pagos.

### Características adicionales

- Validaciones de entradas y manejo de errores con `try...except`
- Uso de bucles `for` y `while`, condicionales `if/elif/else` y `list comprehension` para simplificar el código
- Comentarios en líneas complejas o donde se incluyó lógica adicional
- Uso de `print`/`return` según requerimientos del examen o la lógica del método

---

## Ejecución

Crear una instancia de la clase:

```python
tienda = TiendaOnline()


Llamadas a métodos

tienda.agregar_producto(nombre, precio, cantidad)
tienda.ver_inventario()
tienda.buscar_producto(nombre)
tienda.actualizar_stock(nombre, cantidad)
tienda.eliminar_producto(nombre)
tienda.calcular_valor_inventario()
tienda.agregar_cliente(nombre_cliente, email)
tienda.ver_clientes()
carrito = tienda.realizar_compra(nombre_cliente)
tienda.procesar_pago(total_compra)
tienda.registrar_compra(nombre_cliente, carrito)
tienda.ver_compras_cliente(nombre_cliente)
tienda.calcular_ventas_totales()


---

Nota: Durante la ejecución, algunos métodos solicitan inputs del usuario.
