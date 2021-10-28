# Introduction-to-MPI

### Installing MPI on Ubuntu
```
$ sudo apt-get install -y openmpi-bin
```

#### Compiling MPI Programs

```
mpixx -o hello_world hello_world.cpp
```
#### Executing MPI Programs

```
mpirun -np 4 ./hello_world
```
> -np : Number of Processes
