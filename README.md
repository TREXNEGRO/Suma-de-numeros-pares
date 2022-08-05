# Suma-de-numeros-pares

Tarea Funciones: Suma y producto de pares
Límite de entrega: martes, 26 de julio de 2022, 16:00
Ficheros requeridos: sumaproductopares.c (Descargar)
Tipo de trabajo: Individual
Planteamiento

Escribir un programa que reciba del usuario un número entero PAR y que debe estar entre 1 y 100. El programa debe verificar si el número está en el rango y si es PAR.
Si el número ingresado está fuera del rango o no es par, el programa debe volver a pedir el número.
Si el número está dentro del rango y es par, el programa debe calcular
- la suma de los pares que se encuentran entre 1 y el número ingresado; y
- la suma de los primos que se encuentran entre 1 y el número ingresado.

Por ejemplo, si el número ingresado es 10, la suma de los pares entre 1 y 10 es 2+4+6+8+10=30 y la suma de los primos es 2+3+5+7=17

Use las siguientes firmas (prototipos) de funciones para programarlas e implementar su programa:

int leerNumero(); //Para leer el numero ingresado por el usuario
int estaEnRango(int m); //Para verificar si el numero ingresado está dentro del rango y es par
int sumaPares(int m); //Para obtener la suma de los numeros pares entre 1 y m
int esPrimo(int n); //Para verificar si un numero es primo o no
int sumaPrimos(int m); //Para obtener el producto de los numeros primos entre 1 y m
A continuación se incluyen unos ejemplos de salida del programa:

Ejemplo 1 de salida del programa

Ingrese el numero: 10
Suma de pares: 30                                                               
Suma de primos: 17
Ejemplo 2 de salida del programa

Ingrese el numero: 0
Ingrese el numero: 101
Ingrese el numero: 99
Ingrese el numero: 98 
Suma de pares: 2450                                                             
Suma de primos: 1060                                                            

