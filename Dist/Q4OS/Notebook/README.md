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

Total: 54

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBook4,1               | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Acer          | Aspire one               | [d040844540](https://linux-hardware.org/?probe=d040844540) | Sep 27, 2023 |
| Acer          | Aspire 1700              | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
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
| Q4OS 4 | 27        | 60%     |
| Q4OS 3 | 11        | 24.44%  |
| Q4OS 5 | 4         | 8.89%   |
| Q4OS 2 | 3         | 6.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 45        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-23-amd64      | 4         | 8.89%   |
| 4.19.0-17-amd64      | 4         | 8.89%   |
| 5.10.0-21-amd64      | 3         | 6.67%   |
| 5.10.0-12-amd64      | 3         | 6.67%   |
| 5.10.0-8-amd64       | 2         | 4.44%   |
| 5.10.0-14-686-pae    | 2         | 4.44%   |
| 6.1.0-12-amd64       | 1         | 2.22%   |
| 6.1.0-12-686-pae     | 1         | 2.22%   |
| 6.1.0-11-686-pae     | 1         | 2.22%   |
| 6.1.0-10-686-pae     | 1         | 2.22%   |
| 5.9.0-5-amd64        | 1         | 2.22%   |
| 5.6.0-1-amd64        | 1         | 2.22%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 2.22%   |
| 5.10.0-9-amd64       | 1         | 2.22%   |
| 5.10.0-8-686-pae     | 1         | 2.22%   |
| 5.10.0-21-686-pae    | 1         | 2.22%   |
| 5.10.0-20-686        | 1         | 2.22%   |
| 5.10.0-17-amd64      | 1         | 2.22%   |
| 5.10.0-15-686-pae    | 1         | 2.22%   |
| 5.10.0-13-amd64      | 1         | 2.22%   |
| 5.10.0-12-686-pae    | 1         | 2.22%   |
| 5.10.0-11-686-pae    | 1         | 2.22%   |
| 5.10.0-10-686-pae    | 1         | 2.22%   |
| 4.9.0-8-amd64        | 1         | 2.22%   |
| 4.9.0-14-686-pae     | 1         | 2.22%   |
| 4.9.0-12-686-pae     | 1         | 2.22%   |
| 4.19.0-22-amd64      | 1         | 2.22%   |
| 4.19.0-20-amd64      | 1         | 2.22%   |
| 4.19.0-17-686        | 1         | 2.22%   |
| 4.19.0-14-amd64      | 1         | 2.22%   |
| 4.19.0-13-amd64      | 1         | 2.22%   |
| 4.19.0-12-amd64      | 1         | 2.22%   |
| 4.19.0-10-amd64      | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 24        | 53.33%  |
| 4.19.0  | 11        | 24.44%  |
| 6.1.0   | 4         | 8.89%   |
| 4.9.0   | 3         | 6.67%   |
| 5.9.0   | 1         | 2.22%   |
| 5.6.0   | 1         | 2.22%   |
| 5.18.0  | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 24        | 53.33%  |
| 4.19    | 11        | 24.44%  |
| 6.1     | 4         | 8.89%   |
| 4.9     | 3         | 6.67%   |
| 5.9     | 1         | 2.22%   |
| 5.6     | 1         | 2.22%   |
| 5.18    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 30        | 66.67%  |
| i686   | 15        | 33.33%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 23        | 51.11%  |
| trinity  | 20        | 44.44%  |
| KDE      | 1         | 2.22%   |
| Cinnamon | 1         | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 44        | 97.78%  |
| Tty  | 1         | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 25        | 55.56%  |
| TDM  | 20        | 44.44%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 20        | 44.44%  |
| en_GB   | 5         | 11.11%  |
| it_IT   | 3         | 6.67%   |
| es_ES   | 3         | 6.67%   |
| de_DE   | 3         | 6.67%   |
| hu_HU   | 2         | 4.44%   |
| sv_SE   | 1         | 2.22%   |
| sl_SI   | 1         | 2.22%   |
| ru_RU   | 1         | 2.22%   |
| pl_PL   | 1         | 2.22%   |
| fr_FR   | 1         | 2.22%   |
| es_VE   | 1         | 2.22%   |
| en_SG   | 1         | 2.22%   |
| C       | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 29        | 64.44%  |
| EFI  | 16        | 35.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 42        | 93.33%  |
| Overlay | 3         | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 28        | 62.22%  |
| GPT     | 16        | 35.56%  |
| Unknown | 1         | 2.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 88.89%  |
| Yes       | 5         | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 68.89%  |
| Yes       | 14        | 31.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 8         | 17.78%  |
| Lenovo           | 5         | 11.11%  |
| ASUSTek Computer | 5         | 11.11%  |
| Toshiba          | 4         | 8.89%   |
| Acer             | 3         | 6.67%   |
| Sony             | 2         | 4.44%   |
| MSI              | 2         | 4.44%   |
| Medion           | 2         | 4.44%   |
| Google           | 2         | 4.44%   |
| Visual Land      | 1         | 2.22%   |
| Qilive           | 1         | 2.22%   |
| Phoenix/SiS      | 1         | 2.22%   |
| Philco           | 1         | 2.22%   |
| Packard Bell     | 1         | 2.22%   |
| JVC              | 1         | 2.22%   |
| IBM              | 1         | 2.22%   |
| Fujitsu Siemens  | 1         | 2.22%   |
| Dell             | 1         | 2.22%   |
| Chuwi            | 1         | 2.22%   |
| Apple            | 1         | 2.22%   |
| AMI              | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba Satellite C660                  | 2         | 4.44%   |
| Visual Land Premier 10                  | 1         | 2.22%   |
| Toshiba Satellite Pro L500              | 1         | 2.22%   |
| Toshiba Satellite M70                   | 1         | 2.22%   |
| Sony VGN-P11Z_Q                         | 1         | 2.22%   |
| Sony VGN-FW21Z                          | 1         | 2.22%   |
| Qilive QW19141AMSP                      | 1         | 2.22%   |
| Phoenix/SiS M720SR                      | 1         | 2.22%   |
| Philco 14I                              | 1         | 2.22%   |
| Packard Bell EasyNote LM81              | 1         | 2.22%   |
| MSI U90/U100                            | 1         | 2.22%   |
| MSI U210                                | 1         | 2.22%   |
| Medion P6620                            | 1         | 2.22%   |
| Lenovo ThinkPad T495 20NKS0PG00         | 1         | 2.22%   |
| Lenovo ThinkPad 11e 20DAS0PS00          | 1         | 2.22%   |
| Lenovo IdeaPad 5 14IAL7 82SD            | 1         | 2.22%   |
| Lenovo IdeaPad 330S-14IKB 81F4          | 1         | 2.22%   |
| Lenovo IdeaPad 330-15IGM 81D1           | 1         | 2.22%   |
| JVC J3N                                 | 1         | 2.22%   |
| IBM ThinkPad T42 2378FVU                | 1         | 2.22%   |
| HP ProBook 6550b                        | 1         | 2.22%   |
| HP ProBook 650 G1                       | 1         | 2.22%   |
| HP ProBook 450 G2                       | 1         | 2.22%   |
| HP Presario CQ56                        | 1         | 2.22%   |
| HP OmniBook PC                          | 1         | 2.22%   |
| HP Laptop 15s-fq2xxx                    | 1         | 2.22%   |
| HP 250 G5 Notebook PC                   | 1         | 2.22%   |
| HP 2000                                 | 1         | 2.22%   |
| Google Reks                             | 1         | 2.22%   |
| Google Cave                             | 1         | 2.22%   |
| Fujitsu Siemens AMILO Pro Edition V3505 | 1         | 2.22%   |
| Dell Latitude D630                      | 1         | 2.22%   |
| Chuwi GemiBook Pro                      | 1         | 2.22%   |
| ASUS X540YA                             | 1         | 2.22%   |
| ASUS T12Eg                              | 1         | 2.22%   |
| ASUS K53SJ                              | 1         | 2.22%   |
| ASUS A6U                                | 1         | 2.22%   |
| ASUS A6JC                               | 1         | 2.22%   |
| Apple MacBook4,1                        | 1         | 2.22%   |
| AMI Intel                               | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toshiba Satellite     | 4         | 8.89%   |
| Lenovo IdeaPad        | 3         | 6.67%   |
| HP ProBook            | 3         | 6.67%   |
| Lenovo ThinkPad       | 2         | 4.44%   |
| Acer Aspire           | 2         | 4.44%   |
| Visual Land Premier   | 1         | 2.22%   |
| Sony VGN-P11Z         | 1         | 2.22%   |
| Sony VGN-FW21Z        | 1         | 2.22%   |
| Qilive QW19141AMSP    | 1         | 2.22%   |
| Phoenix/SiS M720SR    | 1         | 2.22%   |
| Philco 14I            | 1         | 2.22%   |
| Packard Bell EasyNote | 1         | 2.22%   |
| MSI U90               | 1         | 2.22%   |
| MSI U210              | 1         | 2.22%   |
| Medion P6620          | 1         | 2.22%   |
| JVC J3N               | 1         | 2.22%   |
| IBM ThinkPad          | 1         | 2.22%   |
| HP Presario           | 1         | 2.22%   |
| HP OmniBook           | 1         | 2.22%   |
| HP Laptop             | 1         | 2.22%   |
| HP 250                | 1         | 2.22%   |
| HP 2000               | 1         | 2.22%   |
| Google Reks           | 1         | 2.22%   |
| Google Cave           | 1         | 2.22%   |
| Fujitsu Siemens AMILO | 1         | 2.22%   |
| Dell Latitude         | 1         | 2.22%   |
| Chuwi GemiBook        | 1         | 2.22%   |
| ASUS X540YA           | 1         | 2.22%   |
| ASUS T12Eg            | 1         | 2.22%   |
| ASUS K53SJ            | 1         | 2.22%   |
| ASUS A6U              | 1         | 2.22%   |
| ASUS A6JC             | 1         | 2.22%   |
| Apple MacBook4        | 1         | 2.22%   |
| AMI Intel             | 1         | 2.22%   |
| Acer AO751h           | 1         | 2.22%   |
| Unknown               | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 6         | 13.33%  |
| 2010    | 5         | 11.11%  |
| 2020    | 3         | 6.67%   |
| 2008    | 3         | 6.67%   |
| 2022    | 2         | 4.44%   |
| 2019    | 2         | 4.44%   |
| 2018    | 2         | 4.44%   |
| 2016    | 2         | 4.44%   |
| 2014    | 2         | 4.44%   |
| 2011    | 2         | 4.44%   |
| 2007    | 2         | 4.44%   |
| 2006    | 2         | 4.44%   |
| 2005    | 2         | 4.44%   |
| 2004    | 2         | 4.44%   |
| Unknown | 2         | 4.44%   |
| 2023    | 1         | 2.22%   |
| 2017    | 1         | 2.22%   |
| 2015    | 1         | 2.22%   |
| 2013    | 1         | 2.22%   |
| 2012    | 1         | 2.22%   |
| 2003    | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 45        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 42        | 93.33%  |
| Enabled  | 3         | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 95.56%  |
| Yes  | 2         | 4.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 15        | 33.33%  |
| 4.01-8.0   | 8         | 17.78%  |
| 2.01-3.0   | 8         | 17.78%  |
| 1.01-2.0   | 6         | 13.33%  |
| 0.51-1.0   | 3         | 6.67%   |
| 0.01-0.5   | 2         | 4.44%   |
| 24.01-32.0 | 1         | 2.22%   |
| 16.01-24.0 | 1         | 2.22%   |
| 8.01-16.0  | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 20        | 44.44%  |
| 0.51-1.0 | 10        | 22.22%  |
| 2.01-3.0 | 8         | 17.78%  |
| 0.01-0.5 | 5         | 11.11%  |
| 3.01-4.0 | 2         | 4.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 77.78%  |
| 2      | 9         | 20%     |
| 3      | 1         | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 55.56%  |
| No        | 20        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 82.22%  |
| No        | 8         | 17.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 93.33%  |
| No        | 3         | 6.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 53.33%  |
| Yes       | 21        | 46.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 8         | 17.78%  |
| UK           | 5         | 11.11%  |
| Italy        | 4         | 8.89%   |
| Spain        | 3         | 6.67%   |
| Kenya        | 3         | 6.67%   |
| Germany      | 3         | 6.67%   |
| Romania      | 2         | 4.44%   |
| Poland       | 2         | 4.44%   |
| Hungary      | 2         | 4.44%   |
| Venezuela    | 1         | 2.22%   |
| Turkey       | 1         | 2.22%   |
| Sweden       | 1         | 2.22%   |
| Slovenia     | 1         | 2.22%   |
| Singapore    | 1         | 2.22%   |
| Saudi Arabia | 1         | 2.22%   |
| Russia       | 1         | 2.22%   |
| Qatar        | 1         | 2.22%   |
| Mexico       | 1         | 2.22%   |
| France       | 1         | 2.22%   |
| Croatia      | 1         | 2.22%   |
| Brazil       | 1         | 2.22%   |
| Belarus      | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 6.67%   |
| Swindon               | 2         | 4.44%   |
| Mesa                  | 2         | 4.44%   |
| Drobeta-Turnu Severin | 2         | 4.44%   |
| Budapest              | 2         | 4.44%   |
| West Corinth          | 1         | 2.22%   |
| Tenbury Wells         | 1         | 2.22%   |
| Tellico Plains        | 1         | 2.22%   |
| Sosnowiec             | 1         | 2.22%   |
| Singapore             | 1         | 2.22%   |
| Schermbeck            | 1         | 2.22%   |
| Salsomaggiore Terme   | 1         | 2.22%   |
| Rostock               | 1         | 2.22%   |
| Rijeka                | 1         | 2.22%   |
| Puerto Cumarebo       | 1         | 2.22%   |
| Moscow                | 1         | 2.22%   |
| Morelia               | 1         | 2.22%   |
| Mooresville           | 1         | 2.22%   |
| Moirans               | 1         | 2.22%   |
| Mogilev               | 1         | 2.22%   |
| Milano                | 1         | 2.22%   |
| Mannheim              | 1         | 2.22%   |
| Londrina              | 1         | 2.22%   |
| Ljubljana             | 1         | 2.22%   |
| Las Vegas             | 1         | 2.22%   |
| Klaudyn               | 1         | 2.22%   |
| Jönköping           | 1         | 2.22%   |
| Jacksonville          | 1         | 2.22%   |
| Indianapolis          | 1         | 2.22%   |
| Giussano              | 1         | 2.22%   |
| Gijón                | 1         | 2.22%   |
| Fulham                | 1         | 2.22%   |
| Doha                  | 1         | 2.22%   |
| Dammam                | 1         | 2.22%   |
| Carterton             | 1         | 2.22%   |
| Calvecchia            | 1         | 2.22%   |
| Barcelona             | 1         | 2.22%   |
| Alicante              | 1         | 2.22%   |
| Adana                 | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 12.24%  |
| Unknown             | 6         | 6      | 12.24%  |
| Seagate             | 5         | 5      | 10.2%   |
| Samsung Electronics | 5         | 5      | 10.2%   |
| Kingston            | 5         | 5      | 10.2%   |
| Toshiba             | 3         | 3      | 6.12%   |
| Hitachi             | 3         | 3      | 6.12%   |
| SanDisk             | 2         | 2      | 4.08%   |
| KESU                | 2         | 2      | 4.08%   |
| HGST                | 2         | 2      | 4.08%   |
| Fujitsu             | 2         | 2      | 4.08%   |
| China               | 2         | 2      | 4.08%   |
| Silicon Motion      | 1         | 1      | 2.04%   |
| Phison              | 1         | 1      | 2.04%   |
| KingSpec            | 1         | 1      | 2.04%   |
| KBG40ZNV            | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |
| Unknown             | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 2         | 4.08%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 4.08%   |
| KESU USB 3.1 256GB                   | 2         | 4.08%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 2.04%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 2.04%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 2.04%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 2.04%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 2.04%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 2.04%   |
| Unknown USDU1  32GB                  | 1         | 2.04%   |
| Unknown SLD64G  64GB                 | 1         | 2.04%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 2.04%   |
| Unknown MMC Card  64GB               | 1         | 2.04%   |
| Unknown HAG2e  16GB                  | 1         | 2.04%   |
| Unknown 064G38  64GB                 | 1         | 2.04%   |
| Toshiba MK8025GAS 80GB               | 1         | 2.04%   |
| Toshiba MK6028GAL 64GB               | 1         | 2.04%   |
| Toshiba MK3252GSX 320GB              | 1         | 2.04%   |
| Silicon Motion NVME SSD 512GB        | 1         | 2.04%   |
| Seagate ST96812AS 64GB               | 1         | 2.04%   |
| Seagate ST9500325AS 500GB            | 1         | 2.04%   |
| Seagate ST9120822AS 120GB            | 1         | 2.04%   |
| Seagate ST380012A 80GB               | 1         | 2.04%   |
| Seagate Backup+ SL 1TB               | 1         | 2.04%   |
| SanDisk SDCFX-032G SSD               | 1         | 2.04%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 2.04%   |
| Samsung MZALQ256HBJD-00BL1 256GB     | 1         | 2.04%   |
| Samsung MZAL4512HBLU-00BL2 512GB     | 1         | 2.04%   |
| Samsung AWMB3R  16GB                 | 1         | 2.04%   |
| Phison APS-SE20G-1T                  | 1         | 2.04%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 2.04%   |
| Kingston SV300S37A240G 240GB SSD     | 1         | 2.04%   |
| Kingston SUV400S37120G 120GB SSD     | 1         | 2.04%   |
| KingSpec KSD-PA25.6-064MS 64GB SSD   | 1         | 2.04%   |
| KBG40ZNV 256G KIOXIA                 | 1         | 2.04%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 2.04%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 2.04%   |
| Hitachi DK23CA-20 20GB               | 1         | 2.04%   |
| HGST HTS725050A7E630 500GB           | 1         | 2.04%   |
| HGST HTS541075A9E680 752GB           | 1         | 2.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 25%     |
| Seagate | 4         | 4      | 20%     |
| Toshiba | 3         | 3      | 15%     |
| Hitachi | 3         | 3      | 15%     |
| HGST    | 2         | 2      | 10%     |
| Fujitsu | 2         | 2      | 10%     |
| Unknown | 1         | 1      | 5%      |

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
| HDD     | 19        | 20     | 41.3%   |
| SSD     | 14        | 14     | 30.43%  |
| MMC     | 6         | 6      | 13.04%  |
| NVMe    | 4         | 6      | 8.7%    |
| Unknown | 3         | 3      | 6.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 33     | 68.75%  |
| MMC  | 6         | 6      | 12.5%   |
| SAS  | 5         | 5      | 10.42%  |
| NVMe | 4         | 5      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 32     | 93.94%  |
| 0.51-1.0   | 2         | 2      | 6.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 24.44%  |
| 51-100     | 10        | 22.22%  |
| 251-500    | 7         | 15.56%  |
| 1-20       | 7         | 15.56%  |
| 21-50      | 5         | 11.11%  |
| 1001-2000  | 2         | 4.44%   |
| 501-1000   | 2         | 4.44%   |
| Unknown    | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 32        | 71.11%  |
| 21-50    | 7         | 15.56%  |
| 251-500  | 2         | 4.44%   |
| 51-100   | 2         | 4.44%   |
| 501-1000 | 1         | 2.22%   |
| Unknown  | 1         | 2.22%   |

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
| Works    | 25        | 27     | 54.35%  |
| Malfunc  | 11        | 11     | 23.91%  |
| Detected | 10        | 11     | 21.74%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 30        | 68.18%  |
| AMD                              | 6         | 13.64%  |
| Silicon Integrated Systems [SiS] | 3         | 6.82%   |
| Samsung Electronics              | 2         | 4.55%   |
| Silicon Motion                   | 1         | 2.27%   |
| SanDisk                          | 1         | 2.27%   |
| Phison Electronics               | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 7.69%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 5.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 5.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 5.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 5.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 5.77%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 5.77%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 3.85%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 3.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.92%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.92%   |
| Samsung NVMe SSD Controller PM9B1                                                | 1         | 1.92%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.92%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.92%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.92%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.92%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.92%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 27        | 56.25%  |
| IDE  | 16        | 33.33%  |
| NVMe | 4         | 8.33%   |
| RAID | 1         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 82.22%  |
| AMD    | 8         | 17.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz               | 2         | 4.44%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 4.44%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 4.44%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 4.44%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 2         | 4.44%   |
| Intel Pentium M processor 1000MHz               | 1         | 2.22%   |
| Intel Pentium III (Coppermine)                  | 1         | 2.22%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 2.22%   |
| Intel Pentium CPU 4415U @ 2.30GHz               | 1         | 2.22%   |
| Intel Pentium 4 CPU 2.66GHz                     | 1         | 2.22%   |
| Intel Genuine CPU T2050 @ 1.60GHz               | 1         | 2.22%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 2.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.22%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 2.22%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 2.22%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 2.22%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.22%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.22%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.22%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 2.22%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 2.22%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.22%   |
| Intel Atom CPU Z3735G @ 1.33GHz                 | 1         | 2.22%   |
| Intel 12th Gen Core i5-1240P                    | 1         | 2.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.22%   |
| AMD V120 Processor                              | 1         | 2.22%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.22%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 2.22%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 2.22%   |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 2.22%   |
| AMD Athlon Neo Processor MV-40                  | 1         | 2.22%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.22%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G   | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 7         | 15.56%  |
| Intel Celeron           | 6         | 13.33%  |
| Intel Atom              | 6         | 13.33%  |
| Intel Pentium M         | 3         | 6.67%   |
| Intel Core i5           | 3         | 6.67%   |
| Intel Core i3           | 3         | 6.67%   |
| Other                   | 2         | 4.44%   |
| Intel Pentium III       | 1         | 2.22%   |
| Intel Pentium Dual-Core | 1         | 2.22%   |
| Intel Pentium 4         | 1         | 2.22%   |
| Intel Pentium           | 1         | 2.22%   |
| Intel Genuine           | 1         | 2.22%   |
| Intel Core m3           | 1         | 2.22%   |
| Intel Core 2            | 1         | 2.22%   |
| AMD V120                | 1         | 2.22%   |
| AMD Ryzen 7 PRO         | 1         | 2.22%   |
| AMD Mobile Sempron      | 1         | 2.22%   |
| AMD E                   | 1         | 2.22%   |
| AMD C-70                | 1         | 2.22%   |
| AMD Athlon Neo          | 1         | 2.22%   |
| AMD A8                  | 1         | 2.22%   |
| AMD A4                  | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 53.33%  |
| 1      | 12        | 26.67%  |
| 4      | 8         | 17.78%  |
| 12     | 1         | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 45        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 68.89%  |
| 2      | 14        | 31.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 75.56%  |
| 32-bit         | 11        | 24.44%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 8.89%   |
| 0x206a7    | 3         | 6.67%   |
| 0x106c2    | 3         | 6.67%   |
| 0x1067a    | 3         | 6.67%   |
| 0x706a1    | 2         | 4.44%   |
| 0x6fd      | 2         | 4.44%   |
| 0x406c4    | 2         | 4.44%   |
| 0x30678    | 2         | 4.44%   |
| 0x10676    | 2         | 4.44%   |
| 0xf27      | 1         | 2.22%   |
| 0x906a3    | 1         | 2.22%   |
| 0x806e9    | 1         | 2.22%   |
| 0x806c1    | 1         | 2.22%   |
| 0x706a8    | 1         | 2.22%   |
| 0x6fb      | 1         | 2.22%   |
| 0x6f6      | 1         | 2.22%   |
| 0x6e8      | 1         | 2.22%   |
| 0x6d8      | 1         | 2.22%   |
| 0x6d6      | 1         | 2.22%   |
| 0x695      | 1         | 2.22%   |
| 0x68a      | 1         | 2.22%   |
| 0x406e3    | 1         | 2.22%   |
| 0x40651    | 1         | 2.22%   |
| 0x306c3    | 1         | 2.22%   |
| 0x20655    | 1         | 2.22%   |
| 0x08108102 | 1         | 2.22%   |
| 0x07030106 | 1         | 2.22%   |
| 0x06006705 | 1         | 2.22%   |
| 0x05000119 | 1         | 2.22%   |
| 0x0500010d | 1         | 2.22%   |
| 0x010000c8 | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 5         | 11.11%  |
| Penryn        | 5         | 11.11%  |
| P6            | 5         | 11.11%  |
| Core          | 4         | 8.89%   |
| Bonnell       | 4         | 8.89%   |
| SandyBridge   | 3         | 6.67%   |
| Goldmont plus | 3         | 6.67%   |
| K8 Hammer     | 2         | 4.44%   |
| Haswell       | 2         | 4.44%   |
| Bobcat        | 2         | 4.44%   |
| Zen+          | 1         | 2.22%   |
| Westmere      | 1         | 2.22%   |
| TigerLake     | 1         | 2.22%   |
| Skylake       | 1         | 2.22%   |
| Puma          | 1         | 2.22%   |
| NetBurst      | 1         | 2.22%   |
| KabyLake      | 1         | 2.22%   |
| K10           | 1         | 2.22%   |
| Excavator     | 1         | 2.22%   |
| Unknown       | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 28        | 59.57%  |
| AMD                              | 12        | 25.53%  |
| Silicon Integrated Systems [SiS] | 3         | 6.38%   |
| Nvidia                           | 3         | 6.38%   |
| S3 Graphics                      | 1         | 2.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 3         | 5.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 3         | 5.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 3         | 5.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 5.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 3         | 5.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 5.66%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 3.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 2         | 3.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 2         | 3.77%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.89%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 1.89%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 1.89%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.89%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 1.89%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.89%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 1.89%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 1.89%   |
| Intel HD Graphics 610                                                                      | 1         | 1.89%   |
| Intel HD Graphics 515                                                                      | 1         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 1.89%   |
| Intel Alder Lake-P Integrated Graphics Controller                                          | 1         | 1.89%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 1         | 1.89%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 1.89%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 1.89%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 1.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 1.89%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]                | 1         | 1.89%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                           | 1         | 1.89%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                    | 1         | 1.89%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 1         | 1.89%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 1.89%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 1.89%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 22        | 48.89%  |
| 1 x AMD         | 11        | 24.44%  |
| 2 x Intel       | 3         | 6.67%   |
| 1 x SiS         | 3         | 6.67%   |
| 1 x Nvidia      | 2         | 4.44%   |
| Other           | 1         | 2.22%   |
| 1 x S3 Graphics | 1         | 2.22%   |
| Intel + Nvidia  | 1         | 2.22%   |
| Intel + AMD     | 1         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 38        | 84.44%  |
| Unknown     | 5         | 11.11%  |
| Proprietary | 2         | 4.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 68.89%  |
| 0.01-0.5   | 12        | 26.67%  |
| 1.01-2.0   | 2         | 4.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 21.05%  |
| Samsung Electronics     | 7         | 18.42%  |
| Chimei Innolux          | 7         | 18.42%  |
| LG Display              | 5         | 13.16%  |
| HannStar                | 2         | 5.26%   |
| CPT                     | 2         | 5.26%   |
| MQP                     | 1         | 2.63%   |
| LG Philips              | 1         | 2.63%   |
| Hewlett-Packard         | 1         | 2.63%   |
| Dell                    | 1         | 2.63%   |
| Chi Mei Optoelectronics | 1         | 2.63%   |
| BOE                     | 1         | 2.63%   |
| Apple                   | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 5.26%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 5.26%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch      | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 890x500mm 40.2-inch    | 1         | 2.63%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                     | 1         | 2.63%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 1         | 2.63%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch               | 1         | 2.63%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.63%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 1         | 2.63%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                         | 1         | 2.63%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                     | 1         | 2.63%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                     | 1         | 2.63%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1004 1024x600 222x125mm 10.0-inch | 1         | 2.63%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                     | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 14        | 36.84%  |
| 1920x1080 (FHD)   | 10        | 26.32%  |
| 1280x800 (WXGA)   | 6         | 15.79%  |
| 1600x900 (HD+)    | 3         | 7.89%   |
| 1024x600          | 2         | 5.26%   |
| 800x600           | 1         | 2.63%   |
| 2160x1440         | 1         | 2.63%   |
| 1920x1200 (WUXGA) | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 44.74%  |
| 13     | 4         | 10.53%  |
| 14     | 3         | 7.89%   |
| 12     | 3         | 7.89%   |
| 11     | 3         | 7.89%   |
| 10     | 2         | 5.26%   |
| 46     | 1         | 2.63%   |
| 40     | 1         | 2.63%   |
| 24     | 1         | 2.63%   |
| 23     | 1         | 2.63%   |
| 18     | 1         | 2.63%   |
| 17     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 56.76%  |
| 201-300     | 9         | 24.32%  |
| 351-400     | 3         | 8.11%   |
| 501-600     | 2         | 5.41%   |
| 801-900     | 1         | 2.7%    |
| 1001-1500   | 1         | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 75%     |
| 16/10 | 7         | 19.44%  |
| 4/3   | 1         | 2.78%   |
| 3/2   | 1         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 44.74%  |
| 81-90          | 7         | 18.42%  |
| 51-60          | 3         | 7.89%   |
| 61-70          | 2         | 5.26%   |
| 41-50          | 2         | 5.26%   |
| 501-1000       | 2         | 5.26%   |
| 71-80          | 1         | 2.63%   |
| 251-300        | 1         | 2.63%   |
| 201-250        | 1         | 2.63%   |
| 141-150        | 1         | 2.63%   |
| 121-130        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 18        | 47.37%  |
| 51-100  | 9         | 23.68%  |
| 121-160 | 7         | 18.42%  |
| 161-240 | 3         | 7.89%   |
| 1-50    | 1         | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 84.44%  |
| 0     | 4         | 8.89%   |
| 2     | 3         | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 25        | 32.47%  |
| Intel                            | 16        | 20.78%  |
| Qualcomm Atheros                 | 15        | 19.48%  |
| Broadcom                         | 5         | 6.49%   |
| Marvell Technology Group         | 4         | 5.19%   |
| Silicon Integrated Systems [SiS] | 3         | 3.9%    |
| Broadcom Limited                 | 2         | 2.6%    |
| Xiaomi                           | 1         | 1.3%    |
| Ralink Technology                | 1         | 1.3%    |
| Motorola PCS                     | 1         | 1.3%    |
| LG Electronics                   | 1         | 1.3%    |
| JMicron Technology               | 1         | 1.3%    |
| D-Link System                    | 1         | 1.3%    |
| Accton Technology                | 1         | 1.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 10.47%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 8         | 9.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 4.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 3.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 3.49%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 3.49%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 2.33%   |
| Intel Wireless 7265                                                     | 2         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.33%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.16%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 1.16%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.16%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.16%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 1.16%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.16%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.16%   |
| Motorola PCS moto g51 5G                                                | 1         | 1.16%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 1         | 1.16%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 1.16%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 1.16%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.16%   |
| Intel Wireless 3165                                                     | 1         | 1.16%   |
| Intel WiFi Link 5100                                                    | 1         | 1.16%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.16%   |
| Intel Ethernet Connection I217-V                                        | 1         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.16%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 14        | 32.56%  |
| Intel                 | 14        | 32.56%  |
| Realtek Semiconductor | 8         | 18.6%   |
| Broadcom              | 3         | 6.98%   |
| Broadcom Limited      | 2         | 4.65%   |
| Ralink Technology     | 1         | 2.33%   |
| D-Link System         | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 9.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 9.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 6.98%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 6.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 4.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 4.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 4.65%   |
| Intel Wireless 7265                                                         | 2         | 4.65%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 2.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 2.33%   |
| Realtek RTL8187SE Wireless LAN Controller                                   | 1         | 2.33%   |
| Realtek 802.11n WLAN Adapter                                                | 1         | 2.33%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 2.33%   |
| Intel Wireless 3165                                                         | 1         | 2.33%   |
| Intel WiFi Link 5100                                                        | 1         | 2.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.33%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 1         | 2.33%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2.33%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                   | 1         | 2.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.33%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 21        | 55.26%  |
| Marvell Technology Group         | 4         | 10.53%  |
| Intel                            | 3         | 7.89%   |
| Silicon Integrated Systems [SiS] | 2         | 5.26%   |
| Broadcom                         | 2         | 5.26%   |
| Xiaomi                           | 1         | 2.63%   |
| Qualcomm Atheros                 | 1         | 2.63%   |
| Motorola PCS                     | 1         | 2.63%   |
| LG Electronics                   | 1         | 2.63%   |
| JMicron Technology               | 1         | 2.63%   |
| Accton Technology                | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 23.68%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 21.05%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 7.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 5.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.63%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 2.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.63%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 2.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.63%   |
| Motorola PCS moto g51 5G                                          | 1         | 2.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.63%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.63%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.63%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.63%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 2.63%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 2.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.63%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 50%     |
| Ethernet | 37        | 44.05%  |
| Modem    | 5         | 5.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 68.89%  |
| Ethernet | 14        | 31.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 30        | 66.67%  |
| 1     | 12        | 26.67%  |
| 0     | 2         | 4.44%   |
| 3     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 84.44%  |
| Yes  | 7         | 15.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 6         | 28.57%  |
| Intel                           | 6         | 28.57%  |
| Realtek Semiconductor           | 3         | 14.29%  |
| Alps Electric                   | 2         | 9.52%   |
| Toshiba                         | 1         | 4.76%   |
| Hewlett-Packard                 | 1         | 4.76%   |
| ASUSTek Computer                | 1         | 4.76%   |
| Apple                           | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth              | 4         | 19.05%  |
| Realtek Bluetooth Radio                        | 3         | 14.29%  |
| Intel Bluetooth wireless interface             | 3         | 14.29%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 9.52%   |
| Intel AX200 Bluetooth                          | 2         | 9.52%   |
| Alps Electric BCM2046 Bluetooth Device         | 2         | 9.52%   |
| Toshiba Askey for                              | 1         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 4.76%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 4.76%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 4.76%   |
| Apple Bluetooth HCI                            | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 31        | 68.89%  |
| AMD                              | 10        | 22.22%  |
| Silicon Integrated Systems [SiS] | 3         | 6.67%   |
| ESS Technology                   | 1         | 2.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 7.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 7.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 5.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 5.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 5.56%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 3.7%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 3.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.7%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 3.7%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 3.7%    |
| AMD FCH Azalia Controller                                                                         | 2         | 3.7%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.85%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.85%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.85%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.85%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.85%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.85%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 17        | 34.69%  |
| Samsung Electronics | 11        | 22.45%  |
| SK hynix            | 5         | 10.2%   |
| Kingston            | 5         | 10.2%   |
| Unknown (ABCD)      | 2         | 4.08%   |
| Micron Technology   | 2         | 4.08%   |
| Elpida              | 2         | 4.08%   |
| Toshiba             | 1         | 2.04%   |
| Team                | 1         | 2.04%   |
| Ramaxel Technology  | 1         | 2.04%   |
| Crucial             | 1         | 2.04%   |
| A-DATA Technology   | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 11.32%  |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 5.66%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 3.77%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.77%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.89%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.89%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.89%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.89%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.89%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.89%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.89%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.89%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.89%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.89%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.89%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.89%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.89%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.89%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.89%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1.89%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.89%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.89%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.89%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 1.89%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.89%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 1.89%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 1.89%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.89%   |
| Micron RAM MT52L256M32D1PF-10 2GB LPDDR3 1867MT/s                | 1         | 1.89%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.89%   |
| Kingston RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 1.89%   |
| Kingston RAM Module 2GB SODIMM DDR 667MT/s                       | 1         | 1.89%   |
| Kingston RAM HP32D4S2S1ME-4 4096MB SODIMM DDR4 3200MT/s          | 1         | 1.89%   |
| Kingston RAM HP16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 12        | 27.27%  |
| DDR2   | 12        | 27.27%  |
| DDR4   | 6         | 13.64%  |
| SDRAM  | 4         | 9.09%   |
| DDR    | 4         | 9.09%   |
| LPDDR4 | 2         | 4.55%   |
| LPDDR3 | 2         | 4.55%   |
| DRAM   | 2         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 90.7%   |
| Unknown      | 2         | 4.65%   |
| Row Of Chips | 1         | 2.33%   |
| DIMM         | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 18        | 37.5%   |
| 4096  | 13        | 27.08%  |
| 1024  | 6         | 12.5%   |
| 8192  | 5         | 10.42%  |
| 512   | 3         | 6.25%   |
| 32768 | 1         | 2.08%   |
| 16384 | 1         | 2.08%   |
| 256   | 1         | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 13        | 28.26%  |
| 1600    | 5         | 10.87%  |
| 2400    | 4         | 8.7%    |
| 1334    | 4         | 8.7%    |
| 3200    | 3         | 6.52%   |
| 2667    | 2         | 4.35%   |
| 1867    | 2         | 4.35%   |
| 1333    | 2         | 4.35%   |
| 1067    | 2         | 4.35%   |
| 667     | 2         | 4.35%   |
| 4199    | 1         | 2.17%   |
| 3266    | 1         | 2.17%   |
| 2048    | 1         | 2.17%   |
| 1066    | 1         | 2.17%   |
| 800     | 1         | 2.17%   |
| 533     | 1         | 2.17%   |
| 266     | 1         | 2.17%   |

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
| IMC Networks                           | 4         | 15.38%  |
| Chicony Electronics                    | 4         | 15.38%  |
| Microdia                               | 3         | 11.54%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 11.54%  |
| Ricoh                                  | 2         | 7.69%   |
| Bison Electronics                      | 2         | 7.69%   |
| Suyin                                  | 1         | 3.85%   |
| Silicon Motion                         | 1         | 3.85%   |
| Realtek Semiconductor                  | 1         | 3.85%   |
| Quanta                                 | 1         | 3.85%   |
| Luxvisions Innotech Limited            | 1         | 3.85%   |
| ALi                                    | 1         | 3.85%   |
| Alcor Micro                            | 1         | 3.85%   |
| Acer                                   | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                               | 2         | 7.69%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.85%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 3.85%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 3.85%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 3.85%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 3.85%   |
| Quanta Chromebook HD Camera                                 | 1         | 3.85%   |
| Microdia Webcam Vitade AF                                   | 1         | 3.85%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.85%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 3.85%   |
| IMC Networks Integrated Camera                              | 1         | 3.85%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 3.85%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 3.85%   |
| Chicony Integrated Camera                                   | 1         | 3.85%   |
| Chicony HP Webcam                                           | 1         | 3.85%   |
| Chicony HP HD Webcam                                        | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 3.85%   |
| Bison Integrated Camera                                     | 1         | 3.85%   |
| Bison EasyCamera                                            | 1         | 3.85%   |
| ALi M5603 Video Camera Controller                           | 1         | 3.85%   |
| Alcor Micro USB 2.0 Web Camera                              | 1         | 3.85%   |
| Acer HP Webcam-101                                          | 1         | 3.85%   |

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
| 0     | 32        | 71.11%  |
| 1     | 7         | 15.56%  |
| 2     | 5         | 11.11%  |
| 4     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 42.86%  |
| Fingerprint reader       | 4         | 19.05%  |
| Flash memory             | 2         | 9.52%   |
| Communication controller | 2         | 9.52%   |
| Chipcard                 | 2         | 9.52%   |
| Net/wireless             | 1         | 4.76%   |
| Camera                   | 1         | 4.76%   |

