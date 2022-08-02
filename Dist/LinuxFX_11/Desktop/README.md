LinuxFX 11 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for LinuxFX 11.

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

Total: 62

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| ASUSTek  | M5A97                | [bcca05b660](https://linux-hardware.org/?probe=bcca05b660) | Jun 19, 2022 |
| ASUSTek  | M5A97                | [adc58c941b](https://linux-hardware.org/?probe=adc58c941b) | Jun 07, 2022 |
| ASUSTek  | M5A78L-M/USB3        | [07a415d261](https://linux-hardware.org/?probe=07a415d261) | Jun 02, 2022 |
| Lenovo   | MAHOBAY NO DPK       | [d9ed530aa9](https://linux-hardware.org/?probe=d9ed530aa9) | May 04, 2022 |
| Intel    | DB85FL AAG89861-203  | [7d75948e9a](https://linux-hardware.org/?probe=7d75948e9a) | May 01, 2022 |
| Intel    | DB85FL AAG89861-203  | [1d3dfb69e7](https://linux-hardware.org/?probe=1d3dfb69e7) | May 01, 2022 |
| MSI      | X58M                 | [d4146d0724](https://linux-hardware.org/?probe=d4146d0724) | Apr 05, 2022 |
| ASUSTek  | PRIME B450M-A II     | [18d216846f](https://linux-hardware.org/?probe=18d216846f) | Mar 23, 2022 |
| ASUSTek  | P5G41T-M LX          | [cfd96dd963](https://linux-hardware.org/?probe=cfd96dd963) | Mar 08, 2022 |
| ASUSTek  | PRIME A320M-K        | [65b41a7a67](https://linux-hardware.org/?probe=65b41a7a67) | Feb 26, 2022 |
| ASUSTek  | P7H55-M PRO          | [a3ebde02ae](https://linux-hardware.org/?probe=a3ebde02ae) | Feb 15, 2022 |
| Dell     | 0JP3NX A01           | [b7696b0129](https://linux-hardware.org/?probe=b7696b0129) | Feb 14, 2022 |
| Dell     | 0JP3NX A01           | [504bb820fe](https://linux-hardware.org/?probe=504bb820fe) | Feb 14, 2022 |
| Intel    | DP55WB AAE64798-205  | [bd77a66760](https://linux-hardware.org/?probe=bd77a66760) | Feb 12, 2022 |
| Gigabyte | F2A78M-D3H           | [f508e8a6f8](https://linux-hardware.org/?probe=f508e8a6f8) | Jan 31, 2022 |
| ASRock   | X370 Gaming X        | [67d9bb3ace](https://linux-hardware.org/?probe=67d9bb3ace) | Jan 30, 2022 |
| MSI      | MPG X570 GAMING PLUS | [86e6d5c19a](https://linux-hardware.org/?probe=86e6d5c19a) | Jan 23, 2022 |
| MSI      | Z77A-G45             | [a397ea4233](https://linux-hardware.org/?probe=a397ea4233) | Jan 22, 2022 |
| ASRock   | 980DE3/U3S3          | [b7e4b6f2f1](https://linux-hardware.org/?probe=b7e4b6f2f1) | Jan 13, 2022 |
| Intel    | DQ57TM AAE92694-400  | [59ef421003](https://linux-hardware.org/?probe=59ef421003) | Jan 12, 2022 |
| Google   | Teemo                | [0f67b5ae59](https://linux-hardware.org/?probe=0f67b5ae59) | Jan 10, 2022 |
| ABIT     | AW9D-MAX             | [104f0e6fde](https://linux-hardware.org/?probe=104f0e6fde) | Jan 01, 2022 |
| Foxconn  | D270S/D250S MP       | [82580ebcb5](https://linux-hardware.org/?probe=82580ebcb5) | Dec 28, 2021 |
| MSI      | X470 GAMING PLUS MAX | [dd7335ec13](https://linux-hardware.org/?probe=dd7335ec13) | Dec 27, 2021 |
| Gigabyte | GA-970A-D3           | [135d34c579](https://linux-hardware.org/?probe=135d34c579) | Dec 26, 2021 |
| ASRock   | N68-S3 UCC           | [ae1acd8bbe](https://linux-hardware.org/?probe=ae1acd8bbe) | Dec 24, 2021 |
| HP       | 2AF7                 | [3b7ab440c6](https://linux-hardware.org/?probe=3b7ab440c6) | Dec 23, 2021 |
| Pegatron | Maureen              | [4bb6b10ba4](https://linux-hardware.org/?probe=4bb6b10ba4) | Dec 23, 2021 |
| Positivo | POS-EIBTPDC          | [882c4d6758](https://linux-hardware.org/?probe=882c4d6758) | Dec 17, 2021 |
| Dell     | 0R6JMP A00           | [7bc4106877](https://linux-hardware.org/?probe=7bc4106877) | Dec 12, 2021 |
| Dell     | 0R6JMP A00           | [2b3e03c89b](https://linux-hardware.org/?probe=2b3e03c89b) | Dec 12, 2021 |
| ASUSTek  | CM6650               | [ef34d60843](https://linux-hardware.org/?probe=ef34d60843) | Dec 09, 2021 |
| Dell     | 040DDP A01           | [6808d41bfe](https://linux-hardware.org/?probe=6808d41bfe) | Dec 08, 2021 |
| Gigabyte | GA-970A-D3           | [543f25da6d](https://linux-hardware.org/?probe=543f25da6d) | Dec 06, 2021 |
| ASUSTek  | H110-PLUS            | [78a4619b31](https://linux-hardware.org/?probe=78a4619b31) | Dec 05, 2021 |
| Gigabyte | GA-970A-D3           | [f4b7b56b1b](https://linux-hardware.org/?probe=f4b7b56b1b) | Dec 05, 2021 |
| Acer     | Aspire X1930         | [68d51a9af5](https://linux-hardware.org/?probe=68d51a9af5) | Dec 03, 2021 |
| Intel    | H55                  | [57390a46ad](https://linux-hardware.org/?probe=57390a46ad) | Dec 02, 2021 |
| ASRock   | Q1900-ITX            | [878cd074fb](https://linux-hardware.org/?probe=878cd074fb) | Nov 30, 2021 |
| ASRock   | Q1900-ITX            | [3468f76ee4](https://linux-hardware.org/?probe=3468f76ee4) | Nov 30, 2021 |
| Positivo | POS-EIBTPDC          | [1e36050d80](https://linux-hardware.org/?probe=1e36050d80) | Nov 18, 2021 |
| Positivo | POS-PIQ67CG POSITIVO | [bcec39d0de](https://linux-hardware.org/?probe=bcec39d0de) | Nov 16, 2021 |
| Positivo | POS-PIQ67CG POSITIVO | [8f7dd03e2d](https://linux-hardware.org/?probe=8f7dd03e2d) | Nov 15, 2021 |
| HP       | 8054                 | [0a502d18dd](https://linux-hardware.org/?probe=0a502d18dd) | Nov 03, 2021 |
| ASUSTek  | M5A78L-M PLUS/USB3   | [24fe21040d](https://linux-hardware.org/?probe=24fe21040d) | Oct 30, 2021 |
| Pegatron | 2A99                 | [29fd6eae29](https://linux-hardware.org/?probe=29fd6eae29) | Oct 27, 2021 |
| Gigabyte | B85-HD3-A            | [23bb246149](https://linux-hardware.org/?probe=23bb246149) | Oct 20, 2021 |
| Gigabyte | H61M-S2PV            | [d08969a0a4](https://linux-hardware.org/?probe=d08969a0a4) | Oct 17, 2021 |
| Intel    | DG35EC AAE29266-202  | [d61f31abf0](https://linux-hardware.org/?probe=d61f31abf0) | Oct 10, 2021 |
| Intel    | DG35EC AAE29266-202  | [24fa8f8f31](https://linux-hardware.org/?probe=24fa8f8f31) | Oct 10, 2021 |
| MSI      | P67A-GD65            | [13a07c6b4d](https://linux-hardware.org/?probe=13a07c6b4d) | Oct 09, 2021 |
| MSI      | 970 GAMING           | [0778440642](https://linux-hardware.org/?probe=0778440642) | Oct 02, 2021 |
| Intel    | DG35EC AAE29266-202  | [f29471dfd6](https://linux-hardware.org/?probe=f29471dfd6) | Oct 01, 2021 |
| Dell     | 0DN075               | [1d0145e3e0](https://linux-hardware.org/?probe=1d0145e3e0) | Oct 01, 2021 |
| MSI      | G31TM-P25            | [efe15b35ca](https://linux-hardware.org/?probe=efe15b35ca) | Sep 29, 2021 |
| ASRock   | A55M-HVS             | [3061a2007b](https://linux-hardware.org/?probe=3061a2007b) | Sep 27, 2021 |
| ASRock   | A55M-HVS             | [a367ec462a](https://linux-hardware.org/?probe=a367ec462a) | Sep 23, 2021 |
| ASRock   | A55M-HVS             | [f0081639fb](https://linux-hardware.org/?probe=f0081639fb) | Sep 22, 2021 |
| MSI      | P67A-GD65            | [b23b139081](https://linux-hardware.org/?probe=b23b139081) | Sep 20, 2021 |
| MSI      | P67A-GD65            | [e42a9da750](https://linux-hardware.org/?probe=e42a9da750) | Sep 20, 2021 |
| Gigabyte | 970A-D3              | [8daebb1450](https://linux-hardware.org/?probe=8daebb1450) | Sep 19, 2021 |
| MSI      | Z270-A PRO           | [6488569b77](https://linux-hardware.org/?probe=6488569b77) | Sep 19, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-43-generic | 6        | 12.77%  |
| 5.11.0-41-generic | 6        | 12.77%  |
| 5.11.0-37-generic | 6        | 12.77%  |
| 5.11.0-40-generic | 5        | 10.64%  |
| 5.13.0-28-generic | 4        | 8.51%   |
| 5.13.0-27-generic | 4        | 8.51%   |
| 5.11.0-38-generic | 4        | 8.51%   |
| 5.11.0-34-generic | 3        | 6.38%   |
| 5.13.0-44-generic | 2        | 4.26%   |
| 5.13.0-30-generic | 2        | 4.26%   |
| 5.11.0-46-generic | 2        | 4.26%   |
| 5.13.0-40-generic | 1        | 2.13%   |
| 5.13.0-39-generic | 1        | 2.13%   |
| 5.11.0-36-generic | 1        | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 32       | 69.57%  |
| 5.13.0  | 14       | 30.43%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 32       | 69.57%  |
| 5.13    | 14       | 30.43%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 46       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 44       | 93.62%  |
| KDE  | 3        | 6.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 46       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 82.61%  |
| SDDM    | 8        | 17.39%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 13       | 28.26%  |
| pt_BR | 7        | 15.22%  |
| C     | 4        | 8.7%    |
| fr_FR | 3        | 6.52%   |
| en_GB | 3        | 6.52%   |
| de_DE | 3        | 6.52%   |
| it_IT | 2        | 4.35%   |
| en_CA | 2        | 4.35%   |
| sv_SE | 1        | 2.17%   |
| ru_RU | 1        | 2.17%   |
| pl_PL | 1        | 2.17%   |
| nl_NL | 1        | 2.17%   |
| es_MX | 1        | 2.17%   |
| es_ES | 1        | 2.17%   |
| es_AR | 1        | 2.17%   |
| en_ZA | 1        | 2.17%   |
| en_IN | 1        | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 32       | 69.57%  |
| EFI  | 14       | 30.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 44       | 95.65%  |
| Overlay | 2        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 97.83%  |
| GPT     | 1        | 2.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 91.3%   |
| Yes       | 4        | 8.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 86.96%  |
| Yes       | 6        | 13.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 8        | 17.39%  |
| ASUSTek Computer    | 8        | 17.39%  |
| Intel               | 5        | 10.87%  |
| Gigabyte Technology | 5        | 10.87%  |
| ASRock              | 5        | 10.87%  |
| Dell                | 4        | 8.7%    |
| Positivo            | 2        | 4.35%   |
| Pegatron            | 2        | 4.35%   |
| Hewlett-Packard     | 2        | 4.35%   |
| Lenovo              | 1        | 2.17%   |
| Google              | 1        | 2.17%   |
| Foxconn             | 1        | 2.17%   |
| Acer                | 1        | 2.17%   |
| ABIT                | 1        | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Positivo POS-PIQ67CG           | 1        | 2.17%   |
| Positivo POS-EIBTPDC           | 1        | 2.17%   |
| Pegatron p6745br               | 1        | 2.17%   |
| Pegatron NC045AA-ABU IQ525uk   | 1        | 2.17%   |
| MSI MS-7C37                    | 1        | 2.17%   |
| MSI MS-7B79                    | 1        | 2.17%   |
| MSI MS-7A71                    | 1        | 2.17%   |
| MSI MS-7752                    | 1        | 2.17%   |
| MSI MS-7693                    | 1        | 2.17%   |
| MSI MS-7681                    | 1        | 2.17%   |
| MSI MS-7593                    | 1        | 2.17%   |
| MSI MS-7529                    | 1        | 2.17%   |
| Lenovo ThinkCentre M82 2929AZ6 | 1        | 2.17%   |
| Intel H55                      | 1        | 2.17%   |
| Intel DP55WB AAE64798-205      | 1        | 2.17%   |
| Intel DG35EC AAE29266-202      | 1        | 2.17%   |
| Intel DESKTOP 300              | 1        | 2.17%   |
| Intel DB85FL AAG89861-203      | 1        | 2.17%   |
| HP EliteDesk 800 G2 SFF        | 1        | 2.17%   |
| HP 700-214                     | 1        | 2.17%   |
| Google Teemo                   | 1        | 2.17%   |
| Gigabyte H61M-S2PV             | 1        | 2.17%   |
| Gigabyte GA-970A-D3            | 1        | 2.17%   |
| Gigabyte F2A78M-D3H            | 1        | 2.17%   |
| Gigabyte 970A-D3               | 1        | 2.17%   |
| Gigabyte 7200-5121B            | 1        | 2.17%   |
| Foxconn D270S/D250S MP         | 1        | 2.17%   |
| Dell Precision WorkStation 390 | 1        | 2.17%   |
| Dell OptiPlex 3050             | 1        | 2.17%   |
| Dell OptiPlex 3020             | 1        | 2.17%   |
| Dell Inspiron 3670             | 1        | 2.17%   |
| ASUS PRIME A320M-K             | 1        | 2.17%   |
| ASUS P7H55-M PRO               | 1        | 2.17%   |
| ASUS P5G41T-M LX               | 1        | 2.17%   |
| ASUS M5A97                     | 1        | 2.17%   |
| ASUS M5A78L-M/USB3             | 1        | 2.17%   |
| ASUS M5A78L-M PLUS/USB3        | 1        | 2.17%   |
| ASUS H110-PLUS                 | 1        | 2.17%   |
| ASUS CM6650                    | 1        | 2.17%   |
| ASRock X370 Gaming X           | 1        | 2.17%   |
| ASRock Q1900-ITX               | 1        | 2.17%   |
| ASRock N68-S3 UCC              | 1        | 2.17%   |
| ASRock A55M-HVS                | 1        | 2.17%   |
| ASRock 980DE3/U3S3             | 1        | 2.17%   |
| Acer Aspire X1930              | 1        | 2.17%   |
| ABIT AW9D-MAX                  | 1        | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 2        | 4.35%   |
| ASUS M5A78L-M        | 2        | 4.35%   |
| Positivo POS-PIQ67CG | 1        | 2.17%   |
| Positivo POS-EIBTPDC | 1        | 2.17%   |
| Pegatron p6745br     | 1        | 2.17%   |
| Pegatron NC045AA-ABU | 1        | 2.17%   |
| MSI MS-7C37          | 1        | 2.17%   |
| MSI MS-7B79          | 1        | 2.17%   |
| MSI MS-7A71          | 1        | 2.17%   |
| MSI MS-7752          | 1        | 2.17%   |
| MSI MS-7693          | 1        | 2.17%   |
| MSI MS-7681          | 1        | 2.17%   |
| MSI MS-7593          | 1        | 2.17%   |
| MSI MS-7529          | 1        | 2.17%   |
| Lenovo ThinkCentre   | 1        | 2.17%   |
| Intel H55            | 1        | 2.17%   |
| Intel DP55WB         | 1        | 2.17%   |
| Intel DG35EC         | 1        | 2.17%   |
| Intel DESKTOP        | 1        | 2.17%   |
| Intel DB85FL         | 1        | 2.17%   |
| HP EliteDesk         | 1        | 2.17%   |
| HP 700-214           | 1        | 2.17%   |
| Google Teemo         | 1        | 2.17%   |
| Gigabyte H61M-S2PV   | 1        | 2.17%   |
| Gigabyte GA-970A-D3  | 1        | 2.17%   |
| Gigabyte F2A78M-D3H  | 1        | 2.17%   |
| Gigabyte 970A-D3     | 1        | 2.17%   |
| Gigabyte 7200-5121B  | 1        | 2.17%   |
| Foxconn D270S        | 1        | 2.17%   |
| Dell Precision       | 1        | 2.17%   |
| Dell Inspiron        | 1        | 2.17%   |
| ASUS PRIME           | 1        | 2.17%   |
| ASUS P7H55-M         | 1        | 2.17%   |
| ASUS P5G41T-M        | 1        | 2.17%   |
| ASUS M5A97           | 1        | 2.17%   |
| ASUS H110-PLUS       | 1        | 2.17%   |
| ASUS CM6650          | 1        | 2.17%   |
| ASRock X370          | 1        | 2.17%   |
| ASRock Q1900-ITX     | 1        | 2.17%   |
| ASRock N68-S3        | 1        | 2.17%   |
| ASRock A55M-HVS      | 1        | 2.17%   |
| ASRock 980DE3        | 1        | 2.17%   |
| Acer Aspire          | 1        | 2.17%   |
| ABIT AW9D-MAX        | 1        | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 8        | 17.39%  |
| 2014 | 6        | 13.04%  |
| 2012 | 5        | 10.87%  |
| 2010 | 5        | 10.87%  |
| 2013 | 4        | 8.7%    |
| 2019 | 3        | 6.52%   |
| 2017 | 3        | 6.52%   |
| 2016 | 3        | 6.52%   |
| 2009 | 3        | 6.52%   |
| 2015 | 2        | 4.35%   |
| 2008 | 2        | 4.35%   |
| 2021 | 1        | 2.17%   |
| 2006 | 1        | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 46       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 44       | 95.65%  |
| Enabled  | 2        | 4.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 97.83%  |
| Yes  | 1        | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 12       | 26.09%  |
| 16.01-24.0 | 11       | 23.91%  |
| 4.01-8.0   | 8        | 17.39%  |
| 3.01-4.0   | 8        | 17.39%  |
| 32.01-64.0 | 4        | 8.7%    |
| 1.01-2.0   | 2        | 4.35%   |
| 24.01-32.0 | 1        | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 20       | 43.48%  |
| 2.01-3.0  | 12       | 26.09%  |
| 3.01-4.0  | 5        | 10.87%  |
| 0.51-1.0  | 4        | 8.7%    |
| 4.01-8.0  | 3        | 6.52%   |
| 8.01-16.0 | 2        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 46.81%  |
| 2      | 13       | 27.66%  |
| 3      | 6        | 12.77%  |
| 4      | 4        | 8.51%   |
| 5      | 2        | 4.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 56.52%  |
| No        | 20       | 43.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 51.06%  |
| Yes       | 23       | 48.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 60.87%  |
| Yes       | 18       | 39.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 13       | 28.26%  |
| Brazil       | 8        | 17.39%  |
| Germany      | 3        | 6.52%   |
| Canada       | 3        | 6.52%   |
| UK           | 2        | 4.35%   |
| Poland       | 2        | 4.35%   |
| Italy        | 2        | 4.35%   |
| France       | 2        | 4.35%   |
| Sweden       | 1        | 2.17%   |
| Spain        | 1        | 2.17%   |
| South Africa | 1        | 2.17%   |
| Serbia       | 1        | 2.17%   |
| Russia       | 1        | 2.17%   |
| Puerto Rico  | 1        | 2.17%   |
| Netherlands  | 1        | 2.17%   |
| Namibia      | 1        | 2.17%   |
| Mexico       | 1        | 2.17%   |
| India        | 1        | 2.17%   |
| Argentina    | 1        | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Rio de Janeiro       | 3        | 6.52%   |
| Windhoek             | 1        | 2.17%   |
| Wegberg              | 1        | 2.17%   |
| Warsaw               | 1        | 2.17%   |
| Toronto              | 1        | 2.17%   |
| Stourbridge          | 1        | 2.17%   |
| Stockport            | 1        | 2.17%   |
| Stockholm            | 1        | 2.17%   |
| Sparta               | 1        | 2.17%   |
| Siegburg             | 1        | 2.17%   |
| Sao Paulo            | 1        | 2.17%   |
| Salt Lake City       | 1        | 2.17%   |
| Ruda Śląska        | 1        | 2.17%   |
| Pretoria             | 1        | 2.17%   |
| Port Coquitlam       | 1        | 2.17%   |
| Patchogue            | 1        | 2.17%   |
| Novi Karlovci        | 1        | 2.17%   |
| North Richland Hills | 1        | 2.17%   |
| Newburgh             | 1        | 2.17%   |
| New York             | 1        | 2.17%   |
| Missoula             | 1        | 2.17%   |
| Milan                | 1        | 2.17%   |
| Melbourne            | 1        | 2.17%   |
| Marica               | 1        | 2.17%   |
| Madrid               | 1        | 2.17%   |
| Kochi                | 1        | 2.17%   |
| Ingolstadt           | 1        | 2.17%   |
| Indaiatuba           | 1        | 2.17%   |
| Holmen               | 1        | 2.17%   |
| Guadalajara          | 1        | 2.17%   |
| Genoa                | 1        | 2.17%   |
| Garanhuns            | 1        | 2.17%   |
| Duluth               | 1        | 2.17%   |
| Dorado               | 1        | 2.17%   |
| Columbus             | 1        | 2.17%   |
| Chatenois-les-Forges | 1        | 2.17%   |
| Charlotte            | 1        | 2.17%   |
| Campinas             | 1        | 2.17%   |
| Buenos Aires         | 1        | 2.17%   |
| Brampton             | 1        | 2.17%   |
| Bolshoy Kamen        | 1        | 2.17%   |
| Battle Creek         | 1        | 2.17%   |
| Amsterdam            | 1        | 2.17%   |
| Amiens               | 1        | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 27     | 25.97%  |
| WDC                 | 16       | 22     | 20.78%  |
| Samsung Electronics | 12       | 12     | 15.58%  |
| SanDisk             | 7        | 7      | 9.09%   |
| Crucial             | 3        | 3      | 3.9%    |
| Transcend           | 2        | 2      | 2.6%    |
| Toshiba             | 2        | 2      | 2.6%    |
| SPCC                | 2        | 2      | 2.6%    |
| Kingston            | 2        | 2      | 2.6%    |
| SATAFIRM            | 1        | 1      | 1.3%    |
| PNY                 | 1        | 1      | 1.3%    |
| Phison              | 1        | 1      | 1.3%    |
| OCZ                 | 1        | 1      | 1.3%    |
| Maxtor              | 1        | 1      | 1.3%    |
| JMicron Technology  | 1        | 1      | 1.3%    |
| Hitachi             | 1        | 1      | 1.3%    |
| Apple               | 1        | 1      | 1.3%    |
| Apacer              | 1        | 2      | 1.3%    |
| AFOX                | 1        | 1      | 1.3%    |
| A-DATA Technology   | 1        | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB      | 4        | 4.6%    |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 2.3%    |
| Seagate Expansion Desk 4TB          | 2        | 2.3%    |
| SanDisk SDSSDX240GG25 240GB         | 2        | 2.3%    |
| Samsung SSD 860 EVO 1TB             | 2        | 2.3%    |
| Crucial CT1000MX500SSD1 1TB         | 2        | 2.3%    |
| WDC WDS500G2B0C-00PXH0 500GB        | 1        | 1.15%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1        | 1.15%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1        | 1.15%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1.15%   |
| WDC WDBNCE5000PNC 500GB SSD         | 1        | 1.15%   |
| WDC WD6402AAEX-00Y9A0 640GB         | 1        | 1.15%   |
| WDC WD6401AALS-00L3B2 640GB         | 1        | 1.15%   |
| WDC WD5000AVVS-63M8B0 500GB         | 1        | 1.15%   |
| WDC WD5000AAKS-75A7B2 500GB         | 1        | 1.15%   |
| WDC WD3200AAKS-61L9A0 320GB         | 1        | 1.15%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1        | 1.15%   |
| WDC WD30EZRX-00MMMB0 3TB            | 1        | 1.15%   |
| WDC WD20EADS-00R6B0 2TB             | 1        | 1.15%   |
| WDC WD2002FAEX-007BA0 2TB           | 1        | 1.15%   |
| WDC WD1600JB-32FUA0 160GB           | 1        | 1.15%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1.15%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 1.15%   |
| WDC WD10EADS-65M2BX 1TB             | 1        | 1.15%   |
| WDC WD10EADS-22M2B0 1TB             | 1        | 1.15%   |
| WDC WD10EADS-00L5B1 1TB             | 1        | 1.15%   |
| WDC WD1001FALS-00J7B0 1TB           | 1        | 1.15%   |
| Transcend TS32GMTS400 32GB SSD      | 1        | 1.15%   |
| Transcend TS128GSSD360S 128GB       | 1        | 1.15%   |
| Toshiba MQ01ABD050 500GB            | 1        | 1.15%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1        | 1.15%   |
| SPCC Solid State Disk 512GB         | 1        | 1.15%   |
| SPCC Solid State Disk 128GB         | 1        | 1.15%   |
| Seagate ST9160310AS 160GB           | 1        | 1.15%   |
| Seagate ST500LT012-9WS142 500GB     | 1        | 1.15%   |
| Seagate ST500DM009-2F110A 500GB     | 1        | 1.15%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1.15%   |
| Seagate ST3750640NS 752GB           | 1        | 1.15%   |
| Seagate ST3500414CS 500GB           | 1        | 1.15%   |
| Seagate ST3160811AS 160GB           | 1        | 1.15%   |
| Seagate ST31000528AS 1TB            | 1        | 1.15%   |
| Seagate ST2000VM003-1ET164 2TB      | 1        | 1.15%   |
| Seagate ST2000DX002-2DV164 2TB      | 1        | 1.15%   |
| Seagate ST2000DM006-2DM164 2TB      | 1        | 1.15%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1.15%   |
| Seagate ST2000DM001-1CH164 2TB      | 1        | 1.15%   |
| Seagate ST2000DM 008-2FR102 2TB     | 1        | 1.15%   |
| Seagate Expansion 1TB               | 1        | 1.15%   |
| Seagate Backup+ Hub BK 4TB          | 1        | 1.15%   |
| SATAFIRM S11 240GB                  | 1        | 1.15%   |
| SanDisk SDSSDA240G 240GB            | 1        | 1.15%   |
| SanDisk SDSSDA120G 120GB            | 1        | 1.15%   |
| SanDisk SD8SNAT128G1002 128GB SSD   | 1        | 1.15%   |
| SanDisk SD8SBAT128G1122 128GB SSD   | 1        | 1.15%   |
| SanDisk NVMe SSD Drive 256GB        | 1        | 1.15%   |
| Samsung SSD 860 EVO 500GB           | 1        | 1.15%   |
| Samsung SSD 850 EVO 500GB           | 1        | 1.15%   |
| Samsung SSD 840 Series 120GB        | 1        | 1.15%   |
| Samsung SSD 840 EVO 500GB mSATA     | 1        | 1.15%   |
| Samsung SSD 840 EVO 120GB           | 1        | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 27     | 51.28%  |
| WDC                 | 12       | 17     | 30.77%  |
| Samsung Electronics | 2        | 2      | 5.13%   |
| Toshiba             | 1        | 1      | 2.56%   |
| SATAFIRM            | 1        | 1      | 2.56%   |
| Maxtor              | 1        | 1      | 2.56%   |
| Hitachi             | 1        | 1      | 2.56%   |
| Apple               | 1        | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 8      | 25%     |
| SanDisk             | 6        | 6      | 18.75%  |
| WDC                 | 4        | 4      | 12.5%   |
| Crucial             | 3        | 3      | 9.38%   |
| Transcend           | 2        | 2      | 6.25%   |
| SPCC                | 2        | 2      | 6.25%   |
| Kingston            | 2        | 2      | 6.25%   |
| PNY                 | 1        | 1      | 3.13%   |
| OCZ                 | 1        | 1      | 3.13%   |
| JMicron Technology  | 1        | 1      | 3.13%   |
| Apacer              | 1        | 2      | 3.13%   |
| A-DATA Technology   | 1        | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 30       | 51     | 48.39%  |
| SSD     | 25       | 33     | 40.32%  |
| NVMe    | 6        | 6      | 9.68%   |
| Unknown | 1        | 1      | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 79     | 80.36%  |
| NVMe | 6        | 6      | 10.71%  |
| SAS  | 5        | 6      | 8.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 42     | 50.79%  |
| 0.51-1.0   | 19       | 28     | 30.16%  |
| 1.01-2.0   | 7        | 9      | 11.11%  |
| 3.01-4.0   | 3        | 3      | 4.76%   |
| 2.01-3.0   | 2        | 2      | 3.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 28.26%  |
| 251-500        | 10       | 21.74%  |
| 501-1000       | 8        | 17.39%  |
| 21-50          | 4        | 8.7%    |
| 1001-2000      | 3        | 6.52%   |
| 1-20           | 3        | 6.52%   |
| More than 3000 | 2        | 4.35%   |
| 2001-3000      | 1        | 2.17%   |
| 51-100         | 1        | 2.17%   |
| Unknown        | 1        | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 22       | 46.81%  |
| 1-20      | 12       | 25.53%  |
| 51-100    | 5        | 10.64%  |
| 251-500   | 3        | 6.38%   |
| 2001-3000 | 2        | 4.26%   |
| 101-250   | 2        | 4.26%   |
| Unknown   | 1        | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 45       | 89     | 97.83%  |
| Works    | 1        | 2      | 2.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 30       | 48.39%  |
| AMD                           | 13       | 20.97%  |
| JMicron Technology            | 4        | 6.45%   |
| ASMedia Technology            | 3        | 4.84%   |
| SanDisk                       | 2        | 3.23%   |
| Samsung Electronics           | 2        | 3.23%   |
| Nvidia                        | 2        | 3.23%   |
| Toshiba America Info Systems  | 1        | 1.61%   |
| Silicon Image                 | 1        | 1.61%   |
| Promise Technology            | 1        | 1.61%   |
| Phison Electronics            | 1        | 1.61%   |
| Marvell Technology Group      | 1        | 1.61%   |
| Integrated Technology Express | 1        | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 6.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 4.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 4.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 4.94%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 4.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.47%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 2.47%   |
| JMicron JMB368 IDE controller                                                           | 2        | 2.47%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 2.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.47%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.23%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.23%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 1.23%   |
| Promise PDC20262 (FastTrak66/Ultra66)                                                   | 1        | 1.23%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.23%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.23%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 1.23%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 1.23%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.23%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 1.23%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.23%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1        | 1.23%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.23%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.23%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.23%   |
| Integrated Express IT8212 Dual channel ATA RAID controller                              | 1        | 1.23%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.23%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.23%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.23%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 34       | 53.97%  |
| IDE  | 19       | 30.16%  |
| NVMe | 6        | 9.52%   |
| RAID | 4        | 6.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 67.39%  |
| AMD    | 15       | 32.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 4.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 4.35%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 4.35%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 2.17%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 2.17%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 2.17%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 2.17%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 2.17%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 2.17%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 2.17%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 2.17%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 2.17%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 2.17%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 2.17%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1        | 2.17%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1        | 2.17%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 2.17%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1        | 2.17%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 2.17%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 2.17%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1        | 2.17%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 1        | 2.17%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 1        | 2.17%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 2.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 2.17%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 1        | 2.17%   |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1        | 2.17%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 2.17%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 1        | 2.17%   |
| Intel Atom CPU D2700 @ 2.13GHz              | 1        | 2.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 2.17%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1        | 2.17%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 1        | 2.17%   |
| AMD Phenom II X4 945 Processor              | 1        | 2.17%   |
| AMD Phenom II X4 830 Processor              | 1        | 2.17%   |
| AMD Phenom II X2 565 Processor              | 1        | 2.17%   |
| AMD FX-6300 Six-Core Processor              | 1        | 2.17%   |
| AMD FX-6100 Six-Core Processor              | 1        | 2.17%   |
| AMD FX-4100 Quad-Core Processor             | 1        | 2.17%   |
| AMD Athlon II X2 220 Processor              | 1        | 2.17%   |
| AMD A8-3850 APU with Radeon HD Graphics     | 1        | 2.17%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 1        | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 12       | 26.09%  |
| Intel Core i7      | 5        | 10.87%  |
| Intel Core i3      | 5        | 10.87%  |
| AMD FX             | 5        | 10.87%  |
| Intel Core 2 Quad  | 3        | 6.52%   |
| AMD Ryzen 5        | 3        | 6.52%   |
| Intel Celeron      | 2        | 4.35%   |
| AMD Phenom II X4   | 2        | 4.35%   |
| Intel Pentium Dual | 1        | 2.17%   |
| Intel Core 2 Duo   | 1        | 2.17%   |
| Intel Core 2       | 1        | 2.17%   |
| Intel Atom         | 1        | 2.17%   |
| AMD Ryzen 7        | 1        | 2.17%   |
| AMD Phenom II X2   | 1        | 2.17%   |
| AMD Athlon II X2   | 1        | 2.17%   |
| AMD A8             | 1        | 2.17%   |
| AMD A10            | 1        | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 25       | 54.35%  |
| 2      | 15       | 32.61%  |
| 6      | 3        | 6.52%   |
| 3      | 2        | 4.35%   |
| 8      | 1        | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 52.17%  |
| 2      | 22       | 47.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 46       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 4        | 8.7%    |
| 0x506e3    | 3        | 6.52%   |
| 0x206a7    | 3        | 6.52%   |
| 0x06000852 | 3        | 6.52%   |
| 0x010000c8 | 3        | 6.52%   |
| Unknown    | 3        | 6.52%   |
| 0x306c3    | 2        | 4.35%   |
| 0x20652    | 2        | 4.35%   |
| 0x1067a    | 2        | 4.35%   |
| 0x0600063e | 2        | 4.35%   |
| 0x906ed    | 1        | 2.17%   |
| 0x906e9    | 1        | 2.17%   |
| 0x806e9    | 1        | 2.17%   |
| 0x6fd      | 1        | 2.17%   |
| 0x6fb      | 1        | 2.17%   |
| 0x6f2      | 1        | 2.17%   |
| 0x30678    | 1        | 2.17%   |
| 0x30673    | 1        | 2.17%   |
| 0x30661    | 1        | 2.17%   |
| 0x20655    | 1        | 2.17%   |
| 0x106e5    | 1        | 2.17%   |
| 0x106a5    | 1        | 2.17%   |
| 0x10676    | 1        | 2.17%   |
| 0x08701021 | 1        | 2.17%   |
| 0x08101016 | 1        | 2.17%   |
| 0x08001138 | 1        | 2.17%   |
| 0x06001119 | 1        | 2.17%   |
| 0x03000027 | 1        | 2.17%   |
| 0x010000db | 1        | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Piledriver  | 4        | 8.7%    |
| K10         | 4        | 8.7%    |
| IvyBridge   | 4        | 8.7%    |
| Haswell     | 4        | 8.7%    |
| Westmere    | 3        | 6.52%   |
| Skylake     | 3        | 6.52%   |
| SandyBridge | 3        | 6.52%   |
| Penryn      | 3        | 6.52%   |
| KabyLake    | 3        | 6.52%   |
| Core        | 3        | 6.52%   |
| Zen 2       | 2        | 4.35%   |
| Zen         | 2        | 4.35%   |
| Silvermont  | 2        | 4.35%   |
| Nehalem     | 2        | 4.35%   |
| Bulldozer   | 2        | 4.35%   |
| K10 Llano   | 1        | 2.17%   |
| Bonnell     | 1        | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 21       | 42.86%  |
| Intel  | 15       | 30.61%  |
| AMD    | 13       | 26.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 4.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 4.08%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 2        | 4.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 4.08%   |
| Intel HD Graphics 530                                                       | 2        | 4.08%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 4.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 4.08%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 4.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 4.08%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 2.04%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.04%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.04%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 2.04%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 2.04%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 2.04%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 2.04%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 2.04%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.04%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.04%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 2.04%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 2.04%   |
| Nvidia G96CM [GeForce 9600M GS]                                             | 1        | 2.04%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 2.04%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 2.04%   |
| Intel HD Graphics 630                                                       | 1        | 2.04%   |
| Intel HD Graphics 620                                                       | 1        | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.04%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 2.04%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 2.04%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.04%   |
| AMD Sumo [Radeon HD 6550D]                                                  | 1        | 2.04%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 2.04%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 2.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.04%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 2.04%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.04%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 2.04%   |
| AMD Barts XT [Radeon HD 6870]                                               | 1        | 2.04%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 20       | 43.48%  |
| 1 x AMD        | 13       | 28.26%  |
| 1 x Intel      | 12       | 26.09%  |
| Intel + Nvidia | 1        | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 36       | 78.26%  |
| Proprietary | 6        | 13.04%  |
| Unknown     | 4        | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 34.78%  |
| 0.51-1.0   | 8        | 17.39%  |
| 1.01-2.0   | 7        | 15.22%  |
| 0.01-0.5   | 6        | 13.04%  |
| 2.01-3.0   | 4        | 8.7%    |
| 3.01-4.0   | 3        | 6.52%   |
| 7.01-8.0   | 1        | 2.17%   |
| 5.01-6.0   | 1        | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 18.18%  |
| Ancor Communications | 6        | 13.64%  |
| AOC                  | 4        | 9.09%   |
| Acer                 | 4        | 9.09%   |
| Philips              | 3        | 6.82%   |
| Hewlett-Packard      | 3        | 6.82%   |
| Goldstar             | 3        | 6.82%   |
| ViewSonic            | 2        | 4.55%   |
| Dell                 | 2        | 4.55%   |
| ___                  | 1        | 2.27%   |
| Tech Concepts        | 1        | 2.27%   |
| Onkyo                | 1        | 2.27%   |
| Microstep            | 1        | 2.27%   |
| Insignia             | 1        | 2.27%   |
| Idek Iiyama          | 1        | 2.27%   |
| HKC                  | 1        | 2.27%   |
| BenQ                 | 1        | 2.27%   |
| Unknown              | 1        | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ___ AAA ___01FF 1366x768 700x390mm 31.5-inch                          | 1        | 2.17%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1        | 2.17%   |
| ViewSonic VA2013wSERIES VSCF122 1600x900 443x249mm 20.0-inch          | 1        | 2.17%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                            | 1        | 2.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 2.17%   |
| Samsung Electronics T24C310 SAM0AEA 1920x1080 531x299mm 24.0-inch     | 1        | 2.17%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch  | 1        | 2.17%   |
| Samsung Electronics SMT22A550 SAM07AE 1920x1080 477x268mm 21.5-inch   | 1        | 2.17%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch     | 1        | 2.17%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 2.17%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch  | 1        | 2.17%   |
| Samsung Electronics LCD Monitor S24B300 3840x1080                     | 1        | 2.17%   |
| Philips PHL 241P4 PHL08D5 1920x1080 531x299mm 24.0-inch               | 1        | 2.17%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch             | 1        | 2.17%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 1        | 2.17%   |
| Onkyo AV Receiver ONK1050 1920x1080                                   | 1        | 2.17%   |
| Microstep LCD Monitor MSI MAG341CQ 3440x1440                          | 1        | 2.17%   |
| Insignia NS28D310NA15 BBY0028 1680x1050 640x384mm 29.4-inch           | 1        | 2.17%   |
| Idek Iiyama LCD Monitor PL2473HD 1920x1080                            | 1        | 2.17%   |
| HKC LCD Monitor HKC2400 1920x1080 597x336mm 27.0-inch                 | 1        | 2.17%   |
| Hewlett-Packard v185e HWP2838 1366x768 410x230mm 18.5-inch            | 1        | 2.17%   |
| Hewlett-Packard LCD Monitor w2338h                                    | 1        | 2.17%   |
| Hewlett-Packard Compaq W185q HWP284F 1366x768 410x230mm 18.5-inch     | 1        | 2.17%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 1        | 2.17%   |
| Goldstar RZ32LZ55 GSM7546 1360x768 930x523mm 42.0-inch                | 1        | 2.17%   |
| Goldstar M237WDP GSM5778 1920x1080 510x290mm 23.1-inch                | 1        | 2.17%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1        | 2.17%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 1        | 2.17%   |
| Dell LCD Monitor DELA026 1920x1200 520x330mm 24.2-inch                | 1        | 2.17%   |
| BenQ FP71V+ BNQ76A2 1280x1024 376x301mm 19.0-inch                     | 1        | 2.17%   |
| AOC G2770 AOC2770 1920x1080 598x336mm 27.0-inch                       | 1        | 2.17%   |
| AOC 519W AOC1519 1280x720 340x270mm 17.1-inch                         | 1        | 2.17%   |
| AOC 2752 AOC2752 1920x1080 579x336mm 26.4-inch                        | 1        | 2.17%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 1        | 2.17%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 1        | 2.17%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 1        | 2.17%   |
| Ancor Communications MW221 ACI22B1 1680x1050 473x296mm 22.0-inch      | 1        | 2.17%   |
| Ancor Communications LCD Monitor ASUS VS228 1920x1080                 | 1        | 2.17%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 1        | 2.17%   |
| Ancor Communications ASUS VG278 ACI27E1 1920x1080 598x336mm 27.0-inch | 1        | 2.17%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 528x310mm 24.1-inch | 1        | 2.17%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 1        | 2.17%   |
| Acer H6510BD ACR1535 1920x1080                                        | 1        | 2.17%   |
| Acer CB282K ACR075F 3840x2160 621x341mm 27.9-inch                     | 1        | 2.17%   |
| Acer B226HQL ACR0330 1920x1080 477x268mm 21.5-inch                    | 1        | 2.17%   |
| Unknown                                                               | 1        | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 46.34%  |
| 1366x768 (WXGA)    | 5        | 12.2%   |
| 3840x2160 (4K)     | 3        | 7.32%   |
| 1360x768           | 3        | 7.32%   |
| 1680x1050 (WSXGA+) | 2        | 4.88%   |
| 1600x900 (HD+)     | 2        | 4.88%   |
| 3840x1080          | 1        | 2.44%   |
| 3440x1440          | 1        | 2.44%   |
| 2560x1440 (QHD)    | 1        | 2.44%   |
| 1920x1200 (WUXGA)  | 1        | 2.44%   |
| 1280x720 (HD)      | 1        | 2.44%   |
| 1280x1024 (SXGA)   | 1        | 2.44%   |
| Unknown            | 1        | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 9        | 20.45%  |
| 24      | 7        | 15.91%  |
| Unknown | 7        | 15.91%  |
| 21      | 5        | 11.36%  |
| 18      | 4        | 9.09%   |
| 31      | 3        | 6.82%   |
| 23      | 2        | 4.55%   |
| 22      | 2        | 4.55%   |
| 19      | 2        | 4.55%   |
| 42      | 1        | 2.27%   |
| 20      | 1        | 2.27%   |
| 17      | 1        | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 33.33%  |
| 401-500     | 13       | 30.95%  |
| Unknown     | 7        | 16.67%  |
| 601-700     | 5        | 11.9%   |
| 351-400     | 1        | 2.38%   |
| 301-350     | 1        | 2.38%   |
| 901-1000    | 1        | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 74.36%  |
| Unknown | 5        | 12.82%  |
| 16/10   | 3        | 7.69%   |
| 5/4     | 2        | 5.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 25.58%  |
| 301-350        | 9        | 20.93%  |
| Unknown        | 7        | 16.28%  |
| 151-200        | 5        | 11.63%  |
| 141-150        | 5        | 11.63%  |
| 351-500        | 3        | 6.98%   |
| 251-300        | 2        | 4.65%   |
| 501-1000       | 1        | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 56.1%   |
| Unknown | 7        | 17.07%  |
| 101-120 | 5        | 12.2%   |
| 1-50    | 4        | 9.76%   |
| 121-160 | 2        | 4.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 78.26%  |
| 2     | 6        | 13.04%  |
| 0     | 3        | 6.52%   |
| 3     | 1        | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 35       | 51.47%  |
| Intel                           | 13       | 19.12%  |
| Qualcomm Atheros                | 5        | 7.35%   |
| Ralink                          | 3        | 4.41%   |
| TP-Link                         | 2        | 2.94%   |
| Nvidia                          | 2        | 2.94%   |
| Ralink Technology               | 1        | 1.47%   |
| Qualcomm Atheros Communications | 1        | 1.47%   |
| Motorola PCS                    | 1        | 1.47%   |
| Huawei Technologies             | 1        | 1.47%   |
| D-Link System                   | 1        | 1.47%   |
| D-Link                          | 1        | 1.47%   |
| Broadcom Limited                | 1        | 1.47%   |
| Broadcom                        | 1        | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 31       | 41.33%  |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2        | 2.67%   |
| Nvidia MCP61 Ethernet                                                                         | 2        | 2.67%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 2.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 1.33%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.33%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1        | 1.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 1.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.33%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1        | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 1.33%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1        | 1.33%   |
| Motorola PCS moto g(9) play                                                                   | 1        | 1.33%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 1.33%   |
| Intel Wireless 7265                                                                           | 1        | 1.33%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.33%   |
| Intel Ethernet Connection I217-V                                                              | 1        | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 1        | 1.33%   |
| Intel 82578DM Gigabit Network Connection                                                      | 1        | 1.33%   |
| Intel 82578DC Gigabit Network Connection                                                      | 1        | 1.33%   |
| Intel 82566DC Gigabit Network Connection                                                      | 1        | 1.33%   |
| Huawei E353/E3131                                                                             | 1        | 1.33%   |
| D-Link System DWA-126 802.11n Wireless Adapter [Atheros AR9271]                               | 1        | 1.33%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1        | 1.33%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express                               | 1        | 1.33%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 8        | 30.77%  |
| Intel                           | 5        | 19.23%  |
| Ralink                          | 3        | 11.54%  |
| Qualcomm Atheros                | 3        | 11.54%  |
| TP-Link                         | 2        | 7.69%   |
| Ralink Technology               | 1        | 3.85%   |
| Qualcomm Atheros Communications | 1        | 3.85%   |
| D-Link System                   | 1        | 3.85%   |
| D-Link                          | 1        | 3.85%   |
| Broadcom                        | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 3        | 11.54%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 7.69%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 3.85%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 3.85%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 3.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 3.85%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1        | 3.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 3.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 3.85%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 3.85%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 3.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 3.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 3.85%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1        | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1        | 3.85%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1        | 3.85%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 3.85%   |
| Intel Wireless 7265                                                                           | 1        | 3.85%   |
| D-Link System DWA-126 802.11n Wireless Adapter [Atheros AR9271]                               | 1        | 3.85%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1        | 3.85%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 33       | 67.35%  |
| Intel                 | 9        | 18.37%  |
| Qualcomm Atheros      | 2        | 4.08%   |
| Nvidia                | 2        | 4.08%   |
| Motorola PCS          | 1        | 2.04%   |
| Huawei Technologies   | 1        | 2.04%   |
| Broadcom Limited      | 1        | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 63.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 4.08%   |
| Nvidia MCP61 Ethernet                                             | 2        | 4.08%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 4.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.04%   |
| Motorola PCS moto g(9) play                                       | 1        | 2.04%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.04%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.04%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.04%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.04%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 2.04%   |
| Huawei E353/E3131                                                 | 1        | 2.04%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 66.67%  |
| WiFi     | 23       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 68.75%  |
| WiFi     | 15       | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 69.57%  |
| 2     | 14       | 30.43%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 58.7%   |
| Yes  | 19       | 41.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 7        | 38.89%  |
| Intel                           | 5        | 27.78%  |
| ASUSTek Computer                | 2        | 11.11%  |
| Ralink                          | 1        | 5.56%   |
| Qualcomm Atheros Communications | 1        | 5.56%   |
| Hewlett-Packard                 | 1        | 5.56%   |
| Broadcom                        | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 38.89%  |
| Intel AX200 Bluetooth                               | 3        | 16.67%  |
| Intel Bluetooth wireless interface                  | 2        | 11.11%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 11.11%  |
| Ralink RT3290 Bluetooth                             | 1        | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 5.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 5.56%   |
| Broadcom Bluetooth Device                           | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 28       | 33.73%  |
| Nvidia                    | 19       | 22.89%  |
| AMD                       | 18       | 21.69%  |
| C-Media Electronics       | 5        | 6.02%   |
| GN Netcom                 | 2        | 2.41%   |
| Creative Labs             | 2        | 2.41%   |
| Texas Instruments         | 1        | 1.2%    |
| Sennheiser Communications | 1        | 1.2%    |
| ROCCAT                    | 1        | 1.2%    |
| Microsoft                 | 1        | 1.2%    |
| M-Audio                   | 1        | 1.2%    |
| JMTek                     | 1        | 1.2%    |
| iSoft Silicon             | 1        | 1.2%    |
| Focusrite-Novation        | 1        | 1.2%    |
| AOKEO                     | 1        | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 7.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 5.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 4.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 4.35%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 3.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 3.26%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 2.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.17%   |
| Nvidia GK110 High Definition Audio Controller                              | 2        | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.17%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.17%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2        | 2.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.17%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.17%   |
| Texas Instruments PCM2903B Audio CODEC                                     | 1        | 1.09%   |
| Sennheiser Communications PXC 550                                          | 1        | 1.09%   |
| ROCCAT Juke                                                                | 1        | 1.09%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.09%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.09%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.09%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 1.09%   |
| Microsoft LifeChat LX-3000 Headset                                         | 1        | 1.09%   |
| M-Audio M-Audio Fast Track MKII                                            | 1        | 1.09%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.09%   |
| iSoft Silicon USB Ear-Microphone                                           | 1        | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.09%   |
| Intel Sunrise Point-LP HD Audio                                            | 1        | 1.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 1.09%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.09%   |
| GN Netcom Jabra Link 380                                                   | 1        | 1.09%   |
| GN Netcom Jabra Link 370                                                   | 1        | 1.09%   |
| Focusrite-Novation Launchkey MK2 25                                        | 1        | 1.09%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 1.09%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 1        | 1.09%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 1.09%   |
| C-Media Electronics Blue Snowball                                          | 1        | 1.09%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.09%   |
| AOKEO LCS_USB_Audio                                                        | 1        | 1.09%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 1.09%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.09%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1        | 1.09%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Corsair | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 1        | 100%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Seiko Epson L395 Series  | 1        | 50%     |
| Canon PIXMA MX920 Series | 1        | 50%     |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Microsoft                 | 2        | 15.38%  |
| Logitech                  | 2        | 15.38%  |
| Chicony Electronics       | 2        | 15.38%  |
| YGTek                     | 1        | 7.69%   |
| Silicon Motion            | 1        | 7.69%   |
| SHENZHEN EMEET TECHNOLOGY | 1        | 7.69%   |
| Jieli Technology          | 1        | 7.69%   |
| Hewlett-Packard           | 1        | 7.69%   |
| Creative Technology       | 1        | 7.69%   |
| 2M UVC CAMERA             | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| YGTek Webcam                                   | 1        | 7.69%   |
| Silicon Motion SM731 Camera                    | 1        | 7.69%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1        | 7.69%   |
| Microsoft LifeCam VX-5000                      | 1        | 7.69%   |
| Microsoft LifeCam VX-500 [1357]                | 1        | 7.69%   |
| Logitech Webcam C600                           | 1        | 7.69%   |
| Logitech C922 Pro Stream Webcam                | 1        | 7.69%   |
| Jieli USB PHY 2.0                              | 1        | 7.69%   |
| HP Webcam 3110                                 | 1        | 7.69%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 7.69%   |
| Chicony CNF7042                                | 1        | 7.69%   |
| Chicony 2.0M UVC Webcam / CNF7129              | 1        | 7.69%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam           | 1        | 7.69%   |

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
| 0     | 36       | 78.26%  |
| 1     | 10       | 21.74%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 5        | 50%     |
| Graphics card | 4        | 40%     |
| Bluetooth     | 1        | 10%     |

