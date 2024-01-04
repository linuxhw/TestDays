Mageia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Mageia.

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

Total: 61

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | VivoBook_ASUSLaptop K660... | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek  | VivoBook_ASUSLaptop K660... | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| HP       | 255 15.6 inch G9 Noteboo... | [b1394cc278](https://linux-hardware.org/?probe=b1394cc278) | Oct 30, 2023 |
| Lenovo   | IdeaPad Slim 3 15AMN8 82... | [02c2fabd1e](https://linux-hardware.org/?probe=02c2fabd1e) | Oct 11, 2023 |
| Lenovo   | IdeaPad Slim 3 15AMN8 82... | [02a4135aff](https://linux-hardware.org/?probe=02a4135aff) | Oct 09, 2023 |
| Fujitsu  | S6420                       | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| HP       | Pavilion Notebook           | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| Dell     | Latitude E5470              | [f64529e38b](https://linux-hardware.org/?probe=f64529e38b) | Aug 08, 2023 |
| ASUSTek  | Q551LN                      | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| HP       | Laptop 14-cm0xxx            | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| Compaq   | 420                         | [6f4350d53e](https://linux-hardware.org/?probe=6f4350d53e) | Jul 10, 2023 |
| ASUSTek  | K73SD                       | [063e42ac60](https://linux-hardware.org/?probe=063e42ac60) | May 22, 2023 |
| Dell     | Latitude 7370               | [a254d0d7f1](https://linux-hardware.org/?probe=a254d0d7f1) | Apr 02, 2023 |
| Dell     | Latitude 7370               | [b8a0b25983](https://linux-hardware.org/?probe=b8a0b25983) | Mar 30, 2023 |
| HP       | ProBook 5330m               | [2ec50367d4](https://linux-hardware.org/?probe=2ec50367d4) | Mar 11, 2023 |
| HP       | Unknown                     | [702ed67add](https://linux-hardware.org/?probe=702ed67add) | Dec 17, 2022 |
| HP       | Unknown                     | [d952fd785e](https://linux-hardware.org/?probe=d952fd785e) | Dec 17, 2022 |
| Fujitsu  | CELSIUS H720                | [a7eacb37c5](https://linux-hardware.org/?probe=a7eacb37c5) | Dec 03, 2022 |
| Irbis    | NB264                       | [103ca2d20b](https://linux-hardware.org/?probe=103ca2d20b) | Sep 16, 2022 |
| ASUSTek  | X751LN                      | [68cd0152fb](https://linux-hardware.org/?probe=68cd0152fb) | Aug 22, 2022 |
| Schenker | VIA_14_SVI14E20             | [3adb69bbf5](https://linux-hardware.org/?probe=3adb69bbf5) | Jun 03, 2022 |
| Notebook | NH5x_NH7x_HHx_HJx_HKx       | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Dell     | Latitude E5570              | [ec640c6644](https://linux-hardware.org/?probe=ec640c6644) | May 12, 2022 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Toshiba  | dynabook R73/A              | [42b60c90c7](https://linux-hardware.org/?probe=42b60c90c7) | Apr 01, 2022 |
| Dell     | Latitude E5570              | [38032eae74](https://linux-hardware.org/?probe=38032eae74) | Dec 06, 2021 |
| Dell     | Latitude E5570              | [9314738bbb](https://linux-hardware.org/?probe=9314738bbb) | Dec 06, 2021 |
| Dell     | Precision 5530              | [f98313a80c](https://linux-hardware.org/?probe=f98313a80c) | Nov 29, 2021 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [46250d420a](https://linux-hardware.org/?probe=46250d420a) | Aug 14, 2021 |
| Lenovo   | ThinkPad T61 6468AE2        | [216fbf401b](https://linux-hardware.org/?probe=216fbf401b) | Aug 05, 2021 |
| ASUSTek  | X751LN                      | [8c0efa94e8](https://linux-hardware.org/?probe=8c0efa94e8) | Jul 08, 2021 |
| Notebook | NL40_50GU                   | [baa8447288](https://linux-hardware.org/?probe=baa8447288) | May 08, 2021 |
| Medion   | DEFENDER P10                | [cb752c0a4a](https://linux-hardware.org/?probe=cb752c0a4a) | May 01, 2021 |
| Medion   | DEFENDER P10                | [f42aa05a37](https://linux-hardware.org/?probe=f42aa05a37) | May 01, 2021 |
| Fujitsu  | LIFEBOOK E752               | [8ec052ba75](https://linux-hardware.org/?probe=8ec052ba75) | Apr 15, 2021 |
| Lenovo   | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| ASUSTek  | X751LN                      | [09afc59907](https://linux-hardware.org/?probe=09afc59907) | Apr 02, 2021 |
| ASUSTek  | X556URK                     | [4904d2c78e](https://linux-hardware.org/?probe=4904d2c78e) | Mar 18, 2021 |
| ASUSTek  | X751LN                      | [0bb2c11bdc](https://linux-hardware.org/?probe=0bb2c11bdc) | Feb 24, 2021 |
| Dell     | Latitude E6530              | [035378659f](https://linux-hardware.org/?probe=035378659f) | Feb 12, 2021 |
| Dell     | Inspiron 5480               | [2ae12f394c](https://linux-hardware.org/?probe=2ae12f394c) | Jan 27, 2021 |
| Kiano    | SlimNote 15.6               | [55179f361c](https://linux-hardware.org/?probe=55179f361c) | Jan 08, 2021 |
| Kiano    | SlimNote 15.6               | [5379fd7478](https://linux-hardware.org/?probe=5379fd7478) | Jan 08, 2021 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [01aa1a7b95](https://linux-hardware.org/?probe=01aa1a7b95) | Dec 30, 2020 |
| ASUSTek  | X751LN                      | [f7f3533d54](https://linux-hardware.org/?probe=f7f3533d54) | Dec 27, 2020 |
| Dell     | Inspiron 5480               | [1261d0c9d3](https://linux-hardware.org/?probe=1261d0c9d3) | Dec 21, 2020 |
| HP       | Spectre 13 Ultrabook        | [9b88fe4fa5](https://linux-hardware.org/?probe=9b88fe4fa5) | Nov 30, 2020 |
| HP       | EliteBook 840 G3            | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP       | EliteBook 840 G3            | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | [889cb35866](https://linux-hardware.org/?probe=889cb35866) | Nov 13, 2020 |
| HP       | ProBook 445 G7              | [2e97281aa0](https://linux-hardware.org/?probe=2e97281aa0) | Nov 05, 2020 |
| Acer     | Aspire V3-772               | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| Dell     | Inspiron 5480               | [62bb8575f1](https://linux-hardware.org/?probe=62bb8575f1) | Oct 22, 2020 |
| HP       | Unknown                     | [b12d1589a1](https://linux-hardware.org/?probe=b12d1589a1) | Sep 08, 2020 |
| Acer     | Aspire 7741                 | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| HP       | Pavilion dv6                | [021a94f63e](https://linux-hardware.org/?probe=021a94f63e) | Sep 03, 2020 |
| Lenovo   | G480 20149                  | [5598a535c7](https://linux-hardware.org/?probe=5598a535c7) | Jul 24, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [8e31f45bf5](https://linux-hardware.org/?probe=8e31f45bf5) | May 07, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [4b71b90312](https://linux-hardware.org/?probe=4b71b90312) | May 04, 2020 |
| Lenovo   | G570 20079                  | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Mageia 8 | 18        | 45%     |
| Mageia 9 | 11        | 27.5%   |
| Mageia 7 | 11        | 27.5%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Mageia | 38        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7   | 4         | 8.89%   |
| 5.7.19-desktop-1.mga7   | 3         | 6.67%   |
| 6.4.8-desktop-6.mga9    | 2         | 4.44%   |
| 6.4.16-desktop-3.mga9   | 2         | 4.44%   |
| 5.6.14-desktop-2.mga7   | 2         | 4.44%   |
| 5.15.4-desktop-1.mga8   | 2         | 4.44%   |
| 5.15.32-desktop-1.mga8  | 2         | 4.44%   |
| 6.4.9-desktop-4.mga9    | 1         | 2.22%   |
| 6.4.6-desktop-2.mga9    | 1         | 2.22%   |
| 6.4.3-desktop-1.mga9    | 1         | 2.22%   |
| 6.2.2-desktop-2.mga9    | 1         | 2.22%   |
| 6.1.14-desktop-1.mga9   | 1         | 2.22%   |
| 6.0.10-desktop-1.mga9   | 1         | 2.22%   |
| 5.9.6-desktop-1.mga8    | 1         | 2.22%   |
| 5.9.16-desktop-1.mga7   | 1         | 2.22%   |
| 5.9.11-desktop-3.mga8   | 1         | 2.22%   |
| 5.8.5-desktop-2.mga8    | 1         | 2.22%   |
| 5.7.8-desktop-1.mga8    | 1         | 2.22%   |
| 5.6.6-desktop-1.mga7    | 1         | 2.22%   |
| 5.18.15-desktop-1.mga8  | 1         | 2.22%   |
| 5.16.10-desktop-2.mga8  | 1         | 2.22%   |
| 5.15.98-desktop-1.mga8  | 1         | 2.22%   |
| 5.15.79-desktop-1.mga8  | 1         | 2.22%   |
| 5.15.43-desktop-1.mga8  | 1         | 2.22%   |
| 5.15.35-desktop-2.mga8  | 1         | 2.22%   |
| 5.15.117-desktop-2.mga8 | 1         | 2.22%   |
| 5.10.46-desktop-1.mga8  | 1         | 2.22%   |
| 5.10.33-desktop-1.mga8  | 1         | 2.22%   |
| 5.10.30-desktop-1.mga8  | 1         | 2.22%   |
| 5.10.27-desktop-1.mga8  | 1         | 2.22%   |
| 5.10.25-desktop-1.mga8  | 1         | 2.22%   |
| 5.10.20-desktop-2.mga7  | 1         | 2.22%   |
| 5.10.16-desktop-1.mga8  | 1         | 2.22%   |
| 5.10.16-desktop-1.mga7  | 1         | 2.22%   |
| 5.10.12-desktop-2.mga8  | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.7.19   | 7         | 15.56%  |
| 6.4.8    | 2         | 4.44%   |
| 6.4.16   | 2         | 4.44%   |
| 5.6.14   | 2         | 4.44%   |
| 5.15.4   | 2         | 4.44%   |
| 5.15.32  | 2         | 4.44%   |
| 5.10.16  | 2         | 4.44%   |
| 6.4.9    | 1         | 2.22%   |
| 6.4.6    | 1         | 2.22%   |
| 6.4.3    | 1         | 2.22%   |
| 6.2.2    | 1         | 2.22%   |
| 6.1.14   | 1         | 2.22%   |
| 6.0.10   | 1         | 2.22%   |
| 5.9.6    | 1         | 2.22%   |
| 5.9.16   | 1         | 2.22%   |
| 5.9.11   | 1         | 2.22%   |
| 5.8.5    | 1         | 2.22%   |
| 5.7.8    | 1         | 2.22%   |
| 5.6.6    | 1         | 2.22%   |
| 5.18.15  | 1         | 2.22%   |
| 5.16.10  | 1         | 2.22%   |
| 5.15.98  | 1         | 2.22%   |
| 5.15.79  | 1         | 2.22%   |
| 5.15.43  | 1         | 2.22%   |
| 5.15.35  | 1         | 2.22%   |
| 5.15.117 | 1         | 2.22%   |
| 5.10.46  | 1         | 2.22%   |
| 5.10.33  | 1         | 2.22%   |
| 5.10.30  | 1         | 2.22%   |
| 5.10.27  | 1         | 2.22%   |
| 5.10.25  | 1         | 2.22%   |
| 5.10.20  | 1         | 2.22%   |
| 5.10.12  | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 9         | 20.93%  |
| 5.7     | 8         | 18.6%   |
| 6.4     | 7         | 16.28%  |
| 5.10    | 7         | 16.28%  |
| 5.9     | 3         | 6.98%   |
| 5.6     | 3         | 6.98%   |
| 6.2     | 1         | 2.33%   |
| 6.1     | 1         | 2.33%   |
| 6.0     | 1         | 2.33%   |
| 5.8     | 1         | 2.33%   |
| 5.18    | 1         | 2.33%   |
| 5.16    | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 38        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 22        | 55%     |
| KDE     | 8         | 20%     |
| XFCE    | 4         | 10%     |
| GNOME   | 4         | 10%     |
| MATE    | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 37        | 97.37%  |
| Wayland | 1         | 2.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 16        | 42.11%  |
| Unknown | 16        | 42.11%  |
| TDM     | 2         | 5.26%   |
| LightDM | 2         | 5.26%   |
| GDM     | 2         | 5.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 7         | 18.42%  |
| fr_FR | 6         | 15.79%  |
| en_GB | 5         | 13.16%  |
| de_DE | 3         | 7.89%   |
| it_IT | 2         | 5.26%   |
| hu_HU | 2         | 5.26%   |
| es_MX | 2         | 5.26%   |
| es_GT | 2         | 5.26%   |
| bg_BG | 2         | 5.26%   |
| ru_RU | 1         | 2.63%   |
| ro_RO | 1         | 2.63%   |
| pt_BR | 1         | 2.63%   |
| pl_PL | 1         | 2.63%   |
| es_ES | 1         | 2.63%   |
| es_CR | 1         | 2.63%   |
| en_CA | 1         | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 27        | 64.29%  |
| BIOS | 15        | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 36        | 94.74%  |
| Xfs     | 1         | 2.63%   |
| Overlay | 1         | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 19        | 46.34%  |
| Unknown | 14        | 34.15%  |
| MBR     | 8         | 19.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 86.84%  |
| Yes       | 5         | 13.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 77.5%   |
| Yes       | 9         | 22.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 10        | 26.32%  |
| Dell             | 6         | 15.79%  |
| ASUSTek Computer | 6         | 15.79%  |
| Lenovo           | 5         | 13.16%  |
| Fujitsu          | 3         | 7.89%   |
| Notebook         | 2         | 5.26%   |
| Acer             | 2         | 5.26%   |
| Toshiba          | 1         | 2.63%   |
| Schenker         | 1         | 2.63%   |
| Medion           | 1         | 2.63%   |
| Kiano            | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 5.26%   |
| Toshiba dynabook R73/A                   | 1         | 2.63%   |
| Schenker VIA_14_SVI14E20                 | 1         | 2.63%   |
| Notebook NL40_50GU                       | 1         | 2.63%   |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 2.63%   |
| Medion DEFENDER P10                      | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 2.63%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 2.63%   |
| Lenovo IdeaPad Slim 3 15AMN8 82XQ        | 1         | 2.63%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 2.63%   |
| Lenovo G480 20149                        | 1         | 2.63%   |
| Kiano SlimNote 15.6                      | 1         | 2.63%   |
| HP Spectre 13 Ultrabook                  | 1         | 2.63%   |
| HP ProBook 5330m                         | 1         | 2.63%   |
| HP ProBook 445 G7                        | 1         | 2.63%   |
| HP Pavilion Notebook                     | 1         | 2.63%   |
| HP Pavilion dv6                          | 1         | 2.63%   |
| HP Laptop 14-cm0xxx                      | 1         | 2.63%   |
| HP EliteBook 840 G3                      | 1         | 2.63%   |
| HP 255 15.6 inch G9 Notebook PC          | 1         | 2.63%   |
| Fujitsu S6420                            | 1         | 2.63%   |
| Fujitsu LIFEBOOK E752                    | 1         | 2.63%   |
| Fujitsu CELSIUS H720                     | 1         | 2.63%   |
| Dell Precision 5530                      | 1         | 2.63%   |
| Dell Latitude E6530                      | 1         | 2.63%   |
| Dell Latitude E5570                      | 1         | 2.63%   |
| Dell Latitude E5470                      | 1         | 2.63%   |
| Dell Latitude 7370                       | 1         | 2.63%   |
| Dell Inspiron 5480                       | 1         | 2.63%   |
| ASUS X751LN                              | 1         | 2.63%   |
| ASUS X556URK                             | 1         | 2.63%   |
| ASUS VivoBook_ASUSLaptop K6602ZC_K6602ZC | 1         | 2.63%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR     | 1         | 2.63%   |
| ASUS Q551LN                              | 1         | 2.63%   |
| ASUS K73SD                               | 1         | 2.63%   |
| Acer Aspire V3-772                       | 1         | 2.63%   |
| Acer Aspire 7741                         | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell Latitude    | 4         | 10.53%  |
| Lenovo ThinkPad  | 2         | 5.26%   |
| Lenovo IdeaPad   | 2         | 5.26%   |
| HP ProBook       | 2         | 5.26%   |
| HP Pavilion      | 2         | 5.26%   |
| ASUS VivoBook    | 2         | 5.26%   |
| Acer Aspire      | 2         | 5.26%   |
| Unknown          | 2         | 5.26%   |
| Toshiba dynabook | 1         | 2.63%   |
| Schenker VIA     | 1         | 2.63%   |
| Notebook NL40    | 1         | 2.63%   |
| Notebook NH5x    | 1         | 2.63%   |
| Medion DEFENDER  | 1         | 2.63%   |
| Lenovo G480      | 1         | 2.63%   |
| Kiano SlimNote   | 1         | 2.63%   |
| HP Spectre       | 1         | 2.63%   |
| HP Laptop        | 1         | 2.63%   |
| HP EliteBook     | 1         | 2.63%   |
| HP 255           | 1         | 2.63%   |
| Fujitsu S6420    | 1         | 2.63%   |
| Fujitsu LIFEBOOK | 1         | 2.63%   |
| Fujitsu CELSIUS  | 1         | 2.63%   |
| Dell Precision   | 1         | 2.63%   |
| Dell Inspiron    | 1         | 2.63%   |
| ASUS X751LN      | 1         | 2.63%   |
| ASUS X556URK     | 1         | 2.63%   |
| ASUS Q551LN      | 1         | 2.63%   |
| ASUS K73SD       | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 5         | 13.16%  |
| 2012 | 5         | 13.16%  |
| 2018 | 4         | 10.53%  |
| 2020 | 3         | 7.89%   |
| 2019 | 3         | 7.89%   |
| 2017 | 3         | 7.89%   |
| 2022 | 2         | 5.26%   |
| 2014 | 2         | 5.26%   |
| 2013 | 2         | 5.26%   |
| 2011 | 2         | 5.26%   |
| 2008 | 2         | 5.26%   |
| 2007 | 2         | 5.26%   |
| 2023 | 1         | 2.63%   |
| 2021 | 1         | 2.63%   |
| 2010 | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 38        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 38        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 38.46%  |
| 8.01-16.0  | 8         | 20.51%  |
| 3.01-4.0   | 7         | 17.95%  |
| 16.01-24.0 | 5         | 12.82%  |
| 32.01-64.0 | 3         | 7.69%   |
| 1.01-2.0   | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 17        | 40.48%  |
| 4.01-8.0 | 10        | 23.81%  |
| 1.01-2.0 | 10        | 23.81%  |
| 3.01-4.0 | 5         | 11.9%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 77.5%   |
| 2      | 8         | 20%     |
| 3      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 60.53%  |
| Yes       | 15        | 39.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 78.95%  |
| No        | 8         | 21.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 97.37%  |
| No        | 1         | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 78.95%  |
| No        | 8         | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| France      | 6         | 15.79%  |
| UK          | 4         | 10.53%  |
| USA         | 3         | 7.89%   |
| Italy       | 3         | 7.89%   |
| Germany     | 3         | 7.89%   |
| Romania     | 2         | 5.26%   |
| Mexico      | 2         | 5.26%   |
| Guatemala   | 2         | 5.26%   |
| Bulgaria    | 2         | 5.26%   |
| Russia      | 1         | 2.63%   |
| Poland      | 1         | 2.63%   |
| Netherlands | 1         | 2.63%   |
| Indonesia   | 1         | 2.63%   |
| Hungary     | 1         | 2.63%   |
| Greece      | 1         | 2.63%   |
| Costa Rica  | 1         | 2.63%   |
| Colombia    | 1         | 2.63%   |
| Canada      | 1         | 2.63%   |
| Brazil      | 1         | 2.63%   |
| Australia   | 1         | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Guatemala City        | 2         | 4.65%   |
| Wiwersheim            | 1         | 2.33%   |
| Tver                  | 1         | 2.33%   |
| Tours                 | 1         | 2.33%   |
| Toulouse              | 1         | 2.33%   |
| Surabaya              | 1         | 2.33%   |
| Strasbourg            | 1         | 2.33%   |
| Sofia                 | 1         | 2.33%   |
| Sao Paulo             | 1         | 2.33%   |
| Sant'Angelo Lodigiano | 1         | 2.33%   |
| San Antonio           | 1         | 2.33%   |
| Rommerskirchen        | 1         | 2.33%   |
| Rome                  | 1         | 2.33%   |
| Quaregna              | 1         | 2.33%   |
| Poznan                | 1         | 2.33%   |
| Paris                 | 1         | 2.33%   |
| Oxford                | 1         | 2.33%   |
| Ottawa                | 1         | 2.33%   |
| Odenville             | 1         | 2.33%   |
| Nordenham             | 1         | 2.33%   |
| Miercurea-Ciuc        | 1         | 2.33%   |
| Melbourne             | 1         | 2.33%   |
| Marino                | 1         | 2.33%   |
| March                 | 1         | 2.33%   |
| Luce                  | 1         | 2.33%   |
| León                 | 1         | 2.33%   |
| Le Faouet             | 1         | 2.33%   |
| Iztapalapa            | 1         | 2.33%   |
| Győr                 | 1         | 2.33%   |
| Guapiles              | 1         | 2.33%   |
| Giannitsa             | 1         | 2.33%   |
| Eaubonne              | 1         | 2.33%   |
| Dundee                | 1         | 2.33%   |
| Denver                | 1         | 2.33%   |
| Chemnitz              | 1         | 2.33%   |
| Burgas                | 1         | 2.33%   |
| Bucharest             | 1         | 2.33%   |
| Bradford              | 1         | 2.33%   |
| Bogotá               | 1         | 2.33%   |
| Bernwiller            | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 6         | 9      | 12.77%  |
| WDC                     | 5         | 7      | 10.64%  |
| Toshiba                 | 5         | 6      | 10.64%  |
| Unknown                 | 4         | 4      | 8.51%   |
| Seagate                 | 4         | 4      | 8.51%   |
| Kingston                | 4         | 5      | 8.51%   |
| Hitachi                 | 3         | 3      | 6.38%   |
| SK hynix                | 2         | 3      | 4.26%   |
| Intel                   | 2         | 2      | 4.26%   |
| Crucial                 | 2         | 2      | 4.26%   |
| Union Memory (Shenzhen) | 1         | 1      | 2.13%   |
| SanDisk                 | 1         | 1      | 2.13%   |
| Phison                  | 1         | 1      | 2.13%   |
| LDLC                    | 1         | 1      | 2.13%   |
| KingFast                | 1         | 2      | 2.13%   |
| JMicron Technology      | 1         | 1      | 2.13%   |
| HGST                    | 1         | 5      | 2.13%   |
| Fujitsu                 | 1         | 1      | 2.13%   |
| China                   | 1         | 1      | 2.13%   |
| A-DATA Technology       | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                     | 2         | 3.92%   |
| Samsung SSD 860 EVO 500GB                    | 2         | 3.92%   |
| Crucial CT120BX500SSD1 120GB                 | 2         | 3.92%   |
| WDC WDS500G2B0C-00PXH0 500GB                 | 1         | 1.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1.96%   |
| WDC WDS100T2B0A 1TB SSD                      | 1         | 1.96%   |
| WDC WD5000LPLX-66ZNTT1 500GB                 | 1         | 1.96%   |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 1.96%   |
| Unknown MMC Card  8GB                        | 1         | 1.96%   |
| Unknown MMC Card  7GB                        | 1         | 1.96%   |
| Unknown MMC Card  32GB                       | 1         | 1.96%   |
| Unknown MMC Card  16GB                       | 1         | 1.96%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.96%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.96%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1.96%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1.96%   |
| SK hynix SKHynix_HFS256GEJ4X112N 256GB       | 1         | 1.96%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB    | 1         | 1.96%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 1.96%   |
| Seagate ST96812AS 64GB                       | 1         | 1.96%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1.96%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.96%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD          | 1         | 1.96%   |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 1.96%   |
| Samsung SSD 870 QVO 1TB                      | 1         | 1.96%   |
| Samsung SSD 850 EVO 500GB                    | 1         | 1.96%   |
| Samsung NVMe SSD Drive 500GB                 | 1         | 1.96%   |
| Samsung MZVLQ256HBJD-00BH1 256GB             | 1         | 1.96%   |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 1.96%   |
| Phison E12S-1TB-PHISON-SSD-B27B              | 1         | 1.96%   |
| LDLC F6+M.2 480 480GB                        | 1         | 1.96%   |
| Kingston SNVS1000G 1TB                       | 1         | 1.96%   |
| Kingston SA400S37480G 480GB SSD              | 1         | 1.96%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1.96%   |
| Kingston SA2000M8500G 500GB                  | 1         | 1.96%   |
| Kingston NVMe SSD Drive 1TB                  | 1         | 1.96%   |
| KingFast SSD 256GB                           | 1         | 1.96%   |
| JMicron Generic 2TB                          | 1         | 1.96%   |
| Intel SSDPEKNU010TZ 1024GB                   | 1         | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 26.67%  |
| Seagate | 4         | 4      | 26.67%  |
| Hitachi | 3         | 3      | 20%     |
| WDC     | 2         | 4      | 13.33%  |
| HGST    | 1         | 5      | 6.67%   |
| Fujitsu | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 23.53%  |
| WDC                 | 2         | 2      | 11.76%  |
| Kingston            | 2         | 2      | 11.76%  |
| Crucial             | 2         | 2      | 11.76%  |
| SanDisk             | 1         | 1      | 5.88%   |
| LDLC                | 1         | 1      | 5.88%   |
| KingFast            | 1         | 2      | 5.88%   |
| JMicron Technology  | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| China               | 1         | 1      | 5.88%   |
| A-DATA Technology   | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 16        | 19     | 34.04%  |
| HDD  | 15        | 22     | 31.91%  |
| NVMe | 12        | 15     | 25.53%  |
| MMC  | 4         | 4      | 8.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 40     | 63.04%  |
| NVMe | 12        | 15     | 26.09%  |
| MMC  | 4         | 4      | 8.7%    |
| SAS  | 1         | 1      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 25     | 70.97%  |
| 0.51-1.0   | 8         | 15     | 25.81%  |
| 1.01-2.0   | 1         | 1      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 15        | 39.47%  |
| 501-1000   | 11        | 28.95%  |
| 101-250    | 9         | 23.68%  |
| 1001-2000  | 1         | 2.63%   |
| 51-100     | 1         | 2.63%   |
| Unknown    | 1         | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 10        | 24.39%  |
| 21-50     | 9         | 21.95%  |
| 101-250   | 8         | 19.51%  |
| 51-100    | 8         | 19.51%  |
| 501-1000  | 3         | 7.32%   |
| 251-500   | 1         | 2.44%   |
| 1001-2000 | 1         | 2.44%   |
| Unknown   | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 20%     |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 20%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 20%     |
| Hitachi HTS725050A9A364 500GB      | 1         | 1      | 20%     |
| Fujitsu MHZ2160BH G2 160GB         | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |
| Fujitsu | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |
| Fujitsu | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 100%    |

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
| Works    | 23        | 27     | 52.27%  |
| Detected | 16        | 28     | 36.36%  |
| Malfunc  | 5         | 5      | 11.36%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 28        | 65.12%  |
| AMD                          | 5         | 11.63%  |
| Samsung Electronics          | 3         | 6.98%   |
| SK hynix                     | 2         | 4.65%   |
| Kingston Technology Company  | 2         | 4.65%   |
| Toshiba America Info Systems | 1         | 2.33%   |
| SanDisk                      | 1         | 2.33%   |
| Phison Electronics           | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 10.64%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 8.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 6.38%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 6.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 4.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.26%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 2         | 4.26%   |
| AMD SB600 IDE                                                                  | 2         | 4.26%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 2.13%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 2.13%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 2.13%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.13%   |
| Phison E12 NVMe Controller                                                     | 1         | 2.13%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 1         | 2.13%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 2.13%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 2.13%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.13%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 2.13%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 28        | 60.87%  |
| NVMe | 11        | 23.91%  |
| IDE  | 4         | 8.7%    |
| RAID | 3         | 6.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 78.95%  |
| AMD    | 8         | 21.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 7.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 2         | 5.26%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 5.26%   |
| AMD Turion 64 X2 Mobile Technology TL-60        | 2         | 5.26%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 1         | 2.63%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 2.63%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz                | 1         | 2.63%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 2.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.63%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 2.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 2.63%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 2.63%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 2.63%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 2.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 2.63%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz              | 1         | 2.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 2.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 2.63%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 2.63%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 1         | 2.63%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz            | 1         | 2.63%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 1         | 2.63%   |
| Intel 12th Gen Core i5-12450H                   | 1         | 2.63%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 1         | 2.63%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 2.63%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 2.63%   |
| AMD Ryzen 3 7320U with Radeon Graphics          | 1         | 2.63%   |
| AMD Ryzen 3 5425U with Radeon Graphics          | 1         | 2.63%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G    | 1         | 2.63%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 11        | 28.95%  |
| Intel Core i5           | 10        | 26.32%  |
| Other                   | 2         | 5.26%   |
| Intel Core i3           | 2         | 5.26%   |
| AMD Turion 64 X2 Mobile | 2         | 5.26%   |
| AMD Ryzen 7             | 2         | 5.26%   |
| AMD Ryzen 3             | 2         | 5.26%   |
| Intel Pentium Silver    | 1         | 2.63%   |
| Intel Pentium           | 1         | 2.63%   |
| Intel Core m5           | 1         | 2.63%   |
| Intel Core 2 Duo        | 1         | 2.63%   |
| Intel Atom              | 1         | 2.63%   |
| AMD A6                  | 1         | 2.63%   |
| AMD A10                 | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 60.53%  |
| 4      | 10        | 26.32%  |
| 8      | 3         | 7.89%   |
| 6      | 2         | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 29        | 76.32%  |
| 1      | 9         | 23.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 32.5%   |
| 0x306a9    | 4         | 10%     |
| 0x806e9    | 3         | 7.5%    |
| 0x406e3    | 3         | 7.5%    |
| 0x40651    | 2         | 5%      |
| 0x206a7    | 2         | 5%      |
| 0xa0652    | 1         | 2.5%    |
| 0x906ea    | 1         | 2.5%    |
| 0x806ec    | 1         | 2.5%    |
| 0x806eb    | 1         | 2.5%    |
| 0x706a1    | 1         | 2.5%    |
| 0x506e3    | 1         | 2.5%    |
| 0x406c4    | 1         | 2.5%    |
| 0x306c3    | 1         | 2.5%    |
| 0x20655    | 1         | 2.5%    |
| 0x0a50000d | 1         | 2.5%    |
| 0x08a00008 | 1         | 2.5%    |
| 0x08600106 | 1         | 2.5%    |
| 0x08108109 | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 6         | 15.79%  |
| Skylake          | 5         | 13.16%  |
| IvyBridge        | 5         | 13.16%  |
| Haswell          | 4         | 10.53%  |
| SandyBridge      | 3         | 7.89%   |
| K8 Hammer        | 2         | 5.26%   |
| Excavator        | 2         | 5.26%   |
| Unknown          | 2         | 5.26%   |
| Zen+             | 1         | 2.63%   |
| Zen 3            | 1         | 2.63%   |
| Zen 2            | 1         | 2.63%   |
| Westmere         | 1         | 2.63%   |
| Silvermont       | 1         | 2.63%   |
| Penryn           | 1         | 2.63%   |
| Goldmont plus    | 1         | 2.63%   |
| CometLake        | 1         | 2.63%   |
| Alderlake Hybrid | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 58.82%  |
| Nvidia | 12        | 23.53%  |
| AMD    | 9         | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 9.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 5.77%   |
| Intel HD Graphics 620                                                                    | 3         | 5.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 5.77%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 3.85%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 2         | 3.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.92%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.92%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 1.92%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.92%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.92%   |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 1.92%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1.92%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.92%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.92%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.92%   |
| Intel HD Graphics 530                                                                    | 1         | 1.92%   |
| Intel HD Graphics 515                                                                    | 1         | 1.92%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.92%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 1         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.92%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.92%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.92%   |
| AMD Mendocino                                                                            | 1         | 1.92%   |
| AMD Barcelo                                                                              | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 42.11%  |
| Intel + Nvidia | 12        | 31.58%  |
| 1 x AMD        | 7         | 18.42%  |
| 2 x Intel      | 1         | 2.63%   |
| 2 x AMD        | 1         | 2.63%   |
| Intel + AMD    | 1         | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 38        | 97.44%  |
| Proprietary | 1         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 58.54%  |
| 1.01-2.0   | 8         | 19.51%  |
| 0.01-0.5   | 4         | 9.76%   |
| 3.01-4.0   | 2         | 4.88%   |
| 0.51-1.0   | 2         | 4.88%   |
| 5.01-6.0   | 1         | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 20%     |
| Chimei Innolux          | 7         | 17.5%   |
| BOE                     | 7         | 17.5%   |
| AU Optronics            | 7         | 17.5%   |
| Samsung Electronics     | 4         | 10%     |
| Sharp                   | 2         | 5%      |
| Chi Mei Optoelectronics | 2         | 5%      |
| Lenovo                  | 1         | 2.5%    |
| Ancor Communications    | 1         | 2.5%    |
| Acer                    | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch             | 2         | 4.88%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 2.44%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch                   | 1         | 2.44%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch        | 1         | 2.44%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch        | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch     | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 1         | 2.44%   |
| LG Display LCD Monitor LGD066A 1920x1080 344x194mm 15.5-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch               | 1         | 2.44%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD0457 1920x1080 345x194mm 15.6-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 2.44%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 1         | 2.44%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 1         | 2.44%   |
| LG Display LCD Monitor LGD0215 1920x1080 345x194mm 15.6-inch              | 1         | 2.44%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1364 1366x768 293x164mm 13.2-inch           | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch          | 1         | 2.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 2.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 2.44%   |
| BOE LCD Monitor BOE0B2B 1920x1200 345x215mm 16.0-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE0806 1920x1080 309x173mm 13.9-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 1         | 2.44%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO429D 1920x1080 382x215mm 17.3-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO369F 1920x1080 344x194mm 15.5-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 1         | 2.44%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch          | 1         | 2.44%   |
| Acer G247HL ACR03FA 1920x1080 531x299mm 24.0-inch                         | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 51.28%  |
| 1366x768 (WXGA)    | 9         | 23.08%  |
| 1600x900 (HD+)     | 4         | 10.26%  |
| 1920x1200 (WUXGA)  | 2         | 5.13%   |
| 1280x800 (WXGA)    | 2         | 5.13%   |
| 3200x1800 (QHD+)   | 1         | 2.56%   |
| 1680x1050 (WSXGA+) | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 42.5%   |
| 13     | 8         | 20%     |
| 17     | 7         | 17.5%   |
| 14     | 4         | 10%     |
| 24     | 2         | 5%      |
| 22     | 1         | 2.5%    |
| 16     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 67.5%   |
| 351-400     | 7         | 17.5%   |
| 201-300     | 3         | 7.5%    |
| 501-600     | 2         | 5%      |
| 401-500     | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 86.84%  |
| 16/10 | 5         | 13.16%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 42.5%   |
| 81-90          | 9         | 22.5%   |
| 121-130        | 6         | 15%     |
| 71-80          | 3         | 7.5%    |
| 201-250        | 3         | 7.5%    |
| 131-140        | 1         | 2.5%    |
| 111-120        | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 51.28%  |
| 101-120       | 12        | 30.77%  |
| 51-100        | 5         | 12.82%  |
| More than 240 | 1         | 2.56%   |
| 161-240       | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 35        | 92.11%  |
| 2     | 3         | 7.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 37.93%  |
| Realtek Semiconductor    | 15        | 25.86%  |
| Qualcomm Atheros         | 7         | 12.07%  |
| Broadcom                 | 6         | 10.34%  |
| Sierra Wireless          | 2         | 3.45%   |
| Broadcom Limited         | 2         | 3.45%   |
| MediaTek                 | 1         | 1.72%   |
| Marvell Technology Group | 1         | 1.72%   |
| Dell                     | 1         | 1.72%   |
| ASIX Electronics         | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 14.08%  |
| Intel Wireless 8260                                               | 4         | 5.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 5.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 4.23%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 4.23%   |
| Sierra Wireless MC8305 Modem                                      | 2         | 2.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.82%   |
| Intel Wireless-AC 9260                                            | 2         | 2.82%   |
| Intel Wireless 7260                                               | 2         | 2.82%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 2.82%   |
| Broadcom BCM4311 802.11a/b/g                                      | 2         | 2.82%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.41%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.41%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.41%   |
| Intel Wireless 3165                                               | 1         | 1.41%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 1.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.41%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.41%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.41%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                              | 1         | 1.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.41%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.41%   |
| Broadcom BCM4323 802.11abgn Wireless Adapter                      | 1         | 1.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 51.22%  |
| Qualcomm Atheros      | 7         | 17.07%  |
| Broadcom              | 5         | 12.2%   |
| Realtek Semiconductor | 4         | 9.76%   |
| Sierra Wireless       | 2         | 4.88%   |
| MediaTek              | 1         | 2.44%   |
| Dell                  | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 9.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 9.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 7.32%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 7.32%   |
| Sierra Wireless MC8305 Modem                                   | 2         | 4.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 4.88%   |
| Intel Wireless-AC 9260                                         | 2         | 4.88%   |
| Intel Wireless 7260                                            | 2         | 4.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 4.88%   |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 4.88%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 2.44%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.44%   |
| Intel Wireless 3165                                            | 1         | 2.44%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 2.44%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.44%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 2.44%   |
| Broadcom BCM4323 802.11abgn Wireless Adapter                   | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 13        | 43.33%  |
| Intel                    | 10        | 33.33%  |
| Qualcomm Atheros         | 2         | 6.67%   |
| Broadcom Limited         | 2         | 6.67%   |
| Marvell Technology Group | 1         | 3.33%   |
| Broadcom                 | 1         | 3.33%   |
| ASIX Electronics         | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 33.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 13.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 6.67%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 6.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 3.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.33%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.33%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.33%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 3.33%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 3.33%   |
| ASIX AX88772B                                                     | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 55.22%  |
| Ethernet | 30        | 44.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 85%     |
| Ethernet | 6         | 15%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 73.68%  |
| 1     | 9         | 23.68%  |
| 0     | 1         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 76.92%  |
| Yes  | 9         | 23.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 13        | 41.94%  |
| Realtek Semiconductor   | 4         | 12.9%   |
| IMC Networks            | 4         | 12.9%   |
| Hewlett-Packard         | 3         | 9.68%   |
| Foxconn / Hon Hai       | 2         | 6.45%   |
| Taiyo Yuden             | 1         | 3.23%   |
| Lite-On Technology      | 1         | 3.23%   |
| Dell                    | 1         | 3.23%   |
| Cambridge Silicon Radio | 1         | 3.23%   |
| Broadcom                | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 16.13%  |
| Realtek Bluetooth Radio                             | 3         | 9.68%   |
| Intel AX200 Bluetooth                               | 3         | 9.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.45%   |
| IMC Networks Bluetooth Device                       | 2         | 6.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 6.45%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 6.45%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.23%   |
| Lite-On Bluetooth Device                            | 1         | 3.23%   |
| Intel Bluetooth Device                              | 1         | 3.23%   |
| IMC Networks Wireless_Device                        | 1         | 3.23%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.23%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.23%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 29        | 67.44%  |
| AMD                 | 8         | 18.6%   |
| Nvidia              | 5         | 11.63%  |
| C-Media Electronics | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 13.46%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 9.62%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 7.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 5.77%   |
| Nvidia Audio device                                                        | 2         | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 3.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 3.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.92%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.92%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.92%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.92%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.92%   |
| AMD High Definition Audio Controller                                       | 1         | 1.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 30.56%  |
| SK hynix            | 8         | 22.22%  |
| Kingston            | 5         | 13.89%  |
| Unknown             | 4         | 11.11%  |
| Micron Technology   | 3         | 8.33%   |
| Corsair             | 2         | 5.56%   |
| Unknown (ABCD)      | 1         | 2.78%   |
| Smart               | 1         | 2.78%   |
| Crucial             | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 5.41%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 2.7%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 2.7%    |
| Unknown RAM Module 2GB SODIMM 533MT/s                            | 1         | 2.7%    |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 2.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.7%    |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 2.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 2.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 2.7%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 2.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.7%    |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.7%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Samsung RAM M4 70T5663QZ3-CE6 2048MB SODIMM DDR2 667MT/s         | 1         | 2.7%    |
| Samsung RAM K3LKBKB0BM-MGCP 8GB Row Of Chips LPDDR5 6400MT/s     | 1         | 2.7%    |
| Micron RAM 8KTS51264HDZ-1G6E1 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.7%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 2.7%    |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s            | 1         | 2.7%    |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 1         | 2.7%    |
| Kingston RAM KFYHV1-HYC 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.7%    |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s                | 1         | 2.7%    |
| Kingston RAM ACR16D3LS1KBG/8G 8GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| Kingston RAM 99U5428-042.A00G 4096MB SODIMM DDR3 4199MT/s        | 1         | 2.7%    |
| Kingston RAM 9905428-102.A00G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 2.7%    |
| Corsair RAM CMSX16GX4M1A2666C18 16GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Corsair RAM CM4X8GF2666C18S2 8GB SODIMM DDR4 3000MT/s            | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 12        | 41.38%  |
| DDR3    | 11        | 37.93%  |
| SDRAM   | 1         | 3.45%   |
| LPDDR5  | 1         | 3.45%   |
| LPDDR4  | 1         | 3.45%   |
| LPDDR3  | 1         | 3.45%   |
| DDR2    | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 96.43%  |
| Row Of Chips | 1         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 14        | 46.67%  |
| 8192  | 11        | 36.67%  |
| 2048  | 3         | 10%     |
| 16384 | 2         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 9         | 28.13%  |
| 2667  | 4         | 12.5%   |
| 2400  | 4         | 12.5%   |
| 3200  | 3         | 9.38%   |
| 2133  | 2         | 6.25%   |
| 1334  | 2         | 6.25%   |
| 6400  | 1         | 3.13%   |
| 4199  | 1         | 3.13%   |
| 3266  | 1         | 3.13%   |
| 3000  | 1         | 3.13%   |
| 1066  | 1         | 3.13%   |
| 975   | 1         | 3.13%   |
| 667   | 1         | 3.13%   |
| 533   | 1         | 3.13%   |

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
| Chicony Electronics                    | 13        | 36.11%  |
| Realtek Semiconductor                  | 4         | 11.11%  |
| IMC Networks                           | 3         | 8.33%   |
| Microdia                               | 2         | 5.56%   |
| Luxvisions Innotech Limited            | 2         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.56%   |
| Alcor Micro                            | 2         | 5.56%   |
| Suyin                                  | 1         | 2.78%   |
| Sunplus Innovation Technology          | 1         | 2.78%   |
| Sonix Technology                       | 1         | 2.78%   |
| Primax Electronics                     | 1         | 2.78%   |
| Logitech                               | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| Apple                                  | 1         | 2.78%   |
| Acer                                   | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 3         | 8.11%   |
| Chicony USB2.0 Camera                                                      | 3         | 8.11%   |
| Chicony Integrated Camera                                                  | 3         | 8.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 5.41%   |
| Chicony FJ Camera                                                          | 2         | 5.41%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.7%    |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 2.7%    |
| Sonix USB2.0 FHD UVC WebCam                                                | 1         | 2.7%    |
| Realtek USB Camera                                                         | 1         | 2.7%    |
| Primax HP Truevision FHD                                                   | 1         | 2.7%    |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.7%    |
| Microdia Integrated Webcam                                                 | 1         | 2.7%    |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 2.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2.7%    |
| Logitech Fujitsu Webcam                                                    | 1         | 2.7%    |
| Lite-On HP Webcam                                                          | 1         | 2.7%    |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 2.7%    |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 2.7%    |
| Chicony Lenovo EasyCamera                                                  | 1         | 2.7%    |
| Chicony Integrated IR Camera                                               | 1         | 2.7%    |
| Chicony Integrated HP HD Webcam                                            | 1         | 2.7%    |
| Chicony HD WebCam                                                          | 1         | 2.7%    |
| Chicony 1.3M HD WebCam                                                     | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 2.7%    |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 2.7%    |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 2.7%    |
| Alcor Micro Asus Integrated Webcam                                         | 1         | 2.7%    |
| Acer BisonCam,NB Pro                                                       | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 4         | 36.36%  |
| AuthenTec                          | 4         | 36.36%  |
| Shenzhen Goodix Technology         | 2         | 18.18%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 27.27%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner                            | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 9.09%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 9.09%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 60%     |
| O2 Micro | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 40%     |
| Broadcom 5880                                                                | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 19        | 46.34%  |
| 1     | 16        | 39.02%  |
| 3     | 3         | 7.32%   |
| 2     | 3         | 7.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 39.29%  |
| Graphics card         | 8         | 28.57%  |
| Chipcard              | 5         | 17.86%  |
| Storage               | 1         | 3.57%   |
| Net/wireless          | 1         | 3.57%   |
| Multimedia controller | 1         | 3.57%   |
| Camera                | 1         | 3.57%   |

