===========================================
Autenticación de inicio de sesión de Google
===========================================

La **autenticación de inicio de sesión de Google** es una función útil que permite que los usuarios inicien sesión en
Daeris con su cuenta de Google.

Esto es útil si tu organización utiliza Google Workspace y quieres que los empleados de tu empresa se conecten a Daeris
con sus cuentas de Google.

Configuración
=============

La integración de la función de inicio de sesión con Google requiere que se realice configuración tanto en Google como
en Daeris.

API de Google
-------------

#. Navega a la plataforma de `APIs de Google <https://console.developers.google.com/>`_.
#. Inicia sesión con tu cuenta de Google.

   .. image:: google/iniciar-sesion-google.png
      :align: center
      :alt: Iniciar sesión en Google

#. Asegúrate de tener abierto el proyecto correcto. Si todavía no tienes un proyecto, haz clic en *Crear proyecto*,
   informa el nombre del proyecto y otros detalles de tu empresa y haz clic en *Crear*.

   .. image:: google/nuevo-proyecto.png
      :align: center
      :alt: Crear un nuevo proyecto en APIs de Google

Pantalla de consentimiento de OAuth
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. En el lado izquierdo del menú haz clic en :menuselection:`Pantalla de consentimiento de OAuth`.

   .. image:: google/seleccionar-consentimiento-oauth.png
      :align: center
      :alt: Seleccionar pantalla de consentimiento OAuth

#. Elige una de las opciones (Interno/Externo) y después haz clic en *Crear*.

   .. image:: google/consentimiento.png
      :align: center
      :alt: Seleccionar un tipo de usuario en consentimiento OAuth

#. Informa un nombre de aplicación, un correo electrónico de asistencia, un logotipo, un enlace a la página principal de
   la aplicación (por ejemplo, `https://daeris.com`), un enlace a la política de privacidad de la aplicación (por ejemplo,
   `https://daeris.com/legal/politica-de-privacidad`), un enlace a las condiciones del servicio de la aplicación (por ejemplo,
   `https://daeris.com/legal/condiciones-de-uso`), un dominio autorizado (por ejemplo, `daeris.com`) y un correo electrónico
   de contacto. Una vez completados estos campos, pulsa el botón *Guardar y continuar*.

   .. image:: google/informacion-aplicacion.png
      :align: center
      :alt: Información de la aplicación en consentimiento OAuth

#. En la página de **Permisos**, deja todos los campos como están y haz clic en *Guardar y continuar*.

Credenciales
~~~~~~~~~~~~

#. En el menú del lado izquierdo haz clic en :menuselection:`Credenciales`.

   .. image:: google/seleccionar-credenciales.png
      :align: center
      :alt: Seleccionar credenciales

#. Haz clic en *Crear credenciales* y selecciona **ID de cliente OAuth**.

   .. image:: google/id-cliente-oauth.png
      :align: center
      :alt: ID de cliente de OAuth

#. Selecciona **Aplicación web** como el tipo de aplicación y configura las páginas permitidas a las que se les redirigirá.
   Para ello, en el campo **URI de redireccionamiento autorizados**, introduce la URL de tu instancia Daeris seguido de
   `/auth_oauth/signin`. Por ejemplo, `https://tst15.daeris.com/auth_oauth/signin`. Una vez informados los campos, pulsa
   el botón *Crear*.

   .. image:: google/crear-id-cliente.png
      :align: center
      :alt: Crear id de cliente de OAuth

#. Copia el **ID de cliente** generado por Google.

   .. image:: google/id-cliente.png
      :align: center
      :alt: Id de cliente de Google

Autenticación de Google en Daeris
---------------------------------

Activación en Daeris
~~~~~~~~~~~~~~~~~~~~

#. Navega a la pantalla :menuselection:`Ajustes --> Opciones generales` y, desde el apartado de *Integraciones*,
   activa la opción **Autenticación OAuth** y pulsa el botón *Guardar* de la pantalla de ajustes.

   .. image:: google/activar-autenticacion-oauth.png
      :align: center
      :alt: Activar autenticación OAuth en Daeris

   .. note::
      Es posible que tengas que volver a iniciar sesión después de este paso.

#. A continuación, vuelve a la pantalla :menuselection:`Ajustes --> Opciones generales` y, desde el apartado de *Integraciones*,
   activa la opción **Autenticación de Google**, informa el ID de cliente generado por Google y pulsa el botón *Guardar*
   de la pantalla de ajustes.

   .. image:: google/activar-autenticacion-google.png
      :align: center
      :alt: Activar autenticación de Google en Daeris

Inicia sesión en Daeris con Google
==================================

Usuarios existentes
-------------------

Los usuarios existentes deben :doc:`restablecer su contraseña <../usuarios_companias/usuarios>` para ingresar a la
página de restablecimiento de contraseña. Desde esa página, para vincular tu cuenta de Google con tu perfil de usuario
de Daeris, haz clic en *Acceder con Google* cuando te pidan elegir una contraseña nueva:

   .. image:: google/acceder-con-google.png
      :align: center
      :alt: Pantalla de resetear contraseña con el botón de "Acceder con Google"

La aplicación te redireccionará a Google para que inicies sesión con tu cuenta:

   .. image:: google/cuenta-de-google.png
      :align: center
      :alt: Seleccionar cuenta de Google

Usuarios nuevos
---------------

Los nuevos usuarios que se registren en el portal, pueden hacer clic directamente en *Acceder con Google* en lugar de
elegir una contraseña nueva:

   .. image:: google/acceder-con-google-2.png
      :align: center
      :alt: Pantalla de registro de usuario con el botón de "Acceder con Google"

.. seealso::
   - `Ayuda de Google Cloud Platform Console - Setting up OAuth 2.0
     <https://support.google.com/cloud/answer/6158849>`_