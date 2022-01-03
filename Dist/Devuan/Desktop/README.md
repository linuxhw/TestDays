Devuan - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Devuan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                | Probe                                                      | Date         |
|---------------|----------------------|------------------------------------------------------------|--------------|
| Gigabyte      | MZGLKBP-00           | [202ccac61c](https://linux-hardware.org/?probe=202ccac61c) | Dec 30, 2021 |
| Gigabyte      | B75M-D3V             | [1c15b6b3c7](https://linux-hardware.org/?probe=1c15b6b3c7) | Dec 26, 2021 |
| HP            | 1495                 | [28835849f0](https://linux-hardware.org/?probe=28835849f0) | Oct 29, 2021 |
| ASUSTek       | PRIME Z490M-PLUS     | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| MSI           | B360M PRO-VD         | [06e625d98f](https://linux-hardware.org/?probe=06e625d98f) | Oct 02, 2021 |
| HP            | 1825                 | [ff75be1ea3](https://linux-hardware.org/?probe=ff75be1ea3) | Jun 06, 2021 |
| ASUSTek       | P5G41T-M LX2/BR      | [8702580cb4](https://linux-hardware.org/?probe=8702580cb4) | May 26, 2021 |
| ASUSTek       | P5G41T-M LX2/BR      | [05f1d12390](https://linux-hardware.org/?probe=05f1d12390) | May 26, 2021 |
| Gigabyte      | H170-HD3-CF          | [2ffdc89c2a](https://linux-hardware.org/?probe=2ffdc89c2a) | Apr 28, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF   | [50f8ddb45c](https://linux-hardware.org/?probe=50f8ddb45c) | Apr 28, 2021 |
| Google        | Panther              | [666794d603](https://linux-hardware.org/?probe=666794d603) | Apr 26, 2021 |
| ASUSTek       | F1A55-M LX           | [630bbb748a](https://linux-hardware.org/?probe=630bbb748a) | Apr 17, 2021 |
| Gigabyte      | H170-HD3-CF          | [f103eefd66](https://linux-hardware.org/?probe=f103eefd66) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF   | [e802fc9ff5](https://linux-hardware.org/?probe=e802fc9ff5) | Apr 17, 2021 |
| Sun Micros... | Ultra 24 50          | [e4b76f9137](https://linux-hardware.org/?probe=e4b76f9137) | Apr 10, 2021 |
| Sun Micros... | Ultra 24 50          | [15691fbc42](https://linux-hardware.org/?probe=15691fbc42) | Apr 10, 2021 |
| ASUSTek       | A8R-MVP              | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| ASRock        | K8A780LM             | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| Gigabyte      | 970A-DS3P            | [eeebc66137](https://linux-hardware.org/?probe=eeebc66137) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P            | [fdf4e6d366](https://linux-hardware.org/?probe=fdf4e6d366) | Mar 17, 2021 |
| ASRock        | K8A780LM             | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASRock        | H81M-ITX             | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX             | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| Intel         | D815EEA AAA45884-401 | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401 | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | GA-G41M-ES2L         | [592c995804](https://linux-hardware.org/?probe=592c995804) | Jan 30, 2021 |
| Acer          | F672CR R01-A4        | [8d41694165](https://linux-hardware.org/?probe=8d41694165) | Jan 25, 2021 |
| Lenovo        | Board                | [f963a2e7f9](https://linux-hardware.org/?probe=f963a2e7f9) | Jan 06, 2021 |
| Lenovo        | Board                | [3ab2cd64a6](https://linux-hardware.org/?probe=3ab2cd64a6) | Jan 04, 2021 |
| Dell          | 0GXM1W A04           | [989f983b51](https://linux-hardware.org/?probe=989f983b51) | Dec 28, 2020 |
| Lenovo        | Board                | [aac28ba905](https://linux-hardware.org/?probe=aac28ba905) | Dec 19, 2020 |
| ASUSTek       | Maximus V GENE       | [253b5aba98](https://linux-hardware.org/?probe=253b5aba98) | Oct 29, 2020 |
| ASUSTek       | H81M-C               | [cd136e059e](https://linux-hardware.org/?probe=cd136e059e) | Oct 05, 2020 |
| HP            | 1791                 | [f41fcdc019](https://linux-hardware.org/?probe=f41fcdc019) | Sep 26, 2020 |
| ASUSTek       | EX-A320M-GAMING      | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| HP            | 1791                 | [5a21e91155](https://linux-hardware.org/?probe=5a21e91155) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS ELITE     | [ff5143e508](https://linux-hardware.org/?probe=ff5143e508) | Aug 02, 2020 |
| ASUSTek       | P5PE-VM              | [298c1239dd](https://linux-hardware.org/?probe=298c1239dd) | May 20, 2020 |
| MSI           | B350 PC MATE         | [ff3852f02d](https://linux-hardware.org/?probe=ff3852f02d) | Mar 23, 2020 |
| ASRock        | G31M-VS2             | [b64547f948](https://linux-hardware.org/?probe=b64547f948) | Dec 06, 2019 |
| Gigabyte      | H170-HD3-CF          | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASUSTek       | P5PE-VM              | [6a89046dfb](https://linux-hardware.org/?probe=6a89046dfb) | Dec 02, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 4.19.0-14-amd64      | 4        | 12.9%   |
| 5.10.0-9-amd64       | 3        | 9.68%   |
| 4.19.0-16-amd64      | 3        | 9.68%   |
| 5.10.0-8-amd64       | 2        | 6.45%   |
| 4.19.0-9-amd64       | 2        | 6.45%   |
| 5.9.0-1-amd64        | 1        | 3.23%   |
| 5.7.0-1-amd64        | 1        | 3.23%   |
| 5.7.0-0.bpo.2-amd64  | 1        | 3.23%   |
| 5.10.0-6-amd64       | 1        | 3.23%   |
| 5.10.0-5-amd64       | 1        | 3.23%   |
| 5.10.0-2-amd64       | 1        | 3.23%   |
| 4.9.0-15-amd64       | 1        | 3.23%   |
| 4.9.0-14-686-pae     | 1        | 3.23%   |
| 4.9.0-14-686         | 1        | 3.23%   |
| 4.9.0-11-686-pae     | 1        | 3.23%   |
| 4.19.112             | 1        | 3.23%   |
| 4.19.0-13-amd64      | 1        | 3.23%   |
| 4.19.0-12-amd64      | 1        | 3.23%   |
| 4.19.0-10-amd64      | 1        | 3.23%   |
| 4.19.0-1-amd64       | 1        | 3.23%   |
| 4.19.0-0.bpo.6-amd64 | 1        | 3.23%   |
| 4.18.0-0.bpo.1-amd64 | 1        | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.19.0   | 13       | 43.33%  |
| 5.10.0   | 8        | 26.67%  |
| 4.9.0    | 4        | 13.33%  |
| 5.7.0    | 2        | 6.67%   |
| 5.9.0    | 1        | 3.33%   |
| 4.19.112 | 1        | 3.33%   |
| 4.18.0   | 1        | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 14       | 46.67%  |
| 5.10    | 8        | 26.67%  |
| 4.9     | 4        | 13.33%  |
| 5.7     | 2        | 6.67%   |
| 5.9     | 1        | 3.33%   |
| 4.18    | 1        | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 26       | 89.66%  |
| i686   | 3        | 10.34%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| XFCE    | 18       | 60%     |
| Unknown | 4        | 13.33%  |
| MATE    | 3        | 10%     |
| KDE5    | 2        | 6.67%   |
| LXDE    | 1        | 3.33%   |
| i3      | 1        | 3.33%   |
| awesome | 1        | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 26       | 89.66%  |
| Tty  | 3        | 10.34%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 17       | 58.62%  |
| LightDM | 6        | 20.69%  |
| Unknown | 4        | 13.79%  |
| XDM     | 1        | 3.45%   |
| NODM    | 1        | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 7        | 24.14%  |
| sk_SK   | 3        | 10.34%  |
| fr_FR   | 3        | 10.34%  |
| en_GB   | 3        | 10.34%  |
| Unknown | 3        | 10.34%  |
| ru_RU   | 2        | 6.9%    |
| en_AU   | 2        | 6.9%    |
| C       | 2        | 6.9%    |
| pt_BR   | 1        | 3.45%   |
| pl_PL   | 1        | 3.45%   |
| en_NZ   | 1        | 3.45%   |
| en_CA   | 1        | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 22       | 75.86%  |
| EFI  | 7        | 24.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 25       | 86.21%  |
| Overlay | 2        | 6.9%    |
| Ext3    | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 15       | 48.39%  |
| GPT     | 14       | 45.16%  |
| Unknown | 2        | 6.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 63.33%  |
| Yes       | 11       | 36.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 68.97%  |
| Yes       | 9        | 31.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 27.59%  |
| ASUSTek Computer    | 7        | 24.14%  |
| Hewlett-Packard     | 3        | 10.34%  |
| ASRock              | 3        | 10.34%  |
| MSI                 | 2        | 6.9%    |
| Sun Microsystems    | 1        | 3.45%   |
| Lenovo              | 1        | 3.45%   |
| Intel               | 1        | 3.45%   |
| Google              | 1        | 3.45%   |
| Dell                | 1        | 3.45%   |
| Acer                | 1        | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Sun Microsystems Ultra 24       | 1        | 3.45%   |
| MSI MS-7B53                     | 1        | 3.45%   |
| MSI MS-7A34                     | 1        | 3.45%   |
| Lenovo ThinkStation E20 4220CTO | 1        | 3.45%   |
| Intel D815EEA AAA45884-401      | 1        | 3.45%   |
| HP Z220 SFF Workstation         | 1        | 3.45%   |
| HP EliteDesk 800 G1 DM          | 1        | 3.45%   |
| HP Compaq 8200 Elite SFF PC     | 1        | 3.45%   |
| Google Panther                  | 1        | 3.45%   |
| Gigabyte Z390 GAMING SLI        | 1        | 3.45%   |
| Gigabyte MZGLKBP-00             | 1        | 3.45%   |
| Gigabyte H170-HD3-CF            | 1        | 3.45%   |
| Gigabyte H170-HD3               | 1        | 3.45%   |
| Gigabyte GA-G41M-ES2L           | 1        | 3.45%   |
| Gigabyte B75M-D3V               | 1        | 3.45%   |
| Gigabyte B450 AORUS ELITE       | 1        | 3.45%   |
| Gigabyte 970A-DS3P              | 1        | 3.45%   |
| Dell OptiPlex 7010              | 1        | 3.45%   |
| ASUS PRIME Z490M-PLUS           | 1        | 3.45%   |
| ASUS P5PE-VM                    | 1        | 3.45%   |
| ASUS P5G41T-M LX2/BR            | 1        | 3.45%   |
| ASUS Maximus V GENE             | 1        | 3.45%   |
| ASUS F1A55-M LX                 | 1        | 3.45%   |
| ASUS EX-A320M-GAMING            | 1        | 3.45%   |
| ASUS All Series                 | 1        | 3.45%   |
| ASRock K8A780LM                 | 1        | 3.45%   |
| ASRock H81M-ITX                 | 1        | 3.45%   |
| ASRock G31M-VS2                 | 1        | 3.45%   |
| Acer Aspire M1610               | 1        | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Sun Microsystems Ultra | 1        | 3.45%   |
| MSI MS-7B53            | 1        | 3.45%   |
| MSI MS-7A34            | 1        | 3.45%   |
| Lenovo ThinkStation    | 1        | 3.45%   |
| Intel D815EEA          | 1        | 3.45%   |
| HP Z220                | 1        | 3.45%   |
| HP EliteDesk           | 1        | 3.45%   |
| HP Compaq              | 1        | 3.45%   |
| Google Panther         | 1        | 3.45%   |
| Gigabyte Z390          | 1        | 3.45%   |
| Gigabyte MZGLKBP-00    | 1        | 3.45%   |
| Gigabyte H170-HD3-CF   | 1        | 3.45%   |
| Gigabyte H170-HD3      | 1        | 3.45%   |
| Gigabyte GA-G41M-ES2L  | 1        | 3.45%   |
| Gigabyte B75M-D3V      | 1        | 3.45%   |
| Gigabyte B450          | 1        | 3.45%   |
| Gigabyte 970A-DS3P     | 1        | 3.45%   |
| Dell OptiPlex          | 1        | 3.45%   |
| ASUS PRIME             | 1        | 3.45%   |
| ASUS P5PE-VM           | 1        | 3.45%   |
| ASUS P5G41T-M          | 1        | 3.45%   |
| ASUS Maximus           | 1        | 3.45%   |
| ASUS F1A55-M           | 1        | 3.45%   |
| ASUS EX-A320M-GAMING   | 1        | 3.45%   |
| ASUS All               | 1        | 3.45%   |
| ASRock K8A780LM        | 1        | 3.45%   |
| ASRock H81M-ITX        | 1        | 3.45%   |
| ASRock G31M-VS2        | 1        | 3.45%   |
| Acer Aspire            | 1        | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 5        | 17.24%  |
| 2014 | 3        | 10.34%  |
| 2013 | 3        | 10.34%  |
| 2021 | 2        | 6.9%    |
| 2018 | 2        | 6.9%    |
| 2016 | 2        | 6.9%    |
| 2015 | 2        | 6.9%    |
| 2012 | 2        | 6.9%    |
| 2011 | 2        | 6.9%    |
| 2007 | 2        | 6.9%    |
| 2020 | 1        | 3.45%   |
| 2017 | 1        | 3.45%   |
| 2009 | 1        | 3.45%   |
| 2000 | 1        | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 29       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 29       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 93.1%   |
| Yes  | 2        | 6.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 8        | 27.59%  |
| 8.01-16.0  | 8        | 27.59%  |
| 32.01-64.0 | 5        | 17.24%  |
| 4.01-8.0   | 3        | 10.34%  |
| 1.01-2.0   | 3        | 10.34%  |
| 3.01-4.0   | 1        | 3.45%   |
| 0.01-0.5   | 1        | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 9        | 31.03%  |
| 0.51-1.0  | 7        | 24.14%  |
| 4.01-8.0  | 6        | 20.69%  |
| 2.01-3.0  | 3        | 10.34%  |
| 8.01-16.0 | 2        | 6.9%    |
| 3.01-4.0  | 1        | 3.45%   |
| 0.01-0.5  | 1        | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 37.93%  |
| 4      | 5        | 17.24%  |
| 3      | 5        | 17.24%  |
| 2      | 5        | 17.24%  |
| 5      | 3        | 10.34%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 75.86%  |
| Yes       | 7        | 24.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 96.55%  |
| No        | 1        | 3.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 80%     |
| Yes       | 6        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 86.21%  |
| Yes       | 4        | 13.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 4        | 13.79%  |
| France      | 4        | 13.79%  |
| Ukraine     | 3        | 10.34%  |
| Slovakia    | 3        | 10.34%  |
| Poland      | 2        | 6.9%    |
| Netherlands | 2        | 6.9%    |
| Australia   | 2        | 6.9%    |
| USA         | 1        | 3.45%   |
| UK          | 1        | 3.45%   |
| South Korea | 1        | 3.45%   |
| New Zealand | 1        | 3.45%   |
| Israel      | 1        | 3.45%   |
| Canada      | 1        | 3.45%   |
| Brazil      | 1        | 3.45%   |
| Belgium     | 1        | 3.45%   |
| Argentina   | 1        | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Bratislava     | 3        | 10.34%  |
| Volzhskiy      | 2        | 6.9%    |
| Ryde           | 2        | 6.9%    |
| Bagnolet       | 2        | 6.9%    |
| Zeist          | 1        | 3.45%   |
| Wroclaw        | 1        | 3.45%   |
| Wageningen     | 1        | 3.45%   |
| Toronto        | 1        | 3.45%   |
| Tel Aviv       | 1        | 3.45%   |
| Seongbuk-gu    | 1        | 3.45%   |
| Saint-Herblain | 1        | 3.45%   |
| Rio de Janeiro | 1        | 3.45%   |
| Poperinge      | 1        | 3.45%   |
| Oleksandriya   | 1        | 3.45%   |
| Nérac         | 1        | 3.45%   |
| Mozdok         | 1        | 3.45%   |
| Miedziana Gora | 1        | 3.45%   |
| Miami          | 1        | 3.45%   |
| Kyiv           | 1        | 3.45%   |
| Kirov          | 1        | 3.45%   |
| Donetsk        | 1        | 3.45%   |
| Coghlan        | 1        | 3.45%   |
| Bradford       | 1        | 3.45%   |
| Auckland       | 1        | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 19     | 21.43%  |
| Seagate             | 12       | 19     | 21.43%  |
| Kingston            | 6        | 7      | 10.71%  |
| Toshiba             | 4        | 4      | 7.14%   |
| Samsung Electronics | 4        | 5      | 7.14%   |
| Crucial             | 3        | 4      | 5.36%   |
| Netac               | 2        | 2      | 3.57%   |
| Dogfish             | 2        | 2      | 3.57%   |
| A-DATA Technology   | 2        | 2      | 3.57%   |
| Transcend           | 1        | 2      | 1.79%   |
| Micron Technology   | 1        | 1      | 1.79%   |
| MAXTOR              | 1        | 1      | 1.79%   |
| KingDian            | 1        | 1      | 1.79%   |
| IBM/Hitachi         | 1        | 1      | 1.79%   |
| Hitachi             | 1        | 1      | 1.79%   |
| Hewlett-Packard     | 1        | 2      | 1.79%   |
| GOODRAM             | 1        | 1      | 1.79%   |
| Fujitsu             | 1        | 1      | 1.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WD10EARX-00N0YB0 1TB            | 2        | 3.03%   |
| Seagate ST2000DX002-2DV164 2TB      | 2        | 3.03%   |
| Samsung SSD 860 EVO 250GB           | 2        | 3.03%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 3.03%   |
| Kingston SA2000M8250G 250GB         | 2        | 3.03%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1        | 1.52%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1        | 1.52%   |
| WDC WD800BB-00JHC0 80GB             | 1        | 1.52%   |
| WDC WD5001AALS-00L3B2 500GB         | 1        | 1.52%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1        | 1.52%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1.52%   |
| WDC WD20PURZ-85GU6Y0 2TB            | 1        | 1.52%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1.52%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1.52%   |
| WDC WD1200JS-55NCB1 120GB           | 1        | 1.52%   |
| WDC WD10EZRX-00D8PB0 1TB            | 1        | 1.52%   |
| WDC WD10EZEX-75M2NA0 1TB            | 1        | 1.52%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 1.52%   |
| WDC WD10EZEX-22BN5A0 1TB            | 1        | 1.52%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1.52%   |
| Transcend TS128GSSD370S 128GB       | 1        | 1.52%   |
| Toshiba MQ04ABF100 1TB              | 1        | 1.52%   |
| Toshiba MQ02ABF100 1TB              | 1        | 1.52%   |
| Toshiba HDWD110 1TB                 | 1        | 1.52%   |
| Toshiba DT01ACA100 1TB              | 1        | 1.52%   |
| Seagate ST750LX003-1AC154 752GB     | 1        | 1.52%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1.52%   |
| Seagate ST4000VN008-2DR166 4TB      | 1        | 1.52%   |
| Seagate ST350063 0NS 500GB          | 1        | 1.52%   |
| Seagate ST3500418AS 500GB           | 1        | 1.52%   |
| Seagate ST340014A 40GB              | 1        | 1.52%   |
| Seagate ST3300555SS 304GB           | 1        | 1.52%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 1.52%   |
| Seagate ST3160815A 160GB            | 1        | 1.52%   |
| Seagate ST3160813AS 160GB           | 1        | 1.52%   |
| Seagate ST2000DM006-2DM164 2TB      | 1        | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB      | 1        | 1.52%   |
| Seagate ST1000DM003-1SB102 1TB      | 1        | 1.52%   |
| Seagate BUP Ultra Touch 2TB         | 1        | 1.52%   |
| Samsung SSD 860 EVO 500G            | 1        | 1.52%   |
| Samsung SSD 850 EVO 250GB           | 1        | 1.52%   |
| Netac SSD 720GB                     | 1        | 1.52%   |
| Netac SSD 512GB                     | 1        | 1.52%   |
| Micron 1100_MTFDDAK2T0TBN 2TB SSD   | 1        | 1.52%   |
| MAXTOR 6E040L0 41GB                 | 1        | 1.52%   |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1.52%   |
| Kingston SA400S37960G 960GB SSD     | 1        | 1.52%   |
| Kingston SA2000M8500G 500GB         | 1        | 1.52%   |
| KingDian S400 480GB SSD             | 1        | 1.52%   |
| IBM/Hitachi IC25N030ATCS04-0 32GB   | 1        | 1.52%   |
| Hitachi HDS721616PLA380 160GB       | 1        | 1.52%   |
| HP VB0250EAVER 250GB                | 1        | 1.52%   |
| GOODRAM SSDPR-CX400-128 128GB       | 1        | 1.52%   |
| Fujitsu MHV2060BH PL 64GB           | 1        | 1.52%   |
| DOGFISH SSD 64GB                    | 1        | 1.52%   |
| Dogfish SSD 256GB                   | 1        | 1.52%   |
| Crucial CT500P2SSD8 500GB           | 1        | 1.52%   |
| Crucial CT500MX500SSD1 500GB        | 1        | 1.52%   |
| Crucial CT1000P2SSD8 1TB            | 1        | 1.52%   |
| A-DATA SP600 32GB SSD               | 1        | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Seagate         | 12       | 19     | 38.71%  |
| WDC             | 10       | 17     | 32.26%  |
| Toshiba         | 4        | 4      | 12.9%   |
| MAXTOR          | 1        | 1      | 3.23%   |
| IBM/Hitachi     | 1        | 1      | 3.23%   |
| Hitachi         | 1        | 1      | 3.23%   |
| Hewlett-Packard | 1        | 2      | 3.23%   |
| Fujitsu         | 1        | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 19.05%  |
| Kingston            | 4        | 4      | 19.05%  |
| WDC                 | 2        | 2      | 9.52%   |
| Netac               | 2        | 2      | 9.52%   |
| DOGFISH             | 2        | 2      | 9.52%   |
| A-DATA Technology   | 2        | 2      | 9.52%   |
| Transcend           | 1        | 2      | 4.76%   |
| Micron Technology   | 1        | 1      | 4.76%   |
| KingDian            | 1        | 1      | 4.76%   |
| GOODRAM             | 1        | 1      | 4.76%   |
| Crucial             | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 46     | 52.17%  |
| SSD  | 18       | 23     | 39.13%  |
| NVMe | 4        | 6      | 8.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 63     | 80.56%  |
| NVMe | 4        | 6      | 11.11%  |
| SAS  | 3        | 6      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 40     | 55%     |
| 0.51-1.0   | 11       | 17     | 27.5%   |
| 1.01-2.0   | 5        | 10     | 12.5%   |
| 3.01-4.0   | 2        | 2      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 7        | 22.58%  |
| 251-500        | 6        | 19.35%  |
| 101-250        | 4        | 12.9%   |
| 501-1000       | 4        | 12.9%   |
| 21-50          | 3        | 9.68%   |
| More than 3000 | 2        | 6.45%   |
| 51-100         | 2        | 6.45%   |
| Unknown        | 2        | 6.45%   |
| 1-20           | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 9        | 29.03%  |
| 1-20      | 7        | 22.58%  |
| 21-50     | 4        | 12.9%   |
| 1001-2000 | 4        | 12.9%   |
| 501-1000  | 3        | 9.68%   |
| Unknown   | 2        | 6.45%   |
| 251-500   | 1        | 3.23%   |
| 51-100    | 1        | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB      | 1        | 1      | 11.11%  |
| WDC WD10EARX-00N0YB0 1TB          | 1        | 1      | 11.11%  |
| Toshiba MQ04ABF100 1TB            | 1        | 1      | 11.11%  |
| Toshiba MQ02ABF100 1TB            | 1        | 1      | 11.11%  |
| MAXTOR 6E040L0 41GB               | 1        | 1      | 11.11%  |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 11.11%  |
| Hitachi HDS721616PLA380 160GB     | 1        | 1      | 11.11%  |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 2      | 11.11%  |
| Fujitsu MHV2060BH PL 64GB         | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 2        | 2      | 22.22%  |
| Toshiba         | 2        | 2      | 22.22%  |
| MAXTOR          | 1        | 1      | 11.11%  |
| Kingston        | 1        | 1      | 11.11%  |
| Hitachi         | 1        | 1      | 11.11%  |
| Hewlett-Packard | 1        | 2      | 11.11%  |
| Fujitsu         | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 2        | 2      | 25%     |
| Toshiba         | 2        | 2      | 25%     |
| MAXTOR          | 1        | 1      | 12.5%   |
| Hitachi         | 1        | 1      | 12.5%   |
| Hewlett-Packard | 1        | 2      | 12.5%   |
| Fujitsu         | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 9      | 88.89%  |
| SSD  | 1        | 1      | 11.11%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 20       | 50     | 54.05%  |
| Detected | 9        | 15     | 24.32%  |
| Malfunc  | 8        | 10     | 21.62%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 22       | 57.89%  |
| AMD                              | 6        | 15.79%  |
| Kingston Technology Company      | 3        | 7.89%   |
| Micron/Crucial Technology        | 2        | 5.26%   |
| Silicon Integrated Systems [SiS] | 1        | 2.63%   |
| Marvell Technology Group         | 1        | 2.63%   |
| Broadcom / LSI                   | 1        | 2.63%   |
| ASMedia Technology               | 1        | 2.63%   |
| Adaptec                          | 1        | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Kingston Company A2000 NVMe SSD                                                | 3        | 6.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 6.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 6.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 6.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 6.38%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 6.38%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 4.26%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 4.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 4.26%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1        | 2.13%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1        | 2.13%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 2.13%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 2.13%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 1        | 2.13%   |
| Intel 82801BA IDE U100 Controller                                              | 1        | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 2.13%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                             | 1        | 2.13%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 2.13%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 2.13%   |
| AMD FCH SATA Controller D                                                      | 1        | 2.13%   |
| AMD FCH IDE Controller                                                         | 1        | 2.13%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.13%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 2.13%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                   | 1        | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 21       | 58.33%  |
| IDE  | 8        | 22.22%  |
| NVMe | 4        | 11.11%  |
| RAID | 2        | 5.56%   |
| SCSI | 1        | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 23       | 79.31%  |
| AMD    | 6        | 20.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 6.67%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 6.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 6.67%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 6.67%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1        | 3.33%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 3.33%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 3.33%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 3.33%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 3.33%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 3.33%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 3.33%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 3.33%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 3.33%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1        | 3.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 3.33%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 3.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 3.33%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 3.33%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 3.33%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 3.33%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 3.33%   |
| Intel Celeron (Coppermine)                  | 1        | 3.33%   |
| AMD Sempron Processor 2800+                 | 1        | 3.33%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 3.33%   |
| AMD FX-8300 Eight-Core Processor            | 1        | 3.33%   |
| AMD A4-3300 APU with Radeon HD Graphics     | 1        | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 8        | 26.67%  |
| Intel Xeon              | 3        | 10%     |
| Intel Core 2 Duo        | 3        | 10%     |
| AMD Ryzen 5             | 3        | 10%     |
| Intel Core i7           | 2        | 6.67%   |
| Intel Pentium Silver    | 1        | 3.33%   |
| Intel Pentium Dual-Core | 1        | 3.33%   |
| Intel Pentium Dual      | 1        | 3.33%   |
| Intel Pentium 4         | 1        | 3.33%   |
| Intel Pentium           | 1        | 3.33%   |
| Intel Core i9           | 1        | 3.33%   |
| Intel Core 2 Quad       | 1        | 3.33%   |
| Intel Celeron           | 1        | 3.33%   |
| AMD Sempron             | 1        | 3.33%   |
| AMD FX                  | 1        | 3.33%   |
| AMD A4                  | 1        | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 44.83%  |
| 2      | 7        | 24.14%  |
| 6      | 5        | 17.24%  |
| 1      | 3        | 10.34%  |
| 10     | 1        | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 65.52%  |
| 2      | 10       | 34.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 28       | 96.55%  |
| 32-bit         | 1        | 3.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 16.67%  |
| 0x306a9    | 3        | 10%     |
| 0x1067a    | 3        | 10%     |
| 0x906ea    | 2        | 6.67%   |
| 0x306c3    | 2        | 6.67%   |
| 0x206a7    | 2        | 6.67%   |
| 0xf49      | 1        | 3.33%   |
| 0xa0655    | 1        | 3.33%   |
| 0x706a1    | 1        | 3.33%   |
| 0x6fd      | 1        | 3.33%   |
| 0x686      | 1        | 3.33%   |
| 0x506e3    | 1        | 3.33%   |
| 0x40651    | 1        | 3.33%   |
| 0x106e5    | 1        | 3.33%   |
| 0x10676    | 1        | 3.33%   |
| 0x08701013 | 1        | 3.33%   |
| 0x08001138 | 1        | 3.33%   |
| 0x08001129 | 1        | 3.33%   |
| 0x03000027 | 1        | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 4        | 13.79%  |
| Haswell       | 4        | 13.79%  |
| IvyBridge     | 3        | 10.34%  |
| Zen           | 2        | 6.9%    |
| Skylake       | 2        | 6.9%    |
| SandyBridge   | 2        | 6.9%    |
| KabyLake      | 2        | 6.9%    |
| Zen 2         | 1        | 3.45%   |
| Piledriver    | 1        | 3.45%   |
| P6            | 1        | 3.45%   |
| NetBurst      | 1        | 3.45%   |
| Nehalem       | 1        | 3.45%   |
| K8 Hammer     | 1        | 3.45%   |
| K10 Llano     | 1        | 3.45%   |
| Goldmont plus | 1        | 3.45%   |
| Core          | 1        | 3.45%   |
| CometLake     | 1        | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 12       | 40%     |
| Intel                            | 10       | 33.33%  |
| AMD                              | 7        | 23.33%  |
| Silicon Integrated Systems [SiS] | 1        | 3.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 9.09%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2        | 6.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.06%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 3.03%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 3.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.03%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.03%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 3.03%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 3.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.03%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 3.03%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 3.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.03%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 3.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.03%   |
| AMD RV350 [Radeon 9550] (Secondary)                                         | 1        | 3.03%   |
| AMD RV350 [Radeon 9550]                                                     | 1        | 3.03%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                         | 1        | 3.03%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 3.03%   |
| AMD R350 [Radeon 9800 Series]                                               | 1        | 3.03%   |
| AMD R350 [Radeon 9800 PRO] (Secondary)                                      | 1        | 3.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 3.03%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 3.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 3.03%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 12       | 41.38%  |
| 1 x Intel  | 9        | 31.03%  |
| 1 x AMD    | 6        | 20.69%  |
| 2 x AMD    | 1        | 3.45%   |
| 1 x SiS    | 1        | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 21       | 70%     |
| Proprietary | 8        | 26.67%  |
| Unknown     | 1        | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 31.03%  |
| 0.01-0.5   | 7        | 24.14%  |
| 3.01-4.0   | 3        | 10.34%  |
| 2.01-3.0   | 3        | 10.34%  |
| 0.51-1.0   | 3        | 10.34%  |
| 7.01-8.0   | 2        | 6.9%    |
| 5.01-6.0   | 1        | 3.45%   |
| 1.01-2.0   | 1        | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 9        | 28.13%  |
| Philips              | 3        | 9.38%   |
| Hewlett-Packard      | 3        | 9.38%   |
| Goldstar             | 3        | 9.38%   |
| AOC                  | 3        | 9.38%   |
| Iiyama               | 2        | 6.25%   |
| ViewSonic            | 1        | 3.13%   |
| Toshiba              | 1        | 3.13%   |
| Lenovo               | 1        | 3.13%   |
| HJW                  | 1        | 3.13%   |
| Eizo                 | 1        | 3.13%   |
| Dell                 | 1        | 3.13%   |
| CVT                  | 1        | 3.13%   |
| Ancor Communications | 1        | 3.13%   |
| Acer                 | 1        | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2        | 5.56%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                 | 1        | 2.78%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1        | 2.78%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1        | 2.78%   |
| Samsung Electronics SyncMaster SAM0029 1280x1024 312x234mm 15.4-inch   | 1        | 2.78%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1        | 2.78%   |
| Samsung Electronics LCD Monitor S24D340                                | 1        | 2.78%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1        | 2.78%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 600x340mm 27.2-inch      | 1        | 2.78%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 2.78%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1        | 2.78%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1        | 2.78%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1        | 2.78%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1        | 2.78%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1        | 2.78%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1        | 2.78%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 476x268mm 21.5-inch           | 1        | 2.78%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 470x300mm 22.0-inch           | 1        | 2.78%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch    | 1        | 2.78%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1        | 2.78%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1        | 2.78%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                  | 1        | 2.78%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 2.78%   |
| Eizo EV2456 ENC2798 1920x1200 520x330mm 24.2-inch                      | 1        | 2.78%   |
| Dell LCD Monitor P1914S 1280x1024                                      | 1        | 2.78%   |
| CVT LCD Monitor CVT4668 1440x900 360x290mm 18.2-inch                   | 1        | 2.78%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 1        | 2.78%   |
| AOC Q2790 AOC2790 2560x1440 600x340mm 27.2-inch                        | 1        | 2.78%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                         | 1        | 2.78%   |
| Ancor Communications ASUS VW190 ACI19E9 1366x768 410x230mm 18.5-inch   | 1        | 2.78%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                      | 1        | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 13       | 40.63%  |
| 1280x1024 (SXGA)   | 5        | 15.63%  |
| 3840x2160 (4K)     | 4        | 12.5%   |
| 1600x1200          | 2        | 6.25%   |
| 1366x768 (WXGA)    | 2        | 6.25%   |
| Unknown            | 2        | 6.25%   |
| 5760x1080          | 1        | 3.13%   |
| 1920x1200 (WUXGA)  | 1        | 3.13%   |
| 1680x1050 (WSXGA+) | 1        | 3.13%   |
| 1440x900 (WXGA+)   | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 9        | 29.03%  |
| 27      | 3        | 9.68%   |
| 18      | 3        | 9.68%   |
| 31      | 2        | 6.45%   |
| 24      | 2        | 6.45%   |
| 23      | 2        | 6.45%   |
| 17      | 2        | 6.45%   |
| 15      | 2        | 6.45%   |
| Unknown | 2        | 6.45%   |
| 72      | 1        | 3.23%   |
| 54      | 1        | 3.23%   |
| 22      | 1        | 3.23%   |
| 19      | 1        | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 10       | 35.71%  |
| 501-600     | 7        | 25%     |
| 301-350     | 3        | 10.71%  |
| 601-700     | 2        | 7.14%   |
| 351-400     | 2        | 7.14%   |
| Unknown     | 2        | 7.14%   |
| 1501-2000   | 1        | 3.57%   |
| 1001-1500   | 1        | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 17       | 58.62%  |
| 4/3     | 4        | 13.79%  |
| 5/4     | 3        | 10.34%  |
| 16/10   | 2        | 6.9%    |
| Unknown | 2        | 6.9%    |
| 6/5     | 1        | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 30%     |
| 151-200        | 5        | 16.67%  |
| 141-150        | 4        | 13.33%  |
| 301-350        | 3        | 10%     |
| More than 1000 | 2        | 6.67%   |
| 351-500        | 2        | 6.67%   |
| 111-120        | 2        | 6.67%   |
| Unknown        | 2        | 6.67%   |
| 251-300        | 1        | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 50%     |
| 101-120 | 10       | 33.33%  |
| 1-50    | 2        | 6.67%   |
| Unknown | 2        | 6.67%   |
| 161-240 | 1        | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 82.76%  |
| 3     | 3        | 10.34%  |
| 2     | 2        | 6.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 17       | 48.57%  |
| Intel                            | 10       | 28.57%  |
| Qualcomm Atheros                 | 3        | 8.57%   |
| Marvell Technology Group         | 2        | 5.71%   |
| TP-Link                          | 1        | 2.86%   |
| Silicon Integrated Systems [SiS] | 1        | 2.86%   |
| Ralink Technology                | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 43.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 8.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 2.7%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.7%    |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 2.7%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 2.7%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2.7%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2.7%    |
| Intel Wireless 7260                                               | 1        | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.7%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.7%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.7%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.7%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 2.7%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Qualcomm Atheros  | 2        | 33.33%  |
| Intel             | 2        | 33.33%  |
| TP-Link           | 1        | 16.67%  |
| Ralink Technology | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 16.67%  |
| Ralink MT7601U Wireless Adapter                            | 1        | 16.67%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 16.67%  |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 16.67%  |
| Intel Wireless 7260                                        | 1        | 16.67%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 17       | 56.67%  |
| Intel                            | 9        | 30%     |
| Marvell Technology Group         | 2        | 6.67%   |
| Silicon Integrated Systems [SiS] | 1        | 3.33%   |
| Qualcomm Atheros                 | 1        | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 51.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 9.68%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 3.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 3.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 3.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 3.23%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 3.23%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.23%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.23%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 3.23%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 3.23%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 3.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 3.23%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 82.35%  |
| WiFi     | 6        | 17.65%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 83.33%  |
| WiFi     | 5        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 70%     |
| 2     | 7        | 23.33%  |
| 5     | 1        | 3.33%   |
| 0     | 1        | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 29       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 2        | 50%     |
| Intel                           | 2        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Qualcomm Atheros  Bluetooth Device | 1        | 25%     |
| Qualcomm Atheros AR3011 Bluetooth  | 1        | 25%     |
| Intel Wireless-AC 3168 Bluetooth   | 1        | 25%     |
| Intel Bluetooth wireless interface | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 20       | 42.55%  |
| Nvidia                           | 10       | 21.28%  |
| AMD                              | 7        | 14.89%  |
| Plantronics                      | 2        | 4.26%   |
| Creative Labs                    | 2        | 4.26%   |
| Texas Instruments                | 1        | 2.13%   |
| Silicon Integrated Systems [SiS] | 1        | 2.13%   |
| M-Audio                          | 1        | 2.13%   |
| Logitech                         | 1        | 2.13%   |
| KORG                             | 1        | 2.13%   |
| Cirrus Logic                     | 1        | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 High Definition Audio Controller                              | 4        | 7.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 7.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 5.56%   |
| Plantronics HD1                                                            | 2        | 3.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 3.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 3.7%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 3.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 3.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 3.7%    |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.85%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 1.85%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.85%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.85%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.85%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1        | 1.85%   |
| M-Audio M-Audio 1x1                                                        | 1        | 1.85%   |
| Logitech H390 headset with microphone                                      | 1        | 1.85%   |
| KORG nanoKONTROL studio controller                                         | 1        | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.85%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.85%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1        | 1.85%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.85%   |
| Cirrus Logic Crystal CS4281 PCI Audio                                      | 1        | 1.85%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.85%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 10       | 29.41%  |
| Kingston            | 8        | 23.53%  |
| Corsair             | 3        | 8.82%   |
| SK Hynix            | 2        | 5.88%   |
| Samsung Electronics | 2        | 5.88%   |
| Nanya Technology    | 2        | 5.88%   |
| G.Skill             | 2        | 5.88%   |
| Micron Technology   | 1        | 2.94%   |
| GOODRAM             | 1        | 2.94%   |
| Crucial             | 1        | 2.94%   |
| Avant               | 1        | 2.94%   |
| A-DATA Technology   | 1        | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM 99U5471-054.A00LF 8192MB DIMM DDR3 1600MT/s  | 2        | 5.13%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s | 1        | 2.56%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s               | 1        | 2.56%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                 | 1        | 2.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 2.56%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                | 1        | 2.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1        | 2.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s              | 1        | 2.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 2.56%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                | 1        | 2.56%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                | 1        | 2.56%   |
| Unknown RAM Module 1024MB DIMM DDR                        | 1        | 2.56%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 1        | 2.56%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 2.56%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 2.56%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 2.56%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s    | 1        | 2.56%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 2.56%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s        | 1        | 2.56%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 2.56%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 2.56%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s       | 1        | 2.56%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 1        | 2.56%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 1        | 2.56%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 2.56%   |
| Kingston RAM 99U5471-066.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 2.56%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 2.56%   |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s     | 1        | 2.56%   |
| Kingston RAM 9905471-084.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 2.56%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s        | 1        | 2.56%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s      | 1        | 2.56%   |
| G.Skill RAM F4-2133C15-16GIS 16384MB DIMM DDR4 2133MT/s   | 1        | 2.56%   |
| Crucial RAM CT51264BA160BJ.C8 4GB DIMM DDR3 1600MT/s      | 1        | 2.56%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s     | 1        | 2.56%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 2.56%   |
| Corsair RAM CMD8GX3M2B2133C9 4096MB DIMM DDR3 1333MT/s    | 1        | 2.56%   |
| Avant RAM F6451U67F9333G 4096MB DIMM DDR3 1333MT/s        | 1        | 2.56%   |
| A-DATA RAM DDR4 2666 2OZ 8GB DIMM DDR4 2667MT/s           | 1        | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 11       | 42.31%  |
| DDR4  | 9        | 34.62%  |
| SDRAM | 2        | 7.69%   |
| DDR   | 2        | 7.69%   |
| DRAM  | 1        | 3.85%   |
| DDR2  | 1        | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 23       | 88.46%  |
| SODIMM | 3        | 11.54%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 8        | 26.67%  |
| 8192  | 7        | 23.33%  |
| 16384 | 5        | 16.67%  |
| 2048  | 4        | 13.33%  |
| 1024  | 2        | 6.67%   |
| 32768 | 1        | 3.33%   |
| 256   | 1        | 3.33%   |
| 128   | 1        | 3.33%   |
| 64    | 1        | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 17.24%  |
| 3600    | 3        | 10.34%  |
| 2667    | 3        | 10.34%  |
| 2400    | 3        | 10.34%  |
| 1333    | 3        | 10.34%  |
| 2133    | 2        | 6.9%    |
| 667     | 2        | 6.9%    |
| Unknown | 2        | 6.9%    |
| 3200    | 1        | 3.45%   |
| 1867    | 1        | 3.45%   |
| 1800    | 1        | 3.45%   |
| 800     | 1        | 3.45%   |
| 400     | 1        | 3.45%   |
| 100     | 1        | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Custom Engineering SPA | 1        | 50%     |
| Brother Industries     | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Custom Engineering SPA KUBE USB | 1        | 50%     |
| Brother HL-L2375DW series       | 1        | 50%     |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 1        | 20%     |
| Softkinetic             | 1        | 20%     |
| MacroSilicon            | 1        | 20%     |
| Logitech                | 1        | 20%     |
| GEMBIRD                 | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Z-Star Vimicro USB2.0 Camera | 1        | 20%     |
| Softkinetic DepthSense 325   | 1        | 20%     |
| MacroSilicon USB Video       | 1        | 20%     |
| Logitech Webcam C270         | 1        | 20%     |
| GEMBIRD USB2.0 PC CAMERA     | 1        | 20%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 27       | 93.1%   |
| 2     | 1        | 3.45%   |
| 1     | 1        | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1        | 33.33%  |
| Firewire controller      | 1        | 33.33%  |
| Communication controller | 1        | 33.33%  |

