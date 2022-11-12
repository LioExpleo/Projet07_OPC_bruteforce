# Projet 7 - Résolvez des problèmes en utilisant des algorithmes en Python - OpenClassrooms
 Algorithme Force Brute.

## Principe du programme:
Les donnees d'entrées sont dans un fichier CSV avec une liste de 20 actions.
Chaque action a un cout et un bénéfice associé après 2 ans.
Le but de l'algorithme est de maximiser le choix des actions pour avoir le meilleur profit dans une limite de 500€ 
d'investissement.

les données sont déjà dans le projet. Pour une utilisation d'autres données, il suffit de remplacer les données dans
le projet par d'autres en respectant le même format et le même nom de fichier csv

## Récupération et installation du programme: 

#### I) Windows :

###### - Récupération du projet sous github à l'adresse suivante

    https://github.com/LioExpleo/Projet07_OPC_bruteforce.git

###### - mettre le projet sous un répertoire

###### Ouvrir l'invite de commande windows, et aller sous le répertoire choisi avec la commande .\...Projet07_OPC_bruteforce
    Dans Windows sous l'invite de commande, naviguer pour se retrouver sous le projet. "Projet07_OPC_bruteforce" 

###### - Créer et activer l'environnement virtuel avec :
    $ python -m venv env 
    $ ~env\scripts\activate
    
###### - Installer les paquets requis
    $ pip install -r requirements.txt

###### - Lancer le programme
    $ python bruteforce.py


-----
#### II) MacOS, Linux :
Dans le terminal, naviguer vers le dossier souhaité.

###### - Récupération du projet

    $ git clone https://github.com/LioExpleo/Projet07_OPC_bruteforce.git

###### - Activer l'environnement virtuel

    $ se déplacer pour se trouver sous le projet comme sous windows "Projet07_OPC_bruteforce"
    $ python3 -m venv env  (création environnement virtuel)
    $ source env/bin/activate (activation environnement virtuel)
    
###### - Installer les paquets requis
    $ pip install -r requirements.txt

###### - Lancer le programme
    $ python3 bruteforce.py



