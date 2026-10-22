# Proyecto Python - Katas de Python

Resolución de 40 ejercicios de programación en Python

Maria Montlló

## Descripción

Este proyecto forma parte del curso de Python y consiste en resolver una colección de katas que cubren los principales conceptos del lenguaje. El objetivo es demostrar el manejo de estructuras, funciones y paradigmas fundamentales de Python, desde tipos de datos básicos hasta programación orientada a objetos.

## Estructura del Proyecto

```
proyecto_python/
├── katas_python.py    # Archivo con los 40 ejercicios resueltos
├── README.md          # Este archivo
```

## Herramientas utilizadas

- Python 3
- Jupyter Notebook

## Pasos seguidos

1. Leí los enunciados de cada kata y los analicé antes de empezar
2. Resolví los ejercicios de forma progresiva, organizados por temática:
   - Tipos de datos básicos y funciones incorporadas
   - Estructuras de datos (listas, tuplas, diccionarios) y sus métodos
   - Condicionales y estructuras de control de flujo
   - Funciones de orden superior: `map()`, `filter()` y `reduce()`
   - Funciones lambda y recursividad
   - Manejo de excepciones y errores personalizados
   - Clases y programación orientada a objetos
   - Uso de módulos (`math`, `functools`)
3. Añadí comentarios explicativos en los pasos que me costaron más para documentar el razonamiento

## Lo que más me costó

**`map()` y `filter()` con lambda**
Al principio me costaron bastante porque estaba acostumbrada a usar bucles `for` y no entendía muy bien para qué servía `lambda`. Me liaba con los paréntesis y con los argumentos que tenía que poner en cada función. Poco a poco, cuando entendí que `lambda` permite escribir una función sencilla en una sola línea, empecé a entenderlo mejor y a sentirme más cómoda usándolo.

**Recursividad**
El ejercicio del factorial fue uno de los que más me hizo pensar. Al principio me costaba entender cómo una función podía llamarse a sí misma y, sobre todo, cómo sabía cuándo tenía que parar. Cuando entendí que el `if n == 1: return 1` era la condición que hacía que la función dejara de llamarse, todo empezó a tener más sentido. Aun así, tuve que repasar el ejemplo paso a paso para terminar de entenderlo bien.

**Excepciones personalizadas**
Ya sabía utilizar `try/except` para controlar errores, pero crear mi propia excepción con `class ListaVaciaError(Exception)` era algo nuevo para mí. No entendía muy bien para qué servía `pass` ni por qué había que heredar de `Exception`. Después de practicarlo, comprendí mejor cómo funcionaba y vi que podía ser muy útil para mostrar mensajes de error más claros.

**`*args` en funciones con argumentos variables**
En el ejercicio de `procesar_texto` me costó entender por qué se utilizaba `*args` en lugar de poner todos los argumentos directamente. Al final entendí que servía para recibir una cantidad variable de argumentos, ya que, dependiendo de la opción elegida, la función necesitaba uno, dos o ninguno. Una vez que lo vi con los ejemplos, me resultó mucho más fácil entenderlo.

**`reduce()` y el módulo `functools`**
Una de las primeras cosas que me llamó la atención fue que tenía que importar `reduce()` desde el módulo `functools`, mientras que `map()` y `filter()` se podían utilizar directamente. Después me costó entender cómo iba acumulando el resultado. Cuando vi que trabajaba con dos elementos cada vez y que iba utilizando el resultado anterior para continuar, lo entendí mucho mejor, sobre todo con el ejemplo de los dígitos.

**Programación orientada a objetos**
Las clases fueron, probablemente, una de las partes que más me costaron de todo el proyecto. Al principio, el `self` me parecía bastante confuso y no entendía por qué había que ponerlo en los métodos. Con los ejemplos, como el de la clase `Arbol`, fui comprendiendo poco a poco cómo funcionaban las clases y los objetos. Aun así, tuve que leer varias veces el enunciado para entender bien qué tenía que hacer en cada paso.

**La clase `UsuarioBanco`**
Este fue el ejercicio que más difícil me resultó. No solo tenía que entender cómo funcionaba la clase, sino que también me di cuenta de que los números del enunciado no cuadraban, porque Bob no tenía suficiente saldo para hacer la transferencia. Tuve que revisar las operaciones, encontrar el problema y justificar el cambio. En ese momento me resultó un poco frustrante, pero al final me sirvió para aprender a detectar errores y comprobar si el código funcionaba como debía.

**Gestión de múltiples excepciones**
Al principio tendía a poner todos los errores en un mismo `except`, porque no veía muy clara la diferencia. Después entendí que separarlos permite identificar mejor qué ha fallado y mostrar un mensaje distinto para cada caso. Esto me ayudó a ver que controlar los errores no consiste solo en evitar que el programa falle, sino también en hacer que sea más fácil de entender y utilizar.

## Resultados y Conclusiones

A lo largo del proyecto consolidé los conceptos fundamentales de Python. Lo más valioso fue entender la diferencia entre trabajar con funciones de orden superior (`map`, `filter`, `reduce`) frente a bucles tradicionales, y cómo las clases permiten organizar el código de forma más estructurada y reutilizable.

Durante el proceso también utilicé IA como apoyo en los momentos en los que me quedaba más encallada. No para que me diera las soluciones directamente, sino para pedirle pistas que me ayudaran a desbloquearme y seguir avanzando por mi cuenta. También me fue útil para conocer buenas prácticas que mejoraban el resultado más allá de lo que pedía el enunciado. Ver en qué fallaba y entender por qué, con una explicación adaptada a lo que estaba haciendo en cada momento, fue en sí mismo un aprendizaje.

## Autora

Maria Montlló  
[@mariamontllo](https://github.com/mariamontllo)
