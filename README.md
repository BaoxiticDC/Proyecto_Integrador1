# Proyecto_Integrador1

## Descripción

Este repositorio hace respuesta al trabajo de procesamiento de imágenes que está en este [link](https://docs.google.com/document/d/17uPzsD2PQmVAoKm4ZYjob9AIDDU_Uum0vs5Z9SrwmeA/edit)



## Arquitectura

## Guia de uso

Una vez se clona el proyecto se tienen 2 archivos principales.

- Entrega1.ipynb: Este notebook simplemente lee el dataset de la carpeta input y muestra los resultados obtenidos 
- user_input(Demo).ipynb: Este notebook se debe correr todo y responder de forma interactiva. En general las decisiones son elegir la métrica a usar y tomarse fotos para luego ver la norma de las nuevas fotos con respecto al dataset.

## Dependencias

Todo el código está hecho en python 3.7 donde además se utilizaron las siguientes librerías


- cv2 (openCV) Librería utilizada para tomar fotos y leer imágenes
- numpy Libreria utilizada para el calculo de varias distancias y el manejo de 	-	- matrices
- matplotlib.pyplot Libreria base para hacer gráficas
- seaborn  Librería para hacer gráficas estadísticas más estéticas
- sklearn Libreria importante para calcular la matriz de confusión
- skimage libreria usada para calcular el SSIM
- collections Librería que tiene una función para contar cuantos elementos de un vector cumplen una condición
- pandas: Es usada para poder cargar y guardar las distancias precalculadas para el demo.




