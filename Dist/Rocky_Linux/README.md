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

Total: 90

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProLiant DL380 G7           | Server      | [6d994999c9](https://linux-hardware.org/?probe=6d994999c9) | Nov 01, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cda3087aaf](https://linux-hardware.org/?probe=cda3087aaf) | Oct 23, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [fd411132f6](https://linux-hardware.org/?probe=fd411132f6) | Oct 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
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
| Rocky Linux 8.5 | 31        | 40.79%  |
| Rocky Linux 8.4 | 19        | 25%     |
| Rocky Linux 9.0 | 15        | 19.74%  |
| Rocky Linux 8.6 | 9         | 11.84%  |
| Rocky Linux 8.3 | 2         | 2.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 75        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 17.11%  |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 10.53%  |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 7.89%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 5         | 6.58%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 6.58%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 5.26%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 5.26%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 3.95%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 2.63%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 2.63%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 2.63%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 2.63%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 2.63%   |
| 4.18.0-305.el8.x86_64            | 2         | 2.63%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 2.63%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 2.63%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 2.63%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 2.63%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.32%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1         | 1.32%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.32%   |
| 5.10.89-1.el8.x86_64             | 1         | 1.32%   |
| 5.10.52-v8.1.el8                 | 1         | 1.32%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 1         | 1.32%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.32%   |
| 4.18.0-348.23.1.el8_5.x86_64     | 1         | 1.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 56        | 74.67%  |
| 5.14.0  | 15        | 20%     |
| 5.4.157 | 1         | 1.33%   |
| 5.14.1  | 1         | 1.33%   |
| 5.10.89 | 1         | 1.33%   |
| 5.10.52 | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 56        | 74.67%  |
| 5.14    | 16        | 21.33%  |
| 5.10    | 2         | 2.67%   |
| 5.4     | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 74        | 98.67%  |
| aarch64 | 1         | 1.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 54        | 72%     |
| Unknown       | 7         | 9.33%   |
| MATE          | 5         | 6.67%   |
| KDE5          | 4         | 5.33%   |
| GNOME Classic | 3         | 4%      |
| XFCE          | 1         | 1.33%   |
| X-Cinnamon    | 1         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 42        | 56%     |
| X11     | 28        | 37.33%  |
| Unknown | 5         | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 49.33%  |
| GDM     | 33        | 44%     |
| SDDM    | 3         | 4%      |
| LightDM | 2         | 2.67%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 47        | 62.67%  |
| ru_RU   | 4         | 5.33%   |
| en_AU   | 4         | 5.33%   |
| en_IL   | 3         | 4%      |
| en_CA   | 3         | 4%      |
| en_ZA   | 2         | 2.67%   |
| en_SG   | 2         | 2.67%   |
| de_DE   | 2         | 2.67%   |
| pt_BR   | 1         | 1.33%   |
| pl_PL   | 1         | 1.33%   |
| ja_JP   | 1         | 1.33%   |
| it_IT   | 1         | 1.33%   |
| hu_HU   | 1         | 1.33%   |
| es_CO   | 1         | 1.33%   |
| af_ZA   | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 41        | 54.67%  |
| BIOS | 34        | 45.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 60        | 80%     |
| Ext4 | 14        | 18.67%  |
| Ext3 | 1         | 1.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 41.33%  |
| GPT     | 27        | 36%     |
| MBR     | 17        | 22.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 82.67%  |
| Yes       | 13        | 17.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 88%     |
| Yes       | 9         | 12%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 15        | 20%     |
| Dell                    | 15        | 20%     |
| ASUSTek Computer        | 14        | 18.67%  |
| Hewlett-Packard         | 8         | 10.67%  |
| Gigabyte Technology     | 5         | 6.67%   |
| Toshiba                 | 2         | 2.67%   |
| Supermicro              | 2         | 2.67%   |
| AZW                     | 2         | 2.67%   |
| Unknown                 | 2         | 2.67%   |
| Raspberry Pi Foundation | 1         | 1.33%   |
| NCR                     | 1         | 1.33%   |
| MSI                     | 1         | 1.33%   |
| Intel                   | 1         | 1.33%   |
| IBM                     | 1         | 1.33%   |
| Google                  | 1         | 1.33%   |
| BESSTAR Tech            | 1         | 1.33%   |
| BANGHO                  | 1         | 1.33%   |
| ASRock                  | 1         | 1.33%   |
| Acer                    | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Dell PowerEdge R610                    | 2         | 2.67%   |
| Dell OptiPlex 9020                     | 2         | 2.67%   |
| Unknown                                | 2         | 2.67%   |
| Toshiba TECRA W50-A                    | 1         | 1.33%   |
| Toshiba Satellite E45-B                | 1         | 1.33%   |
| Supermicro SYS-5029P-WTR               | 1         | 1.33%   |
| Supermicro Super Server                | 1         | 1.33%   |
| RPi Raspberry Pi                       | 1         | 1.33%   |
| NCR xxxx-xxxx-xxxx                     | 1         | 1.33%   |
| MSI MS-7917                            | 1         | 1.33%   |
| Lenovo ThinkStation P620 30E0S0PR00    | 1         | 1.33%   |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 1.33%   |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 1.33%   |
| Lenovo ThinkPad W500 406132G           | 1         | 1.33%   |
| Lenovo ThinkPad T420 42365H1           | 1         | 1.33%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 1.33%   |
| Lenovo ThinkCentre M72e 36601Y8        | 1         | 1.33%   |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 1.33%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 1.33%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9       | 1         | 1.33%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 1.33%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 1.33%   |
| Lenovo IdeaPad Y410P 20216             | 1         | 1.33%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 1.33%   |
| Lenovo IdeaPad 500S-14ISK 80Q3         | 1         | 1.33%   |
| Intel S2600WFT                         | 1         | 1.33%   |
| IBM System x3200 M2 -[4368IGS]-        | 1         | 1.33%   |
| HP ZBook 15u G6                        | 1         | 1.33%   |
| HP ZBook 15 G3                         | 1         | 1.33%   |
| HP ZBook 15 G2                         | 1         | 1.33%   |
| HP Z600 Workstation                    | 1         | 1.33%   |
| HP ProLiant DL380 G7                   | 1         | 1.33%   |
| HP Pavilion g6                         | 1         | 1.33%   |
| HP Laptop 17-ca1xxx                    | 1         | 1.33%   |
| HP EliteBook 840 G7 Notebook PC        | 1         | 1.33%   |
| Google Panther                         | 1         | 1.33%   |
| Gigabyte X570 AORUS ULTRA              | 1         | 1.33%   |
| Gigabyte H87-D3H                       | 1         | 1.33%   |
| Gigabyte H81M-S2PV                     | 1         | 1.33%   |
| Gigabyte G41MT-USB3                    | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUS PRIME               | 7         | 9.33%   |
| Lenovo ThinkPad          | 5         | 6.67%   |
| Lenovo IdeaPad           | 4         | 5.33%   |
| Dell PowerEdge           | 4         | 5.33%   |
| HP ZBook                 | 3         | 4%      |
| Dell Precision           | 3         | 4%      |
| Dell OptiPlex            | 3         | 4%      |
| Dell Latitude            | 3         | 4%      |
| Lenovo Legion            | 2         | 2.67%   |
| Lenovo IdeaPadFlex       | 2         | 2.67%   |
| ASUS ASUS                | 2         | 2.67%   |
| Unknown                  | 2         | 2.67%   |
| Toshiba TECRA            | 1         | 1.33%   |
| Toshiba Satellite        | 1         | 1.33%   |
| Supermicro SYS-5029P-WTR | 1         | 1.33%   |
| Supermicro Super         | 1         | 1.33%   |
| RPi Raspberry            | 1         | 1.33%   |
| NCR xxxx-xxxx-xxxx       | 1         | 1.33%   |
| MSI MS-7917              | 1         | 1.33%   |
| Lenovo ThinkStation      | 1         | 1.33%   |
| Lenovo ThinkCentre       | 1         | 1.33%   |
| Intel S2600WFT           | 1         | 1.33%   |
| IBM System               | 1         | 1.33%   |
| HP Z600                  | 1         | 1.33%   |
| HP ProLiant              | 1         | 1.33%   |
| HP Pavilion              | 1         | 1.33%   |
| HP Laptop                | 1         | 1.33%   |
| HP EliteBook             | 1         | 1.33%   |
| Google Panther           | 1         | 1.33%   |
| Gigabyte X570            | 1         | 1.33%   |
| Gigabyte H87-D3H         | 1         | 1.33%   |
| Gigabyte H81M-S2PV       | 1         | 1.33%   |
| Gigabyte G41MT-USB3      | 1         | 1.33%   |
| Gigabyte 970A-UD3P       | 1         | 1.33%   |
| Dell XPS                 | 1         | 1.33%   |
| Dell Vostro              | 1         | 1.33%   |
| BESSTAR Tech HM90        | 1         | 1.33%   |
| BANGHO BES               | 1         | 1.33%   |
| AZW GTR                  | 1         | 1.33%   |
| AZW Gemini               | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 11        | 14.67%  |
| 2020    | 10        | 13.33%  |
| 2019    | 9         | 12%     |
| 2014    | 7         | 9.33%   |
| 2013    | 6         | 8%      |
| 2011    | 6         | 8%      |
| 2018    | 5         | 6.67%   |
| 2015    | 5         | 6.67%   |
| 2012    | 4         | 5.33%   |
| 2022    | 3         | 4%      |
| 2016    | 2         | 2.67%   |
| 2010    | 2         | 2.67%   |
| 2009    | 2         | 2.67%   |
| 2008    | 2         | 2.67%   |
| Unknown | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 33        | 44%     |
| Notebook       | 28        | 37.33%  |
| Server         | 9         | 12%     |
| Convertible    | 2         | 2.67%   |
| System on chip | 1         | 1.33%   |
| Tablet         | 1         | 1.33%   |
| Mini pc        | 1         | 1.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 72        | 96%     |
| Enabled  | 3         | 4%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 74        | 98.67%  |
| Yes  | 1         | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 17        | 22.67%  |
| 4.01-8.0        | 15        | 20%     |
| 32.01-64.0      | 14        | 18.67%  |
| 16.01-24.0      | 11        | 14.67%  |
| 3.01-4.0        | 4         | 5.33%   |
| 64.01-256.0     | 4         | 5.33%   |
| More than 256.0 | 3         | 4%      |
| 1.01-2.0        | 3         | 4%      |
| 24.01-32.0      | 2         | 2.67%   |
| 2.01-3.0        | 2         | 2.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 20        | 26.32%  |
| 3.01-4.0  | 17        | 22.37%  |
| 4.01-8.0  | 16        | 21.05%  |
| 1.01-2.0  | 15        | 19.74%  |
| 8.01-16.0 | 5         | 6.58%   |
| 0.51-1.0  | 2         | 2.63%   |
| 0.01-0.5  | 1         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 50.67%  |
| 2      | 17        | 22.67%  |
| 3      | 10        | 13.33%  |
| 4      | 5         | 6.67%   |
| 18     | 1         | 1.33%   |
| 16     | 1         | 1.33%   |
| 14     | 1         | 1.33%   |
| 8      | 1         | 1.33%   |
| 5      | 1         | 1.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 64%     |
| Yes       | 27        | 36%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 93.33%  |
| No        | 5         | 6.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 58.67%  |
| No        | 31        | 41.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 50.67%  |
| No        | 37        | 49.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 21.33%  |
| Australia    | 5         | 6.67%   |
| Russia       | 4         | 5.33%   |
| Germany      | 4         | 5.33%   |
| Czechia      | 4         | 5.33%   |
| Canada       | 4         | 5.33%   |
| South Africa | 3         | 4%      |
| Singapore    | 3         | 4%      |
| Israel       | 3         | 4%      |
| Sweden       | 2         | 2.67%   |
| Poland       | 2         | 2.67%   |
| Mexico       | 2         | 2.67%   |
| Italy        | 2         | 2.67%   |
| India        | 2         | 2.67%   |
| Belgium      | 2         | 2.67%   |
| UK           | 1         | 1.33%   |
| Turkey       | 1         | 1.33%   |
| Switzerland  | 1         | 1.33%   |
| South Korea  | 1         | 1.33%   |
| Slovakia     | 1         | 1.33%   |
| Portugal     | 1         | 1.33%   |
| Norway       | 1         | 1.33%   |
| Netherlands  | 1         | 1.33%   |
| Malaysia     | 1         | 1.33%   |
| Kazakhstan   | 1         | 1.33%   |
| Japan        | 1         | 1.33%   |
| Hungary      | 1         | 1.33%   |
| France       | 1         | 1.33%   |
| Colombia     | 1         | 1.33%   |
| China        | 1         | 1.33%   |
| Brazil       | 1         | 1.33%   |
| Argentina    | 1         | 1.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 4%      |
| Melbourne              | 3         | 4%      |
| Toronto                | 2         | 2.67%   |
| Prague                 | 2         | 2.67%   |
| Moscow                 | 2         | 2.67%   |
| Haifa                  | 2         | 2.67%   |
| Centurion              | 2         | 2.67%   |
| Berlin                 | 2         | 2.67%   |
| Žilina                | 1         | 1.33%   |
| Xi'an                  | 1         | 1.33%   |
| Waltham                | 1         | 1.33%   |
| Tlaxcala City          | 1         | 1.33%   |
| St Petersburg          | 1         | 1.33%   |
| Sobral de Monte Agraco | 1         | 1.33%   |
| Smolensk               | 1         | 1.33%   |
| Senigallia             | 1         | 1.33%   |
| Scarborough            | 1         | 1.33%   |
| San Miguel de Tucumán | 1         | 1.33%   |
| Rehovot                | 1         | 1.33%   |
| Progresista            | 1         | 1.33%   |
| Philadelphia           | 1         | 1.33%   |
| Paris                  | 1         | 1.33%   |
| Ottignies              | 1         | 1.33%   |
| Ōtsu                  | 1         | 1.33%   |
| Oslo                   | 1         | 1.33%   |
| Örebro                | 1         | 1.33%   |
| Oklahoma City          | 1         | 1.33%   |
| Oakley                 | 1         | 1.33%   |
| Nur-Sultan             | 1         | 1.33%   |
| New York               | 1         | 1.33%   |
| Mugla                  | 1         | 1.33%   |
| Mossel Bay             | 1         | 1.33%   |
| Monza                  | 1         | 1.33%   |
| Montreal               | 1         | 1.33%   |
| Mequon                 | 1         | 1.33%   |
| Manassas               | 1         | 1.33%   |
| Lebanon                | 1         | 1.33%   |
| Kutno                  | 1         | 1.33%   |
| Krasova                | 1         | 1.33%   |
| Krakow                 | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 20        | 50     | 17.24%  |
| Samsung Electronics     | 18        | 23     | 15.52%  |
| WDC                     | 15        | 31     | 12.93%  |
| Toshiba                 | 11        | 11     | 9.48%   |
| Kingston                | 5         | 5      | 4.31%   |
| Intel                   | 5         | 7      | 4.31%   |
| Unknown                 | 4         | 4      | 3.45%   |
| Hitachi                 | 4         | 5      | 3.45%   |
| SK hynix                | 3         | 4      | 2.59%   |
| SanDisk                 | 3         | 3      | 2.59%   |
| Crucial                 | 3         | 3      | 2.59%   |
| Phison                  | 2         | 2      | 1.72%   |
| LITEONIT                | 2         | 2      | 1.72%   |
| HGST                    | 2         | 2      | 1.72%   |
| Corsair                 | 2         | 2      | 1.72%   |
| A-DATA Technology       | 2         | 2      | 1.72%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.86%   |
| UMIS                    | 1         | 1      | 0.86%   |
| Team                    | 1         | 1      | 0.86%   |
| StoreJet                | 1         | 1      | 0.86%   |
| PNY                     | 1         | 1      | 0.86%   |
| LITEON                  | 1         | 1      | 0.86%   |
| IBM                     | 1         | 1      | 0.86%   |
| HS-SSD-C100             | 1         | 1      | 0.86%   |
| Gigabyte Technology     | 1         | 1      | 0.86%   |
| Fujitsu                 | 1         | 1      | 0.86%   |
| Dogfish                 | 1         | 1      | 0.86%   |
| China                   | 1         | 1      | 0.86%   |
| Apacer                  | 1         | 1      | 0.86%   |
| AGI                     | 1         | 1      | 0.86%   |
| ADATA Technology        | 1         | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB              | 3         | 2.27%   |
| Unknown MMC Card  64GB                       | 2         | 1.52%   |
| Seagate ST9320325AS 320GB                    | 2         | 1.52%   |
| Seagate ST300MP0005 304GB                    | 2         | 1.52%   |
| Seagate ST2000DM008-2FR102 2TB               | 2         | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB               | 2         | 1.52%   |
| A-DATA SWORDFISH 1TB                         | 2         | 1.52%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD             | 1         | 0.76%   |
| WDC WDS480G2G0A-00JH30 480GB SSD             | 1         | 0.76%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 0.76%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD               | 1         | 0.76%   |
| WDC WD80EZZX-11CSGA0 8TB                     | 1         | 0.76%   |
| WDC WD80EMAZ-00WJTA0 8TB                     | 1         | 0.76%   |
| WDC WD80EDAZ-11TA3A0 8TB                     | 1         | 0.76%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 0.76%   |
| WDC WD5000AUDX-63WNHY0 500GB                 | 1         | 0.76%   |
| WDC WD5000AAKX-75U6AA0 500GB                 | 1         | 0.76%   |
| WDC WD5000AAKX-001CA0 500GB                  | 1         | 0.76%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 0.76%   |
| WDC WD2500AAJS-22VTA0 250GB                  | 1         | 0.76%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1         | 0.76%   |
| WDC WD2002FAEX-007BA0 2TB                    | 1         | 0.76%   |
| WDC WD120EDAZ-11F3RA0 12TB                   | 1         | 0.76%   |
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 0.76%   |
| WDC WD100EMAZ-00WJTA0 10TB                   | 1         | 0.76%   |
| WDC WD1001FALS-00J7B0 1TB                    | 1         | 0.76%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB         | 1         | 0.76%   |
| Unknown SD/MMC/MS PRO 1TB                    | 1         | 0.76%   |
| Unknown DA4064  64GB                         | 1         | 0.76%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.76%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 0.76%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 0.76%   |
| Toshiba THNSNJ128GCSU 128GB SSD              | 1         | 0.76%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 0.76%   |
| Toshiba PX05SVB192Y 1.9TB                    | 1         | 0.76%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.76%   |
| Toshiba MK1059GSM 1TB                        | 1         | 0.76%   |
| Toshiba MG07ACA12TE 12TB                     | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 50     | 40.82%  |
| WDC                 | 11        | 22     | 22.45%  |
| Toshiba             | 6         | 6      | 12.24%  |
| Hitachi             | 4         | 5      | 8.16%   |
| Samsung Electronics | 2         | 3      | 4.08%   |
| HGST                | 2         | 2      | 4.08%   |
| Unknown             | 1         | 1      | 2.04%   |
| StoreJet            | 1         | 1      | 2.04%   |
| IBM                 | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 20%     |
| WDC                 | 4         | 7      | 11.43%  |
| Toshiba             | 4         | 4      | 11.43%  |
| SanDisk             | 3         | 3      | 8.57%   |
| SK hynix            | 2         | 2      | 5.71%   |
| LITEONIT            | 2         | 2      | 5.71%   |
| Kingston            | 2         | 2      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| Team                | 1         | 1      | 2.86%   |
| PNY                 | 1         | 1      | 2.86%   |
| LITEON              | 1         | 1      | 2.86%   |
| Intel               | 1         | 2      | 2.86%   |
| Gigabyte Technology | 1         | 1      | 2.86%   |
| Dogfish             | 1         | 1      | 2.86%   |
| Corsair             | 1         | 1      | 2.86%   |
| China               | 1         | 1      | 2.86%   |
| Apacer              | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 35        | 92     | 36.08%  |
| SSD     | 30        | 40     | 30.93%  |
| NVMe    | 27        | 34     | 27.84%  |
| MMC     | 3         | 3      | 3.09%   |
| Unknown | 2         | 2      | 2.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 129    | 60.23%  |
| NVMe | 27        | 34     | 30.68%  |
| SAS  | 5         | 5      | 5.68%   |
| MMC  | 3         | 3      | 3.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 56     | 47.89%  |
| 0.51-1.0   | 18        | 26     | 25.35%  |
| 1.01-2.0   | 11        | 14     | 15.49%  |
| 3.01-4.0   | 4         | 20     | 5.63%   |
| 10.01-20.0 | 2         | 3      | 2.82%   |
| 2.01-3.0   | 1         | 1      | 1.41%   |
| 4.01-10.0  | 1         | 12     | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 25.33%  |
| 251-500        | 17        | 22.67%  |
| 501-1000       | 11        | 14.67%  |
| 1001-2000      | 10        | 13.33%  |
| More than 3000 | 7         | 9.33%   |
| 2001-3000      | 4         | 5.33%   |
| 51-100         | 4         | 5.33%   |
| Unknown        | 2         | 2.67%   |
| 1-20           | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 32%     |
| 21-50          | 15        | 20%     |
| 101-250        | 7         | 9.33%   |
| 501-1000       | 7         | 9.33%   |
| 51-100         | 7         | 9.33%   |
| 251-500        | 6         | 8%      |
| More than 3000 | 3         | 4%      |
| 1001-2000      | 3         | 4%      |
| Unknown        | 2         | 2.67%   |
| 2001-3000      | 1         | 1.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 9.09%   |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 9.09%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 9.09%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 9.09%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 9.09%   |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 9.09%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 9.09%   |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 9.09%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 9.09%   |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 9.09%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 15     | 45.45%  |
| Hitachi | 2         | 2      | 18.18%  |
| WDC     | 1         | 4      | 9.09%   |
| Toshiba | 1         | 1      | 9.09%   |
| IBM     | 1         | 1      | 9.09%   |
| Corsair | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 15     | 50%     |
| Hitachi | 2         | 2      | 20%     |
| WDC     | 1         | 4      | 10%     |
| Toshiba | 1         | 1      | 10%     |
| IBM     | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 23     | 90%     |
| SSD  | 1         | 1      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 42        | 92     | 48.28%  |
| Detected | 34        | 54     | 39.08%  |
| Malfunc  | 10        | 24     | 11.49%  |
| Failed   | 1         | 1      | 1.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 49.5%   |
| AMD                          | 16        | 15.84%  |
| Samsung Electronics          | 8         | 7.92%   |
| LSI Logic / Symbios Logic    | 4         | 3.96%   |
| Phison Electronics           | 3         | 2.97%   |
| Kingston Technology Company  | 3         | 2.97%   |
| Broadcom / LSI               | 3         | 2.97%   |
| Realtek Semiconductor        | 2         | 1.98%   |
| ASMedia Technology           | 2         | 1.98%   |
| VIA Technologies             | 1         | 0.99%   |
| Union Memory (Shenzhen)      | 1         | 0.99%   |
| Toshiba America Info Systems | 1         | 0.99%   |
| SK hynix                     | 1         | 0.99%   |
| SanDisk                      | 1         | 0.99%   |
| Micron/Crucial Technology    | 1         | 0.99%   |
| Marvell Technology Group     | 1         | 0.99%   |
| Hewlett-Packard              | 1         | 0.99%   |
| ADATA Technology             | 1         | 0.99%   |
| Adaptec                      | 1         | 0.99%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 9.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 3.33%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.67%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2         | 1.67%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 1.67%   |
| Intel SSD 660P Series                                                                   | 2         | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.67%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 1.67%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 1.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 1.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 1.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.67%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.67%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.67%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2         | 1.67%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.67%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.83%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.83%   |
| SK hynix BC511                                                                          | 1         | 0.83%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.83%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.83%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1         | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.83%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 0.83%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 0.83%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46        | 44.23%  |
| NVMe | 27        | 25.96%  |
| IDE  | 15        | 14.42%  |
| RAID | 12        | 11.54%  |
| SAS  | 3         | 2.88%   |
| SCSI | 1         | 0.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 54        | 72%     |
| AMD    | 20        | 26.67%  |
| ARM    | 1         | 1.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Xeon CPU L5530 @ 2.40GHz              | 2         | 2.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 2.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 2.67%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 1.33%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 1         | 1.33%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 1.33%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 1.33%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 1.33%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 1.33%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1         | 1.33%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 1.33%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 1.33%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 1.33%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 1.33%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.33%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.33%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.33%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.33%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 1.33%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1.33%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.33%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 1.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.33%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.33%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.33%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 1.33%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 1.33%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 1.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.33%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.33%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.33%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1         | 1.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 24%     |
| Intel Xeon              | 11        | 14.67%  |
| Intel Core i5           | 10        | 13.33%  |
| Other                   | 6         | 8%      |
| AMD Ryzen 5             | 4         | 5.33%   |
| Intel Celeron           | 3         | 4%      |
| AMD Ryzen 9             | 3         | 4%      |
| AMD Ryzen 7             | 3         | 4%      |
| Intel Core i3           | 2         | 2.67%   |
| AMD Ryzen Threadripper  | 2         | 2.67%   |
| AMD FX                  | 2         | 2.67%   |
| Intel Xeon Silver       | 1         | 1.33%   |
| Intel Xeon Gold         | 1         | 1.33%   |
| Intel Pentium Dual-Core | 1         | 1.33%   |
| Intel Pentium Dual      | 1         | 1.33%   |
| Intel Core 2 Quad       | 1         | 1.33%   |
| Intel Core 2 Duo        | 1         | 1.33%   |
| AMD Ryzen 7 PRO         | 1         | 1.33%   |
| AMD Ryzen 5 PRO         | 1         | 1.33%   |
| AMD Ryzen 3             | 1         | 1.33%   |
| AMD Phenom II X6        | 1         | 1.33%   |
| AMD A8                  | 1         | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 27        | 36%     |
| 2      | 15        | 20%     |
| 8      | 12        | 16%     |
| 6      | 10        | 13.33%  |
| 16     | 3         | 4%      |
| 12     | 3         | 4%      |
| 32     | 1         | 1.33%   |
| 28     | 1         | 1.33%   |
| 24     | 1         | 1.33%   |
| 10     | 1         | 1.33%   |
| 3      | 1         | 1.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 67        | 89.33%  |
| 2      | 8         | 10.67%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 55        | 73.33%  |
| 1      | 20        | 26.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 75        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 10        | 13.33%  |
| 0x806ec    | 4         | 5.33%   |
| 0x506e3    | 3         | 4%      |
| 0x306a9    | 3         | 4%      |
| 0x206a7    | 3         | 4%      |
| 0xa0655    | 2         | 2.67%   |
| 0x806c1    | 2         | 2.67%   |
| 0x706a8    | 2         | 2.67%   |
| 0x40651    | 2         | 2.67%   |
| 0x306e4    | 2         | 2.67%   |
| 0x206c2    | 2         | 2.67%   |
| 0x106a5    | 2         | 2.67%   |
| 0x10676    | 2         | 2.67%   |
| 0x0a50000c | 2         | 2.67%   |
| 0x08608103 | 2         | 2.67%   |
| 0x08600106 | 2         | 2.67%   |
| 0x08600104 | 2         | 2.67%   |
| 0x06000852 | 2         | 2.67%   |
| Unknown    | 2         | 2.67%   |
| 0xa0671    | 1         | 1.33%   |
| 0xa0652    | 1         | 1.33%   |
| 0x906ed    | 1         | 1.33%   |
| 0x906ea    | 1         | 1.33%   |
| 0x906a4    | 1         | 1.33%   |
| 0x6fd      | 1         | 1.33%   |
| 0x50657    | 1         | 1.33%   |
| 0x50654    | 1         | 1.33%   |
| 0x406f1    | 1         | 1.33%   |
| 0x406e3    | 1         | 1.33%   |
| 0x306f2    | 1         | 1.33%   |
| 0x206d7    | 1         | 1.33%   |
| 0x1067a    | 1         | 1.33%   |
| 0x10677    | 1         | 1.33%   |
| 0x0a201009 | 1         | 1.33%   |
| 0x0870100a | 1         | 1.33%   |
| 0x0830104d | 1         | 1.33%   |
| 0x08301039 | 1         | 1.33%   |
| 0x08108109 | 1         | 1.33%   |
| 0x08108102 | 1         | 1.33%   |
| 0x0800820d | 1         | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 14        | 18.67%  |
| Zen 2            | 7         | 9.33%   |
| Skylake          | 6         | 8%      |
| KabyLake         | 6         | 8%      |
| IvyBridge        | 5         | 6.67%   |
| SandyBridge      | 4         | 5.33%   |
| Penryn           | 4         | 5.33%   |
| Zen+             | 3         | 4%      |
| Zen 3            | 3         | 4%      |
| Piledriver       | 3         | 4%      |
| CometLake        | 3         | 4%      |
| Unknown          | 3         | 4%      |
| Westmere         | 2         | 2.67%   |
| TigerLake        | 2         | 2.67%   |
| Nehalem          | 2         | 2.67%   |
| Goldmont plus    | 2         | 2.67%   |
| K10              | 1         | 1.33%   |
| Icelake          | 1         | 1.33%   |
| Excavator        | 1         | 1.33%   |
| Core             | 1         | 1.33%   |
| Broadwell        | 1         | 1.33%   |
| Alderlake Hybrid | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 34        | 37.36%  |
| Nvidia                     | 32        | 35.16%  |
| AMD                        | 18        | 19.78%  |
| Matrox Electronics Systems | 4         | 4.4%    |
| ASPEED Technology          | 3         | 3.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 4.35%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 3.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 3.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 3.26%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3         | 3.26%   |
| AMD Renoir                                                                  | 3         | 3.26%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 2.17%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 2.17%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.17%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.17%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 2.17%   |
| AMD Lucienne                                                                | 2         | 2.17%   |
| AMD Cezanne                                                                 | 2         | 2.17%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.09%   |
| Nvidia TU117GL [T600]                                                       | 1         | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.09%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 1.09%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 1.09%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 1.09%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 1.09%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.09%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.09%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 1.09%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 1.09%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.09%   |
| Nvidia GK107M [GeForce GT 755M]                                             | 1         | 1.09%   |
| Nvidia GK107GL [Quadro K600]                                                | 1         | 1.09%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.09%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 1.09%   |
| Nvidia GK106 [GeForce GTX 645 OEM]                                          | 1         | 1.09%   |
| Nvidia GK104GL [GRID K2]                                                    | 1         | 1.09%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1         | 1.09%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 1.09%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1         | 1.09%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 19        | 25.33%  |
| 1 x Nvidia      | 18        | 24%     |
| 1 x AMD         | 14        | 18.67%  |
| Intel + Nvidia  | 12        | 16%     |
| 1 x Matrox      | 3         | 4%      |
| 1 x ASPEED      | 3         | 4%      |
| Intel + AMD     | 2         | 2.67%   |
| Other           | 1         | 1.33%   |
| 2 x AMD         | 1         | 1.33%   |
| Nvidia + Matrox | 1         | 1.33%   |
| AMD + Nvidia    | 1         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 55        | 73.33%  |
| Proprietary | 13        | 17.33%  |
| Unknown     | 7         | 9.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 45.33%  |
| 0.01-0.5   | 13        | 17.33%  |
| 1.01-2.0   | 10        | 13.33%  |
| 3.01-4.0   | 6         | 8%      |
| 0.51-1.0   | 5         | 6.67%   |
| 5.01-6.0   | 3         | 4%      |
| 7.01-8.0   | 2         | 2.67%   |
| 32.01-64.0 | 1         | 1.33%   |
| 8.01-16.0  | 1         | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 12        | 15.38%  |
| Samsung Electronics  | 7         | 8.97%   |
| LG Display           | 7         | 8.97%   |
| Goldstar             | 7         | 8.97%   |
| AU Optronics         | 7         | 8.97%   |
| Chimei Innolux       | 6         | 7.69%   |
| Philips              | 4         | 5.13%   |
| BOE                  | 4         | 5.13%   |
| AOC                  | 4         | 5.13%   |
| Iiyama               | 3         | 3.85%   |
| ASUSTek Computer     | 2         | 2.56%   |
| Acer                 | 2         | 2.56%   |
| Vizio                | 1         | 1.28%   |
| Sony                 | 1         | 1.28%   |
| Sharp                | 1         | 1.28%   |
| PANDA                | 1         | 1.28%   |
| Panasonic            | 1         | 1.28%   |
| OEM                  | 1         | 1.28%   |
| Lenovo               | 1         | 1.28%   |
| IBM                  | 1         | 1.28%   |
| Hewlett-Packard      | 1         | 1.28%   |
| HCL                  | 1         | 1.28%   |
| Eizo                 | 1         | 1.28%   |
| Ancor Communications | 1         | 1.28%   |
| ADR                  | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 2.44%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 1.22%   |
| Sony LG TV SNY045B 1920x540                                           | 1         | 1.22%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 1.22%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch     | 1         | 1.22%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 1.22%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.22%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 1.22%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1.22%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 1.22%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.22%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 1.22%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1         | 1.22%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.22%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.22%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 1.22%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                       | 1         | 1.22%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.22%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.22%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 1         | 1.22%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1         | 1.22%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1         | 1.22%   |
| IBM RSA2 IBM029A 1024x768 300x225mm 14.8-inch                         | 1         | 1.22%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1         | 1.22%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                   | 1         | 1.22%   |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                   | 1         | 1.22%   |
| Goldstar W2252 GSM567D 1680x1050 490x320mm 23.0-inch                  | 1         | 1.22%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 1         | 1.22%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.22%   |
| Goldstar LG ULTRAWIDE GSM7770 2560x1080 800x340mm 34.2-inch           | 1         | 1.22%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 44.44%  |
| 1600x900 (HD+)     | 5         | 6.94%   |
| 1366x768 (WXGA)    | 5         | 6.94%   |
| 3840x2160 (4K)     | 4         | 5.56%   |
| 1920x1200 (WUXGA)  | 4         | 5.56%   |
| 3840x1080          | 3         | 4.17%   |
| 1280x1024 (SXGA)   | 3         | 4.17%   |
| 3440x1440          | 2         | 2.78%   |
| 2560x1440 (QHD)    | 2         | 2.78%   |
| 2560x1080          | 2         | 2.78%   |
| 1920x540           | 2         | 2.78%   |
| 1680x1050 (WSXGA+) | 2         | 2.78%   |
| 1440x900 (WXGA+)   | 2         | 2.78%   |
| Unknown            | 2         | 2.78%   |
| 1280x768           | 1         | 1.39%   |
| 1024x768 (XGA)     | 1         | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 23.08%  |
| 27      | 10        | 12.82%  |
| 14      | 9         | 11.54%  |
| 24      | 7         | 8.97%   |
| 34      | 4         | 5.13%   |
| 23      | 4         | 5.13%   |
| 21      | 4         | 5.13%   |
| 17      | 4         | 5.13%   |
| 19      | 3         | 3.85%   |
| 13      | 3         | 3.85%   |
| 31      | 2         | 2.56%   |
| Unknown | 2         | 2.56%   |
| 65      | 1         | 1.28%   |
| 49      | 1         | 1.28%   |
| 48      | 1         | 1.28%   |
| 40      | 1         | 1.28%   |
| 28      | 1         | 1.28%   |
| 22      | 1         | 1.28%   |
| 20      | 1         | 1.28%   |
| 18      | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 40.26%  |
| 501-600     | 20        | 25.97%  |
| 401-500     | 11        | 14.29%  |
| 701-800     | 4         | 5.19%   |
| 1001-1500   | 3         | 3.9%    |
| 601-700     | 2         | 2.6%    |
| 351-400     | 2         | 2.6%    |
| Unknown     | 2         | 2.6%    |
| 801-900     | 1         | 1.3%    |
| 201-300     | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 49        | 73.13%  |
| 16/10   | 6         | 8.96%   |
| 5/4     | 3         | 4.48%   |
| 21/9    | 3         | 4.48%   |
| 32/9    | 2         | 2.99%   |
| 3/2     | 2         | 2.99%   |
| 4/3     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 23.38%  |
| 201-250        | 12        | 15.58%  |
| 81-90          | 11        | 14.29%  |
| 301-350        | 10        | 12.99%  |
| 351-500        | 6         | 7.79%   |
| 151-200        | 5         | 6.49%   |
| 501-1000       | 4         | 5.19%   |
| 141-150        | 3         | 3.9%    |
| 251-300        | 2         | 2.6%    |
| 121-130        | 2         | 2.6%    |
| Unknown        | 2         | 2.6%    |
| More than 1000 | 1         | 1.3%    |
| 91-100         | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 32        | 41.56%  |
| 121-160       | 27        | 35.06%  |
| 101-120       | 10        | 12.99%  |
| 161-240       | 3         | 3.9%    |
| 1-50          | 2         | 2.6%    |
| Unknown       | 2         | 2.6%    |
| More than 240 | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 58.67%  |
| 2     | 14        | 18.67%  |
| 0     | 14        | 18.67%  |
| 3     | 2         | 2.67%   |
| 4     | 1         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 46        | 41.82%  |
| Realtek Semiconductor     | 34        | 30.91%  |
| Broadcom                  | 6         | 5.45%   |
| Qualcomm Atheros          | 5         | 4.55%   |
| Mellanox Technologies     | 3         | 2.73%   |
| MediaTek                  | 3         | 2.73%   |
| Ralink Technology         | 2         | 1.82%   |
| Marvell Technology Group  | 2         | 1.82%   |
| Linksys                   | 2         | 1.82%   |
| Solarflare Communications | 1         | 0.91%   |
| Ralink                    | 1         | 0.91%   |
| Qualcomm                  | 1         | 0.91%   |
| Microsoft                 | 1         | 0.91%   |
| BUFFALO                   | 1         | 0.91%   |
| Broadcom Limited          | 1         | 0.91%   |
| Aquantia                  | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 27        | 20.61%  |
| Intel Ethernet Connection I217-LM                                                                                      | 6         | 4.58%   |
| Intel Wireless 7260                                                                                                    | 5         | 3.82%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 5         | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 4         | 3.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 3         | 2.29%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 3         | 2.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 1.53%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 2         | 1.53%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 1.53%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 2         | 1.53%   |
| Intel Wireless 8260                                                                                                    | 2         | 1.53%   |
| Intel Wireless 3165                                                                                                    | 2         | 1.53%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 2         | 1.53%   |
| Intel I211 Gigabit Network Connection                                                                                  | 2         | 1.53%   |
| Intel Ethernet Controller I225-V                                                                                       | 2         | 1.53%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 1.53%   |
| Intel Ethernet Connection I217-V                                                                                       | 2         | 1.53%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 2         | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 2         | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 2         | 1.53%   |
| Solarflare SFC9020 10G Ethernet Controller                                                                             | 1         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 1         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                                | 1         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                             | 1         | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 1         | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 1         | 0.76%   |
| Realtek 802.11ac NIC                                                                                                   | 1         | 0.76%   |
| Ralink RT3071 Wireless Adapter                                                                                         | 1         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                              | 1         | 0.76%   |
| Qualcomm Mobile Router                                                                                                 | 1         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 1         | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 1         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                                              | 1         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                                       | 1         | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                       | 1         | 0.76%   |
| Microsoft Xbox 360 Wireless Adapter                                                                                    | 1         | 0.76%   |
| Mellanox MT27700 Family [ConnectX-4]                                                                                   | 1         | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 59.57%  |
| Realtek Semiconductor | 5         | 10.64%  |
| Qualcomm Atheros      | 4         | 8.51%   |
| MediaTek              | 3         | 6.38%   |
| Ralink Technology     | 2         | 4.26%   |
| Linksys               | 2         | 4.26%   |
| Ralink                | 1         | 2.13%   |
| Microsoft             | 1         | 2.13%   |
| BUFFALO               | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 5         | 10.2%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 10.2%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 4.08%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 4.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 4.08%   |
| Intel Wireless 8260                                            | 2         | 4.08%   |
| Intel Wireless 3165                                            | 2         | 4.08%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 4.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.04%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 2.04%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2.04%   |
| Realtek 802.11ac NIC                                           | 1         | 2.04%   |
| Ralink RT3071 Wireless Adapter                                 | 1         | 2.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 2.04%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 2.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 2.04%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1         | 2.04%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1         | 2.04%   |
| Intel Wireless 7265                                            | 1         | 2.04%   |
| Intel Wireless 3160                                            | 1         | 2.04%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.04%   |
| Intel Centrino Wireless-N 135                                  | 1         | 2.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 2.04%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]       | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 32        | 43.24%  |
| Intel                     | 29        | 39.19%  |
| Broadcom                  | 6         | 8.11%   |
| Marvell Technology Group  | 2         | 2.7%    |
| Solarflare Communications | 1         | 1.35%   |
| Qualcomm Atheros          | 1         | 1.35%   |
| Qualcomm                  | 1         | 1.35%   |
| Broadcom Limited          | 1         | 1.35%   |
| Aquantia                  | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 34.18%  |
| Intel Ethernet Connection I217-LM                                 | 6         | 7.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.8%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 3.8%    |
| Intel I211 Gigabit Network Connection                             | 2         | 2.53%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.53%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 2.53%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.53%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 1.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.27%   |
| Qualcomm Mobile Router                                            | 1         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.27%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.27%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.27%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.27%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.27%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 1.27%   |
| Intel Ethernet Controller X550                                    | 1         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.27%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.27%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.27%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 1.27%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 1.27%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 1.27%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.27%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.27%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 1         | 1.27%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet      | 1         | 1.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 59.48%  |
| WiFi     | 44        | 37.93%  |
| Unknown  | 3         | 2.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 64%     |
| WiFi     | 26        | 34.67%  |
| Unknown  | 1         | 1.33%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 45.33%  |
| 1     | 29        | 38.67%  |
| 3     | 4         | 5.33%   |
| 5     | 3         | 4%      |
| 0     | 2         | 2.67%   |
| 66    | 1         | 1.33%   |
| 8     | 1         | 1.33%   |
| 4     | 1         | 1.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 81.33%  |
| Yes  | 14        | 18.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 63.16%  |
| Realtek Semiconductor           | 2         | 5.26%   |
| MediaTek                        | 2         | 5.26%   |
| Foxconn / Hon Hai               | 2         | 5.26%   |
| Cambridge Silicon Radio         | 2         | 5.26%   |
| Broadcom                        | 2         | 5.26%   |
| Ralink                          | 1         | 2.63%   |
| Qualcomm Atheros Communications | 1         | 2.63%   |
| Integrated System Solution      | 1         | 2.63%   |
| IMC Networks                    | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 12        | 31.58%  |
| Intel AX200 Bluetooth                                 | 5         | 13.16%  |
| Intel AX201 Bluetooth                                 | 4         | 10.53%  |
| MediaTek Wireless_Device                              | 2         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 5.26%   |
| Foxconn / Hon Hai Wireless_Device                     | 2         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 2.63%   |
| Realtek Bluetooth Radio                               | 1         | 2.63%   |
| Ralink RT3290 Bluetooth                               | 1         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                    | 1         | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 2.63%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 2.63%   |
| IMC Networks Bluetooth Device                         | 1         | 2.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 45        | 43.69%  |
| Nvidia              | 24        | 23.3%   |
| AMD                 | 21        | 20.39%  |
| C-Media Electronics | 4         | 3.88%   |
| Logitech            | 2         | 1.94%   |
| Unknown             | 1         | 0.97%   |
| Nektar              | 1         | 0.97%   |
| Hewlett-Packard     | 1         | 0.97%   |
| GN Netcom           | 1         | 0.97%   |
| Creative Technology | 1         | 0.97%   |
| Conexant Systems    | 1         | 0.97%   |
| ASUSTek Computer    | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 7.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 7.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.97%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 3.17%   |
| Nvidia GK106 HDMI Audio Controller                                         | 4         | 3.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.59%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.59%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.59%   |
| C-Media Electronics Anua Mic CM 900                                        | 2         | 1.59%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.59%   |
| Unknown Realtek USB Audio Rear                                             | 1         | 0.79%   |
| Unknown Realtek USB Audio Front                                            | 1         | 0.79%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.79%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.79%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.79%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.79%   |
| Nektar Impact GX61                                                         | 1         | 0.79%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 12        | 25%     |
| Samsung Electronics | 11        | 22.92%  |
| Kingston            | 5         | 10.42%  |
| Unknown             | 4         | 8.33%   |
| G.Skill             | 4         | 8.33%   |
| SK hynix            | 3         | 6.25%   |
| Corsair             | 3         | 6.25%   |
| Crucial             | 2         | 4.17%   |
| Unknown (ABCD)      | 1         | 2.08%   |
| Patriot             | 1         | 2.08%   |
| Magnum Tech         | 1         | 2.08%   |
| A-DATA Technology   | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                             | 1         | 2%      |
| Unknown RAM Module 2GB DIMM 667MT/s                                   | 1         | 2%      |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 2%      |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                              | 1         | 2%      |
| Unknown RAM Module 1GB DIMM 667MT/s                                   | 1         | 2%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s      | 1         | 2%      |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                  | 1         | 2%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                | 1         | 2%      |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s            | 1         | 2%      |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 2%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 2%      |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                | 1         | 2%      |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                 | 1         | 2%      |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s                  | 1         | 2%      |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 2%      |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 2%      |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 2%      |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                   | 1         | 2%      |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 2%      |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s                  | 1         | 2%      |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s                      | 1         | 2%      |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s         | 1         | 2%      |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                              | 1         | 2%      |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                   | 1         | 2%      |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                  | 1         | 2%      |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                    | 1         | 2%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s            | 1         | 2%      |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s                  | 1         | 2%      |
| Micron RAM 36ASF4G72PZ-2G3D1 32GB DIMM DDR4 2400MT/s                  | 1         | 2%      |
| Micron RAM 3138485446313238373241592D3636374631 1GB DIMM DDR2 667MT/s | 1         | 2%      |
| Micron RAM 18ASF2G72AZ-2G3A1 16GB DIMM DDR4 2400MT/s                  | 1         | 2%      |
| Micron RAM 18ASF1G72PDZ-2G6F1 8GB DIMM DDR4 2666MT/s                  | 1         | 2%      |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s                 | 1         | 2%      |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s                   | 1         | 2%      |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s                   | 1         | 2%      |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s               | 1         | 2%      |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 2%      |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 2%      |
| Kingston RAM 9905417-062.A00G 4GB SODIMM DDR3 1600MT/s                | 1         | 2%      |
| Kingston RAM 9905402-670.A00LF 4GB DIMM DDR3 1333MT/s                 | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 23        | 51.11%  |
| DDR3    | 16        | 35.56%  |
| LPDDR4  | 3         | 6.67%   |
| DDR2    | 2         | 4.44%   |
| Unknown | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 28        | 62.22%  |
| SODIMM       | 14        | 31.11%  |
| Row Of Chips | 2         | 4.44%   |
| RIMM         | 1         | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 41.67%  |
| 16384 | 8         | 16.67%  |
| 32768 | 6         | 12.5%   |
| 4096  | 6         | 12.5%   |
| 1024  | 5         | 10.42%  |
| 2048  | 3         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 10        | 21.74%  |
| 1600  | 7         | 15.22%  |
| 2667  | 5         | 10.87%  |
| 2400  | 5         | 10.87%  |
| 667   | 3         | 6.52%   |
| 3600  | 2         | 4.35%   |
| 2666  | 2         | 4.35%   |
| 2133  | 2         | 4.35%   |
| 1333  | 2         | 4.35%   |
| 1066  | 2         | 4.35%   |
| 4267  | 1         | 2.17%   |
| 4266  | 1         | 2.17%   |
| 3400  | 1         | 2.17%   |
| 2200  | 1         | 2.17%   |
| 1866  | 1         | 2.17%   |
| 1800  | 1         | 2.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 66.67%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series    | 1         | 33.33%  |
| Seiko Epson Printer           | 1         | 33.33%  |
| Brother HL-2030 Laser Printer | 1         | 33.33%  |

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
| Chicony Electronics                    | 6         | 16.67%  |
| Syntek                                 | 4         | 11.11%  |
| Logitech                               | 3         | 8.33%   |
| IMC Networks                           | 3         | 8.33%   |
| Realtek Semiconductor                  | 2         | 5.56%   |
| Microdia                               | 2         | 5.56%   |
| Luxvisions Innotech Limited            | 2         | 5.56%   |
| Generalplus Technology                 | 2         | 5.56%   |
| Suyin                                  | 1         | 2.78%   |
| Sunplus Innovation Technology          | 1         | 2.78%   |
| Quanta                                 | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| Lenovo                                 | 1         | 2.78%   |
| Intel                                  | 1         | 2.78%   |
| Huawei Technologies                    | 1         | 2.78%   |
| Elgato Systems                         | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |
| Apple                                  | 1         | 2.78%   |
| Acer                                   | 1         | 2.78%   |
| 2M UVC CAMERA                          | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 11.11%  |
| Syntek Lenovo EasyCamera                                                   | 2         | 5.56%   |
| Syntek Integrated Camera                                                   | 2         | 5.56%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 5.56%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 5.56%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 5.56%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.78%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 2.78%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.78%   |
| Realtek EasyCamera                                                         | 1         | 2.78%   |
| Quanta HP Webcam                                                           | 1         | 2.78%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 2.78%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 2.78%   |
| Logitech Webcam C270                                                       | 1         | 2.78%   |
| Logitech HD Pro Webcam C920                                                | 1         | 2.78%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 2.78%   |
| Lite-On HP HD Webcam                                                       | 1         | 2.78%   |
| Lenovo UVC Camera                                                          | 1         | 2.78%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 2.78%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 2.78%   |
| Huawei HiCamera                                                            | 1         | 2.78%   |
| Elgato Systems Elgato Facecam                                              | 1         | 2.78%   |
| Chicony HP HD Camera                                                       | 1         | 2.78%   |
| Chicony HD WebCam                                                          | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 2.78%   |
| Acer Integrated Camera                                                     | 1         | 2.78%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam                                        | 1         | 2.78%   |

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
| LighTuning EgisTec_ES603                                   | 1         | 9.09%   |
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
| 0     | 37        | 49.33%  |
| 1     | 26        | 34.67%  |
| 2     | 9         | 12%     |
| 5     | 1         | 1.33%   |
| 4     | 1         | 1.33%   |
| 3     | 1         | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 22%     |
| Net/wireless             | 9         | 18%     |
| Graphics card            | 8         | 16%     |
| Unassigned class         | 4         | 8%      |
| Communication controller | 4         | 8%      |
| Network                  | 2         | 4%      |
| Net/ethernet             | 2         | 4%      |
| Multimedia controller    | 2         | 4%      |
| Chipcard                 | 2         | 4%      |
| Storage/raid             | 1         | 2%      |
| Storage                  | 1         | 2%      |
| Sound                    | 1         | 2%      |
| Firewire controller      | 1         | 2%      |
| Card reader              | 1         | 2%      |
| Bluetooth                | 1         | 2%      |

