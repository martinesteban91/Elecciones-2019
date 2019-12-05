## Elecciones-2019

**Análisis sobre el cambio de votos de las elecciones 2019 para Jefe de gobierno CABA.**

Objetivo: Intentar explicar la influencia de los cambios realizados por la gestion actual y las caracteristicas de la poblacion en la variacion de voto.
¿Se ganaron votos donde se inviertio mas?
¿Se perdieron votos donde aumento la delincuencia?
¿Quienes tendieron a cambiar mas su voto?

https://guides.github.com/features/mastering-markdown/

### Mapa interactivo publicado https://lukewlodarczyk.github.io/Interactive-World-Map/

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

**Modelos utilizados +Grid Search**
* Random Forest
* Extra Trees
* KNN

Comparacion de modelos



**Librerias utilizadas para mapa y ML**

numpy - pandas - matplotlib - sklearn - folium


