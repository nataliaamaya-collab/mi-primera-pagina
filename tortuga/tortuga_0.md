# 🐢 RECREAR MI PROPIA TORTUGA 🐢

**ENUNCIADO**
💡simula el comportamiento de la tortuga usando Solo "print´" e "input"
este es el codigo usado para este paso.

```python
print("TORTUGA: moviéndose en línea →")
pasos = int(input("¿Cuántos pasos hacia la derecha? "))
print("→" * pasos)
```

Resultado obtenido

<img width="488" height="111" alt="Captura de pantalla 2025-11-29 134959" src="https://github.com/user-attachments/assets/0af836dd-feda-43a6-a7ec-a0aecf1a3902" />

el objetivo es simular el comportamiento de la turtle unicamente utilizando textopor medio de las funciones print() para mostrar mensajes en pantalla y input() para pedir datos al usuario para lograrlo,el programa pregunta cuantos pasos debe avanzar la tortuga y luego muestra ese avance (→)como una forma visual simple del movimieento.

**ENUNCIADO 2**
🤓crear el rastro de una tortuga moviendose hacia abajo usando unicamente  print()e input()

```python
pasos = int(input("¿Cuántos pasos hacia abajo quieres que dé la flecha? "))
print(("↓\n") * pasos)
```
Resultado

<img width="641" height="206" alt="Captura de pantalla 2025-11-29 150938" src="https://github.com/user-attachments/assets/abb2a824-16a1-43a6-af9f-390dd059a7af" />

**Cómo funciona:**
 * input() pide la cantidad de pasos hacia abajo.
* ("↓\n") * pasos genera una cadena con la flecha hacia abajo repetida en líneas separadas.
* print() muestra todas las flechas a la vez.

**TERCER ENUNCIADO**
Ahora la tortuga no solo avanza: también gira.






