=============================================
Autenticación de inicio de sesión de Facebook
=============================================

La **autenticación de inicio de sesión de Facebook** es una función útil que permite que los usuarios inicien sesión en
Daeris con su cuenta de Facebook, evitando de esta manera que tengan que crear una nueva contraseña, pudiendo utilizar
las credenciales de Facebook.

Configuración
=============

La integración de la función de inicio de sesión con Facebook requiere que se realice configuración tanto en Facebook como
en Daeris.

Apps de Facebook
----------------

#. Navega a la plataforma de `Apps de Facebook <https://developers.facebook.com/apps>`_.
#. Inicia sesión con tu cuenta de Facebook.

   .. image:: facebook/iniciar-sesion-facebook.png
      :align: center
      :alt: Iniciar sesión en Facebook

   .. note::
      En caso de no disponer de una cuenta de Facebook para desarrolladores, selecciona la opción del menú *Empezar*
      para crear una nueva cuenta.

Crear una App de Facebook
~~~~~~~~~~~~~~~~~~~~~~~~~

#. Crea una nueva app:

   .. image:: facebook/crear-app.png
      :align: center
      :alt: Crear app en Apps de Facebook

#. Selecciona el tipo de app *Consumidor* que permite utilizar el inicio de sesión con Facebook y pulsa el botón *Siguiente*:

   .. image:: facebook/tipo-app-facebook.png
      :align: center
      :alt: Tipo de app de Facebook

#. Incorpora un nombre intuitivo a la app y una cuenta de correo, y pulsa el botón *Crear app*:

   .. image:: facebook/informacion-basica-app-facebook.png
      :align: center
      :alt: Información básica de la app de Facebook

Configuración de la App
~~~~~~~~~~~~~~~~~~~~~~~

#. Una vez creada la app, en el lado izquierdo del menú haz clic en :menuselection:`Configuración --> Básica`.

   .. image:: facebook/configuracion-basica-app-facebook.png
      :align: center
      :alt: Configuración básica de la app de Facebook

#. Informa un icono de la app, un enlace a la política de privacidad de la aplicación (por ejemplo,
   `https://daeris.com/legal/politica-de-privacidad`), un enlace a las condiciones del servicio de la aplicación (por ejemplo,
   `https://daeris.com/legal/condiciones-de-uso`), un enlace a las instrucciones para eliminación de datos (por ejemplo,
   `https://daeris.com/legal/politica-de-privacidad`), un dominio autorizado (por ejemplo, `daeris.com`), un correo electrónico
   de contacto, e informa la categoría *Negocios y páginas*. Una vez completados estos campos, pulsa el botón *Guardar cambios*.

   .. image:: facebook/pantalla-configuracion-basica-app-facebook.png
      :align: center
      :alt: Pantalla de configuración básica de la app de Facebook

   .. note::
      Copia el **Identificador de la app**, que necesitarás más adelante para configurar Daeris.

#. En el lado izquierdo del menú haz clic en :menuselection:`Configuración --> Avanzada`.

   .. image:: facebook/configuracion-avanzada-app-facebook.png
      :align: center
      :alt: Configuración avanzada de la app de Facebook

#. Agrega la lista de dominios autorizados de redireccionamiento, que se corresponde con el nombre de dominio de tu
   instancia de Daeris y pulsa el botón *Guardar cambios*.

   .. image:: facebook/lista-dominios-autorizados.png
      :align: center
      :alt: Lista de dominios autorizados de redireccionamiento de la app de Facebook

Configuración del inicio de sesión con Facebook
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. En el lado izquierdo del menú haz clic en :menuselection:`Agregar producto`.

#. Haz clic en el botón *Configurar* del producto de **Inicio de sesión con Facebook**.

   .. image:: facebook/configurar-inicio-sesion-facebook.png
      :align: center
      :alt: Configurar inicio de sesión con Facebook

#. En el lado izquierdo del menú haz clic en :menuselection:`Inicio de sesión con Facebook --> Configuración`.

   .. image:: facebook/menu-configuracion-inicio-sesion-facebook.png
      :align: center
      :alt: Menú de configuración del inicio de sesión con Facebook

#. Informa los siguientes parámetros:

   #. Inicio de sesión del cliente de OAuth: Sí
   #. Inicio de sesión de OAuth web: Sí
   #. Forzar reautenticación de OAUth web: No
   #. Usar modo estricto para URI de redireccionamiento: Sí
   #. Aplicar HTTPS: Sí
   #. Inicio de sesión de OAuth de navegador integrado: Sí
   #. URI de redireccionamiento de OAuth válidos: Se corresponde con la URL de tu instancia de Daeris seguido de
      /auth_oauth/signin

   .. image:: facebook/configuracion-cliente-oauth.png
      :align: center
      :alt: Configuración del cliente OAuth

   .. warning::
      Cuando registres la app de Facebook por primera vez, se establecerá en el modo de desarrollo. El modo de desarrollo
      limita el acceso de la app a los usuarios que tienen un rol en ella. Antes de pasar la app al modo en vivo, es posible
      que debas hacer una revisión de la app. Este proceso permite a Facebook verificar quién eres y cómo usarás los datos
      a los que acceda tu app. Una vez que hayas probado la app, puedes pasarla al modo activo para que la puedan utilizar
      todos los usuarios.

Autenticación de Facebook en Daeris
-----------------------------------

Activación en Daeris
~~~~~~~~~~~~~~~~~~~~

#. Navega a la pantalla :menuselection:`Ajustes --> Opciones generales` y, desde el apartado de *Integraciones*,
   activa la opción **Autenticación OAuth** y pulsa el botón *Guardar* de la pantalla de ajustes.

   .. image:: facebook/activar-autenticacion-oauth.png
      :align: center
      :alt: Activar autenticación OAuth en Daeris

   .. note::
      Es posible que tengas que volver a iniciar sesión después de este paso.

#. A continuación, vuelve a la pantalla :menuselection:`Ajustes --> Opciones generales` y, desde el apartado de *Integraciones*,
   activa la opción **Autenticación de Faceboook**, informa en el campo identificación de cliente el identificador de tu
   App de Facebook y pulsa el botón *Guardar* de la pantalla de ajustes.

   .. image:: facebook/activar-autenticacion-facebook.png
      :align: center
      :alt: Activar autenticación de Facebook en Daeris

Inicia sesión en Daeris con Facebook
====================================

Usuarios existentes
-------------------

Los usuarios existentes deben :doc:`restablecer su contraseña <../usuarios_companias/usuarios>` para ingresar a la
página de restablecimiento de contraseña. Desde esa página, para vincular tu cuenta de Facebook con tu perfil de usuario
de Daeris, haz clic en *Acceder con Facebook* cuando te pidan elegir una contraseña nueva:

   .. image:: facebook/acceder-con-facebook.png
      :align: center
      :alt: Pantalla de resetear contraseña con el botón de "Acceder con Facebook"

La aplicación te redireccionará a Facebook para que inicies sesión con tu cuenta:

   .. image:: facebook/cuenta-de-facebook.png
      :align: center
      :alt: Seleccionar cuenta de Facebook

Usuarios nuevos
---------------

Los nuevos usuarios que se registren en el portal, pueden hacer clic directamente en *Acceder con Facebook* en lugar de
elegir una contraseña nueva:

   .. image:: facebook/acceder-con-facebook-2.png
      :align: center
      :alt: Pantalla de registro de usuario con el botón de "Acceder con Facebook"

.. seealso::
   - `Ayuda de Facebook para desarrolladores
     <https://developers.facebook.com/docs/>`_