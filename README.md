<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Shlink for YunoHost

[![Integration level](https://dash.yunohost.org/integration/shlink.svg)](https://dash.yunohost.org/appci/app/shlink) ![Working status](https://ci-apps.yunohost.org/ci/badges/shlink.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/shlink.maintain.svg)

[![Install Shlink with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shlink)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Shlink quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Shlink is a self-hosted URL shortener which provides both a REST and a CLI interface to interact with it.

Additionally, there's also an official Shlink web client which, by making use of Shlink's REST API, provides a beautiful web UI to handle multiple Shlink instances.

**Shipped version:** 3.7.3~ynh1

## Screenshots

![Screenshot of Shlink](./doc/screenshots/shlink-web-client-placeholder.jpg)

## Documentation and resources

* Official app website: <https://shlink.io/>
* Official user documentation: <https://shlink.io/documentation/>
* Upstream app code repository: <https://github.com/shlinkio/shlink>
* YunoHost Store: <https://apps.yunohost.org/app/shlink>
* Report a bug: <https://github.com/YunoHost-Apps/shlink_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/shlink_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/shlink_ynh/tree/testing --debug
or
sudo yunohost app upgrade shlink -u https://github.com/YunoHost-Apps/shlink_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>