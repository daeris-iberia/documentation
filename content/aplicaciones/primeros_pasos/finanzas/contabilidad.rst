:show-content:

=====================
Contabilidad
=====================
..
   .. image:: contabilidad/contabilidad.svg
      :align: center
      :width: 150
      :alt: Contabilidad


La Contabilidad y Facturación de Daeris permite crear facturas, enviárselas a sus clientes, gestionar pagos
además de realizar funciones de contabilidad completas.

Asistente de contabilidad y facturación
==========================================================
Al acceder por primera vez a la aplicación de Contabilidad / Facturación, la página principal muestra un asistente
de configuración el cual te ayuda a configurar las características principales.

El asistente de configuración de la aplicación de contabilidad dispone de cuatro pasos:

   - Períodos contables
   - Plan de cuentas
   - Impuestos
   - Cuentas bancarias

.. seealso::
   * :ref:`finanzas/contabilidad/primeros_pasos/configuracion/inicial/asistente`

Asistente de configuración de facturas
==========================================
Daeris dispone de un asistente sobre :menuselection:`Facturación / Contabilidad --> Clientes --> Facturas`
el cual te ayuda a configurar las características principales de las facturas.

El asistente de configuración de facturas dispone de tres pasos:

   - Información de la compañía
   - Diseño de factura
   - Crear factura

.. seealso::
   * :ref:`finanzas/contabilidad/primeros_pasos/configuracion/inicial/asistente_facturas`

Configuración de términos de pago
==================================
Para configurar los **términos de pago**, navega a la pantalla :menuselection:`Contabilidad / Facturación --> Configuración --> Términos de pago`.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_cobrar/facturas_clientes/terminos/configuracion`

Configuración de redondeo en efectivo
======================================
Para activar el uso de redondeo en efectivo, navega a la pantalla :menuselection:`Contabilidad / Facturación --> Configuración --> Ajustes`
y sobre el apartado **Facturas** de cliente, informa el campo **Redondeo de efectivo** y haz clic sobre el botón **Guadar**.

Posteriormente, haz clic sobre el enlace **Redondeos de fectivo** o navega a la pantalla :menuselection:`Contabilidad / Facturación --> Configuración --> Redondeos de efectivo`.

Sobre el listado de redondeos, haz clic sobre el redondeo a gestionar o sobre el botón **crear**, en el caso de querer definir un nuevo redondeo.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_cobrar/facturas_clientes/redondeo/configuracion`

Configuración código QR Sepa
==============================
Para activar la funcionalidad de añadir un código QR Sepa sobre las facturas, navega a
:menuselection:`Contabilidad / Facturación --> Configuración --> Ajustes` , y sobre el apartado **Pagos de cliente**,
informa la opción **Códigos QR**.

Los códigos QR EPC se añaden automáticamente a tus facturas, siempre y cuando las emitas a cuentas bancarias
cuyo **IBAN** sea de un país que disponga de esta función disponible.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_cobrar/facturas_clientes/codigos_qr/configuracion`

Facturación electrónica (EDI)
==============================
Los formatos de facturación electrónica se habilitan sobre los diarios de facturas. Para ello, navega a
:menuselection:`Contabilidad / Facturación --> Configuración --> Diarios contables`
y sobre el diario **Facturas de clientes**, accede a la pestaña **Configuración avanzada**.

Sobre el apartado **Intercambio de datos electrónico** puedes activar los formatos que deseeshabilitar en el diario.
Ten en cuenta que solo aparecerán los formatos adecuados al país de tu empresa.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_cobrar/facturas_clientes/electronica/configuracion`

Pago de facturas en línea
===========================
De forma predeterminada, "Transferencia bancaria" es el único método de pago activo, pero aún así, debes completar los detalles de pago.

Para activar el Pago en línea de facturas, navega a :menuselection:`Contabilidad / Facturación --> Configuración --> Ajustes`
y sobre el apartado **Pagos de clientes**, informa el campo **Pago de factura en línea** y haz clic sobre el botón **Guardar**.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_cobrar/pagos_clientes/linea/configuracion`

Pagos por lotes: SEPA Direct Debit (SDD)
==========================================
Para activar el pago por SEPA navega a :menuselection:`Contabilidad / Facturación --> Configuración --> Ajustes`
y sobre el apartado **SEPA / PAIN** , informa los campos mostrados.

Posteriormente, navega a :menuselection:`Contabilidad / Facturación --> Configuración --> (Administración) Metodos de pago` y
haz clic sobre el método **Débito directo SEPA para clientes**.

Por último, navega a :menuselection:`Contabilidad / Facturación --> Configuración --> (Administración) Modos de pago` y
haz clic sobre el botón **Crear**.

Selecciona el método de pago **Débito directo SEPA para clientes**, *Si dispones de varios métodos de pago con distintas versiones de PAIN, selecciona el que se adecue a este modo de pago*.
Informa el Identificador del iniciador de la transacción el Emisor de la transacción y el Identificador de acreedor SEPA.
Por último haz clic sobre el botón **Guardar**.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_cobrar/pagos_clientes/sepa/configuracion`

Seguimiento de facturas
==========================
Para configurar los parámetros predeterminados de las acciones de seguimiento, navega a
:menuselection:`Contabilidad / Facturación --> Configuración --> Ajustes`.
Sobre el apartado **Recordatorios de facturas vencidas** informa los campos necesarios.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_cobrar/pagos_clientes/seguimiento/configuracion`

Activar métodos de pago SEPA sobre los diarios bancarios
===========================================================
Para permitir pagos por SEPA, debes activar el método de pago en los diarios bancarios relacionados.

Para ello, navega a :menuselection:`Contabilidad / Facturación --> Tablero`, haz clic sobre el botón **⁝** de la tarjeta de
tu cuenta bancaria y selecciona la opción **Configuración**.

Posteriormente, haz clic sobre la pestaña **Pagos salientes** y agrega una nueva línea, seleccionando como método de
pago **Transferencia de crédito SEPA para proveedores**.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_pagar/pagos_proveedores/sepa/activar_sepa`

Configurar pagar con SEPA
===========================
Si aún no has configurado el modo de pago **Transferencia de crédito SEPA para proveedores**,
navega a :menuselection:`Contabilidad / Facturación --> Configuración --> (Administración) Modos de pago` y
haz clic sobre el botón **Crear**.

Selecciona el método de pago **Transferencia de crédito SEPA para proveedores**, *Si dispones de varios métodos de pago
con distintas versiones de PAIN, selecciona el que se adecue a este modo de pago*.

Informa el Identificador del iniciador de la transacción el Emisor de la transacción y el Identificador de acreedor
SEPA,asi como el diario de tu banco.

.. seealso::
   * :ref:`finanzas/contabilidad/cuentas_pagar/pagos_proveedores/sepa/pagar_sepa`

Añadir una nueva cuenta bancaria
======================================
Para añadir una nueva cuenta Bancaria, navega a
:menuselection:`Facturación / Contabilidad --> Configuración --> Agregar una cuenta bancaria`
y sobre el formulario, informa los campos relacionados con la cuenta.

.. seealso::
   * :ref:`finanzas/contabilidad/banco_efectivo/configuracion/cuentas/anadir_cuenta`

Activar impuestos
==================
Daeris dispone de varios impuestos preconfigurados, pero no todos pueden estar activos de forma predeterminada. En función de tu
modelo de negocio, debes activar los impuestos que vayas a utilizar.

Para **activar los impuestos**, navega a :menuselection:`Contabilidad --> Configuración --> Impuestos`
y mediante el botón **Activar**, habilita o deshabilita el uso del impuesto.

.. seealso::
   * :ref:`finanzas/contabilidad/impuestos/impuestos/impuestos/activar_impuestos`

Impuestos predeterminados
=============================
Para cambiar los Impuestos predeterminados, navega a
:menuselection:`Contabilidad --> Configuración --> Ajustes`, e informa sobre el apartado **Impuestos**
subapartado **Impuestos predeterminados**, los impuestos deseados sobre el campo **Impuesto de venta**
y el campo **Impuesto de compra**, y haz clic sobre el botón **Guardar**.

.. seealso::
   * :ref:`finanzas/contabilidad/impuestos/impuestos/predeterminados/configurar_impuestos`

Incorporar un valor de Incoterm predeterminado
===============================================
Es posible incorporar un valor de incoterm predeterminado sobre las facturas siempre que no se haya realizado el envío.
Para ello, navega a :menuselection:`Facturación / Contabilidad --> Configuración --> Incoterms` y sobre el apartado
**Facturas de cliente***, informa el valor del campo **Incoterm por defecto** y haz clic sobre el botón **Guardar**.

.. seealso::
   * :ref:`finanzas/contabilidad/otros/incoterms/valor_predeterminado`

Moneda principal
===================
Para seleccionar la moneda principal de tu empresa, navega a :menuselection:`Facturación / Contabilidad --> Configuración --> Ajustes`
y sobre el apartado **Monedas** selecciona la moneda principal de tu empresa.

.. seealso::
   * :ref:`finanzas/contabilidad/otros/multidivisa/moneda_principal`

Habilitar monedas extranjeras
==============================
Daeris admite trabajar con múltiples monedas. Estas se crean de forma predeterminada, pero no necesariamente activas.

Para activar las monedas, navega a :menuselection:`Facturación / Contabilidad --> Configuración --> Monedas`.
Sobre el listado de monedas, activa aquellas monedas sobre las que vaya a trabajar tu empresa, haciendo clic sobre el
campo **Activo** de cada registro de moneda a activar.

.. seealso::
   * :ref:`finanzas/contabilidad/otros/multidivisa/habilitar_monedas`

Tipo de cambio
===============
Para incorporar **manualmente** un tipo de cambio, navega a :menuselection:`Facturación / Contabilidad --> Configuración --> Monedas`
y haz clic sobre el registro de la moneda a configurar. Mediante esta acción, accedes al detalle de información de la moneda, desde donde es
posible visualizar el registro histórico de los tipos de cambio que se han producido frente a tu moneda principal.

Desde la pestaña **Tasas**, haz clic sobre **Agregar una línea** para registrar una nueva tasa.

.. seealso::
   * :ref:`finanzas/contabilidad/otros/multidivisa/tipo_cambio`

