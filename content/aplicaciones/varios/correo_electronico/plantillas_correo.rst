================================
Plantillas de correo electrónico
================================

Escribir buenos correos electrónicos es vital para obtener una alta tasa de respuesta, pero para no tener que volver a
escribir la misma estructura cada vez, es posible utilizar plantillas de correo electrónico. Sin necesidad de reescribir
toda la estructura del correo electrónico cada vez, puedes ahorrar tiempo y concentrarte en el contenido. Además, varias
plantillas te permiten entregar el mensaje correcto al público adecuado, lo que mejora su experiencia general con la empresa.

Crear copia de seguridad de una plantilla de correo electrónico
===============================================================

Antes de llevar a cabo modificaciones en las plantillas de correo electrónico, es muy recomendable realizar una copia
de seguridad de dichas plantillas, para que puedan ser restauradas posteriormente en caso de errores.

Para crear una copia de seguridad de una plantilla, navega a la pantalla :menuselection:`Ajustes --> Correo electrónico --> Plantillas`,
y accede al detalle de una plantilla:

.. image:: plantillas_correo/detalle-plantilla-correo-electronico.png
   :align: center
   :alt: Detalle de una plantilla de correo electrónico

A continuación, pulsa el botón *Crear copia de seguridad*:

.. image:: plantillas_correo/crear-copia-seguridad-plantilla.png
   :align: center
   :alt: Crear copia de seguridad de una plantilla de correo electrónico

El sistema solicitará confirmación para realizar la copia de seguridad de la plantilla:

.. image:: plantillas_correo/confirmar-crear-copia-seguridad-plantilla.png
   :align: center
   :alt: Confirmar crear copia de seguridad de una plantilla de correo electrónico

Una vez aceptado el mensaje, el sistema creará una copia de seguridad de dicha plantilla, para que pueda ser restaurada
posteriormente en caso de ser necesario.

Modificar una plantilla de correo electrónico
=============================================

Desde Daeris se realizan diversos envíos de correos electrónicos, y algunos de ellos utilizan plantillas de correo predefinidas.
El listado completo de plantillas de correo utilizadas desde la aplicación se puede encontrar en la pantalla
:menuselection:`Ajustes --> Correo electrónico --> Plantillas`:

.. image:: plantillas_correo/plantillas-correo-electronico.png
   :align: center
   :alt: Plantillas de correo electrónico

Para modificar el formato de una plantilla existente, navega al detalle de la plantilla en cuestión y pulsa el botón *Editar*:

.. image:: plantillas_correo/editar-plantilla.png
   :align: center
   :alt: Editar plantilla de correo electrónico

Desde el modo de edición, puedes modificar el contenido de la plantilla desde la pestaña de *Contenido*:

.. image:: plantillas_correo/contenido-plantilla.png
   :align: center
   :alt: Contenido de la plantilla de correo electrónico

.. danger::
   Cualquier modificación de una plantilla, puede dar lugar a errores en la configuración de dicha plantilla, que provoquen
   que el correo no se envíe a los destinatarios. Hay que prestar especial atención a las variables definidas entre corchetes,
   ya que hacen referencia a campos internos de los objetos de Daeris.

Para acceder a un modo de edición avanzado de la plantilla, pulsa el botón *Vista de Código*:

.. image:: plantillas_correo/codigo-plantilla.png
   :align: center
   :alt: Vista de código de la plantilla de correo electrónico

Desde la vista de código, es posible editar el código HTML de la plantilla, lo que permite un nivel de edición más avanzado:

.. image:: plantillas_correo/vista-codigo-plantilla.png
   :align: center
   :alt: Vista de código de la plantilla de correo electrónico

Una vez modificada la plantilla, es posible realizar una prueba de visualización, mediante el botón *Previsualizar*,
ubicado en la parte superior derecha de la pantalla:

.. image:: plantillas_correo/previsualizar-plantilla.png
   :align: center
   :alt: Previsualizar plantilla de correo electrónico

Al previsualizar la plantilla, puedes confirmar si los cambios realizados son correctos. El sistema te permite elegir un
registro de ejemplo para la previsualización de los datos en la plantilla:

.. image:: plantillas_correo/previsualizacion-de-plantilla.png
   :align: center
   :alt: Previsualización de la plantilla de correo electrónico

De esta manera, es posible comprobar que tanto las variables como el formato de la plantilla son correctos.

Restaurar una plantilla de correo electrónico
=============================================

En el caso de que una plantilla no se visualice correctamente tras los cambios realizados, o que, al enviar un correo
con esta plantilla, el contenido del correo aparezca en blanco, puedes restaurar la versión original de la plantilla
mediante el botón *Restaurar copia de seguridad*:

.. image:: plantillas_correo/restaurar-copia-seguridad-plantilla.png
   :align: center
   :alt: Restaurar copia de seguridad de la plantilla de correo

.. note::
   El botón de restauración de copia de seguridad solo aparece en caso de haber creado previamente una copia de seguridad
   de la plantilla de correo.

Al pulsar el botón de restauración, el sistema solicitará confirmación para restaurar la plantilla con los datos originales,
sobrescribiendo tanto el asunto como el cuerpo de la plantilla:

.. image:: plantillas_correo/confirmar-restaurar-copia-seguridad-plantilla.png
   :align: center
   :alt: Confirmar la restauración de la copia de seguridad de la plantilla de correo

Al pulsar el botón *Aceptar*, la plantilla quedará restaurada con su contenido original.

Añadir acción del contexto para una plantilla
=============================================

Es posible mostrar una opción en el objeto asociado a una plantilla para abrir un asistente de composición de correo
electrónico con dicha plantilla. Para ello, pulsa el botón *Añadir acción del contexto* en el detalle de una plantilla:

.. image:: plantillas_correo/anadir-accion-contexto.png
   :align: center
   :alt: Añadir acción del contexto en una plantilla de correo

A continuación, navega a la vista de tipo listado del objeto asociado a la plantilla. Por ejemplo, si añades una acción
del contexto para una plantilla que aplique a *Cliente potencial/Oportunidad*, navega a la pantalla
:menuselection:`CRM --> Clientes potenciales`. Desde la vista de tipo listado, selecciona al menos un registro y haz
clic en el menú *Acción*. Debe aparecer una nueva opción para enviar un correo utilizando la plantilla en la que se
ha añadido la acción del contexto:

.. image:: plantillas_correo/accion-contexto.png
   :align: center
   :alt: Acción del contexto en una plantilla de correo

.. note::
   Es necesario refrescar o cargar la página de nuevo en el navegador para que se vean reflejados los cambios en el menú Acción.

Al seleccionar esa acción, se desplegará el compositor de correos electrónicos informando por defecto la plantilla de
correo electrónico:

.. image:: plantillas_correo/compositor-correos.png
   :align: center
   :alt: Compositor de correos electrónicos

Por último, si la acción se ha creado por error, o si ya no es necesario mostrar esa acción en el contexto del objeto
de la plantilla, es posible eliminar dicha acción pulsando el botón *Eliminar acción del contexto* ubicado en el
formulario de detalle de la plantilla:

.. image:: plantillas_correo/eliminar-accion-contexto.png
   :align: center
   :alt: Eliminar acción del contexto de una plantilla