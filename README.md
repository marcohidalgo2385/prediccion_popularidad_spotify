# prediccion_popularidad_spotify

# Predicción de Popularidad de Canciones de Spotify

## Descripción

Este proyecto utiliza Machine Learning para predecir la popularidad de canciones en Spotify basándose en sus características de audio. Se exploran diferentes características como la "danceabilidad", "energía", "acústica", entre otras, para identificar los factores que influyen en la popularidad de una canción.

## Dataset

El dataset utilizado para este proyecto contiene información de 30,000 canciones de Spotify, incluyendo características de audio y la popularidad de cada canción. 

## Metodología

1. **Exploración de Datos (EDA):** Se realiza un análisis exploratorio de los datos para comprender la distribución de las variables, identificar valores atípicos y encontrar correlaciones entre las características y la popularidad.

2. **Ingeniería de Características:** Se crean nuevas características a partir de las existentes para mejorar la capacidad predictiva del modelo. Por ejemplo, se escala la característica "loudness" para que tenga un rango comparable con otras variables.

3. **Selección de Características:** Se seleccionan las características más relevantes para el modelo utilizando técnicas como la correlación con la variable objetivo (popularidad).

4. **Construcción del Modelo:** Se utiliza un modelo de Regresión Logística para predecir la popularidad de las canciones. Se entrena el modelo con un conjunto de datos de entrenamiento y se evalúa su rendimiento con un conjunto de datos de prueba.

5. **Evaluación y Ajuste del Modelo:** Se evalúa la precisión del modelo utilizando métricas como la exactitud (accuracy). Se ajustan los hiperparámetros del modelo para optimizar su rendimiento.

## Resultados

El modelo de Regresión Logística alcanzó una precisión de 0.58 en la predicción de la popularidad de las canciones. Se identificaron las características más influyentes en la popularidad, como la "danceabilidad", "energía" y "acústica".

## Conclusiones

Este proyecto demuestra el potencial del Machine Learning para predecir la popularidad de canciones en Spotify. Los resultados del análisis pueden ser útiles para artistas, productores y plataformas de streaming para comprender las preferencias musicales actuales y crear música más atractiva.

## Próximos Pasos

* Incluir características adicionales como información del artista, fecha de lanzamiento o interacción en redes sociales.
* Experimentar con diferentes algoritmos de Machine Learning para mejorar la precisión del modelo.
* Investigar la influencia de factores culturales en la popularidad musical.


## Herramientas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio: `git clone [URL del repositorio]`
2. Instalar las bibliotecas necesarias: `pip install -r requirements.txt`
3. Ejecutar el notebook de Jupyter: `jupyter notebook spotify_popularity_prediction.ipynb`


## Autor

Marco Hidalgo

