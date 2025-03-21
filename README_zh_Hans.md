<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Sonarr

[![集成程度](https://apps.yunohost.org/badge/integration/sonarr)](https://ci-apps.yunohost.org/ci/apps/sonarr/)
![工作状态](https://apps.yunohost.org/badge/state/sonarr)
![维护状态](https://apps.yunohost.org/badge/maintained/sonarr)

[![使用 YunoHost 安装 Sonarr](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sonarr)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Sonarr。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Sonarr is a PVR for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.


**分发版本：** 4.0.14.2939~ynh1

## 截图

![Sonarr 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://sonarr.tv>
- 官方管理文档： <https://wiki.servarr.com/Sonarr>
- 上游应用代码库： <https://github.com/Sonarr/Sonarr>
- YunoHost 商店： <https://apps.yunohost.org/app/sonarr>
- 报告 bug： <https://github.com/YunoHost-Apps/sonarr_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
或
sudo yunohost app upgrade sonarr -u https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
