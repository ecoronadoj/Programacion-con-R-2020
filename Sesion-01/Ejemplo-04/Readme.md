# Ejemplo 4. Descarga y lectura de DataSets.

## Objetivo
- Fijar y conocer ruta de trabajo
- Lectura de ficheros CSV, locales y en repositorio
- Manejo de objetos

## Requisitos
1. R, RStudio
2. Prework

## Desarrollo
Ejecutar las líneas de comando y tratar de comprender que realiza cada parte de sus entradas

#### Se pueden obtener diversos data sets de Kaggle, visita el sitio para que te familiarices
#### La siguiente es una base de datos de los libros más vendidos en Amazon del 2009 - 2019

Obtenemos la ruta del directorio de trabajo
```R
getwd()
```
Fijando el directorio de trabajo
```R
setwd("c:/Users/User/Documents/Bedu/")
```
El comando read.csv() será util para leer fichero .csv
```R
read.csv("../Bedu/Data/bestsellers with categories.csv")
```
se puede asignar a un objeto el fichero leido anteriormente
```RR
amazon.books <- read.csv("../Bedu/Data/bestsellers with categories.csv")
```
También se puede leer el fichero directamente desde una URL
```R
amazon.books.url <- read.csv("https://raw.githubusercontent.com/ecoronadoj/Sesion_1/main/Data/bestsellers%20with%20categories.csv")
```
Calculamos la dimensión de la base de datos
```R
dim(amazon.books)
```

El tipo de objeto se puede saber utilizando class() 
```R
class(amazon.books)
```
