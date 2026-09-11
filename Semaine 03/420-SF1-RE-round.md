# La fonction round

La fonction round en python utilise l'arrondi bancaire ou l'arrondi au pair le plus proche.

* print(round(2.5, 0)) # 2.0 *
* print(round(3.5, 0)) # 4.0 *

Contrairement à l'arrondi standard (qui arrondit toujours le chiffre 5 au supérieur), l'arrondi bancaire arrondit au nombre pair le plus proche lorsque le chiffre à arrondir est exactement au milieu.

2,5 devient 2 (car 2 est pair)
3,5 devient 4 (car 4 est pair)

Cette technique permet de minimiser l'erreur d'arrondi cumulative lors du calcul de grands ensembles de données financières.