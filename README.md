# PROYECTO-DE-FUNDAMENTOS-DE-PROGRAMCI-N

# Qué es Python?
Python es un lenguaje de programación flexible y diseñado para ser fácil de leer. Es un lenguaje orientado por objetos de alto nivel. Gracias a su sintaxis sencilla es un muy buen lenguaje para aprender a programar. Python utiliza módulos y paquetes lo cual fomenta la modularidad y la reutilización de código. Python también es un lenguaje de scripting independiente de plataforma y orientado a objetos, preparado para realizar cualquier tipo de programa, desde aplicaciones Windows a servidores de red o incluso, páginas web. 

# Qué es una variable?
Una variable es un sitio donde guardamos una determinada información texto, números (que después se pueda recuperar) los datos dentro del programa  
```python
variable = 8
```
## Nombrando una variable
```python
variable = 8 
·Una "variable" es donde se guarda toda la información y "=" señala cual es el valor 
```
## Asignando valores a una variable
``` python 
variable = 4
variable = "Hola mundo"
·El valor delantero del "=" es el valor reflejado de la variable 
```
## Operadores básicos
```python
·Suma: +
·Resta: -
·Multiplicación: *
·División: /
·Módulo: %
```
### Suma
```python
·Agregaremos dos operaciones de variables para continuar con la operación 
num1 = 7
num2 = 5
·Agregaremos una variable donde guardaremos la operación 
result = 0
·Acontinuación presentaremos las dos variables seguida por el signo + 
result = (num1 + num2)
result = 12 
·Mostraremos un print para verificar si la operación es la correcta 
print(result)
```
### Resta
```python
·Agregaremos dos operaciones de variables para continuar con la operación
num1 = 7
num2 = 5
·Agregaremos una variable donde guardaremos la operación 
result = 0
·Acontinuación presentaremos las dos variables seguido por el signo -
result = (num1 - num2)
result = 2
·Mostraremos un print para verificar si la operación es la correcta 
print(result)
```
### Multiplicación
```python
·Agregaremos dos operaciones de variables para continuar con la operación
num1 = 7
num2 = 5
·Agregaremos una variable donde guardaremos la operación 
result = 0
·Acontinuación presentaremos las dos variables seguido por el signo *
result = (num1 * num2)
result = 35
·Mostraremos un print para verificar si la operación es la correcta 
print(result)
```
### División
```python
·Agregaremos dos operaciones de variables para continuar con la operación
num1 = 7
num2 = 5
·Agregaremos una variable donde guardaremos la operación 
result = 0
·Acontinuación presentaremos las dos variables seguido por el signo /
result = (num1 / num2)
result = 1,4
·Mostraremos un print para verificar si la operación es la correcta 
print(result)
```
### Módulo
```python
·Agregaremos dos operaciones de variables para continuar con la operación
num1 = 7
num2 = 5
·Agregaremos una variable donde guardaremos la operación 
result = 0
·Acontinuación presentaremos las dos variables seguido por el signo %
result = (num1 % num2)
result = 1,4
·Mostraremos un print para verificar si la operación es la correcta 
print(result)
```
# Tipos de datos en Python

## Integer
Los números enteros son números enteros que no contienen decimales, excepto el cero, estos también puedes ser positivos o negativos. En Python y también existes otros tipos  lenguajes de programación, se denominan tipo int (entero, int) o tipo largo (largo). Existe una diferencia entre ambos es que long ya que este nos permite almacenar números más grandes, por lo que este ocupa una gran cantidad más espacio en el programa, por lo que generalmente solo se recomienda utilizar cuando sea nese se recomienda usarlo solo cuando sea necesario.

ejemplo:

```python
x = 1
y = 35656222554887711
z = -3255522
```
## Float
Este tipo de datos se representa en los lenguajes de programación como números de coma float. Estos tambien pueden ser positivo o negativo como un número entero y también puede contener uno o más decimales. Este tipo de datos corresponde a números reales con parte fraccionaria. Es importante tener en cuenta que el separador decimal en Python es un punto ``. ``no una coma ``,``.

ejemplo:

```python 
x = 1.10
y = 1.0
z = -35.59
```
## String
Los cadenas (o strings) son un tipo de datos compuestos por secuencias de caracteres que representan texto. Estas cadenas de texto son de tipo str y se delimitan mediante el uso de comillas simples o dobles.

ejemplo:

```python
print("Hola mundo")
print('Hola mundo')
```
## Casting en Python
Hacer un cast o casting significa convertir un tipo de dato a otro. Anteriormente hemos visto tipos como los int, string o float. Pues bien, es posible convertir de un tipo a otro.
Conversión implícita: Esta conversión de tipos es realizada automáticamente por Python, prácticamente sin que nos demos cuenta. Aún así, es importante saber lo que pasa por debajo para evitar problemas futuros.

ejemplo:

```python
a = 1   # <class 'int'>
b = 2.3 # <class 'float'>
a = a + b
print(a)       # 3.3
print(type(a)) # <class 'float'>
```
Conversión explícita: Es realizada expresamente por nosotros, como por ejemplo convertir de str a int con str().
```python

ejemplo:

a = 3.5  
print(type(a)) # <class 'float'>  
a = str(a)  
print(type(a)) # <class 'str'>
```
## List
Las listas (o ‘List’) en Python son un tipo de estructuras de datos muy flexible que guardan de forma ordenada un conjunto de datos que no tiene porque ser del mismo tipo. En otros lenguajes de programación una lista equivaldría a un array, aunque Python no exige que los elementos de la lista tenga que ser del mismo tipo (‘int’, ‘float’, ‘chr’, ‘str’, ‘bool’, ‘object’).
```python
lista1 = ["cama", "almohada", "colchón"]
 
    print:("lista1")
```
## Tuple
El tuple o las tuplas son básicamente listas de elementos estática, es decir, que no pueden modificarse (decimos que el tuple es inmutable en Python). para su definicion en lugar de ``[]`` se encierran valores separdos por comas entre paréntesis ``(, , ,)``.

ejemplo:
```python
thistuple = ("apple", "banana", "cherry")  
print(thistuple)
[salida]: [apple, banana, cherry]
```

## Dictionary
Los diccionarios se utilizan para almacenar valores de datos en pares clave:valor.
Un diccionario es una colección ordenada*, modificable y que no admite duplicados.

ejemplo:

```python
my_diccionario1 = {'nombre': 'Jack', 'edad': 26}

    print(mi_diccionario1['nombre'])
    
    print(mi_diccionario.get('edad'))
    
    print(mi_diccionario.get('dirección'))
    
    print(mi_diccionario['dirreción'])
```

# Tomando decisiones
## Sentencia if
Python admite las condiciones lógicas habituales de las matemáticas:

Es igual a: a == b
No es igual a: a != b
Menos que: a < b
Menor o igual que: a <= b
Mayor que: a > b
Mayor o igual que: a >= b

Estas condiciones se pueden usar de varias maneras, más comúnmente en "sentencias if" y bucles.
Una "sentencia if" se escribe utilizando la palabra clave if.

ejemplo:

```python
a = 33  
b = 200  
si b > a:  
    print("b es mayor que a")
```

La palabra clave elif es la forma de Python de decir "si las condiciones anteriores no fueron ciertas, intente esta condición".

ejemplo:
```python
a = 33  
b = 33  
si b > a:  
  print("b es mayor que a")  
elif a == b:  
  print("a y b son iguales")
 ```

## Ciclo For
Los ciclos for son lo que se conoce como estructuras de control de flujo cíclicas o simplemente estructuras cíclicas, estos ciclos, como su nombre lo sugiere, nos permiten ejecutar una o varias líneas de código de forma iterativa, conociendo un valor especifico inicial y otro valor final, además nos permiten determinar el tamaño del paso entre cada "giro" o iteración del ciclo.

ejemplo: 

```python
nums = [4, 78, 9, 84]
for n in nums:
  print(n)
```  
## Ciclo While
Con el bucle while podemos ejecutar un conjunto de declaraciones siempre que una condición sea verdadera.

ejemplo:

```python
i = 1  
while i < 6:  
  print(i)  
  i += 1
```
## Break
En Python, la instrucciónbreak le proporciona la oportunidad de cerrar un bucle cuando se activa una condición externa. Debe poner la instrucción break dentro del bloque de código bajo la instrucción de su bucle, generalmente después de una instrucción if condicional.

ejemplo: 

```python
i = 1  
while i < 6:  
  print(i)  
  if i == 3:  
    break  
  i += 1 
```
## Continue
La instrucción, continue da la opción de omitir la parte de un bucle en la que se activa una condición externa, pero continuar para completar el resto del bucle. Es decir, la iteración actual del bucle se interrumpirá, pero el programa volverá a la parte superior del bucle.

La instrucción, continue se encuentra dentro del bloque de código abajo de la instrucción del bucle, generalmente después de una instrucción if condicional.

Ejemplo:

```python 
numero = 0

for numero in range(10):

    if numero = 5
      continue
       print("numero es" + str(numero))
       print("out of loop")
```
