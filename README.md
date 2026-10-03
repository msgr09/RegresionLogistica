# Regresión logística – Cáncer de mama (Wisconsin)

## Archivos
- `Regresion_Logistica_Wisconsin_Guiada.ipynb`: Notebook guiado de clasificación binaria con regresión logística, métricas, cambio de umbral y curva ROC.

El dataset viene incluido en scikit-learn (`load_breast_cancer`), por lo que no se necesita ningún CSV.

## Librerías
pandas, numpy, matplotlib y scikit-learn.

## Ejecución
Instalar:
`pip install pandas numpy matplotlib scikit-learn jupyter`

Después abrir:
`jupyter notebook`

Abrir el Notebook y ejecutar las celdas en orden.

## Análisis incluido
- Carga y exploración de datos.
- Codificación de la variable objetivo (0 = benigno, 1 = maligno).
- Gráfico de dispersión radio medio vs. diagnóstico.
- División entrenamiento/prueba (75 % / 25 %, estratificada).
- Estandarización de variables (StandardScaler).
- Regresión logística.
- Predicción de clases y probabilidades.
- Accuracy, Precision, Recall y F1-score.
- Matriz de confusión.
- Cambio de umbral de decisión (0.50 a 0.60).
- Curva ROC y ROC-AUC.

## Resultados del notebook
- Accuracy: 96.50 %
- Precision (maligno): 98.00 %
- Recall (maligno): 92.45 %
- F1-score (maligno): 95.15 %
- ROC-AUC: 99.62 %

## Nota
La redacción y contextualización final deben ser revisadas y adaptadas por el estudiante antes de la entrega.
