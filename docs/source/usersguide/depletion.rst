.. _usersguide_depletion:

=========
Depletion
=========

DDNRS-ERSN supports coupled depletion, or burnup, calculations through the
**EVO:** module. DRAGON5 solves the transport equation to
obtain transmutation reaction rates, and then the reaction rates are used to
solve a set of transmutation equations that determine the evolution of nuclide
densities within a material. The nuclide densities predicted as some future time
are then used to determine updated reaction rates, and the process is repeated
for as many timesteps as are requested.
