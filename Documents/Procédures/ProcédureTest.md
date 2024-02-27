# Procédure de test du service *NOM_DU_SERVICE*
==Vous devez ici ajouter l'ensemble des commandes, des configurations et manipulations que vous avez fait pour tester votre technologie et voir si celle-ci fonctionne. Voici un exemple de base pour vous aide avec la syntaxe Markdown==

## Comptes utilisateurs et administrateur
| Comptes utilisateurs | mot de passe |
| -------------------- | ------------ |
| Utilisateur 1        | PassPass123  |
| Utilisateur 2        | PassPass132  |
| Utilisateur 3        | PassPass321  |
| Administrateur       | PassPass!@£  |

## Tests de la création du service ainsi que la connexion à partir de l'externe au serveur du service X

##### Ajout des configurations du pare-feu et validation des accès
```
sudo ufw allow 22/tcp
sudo ufw allow 666/tcp
sudo ufw status
```

##### Installation du Service X
```
sudo apt-get install serviceX -y
serviceX --configmenu AUTO-CONFIG ALL
sudo systemctl serviceX status
```

##### à partir d'un powershell externe au serveur
Test de ping vers le serveur de serviceX et test de connection à l'aide du service weeWoo
```
ping serviceX.exemple.com
weeWoo --connect serviceX.exemple.com --test
```

...