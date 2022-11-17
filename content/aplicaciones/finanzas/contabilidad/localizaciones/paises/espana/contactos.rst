====================================================================
Adaptación de contactos y entidades bancarias
====================================================================

Nombre comercial
=================

Desde la pantalla :menuselection:`Contactos --> Contactos`, y bajo el formulario de un contacto
de tipo **Compañía**, se incorpora el campo **Nombre comercial** el cual permite informar
el nombre comercial de una compañía.

.. image:: contactos/nombre01.png
   :align: center
   :alt: Nombre comercial

Si se informa el nombre comercial, el nombre de la compañía se muestra como el (nombre comercial)
seguido del nombre de la empresa.

.. image:: contactos/nombre02.png
   :align: center
   :alt: Nombre comercial

Comprobación de Calidad de datos identificativos
==================================================

Daeris permite comprobar los datos de la empresa en el censo de la AEAT y en el recargo de equivalencia.

.. seealso::
   `Calidad de datos identificativos <https://www.agenciatributaria.es/static_files/AEAT/Contenidos_Comunes/La_Agencia_Tributaria/Modelos_y_formularios/Declaraciones/Modelos_01_al_99/030_036_037/WS_Masivo/Manual_Tecnico_WS_Masivo_Calidad_Datos_Identificativos.pdf>`_ .


Configurar certificado
-----------------------

Para usar el servicio de censo de la AEAT debes disponer de un certificado válido de tu empresa y/o persona.

Para configurar un certificado navega a la pantalla
:menuselection:`Facturación / Contabilidad --> Configuración --> Certificados AEAT` y haz clic sobre el botón **Crear**.

.. image:: sii/cert01.png
   :align: center
   :alt: Configurar certificados

Sobre el formulario de detalle, informa los siguientes campos:

   - **Nombre**: Nombre del certificado.
   - **Archivo**: Selecciona tu certificado de una entidad certificadora válida.
   - **Nombre de la carpeta**: Especifica un nombre para la carpeta en donde se alojará el certificado en el sistema.

.. image:: sii/cert02.png
   :align: center
   :alt: Configurar certificados

Una vez dado de alta el certificado, pulsa el botón **Obtener claves**.

El sistema mostrará una ventana en donde introducir la contraseña del certificado. Si todo ha ido bien, se
generarán las claves, y se podrá activar el certificado mediante el botón **Para activar**.

Configurar aplicación
-----------------------

Es posible configurar la aplicación, para que al crear o editar un contacto de tipo **Empresa** se
verifique la información en la AEAT de forma automática.

Para ello, navega a la pantalla :menuselection:`Facturación / Contabilidad --> Configuración --> Ajustes` y sobre el apartado
**Impuestos** informa el campo **Verificar información en la AEAT**.

.. image:: contactos/datos00.png
   :align: center
   :alt: Comprobación de Calidad de datos identificativos

También es posible verificar la información de tus propias compañías.

Para ello, navega a :menuselection:`Ajustes --> Usuarios y compañías --> Compañías` y sobre el detalle de una compañía
informa el campo **Verificar Información de la Empresa AEAT**.

.. image:: contactos/datos01.png
   :align: center
   :alt: Comprobación de Calidad de datos identificativos

Para verificar la información de forma manual, navega al detalle de un contacto de tipo
**Empresa** y sobre la pestaña **AEAT**, haz clic sobre el botón **Comprobar datos de la Empresa**.

.. image:: contactos/datos02.png
   :align: center
   :alt: Comprobación de Calidad de datos identificativos

Información mercantil
=======================

Desde la pantalla :menuselection:`Contactos --> Contactos`, y bajo el formulario de un contacto
de tipo **Compañía**, se incorpora una nueva pestaña **Información mercantil**, que permite registrar
la información mercantil. Es posible informar los siguientes campos:

   - **Libro**
   - **Registro Mercantil**
   - **Hoja**
   - **Folio**
   - **Sección**
   - **Tomo**

.. image:: contactos/mercantil01.png
   :align: center
   :alt: Información mercantil

Entidades bancarias
====================

Se añaden los datos de los bancos españoles extraídos del registro oficial del Banco de España.

.. image:: contactos/bancos02.png
   :align: center
   :alt: Entidades bancarias

Desde la pantalla :menuselection:`Contactos --> Configuración --> Bancos`, y bajo el formulario
de una entidad bancaría, se incorporan los campos:

   - Nombre completo
   - NIF
   - Web

.. image:: contactos/bancos01.png
   :align: center
   :alt: Entidades bancarias

