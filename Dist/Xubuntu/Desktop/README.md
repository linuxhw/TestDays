Xubuntu - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Xubuntu.

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

Total: 2349

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Intel X79                   | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| MSI           | B75MA-P45                   | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| ASRock        | H61M-ITX                    | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [23dc9112a8](https://linux-hardware.org/?probe=23dc9112a8) | Dec 27, 2022 |
| Gigabyte      | B360M D3H-CF                | [2041ed5cba](https://linux-hardware.org/?probe=2041ed5cba) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| ASUSTek       | P5G41T-M LX                 | [01466a6701](https://linux-hardware.org/?probe=01466a6701) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| ASRock        | A320M-HDV R4.0              | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| Dell          | 0YJPT1 A00                  | [f78b9b1a90](https://linux-hardware.org/?probe=f78b9b1a90) | Dec 22, 2022 |
| HP            | 81C9                        | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| HP            | 8594                        | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| PCWare        | IPMH81G1                    | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8862992776](https://linux-hardware.org/?probe=8862992776) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Gigabyte      | B360M D3H-CF                | [6ea891850f](https://linux-hardware.org/?probe=6ea891850f) | Dec 18, 2022 |
| Packard Be... | PT890-8237A                 | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| Gigabyte      | B360M D3H-CF                | [0679db84af](https://linux-hardware.org/?probe=0679db84af) | Dec 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [51acd303f0](https://linux-hardware.org/?probe=51acd303f0) | Dec 12, 2022 |
| HP            | 1497                        | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| MSI           | MPG X670E CARBON WIFI       | [7968282240](https://linux-hardware.org/?probe=7968282240) | Dec 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| HP            | 2B34                        | [18ec4a2e66](https://linux-hardware.org/?probe=18ec4a2e66) | Dec 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [f6bb91c588](https://linux-hardware.org/?probe=f6bb91c588) | Dec 03, 2022 |
| MSI           | PRO Z690-A DDR4             | [db5a886817](https://linux-hardware.org/?probe=db5a886817) | Dec 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| ASUSTek       | H81M-A                      | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a5cfd24a43](https://linux-hardware.org/?probe=a5cfd24a43) | Nov 18, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| Gigabyte      | H97-HD3                     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| MSI           | MS-7309                     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| ASUSTek       | B150M-C                     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| MSI           | A320M PRO-VH                | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| ASUSTek       | VM40B                       | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [640298162b](https://linux-hardware.org/?probe=640298162b) | Nov 07, 2022 |
| Intel         | D525MW AAE93082-401         | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| MSI           | CSM-H87M-G43                | [43ffdafb80](https://linux-hardware.org/?probe=43ffdafb80) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| Gigabyte      | Z77-DS3H                    | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| HP            | 8054                        | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| eMachines     | EL1358G                     | [48d6ba4c24](https://linux-hardware.org/?probe=48d6ba4c24) | Nov 03, 2022 |
| eMachines     | EL1358G                     | [1acbe713b6](https://linux-hardware.org/?probe=1acbe713b6) | Nov 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| ASUSTek       | P9X79                       | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| ECS           | H81H3-M4                    | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Dell          | 0GY6Y8 A03                  | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Dell          | 0XHGV1 A00                  | [8fad928e72](https://linux-hardware.org/?probe=8fad928e72) | Oct 28, 2022 |
| Gigabyte      | H370 HD3-CF                 | [275bc51aaf](https://linux-hardware.org/?probe=275bc51aaf) | Oct 27, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Hardkernel    | ODROID-H2                   | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| ASRock        | B450M Pro4                  | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| MSI           | A320M PRO-VH                | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| MSI           | A68HM-E33 V2                | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| HP            | 1589                        | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| ASUSTek       | ET1612I                     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| Acer          | EQ35M                       | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| Acer          | EQ35M                       | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| Dell          | 0WF810                      | [dd24119965](https://linux-hardware.org/?probe=dd24119965) | Oct 04, 2022 |
| MSI           | A68HM-E33 V2                | [1001ccbbaf](https://linux-hardware.org/?probe=1001ccbbaf) | Sep 30, 2022 |
| ASUSTek       | B85M-G                      | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| Gigabyte      | H81M-D2W                    | [467845e1c1](https://linux-hardware.org/?probe=467845e1c1) | Sep 28, 2022 |
| ASRock        | 775Dual-VSTA                | [9509fb65dd](https://linux-hardware.org/?probe=9509fb65dd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| MSI           | H170M PRO-VDH               | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| ASUSTek       | P6T                         | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| ASUSTek       | A68HM-K                     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| MSI           | Z77A-G43                    | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| ASRock        | 960GC-GS FX                 | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| ASUSTek       | ET1612I                     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Gigabyte      | H410M S2H                   | [d852f09d43](https://linux-hardware.org/?probe=d852f09d43) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [a0bdfffa04](https://linux-hardware.org/?probe=a0bdfffa04) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [196e6b048b](https://linux-hardware.org/?probe=196e6b048b) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [8e95a850da](https://linux-hardware.org/?probe=8e95a850da) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [499d354033](https://linux-hardware.org/?probe=499d354033) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [a830a7b6e5](https://linux-hardware.org/?probe=a830a7b6e5) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [19ba71f923](https://linux-hardware.org/?probe=19ba71f923) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [ad888e4455](https://linux-hardware.org/?probe=ad888e4455) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [d35bf4c513](https://linux-hardware.org/?probe=d35bf4c513) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [dce51bb6d6](https://linux-hardware.org/?probe=dce51bb6d6) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [3bc232858d](https://linux-hardware.org/?probe=3bc232858d) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [ca79460771](https://linux-hardware.org/?probe=ca79460771) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [1e24243624](https://linux-hardware.org/?probe=1e24243624) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [b0625e01e3](https://linux-hardware.org/?probe=b0625e01e3) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [f97cd53683](https://linux-hardware.org/?probe=f97cd53683) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [cd3fc03204](https://linux-hardware.org/?probe=cd3fc03204) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | 0DR845                      | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Gigabyte      | H510M S2H                   | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| MSI           | Z77A-G43                    | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0R092H                      | [a22af2bad5](https://linux-hardware.org/?probe=a22af2bad5) | Sep 09, 2022 |
| ASRock        | Q1900-ITX                   | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| ASRock        | N68-S3 UCC                  | [31fdd16d2f](https://linux-hardware.org/?probe=31fdd16d2f) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | [24647846ee](https://linux-hardware.org/?probe=24647846ee) | Sep 06, 2022 |
| MSI           | MS-7387                     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| Dell          | 0NV0M7 A02                  | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| ASUSTek       | M4A78T-E                    | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| ECS           | G31T-M9                     | [c3212ee5a3](https://linux-hardware.org/?probe=c3212ee5a3) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [673b33ac0c](https://linux-hardware.org/?probe=673b33ac0c) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [18a2d69632](https://linux-hardware.org/?probe=18a2d69632) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [965107cf86](https://linux-hardware.org/?probe=965107cf86) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [d8f5734dd8](https://linux-hardware.org/?probe=d8f5734dd8) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [b2f37a3080](https://linux-hardware.org/?probe=b2f37a3080) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [91857942dd](https://linux-hardware.org/?probe=91857942dd) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [940fb9c208](https://linux-hardware.org/?probe=940fb9c208) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [10315fa577](https://linux-hardware.org/?probe=10315fa577) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [aedc37e8e4](https://linux-hardware.org/?probe=aedc37e8e4) | Sep 02, 2022 |
| Medion        | H110H4-EM                   | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| HP            | 8433 11                     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| DNI           | SNDTP-1513N 5508015890      | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| ASUSTek       | Z97-C                       | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Intel         | H61                         | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| HP            | 844C                        | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| Gigabyte      | H370 HD3-CF                 | [3f06afc812](https://linux-hardware.org/?probe=3f06afc812) | Aug 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [38fd87d37c](https://linux-hardware.org/?probe=38fd87d37c) | Aug 21, 2022 |
| ASUSTek       | Z10PE-D16 WS                | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| MSI           | X370 KRAIT GAMING           | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| Dell          | 07T4MC A06                  | [d6c22de1e9](https://linux-hardware.org/?probe=d6c22de1e9) | Aug 18, 2022 |
| eMachines     | ET1350                      | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [c4336ae88d](https://linux-hardware.org/?probe=c4336ae88d) | Aug 17, 2022 |
| Dell          | 0YXT71 A00                  | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| Dell          | 0RY007                      | [a863b6949c](https://linux-hardware.org/?probe=a863b6949c) | Aug 16, 2022 |
| ASUSTek       | Z10PE-D16 WS                | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Dell          | 0RY007                      | [592206f3e1](https://linux-hardware.org/?probe=592206f3e1) | Aug 14, 2022 |
| Dell          | 0RY007                      | [05edd2876d](https://linux-hardware.org/?probe=05edd2876d) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| eMachines     | EL1358G                     | [eebc968f87](https://linux-hardware.org/?probe=eebc968f87) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| OEM_MB        | NARRA3                      | [4574011966](https://linux-hardware.org/?probe=4574011966) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | [8454f0f091](https://linux-hardware.org/?probe=8454f0f091) | Aug 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| Gigabyte      | F2A78M-HD2                  | [64b08b679f](https://linux-hardware.org/?probe=64b08b679f) | Aug 05, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| ASUSTek       | P5P43TD PRO                 | [7325fb8135](https://linux-hardware.org/?probe=7325fb8135) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| Intel         | SHARKBAY                    | [bd5b812271](https://linux-hardware.org/?probe=bd5b812271) | Jul 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| ASUSTek       | P5QL/EPU                    | [797c3b1dc2](https://linux-hardware.org/?probe=797c3b1dc2) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| ASUSTek       | P8H67-M LE                  | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| ASUSTek       | P4B-M                       | [a193b562fa](https://linux-hardware.org/?probe=a193b562fa) | Jul 22, 2022 |
| ASUSTek       | P4B-M                       | [5128fcd55d](https://linux-hardware.org/?probe=5128fcd55d) | Jul 22, 2022 |
| MSI           | PRO B660M-A DDR4            | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e2cd5c8d4b](https://linux-hardware.org/?probe=e2cd5c8d4b) | Jul 20, 2022 |
| ASUSTek       | PRIME B450M-A               | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Dell          | 0F6X5P A00                  | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| HP            | 1496                        | [7797b2d6dd](https://linux-hardware.org/?probe=7797b2d6dd) | Jul 14, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | [8a5a5a0987](https://linux-hardware.org/?probe=8a5a5a0987) | Jul 12, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| MSI           | A320M PRO-E                 | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| HP            | 158A                        | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| ASUSTek       | P5KC                        | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | 07T4MC A02                  | [88de707c31](https://linux-hardware.org/?probe=88de707c31) | Jul 08, 2022 |
| Gigabyte      | G41M-ES2L                   | [d1aa8fe23d](https://linux-hardware.org/?probe=d1aa8fe23d) | Jul 05, 2022 |
| Dell          | 0GY6Y8 A03                  | [5703355b59](https://linux-hardware.org/?probe=5703355b59) | Jul 04, 2022 |
| MSI           | PRO B660M-A DDR4            | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [3633eb51d4](https://linux-hardware.org/?probe=3633eb51d4) | Jul 01, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8f90bed577](https://linux-hardware.org/?probe=8f90bed577) | Jul 01, 2022 |
| Dell          | 0GXM1W A00                  | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| ASUSTek       | M5A97 R2.0                  | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Dell          | 0WMJ54 A01                  | [a55837dc17](https://linux-hardware.org/?probe=a55837dc17) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [87b9ce1db1](https://linux-hardware.org/?probe=87b9ce1db1) | Jun 28, 2022 |
| ASUSTek       | M2N-E                       | [47cddfb141](https://linux-hardware.org/?probe=47cddfb141) | Jun 25, 2022 |
| ASUSTek       | M2N-E                       | [ad5514340b](https://linux-hardware.org/?probe=ad5514340b) | Jun 25, 2022 |
| Dell          | 0HN7XN A00                  | [4562c09862](https://linux-hardware.org/?probe=4562c09862) | Jun 24, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [8cf9d783a3](https://linux-hardware.org/?probe=8cf9d783a3) | Jun 23, 2022 |
| MSI           | B450M-A PRO MAX             | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| ASRock        | N68-S3 UCC                  | [5e9cdd75c7](https://linux-hardware.org/?probe=5e9cdd75c7) | Jun 22, 2022 |
| Intel         | D102GGC2 AAD42789-204       | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [515b063f08](https://linux-hardware.org/?probe=515b063f08) | Jun 18, 2022 |
| MSI           | X570-A PRO                  | [fc761acd97](https://linux-hardware.org/?probe=fc761acd97) | Jun 18, 2022 |
| Lenovo        | ThinkCentre M71e 5033AR1    | [dd0f797f78](https://linux-hardware.org/?probe=dd0f797f78) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [f340c1d172](https://linux-hardware.org/?probe=f340c1d172) | Jun 17, 2022 |
| MSI           | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Intel         | DG33BU AAD79951-407         | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| ASRock        | N68-S3 UCC                  | [535126df2b](https://linux-hardware.org/?probe=535126df2b) | Jun 09, 2022 |
| Gigabyte      | H97-HD3                     | [7f48bb6a8a](https://linux-hardware.org/?probe=7f48bb6a8a) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| ASUSTek       | Maximus VII HERO            | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| Dell          | 0J1C3P A00                  | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| Gigabyte      | H61M-S2PV                   | [63b4cd5c56](https://linux-hardware.org/?probe=63b4cd5c56) | Jun 05, 2022 |
| HP            | 3397                        | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| ASUSTek       | VM60                        | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| HP            | 2B29                        | [d2ab16d631](https://linux-hardware.org/?probe=d2ab16d631) | May 28, 2022 |
| Pegatron      | Benicia                     | [64aa376623](https://linux-hardware.org/?probe=64aa376623) | May 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| HP            | 1497                        | [4b9a65b621](https://linux-hardware.org/?probe=4b9a65b621) | May 23, 2022 |
| ASUSTek       | X99-A II                    | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Acer          | Aspire G7750                | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| HP            | 158A                        | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| Dell          | 0T656F A01                  | [2df08f807d](https://linux-hardware.org/?probe=2df08f807d) | May 15, 2022 |
| MSI           | AM1I                        | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| ECS           | Asterope                    | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| HP            | 82B4                        | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| ASUSTek       | P5KC                        | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| ASUSTek       | B150-PLUS                   | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Gigabyte      | Z68A-D3-B3                  | [573e425cb6](https://linux-hardware.org/?probe=573e425cb6) | May 08, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| HP            | 3397                        | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Gigabyte      | X48-DS5                     | [72a1aaf67d](https://linux-hardware.org/?probe=72a1aaf67d) | May 05, 2022 |
| Acer          | Veriton M490G               | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Gigabyte      | G33M-DS2R                   | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| HP            | 158A                        | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [c6da7b776e](https://linux-hardware.org/?probe=c6da7b776e) | May 03, 2022 |
| ASRock        | P55 Pro                     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Unknown       | Intel X79                   | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| HP            | 09F8h                       | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| MSI           | Z390-A PRO                  | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| HP            | 09F8h                       | [5042a34dcd](https://linux-hardware.org/?probe=5042a34dcd) | Apr 23, 2022 |
| Gigabyte      | G33M-DS2R                   | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| eMachines     | MCP61PM-GM                  | [16c4522843](https://linux-hardware.org/?probe=16c4522843) | Apr 20, 2022 |
| ASUSTek       | P8Z77-V                     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [4df90e6250](https://linux-hardware.org/?probe=4df90e6250) | Apr 18, 2022 |
| HP            | 18E5                        | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| Apple         | Mac-F221BEC8                | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| HP            | 21B4 A01                    | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [fe40f7c199](https://linux-hardware.org/?probe=fe40f7c199) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| Dell          | 0GY6Y8 A03                  | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Dell          | 00V62H A01                  | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [14ae36ec3e](https://linux-hardware.org/?probe=14ae36ec3e) | Apr 09, 2022 |
| ASUSTek       | Maximus V EXTREME           | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Dell          | 0GY6Y8 A03                  | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Dell          | OptiPlex 760                | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| Dell          | OptiPlex 760                | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | 18E5                        | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| Shuttle       | FH61V                       | [05c1b046da](https://linux-hardware.org/?probe=05c1b046da) | Apr 01, 2022 |
| Shuttle       | FH61V                       | [b89bd4d737](https://linux-hardware.org/?probe=b89bd4d737) | Apr 01, 2022 |
| Shuttle       | FH61V                       | [65009176b4](https://linux-hardware.org/?probe=65009176b4) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | [d3f3139ac2](https://linux-hardware.org/?probe=d3f3139ac2) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | [647fd89862](https://linux-hardware.org/?probe=647fd89862) | Apr 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| Acer          | Veriton M4610G              | [34ac41051e](https://linux-hardware.org/?probe=34ac41051e) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| Dell          | OptiPlex 760                | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| HP            | 21B4 A01                    | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Unknown       | T3 MRD                      | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [d5a1c13ab1](https://linux-hardware.org/?probe=d5a1c13ab1) | Mar 25, 2022 |
| Pegatron      | Benicia                     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d755a1a962](https://linux-hardware.org/?probe=d755a1a962) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | [2cfe733664](https://linux-hardware.org/?probe=2cfe733664) | Mar 22, 2022 |
| ECS           | H87H3-M                     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| ASRock        | B450 Steel Legend           | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| ASUSTek       | A68HM-K                     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| Acer          | Aspire X1920                | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| Gigabyte      | 8IPE775/-G                  | [7888ddbc2b](https://linux-hardware.org/?probe=7888ddbc2b) | Mar 13, 2022 |
| Dell          | 0RW199                      | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [2c17897902](https://linux-hardware.org/?probe=2c17897902) | Mar 10, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Acer          | TPDS05 R3700                | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Dell          | 00V62H A00                  | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| MSI           | B350 TOMAHAWK               | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| Lenovo        | NO DPK                      | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| Dell          | 0Y958C A00                  | [e2abde1282](https://linux-hardware.org/?probe=e2abde1282) | Feb 27, 2022 |
| ASUSTek       | Z170-K                      | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| Dell          | 042P49 A02                  | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| Acer          | TPDS05 R3700                | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| MSI           | G41M-P25                    | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| ASRock        | K10N78M                     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| MSI           | Z97 PC Mate                 | [e7013b772d](https://linux-hardware.org/?probe=e7013b772d) | Feb 21, 2022 |
| MSI           | A55M-P33                    | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [2734c5a939](https://linux-hardware.org/?probe=2734c5a939) | Feb 19, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [7baecb9fce](https://linux-hardware.org/?probe=7baecb9fce) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MEG X570 ACE                | [4cb6628353](https://linux-hardware.org/?probe=4cb6628353) | Feb 14, 2022 |
| MSI           | MEG X570 ACE                | [43ac6b6d18](https://linux-hardware.org/?probe=43ac6b6d18) | Feb 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [6f11ea4988](https://linux-hardware.org/?probe=6f11ea4988) | Feb 14, 2022 |
| Dell          | 0FH884                      | [bd2aa894cc](https://linux-hardware.org/?probe=bd2aa894cc) | Feb 13, 2022 |
| HP            | 3031h                       | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| Unknown       | Intel X79                   | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASUSTek       | P5Q-PRO                     | [d455b09330](https://linux-hardware.org/?probe=d455b09330) | Feb 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| ASRock        | 960GM-GS3 FX                | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| ASUSTek       | PRIME B550M-K               | [b4fe3a7a24](https://linux-hardware.org/?probe=b4fe3a7a24) | Feb 07, 2022 |
| HP            | 1497                        | [2a41e081da](https://linux-hardware.org/?probe=2a41e081da) | Feb 06, 2022 |
| Unknown       | Intel X79                   | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [843210cfb0](https://linux-hardware.org/?probe=843210cfb0) | Feb 06, 2022 |
| Dell          | 0WR7PY A02                  | [2b3c148135](https://linux-hardware.org/?probe=2b3c148135) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [1feae56050](https://linux-hardware.org/?probe=1feae56050) | Feb 06, 2022 |
| Gigabyte      | GA-870A-UD3                 | [e4b5396bf7](https://linux-hardware.org/?probe=e4b5396bf7) | Feb 04, 2022 |
| Dell          | 0XCR8D A01                  | [a68034b1e8](https://linux-hardware.org/?probe=a68034b1e8) | Feb 03, 2022 |
| Dell          | 051FJ8 A00                  | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| ASUSTek       | M4A87TD EVO                 | [8eab19298c](https://linux-hardware.org/?probe=8eab19298c) | Feb 01, 2022 |
| Dell          | 05XGC8 A01                  | [346195c820](https://linux-hardware.org/?probe=346195c820) | Feb 01, 2022 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | [27b9e98a16](https://linux-hardware.org/?probe=27b9e98a16) | Feb 01, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [901d568e70](https://linux-hardware.org/?probe=901d568e70) | Jan 31, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [621d099786](https://linux-hardware.org/?probe=621d099786) | Jan 31, 2022 |
| Chuwi         | RZBOX                       | [bea5e134d8](https://linux-hardware.org/?probe=bea5e134d8) | Jan 30, 2022 |
| ASRock        | M3A UCC                     | [8ca7699b4c](https://linux-hardware.org/?probe=8ca7699b4c) | Jan 28, 2022 |
| HP            | 1497                        | [3a3b4fe530](https://linux-hardware.org/?probe=3a3b4fe530) | Jan 27, 2022 |
| Pegatron      | Benicia                     | [8d1af3f3af](https://linux-hardware.org/?probe=8d1af3f3af) | Jan 27, 2022 |
| VIA Techno... | VT8366-8233/5               | [e285c87c48](https://linux-hardware.org/?probe=e285c87c48) | Jan 27, 2022 |
| Gigabyte      | M68MT-S2P                   | [8a951a4419](https://linux-hardware.org/?probe=8a951a4419) | Jan 26, 2022 |
| Unknown       | Unknown                     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| VIA Techno... | VT8366-8233/5               | [54ce61fa7e](https://linux-hardware.org/?probe=54ce61fa7e) | Jan 25, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [d914fce08c](https://linux-hardware.org/?probe=d914fce08c) | Jan 24, 2022 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [db13a3f215](https://linux-hardware.org/?probe=db13a3f215) | Jan 24, 2022 |
| Gigabyte      | M68MT-S2P                   | [9a38c32175](https://linux-hardware.org/?probe=9a38c32175) | Jan 24, 2022 |
| Intel         | DG965MQ AAD37419-302        | [0c7117815f](https://linux-hardware.org/?probe=0c7117815f) | Jan 23, 2022 |
| ASUSTek       | K8V-MXG                     | [504cbc919c](https://linux-hardware.org/?probe=504cbc919c) | Jan 21, 2022 |
| ASUSTek       | H87M-PLUS                   | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| ASUSTek       | K8V-MXG                     | [d4138da396](https://linux-hardware.org/?probe=d4138da396) | Jan 21, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [44b718700d](https://linux-hardware.org/?probe=44b718700d) | Jan 19, 2022 |
| Gigabyte      | MZBSWBP-00                  | [a8699a0a00](https://linux-hardware.org/?probe=a8699a0a00) | Jan 18, 2022 |
| Foxconn       | 2ABF                        | [54a4320a98](https://linux-hardware.org/?probe=54a4320a98) | Jan 16, 2022 |
| ASUSTek       | P9X79                       | [2afe3ef5cc](https://linux-hardware.org/?probe=2afe3ef5cc) | Jan 16, 2022 |
| Dell          | 0PP150 A00                  | [554774c3c8](https://linux-hardware.org/?probe=554774c3c8) | Jan 16, 2022 |
| Gigabyte      | EX58-UD4P                   | [368d168909](https://linux-hardware.org/?probe=368d168909) | Jan 15, 2022 |
| ASRock        | N68-S3 UCC                  | [1414842f81](https://linux-hardware.org/?probe=1414842f81) | Jan 14, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [78902354bb](https://linux-hardware.org/?probe=78902354bb) | Jan 14, 2022 |
| ASUSTek       | M4A78L-M                    | [dfb87ada40](https://linux-hardware.org/?probe=dfb87ada40) | Jan 13, 2022 |
| HP            | 3031h                       | [46b02ff904](https://linux-hardware.org/?probe=46b02ff904) | Jan 11, 2022 |
| HP            | 3031h                       | [2e78e6c7f8](https://linux-hardware.org/?probe=2e78e6c7f8) | Jan 10, 2022 |
| HP            | 09F8h                       | [b17a2aef1b](https://linux-hardware.org/?probe=b17a2aef1b) | Jan 10, 2022 |
| ASRock        | ALiveNF6G-GLAN              | [004087e9c8](https://linux-hardware.org/?probe=004087e9c8) | Jan 09, 2022 |
| ASUSTek       | H87M-PLUS                   | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| ASUSTek       | M4A88T-M                    | [7f20d8ac9a](https://linux-hardware.org/?probe=7f20d8ac9a) | Jan 09, 2022 |
| Gigabyte      | MJPLNAB-00                  | [79d90bf440](https://linux-hardware.org/?probe=79d90bf440) | Jan 08, 2022 |
| MSI           | H61M-P23                    | [14690b4128](https://linux-hardware.org/?probe=14690b4128) | Jan 08, 2022 |
| ASRock        | N68-VS3 UCC                 | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | 073MMW A03                  | [65c164f304](https://linux-hardware.org/?probe=65c164f304) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [ef69bbfd12](https://linux-hardware.org/?probe=ef69bbfd12) | Jan 07, 2022 |
| Lenovo        | ThinkCentre M91p 4518A13    | [8e163d26ab](https://linux-hardware.org/?probe=8e163d26ab) | Jan 06, 2022 |
| HP            | 0AA8h                       | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| HP            | 0AA8h                       | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Intel         | DP35DP AAD81073-209         | [f6ec40d0f8](https://linux-hardware.org/?probe=f6ec40d0f8) | Jan 01, 2022 |
| ASUSTek       | P5K-E                       | [f1c3532217](https://linux-hardware.org/?probe=f1c3532217) | Dec 31, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [02881d7e37](https://linux-hardware.org/?probe=02881d7e37) | Dec 30, 2021 |
| ECS           | G41T-M2                     | [6b4159a357](https://linux-hardware.org/?probe=6b4159a357) | Dec 29, 2021 |
| Gigabyte      | H110M-H-CF                  | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| MSI           | B450M MORTAR MAX            | [82cd3a640e](https://linux-hardware.org/?probe=82cd3a640e) | Dec 26, 2021 |
| Gigabyte      | H110M-H-CF                  | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| ASRock        | A75M-ITX                    | [1070ea74d9](https://linux-hardware.org/?probe=1070ea74d9) | Dec 25, 2021 |
| MSI           | B450M MORTAR MAX            | [bcfc2dd514](https://linux-hardware.org/?probe=bcfc2dd514) | Dec 25, 2021 |
| MSI           | MS-7255                     | [8bb001fa61](https://linux-hardware.org/?probe=8bb001fa61) | Dec 25, 2021 |
| ASRock        | X570M Pro4                  | [602d3e0afd](https://linux-hardware.org/?probe=602d3e0afd) | Dec 23, 2021 |
| HP            | 3398                        | [759e3821b8](https://linux-hardware.org/?probe=759e3821b8) | Dec 22, 2021 |
| Dell          | 0M5DCD A00                  | [d29b59a855](https://linux-hardware.org/?probe=d29b59a855) | Dec 21, 2021 |
| Gigabyte      | B150M-D3H-CF                | [22f2f5c84b](https://linux-hardware.org/?probe=22f2f5c84b) | Dec 21, 2021 |
| HP            | 18E7                        | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [32340d057e](https://linux-hardware.org/?probe=32340d057e) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [8986819d3f](https://linux-hardware.org/?probe=8986819d3f) | Dec 19, 2021 |
| HP            | 8169                        | [4c7533e842](https://linux-hardware.org/?probe=4c7533e842) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a94bf3ef84](https://linux-hardware.org/?probe=a94bf3ef84) | Dec 19, 2021 |
| Dell          | 0VD5HY A04                  | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| ASUSTek       | P5GC-MX                     | [499a024e97](https://linux-hardware.org/?probe=499a024e97) | Dec 18, 2021 |
| Biostar       | H110MHC                     | [bb74f304fd](https://linux-hardware.org/?probe=bb74f304fd) | Dec 16, 2021 |
| MSI           | Boston                      | [760fa25b63](https://linux-hardware.org/?probe=760fa25b63) | Dec 15, 2021 |
| MSI           | Boston                      | [bc4405aa85](https://linux-hardware.org/?probe=bc4405aa85) | Dec 15, 2021 |
| MSI           | MS-B0501 100                | [ca4048db98](https://linux-hardware.org/?probe=ca4048db98) | Dec 14, 2021 |
| Gigabyte      | EX58-UD4P                   | [aa8da2e23c](https://linux-hardware.org/?probe=aa8da2e23c) | Dec 14, 2021 |
| Dell          | 0T656F A02                  | [c6fcad51e9](https://linux-hardware.org/?probe=c6fcad51e9) | Dec 13, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Dell          | 073MMW A00                  | [c5c064c84f](https://linux-hardware.org/?probe=c5c064c84f) | Dec 13, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1f799f28c2](https://linux-hardware.org/?probe=1f799f28c2) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | [11ff47f723](https://linux-hardware.org/?probe=11ff47f723) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | [0dd637c0b8](https://linux-hardware.org/?probe=0dd637c0b8) | Dec 12, 2021 |
| ASUSTek       | P5G41T-M LX                 | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b7f8b1fb9](https://linux-hardware.org/?probe=1b7f8b1fb9) | Dec 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | [8684f34a9e](https://linux-hardware.org/?probe=8684f34a9e) | Dec 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [43602a8079](https://linux-hardware.org/?probe=43602a8079) | Dec 10, 2021 |
| Quanta        | 2AC5                        | [0e0fcca430](https://linux-hardware.org/?probe=0e0fcca430) | Dec 10, 2021 |
| Quanta        | 2AC5                        | [d0c9fba2a4](https://linux-hardware.org/?probe=d0c9fba2a4) | Dec 10, 2021 |
| Dell          | 06D7TR A00                  | [a4f61b0f15](https://linux-hardware.org/?probe=a4f61b0f15) | Dec 09, 2021 |
| HP            | 8307                        | [488c2db91c](https://linux-hardware.org/?probe=488c2db91c) | Dec 08, 2021 |
| Dell          | 08WKV3 A00                  | [1bb7cb432f](https://linux-hardware.org/?probe=1bb7cb432f) | Dec 08, 2021 |
| Acer          | Veriton E430 v1.0           | [5c857f1bb6](https://linux-hardware.org/?probe=5c857f1bb6) | Dec 08, 2021 |
| ECS           | Nettle2                     | [bb67b27e67](https://linux-hardware.org/?probe=bb67b27e67) | Dec 07, 2021 |
| Dell          | 01W26N A00                  | [7c3e61ec94](https://linux-hardware.org/?probe=7c3e61ec94) | Dec 06, 2021 |
| Gigabyte      | EP35-DS4                    | [570104ad1e](https://linux-hardware.org/?probe=570104ad1e) | Dec 04, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2e34a3a698](https://linux-hardware.org/?probe=2e34a3a698) | Dec 04, 2021 |
| Medion        | H81M-P33                    | [29b3a27675](https://linux-hardware.org/?probe=29b3a27675) | Dec 02, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [8bf8004930](https://linux-hardware.org/?probe=8bf8004930) | Dec 02, 2021 |
| HP            | 0AA4h                       | [f7438f59ac](https://linux-hardware.org/?probe=f7438f59ac) | Dec 01, 2021 |
| Gigabyte      | X99-UD4-CF                  | [190d1b6a29](https://linux-hardware.org/?probe=190d1b6a29) | Dec 01, 2021 |
| Shuttle       | NC03U                       | [2453ada3ba](https://linux-hardware.org/?probe=2453ada3ba) | Nov 30, 2021 |
| ASUSTek       | H81M-PLUS                   | [6d6caad964](https://linux-hardware.org/?probe=6d6caad964) | Nov 29, 2021 |
| ASUSTek       | A68HM-K                     | [29e9d64420](https://linux-hardware.org/?probe=29e9d64420) | Nov 29, 2021 |
| ASUSTek       | P7P55D                      | [85f288d39b](https://linux-hardware.org/?probe=85f288d39b) | Nov 29, 2021 |
| Acer          | EG43LMK                     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| HP            | 0AA8h                       | [1d80d6636e](https://linux-hardware.org/?probe=1d80d6636e) | Nov 26, 2021 |
| ECS           | H81H3-M4                    | [4215fcadd9](https://linux-hardware.org/?probe=4215fcadd9) | Nov 25, 2021 |
| Medion        | H110H4-EM                   | [8b1485f27d](https://linux-hardware.org/?probe=8b1485f27d) | Nov 25, 2021 |
| Gateway       | DX4840                      | [6c540749cd](https://linux-hardware.org/?probe=6c540749cd) | Nov 24, 2021 |
| ASRock        | B450M Pro4                  | [76361c26c6](https://linux-hardware.org/?probe=76361c26c6) | Nov 24, 2021 |
| Dell          | 0RY007                      | [b4bfb93212](https://linux-hardware.org/?probe=b4bfb93212) | Nov 24, 2021 |
| Dell          | 0RY007                      | [74a23ca55d](https://linux-hardware.org/?probe=74a23ca55d) | Nov 24, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [d61128f6f4](https://linux-hardware.org/?probe=d61128f6f4) | Nov 24, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [fe8ad04ad3](https://linux-hardware.org/?probe=fe8ad04ad3) | Nov 23, 2021 |
| ASUSTek       | M3N78-EM                    | [b358f07f1d](https://linux-hardware.org/?probe=b358f07f1d) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| ASUSTek       | M3N78-EM                    | [930c018424](https://linux-hardware.org/?probe=930c018424) | Nov 20, 2021 |
| Dell          | 014GRG A02                  | [c23455dd49](https://linux-hardware.org/?probe=c23455dd49) | Nov 20, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [ad117f68b3](https://linux-hardware.org/?probe=ad117f68b3) | Nov 20, 2021 |
| ASUSTek       | B150-PLUS                   | [3c4c353831](https://linux-hardware.org/?probe=3c4c353831) | Nov 19, 2021 |
| MSI           | 3666h                       | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| ASRock        | Z97 Extreme4                | [fc86b0fc2e](https://linux-hardware.org/?probe=fc86b0fc2e) | Nov 18, 2021 |
| MSI           | 3666h                       | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| ASUSTek       | P5LD2-VM                    | [befbf7345c](https://linux-hardware.org/?probe=befbf7345c) | Nov 17, 2021 |
| HP            | 0AA8h                       | [5cd5f5de04](https://linux-hardware.org/?probe=5cd5f5de04) | Nov 16, 2021 |
| ASUSTek       | Acacia                      | [acb0ed7655](https://linux-hardware.org/?probe=acb0ed7655) | Nov 16, 2021 |
| ASRock        | H470 Phantom Gaming 4       | [07ef26c830](https://linux-hardware.org/?probe=07ef26c830) | Nov 16, 2021 |
| HP            | 0AACh                       | [31db25eee2](https://linux-hardware.org/?probe=31db25eee2) | Nov 13, 2021 |
| HP            | 0AACh                       | [490587bfd6](https://linux-hardware.org/?probe=490587bfd6) | Nov 13, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | [a8398f9036](https://linux-hardware.org/?probe=a8398f9036) | Nov 13, 2021 |
| ASRock        | N68C-S UCC                  | [245cf1e8e7](https://linux-hardware.org/?probe=245cf1e8e7) | Nov 13, 2021 |
| ASUSTek       | PRIME B550M-A               | [269b146e10](https://linux-hardware.org/?probe=269b146e10) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| Medion        | H110H4-EM                   | [3ecf7775d6](https://linux-hardware.org/?probe=3ecf7775d6) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-A               | [9456930b53](https://linux-hardware.org/?probe=9456930b53) | Nov 08, 2021 |
| MSI           | X470 GAMING PLUS            | [ac741fe858](https://linux-hardware.org/?probe=ac741fe858) | Nov 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [425b956614](https://linux-hardware.org/?probe=425b956614) | Nov 07, 2021 |
| NCR           | Pocono BIOS.3.1             | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| ASUSTek       | A8N32-SLI-Deluxe            | [d3f60c7a58](https://linux-hardware.org/?probe=d3f60c7a58) | Nov 06, 2021 |
| ASUSTek       | M4A89GTD-PRO                | [4964ad307b](https://linux-hardware.org/?probe=4964ad307b) | Nov 06, 2021 |
| Dell          | 0XPDFK A01                  | [6ba2adb529](https://linux-hardware.org/?probe=6ba2adb529) | Nov 05, 2021 |
| Gigabyte      | 945GZM-S2                   | [df920d0ad1](https://linux-hardware.org/?probe=df920d0ad1) | Nov 04, 2021 |
| Medion        | MS-7366                     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| ABIT          | AI7                         | [75f77dabe1](https://linux-hardware.org/?probe=75f77dabe1) | Nov 03, 2021 |
| Gigabyte      | H370 HD3-CF                 | [c4bd2daf84](https://linux-hardware.org/?probe=c4bd2daf84) | Nov 03, 2021 |
| Dell          | 0XPDFK A01                  | [1df464dbfe](https://linux-hardware.org/?probe=1df464dbfe) | Nov 03, 2021 |
| EVGA          | 111-CS-E371                 | [0f95a7356a](https://linux-hardware.org/?probe=0f95a7356a) | Nov 02, 2021 |
| ASUSTek       | M2N-E SLI                   | [f9bff20c4d](https://linux-hardware.org/?probe=f9bff20c4d) | Oct 31, 2021 |
| ASUSTek       | M2N-E SLI                   | [03db91ce41](https://linux-hardware.org/?probe=03db91ce41) | Oct 31, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | [29e8bce644](https://linux-hardware.org/?probe=29e8bce644) | Oct 30, 2021 |
| Acer          | Aspire X3990                | [967427d98c](https://linux-hardware.org/?probe=967427d98c) | Oct 29, 2021 |
| Acer          | Aspire X3990                | [7ccc4b3004](https://linux-hardware.org/?probe=7ccc4b3004) | Oct 29, 2021 |
| HP            | 8433 11                     | [6183f8775b](https://linux-hardware.org/?probe=6183f8775b) | Oct 29, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| Dell          | 0478VN A00                  | [f90352c29f](https://linux-hardware.org/?probe=f90352c29f) | Oct 28, 2021 |
| ASUSTek       | P5KC                        | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2b52b81540](https://linux-hardware.org/?probe=2b52b81540) | Oct 24, 2021 |
| Dell          | 042P49 A00                  | [7bb7c6c3cb](https://linux-hardware.org/?probe=7bb7c6c3cb) | Oct 23, 2021 |
| MSI           | Z97 GAMING 5                | [0273030434](https://linux-hardware.org/?probe=0273030434) | Oct 22, 2021 |
| MSI           | X570-A PRO                  | [357ea9ab5d](https://linux-hardware.org/?probe=357ea9ab5d) | Oct 22, 2021 |
| Gigabyte      | GA-990FXA-D3                | [166334966a](https://linux-hardware.org/?probe=166334966a) | Oct 21, 2021 |
| HP            | 1998                        | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Dell          | 0PU052                      | [7e7d0bc489](https://linux-hardware.org/?probe=7e7d0bc489) | Oct 21, 2021 |
| ASUSTek       | PRIME H310T                 | [b0e10a4766](https://linux-hardware.org/?probe=b0e10a4766) | Oct 20, 2021 |
| MSI           | B350 TOMAHAWK               | [a119d97189](https://linux-hardware.org/?probe=a119d97189) | Oct 20, 2021 |
| Acer          | Aspire XC-603G              | [943617d620](https://linux-hardware.org/?probe=943617d620) | Oct 20, 2021 |
| ASRock        | G31M-VS2                    | [555bb7179c](https://linux-hardware.org/?probe=555bb7179c) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | [63cab5e07f](https://linux-hardware.org/?probe=63cab5e07f) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | [355e464f7f](https://linux-hardware.org/?probe=355e464f7f) | Oct 19, 2021 |
| Dell          | 0RY007                      | [b1095c5887](https://linux-hardware.org/?probe=b1095c5887) | Oct 18, 2021 |
| HP            | 8717                        | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| ASUSTek       | A8N32-SLI-Deluxe            | [1b7f4401be](https://linux-hardware.org/?probe=1b7f4401be) | Oct 17, 2021 |
| Gigabyte      | M68MT-D3P                   | [0d3c131ddf](https://linux-hardware.org/?probe=0d3c131ddf) | Oct 16, 2021 |
| Gigabyte      | M68MT-D3P                   | [9debdd654c](https://linux-hardware.org/?probe=9debdd654c) | Oct 15, 2021 |
| NCR           | Pocono BIOS.3.1             | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| ASUSTek       | P8H61-I R2.0                | [7f199df3a7](https://linux-hardware.org/?probe=7f199df3a7) | Oct 14, 2021 |
| ASUSTek       | Z170-P                      | [b7907647ce](https://linux-hardware.org/?probe=b7907647ce) | Oct 14, 2021 |
| Lenovo        | MAHOBAY                     | [2529e14d59](https://linux-hardware.org/?probe=2529e14d59) | Oct 14, 2021 |
| Clientron     | Pineview-D                  | [59bf0b789c](https://linux-hardware.org/?probe=59bf0b789c) | Oct 13, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [c02c412d87](https://linux-hardware.org/?probe=c02c412d87) | Oct 13, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [83e53328a7](https://linux-hardware.org/?probe=83e53328a7) | Oct 13, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e922eda008](https://linux-hardware.org/?probe=e922eda008) | Oct 12, 2021 |
| Foxconn       | 2AB1h                       | [6216ce3f5c](https://linux-hardware.org/?probe=6216ce3f5c) | Oct 12, 2021 |
| Dell          | 0215PR A02                  | [d9e5820db2](https://linux-hardware.org/?probe=d9e5820db2) | Oct 11, 2021 |
| PCChips       | P49G                        | [381061a980](https://linux-hardware.org/?probe=381061a980) | Oct 11, 2021 |
| ASRock        | G31M-VS                     | [0c8b706839](https://linux-hardware.org/?probe=0c8b706839) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | [56135a7fa6](https://linux-hardware.org/?probe=56135a7fa6) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | [d7676eeb32](https://linux-hardware.org/?probe=d7676eeb32) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [c49cbf2f7a](https://linux-hardware.org/?probe=c49cbf2f7a) | Oct 11, 2021 |
| Medion        | B360H4-EM V1.0              | [6d2f43a452](https://linux-hardware.org/?probe=6d2f43a452) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6beb9ddceb](https://linux-hardware.org/?probe=6beb9ddceb) | Oct 09, 2021 |
| Gigabyte      | H510M S2H                   | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| Dell          | 0YC523                      | [cf8d063deb](https://linux-hardware.org/?probe=cf8d063deb) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-K               | [a4da124d05](https://linux-hardware.org/?probe=a4da124d05) | Oct 08, 2021 |
| ASRock        | G31M-VS                     | [17021380ec](https://linux-hardware.org/?probe=17021380ec) | Oct 08, 2021 |
| Gigabyte      | X38-DS4                     | [5e06d3cb35](https://linux-hardware.org/?probe=5e06d3cb35) | Oct 08, 2021 |
| Dell          | 05DN3X A00                  | [248c508eb0](https://linux-hardware.org/?probe=248c508eb0) | Oct 07, 2021 |
| Gigabyte      | H61M-S2PV                   | [c78f82b137](https://linux-hardware.org/?probe=c78f82b137) | Oct 07, 2021 |
| Dell          | 05DN3X A00                  | [0735063fbe](https://linux-hardware.org/?probe=0735063fbe) | Oct 07, 2021 |
| Gigabyte      | H370 HD3-CF                 | [bc2d1e8c10](https://linux-hardware.org/?probe=bc2d1e8c10) | Oct 06, 2021 |
| ASRock        | 775Dual-VSTA                | [6df28d7ea1](https://linux-hardware.org/?probe=6df28d7ea1) | Oct 06, 2021 |
| Lenovo        | ThinkCentre A55 92658HG     | [edc1f2768d](https://linux-hardware.org/?probe=edc1f2768d) | Oct 05, 2021 |
| Acer          | Aspire X1430                | [0864e39368](https://linux-hardware.org/?probe=0864e39368) | Oct 05, 2021 |
| HP            | ProLiant ML350 G6           | [2645539128](https://linux-hardware.org/?probe=2645539128) | Oct 03, 2021 |
| MiTAC         | PD14RI                      | [04ec92a4b9](https://linux-hardware.org/?probe=04ec92a4b9) | Oct 02, 2021 |
| MSI           | MPG Z390 GAMING EDGE AC     | [37caf69047](https://linux-hardware.org/?probe=37caf69047) | Oct 02, 2021 |
| ASRock        | N68C-S UCC                  | [14def316c8](https://linux-hardware.org/?probe=14def316c8) | Oct 01, 2021 |
| ASRock        | Z170 Gaming K4              | [f107c84c00](https://linux-hardware.org/?probe=f107c84c00) | Sep 30, 2021 |
| Insyde        | Harrisonville               | [2b7a8ba5fc](https://linux-hardware.org/?probe=2b7a8ba5fc) | Sep 30, 2021 |
| HP            | 2175                        | [856907ec52](https://linux-hardware.org/?probe=856907ec52) | Sep 28, 2021 |
| ASUSTek       | PRIME H310T                 | [58721f0765](https://linux-hardware.org/?probe=58721f0765) | Sep 28, 2021 |
| Dell          | 0N826N A03                  | [fc1d74c246](https://linux-hardware.org/?probe=fc1d74c246) | Sep 27, 2021 |
| HP            | 1905                        | [5c8416c157](https://linux-hardware.org/?probe=5c8416c157) | Sep 27, 2021 |
| ASUSTek       | P5L-MX                      | [6b722285dd](https://linux-hardware.org/?probe=6b722285dd) | Sep 26, 2021 |
| Acer          | Aspire XC-603G              | [ec0efc1b42](https://linux-hardware.org/?probe=ec0efc1b42) | Sep 25, 2021 |
| ASUSTek       | P5Q-PRO                     | [84016450a8](https://linux-hardware.org/?probe=84016450a8) | Sep 25, 2021 |
| ASUSTek       | P5Q-PRO                     | [6802376ebe](https://linux-hardware.org/?probe=6802376ebe) | Sep 25, 2021 |
| ASUSTek       | PRIME H510M-K               | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| HP            | 1905                        | [1c85499a51](https://linux-hardware.org/?probe=1c85499a51) | Sep 22, 2021 |
| HP            | 21F5                        | [d6613e1901](https://linux-hardware.org/?probe=d6613e1901) | Sep 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | [7abd7a20df](https://linux-hardware.org/?probe=7abd7a20df) | Sep 21, 2021 |
| NCR           | Pocono                      | [bbd821ad81](https://linux-hardware.org/?probe=bbd821ad81) | Sep 18, 2021 |
| MSI           | B350M PRO-VDH               | [fd8290e92f](https://linux-hardware.org/?probe=fd8290e92f) | Sep 17, 2021 |
| ASUSTek       | P8H67                       | [ad597e71b6](https://linux-hardware.org/?probe=ad597e71b6) | Sep 16, 2021 |
| Gigabyte      | GA-970A-UD3                 | [009afad721](https://linux-hardware.org/?probe=009afad721) | Sep 16, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [ea9fbdbba6](https://linux-hardware.org/?probe=ea9fbdbba6) | Sep 14, 2021 |
| Dell          | 0XHGV1 A00                  | [c7f133cbb9](https://linux-hardware.org/?probe=c7f133cbb9) | Sep 14, 2021 |
| Foxconn       | M61PMV FAB                  | [290d3e0fd5](https://linux-hardware.org/?probe=290d3e0fd5) | Sep 14, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [6a8c881d1b](https://linux-hardware.org/?probe=6a8c881d1b) | Sep 13, 2021 |
| Foxconn       | 2ABF                        | [b86d7ca102](https://linux-hardware.org/?probe=b86d7ca102) | Sep 12, 2021 |
| Foxconn       | 2A8C                        | [f7b2ed152f](https://linux-hardware.org/?probe=f7b2ed152f) | Sep 12, 2021 |
| ASUSTek       | V-M3N8200                   | [4ee51bb086](https://linux-hardware.org/?probe=4ee51bb086) | Sep 11, 2021 |
| ASRock        | X570 Taichi                 | [d40b2f831e](https://linux-hardware.org/?probe=d40b2f831e) | Sep 11, 2021 |
| ASRock        | HM55-MXM                    | [0d500a3661](https://linux-hardware.org/?probe=0d500a3661) | Sep 11, 2021 |
| ASUSTek       | P8Z68 DELUXE                | [4e38c7976d](https://linux-hardware.org/?probe=4e38c7976d) | Sep 11, 2021 |
| ASUSTek       | M3N18L T-M3N8200            | [bd8410bceb](https://linux-hardware.org/?probe=bd8410bceb) | Sep 09, 2021 |
| Biostar       | G41D3C                      | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| ASUSTek       | H170M-PLUS                  | [7b81d32161](https://linux-hardware.org/?probe=7b81d32161) | Sep 07, 2021 |
| OEM           | BayTrail JHS365             | [e82d82c85b](https://linux-hardware.org/?probe=e82d82c85b) | Sep 03, 2021 |
| ASUSTek       | P8Z68-V LX                  | [899954b326](https://linux-hardware.org/?probe=899954b326) | Sep 02, 2021 |
| Acer          | Aspire XC-603G              | [888a6f7244](https://linux-hardware.org/?probe=888a6f7244) | Sep 02, 2021 |
| HP            | 3032h                       | [4b261dcd37](https://linux-hardware.org/?probe=4b261dcd37) | Sep 02, 2021 |
| Gigabyte      | G41M-ES2L                   | [b9fdcaf2f7](https://linux-hardware.org/?probe=b9fdcaf2f7) | Sep 02, 2021 |
| HP            | 3396                        | [a22cfaf69e](https://linux-hardware.org/?probe=a22cfaf69e) | Sep 02, 2021 |
| Biostar       | G41D3C                      | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI           | Z97-G43                     | [364baf5248](https://linux-hardware.org/?probe=364baf5248) | Aug 31, 2021 |
| ASRock        | Q1900M                      | [bdb4eba3e4](https://linux-hardware.org/?probe=bdb4eba3e4) | Aug 31, 2021 |
| Foxconn       | 2ABF                        | [967db93155](https://linux-hardware.org/?probe=967db93155) | Aug 30, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [89c397b882](https://linux-hardware.org/?probe=89c397b882) | Aug 29, 2021 |
| MSI           | 2A78h                       | [2fbe95f312](https://linux-hardware.org/?probe=2fbe95f312) | Aug 29, 2021 |
| MSI           | 2A78h                       | [b39690d456](https://linux-hardware.org/?probe=b39690d456) | Aug 29, 2021 |
| Lenovo        | ThinkCentre M58 7627AA9     | [e5bedff47d](https://linux-hardware.org/?probe=e5bedff47d) | Aug 29, 2021 |
| ASUSTek       | Z170-A                      | [2d0a7ed28d](https://linux-hardware.org/?probe=2d0a7ed28d) | Aug 28, 2021 |
| ASUSTek       | Z170-A                      | [fc294326ce](https://linux-hardware.org/?probe=fc294326ce) | Aug 28, 2021 |
| Intel         | DH67BL AAG10189-206         | [cf6543044c](https://linux-hardware.org/?probe=cf6543044c) | Aug 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [aa1a98a9d6](https://linux-hardware.org/?probe=aa1a98a9d6) | Aug 25, 2021 |
| Intel         | DH67BL AAG10189-206         | [67f7ee5fde](https://linux-hardware.org/?probe=67f7ee5fde) | Aug 25, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [fae18649fd](https://linux-hardware.org/?probe=fae18649fd) | Aug 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f0824b7193](https://linux-hardware.org/?probe=f0824b7193) | Aug 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [8d43ff5f35](https://linux-hardware.org/?probe=8d43ff5f35) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [23fcf2122e](https://linux-hardware.org/?probe=23fcf2122e) | Aug 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f128b4ee5a](https://linux-hardware.org/?probe=f128b4ee5a) | Aug 23, 2021 |
| Acer          | Aspire XC-603G              | [3aca23ef5f](https://linux-hardware.org/?probe=3aca23ef5f) | Aug 22, 2021 |
| Foxconn       | 2A8C                        | [f3ae3bb84c](https://linux-hardware.org/?probe=f3ae3bb84c) | Aug 21, 2021 |
| ASRock        | X399M Taichi                | [7387be39e6](https://linux-hardware.org/?probe=7387be39e6) | Aug 21, 2021 |
| Alienware     | 0N4R4N A00                  | [bf5947b943](https://linux-hardware.org/?probe=bf5947b943) | Aug 20, 2021 |
| ASRock        | B450 Steel Legend           | [4819fabe04](https://linux-hardware.org/?probe=4819fabe04) | Aug 20, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [de1fa2ccc0](https://linux-hardware.org/?probe=de1fa2ccc0) | Aug 20, 2021 |
| ASRock        | A320M-HDV                   | [42ab0a8ca5](https://linux-hardware.org/?probe=42ab0a8ca5) | Aug 20, 2021 |
| Acer          | Aspire X1470                | [79d5cfd4fd](https://linux-hardware.org/?probe=79d5cfd4fd) | Aug 20, 2021 |
| NEC Comput... | GA-8TRC410M-NF              | [e2215fc750](https://linux-hardware.org/?probe=e2215fc750) | Aug 18, 2021 |
| NEC Comput... | GA-8TRC410M-NF              | [552abea580](https://linux-hardware.org/?probe=552abea580) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [dbb548b728](https://linux-hardware.org/?probe=dbb548b728) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4740529a1f](https://linux-hardware.org/?probe=4740529a1f) | Aug 17, 2021 |
| MSI           | Boston                      | [eb189f6da8](https://linux-hardware.org/?probe=eb189f6da8) | Aug 17, 2021 |
| HP            | 0B54h D                     | [f68a448d75](https://linux-hardware.org/?probe=f68a448d75) | Aug 17, 2021 |
| Gateway       | SX2185                      | [6e9745ae09](https://linux-hardware.org/?probe=6e9745ae09) | Aug 17, 2021 |
| HP            | 0B54h D                     | [9fd9d289f2](https://linux-hardware.org/?probe=9fd9d289f2) | Aug 17, 2021 |
| Dell          | 0X9680                      | [1b15ec58a9](https://linux-hardware.org/?probe=1b15ec58a9) | Aug 16, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [b178612e9f](https://linux-hardware.org/?probe=b178612e9f) | Aug 14, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [28b07ead33](https://linux-hardware.org/?probe=28b07ead33) | Aug 14, 2021 |
| ASUSTek       | B85-PLUS                    | [10fd5746f0](https://linux-hardware.org/?probe=10fd5746f0) | Aug 14, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [81a83c41a2](https://linux-hardware.org/?probe=81a83c41a2) | Aug 14, 2021 |
| ASRock        | A300M-STX                   | [3ff1b8f6dc](https://linux-hardware.org/?probe=3ff1b8f6dc) | Aug 14, 2021 |
| Dell          | 0478VN A00                  | [c8aed0954a](https://linux-hardware.org/?probe=c8aed0954a) | Aug 13, 2021 |
| Dell          | 0YJPT1 A00                  | [38822c9ed8](https://linux-hardware.org/?probe=38822c9ed8) | Aug 12, 2021 |
| HP            | 0B54h D                     | [49eb423362](https://linux-hardware.org/?probe=49eb423362) | Aug 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| ASRock        | Q1900M                      | [14a67edffe](https://linux-hardware.org/?probe=14a67edffe) | Aug 09, 2021 |
| Gigabyte      | X99-UD4-CF                  | [0b019ac936](https://linux-hardware.org/?probe=0b019ac936) | Aug 09, 2021 |
| ASUSTek       | H87M-PLUS                   | [c2ed04ce87](https://linux-hardware.org/?probe=c2ed04ce87) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| Dell          | 0WMJ54 A00                  | [d577241d35](https://linux-hardware.org/?probe=d577241d35) | Aug 08, 2021 |
| Gigabyte      | H81M-H                      | [a54ce42dd4](https://linux-hardware.org/?probe=a54ce42dd4) | Aug 07, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [c45499e754](https://linux-hardware.org/?probe=c45499e754) | Aug 07, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [c3ac112d1b](https://linux-hardware.org/?probe=c3ac112d1b) | Aug 06, 2021 |
| HP            | 1998                        | [e6d0744e85](https://linux-hardware.org/?probe=e6d0744e85) | Aug 04, 2021 |
| HP            | 1998                        | [b3b909d152](https://linux-hardware.org/?probe=b3b909d152) | Aug 04, 2021 |
| ASUSTek       | Lancaster                   | [7c955ee689](https://linux-hardware.org/?probe=7c955ee689) | Aug 02, 2021 |
| HP            | 3646h                       | [60fb363058](https://linux-hardware.org/?probe=60fb363058) | Aug 02, 2021 |
| HP            | 2B29                        | [06babd8c13](https://linux-hardware.org/?probe=06babd8c13) | Aug 01, 2021 |
| HP            | 0B54h D                     | [a7f0b16b1f](https://linux-hardware.org/?probe=a7f0b16b1f) | Jul 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0aae2dd454](https://linux-hardware.org/?probe=0aae2dd454) | Jul 30, 2021 |
| Lenovo        | 4518-a12                    | [8574df0f54](https://linux-hardware.org/?probe=8574df0f54) | Jul 27, 2021 |
| ASUSTek       | Lancaster                   | [03d7312da2](https://linux-hardware.org/?probe=03d7312da2) | Jul 27, 2021 |
| MSI           | MS-7181                     | [f2c624a258](https://linux-hardware.org/?probe=f2c624a258) | Jul 26, 2021 |
| WinFast       | 6100M2MA FAB1.0             | [f994eb2a66](https://linux-hardware.org/?probe=f994eb2a66) | Jul 26, 2021 |
| Intel         | DQ67SW AAG12527-310         | [36a4037b9d](https://linux-hardware.org/?probe=36a4037b9d) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | [73d6127953](https://linux-hardware.org/?probe=73d6127953) | Jul 26, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [c17c4c65d5](https://linux-hardware.org/?probe=c17c4c65d5) | Jul 26, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [69bc249119](https://linux-hardware.org/?probe=69bc249119) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [d6e4e7f445](https://linux-hardware.org/?probe=d6e4e7f445) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [7d7ebd3f1e](https://linux-hardware.org/?probe=7d7ebd3f1e) | Jul 25, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [56198fa6c1](https://linux-hardware.org/?probe=56198fa6c1) | Jul 24, 2021 |
| Unknown       | 775i65G                     | [5d536ea682](https://linux-hardware.org/?probe=5d536ea682) | Jul 24, 2021 |
| Dell          | 03KWTV A02                  | [b292aa69b5](https://linux-hardware.org/?probe=b292aa69b5) | Jul 24, 2021 |
| Unknown       | 775i65G                     | [0eefee7dfd](https://linux-hardware.org/?probe=0eefee7dfd) | Jul 24, 2021 |
| HP            | 1589                        | [2885bdaad2](https://linux-hardware.org/?probe=2885bdaad2) | Jul 23, 2021 |
| MSI           | Z370-A PRO                  | [b125a65313](https://linux-hardware.org/?probe=b125a65313) | Jul 22, 2021 |
| ASUSTek       | M4A89GTD-PRO                | [a556f90b28](https://linux-hardware.org/?probe=a556f90b28) | Jul 20, 2021 |
| ASRock        | B85M-HDS                    | [9104b94412](https://linux-hardware.org/?probe=9104b94412) | Jul 19, 2021 |
| ASRock        | B85M-HDS                    | [cafe2c46f1](https://linux-hardware.org/?probe=cafe2c46f1) | Jul 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| ASUSTek       | PRIME Z390-A                | [f8767723e4](https://linux-hardware.org/?probe=f8767723e4) | Jul 18, 2021 |
| ASRock        | 880GM-LE                    | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [8026da144d](https://linux-hardware.org/?probe=8026da144d) | Jul 18, 2021 |
| Dell          | 0VNP2H A00                  | [167ec81986](https://linux-hardware.org/?probe=167ec81986) | Jul 17, 2021 |
| Gigabyte      | Z77X-D3H                    | [8263a1f725](https://linux-hardware.org/?probe=8263a1f725) | Jul 17, 2021 |
| ASUSTek       | M4A89GTD-PRO                | [6b1b434e27](https://linux-hardware.org/?probe=6b1b434e27) | Jul 17, 2021 |
| ASRock        | X300M-STX                   | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| ASUSTek       | M3A-H/HDMI                  | [6c97b09b3f](https://linux-hardware.org/?probe=6c97b09b3f) | Jul 14, 2021 |
| Gigabyte      | H55M-UD2H                   | [d871a17735](https://linux-hardware.org/?probe=d871a17735) | Jul 14, 2021 |
| ASRock        | Z490 Phantom Gaming 4       | [ee2fa49a14](https://linux-hardware.org/?probe=ee2fa49a14) | Jul 13, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [62577e9673](https://linux-hardware.org/?probe=62577e9673) | Jul 13, 2021 |
| HP            | 0A64h                       | [317c62b0b9](https://linux-hardware.org/?probe=317c62b0b9) | Jul 13, 2021 |
| HP            | 0A64h                       | [7495976a12](https://linux-hardware.org/?probe=7495976a12) | Jul 13, 2021 |
| ASUSTek       | A68HM-K                     | [03c69f44e3](https://linux-hardware.org/?probe=03c69f44e3) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | [e46886ce2d](https://linux-hardware.org/?probe=e46886ce2d) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | [f51a4f44b2](https://linux-hardware.org/?probe=f51a4f44b2) | Jul 12, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [2e9f511032](https://linux-hardware.org/?probe=2e9f511032) | Jul 11, 2021 |
| Gigabyte      | Z77X-D3H                    | [5416b8d0da](https://linux-hardware.org/?probe=5416b8d0da) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [252d84e173](https://linux-hardware.org/?probe=252d84e173) | Jul 05, 2021 |
| MSI           | Boston                      | [72f1bfa2f0](https://linux-hardware.org/?probe=72f1bfa2f0) | Jul 05, 2021 |
| MSI           | Boston                      | [ff82275c70](https://linux-hardware.org/?probe=ff82275c70) | Jul 04, 2021 |
| ASRock        | J4105M                      | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Gigabyte      | F2A78M-HD2                  | [7974efd1a4](https://linux-hardware.org/?probe=7974efd1a4) | Jul 03, 2021 |
| HP            | 0A54h                       | [c8d8757784](https://linux-hardware.org/?probe=c8d8757784) | Jul 02, 2021 |
| HP            | 3397                        | [85b6ea31ba](https://linux-hardware.org/?probe=85b6ea31ba) | Jun 30, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [a2398ab2d4](https://linux-hardware.org/?probe=a2398ab2d4) | Jun 29, 2021 |
| Dell          | 0M863N A00                  | [a505e284ec](https://linux-hardware.org/?probe=a505e284ec) | Jun 27, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1e4e8c8638](https://linux-hardware.org/?probe=1e4e8c8638) | Jun 27, 2021 |
| Gigabyte      | P31-DS3L                    | [9e8b678a15](https://linux-hardware.org/?probe=9e8b678a15) | Jun 26, 2021 |
| Lenovo        | ThinkStation D20 4158CM1    | [004bd0bb8e](https://linux-hardware.org/?probe=004bd0bb8e) | Jun 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [c40b02d888](https://linux-hardware.org/?probe=c40b02d888) | Jun 24, 2021 |
| HP            | 0AA8h                       | [8de391044c](https://linux-hardware.org/?probe=8de391044c) | Jun 24, 2021 |
| HP            | 0AA8h                       | [a477bc402f](https://linux-hardware.org/?probe=a477bc402f) | Jun 24, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [f697fb056b](https://linux-hardware.org/?probe=f697fb056b) | Jun 24, 2021 |
| MSI           | X470 GAMING PLUS            | [6e3bc83381](https://linux-hardware.org/?probe=6e3bc83381) | Jun 23, 2021 |
| MSI           | B350M PRO-VDH               | [c1009474e9](https://linux-hardware.org/?probe=c1009474e9) | Jun 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [d2519fe6fd](https://linux-hardware.org/?probe=d2519fe6fd) | Jun 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d5ebc8bdc6](https://linux-hardware.org/?probe=d5ebc8bdc6) | Jun 18, 2021 |
| Dell          | 0WG855                      | [02b09ef628](https://linux-hardware.org/?probe=02b09ef628) | Jun 17, 2021 |
| Dell          | 0WR7PY A02                  | [fb27aaebe4](https://linux-hardware.org/?probe=fb27aaebe4) | Jun 15, 2021 |
| MSI           | B350M PRO-VDH               | [b2d3b7546a](https://linux-hardware.org/?probe=b2d3b7546a) | Jun 15, 2021 |
| Gigabyte      | H55M-USB3                   | [3372e4c0ab](https://linux-hardware.org/?probe=3372e4c0ab) | Jun 14, 2021 |
| HP            | 1589                        | [531fd7a206](https://linux-hardware.org/?probe=531fd7a206) | Jun 12, 2021 |
| ASRock        | X300M-STX                   | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | [28cc50b8af](https://linux-hardware.org/?probe=28cc50b8af) | Jun 11, 2021 |
| Gigabyte      | H81M-D2W                    | [a5cf29d3fa](https://linux-hardware.org/?probe=a5cf29d3fa) | Jun 11, 2021 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6b3ad983d3](https://linux-hardware.org/?probe=6b3ad983d3) | Jun 11, 2021 |
| Packard Be... | WMCP78M                     | [c267385b22](https://linux-hardware.org/?probe=c267385b22) | Jun 11, 2021 |
| Dell          | 0M863N A01                  | [0e646737b0](https://linux-hardware.org/?probe=0e646737b0) | Jun 11, 2021 |
| Dell          | 0X75JG A01                  | [42bf6b208e](https://linux-hardware.org/?probe=42bf6b208e) | Jun 09, 2021 |
| Dell          | 0MWYPT A01                  | [fb7b10919d](https://linux-hardware.org/?probe=fb7b10919d) | Jun 09, 2021 |
| Gigabyte      | 945PL-S3                    | [885dc78ef1](https://linux-hardware.org/?probe=885dc78ef1) | Jun 08, 2021 |
| HP            | 3397                        | [883f6f07e7](https://linux-hardware.org/?probe=883f6f07e7) | Jun 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [7b6170422b](https://linux-hardware.org/?probe=7b6170422b) | Jun 08, 2021 |
| Gateway       | SX2185                      | [541a86ceb1](https://linux-hardware.org/?probe=541a86ceb1) | Jun 08, 2021 |
| Intel         | H61                         | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| Gigabyte      | X58A-UD3R                   | [216d963387](https://linux-hardware.org/?probe=216d963387) | Jun 05, 2021 |
| MSI           | X99A SLI Krait Edition      | [f9626d011c](https://linux-hardware.org/?probe=f9626d011c) | Jun 05, 2021 |
| Foxconn       | 2ABF                        | [11b7eb9f82](https://linux-hardware.org/?probe=11b7eb9f82) | Jun 05, 2021 |
| ASRock        | A320M-DVS R4.0              | [4ce3673d2d](https://linux-hardware.org/?probe=4ce3673d2d) | Jun 04, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [8684efd5c9](https://linux-hardware.org/?probe=8684efd5c9) | Jun 04, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5dbe42cf75](https://linux-hardware.org/?probe=5dbe42cf75) | Jun 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [07eb1feeb4](https://linux-hardware.org/?probe=07eb1feeb4) | Jun 03, 2021 |
| HP            | 3032h                       | [dade0cb1d6](https://linux-hardware.org/?probe=dade0cb1d6) | Jun 03, 2021 |
| Packard Be... | IMEDIA S2110A               | [34a921fd71](https://linux-hardware.org/?probe=34a921fd71) | Jun 03, 2021 |
| QTQD          | Unknown                     | [f7d66120da](https://linux-hardware.org/?probe=f7d66120da) | Jun 01, 2021 |
| Intel         | DH61WW AAG23116-204         | [5b590117dd](https://linux-hardware.org/?probe=5b590117dd) | Jun 01, 2021 |
| MSI           | B250M PRO-VD                | [c90bb6eca1](https://linux-hardware.org/?probe=c90bb6eca1) | May 31, 2021 |
| HP            | 3032h                       | [ea009f77d1](https://linux-hardware.org/?probe=ea009f77d1) | May 31, 2021 |
| NCR           | Pocono                      | [73bfada83a](https://linux-hardware.org/?probe=73bfada83a) | May 30, 2021 |
| Acer          | Veriton X270                | [d6cb41706d](https://linux-hardware.org/?probe=d6cb41706d) | May 30, 2021 |
| Intel         | DH61WW AAG23116-204         | [f109707413](https://linux-hardware.org/?probe=f109707413) | May 29, 2021 |
| Dell          | 0RY206                      | [f02982ff12](https://linux-hardware.org/?probe=f02982ff12) | May 29, 2021 |
| MSI           | A68HM-E33 V2                | [a9971ed939](https://linux-hardware.org/?probe=a9971ed939) | May 29, 2021 |
| Intel         | D945GCPE AAD97209-201       | [101800e413](https://linux-hardware.org/?probe=101800e413) | May 29, 2021 |
| Intel         | D945GNT AAC96315-402        | [36fb4e2aba](https://linux-hardware.org/?probe=36fb4e2aba) | May 29, 2021 |
| ASUSTek       | P8Z77-V LK                  | [adeef0fa37](https://linux-hardware.org/?probe=adeef0fa37) | May 27, 2021 |
| HP            | 18E7                        | [dbb0731dd9](https://linux-hardware.org/?probe=dbb0731dd9) | May 27, 2021 |
| HP            | 3397                        | [de611cdb9f](https://linux-hardware.org/?probe=de611cdb9f) | May 26, 2021 |
| Medion        | H110H4-EM                   | [09ca813f06](https://linux-hardware.org/?probe=09ca813f06) | May 25, 2021 |
| ASRock        | H110M-ITX/ac                | [f03f0287f4](https://linux-hardware.org/?probe=f03f0287f4) | May 24, 2021 |
| HP            | 0AA8h                       | [c0e9143e13](https://linux-hardware.org/?probe=c0e9143e13) | May 23, 2021 |
| ECS           | H61H2-M2                    | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| ASUSTek       | A68HM-K                     | [d62c1cc4aa](https://linux-hardware.org/?probe=d62c1cc4aa) | May 22, 2021 |
| MSI           | B450M PRO-M2 MAX            | [7dbdabf49b](https://linux-hardware.org/?probe=7dbdabf49b) | May 22, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [c4a7a4682b](https://linux-hardware.org/?probe=c4a7a4682b) | May 21, 2021 |
| Medion        | MS-7366                     | [903b29e77e](https://linux-hardware.org/?probe=903b29e77e) | May 20, 2021 |
| Dell          | 0M863N A01                  | [8f0c6ed152](https://linux-hardware.org/?probe=8f0c6ed152) | May 20, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [4a87825add](https://linux-hardware.org/?probe=4a87825add) | May 20, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [74172b19b1](https://linux-hardware.org/?probe=74172b19b1) | May 20, 2021 |
| Acer          | H57M01                      | [8b9e2fb5f2](https://linux-hardware.org/?probe=8b9e2fb5f2) | May 19, 2021 |
| MSI           | B450M MORTAR MAX            | [22e4c37309](https://linux-hardware.org/?probe=22e4c37309) | May 19, 2021 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [21bb7408e3](https://linux-hardware.org/?probe=21bb7408e3) | May 18, 2021 |
| Gigabyte      | C847N                       | [7a17d8efef](https://linux-hardware.org/?probe=7a17d8efef) | May 17, 2021 |
| Gigabyte      | C847N                       | [deb3c6a79f](https://linux-hardware.org/?probe=deb3c6a79f) | May 17, 2021 |
| ASUSTek       | P8Z77-V LK                  | [4b3a2f512f](https://linux-hardware.org/?probe=4b3a2f512f) | May 17, 2021 |
| Acer          | H57M01                      | [a80686767d](https://linux-hardware.org/?probe=a80686767d) | May 16, 2021 |
| Gigabyte      | B150M-D3H-CF                | [1fc64a9567](https://linux-hardware.org/?probe=1fc64a9567) | May 16, 2021 |
| Intel         | BTC-T37                     | [dcfc697c0a](https://linux-hardware.org/?probe=dcfc697c0a) | May 16, 2021 |
| ASUSTek       | M4A78-VM                    | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| Dell          | 0PJ149                      | [132993403b](https://linux-hardware.org/?probe=132993403b) | May 15, 2021 |
| Dell          | 0PJ149                      | [6c5a768962](https://linux-hardware.org/?probe=6c5a768962) | May 15, 2021 |
| Lenovo        | MAHOBAY                     | [0299025f98](https://linux-hardware.org/?probe=0299025f98) | May 15, 2021 |
| Acer          | TPDS05 R3700                | [9abf1ed283](https://linux-hardware.org/?probe=9abf1ed283) | May 15, 2021 |
| Gigabyte      | A320M-S2H-CF                | [48f873b6de](https://linux-hardware.org/?probe=48f873b6de) | May 14, 2021 |
| MSI           | B450-A PRO MAX              | [7b40989bc7](https://linux-hardware.org/?probe=7b40989bc7) | May 13, 2021 |
| MSI           | B450-A PRO MAX              | [acff281d6b](https://linux-hardware.org/?probe=acff281d6b) | May 12, 2021 |
| Gigabyte      | EP45-UD3R                   | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Dell          | 0WF810                      | [8939e63ade](https://linux-hardware.org/?probe=8939e63ade) | May 11, 2021 |
| Gigabyte      | A320M-S2H-CF                | [a3f9e2334a](https://linux-hardware.org/?probe=a3f9e2334a) | May 11, 2021 |
| Dell          | 0CU409                      | [151b11acfc](https://linux-hardware.org/?probe=151b11acfc) | May 11, 2021 |
| Dell          | 0CU409                      | [3ea181ca1b](https://linux-hardware.org/?probe=3ea181ca1b) | May 10, 2021 |
| ASUSTek       | P8Z77-V LK                  | [70b78860ae](https://linux-hardware.org/?probe=70b78860ae) | May 10, 2021 |
| Medion        | H110H4-CM2                  | [c622bcf1bb](https://linux-hardware.org/?probe=c622bcf1bb) | May 09, 2021 |
| MSI           | AM1I                        | [4c05e00484](https://linux-hardware.org/?probe=4c05e00484) | May 09, 2021 |
| Acer          | H57M01                      | [ec79128c45](https://linux-hardware.org/?probe=ec79128c45) | May 09, 2021 |
| ASRock        | A75M-HVS                    | [17d284ce82](https://linux-hardware.org/?probe=17d284ce82) | May 09, 2021 |
| Gigabyte      | A520I AC                    | [eb32404ebf](https://linux-hardware.org/?probe=eb32404ebf) | May 07, 2021 |
| Lenovo        | ThinkStation D30 4223B35    | [e3c6a7b793](https://linux-hardware.org/?probe=e3c6a7b793) | May 06, 2021 |
| Gigabyte      | H110N-CF                    | [d03c007deb](https://linux-hardware.org/?probe=d03c007deb) | May 06, 2021 |
| HP            | 2B05                        | [0bfbf859ca](https://linux-hardware.org/?probe=0bfbf859ca) | May 05, 2021 |
| Huanan        | X58-RX3.0 V111              | [5181d65714](https://linux-hardware.org/?probe=5181d65714) | May 04, 2021 |
| ASUSTek       | PRIME X570-PRO              | [e1b742d511](https://linux-hardware.org/?probe=e1b742d511) | May 04, 2021 |
| HP            | 198E                        | [396de7f15d](https://linux-hardware.org/?probe=396de7f15d) | May 03, 2021 |
| Gigabyte      | H81M-DS2                    | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [05bc374383](https://linux-hardware.org/?probe=05bc374383) | May 02, 2021 |
| Dell          | 02YRK5 A02                  | [0ff2e7f046](https://linux-hardware.org/?probe=0ff2e7f046) | May 02, 2021 |
| ASUSTek       | Z170-P                      | [036adc9920](https://linux-hardware.org/?probe=036adc9920) | May 02, 2021 |
| MSI           | Z490M-S01                   | [b2de3af507](https://linux-hardware.org/?probe=b2de3af507) | May 02, 2021 |
| Foxconn       | H67M-S/H67M-V/H67           | [f22a2df347](https://linux-hardware.org/?probe=f22a2df347) | May 01, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [f2e3521766](https://linux-hardware.org/?probe=f2e3521766) | Apr 30, 2021 |
| Lenovo        | ThinkCentre M57 6071ADF     | [aeb8467831](https://linux-hardware.org/?probe=aeb8467831) | Apr 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | [0deafa542c](https://linux-hardware.org/?probe=0deafa542c) | Apr 29, 2021 |
| Gigabyte      | A320M-S2H-CF                | [04d81bb2f6](https://linux-hardware.org/?probe=04d81bb2f6) | Apr 29, 2021 |
| Acer          | FC51GM                      | [ace5e495f5](https://linux-hardware.org/?probe=ace5e495f5) | Apr 26, 2021 |
| ASRock        | X300M-STX                   | [0f15e44442](https://linux-hardware.org/?probe=0f15e44442) | Apr 26, 2021 |
| HP            | 21B4 A01                    | [9193163279](https://linux-hardware.org/?probe=9193163279) | Apr 26, 2021 |
| ASRock        | B550 Taichi                 | [cbb2ac50e7](https://linux-hardware.org/?probe=cbb2ac50e7) | Apr 25, 2021 |
| ASUSTek       | H87M-PLUS                   | [7ecfe05882](https://linux-hardware.org/?probe=7ecfe05882) | Apr 25, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [f6e266a897](https://linux-hardware.org/?probe=f6e266a897) | Apr 25, 2021 |
| ASRock        | Z170 Gaming K4              | [69ec5d246b](https://linux-hardware.org/?probe=69ec5d246b) | Apr 25, 2021 |
| ASRock        | N68-VS3 FX                  | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| Toshiba       | STI 001213 ECS              | [f3b44173de](https://linux-hardware.org/?probe=f3b44173de) | Apr 24, 2021 |
| Intel         | DH61WW AAG23116-203         | [32aae9ea9a](https://linux-hardware.org/?probe=32aae9ea9a) | Apr 24, 2021 |
| HP            | 339A                        | [ed44deea1a](https://linux-hardware.org/?probe=ed44deea1a) | Apr 21, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [2517cbf080](https://linux-hardware.org/?probe=2517cbf080) | Apr 20, 2021 |
| Dell          | 06D7TR A00                  | [907d14ed71](https://linux-hardware.org/?probe=907d14ed71) | Apr 20, 2021 |
| MSI           | 770-G45                     | [85ebceeb24](https://linux-hardware.org/?probe=85ebceeb24) | Apr 20, 2021 |
| Dell          | 0M5DCD A02                  | [ef0ddc38ce](https://linux-hardware.org/?probe=ef0ddc38ce) | Apr 19, 2021 |
| ASUSTek       | P8B75-V                     | [57d0c51af4](https://linux-hardware.org/?probe=57d0c51af4) | Apr 18, 2021 |
| Dell          | 0KRC95 A03                  | [61da77da82](https://linux-hardware.org/?probe=61da77da82) | Apr 18, 2021 |
| HP            | 3047h                       | [c426bd5393](https://linux-hardware.org/?probe=c426bd5393) | Apr 18, 2021 |
| Gigabyte      | G31M-ES2C                   | [1b5a4441c9](https://linux-hardware.org/?probe=1b5a4441c9) | Apr 18, 2021 |
| Huanan        | X58-RX3.0 V111              | [52841d2dbf](https://linux-hardware.org/?probe=52841d2dbf) | Apr 17, 2021 |
| HP            | ML110 G4                    | [443a299302](https://linux-hardware.org/?probe=443a299302) | Apr 17, 2021 |
| Dell          | 0M5DCD A02                  | [91f1b586b4](https://linux-hardware.org/?probe=91f1b586b4) | Apr 16, 2021 |
| Lenovo        | ThinkCentre M57 6071ADF     | [d997531604](https://linux-hardware.org/?probe=d997531604) | Apr 16, 2021 |
| Acer          | TPDS05 R3700                | [4c7b9482f3](https://linux-hardware.org/?probe=4c7b9482f3) | Apr 15, 2021 |
| Pegatron      | 2AC2A                       | [87fa4f3888](https://linux-hardware.org/?probe=87fa4f3888) | Apr 13, 2021 |
| ASUSTek       | AM1I-A                      | [6c2469b32a](https://linux-hardware.org/?probe=6c2469b32a) | Apr 11, 2021 |
| MSI           | B450M MORTAR MAX            | [aa0ca44bd4](https://linux-hardware.org/?probe=aa0ca44bd4) | Apr 11, 2021 |
| MSI           | B450M MORTAR MAX            | [fb354a97da](https://linux-hardware.org/?probe=fb354a97da) | Apr 11, 2021 |
| Acer          | Aspire X1430                | [b3b59b7e37](https://linux-hardware.org/?probe=b3b59b7e37) | Apr 11, 2021 |
| ASUSTek       | AM1I-A                      | [56f187f014](https://linux-hardware.org/?probe=56f187f014) | Apr 11, 2021 |
| ASRock        | H270M-ITX/ac                | [071ce283c1](https://linux-hardware.org/?probe=071ce283c1) | Apr 11, 2021 |
| ASRock        | H270M-ITX/ac                | [73cf10f10a](https://linux-hardware.org/?probe=73cf10f10a) | Apr 11, 2021 |
| ASRock        | B450M/ac                    | [ef79828d94](https://linux-hardware.org/?probe=ef79828d94) | Apr 11, 2021 |
| Dell          | 0GM819                      | [95f4b4a653](https://linux-hardware.org/?probe=95f4b4a653) | Apr 10, 2021 |
| Gigabyte      | X99-UD4-CF                  | [2189f9be68](https://linux-hardware.org/?probe=2189f9be68) | Apr 10, 2021 |
| ASRock        | B450 Pro4                   | [e97c041e12](https://linux-hardware.org/?probe=e97c041e12) | Apr 10, 2021 |
| MSI           | 970A-G43                    | [4618a9eef4](https://linux-hardware.org/?probe=4618a9eef4) | Apr 09, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [cb6c7d5ecb](https://linux-hardware.org/?probe=cb6c7d5ecb) | Apr 09, 2021 |
| ASUSTek       | P5VD2-VM SE                 | [922a324d57](https://linux-hardware.org/?probe=922a324d57) | Apr 09, 2021 |
| HP            | EG157AA-ABF m1260.fr        | [cf4f87aefd](https://linux-hardware.org/?probe=cf4f87aefd) | Apr 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | [a66003eab5](https://linux-hardware.org/?probe=a66003eab5) | Apr 05, 2021 |
| Gigabyte      | H270-HD3-CF                 | [987824d49a](https://linux-hardware.org/?probe=987824d49a) | Apr 05, 2021 |
| Biostar       | TB250-BTC                   | [a1b3b845a7](https://linux-hardware.org/?probe=a1b3b845a7) | Apr 05, 2021 |
| Biostar       | TB250-BTC                   | [908171f266](https://linux-hardware.org/?probe=908171f266) | Apr 05, 2021 |
| ASUSTek       | P5LD2EB2-DHS                | [4089d0f836](https://linux-hardware.org/?probe=4089d0f836) | Apr 04, 2021 |
| MSI           | P45-C51                     | [fd6b5e81cc](https://linux-hardware.org/?probe=fd6b5e81cc) | Apr 04, 2021 |
| Intel         | DG31PR AAD97573-302         | [330f034c61](https://linux-hardware.org/?probe=330f034c61) | Apr 04, 2021 |
| Intel         | DG31PR AAD97573-302         | [4cf71fac35](https://linux-hardware.org/?probe=4cf71fac35) | Apr 04, 2021 |
| ASUSTek       | B150I PRO GAMING/AURA       | [b33866b71b](https://linux-hardware.org/?probe=b33866b71b) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| Gigabyte      | 990FXA-UD3                  | [327a4888d5](https://linux-hardware.org/?probe=327a4888d5) | Apr 03, 2021 |
| Acer          | RS780DV                     | [42ed33d902](https://linux-hardware.org/?probe=42ed33d902) | Apr 03, 2021 |
| ASUSTek       | PRIME Z390-A                | [d17ca5581f](https://linux-hardware.org/?probe=d17ca5581f) | Apr 01, 2021 |
| MSI           | MS-7061                     | [ff8b934f8d](https://linux-hardware.org/?probe=ff8b934f8d) | Mar 31, 2021 |
| ASUSTek       | P8H61                       | [cb9797346b](https://linux-hardware.org/?probe=cb9797346b) | Mar 30, 2021 |
| Huanan        | X58-RX3.0 V111              | [c18bd3abe8](https://linux-hardware.org/?probe=c18bd3abe8) | Mar 30, 2021 |
| ASRock        | K10N78D                     | [500f4c7c38](https://linux-hardware.org/?probe=500f4c7c38) | Mar 29, 2021 |
| ASRock        | ALiveNF6G-GLAN              | [1f409f9bf1](https://linux-hardware.org/?probe=1f409f9bf1) | Mar 28, 2021 |
| ASUSTek       | A68HM-K                     | [ef5acde9af](https://linux-hardware.org/?probe=ef5acde9af) | Mar 28, 2021 |
| eMachines     | EL1850                      | [7c2d95778c](https://linux-hardware.org/?probe=7c2d95778c) | Mar 27, 2021 |
| Gigabyte      | Z97X-Gaming 5               | [ab9c020fbf](https://linux-hardware.org/?probe=ab9c020fbf) | Mar 26, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [47323e14e8](https://linux-hardware.org/?probe=47323e14e8) | Mar 26, 2021 |
| ASUSTek       | P8Z68 DELUXE                | [8ce30ac5a9](https://linux-hardware.org/?probe=8ce30ac5a9) | Mar 26, 2021 |
| HP            | 3646h                       | [b529769ddc](https://linux-hardware.org/?probe=b529769ddc) | Mar 25, 2021 |
| ASUSTek       | P5KC                        | [0d1ffacb54](https://linux-hardware.org/?probe=0d1ffacb54) | Mar 24, 2021 |
| Foxconn       | G31MXP FAB:1.1              | [e1e70c62da](https://linux-hardware.org/?probe=e1e70c62da) | Mar 23, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [56e94aaad4](https://linux-hardware.org/?probe=56e94aaad4) | Mar 23, 2021 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [ca09a97564](https://linux-hardware.org/?probe=ca09a97564) | Mar 23, 2021 |
| Gigabyte      | 945GZM-S2                   | [3da6cb6a08](https://linux-hardware.org/?probe=3da6cb6a08) | Mar 22, 2021 |
| Gigabyte      | Z97X-Gaming 5               | [5d83038560](https://linux-hardware.org/?probe=5d83038560) | Mar 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | [ee93b490f0](https://linux-hardware.org/?probe=ee93b490f0) | Mar 22, 2021 |
| ASRock        | X300M-STX                   | [d5722fd82b](https://linux-hardware.org/?probe=d5722fd82b) | Mar 22, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [070c4000e1](https://linux-hardware.org/?probe=070c4000e1) | Mar 22, 2021 |
| Foxconn       | nT-i1000 Series PCB         | [05ae766e7f](https://linux-hardware.org/?probe=05ae766e7f) | Mar 20, 2021 |
| Gigabyte      | Z97X-Gaming 5               | [3795b5e3a6](https://linux-hardware.org/?probe=3795b5e3a6) | Mar 19, 2021 |
| ECS           | J1800NH3                    | [69c12914ce](https://linux-hardware.org/?probe=69c12914ce) | Mar 19, 2021 |
| Gigabyte      | B450M S2H                   | [deb06f914c](https://linux-hardware.org/?probe=deb06f914c) | Mar 19, 2021 |
| ASRock        | A320M-HDV R3.0              | [05f64afe14](https://linux-hardware.org/?probe=05f64afe14) | Mar 18, 2021 |
| HP            | 3031h                       | [b30170a46c](https://linux-hardware.org/?probe=b30170a46c) | Mar 18, 2021 |
| MSI           | Z97-G43                     | [984145ba36](https://linux-hardware.org/?probe=984145ba36) | Mar 18, 2021 |
| ASRock        | AB350M Pro4 R2.0            | [d5ddb563ac](https://linux-hardware.org/?probe=d5ddb563ac) | Mar 18, 2021 |
| ASRock        | AB350M Pro4 R2.0            | [af9b948ec2](https://linux-hardware.org/?probe=af9b948ec2) | Mar 17, 2021 |
| Intel         | X99                         | [eff3e65d6d](https://linux-hardware.org/?probe=eff3e65d6d) | Mar 17, 2021 |
| MSI           | H310M PRO-VH PLUS           | [b952795165](https://linux-hardware.org/?probe=b952795165) | Mar 17, 2021 |
| ASUSTek       | M4A78 PRO                   | [0d75059dc8](https://linux-hardware.org/?probe=0d75059dc8) | Mar 17, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [7cc0dfac27](https://linux-hardware.org/?probe=7cc0dfac27) | Mar 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [b26a3ac620](https://linux-hardware.org/?probe=b26a3ac620) | Mar 17, 2021 |
| Intel         | X99                         | [1f84949851](https://linux-hardware.org/?probe=1f84949851) | Mar 17, 2021 |
| MSI           | A88XM-E45                   | [96048dac39](https://linux-hardware.org/?probe=96048dac39) | Mar 17, 2021 |
| HP            | 2B17                        | [753cbbeb9e](https://linux-hardware.org/?probe=753cbbeb9e) | Mar 16, 2021 |
| ASRock        | X300M-STX                   | [b36b41329b](https://linux-hardware.org/?probe=b36b41329b) | Mar 14, 2021 |
| ASUSTek       | P4C800-E                    | [e4d5f651e2](https://linux-hardware.org/?probe=e4d5f651e2) | Mar 14, 2021 |
| ASRock        | FM2A88X-ITX+                | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| Dell          | 0T656F A02                  | [708eb1bf51](https://linux-hardware.org/?probe=708eb1bf51) | Mar 13, 2021 |
| HP            | 339A                        | [355b85c060](https://linux-hardware.org/?probe=355b85c060) | Mar 13, 2021 |
| Medion        | H110H4-EM                   | [c0f324b6aa](https://linux-hardware.org/?probe=c0f324b6aa) | Mar 13, 2021 |
| HP            | 18E7                        | [c0793d8023](https://linux-hardware.org/?probe=c0793d8023) | Mar 13, 2021 |
| HP            | 339A                        | [a24b4dd571](https://linux-hardware.org/?probe=a24b4dd571) | Mar 13, 2021 |
| ASUSTek       | P5KC                        | [d20831473f](https://linux-hardware.org/?probe=d20831473f) | Mar 12, 2021 |
| HP            | 212B                        | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Dell          | 0T656F A02                  | [cc36a18a02](https://linux-hardware.org/?probe=cc36a18a02) | Mar 12, 2021 |
| Lenovo        | ThinkCentre M91p 4518A13    | [85a5abb007](https://linux-hardware.org/?probe=85a5abb007) | Mar 12, 2021 |
| Acer          | Aspire TC-780               | [5ac5e5625a](https://linux-hardware.org/?probe=5ac5e5625a) | Mar 12, 2021 |
| Intel         | DG965MQ AAD37419-302        | [2c5b191c86](https://linux-hardware.org/?probe=2c5b191c86) | Mar 11, 2021 |
| MSI           | B450M MORTAR MAX            | [a4da5e59df](https://linux-hardware.org/?probe=a4da5e59df) | Mar 11, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [5f4e258cd5](https://linux-hardware.org/?probe=5f4e258cd5) | Mar 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | [0d5694c1b3](https://linux-hardware.org/?probe=0d5694c1b3) | Mar 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [0dc7c8f9dc](https://linux-hardware.org/?probe=0dc7c8f9dc) | Mar 10, 2021 |
| ASUSTek       | P5K Premium                 | [868aaae2fd](https://linux-hardware.org/?probe=868aaae2fd) | Mar 09, 2021 |
| Foxconn       | 2ADA                        | [2540cc492a](https://linux-hardware.org/?probe=2540cc492a) | Mar 09, 2021 |
| Dell          | 0GM819                      | [395dee4e1f](https://linux-hardware.org/?probe=395dee4e1f) | Mar 08, 2021 |
| HP            | 21B4 A01                    | [1b6837c321](https://linux-hardware.org/?probe=1b6837c321) | Mar 08, 2021 |
| HP            | 339A                        | [dd14e6b8f8](https://linux-hardware.org/?probe=dd14e6b8f8) | Mar 08, 2021 |
| Gigabyte      | 970-GAMING                  | [f05a49c047](https://linux-hardware.org/?probe=f05a49c047) | Mar 08, 2021 |
| Intel         | DG965MQ AAD37419-302        | [e444e349b6](https://linux-hardware.org/?probe=e444e349b6) | Mar 08, 2021 |
| ASUSTek       | P5K Premium                 | [551f3363c1](https://linux-hardware.org/?probe=551f3363c1) | Mar 07, 2021 |
| HP            | 212B                        | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| ASRock        | FM2A68M-HD+                 | [a9a3d7da6f](https://linux-hardware.org/?probe=a9a3d7da6f) | Mar 05, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| ASUSTek       | M2N68-AM Plus               | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | [bfa3a17409](https://linux-hardware.org/?probe=bfa3a17409) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | [4b9649e87e](https://linux-hardware.org/?probe=4b9649e87e) | Mar 02, 2021 |
| Gigabyte      | M61PME-S2P                  | [39f661106f](https://linux-hardware.org/?probe=39f661106f) | Mar 01, 2021 |
| Unknown       | Intel X79                   | [85e2bda5cc](https://linux-hardware.org/?probe=85e2bda5cc) | Feb 28, 2021 |
| Unknown       | Intel X79                   | [cbe66f456c](https://linux-hardware.org/?probe=cbe66f456c) | Feb 28, 2021 |
| Acer          | Veriton X2611G V1.0         | [0f52aff29d](https://linux-hardware.org/?probe=0f52aff29d) | Feb 27, 2021 |
| ASRock        | A320M-HDV R4.0              | [9057e2fabf](https://linux-hardware.org/?probe=9057e2fabf) | Feb 27, 2021 |
| Acer          | Veriton X2611G V1.0         | [ba907b59a6](https://linux-hardware.org/?probe=ba907b59a6) | Feb 27, 2021 |
| Gigabyte      | 8I915PL-G                   | [e9ed9c7fdf](https://linux-hardware.org/?probe=e9ed9c7fdf) | Feb 27, 2021 |
| MSI           | H87-G43 GAMING              | [84a36237d0](https://linux-hardware.org/?probe=84a36237d0) | Feb 24, 2021 |
| MSI           | B450M PRO-VDH MAX           | [be1a115b55](https://linux-hardware.org/?probe=be1a115b55) | Feb 23, 2021 |
| ASUSTek       | Rampage V EXTREME           | [8912ddde77](https://linux-hardware.org/?probe=8912ddde77) | Feb 23, 2021 |
| Shuttle       | B10IE01                     | [33f0017dbd](https://linux-hardware.org/?probe=33f0017dbd) | Feb 22, 2021 |
| Shuttle       | B10IE01                     | [33babdfb03](https://linux-hardware.org/?probe=33babdfb03) | Feb 22, 2021 |
| Dell          | 0YC523                      | [d805d39715](https://linux-hardware.org/?probe=d805d39715) | Feb 22, 2021 |
| ASUSTek       | P5K                         | [26b7e4d025](https://linux-hardware.org/?probe=26b7e4d025) | Feb 22, 2021 |
| Pegatron      | NARRA5                      | [294b1c19fb](https://linux-hardware.org/?probe=294b1c19fb) | Feb 20, 2021 |
| Intel         | DP55WB AAE64798-204         | [6e9ac2a13d](https://linux-hardware.org/?probe=6e9ac2a13d) | Feb 20, 2021 |
| ASRock        | X300M-STX                   | [826dd058e1](https://linux-hardware.org/?probe=826dd058e1) | Feb 20, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Xubuntu 20.04 | 798      | 51.82%  |
| Xubuntu 18.04 | 388      | 25.19%  |
| Xubuntu 22.04 | 96       | 6.23%   |
| Xubuntu 19.10 | 77       | 5%      |
| Xubuntu 16.04 | 48       | 3.12%   |
| Xubuntu 20.10 | 43       | 2.79%   |
| Xubuntu 21.10 | 33       | 2.14%   |
| Xubuntu 21.04 | 29       | 1.88%   |
| Xubuntu 19.04 | 11       | 0.71%   |
| Xubuntu 22.10 | 10       | 0.65%   |
| Xubuntu 18.10 | 5        | 0.32%   |
| Xubuntu       | 2        | 0.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Xubuntu | 1475     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.4.0-42-generic    | 62       | 3.45%   |
| 5.4.0-48-generic    | 33       | 1.83%   |
| 5.4.0-52-generic    | 28       | 1.56%   |
| 5.4.0-58-generic    | 26       | 1.45%   |
| 5.4.0-42-lowlatency | 21       | 1.17%   |
| 5.3.0-40-generic    | 20       | 1.11%   |
| 5.15.0-52-generic   | 20       | 1.11%   |
| 5.4.0-65-generic    | 19       | 1.06%   |
| 5.4.0-54-generic    | 19       | 1.06%   |
| 5.4.0-37-generic    | 17       | 0.94%   |
| 5.4.0-26-generic    | 17       | 0.94%   |
| 5.4.0-126-generic   | 17       | 0.94%   |
| 5.3.0-46-generic    | 17       | 0.94%   |
| 5.4.0-29-generic    | 16       | 0.89%   |
| 5.3.0-28-generic    | 15       | 0.83%   |
| 5.15.0-56-generic   | 15       | 0.83%   |
| 5.4.0-72-generic    | 14       | 0.78%   |
| 5.4.0-66-generic    | 14       | 0.78%   |
| 5.4.0-40-lowlatency | 14       | 0.78%   |
| 5.4.0-40-generic    | 14       | 0.78%   |
| 5.4.0-29-lowlatency | 14       | 0.78%   |
| 5.4.0-125-generic   | 14       | 0.78%   |
| 5.15.0-46-generic   | 14       | 0.78%   |
| 5.0.0-37-generic    | 13       | 0.72%   |
| 4.15.0-72-generic   | 13       | 0.72%   |
| 5.4.0-89-generic    | 12       | 0.67%   |
| 5.4.0-81-generic    | 12       | 0.67%   |
| 5.4.0-91-generic    | 11       | 0.61%   |
| 5.4.0-73-generic    | 11       | 0.61%   |
| 5.4.0-70-generic    | 11       | 0.61%   |
| 5.4.0-52-lowlatency | 11       | 0.61%   |
| 5.4.0-47-generic    | 11       | 0.61%   |
| 5.4.0-45-generic    | 11       | 0.61%   |
| 5.4.0-37-lowlatency | 11       | 0.61%   |
| 5.0.0-36-generic    | 11       | 0.61%   |
| 4.15.0-99-generic   | 11       | 0.61%   |
| 5.4.0-80-generic    | 10       | 0.56%   |
| 5.4.0-77-generic    | 10       | 0.56%   |
| 5.4.0-74-generic    | 10       | 0.56%   |
| 5.4.0-47-lowlatency | 10       | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 684      | 43.57%  |
| 4.15.0  | 209      | 13.31%  |
| 5.3.0   | 157      | 10%     |
| 5.15.0  | 116      | 7.39%   |
| 5.8.0   | 102      | 6.5%    |
| 5.11.0  | 90       | 5.73%   |
| 5.13.0  | 78       | 4.97%   |
| 5.0.0   | 45       | 2.87%   |
| 4.4.0   | 22       | 1.4%    |
| 5.19.0  | 13       | 0.83%   |
| 4.18.0  | 10       | 0.64%   |
| 4.10.0  | 4        | 0.25%   |
| 5.9.8   | 2        | 0.13%   |
| 5.9.16  | 2        | 0.13%   |
| 5.6.0   | 2        | 0.13%   |
| 5.17.0  | 2        | 0.13%   |
| 5.15.1  | 2        | 0.13%   |
| 5.11.16 | 2        | 0.13%   |
| 4.13.0  | 2        | 0.13%   |
| 5.9.14  | 1        | 0.06%   |
| 5.8.5   | 1        | 0.06%   |
| 5.8.1   | 1        | 0.06%   |
| 5.7.17  | 1        | 0.06%   |
| 5.7.1   | 1        | 0.06%   |
| 5.6.6   | 1        | 0.06%   |
| 5.5.13  | 1        | 0.06%   |
| 5.4.64  | 1        | 0.06%   |
| 5.2.3   | 1        | 0.06%   |
| 5.19.13 | 1        | 0.06%   |
| 5.16.9  | 1        | 0.06%   |
| 5.16.0  | 1        | 0.06%   |
| 5.14.7  | 1        | 0.06%   |
| 5.13.7  | 1        | 0.06%   |
| 5.13.4  | 1        | 0.06%   |
| 5.12.2  | 1        | 0.06%   |
| 5.12.17 | 1        | 0.06%   |
| 5.12.12 | 1        | 0.06%   |
| 5.12.10 | 1        | 0.06%   |
| 5.11.6  | 1        | 0.06%   |
| 5.10.27 | 1        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 685      | 43.71%  |
| 4.15    | 209      | 13.34%  |
| 5.3     | 157      | 10.02%  |
| 5.15    | 118      | 7.53%   |
| 5.8     | 104      | 6.64%   |
| 5.11    | 91       | 5.81%   |
| 5.13    | 80       | 5.11%   |
| 5.0     | 46       | 2.94%   |
| 4.4     | 22       | 1.4%    |
| 5.19    | 14       | 0.89%   |
| 4.18    | 10       | 0.64%   |
| 5.9     | 5        | 0.32%   |
| 4.10    | 4        | 0.26%   |
| 5.6     | 3        | 0.19%   |
| 5.12    | 3        | 0.19%   |
| 5.10    | 3        | 0.19%   |
| 5.7     | 2        | 0.13%   |
| 5.17    | 2        | 0.13%   |
| 5.16    | 2        | 0.13%   |
| 4.13    | 2        | 0.13%   |
| 5.5     | 1        | 0.06%   |
| 5.2     | 1        | 0.06%   |
| 5.14    | 1        | 0.06%   |
| 4.8     | 1        | 0.06%   |
| 4.14    | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1323     | 89.45%  |
| i686   | 155      | 10.48%  |
| armv7l | 1        | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 1427     | 96.55%  |
| GNOME           | 37       | 2.5%    |
| KDE5            | 4        | 0.27%   |
| X-Cinnamon      | 2        | 0.14%   |
| GNOME Flashback | 2        | 0.14%   |
| Cinnamon        | 2        | 0.14%   |
| MATE            | 1        | 0.07%   |
| LXQt            | 1        | 0.07%   |
| GNUstep         | 1        | 0.07%   |
| Unknown         | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1443     | 97.7%   |
| Tty     | 25       | 1.69%   |
| Wayland | 5        | 0.34%   |
| Web     | 3        | 0.2%    |
| Unknown | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 870      | 56.94%  |
| LightDM | 423      | 27.68%  |
| TDM     | 197      | 12.89%  |
| GDM3    | 17       | 1.11%   |
| GDM     | 17       | 1.11%   |
| XDM     | 3        | 0.2%    |
| SDDM    | 1        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 449      | 30.17%  |
| de_DE   | 155      | 10.42%  |
| fr_FR   | 136      | 9.14%   |
| it_IT   | 92       | 6.18%   |
| ru_RU   | 89       | 5.98%   |
| pt_BR   | 83       | 5.58%   |
| en_GB   | 53       | 3.56%   |
| en_CA   | 53       | 3.56%   |
| en_AU   | 36       | 2.42%   |
| es_ES   | 35       | 2.35%   |
| Unknown | 32       | 2.15%   |
| C       | 30       | 2.02%   |
| pl_PL   | 21       | 1.41%   |
| es_AR   | 21       | 1.41%   |
| nl_NL   | 20       | 1.34%   |
| ja_JP   | 20       | 1.34%   |
| hu_HU   | 18       | 1.21%   |
| zh_TW   | 9        | 0.6%    |
| fr_BE   | 8        | 0.54%   |
| sv_SE   | 7        | 0.47%   |
| fr_CA   | 7        | 0.47%   |
| es_MX   | 7        | 0.47%   |
| cs_CZ   | 7        | 0.47%   |
| ru_UA   | 6        | 0.4%    |
| pt_PT   | 6        | 0.4%    |
| fi_FI   | 6        | 0.4%    |
| es_CO   | 6        | 0.4%    |
| de_AT   | 6        | 0.4%    |
| sk_SK   | 5        | 0.34%   |
| en_ZA   | 5        | 0.34%   |
| ro_RO   | 4        | 0.27%   |
| es_UY   | 4        | 0.27%   |
| en_IN   | 4        | 0.27%   |
| de_CH   | 4        | 0.27%   |
| zh_CN   | 3        | 0.2%    |
| nl_BE   | 3        | 0.2%    |
| es_VE   | 3        | 0.2%    |
| en_IL   | 3        | 0.2%    |
| tr_TR   | 2        | 0.13%   |
| sl_SI   | 2        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1124     | 75.08%  |
| EFI  | 373      | 24.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1372     | 92.45%  |
| Overlay | 37       | 2.49%   |
| Btrfs   | 28       | 1.89%   |
| Zfs     | 16       | 1.08%   |
| Unknown | 11       | 0.74%   |
| Xfs     | 10       | 0.67%   |
| Ext2    | 5        | 0.34%   |
| Ext3    | 4        | 0.27%   |
| Aufs    | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1014     | 68.01%  |
| GPT     | 268      | 17.97%  |
| MBR     | 209      | 14.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1161     | 76.84%  |
| Yes       | 350      | 23.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 912      | 60.2%   |
| Yes       | 603      | 39.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 326      | 22.1%   |
| Gigabyte Technology | 206      | 13.97%  |
| Dell                | 165      | 11.19%  |
| ASRock              | 141      | 9.56%   |
| MSI                 | 136      | 9.22%   |
| Hewlett-Packard     | 134      | 9.08%   |
| Lenovo              | 54       | 3.66%   |
| Intel               | 42       | 2.85%   |
| Acer                | 40       | 2.71%   |
| ECS                 | 28       | 1.9%    |
| Unknown             | 25       | 1.69%   |
| Foxconn             | 20       | 1.36%   |
| Medion              | 15       | 1.02%   |
| Fujitsu             | 15       | 1.02%   |
| Pegatron            | 13       | 0.88%   |
| eMachines           | 8        | 0.54%   |
| Biostar             | 8        | 0.54%   |
| Packard Bell        | 7        | 0.47%   |
| Fujitsu Siemens     | 7        | 0.47%   |
| Positivo            | 6        | 0.41%   |
| Apple               | 5        | 0.34%   |
| Shuttle             | 4        | 0.27%   |
| NEC Computers       | 4        | 0.27%   |
| AOpen               | 4        | 0.27%   |
| AAEON               | 4        | 0.27%   |
| PCWare              | 3        | 0.2%    |
| IBM                 | 3        | 0.2%    |
| EVGA                | 3        | 0.2%    |
| ZOTAC               | 2        | 0.14%   |
| WinFast             | 2        | 0.14%   |
| VIA Technologies    | 2        | 0.14%   |
| Semp Toshiba        | 2        | 0.14%   |
| Quanta              | 2        | 0.14%   |
| PCChips             | 2        | 0.14%   |
| OEM                 | 2        | 0.14%   |
| NCR                 | 2        | 0.14%   |
| Itautec             | 2        | 0.14%   |
| Huanan              | 2        | 0.14%   |
| Gateway             | 2        | 0.14%   |
| BCM                 | 2        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 27       | 1.83%   |
| ASUS All Series                    | 25       | 1.69%   |
| Gigabyte H410M S2H                 | 15       | 1.02%   |
| Dell OptiPlex 7010                 | 15       | 1.02%   |
| Dell OptiPlex 755                  | 11       | 0.75%   |
| ECS G31T-M9                        | 9        | 0.61%   |
| Dell OptiPlex 780                  | 8        | 0.54%   |
| Dell OptiPlex 760                  | 8        | 0.54%   |
| Dell OptiPlex 390                  | 8        | 0.54%   |
| ASRock N68C-S UCC                  | 8        | 0.54%   |
| MSI MS-7C37                        | 6        | 0.41%   |
| HP EliteDesk 800 G1 SFF            | 6        | 0.41%   |
| ASUS TUF Gaming X570-PLUS          | 6        | 0.41%   |
| MSI MS-7B89                        | 5        | 0.34%   |
| MSI MS-7B79                        | 5        | 0.34%   |
| MSI MS-7A38                        | 5        | 0.34%   |
| MSI MS-7721                        | 5        | 0.34%   |
| HP Compaq Elite 8300 SFF           | 5        | 0.34%   |
| HP Compaq dc7600 Small Form Factor | 5        | 0.34%   |
| Dell OptiPlex GX620                | 5        | 0.34%   |
| Dell OptiPlex 3020                 | 5        | 0.34%   |
| ASUS M5A78L-M/USB3                 | 5        | 0.34%   |
| MSI MS-7C02                        | 4        | 0.27%   |
| MSI MS-7817                        | 4        | 0.27%   |
| MSI MS-7816                        | 4        | 0.27%   |
| MSI MS-7693                        | 4        | 0.27%   |
| Intel H61                          | 4        | 0.27%   |
| HP Z420 Workstation                | 4        | 0.27%   |
| HP Compaq Pro 6300 SFF             | 4        | 0.27%   |
| HP Compaq dc7900 Small Form Factor | 4        | 0.27%   |
| HP Compaq 8200 Elite SFF PC        | 4        | 0.27%   |
| HP Compaq 6200 Pro MT PC           | 4        | 0.27%   |
| Gigabyte X570 AORUS MASTER         | 4        | 0.27%   |
| Gigabyte GA-MA785GM-US2H           | 4        | 0.27%   |
| Gigabyte B450M DS3H                | 4        | 0.27%   |
| Gigabyte 945GZM-S2                 | 4        | 0.27%   |
| Dell Precision WorkStation T7400   | 4        | 0.27%   |
| Dell OptiPlex 990                  | 4        | 0.27%   |
| Dell OptiPlex 9020                 | 4        | 0.27%   |
| Dell OptiPlex 3010                 | 4        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 93       | 6.31%   |
| HP Compaq           | 62       | 4.2%    |
| ASUS PRIME          | 44       | 2.98%   |
| Lenovo ThinkCentre  | 37       | 2.51%   |
| Unknown             | 27       | 1.83%   |
| Dell Inspiron       | 26       | 1.76%   |
| ASUS All            | 25       | 1.69%   |
| Dell Precision      | 19       | 1.29%   |
| Acer Aspire         | 19       | 1.29%   |
| ASUS TUF            | 18       | 1.22%   |
| Acer Veriton        | 16       | 1.08%   |
| Gigabyte H410M      | 15       | 1.02%   |
| HP ProDesk          | 13       | 0.88%   |
| HP EliteDesk        | 13       | 0.88%   |
| Fujitsu ESPRIMO     | 11       | 0.75%   |
| ASUS ROG            | 10       | 0.68%   |
| ASUS P8H61-M        | 10       | 0.68%   |
| ECS G31T-M9         | 9        | 0.61%   |
| ASUS P5KPL-AM       | 9        | 0.61%   |
| ASUS M5A78L-M       | 9        | 0.61%   |
| ASRock N68C-S       | 8        | 0.54%   |
| Packard Bell IMEDIA | 7        | 0.47%   |
| Gigabyte X570       | 7        | 0.47%   |
| MSI MS-7C37         | 6        | 0.41%   |
| Lenovo ThinkStation | 6        | 0.41%   |
| Lenovo IdeaCentre   | 6        | 0.41%   |
| Gigabyte B450M      | 6        | 0.41%   |
| ASUS P9X79          | 6        | 0.41%   |
| ASUS P8Z77-V        | 6        | 0.41%   |
| ASUS P5K            | 6        | 0.41%   |
| MSI MS-7B89         | 5        | 0.34%   |
| MSI MS-7B79         | 5        | 0.34%   |
| MSI MS-7A38         | 5        | 0.34%   |
| MSI MS-7721         | 5        | 0.34%   |
| Dell Studio         | 5        | 0.34%   |
| ASRock B450M        | 5        | 0.34%   |
| MSI MS-7C02         | 4        | 0.27%   |
| MSI MS-7817         | 4        | 0.27%   |
| MSI MS-7816         | 4        | 0.27%   |
| MSI MS-7693         | 4        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 138      | 9.36%   |
| 2009    | 137      | 9.29%   |
| 2013    | 126      | 8.54%   |
| 2011    | 125      | 8.47%   |
| 2010    | 112      | 7.59%   |
| 2007    | 105      | 7.12%   |
| 2008    | 103      | 6.98%   |
| 2018    | 94       | 6.37%   |
| 2014    | 82       | 5.56%   |
| 2019    | 81       | 5.49%   |
| 2017    | 68       | 4.61%   |
| 2020    | 59       | 4%      |
| 2006    | 59       | 4%      |
| 2015    | 56       | 3.8%    |
| 2016    | 44       | 2.98%   |
| 2005    | 34       | 2.31%   |
| 2021    | 23       | 1.56%   |
| 2004    | 9        | 0.61%   |
| 2003    | 7        | 0.47%   |
| 2022    | 4        | 0.27%   |
| 2001    | 4        | 0.27%   |
| Unknown | 3        | 0.2%    |
| 2002    | 2        | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1475     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1448     | 97.77%  |
| Enabled  | 33       | 2.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1474     | 99.93%  |
| Yes  | 1        | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 342      | 22.71%  |
| 16.01-24.0      | 259      | 17.2%   |
| 8.01-16.0       | 259      | 17.2%   |
| 4.01-8.0        | 234      | 15.54%  |
| 1.01-2.0        | 139      | 9.23%   |
| 32.01-64.0      | 116      | 7.7%    |
| 2.01-3.0        | 49       | 3.25%   |
| 64.01-256.0     | 46       | 3.05%   |
| 0.51-1.0        | 30       | 1.99%   |
| 24.01-32.0      | 26       | 1.73%   |
| 0.01-0.5        | 5        | 0.33%   |
| More than 256.0 | 1        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 714      | 42.73%  |
| 0.51-1.0   | 310      | 18.55%  |
| 2.01-3.0   | 276      | 16.52%  |
| 4.01-8.0   | 150      | 8.98%   |
| 3.01-4.0   | 124      | 7.42%   |
| 8.01-16.0  | 46       | 2.75%   |
| 0.01-0.5   | 36       | 2.15%   |
| 16.01-24.0 | 7        | 0.42%   |
| 24.01-32.0 | 6        | 0.36%   |
| 32.01-64.0 | 2        | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 681      | 44.28%  |
| 2      | 435      | 28.28%  |
| 3      | 232      | 15.08%  |
| 4      | 98       | 6.37%   |
| 5      | 45       | 2.93%   |
| 6      | 18       | 1.17%   |
| 7      | 11       | 0.72%   |
| 0      | 9        | 0.59%   |
| 10     | 4        | 0.26%   |
| 8      | 3        | 0.2%    |
| 9      | 2        | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 867      | 57.88%  |
| No        | 631      | 42.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1459     | 98.92%  |
| No        | 16       | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 930      | 62.04%  |
| Yes       | 569      | 37.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1228     | 82.14%  |
| Yes       | 267      | 17.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 248      | 16.77%  |
| Germany      | 178      | 12.04%  |
| France       | 132      | 8.92%   |
| Italy        | 103      | 6.96%   |
| Russia       | 101      | 6.83%   |
| Brazil       | 92       | 6.22%   |
| Canada       | 67       | 4.53%   |
| UK           | 54       | 3.65%   |
| Spain        | 41       | 2.77%   |
| Australia    | 39       | 2.64%   |
| Netherlands  | 38       | 2.57%   |
| Ukraine      | 26       | 1.76%   |
| Argentina    | 26       | 1.76%   |
| Japan        | 23       | 1.56%   |
| Hungary      | 22       | 1.49%   |
| Poland       | 21       | 1.42%   |
| Sweden       | 19       | 1.28%   |
| Belgium      | 19       | 1.28%   |
| Finland      | 16       | 1.08%   |
| Greece       | 13       | 0.88%   |
| Taiwan       | 12       | 0.81%   |
| Mexico       | 11       | 0.74%   |
| Bulgaria     | 10       | 0.68%   |
| Austria      | 10       | 0.68%   |
| Portugal     | 9        | 0.61%   |
| Romania      | 8        | 0.54%   |
| Czechia      | 8        | 0.54%   |
| Iran         | 7        | 0.47%   |
| Thailand     | 6        | 0.41%   |
| Switzerland  | 6        | 0.41%   |
| South Africa | 6        | 0.41%   |
| Slovakia     | 6        | 0.41%   |
| Israel       | 6        | 0.41%   |
| Indonesia    | 6        | 0.41%   |
| Colombia     | 6        | 0.41%   |
| Venezuela    | 5        | 0.34%   |
| Uruguay      | 5        | 0.34%   |
| Slovenia     | 5        | 0.34%   |
| Norway       | 4        | 0.27%   |
| India        | 4        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Voronezh       | 27       | 1.72%   |
| Paris          | 17       | 1.08%   |
| Berlin         | 17       | 1.08%   |
| Sydney         | 14       | 0.89%   |
| Sao Paulo      | 12       | 0.77%   |
| Moscow         | 12       | 0.77%   |
| Rome           | 11       | 0.7%    |
| Milan          | 10       | 0.64%   |
| Madrid         | 10       | 0.64%   |
| Amsterdam      | 10       | 0.64%   |
| Vancouver      | 9        | 0.57%   |
| Montreal       | 9        | 0.57%   |
| Hamburg        | 9        | 0.57%   |
| Budapest       | 9        | 0.57%   |
| Oryol          | 8        | 0.51%   |
| Genoa          | 8        | 0.51%   |
| Rio de Janeiro | 7        | 0.45%   |
| Melbourne      | 7        | 0.45%   |
| Buenos Aires   | 7        | 0.45%   |
| Turin          | 6        | 0.38%   |
| Tehran         | 6        | 0.38%   |
| Munich         | 6        | 0.38%   |
| Cologne        | 6        | 0.38%   |
| Athens         | 6        | 0.38%   |
| Tampere        | 5        | 0.32%   |
| Sofia          | 5        | 0.32%   |
| Perth          | 5        | 0.32%   |
| Kyiv           | 5        | 0.32%   |
| Helsinki       | 5        | 0.32%   |
| Dresden        | 5        | 0.32%   |
| Warsaw         | 4        | 0.26%   |
| The Hague      | 4        | 0.26%   |
| Taipei         | 4        | 0.26%   |
| Stuttgart      | 4        | 0.26%   |
| Ottawa         | 4        | 0.26%   |
| Odessa         | 4        | 0.26%   |
| New Taipei     | 4        | 0.26%   |
| Montevideo     | 4        | 0.26%   |
| Lund           | 4        | 0.26%   |
| Londrina       | 4        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 543      | 883    | 21.93%  |
| WDC                 | 541      | 851    | 21.85%  |
| Samsung Electronics | 327      | 518    | 13.21%  |
| Hitachi             | 149      | 217    | 6.02%   |
| Toshiba             | 130      | 187    | 5.25%   |
| Kingston            | 119      | 150    | 4.81%   |
| SanDisk             | 80       | 102    | 3.23%   |
| Crucial             | 77       | 113    | 3.11%   |
| Maxtor              | 59       | 84     | 2.38%   |
| A-DATA Technology   | 37       | 46     | 1.49%   |
| Intel               | 36       | 55     | 1.45%   |
| Unknown             | 27       | 33     | 1.09%   |
| China               | 26       | 33     | 1.05%   |
| Patriot             | 24       | 29     | 0.97%   |
| HGST                | 20       | 25     | 0.81%   |
| PNY                 | 18       | 25     | 0.73%   |
| OCZ                 | 15       | 21     | 0.61%   |
| Intenso             | 15       | 22     | 0.61%   |
| Phison              | 12       | 13     | 0.48%   |
| Transcend           | 11       | 12     | 0.44%   |
| Fujitsu             | 11       | 13     | 0.44%   |
| Silicon Motion      | 9        | 10     | 0.36%   |
| SPCC                | 8        | 14     | 0.32%   |
| Lexar               | 8        | 8      | 0.32%   |
| ASMT                | 8        | 12     | 0.32%   |
| SK hynix            | 7        | 7      | 0.28%   |
| Micron Technology   | 7        | 9      | 0.28%   |
| KingDian            | 6        | 10     | 0.24%   |
| Apacer              | 6        | 9      | 0.24%   |
| Corsair             | 5        | 5      | 0.2%    |
| XPG                 | 4        | 10     | 0.16%   |
| Team                | 4        | 6      | 0.16%   |
| Plextor             | 4        | 4      | 0.16%   |
| Mushkin             | 4        | 4      | 0.16%   |
| KIOXIA              | 4        | 7      | 0.16%   |
| Hewlett-Packard     | 4        | 6      | 0.16%   |
| GOODRAM             | 4        | 6      | 0.16%   |
| Apple               | 4        | 5      | 0.16%   |
| USB3.0              | 3        | 5      | 0.12%   |
| Smartbuy            | 3        | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 45       | 1.57%   |
| Kingston SA400S37240G 240GB SSD | 45       | 1.57%   |
| Seagate ST1000DM010-2EP102 1TB  | 29       | 1.01%   |
| Samsung SSD 860 EVO 500GB       | 26       | 0.91%   |
| Toshiba DT01ACA100 1TB          | 22       | 0.77%   |
| Seagate ST3500418AS 500GB       | 19       | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB  | 19       | 0.66%   |
| Seagate ST2000DM001-1CH164 2TB  | 18       | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB  | 18       | 0.63%   |
| Seagate ST31000528AS 1TB        | 17       | 0.59%   |
| Samsung SSD 850 EVO 250GB       | 17       | 0.59%   |
| Hitachi HDS721010CLA332 1TB     | 16       | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB  | 15       | 0.52%   |
| Kingston SA400S37480G 480GB SSD | 15       | 0.52%   |
| Toshiba DT01ACA050 500GB        | 14       | 0.49%   |
| Toshiba HDWD110 1TB             | 13       | 0.45%   |
| Seagate ST380815AS 80GB         | 13       | 0.45%   |
| Seagate ST3250310AS 250GB       | 13       | 0.45%   |
| Seagate ST3160815AS 160GB       | 13       | 0.45%   |
| Seagate Expansion 4TB           | 13       | 0.45%   |
| WDC WD800JD-75MSA3 80GB         | 12       | 0.42%   |
| Seagate ST3500413AS 500GB       | 12       | 0.42%   |
| Seagate ST31000524AS 1TB        | 12       | 0.42%   |
| Samsung SSD 850 EVO 500GB       | 12       | 0.42%   |
| Patriot Burst 120GB SSD         | 12       | 0.42%   |
| Hitachi HDS721050CLA362 500GB   | 12       | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB        | 11       | 0.38%   |
| Unknown SD/MMC/MS PRO 64GB      | 11       | 0.38%   |
| Toshiba DT01ACA200 2TB          | 11       | 0.38%   |
| Crucial CT1000MX500SSD1 1TB     | 11       | 0.38%   |
| WDC WD20EARX-00PASB0 2TB        | 10       | 0.35%   |
| WDC WD10EZEX-00BN5A0 1TB        | 10       | 0.35%   |
| Seagate ST3250820AS 250GB       | 10       | 0.35%   |
| Samsung NVMe SSD Drive 1TB      | 10       | 0.35%   |
| Samsung HD103SJ 1TB             | 10       | 0.35%   |
| Kingston SA400S37120G 120GB SSD | 10       | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB  | 9        | 0.31%   |
| Samsung SSD 860 EVO 1TB         | 9        | 0.31%   |
| Samsung SSD 840 Series 120GB    | 9        | 0.31%   |
| Samsung SSD 840 EVO 250GB       | 9        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 535      | 868    | 34.27%  |
| WDC                 | 502      | 773    | 32.16%  |
| Hitachi             | 149      | 217    | 9.55%   |
| Samsung Electronics | 129      | 194    | 8.26%   |
| Toshiba             | 115      | 165    | 7.37%   |
| Maxtor              | 57       | 82     | 3.65%   |
| HGST                | 20       | 25     | 1.28%   |
| Unknown             | 12       | 14     | 0.77%   |
| Fujitsu             | 11       | 13     | 0.7%    |
| ASMT                | 8        | 12     | 0.51%   |
| Intenso             | 4        | 5      | 0.26%   |
| USB3.0              | 3        | 5      | 0.19%   |
| Apple               | 3        | 4      | 0.19%   |
| WD MediaMax         | 2        | 2      | 0.13%   |
| Hewlett-Packard     | 2        | 2      | 0.13%   |
| ExcelStor           | 2        | 2      | 0.13%   |
| SAGE                | 1        | 1      | 0.06%   |
| PHD 3.0             | 1        | 1      | 0.06%   |
| LaCie               | 1        | 4      | 0.06%   |
| Inateck             | 1        | 1      | 0.06%   |
| ICY BOX             | 1        | 1      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| HPE                 | 1        | 4      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 168      | 238    | 22.52%  |
| Kingston            | 107      | 131    | 14.34%  |
| SanDisk             | 71       | 92     | 9.52%   |
| Crucial             | 68       | 104    | 9.12%   |
| WDC                 | 48       | 68     | 6.43%   |
| A-DATA Technology   | 30       | 38     | 4.02%   |
| Intel               | 28       | 43     | 3.75%   |
| China               | 26       | 33     | 3.49%   |
| Patriot             | 24       | 29     | 3.22%   |
| PNY                 | 17       | 24     | 2.28%   |
| OCZ                 | 14       | 19     | 1.88%   |
| Toshiba             | 10       | 16     | 1.34%   |
| Transcend           | 9        | 9      | 1.21%   |
| Intenso             | 9        | 11     | 1.21%   |
| SPCC                | 8        | 14     | 1.07%   |
| Micron Technology   | 7        | 9      | 0.94%   |
| Lexar               | 7        | 7      | 0.94%   |
| KingDian            | 6        | 10     | 0.8%    |
| Apacer              | 6        | 9      | 0.8%    |
| Corsair             | 5        | 5      | 0.67%   |
| Team                | 4        | 6      | 0.54%   |
| SK hynix            | 4        | 4      | 0.54%   |
| Plextor             | 4        | 4      | 0.54%   |
| Goodram             | 4        | 6      | 0.54%   |
| Smartbuy            | 3        | 3      | 0.4%    |
| Mushkin             | 3        | 3      | 0.4%    |
| LITEONIT            | 3        | 3      | 0.4%    |
| Vaseky              | 2        | 2      | 0.27%   |
| TO Exter            | 2        | 3      | 0.27%   |
| TEXTORM             | 2        | 2      | 0.27%   |
| OCZ-VERTEX3         | 2        | 2      | 0.27%   |
| Maxtor              | 2        | 2      | 0.27%   |
| LITEON              | 2        | 2      | 0.27%   |
| Kingmax             | 2        | 3      | 0.27%   |
| KingFast            | 2        | 2      | 0.27%   |
| Integral            | 2        | 2      | 0.27%   |
| Hewlett-Packard     | 2        | 4      | 0.27%   |
| Emtec               | 2        | 2      | 0.27%   |
| Unknown             | 2        | 2      | 0.27%   |
| Wintec              | 1        | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1167     | 2396   | 57.94%  |
| SSD     | 642      | 1000   | 31.88%  |
| NVMe    | 158      | 231    | 7.85%   |
| Unknown | 37       | 54     | 1.84%   |
| MMC     | 10       | 11     | 0.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1428     | 3296   | 83.9%   |
| NVMe | 156      | 228    | 9.17%   |
| SAS  | 108      | 157    | 6.35%   |
| MMC  | 10       | 11     | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1175     | 2093   | 59.1%   |
| 0.51-1.0   | 466      | 729    | 23.44%  |
| 1.01-2.0   | 173      | 291    | 8.7%    |
| 3.01-4.0   | 76       | 121    | 3.82%   |
| 2.01-3.0   | 52       | 92     | 2.62%   |
| 4.01-10.0  | 43       | 67     | 2.16%   |
| 10.01-20.0 | 3        | 3      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 440      | 28.22%  |
| 251-500        | 283      | 18.15%  |
| 501-1000       | 222      | 14.24%  |
| 1001-2000      | 163      | 10.46%  |
| 51-100         | 119      | 7.63%   |
| More than 3000 | 113      | 7.25%   |
| 21-50          | 88       | 5.64%   |
| 2001-3000      | 66       | 4.23%   |
| 1-20           | 53       | 3.4%    |
| Unknown        | 12       | 0.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 533      | 32.78%  |
| 21-50          | 259      | 15.93%  |
| 101-250        | 213      | 13.1%   |
| 51-100         | 202      | 12.42%  |
| 251-500        | 134      | 8.24%   |
| 501-1000       | 114      | 7.01%   |
| 1001-2000      | 77       | 4.74%   |
| More than 3000 | 48       | 2.95%   |
| 2001-3000      | 34       | 2.09%   |
| Unknown        | 12       | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 5        | 5      | 3.31%   |
| Seagate ST3500418AS 500GB         | 3        | 4      | 1.99%   |
| Seagate ST2000DM001-1CH164 2TB    | 3        | 4      | 1.99%   |
| Maxtor STM3160215AS 160GB         | 3        | 3      | 1.99%   |
| Hitachi HDS721050CLA362 500GB     | 3        | 3      | 1.99%   |
| WDC WD4000FYYZ-01UL1B1 4TB        | 2        | 3      | 1.32%   |
| WDC WD3200AAKS-00L9A0 320GB       | 2        | 2      | 1.32%   |
| WDC WD1002FAEX-00Z3A0 1TB         | 2        | 2      | 1.32%   |
| Toshiba DT01ACA100 1TB            | 2        | 2      | 1.32%   |
| Seagate ST3250318AS 250GB         | 2        | 4      | 1.32%   |
| Seagate ST31000528AS 1TB          | 2        | 2      | 1.32%   |
| Seagate ST1000DL002-9TT153 1TB    | 2        | 2      | 1.32%   |
| Samsung Electronics HM321HI 320GB | 2        | 3      | 1.32%   |
| Samsung Electronics HD753LJ 752GB | 2        | 3      | 1.32%   |
| Samsung Electronics HD103SJ 1TB   | 2        | 3      | 1.32%   |
| Samsung Electronics HD103SI 1TB   | 2        | 2      | 1.32%   |
| Samsung Electronics HD081GJ 80GB  | 2        | 2      | 1.32%   |
| Kingston SA400S37240G 240GB SSD   | 2        | 2      | 1.32%   |
| Hitachi HDS721010CLA332 1TB       | 2        | 2      | 1.32%   |
| WDC WDS480G2G0A-00JH30 480GB SSD  | 1        | 1      | 0.66%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 0.66%   |
| WDC WD6400AAKS-22A7B2 640GB       | 1        | 1      | 0.66%   |
| WDC WD6400AAKS-22A7B0 640GB       | 1        | 1      | 0.66%   |
| WDC WD5000LPVX-08V0TT5 500GB      | 1        | 1      | 0.66%   |
| WDC WD5000LPCX-00VHAT0 500GB      | 1        | 1      | 0.66%   |
| WDC WD5000BEVT-22ZAT0 500GB       | 1        | 1      | 0.66%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 0.66%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1        | 1      | 0.66%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 1      | 0.66%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 0.66%   |
| WDC WD5000AAKS-22V1A0 500GB       | 1        | 1      | 0.66%   |
| WDC WD5000AAKS-00A7B0 500GB       | 1        | 1      | 0.66%   |
| WDC WD5000AADS-00S9B0 500GB       | 1        | 1      | 0.66%   |
| WDC WD400EB-00CPF0 40GB           | 1        | 1      | 0.66%   |
| WDC WD3200BEVT-75ZCT1 320GB       | 1        | 1      | 0.66%   |
| WDC WD3200AVJS-63TBA0 320GB       | 1        | 1      | 0.66%   |
| WDC WD3200AAJS-60Z0A0 320GB       | 1        | 1      | 0.66%   |
| WDC WD3200AAJS-08L7A0 320GB       | 1        | 1      | 0.66%   |
| WDC WD30EFRX-68EUZN0 3TB          | 1        | 1      | 0.66%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 2      | 0.66%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 42       | 51     | 29.17%  |
| WDC                 | 41       | 46     | 28.47%  |
| Samsung Electronics | 15       | 22     | 10.42%  |
| Hitachi             | 12       | 17     | 8.33%   |
| Toshiba             | 10       | 11     | 6.94%   |
| Maxtor              | 6        | 6      | 4.17%   |
| Kingston            | 4        | 4      | 2.78%   |
| SK hynix            | 2        | 2      | 1.39%   |
| Crucial             | 2        | 2      | 1.39%   |
| SPCC                | 1        | 1      | 0.69%   |
| KingDian            | 1        | 1      | 0.69%   |
| Intel               | 1        | 2      | 0.69%   |
| ICY BOX             | 1        | 1      | 0.69%   |
| HGST                | 1        | 1      | 0.69%   |
| FORESEE             | 1        | 1      | 0.69%   |
| Corsair             | 1        | 1      | 0.69%   |
| Avant               | 1        | 1      | 0.69%   |
| ASMT                | 1        | 4      | 0.69%   |
| A-DATA Technology   | 1        | 1      | 0.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 42       | 51     | 33.6%   |
| WDC                 | 39       | 44     | 31.2%   |
| Samsung Electronics | 14       | 20     | 11.2%   |
| Hitachi             | 12       | 17     | 9.6%    |
| Toshiba             | 9        | 10     | 7.2%    |
| Maxtor              | 6        | 6      | 4.8%    |
| ICY BOX             | 1        | 1      | 0.8%    |
| HGST                | 1        | 1      | 0.8%    |
| ASMT                | 1        | 4      | 0.8%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 112      | 154    | 86.82%  |
| SSD  | 17       | 21     | 13.18%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD20EARS-00J99B0 2TB         | 1        | 2      | 25%     |
| Toshiba DT01ACA200 2TB           | 1        | 1      | 25%     |
| Seagate ST500DM002-1BC142 500GB  | 1        | 1      | 25%     |
| A-DATA Technology SP800 32GB SSD | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 1        | 2      | 25%     |
| Toshiba           | 1        | 1      | 25%     |
| Seagate           | 1        | 1      | 25%     |
| A-DATA Technology | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1057     | 2618   | 66.23%  |
| Works    | 411      | 894    | 25.75%  |
| Malfunc  | 124      | 175    | 7.77%   |
| Failed   | 4        | 5      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 976      | 53.13%  |
| AMD                              | 357      | 19.43%  |
| Nvidia                           | 100      | 5.44%   |
| Samsung Electronics              | 61       | 3.32%   |
| ASMedia Technology               | 61       | 3.32%   |
| JMicron Technology               | 58       | 3.16%   |
| Marvell Technology Group         | 45       | 2.45%   |
| VIA Technologies                 | 39       | 2.12%   |
| Phison Electronics               | 15       | 0.82%   |
| Kingston Technology Company      | 15       | 0.82%   |
| Silicon Motion                   | 13       | 0.71%   |
| SanDisk                          | 12       | 0.65%   |
| ADATA Technology                 | 11       | 0.6%    |
| Micron/Crucial Technology        | 10       | 0.54%   |
| Silicon Integrated Systems [SiS] | 7        | 0.38%   |
| Silicon Image                    | 6        | 0.33%   |
| Broadcom / LSI                   | 6        | 0.33%   |
| Toshiba America Info Systems     | 5        | 0.27%   |
| Realtek Semiconductor            | 5        | 0.27%   |
| LSI Logic / Symbios Logic        | 5        | 0.27%   |
| Adaptec                          | 5        | 0.27%   |
| Promise Technology               | 4        | 0.22%   |
| Integrated Technology Express    | 4        | 0.22%   |
| KIOXIA                           | 3        | 0.16%   |
| ULi Electronics                  | 2        | 0.11%   |
| SK hynix                         | 2        | 0.11%   |
| Shenzhen Longsys Electronics     | 2        | 0.11%   |
| Micron Technology                | 2        | 0.11%   |
| Seagate Technology               | 1        | 0.05%   |
| OCZ Technology Group             | 1        | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.05%   |
| Lite-On Technology               | 1        | 0.05%   |
| HighPoint Technologies           | 1        | 0.05%   |
| Hewlett-Packard                  | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 188      | 7.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 144      | 5.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 110      | 4.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 93       | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 90       | 3.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 80       | 3.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 70       | 2.74%   |
| Nvidia MCP61 SATA Controller                                                            | 59       | 2.31%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 59       | 2.31%   |
| AMD 400 Series Chipset SATA Controller                                                  | 59       | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 56       | 2.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 51       | 1.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 50       | 1.95%   |
| Intel SATA Controller [RAID mode]                                                       | 49       | 1.92%   |
| Nvidia MCP61 IDE                                                                        | 48       | 1.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 41       | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41       | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 41       | 1.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 38       | 1.49%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 37       | 1.45%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 36       | 1.41%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 35       | 1.37%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 29       | 1.13%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 27       | 1.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 25       | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 24       | 0.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 24       | 0.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 22       | 0.86%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 22       | 0.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 21       | 0.82%   |
| AMD FCH IDE Controller                                                                  | 21       | 0.82%   |
| AMD FCH SATA Controller D                                                               | 20       | 0.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19       | 0.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 18       | 0.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 18       | 0.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 18       | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18       | 0.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 17       | 0.66%   |
| AMD 300 Series Chipset SATA Controller                                                  | 17       | 0.66%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 16       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 955      | 50.13%  |
| IDE  | 678      | 35.59%  |
| NVMe | 157      | 8.24%   |
| RAID | 96       | 5.04%   |
| SAS  | 10       | 0.52%   |
| SCSI | 9        | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1022     | 69.29%  |
| AMD          | 451      | 30.58%  |
| CentaurHauls | 1        | 0.07%   |
| ARM          | 1        | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 25       | 1.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 23       | 1.55%   |
| Intel Pentium 4 CPU 3.00GHz                 | 21       | 1.41%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 19       | 1.28%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 18       | 1.21%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 17       | 1.14%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 16       | 1.08%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 16       | 1.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 14       | 0.94%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 14       | 0.94%   |
| AMD Ryzen 5 3600 6-Core Processor           | 14       | 0.94%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 14       | 0.94%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 13       | 0.87%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 13       | 0.87%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 12       | 0.81%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 11       | 0.74%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 11       | 0.74%   |
| AMD Phenom II X4 955 Processor              | 11       | 0.74%   |
| AMD FX-8350 Eight-Core Processor            | 11       | 0.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 10       | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 10       | 0.67%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 10       | 0.67%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 10       | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 10       | 0.67%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 10       | 0.67%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 9        | 0.61%   |
| Intel Pentium 4 CPU 3.20GHz                 | 9        | 0.61%   |
| Intel Pentium 4 CPU 2.80GHz                 | 9        | 0.61%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 9        | 0.61%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 9        | 0.61%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 9        | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 9        | 0.61%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 9        | 0.61%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 9        | 0.61%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 9        | 0.61%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 9        | 0.61%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 9        | 0.61%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 8        | 0.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 8        | 0.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 8        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 220      | 14.81%  |
| Intel Core i7           | 147      | 9.9%    |
| Intel Core i3           | 120      | 8.08%   |
| Intel Core 2 Duo        | 100      | 6.73%   |
| Intel Xeon              | 69       | 4.65%   |
| AMD Ryzen 5             | 67       | 4.51%   |
| Intel Celeron           | 61       | 4.11%   |
| Intel Pentium 4         | 55       | 3.7%    |
| Intel Core 2 Quad       | 51       | 3.43%   |
| AMD FX                  | 48       | 3.23%   |
| Intel Pentium Dual-Core | 45       | 3.03%   |
| AMD Ryzen 7             | 45       | 3.03%   |
| Intel Pentium           | 43       | 2.9%    |
| AMD Athlon 64 X2        | 34       | 2.29%   |
| AMD Phenom II X4        | 27       | 1.82%   |
| AMD Athlon II X2        | 26       | 1.75%   |
| Intel Pentium Dual      | 25       | 1.68%   |
| Intel Atom              | 23       | 1.55%   |
| AMD Ryzen 9             | 23       | 1.55%   |
| Intel Core 2            | 20       | 1.35%   |
| AMD Ryzen 3             | 18       | 1.21%   |
| AMD A8                  | 18       | 1.21%   |
| Intel Pentium D         | 17       | 1.14%   |
| AMD Athlon 64           | 16       | 1.08%   |
| AMD Sempron             | 15       | 1.01%   |
| AMD A10                 | 15       | 1.01%   |
| Other                   | 13       | 0.88%   |
| Intel Core i9           | 12       | 0.81%   |
| AMD Phenom              | 11       | 0.74%   |
| AMD Athlon II X4        | 11       | 0.74%   |
| AMD Athlon              | 10       | 0.67%   |
| AMD A4                  | 8        | 0.54%   |
| AMD Phenom II X6        | 7        | 0.47%   |
| AMD Ryzen Threadripper  | 6        | 0.4%    |
| AMD Athlon Dual Core    | 6        | 0.4%    |
| AMD A6                  | 6        | 0.4%    |
| Intel Pentium Gold      | 4        | 0.27%   |
| AMD Phenom II X2        | 4        | 0.27%   |
| AMD E1                  | 4        | 0.27%   |
| AMD E                   | 4        | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 573      | 38.64%  |
| 2       | 533      | 35.94%  |
| 1       | 118      | 7.96%   |
| 6       | 110      | 7.42%   |
| 8       | 82       | 5.53%   |
| 12      | 26       | 1.75%   |
| 3       | 17       | 1.15%   |
| 16      | 15       | 1.01%   |
| 10      | 5        | 0.34%   |
| 24      | 1        | 0.07%   |
| 20      | 1        | 0.07%   |
| 14      | 1        | 0.07%   |
| Unknown | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1451     | 98.37%  |
| 2      | 24       | 1.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 850      | 57.47%  |
| 2       | 628      | 42.46%  |
| Unknown | 1        | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1450     | 98.31%  |
| 32-bit         | 24       | 1.63%   |
| Unknown        | 1        | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 269      | 17.62%  |
| 0x1067a    | 120      | 7.86%   |
| 0x306c3    | 106      | 6.94%   |
| 0x206a7    | 99       | 6.48%   |
| 0x306a9    | 94       | 6.16%   |
| 0x506e3    | 45       | 2.95%   |
| 0x010000c8 | 44       | 2.88%   |
| 0x6fd      | 36       | 2.36%   |
| 0x06000852 | 36       | 2.36%   |
| 0x10676    | 31       | 2.03%   |
| 0x0800820d | 31       | 2.03%   |
| 0x6fb      | 30       | 1.96%   |
| 0x08701021 | 30       | 1.96%   |
| 0x106e5    | 24       | 1.57%   |
| 0x906ea    | 23       | 1.51%   |
| 0x906e9    | 23       | 1.51%   |
| 0xa0653    | 20       | 1.31%   |
| 0xf43      | 17       | 1.11%   |
| 0x06001119 | 17       | 1.11%   |
| 0x6f6      | 16       | 1.05%   |
| 0x08108109 | 16       | 1.05%   |
| 0x206d7    | 14       | 0.92%   |
| 0x20655    | 13       | 0.85%   |
| 0x106a5    | 12       | 0.79%   |
| 0x08701013 | 12       | 0.79%   |
| 0x010000db | 12       | 0.79%   |
| 0xf64      | 11       | 0.72%   |
| 0x03000027 | 11       | 0.72%   |
| 0xf65      | 10       | 0.65%   |
| 0xf49      | 10       | 0.65%   |
| 0x906ed    | 10       | 0.65%   |
| 0x306f2    | 10       | 0.65%   |
| 0xf41      | 9        | 0.59%   |
| 0x106ca    | 9        | 0.59%   |
| 0x10677    | 9        | 0.59%   |
| 0x08001137 | 9        | 0.59%   |
| 0x0700010f | 9        | 0.59%   |
| 0x0600063e | 9        | 0.59%   |
| 0x010000dc | 9        | 0.59%   |
| 0x010000c7 | 9        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 170      | 11.46%  |
| Haswell          | 137      | 9.24%   |
| SandyBridge      | 126      | 8.5%    |
| IvyBridge        | 116      | 7.82%   |
| Core             | 103      | 6.95%   |
| K10              | 97       | 6.54%   |
| KabyLake         | 79       | 5.33%   |
| NetBurst         | 78       | 5.26%   |
| K8 Hammer        | 72       | 4.86%   |
| Zen 2            | 61       | 4.11%   |
| Piledriver       | 57       | 3.84%   |
| Skylake          | 53       | 3.57%   |
| Zen+             | 52       | 3.51%   |
| Nehalem          | 39       | 2.63%   |
| Zen              | 36       | 2.43%   |
| Westmere         | 30       | 2.02%   |
| Silvermont       | 26       | 1.75%   |
| CometLake        | 24       | 1.62%   |
| Zen 3            | 20       | 1.35%   |
| Bonnell          | 18       | 1.21%   |
| K10 Llano        | 12       | 0.81%   |
| Bulldozer        | 10       | 0.67%   |
| Jaguar           | 9        | 0.61%   |
| Excavator        | 9        | 0.61%   |
| Unknown          | 9        | 0.61%   |
| Steamroller      | 8        | 0.54%   |
| Goldmont         | 6        | 0.4%    |
| Bobcat           | 6        | 0.4%    |
| Broadwell        | 5        | 0.34%   |
| K6               | 4        | 0.27%   |
| Alderlake Hybrid | 4        | 0.27%   |
| Puma             | 2        | 0.13%   |
| Icelake          | 2        | 0.13%   |
| Goldmont plus    | 2        | 0.13%   |
| Tremont          | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 601      | 38.62%  |
| Intel                            | 539      | 34.64%  |
| AMD                              | 403      | 25.9%   |
| VIA Technologies                 | 5        | 0.32%   |
| Silicon Integrated Systems [SiS] | 4        | 0.26%   |
| Matrox Electronics Systems       | 2        | 0.13%   |
| ASPEED Technology                | 1        | 0.06%   |
| Alliance Semiconductor           | 1        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 69       | 4.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 66       | 4.04%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 59       | 3.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 48       | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 44       | 2.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 43       | 2.63%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 42       | 2.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 34       | 2.08%   |
| Nvidia GT218 [GeForce 210]                                                               | 29       | 1.78%   |
| Intel HD Graphics 530                                                                    | 25       | 1.53%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 24       | 1.47%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 22       | 1.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 21       | 1.29%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 19       | 1.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 19       | 1.16%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 17       | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 16       | 0.98%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 16       | 0.98%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 16       | 0.98%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 15       | 0.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15       | 0.92%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 14       | 0.86%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 14       | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14       | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14       | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 13       | 0.8%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 12       | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12       | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 11       | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 11       | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10       | 0.61%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 10       | 0.61%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 10       | 0.61%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 10       | 0.61%   |
| Intel HD Graphics 630                                                                    | 10       | 0.61%   |
| AMD RS880 [Radeon HD 4250]                                                               | 10       | 0.61%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 9        | 0.55%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 8        | 0.49%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 8        | 0.49%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 8        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| 1 x Nvidia                           | 571      | 38.14%  |
| 1 x Intel                            | 491      | 32.8%   |
| 1 x AMD                              | 344      | 22.98%  |
| 2 x AMD                              | 40       | 2.67%   |
| Intel + Nvidia                       | 12       | 0.8%    |
| Intel + AMD                          | 7        | 0.47%   |
| AMD + Nvidia                         | 6        | 0.4%    |
| 2 x Nvidia                           | 5        | 0.33%   |
| 1 x VIA                              | 5        | 0.33%   |
| 1 x SiS                              | 4        | 0.27%   |
| Other                                | 3        | 0.2%    |
| 1 x Matrox                           | 2        | 0.13%   |
| 3 x AMD                              | 1        | 0.07%   |
| 2 x Intel                            | 1        | 0.07%   |
| 2 x AMD + 1 x Nvidia                 | 1        | 0.07%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1        | 0.07%   |
| Nvidia + ASPEED                      | 1        | 0.07%   |
| Intel + 2 x AMD                      | 1        | 0.07%   |
| Intel + AMD + 1 x Nvidia             | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1080     | 72.29%  |
| Proprietary | 352      | 23.56%  |
| Unknown     | 62       | 4.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 574      | 37.61%  |
| 0.01-0.5   | 308      | 20.18%  |
| 0.51-1.0   | 219      | 14.35%  |
| 1.01-2.0   | 208      | 13.63%  |
| 3.01-4.0   | 105      | 6.88%   |
| 7.01-8.0   | 63       | 4.13%   |
| 5.01-6.0   | 24       | 1.57%   |
| 8.01-16.0  | 12       | 0.79%   |
| 2.01-3.0   | 10       | 0.66%   |
| 4.01-5.0   | 2        | 0.13%   |
| 16.01-24.0 | 1        | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 246      | 16.27%  |
| Dell                    | 154      | 10.19%  |
| Goldstar                | 137      | 9.06%   |
| Hewlett-Packard         | 122      | 8.07%   |
| Acer                    | 108      | 7.14%   |
| AOC                     | 85       | 5.62%   |
| Philips                 | 82       | 5.42%   |
| Ancor Communications    | 56       | 3.7%    |
| BenQ                    | 52       | 3.44%   |
| ViewSonic               | 38       | 2.51%   |
| Unknown                 | 35       | 2.31%   |
| LG Electronics          | 34       | 2.25%   |
| Iiyama                  | 27       | 1.79%   |
| Sony                    | 24       | 1.59%   |
| Fujitsu Siemens         | 20       | 1.32%   |
| NEC Computers           | 19       | 1.26%   |
| Lenovo                  | 17       | 1.12%   |
| HannStar                | 16       | 1.06%   |
| Panasonic               | 15       | 0.99%   |
| Eizo                    | 13       | 0.86%   |
| ASUSTek Computer        | 12       | 0.79%   |
| Medion                  | 11       | 0.73%   |
| Vizio                   | 8        | 0.53%   |
| Vestel Elektronik       | 8        | 0.53%   |
| Idek Iiyama             | 6        | 0.4%    |
| Lenovo Group Limited    | 5        | 0.33%   |
| Haier                   | 5        | 0.33%   |
| Gateway                 | 5        | 0.33%   |
| ___                     | 4        | 0.26%   |
| Sharp                   | 4        | 0.26%   |
| Mitsubishi              | 4        | 0.26%   |
| Hitachi                 | 4        | 0.26%   |
| DENON                   | 4        | 0.26%   |
| Chi Mei Optoelectronics | 4        | 0.26%   |
| Toshiba                 | 3        | 0.2%    |
| Packard Bell            | 3        | 0.2%    |
| ONN                     | 3        | 0.2%    |
| MSI                     | 3        | 0.2%    |
| IOD                     | 3        | 0.2%    |
| FUS                     | 3        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 16       | 0.99%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 10       | 0.62%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 9        | 0.56%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch   | 8        | 0.5%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 6        | 0.37%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 6        | 0.37%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 6        | 0.37%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                      | 6        | 0.37%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 5        | 0.31%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch   | 5        | 0.31%   |
| LG Electronics LCD Monitor LG TV 1920x1080                             | 5        | 0.31%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                       | 5        | 0.31%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 4        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 4        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 4        | 0.25%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 4        | 0.25%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 4        | 0.25%   |
| Philips 170S PHL0839 1280x1024 338x270mm 17.0-inch                     | 4        | 0.25%   |
| Iiyama PL2278H IVM5624 1920x1080 477x268mm 21.5-inch                   | 4        | 0.25%   |
| Dell 1908FP DEL4026 1280x1024 376x301mm 19.0-inch                      | 4        | 0.25%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 3        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 3        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 3        | 0.19%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 3        | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 3        | 0.19%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                     | 3        | 0.19%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                  | 3        | 0.19%   |
| Hewlett-Packard w2007 HWP26A7 1680x1050 433x271mm 20.1-inch            | 3        | 0.19%   |
| Hewlett-Packard P19A HWP3087 1280x1024 338x270mm 17.0-inch             | 3        | 0.19%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 3        | 0.19%   |
| Hewlett-Packard LCD Monitor HWP285A 1920x1080 470x270mm 21.3-inch      | 3        | 0.19%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch            | 3        | 0.19%   |
| Hewlett-Packard L1706 HWP265C 1280x1024 340x270mm 17.1-inch            | 3        | 0.19%   |
| Hewlett-Packard E201 HWP305C 1600x900 443x249mm 20.0-inch              | 3        | 0.19%   |
| Hewlett-Packard 24er HWP3320 1920x1080 527x296mm 23.8-inch             | 3        | 0.19%   |
| Haier HL24XD2 HAR2410 1920x1080 520x290mm 23.4-inch                    | 3        | 0.19%   |
| Goldstar W2241 GSM56B3 1680x1050 474x296mm 22.0-inch                   | 3        | 0.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3        | 0.19%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 0.19%   |
| Goldstar 2D HD TV GSM59C8 1366x768 509x286mm 23.0-inch                 | 3        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 583      | 38.89%  |
| 1280x1024 (SXGA)   | 186      | 12.41%  |
| 1680x1050 (WSXGA+) | 108      | 7.2%    |
| 1440x900 (WXGA+)   | 88       | 5.87%   |
| 1366x768 (WXGA)    | 84       | 5.6%    |
| 3840x2160 (4K)     | 81       | 5.4%    |
| Unknown            | 52       | 3.47%   |
| 1920x1200 (WUXGA)  | 50       | 3.34%   |
| 1600x900 (HD+)     | 50       | 3.34%   |
| 2560x1440 (QHD)    | 47       | 3.14%   |
| 1360x768           | 33       | 2.2%    |
| 1024x768 (XGA)     | 26       | 1.73%   |
| 3840x1080          | 18       | 1.2%    |
| 1920x540           | 9        | 0.6%    |
| 1600x1200          | 9        | 0.6%    |
| 3440x1440          | 7        | 0.47%   |
| 2560x1080          | 7        | 0.47%   |
| 1280x720 (HD)      | 7        | 0.47%   |
| 3200x1080          | 6        | 0.4%    |
| 5120x1440          | 4        | 0.27%   |
| 2288x1287          | 4        | 0.27%   |
| 3840x1200          | 3        | 0.2%    |
| 2048x1152          | 3        | 0.2%    |
| 4480x1440          | 2        | 0.13%   |
| 3286x1080          | 2        | 0.13%   |
| 3200x900           | 2        | 0.13%   |
| 2960x1050          | 2        | 0.13%   |
| 2560x1600          | 2        | 0.13%   |
| 2048x1536          | 2        | 0.13%   |
| 1280x960           | 2        | 0.13%   |
| 1280x800 (WXGA)    | 2        | 0.13%   |
| 800x600            | 1        | 0.07%   |
| 7680x2164          | 1        | 0.07%   |
| 6400x1440          | 1        | 0.07%   |
| 5760x2160          | 1        | 0.07%   |
| 5760x1200          | 1        | 0.07%   |
| 5760x1080          | 1        | 0.07%   |
| 5520x2160          | 1        | 0.07%   |
| 5360x1440          | 1        | 0.07%   |
| 5280x2160          | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 228      | 15.26%  |
| 23      | 164      | 10.98%  |
| 19      | 153      | 10.24%  |
| 24      | 141      | 9.44%   |
| 21      | 138      | 9.24%   |
| 17      | 104      | 6.96%   |
| 27      | 102      | 6.83%   |
| 18      | 91       | 6.09%   |
| 20      | 71       | 4.75%   |
| 22      | 66       | 4.42%   |
| 31      | 50       | 3.35%   |
| 15      | 33       | 2.21%   |
| 84      | 23       | 1.54%   |
| 72      | 16       | 1.07%   |
| 32      | 11       | 0.74%   |
| 40      | 10       | 0.67%   |
| 26      | 9        | 0.6%    |
| 34      | 8        | 0.54%   |
| 28      | 8        | 0.54%   |
| 25      | 8        | 0.54%   |
| 54      | 7        | 0.47%   |
| 52      | 6        | 0.4%    |
| 48      | 5        | 0.33%   |
| 14      | 5        | 0.33%   |
| 12      | 5        | 0.33%   |
| 37      | 4        | 0.27%   |
| 142     | 2        | 0.13%   |
| 65      | 2        | 0.13%   |
| 60      | 2        | 0.13%   |
| 47      | 2        | 0.13%   |
| 46      | 2        | 0.13%   |
| 29      | 2        | 0.13%   |
| 16      | 2        | 0.13%   |
| 13      | 2        | 0.13%   |
| 10      | 2        | 0.13%   |
| 69      | 1        | 0.07%   |
| 63      | 1        | 0.07%   |
| 57      | 1        | 0.07%   |
| 49      | 1        | 0.07%   |
| 41      | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 423      | 28.91%  |
| 501-600        | 385      | 26.32%  |
| Unknown        | 228      | 15.58%  |
| 301-350        | 135      | 9.23%   |
| 351-400        | 95       | 6.49%   |
| 601-700        | 75       | 5.13%   |
| 1501-2000      | 40       | 2.73%   |
| 1001-1500      | 27       | 1.85%   |
| 701-800        | 20       | 1.37%   |
| 801-900        | 16       | 1.09%   |
| 201-300        | 15       | 1.03%   |
| More than 2000 | 2        | 0.14%   |
| 101-200        | 1        | 0.07%   |
| 901-1000       | 1        | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 728      | 51.05%  |
| 16/10   | 226      | 15.85%  |
| Unknown | 214      | 15.01%  |
| 5/4     | 180      | 12.62%  |
| 4/3     | 45       | 3.16%   |
| 21/9    | 12       | 0.84%   |
| 3/2     | 8        | 0.56%   |
| 6/5     | 7        | 0.49%   |
| 1.00    | 3        | 0.21%   |
| 32/9    | 2        | 0.14%   |
| 1.96    | 1        | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 416      | 28.17%  |
| 151-200        | 276      | 18.69%  |
| Unknown        | 228      | 15.44%  |
| 141-150        | 167      | 11.31%  |
| 301-350        | 105      | 7.11%   |
| 351-500        | 75       | 5.08%   |
| 251-300        | 69       | 4.67%   |
| More than 1000 | 64       | 4.33%   |
| 101-110        | 35       | 2.37%   |
| 501-1000       | 23       | 1.56%   |
| 71-80          | 4        | 0.27%   |
| 131-140        | 4        | 0.27%   |
| 81-90          | 2        | 0.14%   |
| 51-60          | 2        | 0.14%   |
| 91-100         | 2        | 0.14%   |
| 61-70          | 1        | 0.07%   |
| 41-50          | 1        | 0.07%   |
| 1-40           | 1        | 0.07%   |
| 121-130        | 1        | 0.07%   |
| 111-120        | 1        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 893      | 63.51%  |
| Unknown       | 228      | 16.22%  |
| 101-120       | 184      | 13.09%  |
| 1-50          | 52       | 3.7%    |
| 121-160       | 43       | 3.06%   |
| 161-240       | 5        | 0.36%   |
| More than 240 | 1        | 0.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1215     | 81%     |
| 2     | 193      | 12.87%  |
| 0     | 78       | 5.2%    |
| 3     | 12       | 0.8%    |
| 4     | 2        | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 857      | 41.24%  |
| Intel                             | 506      | 24.35%  |
| Qualcomm Atheros                  | 143      | 6.88%   |
| Nvidia                            | 83       | 3.99%   |
| Broadcom                          | 79       | 3.8%    |
| Ralink Technology                 | 55       | 2.65%   |
| TP-Link                           | 35       | 1.68%   |
| Ralink                            | 31       | 1.49%   |
| VIA Technologies                  | 28       | 1.35%   |
| Qualcomm Atheros Communications   | 28       | 1.35%   |
| Marvell Technology Group          | 25       | 1.2%    |
| Broadcom Limited                  | 22       | 1.06%   |
| D-Link System                     | 21       | 1.01%   |
| NetGear                           | 19       | 0.91%   |
| D-Link                            | 14       | 0.67%   |
| MediaTek                          | 11       | 0.53%   |
| Huawei Technologies               | 11       | 0.53%   |
| Samsung Electronics               | 9        | 0.43%   |
| ASUSTek Computer                  | 8        | 0.38%   |
| Edimax Technology                 | 7        | 0.34%   |
| Belkin Components                 | 7        | 0.34%   |
| Aquantia                          | 6        | 0.29%   |
| Microsoft                         | 5        | 0.24%   |
| Silicon Integrated Systems [SiS]  | 4        | 0.19%   |
| IMC Networks                      | 4        | 0.19%   |
| HTC (High Tech Computer)          | 4        | 0.19%   |
| Xiaomi                            | 3        | 0.14%   |
| Sitecom Europe                    | 3        | 0.14%   |
| Qualcomm                          | 3        | 0.14%   |
| Linksys                           | 3        | 0.14%   |
| DisplayLink                       | 3        | 0.14%   |
| AVM                               | 3        | 0.14%   |
| ASIX Electronics                  | 3        | 0.14%   |
| 3Com                              | 3        | 0.14%   |
| TRENDnet                          | 2        | 0.1%    |
| LG Electronics                    | 2        | 0.1%    |
| Arduino SA                        | 2        | 0.1%    |
| ZyXEL Communications              | 1        | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.05%   |
| Van Ooijen Technische Informatica | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 646      | 28.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55       | 2.44%   |
| Nvidia MCP61 Ethernet                                             | 52       | 2.31%   |
| Intel I211 Gigabit Network Connection                             | 44       | 1.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38       | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 36       | 1.6%    |
| Intel Wi-Fi 6 AX200                                               | 36       | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 35       | 1.55%   |
| Intel Ethernet Connection (2) I219-V                              | 30       | 1.33%   |
| Intel 82579V Gigabit Network Connection                           | 29       | 1.29%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 27       | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 26       | 1.15%   |
| Ralink MT7601U Wireless Adapter                                   | 25       | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                   | 25       | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 23       | 1.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 21       | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 17       | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 16       | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 16       | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 15       | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 15       | 0.67%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.67%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 14       | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 14       | 0.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13       | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12       | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12       | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 12       | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 0.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 11       | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11       | 0.49%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 11       | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10       | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 10       | 0.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 10       | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 10       | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.4%    |
| Nvidia MCP77 Ethernet                                             | 9        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 152      | 24.8%   |
| Intel                                 | 101      | 16.48%  |
| Qualcomm Atheros                      | 81       | 13.21%  |
| Ralink Technology                     | 55       | 8.97%   |
| TP-Link                               | 35       | 5.71%   |
| Ralink                                | 31       | 5.06%   |
| Qualcomm Atheros Communications       | 28       | 4.57%   |
| Broadcom                              | 24       | 3.92%   |
| NetGear                               | 19       | 3.1%    |
| D-Link System                         | 13       | 2.12%   |
| D-Link                                | 13       | 2.12%   |
| ASUSTek Computer                      | 8        | 1.31%   |
| Edimax Technology                     | 7        | 1.14%   |
| Belkin Components                     | 7        | 1.14%   |
| Microsoft                             | 5        | 0.82%   |
| MediaTek                              | 5        | 0.82%   |
| IMC Networks                          | 4        | 0.65%   |
| Sitecom Europe                        | 3        | 0.49%   |
| Marvell Technology Group              | 3        | 0.49%   |
| Linksys                               | 3        | 0.49%   |
| Broadcom Limited                      | 3        | 0.49%   |
| AVM                                   | 3        | 0.49%   |
| TRENDnet                              | 2        | 0.33%   |
| ZyXEL Communications                  | 1        | 0.16%   |
| Xiaomi                                | 1        | 0.16%   |
| Philips (or NXP)                      | 1        | 0.16%   |
| Gemtek                                | 1        | 0.16%   |
| Dell                                  | 1        | 0.16%   |
| AboCom Systems                        | 1        | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.16%   |
| 3Com                                  | 1        | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 36       | 5.82%   |
| Ralink MT7601U Wireless Adapter                                | 25       | 4.04%   |
| Qualcomm Atheros AR9271 802.11n                                | 25       | 4.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 23       | 3.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 17       | 2.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 16       | 2.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 15       | 2.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 14       | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12       | 1.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 11       | 1.78%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 11       | 1.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 10       | 1.62%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 10       | 1.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 8        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8        | 1.29%   |
| Intel Wireless-AC 9260                                         | 8        | 1.29%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 7        | 1.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 7        | 1.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 7        | 1.13%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 7        | 1.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 6        | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 6        | 0.97%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 6        | 0.97%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 6        | 0.97%   |
| Intel Wireless 7260                                            | 6        | 0.97%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 5        | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 5        | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 5        | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 5        | 0.81%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 5        | 0.81%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 5        | 0.81%   |
| NetGear A6210                                                  | 5        | 0.81%   |
| Intel Wireless 7265                                            | 5        | 0.81%   |
| Intel Wireless 3165                                            | 5        | 0.81%   |
| Intel Wireless 3160                                            | 5        | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5        | 0.81%   |
| TP-Link 802.11n NIC                                            | 4        | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4        | 0.65%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 4        | 0.65%   |
| Realtek RTL8187 Wireless Adapter                               | 4        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 783      | 49.59%  |
| Intel                            | 445      | 28.18%  |
| Nvidia                           | 83       | 5.26%   |
| Qualcomm Atheros                 | 72       | 4.56%   |
| Broadcom                         | 56       | 3.55%   |
| VIA Technologies                 | 28       | 1.77%   |
| Marvell Technology Group         | 22       | 1.39%   |
| Broadcom Limited                 | 19       | 1.2%    |
| Samsung Electronics              | 9        | 0.57%   |
| Huawei Technologies              | 8        | 0.51%   |
| D-Link System                    | 8        | 0.51%   |
| MediaTek                         | 6        | 0.38%   |
| Aquantia                         | 6        | 0.38%   |
| Silicon Integrated Systems [SiS] | 4        | 0.25%   |
| HTC (High Tech Computer)         | 4        | 0.25%   |
| Qualcomm                         | 3        | 0.19%   |
| DisplayLink                      | 3        | 0.19%   |
| ASIX Electronics                 | 3        | 0.19%   |
| Xiaomi                           | 2        | 0.13%   |
| LG Electronics                   | 2        | 0.13%   |
| 3Com                             | 2        | 0.13%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.06%   |
| T & A Mobile Phones              | 1        | 0.06%   |
| National Semiconductor           | 1        | 0.06%   |
| Mellanox Technologies            | 1        | 0.06%   |
| Lenovo                           | 1        | 0.06%   |
| JMicron Technology               | 1        | 0.06%   |
| Hangzhou Silan Microelectronics  | 1        | 0.06%   |
| D-Link                           | 1        | 0.06%   |
| Apple                            | 1        | 0.06%   |
| ADMtek                           | 1        | 0.06%   |
| Accton Technology                | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 646      | 39.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 4.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55       | 3.4%    |
| Nvidia MCP61 Ethernet                                             | 52       | 3.22%   |
| Intel I211 Gigabit Network Connection                             | 44       | 2.72%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38       | 2.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 36       | 2.23%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 30       | 1.86%   |
| Intel 82579V Gigabit Network Connection                           | 29       | 1.79%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 27       | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 26       | 1.61%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 21       | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 16       | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 15       | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 14       | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13       | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12       | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 12       | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11       | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10       | 0.62%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 10       | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.56%   |
| Nvidia MCP77 Ethernet                                             | 9        | 0.56%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 9        | 0.56%   |
| Intel 82578DC Gigabit Network Connection                          | 8        | 0.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 8        | 0.5%    |
| Intel 82562V-2 10/100 Network Connection                          | 7        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 7        | 0.43%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 6        | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6        | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6        | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6        | 0.37%   |
| Nvidia MCP51 Ethernet Controller                                  | 6        | 0.37%   |
| Intel I210 Gigabit Network Connection                             | 6        | 0.37%   |
| Intel Ethernet Controller I225-V                                  | 6        | 0.37%   |
| Intel 82578DM Gigabit Network Connection                          | 6        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1459     | 71.34%  |
| WiFi     | 566      | 27.68%  |
| Modem    | 16       | 0.78%   |
| Unknown  | 4        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1154     | 75.67%  |
| WiFi     | 371      | 24.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1086     | 73.18%  |
| 2     | 330      | 22.24%  |
| 3     | 41       | 2.76%   |
| 0     | 19       | 1.28%   |
| 4     | 5        | 0.34%   |
| 5     | 2        | 0.13%   |
| 10    | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1270     | 84.84%  |
| Yes  | 227      | 15.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 91       | 32.97%  |
| Cambridge Silicon Radio         | 79       | 28.62%  |
| Broadcom                        | 29       | 10.51%  |
| Qualcomm Atheros Communications | 18       | 6.52%   |
| Realtek Semiconductor           | 14       | 5.07%   |
| ASUSTek Computer                | 11       | 3.99%   |
| IMC Networks                    | 9        | 3.26%   |
| Integrated System Solution      | 5        | 1.81%   |
| Apple                           | 4        | 1.45%   |
| Lite-On Technology              | 3        | 1.09%   |
| MediaTek                        | 2        | 0.72%   |
| Fujitsu                         | 2        | 0.72%   |
| Edimax Technology               | 2        | 0.72%   |
| TP-Link                         | 1        | 0.36%   |
| Sitecom Europe                  | 1        | 0.36%   |
| Ralink                          | 1        | 0.36%   |
| Logitech                        | 1        | 0.36%   |
| Dell                            | 1        | 0.36%   |
| Conwise Technology              | 1        | 0.36%   |
| Unknown                         | 1        | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 79       | 28.62%  |
| Intel AX200 Bluetooth                                     | 38       | 13.77%  |
| Intel Bluetooth wireless interface                        | 23       | 8.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 15       | 5.43%   |
| Intel Wireless-AC 3168 Bluetooth                          | 13       | 4.71%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 8        | 2.9%    |
| Realtek Bluetooth Radio                                   | 7        | 2.54%   |
| Qualcomm Atheros  Bluetooth Device                        | 7        | 2.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 6        | 2.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 6        | 2.17%   |
| Integrated System Solution Bluetooth Device               | 5        | 1.81%   |
| Realtek  Bluetooth 4.2 Adapter                            | 4        | 1.45%   |
| IMC Networks Bluetooth Radio                              | 4        | 1.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 4        | 1.45%   |
| Realtek RTL8821A Bluetooth                                | 3        | 1.09%   |
| Lite-On Bluetooth Device                                  | 3        | 1.09%   |
| Intel AX210 Bluetooth                                     | 3        | 1.09%   |
| IMC Networks BCM20702A0                                   | 3        | 1.09%   |
| Broadcom BCM2045 Bluetooth                                | 3        | 1.09%   |
| Broadcom ANYCOM Blue USB-UHE 200/250                      | 3        | 1.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 3        | 1.09%   |
| MediaTek Wireless_Device                                  | 2        | 0.72%   |
| Intel AX201 Bluetooth                                     | 2        | 0.72%   |
| IMC Networks Bluetooth Device                             | 2        | 0.72%   |
| Fujitsu Bluetooth Device                                  | 2        | 0.72%   |
| Broadcom BCM2035 Bluetooth dongle                         | 2        | 0.72%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 2        | 0.72%   |
| ASUS BCM20702A0                                           | 2        | 0.72%   |
| TP-Link UB500 Adapter                                     | 1        | 0.36%   |
| Sitecom Europe Sitecom bluetooth2.0 class 2 dongle CN-512 | 1        | 0.36%   |
| Ralink RT3290 Bluetooth                                   | 1        | 0.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1        | 0.36%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 1        | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 1        | 0.36%   |
| Logitech BT Mini-Receiver (HCI mode)                      | 1        | 0.36%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter   | 1        | 0.36%   |
| Edimax Bluetooth Adapter                                  | 1        | 0.36%   |
| Dell Wireless 365 Bluetooth                               | 1        | 0.36%   |
| Conwise CW6622                                            | 1        | 0.36%   |
| Broadcom HP Bluetooth Module                              | 1        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 950      | 41.47%  |
| Nvidia                               | 530      | 23.13%  |
| AMD                                  | 483      | 21.08%  |
| Creative Labs                        | 50       | 2.18%   |
| C-Media Electronics                  | 47       | 2.05%   |
| VIA Technologies                     | 34       | 1.48%   |
| Texas Instruments                    | 19       | 0.83%   |
| Logitech                             | 14       | 0.61%   |
| Yamaha                               | 9        | 0.39%   |
| M-Audio                              | 9        | 0.39%   |
| Focusrite-Novation                   | 9        | 0.39%   |
| GN Netcom                            | 8        | 0.35%   |
| Creative Technology                  | 8        | 0.35%   |
| Silicon Integrated Systems [SiS]     | 7        | 0.31%   |
| JMTek                                | 6        | 0.26%   |
| SAVITECH                             | 4        | 0.17%   |
| Plantronics                          | 4        | 0.17%   |
| Generalplus Technology               | 4        | 0.17%   |
| Ensoniq                              | 4        | 0.17%   |
| Sennheiser Communications            | 3        | 0.13%   |
| Kingston Technology                  | 3        | 0.13%   |
| EGO SYStems                          | 3        | 0.13%   |
| DigiTech                             | 3        | 0.13%   |
| BEHRINGER International              | 3        | 0.13%   |
| AKAI Professional M.I.               | 3        | 0.13%   |
| Xilinx                               | 2        | 0.09%   |
| Unknown                              | 2        | 0.09%   |
| ULi Electronics                      | 2        | 0.09%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.09%   |
| TerraTec Electronic                  | 2        | 0.09%   |
| Tenx Technology                      | 2        | 0.09%   |
| TEAC                                 | 2        | 0.09%   |
| Samson Technologies                  | 2        | 0.09%   |
| Lenovo                               | 2        | 0.09%   |
| FiiO Electronics Technology          | 2        | 0.09%   |
| ESI Audiotechnik                     | 2        | 0.09%   |
| Elite Silicon                        | 2        | 0.09%   |
| Digidesign                           | 2        | 0.09%   |
| Corsair                              | 2        | 0.09%   |
| Blue Microphones                     | 2        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 152      | 5.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 130      | 5.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 113      | 4.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 97       | 3.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 86       | 3.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 73       | 2.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 63       | 2.43%   |
| AMD Starship/Matisse HD Audio Controller                                          | 61       | 2.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 58       | 2.24%   |
| Nvidia MCP61 High Definition Audio                                                | 56       | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 54       | 2.08%   |
| AMD FCH Azalia Controller                                                         | 53       | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 52       | 2.01%   |
| Nvidia High Definition Audio Controller                                           | 47       | 1.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 46       | 1.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 45       | 1.74%   |
| AMD Family 17h/19h HD Audio Controller                                            | 43       | 1.66%   |
| Intel 200 Series PCH HD Audio                                                     | 42       | 1.62%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 41       | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 39       | 1.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 38       | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                                     | 37       | 1.43%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 36       | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                        | 29       | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 29       | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                                     | 25       | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 24       | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                                | 23       | 0.89%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 23       | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 22       | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                | 22       | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 22       | 0.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 20       | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                                     | 17       | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                                     | 16       | 0.62%   |
| Intel Comet Lake PCH-V cAVS                                                       | 16       | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                     | 15       | 0.58%   |
| Nvidia GM206 High Definition Audio Controller                                     | 15       | 0.58%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 15       | 0.58%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 15       | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 141      | 21.23%  |
| Kingston                     | 98       | 14.76%  |
| Samsung Electronics          | 73       | 10.99%  |
| SK hynix                     | 72       | 10.84%  |
| Crucial                      | 58       | 8.73%   |
| Corsair                      | 58       | 8.73%   |
| G.Skill                      | 38       | 5.72%   |
| Micron Technology            | 30       | 4.52%   |
| Nanya Technology             | 14       | 2.11%   |
| Elpida                       | 11       | 1.66%   |
| A-DATA Technology            | 10       | 1.51%   |
| Transcend                    | 9        | 1.36%   |
| Team                         | 7        | 1.05%   |
| Ramaxel Technology           | 5        | 0.75%   |
| Patriot                      | 3        | 0.45%   |
| GOODRAM                      | 3        | 0.45%   |
| Unknown                      | 3        | 0.45%   |
| Unifosa                      | 2        | 0.3%    |
| GeIL                         | 2        | 0.3%    |
| Avant                        | 2        | 0.3%    |
| Apacer                       | 2        | 0.3%    |
| Walton Chaintech             | 1        | 0.15%   |
| Unknown (ABCD)               | 1        | 0.15%   |
| Unknown (0x7FA8000000000000) | 1        | 0.15%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.15%   |
| Toshiba                      | 1        | 0.15%   |
| Smart                        | 1        | 0.15%   |
| Sesame                       | 1        | 0.15%   |
| Reboto                       | 1        | 0.15%   |
| Qimonda                      | 1        | 0.15%   |
| Positivo                     | 1        | 0.15%   |
| PNY                          | 1        | 0.15%   |
| Netac                        | 1        | 0.15%   |
| Neo Forza                    | 1        | 0.15%   |
| Hikvision                    | 1        | 0.15%   |
| HBS                          | 1        | 0.15%   |
| GLOWAY                       | 1        | 0.15%   |
| G-Alantic                    | 1        | 0.15%   |
| EVGA                         | 1        | 0.15%   |
| CSX                          | 1        | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s   | 15       | 2.05%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 11       | 1.5%    |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 11       | 1.5%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 7        | 0.95%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 6        | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 6        | 0.82%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s            | 6        | 0.82%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 6        | 0.82%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 6        | 0.82%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 5        | 0.68%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 5        | 0.68%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s  | 5        | 0.68%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s   | 5        | 0.68%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 5        | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s              | 4        | 0.55%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 4        | 0.55%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 4        | 0.55%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s  | 4        | 0.55%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 4        | 0.55%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 4        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 3        | 0.41%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 3        | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s             | 3        | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR2                     | 3        | 0.41%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s   | 3        | 0.41%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s     | 3        | 0.41%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 3        | 0.41%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 3        | 0.41%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s     | 3        | 0.41%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s      | 3        | 0.41%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s     | 3        | 0.41%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s   | 3        | 0.41%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s   | 3        | 0.41%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 3        | 0.41%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 3        | 0.41%   |
| Unknown                                                 | 3        | 0.41%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 2        | 0.27%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 2        | 0.27%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                 | 2        | 0.27%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 2        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 215      | 36.44%  |
| DDR4    | 207      | 35.08%  |
| DDR2    | 61       | 10.34%  |
| SDRAM   | 48       | 8.14%   |
| Unknown | 41       | 6.95%   |
| DDR     | 14       | 2.37%   |
| LPDDR4  | 3        | 0.51%   |
| DDR5    | 1        | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 538      | 93.73%  |
| SODIMM  | 34       | 5.92%   |
| FB-DIMM | 2        | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 178      | 28.03%  |
| 8192  | 166      | 26.14%  |
| 2048  | 144      | 22.68%  |
| 16384 | 84       | 13.23%  |
| 1024  | 46       | 7.24%   |
| 32768 | 9        | 1.42%   |
| 512   | 8        | 1.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 124      | 19.38%  |
| 1333    | 75       | 11.72%  |
| 800     | 54       | 8.44%   |
| 2667    | 49       | 7.66%   |
| 2400    | 38       | 5.94%   |
| Unknown | 36       | 5.63%   |
| 3200    | 35       | 5.47%   |
| 3600    | 27       | 4.22%   |
| 2133    | 25       | 3.91%   |
| 667     | 20       | 3.13%   |
| 1867    | 16       | 2.5%    |
| 3000    | 14       | 2.19%   |
| 2666    | 13       | 2.03%   |
| 1866    | 13       | 2.03%   |
| 1800    | 11       | 1.72%   |
| 1066    | 11       | 1.72%   |
| 533     | 7        | 1.09%   |
| 3400    | 5        | 0.78%   |
| 400     | 5        | 0.78%   |
| 49926   | 4        | 0.63%   |
| 3800    | 4        | 0.63%   |
| 2733    | 4        | 0.63%   |
| 2200    | 4        | 0.63%   |
| 2048    | 4        | 0.63%   |
| 2000    | 4        | 0.63%   |
| 1067    | 4        | 0.63%   |
| 2800    | 3        | 0.47%   |
| 2448    | 3        | 0.47%   |
| 1334    | 3        | 0.47%   |
| 3466    | 2        | 0.31%   |
| 3266    | 2        | 0.31%   |
| 2187    | 2        | 0.31%   |
| 1648    | 2        | 0.31%   |
| 1639    | 2        | 0.31%   |
| 333     | 2        | 0.31%   |
| 5354    | 1        | 0.16%   |
| 4800    | 1        | 0.16%   |
| 4333    | 1        | 0.16%   |
| 3866    | 1        | 0.16%   |
| 3733    | 1        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 42       | 42%     |
| Brother Industries  | 22       | 22%     |
| Canon               | 14       | 14%     |
| Samsung Electronics | 10       | 10%     |
| Zebra               | 4        | 4%      |
| Seiko Epson         | 4        | 4%      |
| QinHeng Electronics | 2        | 2%      |
| Pantum              | 1        | 1%      |
| Dymo-CoStar         | 1        | 1%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HP LaserJet 400 M401n                                                 | 4        | 4%      |
| Zebra ZP 450 Printer                                                  | 3        | 3%      |
| HP LaserJet P1005                                                     | 3        | 3%      |
| HP ENVY 4520 series                                                   | 3        | 3%      |
| Brother HL-5370DW series                                              | 3        | 3%      |
| QinHeng CH340S                                                        | 2        | 2%      |
| HP OfficeJet Pro 7730 series                                          | 2        | 2%      |
| HP LaserJet P1006                                                     | 2        | 2%      |
| HP Deskjet 3050A                                                      | 2        | 2%      |
| Canon PIXMA MX530 Series                                              | 2        | 2%      |
| Brother HL-5340 series                                                | 2        | 2%      |
| Brother HL-2270DW Laser Printer                                       | 2        | 2%      |
| Zebra ZTC ZP 500 (ZPL)                                                | 1        | 1%      |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1        | 1%      |
| Seiko Epson L3160 Series                                              | 1        | 1%      |
| Seiko Epson L220 Series                                               | 1        | 1%      |
| Seiko Epson ET-2600 Series                                            | 1        | 1%      |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1        | 1%      |
| Samsung SF-760 Series                                                 | 1        | 1%      |
| Samsung SCX-4200 series                                               | 1        | 1%      |
| Samsung SCX-4100 Scanner                                              | 1        | 1%      |
| Samsung SCX-3400 Series                                               | 1        | 1%      |
| Samsung ML-2525W Series                                               | 1        | 1%      |
| Samsung ML-1740 Printer                                               | 1        | 1%      |
| Samsung M2070 Series                                                  | 1        | 1%      |
| Samsung M2020 Series                                                  | 1        | 1%      |
| Samsung C48x Series                                                   | 1        | 1%      |
| Pantum P2000                                                          | 1        | 1%      |
| HP OfficeJet Pro 9010 series                                          | 1        | 1%      |
| HP Officejet Pro 6230                                                 | 1        | 1%      |
| HP Officejet 6600                                                     | 1        | 1%      |
| HP Officejet 2620 series                                              | 1        | 1%      |
| HP LaserJet P2055 series                                              | 1        | 1%      |
| HP LaserJet P2015 series                                              | 1        | 1%      |
| HP LaserJet M14-M17                                                   | 1        | 1%      |
| HP LaserJet M101-M106                                                 | 1        | 1%      |
| HP LaserJet CP 1025                                                   | 1        | 1%      |
| HP LaserJet 1320                                                      | 1        | 1%      |
| HP LaserJet 1150                                                      | 1        | 1%      |
| HP LaserJet 1018                                                      | 1        | 1%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 16       | 66.67%  |
| Seiko Epson     | 4        | 16.67%  |
| Hewlett-Packard | 4        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3        | 12.5%   |
| Canon CanoScan LIDE 25                                      | 2        | 8.33%   |
| Canon CanoScan LiDE 210                                     | 2        | 8.33%   |
| Canon CanoScan LiDE 120                                     | 2        | 8.33%   |
| Canon CanoScan LiDE 110                                     | 2        | 8.33%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1        | 4.17%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1        | 4.17%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1        | 4.17%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1        | 4.17%   |
| HP ScanJet 82x0C                                            | 1        | 4.17%   |
| HP ScanJet 5590                                             | 1        | 4.17%   |
| HP Scanjet 200                                              | 1        | 4.17%   |
| HP PSC 1200                                                 | 1        | 4.17%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1        | 4.17%   |
| Canon CanoScan N650U/N656U                                  | 1        | 4.17%   |
| Canon CanoScan LiDE 90                                      | 1        | 4.17%   |
| Canon CanoScan LiDE 220                                     | 1        | 4.17%   |
| Canon CanoScan LiDE 200                                     | 1        | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 79       | 37.09%  |
| Microdia                      | 23       | 10.8%   |
| Microsoft                     | 15       | 7.04%   |
| Realtek Semiconductor         | 7        | 3.29%   |
| Z-Star Microelectronics       | 6        | 2.82%   |
| Sunplus Innovation Technology | 6        | 2.82%   |
| Samsung Electronics           | 6        | 2.82%   |
| Generalplus Technology        | 6        | 2.82%   |
| Chicony Electronics           | 6        | 2.82%   |
| Apple                         | 5        | 2.35%   |
| MacroSilicon                  | 4        | 1.88%   |
| KYE Systems (Mouse Systems)   | 4        | 1.88%   |
| Jieli Technology              | 4        | 1.88%   |
| Cubeternet                    | 4        | 1.88%   |
| Creative Technology           | 4        | 1.88%   |
| Trust                         | 3        | 1.41%   |
| GEMBIRD                       | 3        | 1.41%   |
| ARC International             | 3        | 1.41%   |
| Razer USA                     | 2        | 0.94%   |
| Linux Foundation              | 2        | 0.94%   |
| Hewlett-Packard               | 2        | 0.94%   |
| Aveo Technology               | 2        | 0.94%   |
| Arkmicro Technologies         | 2        | 0.94%   |
| Xiaomi                        | 1        | 0.47%   |
| USB3.0 HD Audio Capture       | 1        | 0.47%   |
| Sunplus IT                    | 1        | 0.47%   |
| PrehKeyTec                    | 1        | 0.47%   |
| Pixart Imaging                | 1        | 0.47%   |
| OPPO Electronics              | 1        | 0.47%   |
| OmniVision Technologies       | 1        | 0.47%   |
| Omnivision                    | 1        | 0.47%   |
| Nintendo                      | 1        | 0.47%   |
| Mimaki Engineering            | 1        | 0.47%   |
| IMC Networks                  | 1        | 0.47%   |
| Huawei Technologies           | 1        | 0.47%   |
| Guillemot                     | 1        | 0.47%   |
| Genesys Logic                 | 1        | 0.47%   |
| A4Tech                        | 1        | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech Webcam C270                        | 21       | 9.86%   |
| Logitech HD Pro Webcam C920                 | 14       | 6.57%   |
| Samsung Galaxy A5 (MTP)                     | 6        | 2.82%   |
| Microdia Webcam Vitade AF                   | 6        | 2.82%   |
| Logitech C922 Pro Stream Webcam             | 6        | 2.82%   |
| Apple iPhone5/5C/5S/6                       | 5        | 2.35%   |
| Microdia USB 2.0 Camera                     | 4        | 1.88%   |
| Microdia Sonix USB 2.0 Camera               | 4        | 1.88%   |
| MacroSilicon USB Video                      | 4        | 1.88%   |
| Logitech HD Webcam C525                     | 4        | 1.88%   |
| Jieli USB PHY 2.0                           | 4        | 1.88%   |
| Generalplus 808 Camera #9 (web-cam mode)    | 4        | 1.88%   |
| Z-Star Venus USB2.0 Camera                  | 3        | 1.41%   |
| Trust USB Camera                            | 3        | 1.41%   |
| Realtek Full HD webcam                      | 3        | 1.41%   |
| Microdia Camera                             | 3        | 1.41%   |
| Logitech Webcam Pro 9000                    | 3        | 1.41%   |
| Logitech Webcam C170                        | 3        | 1.41%   |
| Logitech QuickCam Pro 9000                  | 3        | 1.41%   |
| Logitech HD Webcam B910                     | 3        | 1.41%   |
| ARC International Camera                    | 3        | 1.41%   |
| Z-Star Vimicro USB Camera (Altair)          | 2        | 0.94%   |
| Sunplus NexiGo N930AF FHD Webcam            | 2        | 0.94%   |
| Microsoft MicrosoftÂ LifeCam Studio        | 2        | 0.94%   |
| Microsoft LifeCam VX-5000                   | 2        | 0.94%   |
| Microsoft LifeCam VX-2000                   | 2        | 0.94%   |
| Microsoft LifeCam HD-3000                   | 2        | 0.94%   |
| Microsoft LifeCam Cinema                    | 2        | 0.94%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 2        | 0.94%   |
| Logitech Webcam C300                        | 2        | 0.94%   |
| Logitech Webcam B500                        | 2        | 0.94%   |
| Logitech QuickCam Pro 5000                  | 2        | 0.94%   |
| Logitech Logitech Webcam C160               | 2        | 0.94%   |
| Logitech HD Webcam C615                     | 2        | 0.94%   |
| Logitech B525 HD Webcam                     | 2        | 0.94%   |
| Linux Foundation EEM Gadget                 | 2        | 0.94%   |
| Generalplus GENERAL WEBCAM                  | 2        | 0.94%   |
| GEMBIRD USB2.0 PC CAMERA                    | 2        | 0.94%   |
| Cubeternet GL-UPC822 UVC WebCam             | 2        | 0.94%   |
| Creative VF0610 Live! Cam Socialize HD      | 2        | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| OmniKey                   | 2        | 18.18%  |
| Gemalto (was Gemplus)     | 2        | 18.18%  |
| Reiner SCT Kartensysteme  | 1        | 9.09%   |
| Lenovo                    | 1        | 9.09%   |
| In Focus Systems          | 1        | 9.09%   |
| Fujitsu Siemens Computers | 1        | 9.09%   |
| Chicony Electronics       | 1        | 9.09%   |
| Cherry                    | 1        | 9.09%   |
| Alcor Micro               | 1        | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                          | 2        | 18.18%  |
| Reiner SCT Kartensysteme cyberJack one               | 1        | 9.09%   |
| Lenovo Smartcard Keyboard                            | 1        | 9.09%   |
| In Focus Systems EMV Smartcard Reader                | 1        | 9.09%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 1        | 9.09%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader     | 1        | 9.09%   |
| Fujitsu Siemens Computers SmartCard Reader 2A        | 1        | 9.09%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 9.09%   |
| Cherry SmartTerminal XX44                            | 1        | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                  | 1        | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1290     | 85.77%  |
| 1     | 173      | 11.5%   |
| 2     | 28       | 1.86%   |
| 3     | 8        | 0.53%   |
| 4     | 4        | 0.27%   |
| 5     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 88       | 36.97%  |
| Net/wireless             | 51       | 21.43%  |
| Communication controller | 27       | 11.34%  |
| Unassigned class         | 13       | 5.46%   |
| Sound                    | 13       | 5.46%   |
| Multimedia controller    | 12       | 5.04%   |
| Chipcard                 | 8        | 3.36%   |
| Camera                   | 8        | 3.36%   |
| Network                  | 3        | 1.26%   |
| Modem                    | 3        | 1.26%   |
| Card reader              | 3        | 1.26%   |
| Storage/raid             | 2        | 0.84%   |
| Net/ethernet             | 2        | 0.84%   |
| Video                    | 1        | 0.42%   |
| Storage/ide              | 1        | 0.42%   |
| Fingerprint reader       | 1        | 0.42%   |
| Dvb card                 | 1        | 0.42%   |
| Bluetooth                | 1        | 0.42%   |

