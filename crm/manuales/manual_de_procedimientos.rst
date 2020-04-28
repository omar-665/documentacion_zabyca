========================
Manual de Procedimientos
========================

I. OBJETIVO
===========

- Definir el proceso para la generación del anexo RDEP del período a declarar 2018

- Establecer las reglas salariales que forman parte de ingresos gravados y exentos

II. ALCANCE
===========

Este manual aplica a la generación del anexo de Relación de Dependencia para el período 2018 a ser declarado en enero 2019.

III. REFERENCIAS
================

Reglamento Ley Orgánica Régimen Tributario Interno Resolución No. NAC-DGER2006-0791 - 72 KB (fecha publicación: 19 de diciembre de 2006)

Resolución No. NAC-DGER2007-1352 - 56 KB (fecha publicación: 12 de febrero de 2008) Resolución No. NAC-DGER2012-0829 - 2 MB (fecha publicación: 26 de diciembre de 2012)

Resolución No. NAC-DGER2013-0880 - 159 KB (fecha publicación: 23 de diciembre de 2013) Resolución No. NAC-DGERCGC14-00124 - 49 KB (fecha publicación: 24 de febrero de 2014)

IV. TÉRMINOS Y DEFINICIONES
===========================

:menuselection:`-->` **SRI** Servicio de Rentas Internas Proveedor del Sistema: Zabyca

:menuselection:`-->` **RDEP** Retenciones en la Fuente Bajo Relación de Dependencia Regla Salarial: Es la definición para el cálculo de los rubros de ingresos y egresos de Nómina

:menuselection:`-->` **Etiquetas XML** Campos definidos por el Servicio de Rentas Internas para la estructura del XML del Anexo

:menuselection:`-->` **Tipo de Valor** Agrupación de las Etiquetas XML

:menuselection:`-->` **Ficha del empleado** Reporte donde se encuentra la información el empleado usada por el sistema

:menuselection:`-->` **Gastos Personales** Son gastos que las personas naturales pueden deducirse para el Impuesto a la Renta, tales como Vivienda, Vestimenta, Alimentación, Salud, y Educación Arte y Cultura

:menuselection:`-->` **Tabla Impuesto a la Renta** Valores definidos por el Servicio de Rentas Internas anualmente para determinar el Impuesto a la Renta para Personas Naturales

  **MANUAL DE PROCEDIMIENTOS**

  **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

  **Emisión 04/enero/2019  Versión 00**

V. POLÍTICAS
============

**De la generación del Anexo RDEP**
-----------------------------------

Se deberá anualmente general el Anexo de Retenciones en la Fuente Bajo Relación de Dependencia (RDEP), según las disposiciones emitidas por el Servicio de Rentas Internas para cada año

**De la responsabilidad de Contabilidad**
-----------------------------------------

Es responsabilidad del área de contabilidad la generación y revisión del Anexo de Retenciones en la Fuente Bajo Relación de Dependencia (RDEP)

**De la configuración y actualización de las Etiquetas XML**
------------------------------------------------------------

Es responsabilidad del usuario del Sistema configurar y de ser el caso actualizar las Etiquetas XML, según las reglas salariales requeridas, para que sean cargadas al XML del Anexo RDEP

**De la creación de la Tabla de Impuesto a la Renta**
-----------------------------------------------------

Es responsabilidad del usuario del Sistema la crear y de ser el caso actualizar la tabla de impuesto a la Renta, según los cambios del Servicio de Rentas Internas

**De los Tipos de Gastos Personales**
-------------------------------------

Es responsabilidad del usuario del Sistema la crear y de ser el caso actualizar de los tipos de gastos personales, según los cambios del Servicio de Rentas Internas

**De las actualización de las fichas de los empleados**
-------------------------------------------------------

Es responsabilidad del usuario del Sistema la actualización de la ficha de los empleados con la información necesaria para la generación del Anexo RDEP

**De los proveedores del Sistema**
----------------------------------

Es responsabilidad del proveedor del Sistema facilitar los permisos necesarios para la generación y edición de las etiquetas XML y generación del Anexo RDEP

Indicar los cambios realizados en el sistema para la generación del Anexo RDEP requeridos por el Servicio de Rentas Internas

  **MANUAL DE PROCEDIMIENTOS**

  **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

  **Emisión 04/enero/2019 Versión 00**

VI. PROCEDIMIENTOS
==================

1. Ingreso al Sistema Integralis360.com
---------------------------------------

1.1 Administrador del Sistema
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Dar permisos al usuario para la generación del Anexo RDEP, y configuración de las Etiquetas del XML

Establecer en la ficha de empleados los campos a reportar en el Anexo RDEP, según las nuevos requerimientos del Servicio de Rentas Internas.

2. Actualización Tabla Impuesto a la Renta para personas naturales
------------------------------------------------------------------

2.1 Ingreso al Sistema Integralis360.com
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

2.2 Módulo de Empleados – Configuración – Tabla de Impuesto a la Renta
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

2.3 Verificar los valores de la Tabla y de ser necesario rectificar, esto aplicará para los usuarios que No hayan utilizado esta tabla en períodos anteriores. Para períodos posteriores se deberá crear otra Tabla que corresponda al año actual.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Imagen 1

2.4 Crear nueva tabla en el caso que SI se haya utilizado en períodos anteriores y marcar como activo la tabla vigente, previamente desactivar la tabla anterior.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

                      **MANUAL DE PROCEDIMIENTOS**

                      **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

                      **Emisión: 04-enero-2019 Versión: 00**

Imagen 2

2.5 Valores de la tabla serán el resultado de dividir, Tabla Anual de Impuesto a la Renta para personas Naturales emitida por el Servicio de Rentas Internas cada año para doce (12). Los porcentajes de Impuesto a la Fracción Básica Excedente NO se deberán ser divididos.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

3. Actualización Gastos Personales
----------------------------------

3.1 Módulo de Empleados – Configuración – Tipo de Gastos Personales
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

3.2 Los valores son el máximo deducible del 1.3 veces de la Fracción Básica desgravada de Impuesto a la Renta Personas Naturales distribuido para cada tipo de gasto, dividido para doce (12) y en el caso de salud.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

                                                     **MANUAL DE PROCEDIMIENTOS**

                            **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

                                                   **Emisión 04/enero/2019 Versión 00**

Imagen 3

4. Configuración de las Etiquetas XML
-------------------------------------

4.1 Módulo de Nómina
~~~~~~~~~~~~~~~~~~~~

4.2 RDEP
~~~~~~~~

4.3 Etiquetas XML
~~~~~~~~~~~~~~~~~

Imagen 4

                            **MANUAL DE PROCEDIMIENTOS**

                            **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

                            **Emisión: 04-enero-2019 Versión: 00**

4.4 Editar las Etiquetas XML
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

4.4.1 Se debe agrupar las Etiquetas por Tipo de Valor
*****************************************************

4.4.2 Los Tipos de Valor que deberán ser editados únicamente por el usuario son los de tipo Gastos Personales y Reglas Salariales
*********************************************************************************************************************************

Imagen 5

4.4.3 Dentro de las Etiquetas XML de Tipo Gasto tenemos los gastos personales, en los que se deberá ubicar la Compañía y el tipo de Gasto Personal.
*******************************************************************************************************************************************************

4.4.4 Los Tipos de Valor CÓDIGO PYTHON y VALOR POR DEFECTO NO DEBEN SER EDITADOS por el usuario, cualquier cambio será responsabilidad exclusiva del mismo.
******************************************************************************************************************************************************************

Imagen 6


                                                     **MANUAL DE PROCEDIMIENTOS**

                            **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

                                                   **Emisión: 04-enero-2019 Versión: 00**

Imagen 7

4.4.5 Dentro de las Etiquetas XML de Regla Salarial tenemos las reglas salariales, donde deberá primeramente ubicar la Compañía, y segundo se deben ubicar por el tipo de Ingreso Gravado o Exento.
***************************************************************************************************************************************************************************************************

Imagen 8

**MANUAL DE PROCEDIMIENTOS**

**PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

**Emisión: 04-enero-2019 Versión: 00**

Imagen 9

4.5 Actualizar Fichas de empleados en el Módulo de Empleados, de acuerdo a los cambios del Servicio de Rentas Internas para el 2019.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

4.5.1 Dentro de las fichas de los empleados, dentro de la pestaña Datos médicos se debe marcar con un visto si es una persona con discapacidad, y llenar el campo tipo de discapacidad y el porcentaje de la misma.
********************************************************************************************************************************************************************************************************************************


Imagen 10

                                                     **MANUAL DE PROCEDIMIENTOS**

                            **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

                                                   **Emisión 04/enero/2019 Versión 00**

4.5.2 Dentro de la ficha del empleado, en la pestaña de RDEP se debe llenar el campo de Condiciones respecto a la Discapacidad si aplica, y seleccionar si el empleado es una persona con enfermedad catastrófica.
*********************************************************************************************************************************************************************************************************************

Imagen 11

4.5.3 Se debe revisar que los números de cédulas de los empleados sean los correctos.
*************************************************************************************


4.6 Generación del Anexo RDEP
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

4.6.1 Nómina-Reportes-Anexo RDEP- Crear
***************************************

Imagen 12

                                                     **MANUAL DE PROCEDIMIENTOS**

                            **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

                                                   **Emisión 04-enero-2019 Versión 00**

4.6.2 Poner el nombre del Anexo
*******************************

4.6.3 Seleccionar el año y la compañía
**************************************

Imagen 13

4.6.4 Guardar
*************

4.6.5 Generar
*************

4.6.6 Descargar el archivo adjunto y Validar en el DIMM
*******************************************************

Imagen 14

                                                     **MANUAL DE PROCEDIMIENTOS**

                            **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

                                                   **Emisión 04-enero-2019 Versión 00**

VII. CONTROL DE CAMBIOS
=======================

El presente documento es la primera versión del Manual de Procedimientos para la generación del Anexo de Retenciones en la Fuente Bajo Relación de Dependencia, por ende, no registra cambios anteriores, y los mismos deberán ser posteriores a esta fecha.

   **MANUAL DE PROCEDIMIENTOS**

   **PARA LA GENERACIÓN ANEXO DE RETENCIONES EN LA FUENTE BAJO RELACIÓN DEPENDENCIA (RDEP)**

   **Emisión 04-enero-2019 Versión 00**
