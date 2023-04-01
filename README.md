# Análisis de precios de inmuebles publicados en un portal venezolano

## 1) Web scraping

El web scraping fue hecho utilizando requests y BeautifulSoup, para luego hacer un limpiado preliminar con pandas. Este proceso está en [este notebook](https://github.com/jmartinelena/propiedades-venezuela/blob/main/web_scraping.ipynb) y su resultado son las dos tablas CSV.

## 2) Análisis de datos

Se hace un análisis de las distrubuciones de las variables por si solas, y la relación de las variables numéricas, ordinales y categóricas con el precio de los inmuebles. El análisis se hizo con pandas, NumPy, SciPy y se graficó con Matplotlib. Este proceso está en [este notebook](https://github.com/jmartinelena/propiedades-venezuela/blob/main/data_analysis.ipynb).

## 3) Machine learning

Una vez analizada la información, se procede a entrenar modelos predictivos con el objetivo de estimar el precio de los inmuebles. Esto podría servir para predecir inmuebles por publicar, o para analizar que tan buena oferta es un inmueble ya publicado. Este proceso está en [este notebook](https://github.com/jmartinelena/propiedades-venezuela/blob/main/machine_learning.ipynb) y su resultado son los dos modelos en formato pickle.
