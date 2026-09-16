# **Exercices supplémentaires (semaine 04)**  
   
1\) Écrivez une fonction qui calcule un rabais par rapport au montant d'achat.
- Si le montant est inférieur à 200, le rabais est de 0%.  
- Si le montant est supérieur ou égal à 200 mais inférieur à 400, le rabais est de 5%.  
- Finalement, pour tout montant supérieur ou égal à $400, le rabais est de 10%.  

Par exemple, 
print(calculer_rabais(100))  # 0
print(calculer_rabais(250))  # 12.50
print(calculer_rabais(555.55))  # 55.56
   
   
2\) Déterminer le quadrant d'un point

Demander les coordonnées (x, y) d’un point.

Afficher s’il se trouve :

- dans le quadrant I
- quadrant II
- quadrant III
- quadrant IV
- sur l’axe des x
- sur l’axe des y
- à l’origine  
   

3\) Écrire une fonction calcule le montant de l'impôt sur le revenu en fonction du revenu annuel brut (en $).

Tranches d'imposition :
- Jusqu'à 20 000 $ inclus : 0% d'impôt
- De 20 001 $ à 50 000 $ inclus : 15% sur la tranche supérieure à 20 000 $
- Plus de 50 000 $ : 4 500 $ + 25% sur la tranche supérieure à 50 000 $

def calculer_impot(revenu):
    ''' Écrivez votre code ici '''
    pass


print(calculer_impot(15000))  # Devrait afficher 0.0
print(calculer_impot(30000))  # Devrait afficher 1500.0  (15% de 10 000)
print(calculer_impot(60000))  # Devrait afficher 7000.0  (4500 + 25% de 10 000)
