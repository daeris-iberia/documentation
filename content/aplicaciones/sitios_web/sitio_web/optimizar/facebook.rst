==============
Facebook Píxel
==============

El **píxel de Facebook** es una herramienta de análisis con la que puedes medir la eficacia de la publicidad al conocer
las acciones que se realizan en tu sitio web.

Puedes utilizar el píxel para lo siguiente:

-  **Asegurarte de que tus anuncios se muestran a las personas adecuadas**: Encuentra a nuevos clientes o personas que han
   visitado una página específica o han realizado una acción de las que te interesan en tu sitio web.

-  **Aumentar las ventas**: Configura pujas automáticas para dirigirte a personas con mayor probabilidad de realizar alguna
   acción que te interese; por ejemplo, hacer una compra.

-  **Medir los resultados de tus anuncios**: Comprende mejor el impacto de tus anuncios con datos de lo que sucede cuando
   las personas los ven.

.. seealso::
   - `Información sobre el píxel de Meta
     <https://es-es.facebook.com/business/help/742478679120153>`__

Daeris permite monitorizar su sitio web con Facebook píxel. Para ello, es necesario crear un píxel de Facebook y configurarlo
sobre el sitio web.

Configuración
=============

Verificación de dominio de Facebook
-----------------------------------

Recientemente, Facebook anunció cambios importantes que afectan a los eventos web. Por esta razón, es necesario completar
el proceso de verificación del dominio para garantizar que tu empresa tenga control sobre qué píxeles y eventos de conversión
son elegibles para la configuración en tus dominios.

Para configurar la verificación de dominio de Facebook, sigue estos pasos:

#. Ve a `Dominios <https://business.facebook.com/settings/owned-domains>`__ en la sección **Seguridad de la marca** de
   *Configuración del negocio*.

#. Haz clic en **Agregar** para agregar un dominio nuevo.

#. Ingresa el dominio raíz sin ningún prefijo. Por ejemplo, ingresa `sitioweb.com`.

#. Haz clic en **Agregar**.

#. Selecciona la opción para agregar una metaetiqueta a tu código fuente HTML.

#. Copia el valor de la variable **content**.

#. Navega a la pantalla :menuselection:`Sitio web --> Configuración --> Ajustes` y marca la opción **Verificación de dominio de Facebook**.
   En el campo **Código de verificación de dominio** informa el código copiado en el paso anterior y pulsa el botón
   *Guardar* de la pantalla de ajustes.

   .. image:: facebook/facebook-verification.png
      :align: center
      :alt: Verificación de dominio de Facebook

#. Haz clic en **Verificar dominio** en la pantalla del administrador comercial de Facebook.

.. note::
   Una vez que tu dominio esté verificado, puedes eliminar las metaetiquetas sin que se vea afectado tu estado de
   verificación.

.. seealso::
   - `Verificar tu dominio en el administrador comercial
     <https://www.facebook.com/business/help/321167023127050>`__

Creación del píxel de Facebook
------------------------------

Los pasos a seguir a la hora de crear un píxel de Facebook son los siguientes:

#. Navega al `administrador de eventos <https://www.facebook.com/events_manager2>`__.

#. Haz clic en **Conectar orígenes de datos** y selecciona *Web*.

#. Selecciona **Píxel de Meta** y haz clic en *Conectar*.

#. Agrega el **Nombre del píxel**.

#. Ingresa la URL de tu sitio web para ver opciones de configuración sencillas.

#. Haz clic en **Continuar**.

Una vez que hayas creado un píxel de Meta, puedes colocar su código en tu sitio web. Para ello, sigue los siguientes
pasos:

#. Navega al `administrador de eventos <https://www.facebook.com/events_manager2>`__.

#. Haz clic en el icono **Orígenes de datos** en el lado izquierdo de la página.

#. Selecciona el píxel que quieres configurar.

#. Haz clic en **Continuar configuración del píxel**.

#. Selecciona **Instalar código manualmente**.

#. Copia el código base del píxel.

#. A continuación, desde Daeris, accede a la pantalla :menuselection:`Sitio web --> Configuración --> Ajustes` y activa la
   opción de **Facebook Píxel**. En el campo **Píxel ID** será necesario introducir el identificador extraído del código base
   del píxel (es un identificador numérico):

   .. image:: facebook/facebook-pixel.png
      :align: center
      :alt: Facebook Píxel

#. Una vez introducido el píxel, guarda los cambios en la pantalla de ajustes mediante el botón *Guardar*.

#. Vuelve al administrador de eventos de Facebook, y haz clic en *Continuar*.

#. Activa las coincidencias avanzadas automáticas y verifica la información del cliente que quieras enviar.

#. Haz clic en *Continuar*.

#. Haz clic en *Ir al resumen del píxel*.

Sobre la pantalla de eventos, podrás visualizar los eventos que Facebook haya registrado hasta el momento. Daeris dispone
de los siguientes eventos configurados:

-  **Página visitada (PageView)**: Se ejecuta cuando los visitantes navegan por el sitio web. Si accedes a los detalles,
   puedes consultar información relacionada con la página visitada.

-  **Compra (Purchase)**: Se ejecuta cuando el visitante accede a la pantalla de confirmación de una compra. Este evento
   se enriquece con el coste de la compra si accedes a visualizar los detalles.

.. seealso::
   - `Cómo configurar e instalar un píxel de Meta
     <https://es-es.facebook.com/business/help/952192354843755>`__