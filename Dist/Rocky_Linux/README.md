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

Total: 107

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 2560p             | Notebook    | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Dell          | Inspiron 14 5425            | Notebook    | [42f45d59d2](https://linux-hardware.org/?probe=42f45d59d2) | Dec 29, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| HP            | 805D                        | Desktop     | [cf88e571df](https://linux-hardware.org/?probe=cf88e571df) | Dec 28, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| HP            | ProBook 640 G3              | Notebook    | [03eba7b664](https://linux-hardware.org/?probe=03eba7b664) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [ede2606ad1](https://linux-hardware.org/?probe=ede2606ad1) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Intel         | D33217GKE G69901-202        | Desktop     | [f10d00e42a](https://linux-hardware.org/?probe=f10d00e42a) | Nov 12, 2022 |
| HP            | 8054                        | Desktop     | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| HP            | 8054                        | Desktop     | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | Desktop     | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
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
| Rocky Linux 8.5 | 31        | 33.7%   |
| Rocky Linux 9.0 | 19        | 20.65%  |
| Rocky Linux 8.4 | 19        | 20.65%  |
| Rocky Linux 8.6 | 11        | 11.96%  |
| Rocky Linux 9.1 | 8         | 8.7%    |
| Rocky Linux 8.7 | 2         | 2.17%   |
| Rocky Linux 8.3 | 2         | 2.17%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 91        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 14.13%  |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 8.7%    |
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 6         | 6.52%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 6.52%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 5         | 5.43%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 5.43%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 4         | 4.35%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 4.35%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 4.35%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 3.26%   |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 2.17%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 2.17%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 2         | 2.17%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 2.17%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 2.17%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 2.17%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 2.17%   |
| 4.18.0-305.el8.x86_64            | 2         | 2.17%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 2.17%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 2.17%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 2.17%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 2.17%   |
| 6.0.10_tkg_bmq                   | 1         | 1.09%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1         | 1.09%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.09%   |
| 5.16.15-1.el8.elrepo.x86_64      | 1         | 1.09%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1         | 1.09%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.09%   |
| 5.10.89-1.el8.x86_64             | 1         | 1.09%   |
| 5.10.52-v8.1.el8                 | 1         | 1.09%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.09%   |
| 4.18.0-348.23.1.el8_5.x86_64     | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 59        | 64.84%  |
| 5.14.0  | 25        | 27.47%  |
| 6.0.10  | 2         | 2.2%    |
| 5.4.157 | 1         | 1.1%    |
| 5.16.15 | 1         | 1.1%    |
| 5.14.1  | 1         | 1.1%    |
| 5.10.89 | 1         | 1.1%    |
| 5.10.52 | 1         | 1.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 59        | 64.84%  |
| 5.14    | 26        | 28.57%  |
| 6.0     | 2         | 2.2%    |
| 5.10    | 2         | 2.2%    |
| 5.4     | 1         | 1.1%    |
| 5.16    | 1         | 1.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 90        | 98.9%   |
| aarch64 | 1         | 1.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 66        | 72.53%  |
| Unknown       | 9         | 9.89%   |
| MATE          | 5         | 5.49%   |
| KDE5          | 4         | 4.4%    |
| XFCE          | 3         | 3.3%    |
| GNOME Classic | 3         | 3.3%    |
| X-Cinnamon    | 1         | 1.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 53        | 58.24%  |
| X11     | 31        | 34.07%  |
| Unknown | 5         | 5.49%   |
| Web     | 2         | 2.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 48.35%  |
| GDM     | 40        | 43.96%  |
| SDDM    | 4         | 4.4%    |
| LightDM | 3         | 3.3%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 60        | 65.93%  |
| en_AU   | 5         | 5.49%   |
| ru_RU   | 4         | 4.4%    |
| en_IL   | 3         | 3.3%    |
| en_CA   | 3         | 3.3%    |
| en_ZA   | 2         | 2.2%    |
| en_SG   | 2         | 2.2%    |
| de_DE   | 2         | 2.2%    |
| pt_BR   | 1         | 1.1%    |
| pl_PL   | 1         | 1.1%    |
| ja_JP   | 1         | 1.1%    |
| it_IT   | 1         | 1.1%    |
| hu_HU   | 1         | 1.1%    |
| es_CO   | 1         | 1.1%    |
| es_AR   | 1         | 1.1%    |
| C       | 1         | 1.1%    |
| af_ZA   | 1         | 1.1%    |
| Unknown | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 54        | 59.34%  |
| BIOS | 37        | 40.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 75        | 82.42%  |
| Ext4 | 15        | 16.48%  |
| Ext3 | 1         | 1.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 39        | 42.86%  |
| Unknown | 35        | 38.46%  |
| MBR     | 17        | 18.68%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 83.52%  |
| Yes       | 15        | 16.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 87.91%  |
| Yes       | 11        | 12.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 18        | 19.78%  |
| Lenovo                  | 17        | 18.68%  |
| ASUSTek Computer        | 17        | 18.68%  |
| Hewlett-Packard         | 12        | 13.19%  |
| Gigabyte Technology     | 5         | 5.49%   |
| MSI                     | 4         | 4.4%    |
| Toshiba                 | 2         | 2.2%    |
| Supermicro              | 2         | 2.2%    |
| Intel                   | 2         | 2.2%    |
| AZW                     | 2         | 2.2%    |
| Unknown                 | 2         | 2.2%    |
| Raspberry Pi Foundation | 1         | 1.1%    |
| NCR                     | 1         | 1.1%    |
| IBM                     | 1         | 1.1%    |
| Google                  | 1         | 1.1%    |
| BESSTAR Tech            | 1         | 1.1%    |
| BANGHO                  | 1         | 1.1%    |
| ASRock                  | 1         | 1.1%    |
| Acer                    | 1         | 1.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Dell PowerEdge R610                    | 2         | 2.2%    |
| Dell OptiPlex 9020                     | 2         | 2.2%    |
| Unknown                                | 2         | 2.2%    |
| Toshiba TECRA W50-A                    | 1         | 1.1%    |
| Toshiba Satellite E45-B                | 1         | 1.1%    |
| Supermicro SYS-5029P-WTR               | 1         | 1.1%    |
| Supermicro Super Server                | 1         | 1.1%    |
| RPi Raspberry Pi                       | 1         | 1.1%    |
| NCR xxxx-xxxx-xxxx                     | 1         | 1.1%    |
| MSI MS-7D46                            | 1         | 1.1%    |
| MSI MS-7B89                            | 1         | 1.1%    |
| MSI MS-7A94                            | 1         | 1.1%    |
| MSI MS-7917                            | 1         | 1.1%    |
| Lenovo ThinkStation P620 30E0S0PR00    | 1         | 1.1%    |
| Lenovo ThinkPad X1 Carbon 344835U      | 1         | 1.1%    |
| Lenovo ThinkPad W540 20BGCTO1WW        | 1         | 1.1%    |
| Lenovo ThinkPad W500 406132G           | 1         | 1.1%    |
| Lenovo ThinkPad T420 42365H1           | 1         | 1.1%    |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS  | 1         | 1.1%    |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK | 1         | 1.1%    |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW    | 1         | 1.1%    |
| Lenovo ThinkCentre M72e 36601Y8        | 1         | 1.1%    |
| Lenovo Legion Y7000 2020H 81Y7         | 1         | 1.1%    |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 1.1%    |
| Lenovo IdeaPadFlex 5 14ALC7 82R9       | 1         | 1.1%    |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 1.1%    |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 1.1%    |
| Lenovo IdeaPad Y410P 20216             | 1         | 1.1%    |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 1         | 1.1%    |
| Lenovo IdeaPad 500S-14ISK 80Q3         | 1         | 1.1%    |
| Intel S2600WFT                         | 1         | 1.1%    |
| Intel PRO412081                        | 1         | 1.1%    |
| IBM System x3200 M2 -[4368IGS]-        | 1         | 1.1%    |
| HP ZBook 15u G6                        | 1         | 1.1%    |
| HP ZBook 15 G3                         | 1         | 1.1%    |
| HP ZBook 15 G2                         | 1         | 1.1%    |
| HP Z600 Workstation                    | 1         | 1.1%    |
| HP ProLiant DL380 G7                   | 1         | 1.1%    |
| HP ProDesk 600 G2 SFF                  | 1         | 1.1%    |
| HP ProBook 640 G3                      | 1         | 1.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUS PRIME               | 8         | 8.79%   |
| Lenovo ThinkPad          | 7         | 7.69%   |
| Lenovo IdeaPad           | 4         | 4.4%    |
| Dell PowerEdge           | 4         | 4.4%    |
| Dell OptiPlex            | 4         | 4.4%    |
| HP ZBook                 | 3         | 3.3%    |
| Dell Precision           | 3         | 3.3%    |
| Dell Latitude            | 3         | 3.3%    |
| Lenovo Legion            | 2         | 2.2%    |
| Lenovo IdeaPadFlex       | 2         | 2.2%    |
| HP EliteBook             | 2         | 2.2%    |
| Dell Vostro              | 2         | 2.2%    |
| ASUS ASUS                | 2         | 2.2%    |
| Unknown                  | 2         | 2.2%    |
| Toshiba TECRA            | 1         | 1.1%    |
| Toshiba Satellite        | 1         | 1.1%    |
| Supermicro SYS-5029P-WTR | 1         | 1.1%    |
| Supermicro Super         | 1         | 1.1%    |
| RPi Raspberry            | 1         | 1.1%    |
| NCR xxxx-xxxx-xxxx       | 1         | 1.1%    |
| MSI MS-7D46              | 1         | 1.1%    |
| MSI MS-7B89              | 1         | 1.1%    |
| MSI MS-7A94              | 1         | 1.1%    |
| MSI MS-7917              | 1         | 1.1%    |
| Lenovo ThinkStation      | 1         | 1.1%    |
| Lenovo ThinkCentre       | 1         | 1.1%    |
| Intel S2600WFT           | 1         | 1.1%    |
| Intel PRO412081          | 1         | 1.1%    |
| IBM System               | 1         | 1.1%    |
| HP Z600                  | 1         | 1.1%    |
| HP ProLiant              | 1         | 1.1%    |
| HP ProDesk               | 1         | 1.1%    |
| HP ProBook               | 1         | 1.1%    |
| HP Pavilion              | 1         | 1.1%    |
| HP Laptop                | 1         | 1.1%    |
| HP EliteDesk             | 1         | 1.1%    |
| Google Panther           | 1         | 1.1%    |
| Gigabyte X570            | 1         | 1.1%    |
| Gigabyte H87-D3H         | 1         | 1.1%    |
| Gigabyte H81M-S2PV       | 1         | 1.1%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 13        | 14.29%  |
| 2020    | 11        | 12.09%  |
| 2019    | 10        | 10.99%  |
| 2018    | 8         | 8.79%   |
| 2014    | 8         | 8.79%   |
| 2015    | 7         | 7.69%   |
| 2011    | 7         | 7.69%   |
| 2013    | 6         | 6.59%   |
| 2022    | 5         | 5.49%   |
| 2012    | 4         | 4.4%    |
| 2010    | 3         | 3.3%    |
| 2017    | 2         | 2.2%    |
| 2016    | 2         | 2.2%    |
| 2009    | 2         | 2.2%    |
| 2008    | 2         | 2.2%    |
| Unknown | 1         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 43        | 47.25%  |
| Notebook       | 34        | 37.36%  |
| Server         | 9         | 9.89%   |
| Convertible    | 2         | 2.2%    |
| System on chip | 1         | 1.1%    |
| Tablet         | 1         | 1.1%    |
| Mini pc        | 1         | 1.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 85        | 93.41%  |
| Enabled  | 6         | 6.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 90        | 98.9%   |
| Yes  | 1         | 1.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 23        | 25.27%  |
| 32.01-64.0      | 18        | 19.78%  |
| 4.01-8.0        | 16        | 17.58%  |
| 16.01-24.0      | 13        | 14.29%  |
| 64.01-256.0     | 6         | 6.59%   |
| 3.01-4.0        | 5         | 5.49%   |
| More than 256.0 | 3         | 3.3%    |
| 1.01-2.0        | 3         | 3.3%    |
| 24.01-32.0      | 2         | 2.2%    |
| 2.01-3.0        | 2         | 2.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 23        | 25%     |
| 4.01-8.0   | 21        | 22.83%  |
| 3.01-4.0   | 20        | 21.74%  |
| 1.01-2.0   | 16        | 17.39%  |
| 8.01-16.0  | 6         | 6.52%   |
| 0.51-1.0   | 3         | 3.26%   |
| 16.01-24.0 | 2         | 2.17%   |
| 0.01-0.5   | 1         | 1.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 53.85%  |
| 2      | 19        | 20.88%  |
| 3      | 11        | 12.09%  |
| 4      | 5         | 5.49%   |
| 5      | 2         | 2.2%    |
| 18     | 1         | 1.1%    |
| 16     | 1         | 1.1%    |
| 14     | 1         | 1.1%    |
| 9      | 1         | 1.1%    |
| 8      | 1         | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 65.93%  |
| Yes       | 31        | 34.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 92.31%  |
| No        | 7         | 7.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 57.14%  |
| No        | 39        | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 50.55%  |
| Yes       | 45        | 49.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 21        | 23.08%  |
| Australia    | 6         | 6.59%   |
| Canada       | 5         | 5.49%   |
| Russia       | 4         | 4.4%    |
| Germany      | 4         | 4.4%    |
| Czechia      | 4         | 4.4%    |
| South Africa | 3         | 3.3%    |
| Singapore    | 3         | 3.3%    |
| Italy        | 3         | 3.3%    |
| Israel       | 3         | 3.3%    |
| Sweden       | 2         | 2.2%    |
| Poland       | 2         | 2.2%    |
| Netherlands  | 2         | 2.2%    |
| Mexico       | 2         | 2.2%    |
| Indonesia    | 2         | 2.2%    |
| India        | 2         | 2.2%    |
| Belgium      | 2         | 2.2%    |
| Argentina    | 2         | 2.2%    |
| UK           | 1         | 1.1%    |
| UAE          | 1         | 1.1%    |
| Turkey       | 1         | 1.1%    |
| Switzerland  | 1         | 1.1%    |
| South Korea  | 1         | 1.1%    |
| Slovakia     | 1         | 1.1%    |
| Portugal     | 1         | 1.1%    |
| Pakistan     | 1         | 1.1%    |
| Norway       | 1         | 1.1%    |
| Malaysia     | 1         | 1.1%    |
| Kazakhstan   | 1         | 1.1%    |
| Japan        | 1         | 1.1%    |
| Hungary      | 1         | 1.1%    |
| France       | 1         | 1.1%    |
| Finland      | 1         | 1.1%    |
| Colombia     | 1         | 1.1%    |
| China        | 1         | 1.1%    |
| Brazil       | 1         | 1.1%    |
| Austria      | 1         | 1.1%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 3.3%    |
| Melbourne              | 3         | 3.3%    |
| Toronto                | 2         | 2.2%    |
| Prague                 | 2         | 2.2%    |
| Moscow                 | 2         | 2.2%    |
| Haifa                  | 2         | 2.2%    |
| Centurion              | 2         | 2.2%    |
| Berlin                 | 2         | 2.2%    |
| Adelaide               | 2         | 2.2%    |
| Žilina                | 1         | 1.1%    |
| Yogyakarta             | 1         | 1.1%    |
| Xi'an                  | 1         | 1.1%    |
| Wells                  | 1         | 1.1%    |
| Waltham                | 1         | 1.1%    |
| Vienna                 | 1         | 1.1%    |
| Tlaxcala City          | 1         | 1.1%    |
| Syracuse               | 1         | 1.1%    |
| St. John's             | 1         | 1.1%    |
| St Petersburg          | 1         | 1.1%    |
| Sobral de Monte Agraco | 1         | 1.1%    |
| Smolensk               | 1         | 1.1%    |
| Senigallia             | 1         | 1.1%    |
| Semarang               | 1         | 1.1%    |
| Scarborough            | 1         | 1.1%    |
| San Miguel de Tucumán | 1         | 1.1%    |
| Rotterdam              | 1         | 1.1%    |
| Rehovot                | 1         | 1.1%    |
| Rawalpindi             | 1         | 1.1%    |
| Progresista            | 1         | 1.1%    |
| Philadelphia           | 1         | 1.1%    |
| Paris                  | 1         | 1.1%    |
| Ottignies              | 1         | 1.1%    |
| Ōtsu                  | 1         | 1.1%    |
| Oslo                   | 1         | 1.1%    |
| Örebro                | 1         | 1.1%    |
| Oklahoma City          | 1         | 1.1%    |
| Oakley                 | 1         | 1.1%    |
| Nur-Sultan             | 1         | 1.1%    |
| New York               | 1         | 1.1%    |
| Mugla                  | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 25        | 33     | 18.12%  |
| Seagate                 | 23        | 54     | 16.67%  |
| WDC                     | 19        | 40     | 13.77%  |
| Toshiba                 | 13        | 14     | 9.42%   |
| Intel                   | 7         | 9      | 5.07%   |
| Kingston                | 6         | 6      | 4.35%   |
| Unknown                 | 4         | 4      | 2.9%    |
| Hitachi                 | 4         | 5      | 2.9%    |
| SK hynix                | 3         | 4      | 2.17%   |
| SanDisk                 | 3         | 3      | 2.17%   |
| Crucial                 | 3         | 3      | 2.17%   |
| Phison                  | 2         | 2      | 1.45%   |
| LITEONIT                | 2         | 2      | 1.45%   |
| HGST                    | 2         | 2      | 1.45%   |
| Corsair                 | 2         | 2      | 1.45%   |
| A-DATA Technology       | 2         | 2      | 1.45%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.72%   |
| UMIS                    | 1         | 1      | 0.72%   |
| Team                    | 1         | 1      | 0.72%   |
| StoreJet                | 1         | 1      | 0.72%   |
| PNY                     | 1         | 1      | 0.72%   |
| MyDigitalSSD            | 1         | 1      | 0.72%   |
| LITEON                  | 1         | 1      | 0.72%   |
| Lexar                   | 1         | 1      | 0.72%   |
| IBM                     | 1         | 1      | 0.72%   |
| HS-SSD-C100             | 1         | 1      | 0.72%   |
| Gigabyte Technology     | 1         | 1      | 0.72%   |
| Fujitsu                 | 1         | 1      | 0.72%   |
| Dogfish                 | 1         | 1      | 0.72%   |
| China                   | 1         | 1      | 0.72%   |
| Apacer                  | 1         | 1      | 0.72%   |
| AGI                     | 1         | 1      | 0.72%   |
| ADATA Technology        | 1         | 1      | 0.72%   |
| ADATA SU                | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 3         | 1.85%   |
| Unknown MMC Card  64GB               | 2         | 1.23%   |
| Seagate ST9320325AS 320GB            | 2         | 1.23%   |
| Seagate ST300MP0005 304GB            | 2         | 1.23%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 1.23%   |
| Samsung SSD 870 EVO 1TB              | 2         | 1.23%   |
| Samsung SSD 860 EVO 1TB              | 2         | 1.23%   |
| A-DATA SWORDFISH 1TB                 | 2         | 1.23%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD     | 1         | 0.62%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.62%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD     | 1         | 0.62%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.62%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.62%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD       | 1         | 0.62%   |
| WDC WD80EZZX-11CSGA0 8TB             | 1         | 0.62%   |
| WDC WD80EMAZ-00WJTA0 8TB             | 1         | 0.62%   |
| WDC WD80EDAZ-11TA3A0 8TB             | 1         | 0.62%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.62%   |
| WDC WD5000BPVT-00A1YT0 500GB         | 1         | 0.62%   |
| WDC WD5000AUDX-63WNHY0 500GB         | 1         | 0.62%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 0.62%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 0.62%   |
| WDC WD30EZRX-00D8PB0 3TB             | 1         | 0.62%   |
| WDC WD2500AAJS-22VTA0 250GB          | 1         | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.62%   |
| WDC WD20EZRX-00DC0B0 2TB             | 1         | 0.62%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1         | 0.62%   |
| WDC WD20EFZX-68AWUN0 2TB             | 1         | 0.62%   |
| WDC WD2002FAEX-007BA0 2TB            | 1         | 0.62%   |
| WDC WD120EDAZ-11F3RA0 12TB           | 1         | 0.62%   |
| WDC WD10SPCX-24HWST1 1TB             | 1         | 0.62%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.62%   |
| WDC WD10EZEX-75M2NA0 1TB             | 1         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.62%   |
| WDC WD100EMAZ-00WJTA0 10TB           | 1         | 0.62%   |
| WDC WD1001FALS-00J7B0 1TB            | 1         | 0.62%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.62%   |
| Unknown SD/MMC/MS PRO 64GB           | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 54     | 41.07%  |
| WDC                 | 14        | 29     | 25%     |
| Toshiba             | 7         | 7      | 12.5%   |
| Hitachi             | 4         | 5      | 7.14%   |
| Samsung Electronics | 2         | 3      | 3.57%   |
| HGST                | 2         | 2      | 3.57%   |
| Unknown             | 1         | 1      | 1.79%   |
| StoreJet            | 1         | 1      | 1.79%   |
| IBM                 | 1         | 1      | 1.79%   |
| Fujitsu             | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 14     | 24.44%  |
| WDC                 | 5         | 8      | 11.11%  |
| Toshiba             | 4         | 4      | 8.89%   |
| SanDisk             | 3         | 3      | 6.67%   |
| Kingston            | 3         | 3      | 6.67%   |
| SK hynix            | 2         | 2      | 4.44%   |
| LITEONIT            | 2         | 2      | 4.44%   |
| Intel               | 2         | 3      | 4.44%   |
| Crucial             | 2         | 2      | 4.44%   |
| Team                | 1         | 1      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| MyDigitalSSD        | 1         | 1      | 2.22%   |
| LITEON              | 1         | 1      | 2.22%   |
| Lexar               | 1         | 1      | 2.22%   |
| Gigabyte Technology | 1         | 1      | 2.22%   |
| Dogfish             | 1         | 1      | 2.22%   |
| Corsair             | 1         | 1      | 2.22%   |
| China               | 1         | 1      | 2.22%   |
| Apacer              | 1         | 1      | 2.22%   |
| ADATA SU            | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 41        | 104    | 34.45%  |
| SSD     | 39        | 52     | 32.77%  |
| NVMe    | 34        | 42     | 28.57%  |
| MMC     | 3         | 3      | 2.52%   |
| Unknown | 2         | 2      | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 65        | 151    | 59.63%  |
| NVMe | 34        | 42     | 31.19%  |
| SAS  | 7         | 7      | 6.42%   |
| MMC  | 3         | 3      | 2.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 66     | 47.19%  |
| 0.51-1.0   | 25        | 34     | 28.09%  |
| 1.01-2.0   | 11        | 17     | 12.36%  |
| 3.01-4.0   | 7         | 23     | 7.87%   |
| 10.01-20.0 | 2         | 3      | 2.25%   |
| 2.01-3.0   | 1         | 1      | 1.12%   |
| 4.01-10.0  | 1         | 12     | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 24.18%  |
| 251-500        | 21        | 23.08%  |
| 501-1000       | 17        | 18.68%  |
| 1001-2000      | 10        | 10.99%  |
| More than 3000 | 8         | 8.79%   |
| 2001-3000      | 5         | 5.49%   |
| 51-100         | 5         | 5.49%   |
| Unknown        | 2         | 2.2%    |
| 1-20           | 1         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 30        | 32.97%  |
| 21-50          | 18        | 19.78%  |
| 51-100         | 11        | 12.09%  |
| 101-250        | 8         | 8.79%   |
| 251-500        | 7         | 7.69%   |
| 501-1000       | 7         | 7.69%   |
| More than 3000 | 4         | 4.4%    |
| 1001-2000      | 3         | 3.3%    |
| Unknown        | 2         | 2.2%    |
| 2001-3000      | 1         | 1.1%    |

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
| Works    | 54        | 116    | 51.92%  |
| Detected | 39        | 62     | 37.5%   |
| Malfunc  | 10        | 24     | 9.62%   |
| Failed   | 1         | 1      | 0.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 62        | 50.82%  |
| AMD                          | 19        | 15.57%  |
| Samsung Electronics          | 12        | 9.84%   |
| LSI Logic / Symbios Logic    | 4         | 3.28%   |
| Phison Electronics           | 3         | 2.46%   |
| Kingston Technology Company  | 3         | 2.46%   |
| Broadcom / LSI               | 3         | 2.46%   |
| Toshiba America Info Systems | 2         | 1.64%   |
| SanDisk                      | 2         | 1.64%   |
| Realtek Semiconductor        | 2         | 1.64%   |
| ASMedia Technology           | 2         | 1.64%   |
| VIA Technologies             | 1         | 0.82%   |
| Union Memory (Shenzhen)      | 1         | 0.82%   |
| SK hynix                     | 1         | 0.82%   |
| Micron/Crucial Technology    | 1         | 0.82%   |
| Marvell Technology Group     | 1         | 0.82%   |
| Hewlett-Packard              | 1         | 0.82%   |
| ADATA Technology             | 1         | 0.82%   |
| Adaptec                      | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13        | 9.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 4.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 3.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 3.5%    |
| Intel SATA Controller [RAID mode]                                                       | 4         | 2.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 2.1%    |
| Samsung NVMe SSD Controller 980                                                         | 3         | 2.1%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 1.4%    |
| Realtek Realtek Non-Volatile memory controller                                          | 2         | 1.4%    |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.4%    |
| Intel SSD 660P Series                                                                   | 2         | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.4%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 1.4%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 1.4%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 1.4%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.4%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.4%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 1.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.4%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.4%    |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2         | 1.4%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.4%    |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.7%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.7%    |
| SK hynix BC511                                                                          | 1         | 0.7%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 0.7%    |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 60        | 47.62%  |
| NVMe | 34        | 26.98%  |
| IDE  | 15        | 11.9%   |
| RAID | 13        | 10.32%  |
| SAS  | 3         | 2.38%   |
| SCSI | 1         | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 73.63%  |
| AMD    | 23        | 25.27%  |
| ARM    | 1         | 1.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Xeon CPU L5530 @ 2.40GHz              | 2         | 2.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 2.2%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 2.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 2.2%    |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 1.1%    |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 1         | 1.1%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 1.1%    |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 1.1%    |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 1.1%    |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 1.1%    |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1         | 1.1%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 1.1%    |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 1.1%    |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 1.1%    |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 1.1%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.1%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.1%    |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 1.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.1%    |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.1%    |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1         | 1.1%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 1.1%    |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.1%    |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 1.1%    |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1.1%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.1%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 1.1%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.1%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.1%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.1%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.1%    |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.1%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.1%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 1.1%    |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 1.1%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 1.1%    |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.1%    |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1         | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 21        | 23.08%  |
| Intel Core i5           | 14        | 15.38%  |
| Intel Xeon              | 11        | 12.09%  |
| Other                   | 9         | 9.89%   |
| AMD Ryzen 5             | 6         | 6.59%   |
| Intel Core i3           | 4         | 4.4%    |
| AMD Ryzen 7             | 4         | 4.4%    |
| Intel Celeron           | 3         | 3.3%    |
| AMD Ryzen 9             | 3         | 3.3%    |
| AMD Ryzen Threadripper  | 2         | 2.2%    |
| AMD FX                  | 2         | 2.2%    |
| Intel Xeon Silver       | 1         | 1.1%    |
| Intel Xeon Gold         | 1         | 1.1%    |
| Intel Pentium Dual-Core | 1         | 1.1%    |
| Intel Pentium Dual      | 1         | 1.1%    |
| Intel Core i9           | 1         | 1.1%    |
| Intel Core 2 Quad       | 1         | 1.1%    |
| Intel Core 2 Duo        | 1         | 1.1%    |
| AMD Ryzen 7 PRO         | 1         | 1.1%    |
| AMD Ryzen 5 PRO         | 1         | 1.1%    |
| AMD Ryzen 3             | 1         | 1.1%    |
| AMD Phenom II X6        | 1         | 1.1%    |
| AMD A8                  | 1         | 1.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 30        | 32.97%  |
| 2      | 19        | 20.88%  |
| 8      | 14        | 15.38%  |
| 6      | 13        | 14.29%  |
| 12     | 5         | 5.49%   |
| 16     | 3         | 3.3%    |
| 10     | 2         | 2.2%    |
| 32     | 1         | 1.1%    |
| 28     | 1         | 1.1%    |
| 24     | 1         | 1.1%    |
| 3      | 1         | 1.1%    |
| 1      | 1         | 1.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 83        | 91.21%  |
| 2      | 8         | 8.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 69        | 75.82%  |
| 1      | 22        | 24.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 91        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 11        | 12.09%  |
| 0x506e3    | 5         | 5.49%   |
| 0x806ec    | 4         | 4.4%    |
| 0x306a9    | 4         | 4.4%    |
| 0x206a7    | 4         | 4.4%    |
| 0x806c1    | 3         | 3.3%    |
| 0xa0655    | 2         | 2.2%    |
| 0xa0652    | 2         | 2.2%    |
| 0x706a8    | 2         | 2.2%    |
| 0x50654    | 2         | 2.2%    |
| 0x406f1    | 2         | 2.2%    |
| 0x40651    | 2         | 2.2%    |
| 0x306e4    | 2         | 2.2%    |
| 0x206c2    | 2         | 2.2%    |
| 0x106a5    | 2         | 2.2%    |
| 0x10676    | 2         | 2.2%    |
| 0x0a50000c | 2         | 2.2%    |
| 0x08608103 | 2         | 2.2%    |
| 0x08600106 | 2         | 2.2%    |
| 0x08600104 | 2         | 2.2%    |
| 0x06000852 | 2         | 2.2%    |
| Unknown    | 2         | 2.2%    |
| 0xa0671    | 1         | 1.1%    |
| 0xa0653    | 1         | 1.1%    |
| 0x906ed    | 1         | 1.1%    |
| 0x906ea    | 1         | 1.1%    |
| 0x906a4    | 1         | 1.1%    |
| 0x906a3    | 1         | 1.1%    |
| 0x90675    | 1         | 1.1%    |
| 0x806e9    | 1         | 1.1%    |
| 0x6fd      | 1         | 1.1%    |
| 0x50657    | 1         | 1.1%    |
| 0x406e3    | 1         | 1.1%    |
| 0x306f2    | 1         | 1.1%    |
| 0x206d7    | 1         | 1.1%    |
| 0x1067a    | 1         | 1.1%    |
| 0x10677    | 1         | 1.1%    |
| 0x0a50000d | 1         | 1.1%    |
| 0x0a201016 | 1         | 1.1%    |
| 0x0a201009 | 1         | 1.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 15        | 16.48%  |
| Skylake          | 9         | 9.89%   |
| Zen 2            | 7         | 7.69%   |
| KabyLake         | 7         | 7.69%   |
| IvyBridge        | 6         | 6.59%   |
| Zen 3            | 5         | 5.49%   |
| SandyBridge      | 5         | 5.49%   |
| CometLake        | 5         | 5.49%   |
| Penryn           | 4         | 4.4%    |
| Zen+             | 3         | 3.3%    |
| TigerLake        | 3         | 3.3%    |
| Piledriver       | 3         | 3.3%    |
| Alderlake Hybrid | 3         | 3.3%    |
| Unknown          | 3         | 3.3%    |
| Westmere         | 2         | 2.2%    |
| Nehalem          | 2         | 2.2%    |
| Goldmont plus    | 2         | 2.2%    |
| Broadwell        | 2         | 2.2%    |
| Zen              | 1         | 1.1%    |
| K10              | 1         | 1.1%    |
| Icelake          | 1         | 1.1%    |
| Excavator        | 1         | 1.1%    |
| Core             | 1         | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 45        | 40.91%  |
| Nvidia                     | 38        | 34.55%  |
| AMD                        | 19        | 17.27%  |
| Matrox Electronics Systems | 4         | 3.64%   |
| ASPEED Technology          | 4         | 3.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 3.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 3.6%    |
| ASPEED Technology ASPEED Graphics Family                                    | 4         | 3.6%    |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 2.7%    |
| Intel HD Graphics 530                                                       | 3         | 2.7%    |
| AMD Renoir                                                                  | 3         | 2.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 1.8%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 1.8%    |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 1.8%    |
| Matrox Electronics Systems G200eR2                                          | 2         | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.8%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 2         | 1.8%    |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.8%    |
| AMD Lucienne                                                                | 2         | 1.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 1.8%    |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.9%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.9%    |
| Nvidia TU117GL [T600]                                                       | 1         | 0.9%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.9%    |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.9%    |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.9%    |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 0.9%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.9%    |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 0.9%    |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 0.9%    |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 0.9%    |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 0.9%    |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 0.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.9%    |
| Nvidia GK107M [GeForce GT 755M]                                             | 1         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 28        | 30.77%  |
| 1 x Nvidia      | 21        | 23.08%  |
| 1 x AMD         | 15        | 16.48%  |
| Intel + Nvidia  | 14        | 15.38%  |
| 1 x Matrox      | 3         | 3.3%    |
| 1 x ASPEED      | 3         | 3.3%    |
| Intel + AMD     | 2         | 2.2%    |
| Other           | 1         | 1.1%    |
| 2 x AMD         | 1         | 1.1%    |
| Nvidia + Matrox | 1         | 1.1%    |
| Nvidia + ASPEED | 1         | 1.1%    |
| AMD + Nvidia    | 1         | 1.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 69        | 75.82%  |
| Proprietary | 15        | 16.48%  |
| Unknown     | 7         | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 49.45%  |
| 0.01-0.5   | 14        | 15.38%  |
| 1.01-2.0   | 13        | 14.29%  |
| 3.01-4.0   | 6         | 6.59%   |
| 0.51-1.0   | 5         | 5.49%   |
| 5.01-6.0   | 3         | 3.3%    |
| 7.01-8.0   | 2         | 2.2%    |
| 8.01-16.0  | 2         | 2.2%    |
| 32.01-64.0 | 1         | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 12        | 12.5%   |
| Dell                 | 12        | 12.5%   |
| AU Optronics         | 9         | 9.38%   |
| LG Display           | 8         | 8.33%   |
| Goldstar             | 7         | 7.29%   |
| Chimei Innolux       | 7         | 7.29%   |
| Philips              | 5         | 5.21%   |
| Acer                 | 5         | 5.21%   |
| BOE                  | 4         | 4.17%   |
| AOC                  | 4         | 4.17%   |
| Iiyama               | 3         | 3.13%   |
| BenQ                 | 2         | 2.08%   |
| ASUSTek Computer     | 2         | 2.08%   |
| Ancor Communications | 2         | 2.08%   |
| Vizio                | 1         | 1.04%   |
| Sony                 | 1         | 1.04%   |
| Sharp                | 1         | 1.04%   |
| PANDA                | 1         | 1.04%   |
| Panasonic            | 1         | 1.04%   |
| OEM                  | 1         | 1.04%   |
| NEC Computers        | 1         | 1.04%   |
| Lenovo               | 1         | 1.04%   |
| IBM                  | 1         | 1.04%   |
| Hewlett-Packard      | 1         | 1.04%   |
| HCL                  | 1         | 1.04%   |
| Gigabyte Technology  | 1         | 1.04%   |
| Eizo                 | 1         | 1.04%   |
| ADR                  | 1         | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 2%      |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 1%      |
| Sony LG TV SNY045B 1920x540                                           | 1         | 1%      |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 1%      |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch     | 1         | 1%      |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1         | 1%      |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1         | 1%      |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1%      |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 700x400mm 31.7-inch    | 1         | 1%      |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 1%      |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1%      |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 1%      |
| Philips PHL 275E2F PHLC23A 2560x1440 600x340mm 27.2-inch              | 1         | 1%      |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 1%      |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1%      |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 1%      |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch             | 1         | 1%      |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1%      |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1%      |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 1%      |
| OEM 22W_LCD_TV OEM3700 1920x540                                       | 1         | 1%      |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch         | 1         | 1%      |
| LG Display LCD Monitor LGD06F9 1920x1200 302x189mm 14.0-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1%      |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1%      |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1%      |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1%      |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1%      |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 1         | 1%      |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1         | 1%      |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1         | 1%      |
| IBM RSA2 IBM029A 1024x768 300x225mm 14.8-inch                         | 1         | 1%      |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1         | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 42.7%   |
| 2560x1440 (QHD)    | 7         | 7.87%   |
| 1366x768 (WXGA)    | 6         | 6.74%   |
| 3840x2160 (4K)     | 5         | 5.62%   |
| 1920x1200 (WUXGA)  | 5         | 5.62%   |
| 1600x900 (HD+)     | 5         | 5.62%   |
| 1280x1024 (SXGA)   | 5         | 5.62%   |
| 3840x1080          | 3         | 3.37%   |
| 3440x1440          | 2         | 2.25%   |
| 2560x1080          | 2         | 2.25%   |
| 1920x540           | 2         | 2.25%   |
| 1680x1050 (WSXGA+) | 2         | 2.25%   |
| 1440x900 (WXGA+)   | 2         | 2.25%   |
| Unknown            | 2         | 2.25%   |
| 2240x1400          | 1         | 1.12%   |
| 1280x768           | 1         | 1.12%   |
| 1024x768 (XGA)     | 1         | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 21.05%  |
| 27      | 14        | 14.74%  |
| 14      | 10        | 10.53%  |
| 24      | 9         | 9.47%   |
| 17      | 6         | 6.32%   |
| 13      | 6         | 6.32%   |
| 21      | 5         | 5.26%   |
| 34      | 4         | 4.21%   |
| 31      | 4         | 4.21%   |
| 23      | 4         | 4.21%   |
| 19      | 3         | 3.16%   |
| Unknown | 2         | 2.11%   |
| 65      | 1         | 1.05%   |
| 49      | 1         | 1.05%   |
| 48      | 1         | 1.05%   |
| 40      | 1         | 1.05%   |
| 28      | 1         | 1.05%   |
| 22      | 1         | 1.05%   |
| 20      | 1         | 1.05%   |
| 18      | 1         | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 39.36%  |
| 501-600     | 25        | 26.6%   |
| 401-500     | 12        | 12.77%  |
| 601-700     | 5         | 5.32%   |
| 701-800     | 4         | 4.26%   |
| 201-300     | 3         | 3.19%   |
| 1001-1500   | 3         | 3.19%   |
| 351-400     | 2         | 2.13%   |
| Unknown     | 2         | 2.13%   |
| 801-900     | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 73.17%  |
| 16/10   | 8         | 9.76%   |
| 5/4     | 5         | 6.1%    |
| 21/9    | 3         | 3.66%   |
| 32/9    | 2         | 2.44%   |
| 3/2     | 2         | 2.44%   |
| 4/3     | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 21.28%  |
| 201-250        | 15        | 15.96%  |
| 81-90          | 14        | 14.89%  |
| 301-350        | 14        | 14.89%  |
| 351-500        | 8         | 8.51%   |
| 151-200        | 5         | 5.32%   |
| 141-150        | 5         | 5.32%   |
| 501-1000       | 4         | 4.26%   |
| 251-300        | 2         | 2.13%   |
| 121-130        | 2         | 2.13%   |
| Unknown        | 2         | 2.13%   |
| More than 1000 | 1         | 1.06%   |
| 71-80          | 1         | 1.06%   |
| 91-100         | 1         | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 40        | 42.55%  |
| 121-160       | 29        | 30.85%  |
| 101-120       | 14        | 14.89%  |
| 161-240       | 5         | 5.32%   |
| More than 240 | 2         | 2.13%   |
| 1-50          | 2         | 2.13%   |
| Unknown       | 2         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 56        | 61.54%  |
| 2     | 16        | 17.58%  |
| 0     | 15        | 16.48%  |
| 3     | 3         | 3.3%    |
| 4     | 1         | 1.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 59        | 45.04%  |
| Realtek Semiconductor     | 39        | 29.77%  |
| Qualcomm Atheros          | 6         | 4.58%   |
| Broadcom                  | 6         | 4.58%   |
| MediaTek                  | 4         | 3.05%   |
| Mellanox Technologies     | 3         | 2.29%   |
| Ralink Technology         | 2         | 1.53%   |
| Marvell Technology Group  | 2         | 1.53%   |
| Linksys                   | 2         | 1.53%   |
| Solarflare Communications | 1         | 0.76%   |
| Ralink                    | 1         | 0.76%   |
| Qualcomm                  | 1         | 0.76%   |
| Microsoft                 | 1         | 0.76%   |
| D-Link                    | 1         | 0.76%   |
| BUFFALO                   | 1         | 0.76%   |
| Broadcom Limited          | 1         | 0.76%   |
| Aquantia                  | 1         | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 30        | 19.23%  |
| Intel Wireless 7260                                                                                                    | 6         | 3.85%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 6         | 3.85%   |
| Intel Ethernet Connection I217-LM                                                                                      | 6         | 3.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 5         | 3.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 5         | 3.21%   |
| Intel I211 Gigabit Network Connection                                                                                  | 3         | 1.92%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 3         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 3         | 1.92%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 3         | 1.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 2         | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 2         | 1.28%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 1.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 2         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 2         | 1.28%   |
| Intel Wireless 8260                                                                                                    | 2         | 1.28%   |
| Intel Wireless 3165                                                                                                    | 2         | 1.28%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 2         | 1.28%   |
| Intel Ethernet Controller I225-V                                                                                       | 2         | 1.28%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 1.28%   |
| Intel Ethernet Connection I217-V                                                                                       | 2         | 1.28%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 2         | 1.28%   |
| Intel Ethernet Connection (14) I219-V                                                                                  | 2         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 2         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 2         | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                       | 2         | 1.28%   |
| Solarflare SFC9020 10G Ethernet Controller                                                                             | 1         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 1         | 0.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                                | 1         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                             | 1         | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 1         | 0.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 1         | 0.64%   |
| Realtek 802.11ac NIC                                                                                                   | 1         | 0.64%   |
| Ralink RT3071 Wireless Adapter                                                                                         | 1         | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                              | 1         | 0.64%   |
| Qualcomm MegaFon M150-4                                                                                                | 1         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 1         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                                              | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 61.82%  |
| Realtek Semiconductor | 5         | 9.09%   |
| Qualcomm Atheros      | 5         | 9.09%   |
| MediaTek              | 4         | 7.27%   |
| Ralink Technology     | 2         | 3.64%   |
| Linksys               | 2         | 3.64%   |
| Ralink                | 1         | 1.82%   |
| Microsoft             | 1         | 1.82%   |
| BUFFALO               | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 6         | 10.53%  |
| Intel Wi-Fi 6 AX200                                            | 6         | 10.53%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 3.51%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 3.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 3.51%   |
| Intel Wireless 8260                                            | 2         | 3.51%   |
| Intel Wireless 3165                                            | 2         | 3.51%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.51%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 3.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 3.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.75%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.75%   |
| Realtek 802.11ac NIC                                           | 1         | 1.75%   |
| Ralink RT3071 Wireless Adapter                                 | 1         | 1.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.75%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 1.75%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1         | 1.75%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1         | 1.75%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.75%   |
| Intel Wireless 7265                                            | 1         | 1.75%   |
| Intel Wireless 3160                                            | 1         | 1.75%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.75%   |
| Intel Centrino Wireless-N 135                                  | 1         | 1.75%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]       | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 39        | 43.33%  |
| Realtek Semiconductor     | 37        | 41.11%  |
| Broadcom                  | 6         | 6.67%   |
| Marvell Technology Group  | 2         | 2.22%   |
| Solarflare Communications | 1         | 1.11%   |
| Qualcomm Atheros          | 1         | 1.11%   |
| Qualcomm                  | 1         | 1.11%   |
| D-Link                    | 1         | 1.11%   |
| Broadcom Limited          | 1         | 1.11%   |
| Aquantia                  | 1         | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 31.25%  |
| Intel Ethernet Connection I217-LM                                 | 6         | 6.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 5.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.21%   |
| Intel I211 Gigabit Network Connection                             | 3         | 3.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 3.13%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 3.13%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.08%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 2.08%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.08%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.08%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 2.08%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 1.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.04%   |
| Qualcomm MegaFon M150-4                                           | 1         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.04%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.04%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.04%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.04%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.04%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 1.04%   |
| Intel Ethernet Controller X550                                    | 1         | 1.04%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.04%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 1.04%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.04%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.04%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 1.04%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 1.04%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.04%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.04%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.04%   |
| D-Link DUBE250 2.5GbE Adapter                                     | 1         | 1.04%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 60.14%  |
| WiFi     | 52        | 37.68%  |
| Unknown  | 3         | 2.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 57        | 63.33%  |
| WiFi     | 32        | 35.56%  |
| Unknown  | 1         | 1.11%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 40        | 43.96%  |
| 1     | 38        | 41.76%  |
| 3     | 5         | 5.49%   |
| 5     | 3         | 3.3%    |
| 0     | 2         | 2.2%    |
| 66    | 1         | 1.1%    |
| 8     | 1         | 1.1%    |
| 4     | 1         | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 72        | 79.12%  |
| Yes  | 19        | 20.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 62.22%  |
| Foxconn / Hon Hai               | 3         | 6.67%   |
| Realtek Semiconductor           | 2         | 4.44%   |
| Qualcomm Atheros Communications | 2         | 4.44%   |
| MediaTek                        | 2         | 4.44%   |
| Cambridge Silicon Radio         | 2         | 4.44%   |
| Broadcom                        | 2         | 4.44%   |
| Ralink                          | 1         | 2.22%   |
| Integrated System Solution      | 1         | 2.22%   |
| IMC Networks                    | 1         | 2.22%   |
| Hewlett-Packard                 | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 13        | 28.89%  |
| Intel AX200 Bluetooth                                 | 6         | 13.33%  |
| Intel AX201 Bluetooth                                 | 5         | 11.11%  |
| Foxconn / Hon Hai Wireless_Device                     | 3         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 4.44%   |
| MediaTek Wireless_Device                              | 2         | 4.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 4.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 4.44%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 2.22%   |
| Realtek Bluetooth Radio                               | 1         | 2.22%   |
| Ralink RT3290 Bluetooth                               | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 2.22%   |
| Intel Bluetooth Device                                | 1         | 2.22%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 2.22%   |
| IMC Networks Bluetooth Device                         | 1         | 2.22%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 2.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 2.22%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 58        | 45.67%  |
| Nvidia              | 30        | 23.62%  |
| AMD                 | 24        | 18.9%   |
| C-Media Electronics | 4         | 3.15%   |
| Logitech            | 2         | 1.57%   |
| GN Netcom           | 2         | 1.57%   |
| Creative Technology | 2         | 1.57%   |
| Unknown             | 1         | 0.79%   |
| Nektar              | 1         | 0.79%   |
| Hewlett-Packard     | 1         | 0.79%   |
| Conexant Systems    | 1         | 0.79%   |
| ASUSTek Computer    | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 7.24%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 7.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 5.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 3.95%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 2.63%   |
| Nvidia GK106 HDMI Audio Controller                                         | 4         | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.63%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 2.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.97%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 1.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.32%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.32%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 1.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.32%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.32%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 1.32%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 1.32%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.32%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.32%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 1.32%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.32%   |
| C-Media Electronics USB PnP Audio Device                                   | 2         | 1.32%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.32%   |
| Unknown Realtek USB Audio Rear                                             | 1         | 0.66%   |
| Unknown Realtek USB Audio Front                                            | 1         | 0.66%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.66%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.66%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.66%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 20.63%  |
| Micron Technology   | 13        | 20.63%  |
| Unknown             | 5         | 7.94%   |
| SK hynix            | 5         | 7.94%   |
| Kingston            | 5         | 7.94%   |
| G.Skill             | 5         | 7.94%   |
| Corsair             | 5         | 7.94%   |
| Crucial             | 3         | 4.76%   |
| A-DATA Technology   | 2         | 3.17%   |
| Unknown (ABCD)      | 1         | 1.59%   |
| Team                | 1         | 1.59%   |
| PNY                 | 1         | 1.59%   |
| Patriot             | 1         | 1.59%   |
| Magnum Tech         | 1         | 1.59%   |
| Lexar               | 1         | 1.59%   |
| Gold Key            | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                             | 1         | 1.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                             | 1         | 1.52%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                   | 1         | 1.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 1.52%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                              | 1         | 1.52%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                   | 1         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s      | 1         | 1.52%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s                    | 1         | 1.52%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                  | 1         | 1.52%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s               | 1         | 1.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                | 1         | 1.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                | 1         | 1.52%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s            | 1         | 1.52%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                           | 1         | 1.52%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s              | 1         | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 1.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                | 1         | 1.52%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.52%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s                  | 1         | 1.52%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 1.52%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 1.52%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 1.52%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s                | 1         | 1.52%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 1.52%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s                  | 1         | 1.52%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s          | 1         | 1.52%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s                  | 1         | 1.52%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s                      | 1         | 1.52%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s         | 1         | 1.52%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                              | 1         | 1.52%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                              | 1         | 1.52%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                   | 1         | 1.52%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                  | 1         | 1.52%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8192MB DIMM DDR4 3200MT/s                 | 1         | 1.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s            | 1         | 1.52%   |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s                  | 1         | 1.52%   |
| Micron RAM 36ASF4G72PZ-2G3D1 32GB DIMM DDR4 2400MT/s                  | 1         | 1.52%   |
| Micron RAM 3138485446313238373241592D3636374631 1GB DIMM DDR2 667MT/s | 1         | 1.52%   |
| Micron RAM 18ASF2G72AZ-2G3A1 16GB DIMM DDR4 2400MT/s                  | 1         | 1.52%   |
| Micron RAM 18ASF1G72PDZ-2G6F1 8GB DIMM DDR4 2666MT/s                  | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 33        | 58.93%  |
| DDR3    | 16        | 28.57%  |
| LPDDR4  | 3         | 5.36%   |
| DDR2    | 2         | 3.57%   |
| LPDDR5  | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 34        | 60.71%  |
| SODIMM       | 18        | 32.14%  |
| Row Of Chips | 3         | 5.36%   |
| RIMM         | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 45.9%   |
| 16384 | 10        | 16.39%  |
| 32768 | 8         | 13.11%  |
| 4096  | 7         | 11.48%  |
| 1024  | 5         | 8.2%    |
| 2048  | 3         | 4.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 14        | 22.95%  |
| 2667  | 9         | 14.75%  |
| 1600  | 7         | 11.48%  |
| 2400  | 6         | 9.84%   |
| 2133  | 4         | 6.56%   |
| 667   | 3         | 4.92%   |
| 1333  | 2         | 3.28%   |
| 1066  | 2         | 3.28%   |
| 6400  | 1         | 1.64%   |
| 4267  | 1         | 1.64%   |
| 4266  | 1         | 1.64%   |
| 3733  | 1         | 1.64%   |
| 3666  | 1         | 1.64%   |
| 3600  | 1         | 1.64%   |
| 3400  | 1         | 1.64%   |
| 3333  | 1         | 1.64%   |
| 3100  | 1         | 1.64%   |
| 3000  | 1         | 1.64%   |
| 2666  | 1         | 1.64%   |
| 2200  | 1         | 1.64%   |
| 1866  | 1         | 1.64%   |
| 1800  | 1         | 1.64%   |

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
| Chicony Electronics                    | 7         | 16.67%  |
| Syntek                                 | 4         | 9.52%   |
| Microdia                               | 4         | 9.52%   |
| IMC Networks                           | 4         | 9.52%   |
| Logitech                               | 3         | 7.14%   |
| Realtek Semiconductor                  | 2         | 4.76%   |
| Luxvisions Innotech Limited            | 2         | 4.76%   |
| Generalplus Technology                 | 2         | 4.76%   |
| Acer                                   | 2         | 4.76%   |
| Suyin                                  | 1         | 2.38%   |
| Sunplus Innovation Technology          | 1         | 2.38%   |
| Quanta                                 | 1         | 2.38%   |
| Lite-On Technology                     | 1         | 2.38%   |
| Lenovo                                 | 1         | 2.38%   |
| KYE Systems (Mouse Systems)            | 1         | 2.38%   |
| Intel                                  | 1         | 2.38%   |
| Huawei Technologies                    | 1         | 2.38%   |
| HD 2MP WEBCAM                          | 1         | 2.38%   |
| Elgato Systems                         | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.38%   |
| Apple                                  | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 9.52%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 7.14%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 4.76%   |
| Syntek Integrated Camera                                                   | 2         | 4.76%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 4.76%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 4.76%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.38%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 2.38%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.38%   |
| Realtek EasyCamera                                                         | 1         | 2.38%   |
| Quanta HP Webcam                                                           | 1         | 2.38%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 2.38%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 2.38%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 2.38%   |
| Logitech Webcam C270                                                       | 1         | 2.38%   |
| Logitech HD Pro Webcam C920                                                | 1         | 2.38%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 2.38%   |
| Lite-On HP HD Webcam                                                       | 1         | 2.38%   |
| Lenovo UVC Camera                                                          | 1         | 2.38%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                                 | 1         | 2.38%   |
| Intel RealSense 3D Camera (Front F200)                                     | 1         | 2.38%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 1         | 2.38%   |
| IMC Networks Integrated Camera                                             | 1         | 2.38%   |
| Huawei UVC Camera                                                          | 1         | 2.38%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                                                | 1         | 2.38%   |
| Elgato Systems Elgato Facecam                                              | 1         | 2.38%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 2.38%   |
| Chicony HP HD Camera                                                       | 1         | 2.38%   |
| Chicony HD WebCam                                                          | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.38%   |
| Apple iPhone5/5C/5S/6                                                      | 1         | 2.38%   |
| Acer Integrated RGB Camera                                                 | 1         | 2.38%   |
| Acer Integrated Camera                                                     | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 38.46%  |
| Synaptics                  | 4         | 30.77%  |
| LighTuning Technology      | 2         | 15.38%  |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| AuthenTec                  | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 15.38%  |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 7.69%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 7.69%   |
| LighTuning Fingerprint Sensor                              | 1         | 7.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 7.69%   |
| AuthenTec AES2810                                          | 1         | 7.69%   |
| Unknown                                                    | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 50%     |
| O2 Micro    | 1         | 25%     |
| Broadcom    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader  | 2         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 25%     |
| Broadcom 58200                       | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 50        | 54.95%  |
| 1     | 27        | 29.67%  |
| 2     | 10        | 10.99%  |
| 3     | 2         | 2.2%    |
| 5     | 1         | 1.1%    |
| 4     | 1         | 1.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 23.21%  |
| Graphics card            | 10        | 17.86%  |
| Net/wireless             | 9         | 16.07%  |
| Unassigned class         | 5         | 8.93%   |
| Communication controller | 4         | 7.14%   |
| Chipcard                 | 3         | 5.36%   |
| Network                  | 2         | 3.57%   |
| Net/ethernet             | 2         | 3.57%   |
| Multimedia controller    | 2         | 3.57%   |
| Storage/raid             | 1         | 1.79%   |
| Storage                  | 1         | 1.79%   |
| Sound                    | 1         | 1.79%   |
| Firewire controller      | 1         | 1.79%   |
| Card reader              | 1         | 1.79%   |
| Bluetooth                | 1         | 1.79%   |

