# **Exercices supplémentaires (semaine 03)**  
   
1\) Écrivez une fonction qui calcule le prix TTC (calculer_prix_ttc) en utilisant les taux de 5% pour la TPS et 9,975% pour la TVQ. La fonction doit arrondir à 2 décimales avant de retourner le prix TTC.   
   
Ne pas utiliser de variables globales svp.  
   
   
print(calculer_prix_ttc(100))    
print(calculer_prix_ttc(400))  
   
Cela devrait afficher  
   
   
114.75    
459.0  
   
2\) Modifiez le code de l'exercice du calcul de la mensualité d'un prêt en ecrivant une fonction (calculer_mensualite). Ne pas utiliser de variables globales svp.  
   
3\) Au E-U, pour la consommation des automobiles, ils utilisent le nombre de miles par gallon (us). Écrivez une fonction qui convertit de miles/gallons à l/100km.  
   
La formule est super simple,   
   
Pour convertir une consommation en miles par gallon américain (MPG US) vers des litres par 100 km (L/100 km), la formule est :  
   
L/100 km= 235,215 / MPG US    
​  
Il est important d'expliquer d'où vient le 235,215 dans notre code. Sinon, quelqu'un qui lit notre code se demandera pour le 235,215    
​  
Le nombre 235,215 est simplement :  
   
$$ \boxed{ \frac{1\text{ gallon US en litres}\times100} {1\text{ mile en kilomètres}} } $$  
   
c'est-à-dire :  
   
$$ \boxed{ \frac{3,785411784\times100}{1,609344} =235,215 } $$  
   
où 1 mile = 1,609344 et 1 gallon = 3,785411784 litres  
   
C'est donc un facteur de conversion, pas une constante propre aux automobiles.  
   
Par exemple, pour 30 MPG :  
   
$$ \frac{235,215}{30}=7,8405 $$  
   
Essayez d'écrire un commentaire qui explique cela en utilisant le """ """  
