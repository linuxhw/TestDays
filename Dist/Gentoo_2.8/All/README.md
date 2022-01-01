Gentoo 2.8 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo_2.8/Desktop/README.md) and [notebooks](/Dist/Gentoo_2.8/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Raspberry ... | Raspberry Pi                | Soc         | [eba53a3d91](https://linux-hardware.org/?probe=eba53a3d91) | Dec 30, 2021 |
| TYAN Compu... | S7025                       | Server      | [4a4fe05b48](https://linux-hardware.org/?probe=4a4fe05b48) | Dec 27, 2021 |
| EVGA          | Z390 DARK                   | Desktop     | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Intel         | S1200RP G62251-406          | Server      | [986c6d1f51](https://linux-hardware.org/?probe=986c6d1f51) | Dec 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [429df0480e](https://linux-hardware.org/?probe=429df0480e) | Dec 23, 2021 |
| Framework     | Laptop                      | Notebook    | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| TYAN Compu... | S7025                       | Server      | [88ee246f4e](https://linux-hardware.org/?probe=88ee246f4e) | Dec 21, 2021 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [36ad5ef96a](https://linux-hardware.org/?probe=36ad5ef96a) | Dec 16, 2021 |
| BESSTAR Te... | ATB15                       | Server      | [783d1d7b6f](https://linux-hardware.org/?probe=783d1d7b6f) | Dec 16, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [0ec288fb32](https://linux-hardware.org/?probe=0ec288fb32) | Dec 16, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d1c651b135](https://linux-hardware.org/?probe=d1c651b135) | Dec 09, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [41b1b4ce39](https://linux-hardware.org/?probe=41b1b4ce39) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [40748c60b0](https://linux-hardware.org/?probe=40748c60b0) | Nov 18, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | Notebook    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3aeb2b6565](https://linux-hardware.org/?probe=3aeb2b6565) | Nov 11, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ced6e2a8c2](https://linux-hardware.org/?probe=ced6e2a8c2) | Nov 04, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1a6eea194f](https://linux-hardware.org/?probe=1a6eea194f) | Oct 28, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cb6d9e548b](https://linux-hardware.org/?probe=cb6d9e548b) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5b06944051](https://linux-hardware.org/?probe=5b06944051) | Oct 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [5d0fc3aa0e](https://linux-hardware.org/?probe=5d0fc3aa0e) | Oct 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [243e5becca](https://linux-hardware.org/?probe=243e5becca) | Oct 14, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [95cd0c0751](https://linux-hardware.org/?probe=95cd0c0751) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.9-gentoo-x86_64         | 3         | 7.14%   |
| 5.15.6-gentoo                | 2         | 4.76%   |
| 5.15.10-gentoo-x86_64        | 2         | 4.76%   |
| 5.15.10-gentoo               | 2         | 4.76%   |
| 5.15.1-gentoo-x86_64         | 2         | 4.76%   |
| 5.14.14-gentoo-x86_64        | 2         | 4.76%   |
| 5.14.14-gentoo-dist          | 2         | 4.76%   |
| 5.14.12-gentoo               | 2         | 4.76%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1         | 2.38%   |
| 5.15.7-gentoo                | 1         | 2.38%   |
| 5.15.5-gentoo-x86_64         | 1         | 2.38%   |
| 5.15.5-gentoo-dist           | 1         | 2.38%   |
| 5.15.5-gentoo                | 1         | 2.38%   |
| 5.15.4-gentoo.8i7HVK         | 1         | 2.38%   |
| 5.15.4-gentoo-deimos         | 1         | 2.38%   |
| 5.15.3-gentoo.4650G          | 1         | 2.38%   |
| 5.15.2-gentoo20210917        | 1         | 2.38%   |
| 5.15.2-gentoo-x86_64         | 1         | 2.38%   |
| 5.15.0-gentoo-x86_64         | 1         | 2.38%   |
| 5.15.0-gentoo                | 1         | 2.38%   |
| 5.14.9-gentoo                | 1         | 2.38%   |
| 5.14.7-gentoo-x86_64         | 1         | 2.38%   |
| 5.14.6                       | 1         | 2.38%   |
| 5.14.15-gentoo20210917       | 1         | 2.38%   |
| 5.14.14-gentoo               | 1         | 2.38%   |
| 5.14.13-gentoo               | 1         | 2.38%   |
| 5.14.11-zen1                 | 1         | 2.38%   |
| 5.10.84-gentoo-112-overlayfs | 1         | 2.38%   |
| 5.10.83-gentoo-dist          | 1         | 2.38%   |
| 5.10.76-gentoo-r1            | 1         | 2.38%   |
| 5.10.74-gentoo-x86_64        | 1         | 2.38%   |
| 5.10.70-1-lts                | 1         | 2.38%   |
| 5.10.11-v8                   | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.14 | 5         | 11.9%   |
| 5.15.10 | 4         | 9.52%   |
| 5.14.9  | 4         | 9.52%   |
| 5.15.5  | 3         | 7.14%   |
| 5.15.6  | 2         | 4.76%   |
| 5.15.4  | 2         | 4.76%   |
| 5.15.2  | 2         | 4.76%   |
| 5.15.1  | 2         | 4.76%   |
| 5.15.0  | 2         | 4.76%   |
| 5.14.12 | 2         | 4.76%   |
| 6.0.0   | 1         | 2.38%   |
| 5.15.7  | 1         | 2.38%   |
| 5.15.3  | 1         | 2.38%   |
| 5.14.7  | 1         | 2.38%   |
| 5.14.6  | 1         | 2.38%   |
| 5.14.15 | 1         | 2.38%   |
| 5.14.13 | 1         | 2.38%   |
| 5.14.11 | 1         | 2.38%   |
| 5.10.84 | 1         | 2.38%   |
| 5.10.83 | 1         | 2.38%   |
| 5.10.76 | 1         | 2.38%   |
| 5.10.74 | 1         | 2.38%   |
| 5.10.70 | 1         | 2.38%   |
| 5.10.11 | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 19        | 45.24%  |
| 5.14    | 16        | 38.1%   |
| 5.10    | 6         | 14.29%  |
| 6.0     | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 40        | 97.56%  |
| aarch64 | 1         | 2.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 17        | 41.46%  |
| Unknown       | 12        | 29.27%  |
| GNOME         | 5         | 12.2%   |
| XFCE          | 3         | 7.32%   |
| Enlightenment | 2         | 4.88%   |
| DWM           | 1         | 2.44%   |
| Cinnamon      | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 20        | 47.62%  |
| Wayland | 10        | 23.81%  |
| Tty     | 7         | 16.67%  |
| Unknown | 5         | 11.9%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 45.24%  |
| SDDM    | 16        | 38.1%   |
| LightDM | 4         | 9.52%   |
| GDM     | 3         | 7.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 14        | 34.15%  |
| en_GB      | 6         | 14.63%  |
| ru_RU      | 3         | 7.32%   |
| pl_PL      | 2         | 4.88%   |
| de_DE      | 2         | 4.88%   |
| C.UTF8     | 2         | 4.88%   |
| C          | 2         | 4.88%   |
| tr_TR      | 1         | 2.44%   |
| sl_SI      | 1         | 2.44%   |
| pt_BR      | 1         | 2.44%   |
| it_IT      | 1         | 2.44%   |
| es_ES      | 1         | 2.44%   |
| en_US.UTF8 | 1         | 2.44%   |
| en_NZ      | 1         | 2.44%   |
| el_GR      | 1         | 2.44%   |
| de_CH      | 1         | 2.44%   |
| Unknown    | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 32        | 74.42%  |
| BIOS | 11        | 25.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 19        | 46.34%  |
| Btrfs | 18        | 43.9%   |
| F2fs  | 2         | 4.88%   |
| Zfs   | 1         | 2.44%   |
| Xtrfs | 1         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 36        | 85.71%  |
| Unknown | 4         | 9.52%   |
| MBR     | 2         | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 70.73%  |
| Yes       | 12        | 29.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 73.17%  |
| Yes       | 11        | 26.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 10        | 24.39%  |
| Lenovo                  | 7         | 17.07%  |
| Intel                   | 3         | 7.32%   |
| Dell                    | 3         | 7.32%   |
| ASRock                  | 3         | 7.32%   |
| MSI                     | 2         | 4.88%   |
| Hewlett-Packard         | 2         | 4.88%   |
| Gigabyte Technology     | 2         | 4.88%   |
| Acer                    | 2         | 4.88%   |
| TYAN Computer           | 1         | 2.44%   |
| Toshiba                 | 1         | 2.44%   |
| Timi                    | 1         | 2.44%   |
| Raspberry Pi Foundation | 1         | 2.44%   |
| Framework               | 1         | 2.44%   |
| EVGA                    | 1         | 2.44%   |
| BESSTAR Tech            | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel S1200RP                        | 2         | 4.88%   |
| HP Laptop 15s-eq0xxx                 | 2         | 4.88%   |
| TYAN S7025                           | 1         | 2.44%   |
| Toshiba Satellite C850D-118          | 1         | 2.44%   |
| Timi Mi Laptop Pro 15                | 1         | 2.44%   |
| RPi Raspberry Pi                     | 1         | 2.44%   |
| MSI MS-7D31                          | 1         | 2.44%   |
| MSI MS-7996                          | 1         | 2.44%   |
| Lenovo ThinkPad T470p 20J7S06Q00     | 1         | 2.44%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437  | 1         | 2.44%   |
| Lenovo ThinkPad E495 20NE000BGE      | 1         | 2.44%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX | 1         | 2.44%   |
| Lenovo ThinkBook 14 G3 ACL 21A2      | 1         | 2.44%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT    | 1         | 2.44%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5     | 1         | 2.44%   |
| Intel NUC8i7HVK                      | 1         | 2.44%   |
| Gigabyte Z87X-UD3H                   | 1         | 2.44%   |
| Gigabyte X570 AORUS MASTER           | 1         | 2.44%   |
| Framework Laptop                     | 1         | 2.44%   |
| EVGA Z390 DARK                       | 1         | 2.44%   |
| Dell XPS 15 9570                     | 1         | 2.44%   |
| Dell Latitude 7490                   | 1         | 2.44%   |
| Dell Inspiron 5415                   | 1         | 2.44%   |
| BESSTAR Tech X400                    | 1         | 2.44%   |
| ASUS Z170-A                          | 1         | 2.44%   |
| ASUS TUF GAMING B550-PLUS            | 1         | 2.44%   |
| ASUS TUF B450-PLUS GAMING            | 1         | 2.44%   |
| ASUS ROG ZENITH II EXTREME           | 1         | 2.44%   |
| ASUS ROG STRIX X570-E GAMING         | 1         | 2.44%   |
| ASUS ROG Strix G513QY_G513QY         | 1         | 2.44%   |
| ASUS ROG STRIX B550-F GAMING         | 1         | 2.44%   |
| ASUS ROG CROSSHAIR VIII HERO         | 1         | 2.44%   |
| ASUS PRIME X570-P                    | 1         | 2.44%   |
| ASUS P5LD2-Deluxe                    | 1         | 2.44%   |
| ASRock X370 Killer SLI/ac            | 1         | 2.44%   |
| ASRock X370 Gaming X                 | 1         | 2.44%   |
| ASRock H110M-HDV R3.0                | 1         | 2.44%   |
| Acer Aspire A715-42G                 | 1         | 2.44%   |
| Acer Aspire A515-55                  | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 5         | 12.2%   |
| Lenovo ThinkPad    | 4         | 9.76%   |
| Intel S1200RP      | 2         | 4.88%   |
| HP Laptop          | 2         | 4.88%   |
| ASUS TUF           | 2         | 4.88%   |
| ASRock X370        | 2         | 4.88%   |
| Acer Aspire        | 2         | 4.88%   |
| TYAN S7025         | 1         | 2.44%   |
| Toshiba Satellite  | 1         | 2.44%   |
| Timi Mi            | 1         | 2.44%   |
| RPi Raspberry      | 1         | 2.44%   |
| MSI MS-7D31        | 1         | 2.44%   |
| MSI MS-7996        | 1         | 2.44%   |
| Lenovo ThinkBook   | 1         | 2.44%   |
| Lenovo IdeaPadFlex | 1         | 2.44%   |
| Lenovo IdeaPad     | 1         | 2.44%   |
| Intel NUC8i7HVK    | 1         | 2.44%   |
| Gigabyte Z87X-UD3H | 1         | 2.44%   |
| Gigabyte X570      | 1         | 2.44%   |
| Framework Laptop   | 1         | 2.44%   |
| EVGA Z390          | 1         | 2.44%   |
| Dell XPS           | 1         | 2.44%   |
| Dell Latitude      | 1         | 2.44%   |
| Dell Inspiron      | 1         | 2.44%   |
| BESSTAR Tech X400  | 1         | 2.44%   |
| ASUS Z170-A        | 1         | 2.44%   |
| ASUS PRIME         | 1         | 2.44%   |
| ASUS P5LD2-Deluxe  | 1         | 2.44%   |
| ASRock H110M-HDV   | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 18        | 43.9%   |
| 2020    | 10        | 24.39%  |
| 2018    | 4         | 9.76%   |
| 2019    | 3         | 7.32%   |
| 2012    | 2         | 4.88%   |
| 2016    | 1         | 2.44%   |
| 2014    | 1         | 2.44%   |
| 2006    | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 17        | 41.46%  |
| Notebook       | 17        | 41.46%  |
| Server         | 4         | 9.76%   |
| System on chip | 1         | 2.44%   |
| Convertible    | 1         | 2.44%   |
| Mini pc        | 1         | 2.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 41        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 12        | 29.27%  |
| 8.01-16.0   | 9         | 21.95%  |
| 64.01-256.0 | 7         | 17.07%  |
| 16.01-24.0  | 5         | 12.2%   |
| 24.01-32.0  | 3         | 7.32%   |
| 4.01-8.0    | 2         | 4.88%   |
| 3.01-4.0    | 1         | 2.44%   |
| 2.01-3.0    | 1         | 2.44%   |
| 1.01-2.0    | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 38.1%   |
| 1.01-2.0   | 9         | 21.43%  |
| 8.01-16.0  | 4         | 9.52%   |
| 0.51-1.0   | 4         | 9.52%   |
| 3.01-4.0   | 3         | 7.14%   |
| 2.01-3.0   | 3         | 7.14%   |
| 24.01-32.0 | 1         | 2.38%   |
| 16.01-24.0 | 1         | 2.38%   |
| 0.01-0.5   | 1         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 19        | 45.24%  |
| 4      | 7         | 16.67%  |
| 3      | 6         | 14.29%  |
| 2      | 5         | 11.9%   |
| 5      | 4         | 9.52%   |
| 7      | 1         | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 90.24%  |
| Yes       | 4         | 9.76%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 75.61%  |
| No        | 10        | 24.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 68.29%  |
| No        | 13        | 31.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 66.67%  |
| No        | 14        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 7         | 17.07%  |
| Poland      | 5         | 12.2%   |
| Germany     | 5         | 12.2%   |
| Russia      | 4         | 9.76%   |
| Spain       | 3         | 7.32%   |
| UK          | 2         | 4.88%   |
| Greece      | 2         | 4.88%   |
| Finland     | 2         | 4.88%   |
| Turkey      | 1         | 2.44%   |
| Switzerland | 1         | 2.44%   |
| Slovenia    | 1         | 2.44%   |
| New Zealand | 1         | 2.44%   |
| Mexico      | 1         | 2.44%   |
| Italy       | 1         | 2.44%   |
| Czechia     | 1         | 2.44%   |
| China       | 1         | 2.44%   |
| Brazil      | 1         | 2.44%   |
| Belarus     | 1         | 2.44%   |
| Bangladesh  | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Swansea          | 2         | 4.76%   |
| Moscow           | 2         | 4.76%   |
| Helsinki         | 2         | 4.76%   |
| Barcelona        | 2         | 4.76%   |
| Athens           | 2         | 4.76%   |
| Zurich           | 1         | 2.38%   |
| Zebulon          | 1         | 2.38%   |
| Warsaw           | 1         | 2.38%   |
| Vigo             | 1         | 2.38%   |
| Ufa              | 1         | 2.38%   |
| Szczecin         | 1         | 2.38%   |
| S??o Paulo       | 1         | 2.38%   |
| Rzesz??w         | 1         | 2.38%   |
| Redmond          | 1         | 2.38%   |
| Ratingen         | 1         | 2.38%   |
| Nuremberg        | 1         | 2.38%   |
| Nizhniy Novgorod | 1         | 2.38%   |
| Niederdorla      | 1         | 2.38%   |
| Monroe           | 1         | 2.38%   |
| Minsk            | 1         | 2.38%   |
| Milan            | 1         | 2.38%   |
| Laziska Gorne    | 1         | 2.38%   |
| Krakow           | 1         | 2.38%   |
| Ivan??na Gorica  | 1         | 2.38%   |
| Harsum           | 1         | 2.38%   |
| Guangzhou        | 1         | 2.38%   |
| Glen Ellyn       | 1         | 2.38%   |
| Everett          | 1         | 2.38%   |
| Dhaka            | 1         | 2.38%   |
| Ciudad Ju??rez   | 1         | 2.38%   |
| Cieszyn          | 1         | 2.38%   |
| Chicago          | 1         | 2.38%   |
| Cerritos         | 1         | 2.38%   |
| Brno             | 1         | 2.38%   |
| Berlin           | 1         | 2.38%   |
| Auckland         | 1         | 2.38%   |
| Ankara           | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 18        | 27     | 25.35%  |
| Samsung Electronics            | 12        | 19     | 16.9%   |
| Seagate                        | 8         | 17     | 11.27%  |
| Toshiba                        | 5         | 5      | 7.04%   |
| Crucial                        | 4         | 7      | 5.63%   |
| SK Hynix                       | 3         | 3      | 4.23%   |
| Intel                          | 3         | 3      | 4.23%   |
| Hitachi                        | 3         | 4      | 4.23%   |
| Unknown                        | 2         | 6      | 2.82%   |
| Team                           | 2         | 2      | 2.82%   |
| Corsair                        | 2         | 2      | 2.82%   |
| Solid State Storage Technology | 1         | 1      | 1.41%   |
| SanDisk                        | 1         | 1      | 1.41%   |
| Phison                         | 1         | 1      | 1.41%   |
| KIOXIA-EXCERIA                 | 1         | 1      | 1.41%   |
| KIOXIA                         | 1         | 1      | 1.41%   |
| Kingston                       | 1         | 1      | 1.41%   |
| Kingchuxing                    | 1         | 1      | 1.41%   |
| GOODRAM                        | 1         | 1      | 1.41%   |
| A-DATA Technology              | 1         | 1      | 1.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| WDC WD30EFRX-68EUZN0 3TB                   | 2         | 2.35%   |
| Toshiba DT01ACA100 1TB                     | 2         | 2.35%   |
| Crucial CT1000P1SSD8 1TB                   | 2         | 2.35%   |
| WDC WDS500G2X0C-00L350 500GB               | 1         | 1.18%   |
| WDC WDS500G2B0B-00YS70 500GB SSD           | 1         | 1.18%   |
| WDC WDS500G2B0A-00SM50 500GB SSD           | 1         | 1.18%   |
| WDC WDS240G2G0A 240GB SSD                  | 1         | 1.18%   |
| WDC WD60EFRX-68L0BN1 6TB                   | 1         | 1.18%   |
| WDC WD5000AZLX-00JKKA0 500GB               | 1         | 1.18%   |
| WDC WD30EFRX-68AX9N0 3TB                   | 1         | 1.18%   |
| WDC WD2500BEVS-22UST0 250GB                | 1         | 1.18%   |
| WDC WD20EFRX-68EUZN0 2TB                   | 1         | 1.18%   |
| WDC WD10PURX-64E5EY0 1TB                   | 1         | 1.18%   |
| WDC WD10EZEX-60WN4A1 1TB                   | 1         | 1.18%   |
| WDC WD10EZEX-22M                           | 1         | 1.18%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1         | 1.18%   |
| WDC WD10EZEX-08M2NA0 1TB                   | 1         | 1.18%   |
| WDC WD10EARS-00MVWB0 1TB                   | 1         | 1.18%   |
| WDC WD10EADS-00L5B1 1TB                    | 1         | 1.18%   |
| WDC WD1002FBYS-18W8B0 1TB                  | 1         | 1.18%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB       | 1         | 1.18%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB       | 1         | 1.18%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB       | 1         | 1.18%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB       | 1         | 1.18%   |
| Unknown USB DISK 3.2 1TB                   | 1         | 1.18%   |
| Unknown MMC Card  32GB                     | 1         | 1.18%   |
| Toshiba THNSN5512GPUK NVMe 512GB           | 1         | 1.18%   |
| Toshiba KXG6AZNV512G 512GB                 | 1         | 1.18%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD    | 1         | 1.18%   |
| Team TM8PS7256G 256GB SSD                  | 1         | 1.18%   |
| Team TM8FP2240G 240GB                      | 1         | 1.18%   |
| Solid State Storage NVMe SSD Drive 256GB   | 1         | 1.18%   |
| SK Hynix HFM512GDHTNG-8710B 512GB          | 1         | 1.18%   |
| SK Hynix HFM512GD3JX016N 512GB             | 1         | 1.18%   |
| SK Hynix BC711 NVMe 512GB                  | 1         | 1.18%   |
| Seagate ST4000DM005-2DP166 4TB             | 1         | 1.18%   |
| Seagate ST4000DM004-2CV104 4TB             | 1         | 1.18%   |
| Seagate ST3500630AS 500GB                  | 1         | 1.18%   |
| Seagate ST3250318AS 250GB                  | 1         | 1.18%   |
| Seagate ST3160023AS 160GB                  | 1         | 1.18%   |
| Seagate ST2000DM001-1ER164 2TB             | 1         | 1.18%   |
| Seagate ST10000NM0568-2H5110 10TB          | 1         | 1.18%   |
| Seagate ST10000NM0156-2AA111 10TB          | 1         | 1.18%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB     | 1         | 1.18%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1         | 1.18%   |
| SanDisk SDSSDHII480G 480GB                 | 1         | 1.18%   |
| Samsung SSD 970 PRO 512GB                  | 1         | 1.18%   |
| Samsung SSD 970 EVO Plus 2TB               | 1         | 1.18%   |
| Samsung SSD 970 EVO Plus 250GB             | 1         | 1.18%   |
| Samsung SSD 970 EVO 500GB                  | 1         | 1.18%   |
| Samsung SSD 970 EVO 250GB                  | 1         | 1.18%   |
| Samsung SSD 950 PRO 512GB                  | 1         | 1.18%   |
| Samsung SSD 860 QVO 4TB                    | 1         | 1.18%   |
| Samsung SSD 860 PRO 1TB                    | 1         | 1.18%   |
| Samsung SSD 860 EVO 2TB                    | 1         | 1.18%   |
| Samsung SSD 850 EVO M.2 1TB                | 1         | 1.18%   |
| Samsung SSD 840 PRO Series 128GB           | 1         | 1.18%   |
| Samsung Portable SSD T3 250GB              | 1         | 1.18%   |
| Samsung NVMe SSD Drive 512GB               | 1         | 1.18%   |
| Samsung NVMe SSD Drive 500GB               | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 12        | 19     | 52.17%  |
| Seagate | 6         | 15     | 26.09%  |
| Hitachi | 3         | 4      | 13.04%  |
| Toshiba | 2         | 2      | 8.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 35.29%  |
| WDC                 | 3         | 3      | 17.65%  |
| Toshiba             | 1         | 1      | 5.88%   |
| Team                | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| Kingston            | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| GOODRAM             | 1         | 1      | 5.88%   |
| Crucial             | 1         | 3      | 5.88%   |
| Corsair             | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 29        | 38     | 46.77%  |
| HDD     | 16        | 40     | 25.81%  |
| SSD     | 15        | 20     | 24.19%  |
| MMC     | 1         | 3      | 1.61%   |
| Unknown | 1         | 3      | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 29        | 38     | 53.7%   |
| SATA | 23        | 60     | 42.59%  |
| SAS  | 1         | 3      | 1.85%   |
| MMC  | 1         | 3      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 11        | 15     | 33.33%  |
| 0.01-0.5   | 11        | 19     | 33.33%  |
| 1.01-2.0   | 4         | 6      | 12.12%  |
| 4.01-10.0  | 3         | 11     | 9.09%   |
| 3.01-4.0   | 2         | 4      | 6.06%   |
| 2.01-3.0   | 2         | 5      | 6.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 12        | 28.57%  |
| 501-1000       | 7         | 16.67%  |
| More than 3000 | 5         | 11.9%   |
| 1001-2000      | 5         | 11.9%   |
| 101-250        | 4         | 9.52%   |
| 1-20           | 4         | 9.52%   |
| Unknown        | 2         | 4.76%   |
| 21-50          | 1         | 2.38%   |
| 2001-3000      | 1         | 2.38%   |
| 51-100         | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 10        | 23.81%  |
| 251-500        | 8         | 19.05%  |
| 21-50          | 5         | 11.9%   |
| 101-250        | 5         | 11.9%   |
| More than 3000 | 4         | 9.52%   |
| 1001-2000      | 3         | 7.14%   |
| 501-1000       | 3         | 7.14%   |
| 51-100         | 2         | 4.76%   |
| Unknown        | 2         | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB    | 1         | 3      | 14.29%  |
| WDC WD30EFRX-68AX9N0 3TB    | 1         | 2      | 14.29%  |
| WDC WD1002FBYS-18W8B0 1TB   | 1         | 1      | 14.29%  |
| Seagate ST3160023AS 160GB   | 1         | 1      | 14.29%  |
| Hitachi HUA721010KLA330 1TB | 1         | 1      | 14.29%  |
| Hitachi HDS722020ALA330 2TB | 1         | 2      | 14.29%  |
| Crucial CT1000P1SSD8 1TB    | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 6      | 42.86%  |
| Hitachi | 2         | 3      | 28.57%  |
| Seagate | 1         | 1      | 14.29%  |
| Crucial | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 6      | 50%     |
| Hitachi | 2         | 3      | 33.33%  |
| Seagate | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 10     | 80%     |
| NVMe | 1         | 1      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 36        | 77     | 75%     |
| Detected | 6         | 15     | 12.5%   |
| Malfunc  | 5         | 11     | 10.42%  |
| Failed   | 1         | 1      | 2.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 16        | 23.19%  |
| AMD                            | 15        | 21.74%  |
| Samsung Electronics            | 9         | 13.04%  |
| Sandisk                        | 5         | 7.25%   |
| ASMedia Technology             | 4         | 5.8%    |
| Toshiba America Info Systems   | 3         | 4.35%   |
| SK Hynix                       | 3         | 4.35%   |
| Phison Electronics             | 3         | 4.35%   |
| Seagate Technology             | 2         | 2.9%    |
| Micron/Crucial Technology      | 2         | 2.9%    |
| Solid State Storage Technology | 1         | 1.45%   |
| Silicon Motion                 | 1         | 1.45%   |
| Silicon Image                  | 1         | 1.45%   |
| Micron Technology              | 1         | 1.45%   |
| Marvell Technology Group       | 1         | 1.45%   |
| KIOXIA                         | 1         | 1.45%   |
| ADATA Technology               | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 17.81%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 9.59%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 5.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 4.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 4.11%   |
| SK Hynix Gold P31 SSD                                                          | 2         | 2.74%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 2.74%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 2.74%   |
| AMD X370 Series Chipset SATA Controller                                        | 2         | 2.74%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 2         | 2.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.37%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.37%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 1.37%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1.37%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 1.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.37%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.37%   |
| Seagate Non-Volatile memory controller                                         | 1         | 1.37%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 1.37%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.37%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.37%   |
| Phison E7 NVMe Controller                                                      | 1         | 1.37%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.37%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 1.37%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.37%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 1.37%   |
| KIOXIA NVMe SSD                                                                | 1         | 1.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.37%   |
| Intel SSD 660P Series                                                          | 1         | 1.37%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.37%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.37%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.37%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.37%   |
| Intel 600 Series Chipset Family SATA AHCI Controller                           | 1         | 1.37%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.37%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 29        | 49.15%  |
| SATA | 27        | 45.76%  |
| IDE  | 2         | 3.39%   |
| RAID | 1         | 1.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 21        | 51.22%  |
| Intel  | 19        | 46.34%  |
| ARM    | 1         | 2.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz            | 2         | 4.88%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 2         | 4.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 2         | 4.88%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2         | 4.88%   |
| Intel Xeon CPU X5680 @ 3.33GHz                 | 1         | 2.44%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1         | 2.44%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 1         | 2.44%   |
| Intel Core i7-8809G CPU @ 3.10GHz              | 1         | 2.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 2.44%   |
| Intel Core i7-8650U CPU @ 1.90GHz              | 1         | 2.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 2.44%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1         | 2.44%   |
| Intel Core i7-10850H CPU @ 2.70GHz             | 1         | 2.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 1         | 2.44%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 2.44%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1         | 2.44%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1         | 2.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 2.44%   |
| Intel 12th Gen Core i7-12700K                  | 1         | 2.44%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 2.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 2.44%   |
| ARM Processor                                  | 1         | 2.44%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1         | 2.44%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1         | 2.44%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 1         | 2.44%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1         | 2.44%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1         | 2.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 2.44%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx  | 1         | 2.44%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1         | 2.44%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics     | 1         | 2.44%   |
| AMD Ryzen 5 5600H with Radeon Graphics         | 1         | 2.44%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 1         | 2.44%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 2.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 2.44%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx  | 1         | 2.44%   |
| AMD E1-1200 APU with Radeon HD Graphics        | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 7         | 17.07%  |
| AMD Ryzen 5            | 6         | 14.63%  |
| AMD Ryzen 9            | 5         | 12.2%   |
| AMD Ryzen 7            | 5         | 12.2%   |
| Other                  | 4         | 9.76%   |
| Intel Core i5          | 4         | 9.76%   |
| Intel Xeon             | 3         | 7.32%   |
| Intel Pentium 4        | 1         | 2.44%   |
| Intel Core i9          | 1         | 2.44%   |
| AMD Ryzen Threadripper | 1         | 2.44%   |
| AMD Ryzen 7 PRO        | 1         | 2.44%   |
| AMD Ryzen 5 PRO        | 1         | 2.44%   |
| AMD Ryzen 3            | 1         | 2.44%   |
| AMD E1                 | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 15        | 36.59%  |
| 6       | 8         | 19.51%  |
| 8       | 7         | 17.07%  |
| 16      | 3         | 7.32%   |
| 12      | 3         | 7.32%   |
| 2       | 2         | 4.88%   |
| 24      | 1         | 2.44%   |
| 1       | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 39        | 95.12%  |
| 2       | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 34        | 82.93%  |
| 1       | 6         | 14.63%  |
| Unknown | 1         | 2.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 41        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 14.63%  |
| 0x906e9    | 3         | 7.32%   |
| 0x08701021 | 3         | 7.32%   |
| 0x08001138 | 3         | 7.32%   |
| 0x306c3    | 2         | 4.88%   |
| 0x0a50000c | 2         | 4.88%   |
| 0x08608103 | 2         | 4.88%   |
| 0x08108109 | 2         | 4.88%   |
| 0xf43      | 1         | 2.44%   |
| 0xa0652    | 1         | 2.44%   |
| 0x906ed    | 1         | 2.44%   |
| 0x906ea    | 1         | 2.44%   |
| 0x90672    | 1         | 2.44%   |
| 0x806ec    | 1         | 2.44%   |
| 0x806c1    | 1         | 2.44%   |
| 0x706e5    | 1         | 2.44%   |
| 0x506e3    | 1         | 2.44%   |
| 0x206c2    | 1         | 2.44%   |
| 0x0a50000b | 1         | 2.44%   |
| 0x0a201016 | 1         | 2.44%   |
| 0x08608102 | 1         | 2.44%   |
| 0x08600106 | 1         | 2.44%   |
| 0x08600103 | 1         | 2.44%   |
| 0x08301039 | 1         | 2.44%   |
| 0x08108102 | 1         | 2.44%   |
| 0x05000119 | 1         | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 2            | 7         | 17.07%  |
| KabyLake         | 7         | 17.07%  |
| Zen 3            | 4         | 9.76%   |
| Unknown          | 4         | 9.76%   |
| Zen+             | 3         | 7.32%   |
| Zen              | 3         | 7.32%   |
| Haswell          | 3         | 7.32%   |
| TigerLake        | 2         | 4.88%   |
| Skylake          | 2         | 4.88%   |
| Westmere         | 1         | 2.44%   |
| NetBurst         | 1         | 2.44%   |
| IceLake          | 1         | 2.44%   |
| CometLake        | 1         | 2.44%   |
| Bobcat           | 1         | 2.44%   |
| Alderlake Hybrid | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| AMD                        | 21        | 43.75%  |
| Intel                      | 13        | 27.08%  |
| Nvidia                     | 12        | 25%     |
| Matrox Electronics Systems | 2         | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]              | 4         | 8%      |
| Intel HD Graphics 630                                                | 3         | 6%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 3         | 6%      |
| AMD Lucienne                                                         | 3         | 6%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                  | 2         | 4%      |
| Nvidia GM206 [GeForce GTX 960]                                       | 2         | 4%      |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)    | 2         | 4%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 2         | 4%      |
| AMD Renoir                                                           | 2         | 4%      |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                         | 2         | 4%      |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                       | 2         | 4%      |
| AMD Cezanne                                                          | 2         | 4%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 1         | 2%      |
| Nvidia TU116 [GeForce GTX 1650]                                      | 1         | 2%      |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                            | 1         | 2%      |
| Nvidia GP108M [GeForce MX250]                                        | 1         | 2%      |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 2%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 2%      |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                   | 1         | 2%      |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 2%      |
| Intel UHD Graphics 620                                               | 1         | 2%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                               | 1         | 2%      |
| Intel HD Graphics 530                                                | 1         | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 1         | 2%      |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                            | 1         | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 1         | 2%      |
| Intel AlderLake-S GT1                                                | 1         | 2%      |
| AMD Wrestler [Radeon HD 7310]                                        | 1         | 2%      |
| AMD Polaris 22 XT [Radeon RX Vega M GH]                              | 1         | 2%      |
| AMD Oland PRO [Radeon R7 240/340]                                    | 1         | 2%      |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                       | 1         | 2%      |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]  | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 16        | 39.02%  |
| 1 x Intel      | 7         | 17.07%  |
| 1 x Nvidia     | 5         | 12.2%   |
| Intel + Nvidia | 4         | 9.76%   |
| AMD + Nvidia   | 3         | 7.32%   |
| Other          | 2         | 4.88%   |
| 2 x AMD        | 2         | 4.88%   |
| 1 x Matrox     | 2         | 4.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 65.85%  |
| Proprietary | 9         | 21.95%  |
| Unknown     | 5         | 12.2%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 42.86%  |
| 1.01-2.0   | 6         | 14.29%  |
| 3.01-4.0   | 5         | 11.9%   |
| 8.01-16.0  | 5         | 11.9%   |
| 0.51-1.0   | 3         | 7.14%   |
| 0.01-0.5   | 3         | 7.14%   |
| 7.01-8.0   | 2         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 5         | 10.87%  |
| AU Optronics            | 5         | 10.87%  |
| Chimei Innolux          | 4         | 8.7%    |
| Dell                    | 3         | 6.52%   |
| Sharp                   | 2         | 4.35%   |
| Samsung Electronics     | 2         | 4.35%   |
| Lenovo                  | 2         | 4.35%   |
| Hewlett-Packard         | 2         | 4.35%   |
| Goldstar                | 2         | 4.35%   |
| BenQ                    | 2         | 4.35%   |
| AOC                     | 2         | 4.35%   |
| Toshiba                 | 1         | 2.17%   |
| Sceptre                 | 1         | 2.17%   |
| Philips                 | 1         | 2.17%   |
| PANDA                   | 1         | 2.17%   |
| NEC Computers           | 1         | 2.17%   |
| MXX                     | 1         | 2.17%   |
| MStar                   | 1         | 2.17%   |
| Mi                      | 1         | 2.17%   |
| Iiyama                  | 1         | 2.17%   |
| Gigabyte Technology     | 1         | 2.17%   |
| Gateway                 | 1         | 2.17%   |
| Chi Mei Optoelectronics | 1         | 2.17%   |
| ASUSTek Computer        | 1         | 2.17%   |
| Ancor Communications    | 1         | 2.17%   |
| Acer                    | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 2         | 4.08%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch         | 2         | 4.08%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1         | 2.04%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 2.04%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 2.04%   |
| Sceptre LCD Monitor C305W-2560UN                                       | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 2.04%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch     | 1         | 2.04%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 2.04%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 2.04%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1         | 2.04%   |
| MXX O-3-H MXX0001 3840x2160 1872x1053mm 84.6-inch                      | 1         | 2.04%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1         | 2.04%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1         | 2.04%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1         | 2.04%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 597x336mm 27.0-inch               | 1         | 2.04%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                   | 1         | 2.04%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch           | 1         | 2.04%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch          | 1         | 2.04%   |
| Hewlett-Packard 22f HPN3541 1920x1080 500x300mm 23.0-inch              | 1         | 2.04%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 1         | 2.04%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch | 1         | 2.04%   |
| Gateway FPD1765 GWY06E9 1280x1024 338x270mm 17.0-inch                  | 1         | 2.04%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 1         | 2.04%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                      | 1         | 2.04%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 1         | 2.04%   |
| Dell P2219HC DELA11A 1920x1080 476x267mm 21.5-inch                     | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch       | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch       | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch       | 1         | 2.04%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch  | 1         | 2.04%   |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                  | 1         | 2.04%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 1         | 2.04%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 1         | 2.04%   |
| BOE LCD Monitor BOE08D6 1920x1080 309x174mm 14.0-inch                  | 1         | 2.04%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                  | 1         | 2.04%   |
| BenQ G2420HD BNQ7840 1920x1080 530x300mm 24.0-inch                     | 1         | 2.04%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                     | 1         | 2.04%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch         | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch         | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch         | 1         | 2.04%   |
| ASUSTek Computer VG27A AUS2723 2560x1440 597x336mm 27.0-inch           | 1         | 2.04%   |
| AOC 2437 AOC2437 1920x1080 521x293mm 23.5-inch                         | 1         | 2.04%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                       | 1         | 2.04%   |
| Ancor Communications LCD Monitor VW246                                 | 1         | 2.04%   |
| Acer LCD Monitor SA230 6400x1080                                       | 1         | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 42.55%  |
| 2560x1440 (QHD)    | 9         | 19.15%  |
| 3840x2160 (4K)     | 5         | 10.64%  |
| 1366x768 (WXGA)    | 2         | 4.26%   |
| 6400x1080          | 1         | 2.13%   |
| 3840x1080          | 1         | 2.13%   |
| 3440x1440          | 1         | 2.13%   |
| 2560x1600          | 1         | 2.13%   |
| 2560x1080          | 1         | 2.13%   |
| 2256x1504          | 1         | 2.13%   |
| 1920x1200 (WUXGA)  | 1         | 2.13%   |
| 1680x1050 (WSXGA+) | 1         | 2.13%   |
| 1440x900 (WXGA+)   | 1         | 2.13%   |
| 1280x1024 (SXGA)   | 1         | 2.13%   |
| Unknown            | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 11        | 23.4%   |
| 27      | 9         | 19.15%  |
| 13      | 5         | 10.64%  |
| 21      | 4         | 8.51%   |
| 23      | 3         | 6.38%   |
| 34      | 2         | 4.26%   |
| 25      | 2         | 4.26%   |
| 14      | 2         | 4.26%   |
| 84      | 1         | 2.13%   |
| 49      | 1         | 2.13%   |
| 31      | 1         | 2.13%   |
| 24      | 1         | 2.13%   |
| 20      | 1         | 2.13%   |
| 19      | 1         | 2.13%   |
| 17      | 1         | 2.13%   |
| 16      | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 43.18%  |
| 501-600     | 11        | 25%     |
| 401-500     | 6         | 13.64%  |
| 701-800     | 2         | 4.55%   |
| 601-700     | 2         | 4.55%   |
| 201-300     | 1         | 2.27%   |
| 1501-2000   | 1         | 2.27%   |
| 1001-1500   | 1         | 2.27%   |
| Unknown     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 32        | 76.19%  |
| 16/10   | 4         | 9.52%   |
| 21/9    | 2         | 4.76%   |
| 5/4     | 1         | 2.38%   |
| 32/9    | 1         | 2.38%   |
| 3/2     | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 23.91%  |
| 301-350        | 9         | 19.57%  |
| 81-90          | 7         | 15.22%  |
| 201-250        | 6         | 13.04%  |
| 351-500        | 3         | 6.52%   |
| 151-200        | 3         | 6.52%   |
| 251-300        | 2         | 4.35%   |
| More than 1000 | 1         | 2.17%   |
| 141-150        | 1         | 2.17%   |
| 111-120        | 1         | 2.17%   |
| 501-1000       | 1         | 2.17%   |
| Unknown        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 32.56%  |
| 101-120       | 13        | 30.23%  |
| 51-100        | 8         | 18.6%   |
| 161-240       | 5         | 11.63%  |
| More than 240 | 1         | 2.33%   |
| 1-50          | 1         | 2.33%   |
| Unknown       | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 63.41%  |
| 2     | 10        | 24.39%  |
| 0     | 4         | 9.76%   |
| 3     | 1         | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 27        | 48.21%  |
| Realtek Semiconductor    | 18        | 32.14%  |
| MEDIATEK                 | 2         | 3.57%   |
| Aquantia                 | 2         | 3.57%   |
| Samsung Electronics      | 1         | 1.79%   |
| Raspberry Pi             | 1         | 1.79%   |
| Ralink Technology        | 1         | 1.79%   |
| Qualcomm Atheros         | 1         | 1.79%   |
| Microsoft                | 1         | 1.79%   |
| Marvell Technology Group | 1         | 1.79%   |
| ICS Advent               | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 14.08%  |
| Intel Wi-Fi 6 AX200                                               | 8         | 11.27%  |
| Intel I211 Gigabit Network Connection                             | 5         | 7.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 5.63%   |
| Intel I210 Gigabit Network Connection                             | 4         | 5.63%   |
| Intel Wireless 8265 / 8275                                        | 3         | 4.23%   |
| MEDIATEK Network controller                                       | 2         | 2.82%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 2.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.41%   |
| Raspberry Pi Pico                                                 | 1         | 1.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 1.41%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 1.41%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1         | 1.41%   |
| Microsoft XBOX ACC                                                | 1         | 1.41%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.41%   |
| Intel Wireless-AC 9260                                            | 1         | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.41%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.41%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.41%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.41%   |
| Intel 600 Series Chipset Family Wireless-AC 9560                  | 1         | 1.41%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 68.97%  |
| Realtek Semiconductor | 4         | 13.79%  |
| MEDIATEK              | 2         | 6.9%    |
| Ralink Technology     | 1         | 3.45%   |
| Qualcomm Atheros      | 1         | 3.45%   |
| Microsoft             | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 8         | 26.67%  |
| Intel Wireless 8265 / 8275                                 | 3         | 10%     |
| MEDIATEK Network controller                                | 2         | 6.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 3.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1         | 3.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1         | 3.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1         | 3.33%   |
| Microsoft XBOX ACC                                         | 1         | 3.33%   |
| Intel Wireless-AC 9260                                     | 1         | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 3.33%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 3.33%   |
| Intel 600 Series Chipset Family Wireless-AC 9560           | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 16        | 43.24%  |
| Intel                    | 16        | 43.24%  |
| Aquantia                 | 2         | 5.41%   |
| Samsung Electronics      | 1         | 2.7%    |
| Marvell Technology Group | 1         | 2.7%    |
| ICS Advent               | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 25%     |
| Intel I211 Gigabit Network Connection                             | 5         | 12.5%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 10%     |
| Intel I210 Gigabit Network Connection                             | 4         | 10%     |
| Intel Ethernet Controller I225-V                                  | 2         | 5%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 5%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.5%    |
| Intel I350 Gigabit Network Connection                             | 1         | 2.5%    |
| Intel Ethernet Connection I217-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.5%    |
| Intel Ethernet Connection (5) I219-V                              | 1         | 2.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.5%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.5%    |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 51.67%  |
| WiFi     | 28        | 46.67%  |
| Modem    | 1         | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 53.19%  |
| WiFi     | 22        | 46.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 18        | 43.9%   |
| 2     | 14        | 34.15%  |
| 3     | 5         | 12.2%   |
| 0     | 2         | 4.88%   |
| 6     | 1         | 2.44%   |
| 4     | 1         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 73.17%  |
| Yes  | 11        | 26.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 19        | 67.86%  |
| Realtek Semiconductor   | 4         | 14.29%  |
| Toshiba                 | 1         | 3.57%   |
| IMC Networks            | 1         | 3.57%   |
| Foxconn / Hon Hai       | 1         | 3.57%   |
| Cambridge Silicon Radio | 1         | 3.57%   |
| ASUSTek Computer        | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 9         | 32.14%  |
| Intel AX200 Bluetooth                               | 8         | 28.57%  |
| Realtek Bluetooth Radio                             | 2         | 7.14%   |
| Toshiba RT Bluetooth Radio                          | 1         | 3.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.57%   |
| IMC Networks Wireless_Device                        | 1         | 3.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| AMD                                  | 24        | 38.1%   |
| Intel                                | 16        | 25.4%   |
| Nvidia                               | 8         | 12.7%   |
| SteelSeries ApS                      | 2         | 3.17%   |
| Logitech                             | 2         | 3.17%   |
| C-Media Electronics                  | 2         | 3.17%   |
| ASUSTek Computer                     | 2         | 3.17%   |
| Thesycon Systemsoftware & Consulting | 1         | 1.59%   |
| Texas Instruments                    | 1         | 1.59%   |
| SAVITECH                             | 1         | 1.59%   |
| RODE Microphones                     | 1         | 1.59%   |
| Creative Labs                        | 1         | 1.59%   |
| AudioQuest                           | 1         | 1.59%   |
| ACTIONS                              | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                     | 11        | 13.1%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 8         | 9.52%   |
| AMD Starship/Matisse HD Audio Controller                                | 6         | 7.14%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]               | 4         | 4.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 4         | 4.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 3         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 3         | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 3         | 3.57%   |
| Nvidia GP106 High Definition Audio Controller                           | 2         | 2.38%   |
| Nvidia GM206 High Definition Audio Controller                           | 2         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 2         | 2.38%   |
| Intel CM238 HD Audio Controller                                         | 2         | 2.38%   |
| Intel Cannon Lake PCH cAVS                                              | 2         | 2.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 2         | 2.38%   |
| Thesycon Systemsoftware & Consulting DX3 Pro                            | 1         | 1.19%   |
| Texas Instruments PCM2912A Audio Codec                                  | 1         | 1.19%   |
| SteelSeries ApS SteelSeries Arctis 5                                    | 1         | 1.19%   |
| SteelSeries ApS Arctis 7 wireless adapter                               | 1         | 1.19%   |
| SAVITECH SA9023 audio controller                                        | 1         | 1.19%   |
| RODE Microphones RODE VideoMic NTG                                      | 1         | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                           | 1         | 1.19%   |
| Nvidia TU102 High Definition Audio Controller                           | 1         | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                           | 1         | 1.19%   |
| Nvidia GP102 HDMI Audio Controller                                      | 1         | 1.19%   |
| Logitech Z-5 Speakers                                                   | 1         | 1.19%   |
| Logitech Yeti X                                                         | 1         | 1.19%   |
| Intel Sunrise Point-LP HD Audio                                         | 1         | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1         | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller               | 1         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                            | 1         | 1.19%   |
| Intel Comet Lake PCH cAVS                                               | 1         | 1.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                        | 1         | 1.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 1         | 1.19%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]           | 1         | 1.19%   |
| C-Media Electronics USB Advanced Audio Device                           | 1         | 1.19%   |
| C-Media Electronics CM108 Audio Controller                              | 1         | 1.19%   |
| AudioQuest SDAC                                                         | 1         | 1.19%   |
| ASUSTek Computer Xonar U1 Audio Station                                 | 1         | 1.19%   |
| ASUSTek Computer USB Audio                                              | 1         | 1.19%   |
| AMD Wrestler HDMI Audio                                                 | 1         | 1.19%   |
| AMD Polaris 22 HDMI Audio                                               | 1         | 1.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 1.19%   |
| AMD FCH Azalia Controller                                               | 1         | 1.19%   |
| ACTIONS EDIFIER M380                                                    | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 23.26%  |
| Kingston            | 10        | 23.26%  |
| SK Hynix            | 6         | 13.95%  |
| G.Skill             | 5         | 11.63%  |
| Crucial             | 4         | 9.3%    |
| Micron Technology   | 3         | 6.98%   |
| Unknown             | 1         | 2.33%   |
| Transcend           | 1         | 2.33%   |
| Team                | 1         | 2.33%   |
| Patriot             | 1         | 2.33%   |
| Corsair             | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 4.44%   |
| Unknown RAM Module 512MB DIMM SDRAM                         | 1         | 2.22%   |
| Unknown RAM Module 1GB DIMM SDRAM                           | 1         | 2.22%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s       | 1         | 2.22%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 1         | 2.22%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s     | 1         | 2.22%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 2.22%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s   | 1         | 2.22%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s   | 1         | 2.22%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 1         | 2.22%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s   | 1         | 2.22%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s       | 1         | 2.22%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s   | 1         | 2.22%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 2.22%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s    | 1         | 2.22%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 1         | 2.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 2.22%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 2.22%   |
| Samsung RAM M378A2G43MX3-CTD 16384MB DIMM DDR4 2666MT/s     | 1         | 2.22%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s         | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 1         | 2.22%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s     | 1         | 2.22%   |
| Micron RAM 18KSF1G72AZ-1G6E1 8GB DIMM DDR3 1600MT/s         | 1         | 2.22%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 1         | 2.22%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s         | 1         | 2.22%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s     | 1         | 2.22%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 1         | 2.22%   |
| Kingston RAM HP26D4S9S8HJ-8 8192MB SODIMM DDR4 2667MT/s     | 1         | 2.22%   |
| Kingston RAM 99U5624-013.A00G 8GB SODIMM DDR4 2400MT/s      | 1         | 2.22%   |
| Kingston RAM 9965525-055.A00LF 8GB DIMM DDR3 1600MT/s       | 1         | 2.22%   |
| Kingston RAM 9965487-004.A00LF 4GB DIMM 1066MT/s            | 1         | 2.22%   |
| Kingston RAM 9905700-053.A00G 8192MB SODIMM DDR4 3200MT/s   | 1         | 2.22%   |
| Kingston RAM 9905625-062.A00G 8192MB DIMM DDR4 2133MT/s     | 1         | 2.22%   |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s       | 1         | 2.22%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s      | 1         | 2.22%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s       | 1         | 2.22%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s         | 1         | 2.22%   |
| G.Skill RAM F3-14900CL9-4GBSR 4096MB DIMM DDR3 1600MT/s     | 1         | 2.22%   |
| Crucial RAM CT16G4DFD8213.C16FAD 16GB DIMM DDR4 2133MT/s    | 1         | 2.22%   |
| Crucial RAM BLS4G4D26BFSE.8FE 4GB DIMM DDR4 2667MT/s        | 1         | 2.22%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4             | 1         | 2.22%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s | 1         | 2.22%   |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s     | 1         | 2.22%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 31        | 83.78%  |
| DDR3    | 4         | 10.81%  |
| SDRAM   | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 48.65%  |
| DIMM         | 18        | 48.65%  |
| Row Of Chips | 1         | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 16        | 40%     |
| 16384 | 14        | 35%     |
| 32768 | 4         | 10%     |
| 4096  | 3         | 7.5%    |
| 2048  | 1         | 2.5%    |
| 1024  | 1         | 2.5%    |
| 512   | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 11        | 27.5%   |
| 2667    | 10        | 25%     |
| 3600    | 4         | 10%     |
| 2133    | 4         | 10%     |
| 1600    | 4         | 10%     |
| 3866    | 1         | 2.5%    |
| 3666    | 1         | 2.5%    |
| 3400    | 1         | 2.5%    |
| 2666    | 1         | 2.5%    |
| 2400    | 1         | 2.5%    |
| 1066    | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| IMC Networks                  | 4         | 16.67%  |
| Logitech                      | 3         | 12.5%   |
| Chicony Electronics           | 3         | 12.5%   |
| Sunplus Innovation Technology | 2         | 8.33%   |
| Realtek Semiconductor         | 2         | 8.33%   |
| Quanta                        | 2         | 8.33%   |
| Luxvisions Innotech Limited   | 2         | 8.33%   |
| SunplusIT                     | 1         | 4.17%   |
| Microdia                      | 1         | 4.17%   |
| Lite-On Technology            | 1         | 4.17%   |
| KYE Systems (Mouse Systems)   | 1         | 4.17%   |
| Generalplus Technology        | 1         | 4.17%   |
| Acer                          | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 4         | 16.67%  |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 8.33%   |
| SunplusIT AUKEY PC???ˆ?”LM4                         | 1         | 4.17%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 4.17%   |
| Sunplus FULL HD webcam                              | 1         | 4.17%   |
| Realtek Integrated Webcam HD                        | 1         | 4.17%   |
| Realtek Integrated Camera                           | 1         | 4.17%   |
| Quanta RGB-IR Camera                                | 1         | 4.17%   |
| Quanta HD Webcam                                    | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.17%   |
| Logitech Webcam C270                                | 1         | 4.17%   |
| Logitech StreamCam                                  | 1         | 4.17%   |
| Logitech QuickCam Orbit/Sphere AF                   | 1         | 4.17%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 4.17%   |
| KYE Systems (Mouse Systems) Genius Webcam           | 1         | 4.17%   |
| Generalplus GENERAL WEBCAM                          | 1         | 4.17%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 4.17%   |
| Chicony Integrated Camera                           | 1         | 4.17%   |
| Chicony HD User Facing                              | 1         | 4.17%   |
| Acer Integrated Camera                              | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 2         | 50%     |
| Validity Sensors      | 1         | 25%     |
| Elan Microelectronics | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 25%     |
| Elan ELAN:Fingerprint                             | 1         | 25%     |
| Unknown                                           | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 22        | 53.66%  |
| 1     | 13        | 31.71%  |
| 2     | 3         | 7.32%   |
| 3     | 2         | 4.88%   |
| 4     | 1         | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 5         | 17.86%  |
| Graphics card            | 4         | 14.29%  |
| Fingerprint reader       | 4         | 14.29%  |
| Camera                   | 4         | 14.29%  |
| Multimedia controller    | 3         | 10.71%  |
| Net/wireless             | 2         | 7.14%   |
| Chipcard                 | 2         | 7.14%   |
| Bluetooth                | 2         | 7.14%   |
| Modem                    | 1         | 3.57%   |
| Card reader              | 1         | 3.57%   |

