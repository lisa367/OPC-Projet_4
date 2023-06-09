# Projet 4: Tournoi d'Echecs
***


## <b>Etape 1</b>
Créez votre répertoire local et initialisez un répertoire git avec à la commande `git init`


Puis clonez le répertoire distant : 
`git clone https://github.com/lisa367/OPC-Projet_4.git`

Déplacez-vous dans le répertoire OPC-Projet_4 et créer un sous-dossier nommé '_Databases_'.   
C'est dans ce répertoire que seront créées les bases de données au format JSON.  

Votre répertoire local devrait désormais avoir la structure suivante : 
<pre>Répertoire_local/
        | OPC-Projet_4/
                | Databases/
                | Echecs/
                        | Modele/
                                |__init__.py
                                | base.py
                                | modele.py
                        | Vue/
                                |__init__.py
                                | base.py
                                | vue.py               
                        | Controleur/
                                |__init__.py
                                | base.py
                                | controleur.py
                        | run.py
                | README.md
                | requirements.txt
</pre>
---

## <b>Etape 2</b>
Créez un environnement virtuel dans le répertoire local en utilisant la commande suivante dans le terminal : 
`python3 -m venv .env` 
<br>
<br>
Démarrer l'environnement virtuel :
`source .env/bin/activate`

---

## <b>Etape 3</b>
Assurez-vous que l'interpréteur Python sélectionné par votre éditeur de code est bien celui de l'environnement virtuel, puis installez les dépendences du projet grâce à la commande : `pip install -r requirements.txt`

Lancez le programme en exécutant le fichier run.py : `python3 Echecs/run.py`

---

## <b>Etape 4</b>

Si vous souhaitez générer un rapport flake8, déplacez-vous dans le dossier Echec depuis le terminal, puis utilisez la commande suivante : `flake8 --format=html --htmldir=flake-report`

