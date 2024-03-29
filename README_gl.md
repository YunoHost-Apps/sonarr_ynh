<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Sonarr para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/sonarr.svg)](https://dash.yunohost.org/appci/app/sonarr) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/sonarr.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/sonarr.maintain.svg)

[![Instalar Sonarr con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sonarr)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Sonarr de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Sonarr is a PVR for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.


**Versión proporcionada:** 3.0.6.1196~ynh3

## Capturas de pantalla

![Captura de pantalla de Sonarr](./doc/screenshots/screenshot.jpg)

## Avisos / información importante

* Sonarr developper's repository only allows to download the very latest version.
  * The version displayed here may be different from the one actually installed.
* Supported architectures are `arm`, `armhf`, `arm64`, and `amd64`
* Access control is done with YunoHost's permissions system.
  * API (`domain.tld/path/api`) can be accessed by visitors to allow control by remote clients.
* The app uses YunoHost's multimedia directories, hence it has write access to users' and shared directories in `/home/yunohost.multimedia`. After installation, you can choose these directories to store your media.

## Documentación e recursos

- Web oficial da app: <https://sonarr.tv>
- Documentación oficial para admin: <https://wiki.servarr.com/Sonarr>
- Repositorio de orixe do código: <https://github.com/Sonarr/Sonarr>
- Tenda YunoHost: <https://apps.yunohost.org/app/sonarr>
- Informar dun problema: <https://github.com/YunoHost-Apps/sonarr_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
ou
sudo yunohost app upgrade sonarr -u https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
