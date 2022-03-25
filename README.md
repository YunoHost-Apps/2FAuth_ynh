<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# 2FAuth for YunoHost

[![Integration level](https://dash.yunohost.org/integration/2fauth.svg)](https://dash.yunohost.org/appci/app/2fauth) ![](https://ci-apps.yunohost.org/ci/badges/2fauth.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/2fauth.maintain.svg)  
[![Install 2FAuth with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install 2FAuth quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.

It aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes

**Shipped version:** 2.1.0~ynh1

**Demo:** https://demo.2fauth.app/login

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentation and resources

* Official app website: https://example.com
* Upstream app code repository: https://github.com/Bubka/2FAuth
* YunoHost documentation for this app: https://yunohost.org/app_2fauth
* Report a bug: https://github.com/YunoHost-Apps/2fauth_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
or
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps