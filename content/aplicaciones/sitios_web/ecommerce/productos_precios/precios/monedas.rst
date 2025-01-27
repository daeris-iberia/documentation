==================================
Cómo vender en monedas extranjeras
==================================

Configuración
=============

Activar una nueva moneda
------------------------

Para activar una nueva moneda, navega a la pantalla :menuselection:`Facturación / Contabilidad --> Configuración --> Monedas`
y haz clic en el botón de activación:

.. image:: monedas/activar-divisa.png
   :align: center
   :alt: Activar una moneda

A partir de ese momento aparecerá en las listas desplegables de monedas.

Seleccionar la moneda principal de la compañía
----------------------------------------------

La moneda principal de la compañía se puede seleccionar desde la pantalla :menuselection:`Facturación / Contabilidad --> Configuración --> Ajustes`:

.. image:: monedas/moneda-principal.png
   :align: center
   :alt: Moneda principal de la compañía

.. note::
   En el desplegable solamente aparecerán las monedas activas.

Conversión automática del precio público
========================================

El precio público de tu empresa se establece en tu moneda principal y se informa en el formulario del producto:

.. image:: monedas/precio-producto.png
   :align: center
   :alt: Precio de un producto

Puedes encontrar los tipos de conversión en :menuselection:`Facturación / Contabilidad --> Configuración --> Monedas`:

.. image:: monedas/tipos-conversion-monedas.png
   :align: center
   :alt: Tipos de conversión de las monedas

Los precios de los productos en divisas diferentes a la moneda principal de la empresa, se actualizan de forma
automática si se cambia el precio público de un producto, en función de la tasa de conversión definida en la pantalla
de administración de monedas.

Establece tus propios precios
=============================

Si prefieres establecer tus propios precios en función de cada una de las monedas activas, navega a la pantalla
:menuselection:`Sitio web --> Productos --> Tarifas` y crea distintas tarifas para cada una de las monedas:

.. image:: monedas/tarifas-monedas.png
   :align: center
   :alt: Monedas asociadas a las tarifas

Al crear una tarifa o editar una tarifa existente, el sistema navega a la pantalla de detalle, donde será posible
incorporar la moneda que aplicará a la tarifa en cuestión:

.. image:: monedas/detalle-tarifas-monedas.png
   :align: center
   :alt: Monedas asociadas a las tarifas en la pantalla de detalle

Una vez hecho esto, navega al detalle de un producto desde la pantalla :menuselection:`Sitio web --> Productos --> Productos`
y pulsa el botón *Precios extras*:

.. image:: monedas/precios-extras-producto.png
   :align: center
   :alt: Precios extras de un producto

Incorpora la tarifa y el precio sobre el producto. En este caso, el precio del producto es de 140€ en la tarifa en EUR,
pero para la tarifa en USD el precio será de $160:

.. image:: monedas/tarifa-moneda-producto.png
   :align: center
   :alt: Tarifa por moneda en un producto

.. _sitios_web/ecommerce/productos_precios/precios/adaptar_precios:

Adaptar precios a los visitantes del sitio web
==============================================

Forzar un precio por geo-localización
-------------------------------------

Para forzar un precio por geo-localización, asigne grupos de países a tu lista de precios desde la pantalla
:menuselection:`Sitio web --> Productos --> Tarifas`:

.. image:: monedas/geo-localizacion.png
   :align: center
   :alt: Forzar un precio por geo-localización

De esta manera, los visitantes que no han iniciado sesión podrán ver su propia divisa al entrar a tu sitio web.

Una vez que el cliente haya iniciado sesión, obtendrá la lista de precios equivalente a su país.

Dejar que el cliente elija la divisa
------------------------------------

En caso de que vendas en varias divisas puedes permitir que tus clientes elijan la que prefieran . Marca la opción *Seleccionable*
en el detalle de una tarifa desde la pantalla :menuselection:`Sitio web --> Productos --> Tarifas`:

.. image:: monedas/elegir-divisa.png
   :align: center
   :alt: Dejar que el cliente elija la divisa

De esta manera, los clientes podrán seleccionar dicha tarifa desde el menú expandible del sitio web:

.. image:: monedas/elegir-divisa-2.png
   :align: center
   :alt: Dejar que el cliente elija la divisa (2)