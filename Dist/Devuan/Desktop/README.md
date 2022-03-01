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
| MSI           | B450M PRO-M2 MAX     | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| ASUSTek       | PRIME H510M-A        | [7ab68e0043](https://linux-hardware.org/?probe=7ab68e0043) | Feb 17, 2022 |
| ASRock        | B450M-HDV R4.0       | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| Gigabyte      | P55A-UD3             | [824dbdd8ad](https://linux-hardware.org/?probe=824dbdd8ad) | Jan 22, 2022 |
| Online Lab... | SR 42                | [e3037eb087](https://linux-hardware.org/?probe=e3037eb087) | Jan 22, 2022 |
| Gigabyte      | H310M S2H x.x        | [9e14e04f7f](https://linux-hardware.org/?probe=9e14e04f7f) | Jan 22, 2022 |
| ASRock        | B450M-HDV R4.0       | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
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
| Intel         | HURONRIVER           | [49bdd1a99d](https://linux-hardware.org/?probe=49bdd1a99d) | Oct 29, 2020 |
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
| 5.10.0-9-amd64       | 4        | 10.53%  |
| 4.19.0-14-amd64      | 4        | 10.53%  |
| 4.19.0-16-amd64      | 3        | 7.89%   |
| 5.10.0-8-amd64       | 2        | 5.26%   |
| 5.10.0-6-amd64       | 2        | 5.26%   |
| 4.19.0-9-amd64       | 2        | 5.26%   |
| 5.9.0-1-amd64        | 1        | 2.63%   |
| 5.8.0-3-amd64        | 1        | 2.63%   |
| 5.7.0-1-amd64        | 1        | 2.63%   |
| 5.7.0-0.bpo.2-amd64  | 1        | 2.63%   |
| 5.16.0-1-amd64       | 1        | 2.63%   |
| 5.15.0-2-amd64       | 1        | 2.63%   |
| 5.15.0-0.bpo.2-amd64 | 1        | 2.63%   |
| 5.10.0-5-amd64       | 1        | 2.63%   |
| 5.10.0-2-amd64       | 1        | 2.63%   |
| 5.10.0-10-amd64      | 1        | 2.63%   |
| 4.9.0-15-amd64       | 1        | 2.63%   |
| 4.9.0-14-686-pae     | 1        | 2.63%   |
| 4.9.0-14-686         | 1        | 2.63%   |
| 4.9.0-11-686-pae     | 1        | 2.63%   |
| 4.19.112             | 1        | 2.63%   |
| 4.19.0-13-amd64      | 1        | 2.63%   |
| 4.19.0-12-amd64      | 1        | 2.63%   |
| 4.19.0-10-amd64      | 1        | 2.63%   |
| 4.19.0-1-amd64       | 1        | 2.63%   |
| 4.19.0-0.bpo.6-amd64 | 1        | 2.63%   |
| 4.18.0-0.bpo.1-amd64 | 1        | 2.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.19.0   | 13       | 35.14%  |
| 5.10.0   | 11       | 29.73%  |
| 4.9.0    | 4        | 10.81%  |
| 5.7.0    | 2        | 5.41%   |
| 5.15.0   | 2        | 5.41%   |
| 5.9.0    | 1        | 2.7%    |
| 5.8.0    | 1        | 2.7%    |
| 5.16.0   | 1        | 2.7%    |
| 4.19.112 | 1        | 2.7%    |
| 4.18.0   | 1        | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 14       | 37.84%  |
| 5.10    | 11       | 29.73%  |
| 4.9     | 4        | 10.81%  |
| 5.7     | 2        | 5.41%   |
| 5.15    | 2        | 5.41%   |
| 5.9     | 1        | 2.7%    |
| 5.8     | 1        | 2.7%    |
| 5.16    | 1        | 2.7%    |
| 4.18    | 1        | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 33       | 91.67%  |
| i686   | 3        | 8.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| XFCE       | 20       | 54.05%  |
| Unknown    | 7        | 18.92%  |
| MATE       | 3        | 8.11%   |
| LXDE       | 2        | 5.41%   |
| KDE5       | 2        | 5.41%   |
| X-Cinnamon | 1        | 2.7%    |
| i3         | 1        | 2.7%    |
| awesome    | 1        | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 30       | 83.33%  |
| Tty     | 5        | 13.89%  |
| Unknown | 1        | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 19       | 52.78%  |
| Unknown | 8        | 22.22%  |
| LightDM | 7        | 19.44%  |
| XDM     | 1        | 2.78%   |
| NODM    | 1        | 2.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 9        | 25%     |
| fr_FR   | 4        | 11.11%  |
| en_GB   | 4        | 11.11%  |
| Unknown | 4        | 11.11%  |
| sk_SK   | 3        | 8.33%   |
| C       | 3        | 8.33%   |
| ru_RU   | 2        | 5.56%   |
| pt_BR   | 2        | 5.56%   |
| en_AU   | 2        | 5.56%   |
| pl_PL   | 1        | 2.78%   |
| en_NZ   | 1        | 2.78%   |
| en_CA   | 1        | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 27       | 75%     |
| EFI  | 9        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 32       | 88.89%  |
| Overlay | 2        | 5.56%   |
| Ext3    | 1        | 2.78%   |
| Unknown | 1        | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 18       | 47.37%  |
| GPT     | 17       | 44.74%  |
| Unknown | 3        | 7.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 62.16%  |
| Yes       | 14       | 37.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 72.22%  |
| Yes       | 10       | 27.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 10       | 27.78%  |
| ASUSTek Computer    | 8        | 22.22%  |
| ASRock              | 4        | 11.11%  |
| MSI                 | 3        | 8.33%   |
| Hewlett-Packard     | 3        | 8.33%   |
| Intel               | 2        | 5.56%   |
| Sun Microsystems    | 1        | 2.78%   |
| Online Labs         | 1        | 2.78%   |
| Lenovo              | 1        | 2.78%   |
| Google              | 1        | 2.78%   |
| Dell                | 1        | 2.78%   |
| Acer                | 1        | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Sun Microsystems Ultra 24       | 1        | 2.78%   |
| Online Labs SR                  | 1        | 2.78%   |
| MSI MS-7B84                     | 1        | 2.78%   |
| MSI MS-7B53                     | 1        | 2.78%   |
| MSI MS-7A34                     | 1        | 2.78%   |
| Lenovo ThinkStation E20 4220CTO | 1        | 2.78%   |
| Intel D815EEA AAA45884-401      | 1        | 2.78%   |
| Intel AHV                       | 1        | 2.78%   |
| HP Z220 SFF Workstation         | 1        | 2.78%   |
| HP EliteDesk 800 G1 DM          | 1        | 2.78%   |
| HP Compaq 8200 Elite SFF PC     | 1        | 2.78%   |
| Google Panther                  | 1        | 2.78%   |
| Gigabyte Z390 GAMING SLI        | 1        | 2.78%   |
| Gigabyte P55A-UD3               | 1        | 2.78%   |
| Gigabyte MZGLKBP-00             | 1        | 2.78%   |
| Gigabyte H310M S2H 2.0          | 1        | 2.78%   |
| Gigabyte H170-HD3-CF            | 1        | 2.78%   |
| Gigabyte H170-HD3               | 1        | 2.78%   |
| Gigabyte GA-G41M-ES2L           | 1        | 2.78%   |
| Gigabyte B75M-D3V               | 1        | 2.78%   |
| Gigabyte B450 AORUS ELITE       | 1        | 2.78%   |
| Gigabyte 970A-DS3P              | 1        | 2.78%   |
| Dell OptiPlex 7010              | 1        | 2.78%   |
| ASUS PRIME Z490M-PLUS           | 1        | 2.78%   |
| ASUS PRIME H510M-A              | 1        | 2.78%   |
| ASUS P5PE-VM                    | 1        | 2.78%   |
| ASUS P5G41T-M LX2/BR            | 1        | 2.78%   |
| ASUS Maximus V GENE             | 1        | 2.78%   |
| ASUS F1A55-M LX                 | 1        | 2.78%   |
| ASUS EX-A320M-GAMING            | 1        | 2.78%   |
| ASUS All Series                 | 1        | 2.78%   |
| ASRock K8A780LM                 | 1        | 2.78%   |
| ASRock H81M-ITX                 | 1        | 2.78%   |
| ASRock G31M-VS2                 | 1        | 2.78%   |
| ASRock B450M-HDV R4.0           | 1        | 2.78%   |
| Acer Aspire M1610               | 1        | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 2        | 5.56%   |
| Sun Microsystems Ultra | 1        | 2.78%   |
| Online Labs SR         | 1        | 2.78%   |
| MSI MS-7B84            | 1        | 2.78%   |
| MSI MS-7B53            | 1        | 2.78%   |
| MSI MS-7A34            | 1        | 2.78%   |
| Lenovo ThinkStation    | 1        | 2.78%   |
| Intel D815EEA          | 1        | 2.78%   |
| Intel AHV              | 1        | 2.78%   |
| HP Z220                | 1        | 2.78%   |
| HP EliteDesk           | 1        | 2.78%   |
| HP Compaq              | 1        | 2.78%   |
| Google Panther         | 1        | 2.78%   |
| Gigabyte Z390          | 1        | 2.78%   |
| Gigabyte P55A-UD3      | 1        | 2.78%   |
| Gigabyte MZGLKBP-00    | 1        | 2.78%   |
| Gigabyte H310M         | 1        | 2.78%   |
| Gigabyte H170-HD3-CF   | 1        | 2.78%   |
| Gigabyte H170-HD3      | 1        | 2.78%   |
| Gigabyte GA-G41M-ES2L  | 1        | 2.78%   |
| Gigabyte B75M-D3V      | 1        | 2.78%   |
| Gigabyte B450          | 1        | 2.78%   |
| Gigabyte 970A-DS3P     | 1        | 2.78%   |
| Dell OptiPlex          | 1        | 2.78%   |
| ASUS P5PE-VM           | 1        | 2.78%   |
| ASUS P5G41T-M          | 1        | 2.78%   |
| ASUS Maximus           | 1        | 2.78%   |
| ASUS F1A55-M           | 1        | 2.78%   |
| ASUS EX-A320M-GAMING   | 1        | 2.78%   |
| ASUS All               | 1        | 2.78%   |
| ASRock K8A780LM        | 1        | 2.78%   |
| ASRock H81M-ITX        | 1        | 2.78%   |
| ASRock G31M-VS2        | 1        | 2.78%   |
| ASRock B450M-HDV       | 1        | 2.78%   |
| Acer Aspire            | 1        | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 8        | 22.22%  |
| 2014 | 4        | 11.11%  |
| 2012 | 4        | 11.11%  |
| 2013 | 3        | 8.33%   |
| 2011 | 3        | 8.33%   |
| 2017 | 2        | 5.56%   |
| 2015 | 2        | 5.56%   |
| 2009 | 2        | 5.56%   |
| 2021 | 1        | 2.78%   |
| 2020 | 1        | 2.78%   |
| 2019 | 1        | 2.78%   |
| 2010 | 1        | 2.78%   |
| 2008 | 1        | 2.78%   |
| 2007 | 1        | 2.78%   |
| 2006 | 1        | 2.78%   |
| 2000 | 1        | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 36       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 36       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 94.44%  |
| Yes  | 2        | 5.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 10       | 27.78%  |
| 8.01-16.0  | 9        | 25%     |
| 32.01-64.0 | 6        | 16.67%  |
| 4.01-8.0   | 5        | 13.89%  |
| 1.01-2.0   | 3        | 8.33%   |
| 3.01-4.0   | 2        | 5.56%   |
| 0.01-0.5   | 1        | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 10       | 27.03%  |
| 4.01-8.0  | 8        | 21.62%  |
| 0.51-1.0  | 7        | 18.92%  |
| 2.01-3.0  | 6        | 16.22%  |
| 3.01-4.0  | 3        | 8.11%   |
| 8.01-16.0 | 2        | 5.41%   |
| 0.01-0.5  | 1        | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 44.44%  |
| 3      | 7        | 19.44%  |
| 4      | 5        | 13.89%  |
| 2      | 5        | 13.89%  |
| 5      | 3        | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 69.44%  |
| Yes       | 11       | 30.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 35       | 97.22%  |
| No        | 1        | 2.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 81.08%  |
| Yes       | 7        | 18.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 88.89%  |
| Yes       | 4        | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| France      | 6        | 16.67%  |
| Russia      | 4        | 11.11%  |
| Ukraine     | 3        | 8.33%   |
| Slovakia    | 3        | 8.33%   |
| USA         | 2        | 5.56%   |
| UK          | 2        | 5.56%   |
| Poland      | 2        | 5.56%   |
| Netherlands | 2        | 5.56%   |
| Brazil      | 2        | 5.56%   |
| Australia   | 2        | 5.56%   |
| Argentina   | 2        | 5.56%   |
| South Korea | 1        | 2.78%   |
| Puerto Rico | 1        | 2.78%   |
| New Zealand | 1        | 2.78%   |
| Israel      | 1        | 2.78%   |
| Canada      | 1        | 2.78%   |
| Belgium     | 1        | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Bratislava     | 3        | 8.33%   |
| Bagnolet       | 3        | 8.33%   |
| Volzhskiy      | 2        | 5.56%   |
| Ryde           | 2        | 5.56%   |
| Zeist          | 1        | 2.78%   |
| Wroclaw        | 1        | 2.78%   |
| Wageningen     | 1        | 2.78%   |
| Toronto        | 1        | 2.78%   |
| Tel Aviv       | 1        | 2.78%   |
| SГЈo Paulo   | 1        | 2.78%   |
| Seongbuk-gu    | 1        | 2.78%   |
| Saint-Herblain | 1        | 2.78%   |
| Rio de Janeiro | 1        | 2.78%   |
| Poperinge      | 1        | 2.78%   |
| Paris          | 1        | 2.78%   |
| Oleksandriya   | 1        | 2.78%   |
| NГ©rac       | 1        | 2.78%   |
| Mozdok         | 1        | 2.78%   |
| Miedziana Gora | 1        | 2.78%   |
| Miami          | 1        | 2.78%   |
| Kyiv           | 1        | 2.78%   |
| Kirov          | 1        | 2.78%   |
| Great Bend     | 1        | 2.78%   |
| Donetsk        | 1        | 2.78%   |
| Coghlan        | 1        | 2.78%   |
| Cipolletti     | 1        | 2.78%   |
| Carlisle       | 1        | 2.78%   |
| Caguas         | 1        | 2.78%   |
| Bradford       | 1        | 2.78%   |
| Auckland       | 1        | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 25     | 23.08%  |
| Seagate             | 14       | 22     | 21.54%  |
| Kingston            | 8        | 9      | 12.31%  |
| Toshiba             | 4        | 4      | 6.15%   |
| Samsung Electronics | 4        | 5      | 6.15%   |
| Crucial             | 3        | 4      | 4.62%   |
| Netac               | 2        | 2      | 3.08%   |
| DOGFISH             | 2        | 2      | 3.08%   |
| A-DATA Technology   | 2        | 2      | 3.08%   |
| WD MediaMax         | 1        | 2      | 1.54%   |
| Transcend           | 1        | 2      | 1.54%   |
| Micron Technology   | 1        | 1      | 1.54%   |
| MAXTOR              | 1        | 1      | 1.54%   |
| KingDian            | 1        | 1      | 1.54%   |
| IBM/Hitachi         | 1        | 1      | 1.54%   |
| Hitachi             | 1        | 1      | 1.54%   |
| HGST                | 1        | 1      | 1.54%   |
| Hewlett-Packard     | 1        | 2      | 1.54%   |
| GOODRAM             | 1        | 1      | 1.54%   |
| Fujitsu             | 1        | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA2000M8250G 250GB         | 3        | 3.95%   |
| WDC WD10EARX-00N0YB0 1TB            | 2        | 2.63%   |
| Seagate ST2000DX002-2DV164 2TB      | 2        | 2.63%   |
| Samsung SSD 860 EVO 250GB           | 2        | 2.63%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 2.63%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1        | 1.32%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1        | 1.32%   |
| WDC WD800BB-00JHC0 80GB             | 1        | 1.32%   |
| WDC WD5001AALS-00L3B2 500GB         | 1        | 1.32%   |
| WDC WD5001AALS-00E3A0 500GB         | 1        | 1.32%   |
| WDC WD5000LPVX-00V0TT0 500GB        | 1        | 1.32%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1        | 1.32%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1.32%   |
| WDC WD20PURZ-85GU6Y0 2TB            | 1        | 1.32%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1.32%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1.32%   |
| WDC WD1200JS-55NCB1 120GB           | 1        | 1.32%   |
| WDC WD10EZRX-00D8PB0 1TB            | 1        | 1.32%   |
| WDC WD10EZEX-75M2NA0 1TB            | 1        | 1.32%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 1.32%   |
| WDC WD10EZEX-22BN5A0 1TB            | 1        | 1.32%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1.32%   |
| WDC WD10EURX-63FH1Y0 1TB            | 1        | 1.32%   |
| WD MediaMax WL500GSA3272 500GB      | 1        | 1.32%   |
| Transcend TS128GSSD370S 128GB       | 1        | 1.32%   |
| Toshiba MQ04ABF100 1TB              | 1        | 1.32%   |
| Toshiba MQ02ABF100 1TB              | 1        | 1.32%   |
| Toshiba HDWD110 1TB                 | 1        | 1.32%   |
| Toshiba DT01ACA100 1TB              | 1        | 1.32%   |
| Seagate ST8000DM004-2CX188 8TB      | 1        | 1.32%   |
| Seagate ST750LX003-1AC154 752GB     | 1        | 1.32%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1.32%   |
| Seagate ST4000VN008-2DR166 4TB      | 1        | 1.32%   |
| Seagate ST4000DM005-2DP166 4TB      | 1        | 1.32%   |
| Seagate ST350063 0NS 500GB          | 1        | 1.32%   |
| Seagate ST3500418AS 500GB           | 1        | 1.32%   |
| Seagate ST340014A 40GB              | 1        | 1.32%   |
| Seagate ST3300555SS 304GB           | 1        | 1.32%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 1.32%   |
| Seagate ST3160815A 160GB            | 1        | 1.32%   |
| Seagate ST3160813AS 160GB           | 1        | 1.32%   |
| Seagate ST2000DM008-2FR102 2TB      | 1        | 1.32%   |
| Seagate ST2000DM006-2DM164 2TB      | 1        | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB      | 1        | 1.32%   |
| Seagate ST1000DM003-1SB102 1TB      | 1        | 1.32%   |
| Seagate BUP Ultra Touch 2TB         | 1        | 1.32%   |
| Samsung SSD 860 EVO 500G            | 1        | 1.32%   |
| Samsung SSD 850 EVO 250GB           | 1        | 1.32%   |
| Netac SSD 720GB                     | 1        | 1.32%   |
| Netac SSD 512GB                     | 1        | 1.32%   |
| Micron 1100_MTFDDAK2T0TBN 2TB SSD   | 1        | 1.32%   |
| MAXTOR 6E040L0 41GB                 | 1        | 1.32%   |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1.32%   |
| Kingston SA400S37960G 960GB SSD     | 1        | 1.32%   |
| Kingston SA400S37480G 480GB SSD     | 1        | 1.32%   |
| Kingston SA2000M8500G 500GB         | 1        | 1.32%   |
| KingDian S400 480GB SSD             | 1        | 1.32%   |
| IBM/Hitachi IC25N030ATCS04-0 32GB   | 1        | 1.32%   |
| Hitachi HDS721616PLA380 164GB       | 1        | 1.32%   |
| HGST HTE721010A9E630 1TB            | 1        | 1.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Seagate         | 14       | 22     | 37.84%  |
| WDC             | 13       | 23     | 35.14%  |
| Toshiba         | 4        | 4      | 10.81%  |
| MAXTOR          | 1        | 1      | 2.7%    |
| IBM/Hitachi     | 1        | 1      | 2.7%    |
| Hitachi         | 1        | 1      | 2.7%    |
| HGST            | 1        | 1      | 2.7%    |
| Hewlett-Packard | 1        | 2      | 2.7%    |
| Fujitsu         | 1        | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 5      | 22.73%  |
| Samsung Electronics | 4        | 5      | 18.18%  |
| WDC                 | 2        | 2      | 9.09%   |
| Netac               | 2        | 2      | 9.09%   |
| DOGFISH             | 2        | 2      | 9.09%   |
| A-DATA Technology   | 2        | 2      | 9.09%   |
| Transcend           | 1        | 2      | 4.55%   |
| Micron Technology   | 1        | 1      | 4.55%   |
| KingDian            | 1        | 1      | 4.55%   |
| GOODRAM             | 1        | 1      | 4.55%   |
| Crucial             | 1        | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 30       | 56     | 54.55%  |
| SSD     | 19       | 24     | 34.55%  |
| NVMe    | 5        | 7      | 9.09%   |
| Unknown | 1        | 2      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 36       | 76     | 81.82%  |
| NVMe | 5        | 7      | 11.36%  |
| SAS  | 3        | 6      | 6.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 25       | 43     | 52.08%  |
| 0.51-1.0   | 13       | 22     | 27.08%  |
| 1.01-2.0   | 6        | 11     | 12.5%   |
| 3.01-4.0   | 3        | 3      | 6.25%   |
| 4.01-10.0  | 1        | 1      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 9        | 23.08%  |
| 1001-2000      | 9        | 23.08%  |
| 101-250        | 5        | 12.82%  |
| 501-1000       | 5        | 12.82%  |
| More than 3000 | 3        | 7.69%   |
| 21-50          | 3        | 7.69%   |
| 51-100         | 2        | 5.13%   |
| Unknown        | 2        | 5.13%   |
| 1-20           | 1        | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14       | 36.84%  |
| 1-20           | 8        | 21.05%  |
| 21-50          | 4        | 10.53%  |
| 1001-2000      | 4        | 10.53%  |
| 501-1000       | 3        | 7.89%   |
| Unknown        | 2        | 5.26%   |
| More than 3000 | 1        | 2.63%   |
| 251-500        | 1        | 2.63%   |
| 51-100         | 1        | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB      | 1        | 1      | 9.09%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1        | 1      | 9.09%   |
| WDC WD10EARX-00N0YB0 1TB          | 1        | 1      | 9.09%   |
| Toshiba MQ04ABF100 1TB            | 1        | 1      | 9.09%   |
| Toshiba MQ02ABF100 1TB            | 1        | 1      | 9.09%   |
| MAXTOR 6E040L0 41GB               | 1        | 1      | 9.09%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 9.09%   |
| Hitachi HDS721616PLA380 164GB     | 1        | 1      | 9.09%   |
| HGST HTE721010A9E630 1TB          | 1        | 1      | 9.09%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 2      | 9.09%   |
| Fujitsu MHV2060BH PL 64GB         | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 3        | 3      | 27.27%  |
| Toshiba         | 2        | 2      | 18.18%  |
| MAXTOR          | 1        | 1      | 9.09%   |
| Kingston        | 1        | 1      | 9.09%   |
| Hitachi         | 1        | 1      | 9.09%   |
| HGST            | 1        | 1      | 9.09%   |
| Hewlett-Packard | 1        | 2      | 9.09%   |
| Fujitsu         | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 3        | 3      | 30%     |
| Toshiba         | 2        | 2      | 20%     |
| MAXTOR          | 1        | 1      | 10%     |
| Hitachi         | 1        | 1      | 10%     |
| HGST            | 1        | 1      | 10%     |
| Hewlett-Packard | 1        | 2      | 10%     |
| Fujitsu         | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 11     | 90.91%  |
| SSD  | 1        | 1      | 9.09%   |

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
| Works    | 24       | 56     | 54.55%  |
| Detected | 10       | 21     | 22.73%  |
| Malfunc  | 10       | 12     | 22.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 27       | 56.25%  |
| AMD                              | 8        | 16.67%  |
| Kingston Technology Company      | 4        | 8.33%   |
| Micron/Crucial Technology        | 2        | 4.17%   |
| Marvell Technology Group         | 2        | 4.17%   |
| Silicon Integrated Systems [SiS] | 1        | 2.08%   |
| Integrated Technology Express    | 1        | 2.08%   |
| Broadcom / LSI                   | 1        | 2.08%   |
| ASMedia Technology               | 1        | 2.08%   |
| Adaptec                          | 1        | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 8.47%   |
| Kingston Company A2000 NVMe SSD                                                | 4        | 6.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 5.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 5.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 5.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 5.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 5.08%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 3.39%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 3.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 3.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 3.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 3.39%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1        | 1.69%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1        | 1.69%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 1.69%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                        | 1        | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.69%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 1        | 1.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 1.69%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 1        | 1.69%   |
| Intel 82801BA IDE U100 Controller                                              | 1        | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.69%   |
| Integrated Express IT8213 IDE Controller                                       | 1        | 1.69%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                             | 1        | 1.69%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 1.69%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 1.69%   |
| AMD FCH SATA Controller D                                                      | 1        | 1.69%   |
| AMD FCH IDE Controller                                                         | 1        | 1.69%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 1.69%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                   | 1        | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 28       | 62.22%  |
| IDE  | 9        | 20%     |
| NVMe | 5        | 11.11%  |
| RAID | 2        | 4.44%   |
| SCSI | 1        | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 28       | 77.78%  |
| AMD    | 8        | 22.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 5.41%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 5.41%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 5.41%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 5.41%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1        | 2.7%    |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 2.7%    |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 2.7%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 2.7%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 2.7%    |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 2.7%    |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 2.7%    |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 2.7%    |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 2.7%    |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 2.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1        | 2.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 2.7%    |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 2.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2.7%    |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 2.7%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 2.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1        | 2.7%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 2.7%    |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 2.7%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 2.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 2.7%    |
| Intel Celeron (Coppermine)                  | 1        | 2.7%    |
| Intel Atom CPU C2750 @ 2.40GHz              | 1        | 2.7%    |
| AMD Sempron Processor 2800+                 | 1        | 2.7%    |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 2.7%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 2.7%    |
| AMD Ryzen 3 3100 4-Core Processor           | 1        | 2.7%    |
| AMD FX-8300 Eight-Core Processor            | 1        | 2.7%    |
| AMD A4-3300 APU with Radeon HD Graphics     | 1        | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 11       | 29.73%  |
| Intel Xeon              | 3        | 8.11%   |
| Intel Core 2 Duo        | 3        | 8.11%   |
| AMD Ryzen 5             | 3        | 8.11%   |
| Intel Core i7           | 2        | 5.41%   |
| AMD Ryzen 3             | 2        | 5.41%   |
| Intel Pentium Silver    | 1        | 2.7%    |
| Intel Pentium Gold      | 1        | 2.7%    |
| Intel Pentium Dual-Core | 1        | 2.7%    |
| Intel Pentium Dual      | 1        | 2.7%    |
| Intel Pentium 4         | 1        | 2.7%    |
| Intel Pentium           | 1        | 2.7%    |
| Intel Core i9           | 1        | 2.7%    |
| Intel Core 2 Quad       | 1        | 2.7%    |
| Intel Celeron           | 1        | 2.7%    |
| Intel Atom              | 1        | 2.7%    |
| AMD Sempron             | 1        | 2.7%    |
| AMD FX                  | 1        | 2.7%    |
| AMD A4                  | 1        | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 16       | 44.44%  |
| 2      | 9        | 25%     |
| 6      | 6        | 16.67%  |
| 1      | 3        | 8.33%   |
| 10     | 1        | 2.78%   |
| 8      | 1        | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 61.11%  |
| 2      | 14       | 38.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 35       | 97.22%  |
| 32-bit         | 1        | 2.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 21.62%  |
| 0x306a9    | 3        | 8.11%   |
| 0x206a7    | 3        | 8.11%   |
| 0x1067a    | 3        | 8.11%   |
| 0x906ea    | 2        | 5.41%   |
| 0x306c3    | 2        | 5.41%   |
| 0xf49      | 1        | 2.7%    |
| 0xa0655    | 1        | 2.7%    |
| 0xa0653    | 1        | 2.7%    |
| 0x706a1    | 1        | 2.7%    |
| 0x6fd      | 1        | 2.7%    |
| 0x686      | 1        | 2.7%    |
| 0x506e3    | 1        | 2.7%    |
| 0x406d8    | 1        | 2.7%    |
| 0x40651    | 1        | 2.7%    |
| 0x106e5    | 1        | 2.7%    |
| 0x10676    | 1        | 2.7%    |
| 0x08701021 | 1        | 2.7%    |
| 0x08701013 | 1        | 2.7%    |
| 0x08001138 | 1        | 2.7%    |
| 0x08001129 | 1        | 2.7%    |
| 0x03000027 | 1        | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 4        | 11.11%  |
| Haswell       | 4        | 11.11%  |
| SandyBridge   | 3        | 8.33%   |
| KabyLake      | 3        | 8.33%   |
| IvyBridge     | 3        | 8.33%   |
| Zen 2         | 2        | 5.56%   |
| Zen           | 2        | 5.56%   |
| Skylake       | 2        | 5.56%   |
| Nehalem       | 2        | 5.56%   |
| CometLake     | 2        | 5.56%   |
| Zen+          | 1        | 2.78%   |
| Silvermont    | 1        | 2.78%   |
| Piledriver    | 1        | 2.78%   |
| P6            | 1        | 2.78%   |
| NetBurst      | 1        | 2.78%   |
| K8 Hammer     | 1        | 2.78%   |
| K10 Llano     | 1        | 2.78%   |
| Goldmont plus | 1        | 2.78%   |
| Core          | 1        | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 13       | 36.11%  |
| Nvidia                           | 12       | 33.33%  |
| AMD                              | 10       | 27.78%  |
| Silicon Integrated Systems [SiS] | 1        | 2.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 7.69%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 2        | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 5.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 5.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 5.13%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 2.56%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 2.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.56%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.56%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.56%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 2.56%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 2.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.56%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 2.56%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 2.56%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 2.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.56%   |
| AMD RV350 [Radeon 9550] (Secondary)                                         | 1        | 2.56%   |
| AMD RV350 [Radeon 9550]                                                     | 1        | 2.56%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                         | 1        | 2.56%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 2.56%   |
| AMD R350 [Radeon 9800 Series]                                               | 1        | 2.56%   |
| AMD R350 [Radeon 9800 PRO] (Secondary)                                      | 1        | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.56%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 2.56%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 12       | 33.33%  |
| 1 x Intel  | 12       | 33.33%  |
| 1 x AMD    | 9        | 25%     |
| Other      | 1        | 2.78%   |
| 2 x AMD    | 1        | 2.78%   |
| 1 x SiS    | 1        | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 25       | 67.57%  |
| Proprietary | 8        | 21.62%  |
| Unknown     | 4        | 10.81%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 38.89%  |
| 0.01-0.5   | 7        | 19.44%  |
| 3.01-4.0   | 4        | 11.11%  |
| 0.51-1.0   | 4        | 11.11%  |
| 2.01-3.0   | 3        | 8.33%   |
| 7.01-8.0   | 2        | 5.56%   |
| 5.01-6.0   | 1        | 2.78%   |
| 1.01-2.0   | 1        | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 27.03%  |
| Goldstar             | 4        | 10.81%  |
| Philips              | 3        | 8.11%   |
| Hewlett-Packard      | 3        | 8.11%   |
| AOC                  | 3        | 8.11%   |
| Lenovo               | 2        | 5.41%   |
| Iiyama               | 2        | 5.41%   |
| Acer                 | 2        | 5.41%   |
| ViewSonic            | 1        | 2.7%    |
| Toshiba              | 1        | 2.7%    |
| HJW                  | 1        | 2.7%    |
| eMachines            | 1        | 2.7%    |
| Eizo                 | 1        | 2.7%    |
| Dell                 | 1        | 2.7%    |
| CVT                  | 1        | 2.7%    |
| Ancor Communications | 1        | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2        | 4.88%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                 | 1        | 2.44%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1        | 2.44%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM0029 1280x1024 312x234mm 15.4-inch   | 1        | 2.44%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch  | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SA300/350/360                          | 1        | 2.44%   |
| Samsung Electronics LCD Monitor S24D340                                | 1        | 2.44%   |
| Samsung Electronics LCD Monitor C27F390 5760x1080                      | 1        | 2.44%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1        | 2.44%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 2.44%   |
| Philips 190B PHL086C 1280x1024 376x301mm 19.0-inch                     | 1        | 2.44%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 1        | 2.44%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                  | 1        | 2.44%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                | 1        | 2.44%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 1        | 2.44%   |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1        | 2.44%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1        | 2.44%   |
| Hewlett-Packard LA2206 HWP2947 1920x1080 476x268mm 21.5-inch           | 1        | 2.44%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 470x300mm 22.0-inch           | 1        | 2.44%   |
| Hewlett-Packard Compaq S2321a HWP2915 1920x1080 509x286mm 23.0-inch    | 1        | 2.44%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1        | 2.44%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                   | 1        | 2.44%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1        | 2.44%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 2.44%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                  | 1        | 2.44%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 1        | 2.44%   |
| Eizo EV2456 ENC2798 1920x1200 520x330mm 24.2-inch                      | 1        | 2.44%   |
| Dell LCD Monitor P1914S 1280x1024                                      | 1        | 2.44%   |
| CVT LCD Monitor CVT4668 1440x900 360x290mm 18.2-inch                   | 1        | 2.44%   |
| AOC U2790B AOC2790 3840x2160 600x340mm 27.2-inch                       | 1        | 2.44%   |
| AOC 32G1WG4 AOC3201 1920x1080 697x392mm 31.5-inch                      | 1        | 2.44%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                         | 1        | 2.44%   |
| Ancor Communications ASUS VW190 ACI19E9 1366x768 410x230mm 18.5-inch   | 1        | 2.44%   |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                      | 1        | 2.44%   |
| Acer V206HQL ACR0334 1600x900 432x240mm 19.5-inch                      | 1        | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 37.84%  |
| 1280x1024 (SXGA)   | 5        | 13.51%  |
| 3840x2160 (4K)     | 4        | 10.81%  |
| 1440x900 (WXGA+)   | 3        | 8.11%   |
| 1366x768 (WXGA)    | 3        | 8.11%   |
| 1600x1200          | 2        | 5.41%   |
| Unknown            | 2        | 5.41%   |
| 5760x1080          | 1        | 2.7%    |
| 1920x1200 (WUXGA)  | 1        | 2.7%    |
| 1680x1050 (WSXGA+) | 1        | 2.7%    |
| 1600x900 (HD+)     | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 10       | 28.57%  |
| 27      | 3        | 8.57%   |
| 19      | 3        | 8.57%   |
| 18      | 3        | 8.57%   |
| 31      | 2        | 5.71%   |
| 24      | 2        | 5.71%   |
| 23      | 2        | 5.71%   |
| 17      | 2        | 5.71%   |
| 15      | 2        | 5.71%   |
| Unknown | 2        | 5.71%   |
| 72      | 1        | 2.86%   |
| 54      | 1        | 2.86%   |
| 22      | 1        | 2.86%   |
| 14      | 1        | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 13       | 40.63%  |
| 501-600     | 7        | 21.88%  |
| 301-350     | 4        | 12.5%   |
| 601-700     | 2        | 6.25%   |
| 351-400     | 2        | 6.25%   |
| Unknown     | 2        | 6.25%   |
| 1501-2000   | 1        | 3.13%   |
| 1001-1500   | 1        | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 58.82%  |
| 4/3     | 4        | 11.76%  |
| 16/10   | 4        | 11.76%  |
| 5/4     | 3        | 8.82%   |
| Unknown | 2        | 5.88%   |
| 6/5     | 1        | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 32.35%  |
| 151-200        | 6        | 17.65%  |
| 141-150        | 4        | 11.76%  |
| 301-350        | 3        | 8.82%   |
| More than 1000 | 2        | 5.88%   |
| 351-500        | 2        | 5.88%   |
| 111-120        | 2        | 5.88%   |
| Unknown        | 2        | 5.88%   |
| 81-90          | 1        | 2.94%   |
| 251-300        | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 50%     |
| 101-120 | 12       | 35.29%  |
| 1-50    | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| 161-240 | 1        | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 75%     |
| 3     | 3        | 8.33%   |
| 2     | 3        | 8.33%   |
| 0     | 3        | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 22       | 48.89%  |
| Intel                            | 14       | 31.11%  |
| Qualcomm Atheros                 | 3        | 6.67%   |
| Marvell Technology Group         | 2        | 4.44%   |
| TP-Link                          | 1        | 2.22%   |
| Silicon Integrated Systems [SiS] | 1        | 2.22%   |
| Ralink Technology                | 1        | 2.22%   |
| JMicron Technology               | 1        | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 42.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 6.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 2.13%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 2.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 2.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.13%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 2.13%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 2.13%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2.13%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2.13%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 2.13%   |
| Intel Wireless 7260                                               | 1        | 2.13%   |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.13%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.13%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.13%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.13%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.13%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.13%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.13%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 2.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 2.13%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Qualcomm Atheros      | 2        | 28.57%  |
| Intel                 | 2        | 28.57%  |
| TP-Link               | 1        | 14.29%  |
| Realtek Semiconductor | 1        | 14.29%  |
| Ralink Technology     | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 14.29%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1        | 14.29%  |
| Ralink MT7601U Wireless Adapter                            | 1        | 14.29%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 14.29%  |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 14.29%  |
| Intel Wireless 7260                                        | 1        | 14.29%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 21       | 53.85%  |
| Intel                            | 13       | 33.33%  |
| Marvell Technology Group         | 2        | 5.13%   |
| Silicon Integrated Systems [SiS] | 1        | 2.56%   |
| Qualcomm Atheros                 | 1        | 2.56%   |
| JMicron Technology               | 1        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20       | 50%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 7.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 2.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2.5%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 2.5%    |
| Intel Ethernet Connection I354 2.5 GbE Backplane                  | 1        | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.5%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.5%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.5%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.5%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.5%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.5%    |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.5%    |
| Intel 82574L Gigabit Network Connection                           | 1        | 2.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 2.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 35       | 83.33%  |
| WiFi     | 7        | 16.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 83.33%  |
| WiFi     | 6        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 64.86%  |
| 2     | 10       | 27.03%  |
| 5     | 1        | 2.7%    |
| 3     | 1        | 2.7%    |
| 0     | 1        | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 36       | 100%    |

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
| Intel                            | 24       | 42.86%  |
| Nvidia                           | 10       | 17.86%  |
| AMD                              | 10       | 17.86%  |
| Plantronics                      | 2        | 3.57%   |
| Creative Labs                    | 2        | 3.57%   |
| Texas Instruments                | 1        | 1.79%   |
| TEAC                             | 1        | 1.79%   |
| Silicon Integrated Systems [SiS] | 1        | 1.79%   |
| M-Audio                          | 1        | 1.79%   |
| Logitech                         | 1        | 1.79%   |
| KORG                             | 1        | 1.79%   |
| Elite Silicon                    | 1        | 1.79%   |
| Cirrus Logic                     | 1        | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 High Definition Audio Controller                              | 4        | 6.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 6.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 4.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 4.62%   |
| Plantronics HD1                                                            | 2        | 3.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 3.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 3.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 3.08%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 3.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 3.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 3.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 3.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 3.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 3.08%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.54%   |
| TEAC US-1800                                                               | 1        | 1.54%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 1.54%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.54%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.54%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.54%   |
| M-Audio MIDISPORT 4x4 Anniv                                                | 1        | 1.54%   |
| M-Audio M-Audio 1x1                                                        | 1        | 1.54%   |
| Logitech H390 headset with microphone                                      | 1        | 1.54%   |
| KORG nanoKONTROL studio controller                                         | 1        | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.54%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.54%   |
| Intel Audio device                                                         | 1        | 1.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.54%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1        | 1.54%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.54%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.54%   |
| Elite Silicon USB Audio Device                                             | 1        | 1.54%   |
| Cirrus Logic Crystal CS4281 PCI Audio                                      | 1        | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.54%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 12       | 30%     |
| Kingston            | 9        | 22.5%   |
| Corsair             | 5        | 12.5%   |
| SK Hynix            | 2        | 5%      |
| Samsung Electronics | 2        | 5%      |
| Nanya Technology    | 2        | 5%      |
| Micron Technology   | 2        | 5%      |
| G.Skill             | 2        | 5%      |
| GOODRAM             | 1        | 2.5%    |
| Crucial             | 1        | 2.5%    |
| Avant               | 1        | 2.5%    |
| A-DATA Technology   | 1        | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 2        | 4.35%   |
| Corsair RAM CMK32GX4M4A2666C16 8192MB DIMM 2667MT/s       | 2        | 4.35%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s | 1        | 2.17%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s               | 1        | 2.17%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                 | 1        | 2.17%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 2.17%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1        | 2.17%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 2.17%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 2.17%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                | 1        | 2.17%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1        | 2.17%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s              | 1        | 2.17%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 2.17%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                | 1        | 2.17%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                | 1        | 2.17%   |
| Unknown RAM Module 1024MB DIMM DDR                        | 1        | 2.17%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 1        | 2.17%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 2.17%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 2.17%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 2.17%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s    | 1        | 2.17%   |
| Nanya RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 2.17%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s        | 1        | 2.17%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 2.17%   |
| Micron RAM DVM64453C DATARAM 8GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 2.17%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s       | 1        | 2.17%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 1        | 2.17%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 1        | 2.17%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 2.17%   |
| Kingston RAM 99U5702-094.A00G 8192MB DIMM DDR4 2400MT/s   | 1        | 2.17%   |
| Kingston RAM 99U5471-066.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 2.17%   |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s     | 1        | 2.17%   |
| Kingston RAM 9905471-084.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 2.17%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s        | 1        | 2.17%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s      | 1        | 2.17%   |
| G.Skill RAM F4-2133C15-16GIS 16384MB DIMM DDR4 2133MT/s   | 1        | 2.17%   |
| Crucial RAM CT51264BA160BJ.C8 4GB DIMM DDR3 1600MT/s      | 1        | 2.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s  | 1        | 2.17%   |
| Corsair RAM CMD8GX3M2B2133C9 4096MB DIMM DDR3 1333MT/s    | 1        | 2.17%   |
| Corsair RAM CM4X16GE2400C16K4 16GB DIMM DDR4 2400MT/s     | 1        | 2.17%   |
| Avant RAM F6451U67F9333G 4096MB DIMM DDR3 1333MT/s        | 1        | 2.17%   |
| A-DATA RAM DDR4 2666 2OZ 4GB DIMM DDR4 2667MT/s           | 1        | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 13       | 40.63%  |
| DDR4    | 12       | 37.5%   |
| SDRAM   | 2        | 6.25%   |
| DDR     | 2        | 6.25%   |
| DRAM    | 1        | 3.13%   |
| DDR2    | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 87.5%   |
| SODIMM | 4        | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 27.03%  |
| 4096  | 10       | 27.03%  |
| 16384 | 6        | 16.22%  |
| 2048  | 5        | 13.51%  |
| 1024  | 2        | 5.41%   |
| 32768 | 1        | 2.7%    |
| 256   | 1        | 2.7%    |
| 128   | 1        | 2.7%    |
| 64    | 1        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 17.14%  |
| 2400    | 5        | 14.29%  |
| 1333    | 5        | 14.29%  |
| 2667    | 4        | 11.43%  |
| 3600    | 3        | 8.57%   |
| 2133    | 2        | 5.71%   |
| 667     | 2        | 5.71%   |
| Unknown | 2        | 5.71%   |
| 3200    | 1        | 2.86%   |
| 1867    | 1        | 2.86%   |
| 1800    | 1        | 2.86%   |
| 800     | 1        | 2.86%   |
| 400     | 1        | 2.86%   |
| 100     | 1        | 2.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 1        | 33.33%  |
| Custom Engineering SPA | 1        | 33.33%  |
| Brother Industries     | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| HP ENVY 5000 series             | 1        | 33.33%  |
| Custom Engineering SPA KUBE USB | 1        | 33.33%  |
| Brother HL-L2375DW series       | 1        | 33.33%  |

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
| Z-Star Microelectronics | 1        | 14.29%  |
| Softkinetic             | 1        | 14.29%  |
| Microdia                | 1        | 14.29%  |
| MacroSilicon            | 1        | 14.29%  |
| Logitech                | 1        | 14.29%  |
| GEMBIRD                 | 1        | 14.29%  |
| Cubeternet              | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera      | 1        | 14.29%  |
| Softkinetic DepthSense 325      | 1        | 14.29%  |
| Microdia Camera                 | 1        | 14.29%  |
| MacroSilicon USB Video          | 1        | 14.29%  |
| Logitech Webcam C270            | 1        | 14.29%  |
| GEMBIRD USB2.0 PC CAMERA        | 1        | 14.29%  |
| Cubeternet GL-UPC822 UVC WebCam | 1        | 14.29%  |

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
| 0     | 32       | 88.89%  |
| 1     | 3        | 8.33%   |
| 2     | 1        | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 3        | 60%     |
| Firewire controller      | 1        | 20%     |
| Communication controller | 1        | 20%     |

