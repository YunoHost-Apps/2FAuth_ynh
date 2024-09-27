<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# 2FAuth для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/2fauth.svg)](https://ci-apps.yunohost.org/ci/apps/2fauth/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/2fauth.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/2fauth.maintain.svg)

[![Установите 2FAuth с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить 2FAuth быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

2FAuth is a web based self-hosted alternative to One Time Passcode (OTP) generators like Google Authenticator, designed for both mobile and desktop.
2FAuth aims to ease you perform your 2FA authentication steps whatever the device you handle, with a clean and suitable interface.

### Features

- Manage your 2FA accounts and organize them using Groups
- Scan and decode any QR code to add account in no time
- Add custom account without QR code thanks to an advanced form
- Edit accounts, even the imported ones
- Generate TOTP and HOTP security codes

**Поставляемая версия:** 5.2.0~ynh2

**Демо-версия:** <https://demo.2fauth.app/login>

## Снимки экрана

![Снимок экрана 2FAuth](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальная документация администратора: <https://docs.2fauth.app/>
- Репозиторий кода главной ветки приложения: <https://github.com/Bubka/2FAuth>
- Магазин YunoHost: <https://apps.yunohost.org/app/2fauth>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
или
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
