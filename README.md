# MESSAGE-PASSING-INTERFACE
MPI PROGRAMS AND WORKING

################################################ HOW TO RUN MPI PROGRAMS ########################################################################
mpicc hello_world_lab1.c -o 1        ( mpicc  filename.c  -o  1    here -o 1   means exe file so you can give any name to to like a1 a2 etc)
mpirun -np 4 ./1                      (mpir7un -np4 means no of processors here its 4  ./1 means name of exe file you created above)



for threads programs========>>>>
gcc -pthread fibo.c  -o 5         (gcc -pthread filename.c -o 5  (-o 5 means exe file it can have any alphanumeric name)
./5 10                            to run ./5 and 10 means fobinaci of first 10 numbers



mpicc mpi_hello.c -o mpi_hello --> to compile the mpi file .
mpirun -np 4 ./mpi_hello --> to run the exe file 
mpi_hello --> is file name 
mpicc file.c -o file
mpirun -np 4 ./file(exe)


for threads------>
gcc -pthread filename.c -o a -> to compile
./a -> to run
