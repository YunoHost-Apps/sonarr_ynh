<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Sonarr per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/sonarr.svg)](https://dash.yunohost.org/appci/app/sonarr) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/sonarr.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/sonarr.maintain.svg)

[![Installa Sonarr con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sonarr)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Sonarr su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Sonarr is a PVR for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.


**Versione pubblicata:** 3.0.6.1196~ynh3

## Screenshot

![Screenshot di Sonarr](./doc/screenshots/screenshot.jpg)

## Attenzione/informazioni importanti

* Sonarr developper's repository only allows to download the very latest version.
  * The version displayed here may be different from the one actually installed.
* Supported architectures are `arm`, `armhf`, `arm64`, and `amd64`
* Access control is done with YunoHost's permissions system.
  * API (`domain.tld/path/api`) can be accessed by visitors to allow control by remote clients.
* The app uses YunoHost's multimedia directories, hence it has write access to users' and shared directories in `/home/yunohost.multimedia`. After installation, you can choose these directories to store your media.

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://sonarr.tv>
- Documentazione ufficiale per gli amministratori: <https://wiki.servarr.com/Sonarr>
- Repository upstream del codice dell’app: <https://github.com/Sonarr/Sonarr>
- Store di YunoHost: <https://apps.yunohost.org/app/sonarr>
- Segnala un problema: <https://github.com/YunoHost-Apps/sonarr_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
o
sudo yunohost app upgrade sonarr -u https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
