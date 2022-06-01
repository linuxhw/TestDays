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

Total: 61

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Rocky Linux 8.5 | 28        | 57.14%  |
| Rocky Linux 8.4 | 18        | 36.73%  |
| Rocky Linux 8.3 | 2         | 4.08%   |
| Rocky Linux 8.6 | 1         | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 49        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64 | 13        | 26.53%  |
| 4.18.0-348.7.1.el8_5.x86_64  | 8         | 16.33%  |
| 4.18.0-305.10.2.el8_4.x86_64 | 5         | 10.2%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 3         | 6.12%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 2         | 4.08%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2         | 4.08%   |
| 4.18.0-305.el8.x86_64        | 2         | 4.08%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 2         | 4.08%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 2         | 4.08%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 2         | 4.08%   |
| 4.18.0-240.22.1.el8.x86_64   | 2         | 4.08%   |
| 5.4.157-1.el8.elrepo.x86_64  | 1         | 2.04%   |
| 5.14.1-1.el8.elrepo.x86_64   | 1         | 2.04%   |
| 5.10.52-v8.1.el8             | 1         | 2.04%   |
| 4.18.0-372.9.1.el8.x86_64    | 1         | 2.04%   |
| 4.18.0-348.el8.0.2.x86_64    | 1         | 2.04%   |
| 4.18.0-348.23.1.el8_5.x86_64 | 1         | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 46        | 93.88%  |
| 5.4.157 | 1         | 2.04%   |
| 5.14.1  | 1         | 2.04%   |
| 5.10.52 | 1         | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 46        | 93.88%  |
| 5.4     | 1         | 2.04%   |
| 5.14    | 1         | 2.04%   |
| 5.10    | 1         | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 48        | 97.96%  |
| aarch64 | 1         | 2.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 32        | 65.31%  |
| Unknown       | 7         | 14.29%  |
| KDE5          | 4         | 8.16%   |
| MATE          | 2         | 4.08%   |
| GNOME Classic | 2         | 4.08%   |
| XFCE          | 1         | 2.04%   |
| X-Cinnamon    | 1         | 2.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 26        | 53.06%  |
| X11     | 18        | 36.73%  |
| Unknown | 5         | 10.2%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 25        | 51.02%  |
| GDM     | 19        | 38.78%  |
| SDDM    | 3         | 6.12%   |
| LightDM | 2         | 4.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 29        | 59.18%  |
| en_IL   | 3         | 6.12%   |
| ru_RU   | 2         | 4.08%   |
| en_ZA   | 2         | 4.08%   |
| en_SG   | 2         | 4.08%   |
| en_AU   | 2         | 4.08%   |
| de_DE   | 2         | 4.08%   |
| pl_PL   | 1         | 2.04%   |
| ja_JP   | 1         | 2.04%   |
| it_IT   | 1         | 2.04%   |
| es_CO   | 1         | 2.04%   |
| en_CA   | 1         | 2.04%   |
| af_ZA   | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 25        | 51.02%  |
| BIOS | 24        | 48.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 38        | 77.55%  |
| Ext4 | 11        | 22.45%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 42.86%  |
| GPT     | 18        | 36.73%  |
| MBR     | 10        | 20.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 89.8%   |
| Yes       | 5         | 10.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 91.84%  |
| Yes       | 4         | 8.16%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 12        | 24.49%  |
| Dell                    | 12        | 24.49%  |
| ASUSTek Computer        | 5         | 10.2%   |
| Hewlett-Packard         | 4         | 8.16%   |
| Gigabyte Technology     | 3         | 6.12%   |
| Toshiba                 | 2         | 4.08%   |
| Supermicro              | 2         | 4.08%   |
| Raspberry Pi Foundation | 1         | 2.04%   |
| NCR                     | 1         | 2.04%   |
| MSI                     | 1         | 2.04%   |
| Intel                   | 1         | 2.04%   |
| IBM                     | 1         | 2.04%   |
| Google                  | 1         | 2.04%   |
| AZW                     | 1         | 2.04%   |
| ASRock                  | 1         | 2.04%   |
| Acer                    | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge R610                      | 2         | 4.08%   |
| Dell OptiPlex 9020                       | 2         | 4.08%   |
| Toshiba TECRA W50-A                      | 1         | 2.04%   |
| Toshiba Satellite E45-B                  | 1         | 2.04%   |
| Supermicro SYS-5029P-WTR                 | 1         | 2.04%   |
| Supermicro Super Server                  | 1         | 2.04%   |
| RPi Raspberry Pi                         | 1         | 2.04%   |
| NCR xxxx-xxxx-xxxx                       | 1         | 2.04%   |
| MSI MS-7917                              | 1         | 2.04%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 2.04%   |
| Lenovo ThinkPad W500 406132G             | 1         | 2.04%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 2.04%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 2.04%   |
| Lenovo ThinkCentre M72e 36601Y8          | 1         | 2.04%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 2.04%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 2.04%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU        | 1         | 2.04%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 2.04%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 2.04%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 2.04%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 2.04%   |
| Intel S2600WFT                           | 1         | 2.04%   |
| IBM System x3200 M2 -[4368IGS]-          | 1         | 2.04%   |
| HP ZBook 15 G3                           | 1         | 2.04%   |
| HP Z600 Workstation                      | 1         | 2.04%   |
| HP Laptop 17-ca1xxx                      | 1         | 2.04%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 2.04%   |
| Google Panther                           | 1         | 2.04%   |
| Gigabyte X570 AORUS ULTRA                | 1         | 2.04%   |
| Gigabyte H87-D3H                         | 1         | 2.04%   |
| Gigabyte G41MT-USB3                      | 1         | 2.04%   |
| Dell Vostro 3681                         | 1         | 2.04%   |
| Dell Precision Tower 7810                | 1         | 2.04%   |
| Dell Precision T7610                     | 1         | 2.04%   |
| Dell Precision T5610                     | 1         | 2.04%   |
| Dell PowerEdge R730xd                    | 1         | 2.04%   |
| Dell PowerEdge R720xd                    | 1         | 2.04%   |
| Dell OptiPlex 390                        | 1         | 2.04%   |
| Dell Latitude 5500                       | 1         | 2.04%   |
| AZW Gemini M                             | 1         | 2.04%   |
| ASUS PRIME TRX40-PRO S                   | 1         | 2.04%   |
| ASUS PRIME B450M-A II                    | 1         | 2.04%   |
| ASUS PRIME B450-PLUS                     | 1         | 2.04%   |
| ASUS P5Q DELUXE                          | 1         | 2.04%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 2.04%   |
| ASRock B450M Pro4                        | 1         | 2.04%   |
| Acer Aspire VN7-591G                     | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 8.16%   |
| Lenovo IdeaPad           | 4         | 8.16%   |
| Dell PowerEdge           | 4         | 8.16%   |
| Dell Precision           | 3         | 6.12%   |
| Dell OptiPlex            | 3         | 6.12%   |
| ASUS PRIME               | 3         | 6.12%   |
| Lenovo Legion            | 2         | 4.08%   |
| Toshiba TECRA            | 1         | 2.04%   |
| Toshiba Satellite        | 1         | 2.04%   |
| Supermicro SYS-5029P-WTR | 1         | 2.04%   |
| Supermicro Super         | 1         | 2.04%   |
| RPi Raspberry            | 1         | 2.04%   |
| NCR xxxx-xxxx-xxxx       | 1         | 2.04%   |
| MSI MS-7917              | 1         | 2.04%   |
| Lenovo ThinkCentre       | 1         | 2.04%   |
| Lenovo IdeaPadFlex       | 1         | 2.04%   |
| Intel S2600WFT           | 1         | 2.04%   |
| IBM System               | 1         | 2.04%   |
| HP ZBook                 | 1         | 2.04%   |
| HP Z600                  | 1         | 2.04%   |
| HP Laptop                | 1         | 2.04%   |
| HP EliteBook             | 1         | 2.04%   |
| Google Panther           | 1         | 2.04%   |
| Gigabyte X570            | 1         | 2.04%   |
| Gigabyte H87-D3H         | 1         | 2.04%   |
| Gigabyte G41MT-USB3      | 1         | 2.04%   |
| Dell Vostro              | 1         | 2.04%   |
| Dell Latitude            | 1         | 2.04%   |
| AZW Gemini               | 1         | 2.04%   |
| ASUS P5Q                 | 1         | 2.04%   |
| ASUS ASUS                | 1         | 2.04%   |
| ASRock B450M             | 1         | 2.04%   |
| Acer Aspire              | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 8         | 16.33%  |
| 2014    | 6         | 12.24%  |
| 2021    | 5         | 10.2%   |
| 2019    | 5         | 10.2%   |
| 2018    | 5         | 10.2%   |
| 2015    | 4         | 8.16%   |
| 2013    | 4         | 8.16%   |
| 2011    | 4         | 8.16%   |
| 2016    | 2         | 4.08%   |
| 2009    | 2         | 4.08%   |
| 2022    | 1         | 2.04%   |
| 2010    | 1         | 2.04%   |
| 2008    | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 21        | 42.86%  |
| Notebook       | 18        | 36.73%  |
| Server         | 8         | 16.33%  |
| System on chip | 1         | 2.04%   |
| Convertible    | 1         | 2.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 49        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 48        | 97.96%  |
| Yes  | 1         | 2.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 12        | 24.49%  |
| 32.01-64.0      | 9         | 18.37%  |
| 16.01-24.0      | 8         | 16.33%  |
| 8.01-16.0       | 8         | 16.33%  |
| 3.01-4.0        | 4         | 8.16%   |
| More than 256.0 | 3         | 6.12%   |
| 1.01-2.0        | 3         | 6.12%   |
| 64.01-256.0     | 2         | 4.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 28.57%  |
| 3.01-4.0  | 13        | 26.53%  |
| 1.01-2.0  | 10        | 20.41%  |
| 4.01-8.0  | 8         | 16.33%  |
| 8.01-16.0 | 2         | 4.08%   |
| 0.51-1.0  | 1         | 2.04%   |
| 0.01-0.5  | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 48.98%  |
| 2      | 11        | 22.45%  |
| 3      | 6         | 12.24%  |
| 4      | 4         | 8.16%   |
| 18     | 1         | 2.04%   |
| 16     | 1         | 2.04%   |
| 14     | 1         | 2.04%   |
| 8      | 1         | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 65.31%  |
| Yes       | 17        | 34.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 93.88%  |
| No        | 3         | 6.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 57.14%  |
| No        | 21        | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 51.02%  |
| Yes       | 24        | 48.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 13        | 26.53%  |
| South Africa | 3         | 6.12%   |
| Singapore    | 3         | 6.12%   |
| Israel       | 3         | 6.12%   |
| Czechia      | 3         | 6.12%   |
| Russia       | 2         | 4.08%   |
| Poland       | 2         | 4.08%   |
| Germany      | 2         | 4.08%   |
| Canada       | 2         | 4.08%   |
| Belgium      | 2         | 4.08%   |
| Australia    | 2         | 4.08%   |
| UK           | 1         | 2.04%   |
| Slovakia     | 1         | 2.04%   |
| Portugal     | 1         | 2.04%   |
| Mexico       | 1         | 2.04%   |
| Malaysia     | 1         | 2.04%   |
| Kazakhstan   | 1         | 2.04%   |
| Japan        | 1         | 2.04%   |
| Italy        | 1         | 2.04%   |
| India        | 1         | 2.04%   |
| France       | 1         | 2.04%   |
| Colombia     | 1         | 2.04%   |
| China        | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 6.12%   |
| Prague                 | 2         | 4.08%   |
| Melbourne              | 2         | 4.08%   |
| Haifa                  | 2         | 4.08%   |
| Centurion              | 2         | 4.08%   |
| Žilina                | 1         | 2.04%   |
| Xi'an                  | 1         | 2.04%   |
| Waltham                | 1         | 2.04%   |
| Toronto                | 1         | 2.04%   |
| St Petersburg          | 1         | 2.04%   |
| Sobral de Monte Agraco | 1         | 2.04%   |
| Senigallia             | 1         | 2.04%   |
| Scarborough            | 1         | 2.04%   |
| Rehovot                | 1         | 2.04%   |
| Progresista            | 1         | 2.04%   |
| Paris                  | 1         | 2.04%   |
| Ottignies              | 1         | 2.04%   |
| Ōtsu                  | 1         | 2.04%   |
| Oakley                 | 1         | 2.04%   |
| Nur-Sultan             | 1         | 2.04%   |
| New York               | 1         | 2.04%   |
| Mossel Bay             | 1         | 2.04%   |
| Moscow                 | 1         | 2.04%   |
| Mequon                 | 1         | 2.04%   |
| Manassas               | 1         | 2.04%   |
| Lebanon                | 1         | 2.04%   |
| Kutno                  | 1         | 2.04%   |
| Krasova                | 1         | 2.04%   |
| Krakow                 | 1         | 2.04%   |
| Johor Bahru            | 1         | 2.04%   |
| Houston                | 1         | 2.04%   |
| Glasgow                | 1         | 2.04%   |
| Fredericton            | 1         | 2.04%   |
| Fredericksburg         | 1         | 2.04%   |
| Forest                 | 1         | 2.04%   |
| Dreieich               | 1         | 2.04%   |
| Corvallis              | 1         | 2.04%   |
| Burlington             | 1         | 2.04%   |
| Bucaramanga            | 1         | 2.04%   |
| Brussels               | 1         | 2.04%   |
| Berlin                 | 1         | 2.04%   |
| Bengaluru              | 1         | 2.04%   |
| Ashburn                | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 13        | 41     | 16.46%  |
| WDC                     | 11        | 23     | 13.92%  |
| Samsung Electronics     | 11        | 13     | 13.92%  |
| Toshiba                 | 9         | 9      | 11.39%  |
| Intel                   | 4         | 5      | 5.06%   |
| Unknown                 | 3         | 3      | 3.8%    |
| SK Hynix                | 3         | 4      | 3.8%    |
| Hitachi                 | 3         | 4      | 3.8%    |
| Phison                  | 2         | 2      | 2.53%   |
| Kingston                | 2         | 2      | 2.53%   |
| Crucial                 | 2         | 2      | 2.53%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.27%   |
| UMIS                    | 1         | 1      | 1.27%   |
| StoreJet                | 1         | 1      | 1.27%   |
| SanDisk                 | 1         | 1      | 1.27%   |
| PNY                     | 1         | 1      | 1.27%   |
| LITEONIT                | 1         | 1      | 1.27%   |
| LITEON                  | 1         | 1      | 1.27%   |
| IBM                     | 1         | 1      | 1.27%   |
| HGST                    | 1         | 1      | 1.27%   |
| Fujitsu                 | 1         | 1      | 1.27%   |
| Dogfish                 | 1         | 1      | 1.27%   |
| Corsair                 | 1         | 1      | 1.27%   |
| China                   | 1         | 1      | 1.27%   |
| Apacer                  | 1         | 1      | 1.27%   |
| AGI                     | 1         | 1      | 1.27%   |
| A-DATA Technology       | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                       | 2         | 2.22%   |
| Seagate ST300MP0005 304GB                    | 2         | 2.22%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1.11%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1.11%   |
| WDC WD80EZZX-11CSGA0 8TB                     | 1         | 1.11%   |
| WDC WD80EMAZ-00WJTA0 8TB                     | 1         | 1.11%   |
| WDC WD80EDAZ-11TA3A0 8TB                     | 1         | 1.11%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 1.11%   |
| WDC WD5000AAKX-75U6AA0 500GB                 | 1         | 1.11%   |
| WDC WD5000AAKX-001CA0 500GB                  | 1         | 1.11%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 1.11%   |
| WDC WD2500AAJS-22VTA0 250GB                  | 1         | 1.11%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1         | 1.11%   |
| WDC WD120EDAZ-11F3RA0 12TB                   | 1         | 1.11%   |
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 1.11%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1.11%   |
| WDC WD100EMAZ-00WJTA0 10TB                   | 1         | 1.11%   |
| WDC WD1001FALS-00J7B0 1TB                    | 1         | 1.11%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB         | 1         | 1.11%   |
| Unknown SD/MMC/MS PRO 999GB                  | 1         | 1.11%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.11%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 1.11%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 1.11%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 1.11%   |
| Toshiba PX05SVB192Y 1.9TB                    | 1         | 1.11%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.11%   |
| Toshiba MG07ACA12TE 12TB                     | 1         | 1.11%   |
| Toshiba MG04ACA400E 4TB                      | 1         | 1.11%   |
| Toshiba MG03ACA400 4TB                       | 1         | 1.11%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1.11%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1.11%   |
| StoreJet Disk 2TB                            | 1         | 1.11%   |
| SK Hynix SHGS31-1000GS-2 1TB SSD             | 1         | 1.11%   |
| SK Hynix SH920 2.5 7MM 256GB SSD             | 1         | 1.11%   |
| SK Hynix NVMe SSD Drive 512GB                | 1         | 1.11%   |
| SK Hynix BC511 NVMe 512GB                    | 1         | 1.11%   |
| Seagate ST91000640SS 1TB                     | 1         | 1.11%   |
| Seagate ST8000DM004-2CX188 8TB               | 1         | 1.11%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 1         | 1.11%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1.11%   |
| Seagate ST4000NM0033-9ZM170 4TB              | 1         | 1.11%   |
| Seagate ST4000DM004-2CV104 4TB               | 1         | 1.11%   |
| Seagate ST3160318AS 160GB                    | 1         | 1.11%   |
| Seagate ST2000NX0433 2TB                     | 1         | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1.11%   |
| Seagate ST1000VX005-2EZ102 1TB               | 1         | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.11%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1.11%   |
| Seagate BUP Slim BL 1TB                      | 1         | 1.11%   |
| SanDisk SSD U110 16GB                        | 1         | 1.11%   |
| Samsung SSD 980 PRO 1TB                      | 1         | 1.11%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 1.11%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 1.11%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 1.11%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 1.11%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 1.11%   |
| Samsung SSD 860 EVO 1TB                      | 1         | 1.11%   |
| Samsung NVMe SSD Drive 256GB                 | 1         | 1.11%   |
| Samsung MZVLB512HBJQ-000L7 512GB             | 1         | 1.11%   |
| Samsung MZVLB512HBJQ-000L2 512GB             | 1         | 1.11%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 41     | 36.11%  |
| WDC                 | 9         | 20     | 25%     |
| Toshiba             | 5         | 5      | 13.89%  |
| Hitachi             | 3         | 4      | 8.33%   |
| Unknown             | 1         | 1      | 2.78%   |
| StoreJet            | 1         | 1      | 2.78%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| IBM                 | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 25%     |
| Toshiba             | 3         | 3      | 12.5%   |
| WDC                 | 2         | 2      | 8.33%   |
| SK Hynix            | 2         | 2      | 8.33%   |
| SanDisk             | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| LITEONIT            | 1         | 1      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |
| Intel               | 1         | 2      | 4.17%   |
| Dogfish             | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| Corsair             | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |
| Apacer              | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 26        | 76     | 40%     |
| SSD     | 20        | 26     | 30.77%  |
| NVMe    | 16        | 19     | 24.62%  |
| MMC     | 2         | 2      | 3.08%   |
| Unknown | 1         | 1      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 99     | 62.71%  |
| NVMe | 16        | 19     | 27.12%  |
| SAS  | 4         | 4      | 6.78%   |
| MMC  | 2         | 2      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 34     | 40.38%  |
| 0.51-1.0   | 17        | 23     | 32.69%  |
| 1.01-2.0   | 6         | 9      | 11.54%  |
| 3.01-4.0   | 4         | 20     | 7.69%   |
| 10.01-20.0 | 2         | 3      | 3.85%   |
| 2.01-3.0   | 1         | 1      | 1.92%   |
| 4.01-10.0  | 1         | 12     | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 28.57%  |
| 251-500        | 8         | 16.33%  |
| 501-1000       | 8         | 16.33%  |
| More than 3000 | 6         | 12.24%  |
| 1001-2000      | 6         | 12.24%  |
| 2001-3000      | 3         | 6.12%   |
| 51-100         | 2         | 4.08%   |
| 1-20           | 1         | 2.04%   |
| Unknown        | 1         | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 16        | 32.65%  |
| 21-50          | 11        | 22.45%  |
| 51-100         | 5         | 10.2%   |
| 101-250        | 4         | 8.16%   |
| More than 3000 | 3         | 6.12%   |
| 251-500        | 3         | 6.12%   |
| 501-1000       | 3         | 6.12%   |
| 1001-2000      | 2         | 4.08%   |
| 2001-3000      | 1         | 2.04%   |
| Unknown        | 1         | 2.04%   |

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
| Works    | 26        | 65     | 45.61%  |
| Detected | 23        | 38     | 40.35%  |
| Malfunc  | 8         | 21     | 14.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 35        | 53.03%  |
| AMD                          | 8         | 12.12%  |
| Samsung Electronics          | 4         | 6.06%   |
| LSI Logic / Symbios Logic    | 4         | 6.06%   |
| Broadcom / LSI               | 3         | 4.55%   |
| Phison Electronics           | 2         | 3.03%   |
| Union Memory (Shenzhen)      | 1         | 1.52%   |
| Toshiba America Info Systems | 1         | 1.52%   |
| SK Hynix                     | 1         | 1.52%   |
| Sandisk                      | 1         | 1.52%   |
| Realtek Semiconductor        | 1         | 1.52%   |
| Micron/Crucial Technology    | 1         | 1.52%   |
| Marvell Technology Group     | 1         | 1.52%   |
| Kingston Technology Company  | 1         | 1.52%   |
| ASMedia Technology           | 1         | 1.52%   |
| Adaptec                      | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 8.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 4.82%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 3.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 3.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 2.41%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 2.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 2.41%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 2.41%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 2.41%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 2.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 2.41%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 2.41%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 2.41%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2         | 2.41%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 1.2%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 1.2%    |
| SK Hynix BC511                                                                          | 1         | 1.2%    |
| Sandisk Non-Volatile memory controller                                                  | 1         | 1.2%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.2%    |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 1.2%    |
| Phison E18 PCIe4 NVMe Controller                                                        | 1         | 1.2%    |
| Phison E12 NVMe Controller                                                              | 1         | 1.2%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 1.2%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 1.2%    |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 1         | 1.2%    |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                               | 1         | 1.2%    |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.2%    |
| Intel SSD 660P Series                                                                   | 1         | 1.2%    |
| Intel PCIe Data Center SSD                                                              | 1         | 1.2%    |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                                | 1         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.2%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.2%    |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1         | 1.2%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 1.2%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 1.2%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.2%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 1.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 1.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 1.2%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 1.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.2%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1         | 1.2%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.2%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1         | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.2%    |
| Adaptec ASC-39320A U320                                                                 | 1         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 29        | 42.03%  |
| NVMe | 16        | 23.19%  |
| IDE  | 12        | 17.39%  |
| RAID | 8         | 11.59%  |
| SAS  | 3         | 4.35%   |
| SCSI | 1         | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 75.51%  |
| AMD    | 11        | 22.45%  |
| ARM    | 1         | 2.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Xeon CPU L5530 @ 2.40GHz                 | 2         | 4.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 2         | 4.08%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2         | 4.08%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz           | 1         | 2.04%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz             | 1         | 2.04%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1         | 2.04%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1         | 2.04%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz            | 1         | 2.04%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz             | 1         | 2.04%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1         | 2.04%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1         | 2.04%   |
| Intel Xeon CPU E3110 @ 3.00GHz                 | 1         | 2.04%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz            | 1         | 2.04%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1         | 2.04%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 1         | 2.04%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz             | 1         | 2.04%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz             | 1         | 2.04%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1         | 2.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 2.04%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz             | 1         | 2.04%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 2.04%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1         | 2.04%   |
| Intel Core i7-10610U CPU @ 1.80GHz             | 1         | 2.04%   |
| Intel Core i5-8365U CPU @ 1.60GHz              | 1         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 2.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 2.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 1         | 2.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 2.04%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1         | 2.04%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1         | 2.04%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 2.04%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 2.04%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1         | 2.04%   |
| ARM Processor                                  | 1         | 2.04%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1         | 2.04%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 2.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 1         | 2.04%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 2.04%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1         | 2.04%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics     | 1         | 2.04%   |
| AMD Ryzen 5 4600H with Radeon Graphics         | 1         | 2.04%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 2.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 2.04%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1         | 2.04%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 14        | 28.57%  |
| Intel Xeon              | 10        | 20.41%  |
| Intel Core i5           | 5         | 10.2%   |
| AMD Ryzen 7             | 3         | 6.12%   |
| AMD Ryzen 5             | 3         | 6.12%   |
| Other                   | 2         | 4.08%   |
| Intel Celeron           | 2         | 4.08%   |
| Intel Xeon Silver       | 1         | 2.04%   |
| Intel Xeon Gold         | 1         | 2.04%   |
| Intel Pentium Dual-Core | 1         | 2.04%   |
| Intel Core i3           | 1         | 2.04%   |
| Intel Core 2 Quad       | 1         | 2.04%   |
| Intel Core 2 Duo        | 1         | 2.04%   |
| AMD Ryzen Threadripper  | 1         | 2.04%   |
| AMD Ryzen 9             | 1         | 2.04%   |
| AMD Ryzen 5 PRO         | 1         | 2.04%   |
| AMD Ryzen 3             | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 20        | 40.82%  |
| 8      | 9         | 18.37%  |
| 2      | 9         | 18.37%  |
| 6      | 4         | 8.16%   |
| 16     | 2         | 4.08%   |
| 12     | 2         | 4.08%   |
| 32     | 1         | 2.04%   |
| 28     | 1         | 2.04%   |
| 24     | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 85.71%  |
| 2      | 7         | 14.29%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 34        | 69.39%  |
| 1      | 15        | 30.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 7         | 14.29%  |
| 0x506e3    | 3         | 6.12%   |
| 0x206a7    | 3         | 6.12%   |
| 0x806ec    | 2         | 4.08%   |
| 0x40651    | 2         | 4.08%   |
| 0x306e4    | 2         | 4.08%   |
| 0x106a5    | 2         | 4.08%   |
| 0x10676    | 2         | 4.08%   |
| 0x08600104 | 2         | 4.08%   |
| Unknown    | 2         | 4.08%   |
| 0xa0655    | 1         | 2.04%   |
| 0xa0652    | 1         | 2.04%   |
| 0x706a8    | 1         | 2.04%   |
| 0x50657    | 1         | 2.04%   |
| 0x50654    | 1         | 2.04%   |
| 0x406f1    | 1         | 2.04%   |
| 0x406e3    | 1         | 2.04%   |
| 0x306f2    | 1         | 2.04%   |
| 0x306a9    | 1         | 2.04%   |
| 0x206d7    | 1         | 2.04%   |
| 0x206c2    | 1         | 2.04%   |
| 0x1067a    | 1         | 2.04%   |
| 0x10677    | 1         | 2.04%   |
| 0x0a50000c | 1         | 2.04%   |
| 0x0a201009 | 1         | 2.04%   |
| 0x0870100a | 1         | 2.04%   |
| 0x08608103 | 1         | 2.04%   |
| 0x08301039 | 1         | 2.04%   |
| 0x08108109 | 1         | 2.04%   |
| 0x08108102 | 1         | 2.04%   |
| 0x0800820d | 1         | 2.04%   |
| 0x06006705 | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 11        | 22.45%  |
| Skylake       | 6         | 12.24%  |
| Zen 2         | 4         | 8.16%   |
| SandyBridge   | 4         | 8.16%   |
| Penryn        | 4         | 8.16%   |
| Zen+          | 3         | 6.12%   |
| IvyBridge     | 3         | 6.12%   |
| Zen 3         | 2         | 4.08%   |
| Nehalem       | 2         | 4.08%   |
| KabyLake      | 2         | 4.08%   |
| CometLake     | 2         | 4.08%   |
| Unknown       | 2         | 4.08%   |
| Westmere      | 1         | 2.04%   |
| Goldmont plus | 1         | 2.04%   |
| Excavator     | 1         | 2.04%   |
| Broadwell     | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 22        | 36.67%  |
| Intel                      | 21        | 35%     |
| AMD                        | 10        | 16.67%  |
| Matrox Electronics Systems | 4         | 6.67%   |
| ASPEED Technology          | 3         | 5%      |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 5%      |
| ASPEED Technology ASPEED Graphics Family                                    | 3         | 5%      |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 3.33%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 2         | 3.33%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 3.33%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 3.33%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 3.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 1.67%   |
| Nvidia TU117GL [T600]                                                       | 1         | 1.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.67%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 1.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 1.67%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 1.67%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.67%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 1.67%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 1.67%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.67%   |
| Nvidia GK107M [GeForce GT 755M]                                             | 1         | 1.67%   |
| Nvidia GK107GL [Quadro K600]                                                | 1         | 1.67%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.67%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 1.67%   |
| Nvidia GK104GL [GRID K2]                                                    | 1         | 1.67%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 1.67%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1         | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.67%   |
| Intel HD Graphics P530                                                      | 1         | 1.67%   |
| Intel HD Graphics 530                                                       | 1         | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1         | 1.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1         | 1.67%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                     | 1         | 1.67%   |
| AMD Renoir                                                                  | 1         | 1.67%   |
| AMD Lucienne                                                                | 1         | 1.67%   |
| AMD ES1000                                                                  | 1         | 1.67%   |
| AMD Cezanne                                                                 | 1         | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Nvidia      | 12        | 24.49%  |
| 1 x Intel       | 11        | 22.45%  |
| Intel + Nvidia  | 8         | 16.33%  |
| 1 x AMD         | 8         | 16.33%  |
| 1 x Matrox      | 3         | 6.12%   |
| 1 x ASPEED      | 3         | 6.12%   |
| Other           | 1         | 2.04%   |
| Nvidia + Matrox | 1         | 2.04%   |
| Intel + AMD     | 1         | 2.04%   |
| AMD + Nvidia    | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 36        | 73.47%  |
| Proprietary | 10        | 20.41%  |
| Unknown     | 3         | 6.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 46.94%  |
| 0.01-0.5   | 8         | 16.33%  |
| 1.01-2.0   | 7         | 14.29%  |
| 3.01-4.0   | 4         | 8.16%   |
| 5.01-6.0   | 3         | 6.12%   |
| 0.51-1.0   | 3         | 6.12%   |
| 8.01-16.0  | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 10        | 19.61%  |
| Samsung Electronics | 5         | 9.8%    |
| AU Optronics        | 5         | 9.8%    |
| LG Display          | 4         | 7.84%   |
| Goldstar            | 4         | 7.84%   |
| BOE                 | 4         | 7.84%   |
| Chimei Innolux      | 3         | 5.88%   |
| Philips             | 2         | 3.92%   |
| Iiyama              | 2         | 3.92%   |
| AOC                 | 2         | 3.92%   |
| Acer                | 2         | 3.92%   |
| Sony                | 1         | 1.96%   |
| PANDA               | 1         | 1.96%   |
| Panasonic           | 1         | 1.96%   |
| Lenovo              | 1         | 1.96%   |
| IBM                 | 1         | 1.96%   |
| Hewlett-Packard     | 1         | 1.96%   |
| ASUSTek Computer    | 1         | 1.96%   |
| ADR                 | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony LG TV SNY045B 1920x540                                           | 1         | 1.85%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 1.85%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 1.85%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.85%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 1.85%   |
| Philips PHL 272S4L PHL08E4 1920x1080 600x340mm 27.2-inch              | 1         | 1.85%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 1.85%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.85%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.85%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.85%   |
| Lenovo LCD Monitor LEN4055 1920x1200 330x210mm 15.4-inch              | 1         | 1.85%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1         | 1.85%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1         | 1.85%   |
| IBM RSA2 IBM029A 1024x768 300x225mm 14.8-inch                         | 1         | 1.85%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1         | 1.85%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.85%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.85%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.85%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.85%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 1         | 1.85%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 1.85%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 1.85%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.85%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                      | 1         | 1.85%   |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                       | 1         | 1.85%   |
| Dell LCD Monitor U2414H 3840x1080                                     | 1         | 1.85%   |
| Dell LCD Monitor U2414H                                               | 1         | 1.85%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                     | 1         | 1.85%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 1.85%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1         | 1.85%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 1         | 1.85%   |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                 | 1         | 1.85%   |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 1.85%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 1.85%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                 | 1         | 1.85%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch        | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 1.85%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch          | 1         | 1.85%   |
| AOC 2279WH AOC2279 1920x1080 477x268mm 21.5-inch                      | 1         | 1.85%   |
| AOC 1620 AOC1620 1366x768 340x190mm 15.3-inch                         | 1         | 1.85%   |
| ADR KVM-via-IP ADR0219 1280x1024                                      | 1         | 1.85%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 1         | 1.85%   |
| Acer G277HL ACR03FB 1920x1080 598x336mm 27.0-inch                     | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 45.65%  |
| 1600x900 (HD+)     | 4         | 8.7%    |
| 1280x1024 (SXGA)   | 3         | 6.52%   |
| 3840x2160 (4K)     | 2         | 4.35%   |
| 3840x1080          | 2         | 4.35%   |
| 1920x1200 (WUXGA)  | 2         | 4.35%   |
| 1680x1050 (WSXGA+) | 2         | 4.35%   |
| 1440x900 (WXGA+)   | 2         | 4.35%   |
| Unknown            | 2         | 4.35%   |
| 3440x1440          | 1         | 2.17%   |
| 2560x1440 (QHD)    | 1         | 2.17%   |
| 2560x1080          | 1         | 2.17%   |
| 1920x540           | 1         | 2.17%   |
| 1366x768 (WXGA)    | 1         | 2.17%   |
| 1024x768 (XGA)     | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 19.61%  |
| 27      | 7         | 13.73%  |
| 14      | 7         | 13.73%  |
| 17      | 4         | 7.84%   |
| 23      | 3         | 5.88%   |
| 21      | 3         | 5.88%   |
| 19      | 3         | 5.88%   |
| 34      | 2         | 3.92%   |
| 24      | 2         | 3.92%   |
| 13      | 2         | 3.92%   |
| Unknown | 2         | 3.92%   |
| 65      | 1         | 1.96%   |
| 48      | 1         | 1.96%   |
| 31      | 1         | 1.96%   |
| 28      | 1         | 1.96%   |
| 22      | 1         | 1.96%   |
| 20      | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 39.22%  |
| 501-600     | 12        | 23.53%  |
| 401-500     | 9         | 17.65%  |
| 701-800     | 2         | 3.92%   |
| 351-400     | 2         | 3.92%   |
| 1001-1500   | 2         | 3.92%   |
| Unknown     | 2         | 3.92%   |
| 601-700     | 1         | 1.96%   |
| 201-300     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 29        | 67.44%  |
| 16/10   | 4         | 9.3%    |
| 5/4     | 3         | 6.98%   |
| 3/2     | 2         | 4.65%   |
| 21/9    | 2         | 4.65%   |
| 4/3     | 1         | 2.33%   |
| 32/9    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 20%     |
| 81-90          | 8         | 16%     |
| 301-350        | 7         | 14%     |
| 201-250        | 7         | 14%     |
| 151-200        | 5         | 10%     |
| 351-500        | 4         | 8%      |
| 141-150        | 2         | 4%      |
| 121-130        | 2         | 4%      |
| Unknown        | 2         | 4%      |
| More than 1000 | 1         | 2%      |
| 501-1000       | 1         | 2%      |
| 91-100         | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 20        | 40%     |
| 121-160       | 19        | 38%     |
| 101-120       | 6         | 12%     |
| Unknown       | 2         | 4%      |
| More than 240 | 1         | 2%      |
| 1-50          | 1         | 2%      |
| 161-240       | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 53.06%  |
| 0     | 11        | 22.45%  |
| 2     | 9         | 18.37%  |
| 3     | 2         | 4.08%   |
| 4     | 1         | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 31        | 44.29%  |
| Realtek Semiconductor     | 20        | 28.57%  |
| Broadcom                  | 5         | 7.14%   |
| Qualcomm Atheros          | 4         | 5.71%   |
| Mellanox Technologies     | 3         | 4.29%   |
| Solarflare Communications | 1         | 1.43%   |
| Microsoft                 | 1         | 1.43%   |
| MEDIATEK                  | 1         | 1.43%   |
| Marvell Technology Group  | 1         | 1.43%   |
| Linksys                   | 1         | 1.43%   |
| BUFFALO                   | 1         | 1.43%   |
| Broadcom Limited          | 1         | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 18        | 21.18%  |
| Intel Ethernet Connection I217-LM                                                                                      | 5         | 5.88%   |
| Intel Wireless 7260                                                                                                    | 4         | 4.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 4         | 4.71%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 3         | 3.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 2         | 2.35%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 2.35%   |
| Intel Wireless 8260                                                                                                    | 2         | 2.35%   |
| Intel Wireless 3165                                                                                                    | 2         | 2.35%   |
| Intel I211 Gigabit Network Connection                                                                                  | 2         | 2.35%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 2.35%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 2         | 2.35%   |
| Solarflare SFC9020 10G Ethernet Controller                                                                             | 1         | 1.18%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 1         | 1.18%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                             | 1         | 1.18%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1         | 1.18%   |
| Realtek 802.11ac NIC                                                                                                   | 1         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 1         | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                                              | 1         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                                       | 1         | 1.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                       | 1         | 1.18%   |
| Microsoft Xbox 360 Wireless Adapter                                                                                    | 1         | 1.18%   |
| Mellanox MT27700 Family [ConnectX-4]                                                                                   | 1         | 1.18%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 1         | 1.18%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                                                | 1         | 1.18%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                                                      | 1         | 1.18%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                                    | 1         | 1.18%   |
| Intel Wireless 7265                                                                                                    | 1         | 1.18%   |
| Intel Wireless 3160                                                                                                    | 1         | 1.18%   |
| Intel Ultimate N WiFi Link 5300                                                                                        | 1         | 1.18%   |
| Intel I350 Gigabit Network Connection                                                                                  | 1         | 1.18%   |
| Intel Ethernet Virtual Function 700 Series                                                                             | 1         | 1.18%   |
| Intel Ethernet Controller X550                                                                                         | 1         | 1.18%   |
| Intel Ethernet Connection I217-V                                                                                       | 1         | 1.18%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 1         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 1         | 1.18%   |
| Intel Ethernet 10G 2P X520 Adapter                                                                                     | 1         | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                        | 1         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 1         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 1         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 1         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 1         | 1.18%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                                                   | 1         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                                                                               | 1         | 1.18%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                                                               | 1         | 1.18%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                                                                      | 1         | 1.18%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                                                      | 1         | 1.18%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                                                                | 1         | 1.18%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet                                                           | 1         | 1.18%   |

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
| Realtek Semiconductor     | 20        | 41.67%  |
| Intel                     | 19        | 39.58%  |
| Broadcom                  | 5         | 10.42%  |
| Solarflare Communications | 1         | 2.08%   |
| Qualcomm Atheros          | 1         | 2.08%   |
| Marvell Technology Group  | 1         | 2.08%   |
| Broadcom Limited          | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 33.96%  |
| Intel Ethernet Connection I217-LM                                 | 5         | 9.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 7.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.77%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.77%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 3.77%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 3.77%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 1.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.89%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.89%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.89%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.89%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 1.89%   |
| Intel Ethernet Controller X550                                    | 1         | 1.89%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 1.89%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 1.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.89%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 1         | 1.89%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet      | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 59.74%  |
| WiFi     | 28        | 36.36%  |
| Unknown  | 3         | 3.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 33        | 66%     |
| WiFi     | 16        | 32%     |
| Unknown  | 1         | 2%      |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 48.98%  |
| 1     | 17        | 34.69%  |
| 5     | 2         | 4.08%   |
| 3     | 2         | 4.08%   |
| 66    | 1         | 2.04%   |
| 8     | 1         | 2.04%   |
| 4     | 1         | 2.04%   |
| 0     | 1         | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 79.59%  |
| Yes  | 10        | 20.41%  |

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
| Intel AX201 Bluetooth                               | 2         | 8.33%   |
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
| Intel               | 29        | 43.28%  |
| Nvidia              | 18        | 26.87%  |
| AMD                 | 12        | 17.91%  |
| Logitech            | 2         | 2.99%   |
| C-Media Electronics | 2         | 2.99%   |
| Hewlett-Packard     | 1         | 1.49%   |
| GN Netcom           | 1         | 1.49%   |
| Conexant Systems    | 1         | 1.49%   |
| ASUSTek Computer    | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 8.64%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 7.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 6.17%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.47%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.47%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 2.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 2.47%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 2.47%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.47%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2         | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.47%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.23%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 1.23%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.23%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.23%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.23%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.23%   |
| Logitech Stereo H650e                                                      | 1         | 1.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.23%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.23%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.23%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.23%   |
| GN Netcom Jabra Evolve 65                                                  | 1         | 1.23%   |
| Conexant Systems HP Dock Audio                                             | 1         | 1.23%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 1.23%   |
| C-Media Electronics TONOR TC30 Audio Device                                | 1         | 1.23%   |
| ASUSTek Computer USB Audio                                                 | 1         | 1.23%   |
| AMD High Definition Audio Controller                                       | 1         | 1.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 9         | 31.03%  |
| Samsung Electronics | 8         | 27.59%  |
| SK Hynix            | 3         | 10.34%  |
| G.Skill             | 3         | 10.34%  |
| Unknown             | 2         | 6.9%    |
| Kingston            | 2         | 6.9%    |
| Crucial             | 1         | 3.45%   |
| Corsair             | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 3.33%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                              | 1         | 3.33%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                  | 1         | 3.33%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                | 1         | 3.33%   |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s            | 1         | 3.33%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s              | 1         | 3.33%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s              | 1         | 3.33%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                | 1         | 3.33%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s                  | 1         | 3.33%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 3.33%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 3.33%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                   | 1         | 3.33%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 3.33%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                              | 1         | 3.33%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                   | 1         | 3.33%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                    | 1         | 3.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s         | 1         | 3.33%   |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s                  | 1         | 3.33%   |
| Micron RAM 36ASF4G72PZ-2G3D1 32GB DIMM DDR4 2400MT/s                  | 1         | 3.33%   |
| Micron RAM 3138485446313238373241592D3636374631 1GB DIMM DDR2 667MT/s | 1         | 3.33%   |
| Micron RAM 18ASF2G72AZ-2G3A1 16GB DIMM DDR4 2400MT/s                  | 1         | 3.33%   |
| Micron RAM 18ASF1G72PDZ-2G6F1 8GB DIMM DDR4 2666MT/s                  | 1         | 3.33%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 1600MT/s                   | 1         | 3.33%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 3.33%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 3.33%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s                   | 1         | 3.33%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s                  | 1         | 3.33%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s                    | 1         | 3.33%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s            | 1         | 3.33%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s                  | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 53.57%  |
| DDR3   | 10        | 35.71%  |
| DDR2   | 2         | 7.14%   |
| LPDDR4 | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 19        | 67.86%  |
| SODIMM       | 7         | 25%     |
| Row Of Chips | 1         | 3.57%   |
| RIMM         | 1         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 42.86%  |
| 16384 | 5         | 17.86%  |
| 32768 | 4         | 14.29%  |
| 1024  | 4         | 14.29%  |
| 4096  | 2         | 7.14%   |
| 2048  | 1         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 6         | 20.69%  |
| 2667  | 4         | 13.79%  |
| 1600  | 4         | 13.79%  |
| 2400  | 3         | 10.34%  |
| 2666  | 2         | 6.9%    |
| 1066  | 2         | 6.9%    |
| 667   | 2         | 6.9%    |
| 4266  | 1         | 3.45%   |
| 2933  | 1         | 3.45%   |
| 2200  | 1         | 3.45%   |
| 2133  | 1         | 3.45%   |
| 1866  | 1         | 3.45%   |
| 1800  | 1         | 3.45%   |

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
| 0     | 27        | 55.1%   |
| 1     | 15        | 30.61%  |
| 2     | 5         | 10.2%   |
| 5     | 1         | 2.04%   |
| 4     | 1         | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 20.69%  |
| Net/wireless             | 5         | 17.24%  |
| Unassigned class         | 4         | 13.79%  |
| Communication controller | 4         | 13.79%  |
| Graphics card            | 3         | 10.34%  |
| Network                  | 2         | 6.9%    |
| Chipcard                 | 2         | 6.9%    |
| Net/ethernet             | 1         | 3.45%   |
| Multimedia controller    | 1         | 3.45%   |
| Card reader              | 1         | 3.45%   |

