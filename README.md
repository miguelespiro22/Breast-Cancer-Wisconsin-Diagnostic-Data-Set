# Breast-Cancer-Wisconsin-Diagnostic-Data-Set
Introducción
En este proyecto, desarrollaré un modelo que pueda identificar si un paciente tiene o no cáncer de mama. Para ello, utilizaré un conjunto de datos del repositorio de aprendizaje automático de UCI. El conjunto de datos contiene mediciones de características del núcleo de células obtenidas a partir de muestras de tejido mamario de mujeres con cáncer de mama. El objetivo es desarrollar un modelo de aprendizaje automático que pueda predecir si una muestra es benigna o maligna. Dado que es más peligroso tener un falso negativo (un resultado incorrecto que indica que la muestra es benigna cuando en realidad es maligna), enfocaré la evaluación del modelo en minimizar los falsos negativos.

Datos
El conjunto de datos que utilizaré en este proyecto está disponible en el siguiente enlace: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

El conjunto de datos contiene 569 muestras de células de mama, cada una de las cuales tiene 30 características. Cada muestra tiene una etiqueta que indica si la muestra es benigna (B) o maligna (M). La etiqueta es el resultado que se intentará predecir con el modelo.

Preprocesado de datos
Antes de empezar a construir el modelo, es necesario preprocesar los datos. En particular, es necesario:

Cargar los datos desde un archivo CSV.
Eliminar las columnas que no se utilizarán en el modelo.
Convertir las etiquetas en valores binarios (0 o 1) para que puedan ser utilizadas por los algoritmos de aprendizaje automático.
Escalar los datos para que tengan una media de 0 y una desviación estándar de 1. Esto ayuda a asegurar que las características tengan la misma escala y evita que las características con valores grandes dominen el modelo.
