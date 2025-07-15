# Challenge-T-cnico
Este proyecto consiste en desarrollar un modelo de machine learning para clasificar la personalidad de individuos en introvertidos y extrovertidos basado en datos comportamentales recopilados sobre sus hábitos sociales.

Objetivo
El objetivo principal es analizar un dataset real con múltiples variables sociales y de comportamiento para predecir la personalidad de una persona. Se realiza un análisis exploratorio de datos (EDA), limpieza e imputación de valores faltantes y se entrenan varios modelos de clasificación.

Metodología
Se exploraron y analizaron variables numéricas y categóricas relevantes para entender su distribución y posibles valores atípicos.
Se imputaron valores faltantes usando mediana para variables numéricas y moda para variables categóricas.
Se entrenaron y compararon cinco modelos diferentes: Regresión Logística, K-Nearest Neighbors, Árbol de Decisión, XGBoost y LightGBM.
Se optimizaron los hiperparámetros usando GridSearchCV para mejorar el rendimiento.
Se seleccionó el mejor modelo basado en métricas de precisión.

Resultados
El modelo LightGBM con hiperparámetros optimizados alcanzó un accuracy superior al 96%, demostrando la efectividad de los datos y el enfoque aplicado para predecir la personalidad.
