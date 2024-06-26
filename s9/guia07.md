# Guía 07 - C++ (parte 2)

La siguiente guía debe de realizarla utilizando C++. Además la compilación deberá hacerla utilizando un archivo Makefile
que deberá de construir.

## Easy

1. Escribir una función que intercambie el valor de dos variables enteras utilizando punteros.
2. Escribir una función que reciba un puntero a un número entero y verifique si es par.
3. Escribir una función que reciba un puntero a un número entero y determine si es positivo, negativo o cero.
4. Escribir una función que reciba un arreglo de enteros y su tamaño, y retorne el valor máximo utilizando punteros.
5. Escribir una función que reciba un puntero a un arreglo de caracteres y lo imprima en reversa. \0 representa null
6. Escribir un programa que: 
   - a) Implemente una funcion que reciba un valor entero "n", lea "n" valores desde el teclado y los retorne en un array. 
   - b) Implemente una funcion que reciba un array (como un puntero a entero), un valor "n" con la longitud e imprima los valores en pantalla.
   - c) La misma función anterior pero recorriendo el arreglo de otra forma.

## B
7. Elabora una función que reciba un puntero a un numero entero, calcule su cuadrado y actualize su valor.
8. Elabora una función que reciba 2 parametros: el puntero de un numero entero y un numero entero. La función debera multiplicar el valor del puntero por el numero ingresado.
9. Elabore una función que intercambie los valores de 2 punteros de strings.
10. Elabora una función que reciba 3 parametros: 2 numeros enteros y el puntero de un entero. Si ambos numeros son pares, deberá sumarlos y guardar el resultado en el puntero. Si ambos son imprates, debera restarlos y guardar el resultado en el puntero. Caso contrario, multiplicar ambos numeros y guardar el resultado en el puntero.
11. Elabora una funcion que reciba 4 parametros: 2 floats (ancho, alto) y 2 punteros de floats. La funcion debera calcular el area y permitro del recantgulo y guardar los resultados en los punteros.

## Medium

12. Realice la implementación de una pila (estructura de datos) de numeros enteros usando nodos. Además deberá implementar 3 metodos:
   - a) push (añade un nuevo elemento a la pila)
   - b) pop (elimina un elemento de la pila)
   - c) mostrarElementos (muestra los elementos de la pila)
13. (1p) Escribir un programa que: 
   - a) Implemente la funcion inputArreglo que reciba un valor entero "m", lea "m" valores desde el teclado y los retorne en un array.
   - b) Implemente la funcion inputMatriz que reciba dos valores enteros "m" y "n", lea "n" valores desde el teclado "m" veces, y los retorne en una matriz.
   - c) Implemente la funcion generateArreglo que reciba un valor entero "m", y genere "m" números aleatorios del 0 al 9 y los retorne en un array.
   - d) Implemente la funcion generateMatriz que reciba dos valores enteros "m" y "n", y genere "m" x "n" valores, y los retorne en una matriz.
   - e) Implemente la función printArreglo que imprima un arreglo
   - f) Implemente la función printMatrix que imprima una matriz
   - g) Imprimir inputArreglo, inputMatriz, generateArreglo, generateMatriz
14. (1p) Escribir un programa que:
   - a) Implemente la funcion sumArreglo que suma los valores de un arreglo
   - b) Implemente la funcion sumMatrix que suma los valores de una matriz
   - c) Implemente la funcion averageArreglo que promedia los valores de un arreglo
   - d) Implemente la funcion averageMatrix que promedia los valores de una matriz
   - c) Usar las funciones generateArreglo y generateMatriz
15. (1p) Escribir un programa que:
   - a) Implemente una función que reciba un puntero a una cadena de caracteres y devuelva la cantidad de vocales que contiene. Usar strlen para obtener el tamaño de la cadena
   - b) Imprimir la cantidad de vocales
   - c) Imprimir la cantidad de caracteres
16. (3p) Escribir un programa que:
   - a) Implemente una función que reciba una matriz de caracteres , y encuentre la cantidad de letras 'A' en la matriz.
   - b) Implemente una función que genere una matriz de caracteres dado su tamaño (filas, columnas). Usar `'A' + rand() % 26;
   - c) Imprimir matriz
   - d) Imprimir la cantidad de vocales
17. (3p) Escribir un programa que:
   - a) Implemente la funcion getNumerosPares que cuente los pares de una matriz
   - b) Implemente la funcion getMaximo que obtenga el número máximo de una matriz
   - c) Implemente la funcion getMínimo que obtenga el número mínimo de una matriz
   - d) Implemente la funcion getRepetidos que cuente la cantidad de repetidos. Un repetido se considera cuando un número aparece 2 o más veces.
   - e) Usar la función generateMatriz
   - f) Imprimir los resultados de cada una de las funciones.
18. (1p) Programar un juego de búsqueda del tesoro, donde:
   - a) el tablero es una matriz de "m" x "n" donde m y n es ingresado por teclado, inicializado con 0 (ceros) que se ve alineada
   - b) el jugador solo tiene 3 intentos para adivinar en qué fila y columna se encuentra un tesoro
   - c) si el usuario adivina correctamente, gana el juego; de lo contrario, pierde al superar los 3 intentos. 
   - d) solo hay un tesoro oculto en el tablero, ubicado aleatoriamente.
   - e) en cada intento se muestra el tablero, el tesoro no se muestra, pero sí los intentos con -1
   - f) si adivina la ubicación se muestra el tesoro con el número 10.
   - g) se muestra ¡Ganaste! si se encontró el tesoro, ¡Perdiste! en caso contrario.
   - h) Al finalizar el juego, mostrar el tablero con el tesoro con número 10
   - i) se requiere las siguientes funciones mínimas: inicializarTablero, colocarTesoro, mostrarTablero
19. (5p) Programar la versión 2 del juego de búsqueda del tesoro, donde
   - a) se solicita al usuario que ingrese la cantidad de tesoros a encontrar.
   - b) si el usuario adivina todos los tesoros, gana el juego; de lo contrario, pierde al superar los 3 intentos. 
   - c) se muestra ¡Ganaste! si se encontró todos los tesoros, ¡Perdiste! en caso contrario.
   - d) Al finalizar el juego, mostrar el tablero con los tesoros con número 10
   - e) se actualizar la función: colocarTesoro por colocarTesoros

## Medium Hard

20. Dada la siguiente lista enlazada: | 1 | -> | 2 | -> | 3 | -> | 4 | -> | 5 |
   - a) Implemente un método que muestre la cantidad de nodos de la lista.
   - b) Implemente un método que reciba dos parámetros, el primero debe ser un nodo nuevo y el segundo la posición de la lista enlazada en la cual se ingresará dicho elemento. Si es que el valor del segundo parámetro es mayor a la longitud de la lista enlazada, imprimir un mensaje de alerta.
   - c) Implemente un método que reciba como parámetro la posición del nodo de la lista enlazada que se eliminará. Si es que el valor del parámetro es mayor o igual a la longitud de la lista enlazada, imprimir un mensaje de alerta.
   
21. Implementar un programa en C++ que invierta el orden de los elementos de una pila. Trabajar con la siguiente pila: | 10 | -> | 1 | -> | 7 | -> | 2 | -> | 5 |

22. Implementar un programa donde se utilice la siguiente lista doblemente enlazada: | 5 | <-> | 10 | <-> | 15 | <-> | 20 | <-> | 25 |. Imprimir la lista en orden inverso.