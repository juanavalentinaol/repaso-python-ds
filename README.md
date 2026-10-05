
# Repaso de Python para Ciencia de Datos

Esta actividad repasa los fundamentos de Python que se usan en ciencia de datos: variables, estructuras de control, diccionarios y funciones. Todo el desarrollo está en el notebook `practica_python.ipynb`.

## Contenido

### Tarea 1: Definición de variables
Se definen variables de distintos tipos para describir un producto:
- Nombre (`str`)
- Precio (`float`)
- Cantidad en stock (`int`)
- Disponibilidad de descuento (`bool`)

Después se imprime un resumen del producto con **f-strings**.

### Tarea 2: Lógica de negocio (bucle + condicional)
Se crea una lista de precios y se recorre con un bucle `for`. Cada precio se clasifica con un condicional:
- **Caro**: mayor a 100
- **Económico**: menor o igual a 100

### Tarea 3: Estructura de datos compleja
Se crea un diccionario `almacen`, donde cada clave es un producto y cada valor es su stock. En esta tarea se practica:
- Agregar un nuevo producto al diccionario
- Consultar e imprimir el stock de un producto específico

### Tarea 4: Modularización con funciones
Se implementa la función `resumen_estadistico(numeros)`, que recibe una lista de números y devuelve un diccionario con:
- La **suma** total
- El **promedio**
- La **cantidad** de elementos

```python
resumen_estadistico([10, 20, 30])
# {'suma': 60, 'cantidad': 3, 'promedio': 20.0}
