<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# 2FAuth dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/2fauth)](https://ci-apps.yunohost.org/ci/apps/2fauth/)
![Status działania](https://apps.yunohost.org/badge/state/2fauth)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/2fauth)

[![Zainstaluj 2FAuth z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację 2FAuth na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes


**Dostarczona wersja:** 5.4.3~ynh1

**Demo:** <https://demo.2fauth.app/login>

## Zrzuty ekranu

![Zrzut ekranu z 2FAuth](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna dokumentacja dla administratora: <https://docs.2fauth.app/>
- Repozytorium z kodem źródłowym: <https://github.com/Bubka/2FAuth>
- Sklep YunoHost: <https://apps.yunohost.org/app/2fauth>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
lub
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
