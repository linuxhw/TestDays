Q4OS - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Q4OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 57

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Framework     | Laptop 13 (AMD Ryzen 704... | [f526bc07cf](https://linux-hardware.org/?probe=f526bc07cf) | Nov 25, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7b53c24f1e](https://linux-hardware.org/?probe=7b53c24f1e) | Nov 25, 2023 |
| Dell          | Latitude E6430              | [ac45698de6](https://linux-hardware.org/?probe=ac45698de6) | Nov 13, 2023 |
| Apple         | MacBook4,1                  | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Acer          | Aspire one                  | [d040844540](https://linux-hardware.org/?probe=d040844540) | Sep 27, 2023 |
| Acer          | Aspire 1700                 | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| MSI           | U90/U100                    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [8424587178](https://linux-hardware.org/?probe=8424587178) | Jul 27, 2023 |
| ASUSTek       | K53SJ                       | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| Dell          | Latitude D630               | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| Sony          | VGN-FW21Z                   | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Google        | Reks                        | [be1a98408d](https://linux-hardware.org/?probe=be1a98408d) | Feb 28, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| IBM           | ThinkPad T42 2378FVU        | [ce2f3fb897](https://linux-hardware.org/?probe=ce2f3fb897) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU        | [50f1d0a765](https://linux-hardware.org/?probe=50f1d0a765) | Dec 19, 2022 |
| IBM           | ThinkPad T42 2378FVU        | [fe6bdea3fd](https://linux-hardware.org/?probe=fe6bdea3fd) | Dec 19, 2022 |
| Google        | Cave                        | [ce7f60e0ee](https://linux-hardware.org/?probe=ce7f60e0ee) | Nov 06, 2022 |
| Google        | Cave                        | [63e06049da](https://linux-hardware.org/?probe=63e06049da) | Nov 06, 2022 |
| Medion        | P6620                       | [e5db2a930b](https://linux-hardware.org/?probe=e5db2a930b) | Aug 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q                  | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70               | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC          | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASUSTek       | A6U                         | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500          | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                      | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                       | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                      | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10                  | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56               | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56               | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| MSI           | U210                        | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                       | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660              | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Phoenix/Si... | M720SR                      | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx           | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro                | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| HP            | ProBook 450 G2              | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                         | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| HP            | ProBook 6550b               | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                        | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASUSTek       | A6JC                        | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                        | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00     | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81               | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP                 | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC                 | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                     | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                         | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Q4OS 4 | 27        | 57.45%  |
| Q4OS 3 | 11        | 23.4%   |
| Q4OS 5 | 6         | 12.77%  |
| Q4OS 2 | 3         | 6.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 47        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-23-amd64      | 4         | 8.51%   |
| 4.19.0-17-amd64      | 4         | 8.51%   |
| 5.10.0-21-amd64      | 3         | 6.38%   |
| 5.10.0-12-amd64      | 3         | 6.38%   |
| 5.10.0-8-amd64       | 2         | 4.26%   |
| 5.10.0-14-686-pae    | 2         | 4.26%   |
| 6.5.0-4-amd64        | 1         | 2.13%   |
| 6.1.0-13-amd64       | 1         | 2.13%   |
| 6.1.0-12-amd64       | 1         | 2.13%   |
| 6.1.0-12-686-pae     | 1         | 2.13%   |
| 6.1.0-11-686-pae     | 1         | 2.13%   |
| 6.1.0-10-686-pae     | 1         | 2.13%   |
| 5.9.0-5-amd64        | 1         | 2.13%   |
| 5.6.0-1-amd64        | 1         | 2.13%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 2.13%   |
| 5.10.0-9-amd64       | 1         | 2.13%   |
| 5.10.0-8-686-pae     | 1         | 2.13%   |
| 5.10.0-21-686-pae    | 1         | 2.13%   |
| 5.10.0-20-686        | 1         | 2.13%   |
| 5.10.0-17-amd64      | 1         | 2.13%   |
| 5.10.0-15-686-pae    | 1         | 2.13%   |
| 5.10.0-13-amd64      | 1         | 2.13%   |
| 5.10.0-12-686-pae    | 1         | 2.13%   |
| 5.10.0-11-686-pae    | 1         | 2.13%   |
| 5.10.0-10-686-pae    | 1         | 2.13%   |
| 4.9.0-8-amd64        | 1         | 2.13%   |
| 4.9.0-14-686-pae     | 1         | 2.13%   |
| 4.9.0-12-686-pae     | 1         | 2.13%   |
| 4.19.0-22-amd64      | 1         | 2.13%   |
| 4.19.0-20-amd64      | 1         | 2.13%   |
| 4.19.0-17-686        | 1         | 2.13%   |
| 4.19.0-14-amd64      | 1         | 2.13%   |
| 4.19.0-13-amd64      | 1         | 2.13%   |
| 4.19.0-12-amd64      | 1         | 2.13%   |
| 4.19.0-10-amd64      | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 24        | 51.06%  |
| 4.19.0  | 11        | 23.4%   |
| 6.1.0   | 5         | 10.64%  |
| 4.9.0   | 3         | 6.38%   |
| 6.5.0   | 1         | 2.13%   |
| 5.9.0   | 1         | 2.13%   |
| 5.6.0   | 1         | 2.13%   |
| 5.18.0  | 1         | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 24        | 51.06%  |
| 4.19    | 11        | 23.4%   |
| 6.1     | 5         | 10.64%  |
| 4.9     | 3         | 6.38%   |
| 6.5     | 1         | 2.13%   |
| 5.9     | 1         | 2.13%   |
| 5.6     | 1         | 2.13%   |
| 5.18    | 1         | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 68.09%  |
| i686   | 15        | 31.91%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 25        | 53.19%  |
| trinity  | 20        | 42.55%  |
| KDE      | 1         | 2.13%   |
| Cinnamon | 1         | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 46        | 97.87%  |
| Tty  | 1         | 2.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 27        | 57.45%  |
| TDM  | 20        | 42.55%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 21        | 44.68%  |
| en_GB   | 5         | 10.64%  |
| de_DE   | 4         | 8.51%   |
| it_IT   | 3         | 6.38%   |
| es_ES   | 3         | 6.38%   |
| hu_HU   | 2         | 4.26%   |
| sv_SE   | 1         | 2.13%   |
| sl_SI   | 1         | 2.13%   |
| ru_RU   | 1         | 2.13%   |
| pl_PL   | 1         | 2.13%   |
| fr_FR   | 1         | 2.13%   |
| es_VE   | 1         | 2.13%   |
| en_SG   | 1         | 2.13%   |
| C       | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 30        | 63.83%  |
| EFI  | 17        | 36.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 44        | 93.62%  |
| Overlay | 3         | 6.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 30        | 63.83%  |
| GPT     | 16        | 34.04%  |
| Unknown | 1         | 2.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 89.36%  |
| Yes       | 5         | 10.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 70.21%  |
| Yes       | 14        | 29.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 8         | 17.02%  |
| Lenovo           | 5         | 10.64%  |
| ASUSTek Computer | 5         | 10.64%  |
| Toshiba          | 4         | 8.51%   |
| Acer             | 3         | 6.38%   |
| Sony             | 2         | 4.26%   |
| MSI              | 2         | 4.26%   |
| Medion           | 2         | 4.26%   |
| Google           | 2         | 4.26%   |
| Dell             | 2         | 4.26%   |
| Visual Land      | 1         | 2.13%   |
| Qilive           | 1         | 2.13%   |
| Phoenix/SiS      | 1         | 2.13%   |
| Philco           | 1         | 2.13%   |
| Packard Bell     | 1         | 2.13%   |
| JVC              | 1         | 2.13%   |
| IBM              | 1         | 2.13%   |
| Fujitsu Siemens  | 1         | 2.13%   |
| Framework        | 1         | 2.13%   |
| Chuwi            | 1         | 2.13%   |
| Apple            | 1         | 2.13%   |
| AMI              | 1         | 2.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C660                     | 2         | 4.26%   |
| Visual Land Premier 10                     | 1         | 2.13%   |
| Toshiba Satellite Pro L500                 | 1         | 2.13%   |
| Toshiba Satellite M70                      | 1         | 2.13%   |
| Sony VGN-P11Z_Q                            | 1         | 2.13%   |
| Sony VGN-FW21Z                             | 1         | 2.13%   |
| Qilive QW19141AMSP                         | 1         | 2.13%   |
| Phoenix/SiS M720SR                         | 1         | 2.13%   |
| Philco 14I                                 | 1         | 2.13%   |
| Packard Bell EasyNote LM81                 | 1         | 2.13%   |
| MSI U90/U100                               | 1         | 2.13%   |
| MSI U210                                   | 1         | 2.13%   |
| Medion P6620                               | 1         | 2.13%   |
| Lenovo ThinkPad T495 20NKS0PG00            | 1         | 2.13%   |
| Lenovo ThinkPad 11e 20DAS0PS00             | 1         | 2.13%   |
| Lenovo IdeaPad 5 14IAL7 82SD               | 1         | 2.13%   |
| Lenovo IdeaPad 330S-14IKB 81F4             | 1         | 2.13%   |
| Lenovo IdeaPad 330-15IGM 81D1              | 1         | 2.13%   |
| JVC J3N                                    | 1         | 2.13%   |
| IBM ThinkPad T42 2378FVU                   | 1         | 2.13%   |
| HP ProBook 6550b                           | 1         | 2.13%   |
| HP ProBook 650 G1                          | 1         | 2.13%   |
| HP ProBook 450 G2                          | 1         | 2.13%   |
| HP Presario CQ56                           | 1         | 2.13%   |
| HP OmniBook PC                             | 1         | 2.13%   |
| HP Laptop 15s-fq2xxx                       | 1         | 2.13%   |
| HP 250 G5 Notebook PC                      | 1         | 2.13%   |
| HP 2000                                    | 1         | 2.13%   |
| Google Reks                                | 1         | 2.13%   |
| Google Cave                                | 1         | 2.13%   |
| Fujitsu Siemens AMILO Pro Edition V3505    | 1         | 2.13%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 1         | 2.13%   |
| Dell Latitude E6430                        | 1         | 2.13%   |
| Dell Latitude D630                         | 1         | 2.13%   |
| Chuwi GemiBook Pro                         | 1         | 2.13%   |
| ASUS X540YA                                | 1         | 2.13%   |
| ASUS T12Eg                                 | 1         | 2.13%   |
| ASUS K53SJ                                 | 1         | 2.13%   |
| ASUS A6U                                   | 1         | 2.13%   |
| ASUS A6JC                                  | 1         | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toshiba Satellite     | 4         | 8.51%   |
| Lenovo IdeaPad        | 3         | 6.38%   |
| HP ProBook            | 3         | 6.38%   |
| Lenovo ThinkPad       | 2         | 4.26%   |
| Dell Latitude         | 2         | 4.26%   |
| Acer Aspire           | 2         | 4.26%   |
| Visual Land Premier   | 1         | 2.13%   |
| Sony VGN-P11Z         | 1         | 2.13%   |
| Sony VGN-FW21Z        | 1         | 2.13%   |
| Qilive QW19141AMSP    | 1         | 2.13%   |
| Phoenix/SiS M720SR    | 1         | 2.13%   |
| Philco 14I            | 1         | 2.13%   |
| Packard Bell EasyNote | 1         | 2.13%   |
| MSI U90               | 1         | 2.13%   |
| MSI U210              | 1         | 2.13%   |
| Medion P6620          | 1         | 2.13%   |
| JVC J3N               | 1         | 2.13%   |
| IBM ThinkPad          | 1         | 2.13%   |
| HP Presario           | 1         | 2.13%   |
| HP OmniBook           | 1         | 2.13%   |
| HP Laptop             | 1         | 2.13%   |
| HP 250                | 1         | 2.13%   |
| HP 2000               | 1         | 2.13%   |
| Google Reks           | 1         | 2.13%   |
| Google Cave           | 1         | 2.13%   |
| Fujitsu Siemens AMILO | 1         | 2.13%   |
| Framework Laptop      | 1         | 2.13%   |
| Chuwi GemiBook        | 1         | 2.13%   |
| ASUS X540YA           | 1         | 2.13%   |
| ASUS T12Eg            | 1         | 2.13%   |
| ASUS K53SJ            | 1         | 2.13%   |
| ASUS A6U              | 1         | 2.13%   |
| ASUS A6JC             | 1         | 2.13%   |
| Apple MacBook4        | 1         | 2.13%   |
| AMI Intel             | 1         | 2.13%   |
| Acer AO751h           | 1         | 2.13%   |
| Unknown               | 1         | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 6         | 12.77%  |
| 2010    | 5         | 10.64%  |
| 2020    | 3         | 6.38%   |
| 2008    | 3         | 6.38%   |
| 2023    | 2         | 4.26%   |
| 2022    | 2         | 4.26%   |
| 2019    | 2         | 4.26%   |
| 2018    | 2         | 4.26%   |
| 2016    | 2         | 4.26%   |
| 2014    | 2         | 4.26%   |
| 2012    | 2         | 4.26%   |
| 2011    | 2         | 4.26%   |
| 2007    | 2         | 4.26%   |
| 2006    | 2         | 4.26%   |
| 2005    | 2         | 4.26%   |
| 2004    | 2         | 4.26%   |
| Unknown | 2         | 4.26%   |
| 2017    | 1         | 2.13%   |
| 2015    | 1         | 2.13%   |
| 2013    | 1         | 2.13%   |
| 2003    | 1         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 47        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 44        | 93.62%  |
| Enabled  | 3         | 6.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 95.74%  |
| Yes  | 2         | 4.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 16        | 34.04%  |
| 4.01-8.0   | 8         | 17.02%  |
| 2.01-3.0   | 8         | 17.02%  |
| 1.01-2.0   | 6         | 12.77%  |
| 0.51-1.0   | 3         | 6.38%   |
| 8.01-16.0  | 2         | 4.26%   |
| 0.01-0.5   | 2         | 4.26%   |
| 24.01-32.0 | 1         | 2.13%   |
| 16.01-24.0 | 1         | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 21        | 44.68%  |
| 0.51-1.0 | 10        | 21.28%  |
| 2.01-3.0 | 8         | 17.02%  |
| 0.01-0.5 | 5         | 10.64%  |
| 3.01-4.0 | 2         | 4.26%   |
| 4.01-8.0 | 1         | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 78.72%  |
| 2      | 9         | 19.15%  |
| 3      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 55.32%  |
| No        | 21        | 44.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 80.85%  |
| No        | 9         | 19.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 93.62%  |
| No        | 3         | 6.38%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 53.19%  |
| Yes       | 22        | 46.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 8         | 17.02%  |
| UK           | 5         | 10.64%  |
| Italy        | 4         | 8.51%   |
| Germany      | 4         | 8.51%   |
| Spain        | 3         | 6.38%   |
| Kenya        | 3         | 6.38%   |
| Romania      | 2         | 4.26%   |
| Poland       | 2         | 4.26%   |
| Hungary      | 2         | 4.26%   |
| Venezuela    | 1         | 2.13%   |
| Turkey       | 1         | 2.13%   |
| Sweden       | 1         | 2.13%   |
| Slovenia     | 1         | 2.13%   |
| Singapore    | 1         | 2.13%   |
| Saudi Arabia | 1         | 2.13%   |
| Russia       | 1         | 2.13%   |
| Qatar        | 1         | 2.13%   |
| Mexico       | 1         | 2.13%   |
| France       | 1         | 2.13%   |
| Croatia      | 1         | 2.13%   |
| Canada       | 1         | 2.13%   |
| Brazil       | 1         | 2.13%   |
| Belarus      | 1         | 2.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 6.38%   |
| Swindon               | 2         | 4.26%   |
| Mesa                  | 2         | 4.26%   |
| Drobeta-Turnu Severin | 2         | 4.26%   |
| Budapest              | 2         | 4.26%   |
| West Corinth          | 1         | 2.13%   |
| Tenbury Wells         | 1         | 2.13%   |
| Tellico Plains        | 1         | 2.13%   |
| Sosnowiec             | 1         | 2.13%   |
| Singapore             | 1         | 2.13%   |
| Schermbeck            | 1         | 2.13%   |
| Salsomaggiore Terme   | 1         | 2.13%   |
| Rostock               | 1         | 2.13%   |
| Rijeka                | 1         | 2.13%   |
| Puerto Cumarebo       | 1         | 2.13%   |
| Moscow                | 1         | 2.13%   |
| Morelia               | 1         | 2.13%   |
| Mooresville           | 1         | 2.13%   |
| Moirans               | 1         | 2.13%   |
| Mogilev               | 1         | 2.13%   |
| Milano                | 1         | 2.13%   |
| Mannheim              | 1         | 2.13%   |
| Londrina              | 1         | 2.13%   |
| Ljubljana             | 1         | 2.13%   |
| Little Current        | 1         | 2.13%   |
| Leipzig               | 1         | 2.13%   |
| Las Vegas             | 1         | 2.13%   |
| Klaudyn               | 1         | 2.13%   |
| Jönköping           | 1         | 2.13%   |
| Jacksonville          | 1         | 2.13%   |
| Indianapolis          | 1         | 2.13%   |
| Giussano              | 1         | 2.13%   |
| Gijón                | 1         | 2.13%   |
| Fulham                | 1         | 2.13%   |
| Doha                  | 1         | 2.13%   |
| Dammam                | 1         | 2.13%   |
| Carterton             | 1         | 2.13%   |
| Calvecchia            | 1         | 2.13%   |
| Barcelona             | 1         | 2.13%   |
| Alicante              | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 13.73%  |
| Unknown             | 6         | 6      | 11.76%  |
| Seagate             | 5         | 5      | 9.8%    |
| Samsung Electronics | 5         | 5      | 9.8%    |
| Kingston            | 5         | 5      | 9.8%    |
| Toshiba             | 3         | 3      | 5.88%   |
| SanDisk             | 3         | 3      | 5.88%   |
| Hitachi             | 3         | 3      | 5.88%   |
| KESU                | 2         | 2      | 3.92%   |
| HGST                | 2         | 2      | 3.92%   |
| Fujitsu             | 2         | 2      | 3.92%   |
| China               | 2         | 2      | 3.92%   |
| Silicon Motion      | 1         | 1      | 1.96%   |
| Phison              | 1         | 1      | 1.96%   |
| KingSpec            | 1         | 1      | 1.96%   |
| KBG40ZNV            | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |
| Unknown             | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 2         | 3.92%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 3.92%   |
| KESU USB 3.1 256GB                   | 2         | 3.92%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.96%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.96%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.96%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1.96%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.96%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.96%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.96%   |
| Unknown USDU1  32GB                  | 1         | 1.96%   |
| Unknown SLD64G  64GB                 | 1         | 1.96%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 1.96%   |
| Unknown MMC Card  64GB               | 1         | 1.96%   |
| Unknown HAG2e  16GB                  | 1         | 1.96%   |
| Unknown 064G38  64GB                 | 1         | 1.96%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.96%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.96%   |
| Toshiba MK3252GSX 320GB              | 1         | 1.96%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.96%   |
| Seagate ST96812AS 64GB               | 1         | 1.96%   |
| Seagate ST9500325AS 500GB            | 1         | 1.96%   |
| Seagate ST9120822AS 120GB            | 1         | 1.96%   |
| Seagate ST380012A 80GB               | 1         | 1.96%   |
| Seagate Backup+ SL 1TB               | 1         | 1.96%   |
| SanDisk SDCFX-032G SSD               | 1         | 1.96%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 1.96%   |
| SanDisk NVMe SSD Drive 250GB         | 1         | 1.96%   |
| Samsung MZALQ256HBJD-00BL1 256GB     | 1         | 1.96%   |
| Samsung MZAL4512HBLU-00BL2 512GB     | 1         | 1.96%   |
| Samsung AWMB3R  16GB                 | 1         | 1.96%   |
| Phison APS-SE20G-1T                  | 1         | 1.96%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1.96%   |
| Kingston SV300S37A240G 240GB SSD     | 1         | 1.96%   |
| Kingston SUV400S37120G 120GB SSD     | 1         | 1.96%   |
| KingSpec KSD-PA25.6-064MS 64GB SSD   | 1         | 1.96%   |
| KBG40ZNV 256G KIOXIA                 | 1         | 1.96%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 1.96%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1.96%   |
| Hitachi DK23CA-20 20GB               | 1         | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 6      | 28.57%  |
| Seagate | 4         | 4      | 19.05%  |
| Toshiba | 3         | 3      | 14.29%  |
| Hitachi | 3         | 3      | 14.29%  |
| HGST    | 2         | 2      | 9.52%   |
| Fujitsu | 2         | 2      | 9.52%   |
| Unknown | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 35.71%  |
| SanDisk             | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| China               | 2         | 2      | 14.29%  |
| KingSpec            | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |
| Unknown             | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 20        | 21     | 41.67%  |
| SSD     | 14        | 14     | 29.17%  |
| MMC     | 6         | 6      | 12.5%   |
| NVMe    | 5         | 7      | 10.42%  |
| Unknown | 3         | 3      | 6.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 34     | 68%     |
| MMC  | 6         | 6      | 12%     |
| SAS  | 5         | 5      | 10%     |
| NVMe | 5         | 6      | 10%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 33     | 94.12%  |
| 0.51-1.0   | 2         | 2      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 25.53%  |
| 51-100     | 10        | 21.28%  |
| 251-500    | 8         | 17.02%  |
| 1-20       | 7         | 14.89%  |
| 21-50      | 5         | 10.64%  |
| 1001-2000  | 2         | 4.26%   |
| 501-1000   | 2         | 4.26%   |
| Unknown    | 1         | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 34        | 72.34%  |
| 21-50    | 7         | 14.89%  |
| 251-500  | 2         | 4.26%   |
| 51-100   | 2         | 4.26%   |
| 501-1000 | 1         | 2.13%   |
| Unknown  | 1         | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 9.09%   |
| Toshiba MK3252GSX 320GB       | 1         | 1      | 9.09%   |
| Seagate ST9500325AS 500GB     | 1         | 1      | 9.09%   |
| Seagate ST9120822AS 120GB     | 1         | 1      | 9.09%   |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 9.09%   |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 9.09%   |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB    | 1         | 1      | 9.09%   |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 9.09%   |
| Fujitsu MHZ2160BH G2 160GB    | 1         | 1      | 9.09%   |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 27.27%  |
| Seagate | 2         | 2      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |
| Fujitsu | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |
| Toshiba | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 27.27%  |
| Seagate | 2         | 2      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |
| Fujitsu | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |
| Toshiba | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 26        | 28     | 54.17%  |
| Detected | 11        | 12     | 22.92%  |
| Malfunc  | 11        | 11     | 22.92%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 31        | 67.39%  |
| AMD                              | 6         | 13.04%  |
| Silicon Integrated Systems [SiS] | 3         | 6.52%   |
| SanDisk                          | 2         | 4.35%   |
| Samsung Electronics              | 2         | 4.35%   |
| Silicon Motion                   | 1         | 2.17%   |
| Phison Electronics               | 1         | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 7.41%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 5.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 5.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 5.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 5.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 5.56%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 5.56%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 3.7%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 3.7%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.85%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.85%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.85%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.85%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 1.85%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.85%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.85%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 1.85%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.85%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 27        | 54%     |
| IDE  | 16        | 32%     |
| NVMe | 5         | 10%     |
| RAID | 2         | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 80.85%  |
| AMD    | 9         | 19.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz               | 2         | 4.26%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 4.26%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 4.26%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 4.26%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 2         | 4.26%   |
| Intel Pentium M processor 1000MHz               | 1         | 2.13%   |
| Intel Pentium III (Coppermine)                  | 1         | 2.13%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2.13%   |
| Intel Pentium CPU 4415U @ 2.30GHz               | 1         | 2.13%   |
| Intel Pentium 4 CPU 2.66GHz                     | 1         | 2.13%   |
| Intel Genuine CPU T2050 @ 1.60GHz               | 1         | 2.13%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 2.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.13%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 2.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 1         | 2.13%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2.13%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 2.13%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 2.13%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 2.13%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 2.13%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.13%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2.13%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2.13%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.13%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.13%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.13%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.13%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2.13%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2.13%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.13%   |
| Intel Atom CPU Z3735G @ 1.33GHz                 | 1         | 2.13%   |
| Intel 12th Gen Core i5-1240P                    | 1         | 2.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.13%   |
| AMD V120 Processor                              | 1         | 2.13%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.13%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics       | 1         | 2.13%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 2.13%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.13%   |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2.13%   |
| AMD Athlon Neo Processor MV-40                  | 1         | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 7         | 14.89%  |
| Intel Celeron           | 6         | 12.77%  |
| Intel Atom              | 6         | 12.77%  |
| Intel Core i5           | 4         | 8.51%   |
| Intel Pentium M         | 3         | 6.38%   |
| Intel Core i3           | 3         | 6.38%   |
| Other                   | 2         | 4.26%   |
| Intel Pentium III       | 1         | 2.13%   |
| Intel Pentium Dual-Core | 1         | 2.13%   |
| Intel Pentium 4         | 1         | 2.13%   |
| Intel Pentium           | 1         | 2.13%   |
| Intel Genuine           | 1         | 2.13%   |
| Intel Core m3           | 1         | 2.13%   |
| Intel Core 2            | 1         | 2.13%   |
| AMD V120                | 1         | 2.13%   |
| AMD Ryzen 7 PRO         | 1         | 2.13%   |
| AMD Ryzen 7             | 1         | 2.13%   |
| AMD Mobile Sempron      | 1         | 2.13%   |
| AMD E                   | 1         | 2.13%   |
| AMD C-70                | 1         | 2.13%   |
| AMD Athlon Neo          | 1         | 2.13%   |
| AMD A8                  | 1         | 2.13%   |
| AMD A4                  | 1         | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 53.19%  |
| 1      | 12        | 25.53%  |
| 4      | 8         | 17.02%  |
| 12     | 1         | 2.13%   |
| 8      | 1         | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 47        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 65.96%  |
| 2      | 16        | 34.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 76.6%   |
| 32-bit         | 11        | 23.4%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 8.51%   |
| 0x206a7    | 3         | 6.38%   |
| 0x106c2    | 3         | 6.38%   |
| 0x1067a    | 3         | 6.38%   |
| 0x706a1    | 2         | 4.26%   |
| 0x6fd      | 2         | 4.26%   |
| 0x406c4    | 2         | 4.26%   |
| 0x30678    | 2         | 4.26%   |
| 0x10676    | 2         | 4.26%   |
| 0xf27      | 1         | 2.13%   |
| 0x906a3    | 1         | 2.13%   |
| 0x806e9    | 1         | 2.13%   |
| 0x806c1    | 1         | 2.13%   |
| 0x706a8    | 1         | 2.13%   |
| 0x6fb      | 1         | 2.13%   |
| 0x6f6      | 1         | 2.13%   |
| 0x6e8      | 1         | 2.13%   |
| 0x6d8      | 1         | 2.13%   |
| 0x6d6      | 1         | 2.13%   |
| 0x695      | 1         | 2.13%   |
| 0x68a      | 1         | 2.13%   |
| 0x406e3    | 1         | 2.13%   |
| 0x40651    | 1         | 2.13%   |
| 0x306c3    | 1         | 2.13%   |
| 0x306a9    | 1         | 2.13%   |
| 0x20655    | 1         | 2.13%   |
| 0x0a704103 | 1         | 2.13%   |
| 0x08108102 | 1         | 2.13%   |
| 0x07030106 | 1         | 2.13%   |
| 0x06006705 | 1         | 2.13%   |
| 0x05000119 | 1         | 2.13%   |
| 0x0500010d | 1         | 2.13%   |
| 0x010000c8 | 1         | 2.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 5         | 10.64%  |
| Penryn        | 5         | 10.64%  |
| P6            | 5         | 10.64%  |
| Core          | 4         | 8.51%   |
| Bonnell       | 4         | 8.51%   |
| SandyBridge   | 3         | 6.38%   |
| Goldmont plus | 3         | 6.38%   |
| K8 Hammer     | 2         | 4.26%   |
| Haswell       | 2         | 4.26%   |
| Bobcat        | 2         | 4.26%   |
| Unknown       | 2         | 4.26%   |
| Zen+          | 1         | 2.13%   |
| Westmere      | 1         | 2.13%   |
| TigerLake     | 1         | 2.13%   |
| Skylake       | 1         | 2.13%   |
| Puma          | 1         | 2.13%   |
| NetBurst      | 1         | 2.13%   |
| KabyLake      | 1         | 2.13%   |
| K10           | 1         | 2.13%   |
| IvyBridge     | 1         | 2.13%   |
| Excavator     | 1         | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 29        | 59.18%  |
| AMD                              | 13        | 26.53%  |
| Silicon Integrated Systems [SiS] | 3         | 6.12%   |
| Nvidia                           | 3         | 6.12%   |
| S3 Graphics                      | 1         | 2.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 3         | 5.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 3         | 5.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 3         | 5.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 5.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 3         | 5.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 5.45%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 3.64%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 2         | 3.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 2         | 3.64%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.82%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 1.82%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 1.82%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.82%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 1.82%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.82%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 1.82%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 1.82%   |
| Intel HD Graphics 610                                                                      | 1         | 1.82%   |
| Intel HD Graphics 515                                                                      | 1         | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 1.82%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                  | 1         | 1.82%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 1         | 1.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 1         | 1.82%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 1.82%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 1.82%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 1.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 1.82%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]                | 1         | 1.82%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                           | 1         | 1.82%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                    | 1         | 1.82%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 1         | 1.82%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 1.82%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 1.82%   |
| AMD Phoenix1                                                                               | 1         | 1.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 23        | 48.94%  |
| 1 x AMD         | 12        | 25.53%  |
| 2 x Intel       | 3         | 6.38%   |
| 1 x SiS         | 3         | 6.38%   |
| 1 x Nvidia      | 2         | 4.26%   |
| Other           | 1         | 2.13%   |
| 1 x S3 Graphics | 1         | 2.13%   |
| Intel + Nvidia  | 1         | 2.13%   |
| Intel + AMD     | 1         | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 40        | 85.11%  |
| Unknown     | 5         | 10.64%  |
| Proprietary | 2         | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 68.09%  |
| 0.01-0.5   | 13        | 27.66%  |
| 1.01-2.0   | 2         | 4.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 22.5%   |
| Samsung Electronics     | 7         | 17.5%   |
| Chimei Innolux          | 7         | 17.5%   |
| LG Display              | 5         | 12.5%   |
| HannStar                | 2         | 5%      |
| CPT                     | 2         | 5%      |
| BOE                     | 2         | 5%      |
| MQP                     | 1         | 2.5%    |
| LG Philips              | 1         | 2.5%    |
| Hewlett-Packard         | 1         | 2.5%    |
| Dell                    | 1         | 2.5%    |
| Chi Mei Optoelectronics | 1         | 2.5%    |
| Apple                   | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 5%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 5%      |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch      | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 890x500mm 40.2-inch    | 1         | 2.5%    |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                     | 1         | 2.5%    |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 2.5%    |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 1         | 2.5%    |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch               | 1         | 2.5%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.5%    |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 1         | 2.5%    |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                         | 1         | 2.5%    |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                     | 1         | 2.5%    |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                     | 1         | 2.5%    |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 1         | 2.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO1004 1024x600 222x125mm 10.0-inch | 1         | 2.5%    |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                    | 1         | 2.5%    |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                     | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch           | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch           | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch            | 1         | 2.5%    |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 1         | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 15        | 37.5%   |
| 1920x1080 (FHD)   | 10        | 25%     |
| 1280x800 (WXGA)   | 6         | 15%     |
| 1600x900 (HD+)    | 3         | 7.5%    |
| 1024x600          | 2         | 5%      |
| 800x600           | 1         | 2.5%    |
| 2256x1504         | 1         | 2.5%    |
| 2160x1440         | 1         | 2.5%    |
| 1920x1200 (WUXGA) | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 42.5%   |
| 13     | 6         | 15%     |
| 14     | 3         | 7.5%    |
| 12     | 3         | 7.5%    |
| 11     | 3         | 7.5%    |
| 10     | 2         | 5%      |
| 46     | 1         | 2.5%    |
| 40     | 1         | 2.5%    |
| 24     | 1         | 2.5%    |
| 23     | 1         | 2.5%    |
| 18     | 1         | 2.5%    |
| 17     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 56.41%  |
| 201-300     | 10        | 25.64%  |
| 351-400     | 3         | 7.69%   |
| 501-600     | 2         | 5.13%   |
| 801-900     | 1         | 2.56%   |
| 1001-1500   | 1         | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 73.68%  |
| 16/10 | 7         | 18.42%  |
| 3/2   | 2         | 5.26%   |
| 4/3   | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 42.5%   |
| 81-90          | 9         | 22.5%   |
| 51-60          | 3         | 7.5%    |
| 61-70          | 2         | 5%      |
| 41-50          | 2         | 5%      |
| 501-1000       | 2         | 5%      |
| 71-80          | 1         | 2.5%    |
| 251-300        | 1         | 2.5%    |
| 201-250        | 1         | 2.5%    |
| 141-150        | 1         | 2.5%    |
| 121-130        | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 19        | 47.5%   |
| 51-100  | 9         | 22.5%   |
| 121-160 | 7         | 17.5%   |
| 161-240 | 4         | 10%     |
| 1-50    | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 85.11%  |
| 0     | 4         | 8.51%   |
| 2     | 3         | 6.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 25        | 31.65%  |
| Intel                            | 17        | 21.52%  |
| Qualcomm Atheros                 | 15        | 18.99%  |
| Broadcom                         | 5         | 6.33%   |
| Marvell Technology Group         | 4         | 5.06%   |
| Silicon Integrated Systems [SiS] | 3         | 3.8%    |
| Broadcom Limited                 | 2         | 2.53%   |
| Xiaomi                           | 1         | 1.27%   |
| Ralink Technology                | 1         | 1.27%   |
| Motorola PCS                     | 1         | 1.27%   |
| MediaTek                         | 1         | 1.27%   |
| LG Electronics                   | 1         | 1.27%   |
| JMicron Technology               | 1         | 1.27%   |
| D-Link System                    | 1         | 1.27%   |
| Accton Technology                | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 10.11%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 8         | 8.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 4.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 3.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 3.37%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 3.37%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.25%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 2.25%   |
| Intel Wireless 7265                                                     | 2         | 2.25%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.25%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 2.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.12%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 1.12%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.12%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.12%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.12%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 1.12%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.12%   |
| Motorola PCS moto g62 5G                                                | 1         | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.12%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 1         | 1.12%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 1.12%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 1.12%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.12%   |
| Intel Wireless 3165                                                     | 1         | 1.12%   |
| Intel WiFi Link 5100                                                    | 1         | 1.12%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.12%   |
| Intel Ethernet Connection I217-V                                        | 1         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 33.33%  |
| Qualcomm Atheros      | 14        | 31.11%  |
| Realtek Semiconductor | 8         | 17.78%  |
| Broadcom              | 3         | 6.67%   |
| Broadcom Limited      | 2         | 4.44%   |
| Ralink Technology     | 1         | 2.22%   |
| MediaTek              | 1         | 2.22%   |
| D-Link System         | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 8.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 8.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 6.67%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 6.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 4.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 4.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 4.44%   |
| Intel Wireless 7265                                                         | 2         | 4.44%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 2.22%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 2.22%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 2.22%   |
| Realtek RTL8187SE Wireless LAN Controller                                   | 1         | 2.22%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 2.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter               | 1         | 2.22%   |
| Intel Wireless 3165                                                         | 1         | 2.22%   |
| Intel WiFi Link 5100                                                        | 1         | 2.22%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 2.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.22%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 1         | 2.22%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2.22%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                   | 1         | 2.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.22%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 21        | 53.85%  |
| Marvell Technology Group         | 4         | 10.26%  |
| Intel                            | 4         | 10.26%  |
| Silicon Integrated Systems [SiS] | 2         | 5.13%   |
| Broadcom                         | 2         | 5.13%   |
| Xiaomi                           | 1         | 2.56%   |
| Qualcomm Atheros                 | 1         | 2.56%   |
| Motorola PCS                     | 1         | 2.56%   |
| LG Electronics                   | 1         | 2.56%   |
| JMicron Technology               | 1         | 2.56%   |
| Accton Technology                | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 23.08%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 20.51%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 7.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 5.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.56%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 2.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 2.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.56%   |
| Motorola PCS moto g62 5G                                          | 1         | 2.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.56%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.56%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.56%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 2.56%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 2.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.56%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 50.57%  |
| Ethernet | 38        | 43.68%  |
| Modem    | 5         | 5.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 70.21%  |
| Ethernet | 14        | 29.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 31        | 65.96%  |
| 1     | 13        | 27.66%  |
| 0     | 2         | 4.26%   |
| 3     | 1         | 2.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 85.11%  |
| Yes  | 7         | 14.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 6         | 27.27%  |
| Intel                           | 6         | 27.27%  |
| Realtek Semiconductor           | 3         | 13.64%  |
| Alps Electric                   | 2         | 9.09%   |
| Toshiba                         | 1         | 4.55%   |
| MediaTek                        | 1         | 4.55%   |
| Hewlett-Packard                 | 1         | 4.55%   |
| ASUSTek Computer                | 1         | 4.55%   |
| Apple                           | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth              | 4         | 18.18%  |
| Realtek Bluetooth Radio                        | 3         | 13.64%  |
| Intel Bluetooth wireless interface             | 3         | 13.64%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 9.09%   |
| Intel AX200 Bluetooth                          | 2         | 9.09%   |
| Alps Electric BCM2046 Bluetooth Device         | 2         | 9.09%   |
| Toshiba Askey for                              | 1         | 4.55%   |
| MediaTek Wireless_Device                       | 1         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 4.55%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 4.55%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 4.55%   |
| Apple Bluetooth HCI                            | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 32        | 68.09%  |
| AMD                              | 11        | 23.4%   |
| Silicon Integrated Systems [SiS] | 3         | 6.38%   |
| ESS Technology                   | 1         | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 7.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 7.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 5.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 5.26%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 3.51%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 3.51%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 3.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.51%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 3.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 3.51%   |
| AMD FCH Azalia Controller                                                                         | 2         | 3.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 3.51%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.75%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.75%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.75%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.75%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.75%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.75%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.75%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.75%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.75%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 17        | 33.33%  |
| Samsung Electronics | 11        | 21.57%  |
| SK hynix            | 6         | 11.76%  |
| Kingston            | 5         | 9.8%    |
| Unknown (ABCD)      | 2         | 3.92%   |
| Micron Technology   | 2         | 3.92%   |
| Elpida              | 2         | 3.92%   |
| A-DATA Technology   | 2         | 3.92%   |
| Toshiba             | 1         | 1.96%   |
| Team                | 1         | 1.96%   |
| Ramaxel Technology  | 1         | 1.96%   |
| Crucial             | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 10.91%  |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 5.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.64%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.82%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.82%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.82%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.82%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.82%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.82%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.82%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.82%   |
| Toshiba RAM 8HTF12864HDY-800G1 1GB SODIMM 1066MT/s               | 1         | 1.82%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.82%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1.82%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.82%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.82%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2400MT/s        | 1         | 1.82%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.82%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 1.82%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 1.82%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.82%   |
| Micron RAM MT52L256M32D1PF-10 2GB LPDDR3 1867MT/s                | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 3200MT/s         | 1         | 1.82%   |
| Kingston RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 1.82%   |
| Kingston RAM Module 2GB SODIMM DDR 667MT/s                       | 1         | 1.82%   |
| Kingston RAM HP32D4S2S1ME-4 4096MB SODIMM DDR4 3200MT/s          | 1         | 1.82%   |
| Kingston RAM HP16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 13        | 28.26%  |
| DDR2   | 12        | 26.09%  |
| DDR4   | 6         | 13.04%  |
| SDRAM  | 4         | 8.7%    |
| DDR    | 4         | 8.7%    |
| LPDDR4 | 2         | 4.35%   |
| LPDDR3 | 2         | 4.35%   |
| DRAM   | 2         | 4.35%   |
| DDR5   | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 91.11%  |
| Unknown      | 2         | 4.44%   |
| Row Of Chips | 1         | 2.22%   |
| DIMM         | 1         | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 18        | 36%     |
| 4096  | 14        | 28%     |
| 8192  | 6         | 12%     |
| 1024  | 6         | 12%     |
| 512   | 3         | 6%      |
| 32768 | 1         | 2%      |
| 16384 | 1         | 2%      |
| 256   | 1         | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 13        | 27.08%  |
| 1600    | 6         | 12.5%   |
| 2400    | 4         | 8.33%   |
| 1334    | 4         | 8.33%   |
| 3200    | 3         | 6.25%   |
| 2667    | 2         | 4.17%   |
| 1867    | 2         | 4.17%   |
| 1333    | 2         | 4.17%   |
| 1067    | 2         | 4.17%   |
| 667     | 2         | 4.17%   |
| 5600    | 1         | 2.08%   |
| 4199    | 1         | 2.08%   |
| 3266    | 1         | 2.08%   |
| 2048    | 1         | 2.08%   |
| 1066    | 1         | 2.08%   |
| 800     | 1         | 2.08%   |
| 533     | 1         | 2.08%   |
| 266     | 1         | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Microdia                               | 4         | 14.81%  |
| IMC Networks                           | 4         | 14.81%  |
| Chicony Electronics                    | 4         | 14.81%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 11.11%  |
| Ricoh                                  | 2         | 7.41%   |
| Bison Electronics                      | 2         | 7.41%   |
| Suyin                                  | 1         | 3.7%    |
| Silicon Motion                         | 1         | 3.7%    |
| Realtek Semiconductor                  | 1         | 3.7%    |
| Quanta                                 | 1         | 3.7%    |
| Luxvisions Innotech Limited            | 1         | 3.7%    |
| ALi                                    | 1         | 3.7%    |
| Alcor Micro                            | 1         | 3.7%    |
| Acer                                   | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                               | 2         | 7.41%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.7%    |
| Silicon Motion 300k Pixel Camera                            | 1         | 3.7%    |
| Ricoh Sony Visual Communication Camera                      | 1         | 3.7%    |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 3.7%    |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 3.7%    |
| Quanta Chromebook HD Camera                                 | 1         | 3.7%    |
| Microdia Webcam Vitade AF                                   | 1         | 3.7%    |
| Microdia Laptop_Integrated_Webcam_E4HD                      | 1         | 3.7%    |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.7%    |
| IMC Networks USB 2.0 Camera                                 | 1         | 3.7%    |
| IMC Networks Integrated Camera                              | 1         | 3.7%    |
| IMC Networks HP TrueVision HD Camera                        | 1         | 3.7%    |
| Chicony USB2.0 UVC WebCam                                   | 1         | 3.7%    |
| Chicony Integrated Camera                                   | 1         | 3.7%    |
| Chicony HP Webcam                                           | 1         | 3.7%    |
| Chicony HP HD Webcam                                        | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 3.7%    |
| Bison Integrated Camera                                     | 1         | 3.7%    |
| Bison EasyCamera                                            | 1         | 3.7%    |
| ALi M5603 Video Camera Controller                           | 1         | 3.7%    |
| Alcor Micro USB 2.0 Camera                                  | 1         | 3.7%    |
| Acer HP Webcam-101                                          | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 50%     |
| Synaptics                  | 1         | 25%     |
| Shenzhen Goodix Technology | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 25%     |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 25%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 36        | 76.6%   |
| 2     | 5         | 10.64%  |
| 1     | 5         | 10.64%  |
| 4     | 1         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 7         | 36.84%  |
| Fingerprint reader       | 4         | 21.05%  |
| Flash memory             | 2         | 10.53%  |
| Communication controller | 2         | 10.53%  |
| Chipcard                 | 2         | 10.53%  |
| Net/wireless             | 1         | 5.26%   |
| Camera                   | 1         | 5.26%   |

