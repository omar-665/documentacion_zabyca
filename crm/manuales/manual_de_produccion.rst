====================
Manual de Producción
====================

**Previamente**

-Lista de Materiales 

1. ORDEN DE PRODUCCION
======================

1.1 Crear
---------

Ir a: :menuselection:`Módulo de Fabricación --> Operaciones --> Ordenes de Produccion --> Crear --> Ingresar los datos --> Grabar`


.. image:: media/img01.png
   :align: center

:menuselection:`-->` Varios

.. image:: media/img02.png
   :align: center

:menuselection:`-->` Elegir Tipo de Operación

.. note::
    Elegir la bodega desde la cual se realizar la operacion , debe ser la misma que la de donde tomará las materias primas tomando en cuenta esté seguida de: **Fabricación**

:menuselection:`-->` Elegir Ubicación de materias primas

.. note:: 
    Esto predetermina desde que bodega se tomarán las materias primas, se deberá elegir la bodega que esté seguida de **/Existencias**.

:menuselection:`-->` Elegir Ubicación de productos finalizados.

.. note:: 
    Esto predetermina en que bodega se recibirán los productos finalizados , se deberá elegir la bodega que esté seguida de **/Existencias**

:menuselection:`-->` Pulsar **GRABAR**

.. note:: 
    En este punto el sistema calcula cantidades y está a espera de confirmar exista disponibilidad de productos

.. image:: media/img03.png
   :align: center

1.2 Reservar
------------

:menuselection:`Desbloquear --> EDITAR --> Click sobre el producto en la lista de materiales -->` Elegir **Lote** :menuselection:`-->` **GRABAR**

.. image:: media/img04.png
   :align: center

Elegir **Lote** y la cantidad correspondiente en **Realizado** de cada producto :menuselection:`-->GRABAR`

.. note:: Se puede elegir varios lotes

.. image:: media/img05.png
   :align: center

:menuselection:`-->GRABAR --> BLOQUEAR`

.. image:: media/img06.png
   :align: center

Pulsar **COMPROBAR DISPONIBILIDAD**

.. note::
    Los productos de los cuales exista disponibilidad se pintaran de color negro, adicional esta acción reserva la materia prima a utilizar, cuando todos los productos tengan disponibilidad se habilita el botón **PRODUCIR**.

.. image:: media/img07.png
   :align: center

1.3 Terminar
------------

Pulse **Producir**

.. image:: media/img08.png
   :align: center

Crear y Editar el Lote de los nuevos productos

.. image:: media/img09.png
   :align: center

:menuselection:`-->` De ser el caso editar **Cantidad** de productos terminados (Se produjo más o menos de lo esperado)

:menuselection:`-->` De ser el caso editar **Hecho** de productos utilizados (Se utilizó más o menos de lo esperado)

:menuselection:`-->` De ser el caso editar **Añadir un elemento** de productos utilizados extra (Se utilizaron productos diferentes en la producción)

:menuselection:`-->` Pulsar **REGISTRAR PRODUCCION**

:menuselection:`-->` Pulsar **MARCAR COMO HECHO**

.. note::
    En este punto se termina la producción y se carga el inventario.

.. image:: media/img10.png
   :align: center   

1.4 Desechos
------------

Antes de **MARCAR COMO HECHO** de ser el caso que se daño algún insumo dentro de la receta del producto y se va a cargar al costo de la producción 

:menuselection:`-->` Pulsar **DESECHO**

.. image:: media/img11.png
   :align: center   

:menuselection:`-->` Agregar los datos señalados

:menuselection:`-->` Pulsar **REALIZADO**

:menuselection:`-->` Continuar Proceso

.. note::
    En este punto se dio de baja los insumos seleccionados
