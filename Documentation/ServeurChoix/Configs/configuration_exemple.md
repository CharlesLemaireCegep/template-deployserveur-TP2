#### Configurations
Localisation: `/var/ServiceX/client.conf`
Le fichier client.conf permet la configuration du client du serviceX il offre les différentes options suivantes:
```yaml
# Exemple de fichier de configuration pour le client du Service X

serviceXClientConfig:
  # Informations d'identification pour se connecter au Service X
  auth:
    username: "utilisateurExemple"
    password: "motDePasseSécurisé"
    apiKey: "cléAPIfournieParServiceX"

  # Paramètres spécifiques à l'application ou au service
  appSettings:
    mode: "production" # Ou "development", selon l'environnement
    logLevel: "info" # Niveaux: debug, info, warning, error
```