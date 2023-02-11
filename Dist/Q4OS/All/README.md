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

Total: 62

| Vendor        | Model                    | Form-Factor | Probe                                                      | Date         |
|---------------|--------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 1850                     | Desktop     | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| VXL           | M6V90AI-VL               | Desktop     | [1ad8dbaae1](https://linux-hardware.org/?probe=1ad8dbaae1) | Jan 08, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Q4OS 4 | 29        | 58%     |
| Q4OS 3 | 16        | 32%     |
| Q4OS 2 | 5         | 10%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-19-amd64        | 4         | 8%      |
| 4.19.0-17-amd64        | 4         | 8%      |
| 5.10.0-12-amd64        | 3         | 6%      |
| 5.10.0-8-amd64         | 2         | 4%      |
| 5.10.0-14-686-pae      | 2         | 4%      |
| 5.10.0-10-686-pae      | 2         | 4%      |
| 6.0.0-1-amd64          | 1         | 2%      |
| 5.9.0-5-amd64          | 1         | 2%      |
| 5.6.0-1-amd64          | 1         | 2%      |
| 5.18.0-0.bpo.1-amd64   | 1         | 2%      |
| 5.10.0-9-amd64         | 1         | 2%      |
| 5.10.0-9-686-pae       | 1         | 2%      |
| 5.10.0-8-686-pae       | 1         | 2%      |
| 5.10.0-20-amd64        | 1         | 2%      |
| 5.10.0-20-686-pae      | 1         | 2%      |
| 5.10.0-20-686          | 1         | 2%      |
| 5.10.0-17-amd64        | 1         | 2%      |
| 5.10.0-15-686-pae      | 1         | 2%      |
| 5.10.0-14-amd64        | 1         | 2%      |
| 5.10.0-13-amd64        | 1         | 2%      |
| 5.10.0-12-686-pae      | 1         | 2%      |
| 5.10.0-11-686-pae      | 1         | 2%      |
| 4.9.0-9-686-pae        | 1         | 2%      |
| 4.9.0-8-amd64          | 1         | 2%      |
| 4.9.0-14-686-pae       | 1         | 2%      |
| 4.9.0-12-686-pae       | 1         | 2%      |
| 4.19.0-6-amd64         | 1         | 2%      |
| 4.19.0-22-amd64        | 1         | 2%      |
| 4.19.0-21-amd64        | 1         | 2%      |
| 4.19.0-20-amd64        | 1         | 2%      |
| 4.19.0-17-686-pae      | 1         | 2%      |
| 4.19.0-17-686          | 1         | 2%      |
| 4.19.0-16-amd64        | 1         | 2%      |
| 4.19.0-16-686          | 1         | 2%      |
| 4.19.0-14-amd64        | 1         | 2%      |
| 4.19.0-13-amd64        | 1         | 2%      |
| 4.19.0-12-amd64        | 1         | 2%      |
| 4.19.0-10-amd64        | 1         | 2%      |
| 4.19.0-0.bpo.5-686-pae | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 25        | 50%     |
| 4.19.0  | 17        | 34%     |
| 4.9.0   | 4         | 8%      |
| 6.0.0   | 1         | 2%      |
| 5.9.0   | 1         | 2%      |
| 5.6.0   | 1         | 2%      |
| 5.18.0  | 1         | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 25        | 50%     |
| 4.19    | 17        | 34%     |
| 4.9     | 4         | 8%      |
| 6.0     | 1         | 2%      |
| 5.9     | 1         | 2%      |
| 5.6     | 1         | 2%      |
| 5.18    | 1         | 2%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 64%     |
| i686   | 18        | 36%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trinity  | 28        | 56%     |
| KDE5     | 19        | 38%     |
| LXDE     | 1         | 2%      |
| KDE      | 1         | 2%      |
| Cinnamon | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 49        | 98%     |
| Tty  | 1         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 28        | 56%     |
| SDDM    | 21        | 42%     |
| LightDM | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 17        | 34%     |
| it_IT   | 4         | 8%      |
| es_ES   | 3         | 6%      |
| en_GB   | 3         | 6%      |
| de_DE   | 3         | 6%      |
| Unknown | 3         | 6%      |
| fr_FR   | 2         | 4%      |
| sv_SE   | 1         | 2%      |
| sl_SI   | 1         | 2%      |
| sk_SK   | 1         | 2%      |
| ru_RU   | 1         | 2%      |
| pt_BR   | 1         | 2%      |
| pl_PL   | 1         | 2%      |
| hu_HU   | 1         | 2%      |
| es_VE   | 1         | 2%      |
| es_PE   | 1         | 2%      |
| es_AR   | 1         | 2%      |
| en_ZA   | 1         | 2%      |
| en_SG   | 1         | 2%      |
| en_IE   | 1         | 2%      |
| C       | 1         | 2%      |
| bg_BG   | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 31        | 62%     |
| EFI  | 19        | 38%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 47        | 94%     |
| Overlay | 3         | 6%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 26        | 52%     |
| GPT     | 23        | 46%     |
| Unknown | 1         | 2%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 88%     |
| Yes       | 6         | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 66%     |
| Yes       | 17        | 34%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 8         | 16%     |
| Toshiba                     | 4         | 8%      |
| MSI                         | 4         | 8%      |
| ASUSTek Computer            | 4         | 8%      |
| ASRock                      | 4         | 8%      |
| Lenovo                      | 3         | 6%      |
| TrekStor                    | 2         | 4%      |
| Medion                      | 2         | 4%      |
| Gigabyte Technology         | 2         | 4%      |
| VXL                         | 1         | 2%      |
| Visual Land                 | 1         | 2%      |
| TECO Electric and Machinery | 1         | 2%      |
| Sony                        | 1         | 2%      |
| Qilive                      | 1         | 2%      |
| Phoenix/SiS                 | 1         | 2%      |
| Philco                      | 1         | 2%      |
| Packard Bell                | 1         | 2%      |
| JVC                         | 1         | 2%      |
| IBM                         | 1         | 2%      |
| Google                      | 1         | 2%      |
| Foxconn                     | 1         | 2%      |
| Compaq                      | 1         | 2%      |
| Chuwi                       | 1         | 2%      |
| BESSTAR Tech                | 1         | 2%      |
| AMI                         | 1         | 2%      |
| Acer                        | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 4%      |
| Toshiba Satellite C660                 | 2         | 4%      |
| VXL TC7500D Series                     | 1         | 2%      |
| Visual Land Premier 10                 | 1         | 2%      |
| Toshiba Satellite Pro L500             | 1         | 2%      |
| Toshiba Satellite M70                  | 1         | 2%      |
| TECO Electric and Machinery FUTRO S400 | 1         | 2%      |
| Sony VGN-P11Z_Q                        | 1         | 2%      |
| Qilive QW19141AMSP                     | 1         | 2%      |
| Phoenix/SiS M720SR                     | 1         | 2%      |
| Philco 14I                             | 1         | 2%      |
| Packard Bell EasyNote LM81             | 1         | 2%      |
| MSI U210                               | 1         | 2%      |
| MSI MS-7C56                            | 1         | 2%      |
| MSI MS-7597                            | 1         | 2%      |
| MSI MS-7592                            | 1         | 2%      |
| Medion P6620                           | 1         | 2%      |
| Lenovo ThinkPad T495 20NKS0PG00        | 1         | 2%      |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 2%      |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 2%      |
| JVC J3N                                | 1         | 2%      |
| IBM ThinkPad T42 2378FVU               | 1         | 2%      |
| HP ProBook 6550b                       | 1         | 2%      |
| HP ProBook 450 G2                      | 1         | 2%      |
| HP Presario CQ56                       | 1         | 2%      |
| HP OmniBook PC                         | 1         | 2%      |
| HP Laptop 15s-fq2xxx                   | 1         | 2%      |
| HP Compaq Pro 6305 SFF                 | 1         | 2%      |
| HP 250 G5 Notebook PC                  | 1         | 2%      |
| HP 2000                                | 1         | 2%      |
| Google Cave                            | 1         | 2%      |
| Gigabyte XP-M5S661GX                   | 1         | 2%      |
| Gigabyte AB350-Gaming                  | 1         | 2%      |
| Foxconn Pro 3400 Series MT             | 1         | 2%      |
| Compaq Evo D510 SFF                    | 1         | 2%      |
| Chuwi GemiBook Pro                     | 1         | 2%      |
| BESSTAR Tech UM250                     | 1         | 2%      |
| ASUS X540YA                            | 1         | 2%      |
| ASUS T12Eg                             | 1         | 2%      |
| ASUS A6U                               | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 4         | 8%      |
| TrekStor SurfTab                  | 2         | 4%      |
| Lenovo ThinkPad                   | 2         | 4%      |
| HP ProBook                        | 2         | 4%      |
| VXL TC7500D                       | 1         | 2%      |
| Visual Land Premier               | 1         | 2%      |
| TECO Electric and Machinery FUTRO | 1         | 2%      |
| Sony VGN-P11Z                     | 1         | 2%      |
| Qilive QW19141AMSP                | 1         | 2%      |
| Phoenix/SiS M720SR                | 1         | 2%      |
| Philco 14I                        | 1         | 2%      |
| Packard Bell EasyNote             | 1         | 2%      |
| MSI U210                          | 1         | 2%      |
| MSI MS-7C56                       | 1         | 2%      |
| MSI MS-7597                       | 1         | 2%      |
| MSI MS-7592                       | 1         | 2%      |
| Medion P6620                      | 1         | 2%      |
| Lenovo IdeaPad                    | 1         | 2%      |
| JVC J3N                           | 1         | 2%      |
| IBM ThinkPad                      | 1         | 2%      |
| HP Presario                       | 1         | 2%      |
| HP OmniBook                       | 1         | 2%      |
| HP Laptop                         | 1         | 2%      |
| HP Compaq                         | 1         | 2%      |
| HP 250                            | 1         | 2%      |
| HP 2000                           | 1         | 2%      |
| Google Cave                       | 1         | 2%      |
| Gigabyte XP-M5S661GX              | 1         | 2%      |
| Gigabyte AB350-Gaming             | 1         | 2%      |
| Foxconn Pro                       | 1         | 2%      |
| Compaq Evo                        | 1         | 2%      |
| Chuwi GemiBook                    | 1         | 2%      |
| BESSTAR Tech UM250                | 1         | 2%      |
| ASUS X540YA                       | 1         | 2%      |
| ASUS T12Eg                        | 1         | 2%      |
| ASUS A6U                          | 1         | 2%      |
| ASUS A6JC                         | 1         | 2%      |
| ASRock J3455B-ITX                 | 1         | 2%      |
| ASRock H61M-HVS                   | 1         | 2%      |
| ASRock G41M-VS3                   | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 12%     |
| 2009    | 5         | 10%     |
| 2020    | 4         | 8%      |
| 2011    | 4         | 8%      |
| 2016    | 3         | 6%      |
| 2015    | 3         | 6%      |
| 2005    | 3         | 6%      |
| 2019    | 2         | 4%      |
| 2018    | 2         | 4%      |
| 2017    | 2         | 4%      |
| 2014    | 2         | 4%      |
| 2012    | 2         | 4%      |
| 2008    | 2         | 4%      |
| 2004    | 2         | 4%      |
| Unknown | 2         | 4%      |
| 2022    | 1         | 2%      |
| 2021    | 1         | 2%      |
| 2013    | 1         | 2%      |
| 2007    | 1         | 2%      |
| 2006    | 1         | 2%      |
| 2002    | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 33        | 66%     |
| Desktop  | 15        | 30%     |
| Tablet   | 2         | 4%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 48        | 96%     |
| Enabled  | 2         | 4%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 98%     |
| Yes  | 1         | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 14        | 28%     |
| 2.01-3.0    | 8         | 16%     |
| 1.01-2.0    | 7         | 14%     |
| 4.01-8.0    | 6         | 12%     |
| 0.51-1.0    | 6         | 12%     |
| 16.01-24.0  | 3         | 6%      |
| 0.01-0.5    | 2         | 4%      |
| 32.01-64.0  | 1         | 2%      |
| 24.01-32.0  | 1         | 2%      |
| 64.01-256.0 | 1         | 2%      |
| 8.01-16.0   | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 16        | 32%     |
| 0.51-1.0  | 13        | 26%     |
| 2.01-3.0  | 9         | 18%     |
| 0.01-0.5  | 7         | 14%     |
| 3.01-4.0  | 3         | 6%      |
| 4.01-8.0  | 1         | 2%      |
| 8.01-16.0 | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 72%     |
| 2      | 10        | 20%     |
| 3      | 4         | 8%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 52%     |
| Yes       | 24        | 48%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 90%     |
| No        | 5         | 10%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 70%     |
| No        | 15        | 30%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 64%     |
| Yes       | 18        | 36%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 7         | 14%     |
| Italy        | 5         | 10%     |
| UK           | 3         | 6%      |
| Spain        | 3         | 6%      |
| Kenya        | 3         | 6%      |
| Germany      | 3         | 6%      |
| Switzerland  | 2         | 4%      |
| Romania      | 2         | 4%      |
| Poland       | 2         | 4%      |
| France       | 2         | 4%      |
| Brazil       | 2         | 4%      |
| Venezuela    | 1         | 2%      |
| Sweden       | 1         | 2%      |
| South Africa | 1         | 2%      |
| Slovenia     | 1         | 2%      |
| Slovakia     | 1         | 2%      |
| Singapore    | 1         | 2%      |
| Saudi Arabia | 1         | 2%      |
| Russia       | 1         | 2%      |
| Qatar        | 1         | 2%      |
| Peru         | 1         | 2%      |
| Netherlands  | 1         | 2%      |
| Hungary      | 1         | 2%      |
| Bulgaria     | 1         | 2%      |
| Belgium      | 1         | 2%      |
| Belarus      | 1         | 2%      |
| Argentina    | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 6%      |
| Zurich                | 2         | 4%      |
| Swindon               | 2         | 4%      |
| Rostock               | 2         | 4%      |
| Mesa                  | 2         | 4%      |
| Drobeta-Turnu Severin | 2         | 4%      |
| Bologna               | 2         | 4%      |
| Toalmas               | 1         | 2%      |
| The Hague             | 1         | 2%      |
| Tellico Plains        | 1         | 2%      |
| Sosnowiec             | 1         | 2%      |
| Sofia                 | 1         | 2%      |
| Singapore             | 1         | 2%      |
| Schermbeck            | 1         | 2%      |
| Salsomaggiore Terme   | 1         | 2%      |
| Rome                  | 1         | 2%      |
| Puerto Cumarebo       | 1         | 2%      |
| Posadas               | 1         | 2%      |
| Moscow                | 1         | 2%      |
| Mooresville           | 1         | 2%      |
| Moirans               | 1         | 2%      |
| Mogilev               | 1         | 2%      |
| Londrina              | 1         | 2%      |
| Ljubljana             | 1         | 2%      |
| Lima                  | 1         | 2%      |
| Las Vegas             | 1         | 2%      |
| Klaudyn               | 1         | 2%      |
| Jönköping           | 1         | 2%      |
| Johannesburg          | 1         | 2%      |
| Indianapolis          | 1         | 2%      |
| Guarulhos             | 1         | 2%      |
| Grand Junction        | 1         | 2%      |
| Gijón                | 1         | 2%      |
| Fulham                | 1         | 2%      |
| Doha                  | 1         | 2%      |
| Dammam                | 1         | 2%      |
| Calvecchia            | 1         | 2%      |
| Brussels              | 1         | 2%      |
| Bratislava            | 1         | 2%      |
| Boulogne-sur-Mer      | 1         | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 16.67%  |
| Seagate             | 8         | 9      | 13.33%  |
| Unknown             | 7         | 7      | 11.67%  |
| Samsung Electronics | 5         | 5      | 8.33%   |
| SanDisk             | 3         | 3      | 5%      |
| Kingston            | 3         | 3      | 5%      |
| Hitachi             | 3         | 3      | 5%      |
| China               | 3         | 4      | 5%      |
| Toshiba             | 2         | 2      | 3.33%   |
| KESU                | 2         | 2      | 3.33%   |
| HGST                | 2         | 2      | 3.33%   |
| A-DATA Technology   | 2         | 2      | 3.33%   |
| Unknown (CF)        | 1         | 1      | 1.67%   |
| Transcend           | 1         | 1      | 1.67%   |
| SPCC                | 1         | 1      | 1.67%   |
| Silicon Motion      | 1         | 1      | 1.67%   |
| Phison              | 1         | 1      | 1.67%   |
| Maxtor              | 1         | 1      | 1.67%   |
| KingSpec            | 1         | 1      | 1.67%   |
| Fujitsu             | 1         | 1      | 1.67%   |
| Crucial             | 1         | 2      | 1.67%   |
| Unknown             | 1         | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 3.17%   |
| Samsung SSD 850 EVO 250GB            | 2         | 3.17%   |
| KESU USB 3.1 256GB                   | 2         | 3.17%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.59%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.59%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 1.59%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.59%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.59%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.59%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 1.59%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 1.59%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 1.59%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.59%   |
| Unknown USDU1  32GB                  | 1         | 1.59%   |
| Unknown SLD64G  64GB                 | 1         | 1.59%   |
| Unknown SD/MMC/MS PRO 2GB            | 1         | 1.59%   |
| Unknown MMC Card  64GB               | 1         | 1.59%   |
| Unknown 064G38  64GB                 | 1         | 1.59%   |
| Unknown (CF) Card 16GB SSD           | 1         | 1.59%   |
| Transcend TS32GHSD370 32GB SSD       | 1         | 1.59%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.59%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.59%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1.59%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.59%   |
| Seagate ST9120822AS 120GB            | 1         | 1.59%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1.59%   |
| Seagate ST3500413AS 500GB            | 1         | 1.59%   |
| Seagate ST3320820SCE 320GB           | 1         | 1.59%   |
| Seagate ST3160815AS 160GB            | 1         | 1.59%   |
| Seagate ST3160812AS 160GB            | 1         | 1.59%   |
| Seagate ST310211A 10GB               | 1         | 1.59%   |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 1.59%   |
| Seagate Backup+ SL 1TB               | 1         | 1.59%   |
| SanDisk SDSSDA120G 120GB             | 1         | 1.59%   |
| SanDisk SDCFX-032G SSD               | 1         | 1.59%   |
| SanDisk SD8SN8U1T001122 1024GB SSD   | 1         | 1.59%   |
| Samsung SSD 860 EVO 250GB            | 1         | 1.59%   |
| Samsung HD081GJ 80GB                 | 1         | 1.59%   |
| Samsung AWMB3R  16GB                 | 1         | 1.59%   |
| Phison APS-SE20G-1T                  | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 30.77%  |
| Seagate             | 7         | 8      | 26.92%  |
| Hitachi             | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| HGST                | 2         | 2      | 7.69%   |
| Unknown             | 1         | 1      | 3.85%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 15.79%  |
| Samsung Electronics | 3         | 3      | 15.79%  |
| Kingston            | 3         | 3      | 15.79%  |
| China               | 3         | 4      | 15.79%  |
| WDC                 | 1         | 1      | 5.26%   |
| Unknown (CF)        | 1         | 1      | 5.26%   |
| Transcend           | 1         | 1      | 5.26%   |
| KingSpec            | 1         | 1      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |
| A-DATA Technology   | 1         | 1      | 5.26%   |
| Unknown             | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 22        | 27     | 40%     |
| SSD     | 18        | 20     | 32.73%  |
| MMC     | 7         | 7      | 12.73%  |
| NVMe    | 5         | 6      | 9.09%   |
| Unknown | 3         | 3      | 5.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 46     | 70.37%  |
| MMC  | 7         | 7      | 12.96%  |
| NVMe | 5         | 6      | 9.26%   |
| SAS  | 4         | 4      | 7.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 41     | 85%     |
| 0.51-1.0   | 4         | 4      | 10%     |
| 1.01-2.0   | 1         | 1      | 2.5%    |
| 4.01-10.0  | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 10        | 20%     |
| 51-100         | 9         | 18%     |
| 101-250        | 8         | 16%     |
| 251-500        | 7         | 14%     |
| 21-50          | 7         | 14%     |
| 1001-2000      | 4         | 8%      |
| 501-1000       | 3         | 6%      |
| More than 3000 | 1         | 2%      |
| Unknown        | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 66%     |
| 21-50          | 7         | 14%     |
| 251-500        | 2         | 4%      |
| 101-250        | 2         | 4%      |
| 501-1000       | 2         | 4%      |
| 51-100         | 2         | 4%      |
| More than 3000 | 1         | 2%      |
| Unknown        | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD400BD-23JMC0 40GB       | 1         | 1      | 8.33%   |
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 8.33%   |
| WDC WD1600AAJS-75M0A0 160GB   | 1         | 1      | 8.33%   |
| Seagate ST9120822AS 120GB     | 1         | 1      | 8.33%   |
| Seagate ST3320820SCE 320GB    | 1         | 1      | 8.33%   |
| Maxtor 6Y080L0 81GB           | 1         | 1      | 8.33%   |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 8.33%   |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 8.33%   |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 8.33%   |
| HGST HTS725050A7E630 500GB    | 1         | 1      | 8.33%   |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 8.33%   |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 25%     |
| Hitachi | 3         | 3      | 25%     |
| Seagate | 2         | 2      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |
| Maxtor  | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 25%     |
| Hitachi | 3         | 3      | 25%     |
| Seagate | 2         | 2      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |
| Maxtor  | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 12     | 100%    |

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
| Works    | 31        | 39     | 58.49%  |
| Detected | 11        | 12     | 20.75%  |
| Malfunc  | 11        | 12     | 20.75%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 27        | 54%     |
| AMD                              | 11        | 22%     |
| Silicon Integrated Systems [SiS] | 4         | 8%      |
| VIA Technologies                 | 1         | 2%      |
| Silicon Motion                   | 1         | 2%      |
| SanDisk                          | 1         | 2%      |
| Phison Electronics               | 1         | 2%      |
| Nvidia                           | 1         | 2%      |
| Micron/Crucial Technology        | 1         | 2%      |
| ASMedia Technology               | 1         | 2%      |
| ADATA Technology                 | 1         | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 13.11%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 4         | 6.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 4.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 4.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 4.92%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 3.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 3.28%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 3.28%   |
| VIA VX900 Series Serial-ATA Controller                                           | 1         | 1.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.64%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.64%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 1.64%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.64%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.64%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.64%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.64%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.64%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.64%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.64%   |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 1.64%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.64%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.64%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.64%   |
| AMD 500 Series Chipset SATA Controller                                           | 1         | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.64%   |
| AMD 300 Series Chipset SATA Controller                                           | 1         | 1.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 1.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 52.94%  |
| IDE  | 18        | 35.29%  |
| NVMe | 4         | 7.84%   |
| RAID | 2         | 3.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 34        | 68%     |
| AMD          | 15        | 30%     |
| CentaurHauls | 1         | 2%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz                 | 3         | 6%      |
| Intel Pentium M processor 1.70GHz               | 2         | 4%      |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 4%      |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 4%      |
| Intel Pentium M processor 1000MHz               | 1         | 2%      |
| Intel Pentium III (Coppermine)                  | 1         | 2%      |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2%      |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1         | 2%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 2%      |
| Intel Pentium 4 CPU 3.00GHz                     | 1         | 2%      |
| Intel Pentium 4 CPU 2.00GHz                     | 1         | 2%      |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 2%      |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 2%      |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2%      |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1         | 2%      |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2%      |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2%      |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2%      |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2%      |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2%      |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2%      |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2%      |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2%      |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1         | 2%      |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2%      |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz       | 1         | 2%      |
| AMD V120 Processor                              | 1         | 2%      |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2%      |
| AMD Ryzen 7 3700X 8-Core Processor              | 1         | 2%      |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1         | 2%      |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 2%      |
| AMD Mobile Sempron Processor 3000+              | 1         | 2%      |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2%      |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2%      |
| AMD Athlon Processor                            | 1         | 2%      |
| AMD Athlon Neo Processor MV-40                  | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 6         | 12%     |
| Intel Atom              | 6         | 12%     |
| Intel Core 2 Duo        | 4         | 8%      |
| Intel Pentium M         | 3         | 6%      |
| Intel Pentium Dual-Core | 3         | 6%      |
| Intel Core i5           | 3         | 6%      |
| Intel Pentium 4         | 2         | 4%      |
| Intel Core i3           | 2         | 4%      |
| AMD Ryzen 7             | 2         | 4%      |
| AMD Athlon              | 2         | 4%      |
| AMD A4                  | 2         | 4%      |
| Other                   | 1         | 2%      |
| Intel Pentium III       | 1         | 2%      |
| Intel Core m3           | 1         | 2%      |
| Intel Core i7           | 1         | 2%      |
| Intel Core 2            | 1         | 2%      |
| CentaurHauls VIA Eden   | 1         | 2%      |
| AMD V120                | 1         | 2%      |
| AMD Ryzen 7 PRO         | 1         | 2%      |
| AMD Ryzen 5 PRO         | 1         | 2%      |
| AMD Mobile Sempron      | 1         | 2%      |
| AMD E                   | 1         | 2%      |
| AMD C-70                | 1         | 2%      |
| AMD Athlon Neo          | 1         | 2%      |
| AMD Athlon II X2        | 1         | 2%      |
| AMD A8                  | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 42%     |
| 4      | 14        | 28%     |
| 1      | 13        | 26%     |
| 8      | 2         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 68%     |
| 2      | 16        | 32%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 41        | 82%     |
| 32-bit         | 9         | 18%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 14%     |
| 0x1067a    | 5         | 10%     |
| 0x30678    | 4         | 8%      |
| 0x206a7    | 4         | 8%      |
| 0x706a1    | 2         | 4%      |
| 0x6fd      | 2         | 4%      |
| 0x0810100b | 2         | 4%      |
| 0x010000c8 | 2         | 4%      |
| 0xf49      | 1         | 2%      |
| 0xf27      | 1         | 2%      |
| 0x806c1    | 1         | 2%      |
| 0x706a8    | 1         | 2%      |
| 0x6f6      | 1         | 2%      |
| 0x6d8      | 1         | 2%      |
| 0x6d6      | 1         | 2%      |
| 0x695      | 1         | 2%      |
| 0x68a      | 1         | 2%      |
| 0x406e3    | 1         | 2%      |
| 0x406c4    | 1         | 2%      |
| 0x40651    | 1         | 2%      |
| 0x20655    | 1         | 2%      |
| 0x106c2    | 1         | 2%      |
| 0x08701013 | 1         | 2%      |
| 0x08108102 | 1         | 2%      |
| 0x0800820d | 1         | 2%      |
| 0x07030106 | 1         | 2%      |
| 0x06006705 | 1         | 2%      |
| 0x0600111f | 1         | 2%      |
| 0x05000119 | 1         | 2%      |
| 0x0500010d | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 6         | 12%     |
| Penryn        | 5         | 10%     |
| SandyBridge   | 4         | 8%      |
| P6            | 4         | 8%      |
| Goldmont plus | 3         | 6%      |
| Core          | 3         | 6%      |
| Zen+          | 2         | 4%      |
| Zen           | 2         | 4%      |
| NetBurst      | 2         | 4%      |
| K8 Hammer     | 2         | 4%      |
| K10           | 2         | 4%      |
| Bonnell       | 2         | 4%      |
| Bobcat        | 2         | 4%      |
| Zen 2         | 1         | 2%      |
| Westmere      | 1         | 2%      |
| TigerLake     | 1         | 2%      |
| Skylake       | 1         | 2%      |
| Puma          | 1         | 2%      |
| Piledriver    | 1         | 2%      |
| K6            | 1         | 2%      |
| Haswell       | 1         | 2%      |
| Goldmont      | 1         | 2%      |
| Excavator     | 1         | 2%      |
| Unknown       | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 25        | 49.02%  |
| AMD                              | 14        | 27.45%  |
| Nvidia                           | 6         | 11.76%  |
| Silicon Integrated Systems [SiS] | 4         | 7.84%   |
| VIA Technologies                 | 1         | 1.96%   |
| S3 Graphics                      | 1         | 1.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 7.69%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 5.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 5.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 5.77%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 3.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 2         | 3.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 3.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 3.85%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1         | 1.92%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.92%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 1.92%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 1.92%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1         | 1.92%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.92%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.92%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 1.92%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 1.92%   |
| Intel HD Graphics 515                                                                      | 1         | 1.92%   |
| Intel HD Graphics 500                                                                      | 1         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 1.92%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.92%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 1.92%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 1.92%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 1.92%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                            | 1         | 1.92%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 1.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 1.92%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 1         | 1.92%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 1.92%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 1         | 1.92%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 1.92%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 1.92%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 23        | 46%     |
| 1 x AMD         | 13        | 26%     |
| 1 x Nvidia      | 6         | 12%     |
| 1 x SiS         | 4         | 8%      |
| Other           | 1         | 2%      |
| 1 x VIA         | 1         | 2%      |
| 1 x S3 Graphics | 1         | 2%      |
| Intel + AMD     | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 82%     |
| Unknown     | 6         | 12%     |
| Proprietary | 3         | 6%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 58%     |
| 0.01-0.5   | 13        | 26%     |
| 1.01-2.0   | 5         | 10%     |
| 0.51-1.0   | 2         | 4%      |
| 3.01-4.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 19.05%  |
| Chimei Innolux      | 7         | 16.67%  |
| AU Optronics        | 7         | 16.67%  |
| Philips             | 3         | 7.14%   |
| LG Display          | 3         | 7.14%   |
| Hewlett-Packard     | 2         | 4.76%   |
| Dell                | 2         | 4.76%   |
| ViewSonic           | 1         | 2.38%   |
| VIE                 | 1         | 2.38%   |
| Orion               | 1         | 2.38%   |
| Iiyama              | 1         | 2.38%   |
| HannStar            | 1         | 2.38%   |
| Goldstar            | 1         | 2.38%   |
| CPT                 | 1         | 2.38%   |
| BOE                 | 1         | 2.38%   |
| AOC                 | 1         | 2.38%   |
| Acer                | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3         | 7.14%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 4.76%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 4.76%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 2.38%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 2.38%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 2.38%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 2.38%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch    | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch    | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch    | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 2.38%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 2.38%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 2.38%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1         | 2.38%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 2.38%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1         | 2.38%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 2.38%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 2.38%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 2.38%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1         | 2.38%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 2.38%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch         | 1         | 2.38%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch          | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO139E 1600x900 380x210mm 17.1-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch           | 1         | 2.38%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                        | 1         | 2.38%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                      | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 35.71%  |
| 1366x768 (WXGA)    | 12        | 28.57%  |
| 1600x900 (HD+)     | 5         | 11.9%   |
| 1280x800 (WXGA)    | 3         | 7.14%   |
| 1920x1200 (WUXGA)  | 2         | 4.76%   |
| 3840x2160 (4K)     | 1         | 2.38%   |
| 2160x1440          | 1         | 2.38%   |
| 1920x540           | 1         | 2.38%   |
| 1680x1050 (WSXGA+) | 1         | 2.38%   |
| 1280x1024 (SXGA)   | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 35.71%  |
| 24      | 6         | 14.29%  |
| 13      | 3         | 7.14%   |
| 23      | 2         | 4.76%   |
| 17      | 2         | 4.76%   |
| 12      | 2         | 4.76%   |
| 11      | 2         | 4.76%   |
| 46      | 1         | 2.38%   |
| 40      | 1         | 2.38%   |
| 31      | 1         | 2.38%   |
| 22      | 1         | 2.38%   |
| 21      | 1         | 2.38%   |
| 20      | 1         | 2.38%   |
| 19      | 1         | 2.38%   |
| 18      | 1         | 2.38%   |
| 14      | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 42.86%  |
| 501-600     | 8         | 19.05%  |
| 201-300     | 5         | 11.9%   |
| 401-500     | 4         | 9.52%   |
| 351-400     | 3         | 7.14%   |
| 801-900     | 1         | 2.38%   |
| 601-700     | 1         | 2.38%   |
| 1001-1500   | 1         | 2.38%   |
| Unknown     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 74.36%  |
| 16/10 | 7         | 17.95%  |
| 5/4   | 1         | 2.56%   |
| 32/9  | 1         | 2.56%   |
| 3/2   | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 35.71%  |
| 201-250        | 7         | 16.67%  |
| 81-90          | 4         | 9.52%   |
| 251-300        | 3         | 7.14%   |
| 61-70          | 2         | 4.76%   |
| 51-60          | 2         | 4.76%   |
| 151-200        | 2         | 4.76%   |
| 141-150        | 2         | 4.76%   |
| 501-1000       | 2         | 4.76%   |
| 351-500        | 1         | 2.38%   |
| 121-130        | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 17        | 40.48%  |
| 101-120 | 14        | 33.33%  |
| 121-160 | 6         | 14.29%  |
| 161-240 | 3         | 7.14%   |
| 1-50    | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 88%     |
| 0     | 3         | 6%      |
| 2     | 2         | 4%      |
| 3     | 1         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 36        | 46.15%  |
| Intel                            | 13        | 16.67%  |
| Qualcomm Atheros                 | 12        | 15.38%  |
| Silicon Integrated Systems [SiS] | 3         | 3.85%   |
| Samsung Electronics              | 2         | 2.56%   |
| Broadcom Limited                 | 2         | 2.56%   |
| Broadcom                         | 2         | 2.56%   |
| Xiaomi                           | 1         | 1.28%   |
| Motorola PCS                     | 1         | 1.28%   |
| Marvell Technology Group         | 1         | 1.28%   |
| LG Electronics                   | 1         | 1.28%   |
| JMicron Technology               | 1         | 1.28%   |
| IBM                              | 1         | 1.28%   |
| Guillemot                        | 1         | 1.28%   |
| Accton Technology                | 1         | 1.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 15        | 17.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 11.49%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 3.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 3.45%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.45%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 3.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 2.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 2.3%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 2.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.15%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 1.15%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.15%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 1.15%   |
| Motorola PCS motorola one 5G ace                                        | 1         | 1.15%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 1.15%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 1.15%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.15%   |
| Intel Wireless 7265                                                     | 1         | 1.15%   |
| Intel Wireless 3165                                                     | 1         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.15%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 1.15%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                      | 1         | 1.15%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 12        | 34.29%  |
| Intel                 | 11        | 31.43%  |
| Realtek Semiconductor | 9         | 25.71%  |
| Guillemot             | 1         | 2.86%   |
| Broadcom Limited      | 1         | 2.86%   |
| Broadcom              | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 8.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 8.57%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 8.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 8.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 5.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 5.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 5.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 2.86%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 2.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 1         | 2.86%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 2.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 2.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 2.86%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 2.86%   |
| Intel Wireless 7265                                                         | 1         | 2.86%   |
| Intel Wireless 3165                                                         | 1         | 2.86%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 2.86%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS]   | 1         | 2.86%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 31        | 65.96%  |
| Intel                            | 3         | 6.38%   |
| Silicon Integrated Systems [SiS] | 2         | 4.26%   |
| Samsung Electronics              | 2         | 4.26%   |
| Xiaomi                           | 1         | 2.13%   |
| Qualcomm Atheros                 | 1         | 2.13%   |
| Motorola PCS                     | 1         | 2.13%   |
| Marvell Technology Group         | 1         | 2.13%   |
| LG Electronics                   | 1         | 2.13%   |
| JMicron Technology               | 1         | 2.13%   |
| Broadcom Limited                 | 1         | 2.13%   |
| Broadcom                         | 1         | 2.13%   |
| Accton Technology                | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 31.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 21.28%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 6.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 4.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 4.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.13%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 2.13%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.13%   |
| Motorola PCS motorola one 5G ace                                  | 1         | 2.13%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.13%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.13%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.13%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 2.13%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.13%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 2.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.13%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.13%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 52.94%  |
| WiFi     | 35        | 41.18%  |
| Modem    | 4         | 4.71%   |
| Unknown  | 1         | 1.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 53.19%  |
| Ethernet | 22        | 46.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 25        | 50%     |
| 1     | 19        | 38%     |
| 0     | 4         | 8%      |
| 3     | 2         | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 90%     |
| Yes  | 5         | 10%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./images/pie_chart/bt_model.svg)


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

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 53.06%  |
| AMD                              | 14        | 28.57%  |
| Nvidia                           | 4         | 8.16%   |
| Silicon Integrated Systems [SiS] | 3         | 6.12%   |
| VIA Technologies                 | 1         | 2.04%   |
| ESS Technology                   | 1         | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 6.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 4.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 4.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 4.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 4.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 4.92%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.92%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 3.28%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 3.28%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 3.28%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 3.28%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 3.28%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 1.64%   |
| VIA Technologies High Definition Audio Controller                                                 | 1         | 1.64%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.64%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.64%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.64%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.64%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.64%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.64%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.64%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.64%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.64%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.64%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 1.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 20        | 38.46%  |
| Samsung Electronics | 8         | 15.38%  |
| SK hynix            | 6         | 11.54%  |
| Kingston            | 4         | 7.69%   |
| Unknown (ABCD)      | 2         | 3.85%   |
| A-DATA Technology   | 2         | 3.85%   |
| Transcend           | 1         | 1.92%   |
| Toshiba             | 1         | 1.92%   |
| Teikon              | 1         | 1.92%   |
| Team                | 1         | 1.92%   |
| S                   | 1         | 1.92%   |
| Micron Technology   | 1         | 1.92%   |
| M                   | 1         | 1.92%   |
| Elpida              | 1         | 1.92%   |
| Crucial             | 1         | 1.92%   |
| Unknown             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 7.27%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 3.64%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 3.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.64%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.82%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 1.82%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 1.82%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.82%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1         | 1.82%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.82%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.82%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 1.82%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.82%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.82%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.82%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 1.82%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.82%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.82%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s             | 1         | 1.82%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 1.82%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.82%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.82%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s          | 1         | 1.82%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 1.82%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.82%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 975MT/s         | 1         | 1.82%   |
| S RAM Module 2GB DIMM DDR3 1333MT/s                              | 1         | 1.82%   |
| Micron RAM MT52L256M32D1PF-10 2GB LPDDR3 1867MT/s                | 1         | 1.82%   |
| M RAM Module 1GB DIMM DDR3 1333MT/s                              | 1         | 1.82%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 17        | 34.69%  |
| DDR4    | 9         | 18.37%  |
| SDRAM   | 8         | 16.33%  |
| DDR2    | 6         | 12.24%  |
| DDR     | 3         | 6.12%   |
| LPDDR4  | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| LPDDR3  | 1         | 2.04%   |
| DRAM    | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 33        | 67.35%  |
| DIMM    | 15        | 30.61%  |
| Unknown | 1         | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 17        | 32.69%  |
| 4096  | 13        | 25%     |
| 1024  | 9         | 17.31%  |
| 8192  | 6         | 11.54%  |
| 512   | 3         | 5.77%   |
| 16384 | 2         | 3.85%   |
| 32768 | 1         | 1.92%   |
| 256   | 1         | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 11        | 21.57%  |
| 1600    | 6         | 11.76%  |
| 1333    | 6         | 11.76%  |
| 2667    | 4         | 7.84%   |
| 2400    | 4         | 7.84%   |
| 1334    | 4         | 7.84%   |
| 1067    | 2         | 3.92%   |
| 1066    | 2         | 3.92%   |
| 800     | 2         | 3.92%   |
| 266     | 2         | 3.92%   |
| 4199    | 1         | 1.96%   |
| 3600    | 1         | 1.96%   |
| 3266    | 1         | 1.96%   |
| 3200    | 1         | 1.96%   |
| 2666    | 1         | 1.96%   |
| 2048    | 1         | 1.96%   |
| 1867    | 1         | 1.96%   |
| 400     | 1         | 1.96%   |

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

![Camera Model](./images/pie_chart/camera_model.svg)


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
| Alcor Micro USB Camera                                      | 1         | 5.26%   |
| Acer HP Webcam-101                                          | 1         | 5.26%   |
| Acer EasyCamera                                             | 1         | 5.26%   |

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
| 0     | 39        | 78%     |
| 1     | 7         | 14%     |
| 2     | 4         | 8%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 8         | 53.33%  |
| Fingerprint reader       | 3         | 20%     |
| Network                  | 1         | 6.67%   |
| Flash memory             | 1         | 6.67%   |
| Communication controller | 1         | 6.67%   |
| Camera                   | 1         | 6.67%   |

