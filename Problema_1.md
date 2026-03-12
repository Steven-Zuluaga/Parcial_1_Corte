# Problema 1: Resultado de un Partido de Baloncesto

En el baloncesto existen tres tipos de jugadas que otorgan puntos:

Un tiro de tres puntos , que vale 3 puntos .
Un tiro de dos puntos , que vale 2 puntos .
Un tiro libre , que vale 1 punto .
Usted acaba de observar un partido de baloncesto entre los equipos Apples y Bananas , y registró el número de jugadas exitosas de cada tipo para ambos equipos.

Su tarea consiste en determinar el resultado del partido : si el equipo Apples ganó , si Bananas ganó , o si el partido terminó empatado .

---
  
## Solucion

- Pseudocodigo
  
```
Leer d_1 
Leer d_2 
Leer d_3 
Leer d_4 

Si (d_1 == 8 o d_1 == 9) y (d_4 == 8 o d_4 == 9) y (d_2 == d_3) Entonces
  Escribir 'ignore'

Sino Entonces
  Escribir 'answer'

```
- Codigo

```python

a_3 = int(input('tiros de 3 puntos exitosos Apples: '))
a_2 = int(input('tiros de 2 puntos exitosos Apples: '))
a_1 = int(input('tiros libres exitosos Apples: '))

b_3 = int(input('tiros de 3 puntos exitosos Bananas: '))
b_2 = int(input('tiros de 2 puntos exitosos Bananas: '))
b_1 = int(input('tiros libres exitosos Bananas: '))

apples = (a_3 * 3) + (a_2 * 2) + (a_1)
bananas = (b_3 * 3) + (b_2 * 2) + (b_1)

if apples > bananas:
  print('A')

elif bananas > apples:
  print('B')

else:
  print('T')

```
