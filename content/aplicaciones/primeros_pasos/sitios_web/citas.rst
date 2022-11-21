:show-content:

=====================
Citas
=====================
..
   .. image:: citas/citas.svg
      :align: center
      :width: 150
      :alt: Chat

Daeris dispone de un servicio que permite a tus clientes, programar citas en el calendario de tus empleados a su conveniencia.
Gracias a la aplicación de citas, tus clientes serán autónomos a la hora de realizar reservas, permitiéndote gestionarlas fácilmente.

Crear un bloque de gestión de citas
=====================================

Un *bloque de gestión de citas* es un apartado desde donde los clientes de nuestro sitio web pueden registrar sus citas con nuestros empleados.
Para gestionar los bloques de citas navega a la pantalla :menuselection:`Citas --> Citas`.
Para crear un nuevo bloque pulsa el botón *Crear*.

.. seealso::
   * :ref:`sitios_web/citas/crear_bloque`

Configurar franjas horarias
============================
Las *franjas horarias*, permiten identificar la posibilidad del inicio de una cita para un usuario determinado en un día de la semana concreto (de lunes a domingo).
Cada franja horaria se corresponderá con una única posible cita, siempre que el usuario no tenga planificado ningún evento en el calendario que coincida con la cita.
Los clientes podrán seleccionar las franjas horarias libres de los usuarios asociados a las citas, siempre que la duración de la cita no se superponga con un evento posterior.

Para crear franjas horarias, navega a la pantalla :menuselection:`Citas --> Configuración --> Franjas horarias` y haz clic sobre el botón *Crear*.

.. seealso::
   * :ref:`sitios_web/citas/franjas`

Configurar la protección de envio de formularios frente a SPAM
===============================================================

Para habilitar el sistema de Google ReCaptcha navega a la pantalla :menuselection:`Citas --> Configuración --> Ajustes`
e informa sobre el campo *Clave ReCaptcha* tu clave de Google ReCaptcha.

Si no dispones de una clave ReCaptcha, puedes crear una `Aquí <http://www.google.com/recaptcha/admin>`_. La clave creada debe ser de tipo ReCaptcha v2 y el dominio debe coincidir con el dominio de tu instancia daeris.

.. seealso::
   * :ref:`sitios_web/citas/spam`

Limitar el acceso al registro de citas
=======================================

Daeris permite limitar la opción de crear registros de citas a usuarios registrados en el sistema.
Mediante esta opción, solo se permite generar citas si el cliente se ha registrado previamente en el portal de cliente y se ha autentificado en el sistema.
Para usar esta opción, navega a la pantalla :menuselection:`Citas --> Configuración --> Ajustes`.
Mediante el campo *visibilidad*, podemos incorporar la opción *Usuarios no registrados*, opción por defecto o *Usuarios registrados*, opción que limitará la posibilidad de crear citas a clientes registrados en el sistema.

.. seealso::
   * :ref:`sitios_web/citas/registro`
