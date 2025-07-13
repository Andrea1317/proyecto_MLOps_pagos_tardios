# proyecto_MLOps_pagos_tardios

Este proyecto tiene como objetivo predecir qué facturas corren riesgo de ser pagadas fuera del plazo legal, utilizando un modelo de machine learning implementado bajo buenas prácticas de MLOps. La solución busca anticipar posibles incumplimientos del Periodo Medio de Pago (PMP) para permitir a los equipos financieros actuar proactivamente.

# Objetivos
-Diseñar un flujo de trabajo reproducible y escalable basado en principios de MLOps.
-Entrenar un modelo de clasificación que anticipe pagos fuera de plazo.
-Registrar experimentos, versionar datos y preparar el modelo para su despliegue.
-Proponer una arquitectura de despliegue y monitorización continua.

# Flujo de trabajo (Pipeline)
-Ingesta y preprocesamiento de datos (pandas, numpy)
-Entrenamiento y validación (Random Forest con scikit-learn)
-Registro de experimentos (MLflow)
-Exportación del modelo (joblib)
-Diseño de despliegue y monitorización (FastAPI, Docker, Prometheus)

# Estructura del repositorio
-notebook_mlops_pago_tardio.ipynb # Desarrollo principal del modelo
-dataset.csv # Dataset de facturas (formato público)
-README.md # Descripción del proyecto

# Herramientas y librerías utilizadas
-Python 3.10+
-scikit-learn
-pandas
-numpy
-MLflow
-joblib
-(propuestas): DVC, Docker, FastAPI, GitHub Actions, Prometheus, Grafana, Kubeflow
