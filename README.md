# TFG - Análisis Topológico en CNNs

Este trabajo de fin de grado explora la evolución y estructura de los filtros en redes neuronales convolucionales (CNN) mediante técnicas avanzadas de visualización y análisis de datos como PCA, UMAP y Vietoris-Rips. Se investiga cómo la definición y especificidad de los filtros mejoran con el aumento de epochs, impactando positivamente en la precisión del modelo.

## Requisitos de Instalación

Este proyecto requiere la configuración de dos entornos virtuales distintos, devido a las incompatibilidades de librerias por el uso del entorno virtual de Kaggle.
Un entorno es para entrenamiento y alamcenamiento de modelos y otro para análisis.

### Entorno para entrenamiento de modelos y almacenamiento de pesos (entorno de Kaggle):
**Python**: `3.8.16`

**Librerías**
- **TensorFlow**: `2.15.0`
- **NumPy**: `1.26.4`
- **Pandas**: `2.2.2`

### Entorno para análisis de modelos:
**Python**: `3.8.16`

**Librerías**
- **Pandas**: `1.5.2`
- **RE**: `2.2.1`
- **NumPy**: `1.24.4`
- **UMAP**: `0.5.5`
- **Matplotlib**: `3.7.4`
- **KeplerMapper**: `2.0.1`
- **Plotly**: `5.18.0`
- **PIL (Pillow)**: `9.4.0`
- **Bokeh**: `3.1.1`
- **Giotto-TDA**: `0.6.0`
- **Scikit-learn**: `1.1.3`


Nota: Algunas librerías básicas de Python como `os`, `math`, `io`, `csv` y `base64` no exponen información de versión ya que son parte de la biblioteca estándar de Python.

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
- `analisis_filtros_n_epoch.ipynb` para análisis después de n épocas.


#### Visualización de filtros de la primera capa
- `filtros_1r_capa_n_epoch.ipynb` visualización después de n épocas.
  

#### Carga de modelos entrenados
- `carga_modelo_n_epoch.ipynb` carga del modelo después de n épocas.


Para ejecutar cualquiera de los notebooks:
jupyter notebook <nombre_del_notebook.ipynb>

## Características del Proyecto

Este Trabajo de Fin de Grado profundiza en la evolución y estructura de los filtros en redes neuronales convolucionales (CNN), empleando técnicas avanzadas de análisis y visualización de datos como PCA, UMAP y Vietoris-Rips. Los principales hallazgos revelan que los filtros de la CNN aumentan su definición y especificidad conforme incrementa el número de epochs, contribuyendo así a la mejora de la precisión del modelo.

A pesar de que técnicas como PCA y UMAP proporcionaron insights valiosos sobre la organización de los filtros, el método Mapper mostró limitaciones significativas para visualizar estructuras complejas de manera clara. Este estudio resalta la importancia de integrar múltiples técnicas para capturar de manera efectiva la dinámica interna de las CNN y sugiere direcciones futuras para optimizar su rendimiento y eficiencia en aplicaciones prácticas.

El análisis topológico, especialmente mediante la homología persistente de Vietoris-Rips, permite observar y entender la topología intrínseca de los espacios de características aprendidos por las CNN, ofreciendo una perspectiva única sobre las complejas interacciones de las características que influencian las decisiones finales del modelo.

### Impacto y Aplicaciones Futuras

La capacidad de visualizar y entender la estructura interna y funcionamiento de modelos de CNN mediante TDA abre nuevas vías para investigaciones futuras que busquen mejorar la interpretabilidad y eficiencia de estos modelos en campos como visión por computador y otras áreas de procesamiento de imágenes donde las CNN dominan actualmente.

## Contacto

Para preguntas o más información, puedes contactarme en: albertrq11@gmail.com.
