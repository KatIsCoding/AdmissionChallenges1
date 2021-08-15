# Prueba de admision para start-up
Bienvenido a la prueba de admision para mi start-up, si recibiste el enlace en el que esta situado este repositorio es porque te inscribiste a participar en proyecto del cual te hablé y accediste a una breve descripcion de las condiciones, sin embargo, una vez terminada la prueba y ser admitido se te preguntará por segunda vez si aceptas los terminos y condiciones mediante la firma de un contrato del cual tendras acceso una vez seas admitido. _(En caso de no tener la mayoria de edad y ademas ser admitido, por favor hazmelo saber una vez estes seguro que estas admitido)_

[Discord]Snow!!#8384

_Nota: Cualquier duda acerca de algun problema será ignorada, haz lo que creas que es la respuesta correcta para cada uno de los desafios._

## Indicaciones

1. Crea un nuevo archivo para cada uno de los desafios, el archivo debe contener el mismo nombre que el desafio
2. Tomate el tiempo para pensar la mejor respuesta posible.
3. Desarrolla tu solucion en una estructura funcional (Programacion funcional).
4. Una vez termines todos los desafios, empaquetalos con cualquier herramienta (rar, 7zip, tar) y enviamelos por Discord, en los proximos dias estaras recibiendo tus resultados

## Desafios

### **FizzBuzz**
```diff
Lenguaje de programacion: 
+ Cualquiera
Dificultad:
+ Facil
```
> El proposito de este desafio es comprobar que tanto conocimiento tiene en el lenguaje que elija

Cree una funcion que cuente de 1 hasta 100, si el numero es divisible entre 3, imprima "Fizz", si el numero es divisible entre 5, imprima "Buzz" y si es divisible entre ambos escriba "FizzBuzz", si no es divisible entre ninguno de los dos, imprima el numero en su lugar
Ejemplo:
```
1
2
Fizz
4
Buzz
Fizz
...
```

### **Que hora es?**
```diff
Lenguaje de programacion:
+ Cualquiera
Dificultad:
! Medio
```

Cree una funcion que envie una peticion HTTP al siguiente servidor: http://worldtimeapi.org/, tiene que solicitar la informacion del tiempo de Costa Rica e imprimir la siguiente informacion: 
```
Dia de la semana
Dia del año
Numero de semana
Tiempo en formato UTC
```
> Como extra, transforme la informacion en un objeto tipo tiempo

## **Sumatoria de series N**
```diff
Lenguaje de programacion:
! Javascript o C/C++
Dificultad:
! Medio
```

Existe una sequencia cuyo elemento N es:

T<sub>n</sub> = n<sup>2</sup> - (n - 1)<sup>2</sup>

Evalue la serie:

S<sub>n</sub> = T<sub>1</sub> + T<sub>2</sub> + T<sub>3</sub> + ... + T<sub>n</sub>

Ejemplo:

n = 3

1<sup>2</sup> - 0<sup>2</sup> + 2<sup>2</sup> - 1<sup>2</sup> + 3<sup>2</sup> - 2<sup>2</sup> = 1 + 3 + 5 = 9 

Cree una funcion capaz de evaluar la serie cuando se le introduce un numero "n" como argumento y devuelva el resultado S<sub>n</sub>

## **Luces**
```diff
Lenguaje de Programacion:
! Python
Dificultad:
+ Facil
```
Cree una funcion que reciba como argumento un numero N y que calcule en cuantos ordenes diferentes N luces pueden estar encendidas.__Excluya el caso en el que ambas estan apagadas__
Ejemplo:
```diff
N = 2
Resultado: 3
Explicacion:
+ -*, *-, **
Para 2 bombillas solo hay 3 posibles casos en las que almenos una bombilla esta encendida
```

## **BinarySearch**
```diff
Lenguaje de Programacion:
+ Cualquiera
Dificultad:
+ Facil
```
Cree una funcion que reciba como argumento una lista o vector conformada por enteros, la funcion tendra que ordenar la lista y devolver en que indice esta el numero solicitado. Ejemplo:
```
Lista: [3,5,1,9,0]
Numero a Buscar: 5

Lista Ordenada: [0,1,3,5,9]
Resultado: 3
```

## **Cifrado Caesar**
```diff
Lenguaje de Programacion:
+ Cualquiera (Preferiblemente JavaScript)
Dificultad:
+ Facil
```

Cree una funcion que reciba un "mensaje" y un indice de rotacion "k" y devuelva el "mensaje" cifrado.

## **Cuadrado magico**
```diff
Lenguaje de Programacion:
+ Cualquiera
Dificultad:
! Medio
```

Cree una funcion que reciba como argumento un numero "n", y devuelva en forma de matriz un cuadrado magico con numeros aleatorios de tamaño n*n

# **Opcionales**
> Si logras resolver cualquiera de estos problemas, tendras muchas mas posibilidades de ser aceptado.

## **Communication!!**
```diff
Lenguaje de programacion:
! Python, Javascript o Golang
Dificultad:
- Dificil
```

Create a simple peer-to-peer communication system (No encription needed) using sockets or websockets. Both clients should be able to see the other's message, as well as sending messages. This implies the creation of a server, if you create an actual remote server would be impressive, but I know it is not always for free, so you can make it work as a local server

## **Matrix rotation**
```diff
Lenguaje de programacion:
- C++
Dificultad:
- Muy dificil
```
Implement an algorithm which rotates a matrix "m", by a factor "k"

```diff
m =
1  2  3  4
5  6  7  8
9 10 11 12
13 14 15 16

k = 2

Result:
  1  2  3  4      2  3  4  8      3  4  8 12
  5  6  7  8      1  7 11 12      2 11 10 16
  9 10 11 12  ->  5  6 10 16  ->  1  7  6 15
 13 14 15 16      9 13 14 15      5  9 13 14
```
