# Aprendiendo Markdown

Esto es un texto normal que estamos escribiendo debajo del encabezado

# Encabezado nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4
##### Encabezado de nivel 5
###### Encabezado de nivel 6

# Prueba de texto

Este es un texto que está en 
la misma línea, aunque en el 
editor se escribe en líneas separadas

Esto comienza en un párrafo nuevo
porque se han puesto dos saltos de línea

Y esto está en líneas sepadas  
porque tras cada linea hay  
dos espacios y un salto de línea

# Listas no ordenadas

* Elemento 1
* Otro elemento
* Más elementos
  * Elemento anidado
  * Anidado 2
    * Anidado 3   

# Listas ordenadas

Estos son los puntos a seguir:

1. Leer la documentación
2. Practicar
3. Practicar más
4. Y seguir practicando más y más

# Resaltado de texto

Ejemplo de *texto en cursiva*  
Ejemplo de **texto en negrita**

```
# -- Ejemplo de código en python
a = 2
print("Programa en python")
print(f"La variable a vale {a}")
```

```python
# -- Ejemplo de código en python
a = 2
print("Programa en python")
print(f"La variable a vale {a}")
```

En python la expresión `print(f" a + b = {2 + 1} ")` produce como resultado `a + b = 3` 

# Enlaces 

## Enlaces externos

En wikipedia encontramos más información sobre [markdown](https://es.wikipedia.org/wiki/Markdown)

## Enlaces internos

Aquí hay información sobre [los enlaces](#Enlaces) en markdwon

# Imágenes

## Imagen en fichero local

![](Logo-urjc.png)


## Imagen en URL

![](https://upload.wikimedia.org/wikipedia/commons/2/2f/CC_BY-SA_3.0.png)

# Citas

Un par de citas de Isaac Asimov:

> Escribo por la misma razón por la que respiro, porque si no lo hiciera, moriría

> Estoy convencido de que la autoeducación es el único tipo de educación que existe  


# Tablas

|         | Col 1 | Col 2| Col 3| Col4 |
|---------|-------|------|------|------|
|  Fila 1 |   1   |   2  |   3  |  4   |
|  Fila 2 |   2   |   4  |   6  |  8   |
|  Fila 3 |   3   |   6  |   9  |  12  |

|          |  node.js  | Django | Flask | Electron |
|----------|-----------|--------|-------|----------|
| Lenguaje | Js        | Python | Python| js       |
| URL      | [link](https://nodejs.org/es/) | [link](https://www.djangoproject.com/)  | [Link](https://flask.palletsprojects.com/en/1.1.x/) | [Link](https://www.electronjs.org/) |
| Versión  |  14.15.5  | 3.1.6  | 1.1.2 | 11.2.3 |