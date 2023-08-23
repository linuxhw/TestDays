EndeavourOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

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

Total: 500

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 08NPPY A00                  | [bdc11616d7](https://linux-hardware.org/?probe=bdc11616d7) | Aug 08, 2023 |
| ASRock        | B650 PG Lightning           | [bc55c09547](https://linux-hardware.org/?probe=bc55c09547) | Aug 06, 2023 |
| MSI           | X470 GAMING PLUS            | [0e79a19ed6](https://linux-hardware.org/?probe=0e79a19ed6) | Aug 06, 2023 |
| ASRock        | X570 Taichi                 | [34e27f60e0](https://linux-hardware.org/?probe=34e27f60e0) | Aug 05, 2023 |
| Gigabyte      | H77-DS3H                    | [4c677637c2](https://linux-hardware.org/?probe=4c677637c2) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [a08886d394](https://linux-hardware.org/?probe=a08886d394) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fd9503645f](https://linux-hardware.org/?probe=fd9503645f) | Aug 01, 2023 |
| MSI           | X470 GAMING PLUS            | [9e892c6bc7](https://linux-hardware.org/?probe=9e892c6bc7) | Aug 01, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [13a4427208](https://linux-hardware.org/?probe=13a4427208) | Jul 31, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [351ebe5f4f](https://linux-hardware.org/?probe=351ebe5f4f) | Jul 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a179c222ea](https://linux-hardware.org/?probe=a179c222ea) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [32fbe34ce0](https://linux-hardware.org/?probe=32fbe34ce0) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [25aef4eda4](https://linux-hardware.org/?probe=25aef4eda4) | Jul 18, 2023 |
| MSI           | B350 TOMAHAWK               | [d589d40102](https://linux-hardware.org/?probe=d589d40102) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | [7e0ff09c1f](https://linux-hardware.org/?probe=7e0ff09c1f) | Jul 15, 2023 |
| MSI           | B150M ECO                   | [84601cd9dc](https://linux-hardware.org/?probe=84601cd9dc) | Jul 14, 2023 |
| Gigabyte      | B550 VISION D-P             | [160af9ddfb](https://linux-hardware.org/?probe=160af9ddfb) | Jul 09, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [33e4bac631](https://linux-hardware.org/?probe=33e4bac631) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [6df7cc5145](https://linux-hardware.org/?probe=6df7cc5145) | Jul 02, 2023 |
| Daten Tecn... | DH110MXV                    | [83dd07d2a7](https://linux-hardware.org/?probe=83dd07d2a7) | Jul 01, 2023 |
| Gigabyte      | P55A-UD3                    | [1ab74730be](https://linux-hardware.org/?probe=1ab74730be) | Jul 01, 2023 |
| ASRock        | B450M Pro4                  | [b5f1dc88df](https://linux-hardware.org/?probe=b5f1dc88df) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [916b60f6f7](https://linux-hardware.org/?probe=916b60f6f7) | Jun 30, 2023 |
| MSI           | A320M PRO-VH                | [1a84c61bd4](https://linux-hardware.org/?probe=1a84c61bd4) | Jun 27, 2023 |
| MSI           | X570-A PRO                  | [f664b455eb](https://linux-hardware.org/?probe=f664b455eb) | Jun 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| MSI           | B450M PRO-VDH               | [ed8ee7af2c](https://linux-hardware.org/?probe=ed8ee7af2c) | Jun 19, 2023 |
| ASRock        | Z77 Extreme4                | [78207fbf49](https://linux-hardware.org/?probe=78207fbf49) | Jun 19, 2023 |
| MSI           | B350M MORTAR                | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| MSI           | B450 TOMAHAWK               | [e8ed28dba0](https://linux-hardware.org/?probe=e8ed28dba0) | Jun 14, 2023 |
| MSI           | B450 TOMAHAWK               | [507d8cc765](https://linux-hardware.org/?probe=507d8cc765) | Jun 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c433d533f0](https://linux-hardware.org/?probe=c433d533f0) | Jun 11, 2023 |
| ASUSTek       | CM6850                      | [33579719ed](https://linux-hardware.org/?probe=33579719ed) | Jun 11, 2023 |
| Dell          | 0DWPVW A00                  | [ffad802816](https://linux-hardware.org/?probe=ffad802816) | Jun 10, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| Dell          | 0D24M8 A00                  | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| ASUSTek       | H97-PRO                     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| MSI           | MEG X670E ACE               | [8bc281486e](https://linux-hardware.org/?probe=8bc281486e) | May 31, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| HP            | 158A                        | [a605d12e2d](https://linux-hardware.org/?probe=a605d12e2d) | May 23, 2023 |
| HP            | 158A                        | [a1770c45b0](https://linux-hardware.org/?probe=a1770c45b0) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| HP            | 18E4                        | [5601900c8b](https://linux-hardware.org/?probe=5601900c8b) | May 22, 2023 |
| HP            | 18E4                        | [7560196205](https://linux-hardware.org/?probe=7560196205) | May 16, 2023 |
| HP            | 18E4                        | [4dc91feab7](https://linux-hardware.org/?probe=4dc91feab7) | May 14, 2023 |
| Daten Tecn... | DH110MXV                    | [4fd655c0aa](https://linux-hardware.org/?probe=4fd655c0aa) | May 13, 2023 |
| MSI           | X470 GAMING PLUS            | [bc0dacd119](https://linux-hardware.org/?probe=bc0dacd119) | May 13, 2023 |
| HP            | 18E4                        | [2a528dc758](https://linux-hardware.org/?probe=2a528dc758) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7a1ffd8bd2](https://linux-hardware.org/?probe=7a1ffd8bd2) | May 07, 2023 |
| HP            | 1589                        | [dd3e55b423](https://linux-hardware.org/?probe=dd3e55b423) | May 05, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [8ff62a5045](https://linux-hardware.org/?probe=8ff62a5045) | May 05, 2023 |
| HP            | 18E4                        | [d1344e36dd](https://linux-hardware.org/?probe=d1344e36dd) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Daten Tecn... | DH110MXV                    | [96402fa64a](https://linux-hardware.org/?probe=96402fa64a) | May 01, 2023 |
| Gigabyte      | P55A-UD3                    | [07324ae678](https://linux-hardware.org/?probe=07324ae678) | May 01, 2023 |
| ASRock        | B450M Pro4                  | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| HP            | 18E4                        | [da858ea464](https://linux-hardware.org/?probe=da858ea464) | Apr 30, 2023 |
| Gigabyte      | B365M D3H-CF                | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| Unknown       | Unknown                     | [c27abc2880](https://linux-hardware.org/?probe=c27abc2880) | Apr 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [f6a652b68d](https://linux-hardware.org/?probe=f6a652b68d) | Apr 14, 2023 |
| MSI           | B450M-A PRO MAX             | [07353da9f6](https://linux-hardware.org/?probe=07353da9f6) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [59db7a4f11](https://linux-hardware.org/?probe=59db7a4f11) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| HP            | 18E4                        | [54c681affc](https://linux-hardware.org/?probe=54c681affc) | Apr 10, 2023 |
| MSI           | PRO Z690-A DDR4             | [d1167f66b8](https://linux-hardware.org/?probe=d1167f66b8) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | [a6c5efe560](https://linux-hardware.org/?probe=a6c5efe560) | Apr 07, 2023 |
| Gigabyte      | H87M-D3H                    | [b9c169025d](https://linux-hardware.org/?probe=b9c169025d) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [5012c822d7](https://linux-hardware.org/?probe=5012c822d7) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [33eb81c75e](https://linux-hardware.org/?probe=33eb81c75e) | Apr 05, 2023 |
| MSI           | X470 GAMING PLUS            | [d3a27ee996](https://linux-hardware.org/?probe=d3a27ee996) | Apr 03, 2023 |
| HP            | 18E4                        | [5d10e73e1d](https://linux-hardware.org/?probe=5d10e73e1d) | Mar 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a8d31fc431](https://linux-hardware.org/?probe=a8d31fc431) | Mar 26, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [4253088a92](https://linux-hardware.org/?probe=4253088a92) | Mar 25, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [5bd922e142](https://linux-hardware.org/?probe=5bd922e142) | Mar 23, 2023 |
| AZW           | GK35                        | [bd935978b7](https://linux-hardware.org/?probe=bd935978b7) | Mar 22, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [a3e8bcd9dd](https://linux-hardware.org/?probe=a3e8bcd9dd) | Mar 18, 2023 |
| AZW           | U59                         | [ce6bd37711](https://linux-hardware.org/?probe=ce6bd37711) | Mar 18, 2023 |
| MSI           | 760GMA-P34                  | [b43ea7bb6e](https://linux-hardware.org/?probe=b43ea7bb6e) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| Unknown       | HX90                        | [51aca581e4](https://linux-hardware.org/?probe=51aca581e4) | Mar 11, 2023 |
| MSI           | B450I GAMING PLUS AC        | [bf6081f2af](https://linux-hardware.org/?probe=bf6081f2af) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0fdb67b9d2](https://linux-hardware.org/?probe=0fdb67b9d2) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2e48f233a0](https://linux-hardware.org/?probe=2e48f233a0) | Mar 09, 2023 |
| Dell          | 0KWVT8 A03                  | [af171db9dc](https://linux-hardware.org/?probe=af171db9dc) | Mar 08, 2023 |
| Dell          | 0GY6Y8 A02                  | [f363dca8ca](https://linux-hardware.org/?probe=f363dca8ca) | Mar 07, 2023 |
| HP            | 8860 A                      | [78c9aa9174](https://linux-hardware.org/?probe=78c9aa9174) | Mar 07, 2023 |
| HP            | 18E4                        | [a277b636c1](https://linux-hardware.org/?probe=a277b636c1) | Mar 05, 2023 |
| HP            | 18E4                        | [8e76736e7e](https://linux-hardware.org/?probe=8e76736e7e) | Mar 02, 2023 |
| Gigabyte      | P55A-UD3                    | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| HP            | 18E4                        | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| HP            | 18E4                        | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| ASRock        | B460 Steel Legend           | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [d5f5531b82](https://linux-hardware.org/?probe=d5f5531b82) | Feb 20, 2023 |
| ASUSTek       | PRIME Z390-P                | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| ASUSTek       | BT6130                      | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | [c84212b39c](https://linux-hardware.org/?probe=c84212b39c) | Feb 15, 2023 |
| MSI           | 760GMA-P34                  | [6c540405e8](https://linux-hardware.org/?probe=6c540405e8) | Feb 15, 2023 |
| Alienware     | 0VDT73 A00                  | [d8ed5d5e88](https://linux-hardware.org/?probe=d8ed5d5e88) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [820aa2bf49](https://linux-hardware.org/?probe=820aa2bf49) | Feb 13, 2023 |
| MSI           | X470 GAMING PLUS            | [debdb17904](https://linux-hardware.org/?probe=debdb17904) | Feb 12, 2023 |
| MSI           | 760GMA-P34                  | [05d11c4fe3](https://linux-hardware.org/?probe=05d11c4fe3) | Feb 12, 2023 |
| Dell          | 0Y5FXV A00                  | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [96847498e3](https://linux-hardware.org/?probe=96847498e3) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [de7f0840d1](https://linux-hardware.org/?probe=de7f0840d1) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [4251ab2f9a](https://linux-hardware.org/?probe=4251ab2f9a) | Feb 01, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [55b2bf8aea](https://linux-hardware.org/?probe=55b2bf8aea) | Jan 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | [f1d22db1d7](https://linux-hardware.org/?probe=f1d22db1d7) | Jan 21, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [2c44f8275e](https://linux-hardware.org/?probe=2c44f8275e) | Jan 17, 2023 |
| ASUSTek       | PRIME B460M-A               | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| Unknown       | Unknown                     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [154dafff1e](https://linux-hardware.org/?probe=154dafff1e) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [ce588e0413](https://linux-hardware.org/?probe=ce588e0413) | Jan 14, 2023 |
| ASUSTek       | PRIME Z390-P                | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [4fc1f3aff0](https://linux-hardware.org/?probe=4fc1f3aff0) | Jan 11, 2023 |
| MSI           | B450 TOMAHAWK               | [878c92decc](https://linux-hardware.org/?probe=878c92decc) | Jan 11, 2023 |
| HP            | 18E4                        | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| HP            | 18E4                        | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 2179                        | [ad75cc2104](https://linux-hardware.org/?probe=ad75cc2104) | Jan 10, 2023 |
| Dell          | 0NRKPK A01                  | [f5bdf45b4a](https://linux-hardware.org/?probe=f5bdf45b4a) | Jan 08, 2023 |
| Dell          | 0J584C A00                  | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| Intel         | DH61DL AAG14066-205         | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c84118baf](https://linux-hardware.org/?probe=0c84118baf) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | [2d0530b779](https://linux-hardware.org/?probe=2d0530b779) | Jan 03, 2023 |
| MSI           | B250M PRO-VD                | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| Intel         | DH61DL AAG14066-205         | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| Gigabyte      | P55A-UD3                    | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| HP            | 18E4                        | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [20eb2d93e2](https://linux-hardware.org/?probe=20eb2d93e2) | Jan 01, 2023 |
| HP            | 18E4                        | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | H310M S2 x.x                | [9aba0ac647](https://linux-hardware.org/?probe=9aba0ac647) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [b38e3cc51e](https://linux-hardware.org/?probe=b38e3cc51e) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [adb13e2649](https://linux-hardware.org/?probe=adb13e2649) | Dec 29, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | [cd90f1782c](https://linux-hardware.org/?probe=cd90f1782c) | Dec 26, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | [78418bfaa6](https://linux-hardware.org/?probe=78418bfaa6) | Dec 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| Gigabyte      | X570S AERO G                | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| HP            | 18E4                        | [26757adc9d](https://linux-hardware.org/?probe=26757adc9d) | Dec 15, 2022 |
| HP            | 18E4                        | [ba6bef79d5](https://linux-hardware.org/?probe=ba6bef79d5) | Dec 15, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [de70f43070](https://linux-hardware.org/?probe=de70f43070) | Dec 14, 2022 |
| HP            | 18E4                        | [00f1e4a14a](https://linux-hardware.org/?probe=00f1e4a14a) | Dec 14, 2022 |
| MSI           | B75MA-E33                   | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| ASRock        | X300M-STX                   | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| HP            | 18E4                        | [418a689ae5](https://linux-hardware.org/?probe=418a689ae5) | Dec 10, 2022 |
| MSI           | B450M-A PRO MAX             | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| HP            | 18E4                        | [e897549786](https://linux-hardware.org/?probe=e897549786) | Dec 06, 2022 |
| HP            | 18E4                        | [b12969b62f](https://linux-hardware.org/?probe=b12969b62f) | Dec 06, 2022 |
| MSI           | MEG Z490 UNIFY              | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1deadcff69](https://linux-hardware.org/?probe=1deadcff69) | Nov 27, 2022 |
| HP            | 18E4                        | [d72a174606](https://linux-hardware.org/?probe=d72a174606) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [63521d3e8d](https://linux-hardware.org/?probe=63521d3e8d) | Nov 26, 2022 |
| HP            | 18E4                        | [4a4ac150b6](https://linux-hardware.org/?probe=4a4ac150b6) | Nov 24, 2022 |
| ASRock        | X570M Pro4                  | [2b2778b81a](https://linux-hardware.org/?probe=2b2778b81a) | Nov 24, 2022 |
| ASUSTek       | PRIME B460M-A               | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| HP            | 18E4                        | [ff954b29c9](https://linux-hardware.org/?probe=ff954b29c9) | Nov 21, 2022 |
| MSI           | B360 GAMING PLUS            | [6552f5cfc9](https://linux-hardware.org/?probe=6552f5cfc9) | Nov 18, 2022 |
| HP            | 18E4                        | [37dd18c268](https://linux-hardware.org/?probe=37dd18c268) | Nov 17, 2022 |
| HP            | 3397                        | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| HP            | 18E4                        | [be545cc91f](https://linux-hardware.org/?probe=be545cc91f) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [31cae1e989](https://linux-hardware.org/?probe=31cae1e989) | Nov 04, 2022 |
| HP            | 18E4                        | [66463ac87d](https://linux-hardware.org/?probe=66463ac87d) | Nov 04, 2022 |
| HP            | 18E4                        | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| Gigabyte      | P55A-UD3                    | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| HP            | 18E7                        | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| Acer          | Predator PO3-620            | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| HP            | 18E4                        | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| Dell          | 040DDP A01                  | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3ab5922ddf](https://linux-hardware.org/?probe=3ab5922ddf) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| ASRock        | A320M-HDV R4.0              | [17a0e006d0](https://linux-hardware.org/?probe=17a0e006d0) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| Dell          | 042P49 A02                  | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| HP            | 18E4                        | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| Gigabyte      | H87M-D3H                    | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [c8997eb831](https://linux-hardware.org/?probe=c8997eb831) | Oct 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [01338c4f3c](https://linux-hardware.org/?probe=01338c4f3c) | Oct 19, 2022 |
| ASRock        | B450 Pro4                   | [d7784759fb](https://linux-hardware.org/?probe=d7784759fb) | Oct 19, 2022 |
| MSI           | Z390-A PRO                  | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| MSI           | B250M PRO-VD                | [28d9942c9f](https://linux-hardware.org/?probe=28d9942c9f) | Oct 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [bf1677e47c](https://linux-hardware.org/?probe=bf1677e47c) | Oct 14, 2022 |
| ASUSTek       | PRIME B560M-A               | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| Gigabyte      | H81M-S2PV                   | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| HP            | 18E4                        | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| HP            | 18E4                        | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [75e1aeaff5](https://linux-hardware.org/?probe=75e1aeaff5) | Oct 02, 2022 |
| ASUSTek       | PRIME Z390-P                | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| ASRock        | B450M-HDV R4.0              | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | [6e96f4620a](https://linux-hardware.org/?probe=6e96f4620a) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | [acb677ddeb](https://linux-hardware.org/?probe=acb677ddeb) | Sep 25, 2022 |
| ASRock        | B450 Pro4                   | [fe99b8a461](https://linux-hardware.org/?probe=fe99b8a461) | Sep 25, 2022 |
| ASUSTek       | SABERTOOTH P67              | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| AZW           | SEi                         | [579b2be420](https://linux-hardware.org/?probe=579b2be420) | Sep 23, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [d0f94bde46](https://linux-hardware.org/?probe=d0f94bde46) | Sep 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f4f33e2362](https://linux-hardware.org/?probe=f4f33e2362) | Sep 20, 2022 |
| ASUSTek       | SABERTOOTH P67              | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [543fad9f1c](https://linux-hardware.org/?probe=543fad9f1c) | Sep 18, 2022 |
| HP            | 1998                        | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| ASUSTek       | H170M-PLUS                  | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Dell          | 0HMF7C A01                  | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| ASUSTek       | PRIME H310M-K               | [2fb52eb1a8](https://linux-hardware.org/?probe=2fb52eb1a8) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | P55A-UD3                    | [297cab0eb2](https://linux-hardware.org/?probe=297cab0eb2) | Sep 01, 2022 |
| HP            | 18E7                        | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek       | Maximus IX HERO             | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| ASRock        | B550M Pro4                  | [9b5ba9f755](https://linux-hardware.org/?probe=9b5ba9f755) | Aug 18, 2022 |
| MSI           | A320M PRO-E                 | [2aa966d8af](https://linux-hardware.org/?probe=2aa966d8af) | Aug 14, 2022 |
| ASUSTek       | PRIME X570-P                | [94579c3a70](https://linux-hardware.org/?probe=94579c3a70) | Aug 13, 2022 |
| AZW           | U59                         | [33aea75ff4](https://linux-hardware.org/?probe=33aea75ff4) | Aug 07, 2022 |
| Gigabyte      | B550M AORUS PRO             | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| ASRock        | A320M-HDV R4.0              | [06dd902359](https://linux-hardware.org/?probe=06dd902359) | Jul 23, 2022 |
| MSI           | PRO Z690-A WIFI             | [00f490c5d0](https://linux-hardware.org/?probe=00f490c5d0) | Jul 22, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b3f65d7c35](https://linux-hardware.org/?probe=b3f65d7c35) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [d7e2758b93](https://linux-hardware.org/?probe=d7e2758b93) | Jul 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| Samsung       | DeskTop System              | [d0d33ec330](https://linux-hardware.org/?probe=d0d33ec330) | Jul 19, 2022 |
| Samsung       | DeskTop System              | [3af9bcc9cb](https://linux-hardware.org/?probe=3af9bcc9cb) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85a02f5d41](https://linux-hardware.org/?probe=85a02f5d41) | Jul 15, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HP            | 158B                        | [1f3ebf7ecf](https://linux-hardware.org/?probe=1f3ebf7ecf) | Jul 07, 2022 |
| Gigabyte      | N3160TN                     | [b92830b100](https://linux-hardware.org/?probe=b92830b100) | Jul 03, 2022 |
| Gigabyte      | P55A-UD3                    | [36dcdacdb1](https://linux-hardware.org/?probe=36dcdacdb1) | Jul 01, 2022 |
| ASRock        | B450M Pro4                  | [5dd727cd5e](https://linux-hardware.org/?probe=5dd727cd5e) | Jul 01, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| MSI           | B450 TOMAHAWK               | [b9a8ce148e](https://linux-hardware.org/?probe=b9a8ce148e) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | [16d7a07f8f](https://linux-hardware.org/?probe=16d7a07f8f) | Jun 20, 2022 |
| Dell          | 040DDP A01                  | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [b0cc04798d](https://linux-hardware.org/?probe=b0cc04798d) | Jun 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| MSI           | B450 TOMAHAWK               | [ed5235f3f4](https://linux-hardware.org/?probe=ed5235f3f4) | Jun 09, 2022 |
| ASUSTek       | SABERTOOTH X99              | [5c7a9690cf](https://linux-hardware.org/?probe=5c7a9690cf) | Jun 05, 2022 |
| ASUSTek       | H110M-E/M.2                 | [cb5ea65a1d](https://linux-hardware.org/?probe=cb5ea65a1d) | Jun 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| ASRock        | B450 Pro4                   | [394d112de5](https://linux-hardware.org/?probe=394d112de5) | May 31, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| Gigabyte      | B550M AORUS PRO             | [0075e2d9df](https://linux-hardware.org/?probe=0075e2d9df) | May 28, 2022 |
| Dell          | 0K240Y A01                  | [4ef7645f2d](https://linux-hardware.org/?probe=4ef7645f2d) | May 28, 2022 |
| HP            | 0A08h                       | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| ASRock        | A320M/ac                    | [78ee9c8853](https://linux-hardware.org/?probe=78ee9c8853) | May 20, 2022 |
| HP            | 3647h                       | [eccb82bec8](https://linux-hardware.org/?probe=eccb82bec8) | May 20, 2022 |
| HP            | 8906 SMVB                   | [0bc568827c](https://linux-hardware.org/?probe=0bc568827c) | May 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| MSI           | B75MA-E33                   | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| ASUSTek       | P8H77-M                     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [7354dedb38](https://linux-hardware.org/?probe=7354dedb38) | May 03, 2022 |
| ASRock        | B450 Pro4                   | [bcc65ca336](https://linux-hardware.org/?probe=bcc65ca336) | May 03, 2022 |
| ASRock        | B450 Pro4                   | [e40e784775](https://linux-hardware.org/?probe=e40e784775) | May 03, 2022 |
| ASRock        | AB350M Pro4                 | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| Gigabyte      | P55A-UD3                    | [b212517217](https://linux-hardware.org/?probe=b212517217) | May 01, 2022 |
| ASRock        | B450M Pro4                  | [79a3d8d3f6](https://linux-hardware.org/?probe=79a3d8d3f6) | May 01, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e45e120b35](https://linux-hardware.org/?probe=e45e120b35) | Apr 29, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a7eeea4f7c](https://linux-hardware.org/?probe=a7eeea4f7c) | Apr 27, 2022 |
| ASRock        | B560 Pro4                   | [5fdc5a8e7b](https://linux-hardware.org/?probe=5fdc5a8e7b) | Apr 21, 2022 |
| ASUSTek       | PRIME H410M-E               | [583693a1a9](https://linux-hardware.org/?probe=583693a1a9) | Apr 17, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1a48a9a11d](https://linux-hardware.org/?probe=1a48a9a11d) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| ASRock        | B560 Pro4                   | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| Dell          | 0WMJ54 A01                  | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASRock        | B450 Pro4                   | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| Gigabyte      | B450 GAMING X               | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Lenovo        | ThinkStation C20 426593U    | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [a0a0ba299e](https://linux-hardware.org/?probe=a0a0ba299e) | Mar 15, 2022 |
| Dell          | 0JP3NX A01                  | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | P55A-UD3                    | [677fa0d0a3](https://linux-hardware.org/?probe=677fa0d0a3) | Mar 01, 2022 |
| ASRock        | B450M Pro4                  | [e81420b85c](https://linux-hardware.org/?probe=e81420b85c) | Mar 01, 2022 |
| MSI           | B75MA-P45                   | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0KWVT8 A03                  | [f4bc34ce43](https://linux-hardware.org/?probe=f4bc34ce43) | Feb 23, 2022 |
| ASRock        | B450M Pro4                  | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [7ad21cbc90](https://linux-hardware.org/?probe=7ad21cbc90) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | [2bfd36f050](https://linux-hardware.org/?probe=2bfd36f050) | Feb 18, 2022 |
| MSI           | B450 TOMAHAWK               | [63d492d4bb](https://linux-hardware.org/?probe=63d492d4bb) | Feb 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [64e32a1354](https://linux-hardware.org/?probe=64e32a1354) | Feb 02, 2022 |
| HP            | 1905                        | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| ASUSTek       | P8H77-V                     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| MSI           | B75MA-P45                   | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5c5ac9fe1d](https://linux-hardware.org/?probe=5c5ac9fe1d) | Jan 26, 2022 |
| ASRock        | A320M-HD                    | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| MSI           | B150M ECO                   | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | [56e21b8bd6](https://linux-hardware.org/?probe=56e21b8bd6) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | [6586f2d78f](https://linux-hardware.org/?probe=6586f2d78f) | Jan 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| ASRock        | B550M Steel Legend          | [b09195fb3c](https://linux-hardware.org/?probe=b09195fb3c) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
| MSI           | Z170A GAMING M3             | [57e7500f2a](https://linux-hardware.org/?probe=57e7500f2a) | Jan 17, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [e1f153a5e6](https://linux-hardware.org/?probe=e1f153a5e6) | Jan 14, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [5ca44fe54c](https://linux-hardware.org/?probe=5ca44fe54c) | Jan 10, 2022 |
| ASUSTek       | Maximus VII GENE            | [0462560ab2](https://linux-hardware.org/?probe=0462560ab2) | Jan 10, 2022 |
| ASRock        | FM2A88X Pro3+               | [1cc054ed3f](https://linux-hardware.org/?probe=1cc054ed3f) | Jan 09, 2022 |
| Dell          | 0K240Y A01                  | [2542ffac8a](https://linux-hardware.org/?probe=2542ffac8a) | Jan 06, 2022 |
| MSI           | Z97 PC Mate                 | [2e5c796311](https://linux-hardware.org/?probe=2e5c796311) | Jan 06, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI           | Z490-A PRO                  | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Positivo      | POS-PIH81DI                 | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| ASUSTek       | Z97-A                       | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock        | B450 Steel Legend           | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| MSI           | B450 TOMAHAWK               | [c85d7c78e7](https://linux-hardware.org/?probe=c85d7c78e7) | Dec 28, 2021 |
| LattePanda    | Alpha                       | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar       | G31-M7 TE                   | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda    | Alpha                       | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte      | M68M-S2P                    | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Acer          | Aspire XC-1660G V:1.1       | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| Gigabyte      | H110N-CF                    | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| MSI           | Z87-G41 PC Mate             | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| Unknown       | Intel X79                   | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell          | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| MSI           | B350 PC MATE                | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Gigabyte      | B560M DS3H                  | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| ASUSTek       | Z87-DELUXE                  | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte      | B560M DS3H                  | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| Gigabyte      | Z77X-D3H                    | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7ebeace900](https://linux-hardware.org/?probe=7ebeace900) | Nov 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [1cfd4ee9f9](https://linux-hardware.org/?probe=1cfd4ee9f9) | Nov 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [c9e5138184](https://linux-hardware.org/?probe=c9e5138184) | Nov 07, 2021 |
| ASUSTek       | Maximus VIII HERO           | [22ce2703b9](https://linux-hardware.org/?probe=22ce2703b9) | Nov 07, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [5d0bad7c15](https://linux-hardware.org/?probe=5d0bad7c15) | Nov 06, 2021 |
| ASRock        | H310CM-DVS                  | [79e6ef3655](https://linux-hardware.org/?probe=79e6ef3655) | Oct 29, 2021 |
| ASRock        | H310CM-DVS                  | [6db3b9d661](https://linux-hardware.org/?probe=6db3b9d661) | Oct 29, 2021 |
| Gigabyte      | B450 GAMING X               | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| ASRock        | B550M Pro4                  | [87ab64b604](https://linux-hardware.org/?probe=87ab64b604) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| UMAX          | J42 Nano                    | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte      | B85M-HD3                    | [cc7d0245a7](https://linux-hardware.org/?probe=cc7d0245a7) | Oct 09, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [849ca2da3d](https://linux-hardware.org/?probe=849ca2da3d) | Oct 06, 2021 |
| Gigabyte      | B550 VISION D               | [e8a2ba9952](https://linux-hardware.org/?probe=e8a2ba9952) | Oct 03, 2021 |
| MSI           | G41M-P33 Combo              | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Gigabyte      | H110M-S2-CF                 | [a20f426eed](https://linux-hardware.org/?probe=a20f426eed) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [8ffa4dd273](https://linux-hardware.org/?probe=8ffa4dd273) | Sep 18, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [60555ce93d](https://linux-hardware.org/?probe=60555ce93d) | Sep 16, 2021 |
| MSI           | B450M PRO-VDH MAX           | [33cee010e8](https://linux-hardware.org/?probe=33cee010e8) | Sep 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [c06b4b30a0](https://linux-hardware.org/?probe=c06b4b30a0) | Sep 10, 2021 |
| MSI           | B450-A PRO MAX              | [12cf057e04](https://linux-hardware.org/?probe=12cf057e04) | Sep 02, 2021 |
| Intel         | DH55HC AAE70933-504         | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP            | 8906 SMVB                   | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Gigabyte      | P35-DS3R                    | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [8e9d51a941](https://linux-hardware.org/?probe=8e9d51a941) | Aug 07, 2021 |
| Dell          | 0K240Y A01                  | [5cc92cb5ac](https://linux-hardware.org/?probe=5cc92cb5ac) | Aug 04, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [f36328f6b3](https://linux-hardware.org/?probe=f36328f6b3) | Jul 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [14b3d46ef8](https://linux-hardware.org/?probe=14b3d46ef8) | Jul 03, 2021 |
| ASUSTek       | P7H55D-M EVO                | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| Gigabyte      | Z97X-Gaming 5               | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [10c5bbf0f8](https://linux-hardware.org/?probe=10c5bbf0f8) | Jun 18, 2021 |
| ASUSTek       | F1A55-M LX                  | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [585db3001d](https://linux-hardware.org/?probe=585db3001d) | May 19, 2021 |
| HP            | 2B36                        | [62135f1e45](https://linux-hardware.org/?probe=62135f1e45) | May 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| ASRock        | A300M-STX                   | [fc96347868](https://linux-hardware.org/?probe=fc96347868) | May 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [dd68978e2b](https://linux-hardware.org/?probe=dd68978e2b) | Apr 28, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [7ee064e334](https://linux-hardware.org/?probe=7ee064e334) | Apr 27, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| Lenovo        | SHARKBAY NOK                | [0685ce717e](https://linux-hardware.org/?probe=0685ce717e) | Apr 16, 2021 |
| Gigabyte      | B550M AORUS PRO             | [a635a3acb3](https://linux-hardware.org/?probe=a635a3acb3) | Apr 13, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Gigabyte      | B450 AORUS M                | [d53c2a8b0e](https://linux-hardware.org/?probe=d53c2a8b0e) | Apr 11, 2021 |
| Dell          | 0080PM A00                  | [efc9497e6d](https://linux-hardware.org/?probe=efc9497e6d) | Apr 08, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [63e7ed5aa3](https://linux-hardware.org/?probe=63e7ed5aa3) | Apr 07, 2021 |
| Lenovo        | 36EB NOK                    | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [08f8da317e](https://linux-hardware.org/?probe=08f8da317e) | Apr 03, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [31baa57d40](https://linux-hardware.org/?probe=31baa57d40) | Mar 17, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [7c5776953c](https://linux-hardware.org/?probe=7c5776953c) | Mar 15, 2021 |
| Gigabyte      | B550M AORUS PRO             | [41de0a7ee7](https://linux-hardware.org/?probe=41de0a7ee7) | Mar 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
| MSI           | Z87-G45 GAMING              | [67ca38a642](https://linux-hardware.org/?probe=67ca38a642) | Feb 12, 2021 |
| MSI           | Z87-G45 GAMING              | [e6937666ae](https://linux-hardware.org/?probe=e6937666ae) | Feb 11, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [e11200bd19](https://linux-hardware.org/?probe=e11200bd19) | Feb 10, 2021 |
| ASUSTek       | H81-PLUS                    | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [cef326fa21](https://linux-hardware.org/?probe=cef326fa21) | Feb 08, 2021 |
| ASRock        | B550M Steel Legend          | [335242ec06](https://linux-hardware.org/?probe=335242ec06) | Jan 20, 2021 |
| ASUSTek       | PRIME X470-PRO              | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| Gigabyte      | X58A-UD3R                   | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| ASUSTek       | Z87-PRO                     | [2ab19967fa](https://linux-hardware.org/?probe=2ab19967fa) | Dec 30, 2020 |
| ASUSTek       | Maximus VIII HERO           | [4d27980548](https://linux-hardware.org/?probe=4d27980548) | Dec 27, 2020 |
| ASUSTek       | Maximus VIII HERO           | [08895b552f](https://linux-hardware.org/?probe=08895b552f) | Dec 27, 2020 |
| HP            | 1905                        | [63771015f5](https://linux-hardware.org/?probe=63771015f5) | Dec 22, 2020 |
| Gigabyte      | H110M-S2-CF                 | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| Gigabyte      | X58A-UD3R                   | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [0ffe9c1f28](https://linux-hardware.org/?probe=0ffe9c1f28) | Nov 27, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| Dell          | 0KRC95 A02                  | [af91587001](https://linux-hardware.org/?probe=af91587001) | Nov 19, 2020 |
| ASRock        | Z77 Extreme4                | [3de701fc00](https://linux-hardware.org/?probe=3de701fc00) | Nov 12, 2020 |
| ASRock        | Z77 Extreme4                | [64d986c0ec](https://linux-hardware.org/?probe=64d986c0ec) | Nov 12, 2020 |
| Dell          | 0KRC95 A02                  | [6471eccd57](https://linux-hardware.org/?probe=6471eccd57) | Nov 11, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7a14486580](https://linux-hardware.org/?probe=7a14486580) | Nov 04, 2020 |
| Gigabyte      | H270-HD3-CF                 | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| HP            | 8455                        | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| HP            | 8455                        | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| Dell          | 0G214D A00                  | [21319d118b](https://linux-hardware.org/?probe=21319d118b) | Oct 25, 2020 |
| MSI           | MS-7366                     | [ada828f120](https://linux-hardware.org/?probe=ada828f120) | Sep 29, 2020 |
| Dell          | 096JG8 A01                  | [a031f4a8a2](https://linux-hardware.org/?probe=a031f4a8a2) | Sep 29, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [ee969068e8](https://linux-hardware.org/?probe=ee969068e8) | Sep 28, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a4e794299b](https://linux-hardware.org/?probe=a4e794299b) | Sep 28, 2020 |
| ASUSTek       | P8P67 DELUXE                | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| MSI           | MS-7366                     | [9938e6501b](https://linux-hardware.org/?probe=9938e6501b) | Sep 24, 2020 |
| Gigabyte      | B450 AORUS M                | [34f1896f7e](https://linux-hardware.org/?probe=34f1896f7e) | Sep 23, 2020 |
| Gigabyte      | B550M AORUS PRO             | [17e933a69c](https://linux-hardware.org/?probe=17e933a69c) | Sep 21, 2020 |
| HP            | 1497                        | [7cb2cee563](https://linux-hardware.org/?probe=7cb2cee563) | Sep 19, 2020 |
| Gigabyte      | B550M AORUS PRO             | [50a3035c47](https://linux-hardware.org/?probe=50a3035c47) | Sep 12, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3919584d23](https://linux-hardware.org/?probe=3919584d23) | Sep 06, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [028f3ba060](https://linux-hardware.org/?probe=028f3ba060) | Sep 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | [662f61d283](https://linux-hardware.org/?probe=662f61d283) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [143c679f1a](https://linux-hardware.org/?probe=143c679f1a) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2ab9b15cb6](https://linux-hardware.org/?probe=2ab9b15cb6) | Sep 03, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| ASUSTek       | Z87M-PLUS                   | [844cca1bee](https://linux-hardware.org/?probe=844cca1bee) | Aug 09, 2020 |
| ASUSTek       | PRIME X570-P                | [cb7a700ec4](https://linux-hardware.org/?probe=cb7a700ec4) | Aug 07, 2020 |
| Gigabyte      | B365M DS3H                  | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [54774ae912](https://linux-hardware.org/?probe=54774ae912) | Jul 14, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [85295c522b](https://linux-hardware.org/?probe=85295c522b) | Jul 14, 2020 |
| Lenovo        | MAHOBAY NOK                 | [6e3c82fbca](https://linux-hardware.org/?probe=6e3c82fbca) | Jul 13, 2020 |
| ASUSTek       | Z87M-PLUS                   | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte      | B365M DS3H                  | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI           | B450-A PRO MAX              | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Biostar       | G31-M7 TE                   | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte      | B85M-D3H                    | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| ASUSTek       | PRIME A320M-K               | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte      | B450M S2H                   | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| ASUSTek       | PRIME A320M-K               | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek       | PRIME A320M-K               | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek       | PRIME A320M-K               | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek       | PRIME A320M-K               | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek       | PRIME A320M-K               | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| EndeavourOS Rolling | 277      | 82.2%   |
| EndeavourOS         | 60       | 17.8%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| EndeavourOS | 333      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.15.12-arch1-1    | 10       | 2.48%   |
| 6.1.1-arch1-1      | 8        | 1.98%   |
| 5.7.7-arch1-1      | 6        | 1.49%   |
| 6.3.9-arch1-1      | 5        | 1.24%   |
| 6.2.2-arch1-1      | 5        | 1.24%   |
| 6.2.13-arch1-1     | 5        | 1.24%   |
| 6.1.12-arch1-1     | 5        | 1.24%   |
| 6.0.2-zen1-1-zen   | 5        | 1.24%   |
| 6.0.2-arch1-1      | 5        | 1.24%   |
| 5.17.5-arch1-1     | 5        | 1.24%   |
| 5.17.1-arch1-1     | 5        | 1.24%   |
| 5.16.2-arch1-1     | 5        | 1.24%   |
| 6.0.9-arch1-1      | 4        | 0.99%   |
| 5.18.12-arch1-1    | 4        | 0.99%   |
| 5.15.74-1-lts      | 4        | 0.99%   |
| 5.15.7-arch1-1     | 4        | 0.99%   |
| 5.11.11-arch1-1    | 4        | 0.99%   |
| 6.2.10-arch1-1     | 3        | 0.74%   |
| 6.1.11-arch1-1     | 3        | 0.74%   |
| 6.1.1-zen1-1-zen   | 3        | 0.74%   |
| 6.0.6-arch1-1      | 3        | 0.74%   |
| 5.19.10-arch1-1    | 3        | 0.74%   |
| 5.18.7-arch1-1     | 3        | 0.74%   |
| 5.18.5-arch1-1     | 3        | 0.74%   |
| 5.18.14-arch1-1    | 3        | 0.74%   |
| 5.17.9-arch1-1     | 3        | 0.74%   |
| 5.16.16-arch1-1    | 3        | 0.74%   |
| 5.16.10-arch1-1    | 3        | 0.74%   |
| 5.15.8-arch1-1     | 3        | 0.74%   |
| 5.15.12-zen1-1-zen | 3        | 0.74%   |
| 5.15.10-arch1-1    | 3        | 0.74%   |
| 5.14.9-arch2-1     | 3        | 0.74%   |
| 5.14.8-arch1-1     | 3        | 0.74%   |
| 5.10.88-2-lts      | 3        | 0.74%   |
| 6.4.8-arch1-1      | 2        | 0.5%    |
| 6.4.2-arch1-1      | 2        | 0.5%    |
| 6.3.4-arch1-1      | 2        | 0.5%    |
| 6.3.1-arch1-1      | 2        | 0.5%    |
| 6.2.11-arch1-1     | 2        | 0.5%    |
| 6.2.10-zen1-1-zen  | 2        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 14       | 3.47%   |
| 6.1.1   | 11       | 2.72%   |
| 6.0.2   | 10       | 2.48%   |
| 6.2.2   | 7        | 1.73%   |
| 5.17.5  | 7        | 1.73%   |
| 6.2.13  | 6        | 1.49%   |
| 5.7.7   | 6        | 1.49%   |
| 6.3.9   | 5        | 1.24%   |
| 6.3.1   | 5        | 1.24%   |
| 6.2.10  | 5        | 1.24%   |
| 6.1.12  | 5        | 1.24%   |
| 6.0.9   | 5        | 1.24%   |
| 6.0.6   | 5        | 1.24%   |
| 5.19.9  | 5        | 1.24%   |
| 5.18.12 | 5        | 1.24%   |
| 5.17.1  | 5        | 1.24%   |
| 5.16.2  | 5        | 1.24%   |
| 5.16.16 | 5        | 1.24%   |
| 5.15.7  | 5        | 1.24%   |
| 6.4.7   | 4        | 0.99%   |
| 6.4.3   | 4        | 0.99%   |
| 6.1.4   | 4        | 0.99%   |
| 6.0.11  | 4        | 0.99%   |
| 5.8.5   | 4        | 0.99%   |
| 5.18.5  | 4        | 0.99%   |
| 5.17.9  | 4        | 0.99%   |
| 5.15.74 | 4        | 0.99%   |
| 5.11.11 | 4        | 0.99%   |
| 5.10.88 | 4        | 0.99%   |
| 6.3.5   | 3        | 0.74%   |
| 6.3.4   | 3        | 0.74%   |
| 6.2.1   | 3        | 0.74%   |
| 6.1.8   | 3        | 0.74%   |
| 6.1.11  | 3        | 0.74%   |
| 6.0.12  | 3        | 0.74%   |
| 5.9.1   | 3        | 0.74%   |
| 5.19.5  | 3        | 0.74%   |
| 5.19.10 | 3        | 0.74%   |
| 5.18.7  | 3        | 0.74%   |
| 5.18.14 | 3        | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 53       | 13.55%  |
| 6.1     | 39       | 9.97%   |
| 6.0     | 31       | 7.93%   |
| 6.2     | 28       | 7.16%   |
| 5.18    | 28       | 7.16%   |
| 5.16    | 25       | 6.39%   |
| 6.3     | 22       | 5.63%   |
| 5.19    | 22       | 5.63%   |
| 5.17    | 22       | 5.63%   |
| 5.14    | 17       | 4.35%   |
| 6.4     | 16       | 4.09%   |
| 5.10    | 15       | 3.84%   |
| 5.11    | 14       | 3.58%   |
| 5.9     | 13       | 3.32%   |
| 5.12    | 13       | 3.32%   |
| 5.8     | 10       | 2.56%   |
| 5.7     | 9        | 2.3%    |
| 5.13    | 7        | 1.79%   |
| 5.6     | 3        | 0.77%   |
| 5.5     | 2        | 0.51%   |
| 5.4     | 1        | 0.26%   |
| Unknown | 1        | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 333      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 148      | 42.41%  |
| XFCE            | 64       | 18.34%  |
| GNOME           | 56       | 16.05%  |
| i3              | 19       | 5.44%   |
| X-Cinnamon      | 18       | 5.16%   |
| KDE             | 11       | 3.15%   |
| Budgie          | 7        | 2.01%   |
| Cinnamon        | 5        | 1.43%   |
| sway            | 4        | 1.15%   |
| Unknown         | 4        | 1.15%   |
| LXQt            | 3        | 0.86%   |
| MATE            | 2        | 0.57%   |
| openbox         | 1        | 0.29%   |
| jwm             | 1        | 0.29%   |
| Hyprland        | 1        | 0.29%   |
| herbstluftwm    | 1        | 0.29%   |
| GNOME Flashback | 1        | 0.29%   |
| Deepin          | 1        | 0.29%   |
| bspwm           | 1        | 0.29%   |
| awesome         | 1        | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 281      | 82.16%  |
| Wayland | 45       | 13.16%  |
| Tty     | 12       | 3.51%   |
| Unknown | 3        | 0.88%   |
| Web     | 1        | 0.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 110      | 32.07%  |
| Unknown | 93       | 27.11%  |
| SDDM    | 88       | 25.66%  |
| GDM     | 31       | 9.04%   |
| TDM     | 20       | 5.83%   |
| LY-DM   | 1        | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 165      | 49.25%  |
| de_DE   | 27       | 8.06%   |
| en_GB   | 25       | 7.46%   |
| it_IT   | 18       | 5.37%   |
| en_CA   | 13       | 3.88%   |
| ru_RU   | 10       | 2.99%   |
| pl_PL   | 6        | 1.79%   |
| fr_FR   | 6        | 1.79%   |
| es_ES   | 5        | 1.49%   |
| en_IN   | 5        | 1.49%   |
| pt_BR   | 4        | 1.19%   |
| nl_BE   | 4        | 1.19%   |
| en_DK   | 4        | 1.19%   |
| en_AU   | 4        | 1.19%   |
| en_AG   | 4        | 1.19%   |
| nl_NL   | 3        | 0.9%    |
| es_AR   | 3        | 0.9%    |
| Unknown | 3        | 0.9%    |
| tr_TR   | 2        | 0.6%    |
| sv_SE   | 2        | 0.6%    |
| es_MX   | 2        | 0.6%    |
| en_HK   | 2        | 0.6%    |
| de_AT   | 2        | 0.6%    |
| sl_SI   | 1        | 0.3%    |
| pt_PT   | 1        | 0.3%    |
| hu_HU   | 1        | 0.3%    |
| fr_CA   | 1        | 0.3%    |
| fr_BE   | 1        | 0.3%    |
| fi_FI   | 1        | 0.3%    |
| es_GT   | 1        | 0.3%    |
| es_CR   | 1        | 0.3%    |
| eo      | 1        | 0.3%    |
| en_ZA   | 1        | 0.3%    |
| en_SG   | 1        | 0.3%    |
| en_FI   | 1        | 0.3%    |
| de_LU   | 1        | 0.3%    |
| de_CH   | 1        | 0.3%    |
| cs_CZ   | 1        | 0.3%    |
| C       | 1        | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 197      | 58.63%  |
| BIOS | 139      | 41.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 235      | 70.15%  |
| Btrfs   | 89       | 26.57%  |
| Overlay | 5        | 1.49%   |
| Xfs     | 2        | 0.6%    |
| Tmpfs   | 2        | 0.6%    |
| XXX4    | 1        | 0.3%    |
| F2fs    | 1        | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 214      | 63.69%  |
| Unknown | 98       | 29.17%  |
| MBR     | 24       | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 268      | 79.29%  |
| Yes       | 70       | 20.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 199      | 58.53%  |
| Yes       | 141      | 41.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 90       | 27.03%  |
| MSI                                  | 73       | 21.92%  |
| Gigabyte Technology                  | 67       | 20.12%  |
| ASRock                               | 32       | 9.61%   |
| Hewlett-Packard                      | 19       | 5.71%   |
| Dell                                 | 17       | 5.11%   |
| Lenovo                               | 9        | 2.7%    |
| Unknown                              | 4        | 1.2%    |
| AZW                                  | 3        | 0.9%    |
| Samsung Electronics                  | 2        | 0.6%    |
| Intel                                | 2        | 0.6%    |
| Huanan                               | 2        | 0.6%    |
| Fujitsu                              | 2        | 0.6%    |
| Biostar                              | 2        | 0.6%    |
| Acer                                 | 2        | 0.6%    |
| UMAX                                 | 1        | 0.3%    |
| Shenzhen Meigao Electronic Equipment | 1        | 0.3%    |
| Positivo                             | 1        | 0.3%    |
| Medion                               | 1        | 0.3%    |
| LattePanda                           | 1        | 0.3%    |
| Daten Tecnologia                     | 1        | 0.3%    |
| Alienware                            | 1        | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI MS-7C37                          | 11       | 3.3%    |
| ASUS All Series                      | 9        | 2.7%    |
| MSI MS-7C02                          | 5        | 1.5%    |
| MSI MS-7A38                          | 5        | 1.5%    |
| ASUS ROG STRIX X570-E GAMING         | 5        | 1.5%    |
| Gigabyte B450 AORUS ELITE            | 4        | 1.2%    |
| ASUS TUF Gaming X570-PLUS            | 4        | 1.2%    |
| ASRock B450M Pro4                    | 4        | 1.2%    |
| ASRock B450 Pro4                     | 4        | 1.2%    |
| Unknown                              | 4        | 1.2%    |
| MSI MS-7C91                          | 3        | 0.9%    |
| MSI MS-7C56                          | 3        | 0.9%    |
| MSI MS-7C52                          | 3        | 0.9%    |
| Gigabyte B550M AORUS PRO             | 3        | 0.9%    |
| Gigabyte B550 AORUS ELITE V2         | 3        | 0.9%    |
| Gigabyte B450M DS3H                  | 3        | 0.9%    |
| ASUS ROG STRIX B550-F GAMING         | 3        | 0.9%    |
| MSI MS-7D25                          | 2        | 0.6%    |
| MSI MS-7C84                          | 2        | 0.6%    |
| MSI MS-7B86                          | 2        | 0.6%    |
| MSI MS-7B85                          | 2        | 0.6%    |
| MSI MS-7B79                          | 2        | 0.6%    |
| MSI MS-7A74                          | 2        | 0.6%    |
| MSI MS-7A34                          | 2        | 0.6%    |
| MSI MS-7850                          | 2        | 0.6%    |
| MSI MS-7798                          | 2        | 0.6%    |
| HP Z230 Tower Workstation            | 2        | 0.6%    |
| HP ProDesk 600 G1 SFF                | 2        | 0.6%    |
| HP Pavilion Gaming Desktop TG01-2xxx | 2        | 0.6%    |
| Gigabyte X570 AORUS ELITE            | 2        | 0.6%    |
| Gigabyte H110M-S2                    | 2        | 0.6%    |
| Gigabyte B450M S2H                   | 2        | 0.6%    |
| Dell OptiPlex 7010                   | 2        | 0.6%    |
| Dell OptiPlex 3050                   | 2        | 0.6%    |
| Dell OptiPlex 3020                   | 2        | 0.6%    |
| Biostar G31-M7 TE                    | 2        | 0.6%    |
| ASUS TUF Gaming X570-PRO             | 2        | 0.6%    |
| ASUS ROG STRIX B450-F GAMING         | 2        | 0.6%    |
| ASUS ROG CROSSHAIR VIII DARK HERO    | 2        | 0.6%    |
| ASUS PRIME X570-P                    | 2        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 23       | 6.91%   |
| ASUS PRIME           | 17       | 5.11%   |
| ASUS TUF             | 16       | 4.8%    |
| Dell OptiPlex        | 12       | 3.6%    |
| MSI MS-7C37          | 11       | 3.3%    |
| ASUS All             | 9        | 2.7%    |
| Gigabyte B550        | 7        | 2.1%    |
| Gigabyte B450        | 7        | 2.1%    |
| ASRock B450          | 6        | 1.8%    |
| MSI MS-7C02          | 5        | 1.5%    |
| MSI MS-7A38          | 5        | 1.5%    |
| Lenovo ThinkCentre   | 5        | 1.5%    |
| Gigabyte X570        | 5        | 1.5%    |
| Gigabyte B450M       | 5        | 1.5%    |
| Gigabyte B550M       | 4        | 1.2%    |
| ASRock B550M         | 4        | 1.2%    |
| ASRock B450M         | 4        | 1.2%    |
| Unknown              | 4        | 1.2%    |
| MSI MS-7C91          | 3        | 0.9%    |
| MSI MS-7C56          | 3        | 0.9%    |
| MSI MS-7C52          | 3        | 0.9%    |
| HP Pavilion          | 3        | 0.9%    |
| Gigabyte Z390        | 3        | 0.9%    |
| ASUS STRIX           | 3        | 0.9%    |
| MSI MS-7D25          | 2        | 0.6%    |
| MSI MS-7C84          | 2        | 0.6%    |
| MSI MS-7B86          | 2        | 0.6%    |
| MSI MS-7B85          | 2        | 0.6%    |
| MSI MS-7B79          | 2        | 0.6%    |
| MSI MS-7A74          | 2        | 0.6%    |
| MSI MS-7A34          | 2        | 0.6%    |
| MSI MS-7850          | 2        | 0.6%    |
| MSI MS-7798          | 2        | 0.6%    |
| Lenovo IdeaCentre    | 2        | 0.6%    |
| HP Z230              | 2        | 0.6%    |
| HP ProDesk           | 2        | 0.6%    |
| HP EliteDesk         | 2        | 0.6%    |
| HP Compaq            | 2        | 0.6%    |
| Gigabyte Z97X-Gaming | 2        | 0.6%    |
| Gigabyte X470        | 2        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 62       | 18.62%  |
| 2019 | 54       | 16.22%  |
| 2020 | 47       | 14.11%  |
| 2021 | 30       | 9.01%   |
| 2013 | 24       | 7.21%   |
| 2012 | 21       | 6.31%   |
| 2017 | 19       | 5.71%   |
| 2016 | 15       | 4.5%    |
| 2014 | 14       | 4.2%    |
| 2022 | 12       | 3.6%    |
| 2011 | 9        | 2.7%    |
| 2015 | 7        | 2.1%    |
| 2009 | 6        | 1.8%    |
| 2008 | 5        | 1.5%    |
| 2007 | 4        | 1.2%    |
| 2023 | 2        | 0.6%    |
| 2010 | 2        | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 333      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 330      | 98.8%   |
| Enabled  | 4        | 1.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 333      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 122      | 36.09%  |
| 32.01-64.0  | 100      | 29.59%  |
| 8.01-16.0   | 45       | 13.31%  |
| 4.01-8.0    | 20       | 5.92%   |
| 24.01-32.0  | 20       | 5.92%   |
| 64.01-256.0 | 18       | 5.33%   |
| 3.01-4.0    | 11       | 3.25%   |
| 1.01-2.0    | 2        | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 103      | 27.99%  |
| 2.01-3.0   | 72       | 19.57%  |
| 3.01-4.0   | 67       | 18.21%  |
| 1.01-2.0   | 67       | 18.21%  |
| 8.01-16.0  | 46       | 12.5%   |
| 16.01-24.0 | 6        | 1.63%   |
| 0.51-1.0   | 5        | 1.36%   |
| 24.01-32.0 | 2        | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 96       | 27.51%  |
| 3      | 78       | 22.35%  |
| 1      | 67       | 19.2%   |
| 4      | 61       | 17.48%  |
| 5      | 28       | 8.02%   |
| 6      | 11       | 3.15%   |
| 7      | 4        | 1.15%   |
| 8      | 2        | 0.57%   |
| 9      | 1        | 0.29%   |
| 0      | 1        | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 264      | 78.57%  |
| Yes       | 72       | 21.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 332      | 99.7%   |
| No        | 1        | 0.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 180      | 53.73%  |
| No        | 155      | 46.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 180      | 53.1%   |
| No        | 159      | 46.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 81       | 24.11%  |
| Germany             | 38       | 11.31%  |
| Italy               | 27       | 8.04%   |
| Canada              | 16       | 4.76%   |
| France              | 15       | 4.46%   |
| Poland              | 11       | 3.27%   |
| Netherlands         | 11       | 3.27%   |
| Belgium             | 11       | 3.27%   |
| Sweden              | 9        | 2.68%   |
| Russia              | 9        | 2.68%   |
| UK                  | 8        | 2.38%   |
| Spain               | 8        | 2.38%   |
| Brazil              | 7        | 2.08%   |
| Austria             | 7        | 2.08%   |
| India               | 6        | 1.79%   |
| Hungary             | 5        | 1.49%   |
| Australia           | 5        | 1.49%   |
| Turkey              | 3        | 0.89%   |
| Switzerland         | 3        | 0.89%   |
| Slovenia            | 3        | 0.89%   |
| Mexico              | 3        | 0.89%   |
| Finland             | 3        | 0.89%   |
| Denmark             | 3        | 0.89%   |
| Argentina           | 3        | 0.89%   |
| Romania             | 2        | 0.6%    |
| Portugal            | 2        | 0.6%    |
| Norway              | 2        | 0.6%    |
| Malaysia            | 2        | 0.6%    |
| Indonesia           | 2        | 0.6%    |
| Hong Kong           | 2        | 0.6%    |
| Czechia             | 2        | 0.6%    |
| Croatia             | 2        | 0.6%    |
| Chile               | 2        | 0.6%    |
| Vietnam             | 1        | 0.3%    |
| UAE                 | 1        | 0.3%    |
| Trinidad and Tobago | 1        | 0.3%    |
| Sri Lanka           | 1        | 0.3%    |
| South Korea         | 1        | 0.3%    |
| South Africa        | 1        | 0.3%    |
| Singapore           | 1        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 6        | 1.68%   |
| Montreal          | 4        | 1.12%   |
| Milan             | 4        | 1.12%   |
| Leipzig           | 4        | 1.12%   |
| Warsaw            | 3        | 0.84%   |
| Turin             | 3        | 0.84%   |
| St Petersburg     | 3        | 0.84%   |
| Ottawa            | 3        | 0.84%   |
| Houston           | 3        | 0.84%   |
| Hamburg           | 3        | 0.84%   |
| Amsterdam         | 3        | 0.84%   |
| Unknown           | 3        | 0.84%   |
| Zurich            | 2        | 0.56%   |
| Wroclaw           | 2        | 0.56%   |
| Vienna            | 2        | 0.56%   |
| Tuen Mun          | 2        | 0.56%   |
| Toronto           | 2        | 0.56%   |
| Sydney            | 2        | 0.56%   |
| Snohomish         | 2        | 0.56%   |
| Schiedam          | 2        | 0.56%   |
| Renton            | 2        | 0.56%   |
| Porth             | 2        | 0.56%   |
| Paris             | 2        | 0.56%   |
| Oldenzaal         | 2        | 0.56%   |
| North Little Rock | 2        | 0.56%   |
| Malmo             | 2        | 0.56%   |
| Madrid            | 2        | 0.56%   |
| Ljubljana         | 2        | 0.56%   |
| Kuala Lumpur      | 2        | 0.56%   |
| Istanbul          | 2        | 0.56%   |
| Gothenburg        | 2        | 0.56%   |
| Geesteren         | 2        | 0.56%   |
| Budapest          | 2        | 0.56%   |
| Brooklyn          | 2        | 0.56%   |
| Barbentane        | 2        | 0.56%   |
| Antwerp           | 2        | 0.56%   |
| Zuidlaren         | 1        | 0.28%   |
| Zapopan           | 1        | 0.28%   |
| Yuzhno-Sakhalinsk | 1        | 0.28%   |
| Wimauma           | 1        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 142      | 255    | 18.76%  |
| Seagate                     | 124      | 188    | 16.38%  |
| WDC                         | 123      | 216    | 16.25%  |
| Kingston                    | 59       | 96     | 7.79%   |
| Crucial                     | 49       | 77     | 6.47%   |
| SanDisk                     | 39       | 52     | 5.15%   |
| Toshiba                     | 29       | 37     | 3.83%   |
| Hitachi                     | 16       | 17     | 2.11%   |
| Intel                       | 14       | 21     | 1.85%   |
| Phison                      | 12       | 13     | 1.59%   |
| Phison Electronics          | 10       | 11     | 1.32%   |
| Micron Technology           | 7        | 9      | 0.92%   |
| Corsair                     | 7        | 7      | 0.92%   |
| China                       | 7        | 7      | 0.92%   |
| A-DATA Technology           | 7        | 13     | 0.92%   |
| SPCC                        | 6        | 6      | 0.79%   |
| HGST                        | 6        | 8      | 0.79%   |
| Unknown                     | 5        | 8      | 0.66%   |
| SK hynix                    | 5        | 7      | 0.66%   |
| Micron/Crucial Technology   | 5        | 12     | 0.66%   |
| Intenso                     | 5        | 7      | 0.66%   |
| XPG                         | 4        | 4      | 0.53%   |
| PNY                         | 4        | 4      | 0.53%   |
| Kingston Technology Company | 4        | 4      | 0.53%   |
| Gigabyte Technology         | 4        | 5      | 0.53%   |
| ADATA Technology            | 4        | 4      | 0.53%   |
| Silicon Motion              | 3        | 3      | 0.4%    |
| Plextor                     | 3        | 4      | 0.4%    |
| Patriot                     | 3        | 4      | 0.4%    |
| OCZ                         | 3        | 3      | 0.4%    |
| Transcend                   | 2        | 3      | 0.26%   |
| SABRENT                     | 2        | 4      | 0.26%   |
| Realtek Semiconductor       | 2        | 2      | 0.26%   |
| Realtek                     | 2        | 3      | 0.26%   |
| LITEON                      | 2        | 2      | 0.26%   |
| Lexar                       | 2        | 2      | 0.26%   |
| Leven                       | 2        | 3      | 0.26%   |
| JMicron Technology          | 2        | 2      | 0.26%   |
| ASMT                        | 2        | 4      | 0.26%   |
| Unknown                     | 2        | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                      | 24       | 2.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 19       | 2.08%   |
| Crucial CT500MX500SSD1 500GB                        | 15       | 1.64%   |
| Samsung SSD 860 EVO 1TB                             | 14       | 1.53%   |
| Samsung SSD 850 EVO 250GB                           | 13       | 1.42%   |
| Samsung SSD 860 EVO 500GB                           | 12       | 1.31%   |
| Kingston SA400S37120G 120GB SSD                     | 12       | 1.31%   |
| Seagate ST4000DM004-2CV104 4TB                      | 11       | 1.2%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 10       | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB                      | 10       | 1.09%   |
| Samsung SSD 850 EVO 500GB                           | 9        | 0.98%   |
| Kingston SA400S37480G 480GB SSD                     | 9        | 0.98%   |
| Kingston SA400S37240G 240GB SSD                     | 9        | 0.98%   |
| Seagate ST2000DM006-2DM164 2TB                      | 7        | 0.77%   |
| Crucial CT1000MX500SSD1 1TB                         | 7        | 0.77%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 6        | 0.66%   |
| Samsung SSD 870 QVO 1TB                             | 6        | 0.66%   |
| Samsung SSD 860 EVO 250GB                           | 6        | 0.66%   |
| Crucial CT240BX500SSD1 240GB                        | 6        | 0.66%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 5        | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 5        | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB                      | 5        | 0.55%   |
| Seagate Expansion Desk 8TB                          | 5        | 0.55%   |
| Samsung SSD 980 500GB                               | 5        | 0.55%   |
| Samsung SSD 870 EVO 1TB                             | 5        | 0.55%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 5        | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 4        | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 4        | 0.44%   |
| Toshiba HDWD110 1TB                                 | 4        | 0.44%   |
| Seagate ST500DM002-1BD142 500GB                     | 4        | 0.44%   |
| Seagate ST1000DM003-1SB102 1TB                      | 4        | 0.44%   |
| Seagate ST1000DM003-1ER162 1TB                      | 4        | 0.44%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 4        | 0.44%   |
| Samsung SSD 980 1TB                                 | 4        | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB                      | 4        | 0.44%   |
| Samsung SSD 970 EVO 500GB                           | 4        | 0.44%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 4        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 4        | 0.44%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 4        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 4        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 123      | 187    | 42.71%  |
| WDC                 | 95       | 154    | 32.99%  |
| Toshiba             | 24       | 28     | 8.33%   |
| Hitachi             | 16       | 17     | 5.56%   |
| Samsung Electronics | 10       | 27     | 3.47%   |
| HGST                | 6        | 8      | 2.08%   |
| Unknown             | 3        | 3      | 1.04%   |
| JMicron Technology  | 2        | 2      | 0.69%   |
| ASMT                | 2        | 4      | 0.69%   |
| PI-041              | 1        | 1      | 0.35%   |
| Maxtor              | 1        | 1      | 0.35%   |
| Maxone              | 1        | 1      | 0.35%   |
| MaxDigital          | 1        | 1      | 0.35%   |
| HPE                 | 1        | 1      | 0.35%   |
| ASMedia             | 1        | 1      | 0.35%   |
| Unknown             | 1        | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 96       | 141    | 30.38%  |
| Kingston            | 46       | 74     | 14.56%  |
| Crucial             | 45       | 65     | 14.24%  |
| WDC                 | 29       | 38     | 9.18%   |
| SanDisk             | 22       | 27     | 6.96%   |
| Intel               | 8        | 12     | 2.53%   |
| China               | 7        | 7      | 2.22%   |
| Micron Technology   | 6        | 8      | 1.9%    |
| Intenso             | 5        | 7      | 1.58%   |
| Toshiba             | 4        | 6      | 1.27%   |
| SPCC                | 4        | 4      | 1.27%   |
| PNY                 | 3        | 3      | 0.95%   |
| Patriot             | 3        | 4      | 0.95%   |
| OCZ                 | 3        | 3      | 0.95%   |
| Gigabyte Technology | 3        | 3      | 0.95%   |
| Corsair             | 3        | 3      | 0.95%   |
| A-DATA Technology   | 3        | 3      | 0.95%   |
| Plextor             | 2        | 3      | 0.63%   |
| Phison              | 2        | 2      | 0.63%   |
| LITEON              | 2        | 2      | 0.63%   |
| Leven               | 2        | 3      | 0.63%   |
| UMAX                | 1        | 1      | 0.32%   |
| Transcend           | 1        | 1      | 0.32%   |
| Timetec             | 1        | 8      | 0.32%   |
| Super Talent        | 1        | 1      | 0.32%   |
| Pioneer             | 1        | 3      | 0.32%   |
| NGFF                | 1        | 1      | 0.32%   |
| Mushkin             | 1        | 1      | 0.32%   |
| MAXSUN              | 1        | 1      | 0.32%   |
| LITEONIT            | 1        | 1      | 0.32%   |
| Lexar               | 1        | 1      | 0.32%   |
| LDLC                | 1        | 1      | 0.32%   |
| Kingmax             | 1        | 4      | 0.32%   |
| Imation             | 1        | 1      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| GOODRAM             | 1        | 1      | 0.32%   |
| Emtec               | 1        | 1      | 0.32%   |
| Drevo               | 1        | 1      | 0.32%   |
| Unknown             | 1        | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 227      | 448    | 37.03%  |
| HDD     | 216      | 437    | 35.24%  |
| NVMe    | 165      | 276    | 26.92%  |
| Unknown | 5        | 8      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 293      | 847    | 59.43%  |
| NVMe | 165      | 269    | 33.47%  |
| SAS  | 35       | 53     | 7.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 203      | 421    | 39.49%  |
| 0.51-1.0   | 158      | 251    | 30.74%  |
| 1.01-2.0   | 80       | 122    | 15.56%  |
| 3.01-4.0   | 32       | 47     | 6.23%   |
| 4.01-10.0  | 20       | 22     | 3.89%   |
| 2.01-3.0   | 18       | 19     | 3.5%    |
| 10.01-20.0 | 3        | 3      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 74       | 21.33%  |
| More than 3000 | 69       | 19.88%  |
| 501-1000       | 54       | 15.56%  |
| 101-250        | 43       | 12.39%  |
| 251-500        | 37       | 10.66%  |
| 2001-3000      | 36       | 10.37%  |
| Unknown        | 17       | 4.9%    |
| 1-20           | 8        | 2.31%   |
| 51-100         | 6        | 1.73%   |
| 21-50          | 3        | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 58       | 15.8%   |
| 501-1000       | 52       | 14.17%  |
| 1-20           | 49       | 13.35%  |
| 101-250        | 43       | 11.72%  |
| 51-100         | 39       | 10.63%  |
| 251-500        | 38       | 10.35%  |
| 21-50          | 33       | 8.99%   |
| More than 3000 | 26       | 7.08%   |
| Unknown        | 17       | 4.63%   |
| 2001-3000      | 12       | 3.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB SSD                                | 2        | 2      | 3.92%   |
| WDC WD20EARX-00PASB0 2TB                                        | 2        | 2      | 3.92%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 2        | 7      | 3.92%   |
| XPG GAMMIX S11 240GB                                            | 1        | 1      | 1.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1        | 1      | 1.96%   |
| WDC WD5000AZRX-00A8LB0 500GB                                    | 1        | 1      | 1.96%   |
| WDC WD5000AVDS-63U7B1 500GB                                     | 1        | 1      | 1.96%   |
| WDC WD40EFRX-68WT0N0 4TB                                        | 1        | 2      | 1.96%   |
| WDC WD2003FZEX-00Z4SA0 2TB                                      | 1        | 1      | 1.96%   |
| WDC WD2002FYPS-01U1B0 2TB                                       | 1        | 1      | 1.96%   |
| WDC WD10EARS-00MVWB0 1TB                                        | 1        | 1      | 1.96%   |
| WDC WD10EACS-00D6B1 1TB                                         | 1        | 1      | 1.96%   |
| WDC WD1003FBYZ-010FB0 1TB                                       | 1        | 2      | 1.96%   |
| WDC WD1002FBYS-02A6B0 1TB                                       | 1        | 1      | 1.96%   |
| WDC WD Blue SA510 2.5 1TB SSD                                   | 1        | 2      | 1.96%   |
| Toshiba DT01ACA300 3TB                                          | 1        | 1      | 1.96%   |
| Toshiba DT01ACA100 1TB                                          | 1        | 1      | 1.96%   |
| Seagate ST9320325AS 320GB                                       | 1        | 4      | 1.96%   |
| Seagate ST6000VX0023-2EF110 6TB                                 | 1        | 1      | 1.96%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1        | 1      | 1.96%   |
| Seagate ST4000DM004-2CV104 4TB                                  | 1        | 1      | 1.96%   |
| Seagate ST3320620AS 320GB                                       | 1        | 1      | 1.96%   |
| Seagate ST3200820AS 200GB                                       | 1        | 1      | 1.96%   |
| Seagate ST2000DX002-2DV164 2TB                                  | 1        | 1      | 1.96%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 1        | 1      | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 1        | 2      | 1.96%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 1        | 1      | 1.96%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 1        | 2      | 1.96%   |
| Samsung Electronics SSD 960 EVO 500GB                           | 1        | 1      | 1.96%   |
| Samsung Electronics SSD 840 Series 120GB                        | 1        | 1      | 1.96%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 1        | 4      | 1.96%   |
| Samsung Electronics HD103SI 1TB                                 | 1        | 1      | 1.96%   |
| Patriot Burst 480GB SSD                                         | 1        | 1      | 1.96%   |
| OCZ VERTEX3 240GB SSD                                           | 1        | 1      | 1.96%   |
| Micron Technology 1100 SATA 512GB SSD                           | 1        | 1      | 1.96%   |
| Kingston SV300S37A120G 120GB SSD                                | 1        | 1      | 1.96%   |
| Intel SSDSC2BB480G7 480GB                                       | 1        | 1      | 1.96%   |
| Hitachi HTS547575A9E384 752GB                                   | 1        | 1      | 1.96%   |
| Hitachi HTS545050A7E380 500GB                                   | 1        | 1      | 1.96%   |
| Hitachi HDT725025VLA380 250GB                                   | 1        | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 18     | 28.57%  |
| Seagate             | 12       | 23     | 24.49%  |
| Samsung Electronics | 4        | 7      | 8.16%   |
| Crucial             | 4        | 12     | 8.16%   |
| Hitachi             | 3        | 3      | 6.12%   |
| Toshiba             | 2        | 2      | 4.08%   |
| XPG                 | 1        | 1      | 2.04%   |
| Patriot             | 1        | 1      | 2.04%   |
| OCZ                 | 1        | 1      | 2.04%   |
| Micron Technology   | 1        | 1      | 2.04%   |
| Kingston            | 1        | 1      | 2.04%   |
| Intel               | 1        | 1      | 2.04%   |
| HGST                | 1        | 3      | 2.04%   |
| Drevo               | 1        | 1      | 2.04%   |
| Corsair             | 1        | 1      | 2.04%   |
| ASMT                | 1        | 2      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 23     | 38.71%  |
| WDC                 | 11       | 13     | 35.48%  |
| Hitachi             | 3        | 3      | 9.68%   |
| Toshiba             | 2        | 2      | 6.45%   |
| Samsung Electronics | 1        | 1      | 3.23%   |
| HGST                | 1        | 3      | 3.23%   |
| ASMT                | 1        | 2      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 29       | 47     | 64.44%  |
| SSD  | 13       | 25     | 28.89%  |
| NVMe | 3        | 6      | 6.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 50%     |
| Samsung Electronics HD252HJ 250GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 230      | 712    | 57.79%  |
| Detected | 124      | 377    | 31.16%  |
| Malfunc  | 42       | 78     | 10.55%  |
| Failed   | 2        | 2      | 0.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 166      | 29.02%  |
| AMD                            | 161      | 28.15%  |
| Samsung Electronics            | 68       | 11.89%  |
| SanDisk                        | 36       | 6.29%   |
| ASMedia Technology             | 33       | 5.77%   |
| Phison Electronics             | 27       | 4.72%   |
| Kingston Technology Company    | 19       | 3.32%   |
| Micron/Crucial Technology      | 9        | 1.57%   |
| ADATA Technology               | 8        | 1.4%    |
| Silicon Motion                 | 6        | 1.05%   |
| Realtek Semiconductor          | 6        | 1.05%   |
| Marvell Technology Group       | 6        | 1.05%   |
| SK hynix                       | 5        | 0.87%   |
| JMicron Technology             | 5        | 0.87%   |
| Toshiba America Info Systems   | 3        | 0.52%   |
| Nvidia                         | 3        | 0.52%   |
| Transcend                      | 2        | 0.35%   |
| Micron Technology              | 2        | 0.35%   |
| MAXIO Technology (Hangzhou)    | 2        | 0.35%   |
| Solid State Storage Technology | 1        | 0.17%   |
| Seagate Technology             | 1        | 0.17%   |
| LSI Logic / Symbios Logic      | 1        | 0.17%   |
| KIOXIA                         | 1        | 0.17%   |
| Broadcom / LSI                 | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 102      | 15.27%  |
| AMD 400 Series Chipset SATA Controller                                         | 55       | 8.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 40       | 5.99%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 32       | 4.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 29       | 4.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 26       | 3.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 18       | 2.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 15       | 2.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15       | 2.25%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 13       | 1.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 12       | 1.8%    |
| Samsung NVMe SSD Controller 980                                                | 12       | 1.8%    |
| Phison E16 PCIe4 NVMe Controller                                               | 12       | 1.8%    |
| Phison E12 NVMe Controller                                                     | 10       | 1.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9        | 1.35%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9        | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8        | 1.2%    |
| Kingston Company A2000 NVMe SSD                                                | 8        | 1.2%    |
| Intel SATA Controller [RAID mode]                                              | 8        | 1.2%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 7        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7        | 1.05%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7        | 1.05%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 7        | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 7        | 1.05%   |
| AMD FCH SATA Controller D                                                      | 6        | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                         | 6        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4        | 0.6%    |
| Phison E18 PCIe4 NVMe Controller                                               | 4        | 0.6%    |
| Kingston Company NVMe Controller                                               | 4        | 0.6%    |
| Intel Volume Management Device NVMe RAID Controller                            | 4        | 0.6%    |
| Intel SSD 660P Series                                                          | 4        | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 0.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4        | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 0.6%    |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 3        | 0.45%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 3        | 0.45%   |
| Kingston Company KC3000/Renegade NVMe SSD                                      | 3        | 0.45%   |
| Kingston Company KC2000/KC2500 NVMe SSD                                        | 3        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 304      | 58.91%  |
| NVMe | 165      | 31.98%  |
| IDE  | 26       | 5.04%   |
| RAID | 17       | 3.29%   |
| SAS  | 4        | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 169      | 50.75%  |
| AMD    | 164      | 49.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 17       | 5.11%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 16       | 4.8%    |
| AMD Ryzen 5 3600 6-Core Processor           | 16       | 4.8%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 10       | 3%      |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 2.7%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 8        | 2.4%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 6        | 1.8%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 5        | 1.5%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.5%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 5        | 1.5%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 5        | 1.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 1.2%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 1.2%    |
| Intel Core i7-10700K CPU @ 3.80GHz          | 4        | 1.2%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 1.2%    |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 1.2%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.2%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 1.2%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.9%    |
| Intel Core i5-7500 CPU @ 3.40GHz            | 3        | 0.9%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 0.9%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 0.9%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 0.9%    |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 3        | 0.9%    |
| AMD Ryzen 7 5700X 8-Core Processor          | 3        | 0.9%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.9%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.6%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.6%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.6%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.6%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.6%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.6%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 2        | 0.6%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.6%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.6%    |
| Intel Core i5-6600 CPU @ 3.30GHz            | 2        | 0.6%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.6%    |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 65       | 19.52%  |
| Intel Core i5           | 57       | 17.12%  |
| AMD Ryzen 7             | 54       | 16.22%  |
| Intel Core i7           | 49       | 14.71%  |
| AMD Ryzen 9             | 26       | 7.81%   |
| Other                   | 15       | 4.5%    |
| Intel Xeon              | 14       | 4.2%    |
| Intel Core i3           | 11       | 3.3%    |
| AMD FX                  | 6        | 1.8%    |
| Intel Celeron           | 5        | 1.5%    |
| AMD Ryzen 3             | 5        | 1.5%    |
| Intel Core 2 Duo        | 4        | 1.2%    |
| Intel Pentium           | 3        | 0.9%    |
| Intel Core i9           | 3        | 0.9%    |
| Intel Core 2 Quad       | 3        | 0.9%    |
| AMD Ryzen Threadripper  | 3        | 0.9%    |
| Intel Pentium Gold      | 1        | 0.3%    |
| Intel Pentium Dual-Core | 1        | 0.3%    |
| Intel Pentium Dual      | 1        | 0.3%    |
| Intel Core m3           | 1        | 0.3%    |
| Intel Core 2            | 1        | 0.3%    |
| AMD Phenom II X4        | 1        | 0.3%    |
| AMD Athlon X4           | 1        | 0.3%    |
| AMD Athlon II X4        | 1        | 0.3%    |
| AMD Athlon              | 1        | 0.3%    |
| AMD A8                  | 1        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 109      | 32.63%  |
| 6      | 83       | 24.85%  |
| 8      | 72       | 21.56%  |
| 2      | 26       | 7.78%   |
| 12     | 24       | 7.19%   |
| 16     | 9        | 2.69%   |
| 10     | 5        | 1.5%    |
| 3      | 3        | 0.9%    |
| 14     | 2        | 0.6%    |
| 32     | 1        | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 329      | 98.5%   |
| 2      | 5        | 1.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 246      | 73.87%  |
| 1      | 87       | 26.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 333      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 140      | 40.7%   |
| 0x08701021 | 29       | 8.43%   |
| 0x306c3    | 19       | 5.52%   |
| 0x0a201009 | 11       | 3.2%    |
| 0x08701013 | 11       | 3.2%    |
| 0x506e3    | 8        | 2.33%   |
| 0x306a9    | 8        | 2.33%   |
| 0x0a20120a | 8        | 2.33%   |
| 0x906ea    | 7        | 2.03%   |
| 0x0a50000c | 7        | 2.03%   |
| 0x0a201016 | 7        | 2.03%   |
| 0x0800820d | 7        | 2.03%   |
| 0x906e9    | 6        | 1.74%   |
| 0x08001138 | 6        | 1.74%   |
| 0xa0655    | 5        | 1.45%   |
| 0x08108109 | 5        | 1.45%   |
| 0x0a601203 | 4        | 1.16%   |
| 0xa0653    | 3        | 0.87%   |
| 0x106a5    | 3        | 0.87%   |
| 0x08701030 | 3        | 0.87%   |
| 0x08001137 | 3        | 0.87%   |
| 0x06000852 | 3        | 0.87%   |
| 0xa0671    | 2        | 0.58%   |
| 0x906ec    | 2        | 0.58%   |
| 0x906eb    | 2        | 0.58%   |
| 0x90672    | 2        | 0.58%   |
| 0x6fd      | 2        | 0.58%   |
| 0x306f2    | 2        | 0.58%   |
| 0x106e5    | 2        | 0.58%   |
| 0x0a601201 | 2        | 0.58%   |
| 0x0a201204 | 2        | 0.58%   |
| 0x08101016 | 2        | 0.58%   |
| 0xb0671    | 1        | 0.29%   |
| 0x906ed    | 1        | 0.29%   |
| 0x706a8    | 1        | 0.29%   |
| 0x706a1    | 1        | 0.29%   |
| 0x6fb      | 1        | 0.29%   |
| 0x6f6      | 1        | 0.29%   |
| 0x6f2      | 1        | 0.29%   |
| 0x406c4    | 1        | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 61       | 18.26%  |
| Zen 3            | 51       | 15.27%  |
| KabyLake         | 38       | 11.38%  |
| Haswell          | 38       | 11.38%  |
| Zen+             | 18       | 5.39%   |
| Zen              | 17       | 5.09%   |
| Unknown          | 17       | 5.09%   |
| Skylake          | 16       | 4.79%   |
| IvyBridge        | 16       | 4.79%   |
| CometLake        | 14       | 4.19%   |
| SandyBridge      | 10       | 2.99%   |
| Core             | 7        | 2.1%    |
| Nehalem          | 5        | 1.5%    |
| Alderlake Hybrid | 5        | 1.5%    |
| Piledriver       | 4        | 1.2%    |
| Penryn           | 4        | 1.2%    |
| Westmere         | 2        | 0.6%    |
| Icelake          | 2        | 0.6%    |
| Goldmont plus    | 2        | 0.6%    |
| Bulldozer        | 2        | 0.6%    |
| Steamroller      | 1        | 0.3%    |
| Silvermont       | 1        | 0.3%    |
| K10 Llano        | 1        | 0.3%    |
| K10              | 1        | 0.3%    |
| Excavator        | 1        | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 172      | 46.87%  |
| AMD    | 132      | 35.97%  |
| Intel  | 63       | 17.17%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 32       | 8.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 5.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 15       | 3.96%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 13       | 3.43%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 13       | 3.43%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 13       | 3.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 2.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 9        | 2.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 2.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 2.37%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 8        | 2.11%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 8        | 2.11%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 6        | 1.58%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 1.58%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 1.32%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 5        | 1.32%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 5        | 1.32%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 5        | 1.32%   |
| Intel HD Graphics 630                                                       | 5        | 1.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 1.32%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.06%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 1.06%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 1.06%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 4        | 1.06%   |
| Intel HD Graphics 530                                                       | 4        | 1.06%   |
| Intel AlderLake-S GT1                                                       | 4        | 1.06%   |
| AMD Raphael                                                                 | 4        | 1.06%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 4        | 1.06%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.79%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 3        | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 0.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 151      | 44.67%  |
| 1 x AMD                  | 111      | 32.84%  |
| 1 x Intel                | 40       | 11.83%  |
| Intel + Nvidia           | 10       | 2.96%   |
| 2 x AMD                  | 9        | 2.66%   |
| AMD + Nvidia             | 7        | 2.07%   |
| Intel + AMD              | 6        | 1.78%   |
| 2 x Nvidia               | 3        | 0.89%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 192      | 57.49%  |
| Proprietary | 142      | 42.51%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 105      | 30.7%   |
| 7.01-8.0   | 70       | 20.47%  |
| 3.01-4.0   | 38       | 11.11%  |
| 8.01-16.0  | 38       | 11.11%  |
| 1.01-2.0   | 34       | 9.94%   |
| 5.01-6.0   | 29       | 8.48%   |
| 0.51-1.0   | 11       | 3.22%   |
| 0.01-0.5   | 11       | 3.22%   |
| 16.01-24.0 | 5        | 1.46%   |
| 2.01-3.0   | 1        | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 69       | 15.97%  |
| Goldstar             | 40       | 9.26%   |
| Acer                 | 40       | 9.26%   |
| Dell                 | 36       | 8.33%   |
| AOC                  | 32       | 7.41%   |
| Ancor Communications | 29       | 6.71%   |
| BenQ                 | 23       | 5.32%   |
| ASUSTek Computer     | 21       | 4.86%   |
| Hewlett-Packard      | 19       | 4.4%    |
| Lenovo               | 10       | 2.31%   |
| ViewSonic            | 9        | 2.08%   |
| Iiyama               | 9        | 2.08%   |
| Gigabyte Technology  | 8        | 1.85%   |
| Vizio                | 7        | 1.62%   |
| LG Electronics       | 7        | 1.62%   |
| Philips              | 6        | 1.39%   |
| Valve                | 3        | 0.69%   |
| Mi                   | 3        | 0.69%   |
| Fujitsu Siemens      | 3        | 0.69%   |
| Eizo                 | 3        | 0.69%   |
| Sony                 | 2        | 0.46%   |
| Sceptre Tech         | 2        | 0.46%   |
| MSI                  | 2        | 0.46%   |
| Lenovo Group Limited | 2        | 0.46%   |
| ITE                  | 2        | 0.46%   |
| HVR                  | 2        | 0.46%   |
| GDH                  | 2        | 0.46%   |
| Denver               | 2        | 0.46%   |
| AOpen                | 2        | 0.46%   |
| Xiaomi               | 1        | 0.23%   |
| XHS                  | 1        | 0.23%   |
| VOXICON              | 1        | 0.23%   |
| Unknown (XXX)        | 1        | 0.23%   |
| Unknown              | 1        | 0.23%   |
| UGD                  | 1        | 0.23%   |
| Toshiba              | 1        | 0.23%   |
| TOL                  | 1        | 0.23%   |
| SKY                  | 1        | 0.23%   |
| SAC                  | 1        | 0.23%   |
| RTK                  | 1        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch   | 5        | 1.08%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch            | 5        | 1.08%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                  | 5        | 1.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 4        | 0.86%   |
| Valve Index HMD VLV91A8                                             | 3        | 0.65%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch   | 3        | 0.65%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch   | 3        | 0.65%   |
| Iiyama PL2792Q IVM6637 2560x1440 600x340mm 27.2-inch                | 3        | 0.65%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch            | 3        | 0.65%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch      | 3        | 0.65%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                    | 3        | 0.65%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                    | 3        | 0.65%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch    | 3        | 0.65%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch       | 2        | 0.43%   |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch       | 2        | 0.43%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch      | 2        | 0.43%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch | 2        | 0.43%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 530x300mm 24.0-inch   | 2        | 0.43%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch   | 2        | 0.43%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch   | 2        | 0.43%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch   | 2        | 0.43%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                    | 2        | 0.43%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch            | 2        | 0.43%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch               | 2        | 0.43%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch          | 2        | 0.43%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch        | 2        | 0.43%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch          | 2        | 0.43%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch           | 2        | 0.43%   |
| Gigabyte Technology M32U GBT3204 3840x2160 697x392mm 31.5-inch      | 2        | 0.43%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch      | 2        | 0.43%   |
| GDH PHILCO GDH0030 1440x900 708x398mm 32.0-inch                     | 2        | 0.43%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                 | 2        | 0.43%   |
| BenQ XL2411Z BNQ7F31 1920x1080 530x300mm 24.0-inch                  | 2        | 0.43%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                   | 2        | 0.43%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                   | 2        | 0.43%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                   | 2        | 0.43%   |
| BenQ G2450H BNQ78AB 1920x1080 530x300mm 24.0-inch                   | 2        | 0.43%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                  | 2        | 0.43%   |
| BenQ EL2870U BNQ7949 3840x2160 620x340mm 27.8-inch                  | 2        | 0.43%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 620x340mm 27.8-inch        | 2        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 184      | 44.88%  |
| 2560x1440 (QHD)    | 65       | 15.85%  |
| 3840x2160 (4K)     | 54       | 13.17%  |
| 1280x1024 (SXGA)   | 13       | 3.17%   |
| 2560x1080          | 12       | 2.93%   |
| Unknown            | 11       | 2.68%   |
| 1680x1050 (WSXGA+) | 10       | 2.44%   |
| 1920x1200 (WUXGA)  | 9        | 2.2%    |
| 1600x900 (HD+)     | 8        | 1.95%   |
| 1440x900 (WXGA+)   | 7        | 1.71%   |
| 3440x1440          | 6        | 1.46%   |
| 1366x768 (WXGA)    | 6        | 1.46%   |
| 3840x1080          | 4        | 0.98%   |
| 1920x540           | 3        | 0.73%   |
| 1360x768           | 3        | 0.73%   |
| 3840x1600          | 2        | 0.49%   |
| 1024x768 (XGA)     | 2        | 0.49%   |
| 9840x3840          | 1        | 0.24%   |
| 5760x1080          | 1        | 0.24%   |
| 4480x1440          | 1        | 0.24%   |
| 3840x2560          | 1        | 0.24%   |
| 3840x1200          | 1        | 0.24%   |
| 3520x1080          | 1        | 0.24%   |
| 3200x1080          | 1        | 0.24%   |
| 2880x1700          | 1        | 0.24%   |
| 2560x1600          | 1        | 0.24%   |
| 2160x1200          | 1        | 0.24%   |
| 1600x1200          | 1        | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 88       | 20.47%  |
| 27      | 86       | 20%     |
| 23      | 43       | 10%     |
| 21      | 36       | 8.37%   |
| Unknown | 32       | 7.44%   |
| 31      | 25       | 5.81%   |
| 34      | 20       | 4.65%   |
| 19      | 14       | 3.26%   |
| 22      | 10       | 2.33%   |
| 54      | 8        | 1.86%   |
| 18      | 8        | 1.86%   |
| 20      | 6        | 1.4%    |
| 17      | 6        | 1.4%    |
| 84      | 5        | 1.16%   |
| 32      | 5        | 1.16%   |
| 40      | 3        | 0.7%    |
| 28      | 3        | 0.7%    |
| 15      | 3        | 0.7%    |
| 72      | 2        | 0.47%   |
| 69      | 2        | 0.47%   |
| 52      | 2        | 0.47%   |
| 49      | 2        | 0.47%   |
| 46      | 2        | 0.47%   |
| 42      | 2        | 0.47%   |
| 37      | 2        | 0.47%   |
| 36      | 2        | 0.47%   |
| 33      | 2        | 0.47%   |
| 74      | 1        | 0.23%   |
| 65      | 1        | 0.23%   |
| 60      | 1        | 0.23%   |
| 50      | 1        | 0.23%   |
| 48      | 1        | 0.23%   |
| 29      | 1        | 0.23%   |
| 26      | 1        | 0.23%   |
| 25      | 1        | 0.23%   |
| 16      | 1        | 0.23%   |
| 13      | 1        | 0.23%   |
| 10      | 1        | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 183      | 46.45%  |
| 401-500     | 65       | 16.5%   |
| 601-700     | 33       | 8.38%   |
| Unknown     | 32       | 8.12%   |
| 701-800     | 29       | 7.36%   |
| 1001-1500   | 18       | 4.57%   |
| 301-350     | 10       | 2.54%   |
| 1501-2000   | 10       | 2.54%   |
| 801-900     | 5        | 1.27%   |
| 351-400     | 5        | 1.27%   |
| 201-300     | 2        | 0.51%   |
| 901-1000    | 2        | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 261      | 72.3%   |
| 16/10   | 33       | 9.14%   |
| Unknown | 27       | 7.48%   |
| 21/9    | 21       | 5.82%   |
| 5/4     | 10       | 2.77%   |
| 4/3     | 3        | 0.83%   |
| 32/9    | 3        | 0.83%   |
| 6/5     | 2        | 0.55%   |
| 3/2     | 1        | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 134      | 32.52%  |
| 301-350        | 88       | 21.36%  |
| 351-500        | 50       | 12.14%  |
| Unknown        | 32       | 7.77%   |
| 251-300        | 26       | 6.31%   |
| More than 1000 | 24       | 5.83%   |
| 151-200        | 24       | 5.83%   |
| 501-1000       | 15       | 3.64%   |
| 141-150        | 13       | 3.16%   |
| 101-110        | 2        | 0.49%   |
| 71-80          | 1        | 0.24%   |
| 41-50          | 1        | 0.24%   |
| 131-140        | 1        | 0.24%   |
| 111-120        | 1        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 218      | 58.6%   |
| 101-120       | 79       | 21.24%  |
| Unknown       | 32       | 8.6%    |
| 1-50          | 18       | 4.84%   |
| 121-160       | 13       | 3.49%   |
| 161-240       | 11       | 2.96%   |
| More than 240 | 1        | 0.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 229      | 66.96%  |
| 2     | 87       | 25.44%  |
| 3     | 23       | 6.73%   |
| 4     | 2        | 0.58%   |
| 0     | 1        | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 223      | 45.42%  |
| Intel                                 | 167      | 34.01%  |
| Qualcomm Atheros                      | 19       | 3.87%   |
| Broadcom                              | 13       | 2.65%   |
| Microsoft                             | 10       | 2.04%   |
| TP-Link                               | 8        | 1.63%   |
| MediaTek                              | 7        | 1.43%   |
| Ralink Technology                     | 5        | 1.02%   |
| ASIX Electronics                      | 5        | 1.02%   |
| Aquantia                              | 4        | 0.81%   |
| Ralink                                | 3        | 0.61%   |
| Xiaomi                                | 2        | 0.41%   |
| OPPO Electronics                      | 2        | 0.41%   |
| Nvidia                                | 2        | 0.41%   |
| Microchip Technology                  | 2        | 0.41%   |
| Google                                | 2        | 0.41%   |
| D-Link                                | 2        | 0.41%   |
| Wilocity                              | 1        | 0.2%    |
| Samsung Electronics                   | 1        | 0.2%    |
| Qualcomm Atheros Communications       | 1        | 0.2%    |
| Oculus VR                             | 1        | 0.2%    |
| NetGear                               | 1        | 0.2%    |
| Motorola PCS                          | 1        | 0.2%    |
| Linksys                               | 1        | 0.2%    |
| InterBiometrics                       | 1        | 0.2%    |
| Huawei Technologies                   | 1        | 0.2%    |
| Exar                                  | 1        | 0.2%    |
| Edimax Technology                     | 1        | 0.2%    |
| DisplayLink                           | 1        | 0.2%    |
| Broadcom Limited                      | 1        | 0.2%    |
| AVM                                   | 1        | 0.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 161      | 27.71%  |
| Realtek RTL8125 2.5GbE Controller                                 | 44       | 7.57%   |
| Intel Wi-Fi 6 AX200                                               | 37       | 6.37%   |
| Intel I211 Gigabit Network Connection                             | 35       | 6.02%   |
| Intel Ethernet Controller I225-V                                  | 17       | 2.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 15       | 2.58%   |
| Intel Ethernet Connection (2) I219-V                              | 15       | 2.58%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 1.72%   |
| Intel Wireless-AC 9260                                            | 9        | 1.55%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 8        | 1.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 0.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 0.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 4        | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.69%   |
| Realtek 802.11ac NIC                                              | 4        | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4        | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 3        | 0.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 0.52%   |
| Intel Wireless 3165                                               | 3        | 0.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3        | 0.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3        | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 0.52%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.34%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.34%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 92       | 47.92%  |
| Realtek Semiconductor                 | 38       | 19.79%  |
| Qualcomm Atheros                      | 11       | 5.73%   |
| Microsoft                             | 10       | 5.21%   |
| Broadcom                              | 10       | 5.21%   |
| TP-Link                               | 7        | 3.65%   |
| MediaTek                              | 7        | 3.65%   |
| Ralink Technology                     | 5        | 2.6%    |
| Ralink                                | 3        | 1.56%   |
| D-Link                                | 2        | 1.04%   |
| Wilocity                              | 1        | 0.52%   |
| Qualcomm Atheros Communications       | 1        | 0.52%   |
| NetGear                               | 1        | 0.52%   |
| Linksys                               | 1        | 0.52%   |
| Edimax Technology                     | 1        | 0.52%   |
| AVM                                   | 1        | 0.52%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 37       | 18.88%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 15       | 7.65%   |
| Intel Wireless-AC 9260                                                                        | 9        | 4.59%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 8        | 4.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 7        | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 6        | 3.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 2.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 4        | 2.04%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 2.04%   |
| Realtek 802.11ac NIC                                                                          | 4        | 2.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.53%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 3        | 1.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 1.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 3        | 1.53%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 1.53%   |
| Intel Wireless 3165                                                                           | 3        | 1.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 3        | 1.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 3        | 1.53%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3        | 1.53%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 3        | 1.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.02%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2        | 1.02%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 1.02%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 2        | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 1.02%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 1.02%   |
| Intel Wireless 8265 / 8275                                                                    | 2        | 1.02%   |
| Intel Wireless 8260                                                                           | 2        | 1.02%   |
| Intel Wireless 7265                                                                           | 2        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2        | 1.02%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 2        | 1.02%   |
| Intel 700 Series Chipset Family Wi-Fi                                                         | 2        | 1.02%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                            | 1        | 0.51%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.51%   |
| TP-Link Archer T4UH v2 [Realtek RTL8812AU]                                                    | 1        | 0.51%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 1        | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 210      | 56.91%  |
| Intel                 | 124      | 33.6%   |
| Qualcomm Atheros      | 10       | 2.71%   |
| ASIX Electronics      | 5        | 1.36%   |
| Aquantia              | 4        | 1.08%   |
| Broadcom              | 3        | 0.81%   |
| Xiaomi                | 2        | 0.54%   |
| OPPO Electronics      | 2        | 0.54%   |
| Nvidia                | 2        | 0.54%   |
| Google                | 2        | 0.54%   |
| TP-Link               | 1        | 0.27%   |
| Samsung Electronics   | 1        | 0.27%   |
| Motorola PCS          | 1        | 0.27%   |
| DisplayLink           | 1        | 0.27%   |
| Broadcom Limited      | 1        | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 161      | 42.48%  |
| Realtek RTL8125 2.5GbE Controller                                   | 44       | 11.61%  |
| Intel I211 Gigabit Network Connection                               | 35       | 9.23%   |
| Intel Ethernet Controller I225-V                                    | 17       | 4.49%   |
| Intel Ethernet Connection (2) I219-V                                | 15       | 3.96%   |
| Intel Ethernet Connection (7) I219-V                                | 11       | 2.9%    |
| Intel Ethernet Connection I217-LM                                   | 10       | 2.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 8        | 2.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 5        | 1.32%   |
| Intel Ethernet Connection (2) I218-V                                | 5        | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 4        | 1.06%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.06%   |
| Intel 82579V Gigabit Network Connection                             | 4        | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                       | 4        | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 0.79%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.53%   |
| OPPO SM6375-QRD _SN:F4A23F05                                        | 2        | 0.53%   |
| Intel Ethernet Controller I226-V                                    | 2        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                               | 2        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 0.53%   |
| Intel Ethernet Connection (14) I219-V                               | 2        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.53%   |
| Google Pixel 7                                                      | 2        | 0.53%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.26%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.26%   |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.26%   |
| Nvidia MCP73 Ethernet                                               | 1        | 0.26%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.26%   |
| Motorola PCS XT1032                                                 | 1        | 0.26%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.26%   |
| Intel Ethernet Connection (5) I219-LM                               | 1        | 0.26%   |
| Intel Ethernet Connection (17) I219-V                               | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 332      | 64.47%  |
| WiFi     | 177      | 34.37%  |
| Modem    | 6        | 1.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 270      | 76.49%  |
| WiFi     | 83       | 23.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 186      | 55.36%  |
| 2     | 125      | 37.2%   |
| 3     | 20       | 5.95%   |
| 4     | 4        | 1.19%   |
| 0     | 1        | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 256      | 75.07%  |
| Yes  | 85       | 24.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 86       | 45.5%   |
| Cambridge Silicon Radio         | 33       | 17.46%  |
| Realtek Semiconductor           | 20       | 10.58%  |
| ASUSTek Computer                | 17       | 8.99%   |
| Broadcom                        | 10       | 5.29%   |
| MediaTek                        | 7        | 3.7%    |
| TP-Link                         | 4        | 2.12%   |
| IMC Networks                    | 3        | 1.59%   |
| HTC (High Tech Computer)        | 3        | 1.59%   |
| Qualcomm Atheros Communications | 2        | 1.06%   |
| Toshiba                         | 1        | 0.53%   |
| Realtek                         | 1        | 0.53%   |
| Edimax Technology               | 1        | 0.53%   |
| Dynex                           | 1        | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 34       | 17.89%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 33       | 17.37%  |
| Realtek Bluetooth Radio                                              | 19       | 10%     |
| Intel AX210 Bluetooth                                                | 15       | 7.89%   |
| Intel Bluetooth wireless interface                                   | 12       | 6.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 8        | 4.21%   |
| MediaTek Wireless_Device                                             | 7        | 3.68%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 7        | 3.68%   |
| Intel AX201 Bluetooth                                                | 7        | 3.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 7        | 3.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 7        | 3.68%   |
| TP-Link UB500 Adapter                                                | 4        | 2.11%   |
| IMC Networks Bluetooth Radio                                         | 3        | 1.58%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 1.58%   |
| ASUS ASUS USB-BT500                                                  | 3        | 1.58%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 1.05%   |
| Intel Bluetooth Device                                               | 2        | 1.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 1.05%   |
| ASUS Bluetooth Device                                                | 2        | 1.05%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1        | 0.53%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.53%   |
| Realtek Bluetooth Radio                                              | 1        | 0.53%   |
| Edimax Bluetooth Adapter                                             | 1        | 0.53%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.53%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 0.53%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 0.53%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.53%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.53%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.53%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.53%   |
| ASUS BCM20702A0                                                      | 1        | 0.53%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter                     | 1        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 196      | 26.78%  |
| Nvidia                               | 168      | 22.95%  |
| Intel                                | 162      | 22.13%  |
| C-Media Electronics                  | 25       | 3.42%   |
| Logitech                             | 19       | 2.6%    |
| SteelSeries ApS                      | 17       | 2.32%   |
| Kingston Technology                  | 13       | 1.78%   |
| Creative Labs                        | 11       | 1.5%    |
| Texas Instruments                    | 9        | 1.23%   |
| Razer USA                            | 8        | 1.09%   |
| JMTek                                | 7        | 0.96%   |
| Blue Microphones                     | 7        | 0.96%   |
| RODE Microphones                     | 6        | 0.82%   |
| Creative Technology                  | 6        | 0.82%   |
| Sony                                 | 5        | 0.68%   |
| Valve Software                       | 4        | 0.55%   |
| Micro Star International             | 4        | 0.55%   |
| KTMicro                              | 3        | 0.41%   |
| Generalplus Technology               | 3        | 0.41%   |
| Focusrite-Novation                   | 3        | 0.41%   |
| XMOS                                 | 2        | 0.27%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.27%   |
| Sennheiser Communications            | 2        | 0.27%   |
| Scarlett                             | 2        | 0.27%   |
| Samson Technologies                  | 2        | 0.27%   |
| Hewlett-Packard                      | 2        | 0.27%   |
| Giga-Byte Technology                 | 2        | 0.27%   |
| FiiO Electronics Technology          | 2        | 0.27%   |
| Elgato Systems                       | 2        | 0.27%   |
| Corsair                              | 2        | 0.27%   |
| Cambridge Silicon Radio              | 2        | 0.27%   |
| BEHRINGER International              | 2        | 0.27%   |
| ASUSTek Computer                     | 2        | 0.27%   |
| Yamaha                               | 1        | 0.14%   |
| Xilinx                               | 1        | 0.14%   |
| VIA Technologies                     | 1        | 0.14%   |
| Trust                                | 1        | 0.14%   |
| TC Electronic                        | 1        | 0.14%   |
| Solid State System                   | 1        | 0.14%   |
| Realtek Semiconductor                | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 93       | 10.86%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 37       | 4.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 33       | 3.86%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 29       | 3.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 28       | 3.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 25       | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 21       | 2.45%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 20       | 2.34%   |
| Intel 200 Series PCH HD Audio                                                                   | 20       | 2.34%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 19       | 2.22%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 17       | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 16       | 1.87%   |
| AMD Navi 10 HDMI Audio                                                                          | 16       | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                                      | 15       | 1.75%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 14       | 1.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 14       | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 12       | 1.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 11       | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 10       | 1.17%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 10       | 1.17%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 10       | 1.17%   |
| Kingston Technology HyperX 7.1 Audio                                                            | 9        | 1.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 9        | 1.05%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 8        | 0.93%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 8        | 0.93%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 7        | 0.82%   |
| Nvidia TU104 HD Audio Controller                                                                | 7        | 0.82%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 7        | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 7        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 7        | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 6        | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                                                   | 6        | 0.7%    |
| Intel Comet Lake PCH-V cAVS                                                                     | 6        | 0.7%    |
| Blue Microphones Yeti Stereo Microphone                                                         | 6        | 0.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 6        | 0.7%    |
| SteelSeries ApS Arctis Pro Wireless                                                             | 5        | 0.58%   |
| Nvidia GP102 HDMI Audio Controller                                                              | 5        | 0.58%   |
| JMTek USB PnP Audio Device                                                                      | 5        | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 5        | 0.58%   |
| C-Media Electronics USB Audio Device                                                            | 5        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 58       | 21.4%   |
| Corsair             | 54       | 19.93%  |
| Kingston            | 37       | 13.65%  |
| Crucial             | 25       | 9.23%   |
| Samsung Electronics | 19       | 7.01%   |
| Unknown             | 15       | 5.54%   |
| SK hynix            | 14       | 5.17%   |
| Patriot             | 9        | 3.32%   |
| Team                | 8        | 2.95%   |
| Micron Technology   | 6        | 2.21%   |
| A-DATA Technology   | 4        | 1.48%   |
| Unknown             | 3        | 1.11%   |
| Ramaxel Technology  | 2        | 0.74%   |
| GOODRAM             | 2        | 0.74%   |
| Golden Empire       | 2        | 0.74%   |
| Wilk                | 1        | 0.37%   |
| Unknown (ABCD)      | 1        | 0.37%   |
| Unknown (0x5846)    | 1        | 0.37%   |
| Strontium           | 1        | 0.37%   |
| PNY                 | 1        | 0.37%   |
| Neo Forza           | 1        | 0.37%   |
| Nanya Technology    | 1        | 0.37%   |
| MAXSUN              | 1        | 0.37%   |
| Kingmax             | 1        | 0.37%   |
| GeIL                | 1        | 0.37%   |
| Avant               | 1        | 0.37%   |
| Apacer              | 1        | 0.37%   |
| AMD                 | 1        | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 11       | 3.62%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s     | 6        | 1.97%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 5        | 1.64%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 5        | 1.64%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 4        | 1.32%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s       | 3        | 0.99%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s         | 3        | 0.99%   |
| G.Skill RAM F4-3600C18-16GTZR 16GB DIMM DDR4 3600MT/s     | 3        | 0.99%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 3        | 0.99%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s      | 3        | 0.99%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 3        | 0.99%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s | 3        | 0.99%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s              | 3        | 0.99%   |
| Unknown                                                   | 3        | 0.99%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 2        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s       | 2        | 0.66%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 2        | 0.66%   |
| SK hynix RAM HMT41GU6AFR8C-PB 8GB DIMM DDR3 1600MT/s      | 2        | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 2        | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s | 2        | 0.66%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s       | 2        | 0.66%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s       | 2        | 0.66%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s       | 2        | 0.66%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s       | 2        | 0.66%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s            | 2        | 0.66%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1648MT/s            | 2        | 0.66%   |
| Patriot RAM 3200 C16 Series 8192MB DIMM DDR4 3266MT/s     | 2        | 0.66%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 2        | 0.66%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 2        | 0.66%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s      | 2        | 0.66%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s    | 2        | 0.66%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s       | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GTZRX 8GB DIMM DDR4 3200MT/s      | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s        | 2        | 0.66%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 2        | 0.66%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4096MB DIMM DDR4 2733MT/s | 2        | 0.66%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s     | 2        | 0.66%   |
| Crucial RAM BL8G32C16U4BL.M8FE 8GB DIMM DDR4 3600MT/s     | 2        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 168      | 69.14%  |
| DDR3    | 48       | 19.75%  |
| DDR5    | 7        | 2.88%   |
| Unknown | 6        | 2.47%   |
| SDRAM   | 5        | 2.06%   |
| DDR2    | 5        | 2.06%   |
| LPDDR4  | 3        | 1.23%   |
| DDR     | 1        | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 224      | 94.51%  |
| SODIMM  | 11       | 4.64%   |
| RIMM    | 1        | 0.42%   |
| FB-DIMM | 1        | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 128      | 49.42%  |
| 16384 | 54       | 20.85%  |
| 4096  | 39       | 15.06%  |
| 32768 | 19       | 7.34%   |
| 2048  | 17       | 6.56%   |
| 1024  | 2        | 0.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 48       | 17.45%  |
| 3600    | 46       | 16.73%  |
| 1600    | 30       | 10.91%  |
| 1333    | 18       | 6.55%   |
| 2667    | 16       | 5.82%   |
| 2400    | 13       | 4.73%   |
| 2133    | 9        | 3.27%   |
| 3533    | 7        | 2.55%   |
| 3400    | 7        | 2.55%   |
| 3866    | 6        | 2.18%   |
| 3733    | 6        | 2.18%   |
| 3800    | 5        | 1.82%   |
| 3266    | 5        | 1.82%   |
| 1800    | 5        | 1.82%   |
| 3000    | 4        | 1.45%   |
| 1867    | 4        | 1.45%   |
| 800     | 4        | 1.45%   |
| 6400    | 2        | 0.73%   |
| 6000    | 2        | 0.73%   |
| 4800    | 2        | 0.73%   |
| 3534    | 2        | 0.73%   |
| 3500    | 2        | 0.73%   |
| 3466    | 2        | 0.73%   |
| 2733    | 2        | 0.73%   |
| 2666    | 2        | 0.73%   |
| 1648    | 2        | 0.73%   |
| 667     | 2        | 0.73%   |
| Unknown | 2        | 0.73%   |
| 65535   | 1        | 0.36%   |
| 49926   | 1        | 0.36%   |
| 5800    | 1        | 0.36%   |
| 4333    | 1        | 0.36%   |
| 4000    | 1        | 0.36%   |
| 3933    | 1        | 0.36%   |
| 3666    | 1        | 0.36%   |
| 3333    | 1        | 0.36%   |
| 3151    | 1        | 0.36%   |
| 3134    | 1        | 0.36%   |
| 3066    | 1        | 0.36%   |
| 2800    | 1        | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 6        | 50%     |
| Hewlett-Packard     | 2        | 16.67%  |
| Canon               | 2        | 16.67%  |
| Prolific Technology | 1        | 8.33%   |
| Pantum              | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Prolific PL2305 Parallel Port | 1        | 8.33%   |
| Pantum P2500W series          | 1        | 8.33%   |
| HP ENVY 5000 series           | 1        | 8.33%   |
| HP ColorLaserJet M253-M254    | 1        | 8.33%   |
| Canon PIXMA MG2500 Series     | 1        | 8.33%   |
| Canon MF260 II Series         | 1        | 8.33%   |
| Brother Printer               | 1        | 8.33%   |
| Brother MFC-L2710DW series    | 1        | 8.33%   |
| Brother MFC-J4535DW           | 1        | 8.33%   |
| Brother HL-2130 series        | 1        | 8.33%   |
| Brother DCP-9020CDW           | 1        | 8.33%   |
| Brother DCP-9015CDW           | 1        | 8.33%   |

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


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 47       | 43.12%  |
| Microdia                               | 10       | 9.17%   |
| Microsoft                              | 7        | 6.42%   |
| Valve Software                         | 4        | 3.67%   |
| Sunplus Innovation Technology          | 3        | 2.75%   |
| Hewlett-Packard                        | 3        | 2.75%   |
| Sunplus IT                             | 2        | 1.83%   |
| Samsung Electronics                    | 2        | 1.83%   |
| MacroSilicon                           | 2        | 1.83%   |
| KYE Systems (Mouse Systems)            | 2        | 1.83%   |
| Huawei Technologies                    | 2        | 1.83%   |
| GEMBIRD                                | 2        | 1.83%   |
| Apple                                  | 2        | 1.83%   |
| Xiaomi                                 | 1        | 0.92%   |
| WCM_USB                                | 1        | 0.92%   |
| Trust                                  | 1        | 0.92%   |
| Tobii Technology AB                    | 1        | 0.92%   |
| Sony                                   | 1        | 0.92%   |
| SN0002                                 | 1        | 0.92%   |
| Realtek Semiconductor                  | 1        | 0.92%   |
| Razer USA                              | 1        | 0.92%   |
| Nikon                                  | 1        | 0.92%   |
| Netchip Technology                     | 1        | 0.92%   |
| LG Electronics                         | 1        | 0.92%   |
| Lenovo                                 | 1        | 0.92%   |
| Leap Motion                            | 1        | 0.92%   |
| Jieli Technology                       | 1        | 0.92%   |
| HTC (High Tech Computer)               | 1        | 0.92%   |
| Google                                 | 1        | 0.92%   |
| EVGA                                   | 1        | 0.92%   |
| Cubeternet                             | 1        | 0.92%   |
| Creative Technology                    | 1        | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.92%   |
| Unknown                                | 1        | 0.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 12       | 10.91%  |
| Logitech Webcam C270                       | 10       | 9.09%   |
| Valve Software 3D Camera                   | 4        | 3.64%   |
| Microdia Webcam Vitade AF                  | 4        | 3.64%   |
| Logitech C922 Pro Stream Webcam            | 4        | 3.64%   |
| Microdia USB 2.0 Camera                    | 3        | 2.73%   |
| Logitech Webcam C310                       | 3        | 2.73%   |
| Logitech HD Webcam C615                    | 3        | 2.73%   |
| Samsung Galaxy series, misc. (MTP mode)    | 2        | 1.82%   |
| Microsoft LifeCam VX-5000                  | 2        | 1.82%   |
| Microsoft LifeCam HD-3000                  | 2        | 1.82%   |
| MacroSilicon USB Video                     | 2        | 1.82%   |
| Logitech Webcam C170                       | 2        | 1.82%   |
| Logitech StreamCam                         | 2        | 1.82%   |
| Logitech BRIO Ultra HD Webcam              | 2        | 1.82%   |
| Logitech BRIO 4K Stream Edition            | 2        | 1.82%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 2        | 1.82%   |
| Huawei HiCamera                            | 2        | 1.82%   |
| HP Webcam HD 2300                          | 2        | 1.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X            | 2        | 1.82%   |
| Xiaomi Mi/Redmi series (PTP + ADB)         | 1        | 0.91%   |
| WCM_USB WEB CAM                            | 1        | 0.91%   |
| Trust Full HD Webcam                       | 1        | 0.91%   |
| Tobii AB EyeChip                           | 1        | 0.91%   |
| Sunplus IT AUKEY PC-LM1 USB Camera         | 1        | 0.91%   |
| Sunplus IT 1080P Webcam                    | 1        | 0.91%   |
| Sunplus USB Camera                         | 1        | 0.91%   |
| Sunplus FULL HD webcam                     | 1        | 0.91%   |
| Sunplus 1080P Webcam                       | 1        | 0.91%   |
| Sony CEVCECM                               | 1        | 0.91%   |
| SN0002 HIK 1080P USB CAMERA                | 1        | 0.91%   |
| Realtek Webcam                             | 1        | 0.91%   |
| Razer USA Gaming Webcam [Kiyo]             | 1        | 0.91%   |
| Nikon D50 (ptp)                            | 1        | 0.91%   |
| Netchip Nuroum V11                         | 1        | 0.91%   |
| Microsoft LifeCam VX-800                   | 1        | 0.91%   |
| Microsoft LifeCam VX-2000                  | 1        | 0.91%   |
| Microsoft LifeCam Cinema                   | 1        | 0.91%   |
| Microdia Integrated Camera                 | 1        | 0.91%   |
| Microdia Hy-UXGA(2601)-Camera              | 1        | 0.91%   |

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


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 2        | 66.67%  |
| HID Global  | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| HID Global USB Reader V3            | 1        | 33.33%  |
| Alcor Micro Watchdata W 1981        | 1        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 294      | 86.47%  |
| 1     | 40       | 11.76%  |
| 2     | 4        | 1.18%   |
| 4     | 1        | 0.29%   |
| 3     | 1        | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 9        | 18.75%  |
| Graphics card         | 7        | 14.58%  |
| Network               | 6        | 12.5%   |
| Net/ethernet          | 5        | 10.42%  |
| Camera                | 4        | 8.33%   |
| Multimedia controller | 3        | 6.25%   |
| Chipcard              | 3        | 6.25%   |
| Bluetooth             | 3        | 6.25%   |
| Unassigned class      | 2        | 4.17%   |
| Sound                 | 2        | 4.17%   |
| Dvb card              | 2        | 4.17%   |
| Storage/nvme          | 1        | 2.08%   |
| Storage               | 1        | 2.08%   |

