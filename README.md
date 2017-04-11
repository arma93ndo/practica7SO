# Practica 7: Memoria Virtual

## Compilación

´´´
gcc -c pagefault.c
gcc -o procesos procesos.c mmu.o pagefault.o

´´´

## Ejecución

Para ejecutarlo en modo normal solamente ejecute el programa procesos:

´´´
./procesos
´´´

Para ejecutarlo en modo de depuración, ejecute el programa procesos añadiendo el parámetro /debug.

´´´
./procesos /debug
´´´