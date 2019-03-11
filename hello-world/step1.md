To install FLEUR you have to provide a system with at least:
* A Fortran compiler (and a compatible C compiler)
* The cmake executable
* The libxml2 library
* The BLAS/LAPACK library

## Example setup
The configuration of your system might be complex and not at all like the steps we perform here.
If in trouble please contact your system-admin for help.

In this tutorial a basic UBUNTU image is used. Hence we have to install quite some additional software.
Please perform the following steps to install:
* GFortran Version 7 (You need at least this version for FLEUR)
`add-apt-repository -y ppa:ubuntu-toolchain-r/test ;apt update ;apt -y install gfortran-7`{{execute}}
* CMake
`apt -y install cmake`{{execute}}
* The libraries:
`apt -y install libxml2-dev`{{execute}}
`apt -y install liblapack-dev`{{execute}}

