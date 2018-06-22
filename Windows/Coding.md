:: Windows 10 DevEnv :: Coding ::
=================================

# Overview

# Applications

## Tools

### [TortoiseSVN 1.9.5.27581](https://tortoisesvn.net/)

### [TortoiseGit 2.3.0.0](https://tortoisegit.org/)

### [WinMerge 2.14.0](http://winmerge.org/)

Can be used by TortoiseSVN.

### SoapUI

## Toolkits

## Compilers

### [JDK 8.0.172](http://www.oracle.com/technetwork/java/javase/overview/index.html)

- Java SE 8u172;
- Java SE 7u80;
- Java SE 6u45;
- Java SE 5u22;

#### Build Tools

##### [Ant 1.10.4](http://ant.apache.org/)

##### [Maven 3.5.4](http://maven.apache.org/)

Create a settings.xml with the following content under %USERPROFILE%\.m2\ folder:

```xml
<settings xmlns              = "http://maven.apache.org/SETTINGS/1.0.0"
          xmlns:xsi          = "http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation = "
            http://maven.apache.org/SETTINGS/1.0.0 https://maven.apache.org/xsd/settings-1.0.0.xsd
          "
>

    <localRepository>/Hosting/Repositories/Maven</localRepository>
    
    <interactiveMode/>
    
    <usePluginRegistry/>
    
    <offline/>
    
    <pluginGroups/>
    
    <servers/>
    
    <!-- http://maven.apache.org/guides/mini/guide-mirror-settings.html !-->
    <mirrors/>
    
    <!-- http://maven.apache.org/guides/mini/guide-proxies.html !-->
    <proxies/>
    
    <profiles/>
    
    <activeProfiles/>

</settings>
```

##### [Gradle 4.8.1](https://gradle.org/)

> Gradle looks into %USERPROFILE%\.m2\settings.xml for information where the local Maven repository is located. If no information is found, it assumes %USERPROFILE%\.m2\repository.

### ~~[Mono 5.12.0.226](https://www.mono-project.com/)~~

### [Go 1.10.3](https://golang.org/)

Although there's [ActiveState Go 1.8.3](https://www.activestate.com/activego) the recommendation is to install the official Python distribution.

## Interpreters

### [Groovy 2.4.15](http://groovy-lang.org/)

### [JRuby 9.2.0.0](http://jruby.org/)

### [Jython 2.7.0](http://www.jython.org/)

### ~~[Tcl/Tk 8.6.6](https://tcl.tk/)~~

Although there's [ActiveState Tcl/Tk 8.6.7.0](https://www.activestate.com/activetcl) the recommendation is to build from the official Tcl/Tk sources.

### ~~[Perl](https://www.perl.org/get.html#win32)~~

The choice between [Strawberry Perl 5.26.1.2601](http://strawberryperl.com/) and [ActiveState Perl 5.24.3.2404](https://www.activestate.com/activeperl) leans towards Strawberry Perl.

### [Ruby 2.5.1-1](https://rubyinstaller.org/)

### [Python 3.6.5](https://www.python.org/)

Although there's [ActiveState Python 3.6.0.3600](https://www.activestate.com/activepython) the recommendation is to install the official Python distribution.

### ~~[PHP](https://php.net/)~~

- 5.6.29
- 7.0.14
- 7.1.0

### Javascript

#### [Node.js 8.11.3](https://nodejs.org/en/)

## IDEs

### [Geany 1.33](https://www.geany.org/)

### [NetBeans 8.2](http://netbeans.org/)

### [Eclipse Oxygen 4.7](https://www.eclipse.org/ide/)

### [IDEA Community 2018.1.5](https://www.jetbrains.com/idea)

### [DBeaver Community Edition 5.1.1](dbeaver.jkiss.org)
