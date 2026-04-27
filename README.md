# Evaluación Parcial N°1 — Deep Learning

Este repositorio contiene el desarrollo de la Evaluación Parcial N°1 para la asignatura **Deep Learning**. 

El proyecto consiste en la implementación de una Red Neuronal Artificial (Perceptrón Multicapa - MLP) desarrollada en Python (TensorFlow/Keras) para resolver un problema de clasificación binaria: predecir la presencia de enfermedades cardíacas basándose en variables clínicas. Todo el desarrollo sigue la metodología **CRISP-DM**.

## Autor
* **Estudiante:** Inti Escobar
* **Profesor:** Edwin Orlando Sanchez Valderrama
* **Asignatura:** DLY0100 - Deep Learning

## Contenido del Repositorio
* `Evaluacion_Parcial_1.ipynb`: Cuaderno de Google Colab con el código fuente, preprocesamiento, arquitectura del modelo, análisis teórico y conclusiones.
* `heart.csv`: Dataset original extraído de UCI Machine Learning Repository utilizado para entrenar y evaluar el modelo.
* `README.md`: Documentación e instrucciones de ejecución.

## Requisitos
Para ejecutar este proyecto, no es necesario instalar nada localmente si se utiliza **Google Colab**. Las librerías principales utilizadas son:
* `tensorflow` / `keras`
* `pandas`
* `numpy`
* `matplotlib` / `seaborn`
* `scikit-learn`

## Instrucciones de Ejecución

Para replicar y evaluar este proyecto, sigue estos pasos:

1. **Abrir el Cuaderno en Google Colab:**
   * Descarga el archivo `Evaluacion_Parcial_1.ipynb` de este repositorio.
   * Ve a [Google Colab](https://colab.research.google.com/), selecciona "Subir" (Upload) y carga el cuaderno.

2. **Cargar el Dataset (heart.csv):**
   * Descarga el archivo `heart.csv` de este repositorio a tu computadora.
   * En el entorno de Google Colab, ve al panel izquierdo y haz clic en el icono de la **Carpeta** (Archivos).
   * Haz clic en el icono de **Subir al almacenamiento de sesión** (el papel con una flecha hacia arriba).
   * Selecciona el archivo `heart.csv` que descargaste. *(Nota: El archivo debe quedar suelto en la carpeta principal de Colab para que el código lo lea correctamente).*

3. **Ejecutar el Código:**
   * Una vez cargado el cuaderno y el archivo CSV, ve al menú superior y selecciona **"Entorno de ejecución" > "Ejecutar todo"**.
   * El código se ejecutará secuencialmente mostrando el preprocesamiento, el entrenamiento del modelo y los gráficos de evaluación final.
