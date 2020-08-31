# TP1

<!--- Changer la date de remise en modifiant le URL--->
#### :alarm_clock: [Date de remise](https://www.timeanddate.com/countdown/generic?iso=20210131T2359&p0=165&msg=Remise&font=cursive&csz=1#)

## Objectif

Ce TP à pour objectif de vous introduire à l'algorithmie avec le langage de programmation python.
Celui-ci est composé de 5 exercices différent et vous devez compléter le code à chaque fois que vous voyez l'indicateur "TODO".

## Consignes à respecter

Tout d'abord, assurez-vous d'avoir lu le fichier instruction.md et d'avoir télécharger le fichier main.py que vous devrez completer.
Pour ce TP certaines contraintes sont a respectés:
- Vous ne pouvez pas importer d'autre librairies
- Il est interdit de manipuler des chaines de caractère.
- Il est interdit d'utiliser les structures de répetitions(for, while, etc.) 

## Exercice 1:
Dans cet exercice vous devez calculer l'énergie cinetique d'une voiture. Le programme commence en demandant à l'utilisateur de saisir la masse et la vitesse de la voiture, il suffit de compléter la fonction "calculerEnergie".
```python
    def calculerEnergie(masse,vitesse):
        # TODO convertir la vitesse en metre par seconde, assigner la valeur à la variable "vitesse"
        vitesse=
        
        # TODO calculer l'energie cinetique, assigner la valeur à la variable "energieCinetique"
        energieCinetique=
        
        return energieCinetique
```

## Exercice 2:
Dans cet exercice vous devez résoudre une equation quadratique de la forme <img src="https://render.githubusercontent.com/render/math?math=ax^2"> + <img src="https://render.githubusercontent.com/render/math?math=bx"> + <img src="https://render.githubusercontent.com/render/math?math=c">. Le programme commence en demandant à l'utilisateur de saisir a,b,c il suffit de compléter la fonction "resoudreEquation".
```python
    def resoudreEquation(a, b, c):
    # TODO: Calculer le discriminant et assigner la valeur dans la variable "delta"
    delta =

    # TODO: Déterminer la condition (bool) qui correspond à aucune solution de l'équation et mettre la valeur dans la variable "naPasDeSolution"
    naPasDeSolution =

    if naPasDeSolution:
        # ces ligne de code seront executé si il y'a aucune racine
        # TODO: afficher sur l'écran "Aucune racine"

        # ne pas modifier
        return None

    # TODO: Déterminer la condition (bool) qui correspond à une unique solution de l'équation et mettre la valeur dans "aUneSeuleSolution"
    aUneSeuleSolution =

    if aUneSeuleSolution:
        # ces ligne de code seront executé si il y'a une seule racine
        # TODO: afficher sur l'écran "Une seule racine"

        # TODO: assigner a la variable x1 la valeur de la racine
        x1 =
        # ne pas modifier
        return x1

    # TODO: Déterminer la condition (bool) qui correspond à deux solutions de l'équation et mettre la valeur dans "aDeuxSolutions"
    aDeuxSolutions =

    if aDeuxSolutions:
        # TODO: afficher sur l'écran "Deux racines"

        # TODO: calculer la prmiere racine, assigner la a "x1"
        x1 =

        # TODO: calculer la deuxieme racine, assigner la a "x2"
        x2 =

        # ne pas modifier cette ligne
        return x1, x2
```
## Exercice 3:
Dans cet exercice vous devez calculer le nombre de chiffre qui compose un nombre indiquez par l'utilisateur. Cepandant vous pouvez uniquement utiliser les fonctions de la libraire Math.
```python
    def calculerNombreChiffres(nombre):

        # TODO: Déterminer le nombre de chiffres de "nombre" et mettre la valeur dans "nombreDeChiffres"
        nombreDeChiffres =

        # TODO: Afficher la valeur de "nombreDeChiffres"

        return nombreDeChiffres
```
## Exercice 4:
Dans cet exercice vous devez convertir des secondes en nombres d'annés,semaine,jours,heures,minute et secondes. Par exemple si l'utilisateur rentre le le chiffre '633323104' votre programme devra renvoyé 20 années, 4 semaine, 2 jours, 3 heures, 5 minute et 4 seconde. Vous pouvez allouer de nouvelle variables pour vous aider.
```python
    def decomposer(secondes):
        # TODO: Assigner à la variable "annees" le nombre d'années
        annees =

        # TODO: Assigner à la variable "semaines" le nombre de semaines restantes
        semaines =

        # TODO: Assigner à la variable "jours" le nombre de jours restants
        jours =

        # TODO: Assigner à la variable "heures" le nombre d'heures restantes
        heures =

        # TODO: Assigner à la variable "minute" le nombre de minutes restantes
        minutes =

        # TODO: Assigner à la variable "secondes" le nombre de secondes restantes
        secondes =

        # TODO: Afficher le nombres d'années, semaines, jours, heures, minutes et secondes
        print(annees ,semaines ,jours ,heures ,minutes ,secondes)

        return (annees ,semaines ,jours ,heures ,minutes ,secondes)
```
## Exercice 5:
Dans cet exercice vous manipulerez les nombres complexes. Vous devez completez deux fonctions, la fonction trouverModule() qui retourne le module d'un nombre complexe et la fonction effectuerRotation() qui effectue une rotation du nombre complexe selon un angle saisit par un utilisateur. Rappel, pour effectuer une rotation d'un angle <img src="https://render.githubusercontent.com/render/math?math=\alpha">, il suffit de multiplier le nombre complexe par par <img src="https://render.githubusercontent.com/render/math?math=(cos(\alpha)"> + <img src="https://render.githubusercontent.com/render/math?math=sin(\alpha)i)">.
Voici les deux fonctions à compléter:
```python
        def decomposer(secondes):
            def trouverModule(nombreComplexe):
            # TODO: Calculer le module du nombre complexe et l'assigner dans "module"
            module =

            return module
```
```python
        def effectuerRotation(nombreComplexe, angle_rotation, trouverModule):

            module = trouverModule(nombreComplexe)
            angle = trouverAngle(nombreComplexe)

            # TODO: Afficher le module et l'angle du nombre complexe (3 decimales de précision)


            # TODO: Calculer le nouveau nombre complexe après rotation, assigner le nouveau nombre complexe à la variable 'resultat'

            resultat =

            nouveauModule = trouverModule(resultat)
            nouvelAngle = trouverAngle(resultat)

            # TODO : Afficher le nouveau module et le nouvel angle du nombre complexe après rotation (3 decimales de précision)
            print("Après rotation, le module reste : {:.3f} et le nouveau angle est {:.3f}".format(nouveauModule, nouvelAngle))

            return resultat
```
Si votre programme à été correctement écrit, vous devriez voire une simulation visuelle du nombre complexe avant et apres rotation.

