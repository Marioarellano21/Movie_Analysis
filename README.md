<h1>Movie Analysis</h1>

> [!NOTE]
> Este es un proyecto que pretende en base a un análisis de los datos oficiales de peliculas y tvseries generar insight de negocio para una empresa de stremaming que busca entrar al mercado. <br>

<h2>Problema del negocio</h2>

<table><tr><td> 
<p align="justify">Una plataforma de streaming para el hogar, con presencia en todo el mundo, necesita impulsar su rendimiento utilizando datos de tendencias en el sector de manera estratégica. </p>
</td></tr></table>

<h2>Tecnologías Usadas</h2>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) 

<h2>Objetivos</h2>
  
  1. <p align="justify"> ¿Cual es la evolución del rating por tipo de contenido? </p>
  2. <p align="justify"> ¿Cual es el rating promedio por género? </p>
  3. <p align="justify"> ¿Cuáles son los géneros que proporcionan mayor ROI? </p>
  4. <p align="justify"> ¿Cuáles son los países con mayor producción de contenido? </p>
  5. <p align="justify"> Pregunta 5</p>
  6. <p align="justify"> Pregunta 6</p>

<h2> Análisis Exploratorio de los Datos(EDA) </h2>

**Tiempo de duración en Minutos**

<p align="center">
  <img src="https://github.com/Marioarellano21/Movie_Analysis/assets/146877817/87e9907a-a511-45c0-9c49-42712f5baa54" alt="Tiempo de duración en Minutos" />
</p>

<p align="justify"> Encontramos valores atípiocos/extremos con cantidad de miles de minutos, por eso observamos una gráfica donde la mayor concentración de datos esta en 0 en teoría, lo que pasa es que tenemos valores extremos tan grandes que parece que esto, pero la realidad es que las peliculas suelen tener duración de entre 1 hora(60 min) a 2 horas(120min) normalmente, algunas otras suelen durar entre las 2 y 3 horas, pero estas son un poco más excepcionales, es decir si establecemos como un maximo(180min) en cuanto a minimo 15min, ya que hay series que sus capitulos rondan los 15-20min de duración, vemos como mejora el boxplot en gran medida, donde ya no observamos datos atípicos.</p>

**Estrenos porcentaje de estrenos por año/Cantidad de estrenos por año**

<p align="center">
  <img src="https://github.com/Marioarellano21/Movie_Analysis/assets/146877817/f331cb0d-923c-4ca9-88ea-f2ff64914def" alt="Tiempo de duración en Minutos" />
</p>

<p align="justify"> Podemos observar que la mayoría de las películas y series han sido producidas y estrenadas en el siglo 21, en estos ultimos 20 años se han lanzado aproximadamente unos 300mil titulos lo que representa un 62% de nuestros datos, dividos la primera decada de los 2000 con un 33% de estos lanzamientos y en la segunda epoca, en este caso incluyendo los ultimos 4 años un 29% de lanzamientos, parece que con el paso de tiemp disminuyo un poco la cantidad de producciones realizadas, como la compañia es de streaming y los tiempos van cambiando constantemente, limitaremos el análisis de las producciones entre el año 1990 hasta el presente año 2024, el resto no las consideraremos porque aunque fueron de gran impacto en su epoca, hoy en día pueden que no tengan el mismo impacto debido a los grandes cambios culturales que hemos tenido en estas dos ultimas decadas.</p>

**Distribución del promedio del ranking/Boxplot Cantidad de votos**

<p align="center">
  <img src="https://github.com/Marioarellano21/Movie_Analysis/assets/146877817/d7e1d60d-e202-421f-8dd9-6fe553536004" alt="Tiempo de duración en Minutos" />
</p>

<p align="justify"> Encontramos que la mayoría de las Producciones tienen un ranking de entre 6 y 8 aproximadamente, aquí se concentran aproximadamente la mayoría de los datos en el histograma. Observamos que es difícil ver producciones con ratings de 1, 2, 3 y e incluso 4, pero las hay.</p>

<h2>Insights</h2>

<h3>Pregunta 1: ¿Cuál es la evolución del rating por tipo de contenido?</h3>

<p align="center">
  <img src="https://github.com/Marioarellano21/Movie_Analysis/assets/146877817/14672613-7382-4201-862d-96442b75fff6" alt="EVOLUCIÓN RATING" />
</p>

<p align="justify"> El análisis del contenido indica que históricamente el público consume más películas que series de TV.</p>
  
<p align="justify">El público prefiere más las series deTV con un rating superior a los 7 puntos hasta los 7.4. En cuanto a las películas tuvo una subida desde el 2020 hasta el 2023 a un promedio de 6,4.</p>

<p align="justify">Desde el 1990 se han producido muchas más películas que series de TV.</p>

**RECOMENDACIONES**

<p align="justify">Recomendamos invertir en contenido con un rating promedio de 6 en adelante en películas y en series desde 6.8 en adelante, por ultimo se recomienda que la proporción sea 80% películas y 20% series.</p>

<h3>Pregunta 2: ¿Cual es el rating promedio por género?</h3>
<p align="center">
  <img src="https://github.com/Marioarellano21/Movie_Analysis/assets/146877817/433790e5-be65-437c-bcea-8ac177e9f062" alt="RATING PROMEDIO POR GENERO" />
</p>

<p align="justify"> El análisis de los géneros nos indica que el público prefiere contenidos relacionados a Documentales, Guerra, Talks Show, Romance y Acción.</p>
  
<p align="justify">Sin embargo, son contenidos con pocas producciones, por tanto, no es un nicho explorado y explotado.</p>

**RECOMENDACIONES**

<p align="justify">Recomendamos invertir en estos contenidos, pero teniendo en cuenta ciertos parámetros como el rating, en el caso por ejemplo del Talks Show, esto es un tipo de tvserie, es recomendable invertir como se vio anteriormente en aquellas con ranking superiores a los 6.8, por supuesto esto no será el límite, también recomendamos invertir en las demás categorías sólo que la inversión tiene que ser menor y más selectiva.</p>

<h3>Pregunta 3:  ¿Cuáles son los géneros que proporcionan mayor ROI?</h3>
<p align="center">
  <img src="https://github.com/Marioarellano21/Movie_Analysis/assets/146877817/98cb6322-7c16-4eff-a960-40ddb86c577b" alt="ROI POR GENERO" />
</p>

<p align="justify"> El análisis del ROI nos indica que los géneros relacionados con Aventuras, Ciencia Ficción, Acción y Fantasía son los que generan mayor Roi.</p>
  
<p align="justify">Seguidos de cerca por los géneros de Misterio, Animación y Romance.</p>

**RECOMENDACIONES**

<p align="justify">Invertir en las producciones de estas categorías que generaron más dividendos, las que fueron más vistas por el público y que tenga un rating superior a 6.4, teniendo en cuenta que como observamos, aunque estás generan más ROI no son las que más se buscan cuando tenemos en consideración el insight anterior.</p>

<h3>Pregunta 4:   ¿Cuáles son los países con mayor producción de contenido?</h3>
<p align="center">
  <img src="https://github.com/Marioarellano21/Movie_Analysis/assets/146877817/4dafeb05-dbfe-4517-b74a-4f8645f54140" alt="PAÍSES QUE MÁS PRODUCEN" />
</p>

<p align="justify"> El país con la mayor producción de contenidos es USA y el Reino unido sin embargo observamos que su ROI suele rondar entre 0.8 y 1 mientras que países como China, Japón y la India, producen mucho menos contenido y generan mayores ganancias con respecto al presupuesto invertido.</p>

**RECOMENDACIONES**

<p align="justify">Como sugerencia al negocio proponemos seguir adquiriendo y sumando a la plataforma series y películas de países como USA y UK en mayor medida, pero dejando un espacio para traer contenido de China, India y Japón realizando primero un estudio del contenido a traer, basados en los géneros y tomar una muestra de individuos primero, que hagan una evaluación del contenido para ver si es de calidad para el consumidor de la plataforma.</p>

