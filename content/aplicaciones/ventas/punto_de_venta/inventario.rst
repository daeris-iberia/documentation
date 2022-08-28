==============
Inventario
==============

Configurar el TPV sobre el tablero del inventario
------------------------------------------------------------

Para asociar el TPV con un panel de inventario, navega al detalle del TPV desde la pantalla
:menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, y sobre el apartado de Inventario,
informa el campo **Tipo de operación**.

.. image:: inventario/tipo_operacion.png
   :align: center
   :alt: Tipo de operación

Al navegar a la pantalla :menuselection:`Inventario --> Información general`, podrás visualizar un panel de
Pedidos TPV.

.. image:: inventario/inventario.png
   :align: center
   :alt: Pedidos TPV

Desde las opciones del menú del panel de Pedidos TPV, puedes acceder a diferentes consultas sobre los movimientos
de inventario realizados a partir de las ventas realizadas a los clientes.

.. image:: inventario/pedidos_tpv.png
   :align: center
   :alt: Panel TPV

Enviar los productos vendidos por TPV.
------------------------------------------

Daeris permite vender tus productos desde el TPV para que sean enviados más tarde. Para ello, debes indicar
el almacén donde residen las existencias que estas vendiendo, asi como la politica de entrega. Para ello,
navega al detalle del TPV desde la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`
e informa el campo **Enviar más tarde**.

Posteriormente debes informar el **almacén** y la **política de entrega**, siendo posible seleccionar entre enviar
los productos a medida que esten disponibles o enviarlos cuando todos esten disponibles.

.. image:: inventario/mas_tarde.png
   :align: center
   :alt: Enviar los pedidos TPV más tarde

Al cobrar un pedido aparecerá la opción **enviar más tarde**. En el caso de que quieras enviar el pedido a la dirección del cliente,
deberás pulsar la opción **enviar más tarde** y seleccionar el cliente al que realizar el envío.

.. image:: inventario/validar_envio.png
   :align: center
   :alt: Enviar el pedido del tpv.

Una vez el pedido haya sido validado, podrás encontrar el albaran de entrega sobre las expediciones del almacén configurado.
Para ello navega a la pantalla :menuselection:`Inventario --> Información general` y haz clic sobre el registro
**Expediciones**.

.. image:: inventario/expediciones.png
   :align: center
   :alt: Expediciones  del pedido del tpv.

En el caso de que existan existencias del producto vendido, dispondrás de un movimiento en estado **Preparado** a la
espera de que realices el correspondiente envío. En el caso de que no existan existencias, el movimiento estará en
estado **En espera**.

.. image:: inventario/expediciones2.png
   :align: center
   :alt: Expediciones  del pedido del tpv.

Desde el detalle del registro, es posible gestionar el envío.

.. image:: inventario/envio.png
   :align: center
   :alt: Enviar el pedido del tpv.


Actualizar stock en tiempo real
----------------------------------

Daeris permite gestionar el stock de los productos vendidos a través de los TPV. Para evitar generar operaciones
al sistema que podrían llegar a generar esperas entre venta y venta, por defecto, los movimientos de stock
de los productos vendidos durante la sesión se realizan al cierre de la sesión.

Si necesitas que estos movimientos se produzcan en tiempo real para disponer de una mayor precisión sobre la
cantidad de stock de tus productos, puedes activar esta opción.

Para ello, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Ajustes`, y marca la opción
**En tiempo real** del apartado **Gestión de inventario**. Por último, recuerda hacer clic sobre el botón
**Guardar** para que tus cambios queden registrados.

.. image:: inventario/real.png
   :align: center
   :alt: Actualizar stock en tiempo real.

A partir del momento en que inicies una nueva sesión, los movimientos de inventario de tus productos se visualizarán
en tiempo real.

Recordamos que es posible visualizar la infomación sobre el volumen de inventario que hay disponible sobre un
producto en concreto de las siguientes formas:

    - Haciendo clic sobre el botón **(i)** sobre la imagen del producto

    - Posicionándote sobre la línea del pedido y haciendo clic sobre el botón **Información** de la botonera del TPV

.. image:: inventario/real3.png
   :align: center
   :alt: Actualizar stock en tiempo real.

La pantalla de información del producto muestra un apartado relacionado con el inventario.

.. image:: inventario/real2.png
   :align: center
   :alt: Actualizar stock en tiempo real.