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

Total: 51

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| MSI           | U90/U100                 | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4  | [8424587178](https://linux-hardware.org/?probe=8424587178) | Jul 27, 2023 |
| ASUSTek       | K53SJ                    | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
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
| Q4OS 4 | 27        | 64.29%  |
| Q4OS 3 | 11        | 26.19%  |
| Q4OS 2 | 3         | 7.14%   |
| Q4OS 5 | 1         | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 42        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-23-amd64      | 4         | 9.52%   |
| 4.19.0-17-amd64      | 4         | 9.52%   |
| 5.10.0-21-amd64      | 3         | 7.14%   |
| 5.10.0-12-amd64      | 3         | 7.14%   |
| 5.10.0-8-amd64       | 2         | 4.76%   |
| 5.10.0-14-686-pae    | 2         | 4.76%   |
| 6.1.0-10-686-pae     | 1         | 2.38%   |
| 5.9.0-5-amd64        | 1         | 2.38%   |
| 5.6.0-1-amd64        | 1         | 2.38%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 2.38%   |
| 5.10.0-9-amd64       | 1         | 2.38%   |
| 5.10.0-8-686-pae     | 1         | 2.38%   |
| 5.10.0-21-686-pae    | 1         | 2.38%   |
| 5.10.0-20-686        | 1         | 2.38%   |
| 5.10.0-17-amd64      | 1         | 2.38%   |
| 5.10.0-15-686-pae    | 1         | 2.38%   |
| 5.10.0-13-amd64      | 1         | 2.38%   |
| 5.10.0-12-686-pae    | 1         | 2.38%   |
| 5.10.0-11-686-pae    | 1         | 2.38%   |
| 5.10.0-10-686-pae    | 1         | 2.38%   |
| 4.9.0-8-amd64        | 1         | 2.38%   |
| 4.9.0-14-686-pae     | 1         | 2.38%   |
| 4.9.0-12-686-pae     | 1         | 2.38%   |
| 4.19.0-22-amd64      | 1         | 2.38%   |
| 4.19.0-20-amd64      | 1         | 2.38%   |
| 4.19.0-17-686        | 1         | 2.38%   |
| 4.19.0-14-amd64      | 1         | 2.38%   |
| 4.19.0-13-amd64      | 1         | 2.38%   |
| 4.19.0-12-amd64      | 1         | 2.38%   |
| 4.19.0-10-amd64      | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 24        | 57.14%  |
| 4.19.0  | 11        | 26.19%  |
| 4.9.0   | 3         | 7.14%   |
| 6.1.0   | 1         | 2.38%   |
| 5.9.0   | 1         | 2.38%   |
| 5.6.0   | 1         | 2.38%   |
| 5.18.0  | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 24        | 57.14%  |
| 4.19    | 11        | 26.19%  |
| 4.9     | 3         | 7.14%   |
| 6.1     | 1         | 2.38%   |
| 5.9     | 1         | 2.38%   |
| 5.6     | 1         | 2.38%   |
| 5.18    | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 29        | 69.05%  |
| i686   | 13        | 30.95%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 22        | 52.38%  |
| trinity  | 18        | 42.86%  |
| KDE      | 1         | 2.38%   |
| Cinnamon | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 41        | 97.62%  |
| Tty  | 1         | 2.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 24        | 57.14%  |
| TDM  | 18        | 42.86%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 18        | 42.86%  |
| en_GB   | 5         | 11.9%   |
| es_ES   | 3         | 7.14%   |
| de_DE   | 3         | 7.14%   |
| it_IT   | 2         | 4.76%   |
| hu_HU   | 2         | 4.76%   |
| sv_SE   | 1         | 2.38%   |
| sl_SI   | 1         | 2.38%   |
| ru_RU   | 1         | 2.38%   |
| pl_PL   | 1         | 2.38%   |
| fr_FR   | 1         | 2.38%   |
| es_VE   | 1         | 2.38%   |
| en_SG   | 1         | 2.38%   |
| C       | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 27        | 64.29%  |
| EFI  | 15        | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 39        | 92.86%  |
| Overlay | 3         | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 26        | 61.9%   |
| GPT     | 15        | 35.71%  |
| Unknown | 1         | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 88.1%   |
| Yes       | 5         | 11.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 66.67%  |
| Yes       | 14        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 8         | 19.05%  |
| Lenovo           | 5         | 11.9%   |
| ASUSTek Computer | 5         | 11.9%   |
| Toshiba          | 4         | 9.52%   |
| Sony             | 2         | 4.76%   |
| MSI              | 2         | 4.76%   |
| Medion           | 2         | 4.76%   |
| Google           | 2         | 4.76%   |
| Visual Land      | 1         | 2.38%   |
| Qilive           | 1         | 2.38%   |
| Phoenix/SiS      | 1         | 2.38%   |
| Philco           | 1         | 2.38%   |
| Packard Bell     | 1         | 2.38%   |
| JVC              | 1         | 2.38%   |
| IBM              | 1         | 2.38%   |
| Fujitsu Siemens  | 1         | 2.38%   |
| Dell             | 1         | 2.38%   |
| Chuwi            | 1         | 2.38%   |
| AMI              | 1         | 2.38%   |
| Acer             | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba Satellite C660                  | 2         | 4.76%   |
| Visual Land Premier 10                  | 1         | 2.38%   |
| Toshiba Satellite Pro L500              | 1         | 2.38%   |
| Toshiba Satellite M70                   | 1         | 2.38%   |
| Sony VGN-P11Z_Q                         | 1         | 2.38%   |
| Sony VGN-FW21Z                          | 1         | 2.38%   |
| Qilive QW19141AMSP                      | 1         | 2.38%   |
| Phoenix/SiS M720SR                      | 1         | 2.38%   |
| Philco 14I                              | 1         | 2.38%   |
| Packard Bell EasyNote LM81              | 1         | 2.38%   |
| MSI U90/U100                            | 1         | 2.38%   |
| MSI U210                                | 1         | 2.38%   |
| Medion P6620                            | 1         | 2.38%   |
| Lenovo ThinkPad T495 20NKS0PG00         | 1         | 2.38%   |
| Lenovo ThinkPad 11e 20DAS0PS00          | 1         | 2.38%   |
| Lenovo IdeaPad 5 14IAL7 82SD            | 1         | 2.38%   |
| Lenovo IdeaPad 330S-14IKB 81F4          | 1         | 2.38%   |
| Lenovo IdeaPad 330-15IGM 81D1           | 1         | 2.38%   |
| JVC J3N                                 | 1         | 2.38%   |
| IBM ThinkPad T42 2378FVU                | 1         | 2.38%   |
| HP ProBook 6550b                        | 1         | 2.38%   |
| HP ProBook 650 G1                       | 1         | 2.38%   |
| HP ProBook 450 G2                       | 1         | 2.38%   |
| HP Presario CQ56                        | 1         | 2.38%   |
| HP OmniBook PC                          | 1         | 2.38%   |
| HP Laptop 15s-fq2xxx                    | 1         | 2.38%   |
| HP 250 G5 Notebook PC                   | 1         | 2.38%   |
| HP 2000                                 | 1         | 2.38%   |
| Google Reks                             | 1         | 2.38%   |
| Google Cave                             | 1         | 2.38%   |
| Fujitsu Siemens AMILO Pro Edition V3505 | 1         | 2.38%   |
| Dell Latitude D630                      | 1         | 2.38%   |
| Chuwi GemiBook Pro                      | 1         | 2.38%   |
| ASUS X540YA                             | 1         | 2.38%   |
| ASUS T12Eg                              | 1         | 2.38%   |
| ASUS K53SJ                              | 1         | 2.38%   |
| ASUS A6U                                | 1         | 2.38%   |
| ASUS A6JC                               | 1         | 2.38%   |
| AMI Intel                               | 1         | 2.38%   |
| Acer AO751h                             | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toshiba Satellite     | 4         | 9.52%   |
| Lenovo IdeaPad        | 3         | 7.14%   |
| HP ProBook            | 3         | 7.14%   |
| Lenovo ThinkPad       | 2         | 4.76%   |
| Visual Land Premier   | 1         | 2.38%   |
| Sony VGN-P11Z         | 1         | 2.38%   |
| Sony VGN-FW21Z        | 1         | 2.38%   |
| Qilive QW19141AMSP    | 1         | 2.38%   |
| Phoenix/SiS M720SR    | 1         | 2.38%   |
| Philco 14I            | 1         | 2.38%   |
| Packard Bell EasyNote | 1         | 2.38%   |
| MSI U90               | 1         | 2.38%   |
| MSI U210              | 1         | 2.38%   |
| Medion P6620          | 1         | 2.38%   |
| JVC J3N               | 1         | 2.38%   |
| IBM ThinkPad          | 1         | 2.38%   |
| HP Presario           | 1         | 2.38%   |
| HP OmniBook           | 1         | 2.38%   |
| HP Laptop             | 1         | 2.38%   |
| HP 250                | 1         | 2.38%   |
| HP 2000               | 1         | 2.38%   |
| Google Reks           | 1         | 2.38%   |
| Google Cave           | 1         | 2.38%   |
| Fujitsu Siemens AMILO | 1         | 2.38%   |
| Dell Latitude         | 1         | 2.38%   |
| Chuwi GemiBook        | 1         | 2.38%   |
| ASUS X540YA           | 1         | 2.38%   |
| ASUS T12Eg            | 1         | 2.38%   |
| ASUS K53SJ            | 1         | 2.38%   |
| ASUS A6U              | 1         | 2.38%   |
| ASUS A6JC             | 1         | 2.38%   |
| AMI Intel             | 1         | 2.38%   |
| Acer AO751h           | 1         | 2.38%   |
| Unknown               | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 5         | 11.9%   |
| 2009    | 5         | 11.9%   |
| 2020    | 3         | 7.14%   |
| 2022    | 2         | 4.76%   |
| 2019    | 2         | 4.76%   |
| 2018    | 2         | 4.76%   |
| 2016    | 2         | 4.76%   |
| 2014    | 2         | 4.76%   |
| 2011    | 2         | 4.76%   |
| 2008    | 2         | 4.76%   |
| 2007    | 2         | 4.76%   |
| 2006    | 2         | 4.76%   |
| 2005    | 2         | 4.76%   |
| 2004    | 2         | 4.76%   |
| Unknown | 2         | 4.76%   |
| 2023    | 1         | 2.38%   |
| 2017    | 1         | 2.38%   |
| 2015    | 1         | 2.38%   |
| 2013    | 1         | 2.38%   |
| 2012    | 1         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 42        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 39        | 92.86%  |
| Enabled  | 3         | 7.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 95.24%  |
| Yes  | 2         | 4.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 14        | 33.33%  |
| 4.01-8.0   | 8         | 19.05%  |
| 2.01-3.0   | 7         | 16.67%  |
| 1.01-2.0   | 6         | 14.29%  |
| 0.51-1.0   | 3         | 7.14%   |
| 24.01-32.0 | 1         | 2.38%   |
| 16.01-24.0 | 1         | 2.38%   |
| 8.01-16.0  | 1         | 2.38%   |
| 0.01-0.5   | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 19        | 45.24%  |
| 0.51-1.0 | 9         | 21.43%  |
| 2.01-3.0 | 8         | 19.05%  |
| 0.01-0.5 | 4         | 9.52%   |
| 3.01-4.0 | 2         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 76.19%  |
| 2      | 9         | 21.43%  |
| 3      | 1         | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 54.76%  |
| No        | 19        | 45.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 80.95%  |
| No        | 8         | 19.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 92.86%  |
| No        | 3         | 7.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 52.38%  |
| Yes       | 20        | 47.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 7         | 16.67%  |
| UK           | 5         | 11.9%   |
| Spain        | 3         | 7.14%   |
| Kenya        | 3         | 7.14%   |
| Italy        | 3         | 7.14%   |
| Germany      | 3         | 7.14%   |
| Romania      | 2         | 4.76%   |
| Poland       | 2         | 4.76%   |
| Hungary      | 2         | 4.76%   |
| Venezuela    | 1         | 2.38%   |
| Turkey       | 1         | 2.38%   |
| Sweden       | 1         | 2.38%   |
| Slovenia     | 1         | 2.38%   |
| Singapore    | 1         | 2.38%   |
| Saudi Arabia | 1         | 2.38%   |
| Russia       | 1         | 2.38%   |
| Qatar        | 1         | 2.38%   |
| France       | 1         | 2.38%   |
| Croatia      | 1         | 2.38%   |
| Brazil       | 1         | 2.38%   |
| Belarus      | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 7.14%   |
| Swindon               | 2         | 4.76%   |
| Mesa                  | 2         | 4.76%   |
| Drobeta-Turnu Severin | 2         | 4.76%   |
| Budapest              | 2         | 4.76%   |
| West Corinth          | 1         | 2.38%   |
| Tenbury Wells         | 1         | 2.38%   |
| Tellico Plains        | 1         | 2.38%   |
| Sosnowiec             | 1         | 2.38%   |
| Singapore             | 1         | 2.38%   |
| Schermbeck            | 1         | 2.38%   |
| Salsomaggiore Terme   | 1         | 2.38%   |
| Rostock               | 1         | 2.38%   |
| Rijeka                | 1         | 2.38%   |
| Puerto Cumarebo       | 1         | 2.38%   |
| Moscow                | 1         | 2.38%   |
| Mooresville           | 1         | 2.38%   |
| Moirans               | 1         | 2.38%   |
| Mogilev               | 1         | 2.38%   |
| Milano                | 1         | 2.38%   |
| Mannheim              | 1         | 2.38%   |
| Londrina              | 1         | 2.38%   |
| Ljubljana             | 1         | 2.38%   |
| Las Vegas             | 1         | 2.38%   |
| Klaudyn               | 1         | 2.38%   |
| Jönköping           | 1         | 2.38%   |
| Indianapolis          | 1         | 2.38%   |
| Gijón                | 1         | 2.38%   |
| Fulham                | 1         | 2.38%   |
| Doha                  | 1         | 2.38%   |
| Dammam                | 1         | 2.38%   |
| Carterton             | 1         | 2.38%   |
| Calvecchia            | 1         | 2.38%   |
| Barcelona             | 1         | 2.38%   |
| Alicante              | 1         | 2.38%   |
| Adana                 | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 6         | 6      | 13.04%  |
| WDC                 | 5         | 5      | 10.87%  |
| Samsung Electronics | 5         | 5      | 10.87%  |
| Kingston            | 5         | 5      | 10.87%  |
| Seagate             | 4         | 4      | 8.7%    |
| Toshiba             | 3         | 3      | 6.52%   |
| Hitachi             | 3         | 3      | 6.52%   |
| SanDisk             | 2         | 2      | 4.35%   |
| KESU                | 2         | 2      | 4.35%   |
| HGST                | 2         | 2      | 4.35%   |
| China               | 2         | 2      | 4.35%   |
| Silicon Motion      | 1         | 1      | 2.17%   |
| Phison              | 1         | 1      | 2.17%   |
| KingSpec            | 1         | 1      | 2.17%   |
| KBG40ZNV            | 1         | 1      | 2.17%   |
| Fujitsu             | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |
| Unknown             | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 2         | 4.35%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 4.35%   |
| KESU USB 3.1 256GB                   | 2         | 4.35%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 2.17%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 2.17%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 2.17%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 2.17%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 2.17%   |
| Unknown USDU1  32GB                  | 1         | 2.17%   |
| Unknown SLD64G  64GB                 | 1         | 2.17%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 2.17%   |
| Unknown MMC Card  64GB               | 1         | 2.17%   |
| Unknown HAG2e  16GB                  | 1         | 2.17%   |
| Unknown 064G38  64GB                 | 1         | 2.17%   |
| Toshiba MK8025GAS 80GB               | 1         | 2.17%   |
| Toshiba MK6028GAL 64GB               | 1         | 2.17%   |
| Toshiba MK3252GSX 320GB              | 1         | 2.17%   |
| Silicon Motion NVME SSD 512GB        | 1         | 2.17%   |
| Seagate ST96812AS 64GB               | 1         | 2.17%   |
| Seagate ST9500325AS 500GB            | 1         | 2.17%   |
| Seagate ST9120822AS 120GB            | 1         | 2.17%   |
| Seagate Backup+ SL 1TB               | 1         | 2.17%   |
| SanDisk SDCFX-032G SSD               | 1         | 2.17%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 2.17%   |
| Samsung MZALQ256HBJD-00BL1 256GB     | 1         | 2.17%   |
| Samsung MZAL4512HBLU-00BL2 512GB     | 1         | 2.17%   |
| Samsung AWMB3R  16GB                 | 1         | 2.17%   |
| Phison APS-SE20G-1T                  | 1         | 2.17%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 2.17%   |
| Kingston SV300S37A240G 240GB SSD     | 1         | 2.17%   |
| Kingston SUV400S37120G 120GB SSD     | 1         | 2.17%   |
| KingSpec KSD-PA25.6-064MS 64GB SSD   | 1         | 2.17%   |
| KBG40ZNV 256G KIOXIA                 | 1         | 2.17%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 2.17%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 2.17%   |
| Hitachi DK23CA-20 20GB               | 1         | 2.17%   |
| HGST HTS725050A7E630 500GB           | 1         | 2.17%   |
| HGST HTS541075A9E680 752GB           | 1         | 2.17%   |
| Fujitsu MHY2080BH 80GB               | 1         | 2.17%   |
| China SSD128GBS800                   | 1         | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 23.53%  |
| Toshiba | 3         | 3      | 17.65%  |
| Seagate | 3         | 3      | 17.65%  |
| Hitachi | 3         | 3      | 17.65%  |
| HGST    | 2         | 2      | 11.76%  |
| Unknown | 1         | 1      | 5.88%   |
| Fujitsu | 1         | 1      | 5.88%   |

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
| HDD     | 16        | 17     | 37.21%  |
| SSD     | 14        | 14     | 32.56%  |
| MMC     | 6         | 6      | 13.95%  |
| NVMe    | 4         | 6      | 9.3%    |
| Unknown | 3         | 3      | 6.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 30     | 66.67%  |
| MMC  | 6         | 6      | 13.33%  |
| SAS  | 5         | 5      | 11.11%  |
| NVMe | 4         | 5      | 8.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 29     | 93.33%  |
| 0.51-1.0   | 2         | 2      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 23.81%  |
| 51-100     | 8         | 19.05%  |
| 251-500    | 7         | 16.67%  |
| 1-20       | 7         | 16.67%  |
| 21-50      | 5         | 11.9%   |
| 1001-2000  | 2         | 4.76%   |
| 501-1000   | 2         | 4.76%   |
| Unknown    | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 29        | 69.05%  |
| 21-50    | 7         | 16.67%  |
| 251-500  | 2         | 4.76%   |
| 51-100   | 2         | 4.76%   |
| 501-1000 | 1         | 2.38%   |
| Unknown  | 1         | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 10%     |
| Toshiba MK3252GSX 320GB       | 1         | 1      | 10%     |
| Seagate ST9500325AS 500GB     | 1         | 1      | 10%     |
| Seagate ST9120822AS 120GB     | 1         | 1      | 10%     |
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


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 30%     |
| Seagate | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| Toshiba | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 30%     |
| Seagate | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| Toshiba | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 23        | 25     | 53.49%  |
| Detected | 10        | 11     | 23.26%  |
| Malfunc  | 10        | 10     | 23.26%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 28        | 68.29%  |
| AMD                              | 6         | 14.63%  |
| Silicon Integrated Systems [SiS] | 2         | 4.88%   |
| Samsung Electronics              | 2         | 4.88%   |
| Silicon Motion                   | 1         | 2.44%   |
| SanDisk                          | 1         | 2.44%   |
| Phison Electronics               | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 8.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 6.38%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 6.38%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 4.26%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 4.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 4.26%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 4.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 4.26%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 4.26%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 2.13%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 2.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.13%   |
| Samsung NVMe SSD Controller PM9B1                                                | 1         | 2.13%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 2.13%   |
| Phison E12 NVMe Controller                                                       | 1         | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.13%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 2.13%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 2.13%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 2.13%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 25        | 58.14%  |
| IDE  | 13        | 30.23%  |
| NVMe | 4         | 9.3%    |
| RAID | 1         | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 80.95%  |
| AMD    | 8         | 19.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz               | 2         | 4.76%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 4.76%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 4.76%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 4.76%   |
| Intel Pentium M processor 1000MHz               | 1         | 2.38%   |
| Intel Pentium III (Coppermine)                  | 1         | 2.38%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2.38%   |
| Intel Pentium CPU 4415U @ 2.30GHz               | 1         | 2.38%   |
| Intel Genuine CPU T2050 @ 1.60GHz               | 1         | 2.38%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 2.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.38%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 2.38%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2.38%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 2.38%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 2.38%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 2.38%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.38%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2.38%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2.38%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.38%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.38%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.38%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2.38%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2.38%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.38%   |
| Intel Atom CPU Z3735G @ 1.33GHz                 | 1         | 2.38%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 2.38%   |
| Intel 12th Gen Core i5-1240P                    | 1         | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.38%   |
| AMD V120 Processor                              | 1         | 2.38%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.38%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 2.38%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.38%   |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2.38%   |
| AMD Athlon Neo Processor MV-40                  | 1         | 2.38%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.38%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G   | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 6         | 14.29%  |
| Intel Celeron           | 6         | 14.29%  |
| Intel Atom              | 5         | 11.9%   |
| Intel Pentium M         | 3         | 7.14%   |
| Intel Core i5           | 3         | 7.14%   |
| Intel Core i3           | 3         | 7.14%   |
| Other                   | 2         | 4.76%   |
| Intel Pentium III       | 1         | 2.38%   |
| Intel Pentium Dual-Core | 1         | 2.38%   |
| Intel Pentium           | 1         | 2.38%   |
| Intel Genuine           | 1         | 2.38%   |
| Intel Core m3           | 1         | 2.38%   |
| Intel Core 2            | 1         | 2.38%   |
| AMD V120                | 1         | 2.38%   |
| AMD Ryzen 7 PRO         | 1         | 2.38%   |
| AMD Mobile Sempron      | 1         | 2.38%   |
| AMD E                   | 1         | 2.38%   |
| AMD C-70                | 1         | 2.38%   |
| AMD Athlon Neo          | 1         | 2.38%   |
| AMD A8                  | 1         | 2.38%   |
| AMD A4                  | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 54.76%  |
| 1      | 10        | 23.81%  |
| 4      | 8         | 19.05%  |
| 12     | 1         | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 69.05%  |
| 2      | 13        | 30.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 78.57%  |
| 32-bit         | 9         | 21.43%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 9.52%   |
| 0x206a7    | 3         | 7.14%   |
| 0x1067a    | 3         | 7.14%   |
| 0x706a1    | 2         | 4.76%   |
| 0x6fd      | 2         | 4.76%   |
| 0x406c4    | 2         | 4.76%   |
| 0x30678    | 2         | 4.76%   |
| 0x106c2    | 2         | 4.76%   |
| 0x906a3    | 1         | 2.38%   |
| 0x806e9    | 1         | 2.38%   |
| 0x806c1    | 1         | 2.38%   |
| 0x706a8    | 1         | 2.38%   |
| 0x6fb      | 1         | 2.38%   |
| 0x6f6      | 1         | 2.38%   |
| 0x6e8      | 1         | 2.38%   |
| 0x6d8      | 1         | 2.38%   |
| 0x6d6      | 1         | 2.38%   |
| 0x695      | 1         | 2.38%   |
| 0x68a      | 1         | 2.38%   |
| 0x406e3    | 1         | 2.38%   |
| 0x40651    | 1         | 2.38%   |
| 0x306c3    | 1         | 2.38%   |
| 0x20655    | 1         | 2.38%   |
| 0x10676    | 1         | 2.38%   |
| 0x08108102 | 1         | 2.38%   |
| 0x07030106 | 1         | 2.38%   |
| 0x06006705 | 1         | 2.38%   |
| 0x05000119 | 1         | 2.38%   |
| 0x0500010d | 1         | 2.38%   |
| 0x010000c8 | 1         | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 5         | 11.9%   |
| P6            | 5         | 11.9%   |
| Penryn        | 4         | 9.52%   |
| Core          | 4         | 9.52%   |
| SandyBridge   | 3         | 7.14%   |
| Goldmont plus | 3         | 7.14%   |
| Bonnell       | 3         | 7.14%   |
| K8 Hammer     | 2         | 4.76%   |
| Haswell       | 2         | 4.76%   |
| Bobcat        | 2         | 4.76%   |
| Zen+          | 1         | 2.38%   |
| Westmere      | 1         | 2.38%   |
| TigerLake     | 1         | 2.38%   |
| Skylake       | 1         | 2.38%   |
| Puma          | 1         | 2.38%   |
| KabyLake      | 1         | 2.38%   |
| K10           | 1         | 2.38%   |
| Excavator     | 1         | 2.38%   |
| Unknown       | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 59.09%  |
| AMD                              | 12        | 27.27%  |
| Nvidia                           | 3         | 6.82%   |
| Silicon Integrated Systems [SiS] | 2         | 4.55%   |
| S3 Graphics                      | 1         | 2.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 6.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 3         | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 6.25%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 4.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 2         | 4.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 2         | 4.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 2         | 4.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 2         | 4.17%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 2.08%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 2.08%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 2.08%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 2.08%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 2.08%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 2.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 2.08%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 1         | 2.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 2.08%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 2.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 2.08%   |
| Intel HD Graphics 610                                                                      | 1         | 2.08%   |
| Intel HD Graphics 515                                                                      | 1         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 2.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                                          | 1         | 2.08%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 1         | 2.08%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 2.08%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 2.08%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 2.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 2.08%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]                | 1         | 2.08%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                           | 1         | 2.08%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                    | 1         | 2.08%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 1         | 2.08%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 2.08%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 2.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 22        | 52.38%  |
| 1 x AMD         | 11        | 26.19%  |
| 1 x SiS         | 2         | 4.76%   |
| 1 x Nvidia      | 2         | 4.76%   |
| Other           | 1         | 2.38%   |
| 2 x Intel       | 1         | 2.38%   |
| 1 x S3 Graphics | 1         | 2.38%   |
| Intel + Nvidia  | 1         | 2.38%   |
| Intel + AMD     | 1         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 85.71%  |
| Unknown     | 4         | 9.52%   |
| Proprietary | 2         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 66.67%  |
| 0.01-0.5   | 12        | 28.57%  |
| 1.01-2.0   | 2         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 8         | 22.22%  |
| Samsung Electronics | 7         | 19.44%  |
| Chimei Innolux      | 7         | 19.44%  |
| LG Display          | 5         | 13.89%  |
| HannStar            | 2         | 5.56%   |
| CPT                 | 2         | 5.56%   |
| MQP                 | 1         | 2.78%   |
| LG Philips          | 1         | 2.78%   |
| Hewlett-Packard     | 1         | 2.78%   |
| Dell                | 1         | 2.78%   |
| BOE                 | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 5.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 5.56%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch   | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 890x500mm 40.2-inch | 1         | 2.78%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                  | 1         | 2.78%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch           | 1         | 2.78%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch           | 1         | 2.78%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 2.78%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch            | 1         | 2.78%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 2.78%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch              | 1         | 2.78%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                      | 1         | 2.78%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                  | 1         | 2.78%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                  | 1         | 2.78%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch       | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch       | 1         | 2.78%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch         | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 14        | 38.89%  |
| 1920x1080 (FHD)   | 10        | 27.78%  |
| 1280x800 (WXGA)   | 5         | 13.89%  |
| 1600x900 (HD+)    | 3         | 8.33%   |
| 800x600           | 1         | 2.78%   |
| 2160x1440         | 1         | 2.78%   |
| 1920x1200 (WUXGA) | 1         | 2.78%   |
| 1024x600          | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 47.22%  |
| 14     | 3         | 8.33%   |
| 13     | 3         | 8.33%   |
| 12     | 3         | 8.33%   |
| 11     | 3         | 8.33%   |
| 46     | 1         | 2.78%   |
| 40     | 1         | 2.78%   |
| 24     | 1         | 2.78%   |
| 23     | 1         | 2.78%   |
| 18     | 1         | 2.78%   |
| 17     | 1         | 2.78%   |
| 10     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 60%     |
| 201-300     | 7         | 20%     |
| 351-400     | 3         | 8.57%   |
| 501-600     | 2         | 5.71%   |
| 801-900     | 1         | 2.86%   |
| 1001-1500   | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 76.47%  |
| 16/10 | 6         | 17.65%  |
| 4/3   | 1         | 2.94%   |
| 3/2   | 1         | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 47.22%  |
| 81-90          | 6         | 16.67%  |
| 51-60          | 3         | 8.33%   |
| 61-70          | 2         | 5.56%   |
| 501-1000       | 2         | 5.56%   |
| 71-80          | 1         | 2.78%   |
| 41-50          | 1         | 2.78%   |
| 251-300        | 1         | 2.78%   |
| 201-250        | 1         | 2.78%   |
| 141-150        | 1         | 2.78%   |
| 121-130        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 16        | 44.44%  |
| 51-100  | 9         | 25%     |
| 121-160 | 7         | 19.44%  |
| 161-240 | 3         | 8.33%   |
| 1-50    | 1         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 85.71%  |
| 2     | 3         | 7.14%   |
| 0     | 3         | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 25        | 35.21%  |
| Intel                            | 16        | 22.54%  |
| Qualcomm Atheros                 | 14        | 19.72%  |
| Broadcom                         | 4         | 5.63%   |
| Marvell Technology Group         | 3         | 4.23%   |
| Silicon Integrated Systems [SiS] | 2         | 2.82%   |
| Xiaomi                           | 1         | 1.41%   |
| Ralink Technology                | 1         | 1.41%   |
| Motorola PCS                     | 1         | 1.41%   |
| LG Electronics                   | 1         | 1.41%   |
| JMicron Technology               | 1         | 1.41%   |
| Broadcom Limited                 | 1         | 1.41%   |
| Accton Technology                | 1         | 1.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 11.39%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 8         | 10.13%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 5.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 5.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 3.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 3.8%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 3.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 2.53%   |
| Intel Wireless 7265                                                     | 2         | 2.53%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.53%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.27%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.27%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.27%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.27%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 1.27%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.27%   |
| Motorola PCS XT1032                                                     | 1         | 1.27%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 1.27%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.27%   |
| Intel Wireless 3165                                                     | 1         | 1.27%   |
| Intel WiFi Link 5100                                                    | 1         | 1.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.27%   |
| Intel Ethernet Connection I217-V                                        | 1         | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.27%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 1.27%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 1.27%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                      | 1         | 1.27%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                | 1         | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 14        | 35%     |
| Intel                 | 14        | 35%     |
| Realtek Semiconductor | 8         | 20%     |
| Broadcom              | 2         | 5%      |
| Ralink Technology     | 1         | 2.5%    |
| Broadcom Limited      | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 10%     |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 10%     |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 7.5%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 7.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 5%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 5%      |
| Intel Wireless 7265                                                         | 2         | 5%      |
| Intel Wi-Fi 6 AX200                                                         | 2         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 2.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 2.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 2.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 2.5%    |
| Realtek RTL8187SE Wireless LAN Controller                                   | 1         | 2.5%    |
| Ralink RT5370 Wireless Adapter                                              | 1         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 2.5%    |
| Intel Wireless 3165                                                         | 1         | 2.5%    |
| Intel WiFi Link 5100                                                        | 1         | 2.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 2.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.5%    |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2.5%    |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 21        | 60%     |
| Marvell Technology Group         | 3         | 8.57%   |
| Intel                            | 3         | 8.57%   |
| Broadcom                         | 2         | 5.71%   |
| Xiaomi                           | 1         | 2.86%   |
| Silicon Integrated Systems [SiS] | 1         | 2.86%   |
| Motorola PCS                     | 1         | 2.86%   |
| LG Electronics                   | 1         | 2.86%   |
| JMicron Technology               | 1         | 2.86%   |
| Accton Technology                | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 25.71%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 22.86%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 8.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 5.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.86%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.86%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 2.86%   |
| Motorola PCS XT1032                                               | 1         | 2.86%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.86%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.86%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.86%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.86%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.86%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 2.86%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 2.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.86%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 50.65%  |
| Ethernet | 34        | 44.16%  |
| Modem    | 4         | 5.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 66.67%  |
| Ethernet | 14        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 66.67%  |
| 1     | 11        | 26.19%  |
| 0     | 2         | 4.76%   |
| 3     | 1         | 2.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 88.1%   |
| Yes  | 5         | 11.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 6         | 30%     |
| Intel                           | 6         | 30%     |
| Realtek Semiconductor           | 3         | 15%     |
| Alps Electric                   | 2         | 10%     |
| Toshiba                         | 1         | 5%      |
| Hewlett-Packard                 | 1         | 5%      |
| ASUSTek Computer                | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth              | 4         | 20%     |
| Realtek Bluetooth Radio                        | 3         | 15%     |
| Intel Bluetooth wireless interface             | 3         | 15%     |
| Qualcomm Atheros  Bluetooth Device             | 2         | 10%     |
| Intel AX200 Bluetooth                          | 2         | 10%     |
| Alps Electric BCM2046 Bluetooth Device         | 2         | 10%     |
| Toshiba Askey for                              | 1         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 5%      |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 5%      |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 29        | 69.05%  |
| AMD                              | 10        | 23.81%  |
| Silicon Integrated Systems [SiS] | 2         | 4.76%   |
| ESS Technology                   | 1         | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 7.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 5.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 5.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 5.88%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 3.92%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 3.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 3.92%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 3.92%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 3.92%   |
| AMD FCH Azalia Controller                                                                         | 2         | 3.92%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 1.96%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.96%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.96%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.96%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.96%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.96%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.96%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.96%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 16        | 34.78%  |
| Samsung Electronics | 11        | 23.91%  |
| SK hynix            | 5         | 10.87%  |
| Kingston            | 4         | 8.7%    |
| Unknown (ABCD)      | 2         | 4.35%   |
| Micron Technology   | 2         | 4.35%   |
| Elpida              | 2         | 4.35%   |
| Toshiba             | 1         | 2.17%   |
| Team                | 1         | 2.17%   |
| Ramaxel Technology  | 1         | 2.17%   |
| A-DATA Technology   | 1         | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 12%     |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 6%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 4%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 4%      |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 2%      |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 2%      |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 2%      |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 2%      |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 2%      |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 2%      |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 2%      |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 2%      |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 2%      |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 2%      |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 2%      |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s            | 1         | 2%      |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 2%      |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 2%      |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 2%      |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2%      |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 2%      |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 2%      |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2%      |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 2%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2%      |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 2%      |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 2%      |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 2%      |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 2%      |
| Micron RAM MT52L256M32D1PF-10 2GB LPDDR3 1867MT/s                | 1         | 2%      |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 2%      |
| Kingston RAM Module 2GB SODIMM DDR 667MT/s                       | 1         | 2%      |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 2%      |
| Kingston RAM HP16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 2%      |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 2%      |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 2%      |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s            | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 12        | 29.27%  |
| DDR2   | 10        | 24.39%  |
| DDR4   | 6         | 14.63%  |
| SDRAM  | 4         | 9.76%   |
| DDR    | 4         | 9.76%   |
| LPDDR4 | 2         | 4.88%   |
| LPDDR3 | 2         | 4.88%   |
| DRAM   | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 90%     |
| Unknown      | 2         | 5%      |
| Row Of Chips | 1         | 2.5%    |
| DIMM         | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 16        | 36.36%  |
| 4096  | 13        | 29.55%  |
| 1024  | 6         | 13.64%  |
| 8192  | 5         | 11.36%  |
| 512   | 2         | 4.55%   |
| 16384 | 1         | 2.27%   |
| 256   | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 27.91%  |
| 2400    | 5         | 11.63%  |
| 1600    | 5         | 11.63%  |
| 1334    | 4         | 9.3%    |
| 3200    | 2         | 4.65%   |
| 2667    | 2         | 4.65%   |
| 1867    | 2         | 4.65%   |
| 1333    | 2         | 4.65%   |
| 1067    | 2         | 4.65%   |
| 4199    | 1         | 2.33%   |
| 3266    | 1         | 2.33%   |
| 2048    | 1         | 2.33%   |
| 1066    | 1         | 2.33%   |
| 800     | 1         | 2.33%   |
| 667     | 1         | 2.33%   |
| 266     | 1         | 2.33%   |

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
| IMC Networks                           | 4         | 16%     |
| Chicony Electronics                    | 4         | 16%     |
| Cheng Uei Precision Industry (Foxlink) | 3         | 12%     |
| Ricoh                                  | 2         | 8%      |
| Microdia                               | 2         | 8%      |
| Acer                                   | 2         | 8%      |
| Suyin                                  | 1         | 4%      |
| Silicon Motion                         | 1         | 4%      |
| Realtek Semiconductor                  | 1         | 4%      |
| Quanta                                 | 1         | 4%      |
| Luxvisions Innotech Limited            | 1         | 4%      |
| Bison Electronics                      | 1         | 4%      |
| ALi                                    | 1         | 4%      |
| Alcor Micro                            | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 4%      |
| Silicon Motion 300k Pixel Camera                            | 1         | 4%      |
| Ricoh Sony Visual Communication Camera                      | 1         | 4%      |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 4%      |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 4%      |
| Quanta Chromebook HD Camera                                 | 1         | 4%      |
| Microdia Webcam Vitade AF                                   | 1         | 4%      |
| Microdia Sonix USB 2.0 Camera                               | 1         | 4%      |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 4%      |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 4%      |
| IMC Networks USB 2.0 Camera                                 | 1         | 4%      |
| IMC Networks Integrated Camera                              | 1         | 4%      |
| IMC Networks HP TrueVision HD Camera                        | 1         | 4%      |
| Chicony USB2.0 UVC WebCam                                   | 1         | 4%      |
| Chicony Integrated Camera                                   | 1         | 4%      |
| Chicony HP Webcam                                           | 1         | 4%      |
| Chicony HP HD Webcam                                        | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 4%      |
| Bison EasyCamera                                            | 1         | 4%      |
| ALi M5603 Video Camera Controller                           | 1         | 4%      |
| Alcor Micro USB 2.0 Camera                                  | 1         | 4%      |
| Acer Integrated Camera                                      | 1         | 4%      |
| Acer HP Webcam-101                                          | 1         | 4%      |

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
| 0     | 31        | 73.81%  |
| 1     | 6         | 14.29%  |
| 2     | 4         | 9.52%   |
| 4     | 1         | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 6         | 33.33%  |
| Fingerprint reader       | 4         | 22.22%  |
| Flash memory             | 2         | 11.11%  |
| Communication controller | 2         | 11.11%  |
| Chipcard                 | 2         | 11.11%  |
| Net/wireless             | 1         | 5.56%   |
| Camera                   | 1         | 5.56%   |

