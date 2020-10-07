Fomu on IceStudio *Nightly*
---------------------------

“Hello world!” - Blink a LED
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The canonical “Hello, world!” of hardware is to blink a LED. The
directory ``icestudio`` contains a Blinky example in ICE format.
Moreover, ``Blinky_BoardTop.ice`` wraps Blinky, showcasing how
to use the Design Under Test (DUT) as a black box.

Open ``Blinky_BoardTop.ice`` from Icestudio and use the buttons
on the botton right for verifying, building and uploading the
design to the board.

.. IMPORTANT:: Fomu is currently not supported in the stable releases
  of IceStudio. Development or nightly releases need to be used.
  Moreover, Apio needs to be updated from the git repository:

  .. code-block:: shell

      pip install git+https://github.com/FPGAwars/apio.git@develop#egg=apio
