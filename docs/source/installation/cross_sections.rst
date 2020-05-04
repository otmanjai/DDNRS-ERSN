.. _installation_cross_sections:

===========================
Cross Section Configuration
===========================

In order to run a simulation with DDNRS-ERSN, you will need cross section data for
each nuclide or material in your problem. DDNRS-ERSN can be run in multi-group mode using variuos nuclear data formats such as: 
**DRAGLIB**, **APOLLO** and **WIMS-D4** libraries.

Using Pregenerated Libraries
----------------------------

Various evaluated nuclear data libraries have been processed into the XMAS or SHEM binary formats required by **DRAGON5** code and can be found at: https://www.polymtl.ca/merlin/libraries.htm.

.. _create_xs_library:

Manually Creating a Library from ENDF files
-------------------------------------------

If you need to create a nuclear data library or you need to further customize the data (for example,
adding more temperatures), the **PyNJOY** tool can be used to create data instances. 
