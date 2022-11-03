Xubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 80

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | 970A-DS3P                   | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek    | K30AD_M31AD_M51AD_M32AD     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel      | DH61AG AAG23736-507         | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Hardkernel | ODROID-H2                   | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| MSI        | A320M PRO-VH                | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek    | Z97-P                       | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| Itautec    | ST 4273 ST-4273 Padrao 0... | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI        | MS-7309                     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek    | P8H67                       | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo     | ThinkCentre M58 7373A5G     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP         | 198E                        | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte   | G33M-DS2R                   | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek    | M5A97 EVO R2.0              | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell       | 0WR7PY A03                  | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| HP         | 1589                        | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| ASUSTek    | ET1612I                     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| MSI        | H170M PRO-VDH               | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| ASUSTek    | PRIME A320M-K               | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek    | PRIME A320M-K               | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| ASUSTek    | A68HM-K                     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| ASRock     | 960GC-GS FX                 | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| ASUSTek    | ET1612I                     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| ASUSTek    | PRIME H310M-D R2.0          | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek    | PRIME H310M-D R2.0          | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| ASUSTek    | Maximus VII HERO            | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell       | 0DR845                      | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| ASUSTek    | K30BD                       | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek    | H61M-C                      | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock     | N68-S3 UCC                  | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock     | N68-S3 UCC                  | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell       | 0DR845                      | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| ASUSTek    | PRIME A320M-K               | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell       | 03NVJ6 A01                  | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| ASUSTek    | PRIME A320M-C R2.0          | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek    | PRIME B560-PLUS             | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek    | PRIME B560-PLUS             | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| ASUSTek    | PRIME H270M-PLUS            | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| ASUSTek    | K30BD                       | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| HP         | 8433 11                     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| ASUSTek    | Z97-C                       | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte   | GA-MA790FXT-UD5P            | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| ASUSTek    | P8H67-M LE                  | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| ASUSTek    | TUF B450-PLUS GAMING        | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| Gigabyte   | AB350-Gaming-CF             | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte   | GA-78LMT-USB3 SEx           | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte   | GA-78LMT-USB3 SEx           | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines  | ET1350                      | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn    | 2ADA                        | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP         | 8591                        | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell       | 0YXT71 A00                  | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek    | K30AD_M31AD_M51AD_M32AD     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| MSI        | H310M PRO-M2 PLUS           | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| ASUSTek    | TUF Gaming B550M-E WIFI     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek    | PRIME A320M-K               | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| ASUSTek    | PRIME A320M-K               | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo     | SHARKBAY SDK0E50510 WIN     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek    | P8H67-M LE                  | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare     | IPX1800E2                   | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI        | PRO B660M-A DDR4            | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek    | PRIME B450M-A               | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| MSI        | A320M PRO-E                 | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| MSI        | PRO B660M-A DDR4            | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Dell       | 0GXM1W A00                  | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| MSI        | B450M-A PRO MAX             | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| MSI        | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| ASUSTek    | PRIME X470-PRO              | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Lenovo     | MAHOBAY NOK                 | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| ASUSTek    | X99-A II                    | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI        | MPG B550 GAMING EDGE WIF... | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Fujitsu    | D2917-A1 S26361-D2917-A1    | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| ASUSTek    | TUF B450M-PRO GAMING        | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| ASRock     | X570 Phantom Gaming 4       | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Acer       | Veriton M490G               | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| ASRock     | P55 Pro                     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| HP         | 09F8h                       | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.15.0-47-generic          | 9        | 12.86%  |
| 5.15.0-46-generic          | 9        | 12.86%  |
| 5.15.0-48-generic          | 6        | 8.57%   |
| 5.15.0-27-generic          | 6        | 8.57%   |
| 5.15.0-52-generic          | 5        | 7.14%   |
| 5.15.0-41-generic          | 5        | 7.14%   |
| 5.15.0-43-generic          | 4        | 5.71%   |
| 5.15.0-50-generic          | 3        | 4.29%   |
| 5.15.0-40-generic          | 3        | 4.29%   |
| 5.15.0-33-generic          | 2        | 2.86%   |
| 5.15.0-30-generic          | 2        | 2.86%   |
| 6.0.0                      | 1        | 1.43%   |
| 5.4.0-122-generic          | 1        | 1.43%   |
| 5.19.1                     | 1        | 1.43%   |
| 5.19.0-8.2-liquorix-amd64  | 1        | 1.43%   |
| 5.19.0-15.2-liquorix-amd64 | 1        | 1.43%   |
| 5.18.0                     | 1        | 1.43%   |
| 5.17.0-8-generic           | 1        | 1.43%   |
| 5.17.0-1003-oem            | 1        | 1.43%   |
| 5.15.0-50-lowlatency       | 1        | 1.43%   |
| 5.15.0-48-lowlatency       | 1        | 1.43%   |
| 5.15.0-46-lowlatency       | 1        | 1.43%   |
| 5.15.0-39-lowlatency       | 1        | 1.43%   |
| 5.15.0-39-generic          | 1        | 1.43%   |
| 5.15.0-37-generic          | 1        | 1.43%   |
| 5.15.0-25-generic          | 1        | 1.43%   |
| 5.15.0-18-generic          | 1        | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 59       | 88.06%  |
| 5.19.0  | 2        | 2.99%   |
| 5.17.0  | 2        | 2.99%   |
| 6.0.0   | 1        | 1.49%   |
| 5.4.0   | 1        | 1.49%   |
| 5.19.1  | 1        | 1.49%   |
| 5.18.0  | 1        | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 59       | 88.06%  |
| 5.19    | 3        | 4.48%   |
| 5.17    | 2        | 2.99%   |
| 6.0     | 1        | 1.49%   |
| 5.4     | 1        | 1.49%   |
| 5.18    | 1        | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 65       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 63       | 96.92%  |
| i3    | 1        | 1.54%   |
| GNOME | 1        | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 63       | 95.45%  |
| Tty  | 3        | 4.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 57       | 87.69%  |
| GDM3    | 4        | 6.15%   |
| Unknown | 4        | 6.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 18       | 27.69%  |
| fr_FR | 13       | 20%     |
| it_IT | 11       | 16.92%  |
| de_DE | 6        | 9.23%   |
| pt_BR | 4        | 6.15%   |
| en_CA | 4        | 6.15%   |
| sv_SE | 1        | 1.54%   |
| ru_RU | 1        | 1.54%   |
| nl_NL | 1        | 1.54%   |
| hu_HU | 1        | 1.54%   |
| es_CO | 1        | 1.54%   |
| es_AR | 1        | 1.54%   |
| en_ZA | 1        | 1.54%   |
| en_GB | 1        | 1.54%   |
| en_AU | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39       | 60%     |
| EFI  | 26       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 61       | 93.85%  |
| Zfs     | 1        | 1.54%   |
| Overlay | 1        | 1.54%   |
| Ext3    | 1        | 1.54%   |
| Btrfs   | 1        | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 34       | 51.52%  |
| Unknown | 23       | 34.85%  |
| MBR     | 9        | 13.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 75.38%  |
| Yes       | 16       | 24.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 60%     |
| Yes       | 26       | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 26       | 40%     |
| MSI                 | 10       | 15.38%  |
| Hewlett-Packard     | 5        | 7.69%   |
| Gigabyte Technology | 5        | 7.69%   |
| Dell                | 5        | 7.69%   |
| Lenovo              | 3        | 4.62%   |
| ASRock              | 3        | 4.62%   |
| PCWare              | 1        | 1.54%   |
| Itautec             | 1        | 1.54%   |
| Intel               | 1        | 1.54%   |
| Hardkernel          | 1        | 1.54%   |
| Fujitsu             | 1        | 1.54%   |
| Foxconn             | 1        | 1.54%   |
| eMachines           | 1        | 1.54%   |
| Acer                | 1        | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 4        | 6.15%   |
| Dell OptiPlex 7010                 | 3        | 4.62%   |
| MSI MS-7D43                        | 2        | 3.08%   |
| MSI MS-7C52                        | 2        | 3.08%   |
| ASUS K30AD_M31AD_M51AD             | 2        | 3.08%   |
| PCWare IPX1800E2                   | 1        | 1.54%   |
| MSI MS-7C91                        | 1        | 1.54%   |
| MSI MS-7C08                        | 1        | 1.54%   |
| MSI MS-7982                        | 1        | 1.54%   |
| MSI MS-7529                        | 1        | 1.54%   |
| MSI MS-7309                        | 1        | 1.54%   |
| MSI Hyrican PC A320M PRO-E         | 1        | 1.54%   |
| Lenovo ThinkCentre M83 10AM0010US  | 1        | 1.54%   |
| Lenovo ThinkCentre M72e 32675L2    | 1        | 1.54%   |
| Lenovo ThinkCentre M58 7373A5G     | 1        | 1.54%   |
| Itautec Infoway ST-4273            | 1        | 1.54%   |
| Intel DH61AG AAG23736-507          | 1        | 1.54%   |
| HP Z420 Workstation                | 1        | 1.54%   |
| HP Z1 Entry Tower G5               | 1        | 1.54%   |
| HP ProDesk 400 G2 MT (TPM DP)      | 1        | 1.54%   |
| HP Pavilion Desktop 590-p0xxx      | 1        | 1.54%   |
| HP Compaq dc7600 Small Form Factor | 1        | 1.54%   |
| Hardkernel ODROID-H2               | 1        | 1.54%   |
| Gigabyte GA-MA790FXT-UD5P          | 1        | 1.54%   |
| Gigabyte GA-78LMT-USB3 6.0         | 1        | 1.54%   |
| Gigabyte G33M-DS2R                 | 1        | 1.54%   |
| Gigabyte AB350-Gaming              | 1        | 1.54%   |
| Gigabyte 970A-DS3P                 | 1        | 1.54%   |
| Fujitsu CELSIUS W380               | 1        | 1.54%   |
| Foxconn p6-2466ef                  | 1        | 1.54%   |
| eMachines ET1352                   | 1        | 1.54%   |
| Dell OptiPlex 780                  | 1        | 1.54%   |
| Dell OptiPlex 755                  | 1        | 1.54%   |
| ASUS TUF Gaming B550M-PLUS         | 1        | 1.54%   |
| ASUS TUF Gaming B550M-E WIFI       | 1        | 1.54%   |
| ASUS TUF B450M-PRO GAMING          | 1        | 1.54%   |
| ASUS ROG STRIX B450-F GAMING II    | 1        | 1.54%   |
| ASUS ROG CROSSHAIR VIII DARK HERO  | 1        | 1.54%   |
| ASUS PRIME X470-PRO                | 1        | 1.54%   |
| ASUS PRIME H310M-D R2.0            | 1        | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 7        | 10.77%  |
| Dell OptiPlex             | 5        | 7.69%   |
| ASUS All                  | 4        | 6.15%   |
| Lenovo ThinkCentre        | 3        | 4.62%   |
| ASUS TUF                  | 3        | 4.62%   |
| MSI MS-7D43               | 2        | 3.08%   |
| MSI MS-7C52               | 2        | 3.08%   |
| ASUS ROG                  | 2        | 3.08%   |
| ASUS K30AD                | 2        | 3.08%   |
| PCWare IPX1800E2          | 1        | 1.54%   |
| MSI MS-7C91               | 1        | 1.54%   |
| MSI MS-7C08               | 1        | 1.54%   |
| MSI MS-7982               | 1        | 1.54%   |
| MSI MS-7529               | 1        | 1.54%   |
| MSI MS-7309               | 1        | 1.54%   |
| MSI Hyrican               | 1        | 1.54%   |
| Itautec Infoway           | 1        | 1.54%   |
| Intel DH61AG              | 1        | 1.54%   |
| HP Z420                   | 1        | 1.54%   |
| HP Z1                     | 1        | 1.54%   |
| HP ProDesk                | 1        | 1.54%   |
| HP Pavilion               | 1        | 1.54%   |
| HP Compaq                 | 1        | 1.54%   |
| Hardkernel ODROID-H2      | 1        | 1.54%   |
| Gigabyte GA-MA790FXT-UD5P | 1        | 1.54%   |
| Gigabyte GA-78LMT-USB3    | 1        | 1.54%   |
| Gigabyte G33M-DS2R        | 1        | 1.54%   |
| Gigabyte AB350-Gaming     | 1        | 1.54%   |
| Gigabyte 970A-DS3P        | 1        | 1.54%   |
| Fujitsu CELSIUS           | 1        | 1.54%   |
| Foxconn p6-2466ef         | 1        | 1.54%   |
| eMachines ET1352          | 1        | 1.54%   |
| ASUS P8H67-M              | 1        | 1.54%   |
| ASUS P8H67                | 1        | 1.54%   |
| ASUS M5A97                | 1        | 1.54%   |
| ASUS K30BD                | 1        | 1.54%   |
| ASUS H61M-C               | 1        | 1.54%   |
| ASUS ET1612I              | 1        | 1.54%   |
| ASUS A68HM-K              | 1        | 1.54%   |
| ASUS A0000001             | 1        | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 9        | 13.85%  |
| 2018 | 7        | 10.77%  |
| 2013 | 6        | 9.23%   |
| 2021 | 5        | 7.69%   |
| 2019 | 5        | 7.69%   |
| 2012 | 5        | 7.69%   |
| 2010 | 5        | 7.69%   |
| 2020 | 4        | 6.15%   |
| 2017 | 4        | 6.15%   |
| 2009 | 4        | 6.15%   |
| 2016 | 3        | 4.62%   |
| 2015 | 2        | 3.08%   |
| 2007 | 2        | 3.08%   |
| 2011 | 1        | 1.54%   |
| 2008 | 1        | 1.54%   |
| 2006 | 1        | 1.54%   |
| 2005 | 1        | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 65       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 63       | 96.92%  |
| Enabled  | 2        | 3.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 16       | 24.62%  |
| 4.01-8.0    | 14       | 21.54%  |
| 3.01-4.0    | 14       | 21.54%  |
| 8.01-16.0   | 9        | 13.85%  |
| 32.01-64.0  | 6        | 9.23%   |
| 1.01-2.0    | 3        | 4.62%   |
| 64.01-256.0 | 2        | 3.08%   |
| 24.01-32.0  | 1        | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 32       | 47.06%  |
| 3.01-4.0  | 14       | 20.59%  |
| 2.01-3.0  | 9        | 13.24%  |
| 4.01-8.0  | 6        | 8.82%   |
| 0.51-1.0  | 4        | 5.88%   |
| 8.01-16.0 | 2        | 2.94%   |
| 0.01-0.5  | 1        | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 37.88%  |
| 2      | 20       | 30.3%   |
| 3      | 12       | 18.18%  |
| 4      | 6        | 9.09%   |
| 5      | 2        | 3.03%   |
| 7      | 1        | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 37       | 56.06%  |
| No        | 29       | 43.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 65       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 60%     |
| Yes       | 26       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 75.38%  |
| Yes       | 16       | 24.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Italy        | 11       | 16.92%  |
| France       | 11       | 16.92%  |
| Germany      | 9        | 13.85%  |
| USA          | 6        | 9.23%   |
| Canada       | 4        | 6.15%   |
| Brazil       | 4        | 6.15%   |
| Sweden       | 3        | 4.62%   |
| Netherlands  | 2        | 3.08%   |
| UK           | 1        | 1.54%   |
| Taiwan       | 1        | 1.54%   |
| South Africa | 1        | 1.54%   |
| Russia       | 1        | 1.54%   |
| Portugal     | 1        | 1.54%   |
| Norway       | 1        | 1.54%   |
| Iran         | 1        | 1.54%   |
| Indonesia    | 1        | 1.54%   |
| Hungary      | 1        | 1.54%   |
| Guernsey     | 1        | 1.54%   |
| Guadeloupe   | 1        | 1.54%   |
| Colombia     | 1        | 1.54%   |
| Belgium      | 1        | 1.54%   |
| Australia    | 1        | 1.54%   |
| Argentina    | 1        | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Paris               | 5        | 7.58%   |
| Clermont-Ferrand    | 2        | 3.03%   |
| Biella              | 2        | 3.03%   |
| Berlin              | 2        | 3.03%   |
| Washington          | 1        | 1.52%   |
| Waarder             | 1        | 1.52%   |
| Vicenza             | 1        | 1.52%   |
| Västerås          | 1        | 1.52%   |
| Valparaiso de Goias | 1        | 1.52%   |
| Tourouvre           | 1        | 1.52%   |
| Toronto             | 1        | 1.52%   |
| The Hague           | 1        | 1.52%   |
| Teresina            | 1        | 1.52%   |
| Tehran              | 1        | 1.52%   |
| Taichung            | 1        | 1.52%   |
| Surrey              | 1        | 1.52%   |
| Stuttgart           | 1        | 1.52%   |
| St Peter Port       | 1        | 1.52%   |
| Sassari             | 1        | 1.52%   |
| Santiago de Cali    | 1        | 1.52%   |
| Salzgitter          | 1        | 1.52%   |
| Sainte-Rose         | 1        | 1.52%   |
| Rio de Janeiro      | 1        | 1.52%   |
| Rho                 | 1        | 1.52%   |
| Pieris              | 1        | 1.52%   |
| Peterborough        | 1        | 1.52%   |
| Pescara             | 1        | 1.52%   |
| Perth-Andover       | 1        | 1.52%   |
| Nettetal            | 1        | 1.52%   |
| Münster            | 1        | 1.52%   |
| Munich              | 1        | 1.52%   |
| Melbourne           | 1        | 1.52%   |
| Malmo               | 1        | 1.52%   |
| Lisbon              | 1        | 1.52%   |
| Linköping          | 1        | 1.52%   |
| Lavras              | 1        | 1.52%   |
| Lansdale            | 1        | 1.52%   |
| Lancaster           | 1        | 1.52%   |
| La Plata            | 1        | 1.52%   |
| Kamensk-Shakhtinsky | 1        | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 28     | 19.49%  |
| Seagate             | 21       | 30     | 17.8%   |
| Samsung Electronics | 15       | 20     | 12.71%  |
| Toshiba             | 10       | 10     | 8.47%   |
| Kingston            | 9        | 10     | 7.63%   |
| SanDisk             | 5        | 6      | 4.24%   |
| Hitachi             | 5        | 7      | 4.24%   |
| Crucial             | 4        | 7      | 3.39%   |
| PNY                 | 3        | 3      | 2.54%   |
| China               | 3        | 3      | 2.54%   |
| TEXTORM             | 2        | 2      | 1.69%   |
| Patriot             | 2        | 2      | 1.69%   |
| Maxtor              | 2        | 2      | 1.69%   |
| Intel               | 2        | 2      | 1.69%   |
| HGST                | 2        | 2      | 1.69%   |
| Unknown             | 1        | 1      | 0.85%   |
| SK hynix            | 1        | 1      | 0.85%   |
| Phison              | 1        | 6      | 0.85%   |
| OCZ                 | 1        | 1      | 0.85%   |
| Lexar               | 1        | 1      | 0.85%   |
| KingFast            | 1        | 1      | 0.85%   |
| Emtec               | 1        | 1      | 0.85%   |
| CHN25SATAS1         | 1        | 1      | 0.85%   |
| ASMT                | 1        | 1      | 0.85%   |
| Unknown             | 1        | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 3        | 2.19%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 2.19%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 1.46%   |
| Toshiba HDWD110 1TB              | 2        | 1.46%   |
| Toshiba DT01ACA200 2TB           | 2        | 1.46%   |
| TEXTORM BM5 240GB SSD            | 2        | 1.46%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.46%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 1.46%   |
| Seagate ST31000528AS 1TB         | 2        | 1.46%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.46%   |
| SanDisk SDSSDA240G 240GB         | 2        | 1.46%   |
| Samsung SSD 840 Series 120GB     | 2        | 1.46%   |
| Hitachi HDS721010CLA332 1TB      | 2        | 1.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.73%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.73%   |
| WDC WD800JD-75MSA3 80GB          | 1        | 0.73%   |
| WDC WD800JD-22MSA1 80GB          | 1        | 0.73%   |
| WDC WD740ADFD-00NLR5 74GB        | 1        | 0.73%   |
| WDC WD6400BPVT-80HXZT1 640GB     | 1        | 0.73%   |
| WDC WD6400BEVT-80A0RT0 640GB     | 1        | 0.73%   |
| WDC WD5000AVCS-612DY1 500GB      | 1        | 0.73%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.73%   |
| WDC WD5000AAKS-00UU3A0 500GB     | 1        | 0.73%   |
| WDC WD40PURX-78AKYY0 4TB         | 1        | 0.73%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 1        | 0.73%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.73%   |
| WDC WD3200AAKS-00L9A0 320GB      | 1        | 0.73%   |
| WDC WD3200AAJS-08L7A0 320GB      | 1        | 0.73%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.73%   |
| WDC WD2002FYPS-02W3B0 2TB        | 1        | 0.73%   |
| WDC WD1600JS-60MHB1 160GB        | 1        | 0.73%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 1        | 0.73%   |
| WDC WD10EZEX-60ZF5A0 1TB         | 1        | 0.73%   |
| WDC WD10EZEX-00ZF5A0 1TB         | 1        | 0.73%   |
| WDC WD10EAVS-00D7B1 1TB          | 1        | 0.73%   |
| WDC WD10EARS-22Y5B1 1TB          | 1        | 0.73%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 0.73%   |
| WDC WD10EARS-00MVWB0 1TB         | 1        | 0.73%   |
| Unknown CJTD4R  64GB             | 1        | 0.73%   |
| Toshiba TR200 240GB SSD          | 1        | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 26     | 33.33%  |
| Seagate             | 21       | 30     | 33.33%  |
| Toshiba             | 8        | 8      | 12.7%   |
| Hitachi             | 5        | 7      | 7.94%   |
| Samsung Electronics | 4        | 6      | 6.35%   |
| HGST                | 2        | 2      | 3.17%   |
| Maxtor              | 1        | 1      | 1.59%   |
| ASMT                | 1        | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 9      | 18.6%   |
| Kingston            | 7        | 7      | 16.28%  |
| SanDisk             | 5        | 6      | 11.63%  |
| Crucial             | 4        | 7      | 9.3%    |
| China               | 3        | 3      | 6.98%   |
| WDC                 | 2        | 2      | 4.65%   |
| Toshiba             | 2        | 2      | 4.65%   |
| TEXTORM             | 2        | 2      | 4.65%   |
| PNY                 | 2        | 2      | 4.65%   |
| Patriot             | 2        | 2      | 4.65%   |
| Intel               | 2        | 2      | 4.65%   |
| OCZ                 | 1        | 1      | 2.33%   |
| Maxtor              | 1        | 1      | 2.33%   |
| KingFast            | 1        | 1      | 2.33%   |
| Unknown             | 1        | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 49       | 81     | 50.52%  |
| SSD     | 35       | 48     | 36.08%  |
| NVMe    | 10       | 17     | 10.31%  |
| Unknown | 2        | 2      | 2.06%   |
| MMC     | 1        | 1      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 63       | 126    | 80.77%  |
| NVMe | 10       | 17     | 12.82%  |
| SAS  | 4        | 5      | 5.13%   |
| MMC  | 1        | 1      | 1.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 80     | 52.75%  |
| 0.51-1.0   | 26       | 30     | 28.57%  |
| 1.01-2.0   | 8        | 8      | 8.79%   |
| 3.01-4.0   | 6        | 7      | 6.59%   |
| 4.01-10.0  | 2        | 3      | 2.2%    |
| 2.01-3.0   | 1        | 1      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 17       | 26.15%  |
| 251-500        | 16       | 24.62%  |
| 1001-2000      | 12       | 18.46%  |
| 501-1000       | 8        | 12.31%  |
| More than 3000 | 5        | 7.69%   |
| 2001-3000      | 4        | 6.15%   |
| 21-50          | 1        | 1.54%   |
| 1-20           | 1        | 1.54%   |
| 51-100         | 1        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 17       | 25.76%  |
| 21-50          | 12       | 18.18%  |
| 101-250        | 11       | 16.67%  |
| 1-20           | 10       | 15.15%  |
| 51-100         | 5        | 7.58%   |
| More than 3000 | 3        | 4.55%   |
| 1001-2000      | 3        | 4.55%   |
| 501-1000       | 3        | 4.55%   |
| 2001-3000      | 2        | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 7.14%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 7.14%   |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 7.14%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 7.14%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 7.14%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 7.14%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 7.14%   |
| Seagate ST3750840AS 752GB         | 1        | 1      | 7.14%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 7.14%   |
| Samsung Electronics HM321HI 320GB | 1        | 1      | 7.14%   |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 7.14%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 7.14%   |
| Hitachi HCP725032GLA380 320GB     | 1        | 2      | 7.14%   |
| Crucial CT128MX100SSD1 128GB      | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 42.86%  |
| Seagate             | 2        | 3      | 14.29%  |
| Hitachi             | 2        | 3      | 14.29%  |
| Toshiba             | 1        | 1      | 7.14%   |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Maxtor              | 1        | 1      | 7.14%   |
| Crucial             | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 41.67%  |
| Seagate             | 2        | 3      | 16.67%  |
| Hitachi             | 2        | 3      | 16.67%  |
| Toshiba             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Maxtor              | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 14     | 90.91%  |
| SSD  | 1        | 2      | 9.09%   |

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
| Works    | 36       | 75     | 49.32%  |
| Detected | 27       | 58     | 36.99%  |
| Malfunc  | 10       | 16     | 13.7%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 39       | 47.56%  |
| AMD                          | 23       | 28.05%  |
| Samsung Electronics          | 4        | 4.88%   |
| Nvidia                       | 3        | 3.66%   |
| JMicron Technology           | 3        | 3.66%   |
| ASMedia Technology           | 3        | 3.66%   |
| Phison Electronics           | 2        | 2.44%   |
| Kingston Technology Company  | 2        | 2.44%   |
| VIA Technologies             | 1        | 1.22%   |
| SK hynix                     | 1        | 1.22%   |
| Shenzhen Longsys Electronics | 1        | 1.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14       | 12.39%  |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 5.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 4.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 3.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 3.54%   |
| AMD FCH SATA Controller D                                                      | 4        | 3.54%   |
| Nvidia MCP61 SATA Controller                                                   | 3        | 2.65%   |
| Nvidia MCP61 IDE                                                               | 3        | 2.65%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 2.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 2.65%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 2.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 1.77%   |
| Kingston Company A2000 NVMe SSD                                                | 2        | 1.77%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 1.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.77%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.77%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                          | 2        | 1.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 1.77%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 1.77%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 1.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 1.77%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.77%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 0.88%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.88%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                               | 1        | 0.88%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.88%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.88%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.88%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.88%   |
| JMicron JMB368 IDE controller                                                  | 1        | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 0.88%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 0.88%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 0.88%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 53       | 62.35%  |
| IDE  | 17       | 20%     |
| NVMe | 10       | 11.76%  |
| RAID | 4        | 4.71%   |
| SAS  | 1        | 1.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 39       | 60%     |
| AMD    | 26       | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor     | 3        | 4.55%   |
| Intel Core i3-3240 CPU @ 3.40GHz      | 2        | 3.03%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz  | 2        | 3.03%   |
| Intel 12th Gen Core i7-12700          | 2        | 3.03%   |
| AMD Ryzen 7 2700 Eight-Core Processor | 2        | 3.03%   |
| AMD FX-6300 Six-Core Processor        | 2        | 3.03%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz    | 1        | 1.52%   |
| Intel Pentium 4 CPU 3.00GHz           | 1        | 1.52%   |
| Intel Core i7-9700 CPU @ 3.00GHz      | 1        | 1.52%   |
| Intel Core i7-6800K CPU @ 3.40GHz     | 1        | 1.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz     | 1        | 1.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz      | 1        | 1.52%   |
| Intel Core i7-4771 CPU @ 3.50GHz      | 1        | 1.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz      | 1        | 1.52%   |
| Intel Core i7-2600K CPU @ 3.40GHz     | 1        | 1.52%   |
| Intel Core i7-2600 CPU @ 3.40GHz      | 1        | 1.52%   |
| Intel Core i7 CPU 870 @ 2.93GHz       | 1        | 1.52%   |
| Intel Core i5-9400 CPU @ 2.90GHz      | 1        | 1.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz      | 1        | 1.52%   |
| Intel Core i5-4690K CPU @ 3.50GHz     | 1        | 1.52%   |
| Intel Core i5-4690 CPU @ 3.50GHz      | 1        | 1.52%   |
| Intel Core i5-4590S CPU @ 3.00GHz     | 1        | 1.52%   |
| Intel Core i5-3570 CPU @ 3.40GHz      | 1        | 1.52%   |
| Intel Core i5-3470T CPU @ 2.90GHz     | 1        | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz      | 1        | 1.52%   |
| Intel Core i5-3350P CPU @ 3.10GHz     | 1        | 1.52%   |
| Intel Core i5-2400S CPU @ 2.50GHz     | 1        | 1.52%   |
| Intel Core i5-10400 CPU @ 2.90GHz     | 1        | 1.52%   |
| Intel Core i5 CPU 760 @ 2.80GHz       | 1        | 1.52%   |
| Intel Core i5 CPU 660 @ 3.33GHz       | 1        | 1.52%   |
| Intel Core i3-9100 CPU @ 3.60GHz      | 1        | 1.52%   |
| Intel Core i3-7100 CPU @ 3.90GHz      | 1        | 1.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz      | 1        | 1.52%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz | 1        | 1.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz  | 1        | 1.52%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz  | 1        | 1.52%   |
| Intel Celeron J4105 CPU @ 1.50GHz     | 1        | 1.52%   |
| Intel Celeron CPU J1800 @ 2.41GHz     | 1        | 1.52%   |
| Intel Celeron CPU 847 @ 1.10GHz       | 1        | 1.52%   |
| AMD Sempron 3850 APU with Radeon R3   | 1        | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 13       | 19.7%   |
| Intel Core i7     | 9        | 13.64%  |
| AMD Ryzen 5       | 9        | 13.64%  |
| Intel Core i3     | 5        | 7.58%   |
| Intel Core 2 Duo  | 4        | 6.06%   |
| Intel Celeron     | 3        | 4.55%   |
| AMD Ryzen 9       | 3        | 4.55%   |
| Other             | 2        | 3.03%   |
| AMD Ryzen 7       | 2        | 3.03%   |
| AMD Ryzen 3       | 2        | 3.03%   |
| AMD FX            | 2        | 3.03%   |
| AMD Athlon II X2  | 2        | 3.03%   |
| Intel Xeon        | 1        | 1.52%   |
| Intel Pentium 4   | 1        | 1.52%   |
| Intel Core 2 Quad | 1        | 1.52%   |
| AMD Sempron       | 1        | 1.52%   |
| AMD Ryzen 7 PRO   | 1        | 1.52%   |
| AMD Phenom II X4  | 1        | 1.52%   |
| AMD Athlon II     | 1        | 1.52%   |
| AMD Athlon 64 X2  | 1        | 1.52%   |
| AMD Athlon        | 1        | 1.52%   |
| AMD A10           | 1        | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 27       | 40.91%  |
| 2      | 17       | 25.76%  |
| 6      | 9        | 13.64%  |
| 12     | 4        | 6.06%   |
| 8      | 4        | 6.06%   |
| 3      | 2        | 3.03%   |
| 1      | 2        | 3.03%   |
| 16     | 1        | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 65       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 38       | 58.46%  |
| 1      | 27       | 41.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 32.31%  |
| 0x306c3    | 4        | 6.15%   |
| 0x306a9    | 4        | 6.15%   |
| 0x206a7    | 4        | 6.15%   |
| 0x08701021 | 3        | 4.62%   |
| 0x0800820d | 3        | 4.62%   |
| 0x90672    | 2        | 3.08%   |
| 0x106e5    | 2        | 3.08%   |
| 0x10676    | 2        | 3.08%   |
| 0x06000852 | 2        | 3.08%   |
| 0x010000c8 | 2        | 3.08%   |
| 0xa0653    | 1        | 1.54%   |
| 0x906ed    | 1        | 1.54%   |
| 0x906ea    | 1        | 1.54%   |
| 0x706a1    | 1        | 1.54%   |
| 0x206d7    | 1        | 1.54%   |
| 0x20652    | 1        | 1.54%   |
| 0x1067a    | 1        | 1.54%   |
| 0x0a50000c | 1        | 1.54%   |
| 0x0a201016 | 1        | 1.54%   |
| 0x08701013 | 1        | 1.54%   |
| 0x08108109 | 1        | 1.54%   |
| 0x08101016 | 1        | 1.54%   |
| 0x08001138 | 1        | 1.54%   |
| 0x08001137 | 1        | 1.54%   |
| 0x0700010f | 1        | 1.54%   |
| 0x010000c7 | 1        | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 7        | 10.61%  |
| Zen 2            | 6        | 9.09%   |
| SandyBridge      | 6        | 9.09%   |
| IvyBridge        | 6        | 9.09%   |
| Zen+             | 5        | 7.58%   |
| Zen              | 4        | 6.06%   |
| Penryn           | 4        | 6.06%   |
| KabyLake         | 4        | 6.06%   |
| K10              | 4        | 6.06%   |
| Zen 3            | 3        | 4.55%   |
| Piledriver       | 3        | 4.55%   |
| Nehalem          | 2        | 3.03%   |
| Alderlake Hybrid | 2        | 3.03%   |
| Westmere         | 1        | 1.52%   |
| Skylake          | 1        | 1.52%   |
| Silvermont       | 1        | 1.52%   |
| NetBurst         | 1        | 1.52%   |
| K8 Hammer        | 1        | 1.52%   |
| Jaguar           | 1        | 1.52%   |
| Goldmont plus    | 1        | 1.52%   |
| Core             | 1        | 1.52%   |
| CometLake        | 1        | 1.52%   |
| Broadwell        | 1        | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 27       | 38.03%  |
| Intel  | 26       | 36.62%  |
| AMD    | 18       | 25.35%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 7.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 5.63%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 4.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 4.23%   |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 2.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.82%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 2.82%   |
| Intel AlderLake-S GT1                                                       | 2        | 2.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.82%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 2.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.82%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.41%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.41%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.41%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 1.41%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 1.41%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.41%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.41%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.41%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.41%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 1.41%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.41%   |
| Nvidia GK104 [GeForce GTX 690]                                              | 1        | 1.41%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.41%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.41%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.41%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.41%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.41%   |
| Intel HD Graphics 630                                                       | 1        | 1.41%   |
| Intel HD Graphics 530                                                       | 1        | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.41%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.41%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.41%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.41%   |
| AMD Trinity [Radeon HD 7660D]                                               | 1        | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 23       | 35.38%  |
| 1 x Intel      | 21       | 32.31%  |
| 1 x AMD        | 17       | 26.15%  |
| Intel + Nvidia | 3        | 4.62%   |
| AMD + Nvidia   | 1        | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 72.31%  |
| Proprietary | 15       | 23.08%  |
| Unknown     | 3        | 4.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 55.38%  |
| 1.01-2.0   | 10       | 15.38%  |
| 0.51-1.0   | 7        | 10.77%  |
| 3.01-4.0   | 5        | 7.69%   |
| 0.01-0.5   | 4        | 6.15%   |
| 7.01-8.0   | 1        | 1.54%   |
| 5.01-6.0   | 1        | 1.54%   |
| 8.01-16.0  | 1        | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Hewlett-Packard         | 12       | 18.18%  |
| Samsung Electronics     | 10       | 15.15%  |
| Dell                    | 7        | 10.61%  |
| Acer                    | 5        | 7.58%   |
| ViewSonic               | 4        | 6.06%   |
| Iiyama                  | 4        | 6.06%   |
| Goldstar                | 4        | 6.06%   |
| AOC                     | 3        | 4.55%   |
| Philips                 | 2        | 3.03%   |
| Ancor Communications    | 2        | 3.03%   |
| ___                     | 1        | 1.52%   |
| Vestel Elektronik       | 1        | 1.52%   |
| Toshiba                 | 1        | 1.52%   |
| TEO                     | 1        | 1.52%   |
| TCL                     | 1        | 1.52%   |
| MAG                     | 1        | 1.52%   |
| LG Electronics          | 1        | 1.52%   |
| Lenovo                  | 1        | 1.52%   |
| Fujitsu Siemens         | 1        | 1.52%   |
| Denver                  | 1        | 1.52%   |
| Chi Mei Optoelectronics | 1        | 1.52%   |
| BenQ                    | 1        | 1.52%   |
| Unknown                 | 1        | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch             | 2        | 2.99%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                     | 1        | 1.49%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 1        | 1.49%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch             | 1        | 1.49%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                 | 1        | 1.49%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch           | 1        | 1.49%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 1.49%   |
| Toshiba TV TSB0109 1920x1080 1594x900mm 72.1-inch                      | 1        | 1.49%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                        | 1        | 1.49%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                       | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                       | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch   | 1        | 1.49%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch      | 1        | 1.49%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch     | 1        | 1.49%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch      | 1        | 1.49%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 1.49%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch       | 1        | 1.49%   |
| Samsung Electronics LCD Monitor SAM07BB 1360x768 410x256mm 19.0-inch   | 1        | 1.49%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1        | 1.49%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                | 1        | 1.49%   |
| Philips 221TE PHLC062 1920x1080 476x268mm 21.5-inch                    | 1        | 1.49%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                     | 1        | 1.49%   |
| MAG Monitor MAG1901 1280x1024 320x206mm 15.0-inch                      | 1        | 1.49%   |
| LG Electronics LCD Monitor E2442 1920x1080                             | 1        | 1.49%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                   | 1        | 1.49%   |
| Iiyama X2483_2480-DP IVM6129 1920x1080 527x296mm 23.8-inch             | 1        | 1.49%   |
| Iiyama PL2780H IVM6609 1920x1080 600x340mm 27.2-inch                   | 1        | 1.49%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                    | 1        | 1.49%   |
| Iiyama PL1908W IVM483D 1680x1050 408x255mm 18.9-inch                   | 1        | 1.49%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch            | 1        | 1.49%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch             | 1        | 1.49%   |
| Hewlett-Packard LCD Monitor L185b 1024x768                             | 1        | 1.49%   |
| Hewlett-Packard L1706 HWP265C 1280x1024 337x270mm 17.0-inch            | 1        | 1.49%   |
| Hewlett-Packard E240 HWP3264 1920x1080 530x300mm 24.0-inch             | 1        | 1.49%   |
| Hewlett-Packard E201 HWP305F 1600x900 443x249mm 20.0-inch              | 1        | 1.49%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch     | 1        | 1.49%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch              | 1        | 1.49%   |
| Hewlett-Packard 24y HPN3504 1920x1080 530x300mm 24.0-inch              | 1        | 1.49%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch              | 1        | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 42.86%  |
| 1280x1024 (SXGA)   | 7        | 11.11%  |
| 1440x900 (WXGA+)   | 6        | 9.52%   |
| 1366x768 (WXGA)    | 6        | 9.52%   |
| 3840x2160 (4K)     | 3        | 4.76%   |
| 3840x1600          | 2        | 3.17%   |
| 1920x1200 (WUXGA)  | 2        | 3.17%   |
| 1680x1050 (WSXGA+) | 2        | 3.17%   |
| 1600x900 (HD+)     | 2        | 3.17%   |
| 2560x1600          | 1        | 1.59%   |
| 2560x1440 (QHD)    | 1        | 1.59%   |
| 1920x540           | 1        | 1.59%   |
| 1600x1200          | 1        | 1.59%   |
| 1360x768           | 1        | 1.59%   |
| 1024x768 (XGA)     | 1        | 1.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 10       | 14.93%  |
| 23      | 8        | 11.94%  |
| 19      | 7        | 10.45%  |
| 17      | 6        | 8.96%   |
| 27      | 5        | 7.46%   |
| 21      | 5        | 7.46%   |
| 18      | 5        | 7.46%   |
| 20      | 3        | 4.48%   |
| Unknown | 3        | 4.48%   |
| 37      | 2        | 2.99%   |
| 31      | 2        | 2.99%   |
| 26      | 2        | 2.99%   |
| 15      | 2        | 2.99%   |
| 84      | 1        | 1.49%   |
| 72      | 1        | 1.49%   |
| 32      | 1        | 1.49%   |
| 30      | 1        | 1.49%   |
| 25      | 1        | 1.49%   |
| 22      | 1        | 1.49%   |
| 6       | 1        | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 38.46%  |
| 401-500     | 20       | 30.77%  |
| 301-350     | 8        | 12.31%  |
| 601-700     | 3        | 4.62%   |
| Unknown     | 3        | 4.62%   |
| 801-900     | 2        | 3.08%   |
| 1501-2000   | 2        | 3.08%   |
| 701-800     | 1        | 1.54%   |
| 101-200     | 1        | 1.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 36       | 58.06%  |
| 16/10   | 14       | 22.58%  |
| 5/4     | 6        | 9.68%   |
| 4/3     | 2        | 3.23%   |
| 21/9    | 2        | 3.23%   |
| Unknown | 2        | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 27.69%  |
| 151-200        | 14       | 21.54%  |
| 141-150        | 10       | 15.38%  |
| 301-350        | 6        | 9.23%   |
| 351-500        | 4        | 6.15%   |
| 251-300        | 4        | 6.15%   |
| Unknown        | 3        | 4.62%   |
| More than 1000 | 2        | 3.08%   |
| 101-110        | 2        | 3.08%   |
| 1-40           | 1        | 1.54%   |
| 501-1000       | 1        | 1.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 47       | 74.6%   |
| 101-120       | 10       | 15.87%  |
| Unknown       | 3        | 4.76%   |
| More than 240 | 1        | 1.59%   |
| 1-50          | 1        | 1.59%   |
| 121-160       | 1        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 84.62%  |
| 2     | 5        | 7.69%   |
| 0     | 3        | 4.62%   |
| 3     | 2        | 3.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 40       | 44.44%  |
| Intel                           | 28       | 31.11%  |
| Qualcomm Atheros                | 5        | 5.56%   |
| Ralink Technology               | 3        | 3.33%   |
| Nvidia                          | 3        | 3.33%   |
| D-Link System                   | 2        | 2.22%   |
| TRENDnet                        | 1        | 1.11%   |
| TP-Link                         | 1        | 1.11%   |
| Ralink                          | 1        | 1.11%   |
| Qualcomm Atheros Communications | 1        | 1.11%   |
| NetGear                         | 1        | 1.11%   |
| Microchip Technology            | 1        | 1.11%   |
| Dell                            | 1        | 1.11%   |
| Broadcom Limited                | 1        | 1.11%   |
| Broadcom                        | 1        | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 32       | 32.65%  |
| Realtek RTL8125 2.5GbE Controller                                              | 6        | 6.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5        | 5.1%    |
| Intel Wi-Fi 6 AX200                                                            | 4        | 4.08%   |
| Intel I211 Gigabit Network Connection                                          | 4        | 4.08%   |
| Nvidia MCP61 Ethernet                                                          | 3        | 3.06%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 3.06%   |
| Intel Ethernet Connection I217-V                                               | 2        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                                           | 2        | 2.04%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 2.04%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]     | 1        | 1.02%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                            | 1        | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 1.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 1.02%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 1.02%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 1.02%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 1        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 1.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 1.02%   |
| Ralink RT2770 Wireless Adapter                                                 | 1        | 1.02%   |
| Ralink RT2501/RT2573 Wireless Adapter                                          | 1        | 1.02%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 1.02%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1        | 1.02%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 1.02%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 1        | 1.02%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1        | 1.02%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                            | 1        | 1.02%   |
| Microchip TrueRNG                                                              | 1        | 1.02%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 1.02%   |
| Intel Ethernet Connection (14) I219-V                                          | 1        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1        | 1.02%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 1.02%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 1.02%   |
| Intel 82578DC Gigabit Network Connection                                       | 1        | 1.02%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1        | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 6        | 22.22%  |
| Qualcomm Atheros                | 5        | 18.52%  |
| Intel                           | 5        | 18.52%  |
| Ralink Technology               | 3        | 11.11%  |
| TRENDnet                        | 1        | 3.7%    |
| TP-Link                         | 1        | 3.7%    |
| Ralink                          | 1        | 3.7%    |
| Qualcomm Atheros Communications | 1        | 3.7%    |
| NetGear                         | 1        | 3.7%    |
| Dell                            | 1        | 3.7%    |
| D-Link System                   | 1        | 3.7%    |
| Broadcom                        | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 4        | 14.81%  |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]        | 1        | 3.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 1        | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 3.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 3.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 3.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 3.7%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 1        | 3.7%    |
| Ralink RT2770 Wireless Adapter                                                    | 1        | 3.7%    |
| Ralink RT2501/RT2573 Wireless Adapter                                             | 1        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                                   | 1        | 3.7%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                            | 1        | 3.7%    |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 3.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 3.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 3.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                  | 1        | 3.7%    |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]    | 1        | 3.7%    |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                               | 1        | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 1        | 3.7%    |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]             | 1        | 3.7%    |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 3.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 38       | 55.88%  |
| Intel                 | 25       | 36.76%  |
| Nvidia                | 3        | 4.41%   |
| D-Link System         | 1        | 1.47%   |
| Broadcom Limited      | 1        | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 45.71%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 8.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 7.14%   |
| Intel I211 Gigabit Network Connection                             | 4        | 5.71%   |
| Nvidia MCP61 Ethernet                                             | 3        | 4.29%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 4.29%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.43%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.43%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.43%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.43%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.43%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 70.65%  |
| WiFi     | 26       | 28.26%  |
| Modem    | 1        | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 77.94%  |
| WiFi     | 15       | 22.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 67.69%  |
| 2     | 19       | 29.23%  |
| 3     | 2        | 3.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 60%     |
| Yes  | 26       | 40%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 6        | 37.5%   |
| Intel                   | 5        | 31.25%  |
| Broadcom                | 2        | 12.5%   |
| Realtek Semiconductor   | 1        | 6.25%   |
| IMC Networks            | 1        | 6.25%   |
| Fujitsu                 | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 37.5%   |
| Intel AX200 Bluetooth                               | 4        | 25%     |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.25%   |
| IMC Networks Bluetooth Radio                        | 1        | 6.25%   |
| Fujitsu Bluetooth Device                            | 1        | 6.25%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 39       | 37.5%   |
| AMD                         | 27       | 25.96%  |
| Nvidia                      | 26       | 25%     |
| C-Media Electronics         | 3        | 2.88%   |
| SAVITECH                    | 1        | 0.96%   |
| Samson Technologies         | 1        | 0.96%   |
| Medeli Electronics          | 1        | 0.96%   |
| MAG Technology              | 1        | 0.96%   |
| Logitech                    | 1        | 0.96%   |
| Lenovo                      | 1        | 0.96%   |
| Kingston Technology         | 1        | 0.96%   |
| FiiO Electronics Technology | 1        | 0.96%   |
| Corsair                     | 1        | 0.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 5.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 5.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 5.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 4.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 4.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 3.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 3.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 3.39%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 2.54%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 2.54%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.54%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.69%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2        | 1.69%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.69%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.69%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 1.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.69%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.69%   |
| SAVITECH PHIREE D1                                                         | 1        | 0.85%   |
| Samson Technologies Q1U dynamic microphone                                 | 1        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.85%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.85%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.85%   |
| Medeli Electronics USB Audio Device                                        | 1        | 0.85%   |
| MAG Technology ARC AMP DAC                                                 | 1        | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 10       | 19.61%  |
| Unknown             | 9        | 17.65%  |
| Samsung Electronics | 8        | 15.69%  |
| Crucial             | 5        | 9.8%    |
| Corsair             | 5        | 9.8%    |
| SK hynix            | 4        | 7.84%   |
| G.Skill             | 3        | 5.88%   |
| Nanya Technology    | 2        | 3.92%   |
| Unknown (ABCD)      | 1        | 1.96%   |
| Ramaxel Technology  | 1        | 1.96%   |
| GLOWAY              | 1        | 1.96%   |
| ASint Technology    | 1        | 1.96%   |
| Unknown             | 1        | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s         | 2        | 3.64%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 1        | 1.82%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 1.82%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 1.82%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 1.82%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1.82%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                    | 1        | 1.82%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 1.82%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s    | 1        | 1.82%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s        | 1        | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s | 1        | 1.82%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                  | 1        | 1.82%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.82%   |
| SK hynix RAM HMT351U7EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.82%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 1        | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1        | 1.82%   |
| Samsung RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 1.82%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s        | 1        | 1.82%   |
| Samsung RAM M391B5773DH0-CK0 2GB DIMM DDR3 1600MT/s          | 1        | 1.82%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s       | 1        | 1.82%   |
| Samsung RAM M378B5173EB0-CK0 4096MB DIMM DDR3 1600MT/s       | 1        | 1.82%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.82%   |
| Samsung RAM M378B5173BH0-CH9 4GB DIMM DDR3 1867MT/s          | 1        | 1.82%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s          | 1        | 1.82%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s        | 1        | 1.82%   |
| Nanya RAM M2F4G64CB88B4N-DI 4GB DIMM DDR3 1600MT/s           | 1        | 1.82%   |
| Nanya RAM 16G3200CL16RGB 16GB DIMM DDR4 3400MT/s             | 1        | 1.82%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s               | 1        | 1.82%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 1        | 1.82%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 1        | 1.82%   |
| Kingston RAM 99U5702-085.A00G 8GB DIMM DDR4 2666MT/s         | 1        | 1.82%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 1.82%   |
| Kingston RAM 99U5471-002.A01LF 2GB DIMM DDR3 1334MT/s        | 1        | 1.82%   |
| Kingston RAM 99U5471-002.A00LF 2GB DIMM DDR3 1334MT/s        | 1        | 1.82%   |
| Kingston RAM 99U5471-001.A00LF 2GB DIMM DDR3 1334MT/s        | 1        | 1.82%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3600MT/s        | 1        | 1.82%   |
| Kingston RAM 9905584-014.A 4GB DIMM DDR3 1600MT/s            | 1        | 1.82%   |
| Kingston RAM 9905471-001.A01LF 2GB DIMM 1600MT/s             | 1        | 1.82%   |
| GLOWAY RAM TAC4U3200E16081C 8GB DIMM DDR4 2400MT/s           | 1        | 1.82%   |
| G.Skill RAM F4-3600C16-32GTRS 32GB DIMM DDR4 3600MT/s        | 1        | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 19       | 43.18%  |
| DDR3    | 19       | 43.18%  |
| SDRAM   | 2        | 4.55%   |
| Unknown | 2        | 4.55%   |
| LPDDR4  | 1        | 2.27%   |
| DDR2    | 1        | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 43       | 97.73%  |
| SODIMM | 1        | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 35.42%  |
| 4096  | 14       | 29.17%  |
| 2048  | 8        | 16.67%  |
| 16384 | 6        | 12.5%   |
| 32768 | 2        | 4.17%   |
| 1024  | 1        | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 25%     |
| 2667    | 6        | 12.5%   |
| 1333    | 6        | 12.5%   |
| 3600    | 4        | 8.33%   |
| 2400    | 3        | 6.25%   |
| 3000    | 2        | 4.17%   |
| 2666    | 2        | 4.17%   |
| 1867    | 2        | 4.17%   |
| Unknown | 2        | 4.17%   |
| 3400    | 1        | 2.08%   |
| 3200    | 1        | 2.08%   |
| 3020    | 1        | 2.08%   |
| 2800    | 1        | 2.08%   |
| 2000    | 1        | 2.08%   |
| 1800    | 1        | 2.08%   |
| 1334    | 1        | 2.08%   |
| 1067    | 1        | 2.08%   |
| 1066    | 1        | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 75%     |
| Canon           | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP DeskJet D1360            | 1        | 25%     |
| HP DeskJet 840c             | 1        | 25%     |
| HP Deskjet 3070 B611 series | 1        | 25%     |
| Canon TS3500 series         | 1        | 25%     |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 4        | 26.67%  |
| Microsoft                   | 2        | 13.33%  |
| Xiaomi                      | 1        | 6.67%   |
| Samsung Electronics         | 1        | 6.67%   |
| Realtek Semiconductor       | 1        | 6.67%   |
| Microdia                    | 1        | 6.67%   |
| KYE Systems (Mouse Systems) | 1        | 6.67%   |
| IMC Networks                | 1        | 6.67%   |
| Guillemot                   | 1        | 6.67%   |
| Creative Technology         | 1        | 6.67%   |
| Apple                       | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 2        | 13.33%  |
| Xiaomi Mi/Redmi series (PTP)             | 1        | 6.67%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 6.67%   |
| Realtek Streaming Webcam                 | 1        | 6.67%   |
| Microsoft MicrosoftÂ LifeCam Studio     | 1        | 6.67%   |
| Microsoft LifeCam VX-2000                | 1        | 6.67%   |
| Microdia Sonix USB 2.0 Camera            | 1        | 6.67%   |
| Logitech C922 Pro Stream Webcam          | 1        | 6.67%   |
| Logitech BRIO Ultra HD Webcam            | 1        | 6.67%   |
| KYE Systems (Mouse Systems) iSlim 2020AF | 1        | 6.67%   |
| IMC Networks USB2.0 UVC HD Webcam        | 1        | 6.67%   |
| Guillemot Hercules Dualpix Exchange      | 1        | 6.67%   |
| Creative Live! Cam Sync 1080p            | 1        | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE                | 1        | 6.67%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| In Focus Systems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| In Focus Systems EMV Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 56       | 84.85%  |
| 1     | 6        | 9.09%   |
| 2     | 3        | 4.55%   |
| 3     | 1        | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 7        | 53.85%  |
| Camera                | 2        | 15.38%  |
| Unassigned class      | 1        | 7.69%   |
| Sound                 | 1        | 7.69%   |
| Multimedia controller | 1        | 7.69%   |
| Chipcard              | 1        | 7.69%   |

