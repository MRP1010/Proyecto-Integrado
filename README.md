# Data-Driven Success: Análisis Predictivo de Éxito en la Industria del Videojuego
Proyecto Integrado.- Trabajas para la tienda online Ice que vende videojuegos por todo el mundo. Las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation). Tienes que identificar patrones que determinen si un juego tiene éxito o no.

Descripción de datos:

— Name (Nombre)

— Platform (Plataforma)

— Year_of_Release (Año de lanzamiento)

— Genre (Género) 

— NA_sales (ventas en Norteamérica en millones de dólares estadounidenses) 

— EU_sales (ventas en Europa en millones de dólares estadounidenses) 

— JP_sales (ventas en Japón en millones de dólares estadounidenses) 

— Other_sales (ventas en otros países en millones de dólares estadounidenses) 

— Critic_Score (máximo de 100) 

— User_Score (máximo de 10) 

— Rating (ESRB)

## Objetivo – ¿Qué problema resolviste con datos?

El objetivo principal fue mitigar el riesgo y la incertidumbre en la planificación de marketing y desarrollo de la tienda online Ice.

Se resolvió la necesidad de inversión al:

 Identificar patrones clave (plataformas, géneros, críticas) que impulsan las ventas de videojuegos.

 Generar un pronóstico de mercado para el próximo año (2017) basado en tendencias recientes (2013-2016).

Esto permite a la empresa enfocar recursos de publicidad en los juegos y regiones con mayor potencial de éxito.

## Tecnologías Usadas

El análisis se desarrolló completamente en Python, utilizando el siguiente stack de herramientas:

 ### Análisis de Datos   » Python    Lenguaje principal de programación.

 ### 

## Metodología – Pasos y Enfoque

Se adoptó un enfoque de análisis exploratorio segmentado, centrado en el período más relevante (2013-2016) para la toma de decisiones, ya que las tendencias históricas anteriores perdieron vigencia.

 1. Analisis y Limpieza de Datos (Data Wrangling):

    » Estandarización de nombres de columnas (minúsculas).

    » Manejo de valores ausentes, incluyendo la corrección de valores 'tbd' a NaN en user_score para el análisis numérico.

 2. Ingeniería de Características (Feature Engineering):

     » Creación de la columna total_sales (ventas globales).

 3. Análisis Exploratorio de Datos (EDA) y Segmentación:

     » Análisis de la vida útil de las plataformas (media de 7.6 años).

     » Identificación de las Plataformas Top 5 y los Géneros más rentables en el periodo de estudio.

     » Análisis de la correlación entre las puntuaciones de críticos/usuarios y las ventas.
 
 4. Análisis Regional y Pruebas Estadísticas:

     » Segmentación de las preferencias de plataformas y géneros en Norteamérica (NA), Europa (EU) y Japón (JP).

     » Pruebas de hipótesis para validar si las medias de ventas son estadísticamente diferentes entre regiones y géneros.

# CONCLUSIÓN 

El análisis nos permitió ver de forma más visible las tendencias y los valores que específicos que nos permitirán planificar campañas publicitarias más exitosas. Ya que conocemos cuales son las estadísticas de venta por consolas, región, rating y géneros preferido por nuestras audiencias.

Cabe recalcar que el mercado a cambiado bastante como pudimos ver tuvimos un auge del 2006 a 2011 y del 2012 en adelante bajan las ventas casi un 50% y se han mantenido. Es por eso que nuestro análisis de dividió en dos con la muestra completa y con muestra recortada que nos permitiera analizar nuestra actualidad y del mercado. Decidimos recopilar datos de los últimos 5 años para elaborar un pronóstico para 2017, ya que consideramos que serían los más relevantes para nuestra situación en 2017.

