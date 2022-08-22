===============
Control de Caja
===============

Configuración
==============

Apertura del TPV 
------------------

Para que un empleado pueda abrir una sesión de TPV debe realizar previamente el **control de apertura**.

Esta tarea se basa en contabilizar el efectivo de que dispone la caja registradora. Para ello, navega a la pantalla
:menuselection:`Punto de Venta --> Tablero`, y sobre una sesión de TPV no iniciada, pulsa el botón **Nueva sesión**.

.. image:: control_caja/sesion.png
   :align: center
   :alt: Nueva sesión de TPV

Al iniciar una nueva sesión, se solicita la identificación del empleado (en el caso de que el TPV este configurado para ello).
Posteriormente, se muestra una pantalla donde se indica el saldo de apertura de la caja. Además, se
puede gestionar el número de monedas y billetes mediante el icono de la **calculadora**.

.. image:: control_caja/apertura_control.png
   :align: center
   :alt: Balance de apertura

Al hacer clic sobre la calculadora, se debe incorporar el número de monedas y billetes disponible en la caja
registradora.

.. image:: control_caja/saldo_ini.png
   :align: center
   :alt: Control de efectivo

Una vez revisado el listado de monedas y billetes, y realizados los ajustes necesarios, pulsa el botón Confirmar.
El saldo de apertura de actualizará con el efectivo introducido.

.. image:: control_caja/saldo_fin.png
   :align: center
   :alt: Saldo de apertura

A continuación, para abrir la sesión, pulsa el botón **Abrir sesión**.

.. image:: control_caja/abrir_sesion.png
   :align: center
   :alt: Abrir sesión

Al abrir la sesión, se mostrará la pantalla inicial del TPV.

.. image:: control_caja/tpv_ini.png
   :align: center
   :alt: Inicio del TPV

Cierre del TPV
----------------

Para realizar el **control de caja** sobre un TPV, pulsa el botón **Cerrar** de la barra superior derecha.

.. image:: control_caja/cerrar.png
   :align: center
   :alt: Cerrar TPV

El sistema muestra la pantalla de control de cierre de la sesión del TPV, donde es posible indicar el número de monedas
disponibles en la caja registradora, haciendo clic sobre el botón **calculadora**.

.. image:: control_caja/control_cierre.png
   :align: center
   :alt: Control de cierre

En este punto, el empleado deberá contabilizar el número de monedas y billetes disponible en la caja registradora.
Posteriormente deberá confirmar la operación haciendo clic sobre el botón **confirmar**.

.. image:: control_caja/control_cierre_monedas.png
   :align: center
   :alt: Control de cierre

En el caso de existir diferencias entre lo contabilizado por el sistema y lo contabilizado en caja, aparecerán sobre
el apartado diferencia. En el caso de que el empleado desee registrar la diferencia deberá seleccionar la opción
**Acepta la diferencia...** y cerrar la sesión mediante el botón **Cerrar sesión**.

.. image:: control_caja/control_cierre2.png
   :align: center
   :alt: Control de cierre


El TPV quedará disponible para iniciar una nueva sesión desde la pantalla :menuselection:`Punto de Venta --> Tablero`,
desde donde es posible consultar el detalle de todas las sesiones haciendo clic sobre el botón **Sesiones**.

.. image:: control_caja/sesion2.png
   :align: center
   :alt: Sesiones del TPV

Sobre la pantalla de sesiones del TPV, es posible identificar todas las sesiones realizadas.

.. image:: control_caja/sesiones_lista.png
   :align: center
   :alt: Sesiones del TPV

Al hacer clic sobre un registro del listado, accedemos a su detalle desde donde es posible consultar toda la información
relevante de la sesión asi como sus registros relacionados haciendo clic sobre los botones de acceso a Pedidos,
albaranes, pagos, apuntes contables y registros de caja.

.. image:: control_caja/sesion_detalle.png
   :align: center
   :alt: Sesiones del TPV

Opciones adicionales
=====================

Establecer la diferencia máxima sobre el control de caja
-----------------------------------------------------------

En ocaciones, debido a un error a la hora de devolver el cambio a un cliente, se producen descuadres de caja.
Daeris, permite establecer una diferencia máxima a la hora de realizar el control de caja, sin pasar por la autorización
de un responsable.

.. note::
   Esta opción solo es válida si **no se usa** la opción **Empleados autorizados** debido a que con esta opción, solo pueden cerrar sesión del TPV y hacer control de caja , los usuarios con permisos de **Administrador** del punto de venta.

.. seealso::
   * :doc:`../../varios/usuarios_companias/usuarios`

Para ello, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al
detalle del TPV y sobre el apartado *Pagos* incorpora la opción **Establecer la diferencia máxima** y añade la
diferencia máxima autorizada.

.. image:: control_caja/diferencia.png
   :align: center
   :alt: Establecer la diferencia máxima

Cuando un empleado intenta realizar un control de cierre superando la diferencia máxima, se muestra un mensaje por
pantalla, indicando que ha de contactar con un responsable para **Aceptar** la diferencia máxima permitida.

.. image:: control_caja/diferencia2.png
   :align: center
   :alt: Aviso por diferencia máxima

El empleado responsable con permisos de administrador del TPV , deberá realizar el control de cierre para poder cerrar la sesión, ya que a este, no le aplicará
dicha restricción.


Establecer el volumen de monedas y billetes en la apertura del TPV
-------------------------------------------------------------------

En primer lugar, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Punto de Venta`, accede al
detalle del TPV y sobre el apartado *Pagos* incorpora la opción **Efectivo** como método de pago.

Al incorporar este método, es posible establecer la cantidad de monedas y billetes que debe disponer la caja tanto al iniciar
como al finalizar la sesión.

Configurar esta opción es tarea necesaria ya que todas las cajas deben disponer de monedas y billetes para poder
devolver el cambio a los clientes.

.. image:: control_caja/metodo.png
   :align: center
   :alt: Efectivo como método de pago

Para gestionar las posibles monedas o billetes a incorporar sobre el TPV, navega a la pantalla :menuselection:`Punto de Venta --> Configuración --> Monedas / Billetes`.
Esta acción te llevará a la pantalla de valores de moneda de los TPV, donde podrás crear nuevos registros mediante el
botón **Crear** o actualizar los existentes.

.. image:: control_caja/configurar_monedas.png
   :align: center
   :alt: Gestionar las posibles monedas o billetes a incorporar sobre el TPV

Una vez configuradas las agrupaciones de moneda, desde la pantalla de configuración del TPV, deberás seleccionar
aquellas que consideres oportunas sobre el apartado **Monedas / Billetes**.

.. image:: control_caja/monedas.png
   :align: center
   :alt: Monedas / Billetes sobre el TPV

.. note::
   Hay que ser cuidadoso al establecer los valores de apertura por defecto ya que en función del tipo de negocio, puede ser común que los clientes paguen con moneda pequeña, moneda de alto valor, etc. Si no dispones de suficiente cambio de moneda, el empleado deberá solicitar cambio, provocando lentitud en las colas de caja y el consiguiente malestar en los clientes.

