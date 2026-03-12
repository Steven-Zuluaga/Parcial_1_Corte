# Problema 4: Volumen de un Cono

Calcular el **volumen de un cono circular recto**.

---

## Solucion

- Pseudocodigo
  
```
importar matematicas

Leer r 
Leer h 
pi = math.pi

volumen = (pi * (r**2) * h) / 3

Escribir(volumen)

```

- Codigo
  
```python

import math

r = int(input('Radio del conocimiento: '))
h = int(input('Altura del cono: '))
pi = math.pi

volumen = (pi * (r**2) * h) / 3

print(volumen)

```
