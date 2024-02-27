# Procédure d'installation et configuration du service *NOM_DU_SERVICE*
==Vous devez ici ajouter l'ensemble des commandes, des configurations et manipulations pour qu'un programmeur puisse compléter votre projet du service choisi à partir de zéro. Voici un exemple de base pour vous aide avec la syntaxe Markdown==

## Étape EXEMPLE - Préparation du pare-feu et installation du Service X

##### Ajout des configurations du pare-feu et validation des accès
```
sudo ufw allow 22/tcp
sudo ufw allow 6667/tcp
sudo ufw status
```

##### Installation du Service X
```
sudo apt-get install serviceX -y
serviceX --configmenu
...
```

## Liens vers les procédures des améliorations
- [Amélioration A](/Documentation/Améliorations/ProcédureAméliorationA.md)