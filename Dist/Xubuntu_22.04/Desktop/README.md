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

Total: 118

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Intel X79                   | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| Dell          | 040DDP A01                  | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| Acer          | Veriton NBU                 | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| ASRock        | N3700-ITX                   | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| ASRock        | A320M-HDV R4.0              | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| HP            | 81C9                        | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| HP            | 8594                        | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| PCWare        | IPMH81G1                    | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Packard Be... | PT890-8237A                 | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| HP            | 1497                        | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX3                 | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Gigabyte      | A320M-S2H-CF                | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| MSI           | A320M PRO-VH                | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Intel         | D525MW AAE93082-401         | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| HP            | 8054                        | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Hardkernel    | ODROID-H2                   | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| MSI           | A320M PRO-VH                | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| HP            | 1589                        | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| ASUSTek       | ET1612I                     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| MSI           | H170M PRO-VDH               | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| ASUSTek       | A68HM-K                     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| ASRock        | 960GC-GS FX                 | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| ASUSTek       | ET1612I                     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| ASUSTek       | Maximus VII HERO            | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | 0DR845                      | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| ASUSTek       | PRIME A320M-K               | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| HP            | 8433 11                     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| ASUSTek       | Z97-C                       | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| ASUSTek       | P8H67-M LE                  | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | P8H67-M LE                  | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | PRIME B450M-A               | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| MSI           | A320M PRO-E                 | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| MSI           | PRO B660M-A DDR4            | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| MSI           | B450M-A PRO MAX             | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| MSI           | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| ASUSTek       | PRIME X470-PRO              | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | X99-A II                    | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Acer          | Veriton M490G               | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| ASRock        | P55 Pro                     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| HP            | 09F8h                       | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.15.0-52-generic          | 15       | 14.71%  |
| 5.15.0-56-generic          | 13       | 12.75%  |
| 5.15.0-47-generic          | 9        | 8.82%   |
| 5.15.0-46-generic          | 9        | 8.82%   |
| 5.15.0-48-generic          | 6        | 5.88%   |
| 5.15.0-27-generic          | 6        | 5.88%   |
| 5.15.0-43-generic          | 5        | 4.9%    |
| 5.15.0-41-generic          | 5        | 4.9%    |
| 5.15.0-53-generic          | 4        | 3.92%   |
| 5.15.0-50-generic          | 4        | 3.92%   |
| 5.15.0-25-generic          | 4        | 3.92%   |
| 5.15.0-40-generic          | 3        | 2.94%   |
| 5.15.0-33-generic          | 2        | 1.96%   |
| 5.15.0-30-generic          | 2        | 1.96%   |
| 5.4.0-122-generic          | 1        | 0.98%   |
| 5.19.13-xanmod1            | 1        | 0.98%   |
| 5.19.0-8.2-liquorix-amd64  | 1        | 0.98%   |
| 5.19.0-15.2-liquorix-amd64 | 1        | 0.98%   |
| 5.17.0-8-generic           | 1        | 0.98%   |
| 5.17.0-1003-oem            | 1        | 0.98%   |
| 5.15.0-57-generic          | 1        | 0.98%   |
| 5.15.0-53-lowlatency       | 1        | 0.98%   |
| 5.15.0-50-lowlatency       | 1        | 0.98%   |
| 5.15.0-48-lowlatency       | 1        | 0.98%   |
| 5.15.0-46-lowlatency       | 1        | 0.98%   |
| 5.15.0-39-lowlatency       | 1        | 0.98%   |
| 5.15.0-39-generic          | 1        | 0.98%   |
| 5.15.0-37-generic          | 1        | 0.98%   |
| 5.15.0-18-generic          | 1        | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 90       | 93.75%  |
| 5.19.0  | 2        | 2.08%   |
| 5.17.0  | 2        | 2.08%   |
| 5.4.0   | 1        | 1.04%   |
| 5.19.13 | 1        | 1.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 90       | 93.75%  |
| 5.19    | 3        | 3.13%   |
| 5.17    | 2        | 2.08%   |
| 5.4     | 1        | 1.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 96       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 93       | 96.88%  |
| GNOME | 3        | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 95       | 96.94%  |
| Tty  | 3        | 3.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 81       | 84.38%  |
| GDM3    | 8        | 8.33%   |
| Unknown | 6        | 6.25%   |
| GDM     | 1        | 1.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 28       | 29.17%  |
| fr_FR | 20       | 20.83%  |
| it_IT | 13       | 13.54%  |
| de_DE | 12       | 12.5%   |
| pt_BR | 5        | 5.21%   |
| en_CA | 4        | 4.17%   |
| ru_RU | 3        | 3.13%   |
| en_GB | 2        | 2.08%   |
| sv_SE | 1        | 1.04%   |
| pl_PL | 1        | 1.04%   |
| nl_NL | 1        | 1.04%   |
| hu_HU | 1        | 1.04%   |
| fr_CA | 1        | 1.04%   |
| es_CO | 1        | 1.04%   |
| es_AR | 1        | 1.04%   |
| en_ZA | 1        | 1.04%   |
| en_AU | 1        | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 60       | 61.86%  |
| EFI  | 37       | 38.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 87       | 90.63%  |
| Overlay | 3        | 3.13%   |
| Btrfs   | 3        | 3.13%   |
| Zfs     | 2        | 2.08%   |
| Ext3    | 1        | 1.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 60       | 60.61%  |
| Unknown | 25       | 25.25%  |
| MBR     | 14       | 14.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 76.04%  |
| Yes       | 23       | 23.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 59.79%  |
| Yes       | 39       | 40.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 30       | 31.25%  |
| MSI                 | 15       | 15.63%  |
| Hewlett-Packard     | 11       | 11.46%  |
| Gigabyte Technology | 7        | 7.29%   |
| Dell                | 7        | 7.29%   |
| Lenovo              | 6        | 6.25%   |
| ASRock              | 6        | 6.25%   |
| PCWare              | 2        | 2.08%   |
| Intel               | 2        | 2.08%   |
| Acer                | 2        | 2.08%   |
| Packard Bell        | 1        | 1.04%   |
| MACHINIST           | 1        | 1.04%   |
| Itautec             | 1        | 1.04%   |
| Hardkernel          | 1        | 1.04%   |
| Fujitsu             | 1        | 1.04%   |
| Foxconn             | 1        | 1.04%   |
| eMachines           | 1        | 1.04%   |
| Unknown             | 1        | 1.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 4        | 4.17%   |
| Dell OptiPlex 7010                 | 3        | 3.13%   |
| MSI MS-7D46                        | 2        | 2.08%   |
| MSI MS-7D43                        | 2        | 2.08%   |
| MSI MS-7C52                        | 2        | 2.08%   |
| ASUS K30AD_M31AD_M51AD             | 2        | 2.08%   |
| PCWare IPX1800E2                   | 1        | 1.04%   |
| PCWare IPMH81G1                    | 1        | 1.04%   |
| Packard Bell IMEDIA X9305          | 1        | 1.04%   |
| MSI MS-7D25                        | 1        | 1.04%   |
| MSI MS-7C91                        | 1        | 1.04%   |
| MSI MS-7C08                        | 1        | 1.04%   |
| MSI MS-7B98                        | 1        | 1.04%   |
| MSI MS-7A32                        | 1        | 1.04%   |
| MSI MS-7982                        | 1        | 1.04%   |
| MSI MS-7529                        | 1        | 1.04%   |
| MSI MS-7309                        | 1        | 1.04%   |
| MSI Hyrican PC A320M PRO-E         | 1        | 1.04%   |
| MACHINIST X99-RS9 V2.0             | 1        | 1.04%   |
| Lenovo V530S-07ICB 10TX0010PB      | 1        | 1.04%   |
| Lenovo ThinkCentre M90p 3282A9G    | 1        | 1.04%   |
| Lenovo ThinkCentre M83 10AM0010US  | 1        | 1.04%   |
| Lenovo ThinkCentre M72e 32675L2    | 1        | 1.04%   |
| Lenovo ThinkCentre M58 7373A5G     | 1        | 1.04%   |
| Lenovo ThinkCentre M32 10BV000CMD  | 1        | 1.04%   |
| Itautec Infoway ST-4273            | 1        | 1.04%   |
| Intel DH61AG AAG23736-507          | 1        | 1.04%   |
| Intel D525MW AAE93082-401          | 1        | 1.04%   |
| HP Z420 Workstation                | 1        | 1.04%   |
| HP Z1 Entry Tower G5               | 1        | 1.04%   |
| HP ProDesk 400 G2 MT (TPM DP)      | 1        | 1.04%   |
| HP Pavilion Wave Desktop 600-a0xx  | 1        | 1.04%   |
| HP Pavilion Desktop 590-p0xxx      | 1        | 1.04%   |
| HP EliteDesk 800 G5 Desktop Mini   | 1        | 1.04%   |
| HP EliteDesk 800 G2 SFF            | 1        | 1.04%   |
| HP EliteDesk 800 G1 SFF            | 1        | 1.04%   |
| HP Compaq dc7600 Small Form Factor | 1        | 1.04%   |
| HP Compaq 8200 Elite SFF PC        | 1        | 1.04%   |
| HP Compaq 6200 Pro MT PC           | 1        | 1.04%   |
| Hardkernel ODROID-H2               | 1        | 1.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 8        | 8.33%   |
| Dell OptiPlex             | 7        | 7.29%   |
| Lenovo ThinkCentre        | 5        | 5.21%   |
| ASUS All                  | 4        | 4.17%   |
| HP EliteDesk              | 3        | 3.13%   |
| HP Compaq                 | 3        | 3.13%   |
| ASUS TUF                  | 3        | 3.13%   |
| MSI MS-7D46               | 2        | 2.08%   |
| MSI MS-7D43               | 2        | 2.08%   |
| MSI MS-7C52               | 2        | 2.08%   |
| HP Pavilion               | 2        | 2.08%   |
| ASUS P8H61-M              | 2        | 2.08%   |
| ASUS K30AD                | 2        | 2.08%   |
| Acer Veriton              | 2        | 2.08%   |
| PCWare IPX1800E2          | 1        | 1.04%   |
| PCWare IPMH81G1           | 1        | 1.04%   |
| Packard Bell IMEDIA       | 1        | 1.04%   |
| MSI MS-7D25               | 1        | 1.04%   |
| MSI MS-7C91               | 1        | 1.04%   |
| MSI MS-7C08               | 1        | 1.04%   |
| MSI MS-7B98               | 1        | 1.04%   |
| MSI MS-7A32               | 1        | 1.04%   |
| MSI MS-7982               | 1        | 1.04%   |
| MSI MS-7529               | 1        | 1.04%   |
| MSI MS-7309               | 1        | 1.04%   |
| MSI Hyrican               | 1        | 1.04%   |
| MACHINIST X99-RS9         | 1        | 1.04%   |
| Lenovo V530S-07ICB        | 1        | 1.04%   |
| Itautec Infoway           | 1        | 1.04%   |
| Intel DH61AG              | 1        | 1.04%   |
| Intel D525MW              | 1        | 1.04%   |
| HP Z420                   | 1        | 1.04%   |
| HP Z1                     | 1        | 1.04%   |
| HP ProDesk                | 1        | 1.04%   |
| Hardkernel ODROID-H2      | 1        | 1.04%   |
| Gigabyte Z77-DS3H         | 1        | 1.04%   |
| Gigabyte GA-MA790FXT-UD5P | 1        | 1.04%   |
| Gigabyte GA-78LMT-USB3    | 1        | 1.04%   |
| Gigabyte G33M-DS2R        | 1        | 1.04%   |
| Gigabyte AB350-Gaming     | 1        | 1.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 13       | 13.54%  |
| 2018 | 12       | 12.5%   |
| 2012 | 8        | 8.33%   |
| 2010 | 8        | 8.33%   |
| 2019 | 7        | 7.29%   |
| 2013 | 7        | 7.29%   |
| 2021 | 6        | 6.25%   |
| 2017 | 6        | 6.25%   |
| 2011 | 5        | 5.21%   |
| 2020 | 4        | 4.17%   |
| 2016 | 4        | 4.17%   |
| 2015 | 4        | 4.17%   |
| 2009 | 4        | 4.17%   |
| 2007 | 3        | 3.13%   |
| 2022 | 2        | 2.08%   |
| 2008 | 1        | 1.04%   |
| 2006 | 1        | 1.04%   |
| 2005 | 1        | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 96       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 91       | 94.79%  |
| Enabled  | 5        | 5.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 96       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 22       | 22.92%  |
| 16.01-24.0  | 22       | 22.92%  |
| 3.01-4.0    | 19       | 19.79%  |
| 8.01-16.0   | 13       | 13.54%  |
| 32.01-64.0  | 10       | 10.42%  |
| 24.01-32.0  | 4        | 4.17%   |
| 1.01-2.0    | 4        | 4.17%   |
| 2.01-3.0    | 1        | 1.04%   |
| 64.01-256.0 | 1        | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 47       | 46.53%  |
| 3.01-4.0  | 16       | 15.84%  |
| 2.01-3.0  | 15       | 14.85%  |
| 4.01-8.0  | 12       | 11.88%  |
| 8.01-16.0 | 5        | 4.95%   |
| 0.51-1.0  | 5        | 4.95%   |
| 0.01-0.5  | 1        | 0.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 39.18%  |
| 2      | 26       | 26.8%   |
| 3      | 16       | 16.49%  |
| 4      | 9        | 9.28%   |
| 5      | 4        | 4.12%   |
| 6      | 2        | 2.06%   |
| 10     | 1        | 1.03%   |
| 7      | 1        | 1.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 52       | 53.61%  |
| No        | 45       | 46.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 65.63%  |
| Yes       | 33       | 34.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 78.13%  |
| Yes       | 21       | 21.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| France       | 18       | 18.56%  |
| Germany      | 15       | 15.46%  |
| Italy        | 12       | 12.37%  |
| USA          | 9        | 9.28%   |
| Brazil       | 6        | 6.19%   |
| Sweden       | 5        | 5.15%   |
| Canada       | 5        | 5.15%   |
| UK           | 2        | 2.06%   |
| Russia       | 2        | 2.06%   |
| Poland       | 2        | 2.06%   |
| Netherlands  | 2        | 2.06%   |
| Greece       | 2        | 2.06%   |
| Belgium      | 2        | 2.06%   |
| Belarus      | 2        | 2.06%   |
| Taiwan       | 1        | 1.03%   |
| South Africa | 1        | 1.03%   |
| Slovenia     | 1        | 1.03%   |
| Portugal     | 1        | 1.03%   |
| Norway       | 1        | 1.03%   |
| Iran         | 1        | 1.03%   |
| Indonesia    | 1        | 1.03%   |
| Hungary      | 1        | 1.03%   |
| Guernsey     | 1        | 1.03%   |
| Guadeloupe   | 1        | 1.03%   |
| Colombia     | 1        | 1.03%   |
| Australia    | 1        | 1.03%   |
| Argentina    | 1        | 1.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 5        | 5.05%   |
| Berlin               | 3        | 3.03%   |
| Stuttgart            | 2        | 2.02%   |
| Clermont-Ferrand     | 2        | 2.02%   |
| Biella               | 2        | 2.02%   |
| Żywiec              | 1        | 1.01%   |
| Wettringen           | 1        | 1.01%   |
| Washington           | 1        | 1.01%   |
| Waghausel            | 1        | 1.01%   |
| Waarder              | 1        | 1.01%   |
| Vohenstrauss         | 1        | 1.01%   |
| Vohburg an der Donau | 1        | 1.01%   |
| Vicenza              | 1        | 1.01%   |
| Västerås           | 1        | 1.01%   |
| Valparaiso de Goias  | 1        | 1.01%   |
| Uppsala              | 1        | 1.01%   |
| Tourouvre            | 1        | 1.01%   |
| Toronto              | 1        | 1.01%   |
| The Hague            | 1        | 1.01%   |
| Teresina             | 1        | 1.01%   |
| Tehran               | 1        | 1.01%   |
| Taichung             | 1        | 1.01%   |
| Surrey               | 1        | 1.01%   |
| St Peter Port        | 1        | 1.01%   |
| Sölvesborg          | 1        | 1.01%   |
| Sassari              | 1        | 1.01%   |
| Santiago de Cali     | 1        | 1.01%   |
| Salzgitter           | 1        | 1.01%   |
| Sainte-Rose          | 1        | 1.01%   |
| Saint-Eustache       | 1        | 1.01%   |
| Saint-Denis          | 1        | 1.01%   |
| Roubaix              | 1        | 1.01%   |
| Rio de Janeiro       | 1        | 1.01%   |
| Rho                  | 1        | 1.01%   |
| Poitiers             | 1        | 1.01%   |
| Pocatello            | 1        | 1.01%   |
| Pieris               | 1        | 1.01%   |
| Peterborough         | 1        | 1.01%   |
| Pescara              | 1        | 1.01%   |
| Perth-Andover        | 1        | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 34       | 51     | 18.68%  |
| Seagate             | 27       | 38     | 14.84%  |
| Samsung Electronics | 27       | 36     | 14.84%  |
| Toshiba             | 16       | 16     | 8.79%   |
| Kingston            | 12       | 15     | 6.59%   |
| Hitachi             | 10       | 18     | 5.49%   |
| SanDisk             | 8        | 9      | 4.4%    |
| Crucial             | 8        | 12     | 4.4%    |
| PNY                 | 3        | 3      | 1.65%   |
| Patriot             | 3        | 3      | 1.65%   |
| HGST                | 3        | 4      | 1.65%   |
| China               | 3        | 3      | 1.65%   |
| Unknown             | 2        | 2      | 1.1%    |
| TEXTORM             | 2        | 2      | 1.1%    |
| Maxtor              | 2        | 2      | 1.1%    |
| Intel               | 2        | 2      | 1.1%    |
| ASMT                | 2        | 5      | 1.1%    |
| XPG                 | 1        | 1      | 0.55%   |
| Vaseky              | 1        | 1      | 0.55%   |
| USB3.0              | 1        | 2      | 0.55%   |
| SK hynix            | 1        | 1      | 0.55%   |
| Silicon Motion      | 1        | 1      | 0.55%   |
| Phison Electronics  | 1        | 2      | 0.55%   |
| PHD 3.0             | 1        | 1      | 0.55%   |
| OCZ                 | 1        | 1      | 0.55%   |
| Lexar               | 1        | 1      | 0.55%   |
| KIOXIA              | 1        | 1      | 0.55%   |
| KingFast            | 1        | 1      | 0.55%   |
| KingDian            | 1        | 1      | 0.55%   |
| Intenso             | 1        | 1      | 0.55%   |
| HGST HUS            | 1        | 1      | 0.55%   |
| Emtec               | 1        | 1      | 0.55%   |
| CHN25SATAS1         | 1        | 1      | 0.55%   |
| AMD                 | 1        | 1      | 0.55%   |
| Unknown             | 1        | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Crucial CT480BX500SSD1 480GB     | 5        | 2.31%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 1.85%   |
| Toshiba HDWD110 1TB              | 3        | 1.39%   |
| Samsung SSD 840 Series 120GB     | 3        | 1.39%   |
| Kingston SA400S37480G 480GB SSD  | 3        | 1.39%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 0.93%   |
| Toshiba DT01ACA200 2TB           | 2        | 0.93%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.93%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.93%   |
| TEXTORM BM5 240GB SSD            | 2        | 0.93%   |
| Seagate ST500LM000-1EJ162 500GB  | 2        | 0.93%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.93%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 0.93%   |
| Seagate ST31000528AS 1TB         | 2        | 0.93%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.93%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.93%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.93%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.93%   |
| Samsung HD250HJ 250GB            | 2        | 0.93%   |
| Hitachi HDS721010CLA332 1TB      | 2        | 0.93%   |
| Hitachi HDP725050GLA360 500GB    | 2        | 0.93%   |
| XPG GAMMIX S11L 256GB            | 1        | 0.46%   |
| WDC WUH721816ALE6L4 16TB         | 1        | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.46%   |
| WDC WDS250G2B0B-00YS70 250GB SSD | 1        | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.46%   |
| WDC WD800JD-75MSA3 80GB          | 1        | 0.46%   |
| WDC WD800JD-22MSA1 80GB          | 1        | 0.46%   |
| WDC WD740ADFD-00NLR5 74GB        | 1        | 0.46%   |
| WDC WD6400BPVT-80HXZT1 640GB     | 1        | 0.46%   |
| WDC WD6400BEVT-80A0RT0 640GB     | 1        | 0.46%   |
| WDC WD5003AZEX-00S3DA0 500GB     | 1        | 0.46%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1        | 0.46%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 0.46%   |
| WDC WD5000AVCS-612DY1 500GB      | 1        | 0.46%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.46%   |
| WDC WD5000AAKS-00UU3A0 500GB     | 1        | 0.46%   |
| WDC WD40PURX-78AKYY0 4TB         | 1        | 0.46%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 1        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 48     | 32.32%  |
| Seagate             | 27       | 37     | 27.27%  |
| Toshiba             | 13       | 13     | 13.13%  |
| Hitachi             | 10       | 18     | 10.1%   |
| Samsung Electronics | 8        | 12     | 8.08%   |
| HGST                | 3        | 4      | 3.03%   |
| ASMT                | 2        | 5      | 2.02%   |
| USB3.0              | 1        | 2      | 1.01%   |
| Unknown             | 1        | 1      | 1.01%   |
| PHD 3.0             | 1        | 1      | 1.01%   |
| Maxtor              | 1        | 1      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 17     | 24.24%  |
| Kingston            | 10       | 11     | 15.15%  |
| Crucial             | 8        | 12     | 12.12%  |
| SanDisk             | 7        | 8      | 10.61%  |
| WDC                 | 3        | 3      | 4.55%   |
| Toshiba             | 3        | 3      | 4.55%   |
| Patriot             | 3        | 3      | 4.55%   |
| China               | 3        | 3      | 4.55%   |
| TEXTORM             | 2        | 2      | 3.03%   |
| PNY                 | 2        | 2      | 3.03%   |
| Intel               | 2        | 2      | 3.03%   |
| Vaseky              | 1        | 1      | 1.52%   |
| OCZ                 | 1        | 1      | 1.52%   |
| Maxtor              | 1        | 1      | 1.52%   |
| KingFast            | 1        | 1      | 1.52%   |
| KingDian            | 1        | 1      | 1.52%   |
| Intenso             | 1        | 1      | 1.52%   |
| Unknown             | 1        | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 74       | 142    | 50%     |
| SSD     | 53       | 73     | 35.81%  |
| NVMe    | 16       | 21     | 10.81%  |
| Unknown | 4        | 4      | 2.7%    |
| MMC     | 1        | 1      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 93       | 201    | 78.15%  |
| NVMe | 16       | 21     | 13.45%  |
| SAS  | 9        | 18     | 7.56%   |
| MMC  | 1        | 1      | 0.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 76       | 131    | 53.15%  |
| 0.51-1.0   | 37       | 46     | 25.87%  |
| 1.01-2.0   | 13       | 15     | 9.09%   |
| 3.01-4.0   | 11       | 16     | 7.69%   |
| 2.01-3.0   | 3        | 3      | 2.1%    |
| 4.01-10.0  | 2        | 3      | 1.4%    |
| 10.01-20.0 | 1        | 1      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 24       | 24.49%  |
| 251-500        | 22       | 22.45%  |
| 1001-2000      | 15       | 15.31%  |
| 501-1000       | 13       | 13.27%  |
| More than 3000 | 12       | 12.24%  |
| 2001-3000      | 5        | 5.1%    |
| 21-50          | 3        | 3.06%   |
| 1-20           | 3        | 3.06%   |
| 51-100         | 1        | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 19       | 19.19%  |
| 21-50          | 18       | 18.18%  |
| 1-20           | 17       | 17.17%  |
| 101-250        | 16       | 16.16%  |
| 51-100         | 9        | 9.09%   |
| 1001-2000      | 6        | 6.06%   |
| 2001-3000      | 5        | 5.05%   |
| 501-1000       | 5        | 5.05%   |
| More than 3000 | 4        | 4.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 8%      |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 4%      |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 4%      |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 4%      |
| WDC WD20EFRX-68AX9N0 2TB          | 1        | 1      | 4%      |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 4%      |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 4%      |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 4%      |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 4%      |
| WDC WD1003FBYX-01Y7B1 1TB         | 1        | 1      | 4%      |
| Seagate ST9250410AS 250GB         | 1        | 1      | 4%      |
| Seagate ST3750840AS 752GB         | 1        | 1      | 4%      |
| Seagate ST3250318AS 250GB         | 1        | 2      | 4%      |
| Samsung Electronics SP2514N 250GB | 1        | 1      | 4%      |
| Samsung Electronics HM321HI 320GB | 1        | 2      | 4%      |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 4%      |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 4%      |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 4%      |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 4%      |
| Hitachi HDS722540VLAT20 40GB      | 1        | 1      | 4%      |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 4%      |
| Hitachi HCP725032GLA380 320GB     | 1        | 2      | 4%      |
| Crucial CT128MX100SSD1 128GB      | 1        | 1      | 4%      |
| ASMT ASMT105x 80GB                | 1        | 4      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 9      | 37.5%   |
| Samsung Electronics | 4        | 6      | 16.67%  |
| Seagate             | 3        | 4      | 12.5%   |
| Hitachi             | 3        | 4      | 12.5%   |
| Toshiba             | 2        | 2      | 8.33%   |
| Maxtor              | 1        | 1      | 4.17%   |
| Crucial             | 1        | 1      | 4.17%   |
| ASMT                | 1        | 4      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 36.36%  |
| Samsung Electronics | 4        | 6      | 18.18%  |
| Seagate             | 3        | 4      | 13.64%  |
| Hitachi             | 3        | 4      | 13.64%  |
| Toshiba             | 2        | 2      | 9.09%   |
| Maxtor              | 1        | 1      | 4.55%   |
| ASMT                | 1        | 4      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 29     | 95%     |
| SSD  | 1        | 2      | 5%      |

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
| Works    | 52       | 108    | 46.02%  |
| Detected | 42       | 102    | 37.17%  |
| Malfunc  | 19       | 31     | 16.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 63       | 51.22%  |
| AMD                          | 28       | 22.76%  |
| Samsung Electronics          | 5        | 4.07%   |
| ASMedia Technology           | 5        | 4.07%   |
| VIA Technologies             | 3        | 2.44%   |
| Nvidia                       | 3        | 2.44%   |
| Kingston Technology Company  | 3        | 2.44%   |
| JMicron Technology           | 3        | 2.44%   |
| Silicon Motion               | 2        | 1.63%   |
| SK hynix                     | 1        | 0.81%   |
| Shenzhen Longsys Electronics | 1        | 0.81%   |
| SanDisk                      | 1        | 0.81%   |
| Realtek Semiconductor        | 1        | 0.81%   |
| Phison Electronics           | 1        | 0.81%   |
| Marvell Technology Group     | 1        | 0.81%   |
| KIOXIA                       | 1        | 0.81%   |
| Adaptec                      | 1        | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 10.37%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 4.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 4.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 3.66%   |
| AMD FCH SATA Controller D                                                               | 6        | 3.66%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 3.05%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 3.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.83%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.83%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.83%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.83%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 1.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.22%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.22%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 1.22%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.22%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.22%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.22%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.61%   |
| VIA Serial ATA Controller                                                               | 1        | 0.61%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 0.61%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1        | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 80       | 64%     |
| IDE  | 23       | 18.4%   |
| NVMe | 16       | 12.8%   |
| RAID | 5        | 4%      |
| SAS  | 1        | 0.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 65       | 67.71%  |
| AMD    | 31       | 32.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 3.09%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 2.06%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 2.06%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 2.06%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 2.06%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 2.06%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 2.06%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 2.06%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 2.06%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 2        | 2.06%   |
| Intel 12th Gen Core i7-12700                | 2        | 2.06%   |
| Intel 12th Gen Core i3-12100                | 2        | 2.06%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 2.06%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 2.06%   |
| AMD Phenom II X4 955 Processor              | 2        | 2.06%   |
| AMD FX-6300 Six-Core Processor              | 2        | 2.06%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 1.03%   |
| Intel Xeon CPU E5-2666 v3 @ 2.90GHz         | 1        | 1.03%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 1.03%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 1.03%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.03%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.03%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1        | 1.03%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.03%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 1        | 1.03%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.03%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.03%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.03%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 1.03%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.03%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.03%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.03%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1        | 1.03%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.03%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.03%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 1.03%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.03%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 1.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 24       | 24.74%  |
| AMD Ryzen 5       | 12       | 12.37%  |
| Intel Core i3     | 10       | 10.31%  |
| Intel Core i7     | 9        | 9.28%   |
| Other             | 5        | 5.15%   |
| Intel Celeron     | 5        | 5.15%   |
| Intel Core 2 Duo  | 4        | 4.12%   |
| Intel Xeon        | 3        | 3.09%   |
| AMD Ryzen 7       | 3        | 3.09%   |
| Intel Core 2 Quad | 2        | 2.06%   |
| AMD Ryzen 9       | 2        | 2.06%   |
| AMD Ryzen 3       | 2        | 2.06%   |
| AMD Phenom II X4  | 2        | 2.06%   |
| AMD FX            | 2        | 2.06%   |
| AMD Athlon II X2  | 2        | 2.06%   |
| Intel Pentium 4   | 1        | 1.03%   |
| Intel Pentium     | 1        | 1.03%   |
| Intel Atom        | 1        | 1.03%   |
| AMD Sempron       | 1        | 1.03%   |
| AMD Ryzen 7 PRO   | 1        | 1.03%   |
| AMD Phenom II X6  | 1        | 1.03%   |
| AMD Athlon II     | 1        | 1.03%   |
| AMD Athlon 64 X2  | 1        | 1.03%   |
| AMD Athlon        | 1        | 1.03%   |
| AMD A10           | 1        | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 43       | 43.88%  |
| 2      | 24       | 24.49%  |
| 6      | 15       | 15.31%  |
| 8      | 6        | 6.12%   |
| 12     | 4        | 4.08%   |
| 3      | 2        | 2.04%   |
| 1      | 2        | 2.04%   |
| 14     | 1        | 1.02%   |
| 10     | 1        | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 96       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 51       | 53.13%  |
| 1      | 45       | 46.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 96       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 36.08%  |
| 0x306c3    | 6        | 6.19%   |
| 0x206a7    | 6        | 6.19%   |
| 0x306a9    | 5        | 5.15%   |
| 0x0800820d | 4        | 4.12%   |
| 0x106e5    | 3        | 3.09%   |
| 0x08701021 | 3        | 3.09%   |
| 0x010000c8 | 3        | 3.09%   |
| 0x906ea    | 2        | 2.06%   |
| 0x90672    | 2        | 2.06%   |
| 0x506e3    | 2        | 2.06%   |
| 0x206d7    | 2        | 2.06%   |
| 0x10676    | 2        | 2.06%   |
| 0x06000852 | 2        | 2.06%   |
| 0xb0671    | 1        | 1.03%   |
| 0xa0653    | 1        | 1.03%   |
| 0x906ed    | 1        | 1.03%   |
| 0x906eb    | 1        | 1.03%   |
| 0x706a1    | 1        | 1.03%   |
| 0x6fb      | 1        | 1.03%   |
| 0x406c3    | 1        | 1.03%   |
| 0x306f2    | 1        | 1.03%   |
| 0x20652    | 1        | 1.03%   |
| 0x106ca    | 1        | 1.03%   |
| 0x1067a    | 1        | 1.03%   |
| 0x0a50000c | 1        | 1.03%   |
| 0x08701013 | 1        | 1.03%   |
| 0x08600106 | 1        | 1.03%   |
| 0x08108109 | 1        | 1.03%   |
| 0x08101016 | 1        | 1.03%   |
| 0x08001138 | 1        | 1.03%   |
| 0x08001137 | 1        | 1.03%   |
| 0x0700010f | 1        | 1.03%   |
| 0x010000c7 | 1        | 1.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 12       | 12.37%  |
| Haswell          | 11       | 11.34%  |
| Zen 2            | 8        | 8.25%   |
| KabyLake         | 8        | 8.25%   |
| IvyBridge        | 8        | 8.25%   |
| Zen+             | 7        | 7.22%   |
| K10              | 6        | 6.19%   |
| Zen              | 4        | 4.12%   |
| Skylake          | 4        | 4.12%   |
| Penryn           | 4        | 4.12%   |
| Piledriver       | 3        | 3.09%   |
| Nehalem          | 3        | 3.09%   |
| Unknown          | 3        | 3.09%   |
| Zen 3            | 2        | 2.06%   |
| Silvermont       | 2        | 2.06%   |
| Core             | 2        | 2.06%   |
| Alderlake Hybrid | 2        | 2.06%   |
| Westmere         | 1        | 1.03%   |
| NetBurst         | 1        | 1.03%   |
| K8 Hammer        | 1        | 1.03%   |
| Jaguar           | 1        | 1.03%   |
| Goldmont plus    | 1        | 1.03%   |
| CometLake        | 1        | 1.03%   |
| Broadwell        | 1        | 1.03%   |
| Bonnell          | 1        | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 45       | 42.86%  |
| Nvidia | 36       | 34.29%  |
| AMD    | 24       | 22.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 7.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 4.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 4.76%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 3.81%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 3.81%   |
| Intel HD Graphics 530                                                       | 4        | 3.81%   |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 1.9%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.9%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.9%    |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.9%    |
| Intel HD Graphics 630                                                       | 2        | 1.9%    |
| Intel AlderLake-S GT1                                                       | 2        | 1.9%    |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.9%    |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.9%    |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 1.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.9%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.9%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.9%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.95%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.95%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.95%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.95%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 0.95%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.95%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.95%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 0.95%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.95%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.95%   |
| Nvidia GK104 [GeForce GTX 690]                                              | 1        | 0.95%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.95%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 0.95%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 0.95%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 0.95%   |
| Nvidia G84 [GeForce 8600 GS]                                                | 1        | 0.95%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 37       | 38.54%  |
| 1 x Nvidia     | 32       | 33.33%  |
| 1 x AMD        | 22       | 22.92%  |
| Intel + Nvidia | 3        | 3.13%   |
| Intel + AMD    | 1        | 1.04%   |
| AMD + Nvidia   | 1        | 1.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 71       | 73.96%  |
| Proprietary | 22       | 22.92%  |
| Unknown     | 3        | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 60       | 61.86%  |
| 1.01-2.0   | 14       | 14.43%  |
| 0.51-1.0   | 9        | 9.28%   |
| 3.01-4.0   | 6        | 6.19%   |
| 0.01-0.5   | 6        | 6.19%   |
| 7.01-8.0   | 1        | 1.03%   |
| 5.01-6.0   | 1        | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 15       | 14.85%  |
| Hewlett-Packard         | 14       | 13.86%  |
| Dell                    | 12       | 11.88%  |
| Acer                    | 7        | 6.93%   |
| AOC                     | 6        | 5.94%   |
| ViewSonic               | 5        | 4.95%   |
| Iiyama                  | 5        | 4.95%   |
| Goldstar                | 5        | 4.95%   |
| Philips                 | 4        | 3.96%   |
| BenQ                    | 3        | 2.97%   |
| Lenovo                  | 2        | 1.98%   |
| Fujitsu Siemens         | 2        | 1.98%   |
| Ancor Communications    | 2        | 1.98%   |
| ___                     | 1        | 0.99%   |
| Vestel Elektronik       | 1        | 0.99%   |
| Unknown                 | 1        | 0.99%   |
| Toshiba                 | 1        | 0.99%   |
| TEO                     | 1        | 0.99%   |
| TCL                     | 1        | 0.99%   |
| Packard Bell            | 1        | 0.99%   |
| Mi                      | 1        | 0.99%   |
| MAG                     | 1        | 0.99%   |
| LG Electronics          | 1        | 0.99%   |
| Gateway                 | 1        | 0.99%   |
| Envision Peripherals    | 1        | 0.99%   |
| eMachines               | 1        | 0.99%   |
| Elo Touch               | 1        | 0.99%   |
| Eizo                    | 1        | 0.99%   |
| Denver                  | 1        | 0.99%   |
| Chi Mei Optoelectronics | 1        | 0.99%   |
| ASUSTek Computer        | 1        | 0.99%   |
| Unknown                 | 1        | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch               | 2        | 1.89%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                   | 2        | 1.89%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch           | 2        | 1.89%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                   | 1        | 0.94%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch        | 1        | 0.94%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch           | 1        | 0.94%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch         | 1        | 0.94%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch | 1        | 0.94%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                | 1        | 0.94%   |
| Toshiba TV TSB0109 1920x1080 1594x900mm 72.1-inch                    | 1        | 0.94%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                      | 1        | 0.94%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                     | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                     | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch | 1        | 0.94%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch | 1        | 0.94%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch    | 1        | 0.94%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch   | 1        | 0.94%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch    | 1        | 0.94%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1        | 0.94%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch    | 1        | 0.94%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 1        | 0.94%   |
| Samsung Electronics LCD Monitor SAM07BB 1360x768 410x256mm 19.0-inch | 1        | 0.94%   |
| Samsung Electronics LCD Monitor S22E450 1920x1080                    | 1        | 0.94%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch    | 1        | 0.94%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch    | 1        | 0.94%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1        | 0.94%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch              | 1        | 0.94%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch              | 1        | 0.94%   |
| Philips 221TE PHLC062 1920x1080 476x268mm 21.5-inch                  | 1        | 0.94%   |
| Packard Bell Viseo 230Ws PKB00C1 1920x1080 509x286mm 23.0-inch       | 1        | 0.94%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                     | 1        | 0.94%   |
| MAG Monitor MAG1901 1280x1024 320x206mm 15.0-inch                    | 1        | 0.94%   |
| LG Electronics LCD Monitor E2442 1920x1080                           | 1        | 0.94%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                 | 1        | 0.94%   |
| Lenovo LCD Monitor LEN60A0 1600x900 430x240mm 19.4-inch              | 1        | 0.94%   |
| Iiyama X2483_2480-DP IVM6129 1920x1080 527x296mm 23.8-inch           | 1        | 0.94%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                | 1        | 0.94%   |
| Iiyama PL2780H IVM6609 1920x1080 600x340mm 27.2-inch                 | 1        | 0.94%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                  | 1        | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 45       | 46.88%  |
| 1280x1024 (SXGA)   | 9        | 9.38%   |
| 1366x768 (WXGA)    | 8        | 8.33%   |
| 1440x900 (WXGA+)   | 6        | 6.25%   |
| 3840x2160 (4K)     | 5        | 5.21%   |
| 1680x1050 (WSXGA+) | 5        | 5.21%   |
| 1600x900 (HD+)     | 4        | 4.17%   |
| 1920x1200 (WUXGA)  | 3        | 3.13%   |
| 2560x1440 (QHD)    | 2        | 2.08%   |
| 1360x768           | 2        | 2.08%   |
| 1024x768 (XGA)     | 2        | 2.08%   |
| 3840x1600          | 1        | 1.04%   |
| 3840x1080          | 1        | 1.04%   |
| 1920x540           | 1        | 1.04%   |
| 1600x1200          | 1        | 1.04%   |
| Unknown            | 1        | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 18       | 17.65%  |
| 23      | 13       | 12.75%  |
| 27      | 10       | 9.8%    |
| 19      | 9        | 8.82%   |
| 18      | 8        | 7.84%   |
| 21      | 7        | 6.86%   |
| 17      | 7        | 6.86%   |
| Unknown | 7        | 6.86%   |
| 20      | 5        | 4.9%    |
| 31      | 4        | 3.92%   |
| 22      | 3        | 2.94%   |
| 15      | 3        | 2.94%   |
| 26      | 2        | 1.96%   |
| 84      | 1        | 0.98%   |
| 72      | 1        | 0.98%   |
| 37      | 1        | 0.98%   |
| 32      | 1        | 0.98%   |
| 25      | 1        | 0.98%   |
| 6       | 1        | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 39       | 40.63%  |
| 401-500     | 30       | 31.25%  |
| 301-350     | 10       | 10.42%  |
| Unknown     | 7        | 7.29%   |
| 601-700     | 4        | 4.17%   |
| 1501-2000   | 2        | 2.08%   |
| 801-900     | 1        | 1.04%   |
| 701-800     | 1        | 1.04%   |
| 351-400     | 1        | 1.04%   |
| 101-200     | 1        | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 57       | 61.96%  |
| 16/10   | 17       | 18.48%  |
| 5/4     | 8        | 8.7%    |
| Unknown | 6        | 6.52%   |
| 4/3     | 3        | 3.26%   |
| 21/9    | 1        | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 32       | 32%     |
| 151-200        | 19       | 19%     |
| 141-150        | 14       | 14%     |
| 301-350        | 11       | 11%     |
| Unknown        | 7        | 7%      |
| 351-500        | 5        | 5%      |
| 251-300        | 5        | 5%      |
| 101-110        | 3        | 3%      |
| More than 1000 | 2        | 2%      |
| 1-40           | 1        | 1%      |
| 501-1000       | 1        | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 71       | 75.53%  |
| 101-120       | 11       | 11.7%   |
| Unknown       | 7        | 7.45%   |
| 121-160       | 3        | 3.19%   |
| More than 240 | 1        | 1.06%   |
| 1-50          | 1        | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 78       | 81.25%  |
| 2     | 11       | 11.46%  |
| 0     | 4        | 4.17%   |
| 3     | 3        | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 63       | 48.46%  |
| Intel                           | 42       | 32.31%  |
| Qualcomm Atheros                | 7        | 5.38%   |
| Ralink Technology               | 3        | 2.31%   |
| Nvidia                          | 3        | 2.31%   |
| D-Link System                   | 2        | 1.54%   |
| Broadcom                        | 2        | 1.54%   |
| TRENDnet                        | 1        | 0.77%   |
| TP-Link                         | 1        | 0.77%   |
| Ralink                          | 1        | 0.77%   |
| Qualcomm Atheros Communications | 1        | 0.77%   |
| NetGear                         | 1        | 0.77%   |
| Microchip Technology            | 1        | 0.77%   |
| Dell                            | 1        | 0.77%   |
| Broadcom Limited                | 1        | 0.77%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 51       | 36.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 7        | 4.96%   |
| Realtek RTL8125 2.5GbE Controller                                          | 5        | 3.55%   |
| Intel I211 Gigabit Network Connection                                      | 5        | 3.55%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 2.13%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 2.13%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 2.13%   |
| Intel Ethernet Connection (2) I218-V                                       | 3        | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 2        | 1.42%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.42%   |
| Intel Ethernet Connection I217-LM                                          | 2        | 1.42%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 1.42%   |
| Intel Ethernet Connection (17) I219-V                                      | 2        | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 1.42%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 1.42%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 1.42%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU] | 1        | 0.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 0.71%   |
| Realtek USB 10/100/1G/2.5G LAN                                             | 1        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 0.71%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 0.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 0.71%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 0.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.71%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                     | 1        | 0.71%   |
| Ralink RT2770 Wireless Adapter                                             | 1        | 0.71%   |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 1        | 0.71%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 0.71%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                     | 1        | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                            | 1        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 0.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 28.57%  |
| Qualcomm Atheros                | 7        | 20%     |
| Intel                           | 7        | 20%     |
| Ralink Technology               | 3        | 8.57%   |
| TRENDnet                        | 1        | 2.86%   |
| TP-Link                         | 1        | 2.86%   |
| Ralink                          | 1        | 2.86%   |
| Qualcomm Atheros Communications | 1        | 2.86%   |
| NetGear                         | 1        | 2.86%   |
| Dell                            | 1        | 2.86%   |
| D-Link System                   | 1        | 2.86%   |
| Broadcom                        | 1        | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 3        | 8.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 5.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 2        | 5.71%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]        | 1        | 2.86%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 1        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 2.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 2.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 2.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 2.86%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 2.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 1        | 2.86%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 1        | 2.86%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                            | 1        | 2.86%   |
| Ralink RT2770 Wireless Adapter                                                    | 1        | 2.86%   |
| Ralink RT2501/RT2573 Wireless Adapter                                             | 1        | 2.86%   |
| Ralink MT7601U Wireless Adapter                                                   | 1        | 2.86%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                            | 1        | 2.86%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 2.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 2.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 2.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                    | 1        | 2.86%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                  | 1        | 2.86%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]    | 1        | 2.86%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                        | 1        | 2.86%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                               | 1        | 2.86%   |
| Intel Wireless 7265                                                               | 1        | 2.86%   |
| Intel Wireless 3160                                                               | 1        | 2.86%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]             | 1        | 2.86%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 2.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 1        | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 59       | 57.84%  |
| Intel                 | 37       | 36.27%  |
| Nvidia                | 3        | 2.94%   |
| D-Link System         | 1        | 0.98%   |
| Broadcom Limited      | 1        | 0.98%   |
| Broadcom              | 1        | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51       | 48.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 4.76%   |
| Intel I211 Gigabit Network Connection                             | 5        | 4.76%   |
| Nvidia MCP61 Ethernet                                             | 3        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.86%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.9%    |
| Intel Ethernet Connection I217-V                                  | 2        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.9%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.9%    |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.9%    |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.9%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.95%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.95%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.95%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.95%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.95%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1        | 0.95%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.95%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                       | 1        | 0.95%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 96       | 73.85%  |
| WiFi     | 33       | 25.38%  |
| Modem    | 1        | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 80.61%  |
| WiFi     | 19       | 19.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 71.88%  |
| 2     | 24       | 25%     |
| 3     | 3        | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 61       | 62.24%  |
| Yes  | 37       | 37.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 9        | 40.91%  |
| Intel                   | 7        | 31.82%  |
| Realtek Semiconductor   | 2        | 9.09%   |
| Broadcom                | 2        | 9.09%   |
| IMC Networks            | 1        | 4.55%   |
| Fujitsu                 | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 40.91%  |
| Intel AX200 Bluetooth                               | 3        | 13.64%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 9.09%   |
| Intel Bluetooth wireless interface                  | 2        | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.55%   |
| Realtek Bluetooth Radio                             | 1        | 4.55%   |
| IMC Networks Bluetooth Radio                        | 1        | 4.55%   |
| Fujitsu Bluetooth Device                            | 1        | 4.55%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 65       | 44.22%  |
| Nvidia                      | 34       | 23.13%  |
| AMD                         | 33       | 22.45%  |
| C-Media Electronics         | 3        | 2.04%   |
| SAVITECH                    | 2        | 1.36%   |
| VIA Technologies            | 1        | 0.68%   |
| Samson Technologies         | 1        | 0.68%   |
| Medeli Electronics          | 1        | 0.68%   |
| Logitech                    | 1        | 0.68%   |
| Lenovo                      | 1        | 0.68%   |
| Kingston Technology         | 1        | 0.68%   |
| GN Netcom                   | 1        | 0.68%   |
| FiiO Electronics Technology | 1        | 0.68%   |
| Creative Labs               | 1        | 0.68%   |
| Corsair                     | 1        | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 6.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8        | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 8        | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 4.76%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5        | 2.98%   |
| Intel Alder Lake-S HD Audio Controller                                            | 5        | 2.98%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 2.98%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 2.38%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 2.38%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 1.79%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 1.79%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 1.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 1.79%   |
| Nvidia TU104 HD Audio Controller                                                  | 2        | 1.19%   |
| Nvidia GT216 HDMI Audio Controller                                                | 2        | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 1.19%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1.19%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 2        | 1.19%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 1.19%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 2        | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 1.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 1.19%   |
| AMD FCH Azalia Controller                                                         | 2        | 1.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 1.19%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 0.6%    |
| SAVITECH PHIREE D1                                                                | 1        | 0.6%    |
| SAVITECH ODAC-revB                                                                | 1        | 0.6%    |
| Samson Technologies Q1U dynamic microphone                                        | 1        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 16       | 20%     |
| Unknown             | 15       | 18.75%  |
| Samsung Electronics | 12       | 15%     |
| Crucial             | 9        | 11.25%  |
| SK hynix            | 5        | 6.25%   |
| Corsair             | 5        | 6.25%   |
| G.Skill             | 4        | 5%      |
| Ramaxel Technology  | 3        | 3.75%   |
| Nanya Technology    | 2        | 2.5%    |
| Micron Technology   | 2        | 2.5%    |
| Unknown             | 2        | 2.5%    |
| Unknown (ABCD)      | 1        | 1.25%   |
| Transcend           | 1        | 1.25%   |
| GLOWAY              | 1        | 1.25%   |
| Elpida              | 1        | 1.25%   |
| ASint Technology    | 1        | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 2        | 2.33%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s         | 2        | 2.33%   |
| Unknown                                                      | 2        | 2.33%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 1        | 1.16%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1        | 1.16%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 1        | 1.16%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 1.16%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1        | 1.16%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 1.16%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                     | 1        | 1.16%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1.16%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                    | 1        | 1.16%   |
| Unknown RAM Module 2GB DIMM DDR2                             | 1        | 1.16%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 1.16%   |
| Unknown RAM Module 1GB DIMM DDR2                             | 1        | 1.16%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s    | 1        | 1.16%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s        | 1        | 1.16%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 1.16%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 1.16%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                 | 1        | 1.16%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                  | 1        | 1.16%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s         | 1        | 1.16%   |
| SK hynix RAM HMT351U7EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.16%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 1        | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1        | 1.16%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1.16%   |
| Samsung RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 1.16%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s        | 1        | 1.16%   |
| Samsung RAM M393B1K70DH0 8GB DIMM DDR3 1866MT/s              | 1        | 1.16%   |
| Samsung RAM M391B5773DH0-CK0 2GB DIMM DDR3 1600MT/s          | 1        | 1.16%   |
| Samsung RAM M391B5673GB0-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 1.16%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s          | 1        | 1.16%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.16%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.16%   |
| Samsung RAM M378B5173BH0-CH9 4GB DIMM DDR3 1867MT/s          | 1        | 1.16%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s          | 1        | 1.16%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s         | 1        | 1.16%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s      | 1        | 1.16%   |
| Ramaxel RAM RMUA5120MB86H9F-2400 4GB DIMM DDR4 2400MT/s      | 1        | 1.16%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s        | 1        | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 43.28%  |
| DDR3    | 29       | 43.28%  |
| SDRAM   | 3        | 4.48%   |
| Unknown | 3        | 4.48%   |
| DDR2    | 2        | 2.99%   |
| LPDDR4  | 1        | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 62       | 93.94%  |
| SODIMM | 4        | 6.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 24       | 32.88%  |
| 4096  | 23       | 31.51%  |
| 2048  | 13       | 17.81%  |
| 16384 | 9        | 12.33%  |
| 1024  | 3        | 4.11%   |
| 32768 | 1        | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 22.97%  |
| 1333    | 11       | 14.86%  |
| 2667    | 9        | 12.16%  |
| 2400    | 6        | 8.11%   |
| 3200    | 5        | 6.76%   |
| 3600    | 3        | 4.05%   |
| 3000    | 3        | 4.05%   |
| Unknown | 3        | 4.05%   |
| 2666    | 2        | 2.7%    |
| 1867    | 2        | 2.7%    |
| 3466    | 1        | 1.35%   |
| 3400    | 1        | 1.35%   |
| 3020    | 1        | 1.35%   |
| 2800    | 1        | 1.35%   |
| 2133    | 1        | 1.35%   |
| 2000    | 1        | 1.35%   |
| 1866    | 1        | 1.35%   |
| 1800    | 1        | 1.35%   |
| 1648    | 1        | 1.35%   |
| 1334    | 1        | 1.35%   |
| 1067    | 1        | 1.35%   |
| 1066    | 1        | 1.35%   |
| 800     | 1        | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 42.86%  |
| Brother Industries  | 2        | 28.57%  |
| Samsung Electronics | 1        | 14.29%  |
| Canon               | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SF-760 Series         | 1        | 14.29%  |
| HP DeskJet D1360              | 1        | 14.29%  |
| HP DeskJet 840c               | 1        | 14.29%  |
| HP Deskjet 3070 B611 series   | 1        | 14.29%  |
| Canon TS3500 series           | 1        | 14.29%  |
| Brother HL-2030 Laser Printer | 1        | 14.29%  |
| Brother DCP-7040              | 1        | 14.29%  |

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
| Microdia                    | 4        | 21.05%  |
| Logitech                    | 4        | 21.05%  |
| Realtek Semiconductor       | 2        | 10.53%  |
| Microsoft                   | 2        | 10.53%  |
| Xiaomi                      | 1        | 5.26%   |
| Samsung Electronics         | 1        | 5.26%   |
| KYE Systems (Mouse Systems) | 1        | 5.26%   |
| IMC Networks                | 1        | 5.26%   |
| Guillemot                   | 1        | 5.26%   |
| Creative Technology         | 1        | 5.26%   |
| Apple                       | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 2        | 10.53%  |
| Xiaomi Mi/Redmi series (PTP)             | 1        | 5.26%   |
| Samsung Galaxy A5 (MTP)                  | 1        | 5.26%   |
| Realtek USB Camera                       | 1        | 5.26%   |
| Realtek Full HD webcam                   | 1        | 5.26%   |
| Microsoft MicrosoftÂ LifeCam Studio     | 1        | 5.26%   |
| Microsoft LifeCam VX-2000                | 1        | 5.26%   |
| Microdia Webcam Vitade AF                | 1        | 5.26%   |
| Microdia USB 2.0 Camera                  | 1        | 5.26%   |
| Microdia Sonix USB 2.0 Camera            | 1        | 5.26%   |
| Microdia Camera                          | 1        | 5.26%   |
| Logitech Webcam C300                     | 1        | 5.26%   |
| Logitech C922 Pro Stream Webcam          | 1        | 5.26%   |
| KYE Systems (Mouse Systems) iSlim 2020AF | 1        | 5.26%   |
| IMC Networks USB2.0 UVC HD Webcam        | 1        | 5.26%   |
| Guillemot Hercules Dualpix Exchange      | 1        | 5.26%   |
| Creative Live! Cam Sync 1080p            | 1        | 5.26%   |
| Apple iPhone5/5C/5S/6                    | 1        | 5.26%   |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Reiner SCT Kartensysteme | 1        | 50%     |
| In Focus Systems         | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack one | 1        | 50%     |
| In Focus Systems EMV Smartcard Reader  | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 84       | 86.6%   |
| 1     | 9        | 9.28%   |
| 2     | 3        | 3.09%   |
| 3     | 1        | 1.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 8        | 50%     |
| Multimedia controller | 2        | 12.5%   |
| Chipcard              | 2        | 12.5%   |
| Camera                | 2        | 12.5%   |
| Unassigned class      | 1        | 6.25%   |
| Sound                 | 1        | 6.25%   |

