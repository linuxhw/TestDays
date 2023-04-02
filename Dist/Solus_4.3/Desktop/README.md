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

Total: 59

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | TUF Gaming B550-PLUS        | [dbf0b56c64](https://linux-hardware.org/?probe=dbf0b56c64) | Mar 24, 2023 |
| Gigabyte   | EP45-UD3P                   | [da7b0aca1f](https://linux-hardware.org/?probe=da7b0aca1f) | Feb 03, 2023 |
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
| 6.0.11-225.current  | 6        | 14.29%  |
| 5.15.32-213.current | 5        | 11.9%   |
| 5.14.21-210.current | 4        | 9.52%   |
| 5.14.16-205.current | 4        | 9.52%   |
| 6.1.5-229.current   | 3        | 7.14%   |
| 5.13.12-193.current | 3        | 7.14%   |
| 5.15.50-216.current | 2        | 4.76%   |
| 5.15.43-215.current | 2        | 4.76%   |
| 5.15.30-212.current | 2        | 4.76%   |
| 5.14.14-202.current | 2        | 4.76%   |
| 5.13.6-190.current  | 2        | 4.76%   |
| 5.13.1-187.current  | 2        | 4.76%   |
| 5.15.77-219.current | 1        | 2.38%   |
| 5.15.68-218.current | 1        | 2.38%   |
| 5.15.37-214.current | 1        | 2.38%   |
| 5.15.26-211.current | 1        | 2.38%   |
| 5.13.8-191.current  | 1        | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.11  | 6        | 14.29%  |
| 5.15.32 | 5        | 11.9%   |
| 5.14.21 | 4        | 9.52%   |
| 5.14.16 | 4        | 9.52%   |
| 6.1.5   | 3        | 7.14%   |
| 5.13.12 | 3        | 7.14%   |
| 5.15.50 | 2        | 4.76%   |
| 5.15.43 | 2        | 4.76%   |
| 5.15.30 | 2        | 4.76%   |
| 5.14.14 | 2        | 4.76%   |
| 5.13.6  | 2        | 4.76%   |
| 5.13.1  | 2        | 4.76%   |
| 5.15.77 | 1        | 2.38%   |
| 5.15.68 | 1        | 2.38%   |
| 5.15.37 | 1        | 2.38%   |
| 5.15.26 | 1        | 2.38%   |
| 5.13.8  | 1        | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 14       | 34.15%  |
| 5.14    | 10       | 24.39%  |
| 5.13    | 8        | 19.51%  |
| 6.0     | 6        | 14.63%  |
| 6.1     | 3        | 7.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 38       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Budgie  | 24       | 63.16%  |
| GNOME   | 7        | 18.42%  |
| KDE5    | 3        | 7.89%   |
| MATE    | 2        | 5.26%   |
| KDE     | 1        | 2.63%   |
| Unknown | 1        | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 37       | 97.37%  |
| Wayland | 1        | 2.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 71.05%  |
| LightDM | 6        | 15.79%  |
| GDM     | 3        | 7.89%   |
| SDDM    | 2        | 5.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 17       | 43.59%  |
| ru_RU | 3        | 7.69%   |
| ro_RO | 3        | 7.69%   |
| es_ES | 3        | 7.69%   |
| fr_FR | 2        | 5.13%   |
| en_GB | 2        | 5.13%   |
| de_DE | 2        | 5.13%   |
| pt_BR | 1        | 2.56%   |
| nl_NL | 1        | 2.56%   |
| fi_FI | 1        | 2.56%   |
| es_VE | 1        | 2.56%   |
| en_DK | 1        | 2.56%   |
| ar_SA | 1        | 2.56%   |
| ar_EG | 1        | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 22       | 57.89%  |
| EFI  | 16       | 42.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 36       | 94.74%  |
| Xfs   | 1        | 2.63%   |
| Btrfs | 1        | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 74.36%  |
| MBR     | 7        | 17.95%  |
| GPT     | 3        | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 87.18%  |
| Yes       | 5        | 12.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 81.58%  |
| Yes       | 7        | 18.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 10       | 26.32%  |
| ASUSTek Computer    | 7        | 18.42%  |
| ASRock              | 6        | 15.79%  |
| MSI                 | 3        | 7.89%   |
| Lenovo              | 2        | 5.26%   |
| Hewlett-Packard     | 2        | 5.26%   |
| Unknown             | 2        | 5.26%   |
| MEGA                | 1        | 2.63%   |
| Intel               | 1        | 2.63%   |
| Fujitsu             | 1        | 2.63%   |
| eMachines           | 1        | 2.63%   |
| Dell                | 1        | 2.63%   |
| Biostar             | 1        | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 2        | 5.26%   |
| MSI MS-7B89                      | 1        | 2.63%   |
| MSI MS-7B85                      | 1        | 2.63%   |
| MSI MS-7A34                      | 1        | 2.63%   |
| MEGA G41T-M7 LGT                 | 1        | 2.63%   |
| Lenovo ThinkCentre M71e 3157G6S  | 1        | 2.63%   |
| Lenovo C50-30 F0B1002EFR         | 1        | 2.63%   |
| Intel D946GZIS AAD66165-302      | 1        | 2.63%   |
| HP ProDesk 490 G3 MT Business PC | 1        | 2.63%   |
| HP 750-171                       | 1        | 2.63%   |
| Gigabyte Z68AP-D3                | 1        | 2.63%   |
| Gigabyte P31-ES3G                | 1        | 2.63%   |
| Gigabyte H81M-S2V                | 1        | 2.63%   |
| Gigabyte H110M-DS2V              | 1        | 2.63%   |
| Gigabyte GA-MA770-UD3            | 1        | 2.63%   |
| Gigabyte GA-78LMT-USB3 6.0       | 1        | 2.63%   |
| Gigabyte F2A68HM-H               | 1        | 2.63%   |
| Gigabyte EP45-UD3P               | 1        | 2.63%   |
| Gigabyte B85M-D3H                | 1        | 2.63%   |
| Gigabyte B550M AORUS PRO-P       | 1        | 2.63%   |
| Fujitsu CELSIUS W530             | 1        | 2.63%   |
| eMachines EL1852G                | 1        | 2.63%   |
| Dell OptiPlex 9020               | 1        | 2.63%   |
| Biostar H61MLV2                  | 1        | 2.63%   |
| ASUS TUF Gaming X570-PRO         | 1        | 2.63%   |
| ASUS TUF Gaming B550-PLUS        | 1        | 2.63%   |
| ASUS TUF B450-PRO GAMING         | 1        | 2.63%   |
| ASUS ROG STRIX B450-F GAMING     | 1        | 2.63%   |
| ASUS P5G41T-M LX3                | 1        | 2.63%   |
| ASUS All Series                  | 1        | 2.63%   |
| ASUS A88X-PRO                    | 1        | 2.63%   |
| ASRock X570M Pro4                | 1        | 2.63%   |
| ASRock X300M-STX                 | 1        | 2.63%   |
| ASRock H81 Pro BTC R2.0          | 1        | 2.63%   |
| ASRock FM2A88X Extreme4+         | 1        | 2.63%   |
| ASRock FM2A88M-HD+ R3.0          | 1        | 2.63%   |
| ASRock B450 Gaming-ITX/ac        | 1        | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS TUF               | 3        | 7.89%   |
| Unknown                | 2        | 5.26%   |
| MSI MS-7B89            | 1        | 2.63%   |
| MSI MS-7B85            | 1        | 2.63%   |
| MSI MS-7A34            | 1        | 2.63%   |
| MEGA G41T-M7           | 1        | 2.63%   |
| Lenovo ThinkCentre     | 1        | 2.63%   |
| Lenovo C50-30          | 1        | 2.63%   |
| Intel D946GZIS         | 1        | 2.63%   |
| HP ProDesk             | 1        | 2.63%   |
| HP 750-171             | 1        | 2.63%   |
| Gigabyte Z68AP-D3      | 1        | 2.63%   |
| Gigabyte P31-ES3G      | 1        | 2.63%   |
| Gigabyte H81M-S2V      | 1        | 2.63%   |
| Gigabyte H110M-DS2V    | 1        | 2.63%   |
| Gigabyte GA-MA770-UD3  | 1        | 2.63%   |
| Gigabyte GA-78LMT-USB3 | 1        | 2.63%   |
| Gigabyte F2A68HM-H     | 1        | 2.63%   |
| Gigabyte EP45-UD3P     | 1        | 2.63%   |
| Gigabyte B85M-D3H      | 1        | 2.63%   |
| Gigabyte B550M         | 1        | 2.63%   |
| Fujitsu CELSIUS        | 1        | 2.63%   |
| eMachines EL1852G      | 1        | 2.63%   |
| Dell OptiPlex          | 1        | 2.63%   |
| Biostar H61MLV2        | 1        | 2.63%   |
| ASUS ROG               | 1        | 2.63%   |
| ASUS P5G41T-M          | 1        | 2.63%   |
| ASUS All               | 1        | 2.63%   |
| ASUS A88X-PRO          | 1        | 2.63%   |
| ASRock X570M           | 1        | 2.63%   |
| ASRock X300M-STX       | 1        | 2.63%   |
| ASRock H81             | 1        | 2.63%   |
| ASRock FM2A88X         | 1        | 2.63%   |
| ASRock FM2A88M-HD+     | 1        | 2.63%   |
| ASRock B450            | 1        | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 7        | 18.42%  |
| 2014 | 6        | 15.79%  |
| 2015 | 4        | 10.53%  |
| 2011 | 4        | 10.53%  |
| 2020 | 3        | 7.89%   |
| 2008 | 3        | 7.89%   |
| 2021 | 2        | 5.26%   |
| 2016 | 2        | 5.26%   |
| 2013 | 2        | 5.26%   |
| 2019 | 1        | 2.63%   |
| 2017 | 1        | 2.63%   |
| 2012 | 1        | 2.63%   |
| 2010 | 1        | 2.63%   |
| 2006 | 1        | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 38       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 38       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 10       | 26.32%  |
| 3.01-4.0   | 9        | 23.68%  |
| 8.01-16.0  | 7        | 18.42%  |
| 4.01-8.0   | 6        | 15.79%  |
| 32.01-64.0 | 5        | 13.16%  |
| 2.01-3.0   | 1        | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 18       | 43.9%   |
| 4.01-8.0  | 7        | 17.07%  |
| 3.01-4.0  | 7        | 17.07%  |
| 2.01-3.0  | 7        | 17.07%  |
| 8.01-16.0 | 1        | 2.44%   |
| 0.51-1.0  | 1        | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 29.27%  |
| 4      | 10       | 24.39%  |
| 2      | 10       | 24.39%  |
| 3      | 5        | 12.2%   |
| 5      | 3        | 7.32%   |
| 6      | 1        | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 56.41%  |
| Yes       | 17       | 43.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 38       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 50%     |
| No        | 19       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 58.97%  |
| Yes       | 16       | 41.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 8        | 21.05%  |
| Germany      | 4        | 10.53%  |
| Romania      | 3        | 7.89%   |
| Russia       | 2        | 5.26%   |
| Argentina    | 2        | 5.26%   |
| Venezuela    | 1        | 2.63%   |
| Thailand     | 1        | 2.63%   |
| Sweden       | 1        | 2.63%   |
| Spain        | 1        | 2.63%   |
| Saudi Arabia | 1        | 2.63%   |
| Philippines  | 1        | 2.63%   |
| Norway       | 1        | 2.63%   |
| Netherlands  | 1        | 2.63%   |
| Kazakhstan   | 1        | 2.63%   |
| Iran         | 1        | 2.63%   |
| India        | 1        | 2.63%   |
| Guyana       | 1        | 2.63%   |
| Greece       | 1        | 2.63%   |
| France       | 1        | 2.63%   |
| Finland      | 1        | 2.63%   |
| Denmark      | 1        | 2.63%   |
| Canada       | 1        | 2.63%   |
| Brazil       | 1        | 2.63%   |
| Albania      | 1        | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Constanța      | 3        | 7.5%    |
| Weil am Rhein   | 1        | 2.5%    |
| Warrensburg     | 1        | 2.5%    |
| Viby J          | 1        | 2.5%    |
| Toronto         | 1        | 2.5%    |
| Thessaloniki    | 1        | 2.5%    |
| Stockholm       | 1        | 2.5%    |
| Songkhla        | 1        | 2.5%    |
| Seville         | 1        | 2.5%    |
| Severna Park    | 1        | 2.5%    |
| San Justo       | 1        | 2.5%    |
| Portsmouth      | 1        | 2.5%    |
| Phoenix         | 1        | 2.5%    |
| Oslo            | 1        | 2.5%    |
| Orenburg        | 1        | 2.5%    |
| Ochten          | 1        | 2.5%    |
| Lohja           | 1        | 2.5%    |
| Lipa City       | 1        | 2.5%    |
| Lexington       | 1        | 2.5%    |
| Krefeld         | 1        | 2.5%    |
| Kozani          | 1        | 2.5%    |
| Kolkata         | 1        | 2.5%    |
| Khobar          | 1        | 2.5%    |
| Isidro Casanova | 1        | 2.5%    |
| Huntington Park | 1        | 2.5%    |
| Hamburg         | 1        | 2.5%    |
| Great Neck      | 1        | 2.5%    |
| Georgetown      | 1        | 2.5%    |
| Garland         | 1        | 2.5%    |
| Durrës         | 1        | 2.5%    |
| Dammam          | 1        | 2.5%    |
| Curitiba        | 1        | 2.5%    |
| Chita           | 1        | 2.5%    |
| Caracas         | 1        | 2.5%    |
| Caen            | 1        | 2.5%    |
| Bad Homburg     | 1        | 2.5%    |
| Atyrau          | 1        | 2.5%    |
| Arak            | 1        | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 21       | 30     | 24.71%  |
| Samsung Electronics         | 15       | 24     | 17.65%  |
| Seagate                     | 9        | 11     | 10.59%  |
| Kingston                    | 8        | 11     | 9.41%   |
| Crucial                     | 6        | 6      | 7.06%   |
| Toshiba                     | 3        | 3      | 3.53%   |
| SanDisk                     | 3        | 3      | 3.53%   |
| PNY                         | 2        | 2      | 2.35%   |
| Kingston Technology Company | 2        | 2      | 2.35%   |
| Hitachi                     | 2        | 2      | 2.35%   |
| Unknown                     | 1        | 1      | 1.18%   |
| SPCC Sol                    | 1        | 1      | 1.18%   |
| SK hynix                    | 1        | 1      | 1.18%   |
| Silicon Motion              | 1        | 1      | 1.18%   |
| Phison Electronics          | 1        | 1      | 1.18%   |
| Phison                      | 1        | 1      | 1.18%   |
| Patriot                     | 1        | 1      | 1.18%   |
| Micron Technology           | 1        | 1      | 1.18%   |
| Maxtor                      | 1        | 1      | 1.18%   |
| Intenso                     | 1        | 2      | 1.18%   |
| HFS512GD                    | 1        | 1      | 1.18%   |
| Emtec                       | 1        | 1      | 1.18%   |
| China                       | 1        | 1      | 1.18%   |
| A-DATA Technology           | 1        | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                         | 4        | 4.17%   |
| Seagate ST4000DM004-2CV104 4TB                    | 3        | 3.13%   |
| Samsung NVMe SSD Drive 500GB                      | 3        | 3.13%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2        | 2.08%   |
| WDC WD10EZEX-08M2NA0 1TB                          | 2        | 2.08%   |
| Toshiba DT01ACA050 500GB                          | 2        | 2.08%   |
| Seagate ST2000DM006-2DM164 2TB                    | 2        | 2.08%   |
| Kingston Company A2000 NVMe SSD 500GB             | 2        | 2.08%   |
| Kingston SA400S37480G 480GB SSD                   | 2        | 2.08%   |
| Kingston SA400S37240G 240GB SSD                   | 2        | 2.08%   |
| Crucial CT1000P1SSD8 1TB                          | 2        | 2.08%   |
| Crucial CT1000MX500SSD1 1TB                       | 2        | 2.08%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                  | 1        | 1.04%   |
| WDC WD6400AAKS-75A7B2 640GB                       | 1        | 1.04%   |
| WDC WD5000AVDS-63U7B1 500GB                       | 1        | 1.04%   |
| WDC WD5000AVCS-632DY1 500GB                       | 1        | 1.04%   |
| WDC WD5000AAKX-003CA0 500GB                       | 1        | 1.04%   |
| WDC WD40EZRZ-00GXCB0 4TB                          | 1        | 1.04%   |
| WDC WD3200AAJS-00YZCA0 320GB                      | 1        | 1.04%   |
| WDC WD32 00AAJS-00L7A0 320GB                      | 1        | 1.04%   |
| WDC WD3000GLFS-01F8U0 304GB                       | 1        | 1.04%   |
| WDC WD2500HHTZ-04N21V1 250GB                      | 1        | 1.04%   |
| WDC WD20EARX-00PASB0 2TB                          | 1        | 1.04%   |
| WDC WD2003FZEX-00Z4SA0 2TB                        | 1        | 1.04%   |
| WDC WD2003FZEX-00SRLA0 2TB                        | 1        | 1.04%   |
| WDC WD1600AAJS-00PSA0 160GB                       | 1        | 1.04%   |
| WDC WD1600AAJS-00M0A0 160GB                       | 1        | 1.04%   |
| WDC WD140EFGX-68B0GN0 14TB                        | 1        | 1.04%   |
| WDC WD10SPSX-00A6WT0 1TB                          | 1        | 1.04%   |
| WDC WD10EZRX-00L4HB0 1TB                          | 1        | 1.04%   |
| WDC WD10EZEX-21WN4A0 1TB                          | 1        | 1.04%   |
| WDC WD10EADS-00P8B0 1TB                           | 1        | 1.04%   |
| WDC WD10EADS-00M2B0 1TB                           | 1        | 1.04%   |
| WDC WD1003FBYX-01Y7B0 1TB                         | 1        | 1.04%   |
| WDC WD My Passport 25F3 512GB                     | 1        | 1.04%   |
| Unknown SD/MMC/MS PRO 64GB                        | 1        | 1.04%   |
| Toshiba DT01ACA100 1TB                            | 1        | 1.04%   |
| SPCC Sol id State Disk 1TB SSD                    | 1        | 1.04%   |
| SK hynix HFS512GD9TNG-L2A0A 512GB                 | 1        | 1.04%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1        | 1.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 28     | 52.63%  |
| Seagate             | 9        | 11     | 23.68%  |
| Toshiba             | 3        | 3      | 7.89%   |
| Hitachi             | 2        | 2      | 5.26%   |
| Unknown             | 1        | 1      | 2.63%   |
| Samsung Electronics | 1        | 1      | 2.63%   |
| Maxtor              | 1        | 1      | 2.63%   |
| Intenso             | 1        | 2      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 19     | 38.24%  |
| Kingston            | 6        | 9      | 17.65%  |
| Crucial             | 4        | 4      | 11.76%  |
| SanDisk             | 2        | 2      | 5.88%   |
| PNY                 | 2        | 2      | 5.88%   |
| WDC                 | 1        | 1      | 2.94%   |
| SPCC Sol            | 1        | 1      | 2.94%   |
| Patriot             | 1        | 1      | 2.94%   |
| Micron Technology   | 1        | 1      | 2.94%   |
| Emtec               | 1        | 1      | 2.94%   |
| China               | 1        | 1      | 2.94%   |
| A-DATA Technology   | 1        | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 30       | 49     | 44.12%  |
| SSD     | 24       | 43     | 35.29%  |
| NVMe    | 12       | 15     | 17.65%  |
| Unknown | 2        | 2      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 36       | 87     | 69.23%  |
| NVMe | 12       | 15     | 23.08%  |
| SAS  | 4        | 7      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 54     | 49.12%  |
| 0.51-1.0   | 16       | 22     | 28.07%  |
| 1.01-2.0   | 7        | 8      | 12.28%  |
| 3.01-4.0   | 4        | 5      | 7.02%   |
| 2.01-3.0   | 1        | 2      | 1.75%   |
| 10.01-20.0 | 1        | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 9        | 23.08%  |
| 101-250        | 9        | 23.08%  |
| 501-1000       | 7        | 17.95%  |
| 1001-2000      | 6        | 15.38%  |
| More than 3000 | 5        | 12.82%  |
| 21-50          | 1        | 2.56%   |
| 2001-3000      | 1        | 2.56%   |
| 51-100         | 1        | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 10       | 25%     |
| 1001-2000      | 7        | 17.5%   |
| 101-250        | 6        | 15%     |
| 501-1000       | 6        | 15%     |
| 21-50          | 4        | 10%     |
| 251-500        | 3        | 7.5%    |
| 51-100         | 3        | 7.5%    |
| More than 3000 | 1        | 2.5%    |

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
| Detected | 31       | 85     | 70.45%  |
| Works    | 11       | 22     | 25%     |
| Malfunc  | 2        | 2      | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 19       | 36.54%  |
| AMD                         | 19       | 36.54%  |
| Kingston Technology Company | 4        | 7.69%   |
| Samsung Electronics         | 2        | 3.85%   |
| Phison Electronics          | 2        | 3.85%   |
| Micron/Crucial Technology   | 2        | 3.85%   |
| SK hynix                    | 1        | 1.92%   |
| Silicon Motion              | 1        | 1.92%   |
| SanDisk                     | 1        | 1.92%   |
| JMicron Technology          | 1        | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 18.18%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 9.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 7.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 7.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 6.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 3.03%   |
| Phison E12 NVMe Controller                                                              | 2        | 3.03%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 3.03%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 3.03%   |
| AMD FCH IDE Controller                                                                  | 2        | 3.03%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 3.03%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 1.52%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.52%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.52%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1        | 1.52%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.52%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.52%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.52%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.52%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 31       | 58.49%  |
| NVMe | 11       | 20.75%  |
| IDE  | 11       | 20.75%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 50%     |
| AMD    | 19       | 50%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i3-4160 CPU @ 3.60GHz                | 2        | 5.26%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2        | 5.26%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz             | 1        | 2.63%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 2.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 2.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 2.63%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 2.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 2.63%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 2.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 2.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1        | 2.63%   |
| Intel Core i3-3210 CPU @ 3.20GHz                | 1        | 2.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 2.63%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 2.63%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1        | 2.63%   |
| Intel Core 2 CPU 4300 @ 1.80GHz                 | 1        | 2.63%   |
| Intel Celeron CPU G3930 @ 2.90GHz               | 1        | 2.63%   |
| Intel Celeron CPU E3400 @ 2.60GHz               | 1        | 2.63%   |
| Intel Celeron CPU E3300 @ 2.50GHz               | 1        | 2.63%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1        | 2.63%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 2.63%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 1        | 2.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1        | 2.63%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 1        | 2.63%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 2.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 2.63%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 2.63%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 2.63%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2.63%   |
| AMD Ryzen 3 4300GE with Radeon Graphics         | 1        | 2.63%   |
| AMD Phenom II X4 955 Processor                  | 1        | 2.63%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 2.63%   |
| AMD A8-7650K Radeon R7, 10 Compute Cores 4C+6G  | 1        | 2.63%   |
| AMD A10-7890K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.63%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.63%   |
| AMD A10-6800K APU with Radeon HD Graphics       | 1        | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 7             | 7        | 18.42%  |
| Intel Core i5           | 4        | 10.53%  |
| Intel Core i3           | 4        | 10.53%  |
| Intel Core i7           | 3        | 7.89%   |
| Intel Celeron           | 3        | 7.89%   |
| AMD Ryzen 5             | 3        | 7.89%   |
| AMD A10                 | 3        | 7.89%   |
| Intel Core 2 Quad       | 2        | 5.26%   |
| AMD Ryzen 9             | 2        | 5.26%   |
| Intel Xeon              | 1        | 2.63%   |
| Intel Pentium Dual-Core | 1        | 2.63%   |
| Intel Core 2            | 1        | 2.63%   |
| AMD Ryzen 3             | 1        | 2.63%   |
| AMD Phenom II X4        | 1        | 2.63%   |
| AMD FX                  | 1        | 2.63%   |
| AMD A8                  | 1        | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 36.84%  |
| 4      | 11       | 28.95%  |
| 8      | 8        | 21.05%  |
| 6      | 3        | 7.89%   |
| 12     | 1        | 2.63%   |
| 3      | 1        | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 71.05%  |
| 1      | 11       | 28.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 38       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 6        | 15%     |
| 0x1067a    | 4        | 10%     |
| 0x0800820d | 3        | 7.5%    |
| 0x06003106 | 3        | 7.5%    |
| 0x506e3    | 2        | 5%      |
| 0x206a7    | 2        | 5%      |
| 0x0a50000c | 2        | 5%      |
| 0x08701021 | 2        | 5%      |
| 0x08701013 | 2        | 5%      |
| 0x08600106 | 2        | 5%      |
| Unknown    | 2        | 5%      |
| 0x906e9    | 1        | 2.5%    |
| 0x6f2      | 1        | 2.5%    |
| 0x40651    | 1        | 2.5%    |
| 0x306a9    | 1        | 2.5%    |
| 0x0a201204 | 1        | 2.5%    |
| 0x0a201016 | 1        | 2.5%    |
| 0x0800820b | 1        | 2.5%    |
| 0x06001119 | 1        | 2.5%    |
| 0x06000852 | 1        | 2.5%    |
| 0x010000c8 | 1        | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 7        | 18.42%  |
| Zen 2       | 6        | 15.79%  |
| Penryn      | 5        | 13.16%  |
| Zen 3       | 4        | 10.53%  |
| Zen+        | 3        | 7.89%   |
| Steamroller | 3        | 7.89%   |
| Skylake     | 2        | 5.26%   |
| SandyBridge | 2        | 5.26%   |
| Piledriver  | 2        | 5.26%   |
| KabyLake    | 1        | 2.63%   |
| K10         | 1        | 2.63%   |
| IvyBridge   | 1        | 2.63%   |
| Core        | 1        | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 19       | 43.18%  |
| Nvidia | 13       | 29.55%  |
| Intel  | 12       | 27.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 6.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 6.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 4.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.55%   |
| AMD Renoir                                                                  | 2        | 4.55%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 4.55%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 4.55%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.27%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 2.27%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.27%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 1        | 2.27%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 2.27%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 2.27%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1        | 2.27%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 2.27%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 2.27%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 2.27%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 1        | 2.27%   |
| Intel HD Graphics 530                                                       | 1        | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 2.27%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 2.27%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 2.27%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 2.27%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 2.27%   |
| AMD Richland [Radeon HD 8670D]                                              | 1        | 2.27%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 2.27%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 2.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.27%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 2.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 2.27%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 18       | 47.37%  |
| 1 x Nvidia     | 11       | 28.95%  |
| 1 x Intel      | 6        | 15.79%  |
| Intel + Nvidia | 2        | 5.26%   |
| Intel + AMD    | 1        | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 30       | 78.95%  |
| Proprietary | 8        | 21.05%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 9        | 23.68%  |
| 0.51-1.0   | 8        | 21.05%  |
| Unknown    | 7        | 18.42%  |
| 7.01-8.0   | 4        | 10.53%  |
| 3.01-4.0   | 4        | 10.53%  |
| 5.01-6.0   | 2        | 5.26%   |
| 8.01-16.0  | 2        | 5.26%   |
| 0.01-0.5   | 2        | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 17.39%  |
| Goldstar             | 8        | 17.39%  |
| AOC                  | 8        | 17.39%  |
| Dell                 | 3        | 6.52%   |
| Ancor Communications | 3        | 6.52%   |
| Acer                 | 3        | 6.52%   |
| NEC Computers        | 2        | 4.35%   |
| BenQ                 | 2        | 4.35%   |
| Unknown              | 2        | 4.35%   |
| Sharp                | 1        | 2.17%   |
| Philips              | 1        | 2.17%   |
| Microstep            | 1        | 2.17%   |
| LG Electronics       | 1        | 2.17%   |
| Lenovo               | 1        | 2.17%   |
| Hewlett-Packard      | 1        | 2.17%   |
| ASUSTek Computer     | 1        | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 3        | 6.12%   |
| Goldstar L227W GSM566E 1680x1050 474x296mm 22.0-inch                 | 2        | 4.08%   |
| Unknown                                                              | 2        | 4.08%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM029A 1920x1200 582x364mm 27.0-inch | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1        | 2.04%   |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch   | 1        | 2.04%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1        | 2.04%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                   | 1        | 2.04%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1        | 2.04%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch           | 1        | 2.04%   |
| Microstep LCD Monitor MSI G241                                       | 1        | 2.04%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 2.04%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 1        | 2.04%   |
| Hewlett-Packard 24yh HPN3504 1920x1080 528x297mm 23.9-inch           | 1        | 2.04%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1        | 2.04%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1        | 2.04%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 2.04%   |
| Goldstar L227W GSM566F 1680x1050 474x296mm 22.0-inch                 | 1        | 2.04%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1        | 2.04%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 2.04%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                  | 1        | 2.04%   |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                  | 1        | 2.04%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                    | 1        | 2.04%   |
| BenQ LCD Monitor T2200HD 5760x1080                                   | 1        | 2.04%   |
| BenQ LCD Monitor T2200HD                                             | 1        | 2.04%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 2.04%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 1        | 2.04%   |
| ASUSTek Computer MG248 AUS24A3 1920x1080 531x299mm 24.0-inch         | 1        | 2.04%   |
| AOC Q29G2G5 AOC2902 2560x1080 681x287mm 29.1-inch                    | 1        | 2.04%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 1        | 2.04%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 1        | 2.04%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 1        | 2.04%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                     | 1        | 2.04%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 2.04%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch     | 1        | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 39.13%  |
| 2560x1440 (QHD)    | 5        | 10.87%  |
| 1680x1050 (WSXGA+) | 4        | 8.7%    |
| 1280x1024 (SXGA)   | 4        | 8.7%    |
| 1366x768 (WXGA)    | 3        | 6.52%   |
| 3840x2160 (4K)     | 2        | 4.35%   |
| Unknown            | 2        | 4.35%   |
| 5760x1080          | 1        | 2.17%   |
| 3840x1080          | 1        | 2.17%   |
| 2560x1080          | 1        | 2.17%   |
| 1920x1200 (WUXGA)  | 1        | 2.17%   |
| 1600x900 (HD+)     | 1        | 2.17%   |
| 1440x900 (WXGA+)   | 1        | 2.17%   |
| 1360x768           | 1        | 2.17%   |
| 1024x768 (XGA)     | 1        | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 19.05%  |
| Unknown | 8        | 19.05%  |
| 27      | 5        | 11.9%   |
| 23      | 4        | 9.52%   |
| 18      | 4        | 9.52%   |
| 22      | 3        | 7.14%   |
| 21      | 3        | 7.14%   |
| 17      | 2        | 4.76%   |
| 31      | 1        | 2.38%   |
| 29      | 1        | 2.38%   |
| 20      | 1        | 2.38%   |
| 19      | 1        | 2.38%   |
| 15      | 1        | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 38.1%   |
| 401-500     | 12       | 28.57%  |
| Unknown     | 8        | 19.05%  |
| 301-350     | 3        | 7.14%   |
| 601-700     | 2        | 4.76%   |
| 351-400     | 1        | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 46.51%  |
| 16/10   | 9        | 20.93%  |
| Unknown | 8        | 18.6%   |
| 5/4     | 3        | 6.98%   |
| 4/3     | 1        | 2.33%   |
| 3/2     | 1        | 2.33%   |
| 21/9    | 1        | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 32.56%  |
| Unknown        | 8        | 18.6%   |
| 301-350        | 6        | 13.95%  |
| 141-150        | 5        | 11.63%  |
| 251-300        | 4        | 9.3%    |
| 151-200        | 4        | 9.3%    |
| 351-500        | 1        | 2.33%   |
| 101-110        | 1        | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 27       | 65.85%  |
| Unknown | 8        | 19.51%  |
| 101-120 | 5        | 12.2%   |
| 161-240 | 1        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 65.79%  |
| 2     | 12       | 31.58%  |
| 3     | 1        | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 29       | 49.15%  |
| Intel                 | 14       | 23.73%  |
| Qualcomm Atheros      | 7        | 11.86%  |
| MediaTek              | 2        | 3.39%   |
| Xiaomi                | 1        | 1.69%   |
| Ralink Technology     | 1        | 1.69%   |
| Linksys               | 1        | 1.69%   |
| Huawei Technologies   | 1        | 1.69%   |
| D-Link System         | 1        | 1.69%   |
| Broadcom              | 1        | 1.69%   |
| Belkin Components     | 1        | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                       | 24       | 35.29%  |
| Intel I211 Gigabit Network Connection                                                   | 4        | 5.88%   |
| Intel Wi-Fi 6 AX200                                                                     | 3        | 4.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                                       | 2        | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2        | 2.94%   |
| Intel Wireless 3165                                                                     | 2        | 2.94%   |
| Intel Ethernet Controller I225-V                                                        | 2        | 2.94%   |
| Intel Ethernet Connection I217-LM                                                       | 2        | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                          | 1        | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 1.47%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                   | 1        | 1.47%   |
| Realtek 802.11ac NIC                                                                    | 1        | 1.47%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                               | 1        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 1.47%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 1        | 1.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                              | 1        | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                           | 1        | 1.47%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                              | 1        | 1.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 1.47%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 1.47%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 1.47%   |
| Intel Wireless-AC 9260                                                                  | 1        | 1.47%   |
| Intel Wireless 7265                                                                     | 1        | 1.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                           | 1        | 1.47%   |
| Intel PRO/100 VE Network Connection                                                     | 1        | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 1.47%   |
| Huawei ANA-NX9                                                                          | 1        | 1.47%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 1.47%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 30.77%  |
| Realtek Semiconductor | 6        | 23.08%  |
| Qualcomm Atheros      | 5        | 19.23%  |
| MediaTek              | 2        | 7.69%   |
| Ralink Technology     | 1        | 3.85%   |
| Linksys               | 1        | 3.85%   |
| D-Link System         | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |
| Belkin Components     | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 3        | 11.11%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 7.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2        | 7.41%   |
| Intel Wireless 3165                                                                     | 2        | 7.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 3.7%    |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 3.7%    |
| Realtek 802.11ac NIC                                                                    | 1        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 3.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 1        | 3.7%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                              | 1        | 3.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 3.7%    |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 3.7%    |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 3.7%    |
| Intel Wireless-AC 9260                                                                  | 1        | 3.7%    |
| Intel Wireless 7265                                                                     | 1        | 3.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                           | 1        | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 3.7%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 3.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 3.7%    |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 65.85%  |
| Intel                 | 9        | 21.95%  |
| Qualcomm Atheros      | 3        | 7.32%   |
| Xiaomi                | 1        | 2.44%   |
| Huawei Technologies   | 1        | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24       | 58.54%  |
| Intel I211 Gigabit Network Connection                             | 4        | 9.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 4.88%   |
| Intel Ethernet Controller I225-V                                  | 2        | 4.88%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 4.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.44%   |
| Intel PRO/100 VE Network Connection                               | 1        | 2.44%   |
| Huawei ANA-NX9                                                    | 1        | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 65.52%  |
| WiFi     | 20       | 34.48%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 70.73%  |
| WiFi     | 12       | 29.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 57.89%  |
| 2     | 14       | 36.84%  |
| 3     | 2        | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 64.1%   |
| Yes  | 14       | 35.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 38.89%  |
| Cambridge Silicon Radio         | 4        | 22.22%  |
| Qualcomm Atheros Communications | 2        | 11.11%  |
| Broadcom                        | 2        | 11.11%  |
| Realtek Semiconductor           | 1        | 5.56%   |
| MediaTek                        | 1        | 5.56%   |
| ASUSTek Computer                | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 22.22%  |
| Intel Bluetooth wireless interface                  | 3        | 16.67%  |
| Intel AX200 Bluetooth                               | 2        | 11.11%  |
| Realtek Bluetooth Radio                             | 1        | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 5.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 5.56%   |
| MediaTek Wireless_Device                            | 1        | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.56%   |
| Broadcom BCM92045B3 ROM                             | 1        | 5.56%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 5.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 22       | 36.67%  |
| Intel               | 19       | 31.67%  |
| Nvidia              | 11       | 18.33%  |
| Texas Instruments   | 2        | 3.33%   |
| C-Media Electronics | 2        | 3.33%   |
| Blue Microphones    | 2        | 3.33%   |
| Tenx Technology     | 1        | 1.67%   |
| Cooler Master       | 1        | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 7.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 7.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 6.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 4.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 4.94%   |
| AMD FCH Azalia Controller                                                  | 4        | 4.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 3.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 3.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.47%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 2.47%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.47%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 2.47%   |
| Texas Instruments PCM2904 Audio Codec                                      | 1        | 1.23%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.23%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.23%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.23%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.23%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.23%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.23%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.23%   |
| Cooler Master CH321                                                        | 1        | 1.23%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 1.23%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.23%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.23%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 1.23%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.23%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.23%   |

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
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s      | 1        | 7.69%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 7.69%   |
| Patriot RAM 2133 CL11 Series 8GB DIMM DDR3 2400MT/s    | 1        | 7.69%   |
| Kingston RAM KHX1866C9D3/4GX 4GB DIMM DDR3 1867MT/s    | 1        | 7.69%   |
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
| 0     | 33       | 84.62%  |
| 1     | 4        | 10.26%  |
| 3     | 1        | 2.56%   |
| 2     | 1        | 2.56%   |

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

