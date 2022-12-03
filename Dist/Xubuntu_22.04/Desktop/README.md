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

Total: 101

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | P8H61-M LX3                 | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| MSI        | PRO Z690-A DDR4             | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI        | PRO Z690-A DDR4             | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock     | H270M-ITX/ac                | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek    | TUF B450-PLUS GAMING        | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Gigabyte   | A320M-S2H-CF                | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| ASUSTek    | M4A88TD-M/USB3              | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST  | X99-RS9 V2.0                | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI        | PRO H610M-B DDR4            | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP         | 1495                        | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek    | P8H61-M LX PLUS R2.0        | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| Dell       | 0M5DCD A00                  | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| MSI        | A320M PRO-VH                | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| MSI        | PRO H610M-B DDR4            | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI        | X370 GAMING PRO CARBON      | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Intel      | D525MW AAE93082-401         | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte   | Z77-DS3H                    | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Lenovo     | ThinkCentre M90p 3282A9G    | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo     | ThinkCentre M90p 3282A9G    | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| HP         | 8054                        | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek    | P8H61-M LX PLUS R2.0        | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
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
| 5.15.0-52-generic          | 15       | 17.24%  |
| 5.15.0-47-generic          | 9        | 10.34%  |
| 5.15.0-46-generic          | 9        | 10.34%  |
| 5.15.0-48-generic          | 6        | 6.9%    |
| 5.15.0-27-generic          | 6        | 6.9%    |
| 5.15.0-43-generic          | 5        | 5.75%   |
| 5.15.0-41-generic          | 5        | 5.75%   |
| 5.15.0-53-generic          | 4        | 4.6%    |
| 5.15.0-50-generic          | 4        | 4.6%    |
| 5.15.0-40-generic          | 3        | 3.45%   |
| 5.15.0-33-generic          | 2        | 2.3%    |
| 5.15.0-30-generic          | 2        | 2.3%    |
| 6.0.0                      | 1        | 1.15%   |
| 5.4.0-122-generic          | 1        | 1.15%   |
| 5.19.1                     | 1        | 1.15%   |
| 5.19.0-8.2-liquorix-amd64  | 1        | 1.15%   |
| 5.19.0-15.2-liquorix-amd64 | 1        | 1.15%   |
| 5.18.0                     | 1        | 1.15%   |
| 5.17.0-8-generic           | 1        | 1.15%   |
| 5.17.0-1003-oem            | 1        | 1.15%   |
| 5.15.0-53-lowlatency       | 1        | 1.15%   |
| 5.15.0-50-lowlatency       | 1        | 1.15%   |
| 5.15.0-48-lowlatency       | 1        | 1.15%   |
| 5.15.0-46-lowlatency       | 1        | 1.15%   |
| 5.15.0-39-lowlatency       | 1        | 1.15%   |
| 5.15.0-39-generic          | 1        | 1.15%   |
| 5.15.0-37-generic          | 1        | 1.15%   |
| 5.15.0-25-generic          | 1        | 1.15%   |
| 5.15.0-18-generic          | 1        | 1.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 75       | 90.36%  |
| 5.19.0  | 2        | 2.41%   |
| 5.17.0  | 2        | 2.41%   |
| 6.0.0   | 1        | 1.2%    |
| 5.4.0   | 1        | 1.2%    |
| 5.19.1  | 1        | 1.2%    |
| 5.18.0  | 1        | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 75       | 90.36%  |
| 5.19    | 3        | 3.61%   |
| 5.17    | 2        | 2.41%   |
| 6.0     | 1        | 1.2%    |
| 5.4     | 1        | 1.2%    |
| 5.18    | 1        | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 81       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 79       | 97.53%  |
| i3    | 1        | 1.23%   |
| GNOME | 1        | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 80       | 96.39%  |
| Tty  | 3        | 3.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 71       | 87.65%  |
| GDM3    | 6        | 7.41%   |
| Unknown | 4        | 4.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 25       | 30.86%  |
| fr_FR | 16       | 19.75%  |
| it_IT | 12       | 14.81%  |
| de_DE | 8        | 9.88%   |
| pt_BR | 5        | 6.17%   |
| en_CA | 4        | 4.94%   |
| en_GB | 2        | 2.47%   |
| sv_SE | 1        | 1.23%   |
| ru_RU | 1        | 1.23%   |
| nl_NL | 1        | 1.23%   |
| hu_HU | 1        | 1.23%   |
| fr_CA | 1        | 1.23%   |
| es_CO | 1        | 1.23%   |
| es_AR | 1        | 1.23%   |
| en_ZA | 1        | 1.23%   |
| en_AU | 1        | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 51       | 62.2%   |
| EFI  | 31       | 37.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 75       | 92.59%  |
| Zfs     | 2        | 2.47%   |
| Btrfs   | 2        | 2.47%   |
| Overlay | 1        | 1.23%   |
| Ext3    | 1        | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 48       | 57.83%  |
| Unknown | 23       | 27.71%  |
| MBR     | 12       | 14.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 75.31%  |
| Yes       | 20       | 24.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 60.49%  |
| Yes       | 32       | 39.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 29       | 35.8%   |
| MSI                 | 14       | 17.28%  |
| Hewlett-Packard     | 7        | 8.64%   |
| Gigabyte Technology | 7        | 8.64%   |
| Dell                | 6        | 7.41%   |
| Lenovo              | 4        | 4.94%   |
| ASRock              | 4        | 4.94%   |
| Intel               | 2        | 2.47%   |
| PCWare              | 1        | 1.23%   |
| MACHINIST           | 1        | 1.23%   |
| Itautec             | 1        | 1.23%   |
| Hardkernel          | 1        | 1.23%   |
| Fujitsu             | 1        | 1.23%   |
| Foxconn             | 1        | 1.23%   |
| eMachines           | 1        | 1.23%   |
| Acer                | 1        | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 4        | 4.94%   |
| Dell OptiPlex 7010                 | 3        | 3.7%    |
| MSI MS-7D46                        | 2        | 2.47%   |
| MSI MS-7D43                        | 2        | 2.47%   |
| MSI MS-7C52                        | 2        | 2.47%   |
| ASUS K30AD_M31AD_M51AD             | 2        | 2.47%   |
| PCWare IPX1800E2                   | 1        | 1.23%   |
| MSI MS-7D25                        | 1        | 1.23%   |
| MSI MS-7C91                        | 1        | 1.23%   |
| MSI MS-7C08                        | 1        | 1.23%   |
| MSI MS-7A32                        | 1        | 1.23%   |
| MSI MS-7982                        | 1        | 1.23%   |
| MSI MS-7529                        | 1        | 1.23%   |
| MSI MS-7309                        | 1        | 1.23%   |
| MSI Hyrican PC A320M PRO-E         | 1        | 1.23%   |
| MACHINIST X99-RS9 V2.0             | 1        | 1.23%   |
| Lenovo ThinkCentre M90p 3282A9G    | 1        | 1.23%   |
| Lenovo ThinkCentre M83 10AM0010US  | 1        | 1.23%   |
| Lenovo ThinkCentre M72e 32675L2    | 1        | 1.23%   |
| Lenovo ThinkCentre M58 7373A5G     | 1        | 1.23%   |
| Itautec Infoway ST-4273            | 1        | 1.23%   |
| Intel DH61AG AAG23736-507          | 1        | 1.23%   |
| Intel D525MW AAE93082-401          | 1        | 1.23%   |
| HP Z420 Workstation                | 1        | 1.23%   |
| HP Z1 Entry Tower G5               | 1        | 1.23%   |
| HP ProDesk 400 G2 MT (TPM DP)      | 1        | 1.23%   |
| HP Pavilion Desktop 590-p0xxx      | 1        | 1.23%   |
| HP EliteDesk 800 G2 SFF            | 1        | 1.23%   |
| HP Compaq dc7600 Small Form Factor | 1        | 1.23%   |
| HP Compaq 8200 Elite SFF PC        | 1        | 1.23%   |
| Hardkernel ODROID-H2               | 1        | 1.23%   |
| Gigabyte Z77-DS3H                  | 1        | 1.23%   |
| Gigabyte GA-MA790FXT-UD5P          | 1        | 1.23%   |
| Gigabyte GA-78LMT-USB3 6.0         | 1        | 1.23%   |
| Gigabyte G33M-DS2R                 | 1        | 1.23%   |
| Gigabyte AB350-Gaming              | 1        | 1.23%   |
| Gigabyte A320M-S2H                 | 1        | 1.23%   |
| Gigabyte 970A-DS3P                 | 1        | 1.23%   |
| Fujitsu CELSIUS W380               | 1        | 1.23%   |
| Foxconn p6-2466ef                  | 1        | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 7        | 8.64%   |
| Dell OptiPlex             | 6        | 7.41%   |
| Lenovo ThinkCentre        | 4        | 4.94%   |
| ASUS All                  | 4        | 4.94%   |
| ASUS TUF                  | 3        | 3.7%    |
| MSI MS-7D46               | 2        | 2.47%   |
| MSI MS-7D43               | 2        | 2.47%   |
| MSI MS-7C52               | 2        | 2.47%   |
| HP Compaq                 | 2        | 2.47%   |
| ASUS ROG                  | 2        | 2.47%   |
| ASUS P8H61-M              | 2        | 2.47%   |
| ASUS K30AD                | 2        | 2.47%   |
| PCWare IPX1800E2          | 1        | 1.23%   |
| MSI MS-7D25               | 1        | 1.23%   |
| MSI MS-7C91               | 1        | 1.23%   |
| MSI MS-7C08               | 1        | 1.23%   |
| MSI MS-7A32               | 1        | 1.23%   |
| MSI MS-7982               | 1        | 1.23%   |
| MSI MS-7529               | 1        | 1.23%   |
| MSI MS-7309               | 1        | 1.23%   |
| MSI Hyrican               | 1        | 1.23%   |
| MACHINIST X99-RS9         | 1        | 1.23%   |
| Itautec Infoway           | 1        | 1.23%   |
| Intel DH61AG              | 1        | 1.23%   |
| Intel D525MW              | 1        | 1.23%   |
| HP Z420                   | 1        | 1.23%   |
| HP Z1                     | 1        | 1.23%   |
| HP ProDesk                | 1        | 1.23%   |
| HP Pavilion               | 1        | 1.23%   |
| HP EliteDesk              | 1        | 1.23%   |
| Hardkernel ODROID-H2      | 1        | 1.23%   |
| Gigabyte Z77-DS3H         | 1        | 1.23%   |
| Gigabyte GA-MA790FXT-UD5P | 1        | 1.23%   |
| Gigabyte GA-78LMT-USB3    | 1        | 1.23%   |
| Gigabyte G33M-DS2R        | 1        | 1.23%   |
| Gigabyte AB350-Gaming     | 1        | 1.23%   |
| Gigabyte A320M-S2H        | 1        | 1.23%   |
| Gigabyte 970A-DS3P        | 1        | 1.23%   |
| Fujitsu CELSIUS           | 1        | 1.23%   |
| Foxconn p6-2466ef         | 1        | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 10       | 12.35%  |
| 2012 | 8        | 9.88%   |
| 2021 | 7        | 8.64%   |
| 2018 | 7        | 8.64%   |
| 2010 | 7        | 8.64%   |
| 2017 | 6        | 7.41%   |
| 2013 | 6        | 7.41%   |
| 2019 | 5        | 6.17%   |
| 2020 | 4        | 4.94%   |
| 2011 | 4        | 4.94%   |
| 2009 | 4        | 4.94%   |
| 2016 | 3        | 3.7%    |
| 2015 | 3        | 3.7%    |
| 2022 | 2        | 2.47%   |
| 2007 | 2        | 2.47%   |
| 2008 | 1        | 1.23%   |
| 2006 | 1        | 1.23%   |
| 2005 | 1        | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 81       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 77       | 95.06%  |
| Enabled  | 4        | 4.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 81       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 18       | 22.22%  |
| 16.01-24.0  | 18       | 22.22%  |
| 3.01-4.0    | 15       | 18.52%  |
| 8.01-16.0   | 11       | 13.58%  |
| 32.01-64.0  | 9        | 11.11%  |
| 1.01-2.0    | 4        | 4.94%   |
| 24.01-32.0  | 3        | 3.7%    |
| 64.01-256.0 | 2        | 2.47%   |
| 2.01-3.0    | 1        | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 38       | 44.19%  |
| 3.01-4.0  | 15       | 17.44%  |
| 2.01-3.0  | 13       | 15.12%  |
| 4.01-8.0  | 10       | 11.63%  |
| 0.51-1.0  | 5        | 5.81%   |
| 8.01-16.0 | 4        | 4.65%   |
| 0.01-0.5  | 1        | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 37.8%   |
| 2      | 22       | 26.83%  |
| 3      | 13       | 15.85%  |
| 4      | 8        | 9.76%   |
| 5      | 4        | 4.88%   |
| 6      | 2        | 2.44%   |
| 10     | 1        | 1.22%   |
| 7      | 1        | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 56.1%   |
| No        | 36       | 43.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 81       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 62.96%  |
| Yes       | 30       | 37.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 75.31%  |
| Yes       | 20       | 24.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| France       | 14       | 17.28%  |
| Italy        | 12       | 14.81%  |
| Germany      | 11       | 13.58%  |
| USA          | 9        | 11.11%  |
| Canada       | 5        | 6.17%   |
| Brazil       | 5        | 6.17%   |
| Sweden       | 3        | 3.7%    |
| UK           | 2        | 2.47%   |
| Russia       | 2        | 2.47%   |
| Netherlands  | 2        | 2.47%   |
| Greece       | 2        | 2.47%   |
| Taiwan       | 1        | 1.23%   |
| South Africa | 1        | 1.23%   |
| Portugal     | 1        | 1.23%   |
| Poland       | 1        | 1.23%   |
| Norway       | 1        | 1.23%   |
| Iran         | 1        | 1.23%   |
| Indonesia    | 1        | 1.23%   |
| Hungary      | 1        | 1.23%   |
| Guernsey     | 1        | 1.23%   |
| Guadeloupe   | 1        | 1.23%   |
| Colombia     | 1        | 1.23%   |
| Belgium      | 1        | 1.23%   |
| Australia    | 1        | 1.23%   |
| Argentina    | 1        | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Paris               | 5        | 6.1%    |
| Clermont-Ferrand    | 2        | 2.44%   |
| Biella              | 2        | 2.44%   |
| Berlin              | 2        | 2.44%   |
| Żywiec             | 1        | 1.22%   |
| Wettringen          | 1        | 1.22%   |
| Washington          | 1        | 1.22%   |
| Waarder             | 1        | 1.22%   |
| Vicenza             | 1        | 1.22%   |
| Västerås          | 1        | 1.22%   |
| Valparaiso de Goias | 1        | 1.22%   |
| Tourouvre           | 1        | 1.22%   |
| Toronto             | 1        | 1.22%   |
| The Hague           | 1        | 1.22%   |
| Teresina            | 1        | 1.22%   |
| Tehran              | 1        | 1.22%   |
| Taichung            | 1        | 1.22%   |
| Surrey              | 1        | 1.22%   |
| Stuttgart           | 1        | 1.22%   |
| St Peter Port       | 1        | 1.22%   |
| Sassari             | 1        | 1.22%   |
| Santiago de Cali    | 1        | 1.22%   |
| Salzgitter          | 1        | 1.22%   |
| Sainte-Rose         | 1        | 1.22%   |
| Saint-Eustache      | 1        | 1.22%   |
| Saint-Denis         | 1        | 1.22%   |
| Rio de Janeiro      | 1        | 1.22%   |
| Rho                 | 1        | 1.22%   |
| Pocatello           | 1        | 1.22%   |
| Pieris              | 1        | 1.22%   |
| Peterborough        | 1        | 1.22%   |
| Pescara             | 1        | 1.22%   |
| Perth-Andover       | 1        | 1.22%   |
| North Augusta       | 1        | 1.22%   |
| Newton Abbot        | 1        | 1.22%   |
| Nettetal            | 1        | 1.22%   |
| Münster            | 1        | 1.22%   |
| Munich              | 1        | 1.22%   |
| Melbourne           | 1        | 1.22%   |
| Malmo               | 1        | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 45     | 19.23%  |
| Seagate             | 24       | 34     | 15.38%  |
| Samsung Electronics | 20       | 28     | 12.82%  |
| Toshiba             | 14       | 14     | 8.97%   |
| Kingston            | 11       | 14     | 7.05%   |
| Hitachi             | 8        | 13     | 5.13%   |
| SanDisk             | 7        | 8      | 4.49%   |
| Crucial             | 7        | 10     | 4.49%   |
| PNY                 | 3        | 3      | 1.92%   |
| Patriot             | 3        | 3      | 1.92%   |
| HGST                | 3        | 4      | 1.92%   |
| China               | 3        | 3      | 1.92%   |
| TEXTORM             | 2        | 2      | 1.28%   |
| Maxtor              | 2        | 2      | 1.28%   |
| Intel               | 2        | 2      | 1.28%   |
| ASMT                | 2        | 5      | 1.28%   |
| XPG                 | 1        | 1      | 0.64%   |
| Vaseky              | 1        | 1      | 0.64%   |
| USB3.0              | 1        | 2      | 0.64%   |
| Unknown             | 1        | 1      | 0.64%   |
| SK hynix            | 1        | 1      | 0.64%   |
| Phison Electronics  | 1        | 1      | 0.64%   |
| Phison              | 1        | 6      | 0.64%   |
| OCZ                 | 1        | 1      | 0.64%   |
| Lexar               | 1        | 1      | 0.64%   |
| KingFast            | 1        | 1      | 0.64%   |
| Intenso             | 1        | 1      | 0.64%   |
| HGST HUS            | 1        | 1      | 0.64%   |
| Emtec               | 1        | 1      | 0.64%   |
| CHN25SATAS1         | 1        | 1      | 0.64%   |
| Unknown             | 1        | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Crucial CT480BX500SSD1 480GB     | 4        | 2.13%   |
| Toshiba HDWD110 1TB              | 3        | 1.6%    |
| Samsung SSD 840 Series 120GB     | 3        | 1.6%    |
| Kingston SA400S37480G 480GB SSD  | 3        | 1.6%    |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.6%    |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 1.06%   |
| Toshiba DT01ACA200 2TB           | 2        | 1.06%   |
| Toshiba DT01ACA050 500GB         | 2        | 1.06%   |
| TEXTORM BM5 240GB SSD            | 2        | 1.06%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.06%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 1.06%   |
| Seagate ST31000528AS 1TB         | 2        | 1.06%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.06%   |
| SanDisk SDSSDA240G 240GB         | 2        | 1.06%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 1.06%   |
| Hitachi HDS721010CLA332 1TB      | 2        | 1.06%   |
| Hitachi HDP725050GLA360 500GB    | 2        | 1.06%   |
| XPG GAMMIX S11L 256GB            | 1        | 0.53%   |
| WDC WUH721816ALE6L4 16TB         | 1        | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.53%   |
| WDC WDS250G2B0B-00YS70 250GB SSD | 1        | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.53%   |
| WDC WD800JD-75MSA3 80GB          | 1        | 0.53%   |
| WDC WD800JD-22MSA1 80GB          | 1        | 0.53%   |
| WDC WD740ADFD-00NLR5 74GB        | 1        | 0.53%   |
| WDC WD6400BPVT-80HXZT1 640GB     | 1        | 0.53%   |
| WDC WD6400BEVT-80A0RT0 640GB     | 1        | 0.53%   |
| WDC WD5003AZEX-00S3DA0 500GB     | 1        | 0.53%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1        | 0.53%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 0.53%   |
| WDC WD5000AVCS-612DY1 500GB      | 1        | 0.53%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.53%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.53%   |
| WDC WD5000AAKS-00UU3A0 500GB     | 1        | 0.53%   |
| WDC WD40PURX-78AKYY0 4TB         | 1        | 0.53%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 1        | 0.53%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.53%   |
| WDC WD40EFAX-68JH4N1 4TB         | 1        | 0.53%   |
| WDC WD4003FRYZ-01F0DB0 4TB       | 1        | 0.53%   |
| WDC WD3200AAKS-00L9A0 320GB      | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 42     | 32.94%  |
| Seagate             | 24       | 34     | 28.24%  |
| Toshiba             | 12       | 12     | 14.12%  |
| Hitachi             | 8        | 13     | 9.41%   |
| Samsung Electronics | 6        | 10     | 7.06%   |
| HGST                | 3        | 4      | 3.53%   |
| ASMT                | 2        | 5      | 2.35%   |
| USB3.0              | 1        | 2      | 1.18%   |
| Maxtor              | 1        | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 12     | 19.64%  |
| Kingston            | 9        | 10     | 16.07%  |
| Crucial             | 7        | 10     | 12.5%   |
| SanDisk             | 6        | 7      | 10.71%  |
| WDC                 | 3        | 3      | 5.36%   |
| Patriot             | 3        | 3      | 5.36%   |
| China               | 3        | 3      | 5.36%   |
| Toshiba             | 2        | 2      | 3.57%   |
| TEXTORM             | 2        | 2      | 3.57%   |
| PNY                 | 2        | 2      | 3.57%   |
| Intel               | 2        | 2      | 3.57%   |
| Vaseky              | 1        | 1      | 1.79%   |
| OCZ                 | 1        | 1      | 1.79%   |
| Maxtor              | 1        | 1      | 1.79%   |
| KingFast            | 1        | 1      | 1.79%   |
| Intenso             | 1        | 1      | 1.79%   |
| Unknown             | 1        | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 62       | 123    | 49.6%   |
| SSD     | 45       | 62     | 36%     |
| NVMe    | 14       | 22     | 11.2%   |
| Unknown | 3        | 3      | 2.4%    |
| MMC     | 1        | 1      | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 79       | 173    | 79%     |
| NVMe | 14       | 22     | 14%     |
| SAS  | 6        | 15     | 6%      |
| MMC  | 1        | 1      | 1%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 63       | 107    | 52.5%   |
| 0.51-1.0   | 32       | 41     | 26.67%  |
| 3.01-4.0   | 11       | 16     | 9.17%   |
| 1.01-2.0   | 10       | 11     | 8.33%   |
| 2.01-3.0   | 2        | 8      | 1.67%   |
| 10.01-20.0 | 1        | 1      | 0.83%   |
| 4.01-10.0  | 1        | 1      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 19       | 23.17%  |
| 101-250        | 19       | 23.17%  |
| 1001-2000      | 14       | 17.07%  |
| 501-1000       | 11       | 13.41%  |
| More than 3000 | 9        | 10.98%  |
| 2001-3000      | 6        | 7.32%   |
| 21-50          | 2        | 2.44%   |
| 1-20           | 1        | 1.22%   |
| 51-100         | 1        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 18       | 21.69%  |
| 21-50          | 15       | 18.07%  |
| 101-250        | 15       | 18.07%  |
| 1-20           | 13       | 15.66%  |
| 51-100         | 6        | 7.23%   |
| 1001-2000      | 5        | 6.02%   |
| More than 3000 | 4        | 4.82%   |
| 501-1000       | 4        | 4.82%   |
| 2001-3000      | 3        | 3.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 5%      |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 5%      |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 5%      |
| WDC WD20EFRX-68AX9N0 2TB          | 1        | 1      | 5%      |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 5%      |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 5%      |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 5%      |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 5%      |
| WDC WD1003FBYX-01Y7B1 1TB         | 1        | 1      | 5%      |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 5%      |
| Seagate ST3750840AS 752GB         | 1        | 1      | 5%      |
| Seagate ST3250318AS 250GB         | 1        | 2      | 5%      |
| Samsung Electronics HM321HI 320GB | 1        | 2      | 5%      |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 5%      |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 5%      |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 5%      |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 5%      |
| Hitachi HCP725032GLA380 320GB     | 1        | 2      | 5%      |
| Crucial CT128MX100SSD1 128GB      | 1        | 1      | 5%      |
| ASMT ASMT105x 3TB                 | 1        | 4      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 9      | 47.37%  |
| Seagate             | 2        | 3      | 10.53%  |
| Samsung Electronics | 2        | 4      | 10.53%  |
| Hitachi             | 2        | 3      | 10.53%  |
| Toshiba             | 1        | 1      | 5.26%   |
| Maxtor              | 1        | 1      | 5.26%   |
| Crucial             | 1        | 1      | 5.26%   |
| ASMT                | 1        | 4      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 47.06%  |
| Seagate             | 2        | 3      | 11.76%  |
| Samsung Electronics | 2        | 4      | 11.76%  |
| Hitachi             | 2        | 3      | 11.76%  |
| Toshiba             | 1        | 1      | 5.88%   |
| Maxtor              | 1        | 1      | 5.88%   |
| ASMT                | 1        | 4      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 24     | 93.33%  |
| SSD  | 1        | 2      | 6.67%   |

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
| Works    | 46       | 102    | 48.42%  |
| Detected | 35       | 83     | 36.84%  |
| Malfunc  | 14       | 26     | 14.74%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 52       | 49.06%  |
| AMD                          | 26       | 24.53%  |
| Samsung Electronics          | 5        | 4.72%   |
| ASMedia Technology           | 4        | 3.77%   |
| Nvidia                       | 3        | 2.83%   |
| Kingston Technology Company  | 3        | 2.83%   |
| JMicron Technology           | 3        | 2.83%   |
| VIA Technologies             | 2        | 1.89%   |
| Phison Electronics           | 2        | 1.89%   |
| SK hynix                     | 1        | 0.94%   |
| Shenzhen Longsys Electronics | 1        | 0.94%   |
| SanDisk                      | 1        | 0.94%   |
| Realtek Semiconductor        | 1        | 0.94%   |
| Marvell Technology Group     | 1        | 0.94%   |
| Adaptec                      | 1        | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 11.19%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 4.2%    |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.2%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 3.5%    |
| AMD FCH SATA Controller D                                                               | 5        | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 2.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.1%    |
| Nvidia MCP61 SATA Controller                                                            | 3        | 2.1%    |
| Nvidia MCP61 IDE                                                                        | 3        | 2.1%    |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 2.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 2.1%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 1.4%    |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.4%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.4%    |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.4%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.4%    |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.4%    |
| SK hynix Non-Volatile memory controller                                                 | 1        | 0.7%    |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1        | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.7%    |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.7%    |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.7%    |
| Phison E18 PCIe4 NVMe Controller                                                        | 1        | 0.7%    |
| Phison E12 NVMe Controller                                                              | 1        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 66       | 61.68%  |
| IDE  | 21       | 19.63%  |
| NVMe | 14       | 13.08%  |
| RAID | 5        | 4.67%   |
| SAS  | 1        | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 52       | 64.2%   |
| AMD    | 29       | 35.8%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor     | 3        | 3.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz      | 2        | 2.44%   |
| Intel Core i5-3570K CPU @ 3.40GHz     | 2        | 2.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz      | 2        | 2.44%   |
| Intel Core i3-3240 CPU @ 3.40GHz      | 2        | 2.44%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz  | 2        | 2.44%   |
| Intel 12th Gen Core i7-12700          | 2        | 2.44%   |
| Intel 12th Gen Core i3-12100          | 2        | 2.44%   |
| AMD Ryzen 7 2700 Eight-Core Processor | 2        | 2.44%   |
| AMD FX-6300 Six-Core Processor        | 2        | 2.44%   |
| Intel Xeon CPU E5-2666 v3 @ 2.90GHz   | 1        | 1.22%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz    | 1        | 1.22%   |
| Intel Pentium 4 CPU 3.00GHz           | 1        | 1.22%   |
| Intel Core i7-9700 CPU @ 3.00GHz      | 1        | 1.22%   |
| Intel Core i7-6800K CPU @ 3.40GHz     | 1        | 1.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz     | 1        | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz      | 1        | 1.22%   |
| Intel Core i7-4771 CPU @ 3.50GHz      | 1        | 1.22%   |
| Intel Core i7-4770 CPU @ 3.40GHz      | 1        | 1.22%   |
| Intel Core i7-2600K CPU @ 3.40GHz     | 1        | 1.22%   |
| Intel Core i7-2600 CPU @ 3.40GHz      | 1        | 1.22%   |
| Intel Core i7 CPU 870 @ 2.93GHz       | 1        | 1.22%   |
| Intel Core i5-9400 CPU @ 2.90GHz      | 1        | 1.22%   |
| Intel Core i5-4690K CPU @ 3.50GHz     | 1        | 1.22%   |
| Intel Core i5-4690 CPU @ 3.50GHz      | 1        | 1.22%   |
| Intel Core i5-4590S CPU @ 3.00GHz     | 1        | 1.22%   |
| Intel Core i5-3570 CPU @ 3.40GHz      | 1        | 1.22%   |
| Intel Core i5-3470T CPU @ 2.90GHz     | 1        | 1.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz      | 1        | 1.22%   |
| Intel Core i5-3350P CPU @ 3.10GHz     | 1        | 1.22%   |
| Intel Core i5-2400S CPU @ 2.50GHz     | 1        | 1.22%   |
| Intel Core i5-10400 CPU @ 2.90GHz     | 1        | 1.22%   |
| Intel Core i5 CPU 760 @ 2.80GHz       | 1        | 1.22%   |
| Intel Core i5 CPU 750 @ 2.67GHz       | 1        | 1.22%   |
| Intel Core i5 CPU 660 @ 3.33GHz       | 1        | 1.22%   |
| Intel Core i3-9100 CPU @ 3.60GHz      | 1        | 1.22%   |
| Intel Core i3-7300 CPU @ 4.00GHz      | 1        | 1.22%   |
| Intel Core i3-7100 CPU @ 3.90GHz      | 1        | 1.22%   |
| Intel Core i3-2120 CPU @ 3.30GHz      | 1        | 1.22%   |
| Intel Core i3-2100 CPU @ 3.10GHz      | 1        | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 19       | 23.17%  |
| AMD Ryzen 5       | 10       | 12.2%   |
| Intel Core i7     | 9        | 10.98%  |
| Intel Core i3     | 7        | 8.54%   |
| Other             | 5        | 6.1%    |
| Intel Core 2 Duo  | 4        | 4.88%   |
| Intel Celeron     | 3        | 3.66%   |
| AMD Ryzen 9       | 3        | 3.66%   |
| AMD Ryzen 7       | 3        | 3.66%   |
| Intel Xeon        | 2        | 2.44%   |
| AMD Ryzen 3       | 2        | 2.44%   |
| AMD FX            | 2        | 2.44%   |
| AMD Athlon II X2  | 2        | 2.44%   |
| Intel Pentium 4   | 1        | 1.22%   |
| Intel Core 2 Quad | 1        | 1.22%   |
| Intel Atom        | 1        | 1.22%   |
| AMD Sempron       | 1        | 1.22%   |
| AMD Ryzen 7 PRO   | 1        | 1.22%   |
| AMD Phenom II X6  | 1        | 1.22%   |
| AMD Phenom II X4  | 1        | 1.22%   |
| AMD Athlon II     | 1        | 1.22%   |
| AMD Athlon 64 X2  | 1        | 1.22%   |
| AMD Athlon        | 1        | 1.22%   |
| AMD A10           | 1        | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 35       | 42.17%  |
| 2      | 20       | 24.1%   |
| 6      | 12       | 14.46%  |
| 8      | 5        | 6.02%   |
| 12     | 4        | 4.82%   |
| 3      | 2        | 2.41%   |
| 1      | 2        | 2.41%   |
| 16     | 1        | 1.2%    |
| 14     | 1        | 1.2%    |
| 10     | 1        | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 81       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 47       | 58.02%  |
| 1      | 34       | 41.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 81       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 36.59%  |
| 0x306a9    | 5        | 6.1%    |
| 0x206a7    | 5        | 6.1%    |
| 0x306c3    | 4        | 4.88%   |
| 0x106e5    | 3        | 3.66%   |
| 0x08701021 | 3        | 3.66%   |
| 0x0800820d | 3        | 3.66%   |
| 0x90672    | 2        | 2.44%   |
| 0x10676    | 2        | 2.44%   |
| 0x06000852 | 2        | 2.44%   |
| 0x010000c8 | 2        | 2.44%   |
| 0xb0671    | 1        | 1.22%   |
| 0xa0653    | 1        | 1.22%   |
| 0x906ed    | 1        | 1.22%   |
| 0x906ea    | 1        | 1.22%   |
| 0x706a1    | 1        | 1.22%   |
| 0x506e3    | 1        | 1.22%   |
| 0x306f2    | 1        | 1.22%   |
| 0x206d7    | 1        | 1.22%   |
| 0x20652    | 1        | 1.22%   |
| 0x106ca    | 1        | 1.22%   |
| 0x1067a    | 1        | 1.22%   |
| 0x0a50000c | 1        | 1.22%   |
| 0x0a201016 | 1        | 1.22%   |
| 0x08701013 | 1        | 1.22%   |
| 0x08600106 | 1        | 1.22%   |
| 0x08108109 | 1        | 1.22%   |
| 0x08101016 | 1        | 1.22%   |
| 0x08001138 | 1        | 1.22%   |
| 0x08001137 | 1        | 1.22%   |
| 0x0700010f | 1        | 1.22%   |
| 0x010000c7 | 1        | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 9        | 10.98%  |
| Zen 2            | 8        | 9.76%   |
| IvyBridge        | 8        | 9.76%   |
| Haswell          | 8        | 9.76%   |
| Zen+             | 5        | 6.1%    |
| KabyLake         | 5        | 6.1%    |
| K10              | 5        | 6.1%    |
| Zen              | 4        | 4.88%   |
| Penryn           | 4        | 4.88%   |
| Zen 3            | 3        | 3.66%   |
| Piledriver       | 3        | 3.66%   |
| Nehalem          | 3        | 3.66%   |
| Unknown          | 3        | 3.66%   |
| Skylake          | 2        | 2.44%   |
| Alderlake Hybrid | 2        | 2.44%   |
| Westmere         | 1        | 1.22%   |
| Silvermont       | 1        | 1.22%   |
| NetBurst         | 1        | 1.22%   |
| K8 Hammer        | 1        | 1.22%   |
| Jaguar           | 1        | 1.22%   |
| Goldmont plus    | 1        | 1.22%   |
| Core             | 1        | 1.22%   |
| CometLake        | 1        | 1.22%   |
| Broadwell        | 1        | 1.22%   |
| Bonnell          | 1        | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 40.45%  |
| Nvidia | 32       | 35.96%  |
| AMD    | 21       | 23.6%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 7.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 5.62%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 4.49%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 4.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.37%   |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 2.25%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.25%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 2.25%   |
| Intel HD Graphics 630                                                       | 2        | 2.25%   |
| Intel HD Graphics 530                                                       | 2        | 2.25%   |
| Intel AlderLake-S GT1                                                       | 2        | 2.25%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 2.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.25%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 2.25%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.25%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 2.25%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.12%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 1.12%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 1.12%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.12%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.12%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.12%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.12%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 1.12%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.12%   |
| Nvidia GK104 [GeForce GTX 690]                                              | 1        | 1.12%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.12%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.12%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.12%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.12%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.12%   |
| Intel Raptor Lake-S UHD Graphics                                            | 1        | 1.12%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.12%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 29       | 35.8%   |
| 1 x Nvidia     | 28       | 34.57%  |
| 1 x AMD        | 20       | 24.69%  |
| Intel + Nvidia | 3        | 3.7%    |
| AMD + Nvidia   | 1        | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 59       | 72.84%  |
| Proprietary | 19       | 23.46%  |
| Unknown     | 3        | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 57.32%  |
| 1.01-2.0   | 14       | 17.07%  |
| 0.51-1.0   | 9        | 10.98%  |
| 3.01-4.0   | 5        | 6.1%    |
| 0.01-0.5   | 4        | 4.88%   |
| 7.01-8.0   | 1        | 1.22%   |
| 5.01-6.0   | 1        | 1.22%   |
| 8.01-16.0  | 1        | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 13       | 15.12%  |
| Hewlett-Packard         | 13       | 15.12%  |
| Dell                    | 10       | 11.63%  |
| Acer                    | 6        | 6.98%   |
| ViewSonic               | 5        | 5.81%   |
| Iiyama                  | 5        | 5.81%   |
| Goldstar                | 5        | 5.81%   |
| Philips                 | 3        | 3.49%   |
| AOC                     | 3        | 3.49%   |
| BenQ                    | 2        | 2.33%   |
| Ancor Communications    | 2        | 2.33%   |
| ___                     | 1        | 1.16%   |
| Vestel Elektronik       | 1        | 1.16%   |
| Unknown                 | 1        | 1.16%   |
| Toshiba                 | 1        | 1.16%   |
| TEO                     | 1        | 1.16%   |
| TCL                     | 1        | 1.16%   |
| Mi                      | 1        | 1.16%   |
| MAG                     | 1        | 1.16%   |
| LG Electronics          | 1        | 1.16%   |
| Lenovo                  | 1        | 1.16%   |
| Gateway                 | 1        | 1.16%   |
| Fujitsu Siemens         | 1        | 1.16%   |
| eMachines               | 1        | 1.16%   |
| Elo Touch               | 1        | 1.16%   |
| Eizo                    | 1        | 1.16%   |
| Denver                  | 1        | 1.16%   |
| Chi Mei Optoelectronics | 1        | 1.16%   |
| ASUSTek Computer        | 1        | 1.16%   |
| Unknown                 | 1        | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                 | 2        | 2.22%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch             | 2        | 2.22%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                     | 1        | 1.11%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch             | 1        | 1.11%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch           | 1        | 1.11%   |
| ViewSonic LCD Monitor VSCBB31 1920x1080 530x300mm 24.0-inch            | 1        | 1.11%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 1.11%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 1        | 1.11%   |
| Toshiba TV TSB0109 1920x1080 1594x900mm 72.1-inch                      | 1        | 1.11%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                        | 1        | 1.11%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                       | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                       | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch   | 1        | 1.11%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch      | 1        | 1.11%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch     | 1        | 1.11%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch      | 1        | 1.11%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 1.11%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 1        | 1.11%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch       | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SAM07BB 1360x768 410x256mm 19.0-inch   | 1        | 1.11%   |
| Samsung Electronics LCD Monitor S22E450 1920x1080                      | 1        | 1.11%   |
| Samsung Electronics C27R500 SAM0F9E 1920x1080 598x336mm 27.0-inch      | 1        | 1.11%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1        | 1.11%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch                | 1        | 1.11%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                | 1        | 1.11%   |
| Philips 221TE PHLC062 1920x1080 476x268mm 21.5-inch                    | 1        | 1.11%   |
| Philips 170S PHL082B 1280x1024 340x270mm 17.1-inch                     | 1        | 1.11%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                       | 1        | 1.11%   |
| MAG Monitor MAG1901 1280x1024 320x206mm 15.0-inch                      | 1        | 1.11%   |
| LG Electronics LCD Monitor E2442 1920x1080                             | 1        | 1.11%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                   | 1        | 1.11%   |
| Iiyama X2483_2480-DP IVM6129 1920x1080 527x296mm 23.8-inch             | 1        | 1.11%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                  | 1        | 1.11%   |
| Iiyama PL2780H IVM6609 1920x1080 600x340mm 27.2-inch                   | 1        | 1.11%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                    | 1        | 1.11%   |
| Iiyama PL1908W IVM483D 1680x1050 408x255mm 18.9-inch                   | 1        | 1.11%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch            | 1        | 1.11%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch             | 1        | 1.11%   |
| Hewlett-Packard LCD Monitor L185b 1024x768                             | 1        | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 36       | 44.44%  |
| 1366x768 (WXGA)    | 7        | 8.64%   |
| 1280x1024 (SXGA)   | 7        | 8.64%   |
| 1440x900 (WXGA+)   | 6        | 7.41%   |
| 3840x2160 (4K)     | 4        | 4.94%   |
| 1920x1200 (WUXGA)  | 3        | 3.7%    |
| 1680x1050 (WSXGA+) | 3        | 3.7%    |
| 1600x900 (HD+)     | 3        | 3.7%    |
| 3840x1600          | 2        | 2.47%   |
| 1360x768           | 2        | 2.47%   |
| 1024x768 (XGA)     | 2        | 2.47%   |
| 3840x1080          | 1        | 1.23%   |
| 2560x1600          | 1        | 1.23%   |
| 2560x1440 (QHD)    | 1        | 1.23%   |
| 1920x540           | 1        | 1.23%   |
| 1600x1200          | 1        | 1.23%   |
| Unknown            | 1        | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 15       | 17.24%  |
| 23      | 11       | 12.64%  |
| 27      | 8        | 9.2%    |
| 19      | 7        | 8.05%   |
| 18      | 7        | 8.05%   |
| 17      | 6        | 6.9%    |
| Unknown | 6        | 6.9%    |
| 21      | 5        | 5.75%   |
| 31      | 4        | 4.6%    |
| 20      | 4        | 4.6%    |
| 15      | 3        | 3.45%   |
| 37      | 2        | 2.3%    |
| 26      | 2        | 2.3%    |
| 84      | 1        | 1.15%   |
| 72      | 1        | 1.15%   |
| 32      | 1        | 1.15%   |
| 30      | 1        | 1.15%   |
| 25      | 1        | 1.15%   |
| 22      | 1        | 1.15%   |
| 6       | 1        | 1.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 33       | 40.24%  |
| 401-500     | 23       | 28.05%  |
| 301-350     | 9        | 10.98%  |
| Unknown     | 6        | 7.32%   |
| 601-700     | 5        | 6.1%    |
| 801-900     | 2        | 2.44%   |
| 1501-2000   | 2        | 2.44%   |
| 701-800     | 1        | 1.22%   |
| 101-200     | 1        | 1.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 47       | 60.26%  |
| 16/10   | 15       | 19.23%  |
| 5/4     | 6        | 7.69%   |
| Unknown | 5        | 6.41%   |
| 4/3     | 3        | 3.85%   |
| 21/9    | 2        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 28.57%  |
| 151-200        | 15       | 17.86%  |
| 141-150        | 12       | 14.29%  |
| 301-350        | 9        | 10.71%  |
| 351-500        | 6        | 7.14%   |
| Unknown        | 6        | 7.14%   |
| 251-300        | 5        | 5.95%   |
| 101-110        | 3        | 3.57%   |
| More than 1000 | 2        | 2.38%   |
| 1-40           | 1        | 1.19%   |
| 501-1000       | 1        | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 59       | 74.68%  |
| 101-120       | 10       | 12.66%  |
| Unknown       | 6        | 7.59%   |
| 121-160       | 2        | 2.53%   |
| More than 240 | 1        | 1.27%   |
| 1-50          | 1        | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 65       | 80.25%  |
| 2     | 9        | 11.11%  |
| 0     | 4        | 4.94%   |
| 3     | 3        | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 50       | 45.45%  |
| Intel                           | 37       | 33.64%  |
| Qualcomm Atheros                | 5        | 4.55%   |
| Ralink Technology               | 3        | 2.73%   |
| Nvidia                          | 3        | 2.73%   |
| D-Link System                   | 2        | 1.82%   |
| Broadcom                        | 2        | 1.82%   |
| TRENDnet                        | 1        | 0.91%   |
| TP-Link                         | 1        | 0.91%   |
| Ralink                          | 1        | 0.91%   |
| Qualcomm Atheros Communications | 1        | 0.91%   |
| NetGear                         | 1        | 0.91%   |
| Microchip Technology            | 1        | 0.91%   |
| Dell                            | 1        | 0.91%   |
| Broadcom Limited                | 1        | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 39       | 32.23%  |
| Realtek RTL8125 2.5GbE Controller                                              | 6        | 4.96%   |
| Intel I211 Gigabit Network Connection                                          | 6        | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6        | 4.96%   |
| Intel Wi-Fi 6 AX200                                                            | 4        | 3.31%   |
| Nvidia MCP61 Ethernet                                                          | 3        | 2.48%   |
| Intel Ethernet Connection (2) I219-V                                           | 3        | 2.48%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 2.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1.65%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.65%   |
| Intel Ethernet Connection (17) I219-V                                          | 2        | 1.65%   |
| Intel 82578DM Gigabit Network Connection                                       | 2        | 1.65%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 1.65%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]     | 1        | 0.83%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                            | 1        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.83%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 0.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 0.83%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 1        | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.83%   |
| Realtek 802.11ac NIC                                                           | 1        | 0.83%   |
| Ralink RT2770 Wireless Adapter                                                 | 1        | 0.83%   |
| Ralink RT2501/RT2573 Wireless Adapter                                          | 1        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 0.83%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1        | 0.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 0.83%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 1        | 0.83%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1        | 0.83%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                            | 1        | 0.83%   |
| Microchip TrueRNG                                                              | 1        | 0.83%   |
| Intel Wireless 3160                                                            | 1        | 0.83%   |
| Intel Ethernet Controller I225-V                                               | 1        | 0.83%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 9        | 29.03%  |
| Intel                           | 6        | 19.35%  |
| Qualcomm Atheros                | 5        | 16.13%  |
| Ralink Technology               | 3        | 9.68%   |
| TRENDnet                        | 1        | 3.23%   |
| TP-Link                         | 1        | 3.23%   |
| Ralink                          | 1        | 3.23%   |
| Qualcomm Atheros Communications | 1        | 3.23%   |
| NetGear                         | 1        | 3.23%   |
| Dell                            | 1        | 3.23%   |
| D-Link System                   | 1        | 3.23%   |
| Broadcom                        | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 4        | 12.9%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 6.45%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]        | 1        | 3.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 1        | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 3.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 3.23%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 3.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 1        | 3.23%   |
| Realtek 802.11ac NIC                                                              | 1        | 3.23%   |
| Ralink RT2770 Wireless Adapter                                                    | 1        | 3.23%   |
| Ralink RT2501/RT2573 Wireless Adapter                                             | 1        | 3.23%   |
| Ralink MT7601U Wireless Adapter                                                   | 1        | 3.23%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                            | 1        | 3.23%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 3.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 3.23%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                  | 1        | 3.23%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]    | 1        | 3.23%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                               | 1        | 3.23%   |
| Intel Wireless 3160                                                               | 1        | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 1        | 3.23%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]             | 1        | 3.23%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 3.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 46       | 53.49%  |
| Intel                 | 34       | 39.53%  |
| Nvidia                | 3        | 3.49%   |
| D-Link System         | 1        | 1.16%   |
| Broadcom Limited      | 1        | 1.16%   |
| Broadcom              | 1        | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39       | 43.82%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 6.74%   |
| Intel I211 Gigabit Network Connection                             | 6        | 6.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 6.74%   |
| Nvidia MCP61 Ethernet                                             | 3        | 3.37%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.37%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.25%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.25%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 2.25%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 2.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.12%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.12%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.12%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.12%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.12%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.12%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1        | 1.12%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.12%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                       | 1        | 1.12%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 81       | 72.32%  |
| WiFi     | 30       | 26.79%  |
| Modem    | 1        | 0.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 67       | 79.76%  |
| WiFi     | 17       | 20.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 57       | 70.37%  |
| 2     | 20       | 24.69%  |
| 3     | 4        | 4.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 60.98%  |
| Yes  | 32       | 39.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 9        | 42.86%  |
| Intel                   | 6        | 28.57%  |
| Realtek Semiconductor   | 2        | 9.52%   |
| Broadcom                | 2        | 9.52%   |
| IMC Networks            | 1        | 4.76%   |
| Fujitsu                 | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 42.86%  |
| Intel AX200 Bluetooth                               | 4        | 19.05%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.76%   |
| Realtek Bluetooth Radio                             | 1        | 4.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.76%   |
| Intel Bluetooth wireless interface                  | 1        | 4.76%   |
| IMC Networks Bluetooth Radio                        | 1        | 4.76%   |
| Fujitsu Bluetooth Device                            | 1        | 4.76%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 4.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 52       | 40.63%  |
| Nvidia                      | 31       | 24.22%  |
| AMD                         | 31       | 24.22%  |
| C-Media Electronics         | 3        | 2.34%   |
| SAVITECH                    | 2        | 1.56%   |
| Samson Technologies         | 1        | 0.78%   |
| Medeli Electronics          | 1        | 0.78%   |
| MAG Technology              | 1        | 0.78%   |
| Logitech                    | 1        | 0.78%   |
| Lenovo                      | 1        | 0.78%   |
| Kingston Technology         | 1        | 0.78%   |
| GN Netcom                   | 1        | 0.78%   |
| FiiO Electronics Technology | 1        | 0.78%   |
| Corsair                     | 1        | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 6.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 5.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 4.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 4.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 4.14%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 3.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 2.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 2.76%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.76%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 2.07%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 2.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.07%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 2.07%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.38%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2        | 1.38%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.38%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.38%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.38%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.38%   |
| SAVITECH PHIREE D1                                                         | 1        | 0.69%   |
| SAVITECH ODAC-revB                                                         | 1        | 0.69%   |
| Samson Technologies Q1U dynamic microphone                                 | 1        | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.69%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 13       | 19.7%   |
| Unknown             | 12       | 18.18%  |
| Samsung Electronics | 9        | 13.64%  |
| Crucial             | 7        | 10.61%  |
| G.Skill             | 5        | 7.58%   |
| Corsair             | 5        | 7.58%   |
| SK hynix            | 4        | 6.06%   |
| Nanya Technology    | 2        | 3.03%   |
| Unknown             | 2        | 3.03%   |
| Unknown (ABCD)      | 1        | 1.52%   |
| Transcend           | 1        | 1.52%   |
| Ramaxel Technology  | 1        | 1.52%   |
| Micron Technology   | 1        | 1.52%   |
| GLOWAY              | 1        | 1.52%   |
| Elpida              | 1        | 1.52%   |
| ASint Technology    | 1        | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s         | 2        | 2.86%   |
| Unknown                                                      | 2        | 2.86%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 1        | 1.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 1        | 1.43%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 1.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                     | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                    | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 1.43%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s    | 1        | 1.43%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s        | 1        | 1.43%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 1.43%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 1.43%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                  | 1        | 1.43%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s         | 1        | 1.43%   |
| SK hynix RAM HMT351U7EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.43%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 1        | 1.43%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1        | 1.43%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| Samsung RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 1.43%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s        | 1        | 1.43%   |
| Samsung RAM M391B5773DH0-CK0 2GB DIMM DDR3 1600MT/s          | 1        | 1.43%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s          | 1        | 1.43%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.43%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.43%   |
| Samsung RAM M378B5173BH0-CH9 4GB DIMM DDR3 1867MT/s          | 1        | 1.43%   |
| Samsung RAM M378B1G73EB0-YK0 8192MB DIMM DDR3 1600MT/s       | 1        | 1.43%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s        | 1        | 1.43%   |
| Nanya RAM M2F4G64CB88B4N-DI 4GB DIMM DDR3 1600MT/s           | 1        | 1.43%   |
| Nanya RAM 16G3200CL16RGB 16GB DIMM DDR4 3400MT/s             | 1        | 1.43%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s          | 1        | 1.43%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s               | 1        | 1.43%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s      | 1        | 1.43%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s          | 1        | 1.43%   |
| Kingston RAM KHX2400C12D4/16GX 16GB DIMM DDR4 2400MT/s       | 1        | 1.43%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s       | 1        | 1.43%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 1        | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 25       | 44.64%  |
| DDR3    | 24       | 42.86%  |
| SDRAM   | 3        | 5.36%   |
| Unknown | 2        | 3.57%   |
| LPDDR4  | 1        | 1.79%   |
| DDR2    | 1        | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 54       | 98.18%  |
| SODIMM | 1        | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 34.43%  |
| 4096  | 17       | 27.87%  |
| 2048  | 11       | 18.03%  |
| 16384 | 8        | 13.11%  |
| 32768 | 2        | 3.28%   |
| 1024  | 2        | 3.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 21.31%  |
| 1333    | 9        | 14.75%  |
| 2667    | 8        | 13.11%  |
| 3600    | 4        | 6.56%   |
| 3200    | 4        | 6.56%   |
| 2400    | 4        | 6.56%   |
| 3000    | 3        | 4.92%   |
| 2666    | 2        | 3.28%   |
| 1867    | 2        | 3.28%   |
| Unknown | 2        | 3.28%   |
| 3400    | 1        | 1.64%   |
| 3020    | 1        | 1.64%   |
| 2800    | 1        | 1.64%   |
| 2000    | 1        | 1.64%   |
| 1800    | 1        | 1.64%   |
| 1648    | 1        | 1.64%   |
| 1334    | 1        | 1.64%   |
| 1067    | 1        | 1.64%   |
| 1066    | 1        | 1.64%   |
| 800     | 1        | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 3        | 60%     |
| Canon              | 1        | 20%     |
| Brother Industries | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP DeskJet D1360            | 1        | 20%     |
| HP DeskJet 840c             | 1        | 20%     |
| HP Deskjet 3070 B611 series | 1        | 20%     |
| Canon TS3500 series         | 1        | 20%     |
| Brother DCP-7040            | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seiko Epson GT-9800F [Perfection 3200] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 5        | 29.41%  |
| Realtek Semiconductor       | 2        | 11.76%  |
| Microsoft                   | 2        | 11.76%  |
| Xiaomi                      | 1        | 5.88%   |
| Samsung Electronics         | 1        | 5.88%   |
| Microdia                    | 1        | 5.88%   |
| KYE Systems (Mouse Systems) | 1        | 5.88%   |
| IMC Networks                | 1        | 5.88%   |
| Guillemot                   | 1        | 5.88%   |
| Creative Technology         | 1        | 5.88%   |
| Apple                       | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 2        | 11.76%  |
| Xiaomi Mi/Redmi series (PTP)             | 1        | 5.88%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 5.88%   |
| Realtek USB Camera                       | 1        | 5.88%   |
| Realtek HD webcam                        | 1        | 5.88%   |
| Microsoft MicrosoftÂ LifeCam Studio     | 1        | 5.88%   |
| Microsoft LifeCam VX-2000                | 1        | 5.88%   |
| Microdia Sonix USB 2.0 Camera            | 1        | 5.88%   |
| Logitech Webcam C300                     | 1        | 5.88%   |
| Logitech C922 Pro Stream Webcam          | 1        | 5.88%   |
| Logitech BRIO                            | 1        | 5.88%   |
| KYE Systems (Mouse Systems) iSlim 2020AF | 1        | 5.88%   |
| IMC Networks USB2.0 UVC HD Webcam        | 1        | 5.88%   |
| Guillemot Hercules Dualpix Exchange      | 1        | 5.88%   |
| Creative Live! Cam Sync 1080p            | 1        | 5.88%   |
| Apple iPhone 5/5C/5S/6/SE                | 1        | 5.88%   |

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
| 0     | 70       | 85.37%  |
| 1     | 8        | 9.76%   |
| 2     | 3        | 3.66%   |
| 3     | 1        | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 8        | 53.33%  |
| Multimedia controller | 2        | 13.33%  |
| Camera                | 2        | 13.33%  |
| Unassigned class      | 1        | 6.67%   |
| Sound                 | 1        | 6.67%   |
| Chipcard              | 1        | 6.67%   |

