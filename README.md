# ML Lab - Iris Classification

Laboratorio inicial de Machine Learning orientado a validar un entorno local de trabajo, comprender el flujo básico de un problema de clasificación supervisada y documentar técnicamente cada etapa del proceso.

Este proyecto utiliza el dataset **Iris** y un modelo **Random Forest** para construir un primer pipeline de Machine Learning simple, reproducible y explicado paso a paso.

---

## Objetivo

El objetivo principal de este laboratorio es doble:

1. **Validar el entorno técnico local**, incluyendo Python, Jupyter Notebook, entorno virtual y estructura de proyecto.
2. **Comprender el flujo base de un problema de clasificación supervisada**, desde la carga de datos hasta la evaluación del modelo.

Este repositorio fue concebido como una base inicial para evolucionar hacia proyectos más cercanos a escenarios reales de análisis de datos, ingeniería de datos y machine learning.

---

## Alcance del laboratorio

Este laboratorio cubre las siguientes etapas:

- importación de librerías del ecosistema de ciencia de datos,
- carga y estructuración del dataset Iris,
- separación de variables predictoras y variable objetivo,
- división del dataset en entrenamiento y prueba,
- entrenamiento de un modelo `RandomForestClassifier`,
- evaluación del desempeño mediante `accuracy` y `classification_report`,
- análisis de importancia relativa de variables,
- documentación técnica del notebook en formato Markdown.

---

## Estructura del proyecto

```text
ml-lab/
├── .gitignore
├── Dockerfile
├── compose.yml
├── requirements.txt
└── notebooks/
    ├── ml_lab_iris.ipynb
    └── test_venv.py