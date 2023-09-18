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

23.
        start_date <- dmy("23012017")

24.
        today()

25.
        year(start_date)

26.
        month(start_date)

27.
        day(start_date)

28.
        month(start_date) <- 2

29.
        day(start_date) <- day(start_date) + 6

30.
        month(start_date) <- month(start_date) - 3

31.
        concatenated_dates <- dmy(c("18.09.2023", "22.10.2023", "09.01.2024"))

32.
        day(start_date) <- day(start_date) + ceiling(runif(n=1, min=0, max=10))