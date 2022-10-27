========================
Procesos de facturación
========================

En función de tu modelo de negocio y la aplicación que utilices, hay diferentes formas de automatizar la creación de
facturas de clientes.

Por lo general, el sistema crea un **borrador de factura** (con información proveniente de otros documentos como
pedidos de ventas o contratos) y el usuario solo tiene que validar los borradores de facturas y enviar las
facturas por lotes (por correo ordinario o correo electrónico).

Dependiendo de tu negocio, puedes optar por una de las siguientes formas de crear borradores de facturas:

Ventas
==========

Pedido de venta ‣ Factura
---------------------------

En la mayoría de las empresas, los vendedores crean presupuestos que se convierten en pedidos de ventas una vez que
se validan. Posteriormente, se crean borradores de facturas en función del pedido de cliente. Tienes diferentes opciones
como:

   - **Facturar manualmente**: utiliza un botón en el pedido de venta para activar el borrador de la factura
   - **Factura antes de la entrega**: factura el pedido completo antes de activar el pedido de entrega
   - **Factura basada en el pedido de entrega**: La factura antes de la entrega suele ser utilizada por la aplicación de comercio electrónico cuando el cliente paga en el pedido y nosotros entregamos después. (prepago)

En cualquier otro caso de uso, se recomienda facturar manualmente permitiendo al vendedor activar la factura bajo
demanda con las siguientes opciones:

   - Facturar **todo el pedido**
   - Facturar **un porcentaje** (anticipo)
   - Facturar algunas **líneas**
   - Facturar un **anticipo fijo**.

Este proceso es válido tanto para la venta de servicios como para la venta de productos físicos.


Pedido de venta ‣ Pedido de entrega ‣ Factura
-----------------------------------------------

Los minoristas y el comercio electrónico generalmente facturan en función de las órdenes de entrega, en lugar de la
orden de ventas. Este enfoque es adecuado para empresas donde las cantidades que entrega pueden diferir de las
cantidades pedidas: alimentos (factura basada en Kg reales).

De esta manera, si entregas un pedido parcial, solo facturas por lo que realmente entregaste. Si haces pedidos atrasados
(entrega parcialmente y el resto más tarde), el cliente recibirá dos facturas, una por cada pedido de entrega.


Pedido de comercio electrónico ‣ Factura
------------------------------------------

Un pedido de comercio electrónico también activará la creación del pedido cuando esté completamente pagado.
Si permite pagar pedidos mediante cheque o transferencia bancaria, Daeris solo crea un pedido y la factura
se activará **una vez que se reciba el pago**.

Contratos
===========

Contratos regulares ‣ Facturas
-------------------------------

Si utilizas contratos, puedes activar la factura en función del tiempo y el material gastado, los gastos o las líneas
fijas de servicios / productos. Cada mes, el vendedor activará la factura en función de las actividades del contrato.
Las actividades pueden ser:

   - **Productos/servicios fijos**, procedentes de un pedido de venta vinculado a este contrato.
   - **Materiales comprados** (que volverá a facturar).
   - **Tiempo y material basado en partes de horas o compras** (subcontratación)
   - **Gastos como viajes y alojamiento** que vuelves a facturar al cliente.

Puedes facturar al final del contrato o activar facturas intermedias. Este enfoque es utilizado por las empresas de
servicios que facturan principalmente en función del tiempo y el material. Para las empresas de servicios que facturan
a un precio fijo, utilizan un pedido de venta regular.

Contratos recurrentes ‣ Facturas
-----------------------------------

Para las suscripciones, una factura se activa periódicamente, automáticamente. La frecuencia de la facturación y
los servicios/productos facturados se definen en el contrato.

Otros
========

Creación manual de una factura
-------------------------------------

Los usuarios también pueden crear facturas manualmente sin usar contratos o un pedido de ventas. Es un enfoque
recomendado si no necesitas administrar el proceso de ventas (presupuestos) o la entrega de los productos o servicios.
Incluso si generas la factura a partir de un pedido de cliente, es posible que debas crear facturas manualmente
en casos de uso excepcionales:

   - Si necesitas crear un reembolso (factura rectificativa).
   - Si necesitas ofrecer un descuento.
   - Si necesitas cambiar una factura creada a partir de un pedido de cliente.
   - Si necesitas facturar algo que no está relacionado con tu negocio principal.

