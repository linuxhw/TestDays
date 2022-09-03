Q4OS - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Q4OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Q4OS/Desktop/README.md) and [notebooks](/Dist/Q4OS/Notebook/README.md).

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

| Vendor        | Model                    | Form-Factor | Probe                                                      | Date         |
|---------------|--------------------------|-------------|------------------------------------------------------------|--------------|
| Medion        | P6620                    | Notebook    | [e5db2a930b](https://linux-hardware.org/?probe=e5db2a930b) | Aug 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00 | Notebook    | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q               | Notebook    | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70            | Notebook    | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC       | Notebook    | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASRock        | H61M-HVS                 | Desktop     | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| ASUSTek       | A6U                      | Notebook    | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500       | Notebook    | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1   | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                   | Notebook    | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                    | Notebook    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                   | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10               | Notebook    | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56            | Notebook    | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56            | Notebook    | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Compaq        | 07E4h                    | Desktop     | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| MSI           | U210                     | Notebook    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660           | Notebook    | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660           | Notebook    | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                    | Notebook    | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660           | Notebook    | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660           | Notebook    | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Gigabyte      | XP-M5S661GX              | Desktop     | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| Phoenix/Si... | M720SR                   | Notebook    | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx        | Notebook    | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx        | Notebook    | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro             | Notebook    | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| TECO Elect... | TR53A0                   | Desktop     | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| HP            | ProBook 450 G2           | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                      | Notebook    | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| MSI           | B550-A PRO               | Desktop     | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2            | Desktop     | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| HP            | ProBook 6550b            | Notebook    | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                     | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASRock        | G41M-VS3                 | Desktop     | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3                 | Desktop     | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |
| ASUSTek       | A6JC                     | Notebook    | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                     | Notebook    | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00  | Notebook    | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81            | Notebook    | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP              | Notebook    | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC              | Notebook    | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                  | Notebook    | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| TrekStor      | SurfTab wintron 7.0      | Tablet      | [464706154e](https://linux-hardware.org/?probe=464706154e) | Jun 26, 2019 |
| TrekStor      | SurfTab wintron 7.0      | Tablet      | [db63ea2d00](https://linux-hardware.org/?probe=db63ea2d00) | Jun 19, 2019 |
| TrekStor      | SurfTab wintron 7.0      | Tablet      | [9e530b2e21](https://linux-hardware.org/?probe=9e530b2e21) | Jun 18, 2019 |
| Philco        | 14I                      | Notebook    | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Q4OS 4 | 21        | 52.5%   |
| Q4OS 3 | 14        | 35%     |
| Q4OS 2 | 5         | 12.5%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 4.19.0-17-amd64        | 4         | 10%     |
| 5.10.0-12-amd64        | 3         | 7.5%    |
| 5.10.0-8-amd64         | 2         | 5%      |
| 5.10.0-14-686-pae      | 2         | 5%      |
| 5.10.0-10-686-pae      | 2         | 5%      |
| 5.9.0-5-amd64          | 1         | 2.5%    |
| 5.6.0-1-amd64          | 1         | 2.5%    |
| 5.18.0-0.bpo.1-amd64   | 1         | 2.5%    |
| 5.10.0-9-amd64         | 1         | 2.5%    |
| 5.10.0-9-686-pae       | 1         | 2.5%    |
| 5.10.0-8-686-pae       | 1         | 2.5%    |
| 5.10.0-17-amd64        | 1         | 2.5%    |
| 5.10.0-15-686-pae      | 1         | 2.5%    |
| 5.10.0-14-amd64        | 1         | 2.5%    |
| 5.10.0-13-amd64        | 1         | 2.5%    |
| 5.10.0-12-686-pae      | 1         | 2.5%    |
| 5.10.0-11-686-pae      | 1         | 2.5%    |
| 4.9.0-9-686-pae        | 1         | 2.5%    |
| 4.9.0-8-amd64          | 1         | 2.5%    |
| 4.9.0-14-686-pae       | 1         | 2.5%    |
| 4.9.0-12-686-pae       | 1         | 2.5%    |
| 4.19.0-6-amd64         | 1         | 2.5%    |
| 4.19.0-20-amd64        | 1         | 2.5%    |
| 4.19.0-17-686-pae      | 1         | 2.5%    |
| 4.19.0-17-686          | 1         | 2.5%    |
| 4.19.0-16-amd64        | 1         | 2.5%    |
| 4.19.0-16-686          | 1         | 2.5%    |
| 4.19.0-14-amd64        | 1         | 2.5%    |
| 4.19.0-13-amd64        | 1         | 2.5%    |
| 4.19.0-12-amd64        | 1         | 2.5%    |
| 4.19.0-10-amd64        | 1         | 2.5%    |
| 4.19.0-0.bpo.5-686-pae | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 18        | 45%     |
| 4.19.0  | 15        | 37.5%   |
| 4.9.0   | 4         | 10%     |
| 5.9.0   | 1         | 2.5%    |
| 5.6.0   | 1         | 2.5%    |
| 5.18.0  | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 45%     |
| 4.19    | 15        | 37.5%   |
| 4.9     | 4         | 10%     |
| 5.9     | 1         | 2.5%    |
| 5.6     | 1         | 2.5%    |
| 5.18    | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 24        | 60%     |
| i686   | 16        | 40%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Trinity | 21        | 52.5%   |
| KDE5    | 18        | 45%     |
| KDE     | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 39        | 97.5%   |
| Tty  | 1         | 2.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| TDM  | 21        | 52.5%   |
| SDDM | 19        | 47.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 15        | 37.5%   |
| es_ES   | 3         | 7.5%    |
| en_GB   | 3         | 7.5%    |
| de_DE   | 3         | 7.5%    |
| Unknown | 3         | 7.5%    |
| fr_FR   | 2         | 5%      |
| sv_SE   | 1         | 2.5%    |
| sl_SI   | 1         | 2.5%    |
| ru_RU   | 1         | 2.5%    |
| pt_BR   | 1         | 2.5%    |
| pl_PL   | 1         | 2.5%    |
| it_IT   | 1         | 2.5%    |
| es_VE   | 1         | 2.5%    |
| es_AR   | 1         | 2.5%    |
| en_ZA   | 1         | 2.5%    |
| en_SG   | 1         | 2.5%    |
| C       | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 25        | 62.5%   |
| EFI  | 15        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 92.5%   |
| Overlay | 3         | 7.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 23        | 57.5%   |
| GPT     | 16        | 40%     |
| Unknown | 1         | 2.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 85%     |
| Yes       | 6         | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 62.5%   |
| Yes       | 15        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 7         | 17.5%   |
| Toshiba                     | 4         | 10%     |
| ASUSTek Computer            | 4         | 10%     |
| MSI                         | 3         | 7.5%    |
| Lenovo                      | 3         | 7.5%    |
| TrekStor                    | 2         | 5%      |
| Medion                      | 2         | 5%      |
| ASRock                      | 2         | 5%      |
| Visual Land                 | 1         | 2.5%    |
| TECO Electric and Machinery | 1         | 2.5%    |
| Sony                        | 1         | 2.5%    |
| Qilive                      | 1         | 2.5%    |
| Phoenix/SiS                 | 1         | 2.5%    |
| Philco                      | 1         | 2.5%    |
| Packard Bell                | 1         | 2.5%    |
| JVC                         | 1         | 2.5%    |
| Gigabyte Technology         | 1         | 2.5%    |
| Compaq                      | 1         | 2.5%    |
| Chuwi                       | 1         | 2.5%    |
| AMI                         | 1         | 2.5%    |
| Acer                        | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 5%      |
| Toshiba Satellite C660                 | 2         | 5%      |
| Visual Land Premier 10                 | 1         | 2.5%    |
| Toshiba Satellite Pro L500             | 1         | 2.5%    |
| Toshiba Satellite M70                  | 1         | 2.5%    |
| TECO Electric and Machinery FUTRO S400 | 1         | 2.5%    |
| Sony VGN-P11Z_Q                        | 1         | 2.5%    |
| Qilive QW19141AMSP                     | 1         | 2.5%    |
| Phoenix/SiS M720SR                     | 1         | 2.5%    |
| Philco 14I                             | 1         | 2.5%    |
| Packard Bell EasyNote LM81             | 1         | 2.5%    |
| MSI U210                               | 1         | 2.5%    |
| MSI MS-7C56                            | 1         | 2.5%    |
| MSI MS-7597                            | 1         | 2.5%    |
| Medion P6620                           | 1         | 2.5%    |
| Lenovo ThinkPad T495 20NKS0PG00        | 1         | 2.5%    |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 2.5%    |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 2.5%    |
| JVC J3N                                | 1         | 2.5%    |
| HP ProBook 6550b                       | 1         | 2.5%    |
| HP ProBook 450 G2                      | 1         | 2.5%    |
| HP Presario CQ56                       | 1         | 2.5%    |
| HP OmniBook PC                         | 1         | 2.5%    |
| HP Laptop 15s-fq2xxx                   | 1         | 2.5%    |
| HP 250 G5 Notebook PC                  | 1         | 2.5%    |
| HP 2000                                | 1         | 2.5%    |
| Gigabyte XP-M5S661GX                   | 1         | 2.5%    |
| Compaq Evo D510 SFF                    | 1         | 2.5%    |
| Chuwi GemiBook Pro                     | 1         | 2.5%    |
| ASUS X540YA                            | 1         | 2.5%    |
| ASUS T12Eg                             | 1         | 2.5%    |
| ASUS A6U                               | 1         | 2.5%    |
| ASUS A6JC                              | 1         | 2.5%    |
| ASRock H61M-HVS                        | 1         | 2.5%    |
| ASRock G41M-VS3                        | 1         | 2.5%    |
| AMI Intel                              | 1         | 2.5%    |
| Acer AO751h                            | 1         | 2.5%    |
| Unknown                                | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 10%     |
| TrekStor SurfTab                  | 2         | 5%      |
| Lenovo ThinkPad                   | 2         | 5%      |
| HP ProBook                        | 2         | 5%      |
| Visual Land Premier               | 1         | 2.5%    |
| TECO Electric and Machinery FUTRO | 1         | 2.5%    |
| Sony VGN-P11Z                     | 1         | 2.5%    |
| Qilive QW19141AMSP                | 1         | 2.5%    |
| Phoenix/SiS M720SR                | 1         | 2.5%    |
| Philco 14I                        | 1         | 2.5%    |
| Packard Bell EasyNote             | 1         | 2.5%    |
| MSI U210                          | 1         | 2.5%    |
| MSI MS-7C56                       | 1         | 2.5%    |
| MSI MS-7597                       | 1         | 2.5%    |
| Medion P6620                      | 1         | 2.5%    |
| Lenovo IdeaPad                    | 1         | 2.5%    |
| JVC J3N                           | 1         | 2.5%    |
| HP Presario                       | 1         | 2.5%    |
| HP OmniBook                       | 1         | 2.5%    |
| HP Laptop                         | 1         | 2.5%    |
| HP 250                            | 1         | 2.5%    |
| HP 2000                           | 1         | 2.5%    |
| Gigabyte XP-M5S661GX              | 1         | 2.5%    |
| Compaq Evo                        | 1         | 2.5%    |
| Chuwi GemiBook                    | 1         | 2.5%    |
| ASUS X540YA                       | 1         | 2.5%    |
| ASUS T12Eg                        | 1         | 2.5%    |
| ASUS A6U                          | 1         | 2.5%    |
| ASUS A6JC                         | 1         | 2.5%    |
| ASRock H61M-HVS                   | 1         | 2.5%    |
| ASRock G41M-VS3                   | 1         | 2.5%    |
| AMI Intel                         | 1         | 2.5%    |
| Acer AO751h                       | 1         | 2.5%    |
| Unknown                           | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 15%     |
| 2020    | 4         | 10%     |
| 2009    | 4         | 10%     |
| 2015    | 3         | 7.5%    |
| 2011    | 3         | 7.5%    |
| 2005    | 3         | 7.5%    |
| 2019    | 2         | 5%      |
| 2016    | 2         | 5%      |
| 2014    | 2         | 5%      |
| 2008    | 2         | 5%      |
| Unknown | 2         | 5%      |
| 2018    | 1         | 2.5%    |
| 2017    | 1         | 2.5%    |
| 2012    | 1         | 2.5%    |
| 2007    | 1         | 2.5%    |
| 2006    | 1         | 2.5%    |
| 2004    | 1         | 2.5%    |
| 2002    | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 31        | 77.5%   |
| Desktop  | 7         | 17.5%   |
| Tablet   | 2         | 5%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 38        | 95%     |
| Enabled  | 2         | 5%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 10        | 25%     |
| 2.01-3.0    | 7         | 17.5%   |
| 1.01-2.0    | 6         | 15%     |
| 0.51-1.0    | 6         | 15%     |
| 4.01-8.0    | 5         | 12.5%   |
| 16.01-24.0  | 2         | 5%      |
| 0.01-0.5    | 2         | 5%      |
| 24.01-32.0  | 1         | 2.5%    |
| 64.01-256.0 | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 14        | 35%     |
| 0.51-1.0  | 11        | 27.5%   |
| 0.01-0.5  | 7         | 17.5%   |
| 2.01-3.0  | 5         | 12.5%   |
| 3.01-4.0  | 2         | 5%      |
| 8.01-16.0 | 1         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 70%     |
| 2      | 8         | 20%     |
| 3      | 4         | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 50%     |
| No        | 20        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 90%     |
| No        | 4         | 10%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 72.5%   |
| No        | 11        | 27.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 60%     |
| Yes       | 16        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 5         | 12.5%   |
| UK           | 3         | 7.5%    |
| Spain        | 3         | 7.5%    |
| Kenya        | 3         | 7.5%    |
| Germany      | 3         | 7.5%    |
| Switzerland  | 2         | 5%      |
| Romania      | 2         | 5%      |
| Poland       | 2         | 5%      |
| Italy        | 2         | 5%      |
| France       | 2         | 5%      |
| Brazil       | 2         | 5%      |
| Venezuela    | 1         | 2.5%    |
| Sweden       | 1         | 2.5%    |
| South Africa | 1         | 2.5%    |
| Slovenia     | 1         | 2.5%    |
| Singapore    | 1         | 2.5%    |
| Saudi Arabia | 1         | 2.5%    |
| Russia       | 1         | 2.5%    |
| Qatar        | 1         | 2.5%    |
| Netherlands  | 1         | 2.5%    |
| Belarus      | 1         | 2.5%    |
| Argentina    | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 7.5%    |
| Zurich                | 2         | 5%      |
| Swindon               | 2         | 5%      |
| Rostock               | 2         | 5%      |
| Mesa                  | 2         | 5%      |
| Drobeta-Turnu Severin | 2         | 5%      |
| Tranas                | 1         | 2.5%    |
| The Hague             | 1         | 2.5%    |
| Tellico Plains        | 1         | 2.5%    |
| Sosnowiec             | 1         | 2.5%    |
| Singapore             | 1         | 2.5%    |
| Schermbeck            | 1         | 2.5%    |
| Salsomaggiore Terme   | 1         | 2.5%    |
| Puerto Cumarebo       | 1         | 2.5%    |
| Posadas               | 1         | 2.5%    |
| Moscow                | 1         | 2.5%    |
| Moirans               | 1         | 2.5%    |
| Mogilev               | 1         | 2.5%    |
| Londrina              | 1         | 2.5%    |
| Ljubljana             | 1         | 2.5%    |
| Las Vegas             | 1         | 2.5%    |
| Klaudyn               | 1         | 2.5%    |
| Johannesburg          | 1         | 2.5%    |
| Guarulhos             | 1         | 2.5%    |
| Grand Junction        | 1         | 2.5%    |
| Gijón                | 1         | 2.5%    |
| Fulham                | 1         | 2.5%    |
| Doha                  | 1         | 2.5%    |
| Dammam                | 1         | 2.5%    |
| Calvecchia            | 1         | 2.5%    |
| Boulogne-sur-Mer      | 1         | 2.5%    |
| Barcelona             | 1         | 2.5%    |
| Alicante              | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 16.67%  |
| Unknown             | 6         | 6      | 12.5%   |
| Seagate             | 6         | 7      | 12.5%   |
| Samsung Electronics | 4         | 4      | 8.33%   |
| SanDisk             | 3         | 3      | 6.25%   |
| Hitachi             | 3         | 3      | 6.25%   |
| China               | 3         | 4      | 6.25%   |
| Toshiba             | 2         | 2      | 4.17%   |
| Kingston            | 2         | 2      | 4.17%   |
| KESU                | 2         | 2      | 4.17%   |
| HGST                | 2         | 2      | 4.17%   |
| Unknown (CF)        | 1         | 1      | 2.08%   |
| Silicon Motion      | 1         | 1      | 2.08%   |
| Phison              | 1         | 1      | 2.08%   |
| Maxtor              | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |
| Unknown             | 1         | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 4%      |
| Samsung SSD 850 EVO 250GB            | 2         | 4%      |
| KESU USB 3.1 128GB                   | 2         | 4%      |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 2%      |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 2%      |
| WDC WD400BD-23JMC0 40GB              | 1         | 2%      |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 2%      |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 2%      |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 2%      |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 2%      |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 2%      |
| Unknown USDU1  32GB                  | 1         | 2%      |
| Unknown SLD64G  64GB                 | 1         | 2%      |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 2%      |
| Unknown 064G38  64GB                 | 1         | 2%      |
| Unknown (CF) Card 16GB SSD           | 1         | 2%      |
| Toshiba MK8025GAS 80GB               | 1         | 2%      |
| Toshiba MK6028GAL 64GB               | 1         | 2%      |
| Silicon Motion NVME SSD 512GB        | 1         | 2%      |
| Seagate ST9120822AS 120GB            | 1         | 2%      |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 2%      |
| Seagate ST3160815AS 160GB            | 1         | 2%      |
| Seagate ST3160812AS 160GB            | 1         | 2%      |
| Seagate ST310211A 10GB               | 1         | 2%      |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 2%      |
| Seagate Backup+ SL 1TB               | 1         | 2%      |
| SanDisk SDSSDA120G 120GB             | 1         | 2%      |
| SanDisk SDCFX-032G SSD               | 1         | 2%      |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 2%      |
| Samsung HD081GJ 80GB                 | 1         | 2%      |
| Samsung AWMB3R  16GB                 | 1         | 2%      |
| Phison APS-SE20G-1T                  | 1         | 2%      |
| Maxtor 6Y080L0 82GB                  | 1         | 2%      |
| Kingston SV300S37A60G 64GB SSD       | 1         | 2%      |
| Kingston SA400S37240G 240GB SSD      | 1         | 2%      |
| Hitachi HTS545032B9A300 320GB        | 1         | 2%      |
| Hitachi HTS543225L9SA00 250GB        | 1         | 2%      |
| Hitachi DK23CA-20 20GB               | 1         | 2%      |
| HGST HTS725050A7E630 500GB           | 1         | 2%      |
| HGST HTS541075A9E680 752GB           | 1         | 2%      |
| Fujitsu MHY2080BH 80GB               | 1         | 2%      |
| China SSD128GBS800                   | 1         | 2%      |
| China SSD 256GB                      | 1         | 2%      |
| China SSD 120GB                      | 1         | 2%      |
| China SATA SSD 240GB                 | 1         | 2%      |
| A-DATA SU630 240GB SSD               | 1         | 2%      |
| Unknown                              | 1         | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 27.27%  |
| Seagate             | 5         | 6      | 22.73%  |
| Hitachi             | 3         | 3      | 13.64%  |
| Toshiba             | 2         | 2      | 9.09%   |
| HGST                | 2         | 2      | 9.09%   |
| Unknown             | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| Maxtor              | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 21.43%  |
| China               | 3         | 4      | 21.43%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| Kingston            | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Unknown (CF)        | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |
| Unknown             | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 23     | 44.19%  |
| SSD     | 13        | 15     | 30.23%  |
| MMC     | 6         | 6      | 13.95%  |
| Unknown | 3         | 3      | 6.98%   |
| NVMe    | 2         | 3      | 4.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 37     | 71.43%  |
| MMC  | 6         | 6      | 14.29%  |
| SAS  | 4         | 4      | 9.52%   |
| NVMe | 2         | 3      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 34     | 87.5%   |
| 0.51-1.0   | 3         | 3      | 9.38%   |
| 4.01-10.0  | 1         | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 9         | 22.5%   |
| 51-100         | 9         | 22.5%   |
| 101-250        | 6         | 15%     |
| 21-50          | 5         | 12.5%   |
| 251-500        | 4         | 10%     |
| 1001-2000      | 3         | 7.5%    |
| 501-1000       | 2         | 5%      |
| More than 3000 | 1         | 2.5%    |
| Unknown        | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 27        | 67.5%   |
| 21-50          | 6         | 15%     |
| 251-500        | 2         | 5%      |
| 501-1000       | 2         | 5%      |
| More than 3000 | 1         | 2.5%    |
| 51-100         | 1         | 2.5%    |
| Unknown        | 1         | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD400BD-23JMC0 40GB       | 1         | 1      | 10%     |
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 10%     |
| Seagate ST9120822AS 120GB     | 1         | 1      | 10%     |
| Maxtor 6Y080L0 82GB           | 1         | 1      | 10%     |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 10%     |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 10%     |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 10%     |
| HGST HTS725050A7E630 500GB    | 1         | 1      | 10%     |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 10%     |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Seagate | 1         | 1      | 10%     |
| Maxtor  | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Seagate | 1         | 1      | 10%     |
| Maxtor  | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 22        | 29     | 52.38%  |
| Detected | 10        | 11     | 23.81%  |
| Malfunc  | 10        | 10     | 23.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 23        | 60.53%  |
| AMD                              | 7         | 18.42%  |
| Silicon Integrated Systems [SiS] | 4         | 10.53%  |
| Silicon Motion                   | 1         | 2.63%   |
| SanDisk                          | 1         | 2.63%   |
| Phison Electronics               | 1         | 2.63%   |
| Nvidia                           | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 4         | 8.7%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 8.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 6.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 6.52%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 4.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 4.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.17%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 2.17%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 2.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.17%   |
| Phison E12 NVMe Controller                                                       | 1         | 2.17%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 2.17%   |
| Nvidia MCP61 IDE                                                                 | 1         | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.17%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 2.17%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 2.17%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 2.17%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 2.17%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 2.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 2.17%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                           | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 20        | 51.28%  |
| IDE  | 15        | 38.46%  |
| RAID | 2         | 5.13%   |
| NVMe | 2         | 5.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 72.5%   |
| AMD    | 11        | 27.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz                 | 3         | 7.5%    |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 5%      |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 5%      |
| Intel Pentium M processor 1000MHz               | 1         | 2.5%    |
| Intel Pentium M processor 1.70GHz               | 1         | 2.5%    |
| Intel Pentium III (Coppermine)                  | 1         | 2.5%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2.5%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 2.5%    |
| Intel Pentium 4 CPU 3.00GHz                     | 1         | 2.5%    |
| Intel Pentium 4 CPU 2.00GHz                     | 1         | 2.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 2.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.5%    |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2.5%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.5%    |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2.5%    |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2.5%    |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.5%    |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.5%    |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.5%    |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.5%    |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2.5%    |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.5%    |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2.5%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.5%    |
| AMD V120 Processor                              | 1         | 2.5%    |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.5%    |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1         | 2.5%    |
| AMD Mobile Sempron Processor 3000+              | 1         | 2.5%    |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.5%    |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2.5%    |
| AMD Athlon Processor                            | 1         | 2.5%    |
| AMD Athlon Neo Processor MV-40                  | 1         | 2.5%    |
| AMD Athlon II X2 250 Processor                  | 1         | 2.5%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.5%    |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G   | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 6         | 15%     |
| Intel Celeron           | 5         | 12.5%   |
| Intel Core 2 Duo        | 4         | 10%     |
| Intel Pentium M         | 2         | 5%      |
| Intel Pentium Dual-Core | 2         | 5%      |
| Intel Pentium 4         | 2         | 5%      |
| Intel Core i5           | 2         | 5%      |
| Intel Core i3           | 2         | 5%      |
| Other                   | 1         | 2.5%    |
| Intel Pentium III       | 1         | 2.5%    |
| Intel Core i7           | 1         | 2.5%    |
| Intel Core 2            | 1         | 2.5%    |
| AMD V120                | 1         | 2.5%    |
| AMD Ryzen 7 PRO         | 1         | 2.5%    |
| AMD Ryzen 7             | 1         | 2.5%    |
| AMD Mobile Sempron      | 1         | 2.5%    |
| AMD E                   | 1         | 2.5%    |
| AMD C-70                | 1         | 2.5%    |
| AMD Athlon Neo          | 1         | 2.5%    |
| AMD Athlon II X2        | 1         | 2.5%    |
| AMD Athlon              | 1         | 2.5%    |
| AMD A8                  | 1         | 2.5%    |
| AMD A4                  | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 42.5%   |
| 4      | 11        | 27.5%   |
| 1      | 11        | 27.5%   |
| 8      | 1         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 72.5%   |
| 2      | 11        | 27.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 32        | 80%     |
| 32-bit         | 8         | 20%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 12.5%   |
| 0x30678    | 4         | 10%     |
| 0x1067a    | 4         | 10%     |
| 0x206a7    | 3         | 7.5%    |
| 0x706a1    | 2         | 5%      |
| 0x6fd      | 2         | 5%      |
| 0x010000c8 | 2         | 5%      |
| 0xf49      | 1         | 2.5%    |
| 0xf27      | 1         | 2.5%    |
| 0x806c1    | 1         | 2.5%    |
| 0x706a8    | 1         | 2.5%    |
| 0x6f6      | 1         | 2.5%    |
| 0x6d8      | 1         | 2.5%    |
| 0x695      | 1         | 2.5%    |
| 0x68a      | 1         | 2.5%    |
| 0x406c4    | 1         | 2.5%    |
| 0x40651    | 1         | 2.5%    |
| 0x20655    | 1         | 2.5%    |
| 0x106c2    | 1         | 2.5%    |
| 0x08108102 | 1         | 2.5%    |
| 0x0800820d | 1         | 2.5%    |
| 0x07030106 | 1         | 2.5%    |
| 0x06006705 | 1         | 2.5%    |
| 0x05000119 | 1         | 2.5%    |
| 0x0500010d | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 6         | 15%     |
| Penryn        | 4         | 10%     |
| SandyBridge   | 3         | 7.5%    |
| P6            | 3         | 7.5%    |
| Goldmont plus | 3         | 7.5%    |
| Core          | 3         | 7.5%    |
| Zen+          | 2         | 5%      |
| NetBurst      | 2         | 5%      |
| K8 Hammer     | 2         | 5%      |
| K10           | 2         | 5%      |
| Bonnell       | 2         | 5%      |
| Bobcat        | 2         | 5%      |
| Westmere      | 1         | 2.5%    |
| TigerLake     | 1         | 2.5%    |
| Puma          | 1         | 2.5%    |
| K6            | 1         | 2.5%    |
| Haswell       | 1         | 2.5%    |
| Excavator     | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 21        | 51.22%  |
| AMD                              | 10        | 24.39%  |
| Nvidia                           | 5         | 12.2%   |
| Silicon Integrated Systems [SiS] | 4         | 9.76%   |
| S3 Graphics                      | 1         | 2.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 9.52%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 7.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 7.14%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 4.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 2         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 2         | 4.76%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 2.38%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 2.38%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 2.38%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 2.38%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 2.38%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 2.38%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 2.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 2.38%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 2.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 2.38%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 2.38%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 2.38%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 1         | 2.38%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 2.38%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 2.38%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 2.38%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 2.38%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 1         | 2.38%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 2.38%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 2.38%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 2.38%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 19        | 47.5%   |
| 1 x AMD         | 9         | 22.5%   |
| 1 x Nvidia      | 5         | 12.5%   |
| 1 x SiS         | 4         | 10%     |
| Other           | 1         | 2.5%    |
| 1 x S3 Graphics | 1         | 2.5%    |
| Intel + AMD     | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 80%     |
| Unknown     | 5         | 12.5%   |
| Proprietary | 3         | 7.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 60%     |
| 0.01-0.5   | 11        | 27.5%   |
| 1.01-2.0   | 4         | 10%     |
| 3.01-4.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 23.53%  |
| Chimei Innolux      | 7         | 20.59%  |
| AU Optronics        | 6         | 17.65%  |
| LG Display          | 3         | 8.82%   |
| Hewlett-Packard     | 2         | 5.88%   |
| ViewSonic           | 1         | 2.94%   |
| VIE                 | 1         | 2.94%   |
| Orion               | 1         | 2.94%   |
| HannStar            | 1         | 2.94%   |
| Goldstar            | 1         | 2.94%   |
| Dell                | 1         | 2.94%   |
| CPT                 | 1         | 2.94%   |
| BOE                 | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 5.88%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 5.88%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 2.94%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 2.94%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 340x190mm 15.3-inch       | 1         | 2.94%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 2.94%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch    | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 2.94%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 2.94%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 2.94%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 2.94%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1         | 2.94%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 2.94%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 2.94%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 2.94%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 2.94%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch         | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch         | 1         | 2.94%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch           | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 12        | 35.29%  |
| 1920x1080 (FHD)    | 9         | 26.47%  |
| 1600x900 (HD+)     | 5         | 14.71%  |
| 1280x800 (WXGA)    | 3         | 8.82%   |
| 3840x2160 (4K)     | 1         | 2.94%   |
| 2160x1440          | 1         | 2.94%   |
| 1920x540           | 1         | 2.94%   |
| 1920x1200 (WUXGA)  | 1         | 2.94%   |
| 1680x1050 (WSXGA+) | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 44.12%  |
| 13      | 3         | 8.82%   |
| 23      | 2         | 5.88%   |
| 11      | 2         | 5.88%   |
| 46      | 1         | 2.94%   |
| 40      | 1         | 2.94%   |
| 31      | 1         | 2.94%   |
| 24      | 1         | 2.94%   |
| 22      | 1         | 2.94%   |
| 20      | 1         | 2.94%   |
| 19      | 1         | 2.94%   |
| 18      | 1         | 2.94%   |
| 17      | 1         | 2.94%   |
| 14      | 1         | 2.94%   |
| 12      | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 50%     |
| 201-300     | 4         | 11.76%  |
| 501-600     | 3         | 8.82%   |
| 401-500     | 3         | 8.82%   |
| 351-400     | 3         | 8.82%   |
| 801-900     | 1         | 2.94%   |
| 601-700     | 1         | 2.94%   |
| 1001-1500   | 1         | 2.94%   |
| Unknown     | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 77.42%  |
| 16/10 | 5         | 16.13%  |
| 32/9  | 1         | 3.23%   |
| 3/2   | 1         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 44.12%  |
| 81-90          | 4         | 11.76%  |
| 201-250        | 3         | 8.82%   |
| 51-60          | 2         | 5.88%   |
| 151-200        | 2         | 5.88%   |
| 501-1000       | 2         | 5.88%   |
| 61-70          | 1         | 2.94%   |
| 351-500        | 1         | 2.94%   |
| 251-300        | 1         | 2.94%   |
| 141-150        | 1         | 2.94%   |
| 121-130        | 1         | 2.94%   |
| Unknown        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 13        | 38.24%  |
| 51-100  | 11        | 32.35%  |
| 121-160 | 6         | 17.65%  |
| 161-240 | 2         | 5.88%   |
| 1-50    | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 87.5%   |
| 2     | 2         | 5%      |
| 0     | 2         | 5%      |
| 3     | 1         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 28        | 43.08%  |
| Qualcomm Atheros                 | 12        | 18.46%  |
| Intel                            | 10        | 15.38%  |
| Silicon Integrated Systems [SiS] | 3         | 4.62%   |
| Samsung Electronics              | 2         | 3.08%   |
| Broadcom                         | 2         | 3.08%   |
| Xiaomi                           | 1         | 1.54%   |
| Motorola PCS                     | 1         | 1.54%   |
| Marvell Technology Group         | 1         | 1.54%   |
| LG Electronics                   | 1         | 1.54%   |
| JMicron Technology               | 1         | 1.54%   |
| IBM                              | 1         | 1.54%   |
| Broadcom Limited                 | 1         | 1.54%   |
| Accton Technology                | 1         | 1.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 9         | 12.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 9         | 12.68%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 3         | 4.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 4.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 4.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                 | 2         | 2.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 2.82%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                  | 2         | 2.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 2.82%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 2.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 2.82%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 2         | 2.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                              | 1         | 1.41%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                   | 1         | 1.41%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                     | 1         | 1.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter               | 1         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.41%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 1.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                    | 1         | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 1.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 1.41%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 1.41%   |
| Motorola PCS Moto E (4) Plus                                                | 1         | 1.41%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                     | 1         | 1.41%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                         | 1         | 1.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                      | 1         | 1.41%   |
| Intel Wireless 3165                                                         | 1         | 1.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller            | 1         | 1.41%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller           | 1         | 1.41%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                          | 1         | 1.41%   |
| Intel 82577LC Gigabit Network Connection                                    | 1         | 1.41%   |
| IBM Winnipeg PCI-X Host Bridge                                              | 1         | 1.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                             | 1         | 1.41%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.41%   |
| Accton EN-1216 Ethernet Adapter                                             | 1         | 1.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 12        | 41.38%  |
| Intel                 | 8         | 27.59%  |
| Realtek Semiconductor | 7         | 24.14%  |
| Broadcom Limited      | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 10.34%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 10.34%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 6.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 6.9%    |
| Intel Wi-Fi 6 AX200                                                         | 2         | 6.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 6.9%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 2         | 6.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 3.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 3.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 3.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 3.45%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 3.45%   |
| Intel Wireless 3165                                                         | 1         | 3.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 3.45%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 24        | 63.16%  |
| Silicon Integrated Systems [SiS] | 2         | 5.26%   |
| Samsung Electronics              | 2         | 5.26%   |
| Intel                            | 2         | 5.26%   |
| Xiaomi                           | 1         | 2.63%   |
| Qualcomm Atheros                 | 1         | 2.63%   |
| Motorola PCS                     | 1         | 2.63%   |
| Marvell Technology Group         | 1         | 2.63%   |
| LG Electronics                   | 1         | 2.63%   |
| JMicron Technology               | 1         | 2.63%   |
| Broadcom                         | 1         | 2.63%   |
| Accton Technology                | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 23.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 23.68%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 7.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 5.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 5.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.63%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 2.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.63%   |
| Motorola PCS Moto E (4) Plus                                      | 1         | 2.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.63%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.63%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 2.63%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.63%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 36        | 52.17%  |
| WiFi     | 29        | 42.03%  |
| Modem    | 3         | 4.35%   |
| Unknown  | 1         | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 55.26%  |
| Ethernet | 17        | 44.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 57.5%   |
| 1     | 12        | 30%     |
| 0     | 4         | 10%     |
| 3     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 37        | 92.5%   |
| Yes  | 3         | 7.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 4         | 25%     |
| Intel                           | 4         | 25%     |
| Realtek Semiconductor           | 3         | 18.75%  |
| Toshiba                         | 1         | 6.25%   |
| Hewlett-Packard                 | 1         | 6.25%   |
| Cambridge Silicon Radio         | 1         | 6.25%   |
| ASUSTek Computer                | 1         | 6.25%   |
| Alps Electric                   | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 3         | 18.75%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 18.75%  |
| Intel AX200 Bluetooth                               | 2         | 12.5%   |
| Toshiba Askey for                                   | 1         | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 6.25%   |
| Intel Bluetooth wireless interface                  | 1         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 6.25%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.25%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 6.25%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 56.41%  |
| AMD                              | 10        | 25.64%  |
| Silicon Integrated Systems [SiS] | 3         | 7.69%   |
| Nvidia                           | 3         | 7.69%   |
| ESS Technology                   | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 6.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 6.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 6.38%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 4.26%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 4.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.26%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 4.26%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 4.26%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 4.26%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.26%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 2.13%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 2.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.13%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.13%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 2.13%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.13%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 2.13%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2.13%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.13%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 2.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 2.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 18        | 45%     |
| Samsung Electronics | 8         | 20%     |
| SK hynix            | 4         | 10%     |
| Unknown (ABCD)      | 2         | 5%      |
| Kingston            | 2         | 5%      |
| Transcend           | 1         | 2.5%    |
| Toshiba             | 1         | 2.5%    |
| Teikon              | 1         | 2.5%    |
| Team                | 1         | 2.5%    |
| Elpida              | 1         | 2.5%    |
| A-DATA Technology   | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                                  | 4         | 9.3%    |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                        | 2         | 4.65%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 4.65%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 4.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 4.65%   |
| Unknown RAM Module 512MB SODIMM SDRAM                               | 1         | 2.33%   |
| Unknown RAM Module 512MB DIMM 400MT/s                               | 1         | 2.33%   |
| Unknown RAM Module 512MB DIMM                                       | 1         | 2.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DDR                                   | 1         | 2.33%   |
| Unknown RAM Module 256MB SODIMM SDRAM                               | 1         | 2.33%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                              | 1         | 2.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                       | 1         | 2.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 2.33%   |
| Unknown RAM Module 1GB SODIMM DRAM                                  | 1         | 2.33%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                           | 1         | 2.33%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                           | 1         | 2.33%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s             | 1         | 2.33%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                         | 1         | 2.33%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s                  | 1         | 2.33%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                   | 1         | 2.33%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s                | 1         | 2.33%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s                  | 1         | 2.33%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                     | 1         | 2.33%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s               | 1         | 2.33%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s              | 1         | 2.33%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 2.33%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 2.33%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 2.33%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 2.33%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s               | 1         | 2.33%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s                | 1         | 2.33%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s              | 1         | 2.33%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s               | 1         | 2.33%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s                | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 13        | 34.21%  |
| SDRAM   | 7         | 18.42%  |
| DDR2    | 6         | 15.79%  |
| DDR4    | 5         | 13.16%  |
| LPDDR4  | 2         | 5.26%   |
| DDR     | 2         | 5.26%   |
| Unknown | 2         | 5.26%   |
| DRAM    | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 28        | 73.68%  |
| DIMM   | 10        | 26.32%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 13        | 32.5%   |
| 2048  | 13        | 32.5%   |
| 1024  | 7         | 17.5%   |
| 512   | 3         | 7.5%    |
| 16384 | 2         | 5%      |
| 8192  | 1         | 2.5%    |
| 256   | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 25%     |
| 1333    | 5         | 12.5%   |
| 2400    | 4         | 10%     |
| 1600    | 4         | 10%     |
| 1334    | 3         | 7.5%    |
| 1067    | 2         | 5%      |
| 1066    | 2         | 5%      |
| 266     | 2         | 5%      |
| 4199    | 1         | 2.5%    |
| 3600    | 1         | 2.5%    |
| 3266    | 1         | 2.5%    |
| 3200    | 1         | 2.5%    |
| 2667    | 1         | 2.5%    |
| 2048    | 1         | 2.5%    |
| 800     | 1         | 2.5%    |
| 400     | 1         | 2.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Brother HL-1110 series | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 4         | 22.22%  |
| Microdia                               | 2         | 11.11%  |
| IMC Networks                           | 2         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 11.11%  |
| Acer                                   | 2         | 11.11%  |
| Suyin                                  | 1         | 5.56%   |
| Silicon Motion                         | 1         | 5.56%   |
| Ricoh                                  | 1         | 5.56%   |
| Realtek Semiconductor                  | 1         | 5.56%   |
| ALi                                    | 1         | 5.56%   |
| Alcor Micro                            | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 5.56%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 5.56%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 5.56%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 5.56%   |
| Microdia Webcam Vitade AF                                   | 1         | 5.56%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 5.56%   |
| IMC Networks Integrated Camera                              | 1         | 5.56%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 5.56%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 5.56%   |
| Chicony Integrated Camera                                   | 1         | 5.56%   |
| Chicony HP Webcam                                           | 1         | 5.56%   |
| Chicony HP HD Webcam                                        | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 5.56%   |
| ALi M5603 Video Camera Controller                           | 1         | 5.56%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 5.56%   |
| Acer USB Camera                                             | 1         | 5.56%   |
| Acer EasyCamera                                             | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 66.67%  |
| Synaptics        | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 33.33%  |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 33.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 33.33%  |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 31        | 77.5%   |
| 1     | 5         | 12.5%   |
| 2     | 4         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 6         | 46.15%  |
| Fingerprint reader       | 3         | 23.08%  |
| Network                  | 1         | 7.69%   |
| Flash memory             | 1         | 7.69%   |
| Communication controller | 1         | 7.69%   |
| Camera                   | 1         | 7.69%   |

