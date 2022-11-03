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

Total: 49

| Vendor        | Model                    | Form-Factor | Probe                                                      | Date         |
|---------------|--------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Q4OS 4 | 22        | 52.38%  |
| Q4OS 3 | 15        | 35.71%  |
| Q4OS 2 | 5         | 11.9%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 42        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 4.19.0-17-amd64        | 4         | 9.52%   |
| 5.10.0-12-amd64        | 3         | 7.14%   |
| 5.10.0-8-amd64         | 2         | 4.76%   |
| 5.10.0-14-686-pae      | 2         | 4.76%   |
| 5.10.0-10-686-pae      | 2         | 4.76%   |
| 6.0.0-1-amd64          | 1         | 2.38%   |
| 5.9.0-5-amd64          | 1         | 2.38%   |
| 5.6.0-1-amd64          | 1         | 2.38%   |
| 5.18.0-0.bpo.1-amd64   | 1         | 2.38%   |
| 5.10.0-9-amd64         | 1         | 2.38%   |
| 5.10.0-9-686-pae       | 1         | 2.38%   |
| 5.10.0-8-686-pae       | 1         | 2.38%   |
| 5.10.0-17-amd64        | 1         | 2.38%   |
| 5.10.0-15-686-pae      | 1         | 2.38%   |
| 5.10.0-14-amd64        | 1         | 2.38%   |
| 5.10.0-13-amd64        | 1         | 2.38%   |
| 5.10.0-12-686-pae      | 1         | 2.38%   |
| 5.10.0-11-686-pae      | 1         | 2.38%   |
| 4.9.0-9-686-pae        | 1         | 2.38%   |
| 4.9.0-8-amd64          | 1         | 2.38%   |
| 4.9.0-14-686-pae       | 1         | 2.38%   |
| 4.9.0-12-686-pae       | 1         | 2.38%   |
| 4.19.0-6-amd64         | 1         | 2.38%   |
| 4.19.0-21-amd64        | 1         | 2.38%   |
| 4.19.0-20-amd64        | 1         | 2.38%   |
| 4.19.0-17-686-pae      | 1         | 2.38%   |
| 4.19.0-17-686          | 1         | 2.38%   |
| 4.19.0-16-amd64        | 1         | 2.38%   |
| 4.19.0-16-686          | 1         | 2.38%   |
| 4.19.0-14-amd64        | 1         | 2.38%   |
| 4.19.0-13-amd64        | 1         | 2.38%   |
| 4.19.0-12-amd64        | 1         | 2.38%   |
| 4.19.0-10-amd64        | 1         | 2.38%   |
| 4.19.0-0.bpo.5-686-pae | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 18        | 42.86%  |
| 4.19.0  | 16        | 38.1%   |
| 4.9.0   | 4         | 9.52%   |
| 6.0.0   | 1         | 2.38%   |
| 5.9.0   | 1         | 2.38%   |
| 5.6.0   | 1         | 2.38%   |
| 5.18.0  | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 42.86%  |
| 4.19    | 16        | 38.1%   |
| 4.9     | 4         | 9.52%   |
| 6.0     | 1         | 2.38%   |
| 5.9     | 1         | 2.38%   |
| 5.6     | 1         | 2.38%   |
| 5.18    | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 61.9%   |
| i686   | 16        | 38.1%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Trinity | 22        | 52.38%  |
| KDE5    | 18        | 42.86%  |
| LXDE    | 1         | 2.38%   |
| KDE     | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 41        | 97.62%  |
| Tty  | 1         | 2.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 22        | 52.38%  |
| SDDM    | 19        | 45.24%  |
| LightDM | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 15        | 35.71%  |
| es_ES   | 3         | 7.14%   |
| en_GB   | 3         | 7.14%   |
| de_DE   | 3         | 7.14%   |
| Unknown | 3         | 7.14%   |
| fr_FR   | 2         | 4.76%   |
| sv_SE   | 1         | 2.38%   |
| sl_SI   | 1         | 2.38%   |
| ru_RU   | 1         | 2.38%   |
| pt_BR   | 1         | 2.38%   |
| pl_PL   | 1         | 2.38%   |
| it_IT   | 1         | 2.38%   |
| es_VE   | 1         | 2.38%   |
| es_AR   | 1         | 2.38%   |
| en_ZA   | 1         | 2.38%   |
| en_SG   | 1         | 2.38%   |
| en_IE   | 1         | 2.38%   |
| C       | 1         | 2.38%   |
| bg_BG   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 25        | 59.52%  |
| EFI  | 17        | 40.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 39        | 92.86%  |
| Overlay | 3         | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 23        | 54.76%  |
| GPT     | 18        | 42.86%  |
| Unknown | 1         | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 85.71%  |
| Yes       | 6         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 64.29%  |
| Yes       | 15        | 35.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 7         | 16.67%  |
| Toshiba                     | 4         | 9.52%   |
| ASUSTek Computer            | 4         | 9.52%   |
| MSI                         | 3         | 7.14%   |
| Lenovo                      | 3         | 7.14%   |
| TrekStor                    | 2         | 4.76%   |
| Medion                      | 2         | 4.76%   |
| Gigabyte Technology         | 2         | 4.76%   |
| ASRock                      | 2         | 4.76%   |
| Visual Land                 | 1         | 2.38%   |
| TECO Electric and Machinery | 1         | 2.38%   |
| Sony                        | 1         | 2.38%   |
| Qilive                      | 1         | 2.38%   |
| Phoenix/SiS                 | 1         | 2.38%   |
| Philco                      | 1         | 2.38%   |
| Packard Bell                | 1         | 2.38%   |
| JVC                         | 1         | 2.38%   |
| Foxconn                     | 1         | 2.38%   |
| Compaq                      | 1         | 2.38%   |
| Chuwi                       | 1         | 2.38%   |
| AMI                         | 1         | 2.38%   |
| Acer                        | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 4.76%   |
| Toshiba Satellite C660                 | 2         | 4.76%   |
| Visual Land Premier 10                 | 1         | 2.38%   |
| Toshiba Satellite Pro L500             | 1         | 2.38%   |
| Toshiba Satellite M70                  | 1         | 2.38%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 2.38%   |
| Sony VGN-P11Z_Q                        | 1         | 2.38%   |
| Qilive QW19141AMSP                     | 1         | 2.38%   |
| Phoenix/SiS M720SR                     | 1         | 2.38%   |
| Philco 14I                             | 1         | 2.38%   |
| Packard Bell EasyNote LM81             | 1         | 2.38%   |
| MSI U210                               | 1         | 2.38%   |
| MSI MS-7C56                            | 1         | 2.38%   |
| MSI MS-7597                            | 1         | 2.38%   |
| Medion P6620                           | 1         | 2.38%   |
| Lenovo ThinkPad T495 20NKS0PG00        | 1         | 2.38%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 2.38%   |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 2.38%   |
| JVC J3N                                | 1         | 2.38%   |
| HP ProBook 6550b                       | 1         | 2.38%   |
| HP ProBook 450 G2                      | 1         | 2.38%   |
| HP Presario CQ56                       | 1         | 2.38%   |
| HP OmniBook PC                         | 1         | 2.38%   |
| HP Laptop 15s-fq2xxx                   | 1         | 2.38%   |
| HP 250 G5 Notebook PC                  | 1         | 2.38%   |
| HP 2000                                | 1         | 2.38%   |
| Gigabyte XP-M5S661GX                   | 1         | 2.38%   |
| Gigabyte AB350-Gaming                  | 1         | 2.38%   |
| Foxconn Pro 3400 Series MT             | 1         | 2.38%   |
| Compaq Evo D510 SFF                    | 1         | 2.38%   |
| Chuwi GemiBook Pro                     | 1         | 2.38%   |
| ASUS X540YA                            | 1         | 2.38%   |
| ASUS T12Eg                             | 1         | 2.38%   |
| ASUS A6U                               | 1         | 2.38%   |
| ASUS A6JC                              | 1         | 2.38%   |
| ASRock H61M-HVS                        | 1         | 2.38%   |
| ASRock G41M-VS3                        | 1         | 2.38%   |
| AMI Intel                              | 1         | 2.38%   |
| Acer AO751h                            | 1         | 2.38%   |
| Unknown                                | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 9.52%   |
| TrekStor SurfTab                  | 2         | 4.76%   |
| Lenovo ThinkPad                   | 2         | 4.76%   |
| HP ProBook                        | 2         | 4.76%   |
| Visual Land Premier               | 1         | 2.38%   |
| TECO Electric and Machinery FUTRO | 1         | 2.38%   |
| Sony VGN-P11Z                     | 1         | 2.38%   |
| Qilive QW19141AMSP                | 1         | 2.38%   |
| Phoenix/SiS M720SR                | 1         | 2.38%   |
| Philco 14I                        | 1         | 2.38%   |
| Packard Bell EasyNote             | 1         | 2.38%   |
| MSI U210                          | 1         | 2.38%   |
| MSI MS-7C56                       | 1         | 2.38%   |
| MSI MS-7597                       | 1         | 2.38%   |
| Medion P6620                      | 1         | 2.38%   |
| Lenovo IdeaPad                    | 1         | 2.38%   |
| JVC J3N                           | 1         | 2.38%   |
| HP Presario                       | 1         | 2.38%   |
| HP OmniBook                       | 1         | 2.38%   |
| HP Laptop                         | 1         | 2.38%   |
| HP 250                            | 1         | 2.38%   |
| HP 2000                           | 1         | 2.38%   |
| Gigabyte XP-M5S661GX              | 1         | 2.38%   |
| Gigabyte AB350-Gaming             | 1         | 2.38%   |
| Foxconn Pro                       | 1         | 2.38%   |
| Compaq Evo                        | 1         | 2.38%   |
| Chuwi GemiBook                    | 1         | 2.38%   |
| ASUS X540YA                       | 1         | 2.38%   |
| ASUS T12Eg                        | 1         | 2.38%   |
| ASUS A6U                          | 1         | 2.38%   |
| ASUS A6JC                         | 1         | 2.38%   |
| ASRock H61M-HVS                   | 1         | 2.38%   |
| ASRock G41M-VS3                   | 1         | 2.38%   |
| AMI Intel                         | 1         | 2.38%   |
| Acer AO751h                       | 1         | 2.38%   |
| Unknown                           | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 14.29%  |
| 2020    | 4         | 9.52%   |
| 2011    | 4         | 9.52%   |
| 2009    | 4         | 9.52%   |
| 2015    | 3         | 7.14%   |
| 2005    | 3         | 7.14%   |
| 2019    | 2         | 4.76%   |
| 2017    | 2         | 4.76%   |
| 2016    | 2         | 4.76%   |
| 2014    | 2         | 4.76%   |
| 2008    | 2         | 4.76%   |
| Unknown | 2         | 4.76%   |
| 2018    | 1         | 2.38%   |
| 2012    | 1         | 2.38%   |
| 2007    | 1         | 2.38%   |
| 2006    | 1         | 2.38%   |
| 2004    | 1         | 2.38%   |
| 2002    | 1         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 31        | 73.81%  |
| Desktop  | 9         | 21.43%  |
| Tablet   | 2         | 4.76%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 40        | 95.24%  |
| Enabled  | 2         | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 11        | 26.19%  |
| 2.01-3.0    | 7         | 16.67%  |
| 4.01-8.0    | 6         | 14.29%  |
| 1.01-2.0    | 6         | 14.29%  |
| 0.51-1.0    | 6         | 14.29%  |
| 16.01-24.0  | 2         | 4.76%   |
| 0.01-0.5    | 2         | 4.76%   |
| 24.01-32.0  | 1         | 2.38%   |
| 64.01-256.0 | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 15        | 35.71%  |
| 0.51-1.0  | 11        | 26.19%  |
| 0.01-0.5  | 7         | 16.67%  |
| 2.01-3.0  | 5         | 11.9%   |
| 3.01-4.0  | 3         | 7.14%   |
| 8.01-16.0 | 1         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 71.43%  |
| 2      | 8         | 19.05%  |
| 3      | 4         | 9.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 50%     |
| No        | 21        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 90.48%  |
| No        | 4         | 9.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 71.43%  |
| No        | 12        | 28.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 61.9%   |
| Yes       | 16        | 38.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 5         | 11.9%   |
| UK           | 3         | 7.14%   |
| Spain        | 3         | 7.14%   |
| Kenya        | 3         | 7.14%   |
| Germany      | 3         | 7.14%   |
| Switzerland  | 2         | 4.76%   |
| Romania      | 2         | 4.76%   |
| Poland       | 2         | 4.76%   |
| Italy        | 2         | 4.76%   |
| France       | 2         | 4.76%   |
| Brazil       | 2         | 4.76%   |
| Venezuela    | 1         | 2.38%   |
| Sweden       | 1         | 2.38%   |
| South Africa | 1         | 2.38%   |
| Slovenia     | 1         | 2.38%   |
| Singapore    | 1         | 2.38%   |
| Saudi Arabia | 1         | 2.38%   |
| Russia       | 1         | 2.38%   |
| Qatar        | 1         | 2.38%   |
| Netherlands  | 1         | 2.38%   |
| Bulgaria     | 1         | 2.38%   |
| Belgium      | 1         | 2.38%   |
| Belarus      | 1         | 2.38%   |
| Argentina    | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 7.14%   |
| Zurich                | 2         | 4.76%   |
| Swindon               | 2         | 4.76%   |
| Rostock               | 2         | 4.76%   |
| Mesa                  | 2         | 4.76%   |
| Drobeta-Turnu Severin | 2         | 4.76%   |
| Tranas                | 1         | 2.38%   |
| The Hague             | 1         | 2.38%   |
| Tellico Plains        | 1         | 2.38%   |
| Sosnowiec             | 1         | 2.38%   |
| Sofia                 | 1         | 2.38%   |
| Singapore             | 1         | 2.38%   |
| Schermbeck            | 1         | 2.38%   |
| Salsomaggiore Terme   | 1         | 2.38%   |
| Puerto Cumarebo       | 1         | 2.38%   |
| Posadas               | 1         | 2.38%   |
| Moscow                | 1         | 2.38%   |
| Moirans               | 1         | 2.38%   |
| Mogilev               | 1         | 2.38%   |
| Londrina              | 1         | 2.38%   |
| Ljubljana             | 1         | 2.38%   |
| Las Vegas             | 1         | 2.38%   |
| Klaudyn               | 1         | 2.38%   |
| Johannesburg          | 1         | 2.38%   |
| Guarulhos             | 1         | 2.38%   |
| Grand Junction        | 1         | 2.38%   |
| Gijón                | 1         | 2.38%   |
| Fulham                | 1         | 2.38%   |
| Doha                  | 1         | 2.38%   |
| Dammam                | 1         | 2.38%   |
| Calvecchia            | 1         | 2.38%   |
| Brussels              | 1         | 2.38%   |
| Boulogne-sur-Mer      | 1         | 2.38%   |
| Barcelona             | 1         | 2.38%   |
| Alicante              | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 16%     |
| Seagate             | 7         | 8      | 14%     |
| Unknown             | 6         | 6      | 12%     |
| Samsung Electronics | 4         | 4      | 8%      |
| SanDisk             | 3         | 3      | 6%      |
| Hitachi             | 3         | 3      | 6%      |
| China               | 3         | 4      | 6%      |
| Toshiba             | 2         | 2      | 4%      |
| Kingston            | 2         | 2      | 4%      |
| KESU                | 2         | 2      | 4%      |
| HGST                | 2         | 2      | 4%      |
| A-DATA Technology   | 2         | 2      | 4%      |
| Unknown (CF)        | 1         | 1      | 2%      |
| Silicon Motion      | 1         | 1      | 2%      |
| Phison              | 1         | 1      | 2%      |
| Maxtor              | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| Unknown             | 1         | 1      | 2%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 3.85%   |
| Samsung SSD 850 EVO 250GB            | 2         | 3.85%   |
| KESU USB 3.1 256GB                   | 2         | 3.85%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.92%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.92%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 1.92%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.92%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.92%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.92%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 1.92%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.92%   |
| Unknown USDU1  32GB                  | 1         | 1.92%   |
| Unknown SLD64G  64GB                 | 1         | 1.92%   |
| Unknown SD/MMC/MS PRO 1TB            | 1         | 1.92%   |
| Unknown 064G38  64GB                 | 1         | 1.92%   |
| Unknown (CF) Card 16GB SSD           | 1         | 1.92%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.92%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.92%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.92%   |
| Seagate ST9120822AS 120GB            | 1         | 1.92%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1.92%   |
| Seagate ST3500413AS 500GB            | 1         | 1.92%   |
| Seagate ST3160815AS 160GB            | 1         | 1.92%   |
| Seagate ST3160812AS 160GB            | 1         | 1.92%   |
| Seagate ST310211A 10GB               | 1         | 1.92%   |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 1.92%   |
| Seagate Backup+ SL 1TB               | 1         | 1.92%   |
| SanDisk SDSSDA120G 120GB             | 1         | 1.92%   |
| SanDisk SDCFX-032G SSD               | 1         | 1.92%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 1.92%   |
| Samsung HD081GJ 80GB                 | 1         | 1.92%   |
| Samsung AWMB3R  16GB                 | 1         | 1.92%   |
| Phison APS-SE20G-1T                  | 1         | 1.92%   |
| Maxtor 6Y080L0 81GB                  | 1         | 1.92%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1.92%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 1.92%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 1.92%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1.92%   |
| Hitachi DK23CA-20 20GB               | 1         | 1.92%   |
| HGST HTS725050A7E630 500GB           | 1         | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 26.09%  |
| Seagate             | 6         | 7      | 26.09%  |
| Hitachi             | 3         | 3      | 13.04%  |
| Toshiba             | 2         | 2      | 8.7%    |
| HGST                | 2         | 2      | 8.7%    |
| Unknown             | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| Maxtor              | 1         | 1      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |

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
| HDD     | 20        | 24     | 44.44%  |
| SSD     | 13        | 15     | 28.89%  |
| MMC     | 6         | 6      | 13.33%  |
| NVMe    | 3         | 4      | 6.67%   |
| Unknown | 3         | 3      | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 38     | 70.45%  |
| MMC  | 6         | 6      | 13.64%  |
| SAS  | 4         | 4      | 9.09%   |
| NVMe | 3         | 4      | 6.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 34     | 85.29%  |
| 0.51-1.0   | 4         | 4      | 11.76%  |
| 4.01-10.0  | 1         | 1      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 9         | 21.43%  |
| 51-100         | 9         | 21.43%  |
| 251-500        | 6         | 14.29%  |
| 101-250        | 6         | 14.29%  |
| 21-50          | 5         | 11.9%   |
| 1001-2000      | 3         | 7.14%   |
| 501-1000       | 2         | 4.76%   |
| More than 3000 | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 29        | 69.05%  |
| 21-50          | 6         | 14.29%  |
| 251-500        | 2         | 4.76%   |
| 501-1000       | 2         | 4.76%   |
| More than 3000 | 1         | 2.38%   |
| 51-100         | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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
| Works    | 24        | 31     | 54.55%  |
| Detected | 10        | 11     | 22.73%  |
| Malfunc  | 10        | 10     | 22.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 24        | 58.54%  |
| AMD                              | 8         | 19.51%  |
| Silicon Integrated Systems [SiS] | 4         | 9.76%   |
| Silicon Motion                   | 1         | 2.44%   |
| SanDisk                          | 1         | 2.44%   |
| Phison Electronics               | 1         | 2.44%   |
| Nvidia                           | 1         | 2.44%   |
| ADATA Technology                 | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 10%     |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 4         | 8%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 6%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 6%      |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 4%      |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 4%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2%      |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 2%      |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 2%      |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2%      |
| Phison E12 NVMe Controller                                                       | 1         | 2%      |
| Nvidia MCP61 SATA Controller                                                     | 1         | 2%      |
| Nvidia MCP61 IDE                                                                 | 1         | 2%      |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2%      |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 2%      |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 2%      |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 2%      |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 2%      |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 2%      |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 2%      |
| AMD 500 Series Chipset SATA Controller                                           | 1         | 2%      |
| AMD 300 Series Chipset SATA Controller                                           | 1         | 2%      |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 22        | 52.38%  |
| IDE  | 15        | 35.71%  |
| NVMe | 3         | 7.14%   |
| RAID | 2         | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 30        | 71.43%  |
| AMD    | 12        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz                 | 3         | 7.14%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 4.76%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 4.76%   |
| Intel Pentium M processor 1000MHz               | 1         | 2.38%   |
| Intel Pentium M processor 1.70GHz               | 1         | 2.38%   |
| Intel Pentium III (Coppermine)                  | 1         | 2.38%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2.38%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 2.38%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1         | 2.38%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1         | 2.38%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 2.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.38%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1         | 2.38%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2.38%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.38%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2.38%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2.38%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.38%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.38%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.38%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2.38%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.38%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2.38%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.38%   |
| AMD V120 Processor                              | 1         | 2.38%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.38%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1         | 2.38%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 2.38%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.38%   |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2.38%   |
| AMD Athlon Processor                            | 1         | 2.38%   |
| AMD Athlon Neo Processor MV-40                  | 1         | 2.38%   |
| AMD Athlon II X2 250 Processor                  | 1         | 2.38%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 1         | 2.38%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.38%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G   | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 6         | 14.29%  |
| Intel Celeron           | 5         | 11.9%   |
| Intel Core 2 Duo        | 4         | 9.52%   |
| Intel Core i5           | 3         | 7.14%   |
| Intel Pentium M         | 2         | 4.76%   |
| Intel Pentium Dual-Core | 2         | 4.76%   |
| Intel Pentium 4         | 2         | 4.76%   |
| Intel Core i3           | 2         | 4.76%   |
| AMD Athlon              | 2         | 4.76%   |
| Other                   | 1         | 2.38%   |
| Intel Pentium III       | 1         | 2.38%   |
| Intel Core i7           | 1         | 2.38%   |
| Intel Core 2            | 1         | 2.38%   |
| AMD V120                | 1         | 2.38%   |
| AMD Ryzen 7 PRO         | 1         | 2.38%   |
| AMD Ryzen 7             | 1         | 2.38%   |
| AMD Mobile Sempron      | 1         | 2.38%   |
| AMD E                   | 1         | 2.38%   |
| AMD C-70                | 1         | 2.38%   |
| AMD Athlon Neo          | 1         | 2.38%   |
| AMD Athlon II X2        | 1         | 2.38%   |
| AMD A8                  | 1         | 2.38%   |
| AMD A4                  | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 42.86%  |
| 4      | 12        | 28.57%  |
| 1      | 11        | 26.19%  |
| 8      | 1         | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 71.43%  |
| 2      | 12        | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 80.95%  |
| 32-bit         | 8         | 19.05%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 11.9%   |
| 0x30678    | 4         | 9.52%   |
| 0x206a7    | 4         | 9.52%   |
| 0x1067a    | 4         | 9.52%   |
| 0x706a1    | 2         | 4.76%   |
| 0x6fd      | 2         | 4.76%   |
| 0x010000c8 | 2         | 4.76%   |
| 0xf49      | 1         | 2.38%   |
| 0xf27      | 1         | 2.38%   |
| 0x806c1    | 1         | 2.38%   |
| 0x706a8    | 1         | 2.38%   |
| 0x6f6      | 1         | 2.38%   |
| 0x6d8      | 1         | 2.38%   |
| 0x695      | 1         | 2.38%   |
| 0x68a      | 1         | 2.38%   |
| 0x406c4    | 1         | 2.38%   |
| 0x40651    | 1         | 2.38%   |
| 0x20655    | 1         | 2.38%   |
| 0x106c2    | 1         | 2.38%   |
| 0x08108102 | 1         | 2.38%   |
| 0x0810100b | 1         | 2.38%   |
| 0x0800820d | 1         | 2.38%   |
| 0x07030106 | 1         | 2.38%   |
| 0x06006705 | 1         | 2.38%   |
| 0x05000119 | 1         | 2.38%   |
| 0x0500010d | 1         | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 6         | 14.29%  |
| SandyBridge   | 4         | 9.52%   |
| Penryn        | 4         | 9.52%   |
| P6            | 3         | 7.14%   |
| Goldmont plus | 3         | 7.14%   |
| Core          | 3         | 7.14%   |
| Zen+          | 2         | 4.76%   |
| NetBurst      | 2         | 4.76%   |
| K8 Hammer     | 2         | 4.76%   |
| K10           | 2         | 4.76%   |
| Bonnell       | 2         | 4.76%   |
| Bobcat        | 2         | 4.76%   |
| Zen           | 1         | 2.38%   |
| Westmere      | 1         | 2.38%   |
| TigerLake     | 1         | 2.38%   |
| Puma          | 1         | 2.38%   |
| K6            | 1         | 2.38%   |
| Haswell       | 1         | 2.38%   |
| Excavator     | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 51.16%  |
| AMD                              | 11        | 25.58%  |
| Nvidia                           | 5         | 11.63%  |
| Silicon Integrated Systems [SiS] | 4         | 9.3%    |
| S3 Graphics                      | 1         | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 9.09%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 6.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 6.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 6.82%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 4.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 2         | 4.55%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 2.27%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 2.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 2.27%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 2.27%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 2.27%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 2.27%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 2.27%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 2.27%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 2.27%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 2.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 1         | 2.27%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 2.27%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 2.27%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 2.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 2.27%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 1         | 2.27%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 2.27%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 2.27%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 2.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 1         | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 2.27%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 20        | 47.62%  |
| 1 x AMD         | 10        | 23.81%  |
| 1 x Nvidia      | 5         | 11.9%   |
| 1 x SiS         | 4         | 9.52%   |
| Other           | 1         | 2.38%   |
| 1 x S3 Graphics | 1         | 2.38%   |
| Intel + AMD     | 1         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 34        | 80.95%  |
| Unknown     | 5         | 11.9%   |
| Proprietary | 3         | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 59.52%  |
| 0.01-0.5   | 11        | 26.19%  |
| 1.01-2.0   | 4         | 9.52%   |
| 3.01-4.0   | 1         | 2.38%   |
| 0.51-1.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 22.22%  |
| Chimei Innolux      | 7         | 19.44%  |
| AU Optronics        | 6         | 16.67%  |
| LG Display          | 3         | 8.33%   |
| Hewlett-Packard     | 2         | 5.56%   |
| ViewSonic           | 1         | 2.78%   |
| VIE                 | 1         | 2.78%   |
| Orion               | 1         | 2.78%   |
| HannStar            | 1         | 2.78%   |
| Goldstar            | 1         | 2.78%   |
| Dell                | 1         | 2.78%   |
| CPT                 | 1         | 2.78%   |
| BOE                 | 1         | 2.78%   |
| AOC                 | 1         | 2.78%   |
| Acer                | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 5.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 5.56%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 2.78%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 2.78%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 2.78%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 2.78%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch    | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 2.78%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 2.78%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 2.78%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 2.78%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch               | 1         | 2.78%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 2.78%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 2.78%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 2.78%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 2.78%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch         | 1         | 2.78%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch           | 1         | 2.78%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                        | 1         | 2.78%   |
| Acer K222HQL ACR03E1 1920x1080 480x270mm 21.7-inch                      | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 12        | 33.33%  |
| 1920x1080 (FHD)    | 11        | 30.56%  |
| 1600x900 (HD+)     | 5         | 13.89%  |
| 1280x800 (WXGA)    | 3         | 8.33%   |
| 3840x2160 (4K)     | 1         | 2.78%   |
| 2160x1440          | 1         | 2.78%   |
| 1920x540           | 1         | 2.78%   |
| 1920x1200 (WUXGA)  | 1         | 2.78%   |
| 1680x1050 (WSXGA+) | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 41.67%  |
| 13      | 3         | 8.33%   |
| 24      | 2         | 5.56%   |
| 23      | 2         | 5.56%   |
| 11      | 2         | 5.56%   |
| 46      | 1         | 2.78%   |
| 40      | 1         | 2.78%   |
| 31      | 1         | 2.78%   |
| 22      | 1         | 2.78%   |
| 21      | 1         | 2.78%   |
| 20      | 1         | 2.78%   |
| 19      | 1         | 2.78%   |
| 18      | 1         | 2.78%   |
| 17      | 1         | 2.78%   |
| 14      | 1         | 2.78%   |
| 12      | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 47.22%  |
| 501-600     | 4         | 11.11%  |
| 401-500     | 4         | 11.11%  |
| 201-300     | 4         | 11.11%  |
| 351-400     | 3         | 8.33%   |
| 801-900     | 1         | 2.78%   |
| 601-700     | 1         | 2.78%   |
| 1001-1500   | 1         | 2.78%   |
| Unknown     | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 75.76%  |
| 16/10 | 6         | 18.18%  |
| 32/9  | 1         | 3.03%   |
| 3/2   | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 41.67%  |
| 81-90          | 4         | 11.11%  |
| 201-250        | 4         | 11.11%  |
| 51-60          | 2         | 5.56%   |
| 251-300        | 2         | 5.56%   |
| 151-200        | 2         | 5.56%   |
| 501-1000       | 2         | 5.56%   |
| 61-70          | 1         | 2.78%   |
| 351-500        | 1         | 2.78%   |
| 141-150        | 1         | 2.78%   |
| 121-130        | 1         | 2.78%   |
| Unknown        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 14        | 38.89%  |
| 51-100  | 12        | 33.33%  |
| 121-160 | 6         | 16.67%  |
| 161-240 | 2         | 5.56%   |
| 1-50    | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 88.1%   |
| 2     | 2         | 4.76%   |
| 0     | 2         | 4.76%   |
| 3     | 1         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 30        | 44.12%  |
| Qualcomm Atheros                 | 12        | 17.65%  |
| Intel                            | 10        | 14.71%  |
| Silicon Integrated Systems [SiS] | 3         | 4.41%   |
| Samsung Electronics              | 2         | 2.94%   |
| Broadcom                         | 2         | 2.94%   |
| Xiaomi                           | 1         | 1.47%   |
| Motorola PCS                     | 1         | 1.47%   |
| Marvell Technology Group         | 1         | 1.47%   |
| LG Electronics                   | 1         | 1.47%   |
| JMicron Technology               | 1         | 1.47%   |
| IBM                              | 1         | 1.47%   |
| Guillemot                        | 1         | 1.47%   |
| Broadcom Limited                 | 1         | 1.47%   |
| Accton Technology                | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 11        | 14.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 9         | 12.16%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                     | 3         | 4.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 3         | 4.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 3         | 4.05%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 2         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 2.7%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                | 2         | 2.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 2         | 2.7%    |
| Intel Wi-Fi 6 AX200                                                       | 2         | 2.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 2         | 2.7%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                  | 2         | 2.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 1.35%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                 | 1         | 1.35%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                   | 1         | 1.35%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter             | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1         | 1.35%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                | 1         | 1.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1         | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 1         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 1         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 1         | 1.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1         | 1.35%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1         | 1.35%   |
| Motorola PCS moto g(6) plus                                               | 1         | 1.35%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                   | 1         | 1.35%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                       | 1         | 1.35%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                    | 1         | 1.35%   |
| Intel Wireless 3165                                                       | 1         | 1.35%   |
| Intel Gemini Lake PCH CNVi WiFi                                           | 1         | 1.35%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller          | 1         | 1.35%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller         | 1         | 1.35%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                        | 1         | 1.35%   |
| Intel 82577LC Gigabit Network Connection                                  | 1         | 1.35%   |
| IBM Winnipeg PCI-X Host Bridge                                            | 1         | 1.35%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1         | 1.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 1         | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 12        | 40%     |
| Intel                 | 8         | 26.67%  |
| Realtek Semiconductor | 7         | 23.33%  |
| Guillemot             | 1         | 3.33%   |
| Broadcom Limited      | 1         | 3.33%   |
| Broadcom              | 1         | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 10%     |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 10%     |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 6.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 6.67%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 6.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 6.67%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 2         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 3.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 3.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 3.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 3.33%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 3.33%   |
| Intel Wireless 3165                                                         | 1         | 3.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 3.33%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS]   | 1         | 3.33%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 26        | 65%     |
| Silicon Integrated Systems [SiS] | 2         | 5%      |
| Samsung Electronics              | 2         | 5%      |
| Intel                            | 2         | 5%      |
| Xiaomi                           | 1         | 2.5%    |
| Qualcomm Atheros                 | 1         | 2.5%    |
| Motorola PCS                     | 1         | 2.5%    |
| Marvell Technology Group         | 1         | 2.5%    |
| LG Electronics                   | 1         | 2.5%    |
| JMicron Technology               | 1         | 2.5%    |
| Broadcom                         | 1         | 2.5%    |
| Accton Technology                | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 27.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 22.5%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 7.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 5%      |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 5%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.5%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 2.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.5%    |
| Motorola PCS moto g(6) plus                                       | 1         | 2.5%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.5%    |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.5%    |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 2.5%    |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.5%    |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 52.78%  |
| WiFi     | 30        | 41.67%  |
| Modem    | 3         | 4.17%   |
| Unknown  | 1         | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 52.5%   |
| Ethernet | 19        | 47.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 54.76%  |
| 1     | 14        | 33.33%  |
| 0     | 4         | 9.52%   |
| 3     | 1         | 2.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 92.86%  |
| Yes  | 3         | 7.14%   |

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
| Intel                            | 23        | 56.1%   |
| AMD                              | 11        | 26.83%  |
| Silicon Integrated Systems [SiS] | 3         | 7.32%   |
| Nvidia                           | 3         | 7.32%   |
| ESS Technology                   | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 8%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 6%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 6%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 6%      |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 4%      |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 4%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4%      |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 4%      |
| AMD Wrestler HDMI Audio                                                                           | 2         | 4%      |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 4%      |
| AMD FCH Azalia Controller                                                                         | 2         | 4%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 4%      |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 2%      |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 2%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2%      |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2%      |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 2%      |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2%      |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 2%      |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2%      |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 2%      |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2%      |
| AMD High Definition Audio Controller                                                              | 1         | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 2%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 18        | 42.86%  |
| Samsung Electronics | 8         | 19.05%  |
| SK hynix            | 5         | 11.9%   |
| Unknown (ABCD)      | 2         | 4.76%   |
| Kingston            | 2         | 4.76%   |
| A-DATA Technology   | 2         | 4.76%   |
| Transcend           | 1         | 2.38%   |
| Toshiba             | 1         | 2.38%   |
| Teikon              | 1         | 2.38%   |
| Team                | 1         | 2.38%   |
| Elpida              | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 8.89%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 4.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 4.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 4.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 4.44%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 2.22%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 2.22%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 2.22%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 2.22%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 2.22%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 2.22%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 2.22%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 2.22%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 2.22%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 2.22%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 2.22%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 2.22%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 2.22%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 2.22%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 2.22%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 2.22%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 2.22%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s          | 1         | 2.22%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 2.22%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2.22%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.22%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 975MT/s         | 1         | 2.22%   |
| Kingston RAM HP32D4S2S1ME-4 4096MB SODIMM DDR4 3200MT/s          | 1         | 2.22%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 2.22%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s            | 1         | 2.22%   |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s                         | 1         | 2.22%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s             | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 14        | 35%     |
| SDRAM   | 7         | 17.5%   |
| DDR4    | 6         | 15%     |
| DDR2    | 6         | 15%     |
| LPDDR4  | 2         | 5%      |
| DDR     | 2         | 5%      |
| Unknown | 2         | 5%      |
| DRAM    | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 28        | 70%     |
| DIMM   | 12        | 30%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 15        | 35.71%  |
| 2048  | 13        | 30.95%  |
| 1024  | 7         | 16.67%  |
| 512   | 3         | 7.14%   |
| 32768 | 1         | 2.38%   |
| 16384 | 1         | 2.38%   |
| 8192  | 1         | 2.38%   |
| 256   | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 23.81%  |
| 1600    | 5         | 11.9%   |
| 1333    | 5         | 11.9%   |
| 2400    | 4         | 9.52%   |
| 1334    | 3         | 7.14%   |
| 1067    | 2         | 4.76%   |
| 1066    | 2         | 4.76%   |
| 266     | 2         | 4.76%   |
| 4199    | 1         | 2.38%   |
| 3600    | 1         | 2.38%   |
| 3266    | 1         | 2.38%   |
| 3200    | 1         | 2.38%   |
| 2667    | 1         | 2.38%   |
| 2666    | 1         | 2.38%   |
| 2048    | 1         | 2.38%   |
| 800     | 1         | 2.38%   |
| 400     | 1         | 2.38%   |

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
| Alcor Micro USB 2.0 WebCamera                               | 1         | 5.56%   |
| Acer HP Webcam-101                                          | 1         | 5.56%   |
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
| 0     | 32        | 76.19%  |
| 1     | 6         | 14.29%  |
| 2     | 4         | 9.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 7         | 50%     |
| Fingerprint reader       | 3         | 21.43%  |
| Network                  | 1         | 7.14%   |
| Flash memory             | 1         | 7.14%   |
| Communication controller | 1         | 7.14%   |
| Camera                   | 1         | 7.14%   |

