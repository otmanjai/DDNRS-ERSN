.. _usersguide_install:

==============================
Installation and Configuration
==============================

.. _install_source:

-------------------------------
Installing Version5 from Source
-------------------------------

.. _prerequisites:

Prerequisites
-------------

.. admonition:: Required
   :class: error

    * A Fortran compiler such as gfortran_
    
    * A C/C++ compiler such as gcc_

      If you are using a Debian-based distribution, you can install the g++ compiler using the
      following command::

          sudo apt install g++

    * CMake_ cross-platform build system

      The compiling and linking of source files is handled by CMake in a
      platform-independent manner. If you are using Debian or a Debian
      derivative such as Ubuntu, you can install CMake using the following
      command::

          sudo apt install cmake

Obtaining the Source
--------------------
All Version5 source code is hosted on Merlin_ page. You can download the source code
directly from Merlin_ page or, you can use **wget** to obtain the source code, run the following command::

     wget http://www.polymtl.ca/merlin/downloads/version5_v5.0.6.tgz

.. _gcc: https://gcc.gnu.org/
.. _CMake: http://www.cmake.org
.. _gfortran: https://gcc.gnu.org/wiki/GFortranBinaries
.. _Merlin: https://www.polymtl.ca/merlin/version5.htm
