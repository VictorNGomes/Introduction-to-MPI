# Introduction-to-MPI

Run the following command on `terminal`
```
$ sudo apt-get install libcr-dev mpich2 mpich2-doc
```
#### Compiling MPI Programs

```
mpicc -o hello_world_c hello_world.c
```
#### Executing MPI Programs

```
mpiexec -np 4 ./hello_world_c
```
> -np : Number of Processes
