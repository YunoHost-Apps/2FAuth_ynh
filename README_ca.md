<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# 2FAuth per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/2fauth)](https://ci-apps.yunohost.org/ci/apps/2fauth/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/2fauth)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/2fauth)

[![Instal·la 2FAuth amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar 2FAuth de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes


**Versió inclosa:** 5.5.0~ynh1

**Demo:** <https://demo.2fauth.app/login>

## Captures de pantalla

![Captures de pantalla de 2FAuth](./doc/screenshots/screenshot.png)

## Documentació i recursos

- Documentació oficial per l'administrador: <https://docs.2fauth.app/>
- Repositori oficial del codi de l'aplicació: <https://github.com/Bubka/2FAuth>
- Botiga YunoHost: <https://apps.yunohost.org/app/2fauth>
- Reportar un error: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
o
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
