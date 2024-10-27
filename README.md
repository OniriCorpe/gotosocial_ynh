<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# GoToSocial for YunoHost

[![Integration level](https://dash.yunohost.org/integration/gotosocial.svg)](https://ci-apps.yunohost.org/ci/apps/gotosocial/) ![Working status](https://ci-apps.yunohost.org/ci/badges/gotosocial.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/gotosocial.maintain.svg)

[![Install GoToSocial with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gotosocial)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install GoToSocial quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

GoToSocial is a fast [ActivityPub](https://activitypub.rocks/) social network server, written in Golang.

With GoToSocial, you can keep in touch with your friends, post, read, and share images and articles. All without being tracked or advertised to!

The official documentation is at [docs.gotosocial.org](https://docs.gotosocial.org).  

Admins are **strongly encouraged to read the documentation** of this package after installing it. It is available in the webadmin under Applications > gotosocial (at the bottom) or [here on the package's repository](https://github.com/YunoHost-Apps/gotosocial_ynh/blob/master/doc/ADMIN.md)!

Please note that this package uses the ["i'm so tired" software license 1.0](https://github.com/YunoHost-Apps/gotosocial_ynh/blob/master/LICENSE), please read it and accept it before proceeding with installation.


**Shipped version:** 0.17.1~ynh2

## Screenshots

![Screenshot of GoToSocial](./doc/screenshots/screenshot.png)

## :red_circle: Antifeatures

- **Alpha software**: Early development stage. May contain changing or unstable features, bugs, and security vulnerability.
- **Not totally free package**: The YunoHost package of this app is under an overall free license, but with clauses that may restrict its use.

## Documentation and resources

- Official app website: <https://gotosocial.org/>
- Official user documentation: <https://docs.gotosocial.org/en/latest/>
- Official admin documentation: <https://docs.gotosocial.org/en/latest/>
- Upstream app code repository: <https://github.com/superseriousbusiness/gotosocial>
- YunoHost Store: <https://apps.yunohost.org/app/gotosocial>
- Report a bug: <https://github.com/YunoHost-Apps/gotosocial_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/gotosocial_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gotosocial_ynh/tree/testing --debug
or
sudo yunohost app upgrade gotosocial -u https://github.com/YunoHost-Apps/gotosocial_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
