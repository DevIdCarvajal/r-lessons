# Soluciones rápidas

## Variables

1.
        variableSinValor <- NA

2.
        booleano1 <- TRUE
        booleano2 <- FALSE

3.
        PI <- 3.14

4.
        TAU <- PI * 2

5.
        variableValorNumerico <- 14L

6.
        miNombre <- "Íñigo Montoya"

7.
        miComplejoFav <- 3 + 7i

## Booleanos

8.
        booleanoAnd <- booleano1 && booleano2

9.
        booleanoOr <- booleano1 || booleano2

10.
        booleanoNot <- !booleano1

11.
        booleanoMix0 <- (booleano1 && !booleano2) || (!booleano1 || booleano2)

12.
        booleanoMix1 <- booleano1 && (TAU/2 == PI)

13.
        seisNoEsNueve <- 6 != 9

14.
        booleanoMix2 <- variableValorNumerico > 0 || variableValorNumerico < -(variableValorNumerico * TAU)

## Operadores

15.
        valorSuma <- variableValorNumerico + 23

16.
        valorResta <- 32 - variableValorNumerico

17.
        valorMultiplicacion <- 4 * variableValorNumerico

18.
        valorDivision <- variableValorNumerico / 3

## Estructuras de control de flujo

19.
        contarHasta10while <- 0

        while (contarHasta10while < 10) {
          contarHasta10while <- contarHasta10while + 1
        }

20.
        i <- 0
        j <- 0

        while (i < 11) {
          j <- j + i^2
        }

21.
        sumaPares <- 0

        for (i in 1:10) {
          if (i %% 2 == 0) {
            sumaPares <- sumaPares + i
          }
        }

22.
        contarHasta10for <- 0

        for (i in 1:1000) {
          if (contarHasta10for == 10) {
            break
          } else {
            contarHasta10for <- contarHasta10for + 1
          }
        }

## Manejo de fecha y hora

23. Poblar una variable llamada `start_date` con una representación en formato fecha del string `23012017`.
24. Usar la función `today` para imprimir la fecha actual.
25. Extraer el año de la variable `start_date` del ejercicio anterior.
26. Extraer el mes de la variable `start_date`.
27. Extraer el día de la variable `start_date`.
28. Asignar el mes de la variable `start_date` a febrero.
29. Sumar 6 días a la `start_date`. (¿Qué ha pasado con el mes?)
30. Restar 3 meses a la variable `start_date`.
31. Poblar una variable llamada `concatenated_dates` con un vector de fechas que contengan los siguientes valores: `18.09.2023`, `22.10.2023`, `09.01.2024`.
32. Calcular de la forma más sencilla posible la suma de 1 a 10 días (determinando la cantidad de días aleatoriamente) a la variable `start_date`.