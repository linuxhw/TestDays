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

Total: 64

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | G50-30 80G0                 | [e1e268d222](https://linux-hardware.org/?probe=e1e268d222) | Jan 18, 2024 |
| HP       | ProBook 450 G1              | [028d205023](https://linux-hardware.org/?probe=028d205023) | Jan 09, 2024 |
| HP       | Compaq 6710b (GB887ET#AB... | [2aaeccac56](https://linux-hardware.org/?probe=2aaeccac56) | Jan 08, 2024 |
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
| Mageia 8 | 19        | 44.19%  |
| Mageia 9 | 13        | 30.23%  |
| Mageia 7 | 11        | 25.58%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Mageia | 41        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7   | 4         | 8.33%   |
| 5.7.19-desktop-1.mga7   | 3         | 6.25%   |
| 6.4.8-desktop-6.mga9    | 2         | 4.17%   |
| 6.4.16-desktop-3.mga9   | 2         | 4.17%   |
| 5.6.14-desktop-2.mga7   | 2         | 4.17%   |
| 5.15.4-desktop-1.mga8   | 2         | 4.17%   |
| 5.15.32-desktop-1.mga8  | 2         | 4.17%   |
| 6.5.13-server-6.mga9    | 1         | 2.08%   |
| 6.5.13-desktop-6.mga9   | 1         | 2.08%   |
| 6.4.9-desktop-4.mga9    | 1         | 2.08%   |
| 6.4.6-desktop-2.mga9    | 1         | 2.08%   |
| 6.4.3-desktop-1.mga9    | 1         | 2.08%   |
| 6.2.2-desktop-2.mga9    | 1         | 2.08%   |
| 6.1.45-desktop-1.mga8   | 1         | 2.08%   |
| 6.1.14-desktop-1.mga9   | 1         | 2.08%   |
| 6.0.10-desktop-1.mga9   | 1         | 2.08%   |
| 5.9.6-desktop-1.mga8    | 1         | 2.08%   |
| 5.9.16-desktop-1.mga7   | 1         | 2.08%   |
| 5.9.11-desktop-3.mga8   | 1         | 2.08%   |
| 5.8.5-desktop-2.mga8    | 1         | 2.08%   |
| 5.7.8-desktop-1.mga8    | 1         | 2.08%   |
| 5.6.6-desktop-1.mga7    | 1         | 2.08%   |
| 5.18.15-desktop-1.mga8  | 1         | 2.08%   |
| 5.16.10-desktop-2.mga8  | 1         | 2.08%   |
| 5.15.98-desktop-1.mga8  | 1         | 2.08%   |
| 5.15.79-desktop-1.mga8  | 1         | 2.08%   |
| 5.15.43-desktop-1.mga8  | 1         | 2.08%   |
| 5.15.35-desktop-2.mga8  | 1         | 2.08%   |
| 5.15.117-desktop-2.mga8 | 1         | 2.08%   |
| 5.10.46-desktop-1.mga8  | 1         | 2.08%   |
| 5.10.33-desktop-1.mga8  | 1         | 2.08%   |
| 5.10.30-desktop-1.mga8  | 1         | 2.08%   |
| 5.10.27-desktop-1.mga8  | 1         | 2.08%   |
| 5.10.25-desktop-1.mga8  | 1         | 2.08%   |
| 5.10.20-desktop-2.mga7  | 1         | 2.08%   |
| 5.10.16-desktop-1.mga8  | 1         | 2.08%   |
| 5.10.16-desktop-1.mga7  | 1         | 2.08%   |
| 5.10.12-desktop-2.mga8  | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.7.19   | 7         | 14.58%  |
| 6.5.13   | 2         | 4.17%   |
| 6.4.8    | 2         | 4.17%   |
| 6.4.16   | 2         | 4.17%   |
| 5.6.14   | 2         | 4.17%   |
| 5.15.4   | 2         | 4.17%   |
| 5.15.32  | 2         | 4.17%   |
| 5.10.16  | 2         | 4.17%   |
| 6.4.9    | 1         | 2.08%   |
| 6.4.6    | 1         | 2.08%   |
| 6.4.3    | 1         | 2.08%   |
| 6.2.2    | 1         | 2.08%   |
| 6.1.45   | 1         | 2.08%   |
| 6.1.14   | 1         | 2.08%   |
| 6.0.10   | 1         | 2.08%   |
| 5.9.6    | 1         | 2.08%   |
| 5.9.16   | 1         | 2.08%   |
| 5.9.11   | 1         | 2.08%   |
| 5.8.5    | 1         | 2.08%   |
| 5.7.8    | 1         | 2.08%   |
| 5.6.6    | 1         | 2.08%   |
| 5.18.15  | 1         | 2.08%   |
| 5.16.10  | 1         | 2.08%   |
| 5.15.98  | 1         | 2.08%   |
| 5.15.79  | 1         | 2.08%   |
| 5.15.43  | 1         | 2.08%   |
| 5.15.35  | 1         | 2.08%   |
| 5.15.117 | 1         | 2.08%   |
| 5.10.46  | 1         | 2.08%   |
| 5.10.33  | 1         | 2.08%   |
| 5.10.30  | 1         | 2.08%   |
| 5.10.27  | 1         | 2.08%   |
| 5.10.25  | 1         | 2.08%   |
| 5.10.20  | 1         | 2.08%   |
| 5.10.12  | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 9         | 19.57%  |
| 5.7     | 8         | 17.39%  |
| 6.4     | 7         | 15.22%  |
| 5.10    | 7         | 15.22%  |
| 5.9     | 3         | 6.52%   |
| 5.6     | 3         | 6.52%   |
| 6.5     | 2         | 4.35%   |
| 6.1     | 2         | 4.35%   |
| 6.2     | 1         | 2.17%   |
| 6.0     | 1         | 2.17%   |
| 5.8     | 1         | 2.17%   |
| 5.18    | 1         | 2.17%   |
| 5.16    | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 41        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 23        | 53.49%  |
| KDE     | 8         | 18.6%   |
| GNOME   | 6         | 13.95%  |
| XFCE    | 4         | 9.3%    |
| MATE    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 40        | 97.56%  |
| Wayland | 1         | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 19        | 46.34%  |
| Unknown | 16        | 39.02%  |
| TDM     | 2         | 4.88%   |
| LightDM | 2         | 4.88%   |
| GDM     | 2         | 4.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 10        | 24.39%  |
| fr_FR | 6         | 14.63%  |
| en_GB | 5         | 12.2%   |
| de_DE | 3         | 7.32%   |
| it_IT | 2         | 4.88%   |
| hu_HU | 2         | 4.88%   |
| es_MX | 2         | 4.88%   |
| es_GT | 2         | 4.88%   |
| bg_BG | 2         | 4.88%   |
| ru_RU | 1         | 2.44%   |
| ro_RO | 1         | 2.44%   |
| pt_BR | 1         | 2.44%   |
| pl_PL | 1         | 2.44%   |
| es_ES | 1         | 2.44%   |
| es_CR | 1         | 2.44%   |
| en_CA | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 28        | 62.22%  |
| BIOS | 17        | 37.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 38        | 92.68%  |
| Xfs     | 1         | 2.44%   |
| Overlay | 1         | 2.44%   |
| Ext3    | 1         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 20        | 45.45%  |
| Unknown | 14        | 31.82%  |
| MBR     | 10        | 22.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 85.37%  |
| Yes       | 6         | 14.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 74.42%  |
| Yes       | 11        | 25.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 12        | 29.27%  |
| Lenovo           | 6         | 14.63%  |
| Dell             | 6         | 14.63%  |
| ASUSTek Computer | 6         | 14.63%  |
| Fujitsu          | 3         | 7.32%   |
| Notebook         | 2         | 4.88%   |
| Acer             | 2         | 4.88%   |
| Toshiba          | 1         | 2.44%   |
| Schenker         | 1         | 2.44%   |
| Medion           | 1         | 2.44%   |
| Kiano            | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 4.88%   |
| Toshiba dynabook R73/A                   | 1         | 2.44%   |
| Schenker VIA_14_SVI14E20                 | 1         | 2.44%   |
| Notebook NL40_50GU                       | 1         | 2.44%   |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 2.44%   |
| Medion DEFENDER P10                      | 1         | 2.44%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 2.44%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 2.44%   |
| Lenovo IdeaPad Slim 3 15AMN8 82XQ        | 1         | 2.44%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 2.44%   |
| Lenovo G50-30 80G0                       | 1         | 2.44%   |
| Lenovo G480 20149                        | 1         | 2.44%   |
| Kiano SlimNote 15.6                      | 1         | 2.44%   |
| HP Spectre 13 Ultrabook                  | 1         | 2.44%   |
| HP ProBook 5330m                         | 1         | 2.44%   |
| HP ProBook 450 G1                        | 1         | 2.44%   |
| HP ProBook 445 G7                        | 1         | 2.44%   |
| HP Pavilion Notebook                     | 1         | 2.44%   |
| HP Pavilion dv6                          | 1         | 2.44%   |
| HP Laptop 14-cm0xxx                      | 1         | 2.44%   |
| HP EliteBook 840 G3                      | 1         | 2.44%   |
| HP Compaq 6710b (GB887ET#ABH)            | 1         | 2.44%   |
| HP 255 15.6 inch G9 Notebook PC          | 1         | 2.44%   |
| Fujitsu S6420                            | 1         | 2.44%   |
| Fujitsu LIFEBOOK E752                    | 1         | 2.44%   |
| Fujitsu CELSIUS H720                     | 1         | 2.44%   |
| Dell Precision 5530                      | 1         | 2.44%   |
| Dell Latitude E6530                      | 1         | 2.44%   |
| Dell Latitude E5570                      | 1         | 2.44%   |
| Dell Latitude E5470                      | 1         | 2.44%   |
| Dell Latitude 7370                       | 1         | 2.44%   |
| Dell Inspiron 5480                       | 1         | 2.44%   |
| ASUS X751LN                              | 1         | 2.44%   |
| ASUS X556URK                             | 1         | 2.44%   |
| ASUS VivoBook_ASUSLaptop K6602ZC_K6602ZC | 1         | 2.44%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR     | 1         | 2.44%   |
| ASUS Q551LN                              | 1         | 2.44%   |
| ASUS K73SD                               | 1         | 2.44%   |
| Acer Aspire V3-772                       | 1         | 2.44%   |
| Acer Aspire 7741                         | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell Latitude    | 4         | 9.76%   |
| HP ProBook       | 3         | 7.32%   |
| Lenovo ThinkPad  | 2         | 4.88%   |
| Lenovo IdeaPad   | 2         | 4.88%   |
| HP Pavilion      | 2         | 4.88%   |
| ASUS VivoBook    | 2         | 4.88%   |
| Acer Aspire      | 2         | 4.88%   |
| Unknown          | 2         | 4.88%   |
| Toshiba dynabook | 1         | 2.44%   |
| Schenker VIA     | 1         | 2.44%   |
| Notebook NL40    | 1         | 2.44%   |
| Notebook NH5x    | 1         | 2.44%   |
| Medion DEFENDER  | 1         | 2.44%   |
| Lenovo G50-30    | 1         | 2.44%   |
| Lenovo G480      | 1         | 2.44%   |
| Kiano SlimNote   | 1         | 2.44%   |
| HP Spectre       | 1         | 2.44%   |
| HP Laptop        | 1         | 2.44%   |
| HP EliteBook     | 1         | 2.44%   |
| HP Compaq        | 1         | 2.44%   |
| HP 255           | 1         | 2.44%   |
| Fujitsu S6420    | 1         | 2.44%   |
| Fujitsu LIFEBOOK | 1         | 2.44%   |
| Fujitsu CELSIUS  | 1         | 2.44%   |
| Dell Precision   | 1         | 2.44%   |
| Dell Inspiron    | 1         | 2.44%   |
| ASUS X751LN      | 1         | 2.44%   |
| ASUS X556URK     | 1         | 2.44%   |
| ASUS Q551LN      | 1         | 2.44%   |
| ASUS K73SD       | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 5         | 12.2%   |
| 2012 | 5         | 12.2%   |
| 2018 | 4         | 9.76%   |
| 2020 | 3         | 7.32%   |
| 2019 | 3         | 7.32%   |
| 2017 | 3         | 7.32%   |
| 2014 | 3         | 7.32%   |
| 2013 | 3         | 7.32%   |
| 2007 | 3         | 7.32%   |
| 2022 | 2         | 4.88%   |
| 2011 | 2         | 4.88%   |
| 2008 | 2         | 4.88%   |
| 2023 | 1         | 2.44%   |
| 2021 | 1         | 2.44%   |
| 2010 | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 41        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 41        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 38.1%   |
| 3.01-4.0   | 8         | 19.05%  |
| 8.01-16.0  | 8         | 19.05%  |
| 16.01-24.0 | 5         | 11.9%   |
| 32.01-64.0 | 3         | 7.14%   |
| 2.01-3.0   | 1         | 2.38%   |
| 1.01-2.0   | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 18        | 40%     |
| 1.01-2.0 | 12        | 26.67%  |
| 4.01-8.0 | 10        | 22.22%  |
| 3.01-4.0 | 5         | 11.11%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 79.07%  |
| 2      | 8         | 18.6%   |
| 3      | 1         | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 58.54%  |
| Yes       | 17        | 41.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 80.49%  |
| No        | 8         | 19.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 97.56%  |
| No        | 1         | 2.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 78.05%  |
| No        | 9         | 21.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| France          | 6         | 14.63%  |
| UK              | 4         | 9.76%   |
| USA             | 3         | 7.32%   |
| Netherlands     | 3         | 7.32%   |
| Italy           | 3         | 7.32%   |
| Germany         | 3         | 7.32%   |
| Romania         | 2         | 4.88%   |
| Mexico          | 2         | 4.88%   |
| Guatemala       | 2         | 4.88%   |
| Bulgaria        | 2         | 4.88%   |
| The Netherlands | 1         | 2.44%   |
| Russia          | 1         | 2.44%   |
| Poland          | 1         | 2.44%   |
| Indonesia       | 1         | 2.44%   |
| Hungary         | 1         | 2.44%   |
| Greece          | 1         | 2.44%   |
| Costa Rica      | 1         | 2.44%   |
| Colombia        | 1         | 2.44%   |
| Canada          | 1         | 2.44%   |
| Brazil          | 1         | 2.44%   |
| Australia       | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Guatemala City        | 2         | 4.35%   |
| Delft                 | 2         | 4.35%   |
| Wiwersheim            | 1         | 2.17%   |
| Tver                  | 1         | 2.17%   |
| Tours                 | 1         | 2.17%   |
| Toulouse              | 1         | 2.17%   |
| The Hague             | 1         | 2.17%   |
| Surabaya              | 1         | 2.17%   |
| Strasbourg            | 1         | 2.17%   |
| Sofia                 | 1         | 2.17%   |
| Sao Paulo             | 1         | 2.17%   |
| Sant'Angelo Lodigiano | 1         | 2.17%   |
| San Antonio           | 1         | 2.17%   |
| Rommerskirchen        | 1         | 2.17%   |
| Rome                  | 1         | 2.17%   |
| Quaregna              | 1         | 2.17%   |
| Poznan                | 1         | 2.17%   |
| Paris                 | 1         | 2.17%   |
| Oxford                | 1         | 2.17%   |
| Ottawa                | 1         | 2.17%   |
| Odenville             | 1         | 2.17%   |
| Nordenham             | 1         | 2.17%   |
| Miercurea-Ciuc        | 1         | 2.17%   |
| Melbourne             | 1         | 2.17%   |
| Marino                | 1         | 2.17%   |
| March                 | 1         | 2.17%   |
| Luce                  | 1         | 2.17%   |
| León                 | 1         | 2.17%   |
| Le Faouet             | 1         | 2.17%   |
| Iztapalapa            | 1         | 2.17%   |
| Győr                 | 1         | 2.17%   |
| Guapiles              | 1         | 2.17%   |
| Giannitsa             | 1         | 2.17%   |
| Eaubonne              | 1         | 2.17%   |
| Dundee                | 1         | 2.17%   |
| Denver                | 1         | 2.17%   |
| Chemnitz              | 1         | 2.17%   |
| Burgas                | 1         | 2.17%   |
| Bucharest             | 1         | 2.17%   |
| Bradford              | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 6         | 9      | 12%     |
| WDC                     | 5         | 7      | 10%     |
| Toshiba                 | 5         | 6      | 10%     |
| Seagate                 | 5         | 5      | 10%     |
| Unknown                 | 4         | 4      | 8%      |
| Kingston                | 4         | 5      | 8%      |
| Hitachi                 | 4         | 4      | 8%      |
| SK hynix                | 2         | 3      | 4%      |
| Intel                   | 2         | 2      | 4%      |
| Crucial                 | 2         | 2      | 4%      |
| Union Memory (Shenzhen) | 1         | 1      | 2%      |
| SanDisk                 | 1         | 1      | 2%      |
| Phison                  | 1         | 1      | 2%      |
| LDLC                    | 1         | 1      | 2%      |
| KingFast                | 1         | 2      | 2%      |
| JMicron Technology      | 1         | 1      | 2%      |
| HGST                    | 1         | 5      | 2%      |
| GOODRAM                 | 1         | 1      | 2%      |
| Fujitsu                 | 1         | 1      | 2%      |
| China                   | 1         | 1      | 2%      |
| A-DATA Technology       | 1         | 1      | 2%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                     | 2         | 3.7%    |
| Samsung SSD 860 EVO 500GB                    | 2         | 3.7%    |
| Crucial CT120BX500SSD1 120GB                 | 2         | 3.7%    |
| WDC WDS500G2B0C-00PXH0 500GB                 | 1         | 1.85%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1.85%   |
| WDC WDS100T2B0A 1TB SSD                      | 1         | 1.85%   |
| WDC WD5000LPLX-66ZNTT1 500GB                 | 1         | 1.85%   |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 1.85%   |
| Unknown MMC Card  8GB                        | 1         | 1.85%   |
| Unknown MMC Card  7GB                        | 1         | 1.85%   |
| Unknown MMC Card  32GB                       | 1         | 1.85%   |
| Unknown MMC Card  16GB                       | 1         | 1.85%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.85%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.85%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1.85%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1.85%   |
| SK hynix SKHynix_HFS256GEJ4X112N 256GB       | 1         | 1.85%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB    | 1         | 1.85%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 1.85%   |
| Seagate ST96812AS 64GB                       | 1         | 1.85%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1.85%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1.85%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.85%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD          | 1         | 1.85%   |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 1.85%   |
| Samsung SSD 870 QVO 1TB                      | 1         | 1.85%   |
| Samsung SSD 850 EVO 500GB                    | 1         | 1.85%   |
| Samsung NVMe SSD Drive 500GB                 | 1         | 1.85%   |
| Samsung MZVLQ256HBJD-00BH1 256GB             | 1         | 1.85%   |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 1.85%   |
| Phison E12S-1TB-PHISON-SSD-B27B              | 1         | 1.85%   |
| LDLC F6+M.2 480 480GB                        | 1         | 1.85%   |
| Kingston SNVS1000G 1TB                       | 1         | 1.85%   |
| Kingston SA400S37480G 480GB SSD              | 1         | 1.85%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1.85%   |
| Kingston SA2000M8500G 500GB                  | 1         | 1.85%   |
| Kingston NVMe SSD Drive 1TB                  | 1         | 1.85%   |
| KingFast SSD 256GB                           | 1         | 1.85%   |
| JMicron Generic 8GB                          | 1         | 1.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 5         | 5      | 27.78%  |
| Toshiba            | 4         | 5      | 22.22%  |
| Hitachi            | 4         | 4      | 22.22%  |
| WDC                | 2         | 4      | 11.11%  |
| JMicron Technology | 1         | 1      | 5.56%   |
| HGST               | 1         | 5      | 5.56%   |
| Fujitsu            | 1         | 1      | 5.56%   |

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
| Intel               | 1         | 1      | 5.88%   |
| GOODRAM             | 1         | 1      | 5.88%   |
| China               | 1         | 1      | 5.88%   |
| A-DATA Technology   | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 25     | 35.29%  |
| SSD  | 17        | 19     | 33.33%  |
| NVMe | 12        | 15     | 23.53%  |
| MMC  | 4         | 4      | 7.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 43     | 65.31%  |
| NVMe | 12        | 15     | 24.49%  |
| MMC  | 4         | 4      | 8.16%   |
| SAS  | 1         | 1      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 29     | 75.76%  |
| 0.51-1.0   | 8         | 15     | 24.24%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 16        | 39.02%  |
| 501-1000   | 11        | 26.83%  |
| 101-250    | 9         | 21.95%  |
| 51-100     | 2         | 4.88%   |
| 21-50      | 1         | 2.44%   |
| 1001-2000  | 1         | 2.44%   |
| Unknown    | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 11        | 25%     |
| 1-20      | 11        | 25%     |
| 101-250   | 8         | 18.18%  |
| 51-100    | 8         | 18.18%  |
| 501-1000  | 3         | 6.82%   |
| 251-500   | 1         | 2.27%   |
| 1001-2000 | 1         | 2.27%   |
| Unknown   | 1         | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 16.67%  |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 16.67%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |
| Hitachi HTS725050A9A364 500GB      | 1         | 1      | 16.67%  |
| Hitachi HTS542525K9A300 250GB      | 1         | 1      | 16.67%  |
| Fujitsu MHZ2160BH G2 160GB         | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 33.33%  |
| Hitachi | 2         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |
| Fujitsu | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 33.33%  |
| Hitachi | 2         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |
| Fujitsu | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 100%    |

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
| Works    | 25        | 29     | 53.19%  |
| Detected | 16        | 28     | 34.04%  |
| Malfunc  | 6         | 6      | 12.77%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 31        | 67.39%  |
| AMD                          | 5         | 10.87%  |
| Samsung Electronics          | 3         | 6.52%   |
| SK hynix                     | 2         | 4.35%   |
| Kingston Technology Company  | 2         | 4.35%   |
| Toshiba America Info Systems | 1         | 2.17%   |
| SanDisk                      | 1         | 2.17%   |
| Phison Electronics           | 1         | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 9.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 7.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 5.88%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 3.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.92%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 2         | 3.92%   |
| AMD SB600 IDE                                                                  | 2         | 3.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.96%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 1.96%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.96%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.96%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.96%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 1         | 1.96%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.96%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 1.96%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.96%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.96%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 31        | 62%     |
| NVMe | 11        | 22%     |
| IDE  | 5         | 10%     |
| RAID | 3         | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 80.49%  |
| AMD    | 8         | 19.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 7.32%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 2         | 4.88%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 4.88%   |
| AMD Turion 64 X2 Mobile Technology TL-60        | 2         | 4.88%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 1         | 2.44%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 2.44%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz                | 1         | 2.44%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 2.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.44%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 2.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 2.44%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 2.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 2.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 2.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 2.44%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz              | 1         | 2.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 2.44%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 1         | 2.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.44%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 2.44%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 2.44%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 1         | 2.44%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 1         | 2.44%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz            | 1         | 2.44%   |
| Intel Celeron CPU N2820 @ 2.13GHz               | 1         | 2.44%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 1         | 2.44%   |
| Intel 12th Gen Core i5-12450H                   | 1         | 2.44%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 1         | 2.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 2.44%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 2.44%   |
| AMD Ryzen 3 7320U with Radeon Graphics          | 1         | 2.44%   |
| AMD Ryzen 3 5425U with Radeon Graphics          | 1         | 2.44%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G    | 1         | 2.44%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 11        | 26.83%  |
| Intel Core i5           | 11        | 26.83%  |
| Other                   | 2         | 4.88%   |
| Intel Core i3           | 2         | 4.88%   |
| Intel Core 2 Duo        | 2         | 4.88%   |
| AMD Turion 64 X2 Mobile | 2         | 4.88%   |
| AMD Ryzen 7             | 2         | 4.88%   |
| AMD Ryzen 3             | 2         | 4.88%   |
| Intel Pentium Silver    | 1         | 2.44%   |
| Intel Pentium           | 1         | 2.44%   |
| Intel Core m5           | 1         | 2.44%   |
| Intel Celeron           | 1         | 2.44%   |
| Intel Atom              | 1         | 2.44%   |
| AMD A6                  | 1         | 2.44%   |
| AMD A10                 | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 63.41%  |
| 4      | 10        | 24.39%  |
| 8      | 3         | 7.32%   |
| 6      | 2         | 4.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 73.17%  |
| 1      | 11        | 26.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 41        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 34.88%  |
| 0x306a9    | 4         | 9.3%    |
| 0x806e9    | 3         | 6.98%   |
| 0x406e3    | 3         | 6.98%   |
| 0x40651    | 2         | 4.65%   |
| 0x306c3    | 2         | 4.65%   |
| 0x206a7    | 2         | 4.65%   |
| 0xa0652    | 1         | 2.33%   |
| 0x906ea    | 1         | 2.33%   |
| 0x806ec    | 1         | 2.33%   |
| 0x806eb    | 1         | 2.33%   |
| 0x706a1    | 1         | 2.33%   |
| 0x506e3    | 1         | 2.33%   |
| 0x406c4    | 1         | 2.33%   |
| 0x20655    | 1         | 2.33%   |
| 0x0a50000d | 1         | 2.33%   |
| 0x08a00008 | 1         | 2.33%   |
| 0x08600106 | 1         | 2.33%   |
| 0x08108109 | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 6         | 14.63%  |
| Skylake          | 5         | 12.2%   |
| IvyBridge        | 5         | 12.2%   |
| Haswell          | 5         | 12.2%   |
| SandyBridge      | 3         | 7.32%   |
| Silvermont       | 2         | 4.88%   |
| K8 Hammer        | 2         | 4.88%   |
| Excavator        | 2         | 4.88%   |
| Unknown          | 2         | 4.88%   |
| Zen+             | 1         | 2.44%   |
| Zen 3            | 1         | 2.44%   |
| Zen 2            | 1         | 2.44%   |
| Westmere         | 1         | 2.44%   |
| Penryn           | 1         | 2.44%   |
| Goldmont plus    | 1         | 2.44%   |
| Core             | 1         | 2.44%   |
| CometLake        | 1         | 2.44%   |
| Alderlake Hybrid | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 60%     |
| Nvidia | 12        | 21.82%  |
| AMD    | 10        | 18.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 8.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 5.26%   |
| Intel HD Graphics 620                                                                    | 3         | 5.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 5.26%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 3.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.51%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 2         | 3.51%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.75%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 1.75%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.75%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.75%   |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 1.75%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1.75%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.75%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.75%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.75%   |
| Intel HD Graphics 530                                                                    | 1         | 1.75%   |
| Intel HD Graphics 515                                                                    | 1         | 1.75%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.75%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 1         | 1.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.75%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.75%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 1         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.75%   |
| AMD Mendocino                                                                            | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 41.46%  |
| Intel + Nvidia | 12        | 29.27%  |
| 1 x AMD        | 7         | 17.07%  |
| 2 x Intel      | 2         | 4.88%   |
| Intel + AMD    | 2         | 4.88%   |
| 2 x AMD        | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 41        | 97.62%  |
| Proprietary | 1         | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 59.09%  |
| 1.01-2.0   | 8         | 18.18%  |
| 0.01-0.5   | 4         | 9.09%   |
| 0.51-1.0   | 3         | 6.82%   |
| 3.01-4.0   | 2         | 4.55%   |
| 5.01-6.0   | 1         | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 20.45%  |
| LG Display              | 8         | 18.18%  |
| Chimei Innolux          | 7         | 15.91%  |
| BOE                     | 7         | 15.91%  |
| Samsung Electronics     | 5         | 11.36%  |
| Sharp                   | 2         | 4.55%   |
| Chi Mei Optoelectronics | 2         | 4.55%   |
| Lenovo                  | 1         | 2.27%   |
| Eizo                    | 1         | 2.27%   |
| Ancor Communications    | 1         | 2.27%   |
| Acer                    | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch             | 2         | 4.44%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 2.22%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch                   | 1         | 2.22%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch        | 1         | 2.22%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch        | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch     | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 1         | 2.22%   |
| LG Display LCD Monitor LGD066A 1920x1080 344x194mm 15.5-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch               | 1         | 2.22%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD0457 1920x1080 345x194mm 15.6-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 2.22%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 1         | 2.22%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 1         | 2.22%   |
| LG Display LCD Monitor LGD0215 1920x1080 345x194mm 15.6-inch              | 1         | 2.22%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 1         | 2.22%   |
| Eizo CS270 ENC2694 1920x1080 597x336mm 27.0-inch                          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1364 1366x768 293x164mm 13.2-inch           | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch          | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 2.22%   |
| BOE LCD Monitor BOE0B2B 1920x1200 345x215mm 16.0-inch                     | 1         | 2.22%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 2.22%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 1         | 2.22%   |
| BOE LCD Monitor BOE0806 1920x1080 309x173mm 13.9-inch                     | 1         | 2.22%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                     | 1         | 2.22%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 1         | 2.22%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch            | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO429D 1920x1080 382x215mm 17.3-inch            | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO369F 1920x1080 344x194mm 15.5-inch            | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 1         | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 48.84%  |
| 1366x768 (WXGA)    | 10        | 23.26%  |
| 1600x900 (HD+)     | 4         | 9.3%    |
| 1280x800 (WXGA)    | 3         | 6.98%   |
| 1920x1200 (WUXGA)  | 2         | 4.65%   |
| 3840x2160 (4K)     | 1         | 2.33%   |
| 3200x1800 (QHD+)   | 1         | 2.33%   |
| 1680x1050 (WSXGA+) | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 20        | 45.45%  |
| 13     | 8         | 18.18%  |
| 17     | 7         | 15.91%  |
| 14     | 4         | 9.09%   |
| 24     | 2         | 4.55%   |
| 27     | 1         | 2.27%   |
| 22     | 1         | 2.27%   |
| 16     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 68.18%  |
| 351-400     | 7         | 15.91%  |
| 501-600     | 3         | 6.82%   |
| 201-300     | 3         | 6.82%   |
| 401-500     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 85.37%  |
| 16/10 | 6         | 14.63%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 45.45%  |
| 81-90          | 9         | 20.45%  |
| 121-130        | 6         | 13.64%  |
| 71-80          | 3         | 6.82%   |
| 201-250        | 3         | 6.82%   |
| 301-350        | 1         | 2.27%   |
| 131-140        | 1         | 2.27%   |
| 111-120        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 46.51%  |
| 101-120       | 14        | 32.56%  |
| 51-100        | 7         | 16.28%  |
| More than 240 | 1         | 2.33%   |
| 161-240       | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 90.24%  |
| 2     | 4         | 9.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 23        | 36.51%  |
| Realtek Semiconductor    | 17        | 26.98%  |
| Qualcomm Atheros         | 7         | 11.11%  |
| Broadcom                 | 6         | 9.52%   |
| Broadcom Limited         | 3         | 4.76%   |
| Sierra Wireless          | 2         | 3.17%   |
| MediaTek                 | 2         | 3.17%   |
| Marvell Technology Group | 1         | 1.59%   |
| Dell                     | 1         | 1.59%   |
| ASIX Electronics         | 1         | 1.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 15.58%  |
| Intel Wireless 8260                                                    | 4         | 5.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 5.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 5.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 3.9%    |
| Intel Wi-Fi 6 AX200                                                    | 3         | 3.9%    |
| Sierra Wireless MC8305 Modem                                           | 2         | 2.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 2.6%    |
| Intel Wireless 7260                                                    | 2         | 2.6%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 2.6%    |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.6%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 2         | 2.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 2.6%    |
| Broadcom BCM4311 802.11a/b/g                                           | 2         | 2.6%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 1.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1         | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 1.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 1.3%    |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                    | 1         | 1.3%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.3%    |
| Intel Wireless 8265 / 8275                                             | 1         | 1.3%    |
| Intel Wireless 3165                                                    | 1         | 1.3%    |
| Intel Ultimate N WiFi Link 5300                                        | 1         | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 1         | 1.3%    |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1         | 1.3%    |
| Intel Ethernet Connection I219-V                                       | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 1         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 1         | 1.3%    |
| Intel 82579V Gigabit Network Connection                                | 1         | 1.3%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                   | 1         | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 50%     |
| Qualcomm Atheros      | 7         | 15.91%  |
| Realtek Semiconductor | 5         | 11.36%  |
| Broadcom              | 5         | 11.36%  |
| Sierra Wireless       | 2         | 4.55%   |
| MediaTek              | 2         | 4.55%   |
| Dell                  | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 9.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 9.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 6.82%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 6.82%   |
| Sierra Wireless MC8305 Modem                                   | 2         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 4.55%   |
| Intel Wireless 7260                                            | 2         | 4.55%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 4.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 4.55%   |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 4.55%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 2.27%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 2.27%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.27%   |
| Intel Wireless 3165                                            | 1         | 2.27%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 2.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.27%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 2.27%   |
| Broadcom BCM4323 802.11abgn Wireless Adapter                   | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 15        | 45.45%  |
| Intel                    | 10        | 30.3%   |
| Broadcom Limited         | 3         | 9.09%   |
| Qualcomm Atheros         | 2         | 6.06%   |
| Marvell Technology Group | 1         | 3.03%   |
| Broadcom                 | 1         | 3.03%   |
| ASIX Electronics         | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 36.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 12.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 6.06%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 6.06%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 2         | 6.06%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 3.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 3.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 3.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 3.03%   |
| Intel Ethernet Connection I219-V                                       | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 3.03%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 3.03%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 3.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 3.03%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 1         | 3.03%   |
| ASIX AX88772B                                                          | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 54.79%  |
| Ethernet | 33        | 45.21%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 81.82%  |
| Ethernet | 8         | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 31        | 75.61%  |
| 1     | 9         | 21.95%  |
| 0     | 1         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 76.19%  |
| Yes  | 10        | 23.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 13        | 39.39%  |
| Realtek Semiconductor   | 5         | 15.15%  |
| IMC Networks            | 4         | 12.12%  |
| Hewlett-Packard         | 3         | 9.09%   |
| Foxconn / Hon Hai       | 2         | 6.06%   |
| Taiyo Yuden             | 1         | 3.03%   |
| MediaTek                | 1         | 3.03%   |
| Lite-On Technology      | 1         | 3.03%   |
| Dell                    | 1         | 3.03%   |
| Cambridge Silicon Radio | 1         | 3.03%   |
| Broadcom                | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 15.15%  |
| Realtek Bluetooth Radio                             | 3         | 9.09%   |
| Intel AX200 Bluetooth                               | 3         | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 6.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.06%   |
| IMC Networks Bluetooth Device                       | 2         | 6.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 6.06%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 6.06%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 3.03%   |
| Realtek RTL8723B Bluetooth                          | 1         | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.03%   |
| MediaTek MT7630e Bluetooth Adapter                  | 1         | 3.03%   |
| Lite-On Bluetooth Device                            | 1         | 3.03%   |
| Intel AX201 Bluetooth                               | 1         | 3.03%   |
| IMC Networks Wireless_Device                        | 1         | 3.03%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.03%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.03%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 69.57%  |
| AMD                 | 8         | 17.39%  |
| Nvidia              | 5         | 10.87%  |
| C-Media Electronics | 1         | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 12.5%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 8.93%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 7.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 5.36%   |
| Nvidia Audio device                                                        | 2         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 3.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 3.57%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.79%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.79%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.79%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.79%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.79%   |
| AMD High Definition Audio Controller                                       | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 35%     |
| SK hynix            | 9         | 22.5%   |
| Kingston            | 5         | 12.5%   |
| Unknown             | 4         | 10%     |
| Micron Technology   | 3         | 7.5%    |
| Corsair             | 2         | 5%      |
| Unknown (ABCD)      | 1         | 2.5%    |
| Smart               | 1         | 2.5%    |
| Crucial             | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 7.14%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 4.76%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s               | 2         | 4.76%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                       | 1         | 2.38%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                         | 1         | 2.38%   |
| Unknown RAM Module 2GB SODIMM 533MT/s                               | 1         | 2.38%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                       | 1         | 2.38%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 2.38%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s               | 1         | 2.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 2.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                        | 1         | 2.38%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 1639MT/s              | 1         | 2.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.38%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 2.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 2.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 2.38%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 2.38%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 1         | 2.38%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 2.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 2.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.38%   |
| Samsung RAM M471B5173BH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 2.38%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 2.38%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 2.38%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 2.38%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s        | 1         | 2.38%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4096MB SODIMM DDR3 1600MT/s           | 1         | 2.38%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 1         | 2.38%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s               | 1         | 2.38%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s           | 1         | 2.38%   |
| Kingston RAM KFYHV1-HYC 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.38%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s                   | 1         | 2.38%   |
| Kingston RAM ACR16D3LS1KBG/8G 8GB SODIMM DDR3 1600MT/s              | 1         | 2.38%   |
| Kingston RAM 99U5428-042.A00G 4096MB SODIMM DDR3 4199MT/s           | 1         | 2.38%   |
| Kingston RAM 9905428-102.A00G 4GB SODIMM DDR3 1600MT/s              | 1         | 2.38%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s          | 1         | 2.38%   |
| Corsair RAM CMSX16GX4M1A2666C18 16GB SODIMM DDR4 2667MT/s           | 1         | 2.38%   |
| Corsair RAM CM4X8GF2666C18S2 8GB SODIMM DDR4 3000MT/s               | 1         | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 13        | 39.39%  |
| DDR4    | 12        | 36.36%  |
| SDRAM   | 2         | 6.06%   |
| DDR2    | 2         | 6.06%   |
| LPDDR5  | 1         | 3.03%   |
| LPDDR4  | 1         | 3.03%   |
| LPDDR3  | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 96.77%  |
| Row Of Chips | 1         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 16        | 47.06%  |
| 8192  | 11        | 32.35%  |
| 2048  | 4         | 11.76%  |
| 16384 | 2         | 5.88%   |
| 1024  | 1         | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 11        | 30.56%  |
| 2667  | 4         | 11.11%  |
| 2400  | 4         | 11.11%  |
| 3200  | 3         | 8.33%   |
| 2133  | 2         | 5.56%   |
| 1334  | 2         | 5.56%   |
| 667   | 2         | 5.56%   |
| 6400  | 1         | 2.78%   |
| 4199  | 1         | 2.78%   |
| 3266  | 1         | 2.78%   |
| 3000  | 1         | 2.78%   |
| 1639  | 1         | 2.78%   |
| 1066  | 1         | 2.78%   |
| 975   | 1         | 2.78%   |
| 533   | 1         | 2.78%   |

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
| Chicony Electronics                    | 13        | 34.21%  |
| Realtek Semiconductor                  | 4         | 10.53%  |
| IMC Networks                           | 3         | 7.89%   |
| Microdia                               | 2         | 5.26%   |
| Luxvisions Innotech Limited            | 2         | 5.26%   |
| Lite-On Technology                     | 2         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.26%   |
| Bison Electronics                      | 2         | 5.26%   |
| Alcor Micro                            | 2         | 5.26%   |
| Suyin                                  | 1         | 2.63%   |
| Sunplus Innovation Technology          | 1         | 2.63%   |
| Sonix Technology                       | 1         | 2.63%   |
| Primax Electronics                     | 1         | 2.63%   |
| Logitech                               | 1         | 2.63%   |
| Apple                                  | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 3         | 7.69%   |
| Chicony USB2.0 Camera                                                      | 3         | 7.69%   |
| Chicony Integrated Camera                                                  | 3         | 7.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 5.13%   |
| Chicony FJ Camera                                                          | 2         | 5.13%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.56%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 2.56%   |
| Sonix USB2.0 FHD UVC WebCam                                                | 1         | 2.56%   |
| Realtek USB Camera                                                         | 1         | 2.56%   |
| Primax HP Truevision FHD                                                   | 1         | 2.56%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.56%   |
| Microdia Integrated Webcam                                                 | 1         | 2.56%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 2.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2.56%   |
| Logitech Fujitsu Webcam                                                    | 1         | 2.56%   |
| Lite-On HP Webcam                                                          | 1         | 2.56%   |
| Lite-On HP HD Webcam                                                       | 1         | 2.56%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 2.56%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 2.56%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 2.56%   |
| Chicony Integrated IR Camera                                               | 1         | 2.56%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 2.56%   |
| Chicony HD WebCam                                                          | 1         | 2.56%   |
| Chicony 1.3M HD WebCam                                                     | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 2.56%   |
| Bison Lenovo EasyCamera                                                    | 1         | 2.56%   |
| Bison BisonCam,NB Pro                                                      | 1         | 2.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 1         | 2.56%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 2.56%   |
| Alcor Micro Asus Integrated Webcam                                         | 1         | 2.56%   |

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
| 0     | 20        | 45.45%  |
| 1     | 17        | 38.64%  |
| 2     | 4         | 9.09%   |
| 3     | 3         | 6.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 35.48%  |
| Graphics card         | 10        | 32.26%  |
| Chipcard              | 5         | 16.13%  |
| Storage               | 1         | 3.23%   |
| Net/wireless          | 1         | 3.23%   |
| Multimedia controller | 1         | 3.23%   |
| Camera                | 1         | 3.23%   |
| Bluetooth             | 1         | 3.23%   |

