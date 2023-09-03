# Álgebra Lineal Aplicada para Machine Learning

Este proyecto fue desarrollado como parte del Curso de Álgebra Lineal Aplicada para Machine Learning de la Escuela de Platzi, impartido por el instructor Sebastián Sosa. El proyecto fue creado por José Pablo Cabrera Romo, un Ingeniero Mecánico con una creciente pasión por la Ciencia de Datos y la Inteligencia Artificial.

## Descripción

Este proyecto explora la aplicación del Álgebra Lineal en el contexto del Machine Learning y la Ciencia de Datos. Se presentan ejemplos prácticos de cómo los conceptos de Álgebra Lineal se utilizan para resolver problemas del mundo real en estas disciplinas.

## Contenido del Proyecto

### 1. Introducción a Álgebra Lineal

- En este apartado se introduce el concepto fundamental del Álgebra Lineal y su importancia en el campo del Machine Learning.
- Se exploran conceptos básicos como vectores, matrices, operaciones lineales y sistemas de ecuaciones lineales.

### 2. Aplicaciones de Álgebra Lineal en Machine Learning

- Aquí se analizan diversas aplicaciones del Álgebra Lineal en el contexto del Machine Learning.
- Se destacan ejemplos de cómo se utilizan matrices y vectores para representar datos, características y modelos en ML.
- Se mencionan ejemplos específicos, como la regresión lineal y la descomposición de valores singulares (SVD).

### 3. Ejemplo de Regresión Lineal con Álgebra Lineal

- Se presenta un ejemplo práctico de cómo utilizar el Álgebra Lineal en la implementación de un modelo de regresión lineal.
- Se muestran las operaciones matriciales involucradas en la regresión lineal y cómo se ajustan los coeficientes del modelo.

### 4. Uso de Descomposición de Valores Singulares (SVD)

- Este apartado explora la Descomposición de Valores Singulares (SVD) como una técnica importante en Álgebra Lineal y Machine Learning.
- Se utiliza un ejemplo para ilustrar cómo calcular y utilizar SVD en la reducción de dimensionalidad.

### 5. Aplicación de PCA a un Conjunto de Imágenes

- Se aplica el Análisis de Componentes Principales (PCA) a un conjunto de imágenes para reducir la dimensionalidad de los datos.
- Se muestra cómo PCA puede ayudar a extraer características relevantes de las imágenes.
- Se visualizan las componentes principales y se demuestra cómo proyectar y reconstruir las imágenes originales.

## Conclusión

Este proyecto demuestra la aplicación práctica del Álgebra Lineal en el contexto del Machine Learning y la Ciencia de Datos. José Pablo Cabrera Romo, un Ingeniero Mecánico con formación en Platzi, ha utilizado conceptos como matrices, vectores, regresión lineal y PCA para abordar problemas y aplicaciones del mundo real.

Este README es un resumen de los logros y aprendizajes clave de su proyecto.

¡Gracias por revisar este proyecto y por tu interés en el Álgebra Lineal Aplicada para Machine Learning!

---

**Contacto:** José Pablo Cabrera Romo
**Escuela:** Escuela de Data Science e Inteligencia Artificial de Platzi
**Instructor:** Sebastián Sosa

  
## Installation guide

Please read [install.md](install.md) for details on how to set up this project.

## Project Organization

    ├── LICENSE
    ├── tasks.py           <- Invoke with commands like `notebook`.
    ├── README.md          <- The top-level README for developers using this project.
    ├── install.md         <- Detailed instructions to set up this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures         <- Generated graphics and figures to be used in reporting.
    │
    ├── environment.yml    <- The requirements file for reproducing the analysis environment.
    │
    ├── .here              <- File that will stop the search if none of the other criteria
    │                         apply when searching head of project.
    │
    ├── setup.py           <- Makes project pip installable (pip install -e .)
    │                         so machinelearninglinalg can be imported.
    │
    └── machinelearninglinalg               <- Source code for use in this project.
        ├── __init__.py    <- Makes machinelearninglinalg a Python module.
        │
        ├── data           <- Scripts to download or generate data.
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling.
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions.
        │   ├── predict_model.py
        │   └── train_model.py
        │
        ├── utils          <- Scripts to help with common tasks.
            └── paths.py   <- Helper functions to relative file referencing across project.
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations.
            └── visualize.py

---
