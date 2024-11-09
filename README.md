# Indialista: Herramienta para ayudarte a encontrar casa en la India

## Descripción del proyecto

**Indialista** es una herramienta diseñada para ayudar a individuos, parejas y familias a encontrar la sociedad y el rango de precios de pisos en la India, según sus necesidades. Este proyecto realiza una exploración exhaustiva del precio medio de los pisos en función de diferentes características, con el objetivo de brindar una guía detallada sobre las opciones disponibles en el mercado inmobiliario indio.

## Estructura del proyecto

El proyecto está organizado en las siguientes carpetas y archivos:

- **data/original_data.xlsx**: Archivo con los datos originales de precios de pisos en India, el cual incluye detalles de cada propiedad (ubicación, tamaño, número de habitaciones, baños, antigüedad, etc.).
- **data/eda_data.xlsx**: Archivo que contiene el análisis exploratorio de datos (EDA), incluyendo estadísticas descriptivas y visualizaciones iniciales.
- **data/final_dashboard.xlsx**: Archivo que presenta las tablas dinámicas y el dashboard final, destacando insights clave obtenidos durante el análisis.

## Requisitos

Para visualizar y utilizar los archivos proporcionados, es necesario contar con:
- **Microsoft Excel 2016 o superior**

## Resultados y Conclusiones

- Se realizó un análisis exploratorio de datos (EDA) para obtener una visión general de las propiedades de los pisos en India.
- Se exploraron correlaciones entre distintas variables y el precio de los pisos.
    - En general, las correlaciones fueron positivas para la mayoría de los casos.
    - La antigüedad de los pisos mostró una discrepancia importante; los pisos más nuevos no siempre son los más caros.
    - La mayoría de características como el nivel de lujo, número de baños, habitaciones y superficie tienen una correlación positiva con el precio.
    - Los áticos o pisos en niveles superiores también presentan una correlación positiva con el precio.

## Próximos pasos

- Desarrollar un dashboard interactivo que permita al usuario:
    - Ajustar el tiempo de pago de la hipoteca.
    - Seleccionar y filtrar propiedades según las características deseadas.
    - Evaluar opciones de pisos según preferencias personalizadas para optimizar la búsqueda de la vivienda ideal.
