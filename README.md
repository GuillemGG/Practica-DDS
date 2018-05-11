# OMNIPRESCENSE

[cat]

El projecte tracta en fer un package de R que obtindrà informació pública a internet per alimentar un sistema de tractament de dades (ja siguin IPs, dates, dominis) que permeti interacció amb l'usuari que l'està fent servir. Per aquest package de R s'ha d'entendre els següents conceptes:
* Data scope
* Sources
* Features/Functionalities

**Data Scope**

Entenem Data Scope com a quins tipus de dades s'acceptaran en el package de R. Per començar i en funció de les complicacions del projecte, el Data Scope serà únicament adreces IP que tinguin certes dades relacionades, com pot ser (a ser posible): data, geolocalització, tipus de llista a la que pertany(campanya de malware, C&C, malware distribution, whatever),+ FALTA ACABAR DE DEFINIR.

**Sources**

Donat que el Data Scope només és IPs, farem servir la següent pàgina web per obtenir informació de diferents llistes de IPs de diferents proveïdors de seguretat:
https://iplists.firehol.org/

**Features/Functionalities**

A continuació hi ha un llistat de les posibles funcionalitats que es volen implementar:
	- Cercar en funció de la categoria (campanya concreta, anonimitzadors, distribuidor de malware,whatever)
	- Obtenir informació d'una IP en concret i veure posibles relacions properes en funció de la semblança amb altres IPs (campanya compartida, distancia del rang de IP, ASN,whatever)
	
**Conclusió final**

El package en R servirà per poder navegar en funció de les dades que tenim i poder treure conclusions sobre la maliciositat de la informació del Data Scope. Tota aquesta informació obtinguda fent servir el package en R es farà servir per realitzar un informe en que es puguin veure diferents casos com els comentat anteriorment.
