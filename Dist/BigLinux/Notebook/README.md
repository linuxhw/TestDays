BigLinux - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for BigLinux.

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

Total: 44

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E5-411G              | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| ASUSTek       | X455LA                      | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| HP            | EliteBook 8760w             | [30ea6db008](https://linux-hardware.org/?probe=30ea6db008) | Jul 23, 2023 |
| Multilaser    | MLSH1H LINUX                | [e699ffe719](https://linux-hardware.org/?probe=e699ffe719) | Jul 08, 2023 |
| ASUSTek       | VX7SX                       | [2ef4295d22](https://linux-hardware.org/?probe=2ef4295d22) | Jul 05, 2023 |
| Positivo      | Q464B                       | [9dad5f0aa1](https://linux-hardware.org/?probe=9dad5f0aa1) | Jul 02, 2023 |
| Multilaser    | MLSH1H LINUX                | [3aa4a11068](https://linux-hardware.org/?probe=3aa4a11068) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [3a8a822af9](https://linux-hardware.org/?probe=3a8a822af9) | Jun 30, 2023 |
| Apple         | MacBookPro9,2               | [5223ed2efd](https://linux-hardware.org/?probe=5223ed2efd) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | [e25224b362](https://linux-hardware.org/?probe=e25224b362) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [91d11f8da1](https://linux-hardware.org/?probe=91d11f8da1) | Jun 04, 2023 |
| Samsung       | 300E5M/300E5L               | [ebd65238d8](https://linux-hardware.org/?probe=ebd65238d8) | May 22, 2023 |
| Dell          | Inspiron 7460               | [696014fc68](https://linux-hardware.org/?probe=696014fc68) | May 01, 2023 |
| Dell          | G15 5520                    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| Acer          | Nitro AN517-54              | [ebe6cc115e](https://linux-hardware.org/?probe=ebe6cc115e) | Mar 22, 2023 |
| Clevo         | W340EU                      | [fb9df7f581](https://linux-hardware.org/?probe=fb9df7f581) | Mar 18, 2023 |
| Clevo         | W340EU                      | [176b7d75bf](https://linux-hardware.org/?probe=176b7d75bf) | Mar 18, 2023 |
| Avell High... | STORM TWO                   | [e6b20084b5](https://linux-hardware.org/?probe=e6b20084b5) | Mar 16, 2023 |
| Acer          | Aspire A315-53              | [fd498f882b](https://linux-hardware.org/?probe=fd498f882b) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [009adbd75c](https://linux-hardware.org/?probe=009adbd75c) | Jan 18, 2023 |
| HP            | 255 G7 Notebook PC          | [b1a7adefab](https://linux-hardware.org/?probe=b1a7adefab) | Jan 09, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| Toshiba       | Satellite S55-A             | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| Toshiba       | Satellite S55-A             | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Dell          | System XPS L502X            | [cd40a3f168](https://linux-hardware.org/?probe=cd40a3f168) | Oct 08, 2022 |
| ASUSTek       | X45U                        | [3efe835653](https://linux-hardware.org/?probe=3efe835653) | Aug 22, 2022 |
| Positivo      | C14RV01                     | [818c67da93](https://linux-hardware.org/?probe=818c67da93) | Aug 21, 2022 |
| Sony          | VGN-NR230AE                 | [ba78970975](https://linux-hardware.org/?probe=ba78970975) | Aug 15, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [2f8b49e4f8](https://linux-hardware.org/?probe=2f8b49e4f8) | Jul 23, 2022 |
| Positivo      | C14RV01                     | [fc6fa07b38](https://linux-hardware.org/?probe=fc6fa07b38) | Sep 10, 2021 |
| Acer          | Predator G9-793             | [6004b8b462](https://linux-hardware.org/?probe=6004b8b462) | Jun 24, 2021 |
| Dell          | System Inspiron N7110       | [e58da0d3ca](https://linux-hardware.org/?probe=e58da0d3ca) | Jun 23, 2021 |
| Acer          | Predator G9-793             | [ae4824f52e](https://linux-hardware.org/?probe=ae4824f52e) | Jun 20, 2021 |
| Dell          | System Inspiron N7110       | [41512cfc6a](https://linux-hardware.org/?probe=41512cfc6a) | Jun 20, 2021 |
| Positivo      | C14RV01                     | [36efae3128](https://linux-hardware.org/?probe=36efae3128) | Feb 03, 2021 |
| Acer          | A315-41                     | [021dc9110e](https://linux-hardware.org/?probe=021dc9110e) | Nov 11, 2020 |
| Lenovo        | ThinkPad T410 25379N2       | [ed777f25b7](https://linux-hardware.org/?probe=ed777f25b7) | Nov 09, 2020 |
| Dell          | Inspiron 3480               | [1f0823c074](https://linux-hardware.org/?probe=1f0823c074) | Oct 13, 2020 |
| Acer          | Aspire A515-51G             | [8b89f99351](https://linux-hardware.org/?probe=8b89f99351) | Jul 17, 2020 |
| Acer          | Aspire A515-51G             | [07fb6950a2](https://linux-hardware.org/?probe=07fb6950a2) | Jul 11, 2020 |
| Lenovo        | IdeaPad Z470                | [3a8f141df4](https://linux-hardware.org/?probe=3a8f141df4) | Mar 28, 2020 |
| Alienware     | 17                          | [14abe97f88](https://linux-hardware.org/?probe=14abe97f88) | Oct 23, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| BigLinux 20.04            | 6         | 17.65%  |
| BigLinux 23.0.0           | 3         | 8.82%   |
| BigLinux 22.0.0           | 3         | 8.82%   |
| BigLinux 19.04            | 3         | 8.82%   |
| BigLinux 22.1.0           | 2         | 5.88%   |
| BigLinux 21.3.7           | 2         | 5.88%   |
| BigLinux 23.01.06         | 1         | 2.94%   |
| BigLinux 22.11.19         | 1         | 2.94%   |
| BigLinux 22.11.14         | 1         | 2.94%   |
| BigLinux 22.10.06         | 1         | 2.94%   |
| BigLinux 22.0.5           | 1         | 2.94%   |
| BigLinux 22.0.4           | 1         | 2.94%   |
| BigLinux 21.3.6           | 1         | 2.94%   |
| BigLinux 21.3.5           | 1         | 2.94%   |
| BigLinux 21.1.2           | 1         | 2.94%   |
| BigLinux 2023-08-04_06-17 | 1         | 2.94%   |
| BigLinux 2023-06-30_08-01 | 1         | 2.94%   |
| BigLinux 2023-06-23_06-21 | 1         | 2.94%   |
| BigLinux 2023-06-03_00-55 | 1         | 2.94%   |
| BigLinux 2023-04-11_15-10 | 1         | 2.94%   |
| BigLinux 2023-03-17_19-23 | 1         | 2.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| BigLinux | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 6.1.31-2-MANJARO   | 2         | 5.88%   |
| 6.1.23-1-MANJARO   | 2         | 5.88%   |
| 6.0.8-1-MANJARO    | 2         | 5.88%   |
| 5.8.0-43-generic   | 2         | 5.88%   |
| 5.2.8-xanmod8      | 2         | 5.88%   |
| 5.15.85-1-MANJARO  | 2         | 5.88%   |
| 5.15.102-1-MANJARO | 2         | 5.88%   |
| 6.4.6-1-MANJARO    | 1         | 2.94%   |
| 6.3.5-2-MANJARO    | 1         | 2.94%   |
| 6.3.5-1-MANJARO    | 1         | 2.94%   |
| 6.3.13-1-MANJARO   | 1         | 2.94%   |
| 6.2.12-1-MANJARO   | 1         | 2.94%   |
| 6.1.1-1-MANJARO    | 1         | 2.94%   |
| 5.9.3-xanmod1      | 1         | 2.94%   |
| 5.8.0-28-generic   | 1         | 2.94%   |
| 5.4.0-48-generic   | 1         | 2.94%   |
| 5.3.6-xanmod5      | 1         | 2.94%   |
| 5.19.13-1-MANJARO  | 1         | 2.94%   |
| 5.15.94-1-MANJARO  | 1         | 2.94%   |
| 5.15.78-1-MANJARO  | 1         | 2.94%   |
| 5.15.60-1-MANJARO  | 1         | 2.94%   |
| 5.15.114-2-MANJARO | 1         | 2.94%   |
| 5.10.61-1-MANJARO  | 1         | 2.94%   |
| 5.10.136-1-MANJARO | 1         | 2.94%   |
| 5.10.131-1-MANJARO | 1         | 2.94%   |
| 5.10.129-1-MANJARO | 1         | 2.94%   |
| 5.10.12-xanmod1    | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.8.0    | 3         | 8.82%   |
| 6.3.5    | 2         | 5.88%   |
| 6.1.31   | 2         | 5.88%   |
| 6.1.23   | 2         | 5.88%   |
| 6.0.8    | 2         | 5.88%   |
| 5.2.8    | 2         | 5.88%   |
| 5.15.85  | 2         | 5.88%   |
| 5.15.102 | 2         | 5.88%   |
| 6.4.6    | 1         | 2.94%   |
| 6.3.13   | 1         | 2.94%   |
| 6.2.12   | 1         | 2.94%   |
| 6.1.1    | 1         | 2.94%   |
| 5.9.3    | 1         | 2.94%   |
| 5.4.0    | 1         | 2.94%   |
| 5.3.6    | 1         | 2.94%   |
| 5.19.13  | 1         | 2.94%   |
| 5.15.94  | 1         | 2.94%   |
| 5.15.78  | 1         | 2.94%   |
| 5.15.60  | 1         | 2.94%   |
| 5.15.114 | 1         | 2.94%   |
| 5.10.61  | 1         | 2.94%   |
| 5.10.136 | 1         | 2.94%   |
| 5.10.131 | 1         | 2.94%   |
| 5.10.129 | 1         | 2.94%   |
| 5.10.12  | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 8         | 25%     |
| 6.1     | 5         | 15.63%  |
| 6.3     | 3         | 9.38%   |
| 5.8     | 3         | 9.38%   |
| 5.10    | 3         | 9.38%   |
| 6.0     | 2         | 6.25%   |
| 5.2     | 2         | 6.25%   |
| 6.4     | 1         | 3.13%   |
| 6.2     | 1         | 3.13%   |
| 5.9     | 1         | 3.13%   |
| 5.4     | 1         | 3.13%   |
| 5.3     | 1         | 3.13%   |
| 5.19    | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 28        | 87.5%   |
| KDE      | 2         | 6.25%   |
| Cinnamon | 1         | 3.13%   |
| Unknown  | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 31        | 96.88%  |
| Wayland | 1         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 27        | 84.38%  |
| Unknown | 3         | 9.38%   |
| LightDM | 2         | 6.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_BR   | 24        | 75%     |
| es_MX   | 2         | 6.25%   |
| en_US   | 2         | 6.25%   |
| fi_FI   | 1         | 3.13%   |
| es_CR   | 1         | 3.13%   |
| el_GR   | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 21        | 63.64%  |
| BIOS | 12        | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 25        | 78.13%  |
| Ext4    | 4         | 12.5%   |
| Overlay | 2         | 6.25%   |
| Unknown | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 21        | 63.64%  |
| MBR     | 9         | 27.27%  |
| Unknown | 3         | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 87.88%  |
| Yes       | 4         | 12.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 59.38%  |
| Yes       | 13        | 40.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 6         | 18.75%  |
| Dell                   | 5         | 15.63%  |
| Acer                   | 5         | 15.63%  |
| ASUSTek Computer       | 4         | 12.5%   |
| Positivo               | 2         | 6.25%   |
| Hewlett-Packard        | 2         | 6.25%   |
| Toshiba                | 1         | 3.13%   |
| Sony                   | 1         | 3.13%   |
| Samsung Electronics    | 1         | 3.13%   |
| Multilaser             | 1         | 3.13%   |
| Clevo                  | 1         | 3.13%   |
| Avell High Performance | 1         | 3.13%   |
| Apple                  | 1         | 3.13%   |
| Alienware              | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba Satellite S55-A                | 1         | 3.13%   |
| Sony VGN-NR230AE                       | 1         | 3.13%   |
| Samsung 300E5M/300E5L                  | 1         | 3.13%   |
| Positivo Q464B                         | 1         | 3.13%   |
| Positivo C14RV01                       | 1         | 3.13%   |
| Multilaser MLSH1H LINUX                | 1         | 3.13%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 1         | 3.13%   |
| Lenovo ThinkPad T410 25379N2           | 1         | 3.13%   |
| Lenovo IdeaPad Z470                    | 1         | 3.13%   |
| Lenovo IdeaPad S400 VIUS3              | 1         | 3.13%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 1         | 3.13%   |
| Lenovo IdeaPad 300-15ISK 80RS          | 1         | 3.13%   |
| HP EliteBook 8760w                     | 1         | 3.13%   |
| HP 255 G7 Notebook PC                  | 1         | 3.13%   |
| Dell System XPS L502X                  | 1         | 3.13%   |
| Dell System Inspiron N7110             | 1         | 3.13%   |
| Dell Inspiron 7460                     | 1         | 3.13%   |
| Dell Inspiron 3480                     | 1         | 3.13%   |
| Dell G15 5520                          | 1         | 3.13%   |
| Clevo W340EU                           | 1         | 3.13%   |
| Avell High Performance STORM TWO       | 1         | 3.13%   |
| ASUS X45U                              | 1         | 3.13%   |
| ASUS X455LA                            | 1         | 3.13%   |
| ASUS VX7SX                             | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X515JA_X515JA | 1         | 3.13%   |
| Apple MacBookPro9,2                    | 1         | 3.13%   |
| Alienware 17                           | 1         | 3.13%   |
| Acer Predator G9-793                   | 1         | 3.13%   |
| Acer Nitro AN517-54                    | 1         | 3.13%   |
| Acer Aspire A515-51G                   | 1         | 3.13%   |
| Acer Aspire A315-53                    | 1         | 3.13%   |
| Acer A315-41                           | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 4         | 12.5%   |
| Dell System                  | 2         | 6.25%   |
| Dell Inspiron                | 2         | 6.25%   |
| Acer Aspire                  | 2         | 6.25%   |
| Toshiba Satellite            | 1         | 3.13%   |
| Sony VGN-NR230AE             | 1         | 3.13%   |
| Samsung 300E5M               | 1         | 3.13%   |
| Positivo Q464B               | 1         | 3.13%   |
| Positivo C14RV01             | 1         | 3.13%   |
| Multilaser MLSH1H            | 1         | 3.13%   |
| Lenovo Yoga                  | 1         | 3.13%   |
| Lenovo ThinkPad              | 1         | 3.13%   |
| HP EliteBook                 | 1         | 3.13%   |
| HP 255                       | 1         | 3.13%   |
| Dell G15                     | 1         | 3.13%   |
| Clevo W340EU                 | 1         | 3.13%   |
| Avell High Performance STORM | 1         | 3.13%   |
| ASUS X45U                    | 1         | 3.13%   |
| ASUS X455LA                  | 1         | 3.13%   |
| ASUS VX7SX                   | 1         | 3.13%   |
| ASUS VivoBook                | 1         | 3.13%   |
| Apple MacBookPro9            | 1         | 3.13%   |
| Alienware 17                 | 1         | 3.13%   |
| Acer Predator                | 1         | 3.13%   |
| Acer Nitro                   | 1         | 3.13%   |
| Acer A315-41                 | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 5         | 15.63%  |
| 2021 | 4         | 12.5%   |
| 2011 | 4         | 12.5%   |
| 2019 | 3         | 9.38%   |
| 2017 | 3         | 9.38%   |
| 2013 | 3         | 9.38%   |
| 2022 | 2         | 6.25%   |
| 2018 | 2         | 6.25%   |
| 2016 | 2         | 6.25%   |
| 2020 | 1         | 3.13%   |
| 2014 | 1         | 3.13%   |
| 2009 | 1         | 3.13%   |
| 2007 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 32        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 32        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 9         | 27.27%  |
| 3.01-4.0    | 8         | 24.24%  |
| 16.01-24.0  | 6         | 18.18%  |
| 8.01-16.0   | 4         | 12.12%  |
| 32.01-64.0  | 2         | 6.06%   |
| 1.01-2.0    | 2         | 6.06%   |
| 2.01-3.0    | 1         | 3.03%   |
| 64.01-256.0 | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 13        | 39.39%  |
| 2.01-3.0  | 9         | 27.27%  |
| 4.01-8.0  | 5         | 15.15%  |
| 3.01-4.0  | 3         | 9.09%   |
| 0.51-1.0  | 2         | 6.06%   |
| 8.01-16.0 | 1         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 71.88%  |
| 3      | 4         | 12.5%   |
| 2      | 4         | 12.5%   |
| 4      | 1         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 59.38%  |
| Yes       | 13        | 40.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 90.63%  |
| No        | 3         | 9.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 96.88%  |
| No        | 1         | 3.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 71.88%  |
| No        | 9         | 28.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Brazil     | 24        | 75%     |
| Mexico     | 2         | 6.25%   |
| Greece     | 2         | 6.25%   |
| USA        | 1         | 3.13%   |
| UK         | 1         | 3.13%   |
| Finland    | 1         | 3.13%   |
| Costa Rica | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Brasília             | 3         | 9.09%   |
| Sao Paulo             | 2         | 6.06%   |
| Curitiba              | 2         | 6.06%   |
| Castanhal             | 2         | 6.06%   |
| Belo Horizonte        | 2         | 6.06%   |
| Thessaloniki          | 1         | 3.03%   |
| Sao Jose do Rio Preto | 1         | 3.03%   |
| Sao Domingos do Capim | 1         | 3.03%   |
| San José             | 1         | 3.03%   |
| Salvador              | 1         | 3.03%   |
| Rio de Janeiro        | 1         | 3.03%   |
| Mirassol              | 1         | 3.03%   |
| Metepec               | 1         | 3.03%   |
| Marataizes            | 1         | 3.03%   |
| Maidstone             | 1         | 3.03%   |
| Londrina              | 1         | 3.03%   |
| Joensuu               | 1         | 3.03%   |
| Hoffman               | 1         | 3.03%   |
| Fernandopolis         | 1         | 3.03%   |
| Domingos Martins      | 1         | 3.03%   |
| Cruz Alta             | 1         | 3.03%   |
| Colombo               | 1         | 3.03%   |
| Caruaru               | 1         | 3.03%   |
| Campeche              | 1         | 3.03%   |
| Belém                | 1         | 3.03%   |
| Ampere                | 1         | 3.03%   |
| Alimos                | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 9         | 11     | 20%     |
| Seagate                   | 5         | 5      | 11.11%  |
| Samsung Electronics       | 4         | 4      | 8.89%   |
| Crucial                   | 4         | 4      | 8.89%   |
| ADATA Technology          | 3         | 3      | 6.67%   |
| Unknown                   | 2         | 2      | 4.44%   |
| LITEON                    | 2         | 3      | 4.44%   |
| KingSpec                  | 2         | 2      | 4.44%   |
| Hitachi                   | 2         | 2      | 4.44%   |
| HGST                      | 2         | 2      | 4.44%   |
| China                     | 2         | 2      | 4.44%   |
| A-DATA Technology         | 2         | 2      | 4.44%   |
| Toshiba                   | 1         | 2      | 2.22%   |
| PNY                       | 1         | 2      | 2.22%   |
| Netac                     | 1         | 2      | 2.22%   |
| Micron/Crucial Technology | 1         | 1      | 2.22%   |
| JMicron Technology        | 1         | 1      | 2.22%   |
| EYOTA                     | 1         | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB                            | 3         | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 6.67%   |
| Unknown MMC Card  64GB                              | 2         | 4.44%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 1         | 2.22%   |
| WDC WD7500BPKX-75HPJT0 752GB                        | 1         | 2.22%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 2.22%   |
| WDC WD5000LPVT-08G33T1 500GB                        | 1         | 2.22%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 2.22%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 1         | 2.22%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 2.22%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 2.22%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 1         | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2.22%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 1         | 2.22%   |
| Seagate Expansion HDD 16TB                          | 1         | 2.22%   |
| Samsung HM501II 500GB                               | 1         | 2.22%   |
| PNY CS900 500GB SSD                                 | 1         | 2.22%   |
| Netac NVMe SSD 2TB                                  | 1         | 2.22%   |
| Micron/Crucial CT500P5SSD8 500GB                    | 1         | 2.22%   |
| LITEON CV3-8D128-11 SATA 128GB SSD                  | 1         | 2.22%   |
| LITEON CV1-8B128 128GB SSD                          | 1         | 2.22%   |
| KingSpec P4-120 120GB                               | 1         | 2.22%   |
| KingSpec P3-512 512GB                               | 1         | 2.22%   |
| JMicron Tech 250GB                                  | 1         | 2.22%   |
| Hitachi HTS727575A9E364 752GB                       | 1         | 2.22%   |
| Hitachi HTS545032A7E380 320GB                       | 1         | 2.22%   |
| HGST HTS721010A9E630 1TB                            | 1         | 2.22%   |
| HGST HTS541075A9E680 752GB                          | 1         | 2.22%   |
| EYOTA 512GB                                         | 1         | 2.22%   |
| Crucial CT500MX500SSD1 500GB                        | 1         | 2.22%   |
| Crucial CT500MX200SSD3 500GB                        | 1         | 2.22%   |
| Crucial CT480BX500SSD1 480GB                        | 1         | 2.22%   |
| Crucial CT275MX300SSD1 275GB                        | 1         | 2.22%   |
| China SSD 120GB                                     | 1         | 2.22%   |
| China SATA SSD 240GB                                | 1         | 2.22%   |
| ADATA SM2P41C3 NVMe 512GB                           | 1         | 2.22%   |
| ADATA SM2P32A8-512GC1 512GB                         | 1         | 2.22%   |
| ADATA IM2P33F8ABR2-512GB                            | 1         | 2.22%   |
| A-DATA SU800 1TB SSD                                | 1         | 2.22%   |
| A-DATA SU630 480GB SSD                              | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 10     | 42.11%  |
| Seagate             | 5         | 5      | 26.32%  |
| Hitachi             | 2         | 2      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Toshiba             | 1         | 2      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Crucial           | 4         | 4      | 28.57%  |
| LITEON            | 2         | 3      | 14.29%  |
| KingSpec          | 2         | 2      | 14.29%  |
| China             | 2         | 2      | 14.29%  |
| A-DATA Technology | 2         | 2      | 14.29%  |
| WDC               | 1         | 1      | 7.14%   |
| PNY               | 1         | 2      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 22     | 45.24%  |
| SSD     | 11        | 16     | 26.19%  |
| NVMe    | 8         | 9      | 19.05%  |
| MMC     | 2         | 2      | 4.76%   |
| Unknown | 2         | 2      | 4.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 38     | 69.23%  |
| NVMe | 8         | 9      | 20.51%  |
| SAS  | 2         | 2      | 5.13%   |
| MMC  | 2         | 2      | 5.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 21     | 50%     |
| 0.51-1.0   | 13        | 15     | 43.33%  |
| 10.01-20.0 | 1         | 1      | 3.33%   |
| 1.01-2.0   | 1         | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 8         | 25%     |
| 2001-3000      | 8         | 25%     |
| 101-250        | 5         | 15.63%  |
| 1001-2000      | 5         | 15.63%  |
| More than 3000 | 3         | 9.38%   |
| 501-1000       | 2         | 6.25%   |
| 1-20           | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 51-100         | 12        | 35.29%  |
| 21-50          | 9         | 26.47%  |
| 101-250        | 7         | 20.59%  |
| 1-20           | 2         | 5.88%   |
| More than 3000 | 1         | 2.94%   |
| 251-500        | 1         | 2.94%   |
| 2001-3000      | 1         | 2.94%   |
| 1001-2000      | 1         | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                  | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-00JJ5T0 320GB           | 1         | 3      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 1      | 14.29%  |
| Hitachi HTS727575A9E364 752GB          | 1         | 1      | 14.29%  |
| Hitachi HTS545032A7E380 320GB          | 1         | 1      | 14.29%  |
| Crucial CT500MX200SSD3 500GB           | 1         | 1      | 14.29%  |
| China SATA SSD 240GB                   | 1         | 1      | 14.29%  |
| ADATA Technology SM2P32A8-512GC1 512GB | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor           | Notebooks | Drives | Percent |
|------------------|-----------|--------|---------|
| Hitachi          | 2         | 2      | 28.57%  |
| WDC              | 1         | 3      | 14.29%  |
| Seagate          | 1         | 1      | 14.29%  |
| Crucial          | 1         | 1      | 14.29%  |
| China            | 1         | 1      | 14.29%  |
| ADATA Technology | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 50%     |
| WDC     | 1         | 3      | 25%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 6      | 57.14%  |
| SSD  | 2         | 2      | 28.57%  |
| NVMe | 1         | 1      | 14.29%  |

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
| Works    | 18        | 25     | 47.37%  |
| Detected | 13        | 17     | 34.21%  |
| Malfunc  | 7         | 9      | 18.42%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 23        | 67.65%  |
| AMD                       | 4         | 11.76%  |
| ADATA Technology          | 3         | 8.82%   |
| Samsung Electronics       | 2         | 5.88%   |
| Netac Technology          | 1         | 2.94%   |
| Micron/Crucial Technology | 1         | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 13.89%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 13.89%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 11.11%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 5.56%   |
| ADATA A Non-Volatile memory controller                                         | 2         | 5.56%   |
| Netac Non-Volatile memory controller                                           | 1         | 2.78%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 1         | 2.78%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 2.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.78%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                    | 1         | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 24        | 68.57%  |
| NVMe | 7         | 20%     |
| RAID | 3         | 8.57%   |
| IDE  | 1         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 81.25%  |
| AMD    | 6         | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 6.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 6.25%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 3.13%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 3.13%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 3.13%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 3.13%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 3.13%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 3.13%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 3.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.13%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 3.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 3.13%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 3.13%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 3.13%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 3.13%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 3.13%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 3.13%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 3.13%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 3.13%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 3.13%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 3.13%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 3.13%   |
| Intel 12th Gen Core i5-12500H                 | 1         | 3.13%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 1         | 3.13%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 1         | 3.13%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 3.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD C-70 APU with Radeon HD Graphics          | 1         | 3.13%   |
| AMD C-60 APU with Radeon HD Graphics          | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 9         | 28.13%  |
| Intel Core i7      | 8         | 25%     |
| Intel Core i3      | 4         | 12.5%   |
| Other              | 3         | 9.38%   |
| AMD Ryzen 5        | 3         | 9.38%   |
| Intel Pentium Dual | 1         | 3.13%   |
| Intel Atom         | 1         | 3.13%   |
| AMD Ryzen 7        | 1         | 3.13%   |
| AMD C-70           | 1         | 3.13%   |
| AMD C-60           | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 53.13%  |
| 4      | 10        | 31.25%  |
| 6      | 2         | 6.25%   |
| 14     | 1         | 3.13%   |
| 12     | 1         | 3.13%   |
| 8      | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 84.38%  |
| 1      | 5         | 15.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 96.88%  |
| Unknown        | 1         | 3.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 18.75%  |
| 0x806e9    | 4         | 12.5%   |
| 0x206a7    | 4         | 12.5%   |
| 0x906a3    | 2         | 6.25%   |
| 0x306a9    | 2         | 6.25%   |
| 0x05000119 | 2         | 6.25%   |
| 0x806ec    | 1         | 3.13%   |
| 0x806d1    | 1         | 3.13%   |
| 0x706e5    | 1         | 3.13%   |
| 0x6fd      | 1         | 3.13%   |
| 0x506e3    | 1         | 3.13%   |
| 0x406e3    | 1         | 3.13%   |
| 0x406c4    | 1         | 3.13%   |
| 0x306c3    | 1         | 3.13%   |
| 0x20652    | 1         | 3.13%   |
| 0x0a50000d | 1         | 3.13%   |
| 0x08108109 | 1         | 3.13%   |
| 0x0810100b | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 6         | 18.75%  |
| KabyLake         | 6         | 18.75%  |
| IvyBridge        | 3         | 9.38%   |
| Skylake          | 2         | 6.25%   |
| Haswell          | 2         | 6.25%   |
| Bobcat           | 2         | 6.25%   |
| Alderlake Hybrid | 2         | 6.25%   |
| Zen+             | 1         | 3.13%   |
| Zen 3            | 1         | 3.13%   |
| Zen 2            | 1         | 3.13%   |
| Zen              | 1         | 3.13%   |
| Westmere         | 1         | 3.13%   |
| Silvermont       | 1         | 3.13%   |
| IceLake          | 1         | 3.13%   |
| Core             | 1         | 3.13%   |
| Unknown          | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 56.1%   |
| Nvidia | 10        | 24.39%  |
| AMD    | 8         | 19.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 5         | 11.9%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 9.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 7.14%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 4.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 4.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.38%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 2.38%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 2.38%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 2.38%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 2.38%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 2.38%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                                 | 1         | 2.38%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                            | 1         | 2.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.38%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.38%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.38%   |
| AMD Wrestler [Radeon HD 7290]                                                            | 1         | 2.38%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 2.38%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 2.38%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.38%   |
| AMD Renoir                                                                               | 1         | 2.38%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 40.63%  |
| Intel + Nvidia | 8         | 25%     |
| 1 x AMD        | 7         | 21.88%  |
| 1 x Nvidia     | 2         | 6.25%   |
| 2 x Intel      | 1         | 3.13%   |
| Intel + AMD    | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 26        | 81.25%  |
| Proprietary | 6         | 18.75%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 65.63%  |
| 1.01-2.0   | 4         | 12.5%   |
| 0.51-1.0   | 2         | 6.25%   |
| 0.01-0.5   | 2         | 6.25%   |
| 7.01-8.0   | 1         | 3.13%   |
| 3.01-4.0   | 1         | 3.13%   |
| 2.01-3.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 7         | 18.42%  |
| LG Display              | 6         | 15.79%  |
| BOE                     | 6         | 15.79%  |
| AU Optronics            | 6         | 15.79%  |
| Goldstar                | 3         | 7.89%   |
| Samsung Electronics     | 2         | 5.26%   |
| Panasonic               | 2         | 5.26%   |
| Chi Mei Optoelectronics | 2         | 5.26%   |
| Lenovo                  | 1         | 2.63%   |
| Hewlett-Packard         | 1         | 2.63%   |
| CSO                     | 1         | 2.63%   |
| Apple                   | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Panasonic TV MEIC10C 1920x540 697x392mm 31.5-inch                        | 2         | 5.26%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch        | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 2.63%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch             | 1         | 2.63%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 1         | 2.63%   |
| Hewlett-Packard 23tm HWP3110 1920x1080 509x286mm 23.0-inch               | 1         | 2.63%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 1         | 2.63%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 2.63%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                   | 1         | 2.63%   |
| CSO LCD Monitor CSO140C 2880x1800 302x188mm 14.0-inch                    | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14C8 1920x1080 309x173mm 13.9-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1724 1600x900 382x215mm 17.3-inch | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1465 1366x768 309x174mm 14.0-inch | 1         | 2.63%   |
| BOE LCD Monitor BOE0A8F 2560x1440 381x214mm 17.2-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE09B4 1920x1080 382x215mm 17.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE0025 1366x768 309x173mm 13.9-inch                     | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOED8F 1920x1080 344x193mm 15.5-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO15ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.63%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 15        | 39.47%  |
| 1920x1080 (FHD) | 12        | 31.58%  |
| 2560x1080       | 3         | 7.89%   |
| 1920x540        | 2         | 5.26%   |
| 1600x900 (HD+)  | 2         | 5.26%   |
| 1280x800 (WXGA) | 2         | 5.26%   |
| 2880x1800       | 1         | 2.63%   |
| 2560x1440 (QHD) | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 11        | 28.95%  |
| 14     | 9         | 23.68%  |
| 17     | 6         | 15.79%  |
| 13     | 5         | 13.16%  |
| 34     | 2         | 5.26%   |
| 31     | 2         | 5.26%   |
| 28     | 1         | 2.63%   |
| 23     | 1         | 2.63%   |
| 21     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 63.16%  |
| 351-400     | 6         | 15.79%  |
| 601-700     | 3         | 7.89%   |
| 701-800     | 2         | 5.26%   |
| 501-600     | 1         | 2.63%   |
| 401-500     | 1         | 2.63%   |
| 201-300     | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 82.35%  |
| 21/9  | 3         | 8.82%   |
| 16/10 | 3         | 8.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 14        | 36.84%  |
| 101-110        | 11        | 28.95%  |
| 121-130        | 6         | 15.79%  |
| 351-500        | 4         | 10.53%  |
| 201-250        | 2         | 5.26%   |
| 251-300        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 18        | 48.65%  |
| 121-160       | 10        | 27.03%  |
| 51-100        | 7         | 18.92%  |
| More than 240 | 1         | 2.7%    |
| 161-240       | 1         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 75.76%  |
| 2     | 8         | 24.24%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 38.18%  |
| Qualcomm Atheros         | 15        | 27.27%  |
| Intel                    | 10        | 18.18%  |
| Broadcom                 | 2         | 3.64%   |
| Ralink Technology        | 1         | 1.82%   |
| Ralink                   | 1         | 1.82%   |
| Marvell Technology Group | 1         | 1.82%   |
| JMicron Technology       | 1         | 1.82%   |
| Edimax Technology        | 1         | 1.82%   |
| Belkin Components        | 1         | 1.82%   |
| ASIX Electronics         | 1         | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                      | 12        | 18.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                  | 5         | 7.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                             | 5         | 7.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                             | 3         | 4.62%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 2         | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                         | 2         | 3.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                       | 2         | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                               | 1         | 1.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                    | 1         | 1.54%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                        | 1         | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                               | 1         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                                      | 1         | 1.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                       | 1         | 1.54%   |
| Realtek 802.11n WLAN Adapter                                                           | 1         | 1.54%   |
| Realtek 802.11ac NIC                                                                   | 1         | 1.54%   |
| Ralink MT7601U Wireless Adapter                                                        | 1         | 1.54%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                              | 1         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                             | 1         | 1.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                              | 1         | 1.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                              | 1         | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                              | 1         | 1.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                               | 1         | 1.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                | 1         | 1.54%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                                   | 1         | 1.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                                 | 1         | 1.54%   |
| Intel Wi-Fi 6 AX200                                                                    | 1         | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                                         | 1         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                        | 1         | 1.54%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                          | 1         | 1.54%   |
| Intel Centrino Ultimate-N 6300                                                         | 1         | 1.54%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                          | 1         | 1.54%   |
| Intel Centrino Advanced-N 6200                                                         | 1         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                               | 1         | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                  | 1         | 1.54%   |
| Intel 82577LM Gigabit Network Connection                                               | 1         | 1.54%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                            | 1         | 1.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                      | 1         | 1.54%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                     | 1         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                                         | 1         | 1.54%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v1000 [Ralink RT3070] | 1         | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 12        | 35.29%  |
| Intel                 | 10        | 29.41%  |
| Realtek Semiconductor | 6         | 17.65%  |
| Broadcom              | 2         | 5.88%   |
| Ralink Technology     | 1         | 2.94%   |
| Ralink                | 1         | 2.94%   |
| Edimax Technology     | 1         | 2.94%   |
| Belkin Components     | 1         | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                             | 5         | 14.29%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                             | 3         | 8.57%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 2         | 5.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                         | 2         | 5.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                       | 2         | 5.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                               | 1         | 2.86%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                    | 1         | 2.86%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                        | 1         | 2.86%   |
| Realtek 802.11n WLAN Adapter                                                           | 1         | 2.86%   |
| Realtek 802.11ac NIC                                                                   | 1         | 2.86%   |
| Ralink MT7601U Wireless Adapter                                                        | 1         | 2.86%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                              | 1         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                             | 1         | 2.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                | 1         | 2.86%   |
| Intel Wi-Fi 6 AX200                                                                    | 1         | 2.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                                         | 1         | 2.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                        | 1         | 2.86%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                          | 1         | 2.86%   |
| Intel Centrino Ultimate-N 6300                                                         | 1         | 2.86%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                          | 1         | 2.86%   |
| Intel Centrino Advanced-N 6200                                                         | 1         | 2.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                               | 1         | 2.86%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                            | 1         | 2.86%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                     | 1         | 2.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                                         | 1         | 2.86%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v1000 [Ralink RT3070] | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 19        | 65.52%  |
| Qualcomm Atheros         | 4         | 13.79%  |
| Intel                    | 2         | 6.9%    |
| Marvell Technology Group | 1         | 3.45%   |
| JMicron Technology       | 1         | 3.45%   |
| Broadcom                 | 1         | 3.45%   |
| ASIX Electronics         | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 16.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 3.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 3.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 3.33%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 3.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 3.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 51.67%  |
| Ethernet | 29        | 48.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 74.19%  |
| Ethernet | 8         | 25.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 26        | 81.25%  |
| 1     | 5         | 15.63%  |
| 0     | 1         | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 62.5%   |
| Yes  | 12        | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 34.78%  |
| Qualcomm Atheros Communications | 5         | 21.74%  |
| Lite-On Technology              | 4         | 17.39%  |
| Realtek Semiconductor           | 1         | 4.35%   |
| IMC Networks                    | 1         | 4.35%   |
| Hewlett-Packard                 | 1         | 4.35%   |
| Foxconn / Hon Hai               | 1         | 4.35%   |
| Broadcom                        | 1         | 4.35%   |
| Apple                           | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device               | 3         | 13.04%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 3         | 13.04%  |
| Intel AX201 Bluetooth                            | 3         | 13.04%  |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 2         | 8.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 2         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 2         | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 4.35%   |
| Lite-On Bluetooth Device                         | 1         | 4.35%   |
| Intel AX200 Bluetooth                            | 1         | 4.35%   |
| IMC Networks BCM20702A0                          | 1         | 4.35%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 4.35%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device  | 1         | 4.35%   |
| Broadcom BCM2045B (BDC-2.1)                      | 1         | 4.35%   |
| Apple Bluetooth USB Host Controller              | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 25        | 62.5%   |
| Nvidia                 | 7         | 17.5%   |
| AMD                    | 7         | 17.5%   |
| Generalplus Technology | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 12.5%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 10.42%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 8.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 4.17%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 4.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 4.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.08%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 2.08%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 2.08%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 2.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.08%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 2.08%   |
| Nvidia Audio device                                                        | 1         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.08%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.08%   |
| Generalplus Technology USB Audio Device                                    | 1         | 2.08%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.08%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 26.67%  |
| Smart               | 4         | 13.33%  |
| Micron Technology   | 4         | 13.33%  |
| Unknown             | 3         | 10%     |
| SK hynix            | 3         | 10%     |
| A-DATA Technology   | 2         | 6.67%   |
| Teikon              | 1         | 3.33%   |
| Kingston            | 1         | 3.33%   |
| Kembona             | 1         | 3.33%   |
| G.Skill             | 1         | 3.33%   |
| Crucial             | 1         | 3.33%   |
| Unknown             | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 2         | 5.71%   |
| Unknown RAM Module 512MB SODIMM DDR2                     | 1         | 2.86%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s              | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s              | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR2                       | 1         | 2.86%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s   | 1         | 2.86%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s    | 1         | 2.86%   |
| Smart RAM SH564568FH8NZPHSCR 2048MB SODIMM DDR3 1333MT/s | 1         | 2.86%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s    | 1         | 2.86%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s    | 1         | 2.86%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s    | 1         | 2.86%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s             | 1         | 2.86%   |
| SK hynix RAM MMXIV 4096MB SODIMM DDR3 1333MT/s           | 1         | 2.86%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s    | 1         | 2.86%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1600MT/s      | 1         | 2.86%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s    | 1         | 2.86%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 1         | 2.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 2.86%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s    | 1         | 2.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s    | 1         | 2.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s    | 1         | 2.86%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 2.86%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4266MT/s       | 1         | 2.86%   |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 2.86%   |
| Micron RAM 16ATF2G64HZ-2G1B1 16GB SODIMM DDR4 2133MT/s   | 1         | 2.86%   |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s    | 1         | 2.86%   |
| Kembona RAM KBN1333D3N9/8G 8GB SODIMM DDR3 1333MT/s      | 1         | 2.86%   |
| Kembona RAM KBN13333D3S9/8G 8GB SODIMM DDR3 1333MT/s     | 1         | 2.86%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s     | 1         | 2.86%   |
| Crucial RAM CT25664BF160B.C8FE 2GB SODIMM DDR3 1600MT/s  | 1         | 2.86%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s              | 1         | 2.86%   |
| A-DATA RAM AD5S480032G-B 32GB SODIMM DDR5 4800MT/s       | 1         | 2.86%   |
| A-DATA RAM AD4S320038G22-BHYD 8GB SODIMM DDR4 3200MT/s   | 1         | 2.86%   |
| Unknown                                                  | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 12        | 46.15%  |
| DDR4   | 9         | 34.62%  |
| DDR5   | 2         | 7.69%   |
| LPDDR4 | 1         | 3.85%   |
| LPDDR3 | 1         | 3.85%   |
| DDR2   | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 92.31%  |
| Row Of Chips | 2         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 40%     |
| 4096  | 8         | 26.67%  |
| 2048  | 6         | 20%     |
| 32768 | 2         | 6.67%   |
| 16384 | 1         | 3.33%   |
| 512   | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 8         | 26.67%  |
| 1334    | 4         | 13.33%  |
| 2667    | 3         | 10%     |
| 2400    | 3         | 10%     |
| 4800    | 2         | 6.67%   |
| 3200    | 2         | 6.67%   |
| 2133    | 2         | 6.67%   |
| 1333    | 2         | 6.67%   |
| 4266    | 1         | 3.33%   |
| 1067    | 1         | 3.33%   |
| 1066    | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

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
| Quanta                                 | 5         | 17.86%  |
| Chicony Electronics                    | 5         | 17.86%  |
| Sunplus Innovation Technology          | 3         | 10.71%  |
| Bison Electronics                      | 3         | 10.71%  |
| Microdia                               | 2         | 7.14%   |
| Y Media                                | 1         | 3.57%   |
| Sonix Technology                       | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Realtek Semiconductor                  | 1         | 3.57%   |
| Lite-On Technology                     | 1         | 3.57%   |
| Lenovo                                 | 1         | 3.57%   |
| IMC Networks                           | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| Apple                                  | 1         | 3.57%   |
| Alcor Micro                            | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Quanta VGA WebCam                                | 2         | 7.14%   |
| Microdia Integrated_Webcam_HD                    | 2         | 7.14%   |
| Bison Lenovo EasyCamera                          | 2         | 7.14%   |
| Y Media USB Camera                               | 1         | 3.57%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 3.57%   |
| Sunplus Laptop Integrated Webcam FHD             | 1         | 3.57%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 3.57%   |
| Sonix USB2.0 HD UVC WebCam                       | 1         | 3.57%   |
| Silicon Motion Web Camera                        | 1         | 3.57%   |
| Realtek USB Camera                               | 1         | 3.57%   |
| Quanta Laptop_Integrated_Webcam_2HDM             | 1         | 3.57%   |
| Quanta HD Webcam                                 | 1         | 3.57%   |
| Quanta HD User Facing                            | 1         | 3.57%   |
| Lite-On TOSHIBA Web Camera - HD                  | 1         | 3.57%   |
| Lenovo Integrated Webcam [R5U877]                | 1         | 3.57%   |
| IMC Networks Integrated Camera                   | 1         | 3.57%   |
| Chicony Lenovo EasyCamera                        | 1         | 3.57%   |
| Chicony Integrated Camera                        | 1         | 3.57%   |
| Chicony HD WebCam                                | 1         | 3.57%   |
| Chicony FHD Webcam                               | 1         | 3.57%   |
| Chicony 2.0M UVC WebCam                          | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 3.57%   |
| Bison HD Webcam                                  | 1         | 3.57%   |
| Apple FaceTime HD Camera                         | 1         | 3.57%   |
| Alcor Micro USB 2.0 Web Camera                   | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader | 1         | 100%    |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 27        | 84.38%  |
| 1     | 4         | 12.5%   |
| 2     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 3         | 42.86%  |
| Graphics card      | 3         | 42.86%  |
| Fingerprint reader | 1         | 14.29%  |

