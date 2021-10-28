# Introduction-to-MPI

### Installing MPI on Ubuntu
```
$ sudo apt-get install libcr-dev mpich2 mpich2-doc
```
or
```
$ sudo apt-get install -y openmpi-bin
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
