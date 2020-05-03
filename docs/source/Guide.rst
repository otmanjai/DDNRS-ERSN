# DDNRS-ERSN

An Open Nuclear Reactor Simulator and Reactor Core Analysis Tool based on the Version5 of the reactor physics codes DRAGON-5 &amp; DONJON-5 developed at École Polytechnique de Montréal.
DRAGON & DONJON Reactor Simulator (ADPRES) is an open nuclear reactor simulator and reactor core analysis tool that solves reactor equations for one, two or three dimensional geometries.

DDNRS-ERSN is also a great learning tool for nuclear reactor theory classes.The main objectives is to make all nuclear engineering students have access on nuclear reactor simulator tool for them to use, learn, and modify for their own purposes. It is open and completely free, so everyone has access to the source codes.
The code, including the graphical user interface is developed and maintained by JAI Otman (Nuclear Engineering PhD) and Prof. EL HAJJAJI Otman from University Abdelmalek Essaadi Tetouan Morocco .

The directory structure of DDNRS-ERSN Tool
=============

        cd DDNRS-ERSN

This directory contains three folders Docs (documentation), Version5_beta_ev1803 (Version5 source files) and libraries (Nuclear Data).

        cd DDNRS-ERSN/Version5_beta_ev1803

This directory contains Version5 source files such as:
* Utilib,
* Ganlib,
* Trivac,
* Dragon and
* Donjon

        cd DDNRS-ERSN/libraries/l_endian

This directory contains the Nuclear Data.

        cd DDNRS-ERSN/src

This directory contains the python files for Graphical User Interface (GUI)


# Instructions for configuring DDNRS-ERSN on UNIX systems
=============

This quick install guide outlines the basic steps needed to install DDNRS-ERSN your computer.

Installing on Linux
-------------------

1. If you are using Ubuntu 18.10 or newer, open a terminal in a GNU/Linux box then install gfortran with the following commands:

        sudo apt-get update
        sudo apt-get install gfortran

2. You need to install gcc library to run the package DDNRS-ERSN:

        sudo apt install gcc

4. Install the DDNRS-ERSN package

        git clone  https://github.com/otmanjai/DDNRS-ERSN.git

5. Import the *DDNRS-ERSN* and run the package in the following way:
    
         cd DDNRS-ERSN
         $ python main.py



[**Project Description**](https://Openrsn.readthedocs.io/en/latest/index.html)

[**Project Presentation**](https://Openrsn.readthedocs.io/en/latest/index.html)

[**Installation Instruction**](https://Openrsn.readthedocs.io/en/latest/Installation.html)

[**Documentation**](https://Openrsn.readthedocs.io/en/latest/index.html)

[**Video Demo**](https://Openrsn.readthedocs.io/en/latest/index.html)

Dependencies:
* gfortran
* gcc
* cmake
* xorg

## Authors

* Otman JAI
* Otman EL HAJJAJI

## How to give feedbacks
You may raise an issue or contact me at:
* otmanway@gmail.com


## License

This code is distributed under the GNU General Public License, see the LICENSE file.

[license](https://ddnrsersn.readthedocs.io/en/latest/License.html).