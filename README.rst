The Sheffield Advanced Code
===========================

SAC is a 1-3D ideal MHD / HD solver that solves for pertubations on top of a 
static background.

Building SAC
------------

The standard way to build SAC is::

    cd sac/src
    make vac

It is also possible to build SAC using Python + Fabricate::

    cd sac/src
    python sac_fabricate.py

The fabricate method is designed to allow the automatic configuration of the 
build parameters from other Python code. See https://github.com/SWAT-Sheffield/Flux-Surfaces.

See also the following repositories
1. The VAC Code: https://github.com/SWAT-Sheffield/vac
2. The GPU Version of SAC: https://github.com/SWAT-Sheffield/smaug-all
3. The development area for SAC: https://github.com/SWAT-Sheffield/SAC_svn

Notes on these and in particular Sheffield Magnetohydrodynamics Accelerated Using GPUs (SMAUG)
http://solarwavetheory.blogspot.com/search/label/SMAUG

