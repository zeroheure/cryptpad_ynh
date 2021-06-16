<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# CryptPad for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cryptpad.svg)](https://dash.yunohost.org/appci/app/cryptpad) ![](https://ci-apps.yunohost.org/ci/badges/cryptpad.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/cryptpad.maintain.svg)  
[![Install CryptPad with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cryptpad)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install CryptPad quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Zero Knowledge realtime collaborative editor

**Shipped version:** 4.7.0~ynh1

**Demo:** https://cryptpad.fr/

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Configuration

* How to configure this app: From the admin panel and the plain file `/var/www/cryptpad/config/config.js.`

## Documentation and resources

* Official app website: https://cryptpad.fr/
* Official user documentation: https://yunohost.org/apps
* Official admin documentation: https://docs.cryptpad.fr/en/
* Upstream app code repository: https://github.com/xwiki-labs/cryptpad
* YunoHost documentation for this app: https://yunohost.org/app_cryptpad
* Report a bug: https://github.com/YunoHost-Apps/cryptpad_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/cryptpad_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/cryptpad_ynh/tree/testing --debug
or
sudo yunohost app upgrade cryptpad -u https://github.com/YunoHost-Apps/cryptpad_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps