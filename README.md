# Cowyo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cowyo.svg)](https://dash.yunohost.org/appci/app/cowyo) ![](https://ci-apps.yunohost.org/ci/badges/cowyo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/cowyo.maintain.svg)  
[![Install cowyo with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=cowyo)

> *This package allow you to install cowyo quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
cowyo is a self-contained wiki server that makes jotting notes easy and fast. The most important feature here is simplicity. Other features include versioning, page locking, self-destructing messages, encryption, and listifying. See https://github.com/schollz/cowyo#usage

**Shipped version:** 2.12.0

## Demo

* [Official demo](https://cowyo.com/)

## Configuration

No configuration required except specifying the domain to access it, and its public/private status.

## Documentation

 * Official documentation: https://github.com/schollz/cowyo/blob/master/README.md

## YunoHost specific features

 * Multi-users support: not applicable.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/cowyo%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/cowyo/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/cowyo%20(Community)%20(%7EARM%7E).svg)](https://ci-apps-arm.yunohost.org/ci/apps/cowyo/)

## Limitations

 * By design, *cowyo* requires its own domain.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/cowyo_ynh/issues
 * Cowyo GitHub page: https://github.com/schollz/cowyo
 * Cowyo demo site: https://cowyo.com/
 * YunoHost website: https://yunohost.org/

---

## Developers infos

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/cowyo_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/cowyo_ynh/tree/testing --debug
or
sudo yunohost app upgrade cowyo -u https://github.com/YunoHost-Apps/cowyo_ynh/tree/testing --debug
```
