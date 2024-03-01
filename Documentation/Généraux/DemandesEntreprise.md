# Demandes de l'entreprise
Dans le cadre du projet, pour des raisons mystérieuses vous demandant de respecter les conditions suivantes pour l'acceptation de votre travail:

### Votre service doit être
- Un logiciel Libre et Open-Source à 100%
- doit être hébergé à 100% sur votre VPS
- Répondre au paradigme Client-Serveur
  - on peut s'y connecter avec un client distant, même s'il y a déjà un client web
- L'exécution doit être permanente sur le serveur
  - écoute sur un port 
  - soit un service *deamon*, utilisé avec la commande service
  - soit un logiciel qui se lance en ligne de commande que l'on rendra permanent

### Votre service not doit pas être
- Un jeu vidéo
- Un site-web (CMS)

Il peut être toutefois accompagné d'un service en ligne / client web!


## Services possibles

### Service de discussion ou de messagerie
- Service de discussion
  - Matrix 
  - Prosody
  - Signal
- Serveur de courriel
  - Postfix + un webmail (Rainloop, Squirrelmail, Bluemail)
- Serveur de newsletter
  - mailman
  - sympa
  - mjml
  - postfix
  - sendmail

### Service de gestion de fichiers, données ou médias
- Serveur de fichiers
  - NextCloud
  - OwnCloud
  - SeaFile
  - Samba
- Serveur de médias ou de streaming
  - Jellyfin
  - Navidrome
  - VLC
- Serveur de base de données
  - PostgreSQL
  - MongoDB
  - Redis
  

### Service de code ou de transactions
- Serveur de versionnement + Serveur de Devops
  - Git
  - Subversion
  - Mercurial
  - Gitlab
  - Gitea
  - Gogs
  - Gitbucket
  - Phabricator
- Serveur de sécurité
  - OpenCanary
  - psono + vpn
  - zabbix
- Serveur de transactions ou blockchain
- VPN + Ressource protégée

### Autres ressources
- [Awesome selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)
- [Alternativo](https://alternativeto.net/software/gitlab/?license=opensource&platform=self-hosted)


### Exemples de modules
- Modules
  - services web, courriels, Mods
- Apps
  - toutes catégories de logiciels
- Plugins ou greffons
  - toutes catégories, spécialement les streamers
- Bots
  - pour les chats et les jeux
- Bridges
  - pour les chats (synchro irc-discord), Automatisation externe
- Services collaboratifs
  - chat irc (nickserv), service identité (ldap-courriel)
- Clients web compagnons
  -  courriels, certains chats
