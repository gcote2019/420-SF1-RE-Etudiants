# **Les chaines (partie 1)**

Le livre ne couvrent vraiment les chaines qu’au chapitre 12.

Ce document essaie de résumer la base des chaines. La partie plus avancée sera couverte par un autre document.

Les chaines permettent de manipuler du texte. Le texte est toujours entouré par des guillemets anglais ou des apostrophes.

nom = "Paul"\
nom = 'Paul'\
print(type(nom))

Cela affichera \<class 'str'> ce qui veut dire que c’est une string (chaine)

Il est possible de créer une chaine en mettant plusieurs chaines bout à bout (concaténation)\
salutations = "Bonjour tout le monde"\
\# ou\
salutations = 'Bonjour' + ' ' + 'tout' + ' ' + 'le' + ' ' + 'monde'\
\# Le + mets les chaines bout à bout.\
print(salutations)

age = 17 # un entier\
\# print nous permet d’utiliser des variables qui ne sont pas des chaines\
print(nom, 'a', age, 'ans')\
\# print convertit age en chaine

\# mais il n’est pas possible de le faire avec des +\
chaine = nom + ' a ' + age + ‘ ans’ ## pas possible, cela retournera une erreur

Il faut convertir age en string

chaine = nom + ' a ' + str(age) + ‘ ans’ # ça marche

## f-string

Il existe une façon plus naturelle de créer des chaines. Cela nous permet d’insérer des variables directement dans la chaine.

On écrit la phrase naturellement mais ça débute par un f" au lieu d’un simple ".

chaine = f"{nom} a {age} ans"

Le bout de code {nom} sera remplacé par le contenu de la variable nom. Même chose pour {age]. On n’a pas à convertir age en utilisant str(age). Le f-string s’en occupe.

Cela peut même être une expression arithmétique.

print(f"Le résultat de 5 + 10 est égal à {5 + 10}")

## Formater des valeurs numériques avec les f-strings

Par exemple, si on a

valeur = 10.124567

et qu’on veut formatter avec deux décimales, on va écrire

print(f"La valeur vaut {valeur:.2f}")

\# avec 4 chiffres significatifs\
print(f"La valeur vaut {valeur:.4g}")

C’est l’équivalent d’écrire

print(f"La valeur vaut {format(valeur, ".4g")}")

Vous pouvez voir plus d’information [ici](https://www.w3schools.com/python/python_string_formatting.asp).
