﻿:: Windows 10 DevEnv ::
=======================

# Overview

These are personal notes on how to bring up a full Development Environment on top of Windows 10 Home Edition.

# Step-by-Step

- [Installation Sequence](InstallationSequence.md)
- Sections:
    - [General](General.md)
    - [Networking](Networking.md)
    - [Hosting](Hosting.md)
    - [Coding](Coding.md)

# Challenges

## Chocolatey

- How to install, upgrade and uninstall packages?
- How to specifiy installation folder?

*Note*: not all packages allow specifiying installation folder and not all allow it in the same way.

## Windows Subsystem for Linux

- [Install the Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
- [Ubuntu](https://www.microsoft.com/en-gb/store/p/ubuntu/9nblggh4msv6?rtc=1)
- [Debian](https://www.microsoft.com/en-gb/store/p/debian-gnu-linux/9msvkqc78pk6?rtc=1)
- [Kali Linux](https://www.microsoft.com/en-gb/store/p/kali-linux/9pkr34tncv07?rtc=1)
- [openSUSE](https://www.microsoft.com/en-gb/store/p/opensuse-leap-42/9njvjts82tjx?rtc=1)
- [SUSE Linux Enterprise Server](https://www.microsoft.com/en-gb/store/p/suse-linux-enterprise-server-12/9p32mwbh6cns?rtc=1)

Open PowerShell as Administrator and run:

```bash
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

## VirtualBox vs. Hyper-V

The article [Client Hyper-V vs. VirtualBox](https://www.altaro.com/hyper-v/client-hyper-v-vs-virtualbox/) provides a reasonably good comparison between Type 1 Hypervisor and Type 2 Hypervisor - Hyper-V and VirtualBox.

It seems that the most flexible option is to use VirtualBox, but then one has to use Docker Toolbox instead of Docker on Windows.
