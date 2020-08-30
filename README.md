# À compléter

<!--- Changer la date de remise en modifiant le URL--->
#### :alarm_clock: [Date de remise](https://www.timeanddate.com/countdown/generic?iso=20210131T2359&p0=165&msg=Remise&font=cursive&csz=1#)

[Voir le guide pour rédiger en Markdown](https://guides.github.com/features/mastering-markdown/)
Capitalisation de noms de pays

Avant de commencer. Consulter les instructions à suivre dans instructions.md
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
