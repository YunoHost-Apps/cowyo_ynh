# Cowyo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cowyo.svg)](https://ci-apps.yunohost.org/jenkins/job/cowyo%20%28Community%29/lastBuild/consoleFull)  
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

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/cowyo%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/cowyo%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/jenkins/job/cowyo%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps-arm.yunohost.org/jenkins/job/cowyo%20(Community)%20(%7EARM%7E)/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/jenkins/job/cowyo%20(Community)/badge/icon)](https://ci-stretch.nohost.me/jenkins/job/cowyo%20(Community)/)

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
