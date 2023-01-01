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

Total: 60

| Vendor        | Model                    | Form-Factor | Probe                                                      | Date         |
|---------------|--------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | G41M4                    | Desktop     | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU     | Notebook    | [ce2f3fb897](https://linux-hardware.org/?probe=ce2f3fb897) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU     | Notebook    | [50f1d0a765](https://linux-hardware.org/?probe=50f1d0a765) | Dec 19, 2022 |
| IBM           | ThinkPad T42 2378FVU     | Notebook    | [fe6bdea3fd](https://linux-hardware.org/?probe=fe6bdea3fd) | Dec 19, 2022 |
| Unknown       | V00                      | Mini pc     | [15a2312211](https://linux-hardware.org/?probe=15a2312211) | Nov 26, 2022 |
| ASRock        | J3455B-ITX               | Desktop     | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| Google        | Cave                     | Notebook    | [ce7f60e0ee](https://linux-hardware.org/?probe=ce7f60e0ee) | Nov 06, 2022 |
| Google        | Cave                     | Notebook    | [63e06049da](https://linux-hardware.org/?probe=63e06049da) | Nov 06, 2022 |
| ASRock        | B450M Pro4               | Desktop     | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0               | Desktop     | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| ASRock        | J3455B-ITX               | Desktop     | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| Gigabyte      | AB350-Gaming-CF          | Desktop     | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Foxconn       | 2ABF                     | Desktop     | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Q4OS 4 | 27        | 56.25%  |
| Q4OS 3 | 16        | 33.33%  |
| Q4OS 2 | 5         | 10.42%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 48        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-19-amd64        | 4         | 8.33%   |
| 4.19.0-17-amd64        | 4         | 8.33%   |
| 5.10.0-12-amd64        | 3         | 6.25%   |
| 5.10.0-8-amd64         | 2         | 4.17%   |
| 5.10.0-14-686-pae      | 2         | 4.17%   |
| 5.10.0-10-686-pae      | 2         | 4.17%   |
| 6.0.0-1-amd64          | 1         | 2.08%   |
| 5.9.0-5-amd64          | 1         | 2.08%   |
| 5.6.0-1-amd64          | 1         | 2.08%   |
| 5.18.0-0.bpo.1-amd64   | 1         | 2.08%   |
| 5.10.0-9-amd64         | 1         | 2.08%   |
| 5.10.0-9-686-pae       | 1         | 2.08%   |
| 5.10.0-8-686-pae       | 1         | 2.08%   |
| 5.10.0-20-686          | 1         | 2.08%   |
| 5.10.0-17-amd64        | 1         | 2.08%   |
| 5.10.0-15-686-pae      | 1         | 2.08%   |
| 5.10.0-14-amd64        | 1         | 2.08%   |
| 5.10.0-13-amd64        | 1         | 2.08%   |
| 5.10.0-12-686-pae      | 1         | 2.08%   |
| 5.10.0-11-686-pae      | 1         | 2.08%   |
| 4.9.0-9-686-pae        | 1         | 2.08%   |
| 4.9.0-8-amd64          | 1         | 2.08%   |
| 4.9.0-14-686-pae       | 1         | 2.08%   |
| 4.9.0-12-686-pae       | 1         | 2.08%   |
| 4.19.0-6-amd64         | 1         | 2.08%   |
| 4.19.0-22-amd64        | 1         | 2.08%   |
| 4.19.0-21-amd64        | 1         | 2.08%   |
| 4.19.0-20-amd64        | 1         | 2.08%   |
| 4.19.0-17-686-pae      | 1         | 2.08%   |
| 4.19.0-17-686          | 1         | 2.08%   |
| 4.19.0-16-amd64        | 1         | 2.08%   |
| 4.19.0-16-686          | 1         | 2.08%   |
| 4.19.0-14-amd64        | 1         | 2.08%   |
| 4.19.0-13-amd64        | 1         | 2.08%   |
| 4.19.0-12-amd64        | 1         | 2.08%   |
| 4.19.0-10-amd64        | 1         | 2.08%   |
| 4.19.0-0.bpo.5-686-pae | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 23        | 47.92%  |
| 4.19.0  | 17        | 35.42%  |
| 4.9.0   | 4         | 8.33%   |
| 6.0.0   | 1         | 2.08%   |
| 5.9.0   | 1         | 2.08%   |
| 5.6.0   | 1         | 2.08%   |
| 5.18.0  | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 23        | 47.92%  |
| 4.19    | 17        | 35.42%  |
| 4.9     | 4         | 8.33%   |
| 6.0     | 1         | 2.08%   |
| 5.9     | 1         | 2.08%   |
| 5.6     | 1         | 2.08%   |
| 5.18    | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 64.58%  |
| i686   | 17        | 35.42%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trinity  | 27        | 56.25%  |
| KDE5     | 18        | 37.5%   |
| LXDE     | 1         | 2.08%   |
| KDE      | 1         | 2.08%   |
| Cinnamon | 1         | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 47        | 97.92%  |
| Tty  | 1         | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 27        | 56.25%  |
| SDDM    | 20        | 41.67%  |
| LightDM | 1         | 2.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 17        | 35.42%  |
| it_IT   | 4         | 8.33%   |
| es_ES   | 3         | 6.25%   |
| en_GB   | 3         | 6.25%   |
| de_DE   | 3         | 6.25%   |
| Unknown | 3         | 6.25%   |
| fr_FR   | 2         | 4.17%   |
| sv_SE   | 1         | 2.08%   |
| sl_SI   | 1         | 2.08%   |
| sk_SK   | 1         | 2.08%   |
| ru_RU   | 1         | 2.08%   |
| pt_BR   | 1         | 2.08%   |
| pl_PL   | 1         | 2.08%   |
| es_VE   | 1         | 2.08%   |
| es_AR   | 1         | 2.08%   |
| en_ZA   | 1         | 2.08%   |
| en_SG   | 1         | 2.08%   |
| en_IE   | 1         | 2.08%   |
| C       | 1         | 2.08%   |
| bg_BG   | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 30        | 62.5%   |
| EFI  | 18        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 45        | 93.75%  |
| Overlay | 3         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 25        | 52.08%  |
| GPT     | 22        | 45.83%  |
| Unknown | 1         | 2.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 87.5%   |
| Yes       | 6         | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 64.58%  |
| Yes       | 17        | 35.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 7         | 14.58%  |
| Toshiba                     | 4         | 8.33%   |
| MSI                         | 4         | 8.33%   |
| ASUSTek Computer            | 4         | 8.33%   |
| ASRock                      | 4         | 8.33%   |
| Lenovo                      | 3         | 6.25%   |
| TrekStor                    | 2         | 4.17%   |
| Medion                      | 2         | 4.17%   |
| Gigabyte Technology         | 2         | 4.17%   |
| Visual Land                 | 1         | 2.08%   |
| TECO Electric and Machinery | 1         | 2.08%   |
| Sony                        | 1         | 2.08%   |
| Qilive                      | 1         | 2.08%   |
| Phoenix/SiS                 | 1         | 2.08%   |
| Philco                      | 1         | 2.08%   |
| Packard Bell                | 1         | 2.08%   |
| JVC                         | 1         | 2.08%   |
| IBM                         | 1         | 2.08%   |
| Google                      | 1         | 2.08%   |
| Foxconn                     | 1         | 2.08%   |
| Compaq                      | 1         | 2.08%   |
| Chuwi                       | 1         | 2.08%   |
| BESSTAR Tech                | 1         | 2.08%   |
| AMI                         | 1         | 2.08%   |
| Acer                        | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 4.17%   |
| Toshiba Satellite C660                 | 2         | 4.17%   |
| Visual Land Premier 10                 | 1         | 2.08%   |
| Toshiba Satellite Pro L500             | 1         | 2.08%   |
| Toshiba Satellite M70                  | 1         | 2.08%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 2.08%   |
| Sony VGN-P11Z_Q                        | 1         | 2.08%   |
| Qilive QW19141AMSP                     | 1         | 2.08%   |
| Phoenix/SiS M720SR                     | 1         | 2.08%   |
| Philco 14I                             | 1         | 2.08%   |
| Packard Bell EasyNote LM81             | 1         | 2.08%   |
| MSI U210                               | 1         | 2.08%   |
| MSI MS-7C56                            | 1         | 2.08%   |
| MSI MS-7597                            | 1         | 2.08%   |
| MSI MS-7592                            | 1         | 2.08%   |
| Medion P6620                           | 1         | 2.08%   |
| Lenovo ThinkPad T495 20NKS0PG00        | 1         | 2.08%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 2.08%   |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 2.08%   |
| JVC J3N                                | 1         | 2.08%   |
| IBM ThinkPad T42 2378FVU               | 1         | 2.08%   |
| HP ProBook 6550b                       | 1         | 2.08%   |
| HP ProBook 450 G2                      | 1         | 2.08%   |
| HP Presario CQ56                       | 1         | 2.08%   |
| HP OmniBook PC                         | 1         | 2.08%   |
| HP Laptop 15s-fq2xxx                   | 1         | 2.08%   |
| HP 250 G5 Notebook PC                  | 1         | 2.08%   |
| HP 2000                                | 1         | 2.08%   |
| Google Cave                            | 1         | 2.08%   |
| Gigabyte XP-M5S661GX                   | 1         | 2.08%   |
| Gigabyte AB350-Gaming                  | 1         | 2.08%   |
| Foxconn Pro 3400 Series MT             | 1         | 2.08%   |
| Compaq Evo D510 SFF                    | 1         | 2.08%   |
| Chuwi GemiBook Pro                     | 1         | 2.08%   |
| BESSTAR Tech UM250                     | 1         | 2.08%   |
| ASUS X540YA                            | 1         | 2.08%   |
| ASUS T12Eg                             | 1         | 2.08%   |
| ASUS A6U                               | 1         | 2.08%   |
| ASUS A6JC                              | 1         | 2.08%   |
| ASRock J3455B-ITX                      | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 8.33%   |
| TrekStor SurfTab                  | 2         | 4.17%   |
| Lenovo ThinkPad                   | 2         | 4.17%   |
| HP ProBook                        | 2         | 4.17%   |
| Visual Land Premier               | 1         | 2.08%   |
| TECO Electric and Machinery FUTRO | 1         | 2.08%   |
| Sony VGN-P11Z                     | 1         | 2.08%   |
| Qilive QW19141AMSP                | 1         | 2.08%   |
| Phoenix/SiS M720SR                | 1         | 2.08%   |
| Philco 14I                        | 1         | 2.08%   |
| Packard Bell EasyNote             | 1         | 2.08%   |
| MSI U210                          | 1         | 2.08%   |
| MSI MS-7C56                       | 1         | 2.08%   |
| MSI MS-7597                       | 1         | 2.08%   |
| MSI MS-7592                       | 1         | 2.08%   |
| Medion P6620                      | 1         | 2.08%   |
| Lenovo IdeaPad                    | 1         | 2.08%   |
| JVC J3N                           | 1         | 2.08%   |
| IBM ThinkPad                      | 1         | 2.08%   |
| HP Presario                       | 1         | 2.08%   |
| HP OmniBook                       | 1         | 2.08%   |
| HP Laptop                         | 1         | 2.08%   |
| HP 250                            | 1         | 2.08%   |
| HP 2000                           | 1         | 2.08%   |
| Google Cave                       | 1         | 2.08%   |
| Gigabyte XP-M5S661GX              | 1         | 2.08%   |
| Gigabyte AB350-Gaming             | 1         | 2.08%   |
| Foxconn Pro                       | 1         | 2.08%   |
| Compaq Evo                        | 1         | 2.08%   |
| Chuwi GemiBook                    | 1         | 2.08%   |
| BESSTAR Tech UM250                | 1         | 2.08%   |
| ASUS X540YA                       | 1         | 2.08%   |
| ASUS T12Eg                        | 1         | 2.08%   |
| ASUS A6U                          | 1         | 2.08%   |
| ASUS A6JC                         | 1         | 2.08%   |
| ASRock J3455B-ITX                 | 1         | 2.08%   |
| ASRock H61M-HVS                   | 1         | 2.08%   |
| ASRock G41M-VS3                   | 1         | 2.08%   |
| ASRock B450M                      | 1         | 2.08%   |
| AMI Intel                         | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 12.5%   |
| 2009    | 5         | 10.42%  |
| 2020    | 4         | 8.33%   |
| 2011    | 4         | 8.33%   |
| 2016    | 3         | 6.25%   |
| 2015    | 3         | 6.25%   |
| 2005    | 3         | 6.25%   |
| 2019    | 2         | 4.17%   |
| 2018    | 2         | 4.17%   |
| 2017    | 2         | 4.17%   |
| 2014    | 2         | 4.17%   |
| 2008    | 2         | 4.17%   |
| 2004    | 2         | 4.17%   |
| Unknown | 2         | 4.17%   |
| 2022    | 1         | 2.08%   |
| 2021    | 1         | 2.08%   |
| 2012    | 1         | 2.08%   |
| 2007    | 1         | 2.08%   |
| 2006    | 1         | 2.08%   |
| 2002    | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 33        | 68.75%  |
| Desktop  | 13        | 27.08%  |
| Tablet   | 2         | 4.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 46        | 95.83%  |
| Enabled  | 2         | 4.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 97.92%  |
| Yes  | 1         | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 13        | 27.08%  |
| 2.01-3.0    | 8         | 16.67%  |
| 4.01-8.0    | 6         | 12.5%   |
| 1.01-2.0    | 6         | 12.5%   |
| 0.51-1.0    | 6         | 12.5%   |
| 16.01-24.0  | 3         | 6.25%   |
| 0.01-0.5    | 2         | 4.17%   |
| 32.01-64.0  | 1         | 2.08%   |
| 24.01-32.0  | 1         | 2.08%   |
| 64.01-256.0 | 1         | 2.08%   |
| 8.01-16.0   | 1         | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 16        | 33.33%  |
| 0.51-1.0  | 12        | 25%     |
| 2.01-3.0  | 8         | 16.67%  |
| 0.01-0.5  | 7         | 14.58%  |
| 3.01-4.0  | 3         | 6.25%   |
| 4.01-8.0  | 1         | 2.08%   |
| 8.01-16.0 | 1         | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 72.92%  |
| 2      | 9         | 18.75%  |
| 3      | 4         | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 50%     |
| No        | 24        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 89.58%  |
| No        | 5         | 10.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 68.75%  |
| No        | 15        | 31.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 62.5%   |
| Yes       | 18        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 7         | 14.58%  |
| Italy        | 5         | 10.42%  |
| UK           | 3         | 6.25%   |
| Spain        | 3         | 6.25%   |
| Kenya        | 3         | 6.25%   |
| Germany      | 3         | 6.25%   |
| Switzerland  | 2         | 4.17%   |
| Romania      | 2         | 4.17%   |
| Poland       | 2         | 4.17%   |
| France       | 2         | 4.17%   |
| Brazil       | 2         | 4.17%   |
| Venezuela    | 1         | 2.08%   |
| Sweden       | 1         | 2.08%   |
| South Africa | 1         | 2.08%   |
| Slovenia     | 1         | 2.08%   |
| Slovakia     | 1         | 2.08%   |
| Singapore    | 1         | 2.08%   |
| Saudi Arabia | 1         | 2.08%   |
| Russia       | 1         | 2.08%   |
| Qatar        | 1         | 2.08%   |
| Netherlands  | 1         | 2.08%   |
| Bulgaria     | 1         | 2.08%   |
| Belgium      | 1         | 2.08%   |
| Belarus      | 1         | 2.08%   |
| Argentina    | 1         | 2.08%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 6.25%   |
| Zurich                | 2         | 4.17%   |
| Swindon               | 2         | 4.17%   |
| Rostock               | 2         | 4.17%   |
| Mesa                  | 2         | 4.17%   |
| Drobeta-Turnu Severin | 2         | 4.17%   |
| Bologna               | 2         | 4.17%   |
| Tranas                | 1         | 2.08%   |
| The Hague             | 1         | 2.08%   |
| Tellico Plains        | 1         | 2.08%   |
| Sosnowiec             | 1         | 2.08%   |
| Sofia                 | 1         | 2.08%   |
| Singapore             | 1         | 2.08%   |
| Schermbeck            | 1         | 2.08%   |
| Salsomaggiore Terme   | 1         | 2.08%   |
| Rome                  | 1         | 2.08%   |
| Puerto Cumarebo       | 1         | 2.08%   |
| Posadas               | 1         | 2.08%   |
| Moscow                | 1         | 2.08%   |
| Mooresville           | 1         | 2.08%   |
| Moirans               | 1         | 2.08%   |
| Mogilev               | 1         | 2.08%   |
| Londrina              | 1         | 2.08%   |
| Ljubljana             | 1         | 2.08%   |
| Las Vegas             | 1         | 2.08%   |
| Klaudyn               | 1         | 2.08%   |
| Johannesburg          | 1         | 2.08%   |
| Indianapolis          | 1         | 2.08%   |
| Guarulhos             | 1         | 2.08%   |
| Grand Junction        | 1         | 2.08%   |
| Gijón                | 1         | 2.08%   |
| Fulham                | 1         | 2.08%   |
| Doha                  | 1         | 2.08%   |
| Dammam                | 1         | 2.08%   |
| Calvecchia            | 1         | 2.08%   |
| Brussels              | 1         | 2.08%   |
| Bratislava            | 1         | 2.08%   |
| Boulogne-sur-Mer      | 1         | 2.08%   |
| Barcelona             | 1         | 2.08%   |
| Alicante              | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 15.79%  |
| Unknown             | 7         | 7      | 12.28%  |
| Seagate             | 7         | 8      | 12.28%  |
| Samsung Electronics | 5         | 5      | 8.77%   |
| SanDisk             | 3         | 3      | 5.26%   |
| Kingston            | 3         | 3      | 5.26%   |
| Hitachi             | 3         | 3      | 5.26%   |
| China               | 3         | 4      | 5.26%   |
| Toshiba             | 2         | 2      | 3.51%   |
| KESU                | 2         | 2      | 3.51%   |
| HGST                | 2         | 2      | 3.51%   |
| A-DATA Technology   | 2         | 2      | 3.51%   |
| Unknown             | 2         | 2      | 3.51%   |
| Unknown (CF)        | 1         | 1      | 1.75%   |
| SPCC                | 1         | 1      | 1.75%   |
| Silicon Motion      | 1         | 1      | 1.75%   |
| Phison              | 1         | 1      | 1.75%   |
| Maxtor              | 1         | 1      | 1.75%   |
| Fujitsu             | 1         | 1      | 1.75%   |
| Crucial             | 1         | 2      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 3.33%   |
| Samsung SSD 850 EVO 250GB            | 2         | 3.33%   |
| KESU USB 3.1 256GB                   | 2         | 3.33%   |
| Unknown                              | 2         | 3.33%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.67%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.67%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 1.67%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.67%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.67%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.67%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 1.67%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 1.67%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.67%   |
| Unknown USDU1  32GB                  | 1         | 1.67%   |
| Unknown SLD64G  64GB                 | 1         | 1.67%   |
| Unknown SD/MMC/MS PRO 64GB           | 1         | 1.67%   |
| Unknown MMC Card  64GB               | 1         | 1.67%   |
| Unknown 064G38  64GB                 | 1         | 1.67%   |
| Unknown (CF) Card 16GB SSD           | 1         | 1.67%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.67%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.67%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1.67%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.67%   |
| Seagate ST9120822AS 120GB            | 1         | 1.67%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1.67%   |
| Seagate ST3500413AS 500GB            | 1         | 1.67%   |
| Seagate ST3160815AS 160GB            | 1         | 1.67%   |
| Seagate ST3160812AS 160GB            | 1         | 1.67%   |
| Seagate ST310211A 10GB               | 1         | 1.67%   |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 1.67%   |
| Seagate Backup+ SL 1TB               | 1         | 1.67%   |
| SanDisk SDSSDA120G 120GB             | 1         | 1.67%   |
| SanDisk SDCFX-032G SSD               | 1         | 1.67%   |
| SanDisk SD8SN8U1T001122 1024GB SSD   | 1         | 1.67%   |
| Samsung SSD 860 EVO 250GB            | 1         | 1.67%   |
| Samsung HD081GJ 80GB                 | 1         | 1.67%   |
| Samsung AWMB3R  16GB                 | 1         | 1.67%   |
| Phison APS-SE20G-1T                  | 1         | 1.67%   |
| Maxtor 6Y080L0 81GB                  | 1         | 1.67%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 29.17%  |
| Seagate             | 6         | 7      | 25%     |
| Hitachi             | 3         | 3      | 12.5%   |
| Toshiba             | 2         | 2      | 8.33%   |
| HGST                | 2         | 2      | 8.33%   |
| Unknown             | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| Maxtor              | 1         | 1      | 4.17%   |
| Fujitsu             | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 16.67%  |
| Samsung Electronics | 3         | 3      | 16.67%  |
| Kingston            | 3         | 3      | 16.67%  |
| China               | 3         | 4      | 16.67%  |
| Unknown             | 2         | 2      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| Unknown (CF)        | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| A-DATA Technology   | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 21        | 25     | 39.62%  |
| SSD     | 17        | 19     | 32.08%  |
| MMC     | 7         | 7      | 13.21%  |
| NVMe    | 5         | 6      | 9.43%   |
| Unknown | 3         | 3      | 5.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 43     | 69.23%  |
| MMC  | 7         | 7      | 13.46%  |
| NVMe | 5         | 6      | 9.62%   |
| SAS  | 4         | 4      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 38     | 84.21%  |
| 0.51-1.0   | 4         | 4      | 10.53%  |
| 1.01-2.0   | 1         | 1      | 2.63%   |
| 4.01-10.0  | 1         | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 10        | 20.83%  |
| 51-100         | 9         | 18.75%  |
| 251-500        | 7         | 14.58%  |
| 101-250        | 7         | 14.58%  |
| 21-50          | 6         | 12.5%   |
| 1001-2000      | 4         | 8.33%   |
| 501-1000       | 3         | 6.25%   |
| More than 3000 | 1         | 2.08%   |
| Unknown        | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 32        | 66.67%  |
| 21-50          | 6         | 12.5%   |
| 251-500        | 2         | 4.17%   |
| 101-250        | 2         | 4.17%   |
| 501-1000       | 2         | 4.17%   |
| 51-100         | 2         | 4.17%   |
| More than 3000 | 1         | 2.08%   |
| Unknown        | 1         | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD400BD-23JMC0 40GB       | 1         | 1      | 10%     |
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 10%     |
| Seagate ST9120822AS 120GB     | 1         | 1      | 10%     |
| Maxtor 6Y080L0 81GB           | 1         | 1      | 10%     |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 10%     |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 10%     |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 10%     |
| HGST HTS725050A7E630 500GB    | 1         | 1      | 10%     |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 10%     |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 30        | 38     | 58.82%  |
| Detected | 11        | 12     | 21.57%  |
| Malfunc  | 10        | 10     | 19.61%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 27        | 57.45%  |
| AMD                              | 10        | 21.28%  |
| Silicon Integrated Systems [SiS] | 4         | 8.51%   |
| Silicon Motion                   | 1         | 2.13%   |
| SanDisk                          | 1         | 2.13%   |
| Phison Electronics               | 1         | 2.13%   |
| Nvidia                           | 1         | 2.13%   |
| Micron/Crucial Technology        | 1         | 2.13%   |
| ADATA Technology                 | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 12.07%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 4         | 6.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 5.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 5.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 5.17%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 3.45%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 3.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.72%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.72%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 1.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.72%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.72%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.72%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.72%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.72%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.72%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.72%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 1.72%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.72%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.72%   |
| AMD 500 Series Chipset SATA Controller                                           | 1         | 1.72%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.72%   |
| AMD 300 Series Chipset SATA Controller                                           | 1         | 1.72%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 25        | 52.08%  |
| IDE  | 17        | 35.42%  |
| NVMe | 4         | 8.33%   |
| RAID | 2         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 70.83%  |
| AMD    | 14        | 29.17%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz                 | 3         | 6.25%   |
| Intel Pentium M processor 1.70GHz               | 2         | 4.17%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 4.17%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 4.17%   |
| Intel Pentium M processor 1000MHz               | 1         | 2.08%   |
| Intel Pentium III (Coppermine)                  | 1         | 2.08%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2.08%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1         | 2.08%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 2.08%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1         | 2.08%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1         | 2.08%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 2.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 2.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.08%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1         | 2.08%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2.08%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.08%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.08%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.08%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.08%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.08%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2.08%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1         | 2.08%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.08%   |
| AMD V120 Processor                              | 1         | 2.08%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.08%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1         | 2.08%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1         | 2.08%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 2.08%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 2.08%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.08%   |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2.08%   |
| AMD Athlon Processor                            | 1         | 2.08%   |
| AMD Athlon Neo Processor MV-40                  | 1         | 2.08%   |
| AMD Athlon II X2 250 Processor                  | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 6         | 12.5%   |
| Intel Atom              | 6         | 12.5%   |
| Intel Core 2 Duo        | 4         | 8.33%   |
| Intel Pentium M         | 3         | 6.25%   |
| Intel Pentium Dual-Core | 3         | 6.25%   |
| Intel Core i5           | 3         | 6.25%   |
| Intel Pentium 4         | 2         | 4.17%   |
| Intel Core i3           | 2         | 4.17%   |
| AMD Ryzen 7             | 2         | 4.17%   |
| AMD Athlon              | 2         | 4.17%   |
| Other                   | 1         | 2.08%   |
| Intel Pentium III       | 1         | 2.08%   |
| Intel Core m3           | 1         | 2.08%   |
| Intel Core i7           | 1         | 2.08%   |
| Intel Core 2            | 1         | 2.08%   |
| AMD V120                | 1         | 2.08%   |
| AMD Ryzen 7 PRO         | 1         | 2.08%   |
| AMD Ryzen 5 PRO         | 1         | 2.08%   |
| AMD Mobile Sempron      | 1         | 2.08%   |
| AMD E                   | 1         | 2.08%   |
| AMD C-70                | 1         | 2.08%   |
| AMD Athlon Neo          | 1         | 2.08%   |
| AMD Athlon II X2        | 1         | 2.08%   |
| AMD A8                  | 1         | 2.08%   |
| AMD A4                  | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 41.67%  |
| 4      | 14        | 29.17%  |
| 1      | 12        | 25%     |
| 8      | 2         | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 68.75%  |
| 2      | 15        | 31.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 39        | 81.25%  |
| 32-bit         | 9         | 18.75%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 12.5%   |
| 0x1067a    | 5         | 10.42%  |
| 0x30678    | 4         | 8.33%   |
| 0x206a7    | 4         | 8.33%   |
| 0x706a1    | 2         | 4.17%   |
| 0x6fd      | 2         | 4.17%   |
| 0x0810100b | 2         | 4.17%   |
| 0x010000c8 | 2         | 4.17%   |
| 0xf49      | 1         | 2.08%   |
| 0xf27      | 1         | 2.08%   |
| 0x806c1    | 1         | 2.08%   |
| 0x706a8    | 1         | 2.08%   |
| 0x6f6      | 1         | 2.08%   |
| 0x6d8      | 1         | 2.08%   |
| 0x6d6      | 1         | 2.08%   |
| 0x695      | 1         | 2.08%   |
| 0x68a      | 1         | 2.08%   |
| 0x406e3    | 1         | 2.08%   |
| 0x406c4    | 1         | 2.08%   |
| 0x40651    | 1         | 2.08%   |
| 0x20655    | 1         | 2.08%   |
| 0x106c2    | 1         | 2.08%   |
| 0x08701013 | 1         | 2.08%   |
| 0x08108102 | 1         | 2.08%   |
| 0x0800820d | 1         | 2.08%   |
| 0x07030106 | 1         | 2.08%   |
| 0x06006705 | 1         | 2.08%   |
| 0x05000119 | 1         | 2.08%   |
| 0x0500010d | 1         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 6         | 12.5%   |
| Penryn        | 5         | 10.42%  |
| SandyBridge   | 4         | 8.33%   |
| P6            | 4         | 8.33%   |
| Goldmont plus | 3         | 6.25%   |
| Core          | 3         | 6.25%   |
| Zen+          | 2         | 4.17%   |
| Zen           | 2         | 4.17%   |
| NetBurst      | 2         | 4.17%   |
| K8 Hammer     | 2         | 4.17%   |
| K10           | 2         | 4.17%   |
| Bonnell       | 2         | 4.17%   |
| Bobcat        | 2         | 4.17%   |
| Zen 2         | 1         | 2.08%   |
| Westmere      | 1         | 2.08%   |
| TigerLake     | 1         | 2.08%   |
| Skylake       | 1         | 2.08%   |
| Puma          | 1         | 2.08%   |
| K6            | 1         | 2.08%   |
| Haswell       | 1         | 2.08%   |
| Goldmont      | 1         | 2.08%   |
| Excavator     | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 25        | 51.02%  |
| AMD                              | 13        | 26.53%  |
| Nvidia                           | 6         | 12.24%  |
| Silicon Integrated Systems [SiS] | 4         | 8.16%   |
| S3 Graphics                      | 1         | 2.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 8%      |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 6%      |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 6%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 6%      |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 4%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 2         | 4%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 4%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 4%      |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 2%      |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 2%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 2%      |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 2%      |
| Nvidia GK208B [GeForce GT 710]                                                             | 1         | 2%      |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 2%      |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 2%      |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 2%      |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 2%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 2%      |
| Intel HD Graphics 515                                                                      | 1         | 2%      |
| Intel HD Graphics 500                                                                      | 1         | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 2%      |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 2%      |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 2%      |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 2%      |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 2%      |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 2%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 2%      |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 1         | 2%      |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 2%      |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 1         | 2%      |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 2%      |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 2%      |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 23        | 47.92%  |
| 1 x AMD         | 12        | 25%     |
| 1 x Nvidia      | 6         | 12.5%   |
| 1 x SiS         | 4         | 8.33%   |
| Other           | 1         | 2.08%   |
| 1 x S3 Graphics | 1         | 2.08%   |
| Intel + AMD     | 1         | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 83.33%  |
| Unknown     | 5         | 10.42%  |
| Proprietary | 3         | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 58.33%  |
| 0.01-0.5   | 13        | 27.08%  |
| 1.01-2.0   | 5         | 10.42%  |
| 3.01-4.0   | 1         | 2.08%   |
| 0.51-1.0   | 1         | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 19.51%  |
| Chimei Innolux      | 7         | 17.07%  |
| AU Optronics        | 7         | 17.07%  |
| Philips             | 3         | 7.32%   |
| LG Display          | 3         | 7.32%   |
| Hewlett-Packard     | 2         | 4.88%   |
| ViewSonic           | 1         | 2.44%   |
| VIE                 | 1         | 2.44%   |
| Orion               | 1         | 2.44%   |
| Iiyama              | 1         | 2.44%   |
| HannStar            | 1         | 2.44%   |
| Goldstar            | 1         | 2.44%   |
| Dell                | 1         | 2.44%   |
| CPT                 | 1         | 2.44%   |
| BOE                 | 1         | 2.44%   |
| AOC                 | 1         | 2.44%   |
| Acer                | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3         | 7.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 4.88%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 4.88%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 2.44%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 2.44%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 2.44%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 2.44%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch    | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch    | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 2.44%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 2.44%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 2.44%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1         | 2.44%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 2.44%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1         | 2.44%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 2.44%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 2.44%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 2.44%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 2.44%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch         | 1         | 2.44%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch          | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch           | 1         | 2.44%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                        | 1         | 2.44%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                      | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 36.59%  |
| 1366x768 (WXGA)    | 12        | 29.27%  |
| 1600x900 (HD+)     | 5         | 12.2%   |
| 1280x800 (WXGA)    | 3         | 7.32%   |
| 1920x1200 (WUXGA)  | 2         | 4.88%   |
| 3840x2160 (4K)     | 1         | 2.44%   |
| 2160x1440          | 1         | 2.44%   |
| 1920x540           | 1         | 2.44%   |
| 1680x1050 (WSXGA+) | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 36.59%  |
| 24      | 6         | 14.63%  |
| 13      | 3         | 7.32%   |
| 23      | 2         | 4.88%   |
| 12      | 2         | 4.88%   |
| 11      | 2         | 4.88%   |
| 46      | 1         | 2.44%   |
| 40      | 1         | 2.44%   |
| 31      | 1         | 2.44%   |
| 22      | 1         | 2.44%   |
| 21      | 1         | 2.44%   |
| 20      | 1         | 2.44%   |
| 19      | 1         | 2.44%   |
| 18      | 1         | 2.44%   |
| 17      | 1         | 2.44%   |
| 14      | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 41.46%  |
| 501-600     | 8         | 19.51%  |
| 201-300     | 5         | 12.2%   |
| 401-500     | 4         | 9.76%   |
| 351-400     | 3         | 7.32%   |
| 801-900     | 1         | 2.44%   |
| 601-700     | 1         | 2.44%   |
| 1001-1500   | 1         | 2.44%   |
| Unknown     | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 76.32%  |
| 16/10 | 7         | 18.42%  |
| 32/9  | 1         | 2.63%   |
| 3/2   | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 36.59%  |
| 201-250        | 7         | 17.07%  |
| 81-90          | 4         | 9.76%   |
| 251-300        | 3         | 7.32%   |
| 61-70          | 2         | 4.88%   |
| 51-60          | 2         | 4.88%   |
| 151-200        | 2         | 4.88%   |
| 501-1000       | 2         | 4.88%   |
| 351-500        | 1         | 2.44%   |
| 141-150        | 1         | 2.44%   |
| 121-130        | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 16        | 39.02%  |
| 101-120 | 14        | 34.15%  |
| 121-160 | 6         | 14.63%  |
| 161-240 | 3         | 7.32%   |
| 1-50    | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 89.58%  |
| 2     | 2         | 4.17%   |
| 0     | 2         | 4.17%   |
| 3     | 1         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 34        | 45.33%  |
| Intel                            | 13        | 17.33%  |
| Qualcomm Atheros                 | 12        | 16%     |
| Silicon Integrated Systems [SiS] | 3         | 4%      |
| Samsung Electronics              | 2         | 2.67%   |
| Broadcom                         | 2         | 2.67%   |
| Xiaomi                           | 1         | 1.33%   |
| Motorola PCS                     | 1         | 1.33%   |
| Marvell Technology Group         | 1         | 1.33%   |
| LG Electronics                   | 1         | 1.33%   |
| JMicron Technology               | 1         | 1.33%   |
| IBM                              | 1         | 1.33%   |
| Guillemot                        | 1         | 1.33%   |
| Broadcom Limited                 | 1         | 1.33%   |
| Accton Technology                | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 14        | 16.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 12.05%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 3.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 3.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 3.61%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.61%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 3.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.41%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 2.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 2.41%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.2%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 1.2%    |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 1         | 1.2%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.2%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.2%    |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.2%    |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 1.2%    |
| Motorola PCS moto g(9) play                                             | 1         | 1.2%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 1.2%    |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 1.2%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.2%    |
| Intel Wireless 7265                                                     | 1         | 1.2%    |
| Intel Wireless 3165                                                     | 1         | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.2%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 1.2%    |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                      | 1         | 1.2%    |
| Intel 82577LC Gigabit Network Connection                                | 1         | 1.2%    |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 1         | 1.2%    |
| IBM Winnipeg PCI-X Host Bridge                                          | 1         | 1.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 12        | 36.36%  |
| Intel                 | 11        | 33.33%  |
| Realtek Semiconductor | 7         | 21.21%  |
| Guillemot             | 1         | 3.03%   |
| Broadcom Limited      | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 9.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 9.09%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 9.09%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 9.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 6.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 6.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 3.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 3.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 3.03%   |
| Realtek 802.11n WLAN Adapter                                                | 1         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 3.03%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 3.03%   |
| Intel Wireless 7265                                                         | 1         | 3.03%   |
| Intel Wireless 3165                                                         | 1         | 3.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 3.03%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS]   | 1         | 3.03%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 30        | 66.67%  |
| Intel                            | 3         | 6.67%   |
| Silicon Integrated Systems [SiS] | 2         | 4.44%   |
| Samsung Electronics              | 2         | 4.44%   |
| Xiaomi                           | 1         | 2.22%   |
| Qualcomm Atheros                 | 1         | 2.22%   |
| Motorola PCS                     | 1         | 2.22%   |
| Marvell Technology Group         | 1         | 2.22%   |
| LG Electronics                   | 1         | 2.22%   |
| JMicron Technology               | 1         | 2.22%   |
| Broadcom                         | 1         | 2.22%   |
| Accton Technology                | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 31.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 22.22%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 6.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 4.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 4.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.22%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 2.22%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.22%   |
| Motorola PCS moto g(9) play                                       | 1         | 2.22%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.22%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.22%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 2.22%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.22%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 2.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.22%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 53.09%  |
| WiFi     | 33        | 40.74%  |
| Modem    | 4         | 4.94%   |
| Unknown  | 1         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 51.11%  |
| Ethernet | 22        | 48.89%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 50%     |
| 1     | 18        | 37.5%   |
| 0     | 4         | 8.33%   |
| 3     | 2         | 4.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 91.67%  |
| Yes  | 4         | 8.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 33.33%  |
| Qualcomm Atheros Communications | 4         | 22.22%  |
| Realtek Semiconductor           | 3         | 16.67%  |
| Toshiba                         | 1         | 5.56%   |
| Hewlett-Packard                 | 1         | 5.56%   |
| Cambridge Silicon Radio         | 1         | 5.56%   |
| ASUSTek Computer                | 1         | 5.56%   |
| Alps Electric                   | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 3         | 16.67%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 16.67%  |
| Intel AX200 Bluetooth                               | 3         | 16.67%  |
| Intel Bluetooth wireless interface                  | 2         | 11.11%  |
| Toshiba Askey for                                   | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 5.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.56%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 5.56%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 55.32%  |
| AMD                              | 13        | 27.66%  |
| Nvidia                           | 4         | 8.51%   |
| Silicon Integrated Systems [SiS] | 3         | 6.38%   |
| ESS Technology                   | 1         | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 7.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 5.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 5.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 5.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 5.26%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 3.51%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 3.51%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 3.51%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 3.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 3.51%   |
| AMD FCH Azalia Controller                                                                         | 2         | 3.51%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.75%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.75%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.75%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.75%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.75%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.75%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.75%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.75%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.75%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 20        | 40.82%  |
| Samsung Electronics | 8         | 16.33%  |
| SK hynix            | 5         | 10.2%   |
| Kingston            | 4         | 8.16%   |
| Unknown (ABCD)      | 2         | 4.08%   |
| A-DATA Technology   | 2         | 4.08%   |
| Transcend           | 1         | 2.04%   |
| Toshiba             | 1         | 2.04%   |
| Teikon              | 1         | 2.04%   |
| Team                | 1         | 2.04%   |
| Micron Technology   | 1         | 2.04%   |
| Elpida              | 1         | 2.04%   |
| Crucial             | 1         | 2.04%   |
| Unknown             | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 7.69%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 3.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.85%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 3.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.85%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.92%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 1.92%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.92%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.92%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.92%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1         | 1.92%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.92%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.92%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 1.92%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.92%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.92%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.92%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.92%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.92%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.92%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 1.92%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s               | 1         | 1.92%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s           | 1         | 1.92%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 1.92%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 1.92%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.92%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 1.92%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s          | 1         | 1.92%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 1.92%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.92%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 1.92%   |
| Micron RAM MT52L256M32D1PF-10 2GB LPDDR3 1867MT/s                | 1         | 1.92%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 1.92%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 15        | 31.91%  |
| DDR4    | 9         | 19.15%  |
| SDRAM   | 8         | 17.02%  |
| DDR2    | 6         | 12.77%  |
| DDR     | 3         | 6.38%   |
| LPDDR4  | 2         | 4.26%   |
| Unknown | 2         | 4.26%   |
| LPDDR3  | 1         | 2.13%   |
| DRAM    | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 32        | 68.09%  |
| DIMM    | 14        | 29.79%  |
| Unknown | 1         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 15        | 30.61%  |
| 4096  | 13        | 26.53%  |
| 1024  | 8         | 16.33%  |
| 8192  | 6         | 12.24%  |
| 512   | 3         | 6.12%   |
| 16384 | 2         | 4.08%   |
| 32768 | 1         | 2.04%   |
| 256   | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 11        | 22.45%  |
| 1600    | 6         | 12.24%  |
| 1333    | 5         | 10.2%   |
| 2667    | 4         | 8.16%   |
| 2400    | 4         | 8.16%   |
| 1334    | 3         | 6.12%   |
| 1067    | 2         | 4.08%   |
| 1066    | 2         | 4.08%   |
| 800     | 2         | 4.08%   |
| 266     | 2         | 4.08%   |
| 4199    | 1         | 2.04%   |
| 3600    | 1         | 2.04%   |
| 3266    | 1         | 2.04%   |
| 3200    | 1         | 2.04%   |
| 2666    | 1         | 2.04%   |
| 2048    | 1         | 2.04%   |
| 1867    | 1         | 2.04%   |
| 400     | 1         | 2.04%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 4         | 21.05%  |
| IMC Networks                           | 3         | 15.79%  |
| Microdia                               | 2         | 10.53%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 10.53%  |
| Acer                                   | 2         | 10.53%  |
| Suyin                                  | 1         | 5.26%   |
| Silicon Motion                         | 1         | 5.26%   |
| Ricoh                                  | 1         | 5.26%   |
| Realtek Semiconductor                  | 1         | 5.26%   |
| ALi                                    | 1         | 5.26%   |
| Alcor Micro                            | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 5.26%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 5.26%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 5.26%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 5.26%   |
| Microdia Webcam Vitade AF                                   | 1         | 5.26%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 5.26%   |
| IMC Networks Integrated Camera                              | 1         | 5.26%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 5.26%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 5.26%   |
| Chicony Integrated Camera                                   | 1         | 5.26%   |
| Chicony HP Webcam                                           | 1         | 5.26%   |
| Chicony HP HD Webcam                                        | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 5.26%   |
| ALi M5603 Video Camera Controller                           | 1         | 5.26%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 5.26%   |
| Acer HP Webcam-101                                          | 1         | 5.26%   |
| Acer EasyCamera                                             | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 66.67%  |
| Synaptics        | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 38        | 79.17%  |
| 1     | 6         | 12.5%   |
| 2     | 4         | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 7         | 50%     |
| Fingerprint reader       | 3         | 21.43%  |
| Network                  | 1         | 7.14%   |
| Flash memory             | 1         | 7.14%   |
| Communication controller | 1         | 7.14%   |
| Camera                   | 1         | 7.14%   |

