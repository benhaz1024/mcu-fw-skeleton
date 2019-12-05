mcu-fw-skeleton
===============
**mcu-fw-skeleton** means a simple/general mcu firmware skeleton.

main goal is offer a simple mcu firmware skeleton and begin a mcu project fast.

main feature is :
  * **RTOS** FreeRTOS
  *

branch
======

to keep git clone fast, all mcu related resource is a git submodule in one branch.

  * **master** the general component intergretion.
  * **stm32f1xx**
  * **stm32f7xx**
  * **stm32l4xx**

How to Use
==========

example:

we create an stm32f1xx develop framework.

.. code::

git checkout stm32f1xx
git submodule init

