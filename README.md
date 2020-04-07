#hello world in assembly for linux x86_64
this program will only work if you are using a Linux x86 64 ...

so check before you start:
$ uname -a

for compilation:
$ nasm -f elf64 -o hello.o hello_world.asm
$ ld hello.o -o hello

and then just run
$ ./hello
