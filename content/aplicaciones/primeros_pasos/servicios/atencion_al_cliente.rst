:show-content:

=====================
Atención al cliente
=====================
..
   .. image:: atencion_al_cliente/atencion_al_cliente.svg
      :align: center
      :width: 150
      :alt: Chat

La aplicación de Atención al Cliente de Daeris te ayuda a simplificar tu proceso de soporte: gestionar los problemas
de tus clientes, dar seguimiento a la productividad y agrega agentes al sistema multicanal. Organiza tus tickets
por categorías asignadas a tus empleados y gestiona tus actividades del día a día con reuniones y próximas actividades.

Configurar categorías
==========================
Las *categorías* permiten clasificar y agrupar los tickets en función de las necesidades de tu negocio.

Para crear una categoría de tickets de soporte, navega a la pantalla :menuselection:`Soporte --> Configuración --> Categorías` y haz clic sobre el botón *Crear*.

Para envíar de forma automática la encuesta indicada en la categoría asociada al ticket cuando se cierra, navega a la pantalla :menuselection:`Soporte --> Configuración --> Ajustes`
e informa el campo **Enviar encuestas automáticamente**.

.. seealso::
   * :ref:`servicios/atencion_al_cliente/configuracion_basica/categorias`

Activar y configurar el SLA
=============================
Daeris permite definir distintos niveles de servicio que ofrecer a los clientes.

Para activar el uso del SLA en el sistema, navega a la pantalla :menuselection:`Soporte --> Configuración --> Ajustes`
e informa el campo **Activar el cálculo diario del SLA**.

Para configurar los niveles de servicio (SLA) de los tickets de soporte, navega a la pantalla :menuselection:`Soporte --> Configuración --> SLA's`.

.. seealso::
   * :ref:`servicios/atencion_al_cliente/configuracion_basica/sla`.


Permitir el alta de tickets desde formulario web
=================================================

Daeris permite el alta de tickets de soporte desde el sitio web a los usuarios registrados en la aplicación o a tus visitantes
si se ha configurado la opción correspondiente.

Para ello, navega a la pantalla :menuselection:`Sitio Web --> Configuración --> Ajustes` y sobre el campo
*Permitir el alta de tickets desde el portal de ayuda*, selecciona la opción *solo usuarios registrados*, en el caso de
que **solo los usuarios autentificados en la aplicación**, puedan *crear* tickets.
Si se selecciona la opción *Todos*, **cualquier visitante** puede registrar un ticket.

En el caso de querer proteger el envío de tus formularios de soporte frente al uso fraudulento de robots, es posible utilizar
la tecnología de Google ReCaptcha V3.

Para configurar tus claves, debes navegar a la pantalla :menuselection:`Ajustes --> Opciones Generales` y sobre el apartado *Integraciones*
informar el campo ReCaptcha, asi como la clave del sitio , la clave secreta y la puntuación mínima.

.. important:: Puedes obtener tus claves de Google ReCaptcha haciendo clic sobre el enlace `Generar claves reCAPTCHA v3 <http://www.google.com/recaptcha/admin>`_, opción que te llevará a la página de configuración de Google.

.. seealso::
   * :ref:`servicios/atencion_al_cliente/multicanalidad/ticket_web`.

Permitir el alta de tickets desde correo electrónico
=======================================================

El sistema de gestión de soporte de Daeris permite el alta y gestión del ticket a través del correo electrónico.

Para permitir que cualquier emisor de un correo, pueda registrar tickets de soporte  es necesario disponer de una cuenta de correo electrónico exclusiva, la cual se debe
configurar como servidor de correo entrante. Para ello, debes navegar a la pantalla :menuselection:`Ajustes --> Correo electrónico --> Servidores de correo entrante`.

.. seealso::
   * :doc:`../../varios/correo_electronico/recibir_correos`

Una vez configurado se debe indicar sobre el campo *Crear un nuevo registro* el valor *Ticket de soporte*.

.. warning::
    Si aún no se ha confirmado el servidor de correo, informar el campo **Nuevo registro** creará **un nuevo ticket por cada correo** que exista actualmente en la **bandeja de entrada** de la cuenta de correo.

    Si no deseas que suceda esta situación debes configurar el servidor de correo sin la opción **Nuevo registro** y ejecutar el botón **Probar y confirmar**, hasta que el buzón quede en estado **Confirmado**. Pasados unos minutos, incorpora sobre el campo *Crear Nuevo registro* del servidor de correo el valor *Ticket de soporte*.

.. seealso::
   * :ref:`servicios/atencion_al_cliente/multicanalidad/ticket_correo`.

Configurar la página inicial de soporte
=========================================
Para configurar la página inicial de soporte del sitio web, navega a la pantalla :menuselection:`Sitio Web --> Configuración --> Ajustes`
y sobre la sección *Portal de documentación de soporte*,  informa el Título, Imagen de fondo y la opción
que permite el alta de tickets desde el Portal.

.. seealso::
   * :ref:`servicios/atencion_al_cliente/configuracion_soporte/pagina_inicial`.

Configurar grupos de ayuda
============================
Los grupos de ayuda son contenedores de páginas web que permiten agrupar documentación de soporte de una temática
particular.

Para crear un grupo, navega a la pantalla :menuselection:`Soporte --> Ayuda --> Grupos de ayuda` y haz clic sobre
el botón *Crear*.

.. seealso::
   * :ref:`servicios/atencion_al_cliente/configuracion_soporte/grupos_ayuda`.

Configurar categorías de páginas de ayuda
==========================================
Las categorías de páginas de ayuda, permiten separar las páginas de un grupo sobre el menú del grupo.
Esta opción es muy útil para organizar las páginas por áreas de la misma temática.

Para crear una categoría, navega a la pantalla :menuselection:`Soporte --> Ayuda --> Categoría de páginas` y haz clic sobre el botón *Crear*.

.. seealso::
   * :ref:`servicios/atencion_al_cliente/configuracion_soporte/categorias_ayuda`.

Configurar páginas de ayuda
===============================
Las páginas de ayuda del sitio web, permiten crear documentación de soporte de una temática particular para los clientes y/o empleados.

Para crear una página de ayuda, navega a la pantalla :menuselection:`Soporte --> Ayuda --> Páginas de ayuda` y haz clic sobre el botón *Crear*.

.. seealso::
   * :ref:`servicios/atencion_al_cliente/configuracion_soporte/paginas_ayuda`.

