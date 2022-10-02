Rocky Linux - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Rocky_Linux/Desktop/README.md) and [notebooks](/Dist/Rocky_Linux/Notebook/README.md).

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

Total: 82

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| AZW           | GTR V01                     | Mini pc     | [40c181376b](https://linux-hardware.org/?probe=40c181376b) | Oct 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [4638cc7f7b](https://linux-hardware.org/?probe=4638cc7f7b) | Oct 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| BANGHO        | BES G1529                   | Notebook    | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Dell          | Latitude 5430               | Notebook    | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [af658eb920](https://linux-hardware.org/?probe=af658eb920) | Sep 06, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [79c81eef28](https://linux-hardware.org/?probe=79c81eef28) | Aug 23, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [713884d2c8](https://linux-hardware.org/?probe=713884d2c8) | Aug 03, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [ce5ca74472](https://linux-hardware.org/?probe=ce5ca74472) | Jul 17, 2022 |
| Unknown       | Unknown                     | Tablet      | [bf70ad93f5](https://linux-hardware.org/?probe=bf70ad93f5) | Jul 06, 2022 |
| Unknown       | Unknown                     | Tablet      | [6edba7f033](https://linux-hardware.org/?probe=6edba7f033) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34483... | Notebook    | [fa20ff88e1](https://linux-hardware.org/?probe=fa20ff88e1) | Jun 19, 2022 |
| Dell          | Latitude 3420               | Notebook    | [b10330b427](https://linux-hardware.org/?probe=b10330b427) | Jun 15, 2022 |
| Unknown       | X31_ICH7                    | Desktop     | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | 0GWHMW A01                  | Desktop     | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | 072T6D A01                  | Server      | [4b88759a98](https://linux-hardware.org/?probe=4b88759a98) | May 06, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR           | Pocono BIOS.5.1             | Desktop     | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| IBM           | 4367 SVT                    | Server      | [3d7400ea9b](https://linux-hardware.org/?probe=3d7400ea9b) | Mar 11, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Supermicro    | X11SSH-CTF                  | Server      | [7a720a4e41](https://linux-hardware.org/?probe=7a720a4e41) | Mar 10, 2022 |
| Dell          | Latitude 5500               | Notebook    | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell          | Latitude 5500               | Notebook    | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| Supermicro    | X11SPW-TF                   | Server      | [a76bb2e30d](https://linux-hardware.org/?probe=a76bb2e30d) | Feb 07, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [02e5c56a80](https://linux-hardware.org/?probe=02e5c56a80) | Feb 03, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [4aa06b4edd](https://linux-hardware.org/?probe=4aa06b4edd) | Feb 03, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI           | Z97A GAMING 6               | Desktop     | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| Dell          | 0X3D66 A07                  | Server      | [d5c4ef93c4](https://linux-hardware.org/?probe=d5c4ef93c4) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [c7f9478d55](https://linux-hardware.org/?probe=c7f9478d55) | Jan 03, 2022 |
| AZW           | Gemini M                    | Desktop     | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW           | Gemini M                    | Desktop     | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google        | Panther                     | Desktop     | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo        | ThinkPad W540 20BGCTO1WW    | Notebook    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d7947a5a8](https://linux-hardware.org/?probe=9d7947a5a8) | Nov 06, 2021 |
| Toshiba       | TECRA W50-A                 | Notebook    | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Dell          | 0N4YC8 A00                  | Desktop     | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| Intel         | S2600WFT H48104-850         | Server      | [36c4acac2d](https://linux-hardware.org/?probe=36c4acac2d) | Sep 14, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | Notebook    | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo        | NOK                         | Desktop     | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | Notebook    | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406132G       | Notebook    | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| HP            | 0B54h D                     | Desktop     | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |
| Acer          | Aspire VN7-591G             | Notebook    | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Rocky Linux 8.5 | 31        | 45.59%  |
| Rocky Linux 8.4 | 19        | 27.94%  |
| Rocky Linux 9.0 | 10        | 14.71%  |
| Rocky Linux 8.6 | 6         | 8.82%   |
| Rocky Linux 8.3 | 2         | 2.94%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 67        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 19.12%  |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 11.76%  |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 8.82%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 7.35%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 5.88%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 3         | 4.41%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 4.41%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 2.94%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 2.94%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 2.94%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 2.94%   |
| 4.18.0-305.el8.x86_64            | 2         | 2.94%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 2.94%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 2.94%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 2.94%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 2.94%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.47%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1         | 1.47%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 1         | 1.47%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.47%   |
| 5.10.89-1.el8.x86_64             | 1         | 1.47%   |
| 5.10.52-v8.1.el8                 | 1         | 1.47%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.47%   |
| 4.18.0-348.23.1.el8_5.x86_64     | 1         | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 53        | 79.1%   |
| 5.14.0  | 10        | 14.93%  |
| 5.4.157 | 1         | 1.49%   |
| 5.14.1  | 1         | 1.49%   |
| 5.10.89 | 1         | 1.49%   |
| 5.10.52 | 1         | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 53        | 79.1%   |
| 5.14    | 11        | 16.42%  |
| 5.10    | 2         | 2.99%   |
| 5.4     | 1         | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 66        | 98.51%  |
| aarch64 | 1         | 1.49%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 47        | 70.15%  |
| Unknown       | 7         | 10.45%  |
| MATE          | 4         | 5.97%   |
| KDE5          | 4         | 5.97%   |
| GNOME Classic | 3         | 4.48%   |
| XFCE          | 1         | 1.49%   |
| X-Cinnamon    | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 36        | 53.73%  |
| X11     | 26        | 38.81%  |
| Unknown | 5         | 7.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 47.76%  |
| GDM     | 30        | 44.78%  |
| SDDM    | 3         | 4.48%   |
| LightDM | 2         | 2.99%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 42        | 62.69%  |
| ru_RU   | 3         | 4.48%   |
| en_IL   | 3         | 4.48%   |
| en_AU   | 3         | 4.48%   |
| en_ZA   | 2         | 2.99%   |
| en_SG   | 2         | 2.99%   |
| en_CA   | 2         | 2.99%   |
| de_DE   | 2         | 2.99%   |
| pt_BR   | 1         | 1.49%   |
| pl_PL   | 1         | 1.49%   |
| ja_JP   | 1         | 1.49%   |
| it_IT   | 1         | 1.49%   |
| hu_HU   | 1         | 1.49%   |
| es_CO   | 1         | 1.49%   |
| af_ZA   | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 53.73%  |
| BIOS | 31        | 46.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 52        | 77.61%  |
| Ext4 | 14        | 20.9%   |
| Ext3 | 1         | 1.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 40.3%   |
| GPT     | 25        | 37.31%  |
| MBR     | 15        | 22.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 83.58%  |
| Yes       | 11        | 16.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 86.57%  |
| Yes       | 9         | 13.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 15        | 22.39%  |
| Dell                    | 15        | 22.39%  |
| ASUSTek Computer        | 10        | 14.93%  |
| Hewlett-Packard         | 6         | 8.96%   |
| Gigabyte Technology     | 4         | 5.97%   |
| Toshiba                 | 2         | 2.99%   |
| Supermicro              | 2         | 2.99%   |
| AZW                     | 2         | 2.99%   |
| Unknown                 | 2         | 2.99%   |
| Raspberry Pi Foundation | 1         | 1.49%   |
| NCR                     | 1         | 1.49%   |
| MSI                     | 1         | 1.49%   |
| Intel                   | 1         | 1.49%   |
| IBM                     | 1         | 1.49%   |
| Google                  | 1         | 1.49%   |
| BANGHO                  | 1         | 1.49%   |
| ASRock                  | 1         | 1.49%   |
| Acer                    | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Dell PowerEdge R610                    | 2         | 2.99%   |
| Dell OptiPlex 9020                     | 2         | 2.99%   |
| Unknown                                | 2         | 2.99%   |
| Toshiba TECRA W50-A                    | 1         | 1.49%   |
| Toshiba Satellite E45-B                | 1         | 1.49%   |
| Supermicro SYS-5029P-WTR               | 1         | 1.49%   |
| Supermicro Super Server                | 1         | 1.49%   |
| RPi Raspberry Pi                       | 1         | 1.49%   |
| NCR xxxx-xxxx-xxxx                     | 1         | 1.49%   |
| MSI MS-7917                            | 1         | 1.49%   |
| Lenovo ThinkStation P620 30E0S0PR00    | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 1.49%   |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 1.49%   |
| Lenovo ThinkPad W500 406132G           | 1         | 1.49%   |
| Lenovo ThinkPad T420 42365H1           | 1         | 1.49%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 1.49%   |
| Lenovo ThinkCentre M72e 36601Y8        | 1         | 1.49%   |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 1.49%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 1.49%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9       | 1         | 1.49%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 1.49%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 1.49%   |
| Lenovo IdeaPad Y410P 20216             | 1         | 1.49%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 1.49%   |
| Lenovo IdeaPad 500S-14ISK 80Q3         | 1         | 1.49%   |
| Intel S2600WFT                         | 1         | 1.49%   |
| IBM System x3200 M2 -[4368IGS]-        | 1         | 1.49%   |
| HP ZBook 15u G6                        | 1         | 1.49%   |
| HP ZBook 15 G3                         | 1         | 1.49%   |
| HP ZBook 15 G2                         | 1         | 1.49%   |
| HP Z600 Workstation                    | 1         | 1.49%   |
| HP Laptop 17-ca1xxx                    | 1         | 1.49%   |
| HP EliteBook 840 G7 Notebook PC        | 1         | 1.49%   |
| Google Panther                         | 1         | 1.49%   |
| Gigabyte X570 AORUS ULTRA              | 1         | 1.49%   |
| Gigabyte H87-D3H                       | 1         | 1.49%   |
| Gigabyte G41MT-USB3                    | 1         | 1.49%   |
| Gigabyte 970A-UD3P                     | 1         | 1.49%   |
| Dell XPS 15 7590                       | 1         | 1.49%   |
| Dell Vostro 3681                       | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUS PRIME               | 6         | 8.96%   |
| Lenovo ThinkPad          | 5         | 7.46%   |
| Lenovo IdeaPad           | 4         | 5.97%   |
| Dell PowerEdge           | 4         | 5.97%   |
| HP ZBook                 | 3         | 4.48%   |
| Dell Precision           | 3         | 4.48%   |
| Dell OptiPlex            | 3         | 4.48%   |
| Dell Latitude            | 3         | 4.48%   |
| Lenovo Legion            | 2         | 2.99%   |
| Lenovo IdeaPadFlex       | 2         | 2.99%   |
| ASUS ASUS                | 2         | 2.99%   |
| Unknown                  | 2         | 2.99%   |
| Toshiba TECRA            | 1         | 1.49%   |
| Toshiba Satellite        | 1         | 1.49%   |
| Supermicro SYS-5029P-WTR | 1         | 1.49%   |
| Supermicro Super         | 1         | 1.49%   |
| RPi Raspberry            | 1         | 1.49%   |
| NCR xxxx-xxxx-xxxx       | 1         | 1.49%   |
| MSI MS-7917              | 1         | 1.49%   |
| Lenovo ThinkStation      | 1         | 1.49%   |
| Lenovo ThinkCentre       | 1         | 1.49%   |
| Intel S2600WFT           | 1         | 1.49%   |
| IBM System               | 1         | 1.49%   |
| HP Z600                  | 1         | 1.49%   |
| HP Laptop                | 1         | 1.49%   |
| HP EliteBook             | 1         | 1.49%   |
| Google Panther           | 1         | 1.49%   |
| Gigabyte X570            | 1         | 1.49%   |
| Gigabyte H87-D3H         | 1         | 1.49%   |
| Gigabyte G41MT-USB3      | 1         | 1.49%   |
| Gigabyte 970A-UD3P       | 1         | 1.49%   |
| Dell XPS                 | 1         | 1.49%   |
| Dell Vostro              | 1         | 1.49%   |
| BANGHO BES               | 1         | 1.49%   |
| AZW GTR                  | 1         | 1.49%   |
| AZW Gemini               | 1         | 1.49%   |
| ASUS P8B                 | 1         | 1.49%   |
| ASUS P5Q                 | 1         | 1.49%   |
| ASRock B450M             | 1         | 1.49%   |
| Acer Aspire              | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 10        | 14.93%  |
| 2021    | 9         | 13.43%  |
| 2019    | 8         | 11.94%  |
| 2014    | 7         | 10.45%  |
| 2018    | 5         | 7.46%   |
| 2015    | 5         | 7.46%   |
| 2013    | 5         | 7.46%   |
| 2022    | 4         | 5.97%   |
| 2011    | 4         | 5.97%   |
| 2016    | 2         | 2.99%   |
| 2012    | 2         | 2.99%   |
| 2009    | 2         | 2.99%   |
| 2008    | 2         | 2.99%   |
| 2010    | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 28        | 41.79%  |
| Notebook       | 26        | 38.81%  |
| Server         | 8         | 11.94%  |
| Convertible    | 2         | 2.99%   |
| System on chip | 1         | 1.49%   |
| Tablet         | 1         | 1.49%   |
| Mini pc        | 1         | 1.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 64        | 95.52%  |
| Enabled  | 3         | 4.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 66        | 98.51%  |
| Yes  | 1         | 1.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 14        | 20.9%   |
| 32.01-64.0      | 14        | 20.9%   |
| 8.01-16.0       | 13        | 19.4%   |
| 16.01-24.0      | 10        | 14.93%  |
| 3.01-4.0        | 4         | 5.97%   |
| More than 256.0 | 3         | 4.48%   |
| 64.01-256.0     | 3         | 4.48%   |
| 1.01-2.0        | 3         | 4.48%   |
| 2.01-3.0        | 2         | 2.99%   |
| 24.01-32.0      | 1         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 17        | 25%     |
| 2.01-3.0  | 16        | 23.53%  |
| 1.01-2.0  | 15        | 22.06%  |
| 4.01-8.0  | 13        | 19.12%  |
| 8.01-16.0 | 4         | 5.88%   |
| 0.51-1.0  | 2         | 2.94%   |
| 0.01-0.5  | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 53.73%  |
| 2      | 15        | 22.39%  |
| 3      | 8         | 11.94%  |
| 4      | 4         | 5.97%   |
| 18     | 1         | 1.49%   |
| 16     | 1         | 1.49%   |
| 14     | 1         | 1.49%   |
| 8      | 1         | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 65.67%  |
| Yes       | 23        | 34.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 94.03%  |
| No        | 4         | 5.97%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 59.7%   |
| No        | 27        | 40.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 50.75%  |
| No        | 33        | 49.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 20.9%   |
| Germany      | 4         | 5.97%   |
| Czechia      | 4         | 5.97%   |
| Australia    | 4         | 5.97%   |
| South Africa | 3         | 4.48%   |
| Singapore    | 3         | 4.48%   |
| Russia       | 3         | 4.48%   |
| Israel       | 3         | 4.48%   |
| Canada       | 3         | 4.48%   |
| Poland       | 2         | 2.99%   |
| Mexico       | 2         | 2.99%   |
| India        | 2         | 2.99%   |
| Belgium      | 2         | 2.99%   |
| UK           | 1         | 1.49%   |
| Switzerland  | 1         | 1.49%   |
| Sweden       | 1         | 1.49%   |
| South Korea  | 1         | 1.49%   |
| Slovakia     | 1         | 1.49%   |
| Portugal     | 1         | 1.49%   |
| Norway       | 1         | 1.49%   |
| Netherlands  | 1         | 1.49%   |
| Malaysia     | 1         | 1.49%   |
| Kazakhstan   | 1         | 1.49%   |
| Japan        | 1         | 1.49%   |
| Italy        | 1         | 1.49%   |
| Hungary      | 1         | 1.49%   |
| France       | 1         | 1.49%   |
| Colombia     | 1         | 1.49%   |
| China        | 1         | 1.49%   |
| Brazil       | 1         | 1.49%   |
| Argentina    | 1         | 1.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 4.48%   |
| Melbourne              | 3         | 4.48%   |
| Prague                 | 2         | 2.99%   |
| Haifa                  | 2         | 2.99%   |
| Centurion              | 2         | 2.99%   |
| Berlin                 | 2         | 2.99%   |
| Žilina                | 1         | 1.49%   |
| Xi'an                  | 1         | 1.49%   |
| Waltham                | 1         | 1.49%   |
| Toronto                | 1         | 1.49%   |
| Tlaxcala City          | 1         | 1.49%   |
| St Petersburg          | 1         | 1.49%   |
| Sobral de Monte Agraco | 1         | 1.49%   |
| Smolensk               | 1         | 1.49%   |
| Senigallia             | 1         | 1.49%   |
| Scarborough            | 1         | 1.49%   |
| San Miguel de Tucumán | 1         | 1.49%   |
| Rehovot                | 1         | 1.49%   |
| Progresista            | 1         | 1.49%   |
| Philadelphia           | 1         | 1.49%   |
| Paris                  | 1         | 1.49%   |
| Ottignies              | 1         | 1.49%   |
| Ōtsu                  | 1         | 1.49%   |
| Oslo                   | 1         | 1.49%   |
| Örebro                | 1         | 1.49%   |
| Oakley                 | 1         | 1.49%   |
| Nur-Sultan             | 1         | 1.49%   |
| New York               | 1         | 1.49%   |
| Mossel Bay             | 1         | 1.49%   |
| Moscow                 | 1         | 1.49%   |
| Montreal               | 1         | 1.49%   |
| Mequon                 | 1         | 1.49%   |
| Manassas               | 1         | 1.49%   |
| Lebanon                | 1         | 1.49%   |
| Kutno                  | 1         | 1.49%   |
| Krasova                | 1         | 1.49%   |
| Krakow                 | 1         | 1.49%   |
| Johor Bahru            | 1         | 1.49%   |
| Jaú                   | 1         | 1.49%   |
| Imphal                 | 1         | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 18        | 23     | 17.65%  |
| Seagate                 | 16        | 44     | 15.69%  |
| WDC                     | 12        | 25     | 11.76%  |
| Toshiba                 | 10        | 10     | 9.8%    |
| Intel                   | 5         | 7      | 4.9%    |
| Unknown                 | 4         | 4      | 3.92%   |
| Hitachi                 | 4         | 5      | 3.92%   |
| SK hynix                | 3         | 4      | 2.94%   |
| SanDisk                 | 3         | 3      | 2.94%   |
| Kingston                | 3         | 3      | 2.94%   |
| Phison                  | 2         | 2      | 1.96%   |
| LITEONIT                | 2         | 2      | 1.96%   |
| Crucial                 | 2         | 2      | 1.96%   |
| Corsair                 | 2         | 2      | 1.96%   |
| A-DATA Technology       | 2         | 2      | 1.96%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.98%   |
| UMIS                    | 1         | 1      | 0.98%   |
| StoreJet                | 1         | 1      | 0.98%   |
| PNY                     | 1         | 1      | 0.98%   |
| LITEON                  | 1         | 1      | 0.98%   |
| IBM                     | 1         | 1      | 0.98%   |
| HGST                    | 1         | 1      | 0.98%   |
| Gigabyte Technology     | 1         | 1      | 0.98%   |
| Fujitsu                 | 1         | 1      | 0.98%   |
| Dogfish                 | 1         | 1      | 0.98%   |
| China                   | 1         | 1      | 0.98%   |
| Apacer                  | 1         | 1      | 0.98%   |
| AGI                     | 1         | 1      | 0.98%   |
| ADATA Technology        | 1         | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                       | 2         | 1.74%   |
| Seagate ST500DM002-1BD142 500GB              | 2         | 1.74%   |
| Seagate ST300MP0005 304GB                    | 2         | 1.74%   |
| Seagate ST2000DM008-2FR102 2TB               | 2         | 1.74%   |
| A-DATA SWORDFISH 1TB                         | 2         | 1.74%   |
| WDC WDS480G2G0A-00JH30 480GB SSD             | 1         | 0.87%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 0.87%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 0.87%   |
| WDC WD80EZZX-11CSGA0 8TB                     | 1         | 0.87%   |
| WDC WD80EMAZ-00WJTA0 8TB                     | 1         | 0.87%   |
| WDC WD80EDAZ-11TA3A0 8TB                     | 1         | 0.87%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 0.87%   |
| WDC WD5000AAKX-75U6AA0 500GB                 | 1         | 0.87%   |
| WDC WD5000AAKX-001CA0 500GB                  | 1         | 0.87%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 0.87%   |
| WDC WD2500AAJS-22VTA0 250GB                  | 1         | 0.87%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1         | 0.87%   |
| WDC WD120EDAZ-11F3RA0 12TB                   | 1         | 0.87%   |
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 0.87%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 0.87%   |
| WDC WD100EMAZ-00WJTA0 10TB                   | 1         | 0.87%   |
| WDC WD1001FALS-00J7B0 1TB                    | 1         | 0.87%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB         | 1         | 0.87%   |
| Unknown SD/MMC/MS PRO 2GB                    | 1         | 0.87%   |
| Unknown DA4064  64GB                         | 1         | 0.87%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.87%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 0.87%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 0.87%   |
| Toshiba THNSNJ128GCSU 128GB SSD              | 1         | 0.87%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 0.87%   |
| Toshiba PX05SVB192Y 1.9TB                    | 1         | 0.87%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.87%   |
| Toshiba MG07ACA12TE 12TB                     | 1         | 0.87%   |
| Toshiba MG04ACA400E 4TB                      | 1         | 0.87%   |
| Toshiba MG03ACA400 4TB                       | 1         | 0.87%   |
| Toshiba DT01ACA100 1TB                       | 1         | 0.87%   |
| Toshiba DT01ACA050 500GB                     | 1         | 0.87%   |
| StoreJet Disk 2TB                            | 1         | 0.87%   |
| SK hynix SHGS31-1000GS-2 1TB SSD             | 1         | 0.87%   |
| SK hynix SH920 2.5 7MM 256GB SSD             | 1         | 0.87%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 44     | 39.02%  |
| WDC                 | 9         | 20     | 21.95%  |
| Toshiba             | 5         | 5      | 12.2%   |
| Hitachi             | 4         | 5      | 9.76%   |
| Samsung Electronics | 2         | 3      | 4.88%   |
| Unknown             | 1         | 1      | 2.44%   |
| StoreJet            | 1         | 1      | 2.44%   |
| IBM                 | 1         | 1      | 2.44%   |
| HGST                | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 22.58%  |
| Toshiba             | 4         | 4      | 12.9%   |
| WDC                 | 3         | 3      | 9.68%   |
| SanDisk             | 3         | 3      | 9.68%   |
| SK hynix            | 2         | 2      | 6.45%   |
| LITEONIT            | 2         | 2      | 6.45%   |
| PNY                 | 1         | 1      | 3.23%   |
| LITEON              | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |
| Intel               | 1         | 2      | 3.23%   |
| Gigabyte Technology | 1         | 1      | 3.23%   |
| Dogfish             | 1         | 1      | 3.23%   |
| Crucial             | 1         | 1      | 3.23%   |
| Corsair             | 1         | 1      | 3.23%   |
| China               | 1         | 1      | 3.23%   |
| Apacer              | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 30        | 82     | 34.48%  |
| SSD     | 27        | 33     | 31.03%  |
| NVMe    | 26        | 33     | 29.89%  |
| MMC     | 3         | 3      | 3.45%   |
| Unknown | 1         | 1      | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 112    | 58.23%  |
| NVMe | 26        | 33     | 32.91%  |
| SAS  | 4         | 4      | 5.06%   |
| MMC  | 3         | 3      | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 46     | 48.39%  |
| 0.51-1.0   | 15        | 21     | 24.19%  |
| 1.01-2.0   | 9         | 12     | 14.52%  |
| 3.01-4.0   | 4         | 20     | 6.45%   |
| 10.01-20.0 | 2         | 3      | 3.23%   |
| 2.01-3.0   | 1         | 1      | 1.61%   |
| 4.01-10.0  | 1         | 12     | 1.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 18        | 26.87%  |
| 251-500        | 15        | 22.39%  |
| 501-1000       | 10        | 14.93%  |
| 1001-2000      | 9         | 13.43%  |
| More than 3000 | 6         | 8.96%   |
| 2001-3000      | 4         | 5.97%   |
| 51-100         | 3         | 4.48%   |
| 1-20           | 1         | 1.49%   |
| Unknown        | 1         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 32.84%  |
| 21-50          | 14        | 20.9%   |
| 101-250        | 7         | 10.45%  |
| 501-1000       | 6         | 8.96%   |
| 51-100         | 6         | 8.96%   |
| 251-500        | 4         | 5.97%   |
| More than 3000 | 3         | 4.48%   |
| 1001-2000      | 3         | 4.48%   |
| 2001-3000      | 1         | 1.49%   |
| Unknown        | 1         | 1.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 11.11%  |
| Seagate ST9320325AS 320GB             | 1         | 1      | 11.11%  |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 11.11%  |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 11.11%  |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 11.11%  |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 11.11%  |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 11.11%  |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 11.11%  |
| Corsair Neutron SSD 64GB              | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 14     | 44.44%  |
| Hitachi | 2         | 2      | 22.22%  |
| WDC     | 1         | 4      | 11.11%  |
| IBM     | 1         | 1      | 11.11%  |
| Corsair | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 14     | 50%     |
| Hitachi | 2         | 2      | 25%     |
| WDC     | 1         | 4      | 12.5%   |
| IBM     | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 21     | 88.89%  |
| SSD  | 1         | 1      | 11.11%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 38        | 82     | 49.35%  |
| Detected | 30        | 48     | 38.96%  |
| Malfunc  | 9         | 22     | 11.69%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 46        | 51.69%  |
| AMD                          | 12        | 13.48%  |
| Samsung Electronics          | 8         | 8.99%   |
| LSI Logic / Symbios Logic    | 4         | 4.49%   |
| Phison Electronics           | 3         | 3.37%   |
| Broadcom / LSI               | 3         | 3.37%   |
| Realtek Semiconductor        | 2         | 2.25%   |
| Kingston Technology Company  | 2         | 2.25%   |
| Union Memory (Shenzhen)      | 1         | 1.12%   |
| Toshiba America Info Systems | 1         | 1.12%   |
| SK hynix                     | 1         | 1.12%   |
| SanDisk                      | 1         | 1.12%   |
| Micron/Crucial Technology    | 1         | 1.12%   |
| Marvell Technology Group     | 1         | 1.12%   |
| ASMedia Technology           | 1         | 1.12%   |
| ADATA Technology             | 1         | 1.12%   |
| Adaptec                      | 1         | 1.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 8.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 4.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 3.7%    |
| Intel SATA Controller [RAID mode]                                                       | 3         | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.85%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2         | 1.85%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 1.85%   |
| Intel SSD 660P Series                                                                   | 2         | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.85%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 1.85%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 1.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 1.85%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 1.85%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.85%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.85%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2         | 1.85%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.93%   |
| SK hynix BC511                                                                          | 1         | 0.93%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.93%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1         | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.93%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 0.93%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 0.93%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 1         | 0.93%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                               | 1         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 40        | 43.01%  |
| NVMe | 26        | 27.96%  |
| IDE  | 14        | 15.05%  |
| RAID | 9         | 9.68%   |
| SAS  | 3         | 3.23%   |
| SCSI | 1         | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 50        | 74.63%  |
| AMD    | 16        | 23.88%  |
| ARM    | 1         | 1.49%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Xeon CPU L5530 @ 2.40GHz              | 2         | 2.99%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 2.99%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 2.99%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 1.49%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 1         | 1.49%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 1.49%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 1.49%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 1.49%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1         | 1.49%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 1.49%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 1.49%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 1.49%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 1.49%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.49%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.49%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 1.49%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1.49%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 1.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.49%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.49%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.49%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 1.49%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 1.49%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 1.49%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.49%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.49%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.49%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1         | 1.49%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1         | 1.49%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 26.87%  |
| Intel Xeon              | 10        | 14.93%  |
| Intel Core i5           | 9         | 13.43%  |
| Other                   | 5         | 7.46%   |
| AMD Ryzen 5             | 4         | 5.97%   |
| Intel Celeron           | 3         | 4.48%   |
| AMD Ryzen 7             | 3         | 4.48%   |
| AMD Ryzen Threadripper  | 2         | 2.99%   |
| AMD Ryzen 9             | 2         | 2.99%   |
| Intel Xeon Silver       | 1         | 1.49%   |
| Intel Xeon Gold         | 1         | 1.49%   |
| Intel Pentium Dual-Core | 1         | 1.49%   |
| Intel Pentium Dual      | 1         | 1.49%   |
| Intel Core i3           | 1         | 1.49%   |
| Intel Core 2 Quad       | 1         | 1.49%   |
| Intel Core 2 Duo        | 1         | 1.49%   |
| AMD Ryzen 7 PRO         | 1         | 1.49%   |
| AMD Ryzen 5 PRO         | 1         | 1.49%   |
| AMD Ryzen 3             | 1         | 1.49%   |
| AMD FX                  | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 25        | 37.31%  |
| 2      | 13        | 19.4%   |
| 8      | 11        | 16.42%  |
| 6      | 8         | 11.94%  |
| 16     | 3         | 4.48%   |
| 12     | 2         | 2.99%   |
| 32     | 1         | 1.49%   |
| 28     | 1         | 1.49%   |
| 24     | 1         | 1.49%   |
| 10     | 1         | 1.49%   |
| 3      | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 89.55%  |
| 2      | 7         | 10.45%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 73.13%  |
| 1      | 18        | 26.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 67        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 9         | 13.43%  |
| 0x806ec    | 3         | 4.48%   |
| 0x506e3    | 3         | 4.48%   |
| 0x306a9    | 3         | 4.48%   |
| 0x206a7    | 3         | 4.48%   |
| 0xa0655    | 2         | 2.99%   |
| 0x806c1    | 2         | 2.99%   |
| 0x706a8    | 2         | 2.99%   |
| 0x40651    | 2         | 2.99%   |
| 0x306e4    | 2         | 2.99%   |
| 0x106a5    | 2         | 2.99%   |
| 0x10676    | 2         | 2.99%   |
| 0x0a50000c | 2         | 2.99%   |
| 0x08608103 | 2         | 2.99%   |
| 0x08600104 | 2         | 2.99%   |
| Unknown    | 2         | 2.99%   |
| 0xa0652    | 1         | 1.49%   |
| 0x906ed    | 1         | 1.49%   |
| 0x906ea    | 1         | 1.49%   |
| 0x906a4    | 1         | 1.49%   |
| 0x6fd      | 1         | 1.49%   |
| 0x50657    | 1         | 1.49%   |
| 0x50654    | 1         | 1.49%   |
| 0x406f1    | 1         | 1.49%   |
| 0x406e3    | 1         | 1.49%   |
| 0x306f2    | 1         | 1.49%   |
| 0x206d7    | 1         | 1.49%   |
| 0x206c2    | 1         | 1.49%   |
| 0x1067a    | 1         | 1.49%   |
| 0x10677    | 1         | 1.49%   |
| 0x0a201009 | 1         | 1.49%   |
| 0x0870100a | 1         | 1.49%   |
| 0x08600106 | 1         | 1.49%   |
| 0x0830104d | 1         | 1.49%   |
| 0x08301039 | 1         | 1.49%   |
| 0x08108109 | 1         | 1.49%   |
| 0x08108102 | 1         | 1.49%   |
| 0x0800820d | 1         | 1.49%   |
| 0x06006705 | 1         | 1.49%   |
| 0x06000852 | 1         | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 13        | 19.4%   |
| Zen 2            | 6         | 8.96%   |
| Skylake          | 6         | 8.96%   |
| KabyLake         | 5         | 7.46%   |
| IvyBridge        | 5         | 7.46%   |
| SandyBridge      | 4         | 5.97%   |
| Penryn           | 4         | 5.97%   |
| Zen+             | 3         | 4.48%   |
| Zen 3            | 3         | 4.48%   |
| CometLake        | 3         | 4.48%   |
| Unknown          | 3         | 4.48%   |
| TigerLake        | 2         | 2.99%   |
| Nehalem          | 2         | 2.99%   |
| Goldmont plus    | 2         | 2.99%   |
| Westmere         | 1         | 1.49%   |
| Piledriver       | 1         | 1.49%   |
| Excavator        | 1         | 1.49%   |
| Core             | 1         | 1.49%   |
| Broadwell        | 1         | 1.49%   |
| Alderlake Hybrid | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 31        | 37.8%   |
| Nvidia                     | 28        | 34.15%  |
| AMD                        | 16        | 19.51%  |
| Matrox Electronics Systems | 4         | 4.88%   |
| ASPEED Technology          | 3         | 3.66%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 4.88%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 3.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 3.66%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3         | 3.66%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 2.44%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 2.44%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.44%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.44%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 2.44%   |
| AMD Renoir                                                                  | 2         | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 2.44%   |
| AMD Lucienne                                                                | 2         | 2.44%   |
| AMD Cezanne                                                                 | 2         | 2.44%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.22%   |
| Nvidia TU117GL [T600]                                                       | 1         | 1.22%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.22%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 1.22%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 1.22%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 1.22%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.22%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.22%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 1.22%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 1.22%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.22%   |
| Nvidia GK107M [GeForce GT 755M]                                             | 1         | 1.22%   |
| Nvidia GK107GL [Quadro K600]                                                | 1         | 1.22%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.22%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 1.22%   |
| Nvidia GK104GL [GRID K2]                                                    | 1         | 1.22%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 1.22%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1         | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.22%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1         | 1.22%   |
| Nvidia GA102GL [RTX A6000]                                                  | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 17        | 25.37%  |
| 1 x Nvidia      | 15        | 22.39%  |
| 1 x AMD         | 13        | 19.4%   |
| Intel + Nvidia  | 11        | 16.42%  |
| 1 x Matrox      | 3         | 4.48%   |
| 1 x ASPEED      | 3         | 4.48%   |
| Intel + AMD     | 2         | 2.99%   |
| Other           | 1         | 1.49%   |
| Nvidia + Matrox | 1         | 1.49%   |
| AMD + Nvidia    | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 50        | 74.63%  |
| Proprietary | 11        | 16.42%  |
| Unknown     | 6         | 8.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 44.78%  |
| 0.01-0.5   | 11        | 16.42%  |
| 1.01-2.0   | 9         | 13.43%  |
| 3.01-4.0   | 6         | 8.96%   |
| 0.51-1.0   | 4         | 5.97%   |
| 5.01-6.0   | 3         | 4.48%   |
| 7.01-8.0   | 2         | 2.99%   |
| 32.01-64.0 | 1         | 1.49%   |
| 8.01-16.0  | 1         | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 11        | 15.94%  |
| Samsung Electronics | 7         | 10.14%  |
| LG Display          | 6         | 8.7%    |
| Goldstar            | 6         | 8.7%    |
| Chimei Innolux      | 6         | 8.7%    |
| AU Optronics        | 6         | 8.7%    |
| BOE                 | 4         | 5.8%    |
| Iiyama              | 3         | 4.35%   |
| AOC                 | 3         | 4.35%   |
| Philips             | 2         | 2.9%    |
| ASUSTek Computer    | 2         | 2.9%    |
| Acer                | 2         | 2.9%    |
| Sony                | 1         | 1.45%   |
| Sharp               | 1         | 1.45%   |
| PANDA               | 1         | 1.45%   |
| Panasonic           | 1         | 1.45%   |
| OEM                 | 1         | 1.45%   |
| Lenovo              | 1         | 1.45%   |
| IBM                 | 1         | 1.45%   |
| Hewlett-Packard     | 1         | 1.45%   |
| HCL                 | 1         | 1.45%   |
| Eizo                | 1         | 1.45%   |
| ADR                 | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony LG TV SNY045B 1920x540                                           | 1         | 1.37%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 1.37%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 1.37%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 1.37%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.37%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 1.37%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1.37%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.37%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 1.37%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.37%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 1         | 1.37%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                       | 1         | 1.37%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.37%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.37%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 1         | 1.37%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1         | 1.37%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1         | 1.37%   |
| IBM RSA2 IBM029A 1024x768 300x225mm 14.8-inch                         | 1         | 1.37%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1         | 1.37%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                   | 1         | 1.37%   |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                   | 1         | 1.37%   |
| Goldstar W2252 GSM567D 1680x1050 490x320mm 23.0-inch                  | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM76F6 1920x1080 800x335mm 34.1-inch              | 1         | 1.37%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.37%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.37%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.37%   |
| Eizo CG247X ENC2801 1920x1200 520x330mm 24.2-inch                     | 1         | 1.37%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 1         | 1.37%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 1.37%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 1.37%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 27        | 42.86%  |
| 1600x900 (HD+)     | 5         | 7.94%   |
| 1920x1200 (WUXGA)  | 4         | 6.35%   |
| 1366x768 (WXGA)    | 4         | 6.35%   |
| 3840x2160 (4K)     | 3         | 4.76%   |
| 3840x1080          | 3         | 4.76%   |
| 1280x1024 (SXGA)   | 3         | 4.76%   |
| 3440x1440          | 2         | 3.17%   |
| 2560x1080          | 2         | 3.17%   |
| 1920x540           | 2         | 3.17%   |
| 1680x1050 (WSXGA+) | 2         | 3.17%   |
| 1440x900 (WXGA+)   | 2         | 3.17%   |
| Unknown            | 2         | 3.17%   |
| 2560x1440 (QHD)    | 1         | 1.59%   |
| 1024x768 (XGA)     | 1         | 1.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 23.19%  |
| 14      | 9         | 13.04%  |
| 27      | 8         | 11.59%  |
| 24      | 5         | 7.25%   |
| 21      | 4         | 5.8%    |
| 17      | 4         | 5.8%    |
| 34      | 3         | 4.35%   |
| 23      | 3         | 4.35%   |
| 19      | 3         | 4.35%   |
| 13      | 3         | 4.35%   |
| Unknown | 2         | 2.9%    |
| 65      | 1         | 1.45%   |
| 49      | 1         | 1.45%   |
| 48      | 1         | 1.45%   |
| 40      | 1         | 1.45%   |
| 31      | 1         | 1.45%   |
| 28      | 1         | 1.45%   |
| 22      | 1         | 1.45%   |
| 20      | 1         | 1.45%   |
| 18      | 1         | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 42.03%  |
| 501-600     | 16        | 23.19%  |
| 401-500     | 11        | 15.94%  |
| 701-800     | 3         | 4.35%   |
| 1001-1500   | 3         | 4.35%   |
| 351-400     | 2         | 2.9%    |
| Unknown     | 2         | 2.9%    |
| 801-900     | 1         | 1.45%   |
| 601-700     | 1         | 1.45%   |
| 201-300     | 1         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 69.49%  |
| 16/10   | 6         | 10.17%  |
| 5/4     | 3         | 5.08%   |
| 21/9    | 3         | 5.08%   |
| 32/9    | 2         | 3.39%   |
| 3/2     | 2         | 3.39%   |
| 4/3     | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 23.53%  |
| 81-90          | 11        | 16.18%  |
| 201-250        | 9         | 13.24%  |
| 301-350        | 8         | 11.76%  |
| 351-500        | 5         | 7.35%   |
| 151-200        | 5         | 7.35%   |
| 141-150        | 3         | 4.41%   |
| 501-1000       | 3         | 4.41%   |
| 251-300        | 2         | 2.94%   |
| 121-130        | 2         | 2.94%   |
| Unknown        | 2         | 2.94%   |
| More than 1000 | 1         | 1.47%   |
| 91-100         | 1         | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 28        | 41.18%  |
| 121-160       | 25        | 36.76%  |
| 101-120       | 9         | 13.24%  |
| 161-240       | 2         | 2.94%   |
| Unknown       | 2         | 2.94%   |
| More than 240 | 1         | 1.47%   |
| 1-50          | 1         | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 55.22%  |
| 0     | 14        | 20.9%   |
| 2     | 13        | 19.4%   |
| 3     | 2         | 2.99%   |
| 4     | 1         | 1.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 42        | 44.21%  |
| Realtek Semiconductor     | 29        | 30.53%  |
| Broadcom                  | 5         | 5.26%   |
| Qualcomm Atheros          | 4         | 4.21%   |
| Mellanox Technologies     | 3         | 3.16%   |
| MediaTek                  | 2         | 2.11%   |
| Marvell Technology Group  | 2         | 2.11%   |
| Solarflare Communications | 1         | 1.05%   |
| Ralink Technology         | 1         | 1.05%   |
| Qualcomm                  | 1         | 1.05%   |
| Microsoft                 | 1         | 1.05%   |
| Linksys                   | 1         | 1.05%   |
| BUFFALO                   | 1         | 1.05%   |
| Broadcom Limited          | 1         | 1.05%   |
| Aquantia                  | 1         | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 23        | 20.35%  |
| Intel Ethernet Connection I217-LM                                                                                      | 6         | 5.31%   |
| Intel Wireless 7260                                                                                                    | 5         | 4.42%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 5         | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 4         | 3.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 3         | 2.65%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 1.77%   |
| Intel Wireless 8260                                                                                                    | 2         | 1.77%   |
| Intel Wireless 3165                                                                                                    | 2         | 1.77%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 2         | 1.77%   |
| Intel I211 Gigabit Network Connection                                                                                  | 2         | 1.77%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 1.77%   |
| Intel Ethernet Connection I217-V                                                                                       | 2         | 1.77%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 2         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 2         | 1.77%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 2         | 1.77%   |
| Solarflare SFC9020 10G Ethernet Controller                                                                             | 1         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 1         | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                                | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                             | 1         | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 1         | 0.88%   |
| Realtek 802.11ac NIC                                                                                                   | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 1         | 0.88%   |
| Qualcomm Mobile Router                                                                                                 | 1         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 1         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                                              | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                                       | 1         | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                       | 1         | 0.88%   |
| Microsoft Xbox 360 Wireless Adapter                                                                                    | 1         | 0.88%   |
| Mellanox MT27700 Family [ConnectX-4]                                                                                   | 1         | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 1         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 1         | 0.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                                                | 1         | 0.88%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                                                                   | 1         | 0.88%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                                                      | 1         | 0.88%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                                    | 1         | 0.88%   |
| Intel Wireless 7265                                                                                                    | 1         | 0.88%   |
| Intel Wireless 3160                                                                                                    | 1         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                                                                        | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 67.5%   |
| Realtek Semiconductor | 4         | 10%     |
| Qualcomm Atheros      | 3         | 7.5%    |
| MediaTek              | 2         | 5%      |
| Ralink Technology     | 1         | 2.5%    |
| Microsoft             | 1         | 2.5%    |
| Linksys               | 1         | 2.5%    |
| BUFFALO               | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 5         | 12.5%   |
| Intel Wi-Fi 6 AX200                                           | 5         | 12.5%   |
| Intel Wireless 8260                                           | 2         | 5%      |
| Intel Wireless 3165                                           | 2         | 5%      |
| Intel Wi-Fi 6 AX201                                           | 2         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1         | 2.5%    |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 2.5%    |
| Realtek 802.11ac NIC                                          | 1         | 2.5%    |
| Ralink MT7601U Wireless Adapter                               | 1         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 2.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 1         | 2.5%    |
| Microsoft Xbox 360 Wireless Adapter                           | 1         | 2.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 2.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.5%    |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter           | 1         | 2.5%    |
| Intel Wireless 7265                                           | 1         | 2.5%    |
| Intel Wireless 3160                                           | 1         | 2.5%    |
| Intel Ultimate N WiFi Link 5300                               | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.5%    |
| Intel Centrino Wireless-N 135                                 | 1         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 2.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 2.5%    |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]      | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 27        | 41.54%  |
| Intel                     | 26        | 40%     |
| Broadcom                  | 5         | 7.69%   |
| Marvell Technology Group  | 2         | 3.08%   |
| Solarflare Communications | 1         | 1.54%   |
| Qualcomm Atheros          | 1         | 1.54%   |
| Qualcomm                  | 1         | 1.54%   |
| Broadcom Limited          | 1         | 1.54%   |
| Aquantia                  | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 32.86%  |
| Intel Ethernet Connection I217-LM                                 | 6         | 8.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.29%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.86%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 2.86%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.86%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.86%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 2.86%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 1.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.43%   |
| Qualcomm Mobile Router                                            | 1         | 1.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.43%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.43%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.43%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.43%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 1.43%   |
| Intel Ethernet Controller X550                                    | 1         | 1.43%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.43%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.43%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 1.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 1.43%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.43%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.43%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.43%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 1         | 1.43%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet      | 1         | 1.43%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 62        | 59.05%  |
| WiFi     | 40        | 38.1%   |
| Unknown  | 3         | 2.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 63.24%  |
| WiFi     | 24        | 35.29%  |
| Unknown  | 1         | 1.47%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 47.76%  |
| 1     | 25        | 37.31%  |
| 3     | 3         | 4.48%   |
| 5     | 2         | 2.99%   |
| 0     | 2         | 2.99%   |
| 66    | 1         | 1.49%   |
| 8     | 1         | 1.49%   |
| 4     | 1         | 1.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 79.1%   |
| Yes  | 14        | 20.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 67.65%  |
| Realtek Semiconductor           | 2         | 5.88%   |
| Foxconn / Hon Hai               | 2         | 5.88%   |
| Broadcom                        | 2         | 5.88%   |
| Qualcomm Atheros Communications | 1         | 2.94%   |
| MediaTek                        | 1         | 2.94%   |
| Integrated System Solution      | 1         | 2.94%   |
| IMC Networks                    | 1         | 2.94%   |
| Cambridge Silicon Radio         | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 12        | 35.29%  |
| Intel AX200 Bluetooth                                 | 5         | 14.71%  |
| Intel AX201 Bluetooth                                 | 4         | 11.76%  |
| Foxconn / Hon Hai Wireless_Device                     | 2         | 5.88%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 2.94%   |
| Realtek Bluetooth Radio                               | 1         | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                    | 1         | 2.94%   |
| MediaTek Wireless_Device                              | 1         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 2.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1         | 2.94%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 2.94%   |
| IMC Networks Bluetooth Device                         | 1         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 2.94%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 42        | 45.16%  |
| Nvidia              | 22        | 23.66%  |
| AMD                 | 17        | 18.28%  |
| C-Media Electronics | 3         | 3.23%   |
| Logitech            | 2         | 2.15%   |
| Unknown             | 1         | 1.08%   |
| Nektar              | 1         | 1.08%   |
| Hewlett-Packard     | 1         | 1.08%   |
| GN Netcom           | 1         | 1.08%   |
| Creative Technology | 1         | 1.08%   |
| Conexant Systems    | 1         | 1.08%   |
| ASUSTek Computer    | 1         | 1.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 7.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 7.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 5.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 5.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.42%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 3.54%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 2.65%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 2.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.77%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.77%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 1.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.77%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.77%   |
| C-Media Electronics USB MICROPHONE                                         | 2         | 1.77%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2         | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.77%   |
| Unknown Realtek USB Audio Rear                                             | 1         | 0.88%   |
| Unknown Realtek USB Audio Front                                            | 1         | 0.88%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.88%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.88%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.88%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.88%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.88%   |
| Nektar Impact GX61                                                         | 1         | 0.88%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 0.88%   |
| Logitech Stereo H650e                                                      | 1         | 0.88%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 12        | 27.91%  |
| Samsung Electronics | 11        | 25.58%  |
| G.Skill             | 4         | 9.3%    |
| Unknown             | 3         | 6.98%   |
| SK hynix            | 3         | 6.98%   |
| Kingston            | 3         | 6.98%   |
| Crucial             | 2         | 4.65%   |
| Unknown (ABCD)      | 1         | 2.33%   |
| Patriot             | 1         | 2.33%   |
| Magnum Tech         | 1         | 2.33%   |
| Corsair             | 1         | 2.33%   |
| A-DATA Technology   | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM 667MT/s                                   | 1         | 2.22%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 2.22%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                              | 1         | 2.22%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                   | 1         | 2.22%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s      | 1         | 2.22%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                  | 1         | 2.22%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                | 1         | 2.22%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s            | 1         | 2.22%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s              | 1         | 2.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.22%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                | 1         | 2.22%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.22%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s                  | 1         | 2.22%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 2.22%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 2.22%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 2.22%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                   | 1         | 2.22%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 2.22%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s                  | 1         | 2.22%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s                      | 1         | 2.22%   |
| Micron RAM MT53E1G32D4NQ_046 8GB Row Of Chips LPDDR4 4267MT/s         | 1         | 2.22%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                              | 1         | 2.22%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                   | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                  | 1         | 2.22%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                    | 1         | 2.22%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s            | 1         | 2.22%   |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s                  | 1         | 2.22%   |
| Micron RAM 36ASF4G72PZ-2G3D1 32GB DIMM DDR4 2400MT/s                  | 1         | 2.22%   |
| Micron RAM 3138485446313238373241592D3636374631 1GB DIMM DDR2 667MT/s | 1         | 2.22%   |
| Micron RAM 18ASF2G72AZ-2G3A1 16GB DIMM DDR4 2400MT/s                  | 1         | 2.22%   |
| Micron RAM 18ASF1G72PDZ-2G6F1 8GB DIMM DDR4 2666MT/s                  | 1         | 2.22%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.22%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.22%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s                | 1         | 2.22%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 2.22%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 2.22%   |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s                | 1         | 2.22%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3600MT/s                   | 1         | 2.22%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s                  | 1         | 2.22%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s                    | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 21        | 51.22%  |
| DDR3    | 14        | 34.15%  |
| LPDDR4  | 3         | 7.32%   |
| DDR2    | 2         | 4.88%   |
| Unknown | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 25        | 60.98%  |
| SODIMM       | 13        | 31.71%  |
| Row Of Chips | 2         | 4.88%   |
| RIMM         | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 19        | 44.19%  |
| 16384 | 7         | 16.28%  |
| 32768 | 6         | 13.95%  |
| 1024  | 5         | 11.63%  |
| 4096  | 4         | 9.3%    |
| 2048  | 2         | 4.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 9         | 21.43%  |
| 1600  | 6         | 14.29%  |
| 2667  | 5         | 11.9%   |
| 2400  | 5         | 11.9%   |
| 667   | 3         | 7.14%   |
| 2666  | 2         | 4.76%   |
| 2133  | 2         | 4.76%   |
| 1066  | 2         | 4.76%   |
| 4267  | 1         | 2.38%   |
| 4266  | 1         | 2.38%   |
| 3600  | 1         | 2.38%   |
| 3400  | 1         | 2.38%   |
| 2200  | 1         | 2.38%   |
| 1866  | 1         | 2.38%   |
| 1800  | 1         | 2.38%   |
| 1333  | 1         | 2.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother HL-2030 Laser Printer | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP OfficeJet 6110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 18.75%  |
| Syntek                                 | 4         | 12.5%   |
| Logitech                               | 3         | 9.38%   |
| Realtek Semiconductor                  | 2         | 6.25%   |
| Microdia                               | 2         | 6.25%   |
| Luxvisions Innotech Limited            | 2         | 6.25%   |
| IMC Networks                           | 2         | 6.25%   |
| Sunplus Innovation Technology          | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| Lenovo                                 | 1         | 3.13%   |
| Intel                                  | 1         | 3.13%   |
| Huawei Technologies                    | 1         | 3.13%   |
| Generalplus Technology                 | 1         | 3.13%   |
| Elgato Systems                         | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |
| Apple                                  | 1         | 3.13%   |
| Acer                                   | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 12.5%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 6.25%   |
| Syntek Integrated Camera                                                   | 2         | 6.25%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 6.25%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.13%   |
| Realtek EasyCamera                                                         | 1         | 3.13%   |
| Quanta HP Webcam                                                           | 1         | 3.13%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 3.13%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 3.13%   |
| Logitech Webcam C270                                                       | 1         | 3.13%   |
| Logitech HD Pro Webcam C920                                                | 1         | 3.13%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 3.13%   |
| Lite-On HP HD Webcam                                                       | 1         | 3.13%   |
| Lenovo UVC Camera                                                          | 1         | 3.13%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 3.13%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 3.13%   |
| Huawei HiCamera                                                            | 1         | 3.13%   |
| Generalplus GENERAL WEBCAM                                                 | 1         | 3.13%   |
| Elgato Systems Elgato Facecam                                              | 1         | 3.13%   |
| Chicony HP HD Camera                                                       | 1         | 3.13%   |
| Chicony HD WebCam                                                          | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.13%   |
| Apple iPhone5/5C/5S/6                                                      | 1         | 3.13%   |
| Acer Integrated Camera                                                     | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Synaptics                  | 3         | 27.27%  |
| LighTuning Technology      | 2         | 18.18%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 18.18%  |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 9.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 9.09%   |
| LighTuning Fingerprint Sensor                              | 1         | 9.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 9.09%   |
| AuthenTec AES2810                                          | 1         | 9.09%   |
| Unknown                                                    | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 33.33%  |
| Broadcom 58200                       | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 47.76%  |
| 1     | 25        | 37.31%  |
| 2     | 7         | 10.45%  |
| 5     | 1         | 1.49%   |
| 4     | 1         | 1.49%   |
| 3     | 1         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 23.91%  |
| Net/wireless             | 8         | 17.39%  |
| Graphics card            | 7         | 15.22%  |
| Unassigned class         | 4         | 8.7%    |
| Communication controller | 4         | 8.7%    |
| Network                  | 2         | 4.35%   |
| Net/ethernet             | 2         | 4.35%   |
| Multimedia controller    | 2         | 4.35%   |
| Chipcard                 | 2         | 4.35%   |
| Storage                  | 1         | 2.17%   |
| Sound                    | 1         | 2.17%   |
| Firewire controller      | 1         | 2.17%   |
| Card reader              | 1         | 2.17%   |

