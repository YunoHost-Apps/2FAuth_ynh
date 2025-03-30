<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# 2FAuth für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/2fauth)](https://ci-apps.yunohost.org/ci/apps/2fauth/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/2fauth)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/2fauth)

[![2FAuth mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie 2FAuth schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes


**Ausgelieferte Version:** 5.5.0~ynh1

**Demo:** <https://demo.2fauth.app/login>

## Bildschirmfotos

![Bildschirmfotos von 2FAuth](./doc/screenshots/screenshot.png)

## Dokumentation und Ressourcen

- Offizielle Verwaltungsdokumentation: <https://docs.2fauth.app/>
- Upstream App Repository: <https://github.com/Bubka/2FAuth>
- YunoHost-Shop: <https://apps.yunohost.org/app/2fauth>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
oder
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>
