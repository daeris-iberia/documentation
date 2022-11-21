:show-content:

=====================
Suscripciones
=====================
..
   .. image:: suscripciones/suscripciones.svg
      :align: center
      :width: 150
      :alt: Chat

Daeris dispone de un módulo de gestión de **Miembros** que puede ser usado para operar clubes,
gimnasios, bibliotecas y muchas otras organizaciones e que incluye todas las funciones necesarias para administrar la membresía.

Crear productos de suscripción
================================

Para crear un producto de suscripción, navega a la pantalla :menuselection:`Miembros --> Configuración --> Productos de Suscripción`
, pulsa el botón *Crear* e informa los campos del formulario.

.. seealso::
   * :ref:`ventas/suscripciones/crear_productos`

Crear miembros
================

Para crear un nuevo miembro, navega a la pantalla :menuselection:`Miembros --> Miembros` , pulsa el botón *Crear*
e informa los campos del formulario.

.. seealso::
   * :ref:`ventas/suscripciones/crear_miembros`

Configurar la membresía gratuita
==================================

Para configurar la membresía gratuita, navega al detalle de un miembro desde la pantalla :menuselection:`Miembros --> Miembros`,
e informa la opción de **Miembro gratuito**.

.. seealso::
   * :ref:`ventas/suscripciones/miembro_gratuito`

Comprar y facturar una membresía
=================================
Para configurar la membresía de pago, navega al detalle de un miembro desde la pantalla :menuselection:`Miembros --> Miembros`,
y desmarcar la opción de **Miembro gratuito**. A continuación, pulsar la opción *Comprar Suscripción*.

.. seealso::
   * :ref:`ventas/suscripciones/comprar_membresia`

Activar las suscripciones de clientes con Stripe
=================================================

Para que los usuarios puedan suscribirse a un servicio o producto mediante el pago recurrente con tarjeta de
crédito o débito crea una cuenta sobre la plataforma de pagos `Stripe <https://stripe.com/es>`__.

Obtén las claves API publica y secreta y añade un nuevo punto de conexión `/stripe-webhook`
para los eventos checkout.session.completed, customer.subscription.updated, customer.subscription.deleted, invoice.payment_failed ,invoice.paid.
Anota el secreto de firma del Webhook para incorporarlo en la configuración de Daeirs.

Desde Daeris, navega a la pantalla :menuselection:`Sitio web --> Configuración --> Ajustes`, y en el
apartado de **Suscripciones**, activa la opción correspondiente.

Por último, completa los campos del formulario de integración de Daeris.

.. seealso::
   * :ref:`ventas/suscripciones/activar_stripe`

Crear los productos y precios de la suscripción
================================================

Navega a tu área de cliente de Stripe, y desde el menú **Productos**, pulsa el botón **Añadir producto**.
Registra el producto y anota el identificador de dichos productos y de sus precios.

Desde Daeris, navega a la pantalla :menuselection:`Miembros --> Configuración --> Productos de Suscripción`,
y crea un nuevo producto mediante el botón *Crear*. Desde el apartado **Stripe** informa el **Id de producto de la suscripción**,
y el  **Id de precio de la suscripción**.

.. seealso::
   * :ref:`ventas/suscripciones/crear_productos_stripe`

Configurar el checkout y el portal de clientes de Stripe
=========================================================

Para configurar el checkout y el portal de clientes de Stripe, navega a tu área de clientes de Stripe, y desde
el menú **Configuración**, accede a la pantalla de **Checkout y Payment Links** y configurar las distintas opciones.

Posteriormente navega a la pantalla de **Configuración**, accede a la pantalla de **Portal de clientes** y configurar las distintas opciones.

.. seealso::
   * :ref:`ventas/suscripciones/configurar_stripe`
