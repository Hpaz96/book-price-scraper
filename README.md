Book Price Scraper

Proyecto de web scraping y preparación de datos desarrollado con Python para extraer información de un catálogo de libros en línea y construir un dataset listo para análisis.

Los datos fueron obtenidos del sitio de práctica Books to Scrape, diseñado para aprender técnicas de extracción de datos.

🎯 Objetivo del proyecto

Construir un pipeline básico de obtención y preparación de datos que permita:

Extraer información desde múltiples páginas web

Transformar datos HTML en un dataset estructurado

Limpiar y preparar los datos para análisis exploratorio

Este proyecto forma parte de mi práctica en ciencia de datos y extracción de información web.

⚙️ Tecnologías utilizadas

Python

Requests

BeautifulSoup

Pandas

🔎 Metodología

El proceso de extracción se realizó mediante scraping paginado, recorriendo automáticamente todas las páginas del catálogo.

Para cada libro se extrajo la siguiente información:

Título del libro

Precio

Disponibilidad

Categoría

Página del catálogo

El proyecto implementa scraping multinivel, ya que para obtener la categoría es necesario acceder a la página individual de cada libro.

📊 Dataset generado

El dataset final contiene aproximadamente 1000 registros.

Ejemplo de estructura:

titulo	precio	disponibilidad	categoria
Book A	22.50	In stock	Travel
Book B	45.10	In stock	Mystery

Los precios fueron limpiados y convertidos a formato numérico para facilitar su análisis.

📈 Posibles análisis

Con el dataset generado es posible realizar análisis como:

Precio promedio por categoría

Distribución de precios

Libros más caros del catálogo

Disponibilidad de inventario por categoría

🚀 Posibles mejoras

Visualización de datos

Análisis exploratorio (EDA)

Almacenamiento en base de datos SQL

Automatización del proceso de scraping

👨‍💻 Autor

Proyecto desarrollado por Hugo Paz, ingeniero en computación interesado en ciencia de datos, análisis de información y automatización con Python.
