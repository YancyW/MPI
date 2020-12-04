# MPI
## init
Because the code need $MPICC, and gcc-8, and use other nodes in the cluster.
Define the following environment variables:
```
export MPICC=/opt/intel/compilers_and_libraries_2019.0.117/linux/mpi/intel64/bin/mpicc
switch_gcc 8
export MPI_HOSTS=~/Code/Git/Introduction/MPI/hosts
```
Then, the mpi code could be run on this machine.

example: in mpitutorial
./run.py mpi_hello_world


# OPENMP
more easy to parallel
```
g++ test_qsort.c -o qsort -fopenmp
```
