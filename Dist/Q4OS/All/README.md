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

Total: 48

| Vendor        | Model                    | Form-Factor | Probe                                                      | Date         |
|---------------|--------------------------|-------------|------------------------------------------------------------|--------------|
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
| Q4OS 4 | 21        | 51.22%  |
| Q4OS 3 | 15        | 36.59%  |
| Q4OS 2 | 5         | 12.2%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 41        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 4.19.0-17-amd64        | 4         | 9.76%   |
| 5.10.0-12-amd64        | 3         | 7.32%   |
| 5.10.0-8-amd64         | 2         | 4.88%   |
| 5.10.0-14-686-pae      | 2         | 4.88%   |
| 5.10.0-10-686-pae      | 2         | 4.88%   |
| 5.9.0-5-amd64          | 1         | 2.44%   |
| 5.6.0-1-amd64          | 1         | 2.44%   |
| 5.18.0-0.bpo.1-amd64   | 1         | 2.44%   |
| 5.10.0-9-amd64         | 1         | 2.44%   |
| 5.10.0-9-686-pae       | 1         | 2.44%   |
| 5.10.0-8-686-pae       | 1         | 2.44%   |
| 5.10.0-17-amd64        | 1         | 2.44%   |
| 5.10.0-15-686-pae      | 1         | 2.44%   |
| 5.10.0-14-amd64        | 1         | 2.44%   |
| 5.10.0-13-amd64        | 1         | 2.44%   |
| 5.10.0-12-686-pae      | 1         | 2.44%   |
| 5.10.0-11-686-pae      | 1         | 2.44%   |
| 4.9.0-9-686-pae        | 1         | 2.44%   |
| 4.9.0-8-amd64          | 1         | 2.44%   |
| 4.9.0-14-686-pae       | 1         | 2.44%   |
| 4.9.0-12-686-pae       | 1         | 2.44%   |
| 4.19.0-6-amd64         | 1         | 2.44%   |
| 4.19.0-21-amd64        | 1         | 2.44%   |
| 4.19.0-20-amd64        | 1         | 2.44%   |
| 4.19.0-17-686-pae      | 1         | 2.44%   |
| 4.19.0-17-686          | 1         | 2.44%   |
| 4.19.0-16-amd64        | 1         | 2.44%   |
| 4.19.0-16-686          | 1         | 2.44%   |
| 4.19.0-14-amd64        | 1         | 2.44%   |
| 4.19.0-13-amd64        | 1         | 2.44%   |
| 4.19.0-12-amd64        | 1         | 2.44%   |
| 4.19.0-10-amd64        | 1         | 2.44%   |
| 4.19.0-0.bpo.5-686-pae | 1         | 2.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 18        | 43.9%   |
| 4.19.0  | 16        | 39.02%  |
| 4.9.0   | 4         | 9.76%   |
| 5.9.0   | 1         | 2.44%   |
| 5.6.0   | 1         | 2.44%   |
| 5.18.0  | 1         | 2.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 43.9%   |
| 4.19    | 16        | 39.02%  |
| 4.9     | 4         | 9.76%   |
| 5.9     | 1         | 2.44%   |
| 5.6     | 1         | 2.44%   |
| 5.18    | 1         | 2.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 25        | 60.98%  |
| i686   | 16        | 39.02%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Trinity | 21        | 51.22%  |
| KDE5    | 18        | 43.9%   |
| LXDE    | 1         | 2.44%   |
| KDE     | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 40        | 97.56%  |
| Tty  | 1         | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 21        | 51.22%  |
| SDDM    | 19        | 46.34%  |
| LightDM | 1         | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 15        | 36.59%  |
| es_ES   | 3         | 7.32%   |
| en_GB   | 3         | 7.32%   |
| de_DE   | 3         | 7.32%   |
| Unknown | 3         | 7.32%   |
| fr_FR   | 2         | 4.88%   |
| sv_SE   | 1         | 2.44%   |
| sl_SI   | 1         | 2.44%   |
| ru_RU   | 1         | 2.44%   |
| pt_BR   | 1         | 2.44%   |
| pl_PL   | 1         | 2.44%   |
| it_IT   | 1         | 2.44%   |
| es_VE   | 1         | 2.44%   |
| es_AR   | 1         | 2.44%   |
| en_ZA   | 1         | 2.44%   |
| en_SG   | 1         | 2.44%   |
| en_IE   | 1         | 2.44%   |
| C       | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 25        | 60.98%  |
| EFI  | 16        | 39.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 38        | 92.68%  |
| Overlay | 3         | 7.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 23        | 56.1%   |
| GPT     | 17        | 41.46%  |
| Unknown | 1         | 2.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 85.37%  |
| Yes       | 6         | 14.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 63.41%  |
| Yes       | 15        | 36.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 7         | 17.07%  |
| Toshiba                     | 4         | 9.76%   |
| ASUSTek Computer            | 4         | 9.76%   |
| MSI                         | 3         | 7.32%   |
| Lenovo                      | 3         | 7.32%   |
| TrekStor                    | 2         | 4.88%   |
| Medion                      | 2         | 4.88%   |
| ASRock                      | 2         | 4.88%   |
| Visual Land                 | 1         | 2.44%   |
| TECO Electric and Machinery | 1         | 2.44%   |
| Sony                        | 1         | 2.44%   |
| Qilive                      | 1         | 2.44%   |
| Phoenix/SiS                 | 1         | 2.44%   |
| Philco                      | 1         | 2.44%   |
| Packard Bell                | 1         | 2.44%   |
| JVC                         | 1         | 2.44%   |
| Gigabyte Technology         | 1         | 2.44%   |
| Foxconn                     | 1         | 2.44%   |
| Compaq                      | 1         | 2.44%   |
| Chuwi                       | 1         | 2.44%   |
| AMI                         | 1         | 2.44%   |
| Acer                        | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 4.88%   |
| Toshiba Satellite C660                 | 2         | 4.88%   |
| Visual Land Premier 10                 | 1         | 2.44%   |
| Toshiba Satellite Pro L500             | 1         | 2.44%   |
| Toshiba Satellite M70                  | 1         | 2.44%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 2.44%   |
| Sony VGN-P11Z_Q                        | 1         | 2.44%   |
| Qilive QW19141AMSP                     | 1         | 2.44%   |
| Phoenix/SiS M720SR                     | 1         | 2.44%   |
| Philco 14I                             | 1         | 2.44%   |
| Packard Bell EasyNote LM81             | 1         | 2.44%   |
| MSI U210                               | 1         | 2.44%   |
| MSI MS-7C56                            | 1         | 2.44%   |
| MSI MS-7597                            | 1         | 2.44%   |
| Medion P6620                           | 1         | 2.44%   |
| Lenovo ThinkPad T495 20NKS0PG00        | 1         | 2.44%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 2.44%   |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 2.44%   |
| JVC J3N                                | 1         | 2.44%   |
| HP ProBook 6550b                       | 1         | 2.44%   |
| HP ProBook 450 G2                      | 1         | 2.44%   |
| HP Presario CQ56                       | 1         | 2.44%   |
| HP OmniBook PC                         | 1         | 2.44%   |
| HP Laptop 15s-fq2xxx                   | 1         | 2.44%   |
| HP 250 G5 Notebook PC                  | 1         | 2.44%   |
| HP 2000                                | 1         | 2.44%   |
| Gigabyte XP-M5S661GX                   | 1         | 2.44%   |
| Foxconn Pro 3400 Series MT             | 1         | 2.44%   |
| Compaq Evo D510 SFF                    | 1         | 2.44%   |
| Chuwi GemiBook Pro                     | 1         | 2.44%   |
| ASUS X540YA                            | 1         | 2.44%   |
| ASUS T12Eg                             | 1         | 2.44%   |
| ASUS A6U                               | 1         | 2.44%   |
| ASUS A6JC                              | 1         | 2.44%   |
| ASRock H61M-HVS                        | 1         | 2.44%   |
| ASRock G41M-VS3                        | 1         | 2.44%   |
| AMI Intel                              | 1         | 2.44%   |
| Acer AO751h                            | 1         | 2.44%   |
| Unknown                                | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 9.76%   |
| TrekStor SurfTab                  | 2         | 4.88%   |
| Lenovo ThinkPad                   | 2         | 4.88%   |
| HP ProBook                        | 2         | 4.88%   |
| Visual Land Premier               | 1         | 2.44%   |
| TECO Electric and Machinery FUTRO | 1         | 2.44%   |
| Sony VGN-P11Z                     | 1         | 2.44%   |
| Qilive QW19141AMSP                | 1         | 2.44%   |
| Phoenix/SiS M720SR                | 1         | 2.44%   |
| Philco 14I                        | 1         | 2.44%   |
| Packard Bell EasyNote             | 1         | 2.44%   |
| MSI U210                          | 1         | 2.44%   |
| MSI MS-7C56                       | 1         | 2.44%   |
| MSI MS-7597                       | 1         | 2.44%   |
| Medion P6620                      | 1         | 2.44%   |
| Lenovo IdeaPad                    | 1         | 2.44%   |
| JVC J3N                           | 1         | 2.44%   |
| HP Presario                       | 1         | 2.44%   |
| HP OmniBook                       | 1         | 2.44%   |
| HP Laptop                         | 1         | 2.44%   |
| HP 250                            | 1         | 2.44%   |
| HP 2000                           | 1         | 2.44%   |
| Gigabyte XP-M5S661GX              | 1         | 2.44%   |
| Foxconn Pro                       | 1         | 2.44%   |
| Compaq Evo                        | 1         | 2.44%   |
| Chuwi GemiBook                    | 1         | 2.44%   |
| ASUS X540YA                       | 1         | 2.44%   |
| ASUS T12Eg                        | 1         | 2.44%   |
| ASUS A6U                          | 1         | 2.44%   |
| ASUS A6JC                         | 1         | 2.44%   |
| ASRock H61M-HVS                   | 1         | 2.44%   |
| ASRock G41M-VS3                   | 1         | 2.44%   |
| AMI Intel                         | 1         | 2.44%   |
| Acer AO751h                       | 1         | 2.44%   |
| Unknown                           | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 14.63%  |
| 2020    | 4         | 9.76%   |
| 2011    | 4         | 9.76%   |
| 2009    | 4         | 9.76%   |
| 2015    | 3         | 7.32%   |
| 2005    | 3         | 7.32%   |
| 2019    | 2         | 4.88%   |
| 2016    | 2         | 4.88%   |
| 2014    | 2         | 4.88%   |
| 2008    | 2         | 4.88%   |
| Unknown | 2         | 4.88%   |
| 2018    | 1         | 2.44%   |
| 2017    | 1         | 2.44%   |
| 2012    | 1         | 2.44%   |
| 2007    | 1         | 2.44%   |
| 2006    | 1         | 2.44%   |
| 2004    | 1         | 2.44%   |
| 2002    | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 31        | 75.61%  |
| Desktop  | 8         | 19.51%  |
| Tablet   | 2         | 4.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 39        | 95.12%  |
| Enabled  | 2         | 4.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 11        | 26.83%  |
| 2.01-3.0    | 7         | 17.07%  |
| 1.01-2.0    | 6         | 14.63%  |
| 0.51-1.0    | 6         | 14.63%  |
| 4.01-8.0    | 5         | 12.2%   |
| 16.01-24.0  | 2         | 4.88%   |
| 0.01-0.5    | 2         | 4.88%   |
| 24.01-32.0  | 1         | 2.44%   |
| 64.01-256.0 | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 15        | 36.59%  |
| 0.51-1.0  | 11        | 26.83%  |
| 0.01-0.5  | 7         | 17.07%  |
| 2.01-3.0  | 5         | 12.2%   |
| 3.01-4.0  | 2         | 4.88%   |
| 8.01-16.0 | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 70.73%  |
| 2      | 8         | 19.51%  |
| 3      | 4         | 9.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 51.22%  |
| No        | 20        | 48.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 90.24%  |
| No        | 4         | 9.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 73.17%  |
| No        | 11        | 26.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 60.98%  |
| Yes       | 16        | 39.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 5         | 12.2%   |
| UK           | 3         | 7.32%   |
| Spain        | 3         | 7.32%   |
| Kenya        | 3         | 7.32%   |
| Germany      | 3         | 7.32%   |
| Switzerland  | 2         | 4.88%   |
| Romania      | 2         | 4.88%   |
| Poland       | 2         | 4.88%   |
| Italy        | 2         | 4.88%   |
| France       | 2         | 4.88%   |
| Brazil       | 2         | 4.88%   |
| Venezuela    | 1         | 2.44%   |
| Sweden       | 1         | 2.44%   |
| South Africa | 1         | 2.44%   |
| Slovenia     | 1         | 2.44%   |
| Singapore    | 1         | 2.44%   |
| Saudi Arabia | 1         | 2.44%   |
| Russia       | 1         | 2.44%   |
| Qatar        | 1         | 2.44%   |
| Netherlands  | 1         | 2.44%   |
| Belgium      | 1         | 2.44%   |
| Belarus      | 1         | 2.44%   |
| Argentina    | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 7.32%   |
| Zurich                | 2         | 4.88%   |
| Swindon               | 2         | 4.88%   |
| Rostock               | 2         | 4.88%   |
| Mesa                  | 2         | 4.88%   |
| Drobeta-Turnu Severin | 2         | 4.88%   |
| Tranas                | 1         | 2.44%   |
| The Hague             | 1         | 2.44%   |
| Tellico Plains        | 1         | 2.44%   |
| Sosnowiec             | 1         | 2.44%   |
| Singapore             | 1         | 2.44%   |
| Schermbeck            | 1         | 2.44%   |
| Salsomaggiore Terme   | 1         | 2.44%   |
| Puerto Cumarebo       | 1         | 2.44%   |
| Posadas               | 1         | 2.44%   |
| Moscow                | 1         | 2.44%   |
| Moirans               | 1         | 2.44%   |
| Mogilev               | 1         | 2.44%   |
| Londrina              | 1         | 2.44%   |
| Ljubljana             | 1         | 2.44%   |
| Las Vegas             | 1         | 2.44%   |
| Klaudyn               | 1         | 2.44%   |
| Johannesburg          | 1         | 2.44%   |
| Guarulhos             | 1         | 2.44%   |
| Grand Junction        | 1         | 2.44%   |
| Gijón                | 1         | 2.44%   |
| Fulham                | 1         | 2.44%   |
| Doha                  | 1         | 2.44%   |
| Dammam                | 1         | 2.44%   |
| Calvecchia            | 1         | 2.44%   |
| Brussels              | 1         | 2.44%   |
| Boulogne-sur-Mer      | 1         | 2.44%   |
| Barcelona             | 1         | 2.44%   |
| Alicante              | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 16.33%  |
| Seagate             | 7         | 8      | 14.29%  |
| Unknown             | 6         | 6      | 12.24%  |
| Samsung Electronics | 4         | 4      | 8.16%   |
| SanDisk             | 3         | 3      | 6.12%   |
| Hitachi             | 3         | 3      | 6.12%   |
| China               | 3         | 4      | 6.12%   |
| Toshiba             | 2         | 2      | 4.08%   |
| Kingston            | 2         | 2      | 4.08%   |
| KESU                | 2         | 2      | 4.08%   |
| HGST                | 2         | 2      | 4.08%   |
| Unknown (CF)        | 1         | 1      | 2.04%   |
| Silicon Motion      | 1         | 1      | 2.04%   |
| Phison              | 1         | 1      | 2.04%   |
| Maxtor              | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |
| Unknown             | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 3.92%   |
| Samsung SSD 850 EVO 250GB            | 2         | 3.92%   |
| KESU USB 3.1 256GB                   | 2         | 3.92%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.96%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.96%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 1.96%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.96%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.96%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.96%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 1.96%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.96%   |
| Unknown USDU1  32GB                  | 1         | 1.96%   |
| Unknown SLD64G  64GB                 | 1         | 1.96%   |
| Unknown SD/MMC/MS PRO 2GB            | 1         | 1.96%   |
| Unknown 064G38  64GB                 | 1         | 1.96%   |
| Unknown (CF) Card 16GB SSD           | 1         | 1.96%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.96%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.96%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.96%   |
| Seagate ST9120822AS 120GB            | 1         | 1.96%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1.96%   |
| Seagate ST3500413AS 500GB            | 1         | 1.96%   |
| Seagate ST3160815AS 160GB            | 1         | 1.96%   |
| Seagate ST3160812AS 160GB            | 1         | 1.96%   |
| Seagate ST310211A 10GB               | 1         | 1.96%   |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 1.96%   |
| Seagate Backup+ SL 1TB               | 1         | 1.96%   |
| SanDisk SDSSDA120G 120GB             | 1         | 1.96%   |
| SanDisk SDCFX-032G SSD               | 1         | 1.96%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 1.96%   |
| Samsung HD081GJ 80GB                 | 1         | 1.96%   |
| Samsung AWMB3R  16GB                 | 1         | 1.96%   |
| Phison APS-SE20G-1T                  | 1         | 1.96%   |
| Maxtor 6Y080L0 81GB                  | 1         | 1.96%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1.96%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 1.96%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 1.96%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1.96%   |
| Hitachi DK23CA-20 20GB               | 1         | 1.96%   |
| HGST HTS725050A7E630 500GB           | 1         | 1.96%   |

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
| HDD     | 20        | 24     | 45.45%  |
| SSD     | 13        | 15     | 29.55%  |
| MMC     | 6         | 6      | 13.64%  |
| Unknown | 3         | 3      | 6.82%   |
| NVMe    | 2         | 3      | 4.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 38     | 72.09%  |
| MMC  | 6         | 6      | 13.95%  |
| SAS  | 4         | 4      | 9.3%    |
| NVMe | 2         | 3      | 4.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 35     | 87.88%  |
| 0.51-1.0   | 3         | 3      | 9.09%   |
| 4.01-10.0  | 1         | 1      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 9         | 21.95%  |
| 51-100         | 9         | 21.95%  |
| 101-250        | 6         | 14.63%  |
| 251-500        | 5         | 12.2%   |
| 21-50          | 5         | 12.2%   |
| 1001-2000      | 3         | 7.32%   |
| 501-1000       | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 68.29%  |
| 21-50          | 6         | 14.63%  |
| 251-500        | 2         | 4.88%   |
| 501-1000       | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| 51-100         | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

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
| Works    | 23        | 30     | 53.49%  |
| Detected | 10        | 11     | 23.26%  |
| Malfunc  | 10        | 10     | 23.26%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 24        | 61.54%  |
| AMD                              | 7         | 17.95%  |
| Silicon Integrated Systems [SiS] | 4         | 10.26%  |
| Silicon Motion                   | 1         | 2.56%   |
| SanDisk                          | 1         | 2.56%   |
| Phison Electronics               | 1         | 2.56%   |
| Nvidia                           | 1         | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 4         | 8.51%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 8.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 6.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 6.38%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 4.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 4.26%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.13%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 2.13%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 2.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.13%   |
| Phison E12 NVMe Controller                                                       | 1         | 2.13%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 2.13%   |
| Nvidia MCP61 IDE                                                                 | 1         | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.13%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 2.13%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 2.13%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 2.13%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 2.13%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 2.13%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 2.13%   |
| AMD 500 Series Chipset SATA Controller                                           | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 21        | 52.5%   |
| IDE  | 15        | 37.5%   |
| RAID | 2         | 5%      |
| NVMe | 2         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 30        | 73.17%  |
| AMD    | 11        | 26.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz                 | 3         | 7.32%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 4.88%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 4.88%   |
| Intel Pentium M processor 1000MHz               | 1         | 2.44%   |
| Intel Pentium M processor 1.70GHz               | 1         | 2.44%   |
| Intel Pentium III (Coppermine)                  | 1         | 2.44%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2.44%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 2.44%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1         | 2.44%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1         | 2.44%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 2.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1         | 2.44%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2.44%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.44%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2.44%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2.44%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.44%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.44%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.44%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2.44%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.44%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2.44%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.44%   |
| AMD V120 Processor                              | 1         | 2.44%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.44%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1         | 2.44%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 2.44%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.44%   |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2.44%   |
| AMD Athlon Processor                            | 1         | 2.44%   |
| AMD Athlon Neo Processor MV-40                  | 1         | 2.44%   |
| AMD Athlon II X2 250 Processor                  | 1         | 2.44%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.44%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G   | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 6         | 14.63%  |
| Intel Celeron           | 5         | 12.2%   |
| Intel Core 2 Duo        | 4         | 9.76%   |
| Intel Core i5           | 3         | 7.32%   |
| Intel Pentium M         | 2         | 4.88%   |
| Intel Pentium Dual-Core | 2         | 4.88%   |
| Intel Pentium 4         | 2         | 4.88%   |
| Intel Core i3           | 2         | 4.88%   |
| Other                   | 1         | 2.44%   |
| Intel Pentium III       | 1         | 2.44%   |
| Intel Core i7           | 1         | 2.44%   |
| Intel Core 2            | 1         | 2.44%   |
| AMD V120                | 1         | 2.44%   |
| AMD Ryzen 7 PRO         | 1         | 2.44%   |
| AMD Ryzen 7             | 1         | 2.44%   |
| AMD Mobile Sempron      | 1         | 2.44%   |
| AMD E                   | 1         | 2.44%   |
| AMD C-70                | 1         | 2.44%   |
| AMD Athlon Neo          | 1         | 2.44%   |
| AMD Athlon II X2        | 1         | 2.44%   |
| AMD Athlon              | 1         | 2.44%   |
| AMD A8                  | 1         | 2.44%   |
| AMD A4                  | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 41.46%  |
| 4      | 12        | 29.27%  |
| 1      | 11        | 26.83%  |
| 8      | 1         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 73.17%  |
| 2      | 11        | 26.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 80.49%  |
| 32-bit         | 8         | 19.51%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 12.2%   |
| 0x30678    | 4         | 9.76%   |
| 0x206a7    | 4         | 9.76%   |
| 0x1067a    | 4         | 9.76%   |
| 0x706a1    | 2         | 4.88%   |
| 0x6fd      | 2         | 4.88%   |
| 0x010000c8 | 2         | 4.88%   |
| 0xf49      | 1         | 2.44%   |
| 0xf27      | 1         | 2.44%   |
| 0x806c1    | 1         | 2.44%   |
| 0x706a8    | 1         | 2.44%   |
| 0x6f6      | 1         | 2.44%   |
| 0x6d8      | 1         | 2.44%   |
| 0x695      | 1         | 2.44%   |
| 0x68a      | 1         | 2.44%   |
| 0x406c4    | 1         | 2.44%   |
| 0x40651    | 1         | 2.44%   |
| 0x20655    | 1         | 2.44%   |
| 0x106c2    | 1         | 2.44%   |
| 0x08108102 | 1         | 2.44%   |
| 0x0800820d | 1         | 2.44%   |
| 0x07030106 | 1         | 2.44%   |
| 0x06006705 | 1         | 2.44%   |
| 0x05000119 | 1         | 2.44%   |
| 0x0500010d | 1         | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 6         | 14.63%  |
| SandyBridge   | 4         | 9.76%   |
| Penryn        | 4         | 9.76%   |
| P6            | 3         | 7.32%   |
| Goldmont plus | 3         | 7.32%   |
| Core          | 3         | 7.32%   |
| Zen+          | 2         | 4.88%   |
| NetBurst      | 2         | 4.88%   |
| K8 Hammer     | 2         | 4.88%   |
| K10           | 2         | 4.88%   |
| Bonnell       | 2         | 4.88%   |
| Bobcat        | 2         | 4.88%   |
| Westmere      | 1         | 2.44%   |
| TigerLake     | 1         | 2.44%   |
| Puma          | 1         | 2.44%   |
| K6            | 1         | 2.44%   |
| Haswell       | 1         | 2.44%   |
| Excavator     | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 52.38%  |
| AMD                              | 10        | 23.81%  |
| Nvidia                           | 5         | 11.9%   |
| Silicon Integrated Systems [SiS] | 4         | 9.52%   |
| S3 Graphics                      | 1         | 2.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 9.3%    |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 6.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 6.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 6.98%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 4.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 2         | 4.65%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 2.33%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 2.33%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 2.33%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 2.33%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 2.33%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 2.33%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 2.33%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 2.33%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 2.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 1         | 2.33%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 2.33%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 2.33%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 2.33%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 1         | 2.33%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 2.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 2.33%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 2.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 20        | 48.78%  |
| 1 x AMD         | 9         | 21.95%  |
| 1 x Nvidia      | 5         | 12.2%   |
| 1 x SiS         | 4         | 9.76%   |
| Other           | 1         | 2.44%   |
| 1 x S3 Graphics | 1         | 2.44%   |
| Intel + AMD     | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 33        | 80.49%  |
| Unknown     | 5         | 12.2%   |
| Proprietary | 3         | 7.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 60.98%  |
| 0.01-0.5   | 11        | 26.83%  |
| 1.01-2.0   | 4         | 9.76%   |
| 3.01-4.0   | 1         | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 22.86%  |
| Chimei Innolux      | 7         | 20%     |
| AU Optronics        | 6         | 17.14%  |
| LG Display          | 3         | 8.57%   |
| Hewlett-Packard     | 2         | 5.71%   |
| ViewSonic           | 1         | 2.86%   |
| VIE                 | 1         | 2.86%   |
| Orion               | 1         | 2.86%   |
| HannStar            | 1         | 2.86%   |
| Goldstar            | 1         | 2.86%   |
| Dell                | 1         | 2.86%   |
| CPT                 | 1         | 2.86%   |
| BOE                 | 1         | 2.86%   |
| Acer                | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 5.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 5.71%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 2.86%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 2.86%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 2.86%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 2.86%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 2.86%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 2.86%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 2.86%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 2.86%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1         | 2.86%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 2.86%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 2.86%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 2.86%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 2.86%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch         | 1         | 2.86%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch           | 1         | 2.86%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                      | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 12        | 34.29%  |
| 1920x1080 (FHD)    | 10        | 28.57%  |
| 1600x900 (HD+)     | 5         | 14.29%  |
| 1280x800 (WXGA)    | 3         | 8.57%   |
| 3840x2160 (4K)     | 1         | 2.86%   |
| 2160x1440          | 1         | 2.86%   |
| 1920x540           | 1         | 2.86%   |
| 1920x1200 (WUXGA)  | 1         | 2.86%   |
| 1680x1050 (WSXGA+) | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 42.86%  |
| 13      | 3         | 8.57%   |
| 23      | 2         | 5.71%   |
| 11      | 2         | 5.71%   |
| 46      | 1         | 2.86%   |
| 40      | 1         | 2.86%   |
| 31      | 1         | 2.86%   |
| 24      | 1         | 2.86%   |
| 22      | 1         | 2.86%   |
| 21      | 1         | 2.86%   |
| 20      | 1         | 2.86%   |
| 19      | 1         | 2.86%   |
| 18      | 1         | 2.86%   |
| 17      | 1         | 2.86%   |
| 14      | 1         | 2.86%   |
| 12      | 1         | 2.86%   |
| Unknown | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 48.57%  |
| 401-500     | 4         | 11.43%  |
| 201-300     | 4         | 11.43%  |
| 501-600     | 3         | 8.57%   |
| 351-400     | 3         | 8.57%   |
| 801-900     | 1         | 2.86%   |
| 601-700     | 1         | 2.86%   |
| 1001-1500   | 1         | 2.86%   |
| Unknown     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 78.13%  |
| 16/10 | 5         | 15.63%  |
| 32/9  | 1         | 3.13%   |
| 3/2   | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 42.86%  |
| 81-90          | 4         | 11.43%  |
| 201-250        | 4         | 11.43%  |
| 51-60          | 2         | 5.71%   |
| 151-200        | 2         | 5.71%   |
| 501-1000       | 2         | 5.71%   |
| 61-70          | 1         | 2.86%   |
| 351-500        | 1         | 2.86%   |
| 251-300        | 1         | 2.86%   |
| 141-150        | 1         | 2.86%   |
| 121-130        | 1         | 2.86%   |
| Unknown        | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 14        | 40%     |
| 51-100  | 11        | 31.43%  |
| 121-160 | 6         | 17.14%  |
| 161-240 | 2         | 5.71%   |
| 1-50    | 1         | 2.86%   |
| Unknown | 1         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 36        | 87.8%   |
| 2     | 2         | 4.88%   |
| 0     | 2         | 4.88%   |
| 3     | 1         | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 29        | 43.28%  |
| Qualcomm Atheros                 | 12        | 17.91%  |
| Intel                            | 10        | 14.93%  |
| Silicon Integrated Systems [SiS] | 3         | 4.48%   |
| Samsung Electronics              | 2         | 2.99%   |
| Broadcom                         | 2         | 2.99%   |
| Xiaomi                           | 1         | 1.49%   |
| Motorola PCS                     | 1         | 1.49%   |
| Marvell Technology Group         | 1         | 1.49%   |
| LG Electronics                   | 1         | 1.49%   |
| JMicron Technology               | 1         | 1.49%   |
| IBM                              | 1         | 1.49%   |
| Guillemot                        | 1         | 1.49%   |
| Broadcom Limited                 | 1         | 1.49%   |
| Accton Technology                | 1         | 1.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 10        | 13.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 9         | 12.33%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                     | 3         | 4.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 3         | 4.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 3         | 4.11%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 2         | 2.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 2.74%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                | 2         | 2.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 2         | 2.74%   |
| Intel Wi-Fi 6 AX200                                                       | 2         | 2.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 2         | 2.74%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                  | 2         | 2.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                 | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                   | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter             | 1         | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1         | 1.37%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                | 1         | 1.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1         | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 1         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 1         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 1         | 1.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1         | 1.37%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1         | 1.37%   |
| Motorola PCS Moto G (5) Plus                                              | 1         | 1.37%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                   | 1         | 1.37%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                       | 1         | 1.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                    | 1         | 1.37%   |
| Intel Wireless 3165                                                       | 1         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                           | 1         | 1.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller          | 1         | 1.37%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller         | 1         | 1.37%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                        | 1         | 1.37%   |
| Intel 82577LC Gigabit Network Connection                                  | 1         | 1.37%   |
| IBM Winnipeg PCI-X Host Bridge                                            | 1         | 1.37%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1         | 1.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 1         | 1.37%   |

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
| Realtek Semiconductor            | 25        | 64.1%   |
| Silicon Integrated Systems [SiS] | 2         | 5.13%   |
| Samsung Electronics              | 2         | 5.13%   |
| Intel                            | 2         | 5.13%   |
| Xiaomi                           | 1         | 2.56%   |
| Qualcomm Atheros                 | 1         | 2.56%   |
| Motorola PCS                     | 1         | 2.56%   |
| Marvell Technology Group         | 1         | 2.56%   |
| LG Electronics                   | 1         | 2.56%   |
| JMicron Technology               | 1         | 2.56%   |
| Broadcom                         | 1         | 2.56%   |
| Accton Technology                | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 25.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 23.08%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 7.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 5.13%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 5.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.56%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 2.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.56%   |
| Motorola PCS Moto G (5) Plus                                      | 1         | 2.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.56%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 2.56%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.56%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 52.11%  |
| WiFi     | 30        | 42.25%  |
| Modem    | 3         | 4.23%   |
| Unknown  | 1         | 1.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 53.85%  |
| Ethernet | 18        | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 56.1%   |
| 1     | 13        | 31.71%  |
| 0     | 4         | 9.76%   |
| 3     | 1         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 38        | 92.68%  |
| Yes  | 3         | 7.32%   |

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
| Intel                            | 23        | 57.5%   |
| AMD                              | 10        | 25%     |
| Silicon Integrated Systems [SiS] | 3         | 7.5%    |
| Nvidia                           | 3         | 7.5%    |
| ESS Technology                   | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 8.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 6.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 6.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 6.25%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 4.17%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 4.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.17%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 4.17%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 4.17%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 4.17%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.17%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 2.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 2.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.08%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 2.08%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.08%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 2.08%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2.08%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.08%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 2.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 18        | 43.9%   |
| Samsung Electronics | 8         | 19.51%  |
| SK hynix            | 5         | 12.2%   |
| Unknown (ABCD)      | 2         | 4.88%   |
| Kingston            | 2         | 4.88%   |
| Transcend           | 1         | 2.44%   |
| Toshiba             | 1         | 2.44%   |
| Teikon              | 1         | 2.44%   |
| Team                | 1         | 2.44%   |
| Elpida              | 1         | 2.44%   |
| A-DATA Technology   | 1         | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 9.09%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 4.55%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 4.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 4.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 4.55%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 2.27%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 2.27%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 2.27%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 2.27%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 2.27%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 2.27%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 2.27%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 2.27%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 2.27%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 2.27%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 2.27%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 2.27%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 2.27%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 2.27%   |
| Toshiba RAM 8HTF12864HDY-800G1 1024MB SODIMM 1066MT/s            | 1         | 2.27%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 2.27%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 2.27%   |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s              | 1         | 2.27%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 2.27%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 2.27%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.27%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s          | 1         | 2.27%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 2.27%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.27%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 2.27%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 2.27%   |
| Kingston RAM HP32D4S2S1ME-4 4096MB SODIMM DDR4 3200MT/s          | 1         | 2.27%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 2.27%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s            | 1         | 2.27%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s             | 1         | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 14        | 35.9%   |
| SDRAM   | 7         | 17.95%  |
| DDR2    | 6         | 15.38%  |
| DDR4    | 5         | 12.82%  |
| LPDDR4  | 2         | 5.13%   |
| DDR     | 2         | 5.13%   |
| Unknown | 2         | 5.13%   |
| DRAM    | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 28        | 71.79%  |
| DIMM   | 11        | 28.21%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 14        | 34.15%  |
| 2048  | 13        | 31.71%  |
| 1024  | 7         | 17.07%  |
| 512   | 3         | 7.32%   |
| 32768 | 1         | 2.44%   |
| 16384 | 1         | 2.44%   |
| 8192  | 1         | 2.44%   |
| 256   | 1         | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 24.39%  |
| 1600    | 5         | 12.2%   |
| 1333    | 5         | 12.2%   |
| 2400    | 4         | 9.76%   |
| 1334    | 3         | 7.32%   |
| 1067    | 2         | 4.88%   |
| 1066    | 2         | 4.88%   |
| 266     | 2         | 4.88%   |
| 4199    | 1         | 2.44%   |
| 3600    | 1         | 2.44%   |
| 3266    | 1         | 2.44%   |
| 3200    | 1         | 2.44%   |
| 2667    | 1         | 2.44%   |
| 2048    | 1         | 2.44%   |
| 800     | 1         | 2.44%   |
| 400     | 1         | 2.44%   |

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
| Alcor Micro SHUNCCM2MP                                      | 1         | 5.56%   |
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
| 0     | 32        | 78.05%  |
| 1     | 5         | 12.2%   |
| 2     | 4         | 9.76%   |

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

