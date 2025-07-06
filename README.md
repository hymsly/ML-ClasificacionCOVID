# Detección de COVID-19 mediante análisis de tos  
**Análisis de tos para la detección de COVID-19: Evaluación de modelos de aprendizaje automático y optimización con Optuna**

Este repositorio contiene el código y resultados del estudio sobre la detección automática de casos positivos de COVID-19 a partir de grabaciones de tos utilizando modelos de aprendizaje automático. El estudio se basa en una version filtrada de la base de datos pública [Coswara](https://github.com/iiscleap/Coswara-Data), y explora diversos modelos de aprendizaje automitco optimizados con técnicas modernas de ajuste de hiperparámetros como Optuna.

---

## Objetivo del Estudio

Evaluar la capacidad predictiva de distintos clasificadores supervisados (SVM, Regresión Logística, KNN, Árboles de Decisión y XGBoost) en la detección de COVID-19 a partir de características acústicas extraídas de señales de tos. Se emplea validación cruzada, métricas como F1-score y AUC, y optimización de hiperparámetros mediante la librería [Optuna](https://optuna.org/).

---

## Resultados Destacados
Mejor modelo: XGBoost

F1-score: 72.0%

AUC: 92.1%

Evaluación final realizada sobre test set no balanceado

## Conclusiones Destacadas
Este estudio demostró que es posible desarrollar modelos predictivos basados en señales de audio con una alta capacidad para detectar la presencia de COVID-19 a partir de grabaciones de tos. A través de la extracción de características acústicas relevantes y la aplicación de técnicas de aprendizaje automático, se logró entrenar modelos con un desempeño competitivo.

Asimismo, la utilización de la librería Optuna para la optimización de hiperparámetros permitió mejorar significativamente el rendimiento de los modelos, mostrando la importancia de ajustar adecuadamente los parámetros de entrenamiento. No obstante, se identificó la necesidad de controlar el sobreajuste, ya que mejoras en el rendimiento sobre el conjunto de entrenamiento no siempre se reflejan en una mayor capacidad de generalización sobre datos nuevos.

Finalmente, es importante destacar que los resultados obtenidos no deben considerarse equivalentes a los de una prueba molecular o serológica. En cambio, estos modelos pueden ser empleados como una herramienta de prediagnóstico rápida, accesible y de bajo costo, útil en escenarios con recursos limitados o complemento a procesos de evaluación inicial no invasiva.
