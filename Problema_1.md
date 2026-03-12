# Problema 1: Resultado de un Partido de Baloncesto


---
  
## Solucion

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
