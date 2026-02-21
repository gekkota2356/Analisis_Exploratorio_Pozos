# 📊 Análisis Estadístico Exploratorio de Registros de Pozo
https://colab.research.google.com/drive/12chUwTYelUqrL_iqx7iP3tIlaNhlkE92?usp=sharin
g
##  Descripción del Proyecto

Este proyecto desarrolla un Análisis Estadístico Exploratorio (EDA)
aplicado a registros petrofísicos de un pozo utilizando Python en Google
Colab. El objetivo es evaluar la calidad, distribución y comportamiento
estadístico de las variables antes de realizar interpretaciones
geológicas o modelamientos más avanzados.

El análisis permite identificar patrones, valores atípicos y relaciones
entre variables, proporcionando una base sólida para estudios
posteriores en caracterización de yacimientos.

------------------------------------------------------------------------

##  Objetivos

-   Realizar limpieza y preparación de datos.
-   Calcular estadísticas descriptivas relevantes.
-   Analizar la distribución de cada variable.
-   Identificar y tratar valores atípicos.
-   Evaluar la dependencia estadística entre registros.
-   Generar visualizaciones técnicas para interpretación.

------------------------------------------------------------------------

##  Datos Utilizados

El proyecto trabaja con un archivo CSV de registros de pozo con
encabezado multinivel, que incluye:

-   Profundidad (DEPTH)
-   Variables petrofísicas numéricas
-   Valores nulos codificados como -999.25 (reemplazados por NaN)

------------------------------------------------------------------------

##  Metodología

### 1 Limpieza de Datos

Reemplazo de valores nulos codificados y filtrado de variables numéricas
para análisis estadístico.

### 2 Estadística Descriptiva

Cálculo de métricas como media, desviación estándar, rango, rango
intercuartílico (IQR), varianza, simetría y curtosis.

###  Análisis Gráfico

Generación de histogramas, boxplots y gráficos QQ para evaluar
distribución y normalidad.

###  Identificación de Outliers

Aplicación del método del Rango Intercuartílico (IQR) para detectar y
tratar valores atípicos.

###  Análisis de Correlación

Construcción de matriz de correlación (Pearson) y visualización mediante
mapa de calor.

------------------------------------------------------------------------

##  Resultados Esperados

-   Comprensión del comportamiento estadístico de cada registro.
-   Identificación de anomalías o datos extremos.
-   Evaluación de relaciones entre variables.
-   Base para modelamiento petrofísico o análisis multivariado.

------------------------------------------------------------------------

##  Herramientas Utilizadas

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   SciPy
-   Google Colab

------------------------------------------------------------------------

##  Aplicaciones

Este análisis es fundamental en caracterización petrofísica, control de
calidad de datos, modelamiento estadístico e interpretación geológica
preliminar.
