# Exp_Fac_Data_Scientist

El código comienza con la creación de una función que solicita al usuario un número. Este número es validado para asegurarse de que sea un entero positivo. Si no se cumple esta condición, un mecanismo de control de errores muestra un mensaje de error y termina el proceso, evitando así posibles futuros errores.

Una vez definida la función de validación y obtención segura del número, se procede a utilizar esta función para asegurar que el número ingresado es correcto. Luego, se emplea un bucle `while` para evaluar si el número introducido puede ser expresado como \(2^k\), donde \(k\) es un entero positivo. El bucle realiza una búsqueda iterativa de \(k\) que satisface la ecuación \(n = 2^k\).

Para validar la funcionalidad del código, se ejecutan varias pruebas que comprueban la veracidad y robustez de la función.

Adicionalmente, se desarrolla una segunda función destinada a calcular el factorial de un número dado. En este caso, se presta especial atención al tratamiento del número 0, ya que el sistema debe reconocer que el factorial de 0 es 1. En esta función se utiliza un bucle `for`, aprovechando que se conoce el número máximo a evaluar.

Se realizaron pruebas exhaustivas en las que se introdujeron números no enteros, confirmando la robustez de la función y su capacidad para manejar entradas no válidas de manera adecuada.

En resumen, el código está diseñado para manejar la entrada de números enteros positivos, buscar exponentes específicos utilizando un bucle `while` y calcular factoriales con un bucle `for`, asegurando robustez y manejo adecuado de errores a lo largo de todo el proceso.
