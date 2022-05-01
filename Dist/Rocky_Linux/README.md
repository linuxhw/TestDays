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

Total: 62

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Dell          | 0M5DCD A00                  | Desktop     | [d40f4d3bee](https://linux-hardware.org/?probe=d40f4d3bee) | Aug 06, 2021 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [5ee09ac705](https://linux-hardware.org/?probe=5ee09ac705) | Aug 04, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [2a4bd5cb12](https://linux-hardware.org/?probe=2a4bd5cb12) | Jul 11, 2021 |
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
| Rocky Linux 8.5 | 27        | 57.45%  |
| Rocky Linux 8.4 | 18        | 38.3%   |
| Rocky Linux 8.3 | 2         | 4.26%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 47        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64 | 13        | 27.66%  |
| 4.18.0-348.7.1.el8_5.x86_64  | 8         | 17.02%  |
| 4.18.0-305.10.2.el8_4.x86_64 | 5         | 10.64%  |
| 4.18.0-305.25.1.el8_4.x86_64 | 3         | 6.38%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 2         | 4.26%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2         | 4.26%   |
| 4.18.0-305.el8.x86_64        | 2         | 4.26%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 2         | 4.26%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 2         | 4.26%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 2         | 4.26%   |
| 4.18.0-240.22.1.el8.x86_64   | 2         | 4.26%   |
| 5.4.157-1.el8.elrepo.x86_64  | 1         | 2.13%   |
| 5.14.1-1.el8.elrepo.x86_64   | 1         | 2.13%   |
| 5.10.52-v8.1.el8             | 1         | 2.13%   |
| 4.18.0-348.el8.0.2.x86_64    | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 44        | 93.62%  |
| 5.4.157 | 1         | 2.13%   |
| 5.14.1  | 1         | 2.13%   |
| 5.10.52 | 1         | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 44        | 93.62%  |
| 5.4     | 1         | 2.13%   |
| 5.14    | 1         | 2.13%   |
| 5.10    | 1         | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 46        | 97.87%  |
| aarch64 | 1         | 2.13%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 30        | 63.83%  |
| Unknown       | 7         | 14.89%  |
| KDE5          | 4         | 8.51%   |
| MATE          | 2         | 4.26%   |
| GNOME Classic | 2         | 4.26%   |
| XFCE          | 1         | 2.13%   |
| X-Cinnamon    | 1         | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 24        | 51.06%  |
| X11     | 18        | 38.3%   |
| Unknown | 5         | 10.64%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 25        | 53.19%  |
| GDM     | 17        | 36.17%  |
| SDDM    | 3         | 6.38%   |
| LightDM | 2         | 4.26%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 28        | 59.57%  |
| en_IL   | 3         | 6.38%   |
| ru_RU   | 2         | 4.26%   |
| en_ZA   | 2         | 4.26%   |
| en_SG   | 2         | 4.26%   |
| en_AU   | 2         | 4.26%   |
| de_DE   | 2         | 4.26%   |
| ja_JP   | 1         | 2.13%   |
| it_IT   | 1         | 2.13%   |
| es_CO   | 1         | 2.13%   |
| en_CA   | 1         | 2.13%   |
| af_ZA   | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 25        | 53.19%  |
| BIOS | 22        | 46.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 37        | 78.72%  |
| Ext4 | 10        | 21.28%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 44.68%  |
| GPT     | 18        | 38.3%   |
| MBR     | 8         | 17.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 91.49%  |
| Yes       | 4         | 8.51%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 91.49%  |
| Yes       | 4         | 8.51%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 12        | 25.53%  |
| Dell                    | 10        | 21.28%  |
| ASUSTek Computer        | 5         | 10.64%  |
| Hewlett-Packard         | 4         | 8.51%   |
| Gigabyte Technology     | 3         | 6.38%   |
| Toshiba                 | 2         | 4.26%   |
| Supermicro              | 2         | 4.26%   |
| Raspberry Pi Foundation | 1         | 2.13%   |
| NCR                     | 1         | 2.13%   |
| MSI                     | 1         | 2.13%   |
| Intel                   | 1         | 2.13%   |
| IBM                     | 1         | 2.13%   |
| Google                  | 1         | 2.13%   |
| AZW                     | 1         | 2.13%   |
| ASRock                  | 1         | 2.13%   |
| Acer                    | 1         | 2.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge R610                      | 2         | 4.26%   |
| Dell OptiPlex 9020                       | 2         | 4.26%   |
| Toshiba TECRA W50-A                      | 1         | 2.13%   |
| Toshiba Satellite E45-B                  | 1         | 2.13%   |
| Supermicro SYS-5029P-WTR                 | 1         | 2.13%   |
| Supermicro Super Server                  | 1         | 2.13%   |
| RPi Raspberry Pi                         | 1         | 2.13%   |
| NCR xxxx-xxxx-xxxx                       | 1         | 2.13%   |
| MSI MS-7917                              | 1         | 2.13%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 2.13%   |
| Lenovo ThinkPad W500 406132G             | 1         | 2.13%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 2.13%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 2.13%   |
| Lenovo ThinkCentre M72e 36601Y8          | 1         | 2.13%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 2.13%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 2.13%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU        | 1         | 2.13%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 2.13%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 2.13%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 2.13%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 2.13%   |
| Intel S2600WFT                           | 1         | 2.13%   |
| IBM System x3200 M2 -[4368IGS]-          | 1         | 2.13%   |
| HP ZBook 15 G3                           | 1         | 2.13%   |
| HP Z600 Workstation                      | 1         | 2.13%   |
| HP Laptop 17-ca1xxx                      | 1         | 2.13%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 2.13%   |
| Google Panther                           | 1         | 2.13%   |
| Gigabyte X570 AORUS ULTRA                | 1         | 2.13%   |
| Gigabyte H87-D3H                         | 1         | 2.13%   |
| Gigabyte G41MT-USB3                      | 1         | 2.13%   |
| Dell Vostro 3681                         | 1         | 2.13%   |
| Dell Precision T7610                     | 1         | 2.13%   |
| Dell Precision T5610                     | 1         | 2.13%   |
| Dell PowerEdge R720xd                    | 1         | 2.13%   |
| Dell OptiPlex 390                        | 1         | 2.13%   |
| Dell Latitude 5500                       | 1         | 2.13%   |
| AZW Gemini M                             | 1         | 2.13%   |
| ASUS PRIME TRX40-PRO S                   | 1         | 2.13%   |
| ASUS PRIME B450M-A II                    | 1         | 2.13%   |
| ASUS PRIME B450-PLUS                     | 1         | 2.13%   |
| ASUS P5Q DELUXE                          | 1         | 2.13%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 2.13%   |
| ASRock B450M Pro4                        | 1         | 2.13%   |
| Acer Aspire VN7-591G                     | 1         | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 8.51%   |
| Lenovo IdeaPad           | 4         | 8.51%   |
| Dell PowerEdge           | 3         | 6.38%   |
| Dell OptiPlex            | 3         | 6.38%   |
| ASUS PRIME               | 3         | 6.38%   |
| Lenovo Legion            | 2         | 4.26%   |
| Dell Precision           | 2         | 4.26%   |
| Toshiba TECRA            | 1         | 2.13%   |
| Toshiba Satellite        | 1         | 2.13%   |
| Supermicro SYS-5029P-WTR | 1         | 2.13%   |
| Supermicro Super         | 1         | 2.13%   |
| RPi Raspberry            | 1         | 2.13%   |
| NCR xxxx-xxxx-xxxx       | 1         | 2.13%   |
| MSI MS-7917              | 1         | 2.13%   |
| Lenovo ThinkCentre       | 1         | 2.13%   |
| Lenovo IdeaPadFlex       | 1         | 2.13%   |
| Intel S2600WFT           | 1         | 2.13%   |
| IBM System               | 1         | 2.13%   |
| HP ZBook                 | 1         | 2.13%   |
| HP Z600                  | 1         | 2.13%   |
| HP Laptop                | 1         | 2.13%   |
| HP EliteBook             | 1         | 2.13%   |
| Google Panther           | 1         | 2.13%   |
| Gigabyte X570            | 1         | 2.13%   |
| Gigabyte H87-D3H         | 1         | 2.13%   |
| Gigabyte G41MT-USB3      | 1         | 2.13%   |
| Dell Vostro              | 1         | 2.13%   |
| Dell Latitude            | 1         | 2.13%   |
| AZW Gemini               | 1         | 2.13%   |
| ASUS P5Q                 | 1         | 2.13%   |
| ASUS ASUS                | 1         | 2.13%   |
| ASRock B450M             | 1         | 2.13%   |
| Acer Aspire              | 1         | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 8         | 17.02%  |
| 2014    | 6         | 12.77%  |
| 2021    | 5         | 10.64%  |
| 2019    | 5         | 10.64%  |
| 2018    | 5         | 10.64%  |
| 2013    | 4         | 8.51%   |
| 2011    | 4         | 8.51%   |
| 2015    | 3         | 6.38%   |
| 2016    | 2         | 4.26%   |
| 2009    | 2         | 4.26%   |
| 2010    | 1         | 2.13%   |
| 2008    | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 20        | 42.55%  |
| Notebook       | 18        | 38.3%   |
| Server         | 7         | 14.89%  |
| System on chip | 1         | 2.13%   |
| Convertible    | 1         | 2.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 47        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 97.87%  |
| Yes  | 1         | 2.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 12        | 25.53%  |
| 32.01-64.0      | 8         | 17.02%  |
| 16.01-24.0      | 8         | 17.02%  |
| 8.01-16.0       | 8         | 17.02%  |
| 3.01-4.0        | 4         | 8.51%   |
| 1.01-2.0        | 3         | 6.38%   |
| More than 256.0 | 2         | 4.26%   |
| 64.01-256.0     | 2         | 4.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 29.79%  |
| 3.01-4.0  | 12        | 25.53%  |
| 1.01-2.0  | 10        | 21.28%  |
| 4.01-8.0  | 7         | 14.89%  |
| 8.01-16.0 | 2         | 4.26%   |
| 0.51-1.0  | 1         | 2.13%   |
| 0.01-0.5  | 1         | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 51.06%  |
| 2      | 10        | 21.28%  |
| 3      | 6         | 12.77%  |
| 4      | 4         | 8.51%   |
| 16     | 1         | 2.13%   |
| 14     | 1         | 2.13%   |
| 8      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 63.83%  |
| Yes       | 17        | 36.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 93.62%  |
| No        | 3         | 6.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 59.57%  |
| No        | 19        | 40.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 51.06%  |
| No        | 23        | 48.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 13        | 27.66%  |
| South Africa | 3         | 6.38%   |
| Singapore    | 3         | 6.38%   |
| Israel       | 3         | 6.38%   |
| Czechia      | 3         | 6.38%   |
| Russia       | 2         | 4.26%   |
| Germany      | 2         | 4.26%   |
| Canada       | 2         | 4.26%   |
| Belgium      | 2         | 4.26%   |
| Australia    | 2         | 4.26%   |
| UK           | 1         | 2.13%   |
| Slovakia     | 1         | 2.13%   |
| Portugal     | 1         | 2.13%   |
| Poland       | 1         | 2.13%   |
| Malaysia     | 1         | 2.13%   |
| Kazakhstan   | 1         | 2.13%   |
| Japan        | 1         | 2.13%   |
| Italy        | 1         | 2.13%   |
| India        | 1         | 2.13%   |
| France       | 1         | 2.13%   |
| Colombia     | 1         | 2.13%   |
| China        | 1         | 2.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Singapore        | 3         | 6.38%   |
| Prague           | 2         | 4.26%   |
| Melbourne        | 2         | 4.26%   |
| Haifa            | 2         | 4.26%   |
| Žilina          | 1         | 2.13%   |
| Xi'an            | 1         | 2.13%   |
| Weinheim         | 1         | 2.13%   |
| Toronto          | 1         | 2.13%   |
| St Petersburg    | 1         | 2.13%   |
| Scarborough      | 1         | 2.13%   |
| San Ramon        | 1         | 2.13%   |
| Saint Albans     | 1         | 2.13%   |
| Rehovot          | 1         | 2.13%   |
| Pretoria         | 1         | 2.13%   |
| Paris            | 1         | 2.13%   |
| Ottignies        | 1         | 2.13%   |
| Nur-Sultan       | 1         | 2.13%   |
| Nowy Wisnicz     | 1         | 2.13%   |
| New York         | 1         | 2.13%   |
| Mossel Bay       | 1         | 2.13%   |
| Moscow           | 1         | 2.13%   |
| Mequon           | 1         | 2.13%   |
| Manassas         | 1         | 2.13%   |
| Lisbon           | 1         | 2.13%   |
| Lebanon          | 1         | 2.13%   |
| Kuala Terengganu | 1         | 2.13%   |
| Jette            | 1         | 2.13%   |
| Houston          | 1         | 2.13%   |
| Glasgow          | 1         | 2.13%   |
| Fredericton      | 1         | 2.13%   |
| Fredericksburg   | 1         | 2.13%   |
| Forest           | 1         | 2.13%   |
| Corvallis        | 1         | 2.13%   |
| Contrada Tenna   | 1         | 2.13%   |
| Centurion        | 1         | 2.13%   |
| Burlington       | 1         | 2.13%   |
| Bucaramanga      | 1         | 2.13%   |
| Boskovice        | 1         | 2.13%   |
| Berlin           | 1         | 2.13%   |
| Bengaluru        | 1         | 2.13%   |
| ÅŒtsu          | 1         | 2.13%   |
| Ashburn          | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 12        | 39     | 16%     |
| WDC                     | 11        | 23     | 14.67%  |
| Samsung Electronics     | 11        | 13     | 14.67%  |
| Toshiba                 | 8         | 8      | 10.67%  |
| Unknown                 | 3         | 3      | 4%      |
| SK Hynix                | 3         | 4      | 4%      |
| Intel                   | 3         | 3      | 4%      |
| Hitachi                 | 3         | 4      | 4%      |
| Phison                  | 2         | 2      | 2.67%   |
| Kingston                | 2         | 2      | 2.67%   |
| Crucial                 | 2         | 2      | 2.67%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.33%   |
| UMIS                    | 1         | 2      | 1.33%   |
| StoreJet                | 1         | 1      | 1.33%   |
| SanDisk                 | 1         | 1      | 1.33%   |
| PNY                     | 1         | 1      | 1.33%   |
| LITEONIT                | 1         | 1      | 1.33%   |
| LITEON                  | 1         | 1      | 1.33%   |
| IBM                     | 1         | 1      | 1.33%   |
| HGST                    | 1         | 1      | 1.33%   |
| Fujitsu                 | 1         | 1      | 1.33%   |
| Dogfish                 | 1         | 1      | 1.33%   |
| Corsair                 | 1         | 1      | 1.33%   |
| China                   | 1         | 1      | 1.33%   |
| AGI                     | 1         | 1      | 1.33%   |
| A-DATA Technology       | 1         | 1      | 1.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                       | 2         | 2.33%   |
| Seagate ST300MP0005 304GB                    | 2         | 2.33%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1.16%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1.16%   |
| WDC WD80EZZX-11CSGA0 8TB                     | 1         | 1.16%   |
| WDC WD80EMAZ-00WJTA0 8TB                     | 1         | 1.16%   |
| WDC WD80EDAZ-11TA3A0 8TB                     | 1         | 1.16%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 1.16%   |
| WDC WD5000AAKX-75U6AA0 500GB                 | 1         | 1.16%   |
| WDC WD5000AAKX-001CA0 500GB                  | 1         | 1.16%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 1.16%   |
| WDC WD2500AAJS-22VTA0 250GB                  | 1         | 1.16%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1         | 1.16%   |
| WDC WD120EDAZ-11F3RA0 12TB                   | 1         | 1.16%   |
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 1.16%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1.16%   |
| WDC WD100EMAZ-00WJTA0 10TB                   | 1         | 1.16%   |
| WDC WD1001FALS-00J7B0 1TB                    | 1         | 1.16%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB         | 1         | 1.16%   |
| Unknown SD/MMC/MS PRO 16GB                   | 1         | 1.16%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.16%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 1.16%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 1.16%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 1.16%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.16%   |
| Toshiba MG07ACA12TE 12TB                     | 1         | 1.16%   |
| Toshiba MG04ACA400E 4TB                      | 1         | 1.16%   |
| Toshiba MG03ACA400 4TB                       | 1         | 1.16%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1.16%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1.16%   |
| StoreJet Disk 2TB                            | 1         | 1.16%   |
| SK Hynix SHGS31-1000GS-2 1TB SSD             | 1         | 1.16%   |
| SK Hynix SH920 2.5 7MM 256GB SSD             | 1         | 1.16%   |
| SK Hynix NVMe SSD Drive 512GB                | 1         | 1.16%   |
| SK Hynix BC511 NVMe 512GB                    | 1         | 1.16%   |
| Seagate ST91000640SS 1TB                     | 1         | 1.16%   |
| Seagate ST8000DM004-2CX188 8TB               | 1         | 1.16%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 1         | 1.16%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1.16%   |
| Seagate ST4000NM0033-9ZM170 4TB              | 1         | 1.16%   |
| Seagate ST4000DM004-2CV104 4TB               | 1         | 1.16%   |
| Seagate ST3160318AS 160GB                    | 1         | 1.16%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1.16%   |
| Seagate ST1000VX005-2EZ102 1TB               | 1         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.16%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1.16%   |
| Seagate BUP Slim BL 2TB                      | 1         | 1.16%   |
| SanDisk SSD U110 16GB                        | 1         | 1.16%   |
| Samsung SSD 980 PRO 1TB                      | 1         | 1.16%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 1.16%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 1.16%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 1.16%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 1.16%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 1.16%   |
| Samsung SSD 860 EVO 1TB                      | 1         | 1.16%   |
| Samsung NVMe SSD Drive 256GB                 | 1         | 1.16%   |
| Samsung MZVLB512HBJQ-000L7 512GB             | 1         | 1.16%   |
| Samsung MZVLB512HBJQ-000L2 512GB             | 1         | 1.16%   |
| Samsung MZNLN512HAJQ-000H1 512GB SSD         | 1         | 1.16%   |
| Samsung HD103SJ 1TB                          | 1         | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 39     | 34.29%  |
| WDC                 | 9         | 20     | 25.71%  |
| Toshiba             | 5         | 5      | 14.29%  |
| Hitachi             | 3         | 4      | 8.57%   |
| Unknown             | 1         | 1      | 2.86%   |
| StoreJet            | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| IBM                 | 1         | 1      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 28.57%  |
| WDC                 | 2         | 2      | 9.52%   |
| Toshiba             | 2         | 2      | 9.52%   |
| SK Hynix            | 2         | 2      | 9.52%   |
| SanDisk             | 1         | 1      | 4.76%   |
| PNY                 | 1         | 1      | 4.76%   |
| LITEONIT            | 1         | 1      | 4.76%   |
| LITEON              | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| Dogfish             | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |
| Corsair             | 1         | 1      | 4.76%   |
| China               | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 25        | 74     | 40.32%  |
| SSD     | 18        | 22     | 29.03%  |
| NVMe    | 16        | 20     | 25.81%  |
| MMC     | 2         | 2      | 3.23%   |
| Unknown | 1         | 1      | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 93     | 61.4%   |
| NVMe | 16        | 20     | 28.07%  |
| SAS  | 4         | 4      | 7.02%   |
| MMC  | 2         | 2      | 3.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 32     | 40.82%  |
| 0.51-1.0   | 15        | 21     | 30.61%  |
| 1.01-2.0   | 6         | 7      | 12.24%  |
| 3.01-4.0   | 4         | 20     | 8.16%   |
| 10.01-20.0 | 2         | 3      | 4.08%   |
| 2.01-3.0   | 1         | 1      | 2.04%   |
| 4.01-10.0  | 1         | 12     | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 27.66%  |
| 251-500        | 8         | 17.02%  |
| 501-1000       | 8         | 17.02%  |
| More than 3000 | 6         | 12.77%  |
| 1001-2000      | 5         | 10.64%  |
| 2001-3000      | 3         | 6.38%   |
| 51-100         | 2         | 4.26%   |
| 1-20           | 1         | 2.13%   |
| Unknown        | 1         | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 15        | 31.91%  |
| 21-50          | 11        | 23.4%   |
| 51-100         | 5         | 10.64%  |
| 101-250        | 4         | 8.51%   |
| More than 3000 | 3         | 6.38%   |
| 501-1000       | 3         | 6.38%   |
| 251-500        | 2         | 4.26%   |
| 1001-2000      | 2         | 4.26%   |
| 2001-3000      | 1         | 2.13%   |
| Unknown        | 1         | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 12.5%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 12.5%   |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 12.5%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 12.5%   |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 12.5%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 12.5%   |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 12.5%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 13     | 37.5%   |
| Hitachi | 2         | 2      | 25%     |
| WDC     | 1         | 4      | 12.5%   |
| IBM     | 1         | 1      | 12.5%   |
| Corsair | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 13     | 42.86%  |
| Hitachi | 2         | 2      | 28.57%  |
| WDC     | 1         | 4      | 14.29%  |
| IBM     | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 20     | 87.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Works    | 24        | 60     | 43.64%  |
| Detected | 23        | 38     | 41.82%  |
| Malfunc  | 8         | 21     | 14.55%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 33        | 53.23%  |
| AMD                          | 8         | 12.9%   |
| Samsung Electronics          | 4         | 6.45%   |
| LSI Logic / Symbios Logic    | 3         | 4.84%   |
| Phison Electronics           | 2         | 3.23%   |
| Broadcom / LSI               | 2         | 3.23%   |
| Union Memory (Shenzhen)      | 1         | 1.61%   |
| Toshiba America Info Systems | 1         | 1.61%   |
| SK Hynix                     | 1         | 1.61%   |
| Sandisk                      | 1         | 1.61%   |
| Realtek Semiconductor        | 1         | 1.61%   |
| Micron/Crucial Technology    | 1         | 1.61%   |
| Marvell Technology Group     | 1         | 1.61%   |
| Kingston Technology Company  | 1         | 1.61%   |
| ASMedia Technology           | 1         | 1.61%   |
| Adaptec                      | 1         | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 9.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 5.26%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 3.95%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 3.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 2.63%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 2.63%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 2.63%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 2.63%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 2.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 2.63%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 1.32%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 1.32%   |
| SK Hynix BC511                                                                          | 1         | 1.32%   |
| Sandisk Non-Volatile memory controller                                                  | 1         | 1.32%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.32%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 1.32%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1         | 1.32%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.32%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 1.32%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 1.32%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                               | 1         | 1.32%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.32%   |
| Intel SSD 660P Series                                                                   | 1         | 1.32%   |
| Intel PCIe Data Center SSD                                                              | 1         | 1.32%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                                | 1         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.32%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.32%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 1.32%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 1.32%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 1.32%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 1.32%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 1.32%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.32%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1         | 1.32%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.32%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 1.32%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1         | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.32%   |
| Adaptec ASC-39320A U320                                                                 | 1         | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 42.19%  |
| NVMe | 16        | 25%     |
| IDE  | 11        | 17.19%  |
| RAID | 7         | 10.94%  |
| SAS  | 2         | 3.13%   |
| SCSI | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 74.47%  |
| AMD    | 11        | 23.4%   |
| ARM    | 1         | 2.13%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Xeon CPU L5530 @ 2.40GHz                 | 2         | 4.26%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 2         | 4.26%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2         | 4.26%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz           | 1         | 2.13%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz             | 1         | 2.13%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1         | 2.13%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1         | 2.13%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz             | 1         | 2.13%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1         | 2.13%   |
| Intel Xeon CPU E3110 @ 3.00GHz                 | 1         | 2.13%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz            | 1         | 2.13%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1         | 2.13%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 1         | 2.13%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz             | 1         | 2.13%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz             | 1         | 2.13%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1         | 2.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 2.13%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz             | 1         | 2.13%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 2.13%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 2.13%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1         | 2.13%   |
| Intel Core i7-10610U CPU @ 1.80GHz             | 1         | 2.13%   |
| Intel Core i5-8365U CPU @ 1.60GHz              | 1         | 2.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 2.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 2.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 1         | 2.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 2.13%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1         | 2.13%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1         | 2.13%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 2.13%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 2.13%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1         | 2.13%   |
| ARM Processor                                  | 1         | 2.13%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1         | 2.13%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 2.13%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 1         | 2.13%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 2.13%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1         | 2.13%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics     | 1         | 2.13%   |
| AMD Ryzen 5 4600H with Radeon Graphics         | 1         | 2.13%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 2.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 2.13%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1         | 2.13%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 14        | 29.79%  |
| Intel Xeon              | 8         | 17.02%  |
| Intel Core i5           | 5         | 10.64%  |
| AMD Ryzen 7             | 3         | 6.38%   |
| AMD Ryzen 5             | 3         | 6.38%   |
| Other                   | 2         | 4.26%   |
| Intel Celeron           | 2         | 4.26%   |
| Intel Xeon Silver       | 1         | 2.13%   |
| Intel Xeon Gold         | 1         | 2.13%   |
| Intel Pentium Dual-Core | 1         | 2.13%   |
| Intel Core i3           | 1         | 2.13%   |
| Intel Core 2 Quad       | 1         | 2.13%   |
| Intel Core 2 Duo        | 1         | 2.13%   |
| AMD Ryzen Threadripper  | 1         | 2.13%   |
| AMD Ryzen 9             | 1         | 2.13%   |
| AMD Ryzen 5 PRO         | 1         | 2.13%   |
| AMD Ryzen 3             | 1         | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 20        | 42.55%  |
| 2      | 9         | 19.15%  |
| 8      | 8         | 17.02%  |
| 6      | 4         | 8.51%   |
| 16     | 2         | 4.26%   |
| 12     | 2         | 4.26%   |
| 32     | 1         | 2.13%   |
| 24     | 1         | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 87.23%  |
| 2      | 6         | 12.77%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 68.09%  |
| 1      | 15        | 31.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 47        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 7         | 14.89%  |
| 0x506e3    | 3         | 6.38%   |
| 0x206a7    | 3         | 6.38%   |
| 0x806ec    | 2         | 4.26%   |
| 0x40651    | 2         | 4.26%   |
| 0x306e4    | 2         | 4.26%   |
| 0x106a5    | 2         | 4.26%   |
| 0x10676    | 2         | 4.26%   |
| 0x08600104 | 2         | 4.26%   |
| Unknown    | 2         | 4.26%   |
| 0xa0655    | 1         | 2.13%   |
| 0xa0652    | 1         | 2.13%   |
| 0x706a8    | 1         | 2.13%   |
| 0x50657    | 1         | 2.13%   |
| 0x50654    | 1         | 2.13%   |
| 0x406e3    | 1         | 2.13%   |
| 0x306a9    | 1         | 2.13%   |
| 0x206d7    | 1         | 2.13%   |
| 0x206c2    | 1         | 2.13%   |
| 0x1067a    | 1         | 2.13%   |
| 0x10677    | 1         | 2.13%   |
| 0x0a50000c | 1         | 2.13%   |
| 0x0a201009 | 1         | 2.13%   |
| 0x0870100a | 1         | 2.13%   |
| 0x08608103 | 1         | 2.13%   |
| 0x08301039 | 1         | 2.13%   |
| 0x08108109 | 1         | 2.13%   |
| 0x08108102 | 1         | 2.13%   |
| 0x0800820d | 1         | 2.13%   |
| 0x06006705 | 1         | 2.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 10        | 21.28%  |
| Skylake       | 6         | 12.77%  |
| Zen 2         | 4         | 8.51%   |
| SandyBridge   | 4         | 8.51%   |
| Penryn        | 4         | 8.51%   |
| Zen+          | 3         | 6.38%   |
| IvyBridge     | 3         | 6.38%   |
| Zen 3         | 2         | 4.26%   |
| Nehalem       | 2         | 4.26%   |
| KabyLake      | 2         | 4.26%   |
| CometLake     | 2         | 4.26%   |
| Unknown       | 2         | 4.26%   |
| Westmere      | 1         | 2.13%   |
| Goldmont plus | 1         | 2.13%   |
| Excavator     | 1         | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 21        | 36.21%  |
| Intel                      | 21        | 36.21%  |
| AMD                        | 10        | 17.24%  |
| Matrox Electronics Systems | 3         | 5.17%   |
| ASPEED Technology          | 3         | 5.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 5.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 5.17%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3         | 5.17%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 3.45%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 2         | 3.45%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 3.45%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 3.45%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 1.72%   |
| Nvidia TU117GL [T600]                                                       | 1         | 1.72%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.72%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 1.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 1.72%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 1.72%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.72%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 1.72%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 1.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.72%   |
| Nvidia GK107M [GeForce GT 755M]                                             | 1         | 1.72%   |
| Nvidia GK107GL [Quadro K600]                                                | 1         | 1.72%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.72%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 1.72%   |
| Nvidia GK104GL [GRID K2]                                                    | 1         | 1.72%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 1.72%   |
| Matrox Electronics Systems G200eR2                                          | 1         | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.72%   |
| Intel HD Graphics P530                                                      | 1         | 1.72%   |
| Intel HD Graphics 530                                                       | 1         | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 1.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1         | 1.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1         | 1.72%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                     | 1         | 1.72%   |
| AMD Renoir                                                                  | 1         | 1.72%   |
| AMD Lucienne                                                                | 1         | 1.72%   |
| AMD ES1000                                                                  | 1         | 1.72%   |
| AMD Cezanne                                                                 | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Nvidia      | 11        | 23.4%   |
| 1 x Intel       | 11        | 23.4%   |
| Intel + Nvidia  | 8         | 17.02%  |
| 1 x AMD         | 8         | 17.02%  |
| 1 x ASPEED      | 3         | 6.38%   |
| 1 x Matrox      | 2         | 4.26%   |
| Other           | 1         | 2.13%   |
| Nvidia + Matrox | 1         | 2.13%   |
| Intel + AMD     | 1         | 2.13%   |
| AMD + Nvidia    | 1         | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 34        | 72.34%  |
| Proprietary | 10        | 21.28%  |
| Unknown     | 3         | 6.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 46.81%  |
| 0.01-0.5   | 8         | 17.02%  |
| 1.01-2.0   | 7         | 14.89%  |
| 3.01-4.0   | 4         | 8.51%   |
| 5.01-6.0   | 3         | 6.38%   |
| 0.51-1.0   | 2         | 4.26%   |
| 8.01-16.0  | 1         | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 10        | 20%     |
| Samsung Electronics | 5         | 10%     |
| AU Optronics        | 5         | 10%     |
| LG Display          | 4         | 8%      |
| Goldstar            | 4         | 8%      |
| BOE                 | 4         | 8%      |
| Chimei Innolux      | 3         | 6%      |
| Philips             | 2         | 4%      |
| Iiyama              | 2         | 4%      |
| AOC                 | 2         | 4%      |
| Sony                | 1         | 2%      |
| PANDA               | 1         | 2%      |
| Panasonic           | 1         | 2%      |
| Lenovo              | 1         | 2%      |
| IBM                 | 1         | 2%      |
| Hewlett-Packard     | 1         | 2%      |
| ASUSTek Computer    | 1         | 2%      |
| ADR                 | 1         | 2%      |
| Acer                | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony LG TV SNY045B 1920x540                                           | 1         | 1.89%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 1.89%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 1.89%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.89%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch    | 1         | 1.89%   |
| Philips PHL 272S4L PHL08E4 1920x1080 600x340mm 27.2-inch              | 1         | 1.89%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 1.89%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.89%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.89%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 1.89%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.89%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.89%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.89%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.89%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 1.89%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1         | 1.89%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1         | 1.89%   |
| IBM RSA2 IBM029A 1024x768 300x225mm 14.8-inch                         | 1         | 1.89%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1         | 1.89%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.89%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.89%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.89%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.89%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 1         | 1.89%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 1.89%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 1.89%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.89%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                      | 1         | 1.89%   |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                       | 1         | 1.89%   |
| Dell LCD Monitor U2414H 3840x1080                                     | 1         | 1.89%   |
| Dell LCD Monitor U2414H                                               | 1         | 1.89%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                     | 1         | 1.89%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 1.89%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1         | 1.89%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 1         | 1.89%   |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                 | 1         | 1.89%   |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 1.89%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 1.89%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                 | 1         | 1.89%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 1.89%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch          | 1         | 1.89%   |
| AOC 2279WH AOC2279 1920x1080 477x268mm 21.5-inch                      | 1         | 1.89%   |
| AOC 1620 AOC1620 1366x768 340x190mm 15.3-inch                         | 1         | 1.89%   |
| ADR KVM-via-IP ADR0219 1280x1024                                      | 1         | 1.89%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 44.44%  |
| 1600x900 (HD+)     | 4         | 8.89%   |
| 1280x1024 (SXGA)   | 3         | 6.67%   |
| 3840x2160 (4K)     | 2         | 4.44%   |
| 3840x1080          | 2         | 4.44%   |
| 1920x1200 (WUXGA)  | 2         | 4.44%   |
| 1680x1050 (WSXGA+) | 2         | 4.44%   |
| 1440x900 (WXGA+)   | 2         | 4.44%   |
| Unknown            | 2         | 4.44%   |
| 3440x1440          | 1         | 2.22%   |
| 2560x1440 (QHD)    | 1         | 2.22%   |
| 2560x1080          | 1         | 2.22%   |
| 1920x540           | 1         | 2.22%   |
| 1366x768 (WXGA)    | 1         | 2.22%   |
| 1024x768 (XGA)     | 1         | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 20%     |
| 14      | 7         | 14%     |
| 27      | 6         | 12%     |
| 17      | 4         | 8%      |
| 23      | 3         | 6%      |
| 21      | 3         | 6%      |
| 19      | 3         | 6%      |
| 34      | 2         | 4%      |
| 24      | 2         | 4%      |
| 13      | 2         | 4%      |
| Unknown | 2         | 4%      |
| 65      | 1         | 2%      |
| 48      | 1         | 2%      |
| 31      | 1         | 2%      |
| 28      | 1         | 2%      |
| 22      | 1         | 2%      |
| 20      | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 40%     |
| 501-600     | 11        | 22%     |
| 401-500     | 9         | 18%     |
| 701-800     | 2         | 4%      |
| 351-400     | 2         | 4%      |
| 1001-1500   | 2         | 4%      |
| Unknown     | 2         | 4%      |
| 601-700     | 1         | 2%      |
| 201-300     | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 28        | 66.67%  |
| 16/10   | 4         | 9.52%   |
| 5/4     | 3         | 7.14%   |
| 3/2     | 2         | 4.76%   |
| 21/9    | 2         | 4.76%   |
| 4/3     | 1         | 2.38%   |
| 32/9    | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 20.41%  |
| 81-90          | 8         | 16.33%  |
| 201-250        | 7         | 14.29%  |
| 301-350        | 6         | 12.24%  |
| 151-200        | 5         | 10.2%   |
| 351-500        | 4         | 8.16%   |
| 141-150        | 2         | 4.08%   |
| 121-130        | 2         | 4.08%   |
| Unknown        | 2         | 4.08%   |
| More than 1000 | 1         | 2.04%   |
| 501-1000       | 1         | 2.04%   |
| 91-100         | 1         | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 19        | 38.78%  |
| 51-100        | 19        | 38.78%  |
| 101-120       | 6         | 12.24%  |
| Unknown       | 2         | 4.08%   |
| More than 240 | 1         | 2.04%   |
| 1-50          | 1         | 2.04%   |
| 161-240       | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 25        | 53.19%  |
| 0     | 10        | 21.28%  |
| 2     | 9         | 19.15%  |
| 3     | 2         | 4.26%   |
| 4     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 29        | 42.65%  |
| Realtek Semiconductor     | 20        | 29.41%  |
| Broadcom                  | 5         | 7.35%   |
| Qualcomm Atheros          | 4         | 5.88%   |
| Mellanox Technologies     | 3         | 4.41%   |
| Solarflare Communications | 1         | 1.47%   |
| Microsoft                 | 1         | 1.47%   |
| MEDIATEK                  | 1         | 1.47%   |
| Marvell Technology Group  | 1         | 1.47%   |
| Linksys                   | 1         | 1.47%   |
| BUFFALO                   | 1         | 1.47%   |
| Broadcom Limited          | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 18        | 22.22%  |
| Intel Wireless 7260                                                                                                    | 4         | 4.94%   |
| Intel Ethernet Connection I217-LM                                                                                      | 4         | 4.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 4         | 4.94%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 3         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 2         | 2.47%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 2.47%   |
| Intel Wireless 8260                                                                                                    | 2         | 2.47%   |
| Intel Wireless 3165                                                                                                    | 2         | 2.47%   |
| Intel I211 Gigabit Network Connection                                                                                  | 2         | 2.47%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 2.47%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 2         | 2.47%   |
| Solarflare SFC9020 10G Ethernet Controller                                                                             | 1         | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 1         | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                             | 1         | 1.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1         | 1.23%   |
| Realtek 802.11ac NIC                                                                                                   | 1         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 1         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                                              | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                                       | 1         | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                       | 1         | 1.23%   |
| Microsoft Xbox 360 Wireless Adapter                                                                                    | 1         | 1.23%   |
| Mellanox MT27700 Family [ConnectX-4]                                                                                   | 1         | 1.23%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 1         | 1.23%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                                                | 1         | 1.23%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                                                      | 1         | 1.23%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                                    | 1         | 1.23%   |
| Intel Wireless 7265                                                                                                    | 1         | 1.23%   |
| Intel Wireless 3160                                                                                                    | 1         | 1.23%   |
| Intel Ultimate N WiFi Link 5300                                                                                        | 1         | 1.23%   |
| Intel Ethernet Virtual Function 700 Series                                                                             | 1         | 1.23%   |
| Intel Ethernet Controller 10G X550T                                                                                    | 1         | 1.23%   |
| Intel Ethernet Connection I217-V                                                                                       | 1         | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                        | 1         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 1         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 1         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 1         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 1         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                                                                               | 1         | 1.23%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                                                               | 1         | 1.23%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                                                                      | 1         | 1.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                                                      | 1         | 1.23%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                                                                | 1         | 1.23%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet                                                           | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 67.86%  |
| Qualcomm Atheros      | 3         | 10.71%  |
| Realtek Semiconductor | 2         | 7.14%   |
| Microsoft             | 1         | 3.57%   |
| MEDIATEK              | 1         | 3.57%   |
| Linksys               | 1         | 3.57%   |
| BUFFALO               | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 4         | 13.79%  |
| Intel Wi-Fi 6 AX200                                           | 3         | 10.34%  |
| Intel Wireless 8260                                           | 2         | 6.9%    |
| Intel Wireless 3165                                           | 2         | 6.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 3.45%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 3.45%   |
| Realtek 802.11ac NIC                                          | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 3.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 3.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 1         | 3.45%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1         | 3.45%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 3.45%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter           | 1         | 3.45%   |
| Intel Wireless 7265                                           | 1         | 3.45%   |
| Intel Wireless 3160                                           | 1         | 3.45%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 3.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 3.45%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 3.45%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]      | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 20        | 43.48%  |
| Intel                     | 17        | 36.96%  |
| Broadcom                  | 5         | 10.87%  |
| Solarflare Communications | 1         | 2.17%   |
| Qualcomm Atheros          | 1         | 2.17%   |
| Marvell Technology Group  | 1         | 2.17%   |
| Broadcom Limited          | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 36.73%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 8.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 8.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.08%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.08%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 4.08%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 4.08%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 2.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 2.04%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 2.04%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 2.04%   |
| Intel Ethernet Controller 10G X550T                               | 1         | 2.04%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.04%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.04%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.04%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 1         | 2.04%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet      | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 44        | 58.67%  |
| WiFi     | 28        | 37.33%  |
| Unknown  | 3         | 4%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 66.67%  |
| WiFi     | 18        | 31.58%  |
| Unknown  | 1         | 1.75%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 51.06%  |
| 1     | 16        | 34.04%  |
| 5     | 2         | 4.26%   |
| 3     | 2         | 4.26%   |
| 66    | 1         | 2.13%   |
| 4     | 1         | 2.13%   |
| 0     | 1         | 2.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 37        | 78.72%  |
| Yes  | 10        | 21.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 70.83%  |
| Broadcom                        | 2         | 8.33%   |
| Realtek Semiconductor           | 1         | 4.17%   |
| Qualcomm Atheros Communications | 1         | 4.17%   |
| IMC Networks                    | 1         | 4.17%   |
| Foxconn / Hon Hai               | 1         | 4.17%   |
| Cambridge Silicon Radio         | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 45.83%  |
| Intel AX200 Bluetooth                               | 3         | 12.5%   |
| Intel Bluetooth Device                              | 2         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4.17%   |
| IMC Networks Bluetooth Device                       | 1         | 4.17%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 4.17%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 28        | 43.08%  |
| Nvidia              | 17        | 26.15%  |
| AMD                 | 12        | 18.46%  |
| Logitech            | 2         | 3.08%   |
| C-Media Electronics | 2         | 3.08%   |
| Hewlett-Packard     | 1         | 1.54%   |
| GN Netcom           | 1         | 1.54%   |
| Conexant Systems    | 1         | 1.54%   |
| ASUSTek Computer    | 1         | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 8.86%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 7.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 6.33%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 5.06%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.53%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.53%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 2.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.53%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 2.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 2.53%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.53%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2         | 2.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.53%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.27%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 1.27%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.27%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.27%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.27%   |
| Logitech Stereo H650e                                                      | 1         | 1.27%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.27%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.27%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.27%   |
| GN Netcom Jabra Evolve 65                                                  | 1         | 1.27%   |
| Conexant Systems HP Dock Audio                                             | 1         | 1.27%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 1.27%   |
| C-Media Electronics Auna Mic CM900                                         | 1         | 1.27%   |
| ASUSTek Computer USB Audio                                                 | 1         | 1.27%   |
| AMD High Definition Audio Controller                                       | 1         | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 29.63%  |
| Micron Technology   | 8         | 29.63%  |
| SK Hynix            | 3         | 11.11%  |
| G.Skill             | 3         | 11.11%  |
| Unknown             | 2         | 7.41%   |
| Kingston            | 1         | 3.7%    |
| Crucial             | 1         | 3.7%    |
| Corsair             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 3.7%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                              | 1         | 3.7%    |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s               | 1         | 3.7%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                | 1         | 3.7%    |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s            | 1         | 3.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 3.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 3.7%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                | 1         | 3.7%    |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s                  | 1         | 3.7%    |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 3.7%    |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 3.7%    |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                   | 1         | 3.7%    |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 3.7%    |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                              | 1         | 3.7%    |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                   | 1         | 3.7%    |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                    | 1         | 3.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s            | 1         | 3.7%    |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s                  | 1         | 3.7%    |
| Micron RAM 3138485446313238373241592D3636374631 1GB DIMM DDR2 667MT/s | 1         | 3.7%    |
| Micron RAM 18ASF2G72AZ-2G3A1 16GB DIMM DDR4 2400MT/s                  | 1         | 3.7%    |
| Micron RAM 18ASF1G72PDZ-2G6F1 8GB DIMM DDR4 2666MT/s                  | 1         | 3.7%    |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 1600MT/s                | 1         | 3.7%    |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s                   | 1         | 3.7%    |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s                  | 1         | 3.7%    |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s                    | 1         | 3.7%    |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s            | 1         | 3.7%    |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s                  | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 50%     |
| DDR3   | 10        | 38.46%  |
| DDR2   | 2         | 7.69%   |
| LPDDR4 | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 18        | 69.23%  |
| SODIMM       | 7         | 26.92%  |
| Row Of Chips | 1         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 46.15%  |
| 16384 | 4         | 15.38%  |
| 1024  | 4         | 15.38%  |
| 32768 | 3         | 11.54%  |
| 4096  | 2         | 7.69%   |
| 2048  | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 6         | 22.22%  |
| 2667  | 4         | 14.81%  |
| 1600  | 4         | 14.81%  |
| 2666  | 2         | 7.41%   |
| 2400  | 2         | 7.41%   |
| 1066  | 2         | 7.41%   |
| 667   | 2         | 7.41%   |
| 4266  | 1         | 3.7%    |
| 2933  | 1         | 3.7%    |
| 2200  | 1         | 3.7%    |
| 1866  | 1         | 3.7%    |
| 1800  | 1         | 3.7%    |

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
| Chicony Electronics         | 6         | 27.27%  |
| Syntek                      | 4         | 18.18%  |
| Logitech                    | 3         | 13.64%  |
| Realtek Semiconductor       | 2         | 9.09%   |
| IMC Networks                | 2         | 9.09%   |
| Quanta                      | 1         | 4.55%   |
| Luxvisions Innotech Limited | 1         | 4.55%   |
| Lenovo                      | 1         | 4.55%   |
| Intel                       | 1         | 4.55%   |
| Huawei Technologies         | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 4         | 18.18%  |
| Syntek Lenovo EasyCamera                 | 2         | 9.09%   |
| Syntek Integrated Camera                 | 2         | 9.09%   |
| Realtek Integrated_Webcam_HD             | 1         | 4.55%   |
| Realtek EasyCamera                       | 1         | 4.55%   |
| Quanta HP Webcam                         | 1         | 4.55%   |
| Luxvisions Innotech Limited HP HD Camera | 1         | 4.55%   |
| Logitech Webcam C270                     | 1         | 4.55%   |
| Logitech HD Pro Webcam C920              | 1         | 4.55%   |
| Logitech BRIO Ultra HD Webcam            | 1         | 4.55%   |
| Lenovo UVC Camera                        | 1         | 4.55%   |
| Intel RealSense 3D Camera (Front F200)   | 1         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 4.55%   |
| IMC Networks TOSHIBA Web Camera - HD     | 1         | 4.55%   |
| Huawei UVC Camera                        | 1         | 4.55%   |
| Chicony HP HD Camera                     | 1         | 4.55%   |
| Chicony HD WebCam                        | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Synaptics        | 2         | 33.33%  |
| AuthenTec        | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 16.67%  |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 16.67%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| AuthenTec AES2810                                         | 1         | 16.67%  |
| Unknown                                                   | 1         | 16.67%  |

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
| 0     | 27        | 57.45%  |
| 1     | 14        | 29.79%  |
| 2     | 4         | 8.51%   |
| 5     | 1         | 2.13%   |
| 4     | 1         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 23.08%  |
| Net/wireless             | 5         | 19.23%  |
| Graphics card            | 3         | 11.54%  |
| Communication controller | 3         | 11.54%  |
| Unassigned class         | 2         | 7.69%   |
| Network                  | 2         | 7.69%   |
| Chipcard                 | 2         | 7.69%   |
| Net/ethernet             | 1         | 3.85%   |
| Multimedia controller    | 1         | 3.85%   |
| Card reader              | 1         | 3.85%   |

