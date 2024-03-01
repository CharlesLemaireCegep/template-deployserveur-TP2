# Procédure d'installation et configuration du module d'amélioration *NOM_DU_MODULE*

## Étape EXEMPLE - Préparation du pare-feu et installation du Module X

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