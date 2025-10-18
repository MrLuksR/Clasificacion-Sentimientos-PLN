# Clasificación de Sentimientos - PLN
## Inicio
Se importaron dos archivos para el *DataFrame* uno de entrenamiento
con la etiqueta objetivo y de prueba, sin dicha etiqueta. Se 
visualizaron estos valores para tener un panorama general de su
contenido y se determinó, mediante código, que estos archivos
no contenían datos vacíos (null).

## Importación del train_test_split
Se importó esta librería para dividir los datos en entrenamiento
y prueba, en donde se dejaron 90% para entrenar y
10% para probar. Esta división de datos fueron acompañados por
un feature adicional (la columna 'emotion'), el cual permitió que
el entrenamiento del modelo fuera más preciso.

## Vectorización
Luego de dividir los datos, se importó la librería *CountVectorizer*
a fin de vectorizar los datos y representarlos de manera numérica,
para facilitar el modelado.

## Importación y entrenamiento de *LogisticRegression*
Se importó el modelo y se lo entrenó con los datos previamente mencionados
y a continuación se creó el archivo de prueba.

## Resultados
<img width="1009" height="51" alt="image" src="https://github.com/user-attachments/assets/e0be8498-528c-463d-976c-72aab4e0784d" />
