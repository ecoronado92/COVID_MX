# Mexico COVID Temporal Map / Mapa Temporal de COVID-19 en México

##### Check it out live at https://ecoronado92.github.io/portfolio/covid_mx.html


**EN:**

The goal of this repo is build a map similar to that published in the NYT by [Lauren Leatherby and Charlie Smart on July 2, 2020](https://www.nytimes.com/interactive/2020/07/02/us/coronavirus-cases-increase.html). It shows the evolution of COVID cases in Mexico across states and counties from Feb 2020 through early July 2020. Data is computed to present number of cases per day (CASOS) , on a rolling sum over the past 2 weeks (CASOS_14d), and it's equivalent measures for every 1000 people in each location (i.e. PER_1000).

This is for informational and visual purposes, and doesn't imply anything about the direction of the epidemic.

**ES:**

El objetivo de este repo es construir un mapa similar al publicado en el NYT por [Lauren Leatherby y Charlie Smart el 2 de julio de 2020](https://www.nytimes.com/interactive/2020/07/02/us/coronavirus-cases-aumentar.html). El mapa muestra como los casos de COVID en México han evolucionado en cada estado y municipio desde febrero del 2020 hasta principios de julio del 2020. Los datos presentan el número casos por día (CASOS), la suma de casos durante últimos 14 días (CASOS_14d), y equivalentemente contiene medidas por cada 1000 habitantes en cada localidad (e.j. PER_1000).

Este mapa es para fines informativos y visuales, y no busca demostrar tendencias de casos y/o la epidemia.


# Files / Archivos

- **data**: Folder with data used in to generate map (sources include INEGI and Mexico's Dept of Health (Secretaría de Salud))

- **covid_mx_map.ipynb**: Main notebook to generate map / Cuarderno principal para generar mapa

- **covid_mx.html**: Map HTML

- **hex_config.py**: Map configuration file / Archivo para configurar el mapa

- **test_files**: Used by KeplerGl to generate map / Utilizados por KeplerGL para generar el mapa

