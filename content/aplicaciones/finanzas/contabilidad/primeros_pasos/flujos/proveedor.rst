==================================================
Desde la factura del proveedor hasta el pago
==================================================

Una vez hayas realizado el registro de las facturas de los proveedores en Daeris, puedes pagar el importe correcto con
facilidad, precisando el momento correcto en función de las políticas de facturación de tu proveedor.

Daeris dispone de informes que te permiten identificar facturas vencidas pendientes de pago.

Si deseas controlar las facturas de proveedor recibidas, puedes usar la aplicación de Compra, la cual te permite
controlarlas y completarlas automáticamente si provienen de un pedido de compra previo.

Registro de factura de proveedor
=================================
Cuando recibes una factura de proveedor, puedes registrarla desde
:menuselection:`Facturación / Contabilidad --> Proveedores --> Facturas` haciendo clic sobre el botón **Crear**
o desde la tarjeta del diario **Facturas de proveedores** del **Tablero** de contabilidad,
donde se encuentra el botón **Cargar** el cual te permite anexar un fichero a una nueva factura y el botón
**Crear manualmente** que te permite crear una nueva factura.

.. example::
   Es posible crear una factura de proveedor desde el botón **Cargar** y desde el botón **Crear manualmente**.

   .. image:: proveedor/proveedor01.png
      :align: center
      :alt: Registro de factura de proveedor

Para registrar una nueva factura de proveedor, informa el **proveedor**, la **referencia de la factura**, agrega
las **líneas de producto**, asegurándote de tener las **cantidades** de producto, **impuestos** y **precios** correctos.

Para registrar una nueva factura de proveedor, informa el **proveedor**, la **referencia de la factura**, agrega las **líneas de producto**, asegurándote de tener las **cantidades** de producto, **impuestos** y **precios** correctos.

.. note::
   Es posible que debas configurar los precios de tus productos sin impuestos debido a que Daeris calculará los impuestos por ti, una vez introducidos los importes.

.. example::
   En el siguiente ejemplo, se crea una factura al proveedor International Wood por la compra de dos productos.

   .. image:: proveedor/proveedor02.png
      :align: center
      :alt: Registro de factura de proveedor

Confirmar la factura de proveedor
===================================

Una vez confirmada la factura de proveedor, se generará un asiento de diario que puede variar en función del paquete
contable que estes usando (*depende del país*).

Para la mayoría de países, el asiento de diario usará las siguientes cuentas:

   - **Cuentas por pagar**: se definen en el formulario del proveedor
   - **Impuestos**: se definen en los productos y en las líneas de la factura
   - **Gastos**: se definen en la línea del artículo del producto adquirido

Puedes consultar los apuntes contables generados por la factura, sobre la pestaña **Apuntes contables**.

.. example::
   Siguiendo el ejemplo anterior, se generan los siguientes apuntes:

   .. image:: proveedor/proveedor03.png
      :align: center
      :alt: Confirmar la factura de proveedor

Pagar una factura de proveedor
===============================
Para crear directamente un pago de una factura de proveedor publicada, puedes hacer clic sobre el botón
**Registrar pago** sobre la parte superior del formulario.

Sobre el formulario de registro de pago, selecciona el método de pago y el importe que deseas pagar.

De forma predeterminada, se propone realizar el pago sobre la totalidad del importe restante. Sobre el campo **Nota**,
es recomendable informar el número de la factura de proveedor para que sirva de referencia.

.. example::
   Siguiendo el ejemplo anterior, se procede a realizar el pago:

   .. image:: proveedor/proveedor04.png
      :align: center
      :alt: Pagar una factura de proveedor

Puedes registrar un pago a un proveedor directamente sin aplicarlo a una factura de proveedor. Para ello, navega a
:menuselection:`Facturación / Contabilidad --> Proveedores --> Pagos`.
Podrás conciliar este pago directamente desde la factura de proveedor.

Seguimiento de pagos
========================

Para obtener una lista de facturas de proveedor pendientes de pago y sus respectivas fechas de vencimiento, puedes usar
el informe **Lista de deudas**.
Para ello, accede a :menuselection:`Facturación / Contabilidad --> Contabilidad --> Lista de deudas` y filtra por **Pagos**.


.. example::
   Recuerda usar el filtro **pagos** para obtener las facturas de proveeedor.

   .. image:: proveedor/proveedor05.png
      :align: center
      :alt: Seguimiento de pagos
