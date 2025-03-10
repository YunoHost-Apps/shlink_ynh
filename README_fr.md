<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Shlink pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/shlink)](https://ci-apps.yunohost.org/ci/apps/shlink/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/shlink)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/shlink)

[![Installer Shlink avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shlink)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Shlink rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Shlink is a self-hosted URL shortener which provides both a REST and a CLI interface to interact with it.

Additionally, there's also an official Shlink web client which, by making use of Shlink's REST API, provides a beautiful web UI to handle multiple Shlink instances.

**Version incluse :** 4.4.5~ynh1

## Captures d’écran

![Capture d’écran de Shlink](./doc/screenshots/shlink-web-client-placeholder.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://shlink.io/>
- Documentation officielle utilisateur : <https://shlink.io/documentation/>
- Dépôt de code officiel de l’app : <https://github.com/shlinkio/shlink>
- YunoHost Store : <https://apps.yunohost.org/app/shlink>
- Signaler un bug : <https://github.com/YunoHost-Apps/shlink_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/shlink_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shlink_ynh/tree/testing --debug
ou
sudo yunohost app upgrade shlink -u https://github.com/YunoHost-Apps/shlink_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
