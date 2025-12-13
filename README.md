# 🧠 ¿Qué es un programa?

Un **programa** es un **conjunto de instrucciones** que una computadora sigue para realizar una tarea o resolver un problema.  
Estas instrucciones se escriben en un **lenguaje de programación**, que la computadora puede entender y ejecutar paso a paso.

## 💻 ¿Qué es un lenguaje de programación?

Un **lenguaje de programación** es una forma de **comunicarse con la computadora**.  
Sirve para **darle instrucciones paso a paso**, decirle **qué hacer** y **cómo hacerlo**, usando palabras y símbolos que la máquina puede entender.
Así como nosotros usamos el español o el inglés para hablar con otras personas, los programadores usan lenguajes como **Python, Java, C++ o JavaScript** para hablar con las computadoras.

**Python** es un **lenguaje de programación** muy popular, fácil de leer y de aprender. 

## 📦 ¿Qué es una variable?

Una **variable** en programación es como una **cajita con nombre** donde se puede **guardar información** para usarla más adelante.  
Esa información puede ser un número, un texto, una lista u otro tipo de dato que necesitemos en el programa.

### 💬 En palabras sencillas

Imagina una variable como una **etiqueta pegada en una caja**.  
Dentro de la caja puedes guardar algo (por ejemplo, un número o una palabra), y después puedes abrirla para **leer o cambiar su contenido**.  

Por eso se llama **variable**, porque su valor puede **variar o cambiar** durante la ejecución del programa.

## ¿que es un valor?

 es la información concreta que un programa almacena y manipula,es decir,es el dato real.
 en programación una *variable* es como la estiqueta o nombre y el *valor*es lo que esta guardado bajo esa etiqueta.
```pytho
 
 a=5
```

a es la variable(la etiqueta)
5 es el valor (el dato que se guarda den la memoria)
el valor siempre tienen un tipo de dato ,que determinan como se guardan y que oeraciones pueden hacersen en ellos.

## 👉¿que es un operador?

un operador es un simbolo que indica una acción.
es como darle una instrucción muy corta:

  + suma
 -  resta
 * multiplicación
 / divide

- = guarda un valor en una variable
 
 - == compara si dos cosas son iguales

hay operadores que en programación no singnifican lo mismo que en matematicas como lo es *=* en programación significa 
guardar un valor en una variable y en matematicas es igual a.

## algunos operadores son:
 ## operadores de comparación
 devuelven true o false:
 
 - == igual
 - == == igual
 - != diferente
 -  > mayor
 - < menor
 - >= mayor o igual
 - <= menor o igual

## ✅  Operadores lógicos#
 Para combinar condiciones:
- and → las dos deben ser ciertas
- or → basta con una
- not → cambia True o False.

## Orden de operaciones

Primero calcula:

- Paréntesis
- Potencias
- Multiplicaciones y divisiones
- Sumas y restas
- Igual que matemáticas.

## Operadores con cadenas

- "texto" + "texto" → une palabras
-"texto" * número → repite el texto
- No se puede restar, dividir, etc.


## Lectura y escritura de valores en variables — Explicación sencilla
 **print(): mostrar cosas en pantalla**
 
print() es como decirle al computador:
➡️ “Muéstrame esto en la pantalla”.

Ejemplo:
```
python
nombre = "Ana"
print("Hola", nombre)

El computador solo imprime lo que le digas.

print(f"Hola, {nombre}")
```
 # input(): pedir datos al usuario

input() sirve para preguntarle algo al usuario y guardar lo que escriba.

➡️ Siempre devuelve texto (string), aunque el usuario escriba números.

## Ejemplo:
```python
nombre=input(¨¿nombre?¨)
```
si necesitas un número tienes que convertirlo:
```python
edad=int(input(¨edad:¨))
```
asi se pueden hacer los cálculos.

## 💡 Ejemplo: 

```python
nombre = "Andrea"
edad = 18
print(f"Hola, me llamo {nombre} y tengo {edad} años.")

👉 Este código crea dos variables: nombre y edad.
Luego usa print() para mostrar un mensaje con esos datos.

x=10
print(x=)
```
print() e input() son ejemplos de funciones, es decir, bloques de código reutilizables que realizan una tarea específica.
Una función puede recibir datos de entrada (llamados parámetros o argumentos) y devolver un resultado o simplemente ejecutar una acción.

# Que es una función?

Una función es un bloque de código que hace una tarea específica.
Sirve para organizar el programa y evitar repetir código.

def saludar():
    print("¡Hola!")


para usarla 

    saludar()

 # la identación

La indentación son los espacios al inicio de las líneas.
En Python es obligatoria porque indica qué instrucciones pertenecen a una función o a un condicional.
# Ejemplo
def ejemplo():
    print("Dentro")
print("Fuera")

## REFLEXIÓN
Es interesante conocer los conceptos básicos de programación y entender como funciona.Esto nos ayuda aclarar muchas dudas y darle sentido a todo el tema de desarrollo de software.poco a poco uno se da cuenta de que detras de cada programa hay una lógica y un proceso que se puede aprender.comprender como se conectan las ideas,las variables y las instruccciones me hace ver que programar no es solo escribir un código si no enteder como piensasn las computadoras.

## Referencias de IA
ChatGPThttps://chatgpt.com/convrsación que es un programa,que es python ejemplos ,variables.

 ## NUEVAS ENTRADAS 
 
En esta entrada se presenta una simulación simple de una tortuga, desarrollada únicamente usando input y print.
La interacción con la tortuga se realiza mediante una interfaz simple con los comandos adelante y abajo, aplicando los conceptos vistos en la Unidad 1.
Se incluye el código en Python y una breve explicación de su funcionamiento.

👉[Repositorio de la Tortuga](https://github.com/nataliaamaya-collab/mi-primera-pagina/tree/main/tortuga)


 ## Evolución de Mini-Turtle 🐢(tarea mini-turtle)

En esta entrada del blog veremos cómo encapsular el comportamiento de una tortuga desarrollada en la Tarea 2.

Primero trabajaremos una encapsulación funcional, organizando el código con funciones y módulos. Luego, evolucionaremos a una encapsulación usando Programación Orientada a Objetos (POO), donde el estado y el comportamiento de la tortuga se agrupan dentro de una clase, permitiendo crear objetos independientes.

Este ejercicio muestra cómo la encapsulación mejora la organización del código.

👉 [Haz clic aquí para ver la versión funcional](https://github.com/nataliaamaya-collab/mini_turtle-)

 👉 [Haz clic aquí para ver la versión orientada a objetos](https://github.com/nataliaamaya-collab/mini_turtle_00_task-)

 
