Lubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

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

Total: 43

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | 0B4Ch D                     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP       | 0B4Ch D                     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Dell     | 0R849J A00                  | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Dell     | 09M8Y8 A01                  | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| MSI      | B450-A PRO MAX              | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte | G31M-S2C                    | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| AMI      | Cherry Trail CR             | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Dell     | 0J584C A00                  | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Gigabyte | G31M-S2C                    | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte | G31M-S2C                    | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| MSI      | Z590-A PRO                  | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| MSI      | Z170A GAMING M3             | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| ASRock   | G41M-VS3                    | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| HP       | 8768 A                      | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| Lenovo   | BRASWELL SDK0J40697 WIN ... | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock   | G41M-VS3                    | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer     | EG31M R01-A3                | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell     | 0WR7PY A03                  | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell     | 0X8582                      | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI      | Cherry Trail CR             | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek  | M5A78L LE                   | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell     | 0X8582                      | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock   | A75M-HVS                    | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell     | 0X8582                      | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| MSI      | X570-A PRO                  | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| HP       | 1495                        | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP       | 1495                        | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| MSI      | 760GM-P23                   | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell     | 0VRWRC A00                  | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek  | M4N78-AM                    | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Lenovo   | SHARKBAY SDK0E50510 PRO     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| ASUSTek  | M4N78-AM                    | [8522c93ea3](https://linux-hardware.org/?probe=8522c93ea3) | Jun 16, 2022 |
| ASUSTek  | M4N78-AM                    | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek  | PRIME X370-A                | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Unknown  | Unknown                     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Unknown  | Unknown                     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown  | HX90                        | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Unknown  | Unknown                     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron | VIOLET6                     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Dell     | 02YYK5 A01                  | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| ZOTAC    | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Unknown  | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek  | PRIME B350M-E               | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.15.0-41-generic           | 5        | 14.29%  |
| 5.15.0-47-generic           | 4        | 11.43%  |
| 5.15.0-25-generic           | 4        | 11.43%  |
| 5.15.0-43-generic           | 3        | 8.57%   |
| 5.15.0-40-generic           | 3        | 8.57%   |
| 5.15.0-39-generic           | 3        | 8.57%   |
| 5.15.0-48-generic           | 2        | 5.71%   |
| 5.15.0-46-generic           | 2        | 5.71%   |
| 5.15.0-30-generic           | 2        | 5.71%   |
| 5.15.0-27-generic           | 2        | 5.71%   |
| 5.15.0-41-lowlatency        | 1        | 2.86%   |
| 5.15.0-362206031516-generic | 1        | 2.86%   |
| 5.15.0-35-generic           | 1        | 2.86%   |
| 5.15.0-23-generic           | 1        | 2.86%   |
| 5.15.0-18-generic           | 1        | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 34       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 34       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 34       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LXQt | 33       | 97.06%  |
| LXDE | 1        | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 32       | 91.43%  |
| Wayland     | 1        | 2.86%   |
| Unspecified | 1        | 2.86%   |
| Tty         | 1        | 2.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 28       | 82.35%  |
| LightDM | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| XDM     | 1        | 2.94%   |
| LXDM    | 1        | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 32.35%  |
| fr_FR | 4        | 11.76%  |
| de_DE | 3        | 8.82%   |
| it_IT | 2        | 5.88%   |
| es_CR | 2        | 5.88%   |
| C     | 2        | 5.88%   |
| sv_SE | 1        | 2.94%   |
| ru_UA | 1        | 2.94%   |
| nl_BE | 1        | 2.94%   |
| es_MX | 1        | 2.94%   |
| es_AR | 1        | 2.94%   |
| en_GB | 1        | 2.94%   |
| en_AU | 1        | 2.94%   |
| en_AG | 1        | 2.94%   |
| el_GR | 1        | 2.94%   |
| cv_RU | 1        | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 28       | 82.35%  |
| EFI  | 6        | 17.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 31       | 91.18%  |
| Overlay | 2        | 5.88%   |
| Btrfs   | 1        | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 52.94%  |
| GPT     | 11       | 32.35%  |
| MBR     | 5        | 14.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 85.29%  |
| Yes       | 5        | 14.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 61.76%  |
| Yes       | 13       | 38.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 23.53%  |
| MSI                 | 5        | 14.71%  |
| ASUSTek Computer    | 4        | 11.76%  |
| Hewlett-Packard     | 3        | 8.82%   |
| Unknown             | 3        | 8.82%   |
| Lenovo              | 2        | 5.88%   |
| Gigabyte Technology | 2        | 5.88%   |
| ASRock              | 2        | 5.88%   |
| AMI                 | 2        | 5.88%   |
| ZOTAC               | 1        | 2.94%   |
| Pegatron            | 1        | 2.94%   |
| Acer                | 1        | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 3        | 8.82%   |
| Dell Dimension 9100                    | 2        | 5.88%   |
| ZOTAC NM10                             | 1        | 2.94%   |
| Pegatron AY748AA-ABA p6320y            | 1        | 2.94%   |
| MSI MS-7D09                            | 1        | 2.94%   |
| MSI MS-7C37                            | 1        | 2.94%   |
| MSI MS-7B86                            | 1        | 2.94%   |
| MSI MS-7978                            | 1        | 2.94%   |
| MSI MS-7641                            | 1        | 2.94%   |
| Lenovo ThinkCentre M83 10ANCTO1WW      | 1        | 2.94%   |
| Lenovo ThinkCentre M600 10KGS09S00     | 1        | 2.94%   |
| HP Z400 Workstation                    | 1        | 2.94%   |
| HP Slim Desktop S01-pF1xxx             | 1        | 2.94%   |
| HP Compaq 8200 ELITE SMALL FORM FACTOR | 1        | 2.94%   |
| Gigabyte G31M-S2C                      | 1        | 2.94%   |
| Gigabyte G31M-ES2C                     | 1        | 2.94%   |
| Dell Vostro 410                        | 1        | 2.94%   |
| Dell Studio XPS 435MT                  | 1        | 2.94%   |
| Dell Precision T3610                   | 1        | 2.94%   |
| Dell OptiPlex 7020                     | 1        | 2.94%   |
| Dell OptiPlex 7010                     | 1        | 2.94%   |
| Dell OptiPlex 3020M                    | 1        | 2.94%   |
| ASUS PRIME X370-A                      | 1        | 2.94%   |
| ASUS PRIME B350M-E                     | 1        | 2.94%   |
| ASUS M5A78L LE                         | 1        | 2.94%   |
| ASUS M4N78-AM                          | 1        | 2.94%   |
| ASRock G41M-VS3                        | 1        | 2.94%   |
| ASRock A75M-HVS                        | 1        | 2.94%   |
| AMI Z83-V                              | 1        | 2.94%   |
| AMI Narrow Box 4K                      | 1        | 2.94%   |
| Acer Aspire M5630                      | 1        | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 3        | 8.82%   |
| Unknown              | 3        | 8.82%   |
| Lenovo ThinkCentre   | 2        | 5.88%   |
| Dell Dimension       | 2        | 5.88%   |
| ASUS PRIME           | 2        | 5.88%   |
| ZOTAC NM10           | 1        | 2.94%   |
| Pegatron AY748AA-ABA | 1        | 2.94%   |
| MSI MS-7D09          | 1        | 2.94%   |
| MSI MS-7C37          | 1        | 2.94%   |
| MSI MS-7B86          | 1        | 2.94%   |
| MSI MS-7978          | 1        | 2.94%   |
| MSI MS-7641          | 1        | 2.94%   |
| HP Z400              | 1        | 2.94%   |
| HP Slim              | 1        | 2.94%   |
| HP Compaq            | 1        | 2.94%   |
| Gigabyte G31M-S2C    | 1        | 2.94%   |
| Gigabyte G31M-ES2C   | 1        | 2.94%   |
| Dell Vostro          | 1        | 2.94%   |
| Dell Studio          | 1        | 2.94%   |
| Dell Precision       | 1        | 2.94%   |
| ASUS M5A78L          | 1        | 2.94%   |
| ASUS M4N78-AM        | 1        | 2.94%   |
| ASRock G41M-VS3      | 1        | 2.94%   |
| ASRock A75M-HVS      | 1        | 2.94%   |
| AMI Z83-V            | 1        | 2.94%   |
| AMI Narrow           | 1        | 2.94%   |
| Acer Aspire          | 1        | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2017 | 5        | 14.71%  |
| 2008 | 4        | 11.76%  |
| 2021 | 3        | 8.82%   |
| 2011 | 3        | 8.82%   |
| 2010 | 3        | 8.82%   |
| 2019 | 2        | 5.88%   |
| 2016 | 2        | 5.88%   |
| 2015 | 2        | 5.88%   |
| 2013 | 2        | 5.88%   |
| 2009 | 2        | 5.88%   |
| 2006 | 2        | 5.88%   |
| 2022 | 1        | 2.94%   |
| 2020 | 1        | 2.94%   |
| 2014 | 1        | 2.94%   |
| 2007 | 1        | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 34       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 33       | 97.06%  |
| Enabled  | 1        | 2.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 8        | 23.53%  |
| 16.01-24.0  | 7        | 20.59%  |
| 3.01-4.0    | 5        | 14.71%  |
| 32.01-64.0  | 4        | 11.76%  |
| 8.01-16.0   | 4        | 11.76%  |
| 1.01-2.0    | 2        | 5.88%   |
| 0.51-1.0    | 2        | 5.88%   |
| 2.01-3.0    | 1        | 2.94%   |
| 64.01-256.0 | 1        | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 13       | 37.14%  |
| 0.51-1.0 | 9        | 25.71%  |
| 2.01-3.0 | 7        | 20%     |
| 4.01-8.0 | 4        | 11.43%  |
| 3.01-4.0 | 2        | 5.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 52.94%  |
| 2      | 11       | 32.35%  |
| 7      | 1        | 2.94%   |
| 6      | 1        | 2.94%   |
| 5      | 1        | 2.94%   |
| 3      | 1        | 2.94%   |
| 0      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 58.82%  |
| Yes       | 14       | 41.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 97.06%  |
| No        | 1        | 2.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 58.82%  |
| Yes       | 14       | 41.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 79.41%  |
| Yes       | 7        | 20.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 10       | 29.41%  |
| France     | 4        | 11.76%  |
| Germany    | 3        | 8.82%   |
| Italy      | 2        | 5.88%   |
| Costa Rica | 2        | 5.88%   |
| Ukraine    | 1        | 2.94%   |
| UK         | 1        | 2.94%   |
| Sweden     | 1        | 2.94%   |
| Romania    | 1        | 2.94%   |
| Poland     | 1        | 2.94%   |
| Mexico     | 1        | 2.94%   |
| Latvia     | 1        | 2.94%   |
| Greece     | 1        | 2.94%   |
| Bulgaria   | 1        | 2.94%   |
| Brazil     | 1        | 2.94%   |
| Belgium    | 1        | 2.94%   |
| Australia  | 1        | 2.94%   |
| Argentina  | 1        | 2.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Largo                | 2        | 5.88%   |
| Heredia              | 2        | 5.88%   |
| Wetteren             | 1        | 2.94%   |
| Washington           | 1        | 2.94%   |
| Varna                | 1        | 2.94%   |
| Valentigney          | 1        | 2.94%   |
| Sonico               | 1        | 2.94%   |
| Richmond             | 1        | 2.94%   |
| Resistencia          | 1        | 2.94%   |
| Paris                | 1        | 2.94%   |
| Ostrów Wielkopolski | 1        | 2.94%   |
| Novo Gama            | 1        | 2.94%   |
| Notting Hill Gate    | 1        | 2.94%   |
| Nederland            | 1        | 2.94%   |
| Mobile               | 1        | 2.94%   |
| Mexico City          | 1        | 2.94%   |
| Melbourne            | 1        | 2.94%   |
| Marseille            | 1        | 2.94%   |
| Lebanon              | 1        | 2.94%   |
| Larissa              | 1        | 2.94%   |
| Kyiv                 | 1        | 2.94%   |
| Koblenz              | 1        | 2.94%   |
| Karlstad             | 1        | 2.94%   |
| Frankfurt am Main    | 1        | 2.94%   |
| Denver               | 1        | 2.94%   |
| Dallas               | 1        | 2.94%   |
| Cirey-sur-Vezouze    | 1        | 2.94%   |
| Chicago              | 1        | 2.94%   |
| Bucharest            | 1        | 2.94%   |
| Brandenburg          | 1        | 2.94%   |
| Arluno               | 1        | 2.94%   |
| Adazi                | 1        | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 10     | 17.31%  |
| WDC                 | 8        | 12     | 15.38%  |
| Samsung Electronics | 5        | 6      | 9.62%   |
| Hitachi             | 5        | 6      | 9.62%   |
| Kingston            | 4        | 5      | 7.69%   |
| Toshiba             | 3        | 3      | 5.77%   |
| SanDisk             | 3        | 3      | 5.77%   |
| WD MediaMax         | 1        | 1      | 1.92%   |
| Unknown             | 1        | 1      | 1.92%   |
| TO Exter            | 1        | 1      | 1.92%   |
| T-FORCE             | 1        | 1      | 1.92%   |
| RSH-319             | 1        | 1      | 1.92%   |
| Patriot             | 1        | 1      | 1.92%   |
| Maxtor              | 1        | 1      | 1.92%   |
| Kston               | 1        | 2      | 1.92%   |
| Intel               | 1        | 1      | 1.92%   |
| HGST HUS            | 1        | 2      | 1.92%   |
| HGST                | 1        | 1      | 1.92%   |
| External            | 1        | 1      | 1.92%   |
| Crucial             | 1        | 1      | 1.92%   |
| Apricorn            | 1        | 1      | 1.92%   |
| Apacer              | 1        | 1      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB             | 3        | 5.17%   |
| Toshiba DT01ACA100 1TB                      | 2        | 3.45%   |
| Seagate ST3120213AS 120GB                   | 2        | 3.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD            | 1        | 1.72%   |
| WDC WDS100T1X0E-00AFY0 1TB                  | 1        | 1.72%   |
| WDC WD800BB-00CAA1 80GB                     | 1        | 1.72%   |
| WDC WD5000AAKX-75U6AA0 500GB                | 1        | 1.72%   |
| WDC WD3200BPVT-00HXZT3 320GB                | 1        | 1.72%   |
| WDC WD30EZRZ-00GXCB0 3TB                    | 1        | 1.72%   |
| WDC WD2500AAJS-07M0A0 250GB                 | 1        | 1.72%   |
| WDC WD20EZRX-00D8PB0 2TB                    | 1        | 1.72%   |
| WDC WD20EZBX-00AYRA0 2TB                    | 1        | 1.72%   |
| WDC WD10EZRZ-00Z5HB0 1TB                    | 1        | 1.72%   |
| WDC WD10EURX-63C57Y0 1TB                    | 1        | 1.72%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB        | 1        | 1.72%   |
| WD MediaMax WL250GSA872 250GB               | 1        | 1.72%   |
| Unknown 032G72  32GB                        | 1        | 1.72%   |
| Toshiba MK6465GSX 640GB                     | 1        | 1.72%   |
| TO Exter nal USB 3.0 180GB                  | 1        | 1.72%   |
| T-FORCE 1TB                                 | 1        | 1.72%   |
| Seagate ST500LM000-1EJ162 500GB             | 1        | 1.72%   |
| Seagate ST4000DM004-2CV104 4TB              | 1        | 1.72%   |
| Seagate ST2000NE001-2M5101 2TB              | 1        | 1.72%   |
| Seagate ST2000LM003 HN-M201RAD 2TB          | 1        | 1.72%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 1        | 1.72%   |
| SanDisk SSD PLUS 1000GB                     | 1        | 1.72%   |
| SanDisk SD8SN8U128G1001 128GB SSD           | 1        | 1.72%   |
| SanDisk DF4032  32GB                        | 1        | 1.72%   |
| Samsung SSD 980 PRO 2TB                     | 1        | 1.72%   |
| Samsung SSD 860 EVO 1TB                     | 1        | 1.72%   |
| Samsung SSD 830 Series 256GB                | 1        | 1.72%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1        | 1.72%   |
| Samsung HN-M500MBB 500GB                    | 1        | 1.72%   |
| Samsung HD502HJ 500GB                       | 1        | 1.72%   |
| RSH-319 ASM1153E 3TB                        | 1        | 1.72%   |
| Patriot Burst 240GB SSD                     | 1        | 1.72%   |
| Maxtor STM3160215AS 160GB                   | 1        | 1.72%   |
| Kston SSD 128GB                             | 1        | 1.72%   |
| Kingston SV300S37A120G 120GB SSD            | 1        | 1.72%   |
| Kingston SSDNow V Series 64GB               | 1        | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 9      | 28.13%  |
| WDC                 | 7        | 9      | 21.88%  |
| Hitachi             | 5        | 6      | 15.63%  |
| Toshiba             | 3        | 3      | 9.38%   |
| Samsung Electronics | 2        | 2      | 6.25%   |
| WD MediaMax         | 1        | 1      | 3.13%   |
| RSH-319             | 1        | 1      | 3.13%   |
| Maxtor              | 1        | 1      | 3.13%   |
| HGST                | 1        | 1      | 3.13%   |
| External            | 1        | 1      | 3.13%   |
| Apricorn            | 1        | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 20%     |
| Kingston            | 3        | 4      | 20%     |
| SanDisk             | 2        | 2      | 13.33%  |
| WDC                 | 1        | 1      | 6.67%   |
| TO Exter            | 1        | 1      | 6.67%   |
| Patriot             | 1        | 1      | 6.67%   |
| Kston               | 1        | 2      | 6.67%   |
| Intel               | 1        | 1      | 6.67%   |
| Crucial             | 1        | 1      | 6.67%   |
| Apacer              | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 21       | 35     | 50%     |
| SSD     | 14       | 17     | 33.33%  |
| NVMe    | 4        | 5      | 9.52%   |
| MMC     | 2        | 2      | 4.76%   |
| Unknown | 1        | 3      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 49     | 76.32%  |
| NVMe | 4        | 5      | 10.53%  |
| SAS  | 3        | 6      | 7.89%   |
| MMC  | 2        | 2      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 25       | 32     | 59.52%  |
| 0.51-1.0   | 7        | 8      | 16.67%  |
| 2.01-3.0   | 4        | 5      | 9.52%   |
| 1.01-2.0   | 4        | 5      | 9.52%   |
| 3.01-4.0   | 2        | 2      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 9        | 26.47%  |
| 251-500        | 5        | 14.71%  |
| 21-50          | 5        | 14.71%  |
| 2001-3000      | 4        | 11.76%  |
| 1-20           | 4        | 11.76%  |
| More than 3000 | 2        | 5.88%   |
| 1001-2000      | 2        | 5.88%   |
| 501-1000       | 2        | 5.88%   |
| 51-100         | 1        | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 15       | 44.12%  |
| 21-50          | 6        | 17.65%  |
| 101-250        | 3        | 8.82%   |
| 501-1000       | 3        | 8.82%   |
| 251-500        | 2        | 5.88%   |
| 1001-2000      | 2        | 5.88%   |
| More than 3000 | 1        | 2.94%   |
| 2001-3000      | 1        | 2.94%   |
| 51-100         | 1        | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba MK6465GSX 640GB          | 1        | 1      | 25%     |
| Seagate ST500DM002-1BD142 500GB  | 1        | 1      | 25%     |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 1      | 25%     |
| Apacer 16GB SATA Flash Drive SSD | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 50%     |
| Toshiba | 1        | 1      | 25%     |
| Apacer  | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| Toshiba | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 75%     |
| SSD  | 1        | 1      | 25%     |

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
| Detected | 18       | 37     | 52.94%  |
| Works    | 12       | 21     | 35.29%  |
| Malfunc  | 4        | 4      | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 22       | 55%     |
| AMD                         | 8        | 20%     |
| SanDisk                     | 2        | 5%      |
| Nvidia                      | 2        | 5%      |
| Seagate Technology          | 1        | 2.5%    |
| Samsung Electronics         | 1        | 2.5%    |
| Marvell Technology Group    | 1        | 2.5%    |
| Kingston Technology Company | 1        | 2.5%    |
| JMicron Technology          | 1        | 2.5%    |
| ASMedia Technology          | 1        | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 11.11%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 9.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 7.41%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 5.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 5.56%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 3.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 3.7%    |
| Seagate FireCuda 520 SSD                                                                | 1        | 1.85%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.85%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 1.85%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 1.85%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 1.85%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.85%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.85%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.85%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.85%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.85%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.85%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.85%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 1.85%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 55%     |
| IDE  | 12       | 30%     |
| NVMe | 4        | 10%     |
| RAID | 2        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 24       | 70.59%  |
| AMD    | 10       | 29.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Pentium D CPU 2.80GHz                | 2        | 5.88%   |
| Intel Celeron J4125 CPU @ 2.00GHz          | 2        | 5.88%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 2        | 5.88%   |
| Intel Xeon CPU W3565 @ 3.20GHz             | 1        | 2.94%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz        | 1        | 2.94%   |
| Intel Core i9-10900K CPU @ 3.70GHz         | 1        | 2.94%   |
| Intel Core i7 CPU 920 @ 2.67GHz            | 1        | 2.94%   |
| Intel Core i5-6600K CPU @ 3.50GHz          | 1        | 2.94%   |
| Intel Core i5-4590T CPU @ 2.00GHz          | 1        | 2.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz           | 1        | 2.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 1        | 2.94%   |
| Intel Core i3-4170 CPU @ 3.70GHz           | 1        | 2.94%   |
| Intel Core i3-2120 CPU @ 3.30GHz           | 1        | 2.94%   |
| Intel Core i3-10105 CPU @ 3.70GHz          | 1        | 2.94%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz      | 1        | 2.94%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz      | 1        | 2.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 1        | 2.94%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz       | 1        | 2.94%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz       | 1        | 2.94%   |
| Intel Celeron CPU N3010 @ 1.04GHz          | 1        | 2.94%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 1        | 2.94%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz          | 1        | 2.94%   |
| Intel Atom CPU D525 @ 1.80GHz              | 1        | 2.94%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 1        | 2.94%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 1        | 2.94%   |
| AMD Ryzen 7 2700 Eight-Core Processor      | 1        | 2.94%   |
| AMD Phenom II X4 820 Processor             | 1        | 2.94%   |
| AMD FX-6350 Six-Core Processor             | 1        | 2.94%   |
| AMD FX-6300 Six-Core Processor             | 1        | 2.94%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+ | 1        | 2.94%   |
| AMD A8-3850 APU with Radeon HD Graphics    | 1        | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 4        | 11.76%  |
| Intel Core i3     | 3        | 8.82%   |
| Intel Core 2 Duo  | 3        | 8.82%   |
| Intel Celeron     | 3        | 8.82%   |
| Intel Atom        | 3        | 8.82%   |
| Intel Xeon        | 2        | 5.88%   |
| Intel Pentium D   | 2        | 5.88%   |
| Intel Core 2 Quad | 2        | 5.88%   |
| AMD Ryzen 7       | 2        | 5.88%   |
| AMD Ryzen 5       | 2        | 5.88%   |
| AMD FX            | 2        | 5.88%   |
| Intel Core i9     | 1        | 2.94%   |
| Intel Core i7     | 1        | 2.94%   |
| AMD Ryzen 9       | 1        | 2.94%   |
| AMD Phenom II X4  | 1        | 2.94%   |
| AMD Athlon 64 X2  | 1        | 2.94%   |
| AMD A8            | 1        | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 16       | 47.06%  |
| 2      | 9        | 26.47%  |
| 8      | 3        | 8.82%   |
| 6      | 2        | 5.88%   |
| 3      | 2        | 5.88%   |
| 10     | 1        | 2.94%   |
| 1      | 1        | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 64.71%  |
| 2      | 12       | 35.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 34       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 55.88%  |
| 0x406c4    | 2        | 5.88%   |
| 0x306c3    | 2        | 5.88%   |
| 0xa0653    | 1        | 2.94%   |
| 0x706a8    | 1        | 2.94%   |
| 0x6fb      | 1        | 2.94%   |
| 0x506e3    | 1        | 2.94%   |
| 0x106ca    | 1        | 2.94%   |
| 0x106a5    | 1        | 2.94%   |
| 0x1067a    | 1        | 2.94%   |
| 0x0a50000c | 1        | 2.94%   |
| 0x0a201009 | 1        | 2.94%   |
| 0x08001138 | 1        | 2.94%   |
| 0x06000852 | 1        | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 3        | 8.82%   |
| Penryn        | 3        | 8.82%   |
| Haswell       | 3        | 8.82%   |
| Zen+          | 2        | 5.88%   |
| Zen 3         | 2        | 5.88%   |
| Piledriver    | 2        | 5.88%   |
| NetBurst      | 2        | 5.88%   |
| Nehalem       | 2        | 5.88%   |
| IvyBridge     | 2        | 5.88%   |
| Goldmont plus | 2        | 5.88%   |
| Core          | 2        | 5.88%   |
| CometLake     | 2        | 5.88%   |
| Zen           | 1        | 2.94%   |
| Skylake       | 1        | 2.94%   |
| SandyBridge   | 1        | 2.94%   |
| K8 Hammer     | 1        | 2.94%   |
| K10 Llano     | 1        | 2.94%   |
| K10           | 1        | 2.94%   |
| Bonnell       | 1        | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 13       | 36.11%  |
| Intel  | 12       | 33.33%  |
| AMD    | 11       | 30.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 7.69%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 7.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 5.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 5.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 5.13%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 5.13%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 5.13%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 5.13%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 2.56%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 2.56%   |
| Nvidia GT218 [ION]                                                                       | 1        | 2.56%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 2.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 2.56%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1        | 2.56%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1        | 2.56%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 2.56%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 2.56%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 2.56%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 2.56%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 2.56%   |
| Nvidia C78 [GeForce 9100]                                                                | 1        | 2.56%   |
| Nvidia C77 [GeForce 8200]                                                                | 1        | 2.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 2.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 2.56%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 1        | 2.56%   |
| AMD Cezanne                                                                              | 1        | 2.56%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 1        | 2.56%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1        | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 11       | 32.35%  |
| 1 x Intel          | 11       | 32.35%  |
| 1 x AMD            | 8        | 23.53%  |
| 2 x AMD            | 2        | 5.88%   |
| Intel + 2 x Nvidia | 1        | 2.94%   |
| AMD + Nvidia       | 1        | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 79.41%  |
| Proprietary | 6        | 17.65%  |
| Unknown     | 1        | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 67.65%  |
| 0.01-0.5   | 4        | 11.76%  |
| 7.01-8.0   | 3        | 8.82%   |
| 3.01-4.0   | 1        | 2.94%   |
| 2.01-3.0   | 1        | 2.94%   |
| 8.01-16.0  | 1        | 2.94%   |
| 0.51-1.0   | 1        | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 16.13%  |
| Hewlett-Packard      | 5        | 16.13%  |
| Dell                 | 4        | 12.9%   |
| Goldstar             | 3        | 9.68%   |
| Ancor Communications | 3        | 9.68%   |
| Philips              | 2        | 6.45%   |
| Unknown              | 1        | 3.23%   |
| Sony                 | 1        | 3.23%   |
| SNC                  | 1        | 3.23%   |
| Sharp                | 1        | 3.23%   |
| MSI                  | 1        | 3.23%   |
| LG Electronics       | 1        | 3.23%   |
| Eizo                 | 1        | 3.23%   |
| BenQ                 | 1        | 3.23%   |
| Acer                 | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 3.13%   |
| Sony TV SNY9C01 1920x1080                                             | 1        | 3.13%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 1        | 3.13%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch              | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 3.13%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1        | 3.13%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch  | 1        | 3.13%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch    | 1        | 3.13%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1        | 3.13%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                    | 1        | 3.13%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                   | 1        | 3.13%   |
| LG Electronics LCD Monitor E2241 1920x1080                            | 1        | 3.13%   |
| Hewlett-Packard w2338h HWP281B 1920x1080 509x286mm 23.0-inch          | 1        | 3.13%   |
| Hewlett-Packard W2071d HWP299E 1600x900 443x249mm 20.0-inch           | 1        | 3.13%   |
| Hewlett-Packard E201 HWP305E 1600x900 440x250mm 19.9-inch             | 1        | 3.13%   |
| Hewlett-Packard 2311 HWP293A 1920x1080 509x286mm 23.0-inch            | 1        | 3.13%   |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch             | 1        | 3.13%   |
| Goldstar M2394D GSM56C4 1920x1080 510x280mm 22.9-inch                 | 1        | 3.13%   |
| Goldstar LG HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch              | 1        | 3.13%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                  | 1        | 3.13%   |
| Eizo L565 ENC1651 1280x1024 337x270mm 17.0-inch                       | 1        | 3.13%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1        | 3.13%   |
| Dell LCD Monitor DELA102 1920x1080 540x300mm 24.3-inch                | 1        | 3.13%   |
| Dell E2209W DELD01F 1680x1050 473x296mm 22.0-inch                     | 1        | 3.13%   |
| Dell E2209W DELD01E 1680x1050 473x296mm 22.0-inch                     | 1        | 3.13%   |
| Dell E1909W DELF00D 1440x900 408x255mm 18.9-inch                      | 1        | 3.13%   |
| BenQ GW2265 BNQ78D1 1920x1080 477x268mm 21.5-inch                     | 1        | 3.13%   |
| Ancor Communications VW22A ACI22E3 1680x1050 473x296mm 22.0-inch      | 1        | 3.13%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 1        | 3.13%   |
| Ancor Communications ASUS VH242 ACI24FA 1920x1080 521x293mm 23.5-inch | 1        | 3.13%   |
| Acer S242HL ACR0216 1920x1080 531x299mm 24.0-inch                     | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 41.38%  |
| 1600x900 (HD+)     | 4        | 13.79%  |
| 1366x768 (WXGA)    | 3        | 10.34%  |
| 1280x1024 (SXGA)   | 3        | 10.34%  |
| 2560x1440 (QHD)    | 2        | 6.9%    |
| 1680x1050 (WSXGA+) | 2        | 6.9%    |
| 2560x1600          | 1        | 3.45%   |
| 1440x900 (WXGA+)   | 1        | 3.45%   |
| 1280x720 (HD)      | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 4        | 13.33%  |
| 27      | 3        | 10%     |
| 24      | 3        | 10%     |
| 20      | 3        | 10%     |
| 19      | 3        | 10%     |
| 18      | 3        | 10%     |
| 22      | 2        | 6.67%   |
| 21      | 2        | 6.67%   |
| Unknown | 2        | 6.67%   |
| 72      | 1        | 3.33%   |
| 49      | 1        | 3.33%   |
| 43      | 1        | 3.33%   |
| 17      | 1        | 3.33%   |
| 15      | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 12       | 40%     |
| 501-600     | 10       | 33.33%  |
| 301-350     | 2        | 6.67%   |
| Unknown     | 2        | 6.67%   |
| 351-400     | 1        | 3.33%   |
| 1501-2000   | 1        | 3.33%   |
| 1001-1500   | 1        | 3.33%   |
| 901-1000    | 1        | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 71.43%  |
| 16/10   | 3        | 10.71%  |
| 5/4     | 2        | 7.14%   |
| Unknown | 2        | 7.14%   |
| 4/3     | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 31.03%  |
| 151-200        | 6        | 20.69%  |
| 141-150        | 4        | 13.79%  |
| 301-350        | 3        | 10.34%  |
| More than 1000 | 2        | 6.9%    |
| Unknown        | 2        | 6.9%    |
| 251-300        | 1        | 3.45%   |
| 111-120        | 1        | 3.45%   |
| 501-1000       | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 64.29%  |
| 101-120 | 5        | 17.86%  |
| 1-50    | 3        | 10.71%  |
| Unknown | 2        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 85.29%  |
| 2     | 4        | 11.76%  |
| 0     | 1        | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 37.78%  |
| Intel                 | 13       | 28.89%  |
| Qualcomm Atheros      | 3        | 6.67%   |
| Broadcom              | 3        | 6.67%   |
| TP-Link               | 2        | 4.44%   |
| Samsung Electronics   | 2        | 4.44%   |
| Nvidia                | 2        | 4.44%   |
| Trident Microsystems  | 1        | 2.22%   |
| MediaTek              | 1        | 2.22%   |
| Broadcom Limited      | 1        | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 14       | 28%     |
| Intel Ethernet Controller I225-V                                    | 3        | 6%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 6%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 4%      |
| Nvidia MCP77 Ethernet                                               | 2        | 4%      |
| Intel NM10/ICH7 Family LAN Controller                               | 2        | 4%      |
| Intel Ethernet Connection I217-LM                                   | 2        | 4%      |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 4%      |
| Trident Microsystems 4DWave DX                                      | 1        | 2%      |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 2%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 2%      |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1        | 2%      |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 2%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 2%      |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 2%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 2%      |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 2%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 2%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 2%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 2%      |
| Intel Wi-Fi 6 AX200                                                 | 1        | 2%      |
| Intel Centrino Advanced-N 6235                                      | 1        | 2%      |
| Intel 82567LF-2 Gigabit Network Connection                          | 1        | 2%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 1        | 2%      |
| Broadcom Limited BCM43224 802.11a/b/g/n                             | 1        | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 28.57%  |
| TP-Link               | 2        | 14.29%  |
| Qualcomm Atheros      | 2        | 14.29%  |
| Intel                 | 2        | 14.29%  |
| Broadcom              | 2        | 14.29%  |
| MediaTek              | 1        | 7.14%   |
| Broadcom Limited      | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 14.29%  |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 7.14%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 7.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 7.14%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 7.14%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 7.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 7.14%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 7.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 7.14%   |
| Intel Wi-Fi 6 AX200                                                 | 1        | 7.14%   |
| Intel Centrino Advanced-N 6235                                      | 1        | 7.14%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                             | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 47.22%  |
| Intel                 | 11       | 30.56%  |
| Samsung Electronics   | 2        | 5.56%   |
| Qualcomm Atheros      | 2        | 5.56%   |
| Nvidia                | 2        | 5.56%   |
| Trident Microsystems  | 1        | 2.78%   |
| Broadcom              | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 38.89%  |
| Intel Ethernet Controller I225-V                                  | 3        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 5.56%   |
| Nvidia MCP77 Ethernet                                             | 2        | 5.56%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 5.56%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 5.56%   |
| Trident Microsystems 4DWave DX                                    | 1        | 2.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 2.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 2.78%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 2.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 2.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.78%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 2.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 70.21%  |
| WiFi     | 14       | 29.79%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 67.65%  |
| WiFi     | 11       | 32.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 64.71%  |
| 2     | 9        | 26.47%  |
| 4     | 1        | 2.94%   |
| 3     | 1        | 2.94%   |
| 0     | 1        | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 67.65%  |
| Yes  | 11       | 32.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2        | 28.57%  |
| Realtek Semiconductor | 1        | 14.29%  |
| MediaTek              | 1        | 14.29%  |
| Logitech              | 1        | 14.29%  |
| Foxconn / Hon Hai     | 1        | 14.29%  |
| Broadcom              | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Realtek  Bluetooth 4.2 Adapter                | 1        | 14.29%  |
| MediaTek Wireless_Device                      | 1        | 14.29%  |
| Logitech BT Mini-Receiver (HCI mode)          | 1        | 14.29%  |
| Intel Centrino Bluetooth Wireless Transceiver | 1        | 14.29%  |
| Intel AX200 Bluetooth                         | 1        | 14.29%  |
| Foxconn / Hon Hai Bluetooth Device            | 1        | 14.29%  |
| Broadcom BCM20702A0 Bluetooth 4.0             | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 22       | 43.14%  |
| Nvidia                                       | 12       | 23.53%  |
| AMD                                          | 11       | 21.57%  |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.96%   |
| Razer USA                                    | 1        | 1.96%   |
| Ensoniq                                      | 1        | 1.96%   |
| Creative Labs                                | 1        | 1.96%   |
| C-Media Electronics                          | 1        | 1.96%   |
| ASUSTek Computer                             | 1        | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 11.86%  |
| Nvidia High Definition Audio Controller                                                           | 3        | 5.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 5.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 5.08%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 3        | 5.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 5.08%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2        | 3.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2        | 3.39%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 3.39%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 3.39%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 1.69%   |
| Razer USA Razer Kraken X USB                                                                      | 1        | 1.69%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1        | 1.69%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 1.69%   |
| Nvidia GM200 High Definition Audio                                                                | 1        | 1.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 1.69%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 1.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 1.69%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1        | 1.69%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 1.69%   |
| Intel Audio device                                                                                | 1        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 1.69%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                                                      | 1        | 1.69%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1        | 1.69%   |
| ASUSTek Computer XONAR SOUND CARD                                                                 | 1        | 1.69%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1        | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1        | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1        | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1        | 1.69%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1        | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 1        | 1.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1        | 1.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1        | 1.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 3        | 15.79%  |
| SK hynix            | 3        | 15.79%  |
| Micron Technology   | 3        | 15.79%  |
| Kingston            | 3        | 15.79%  |
| Corsair             | 2        | 10.53%  |
| Samsung Electronics | 1        | 5.26%   |
| Nanya Technology    | 1        | 5.26%   |
| G.Skill             | 1        | 5.26%   |
| Elpida              | 1        | 5.26%   |
| Unknown             | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 4.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 4.55%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 4.55%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s | 1        | 4.55%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s               | 1        | 4.55%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 1        | 4.55%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 4.55%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 4.55%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s       | 1        | 4.55%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 4.55%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s | 1        | 4.55%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s   | 1        | 4.55%   |
| Kingston RAM KN2M64-ETB 8GB DIMM DDR3 1600MT/s           | 1        | 4.55%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 1        | 4.55%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s  | 1        | 4.55%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3600MT/s      | 1        | 4.55%   |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4GB DIMM DDR3 1333MT/s      | 1        | 4.55%   |
| Elpida RAM EBJ21EE8BDFA-DJ-F 2GB DIMM DDR3 1333MT/s      | 1        | 4.55%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 1        | 4.55%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 1        | 4.55%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 1        | 4.55%   |
| Unknown                                                  | 1        | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 8        | 47.06%  |
| DDR3    | 5        | 29.41%  |
| DDR2    | 2        | 11.76%  |
| SDRAM   | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 70.59%  |
| SODIMM | 5        | 29.41%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 40%     |
| 2048  | 5        | 25%     |
| 4096  | 4        | 20%     |
| 16384 | 3        | 15%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 23.53%  |
| 3200    | 3        | 17.65%  |
| 3600    | 1        | 5.88%   |
| 2933    | 1        | 5.88%   |
| 2800    | 1        | 5.88%   |
| 2400    | 1        | 5.88%   |
| 2133    | 1        | 5.88%   |
| 2048    | 1        | 5.88%   |
| 1333    | 1        | 5.88%   |
| 1066    | 1        | 5.88%   |
| 667     | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model          | Desktops | Percent |
|----------------|----------|---------|
| Canon LiDE 300 | 1        | 100%    |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 2        | 40%     |
| Pixart Imaging         | 1        | 20%     |
| Microsoft              | 1        | 20%     |
| AVerMedia Technologies | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro | 1        | 20%     |
| Microsoft LifeCam VX-800             | 1        | 20%     |
| Logitech Webcam C270                 | 1        | 20%     |
| Logitech HD Webcam C615              | 1        | 20%     |
| AVerMedia Live Streamer CAM 313      | 1        | 20%     |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Cherry | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Cherry SmartCard Reader Keyboard KC 1000 SC | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 32       | 91.43%  |
| 1     | 3        | 8.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 2        | 66.67%  |
| Graphics card | 1        | 33.33%  |

