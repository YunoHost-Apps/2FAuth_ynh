<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# 2FAuth untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/2fauth)](https://ci-apps.yunohost.org/ci/apps/2fauth/)
![Status kerja](https://apps.yunohost.org/badge/state/2fauth)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/2fauth)

[![Pasang 2FAuth dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang 2FAuth secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes


**Versi terkirim:** 5.5.0~ynh1

**Demo:** <https://demo.2fauth.app/login>

## Tangkapan Layar

![Tangkapan Layar pada 2FAuth](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Dokumentasi admin resmi: <https://docs.2fauth.app/>
- Depot kode aplikasi hulu: <https://github.com/Bubka/2FAuth>
- Gudang YunoHost: <https://apps.yunohost.org/app/2fauth>
- Laporkan bug: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
atau
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
