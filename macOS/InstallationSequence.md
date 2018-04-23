:: Installation Sequence ::
===========================

# Sections

## macOS

- Enable Dark Theme (System and Apps);

### Homebrew

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

sudo chown -R $(whoami) /usr/local/var/homebrew
sudo chown -R $(whoami) /usr/local/Homebrew

brew update
brew doctor

brew tap caskroom/cask
brew tap homebrew/services
```

### Bash 4

```bash
brew install bash bash-completion
```

Enter sudo mode, to configure Bash as the default Shell:
```bash
sudo -s
```

Configure Bash as the default Shell, in sudo mode:
```bash
echo "$(brew --prefix)/bin/bash" >> /etc/shells
chsh -s $(brew --prefix)/bin/bash
```

## General

### BBEdit

### The Unarchiver

- Associate extensions

## Networking

### Chrome

### Slack

### Skype

### Bluejeans

### Zoom

## Hosting

### ~~VirtualBox~~

### ~~Vagrant~~

### Docker for Mac

### OpenShift

#### Client Tools

#### ~~Docker Machine Cluster~~

#### ~~Atomic Developer Bundle~~

#### ~~Container Developer Kit~~

#### MiniShift

### PostgreSQL

### ~~MongoDB~~

## Coding

### Meld

### ~~SvnX~~

### ~~GitX~~

### Sourcetree

- Dark Theme

### Compilers

#### Java

##### ~~Java 7u80~~

##### Java 8u161

##### Build Tools

###### Ant

###### Maven

###### Gradle

#### ~~Mono~~

#### ~~Go~~

#### ~~Rust~~

### Interpreters

#### Groovy

#### ~~JRuby~~

#### ~~Jython~~

#### Python

#### Ruby

#### Javascript

##### Node.js

### IDEs

#### Geany

#### ~~NetBeans~~

#### ~~Eclipse~~

#### IDEA

#### DBeaver

## macOS

### Environment Variables

#### HOSTING

#### DEVKITS

#### PATH
