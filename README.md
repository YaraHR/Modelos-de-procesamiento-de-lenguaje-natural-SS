## Información sobre los códigos

- En el archivo [Lista con métricas por texto.ipynb](https://github.com/YaraHR/Modelos-de-procesamiento-de-lenguaje-natural-SS/blob/Machine-Learning/Lista%20con%20m%C3%A9tricas%20por%20texto.ipynb) se encuentra el código que transforma texto a grafo, para utilizarse como objeto de [Networkx](https://networkx.org/) de tal forma que se obtienen distintas métricas como coeficiente de *clustering*, *dregree_centrality*, etc. Para finalmente tener como resultado un archivo .csv con todas esas características para un posterior análisis y/o entrenar algún modelo. NOTA: en este código se utilizan los archivos train/test de la subtask_1 previamente divididos. Para la parte de subtask_2, se utiliza el dataframe original.

- En el archivo [XGB-LR-RF.ipynb](https://github.com/YaraHR/Modelos-de-procesamiento-de-lenguaje-natural-SS-/blob/main/XGB-LR-RF.ipynb) se encuentra el código con distintos modelos de clasificación (*XGBoost*, *Logistic Regression* y *Random Forest*) los cuales han sido entrenados para determinar si un texto es generado por máquina o por humano.

NOTA: Los datos utilizados se encuentran [aquí](https://drive.google.com/drive/folders/1OIr35No1_W1F4UNNN7UYKIi3N3hZxCyG?usp=drive_link), y fueron proporcionados gracias al [IberAuTexTification 2024](https://sites.google.com/view/iberautextification/home?authuser=0).

## Resultados

|                Modelo               | F1-Score |
|-------------------------------------|----------|
|    Random Forest Classifier (RFC)   | **0.719** |
|        LogisticRegression (LR)      | 0.712 |
| Extreme Gradient Boosting (XGBOOST) | 0.638 |

