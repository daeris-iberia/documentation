===============================================
Obtener imágenes de productos con Google Images
===============================================

Las imágenes de los productos son muy útiles en Daeris, por ejemplo, para encontrar rápidamente un producto o comprobar
si se ha escaneado el correcto, pero puede ser muy costoso configurarlo, especialmente si dispones de muchos productos.

La **búsqueda personalizada de Google** permite encontrar imágenes automáticamente para tus productos, según su código de
barras, manteniendo tu enfoque en lo que importa en tu negocio. Con una cuenta gratuita de Google, puedes obtener hasta
100 imágenes gratuitas por día. Si necesitas obtener más imágenes, deberás actualizar a una cuenta de pago.

Configuración
=============

Esta funcionalidad requiere configuración tanto en Google como en Daeris.

API de Google
-------------

#. Navega a la página de `Servicios y API de Google Cloud Platform <https://console.developers.google.com/>`_ para
   generar las credenciales de la API de búsqueda personalizada de Google. Inicia sesión con tu cuenta de Google.

#. Selecciona o crea un proyecto de API para almacenar las credenciales. Dale un nombre explícito (por ejemplo,
   *Imágenes de Daeris*).

   .. image:: imagenes_productos/nuevo-proyecto-google.png
      :align: center
      :alt: Nuevo proyecto en la API de Google

#. En la sección de credenciales, haz clic en **Crear credenciales** y selecciona **Clave de API**.

   .. image:: imagenes_productos/crear-credencial-clave-api.png
      :align: center
      :alt: Crear credenciales de clave de API en Google

#. Guarda tu clave API. La necesitarás para el siguiente paso en Daeris.

#. Utiliza la barra de búsqueda para buscar la **Custom Search API** y selecciónala:

   .. image:: imagenes_productos/buscar-custom-search-api.png
      :align: center
      :alt: Buscar "Custom Search API" en Google Cloud Platform

#. Habilita la API.

   .. image:: imagenes_productos/habilitar-custom-search-api.png
      :align: center
      :alt: Habilitar "Custom Search API" en Google Cloud Platform

Búsqueda Programable de Google
------------------------------

#. Navega al `Motor de Búsqueda Programable de Google <https://programmablesearchengine.google.com/>`_ y haz clic en
   **Get Started**. Inicia sesión con tu cuenta de Google.

   .. image:: imagenes_productos/motor-busqueda-programable-google.png
      :align: center
      :alt: Motor de búsqueda programable de Google con el botón de Get Started

#. Completa el idioma y el nombre del motor de búsqueda. Dale un nombre explícito (por ejemplo, *Imágenes de Daeris*).

   .. note::
      Google no permite crear un motor de búsqueda sin haber ingresado al menos un sitio específico para buscar. Puedes
      poner cualquier sitio web (por ejemplo, *www.google.com*) para este paso, lo eliminaremos más tarde.

   .. image:: imagenes_productos/configurar-motor-busqueda-programable-google.png
      :align: center
      :alt: Configurar motor de búsqueda programable de Google

#. Valida el formulario haciendo clic en **Crear**. Luego, navega al modo de edición del motor de búsqueda creado (ya
   sea haciendo clic en **Panel de control** en la página de confirmación o haciendo clic en el nombre de tu motor de
   búsqueda en la página de inicio).

   .. image:: imagenes_productos/panel-control.png
      :align: center
      :alt: Panel de control en el motor de búsqueda programable de Google

#. En la pestaña de **Aspectos básicos**, asegúrate de habilitar la **Búsqueda de imágenes**, la **Búsqueda segura** y
   la **Búsqueda en toda la Web**.

   .. image:: imagenes_productos/aspectos-basicos-busqueda-google.png
      :align: center
      :alt: Aspectos básicos en el motor de búsqueda programable de Google

#. Una vez que la función **Búsqueda en toda la Web** esté habilitada, puedes eliminar de forma segura el sitio que
   colocaste en el paso número 2.

   .. image:: imagenes_productos/eliminar-sitio-web-busqueda.png
      :align: center
      :alt: Eliminar sitios web de búsqueda en el motor de búsqueda programable de Google

#. Guarda tu **ID de buscador**. Lo necesitarás para el siguiente paso en Daeris.

Activación en Daeris
--------------------

#. Navega a la pantalla :menuselection:`Ajustes --> Opciones Generales`, y en el apartado de integraciones, marca la
   opción de **Imágenes de Google**. Una vez hecho esto, pulsa el botón *Guardar* de la pantalla de ajustes y vuelve a
   ese mismo apartado para completar la configuración.

   .. image:: imagenes_productos/habilitar-imagenes-google.png
      :align: center
      :alt: Habilitar imágenes de Google en Daeris

#. Deberás informar la **Clave API** y el **ID del motor de búsqueda** obtenido en los pasos anteriores. Una vez hecho
   esto, pulsa el botón *Guardar* de la pantalla de ajustes.

   .. image:: imagenes_productos/configurar-imagenes-google.png
      :align: center
      :alt: Configurar imágenes de Google en Daeris

Obtén automáticamente las imágenes de tus productos en Daeris
=============================================================

La acción para obtener automáticamente las imágenes de los productos en Daeris aparece en cualquier vista de lista de
Productos o Variantes de producto. A continuación, se detalla una guía paso a paso:

#. Navega a la pantalla :menuselection:`Productos --> Productos` o :menuselection:`Productos --> Variantes de producto`
   desde cualquier aplicación que use productos, como Inventario o Ventas.

#. En la vista de lista, selecciona los productos que necesitan una imagen.

   .. important::
      Solo se procesarán los 10.000 primeros productos o variantes de productos seleccionados.

   .. note::
      Solo se procesarán los productos o variantes de productos con código de barras y sin imagen.

#. En el menú de Acción, selecciona **Obtener imágenes de Google Imágenes** y valida haciendo clic en **Obtener imagen**.

   .. image:: imagenes_productos/obtener-imagenes-google.png
      :align: center
      :alt: Obtener imágenes de Google Imágenes

#. Deberías ver que las imágenes aparecen de forma incremental.

   .. image:: imagenes_productos/imagenes-obtenidas-google.png
      :align: center
      :alt: Imágenes obtenidas de Google Imágenes

   .. note::
      - Solo las 10 primeras imágenes se obtienen de forma inmediata. Si seleccionaste más de 10, el resto se buscará
        como trabajo en segundo plano.
      - El trabajo en segundo plano procesa alrededor de 100 imágenes por minuto. Si alcanza la cuota autorizada por
        Google (ya sea con un plan gratuito o de pago), el trabajo en segundo plano se pondrá en espera durante 24 horas
        y continuará donde se detuvo el día anterior.