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
print("TORTUGA: moviéndose hacia abajo ↓")
pasos = int(input("¿Cuántos pasos hacia abajo? "))
print(("↓\n") * pasos)
```
Resultado

<img width="279" height="121" alt="image" src="https://github.com/user-attachments/assets/62eb2320-6743-4925-a1c6-aaf93eae25dc" />

**Cómo funciona:**
 * input() pide la cantidad de pasos hacia abajo.
* ("↓\n") * pasos genera una cadena con la flecha hacia abajo repetida en líneas separadas.
* print() muestra todas las flechas a la vez.

**TERCER ENUNCIADO**

Ahora la tortuga no solo avanza: también gira.

```python
print("TORTUGA: dibujando una L\n")
h = int(input("¿Pasos hacia la derecha? "))
v = int(input("¿Pasos hacia abajo? "))
# Línea horizontal
print("→" * h)
# Línea vertical alineada
print((" " * h + "↓\n") * v, end="")
```

Resultado

<img width="268" height="175" alt="image" src="https://github.com/user-attachments/assets/3396a2d8-69e0-4132-a58e-183fc88f2163" />

* Se pide al usuario cuántos pasos hacia la derecha (h) y hacia abajo (v).
* "→" * h dibuja la línea horizontal.
* (" " * h + "↓\n") * v dibuja la vertical alineada al final de la horizontal.

💡 Simula que la “tortuga” dibuja una letra "L" en la consola usando solo texto


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
pos = 0  # posición horizontal global
def adelante(n):
    global pos
    print("→" * n)
    pos += n
def abajo(n):
    global pos
    print((" " * pos + "↓\n") * n, end="")
print("Tortuga dibujando una L con funciones\n")
h = int(input("¿Pasos hacia la derecha? "))
v = int(input("¿Pasos hacia abajo? "))
adelante(h)
abajo(v)
```
Resultado

<img width="279" height="174" alt="image" src="https://github.com/user-attachments/assets/ff2bfc73-627b-4419-aa22-675a0227b5a3" />

* adelante(n) dibuja la línea horizontal y actualiza la posición.
* abajo(n) dibuja la línea vertical alineada con la horizontal.
* h y v se piden al usuario y determinan el tamaño de la “L”.

💡 Simula que la tortuga dibuja una letra "L" en la consola usando funciones y texto.


 🧑‍💻 **QUINTO ENUNCIADO**
  
Ajustar las funciones para que la tortuga pueda bajar escalones.
Cada escalón debe conservar la posición horizontal acumulada y dibujar correctamente tanto el tramo horizontal como el vertical.
Aquí hacemos que la tortuga dibuje escalones, como una escalera que avanza hacia la derecha y luego baja.

Cada escalón tiene:

* Un tramo horizontal (----->)
* Un giro hacia abajo (|, v)
* Y se repite varias veces


```python
  pos = 0  # posición horizontal global
def adelante(n):
    global pos
    print(" " * pos + "-" * n + ">")
    pos += n
def abajo(n):
    global pos
    for i in range(n - 1):
        print(" " * pos + "|")
    print(" " * pos + "v")

print("TORTUGA BAJANDO ESCALONES\n")
escalones = int(input("¿Cuántos escalones? "))
h = int(input("¿Pasos hacia la derecha por escalón? "))
v = int(input("¿Pasos hacia abajo por escalón? "))
for i in range(escalones):
    adelante(h)
    abajo(v)
```

💡 Resultado


<img width="327" height="261" alt="Captura de pantalla 2025-11-30 180623" src="https://github.com/user-attachments/assets/882a3d9c-7282-42d3-b194-a9856c621212" />


* adelante(n) dibuja la parte horizontal de un escalón (- y >).
* abajo(n) dibuja la parte vertical (| y v).
* El bucle for repite esto tantas veces como escalones pida el usuario.
* pos mantiene la posición horizontal para alinear correctamente los escalones.

💡 Simula que una “tortuga” baja escalones en la consola usando texto.

**Referencias de IA** 

ChatGPT: conversación sobre temas variables,funciones,sus usos,ejemplos.
