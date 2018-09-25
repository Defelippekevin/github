##La sentencia
Tal vez el tipo m�s conocido de sentencia sea el if. Por ejemplo:
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
... print('M�s')
...
'Mas'

~~~

## Iteraciones

Se denominar� iteraci�n a aquel conjunto de instrucciones que se encuentran acotadas por un bloque repetivo de acciones indicadas a trav�s de comandos en el lenguaje python. Las instrucciones por excelencia en este lenguaje pertenecen a los bloques for y while. Estos bloques poseen identaci�n para reconocer  el bloque como tal. 



Uso de la instrucci�n for
La instrucci�n for es utilizada para acotar un bloque de sentencias que tendr�n una condici�n a evaluar para permitir la repetici�n de las mismas. Su sint�xis es:
Instrucci�n de inicio del bloque: Se utiliza  la l�nea de c�digo "for variable  in rango_de_variable:". Los dos puntos no se deben omitir son parte de la sint�xis.

Cuerpo del bloque: Corresponde a un conjunto de sentencias que poseen un sangrado porpia del bloque.

Ejemplos:

a) Escribiendo un bloque que calcula la suma de n�mero que van desde 2 hasta 10, asumiendo que el valor inicial de la variable que guarda el resultado es cero.

~~~
resultado = 0
for i in range(2,11):
resultado +=i
   
print("La suma d� " + str(resultado))


~~~

Instrucci�n while:

La instrucci�n while es utilizada para controlar un ciclo repetivo de instrucciones, bajo un sistema de condicional. Su sintaxis es:
L�nea cabecera o de inicio  del bloque: Est� l�nea inicia con la instrucci�n while y debe tener un t�rmino condicional a la par, al final del t�rmino se coloca dos puntos , como " while (condicional):".
Cuerpo del bloque: Son un conjunto de sentencias marcadas por un sangrado que se repiten hasta que la instrucci�n condicional de la cabecera sea falsa.

Ejemplo:

~~~
resultado = 0
i = 2
while (i<11):
resultado +=i
i +=1
   
print("La suma d� " + str(resultado))
~~~
