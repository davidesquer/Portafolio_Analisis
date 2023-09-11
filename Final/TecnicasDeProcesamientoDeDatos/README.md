# Análisis y Preparación de Base de Datos de Precios de Autos

Este repositorio contiene un análisis exploratorio y preparación de una base de datos de características de automóviles y sus precios asociados.

## Contenido

1. `precios_autos.csv`: Conjunto de datos original que contiene características y precios de automóviles.
2. `precios_autos_Diccionario.xlsx`: Diccionario de datos.
3. `analisis.ipynb`: Jupyter Notebook con todo el análisis y preparación de datos.

## Proceso

### Exploración de Datos

- Se leyó el conjunto de datos desde `precios_autos.csv`.
- Se calcularon estadísticas descriptivas para variables cuantitativas y categóricas.
- Se realizaron visualizaciones (boxplots, histogramas, y diagramas de barras) para entender la distribución y relaciones en los datos.

### Preparación de Datos

- Se seleccionaron características importantes basadas en el análisis exploratorio.
- Se manejaron valores atípicos reemplazándolos con los percentiles 1 y 99.
- Se transformó la variable `fueltype` en una variable dummy.
- Se escaló el conjunto de datos utilizando el método Min-Max.
