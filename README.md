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

