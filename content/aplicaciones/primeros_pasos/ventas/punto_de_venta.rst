:show-content:

=====================
Punto de Venta
=====================
..
   .. image:: punto_de_venta/punto_de_venta.svg
      :align: center
      :width: 150
      :alt: Chat

Mediante el **Punto de venta** de Daeris puedes gestionar las ventas de tu negocio de forma sencilla.
Puedes usar la aplicación desde diversos tipos de dispositivos ya que tan solo requiere acceso a un navegador.

Configución de acceso al TPV
=============================

Para configurar la lista de candidatos que pueden usar las sesiones del punto de venta, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV e informa la opción **Empleados Autorizados**. Posteriormente, selecciona todos los
empleados a los que quieras otorgar acceso y pulsa el botón **Guardar**.

.. seealso::
   * :ref:`ventas/punto_de_venta/gestion_basica/configurar_acceso`

Crear categorías y subcategorías
=================================

Una de las tareas iniciales a la hora de configurar los productos que aparecerán en el TPV es la de crear **categorías**
de forma que los empleados se sientan cómodos a la hora de buscarlos.

Para que los TPV muestren los productos categorizados, navega a la pantalla
:menuselection:`Punto de Venta --> Configuración --> Categorías del TPV` ,pulsa el botón *Crear* e informa
los detalles del formulario.

En el caso de que quieras visualizar las imágenes de la categoría en un punto de venta, navega a la pantalla
:menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle del TPV e informa la opción
**Imágenes de la categoría**.

A la hora de iniciar una venta, puedes indicar que cada TPV muestre exclusivamente, una serie de categorías.
Para ello, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
de cada TPV e informa la opción **Restringir categorías de productos**. Posteriormente, selecciona todas las
categorías que necesites mostrar sobre el TPV y pulsa el botón **Guardar**.

A la hora de iniciar una venta, puedes indicar que cada TPV disponga por defecto de una categoría establecida.
Para ello, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle del TPV e informa
la opción **Categoría inicial**, que te permitirá seleccionar una categoría.

.. seealso::
   * :ref:`ventas/punto_de_venta/productos/categorias`

Añadir productos
==================

Para **añadir productos a los TPV**, navega a la pantalla :menuselection:`Punto de Venta --> Productos --> Productos`,
elimina el filtro predefinido *Disponible en TPV* y haz clic sobre el producto a añadir.
Sobre la pestaña **Ventas**, debes informar el campo **Disponible en TPV** y la **Categoría**.

.. seealso::
   * :ref:`ventas/punto_de_venta/productos/anadir`

Añadir código de barras a un producto
=======================================

Para **añadir un código de barras a un producto**, navega a la pantalla :menuselection:`Punto de Venta --> Productos --> Productos`, aparecerán todos los productos
disponibles en el TPV. Posteriormente, haz clic sobre el producto que quieras editar y sobre la pestaña
información general, posiciónate sobre el campo **código de barras** e infórmalo.

.. seealso::
   * :ref:`ventas/punto_de_venta/productos/barras`

.. _ventas/punto_de_venta/control_caja/monedas:

Establecer los tipos de monedas y billetes que permite el TPV
================================================================

Inicialmente, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al
detalle del TPV y sobre el apartado *Pagos* incorpora la opción **Efectivo** como método de pago.

Para gestionar las posibles monedas o billetes que puedes disponer en la caja del TPV, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Monedas / Billetes`.
Esta acción te llevará a la pantalla de valores de moneda de los TPV, donde podrás crear nuevos registros mediante el
botón **Crear** o actualizar los existentes.

Una vez configuradas las agrupaciones de moneda, desde la pantalla de configuración del TPV, deberás seleccionar
aquellas que consideres oportunas sobre el apartado **Monedas / Billetes**.

.. seealso::
   * :ref:`ventas/punto_de_venta/control_caja/monedas`

Configurar el TPV sobre el tablero del inventario
===================================================

Para asociar el TPV con un panel de inventario, navega al detalle del TPV desde la pantalla
:menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, y sobre el apartado de Inventario,
informa el campo **Tipo de operación**.

.. seealso::
   * :ref:`ventas/punto_de_venta/inventario/tablero`

Enviar los productos vendidos por TPV
=========================================

Daeris permite vender tus productos desde el TPV para que sean enviados más tarde. Para ello, debes indicar
el almacén donde residen las existencias que estas vendiendo, así como la política de entrega. Para ello,
navega al detalle del TPV desde la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`
e informa el campo **Enviar más tarde**.

Posteriormente debes informar el **almacén** y la **política de entrega**, siendo posible seleccionar entre enviar
los productos a medida que estén disponibles o enviarlos cuando todos estén disponibles.

.. seealso::
   * :ref:`ventas/punto_de_venta/inventario/envio`

Actualizar stock en tiempo real
================================

Daeris permite gestionar el stock de los productos vendidos a través de los TPV. Para evitar generar operaciones
al sistema que podrían llegar a generar esperas entre venta y venta, por defecto, los movimientos de stock
de los productos vendidos durante la sesión se realizan al cierre de la sesión.

Si necesitas que estos movimientos se produzcan en tiempo real para disponer de una mayor precisión sobre la
cantidad de stock de tus productos, puedes activar esta opción.

Para ello, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Ajustes`, y marca la opción
**En tiempo real** del apartado **Gestión de inventario**. Por último, recuerda hacer clic sobre el botón
**Guardar** para que tus cambios queden registrados.

.. seealso::
   * :ref:`ventas/punto_de_venta/inventario/stock`

Pago de bolsas
===============

Para configurar la operativa, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y marca la opción **Permitir cargos por bolsa** y selecciona la categoría que se corresponda con la categoría
que reúna todos los tipos de bolsa disponibles.

A continuación, navega a la pantalla :menuselection:`Punto de Venta --> Producto --> Productos` y crea el producto bolsa, incorporando la categoría previamente seleccionada.

Recuerda, que si estas restringiendo categorías en tu TPV, deberás añadir la categoría **Bolsa de punto de venta**.

.. seealso::
   * :ref:`ventas/punto_de_venta/pagos/bolsas`

Redondeo de efectivo
=======================

Para activar el redondeo de efectivo , navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Ajustes`
y activa la opción **Redondeo de efectivo**.

Para crear un nuevo método de redondeo, haz clic sobre el enlace **Redondeos de efectivo**.

Posteriormente, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y marca la opción **Redondeo de efectivo**, además del **Método de redondeo**. En el caso de que solo quieras
usar el redondeo cuando el cliente pague en efectivo, incorpora la opción **Solo para métodos de efectivo**.

.. seealso::
   * :ref:`ventas/punto_de_venta/pagos/redondeo`

Restringir el cambio de precios en las líneas de pedido
=========================================================
En el caso de que desees que únicamente los empleados con permisos de **administrador** del punto de venta puedan
modificar los precios de los productos al realizar ventas sobre el TPV, navega a la pantalla
:menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle de un TPV y marca la opción
**control de precios**.

.. seealso::
   * :ref:`ventas/punto_de_venta/pagos/restringir_precios`

Crear facturas
==================

Para **Permitir facturar desde el TPV** navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y sobre el apartado **Facturas y recibos** marca la opción **Facturación**. Posteriormente, incorpora el **diario** contable asociado al TPV.

.. seealso::
   * :ref:`ventas/punto_de_venta/pagos/facturas`

Añadir notas sobre las líneas pedido
=============================================

Daeris permite incorporar notas sobre las líneas del pedido. Estas notas aparecerán en la facturas y el recibo.

Para permitir incorporar notas sobre las líneas del pedido , navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y marca la opción **Notas del cliente**. Recuerda hacer clic sobre el botón **Guardar** para que se apliquen tus cambios.

.. seealso::
   * :ref:`ventas/punto_de_venta/pagos/notas`

Crear tarjeta de crédito como método de pago
=============================================

Para crear un nuevo método de pago, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Métodos de pago`

El sistema navegará a la pantalla de métodos de pago del TPV, donde podrás crear un nuevo método de pago mediante el botón **Crear**.

A continuación, vuelve al detalle del TPV, e informa el nuevo método de pago creado en el campo **Métodos de Pago**:

.. seealso::
   * :ref:`ventas/punto_de_venta/pagos/tarjeta`

Función en modo restaurante/bar
===============================

En el caso de configurar el TPV de un bar/restaurante, navega a la pantalla
:menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y sobre el apartado **Configuración del TPV marca la opción **Es un bar/restaurante**.

.. seealso::
   * :ref:`ventas/punto_de_venta/restaurante/modo_bar`

Configurar las mesas de las salas
==================================

Daeris permite crear mapas de las mesas de las distintas salas para que se puedan gestionar desde el TPV.

Para ello, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y sobre el apartado **Interfaz TPV** marca la opción **Salas y mesas** e incorpora las salas
correspondientes.

.. seealso::
   * :ref:`ventas/punto_de_venta/restaurante/mesas`

Gestionar la impresión de pedidos de barra / cocina
====================================================
Cuando un empleado toma nota de un pedido, puede tener la necesidad de indicar a cocina que debe elaborar
una serie de platos del pedido o a la barra que debe preparar ciertas bebidas.

Estas peticiones se suelen realizar emitiendo una **impresión del pedido** sobre una impresora que deben gestionar los
empleados de cocina.

Para permitir emitir impresiones de pedidos, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y sobre el apartado **Dispositivos conectados** marca la opción **Pedido en impresora**.

.. seealso::
   * :ref:`ventas/punto_de_venta/restaurante/impresion_cocina`

Imprimir una cuenta antes de realizar el pago
==============================================

Para permitir ofrecer a un cliente su cuenta impresa sin tener que mantenerse a la espera de la gestión del pago,
navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y sobre el apartado **Facturas y recibos** marca la opción **Impresión de la cuenta**.

.. seealso::
   * :ref:`ventas/punto_de_venta/restaurante/imprimir_cuenta`

Gestionar las propinas antes de completar un pago
==================================================

Para permitir registrar las propinas ofrecidas por los clientes y descontarlas del cambio a devolver,
navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y sobre el apartado **Pagos** marca la opción **Propinas**.

.. seealso::
   * :ref:`ventas/punto_de_venta/restaurante/propinas`