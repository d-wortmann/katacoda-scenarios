The next step is to configure FLEUR using its configure.sh tool.

It's most basic usage is simply:

`fleur/configure.sh`{{execute}}

However, this will fail in this environment as the default fortran compiler is too old.
We will have to set the Fortran compiler explicitly by using

`FC=gfortran-7 fleur/configure.sh`{{execute}}

This configure step will print a summary of the configuration and create a directory 'build' in which FLEUR will be compiled.


You can use  `fleur/configure.sh -h`{{execute}} to find more options. 
