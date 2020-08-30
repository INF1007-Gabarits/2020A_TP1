# TP1

<!--- Changer la date de remise en modifiant le URL--->
#### :alarm_clock: [Date de remise](https://www.timeanddate.com/countdown/generic?iso=20210131T2359&p0=165&msg=Remise&font=cursive&csz=1#)

## Objectif

Ce TP à pour objectif de vous introduire à l'algorithmie avec le langage de programmation python.
Celui-ci est composé de 5 exercices différent et vous devez compléter le code à chaque fois que vous voyez l'indicateur "TODO".

## Consignes à respecter

Tout d'abord, nous vous recomandons de télécharger l'environement de développement Pycharm, dont la licen
Objectif

Modifier les casses de noms de pays afin que:

    Les mots de liaisons (ex.: and) soient en casses minuscules
    Les premières lettres de noms soient en casses majuscules

Exemple

print(capitaliser_pays('antigua ANd barbuda'))

Antigua and Barbuda
À compléter

Vous devez compléter la fonction suivante du fichier exercice.py.

def capitaliser_pays(nom):
    #TODO completer la fonction
    return nom

Connaissances utiles
Changement de casse

chaine = "Hello, World!"
print(chaine.upper())
print(chaine.lower())
print(chaine.capitalize())
print(chaine.swapcase())

HELLO, WORLD!
hello, world!
Hello, world!
hELLO, wORLD!
Remplacement de sous-chaîne (substring)

print(chaine.replace('Hello', 'Bonjour'))

Bonjour, World!
Trouver une sous-chaîne ou un charactère

# retourne le premier indice trouvé
print(chaine.find('o'))
print(chaine.find('World'))

4
7
