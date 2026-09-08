# **Exercices supplémentaires**

- 1\) On vous demande d’écrire un programme qui permet de saisir un nombre entier et qui retourne le nombre minimum de coupures ($20, $10, $5, $2 et $1). Un rappel que l’instruction input retourne une chaine même si on saisit « 16 ». Il faut convertir en entier.

Par exemple :

Quel est le montant? 16

0 x$20

1 x$10

1 x$5

0 x$2

1 x$1

Quel est le montant? 58

2 x$20

1 x$10

1 x$5

1 x$2

1 x$1

- 2\) Écrivez une petite calculatrice de taxes. Saisir un nombre flottant (montant initial), un rabais (valeur entière qui représente un pourcentage) et calculer la TPS (5%), la TVQ (9,975%) et le montant final. Ne pas oublier que le séparateur décimal en python est le point « . ».

Essayez d’utiliser « print(f"… {variable:.2f}")

Quel est le montant? 120

Quel est le rabais? 15

Montant initial: 120.00

Montant après rabais: 102.00

TPS: 5.10

TVQ: 10.17

Montant final: 117.27

Utiliser « round » après chacun des calculs.

- 3\) Écrivez un programme qui calcule la moyenne de trois valeurs numériques et qui l’affiche avec une seule décimale

Quel est la valeur #1? 4.5

Quel est la valeur #2? 6.1

Quel est la valeur #3? 7.8

La moyenne des valeurs est 6.1

- 4\) Calcul d’un prêt

Pour calculer la mensualité d'un prêt, vous devez utiliser la formule mathématique qui intègre le capital emprunté, le taux d'intérêt et la durée du remboursement.

**La formule de calcul**

La formule pour trouver le montant de chaque versement mensuel (m) est la suivante :

$$
m\mathrm{=}\frac{\mathrm{M \times(}\frac{t}{12}\mathrm{)}}{1-{(1+ \frac{\mathrm{t}}{\mathrm{12}})}^{-n}}
$$

- **M** : Le montant total emprunté (le capital).
- **t** : Le taux d'intérêt annuel (exprimé en décimal, par exemple 5 % devient 0,05).
- **n** : Le nombre total de mois de remboursement (nombre d'années multiplié par 12).

**Les éléments indispensables à connaître**

- **Le capital emprunté (M)** : La somme d'argent demandée à la banque ou à l'institution financière.
- **Le taux d'intérêt annuel (t)** : Le pourcentage facturé par le prêteur pour l'emprunt. Il est divisé par 12 pour obtenir un taux mensuel.
- **La période d'amortissement (n)** : La durée totale prévue pour rembourser l'intégralité du prêt en mois ou en années.

Le montant du prêt? 1000

Le taux d'intérêt? 5

Le nombre d'années? 1

Le montant à payer par mois est $85.61

Le montant du prêt? 20000

Le taux d'intérêt? 6

Le nombre d'années? 5

Le montant à payer par mois est $386.66
