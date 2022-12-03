Ubuntu MATE 22.04 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 64

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock   | 990FX Extreme3              | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| HP       | 1998                        | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| MSI      | B75A-IE35                   | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| ASUSTek  | TUF Gaming B560M-PLUS       | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASRock   | Z77 Extreme4                | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| Gigabyte | B450M DS3H-CF               | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek  | Z170 PRO GAMING/AURA        | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek  | Z170 PRO GAMING/AURA        | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek  | ROG STRIX Z590-E GAMING ... | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| MSI      | H310M PRO-VDH PLUS          | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI      | H310M PRO-VDH PLUS          | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| ASUSTek  | M5A78L LE                   | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo   | T530-28ICB                  | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| MSI      | B550-A PRO                  | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo   | T530-28ICB                  | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek  | PRIME B450-PLUS             | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo   | SHARKBAY SDK0E50510 PRO     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo   | SHARKBAY SDK0E50510 PRO     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek  | PRIME B450-PLUS             | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek  | K30AD_M31AD_M51AD_M32AD     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| MSI      | H81M-P33                    | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock   | HM55-HT                     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| MSI      | 870-G45                     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek  | ROG STRIX Z690-A GAMING ... | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek  | M2A74-AM                    | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek  | M2A74-AM                    | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| ASUSTek  | P7P55 LX                    | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer     | Aspire X3950                | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek  | P5GZ-MX                     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock   | B450 Gaming-ITX/ac          | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| HP       | 2ADC                        | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| HP       | 18E4                        | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP       | 3397                        | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Lenovo   | 3111 SDK0J40697 WIN 3305... | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| AZW      | GK55                        | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| MSI      | H170M PRO-VDH               | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| Dell     | 08NPPY A00                  | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell     | 08NPPY A00                  | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| MSI      | MS-77311                    | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP       | 8433 11                     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Dell     | 0KWVT8 A03                  | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell     | 0KWVT8 A03                  | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| MSI      | 2AE0                        | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI      | 2AE0                        | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Medion   | MS-7797                     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Dell     | 0GM819                      | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Gigabyte | Z87-HD3                     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| HP       | 3646h                       | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Gigabyte | Z87-HD3                     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP       | 8169                        | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP       | 8169                        | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| Acer     | Aspire X3950                | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown  | Unknown                     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| HP       | 3397                        | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte | B360M AORUS Gaming 3-CF     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| ASUSTek  | P5G41T-M LX2/BR             | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| Unknown  | HX90                        | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| MSI      | B450 TOMAHAWK MAX           | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| HP       | 8433 11                     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| Gigabyte | X99P-SLI-CF                 | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek  | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek  | PRIME B550-PLUS             | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek  | PRIME B550-PLUS             | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek  | ROG Maximus XIII HERO       | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-47-generic | 11       | 22%     |
| 5.15.0-48-generic | 6        | 12%     |
| 5.15.0-50-generic | 5        | 10%     |
| 5.15.0-52-generic | 4        | 8%      |
| 5.15.0-46-generic | 3        | 6%      |
| 5.15.0-40-generic | 3        | 6%      |
| 5.15.0-27-generic | 3        | 6%      |
| 5.15.0-41-generic | 2        | 4%      |
| 5.15.0-37-generic | 2        | 4%      |
| 5.15.0-25-generic | 2        | 4%      |
| 5.18.0-1-generic  | 1        | 2%      |
| 5.15.0-43-generic | 1        | 2%      |
| 5.15.0-39-generic | 1        | 2%      |
| 5.15.0-35-generic | 1        | 2%      |
| 5.15.0-30-generic | 1        | 2%      |
| 5.15.0-22-generic | 1        | 2%      |
| 5.15.0-11-generic | 1        | 2%      |
| 5.13.0-52-generic | 1        | 2%      |
| 5.13.0-19-generic | 1        | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 46       | 93.88%  |
| 5.13.0  | 2        | 4.08%   |
| 5.18.0  | 1        | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 46       | 93.88%  |
| 5.13    | 2        | 4.08%   |
| 5.18    | 1        | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 48       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MATE | 47       | 97.92%  |
| KDE5 | 1        | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 47       | 97.92%  |
| Wayland | 1        | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 40       | 81.63%  |
| Unknown | 5        | 10.2%   |
| GDM3    | 4        | 8.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 17       | 35.42%  |
| fr_FR | 6        | 12.5%   |
| it_IT | 4        | 8.33%   |
| en_AU | 3        | 6.25%   |
| de_DE | 3        | 6.25%   |
| pt_BR | 2        | 4.17%   |
| hr_HR | 2        | 4.17%   |
| en_CA | 2        | 4.17%   |
| de_CH | 2        | 4.17%   |
| ru_RU | 1        | 2.08%   |
| nl_NL | 1        | 2.08%   |
| fi_FI | 1        | 2.08%   |
| es_PE | 1        | 2.08%   |
| es_AR | 1        | 2.08%   |
| en_IL | 1        | 2.08%   |
| en_GB | 1        | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 59.18%  |
| EFI  | 20       | 40.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 46       | 93.88%  |
| Zfs   | 1        | 2.04%   |
| Xfs   | 1        | 2.04%   |
| Btrfs | 1        | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 27       | 55.1%   |
| Unknown | 18       | 36.73%  |
| MBR     | 4        | 8.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 85.42%  |
| Yes       | 7        | 14.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 57.14%  |
| Yes       | 21       | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 29.17%  |
| MSI                 | 9        | 18.75%  |
| Hewlett-Packard     | 8        | 16.67%  |
| ASRock              | 4        | 8.33%   |
| Gigabyte Technology | 3        | 6.25%   |
| Dell                | 3        | 6.25%   |
| Lenovo              | 2        | 4.17%   |
| Unknown             | 2        | 4.17%   |
| Medion              | 1        | 2.08%   |
| AZW                 | 1        | 2.08%   |
| Acer                | 1        | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| HP Compaq Elite 8300 SFF             | 2        | 4.17%   |
| Unknown                              | 2        | 4.17%   |
| MSI p6-2330                          | 1        | 2.08%   |
| MSI MS-7C56                          | 1        | 2.08%   |
| MSI MS-7C09                          | 1        | 2.08%   |
| MSI MS-7C02                          | 1        | 2.08%   |
| MSI MS-7982                          | 1        | 2.08%   |
| MSI MS-7817                          | 1        | 2.08%   |
| MSI MS-7758                          | 1        | 2.08%   |
| MSI MS-7599                          | 1        | 2.08%   |
| MSI B02311                           | 1        | 2.08%   |
| Medion MS-7797                       | 1        | 2.08%   |
| Lenovo ThinkCentre M710q 10MQSC0N00  | 1        | 2.08%   |
| Lenovo T530-28ICB                    | 1        | 2.08%   |
| HP ProDesk 600 G2 DM                 | 1        | 2.08%   |
| HP Pavilion 590-p0049 3LC38AA        | 1        | 2.08%   |
| HP EliteDesk 800 G1 TWR              | 1        | 2.08%   |
| HP EliteDesk 800 G1 SFF              | 1        | 2.08%   |
| HP Compaq 8000 Elite SFF PC          | 1        | 2.08%   |
| HP 23-d027c                          | 1        | 2.08%   |
| Gigabyte Z87-HD3                     | 1        | 2.08%   |
| Gigabyte X99P-SLI-CF                 | 1        | 2.08%   |
| Gigabyte B450M DS3H                  | 1        | 2.08%   |
| Dell XPS 8700                        | 1        | 2.08%   |
| Dell OptiPlex 755                    | 1        | 2.08%   |
| Dell OptiPlex 3050                   | 1        | 2.08%   |
| AZW GK55                             | 1        | 2.08%   |
| ASUS Z170 PRO GAMING/AURA            | 1        | 2.08%   |
| ASUS TUF Gaming B560M-PLUS           | 1        | 2.08%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 1        | 2.08%   |
| ASUS ROG STRIX Z590-E GAMING WIFI    | 1        | 2.08%   |
| ASUS ROG Maximus XIII HERO           | 1        | 2.08%   |
| ASUS PRIME H410M-A                   | 1        | 2.08%   |
| ASUS PRIME B550-PLUS                 | 1        | 2.08%   |
| ASUS PRIME B450-PLUS                 | 1        | 2.08%   |
| ASUS P7P55 LX                        | 1        | 2.08%   |
| ASUS P5GZ-MX                         | 1        | 2.08%   |
| ASUS P5G41T-M LX2/BR                 | 1        | 2.08%   |
| ASUS M5A78L LE                       | 1        | 2.08%   |
| ASUS M2A74-AM                        | 1        | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 3        | 6.25%   |
| ASUS ROG             | 3        | 6.25%   |
| ASUS PRIME           | 3        | 6.25%   |
| HP EliteDesk         | 2        | 4.17%   |
| Dell OptiPlex        | 2        | 4.17%   |
| Unknown              | 2        | 4.17%   |
| MSI p6-2330          | 1        | 2.08%   |
| MSI MS-7C56          | 1        | 2.08%   |
| MSI MS-7C09          | 1        | 2.08%   |
| MSI MS-7C02          | 1        | 2.08%   |
| MSI MS-7982          | 1        | 2.08%   |
| MSI MS-7817          | 1        | 2.08%   |
| MSI MS-7758          | 1        | 2.08%   |
| MSI MS-7599          | 1        | 2.08%   |
| MSI B02311           | 1        | 2.08%   |
| Medion MS-7797       | 1        | 2.08%   |
| Lenovo ThinkCentre   | 1        | 2.08%   |
| Lenovo T530-28ICB    | 1        | 2.08%   |
| HP ProDesk           | 1        | 2.08%   |
| HP Pavilion          | 1        | 2.08%   |
| HP 23-d027c          | 1        | 2.08%   |
| Gigabyte Z87-HD3     | 1        | 2.08%   |
| Gigabyte X99P-SLI-CF | 1        | 2.08%   |
| Gigabyte B450M       | 1        | 2.08%   |
| Dell XPS             | 1        | 2.08%   |
| AZW GK55             | 1        | 2.08%   |
| ASUS Z170            | 1        | 2.08%   |
| ASUS TUF             | 1        | 2.08%   |
| ASUS P7P55           | 1        | 2.08%   |
| ASUS P5GZ-MX         | 1        | 2.08%   |
| ASUS P5G41T-M        | 1        | 2.08%   |
| ASUS M5A78L          | 1        | 2.08%   |
| ASUS M2A74-AM        | 1        | 2.08%   |
| ASUS K30AD           | 1        | 2.08%   |
| ASRock Z77           | 1        | 2.08%   |
| ASRock HM55-HT       | 1        | 2.08%   |
| ASRock B450          | 1        | 2.08%   |
| ASRock 990FX         | 1        | 2.08%   |
| Acer Aspire          | 1        | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 6        | 12.5%   |
| 2013 | 6        | 12.5%   |
| 2021 | 5        | 10.42%  |
| 2020 | 5        | 10.42%  |
| 2012 | 5        | 10.42%  |
| 2009 | 4        | 8.33%   |
| 2014 | 3        | 6.25%   |
| 2010 | 3        | 6.25%   |
| 2019 | 2        | 4.17%   |
| 2016 | 2        | 4.17%   |
| 2015 | 2        | 4.17%   |
| 2011 | 2        | 4.17%   |
| 2017 | 1        | 2.08%   |
| 2007 | 1        | 2.08%   |
| 2006 | 1        | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 48       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 46       | 95.83%  |
| Enabled  | 2        | 4.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 10       | 20.83%  |
| 8.01-16.0   | 10       | 20.83%  |
| 3.01-4.0    | 8        | 16.67%  |
| 16.01-24.0  | 8        | 16.67%  |
| 4.01-8.0    | 7        | 14.58%  |
| 24.01-32.0  | 2        | 4.17%   |
| 64.01-256.0 | 2        | 4.17%   |
| 1.01-2.0    | 1        | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 15       | 31.25%  |
| 1.01-2.0  | 14       | 29.17%  |
| 4.01-8.0  | 9        | 18.75%  |
| 3.01-4.0  | 5        | 10.42%  |
| 8.01-16.0 | 3        | 6.25%   |
| 0.51-1.0  | 2        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 41.67%  |
| 3      | 8        | 16.67%  |
| 2      | 8        | 16.67%  |
| 4      | 5        | 10.42%  |
| 6      | 4        | 8.33%   |
| 5      | 2        | 4.17%   |
| 7      | 1        | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 58.33%  |
| No        | 20       | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 60.42%  |
| No        | 19       | 39.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 64.58%  |
| Yes       | 17       | 35.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 10       | 20.83%  |
| France      | 6        | 12.5%   |
| Italy       | 4        | 8.33%   |
| Germany     | 3        | 6.25%   |
| Croatia     | 3        | 6.25%   |
| Canada      | 3        | 6.25%   |
| Australia   | 3        | 6.25%   |
| Switzerland | 2        | 4.17%   |
| Portugal    | 2        | 4.17%   |
| Finland     | 2        | 4.17%   |
| Brazil      | 2        | 4.17%   |
| Ukraine     | 1        | 2.08%   |
| UK          | 1        | 2.08%   |
| Russia      | 1        | 2.08%   |
| Peru        | 1        | 2.08%   |
| Israel      | 1        | 2.08%   |
| Belgium     | 1        | 2.08%   |
| Austria     | 1        | 2.08%   |
| Argentina   | 1        | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Zagreb              | 2        | 4.08%   |
| Melbourne           | 2        | 4.08%   |
| Lansdale            | 2        | 4.08%   |
| York                | 1        | 2.04%   |
| Washington          | 1        | 2.04%   |
| Viana do Castelo    | 1        | 2.04%   |
| Velyki Mosty        | 1        | 2.04%   |
| Vancouver           | 1        | 2.04%   |
| Turku               | 1        | 2.04%   |
| Toulon              | 1        | 2.04%   |
| Terrace             | 1        | 2.04%   |
| Tel Aviv            | 1        | 2.04%   |
| Taranto             | 1        | 2.04%   |
| Talence             | 1        | 2.04%   |
| St Petersburg       | 1        | 2.04%   |
| Split               | 1        | 2.04%   |
| Seia                | 1        | 2.04%   |
| Saint-Etienne       | 1        | 2.04%   |
| Pindamonhangaba     | 1        | 2.04%   |
| Paris               | 1        | 2.04%   |
| Palermo             | 1        | 2.04%   |
| Overpelt            | 1        | 2.04%   |
| Noventa Vicentina   | 1        | 2.04%   |
| Mount Waverley      | 1        | 2.04%   |
| Miami               | 1        | 2.04%   |
| Marysville          | 1        | 2.04%   |
| Maitenbeth          | 1        | 2.04%   |
| Limoges             | 1        | 2.04%   |
| Lima                | 1        | 2.04%   |
| Lanigan             | 1        | 2.04%   |
| Kematen an der Ybbs | 1        | 2.04%   |
| Joigny              | 1        | 2.04%   |
| Imperatriz          | 1        | 2.04%   |
| Houston             | 1        | 2.04%   |
| Helsinki            | 1        | 2.04%   |
| Heerbrugg           | 1        | 2.04%   |
| Goslar              | 1        | 2.04%   |
| Gams                | 1        | 2.04%   |
| Florence            | 1        | 2.04%   |
| El Palomar          | 1        | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 32     | 21.35%  |
| Seagate             | 14       | 18     | 15.73%  |
| Samsung Electronics | 14       | 24     | 15.73%  |
| Crucial             | 7        | 7      | 7.87%   |
| SanDisk             | 5        | 8      | 5.62%   |
| Hitachi             | 4        | 4      | 4.49%   |
| Unknown             | 3        | 4      | 3.37%   |
| Toshiba             | 3        | 3      | 3.37%   |
| A-DATA Technology   | 3        | 3      | 3.37%   |
| SPCC                | 2        | 2      | 2.25%   |
| Phison              | 2        | 2      | 2.25%   |
| Kingston            | 2        | 2      | 2.25%   |
| RZX                 | 1        | 1      | 1.12%   |
| NGFF                | 1        | 1      | 1.12%   |
| Maxtor              | 1        | 1      | 1.12%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.12%   |
| KingSpec            | 1        | 1      | 1.12%   |
| Kimtigo             | 1        | 1      | 1.12%   |
| KESU                | 1        | 1      | 1.12%   |
| GOODRAM             | 1        | 1      | 1.12%   |
| DAS                 | 1        | 6      | 1.12%   |
| China               | 1        | 1      | 1.12%   |
| BAITITON            | 1        | 1      | 1.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM001-1ER164 2TB   | 3        | 2.65%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 2        | 1.77%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 1.77%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 1.77%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.77%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 1.77%   |
| Samsung SSD 870 QVO 2TB          | 2        | 1.77%   |
| Samsung SSD 870 QVO 1TB          | 2        | 1.77%   |
| Crucial CT2000MX500SSD1 2TB      | 2        | 1.77%   |
| Crucial CT1000BX500SSD1 1TB      | 2        | 1.77%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.88%   |
| WDC WDBNCE0010PNC 1TB SSD        | 1        | 0.88%   |
| WDC WD8001FZBX-00ASYA0 8TB       | 1        | 0.88%   |
| WDC WD6400AAKS-00E4A0 640GB      | 1        | 0.88%   |
| WDC WD60 EFAX-68JH4N1 6TB        | 1        | 0.88%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1        | 0.88%   |
| WDC WD5000AAKX-08ERMA0 500GB     | 1        | 0.88%   |
| WDC WD5000AAKX-003CA0 500GB      | 1        | 0.88%   |
| WDC WD5000AAKS-00A7B0 500GB      | 1        | 0.88%   |
| WDC WD40EZRZ-22GXCB0 4TB         | 1        | 0.88%   |
| WDC WD40EFZX-68AWUN0 4TB         | 1        | 0.88%   |
| WDC WD40 PURZ-85TTDY0 4TB        | 1        | 0.88%   |
| WDC WD30EFRX-68N32N0 3TB         | 1        | 0.88%   |
| WDC WD3000HLFS-01G6U0 304GB      | 1        | 0.88%   |
| WDC WD2500AAKX-753CA1 250GB      | 1        | 0.88%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.88%   |
| WDC WD20EADS-00R6B0 2TB          | 1        | 0.88%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 1        | 0.88%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1        | 0.88%   |
| WDC WD10EZEX-75WN4A0 1TB         | 1        | 0.88%   |
| WDC WD10EZEX-60ZF5A0 1TB         | 1        | 0.88%   |
| WDC WD10EZEX-60WN4A0 1TB         | 1        | 0.88%   |
| WDC WD10EZEX-60M2NA0 1TB         | 1        | 0.88%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 0.88%   |
| WDC WD10EZEX-00KUWA0 1TB         | 1        | 0.88%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 0.88%   |
| WDC WD10 01FALS-00J7B1 1TB       | 1        | 0.88%   |
| Unknown SD/MMC 2GB               | 1        | 0.88%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 1        | 0.88%   |
| Unknown CBADS  32GB              | 1        | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 30     | 42.22%  |
| Seagate             | 14       | 18     | 31.11%  |
| Hitachi             | 4        | 4      | 8.89%   |
| Toshiba             | 3        | 3      | 6.67%   |
| Samsung Electronics | 2        | 3      | 4.44%   |
| Maxtor              | 1        | 1      | 2.22%   |
| KESU                | 1        | 1      | 2.22%   |
| DAS                 | 1        | 6      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 26.47%  |
| Crucial             | 7        | 7      | 20.59%  |
| SanDisk             | 3        | 5      | 8.82%   |
| WDC                 | 2        | 2      | 5.88%   |
| SPCC                | 2        | 2      | 5.88%   |
| A-DATA Technology   | 2        | 2      | 5.88%   |
| Unknown             | 1        | 1      | 2.94%   |
| RZX                 | 1        | 1      | 2.94%   |
| NGFF                | 1        | 1      | 2.94%   |
| KIOXIA-EXCERIA      | 1        | 1      | 2.94%   |
| Kingston            | 1        | 1      | 2.94%   |
| KingSpec            | 1        | 1      | 2.94%   |
| GOODRAM             | 1        | 1      | 2.94%   |
| China               | 1        | 1      | 2.94%   |
| BAITITON            | 1        | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 33       | 66     | 45.21%  |
| SSD     | 26       | 39     | 35.62%  |
| NVMe    | 12       | 17     | 16.44%  |
| MMC     | 1        | 1      | 1.37%   |
| Unknown | 1        | 2      | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 43       | 94     | 70.49%  |
| NVMe | 12       | 17     | 19.67%  |
| SAS  | 5        | 13     | 8.2%    |
| MMC  | 1        | 1      | 1.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 51     | 42.31%  |
| 0.51-1.0   | 21       | 26     | 26.92%  |
| 1.01-2.0   | 12       | 13     | 15.38%  |
| 3.01-4.0   | 7        | 8      | 8.97%   |
| 4.01-10.0  | 3        | 3      | 3.85%   |
| 2.01-3.0   | 2        | 4      | 2.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 11       | 22.92%  |
| 101-250        | 10       | 20.83%  |
| More than 3000 | 9        | 18.75%  |
| 501-1000       | 9        | 18.75%  |
| 1001-2000      | 5        | 10.42%  |
| 51-100         | 2        | 4.17%   |
| 21-50          | 1        | 2.08%   |
| 2001-3000      | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 10       | 20.83%  |
| 51-100         | 7        | 14.58%  |
| More than 3000 | 6        | 12.5%   |
| 101-250        | 6        | 12.5%   |
| 501-1000       | 6        | 12.5%   |
| 21-50          | 5        | 10.42%  |
| 251-500        | 4        | 8.33%   |
| 1001-2000      | 3        | 6.25%   |
| 2001-3000      | 1        | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 14.29%  |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 960 PRO 1TB | 1        | 1      | 14.29%  |
| NGFF 2280 256GB SSD                 | 1        | 1      | 14.29%  |
| Hitachi HTS721080G9SA00 80GB        | 1        | 1      | 14.29%  |
| DAS TerraMaster 500GB               | 1        | 3      | 14.29%  |
| China SSD 180GB                     | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 2      | 28.57%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| NGFF                | 1        | 1      | 14.29%  |
| Hitachi             | 1        | 1      | 14.29%  |
| DAS                 | 1        | 3      | 14.29%  |
| China               | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 50%     |
| Hitachi | 1        | 1      | 25%     |
| DAS     | 1        | 3      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 6      | 50%     |
| SSD  | 2        | 2      | 33.33%  |
| NVMe | 1        | 1      | 16.67%  |

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
| Works    | 27       | 59     | 49.09%  |
| Detected | 22       | 57     | 40%     |
| Malfunc  | 6        | 9      | 10.91%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 33       | 52.38%  |
| AMD                         | 14       | 22.22%  |
| Samsung Electronics         | 6        | 9.52%   |
| ASMedia Technology          | 3        | 4.76%   |
| SanDisk                     | 2        | 3.17%   |
| Phison Electronics          | 2        | 3.17%   |
| Silicon Motion              | 1        | 1.59%   |
| Kingston Technology Company | 1        | 1.59%   |
| ADATA Technology            | 1        | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 7.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 6.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5        | 6.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 4.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 4.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 3.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 3.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 3.66%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 3.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3        | 3.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 2.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.44%   |
| Phison NVMe Storage Controller                                                 | 2        | 2.44%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 2.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 2.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 2.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 2.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 2.44%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 2.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.22%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 1.22%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 1.22%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.22%   |
| Kingston Company Company Non-Volatile memory controller                        | 1        | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.22%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 1.22%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 1.22%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 1.22%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 1        | 1.22%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]  | 1        | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 1.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 1.22%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1        | 1.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 58.82%  |
| NVMe | 12       | 17.65%  |
| IDE  | 12       | 17.65%  |
| RAID | 4        | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 34       | 70.83%  |
| AMD    | 14       | 29.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 4.17%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2        | 4.17%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 4.17%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 2.08%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 2.08%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 2.08%   |
| Intel Pentium 4 CPU 3.06GHz                 | 1        | 2.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1        | 2.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 2.08%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 2.08%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 2.08%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 2.08%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 2.08%   |
| Intel Core i5-7400T CPU @ 2.40GHz           | 1        | 2.08%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 2.08%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 2.08%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 2.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 2.08%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 2.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2.08%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 1        | 2.08%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 2.08%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 2.08%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 2.08%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 2.08%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1        | 2.08%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 2.08%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 2.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 2.08%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz        | 1        | 2.08%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 2.08%   |
| Intel 12th Gen Core i7-12700F               | 1        | 2.08%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz     | 1        | 2.08%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1        | 2.08%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 1        | 2.08%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 2.08%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 1        | 2.08%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 2.08%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 2.08%   |
| AMD Phenom II X6 1090T Processor            | 1        | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 12       | 25%     |
| Intel Core i7     | 6        | 12.5%   |
| AMD Ryzen 5       | 5        | 10.42%  |
| Other             | 4        | 8.33%   |
| Intel Core i3     | 4        | 8.33%   |
| Intel Pentium     | 2        | 4.17%   |
| Intel Core 2 Duo  | 2        | 4.17%   |
| Intel Xeon        | 1        | 2.08%   |
| Intel Pentium 4   | 1        | 2.08%   |
| Intel Core 2 Quad | 1        | 2.08%   |
| Intel Celeron     | 1        | 2.08%   |
| AMD Ryzen 9       | 1        | 2.08%   |
| AMD Ryzen 7       | 1        | 2.08%   |
| AMD Ryzen 3       | 1        | 2.08%   |
| AMD Phenom II X6  | 1        | 2.08%   |
| AMD FX            | 1        | 2.08%   |
| AMD E             | 1        | 2.08%   |
| AMD Athlon II X4  | 1        | 2.08%   |
| AMD Athlon II X2  | 1        | 2.08%   |
| AMD A6            | 1        | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 43.75%  |
| 2      | 11       | 22.92%  |
| 6      | 9        | 18.75%  |
| 8      | 3        | 6.25%   |
| 1      | 2        | 4.17%   |
| 12     | 1        | 2.08%   |
| 10     | 1        | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 50%     |
| 1      | 24       | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 43.75%  |
| 0x306c3    | 3        | 6.25%   |
| 0x306a9    | 3        | 6.25%   |
| 0xa0671    | 2        | 4.17%   |
| 0x906ea    | 2        | 4.17%   |
| 0x506e3    | 2        | 4.17%   |
| 0x20655    | 2        | 4.17%   |
| 0xa0653    | 1        | 2.08%   |
| 0x906ed    | 1        | 2.08%   |
| 0x90672    | 1        | 2.08%   |
| 0x6fd      | 1        | 2.08%   |
| 0x306f2    | 1        | 2.08%   |
| 0x206a7    | 1        | 2.08%   |
| 0x10677    | 1        | 2.08%   |
| 0x0a50000c | 1        | 2.08%   |
| 0x08108109 | 1        | 2.08%   |
| 0x06001119 | 1        | 2.08%   |
| 0x05000119 | 1        | 2.08%   |
| 0x010000dc | 1        | 2.08%   |
| 0x010000c8 | 1        | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 7        | 14.58%  |
| IvyBridge        | 5        | 10.42%  |
| Skylake          | 4        | 8.33%   |
| KabyLake         | 4        | 8.33%   |
| Westmere         | 3        | 6.25%   |
| K10              | 3        | 6.25%   |
| Zen+             | 2        | 4.17%   |
| Zen 3            | 2        | 4.17%   |
| Zen 2            | 2        | 4.17%   |
| Zen              | 2        | 4.17%   |
| Penryn           | 2        | 4.17%   |
| Icelake          | 2        | 4.17%   |
| SandyBridge      | 1        | 2.08%   |
| Piledriver       | 1        | 2.08%   |
| NetBurst         | 1        | 2.08%   |
| Goldmont plus    | 1        | 2.08%   |
| Core             | 1        | 2.08%   |
| CometLake        | 1        | 2.08%   |
| Bulldozer        | 1        | 2.08%   |
| Bobcat           | 1        | 2.08%   |
| Alderlake Hybrid | 1        | 2.08%   |
| Unknown          | 1        | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 38.46%  |
| AMD    | 18       | 34.62%  |
| Nvidia | 14       | 26.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 7.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 5.77%   |
| Intel HD Graphics 530                                                       | 3        | 5.77%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 3.85%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 3.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 3.85%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.92%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.92%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.92%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1        | 1.92%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.92%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.92%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.92%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.92%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 1.92%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.92%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.92%   |
| Intel HD Graphics 630                                                       | 1        | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1        | 1.92%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.92%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.92%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 1.92%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 1        | 1.92%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.92%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 1.92%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.92%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 1.92%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.92%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 1.92%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 1.92%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 1        | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Intel    | 17       | 35.42%  |
| 1 x AMD      | 16       | 33.33%  |
| 1 x Nvidia   | 13       | 27.08%  |
| Intel + AMD  | 1        | 2.08%   |
| AMD + Nvidia | 1        | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 37       | 77.08%  |
| Proprietary | 9        | 18.75%  |
| Unknown     | 2        | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 60.42%  |
| 0.51-1.0   | 5        | 10.42%  |
| 3.01-4.0   | 4        | 8.33%   |
| 0.01-0.5   | 3        | 6.25%   |
| 5.01-6.0   | 2        | 4.17%   |
| 1.01-2.0   | 2        | 4.17%   |
| 7.01-8.0   | 1        | 2.08%   |
| 2.01-3.0   | 1        | 2.08%   |
| 8.01-16.0  | 1        | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 19.61%  |
| Goldstar             | 9        | 17.65%  |
| Dell                 | 5        | 9.8%    |
| Acer                 | 5        | 9.8%    |
| Philips              | 4        | 7.84%   |
| Hewlett-Packard      | 3        | 5.88%   |
| Lenovo               | 2        | 3.92%   |
| Iiyama               | 2        | 3.92%   |
| BenQ                 | 2        | 3.92%   |
| Ancor Communications | 2        | 3.92%   |
| Westinghouse         | 1        | 1.96%   |
| VMO                  | 1        | 1.96%   |
| Vizio                | 1        | 1.96%   |
| Insignia             | 1        | 1.96%   |
| Gateway              | 1        | 1.96%   |
| ASUSTek Computer     | 1        | 1.96%   |
| AOC                  | 1        | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                   | 2        | 3.92%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch         | 1        | 1.96%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch            | 1        | 1.96%   |
| Vizio XVT553SV VIZ0063 1920x1080 1210x680mm 54.6-inch                | 1        | 1.96%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1        | 1.96%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 1        | 1.96%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch  | 1        | 1.96%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1        | 1.96%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch    | 1        | 1.96%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1        | 1.96%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch    | 1        | 1.96%   |
| Samsung Electronics LCD Monitor SAM0D4B 1360x768 609x347mm 27.6-inch | 1        | 1.96%   |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch | 1        | 1.96%   |
| Samsung Electronics EPSON PJ SECA605 1600x1200                       | 1        | 1.96%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 1        | 1.96%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch             | 1        | 1.96%   |
| Philips PHL 242E2F PHLC238 1920x1080 527x296mm 23.8-inch             | 1        | 1.96%   |
| Philips 246EL2SBH PHLC074 1920x1080 521x293mm 23.5-inch              | 1        | 1.96%   |
| Lenovo LEN G25-10 LEN65FE 1920x1080 544x303mm 24.5-inch              | 1        | 1.96%   |
| Lenovo C27-35 LEN66BA 1920x1080 597x336mm 27.0-inch                  | 1        | 1.96%   |
| Insignia NS-19E310A13 BBY0101 1360x768 410x230mm 18.5-inch           | 1        | 1.96%   |
| Iiyama PLX436S IVM46D7 1280x1024 340x270mm 17.1-inch                 | 1        | 1.96%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                 | 1        | 1.96%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 465x291mm 21.6-inch          | 1        | 1.96%   |
| Hewlett-Packard LCD Monitor HWP1001 1920x1080 477x268mm 21.5-inch    | 1        | 1.96%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch            | 1        | 1.96%   |
| Goldstar W2353 GSM56F0 1920x1080 510x290mm 23.1-inch                 | 1        | 1.96%   |
| Goldstar W1642C GSM3E89 1366x768 344x194mm 15.5-inch                 | 1        | 1.96%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch             | 1        | 1.96%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch             | 1        | 1.96%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 1.96%   |
| Goldstar L1717S GSM43FF 1280x1024 338x270mm 17.0-inch                | 1        | 1.96%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1        | 1.96%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 1        | 1.96%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                | 1        | 1.96%   |
| Gateway GTW KX2703 GTW0394 1920x1080 598x336mm 27.0-inch             | 1        | 1.96%   |
| Dell U3421WE DELA192 3440x1440 800x335mm 34.1-inch                   | 1        | 1.96%   |
| Dell SE2417HGX DELD0F6 1920x1080 521x293mm 23.5-inch                 | 1        | 1.96%   |
| Dell S3222DGM DELD111 2560x1440 697x392mm 31.5-inch                  | 1        | 1.96%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 1        | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 23       | 50%     |
| 3840x2160 (4K)     | 3        | 6.52%   |
| 2560x1440 (QHD)    | 3        | 6.52%   |
| 1680x1050 (WSXGA+) | 3        | 6.52%   |
| 3440x1440          | 2        | 4.35%   |
| 1440x900 (WXGA+)   | 2        | 4.35%   |
| 1366x768 (WXGA)    | 2        | 4.35%   |
| 1360x768           | 2        | 4.35%   |
| 1280x1024 (SXGA)   | 2        | 4.35%   |
| 2560x1600          | 1        | 2.17%   |
| 2560x1080          | 1        | 2.17%   |
| 1920x1200 (WUXGA)  | 1        | 2.17%   |
| 1280x720 (HD)      | 1        | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 8        | 16.33%  |
| 23      | 8        | 16.33%  |
| 24      | 6        | 12.24%  |
| 21      | 6        | 12.24%  |
| 31      | 5        | 10.2%   |
| 34      | 3        | 6.12%   |
| 19      | 3        | 6.12%   |
| 17      | 3        | 6.12%   |
| 74      | 1        | 2.04%   |
| 54      | 1        | 2.04%   |
| 40      | 1        | 2.04%   |
| 22      | 1        | 2.04%   |
| 18      | 1        | 2.04%   |
| 15      | 1        | 2.04%   |
| Unknown | 1        | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 41.67%  |
| 401-500     | 11       | 22.92%  |
| 601-700     | 6        | 12.5%   |
| 301-350     | 4        | 8.33%   |
| 701-800     | 3        | 6.25%   |
| 801-900     | 1        | 2.08%   |
| 1501-2000   | 1        | 2.08%   |
| 1001-1500   | 1        | 2.08%   |
| Unknown     | 1        | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 29       | 67.44%  |
| 16/10 | 8        | 18.6%   |
| 5/4   | 3        | 6.98%   |
| 21/9  | 3        | 6.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 37.5%   |
| 351-500        | 8        | 16.67%  |
| 301-350        | 8        | 16.67%  |
| 141-150        | 4        | 8.33%   |
| 151-200        | 3        | 6.25%   |
| More than 1000 | 2        | 4.17%   |
| 251-300        | 2        | 4.17%   |
| 101-110        | 1        | 2.08%   |
| 501-1000       | 1        | 2.08%   |
| Unknown        | 1        | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 68.18%  |
| 101-120 | 8        | 18.18%  |
| 1-50    | 3        | 6.82%   |
| 121-160 | 2        | 4.55%   |
| Unknown | 1        | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 77.55%  |
| 2     | 9        | 18.37%  |
| 0     | 2        | 4.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 32       | 47.06%  |
| Intel                    | 20       | 29.41%  |
| Broadcom                 | 4        | 5.88%   |
| Ralink                   | 3        | 4.41%   |
| Qualcomm Atheros         | 3        | 4.41%   |
| TP-Link                  | 2        | 2.94%   |
| NetGear                  | 1        | 1.47%   |
| MediaTek                 | 1        | 1.47%   |
| Marvell Technology Group | 1        | 1.47%   |
| ASUSTek Computer         | 1        | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 32.91%  |
| Intel Ethernet Controller I225-V                                  | 4        | 5.06%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 2.53%   |
| Intel Wireless 7265                                               | 2        | 2.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 2.53%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.53%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.53%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 2.53%   |
| TP-Link Archer T4U ver.3                                          | 1        | 1.27%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 1.27%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.27%   |
| Realtek 802.11n                                                   | 1        | 1.27%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1        | 1.27%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 1.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 1.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.27%   |
| NetGear A6150                                                     | 1        | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.27%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.27%   |
| Intel Wireless 3165                                               | 1        | 1.27%   |
| Intel Wireless 3160                                               | 1        | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.27%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.27%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1        | 1.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 31.03%  |
| Intel                 | 9        | 31.03%  |
| Ralink                | 3        | 10.34%  |
| TP-Link               | 2        | 6.9%    |
| Broadcom              | 2        | 6.9%    |
| Qualcomm Atheros      | 1        | 3.45%   |
| NetGear               | 1        | 3.45%   |
| MediaTek              | 1        | 3.45%   |
| ASUSTek Computer      | 1        | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2        | 6.9%    |
| Intel Wireless 7265                                            | 2        | 6.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2        | 6.9%    |
| TP-Link Archer T4U ver.3                                       | 1        | 3.45%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 3.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 3.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 3.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 3.45%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 3.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 3.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1        | 3.45%   |
| Realtek 802.11n                                                | 1        | 3.45%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 3.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 3.45%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 3.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 3.45%   |
| NetGear A6150                                                  | 1        | 3.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 3.45%   |
| Intel Wireless 3165                                            | 1        | 3.45%   |
| Intel Wireless 3160                                            | 1        | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1        | 3.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 3.45%   |
| Broadcom Network controller                                    | 1        | 3.45%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1        | 3.45%   |
| ASUS 802.11ac NIC                                              | 1        | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 28       | 57.14%  |
| Intel                    | 16       | 32.65%  |
| Qualcomm Atheros         | 2        | 4.08%   |
| Broadcom                 | 2        | 4.08%   |
| Marvell Technology Group | 1        | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 52%     |
| Intel Ethernet Controller I225-V                                  | 4        | 8%      |
| Intel Ethernet Connection I217-LM                                 | 2        | 4%      |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4%      |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 2%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 2%      |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2%      |
| Intel I211 Gigabit Network Connection                             | 1        | 2%      |
| Intel Ethernet Connection I217-V                                  | 1        | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2%      |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 62.34%  |
| WiFi     | 29       | 37.66%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 36       | 73.47%  |
| WiFi     | 13       | 26.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 50%     |
| 2     | 21       | 43.75%  |
| 3     | 3        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 77.55%  |
| Yes  | 11       | 22.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 35.29%  |
| Realtek Semiconductor   | 3        | 17.65%  |
| Cambridge Silicon Radio | 2        | 11.76%  |
| Broadcom                | 2        | 11.76%  |
| Ralink                  | 1        | 5.88%   |
| MediaTek                | 1        | 5.88%   |
| IMC Networks            | 1        | 5.88%   |
| Belkin Components       | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 17.65%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 11.76%  |
| Realtek RTL8723B Bluetooth                          | 1        | 5.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 5.88%   |
| Realtek Bluetooth Radio                             | 1        | 5.88%   |
| Ralink RT3290 Bluetooth                             | 1        | 5.88%   |
| MediaTek Wireless_Device                            | 1        | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.88%   |
| Intel AX210 Bluetooth                               | 1        | 5.88%   |
| Intel AX201 Bluetooth                               | 1        | 5.88%   |
| IMC Networks Bluetooth Radio                        | 1        | 5.88%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 5.88%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 5.88%   |
| Belkin Components F8T013 Bluetooth Adapter          | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 33       | 41.77%  |
| AMD                     | 20       | 25.32%  |
| Nvidia                  | 14       | 17.72%  |
| C-Media Electronics     | 3        | 3.8%    |
| ASUSTek Computer        | 3        | 3.8%    |
| Kingston Technology     | 1        | 1.27%   |
| Generalplus Technology  | 1        | 1.27%   |
| Creative Technology     | 1        | 1.27%   |
| Corsair                 | 1        | 1.27%   |
| Cambridge Silicon Radio | 1        | 1.27%   |
| Anlya.cn                | 1        | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 6.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 5.43%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 5.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 5.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 3.26%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 3.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 3.26%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3.26%   |
| ASUSTek Computer USB Audio                                                 | 3        | 3.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 3.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 2.17%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.09%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.09%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1        | 1.09%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.09%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.09%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.09%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.09%   |
| Creative Technology Sound Blaster Play!                                    | 1        | 1.09%   |
| Corsair VOID ELITE Wireless Gaming Dongle                                  | 1        | 1.09%   |
| Cambridge Silicon Radio B25                                                | 1        | 1.09%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 8        | 22.86%  |
| Crucial             | 6        | 17.14%  |
| Unknown             | 5        | 14.29%  |
| SK hynix            | 5        | 14.29%  |
| Samsung Electronics | 4        | 11.43%  |
| Kingston            | 3        | 8.57%   |
| Unifosa             | 1        | 2.86%   |
| Micron Technology   | 1        | 2.86%   |
| HBS                 | 1        | 2.86%   |
| G.Skill             | 1        | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                  | 1        | 2.7%    |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                  | 1        | 2.7%    |
| Unknown RAM Module 4GB DIMM                               | 1        | 2.7%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 2.7%    |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s   | 1        | 2.7%    |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s | 1        | 2.7%    |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s         | 1        | 2.7%    |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s       | 1        | 2.7%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s      | 1        | 2.7%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 2.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 2.7%    |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 2.7%    |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s     | 1        | 2.7%    |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s    | 1        | 2.7%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.7%    |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 1        | 2.7%    |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s       | 1        | 2.7%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 2.7%    |
| Kingston RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 2.7%    |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s      | 1        | 2.7%    |
| Kingston RAM KF2666C16D4/16G 16GB DIMM DDR4 2666MT/s      | 1        | 2.7%    |
| HBS RAM SO8G1600CL11L 8GB SODIMM DDR3 1600MT/s            | 1        | 2.7%    |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s     | 1        | 2.7%    |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s   | 1        | 2.7%    |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s     | 1        | 2.7%    |
| Crucial RAM CT16G4DFRA266.M8FB 16GB DIMM DDR4 2667MT/s    | 1        | 2.7%    |
| Crucial RAM BLT8G3D1608DT1TX0. 8GB DIMM DDR3 1600MT/s     | 1        | 2.7%    |
| Crucial RAM BLS16G4D240FSC.16FA 16GB DIMM DDR4 2400MT/s   | 1        | 2.7%    |
| Crucial RAM BLM16G40C18U4B.M8FB1 16GB DIMM DDR4 4000MT/s  | 1        | 2.7%    |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s       | 1        | 2.7%    |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 1        | 2.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 2.7%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 1        | 2.7%    |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s     | 1        | 2.7%    |
| Corsair RAM CMK16GX4M1A2666C16 16GB DIMM DDR4 2800MT/s    | 1        | 2.7%    |
| Corsair RAM CMH32GX4M2E3200C16 16GB DIMM DDR4 2133MT/s    | 1        | 2.7%    |
| Corsair RAM CM4X8GF2400Z16K4 8GB DIMM DDR4 2400MT/s       | 1        | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 16       | 51.61%  |
| DDR3    | 11       | 35.48%  |
| DDR2    | 2        | 6.45%   |
| DDR     | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 27       | 87.1%   |
| SODIMM | 4        | 12.9%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 11       | 31.43%  |
| 8192  | 10       | 28.57%  |
| 4096  | 10       | 28.57%  |
| 2048  | 3        | 8.57%   |
| 1024  | 1        | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 7        | 21.88%  |
| 1333    | 4        | 12.5%   |
| 2667    | 3        | 9.38%   |
| 3200    | 2        | 6.25%   |
| 2400    | 2        | 6.25%   |
| 2133    | 2        | 6.25%   |
| 800     | 2        | 6.25%   |
| 4000    | 1        | 3.13%   |
| 3600    | 1        | 3.13%   |
| 3466    | 1        | 3.13%   |
| 3400    | 1        | 3.13%   |
| 3333    | 1        | 3.13%   |
| 3100    | 1        | 3.13%   |
| 2800    | 1        | 3.13%   |
| 2666    | 1        | 3.13%   |
| 1648    | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 1        | 33.33%  |
| Graphtec America   | 1        | 33.33%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series        | 1        | 33.33%  |
| Graphtec America Graphtec Printer | 1        | 33.33%  |
| Brother HL-3140CW series          | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 5        | 41.67%  |
| Z-Star Microelectronics | 1        | 8.33%   |
| Realtek Semiconductor   | 1        | 8.33%   |
| Microsoft               | 1        | 8.33%   |
| Microdia                | 1        | 8.33%   |
| Generalplus Technology  | 1        | 8.33%   |
| ARC International       | 1        | 8.33%   |
| Apple                   | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 2        | 16.67%  |
| Z-Star HP 3-MegaPixel Webcam GX607AA    | 1        | 8.33%   |
| Realtek HP 1.0MP High Definition Webcam | 1        | 8.33%   |
| Microsoft LifeCam VX-500 [1357]         | 1        | 8.33%   |
| Microdia Webcam Vitade AF               | 1        | 8.33%   |
| Logitech Webcam C925e                   | 1        | 8.33%   |
| Logitech QuickCam E 3500                | 1        | 8.33%   |
| Logitech HD Pro Webcam C920             | 1        | 8.33%   |
| Generalplus GENERAL WEBCAM              | 1        | 8.33%   |
| ARC International Camera                | 1        | 8.33%   |
| Apple iPhone 5/5C/5S/6/SE               | 1        | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 42       | 85.71%  |
| 1     | 6        | 12.24%  |
| 3     | 1        | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 37.5%   |
| Graphics card    | 2        | 25%     |
| Unassigned class | 1        | 12.5%   |
| Card reader      | 1        | 12.5%   |
| Bluetooth        | 1        | 12.5%   |

