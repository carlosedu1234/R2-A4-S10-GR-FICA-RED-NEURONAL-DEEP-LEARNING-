# Predicción de la producción agrícola con redes neuronales

## Descripción

En esta práctica se trabajó con redes neuronales para analizar la relación entre la cantidad de fertilizante aplicada y la producción agrícola. Se utilizaron modelos con diferentes números de capas ocultas para comparar su comportamiento y evaluar su capacidad para realizar predicciones.

## Objetivos

- Comprender el funcionamiento básico de las redes neuronales.
- Entrenar modelos con diferentes arquitecturas.
- Comparar los resultados mediante el error cuadrático medio (MSE).
- Analizar cómo pueden utilizarse las predicciones para apoyar la toma de decisiones agrícolas.

## Metodología

Se utilizaron 15 pares de datos de fertilizante y producción, previamente normalizados. Los modelos se implementaron con TensorFlow y Keras, utilizando el optimizador Adam, una tasa de aprendizaje de 0.01 y 1000 épocas de entrenamiento.

Se compararon tres configuraciones con 1, 2 y 3 capas ocultas, cada una con 16 neuronas y activación ReLU.

## Resultados

Los tres modelos estimaron una producción aproximada de **6.8 toneladas por hectárea** para una aplicación de 100 kg/ha de fertilizante.

Los modelos de dos y tres capas obtuvieron un menor error de entrenamiento que el modelo de una capa. Sin embargo, es necesario realizar pruebas adicionales con nuevos datos para evaluar su capacidad de generalización.

## Aplicación práctica

Este ejercicio permite explorar cómo las redes neuronales pueden ayudar a estimar la producción agrícola, comparar diferentes dosis de fertilizante y apoyar decisiones relacionadas con los costos de producción. Las predicciones son aproximaciones y deben validarse con datos reales antes de utilizarse en situaciones agrícolas.

## Tecnologías utilizadas

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
