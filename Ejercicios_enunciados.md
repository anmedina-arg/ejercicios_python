# EJERCICIOS PYTHON

En este archivo vamos a encontrar varios ejercicios para resolver, practicar e ir aprendiendo python!

Vamos a ir desde los más fáciles a los más difíciles... Comencemos!

## Ejercicios sobre: Variables (Basic)

1. Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla
2. Imprimir el tipo de dato de la constante 8.5
3. Imprimir el tipo de dato de la variable creada en el punto 1
4. Crear una variable que contenga tu nombre
5. Mostrar el tipo de dato de la variable crada en el punto 4
6. Crear una variable que contenga el valor del número Pi redondeado a 4 decimales
7. Crear una variable que contenga el valor 'True' y otra que contenga el valor True. ¿Se trata de lo mismo?
8. Imprimir el tipo de dato correspondientes a las variables creadas en el punto 7
9. Asignar a una variable, la suma de un número entero y otro decimal
10. Realizar una operación de suma de números complejos
11. Realizar una operación de multiplicación
12. Mostrar el resultado de elevar 2 a la octava potencia
13. Obtener el cociente de la división de 27 entre 4 en una variable y luego mostrarla
14. De la división anterior solamente mostrar la parte entera
15. De la división de 27 entre 4 mostrar solamente el resto
16. Utilizando como operandos el número 4 y los resultados obtenidos en los puntos 14 y 15. Obtener 27 como resultado
17. Utilizar el operador "+" en una operación donde intervengan solo variables alfanuméricas
18. Evaluar si "2" es igual a 2. ¿Por qué ocurre eso?
19. Utilizar las funciones de cambio de tipo de dato, para que la validación del punto 18 resulte verdadera
20. ¿Por qué arroja error el siguiente cambio de tipo de datos? a = float('3,8')
21. Crear una variable con el valor 3, y utilizar el operador '-=' para modificar su contenido y que de como resultado 2.
22. Realizar la operación 2 + '2' ¿Por qué no está permitido? ¿Si los dos operandos serían del mismo tipo, siempre arrojaría el mismo resultado?
23. Realizar una operación válida entre valores de tipo entero y string

## Ejercicios sobre: Flujos de Control

24. Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla si es mayor o menor a cero
25. Crear dos variables y un condicional que informe si son del mismo tipo de dato
26. Para los valores enteros del 1 al 20, imprimir por pantalla si es par o impar
27. En un ciclo for mostrar para los valores entre 0 y 5 el resultado de elevarlo a la potencia igual a 3
28. Crear una variable que contenga un número entero y realizar un ciclo for la misma cantidad de ciclos
29. Utilizar un ciclo while para realizar el factorial de un número guardado en una variable, sólo si la variable contiene un número entero mayor a 0
30. Crear un ciclo for dentro de un ciclo while
31. Crear un ciclo while dentro de un ciclo for
32. Imprimir los números primos existentes entre 0 y 30
33. ¿Se puede mejorar el proceso del punto 32? Utilizar las sentencias break y/ó continue para tal fin
34. Aplicando continue, armar un ciclo while que solo imprima los valores divisibles por 12, dentro del rango de números de 100 a 300
35. Crear un ciclo while que encuentre dentro del rango de 100 a 300 el primer número divisible por 3 y además múltiplo de 6

## Ejercicios sobre: Estructuras de datos

36. Crear una lista que contenga nombres de ciudades del mundo que contenga más de 5 elementos e imprimir por pantalla
37. Imprimir por pantalla el segundo elemento de la lista
38. Imprimir por pantalla del segundo al cuarto elemento
39. Visualizar el tipo de dato de la lista
40. Visualizar todos los elementos de la lista a partir del tercero de manera genérica, es decir, sin explicitar la posición del último elemento
41. Visualizar los primeros 4 elementos de la lista
42. Agregar dos ciudades más a la lista, una que ya exista y otra que no ¿Arroja algún tipo de error?
43. Agregar otra ciudad, pero en la cuarta posición
44. Concatenar otra lista a la ya creada
45. Encontrar el índice de la ciudad que en el punto 42 agregamos duplicada. ¿Se nota alguna particularidad?
46. ¿Qué pasa si se busca un elemento que no existe?
47. Eliminar un elemento de la lista
48. ¿Qué pasa si el elemento a eliminar no existe?
49. Extraer el úlimo elemento de la lista, guardarlo en una variable e imprimirlo
50. Mostrar la lista multiplicada por 4 (operaciones con listas)
51. Crear una tupla que contenga los números enteros del 1 al 20
52. Imprimir desde el índice 10 al 15 de la tupla
53. Evaluar si los números 20 y 30 están dentro de la tupla
54. Con la lista creada en el punto 36, validar la existencia del elemento 'Persia' y si no existe, agregarlo. Utilizar una variable e informar lo sucedido. Trata de ejecutar el codigo nuevamente. Se agrega de nuevo la ciudad?
55. Mostrar la cantidad de veces que se encuentra un elemento específico dentro de la tupla y de la lista
56. Convertir la tupla en una lista
57. Desempaquetar solo los primeros 3 elementos de la tupla en 3 variables
58. Crear un diccionario utilizando la lista crada en el punto 1, asignandole la clave "ciudad". Agregar tambien otras claves, como puede ser "Pais" y "Continente".
59. Imprimir las claves del diccionario
60. Imprimir las ciudades a través de su clave

## Ejercicios sobre: Iteradores e iterables

61. A partir de una lista vacía, utilizar un ciclo while para cargar allí números negativos del -15 al -1
62. ¿Con un ciclo while sería posible recorrer la lista para imprimir sólo los números pares?
63. Resolver el punto anterior sin utilizar un ciclo while
64. Utilizar el iterable para recorrer sólo los primeros 3 elementos
65. Utilizar la función **enumerate** para obtener dentro del iterable, tambien el índice al que corresponde el elemento.
66. Dada la siguiente lista de números enteros entre 1 y 20, crear un ciclo donde se completen los valores faltantes: lista = [1,2,5,7,8,10,13,14,15,17,20]
67. La sucesión de Fibonacci es un listado de números que sigue la fórmula: <br>
    n<sub>0</sub> = 0<br>
    n<sub>1</sub> = 1<br>
    n<sub>i</sub> = n<sub>i-1</sub> + n<sub>i-2</sub><br>
    Crear una lista con los primeros treinta números de la sucesión.<br>
68. Realizar la suma de todos elementos de la lista del punto anterior
69. A partir de la variable cadena ya dada, mostrar en qué posiciones aparece la letra "n"<br>
    cadena = 'Hola Mundo. Esto es una practica del lenguaje de programación Python'
70. Crear un diccionario e imprimir sus claves utilizando un iterador
71. Convertir en una lista la variable "cadena" del punto 69 y luego recorrerla con un iterador

### Funcion <b>zip</b></br>

Esta funcion se utiliza para combinar elementos de una o más secuencias (como listas o tuplas) en una secuencia de tuplas. Cada tupla resultante contiene elementos de las secuencias originales, emparejados según su posición en esas secuencias. En otras palabras, zip() toma elementos de la misma posición de múltiples secuencias y los agrupa en una tupla.</br>

A menudo se convierte el resultado de zip() en una lista es porque zip() en sí mismo devuelve un objeto zip, que es un iterador. Este objeto zip es eficiente en términos de uso de memoria ya que no crea una nueva lista para almacenar los elementos combinados, sino que genera las combinaciones a medida que se solicitan. Esto puede ser beneficioso en situaciones en las que estás trabajando con grandes conjuntos de datos, ya que evita la necesidad de crear una nueva lista que consuma más memoria.</br>

72. Crear dos listas y unirlas en una tupla utilizando la función zip

### Comprension de listas</br>

Es un concepto fundamental en Python. Se refiere a una técnica que permite crear nuevas listas (u otras secuencias) a partir de secuencias existentes, de manera concisa y legible. Las comprensiones de lista son una característica poderosa y elegante del lenguaje Python que facilita la creación y manipulación de listas.</br>
La sintaxis básica de una comprensión de lista es la siguiente:</br>
nueva_lista = [expresion for elemento in secuencia if condicion]</br>
donde:</br>
</br>
a. <b>nueva_lista</b>: La lista resultante que se crea a partir de la comprensión.</br>
b. <b>expresion</b>: Una expresión que se evalúa para cada elemento de la secuencia.</br>
c. <b>elemento</b>: La variable que representa cada elemento de la secuencia.</br>
d. <b>secuencia</b>: La secuencia (por ejemplo, una lista, tupla o rango) de la cual se toman los elementos.</br>
e. <b>condicion (opcional)</b>: Una condición que filtra los elementos de la secuencia antes de que se incluyan en la nueva lista.</br>
</br>
La comprensión de lista itera a través de la secuencia original, aplica la expresión a cada elemento y, si la condición es True, agrega el resultado a la nueva lista. Esto permite crear nuevas listas de manera eficiente y legible.</br>

73. A partir de la siguiente lista de números, crear una nueva sólo si el número es divisible por 7<br>
    lis = [18,21,29,32,35,42,56,60,63,71,84,90,91,100]
74. A partir de la lista de a continuación, contar la cantidad total de elementos que contiene, teniendo en cuenta que un elemento de la lista podría ser otra lista:<br>
    lis = [[1,2,3,4],'rojo','verde',[True,False,False],['uno','dos','tres']]
75. Tomar la lista del punto anterior y convertir cada elemento en una lista si no lo es

## Problems

1. You will build a program that takes a value, integer , and returns a list of its multiples up to another value, limit . If limit is a multiple of integer, it should be included as well. There will only ever be positive integers passed into the function, not consisting of 0. The limit will always be higher than the base. For example, if the parameters passed are (2, 6), the function should return [2, 4, 6] as 2, 4, and 6 are the multiples of 2 up to 6.
