# Implementación del Perceptrón en el Conjunto de Datos Iris

## Introducción

El conjunto de datos Iris es ampliamente utilizado para demostrar técnicas de clasificación en el aprendizaje automático. Contiene mediciones de flores de tres especies de Iris: Iris setosa, Iris virginica e Iris versicolor. Este proyecto ilustra el uso del algoritmo de Perceptrón para clasificar dos de estas especies utilizando sus características morfológicas.

## Objetivos

1. **Cargar y visualizar el conjunto de datos Iris**.
2. **Entrenar un modelo de Perceptrón para clasificar dos de las tres especies de Iris**.
3. **Visualizar el límite de decisión construido por el algoritmo de Perceptrón**.
4. **Evaluar el rendimiento del modelo entrenado**.

## Librerías Utilizadas

- **Pandas**: Para la manipulación y análisis de datos tabulares.
- **Numpy**: Para operaciones matemáticas y manipulación de matrices.
- **Matplotlib**: Para la visualización de datos en gráficos 2D y 3D.
- **Scikit-learn**: Para la implementación del algoritmo de Perceptrón y la evaluación del modelo.

## Descripción del Proyecto

### 1. Lectura del Conjunto de Datos

El conjunto de datos Iris se carga utilizando Scikit-learn. Este conjunto incluye 50 muestras de cada una de las tres especies de Iris, con cuatro características medidas: longitud del sépalo, ancho del sépalo, longitud del pétalo y ancho del pétalo.

### 2. Visualización del Conjunto de Datos

Se crean visualizaciones en 2D y 3D para observar la distribución de las diferentes especies de Iris en función de sus características medidas. Esto ayuda a entender cómo se separan las especies basadas en estas características.

### 3. Entrenamiento del Algoritmo

Para simplificar el problema, se seleccionan dos especies de Iris (`setosa` y `versicolor`) y dos características (`longitud del pétalo` y `ancho del pétalo`). El algoritmo de Perceptrón se entrena con este subconjunto de datos para clasificar las dos especies.

### 4. Visualización del Límite de Decisión

El límite de decisión generado por el Perceptrón se visualiza en un gráfico 2D. Este gráfico muestra cómo el modelo clasifica las diferentes especies en función de las características seleccionadas.

### Evaluación del Modelo

Se evalúa el rendimiento del modelo utilizando la métrica de precisión (accuracy). La precisión se calcula para determinar qué tan bien el modelo clasifica correctamente las muestras en el conjunto de datos de entrenamiento.

## Resultados

- **Visualización**: Se realizaron visualizaciones en 2D y 3D para comprender mejor la distribución de las diferentes especies de Iris.
- **Entrenamiento del Perceptrón**: Se entrenó un modelo de Perceptrón con un subconjunto de datos y se visualizó el límite de decisión.
- **Evaluación**: El modelo mostró una precisión del 100% en el conjunto de datos de entrenamiento, indicando que fue capaz de clasificar correctamente todas las muestras en el conjunto de datos reducido.
