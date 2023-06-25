***
_Aquest repositori correspon a la pràctica 2 de l'assignatura **Visualització de dades** del Màster universitari de Ciències de Dades (UOC)_

***

# Pràctica 2 - Visualització de dades

# Títol
Oferta i demanda de places d'estudis universitaris de grau

# Autor
* Francisco Bastida López - [fbastidal@uoc.edu](fbastidal@uoc.edu)

# Descripció del projecte

A partir de les dades que publica el Ministeri d'Educació (SIIU) s'ha analitzat les places ofertades en estudis de grau en comparació amb el nombre total d'alumnes aptes cada any a les proves d'accés a la universitat per comunitats autònomes.

Addicionalment, a partir de dades de la població de l'INE, s'ha estimat el nombre d'aptes a les proves d'accés a la universitat dels propers anys i s'ha comparat amb la tendència nacional de l'oferta de places de grau per fer una estimació de l'oferta i demanda que es produirà fins al 2028.

# Desccripció de la presentació

La presentació s'ha centrat en l'evolució històrica de totes les comunitats autònomes, permitint seleccionar un any perquè l'usuari pugui veure la situació d'Espanya en aquest any i adicionalment s'ha fet una narrativa de la previsió dels propers anys a nivell global en Espanya.

## Descripció del repositori

  * `Dades/PAU2020.xlsx`: Document amb les dades del Ministeri
  * `Dades/Poblacion.xlsx`: Document amb les dades poblacionals de l'INE
  * `Dades/Preinscripcion.xlsx`: Document amb les dades de l'oferta
  * `Dades/Estimaciones.xlsx`: Document Excel amb els càlculs d'estimacions futures
  * `/R/ETL.Rmd`: Fitxer font en R que llegeix les dades fonts, les neteja, fusiona i guarda en el fitxer `DataSet.txt`
  * `/Project/menu.html`: Pàgina HTML que fa la presentació de les dades fent servir gràfics construits en Flourish Studio

## Acceso a la presentación en línia:

* [Presentación en línia](https://fbastidal.github.io/VisualitzacioPractica2/Project/)

## Vídeo de presentació

Enllaç al vídeo de presentació de la pràctica:
