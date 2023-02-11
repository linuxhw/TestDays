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

Total: 57

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI        | B350 TOMAHAWK ARCTIC        | [10f14c4cbd](https://linux-hardware.org/?probe=10f14c4cbd) | Jan 23, 2023 |
| ASRock     | X300M-STX                   | [13ce0469f3](https://linux-hardware.org/?probe=13ce0469f3) | Jan 23, 2023 |
| ASRock     | X300M-STX                   | [55db2decf3](https://linux-hardware.org/?probe=55db2decf3) | Jan 07, 2023 |
| Gigabyte   | EP45-UD3P                   | [fa5bdcfc4c](https://linux-hardware.org/?probe=fa5bdcfc4c) | Jan 06, 2023 |
| ASRock     | FM2A88M-HD+ R3.0            | [acbd8114d2](https://linux-hardware.org/?probe=acbd8114d2) | Jan 04, 2023 |
| Gigabyte   | EP45-UD3P                   | [d89c5688d2](https://linux-hardware.org/?probe=d89c5688d2) | Jan 03, 2023 |
| ASRock     | FM2A88X Extreme4+           | [3fb1b015e3](https://linux-hardware.org/?probe=3fb1b015e3) | Jan 02, 2023 |
| Gigabyte   | B550M AORUS PRO-P           | [cdb2bf4725](https://linux-hardware.org/?probe=cdb2bf4725) | Jan 02, 2023 |
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
| 6.0.11-225.current  | 6        | 15%     |
| 5.15.32-213.current | 5        | 12.5%   |
| 5.14.21-210.current | 4        | 10%     |
| 5.14.16-205.current | 4        | 10%     |
| 5.13.12-193.current | 3        | 7.5%    |
| 5.15.50-216.current | 2        | 5%      |
| 5.15.43-215.current | 2        | 5%      |
| 5.15.30-212.current | 2        | 5%      |
| 5.14.14-202.current | 2        | 5%      |
| 5.13.6-190.current  | 2        | 5%      |
| 5.13.1-187.current  | 2        | 5%      |
| 6.1.5-229.current   | 1        | 2.5%    |
| 5.15.77-219.current | 1        | 2.5%    |
| 5.15.68-218.current | 1        | 2.5%    |
| 5.15.37-214.current | 1        | 2.5%    |
| 5.15.26-211.current | 1        | 2.5%    |
| 5.13.8-191.current  | 1        | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.11  | 6        | 15%     |
| 5.15.32 | 5        | 12.5%   |
| 5.14.21 | 4        | 10%     |
| 5.14.16 | 4        | 10%     |
| 5.13.12 | 3        | 7.5%    |
| 5.15.50 | 2        | 5%      |
| 5.15.43 | 2        | 5%      |
| 5.15.30 | 2        | 5%      |
| 5.14.14 | 2        | 5%      |
| 5.13.6  | 2        | 5%      |
| 5.13.1  | 2        | 5%      |
| 6.1.5   | 1        | 2.5%    |
| 5.15.77 | 1        | 2.5%    |
| 5.15.68 | 1        | 2.5%    |
| 5.15.37 | 1        | 2.5%    |
| 5.15.26 | 1        | 2.5%    |
| 5.13.8  | 1        | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 14       | 35.9%   |
| 5.14    | 10       | 25.64%  |
| 5.13    | 8        | 20.51%  |
| 6.0     | 6        | 15.38%  |
| 6.1     | 1        | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 37       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Budgie  | 23       | 62.16%  |
| GNOME   | 7        | 18.92%  |
| KDE5    | 3        | 8.11%   |
| MATE    | 2        | 5.41%   |
| KDE     | 1        | 2.7%    |
| Unknown | 1        | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 36       | 97.3%   |
| Wayland | 1        | 2.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 70.27%  |
| LightDM | 6        | 16.22%  |
| GDM     | 3        | 8.11%   |
| SDDM    | 2        | 5.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 42.11%  |
| ru_RU | 3        | 7.89%   |
| ro_RO | 3        | 7.89%   |
| es_ES | 3        | 7.89%   |
| fr_FR | 2        | 5.26%   |
| en_GB | 2        | 5.26%   |
| de_DE | 2        | 5.26%   |
| pt_BR | 1        | 2.63%   |
| nl_NL | 1        | 2.63%   |
| fi_FI | 1        | 2.63%   |
| es_VE | 1        | 2.63%   |
| en_DK | 1        | 2.63%   |
| ar_SA | 1        | 2.63%   |
| ar_EG | 1        | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 22       | 59.46%  |
| EFI  | 15       | 40.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 35       | 94.59%  |
| Xfs   | 1        | 2.7%    |
| Btrfs | 1        | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 72.97%  |
| MBR     | 7        | 18.92%  |
| GPT     | 3        | 8.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 86.84%  |
| Yes       | 5        | 13.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 81.08%  |
| Yes       | 7        | 18.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 10       | 27.03%  |
| ASUSTek Computer    | 6        | 16.22%  |
| ASRock              | 6        | 16.22%  |
| MSI                 | 3        | 8.11%   |
| Lenovo              | 2        | 5.41%   |
| Hewlett-Packard     | 2        | 5.41%   |
| Unknown             | 2        | 5.41%   |
| MEGA                | 1        | 2.7%    |
| Intel               | 1        | 2.7%    |
| Fujitsu             | 1        | 2.7%    |
| eMachines           | 1        | 2.7%    |
| Dell                | 1        | 2.7%    |
| Biostar             | 1        | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 2        | 5.41%   |
| MSI MS-7B89                      | 1        | 2.7%    |
| MSI MS-7B85                      | 1        | 2.7%    |
| MSI MS-7A34                      | 1        | 2.7%    |
| MEGA G41T-M7 LGT                 | 1        | 2.7%    |
| Lenovo ThinkCentre M71e 3157G6S  | 1        | 2.7%    |
| Lenovo C50-30 F0B1002EFR         | 1        | 2.7%    |
| Intel D946GZIS AAD66165-302      | 1        | 2.7%    |
| HP ProDesk 490 G3 MT Business PC | 1        | 2.7%    |
| HP 750-171                       | 1        | 2.7%    |
| Gigabyte Z68AP-D3                | 1        | 2.7%    |
| Gigabyte P31-ES3G                | 1        | 2.7%    |
| Gigabyte H81M-S2V                | 1        | 2.7%    |
| Gigabyte H110M-DS2V              | 1        | 2.7%    |
| Gigabyte GA-MA770-UD3            | 1        | 2.7%    |
| Gigabyte GA-78LMT-USB3 6.0       | 1        | 2.7%    |
| Gigabyte F2A68HM-H               | 1        | 2.7%    |
| Gigabyte EP45-UD3P               | 1        | 2.7%    |
| Gigabyte B85M-D3H                | 1        | 2.7%    |
| Gigabyte B550M AORUS PRO-P       | 1        | 2.7%    |
| Fujitsu CELSIUS W530             | 1        | 2.7%    |
| eMachines EL1852G                | 1        | 2.7%    |
| Dell OptiPlex 9020               | 1        | 2.7%    |
| Biostar H61MLV2                  | 1        | 2.7%    |
| ASUS TUF Gaming X570-PRO         | 1        | 2.7%    |
| ASUS TUF B450-PRO GAMING         | 1        | 2.7%    |
| ASUS ROG STRIX B450-F GAMING     | 1        | 2.7%    |
| ASUS P5G41T-M LX3                | 1        | 2.7%    |
| ASUS All Series                  | 1        | 2.7%    |
| ASUS A88X-PRO                    | 1        | 2.7%    |
| ASRock X570M Pro4                | 1        | 2.7%    |
| ASRock X300M-STX                 | 1        | 2.7%    |
| ASRock H81 Pro BTC R2.0          | 1        | 2.7%    |
| ASRock FM2A88X Extreme4+         | 1        | 2.7%    |
| ASRock FM2A88M-HD+ R3.0          | 1        | 2.7%    |
| ASRock B450 Gaming-ITX/ac        | 1        | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS TUF               | 2        | 5.41%   |
| Unknown                | 2        | 5.41%   |
| MSI MS-7B89            | 1        | 2.7%    |
| MSI MS-7B85            | 1        | 2.7%    |
| MSI MS-7A34            | 1        | 2.7%    |
| MEGA G41T-M7           | 1        | 2.7%    |
| Lenovo ThinkCentre     | 1        | 2.7%    |
| Lenovo C50-30          | 1        | 2.7%    |
| Intel D946GZIS         | 1        | 2.7%    |
| HP ProDesk             | 1        | 2.7%    |
| HP 750-171             | 1        | 2.7%    |
| Gigabyte Z68AP-D3      | 1        | 2.7%    |
| Gigabyte P31-ES3G      | 1        | 2.7%    |
| Gigabyte H81M-S2V      | 1        | 2.7%    |
| Gigabyte H110M-DS2V    | 1        | 2.7%    |
| Gigabyte GA-MA770-UD3  | 1        | 2.7%    |
| Gigabyte GA-78LMT-USB3 | 1        | 2.7%    |
| Gigabyte F2A68HM-H     | 1        | 2.7%    |
| Gigabyte EP45-UD3P     | 1        | 2.7%    |
| Gigabyte B85M-D3H      | 1        | 2.7%    |
| Gigabyte B550M         | 1        | 2.7%    |
| Fujitsu CELSIUS        | 1        | 2.7%    |
| eMachines EL1852G      | 1        | 2.7%    |
| Dell OptiPlex          | 1        | 2.7%    |
| Biostar H61MLV2        | 1        | 2.7%    |
| ASUS ROG               | 1        | 2.7%    |
| ASUS P5G41T-M          | 1        | 2.7%    |
| ASUS All               | 1        | 2.7%    |
| ASUS A88X-PRO          | 1        | 2.7%    |
| ASRock X570M           | 1        | 2.7%    |
| ASRock X300M-STX       | 1        | 2.7%    |
| ASRock H81             | 1        | 2.7%    |
| ASRock FM2A88X         | 1        | 2.7%    |
| ASRock FM2A88M-HD+     | 1        | 2.7%    |
| ASRock B450            | 1        | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 7        | 18.92%  |
| 2014 | 6        | 16.22%  |
| 2015 | 4        | 10.81%  |
| 2011 | 4        | 10.81%  |
| 2008 | 3        | 8.11%   |
| 2021 | 2        | 5.41%   |
| 2020 | 2        | 5.41%   |
| 2016 | 2        | 5.41%   |
| 2013 | 2        | 5.41%   |
| 2019 | 1        | 2.7%    |
| 2017 | 1        | 2.7%    |
| 2012 | 1        | 2.7%    |
| 2010 | 1        | 2.7%    |
| 2006 | 1        | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 37       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 37       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 9        | 24.32%  |
| 16.01-24.0 | 9        | 24.32%  |
| 8.01-16.0  | 7        | 18.92%  |
| 4.01-8.0   | 6        | 16.22%  |
| 32.01-64.0 | 5        | 13.51%  |
| 2.01-3.0   | 1        | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 18       | 45%     |
| 3.01-4.0  | 7        | 17.5%   |
| 2.01-3.0  | 7        | 17.5%   |
| 4.01-8.0  | 6        | 15%     |
| 8.01-16.0 | 1        | 2.5%    |
| 0.51-1.0  | 1        | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 30%     |
| 4      | 10       | 25%     |
| 2      | 10       | 25%     |
| 3      | 5        | 12.5%   |
| 5      | 3        | 7.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 53.85%  |
| Yes       | 18       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 37       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 51.35%  |
| Yes       | 18       | 48.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 60.53%  |
| Yes       | 15       | 39.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 7        | 18.92%  |
| Germany      | 4        | 10.81%  |
| Romania      | 3        | 8.11%   |
| Russia       | 2        | 5.41%   |
| Argentina    | 2        | 5.41%   |
| Venezuela    | 1        | 2.7%    |
| Thailand     | 1        | 2.7%    |
| Sweden       | 1        | 2.7%    |
| Spain        | 1        | 2.7%    |
| Saudi Arabia | 1        | 2.7%    |
| Philippines  | 1        | 2.7%    |
| Norway       | 1        | 2.7%    |
| Netherlands  | 1        | 2.7%    |
| Kazakhstan   | 1        | 2.7%    |
| Iran         | 1        | 2.7%    |
| India        | 1        | 2.7%    |
| Guyana       | 1        | 2.7%    |
| Greece       | 1        | 2.7%    |
| France       | 1        | 2.7%    |
| Finland      | 1        | 2.7%    |
| Denmark      | 1        | 2.7%    |
| Canada       | 1        | 2.7%    |
| Brazil       | 1        | 2.7%    |
| Albania      | 1        | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Constanța      | 3        | 7.69%   |
| Weil am Rhein   | 1        | 2.56%   |
| Viby J          | 1        | 2.56%   |
| Toronto         | 1        | 2.56%   |
| Thessaloniki    | 1        | 2.56%   |
| Stockholm       | 1        | 2.56%   |
| Songkhla        | 1        | 2.56%   |
| Seville         | 1        | 2.56%   |
| Severna Park    | 1        | 2.56%   |
| San Justo       | 1        | 2.56%   |
| Portsmouth      | 1        | 2.56%   |
| Phoenix         | 1        | 2.56%   |
| Oslo            | 1        | 2.56%   |
| Orenburg        | 1        | 2.56%   |
| Ochten          | 1        | 2.56%   |
| Lohja           | 1        | 2.56%   |
| Lipa City       | 1        | 2.56%   |
| Lexington       | 1        | 2.56%   |
| Krefeld         | 1        | 2.56%   |
| Kozani          | 1        | 2.56%   |
| Kolkata         | 1        | 2.56%   |
| Khobar          | 1        | 2.56%   |
| Isidro Casanova | 1        | 2.56%   |
| Huntington Park | 1        | 2.56%   |
| Hamburg         | 1        | 2.56%   |
| Great Neck      | 1        | 2.56%   |
| Georgetown      | 1        | 2.56%   |
| Garland         | 1        | 2.56%   |
| Durrës         | 1        | 2.56%   |
| Dammam          | 1        | 2.56%   |
| Curitiba        | 1        | 2.56%   |
| Chita           | 1        | 2.56%   |
| Caracas         | 1        | 2.56%   |
| Caen            | 1        | 2.56%   |
| Bad Homburg     | 1        | 2.56%   |
| Atyrau          | 1        | 2.56%   |
| Arak            | 1        | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 21       | 30     | 25.93%  |
| Samsung Electronics         | 14       | 21     | 17.28%  |
| Seagate                     | 8        | 9      | 9.88%   |
| Kingston                    | 8        | 11     | 9.88%   |
| Crucial                     | 6        | 6      | 7.41%   |
| Toshiba                     | 3        | 3      | 3.7%    |
| SanDisk                     | 3        | 3      | 3.7%    |
| PNY                         | 2        | 2      | 2.47%   |
| Hitachi                     | 2        | 2      | 2.47%   |
| Unknown                     | 1        | 1      | 1.23%   |
| SPCC Sol                    | 1        | 1      | 1.23%   |
| Silicon Motion              | 1        | 1      | 1.23%   |
| Phison Electronics          | 1        | 1      | 1.23%   |
| Phison                      | 1        | 1      | 1.23%   |
| Patriot                     | 1        | 1      | 1.23%   |
| Micron Technology           | 1        | 1      | 1.23%   |
| Maxtor                      | 1        | 1      | 1.23%   |
| Kingston Technology Company | 1        | 1      | 1.23%   |
| Intenso                     | 1        | 2      | 1.23%   |
| HFS512GD                    | 1        | 1      | 1.23%   |
| Emtec                       | 1        | 1      | 1.23%   |
| China                       | 1        | 1      | 1.23%   |
| A-DATA Technology           | 1        | 1      | 1.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                         | 4        | 4.35%   |
| Samsung NVMe SSD Drive 500GB                      | 3        | 3.26%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2        | 2.17%   |
| WDC WD10EZEX-08M2NA0 1TB                          | 2        | 2.17%   |
| Toshiba DT01ACA050 500GB                          | 2        | 2.17%   |
| Seagate ST4000DM004-2CV104 4TB                    | 2        | 2.17%   |
| Seagate ST2000DM006-2DM164 2TB                    | 2        | 2.17%   |
| Kingston SA400S37480G 480GB SSD                   | 2        | 2.17%   |
| Kingston SA400S37240G 240GB SSD                   | 2        | 2.17%   |
| Crucial CT1000P1SSD8 1TB                          | 2        | 2.17%   |
| Crucial CT1000MX500SSD1 1TB                       | 2        | 2.17%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                  | 1        | 1.09%   |
| WDC WD6400AAKS-75A7B2 640GB                       | 1        | 1.09%   |
| WDC WD5000AVDS-63U7B1 500GB                       | 1        | 1.09%   |
| WDC WD5000AVCS-632DY1 500GB                       | 1        | 1.09%   |
| WDC WD5000AAKX-003CA0 500GB                       | 1        | 1.09%   |
| WDC WD40EZRZ-00GXCB0 4TB                          | 1        | 1.09%   |
| WDC WD3200AAJS-00YZCA0 320GB                      | 1        | 1.09%   |
| WDC WD32 00AAJS-00L7A0 320GB                      | 1        | 1.09%   |
| WDC WD3000GLFS-01F8U0 304GB                       | 1        | 1.09%   |
| WDC WD2500HHTZ-04N21V1 250GB                      | 1        | 1.09%   |
| WDC WD20EARX-00PASB0 2TB                          | 1        | 1.09%   |
| WDC WD2003FZEX-00Z4SA0 2TB                        | 1        | 1.09%   |
| WDC WD2003FZEX-00SRLA0 2TB                        | 1        | 1.09%   |
| WDC WD1600AAJS-00PSA0 160GB                       | 1        | 1.09%   |
| WDC WD1600AAJS-00M0A0 160GB                       | 1        | 1.09%   |
| WDC WD140EFGX-68B0GN0 14TB                        | 1        | 1.09%   |
| WDC WD10SPSX-00A6WT0 1TB                          | 1        | 1.09%   |
| WDC WD10EZRX-00L4HB0 1TB                          | 1        | 1.09%   |
| WDC WD10EZEX-21WN4A0 1TB                          | 1        | 1.09%   |
| WDC WD10EADS-00P8B0 1TB                           | 1        | 1.09%   |
| WDC WD10EADS-00M2B0 1TB                           | 1        | 1.09%   |
| WDC WD1003FBYX-01Y7B0 1TB                         | 1        | 1.09%   |
| WDC WD My Passport 25F3 512GB                     | 1        | 1.09%   |
| Unknown SD/MMC/MS PRO 2GB                         | 1        | 1.09%   |
| Toshiba DT01ACA100 1TB                            | 1        | 1.09%   |
| SPCC Sol id State Disk 128GB SSD                  | 1        | 1.09%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1        | 1.09%   |
| Seagate ST500DM002-1BD142 500GB                   | 1        | 1.09%   |
| Seagate ST3320418AS 320GB                         | 1        | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 28     | 54.05%  |
| Seagate             | 8        | 9      | 21.62%  |
| Toshiba             | 3        | 3      | 8.11%   |
| Hitachi             | 2        | 2      | 5.41%   |
| Unknown             | 1        | 1      | 2.7%    |
| Samsung Electronics | 1        | 1      | 2.7%    |
| Maxtor              | 1        | 1      | 2.7%    |
| Intenso             | 1        | 2      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 16     | 36.36%  |
| Kingston            | 6        | 9      | 18.18%  |
| Crucial             | 4        | 4      | 12.12%  |
| SanDisk             | 2        | 2      | 6.06%   |
| PNY                 | 2        | 2      | 6.06%   |
| WDC                 | 1        | 1      | 3.03%   |
| SPCC Sol            | 1        | 1      | 3.03%   |
| Patriot             | 1        | 1      | 3.03%   |
| Micron Technology   | 1        | 1      | 3.03%   |
| Emtec               | 1        | 1      | 3.03%   |
| China               | 1        | 1      | 3.03%   |
| A-DATA Technology   | 1        | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 29       | 47     | 44.62%  |
| SSD     | 23       | 40     | 35.38%  |
| NVMe    | 11       | 13     | 16.92%  |
| Unknown | 2        | 2      | 3.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 35       | 82     | 70%     |
| NVMe | 11       | 13     | 22%     |
| SAS  | 4        | 7      | 8%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 54     | 51.85%  |
| 0.51-1.0   | 14       | 19     | 25.93%  |
| 1.01-2.0   | 7        | 8      | 12.96%  |
| 3.01-4.0   | 3        | 3      | 5.56%   |
| 10.01-20.0 | 1        | 1      | 1.85%   |
| 4.01-10.0  | 1        | 2      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 9        | 23.68%  |
| 101-250        | 9        | 23.68%  |
| 501-1000       | 7        | 18.42%  |
| 1001-2000      | 6        | 15.79%  |
| More than 3000 | 4        | 10.53%  |
| 21-50          | 1        | 2.63%   |
| 2001-3000      | 1        | 2.63%   |
| 51-100         | 1        | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 10       | 25.64%  |
| 1001-2000      | 7        | 17.95%  |
| 101-250        | 6        | 15.38%  |
| 501-1000       | 5        | 12.82%  |
| 21-50          | 4        | 10.26%  |
| 251-500        | 3        | 7.69%   |
| 51-100         | 3        | 7.69%   |
| More than 3000 | 1        | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB | 1        | 1      | 50%     |
| Crucial CT1000P1SSD8 1TB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Crucial | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 1        | 1      | 50%     |
| HDD  | 1        | 1      | 50%     |

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
| Detected | 29       | 78     | 69.05%  |
| Works    | 11       | 22     | 26.19%  |
| Malfunc  | 2        | 2      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 19       | 38.78%  |
| AMD                         | 18       | 36.73%  |
| Kingston Technology Company | 3        | 6.12%   |
| Samsung Electronics         | 2        | 4.08%   |
| Phison Electronics          | 2        | 4.08%   |
| Micron/Crucial Technology   | 2        | 4.08%   |
| Silicon Motion              | 1        | 2.04%   |
| SanDisk                     | 1        | 2.04%   |
| JMicron Technology          | 1        | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 19.05%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 9.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 7.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 7.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 6.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 3.17%   |
| Phison E12 NVMe Controller                                                              | 2        | 3.17%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 3.17%   |
| AMD FCH IDE Controller                                                                  | 2        | 3.17%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.59%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.59%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1        | 1.59%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.59%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.59%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.59%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.59%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.59%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 31       | 59.62%  |
| IDE  | 11       | 21.15%  |
| NVMe | 10       | 19.23%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 51.35%  |
| AMD    | 18       | 48.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i3-4160 CPU @ 3.60GHz                | 2        | 5.41%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2        | 5.41%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz             | 1        | 2.7%    |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 2.7%    |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 2.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 2.7%    |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 2.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 2.7%    |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 2.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 2.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1        | 2.7%    |
| Intel Core i3-3210 CPU @ 3.20GHz                | 1        | 2.7%    |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 2.7%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 2.7%    |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1        | 2.7%    |
| Intel Core 2 CPU 4300 @ 1.80GHz                 | 1        | 2.7%    |
| Intel Celeron CPU G3930 @ 2.90GHz               | 1        | 2.7%    |
| Intel Celeron CPU E3400 @ 2.60GHz               | 1        | 2.7%    |
| Intel Celeron CPU E3300 @ 2.50GHz               | 1        | 2.7%    |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1        | 2.7%    |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 2.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1        | 2.7%    |
| AMD Ryzen 7 3800X 8-Core Processor              | 1        | 2.7%    |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 2.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 2.7%    |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 2.7%    |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 2.7%    |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2.7%    |
| AMD Ryzen 3 4300GE with Radeon Graphics         | 1        | 2.7%    |
| AMD Phenom II X4 955 Processor                  | 1        | 2.7%    |
| AMD FX-6300 Six-Core Processor                  | 1        | 2.7%    |
| AMD A8-7650K Radeon R7, 10 Compute Cores 4C+6G  | 1        | 2.7%    |
| AMD A10-7890K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.7%    |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.7%    |
| AMD A10-6800K APU with Radeon HD Graphics       | 1        | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 7             | 6        | 16.22%  |
| Intel Core i5           | 4        | 10.81%  |
| Intel Core i3           | 4        | 10.81%  |
| Intel Core i7           | 3        | 8.11%   |
| Intel Celeron           | 3        | 8.11%   |
| AMD Ryzen 5             | 3        | 8.11%   |
| AMD A10                 | 3        | 8.11%   |
| Intel Core 2 Quad       | 2        | 5.41%   |
| AMD Ryzen 9             | 2        | 5.41%   |
| Intel Xeon              | 1        | 2.7%    |
| Intel Pentium Dual-Core | 1        | 2.7%    |
| Intel Core 2            | 1        | 2.7%    |
| AMD Ryzen 3             | 1        | 2.7%    |
| AMD Phenom II X4        | 1        | 2.7%    |
| AMD FX                  | 1        | 2.7%    |
| AMD A8                  | 1        | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 37.84%  |
| 4      | 11       | 29.73%  |
| 8      | 7        | 18.92%  |
| 6      | 3        | 8.11%   |
| 12     | 1        | 2.7%    |
| 3      | 1        | 2.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 37       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 70.27%  |
| 1      | 11       | 29.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 37       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 6        | 15.38%  |
| 0x1067a    | 4        | 10.26%  |
| 0x0800820d | 3        | 7.69%   |
| 0x06003106 | 3        | 7.69%   |
| 0x506e3    | 2        | 5.13%   |
| 0x206a7    | 2        | 5.13%   |
| 0x08701021 | 2        | 5.13%   |
| 0x08701013 | 2        | 5.13%   |
| 0x08600106 | 2        | 5.13%   |
| Unknown    | 2        | 5.13%   |
| 0x906e9    | 1        | 2.56%   |
| 0x6f2      | 1        | 2.56%   |
| 0x40651    | 1        | 2.56%   |
| 0x306a9    | 1        | 2.56%   |
| 0x0a50000c | 1        | 2.56%   |
| 0x0a201204 | 1        | 2.56%   |
| 0x0a201016 | 1        | 2.56%   |
| 0x0800820b | 1        | 2.56%   |
| 0x06001119 | 1        | 2.56%   |
| 0x06000852 | 1        | 2.56%   |
| 0x010000c8 | 1        | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 7        | 18.92%  |
| Zen 2       | 6        | 16.22%  |
| Penryn      | 5        | 13.51%  |
| Zen+        | 3        | 8.11%   |
| Zen 3       | 3        | 8.11%   |
| Steamroller | 3        | 8.11%   |
| Skylake     | 2        | 5.41%   |
| SandyBridge | 2        | 5.41%   |
| Piledriver  | 2        | 5.41%   |
| KabyLake    | 1        | 2.7%    |
| K10         | 1        | 2.7%    |
| IvyBridge   | 1        | 2.7%    |
| Core        | 1        | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 19       | 44.19%  |
| Nvidia | 12       | 27.91%  |
| Intel  | 12       | 27.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 6.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 6.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 4.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 4.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.65%   |
| AMD Renoir                                                                  | 2        | 4.65%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 4.65%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 4.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.33%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 2.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.33%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 1        | 2.33%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 2.33%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 2.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1        | 2.33%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 2.33%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 2.33%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 1        | 2.33%   |
| Intel HD Graphics 530                                                       | 1        | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 2.33%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 2.33%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 2.33%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 2.33%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 2.33%   |
| AMD Richland [Radeon HD 8670D]                                              | 1        | 2.33%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 2.33%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 2.33%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.33%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 2.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 18       | 48.65%  |
| 1 x Nvidia     | 10       | 27.03%  |
| 1 x Intel      | 6        | 16.22%  |
| Intel + Nvidia | 2        | 5.41%   |
| Intel + AMD    | 1        | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 30       | 81.08%  |
| Proprietary | 7        | 18.92%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 9        | 24.32%  |
| 0.51-1.0   | 8        | 21.62%  |
| Unknown    | 7        | 18.92%  |
| 3.01-4.0   | 4        | 10.81%  |
| 7.01-8.0   | 3        | 8.11%   |
| 5.01-6.0   | 2        | 5.41%   |
| 8.01-16.0  | 2        | 5.41%   |
| 0.01-0.5   | 2        | 5.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 18.18%  |
| Goldstar             | 8        | 18.18%  |
| AOC                  | 8        | 18.18%  |
| Dell                 | 3        | 6.82%   |
| Ancor Communications | 3        | 6.82%   |
| NEC Computers        | 2        | 4.55%   |
| BenQ                 | 2        | 4.55%   |
| Acer                 | 2        | 4.55%   |
| Sharp                | 1        | 2.27%   |
| Philips              | 1        | 2.27%   |
| Microstep            | 1        | 2.27%   |
| LG Electronics       | 1        | 2.27%   |
| Lenovo               | 1        | 2.27%   |
| Hewlett-Packard      | 1        | 2.27%   |
| ASUSTek Computer     | 1        | 2.27%   |
| Unknown              | 1        | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                   | 3        | 6.38%   |
| Goldstar L227W GSM566E 1680x1050 474x296mm 22.0-inch                 | 2        | 4.26%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM029A 1920x1200 582x364mm 27.0-inch | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1        | 2.13%   |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch   | 1        | 2.13%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1        | 2.13%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1        | 2.13%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                   | 1        | 2.13%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1        | 2.13%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch           | 1        | 2.13%   |
| Microstep LCD Monitor MSI G241                                       | 1        | 2.13%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 2.13%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 1        | 2.13%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch            | 1        | 2.13%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1        | 2.13%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1        | 2.13%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 2.13%   |
| Goldstar L227W GSM566F 1680x1050 474x296mm 22.0-inch                 | 1        | 2.13%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1        | 2.13%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 2.13%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                  | 1        | 2.13%   |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                  | 1        | 2.13%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                    | 1        | 2.13%   |
| BenQ LCD Monitor T2200HD 5760x1080                                   | 1        | 2.13%   |
| BenQ LCD Monitor T2200HD                                             | 1        | 2.13%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 2.13%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 1        | 2.13%   |
| ASUSTek Computer MG248 AUS24A3 1920x1080 531x299mm 24.0-inch         | 1        | 2.13%   |
| AOC Q29G2G5 AOC2902 2560x1080 681x287mm 29.1-inch                    | 1        | 2.13%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                     | 1        | 2.13%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 1        | 2.13%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 1        | 2.13%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                       | 1        | 2.13%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 2.13%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch     | 1        | 2.13%   |
| Ancor Communications LCD Monitor ASUS VH238 1920x1080                | 1        | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 40.91%  |
| 2560x1440 (QHD)    | 5        | 11.36%  |
| 1680x1050 (WSXGA+) | 4        | 9.09%   |
| 1280x1024 (SXGA)   | 4        | 9.09%   |
| 1366x768 (WXGA)    | 3        | 6.82%   |
| 3840x2160 (4K)     | 2        | 4.55%   |
| 5760x1080          | 1        | 2.27%   |
| 2560x1080          | 1        | 2.27%   |
| 1920x1200 (WUXGA)  | 1        | 2.27%   |
| 1600x900 (HD+)     | 1        | 2.27%   |
| 1440x900 (WXGA+)   | 1        | 2.27%   |
| 1360x768           | 1        | 2.27%   |
| 1024x768 (XGA)     | 1        | 2.27%   |
| Unknown            | 1        | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 19.51%  |
| Unknown | 7        | 17.07%  |
| 27      | 5        | 12.2%   |
| 23      | 4        | 9.76%   |
| 18      | 4        | 9.76%   |
| 22      | 3        | 7.32%   |
| 21      | 3        | 7.32%   |
| 17      | 2        | 4.88%   |
| 31      | 1        | 2.44%   |
| 29      | 1        | 2.44%   |
| 20      | 1        | 2.44%   |
| 19      | 1        | 2.44%   |
| 15      | 1        | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 39.02%  |
| 401-500     | 12       | 29.27%  |
| Unknown     | 7        | 17.07%  |
| 301-350     | 3        | 7.32%   |
| 601-700     | 2        | 4.88%   |
| 351-400     | 1        | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 47.62%  |
| 16/10   | 9        | 21.43%  |
| Unknown | 7        | 16.67%  |
| 5/4     | 3        | 7.14%   |
| 4/3     | 1        | 2.38%   |
| 3/2     | 1        | 2.38%   |
| 21/9    | 1        | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 33.33%  |
| Unknown        | 7        | 16.67%  |
| 301-350        | 6        | 14.29%  |
| 141-150        | 5        | 11.9%   |
| 251-300        | 4        | 9.52%   |
| 151-200        | 4        | 9.52%   |
| 351-500        | 1        | 2.38%   |
| 101-110        | 1        | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 27       | 67.5%   |
| Unknown | 7        | 17.5%   |
| 101-120 | 5        | 12.5%   |
| 161-240 | 1        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 67.57%  |
| 2     | 11       | 29.73%  |
| 3     | 1        | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 49.12%  |
| Intel                 | 13       | 22.81%  |
| Qualcomm Atheros      | 7        | 12.28%  |
| MediaTek              | 2        | 3.51%   |
| Xiaomi                | 1        | 1.75%   |
| Ralink Technology     | 1        | 1.75%   |
| Linksys               | 1        | 1.75%   |
| Huawei Technologies   | 1        | 1.75%   |
| D-Link System         | 1        | 1.75%   |
| Broadcom              | 1        | 1.75%   |
| Belkin Components     | 1        | 1.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                       | 24       | 36.36%  |
| Intel I211 Gigabit Network Connection                                                   | 4        | 6.06%   |
| Intel Wi-Fi 6 AX200                                                                     | 3        | 4.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2        | 3.03%   |
| Intel Wireless 3165                                                                     | 2        | 3.03%   |
| Intel Ethernet Controller I225-V                                                        | 2        | 3.03%   |
| Intel Ethernet Connection I217-LM                                                       | 2        | 3.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                          | 1        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 1.52%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                                       | 1        | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                   | 1        | 1.52%   |
| Realtek 802.11ac NIC                                                                    | 1        | 1.52%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                               | 1        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 1.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 1        | 1.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                              | 1        | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                           | 1        | 1.52%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                              | 1        | 1.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 1.52%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 1.52%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 1.52%   |
| Intel Wireless-AC 9260                                                                  | 1        | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                           | 1        | 1.52%   |
| Intel PRO/100 VE Network Connection                                                     | 1        | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 1.52%   |
| Huawei ELS-NX9                                                                          | 1        | 1.52%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 1.52%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 1.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 28%     |
| Realtek Semiconductor | 6        | 24%     |
| Qualcomm Atheros      | 5        | 20%     |
| MediaTek              | 2        | 8%      |
| Ralink Technology     | 1        | 4%      |
| Linksys               | 1        | 4%      |
| D-Link System         | 1        | 4%      |
| Broadcom              | 1        | 4%      |
| Belkin Components     | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 3        | 11.54%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2        | 7.69%   |
| Intel Wireless 3165                                                                     | 2        | 7.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 3.85%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 3.85%   |
| Realtek 802.11ac NIC                                                                    | 1        | 3.85%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 3.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 1        | 3.85%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                              | 1        | 3.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 3.85%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 3.85%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 3.85%   |
| Intel Wireless-AC 9260                                                                  | 1        | 3.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                           | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 3.85%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 3.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 3.85%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 26       | 65%     |
| Intel                 | 9        | 22.5%   |
| Qualcomm Atheros      | 3        | 7.5%    |
| Xiaomi                | 1        | 2.5%    |
| Huawei Technologies   | 1        | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24       | 60%     |
| Intel I211 Gigabit Network Connection                             | 4        | 10%     |
| Intel Ethernet Controller I225-V                                  | 2        | 5%      |
| Intel Ethernet Connection I217-LM                                 | 2        | 5%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.5%    |
| Intel PRO/100 VE Network Connection                               | 1        | 2.5%    |
| Huawei ELS-NX9                                                    | 1        | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 66.07%  |
| WiFi     | 19       | 33.93%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 70%     |
| WiFi     | 12       | 30%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 59.46%  |
| 2     | 13       | 35.14%  |
| 3     | 2        | 5.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 65.79%  |
| Yes  | 13       | 34.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 35.29%  |
| Cambridge Silicon Radio         | 4        | 23.53%  |
| Qualcomm Atheros Communications | 2        | 11.76%  |
| Broadcom                        | 2        | 11.76%  |
| Realtek Semiconductor           | 1        | 5.88%   |
| MediaTek                        | 1        | 5.88%   |
| ASUSTek Computer                | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 23.53%  |
| Intel Bluetooth wireless interface                  | 2        | 11.76%  |
| Intel AX200 Bluetooth                               | 2        | 11.76%  |
| Realtek Bluetooth Radio                             | 1        | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 5.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 5.88%   |
| MediaTek Wireless_Device                            | 1        | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.88%   |
| Broadcom BCM92045B3 ROM                             | 1        | 5.88%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 5.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 21       | 36.21%  |
| Intel               | 19       | 32.76%  |
| Nvidia              | 10       | 17.24%  |
| Texas Instruments   | 2        | 3.45%   |
| C-Media Electronics | 2        | 3.45%   |
| Blue Microphones    | 2        | 3.45%   |
| Tenx Technology     | 1        | 1.72%   |
| Cooler Master       | 1        | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 7.69%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 7.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 6.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 5.13%   |
| AMD FCH Azalia Controller                                                  | 4        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 3.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 3.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 3.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.56%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 2.56%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.56%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 2.56%   |
| Texas Instruments PCM2904 Audio Codec                                      | 1        | 1.28%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.28%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.28%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.28%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.28%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.28%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.28%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.28%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.28%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.28%   |
| Cooler Master CH321                                                        | 1        | 1.28%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 1.28%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.28%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.28%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.28%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 1.28%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.28%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.28%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 3        | 25%     |
| Kingston            | 2        | 16.67%  |
| Crucial             | 2        | 16.67%  |
| Transcend           | 1        | 8.33%   |
| Samsung Electronics | 1        | 8.33%   |
| Patriot             | 1        | 8.33%   |
| Corsair             | 1        | 8.33%   |
| A-DATA Technology   | 1        | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 7.69%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 1        | 7.69%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s     | 1        | 7.69%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM 1600MT/s           | 1        | 7.69%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 7.69%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s    | 1        | 7.69%   |
| Kingston RAM KHX1866C9D3/4GX 4GB DIMM 1867MT/s         | 1        | 7.69%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s    | 1        | 7.69%   |
| Kingston RAM 9905403-176.A00LF 2GB DIMM DDR3 1333MT/s  | 1        | 7.69%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s  | 1        | 7.69%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8GB DIMM DDR4 3400MT/s | 1        | 7.69%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s  | 1        | 7.69%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 54.55%  |
| DDR4    | 4        | 36.36%  |
| Unknown | 1        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 11       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 6        | 46.15%  |
| 4096 | 5        | 38.46%  |
| 2048 | 1        | 7.69%   |
| 1024 | 1        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 30.77%  |
| 2400  | 2        | 15.38%  |
| 3600  | 1        | 7.69%   |
| 3400  | 1        | 7.69%   |
| 3200  | 1        | 7.69%   |
| 1867  | 1        | 7.69%   |
| 1866  | 1        | 7.69%   |
| 1333  | 1        | 7.69%   |
| 667   | 1        | 7.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP LaserJet 1018 | 1        | 100%    |

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

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Focal-systems.Corp | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Focal-systems.Corp FT9201Fingerprint. | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Aktiv  | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Aktiv Rutoken lite | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 32       | 84.21%  |
| 1     | 4        | 10.53%  |
| 3     | 1        | 2.63%   |
| 2     | 1        | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 5        | 45.45%  |
| Multimedia controller | 2        | 18.18%  |
| Graphics card         | 1        | 9.09%   |
| Fingerprint reader    | 1        | 9.09%   |
| Chipcard              | 1        | 9.09%   |
| Camera                | 1        | 9.09%   |

