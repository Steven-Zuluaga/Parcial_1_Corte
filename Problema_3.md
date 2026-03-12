# Problema 3: Conteo de Palabras

Debes **contar el número de palabras** que aparecen en una línea de texto.

Para este problema, una **palabra** se define como **cualquier secuencia de letras minúsculas**.

Por ejemplo:

- `hello` es una palabra.
- También se consideran válidas secuencias como `bbaabbb`, aunque no sean palabras del inglés.

---
  
## Solucion 

```python

palabra = str(input())

palabra = palabra.strip()

contar = palabra.count(' ') + 1

print(contar)

```
