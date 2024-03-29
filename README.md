## Elecciones-2019

**Análisis sobre el cambio de votos de las elecciones 2019 para Jefe de gobierno CABA.**

Trabajo realizado en conjunto con: Juan O’Donell, Leandro Martínez, Guido Haissiner.


Objetivo: Intentar explicar la influencia de los cambios realizados por la gestion actual y las caracteristicas de la poblacion en la variacion de voto.
¿Se ganaron votos donde se inviertio mas?
¿Se perdieron votos donde aumento la delincuencia?
¿Quienes tendieron a cambiar su voto?


![Mapa](https://user-images.githubusercontent.com/53145526/70205387-9c6d3e80-1702-11ea-88f6-5422cdf4db97.PNG)



*Mapa hecho sobre los circuitos electorales.*


* Var_votos_bool: Circuitos electorales donde el oficialismo gano o perdio votos respecto a las elecciones anteriores
* Var_votos_ofi: % de votos ganados o perdidos

**Features:**

* educ_superior: Datos tomados de https://www.estadisticaciudad.gob.ar/
* usd_m2: Precios de m2 tomados de properati, año 2015
* Obra publica: Montos gastados en obras publicas. Datos tomados de  https://data.buenosaires.gob.ar/
* Variacion de comercios
* Var_delitos: Datos tomados del mapa del delito del GCBA
* Necesidades basicas: NBI Necesidades Básicas Insatisfechas. Datos tomados de https://www.estadisticaciudad.gob.ar/

**Features importance:**
Relevancia de las features que muestran el cambio de voto por circuito

![descarga](https://user-images.githubusercontent.com/53145526/70263637-9a909300-1775-11ea-8018-97a9fb2b6620.png)

**Modelos utilizados +Grid Search**
* Random Forest
* Extra Trees
* KNN

**Comparacion de modelos**

![Captura](https://user-images.githubusercontent.com/53145526/70263936-2aced800-1776-11ea-9193-8abcebfe822e.PNG)


![descarga](https://user-images.githubusercontent.com/53145526/70263840-02df7480-1776-11ea-9648-eaff689edc82.png)



**Librerias utilizadas para mapa y ML**

numpy - pandas - matplotlib - sklearn - folium


