
# Siniestros Viales en Buenos Aires: Una Mirada a la Seguridad Vial en la Ciudad

![imagen presentacion](https://www.portafolio.co/files/article_new_multimedia/uploads/2023/06/16/648c7edc9fc7d.jpeg)






En la vida cotidiana, el término "siniestro vial" puede pasar desapercibido en medio del ajetreo diario, pero su impacto es innegable. Los siniestros viales, que abarcan desde colisiones automovilísticas hasta accidentes de tránsito, son acontecimientos que ocurren con una frecuencia sorprendente en nuestras carreteras y calles. En esta introducción, exploraremos la relevancia de los siniestros viales y por qué es esencial abordar este tema.

 ##  Los Siniestros Viales: Más que Números y Estadísticas

En primer lugar, es importante reconocer que detrás de las estadísticas frías y las cifras se encuentran vidas humanas, familias y comunidades enteras que se ven afectadas de manera irreversible. Los siniestros viales representan una de las principales causas de muerte en todo el mundo, cobrándose unas 100 victimas en el año 2021 solo en la ciudad de Buenos Aires. Por lo que es una preocupacion creciente para el Estado. Detrás de cada accidente hay una historia, y detrás de cada víctima hay seres queridos que sufren las consecuencias.

## Descripción del Proyecto
Este proyecto tiene como objetivo fundamental analizar datos relacionados con homicidios en siniestros viales en la Ciudad de Buenos Aires durante el período 2016-2021. A través de este análisis, se pretende generar información relevante que pueda ser utilizada por las autoridades locales para tomar medidas efectivas y reducir la cantidad de víctimas fatales en siniestros viales.


## Tecnologias y herramientas

El proyecto se desarrolló utilizando las siguientes tecnologías y herramientas: 

- [![Python](https://img.shields.io/badge/Python-3.7%20%7C%203.8%20%7C%203.9-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
- [![Pandas](https://img.shields.io/badge/Pandas-1.0%20%7C%201.1%20%7C%201.2%20%7C%201.3-green?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
- [![Power BI](https://img.shields.io/badge/Power%20BI-Latest-orange?style=for-the-badge&logo=powerbi&logoColor=white)](https://powerbi.microsoft.com/)
- [![NumPy](https://img.shields.io/badge/NumPy-1.16%20%7C%201.17%20%7C%201.18-blue?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
- [![GeoPandas](https://img.shields.io/badge/GeoPandas-Latest-green?style=for-the-badge&logo=geopandas&logoColor=white)](https://geopandas.org/)
- [![Matplotlib](https://img.shields.io/badge/Matplotlib-3.2%20%7C%203.3%20%7C%203.4-yellow?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)
- [![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.22%20%7C%200.23%20%7C%200.24-blue?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)


## Autor

- [@Aalg26](https://github.com/Aalg26)


## Metodología
La metodología empleada en este proyecto incluye las siguientes etapas:

1. Adquisición de Datos: Se obtuvo un dataset proporcionado por la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires que contenía información sobre homicidios en siniestros viales. Además, se adquirió información geoespacial sobre la ubicación de las cámaras de control vehicular en la ciudad desde fuentes confiables.

2. Preprocesamiento de Datos: Se llevó a cabo el preprocesamiento de datos utilizando Pandas para estructurar y filtrar los datos de manera adecuada. Para el dataset de cámaras, se generó un archivo GeoJSON utilizando datos geográficos.

3. Análisis Exploratorio de Datos (EDA): Se realizó un análisis exploratorio de datos en un cuaderno Jupyter para obtener información valiosa sobre los homicidios en siniestros viales, las cámaras de control vehicular y su ubicación geográfica.

## Estructura de Carpetas y Archivos

La estructura de carpetas y archivos del proyecto es la siguiente:

- dataset: Carpeta que contiene los archivos en crudo utilizados en el proyecto.

- datasetdashboard: Carpeta que almacena los datos listos para ser ingresados al dashboard.

- EDA.ipynb: Cuaderno Jupyter que contiene el Análisis Exploratorio de Datos.

- KPIs.ipynb: Cuaderno Jupyter que incluye el cálculo de los KPIs expuestos en el dashboard.

# Análisis Detallado de los Datos
## Víctimas por Género
Al analizar los datos de homicidios en siniestros viales, observamos que los hombres representan el mayor porcentaje de víctimas anuales en accidentes de tráfico. Este hallazgo podría sugerir la necesidad de implementar medidas específicas de seguridad y concienciación dirigidas a los conductores masculinos para reducir la tasa de accidentes mortales.

![victimas por genero](https://i.imgur.com/cZjtpX5.png)
## Tipos de Vehículos Involucrados
Los datos también revelan que las motocicletas son uno de los tipos de vehículos más comunes involucrados en accidentes mortales. Esto puede indicar que las políticas de seguridad vial deben centrarse en mejorar la seguridad de los motociclistas, como el uso obligatorio de cascos y la educación sobre la conducción segura de motos.

## Comunas con Mayor Riesgo
La comuna 1 se destaca como la que contiene la mayor cantidad de accidentes mortales en la Ciudad de Buenos Aires. Este hallazgo sugiere la necesidad de intensificar los esfuerzos de seguridad vial en esta área específica, como la implementación de zonas de velocidad controlada y campañas de educación vial dirigidas a los residentes de la comuna 1.
![victimas por comunas](https://i.imgur.com/aQFglUF.png)
## Cámaras de Control Vehicular
En cuanto a las cámaras de control vehicular, encontramos que la comuna 13 es la que cuenta con la mayor cantidad de cinemómetros. Sin embargo, la comuna 1 lidera en cuanto a la cantidad de cámaras con análisis de video. Esto podría indicar que la comuna 1 tiene un enfoque más avanzado en la monitorización y la aplicación de la ley en comparación con otras comunas.
![control vehicular](https://i.imgur.com/dZjzCW3.png)
## Cambios en las Muertes Anuales
Es interesante destacar que hubo una disminución en el número de muertes anuales en el año 2020. Este fenómeno podría estar relacionado con las restricciones de movilidad impuestas debido a la pandemia de COVID-19. Esto plantea la pregunta de si algunas de estas restricciones deberían mantenerse o modificarse para mantener una disminución en la tasa de accidentes mortales.
![muertes anuales](https://i.imgur.com/oHNP2vI.png)
## Meses de Mayor Riesgo
Se observa que gran cantidad de los siniestros viales mortales ocurren en el mes de diciembre. Esto podría estar relacionado con las festividades y el aumento de la movilidad durante las vacaciones. La información destaca la importancia de aumentar la vigilancia y la concienciación durante estos períodos festivos.
![muertes por mes](https://i.imgur.com/2lzvr4I.png)
## Tipos de Vías
Al analizar los tipos de vías, notamos que las autopistas muestran la menor cantidad de siniestros mortales. Esto podría deberse a una mejor planificación de la seguridad vial en las autopistas. Este hallazgo sugiere la necesidad de implementar estrategias similares en otras áreas con tasas de accidentes más altas.

# Conclusiones
El análisis detallado de los datos revela una serie de tendencias y patrones significativos en los siniestros viales en Buenos Aires. Estas conclusiones proporcionan información valiosa para las autoridades locales y pueden ayudar a guiar la toma de decisiones y la implementación de políticas de seguridad vial más efectivas. Es esencial seguir investigando y monitoreando estos datos para trabajar en la reducción de accidentes y salvar vidas en las carreteras de la ciudad

# Cómo Contribuir
Estoy dispuesto a recibir datos relevantes para el proyecto a través de mis redes sociales, como [LinkedIn](https://www.linkedin.com/in/adri%C3%A1nle%C3%B3ngracia/) y Discord. Tu contribución puede ayudar a mejorar la calidad y la precisión del análisis, lo que, a su vez, podría tener un impacto positivo en la seguridad vial en Buenos Aires.

Este análisis es solo el comienzo, y la colaboración de la comunidad puede ser fundamental para crear soluciones efectivas que salven vidas en las carreteras de la ciudad.
# Documentación

[municipio.json](https://www.ign.gob.ar/NuestrasActividades/InformacionGeoespacial/CapasSIG)

[Camaras_control_vehicular](https://data.buenosaires.gob.ar/dataset/camaras-fijas-control-vehicular)

[Poblacion Buenos Aires](https://es.wikipedia.org/wiki/Buenos_Aires)

