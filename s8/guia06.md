# Guía 06 - C++ (parte 1)

La siguiente guía debe de realizarla utilizando C++. Además la compilación deberá hacerla utilizando un archivo Makefile
que deberá de construir.

## Easy

1. a) Declara una variable entera llamada "edad" y asígnale el valor 25. Imprime el valor de la variable en la consola. b) Declara una variable de tipo caracter llamada "letra" y asígnale el valor 'A'. Imprime la letra en la consola.
1. Solicitar un caracter y determinar si es mayúscula o minúscula: a) usando isupper, islower, b) sin usar dichas funciones
1. Imprime los números del 1 al 10 utilizando un bucle "for".
1. Imprime los números pares del 1 al 20 utilizando un bucle "while".
1. Imprime los números impares del 10 al 1 utilizando un bucle "do while.
1. Lee un número del usuario e imprime "Par" si es divisible por 2, "Impar" si no lo es.
1. Lee un número del usuario y utiliza un switch para imprimir el día de la semana correspondiente.
1. Declara un array de enteros llamado "numeros" de tamaño 5. Asigna los valores del 1 al 5 a cada posición del array. Imprime los elementos del array en la consola.
1. Lee 5 números enteros del usuario y almacénalos en un array llamado "numeros". Luego, calcula y muestra la suma de los números.
1. Declara una estructura llamada "Persona" con dos miembros: "nombre" (cadena de caracteres) y "edad" (entero). Crea una variable de tipo "Persona" y asígnale valores. Imprime los valores en la consola.
1. Declara una estructura llamada "Punto" con dos miembros: "x" y "y", ambos enteros. Crea una variable de tipo "Punto" y pide al usuario que ingrese los valores de "x" y "y". Imprime los valores en la consola.
1. Declara una variable de tipo "float" llamada "precio" y asígnale el valor 9.99. Imprime el valor de la variable con 2 decimales en la consola.
1. Imprime los números del 10 al 1 en orden descendente utilizando un bucle "for".
1. Calcula la suma de los números del 1 al 100 utilizando un bucle "while". Imprime el resultado.
1. Imprime la tabla de multiplicar del 5 utilizando un bucle "do while".
1. Lee un carácter del usuario y utiliza un switch para determinar si es una vocal (a, e, i, o, u) o una consonante. Usar: tolower para convertir a minúsculas.
1. Lee un número del usuario y utiliza un switch para imprimir el nombre del mes correspondiente.
1. Declara un array de caracteres llamado "palabra" de tamaño 10. Lee una palabra del usuario y almacénala en el array. Imprime la palabra en la consola.
1. Lee 5 números enteros del usuario y almacénalos en un array llamado "numeros". Luego, encuentra el número mayor en el array y muéstralo en la consola.
1. Declara una estructura llamada "Rectangulo" con dos miembros: "largo" y "ancho", ambos enteros. Crea una variable de tipo "Rectangulo" y pide al usuario que ingrese los valores de "largo" y "ancho". Calcula y muestra el área del rectángulo.
1. Utilizando un bucle "do-while", solicita al usuario que adivine un número generado aleatoriamente en un rango entre 1 y 100. Se le debe indicar si el número ingresado está abajo o arriba del número ingresado. Usar: srand(time(0)); int numeroAleatorio = rand() % 100 + 1;
1. Utilizando un bucle "for", imprime los primeros N términos de la secuencia de Fibonacci.
1. Declara una matriz de enteros de tamaño 3x3. Llena la matriz con valores aleatorios entre 1 y 9, y muestra la matriz resultante.
1. Dada la matriz anterior, calcula y muestra la suma de los elementos en la diagonal principal (esquina superior izquierda a esquina inferior derecha)
1. Implementa el juego del ahorcado. El programa define una palabra de forma manual y permite al usuario adivinar letras hasta completar la palabra o perder. 
    - máximo 5 intentos
    - mostrar instrucciones al inicio
    - mostrar la palabra por adivinar usando un guión por cada letra
    - mostrar las letras ingresadas incorrectas
    - no restar intentos permitidos cuando la letra incorrecta ya se ingresó
    - mostrar el mensaje si ganó o perdió al terminar el juego
1. Implementa el juego piedra, papel o tijera.
    - 5 partidas. Enumerarlas.
    - mostrar instrucciones al inicio
    - solicitar "pi", "pa" y "ti", que corresponde con piedra, papel, y tijera
    - el programa genera una opción aleatoria
    - mostrar el mensaje si ganó, perdió o empató en la repetición y en el juego
    - indicar el puntaje: 1 punto si ganó, 0.5 si empató, 0 si perdió

## Medium

1. Implemente un programa que calcule el Indice de Masa Corporal, que capture mediante consola dos valores numéricos que representan la talla (m) y el peso (kg). Utilizar la siguiente fórmula: IMC = peso / (talla)^2
    - Imprimir el nivel de peso según el resultado del IMC, tomar como referencia la siguiente guía:
    - IMC < 18.5 -> Bajo peso
    - IMC >= 18.5, IMC < 25 -> Normal
    - IMC >= 25, IMC < 30 -> Sobrepeso 
    - IMC >= 30 -> Obesidad
2. Ordenar la siguiente lista de valores enteros ascendentemente utilizando el algoritmo de burbuja: [5,12, 20, 32, 1, 8, 15]
3. Utilizar la siguiente estructura:
    - struct Triangulo {
        int base
        int altura
    }
    - Crear un variable tipo Triangulo, ingresar los valores de base y altura mediante consola y calcular el area de la estructura Triángulo.
4. Implementar un bucle que genere un número entero aleatorio hasta que el número generado sea un valor par y múltiplo de 5.
5. Desarrolla un programa que muestre los números primos presentes en un array de números enteros.
6. Escribe un programa que solicite al usuario ingresar un número del 1 al 7 y muestre el día de la semana correspondiente utilizando un switch.
7. Implementa un programa que muestre la tabla de multiplicar de un número ingresado utilizando un bucle while.
8. Crea un programa que almacene la información de un estudiante (nombre, edad y promedio) en una estructura, generar un arreglo de estudiantes e imprimir los datos de aquel que tenga el mayor promedio.
9. Define una estructura "Contacto" con los campos nombre, teléfono y correo electrónico. Crea un arreglo de contactos y busca un contacto por nombre.

## Medium Hard

1. Desarrolla un programa que solicite al usuario ingresar las calificaciones de un grupo de estudiantes. 
El número de estudiantes puede ser definido por el usuario (ingresado por teclado). El programa debe:
    - Almacenar las calificaciones de todos los estudiantes así como su nombre.
    - Calcular la calificación promedio del grupo.
    - Determinar cuántos estudiantes tienen calificaciones por encima del promedio.
    - Imprimir el nombre del estudiante con mayor nota.

2. Implementa un programa que gestione un inventario de productos. Cada producto tiene un nombre, un código y un precio. 
Usa un struct para definir un producto. El programa debe permitir:
    - Implementar un sistema de menús para que el usuario pueda ingresar las opciones a realizar.
    - Ingresar datos de productos.
    - Mostrar el producto con el precio más alto y el más bajo.
    - Imprimir un reporte con la lista de los precios ordenados por precio.

3. Desarrolla un programa que lea las temperaturas mínimas y máximas diarias de una semana (7 días) y determine:
    - La temperatura promedio de la semana.
    - El día con la temperatura más alta y el día con la temperatura más baja.
    - **Tip:** Primero debe calcular la temperatura promedio del día.
