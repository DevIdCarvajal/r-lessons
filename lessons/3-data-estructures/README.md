# 3. Estructuras de datos

## Índice

[1. Vectores](#1-vectores)  
[2. Listas](#2-listas)  
[3. Matrices](#3-matrices)  
[4. Data Frames](#4-data-frames)  
[5. Obtención de subconjuntos](#5-obtención-de-subconjuntos)  
[6. Manejo de valores faltantes](#6-manejo-de-valores-faltantes)

## 1. Vectores

Un vector es una lista de elementos que son del mismo tipo:

    numbers <- c(1, 2, 3, 4, 5)
    numbers2 <- 1:5
    numbers3 <- 1.5:5.5
    numbers4 <- 1.5:5.3

Se puede acceder a un elemento por su índice (los vectores empiezan en 1):

    numbers[1]
    numbers[3] <- 7

Obtener un subconjunto usando otro vector como índice, o un índice negativo:

    numbers[c(1, 3)]
    numbers[c(-1)]

Existen algunas funciones útiles como conocer la longitud, ordenar el vector o hacer copias:

    length(numbers)
    sort(numbers)

    numbers5 <- rep(c(1,2,3), each = 3)
    numbers6 <- rep(c(1,2,3), times = 3)
    numbers7 <- rep(c(1,2,3), times = c(5,2,1))

Para generar vectores con secuencias de números no correlativos:

    numbers8 <- seq(from = 0, to = 100, by = 20)

## 2. Listas

.

## 3. Matrices

.

## 4. Data Frames

.

## 5. Obtención de subconjuntos

.

## 6. Manejo de valores faltantes

.

## Referencias

[Vectores](https://www.w3schools.com/r/r_vectors.asp)  
[Listas](https://www.w3schools.com/r/r_lists.asp)  
[Matrices](https://www.w3schools.com/r/r_matrices.asp)  
[Data Frames](https://www.w3schools.com/r/r_data_frames.asp)  
[]()