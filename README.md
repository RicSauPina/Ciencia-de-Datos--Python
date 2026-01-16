# Empresa-aliada-Ciencia-de-Datos---Python
Este es un modelo de ciencia de datos durante los estudios/cursos, desarrollado con el fin de analizar/poner en práctica distintos temas vistos en varios cursos de ciencia de datos y con el uso de bases de datos prestadas de una empresa aliada se realizará un análisis y un diagnóstico predictivo.

## Descripción del proyecto
En el proyecto hay 5 diferentes archivos de jupyternotebook. Cada uno con del 0.5 al paso 3 son la división del codigo con explicaciones paso a paso de como fue que se realizo este proyecto y el final "Empresa Aliada (Codigo Completo)" Es la fusión de todos los codigos previos para hacer una demostración del codigo.

Hay distintas bases de datos en cada paso. Las orginales son los archivos DIM y FACT, pero para la división de pasos se dividio el modelo en mas bases de datos para acceso sencillo y que los proximos pasos puedan acceder al mismo.

Si estas leyendo esta parte estoy abirto a criticas y/o consejor para mejorar el modelo. 


## Objetivo del proyecto
En este proyecto se puso en practica los estudios de ciencia de datos y con el uso de una base de datos brindados por una empresa se intento hacer un analisis predictivo y conductual.

## Dataset
Se utilizaron las bases de datos de empresas de limpieza y brindaban informacion acerca de los productos, descripciones, etiquetas, ventas por zona y fechas/periodos de venta.

## ¿Qué se analizó?
Se analizo con el uso de series de tiempo la tendencia de las ventas de productos segun su categorias.

## Técnicas utilizadas
Se utilizo en este caso Fruit basket y series de tiempo para intentar analizar el comportamiento de las ventas

## Librerias utilizadas en el modelo
* Graficas 
    * Seaborn
    * Matplotlib
* Texto
   * Re
* Manipulacion de datos
   * Pandas
* Calculos algebraicos
   * Numpy
* Modelado
   * Arima
   * mlxtend

## Resultados principales
Lo que nos pudimos percatar es que aunque las predicciones eran herradas, unicamente dando una media segun un periodo de tiempo. Se pudo comprobar que las ventas iban en decadencia y si seguian el transcurso actual se espera que disminuyan a lo largo del tiempo.

## ¿Qué aprendí?
* La limpieza de datos puede parecer sencilla, pero las excepciones incrementar la dificultad.
* Es mucho mas sencillo investigar ciertas informaciónes en SQL
* Que aun con series de tiempo, una predicción exacta es sumamente complicada sin generar un sobre-entrenamiento.





