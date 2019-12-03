## Elecciones-2019

Análisis sobre el cambio de votos de las elecciones 2019 para Jefe de gobierno CABA.


### Mapa interactivo publicado https://lukewlodarczyk.github.io/Interactive-World-Map/

*italic*Mapa hecho sobre los circuitos electorales.*italic*


* Var_votos_bool: Circuitos electorales donde el oficialismo gano o perdio votos respecto a las elecciones anteriores
* Var_votos_ofi: % de votos ganados o perdidos

Features:

* educ_superior: 
* usd_m2: Precios de m2 tomados de properati, año 2015
* Obra publica: Montos gastados en obras publicas. Datos tomados de  https://data.buenosaires.gob.ar/
* Variacion de comercios
* Var_delitos: Datos tomados del mapa del delito del GCBA
* Necesidades basicas

Features importance:
Relevancia de las features que muestran el cambio de voto por circuito

Modelos utilizados +Grid Search
* Random Forest
* Extra Trees
* KNN

Librerias utilizadas para mapa y ML

*numpy 
*pandas 
*matplotlib
*sklearn
*


