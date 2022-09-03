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

Total: 74

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 8.5 | 31        | 50.82%  |
| Rocky Linux 8.4 | 19        | 31.15%  |
| Rocky Linux 9.0 | 5         | 8.2%    |
| Rocky Linux 8.6 | 4         | 6.56%   |
| Rocky Linux 8.3 | 2         | 3.28%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 60        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 21.31%  |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 13.11%  |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 9.84%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 6.56%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 3         | 4.92%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 4.92%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 3.28%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 3.28%   |
| 4.18.0-305.el8.x86_64            | 2         | 3.28%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 3.28%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 3.28%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 3.28%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 3.28%   |
| 5.4.157-1.el8.elrepo.x86_64      | 1         | 1.64%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1         | 1.64%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 1         | 1.64%   |
| 5.14.0-70.13.1.el9_0.x86_64      | 1         | 1.64%   |
| 5.10.89-1.el8.x86_64             | 1         | 1.64%   |
| 5.10.52-v8.1.el8                 | 1         | 1.64%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 1         | 1.64%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 1         | 1.64%   |
| 4.18.0-348.el8.0.2.x86_64        | 1         | 1.64%   |
| 4.18.0-348.23.1.el8_5.x86_64     | 1         | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 51        | 85%     |
| 5.14.0  | 5         | 8.33%   |
| 5.4.157 | 1         | 1.67%   |
| 5.14.1  | 1         | 1.67%   |
| 5.10.89 | 1         | 1.67%   |
| 5.10.52 | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 51        | 85%     |
| 5.14    | 6         | 10%     |
| 5.10    | 2         | 3.33%   |
| 5.4     | 1         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 59        | 98.33%  |
| aarch64 | 1         | 1.67%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 41        | 68.33%  |
| Unknown       | 7         | 11.67%  |
| KDE5          | 4         | 6.67%   |
| MATE          | 3         | 5%      |
| GNOME Classic | 3         | 5%      |
| XFCE          | 1         | 1.67%   |
| X-Cinnamon    | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 31        | 51.67%  |
| X11     | 24        | 40%     |
| Unknown | 5         | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 50%     |
| GDM     | 25        | 41.67%  |
| SDDM    | 3         | 5%      |
| LightDM | 2         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 37        | 61.67%  |
| ru_RU   | 3         | 5%      |
| en_IL   | 3         | 5%      |
| en_AU   | 3         | 5%      |
| en_ZA   | 2         | 3.33%   |
| en_SG   | 2         | 3.33%   |
| de_DE   | 2         | 3.33%   |
| pt_BR   | 1         | 1.67%   |
| pl_PL   | 1         | 1.67%   |
| ja_JP   | 1         | 1.67%   |
| it_IT   | 1         | 1.67%   |
| es_CO   | 1         | 1.67%   |
| en_CA   | 1         | 1.67%   |
| af_ZA   | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 32        | 53.33%  |
| BIOS | 28        | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 47        | 78.33%  |
| Ext4 | 13        | 21.67%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 25        | 41.67%  |
| GPT     | 23        | 38.33%  |
| MBR     | 12        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 85%     |
| Yes       | 9         | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 86.67%  |
| Yes       | 8         | 13.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 15        | 25%     |
| Dell                    | 13        | 21.67%  |
| ASUSTek Computer        | 8         | 13.33%  |
| Hewlett-Packard         | 5         | 8.33%   |
| Gigabyte Technology     | 4         | 6.67%   |
| Toshiba                 | 2         | 3.33%   |
| Supermicro              | 2         | 3.33%   |
| Unknown                 | 2         | 3.33%   |
| Raspberry Pi Foundation | 1         | 1.67%   |
| NCR                     | 1         | 1.67%   |
| MSI                     | 1         | 1.67%   |
| Intel                   | 1         | 1.67%   |
| IBM                     | 1         | 1.67%   |
| Google                  | 1         | 1.67%   |
| AZW                     | 1         | 1.67%   |
| ASRock                  | 1         | 1.67%   |
| Acer                    | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge R610                      | 2         | 3.33%   |
| Dell OptiPlex 9020                       | 2         | 3.33%   |
| Unknown                                  | 2         | 3.33%   |
| Toshiba TECRA W50-A                      | 1         | 1.67%   |
| Toshiba Satellite E45-B                  | 1         | 1.67%   |
| Supermicro SYS-5029P-WTR                 | 1         | 1.67%   |
| Supermicro Super Server                  | 1         | 1.67%   |
| RPi Raspberry Pi                         | 1         | 1.67%   |
| NCR xxxx-xxxx-xxxx                       | 1         | 1.67%   |
| MSI MS-7917                              | 1         | 1.67%   |
| Lenovo ThinkStation P620 30E0S0PR00      | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 1.67%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 1.67%   |
| Lenovo ThinkPad W500 406132G             | 1         | 1.67%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 1.67%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 1.67%   |
| Lenovo ThinkCentre M72e 36601Y8          | 1         | 1.67%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 1.67%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.67%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9         | 1         | 1.67%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU        | 1         | 1.67%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 1.67%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 1.67%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 1.67%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 1.67%   |
| Intel S2600WFT                           | 1         | 1.67%   |
| IBM System x3200 M2 -[4368IGS]-          | 1         | 1.67%   |
| HP ZBook 15 G3                           | 1         | 1.67%   |
| HP ZBook 15 G2                           | 1         | 1.67%   |
| HP Z600 Workstation                      | 1         | 1.67%   |
| HP Laptop 17-ca1xxx                      | 1         | 1.67%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 1.67%   |
| Google Panther                           | 1         | 1.67%   |
| Gigabyte X570 AORUS ULTRA                | 1         | 1.67%   |
| Gigabyte H87-D3H                         | 1         | 1.67%   |
| Gigabyte G41MT-USB3                      | 1         | 1.67%   |
| Gigabyte 970A-UD3P                       | 1         | 1.67%   |
| Dell Vostro 3681                         | 1         | 1.67%   |
| Dell Precision Tower 7810                | 1         | 1.67%   |
| Dell Precision T7610                     | 1         | 1.67%   |
| Dell Precision T5610                     | 1         | 1.67%   |
| Dell PowerEdge R730xd                    | 1         | 1.67%   |
| Dell PowerEdge R720xd                    | 1         | 1.67%   |
| Dell OptiPlex 390                        | 1         | 1.67%   |
| Dell Latitude 5500                       | 1         | 1.67%   |
| Dell Latitude 3420                       | 1         | 1.67%   |
| AZW Gemini M                             | 1         | 1.67%   |
| ASUS PRIME TRX40-PRO S                   | 1         | 1.67%   |
| ASUS PRIME B460M-A R2.0                  | 1         | 1.67%   |
| ASUS PRIME B450M-A II                    | 1         | 1.67%   |
| ASUS PRIME B450-PLUS                     | 1         | 1.67%   |
| ASUS PRIME B365-PLUS                     | 1         | 1.67%   |
| ASUS P5Q DELUXE                          | 1         | 1.67%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 1.67%   |
| ASUS ASUS TUF Dash F15 FX516PM_FX516PM   | 1         | 1.67%   |
| ASRock B450M Pro4                        | 1         | 1.67%   |
| Acer Aspire VN7-591G                     | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 5         | 8.33%   |
| ASUS PRIME               | 5         | 8.33%   |
| Lenovo IdeaPad           | 4         | 6.67%   |
| Dell PowerEdge           | 4         | 6.67%   |
| Dell Precision           | 3         | 5%      |
| Dell OptiPlex            | 3         | 5%      |
| Lenovo Legion            | 2         | 3.33%   |
| Lenovo IdeaPadFlex       | 2         | 3.33%   |
| HP ZBook                 | 2         | 3.33%   |
| Dell Latitude            | 2         | 3.33%   |
| ASUS ASUS                | 2         | 3.33%   |
| Unknown                  | 2         | 3.33%   |
| Toshiba TECRA            | 1         | 1.67%   |
| Toshiba Satellite        | 1         | 1.67%   |
| Supermicro SYS-5029P-WTR | 1         | 1.67%   |
| Supermicro Super         | 1         | 1.67%   |
| RPi Raspberry            | 1         | 1.67%   |
| NCR xxxx-xxxx-xxxx       | 1         | 1.67%   |
| MSI MS-7917              | 1         | 1.67%   |
| Lenovo ThinkStation      | 1         | 1.67%   |
| Lenovo ThinkCentre       | 1         | 1.67%   |
| Intel S2600WFT           | 1         | 1.67%   |
| IBM System               | 1         | 1.67%   |
| HP Z600                  | 1         | 1.67%   |
| HP Laptop                | 1         | 1.67%   |
| HP EliteBook             | 1         | 1.67%   |
| Google Panther           | 1         | 1.67%   |
| Gigabyte X570            | 1         | 1.67%   |
| Gigabyte H87-D3H         | 1         | 1.67%   |
| Gigabyte G41MT-USB3      | 1         | 1.67%   |
| Gigabyte 970A-UD3P       | 1         | 1.67%   |
| Dell Vostro              | 1         | 1.67%   |
| AZW Gemini               | 1         | 1.67%   |
| ASUS P5Q                 | 1         | 1.67%   |
| ASRock B450M             | 1         | 1.67%   |
| Acer Aspire              | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 9         | 15%     |
| 2020    | 9         | 15%     |
| 2019    | 6         | 10%     |
| 2014    | 6         | 10%     |
| 2018    | 5         | 8.33%   |
| 2015    | 5         | 8.33%   |
| 2013    | 5         | 8.33%   |
| 2011    | 4         | 6.67%   |
| 2022    | 2         | 3.33%   |
| 2016    | 2         | 3.33%   |
| 2009    | 2         | 3.33%   |
| 2008    | 2         | 3.33%   |
| 2012    | 1         | 1.67%   |
| 2010    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 26        | 43.33%  |
| Notebook       | 22        | 36.67%  |
| Server         | 8         | 13.33%  |
| Convertible    | 2         | 3.33%   |
| System on chip | 1         | 1.67%   |
| Tablet         | 1         | 1.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 59        | 98.33%  |
| Enabled  | 1         | 1.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 98.33%  |
| Yes  | 1         | 1.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 13        | 21.67%  |
| 32.01-64.0      | 12        | 20%     |
| 16.01-24.0      | 10        | 16.67%  |
| 8.01-16.0       | 10        | 16.67%  |
| 3.01-4.0        | 4         | 6.67%   |
| More than 256.0 | 3         | 5%      |
| 64.01-256.0     | 3         | 5%      |
| 1.01-2.0        | 3         | 5%      |
| 2.01-3.0        | 2         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 16        | 26.23%  |
| 2.01-3.0  | 14        | 22.95%  |
| 1.01-2.0  | 14        | 22.95%  |
| 4.01-8.0  | 13        | 21.31%  |
| 8.01-16.0 | 2         | 3.28%   |
| 0.51-1.0  | 1         | 1.64%   |
| 0.01-0.5  | 1         | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 51.67%  |
| 2      | 13        | 21.67%  |
| 3      | 8         | 13.33%  |
| 4      | 4         | 6.67%   |
| 18     | 1         | 1.67%   |
| 16     | 1         | 1.67%   |
| 14     | 1         | 1.67%   |
| 8      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 63.33%  |
| Yes       | 22        | 36.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 95%     |
| No        | 3         | 5%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 58.33%  |
| No        | 25        | 41.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 50%     |
| No        | 30        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 23.33%  |
| Australia    | 4         | 6.67%   |
| South Africa | 3         | 5%      |
| Singapore    | 3         | 5%      |
| Russia       | 3         | 5%      |
| Israel       | 3         | 5%      |
| Germany      | 3         | 5%      |
| Czechia      | 3         | 5%      |
| Poland       | 2         | 3.33%   |
| Mexico       | 2         | 3.33%   |
| India        | 2         | 3.33%   |
| Canada       | 2         | 3.33%   |
| Belgium      | 2         | 3.33%   |
| UK           | 1         | 1.67%   |
| Switzerland  | 1         | 1.67%   |
| Sweden       | 1         | 1.67%   |
| Slovakia     | 1         | 1.67%   |
| Portugal     | 1         | 1.67%   |
| Norway       | 1         | 1.67%   |
| Malaysia     | 1         | 1.67%   |
| Kazakhstan   | 1         | 1.67%   |
| Japan        | 1         | 1.67%   |
| Italy        | 1         | 1.67%   |
| France       | 1         | 1.67%   |
| Colombia     | 1         | 1.67%   |
| China        | 1         | 1.67%   |
| Brazil       | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 5%      |
| Melbourne              | 3         | 5%      |
| Prague                 | 2         | 3.33%   |
| Haifa                  | 2         | 3.33%   |
| Centurion              | 2         | 3.33%   |
| Žilina                | 1         | 1.67%   |
| Xi'an                  | 1         | 1.67%   |
| Waltham                | 1         | 1.67%   |
| Toronto                | 1         | 1.67%   |
| Tlaxcala City          | 1         | 1.67%   |
| St Petersburg          | 1         | 1.67%   |
| Sobral de Monte Agraco | 1         | 1.67%   |
| Smolensk               | 1         | 1.67%   |
| Senigallia             | 1         | 1.67%   |
| Scarborough            | 1         | 1.67%   |
| Rehovot                | 1         | 1.67%   |
| Progresista            | 1         | 1.67%   |
| Philadelphia           | 1         | 1.67%   |
| Paris                  | 1         | 1.67%   |
| Ottignies              | 1         | 1.67%   |
| Ōtsu                  | 1         | 1.67%   |
| Oslo                   | 1         | 1.67%   |
| Örebro                | 1         | 1.67%   |
| Oakley                 | 1         | 1.67%   |
| Nur-Sultan             | 1         | 1.67%   |
| New York               | 1         | 1.67%   |
| Mossel Bay             | 1         | 1.67%   |
| Moscow                 | 1         | 1.67%   |
| Mequon                 | 1         | 1.67%   |
| Manassas               | 1         | 1.67%   |
| Lebanon                | 1         | 1.67%   |
| Kutno                  | 1         | 1.67%   |
| Krasova                | 1         | 1.67%   |
| Krakow                 | 1         | 1.67%   |
| Johor Bahru            | 1         | 1.67%   |
| Jaú                   | 1         | 1.67%   |
| Imphal                 | 1         | 1.67%   |
| Houston                | 1         | 1.67%   |
| Glasgow                | 1         | 1.67%   |
| Giessen                | 1         | 1.67%   |
| Fredericton            | 1         | 1.67%   |
| Fredericksburg         | 1         | 1.67%   |
| Forest                 | 1         | 1.67%   |
| Dreieich               | 1         | 1.67%   |
| Corvallis              | 1         | 1.67%   |
| Burlington             | 1         | 1.67%   |
| Bucaramanga            | 1         | 1.67%   |
| Brussels               | 1         | 1.67%   |
| Berlin                 | 1         | 1.67%   |
| Bengaluru              | 1         | 1.67%   |
| Ashburn                | 1         | 1.67%   |
| Adelaide               | 1         | 1.67%   |
| Aarau                  | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 16        | 44     | 17.2%   |
| Samsung Electronics     | 16        | 21     | 17.2%   |
| WDC                     | 11        | 24     | 11.83%  |
| Toshiba                 | 9         | 9      | 9.68%   |
| Unknown                 | 4         | 4      | 4.3%    |
| Intel                   | 4         | 5      | 4.3%    |
| SK hynix                | 3         | 4      | 3.23%   |
| Hitachi                 | 3         | 4      | 3.23%   |
| SanDisk                 | 2         | 2      | 2.15%   |
| Phison                  | 2         | 2      | 2.15%   |
| Kingston                | 2         | 2      | 2.15%   |
| Crucial                 | 2         | 2      | 2.15%   |
| Corsair                 | 2         | 2      | 2.15%   |
| A-DATA Technology       | 2         | 2      | 2.15%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.08%   |
| UMIS                    | 1         | 1      | 1.08%   |
| StoreJet                | 1         | 1      | 1.08%   |
| PNY                     | 1         | 1      | 1.08%   |
| LITEONIT                | 1         | 1      | 1.08%   |
| LITEON                  | 1         | 1      | 1.08%   |
| IBM                     | 1         | 1      | 1.08%   |
| HGST                    | 1         | 1      | 1.08%   |
| Gigabyte Technology     | 1         | 1      | 1.08%   |
| Fujitsu                 | 1         | 1      | 1.08%   |
| Dogfish                 | 1         | 1      | 1.08%   |
| China                   | 1         | 1      | 1.08%   |
| Apacer                  | 1         | 1      | 1.08%   |
| AGI                     | 1         | 1      | 1.08%   |
| ADATA Technology        | 1         | 1      | 1.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                       | 2         | 1.9%    |
| Seagate ST500DM002-1BD142 500GB              | 2         | 1.9%    |
| Seagate ST300MP0005 304GB                    | 2         | 1.9%    |
| Seagate ST2000DM008-2FR102 2TB               | 2         | 1.9%    |
| A-DATA SWORDFISH 1TB                         | 2         | 1.9%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 0.95%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 0.95%   |
| WDC WD80EZZX-11CSGA0 8TB                     | 1         | 0.95%   |
| WDC WD80EMAZ-00WJTA0 8TB                     | 1         | 0.95%   |
| WDC WD80EDAZ-11TA3A0 8TB                     | 1         | 0.95%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 0.95%   |
| WDC WD5000AAKX-75U6AA0 500GB                 | 1         | 0.95%   |
| WDC WD5000AAKX-001CA0 500GB                  | 1         | 0.95%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 0.95%   |
| WDC WD2500AAJS-22VTA0 250GB                  | 1         | 0.95%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1         | 0.95%   |
| WDC WD120EDAZ-11F3RA0 12TB                   | 1         | 0.95%   |
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 0.95%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 0.95%   |
| WDC WD100EMAZ-00WJTA0 10TB                   | 1         | 0.95%   |
| WDC WD1001FALS-00J7B0 1TB                    | 1         | 0.95%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB         | 1         | 0.95%   |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 0.95%   |
| Unknown DA4064  64GB                         | 1         | 0.95%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.95%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 0.95%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 0.95%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 0.95%   |
| Toshiba PX05SVB192Y 1.9TB                    | 1         | 0.95%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.95%   |
| Toshiba MG07ACA12TE 12TB                     | 1         | 0.95%   |
| Toshiba MG04ACA400E 4TB                      | 1         | 0.95%   |
| Toshiba MG03ACA400 4TB                       | 1         | 0.95%   |
| Toshiba DT01ACA100 1TB                       | 1         | 0.95%   |
| Toshiba DT01ACA050 500GB                     | 1         | 0.95%   |
| StoreJet Disk 2TB                            | 1         | 0.95%   |
| SK hynix SHGS31-1000GS-2 1TB SSD             | 1         | 0.95%   |
| SK hynix SH920 2.5 7MM 256GB SSD             | 1         | 0.95%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 0.95%   |
| SK hynix BC511 NVMe 512GB                    | 1         | 0.95%   |
| Seagate ST9320325AS 320GB                    | 1         | 0.95%   |
| Seagate ST91000640SS 1TB                     | 1         | 0.95%   |
| Seagate ST8000DM004-2CX188 8TB               | 1         | 0.95%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 1         | 0.95%   |
| Seagate ST4000NM0033-9ZM170 4TB              | 1         | 0.95%   |
| Seagate ST4000DM004-2CV104 4TB               | 1         | 0.95%   |
| Seagate ST3160318AS 160GB                    | 1         | 0.95%   |
| Seagate ST2000NX0433 2TB                     | 1         | 0.95%   |
| Seagate ST1000VX005-2EZ102 1TB               | 1         | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 0.95%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 0.95%   |
| Seagate BUP Slim BL 2TB                      | 1         | 0.95%   |
| SanDisk SSD U110 16GB                        | 1         | 0.95%   |
| SanDisk SD5SG2256G1052E 256GB SSD            | 1         | 0.95%   |
| Samsung SSD 980 PRO 1TB                      | 1         | 0.95%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 0.95%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 0.95%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 0.95%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 0.95%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 0.95%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 44     | 40%     |
| WDC                 | 9         | 20     | 22.5%   |
| Toshiba             | 5         | 5      | 12.5%   |
| Hitachi             | 3         | 4      | 7.5%    |
| Samsung Electronics | 2         | 3      | 5%      |
| Unknown             | 1         | 1      | 2.5%    |
| StoreJet            | 1         | 1      | 2.5%    |
| IBM                 | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 25.93%  |
| Toshiba             | 3         | 3      | 11.11%  |
| WDC                 | 2         | 2      | 7.41%   |
| SK hynix            | 2         | 2      | 7.41%   |
| SanDisk             | 2         | 2      | 7.41%   |
| PNY                 | 1         | 1      | 3.7%    |
| LITEONIT            | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| Kingston            | 1         | 1      | 3.7%    |
| Intel               | 1         | 2      | 3.7%    |
| Gigabyte Technology | 1         | 1      | 3.7%    |
| Dogfish             | 1         | 1      | 3.7%    |
| Crucial             | 1         | 1      | 3.7%    |
| Corsair             | 1         | 1      | 3.7%    |
| China               | 1         | 1      | 3.7%    |
| Apacer              | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 29        | 81     | 37.18%  |
| SSD     | 23        | 29     | 29.49%  |
| NVMe    | 22        | 28     | 28.21%  |
| MMC     | 3         | 3      | 3.85%   |
| Unknown | 1         | 1      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 107    | 59.15%  |
| NVMe | 22        | 28     | 30.99%  |
| SAS  | 4         | 4      | 5.63%   |
| MMC  | 3         | 3      | 4.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 42     | 45.61%  |
| 0.51-1.0   | 15        | 21     | 26.32%  |
| 1.01-2.0   | 8         | 11     | 14.04%  |
| 3.01-4.0   | 4         | 20     | 7.02%   |
| 10.01-20.0 | 2         | 3      | 3.51%   |
| 2.01-3.0   | 1         | 1      | 1.75%   |
| 4.01-10.0  | 1         | 12     | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 28.33%  |
| 251-500        | 11        | 18.33%  |
| 501-1000       | 10        | 16.67%  |
| 1001-2000      | 7         | 11.67%  |
| More than 3000 | 6         | 10%     |
| 2001-3000      | 4         | 6.67%   |
| 51-100         | 3         | 5%      |
| 1-20           | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 31.67%  |
| 21-50          | 14        | 23.33%  |
| 51-100         | 6         | 10%     |
| 101-250        | 5         | 8.33%   |
| 251-500        | 4         | 6.67%   |
| 501-1000       | 4         | 6.67%   |
| More than 3000 | 3         | 5%      |
| 1001-2000      | 3         | 5%      |
| 2001-3000      | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

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
| Works    | 32        | 75     | 46.38%  |
| Detected | 28        | 45     | 40.58%  |
| Malfunc  | 9         | 22     | 13.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 42        | 52.5%   |
| AMD                          | 10        | 12.5%   |
| Samsung Electronics          | 6         | 7.5%    |
| LSI Logic / Symbios Logic    | 4         | 5%      |
| Phison Electronics           | 3         | 3.75%   |
| Broadcom / LSI               | 3         | 3.75%   |
| Realtek Semiconductor        | 2         | 2.5%    |
| Union Memory (Shenzhen)      | 1         | 1.25%   |
| Toshiba America Info Systems | 1         | 1.25%   |
| SK hynix                     | 1         | 1.25%   |
| SanDisk                      | 1         | 1.25%   |
| Micron/Crucial Technology    | 1         | 1.25%   |
| Marvell Technology Group     | 1         | 1.25%   |
| Kingston Technology Company  | 1         | 1.25%   |
| ASMedia Technology           | 1         | 1.25%   |
| ADATA Technology             | 1         | 1.25%   |
| Adaptec                      | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 8.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 4.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 3.03%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 3.03%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2         | 2.02%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 2.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 2.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 2.02%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 2.02%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 2.02%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 2.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 2.02%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.02%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 2.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 2.02%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2         | 2.02%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 1.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 1.01%   |
| SK hynix BC511                                                                          | 1         | 1.01%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 1.01%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.01%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.01%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1         | 1.01%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 1.01%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.01%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 1.01%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 1.01%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 1         | 1.01%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                               | 1         | 1.01%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 1.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.01%   |
| Intel SSD 660P Series                                                                   | 1         | 1.01%   |
| Intel PCIe Data Center SSD                                                              | 1         | 1.01%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                                | 1         | 1.01%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.01%   |
| Intel Comet Lake PCH-H RAID                                                             | 1         | 1.01%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1         | 1.01%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 1.01%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 1.01%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 1.01%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 1.01%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 1.01%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1         | 1.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 35        | 41.67%  |
| NVMe | 22        | 26.19%  |
| IDE  | 14        | 16.67%  |
| RAID | 9         | 10.71%  |
| SAS  | 3         | 3.57%   |
| SCSI | 1         | 1.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 75%     |
| AMD    | 14        | 23.33%  |
| ARM    | 1         | 1.67%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Xeon CPU L5530 @ 2.40GHz                 | 2         | 3.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 2         | 3.33%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2         | 3.33%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz           | 1         | 1.67%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz             | 1         | 1.67%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1         | 1.67%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1         | 1.67%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz            | 1         | 1.67%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz             | 1         | 1.67%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1         | 1.67%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1         | 1.67%   |
| Intel Xeon CPU E3110 @ 3.00GHz                 | 1         | 1.67%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz            | 1         | 1.67%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1         | 1.67%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1         | 1.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 1         | 1.67%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz             | 1         | 1.67%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz             | 1         | 1.67%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz             | 1         | 1.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1         | 1.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 1.67%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz             | 1         | 1.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.67%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1         | 1.67%   |
| Intel Core i7-10610U CPU @ 1.80GHz             | 1         | 1.67%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1         | 1.67%   |
| Intel Core i5-8365U CPU @ 1.60GHz              | 1         | 1.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 1.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 1.67%   |
| Intel Core i5-3427U CPU @ 1.80GHz              | 1         | 1.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 1         | 1.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 1.67%   |
| Intel Core i5-10600KF CPU @ 4.10GHz            | 1         | 1.67%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1         | 1.67%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1         | 1.67%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 1.67%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 1         | 1.67%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 1.67%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1         | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 1.67%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz        | 1         | 1.67%   |
| ARM Processor                                  | 1         | 1.67%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores     | 1         | 1.67%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1         | 1.67%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 1.67%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 1         | 1.67%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 1.67%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1         | 1.67%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics     | 1         | 1.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 1         | 1.67%   |
| AMD Ryzen 5 4600H with Radeon Graphics         | 1         | 1.67%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 1.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 1.67%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1         | 1.67%   |
| AMD FX-6300 Six-Core Processor                 | 1         | 1.67%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 15        | 25%     |
| Intel Xeon              | 10        | 16.67%  |
| Intel Core i5           | 8         | 13.33%  |
| Other                   | 4         | 6.67%   |
| AMD Ryzen 5             | 4         | 6.67%   |
| Intel Celeron           | 3         | 5%      |
| AMD Ryzen 7             | 3         | 5%      |
| AMD Ryzen Threadripper  | 2         | 3.33%   |
| Intel Xeon Silver       | 1         | 1.67%   |
| Intel Xeon Gold         | 1         | 1.67%   |
| Intel Pentium Dual-Core | 1         | 1.67%   |
| Intel Pentium Dual      | 1         | 1.67%   |
| Intel Core i3           | 1         | 1.67%   |
| Intel Core 2 Quad       | 1         | 1.67%   |
| Intel Core 2 Duo        | 1         | 1.67%   |
| AMD Ryzen 9             | 1         | 1.67%   |
| AMD Ryzen 5 PRO         | 1         | 1.67%   |
| AMD Ryzen 3             | 1         | 1.67%   |
| AMD FX                  | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 23        | 38.33%  |
| 2      | 12        | 20%     |
| 8      | 9         | 15%     |
| 6      | 7         | 11.67%  |
| 16     | 3         | 5%      |
| 12     | 2         | 3.33%   |
| 32     | 1         | 1.67%   |
| 28     | 1         | 1.67%   |
| 24     | 1         | 1.67%   |
| 3      | 1         | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 88.33%  |
| 2      | 7         | 11.67%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 70%     |
| 1      | 18        | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 60        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 8         | 13.33%  |
| 0x506e3    | 3         | 5%      |
| 0x206a7    | 3         | 5%      |
| 0xa0655    | 2         | 3.33%   |
| 0x806ec    | 2         | 3.33%   |
| 0x806c1    | 2         | 3.33%   |
| 0x706a8    | 2         | 3.33%   |
| 0x40651    | 2         | 3.33%   |
| 0x306e4    | 2         | 3.33%   |
| 0x306a9    | 2         | 3.33%   |
| 0x106a5    | 2         | 3.33%   |
| 0x10676    | 2         | 3.33%   |
| 0x08608103 | 2         | 3.33%   |
| 0x08600104 | 2         | 3.33%   |
| Unknown    | 2         | 3.33%   |
| 0xa0652    | 1         | 1.67%   |
| 0x906ed    | 1         | 1.67%   |
| 0x6fd      | 1         | 1.67%   |
| 0x50657    | 1         | 1.67%   |
| 0x50654    | 1         | 1.67%   |
| 0x406f1    | 1         | 1.67%   |
| 0x406e3    | 1         | 1.67%   |
| 0x306f2    | 1         | 1.67%   |
| 0x206d7    | 1         | 1.67%   |
| 0x206c2    | 1         | 1.67%   |
| 0x1067a    | 1         | 1.67%   |
| 0x10677    | 1         | 1.67%   |
| 0x0a50000c | 1         | 1.67%   |
| 0x0a201009 | 1         | 1.67%   |
| 0x0870100a | 1         | 1.67%   |
| 0x0830104d | 1         | 1.67%   |
| 0x08301039 | 1         | 1.67%   |
| 0x08108109 | 1         | 1.67%   |
| 0x08108102 | 1         | 1.67%   |
| 0x0800820d | 1         | 1.67%   |
| 0x06006705 | 1         | 1.67%   |
| 0x06000852 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 12        | 20%     |
| Skylake       | 6         | 10%     |
| Zen 2         | 5         | 8.33%   |
| SandyBridge   | 4         | 6.67%   |
| Penryn        | 4         | 6.67%   |
| IvyBridge     | 4         | 6.67%   |
| Zen+          | 3         | 5%      |
| KabyLake      | 3         | 5%      |
| CometLake     | 3         | 5%      |
| Unknown       | 3         | 5%      |
| Zen 3         | 2         | 3.33%   |
| TigerLake     | 2         | 3.33%   |
| Nehalem       | 2         | 3.33%   |
| Goldmont plus | 2         | 3.33%   |
| Westmere      | 1         | 1.67%   |
| Piledriver    | 1         | 1.67%   |
| Excavator     | 1         | 1.67%   |
| Core          | 1         | 1.67%   |
| Broadwell     | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 27        | 36.99%  |
| Intel                      | 26        | 35.62%  |
| AMD                        | 13        | 17.81%  |
| Matrox Electronics Systems | 4         | 5.48%   |
| ASPEED Technology          | 3         | 4.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 4.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 4.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 4.11%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3         | 4.11%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 2.74%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 2.74%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.74%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.74%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 2.74%   |
| AMD Lucienne                                                                | 2         | 2.74%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 1.37%   |
| Nvidia TU117GL [T600]                                                       | 1         | 1.37%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.37%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 1.37%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 1.37%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 1.37%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.37%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.37%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 1.37%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 1.37%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.37%   |
| Nvidia GK107M [GeForce GT 755M]                                             | 1         | 1.37%   |
| Nvidia GK107GL [Quadro K600]                                                | 1         | 1.37%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.37%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 1.37%   |
| Nvidia GK104GL [GRID K2]                                                    | 1         | 1.37%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 1.37%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1         | 1.37%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.37%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1         | 1.37%   |
| Nvidia GA102GL [RTX A6000]                                                  | 1         | 1.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.37%   |
| Intel HD Graphics P530                                                      | 1         | 1.37%   |
| Intel HD Graphics 530                                                       | 1         | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 1.37%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1         | 1.37%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1         | 1.37%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1         | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1         | 1.37%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                     | 1         | 1.37%   |
| AMD Renoir                                                                  | 1         | 1.37%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1         | 1.37%   |
| AMD ES1000                                                                  | 1         | 1.37%   |
| AMD Cezanne                                                                 | 1         | 1.37%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1         | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Nvidia      | 15        | 25%     |
| 1 x Intel       | 14        | 23.33%  |
| 1 x AMD         | 11        | 18.33%  |
| Intel + Nvidia  | 10        | 16.67%  |
| 1 x Matrox      | 3         | 5%      |
| 1 x ASPEED      | 3         | 5%      |
| Other           | 1         | 1.67%   |
| Nvidia + Matrox | 1         | 1.67%   |
| Intel + AMD     | 1         | 1.67%   |
| AMD + Nvidia    | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 45        | 75%     |
| Proprietary | 11        | 18.33%  |
| Unknown     | 4         | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 45%     |
| 1.01-2.0   | 9         | 15%     |
| 0.01-0.5   | 9         | 15%     |
| 3.01-4.0   | 4         | 6.67%   |
| 0.51-1.0   | 4         | 6.67%   |
| 5.01-6.0   | 3         | 5%      |
| 7.01-8.0   | 2         | 3.33%   |
| 32.01-64.0 | 1         | 1.67%   |
| 8.01-16.0  | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 10        | 16.13%  |
| Samsung Electronics | 6         | 9.68%   |
| Chimei Innolux      | 6         | 9.68%   |
| LG Display          | 5         | 8.06%   |
| Goldstar            | 5         | 8.06%   |
| AU Optronics        | 5         | 8.06%   |
| BOE                 | 4         | 6.45%   |
| Iiyama              | 3         | 4.84%   |
| AOC                 | 3         | 4.84%   |
| Philips             | 2         | 3.23%   |
| Acer                | 2         | 3.23%   |
| Sony                | 1         | 1.61%   |
| PANDA               | 1         | 1.61%   |
| Panasonic           | 1         | 1.61%   |
| OEM                 | 1         | 1.61%   |
| Lenovo              | 1         | 1.61%   |
| IBM                 | 1         | 1.61%   |
| Hewlett-Packard     | 1         | 1.61%   |
| HCL                 | 1         | 1.61%   |
| Eizo                | 1         | 1.61%   |
| ASUSTek Computer    | 1         | 1.61%   |
| ADR                 | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony LG TV SNY045B 1920x540                                           | 1         | 1.52%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 1.52%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 1.52%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.52%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 1.52%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.52%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 1.52%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.52%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.52%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch           | 1         | 1.52%   |
| OEM 32_LCD_TV OEM3700 1920x540                                        | 1         | 1.52%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.52%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.52%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.52%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 1         | 1.52%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1         | 1.52%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1         | 1.52%   |
| IBM RSA2 IBM029A 1024x768 300x225mm 14.8-inch                         | 1         | 1.52%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1         | 1.52%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                   | 1         | 1.52%   |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                   | 1         | 1.52%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.52%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 1         | 1.52%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.52%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.52%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.52%   |
| Eizo CG247X ENC2801 1920x1200 520x330mm 24.2-inch                     | 1         | 1.52%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 1         | 1.52%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 1.52%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 1.52%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.52%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                      | 1         | 1.52%   |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                       | 1         | 1.52%   |
| Dell LCD Monitor U2414H 3840x1080                                     | 1         | 1.52%   |
| Dell LCD Monitor U2414H                                               | 1         | 1.52%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                     | 1         | 1.52%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 1.52%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1         | 1.52%   |
| Dell 1703FP DEL3011 1280x1024 340x270mm 17.1-inch                     | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN14E6 1366x768 309x173mm 13.9-inch       | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN143F 1920x1200 301x188mm 14.0-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 1         | 1.52%   |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                 | 1         | 1.52%   |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 1.52%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 1.52%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                 | 1         | 1.52%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 1.52%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 340x190mm 15.3-inch        | 1         | 1.52%   |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 1.52%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 1.52%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 1.52%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 520x290mm 23.4-inch          | 1         | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 42.11%  |
| 1600x900 (HD+)     | 5         | 8.77%   |
| 1920x1200 (WUXGA)  | 4         | 7.02%   |
| 3840x2160 (4K)     | 3         | 5.26%   |
| 1366x768 (WXGA)    | 3         | 5.26%   |
| 1280x1024 (SXGA)   | 3         | 5.26%   |
| 3840x1080          | 2         | 3.51%   |
| 2560x1080          | 2         | 3.51%   |
| 1920x540           | 2         | 3.51%   |
| 1680x1050 (WSXGA+) | 2         | 3.51%   |
| 1440x900 (WXGA+)   | 2         | 3.51%   |
| Unknown            | 2         | 3.51%   |
| 3440x1440          | 1         | 1.75%   |
| 2560x1440 (QHD)    | 1         | 1.75%   |
| 1024x768 (XGA)     | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 12        | 19.35%  |
| 14      | 9         | 14.52%  |
| 27      | 8         | 12.9%   |
| 24      | 5         | 8.06%   |
| 17      | 4         | 6.45%   |
| 34      | 3         | 4.84%   |
| 23      | 3         | 4.84%   |
| 21      | 3         | 4.84%   |
| 19      | 3         | 4.84%   |
| 13      | 3         | 4.84%   |
| Unknown | 2         | 3.23%   |
| 65      | 1         | 1.61%   |
| 48      | 1         | 1.61%   |
| 31      | 1         | 1.61%   |
| 28      | 1         | 1.61%   |
| 22      | 1         | 1.61%   |
| 20      | 1         | 1.61%   |
| 18      | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 40.32%  |
| 501-600     | 16        | 25.81%  |
| 401-500     | 10        | 16.13%  |
| 701-800     | 3         | 4.84%   |
| 351-400     | 2         | 3.23%   |
| 1001-1500   | 2         | 3.23%   |
| Unknown     | 2         | 3.23%   |
| 601-700     | 1         | 1.61%   |
| 201-300     | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 36        | 67.92%  |
| 16/10   | 6         | 11.32%  |
| 5/4     | 3         | 5.66%   |
| 21/9    | 3         | 5.66%   |
| 3/2     | 2         | 3.77%   |
| 4/3     | 1         | 1.89%   |
| 32/9    | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 19.67%  |
| 81-90          | 11        | 18.03%  |
| 301-350        | 8         | 13.11%  |
| 201-250        | 8         | 13.11%  |
| 351-500        | 5         | 8.2%    |
| 151-200        | 5         | 8.2%    |
| 141-150        | 3         | 4.92%   |
| 251-300        | 2         | 3.28%   |
| 121-130        | 2         | 3.28%   |
| Unknown        | 2         | 3.28%   |
| More than 1000 | 1         | 1.64%   |
| 501-1000       | 1         | 1.64%   |
| 91-100         | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 26        | 42.62%  |
| 121-160       | 22        | 36.07%  |
| 101-120       | 7         | 11.48%  |
| 161-240       | 2         | 3.28%   |
| Unknown       | 2         | 3.28%   |
| More than 240 | 1         | 1.64%   |
| 1-50          | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 34        | 56.67%  |
| 0     | 12        | 20%     |
| 2     | 11        | 18.33%  |
| 3     | 2         | 3.33%   |
| 4     | 1         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 37        | 43.02%  |
| Realtek Semiconductor     | 26        | 30.23%  |
| Broadcom                  | 5         | 5.81%   |
| Qualcomm Atheros          | 4         | 4.65%   |
| Mellanox Technologies     | 3         | 3.49%   |
| Marvell Technology Group  | 2         | 2.33%   |
| Solarflare Communications | 1         | 1.16%   |
| Ralink Technology         | 1         | 1.16%   |
| Qualcomm                  | 1         | 1.16%   |
| Microsoft                 | 1         | 1.16%   |
| MediaTek                  | 1         | 1.16%   |
| Linksys                   | 1         | 1.16%   |
| BUFFALO                   | 1         | 1.16%   |
| Broadcom Limited          | 1         | 1.16%   |
| Aquantia                  | 1         | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 22        | 21.57%  |
| Intel Ethernet Connection I217-LM                                                                                      | 6         | 5.88%   |
| Intel Wireless 7260                                                                                                    | 5         | 4.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 4         | 3.92%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 3         | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 2         | 1.96%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 1.96%   |
| Intel Wireless 8260                                                                                                    | 2         | 1.96%   |
| Intel Wireless 3165                                                                                                    | 2         | 1.96%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 2         | 1.96%   |
| Intel I211 Gigabit Network Connection                                                                                  | 2         | 1.96%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 2         | 1.96%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 2         | 1.96%   |
| Solarflare SFC9020 10G Ethernet Controller                                                                             | 1         | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 1         | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 1         | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                                | 1         | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                             | 1         | 0.98%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1         | 0.98%   |
| Realtek 802.11ac NIC                                                                                                   | 1         | 0.98%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 1         | 0.98%   |
| Qualcomm Nokia X100                                                                                                    | 1         | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 1         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                                              | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                                       | 1         | 0.98%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                       | 1         | 0.98%   |
| Microsoft Xbox 360 Wireless Adapter                                                                                    | 1         | 0.98%   |
| Mellanox MT27700 Family [ConnectX-4]                                                                                   | 1         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 1         | 0.98%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                                                | 1         | 0.98%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                                                                   | 1         | 0.98%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                                                      | 1         | 0.98%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                                    | 1         | 0.98%   |
| Intel Wireless 7265                                                                                                    | 1         | 0.98%   |
| Intel Wireless 3160                                                                                                    | 1         | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                                                                        | 1         | 0.98%   |
| Intel I350 Gigabit Network Connection                                                                                  | 1         | 0.98%   |
| Intel Ethernet Virtual Function 700 Series                                                                             | 1         | 0.98%   |
| Intel Ethernet Controller X550                                                                                         | 1         | 0.98%   |
| Intel Ethernet Controller I225-V                                                                                       | 1         | 0.98%   |
| Intel Ethernet Connection I217-V                                                                                       | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 1         | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 1         | 0.98%   |
| Intel Ethernet Connection (11) I219-V                                                                                  | 1         | 0.98%   |
| Intel Ethernet 10G 2P X520 Adapter                                                                                     | 1         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                        | 1         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 1         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 1         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 1         | 0.98%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                                                   | 1         | 0.98%   |
| Intel 82567LM Gigabit Network Connection                                                                               | 1         | 0.98%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                                                               | 1         | 0.98%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                                                                      | 1         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                                                      | 1         | 0.98%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                                                                | 1         | 0.98%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet                                                           | 1         | 0.98%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                                                      | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 65.71%  |
| Realtek Semiconductor | 4         | 11.43%  |
| Qualcomm Atheros      | 3         | 8.57%   |
| Ralink Technology     | 1         | 2.86%   |
| Microsoft             | 1         | 2.86%   |
| MediaTek              | 1         | 2.86%   |
| Linksys               | 1         | 2.86%   |
| BUFFALO               | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 5         | 13.89%  |
| Intel Wi-Fi 6 AX200                                           | 3         | 8.33%   |
| Intel Wireless 8260                                           | 2         | 5.56%   |
| Intel Wireless 3165                                           | 2         | 5.56%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 5.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 5.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1         | 2.78%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 2.78%   |
| Realtek 802.11ac NIC                                          | 1         | 2.78%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 2.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 2.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 1         | 2.78%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1         | 2.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.78%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter           | 1         | 2.78%   |
| Intel Wireless 7265                                           | 1         | 2.78%   |
| Intel Wireless 3160                                           | 1         | 2.78%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 2.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 2.78%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]      | 1         | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 24        | 41.38%  |
| Intel                     | 22        | 37.93%  |
| Broadcom                  | 5         | 8.62%   |
| Marvell Technology Group  | 2         | 3.45%   |
| Solarflare Communications | 1         | 1.72%   |
| Qualcomm Atheros          | 1         | 1.72%   |
| Qualcomm                  | 1         | 1.72%   |
| Broadcom Limited          | 1         | 1.72%   |
| Aquantia                  | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 34.92%  |
| Intel Ethernet Connection I217-LM                                 | 6         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 6.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.17%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.17%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 3.17%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 3.17%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 1.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.59%   |
| Qualcomm Nokia X100                                               | 1         | 1.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.59%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.59%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.59%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.59%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.59%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 1.59%   |
| Intel Ethernet Controller X550                                    | 1         | 1.59%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.59%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.59%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.59%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.59%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 1.59%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 1.59%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.59%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.59%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 1         | 1.59%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet      | 1         | 1.59%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 56        | 59.57%  |
| WiFi     | 35        | 37.23%  |
| Unknown  | 3         | 3.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 39        | 63.93%  |
| WiFi     | 21        | 34.43%  |
| Unknown  | 1         | 1.64%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 46.67%  |
| 1     | 23        | 38.33%  |
| 5     | 2         | 3.33%   |
| 3     | 2         | 3.33%   |
| 0     | 2         | 3.33%   |
| 66    | 1         | 1.67%   |
| 8     | 1         | 1.67%   |
| 4     | 1         | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 48        | 80%     |
| Yes  | 12        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 66.67%  |
| Realtek Semiconductor           | 2         | 6.67%   |
| Foxconn / Hon Hai               | 2         | 6.67%   |
| Broadcom                        | 2         | 6.67%   |
| Qualcomm Atheros Communications | 1         | 3.33%   |
| Integrated System Solution      | 1         | 3.33%   |
| IMC Networks                    | 1         | 3.33%   |
| Cambridge Silicon Radio         | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 12        | 40%     |
| Intel AX201 Bluetooth                                 | 4         | 13.33%  |
| Intel AX200 Bluetooth                                 | 3         | 10%     |
| Foxconn / Hon Hai Wireless_Device                     | 2         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 3.33%   |
| Realtek Bluetooth Radio                               | 1         | 3.33%   |
| Qualcomm Atheros  Bluetooth Device                    | 1         | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1         | 3.33%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 3.33%   |
| IMC Networks Bluetooth Device                         | 1         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1         | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 3.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 37        | 43.02%  |
| Nvidia              | 22        | 25.58%  |
| AMD                 | 15        | 17.44%  |
| C-Media Electronics | 3         | 3.49%   |
| Logitech            | 2         | 2.33%   |
| Unknown             | 1         | 1.16%   |
| Nektar              | 1         | 1.16%   |
| Hewlett-Packard     | 1         | 1.16%   |
| GN Netcom           | 1         | 1.16%   |
| Creative Technology | 1         | 1.16%   |
| Conexant Systems    | 1         | 1.16%   |
| ASUSTek Computer    | 1         | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 8         | 7.77%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7         | 6.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5         | 4.85%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4         | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 3.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 3.88%   |
| Nvidia GK106 HDMI Audio Controller                                                | 3         | 2.91%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 2.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2         | 1.94%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 1.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2         | 1.94%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.94%   |
| Intel Comet Lake PCH cAVS                                                         | 2         | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 1.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2         | 1.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 1.94%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 1.94%   |
| C-Media Electronics Anua Mic CM 900                                               | 2         | 1.94%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 1.94%   |
| Unknown Realtek USB Audio Rear                                                    | 1         | 0.97%   |
| Unknown Realtek USB Audio Front                                                   | 1         | 0.97%   |
| Nvidia High Definition Audio Controller                                           | 1         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1         | 0.97%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1         | 0.97%   |
| Nvidia GM200 High Definition Audio                                                | 1         | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1         | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1         | 0.97%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1         | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                                     | 1         | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.97%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1         | 0.97%   |
| Nektar Impact GX61                                                                | 1         | 0.97%   |
| Logitech [G533 Wireless Headset Dongle]                                           | 1         | 0.97%   |
| Logitech Stereo H650e                                                             | 1         | 0.97%   |
| Intel Sunrise Point-LP HD Audio                                                   | 1         | 0.97%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1         | 0.97%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1         | 0.97%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1         | 0.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1         | 0.97%   |
| Intel 200 Series PCH HD Audio                                                     | 1         | 0.97%   |
| Hewlett-Packard USB Audio                                                         | 1         | 0.97%   |
| GN Netcom Jabra EVOLVE 65                                                         | 1         | 0.97%   |
| Creative Technology Sound Blaster Play! 3                                         | 1         | 0.97%   |
| Conexant Systems HP Dock Audio                                                    | 1         | 0.97%   |
| C-Media Electronics USB Advanced Audio Device                                     | 1         | 0.97%   |
| ASUSTek Computer USB Audio                                                        | 1         | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 0.97%   |
| AMD Navi 10 HDMI Audio                                                            | 1         | 0.97%   |
| AMD High Definition Audio Controller                                              | 1         | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 0.97%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 11        | 30.56%  |
| Samsung Electronics | 9         | 25%     |
| G.Skill             | 4         | 11.11%  |
| Unknown             | 3         | 8.33%   |
| SK hynix            | 3         | 8.33%   |
| Kingston            | 2         | 5.56%   |
| Unknown (ABCD)      | 1         | 2.78%   |
| Crucial             | 1         | 2.78%   |
| Corsair             | 1         | 2.78%   |
| A-DATA Technology   | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM 667MT/s                                   | 1         | 2.63%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 2.63%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                              | 1         | 2.63%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                   | 1         | 2.63%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s   | 1         | 2.63%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                  | 1         | 2.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                | 1         | 2.63%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s         | 1         | 2.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.63%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                | 1         | 2.63%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s                  | 1         | 2.63%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 2.63%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 2.63%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 2.63%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                   | 1         | 2.63%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 2.63%   |
| Micron RAM MT53E1G32D4NQ_046 8GB Row Of Chips LPDDR4 4267MT/s         | 1         | 2.63%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                              | 1         | 2.63%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                   | 1         | 2.63%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                    | 1         | 2.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s            | 1         | 2.63%   |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s                  | 1         | 2.63%   |
| Micron RAM 36ASF4G72PZ-2G3D1 32GB DIMM DDR4 2400MT/s                  | 1         | 2.63%   |
| Micron RAM 3138485446313238373241592D3636374631 1GB DIMM DDR2 667MT/s | 1         | 2.63%   |
| Micron RAM 18ASF2G72AZ-2G3A1 16GB DIMM DDR4 2400MT/s                  | 1         | 2.63%   |
| Micron RAM 18ASF1G72PDZ-2G6F1 8GB DIMM DDR4 2666MT/s                  | 1         | 2.63%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.63%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s                | 1         | 2.63%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 2.63%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 2.63%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3600MT/s                   | 1         | 2.63%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s                  | 1         | 2.63%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s                    | 1         | 2.63%   |
| G.Skill RAM F3-12800CL10 8GB DIMM DDR3 1600MT/s                       | 1         | 2.63%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16384MB SODIMM DDR4 2667MT/s         | 1         | 2.63%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s                  | 1         | 2.63%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                           | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 17        | 48.57%  |
| DDR3    | 12        | 34.29%  |
| LPDDR4  | 3         | 8.57%   |
| DDR2    | 2         | 5.71%   |
| Unknown | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 23        | 65.71%  |
| SODIMM       | 9         | 25.71%  |
| Row Of Chips | 2         | 5.71%   |
| RIMM         | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 15        | 41.67%  |
| 32768 | 6         | 16.67%  |
| 16384 | 5         | 13.89%  |
| 1024  | 5         | 13.89%  |
| 4096  | 3         | 8.33%   |
| 2048  | 2         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 7         | 19.44%  |
| 1600  | 5         | 13.89%  |
| 2667  | 4         | 11.11%  |
| 2400  | 4         | 11.11%  |
| 667   | 3         | 8.33%   |
| 2666  | 2         | 5.56%   |
| 2133  | 2         | 5.56%   |
| 1066  | 2         | 5.56%   |
| 4267  | 1         | 2.78%   |
| 4266  | 1         | 2.78%   |
| 3600  | 1         | 2.78%   |
| 3400  | 1         | 2.78%   |
| 2200  | 1         | 2.78%   |
| 1866  | 1         | 2.78%   |
| 1800  | 1         | 2.78%   |

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


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 6         | 21.43%  |
| Syntek                      | 4         | 14.29%  |
| Logitech                    | 3         | 10.71%  |
| Realtek Semiconductor       | 2         | 7.14%   |
| Luxvisions Innotech Limited | 2         | 7.14%   |
| IMC Networks                | 2         | 7.14%   |
| Quanta                      | 1         | 3.57%   |
| Microdia                    | 1         | 3.57%   |
| Lite-On Technology          | 1         | 3.57%   |
| Lenovo                      | 1         | 3.57%   |
| Intel                       | 1         | 3.57%   |
| Huawei Technologies         | 1         | 3.57%   |
| Elgato Systems              | 1         | 3.57%   |
| Apple                       | 1         | 3.57%   |
| Acer                        | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 4         | 14.29%  |
| Syntek Lenovo EasyCamera                      | 2         | 7.14%   |
| Syntek Integrated Camera                      | 2         | 7.14%   |
| Realtek Integrated_Webcam_HD                  | 1         | 3.57%   |
| Realtek EasyCamera                            | 1         | 3.57%   |
| Quanta HP Webcam                              | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD                 | 1         | 3.57%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 3.57%   |
| Luxvisions Innotech Limited HP HD Camera      | 1         | 3.57%   |
| Logitech Webcam C270                          | 1         | 3.57%   |
| Logitech HD Pro Webcam C920                   | 1         | 3.57%   |
| Logitech BRIO Ultra HD Webcam                 | 1         | 3.57%   |
| Lite-On HP HD Webcam                          | 1         | 3.57%   |
| Lenovo UVC Camera                             | 1         | 3.57%   |
| Intel RealSense 3D Camera (Front F200)        | 1         | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 3.57%   |
| IMC Networks TOSHIBA Web Camera - HD          | 1         | 3.57%   |
| Huawei UVC Camera                             | 1         | 3.57%   |
| Elgato Systems Elgato Facecam                 | 1         | 3.57%   |
| Chicony HP HD Camera                          | 1         | 3.57%   |
| Chicony HD WebCam                             | 1         | 3.57%   |
| Apple iPhone 5/5C/5S/6/SE                     | 1         | 3.57%   |
| Acer Integrated Camera                        | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 50%     |
| Synaptics                  | 2         | 25%     |
| Shenzhen Goodix Technology | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 25%     |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 12.5%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 12.5%   |
| AuthenTec AES2810                                         | 1         | 12.5%   |
| Unknown                                                   | 1         | 12.5%   |

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
| 0     | 30        | 50%     |
| 1     | 22        | 36.67%  |
| 2     | 6         | 10%     |
| 5     | 1         | 1.67%   |
| 4     | 1         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 21.05%  |
| Net/wireless             | 7         | 18.42%  |
| Graphics card            | 6         | 15.79%  |
| Unassigned class         | 4         | 10.53%  |
| Communication controller | 4         | 10.53%  |
| Network                  | 2         | 5.26%   |
| Net/ethernet             | 2         | 5.26%   |
| Chipcard                 | 2         | 5.26%   |
| Storage                  | 1         | 2.63%   |
| Multimedia controller    | 1         | 2.63%   |
| Card reader              | 1         | 2.63%   |

