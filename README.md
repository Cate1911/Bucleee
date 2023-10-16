# Bucleee
Holaaaa, este repo contiene todo el Reto #8, más, antes de que empieces a leer, quisiera recalcar que no comenté tanto en este repo debido a que la mayoría de comentarios los hago en mi código para que se pueda entender fácilmente (buenas prácticas de esta programadora ;)).
### 1. Imprimir un listado con los números del 1 al 100 cada uno con su respectivo cuadrado.
   Aquí no hubo necesidad de crear una lista, simplemente definí a un elemento i en una colección de enteros entre 1 y 101, sin contar el 101. Después, en base a cada elemento i presente en esa colección, elevé al cuadrado cada uno de los items de la colección. Finalmente, el algoritmo muestra cada número de la colección con su respectivo cuadrado, esto, en sólo 3 líneas de código.

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/fd391f2d-f384-48f1-bf48-8faeee02c10c)

### 2. Imprimir un listado con los números impares desde 1 hasta 999 y seguidamente otro listado con los números pares desde 2 hasta 1000.
   Primero imprimí el mensaje que indicara la lista de números impares, por consiguiente, utilicé el ciclo for con la variable impar en un rango desde 1 hasta 1000 y para que me tomara sólo los números impares, puse el 2 al final, esto, con el objetivo de que me vaya "saltando" de dos en dos desde 1, es decir, de 1 pasa a 3, de 3 a 5 y así sucesivamente.
   Finalmente,m para el caso de los pares, realicé el mismo procedimiento, sólo que partí del número 2 y puse el 1001 como límite para que me tomara el valor de 1000.

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/b10e2a94-dccc-4ef9-aeed-2b5f609fca41)

### 3. Imprimir los números pares en forma descendente hasta 2 que son menores o iguales a un número natural n ≥ 2 dado
   Primero declaré la variable n como un entero y un real, asimismo, inicialicé esta variable según el valor que ingrese el usuario. Luego, use un condicional if para que el programa sólo me admita números naturales, es decir, números mayores que 0 (pero...¿el cero es natural? yo lo tomé como que NO.); así, el algoritmo empezaría con otro condicional (sólo si n es un número natural), el cual, evalúa si n es par o impar según el residuo de la división que n dé entre 2. Si n llega a ser par, no habría problema, de hecho, la lista empezaría desde n, sin embargo, si n llega a ser impar, la lista empezaría desde n-1.
   Cabe aclarar que utilicé el -2 al final del rango debido a que, como en el punto anterior, quiero que me "salte" de 2 en 2, más, como es una lista descendente, me va a saltar para atrás, por eso el -2; la misma lógica pasa con el 1 al final, pues, quiero que me termine en 2 la lista, por eso, incluyo el 1, el cual, si se mira en forma descentente, estaría más adelante que el 2. 

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/1030f53f-d512-4743-8adb-104d4a98abe4)

### 4. Imprimir los números de 1 hasta un número natural n dado, cada uno con su respectivo factorial
Para este punto, imporyé la función factorial, luego, le pedí al usuario que ingresara un número (lo declaré como entero); también imprimí el mensaje utilizando la notación para cadenas f, la cual, en mi opinión, es más sencilla que el string o str, pues, no tengo que andar poniendo tanto símbolo, paréntesis y más y otra vez :/.
Después de la impresión del mensaje, el algoritmo para a una condición que evalúa si el número es un natural (numero>0, aunque, puse n en los comentarios del programa (perdón :(), así, si n es natural, entonces, pasará a un ciclo for en un rango desde 1 hasta numero+1 (pues, quiero que tome el número), de ahí, inicializo el factorial con la función que importé y para que me calcule el factorial de todos los n que se encuentren en ese rango, y finalmente, imprimo una lista de cada número en ese rango con su respectivo factorial, esto, separado por una raya (lo hice con la notación sep=" - ". Cabe mencionar que este algoritmo sólo funciona para números naturales, pues, de lo contrario, el algoritmo le va a decir al usuario que ingrese un número válido.

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/23ccf357-eb8e-4ccc-9aa4-755bfee5df54)

### 5. Calcular el valor de 2 elevado a la potencia n usando ciclos for.
   Aquí declaré la variable n como un entero y un real, asimismo, inicialicé esta variable según el valor que ingrese el usuario. Luego, usé un ciclo for para que me recorriera todos los números en el rango de 1 hasta n (tomando n en cuenta) y para calcular la potencia de 2 elevado a la i inicialicé la variable potencia como la operación de 2^i. Finalmente, imprimí el resultado.

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/c0581f95-bdd2-43ac-b071-2ebebc85ddaa)

### 6. Leer un número natural n, leer otro dato de tipo real x y calcular x^n usando ciclos for. Disclaimer: Trate de no utilizar el operador de potencia (**).
Aquí le pedí al usuario que me diera la base y el exponente de la pontecia, así, yo le daría la potencia, ambos números los declaré como enteros. También declaré una variable "potencia" como un entero y la inicialicé como 1.
Tomé un rango que me tomara todos los números desde 0 hasta n y la potencia, en un ciclo for, será actualizada constantemente por el valor de la base, es decir, la potencia siempre se va a multiplicar por la misma base n veces (rango del ciclo que se recorre con for) y como la potencia es igual a 1 al inicio, "x" o la base siempre se va a multiplicar por el mismo número hasta que llegue a "n" o al exponente el ciclo for. Finalmente, se imprime el resultado, el cual, es la variable potencia.

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/3a2e991e-1e17-4d07-8580-8b65739b767f)

### 7. Diseñe un programa que muestre las tablas de multiplicar del 1 al 9.
      Aquí cree 9 listas para cada una de las tablas de multiplicar, asimismo, para cada tabla de multiplicar, usé el ciclo for, en donde en cada caso tomé valores desde 1 hasta 11(pero sólo me toma hasta el 10), además, en cada caso, definí una variable numero que se irá actualizando a medida que recorra los diferentes valores del rango y se multiplique por el número que corresponde en cada caso de la tabla. También utilicé el comando append para que me añladiera cada iteración a la lista vacía correspondiente. Finalmente, con print, pude imprimir los resultados de las tablas de multiplicar de 1 a 9 multiplicadas por los números del 1 al 10.

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/e2f6bb81-78f4-4075-a304-aba3e4669786)

### 8. Diseñar una función que permita calcular una aproximación de la función exponencial alrededor de 0 para cualquier valor x (real), utilizando los primeros n términos de la serie de Maclaurin. Nota: use math para traer la función exponencial y mostrar la diferencia entre el valor real y la aproximación.
Aquí importé la función exponencial y el factorial (las cules después declaré e inicialicé en la función main), después, definí una función para calcular la aproximación del exponencial y dentro de esta función, declaré e inicialicé la variable suma como 0, la cual, al final de la función es actualizada cuando es el resultado de la suma de la iteración anterior con el nuevo_termino, este último se calculó con un ciclo for en un rango de 0 hasta n+1 (toma n).
Dentro de la función main, declaré e inicialicé las variables, en donde sólo x es el número que se le pide al usuario que ingrese, asimismo, el valor real del exponencial de x se calculó con la función math.exp(x) y el error también se calculó dentro de esta función, este error, a su vez, es la diferencia que hay entre el valor real y la aproximación, sólo que en porcentaje. Finalmente, este algoritmo imprime tanto el valor real del exponencial de x y la aproximación del exponencial, como el %error. Cabe mencionar que puse n como 10 porque es un número "fácil" en términos de sumatoria.

    ![image](https://github.com/Cate1911/Bucleee/assets/141857246/57bf086d-1f43-4fb4-bd0c-63e4b61ed1d4)

### 9. Diseñar una función que permita calcular una aproximación de la función seno alrededor de 0 para cualquier valor x (real), utilizando los primeros n términos de la serie de Maclaurin. Nota: use math para traer la función seno y mostrar la diferencia entre el valor real y la aproximación.
Aquí importé la función seno y el factorial (las cules después declaré e inicialicé en la función main dentro del bucle while), después, definí una función para calcular la aproximación del seno de x y dentro de esta función, declaré e inicialicé la variable suma como 0, la cual, al final de la función es actualizada cuando es el resultado de la suma de la iteración anterior con el termino_final_a_sumar, este último se calculó con un ciclo for en un rango de 0 hasta n+1 (toma n) y a partir de 2 variables más, una que me calculaba sólo el denominador sin factorial y otra que me calculaba toda la fracción. El termino_final_a_sumar se calculó a partir de multiplicar el resultado del termino_inicial_a_sumar (toda la fracción) y (-1)^i
Dentro de la función main, declaré e inicialicé las variables, en donde sólo x es el número que se le pide al usuario que ingrese, asimismo, el valor real del seno de x se calculó con la función math.sin(x) y el error también se calculó dentro de esta función, este error, a su vez, es la diferencia que hay entre el valor real y la aproximación, sólo que en porcentaje. Finalmente, este algoritmo imprime tanto el valor real del seno de x y la aproximación del seno, como el %error. Cabe mencionar que puse n como 1 porque así pude usarlo en un ciclo while para que se pudiera actualizar en el caso de que me dé un error mayor que 0.1, esto hace que el algoritmo sea más preciso.

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/c7ea0dde-b8bc-4a25-ad06-43e3a101c115)

### 10. Diseñar una función que permita calcular una aproximación de la función arcotangente alrededor de 0 para cualquier valor x en el rango [-1, 1], utilizando los primeros n términos de la serie de Maclaurin. Nota: use math para traer la función arctan y mostrar la diferencia entre el valor real y la aproximación.
   En este punto realicé el mismo procedimiento que en el punto 9, sólo que en el denominador de la fracción, no utilicé un factorial; además, aquí calculé el arco tangente de x sólo si x estaba en el rango de [-1,1], sino, el programa le dirá al usuario que ingrese un número válido

   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/d1a380d8-dcbb-4eaa-8855-f58cfb419660)

### ¡MUCHAS GRACIAS POR VER MI REPO, T.Q.M. Y PORFA DALE UNA ESTRELLITA SI TE SIRVIÓ DE GUÍA O TE GUSTÓ!

**_Nota: este reto me costó mucho, creo que terminé muy similar al gatito de abajo :(._**
  
   ![image](https://github.com/Cate1911/Bucleee/assets/141857246/f3a641e6-08fb-470f-81bb-029428ddacd6)
