:show-content:

============
Google Drive
============

Las empresas suelen tener documentos que se encuentran fuera del sistema de gestión empresarial. En Daeris, los usuarios
pueden almacenar y administrar dichos documentos con la ayuda de **Google Drive**.

Google Drive es una de las mejores aplicaciones de almacenamiento en la nube disponibles y ofrece un sistema de
gestión de documentos eficiente. La integración de Daeris con Google Drive permite a los usuarios gestionar los archivos
y documentos relacionados con el negocio de forma estructurada. Lo que significa que el usuario puede agregar muchos
datos adicionales específicos de la industria sin incorporar modelos y campos adicionales en Daeris.

Configuración
=============

.. _productividad/google_drive/habilitar_google_drive:

Habilitar Google Drive
~~~~~~~~~~~~~~~~~~~~~~

Para integrar Daeris con Google Drive, navega a la pantalla :menuselection:`Ajustes --> Opciones Generales`, y dentro del
apartado de integraciones, activa la opción de **Google Drive**:

.. image:: google_drive/activar-google-drive.png
   :align: center
   :alt: Activar Google Drive en Daeris

Una vez hecho esto, pulsa el botón *Guardar* de la pantalla de Ajustes.

A continuación, vuelve al apartado de integraciones para terminar de configurar la funcionalidad. Para ello, pulsa el
enlace para establecer el token de Google Drive:

.. image:: google_drive/configurar-token-google-drive.png
   :align: center
   :alt: Configurar token de Google Drive

Esto abrirá la siguiente ventana:

.. image:: google_drive/configurar-token-actualizacion.png
   :align: center
   :alt: Configurar token de actualización de Google Drive

Para configurar el token, deberás pulsar el enlace **Obtener el código de autorización**, que abrirá una nueva ventana
en donde podrás acceder a tu cuenta de Google Drive:

.. image:: google_drive/selecciona-cuenta-google.png
   :align: center
   :alt: Seleccionar una cuenta de Google Drive

Una vez seleccionada la cuenta, el sistema solicitará permisos para acceder a tu cuenta de Google Drive. Pulsa el botón
*Permitir*:

.. image:: google_drive/permitir-acceso-google-drive.png
   :align: center
   :alt: Permitir el acceso a Google Drive

Por último, el sistema mostrará un token que tendrás que copiar:

.. image:: google_drive/token-google-drive.png
   :align: center
   :alt: Token de Google Drive

A continuación, introduce el token copiado en Daeris, y pulsa el botón *Confirmar*:

.. image:: google_drive/confirmar-token-google-drive.png
   :align: center
   :alt: Confirmar token de Google Drive

Configurar plantillas de Google Drive
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

El siguiente paso consiste en configurar las plantillas de Google Drive. Para ello, pulsa el enlace *Plantillas de Google Drive*:

.. image:: google_drive/plantillas-google-drive.png
   :align: center
   :alt: Plantillas de Google Drive

El sistema navegará a la pantalla de plantillas donde deberás crear una nueva plantilla mediante el botón *Crear*. A
continuación, informa los siguientes campos:

-  **Nombre de la plantilla**: Otorga un nombre específico para la plantilla.

-  **Modelo**: Modelo al que se ve afectada la plantilla. En este ejemplo crearemos una plantilla para el modelo *Proyecto*.

-  **Filtro**: Filtros personalizados para la plantilla.

-  **URL de la plantilla**: URL de un documento en la unidad de Google Drive a la que se deben adjuntar los documentos.
   Este documento servirá como plantilla a la hora de generar documentos para el modelo afectado.

-  **Patrón de nombres de Google Drive**: Es el patrón de nombre del documento. Por ejemplo, al informar `Proyecto: %(name)s`,
   el documento de Google Drive se guardará con el literal *Proyecto* más el nombre del proyecto seleccionado.

.. image:: google_drive/detalle-plantilla-google-drive.png
   :align: center
   :alt: Detalle de una plantilla de Google Drive

Una vez creada la plantilla, pulsa el botón *Guardar*.

Crear y adjuntar documentos de Google Drive a cualquier registro
================================================================

Siguiendo el ejemplo de la plantilla creada en el paso anterior, navega a la pantalla :menuselection:`Proyecto --> Configuración --> Proyectos`,
y accede al detalle de un proyecto. Desde el menú acción, selecciona la acción con nombre **Proyecto**:

.. image:: google_drive/accion-proyecto.png
   :align: center
   :alt: Acción de Google Drive en proyecto

El sistema abrirá una nueva ventana que permitirá editar un nuevo documento en Google Drive, tomando como base la
plantilla especificada:

.. image:: google_drive/editar-documento-google-drive.png
   :align: center
   :alt: Editar documento en Google Drive

Uno de los beneficios de la integración con Google Drive es que evita la necesidad de disponer de múltiples campos de
datos para varios registros dentro de Daeris.

De esta manera, la integración de Google Drive te permitirá organizar la información asociada con los registros de
Daeris sin una gran personalización.
