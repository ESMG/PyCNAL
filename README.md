# PyCNAL
Python Climate Numerical Analysis Library

This repository makes use of submodules. Clone with:

   git clone --recursive https://github.com/ESMG/PyCNAL

which is equivalent to:

   git clone https://github.com/ESMG/PyCNAL
   cd PyCNAL
   git submodule init
   git submodule update --recursive

Any updates need to be acquired by this last line, updating the
submodules.

The current list of submodules is:

  PyCNAL_core - to contain grid objects, etc.
  PyCNAL_gridgeneration - for grid generation.
  PyCNAL_regridding - USE ESMpy for regridding boundary and initial
    conditions from SODA, etc.

This is under development, with regridding being the most mature.
The goal is to support both the ROMS and MOM6 models in a more flexible
manner, while https://github.com/ESMG/pyroms has the older tools for
ROMS only.
