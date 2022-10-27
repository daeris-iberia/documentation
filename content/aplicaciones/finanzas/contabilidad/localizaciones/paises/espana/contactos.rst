====================================================================
Adaptación de clientes, proveedores y bancos
====================================================================

Añade el campo Nombre comercial a las empresas y permite buscar por él.
Permite definir un patrón del nombre a mostrar a partir del nombre y el nombre comercial de la empresa.
Añade los campos nombre largo, NIF y web a los bancos.
Añade los datos de los bancos españoles extraídos del registro oficial del Banco de España (http://goo.gl/mtx6ic). El asistente realiza la descarga automática de Internet, pero si por cualquier razón hay algún problema, existe una copia local cuya última actualización fue el 26/10/2017.

Configuración
=============

Para añadir cuentas bancarias a la compañía, el mejor camino es ir a Contabilidad > Configuración > Contabilidad > Cuentas bancarias.

Para añadir cuentas bancarias a los clientes/proveedores, hay que ir a la lista de empresas desde cualquiera de los accesos, y pulsar sobre el enlace "n Cuenta(s) bancaria(s)" que hay en la pestaña "Ventas y compras".

Para definir el patrón del nombre a mostrar en empresas, hay que ir a Configuración > Técnico > Parámetros > Parámetros del sistema Seleccionar la clave l10n_es_partner.name_pattern Definir el patron utilizando las etiquetas %(name)s para nombre y %(comercial_name)s para nombre comercial.

Información mercantil
=======================

En los contactos que sean del tipo compañía aparecerán unos campos para insertar los datos mercantiles.

Libro
Registro Mercantil
Hoja
Folio
Seccion
Tomo
