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
```python
input("Pulsa Enter para que la tortuga dibuje una figura en angulo")
print("tortuga dibujando L invertida\n")
print("→→→→→")
print("    ↓\n    ↓\n    ↓")
```
Resultado

<img width="507" height="128" alt="Captura de pantalla 2025-11-29 184301" src="https://github.com/user-attachments/assets/e35b5997-22e6-47bc-91c7-d9e7f5e15b77" />

* El programa dibuja una especie de “L” que apunta hacia la derecha y hacia abajo.
* input() hace que el usuario decida cuándo empezar.
* print() muestra las flechas que forman la figura.

  **CUARTO ENUNCIADO**
  
👉Encapsular los comportamientos anteriores usando funciones

Reescribir los retos anteriores creando funciones que representen los movimientos de la tortuga solo con texto.
Usa las siguientes funciones como interfaz:
adelante(n)   # Dibuja el movimiento hacia la derecha (→) por n pasos
abajo(n)      # Dibuja el movimiento hacia abajo (↓) por n pasos
  
Encapsula los comportamientos anteriores usando funciones

Reescribe los retos anteriores creando funciones que representen los movimientos de la tortuga solo con texto.
Usa las siguientes funciones como interfaz:

```python
def adelante(n):
     print("→" * n)
def abajo(n, pos):
    print((" " * pos + "↓\n") * n, end="")  
h = int(input("¿Cuántos pasos hacia la derecha? "))
v = int(input("¿Cuántos pasos hacia abajo? "))
input("Pulsa Enter para dibujar la figura\n")
adelante(h)
abajo(v, h)  
```
Resultado

<img width="318" height="175" alt="Captura de pantalla 2025-11-29 190554" src="https://github.com/user-attachments/assets/6a35c4d9-dfee-46ab-9390-361801e01273" />

* adelante dibuja la línea horizontal →
* abajo dibuja la línea vertical ↓ alineada correctamente
* El usuario puede elegir cuántos pasos quiere en cada dirección
* input() se usa para esperar al usuario antes de empezar a dibujar

  **QUINTO ENUNCIADO**
  
Ajustar las funciones para que la tortuga pueda bajar escalones.
Cada escalón debe conservar la posición horizontal acumulada y dibujar correctamente tanto el tramo horizontal como el vertical.




