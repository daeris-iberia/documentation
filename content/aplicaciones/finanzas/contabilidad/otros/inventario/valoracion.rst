===============================================
Configuración de la valoración de inventario
===============================================

La valoración de inventario se refiere a cómo evalúas tus existencias. Es un aspecto muy importante de un negocio,
ya que el inventario puede ser el activo más grande de una empresa.

La valoración de inventario implica dos elecciones principales:

   - El método de coste que utilizas para evaluar tus productos (estándar, FIFO, coste promedio)
   - La forma en la que registras este valor en tus libros contables (de manera manual o automática)

Esos dos conceptos se explican a continuación en las siguientes secciones.


Métodos de coste: Estándar, FIFO, Coste promedio
==================================================

El método de coste se define en la categoría del producto. Hay tres opciones disponibles. Explicaremos cada una de
ellas a continuación.

   - **Precio estándar**: En precio estándar, cualquier producto se evaluará al coste definido manualmente en el formulario del producto. Normalmente, este coste es una estimación basada en el material y la mano de obra necesarias para obtener el producto. Se debe revisar este coste con periodicidad.

   - **Precio promedio**: todos los productos tienen el mismo valor, el cual es el coste promedio de compra del producto. Con este método de coste, el coste del producto se vuelve a calcular en cada recepción. El coste promedio no cambia cuando los productos salen del almacén.

   - **FIFO**: se evalúan los productos con su precio de compra. Cuando un producto sale de las existencias, se aplica la regla *Primera entrada, primera salida*.

   Ten en cuenta que este es un FIFO financiero. El primer valor de *entrada* es el primer valor de *salida*, sin importar
   la ubicación de almacenamiento, el almacén o el número de serie.

   Se recomienda usar FIFO si gestionas tus flujos de trabajo en Daeris (Ventas, Compra, Inventario). Se adapta a cualquier
   tipo de usuario.

Valoración de inventario: manual o automática.
===============================================

Hay dos formas de registrar tu valoración de inventario en tus libros contables. Al igual que el método de coste, esto
se define en la categoría de tu producto. Estos dos métodos se detallan a continuación.

Valoración manual de inventario
================================

En este caso, las recepciones y entregas de productos no tendrán un impacto directo en tus libros contables.
Tú creas de forma periódica un asiento de diario manual que representa el valor de lo que tienes en existencias.
Para conocer este valor, navega a :menuselection:`Inventario --> Informes --> Valoración de inventario`.
Esta es la configuración predeterminada en Daeris y funciona de forma inmediata.

Si al final del mes/año, tu empresa realiza un inventario físico o solo confías en el inventario en Daeris para valorizar
las existencias en los libros contables, crea un asiento de diario para trasladar el valor de la variación de existencias
de tu sección de Pérdidas y ganancias a tus activos.

Verifica las siguientes operaciones y descubre cómo Daeris gestiona las publicaciones contables.

Factura de proveedor
----------------------
**Configuración**:

   - **Bienes adquiridos**: se define en el producto o en la categoría interna del producto relacionado (campo de cuenta de gastos)
   - **Activos por impuestos diferidos**: se define en el impuesto que se usa en la línea del pedido de compra
   - **Cuentas por pagar**: se define en el proveedor relacionado con la factura

Si el valor de las existencias disminuye, la cuenta de **Inventario** va a crédito y las **variaciones de inventario** a débito.

Recepciones de bienes
----------------------

Si el valor de las existencias disminuye, la cuenta de **Inventario** va a crédito y las **variaciones de inventario** a débito.

Factura de cliente
-------------------
**Configuración**:

   - **Ingresos**: se definen en el producto o en la categoría interna del producto relacionado (campo de cuenta de ingresos)
   - **Pasivos por impuesto diferido**: se definen en el impuesto que se utiliza en la línea de la factura
   - **Cuentas por cobrar**: se definen en el cliente (Cuenta de cuentas por cobrar)

La posición fiscal que se utiliza en la factura puede tener una regla que sustituye a la cuenta de ingresos o el
impuesto definido en el producto por otro.

Envío al cliente
------------------

Si el valor de las existencias disminuye, la cuenta de **Inventario** va a crédito y las **variaciones de inventario** a débito.

Órdenes de fabricación
-----------------------

Si el valor de las existencias disminuye, la cuenta de **Inventario** va a crédito y las **variaciones de inventario** a débito.


Valoración automatizada de inventario
=======================================
En ese caso, cuando un producto entra o deja las existencias, se crea un asiento contable de forma automática.
Esto significa que tus libros contables siempre están actualizados. Este modo solo es para contadores expertos y
usuarios avanzados.

A diferencia de la valoración periódica, requiere algo de configuración adicional y pruebas.
Primero, debes definir las cuentas que se utilizarán para esos asientos contables. Esto se hace en la categoría del
producto.

**Configuración**:

   - **Cuentas por cobrar/por pagar**: se definen en el contacto (pestaña de Contabilidad).
   - **Activos/pasivos por impuestos diferidos**: se definen en el impuesto que se utiliza en la línea de la factura.
   - **Ingresos/gastos**: se definen de forma predeterminada en la categoría interna de los productos. También se pueden establecer en el formulario del producto (pestaña de Contabilidad) como un valor específico de reemplazo.
   - **Variaciones de inventario**: para configurar la cuenta de entrada/salida de inventario en la categoría interna del producto
   - **Inventario**: para configurar la cuenta de valoración de inventario en la categoría interna del producto