# <h1 align=center> **PROYECTO INDIVIDUAL -  DTS06** </h1>

<h1 align=center> Data Visualization </h1>

**¡Hola, bienvenido!** mi nombre es *Franco Soto* y este es mi último proyecto individual, que forma parte de Henry Labs. 
## Objectivos del proyecto
+ Hacer un buen análisis exploratorio de los datos (**EDA**)
+ Hacer una **WordCloud** de los títulos de los cursos
+ Hacer un **Dashboard** funcional y coherente al análisis
+ Sugerir al menos un **KPI** mediante el dashboard creado

## Contextos
Una startup de tecnología está interesada en sumarse al mercado de cursos online, pero de una manera eficiente, por ello se brindo distrintos datasets para la elaboración de una presentación y análisis del mercado. En esta ocasión para el proyecto se hizo del uso de dos datasets de las empresas de Edx y Udemy.
<div>
<img src= "https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/EdX_newer_logo.svg/1200px-EdX_newer_logo.svg.png" width="300px">
<img src="https://programadoresbrasil.com.br/wp-content/uploads/2022/03/udemy-1200x675.png" width="300px">
</div>

## Flujo de Trabajo

### EDA:
Primero se importan los datasets en Pandas, se hace el análisis exporatorio de los datos y por último se exportan los dataframes como un csv para utilizar en la elaboración del dashboard.

### Eliminación, transformación y Filtrado:
De los datasets de eliminaron los duplicados de las filas, se transformaron columnas para hacer de su uso (cambio de forma a número y fecha) y se completaron los nulos, así mismo, se depuraron columnas que a mi criterio parecieron irrelavantes, para ejemplicar una pequeña lista:
+ ID
+ Url
+ Resumenes
+ Descripciones 
+ Sílabos

### WorldCloud:
Para ello se utlizo las liberías de pandas, NLTK y matplotlib. Con pandas se extrajo los títulos de los dataframes, con NLTK se filtraron las palabras que no sé necesitaron y por último matplotlib para la creación de la imagen.

### Dashboard:
Para finalizar el proyecto se hizo en la plataforma de Power BI para la elaboración del dashboard interactivo (Ingestando los dataframes previamente mencionados) y la imagen del WorldCloud, así mismo, se incluyeron imágenes para complementar la presentación.

## Tecnologías Utilizadas
* [Pandas](https://pandas.pydata.org/)
* [Power BI](https://powerbi.microsoft.com/es-es/)
* [Matplotlib](https://matplotlib.org/stable/index.html)
* [Seaborn](https://seaborn.pydata.org/)
* [WordCloud](https://pypi.org/project/wordcloud/)
* [NLTK](https://www.nltk.org/)