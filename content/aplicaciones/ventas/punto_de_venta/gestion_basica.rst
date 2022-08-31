==============
Gestión Básica
==============

Introducción
=============

Mediante el **Punto de venta** de Daeris puedes gestionar las ventas de tu negocio de forma sencilla.

Puedes usar la aplicación desde diversos tipos de dispositivos ya que tan solo requiere acceso a un navegador.

Es necesaria la conexión a internet al iniciar sesión, pero una vez iniciada puedes seguir trabajando si
pierdes la conectividad.


Introducción al TPV de daeris
----------------------------------

El **terminal de punto de venta** de Daeris, es una aplicación intuitiva y de fácil manejo que permite realizar las
gestiones de ventas con comodidad al estar integrado con las aplicaciones de contabilidad, inventario, ventas y CRM, permitiendo
disponer de datos estadísticos de todas las ventas en tiempo real.

Es necesaria **conexión online al iniciar y finalizar la sesión** de cada TPV y se puede ejecutar sobre maquinas
industriales, ordenadores personales, ordenadores portátiles y dispositivos iOS/Android (móviles y tabletas).

Cuando un empleado inicia sesión en el TPV, se encuentra con una aplicación divida en secciones que le permitirá
realizar diversas acciones en función de cómo se haya configurado previamente.

Las secciones principales de las que se compone la pantalla principal del TPV son:

    - **1 - Sesión**: Permite crear/eliminar pedidos ,identificar al empleado y cerrar sesión
    - **2 - Lista de Pedido**: Incorpora un listado con todos los productos añadidos al pedido.
    - **3 - Categoría y subcategoría**: Muestra la categoría y subcategoría sobre la que estás posicionado.
    - **4 - Imágenes de categoría**: Muestra las imágenes de las categorías.
    - **5 - Panel de acción**: Permite realizar múltiples acciones mediante el panel de botones.
    - **6 - Selección de productos**: Muestra todos los productos de la categoría.

.. image:: gestion_basica/pos_partes.png
   :align: center
   :alt: Secciones principales de las que se compone la pantalla principal del TPV

Sesiones
=============

Configución de acceso al TPV
------------------------------

Es posible configurar la lista de posibles candidatos que pueden usar las sesiones del punto de venta.
Para ello, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV e informa la opción **Empleados Autorizados**. Posteriormente, selecciona todos los
empleados a los que quieras otorgar acceso y pulsa el botón **Guardar**.

.. image:: gestion_basica/conf_empleados.png
   :align: center
   :alt: Informa la opción Empleados Autorizados y selecciona todos las empleados a los que quieras otorgar acceso

En el caso de que desees añadir una clave PIN a un empleado, navega a la pantalla :menuselection:`Empleados --> Empleados`,
y haz clic sobre el empleado deseado. Sobre el formulario de detalle, posiciónate sobre la pestaña **Configuración RRHH**.
Añade sobre el campo **Código PIN**, el PIN deseado.

.. image:: gestion_basica/rrhh1.png
   :align: center
   :alt: Informa el PIN deseado

En el caso de querer incorporar una credencial que pueda ser escaneada por el empleado en sustitución de la introducción
del código PIN, informa el campo **ID de credencial** y haz clic sobre el botón **Generar**.

.. image:: gestion_basica/rrhh2.png
   :align: center
   :alt: ID de credencial

Para imprimir la insignia, haz clic sobre el botón **Imprimir Insignia**.

.. image:: gestion_basica/rrhh3.png
   :align: center
   :alt: ID de credencial

La insignia se abrirá en una nueva pestaña desde donde podrá ser impresa.

.. image:: gestion_basica/rrhh4.png
   :align: center
   :alt: ID de credencial

Iniciar o reanudar una sesión
------------------------------

Para iniciar una sesión sobre el TPV, navega a la pantalla :menuselection:`Punto de Venta --> Tablero`, donde
encontrarás todos los puntos de venta disponibles. Haz clic sobre el botón **Nueva sesión o Seguir vendiendo** del TPV al
que quieras acceder.

.. image:: gestion_basica/pos_tablero.png
   :align: center
   :alt: Para iniciar una sesión sobre el TPV, navega a la pantalla : Punto de Venta / Tablero

Sobre la pantalla aparecerá un indicador de carga de la aplicación TPV.

.. image:: gestion_basica/pos_carga.png
   :align: center
   :alt: Indicador de carga de la aplicación TPV

Al finalizar la carga (suele tardar unos segundos), aparecerá la pantalla inicial del TPV .

En el caso de que dispongas de más de un empleado operando con el TPV, se mostrará una pantalla inicial de inicio de sesión.
Desde esta pantalla es posible escanear la credencial del empleado que va a iniciar sesión o seleccionarlo manualmente mediante
el botón **Seleccionar cajero**.

.. image:: gestion_basica/pos_sesion.png
   :align: center
   :alt: escanear la credencial del empleado que va a inciar sesión o seleccionarlo manualmente mediante el botón Seleccionar cajero

Si seleccionamos la opción **Seleccionar cajero**, se mostrará una pantalla desde donde seleccionar el cajero que va a usar el TPV.

.. image:: gestion_basica/pos_cajero.png
   :align: center
   :alt: Pantalla desde donde seleccionar el cajero que va a usar el TPV.

Si el usuario seleccionado dispone de **PIN de autentificación**, deberá incorporarlo para poder iniciar a sesión.

.. image:: gestion_basica/pos_cajero2.png
   :align: center
   :alt: Incorporar el PIN para poder iniciar a sesión.

En el caso de iniciar una nueva sesión, se mostrará el formulario inicial de control de efectivo.
En el caso de haber reanudado la sesión, el empleado dispondrá del pedido tal y como lo dejó al haber finalizado
la sesión anterior.

.. image:: gestion_basica/pos_init.png
   :align: center
   :alt: Pantalla inicial del TPV

Cambiar de empleado sobre una sesión
-------------------------------------
Cambiar el empleado que usa un TPV suele ser una tarea frecuente que requiere de agilidad para no dejar al cliente
en espera. Para cambiar de empleado sobre una sesión de TPV, pulsa sobre el nombre del empleado de la sesión actual.

.. image:: gestion_basica/pos_empleado.png
   :align: center
   :alt: Cambiar el empleado que usa un TPV

Esta acción abrirá una nueva ventana, donde podrás escoger entre una lista de posibles candidatos.

.. image:: gestion_basica/pos_seleccion.png
   :align: center
   :alt: Nueva ventana, donde podrás escoger entre una lista de posibles candidatos

Si el usuario seleccionado dispone de **PIN de autentificación**, deberá incorporarlo para poder acceder a la sesión.

.. image:: gestion_basica/pos_aut.png
   :align: center
   :alt: Si el usuario seleccionado dispone de PIN de autentificación, deberá incorporarlo para poder acceder a la sesión.

Al cambiar de empleado, se cambiará el nombre en la parte superior de la sesión de TPV. La sesión continuará donde
lo había dejado el empleado anterior.

.. image:: gestion_basica/pos_empleado2.png
   :align: center
   :alt: Al cambiar de empleado, se cambiará el nombre en la parte superior de la sesión de TPV

Salir de una sesión
----------------------------

Para cerrar una sesión de TPV, debes pulsar el botón **Cerrar**.

.. image:: gestion_basica/pos_cerrar.png
   :align: center
   :alt: Para cerrar una sesión de TPV, debes pulsar el botón Cerrar.


A continuación, se mostrará la pantalla de control de cierre, desde donde es posible indicar el importe disponible
al contado en la caja registradora (control de caja), así como incorporar notas de los sucesos de la sesión.

Además, es posible realizar las siguientes acciones:

    - **Continuar venta**: Permite salir de la pantalla de control de cierre y continuar operando en la sesión.
    - **Mantener abierta**: Permite salir del TPV sin cerrar la sesión, para continuarla posteriormente.
    - **Cerrar sesión**: Permite salir del TPV cerrando la sesión actual.

.. image:: gestion_basica/pos_control_cierre.png
   :align: center
   :alt: Pantalla de control de caja al cierre del TPV

Al salir de la sesión, Daeris navegará a la pantalla :menuselection:`Punto de Venta --> Tablero`, donde podrás ver
la *Última fecha de cierre* y el *Último saldo de efectivo de cierre*.

.. image:: gestion_basica/pos_post_cierre.png
   :align: center
   :alt: Pantalla de control de caja al cierre del TPV

En el caso de que hayas mantenido abierta la sesión y quieras continuarla, deberás hacer clic sobre el botón **Seguir vendiendo**.

.. image:: gestion_basica/pos_post_cierre2.png
   :align: center
   :alt: Pantalla de control de caja al cierre del TPV

Pedidos
=============

Añadir artículos a un pedido de forma manual
---------------------------------------------

Para **añadir artículos** a un nuevo pedido del TPV, puedes buscar sobre las categorías cada uno de los artículos
que quieras incorporar. En caso de disponer de muchos productos o categorías, puedes utilizar el buscador para
encontrar el artículo.

.. image:: gestion_basica/buscador.png
   :align: center
   :alt: Puedes utilizar el buscador para encontrar el artículo

Al hacer **clic sobre el artículo**, aparecerá sobre el pedido incorporando el precio y el número de unidades.

.. image:: gestion_basica/clic_articulo.png
   :align: center
   :alt: Al hacer clic sobre el artículo, aparecerá sobre el pedido incorporando el precio y el número de unidades.

En el caso de que quieras ampliar el número de unidades, puedes:

    - Hacer **clic sobre el artículo** tantas veces como unidades quieras incorporar.
    - Hacer **clic sobre el teclado numérico**, indicando el número de unidades (es necesario que esté seleccionada la opción **Cantidad** del teclado numérico).

.. image:: gestion_basica/clic_articulo2.png
   :align: center
   :alt: Hacer clic sobre el teclado numérico, indicando el número de unidades , necesario que esté seleccionada la opción Cantidad del teclado numérico.

Una vez añadido un producto, puedes eliminar el término buscado, mediante el botón derecho del buscador. Posteriormente
puedes continuar añadiendo productos al pedido, seleccionando otras categorías y haciendo clic sobre los productos a incorporar.

.. image:: gestion_basica/resultado_articulo.png
   :align: center
   :alt: puedes continuar añadiendo productos al pedido.


Añadir artículos a un pedido mediante la lectura del código de barras
------------------------------------------------------------------------

Para añadir artículos a un pedido del TPV mediante la lectura del código de barras del producto, debes posicionarte
sobre la pantalla de pedidos del TPV.

.. image:: gestion_basica/tpv_buscar.png
   :align: center
   :alt: Buscar productos en el TPV

Al escanear el código de barras del producto con el lector de código de barras, el sistema localizará el producto
correspondiente y lo añadirá al pedido.

.. image:: gestion_basica/tpv_buscar2.png
   :align: center
   :alt: Producto añadido al pedido del TPV

En el caso de que quieras ampliar el número de unidades, puedes:

    - Volver a **escanear el código de barras** del producto, tantas veces como unidades quieras añadir.
    - Hacer **clic sobre el artículo** tantas veces como unidades quieras incorporar.
    - Hacer **clic sobre el teclado numérico**, indicando el número de unidades (es necesario que esté seleccionada la opción Cantidad del teclado numérico).

.. image:: gestion_basica/tpv_unidades.png
   :align: center
   :alt: Unidades del artículo añadido al pedido del TPV

Una vez añadido un producto, puedes continuar añadiendo productos al pedido, escaneando los códigos de barras de los
productos correspondientes.


Gestionar múltiples pedidos 
----------------------------
Una de las situaciones que generan malestar a los clientes se produce cuando un cliente bloquea una cola de ventas.
Esta situación se puede producir por varias razones como:

    - Le falta un producto por adquirir para completar su venta.
    - Quiere realizar un cambio de producto.
    - Ha descuidado su forma de pago y necesita ausentarse unos instantes para disponer de ella.
    - Necesita realizar una consulta externa para garantizar el pedido y no generar una devolución.

A esta lista le podríamos sumar un largo etcétera que a ojos del resto de clientes generan malestar.

Para evitar en la medida de lo posible estas situaciones y evitar que el empleado tenga que deshacer todo el pedido
ya gestionado, Daeris permite **gestionar múltiples pedidos de forma simultánea**. De este modo, si un empleado se
encuentra con una situación como las indicadas, puede mantener a la espera el pedido del cliente bloqueado y
continuar gestionando pedidos del resto de la cola de ventas.

Para crear **nuevos pedidos en una sesión de TPV**, tan solo es necesario hacer clic sobre el botón **Pedidos** de la sección
superior. Este botón incorpora el número total de pedidos abiertos que hay en la sesión.

.. image:: gestion_basica/tpv_anadir_pedido.png
   :align: center
   :alt: Añadir pedido al TPV

Al hacer clic sobre el botón **Pedidos**, aparece una nueva pantalla desde donde es posible buscar pedidos anteriores ,
asi como crear nuevos. Para ello, pulsa el botón **Nuevo pedido**.

.. image:: gestion_basica/tpv_nuevo_pedido.png
   :align: center
   :alt: Nuevo pedido en el TPV

Esta acción abrirá un nuevo pedido y añadirá un pedido al contador de pedidos activos. El empleado podrá
gestionar este nuevo pedido de la forma habitual.

.. image:: gestion_basica/tpv_nuevo_pedido2.png
   :align: center
   :alt: Nuevo pedido en el TPV

Para volver al pedido anterior tan solo deberá hacer clic sobre el botón **pedidos** y volver a hacer clic sobre el pedido del listado.

.. image:: gestion_basica/tpv_volver_pedido.png
   :align: center
   :alt: Volver al pedido anterior

Eliminar un pedido incompleto
-------------------------------

Una de las situaciones que puede llegar a ocurrir mientras se está gestionando un pedido, es que el cliente decida
no completarlo. Esta situación puede darse por múltiples razones, como, por ejemplo, que haya cambiado de opinión,
que no disponga de medios de pago o efectivo suficiente, etc.

Para que un empleado pueda **deshacer el pedido** de forma completa, deberá hacer clic sobre el botón **Pedidos** de la
sección superior.

.. image:: gestion_basica/tpv_eliminar_pedido.png
   :align: center
   :alt: Eliminar el pedido

Posteriormente, deberá hacer clic sobre el botón **Eliminar** (icono de papelera de reciclaje) del listado de pedidos.

.. image:: gestion_basica/tpv_eliminar_pedido2.png
   :align: center
   :alt: Eliminar el pedido

El sistema solicitará **confirmación** para la eliminación del pedido:

.. image:: gestion_basica/tpv_eliminar_confirmar.png
   :align: center
   :alt: Confirmar eliminar el pedido

Una vez confirmada la eliminación, el sistema posicionará al empleado sobre el pedido anterior (en caso de disponer
de más de un pedido en proceso) o creará uno nuevo (en caso de no disponer de pedidos anteriores en proceso).

.. image:: gestion_basica/tpv_eliminar_nuevo.png
   :align: center
   :alt: Nuevo pedido del TPV

Identificar o crear clientes
-------------------------------
Disponer de la mayor información posible de los clientes te permite hacer crecer tu negocio por múltiples vías,
así como poder ofrecer servicios especializados mejorando la fidelidad (descuentos, campañas especiales,
envío de catálogos, etc.).

Tener a tus clientes registrados te permitirá, además, agilizar los procesos de facturación, así como ofrecerles
información detallada de su historial. Para agilizar el registro de clientes, Daeris permite al empleado crear
nuevos clientes desde el TPV.

Para crear un nuevo cliente desde una sesión de TPV, pulsa el botón Cliente del teclado numérico:

.. image:: gestion_basica/tpv_cliente.png
   :align: center
   :alt: Cliente del TPV

Esta acción abrirá una nueva pantalla donde aparece un listado con todos los clientes disponibles, un buscador útil
en el caso de que quieras realizar la búsqueda de un cliente en concreto y un botón que permitirá registrar los
datos de un nuevo cliente.

.. image:: gestion_basica/tpv_anadir_cliente.png
   :align: center
   :alt: Añadir cliente

Al hacer clic sobre el botón **+Crear**, se abre un nuevo formulario donde introducir los datos del cliente. El empleado
puede registrar los datos que le ofrece el cliente.

Campos como el NIF, pueden disponer de validaciones para evitar la introducción de datos erróneos. Una vez
introducidos los datos, pulsa el icono de **Guardar**.

.. image:: gestion_basica/tpv_guardar_cliente.png
   :align: center
   :alt: Guardar cliente

Al guardar el formulario, puedes indicar al TPV que se realizará la venta a este cliente, haciendo clic sobre el
botón **Establecer cliente**.

.. image:: gestion_basica/tpv_establecer_cliente.png
   :align: center
   :alt: Establecer cliente

Esta acción te devolverá a la pantalla de venta principal. Sobre el botón **cliente** aparecerá el nombre del cliente
recién creado, y sobre el que puedes proceder a realizar la venta.

.. image:: gestion_basica/tpv_cliente_on.png
   :align: center
   :alt: Cliente del TPV

Al proceder a registrar el pago, el cliente aparecerá identificado sobre la pantalla de pago.

.. image:: gestion_basica/tpv_cliente_pago.png
   :align: center
   :alt: Cliente del TPV

Una vez validado el pago, aparecerán los datos del cliente en el correspondiente ticket de compra y permitirá enviarle
el recibo por correo electrónico.

.. image:: gestion_basica/tpv_cliente_compra.png
   :align: center
   :alt: Cliente sobre el ticket de compra

Si accedes al detalle del cliente creado desde la pantalla :menuselection:`Contactos --> Contactos`, podrás
visualizar todas las compras realizadas desde el TPV a este cliente haciendo clic sobre el botón **Pedidos TPV**.

.. image:: gestion_basica/tpv_cliente_ventas.png
   :align: center
   :alt: Ventas TPV

El sistema mostrará un listado de las ventas realizadas a ese cliente mediante la TPV.

.. image:: gestion_basica/tpv_cliente_ventas2.png
   :align: center
   :alt: Listado de Ventas TPV


Importar presupuestos / pedidos sobre el TPV
---------------------------------------------

En función de los circuitos de venta establecidos en tu negocio, es posible que envíes presupuestos a tus clientes
o generes pedidos de venta pendientes de pago.

Desde cualquier TPV, es posible la importación de los presupuestos o pedidos con el objetivo de que el cliente
pueda realizar un pago inicial o completar el pago.

En el caso de que los productos asociados al pedido no estén incorporados al TPV, la aplicación solicitará la
importación para poder proceder con su venta.

Además, se incorporará el cliente asociado al pedido sobre el TPV y se permitirá emitir la factura correspondiente.

Para importar un presupuesto o pedido sobre el TPV debes hacer clic sobre el botón **Presupuesto / Pedido**

.. image:: gestion_basica/importar1.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

Esta acción muestra un listado sobre una ventana con todos los presupuestos / pedidos no finalizados. El listado
dispone de información relevante como el número de presupuesto/pedido, fecha, cliente, comercial, importe y estado.
Además, es posible realizar búsquedas con el buscador de la barra superior.

.. image:: gestion_basica/importar2.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

Al seleccionar un pedido, la aplicación solicita al empleado la acción que se procede a realizar, siendo posible
escoger una de las siguientes opciones:

   -  **Aplicar un pago inicial**: Solicitará el porcentaje a aplicar sobre el precio total del pedido.
   -  **Liquidar el pedido**: Aplicará el precio total del pedido.

.. image:: gestion_basica/importar3.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

En el caso de que algunos de los productos asociados al pedido no estén asociados al TPV, la aplicación solicitará
realizar su carga, acción que debe confirmarse.

.. image:: gestion_basica/importar4.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

Una vez seleccionada la opción, se incorporarán las líneas del pedido como línea del pedido del TPV, además del cliente
asociado.

.. image:: gestion_basica/importar5.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

Una vez completado el pedido se debe proceder al pago, mediante el botón **pagos**. Esta acción navega a la pantalla
de pago del pedido desde dónde es necesario seleccionar el método de pago.

.. image:: gestion_basica/importar6.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

Posteriormente es necesario hacer clic sobre el botón **Facturas del cliente**, en el caso de que quieras imprimir
la factura tras **validar** el pago.

.. image:: gestion_basica/importar7.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

Al **validar** el pago aparece la factura, para realizar su impresión.

.. image:: gestion_basica/importar8.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

Al validar el pago aparece la pantalla de gestión del recibo, desde dónde es posible enviar el recibo y la factura por
correo electrónico.

.. image:: gestion_basica/importar9.png
   :align: center
   :alt: Importar presupuestos / pedidos sobre el TPV

Limitar la carga de clientes y/o productos
--------------------------------------------

Al iniciar una sesión del TPV, se cargan de forma predeterminada todos los **productos** y **clientes**.
En función de tu negocio, es posible que dispongas de un volumen de productos o clientes muy elevado.
Esta situación puede provocar **lentitud a la hora de iniciar la sesión**.

Para corregir esta situación, Daeris permite establecer la carga de un número máximo de registros e incluso permite
la opción de cargar el resto de forma invisible una vez se ha iniciado la sesión.

Para limitar la carga de clientes al iniciar la sesión del TPV, navega a la pantalla
:menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y sobre el apartado **Interfaz TPV**, informa la opción **Carga de clientes limitada**.

Al activar esta opción, se cargarán **los primeros 100 clientes** al iniciar la sesión.

En el caso de que desees que se carguen el resto de clientes una vez iniciada la sesión, selecciona la opción
**Cargar todos los clientes restantes en segundo plano**.

Posteriormente, pulsa el botón **Guardar**.

.. image:: gestion_basica/carga1.png
   :align: center
   :alt: Carga de clientes limitada

En el caso de que no incorpores la opción de **Cargar todos los clientes restantes en segundo plano**,
puedes igualmente llegar a cargar un cliente cuando lo necesites.

Sobre el TPV, a la hora de buscar el cliente, debes hacer clic sobre el botón cliente.
Sobre el buscador, introduce parte del nombre del cliente y haz clic posteriormente sobre el botón
**Cargar Clientes**. En el caso de que existan clientes que coincidan con la búsqueda, estos serán cargados
sobre el TPV y aparecerán en el listado.

.. image:: gestion_basica/carga1b.png
   :align: center
   :alt: Carga de clientes limitada

Para limitar la carga de productos al iniciar la sesión del TPV, navega a la pantalla
:menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al detalle
del TPV y sobre el apartado **Inventario**, informa la opción **Carga de productos limitada**.

Al activar esta opción, se cargarán **los 20.000 productos más comunes** al iniciar la sesión.

En el caso de que desees que se carguen el resto de productos una vez iniciada la sesión, selecciona la opción
**Cargar todos los productos restantes en segundo plano**.

Posteriormente, pulsa el botón **Guardar**.

.. image:: gestion_basica/carga2.png
   :align: center
   :alt: Carga de productos limitada

En el caso de que no incorpores la opción de **Cargar todos los productos restantes en segundo plano**,
puedes igualmente llegar a cargar un producto cuando lo necesites.

Desde el TPV, debes introducir sobre el buscador, el nombre del producto
y hacer clic sobre el icono **Base de datos** que se encuentra junto al icono de la lupa.
En el caso de que existan productos que coincidan con la búsqueda, estos serán cargados
sobre el TPV y aparecerán en el listado.

.. image:: gestion_basica/carga2b.png
   :align: center
   :alt: Carga de productos limitada