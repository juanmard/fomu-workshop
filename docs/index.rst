Tutorial FPGA Tomu
==================

.. image:: _static/logo.png
   :align: center
   :width: 600px
   :alt: Fomu logo

¡Hola! ¡Soy `Fomu <https://github.com/im-tomu/fomu-hardware>`_ (FPGA Tomu)!
Este tutorial cubre los aspectos básicos sobre Fomu,
de mayor nivel abstracción hasta los detalles del diseño hardware.
Empezaremos aprendiendo **qué es** Fomu, **cómo cargar software** en Fomu,
**cómo escribir software** para Fomu y finalmente **cómo escribir hardware**
para Fomu.

Las FPGAs son dispositivos complejos y extraños, por lo que iremos poco a
poco. Empezaremos tratando Fomu como un intérprete de Python. Gradualmente,
iremos desgranando las capas hasta escribir nuestros propios registros
hardware. Puedes tomar un descanso en cualquier momento y ¡explorar!
Detente cuando sientas que los conceptos son demasiado extraños, o
sumérgete de lleno en el mundo del hardware.

.. toctree::
   :hidden:
   :maxdepth: 5

   requirements/index
   background
   python
   riscv
   hdl
   renode
   bootloader
   help
