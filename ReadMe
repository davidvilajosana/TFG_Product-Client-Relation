README - Estructura del projecte
Aquest projecte s’ha estructurat al voltant de diversos notebooks en format Jupyter que tracten diferents etapes del procés d’anàlisi de dades orientat al màrqueting digital. L’objectiu general és aplicar tècniques de ciència de dades per extreure informació rellevant a partir del comportament de compra de clients, amb especial èmfasi en la segmentació de productes i clients, així com en l’extracció de patrons útils per a estratègies de màrqueting.

Ordre recomanat d’execució
analisi_dades.ipynb

productes.ipynb

clients.ipynb

coclustering.ipynb

anex.ipynb

Descripció de cada arxiu
analisi_dades.ipynb
Aquest notebook és el punt de partida del projecte. Aquí es realitza la càrrega del dataset original i es duen a terme totes les tasques de neteja, transformació i preparació de les dades. Entre d’altres, s’hi inclouen:

Tractament de valors nuls

Conversió de formats

Agregació de dades per producte i per client

Càlcul de variables derivades rellevants per a les anàlisis posteriors

El resultat d’aquest notebook són els arxius intermedis amb dades netes i estructurades, com df_preparat.csv, que s’utilitzen en els següents notebooks.

productes.ipynb
En aquest notebook s’analitzen els productes de manera agregada. L’objectiu és explorar el comportament de compra per producte i identificar agrupacions naturals mitjançant tècniques de clustering:

S’hi apliquen algoritmes com K-Means i PCA

Es generen agrupacions de productes segons característiques com la quantitat venuda, preu mitjà i temporalitat

Es discuteixen les implicacions d’aquestes agrupacions per a estratègies de product bundling i cross-selling

clients.ipynb
Aquest notebook se centra en l’anàlisi dels clients. A partir de les seves compres, es construeixen perfils de comportament i es duen a terme tècniques de segmentació de clients, com:

Clustering (K-Means, DBSCAN)

Anàlisi de variables com la recurrència, el valor de compra, i el cistell mitjà

Interpretació dels segments obtinguts per ajudar a personalitzar estratègies de màrqueting

coclustering.ipynb
Aquest notebook desenvolupa l’anàlisi més avançada del projecte, basada en tècniques de coclustering. L’objectiu és analitzar conjuntament la relació entre productes i clients, identificant grups de productes que tendeixen a ser comprats per grups similars de clients.

S’utilitza la matriu de co-ocurrència entre productes

Es prova l’algoritme Spectral Co-Clustering

Es planteja una aplicació pràctica d’aquests resultats per definir accions de màrqueting més precises

anex.ipynb
Aquest notebook recull visualitzacions addicionals, proves, gràfics exploratoris i comentaris extres que complementen l’anàlisi principal. També serveix com espai de treball per validar hipòtesis o explorar aspectes no integrats directament en el fil central del projecte.

