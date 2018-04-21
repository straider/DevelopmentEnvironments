:: macOS DevEnv :: Hosting ::
=============================

# Overview

# Applications

## Repositories

### Maven

### Gradle

## ~~[VirtualBox 5.2.10](https://www.virtualbox.org/wiki/Downloads)~~

## ~~[Vagrant 2.0.4](https://www.vagrantup.com/downloads.html)~~

## ~~[Packer 1.2.2](https://www.packer.io/downloads.html)~~

## Docker

### [Docker Community Edition for Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac)

### ~~[Docker Toolbox](https://docs.docker.com/toolbox/toolbox_install_mac/)~~

## OpenShift

### [Client Tools 3.9.0](https://github.com/openshift/origin)

```bash
brew install openshift-cli
```

### ~~[Atomic Developer Bundle 2.3.1](https://github.com/projectatomic/adb-atomic-developer-bundle)~~

### [Container Development Kit 2.4.0](https://developers.redhat.com/products/cdk/overview/)

### [MiniShift 1.15.1](https://github.com/minishift/minishift)

```bash
brew install minishift
```

## [PostgreSQL 10.3](https://www.postgresql.org/download/macosx/)

```bash
brew install postgresql

echo 'export PATH="/usr/local/opt/postgresql@9.5/bin:$PATH"' >> ~/.bash_profile
. ~/.bash_profile
```

Can control the server with:

```bash
brew tap homebrew/services

brew services start postgresql
brew services stop postgresql
```

## [MongoDB 3.6.4](https://www.mongodb.com/download-center?jmp=nav#community)

```bash
brew install mongodb
```
