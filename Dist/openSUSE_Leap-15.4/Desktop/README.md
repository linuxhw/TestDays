openSUSE Leap-15.4 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.4.

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

Total: 70

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock   | B550M-ITX/ac                | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| Gigabyte | Z97-HD3                     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| ASRock   | B550M-ITX/ac                | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| Gigabyte | H55M-S2H                    | [f44b68cf93](https://linux-hardware.org/?probe=f44b68cf93) | Apr 16, 2023 |
| ASRock   | X670E Pro RS                | [0f078152ca](https://linux-hardware.org/?probe=0f078152ca) | Apr 10, 2023 |
| ASRock   | B450 Gaming K4              | [dcf97ad331](https://linux-hardware.org/?probe=dcf97ad331) | Apr 05, 2023 |
| MSI      | P67A-C43                    | [f3e7913310](https://linux-hardware.org/?probe=f3e7913310) | Apr 01, 2023 |
| ASUSTek  | ROG CROSSHAIR X670E HERO    | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| Wortmann | Terra 3100                  | [126586f434](https://linux-hardware.org/?probe=126586f434) | Mar 12, 2023 |
| Lenovo   | 102F SDK0J40697 WIN 3305... | [97741c600c](https://linux-hardware.org/?probe=97741c600c) | Mar 11, 2023 |
| Gigabyte | Z97-HD3                     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| Dell     | 0427JK A00                  | [4b47face39](https://linux-hardware.org/?probe=4b47face39) | Mar 05, 2023 |
| Lenovo   | Bantry CRB 31900058 STD     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| Lenovo   | Bantry CRB 31900058 STD     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| Dell     | 0427JK A00                  | [ca878d6577](https://linux-hardware.org/?probe=ca878d6577) | Feb 27, 2023 |
| ASRock   | B550M-ITX/ac                | [79204339d0](https://linux-hardware.org/?probe=79204339d0) | Feb 11, 2023 |
| HP       | 1494                        | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| HP       | 0B54h D                     | [fa38931f1f](https://linux-hardware.org/?probe=fa38931f1f) | Feb 06, 2023 |
| Gigabyte | Z690 GAMING X DDR4          | [f2636de53b](https://linux-hardware.org/?probe=f2636de53b) | Jan 31, 2023 |
| ASUSTek  | CROSSHAIR V FORMULA-Z       | [32dfb5ebe2](https://linux-hardware.org/?probe=32dfb5ebe2) | Jan 31, 2023 |
| Gigabyte | Z690 GAMING X DDR4          | [6bf8eb9c73](https://linux-hardware.org/?probe=6bf8eb9c73) | Jan 30, 2023 |
| ASUSTek  | PRIME A320M-K               | [17fd020689](https://linux-hardware.org/?probe=17fd020689) | Jan 16, 2023 |
| Dell     | 0WG261                      | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| Dell     | 0WG261                      | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| MSI      | X470 GAMING PRO CARBON      | [947534b3be](https://linux-hardware.org/?probe=947534b3be) | Dec 09, 2022 |
| ASUSTek  | PRIME B350M-A               | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| MSI      | B85-G41 PC Mate             | [a54611689d](https://linux-hardware.org/?probe=a54611689d) | Dec 06, 2022 |
| Dell     | 0C522T A01                  | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| Gigabyte | GA-770TA-UD3                | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| Lenovo   | 1036 SDK0K17763 WIN 1801... | [94f3d7aa9d](https://linux-hardware.org/?probe=94f3d7aa9d) | Oct 22, 2022 |
| ASUSTek  | P5P43TD PRO                 | [a29fae2a74](https://linux-hardware.org/?probe=a29fae2a74) | Oct 14, 2022 |
| MSI      | Z170-A PRO                  | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| MSI      | B450-A PRO MAX              | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI      | B450-A PRO MAX              | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII EXTRE... | [6e0984d7ff](https://linux-hardware.org/?probe=6e0984d7ff) | Sep 06, 2022 |
| ASUSTek  | P5P43TD PRO                 | [f79c38f9ff](https://linux-hardware.org/?probe=f79c38f9ff) | Sep 02, 2022 |
| Lenovo   | 1036 SDK0K17763 WIN 1801... | [3772ec2911](https://linux-hardware.org/?probe=3772ec2911) | Sep 02, 2022 |
| ASRock   | J3355B-ITX                  | [e27f786190](https://linux-hardware.org/?probe=e27f786190) | Aug 28, 2022 |
| Gigabyte | 965P-DS3                    | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| HP       | 802F                        | [2c52215323](https://linux-hardware.org/?probe=2c52215323) | Aug 23, 2022 |
| HP       | 802F                        | [e181d03426](https://linux-hardware.org/?probe=e181d03426) | Aug 23, 2022 |
| ASRock   | Z490 Phantom Gaming 4       | [7b66b20b9f](https://linux-hardware.org/?probe=7b66b20b9f) | Aug 17, 2022 |
| ASRock   | J3355B-ITX                  | [99f7986364](https://linux-hardware.org/?probe=99f7986364) | Aug 02, 2022 |
| ASUSTek  | PRIME B550M-K               | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| Biostar  | B450MH                      | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar  | B450MH                      | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| ASUSTek  | TUF Gaming X570-PRO         | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| MSI      | B450 GAMING PRO CARBON A... | [03d7fde009](https://linux-hardware.org/?probe=03d7fde009) | Jul 18, 2022 |
| Dell     | 0Y2YM6 A00                  | [8b5480a55e](https://linux-hardware.org/?probe=8b5480a55e) | Jul 16, 2022 |
| MSI      | X399 GAMING PRO CARBON A... | [153a698b74](https://linux-hardware.org/?probe=153a698b74) | Jul 01, 2022 |
| Dell     | 0J3C2F A03                  | [6f5f6a7417](https://linux-hardware.org/?probe=6f5f6a7417) | Jun 26, 2022 |
| ASRock   | J3355B-ITX                  | [a00111330b](https://linux-hardware.org/?probe=a00111330b) | Jun 24, 2022 |
| ASUSTek  | TUF Gaming Z590-PLUS        | [520f9b42b8](https://linux-hardware.org/?probe=520f9b42b8) | Jun 20, 2022 |
| HP       | 87C3                        | [1383f85e70](https://linux-hardware.org/?probe=1383f85e70) | Jun 09, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [06e496124a](https://linux-hardware.org/?probe=06e496124a) | Jun 08, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [fd421da52b](https://linux-hardware.org/?probe=fd421da52b) | Jun 08, 2022 |
| MSI      | B450 TOMAHAWK               | [0020802901](https://linux-hardware.org/?probe=0020802901) | May 30, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [e01bfd360d](https://linux-hardware.org/?probe=e01bfd360d) | May 14, 2022 |
| ASUSTek  | PRIME B550M-A WIFI II       | [2e8f888ca3](https://linux-hardware.org/?probe=2e8f888ca3) | May 11, 2022 |
| ASUSTek  | M5A78L-M/USB3               | [ace8669bdd](https://linux-hardware.org/?probe=ace8669bdd) | May 10, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [99078d316d](https://linux-hardware.org/?probe=99078d316d) | May 10, 2022 |
| ASUSTek  | TUF Gaming B550M-E          | [a3c1257116](https://linux-hardware.org/?probe=a3c1257116) | May 09, 2022 |
| ASUSTek  | TUF Gaming B550M-E WIFI     | [27b384c114](https://linux-hardware.org/?probe=27b384c114) | May 08, 2022 |
| ASUSTek  | TUF Gaming B550M-E WIFI     | [d427368abd](https://linux-hardware.org/?probe=d427368abd) | May 08, 2022 |
| ASUSTek  | M4A785TD-V EVO              | [622ff28b28](https://linux-hardware.org/?probe=622ff28b28) | May 05, 2022 |
| ASUSTek  | CROSSHAIR V FORMULA-Z       | [e5a11e0fdd](https://linux-hardware.org/?probe=e5a11e0fdd) | May 04, 2022 |
| ASUSTek  | CROSSHAIR V FORMULA-Z       | [34dcc7bc0c](https://linux-hardware.org/?probe=34dcc7bc0c) | May 04, 2022 |
| ASUSTek  | M4A785TD-V EVO              | [aea37c880d](https://linux-hardware.org/?probe=aea37c880d) | May 04, 2022 |
| Intel    | DG965RY AAD41691-301        | [c2d30af3ce](https://linux-hardware.org/?probe=c2d30af3ce) | Dec 25, 2021 |
| Intel    | DG965RY AAD41691-301        | [586e536e6c](https://linux-hardware.org/?probe=586e536e6c) | Dec 25, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.14.21-150400.22-default           | 11       | 19.64%  |
| 5.14.21-150400.24.46-default        | 6        | 10.71%  |
| 5.14.21-150400.24.21-default        | 6        | 10.71%  |
| 5.14.21-150400.24.18-default        | 6        | 10.71%  |
| 5.14.21-150400.19-default           | 6        | 10.71%  |
| 5.14.21-150400.24.55-default        | 5        | 8.93%   |
| 5.14.21-150400.24.41-default        | 5        | 8.93%   |
| 5.14.21-150400.24.33-default        | 3        | 5.36%   |
| 5.18.0-rc6-lp153.2.ged50f8f-default | 2        | 3.57%   |
| 5.14.21-150400.24.38-default        | 2        | 3.57%   |
| 5.18.2-lp153.4.g6d13af9-default     | 1        | 1.79%   |
| 5.14.21-150400.24.60-default        | 1        | 1.79%   |
| 5.14.21-150400.24.11-default        | 1        | 1.79%   |
| 5.14.19-150400.1-default            | 1        | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.21 | 47       | 92.16%  |
| 5.18.0  | 2        | 3.92%   |
| 5.18.2  | 1        | 1.96%   |
| 5.14.19 | 1        | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 48       | 94.12%  |
| 5.18    | 3        | 5.88%   |

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


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KDE5        | 36       | 72%     |
| GNOME       | 6        | 12%     |
| Unknown     | 5        | 10%     |
| XFCE        | 2        | 4%      |
| WindowMaker | 1        | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 42       | 84%     |
| Wayland | 5        | 10%     |
| Unknown | 2        | 4%      |
| Tty     | 1        | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 50%     |
| SDDM    | 14       | 28%     |
| LightDM | 10       | 20%     |
| XDM     | 1        | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 18       | 36%     |
| POSIX   | 8        | 16%     |
| de_DE   | 6        | 12%     |
| pt_BR   | 4        | 8%      |
| nl_NL   | 3        | 6%      |
| fr_FR   | 2        | 4%      |
| en_GB   | 2        | 4%      |
| ro_RO   | 1        | 2%      |
| pl_PL   | 1        | 2%      |
| es_ES   | 1        | 2%      |
| el_GR   | 1        | 2%      |
| de_CH   | 1        | 2%      |
| ca_ES   | 1        | 2%      |
| Unknown | 1        | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 35       | 70%     |
| EFI  | 15       | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 32       | 64%     |
| Ext4  | 16       | 32%     |
| Xfs   | 1        | 2%      |
| Ext3  | 1        | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 44%     |
| GPT     | 20       | 40%     |
| MBR     | 8        | 16%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 84.31%  |
| Yes       | 8        | 15.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 78%     |
| Yes       | 11       | 22%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 34%     |
| MSI                 | 8        | 16%     |
| Gigabyte Technology | 5        | 10%     |
| Dell                | 5        | 10%     |
| ASRock              | 5        | 10%     |
| Hewlett-Packard     | 4        | 8%      |
| Lenovo              | 3        | 6%      |
| Wortmann AG         | 1        | 2%      |
| Intel               | 1        | 2%      |
| Biostar             | 1        | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS TUF Gaming B550M-E             | 2        | 4%      |
| ASUS M4A785TD-V EVO                 | 2        | 4%      |
| ASUS CROSSHAIR V FORMULA-Z          | 2        | 4%      |
| Wortmann AG Terra 3100              | 1        | 2%      |
| MSI MS-7C02                         | 1        | 2%      |
| MSI MS-7B86                         | 1        | 2%      |
| MSI MS-7B85                         | 1        | 2%      |
| MSI MS-7B78                         | 1        | 2%      |
| MSI MS-7B09                         | 1        | 2%      |
| MSI MS-7971                         | 1        | 2%      |
| MSI MS-7850                         | 1        | 2%      |
| MSI MS-7673                         | 1        | 2%      |
| Lenovo ThinkStation P520 30BE008VGE | 1        | 2%      |
| Lenovo ThinkStation P500 30A6S4JU00 | 1        | 2%      |
| Lenovo H50-55 90BF001SUK            | 1        | 2%      |
| Intel DG965RY AAD41691-301          | 1        | 2%      |
| HP Z600 Workstation                 | 1        | 2%      |
| HP Z240 Tower Workstation           | 1        | 2%      |
| HP OMEN 30L Desktop GT13-0xxx       | 1        | 2%      |
| HP Compaq 8200 Elite CMT PC         | 1        | 2%      |
| Gigabyte Z97-HD3                    | 1        | 2%      |
| Gigabyte Z690 GAMING X DDR4         | 1        | 2%      |
| Gigabyte H55M-S2H                   | 1        | 2%      |
| Gigabyte GA-770TA-UD3               | 1        | 2%      |
| Gigabyte 965P-DS3                   | 1        | 2%      |
| Dell XPS 8940                       | 1        | 2%      |
| Dell Vostro 3268                    | 1        | 2%      |
| Dell OptiPlex 980                   | 1        | 2%      |
| Dell OptiPlex 790                   | 1        | 2%      |
| Dell DM051                          | 1        | 2%      |
| Biostar B450MH                      | 1        | 2%      |
| ASUS TUF Gaming Z590-PLUS           | 1        | 2%      |
| ASUS TUF Gaming X570-PRO            | 1        | 2%      |
| ASUS TUF Gaming B550M-E WIFI        | 1        | 2%      |
| ASUS ROG CROSSHAIR X670E HERO       | 1        | 2%      |
| ASUS ROG CROSSHAIR VIII EXTREME     | 1        | 2%      |
| ASUS PRIME B550M-K                  | 1        | 2%      |
| ASUS PRIME B550M-A WIFI II          | 1        | 2%      |
| ASUS PRIME B350M-A                  | 1        | 2%      |
| ASUS PRIME A320M-K                  | 1        | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS TUF              | 5        | 10%     |
| ASUS PRIME            | 4        | 8%      |
| Lenovo ThinkStation   | 2        | 4%      |
| Dell OptiPlex         | 2        | 4%      |
| ASUS ROG              | 2        | 4%      |
| ASUS M4A785TD-V       | 2        | 4%      |
| ASUS CROSSHAIR        | 2        | 4%      |
| Wortmann AG Terra     | 1        | 2%      |
| MSI MS-7C02           | 1        | 2%      |
| MSI MS-7B86           | 1        | 2%      |
| MSI MS-7B85           | 1        | 2%      |
| MSI MS-7B78           | 1        | 2%      |
| MSI MS-7B09           | 1        | 2%      |
| MSI MS-7971           | 1        | 2%      |
| MSI MS-7850           | 1        | 2%      |
| MSI MS-7673           | 1        | 2%      |
| Lenovo H50-55         | 1        | 2%      |
| Intel DG965RY         | 1        | 2%      |
| HP Z600               | 1        | 2%      |
| HP Z240               | 1        | 2%      |
| HP OMEN               | 1        | 2%      |
| HP Compaq             | 1        | 2%      |
| Gigabyte Z97-HD3      | 1        | 2%      |
| Gigabyte Z690         | 1        | 2%      |
| Gigabyte H55M-S2H     | 1        | 2%      |
| Gigabyte GA-770TA-UD3 | 1        | 2%      |
| Gigabyte 965P-DS3     | 1        | 2%      |
| Dell XPS              | 1        | 2%      |
| Dell Vostro           | 1        | 2%      |
| Dell DM051            | 1        | 2%      |
| Biostar B450MH        | 1        | 2%      |
| ASUS P5P43TD          | 1        | 2%      |
| ASUS M5A78L-M         | 1        | 2%      |
| ASRock Z490           | 1        | 2%      |
| ASRock X670E          | 1        | 2%      |
| ASRock J3355B-ITX     | 1        | 2%      |
| ASRock B550M-ITX      | 1        | 2%      |
| ASRock B450           | 1        | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 6        | 12%     |
| 2022 | 5        | 10%     |
| 2020 | 5        | 10%     |
| 2018 | 5        | 10%     |
| 2017 | 5        | 10%     |
| 2011 | 4        | 8%      |
| 2009 | 4        | 8%      |
| 2015 | 3        | 6%      |
| 2010 | 3        | 6%      |
| 2016 | 2        | 4%      |
| 2014 | 2        | 4%      |
| 2019 | 1        | 2%      |
| 2013 | 1        | 2%      |
| 2012 | 1        | 2%      |
| 2007 | 1        | 2%      |
| 2006 | 1        | 2%      |
| 2005 | 1        | 2%      |

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
| 32.01-64.0  | 14       | 27.45%  |
| 16.01-24.0  | 12       | 23.53%  |
| 64.01-256.0 | 8        | 15.69%  |
| 8.01-16.0   | 8        | 15.69%  |
| 4.01-8.0    | 3        | 5.88%   |
| 3.01-4.0    | 3        | 5.88%   |
| 24.01-32.0  | 3        | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 17       | 33.33%  |
| 4.01-8.0  | 11       | 21.57%  |
| 1.01-2.0  | 9        | 17.65%  |
| 3.01-4.0  | 8        | 15.69%  |
| 8.01-16.0 | 4        | 7.84%   |
| 0.51-1.0  | 2        | 3.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 18       | 34.62%  |
| 1      | 13       | 25%     |
| 3      | 10       | 19.23%  |
| 5      | 5        | 9.62%   |
| 7      | 2        | 3.85%   |
| 4      | 2        | 3.85%   |
| 9      | 1        | 1.92%   |
| 6      | 1        | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 56%     |
| No        | 22       | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 49       | 98%     |
| No        | 1        | 2%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 62%     |
| Yes       | 19       | 38%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 58.82%  |
| Yes       | 21       | 41.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 15       | 30%     |
| USA          | 7        | 14%     |
| Brazil       | 4        | 8%      |
| Netherlands  | 3        | 6%      |
| UK           | 2        | 4%      |
| Switzerland  | 2        | 4%      |
| Spain        | 2        | 4%      |
| Russia       | 2        | 4%      |
| South Africa | 1        | 2%      |
| Serbia       | 1        | 2%      |
| Romania      | 1        | 2%      |
| Poland       | 1        | 2%      |
| Norway       | 1        | 2%      |
| Martinique   | 1        | 2%      |
| Kazakhstan   | 1        | 2%      |
| Italy        | 1        | 2%      |
| India        | 1        | 2%      |
| Greece       | 1        | 2%      |
| France       | 1        | 2%      |
| Finland      | 1        | 2%      |
| Bulgaria     | 1        | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Haßfurt            | 5        | 8.93%   |
| Rio de Janeiro      | 2        | 3.57%   |
| Almere Stad         | 2        | 3.57%   |
| Zierikzee           | 1        | 1.79%   |
| Ulyanovsk           | 1        | 1.79%   |
| Schonbuhl           | 1        | 1.79%   |
| Santa Rosa          | 1        | 1.79%   |
| Sainte-Tulle        | 1        | 1.79%   |
| Rostock             | 1        | 1.79%   |
| Roslindale          | 1        | 1.79%   |
| Riviere Salee       | 1        | 1.79%   |
| Rattelsdorf         | 1        | 1.79%   |
| Ocala               | 1        | 1.79%   |
| Nesebar             | 1        | 1.79%   |
| Moscow              | 1        | 1.79%   |
| Mo i Rana           | 1        | 1.79%   |
| Milan               | 1        | 1.79%   |
| Macanet de la Selva | 1        | 1.79%   |
| Louisville          | 1        | 1.79%   |
| Le Lamentin         | 1        | 1.79%   |
| Lausanne            | 1        | 1.79%   |
| Landau              | 1        | 1.79%   |
| Kurten              | 1        | 1.79%   |
| Kulmbach            | 1        | 1.79%   |
| Kluszkowce          | 1        | 1.79%   |
| Kiel                | 1        | 1.79%   |
| Johannesburg        | 1        | 1.79%   |
| Jegenstorf          | 1        | 1.79%   |
| Hyderabad           | 1        | 1.79%   |
| Hollola             | 1        | 1.79%   |
| Helsinki            | 1        | 1.79%   |
| Heilbronn           | 1        | 1.79%   |
| HaÃŸfurt          | 1        | 1.79%   |
| Gloucester          | 1        | 1.79%   |
| Girona              | 1        | 1.79%   |
| Gaildorf            | 1        | 1.79%   |
| Dunfermline         | 1        | 1.79%   |
| Darmstadt           | 1        | 1.79%   |
| Dallas              | 1        | 1.79%   |
| Converse            | 1        | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 25       | 37     | 25.25%  |
| Samsung Electronics         | 22       | 35     | 22.22%  |
| WDC                         | 14       | 28     | 14.14%  |
| Kingston                    | 7        | 11     | 7.07%   |
| Crucial                     | 5        | 6      | 5.05%   |
| Toshiba                     | 4        | 5      | 4.04%   |
| SanDisk                     | 3        | 5      | 3.03%   |
| Patriot                     | 2        | 2      | 2.02%   |
| Maxtor                      | 2        | 2      | 2.02%   |
| Intel                       | 2        | 2      | 2.02%   |
| Hitachi                     | 2        | 2      | 2.02%   |
| Team                        | 1        | 1      | 1.01%   |
| StoreJet                    | 1        | 1      | 1.01%   |
| Smartbuy                    | 1        | 2      | 1.01%   |
| PNY                         | 1        | 1      | 1.01%   |
| Plextor                     | 1        | 2      | 1.01%   |
| Phison Electronics          | 1        | 1      | 1.01%   |
| MATSHITA                    | 1        | 1      | 1.01%   |
| Kingston Technology Company | 1        | 1      | 1.01%   |
| Intenso                     | 1        | 1      | 1.01%   |
| Fujitsu                     | 1        | 1      | 1.01%   |
| ADATA Technology            | 1        | 1      | 1.01%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 840 EVO 120GB                           | 5        | 4.03%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 2.42%   |
| Samsung SSD 860 EVO 500GB                           | 3        | 2.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 3        | 2.42%   |
| Kingston SA400S37480G 480GB SSD                     | 3        | 2.42%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 2        | 1.61%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.61%   |
| Seagate ST3500418AS 500GB                           | 2        | 1.61%   |
| Seagate ST3000NM0053 3TB                            | 2        | 1.61%   |
| Seagate Expansion 4TB                               | 2        | 1.61%   |
| SanDisk NVMe SSD Drive 240GB                        | 2        | 1.61%   |
| Samsung SSD 870 QVO 2TB                             | 2        | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 2        | 1.61%   |
| Kingston SA400S37960G 960GB SSD                     | 2        | 1.61%   |
| Crucial CT1000MX500SSD1 1TB                         | 2        | 1.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.81%   |
| WDC WDS500G1B0B-00AS40 500GB SSD                    | 1        | 0.81%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1        | 0.81%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.81%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1        | 0.81%   |
| WDC WD5000AZRX-00L4HB0 500GB                        | 1        | 0.81%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 1        | 0.81%   |
| WDC WD4003FRYZ-01F0DB0 4TB                          | 1        | 0.81%   |
| WDC WD30EZRX-00SPEB0 3TB                            | 1        | 0.81%   |
| WDC WD20SPZX-22UA7T0 2TB                            | 1        | 0.81%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.81%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1        | 0.81%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 1        | 0.81%   |
| WDC WD20EARX-00PASB0 2TB                            | 1        | 0.81%   |
| WDC WD20EARS-00MVWB0 2TB                            | 1        | 0.81%   |
| WDC WD120EDAZ-11F3RA0 12TB                          | 1        | 0.81%   |
| WDC WD10EZRX-00A8LB0 1TB                            | 1        | 0.81%   |
| WDC WD10EZEX-75WN4A0 1TB                            | 1        | 0.81%   |
| WDC WD10EURX-63C57Y0 1TB                            | 1        | 0.81%   |
| WDC WD10EADS-00M2B0 1TB                             | 1        | 0.81%   |
| WDC WD1003FBYX-01Y7B1 1TB                           | 1        | 0.81%   |
| Toshiba TL100 240GB SSD                             | 1        | 0.81%   |
| Toshiba MD04ACA50D 5TB                              | 1        | 0.81%   |
| Toshiba HDWU130 3TB                                 | 1        | 0.81%   |
| Toshiba DT01ACA200 2TB                              | 1        | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 33     | 48.98%  |
| WDC                 | 13       | 23     | 26.53%  |
| Samsung Electronics | 4        | 4      | 8.16%   |
| Toshiba             | 3        | 4      | 6.12%   |
| Maxtor              | 2        | 2      | 4.08%   |
| Hitachi             | 2        | 2      | 4.08%   |
| Fujitsu             | 1        | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 18     | 39.02%  |
| Kingston            | 5        | 7      | 12.2%   |
| Crucial             | 5        | 6      | 12.2%   |
| WDC                 | 4        | 4      | 9.76%   |
| Patriot             | 2        | 2      | 4.88%   |
| Toshiba             | 1        | 1      | 2.44%   |
| Team                | 1        | 1      | 2.44%   |
| StoreJet            | 1        | 1      | 2.44%   |
| Smartbuy            | 1        | 2      | 2.44%   |
| SanDisk             | 1        | 3      | 2.44%   |
| PNY                 | 1        | 1      | 2.44%   |
| Plextor             | 1        | 2      | 2.44%   |
| Intenso             | 1        | 1      | 2.44%   |
| Intel               | 1        | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 39       | 69     | 43.33%  |
| SSD     | 33       | 50     | 36.67%  |
| NVMe    | 17       | 28     | 18.89%  |
| Unknown | 1        | 1      | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 49       | 114    | 68.06%  |
| NVMe | 17       | 28     | 23.61%  |
| SAS  | 6        | 6      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 35       | 53     | 46.05%  |
| 0.51-1.0   | 16       | 30     | 21.05%  |
| 1.01-2.0   | 10       | 17     | 13.16%  |
| 2.01-3.0   | 6        | 7      | 7.89%   |
| 3.01-4.0   | 5        | 7      | 6.58%   |
| 10.01-20.0 | 2        | 2      | 2.63%   |
| 4.01-10.0  | 2        | 3      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 19       | 38%     |
| 1001-2000      | 12       | 24%     |
| 2001-3000      | 6        | 12%     |
| 251-500        | 5        | 10%     |
| 501-1000       | 5        | 10%     |
| 21-50          | 1        | 2%      |
| 101-250        | 1        | 2%      |
| Unknown        | 1        | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 51-100         | 11       | 21.57%  |
| 101-250        | 9        | 17.65%  |
| 1001-2000      | 9        | 17.65%  |
| 501-1000       | 9        | 17.65%  |
| 251-500        | 5        | 9.8%    |
| 2001-3000      | 3        | 5.88%   |
| More than 3000 | 2        | 3.92%   |
| 21-50          | 1        | 1.96%   |
| 1-20           | 1        | 1.96%   |
| Unknown        | 1        | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 840 EVO 120GB | 4        | 5      | 36.36%  |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 1      | 9.09%   |
| Seagate ST9500420AS 500GB             | 1        | 1      | 9.09%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 9.09%   |
| Samsung Electronics SSD 850 PRO 256GB | 1        | 1      | 9.09%   |
| Maxtor 6L250S0 256GB                  | 1        | 1      | 9.09%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 9.09%   |
| Intel SSD 600P Series 256GB           | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 45.45%  |
| Seagate             | 2        | 2      | 18.18%  |
| WDC                 | 1        | 1      | 9.09%   |
| Maxtor              | 1        | 1      | 9.09%   |
| Kingston            | 1        | 1      | 9.09%   |
| Intel               | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 50%     |
| WDC     | 1        | 1      | 25%     |
| Maxtor  | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 6        | 7      | 60%     |
| HDD  | 3        | 4      | 30%     |
| NVMe | 1        | 1      | 10%     |

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
| Detected | 24       | 74     | 41.38%  |
| Works    | 24       | 62     | 41.38%  |
| Malfunc  | 10       | 12     | 17.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 27       | 31.03%  |
| Intel                       | 24       | 27.59%  |
| Samsung Electronics         | 8        | 9.2%    |
| ASMedia Technology          | 6        | 6.9%    |
| Kingston Technology Company | 4        | 4.6%    |
| JMicron Technology          | 4        | 4.6%    |
| SanDisk                     | 3        | 3.45%   |
| Marvell Technology Group    | 3        | 3.45%   |
| Seagate Technology          | 2        | 2.3%    |
| LSI Logic / Symbios Logic   | 2        | 2.3%    |
| Silicon Image               | 1        | 1.15%   |
| Promise Technology          | 1        | 1.15%   |
| Phison Electronics          | 1        | 1.15%   |
| ADATA Technology            | 1        | 1.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 11.32%  |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 6.6%    |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 5.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 4.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 4.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 4.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 3.77%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3        | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 2.83%   |
| Seagate FireCuda 530 SSD                                                                | 2        | 1.89%   |
| SanDisk Non-Volatile memory controller                                                  | 2        | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.89%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.89%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 2        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.89%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.94%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.94%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.94%   |
| Promise PDC40719 [FastTrak TX4300/TX4310]                                               | 1        | 0.94%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.94%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.94%   |
| Marvell Group 88SE9125 PCIe SATA 6.0 Gb/s controller                                    | 1        | 0.94%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.94%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 0.94%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 0.94%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.94%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.94%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.94%   |
| Intel SSD 600P Series                                                                   | 1        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.94%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.94%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.94%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1        | 0.94%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.94%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 46       | 56.1%   |
| NVMe | 17       | 20.73%  |
| IDE  | 14       | 17.07%  |
| RAID | 4        | 4.88%   |
| SCSI | 1        | 1.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 27       | 54%     |
| Intel  | 23       | 46%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 5700G with Radeon Graphics         | 4        | 8%      |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 6%      |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 4%      |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 4%      |
| AMD Phenom II X6 1100T Processor               | 2        | 4%      |
| AMD FX-8350 Eight-Core Processor               | 2        | 4%      |
| Intel Xeon W-2135 CPU @ 3.70GHz                | 1        | 2%      |
| Intel Xeon CPU X5675 @ 3.07GHz                 | 1        | 2%      |
| Intel Xeon CPU E5450 @ 3.00GHz                 | 1        | 2%      |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 2%      |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz            | 1        | 2%      |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz    | 1        | 2%      |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 2%      |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 2%      |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 2%      |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 2%      |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 2%      |
| Intel Core i5-2500 CPU @ 3.30GHz               | 1        | 2%      |
| Intel Core i5-2400S CPU @ 2.50GHz              | 1        | 2%      |
| Intel Core i5-10500 CPU @ 3.10GHz              | 1        | 2%      |
| Intel Core i5 CPU 750 @ 2.67GHz                | 1        | 2%      |
| Intel Core i3-4150T CPU @ 3.00GHz              | 1        | 2%      |
| Intel Core i3 CPU 540 @ 3.07GHz                | 1        | 2%      |
| Intel Core 2 CPU 6700 @ 2.66GHz                | 1        | 2%      |
| Intel Celeron CPU J3355 @ 2.00GHz              | 1        | 2%      |
| Intel Atom CPU D525 @ 1.80GHz                  | 1        | 2%      |
| Intel 12th Gen Core i7-12700KF                 | 1        | 2%      |
| Intel 11th Gen Core i9-11900 @ 2.50GHz         | 1        | 2%      |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1        | 2%      |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 2%      |
| AMD Ryzen 9 7950X 16-Core Processor            | 1        | 2%      |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 2%      |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 2%      |
| AMD Ryzen 7 7700 8-Core Processor              | 1        | 2%      |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 2%      |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 2%      |
| AMD Ryzen 5 5600G with Radeon Graphics         | 1        | 2%      |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 2%      |
| AMD Phenom II X4 965 Processor                 | 1        | 2%      |
| AMD Phenom II X4 955 Processor                 | 1        | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 8        | 16%     |
| AMD Ryzen 7             | 7        | 14%     |
| Intel Core i5           | 6        | 12%     |
| Intel Xeon              | 5        | 10%     |
| Other                   | 3        | 6%      |
| AMD Ryzen 9             | 3        | 6%      |
| Intel Core i7           | 2        | 4%      |
| Intel Core i3           | 2        | 4%      |
| AMD Phenom II X6        | 2        | 4%      |
| AMD Phenom II X4        | 2        | 4%      |
| AMD FX                  | 2        | 4%      |
| Intel Pentium Dual-Core | 1        | 2%      |
| Intel Pentium 4         | 1        | 2%      |
| Intel Core 2            | 1        | 2%      |
| Intel Celeron           | 1        | 2%      |
| Intel Atom              | 1        | 2%      |
| AMD Ryzen Threadripper  | 1        | 2%      |
| AMD Ryzen 3             | 1        | 2%      |
| AMD A10                 | 1        | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 15       | 30%     |
| 6      | 11       | 22%     |
| 8      | 9        | 18%     |
| 2      | 7        | 14%     |
| 16     | 3        | 6%      |
| 12     | 3        | 6%      |
| 1      | 2        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 98%     |
| 2      | 1        | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 72%     |
| 1      | 14       | 28%     |

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
| Unknown    | 22       | 43.14%  |
| 0x0a50000c | 3        | 5.88%   |
| 0x0a50000d | 2        | 3.92%   |
| 0x0800820d | 2        | 3.92%   |
| 0x06000852 | 2        | 3.92%   |
| 0x010000dc | 2        | 3.92%   |
| 0x010000c8 | 2        | 3.92%   |
| 0xf4a      | 1        | 1.96%   |
| 0xa0671    | 1        | 1.96%   |
| 0x906e9    | 1        | 1.96%   |
| 0x90672    | 1        | 1.96%   |
| 0x6f6      | 1        | 1.96%   |
| 0x506e3    | 1        | 1.96%   |
| 0x306c3    | 1        | 1.96%   |
| 0x206a7    | 1        | 1.96%   |
| 0x106e5    | 1        | 1.96%   |
| 0x106ca    | 1        | 1.96%   |
| 0x0a601201 | 1        | 1.96%   |
| 0x0a50000b | 1        | 1.96%   |
| 0x0a201016 | 1        | 1.96%   |
| 0x08701021 | 1        | 1.96%   |
| 0x08001138 | 1        | 1.96%   |
| 0x06003106 | 1        | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen+             | 6        | 12%     |
| Zen 3            | 6        | 12%     |
| Zen 2            | 4        | 8%      |
| K10              | 4        | 8%      |
| Skylake          | 3        | 6%      |
| SandyBridge      | 3        | 6%      |
| Haswell          | 3        | 6%      |
| Unknown          | 3        | 6%      |
| Zen              | 2        | 4%      |
| Westmere         | 2        | 4%      |
| Piledriver       | 2        | 4%      |
| Penryn           | 2        | 4%      |
| Steamroller      | 1        | 2%      |
| NetBurst         | 1        | 2%      |
| Nehalem          | 1        | 2%      |
| KabyLake         | 1        | 2%      |
| Icelake          | 1        | 2%      |
| Goldmont         | 1        | 2%      |
| Core             | 1        | 2%      |
| CometLake        | 1        | 2%      |
| Bonnell          | 1        | 2%      |
| Alderlake Hybrid | 1        | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| AMD         | 27       | 50%     |
| Nvidia      | 21       | 38.89%  |
| Intel       | 5        | 9.26%   |
| S3 Graphics | 1        | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                      | 5        | 8.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                | 3        | 5.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                           | 3        | 5.36%   |
| Nvidia GK107 [GeForce GT 640]                                                     | 2        | 3.57%   |
| AMD RS880 [Radeon HD 4200]                                                        | 2        | 3.57%   |
| AMD Raphael                                                                       | 2        | 3.57%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                        | 2        | 3.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                        | 2        | 3.57%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                  | 2        | 3.57%   |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                           | 1        | 1.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                                   | 1        | 1.79%   |
| Nvidia TU106 [GeForce RTX 2070]                                                   | 1        | 1.79%   |
| Nvidia GT218M [ION]                                                               | 1        | 1.79%   |
| Nvidia GT216 [GeForce GT 220]                                                     | 1        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                                    | 1        | 1.79%   |
| Nvidia GM206 [GeForce GTX 960]                                                    | 1        | 1.79%   |
| Nvidia GM204 [GeForce GTX 970]                                                    | 1        | 1.79%   |
| Nvidia GM107GL [Quadro K2200]                                                     | 1        | 1.79%   |
| Nvidia GK208B [GeForce GT 730]                                                    | 1        | 1.79%   |
| Nvidia GF119 [GeForce GT 610]                                                     | 1        | 1.79%   |
| Nvidia GF119 [GeForce GT 520]                                                     | 1        | 1.79%   |
| Nvidia GF110 [GeForce GTX 560 Ti 448 Cores]                                       | 1        | 1.79%   |
| Nvidia GF108 [GeForce GT 430]                                                     | 1        | 1.79%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                    | 1        | 1.79%   |
| Nvidia GA106 [Geforce RTX 3050]                                                   | 1        | 1.79%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                                | 1        | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller       | 1        | 1.79%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                         | 1        | 1.79%   |
| Intel HD Graphics 630                                                             | 1        | 1.79%   |
| Intel HD Graphics 500                                                             | 1        | 1.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller         | 1        | 1.79%   |
| AMD RV620 LE [Radeon HD 3450]                                                     | 1        | 1.79%   |
| AMD RV370 [Radeon X300]                                                           | 1        | 1.79%   |
| AMD RV370 [Radeon X300 SE]                                                        | 1        | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]              | 1        | 1.79%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]             | 1        | 1.79%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                     | 1        | 1.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                           | 1        | 1.79%   |
| AMD Kaveri [Radeon R7 Graphics]                                                   | 1        | 1.79%   |
| AMD Cape Verde PRO / Venus LE / Tropo PRO-L [Radeon HD 8830M / R7 250 / R7 M465X] | 1        | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 22       | 44%     |
| 1 x Nvidia      | 18       | 36%     |
| 1 x Intel       | 3        | 6%      |
| 2 x AMD         | 2        | 4%      |
| AMD + Nvidia    | 2        | 4%      |
| 1 x S3 Graphics | 1        | 2%      |
| Intel + Nvidia  | 1        | 2%      |
| Intel + AMD     | 1        | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 36       | 72%     |
| Proprietary | 13       | 26%     |
| Unknown     | 1        | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 42%     |
| 0.01-0.5   | 10       | 20%     |
| 1.01-2.0   | 7        | 14%     |
| 3.01-4.0   | 5        | 10%     |
| 7.01-8.0   | 3        | 6%      |
| 8.01-16.0  | 2        | 4%      |
| 0.51-1.0   | 2        | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 15.09%  |
| Dell                 | 8        | 15.09%  |
| Fujitsu Siemens      | 7        | 13.21%  |
| Goldstar             | 5        | 9.43%   |
| Iiyama               | 3        | 5.66%   |
| Hewlett-Packard      | 3        | 5.66%   |
| AOC                  | 3        | 5.66%   |
| Ancor Communications | 3        | 5.66%   |
| Acer                 | 3        | 5.66%   |
| ViewSonic            | 1        | 1.89%   |
| Unknown              | 1        | 1.89%   |
| Philips              | 1        | 1.89%   |
| LG Electronics       | 1        | 1.89%   |
| Lenovo               | 1        | 1.89%   |
| Hitachi              | 1        | 1.89%   |
| HannStar             | 1        | 1.89%   |
| Gigabyte Technology  | 1        | 1.89%   |
| BenQ                 | 1        | 1.89%   |
| ASUSTek Computer     | 1        | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch           | 6        | 10.91%  |
| ViewSonic EP3220T VSC33F3 1920x1080 700x390mm 31.5-inch               | 1        | 1.82%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1        | 1.82%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 1.82%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch  | 1        | 1.82%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1        | 1.82%   |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch   | 1        | 1.82%   |
| Samsung Electronics S27E450 SAM0C83 1920x1080 598x336mm 27.0-inch     | 1        | 1.82%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1        | 1.82%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 697x392mm 31.5-inch     | 1        | 1.82%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1.82%   |
| Philips 190X PHL084C 1280x1024 376x301mm 19.0-inch                    | 1        | 1.82%   |
| LG Electronics LCD Monitor E2260 1920x1080                            | 1        | 1.82%   |
| Lenovo LCD Monitor LEN1144 1920x1080 518x324mm 24.1-inch              | 1        | 1.82%   |
| Iiyama PL2592H IVM6135 1920x1080 544x303mm 24.5-inch                  | 1        | 1.82%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1        | 1.82%   |
| Iiyama PL2274HD IVM5619 1920x1080 477x268mm 21.5-inch                 | 1        | 1.82%   |
| Hitachi X90W D-sub HIT6008 1440x900 410x257mm 19.1-inch               | 1        | 1.82%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch          | 1        | 1.82%   |
| Hewlett-Packard L1740 HWP2649 1280x1024 338x270mm 17.0-inch           | 1        | 1.82%   |
| Hewlett-Packard E231 HWP3065 1920x1080 509x286mm 23.0-inch            | 1        | 1.82%   |
| HannStar HH251 HSD2211 1920x1080 543x305mm 24.5-inch                  | 1        | 1.82%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                  | 1        | 1.82%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 1        | 1.82%   |
| Goldstar M2380D GSM57BC 1920x1080 598x336mm 27.0-inch                 | 1        | 1.82%   |
| Goldstar L227W GSM566E 1680x1050 474x296mm 22.0-inch                  | 1        | 1.82%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1        | 1.82%   |
| Goldstar 27MB85R GSM5A8B 2560x1440 597x336mm 27.0-inch                | 1        | 1.82%   |
| Gigabyte Technology AORUS CV27Q GBT2705 2560x1440 596x335mm 26.9-inch | 1        | 1.82%   |
| Fujitsu Siemens B19-5G ECO FUS07C0 1280x1024 376x301mm 19.0-inch      | 1        | 1.82%   |
| Dell U3417W DELA0DD 3440x1440 800x335mm 34.1-inch                     | 1        | 1.82%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 1        | 1.82%   |
| Dell U2713HM DEL407E 2560x1440 597x336mm 27.0-inch                    | 1        | 1.82%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 1        | 1.82%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1        | 1.82%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                     | 1        | 1.82%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                      | 1        | 1.82%   |
| Dell DELL3007WFPHC DEL4016 2560x1600 646x406mm 30.0-inch              | 1        | 1.82%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                  | 1        | 1.82%   |
| ASUSTek Computer ROG PG278QR AUS27B1 2560x1440 598x336mm 27.0-inch    | 1        | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 35.29%  |
| 2560x1440 (QHD)    | 10       | 19.61%  |
| 1280x1024 (SXGA)   | 10       | 19.61%  |
| 1680x1050 (WSXGA+) | 3        | 5.88%   |
| 1366x768 (WXGA)    | 3        | 5.88%   |
| 1440x900 (WXGA+)   | 2        | 3.92%   |
| 3840x2160 (4K)     | 1        | 1.96%   |
| 3440x1440          | 1        | 1.96%   |
| 2560x1600          | 1        | 1.96%   |
| 1920x1200 (WUXGA)  | 1        | 1.96%   |
| 1600x900 (HD+)     | 1        | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 10       | 18.87%  |
| 27      | 9        | 16.98%  |
| 24      | 7        | 13.21%  |
| 23      | 6        | 11.32%  |
| 31      | 4        | 7.55%   |
| 21      | 3        | 5.66%   |
| 22      | 2        | 3.77%   |
| 18      | 2        | 3.77%   |
| 17      | 2        | 3.77%   |
| 54      | 1        | 1.89%   |
| 34      | 1        | 1.89%   |
| 32      | 1        | 1.89%   |
| 30      | 1        | 1.89%   |
| 26      | 1        | 1.89%   |
| 20      | 1        | 1.89%   |
| 15      | 1        | 1.89%   |
| Unknown | 1        | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 36.54%  |
| 401-500     | 11       | 21.15%  |
| 351-400     | 9        | 17.31%  |
| 601-700     | 6        | 11.54%  |
| 301-350     | 3        | 5.77%   |
| 701-800     | 2        | 3.85%   |
| 1001-1500   | 1        | 1.92%   |
| Unknown     | 1        | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 28       | 58.33%  |
| 5/4     | 9        | 18.75%  |
| 16/10   | 7        | 14.58%  |
| 6/5     | 1        | 2.08%   |
| 3/2     | 1        | 2.08%   |
| 21/9    | 1        | 2.08%   |
| Unknown | 1        | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 24.53%  |
| 151-200        | 12       | 22.64%  |
| 301-350        | 10       | 18.87%  |
| 351-500        | 7        | 13.21%  |
| 251-300        | 4        | 7.55%   |
| 141-150        | 4        | 7.55%   |
| More than 1000 | 1        | 1.89%   |
| 101-110        | 1        | 1.89%   |
| Unknown        | 1        | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 70%     |
| 101-120 | 12       | 24%     |
| 1-50    | 1        | 2%      |
| 121-160 | 1        | 2%      |
| Unknown | 1        | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41       | 82%     |
| 2     | 6        | 12%     |
| 0     | 2        | 4%      |
| 3     | 1        | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 32       | 45.71%  |
| Intel                    | 23       | 32.86%  |
| Qualcomm Atheros         | 2        | 2.86%   |
| MediaTek                 | 2        | 2.86%   |
| Broadcom                 | 2        | 2.86%   |
| TP-Link                  | 1        | 1.43%   |
| Ralink Technology        | 1        | 1.43%   |
| Ralink                   | 1        | 1.43%   |
| NetGear                  | 1        | 1.43%   |
| Microchip Technology     | 1        | 1.43%   |
| Marvell Technology Group | 1        | 1.43%   |
| JMicron Technology       | 1        | 1.43%   |
| Atmel                    | 1        | 1.43%   |
| Aquantia                 | 1        | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 32.47%  |
| Intel Ethernet Controller I225-V                                  | 4        | 5.19%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 3.9%    |
| Intel I211 Gigabit Network Connection                             | 3        | 3.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 2.6%    |
| Intel 82583V Gigabit Network Connection                           | 2        | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.6%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.3%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 1.3%    |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.3%    |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.3%    |
| NetGear A6150                                                     | 1        | 1.3%    |
| Microchip SPROG 3 DCC Programmer                                  | 1        | 1.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1        | 1.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.3%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.3%    |
| Intel Wireless-AC 9260                                            | 1        | 1.3%    |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.3%    |
| Intel I350 Gigabit Network Connection                             | 1        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.3%    |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.3%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.3%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.3%    |
| Intel 82566DC Gigabit Network Connection                          | 1        | 1.3%    |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 1.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.3%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 40%     |
| Realtek Semiconductor | 5        | 25%     |
| MediaTek              | 2        | 10%     |
| TP-Link               | 1        | 5%      |
| Ralink Technology     | 1        | 5%      |
| Ralink                | 1        | 5%      |
| Qualcomm Atheros      | 1        | 5%      |
| NetGear               | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 3        | 15%     |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2        | 10%     |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1        | 5%      |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1        | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1        | 5%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1        | 5%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1        | 5%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 5%      |
| Ralink MT7601U Wireless Adapter                               | 1        | 5%      |
| Ralink RT5392 PCIe Wireless Network Adapter                   | 1        | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1        | 5%      |
| NetGear A6150                                                 | 1        | 5%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 5%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1        | 5%      |
| Intel Wireless-AC 9260                                        | 1        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1        | 5%      |
| Intel Comet Lake PCH CNVi WiFi                                | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 29       | 53.7%   |
| Intel                    | 19       | 35.19%  |
| Broadcom                 | 2        | 3.7%    |
| Qualcomm Atheros         | 1        | 1.85%   |
| Marvell Technology Group | 1        | 1.85%   |
| JMicron Technology       | 1        | 1.85%   |
| Aquantia                 | 1        | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 25       | 45.45%  |
| Intel Ethernet Controller I225-V                                    | 4        | 7.27%   |
| Intel I211 Gigabit Network Connection                               | 3        | 5.45%   |
| Realtek RTL8125 2.5GbE Controller                                   | 2        | 3.64%   |
| Intel 82583V Gigabit Network Connection                             | 2        | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 2        | 3.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 1.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 1.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 1.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller              | 1        | 1.82%   |
| Intel NM10/ICH7 Family LAN Controller                               | 1        | 1.82%   |
| Intel I350 Gigabit Network Connection                               | 1        | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 1.82%   |
| Intel Ethernet Connection (2) I218-LM                               | 1        | 1.82%   |
| Intel Ethernet Connection (11) I219-V                               | 1        | 1.82%   |
| Intel 82578DM Gigabit Network Connection                            | 1        | 1.82%   |
| Intel 82566DC Gigabit Network Connection                            | 1        | 1.82%   |
| Intel 82541PI Gigabit Ethernet Controller                           | 1        | 1.82%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 1        | 1.82%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                    | 1        | 1.82%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 71.01%  |
| WiFi     | 19       | 27.54%  |
| Modem    | 1        | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 94%     |
| WiFi     | 3        | 6%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 56%     |
| 2     | 17       | 34%     |
| 3     | 3        | 6%      |
| 4     | 1        | 2%      |
| 0     | 1        | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 66.67%  |
| Yes  | 17       | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 36.36%  |
| Cambridge Silicon Radio         | 5        | 22.73%  |
| Realtek Semiconductor           | 3        | 13.64%  |
| Qualcomm Atheros Communications | 1        | 4.55%   |
| MediaTek                        | 1        | 4.55%   |
| IMC Networks                    | 1        | 4.55%   |
| Broadcom                        | 1        | 4.55%   |
| Belkin Components               | 1        | 4.55%   |
| ASUSTek Computer                | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 22.73%  |
| Intel AX200 Bluetooth                                 | 3        | 13.64%  |
| Realtek Bluetooth Radio                               | 2        | 9.09%   |
| Intel AX210 Bluetooth                                 | 2        | 9.09%   |
| Realtek RTL8821A Bluetooth                            | 1        | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 4.55%   |
| MediaTek Wireless_Device                              | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 4.55%   |
| Intel AX201 Bluetooth                                 | 1        | 4.55%   |
| IMC Networks Wireless_Device                          | 1        | 4.55%   |
| Broadcom Bluetooth Controller                         | 1        | 4.55%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 4.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 32       | 35.96%  |
| Intel                       | 22       | 24.72%  |
| Nvidia                      | 21       | 23.6%   |
| C-Media Electronics         | 4        | 4.49%   |
| Creative Labs               | 3        | 3.37%   |
| Texas Instruments           | 1        | 1.12%   |
| Microsoft                   | 1        | 1.12%   |
| JMTek                       | 1        | 1.12%   |
| GN Netcom                   | 1        | 1.12%   |
| FiiO Electronics Technology | 1        | 1.12%   |
| Ensoniq                     | 1        | 1.12%   |
| ASUSTek Computer            | 1        | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 6.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 6.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 5.36%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 4.46%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 4.46%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 2.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 2.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 2.68%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 2.68%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.79%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 2        | 1.79%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 2        | 1.79%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2        | 1.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.79%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.89%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.89%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia Audio device                                                        | 1        | 0.89%   |
| Microsoft USB Link                                                         | 1        | 0.89%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Kingston          | 11       | 35.48%  |
| Unknown           | 5        | 16.13%  |
| Corsair           | 5        | 16.13%  |
| G.Skill           | 3        | 9.68%   |
| SK hynix          | 2        | 6.45%   |
| TakeMS            | 1        | 3.23%   |
| Micron Technology | 1        | 3.23%   |
| CSX               | 1        | 3.23%   |
| Avant             | 1        | 3.23%   |
| Unknown           | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s     | 3        | 9.09%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2        | 6.06%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                | 1        | 3.03%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 3.03%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 3.03%   |
| TakeMS RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 3.03%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 3.03%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s      | 1        | 3.03%   |
| SK hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s     | 1        | 3.03%   |
| Micron RAM 16ATF2G64AZ-2G1A1 16GB DIMM DDR4 2133MT/s      | 1        | 3.03%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 3.03%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s            | 1        | 3.03%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 3.03%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 3.03%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 1        | 3.03%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 1        | 3.03%   |
| Kingston RAM 9965684-009.A00G 8GB DIMM DDR4 2133MT/s      | 1        | 3.03%   |
| Kingston RAM 9965669-023.A00G 8GB DIMM DDR4 2133MT/s      | 1        | 3.03%   |
| Kingston RAM 9905471-061.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 3.03%   |
| G.Skill RAM F4-3600C14-16GTZNA 16384MB DIMM DDR4 2133MT/s | 1        | 3.03%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s      | 1        | 3.03%   |
| G.Skill RAM F4-3200C15-16GTZKY 16384MB DIMM DDR4 3200MT/s | 1        | 3.03%   |
| CSX RAM V01D2LF1GB18864867 1GB DIMM DDR 533MT/s           | 1        | 3.03%   |
| Corsair RAM CMW32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s     | 1        | 3.03%   |
| Corsair RAM CML16GX3M2A1600C9 8192MB DIMM DDR3 2133MT/s   | 1        | 3.03%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s    | 1        | 3.03%   |
| Corsair RAM CMK32GX5M2B6400C32 16GB DIMM DDR5 4800MT/s    | 1        | 3.03%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3200MT/s    | 1        | 3.03%   |
| Avant RAM F641GU67F9333G 8192MB DIMM DDR3 1333MT/s        | 1        | 3.03%   |
| Unknown                                                   | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 14       | 50%     |
| DDR3    | 6        | 21.43%  |
| Unknown | 4        | 14.29%  |
| DDR2    | 2        | 7.14%   |
| DDR5    | 1        | 3.57%   |
| DDR     | 1        | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 27       | 96.43%  |
| SODIMM | 1        | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 9        | 31.03%  |
| 8192  | 7        | 24.14%  |
| 4096  | 5        | 17.24%  |
| 32768 | 4        | 13.79%  |
| 2048  | 3        | 10.34%  |
| 1024  | 1        | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 5        | 17.24%  |
| 2133  | 5        | 17.24%  |
| 1600  | 4        | 13.79%  |
| 1333  | 4        | 13.79%  |
| 3933  | 3        | 10.34%  |
| 3600  | 2        | 6.9%    |
| 800   | 2        | 6.9%    |
| 4800  | 1        | 3.45%   |
| 2667  | 1        | 3.45%   |
| 2400  | 1        | 3.45%   |
| 533   | 1        | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 50%     |
| Samsung Electronics | 1        | 25%     |
| Hewlett-Packard     | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 1        | 25%     |
| HP Color LaserJet CP1215              | 1        | 25%     |
| Brother Printer                       | 1        | 25%     |
| Brother HL-4150CDN series             | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Seiko Epson    | 1        | 50%     |
| Mustek Systems | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 50%     |
| Mustek Systems ScanExpress A3 USB                             | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 4        | 40%     |
| Microdia            | 2        | 20%     |
| Microsoft           | 1        | 10%     |
| Huawei Technologies | 1        | 10%     |
| ARC International   | 1        | 10%     |
| 2M UVC CAMERA       | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microsoft LifeCam VX-700            | 1        | 10%     |
| Microdia USB 2.0 Camera             | 1        | 10%     |
| Microdia Camera                     | 1        | 10%     |
| Logitech Webcam C270                | 1        | 10%     |
| Logitech Webcam C170                | 1        | 10%     |
| Logitech HD Pro Webcam C920         | 1        | 10%     |
| Logitech BRIO Ultra HD Webcam       | 1        | 10%     |
| Huawei HiCamera                     | 1        | 10%     |
| ARC International Camera            | 1        | 10%     |
| 2M UVC CAMERA NexiGo N60 FHD Webcam | 1        | 10%     |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 42       | 84%     |
| 1     | 6        | 12%     |
| 3     | 1        | 2%      |
| 2     | 1        | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 3        | 27.27%  |
| Graphics card            | 3        | 27.27%  |
| Unassigned class         | 1        | 9.09%   |
| Multimedia controller    | 1        | 9.09%   |
| Communication controller | 1        | 9.09%   |
| Chipcard                 | 1        | 9.09%   |
| Card reader              | 1        | 9.09%   |

