# Cowyo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cowyo.svg)](https://ci-apps.yunohost.org/ci/apps/cowyo/)  
[![Install cowyo with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=cowyo)

> *This package allow you to install cowyo quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
A feature-rich wiki webserver for minimalists. See https://github.com/schollz/cowyo#usage

**Shipped version:** 2.12.0

## Demo

* [Official demo](https://cowyo.com/)

## Configuration

No configuration required except specifying the domain to access it, and its public/private status.

## Documentation

 * [Official documentation (on GitHub)](https://github.com/schollz/cowyo/blob/master/README.md)

## YunoHost specific features

 * Multi-users support: not applicable.

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/cowyo%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/cowyo/)/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/cowyo%20(Community)%20(%7EARM%7E).svg)](https://ci-apps-arm.yunohost.org/ci/apps/cowyo/)/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/cowyo%20(Apps).svg)](https://ci-stretch.nohost.me/ci/apps/cowyo/)/)

## Limitations

 * By design, *cowyo* requires its own domain.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/cowyo_ynh/issues
 * Cowyo GitHub page: https://github.com/schollz/cowyo
 * Cowyo demo site: https://cowyo.com/
 * YunoHost website: https://yunohost.org/

---

Developers infos
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/cowyo_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/cowyo_ynh/tree/testing --debug
or
sudo yunohost app upgrade cowyo -u https://github.com/YunoHost-Apps/cowyo_ynh/tree/testing --debug
```
