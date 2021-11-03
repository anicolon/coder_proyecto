# PROYECTO CODER HOUSE - Encuesta Continua de Hogares 2020
 
## Presentación de la organización y problema específico

La Encuesta Continua de Hogares (ECH) es una encuesta que releva información de los hogares y personas de la República Oriental del Uruguay. La misma presenta indicadores del tipo de vida de las habitantes del país como el mercado de trabajo, el nivel de pobreza y las condiciones de vida de los uruguayos además de servir como insumo de estudio para distintas entidades nacionales e internacionales.

El marco muestral es del último censo nacional (2011) y la supervisión técnica está a cargo del Instituto Nacional de Estadístoca (INE). En el año 2023 se realizará un nuevo censo que servirá como base para encuestas futuras.

A raíz de la pandemia la encuesta pasó a realizarse de forma telefónica con el fin de reducir la movilidad. En otras instancias la misma se realizaba presencial en todo el territorio nacional y por eso pueden encontrarse errores. El caso más claro es la variable de ascendencia, la cual fue eliminada de los datasets puestos a disposición del público.

Por más información se puede referir al seguiente archivo:

[Presentación ECH 2020](https://rtc-cea.cepal.org/sites/default/files/2020-12/Presentaci%C3%B3n%20Uruguay.pdf)


## Fuente del dataset y criterios de selección

El dataset de la ECH es abierto al público y se puede acceder al mismo en distintos formatos dentro de la página oficial del [INE](https://www.ine.gub.uy/encuesta-continua-de-hogares1). En este repositorio se pone a disposición el dataset en formato SPSS.

La elección de este dataset se fundamenta en el deseo de utilizar una base real, contemporánea y que pueda otorgar resultados basados en la realidad socio económica de Uruguay.

## Preguntas y objetivos de la investigación

En esta investigación buscamos determinar cuánto afecta el nivel educativo, la cantidad de hijos y otros indicadores, a la inserción en el mercado laboral de los hogares monomarentales de nuestro país. Luego de un análisis principal de la base para conocer el contexto general de la investigación, intentaremos crear un algoritmo de clasificación para entender la influencia de distintas variables categóricas en un resultado determinado.

## Filtros aplicados a los datos

La ECH 2020 cuenta con más de 300 atributos. Para el objetivo del análisis nos centraremos en aquellos que consideramos pertinentes para la exploración y el objetivo del proyecto. Los mismos refieren a nivel educativo, estado laboral, ingresos y otros. El listado se puede encontrar dentro del archivo ipynb que contiene el análisis, en la sección de importación de datos.
