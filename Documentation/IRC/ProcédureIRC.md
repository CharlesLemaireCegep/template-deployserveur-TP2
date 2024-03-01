# Procédure d'installation du serveur IRC

#### Mise à jour du système
```
sudo apt-get update
```

#### Ajout des configurations du pare-feu et validation des accès
```
sudo apt-get update
sudo ufw allow 22/tcp
sudo ufw allow 6667/tcp
sudo ufw reload
sudo ufw status
```

#### Installation du Client IRC
```
sudo apt-get install weechat
```

#### à continuer...