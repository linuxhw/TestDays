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

Total: 53

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Positivo      | C41TF                       | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Acer          | Aspire A315-42G             | [65494c95ec](https://linux-hardware.org/?probe=65494c95ec) | Oct 23, 2023 |
| Acer          | Nitro AN515-51              | [be03ed57d8](https://linux-hardware.org/?probe=be03ed57d8) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | [e648a8c32a](https://linux-hardware.org/?probe=e648a8c32a) | Oct 20, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [673113259c](https://linux-hardware.org/?probe=673113259c) | Oct 14, 2023 |
| Acer          | Nitro AN515-47              | [0592faaf34](https://linux-hardware.org/?probe=0592faaf34) | Oct 12, 2023 |
| HP            | ZBook 15 G3                 | [cd9071e2ad](https://linux-hardware.org/?probe=cd9071e2ad) | Oct 12, 2023 |
| Dell          | Latitude E6420              | [7508b7cf4f](https://linux-hardware.org/?probe=7508b7cf4f) | Oct 10, 2023 |
| Dell          | Latitude E6420              | [90883fd019](https://linux-hardware.org/?probe=90883fd019) | Oct 02, 2023 |
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
| BigLinux 20.04            | 6         | 14.63%  |
| BigLinux                  | 5         | 12.2%   |
| BigLinux 23.0.0           | 3         | 7.32%   |
| BigLinux 22.0.0           | 3         | 7.32%   |
| BigLinux 19.04            | 3         | 7.32%   |
| BigLinux 22.1.0           | 2         | 4.88%   |
| BigLinux 21.3.7           | 2         | 4.88%   |
| BigLinux 23.01.06         | 1         | 2.44%   |
| BigLinux 23.0.3           | 1         | 2.44%   |
| BigLinux 22.11.19         | 1         | 2.44%   |
| BigLinux 22.11.14         | 1         | 2.44%   |
| BigLinux 22.10.06         | 1         | 2.44%   |
| BigLinux 22.0.5           | 1         | 2.44%   |
| BigLinux 22.0.4           | 1         | 2.44%   |
| BigLinux 21.3.6           | 1         | 2.44%   |
| BigLinux 21.3.5           | 1         | 2.44%   |
| BigLinux 21.1.2           | 1         | 2.44%   |
| BigLinux 2023-10-14_01-04 | 1         | 2.44%   |
| BigLinux 2023-08-04_06-17 | 1         | 2.44%   |
| BigLinux 2023-06-30_08-01 | 1         | 2.44%   |
| BigLinux 2023-06-23_06-21 | 1         | 2.44%   |
| BigLinux 2023-06-03_00-55 | 1         | 2.44%   |
| BigLinux 2023-04-11_15-10 | 1         | 2.44%   |
| BigLinux 2023-03-17_19-23 | 1         | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| BigLinux | 39        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.1.55-1-MANJARO       | 3         | 7.32%   |
| 6.5.5-1-MANJARO        | 2         | 4.88%   |
| 6.1.31-2-MANJARO       | 2         | 4.88%   |
| 6.1.23-1-MANJARO       | 2         | 4.88%   |
| 6.0.8-1-MANJARO        | 2         | 4.88%   |
| 5.8.0-43-generic       | 2         | 4.88%   |
| 5.2.8-xanmod8          | 2         | 4.88%   |
| 5.15.85-1-MANJARO      | 2         | 4.88%   |
| 5.15.102-1-MANJARO     | 2         | 4.88%   |
| 6.5.10-x64v2-xanmod1-1 | 1         | 2.44%   |
| 6.4.6-1-MANJARO        | 1         | 2.44%   |
| 6.3.5-2-MANJARO        | 1         | 2.44%   |
| 6.3.5-1-MANJARO        | 1         | 2.44%   |
| 6.3.13-1-MANJARO       | 1         | 2.44%   |
| 6.2.12-1-MANJARO       | 1         | 2.44%   |
| 6.1.1-1-MANJARO        | 1         | 2.44%   |
| 5.9.3-xanmod1          | 1         | 2.44%   |
| 5.8.0-28-generic       | 1         | 2.44%   |
| 5.4.0-48-generic       | 1         | 2.44%   |
| 5.3.6-xanmod5          | 1         | 2.44%   |
| 5.19.13-1-MANJARO      | 1         | 2.44%   |
| 5.15.94-1-MANJARO      | 1         | 2.44%   |
| 5.15.78-1-MANJARO      | 1         | 2.44%   |
| 5.15.60-1-MANJARO      | 1         | 2.44%   |
| 5.15.114-2-MANJARO     | 1         | 2.44%   |
| 5.10.61-1-MANJARO      | 1         | 2.44%   |
| 5.10.194-1-MANJARO     | 1         | 2.44%   |
| 5.10.136-1-MANJARO     | 1         | 2.44%   |
| 5.10.131-1-MANJARO     | 1         | 2.44%   |
| 5.10.129-1-MANJARO     | 1         | 2.44%   |
| 5.10.12-xanmod1        | 1         | 2.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 6.1.55   | 3         | 7.32%   |
| 5.8.0    | 3         | 7.32%   |
| 6.5.5    | 2         | 4.88%   |
| 6.3.5    | 2         | 4.88%   |
| 6.1.31   | 2         | 4.88%   |
| 6.1.23   | 2         | 4.88%   |
| 6.0.8    | 2         | 4.88%   |
| 5.2.8    | 2         | 4.88%   |
| 5.15.85  | 2         | 4.88%   |
| 5.15.102 | 2         | 4.88%   |
| 6.5.10   | 1         | 2.44%   |
| 6.4.6    | 1         | 2.44%   |
| 6.3.13   | 1         | 2.44%   |
| 6.2.12   | 1         | 2.44%   |
| 6.1.1    | 1         | 2.44%   |
| 5.9.3    | 1         | 2.44%   |
| 5.4.0    | 1         | 2.44%   |
| 5.3.6    | 1         | 2.44%   |
| 5.19.13  | 1         | 2.44%   |
| 5.15.94  | 1         | 2.44%   |
| 5.15.78  | 1         | 2.44%   |
| 5.15.60  | 1         | 2.44%   |
| 5.15.114 | 1         | 2.44%   |
| 5.10.61  | 1         | 2.44%   |
| 5.10.194 | 1         | 2.44%   |
| 5.10.136 | 1         | 2.44%   |
| 5.10.131 | 1         | 2.44%   |
| 5.10.129 | 1         | 2.44%   |
| 5.10.12  | 1         | 2.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 8         | 20.51%  |
| 5.15    | 8         | 20.51%  |
| 5.10    | 4         | 10.26%  |
| 6.5     | 3         | 7.69%   |
| 6.3     | 3         | 7.69%   |
| 5.8     | 3         | 7.69%   |
| 6.0     | 2         | 5.13%   |
| 5.2     | 2         | 5.13%   |
| 6.4     | 1         | 2.56%   |
| 6.2     | 1         | 2.56%   |
| 5.9     | 1         | 2.56%   |
| 5.4     | 1         | 2.56%   |
| 5.3     | 1         | 2.56%   |
| 5.19    | 1         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 35        | 89.74%  |
| KDE      | 2         | 5.13%   |
| Cinnamon | 1         | 2.56%   |
| Unknown  | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 38        | 97.44%  |
| Wayland | 1         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 29        | 74.36%  |
| Unknown | 8         | 20.51%  |
| LightDM | 2         | 5.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_BR   | 29        | 74.36%  |
| en_US   | 3         | 7.69%   |
| es_MX   | 2         | 5.13%   |
| fi_FI   | 1         | 2.56%   |
| es_CR   | 1         | 2.56%   |
| el_GR   | 1         | 2.56%   |
| de_DE   | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 26        | 65%     |
| BIOS | 14        | 35%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 32        | 82.05%  |
| Ext4    | 4         | 10.26%  |
| Overlay | 2         | 5.13%   |
| Unknown | 1         | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 23        | 57.5%   |
| MBR     | 9         | 22.5%   |
| Unknown | 8         | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 90%     |
| Yes       | 4         | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 61.54%  |
| Yes       | 15        | 38.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Acer                   | 8         | 20.51%  |
| Lenovo                 | 7         | 17.95%  |
| Dell                   | 6         | 15.38%  |
| ASUSTek Computer       | 4         | 10.26%  |
| Positivo               | 3         | 7.69%   |
| Hewlett-Packard        | 3         | 7.69%   |
| Toshiba                | 1         | 2.56%   |
| Sony                   | 1         | 2.56%   |
| Samsung Electronics    | 1         | 2.56%   |
| Multilaser             | 1         | 2.56%   |
| Clevo                  | 1         | 2.56%   |
| Avell High Performance | 1         | 2.56%   |
| Apple                  | 1         | 2.56%   |
| Alienware              | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba Satellite S55-A                | 1         | 2.56%   |
| Sony VGN-NR230AE                       | 1         | 2.56%   |
| Samsung 300E5M/300E5L                  | 1         | 2.56%   |
| Positivo Q464B                         | 1         | 2.56%   |
| Positivo C41TF                         | 1         | 2.56%   |
| Positivo C14RV01                       | 1         | 2.56%   |
| Multilaser MLSH1H LINUX                | 1         | 2.56%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 1         | 2.56%   |
| Lenovo ThinkPad T480s 20L70028US       | 1         | 2.56%   |
| Lenovo ThinkPad T410 25379N2           | 1         | 2.56%   |
| Lenovo IdeaPad Z470                    | 1         | 2.56%   |
| Lenovo IdeaPad S400 VIUS3              | 1         | 2.56%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 1         | 2.56%   |
| Lenovo IdeaPad 300-15ISK 80RS          | 1         | 2.56%   |
| HP ZBook 15 G3                         | 1         | 2.56%   |
| HP EliteBook 8760w                     | 1         | 2.56%   |
| HP 255 G7 Notebook PC                  | 1         | 2.56%   |
| Dell System XPS L502X                  | 1         | 2.56%   |
| Dell System Inspiron N7110             | 1         | 2.56%   |
| Dell Latitude E6420                    | 1         | 2.56%   |
| Dell Inspiron 7460                     | 1         | 2.56%   |
| Dell Inspiron 3480                     | 1         | 2.56%   |
| Dell G15 5520                          | 1         | 2.56%   |
| Clevo W340EU                           | 1         | 2.56%   |
| Avell High Performance STORM TWO       | 1         | 2.56%   |
| ASUS X45U                              | 1         | 2.56%   |
| ASUS X455LA                            | 1         | 2.56%   |
| ASUS VX7SX                             | 1         | 2.56%   |
| ASUS VivoBook_ASUSLaptop X515JA_X515JA | 1         | 2.56%   |
| Apple MacBookPro9,2                    | 1         | 2.56%   |
| Alienware 17                           | 1         | 2.56%   |
| Acer Predator G9-793                   | 1         | 2.56%   |
| Acer Nitro AN517-54                    | 1         | 2.56%   |
| Acer Nitro AN515-51                    | 1         | 2.56%   |
| Acer Nitro AN515-47                    | 1         | 2.56%   |
| Acer Aspire A515-51G                   | 1         | 2.56%   |
| Acer Aspire A315-53                    | 1         | 2.56%   |
| Acer Aspire A315-42G                   | 1         | 2.56%   |
| Acer A315-41                           | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 4         | 10.26%  |
| Acer Nitro                   | 3         | 7.69%   |
| Acer Aspire                  | 3         | 7.69%   |
| Lenovo ThinkPad              | 2         | 5.13%   |
| Dell System                  | 2         | 5.13%   |
| Dell Inspiron                | 2         | 5.13%   |
| Toshiba Satellite            | 1         | 2.56%   |
| Sony VGN-NR230AE             | 1         | 2.56%   |
| Samsung 300E5M               | 1         | 2.56%   |
| Positivo Q464B               | 1         | 2.56%   |
| Positivo C41TF               | 1         | 2.56%   |
| Positivo C14RV01             | 1         | 2.56%   |
| Multilaser MLSH1H            | 1         | 2.56%   |
| Lenovo Yoga                  | 1         | 2.56%   |
| HP ZBook                     | 1         | 2.56%   |
| HP EliteBook                 | 1         | 2.56%   |
| HP 255                       | 1         | 2.56%   |
| Dell Latitude                | 1         | 2.56%   |
| Dell G15                     | 1         | 2.56%   |
| Clevo W340EU                 | 1         | 2.56%   |
| Avell High Performance STORM | 1         | 2.56%   |
| ASUS X45U                    | 1         | 2.56%   |
| ASUS X455LA                  | 1         | 2.56%   |
| ASUS VX7SX                   | 1         | 2.56%   |
| ASUS VivoBook                | 1         | 2.56%   |
| Apple MacBookPro9            | 1         | 2.56%   |
| Alienware 17                 | 1         | 2.56%   |
| Acer Predator                | 1         | 2.56%   |
| Acer A315-41                 | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 5         | 12.82%  |
| 2012 | 5         | 12.82%  |
| 2011 | 5         | 12.82%  |
| 2019 | 4         | 10.26%  |
| 2017 | 4         | 10.26%  |
| 2018 | 3         | 7.69%   |
| 2016 | 3         | 7.69%   |
| 2013 | 3         | 7.69%   |
| 2022 | 2         | 5.13%   |
| 2023 | 1         | 2.56%   |
| 2020 | 1         | 2.56%   |
| 2014 | 1         | 2.56%   |
| 2009 | 1         | 2.56%   |
| 2007 | 1         | 2.56%   |

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
| Disabled | 39        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 10        | 25%     |
| 3.01-4.0    | 10        | 25%     |
| 16.01-24.0  | 8         | 20%     |
| 8.01-16.0   | 4         | 10%     |
| 32.01-64.0  | 2         | 5%      |
| 24.01-32.0  | 2         | 5%      |
| 1.01-2.0    | 2         | 5%      |
| 2.01-3.0    | 1         | 2.5%    |
| 64.01-256.0 | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 16        | 40%     |
| 2.01-3.0  | 10        | 25%     |
| 4.01-8.0  | 6         | 15%     |
| 3.01-4.0  | 5         | 12.5%   |
| 0.51-1.0  | 2         | 5%      |
| 8.01-16.0 | 1         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 69.23%  |
| 2      | 7         | 17.95%  |
| 3      | 4         | 10.26%  |
| 4      | 1         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 64.1%   |
| Yes       | 14        | 35.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 89.74%  |
| No        | 4         | 10.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 97.44%  |
| No        | 1         | 2.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 74.36%  |
| No        | 10        | 25.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Brazil     | 29        | 74.36%  |
| USA        | 2         | 5.13%   |
| Mexico     | 2         | 5.13%   |
| Greece     | 2         | 5.13%   |
| UK         | 1         | 2.56%   |
| Germany    | 1         | 2.56%   |
| Finland    | 1         | 2.56%   |
| Costa Rica | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Brasília             | 3         | 7.5%    |
| Sao Paulo             | 2         | 5%      |
| Curitiba              | 2         | 5%      |
| Castanhal             | 2         | 5%      |
| Belo Horizonte        | 2         | 5%      |
| Vitória da Conquista | 1         | 2.5%    |
| Thessaloniki          | 1         | 2.5%    |
| Sao Jose do Rio Preto | 1         | 2.5%    |
| Sao Domingos do Capim | 1         | 2.5%    |
| San José             | 1         | 2.5%    |
| Salvador              | 1         | 2.5%    |
| Rio de Janeiro        | 1         | 2.5%    |
| Mirassol              | 1         | 2.5%    |
| Minneapolis           | 1         | 2.5%    |
| Metepec               | 1         | 2.5%    |
| Marataizes            | 1         | 2.5%    |
| Maidstone             | 1         | 2.5%    |
| Londrina              | 1         | 2.5%    |
| Joensuu               | 1         | 2.5%    |
| Joao Monlevade        | 1         | 2.5%    |
| Hortolândia          | 1         | 2.5%    |
| Hoffman               | 1         | 2.5%    |
| Fernandopolis         | 1         | 2.5%    |
| Domingos Martins      | 1         | 2.5%    |
| Cruz Alta             | 1         | 2.5%    |
| Colombo               | 1         | 2.5%    |
| Caruaru               | 1         | 2.5%    |
| Caratinga             | 1         | 2.5%    |
| Campo Grande          | 1         | 2.5%    |
| Campeche              | 1         | 2.5%    |
| Berlin                | 1         | 2.5%    |
| Belém                | 1         | 2.5%    |
| Ampere                | 1         | 2.5%    |
| Alimos                | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 9         | 11     | 16.36%  |
| Samsung Electronics         | 6         | 6      | 10.91%  |
| Seagate                     | 5         | 5      | 9.09%   |
| Crucial                     | 4         | 4      | 7.27%   |
| KingSpec                    | 3         | 3      | 5.45%   |
| ADATA Technology            | 3         | 3      | 5.45%   |
| Unknown                     | 2         | 2      | 3.64%   |
| Toshiba                     | 2         | 3      | 3.64%   |
| SK hynix                    | 2         | 2      | 3.64%   |
| LITEON                      | 2         | 3      | 3.64%   |
| Hitachi                     | 2         | 2      | 3.64%   |
| HGST                        | 2         | 2      | 3.64%   |
| China                       | 2         | 2      | 3.64%   |
| A-DATA Technology           | 2         | 2      | 3.64%   |
| SanDisk                     | 1         | 1      | 1.82%   |
| PNY                         | 1         | 2      | 1.82%   |
| Netac                       | 1         | 2      | 1.82%   |
| Micron/Crucial Technology   | 1         | 1      | 1.82%   |
| Micron Technology           | 1         | 1      | 1.82%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.82%   |
| Kingston                    | 1         | 1      | 1.82%   |
| JMicron Technology          | 1         | 1      | 1.82%   |
| EYOTA                       | 1         | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 7.27%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 3         | 5.45%   |
| Unknown MMC Card  64GB                            | 2         | 3.64%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 3.64%   |
| KingSpec P3-512 512GB                             | 2         | 3.64%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                    | 1         | 1.82%   |
| WDC WD7500BPKX-75HPJT0 752GB                      | 1         | 1.82%   |
| WDC WD5000LPVX-75V0TT0 500GB                      | 1         | 1.82%   |
| WDC WD5000LPVT-08G33T1 500GB                      | 1         | 1.82%   |
| WDC WD3200BPVT-00JJ5T0 320GB                      | 1         | 1.82%   |
| WDC WD10SPZX-75Z10T3 1TB                          | 1         | 1.82%   |
| SK hynix HFS512GEJ9X125N 512GB                    | 1         | 1.82%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 1         | 1.82%   |
| Seagate ST320LM001 HN-M320MBB 320GB               | 1         | 1.82%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 1         | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1.82%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 1         | 1.82%   |
| Seagate Expansion HDD 8TB                         | 1         | 1.82%   |
| SanDisk SDSSDH3256G 256GB                         | 1         | 1.82%   |
| Samsung SSD 870 QVO 4TB                           | 1         | 1.82%   |
| Samsung HM501II 500GB                             | 1         | 1.82%   |
| PNY CS900 500GB SSD                               | 1         | 1.82%   |
| Netac NVMe SSD 2TB                                | 1         | 1.82%   |
| Micron/Crucial CT500P5SSD8 500GB                  | 1         | 1.82%   |
| Micron MTFDDAV512TBN-1AR15ABHA 512GB SSD          | 1         | 1.82%   |
| MAXIO (Hangzhou) YSSDHB-1TN7000 1TB               | 1         | 1.82%   |
| LITEON CV3-8D128-11 SATA 128GB SSD                | 1         | 1.82%   |
| LITEON CV1-8B128 128GB SSD                        | 1         | 1.82%   |
| Kingston SA400S37480G 480GB SSD                   | 1         | 1.82%   |
| KingSpec P4-120 120GB                             | 1         | 1.82%   |
| JMicron Tech 250GB                                | 1         | 1.82%   |
| Hitachi HTS727575A9E364 752GB                     | 1         | 1.82%   |
| Hitachi HTS545032A7E380 320GB                     | 1         | 1.82%   |
| HGST HTS721010A9E630 1TB                          | 1         | 1.82%   |
| HGST HTS541075A9E680 752GB                        | 1         | 1.82%   |
| EYOTA 512GB                                       | 1         | 1.82%   |
| Crucial CT500MX500SSD1 500GB                      | 1         | 1.82%   |
| Crucial CT500MX200SSD3 500GB                      | 1         | 1.82%   |
| Crucial CT480BX500SSD1 480GB                      | 1         | 1.82%   |
| Crucial CT275MX300SSD1 275GB                      | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 10     | 40%     |
| Seagate             | 5         | 5      | 25%     |
| Toshiba             | 2         | 3      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| HGST                | 2         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 4         | 4      | 21.05%  |
| KingSpec            | 3         | 3      | 15.79%  |
| LITEON              | 2         | 3      | 10.53%  |
| China               | 2         | 2      | 10.53%  |
| A-DATA Technology   | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |
| PNY                 | 1         | 2      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Kingston            | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 20        | 23     | 40%     |
| SSD     | 15        | 21     | 30%     |
| NVMe    | 11        | 13     | 22%     |
| MMC     | 2         | 2      | 4%      |
| Unknown | 2         | 2      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 44     | 68.09%  |
| NVMe | 11        | 13     | 23.4%   |
| SAS  | 2         | 2      | 4.26%   |
| MMC  | 2         | 2      | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 23     | 47.22%  |
| 0.51-1.0   | 16        | 18     | 44.44%  |
| 3.01-4.0   | 1         | 1      | 2.78%   |
| 1.01-2.0   | 1         | 1      | 2.78%   |
| 4.01-10.0  | 1         | 1      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 2001-3000      | 11        | 28.21%  |
| 251-500        | 8         | 20.51%  |
| 1001-2000      | 8         | 20.51%  |
| 101-250        | 5         | 12.82%  |
| More than 3000 | 4         | 10.26%  |
| 501-1000       | 2         | 5.13%   |
| 1-20           | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 51-100         | 15        | 36.59%  |
| 21-50          | 9         | 21.95%  |
| 101-250        | 8         | 19.51%  |
| 251-500        | 3         | 7.32%   |
| 1-20           | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| 2001-3000      | 1         | 2.44%   |
| 1001-2000      | 1         | 2.44%   |
| 501-1000       | 1         | 2.44%   |

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
| Works    | 20        | 29     | 44.44%  |
| Detected | 18        | 23     | 40%     |
| Malfunc  | 7         | 9      | 15.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 27        | 62.79%  |
| AMD                         | 5         | 11.63%  |
| Samsung Electronics         | 3         | 6.98%   |
| ADATA Technology            | 3         | 6.98%   |
| SK hynix                    | 2         | 4.65%   |
| Netac Technology            | 1         | 2.33%   |
| Micron/Crucial Technology   | 1         | 2.33%   |
| MAXIO Technology (Hangzhou) | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 13.33%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 11.11%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 8.89%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 8.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 6.67%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 2.22%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 2.22%   |
| Netac PCIe 4 INNOGRIT based NVMe SSD                                           | 1         | 2.22%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 1         | 2.22%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602                                   | 1         | 2.22%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.22%   |
| ADATA SM2P41C3 NVMe SSD (DRAM-less)                                            | 1         | 2.22%   |
| ADATA SM2P32A8 NVMe SSD (DRAM-less)                                            | 1         | 2.22%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                     | 1         | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 29        | 67.44%  |
| NVMe | 10        | 23.26%  |
| RAID | 3         | 6.98%   |
| IDE  | 1         | 2.33%   |

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


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 5.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 5.13%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 2.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 2.56%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 2.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 2.56%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 2.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 2.56%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 2.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 2.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 2.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 2.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 2.56%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 2.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 2.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.56%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.56%   |
| Intel 12th Gen Core i5-12500H                 | 1         | 2.56%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 1         | 2.56%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 1         | 2.56%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD Ryzen 5 7535HS with Radeon Graphics       | 1         | 2.56%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD C-70 APU with Radeon HD Graphics          | 1         | 2.56%   |
| AMD C-60 APU with Radeon HD Graphics          | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 11        | 28.21%  |
| Intel Core i7      | 10        | 25.64%  |
| Intel Core i3      | 4         | 10.26%  |
| AMD Ryzen 5        | 4         | 10.26%  |
| Other              | 3         | 7.69%   |
| AMD Ryzen 7        | 2         | 5.13%   |
| Intel Pentium Dual | 1         | 2.56%   |
| Intel Celeron      | 1         | 2.56%   |
| Intel Atom         | 1         | 2.56%   |
| AMD C-70           | 1         | 2.56%   |
| AMD C-60           | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 48.72%  |
| 4      | 14        | 35.9%   |
| 6      | 3         | 7.69%   |
| 14     | 1         | 2.56%   |
| 12     | 1         | 2.56%   |
| 8      | 1         | 2.56%   |

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
| 2      | 32        | 82.05%  |
| 1      | 7         | 17.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 97.44%  |
| Unknown        | 1         | 2.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 20.51%  |
| 0x206a7    | 5         | 12.82%  |
| 0x806e9    | 4         | 10.26%  |
| 0x906a3    | 2         | 5.13%   |
| 0x506e3    | 2         | 5.13%   |
| 0x306a9    | 2         | 5.13%   |
| 0x08108109 | 2         | 5.13%   |
| 0x05000119 | 2         | 5.13%   |
| 0x806ec    | 1         | 2.56%   |
| 0x806ea    | 1         | 2.56%   |
| 0x806d1    | 1         | 2.56%   |
| 0x706e5    | 1         | 2.56%   |
| 0x6fd      | 1         | 2.56%   |
| 0x406e3    | 1         | 2.56%   |
| 0x406c4    | 1         | 2.56%   |
| 0x306c3    | 1         | 2.56%   |
| 0x20652    | 1         | 2.56%   |
| 0x0a50000d | 1         | 2.56%   |
| 0x0a404102 | 1         | 2.56%   |
| 0x0810100b | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 8         | 20.51%  |
| SandyBridge      | 7         | 17.95%  |
| Skylake          | 3         | 7.69%   |
| IvyBridge        | 3         | 7.69%   |
| Zen+             | 2         | 5.13%   |
| Haswell          | 2         | 5.13%   |
| Bobcat           | 2         | 5.13%   |
| Alderlake Hybrid | 2         | 5.13%   |
| Unknown          | 2         | 5.13%   |
| Zen 3            | 1         | 2.56%   |
| Zen 2            | 1         | 2.56%   |
| Zen              | 1         | 2.56%   |
| Westmere         | 1         | 2.56%   |
| Silvermont       | 1         | 2.56%   |
| IceLake          | 1         | 2.56%   |
| Goldmont plus    | 1         | 2.56%   |
| Core             | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 54.9%   |
| Nvidia | 13        | 25.49%  |
| AMD    | 10        | 19.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 5         | 9.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 9.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 5.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 3.77%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 3.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.89%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 1.89%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 1.89%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.89%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 1.89%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 1.89%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.89%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.89%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                                 | 1         | 1.89%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                            | 1         | 1.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.89%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.89%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.89%   |
| Intel HD Graphics 630                                                                    | 1         | 1.89%   |
| Intel HD Graphics 530                                                                    | 1         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.89%   |
| AMD Wrestler [Radeon HD 7290]                                                            | 1         | 1.89%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 1.89%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.89%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 1         | 1.89%   |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.89%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 1.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 41.03%  |
| Intel + Nvidia | 10        | 25.64%  |
| 1 x AMD        | 7         | 17.95%  |
| 1 x Nvidia     | 2         | 5.13%   |
| 2 x Intel      | 1         | 2.56%   |
| 2 x AMD        | 1         | 2.56%   |
| Intel + AMD    | 1         | 2.56%   |
| AMD + Nvidia   | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 31        | 79.49%  |
| Proprietary | 8         | 20.51%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 66.67%  |
| 1.01-2.0   | 5         | 12.82%  |
| 0.01-0.5   | 3         | 7.69%   |
| 0.51-1.0   | 2         | 5.13%   |
| 7.01-8.0   | 1         | 2.56%   |
| 3.01-4.0   | 1         | 2.56%   |
| 2.01-3.0   | 1         | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 19.15%  |
| BOE                     | 8         | 17.02%  |
| LG Display              | 7         | 14.89%  |
| Chimei Innolux          | 7         | 14.89%  |
| Goldstar                | 4         | 8.51%   |
| Samsung Electronics     | 3         | 6.38%   |
| Panasonic               | 2         | 4.26%   |
| Chi Mei Optoelectronics | 2         | 4.26%   |
| Lenovo                  | 1         | 2.13%   |
| Hewlett-Packard         | 1         | 2.13%   |
| GDH                     | 1         | 2.13%   |
| CSO                     | 1         | 2.13%   |
| Apple                   | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Panasonic TV MEIC10C 1920x540 697x392mm 31.5-inch                        | 2         | 4.26%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 2         | 4.26%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch        | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 2.13%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch             | 1         | 2.13%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch                  | 1         | 2.13%   |
| Hewlett-Packard 23tm HWP3110 1920x1080 509x286mm 23.0-inch               | 1         | 2.13%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch              | 1         | 2.13%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 2.13%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                   | 1         | 2.13%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                    | 1         | 2.13%   |
| GDH TV PHILCO GDH0030 1920x1080 708x398mm 32.0-inch                      | 1         | 2.13%   |
| CSO LCD Monitor CSO140C 2880x1800 302x188mm 14.0-inch                    | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN14C8 1920x1080 309x173mm 13.9-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch          | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1724 1600x900 382x215mm 17.3-inch | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1465 1366x768 309x174mm 14.0-inch | 1         | 2.13%   |
| BOE LCD Monitor BOE0B02 1920x1080 344x194mm 15.5-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE0A8F 2560x1440 381x214mm 17.2-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE09B4 1920x1080 382x215mm 17.3-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE074F 1920x1080 309x173mm 13.9-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 2.13%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE0025 1366x768 309x173mm 13.9-inch                     | 1         | 2.13%   |
| AU Optronics LCD Monitor AUOED8F 1920x1080 344x193mm 15.5-inch           | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 18        | 38.3%   |
| 1920x1080 (FHD) | 17        | 36.17%  |
| 2560x1080       | 3         | 6.38%   |
| 1920x540        | 2         | 4.26%   |
| 1600x900 (HD+)  | 2         | 4.26%   |
| 1280x800 (WXGA) | 2         | 4.26%   |
| 3840x2160 (4K)  | 1         | 2.13%   |
| 2880x1800       | 1         | 2.13%   |
| 2560x1440 (QHD) | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 34.04%  |
| 14     | 9         | 19.15%  |
| 13     | 7         | 14.89%  |
| 17     | 6         | 12.77%  |
| 34     | 2         | 4.26%   |
| 31     | 2         | 4.26%   |
| 23     | 2         | 4.26%   |
| 52     | 1         | 2.13%   |
| 28     | 1         | 2.13%   |
| 21     | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 63.83%  |
| 351-400     | 7         | 14.89%  |
| 601-700     | 3         | 6.38%   |
| 701-800     | 2         | 4.26%   |
| 501-600     | 2         | 4.26%   |
| 401-500     | 1         | 2.13%   |
| 201-300     | 1         | 2.13%   |
| 1001-1500   | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 85.37%  |
| 21/9  | 3         | 7.32%   |
| 16/10 | 3         | 7.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 34.04%  |
| 101-110        | 16        | 34.04%  |
| 121-130        | 6         | 12.77%  |
| 351-500        | 4         | 8.51%   |
| 201-250        | 3         | 6.38%   |
| More than 1000 | 1         | 2.13%   |
| 251-300        | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 20        | 43.48%  |
| 121-160       | 14        | 30.43%  |
| 51-100        | 9         | 19.57%  |
| More than 240 | 1         | 2.17%   |
| 1-50          | 1         | 2.17%   |
| 161-240       | 1         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 30        | 75%     |
| 2     | 10        | 25%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 37.88%  |
| Qualcomm Atheros         | 15        | 22.73%  |
| Intel                    | 15        | 22.73%  |
| Broadcom                 | 3         | 4.55%   |
| Ralink Technology        | 1         | 1.52%   |
| Ralink                   | 1         | 1.52%   |
| MediaTek                 | 1         | 1.52%   |
| Marvell Technology Group | 1         | 1.52%   |
| JMicron Technology       | 1         | 1.52%   |
| Edimax Technology        | 1         | 1.52%   |
| Belkin Components        | 1         | 1.52%   |
| ASIX Electronics         | 1         | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 14        | 17.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 6.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 6.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 2.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.28%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.28%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.28%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.28%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 1.28%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.28%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.28%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 1.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 1.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.28%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.28%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 1         | 1.28%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.28%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.28%   |
| Intel Wireless 8260                                                     | 1         | 1.28%   |
| Intel Wireless 7265                                                     | 1         | 1.28%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.28%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.28%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 1.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 34.15%  |
| Qualcomm Atheros      | 12        | 29.27%  |
| Realtek Semiconductor | 7         | 17.07%  |
| Broadcom              | 3         | 7.32%   |
| Ralink Technology     | 1         | 2.44%   |
| Ralink                | 1         | 2.44%   |
| MediaTek              | 1         | 2.44%   |
| Edimax Technology     | 1         | 2.44%   |
| Belkin Components     | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                             | 5         | 11.9%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                             | 3         | 7.14%   |
| Realtek RTL8188EE Wireless Network Adapter                                             | 2         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                         | 2         | 4.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                       | 2         | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                               | 1         | 2.38%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                    | 1         | 2.38%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                             | 1         | 2.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                        | 1         | 2.38%   |
| Realtek 802.11n WLAN Adapter                                                           | 1         | 2.38%   |
| Realtek 802.11ac NIC                                                                   | 1         | 2.38%   |
| Ralink MT7601U Wireless Adapter                                                        | 1         | 2.38%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                              | 1         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                             | 1         | 2.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                | 1         | 2.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                          | 1         | 2.38%   |
| Intel Wireless 8265 / 8275                                                             | 1         | 2.38%   |
| Intel Wireless 8260                                                                    | 1         | 2.38%   |
| Intel Wireless 7265                                                                    | 1         | 2.38%   |
| Intel Wi-Fi 6 AX200                                                                    | 1         | 2.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                                         | 1         | 2.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                        | 1         | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                       | 1         | 2.38%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                          | 1         | 2.38%   |
| Intel Centrino Ultimate-N 6300                                                         | 1         | 2.38%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                          | 1         | 2.38%   |
| Intel Centrino Advanced-N 6200                                                         | 1         | 2.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                               | 1         | 2.38%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                            | 1         | 2.38%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                           | 1         | 2.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                                         | 1         | 2.38%   |
| Broadcom BCM43228 802.11a/b/g/n                                                        | 1         | 2.38%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v1000 [Ralink RT3070] | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 62.86%  |
| Intel                    | 5         | 14.29%  |
| Qualcomm Atheros         | 4         | 11.43%  |
| Marvell Technology Group | 1         | 2.86%   |
| JMicron Technology       | 1         | 2.86%   |
| Broadcom                 | 1         | 2.86%   |
| ASIX Electronics         | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 38.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 13.89%  |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.78%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 2.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.78%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 52.05%  |
| Ethernet | 35        | 47.95%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 76.32%  |
| Ethernet | 9         | 23.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 32        | 82.05%  |
| 1     | 5         | 12.82%  |
| 0     | 2         | 5.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 61.54%  |
| Yes  | 15        | 38.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 41.38%  |
| Qualcomm Atheros Communications | 5         | 17.24%  |
| Lite-On Technology              | 4         | 13.79%  |
| Foxconn / Hon Hai               | 2         | 6.9%    |
| Realtek Semiconductor           | 1         | 3.45%   |
| IMC Networks                    | 1         | 3.45%   |
| Hewlett-Packard                 | 1         | 3.45%   |
| Dell                            | 1         | 3.45%   |
| Broadcom                        | 1         | 3.45%   |
| Apple                           | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device              | 3         | 10.34%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth      | 3         | 10.34%  |
| Intel Bluetooth wireless interface              | 3         | 10.34%  |
| Intel AX201 Bluetooth                           | 3         | 10.34%  |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0          | 2         | 6.9%    |
| Intel Bluetooth Device                          | 2         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)  | 2         | 6.9%    |
| Realtek  Bluetooth 4.2 Adapter                  | 1         | 3.45%   |
| Lite-On Bluetooth Device                        | 1         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                | 1         | 3.45%   |
| Intel AX200 Bluetooth                           | 1         | 3.45%   |
| IMC Networks BCM20702A0                         | 1         | 3.45%   |
| HP Broadcom 2070 Bluetooth Combo                | 1         | 3.45%   |
| Foxconn / Hon Hai Wireless_Device               | 1         | 3.45%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device | 1         | 3.45%   |
| Dell DW375 Bluetooth Module                     | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2.1)                     | 1         | 3.45%   |
| Apple Bluetooth USB Host Controller             | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 30        | 60%     |
| Nvidia                 | 10        | 20%     |
| AMD                    | 9         | 18%     |
| Generalplus Technology | 1         | 2%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 11.67%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 10%     |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 10%     |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 6.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 5%      |
| Nvidia Audio device                                                        | 2         | 3.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 3.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 3.33%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 3.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 3.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.67%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.67%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.67%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.67%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.67%   |
| Generalplus Technology USB Audio Device                                    | 1         | 1.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 1.67%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 28.13%  |
| Smart               | 4         | 12.5%   |
| Micron Technology   | 4         | 12.5%   |
| Unknown             | 3         | 9.38%   |
| SK hynix            | 3         | 9.38%   |
| A-DATA Technology   | 2         | 6.25%   |
| Teikon              | 1         | 3.13%   |
| Kingston            | 1         | 3.13%   |
| Kembona             | 1         | 3.13%   |
| G.Skill             | 1         | 3.13%   |
| Crucial             | 1         | 3.13%   |
| Corsair             | 1         | 3.13%   |
| Unknown             | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 5.41%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 2.7%    |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s               | 1         | 2.7%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 2.7%    |
| Unknown RAM Module 2GB SODIMM DDR2                        | 1         | 2.7%    |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s    | 1         | 2.7%    |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 2.7%    |
| Smart RAM SH564568FH8NZPHSCR 2048MB SODIMM DDR3 1333MT/s  | 1         | 2.7%    |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s     | 1         | 2.7%    |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s     | 1         | 2.7%    |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s     | 1         | 2.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s              | 1         | 2.7%    |
| SK hynix RAM MMXIV 4096MB SODIMM DDR3 1333MT/s            | 1         | 2.7%    |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s     | 1         | 2.7%    |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1600MT/s       | 1         | 2.7%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 1         | 2.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 2.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 2.7%    |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 1         | 2.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 2.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 2.7%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s  | 1         | 2.7%    |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 2.7%    |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4266MT/s        | 1         | 2.7%    |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                | 1         | 2.7%    |
| Micron RAM 16ATF2G64HZ-2G1B1 16GB SODIMM DDR4 2133MT/s    | 1         | 2.7%    |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s     | 1         | 2.7%    |
| Kembona RAM KBN1333D3N9/8G 8GB SODIMM DDR3 1333MT/s       | 1         | 2.7%    |
| Kembona RAM KBN13333D3S9/8G 8GB SODIMM DDR3 1333MT/s      | 1         | 2.7%    |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s      | 1         | 2.7%    |
| Crucial RAM CT25664BF160B.C8FE 2GB SODIMM DDR3 1600MT/s   | 1         | 2.7%    |
| Corsair RAM CMSX32GX4M2A2400C16 16GB SODIMM DDR4 2400MT/s | 1         | 2.7%    |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s               | 1         | 2.7%    |
| A-DATA RAM AD5S480032G-B 32GB SODIMM DDR5 4800MT/s        | 1         | 2.7%    |
| A-DATA RAM AD4S320038G22-BHYD 8GB SODIMM DDR4 3200MT/s    | 1         | 2.7%    |
| Unknown                                                   | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 12        | 42.86%  |
| DDR4   | 10        | 35.71%  |
| DDR5   | 3         | 10.71%  |
| LPDDR4 | 1         | 3.57%   |
| LPDDR3 | 1         | 3.57%   |
| DDR2   | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 26        | 92.86%  |
| Row Of Chips | 2         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 37.5%   |
| 4096  | 8         | 25%     |
| 2048  | 6         | 18.75%  |
| 16384 | 3         | 9.38%   |
| 32768 | 2         | 6.25%   |
| 512   | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 8         | 25%     |
| 2400    | 4         | 12.5%   |
| 1334    | 4         | 12.5%   |
| 4800    | 3         | 9.38%   |
| 2667    | 3         | 9.38%   |
| 3200    | 2         | 6.25%   |
| 2133    | 2         | 6.25%   |
| 1333    | 2         | 6.25%   |
| 4266    | 1         | 3.13%   |
| 1067    | 1         | 3.13%   |
| 1066    | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

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
| Quanta                                 | 8         | 22.86%  |
| Chicony Electronics                    | 6         | 17.14%  |
| Sunplus Innovation Technology          | 4         | 11.43%  |
| Microdia                               | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| Bison Electronics                      | 2         | 5.71%   |
| Y Media                                | 1         | 2.86%   |
| SunplusIT                              | 1         | 2.86%   |
| Sonix Technology                       | 1         | 2.86%   |
| Silicon Motion                         | 1         | 2.86%   |
| Realtek Semiconductor                  | 1         | 2.86%   |
| Lite-On Technology                     | 1         | 2.86%   |
| Lenovo                                 | 1         | 2.86%   |
| IMC Networks                           | 1         | 2.86%   |
| Apple                                  | 1         | 2.86%   |
| Alcor Micro                            | 1         | 2.86%   |
| Acer                                   | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Quanta VGA WebCam                                   | 3         | 8.57%   |
| Quanta HD Webcam                                    | 2         | 5.71%   |
| Microdia Integrated_Webcam_HD                       | 2         | 5.71%   |
| Y Media USB Camera                                  | 1         | 2.86%   |
| SunplusIT MTD camera                                | 1         | 2.86%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 2.86%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 2.86%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 2.86%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 2.86%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 2.86%   |
| Silicon Motion Web Camera                           | 1         | 2.86%   |
| Realtek USB Camera                                  | 1         | 2.86%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 2.86%   |
| Quanta HD User Facing                               | 1         | 2.86%   |
| Quanta ACER HD User Facing                          | 1         | 2.86%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 2.86%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 2.86%   |
| IMC Networks Integrated Camera                      | 1         | 2.86%   |
| Chicony Lenovo EasyCamera                           | 1         | 2.86%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.86%   |
| Chicony Integrated Camera                           | 1         | 2.86%   |
| Chicony HD WebCam                                   | 1         | 2.86%   |
| Chicony FHD Webcam                                  | 1         | 2.86%   |
| Chicony 2.0M UVC WebCam                             | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.86%   |
| Bison Lenovo EasyCamera                             | 1         | 2.86%   |
| Bison HD Webcam                                     | 1         | 2.86%   |
| Apple FaceTime HD Camera                            | 1         | 2.86%   |
| Alcor Micro USB 2.0 Camera                          | 1         | 2.86%   |
| Acer Lenovo EasyCamera                              | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Synaptics        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader       | 1         | 50%     |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 31        | 79.49%  |
| 1     | 6         | 15.38%  |
| 2     | 2         | 5.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 4         | 36.36%  |
| Net/wireless       | 3         | 27.27%  |
| Fingerprint reader | 2         | 18.18%  |
| Storage            | 1         | 9.09%   |
| Chipcard           | 1         | 9.09%   |

