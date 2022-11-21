===========================================================
Usar paquetes, unidades de medida o empaquetados especiales
===========================================================

.. _inventario_y_fabricacion/inventario/gestion/productos/paquetes_unidades_empaquetados:

Utilizar diferentes unidades de medida
======================================

Una **unidad de medida** es una cantidad estandarizada de una determinada magnitud física, definida y adoptada por
convención o por ley. Cualquier valor de una cantidad física puede expresarse como un múltiplo de la unidad de medida.

Para configurar productos en diferentes unidades de medida, navega a la pantalla
:menuselection:`Inventario --> Configuración --> Ajustes` y activa la opción de **Unidades de medida**:

.. image:: gestion_basica/activar-unidades-medida.png
   :align: center
   :alt: Activar unidades de medida en Daeris

Una vez activado, pulsa el botón *Guardar* de la pantalla de ajustes.

Las unidades de medida de los productos se agrupan en categorías. De este modo, puedes disponer de una categoría (por
ejemplo, peso) que engloba varias unidades de medida (por ejemplo, gramos, kilos o toneladas).

Para gestionar las categorías de las unidades de medida, navega a la pantalla :menuselection:`Inventario --> Configuración --> Categorías UdM`.
Por defecto, dispones de las siguientes categorías:

-  Unidad

-  Peso

-  Horario de trabajo

-  Longitud/Distancia

-  Superficie

-  Volumen

.. image:: gestion_basica/categorias-unidades-medida.png
   :align: center
   :alt: Categorías de las unidades de medida en Daeris

Para gestionar las unidades de medida, navega al formulario de detalle de una categoría:

.. image:: gestion_basica/detalle-categoria-unidades-medida.png
   :align: center
   :alt: Detalle de una categoría de una unidad de medida en Daeris

Al editar o crear una nueva unidad de medida, puedes encontrar los siguientes campos:

-  **Unidad de medida**: Nombre de la unidad de medida.

-  **Tipo**: Dispones de las siguientes opciones:

   -  **Unidad de medida de referencia para esta categoría**

   -  **Más pequeña que la unidad de medida de referencia**: Si seleccionas este valor, deberás informar la ratio entre esta
      unidad y la de referencia en el campo *Proporción*.

   -  **Más grande que la unidad de medida de referencia**: Si seleccionas este valor, deberás informar la ratio entre esta
      unidad y la de referencia en el campo *Proporción*.

-  **Precisión de redondeo**: Número máximo de decimales hasta realizar el redondeo.

Una vez hayas configurado las unidades de medida de los productos, al editar un producto desde la pantalla
:menuselection:`Inventario --> Productos --> Productos`, podrás seleccionar las unidades de medida del producto
mediante los campos **Unidad de medida** y **UdM de Compra**:

.. image:: gestion_basica/unidad-medida-producto.png
   :align: center
   :alt: Unidad de medida de un producto en Daeris

.. _inventario_y_fabricacion/inventario/gestion/productos/administrar_empaquetados:

Administrar empaquetados de productos
=====================================

El **empaquetado** es el contenedor físico que protege a tu producto. Por ejemplo, si vendes ordenadores, el empaquetado
contiene el ordenador y los cables de energía.

Para activar esta función, navega a la pantalla :menuselection:`Inventario --> Configuración --> Ajustes` y activa
la opción de **Empaquetados del producto**:

.. image:: gestion_basica/activar-empaquetados-producto.png
   :align: center
   :alt: Activar empaquetados del producto

A continuación, pulsa el botón *Guardar* de la pantalla de ajustes.

En Daeris, los empaquetados se utilizan en las transferencias de inventario con propósitos informativos. Se pueden configurar
dichos empaquetados en el formulario de detalle de los productos, desde la vista :menuselection:`Inventario --> Productos --> Productos`,
en la pestaña de *Inventario*:

.. image:: gestion_basica/empaquetados-producto.png
   :align: center
   :alt: Configurar empaquetados del producto

Una vez hecho esto, al crear una transferencia de inventario, será posible informar el empaquetado del producto mediante el
campo **Empaquetado**:

.. image:: gestion_basica/empaquetados-producto-transferencia.png
   :align: center
   :alt: Configurar empaquetados del producto en las transferencias de inventario

.. note::
   Otro uso útil de los empaquetados es para la recepción de productos. Al escanear el código de barras del empaquetado,
   Daeris agrega el número de unidades contenidas en el empaquetado al inventario.

.. _inventario_y_fabricacion/inventario/gestion/productos/administrar_paquetes:

Administrar paquetes de entrega de productos
============================================

El paquete es el contenedor físico en el que pones uno o varios productos de un pedido. Por ejemplo, cuando entregas un
producto, puedes decidir separar la cantidad en dos paquetes diferentes. Esto te permite tener un informe con la cantidad
de productos en cada paquete.

Configuración
-------------

Para habilitar la función de paquetes de entrega, navega a la pantalla :menuselection:`Inventario --> Configuración --> Ajustes`
y marca la opción de **Paquetes**:

.. image:: gestion_basica/paquetes-entrega.png
   :align: center
   :alt: Paquetes de entrega de productos

Una vez hecho esto, pulsa el botón *Guardar* de la pantalla de ajustes.

Crear un tipo de paquete de entrega
-----------------------------------

En función de las características de tus productos, puedes disponer de una serie de paquetes de entrega que dispongan de
ciertos atributos (peso máximo, dimensiones, etc.). Para crear los paquetes de entrega navega a la pantalla
:menuselection:`Inventario --> Configuración --> Tipos de paquete` y pulsa el botón *Crear*:

.. image:: gestion_basica/paquetes-entrega-2.png
   :align: center
   :alt: Paquetes de entrega de productos (2)

El sistema navega al formulario de detalle del paquete de entrega, donde puedes informar los siguientes campos:

-  **Tipo de paquete**: Nombre descriptivo del paquete de entrega.

-  **Tamaño**: Altura, anchura y longitud en milímetros del paquete.

-  **Peso máximo**: Peso máximo que soporta el paquete en kilogramos.

-  **Código de barras**: Código usado para identificar el paquete de entrega.

-  **Compañía**: Empresa asociada al paquete de entrega.

-  **Transportista**: Por defecto, utilizar el valor *Sin integración de transportista*.

-  **Código del transportista**: Código utilizado por el transportista para identificar el paquete.

.. image:: gestion_basica/paquetes-entrega-3.png
   :align: center
   :alt: Paquetes de entrega de productos (3)

Una vez completados los campos necesarios, pulsa el botón *Guardar*.

Empaquetar los productos de un pedido de venta
----------------------------------------------

Para empaquetar los productos de un pedido de venta, será necesario disponer de una entrega (transferencia) en estado
*Preparado*. Para ello, genera y confirma un presupuesto de venta desde la pantalla :menuselection:`Ventas --> Pedidos --> Presupuestos`:

.. image:: gestion_basica/paquetes-entrega-4.png
   :align: center
   :alt: Paquetes de entrega de productos (4)

Al navegar al detalle de la entrega, el estado de la misma debe ser *Preparado*, para lo cuál deberás tener el stock
suficiente de productos para poder realizar la entrega:

.. image:: gestion_basica/paquetes-entrega-5.png
   :align: center
   :alt: Paquetes de entrega de productos (5)

A continuación, edita la transferencia y pulsa sobre el icono para registrar paquetes:

.. image:: gestion_basica/paquetes-entrega-6.png
   :align: center
   :alt: Paquetes de entrega de productos (6)

Al abrirse el formulario de la operación, tienes dos opciones:

#. Si vas a utilizar un nuevo paquete, deja el campo **Paquete destino** en blanco.

#. Si ya has empezado a incorporar productos sobre un paquete y sobra espacio y peso para incorporar más productos,
   informa en el campo **Paquete destino**, el paquete a reutilizar.

Por otro lado, sobre el campo **Hecho**, informa el número de unidades que procedes a incorporar sobre el paquete, y
pulsa el botón *Confirmar*:

.. image:: gestion_basica/paquetes-entrega-7.png
   :align: center
   :alt: Paquetes de entrega de productos (7)

A continuación, pulsa el botón **Poner en paquete**, del formulario de la entrega:

.. image:: gestion_basica/paquetes-entrega-8.png
   :align: center
   :alt: Paquetes de entrega de productos (8)

La acción de poner en paquete incorpora los productos indicados en el paquete correspondiente (puede ser un nuevo paquete
o un paquete existente en función de la información introducida en el campo **Paquete destino**). También se habilita el
botón inteligente **Paquetes** en el detalle de la entrega:

.. image:: gestion_basica/paquetes-entrega-9.png
   :align: center
   :alt: Paquetes de entrega de productos (9)

Al pulsar el botón de paquetes, el sistema navega a la pantalla de paquetes filtrando por todos los paquetes de la
transferencia actual:

.. image:: gestion_basica/paquetes-entrega-10.png
   :align: center
   :alt: Paquetes de entrega de productos (10)

Al acceder al detalle del paquete, puedes informar el tipo de paquete usado y el peso del envío:

.. image:: gestion_basica/paquetes-entrega-11.png
   :align: center
   :alt: Paquetes de entrega de productos (11)

Una vez distribuida la carga de la transferencia en los paquetes, puedes proceder a validarla mediante el botón **Validar**:

.. image:: gestion_basica/paquetes-entrega-12.png
   :align: center
   :alt: Paquetes de entrega de productos (12)

Al validar la transferencia, esta cambiará al estado *Hecho*:

.. image:: gestion_basica/paquetes-entrega-13.png
   :align: center
   :alt: Paquetes de entrega de productos (13)

Gestionar los paquetes de productos
-----------------------------------

Para gestionar los paquetes de productos generados en la aplicación, navega a la pantalla
:menuselection:`Inventario --> Productos --> Paquetes`. En esta pantalla encontrarás todos los paquetes de productos
generados, independientemente de que su transferencia haya sido validada o no:

.. image:: gestion_basica/paquetes-entrega-14.png
   :align: center
   :alt: Paquetes de entrega de productos (14)

Al acceder al detalle de un paquete, aparece un botón llamado **Transferencia de paquete**:

.. image:: gestion_basica/paquetes-entrega-15.png
   :align: center
   :alt: Paquetes de entrega de productos (15)

Este botón permite navegar a la pantalla de transferencias, filtrando por la transferencia asociada al paquete en cuestión:

.. image:: gestion_basica/paquetes-entrega-16.png
   :align: center
   :alt: Paquetes de entrega de productos (16)

Por otro lado, volviendo al detalle del paquete, existe la posibilidad de imprimir el código de barras del paquete con
contenido mediante la opción correspondiente del menú :menuselection:`Imprimir`:

.. image:: gestion_basica/paquetes-entrega-17.png
   :align: center
   :alt: Paquetes de entrega de productos (17)

Esta acción genera un documento en formato PDF con la información del código de barras y del contenido del paquete:

.. image:: gestion_basica/paquetes-entrega-18.png
   :align: center
   :alt: Paquetes de entrega de productos (18)

También existe la opción de imprimir solamente el código de barras del paquete mediante la opción correspondiente del
menú :menuselection:`Imprimir`, tanto en formato PDF como ZPL:

.. image:: gestion_basica/paquetes-entrega-19.png
   :align: center
   :alt: Paquetes de entrega de productos (19)

En el caso del formato PDF, esta acción genera un documento en formato PDF con la información del código de barras del
paquete:

.. image:: gestion_basica/paquetes-entrega-20.png
   :align: center
   :alt: Paquetes de entrega de productos (20)

Mover paquetes completos
------------------------

Para activar esta función, navega a la pantalla :menuselection:`Inventario --> Información general`, y sobre las opciones
del elemento **Expediciones**, accede a la configuración:

.. image:: gestion_basica/paquetes-entrega-23.png
   :align: center
   :alt: Paquetes de entrega de productos (23)

En la pantalla de configuración, marca la opción de **Mover paquetes completos**:

.. image:: gestion_basica/paquetes-entrega-24.png
   :align: center
   :alt: Paquetes de entrega de productos (24)

Una vez marcada esta opción, pulsa el botón *Guardar*.

A partir de aquí, si creas una nueva transferencia desde la pantalla :menuselection:`Inventario --> Operaciones --> Transferencias`,
y seleccionas el tipo de operación *Nombre del almacén: Expediciones*, se habilitará la opción de selección de paquetes
sobre la pantalla de transferencias:

.. image:: gestion_basica/paquetes-entrega-25.png
   :align: center
   :alt: Paquetes de entrega de productos (25)

A continuación, puedes añadir un paquete, y marcarlo como *Hecho*. Por último, valida la transferencia para completar la
transferencia del paquete.