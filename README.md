# MANUEL QGIS POUR LA VECTORISATION DE L’USAGE DES SOLS ET LE GEOREFERENCEMENT DES MINUTES 1:40 000 DE LA CARTE D’ETAT-MAJOR

Manuel réalisé par Etienne Pfister, en stage de master 2 en 2017 et son tuteur Julien Guilloux, chargé de mission forêt au Parc 
national des Ecrins.

[link to Google!](http://google.com)

- Ce manuel vient en complément du [manuel de l'INRA](http://www.foretsanciennes.fr/wp-content/uploads/2012/12/Fabvre-al-2011-digitalisation.pdf), qu'il convient de consulter pour avoir une vision complète du contenu des cartes d'état-major. Nous adressons nos remerciements particuliers à Jean-Luc Dupouey de l'INRA Nancy et à Alain Gervaise, en charge du produit BD Carto® Historique état-major à l'IGN.

- Ce manuel s'intéresse aux aspects techniques de la numérisation des cartes d'état-major avec [QGIS](https://www.qgis.org). La version 
2.18 (« Las Palmas ») de QGIS a été utilisée. Comparé au manuel INRA, proposé pour ArcGIS, nous ajoutons le volet numérisation 
semi-automatique en utilisant le plugin [Historical Map](https://github.com/lennepkade/HistoricalMap). Que les réalisateurs de ce 
plugin soient grandement remerciés : sans l’aide précieuse et les conseils de [Nicolas Karasiak](https://github.com/lennepkade), 
ce travail n’aurait certainement pas été possible. 

- Le plugin Historical Map est issu des travaux techniques de Pierre-Alexis Herrault, David Sheeren, Mathieu Fauvel et Martin Paegelow,  
résumé dans l'article Vectorisation automatique des forêts dans les minutes de la carte d’Etat-Major du 19e siècle. 
Revue Internationale de Géomatique, Lavoisier, 2015, 25 (1), pp.35-51. 
Article disponible sur le [portail HAL de l'Université Toulouse 2 - Jean Jaurès](https://hal-univ-tlse2.archives-ouvertes.fr/hal-01513411/document)

- La méthode présentée dans ce manuel se limite à la vectorisation de la classe d'occupation du sol « forêt ». En effet, ce manuel 
a été construit durant les phases de numérisation des forêts anciennes du parc national des Ecrins. Par extension, la cartographie 
des autres classes d'occupation du sol (agriculture, prairies, etc.) se fera selon la même méthode.

- Nous encourageons les utilisateurs de ce manuel à prendre contact avec les auteurs afin de contribuer à l’homogénéisation de la 
digitalisation de la carte d’état-major dans diverses régions de France. Nous serions aussi intéressés par des retours des utilisateurs 
sur les difficultés rencontrées avec cette méthode QGIS. De même, les avancés de QGIS (nouvelles versions, amélioration des fonctions etc.)
pourraient rendre certains traitements encore plus faciles.

Les 2 modèles cités dans le manuel (chapitre 5) sont disponbibles en téléchargement dans le répertoire [MODELS](https://github.com/PnEcrins/Manuel-QGIS-Forets-Anciennes/tree/master/MODELS). Merci à [Nicolas Karasiak](https://github.com/lennepkade) pour la mise à disposition de ces modèles. 
