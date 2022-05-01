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

Total: 60

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
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
| Gigabyte | GA-970A-D3           | [84b16824bd](https://linux-hardware.org/?probe=84b16824bd) | Dec 26, 2021 |
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
| MSI      | P67A-GD65            | [78c9f06350](https://linux-hardware.org/?probe=78c9f06350) | Oct 08, 2021 |
| MSI      | 970 GAMING           | [0778440642](https://linux-hardware.org/?probe=0778440642) | Oct 02, 2021 |
| Intel    | DG35EC AAE29266-202  | [74d233db8b](https://linux-hardware.org/?probe=74d233db8b) | Oct 02, 2021 |
| Intel    | DG35EC AAE29266-202  | [f29471dfd6](https://linux-hardware.org/?probe=f29471dfd6) | Oct 01, 2021 |
| Dell     | 0DN075               | [1d0145e3e0](https://linux-hardware.org/?probe=1d0145e3e0) | Oct 01, 2021 |
| MSI      | G31TM-P25            | [efe15b35ca](https://linux-hardware.org/?probe=efe15b35ca) | Sep 29, 2021 |
| ASRock   | A55M-HVS             | [3061a2007b](https://linux-hardware.org/?probe=3061a2007b) | Sep 27, 2021 |
| ASRock   | A55M-HVS             | [4748ccb729](https://linux-hardware.org/?probe=4748ccb729) | Sep 25, 2021 |
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
| 5.11.0-43-generic | 6        | 13.95%  |
| 5.11.0-41-generic | 6        | 13.95%  |
| 5.11.0-37-generic | 6        | 13.95%  |
| 5.11.0-40-generic | 5        | 11.63%  |
| 5.13.0-28-generic | 4        | 9.3%    |
| 5.11.0-38-generic | 4        | 9.3%    |
| 5.13.0-27-generic | 3        | 6.98%   |
| 5.11.0-34-generic | 3        | 6.98%   |
| 5.13.0-30-generic | 2        | 4.65%   |
| 5.11.0-46-generic | 2        | 4.65%   |
| 5.13.0-39-generic | 1        | 2.33%   |
| 5.11.0-36-generic | 1        | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 32       | 76.19%  |
| 5.13.0  | 10       | 23.81%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 32       | 76.19%  |
| 5.13    | 10       | 23.81%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 42       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 40       | 93.02%  |
| KDE  | 3        | 6.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 42       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 80.95%  |
| SDDM    | 8        | 19.05%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 26.19%  |
| pt_BR | 7        | 16.67%  |
| C     | 4        | 9.52%   |
| fr_FR | 3        | 7.14%   |
| en_GB | 3        | 7.14%   |
| it_IT | 2        | 4.76%   |
| en_CA | 2        | 4.76%   |
| de_DE | 2        | 4.76%   |
| sv_SE | 1        | 2.38%   |
| ru_RU | 1        | 2.38%   |
| pl_PL | 1        | 2.38%   |
| es_MX | 1        | 2.38%   |
| es_ES | 1        | 2.38%   |
| es_AR | 1        | 2.38%   |
| en_ZA | 1        | 2.38%   |
| en_IN | 1        | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 30       | 71.43%  |
| EFI  | 12       | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 40       | 95.24%  |
| Overlay | 2        | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 97.62%  |
| GPT     | 1        | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 90.48%  |
| Yes       | 4        | 9.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 85.71%  |
| Yes       | 6        | 14.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 8        | 19.05%  |
| ASUSTek Computer    | 6        | 14.29%  |
| Gigabyte Technology | 5        | 11.9%   |
| ASRock              | 5        | 11.9%   |
| Intel               | 4        | 9.52%   |
| Dell                | 4        | 9.52%   |
| Positivo            | 2        | 4.76%   |
| Pegatron            | 2        | 4.76%   |
| Hewlett-Packard     | 2        | 4.76%   |
| Google              | 1        | 2.38%   |
| Foxconn             | 1        | 2.38%   |
| Acer                | 1        | 2.38%   |
| ABIT                | 1        | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Positivo POS-PIQ67CG           | 1        | 2.38%   |
| Positivo POS-EIBTPDC           | 1        | 2.38%   |
| Pegatron p6745br               | 1        | 2.38%   |
| Pegatron NC045AA-ABU IQ525uk   | 1        | 2.38%   |
| MSI MS-7C37                    | 1        | 2.38%   |
| MSI MS-7B79                    | 1        | 2.38%   |
| MSI MS-7A71                    | 1        | 2.38%   |
| MSI MS-7752                    | 1        | 2.38%   |
| MSI MS-7693                    | 1        | 2.38%   |
| MSI MS-7681                    | 1        | 2.38%   |
| MSI MS-7593                    | 1        | 2.38%   |
| MSI MS-7529                    | 1        | 2.38%   |
| Intel H55                      | 1        | 2.38%   |
| Intel DP55WB AAE64798-205      | 1        | 2.38%   |
| Intel DG35EC AAE29266-202      | 1        | 2.38%   |
| Intel DESKTOP 300              | 1        | 2.38%   |
| HP EliteDesk 800 G2 SFF        | 1        | 2.38%   |
| HP 700-214                     | 1        | 2.38%   |
| Google Teemo                   | 1        | 2.38%   |
| Gigabyte H61M-S2PV             | 1        | 2.38%   |
| Gigabyte GA-970A-D3            | 1        | 2.38%   |
| Gigabyte F2A78M-D3H            | 1        | 2.38%   |
| Gigabyte 970A-D3               | 1        | 2.38%   |
| Gigabyte 7200-5121B            | 1        | 2.38%   |
| Foxconn D270S/D250S MP         | 1        | 2.38%   |
| Dell Precision WorkStation 390 | 1        | 2.38%   |
| Dell OptiPlex 3050             | 1        | 2.38%   |
| Dell OptiPlex 3020             | 1        | 2.38%   |
| Dell Inspiron 3670             | 1        | 2.38%   |
| ASUS PRIME A320M-K             | 1        | 2.38%   |
| ASUS P7H55-M PRO               | 1        | 2.38%   |
| ASUS P5G41T-M LX               | 1        | 2.38%   |
| ASUS M5A78L-M PLUS/USB3        | 1        | 2.38%   |
| ASUS H110-PLUS                 | 1        | 2.38%   |
| ASUS CM6650                    | 1        | 2.38%   |
| ASRock X370 Gaming X           | 1        | 2.38%   |
| ASRock Q1900-ITX               | 1        | 2.38%   |
| ASRock N68-S3 UCC              | 1        | 2.38%   |
| ASRock A55M-HVS                | 1        | 2.38%   |
| ASRock 980DE3/U3S3             | 1        | 2.38%   |
| Acer Aspire X1930              | 1        | 2.38%   |
| ABIT AW9D-MAX                  | 1        | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 2        | 4.76%   |
| Positivo POS-PIQ67CG | 1        | 2.38%   |
| Positivo POS-EIBTPDC | 1        | 2.38%   |
| Pegatron p6745br     | 1        | 2.38%   |
| Pegatron NC045AA-ABU | 1        | 2.38%   |
| MSI MS-7C37          | 1        | 2.38%   |
| MSI MS-7B79          | 1        | 2.38%   |
| MSI MS-7A71          | 1        | 2.38%   |
| MSI MS-7752          | 1        | 2.38%   |
| MSI MS-7693          | 1        | 2.38%   |
| MSI MS-7681          | 1        | 2.38%   |
| MSI MS-7593          | 1        | 2.38%   |
| MSI MS-7529          | 1        | 2.38%   |
| Intel H55            | 1        | 2.38%   |
| Intel DP55WB         | 1        | 2.38%   |
| Intel DG35EC         | 1        | 2.38%   |
| Intel DESKTOP        | 1        | 2.38%   |
| HP EliteDesk         | 1        | 2.38%   |
| HP 700-214           | 1        | 2.38%   |
| Google Teemo         | 1        | 2.38%   |
| Gigabyte H61M-S2PV   | 1        | 2.38%   |
| Gigabyte GA-970A-D3  | 1        | 2.38%   |
| Gigabyte F2A78M-D3H  | 1        | 2.38%   |
| Gigabyte 970A-D3     | 1        | 2.38%   |
| Gigabyte 7200-5121B  | 1        | 2.38%   |
| Foxconn D270S        | 1        | 2.38%   |
| Dell Precision       | 1        | 2.38%   |
| Dell Inspiron        | 1        | 2.38%   |
| ASUS PRIME           | 1        | 2.38%   |
| ASUS P7H55-M         | 1        | 2.38%   |
| ASUS P5G41T-M        | 1        | 2.38%   |
| ASUS M5A78L-M        | 1        | 2.38%   |
| ASUS H110-PLUS       | 1        | 2.38%   |
| ASUS CM6650          | 1        | 2.38%   |
| ASRock X370          | 1        | 2.38%   |
| ASRock Q1900-ITX     | 1        | 2.38%   |
| ASRock N68-S3        | 1        | 2.38%   |
| ASRock A55M-HVS      | 1        | 2.38%   |
| ASRock 980DE3        | 1        | 2.38%   |
| Acer Aspire          | 1        | 2.38%   |
| ABIT AW9D-MAX        | 1        | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 7        | 16.67%  |
| 2014 | 5        | 11.9%   |
| 2010 | 5        | 11.9%   |
| 2012 | 4        | 9.52%   |
| 2019 | 3        | 7.14%   |
| 2017 | 3        | 7.14%   |
| 2016 | 3        | 7.14%   |
| 2015 | 3        | 7.14%   |
| 2009 | 3        | 7.14%   |
| 2013 | 2        | 4.76%   |
| 2008 | 2        | 4.76%   |
| 2021 | 1        | 2.38%   |
| 2006 | 1        | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 42       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 40       | 95.24%  |
| Enabled  | 2        | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 97.62%  |
| Yes  | 1        | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 11       | 26.19%  |
| 16.01-24.0 | 10       | 23.81%  |
| 4.01-8.0   | 8        | 19.05%  |
| 3.01-4.0   | 7        | 16.67%  |
| 32.01-64.0 | 3        | 7.14%   |
| 1.01-2.0   | 2        | 4.76%   |
| 24.01-32.0 | 1        | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 19       | 45.24%  |
| 2.01-3.0  | 10       | 23.81%  |
| 3.01-4.0  | 4        | 9.52%   |
| 0.51-1.0  | 4        | 9.52%   |
| 4.01-8.0  | 3        | 7.14%   |
| 8.01-16.0 | 2        | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 48.84%  |
| 2      | 11       | 25.58%  |
| 3      | 6        | 13.95%  |
| 4      | 3        | 6.98%   |
| 5      | 2        | 4.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 57.14%  |
| No        | 18       | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 51.16%  |
| Yes       | 21       | 48.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 66.67%  |
| Yes       | 14       | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 11       | 26.19%  |
| Brazil       | 8        | 19.05%  |
| Canada       | 3        | 7.14%   |
| UK           | 2        | 4.76%   |
| Poland       | 2        | 4.76%   |
| Italy        | 2        | 4.76%   |
| Germany      | 2        | 4.76%   |
| France       | 2        | 4.76%   |
| Sweden       | 1        | 2.38%   |
| Spain        | 1        | 2.38%   |
| South Africa | 1        | 2.38%   |
| Serbia       | 1        | 2.38%   |
| Russia       | 1        | 2.38%   |
| Puerto Rico  | 1        | 2.38%   |
| Namibia      | 1        | 2.38%   |
| Mexico       | 1        | 2.38%   |
| India        | 1        | 2.38%   |
| Argentina    | 1        | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Rio de Janeiro       | 3        | 7.14%   |
| Campinas             | 2        | 4.76%   |
| Windhoek             | 1        | 2.38%   |
| Warsaw               | 1        | 2.38%   |
| Toronto              | 1        | 2.38%   |
| Stourbridge          | 1        | 2.38%   |
| Stockholm            | 1        | 2.38%   |
| Sparta               | 1        | 2.38%   |
| Siegburg             | 1        | 2.38%   |
| Sao Paulo            | 1        | 2.38%   |
| Salt Lake City       | 1        | 2.38%   |
| Saloa                | 1        | 2.38%   |
| Pretoria             | 1        | 2.38%   |
| Port Coquitlam       | 1        | 2.38%   |
| Patchogue            | 1        | 2.38%   |
| Novi Karlovci        | 1        | 2.38%   |
| NiterÃ³i           | 1        | 2.38%   |
| Newcastle upon Tyne  | 1        | 2.38%   |
| Newburgh             | 1        | 2.38%   |
| Missoula             | 1        | 2.38%   |
| Milan                | 1        | 2.38%   |
| Melbourne            | 1        | 2.38%   |
| Madrid               | 1        | 2.38%   |
| Lares                | 1        | 2.38%   |
| Kochi                | 1        | 2.38%   |
| Ingolstadt           | 1        | 2.38%   |
| Holmen               | 1        | 2.38%   |
| Guadalajara          | 1        | 2.38%   |
| Genoa                | 1        | 2.38%   |
| Duluth               | 1        | 2.38%   |
| Columbus             | 1        | 2.38%   |
| ChorzÃ³w           | 1        | 2.38%   |
| Chicago              | 1        | 2.38%   |
| Chatenois-les-Forges | 1        | 2.38%   |
| Buenos Aires         | 1        | 2.38%   |
| Brampton             | 1        | 2.38%   |
| Bolshoy Kamen        | 1        | 2.38%   |
| Battle Creek         | 1        | 2.38%   |
| Amiens               | 1        | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 25     | 25.71%  |
| WDC                 | 15       | 19     | 21.43%  |
| Samsung Electronics | 11       | 11     | 15.71%  |
| SanDisk             | 7        | 7      | 10%     |
| Transcend           | 2        | 2      | 2.86%   |
| Toshiba             | 2        | 2      | 2.86%   |
| SPCC                | 2        | 2      | 2.86%   |
| Kingston            | 2        | 2      | 2.86%   |
| Crucial             | 2        | 2      | 2.86%   |
| SATAFIRM            | 1        | 1      | 1.43%   |
| PNY                 | 1        | 1      | 1.43%   |
| Phison              | 1        | 1      | 1.43%   |
| OCZ                 | 1        | 1      | 1.43%   |
| MAXTOR              | 1        | 1      | 1.43%   |
| JMicron             | 1        | 1      | 1.43%   |
| Apacer              | 1        | 2      | 1.43%   |
| AFOX                | 1        | 1      | 1.43%   |
| A-DATA Technology   | 1        | 1      | 1.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB       | 4        | 5.13%   |
| Seagate ST1000DM003-1CH162 1TB       | 2        | 2.56%   |
| Seagate Expansion Desk 4TB           | 2        | 2.56%   |
| SanDisk SDSSDX240GG25 240GB          | 2        | 2.56%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1        | 1.28%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1        | 1.28%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 1.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 1.28%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1        | 1.28%   |
| WDC WD6402AAEX-00Y9A0 640GB          | 1        | 1.28%   |
| WDC WD6401AALS-00L3B2 640GB          | 1        | 1.28%   |
| WDC WD5000AVVS-63M8B0 500GB          | 1        | 1.28%   |
| WDC WD5000AAKS-75A7B2 500GB          | 1        | 1.28%   |
| WDC WD3200AAKS-61L9A0 320GB          | 1        | 1.28%   |
| WDC WD30EZRZ-00WN9B0 3TB             | 1        | 1.28%   |
| WDC WD30EZRX-00MMMB0 3TB             | 1        | 1.28%   |
| WDC WD20EADS-00R6B0 2TB              | 1        | 1.28%   |
| WDC WD1600JB-32FUA0 160GB            | 1        | 1.28%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 1.28%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1        | 1.28%   |
| WDC WD10EADS-22M2B0 1TB              | 1        | 1.28%   |
| WDC WD1001FALS-00J7B0 1TB            | 1        | 1.28%   |
| Transcend TS32GMTS400 32GB SSD       | 1        | 1.28%   |
| Transcend TS128GSSD360S 128GB        | 1        | 1.28%   |
| Toshiba MQ01ABD050 500GB             | 1        | 1.28%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 1        | 1.28%   |
| SPCC Solid State Disk 512GB          | 1        | 1.28%   |
| SPCC Solid State Disk 128GB          | 1        | 1.28%   |
| Seagate ST9160310AS 160GB            | 1        | 1.28%   |
| Seagate ST500LT012-9WS142 500GB      | 1        | 1.28%   |
| Seagate ST500DM009-2F110A 500GB      | 1        | 1.28%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1.28%   |
| Seagate ST3750640NS 752GB            | 1        | 1.28%   |
| Seagate ST3160811AS 160GB            | 1        | 1.28%   |
| Seagate ST31000528AS 1TB             | 1        | 1.28%   |
| Seagate ST2000DX002-2DV164 2TB       | 1        | 1.28%   |
| Seagate ST2000DM006-2DM164 2TB       | 1        | 1.28%   |
| Seagate ST2000DM001-1ER164 2TB       | 1        | 1.28%   |
| Seagate ST2000DM001-1CH164 2TB       | 1        | 1.28%   |
| Seagate ST2000DM 008-2FR102 2TB      | 1        | 1.28%   |
| Seagate Expansion+ 2TB               | 1        | 1.28%   |
| Seagate Backup+ Hub BK 4TB           | 1        | 1.28%   |
| SATAFIRM S11 240GB SSD               | 1        | 1.28%   |
| SanDisk SDSSDA240G 240GB             | 1        | 1.28%   |
| SanDisk SDSSDA120G 120GB             | 1        | 1.28%   |
| SanDisk SD8SNAT128G1002 128GB SSD    | 1        | 1.28%   |
| SanDisk SD8SBAT128G1122 128GB SSD    | 1        | 1.28%   |
| Sandisk NVMe SSD Drive 256GB         | 1        | 1.28%   |
| Samsung SSD 860 EVO 500GB            | 1        | 1.28%   |
| Samsung SSD 860 EVO 1TB              | 1        | 1.28%   |
| Samsung SSD 850 EVO 500GB            | 1        | 1.28%   |
| Samsung SSD 840 Series 120GB         | 1        | 1.28%   |
| Samsung SSD 840 EVO 500GB mSATA      | 1        | 1.28%   |
| Samsung SSD 840 EVO 120GB            | 1        | 1.28%   |
| Samsung NVMe SSD Drive 500GB         | 1        | 1.28%   |
| Samsung NVMe SSD Drive 250GB         | 1        | 1.28%   |
| Samsung MZNLF128HCHP-000H1 128GB SSD | 1        | 1.28%   |
| Samsung HD103SJ 1TB                  | 1        | 1.28%   |
| Samsung HD103SI 1TB                  | 1        | 1.28%   |
| PNY CS900 120GB SSD                  | 1        | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 25     | 52.94%  |
| WDC                 | 11       | 14     | 32.35%  |
| Samsung Electronics | 2        | 2      | 5.88%   |
| Toshiba             | 1        | 1      | 2.94%   |
| MAXTOR              | 1        | 1      | 2.94%   |
| JMicron             | 1        | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 7      | 23.33%  |
| SanDisk             | 6        | 6      | 20%     |
| WDC                 | 4        | 4      | 13.33%  |
| Transcend           | 2        | 2      | 6.67%   |
| SPCC                | 2        | 2      | 6.67%   |
| Kingston            | 2        | 2      | 6.67%   |
| Crucial             | 2        | 2      | 6.67%   |
| SATAFIRM            | 1        | 1      | 3.33%   |
| PNY                 | 1        | 1      | 3.33%   |
| OCZ                 | 1        | 1      | 3.33%   |
| Apacer              | 1        | 2      | 3.33%   |
| A-DATA Technology   | 1        | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 27       | 44     | 46.55%  |
| SSD     | 24       | 31     | 41.38%  |
| NVMe    | 6        | 6      | 10.34%  |
| Unknown | 1        | 1      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 41       | 70     | 78.85%  |
| NVMe | 6        | 6      | 11.54%  |
| SAS  | 5        | 6      | 9.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 31       | 39     | 52.54%  |
| 0.51-1.0   | 16       | 23     | 27.12%  |
| 1.01-2.0   | 7        | 8      | 11.86%  |
| 3.01-4.0   | 3        | 3      | 5.08%   |
| 2.01-3.0   | 2        | 2      | 3.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 30.95%  |
| 251-500        | 9        | 21.43%  |
| 501-1000       | 6        | 14.29%  |
| 21-50          | 4        | 9.52%   |
| 1001-2000      | 3        | 7.14%   |
| 1-20           | 3        | 7.14%   |
| More than 3000 | 2        | 4.76%   |
| 2001-3000      | 1        | 2.38%   |
| 51-100         | 1        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 21       | 48.84%  |
| 1-20      | 11       | 25.58%  |
| 51-100    | 5        | 11.63%  |
| 251-500   | 2        | 4.65%   |
| 2001-3000 | 2        | 4.65%   |
| 101-250   | 2        | 4.65%   |

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
| Detected | 41       | 80     | 97.62%  |
| Works    | 1        | 2      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 28       | 48.28%  |
| AMD                           | 11       | 18.97%  |
| JMicron Technology            | 4        | 6.9%    |
| ASMedia Technology            | 3        | 5.17%   |
| Sandisk                       | 2        | 3.45%   |
| Samsung Electronics           | 2        | 3.45%   |
| Nvidia                        | 2        | 3.45%   |
| Toshiba America Info Systems  | 1        | 1.72%   |
| Silicon Image                 | 1        | 1.72%   |
| Promise Technology            | 1        | 1.72%   |
| Phison Electronics            | 1        | 1.72%   |
| Marvell Technology Group      | 1        | 1.72%   |
| Integrated Technology Express | 1        | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 5.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 5.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.95%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 3.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.63%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 2.63%   |
| JMicron JMB368 IDE controller                                                           | 2        | 2.63%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 2.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.63%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.32%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 1.32%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.32%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 1.32%   |
| Promise PDC20262 (FastTrak66/Ultra66)                                                   | 1        | 1.32%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.32%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.32%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 1.32%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 1.32%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.32%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 1.32%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.32%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1        | 1.32%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.32%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.32%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.32%   |
| Integrated Express IT8212 Dual channel ATA RAID controller                              | 1        | 1.32%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.32%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.32%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.32%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.32%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 30       | 51.72%  |
| IDE  | 18       | 31.03%  |
| NVMe | 6        | 10.34%  |
| RAID | 4        | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 29       | 69.05%  |
| AMD    | 13       | 30.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 4.76%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 4.76%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 2.38%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 2.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 2.38%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 2.38%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 2.38%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 2.38%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 2.38%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 2.38%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 2.38%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 2.38%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2.38%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1        | 2.38%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1        | 2.38%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 2.38%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1        | 2.38%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 2.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 2.38%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1        | 2.38%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 1        | 2.38%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 1        | 2.38%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 2.38%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 2.38%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 1        | 2.38%   |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1        | 2.38%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 2.38%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 1        | 2.38%   |
| Intel Atom CPU D2700 @ 2.13GHz              | 1        | 2.38%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 2.38%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 2.38%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1        | 2.38%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 1        | 2.38%   |
| AMD Phenom II X4 830 Processor              | 1        | 2.38%   |
| AMD Phenom II X2 565 Processor              | 1        | 2.38%   |
| AMD FX-6300 Six-Core Processor              | 1        | 2.38%   |
| AMD FX-6100 Six-Core Processor              | 1        | 2.38%   |
| AMD Athlon II X2 220 Processor              | 1        | 2.38%   |
| AMD A8-3850 APU with Radeon HD Graphics     | 1        | 2.38%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 1        | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 11       | 26.19%  |
| Intel Core i3      | 5        | 11.9%   |
| Intel Core i7      | 4        | 9.52%   |
| AMD FX             | 4        | 9.52%   |
| Intel Core 2 Quad  | 3        | 7.14%   |
| AMD Ryzen 5        | 3        | 7.14%   |
| Intel Celeron      | 2        | 4.76%   |
| Intel Pentium Dual | 1        | 2.38%   |
| Intel Core 2 Duo   | 1        | 2.38%   |
| Intel Core 2       | 1        | 2.38%   |
| Intel Atom         | 1        | 2.38%   |
| AMD Ryzen 7        | 1        | 2.38%   |
| AMD Phenom II X4   | 1        | 2.38%   |
| AMD Phenom II X2   | 1        | 2.38%   |
| AMD Athlon II X2   | 1        | 2.38%   |
| AMD A8             | 1        | 2.38%   |
| AMD A10            | 1        | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 22       | 52.38%  |
| 2      | 14       | 33.33%  |
| 6      | 3        | 7.14%   |
| 3      | 2        | 4.76%   |
| 8      | 1        | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 42       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 52.38%  |
| 2      | 20       | 47.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 42       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 3        | 7.14%   |
| 0x306a9    | 3        | 7.14%   |
| 0x206a7    | 3        | 7.14%   |
| 0x06000852 | 3        | 7.14%   |
| 0x010000c8 | 3        | 7.14%   |
| Unknown    | 3        | 7.14%   |
| 0x20652    | 2        | 4.76%   |
| 0x1067a    | 2        | 4.76%   |
| 0x906ed    | 1        | 2.38%   |
| 0x906e9    | 1        | 2.38%   |
| 0x806e9    | 1        | 2.38%   |
| 0x6fd      | 1        | 2.38%   |
| 0x6fb      | 1        | 2.38%   |
| 0x6f2      | 1        | 2.38%   |
| 0x306c3    | 1        | 2.38%   |
| 0x30678    | 1        | 2.38%   |
| 0x30673    | 1        | 2.38%   |
| 0x30661    | 1        | 2.38%   |
| 0x20655    | 1        | 2.38%   |
| 0x106e5    | 1        | 2.38%   |
| 0x106a5    | 1        | 2.38%   |
| 0x10676    | 1        | 2.38%   |
| 0x08701021 | 1        | 2.38%   |
| 0x08101016 | 1        | 2.38%   |
| 0x08001138 | 1        | 2.38%   |
| 0x06001119 | 1        | 2.38%   |
| 0x0600063e | 1        | 2.38%   |
| 0x03000027 | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Piledriver  | 4        | 9.52%   |
| Westmere    | 3        | 7.14%   |
| Skylake     | 3        | 7.14%   |
| SandyBridge | 3        | 7.14%   |
| Penryn      | 3        | 7.14%   |
| KabyLake    | 3        | 7.14%   |
| K10         | 3        | 7.14%   |
| IvyBridge   | 3        | 7.14%   |
| Haswell     | 3        | 7.14%   |
| Core        | 3        | 7.14%   |
| Zen 2       | 2        | 4.76%   |
| Zen         | 2        | 4.76%   |
| Silvermont  | 2        | 4.76%   |
| Nehalem     | 2        | 4.76%   |
| K10 Llano   | 1        | 2.38%   |
| Bulldozer   | 1        | 2.38%   |
| Bonnell     | 1        | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 19       | 42.22%  |
| Intel  | 15       | 33.33%  |
| AMD    | 11       | 24.44%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 4.44%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 2        | 4.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 4.44%   |
| Intel HD Graphics 530                                                       | 2        | 4.44%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 4.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 4.44%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 4.44%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 2.22%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.22%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.22%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 2.22%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.22%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 2.22%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 2.22%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 2.22%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.22%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.22%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 2.22%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 2.22%   |
| Nvidia G96CM [GeForce 9600M GS]                                             | 1        | 2.22%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 2.22%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 2.22%   |
| Intel HD Graphics 630                                                       | 1        | 2.22%   |
| Intel HD Graphics 620                                                       | 1        | 2.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.22%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 2.22%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 2.22%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.22%   |
| AMD Sumo [Radeon HD 6550D]                                                  | 1        | 2.22%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 2.22%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 2.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.22%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 2.22%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.22%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 2.22%   |
| AMD Barts XT [Radeon HD 6870]                                               | 1        | 2.22%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 18       | 42.86%  |
| 1 x Intel      | 12       | 28.57%  |
| 1 x AMD        | 11       | 26.19%  |
| Intel + Nvidia | 1        | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 33       | 78.57%  |
| Proprietary | 6        | 14.29%  |
| Unknown     | 3        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 33.33%  |
| 0.51-1.0   | 8        | 19.05%  |
| 1.01-2.0   | 6        | 14.29%  |
| 0.01-0.5   | 5        | 11.9%   |
| 2.01-3.0   | 4        | 9.52%   |
| 3.01-4.0   | 3        | 7.14%   |
| 7.01-8.0   | 1        | 2.38%   |
| 5.01-6.0   | 1        | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Ancor Communications | 6        | 15%     |
| Samsung Electronics  | 5        | 12.5%   |
| AOC                  | 4        | 10%     |
| Acer                 | 4        | 10%     |
| Philips              | 3        | 7.5%    |
| Hewlett-Packard      | 3        | 7.5%    |
| Goldstar             | 3        | 7.5%    |
| ViewSonic            | 2        | 5%      |
| Dell                 | 2        | 5%      |
| ___                  | 1        | 2.5%    |
| Tech Concepts        | 1        | 2.5%    |
| Microstep            | 1        | 2.5%    |
| Insignia             | 1        | 2.5%    |
| Idek Iiyama          | 1        | 2.5%    |
| HKC                  | 1        | 2.5%    |
| BenQ                 | 1        | 2.5%    |
| Unknown              | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ___ AAA ___01FF 1366x768 700x390mm 31.5-inch                          | 1        | 2.38%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1        | 2.38%   |
| ViewSonic VA2013wSERIES VSCF122 1600x900 443x249mm 20.0-inch          | 1        | 2.38%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                            | 1        | 2.38%   |
| Samsung Electronics T24C310 SAM0AEA 1920x1080 531x299mm 24.0-inch     | 1        | 2.38%   |
| Samsung Electronics SMT22A550 SAM07AE 1920x1080 477x268mm 21.5-inch   | 1        | 2.38%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch     | 1        | 2.38%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch  | 1        | 2.38%   |
| Samsung Electronics LCD Monitor S24B300 3840x1080                     | 1        | 2.38%   |
| Philips PHL 241P4 PHL08D5 1920x1080 531x299mm 24.0-inch               | 1        | 2.38%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch             | 1        | 2.38%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 1        | 2.38%   |
| Microstep LCD Monitor MSI MAG341CQ 3440x1440                          | 1        | 2.38%   |
| Insignia NS28D310NA15 BBY0028 1680x1050 640x384mm 29.4-inch           | 1        | 2.38%   |
| Idek Iiyama LCD Monitor PL2473HD 1920x1080                            | 1        | 2.38%   |
| HKC LCD Monitor HKC2400 1920x1080 597x336mm 27.0-inch                 | 1        | 2.38%   |
| Hewlett-Packard v185e HWP2838 1366x768 410x230mm 18.5-inch            | 1        | 2.38%   |
| Hewlett-Packard LCD Monitor w2338h                                    | 1        | 2.38%   |
| Hewlett-Packard Compaq W185q HWP284F 1366x768 410x230mm 18.5-inch     | 1        | 2.38%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                  | 1        | 2.38%   |
| Goldstar RZ32LZ55 GSM7546 1360x768 930x523mm 42.0-inch                | 1        | 2.38%   |
| Goldstar M237WDP GSM5778 1920x1080 510x290mm 23.1-inch                | 1        | 2.38%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1        | 2.38%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 1        | 2.38%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch              | 1        | 2.38%   |
| BenQ FP71V+ BNQ76A2 1280x1024 376x301mm 19.0-inch                     | 1        | 2.38%   |
| AOC 519W AOC1519 1280x720 340x270mm 17.1-inch                         | 1        | 2.38%   |
| AOC 2770 AOC2770 1920x1080 598x336mm 27.0-inch                        | 1        | 2.38%   |
| AOC 2752 AOC2752 1920x1080 579x336mm 26.4-inch                        | 1        | 2.38%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 1        | 2.38%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 1        | 2.38%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 1        | 2.38%   |
| Ancor Communications MW221 ACI22B1 1680x1050 470x300mm 22.0-inch      | 1        | 2.38%   |
| Ancor Communications LCD Monitor ASUS VS228 1920x1080                 | 1        | 2.38%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 1        | 2.38%   |
| Ancor Communications ASUS VG278 ACI27E1 1920x1080 598x336mm 27.0-inch | 1        | 2.38%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch | 1        | 2.38%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 1        | 2.38%   |
| Acer H6510BD ACR1535 1920x1080                                        | 1        | 2.38%   |
| Acer CB282K ACR075F 3840x2160 621x341mm 27.9-inch                     | 1        | 2.38%   |
| Acer B226HQL ACR0330 1920x1080 477x268mm 21.5-inch                    | 1        | 2.38%   |
| Unknown                                                               | 1        | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 44.74%  |
| 1366x768 (WXGA)    | 5        | 13.16%  |
| 1360x768           | 3        | 7.89%   |
| 3840x2160 (4K)     | 2        | 5.26%   |
| 1680x1050 (WSXGA+) | 2        | 5.26%   |
| 1600x900 (HD+)     | 2        | 5.26%   |
| 3840x1080          | 1        | 2.63%   |
| 3440x1440          | 1        | 2.63%   |
| 2560x1440 (QHD)    | 1        | 2.63%   |
| 1920x1200 (WUXGA)  | 1        | 2.63%   |
| 1280x720 (HD)      | 1        | 2.63%   |
| 1280x1024 (SXGA)   | 1        | 2.63%   |
| Unknown            | 1        | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 8        | 20%     |
| 24      | 6        | 15%     |
| Unknown | 6        | 15%     |
| 21      | 4        | 10%     |
| 18      | 4        | 10%     |
| 31      | 3        | 7.5%    |
| 23      | 2        | 5%      |
| 22      | 2        | 5%      |
| 19      | 2        | 5%      |
| 42      | 1        | 2.5%    |
| 20      | 1        | 2.5%    |
| 17      | 1        | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 34.21%  |
| 401-500     | 12       | 31.58%  |
| Unknown     | 6        | 15.79%  |
| 601-700     | 4        | 10.53%  |
| 351-400     | 1        | 2.63%   |
| 301-350     | 1        | 2.63%   |
| 901-1000    | 1        | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 26       | 72.22%  |
| Unknown | 5        | 13.89%  |
| 16/10   | 3        | 8.33%   |
| 5/4     | 2        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 23.08%  |
| 301-350        | 8        | 20.51%  |
| Unknown        | 6        | 15.38%  |
| 151-200        | 5        | 12.82%  |
| 141-150        | 5        | 12.82%  |
| 351-500        | 3        | 7.69%   |
| 251-300        | 2        | 5.13%   |
| 501-1000       | 1        | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 59.46%  |
| Unknown | 6        | 16.22%  |
| 1-50    | 4        | 10.81%  |
| 101-120 | 4        | 10.81%  |
| 121-160 | 1        | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 80.95%  |
| 2     | 5        | 11.9%   |
| 0     | 2        | 4.76%   |
| 3     | 1        | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 33       | 53.23%  |
| Intel                           | 11       | 17.74%  |
| Qualcomm Atheros                | 4        | 6.45%   |
| Ralink                          | 3        | 4.84%   |
| TP-Link                         | 2        | 3.23%   |
| Nvidia                          | 2        | 3.23%   |
| Qualcomm Atheros Communications | 1        | 1.61%   |
| Motorola PCS                    | 1        | 1.61%   |
| Huawei Technologies             | 1        | 1.61%   |
| D-Link System                   | 1        | 1.61%   |
| D-Link                          | 1        | 1.61%   |
| Broadcom Limited                | 1        | 1.61%   |
| Broadcom                        | 1        | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 29       | 42.03%  |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2        | 2.9%    |
| Nvidia MCP61 Ethernet                                                                         | 2        | 2.9%    |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 2.9%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 1.45%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 1.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.45%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1        | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 1.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.45%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.45%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 1.45%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1        | 1.45%   |
| Motorola PCS moto g(30)                                                                       | 1        | 1.45%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 1.45%   |
| Intel Wireless 7265                                                                           | 1        | 1.45%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1        | 1.45%   |
| Intel 82578DM Gigabit Network Connection                                                      | 1        | 1.45%   |
| Intel 82578DC Gigabit Network Connection                                                      | 1        | 1.45%   |
| Intel 82566DC Gigabit Network Connection                                                      | 1        | 1.45%   |
| Huawei E353/E3131                                                                             | 1        | 1.45%   |
| D-Link System DWA-126 802.11n Wireless Adapter [Atheros AR9271]                               | 1        | 1.45%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1        | 1.45%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express                               | 1        | 1.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 1.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 8        | 33.33%  |
| Intel                           | 5        | 20.83%  |
| Ralink                          | 3        | 12.5%   |
| TP-Link                         | 2        | 8.33%   |
| Qualcomm Atheros                | 2        | 8.33%   |
| Qualcomm Atheros Communications | 1        | 4.17%   |
| D-Link System                   | 1        | 4.17%   |
| D-Link                          | 1        | 4.17%   |
| Broadcom                        | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 3        | 12.5%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 8.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 4.17%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 4.17%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 4.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 4.17%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1        | 4.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 4.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 4.17%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 4.17%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 4.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 4.17%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1        | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 4.17%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 4.17%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1        | 4.17%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 4.17%   |
| Intel Wireless 7265                                                                           | 1        | 4.17%   |
| D-Link System DWA-126 802.11n Wireless Adapter [Atheros AR9271]                               | 1        | 4.17%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1        | 4.17%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 31       | 68.89%  |
| Intel                 | 7        | 15.56%  |
| Qualcomm Atheros      | 2        | 4.44%   |
| Nvidia                | 2        | 4.44%   |
| Motorola PCS          | 1        | 2.22%   |
| Huawei Technologies   | 1        | 2.22%   |
| Broadcom Limited      | 1        | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 64.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 4.44%   |
| Nvidia MCP61 Ethernet                                             | 2        | 4.44%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 4.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.22%   |
| Motorola PCS moto g(30)                                           | 1        | 2.22%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.22%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.22%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.22%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 2.22%   |
| Huawei E353/E3131                                                 | 1        | 2.22%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 42       | 66.67%  |
| WiFi     | 21       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 69.64%  |
| WiFi     | 17       | 30.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 69.05%  |
| 2     | 13       | 30.95%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 61.9%   |
| Yes  | 16       | 38.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 35.71%  |
| Cambridge Silicon Radio         | 4        | 28.57%  |
| ASUSTek Computer                | 2        | 14.29%  |
| Ralink                          | 1        | 7.14%   |
| Qualcomm Atheros Communications | 1        | 7.14%   |
| Hewlett-Packard                 | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 28.57%  |
| Intel AX200 Bluetooth                               | 3        | 21.43%  |
| Intel Bluetooth wireless interface                  | 2        | 14.29%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 14.29%  |
| Ralink RT3290 Bluetooth                             | 1        | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 7.14%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 26       | 35.14%  |
| Nvidia                    | 17       | 22.97%  |
| AMD                       | 16       | 21.62%  |
| C-Media Electronics       | 4        | 5.41%   |
| GN Netcom                 | 2        | 2.7%    |
| Texas Instruments         | 1        | 1.35%   |
| Sennheiser Communications | 1        | 1.35%   |
| ROCCAT                    | 1        | 1.35%   |
| Microsoft                 | 1        | 1.35%   |
| M-Audio                   | 1        | 1.35%   |
| JMTek                     | 1        | 1.35%   |
| iSoft Silicon             | 1        | 1.35%   |
| Creative Labs             | 1        | 1.35%   |
| AOKEO                     | 1        | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 6.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 6.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 4.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 3.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 2.47%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 2.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.47%   |
| Nvidia GK110 High Definition Audio Controller                              | 2        | 2.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.47%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 2.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.47%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.47%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.47%   |
| Texas Instruments PCM2903B Audio CODEC                                     | 1        | 1.23%   |
| Sennheiser Communications PXC 550                                          | 1        | 1.23%   |
| ROCCAT Juke                                                                | 1        | 1.23%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.23%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.23%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.23%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.23%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 1.23%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.23%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 1.23%   |
| Microsoft LifeChat LX-3000 Headset                                         | 1        | 1.23%   |
| M-Audio M-Audio Fast Track MKII                                            | 1        | 1.23%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.23%   |
| iSoft Silicon USB Ear-Microphone                                           | 1        | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 1        | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 1.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.23%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.23%   |
| GN Netcom Jabra Link 380                                                   | 1        | 1.23%   |
| GN Netcom Jabra Link 370                                                   | 1        | 1.23%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 1.23%   |
| C-Media Electronics Blue Snowball                                          | 1        | 1.23%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.23%   |
| AOKEO LCS_USB_Audio                                                        | 1        | 1.23%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 1.23%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.23%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.23%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1        | 1.23%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 1        | 1.23%   |

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
| Microsoft                 | 2        | 16.67%  |
| Logitech                  | 2        | 16.67%  |
| Chicony Electronics       | 2        | 16.67%  |
| YGTek                     | 1        | 8.33%   |
| webcam                    | 1        | 8.33%   |
| Silicon Motion            | 1        | 8.33%   |
| SHENZHEN EMEET TECHNOLOGY | 1        | 8.33%   |
| Jieli Technology          | 1        | 8.33%   |
| Creative Technology       | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| YGTek Webcam                                   | 1        | 8.33%   |
| webcam webcam                                  | 1        | 8.33%   |
| Silicon Motion SM731 Camera                    | 1        | 8.33%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1        | 8.33%   |
| Microsoft LifeCam VX-5000                      | 1        | 8.33%   |
| Microsoft LifeCam VX-500 [1357]                | 1        | 8.33%   |
| Logitech Webcam C600                           | 1        | 8.33%   |
| Logitech C922 Pro Stream Webcam                | 1        | 8.33%   |
| Jieli USB PHY 2.0                              | 1        | 8.33%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 8.33%   |
| Chicony CNF7042                                | 1        | 8.33%   |
| Chicony 2.0M UVC Webcam / CNF7129              | 1        | 8.33%   |

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
| 0     | 33       | 78.57%  |
| 1     | 9        | 21.43%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 5        | 55.56%  |
| Graphics card | 3        | 33.33%  |
| Bluetooth     | 1        | 11.11%  |

