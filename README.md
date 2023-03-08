# Breast-Cancer-Wisconsin-Diagnostic-Data-Set
Este código es un ejemplo de análisis y modelado de datos para un conjunto de datos de diagnóstico de cáncer de mama. A continuación, se muestra un resumen de lo que hace cada parte del código:

-Importa las librerías necesarias para el análisis y modelado de datos.
-Lee el conjunto de datos desde un archivo en línea.
-Realiza una exploración inicial de los datos: muestra los primeros registros, imprime información sobre las columnas y muestra estadísticas descriptivas.
-Elimina dos columnas que no son necesarias para el análisis.
-Divide los datos en variables independientes (X) y dependiente (y), donde la variable objetivo es el diagnóstico (benigno o maligno).
-Muestra el recuento de casos benignos y malignos en la variable objetivo.
-Realiza una matriz de correlación para visualizar la relación entre las variables independientes.
-Elimina las variables que tienen una baja correlación con la variable objetivo.
-Divide los datos en conjuntos de entrenamiento y prueba.

-Entrena un modelo de Random Forest y evalúa su precisión.
-Realiza una selección de características utilizando el método de chi-cuadrado.
-Entrena un segundo modelo de Random Forest con las características seleccionadas y evalúa su precisión.
-Entrena un modelo de Support Vector Machine (SVM) y evalúa su precisión.
-Entrena un modelo de Regresión Logística y evalúa su precisión.


La conclusión de este análisis es que se pueden usar diferentes modelos de aprendizaje automático para predecir si un diagnóstico de cáncer de mama es benigno o maligno. Los modelos de Random Forest y SVM parecen ser los más precisos en este conjunto de datos en particular, pero siempre es importante evaluar varios modelos antes de elegir el mejor para un problema específico. Además, la selección de características puede mejorar la precisión del modelo, lo que hace que sea importante considerar este paso en el proceso de modelado.



