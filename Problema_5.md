

# Problema 5: Clasificación de Acceso a un Sistema

Una universidad está implementando un **sistema automático de acceso a sus laboratorios de computación**.

Una universidad está implementando un **sistema automático de acceso a sus laboratorios de computación**.

Cada estudiante puede ingresar al laboratorio dependiendo de tres condiciones:

1. **Si es estudiante activo.**
2. **Si tiene reserva de laboratorio.**
3. **Si llegó dentro del horario permitido.**

Las reglas de acceso son las siguientes:

* Si **no es estudiante activo**, el sistema debe **denegar el acceso** inmediatamente.
* Si **es estudiante activo**, entonces:

  * Si **tiene reserva**, se debe verificar el horario.

    * Si **llegó dentro del horario**, se **permite el acceso**.
    * Si **llegó fuera del horario**, el acceso es **denegado por horario**.
  * Si **no tiene reserva**, el acceso es **denegado por falta de reserva**.

El objetivo del programa es **determinar el resultado del intento de acceso al laboratorio**.

---

## Entrada


```
  
- Código

```python



```
