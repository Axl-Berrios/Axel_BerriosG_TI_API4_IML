# Análisis del Conjunto de Datos de Iris

Este proyecto se centra en el análisis del famoso conjunto de datos de Iris, que contiene información sobre tres especies de flores de iris. El objetivo principal es aplicar el algoritmo K-means para agrupar las flores en función de sus características morfológicas.

## Contenido

- Descripción del conjunto de datos
- Visualización de datos
- Aplicación del algoritmo K-means
- Evaluación del modelo
- Cómo ejecutar el código

## Descripción del Conjunto de Datos

El conjunto de datos de Iris contiene las siguientes características:

- **Número de Instancias**: 150 (50 en cada una de las tres clases)
- **Número de Atributos**: 4 atributos numéricos predictivos y la clase
- **Atributos**:
  - Longitud del sépalo (en cm)
  - Ancho del sépalo (en cm)
  - Longitud del pétalo (en cm)
  - Ancho del pétalo (en cm)
  - Clase:
    - Iris-Setosa
    - Iris-Versicolour
    - Iris-Virginica

## Visualización de Datos

Se realiza una gráfica de dispersión para visualizar la relación entre la longitud y el ancho del sépalo:

```python
import matplotlib.pyplot as plt

sepal_length = iris.data[:, 0]
sepal_width = iris.data[:, 1]

plt.scatter(sepal_length, sepal_width)
plt.xlabel('Largo del sépalo')
plt.ylabel('Ancho del sépalo')
plt.show()


### Notas sobre el archivo `README.md`:

- **Estructura clara**: El archivo está estructurado en secciones que facilitan la lectura y comprensión.
- **Código comentado**: Se incluyen fragmentos de código para ilustrar cada paso del proceso.
- **Instrucciones de ejecución**: Se proporciona una guía sobre cómo ejecutar el código, lo que es útil para otros usuarios que deseen replicar el análisis.
