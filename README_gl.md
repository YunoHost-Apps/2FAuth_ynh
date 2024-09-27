<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# 2FAuth para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/2fauth.svg)](https://ci-apps.yunohost.org/ci/apps/2fauth/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/2fauth.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/2fauth.maintain.svg)

[![Instalar 2FAuth con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar 2FAuth de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes

**Versión proporcionada:** 5.3.0~ynh1

**Demo:** <https://demo.2fauth.app/login>

## Capturas de pantalla

![Captura de pantalla de 2FAuth](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Documentación oficial para admin: <https://docs.2fauth.app/>
- Repositorio de orixe do código: <https://github.com/Bubka/2FAuth>
- Tenda YunoHost: <https://apps.yunohost.org/app/2fauth>
- Informar dun problema: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
ou
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
