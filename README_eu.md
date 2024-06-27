<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Sonarr YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/sonarr.svg)](https://ci-apps.yunohost.org/ci/apps/sonarr/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/sonarr.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/sonarr.maintain.svg)

[![Instalatu Sonarr YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sonarr)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Sonarr YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Sonarr is a PVR for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.


**Paketatutako bertsioa:** 4.0.5.1710~ynh1

## Pantaila-argazkiak

![Sonarr(r)en pantaila-argazkia](./doc/screenshots/screenshot.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://sonarr.tv>
- Administratzaileen dokumentazio ofiziala: <https://wiki.servarr.com/Sonarr>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Sonarr/Sonarr>
- YunoHost Denda: <https://apps.yunohost.org/app/sonarr>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/sonarr_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
edo
sudo yunohost app upgrade sonarr -u https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
