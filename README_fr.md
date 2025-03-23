<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# 2FAuth pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/2fauth)](https://ci-apps.yunohost.org/ci/apps/2fauth/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/2fauth)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/2fauth)

[![Installer 2FAuth avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=2fauth)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer 2FAuth rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

2FAuth est une alternative Web auto-hébergée aux générateurs de codes d'accès à usage unique (OTP) comme Google Authenticator, conçue pour les appareils mobiles et les ordinateurs de bureau.
2FAuth vise à vous faciliter la réalisation de vos démarches d'authentification 2FA quel que soit l'appareil que vous manipulez, avec une interface claire et adaptée.

### Caractéristiques

- Gérez vos comptes 2FA et organisez-les à l'aide de groupes
- Scannez et décodez n'importe quel code QR pour ajouter un compte en un rien de temps
- Ajoutez un compte personnalisé sans QR code grâce à un formulaire avancé
- Modifier les comptes, même ceux importés
- Générer des codes de sécurité TOTP et HOTP


**Version incluse :** 5.4.3~ynh1

**Démo :** <https://demo.2fauth.app/login>

## Captures d’écran

![Capture d’écran de 2FAuth](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://docs.2fauth.app/>
- Dépôt de code officiel de l’app : <https://github.com/Bubka/2FAuth>
- YunoHost Store : <https://apps.yunohost.org/app/2fauth>
- Signaler un bug : <https://github.com/YunoHost-Apps/2fauth_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
ou
sudo yunohost app upgrade 2fauth -u https://github.com/YunoHost-Apps/2fauth_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
