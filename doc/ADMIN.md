* Sonarr has an internal self-upgrade system that has proven to be reliable with YunoHost's package. You may use it, though remember that there will be a discrepancy between Sonarr's actual version and the one known by YunoHost.
* Access control is done with YunoHost's permissions system.
  * API (`__DOMAIN__/__PATH__/api`) can be accessed by visitors to allow control by remote clients.
* The app uses YunoHost's multimedia directories, hence it has write access to users' and shared directories in `/home/yunohost.multimedia`. After installation, you can choose these directories to store your media.
