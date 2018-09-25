##La sentencia
Tal vez el tipo más conocido de sentencia sea el if. Por ejemplo:
~~~
>>> x = int(input("Ingresa un entero, por favor: "))
Ingresa un entero, por favor: 42
>>> if x < 0:
... x = 0
... print('Negativo cambiado a cero')
... elif x == 0:
... print('Cero')
... elif x == 1:
... print('Simple')
... else:
... print('Más')
...
'Mas'

~~~

## Iteraciones

Se denominará iteración a aquel conjunto de instrucciones que se encuentran acotadas por un bloque repetivo de acciones indicadas a través de comandos en el lenguaje python. Las instrucciones por excelencia en este lenguaje pertenecen a los bloques for y while. Estos bloques poseen identación para reconocer  el bloque como tal. 



Uso de la instrucción for
La instrucción for es utilizada para acotar un bloque de sentencias que tendrán una condición a evaluar para permitir la repetición de las mismas. Su sintáxis es:
Instrucción de inicio del bloque: Se utiliza  la línea de código "for variable  in rango_de_variable:". Los dos puntos no se deben omitir son parte de la sintáxis.

Cuerpo del bloque: Corresponde a un conjunto de sentencias que poseen un sangrado porpia del bloque.

Ejemplos:

a) Escribiendo un bloque que calcula la suma de número que van desde 2 hasta 10, asumiendo que el valor inicial de la variable que guarda el resultado es cero.

~~~
resultado = 0
for i in range(2,11):
resultado +=i
   
print("La suma dá " + str(resultado))


~~~

Instrucción while:

La instrucción while es utilizada para controlar un ciclo repetivo de instrucciones, bajo un sistema de condicional. Su sintaxis es:
Línea cabecera o de inicio  del bloque: Está línea inicia con la instrucción while y debe tener un término condicional a la par, al final del término se coloca dos puntos , como " while (condicional):".
Cuerpo del bloque: Son un conjunto de sentencias marcadas por un sangrado que se repiten hasta que la instrucción condicional de la cabecera sea falsa.

Ejemplo:

~~~
resultado = 0
i = 2
while (i<11):
resultado +=i
i +=1
   
print("La suma dá " + str(resultado))
~~~
