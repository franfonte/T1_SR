# Descripción del Proyecto

Este repositorio contiene el desarrollo de una tarea de sistemas de recomendación. A continuación se describen los tres archivos principales y su utilidad:

## 1. analisis_datos.ipynb
Este notebook realiza el análisis exploratorio de los datos. Incluye:
- Carga y revisión de los datasets de entrenamiento, validación y metadatos de videojuegos.
- Cálculo de estadísticas descriptivas (promedios, desviaciones, conteos, etc.).
- Visualización de la distribución de ratings, cantidad de ratings por usuario/item, y otras características relevantes.
- Gráficos y análisis para entender la estructura y calidad de los datos antes de entrenar modelos de recomendación.

## 2. prediccion_ratings.ipynb
En este notebook se implementan y evalúan distintos algoritmos de recomendación, tales como filtrado colaborativo basado en usuarios, en ítems, y modelos de factorización de matrices (SVD, SVD++). Incluye:
- Preparación de los datos para Surprise.
- Entrenamiento y evaluación de modelos con métricas como RMSE y MAE.
- Comparación de desempeño y análisis de resultados.

## 3. generacion_rankings.ipynb
Este notebook se utiliza para generar los rankings de recomendaciones personalizadas para los usuarios, usando los modelos entrenados previamente. Incluye:
- Carga de los modelos y predicciones.
- Obtención de los top-N ítems recomendados para cada usuario.
- Exportación de los resultados para su análisis o entrega.

---
Cada archivo está enfocado en una etapa distinta del flujo de trabajo de sistemas de recomendación: análisis exploratorio, modelado/predicción y generación de rankings finales.