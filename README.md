# Practica 7: Memoria Virtual

## Compilación

1.- Compilar la rutina para el manejo de fallos de página. En este paso se generará un archivo .o que será encadenado al programa ejecutable.
```
gcc -c pagefault.c
```

2.- Compilar el archivo donde están los procesos encadenándose a los archivos pagefault.o generado en el paso 1 y mmu.o.
```
gcc -o procesos procesos.c mmu.o pagefault.o
```

## Ejecución

Para ejecutarlo en modo normal solamente ejecute el programa procesos.
```
./procesos
```
Para ejecutarlo en modo de depuración, ejecute el programa process añadiendo el parámetro /debug.
```
./procesos /debug
```
