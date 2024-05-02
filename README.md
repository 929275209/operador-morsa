## OPERADOR MORSA
El operador se representa mediante dos puntos seguidos de un signo igual (:=). Su principal función es permitir la asignación de valores a variable dentro de una expresión, al mismo tiempo que se evalúa esta.

antes de la aparición del operador morsa se debía hacer en varias líneas.
>EJEMPLO:
```python
suma = a + b

if suma > 100:
    print(f'La suma es {suma}')
```
Una operación que se puede simplificar mucho con esta operación.
>ejemplo:
```python
if (suma:= a + b) > 100:
    print(f'La suma es {suma}')
```