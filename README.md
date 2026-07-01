# Tareas de Machine Learning

Este repositorio contiene distintas tareas prácticas de Machine Learning desarrolladas a partir de notebooks de clase. Cada tarea se encuentra organizada en su propia carpeta, junto con los archivos necesarios para su ejecución.

## Contenido general

El repositorio incluye ejercicios aplicados de:

* Regresión lineal
* Árboles de decisión
* Support Vector Machine
* Modelos de boosting
* Análisis exploratorio de datos
* Evaluación de modelos predictivos

Cada carpeta contiene, según corresponda:

* Un notebook `.ipynb` con la tarea desarrollada.
* Archivos `.csv` con las bases de datos utilizadas.
* Archivos `.pkl` con modelos entrenados o datos serializados.
* Archivos de resultados generados durante la ejecución.

## Archivos `.pkl`

Los archivos `.pkl` corresponden a objetos guardados con Python mediante `pickle`. En este repositorio se utilizan principalmente para almacenar modelos entrenados, particiones de datos o elementos necesarios para reutilizar resultados sin volver a ejecutar todo el entrenamiento.

## Requisitos

Para ejecutar los notebooks se recomienda tener instalado Python 3 y las siguientes librerías:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy statsmodels 
```

## Ejecución

Para revisar una tarea, basta con abrir la carpeta correspondiente y ejecutar el notebook `.ipynb` en Jupyter Notebook o JupyterLab.

Es importante mantener los archivos `.csv` y `.pkl` dentro de la misma carpeta del notebook, ya que son utilizados durante la ejecución.

## Objetivo

El objetivo de este repositorio es reunir y organizar las tareas prácticas de la asignatura, aplicando distintas técnicas de Machine Learning sobre bases de datos reales o de ejemplo.

## Observación

Este repositorio tiene fines académicos. Los modelos y resultados fueron desarrollados según las instrucciones de cada clase y tarea.
