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

Total: 48

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude D630            | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| Sony          | VGN-FW21Z                | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505  | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505  | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Google        | Reks                     | [be1a98408d](https://linux-hardware.org/?probe=be1a98408d) | Feb 28, 2023 |
| HP            | ProBook 650 G1           | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD    | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| IBM           | ThinkPad T42 2378FVU     | [ce2f3fb897](https://linux-hardware.org/?probe=ce2f3fb897) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU     | [50f1d0a765](https://linux-hardware.org/?probe=50f1d0a765) | Dec 19, 2022 |
| IBM           | ThinkPad T42 2378FVU     | [fe6bdea3fd](https://linux-hardware.org/?probe=fe6bdea3fd) | Dec 19, 2022 |
| Google        | Cave                     | [ce7f60e0ee](https://linux-hardware.org/?probe=ce7f60e0ee) | Nov 06, 2022 |
| Google        | Cave                     | [63e06049da](https://linux-hardware.org/?probe=63e06049da) | Nov 06, 2022 |
| Medion        | P6620                    | [e5db2a930b](https://linux-hardware.org/?probe=e5db2a930b) | Aug 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00 | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q               | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70            | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC       | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASUSTek       | A6U                      | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500       | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1   | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                   | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                   | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10               | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56            | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56            | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| MSI           | U210                     | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660           | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660           | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                    | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660           | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660           | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Phoenix/Si... | M720SR                   | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx        | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx        | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro             | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| HP            | ProBook 450 G2           | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                      | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| HP            | ProBook 6550b            | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                     | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASUSTek       | A6JC                     | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                     | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00  | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81            | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP              | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC              | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                  | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                      | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Q4OS 4 | 25        | 64.1%   |
| Q4OS 3 | 11        | 28.21%  |
| Q4OS 2 | 3         | 7.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 39        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 4.19.0-17-amd64      | 4         | 10.26%  |
| 5.10.0-21-amd64      | 3         | 7.69%   |
| 5.10.0-12-amd64      | 3         | 7.69%   |
| 5.10.0-8-amd64       | 2         | 5.13%   |
| 5.10.0-23-amd64      | 2         | 5.13%   |
| 5.10.0-14-686-pae    | 2         | 5.13%   |
| 5.9.0-5-amd64        | 1         | 2.56%   |
| 5.6.0-1-amd64        | 1         | 2.56%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 2.56%   |
| 5.10.0-9-amd64       | 1         | 2.56%   |
| 5.10.0-8-686-pae     | 1         | 2.56%   |
| 5.10.0-21-686-pae    | 1         | 2.56%   |
| 5.10.0-20-686        | 1         | 2.56%   |
| 5.10.0-17-amd64      | 1         | 2.56%   |
| 5.10.0-15-686-pae    | 1         | 2.56%   |
| 5.10.0-13-amd64      | 1         | 2.56%   |
| 5.10.0-12-686-pae    | 1         | 2.56%   |
| 5.10.0-11-686-pae    | 1         | 2.56%   |
| 5.10.0-10-686-pae    | 1         | 2.56%   |
| 4.9.0-8-amd64        | 1         | 2.56%   |
| 4.9.0-14-686-pae     | 1         | 2.56%   |
| 4.9.0-12-686-pae     | 1         | 2.56%   |
| 4.19.0-22-amd64      | 1         | 2.56%   |
| 4.19.0-20-amd64      | 1         | 2.56%   |
| 4.19.0-17-686        | 1         | 2.56%   |
| 4.19.0-14-amd64      | 1         | 2.56%   |
| 4.19.0-13-amd64      | 1         | 2.56%   |
| 4.19.0-12-amd64      | 1         | 2.56%   |
| 4.19.0-10-amd64      | 1         | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 22        | 56.41%  |
| 4.19.0  | 11        | 28.21%  |
| 4.9.0   | 3         | 7.69%   |
| 5.9.0   | 1         | 2.56%   |
| 5.6.0   | 1         | 2.56%   |
| 5.18.0  | 1         | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 22        | 56.41%  |
| 4.19    | 11        | 28.21%  |
| 4.9     | 3         | 7.69%   |
| 5.9     | 1         | 2.56%   |
| 5.6     | 1         | 2.56%   |
| 5.18    | 1         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 27        | 69.23%  |
| i686   | 12        | 30.77%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 20        | 51.28%  |
| trinity  | 17        | 43.59%  |
| KDE      | 1         | 2.56%   |
| Cinnamon | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 38        | 97.44%  |
| Tty  | 1         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 22        | 56.41%  |
| TDM  | 17        | 43.59%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 17        | 43.59%  |
| en_GB   | 5         | 12.82%  |
| es_ES   | 3         | 7.69%   |
| it_IT   | 2         | 5.13%   |
| de_DE   | 2         | 5.13%   |
| sv_SE   | 1         | 2.56%   |
| sl_SI   | 1         | 2.56%   |
| ru_RU   | 1         | 2.56%   |
| pl_PL   | 1         | 2.56%   |
| hu_HU   | 1         | 2.56%   |
| fr_FR   | 1         | 2.56%   |
| es_VE   | 1         | 2.56%   |
| en_SG   | 1         | 2.56%   |
| C       | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 24        | 61.54%  |
| EFI  | 15        | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 36        | 92.31%  |
| Overlay | 3         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 23        | 58.97%  |
| GPT     | 15        | 38.46%  |
| Unknown | 1         | 2.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 87.18%  |
| Yes       | 5         | 12.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 69.23%  |
| Yes       | 12        | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 8         | 20.51%  |
| Toshiba          | 4         | 10.26%  |
| Lenovo           | 4         | 10.26%  |
| ASUSTek Computer | 4         | 10.26%  |
| Sony             | 2         | 5.13%   |
| Medion           | 2         | 5.13%   |
| Google           | 2         | 5.13%   |
| Visual Land      | 1         | 2.56%   |
| Qilive           | 1         | 2.56%   |
| Phoenix/SiS      | 1         | 2.56%   |
| Philco           | 1         | 2.56%   |
| Packard Bell     | 1         | 2.56%   |
| MSI              | 1         | 2.56%   |
| JVC              | 1         | 2.56%   |
| IBM              | 1         | 2.56%   |
| Fujitsu Siemens  | 1         | 2.56%   |
| Dell             | 1         | 2.56%   |
| Chuwi            | 1         | 2.56%   |
| AMI              | 1         | 2.56%   |
| Acer             | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba Satellite C660                  | 2         | 5.13%   |
| Visual Land Premier 10                  | 1         | 2.56%   |
| Toshiba Satellite Pro L500              | 1         | 2.56%   |
| Toshiba Satellite M70                   | 1         | 2.56%   |
| Sony VGN-P11Z_Q                         | 1         | 2.56%   |
| Sony VGN-FW21Z                          | 1         | 2.56%   |
| Qilive QW19141AMSP                      | 1         | 2.56%   |
| Phoenix/SiS M720SR                      | 1         | 2.56%   |
| Philco 14I                              | 1         | 2.56%   |
| Packard Bell EasyNote LM81              | 1         | 2.56%   |
| MSI U210                                | 1         | 2.56%   |
| Medion P6620                            | 1         | 2.56%   |
| Lenovo ThinkPad T495 20NKS0PG00         | 1         | 2.56%   |
| Lenovo ThinkPad 11e 20DAS0PS00          | 1         | 2.56%   |
| Lenovo IdeaPad 5 14IAL7 82SD            | 1         | 2.56%   |
| Lenovo IdeaPad 330-15IGM 81D1           | 1         | 2.56%   |
| JVC J3N                                 | 1         | 2.56%   |
| IBM ThinkPad T42 2378FVU                | 1         | 2.56%   |
| HP ProBook 6550b                        | 1         | 2.56%   |
| HP ProBook 650 G1                       | 1         | 2.56%   |
| HP ProBook 450 G2                       | 1         | 2.56%   |
| HP Presario CQ56                        | 1         | 2.56%   |
| HP OmniBook PC                          | 1         | 2.56%   |
| HP Laptop 15s-fq2xxx                    | 1         | 2.56%   |
| HP 250 G5 Notebook PC                   | 1         | 2.56%   |
| HP 2000                                 | 1         | 2.56%   |
| Google Reks                             | 1         | 2.56%   |
| Google Cave                             | 1         | 2.56%   |
| Fujitsu Siemens AMILO Pro Edition V3505 | 1         | 2.56%   |
| Dell Latitude D630                      | 1         | 2.56%   |
| Chuwi GemiBook Pro                      | 1         | 2.56%   |
| ASUS X540YA                             | 1         | 2.56%   |
| ASUS T12Eg                              | 1         | 2.56%   |
| ASUS A6U                                | 1         | 2.56%   |
| ASUS A6JC                               | 1         | 2.56%   |
| AMI Intel                               | 1         | 2.56%   |
| Acer AO751h                             | 1         | 2.56%   |
| Unknown                                 | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toshiba Satellite     | 4         | 10.26%  |
| HP ProBook            | 3         | 7.69%   |
| Lenovo ThinkPad       | 2         | 5.13%   |
| Lenovo IdeaPad        | 2         | 5.13%   |
| Visual Land Premier   | 1         | 2.56%   |
| Sony VGN-P11Z         | 1         | 2.56%   |
| Sony VGN-FW21Z        | 1         | 2.56%   |
| Qilive QW19141AMSP    | 1         | 2.56%   |
| Phoenix/SiS M720SR    | 1         | 2.56%   |
| Philco 14I            | 1         | 2.56%   |
| Packard Bell EasyNote | 1         | 2.56%   |
| MSI U210              | 1         | 2.56%   |
| Medion P6620          | 1         | 2.56%   |
| JVC J3N               | 1         | 2.56%   |
| IBM ThinkPad          | 1         | 2.56%   |
| HP Presario           | 1         | 2.56%   |
| HP OmniBook           | 1         | 2.56%   |
| HP Laptop             | 1         | 2.56%   |
| HP 250                | 1         | 2.56%   |
| HP 2000               | 1         | 2.56%   |
| Google Reks           | 1         | 2.56%   |
| Google Cave           | 1         | 2.56%   |
| Fujitsu Siemens AMILO | 1         | 2.56%   |
| Dell Latitude         | 1         | 2.56%   |
| Chuwi GemiBook        | 1         | 2.56%   |
| ASUS X540YA           | 1         | 2.56%   |
| ASUS T12Eg            | 1         | 2.56%   |
| ASUS A6U              | 1         | 2.56%   |
| ASUS A6JC             | 1         | 2.56%   |
| AMI Intel             | 1         | 2.56%   |
| Acer AO751h           | 1         | 2.56%   |
| Unknown               | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 5         | 12.82%  |
| 2009    | 4         | 10.26%  |
| 2020    | 3         | 7.69%   |
| 2022    | 2         | 5.13%   |
| 2019    | 2         | 5.13%   |
| 2016    | 2         | 5.13%   |
| 2014    | 2         | 5.13%   |
| 2008    | 2         | 5.13%   |
| 2007    | 2         | 5.13%   |
| 2006    | 2         | 5.13%   |
| 2005    | 2         | 5.13%   |
| 2004    | 2         | 5.13%   |
| Unknown | 2         | 5.13%   |
| 2023    | 1         | 2.56%   |
| 2018    | 1         | 2.56%   |
| 2017    | 1         | 2.56%   |
| 2015    | 1         | 2.56%   |
| 2013    | 1         | 2.56%   |
| 2012    | 1         | 2.56%   |
| 2011    | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 39        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 36        | 92.31%  |
| Enabled  | 3         | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 94.87%  |
| Yes  | 2         | 5.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 14        | 35.9%   |
| 2.01-3.0   | 7         | 17.95%  |
| 4.01-8.0   | 6         | 15.38%  |
| 1.01-2.0   | 5         | 12.82%  |
| 0.51-1.0   | 3         | 7.69%   |
| 24.01-32.0 | 1         | 2.56%   |
| 16.01-24.0 | 1         | 2.56%   |
| 8.01-16.0  | 1         | 2.56%   |
| 0.01-0.5   | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 19        | 48.72%  |
| 0.51-1.0 | 8         | 20.51%  |
| 2.01-3.0 | 6         | 15.38%  |
| 0.01-0.5 | 4         | 10.26%  |
| 3.01-4.0 | 2         | 5.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 79.49%  |
| 2      | 7         | 17.95%  |
| 3      | 1         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 56.41%  |
| No        | 17        | 43.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 82.05%  |
| No        | 7         | 17.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 92.31%  |
| No        | 3         | 7.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 53.85%  |
| Yes       | 18        | 46.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 7         | 17.95%  |
| UK           | 5         | 12.82%  |
| Spain        | 3         | 7.69%   |
| Kenya        | 3         | 7.69%   |
| Italy        | 3         | 7.69%   |
| Romania      | 2         | 5.13%   |
| Poland       | 2         | 5.13%   |
| Germany      | 2         | 5.13%   |
| Venezuela    | 1         | 2.56%   |
| Sweden       | 1         | 2.56%   |
| Slovenia     | 1         | 2.56%   |
| Singapore    | 1         | 2.56%   |
| Saudi Arabia | 1         | 2.56%   |
| Russia       | 1         | 2.56%   |
| Qatar        | 1         | 2.56%   |
| Hungary      | 1         | 2.56%   |
| France       | 1         | 2.56%   |
| Croatia      | 1         | 2.56%   |
| Brazil       | 1         | 2.56%   |
| Belarus      | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 7.69%   |
| Swindon               | 2         | 5.13%   |
| Mesa                  | 2         | 5.13%   |
| Drobeta-Turnu Severin | 2         | 5.13%   |
| West Corinth          | 1         | 2.56%   |
| Tenbury Wells         | 1         | 2.56%   |
| Tellico Plains        | 1         | 2.56%   |
| Sosnowiec             | 1         | 2.56%   |
| Singapore             | 1         | 2.56%   |
| Schermbeck            | 1         | 2.56%   |
| Salsomaggiore Terme   | 1         | 2.56%   |
| Rostock               | 1         | 2.56%   |
| Rijeka                | 1         | 2.56%   |
| Puerto Cumarebo       | 1         | 2.56%   |
| Moscow                | 1         | 2.56%   |
| Mooresville           | 1         | 2.56%   |
| Moirans               | 1         | 2.56%   |
| Mogilev               | 1         | 2.56%   |
| Milano                | 1         | 2.56%   |
| Londrina              | 1         | 2.56%   |
| Ljubljana             | 1         | 2.56%   |
| Las Vegas             | 1         | 2.56%   |
| Klaudyn               | 1         | 2.56%   |
| Jönköping           | 1         | 2.56%   |
| Indianapolis          | 1         | 2.56%   |
| Gijón                | 1         | 2.56%   |
| Fulham                | 1         | 2.56%   |
| Doha                  | 1         | 2.56%   |
| Dammam                | 1         | 2.56%   |
| Carterton             | 1         | 2.56%   |
| Calvecchia            | 1         | 2.56%   |
| Budapest              | 1         | 2.56%   |
| Barcelona             | 1         | 2.56%   |
| Alicante              | 1         | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 6         | 6      | 14.29%  |
| WDC                 | 5         | 5      | 11.9%   |
| Kingston            | 5         | 5      | 11.9%   |
| Samsung Electronics | 4         | 4      | 9.52%   |
| Seagate             | 3         | 3      | 7.14%   |
| Hitachi             | 3         | 3      | 7.14%   |
| Toshiba             | 2         | 2      | 4.76%   |
| SanDisk             | 2         | 2      | 4.76%   |
| KESU                | 2         | 2      | 4.76%   |
| HGST                | 2         | 2      | 4.76%   |
| China               | 2         | 2      | 4.76%   |
| Silicon Motion      | 1         | 1      | 2.38%   |
| Phison              | 1         | 1      | 2.38%   |
| KingSpec            | 1         | 1      | 2.38%   |
| Fujitsu             | 1         | 1      | 2.38%   |
| A-DATA Technology   | 1         | 1      | 2.38%   |
| Unknown             | 1         | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 2         | 4.76%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 4.76%   |
| KESU USB 3.1 256GB                   | 2         | 4.76%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 2.38%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 2.38%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 2.38%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 2.38%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 2.38%   |
| Unknown USDU1  32GB                  | 1         | 2.38%   |
| Unknown SLD64G  64GB                 | 1         | 2.38%   |
| Unknown SD/MMC/MS PRO 64GB           | 1         | 2.38%   |
| Unknown MMC Card  64GB               | 1         | 2.38%   |
| Unknown HAG2e  16GB                  | 1         | 2.38%   |
| Unknown 064G38  64GB                 | 1         | 2.38%   |
| Toshiba MK8025GAS 80GB               | 1         | 2.38%   |
| Toshiba MK6028GAL 64GB               | 1         | 2.38%   |
| Silicon Motion NVME SSD 512GB        | 1         | 2.38%   |
| Seagate ST96812AS 64GB               | 1         | 2.38%   |
| Seagate ST9120822AS 120GB            | 1         | 2.38%   |
| Seagate Backup+ SL 1TB               | 1         | 2.38%   |
| SanDisk SDCFX-032G SSD               | 1         | 2.38%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 2.38%   |
| Samsung MZAL4512HBLU-00BL2 512GB     | 1         | 2.38%   |
| Samsung AWMB3R  16GB                 | 1         | 2.38%   |
| Phison APS-SE20G-1T                  | 1         | 2.38%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 2.38%   |
| Kingston SV300S37A240G 240GB SSD     | 1         | 2.38%   |
| Kingston SUV400S37120G 120GB SSD     | 1         | 2.38%   |
| KingSpec KSD-PA25.6-064MS 64GB SSD   | 1         | 2.38%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 2.38%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 2.38%   |
| Hitachi DK23CA-20 20GB               | 1         | 2.38%   |
| HGST HTS725050A7E630 500GB           | 1         | 2.38%   |
| HGST HTS541075A9E680 752GB           | 1         | 2.38%   |
| Fujitsu MHY2080BH 80GB               | 1         | 2.38%   |
| China SSD128GBS800                   | 1         | 2.38%   |
| China SATA SSD 240GB                 | 1         | 2.38%   |
| A-DATA SU630 240GB SSD               | 1         | 2.38%   |
| Unknown                              | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 26.67%  |
| Hitachi | 3         | 3      | 20%     |
| Toshiba | 2         | 2      | 13.33%  |
| Seagate | 2         | 2      | 13.33%  |
| HGST    | 2         | 2      | 13.33%  |
| Unknown | 1         | 1      | 6.67%   |
| Fujitsu | 1         | 1      | 6.67%   |

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
| SSD     | 14        | 14     | 35%     |
| HDD     | 14        | 15     | 35%     |
| MMC     | 6         | 6      | 15%     |
| NVMe    | 3         | 4      | 7.5%    |
| Unknown | 3         | 3      | 7.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 28     | 68.29%  |
| MMC  | 6         | 6      | 14.63%  |
| SAS  | 4         | 4      | 9.76%   |
| NVMe | 3         | 4      | 7.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 27     | 92.86%  |
| 0.51-1.0   | 2         | 2      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 23.08%  |
| 51-100     | 8         | 20.51%  |
| 1-20       | 7         | 17.95%  |
| 251-500    | 5         | 12.82%  |
| 21-50      | 5         | 12.82%  |
| 1001-2000  | 2         | 5.13%   |
| 501-1000   | 2         | 5.13%   |
| Unknown    | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 27        | 69.23%  |
| 21-50    | 7         | 17.95%  |
| 251-500  | 2         | 5.13%   |
| 501-1000 | 1         | 2.56%   |
| 51-100   | 1         | 2.56%   |
| Unknown  | 1         | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 12.5%   |
| Seagate ST9120822AS 120GB     | 1         | 1      | 12.5%   |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 12.5%   |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 12.5%   |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 12.5%   |
| HGST HTS725050A7E630 500GB    | 1         | 1      | 12.5%   |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 12.5%   |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 37.5%   |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Seagate | 1         | 1      | 12.5%   |
| Fujitsu | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 37.5%   |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Seagate | 1         | 1      | 12.5%   |
| Fujitsu | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 100%    |

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
| Works    | 22        | 23     | 55%     |
| Detected | 10        | 11     | 25%     |
| Malfunc  | 8         | 8      | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 25        | 67.57%  |
| AMD                              | 6         | 16.22%  |
| Silicon Integrated Systems [SiS] | 2         | 5.41%   |
| Silicon Motion                   | 1         | 2.7%    |
| SanDisk                          | 1         | 2.7%    |
| Samsung Electronics              | 1         | 2.7%    |
| Phison Electronics               | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 9.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 6.98%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 6.98%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 4.65%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 4.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 4.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 4.65%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 4.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.33%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 2.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.33%   |
| Samsung NVMe SSD Controller PM9B1                                                | 1         | 2.33%   |
| Phison E12 NVMe Controller                                                       | 1         | 2.33%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.33%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 2.33%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 2.33%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 2.33%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 2.33%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 56.41%  |
| IDE  | 13        | 33.33%  |
| NVMe | 3         | 7.69%   |
| RAID | 1         | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 31        | 79.49%  |
| AMD    | 8         | 20.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz               | 2         | 5.13%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 5.13%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 5.13%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 5.13%   |
| Intel Pentium M processor 1000MHz               | 1         | 2.56%   |
| Intel Pentium III (Coppermine)                  | 1         | 2.56%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2.56%   |
| Intel Genuine CPU T2050 @ 1.60GHz               | 1         | 2.56%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 2.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.56%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 2.56%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2.56%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.56%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.56%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.56%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2.56%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2.56%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.56%   |
| Intel Atom CPU Z3735G @ 1.33GHz                 | 1         | 2.56%   |
| Intel 12th Gen Core i5-1240P                    | 1         | 2.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.56%   |
| AMD V120 Processor                              | 1         | 2.56%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 2.56%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.56%   |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2.56%   |
| AMD Athlon Neo Processor MV-40                  | 1         | 2.56%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.56%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G   | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 6         | 15.38%  |
| Intel Celeron           | 6         | 15.38%  |
| Intel Atom              | 4         | 10.26%  |
| Intel Pentium M         | 3         | 7.69%   |
| Intel Core i5           | 3         | 7.69%   |
| Other                   | 2         | 5.13%   |
| Intel Core i3           | 2         | 5.13%   |
| Intel Pentium III       | 1         | 2.56%   |
| Intel Pentium Dual-Core | 1         | 2.56%   |
| Intel Genuine           | 1         | 2.56%   |
| Intel Core m3           | 1         | 2.56%   |
| Intel Core 2            | 1         | 2.56%   |
| AMD V120                | 1         | 2.56%   |
| AMD Ryzen 7 PRO         | 1         | 2.56%   |
| AMD Mobile Sempron      | 1         | 2.56%   |
| AMD E                   | 1         | 2.56%   |
| AMD C-70                | 1         | 2.56%   |
| AMD Athlon Neo          | 1         | 2.56%   |
| AMD A8                  | 1         | 2.56%   |
| AMD A4                  | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 53.85%  |
| 1      | 9         | 23.08%  |
| 4      | 8         | 20.51%  |
| 12     | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 74.36%  |
| 2      | 10        | 25.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 79.49%  |
| 32-bit         | 8         | 20.51%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 10.26%  |
| 0x1067a    | 3         | 7.69%   |
| 0x706a1    | 2         | 5.13%   |
| 0x6fd      | 2         | 5.13%   |
| 0x406c4    | 2         | 5.13%   |
| 0x30678    | 2         | 5.13%   |
| 0x206a7    | 2         | 5.13%   |
| 0x906a3    | 1         | 2.56%   |
| 0x806c1    | 1         | 2.56%   |
| 0x706a8    | 1         | 2.56%   |
| 0x6fb      | 1         | 2.56%   |
| 0x6f6      | 1         | 2.56%   |
| 0x6e8      | 1         | 2.56%   |
| 0x6d8      | 1         | 2.56%   |
| 0x6d6      | 1         | 2.56%   |
| 0x695      | 1         | 2.56%   |
| 0x68a      | 1         | 2.56%   |
| 0x406e3    | 1         | 2.56%   |
| 0x40651    | 1         | 2.56%   |
| 0x306c3    | 1         | 2.56%   |
| 0x20655    | 1         | 2.56%   |
| 0x106c2    | 1         | 2.56%   |
| 0x10676    | 1         | 2.56%   |
| 0x08108102 | 1         | 2.56%   |
| 0x07030106 | 1         | 2.56%   |
| 0x06006705 | 1         | 2.56%   |
| 0x05000119 | 1         | 2.56%   |
| 0x0500010d | 1         | 2.56%   |
| 0x010000c8 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 5         | 12.82%  |
| P6            | 5         | 12.82%  |
| Penryn        | 4         | 10.26%  |
| Core          | 4         | 10.26%  |
| Goldmont plus | 3         | 7.69%   |
| SandyBridge   | 2         | 5.13%   |
| K8 Hammer     | 2         | 5.13%   |
| Haswell       | 2         | 5.13%   |
| Bonnell       | 2         | 5.13%   |
| Bobcat        | 2         | 5.13%   |
| Zen+          | 1         | 2.56%   |
| Westmere      | 1         | 2.56%   |
| TigerLake     | 1         | 2.56%   |
| Skylake       | 1         | 2.56%   |
| Puma          | 1         | 2.56%   |
| K10           | 1         | 2.56%   |
| Excavator     | 1         | 2.56%   |
| Unknown       | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 23        | 57.5%   |
| AMD                              | 12        | 30%     |
| Silicon Integrated Systems [SiS] | 2         | 5%      |
| Nvidia                           | 2         | 5%      |
| S3 Graphics                      | 1         | 2.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 6.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 3         | 6.98%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 4.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 2         | 4.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 2         | 4.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 2         | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 2         | 4.65%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 2.33%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 2.33%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 2.33%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 2.33%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 2.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 1         | 2.33%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 2.33%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 2.33%   |
| Intel HD Graphics 515                                                                      | 1         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 2.33%   |
| Intel Alder Lake-P Integrated Graphics Controller                                          | 1         | 2.33%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 1         | 2.33%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 2.33%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 2.33%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 2.33%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]                | 1         | 2.33%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                           | 1         | 2.33%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                    | 1         | 2.33%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 1         | 2.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 2.33%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 2.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 21        | 53.85%  |
| 1 x AMD         | 11        | 28.21%  |
| 1 x SiS         | 2         | 5.13%   |
| 1 x Nvidia      | 2         | 5.13%   |
| Other           | 1         | 2.56%   |
| 1 x S3 Graphics | 1         | 2.56%   |
| Intel + AMD     | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 34        | 87.18%  |
| Unknown     | 4         | 10.26%  |
| Proprietary | 1         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 64.1%   |
| 0.01-0.5   | 12        | 30.77%  |
| 1.01-2.0   | 2         | 5.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 21.88%  |
| Chimei Innolux      | 7         | 21.88%  |
| AU Optronics        | 7         | 21.88%  |
| LG Display          | 4         | 12.5%   |
| CPT                 | 2         | 6.25%   |
| LG Philips          | 1         | 3.13%   |
| Hewlett-Packard     | 1         | 3.13%   |
| HannStar            | 1         | 3.13%   |
| Dell                | 1         | 3.13%   |
| BOE                 | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 6.25%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 6.25%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch    | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch   | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch   | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch   | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch   | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch | 1         | 3.13%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch            | 1         | 3.13%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch            | 1         | 3.13%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 3.13%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch             | 1         | 3.13%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch               | 1         | 3.13%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                       | 1         | 3.13%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                   | 1         | 3.13%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                   | 1         | 3.13%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch       | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch        | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch        | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch        | 1         | 3.13%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                   | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch          | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch          | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch          | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch          | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 13        | 40.63%  |
| 1920x1080 (FHD)   | 9         | 28.13%  |
| 1280x800 (WXGA)   | 5         | 15.63%  |
| 1600x900 (HD+)    | 3         | 9.38%   |
| 2160x1440         | 1         | 3.13%   |
| 1920x1200 (WUXGA) | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 50%     |
| 13     | 3         | 9.38%   |
| 11     | 3         | 9.38%   |
| 14     | 2         | 6.25%   |
| 12     | 2         | 6.25%   |
| 46     | 1         | 3.13%   |
| 40     | 1         | 3.13%   |
| 24     | 1         | 3.13%   |
| 23     | 1         | 3.13%   |
| 18     | 1         | 3.13%   |
| 17     | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 59.38%  |
| 201-300     | 6         | 18.75%  |
| 351-400     | 3         | 9.38%   |
| 501-600     | 2         | 6.25%   |
| 801-900     | 1         | 3.13%   |
| 1001-1500   | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 76.67%  |
| 16/10 | 6         | 20%     |
| 3/2   | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 50%     |
| 81-90          | 5         | 15.63%  |
| 51-60          | 3         | 9.38%   |
| 61-70          | 2         | 6.25%   |
| 501-1000       | 2         | 6.25%   |
| 251-300        | 1         | 3.13%   |
| 201-250        | 1         | 3.13%   |
| 141-150        | 1         | 3.13%   |
| 121-130        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 14        | 43.75%  |
| 51-100  | 8         | 25%     |
| 121-160 | 6         | 18.75%  |
| 161-240 | 3         | 9.38%   |
| 1-50    | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 34        | 87.18%  |
| 0     | 3         | 7.69%   |
| 2     | 2         | 5.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 23        | 34.33%  |
| Intel                            | 16        | 23.88%  |
| Qualcomm Atheros                 | 12        | 17.91%  |
| Broadcom                         | 4         | 5.97%   |
| Marvell Technology Group         | 3         | 4.48%   |
| Silicon Integrated Systems [SiS] | 2         | 2.99%   |
| Xiaomi                           | 1         | 1.49%   |
| Ralink Technology                | 1         | 1.49%   |
| Motorola PCS                     | 1         | 1.49%   |
| LG Electronics                   | 1         | 1.49%   |
| JMicron Technology               | 1         | 1.49%   |
| Broadcom Limited                 | 1         | 1.49%   |
| Accton Technology                | 1         | 1.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 10.81%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 7         | 9.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 5.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 4.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 4.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 4.05%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 4.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.7%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 2.7%    |
| Intel Wireless 7265                                                     | 2         | 2.7%    |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.7%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 2.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.35%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 1         | 1.35%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.35%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 1.35%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.35%   |
| Motorola PCS moto g(40) fusion                                          | 1         | 1.35%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 1.35%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 1.35%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.35%   |
| Intel Wireless 3165                                                     | 1         | 1.35%   |
| Intel WiFi Link 5100                                                    | 1         | 1.35%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.35%   |
| Intel Ethernet Connection I217-V                                        | 1         | 1.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.35%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 1.35%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 1.35%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 1         | 1.35%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                | 1         | 1.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 37.84%  |
| Qualcomm Atheros      | 12        | 32.43%  |
| Realtek Semiconductor | 7         | 18.92%  |
| Broadcom              | 2         | 5.41%   |
| Ralink Technology     | 1         | 2.7%    |
| Broadcom Limited      | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 10.81%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 8.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 8.11%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 8.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 5.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 5.41%   |
| Intel Wireless 7265                                                         | 2         | 5.41%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 5.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 2.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 2.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 2.7%    |
| Ralink RT5370 Wireless Adapter                                              | 1         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 2.7%    |
| Intel Wireless 3165                                                         | 1         | 2.7%    |
| Intel WiFi Link 5100                                                        | 1         | 2.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 2.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.7%    |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 19        | 57.58%  |
| Marvell Technology Group         | 3         | 9.09%   |
| Intel                            | 3         | 9.09%   |
| Broadcom                         | 2         | 6.06%   |
| Xiaomi                           | 1         | 3.03%   |
| Silicon Integrated Systems [SiS] | 1         | 3.03%   |
| Motorola PCS                     | 1         | 3.03%   |
| LG Electronics                   | 1         | 3.03%   |
| JMicron Technology               | 1         | 3.03%   |
| Accton Technology                | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 24.24%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 21.21%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 9.09%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 6.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 3.03%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 3.03%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 3.03%   |
| Motorola PCS moto g(40) fusion                                    | 1         | 3.03%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 3.03%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 3.03%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.03%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.03%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 3.03%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 3.03%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 3.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.03%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 50%     |
| Ethernet | 32        | 44.44%  |
| Modem    | 4         | 5.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 66.67%  |
| Ethernet | 13        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 26        | 66.67%  |
| 1     | 10        | 25.64%  |
| 0     | 2         | 5.13%   |
| 3     | 1         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 89.74%  |
| Yes  | 4         | 10.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 33.33%  |
| Qualcomm Atheros Communications | 4         | 22.22%  |
| Realtek Semiconductor           | 3         | 16.67%  |
| Alps Electric                   | 2         | 11.11%  |
| Toshiba                         | 1         | 5.56%   |
| Hewlett-Packard                 | 1         | 5.56%   |
| ASUSTek Computer                | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 3         | 16.67%  |
| Qualcomm Atheros AR3011 Bluetooth              | 3         | 16.67%  |
| Intel Bluetooth wireless interface             | 3         | 16.67%  |
| Intel AX200 Bluetooth                          | 2         | 11.11%  |
| Alps Electric BCM2046 Bluetooth Device         | 2         | 11.11%  |
| Toshiba Askey for                              | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 5.56%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 5.56%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 66.67%  |
| AMD                              | 10        | 25.64%  |
| Silicon Integrated Systems [SiS] | 2         | 5.13%   |
| ESS Technology                   | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 8.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 6.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 6.25%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 4.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 4.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.17%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 4.17%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 4.17%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.17%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 2.08%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.08%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 2.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 2.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.08%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.08%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 2.08%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 2.08%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2.08%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.08%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 2.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 15        | 36.59%  |
| Samsung Electronics | 10        | 24.39%  |
| SK hynix            | 5         | 12.2%   |
| Kingston            | 4         | 9.76%   |
| Unknown (ABCD)      | 2         | 4.88%   |
| Toshiba             | 1         | 2.44%   |
| Team                | 1         | 2.44%   |
| Micron Technology   | 1         | 2.44%   |
| Elpida              | 1         | 2.44%   |
| A-DATA Technology   | 1         | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 13.33%  |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 4.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 4.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 4.44%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 2.22%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 2.22%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 2.22%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 2.22%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 2.22%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 2.22%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 2.22%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 2.22%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 2.22%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 2.22%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 2.22%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 2.22%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 2.22%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 2.22%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.22%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 2.22%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 2.22%   |
| Micron RAM MT52L256M32D1PF-10 2GB LPDDR3 1867MT/s                | 1         | 2.22%   |
| Kingston RAM Module 2GB SODIMM DDR 667MT/s                       | 1         | 2.22%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 2.22%   |
| Kingston RAM HP16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 2.22%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s            | 1         | 2.22%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s             | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 11        | 28.95%  |
| DDR2   | 9         | 23.68%  |
| DDR4   | 5         | 13.16%  |
| SDRAM  | 4         | 10.53%  |
| DDR    | 4         | 10.53%  |
| LPDDR4 | 2         | 5.26%   |
| LPDDR3 | 2         | 5.26%   |
| DRAM   | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 89.19%  |
| Unknown      | 2         | 5.41%   |
| Row Of Chips | 1         | 2.7%    |
| DIMM         | 1         | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 16        | 40%     |
| 4096  | 13        | 32.5%   |
| 1024  | 5         | 12.5%   |
| 8192  | 2         | 5%      |
| 512   | 2         | 5%      |
| 16384 | 1         | 2.5%    |
| 256   | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 11        | 28.21%  |
| 1600    | 5         | 12.82%  |
| 2400    | 4         | 10.26%  |
| 1334    | 3         | 7.69%   |
| 3200    | 2         | 5.13%   |
| 1867    | 2         | 5.13%   |
| 1333    | 2         | 5.13%   |
| 1067    | 2         | 5.13%   |
| 4199    | 1         | 2.56%   |
| 3266    | 1         | 2.56%   |
| 2667    | 1         | 2.56%   |
| 2048    | 1         | 2.56%   |
| 1066    | 1         | 2.56%   |
| 800     | 1         | 2.56%   |
| 667     | 1         | 2.56%   |
| 266     | 1         | 2.56%   |

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
| Chicony Electronics                    | 4         | 17.39%  |
| IMC Networks                           | 3         | 13.04%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 13.04%  |
| Ricoh                                  | 2         | 8.7%    |
| Microdia                               | 2         | 8.7%    |
| Suyin                                  | 1         | 4.35%   |
| Silicon Motion                         | 1         | 4.35%   |
| Realtek Semiconductor                  | 1         | 4.35%   |
| Quanta                                 | 1         | 4.35%   |
| Luxvisions Innotech Limited            | 1         | 4.35%   |
| Bison Electronics                      | 1         | 4.35%   |
| ALi                                    | 1         | 4.35%   |
| Alcor Micro                            | 1         | 4.35%   |
| Acer                                   | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 4.35%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 4.35%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 4.35%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 4.35%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 4.35%   |
| Quanta Chromebook HD Camera                                 | 1         | 4.35%   |
| Microdia Webcam Vitade AF                                   | 1         | 4.35%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 4.35%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 4.35%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 4.35%   |
| IMC Networks Integrated Camera                              | 1         | 4.35%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 4.35%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 4.35%   |
| Chicony Integrated Camera                                   | 1         | 4.35%   |
| Chicony HP Webcam                                           | 1         | 4.35%   |
| Chicony HP HD Webcam                                        | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 4.35%   |
| Bison EasyCamera                                            | 1         | 4.35%   |
| ALi M5603 Video Camera Controller                           | 1         | 4.35%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 4.35%   |
| Acer HP Webcam-101                                          | 1         | 4.35%   |

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
| 0     | 30        | 76.92%  |
| 2     | 4         | 10.26%  |
| 1     | 4         | 10.26%  |
| 4     | 1         | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 4         | 25%     |
| Fingerprint reader       | 4         | 25%     |
| Flash memory             | 2         | 12.5%   |
| Communication controller | 2         | 12.5%   |
| Chipcard                 | 2         | 12.5%   |
| Net/wireless             | 1         | 6.25%   |
| Camera                   | 1         | 6.25%   |

