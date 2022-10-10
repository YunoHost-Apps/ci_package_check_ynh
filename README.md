<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# CI_package_check for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ci_package_check.svg)](https://dash.yunohost.org/appci/app/ci_package_check) ![Working status](https://ci-apps.yunohost.org/ci/badges/ci_package_check.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/ci_package_check.maintain.svg)  
[![Install CI_package_check with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ci_package_check)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install CI_package_check quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Continous Integration server for YunoHost apps
the interface between [yunorunner](https://github.com/YunoHost/yunorunner) (the CI web UI / scheduler) and [package_check](https://github.com/YunoHost/package_check) (the test suite).


**Shipped version:** 1.0~ynh1

**Demo:** https://ci-apps.yunohost.org
## Documentation and resources

* Official app website: <https://github.com/YunoHost/CI_package_check>
* Upstream app code repository: <https://github.com/YunoHost/CI_package_check>
* YunoHost documentation for this app: <https://yunohost.org/app_ci_package_check>
* Report a bug: <https://github.com/YunoHost-Apps/ci_package_check_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ci_package_check_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/ci_package_check_ynh/tree/testing --debug
or
sudo yunohost app upgrade ci_package_check -u https://github.com/YunoHost-Apps/ci_package_check_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
