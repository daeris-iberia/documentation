================================================
IRNR - Impuesto sobre la Renta de no Residentes
================================================

Impuestos y posiciones fiscales
=================================================

Se añaden los impuestos y posiciones fiscales para permitir realizar la retención IRPF de no residentes.

La legislación vigente (2015) nos obliga a realizar las siguientes retenciones:

   - Hasta el 31/12/2006 : 25% -> No es necesario por estar obsoleto
   - Del 2007 al 2011: 24% -> No es necesario por estar obsoleto
   - Del 2012 al 2014: 24,75% -> Necesario para migraciones, aplicable a todos los no residentes
   - 2015 (Hasta 11/07/2015): 20% UE, 24% no-UE
   - 2015 (Desde 12/07/2015): 19,50% UE, 24% no-UE
   - 2016: 19% UE, 24% no-UE

.. seealso::
   `Impuesto sobre la Renta de no Residentes: rentas obtenidas sin establecimiento permanente <https://sede.agenciatributaria.gob.es/Sede/no-residentes/irnr-sin-establecimiento-permanente.html>`_ .

Daeris incorpora las retenciones para el 2016 en adelante, añadiendo los impuestos, códigos de impuestos y
posiciones fiscales a las siguientes plantillas:

   - PGCE entidades sin ánimo de lucro 2008
   - PGCE PYMEs 2008
   - PGCE completo 2008

Las posiciones fiscales añadidas nos permiten:

   - Como **empresa** que recibe una factura de un autónomo no residente (UE):
      - Asignar al autónomo la posición fiscal por ejemplo **Retención IRPF No residentes UE 19%**. Por lo tanto, al crear una factura de proveedor de ese autónomo se aplicará la retencion del 19% a todas las líneas de la factura.

   - Como **autónomo no residente** que emite una factura a todos sus clientes (UE):
      - Asignar a todos los clientes que tienen una posición fiscal 'Régimen Nacional' la posición fiscal **Retención IRPF No residentes UE 19%**. Por lo tanto, al crear una factura a un cliente se aplique la retención del 19% a todas las líneas de la factura.

Consideraciones
================

A tener en cuenta que sobre el apartado II. Rentas no sometidas a retención / ingreso a cuenta, no se rellena con ninguna base procedente de las ventas intra o extra comunitarias.
Dichas acciones deben realizarse manualmente.