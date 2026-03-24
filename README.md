# Workshop 2 - Machine Learning y Deep Learning Aplicado

Universidad EAFIT - Introduccion a la Inteligencia Artificial (2026-01)

## Integrantes
- Sara Ruiz
- Thomas Osorio
- David Hernandez

## Descripcion
Este repositorio contiene la solucion del Workshop 2, compuesta por dos problemas supervisados:

1. Clasificacion: deteccion de fatiga muscular en ciclismo usando senales EMG.
2. Regresion: estimacion de edad a partir de imagenes faciales.

## Estructura de entrega

```text
workshop_2/
|- README.md
|- clasificacion.ipynb
|- regresion.ipynb
```

## Contenido por notebook

### 1) clasificacion.ipynb
Incluye el desarrollo completo del Problema 1:
- analisis preliminar del dataset EMG,
- transformacion del target a 2 clases,
- feature engineering por ventanas de 1 segundo,
- EDA con interpretaciones,
- pipeline de preprocesamiento,
- entrenamiento y ajuste de hiperparametros,
- comparacion de modelos con metricas en train/val/test,
- evaluacion final del mejor modelo,
- prueba con muestra artificial.

### 2) regresion.ipynb
Incluye el desarrollo completo del Problema 2:
- analisis preliminar del dataset de imagenes,
- EDA de edades e imagenes,
- preprocesamiento reproducible,
- entrenamiento del modelo CNN de regresion,
- metricas MAE, RMSE y R2 en train/val/test,
- curvas de entrenamiento y validacion,
- prueba con muestra artificial y variaciones visuales.

## Datasets usados

### Problema 1 (Clasificacion)
- Muscle Fatigue Cycling
- Fuente: https://huggingface.co/datasets/YominE/Muscle_Fatigue_Cycling

### Problema 2 (Regresion)
- Faces: Age Detection from Images
- Fuente: https://www.kaggle.com/datasets/arashnic/faces-age-detection-dataset
- Referencia adicional: https://susanqq.github.io/UTKFace/

## Requisitos
Se recomienda ejecutar en un entorno Python con:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- tensorflow (para DNN/CNN)

## Nota de evaluacion
Cada notebook incluye:
- codigo ejecutable y documentado,
- resultados de evaluacion con tablas de metricas,
- respuestas y analisis para los numerales del enunciado del workshop.
