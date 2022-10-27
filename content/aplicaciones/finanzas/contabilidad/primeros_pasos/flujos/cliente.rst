===========================================
Desde la factura de cliente hasta el cobro
===========================================

Daeris es compatible con múltiples flujos de trabajo de facturación y pago. Puedes usar aquellos que se adecuen a tus
necesidades de negocio.

Si quieres aceptar un solo pago para una sola factura, o procesar un pago que abarca múltiples facturas y efectuar
descuentos por pronto pago, puedes hacerlo con eficacia y precisión.

Creación de facturas
=====================

Los borradores de factura se pueden generar de forma manual, desde otros documentos como pedidos de venta, pedidos de
compra, etc. Aunque puedes crear un borrador de factura directamente si así lo deseas.

Se debe proporcionar al cliente, una factura con la información necesaria para que ellos puedan pagar por los bienes
y servicios solicitados y entregados. También debes incluir otra información necesaria para pagar la factura en tiempo
y forma.

Borrador de factura
======================

Daeris genera facturas que inicialmente se establecen en estado borrador. Mientras estas facturas permanezcan
sin validar, no tienen impacto contable dentro del sistema. No hay nada que impida a los usuarios crear sus propios
borradores de factura.

.. example::
   Creemos una factura de cliente con la siguiente información:

   - **Cliente**: Deco Addict
   - **Producto**: Armario con Puertas
   - **Cantidad**: 1
   - **Precio unitario**: 1000
   - **Impuestos**: impuesto del 21%

   .. image:: cliente/factura01.png
      :align: center
      :alt: Borrador de factura

El documento se compone de tres partes:

   - La parte superior de la factura, con la información del cliente,
   - El cuerpo principal de la factura, con líneas de factura detalladas,
   - La parte inferior de la página, con detalles acerca de los impuestos, y los totales.

Facturas proforma (abiertas)
=============================

Una factura, normalmente incluye la cantidad y el precio de los bienes y/o servicios, la fecha y las partes
involucradas, el número único de factura y la información relacionada con los impuestos.

Confirma la factura mediante el botón **Confirmar** cuando estés listo para publicarla. Esta acción cambia el estado de
la factura de Borrador al estado Publicado.

Cuando Confirmas una factura, Daeris le incorpora un número único de una secuencia definida. Este número no es modificable.

Además,se generarán de forma automática los apuntes contables correspondientes. Un asiento de diario típico generado de una factura autorizada se verá del siguiente modo:

.. list-table:: Asiento de diario
   :widths: 20 20 20 20 20
   :header-rows: 1

   * - Cuenta
     - Cliente
     - Vencimiento
     - Debe
     - Haber
   * - Cuentas por cobrar
     - Decco Adict
     - 10/11/2022
     - 1210,00
     -
   * - Impuestos
     - Decco Adict
     -
     -
     - 210,00
   * - Ventas
     -
     -
     -
     - 1000,00

.. example::
   Continuando con el ejemplo, hemos confirmado una factura en estado borrador.

   .. image:: cliente/factura02.png
      :align: center
      :alt: Facturas proforma

   Los apuntes contables que corresponden a esta factura se generan automáticamente al confirmarla, y se visualizan sobre la pestaña **Otra información**.

   .. image:: cliente/factura03.png
      :align: center
      :alt: Facturas proforma

Enviar la factura al cliente
=============================

Después de confirmar la factura del cliente, puede enviársela directamente mediante el botón **Enviar e imprimir**.

Mediante esta acción, se muestra un formulario el cual permite imprimir factura como PDF, enviar por correo electrónico
o realizar ambas acciones.

Además, en el caso de enviar por correo electrónico, permite seleccionar los destinatarios, editar el asunto y
cuerpo del mensaje, anexar ficheros adjuntos (además de la propia factura) y usar plantillas de correo para agilizar
la redacción del correo.

.. example::
   Continuando con el ejemplo, procedemos a enviar la factura al cliente directamente mediante el botón **Enviar e imprimir**.

   .. image:: cliente/factura04.png
      :align: center
      :alt: Enviar la factura al cliente

Recibir un pago parcial a través de un extracto de cuenta bancario
====================================================================

En Daeris puedes crear extractos de cuenta bancaria de forma manual, o puedes importarlos desde un archivo
(*XLSX o formatos predefinidos de acuerdo a la localización de tu contabilidad*).

.. example::
   Continuando con el ejemplo, desde el tablero de Contabilidad, creamos un extracto de cuenta bancario con el diario relacionado e ingresamos un importe de 100€.

   .. image:: cliente/factura05.png
      :align: center
      :alt: Recibir un pago parcial a través de un extracto de cuenta bancario

Conciliar extracto bancario
=============================
Una vez creadas las líneas de extracto bancario, o importados los extractos correspondientes es posible realizar el
proceso de conciliación, mediante el cual se emparejan los apuntes.

.. example::
   Siguiendo el ejemplo anterior, procedemos a conciliar el apunte creado sobre su factura.

   .. image:: cliente/factura06.png
      :align: center
      :alt: Conciliar extracto bancario

   Como el importe recibido es inferior al importe total, corregimos el saldo y lo validamos.

   .. image:: cliente/factura07.png
      :align: center
      :alt: Conciliar extracto bancario

   Después de haber conciliado los apuntes, la factura queda pagada parcialmente. Bajo la factura aparece el importe ya pagado y el importe pendiente de pago.

   .. image:: cliente/factura08.png
      :align: center
      :alt: Conciliar extracto bancario

Seguimiento de pagos
========================
Puedes realizar el segumiento de tus facturas vencidas pendientes de pago y emitir una comunicación al cliente a modo de recordatorio.

Para iniciar el aistente de recordatorios de facturas vencidas haz clic sobre :menuselection:`Contabilidad / Facturación --> Clientes --> Recordatorios de facturas vencidas`.

.. seealso::
   * :doc:`../../../../finanzas/contabilidad/cuentas_cobrar/pagos_clientes/seguimiento`

También puedes realizar seguimiento de tus facturas, planificando una actividad a realizar el día de vencimiento de la factura.
De esta manera es posible verificar que tus facturas han sido pagadas.

También puedes identificar aquellos clientes que tienen deudas por saldar. Para ello, navega a
:menuselection:`Facturación / Contabilidad --> Contabilidad --> Lista de deudas`. Sobre el listado se muestran todas las facturas
que tienen pagos pendientes.

.. example::
   Siguiendo el ejemplo anterior, se creó una actividad de seguimiento sobre la factura planificada el dia de su vencimiento.

   .. image:: cliente/factura09.png
      :align: center
      :alt: Seguimiento de pagos

   Sobre la lista de deudas, aparece la factura que tiene un importe pendiente por pagar.

   .. image:: cliente/factura10.png
      :align: center
      :alt: Seguimiento de pagos
