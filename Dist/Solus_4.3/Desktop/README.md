Solus 4.3 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

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

Total: 49

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| HP         | 2B47                        | [8980bff4e8](https://linux-hardware.org/?probe=8980bff4e8) | Dec 21, 2022 |
| ASUSTek    | P5G41T-M LX3                | [7d42818fc5](https://linux-hardware.org/?probe=7d42818fc5) | Dec 06, 2022 |
| Intel      | D946GZIS AAD66165-302       | [ef34a2a126](https://linux-hardware.org/?probe=ef34a2a126) | Nov 16, 2022 |
| ASRock     | X570M Pro4                  | [087a173c0d](https://linux-hardware.org/?probe=087a173c0d) | Oct 08, 2022 |
| Unknown    | TB-4000                     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| Unknown    | TB-4000                     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Unknown    | TB-4000                     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| Lenovo     | CRESCENTBAY 31900058 STD    | [f42a689093](https://linux-hardware.org/?probe=f42a689093) | Jun 10, 2022 |
| Gigabyte   | Z68AP-D3                    | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| ASUSTek    | B85M-E                      | [31572b098d](https://linux-hardware.org/?probe=31572b098d) | Apr 24, 2022 |
| ASUSTek    | B85M-E                      | [037b7180fd](https://linux-hardware.org/?probe=037b7180fd) | Apr 23, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [8e0d54760d](https://linux-hardware.org/?probe=8e0d54760d) | Apr 22, 2022 |
| MSI        | B450M MORTAR                | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Gigabyte   | F2A68HM-H                   | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Fujitsu    | D3227-A1 S26361-D3227-A1    | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Gigabyte   | GA-MA770-UD3                | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| Unknown    | HX90                        | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| Unknown    | HX90                        | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| Unknown    | HX90                        | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| ASUSTek    | A88X-PRO                    | [fb6f0426c3](https://linux-hardware.org/?probe=fb6f0426c3) | Jan 20, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Dell       | 06X1TJ A00                  | [315e535dd5](https://linux-hardware.org/?probe=315e535dd5) | Dec 21, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [d65256bf72](https://linux-hardware.org/?probe=d65256bf72) | Dec 12, 2021 |
| Gigabyte   | H110M-DS2V-CF               | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte   | H110M-DS2V-CF               | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MEGA       | G41T-M7 LGT                 | [7238b4cd22](https://linux-hardware.org/?probe=7238b4cd22) | Nov 21, 2021 |
| Gigabyte   | B85M-D3H                    | [7119b7f25b](https://linux-hardware.org/?probe=7119b7f25b) | Nov 19, 2021 |
| MSI        | B350 TOMAHAWK ARCTIC        | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| ASRock     | X470 Master SLI             | [7058d85808](https://linux-hardware.org/?probe=7058d85808) | Nov 11, 2021 |
| HP         | 805F                        | [f7bfb95642](https://linux-hardware.org/?probe=f7bfb95642) | Oct 26, 2021 |
| LattePanda | Alpha                       | [cfe529288b](https://linux-hardware.org/?probe=cfe529288b) | Oct 26, 2021 |
| Biostar    | H61MLV2                     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| Gigabyte   | GA-78LMT-USB3               | [99c69c213a](https://linux-hardware.org/?probe=99c69c213a) | Sep 05, 2021 |
| ASUSTek    | TUF B450-PRO GAMING         | [f7d38e2f91](https://linux-hardware.org/?probe=f7d38e2f91) | Aug 29, 2021 |
| Gigabyte   | P31-ES3G                    | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte   | P31-ES3G                    | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| eMachines  | EL1852G                     | [7683cbf5bb](https://linux-hardware.org/?probe=7683cbf5bb) | Aug 16, 2021 |
| eMachines  | EL1852G                     | [86003fc5b7](https://linux-hardware.org/?probe=86003fc5b7) | Aug 15, 2021 |
| Gigabyte   | H81M-S2V                    | [16b2e8c32f](https://linux-hardware.org/?probe=16b2e8c32f) | Aug 06, 2021 |
| Gigabyte   | H81M-S2V                    | [db8fadad17](https://linux-hardware.org/?probe=db8fadad17) | Aug 06, 2021 |
| MSI        | B450 GAMING PRO CARBON A... | [b6ae0cb479](https://linux-hardware.org/?probe=b6ae0cb479) | Aug 05, 2021 |
| Gigabyte   | B360M AORUS Gaming 3-CF     | [fc89bec579](https://linux-hardware.org/?probe=fc89bec579) | Jul 16, 2021 |
| Lenovo     | ThinkCentre M71e 3157G6S    | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.15.32-213.current | 5        | 14.71%  |
| 5.14.21-210.current | 4        | 11.76%  |
| 5.14.16-205.current | 4        | 11.76%  |
| 5.13.12-193.current | 3        | 8.82%   |
| 6.0.11-225.current  | 2        | 5.88%   |
| 5.15.50-216.current | 2        | 5.88%   |
| 5.15.43-215.current | 2        | 5.88%   |
| 5.15.30-212.current | 2        | 5.88%   |
| 5.14.14-202.current | 2        | 5.88%   |
| 5.13.6-190.current  | 2        | 5.88%   |
| 5.13.1-187.current  | 2        | 5.88%   |
| 5.15.77-219.current | 1        | 2.94%   |
| 5.15.68-218.current | 1        | 2.94%   |
| 5.15.26-211.current | 1        | 2.94%   |
| 5.13.8-191.current  | 1        | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.32 | 5        | 14.71%  |
| 5.14.21 | 4        | 11.76%  |
| 5.14.16 | 4        | 11.76%  |
| 5.13.12 | 3        | 8.82%   |
| 6.0.11  | 2        | 5.88%   |
| 5.15.50 | 2        | 5.88%   |
| 5.15.43 | 2        | 5.88%   |
| 5.15.30 | 2        | 5.88%   |
| 5.14.14 | 2        | 5.88%   |
| 5.13.6  | 2        | 5.88%   |
| 5.13.1  | 2        | 5.88%   |
| 5.15.77 | 1        | 2.94%   |
| 5.15.68 | 1        | 2.94%   |
| 5.15.26 | 1        | 2.94%   |
| 5.13.8  | 1        | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 13       | 39.39%  |
| 5.14    | 10       | 30.3%   |
| 5.13    | 8        | 24.24%  |
| 6.0     | 2        | 6.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 32       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Budgie  | 23       | 71.88%  |
| GNOME   | 3        | 9.38%   |
| MATE    | 2        | 6.25%   |
| KDE5    | 2        | 6.25%   |
| KDE     | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 31       | 96.88%  |
| Wayland | 1        | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 75%     |
| LightDM | 6        | 18.75%  |
| SDDM    | 2        | 6.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 48.48%  |
| es_ES | 3        | 9.09%   |
| ru_RU | 2        | 6.06%   |
| fr_FR | 2        | 6.06%   |
| en_GB | 2        | 6.06%   |
| de_DE | 2        | 6.06%   |
| pt_BR | 1        | 3.03%   |
| nl_NL | 1        | 3.03%   |
| es_VE | 1        | 3.03%   |
| en_DK | 1        | 3.03%   |
| ar_SA | 1        | 3.03%   |
| ar_EG | 1        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 56.25%  |
| EFI  | 14       | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 30       | 93.75%  |
| Xfs   | 1        | 3.13%   |
| Btrfs | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 81.25%  |
| MBR     | 3        | 9.38%   |
| GPT     | 3        | 9.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 87.88%  |
| Yes       | 4        | 12.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 84.38%  |
| Yes       | 5        | 15.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 25%     |
| ASUSTek Computer    | 6        | 18.75%  |
| MSI                 | 3        | 9.38%   |
| ASRock              | 3        | 9.38%   |
| Lenovo              | 2        | 6.25%   |
| Hewlett-Packard     | 2        | 6.25%   |
| Unknown             | 2        | 6.25%   |
| MEGA                | 1        | 3.13%   |
| Intel               | 1        | 3.13%   |
| Fujitsu             | 1        | 3.13%   |
| eMachines           | 1        | 3.13%   |
| Dell                | 1        | 3.13%   |
| Biostar             | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 2        | 6.25%   |
| MSI MS-7B89                      | 1        | 3.13%   |
| MSI MS-7B85                      | 1        | 3.13%   |
| MSI MS-7A34                      | 1        | 3.13%   |
| MEGA G41T-M7 LGT                 | 1        | 3.13%   |
| Lenovo ThinkCentre M71e 3157G6S  | 1        | 3.13%   |
| Lenovo C50-30 F0B1002EFR         | 1        | 3.13%   |
| Intel D946GZIS AAD66165-302      | 1        | 3.13%   |
| HP ProDesk 490 G3 MT Business PC | 1        | 3.13%   |
| HP 750-171                       | 1        | 3.13%   |
| Gigabyte Z68AP-D3                | 1        | 3.13%   |
| Gigabyte P31-ES3G                | 1        | 3.13%   |
| Gigabyte H81M-S2V                | 1        | 3.13%   |
| Gigabyte H110M-DS2V              | 1        | 3.13%   |
| Gigabyte GA-MA770-UD3            | 1        | 3.13%   |
| Gigabyte GA-78LMT-USB3 6.0       | 1        | 3.13%   |
| Gigabyte F2A68HM-H               | 1        | 3.13%   |
| Gigabyte B85M-D3H                | 1        | 3.13%   |
| Fujitsu CELSIUS W530             | 1        | 3.13%   |
| eMachines EL1852G                | 1        | 3.13%   |
| Dell OptiPlex 9020               | 1        | 3.13%   |
| Biostar H61MLV2                  | 1        | 3.13%   |
| ASUS TUF Gaming X570-PRO         | 1        | 3.13%   |
| ASUS TUF B450-PRO GAMING         | 1        | 3.13%   |
| ASUS ROG STRIX B450-F GAMING     | 1        | 3.13%   |
| ASUS P5G41T-M LX3                | 1        | 3.13%   |
| ASUS All Series                  | 1        | 3.13%   |
| ASUS A88X-PRO                    | 1        | 3.13%   |
| ASRock X570M Pro4                | 1        | 3.13%   |
| ASRock H81 Pro BTC R2.0          | 1        | 3.13%   |
| ASRock B450 Gaming-ITX/ac        | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS TUF               | 2        | 6.25%   |
| Unknown                | 2        | 6.25%   |
| MSI MS-7B89            | 1        | 3.13%   |
| MSI MS-7B85            | 1        | 3.13%   |
| MSI MS-7A34            | 1        | 3.13%   |
| MEGA G41T-M7           | 1        | 3.13%   |
| Lenovo ThinkCentre     | 1        | 3.13%   |
| Lenovo C50-30          | 1        | 3.13%   |
| Intel D946GZIS         | 1        | 3.13%   |
| HP ProDesk             | 1        | 3.13%   |
| HP 750-171             | 1        | 3.13%   |
| Gigabyte Z68AP-D3      | 1        | 3.13%   |
| Gigabyte P31-ES3G      | 1        | 3.13%   |
| Gigabyte H81M-S2V      | 1        | 3.13%   |
| Gigabyte H110M-DS2V    | 1        | 3.13%   |
| Gigabyte GA-MA770-UD3  | 1        | 3.13%   |
| Gigabyte GA-78LMT-USB3 | 1        | 3.13%   |
| Gigabyte F2A68HM-H     | 1        | 3.13%   |
| Gigabyte B85M-D3H      | 1        | 3.13%   |
| Fujitsu CELSIUS        | 1        | 3.13%   |
| eMachines EL1852G      | 1        | 3.13%   |
| Dell OptiPlex          | 1        | 3.13%   |
| Biostar H61MLV2        | 1        | 3.13%   |
| ASUS ROG               | 1        | 3.13%   |
| ASUS P5G41T-M          | 1        | 3.13%   |
| ASUS All               | 1        | 3.13%   |
| ASUS A88X-PRO          | 1        | 3.13%   |
| ASRock X570M           | 1        | 3.13%   |
| ASRock H81             | 1        | 3.13%   |
| ASRock B450            | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 6        | 18.75%  |
| 2014 | 5        | 15.63%  |
| 2011 | 4        | 12.5%   |
| 2015 | 3        | 9.38%   |
| 2021 | 2        | 6.25%   |
| 2016 | 2        | 6.25%   |
| 2013 | 2        | 6.25%   |
| 2008 | 2        | 6.25%   |
| 2020 | 1        | 3.13%   |
| 2019 | 1        | 3.13%   |
| 2017 | 1        | 3.13%   |
| 2012 | 1        | 3.13%   |
| 2010 | 1        | 3.13%   |
| 2006 | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 32       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 9        | 28.13%  |
| 3.01-4.0   | 8        | 25%     |
| 8.01-16.0  | 7        | 21.88%  |
| 32.01-64.0 | 4        | 12.5%   |
| 4.01-8.0   | 3        | 9.38%   |
| 2.01-3.0   | 1        | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 14       | 41.18%  |
| 2.01-3.0  | 7        | 20.59%  |
| 4.01-8.0  | 6        | 17.65%  |
| 3.01-4.0  | 5        | 14.71%  |
| 8.01-16.0 | 1        | 2.94%   |
| 0.51-1.0  | 1        | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 32.35%  |
| 2      | 9        | 26.47%  |
| 4      | 8        | 23.53%  |
| 3      | 4        | 11.76%  |
| 5      | 2        | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 53.13%  |
| Yes       | 15       | 46.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 53.13%  |
| Yes       | 15       | 46.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 59.38%  |
| Yes       | 13       | 40.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 7        | 21.88%  |
| Germany      | 4        | 12.5%   |
| Argentina    | 2        | 6.25%   |
| Venezuela    | 1        | 3.13%   |
| Thailand     | 1        | 3.13%   |
| Sweden       | 1        | 3.13%   |
| Spain        | 1        | 3.13%   |
| Saudi Arabia | 1        | 3.13%   |
| Russia       | 1        | 3.13%   |
| Philippines  | 1        | 3.13%   |
| Norway       | 1        | 3.13%   |
| Netherlands  | 1        | 3.13%   |
| Kazakhstan   | 1        | 3.13%   |
| Iran         | 1        | 3.13%   |
| India        | 1        | 3.13%   |
| Guyana       | 1        | 3.13%   |
| Greece       | 1        | 3.13%   |
| France       | 1        | 3.13%   |
| Denmark      | 1        | 3.13%   |
| Canada       | 1        | 3.13%   |
| Brazil       | 1        | 3.13%   |
| Albania      | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Weil am Rhein   | 1        | 3.03%   |
| Viby J          | 1        | 3.03%   |
| Toronto         | 1        | 3.03%   |
| Thessaloniki    | 1        | 3.03%   |
| Stockholm       | 1        | 3.03%   |
| Songkhla        | 1        | 3.03%   |
| Seville         | 1        | 3.03%   |
| Severna Park    | 1        | 3.03%   |
| San Justo       | 1        | 3.03%   |
| Portsmouth      | 1        | 3.03%   |
| Phoenix         | 1        | 3.03%   |
| Oslo            | 1        | 3.03%   |
| Orenburg        | 1        | 3.03%   |
| Ochten          | 1        | 3.03%   |
| Lipa City       | 1        | 3.03%   |
| Lexington       | 1        | 3.03%   |
| Krefeld         | 1        | 3.03%   |
| Kolkata         | 1        | 3.03%   |
| Khobar          | 1        | 3.03%   |
| Isidro Casanova | 1        | 3.03%   |
| Huntington Park | 1        | 3.03%   |
| Hamburg         | 1        | 3.03%   |
| Great Neck      | 1        | 3.03%   |
| Georgetown      | 1        | 3.03%   |
| Garland         | 1        | 3.03%   |
| Durrës         | 1        | 3.03%   |
| Dammam          | 1        | 3.03%   |
| Curitiba        | 1        | 3.03%   |
| Caracas         | 1        | 3.03%   |
| Caen            | 1        | 3.03%   |
| Bad Homburg     | 1        | 3.03%   |
| Atyrau          | 1        | 3.03%   |
| Arak            | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 25     | 26.87%  |
| Samsung Electronics | 13       | 18     | 19.4%   |
| Seagate             | 7        | 7      | 10.45%  |
| Kingston            | 7        | 10     | 10.45%  |
| Crucial             | 4        | 4      | 5.97%   |
| Toshiba             | 3        | 3      | 4.48%   |
| SanDisk             | 3        | 3      | 4.48%   |
| PNY                 | 2        | 2      | 2.99%   |
| Hitachi             | 2        | 2      | 2.99%   |
| Unknown             | 1        | 1      | 1.49%   |
| SPCC Sol            | 1        | 1      | 1.49%   |
| Phison              | 1        | 1      | 1.49%   |
| Micron Technology   | 1        | 1      | 1.49%   |
| Maxtor              | 1        | 1      | 1.49%   |
| Intenso             | 1        | 2      | 1.49%   |
| HFS512GD            | 1        | 1      | 1.49%   |
| China               | 1        | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB        | 3        | 3.95%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 3.95%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 2.63%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 2.63%   |
| Toshiba DT01ACA050 500GB         | 2        | 2.63%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 2.63%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 2.63%   |
| Crucial CT1000P1SSD8 1TB         | 2        | 2.63%   |
| Crucial CT1000MX500SSD1 1TB      | 2        | 2.63%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD | 1        | 1.32%   |
| WDC WD6400AAKS-75A7B2 640GB      | 1        | 1.32%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 1.32%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 1.32%   |
| WDC WD5000AAKX-003CA0 500GB      | 1        | 1.32%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 1.32%   |
| WDC WD3200AAJS-00YZCA0 320GB     | 1        | 1.32%   |
| WDC WD32 00AAJS-00L7A0 320GB     | 1        | 1.32%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1        | 1.32%   |
| WDC WD2500HHTZ-04N21V1 250GB     | 1        | 1.32%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1        | 1.32%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1        | 1.32%   |
| WDC WD1600AAJS-00PSA0 160GB      | 1        | 1.32%   |
| WDC WD1600AAJS-00M0A0 160GB      | 1        | 1.32%   |
| WDC WD140EFGX-68B0GN0 14TB       | 1        | 1.32%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1        | 1.32%   |
| WDC WD10EADS-00P8B0 1TB          | 1        | 1.32%   |
| WDC WD10EADS-00M2B0 1TB          | 1        | 1.32%   |
| WDC WD1003FBYX-01Y7B0 1TB        | 1        | 1.32%   |
| WDC WD My Passport 25F3 512GB    | 1        | 1.32%   |
| Unknown SD/MMC/MS PRO 64GB       | 1        | 1.32%   |
| Toshiba DT01ACA100 1TB           | 1        | 1.32%   |
| SPCC Sol id State Disk 64GB SSD  | 1        | 1.32%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 1.32%   |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 1.32%   |
| Seagate ST3320418AS 320GB        | 1        | 1.32%   |
| Seagate ST31000528AS 1TB         | 1        | 1.32%   |
| Seagate ST2000LM007-1R8174 2TB   | 1        | 1.32%   |
| Seagate ST2000DM006-2DM164 2TB   | 1        | 1.32%   |
| Seagate ST2000DM005-2CW102 2TB   | 1        | 1.32%   |
| SanDisk SDSSDP064G 64GB          | 1        | 1.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 23     | 51.52%  |
| Seagate             | 7        | 7      | 21.21%  |
| Toshiba             | 3        | 3      | 9.09%   |
| Hitachi             | 2        | 2      | 6.06%   |
| Unknown             | 1        | 1      | 3.03%   |
| Samsung Electronics | 1        | 1      | 3.03%   |
| Maxtor              | 1        | 1      | 3.03%   |
| Intenso             | 1        | 2      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 14     | 42.31%  |
| Kingston            | 5        | 8      | 19.23%  |
| SanDisk             | 2        | 2      | 7.69%   |
| PNY                 | 2        | 2      | 7.69%   |
| Crucial             | 2        | 2      | 7.69%   |
| WDC                 | 1        | 1      | 3.85%   |
| SPCC Sol            | 1        | 1      | 3.85%   |
| Micron Technology   | 1        | 1      | 3.85%   |
| China               | 1        | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 26       | 40     | 47.27%  |
| SSD     | 18       | 32     | 32.73%  |
| NVMe    | 9        | 9      | 16.36%  |
| Unknown | 2        | 2      | 3.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 67     | 69.77%  |
| NVMe | 9        | 9      | 20.93%  |
| SAS  | 4        | 7      | 9.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 46     | 52.17%  |
| 0.51-1.0   | 13       | 17     | 28.26%  |
| 1.01-2.0   | 6        | 6      | 13.04%  |
| 3.01-4.0   | 2        | 2      | 4.35%   |
| 10.01-20.0 | 1        | 1      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 9        | 27.27%  |
| 501-1000       | 7        | 21.21%  |
| 101-250        | 6        | 18.18%  |
| 1001-2000      | 5        | 15.15%  |
| More than 3000 | 4        | 12.12%  |
| 21-50          | 1        | 3.03%   |
| 51-100         | 1        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 9        | 27.27%  |
| 101-250        | 6        | 18.18%  |
| 501-1000       | 5        | 15.15%  |
| 1001-2000      | 4        | 12.12%  |
| 251-500        | 3        | 9.09%   |
| 21-50          | 3        | 9.09%   |
| 51-100         | 2        | 6.06%   |
| More than 3000 | 1        | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Crucial CT1000P1SSD8 1TB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Crucial | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 1        | 1      | 100%    |

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
| Detected | 27       | 69     | 77.14%  |
| Works    | 7        | 13     | 20%     |
| Malfunc  | 1        | 1      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 18       | 45%     |
| AMD                         | 14       | 35%     |
| Samsung Electronics         | 2        | 5%      |
| Micron/Crucial Technology   | 2        | 5%      |
| Kingston Technology Company | 2        | 5%      |
| SanDisk                     | 1        | 2.5%    |
| Phison Electronics          | 1        | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 17.65%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 11.76%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 9.8%    |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 9.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 7.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 3.92%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 3.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.96%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.96%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.96%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1        | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.96%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.96%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 61.9%   |
| NVMe | 8        | 19.05%  |
| IDE  | 8        | 19.05%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 56.25%  |
| AMD    | 14       | 43.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i3-4160 CPU @ 3.60GHz                | 2        | 6.25%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz             | 1        | 3.13%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 3.13%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 3.13%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 3.13%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 3.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 3.13%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 3.13%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 3.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1        | 3.13%   |
| Intel Core i3-3210 CPU @ 3.20GHz                | 1        | 3.13%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 3.13%   |
| Intel Core 2 CPU 4300 @ 1.80GHz                 | 1        | 3.13%   |
| Intel Celeron CPU G3930 @ 2.90GHz               | 1        | 3.13%   |
| Intel Celeron CPU E3400 @ 2.60GHz               | 1        | 3.13%   |
| Intel Celeron CPU E3300 @ 2.50GHz               | 1        | 3.13%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1        | 3.13%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 3.13%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 3.13%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1        | 3.13%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 1        | 3.13%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 3.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 3.13%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 3.13%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 3.13%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 3.13%   |
| AMD Phenom II X4 955 Processor                  | 1        | 3.13%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 3.13%   |
| AMD A10-7890K Radeon R7, 12 Compute Cores 4C+8G | 1        | 3.13%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 7             | 5        | 15.63%  |
| Intel Core i5           | 4        | 12.5%   |
| Intel Core i3           | 4        | 12.5%   |
| Intel Core i7           | 3        | 9.38%   |
| Intel Celeron           | 3        | 9.38%   |
| AMD Ryzen 5             | 3        | 9.38%   |
| AMD Ryzen 9             | 2        | 6.25%   |
| AMD A10                 | 2        | 6.25%   |
| Intel Xeon              | 1        | 3.13%   |
| Intel Pentium Dual-Core | 1        | 3.13%   |
| Intel Core 2 Quad       | 1        | 3.13%   |
| Intel Core 2            | 1        | 3.13%   |
| AMD Phenom II X4        | 1        | 3.13%   |
| AMD FX                  | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 37.5%   |
| 4      | 9        | 28.13%  |
| 8      | 6        | 18.75%  |
| 6      | 3        | 9.38%   |
| 12     | 1        | 3.13%   |
| 3      | 1        | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 68.75%  |
| 1      | 10       | 31.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 32       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 6        | 18.18%  |
| 0x1067a    | 4        | 12.12%  |
| 0x0800820d | 3        | 9.09%   |
| 0x506e3    | 2        | 6.06%   |
| 0x206a7    | 2        | 6.06%   |
| 0x08701021 | 2        | 6.06%   |
| 0x08701013 | 2        | 6.06%   |
| 0x06003106 | 2        | 6.06%   |
| 0x906e9    | 1        | 3.03%   |
| 0x6f2      | 1        | 3.03%   |
| 0x40651    | 1        | 3.03%   |
| 0x306a9    | 1        | 3.03%   |
| 0x0a50000c | 1        | 3.03%   |
| 0x0a201204 | 1        | 3.03%   |
| 0x08600106 | 1        | 3.03%   |
| 0x06000852 | 1        | 3.03%   |
| 0x010000c8 | 1        | 3.03%   |
| Unknown    | 1        | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 7        | 21.88%  |
| Zen 2       | 5        | 15.63%  |
| Penryn      | 4        | 12.5%   |
| Zen+        | 3        | 9.38%   |
| Zen 3       | 2        | 6.25%   |
| Steamroller | 2        | 6.25%   |
| Skylake     | 2        | 6.25%   |
| SandyBridge | 2        | 6.25%   |
| Piledriver  | 1        | 3.13%   |
| KabyLake    | 1        | 3.13%   |
| K10         | 1        | 3.13%   |
| IvyBridge   | 1        | 3.13%   |
| Core        | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 15       | 39.47%  |
| Intel  | 12       | 31.58%  |
| Nvidia | 11       | 28.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 7.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.26%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 5.26%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 5.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 5.26%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.63%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 2.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.63%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 1        | 2.63%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 2.63%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 2.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1        | 2.63%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 2.63%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 2.63%   |
| Intel HD Graphics 530                                                       | 1        | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 2.63%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 2.63%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 2.63%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 2.63%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 2.63%   |
| AMD Renoir                                                                  | 1        | 2.63%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 2.63%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 2.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.63%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 2.63%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 2.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 2.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 14       | 43.75%  |
| 1 x Nvidia     | 9        | 28.13%  |
| 1 x Intel      | 6        | 18.75%  |
| Intel + Nvidia | 2        | 6.25%   |
| Intel + AMD    | 1        | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 25       | 78.13%  |
| Proprietary | 7        | 21.88%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 7        | 21.88%  |
| 0.51-1.0   | 7        | 21.88%  |
| Unknown    | 6        | 18.75%  |
| 3.01-4.0   | 4        | 12.5%   |
| 7.01-8.0   | 2        | 6.25%   |
| 5.01-6.0   | 2        | 6.25%   |
| 8.01-16.0  | 2        | 6.25%   |
| 0.01-0.5   | 2        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 18.92%  |
| AOC                  | 7        | 18.92%  |
| Goldstar             | 5        | 13.51%  |
| Dell                 | 3        | 8.11%   |
| NEC Computers        | 2        | 5.41%   |
| BenQ                 | 2        | 5.41%   |
| Ancor Communications | 2        | 5.41%   |
| Acer                 | 2        | 5.41%   |
| Sharp                | 1        | 2.7%    |
| Microstep            | 1        | 2.7%    |
| LG Electronics       | 1        | 2.7%    |
| Lenovo               | 1        | 2.7%    |
| Hewlett-Packard      | 1        | 2.7%    |
| ASUSTek Computer     | 1        | 2.7%    |
| Unknown              | 1        | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 3        | 7.5%    |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1        | 2.5%    |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch   | 1        | 2.5%    |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1        | 2.5%    |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1        | 2.5%    |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch           | 1        | 2.5%    |
| Microstep LCD Monitor MSI G241                                       | 1        | 2.5%    |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 2.5%    |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 1        | 2.5%    |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch            | 1        | 2.5%    |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1        | 2.5%    |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1        | 2.5%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 2.5%    |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1        | 2.5%    |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 2.5%    |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                  | 1        | 2.5%    |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                  | 1        | 2.5%    |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                    | 1        | 2.5%    |
| BenQ LCD Monitor T2200HD 5760x1080                                   | 1        | 2.5%    |
| BenQ LCD Monitor T2200HD                                             | 1        | 2.5%    |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 2.5%    |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 1        | 2.5%    |
| ASUSTek Computer MG248 AUS24A3 1920x1080 531x299mm 24.0-inch         | 1        | 2.5%    |
| AOC Q29G2G5 AOC2902 2560x1080 681x287mm 29.1-inch                    | 1        | 2.5%    |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 1        | 2.5%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 1        | 2.5%    |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                     | 1        | 2.5%    |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 2.5%    |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch     | 1        | 2.5%    |
| Ancor Communications LCD Monitor ASUS VH238 1920x1080                | 1        | 2.5%    |
| Acer V236HL ACR0350 1920x1080 510x290mm 23.1-inch                    | 1        | 2.5%    |
| Acer V193HQV ACR0133 1366x768 410x230mm 18.5-inch                    | 1        | 2.5%    |
| Unknown                                                              | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 45.95%  |
| 2560x1440 (QHD)    | 4        | 10.81%  |
| 1280x1024 (SXGA)   | 4        | 10.81%  |
| 1366x768 (WXGA)    | 3        | 8.11%   |
| 5760x1080          | 1        | 2.7%    |
| 3840x2160 (4K)     | 1        | 2.7%    |
| 2560x1080          | 1        | 2.7%    |
| 1680x1050 (WSXGA+) | 1        | 2.7%    |
| 1600x900 (HD+)     | 1        | 2.7%    |
| 1440x900 (WXGA+)   | 1        | 2.7%    |
| 1360x768           | 1        | 2.7%    |
| 1024x768 (XGA)     | 1        | 2.7%    |
| Unknown            | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 23.53%  |
| Unknown | 7        | 20.59%  |
| 18      | 4        | 11.76%  |
| 23      | 3        | 8.82%   |
| 27      | 2        | 5.88%   |
| 21      | 2        | 5.88%   |
| 17      | 2        | 5.88%   |
| 31      | 1        | 2.94%   |
| 29      | 1        | 2.94%   |
| 22      | 1        | 2.94%   |
| 20      | 1        | 2.94%   |
| 19      | 1        | 2.94%   |
| 15      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 38.24%  |
| 401-500     | 8        | 23.53%  |
| Unknown     | 7        | 20.59%  |
| 301-350     | 3        | 8.82%   |
| 601-700     | 2        | 5.88%   |
| 351-400     | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 50%     |
| Unknown | 7        | 19.44%  |
| 16/10   | 6        | 16.67%  |
| 5/4     | 3        | 8.33%   |
| 4/3     | 1        | 2.78%   |
| 21/9    | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 31.43%  |
| Unknown        | 7        | 20%     |
| 141-150        | 5        | 14.29%  |
| 251-300        | 4        | 11.43%  |
| 301-350        | 3        | 8.57%   |
| 151-200        | 3        | 8.57%   |
| 351-500        | 1        | 2.86%   |
| 101-110        | 1        | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 66.67%  |
| Unknown | 7        | 21.21%  |
| 101-120 | 3        | 9.09%   |
| 161-240 | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 68.75%  |
| 2     | 9        | 28.13%  |
| 3     | 1        | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 24       | 48.98%  |
| Intel                 | 12       | 24.49%  |
| Qualcomm Atheros      | 4        | 8.16%   |
| MediaTek              | 2        | 4.08%   |
| Xiaomi                | 1        | 2.04%   |
| Ralink Technology     | 1        | 2.04%   |
| Linksys               | 1        | 2.04%   |
| Huawei Technologies   | 1        | 2.04%   |
| D-Link System         | 1        | 2.04%   |
| Broadcom              | 1        | 2.04%   |
| Belkin Components     | 1        | 2.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                       | 21       | 36.84%  |
| Intel I211 Gigabit Network Connection                                                   | 4        | 7.02%   |
| Intel Wi-Fi 6 AX200                                                                     | 3        | 5.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 3.51%   |
| Intel Wireless 3165                                                                     | 2        | 3.51%   |
| Intel Ethernet Controller I225-V                                                        | 2        | 3.51%   |
| Intel Ethernet Connection I217-LM                                                       | 2        | 3.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                          | 1        | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 1.75%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                   | 1        | 1.75%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 1.75%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 1        | 1.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                              | 1        | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                           | 1        | 1.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 1.75%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 1.75%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 1.75%   |
| Intel Wireless-AC 9260                                                                  | 1        | 1.75%   |
| Intel PRO/100 VE Network Connection                                                     | 1        | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 1.75%   |
| Huawei STK-L21                                                                          | 1        | 1.75%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 1.75%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 28.57%  |
| Realtek Semiconductor | 5        | 23.81%  |
| Qualcomm Atheros      | 3        | 14.29%  |
| MediaTek              | 2        | 9.52%   |
| Ralink Technology     | 1        | 4.76%   |
| Linksys               | 1        | 4.76%   |
| D-Link System         | 1        | 4.76%   |
| Broadcom              | 1        | 4.76%   |
| Belkin Components     | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 3        | 13.64%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 9.09%   |
| Intel Wireless 3165                                                                     | 2        | 9.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 4.55%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 4.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 1        | 4.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 4.55%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 4.55%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 4.55%   |
| Intel Wireless-AC 9260                                                                  | 1        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 4.55%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 4.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 4.55%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 62.86%  |
| Intel                 | 9        | 25.71%  |
| Qualcomm Atheros      | 2        | 5.71%   |
| Xiaomi                | 1        | 2.86%   |
| Huawei Technologies   | 1        | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 60%     |
| Intel I211 Gigabit Network Connection                             | 4        | 11.43%  |
| Intel Ethernet Controller I225-V                                  | 2        | 5.71%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 5.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.86%   |
| Intel PRO/100 VE Network Connection                               | 1        | 2.86%   |
| Huawei STK-L21                                                    | 1        | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 66.67%  |
| WiFi     | 16       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 65.71%  |
| WiFi     | 12       | 34.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 65.63%  |
| 2     | 9        | 28.13%  |
| 3     | 2        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 72.73%  |
| Yes  | 9        | 27.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 40%     |
| Cambridge Silicon Radio         | 3        | 20%     |
| Broadcom                        | 2        | 13.33%  |
| Realtek Semiconductor           | 1        | 6.67%   |
| Qualcomm Atheros Communications | 1        | 6.67%   |
| MediaTek                        | 1        | 6.67%   |
| ASUSTek Computer                | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 20%     |
| Intel Bluetooth wireless interface                  | 2        | 13.33%  |
| Intel AX200 Bluetooth                               | 2        | 13.33%  |
| Realtek Bluetooth Radio                             | 1        | 6.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 6.67%   |
| MediaTek Wireless_Device                            | 1        | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.67%   |
| Broadcom BCM92045B3 ROM                             | 1        | 6.67%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 6.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 18       | 34.62%  |
| AMD                 | 17       | 32.69%  |
| Nvidia              | 10       | 19.23%  |
| C-Media Electronics | 2        | 3.85%   |
| Blue Microphones    | 2        | 3.85%   |
| Texas Instruments   | 1        | 1.92%   |
| Tenx Technology     | 1        | 1.92%   |
| Cooler Master       | 1        | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 8.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 7.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 7.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 5.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 4.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 4.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 4.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.9%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 2.9%    |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 2.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 2.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.9%    |
| AMD Navi 10 HDMI Audio                                                     | 2        | 2.9%    |
| AMD FCH Azalia Controller                                                  | 2        | 2.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 2.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.9%    |
| Texas Instruments PCM2904 Audio Codec                                      | 1        | 1.45%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.45%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.45%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1.45%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.45%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.45%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.45%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.45%   |
| Cooler Master CH321                                                        | 1        | 1.45%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 1.45%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.45%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 1.45%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.45%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 2        | 25%     |
| Unknown             | 1        | 12.5%   |
| Transcend           | 1        | 12.5%   |
| Samsung Electronics | 1        | 12.5%   |
| Patriot             | 1        | 12.5%   |
| Corsair             | 1        | 12.5%   |
| A-DATA Technology   | 1        | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 12.5%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM 1600MT/s             | 1        | 12.5%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s      | 1        | 12.5%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s      | 1        | 12.5%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s    | 1        | 12.5%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8GB DIMM DDR4 3200MT/s   | 1        | 12.5%   |
| Corsair RAM CMK16GX4M2Z3200C16 8192MB DIMM DDR4 3200MT/s | 1        | 12.5%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s              | 1        | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 4        | 57.14%  |
| DDR4 | 3        | 42.86%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 7        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 5        | 62.5%   |
| 4096 | 3        | 37.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 50%     |
| 3200  | 2        | 25%     |
| 2400  | 2        | 25%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Logitech        | 4        | 44.44%  |
| MacroSilicon    | 1        | 11.11%  |
| LG Electronics  | 1        | 11.11%  |
| Hewlett-Packard | 1        | 11.11%  |
| Acer            | 1        | 11.11%  |
| A4Tech          | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| MacroSilicon ShadowCast              | 1        | 11.11%  |
| Logitech Webcam C270                 | 1        | 11.11%  |
| Logitech HD Pro Webcam C920          | 1        | 11.11%  |
| Logitech C922 Pro Stream Webcam      | 1        | 11.11%  |
| Logitech C920 PRO HD Webcam          | 1        | 11.11%  |
| LG Optimus (Various Models) MTP Mode | 1        | 11.11%  |
| HP Webcam HD 2300                    | 1        | 11.11%  |
| Acer LENOVO LBG 720P CAM             | 1        | 11.11%  |
| A4Tech FHD 1080P PC Camera           | 1        | 11.11%  |

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
| 0     | 29       | 87.88%  |
| 1     | 3        | 9.09%   |
| 3     | 1        | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 4        | 50%     |
| Multimedia controller | 2        | 25%     |
| Graphics card         | 1        | 12.5%   |
| Camera                | 1        | 12.5%   |

