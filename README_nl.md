<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# 2FAuth voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/2fauth.svg)](https://ci-apps.yunohost.org/ci/apps/2fauth/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/2fauth.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/2fauth.maintain.svg)

[![2FAuth met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je 2FAuth snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes

**Geleverde versie:** 5.4.0~ynh1

**Demo:** <https://demo.2fauth.app/login>

## Schermafdrukken

![Schermafdrukken van 2FAuth](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele beheerdersdocumentatie: <https://docs.2fauth.app/>
- Upstream app codedepot: <https://github.com/Bubka/2FAuth>
- YunoHost-store: <https://apps.yunohost.org/app/2fauth>
- Meld een bug: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
of
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
