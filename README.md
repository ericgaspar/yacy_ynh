# YaCy for YunoHost

[![Integration level](https://dash.yunohost.org/integration/yacy.svg)](https://dash.yunohost.org/appci/app/yacy) ![](https://ci-apps.yunohost.org/ci/badges/yacy.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/yacy.maintain.svg)  
[![Install YaCy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=yacy)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install YaCy quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Quick description of this app.

**Shipped version:** 1.0

## Screenshots

![](Link to a screenshot of this app.)

## Demo

* [Official demo](Link to a demo site for this app.)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/yacy%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/yacy/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/yacy%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/yacy/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

**More info on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/yacy_ynh/issues
 * App website: http://yacy.net
 * Upstream app repository: https://github.com/yacy/yacy_search_server
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/yacy_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/yacy_ynh/tree/testing --debug
or
sudo yunohost app upgrade yacy -u https://github.com/YunoHost-Apps/yacy_ynh/tree/testing --debug
```
