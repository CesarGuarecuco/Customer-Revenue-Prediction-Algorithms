# Customer-Revenue-Prediction-Algorithms

## Descripción del Proyecto
Este proyecto tiene como objetivo predecir los ingresos de los clientes utilizando diferentes algoritmos de machine learning aplicados a un conjunto de datos de clientes. El dataset proviene del archivo banco.xlsx y contiene diversas características que se utilizan para entrenar y evaluar modelos predictivos.

El proceso incluye la transformación de datos, la división en conjuntos de entrenamiento y prueba, la elaboración de modelos de predicción, el ajuste de hiperparámetros y la comparación de los modelos obtenidos.

## Instrucciones del Proyecto

##### 1.Transformación de la Columna 'Historial Crediticio':

Se transforma la columna Historial Crediticio a valores numéricos para facilitar su uso en los modelos:

0: Bueno

1: Regular

2: Malo


##### 2.Separación de Variables:
Se identifican las variables independientes y la variable dependiente (R3ta) para construir los modelos predictivos.


##### 3.División de Conjuntos de Datos:
Los datos se dividen en un conjunto de entrenamiento (75%) y un conjunto de prueba (25%) para evaluar el rendimiento de los modelos.


##### 4.Elaboración de Modelos de Predicción:
Se implementan dos modelos iniciales utilizando Scikit-learn.
Se utilizan técnicas de ajuste de hiperparámetros con GridSearchCV para optimizar otros dos modelos.


##### 5.Comparación de Modelos:
Se comparan los modelos utilizando métricas como el MSE (Mean Squared Error) y el R² (Coeficiente de Determinación).


## Resultados Obtenidos
El mejor modelo fue el RandomForest ajustado, con los siguientes resultados:

MSE: 0.048464

R²: 0.86613

Estos resultados indican que el modelo tiene un bajo error de predicción y una alta capacidad para explicar la variabilidad de los ingresos de los clientes.


## Visualización
El proyecto incluye gráficos que comparan los valores reales con las predicciones, facilitando la evaluación visual del rendimiento de los modelos.


### Archivos en el Repositorio
Customer Revenue Prediction Algorithms.ipynb: Notebook principal con el análisis y la implementación de los modelos.

banco.xlsx: Archivo de datos utilizado para el análisis.

README.md: Este archivo de documentación.

requirements.txt: Lista de dependencias necesarias para ejecutar el notebook.


## Conclusiones
El modelo RandomForest ajustado resultó ser el más eficaz para predecir los ingresos de los clientes, basado en las métricas de MSE y R². Este proyecto demuestra el proceso completo de preparación de datos, ajuste de modelos y evaluación de resultados, proporcionando una guía clara para la implementación de algoritmos de predicción en problemas similares.
