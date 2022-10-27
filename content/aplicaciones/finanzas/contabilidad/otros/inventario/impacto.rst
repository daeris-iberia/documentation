===========================================================================
Impacto en la valoración del precio promedio cuando se devuelven productos
===========================================================================

Como se indica en la *página de valoración de inventario*, el coste promedio es uno de los posibles métodos de coste
que puedes usar en la valoración perpetua de inventario.

.. seealso::
   * :doc:`../../../../inventario_y_fabricacion/inventario/gestion/valoracion`

Este documento responde a una pregunta recurrente orientada a empresas que usan ese método para hacer su valoración
de inventario: ¿cuál es el impacto de un envío devuelto a su proveedor en el coste promedio y los asientos contables?

Este documento es **exclusivamente** para el caso de uso específico de valoración perpetua (opuesto al periódico) y en
el método de coste de precio promedio.

Definición de coste promedio
=============================

El método de coste promedio calcula el coste del inventario final y el coste de productos vendidos con base en el
coste promedio ponderado del inventario.

El coste promedio ponderado por unidad se basa en calcular el coste de cada unidad comprada a partir del precio pagado
por ella, realizando posteriormente un promedio. El valor total del stock de este producto será igual al promedio del
coste de todos los productos.

Cuando llegan nuevos productos a un almacén, se vuelve a calcular el coste promedio.

Cuando los productos salen del almacén: el coste promedio **no cambia**.

Definir el precio de compra
----------------------------

El precio de compra se estima en la recepción de los productos (si no se ha recibido la factura del proveedor se vuelven
a evaluar en la recepción de la factura del proveedor). El precio de compra incluye el importe que pagas por los
productos, pero también puede incluir costes adicionales, como los costes en destino.


Ejemplo de coste promedio
==========================

.. list-table:: Ejemplo de coste promedio
   :widths: 40 15 15 15 15
   :header-rows: 1

   * - Operación
     - Valor delta
     - Valor de inventario
     - Cantidad a mano
     - Coste promedio
   * -
     -
     - 0€
     - 0
     - 0€
   * - Recibir 8 productos a 10€
     - +8*10€
     - 80€
     - 8
     - 10€
   * - Recibir 4 productos a 16€
     - +4*16€
     - 144€
     - 12
     - 12€
   * - Entregar 10 productos
     - -10*12€
     - 24€
     - 2
     - 12€

Al principio, el coste promedio se establece en 0 porque no hay ningún producto en el inventario. Cuando se realiza
la primera recepción, el coste promedio se convierte, lógicamente, en el precio de compra.

En la segunda recepción, el coste promedio se actualiza porque el valor del inventario total ahora es 80€ + 4*16€ = 144€.
Como tenemos 12 unidades a mano, el precio promedio por unidad es 144€ / 12 = 12€.

Por definición, la entrega de 10 productos no cambia el coste promedio. De hecho, el valor del inventario ahora es 24€
porque solo nos quedan 2 unidades de cada uno 24€ / 2 = 12€.

Caso de uso de compras devueltas
=================================

En caso de que un producto se devuelva a tu proveedor después de la recepción, el valor del inventario se reduce usando
la fórmula de coste promedio (no al precio inicial de estos productos).

Lo que significa que la tabla anterior se actualizará así:

.. list-table:: Caso de uso de compras devueltas
   :widths: 40 15 15 15 15
   :header-rows: 1

   * - Operación
     - Valor delta
     - Valor de inventario
     - Cantidad a mano
     - Coste promedio
   * -
     -
     - 24€
     - 2
     - 12€
   * - Devolución de 1 producto que se compró inicialmente a 10€
     - -1*12€
     - 12€
     - 1
     - 12€

Explicación: contraejemplo
Recuerda que la definición de Coste promedio dice que no actualizamos el coste promedio de un producto que sale del
inventario. Romper esta regla podría llevar a inconsistencias en tu inventario.

Por ejemplo, a continuación, te presentamos el escenario donde entregas una pieza al cliente y devuelves la otra a
tu proveedor (al coste que la compraste). Esta es la operación:

.. list-table:: Caso de uso de compras devueltas (caso incorrecto)
   :widths: 40 15 15 15 15
   :header-rows: 1

   * - Operación
     - Valor delta
     - Valor de inventario
     - Cantidad a mano
     - Coste promedio
   * -
     -
     - 24€
     - 2
     - 12€
   * - Cliente envía 1 producto
     - -1*12€
     - 12€
     - 1
     - 12€
   * - Devolución de 1 producto que se compró inicialmente en $10
     - -1*10€
     - **2€**
     - **0**
     - 12€

Como puedes ver en este ejemplo, esto resultado no es correcto: una valoración de inventario de 2€ para 0 piezas en el
almacén. El escenario correcto debería ser la devolución de los productos al coste promedio actual:

.. list-table:: Caso de uso de compras devueltas (caso correcto)
   :widths: 40 15 15 15 15
   :header-rows: 1

   * - Operación
     - Valor delta
     - Valor de inventario
     - Cantidad a mano
     - Coste promedio
   * -
     -
     - 24€
     - 2
     - 12€
   * - Cliente envía 1 producto
     - -1*12€
     - 12€
     - 1
     - 12€
   * - Devolución de 1 producto que se compró inicialmente en $10
     - -1*10€
     - **0€**
     - **0**
     - 12€

Por otro lado, usar el coste promedio para valorar la devolución asegura una valoración de inventario correcta
en todo momento.