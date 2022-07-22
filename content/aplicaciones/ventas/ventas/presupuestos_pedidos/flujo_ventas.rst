===============
Flujo de ventas
===============

Un **presupuesto de venta** es una oferta formal que se presenta a un cliente para establecer una negociación sobre la
venta de un producto o servicio. Un **pedido de venta** es un presupuesto aceptado por el cliente. Por lo tanto, la
principal diferencia entre un presupuesto y un pedido de venta es el estado en el que se encuentra la negociación (en
trámite o aceptada por el cliente).

.. youtube:: IlvwZ4DrFbE
    :align: right
    :width: 786
    :height: 442

Crear un presupuesto de venta
=============================

Para crear un presupuesto de venta navega a la pantalla :menuselection:`Ventas --> Pedidos --> Presupuestos`, y pulsa el
botón *Crear*:

.. image:: flujo_ventas/crear-presupuesto.png
   :align: center
   :alt: Crear presupuesto de venta

Al crear un nuevo presupuesto es posible informar los siguientes campos:

-  **Cliente**: Cliente que realiza el pedido.

-  **Dirección de factura**: La información se hereda del cliente.

-  **Dirección de entrega**: La información se hereda del cliente.

-  **Plantilla de presupuesto**: Permite seleccionar la plantilla de presupuesto de entre el listado de plantillas disponibles.

-  **Expiración**: Fecha hasta la que será válido el presupuesto.

-  **Tarifa**: Tarifa con la que se calculará el precio de los productos asociados al presupuesto.

-  **Plazos de pago**: Permite seleccionar de entre los distintos plazos de pago disponibles.

-  **Modo de pago**: Permite seleccionar de entre los distintos modos de pago disponibles.

.. image:: flujo_ventas/formulario-detalle-presupuesto.png
   :align: center
   :alt: Formulario de detalle de presupuesto de venta

.. seealso::
   * :ref:`ventas/presupuestos_pedidos/plantillas_presupuestos`
   * :ref:`ventas/presupuestos_pedidos/validez`
   * :doc:`../productos_precios/precios/precios`

En la pestaña de *Líneas del pedido*, sobre cada línea, puedes informar los diferentes productos asociados al presupuesto,
así como la cantidad, el precio, etc. También es posible informar los términos y condiciones del presupuesto, que serán
incluidos en el presupuesto de venta enviado al cliente.

.. image:: flujo_ventas/lineas-pedido.png
   :align: center
   :alt: Líneas del pedido de venta

.. seealso::
   * :ref:`ventas/presupuestos_pedidos/terminos`

En la pestaña de *Productos opcionales*, se pueden incorporar líneas opcionales de pedido:

.. image:: flujo_ventas/productos-opcionales.png
   :align: center
   :alt: Productos opcionales del presupuesto de venta

En la pestaña de *Otra información*, es posible incorporar información relacionada con el envío, con la facturación y
con la propia venta:

.. image:: flujo_ventas/otra-informacion-presupuesto.png
   :align: center
   :alt: Otra información del presupuesto de venta

Una vez completados los campos necesarios, pulsa el botón *Guardar*. Al guardar el presupuesto, se genera un código de
presupuesto que servirá para su posterior seguimiento:

.. image:: flujo_ventas/numero-presupuesto.png
   :align: center
   :alt: Número del presupuesto de venta

Enviar un presupuesto de venta por correo electrónico
=====================================================

.. seealso::
   * :doc:`../../../varios/correo_electronico/enviar_correos`

Para enviar un presupuesto de venta por correo electrónico, navega a la pantalla :menuselection:`Ventas --> Pedidos --> Presupuestos`,
accede al detalle de un presupuesto y pulsa el botón **Enviar por correo electrónico**:

.. image:: flujo_ventas/enviar-presupuesto-correo.png
   :align: center
   :alt: Enviar presupuesto de venta por correo electrónico

El sistema abrirá un asistente e informará la plantilla de correo electrónico de presupuestos, anexando el presupuesto
en formato PDF:

.. image:: flujo_ventas/enviar-presupuesto-correo-2.png
   :align: center
   :alt: Enviar presupuesto de venta por correo electrónico (2)

Una vez completados los campos necesarios pulsa el botón *Enviar*. Tras hacer esto, el estado del presupuesto cambiará
a *Presupuesto enviado*:

.. image:: flujo_ventas/presupuesto-enviado.png
   :align: center
   :alt: Presupuesto de venta enviado

Pasados unos minutos, el cliente recibirá un correo con el presupuesto adjunto en formato PDF.

Confirmar un pedido de venta
============================

Para confirmar un pedido de venta, navega a la pantalla :menuselection:`Ventas --> Pedidos --> Presupuestos` y accede al
detalle de un presupuesto.

Independientemente de la forma de contacto del cliente con el gestor del equipo de ventas, cuando establecen comunicación
y llegan a un acuerdo, el gestor introduce los términos en el presupuesto, informando el precio unitario de cada uno de
los productos a adquirir.

Una vez ha establecido todos los términos sobre el presupuesto, debe confirmar el pedido mediante el botón **Confirmar**:

.. image:: flujo_ventas/confirmar-presupuesto.png
   :align: center
   :alt: Confirmar presupuesto de venta

Esta acción transforma el presupuesto en pedido de venta y genera una orden de entrega pendiente de tramitar, disponible
mediante el botón *Entrega*:

.. image:: flujo_ventas/presupuesto-confirmado.png
   :align: center
   :alt: Presupuesto de venta confirmado

Entregar productos de un pedido de venta
========================================

Para entregar los productos de un pedido de venta, navega a la pantalla :menuselection:`Ventas --> Pedidos --> Pedidos`
y accede al detalle de un pedido. Una vez hayas entregado los productos del pedido, pulsa el botón *Entrega*:

.. image:: flujo_ventas/entrega-pedido.png
   :align: center
   :alt: Entrega del pedido de venta

La aplicación navegará al detalle de la entrega del producto. En el detalle de la entrega, pulsa el botón
*Comprobar disponibilidad*, que comprueba la disponibilidad del producto vendido en el almacén:

.. image:: flujo_ventas/comprobar-disponibilidad.png
   :align: center
   :alt: Comprobar disponibilidad de los productos

Si todo ha ido bien, el estado de la entrega cambiará a *Preparado*.

.. note::
   Si no tienes disponibilidad de alguno de los productos a entregar, o si el stock no está actualizado en el sistema,
   realiza las compras, fabricaciones o ajustes de inventario necesarios.

A continuación, pulsa el botón *Validar*:

.. image:: flujo_ventas/validar-entrega.png
   :align: center
   :alt: Validar entrega del pedido

El sistema solicitará confirmación para procesar todas las cantidades reservadas:

.. image:: flujo_ventas/transferencia-inmediata.png
   :align: center
   :alt: Transferencia inmediata de una orden de entrega

Pulsa el botón *Aplicar*. Tras esto, se actualizará el estado de la entrega a *Hecho*:

.. image:: flujo_ventas/entrega-hecha.png
   :align: center
   :alt: Orden de entrega hecha

Crear la factura de un pedido de venta
======================================

Para crear la factura de un pedido de venta, navega a la pantalla :menuselection:`Ventas --> Pedidos --> Pedidos` y accede
al detalle de un pedido. Sobre el pedido de venta, puedes crear la factura mediante el botón **Crear Factura**:

.. image:: flujo_ventas/crear-factura.png
   :align: center
   :alt: Crear factura de un pedido de venta

El sistema permitirá seleccionar los importes a facturar de entre una lista de opciones disponibles:

.. image:: flujo_ventas/orden-de-facturacion.png
   :align: center
   :alt: Orden de facturación

Una vez seleccionada la opción correspondiente, pulsa el botón *Crear y ver factura*. Esta acción generará un borrador
de factura con los datos del pedido seleccionado:

.. image:: flujo_ventas/borrador-factura.png
   :align: center
   :alt: Borrador de factura

Una vez revisada la factura, pulsa el botón *Confirmar*:

.. image:: flujo_ventas/confirmar-factura.png
   :align: center
   :alt: Confirmar factura

A continuación, puedes enviar la factura al cliente mediante el botón *Enviar e Imprimir*:

.. image:: flujo_ventas/enviar-imprimir-factura.png
   :align: center
   :alt: Enviar e imprimir factura

El sistema abrirá un asistente e informará la plantilla de correo electrónico de facturas, anexando la factura en formato PDF:

.. image:: flujo_ventas/enviar-factura.png
   :align: center
   :alt: Enviar factura por correo electrónico

Una vez completados los campos necesarios pulsa el botón *Enviar e Imprimir*. Tras hacer esto, se realizará el envío del
correo al cliente y se descargará la factura en formato PDF.

Por último, pulsa el botón *Registrar pago*, una vez se hayan realizado los pagos correspondientes:

.. image:: flujo_ventas/registrar-pago-factura.png
   :align: center
   :alt: Registrar pago de la factura

La aplicación desplegará un formulario donde especificar los detalles del pago:

.. image:: flujo_ventas/crear-pago-factura.png
   :align: center
   :alt: Crear pago de la factura

Una vez completados los campos necesarios, pulsa el botón *Crear pago*.

Si vuelves al detalle del pedido de venta, puedes consultar la factura emitida:

.. image:: flujo_ventas/facturas-pedido-ventas.png
   :align: center
   :alt: Facturas asociadas al pedido de ventas

.. seealso::
   * :doc:`../metodo_facturacion/anticipos`

.. _ventas/presupuestos_pedidos/enviar_whatsapp_pedidos_venta:

Enviar un mensaje de WhatsApp en un pedido de venta
===================================================

.. seealso::
   * :doc:`../../../varios/whatsapp`

Es posible enviar un WhatsApp a un cliente desde el formulario de pedidos de venta. Para ello, debes navegar a la
pantalla :menuselection:`Ventas --> Pedidos --> Pedidos`, y acceder al detalle de un pedido.

Desde esta pantalla, aparecerá un botón que permitirá enviar un mensaje de WhatsApp:

.. image:: flujo_ventas/detalle-pedido-enviar-whatsapp.png
   :align: center
   :alt: Enviar WhatsApp desde el detalle de un pedido de venta

.. note::
   El número de teléfono móvil del cliente debe estar informado con formato internacional (por ejemplo, +33123456789).

El sistema desplegará un formulario desde donde podrás redactar el mensaje de WhatsApp o seleccionar una plantilla que
informe el mensaje de forma automática:

.. image:: flujo_ventas/formulario-enviar-whatsapp.png
   :align: center
   :alt: Formulario para enviar WhatsApp en un pedido de venta

Una vez informado el mensaje, debes pulsar el botón *Enviar*.

En caso de estar conectado a la aplicación mediante un dispositivo de escritorio, el sistema tratará de establecer
conexión mediante la aplicación WhatsApp Web, para lo cual, habrá que escanear el código QR mostrado en pantalla, e
iniciar sesión en tu cuenta de WhatsApp.

Por otro lado, en caso de estar conectado a la aplicación mediante un dispositivo móvil, el sistema tratará de enviar
el mensaje mediante la aplicación WhatsApp instalada en el dispositivo.

Una vez enviado el mensaje desde WhatsApp, cierra la ventana del mensaje mediante la cruz ubicada en la parte superior
derecha del formulario:

.. image:: flujo_ventas/cerrar-formulario-enviar-whatsapp.png
   :align: center
   :alt: Cerrar formulario para enviar WhatsApp en un pedido de venta

Reservar un producto sin existencias a un cliente
=================================================

Para reservar un producto del que no se dispone de existencias, genera un nuevo presupuesto desde la pantalla
:menuselection:`Ventas --> Pedidos --> Presupuestos`. Al seleccionar el producto en las líneas del pedido, el sistema
mostrará un mensaje informando de que no se dispone de existencias del producto seleccionado:

.. image:: flujo_ventas/disponibilidad-producto-pedido.png
   :align: center
   :alt: Disponibilidad de un producto en un pedido de ventas

Una vez completados los datos del presupuesto, y tras confirmar el pedido, el sistema generará una entrega que se podrá
consultar desde el botón de entregas del formulario del pedido:

.. image:: flujo_ventas/entregas-pedido.png
   :align: center
   :alt: Entregas del pedido de venta

Al no disponer de existencias, si pulsas el botón *Comprobar disponibilidad* de la entrega, el sistema no reservará las
cantidades necesarias de producto, impidiendo avanzar en la entrega del producto al cliente:

.. image:: flujo_ventas/producto-no-disponible-entrega.png
   :align: center
   :alt: Producto no disponible en la entrega de un pedido

Si finalmente el producto llega con retraso o no llega, y el cliente decide cancelar el pedido, puedes cancelar la
entrega mediante el botón *Cancelar*:

.. image:: flujo_ventas/cancelar-entrega.png
   :align: center
   :alt: Cancelar la entrega de un pedido

Del mismo modo, podrás cancelar el pedido mediante el botón *Cancelar*.

Por el contrario, si finalmente recibes las existencias del producto, y vuelves a comprobar la disponibilidad en la
entrega, se realizará la reserva del producto y podrás continuar con el proceso de venta. Para ello, deberás pulsar el
botón *Validar*:

.. image:: flujo_ventas/validar-entrega-2.png
   :align: center
   :alt: Validar la entrega de un pedido

Si todo ha ido bien, la entrega quedará marcada como hecha, cosa que indica que el producto ha sido entregado al cliente
de forma correcta:

.. image:: flujo_ventas/entrega-hecha.png
   :align: center
   :alt: Orden de entrega hecha