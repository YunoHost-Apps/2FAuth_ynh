<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# 2FAuth YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/2fauth.svg)](https://ci-apps.yunohost.org/ci/apps/2fauth/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/2fauth.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/2fauth.maintain.svg)

[![Instalatu 2FAuth YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek 2FAuth YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes

**Paketatutako bertsioa:** 5.4.1~ynh1

**Demoa:** <https://demo.2fauth.app/login>

## Pantaila-argazkiak

![2FAuth(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://docs.2fauth.app/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Bubka/2FAuth>
- YunoHost Denda: <https://apps.yunohost.org/app/2fauth>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
edo
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
