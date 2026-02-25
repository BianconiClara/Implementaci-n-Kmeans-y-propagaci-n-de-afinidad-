# Implementaci-n-Kmeans-y-propagaci-n-de-afinidad-
Repositorio correspondiente a un trabajo práctico donde se implementan y comparan dos algoritmos de Machine Learning utilizando el dataset “Wine Recognition” de scikit-learn.
---
## Preparación del Dataset
Los datos fueron cargados en un dataframe de Pandas y luego normalizados por medio de un pipeline restando la media y dividiendo por la desviación estándar. A los datos ya normalizados se les aplicó el algoritmo PCA disminuyendo su dimensionalidad a 2. Finalmente, estos datos fueron representados en un gráfico de dispersión.
## Algoritmos Aplicados
Por medio del comando train_test_split se separó el dataset obtenido en conjuntos de entrenamiento y prueba (30 %). A los datos de entrenamiento se les aplicó el algoritmo KMeans con diferente cantidad de clusters K (2, 3 ,4 y 5). Por último, se aplicó el algoritmo de propagación de afinidad sobre los datos de entrenamiento.
  
 
