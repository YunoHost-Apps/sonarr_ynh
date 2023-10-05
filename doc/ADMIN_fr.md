* Le dépôt des développeurs de Sonarr ne permet de télécharger que la toute dernière version.
  * La version annoncée ici peut être différente de celle réellement installée.
* Les architectures compatibles sont `arm`, `armhf`, `arm64`, et `amd64`
* Le contrôle de l'accès se fait avec le système de permissions de YunoHost.
  * L'API (`domain.tld/path/api`) est accessible aux visiteurs pour permettre le contrôle via des clients externes.
* L'application utilise les dossiers multimédia de YunoHost, elle a donc accès en écriture aux dossiers utilisateurs et communs de `/home/yunohost.multimedia`. Après installation, vous pourrez choisir ces dossiers pour y stocker vos médias.
