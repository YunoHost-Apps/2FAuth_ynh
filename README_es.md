<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# 2FAuth para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/2fauth.svg)](https://ci-apps.yunohost.org/ci/apps/2fauth/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/2fauth.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/2fauth.maintain.svg)

[![Instalar 2FAuth con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalar2FAuth rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes

**Versión actual:** 5.3.0~ynh1

**Demo:** <https://demo.2fauth.app/login>

## Capturas

![Captura de 2FAuth](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Documentación administrador oficial: <https://docs.2fauth.app/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/Bubka/2FAuth>
- Catálogo YunoHost: <https://apps.yunohost.org/app/2fauth>
- Reportar un error: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
o
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
