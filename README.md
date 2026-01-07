# telecom-churn-prediction
Customer churn prediction using machine learning and Python

# Modelo de Clasificación para Predicción de Churn en Telecomunicaciones

## Descripción
Proyecto de ciencia de datos enfocado en la predicción de cancelación de clientes (churn) en una empresa de telecomunicaciones. El objetivo es identificar de manera temprana a los clientes con mayor probabilidad de abandono, apoyando la toma de decisiones estratégicas en iniciativas de retención.

## Objetivo
Desarrollar un modelo de clasificación robusto y reproducible que permita estimar el riesgo de churn de cada cliente, priorizando métricas adecuadas para datos desbalanceados y buenas prácticas de validación.

## Datos
El proyecto utiliza un dataset estructurado de clientes de telecomunicaciones que incluye variables demográficas, de uso del servicio y de facturación.

Los datos utilizados corresponden a un dataset educativo proporcionado en el contexto de un bootcamp de ciencia de datos. No contienen información personal identificable.

## Metodología
Se realizó un análisis exploratorio de datos para comprender la distribución de variables y la relación con el churn.

Posteriormente, se implementó un flujo de modelado supervisado que incluye:
- Limpieza y preparación de datos
- Ingeniería de características
- Entrenamiento de modelos de clasificación
- Evaluación mediante validación cruzada

Se priorizó el uso de métricas como AUC-ROC para evaluar el desempeño del modelo en un escenario de clases desbalanceadas.

## Resultados
El modelo final alcanzó un AUC-ROC de 0.88 mediante validación cruzada, destacando la importancia de la ingeniería de características y la selección adecuada de métricas.

Los resultados permiten identificar segmentos de clientes con alto riesgo de cancelación, aportando información accionable para estrategias de retención.

## Tecnologías
- Python
- pandas
- scikit-learn
- LightGBM

## Reproducibilidad
Para reproducir el análisis:
1. Clonar el repositorio.
2. Crear un entorno virtual.
3. Instalar dependencias desde `requirements.txt`.
4. Ejecutar el notebook ubicado en la carpeta `notebooks/`.
