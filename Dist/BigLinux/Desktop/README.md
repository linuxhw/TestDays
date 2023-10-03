BigLinux - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for BigLinux.

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

Total: 47

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | H61                         | [5dd60be36a](https://linux-hardware.org/?probe=5dd60be36a) | Sep 14, 2023 |
| PCWare        | IPMH81G1                    | [181367c2db](https://linux-hardware.org/?probe=181367c2db) | Sep 12, 2023 |
| Biostar       | G31M+                       | [24eb0eb2db](https://linux-hardware.org/?probe=24eb0eb2db) | Sep 06, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [73e3b8ef8a](https://linux-hardware.org/?probe=73e3b8ef8a) | Sep 04, 2023 |
| ASUSTek       | PRIME H410M-D               | [332e78dfba](https://linux-hardware.org/?probe=332e78dfba) | Sep 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [9cf292357b](https://linux-hardware.org/?probe=9cf292357b) | Aug 30, 2023 |
| Daten Tecn... | DH110MXV                    | [a2487119a6](https://linux-hardware.org/?probe=a2487119a6) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | [f9a1d993b2](https://linux-hardware.org/?probe=f9a1d993b2) | Jul 07, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [613d703a17](https://linux-hardware.org/?probe=613d703a17) | Jun 10, 2023 |
| Toshiba       | STI 005492G                 | [4f161f4ed0](https://linux-hardware.org/?probe=4f161f4ed0) | May 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| HP            | 1495                        | [96283c0a09](https://linux-hardware.org/?probe=96283c0a09) | Apr 01, 2023 |
| HP            | 1495                        | [f25125625a](https://linux-hardware.org/?probe=f25125625a) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| HP            | 3397                        | [0b74e11cdd](https://linux-hardware.org/?probe=0b74e11cdd) | Mar 12, 2023 |
| HP            | 1495                        | [058beaa7d1](https://linux-hardware.org/?probe=058beaa7d1) | Mar 12, 2023 |
| HP            | 1495                        | [517a7a6401](https://linux-hardware.org/?probe=517a7a6401) | Mar 12, 2023 |
| Lenovo        | NOK                         | [2e90ce2e87](https://linux-hardware.org/?probe=2e90ce2e87) | Mar 10, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| Intel         | H61                         | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7c6973f1fa](https://linux-hardware.org/?probe=7c6973f1fa) | Feb 21, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [4bcfe32668](https://linux-hardware.org/?probe=4bcfe32668) | Feb 12, 2023 |
| Intel         | H61                         | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| BESSTAR Te... | HM90                        | [3f958de9bb](https://linux-hardware.org/?probe=3f958de9bb) | Feb 01, 2023 |
| Intel         | H55                         | [4fdea85eec](https://linux-hardware.org/?probe=4fdea85eec) | Jan 14, 2023 |
| Intel         | H55                         | [d875a18037](https://linux-hardware.org/?probe=d875a18037) | Jan 14, 2023 |
| Gigabyte      | Z87-HD3                     | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Gigabyte      | Z87-HD3                     | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| eMachines     | EMCP61M                     | [711594c5b4](https://linux-hardware.org/?probe=711594c5b4) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| Intel         | DH61WW AAG23116-203         | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| ASUSTek       | Z87M-PLUS                   | [0efc94e34d](https://linux-hardware.org/?probe=0efc94e34d) | Jul 24, 2022 |
| Intel         | DH61WW AAG23116-203         | [cfd6e87e09](https://linux-hardware.org/?probe=cfd6e87e09) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | [c30806c628](https://linux-hardware.org/?probe=c30806c628) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | [b805fa0cd8](https://linux-hardware.org/?probe=b805fa0cd8) | Jul 23, 2022 |
| ECS           | H67H2-M2                    | [d82e4c4eb4](https://linux-hardware.org/?probe=d82e4c4eb4) | Apr 10, 2021 |
| ASUSTek       | H110M-C/BR                  | [0c4cd978f2](https://linux-hardware.org/?probe=0c4cd978f2) | Jul 24, 2020 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [3cef63e59d](https://linux-hardware.org/?probe=3cef63e59d) | Jul 17, 2020 |
| PCWare        | IPX1800E2                   | [0990462881](https://linux-hardware.org/?probe=0990462881) | Jun 21, 2020 |
| PCWare        | IPX1800E2                   | [93916c17f2](https://linux-hardware.org/?probe=93916c17f2) | Jun 21, 2020 |
| ASRock        | 775Dual-VSTA                | [0e5ac5a0bf](https://linux-hardware.org/?probe=0e5ac5a0bf) | Jun 12, 2020 |
| ASRock        | 775Dual-VSTA                | [a4f3841c00](https://linux-hardware.org/?probe=a4f3841c00) | May 29, 2020 |
| ASRock        | 775Dual-VSTA                | [3fe70d9fdd](https://linux-hardware.org/?probe=3fe70d9fdd) | May 06, 2020 |
| ASRock        | 775Dual-VSTA                | [8fa9935547](https://linux-hardware.org/?probe=8fa9935547) | Apr 27, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| BigLinux 20.04            | 5        | 14.71%  |
| BigLinux 23.0.0           | 4        | 11.76%  |
| BigLinux 22.0.4           | 3        | 8.82%   |
| BigLinux 23.02.20         | 2        | 5.88%   |
| BigLinux 23.0.1           | 2        | 5.88%   |
| BigLinux 22.1.0           | 2        | 5.88%   |
| BigLinux 22.0.0           | 2        | 5.88%   |
| BigLinux 21.3.5           | 2        | 5.88%   |
| BigLinux 23.02.24         | 1        | 2.94%   |
| BigLinux 23.02.07         | 1        | 2.94%   |
| BigLinux 23.01.30         | 1        | 2.94%   |
| BigLinux 22.12.24         | 1        | 2.94%   |
| BigLinux 22.10.28         | 1        | 2.94%   |
| BigLinux 22.1.1           | 1        | 2.94%   |
| BigLinux 22.09.09         | 1        | 2.94%   |
| BigLinux 22.0.2           | 1        | 2.94%   |
| BigLinux 21.3.7           | 1        | 2.94%   |
| BigLinux 2023-06-30_08-01 | 1        | 2.94%   |
| BigLinux 2023-06-07_06-02 | 1        | 2.94%   |
| BigLinux 19.04            | 1        | 2.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| BigLinux | 32       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.1.12-1-MANJARO      | 4        | 11.11%  |
| 6.4.12-1-MANJARO      | 2        | 5.56%   |
| 6.1.51-1-MANJARO      | 2        | 5.56%   |
| 6.1.31-2-MANJARO      | 2        | 5.56%   |
| 5.4.0-37-generic      | 2        | 5.56%   |
| 5.15.94-1-MANJARO     | 2        | 5.56%   |
| 5.15.71-1-MANJARO     | 2        | 5.56%   |
| 5.15.60-1-MANJARO     | 2        | 5.56%   |
| 6.2.12-1-MANJARO      | 1        | 2.78%   |
| 6.1.9-x64v1-xanmod1-1 | 1        | 2.78%   |
| 6.1.9-1-MANJARO       | 1        | 2.78%   |
| 6.1.49-1-MANJARO      | 1        | 2.78%   |
| 6.1.26-1-MANJARO      | 1        | 2.78%   |
| 6.1.23-1-MANJARO      | 1        | 2.78%   |
| 5.8.0-48-generic      | 1        | 2.78%   |
| 5.7.9-xanmod1         | 1        | 2.78%   |
| 5.6.6-xanmod1         | 1        | 2.78%   |
| 5.6.10-xanmod1        | 1        | 2.78%   |
| 5.4.0-33-generic      | 1        | 2.78%   |
| 5.4.0-31-generic      | 1        | 2.78%   |
| 5.17.15-1-MANJARO     | 1        | 2.78%   |
| 5.16.11-1-BIGLINUX    | 1        | 2.78%   |
| 5.15.89-1-MANJARO     | 1        | 2.78%   |
| 5.15.85-1-MANJARO     | 1        | 2.78%   |
| 5.15.76-1-MANJARO     | 1        | 2.78%   |
| 5.15.55-1-MANJARO     | 1        | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.12  | 4        | 11.43%  |
| 5.4.0   | 3        | 8.57%   |
| 6.4.12  | 2        | 5.71%   |
| 6.1.9   | 2        | 5.71%   |
| 6.1.51  | 2        | 5.71%   |
| 6.1.31  | 2        | 5.71%   |
| 5.15.94 | 2        | 5.71%   |
| 5.15.71 | 2        | 5.71%   |
| 5.15.60 | 2        | 5.71%   |
| 6.2.12  | 1        | 2.86%   |
| 6.1.49  | 1        | 2.86%   |
| 6.1.26  | 1        | 2.86%   |
| 6.1.23  | 1        | 2.86%   |
| 5.8.0   | 1        | 2.86%   |
| 5.7.9   | 1        | 2.86%   |
| 5.6.6   | 1        | 2.86%   |
| 5.6.10  | 1        | 2.86%   |
| 5.17.15 | 1        | 2.86%   |
| 5.16.11 | 1        | 2.86%   |
| 5.15.89 | 1        | 2.86%   |
| 5.15.85 | 1        | 2.86%   |
| 5.15.76 | 1        | 2.86%   |
| 5.15.55 | 1        | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 13       | 40.63%  |
| 5.15    | 8        | 25%     |
| 5.4     | 3        | 9.38%   |
| 6.4     | 2        | 6.25%   |
| 6.2     | 1        | 3.13%   |
| 5.8     | 1        | 3.13%   |
| 5.7     | 1        | 3.13%   |
| 5.6     | 1        | 3.13%   |
| 5.17    | 1        | 3.13%   |
| 5.16    | 1        | 3.13%   |

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


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 28       | 87.5%   |
| KDE  | 4        | 12.5%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 31       | 96.88%  |
| Unknown | 1        | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 27       | 84.38%  |
| Unknown | 4        | 12.5%   |
| LXDM    | 1        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| pt_BR | 17       | 53.13%  |
| en_US | 7        | 21.88%  |
| pt_PT | 2        | 6.25%   |
| en_GB | 2        | 6.25%   |
| es_MX | 1        | 3.13%   |
| es_ES | 1        | 3.13%   |
| es_AR | 1        | 3.13%   |
| de_AT | 1        | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 19       | 59.38%  |
| BIOS | 13       | 40.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 31       | 96.88%  |
| Ext4  | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 18       | 54.55%  |
| MBR     | 10       | 30.3%   |
| Unknown | 5        | 15.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 53.13%  |
| No        | 15       | 46.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 6        | 18.75%  |
| ASUSTek Computer    | 6        | 18.75%  |
| Gigabyte Technology | 4        | 12.5%   |
| PCWare              | 2        | 6.25%   |
| MSI                 | 2        | 6.25%   |
| Lenovo              | 2        | 6.25%   |
| Hewlett-Packard     | 2        | 6.25%   |
| ASRock              | 2        | 6.25%   |
| Semp Toshiba        | 1        | 3.13%   |
| eMachines           | 1        | 3.13%   |
| ECS                 | 1        | 3.13%   |
| Daten Tecnologia    | 1        | 3.13%   |
| Biostar             | 1        | 3.13%   |
| BESSTAR Tech        | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Intel H61                                                    | 3        | 9.38%   |
| ASRock 775Dual-VSTA                                          | 2        | 6.25%   |
| Semp Toshiba STI                                             | 1        | 3.13%   |
| PCWare IPX1800E2                                             | 1        | 3.13%   |
| PCWare IPMH81G1                                              | 1        | 3.13%   |
| MSI MS-7C95                                                  | 1        | 3.13%   |
| MSI MS-7C91                                                  | 1        | 3.13%   |
| Lenovo ThinkCentre M93p 10AB0010US                           | 1        | 3.13%   |
| Lenovo 63 90AT0002BR                                         | 1        | 3.13%   |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V307 | 1        | 3.13%   |
| Intel H55                                                    | 1        | 3.13%   |
| Intel DH61WW AAG23116-203                                    | 1        | 3.13%   |
| HP Compaq Elite 8300 SFF                                     | 1        | 3.13%   |
| HP Compaq 8200 Elite SFF PC                                  | 1        | 3.13%   |
| Gigabyte Z87-HD3                                             | 1        | 3.13%   |
| Gigabyte X399 DESIGNARE EX                                   | 1        | 3.13%   |
| Gigabyte B560M AORUS ELITE                                   | 1        | 3.13%   |
| Gigabyte B550M AORUS ELITE                                   | 1        | 3.13%   |
| eMachines EL1321                                             | 1        | 3.13%   |
| ECS H67H2-M2                                                 | 1        | 3.13%   |
| Daten Tecnologia DH110MXV                                    | 1        | 3.13%   |
| Biostar G31M+                                                | 1        | 3.13%   |
| BESSTAR Tech HM90                                            | 1        | 3.13%   |
| ASUS Z170 PRO GAMING                                         | 1        | 3.13%   |
| ASUS TUF Gaming B450M-PRO S                                  | 1        | 3.13%   |
| ASUS TUF B360M-PLUS GAMING/BR                                | 1        | 3.13%   |
| ASUS PRIME H410M-D                                           | 1        | 3.13%   |
| ASUS H110M-C/BR                                              | 1        | 3.13%   |
| ASUS All Series                                              | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| Intel H61                 | 3        | 9.38%   |
| HP Compaq                 | 2        | 6.25%   |
| ASUS TUF                  | 2        | 6.25%   |
| ASRock 775Dual-VSTA       | 2        | 6.25%   |
| Semp Toshiba STI          | 1        | 3.13%   |
| PCWare IPX1800E2          | 1        | 3.13%   |
| PCWare IPMH81G1           | 1        | 3.13%   |
| MSI MS-7C95               | 1        | 3.13%   |
| MSI MS-7C91               | 1        | 3.13%   |
| Lenovo ThinkCentre        | 1        | 3.13%   |
| Lenovo 63                 | 1        | 3.13%   |
| Intel X79                 | 1        | 3.13%   |
| Intel H55                 | 1        | 3.13%   |
| Intel DH61WW              | 1        | 3.13%   |
| Gigabyte Z87-HD3          | 1        | 3.13%   |
| Gigabyte X399             | 1        | 3.13%   |
| Gigabyte B560M            | 1        | 3.13%   |
| Gigabyte B550M            | 1        | 3.13%   |
| eMachines EL1321          | 1        | 3.13%   |
| ECS H67H2-M2              | 1        | 3.13%   |
| Daten Tecnologia DH110MXV | 1        | 3.13%   |
| Biostar G31M+             | 1        | 3.13%   |
| BESSTAR Tech HM90         | 1        | 3.13%   |
| ASUS Z170                 | 1        | 3.13%   |
| ASUS PRIME                | 1        | 3.13%   |
| ASUS H110M-C              | 1        | 3.13%   |
| ASUS All                  | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 5        | 15.63%  |
| 2017 | 5        | 15.63%  |
| 2014 | 4        | 12.5%   |
| 2021 | 3        | 9.38%   |
| 2018 | 2        | 6.25%   |
| 2013 | 2        | 6.25%   |
| 2012 | 2        | 6.25%   |
| 2011 | 2        | 6.25%   |
| 2009 | 2        | 6.25%   |
| 2006 | 2        | 6.25%   |
| 2016 | 1        | 3.13%   |
| 2015 | 1        | 3.13%   |
| 2010 | 1        | 3.13%   |

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
| Disabled | 31       | 96.88%  |
| Enabled  | 1        | 3.13%   |

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
| 32.01-64.0 | 8        | 25%     |
| 8.01-16.0  | 7        | 21.88%  |
| 3.01-4.0   | 5        | 15.63%  |
| 16.01-24.0 | 5        | 15.63%  |
| 4.01-8.0   | 4        | 12.5%   |
| 2.01-3.0   | 3        | 9.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 16       | 45.71%  |
| 1.01-2.0  | 9        | 25.71%  |
| 4.01-8.0  | 3        | 8.57%   |
| 3.01-4.0  | 3        | 8.57%   |
| 0.51-1.0  | 2        | 5.71%   |
| 8.01-16.0 | 1        | 2.86%   |
| 0.01-0.5  | 1        | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 9        | 27.27%  |
| 2      | 9        | 27.27%  |
| 1      | 9        | 27.27%  |
| 4      | 3        | 9.09%   |
| 6      | 2        | 6.06%   |
| 0      | 1        | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 65.63%  |
| Yes       | 11       | 34.38%  |

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
| No        | 20       | 62.5%   |
| Yes       | 12       | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Brazil    | 20       | 62.5%   |
| USA       | 2        | 6.25%   |
| UK        | 2        | 6.25%   |
| Portugal  | 2        | 6.25%   |
| Spain     | 1        | 3.13%   |
| Mexico    | 1        | 3.13%   |
| Japan     | 1        | 3.13%   |
| Greece    | 1        | 3.13%   |
| Austria   | 1        | 3.13%   |
| Argentina | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sao Paulo              | 3        | 9.38%   |
| Rio de Janeiro         | 2        | 6.25%   |
| Wiener Neustadt        | 1        | 3.13%   |
| Vila Nova de Famalicao | 1        | 3.13%   |
| Tokyo                  | 1        | 3.13%   |
| Tlajomulco de Zuniga   | 1        | 3.13%   |
| Thessaloniki           | 1        | 3.13%   |
| The Villages           | 1        | 3.13%   |
| Sao Joaquim da Barra   | 1        | 3.13%   |
| Sao Domingos do Capim  | 1        | 3.13%   |
| Santo André           | 1        | 3.13%   |
| Santa Cruz de Tenerife | 1        | 3.13%   |
| Ribeirao Grande        | 1        | 3.13%   |
| Queimados              | 1        | 3.13%   |
| Osasco                 | 1        | 3.13%   |
| Maringá               | 1        | 3.13%   |
| Macapa                 | 1        | 3.13%   |
| Juazeiro do Norte      | 1        | 3.13%   |
| Ivinhema               | 1        | 3.13%   |
| Guimaraes              | 1        | 3.13%   |
| Fresno                 | 1        | 3.13%   |
| Franca                 | 1        | 3.13%   |
| Fortaleza              | 1        | 3.13%   |
| El Palomar             | 1        | 3.13%   |
| Dumbarton              | 1        | 3.13%   |
| Caratinga              | 1        | 3.13%   |
| Brasília              | 1        | 3.13%   |
| Bournemouth            | 1        | 3.13%   |
| Belo Horizonte         | 1        | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 12       | 16     | 19.05%  |
| Seagate                     | 12       | 22     | 19.05%  |
| China                       | 5        | 7      | 7.94%   |
| SanDisk                     | 4        | 4      | 6.35%   |
| Kingston                    | 4        | 7      | 6.35%   |
| Hitachi                     | 4        | 4      | 6.35%   |
| Samsung Electronics         | 3        | 4      | 4.76%   |
| XrayDisk                    | 2        | 2      | 3.17%   |
| Toshiba                     | 2        | 2      | 3.17%   |
| PNY                         | 2        | 2      | 3.17%   |
| KingSpec                    | 2        | 2      | 3.17%   |
| WALRAM                      | 1        | 1      | 1.59%   |
| Netac                       | 1        | 1      | 1.59%   |
| Micron/Crucial Technology   | 1        | 1      | 1.59%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 1.59%   |
| Kingston Technology Company | 1        | 1      | 1.59%   |
| JMicron Technology          | 1        | 1      | 1.59%   |
| Intel                       | 1        | 1      | 1.59%   |
| BHT                         | 1        | 1      | 1.59%   |
| Apacer                      | 1        | 1      | 1.59%   |
| ADATA Technology            | 1        | 1      | 1.59%   |
| Unknown                     | 1        | 1      | 1.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 2        | 2.82%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2        | 2.82%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2        | 2.82%   |
| Kingston SV300S37A240G 240GB SSD                    | 2        | 2.82%   |
| XrayDisk 512GB SSD                                  | 1        | 1.41%   |
| XrayDisk 120GB                                      | 1        | 1.41%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1        | 1.41%   |
| WDC WD800BD-22MRA1 80GB                             | 1        | 1.41%   |
| WDC WD800AAJS-75M0A0 80GB                           | 1        | 1.41%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 1.41%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1        | 1.41%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1        | 1.41%   |
| WDC WD3200AAKS-75L9A0 320GB                         | 1        | 1.41%   |
| WDC WD3200AAJS-56M0A0 320GB                         | 1        | 1.41%   |
| WDC WD30EFAX-68JH4N0 3TB                            | 1        | 1.41%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1        | 1.41%   |
| WDC WD10SPZX-80Z10T2 1TB                            | 1        | 1.41%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1        | 1.41%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1        | 1.41%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1        | 1.41%   |
| WDC WD1001FALS-41Y6A1 1TB                           | 1        | 1.41%   |
| WALRAM 240G                                         | 1        | 1.41%   |
| Toshiba MQ01ABD050V -63 500GB                       | 1        | 1.41%   |
| Toshiba DT01ACA050 500GB                            | 1        | 1.41%   |
| Seagate ST9500325AS 500GB                           | 1        | 1.41%   |
| Seagate ST9100824AS 100GB                           | 1        | 1.41%   |
| Seagate ST8000VN0022-2EL112 8TB                     | 1        | 1.41%   |
| Seagate ST8000AS0002-1NA17Z 8TB                     | 1        | 1.41%   |
| Seagate ST380811AS 80GB                             | 1        | 1.41%   |
| Seagate ST3320613AS 320GB                           | 1        | 1.41%   |
| Seagate ST32000542AS 2TB                            | 1        | 1.41%   |
| Seagate ST3160212SCE 160GB                          | 1        | 1.41%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1        | 1.41%   |
| Seagate Expansion 1TB                               | 1        | 1.41%   |
| Sandisk WD Blue SN570 1TB                           | 1        | 1.41%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1TB | 1        | 1.41%   |
| SanDisk SSD PLUS 480GB                              | 1        | 1.41%   |
| SanDisk SDSSDXPS480G 480GB                          | 1        | 1.41%   |
| Samsung SSD 870 QVO 2TB                             | 1        | 1.41%   |
| Samsung SSD 850 EVO M.2 500GB                       | 1        | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 12       | 22     | 41.38%  |
| WDC     | 11       | 15     | 37.93%  |
| Hitachi | 4        | 4      | 13.79%  |
| Toshiba | 2        | 2      | 6.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| China               | 5        | 7      | 21.74%  |
| Kingston            | 4        | 6      | 17.39%  |
| Samsung Electronics | 3        | 4      | 13.04%  |
| SanDisk             | 2        | 2      | 8.7%    |
| PNY                 | 2        | 2      | 8.7%    |
| KingSpec            | 2        | 2      | 8.7%    |
| XrayDisk            | 1        | 1      | 4.35%   |
| WDC                 | 1        | 1      | 4.35%   |
| BHT                 | 1        | 1      | 4.35%   |
| Apacer              | 1        | 1      | 4.35%   |
| Unknown             | 1        | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 22       | 43     | 41.51%  |
| SSD     | 20       | 28     | 37.74%  |
| NVMe    | 8        | 9      | 15.09%  |
| Unknown | 3        | 3      | 5.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 71     | 73.17%  |
| NVMe | 8        | 9      | 19.51%  |
| SAS  | 3        | 3      | 7.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 25       | 42     | 59.52%  |
| 0.51-1.0   | 11       | 17     | 26.19%  |
| 3.01-4.0   | 2        | 6      | 4.76%   |
| 1.01-2.0   | 2        | 3      | 4.76%   |
| 2.01-3.0   | 1        | 1      | 2.38%   |
| 4.01-10.0  | 1        | 2      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 9        | 28.13%  |
| 251-500        | 5        | 15.63%  |
| 101-250        | 5        | 15.63%  |
| More than 3000 | 4        | 12.5%   |
| 2001-3000      | 4        | 12.5%   |
| 501-1000       | 4        | 12.5%   |
| 1-20           | 1        | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 14       | 41.18%  |
| 251-500   | 5        | 14.71%  |
| 501-1000  | 5        | 14.71%  |
| 101-250   | 3        | 8.82%   |
| 1-20      | 3        | 8.82%   |
| 51-100    | 3        | 8.82%   |
| 2001-3000 | 1        | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB       | 1        | 1      | 12.5%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1        | 1      | 12.5%   |
| WDC WD1001FALS-41Y6A1 1TB       | 1        | 2      | 12.5%   |
| Seagate ST9100824AS 100GB       | 1        | 1      | 12.5%   |
| Seagate ST8000AS0002-1NA17Z 8TB | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 2      | 12.5%   |
| Seagate ST3320613AS 320GB       | 1        | 1      | 12.5%   |
| Hitachi HDS721050DLE630 500GB   | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 50%     |
| WDC     | 3        | 4      | 37.5%   |
| Hitachi | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 50%     |
| WDC     | 3        | 4      | 37.5%   |
| Hitachi | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 10     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 18       | 36     | 43.9%   |
| Works    | 15       | 36     | 36.59%  |
| Malfunc  | 7        | 10     | 17.07%  |
| Failed   | 1        | 1      | 2.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 23       | 56.1%   |
| AMD                         | 6        | 14.63%  |
| VIA Technologies            | 2        | 4.88%   |
| SanDisk                     | 2        | 4.88%   |
| Kingston Technology Company | 2        | 4.88%   |
| Phison Electronics          | 1        | 2.44%   |
| Nvidia                      | 1        | 2.44%   |
| Netac Technology            | 1        | 2.44%   |
| Micron/Crucial Technology   | 1        | 2.44%   |
| MAXIO Technology (Hangzhou) | 1        | 2.44%   |
| ADATA Technology            | 1        | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 10.2%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 10.2%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 6.12%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 6.12%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 6.12%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 4.08%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 2        | 4.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 4.08%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1        | 2.04%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 2.04%   |
| Phison E12 NVMe Controller                                                              | 1        | 2.04%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 2.04%   |
| Netac Non-Volatile memory controller                                                    | 1        | 2.04%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                                | 1        | 2.04%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 2.04%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 2.04%   |
| Kingston Company NVMe Controller                                                        | 1        | 2.04%   |
| Intel SSD 660P Series                                                                   | 1        | 2.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 2.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1        | 2.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.04%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 61.9%   |
| NVMe | 8        | 19.05%  |
| IDE  | 6        | 14.29%  |
| RAID | 2        | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 25       | 78.13%  |
| AMD    | 7        | 21.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Pentium D CPU 3.00GHz                    | 2        | 6.25%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 6.25%   |
| AMD Ryzen 5 5600 6-Core Processor              | 2        | 6.25%   |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz            | 1        | 3.13%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz    | 1        | 3.13%   |
| Intel Pentium CPU G4400 @ 3.30GHz              | 1        | 3.13%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 3.13%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 3.13%   |
| Intel Core i7 CPU S 860 @ 2.53GHz              | 1        | 3.13%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 3.13%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 1        | 3.13%   |
| Intel Core i5-4570T CPU @ 2.90GHz              | 1        | 3.13%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 3.13%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 3.13%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 1        | 3.13%   |
| Intel Core i5-2300 CPU @ 2.80GHz               | 1        | 3.13%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 3.13%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 3.13%   |
| Intel Core i3-3250 CPU @ 3.50GHz               | 1        | 3.13%   |
| Intel Core i3-10100F CPU @ 3.60GHz             | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 3.13%   |
| Intel Celeron CPU J1800 @ 2.41GHz              | 1        | 3.13%   |
| Intel Celeron CPU G530 @ 2.40GHz               | 1        | 3.13%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 1        | 3.13%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 3.13%   |
| AMD Ryzen 9 4900H with Radeon Graphics         | 1        | 3.13%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 3.13%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 3.13%   |
| AMD Athlon Processor LE-1660                   | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 9        | 28.13%  |
| Intel Core i3           | 4        | 12.5%   |
| Intel Core i7           | 3        | 9.38%   |
| AMD Ryzen 5             | 3        | 9.38%   |
| Intel Pentium D         | 2        | 6.25%   |
| Intel Celeron           | 2        | 6.25%   |
| Other                   | 1        | 3.13%   |
| Intel Xeon              | 1        | 3.13%   |
| Intel Pentium Dual-Core | 1        | 3.13%   |
| Intel Pentium           | 1        | 3.13%   |
| Intel Core 2 Quad       | 1        | 3.13%   |
| AMD Ryzen Threadripper  | 1        | 3.13%   |
| AMD Ryzen 9             | 1        | 3.13%   |
| AMD Ryzen 7             | 1        | 3.13%   |
| AMD Athlon              | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 12       | 37.5%   |
| 2      | 10       | 31.25%  |
| 6      | 6        | 18.75%  |
| 8      | 2        | 6.25%   |
| 12     | 1        | 3.13%   |
| 1      | 1        | 3.13%   |

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
| 2      | 16       | 50%     |
| 1      | 16       | 50%     |

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
| 0x206a7    | 5        | 15.63%  |
| Unknown    | 5        | 15.63%  |
| 0x306c3    | 4        | 12.5%   |
| 0xf64      | 2        | 6.25%   |
| 0x506e3    | 2        | 6.25%   |
| 0x306a9    | 2        | 6.25%   |
| 0xa0671    | 1        | 3.13%   |
| 0x906ed    | 1        | 3.13%   |
| 0x6fb      | 1        | 3.13%   |
| 0x306e4    | 1        | 3.13%   |
| 0x30678    | 1        | 3.13%   |
| 0x1067a    | 1        | 3.13%   |
| 0x0a20120a | 1        | 3.13%   |
| 0x0a201025 | 1        | 3.13%   |
| 0x08701021 | 1        | 3.13%   |
| 0x08600106 | 1        | 3.13%   |
| 0x0800820d | 1        | 3.13%   |
| 0x08001137 | 1        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 5        | 15.63%  |
| Haswell     | 5        | 15.63%  |
| Skylake     | 3        | 9.38%   |
| IvyBridge   | 3        | 9.38%   |
| Zen 3       | 2        | 6.25%   |
| Zen 2       | 2        | 6.25%   |
| NetBurst    | 2        | 6.25%   |
| Zen+        | 1        | 3.13%   |
| Zen         | 1        | 3.13%   |
| Silvermont  | 1        | 3.13%   |
| Penryn      | 1        | 3.13%   |
| Nehalem     | 1        | 3.13%   |
| KabyLake    | 1        | 3.13%   |
| K8 Hammer   | 1        | 3.13%   |
| Icelake     | 1        | 3.13%   |
| Core        | 1        | 3.13%   |
| CometLake   | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 14       | 41.18%  |
| Intel  | 12       | 35.29%  |
| AMD    | 8        | 23.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 8.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 5.88%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2        | 5.88%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 2.94%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.94%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 2.94%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 2.94%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 2.94%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 2.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.94%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 2.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 2.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.94%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 2.94%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 2.94%   |
| Intel HD Graphics 530                                                       | 1        | 2.94%   |
| Intel HD Graphics 510                                                       | 1        | 2.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 2.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.94%   |
| AMD Renoir                                                                  | 1        | 2.94%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 2.94%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.94%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 1        | 2.94%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 1        | 2.94%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 12       | 37.5%   |
| 1 x Intel      | 10       | 31.25%  |
| 1 x AMD        | 8        | 25%     |
| Intel + Nvidia | 2        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 59.38%  |
| Proprietary | 11       | 34.38%  |
| Unknown     | 2        | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 40.63%  |
| 1.01-2.0   | 8        | 25%     |
| 3.01-4.0   | 3        | 9.38%   |
| 0.01-0.5   | 3        | 9.38%   |
| 5.01-6.0   | 2        | 6.25%   |
| 7.01-8.0   | 1        | 3.13%   |
| 8.01-16.0  | 1        | 3.13%   |
| 0.51-1.0   | 1        | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 10       | 31.25%  |
| Goldstar            | 5        | 15.63%  |
| AOC                 | 3        | 9.38%   |
| Unknown (XXX)       | 2        | 6.25%   |
| Positivo            | 2        | 6.25%   |
| Philips             | 2        | 6.25%   |
| Philco              | 1        | 3.13%   |
| NEC Computers       | 1        | 3.13%   |
| LG Electronics      | 1        | 3.13%   |
| ITE                 | 1        | 3.13%   |
| Hewlett-Packard     | 1        | 3.13%   |
| Dell                | 1        | 3.13%   |
| BenQ                | 1        | 3.13%   |
| ASUSTek Computer    | 1        | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch | 2        | 5.56%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 2.78%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch       | 1        | 2.78%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch | 1        | 2.78%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch  | 1        | 2.78%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 1        | 2.78%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch    | 1        | 2.78%   |
| Samsung Electronics S19B300 SAM08A5 1366x768 410x230mm 18.5-inch     | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SAM0C3C 1360x768 700x390mm 31.5-inch | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SAM02C9 1360x768 885x498mm 40.0-inch | 1        | 2.78%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                    | 1        | 2.78%   |
| Positivo UNION NON1500 1360x768 344x194mm 15.5-inch                  | 1        | 2.78%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                 | 1        | 2.78%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch              | 1        | 2.78%   |
| Philips 237E4 PHLC0AD 1920x1080 509x286mm 23.0-inch                  | 1        | 2.78%   |
| Philco TV PLC0003 1440x900 708x398mm 32.0-inch                       | 1        | 2.78%   |
| NEC Computers LCD1770VX NEC6697 1280x960 338x270mm 17.0-inch         | 1        | 2.78%   |
| LG Electronics LCD Monitor LG FULL HD 3200x1080                      | 1        | 2.78%   |
| LG Electronics LCD Monitor LG FULL HD                                | 1        | 2.78%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                | 1        | 2.78%   |
| Hewlett-Packard 25mx HPN359B 1920x1080 544x303mm 24.5-inch           | 1        | 2.78%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1        | 2.78%   |
| Goldstar ULTRAWIDE GSM5C0C 2560x1080 601x254mm 25.7-inch             | 1        | 2.78%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                | 1        | 2.78%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1        | 2.78%   |
| Goldstar HD 16 GSM3E92 1366x768 344x194mm 15.5-inch                  | 1        | 2.78%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 1        | 2.78%   |
| Dell LCD Monitor E170S 3200x1080                                     | 1        | 2.78%   |
| Dell LCD Monitor E170S                                               | 1        | 2.78%   |
| BenQ LCD Monitor EL2870U 3840x2160                                   | 1        | 2.78%   |
| ASUSTek Computer VP249 AUS24AA 1920x1080 527x296mm 23.8-inch         | 1        | 2.78%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 1        | 2.78%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                       | 1        | 2.78%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 1        | 2.78%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 27.27%  |
| 1366x768 (WXGA)    | 5        | 15.15%  |
| 1360x768           | 4        | 12.12%  |
| 3840x2160 (4K)     | 3        | 9.09%   |
| 2560x1080          | 2        | 6.06%   |
| 1680x1050 (WSXGA+) | 2        | 6.06%   |
| 3200x1080          | 1        | 3.03%   |
| 1920x540           | 1        | 3.03%   |
| 1920x1200 (WUXGA)  | 1        | 3.03%   |
| 1600x900 (HD+)     | 1        | 3.03%   |
| 1440x900 (WXGA+)   | 1        | 3.03%   |
| 1280x960           | 1        | 3.03%   |
| 1280x1024 (SXGA)   | 1        | 3.03%   |
| Unknown            | 1        | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 5        | 15.15%  |
| 27      | 3        | 9.09%   |
| 24      | 3        | 9.09%   |
| 23      | 3        | 9.09%   |
| 20      | 3        | 9.09%   |
| 17      | 3        | 9.09%   |
| Unknown | 3        | 9.09%   |
| 54      | 2        | 6.06%   |
| 15      | 2        | 6.06%   |
| 40      | 1        | 3.03%   |
| 34      | 1        | 3.03%   |
| 32      | 1        | 3.03%   |
| 31      | 1        | 3.03%   |
| 25      | 1        | 3.03%   |
| 21      | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 9        | 28.13%  |
| 501-600     | 8        | 25%     |
| 301-350     | 4        | 12.5%   |
| Unknown     | 3        | 9.38%   |
| 701-800     | 2        | 6.25%   |
| 601-700     | 2        | 6.25%   |
| 1001-1500   | 2        | 6.25%   |
| 801-900     | 1        | 3.13%   |
| 351-400     | 1        | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 63.33%  |
| 16/10   | 4        | 13.33%  |
| Unknown | 3        | 10%     |
| 5/4     | 2        | 6.67%   |
| 21/9    | 2        | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 7        | 21.88%  |
| 201-250        | 5        | 15.63%  |
| 351-500        | 3        | 9.38%   |
| 301-350        | 3        | 9.38%   |
| 151-200        | 3        | 9.38%   |
| Unknown        | 3        | 9.38%   |
| More than 1000 | 2        | 6.25%   |
| 251-300        | 2        | 6.25%   |
| 101-110        | 2        | 6.25%   |
| 131-140        | 1        | 3.13%   |
| 501-1000       | 1        | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 19       | 65.52%  |
| 101-120 | 4        | 13.79%  |
| 1-50    | 3        | 10.34%  |
| Unknown | 3        | 10.34%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 65.63%  |
| 2     | 8        | 25%     |
| 0     | 3        | 9.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 24       | 54.55%  |
| Intel                 | 10       | 22.73%  |
| VIA Technologies      | 2        | 4.55%   |
| Qualcomm Atheros      | 2        | 4.55%   |
| D-Link System         | 2        | 4.55%   |
| Samsung Electronics   | 1        | 2.27%   |
| Ralink Technology     | 1        | 2.27%   |
| MediaTek              | 1        | 2.27%   |
| D-Link                | 1        | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 16       | 29.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 5        | 9.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 3        | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 3        | 5.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 2        | 3.7%    |
| Realtek 802.11ac NIC                                                                  | 2        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2        | 3.7%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                       | 2        | 3.7%    |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1        | 1.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1        | 1.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1        | 1.85%   |
| Ralink RT5370 Wireless Adapter                                                        | 1        | 1.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1        | 1.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 1.85%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 1.85%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 1.85%   |
| Intel I211 Gigabit Network Connection                                                 | 1        | 1.85%   |
| Intel Ethernet Controller I225-V                                                      | 1        | 1.85%   |
| Intel Ethernet Connection I217-LM                                                     | 1        | 1.85%   |
| Intel Ethernet Connection (7) I219-V                                                  | 1        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                                                  | 1        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 1.85%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 1.85%   |
| Intel 82579V Gigabit Network Connection                                               | 1        | 1.85%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                  | 1        | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 46.67%  |
| Intel                 | 4        | 26.67%  |
| Ralink Technology     | 1        | 6.67%   |
| Qualcomm Atheros      | 1        | 6.67%   |
| MediaTek              | 1        | 6.67%   |
| D-Link                | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 3        | 20%     |
| Realtek 802.11ac NIC                                                                  | 2        | 13.33%  |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1        | 6.67%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 6.67%   |
| Ralink RT5370 Wireless Adapter                                                        | 1        | 6.67%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 6.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 6.67%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 6.67%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 6.67%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 6.67%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                  | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 61.11%  |
| Intel                 | 8        | 22.22%  |
| VIA Technologies      | 2        | 5.56%   |
| D-Link System         | 2        | 5.56%   |
| Samsung Electronics   | 1        | 2.78%   |
| Qualcomm Atheros      | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 41.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 12.82%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 7.69%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 5.13%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 5.13%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 2.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.56%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.56%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.56%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.56%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 68.09%  |
| WiFi     | 15       | 31.91%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 81.25%  |
| WiFi     | 6        | 18.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 59.38%  |
| 2     | 11       | 34.38%  |
| 3     | 2        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 59.38%  |
| Yes  | 13       | 40.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 5        | 41.67%  |
| Intel                   | 3        | 25%     |
| Realtek Semiconductor   | 2        | 16.67%  |
| MediaTek                | 1        | 8.33%   |
| Actions                 | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 41.67%  |
| Realtek Bluetooth Radio                             | 2        | 16.67%  |
| MediaTek Wireless_Device                            | 1        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 8.33%   |
| Intel Bluetooth wireless interface                  | 1        | 8.33%   |
| Intel AX200 Bluetooth                               | 1        | 8.33%   |
| Actions general adapter                             | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 23       | 41.07%  |
| Nvidia                 | 13       | 23.21%  |
| AMD                    | 12       | 21.43%  |
| C-Media Electronics    | 3        | 5.36%   |
| Creative Labs          | 2        | 3.57%   |
| Razer USA              | 1        | 1.79%   |
| Generalplus Technology | 1        | 1.79%   |
| DCMT Technology        | 1        | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6        | 10%     |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 8.33%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 5%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 5%      |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 5%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 5%      |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 3.33%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 3.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 3.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 3.33%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 2        | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 3.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 3.33%   |
| Razer USA Razer Leviathan V2                                                      | 1        | 1.67%   |
| Nvidia TU102 High Definition Audio Controller                                     | 1        | 1.67%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 1.67%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.67%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 1.67%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1        | 1.67%   |
| Generalplus Technology USB Audio Device                                           | 1        | 1.67%   |
| DCMT Technology USB Condenser Microphone                                          | 1        | 1.67%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 1        | 1.67%   |
| C-Media Electronics CM108 Audio Controller                                        | 1        | 1.67%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1        | 1.67%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 1        | 1.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 1.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 1        | 1.67%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 29.03%  |
| Unknown             | 6        | 19.35%  |
| Corsair             | 4        | 12.9%   |
| Smart               | 2        | 6.45%   |
| SK hynix            | 2        | 6.45%   |
| Samsung Electronics | 2        | 6.45%   |
| Ramaxel Technology  | 1        | 3.23%   |
| PLEXHD              | 1        | 3.23%   |
| Nanya Technology    | 1        | 3.23%   |
| Micron Technology   | 1        | 3.23%   |
| Crucial             | 1        | 3.23%   |
| Unknown             | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                         | 2        | 6.25%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s       | 2        | 6.25%   |
| Unknown RAM Module 8GB DIMM SDRAM                         | 1        | 3.13%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 3.13%   |
| Unknown RAM Module 2GB DIMM DDR2 266MT/s                  | 1        | 3.13%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                | 1        | 3.13%   |
| SK hynix RAM MD4512NSE-CB3M2 00 4096MB DIMM DDR4 2400MT/s | 1        | 3.13%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s      | 1        | 3.13%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 1        | 3.13%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s       | 1        | 3.13%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s   | 1        | 3.13%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s   | 1        | 3.13%   |
| PLEXHD RAM er 4GB DIMM DDR3 1600MT/s                      | 1        | 3.13%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 3.13%   |
| Micron RAM 36JSZF51272PZ 4GB DIMM DDR3 1600MT/s           | 1        | 3.13%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 3.13%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 1        | 3.13%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s       | 1        | 3.13%   |
| Kingston RAM HX426C16FB/16 16GB DIMM DDR4 2667MT/s        | 1        | 3.13%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s   | 1        | 3.13%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 3.13%   |
| Kingston RAM 9905471-074.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 3.13%   |
| Kingston RAM 9905471-001.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 3.13%   |
| Kingston RAM 9905316-004.A03LF0 1GB DIMM DDR2 266MT/s     | 1        | 3.13%   |
| Crucial RAM CT16G4DFRA32A.M16FE 16GB DIMM DDR4 3200MT/s   | 1        | 3.13%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s     | 1        | 3.13%   |
| Corsair RAM CML8GX3M1A1600C9 8192MB DIMM DDR3 1600MT/s    | 1        | 3.13%   |
| Corsair RAM CMK32GX4M2C3000C16 16GB DIMM DDR4 2133MT/s    | 1        | 3.13%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s     | 1        | 3.13%   |
| Unknown                                                   | 1        | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 11       | 44%     |
| DDR4  | 9        | 36%     |
| SDRAM | 4        | 16%     |
| DDR2  | 1        | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 23       | 92%     |
| SODIMM | 2        | 8%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 32.14%  |
| 4096  | 8        | 28.57%  |
| 16384 | 5        | 17.86%  |
| 2048  | 5        | 17.86%  |
| 1024  | 1        | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 8        | 28.57%  |
| 3200    | 4        | 14.29%  |
| 1333    | 4        | 14.29%  |
| Unknown | 3        | 10.71%  |
| 2400    | 2        | 7.14%   |
| 2133    | 2        | 7.14%   |
| 3733    | 1        | 3.57%   |
| 2667    | 1        | 3.57%   |
| 2200    | 1        | 3.57%   |
| 1867    | 1        | 3.57%   |
| 266     | 1        | 3.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Seiko Epson L380 Series | 1        | 100%    |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 1        | 16.67%  |
| Microsoft                     | 1        | 16.67%  |
| Lenovo                        | 1        | 16.67%  |
| Jieli Technology              | 1        | 16.67%  |
| Generalplus Technology        | 1        | 16.67%  |
| GEMBIRD                       | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Sunplus Integrated_Webcam_HD | 1        | 16.67%  |
| Microsoft LifeCam VX-2000    | 1        | 16.67%  |
| Lenovo FHD Webcam            | 1        | 16.67%  |
| Jieli USB PHY 2.0            | 1        | 16.67%  |
| Generalplus 808 Camera       | 1        | 16.67%  |
| GEMBIRD USB2.0 PC CAMERA     | 1        | 16.67%  |

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
| 0     | 25       | 78.13%  |
| 1     | 7        | 21.88%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 4        | 57.14%  |
| Graphics card | 2        | 28.57%  |
| Network       | 1        | 14.29%  |

