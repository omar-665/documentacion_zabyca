=====================================
Configuración de Contactos y Procesos
=====================================

El siguiente instructivo es direccionado a la configuración y manejo de procesos con diferentes tipos de contacto.

1. Configuración del Contacto
=============================

A continuación la tabla de configuración de contactos:

+-------------------------------+------------+--------------+--------------+-----------------+
|        Tipo de Contacto       | Es Cliente | Es proveedor | Beneficiario | Recibe traslado |
+===============================+============+==============+==============+=================+
|           Proveedor           | ..         |       ￪      |              |                 |
+-------------------------------+------------+--------------+--------------+-----------------+
|            Cliente            |      ￪     |              |              |                 |
+-------------------------------+------------+--------------+--------------+-----------------+
| Empleado (Nómina, Anticipos)  |..          |              |       ￪      |                 |
+-------------------------------+------------+--------------+--------------+-----------------+
|      Empleado (Viáticos)      |            |       ￪      |       ￪      |                 |
+-------------------------------+------------+--------------+--------------+-----------------+
|      Custodio Caja Chica      |            |       ￪      |              |        ￪        |
+-------------------------------+------------+--------------+--------------+-----------------+

Esta configuración se la debe realizar en la siguiente dirección :menuselection:`-->` Módulo de contactos :menuselection:`-->` Seleccionar e ingresar al contacto :menuselection:`-->` Ir a la pestaña **Ventas y Compras** :menuselection:`-->` Seleccionar check según corresponda

2. Procesos de Creación de Documentos y Registro de Pagos
=========================================================

A continuación una tabla de explicación

+------------------------------+--------------------------------------------+--------------------------------------+
|       Tipo de Contacto       |                 Documentos                 |                 Pagos                |
+==============================+============================================+======================================+
| Proveedor                    | Contabilidad / Compras /                   | Contabilidad / Compras / Pagos       |
|                              | Facturas de Proveedor                      |                                      |
+------------------------------+--------------------------------------------+--------------------------------------+
| Cliente                      | Contabilidad / Ventas /                    | Contabilidad / Ventas / Pagos        |
|                              | Facturas de Cliente                        |                                      |
+------------------------------+--------------------------------------------+--------------------------------------+
| Empleado (Nómina)(Anticipos) | ( Nómina / Roles )                         | ( Nómina / marcar roles /            |
|                              | ( Empleados / Loans)                       | Botón acción / Pagar )               |
|                              |                                            | (Nómina / marcar loans / Acreditar ) |
+------------------------------+--------------------------------------------+--------------------------------------+
| Empleado (Viáticos)          | Contabilidad / Compras /                   | Marcar Factura / Botón acción /      |
|                              | Facturas con traslado de deudas            | Registrar pago                       |
+------------------------------+--------------------------------------------+--------------------------------------+
| Custodio Caja Chica          | Documento generado de una                  | Marcar Facturas / Botón acción /     |
|                              | factura de proveedor (Creación automática) | Registrar pago                       |
+------------------------------+--------------------------------------------+--------------------------------------+
