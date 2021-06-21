PyMoDAQ Plugins Lecroy
######################

PyMoDAQ, Modular Data Acquisition with Python, is a set of **python** modules used to perform automated measurements. 

This repository contains various hardware plugins compatible with PyMoDAQ

For an exhaustive list of the available plugins, see https://github.com/CEMES-CNRS/pymodaq_plugin_manager/blob/main/pymodaq_plugin_manager/doc/PluginList.md

GitHub repo: https://github.com/CEMES-CNRS

Documentation: http://pymodaq.cnrs.fr/

Instruments
===========

Below is the list of instruments that can be controlled with this plugin:

Viewers
+++++++

Oscilloscope Lecroy waverunner 9104

System requirements
===================

Operating system: Windows 7 or 10

Python: 3.7

PyMoDAQ: 3.1.2

Installation
============

You need the following python packages to run this plugin.
They can be installed using the command *pip install <package-name>* in a console
where you activated your python environment.

pymodaq >= 3.1.2

numpy

easydict

pyvisa

pywin32

You will also need to install the following softwares.
Follow the link to get the installers.

Lecroy ActiveDSO: https://teledynelecroy.com/support/softwaredownload/activedso.aspx?capid=106&mid=533&smid=

NI-VISA: https://www.ni.com/fr-fr/support/downloads/drivers/download.ni-visa.html#305862


Authors
=======

* David Bresteau (david.bresteau@cea.fr)