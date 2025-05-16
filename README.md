# ml_car_price_predictor
Proyecto de Machine Learning para la predicción del valor de mercado de autos usados, desarrollado para la aplicación de Rusty Bargain. ***Proyecto desarrollado como evaluación final del Sprint Métodos numéricos del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
El servicio de venta de autos usados Rusty Bargain está desarrollando una aplicación para atraer nuevos clientes. Gracias a esa app, puedes averiguar rápidamente el valor de mercado de tu coche. Tienes acceso al historial: especificaciones técnicas, versiones de equipamiento y precios. Tienes que crear un modelo que determine el valor de mercado. A Rusty Bargain le interesa:

- la calidad de la predicción;
- la velocidad de la predicción;
- el tiempo requerido para el entrenamiento

## Objetivo del proyecto
1. Hacer prueba de cordura con regresión lineal
2. Optimizar los hiperparametros de un modelo de:
    1. Bosque aleatorio
    2. Potenciación de gradiente usando LightGBM y Catboost
3. Evaluar los modelos con la métrica RECM

## Modelos de machine learning creados
- Linear Regression
- Decission Tree Regressor
- Random Forest Regressor
- Light GBM Regressor

## Librerías principales utilizadas
- pandas
- matplotlib
- seaborn
- numpy
- sklearn
- lightgbm

## Resultados
- Se probaron 3 modelos (árbol de decisión, bosque aleatorio y GBM) y 1 como prueba de cordura (regresión lineal).
- La prueba de cordura con el modelo de regresión lineal fue exitosamente superada, pasando de una RECM de 0.605 a 0.497 con el modelo ajustado GBM, lo que representa una optimización del error de 18%.
- Se definió el modelo LightGBM como el más adecuado para la predicción de precios en la app de Rusty Bargain.
- En el archivo "Proyecto 13" se puede encontrar el desarrollo completo del proyecto, desdel el EDA hasta la optimización de los modelos predictivos. 
