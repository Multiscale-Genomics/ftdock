# FTDock

This is an adapted version of the original FTDock software (Imperial Cancer Research, 2001) with distributed-memory capabilities using the MPI paradigm.
 
The file [grid.c](grid.c) includes a modified version of the function to calculate the total grid span in order to use a faster version of the correlation functions from FFTW.


##Setup
To compile:

```
export MPI_CC=gcc
make -f Makefile.mpi clean
make -f Makefile.mpi
```
