# Proyecto de Algoritmos de Ordenamiento

Este proyecto contiene la implementación de cuatro algoritmos de ordenamiento en lenguaje C:

- Bubble Sort
- Selection Sort
- Insertion Sort
- Quick Sort
  
## Instrucciones de compilación

Usar el compilador `gcc` desde consola o terminal.

```bash
gcc main.c ordenamientos.c -o programa
```

## Ejecución

Una vez compilado el programa, ejecutarlo así:

```bash
./programa
```

##  Análisis breve de resultados

Se miden los tiempos de ejecución de cada algoritmo con el mismo conjunto de datos aleatorios de tamaño 100,000. Se espera:

- **Bubble Sort** y **Selection Sort**: Muy lentos para este tamaño.
- **Insertion Sort**: Ligeramente mejor, pero aún lento.
- **Quick Sort**: Mucho más rápido, ideal para arreglos grandes.

## Capturas de pantalla

![Captura de pantalla 2025-07-04 200154](https://github.com/user-attachments/assets/3e846859-c058-42a1-911b-9e61c0f062fe)


```txt
Ejecutando Bubble Sort
Tiempo de ejecución: 25166.00 milisegundos
Ejecutando Selection Sort
Tiempo de ejecución: 10991.00 milisegundos
Ejecutando Insertion Sort
Tiempo de ejecución: 5595.00 milisegundos
Ejecutando Quick Sort
Tiempo de ejecución: 18.00 milisegundos
```

> Los tiempos pueden variar dependiendo del procesador, sistema operativo y carga del sistema.

