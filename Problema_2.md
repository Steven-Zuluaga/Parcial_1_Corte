# Problema 2: Llamada de Telemercadeo

## Descripción

En este problema asumiremos que los **números telefónicos tienen cuatro dígitos**.

Un número telefónico **pertenece a un telemercader (telemarketer)** si sus cuatro dígitos cumplen **todas** las siguientes condiciones:

* El **primer dígito** es **8 o 9**.
* El **cuarto dígito** es **8 o 9**.
* El **segundo y tercer dígito** son **iguales**.

Por ejemplo, el número **8119** pertenece a un telemercader porque:

* El primer dígito es **8**.
* El cuarto dígito es **9**.
* El segundo y tercer dígito son **iguales (1 y 1)**.

Su tarea es **determinar si un número telefónico pertenece a un telemercader** y decidir si **debemos contestar la llamada o ignorarla**.

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
FinSi

```


- Codigo

```python

d_1 = int(input('primer dígito: ')) 
d_2 = int(input('segundo dígito: ')) 
d_3 = int(input('tercer dígito: ')) 
d_4 = int(input('cuarto dígito: ')) 

if (d_1 == 8 or d_1 == 9) and (d_4 == 8 or d_4 == 9) and (d_2 == d_3):
  print('ignore')

else:
  print('answer')

```
