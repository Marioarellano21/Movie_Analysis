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
  6. <p align="justify"> Pregunta 6/p>

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
