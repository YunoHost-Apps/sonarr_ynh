* Sonarr a un système de mise à jour interne qui s'est montré compatible avec le package YunoHost. Vous pouvez l'utiliser, mais rappelez-vous que la version de Sonarr sera différente de celle connue de YunoHost.
* Le contrôle de l'accès se fait avec le système de permissions de YunoHost.
  * L'API (`__DOMAIN__/__PATH__/api`) est accessible aux visiteurs pour permettre le contrôle via des clients externes.
* L'application utilise les dossiers multimédia de YunoHost, elle a donc accès en écriture aux dossiers utilisateurs et communs de `/home/yunohost.multimedia`. Après installation, vous pourrez choisir ces dossiers pour y stocker vos médias.
