# Problema 1: Resultado de un Partido de Baloncesto

En el baloncesto existen tres tipos de jugadas que otorgan puntos:

- Un **tiro de tres puntos**, que vale **3 puntos**.
- Un **tiro de dos puntos**, que vale **2 puntos**.
- Un **tiro libre**, que vale **1 punto**.

Usted acaba de observar un partido de baloncesto entre los equipos **Apples** y **Bananas**, y registró el número de jugadas exitosas de cada tipo para ambos equipos.

Su tarea consiste en **determinar el resultado del partido**: si el equipo **Apples ganó**, si **Bananas ganó**, o si el partido terminó **empatado**.

---

## Entrada

El programa recibe **seis líneas de entrada**.

Las **primeras tres líneas** corresponden al equipo **Apples**, y las **últimas tres líneas** corresponden al equipo **Bananas**.

1. La **primera línea** contiene el número de **tiros de tres puntos** exitosos del equipo **Apples**.
2. La **segunda línea** contiene el número de **tiros de dos puntos** exitosos del equipo **Apples**.
3. La **tercera línea** contiene el número de **tiros libres** exitosos (de un punto) del equipo **Apples**.

4. La **cuarta línea** contiene el número de **tiros de tres puntos** exitosos del equipo **Bananas**.
5. La **quinta línea** contiene el número de **tiros de dos puntos** exitosos del equipo **Bananas**.
6. La **sexta línea** contiene el número de **tiros libres** exitosos (de un punto) del equipo **Bananas**.

Cada valor de entrada es un **número entero entre 0 y 100**.

---

## Salida

El programa debe imprimir **un único carácter**:

- **A** si el equipo **Apples** obtuvo más puntos que **Bananas**.
- **B** si el equipo **Bananas** obtuvo más puntos que **Apples**.
- **T** si ambos equipos obtuvieron **la misma cantidad de puntos**.

---

  
- Solucion

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
