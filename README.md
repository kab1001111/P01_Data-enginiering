

Bernardo Mantilla
nzberman@gmail.com

Proyecto Individual

Data Engineering

Pasos del proyecto:

1. Ingesta y Transformacion de los datos. 
Mediante pandas, librería de Python especializada en la manipulación y el análisis de datos, se cargaron en Dataframes los archivos de diferentes fuentes.
Posteriorme se prosigui a hacer las "Transformaciones" correspondientes.

2. Elaboración de la API y relación de tablas
Utilizando FastAPI, se diseña el home en un ambiente virtual para facilitar las consultas del usuario, importando los dataframes trabajados del scrip "dataframe". Se relacionan las tablas mediante la ingesta de variables por parte del usuario en las consultas:

-Cantidad de veces que aparece una keyword en el título de peliculas/series, por plataforma

-Cantidad de películas por plataforma con un puntaje mayor a XX en determinado año

-La segunda película con mayor score para una plataforma determinada, según el orden alfabético de los títulos.

-Película que más duró según año, plataforma y tipo de duración

-Cantidad de series y películas por rating


3. Deployment en Deta para que pueda ser consultado por los usaurios.
