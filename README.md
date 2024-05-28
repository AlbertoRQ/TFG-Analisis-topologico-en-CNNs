# TFG-Análisis Topológico para CNN

Descripción del Proyecto:
[//]: Este trabajo de fin de grado explora la evolución y estructura de los filtros en redes neuronales convolucionales (CNN) mediante técnicas avanzadas de visualización y análisis de datos como PCA, UMAP y Vietoris-Rips. Se investiga cómo la definición y especificidad de los filtros mejoran con el aumento de epochs, impactando positivamente en la precisión del modelo.

## Requisitos de Instalación

Este proyecto requiere la configuración de dos entornos virtuales distintos, uno para entrenamiento de modelos y otro para análisis.

### Entorno para entrenamiento de modelos:
[//]: # (Detalles específicos del entorno como librerías y versiones.)

### Entorno para análisis de modelos:
[//]: # (Detalles específicos del entorno como librerías y versiones.)

## Cómo Usar

### Preparación del entorno
1. Clona el repositorio:
   git clone https://github.com/albertrq11/TFG-Analisis-topologico-para-CNN.git
2. Navega al directorio del proyecto:
   cd TFG-Analisis-topologico-para-CNN
3. Activa el entorno virtual adecuado.

### Notebooks
Este proyecto utiliza Jupyter Notebooks para análisis y visualización en diferentes etapas de entrenamiento del modelo. Aquí tienes una guía rápida para usar cada uno:

#### Construcción y entrenamiento de modelos CNN
- `CNN_(64,32,64).ipynb`: Construcción y entrenamiento de modelos CNN utilizando Keras y TensorFlow para el dataset MNIST.
- `funcionamiento_CNN.ipynb`: Explicación detallada del funcionamiento de las CNN, incluyendo la visualización de filtros y activaciones.
  
#### Análisis de filtros después de entrenamiento
- analisis_filtros_1_epoch.ipynb para análisis después de 1 época.
- analisis_filtros_10_epoch.ipynb para análisis después de 10 épocas.
- analisis_filtros_100_epoch.ipynb para análisis después de 100 épocas.
- analisis_filtros_500_epoch.ipynb para análisis después de 500 épocas.
- analisis_filtros_1000_epoch.ipynb para análisis después de 1000 épocas.
- analisis_filtros_10000_epoch.ipynb para análisis después de 10000 épocas.

#### Visualización de filtros de la primera capa
- filtros_1r_capa_1_epoch.ipynb visualización después de 1 época.
- filtros_1r_capa_10_epoch.ipynb visualización después de 10 épocas.
- filtros_1r_capa_100_epoch.ipynb visualización después de 100 épocas.
- filtros_1r_capa_500_epoch.ipynb visualización después de 500 épocas.
- filtros_1r_capa_1000_epoch.ipynb visualización después de 1000 épocas.
- filtros_1r_capa_10000_epoch.ipynb visualización después de 10000 épocas.

#### Carga de modelos entrenados
- carga_modelo_1_epoch.ipynb carga del modelo después de 1 época.
- carga_modelo_10_epoch.ipynb carga del modelo después de 10 épocas.
- carga_modelo_100_epoch.ipynb carga del modelo después de 100 épocas.
- carga_modelo_500_epoch.ipynb carga del modelo después de 500 épocas.
- carga_modelo_1000_epoch.ipynb carga del modelo después de 1000 épocas.
- carga_modelo_10000_epoch.ipynb carga del modelo después de 10000 épocas.

Para ejecutar cualquiera de los notebooks:
jupyter notebook <nombre_del_notebook.ipynb>

## Características del Proyecto

[//]: # (Descripción de las principales características del proyecto, como métodos de análisis topológico utilizados y cualquier hallazgo relevante.)

## Contacto

Para preguntas o más información, puedes contactarme en: albertrq11@gmail.com.
