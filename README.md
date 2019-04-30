# ASM_programming

These were written for a x86_64 running macOS 10.14 and assembled with NASM (Intel syntax).

Assemble using
nasm -f macho64 main.asm -o main.o

Link using 
ld -e _start -macosx_version_min 10.14 -arch x86_64 assembly.o -lSystem -no_pie

Remind me to create a make file
