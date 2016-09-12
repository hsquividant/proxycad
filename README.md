# PROXYCAD
Proxy permettant � partir d'un seul point d'acc�s de disposer de l'int�gralit� des flux WMS (un par commune) depuis cadastre.gouv.fr.
Ce service s'utilise comme une sercice OGC de type WMS. exemple : (http://kartenn.region-bretagne.fr/ws/cadastre/france.wms?SERVICE=WMS&REQUEST=GetCapabilities)
Il est recommand� d'utiliser une cl� premium cadastre.gouv.fr : (https://www.cadastre.gouv.fr/scpc/afficherServiceWMS.do?CSRF_TOKEN=0QSM-EWVC-RJ2P-ETJA-FS83-ZWFS-GQES-BYMR)

** Pr�requis
Disposer d'une base de donn�es POSTGIS avec une couche des communes disposant des champs suivants : 
 - code INSEE
 - g�om�trie
 
 Exemple d'utilisation : (http://geobretagne.fr/mapfishapp/map/b391ec0966a3ff4da4c78bcfbc5688bf)