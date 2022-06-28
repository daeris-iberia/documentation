============================================================
Cómo adaptar tus precios a tus clientes y aplicar descuentos
============================================================

Daeris tiene una poderosa función de listas de precios para respaldar la estrategia de precios adaptada a tu negocio.
Una lista de precios es un conjunto de reglas que Daeris utiliza para determinar el precio sugerido de los productos.
Puedes establecer varios criterios para utilizar un precio específico: períodos, cantidad mínima de pedido, etc.
Las listas de precios solo sugieren dichos precios, los vendedores pueden sustituirlos al completar los pedidos de venta.

Configuración
=============

Conceder descuentos en líneas de pedido de venta
------------------------------------------------

Es posible aplicar descuentos manuales en las líneas de los pedidos de venta. Para activar esta función, navega a la
pantalla :menuselection:`Ventas --> Configuración --> Ajustes` y marca la opción **Descuentos**:

.. image:: precios/activar-descuentos.png
   :align: center
   :alt: Activar descuentos en pedidos de venta

Una vez marcada la opción, pulsa el botón *Guardar* de la pantalla de ajustes.

Con esta configuración, si el agente crea un presupuesto y selecciona un producto, podrá informar un descuento en el
campo *Desc.%*:

.. image:: precios/descuento-manual-pedido.png
   :align: center
   :alt: Descuento manual en pedidos de venta

Mostrar márgenes en pedidos
---------------------------

Es posible mostrar los márgenes de los productos en los pedidos de venta. El margen se calcula como la suma de los precios
de venta del producto menos el coste establecido en el detalle del producto. Para activar esta función, navega a la
pantalla :menuselection:`Ventas --> Configuración --> Ajustes` y marca la opción **Márgenes**:

.. image:: precios/activar-margenes.png
   :align: center
   :alt: Activar márgenes en pedidos de venta

Una vez marcada la opción, pulsa el botón *Guardar* de la pantalla de ajustes.

Con esta configuración, en los pedidos de venta, se podrá consultar el márgen del pedido debajo del precio total del
pedido:

.. image:: precios/margen-pedido.png
   :align: center
   :alt: Márgen en pedidos de venta

Mostrar el porcentaje de descuento a los clientes
-------------------------------------------------

En caso de descuento, puedes mostrar el precio público y el porcentaje de descuento calculado en los pedidos de venta.
Para hacerlo, navega a la pantalla :menuselection:`Ventas --> Productos --> Tarifas`, y en el detalle de la tarifa,
selecciona la opción **Mostrar al cliente el precio público y el descuento**:

.. image:: precios/mostrar-precio-descuento.png
   :align: center
   :alt: Mostrar al cliente el precio público y el descuento

Múltiples precios por producto
==============================

Para configurar múltiples precios de venta por producto, marca la opción correspondiente desde la pantalla
:menuselection:`Ventas --> Configuración --> Ajustes`:

.. image:: precios/multiples-precios-por-producto.png
   :align: center
   :alt: Múltiples precios por producto

Una vez marcada la opción, pulsa el botón *Guardar* de la pantalla de ajustes.

Con esta opción, es posible configurar varias estrategias de precios.

Precios por segmento de clientes
--------------------------------

Es posible crear listas de precios en base al segmento del cliente. Para ello, navega a la pantalla
:menuselection:`Ventas --> Productos --> Tarifas`, y crea una nueva tarifa mediante el botón *Crear*:

.. image:: precios/crear-tarifa.png
   :align: center
   :alt: Crear nueva tarifa

Especifica un nombre para la nueva tarifa:

.. image:: precios/detalle-tarifa-vip.png
   :align: center
   :alt: Detalle de una tarifa VIP para clientes

Una vez completados los campos necesarios, pulsa el botón *Guardar*.

A continuación, navega al detalle de un producto desde la pantalla :menuselection:`Ventas --> Productos --> Productos`
y pulsa el botón *Precios extras*:

.. image:: precios/precios-extras-producto.png
   :align: center
   :alt: Precios extras de un producto

Incorpora la tarifa y el precio sobre el producto. En este caso, el precio del producto es de 320€ + IVA, pero para los
clientes VIP, el precio será de 240€ + IVA:

.. image:: precios/tarifa-vip-producto.png
   :align: center
   :alt: Tarifa VIP en un producto

Para asociar a un cliente a la nueva lista de precios, navega a la pantalla :menuselection:`Ventas --> Pedidos --> Clientes`,
y accede al detalle de un cliente. Desde la pestaña *Venta y compra*, puedes asociarle la nueva lista de precios en el
campo *Tarifa*:

.. image:: precios/tarifa-vip-cliente.png
   :align: center
   :alt: Tarifa VIP en un cliente

Con esta configuración, si el agente crea un presupuesto para ese cliente, por defecto, se le incorpora la nueva tarifa
y el precio indicado al seleccionar el producto:

.. image:: precios/tarifa-vip-pedido.png
   :align: center
   :alt: Tarifa VIP en un pedido de venta

Precios temporales
------------------

Es posible asociar la lista de precios a los productos fijándoles un periodo predeterminado. Para ello, navega al detalle
de un producto desde la pantalla :menuselection:`Ventas --> Productos --> Productos` y pulsa el botón *Precios extras*:

.. image:: precios/precios-extras-producto.png
   :align: center
   :alt: Precios extras de un producto

Asocia al producto la lista de precios, indicándole el rango de fechas en la que la lista de precios estará vigente. En
este caso, el precio del producto es de 320€ + IVA, pero del 01/06/2022 al 30/06/2022 el precio será de 280€ + IVA:

.. image:: precios/tarifa-temporal-producto.png
   :align: center
   :alt: Tarifa temporal en un producto

Con esta configuración de producto, si el agente se encuentra en un rango de fechas válido, y crea un presupuesto para
ese producto, podrá comprobar que el descuento se aplica correctamente:

.. image:: precios/tarifa-temporal-pedido.png
   :align: center
   :alt: Tarifa temporal en un pedido de venta

Precios por cantidad mínima
---------------------------

También es posible asociar listas de precios a los productos fijándoles una cantidad mínima predeterminada. Para ello,
navega al detalle de un producto desde la pantalla :menuselection:`Ventas --> Productos --> Productos` y pulsa el botón
*Precios extras*:

.. image:: precios/precios-extras-producto.png
   :align: center
   :alt: Precios extras de un producto

Asocia al producto la lista de precios, incorporando la tarifa, cantidad mínima y precio sobre el producto. En este caso,
el precio del producto es de 320€ + IVA, pero si el cliente compra 2 unidades, el precio será de 260€ + IVA:

.. image:: precios/tarifa-cantidad-producto.png
   :align: center
   :alt: Tarifa por cantidad mínima en un producto

Con esta configuración de producto, si el agente crea un presupuesto y selecciona la cantidad mínima del producto, podrá
comprobar que el descuento se aplica correctamente:

.. image:: precios/tarifa-cantidad-pedido.png
   :align: center
   :alt: Tarifa por cantidad mínima en un pedido de venta

Reglas de precio avanzadas
==========================

Las reglas de precio avanzadas permiten establecer reglas de cambio de precios. Los cambios de precio pueden ser relativos
a la lista de productos, al precio de coste del producto o a otra lista de precios. Los cambios de precio se calculan a
través de descuentos o recargos y pueden forzarse para entrar dentro del margen mínimo y margen máximo. Los precios
pueden redondearse al céntimo o euro más cercano, o al múltiplo de cualquiera (los 5 céntimos más cercanos, los 10 euros
más cercanos, etc.).

Para utilizar reglas de precio avanzadas, marca la opción correspondiente desde la pantalla
:menuselection:`Ventas --> Configuración --> Ajustes`:

.. image:: precios/reglas-precio-avanzadas.png
   :align: center
   :alt: Reglas de precio avanzadas

Una vez marcada la opción, pulsa el botón *Guardar* de la pantalla de ajustes.

A partir de ese momento, si navegas al detalle de una tarifa desde la pantalla :menuselection:`Ventas --> Productos --> Tarifas`,
puedes ver el listado de reglas de precio que permite establecer reglas de cambio de precio:

.. image:: precios/reglas-precio-tarifa.png
   :align: center
   :alt: Reglas de precio de la tarifa

Cada elemento de la lista de precios se puede asociar a todos los productos, a una categoría interna del producto
(conjunto de productos) o a un producto específico. Puedes establecer fechas y cantidades mínimas.

.. image:: precios/condiciones-regla-precio.png
   :align: center
   :alt: Condiciones de la regla de precios

.. note::
   Asegúrate de que al menos un artículo de la lista de precios cubra todos tus productos.

Hay 3 modos de cálculo: precio fijo, descuento y fórmula.

.. image:: precios/calculo-regla-precio.png
   :align: center
   :alt: Modo de cálculo de la regla de precios

Descuentos con redondeos
------------------------

Por ejemplo, descuentos del 20% con precios redondeados hasta 9.99.

.. image:: precios/descuentos-con-redondeos.png
   :align: center
   :alt: Descuentos con redondeos

Costes con recargos (venta minorista)
-------------------------------------

Por ejemplo, precio de venta igual a 2 por el coste (100% de margen) con 5€ de margen mínimo.

.. image:: precios/costes-con-recargos.png
   :align: center
   :alt: Costes con recargos

Precios por pais
================

Las listas de precios se pueden establecer por grupo de países. Cualquier cliente nuevo registrado en Daeris obtiene una
lista de precios predeterminada, es decir, la primera en la lista que coincide con el país. En caso de que no se
establezca un país para el cliente, Daeris toma la primera lista de precios sin ningún grupo de países.

.. tip::
   Puedes cambiar la secuencia de listas de precios arrastrando y soltando en la vista de lista.

El grupo de países de una lista de precios se puede configurar desde la pantalla :menuselection:`Ventas --> Productos --> Tarifas`,
accediendo al detalle de la misma:

.. image:: precios/grupo-paises-tarifa.png
   :align: center
   :alt: Grupo de países de una tarifa

.. note::
   Los grupos de países se pueden editar sobre la pantalla :menuselection:`Contactos --> Configuración --> Grupo de países`.

Administrar promociones y programas de cupones
==============================================

Daeris te ayuda a crear cupones y programas promocionales para atraer clientes en el módulo de Ventas. Puedes activar
la función de **Cupones & Promociones** en la pantalla :menuselection:`Ventas --> Configuración --> Ajustes`:

.. image:: precios/activar-cupones-promociones.png
   :align: center
   :alt: Activar cupones y promociones

Una vez marcada la opción, pulsa el botón *Guardar* de la pantalla de ajustes.

Después de habilitar este campo, dispondrás de dos nuevos menús en :menuselection:`Ventas --> Productos`, llamados
**Programa de promociones** y **Programas de cupones**:

.. image:: precios/menu-cupones-promociones.png
   :align: center
   :alt: Menú de cupones y promociones

Programa de promociones
-----------------------

Al navegar a la pantalla :menuselection:`Ventas --> Productos --> Programa de promociones`, obtendrás una vista de las
promociones ya creadas en la plataforma. La vista de tipo listado mostrará el nombre de la promoción y el estado, junto
con el nombre de la compañía:

.. image:: precios/lista-promociones.png
   :align: center
   :alt: Listado de promociones

La vista de tipo Kanban mostrará el nombre de la promoción y el estado, junto con información de los cupones y ventas
relacionadas:

.. image:: precios/kanban-promociones.png
   :align: center
   :alt: Kanban de promociones

Al hacer clic en el botón *Crear*, el sistema navegará al formulario de detalle, donde puedes agregar detalles sobre el
nuevo programa promocional:

.. image:: precios/detalle-promociones.png
   :align: center
   :alt: Formulario de detalle de promociones

El primer paso en la creación de un nuevo programa promocional es agregar el **Nombre del programa** en el campo
correspondiente. Hay varias condiciones disponibles para definir en el formulario. Puedes establecer las condiciones en
función de los clientes y de los productos. Puedes decidir dónde aplicar las reglas seleccionando la opción *Editar dominio*.
En el campo **Cantidad**, puedes mencionar la cantidad mínima de producto para obtener la recompensa. El campo **Compra mínima**
se puede usar para especificar el monto mínimo de compra requerido para obtener la recompensa. Puedes establecer el uso
del código de promoción seleccionando *Aplicación automática* o *Usar un código*.

En el apartado **Validez**, puedes mencionar el sitio web de tu empresa y la validez del programa promocional. En el campo
**Aplicar en el primero**, puedes especificar la cantidad máxima de pedidos de ventas a los que se otorgan recompensas.
También puedes encontrar campos adicionales para agregar la fecha de inicio y la fecha de finalización del programa en
particular.

En el apartado de **Recompensas**, puedes establecer condiciones para las recompensas. Puedes generar la recompensa de dos
formas, *Aplicar en orden actual* y *Envía un cupón*. Daeris ofrece tres tipos de recompensas, descuento, producto gratuito
y envío gratuito.

.. image:: precios/recompensas-promociones.png
   :align: center
   :alt: Recompensas de las promociones

Si has seleccionado la opción *Producto gratis*, aparecerá un campo adicional para agregar los productos gratis como
recompensa. En caso de que hayas elegido la opción *Envío gratis*, el cliente obtendrá una oferta de envío gratis para
los productos seleccionados. Al seleccionar la opción *Descuento*, en el campo **Aplicar descuento en**, debes indicar el
porcentaje del descuento. Puedes aplicar este descuento en pedidos, en el producto más barato o en productos específicos.
Especifica el **Importe descontado máximo** que se puede proporcionar como recompensa en el campo dado.

Después de agregar todos los detalles, puedes guardar la promoción y usarla para el próximo pedido de ventas.

Programas de cupones
--------------------

Al navegar a la pantalla :menuselection:`Ventas --> Productos --> Programas de cupones`, puedes crear atractivos
programas de cupones para que los clientes mejoren las operaciones de venta en Daeris. Esta pantalla contiene todos los
cupones ya creados. Podrás ver el nombre del programa de cupones, el sitio web, el estado activo y el nombre de la
compañía en la vista de tipo listado:

.. image:: precios/lista-cupones.png
   :align: center
   :alt: Listado de cupones

La vista de tipo Kanban mostrará el nombre del cupón y el estado, junto con información de los cupones y ventas
relacionadas:

.. image:: precios/kanban-cupones.png
   :align: center
   :alt: Kanban de cupones

Para crear un nuevo cupón para presupuestos de venta y pedidos, puedes hacer clic en el botón *Crear*:

.. image:: precios/detalle-cupones.png
   :align: center
   :alt: Formulario de detalle de cupones

Especifica el **Nombre del programa** en el campo especificado. Puedes establecer condiciones para el cupón en función del
producto. Puedes establecer las reglas sobre los productos a los que se aplican los cupones en el campo **Según productos**.
Los campos **Cantidad** y **Compra mínima de** se pueden usar para indicar la cantidad mínima y el monto de compra para
obtener la recompensa. Agrega el nombre de tu compañía en el campo indicado. En el apartado **Validez**, puedes agregar el
**Periodo de validez** del cupón junto con los detalles de tu sitio web.

Hay tres tipos de recompensas disponibles para cupones, descuento, producto gratis y envío gratis:

.. image:: precios/recompensas-cupones.png
   :align: center
   :alt: Recompensas de los cupones

Si la recompensa se selecciona como *Descuento*, puedes indicar el porcentaje de descuento proporcionado en un pedido en
particular en el campo **Aplicar descuento**. Puedes aplicar el descuento en pedidos, en el producto más barato o en
productos específicos. El importe de descuento máximo proporcionado en un pedido o presupuesto se puede especificar en
el campo **Importe descontado máximo**. Si has seleccionado *Producto gratis* como recompensa, obtendrás un campo
complementario para seleccionar el producto gratuito. Al seleccionar la opción de *Envío gratis*, el cliente recibirá el
pedido sin pagar gastos de envío.

Después de agregar todos los detalles, puedes guardar el cupón. Para usarlo en el próximo pedido de ventas, deberás
pulsar el botón *Generar cupón*:

.. image:: precios/generar-cupones.png
   :align: center
   :alt: Generar cupones

El sistema desplegará un formulario donde poder informar el número de cupones a generar:

.. image:: precios/formulario-generar-cupones.png
   :align: center
   :alt: Formulario para generar cupones

Al seleccionar la opción *Número de cupones* se podrá especificar el número de cupones a generar. Mediante la opción
*Número de clientes seleccionados* se podrá especificar a qué clientes enviar los cupones, y una plantilla de correo,
para que el sistema envíe de forma automática los cupones a los clientes por correo electrónico.

Añadir promociones y cupones en pedidos de venta
------------------------------------------------

Tras haber configurado programas de promociones y cupones, si el agente crea un presupuesto, podrá añadir las promociones
y cupones creados mediante los botones mostrados a continuación:

.. image:: precios/promociones-cupones-pedidos.png
   :align: center
   :alt: Promociones y cupones en pedidos de venta