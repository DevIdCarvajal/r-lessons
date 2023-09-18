# Ejercicios rápidos

## Introducción

A continuación se ofrece una colección de ejercicios rápidos de programación para desarrollar en R.

Aunque están planteados cubriendo un espectro de dificultad incremental, si te atascas mucho con uno pasa al siguiente y ya lo retomarás más adelante.

## Variables

1. Crear una variable de nombre **variableSinValor** declarada **sin ningún valor**
2. Crear dos variables de nombres **booleano1** y **booleano2** con valores **booleanos**
3. Crear un número de nombre **PI** declarado con valor **3.14**
4. Crear un número de nombre **TAU** declarado con valor **2 veces PI**
5. Crear una variable de nombre **variableValorNumerico** declarada con un **valor entero cualquiera**
6. Crear una variable de nombre **miNombre** declarada con el valor de **tu nombre**
7. Crear una variable de nombre **miComplejoFav** declarada con un **valor complejo**

## Booleanos

1. Crear una variable **booleanoAnd** cuyo valor sea la expresión booleana **booleano1** y **booleano2**
2. Crear una variable **booleanoOr** cuyo valor sea la expresión booleana **booleano1** o **booleano2**
3. Crear una variable **booleanoNot** cuyo valor sea la negación de **booleano1**
4. Crear una variable **booleanoMix0** cuyo valor sea la expresión booleana **(booleano1 and not booleano2) or (not booleano1 or booleano2)**
5. Crear una variable **booleanoMix1** cuyo valor sea la expresión booleana **booleano1 and (TAU/2 sea igual a PI)**
6. Crear una variable **seisNoEsNueve** cuyo valor sea la expresión booleana **6 no es igual que 9**
7. Crear una variable **booleanoMix2** cuyo valor sea la expresión booleana **variableValorNumerico positivo (0 no incluido) o menor que -(variableValorNumerico * TAU)**

## Operadores

15. Crear una variable **valorSuma** cuyo valor sea **la suma de variableValorNumerico y 23**
16. Crear una variable **valorResta** cuyo valor sea **la resta de 32 y variableValorNumerico**
17. Crear una variable **valorMultiplicacion** cuyo valor sea **la multiplicación de 4 por variableValorNumerico**
18. Crear una variable **valorDivision** cuyo valor sea **la división de variableValorNumerico entre 3**

## Estructuras de control de flujo

19. Crear una variable **contarHasta10while** con valor **0** e incrementar su valor con un **bucle while hasta que se verifique que contarHasta10while == 10** 
20. Crear las variables **i** y **j** con valor **0**. A continuación crear **un bucle que itere 11 veces usando i como iterador**. En cada iteración se deberá **sumar al valor de j el valor de i al cuadrado**
21. Crear una variable **sumaPares** con valor **0**. A continuación crear un bucle que **itere 10 veces (i < 10)**. Si la iteración es par se deberá **sumar a sumaPares el número de la iteración actual (i)**
22. Crear una variable **contarHasta10for** con valor **0** e incrementar su valor con un **bucle for hasta que se verifique que contarHasta10for == 10**

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