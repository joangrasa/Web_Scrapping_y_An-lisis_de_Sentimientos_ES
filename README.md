# Web Scrapping y análisis de sentimientos

En este proyecto, nos proponemos realizar un análisis de datos para extraer información valiosa a partir de las reviews de películas. El objetivo es acceder a una página web, recopilar estas reviews, analizar el sentimiento asociado y asignar una puntuación a cada película.

Desarrollaremos todo el trabajo en este notebook, utilizando Python como lenguaje de programación y herramientas de ETL. El proyecto se estructura en tres fases principales:

1. La primera fase se centra en la implementación de técnicas de Web Scraping para extraer datos de las reviews de la web de IMDB.

2. En la segunda fase, utilizando la librería *`BeautifulSoup`*,automatizaremos el proceso para permitir la búsqueda de cualquier película a través de la librería selenium.

3. En la tercera fase utilizaremos una **API de análisis de sentimientos** que recibirá el texto de cada review y devolverá una etiqueta de sentimiento categorizada. Transformaremos estas etiquetas en valores numéricos y comprobaremos las notas medias de la película que hemos obtenido mediante el web scrapping y el análisis de sentimientos. 

4. Finalmente, en la cuarta fase, almacenaremos los resultados en la base de datos.
