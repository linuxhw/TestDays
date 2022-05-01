Slackware - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Slackware.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 58

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | TUF B450-PLUS GAMING        | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI        | 970 GAMING                  | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| ASRock     | N68-S3 FX                   | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI        | MS-7365                     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown    | X79-P3                      | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| HP         | 0A08h                       | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| ASRock     | H410M-ITX/ac                | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek    | PRIME Z390-A                | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Acer       | FMCP7A-ION-LE               | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| ASRock     | H270 Pro4                   | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| Lenovo     | 31900058 STD                | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| Biostar    | X470GTA                     | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| MSI        | G31TM-P21                   | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP         | 212B                        | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI        | B450 TOMAHAWK MAX           | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI        | G31TM-P21                   | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI        | H61M-P31                    | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP         | 21B4 A01                    | [871b196cc2](https://linux-hardware.org/?probe=871b196cc2) | Nov 21, 2021 |
| HP         | 21B4 A01                    | [259232d98b](https://linux-hardware.org/?probe=259232d98b) | Nov 21, 2021 |
| Supermicro | X9DA7/E                     | [3fc1ef2b58](https://linux-hardware.org/?probe=3fc1ef2b58) | Nov 09, 2021 |
| MSI        | B450M-A PRO MAX             | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek    | SABERTOOTH X99              | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI        | B450M-A PRO MAX             | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| Intel      | DZ77RE-75K AAG39010-302     | [069c508e80](https://linux-hardware.org/?probe=069c508e80) | Sep 25, 2021 |
| Shuttle    | NC03U                       | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| ASUSTek    | SABERTOOTH X79              | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| HPE        | ProLiant MicroServer Gen... | [9ac798b737](https://linux-hardware.org/?probe=9ac798b737) | Aug 05, 2021 |
| HPE        | ProLiant MicroServer Gen... | [095745e5fb](https://linux-hardware.org/?probe=095745e5fb) | Jul 06, 2021 |
| HP         | 158A                        | [d612124939](https://linux-hardware.org/?probe=d612124939) | Jun 21, 2021 |
| ASRock     | H310CM-HDV                  | [3291e5d2de](https://linux-hardware.org/?probe=3291e5d2de) | Jun 19, 2021 |
| ASRock     | H87M Pro4                   | [8d4b7f121d](https://linux-hardware.org/?probe=8d4b7f121d) | Jun 02, 2021 |
| ASUSTek    | Pro WS X570-ACE             | [6e60025ac5](https://linux-hardware.org/?probe=6e60025ac5) | May 25, 2021 |
| ASUSTek    | PRIME X370-PRO              | [3e5f76719a](https://linux-hardware.org/?probe=3e5f76719a) | May 24, 2021 |
| ASUSTek    | PRIME X370-PRO              | [c75f9d5c0d](https://linux-hardware.org/?probe=c75f9d5c0d) | May 23, 2021 |
| Dell       | 0PTTT9 A00                  | [e5b81a0da1](https://linux-hardware.org/?probe=e5b81a0da1) | May 20, 2021 |
| Gigabyte   | N3160TN                     | [2fd537312f](https://linux-hardware.org/?probe=2fd537312f) | May 14, 2021 |
| MSI        | G31TM-P21                   | [91c11ae82e](https://linux-hardware.org/?probe=91c11ae82e) | May 07, 2021 |
| Foxconn    | 2ADA                        | [425d15a5ce](https://linux-hardware.org/?probe=425d15a5ce) | Mar 09, 2021 |
| Dell       | 0TP412                      | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| ASRock     | B450M Steel Legend          | [e1424f6de3](https://linux-hardware.org/?probe=e1424f6de3) | Dec 31, 2020 |
| Supermicro | X8SIE 0001                  | [96607f4270](https://linux-hardware.org/?probe=96607f4270) | Nov 12, 2020 |
| ASRock     | Z390M-ITX/ac                | [06eb8afdbc](https://linux-hardware.org/?probe=06eb8afdbc) | Oct 19, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [d42d44dd82](https://linux-hardware.org/?probe=d42d44dd82) | Jul 23, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [888f105221](https://linux-hardware.org/?probe=888f105221) | Jul 23, 2020 |
| ASUSTek    | M5A97 R2.0                  | [2eb600bb96](https://linux-hardware.org/?probe=2eb600bb96) | Jul 10, 2020 |
| ASUSTek    | M5A97 R2.0                  | [232221bf45](https://linux-hardware.org/?probe=232221bf45) | Jul 10, 2020 |
| Huanan     | X79-8D VAA31                | [bbfc99d048](https://linux-hardware.org/?probe=bbfc99d048) | Jan 22, 2020 |
| ASUSTek    | A68HM-PLUS                  | [505df04abc](https://linux-hardware.org/?probe=505df04abc) | Oct 27, 2019 |
| ASUSTek    | PRIME B350M-A               | [0b246f9623](https://linux-hardware.org/?probe=0b246f9623) | Oct 27, 2019 |
| ASUSTek    | ROG STRIX X470-F GAMING     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASUSTek    | Z97-A                       | [482c60ec21](https://linux-hardware.org/?probe=482c60ec21) | Oct 21, 2019 |
| Gigabyte   | M61SME-S2                   | [10469f1659](https://linux-hardware.org/?probe=10469f1659) | Oct 21, 2019 |
| HP         | 2B35                        | [45c5e4afbe](https://linux-hardware.org/?probe=45c5e4afbe) | Oct 21, 2019 |
| Gigabyte   | 970A-DS3P                   | [70ea4f97bf](https://linux-hardware.org/?probe=70ea4f97bf) | Oct 21, 2019 |
| ASUSTek    | Maximus VII HERO            | [4751f76aa2](https://linux-hardware.org/?probe=4751f76aa2) | Oct 20, 2019 |
| ASUSTek    | Maximus VII RANGER          | [71121ccd6f](https://linux-hardware.org/?probe=71121ccd6f) | Oct 20, 2019 |
| ASUSTek    | P5QLD PRO                   | [dabc1ee203](https://linux-hardware.org/?probe=dabc1ee203) | Oct 20, 2019 |
| Gigabyte   | X150M-PRO ECC-CF            | [39987c5d8e](https://linux-hardware.org/?probe=39987c5d8e) | Oct 10, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Slackware 14.2  | 31       | 60.78%  |
| Slackware 15.0  | 18       | 35.29%  |
| Slackware 14.2+ | 2        | 3.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Slackware | 50       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.10.28-Unraid       | 5        | 9.8%    |
| 4.19.80              | 4        | 7.84%   |
| 5.15.19              | 3        | 5.88%   |
| 4.4.190              | 3        | 5.88%   |
| 5.15.27              | 2        | 3.92%   |
| 4.4.240              | 2        | 3.92%   |
| 5.4.77               | 1        | 1.96%   |
| 5.4.53-APRL          | 1        | 1.96%   |
| 5.4.43               | 1        | 1.96%   |
| 5.4.0-rc2-vto        | 1        | 1.96%   |
| 5.17.2               | 1        | 1.96%   |
| 5.17.0-custom        | 1        | 1.96%   |
| 5.16.18              | 1        | 1.96%   |
| 5.16.13              | 1        | 1.96%   |
| 5.16.11              | 1        | 1.96%   |
| 5.15.6               | 1        | 1.96%   |
| 5.15.30-Unraid       | 1        | 1.96%   |
| 5.15.14              | 1        | 1.96%   |
| 5.15.13              | 1        | 1.96%   |
| 5.14.15-Unraid       | 1        | 1.96%   |
| 5.14.15              | 1        | 1.96%   |
| 5.14.11              | 1        | 1.96%   |
| 5.13.9-jw            | 1        | 1.96%   |
| 5.13.12              | 1        | 1.96%   |
| 5.12.12              | 1        | 1.96%   |
| 5.10.44-slack64-host | 1        | 1.96%   |
| 5.10.40              | 1        | 1.96%   |
| 5.10.3               | 1        | 1.96%   |
| 4.9.248.a            | 1        | 1.96%   |
| 4.9.118              | 1        | 1.96%   |
| 4.4.261              | 1        | 1.96%   |
| 4.4.189              | 1        | 1.96%   |
| 4.4.14               | 1        | 1.96%   |
| 4.20.11              | 1        | 1.96%   |
| 4.19.98-Unraid       | 1        | 1.96%   |
| 4.19.88-Unraid       | 1        | 1.96%   |
| 4.19.107-Unraid      | 1        | 1.96%   |
| 4.19.10              | 1        | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.28  | 5        | 9.8%    |
| 4.19.80  | 4        | 7.84%   |
| 5.15.19  | 3        | 5.88%   |
| 4.4.190  | 3        | 5.88%   |
| 5.15.27  | 2        | 3.92%   |
| 5.14.15  | 2        | 3.92%   |
| 4.4.240  | 2        | 3.92%   |
| 5.4.77   | 1        | 1.96%   |
| 5.4.53   | 1        | 1.96%   |
| 5.4.43   | 1        | 1.96%   |
| 5.4.0    | 1        | 1.96%   |
| 5.17.2   | 1        | 1.96%   |
| 5.17.0   | 1        | 1.96%   |
| 5.16.18  | 1        | 1.96%   |
| 5.16.13  | 1        | 1.96%   |
| 5.16.11  | 1        | 1.96%   |
| 5.15.6   | 1        | 1.96%   |
| 5.15.30  | 1        | 1.96%   |
| 5.15.14  | 1        | 1.96%   |
| 5.15.13  | 1        | 1.96%   |
| 5.14.11  | 1        | 1.96%   |
| 5.13.9   | 1        | 1.96%   |
| 5.13.12  | 1        | 1.96%   |
| 5.12.12  | 1        | 1.96%   |
| 5.10.44  | 1        | 1.96%   |
| 5.10.40  | 1        | 1.96%   |
| 5.10.3   | 1        | 1.96%   |
| 4.9.248  | 1        | 1.96%   |
| 4.9.118  | 1        | 1.96%   |
| 4.4.261  | 1        | 1.96%   |
| 4.4.189  | 1        | 1.96%   |
| 4.4.14   | 1        | 1.96%   |
| 4.20.11  | 1        | 1.96%   |
| 4.19.98  | 1        | 1.96%   |
| 4.19.88  | 1        | 1.96%   |
| 4.19.107 | 1        | 1.96%   |
| 4.19.10  | 1        | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 9        | 17.65%  |
| 5.10    | 8        | 15.69%  |
| 4.4     | 8        | 15.69%  |
| 4.19    | 8        | 15.69%  |
| 5.4     | 4        | 7.84%   |
| 5.16    | 3        | 5.88%   |
| 5.14    | 3        | 5.88%   |
| 5.17    | 2        | 3.92%   |
| 5.13    | 2        | 3.92%   |
| 4.9     | 2        | 3.92%   |
| 5.12    | 1        | 1.96%   |
| 4.20    | 1        | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 50       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 43.14%  |
| XFCE    | 13       | 25.49%  |
| KDE5    | 13       | 25.49%  |
| FVWM    | 2        | 3.92%   |
| KDE     | 1        | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 32       | 62.75%  |
| Tty     | 9        | 17.65%  |
| Unknown | 9        | 17.65%  |
| Wayland | 1        | 1.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 39.22%  |
| SDDM    | 15       | 29.41%  |
| XDM     | 12       | 23.53%  |
| SLiM    | 2        | 3.92%   |
| LightDM | 2        | 3.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 23       | 46%     |
| Unknown     | 19       | 38%     |
| it_IT       | 2        | 4%      |
| sr_RS@latin | 1        | 2%      |
| ru_RU       | 1        | 2%      |
| es_ES.UTF8  | 1        | 2%      |
| en_US.ASCII | 1        | 2%      |
| en_GB       | 1        | 2%      |
| C           | 1        | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 30       | 60%     |
| EFI  | 20       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 31       | 62%     |
| Btrfs    | 8        | 16%     |
| Xfs      | 3        | 6%      |
| Rootfs   | 3        | 6%      |
| Overlay  | 2        | 4%      |
| Reiserfs | 1        | 2%      |
| F2fs     | 1        | 2%      |
| Ext3     | 1        | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 33       | 64.71%  |
| MBR     | 17       | 33.33%  |
| Unknown | 1        | 1.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 64%     |
| Yes       | 18       | 36%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 68%     |
| Yes       | 16       | 32%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 30%     |
| ASRock              | 7        | 14%     |
| MSI                 | 6        | 12%     |
| Hewlett-Packard     | 5        | 10%     |
| Gigabyte Technology | 4        | 8%      |
| Supermicro          | 2        | 4%      |
| Dell                | 2        | 4%      |
| Shuttle             | 1        | 2%      |
| Lenovo              | 1        | 2%      |
| Intel               | 1        | 2%      |
| Huanan              | 1        | 2%      |
| HPE                 | 1        | 2%      |
| Foxconn             | 1        | 2%      |
| Biostar             | 1        | 2%      |
| Acer                | 1        | 2%      |
| Unknown             | 1        | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 4        | 8%      |
| Supermicro X9DA7/E                  | 1        | 2%      |
| Supermicro ReadyDATA 5200           | 1        | 2%      |
| Shuttle NC03U                       | 1        | 2%      |
| MSI MS-7C52                         | 1        | 2%      |
| MSI MS-7C02                         | 1        | 2%      |
| MSI MS-7788                         | 1        | 2%      |
| MSI MS-7693                         | 1        | 2%      |
| MSI MS-7529                         | 1        | 2%      |
| MSI MS-7365                         | 1        | 2%      |
| Lenovo H50-05 90BH001WIX            | 1        | 2%      |
| Intel DZ77RE-75K AAG39010-302       | 1        | 2%      |
| Huanan X79-8D VAA31                 | 1        | 2%      |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 2%      |
| HP Z620 Workstation                 | 1        | 2%      |
| HP Z440 Workstation                 | 1        | 2%      |
| HP xw8400 Workstation               | 1        | 2%      |
| HP t620 Quad Core TC                | 1        | 2%      |
| HP 500-515na                        | 1        | 2%      |
| Gigabyte X150M-PRO ECC              | 1        | 2%      |
| Gigabyte N3160TN                    | 1        | 2%      |
| Gigabyte M61SME-S2                  | 1        | 2%      |
| Gigabyte 970A-DS3P                  | 1        | 2%      |
| Foxconn p6-2390                     | 1        | 2%      |
| Dell Precision WorkStation T3400    | 1        | 2%      |
| Dell Precision T3600                | 1        | 2%      |
| Biostar X470GTA                     | 1        | 2%      |
| ASUS TUF B450-PLUS GAMING           | 1        | 2%      |
| ASUS SABERTOOTH X79                 | 1        | 2%      |
| ASUS ROG STRIX X470-F GAMING        | 1        | 2%      |
| ASUS Pro WS X570-ACE                | 1        | 2%      |
| ASUS PRIME Z390-A                   | 1        | 2%      |
| ASUS PRIME X370-PRO                 | 1        | 2%      |
| ASUS PRIME B450-PLUS                | 1        | 2%      |
| ASUS PRIME B350M-A                  | 1        | 2%      |
| ASUS P5QLD PRO                      | 1        | 2%      |
| ASUS M5A97 R2.0                     | 1        | 2%      |
| ASUS A68HM-PLUS                     | 1        | 2%      |
| ASRock Z390M-ITX/ac                 | 1        | 2%      |
| ASRock N68-S3 FX                    | 1        | 2%      |
| ASRock H87M Pro4                    | 1        | 2%      |
| ASRock H410M-ITX/ac                 | 1        | 2%      |
| ASRock H310CM-HDV                   | 1        | 2%      |
| ASRock H270 Pro4                    | 1        | 2%      |
| ASRock B450M Steel Legend           | 1        | 2%      |
| Acer Aspire R3610                   | 1        | 2%      |
| Unknown                             | 1        | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 4        | 8%      |
| ASUS All             | 4        | 8%      |
| Dell Precision       | 2        | 4%      |
| Supermicro X9DA7     | 1        | 2%      |
| Supermicro ReadyDATA | 1        | 2%      |
| Shuttle NC03U        | 1        | 2%      |
| MSI MS-7C52          | 1        | 2%      |
| MSI MS-7C02          | 1        | 2%      |
| MSI MS-7788          | 1        | 2%      |
| MSI MS-7693          | 1        | 2%      |
| MSI MS-7529          | 1        | 2%      |
| MSI MS-7365          | 1        | 2%      |
| Lenovo H50-05        | 1        | 2%      |
| Intel DZ77RE-75K     | 1        | 2%      |
| Huanan X79-8D        | 1        | 2%      |
| HPE ProLiant         | 1        | 2%      |
| HP Z620              | 1        | 2%      |
| HP Z440              | 1        | 2%      |
| HP xw8400            | 1        | 2%      |
| HP t620              | 1        | 2%      |
| HP 500-515na         | 1        | 2%      |
| Gigabyte X150M-PRO   | 1        | 2%      |
| Gigabyte N3160TN     | 1        | 2%      |
| Gigabyte M61SME-S2   | 1        | 2%      |
| Gigabyte 970A-DS3P   | 1        | 2%      |
| Foxconn p6-2390      | 1        | 2%      |
| Biostar X470GTA      | 1        | 2%      |
| ASUS TUF             | 1        | 2%      |
| ASUS SABERTOOTH      | 1        | 2%      |
| ASUS ROG             | 1        | 2%      |
| ASUS Pro             | 1        | 2%      |
| ASUS P5QLD           | 1        | 2%      |
| ASUS M5A97           | 1        | 2%      |
| ASUS A68HM-PLUS      | 1        | 2%      |
| ASRock Z390M-ITX     | 1        | 2%      |
| ASRock N68-S3        | 1        | 2%      |
| ASRock H87M          | 1        | 2%      |
| ASRock H410M-ITX     | 1        | 2%      |
| ASRock H310CM-HDV    | 1        | 2%      |
| ASRock H270          | 1        | 2%      |
| ASRock B450M         | 1        | 2%      |
| Acer Aspire          | 1        | 2%      |
| Unknown              | 1        | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 8        | 16%     |
| 2018 | 6        | 12%     |
| 2017 | 5        | 10%     |
| 2014 | 5        | 10%     |
| 2012 | 5        | 10%     |
| 2020 | 3        | 6%      |
| 2016 | 3        | 6%      |
| 2015 | 3        | 6%      |
| 2011 | 3        | 6%      |
| 2009 | 3        | 6%      |
| 2013 | 2        | 4%      |
| 2008 | 2        | 4%      |
| 2007 | 2        | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 50       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 50       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 14       | 28%     |
| 8.01-16.0   | 8        | 16%     |
| 32.01-64.0  | 7        | 14%     |
| 64.01-256.0 | 6        | 12%     |
| 4.01-8.0    | 5        | 10%     |
| 3.01-4.0    | 5        | 10%     |
| 24.01-32.0  | 3        | 6%      |
| 1.01-2.0    | 2        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 13       | 25%     |
| 4.01-8.0    | 12       | 23.08%  |
| 2.01-3.0    | 9        | 17.31%  |
| 3.01-4.0    | 6        | 11.54%  |
| 0.51-1.0    | 3        | 5.77%   |
| 24.01-32.0  | 2        | 3.85%   |
| 8.01-16.0   | 2        | 3.85%   |
| 0.01-0.5    | 2        | 3.85%   |
| 32.01-64.0  | 1        | 1.92%   |
| 64.01-256.0 | 1        | 1.92%   |
| 16.01-24.0  | 1        | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 22%     |
| 3      | 10       | 20%     |
| 4      | 7        | 14%     |
| 2      | 7        | 14%     |
| 5      | 5        | 10%     |
| 6      | 4        | 8%      |
| 0      | 2        | 4%      |
| 13     | 1        | 2%      |
| 9      | 1        | 2%      |
| 8      | 1        | 2%      |
| 7      | 1        | 2%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 50%     |
| No        | 25       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 66%     |
| Yes       | 17       | 34%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 66%     |
| Yes       | 17       | 34%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 11       | 22%     |
| UK           | 7        | 14%     |
| Italy        | 4        | 8%      |
| Russia       | 3        | 6%      |
| Kazakhstan   | 3        | 6%      |
| Germany      | 3        | 6%      |
| Canada       | 3        | 6%      |
| Sweden       | 2        | 4%      |
| Spain        | 2        | 4%      |
| Japan        | 2        | 4%      |
| Hong Kong    | 2        | 4%      |
| France       | 2        | 4%      |
| Brazil       | 2        | 4%      |
| South Africa | 1        | 2%      |
| Serbia       | 1        | 2%      |
| Portugal     | 1        | 2%      |
| Bulgaria     | 1        | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Yekaterinburg         | 3        | 6%      |
| Ust-Kamenogorsk       | 2        | 4%      |
| Toronto               | 2        | 4%      |
| Springfield           | 2        | 4%      |
| London                | 2        | 4%      |
| Caen                  | 2        | 4%      |
| Weilheim              | 1        | 2%      |
| Verona                | 1        | 2%      |
| Tsuruoka              | 1        | 2%      |
| Tiffin                | 1        | 2%      |
| Stockholm             | 1        | 2%      |
| Sidcup                | 1        | 2%      |
| Sham Shui Po          | 1        | 2%      |
| Santa Cruz do Sul     | 1        | 2%      |
| Saint Paul            | 1        | 2%      |
| Saedinenie            | 1        | 2%      |
| Rome                  | 1        | 2%      |
| Porto Alegre          | 1        | 2%      |
| Paterson              | 1        | 2%      |
| Palma                 | 1        | 2%      |
| Ottawa                | 1        | 2%      |
| Oldham                | 1        | 2%      |
| Naples                | 1        | 2%      |
| Musashino             | 1        | 2%      |
| Milwaukee             | 1        | 2%      |
| Mead                  | 1        | 2%      |
| Lisbon                | 1        | 2%      |
| Lexington             | 1        | 2%      |
| Kowloon               | 1        | 2%      |
| Koblenz               | 1        | 2%      |
| Karaganda             | 1        | 2%      |
| Haar                  | 1        | 2%      |
| Granada               | 1        | 2%      |
| Frosinone             | 1        | 2%      |
| Enskede-Arsta-Vantoer | 1        | 2%      |
| Dallas                | 1        | 2%      |
| Chelmsford            | 1        | 2%      |
| Carrollton            | 1        | 2%      |
| Cape Town             | 1        | 2%      |
| Camp Hill             | 1        | 2%      |
| Belgrade              | 1        | 2%      |
| Belfast               | 1        | 2%      |
| Barry                 | 1        | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 46     | 22%     |
| Seagate             | 20       | 45     | 20%     |
| Samsung Electronics | 14       | 23     | 14%     |
| Toshiba             | 8        | 16     | 8%      |
| Hitachi             | 7        | 10     | 7%      |
| Kingston            | 5        | 6      | 5%      |
| Crucial             | 3        | 3      | 3%      |
| A-DATA Technology   | 3        | 3      | 3%      |
| Intel               | 2        | 2      | 2%      |
| HGST                | 2        | 2      | 2%      |
| Hewlett-Packard     | 2        | 2      | 2%      |
| China               | 2        | 3      | 2%      |
| ZHITAI              | 1        | 2      | 1%      |
| Team                | 1        | 1      | 1%      |
| SK Hynix            | 1        | 1      | 1%      |
| SanDisk             | 1        | 1      | 1%      |
| Patriot             | 1        | 1      | 1%      |
| MAXTOR              | 1        | 1      | 1%      |
| Intenso             | 1        | 1      | 1%      |
| Gigabyte Technology | 1        | 1      | 1%      |
| Fujitsu             | 1        | 1      | 1%      |
| Apple               | 1        | 2      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD20EFRX-68EUZN0 2TB        | 3        | 2.22%   |
| WDC WD1003FZEX-00MK2A0 1TB      | 3        | 2.22%   |
| Samsung SSD 970 EVO 250GB       | 3        | 2.22%   |
| Toshiba MQ01ABD100 1TB          | 2        | 1.48%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 1.48%   |
| Seagate ST4000VN008-2DR166 4TB  | 2        | 1.48%   |
| Seagate ST31000524AS 1TB        | 2        | 1.48%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.48%   |
| Seagate ST2000DM001-1CH164 2TB  | 2        | 1.48%   |
| Seagate ST1000DM010-2EP102 1TB  | 2        | 1.48%   |
| Seagate ST1000DM003-1ER162 1TB  | 2        | 1.48%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 1.48%   |
| Crucial CT500MX500SSD1 500GB    | 2        | 1.48%   |
| ZHITAI SC001 Active 1TB SSD     | 1        | 0.74%   |
| ZHITAI PC005 Active 512GB       | 1        | 0.74%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 0.74%   |
| WDC WD5000BPVT-2 500GB          | 1        | 0.74%   |
| WDC WD5000BPKX-60HPJT0 500GB    | 1        | 0.74%   |
| WDC WD5000AAKX-22ERMA0 500GB    | 1        | 0.74%   |
| WDC WD5000AAKX-00ERMA0 500GB    | 1        | 0.74%   |
| WDC WD5000AAKS-00V0A0 500GB     | 1        | 0.74%   |
| WDC WD5000AAKS-00A7B2 500GB     | 1        | 0.74%   |
| WDC WD40EJRX-89T1XY0 4TB        | 1        | 0.74%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1        | 0.74%   |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 0.74%   |
| WDC WD400BD-60LTA0 40GB         | 1        | 0.74%   |
| WDC WD3200AAJS-65B4A0 320GB     | 1        | 0.74%   |
| WDC WD30EZRX-00SPEB0 3TB        | 1        | 0.74%   |
| WDC WD30EZRX-00M                | 1        | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB        | 1        | 0.74%   |
| WDC WD30EFRX-68AX9N0 3TB        | 1        | 0.74%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 1        | 0.74%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 0.74%   |
| WDC WD2003FZEX-0 2TB            | 1        | 0.74%   |
| WDC WD1600AAJS-00PSA0 160GB     | 1        | 0.74%   |
| WDC WD120EDAZ-11F3RA0 12TB      | 1        | 0.74%   |
| WDC WD10EZRZ-00HTKB0 1TB        | 1        | 0.74%   |
| WDC WD10EZEX-22BN5A0 1TB        | 1        | 0.74%   |
| WDC WD10EZEX-00RKKA0 1TB        | 1        | 0.74%   |
| WDC WD10EZEX-00BN5A0 1TB        | 1        | 0.74%   |
| WDC WD10EURX-61C57Y0 1TB        | 1        | 0.74%   |
| WDC WD10EALS-00Z8A0 1TB         | 1        | 0.74%   |
| WDC WD100EMAZ-00WJTA0 10TB      | 1        | 0.74%   |
| WDC WD1003FZEX-00K3CA0 1TB      | 1        | 0.74%   |
| Toshiba MG07ACA12TE 12TB        | 1        | 0.74%   |
| Toshiba MD04ABA400V 4TB         | 1        | 0.74%   |
| Toshiba HDWD240 4TB             | 1        | 0.74%   |
| Toshiba HDWD110 1TB             | 1        | 0.74%   |
| Toshiba DT01ACA300 3TB          | 1        | 0.74%   |
| Toshiba DT01ACA200 2TB          | 1        | 0.74%   |
| Toshiba DT01ACA100 1TB          | 1        | 0.74%   |
| Team T253X1480G 480GB SSD       | 1        | 0.74%   |
| SK Hynix SHGP31-1000GM-2 1TB    | 1        | 0.74%   |
| Seagate ST980310AS 80GB         | 1        | 0.74%   |
| Seagate ST4000VX000-2AG166 4TB  | 1        | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB  | 1        | 0.74%   |
| Seagate ST380819AS 80GB         | 1        | 0.74%   |
| Seagate ST380011A 80GB          | 1        | 0.74%   |
| Seagate ST3500418AS 500GB       | 1        | 0.74%   |
| Seagate ST3500410AS 500GB       | 1        | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 45     | 34.38%  |
| Seagate             | 20       | 41     | 31.25%  |
| Toshiba             | 8        | 16     | 12.5%   |
| Hitachi             | 7        | 10     | 10.94%  |
| Samsung Electronics | 2        | 2      | 3.13%   |
| HGST                | 2        | 2      | 3.13%   |
| MAXTOR              | 1        | 1      | 1.56%   |
| Hewlett-Packard     | 1        | 1      | 1.56%   |
| Fujitsu             | 1        | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 13     | 26.92%  |
| Kingston            | 5        | 6      | 19.23%  |
| Crucial             | 3        | 3      | 11.54%  |
| China               | 2        | 3      | 7.69%   |
| ZHITAI              | 1        | 1      | 3.85%   |
| Team                | 1        | 1      | 3.85%   |
| SanDisk             | 1        | 1      | 3.85%   |
| Patriot             | 1        | 1      | 3.85%   |
| Intenso             | 1        | 1      | 3.85%   |
| Intel               | 1        | 1      | 3.85%   |
| Hewlett-Packard     | 1        | 1      | 3.85%   |
| Apple               | 1        | 2      | 3.85%   |
| A-DATA Technology   | 1        | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 39       | 119    | 51.32%  |
| SSD     | 23       | 35     | 30.26%  |
| NVMe    | 13       | 15     | 17.11%  |
| Unknown | 1        | 4      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 44       | 149    | 74.58%  |
| NVMe | 13       | 15     | 22.03%  |
| SAS  | 2        | 9      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 57     | 39.51%  |
| 0.51-1.0   | 20       | 42     | 24.69%  |
| 1.01-2.0   | 11       | 15     | 13.58%  |
| 3.01-4.0   | 7        | 18     | 8.64%   |
| 2.01-3.0   | 7        | 15     | 8.64%   |
| 10.01-20.0 | 2        | 5      | 2.47%   |
| 4.01-10.0  | 2        | 2      | 2.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 10       | 19.61%  |
| 501-1000       | 9        | 17.65%  |
| 101-250        | 8        | 15.69%  |
| 1001-2000      | 6        | 11.76%  |
| 251-500        | 5        | 9.8%    |
| 2001-3000      | 5        | 9.8%    |
| 1-20           | 3        | 5.88%   |
| More than 3000 | 2        | 3.92%   |
| 51-100         | 2        | 3.92%   |
| 21-50          | 1        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 12       | 24%     |
| Unknown        | 10       | 20%     |
| 501-1000       | 8        | 16%     |
| 1-20           | 6        | 12%     |
| 251-500        | 5        | 10%     |
| 51-100         | 4        | 8%      |
| More than 3000 | 2        | 4%      |
| 1001-2000      | 2        | 4%      |
| 21-50          | 1        | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000BPKX-60HPJT0 500GB       | 1        | 1      | 3.57%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 1        | 1      | 3.57%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 3.57%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1        | 1      | 3.57%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1        | 2      | 3.57%   |
| WDC WD3200AAJS-65B4A0 320GB        | 1        | 1      | 3.57%   |
| WDC WD30EZRX-00M                   | 1        | 1      | 3.57%   |
| WDC WD30EFRX-68AX9N0 3TB           | 1        | 4      | 3.57%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 2      | 3.57%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 1      | 3.57%   |
| WDC WD10EALS-00Z8A0 1TB            | 1        | 2      | 3.57%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 2      | 3.57%   |
| Seagate ST380011A 80GB             | 1        | 2      | 3.57%   |
| Seagate ST3500418AS 500GB          | 1        | 1      | 3.57%   |
| Seagate ST3500410AS 500GB          | 1        | 1      | 3.57%   |
| Seagate ST31000524AS 1TB           | 1        | 1      | 3.57%   |
| Seagate ST3000VX006-1HH166 3TB     | 1        | 1      | 3.57%   |
| Seagate ST2000DL003-9VT166 2TB     | 1        | 1      | 3.57%   |
| Seagate ST1000VM002-1SD102 1TB     | 1        | 1      | 3.57%   |
| Seagate ST1000NM0011 1TB           | 1        | 2      | 3.57%   |
| Seagate ST1000DM003-1ER162 1TB     | 1        | 2      | 3.57%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1        | 1      | 3.57%   |
| MAXTOR 4G120J6 128GB               | 1        | 1      | 3.57%   |
| Intel SSDSA2M080G2GC 80GB          | 1        | 1      | 3.57%   |
| Hitachi HUA723030ALA640 3TB        | 1        | 1      | 3.57%   |
| Hitachi HDS721050CLA660 500GB      | 1        | 1      | 3.57%   |
| Hitachi HDS721016CLA382 160GB      | 1        | 1      | 3.57%   |
| HGST HDN726040ALE614 4TB           | 1        | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 10       | 19     | 40%     |
| Seagate | 8        | 12     | 32%     |
| Hitachi | 3        | 3      | 12%     |
| SanDisk | 1        | 1      | 4%      |
| MAXTOR  | 1        | 1      | 4%      |
| Intel   | 1        | 1      | 4%      |
| HGST    | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 10       | 19     | 43.48%  |
| Seagate | 8        | 12     | 34.78%  |
| Hitachi | 3        | 3      | 13.04%  |
| MAXTOR  | 1        | 1      | 4.35%   |
| HGST    | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 36     | 90.91%  |
| SSD  | 2        | 2      | 9.09%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 42       | 120    | 61.76%  |
| Malfunc  | 22       | 38     | 32.35%  |
| Detected | 4        | 15     | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 29       | 37.18%  |
| AMD                         | 17       | 21.79%  |
| Samsung Electronics         | 8        | 10.26%  |
| Marvell Technology Group    | 4        | 5.13%   |
| ASMedia Technology          | 4        | 5.13%   |
| Nvidia                      | 3        | 3.85%   |
| Realtek Semiconductor       | 2        | 2.56%   |
| JMicron Technology          | 2        | 2.56%   |
| Broadcom / LSI              | 2        | 2.56%   |
| Yangtze Memory Technologies | 1        | 1.28%   |
| SK Hynix                    | 1        | 1.28%   |
| Silicon Image               | 1        | 1.28%   |
| Sandisk                     | 1        | 1.28%   |
| Phison Electronics          | 1        | 1.28%   |
| Adaptec                     | 1        | 1.28%   |
| 3ware                       | 1        | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 12.75%  |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 6.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 5.88%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 5.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 2.94%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.94%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 1.96%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.96%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.96%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 1.96%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.96%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.96%   |
| Yangtze Memory Non-Volatile memory controller                                           | 1        | 0.98%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.98%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.98%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.98%   |
| Samsung Electronics SATA controller                                                     | 1        | 0.98%   |
| Samsung Apple PCIe SSD                                                                  | 1        | 0.98%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.98%   |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 0.98%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.98%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.98%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.98%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.98%   |
| JMicron JMB58x AHCI SATA controller                                                     | 1        | 0.98%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.98%   |
| Intel SSD 600P Series                                                                   | 1        | 0.98%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.98%   |
| Intel C608 chipset Dual 4-Port SATA/SAS Storage Control Unit                            | 1        | 0.98%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 0.98%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.98%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.98%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.98%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.98%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 0.98%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 0.98%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 0.98%   |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 1        | 0.98%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 0.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.98%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 0.98%   |
| Broadcom / LSI SAS2116 PCI-Express Fusion-MPT SAS-2 [Meteor]                            | 1        | 0.98%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 0.98%   |
| ASMedia 106x SATA/RAID Controller                                                       | 1        | 0.98%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.98%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 0.98%   |
| Adaptec SCSI storage controller                                                         | 1        | 0.98%   |
| 3ware 9650SE SATA-II RAID PCIe                                                          | 1        | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 41       | 56.94%  |
| NVMe | 13       | 18.06%  |
| IDE  | 9        | 12.5%   |
| RAID | 4        | 5.56%   |
| SAS  | 4        | 5.56%   |
| SCSI | 1        | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 62%     |
| AMD    | 19       | 38%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 2        | 4%      |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 4%      |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 4%      |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 4%      |
| AMD FX-8350 Eight-Core Processor            | 2        | 4%      |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 2%      |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz         | 1        | 2%      |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 2%      |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 2%      |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1        | 2%      |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 2%      |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 2%      |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 2%      |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 2%      |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 2%      |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 2%      |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 2%      |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 2%      |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 2%      |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 2%      |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 2%      |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 2%      |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1        | 2%      |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2%      |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 2%      |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 2%      |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 2%      |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz       | 1        | 2%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 2%      |
| Intel Celeron CPU N3160 @ 1.60GHz           | 1        | 2%      |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 2%      |
| AMD Ryzen 9 5950X 16-Core Processor         | 1        | 2%      |
| AMD Ryzen 9 3950X 16-Core Processor         | 1        | 2%      |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 2%      |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 2%      |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 2%      |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1        | 2%      |
| AMD GX-415GA SOC with Radeon HD Graphics    | 1        | 2%      |
| AMD FX-8320 Eight-Core Processor            | 1        | 2%      |
| AMD FX-6300 Six-Core Processor              | 1        | 2%      |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 1        | 2%      |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 1        | 2%      |
| AMD A4-7300 APU with Radeon HD Graphics     | 1        | 2%      |
| AMD A10-5700 APU with Radeon HD Graphics    | 1        | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 10       | 20%     |
| Intel Core i5      | 6        | 12%     |
| Intel Core i7      | 5        | 10%     |
| AMD Ryzen 7        | 4        | 8%      |
| AMD Ryzen 5        | 4        | 8%      |
| AMD FX             | 4        | 8%      |
| Intel Pentium      | 2        | 4%      |
| Intel Core 2 Quad  | 2        | 4%      |
| AMD Ryzen 9        | 2        | 4%      |
| Intel Pentium Gold | 1        | 2%      |
| Intel Pentium Dual | 1        | 2%      |
| Intel Core i3      | 1        | 2%      |
| Intel Core 2 Duo   | 1        | 2%      |
| Intel Celeron      | 1        | 2%      |
| Intel Atom         | 1        | 2%      |
| AMD GX             | 1        | 2%      |
| AMD Athlon 64 X2   | 1        | 2%      |
| AMD A8             | 1        | 2%      |
| AMD A4             | 1        | 2%      |
| AMD A10            | 1        | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 20       | 40%     |
| 2      | 9        | 18%     |
| 8      | 6        | 12%     |
| 6      | 6        | 12%     |
| 16     | 4        | 8%      |
| 14     | 1        | 2%      |
| 12     | 1        | 2%      |
| 10     | 1        | 2%      |
| 3      | 1        | 2%      |
| 1      | 1        | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 92%     |
| 2      | 4        | 8%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 34       | 68%     |
| 1      | 16       | 32%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 50       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 18%     |
| 0x206d7    | 4        | 8%      |
| 0x306c3    | 3        | 6%      |
| 0x906ed    | 2        | 4%      |
| 0x906ea    | 2        | 4%      |
| 0x306f2    | 2        | 4%      |
| 0x306a9    | 2        | 4%      |
| 0x1067a    | 2        | 4%      |
| 0x08701021 | 2        | 4%      |
| 0x08701013 | 2        | 4%      |
| 0x06001119 | 2        | 4%      |
| 0x06000822 | 2        | 4%      |
| 0xa0653    | 1        | 2%      |
| 0x906e9    | 1        | 2%      |
| 0x6fd      | 1        | 2%      |
| 0x406c4    | 1        | 2%      |
| 0x306e4    | 1        | 2%      |
| 0x206a7    | 1        | 2%      |
| 0x106e5    | 1        | 2%      |
| 0x106c2    | 1        | 2%      |
| 0x0a201016 | 1        | 2%      |
| 0x08108109 | 1        | 2%      |
| 0x0810100b | 1        | 2%      |
| 0x08001138 | 1        | 2%      |
| 0x07030105 | 1        | 2%      |
| 0x07000110 | 1        | 2%      |
| 0x06000852 | 1        | 2%      |
| 0x00000000 | 1        | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 7        | 14%     |
| Zen 2       | 6        | 12%     |
| SandyBridge | 6        | 12%     |
| Piledriver  | 6        | 12%     |
| Haswell     | 6        | 12%     |
| IvyBridge   | 3        | 6%      |
| Core        | 3        | 6%      |
| Zen         | 2        | 4%      |
| Penryn      | 2        | 4%      |
| Zen+        | 1        | 2%      |
| Zen 3       | 1        | 2%      |
| Silvermont  | 1        | 2%      |
| Puma        | 1        | 2%      |
| Nehalem     | 1        | 2%      |
| K8 Hammer   | 1        | 2%      |
| Jaguar      | 1        | 2%      |
| CometLake   | 1        | 2%      |
| Bonnell     | 1        | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 20       | 40%     |
| Nvidia                     | 18       | 36%     |
| Intel                      | 10       | 20%     |
| Matrox Electronics Systems | 2        | 4%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5        | 9.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 3.85%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 3.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 3.85%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2        | 3.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.92%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 1.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.92%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 1.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.92%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.92%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.92%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.92%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1        | 1.92%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 1.92%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1        | 1.92%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 1.92%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1        | 1.92%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1        | 1.92%   |
| Nvidia C79 [ION]                                                                         | 1        | 1.92%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.92%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.92%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 1.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.92%   |
| Intel HD Graphics 620                                                                    | 1        | 1.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.92%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.92%   |
| AMD Richland [Radeon HD 8470D]                                                           | 1        | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.92%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 1.92%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 1        | 1.92%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1        | 1.92%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.92%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 1        | 1.92%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 1.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 1.92%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 1        | 1.92%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 1        | 1.92%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 1.92%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1        | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 20       | 40%     |
| 1 x Nvidia     | 16       | 32%     |
| 1 x Intel      | 9        | 18%     |
| 1 x Matrox     | 2        | 4%      |
| Other          | 1        | 2%      |
| 2 x Nvidia     | 1        | 2%      |
| Intel + Nvidia | 1        | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 64%     |
| Proprietary | 12       | 24%     |
| Unknown     | 6        | 12%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 38%     |
| 0.51-1.0   | 9        | 18%     |
| 7.01-8.0   | 5        | 10%     |
| 3.01-4.0   | 5        | 10%     |
| 1.01-2.0   | 5        | 10%     |
| 5.01-6.0   | 2        | 4%      |
| 8.01-16.0  | 2        | 4%      |
| 0.01-0.5   | 2        | 4%      |
| 2.01-3.0   | 1        | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 15.69%  |
| Dell                 | 5        | 9.8%    |
| Hewlett-Packard      | 4        | 7.84%   |
| Goldstar             | 4        | 7.84%   |
| BenQ                 | 4        | 7.84%   |
| Ancor Communications | 4        | 7.84%   |
| Acer                 | 4        | 7.84%   |
| ViewSonic            | 2        | 3.92%   |
| Lenovo               | 2        | 3.92%   |
| Xiaomi               | 1        | 1.96%   |
| Wacom                | 1        | 1.96%   |
| Unknown              | 1        | 1.96%   |
| Toshiba              | 1        | 1.96%   |
| ONN                  | 1        | 1.96%   |
| NEC Computers        | 1        | 1.96%   |
| JVC                  | 1        | 1.96%   |
| IOD                  | 1        | 1.96%   |
| Iiyama               | 1        | 1.96%   |
| Gigabyte Technology  | 1        | 1.96%   |
| GDH                  | 1        | 1.96%   |
| Eizo                 | 1        | 1.96%   |
| ASUSTek Computer     | 1        | 1.96%   |
| AOC                  | 1        | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                    | 1        | 1.89%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1        | 1.89%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1        | 1.89%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1        | 1.89%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 1.89%   |
| Toshiba TV TSB0206 1920x1080 700x390mm 31.5-inch                      | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1        | 1.89%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1        | 1.89%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch    | 1        | 1.89%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1        | 1.89%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1        | 1.89%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 1.89%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                   | 1        | 1.89%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch       | 1        | 1.89%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1        | 1.89%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1        | 1.89%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                         | 1        | 1.89%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1        | 1.89%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                | 1        | 1.89%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch         | 1        | 1.89%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch          | 1        | 1.89%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 1.89%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch            | 1        | 1.89%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                  | 1        | 1.89%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                  | 1        | 1.89%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch             | 1        | 1.89%   |
| Goldstar E1641 GSM8B3E 1366x768 350x200mm 15.9-inch                   | 1        | 1.89%   |
| Goldstar BK750Y GSM5B3E 1920x1080 600x340mm 27.2-inch                 | 1        | 1.89%   |
| Goldstar BK750Y GSM5B3D 1920x1080 480x270mm 21.7-inch                 | 1        | 1.89%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 600x330mm 27.0-inch        | 1        | 1.89%   |
| GDH PHILCO GDH0030 1920x540 1150x650mm 52.0-inch                      | 1        | 1.89%   |
| Eizo M1700 ENC1788 1280x1024 338x271mm 17.1-inch                      | 1        | 1.89%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 1.89%   |
| Dell LCD Monitor U2312HM 1920x1080                                    | 1        | 1.89%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 1        | 1.89%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch              | 1        | 1.89%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                     | 1        | 1.89%   |
| BenQ VZ2770H BNQ7B3C 1920x1080 598x336mm 27.0-inch                    | 1        | 1.89%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1        | 1.89%   |
| BenQ EW2420 BNQ7923 1920x1080 530x300mm 24.0-inch                     | 1        | 1.89%   |
| BenQ BenQG2222HDL BNQ785A 1920x1080 478x269mm 21.6-inch               | 1        | 1.89%   |
| ASUSTek Computer VA24DQLB AUS2482 1920x1080 527x296mm 23.8-inch       | 1        | 1.89%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1        | 1.89%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 1        | 1.89%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 1        | 1.89%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 1.89%   |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch | 1        | 1.89%   |
| Acer RC241YU ACR0600 2560x1440 530x300mm 24.0-inch                    | 1        | 1.89%   |
| Acer K222HQL ACR040D 1920x1080 477x268mm 21.5-inch                    | 1        | 1.89%   |
| Acer GN246HL ACR02F9 1920x1080 530x300mm 24.0-inch                    | 1        | 1.89%   |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1        | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 26       | 52%     |
| 1280x1024 (SXGA)   | 6        | 12%     |
| 2560x1440 (QHD)    | 3        | 6%      |
| 1920x1200 (WUXGA)  | 3        | 6%      |
| 1366x768 (WXGA)    | 3        | 6%      |
| 3840x2160 (4K)     | 2        | 4%      |
| 1680x1050 (WSXGA+) | 2        | 4%      |
| 3440x1440          | 1        | 2%      |
| 2880x1800          | 1        | 2%      |
| 2288x1287          | 1        | 2%      |
| 1920x540           | 1        | 2%      |
| 1600x1200          | 1        | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 17.31%  |
| 27      | 8        | 15.38%  |
| 21      | 8        | 15.38%  |
| 23      | 6        | 11.54%  |
| 17      | 4        | 7.69%   |
| Unknown | 4        | 7.69%   |
| 20      | 2        | 3.85%   |
| 19      | 2        | 3.85%   |
| 18      | 2        | 3.85%   |
| 15      | 2        | 3.85%   |
| 142     | 1        | 1.92%   |
| 74      | 1        | 1.92%   |
| 52      | 1        | 1.92%   |
| 34      | 1        | 1.92%   |
| 22      | 1        | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 21       | 41.18%  |
| 401-500        | 13       | 25.49%  |
| 301-350        | 6        | 11.76%  |
| Unknown        | 4        | 7.84%   |
| 351-400        | 2        | 3.92%   |
| More than 2000 | 1        | 1.96%   |
| 701-800        | 1        | 1.96%   |
| 601-700        | 1        | 1.96%   |
| 1501-2000      | 1        | 1.96%   |
| 1001-1500      | 1        | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 27       | 57.45%  |
| 16/10   | 6        | 12.77%  |
| 5/4     | 4        | 8.51%   |
| Unknown | 3        | 6.38%   |
| 6/5     | 2        | 4.26%   |
| 4/3     | 1        | 2.13%   |
| 32/9    | 1        | 2.13%   |
| 3/2     | 1        | 2.13%   |
| 21/9    | 1        | 2.13%   |
| 1.00    | 1        | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 36%     |
| 301-350        | 8        | 16%     |
| 141-150        | 6        | 12%     |
| 251-300        | 4        | 8%      |
| 151-200        | 4        | 8%      |
| Unknown        | 4        | 8%      |
| More than 1000 | 3        | 6%      |
| 101-110        | 2        | 4%      |
| 351-500        | 1        | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 29       | 55.77%  |
| 101-120 | 12       | 23.08%  |
| 121-160 | 4        | 7.69%   |
| Unknown | 4        | 7.69%   |
| 1-50    | 3        | 5.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 64%     |
| 0     | 8        | 16%     |
| 2     | 7        | 14%     |
| 3     | 3        | 6%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 25       | 37.31%  |
| Intel                    | 24       | 35.82%  |
| Qualcomm Atheros         | 4        | 5.97%   |
| TP-Link                  | 2        | 2.99%   |
| Ralink Technology        | 2        | 2.99%   |
| Nvidia                   | 2        | 2.99%   |
| Broadcom                 | 2        | 2.99%   |
| VIA Technologies         | 1        | 1.49%   |
| Ralink                   | 1        | 1.49%   |
| Micro Star International | 1        | 1.49%   |
| Mellanox Technologies    | 1        | 1.49%   |
| Chelsio Communications   | 1        | 1.49%   |
| Broadcom Limited         | 1        | 1.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19       | 24.05%  |
| Intel I211 Gigabit Network Connection                                         | 5        | 6.33%   |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 5.06%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 5.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 3.8%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 2.53%   |
| Ralink MT7601U Wireless Adapter                                               | 2        | 2.53%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 2.53%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 2.53%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 1.27%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                         | 1        | 1.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 1.27%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.27%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 1.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 1.27%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 1.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 1.27%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 1.27%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 1.27%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 1.27%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 1.27%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.27%   |
| Intel Wireless 7260                                                           | 1        | 1.27%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.27%   |
| Intel Ethernet Connection I217-V                                              | 1        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.27%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 1.27%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 1.27%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.27%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 1.27%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 1.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 1.27%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1        | 1.27%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 5        | 29.41%  |
| Realtek Semiconductor    | 3        | 17.65%  |
| Qualcomm Atheros         | 3        | 17.65%  |
| TP-Link                  | 2        | 11.76%  |
| Ralink Technology        | 2        | 11.76%  |
| Ralink                   | 1        | 5.88%   |
| Micro Star International | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 11.76%  |
| Ralink MT7601U Wireless Adapter                                            | 2        | 11.76%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 11.76%  |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 5.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 5.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 5.88%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 5.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 5.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 5.88%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 5.88%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 5.88%   |
| Intel Wireless-AC 9260                                                     | 1        | 5.88%   |
| Intel Wireless 7260                                                        | 1        | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 24       | 42.86%  |
| Intel                  | 22       | 39.29%  |
| Qualcomm Atheros       | 2        | 3.57%   |
| Nvidia                 | 2        | 3.57%   |
| Broadcom               | 2        | 3.57%   |
| VIA Technologies       | 1        | 1.79%   |
| Mellanox Technologies  | 1        | 1.79%   |
| Chelsio Communications | 1        | 1.79%   |
| Broadcom Limited       | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19       | 30.65%  |
| Intel I211 Gigabit Network Connection                                         | 5        | 8.06%   |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 6.45%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 6.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 4.84%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 3.23%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 3.23%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 1.61%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 1.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 1.61%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 1.61%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 1.61%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 1.61%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.61%   |
| Intel Ethernet Connection I217-V                                              | 1        | 1.61%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.61%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 1.61%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.61%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.61%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 1.61%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 1.61%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 1.61%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1        | 1.61%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 74.63%  |
| WiFi     | 17       | 25.37%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 42       | 87.5%   |
| WiFi     | 6        | 12.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 54%     |
| 2     | 15       | 30%     |
| 4     | 3        | 6%      |
| 3     | 3        | 6%      |
| 5     | 1        | 2%      |
| 0     | 1        | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 46       | 92%     |
| Yes  | 4        | 8%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 11       | 64.71%  |
| Intel                    | 4        | 23.53%  |
| Micro Star International | 1        | 5.88%   |
| Broadcom                 | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 64.71%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 11.76%  |
| Micro Star International Bluetooth Device           | 1        | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5.88%   |
| Intel Bluetooth wireless interface                  | 1        | 5.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 24       | 32.43%  |
| AMD                 | 23       | 31.08%  |
| Nvidia              | 15       | 20.27%  |
| Creative Labs       | 7        | 9.46%   |
| VIA Technologies    | 1        | 1.35%   |
| M-Audio             | 1        | 1.35%   |
| EGO SYStems         | 1        | 1.35%   |
| C-Media Electronics | 1        | 1.35%   |
| ASUSTek Computer    | 1        | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 7        | 7.61%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6        | 6.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5        | 5.43%   |
| AMD FCH Azalia Controller                                                                         | 4        | 4.35%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3        | 3.26%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 3.26%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 3        | 3.26%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 3.26%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 2.17%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2        | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 2.17%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 2.17%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 2.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 2.17%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 1        | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 1.09%   |
| Nvidia MCP79 High Definition Audio                                                                | 1        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 1.09%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 1.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.09%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 1.09%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 1.09%   |
| M-Audio M-Audio MobilePre                                                                         | 1        | 1.09%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 1.09%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 1.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 1.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 1.09%   |
| EGO SYStems U24XL                                                                                 | 1        | 1.09%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                                                 | 1        | 1.09%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1        | 1.09%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.09%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1        | 1.09%   |
| C-Media Electronics USB Audio Device                                                              | 1        | 1.09%   |
| ASUSTek Computer XONAR SOUND CARD                                                                 | 1        | 1.09%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1        | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 1.09%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]                             | 1        | 1.09%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 1.09%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 12       | 22.22%  |
| Corsair             | 7        | 12.96%  |
| Unknown             | 6        | 11.11%  |
| Samsung Electronics | 6        | 11.11%  |
| SK Hynix            | 5        | 9.26%   |
| Crucial             | 5        | 9.26%   |
| Transcend           | 2        | 3.7%    |
| Team                | 2        | 3.7%    |
| Micron Technology   | 2        | 3.7%    |
| Strontium           | 1        | 1.85%   |
| Silicon Power       | 1        | 1.85%   |
| HPE                 | 1        | 1.85%   |
| Gloway              | 1        | 1.85%   |
| G.Skill             | 1        | 1.85%   |
| AMD                 | 1        | 1.85%   |
| A-DATA Technology   | 1        | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 3.28%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s          | 2        | 3.28%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                   | 1        | 1.64%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s               | 1        | 1.64%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1        | 1.64%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                      | 1        | 1.64%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 1.64%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 1.64%   |
| Transcend RAM TS256MLQ72V6U 2048MB DIMM DDR2 667MT/s        | 1        | 1.64%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1        | 1.64%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1        | 1.64%   |
| SK Hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1        | 1.64%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1        | 1.64%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s        | 1        | 1.64%   |
| SK Hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 1333MT/s     | 1        | 1.64%   |
| SK Hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s        | 1        | 1.64%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s   | 1        | 1.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1        | 1.64%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 1.64%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.64%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s        | 1        | 1.64%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 1.64%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 1.64%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.64%   |
| Micron RAM 36KSF1G72PZ-1G4K1 8192MB DIMM DDR3 1333MT/s      | 1        | 1.64%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8192MB DIMM DDR3 1866MT/s      | 1        | 1.64%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s        | 1        | 1.64%   |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s             | 1        | 1.64%   |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 1.64%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s        | 1        | 1.64%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s        | 1        | 1.64%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 1.64%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s         | 1        | 1.64%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s      | 1        | 1.64%   |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR2 800MT/s      | 1        | 1.64%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s    | 1        | 1.64%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s       | 1        | 1.64%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s    | 1        | 1.64%   |
| Kingston RAM 9965669-009.A00G 8192MB DIMM DDR4 2133MT/s     | 1        | 1.64%   |
| Kingston RAM 9905663-031.A00G 16GB SODIMM DDR4 2400MT/s     | 1        | 1.64%   |
| HPE RAM 879526-091 8192MB DIMM DDR4 2666MT/s                | 1        | 1.64%   |
| Gloway RAM TYA4U2666D19161C 16GB DIMM DDR4 2667MT/s         | 1        | 1.64%   |
| G.Skill RAM F4-3200C16-16GTZSW 16384MB DIMM DDR4 3200MT/s   | 1        | 1.64%   |
| Crucial RAM BLT4G3D1869DT1TX0. 4GB DIMM DDR3 1867MT/s       | 1        | 1.64%   |
| Crucial RAM BLT4G3D1608DT1TX0. 4GB DIMM DDR3 1600MT/s       | 1        | 1.64%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8192MB DIMM DDR4 3600MT/s  | 1        | 1.64%   |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s     | 1        | 1.64%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s      | 1        | 1.64%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s       | 1        | 1.64%   |
| Crucial RAM BLS16G4D26BFSC.16FD 16384MB DIMM DDR4 2666MT/s  | 1        | 1.64%   |
| Corsair RAM CMZ8GX3M1A1600C10 8192MB DIMM DDR3 1600MT/s     | 1        | 1.64%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s       | 1        | 1.64%   |
| Corsair RAM CMY32GX3M4A16 8192MB DIMM DDR3 667MT/s          | 1        | 1.64%   |
| Corsair RAM CMY16GX3M2A2400C11 8GB DIMM DDR3 2400MT/s       | 1        | 1.64%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s       | 1        | 1.64%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s      | 1        | 1.64%   |
| Corsair RAM CMK16GX4M1A2666C16 16GB DIMM DDR4 2667MT/s      | 1        | 1.64%   |
| AMD RAM R534G1601S1SL 4096MB DIMM DDR3 1600MT/s             | 1        | 1.64%   |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1        | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 22       | 45.83%  |
| DDR4    | 19       | 39.58%  |
| DDR2    | 3        | 6.25%   |
| SDRAM   | 2        | 4.17%   |
| DDR     | 1        | 2.08%   |
| Unknown | 1        | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 43       | 89.58%  |
| SODIMM  | 3        | 6.25%   |
| RIMM    | 1        | 2.08%   |
| FB-DIMM | 1        | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 34.62%  |
| 4096  | 14       | 26.92%  |
| 16384 | 7        | 13.46%  |
| 2048  | 6        | 11.54%  |
| 1024  | 4        | 7.69%   |
| 32768 | 3        | 5.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 25.49%  |
| 2400    | 5        | 9.8%    |
| 3200    | 4        | 7.84%   |
| 667     | 4        | 7.84%   |
| 3600    | 3        | 5.88%   |
| 1333    | 3        | 5.88%   |
| 2667    | 2        | 3.92%   |
| 2666    | 2        | 3.92%   |
| 2133    | 2        | 3.92%   |
| 1867    | 2        | 3.92%   |
| 1866    | 2        | 3.92%   |
| 800     | 2        | 3.92%   |
| Unknown | 2        | 3.92%   |
| 65535   | 1        | 1.96%   |
| 3800    | 1        | 1.96%   |
| 3533    | 1        | 1.96%   |
| 2000    | 1        | 1.96%   |
| 1066    | 1        | 1.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 37.5%   |
| Brother Industries  | 2        | 25%     |
| QinHeng Electronics | 1        | 12.5%   |
| Dell                | 1        | 12.5%   |
| Canon               | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| QinHeng CH340S               | 1        | 12.5%   |
| HP OfficeJet Pro 9010 series | 1        | 12.5%   |
| HP ENVY 4520 series          | 1        | 12.5%   |
| HP ENVY 4500 series          | 1        | 12.5%   |
| Dell 2330d Laser Printer     | 1        | 12.5%   |
| Canon CanoScan LiDE 300      | 1        | 12.5%   |
| Brother Printer              | 1        | 12.5%   |
| Brother HL-L2320D series     | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 50%     |
| Hewlett-Packard | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 50%     |
| HP ScanJet 5590                               | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 8        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C310            | 1        | 12.5%   |
| Logitech Webcam C300            | 1        | 12.5%   |
| Logitech Webcam C270            | 1        | 12.5%   |
| Logitech Webcam C170            | 1        | 12.5%   |
| Logitech QuickCam Pro 9000      | 1        | 12.5%   |
| Logitech HD Webcam C525         | 1        | 12.5%   |
| Logitech HD Pro Webcam C920     | 1        | 12.5%   |
| Logitech C922 Pro Stream Webcam | 1        | 12.5%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| STMicroelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 32       | 64%     |
| 1     | 7        | 14%     |
| 4     | 4        | 8%      |
| 2     | 4        | 8%      |
| 3     | 3        | 6%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 9        | 25.71%  |
| Graphics card            | 7        | 20%     |
| Communication controller | 6        | 17.14%  |
| Net/wireless             | 4        | 11.43%  |
| Unassigned class         | 3        | 8.57%   |
| Storage/ata              | 1        | 2.86%   |
| Net/ethernet             | 1        | 2.86%   |
| Fingerprint reader       | 1        | 2.86%   |
| Chipcard                 | 1        | 2.86%   |
| Card reader              | 1        | 2.86%   |
| Bluetooth                | 1        | 2.86%   |

