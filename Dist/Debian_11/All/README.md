Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linux-bsd)
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

* [ Printers & scanners ](#printers-scanners)
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
| Lenovo        | IdeaPad S540-13ITL 82H1     | Notebook    | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | Notebook    | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | Notebook    | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [52e5d3e16d](https://linux-hardware.org/?probe=52e5d3e16d) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [e7aeecff98](https://linux-hardware.org/?probe=e7aeecff98) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | Notebook    | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | Notebook    | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | Notebook    | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | Notebook    | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | Notebook    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | Desktop     | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| IBM           | I/O Port                    | Server      | [8538814cd6](https://linux-hardware.org/?probe=8538814cd6) | Jul 25, 2021 |
| Dell          | 0Y1057                      | Desktop     | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | Notebook    | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | Desktop     | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | Notebook    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | Desktop     | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f8ad21d44a](https://linux-hardware.org/?probe=f8ad21d44a) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | Notebook    | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | 3110 SDK0J40697 WIN 3305... | All in one  | [84b6274afe](https://linux-hardware.org/?probe=84b6274afe) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Unknown       | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-8-amd64                 | 125       | 39.94%  |
| 5.10.0-7-amd64                 | 96        | 30.67%  |
| 5.10.0-6-amd64                 | 37        | 11.82%  |
| 5.11.22-1-pve                  | 4         | 1.28%   |
| 5.12.0-19.3-liquorix-amd64     | 2         | 0.64%   |
| 5.11.22-2-pve                  | 2         | 0.64%   |
| 5.10.0-8-686                   | 2         | 0.64%   |
| 5.10-sunxi64                   | 2         | 0.64%   |
| 4.19.0-14-amd64                | 2         | 0.64%   |
| 5.9.0-arm-64                   | 1         | 0.32%   |
| 5.8.0-3-amd64                  | 1         | 0.32%   |
| 5.4.18-sunxi64                 | 1         | 0.32%   |
| 5.4.0-73-generic               | 1         | 0.32%   |
| 5.13.5-xanmod1                 | 1         | 0.32%   |
| 5.13.4-e5520                   | 1         | 0.32%   |
| 5.13.4                         | 1         | 0.32%   |
| 5.13.1a                        | 1         | 0.32%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.32%   |
| 5.12.4                         | 1         | 0.32%   |
| 5.12.10                        | 1         | 0.32%   |
| 5.12.1                         | 1         | 0.32%   |
| 5.12.0-9.2-liquorix-amd64      | 1         | 0.32%   |
| 5.12.0-14.2-liquorix-amd64     | 1         | 0.32%   |
| 5.11.9+                        | 1         | 0.32%   |
| 5.11.15-terranz                | 1         | 0.32%   |
| 5.11.15-051115-generic         | 1         | 0.32%   |
| 5.11.14                        | 1         | 0.32%   |
| 5.11.0-rc6                     | 1         | 0.32%   |
| 5.11.0-21.1-liquorix-amd64     | 1         | 0.32%   |
| 5.11.0-16.1-liquorix-amd64     | 1         | 0.32%   |
| 5.10.46custom                  | 1         | 0.32%   |
| 5.10.40-ismynik                | 1         | 0.32%   |
| 5.10.38-falcot                 | 1         | 0.32%   |
| 5.10.35-rockchip64             | 1         | 0.32%   |
| 5.10.21-sunxi                  | 1         | 0.32%   |
| 5.10.12-sunxi                  | 1         | 0.32%   |
| 5.10.0-io7-amd64               | 1         | 0.32%   |
| 5.10.0-8-rt-amd64              | 1         | 0.32%   |
| 5.10.0-8-armmp                 | 1         | 0.32%   |
| 5.10.0-8-686-pae               | 1         | 0.32%   |
| 5.10.0-7-686-pae               | 1         | 0.32%   |
| 5.10.0-6-rt-amd64              | 1         | 0.32%   |
| 5.10.0-6-686                   | 1         | 0.32%   |
| 5.10.0-5-amd64                 | 1         | 0.32%   |
| 5.10.0-4-amd64                 | 1         | 0.32%   |
| 5.10.0-3-amd64                 | 1         | 0.32%   |
| 5.10.0-2-amd64                 | 1         | 0.32%   |
| 4.19.181-z580322               | 1         | 0.32%   |
| 4.19.0-16-amd64                | 1         | 0.32%   |
| 4.19.0-16-686-pae              | 1         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 263       | 86.51%  |
| 5.11.22  | 6         | 1.97%   |
| 4.19.0   | 4         | 1.32%   |
| 5.12.0   | 3         | 0.99%   |
| 5.11.0   | 3         | 0.99%   |
| 5.13.4   | 2         | 0.66%   |
| 5.11.15  | 2         | 0.66%   |
| 5.10     | 2         | 0.66%   |
| 5.9.0    | 1         | 0.33%   |
| 5.8.0    | 1         | 0.33%   |
| 5.4.18   | 1         | 0.33%   |
| 5.4.0    | 1         | 0.33%   |
| 5.13.5   | 1         | 0.33%   |
| 5.13.1   | 1         | 0.33%   |
| 5.13.0   | 1         | 0.33%   |
| 5.12.4   | 1         | 0.33%   |
| 5.12.10  | 1         | 0.33%   |
| 5.12.1   | 1         | 0.33%   |
| 5.11.9   | 1         | 0.33%   |
| 5.11.14  | 1         | 0.33%   |
| 5.10.46  | 1         | 0.33%   |
| 5.10.40  | 1         | 0.33%   |
| 5.10.38  | 1         | 0.33%   |
| 5.10.35  | 1         | 0.33%   |
| 5.10.21  | 1         | 0.33%   |
| 5.10.12  | 1         | 0.33%   |
| 4.19.181 | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 268       | 88.45%  |
| 5.11    | 13        | 4.29%   |
| 5.12    | 6         | 1.98%   |
| 5.13    | 5         | 1.65%   |
| 4.19    | 5         | 1.65%   |
| 5.4     | 2         | 0.66%   |
| 5       | 2         | 0.66%   |
| 5.9     | 1         | 0.33%   |
| 5.8     | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 290       | 95.71%  |
| i686    | 6         | 1.98%   |
| aarch64 | 5         | 1.65%   |
| armv7l  | 2         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 89        | 29.08%  |
| KDE5             | 64        | 20.92%  |
| XFCE             | 35        | 11.44%  |
| MATE             | 27        | 8.82%   |
| Unknown          | 24        | 7.84%   |
| i3               | 11        | 3.59%   |
| KDE              | 10        | 3.27%   |
| LXQt             | 9         | 2.94%   |
| LXDE             | 7         | 2.29%   |
| Cinnamon         | 7         | 2.29%   |
| X-Cinnamon       | 6         | 1.96%   |
| lightdm-xsession | 4         | 1.31%   |
| GNOME Flashback  | 4         | 1.31%   |
| sway             | 2         | 0.65%   |
| openbox          | 2         | 0.65%   |
| Trinity          | 1         | 0.33%   |
| GNUstep          | 1         | 0.33%   |
| default          | 1         | 0.33%   |
| Budgie           | 1         | 0.33%   |
| awesome          | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 198       | 64.92%  |
| Wayland | 71        | 23.28%  |
| Tty     | 26        | 8.52%   |
| Unknown | 10        | 3.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 88        | 28.85%  |
| GDM     | 85        | 27.87%  |
| SDDM    | 65        | 21.31%  |
| Unknown | 55        | 18.03%  |
| LightDM | 8         | 2.62%   |
| XDM     | 2         | 0.66%   |
| SLiM    | 2         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 132       | 43.42%  |
| en_GB   | 23        | 7.57%   |
| ru_RU   | 19        | 6.25%   |
| fr_FR   | 19        | 6.25%   |
| de_DE   | 17        | 5.59%   |
| es_ES   | 10        | 3.29%   |
| pt_BR   | 8         | 2.63%   |
| pl_PL   | 8         | 2.63%   |
| en_IN   | 8         | 2.63%   |
| C       | 6         | 1.97%   |
| Unknown | 5         | 1.64%   |
| it_IT   | 4         | 1.32%   |
| en_CA   | 4         | 1.32%   |
| en_AU   | 4         | 1.32%   |
| tr_TR   | 3         | 0.99%   |
| nl_BE   | 3         | 0.99%   |
| hu_HU   | 3         | 0.99%   |
| de_CH   | 3         | 0.99%   |
| ru_UA   | 2         | 0.66%   |
| ro_RO   | 2         | 0.66%   |
| pt_PT   | 2         | 0.66%   |
| ja_JP   | 2         | 0.66%   |
| en_SG   | 2         | 0.66%   |
| en_HK   | 2         | 0.66%   |
| uk_UA   | 1         | 0.33%   |
| sv_SE   | 1         | 0.33%   |
| sr_RS   | 1         | 0.33%   |
| sk_SK   | 1         | 0.33%   |
| hr_HR   | 1         | 0.33%   |
| fi_FI   | 1         | 0.33%   |
| es_MX   | 1         | 0.33%   |
| es_EC   | 1         | 0.33%   |
| es_CO   | 1         | 0.33%   |
| es_AR   | 1         | 0.33%   |
| en_PH   | 1         | 0.33%   |
| cs_CZ   | 1         | 0.33%   |
| ca_ES   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 189       | 61.97%  |
| BIOS | 116       | 38.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 248       | 81.85%  |
| Btrfs   | 24        | 7.92%   |
| Overlay | 13        | 4.29%   |
| Zfs     | 7         | 2.31%   |
| Xfs     | 4         | 1.32%   |
| Ext3    | 4         | 1.32%   |
| Unknown | 3         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 204       | 66.89%  |
| MBR     | 67        | 21.97%  |
| Unknown | 34        | 11.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 247       | 81.25%  |
| Yes       | 57        | 18.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 70.72%  |
| Yes       | 89        | 29.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 62        | 20.46%  |
| ASUSTek Computer        | 45        | 14.85%  |
| Dell                    | 42        | 13.86%  |
| Hewlett-Packard         | 39        | 12.87%  |
| Gigabyte Technology     | 30        | 9.9%    |
| MSI                     | 17        | 5.61%   |
| ASRock                  | 16        | 5.28%   |
| Acer                    | 10        | 3.3%    |
| Intel                   | 5         | 1.65%   |
| Apple                   | 4         | 1.32%   |
| Toshiba                 | 3         | 0.99%   |
| sunxi                   | 3         | 0.99%   |
| HUAWEI                  | 3         | 0.99%   |
| Supermicro              | 2         | 0.66%   |
| Huanan                  | 2         | 0.66%   |
| Fujitsu                 | 2         | 0.66%   |
| Unknown                 | 2         | 0.66%   |
| UNOWHY                  | 1         | 0.33%   |
| Samsung Electronics     | 1         | 0.33%   |
| Raspberry Pi Foundation | 1         | 0.33%   |
| Quanta                  | 1         | 0.33%   |
| Protectli               | 1         | 0.33%   |
| Pine Microsystems       | 1         | 0.33%   |
| Pegatron                | 1         | 0.33%   |
| PC Specialist           | 1         | 0.33%   |
| Panasonic               | 1         | 0.33%   |
| Monster                 | 1         | 0.33%   |
| Itautec                 | 1         | 0.33%   |
| IBM                     | 1         | 0.33%   |
| HARDKERNEL              | 1         | 0.33%   |
| Compulab                | 1         | 0.33%   |
| Chuwi                   | 1         | 0.33%   |
| Biostar                 | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ASUS All Series                               | 4         | 1.32%   |
| Unknown                                       | 4         | 1.32%   |
| Gigabyte B550I AORUS PRO AX                   | 3         | 0.99%   |
| ASRock B450M Pro4                             | 3         | 0.99%   |
| Lenovo G50-80 80E5                            | 2         | 0.66%   |
| HUAWEI NBLK-WAX9X                             | 2         | 0.66%   |
| HP Z620 Workstation                           | 2         | 0.66%   |
| Gigabyte Z77-D3H                              | 2         | 0.66%   |
| Gigabyte Z370 AORUS Gaming 5                  | 2         | 0.66%   |
| Dell XPS 13 9310                              | 2         | 0.66%   |
| Dell OptiPlex 760                             | 2         | 0.66%   |
| Dell Latitude 7480                            | 2         | 0.66%   |
| Dell Inspiron 3793                            | 2         | 0.66%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA       | 2         | 0.66%   |
| ASUS PRIME B550-PLUS                          | 2         | 0.66%   |
| ASUS PRIME B450M-A                            | 2         | 0.66%   |
| UNOWHY Y13G002S4EI                            | 1         | 0.33%   |
| Toshiba Satellite U800W                       | 1         | 0.33%   |
| Toshiba Satellite S55-A                       | 1         | 0.33%   |
| Toshiba Satellite C45-A                       | 1         | 0.33%   |
| Supermicro SYS-6019P-WT                       | 1         | 0.33%   |
| Supermicro SYS-5038MA-H24TRF                  | 1         | 0.33%   |
| sunxi Banana Pi BPI-M2-Ultra                  | 1         | 0.33%   |
| Samsung 370E4K                                | 1         | 0.33%   |
| RPi Raspberry Pi 2 Model B Rev 1.1            | 1         | 0.33%   |
| Quanta TWC                                    | 1         | 0.33%   |
| Protectli FW6                                 | 1         | 0.33%   |
| Pine Microsystems Pine64 PinePhone (1.2) (DT) | 1         | 0.33%   |
| Pegatron A15                                  | 1         | 0.33%   |
| PC Specialist NV4XMB,ME,MZ                    | 1         | 0.33%   |
| Panasonic CF-AX2LDCZMF                        | 1         | 0.33%   |
| MSI U90/U100                                  | 1         | 0.33%   |
| MSI MS-7C94                                   | 1         | 0.33%   |
| MSI MS-7C56                                   | 1         | 0.33%   |
| MSI MS-7C35                                   | 1         | 0.33%   |
| MSI MS-7B89                                   | 1         | 0.33%   |
| MSI MS-7B46                                   | 1         | 0.33%   |
| MSI MS-7B09                                   | 1         | 0.33%   |
| MSI MS-7A70                                   | 1         | 0.33%   |
| MSI MS-7A40                                   | 1         | 0.33%   |
| MSI MS-7995                                   | 1         | 0.33%   |
| MSI MS-7823                                   | 1         | 0.33%   |
| MSI MS-7759                                   | 1         | 0.33%   |
| MSI MS-7721                                   | 1         | 0.33%   |
| MSI MS-6712                                   | 1         | 0.33%   |
| MSI Modern 15 A11M                            | 1         | 0.33%   |
| MSI GF65 Thin 10UE                            | 1         | 0.33%   |
| MSI CX700                                     | 1         | 0.33%   |
| Monster ABRA A5 V15.2                         | 1         | 0.33%   |
| Lenovo Yoga 710-11ISK 80TX                    | 1         | 0.33%   |
| Lenovo Yoga 530-14IKB 81EK                    | 1         | 0.33%   |
| Lenovo Yoga 300-11IBR 80M1                    | 1         | 0.33%   |
| Lenovo ThinkPad Yoga 260 20FEA02WJP           | 1         | 0.33%   |
| Lenovo ThinkPad X270 W10DG 20K5S41E00         | 1         | 0.33%   |
| Lenovo ThinkPad X260 20F5S46R00               | 1         | 0.33%   |
| Lenovo ThinkPad X260 20F5S0JF00               | 1         | 0.33%   |
| Lenovo ThinkPad X230 2325AZ8                  | 1         | 0.33%   |
| Lenovo ThinkPad X201 3626ES3                  | 1         | 0.33%   |
| Lenovo ThinkPad X1 Tablet 20GGS02600          | 1         | 0.33%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS   | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 43        | 14.19%  |
| Lenovo IdeaPad               | 11        | 3.63%   |
| ASUS PRIME                   | 11        | 3.63%   |
| Dell Inspiron                | 10        | 3.3%    |
| Acer Aspire                  | 9         | 2.97%   |
| HP EliteBook                 | 8         | 2.64%   |
| Dell XPS                     | 8         | 2.64%   |
| Dell OptiPlex                | 7         | 2.31%   |
| Dell Latitude                | 7         | 2.31%   |
| HP ProBook                   | 6         | 1.98%   |
| Dell Precision               | 6         | 1.98%   |
| ASUS ROG                     | 6         | 1.98%   |
| ASUS ZenBook                 | 5         | 1.65%   |
| ASUS VivoBook                | 5         | 1.65%   |
| HP Laptop                    | 4         | 1.32%   |
| HP Compaq                    | 4         | 1.32%   |
| ASUS All                     | 4         | 1.32%   |
| Unknown                      | 4         | 1.32%   |
| Toshiba Satellite            | 3         | 0.99%   |
| Lenovo Yoga                  | 3         | 0.99%   |
| Lenovo ThinkCentre           | 3         | 0.99%   |
| Gigabyte B550I               | 3         | 0.99%   |
| ASRock B450M                 | 3         | 0.99%   |
| Lenovo G50-80                | 2         | 0.66%   |
| HUAWEI NBLK-WAX9X            | 2         | 0.66%   |
| HP ZBook                     | 2         | 0.66%   |
| HP Z620                      | 2         | 0.66%   |
| HP ProLiant                  | 2         | 0.66%   |
| HP 250                       | 2         | 0.66%   |
| Gigabyte Z77-D3H             | 2         | 0.66%   |
| Gigabyte Z370                | 2         | 0.66%   |
| Gigabyte AERO                | 2         | 0.66%   |
| Fujitsu LIFEBOOK             | 2         | 0.66%   |
| Dell PowerEdge               | 2         | 0.66%   |
| ASRock Z97                   | 2         | 0.66%   |
| UNOWHY Y13G002S4EI           | 1         | 0.33%   |
| Supermicro SYS-6019P-WT      | 1         | 0.33%   |
| Supermicro SYS-5038MA-H24TRF | 1         | 0.33%   |
| sunxi Banana                 | 1         | 0.33%   |
| Samsung 370E4K               | 1         | 0.33%   |
| RPi Raspberry                | 1         | 0.33%   |
| Quanta TWC                   | 1         | 0.33%   |
| Protectli FW6                | 1         | 0.33%   |
| Pine Microsystems Pine64     | 1         | 0.33%   |
| Pegatron A15                 | 1         | 0.33%   |
| PC Specialist NV4XMB         | 1         | 0.33%   |
| Panasonic CF-AX2LDCZMF       | 1         | 0.33%   |
| MSI U90                      | 1         | 0.33%   |
| MSI MS-7C94                  | 1         | 0.33%   |
| MSI MS-7C56                  | 1         | 0.33%   |
| MSI MS-7C35                  | 1         | 0.33%   |
| MSI MS-7B89                  | 1         | 0.33%   |
| MSI MS-7B46                  | 1         | 0.33%   |
| MSI MS-7B09                  | 1         | 0.33%   |
| MSI MS-7A70                  | 1         | 0.33%   |
| MSI MS-7A40                  | 1         | 0.33%   |
| MSI MS-7995                  | 1         | 0.33%   |
| MSI MS-7823                  | 1         | 0.33%   |
| MSI MS-7759                  | 1         | 0.33%   |
| MSI MS-7721                  | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 70        | 23.1%   |
| 2021    | 51        | 16.83%  |
| 2019    | 44        | 14.52%  |
| 2018    | 32        | 10.56%  |
| 2012    | 17        | 5.61%   |
| 2016    | 15        | 4.95%   |
| 2014    | 13        | 4.29%   |
| 2013    | 13        | 4.29%   |
| 2011    | 8         | 2.64%   |
| 2017    | 7         | 2.31%   |
| 2015    | 7         | 2.31%   |
| Unknown | 7         | 2.31%   |
| 2009    | 6         | 1.98%   |
| 2010    | 4         | 1.32%   |
| 2008    | 4         | 1.32%   |
| 2007    | 2         | 0.66%   |
| 2006    | 1         | 0.33%   |
| 2004    | 1         | 0.33%   |
| 2001    | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 163       | 53.8%   |
| Desktop        | 113       | 37.29%  |
| Convertible    | 8         | 2.64%   |
| System on chip | 6         | 1.98%   |
| Mini pc        | 4         | 1.32%   |
| Server         | 4         | 1.32%   |
| Tablet         | 2         | 0.66%   |
| All in one     | 2         | 0.66%   |
| Phone          | 1         | 0.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 270       | 88.52%  |
| Enabled  | 35        | 11.48%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 302       | 99.67%  |
| Yes  | 1         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 91        | 30.03%  |
| 4.01-8.0        | 56        | 18.48%  |
| 8.01-16.0       | 50        | 16.5%   |
| 32.01-64.0      | 32        | 10.56%  |
| 3.01-4.0        | 30        | 9.9%    |
| 64.01-256.0     | 21        | 6.93%   |
| 1.01-2.0        | 9         | 2.97%   |
| 2.01-3.0        | 7         | 2.31%   |
| 24.01-32.0      | 3         | 0.99%   |
| 0.01-0.5        | 2         | 0.66%   |
| More than 256.0 | 1         | 0.33%   |
| 0.51-1.0        | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 71        | 23.05%  |
| 4.01-8.0    | 56        | 18.18%  |
| 1.01-2.0    | 56        | 18.18%  |
| 3.01-4.0    | 48        | 15.58%  |
| 8.01-16.0   | 29        | 9.42%   |
| 0.51-1.0    | 26        | 8.44%   |
| 0.01-0.5    | 11        | 3.57%   |
| 16.01-24.0  | 4         | 1.3%    |
| 32.01-64.0  | 3         | 0.97%   |
| 24.01-32.0  | 3         | 0.97%   |
| 64.01-256.0 | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 146       | 48.18%  |
| 2      | 91        | 30.03%  |
| 3      | 27        | 8.91%   |
| 4      | 17        | 5.61%   |
| 5      | 10        | 3.3%    |
| 8      | 5         | 1.65%   |
| 9      | 3         | 0.99%   |
| 6      | 2         | 0.66%   |
| 0      | 2         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 207       | 68.32%  |
| Yes       | 96        | 31.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 253       | 83.5%   |
| No        | 50        | 16.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 70.63%  |
| No        | 89        | 29.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 57.76%  |
| No        | 128       | 42.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country       | Computers | Percent |
|---------------|-----------|---------|
| USA           | 47        | 15.51%  |
| Germany       | 27        | 8.91%   |
| France        | 27        | 8.91%   |
| Russia        | 25        | 8.25%   |
| UK            | 14        | 4.62%   |
| Spain         | 13        | 4.29%   |
| Poland        | 13        | 4.29%   |
| Ukraine       | 11        | 3.63%   |
| Brazil        | 10        | 3.3%    |
| India         | 8         | 2.64%   |
| Netherlands   | 7         | 2.31%   |
| Canada        | 7         | 2.31%   |
| Switzerland   | 5         | 1.65%   |
| Mexico        | 5         | 1.65%   |
| Italy         | 5         | 1.65%   |
| Hungary       | 5         | 1.65%   |
| Greece        | 5         | 1.65%   |
| Australia     | 5         | 1.65%   |
| Thailand      | 4         | 1.32%   |
| Czechia       | 4         | 1.32%   |
| Bulgaria      | 4         | 1.32%   |
| Turkey        | 3         | 0.99%   |
| Portugal      | 3         | 0.99%   |
| Kazakhstan    | 3         | 0.99%   |
| Finland       | 3         | 0.99%   |
| Ecuador       | 3         | 0.99%   |
| Belgium       | 3         | 0.99%   |
| Belarus       | 3         | 0.99%   |
| Austria       | 3         | 0.99%   |
| Argentina     | 3         | 0.99%   |
| Sweden        | 2         | 0.66%   |
| Norway        | 2         | 0.66%   |
| Japan         | 2         | 0.66%   |
| Croatia       | 2         | 0.66%   |
| Vietnam       | 1         | 0.33%   |
| Syria         | 1         | 0.33%   |
| Slovenia      | 1         | 0.33%   |
| Singapore     | 1         | 0.33%   |
| Serbia        | 1         | 0.33%   |
| Romania       | 1         | 0.33%   |
| Philippines   | 1         | 0.33%   |
| New Caledonia | 1         | 0.33%   |
| Mongolia      | 1         | 0.33%   |
| Malaysia      | 1         | 0.33%   |
| Madagascar    | 1         | 0.33%   |
| Indonesia     | 1         | 0.33%   |
| Hong Kong     | 1         | 0.33%   |
| Denmark       | 1         | 0.33%   |
| Colombia      | 1         | 0.33%   |
| China         | 1         | 0.33%   |
| Bangladesh    | 1         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Paris          | 8         | 2.63%   |
| St Petersburg  | 6         | 1.97%   |
| Sofia          | 4         | 1.32%   |
| Lyon           | 4         | 1.32%   |
| Kyiv           | 4         | 1.32%   |
| Ensenada       | 4         | 1.32%   |
| Bengaluru      | 4         | 1.32%   |
| Bangkok        | 4         | 1.32%   |
| Athens         | 4         | 1.32%   |
| Warsaw         | 3         | 0.99%   |
| Vienna         | 3         | 0.99%   |
| Mesa           | 3         | 0.99%   |
| London         | 3         | 0.99%   |
| Kalamazoo      | 3         | 0.99%   |
| Gloucester     | 3         | 0.99%   |
| Waregem        | 2         | 0.66%   |
| Sunnyvale      | 2         | 0.66%   |
| Shizuoka       | 2         | 0.66%   |
| Rio de Janeiro | 2         | 0.66%   |
| Prague         | 2         | 0.66%   |
| Perm           | 2         | 0.66%   |
| Oleksandrivka  | 2         | 0.66%   |
| Noblesville    | 2         | 0.66%   |
| New York       | 2         | 0.66%   |
| Madrid         | 2         | 0.66%   |
| Lublin         | 2         | 0.66%   |
| Las Vegas      | 2         | 0.66%   |
| Hanover        | 2         | 0.66%   |
| Gorinchem      | 2         | 0.66%   |
| Fryazino       | 2         | 0.66%   |
| Cuenca         | 2         | 0.66%   |
| Burnaby        | 2         | 0.66%   |
| Berlin         | 2         | 0.66%   |
| Ankara         | 2         | 0.66%   |
| Érd           | 1         | 0.33%   |
| Zurich         | 1         | 0.33%   |
| Zaragoza       | 1         | 0.33%   |
| Zagreb         | 1         | 0.33%   |
| Woolloongabba  | 1         | 0.33%   |
| Woodstock      | 1         | 0.33%   |
| Wenatchee      | 1         | 0.33%   |
| Waterloo       | 1         | 0.33%   |
| Vladivostok    | 1         | 0.33%   |
| Vitória       | 1         | 0.33%   |
| Vancouver      | 1         | 0.33%   |
| Valladolid     | 1         | 0.33%   |
| Valencia       | 1         | 0.33%   |
| Vaasa          | 1         | 0.33%   |
| Utrecht        | 1         | 0.33%   |
| Ulyanovsk      | 1         | 0.33%   |
| Ufa            | 1         | 0.33%   |
| Tyumen         | 1         | 0.33%   |
| Turku          | 1         | 0.33%   |
| Turin          | 1         | 0.33%   |
| Toulouse       | 1         | 0.33%   |
| Toul           | 1         | 0.33%   |
| Toronto        | 1         | 0.33%   |
| Thonex         | 1         | 0.33%   |
| Thionville     | 1         | 0.33%   |
| The Hague      | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 82        | 114    | 17.67%  |
| WDC                 | 76        | 113    | 16.38%  |
| Seagate             | 64        | 97     | 13.79%  |
| Toshiba             | 32        | 46     | 6.9%    |
| Crucial             | 25        | 27     | 5.39%   |
| Kingston            | 24        | 28     | 5.17%   |
| Unknown             | 23        | 33     | 4.96%   |
| Intel               | 16        | 23     | 3.45%   |
| Sandisk             | 13        | 15     | 2.8%    |
| SK Hynix            | 11        | 13     | 2.37%   |
| Hitachi             | 11        | 12     | 2.37%   |
| A-DATA Technology   | 10        | 14     | 2.16%   |
| HGST                | 8         | 10     | 1.72%   |
| Micron Technology   | 5         | 5      | 1.08%   |
| Transcend           | 4         | 5      | 0.86%   |
| China               | 4         | 4      | 0.86%   |
| Phison              | 3         | 6      | 0.65%   |
| Patriot             | 3         | 3      | 0.65%   |
| LITEONIT            | 3         | 3      | 0.65%   |
| KIOXIA              | 3         | 3      | 0.65%   |
| Intenso             | 3         | 3      | 0.65%   |
| Gigabyte Technology | 3         | 3      | 0.65%   |
| Apple               | 3         | 3      | 0.65%   |
| Union Memory        | 2         | 2      | 0.43%   |
| SPCC                | 2         | 2      | 0.43%   |
| PNY                 | 2         | 2      | 0.43%   |
| Phison Electronics  | 2         | 2      | 0.43%   |
| LITEON              | 2         | 2      | 0.43%   |
| Lenovo              | 2         | 2      | 0.43%   |
| JMicron             | 2         | 2      | 0.43%   |
| Corsair             | 2         | 2      | 0.43%   |
| ZTC                 | 1         | 1      | 0.22%   |
| XPG                 | 1         | 1      | 0.22%   |
| TrueNAS             | 1         | 1      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| SILICONMOTION       | 1         | 1      | 0.22%   |
| Silicon Motion      | 1         | 2      | 0.22%   |
| SABRENT             | 1         | 1      | 0.22%   |
| Maxtor              | 1         | 2      | 0.22%   |
| Maximus             | 1         | 1      | 0.22%   |
| MaxDigital          | 1         | 2      | 0.22%   |
| Lexar               | 1         | 1      | 0.22%   |
| LDLC                | 1         | 1      | 0.22%   |
| KingDian            | 1         | 1      | 0.22%   |
| IBM-ESXS            | 1         | 2      | 0.22%   |
| Fujitsu             | 1         | 1      | 0.22%   |
| DOGFISH             | 1         | 1      | 0.22%   |
| ASUS-PHISON         | 1         | 1      | 0.22%   |
| Apacer              | 1         | 1      | 0.22%   |
| AMD                 | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB                      | 10        | 1.85%   |
| Samsung SSD 970 EVO Plus 1TB                 | 9         | 1.66%   |
| Samsung SSD 850 EVO 250GB                    | 7         | 1.29%   |
| Samsung SSD 970 EVO Plus 500GB               | 6         | 1.11%   |
| Samsung SSD 850 EVO 500GB                    | 6         | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 4         | 0.74%   |
| Samsung SSD 860 EVO 500GB                    | 4         | 0.74%   |
| Samsung SSD 860 EVO 250GB                    | 4         | 0.74%   |
| Kingston SV300S37A240G 240GB SSD             | 4         | 0.74%   |
| Kingston SA400S37240G 240GB SSD              | 4         | 0.74%   |
| Crucial CT500MX500SSD1 500GB                 | 4         | 0.74%   |
| Crucial CT1000MX500SSD1 1TB                  | 4         | 0.74%   |
| WDC WDS500G3X0C-00SJG0 500GB                 | 3         | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 3         | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 3         | 0.55%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 3         | 0.55%   |
| Unknown DA4064  64GB                         | 3         | 0.55%   |
| Toshiba MQ04ABF100 1TB                       | 3         | 0.55%   |
| Toshiba HDWD110 1TB                          | 3         | 0.55%   |
| Toshiba DT01ACA200 2TB                       | 3         | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB               | 3         | 0.55%   |
| Seagate ST2000LX001-1RG174 2TB               | 3         | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB               | 3         | 0.55%   |
| Samsung SSD 840 PRO Series 256GB             | 3         | 0.55%   |
| Hitachi HUS724040ALE641 4TB                  | 3         | 0.55%   |
| HGST HTS721010A9E630 1TB                     | 3         | 0.55%   |
| Crucial CT500P1SSD8 500GB                    | 3         | 0.55%   |
| Crucial CT1000P1SSD8 1TB                     | 3         | 0.55%   |
| WDC WDS500G2B0C-00PXH0 500GB                 | 2         | 0.37%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 2         | 0.37%   |
| WDC WD20EARX-00PASB0 2TB                     | 2         | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 2         | 0.37%   |
| WDC WD10EFRX-68FYTN0 1TB                     | 2         | 0.37%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 2         | 0.37%   |
| Unknown SL16G  16GB                          | 2         | 0.37%   |
| Unknown MMC Card  64GB                       | 2         | 0.37%   |
| Unknown MMC Card  32GB                       | 2         | 0.37%   |
| Toshiba MQ01ACF032 320GB                     | 2         | 0.37%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 0.37%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB      | 2         | 0.37%   |
| Toshiba DT01ACA300 3TB                       | 2         | 0.37%   |
| Seagate ST500DM002-1BD142 500GB              | 2         | 0.37%   |
| Seagate ST3000DM001-1CH166 3TB               | 2         | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB               | 2         | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB               | 2         | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB               | 2         | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB               | 2         | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB               | 2         | 0.37%   |
| Seagate BUP Slim BL 2TB                      | 2         | 0.37%   |
| Seagate BarraCuda 120 SSD ZA250CM10003 250GB | 2         | 0.37%   |
| Seagate Backup+ Hub BK 4TB                   | 2         | 0.37%   |
| SanDisk Ultra 3D NVMe 1TB                    | 2         | 0.37%   |
| SanDisk SSD PLUS 240GB                       | 2         | 0.37%   |
| Sandisk NVMe SSD Drive 1TB                   | 2         | 0.37%   |
| Samsung SSD 970 EVO Plus 250GB               | 2         | 0.37%   |
| Samsung SSD 970 EVO 500GB                    | 2         | 0.37%   |
| Samsung SSD 970 EVO 1TB                      | 2         | 0.37%   |
| Samsung SSD 860 EVO 2TB                      | 2         | 0.37%   |
| Samsung SSD 850 EVO M.2 250GB                | 2         | 0.37%   |
| Samsung MZALQ256HAJD-000L1 256GB             | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 82     | 36.02%  |
| WDC                 | 53        | 80     | 32.92%  |
| Toshiba             | 21        | 34     | 13.04%  |
| Hitachi             | 11        | 12     | 6.83%   |
| HGST                | 8         | 10     | 4.97%   |
| Samsung Electronics | 6         | 7      | 3.73%   |
| SILICONMOTION       | 1         | 1      | 0.62%   |
| MaxDigital          | 1         | 2      | 0.62%   |
| IBM-ESXS            | 1         | 2      | 0.62%   |
| Fujitsu             | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 66     | 29.19%  |
| Kingston            | 19        | 23     | 11.8%   |
| Crucial             | 18        | 19     | 11.18%  |
| WDC                 | 11        | 14     | 6.83%   |
| SanDisk             | 8         | 9      | 4.97%   |
| A-DATA Technology   | 6         | 7      | 3.73%   |
| Intel               | 5         | 5      | 3.11%   |
| Transcend           | 4         | 5      | 2.48%   |
| China               | 4         | 4      | 2.48%   |
| Toshiba             | 3         | 4      | 1.86%   |
| Seagate             | 3         | 3      | 1.86%   |
| Patriot             | 3         | 3      | 1.86%   |
| LITEONIT            | 3         | 3      | 1.86%   |
| SK Hynix            | 2         | 2      | 1.24%   |
| Micron Technology   | 2         | 2      | 1.24%   |
| Intenso             | 2         | 2      | 1.24%   |
| Apple               | 2         | 2      | 1.24%   |
| ZTC                 | 1         | 1      | 0.62%   |
| Unknown             | 1         | 1      | 0.62%   |
| Union Memory        | 1         | 1      | 0.62%   |
| TrueNAS             | 1         | 1      | 0.62%   |
| Team                | 1         | 1      | 0.62%   |
| SPCC                | 1         | 1      | 0.62%   |
| PNY                 | 1         | 1      | 0.62%   |
| Maxtor              | 1         | 2      | 0.62%   |
| Maximus             | 1         | 1      | 0.62%   |
| LITEON              | 1         | 1      | 0.62%   |
| Lexar               | 1         | 1      | 0.62%   |
| LDLC                | 1         | 1      | 0.62%   |
| KingDian            | 1         | 1      | 0.62%   |
| JMicron             | 1         | 1      | 0.62%   |
| Gigabyte Technology | 1         | 1      | 0.62%   |
| DOGFISH             | 1         | 1      | 0.62%   |
| ASUS-PHISON         | 1         | 1      | 0.62%   |
| Apacer              | 1         | 1      | 0.62%   |
| AMD                 | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 148       | 193    | 34.02%  |
| HDD     | 137       | 231    | 31.49%  |
| NVMe    | 121       | 151    | 27.82%  |
| MMC     | 21        | 32     | 4.83%   |
| Unknown | 8         | 15     | 1.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 212       | 409    | 56.84%  |
| NVMe | 120       | 150    | 32.17%  |
| MMC  | 21        | 32     | 5.63%   |
| SAS  | 20        | 31     | 5.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 146       | 207    | 48.99%  |
| 0.51-1.0   | 89        | 112    | 29.87%  |
| 1.01-2.0   | 34        | 42     | 11.41%  |
| 3.01-4.0   | 12        | 25     | 4.03%   |
| 2.01-3.0   | 8         | 13     | 2.68%   |
| 4.01-10.0  | 6         | 17     | 2.01%   |
| 10.01-20.0 | 3         | 8      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 69        | 22.62%  |
| 101-250        | 54        | 17.7%   |
| 501-1000       | 42        | 13.77%  |
| 1001-2000      | 38        | 12.46%  |
| More than 3000 | 30        | 9.84%   |
| 1-20           | 21        | 6.89%   |
| 51-100         | 19        | 6.23%   |
| 21-50          | 14        | 4.59%   |
| Unknown        | 10        | 3.28%   |
| 2001-3000      | 8         | 2.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 26.54%  |
| 101-250        | 47        | 15.21%  |
| 21-50          | 41        | 13.27%  |
| 251-500        | 32        | 10.36%  |
| 51-100         | 32        | 10.36%  |
| 501-1000       | 26        | 8.41%   |
| 1001-2000      | 17        | 5.5%    |
| More than 3000 | 12        | 3.88%   |
| Unknown        | 10        | 3.24%   |
| 2001-3000      | 7         | 2.27%   |
| 0              | 3         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5003ABYX-18WERA0 500GB                 | 1         | 2      | 1.92%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.92%   |
| WDC WD5000AAKS-22V1A0 500GB                  | 1         | 1      | 1.92%   |
| WDC WD5000AAJS-22A8B0 500GB                  | 1         | 1      | 1.92%   |
| WDC WD400BB-00DEA0 40GB                      | 1         | 1      | 1.92%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 1.92%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.92%   |
| WDC WD20EARS-00MVWB0 2TB                     | 1         | 1      | 1.92%   |
| WDC WD1600AAJS-00L7A0 160GB                  | 1         | 1      | 1.92%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 1.92%   |
| WDC WD10JPVT-75A1YT0 1TB                     | 1         | 1      | 1.92%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 1         | 1      | 1.92%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1         | 1      | 1.92%   |
| WDC WD1001FALS-75J7B0 1TB                    | 1         | 1      | 1.92%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 1.92%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 1.92%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 1.92%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1      | 1.92%   |
| SK Hynix PC401 NVMe 512GB                    | 1         | 2      | 1.92%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.92%   |
| Seagate ST9160310AS 160GB                    | 1         | 1      | 1.92%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 1.92%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 1.92%   |
| Seagate ST3200827AS 200GB                    | 1         | 1      | 1.92%   |
| Seagate ST32000542AS 2TB                     | 1         | 1      | 1.92%   |
| Seagate ST31500341AS 1TB                     | 1         | 1      | 1.92%   |
| Seagate ST3120827AS 120GB                    | 1         | 1      | 1.92%   |
| Seagate ST31000333AS 1TB                     | 1         | 1      | 1.92%   |
| Seagate ST3000DM001-9YN166 3TB               | 1         | 1      | 1.92%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.92%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 1.92%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 1.92%   |
| SanDisk SSD PLUS 120 GB                      | 1         | 1      | 1.92%   |
| Samsung Electronics SSD 970 EVO 250GB        | 1         | 1      | 1.92%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 1.92%   |
| Samsung Electronics HD161GJ 160GB            | 1         | 1      | 1.92%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 1.92%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 1.92%   |
| KingDian S280 240GB                          | 1         | 1      | 1.92%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 1.92%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 1.92%   |
| Intel SSDPEKKW010T7 1TB                      | 1         | 2      | 1.92%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 1.92%   |
| Hitachi HTS543212L9A300 120GB                | 1         | 1      | 1.92%   |
| Hitachi HDS722525VLAT80 250GB                | 1         | 1      | 1.92%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 1.92%   |
| A-DATA Technology SU800 256GB SSD            | 1         | 2      | 1.92%   |
| A-DATA Technology SU630 480GB SSD            | 1         | 1      | 1.92%   |
| A-DATA Technology SSD DP900 128GB-DL3        | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 16     | 27.45%  |
| Seagate             | 14        | 15     | 27.45%  |
| Toshiba             | 5         | 5      | 9.8%    |
| Samsung Electronics | 3         | 4      | 5.88%   |
| Intel               | 3         | 4      | 5.88%   |
| Hitachi             | 3         | 3      | 5.88%   |
| A-DATA Technology   | 3         | 4      | 5.88%   |
| SK Hynix            | 1         | 2      | 1.96%   |
| SanDisk             | 1         | 1      | 1.96%   |
| LITEONIT            | 1         | 1      | 1.96%   |
| Kingston            | 1         | 1      | 1.96%   |
| KingDian            | 1         | 1      | 1.96%   |
| HGST                | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 16     | 36.84%  |
| Seagate             | 14        | 15     | 36.84%  |
| Toshiba             | 5         | 5      | 13.16%  |
| Hitachi             | 3         | 3      | 7.89%   |
| Samsung Electronics | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 41     | 74%     |
| SSD  | 10        | 12     | 20%     |
| NVMe | 3         | 5      | 6%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500830AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 244       | 450    | 68.93%  |
| Detected | 61        | 113    | 17.23%  |
| Malfunc  | 48        | 58     | 13.56%  |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 192       | 49.87%  |
| AMD                          | 55        | 14.29%  |
| Samsung Electronics          | 42        | 10.91%  |
| Sandisk                      | 20        | 5.19%   |
| Phison Electronics           | 10        | 2.6%    |
| SK Hynix                     | 9         | 2.34%   |
| Micron/Crucial Technology    | 8         | 2.08%   |
| Toshiba America Info Systems | 7         | 1.82%   |
| ASMedia Technology           | 6         | 1.56%   |
| Kingston Technology Company  | 5         | 1.3%    |
| ADATA Technology             | 5         | 1.3%    |
| Marvell Technology Group     | 4         | 1.04%   |
| KIOXIA                       | 4         | 1.04%   |
| Broadcom / LSI               | 4         | 1.04%   |
| Micron Technology            | 3         | 0.78%   |
| JMicron Technology           | 3         | 0.78%   |
| Lenovo                       | 2         | 0.52%   |
| VIA Technologies             | 1         | 0.26%   |
| Union Memory (Shenzhen)      | 1         | 0.26%   |
| Silicon Motion               | 1         | 0.26%   |
| Seagate Technology           | 1         | 0.26%   |
| Lite-On Technology           | 1         | 0.26%   |
| Adaptec                      | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 40        | 8.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 6.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 20        | 4.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 3.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 3.14%   |
| AMD 400 Series Chipset SATA Controller                                         | 14        | 3.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 2.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9         | 2.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 1.79%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 8         | 1.79%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.57%   |
| Phison E12 NVMe Controller                                                     | 7         | 1.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 1.57%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 6         | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.35%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 6         | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1.12%   |
| Samsung NVMe Controller                                                        | 5         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.12%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                         | 5         | 1.12%   |
| KIOXIA Non-Volatile memory controller                                          | 4         | 0.9%    |
| Intel SATA Controller [RAID mode]                                              | 4         | 0.9%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.9%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 0.9%    |
| SK Hynix NVMe SSD Controller                                                   | 3         | 0.67%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 3         | 0.67%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.67%   |
| Micron Non-Volatile memory controller                                          | 3         | 0.67%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.67%   |
| Intel SSD 600P Series                                                          | 3         | 0.67%   |
| Intel NVMe Optane Memory Series                                                | 3         | 0.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.67%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 3         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.67%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 0.67%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.45%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.45%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 0.45%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.45%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2         | 0.45%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 0.45%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 0.45%   |
| Intel SSD 660P Series                                                          | 2         | 0.45%   |
| Intel Non-Volatile memory controller                                           | 2         | 0.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 0.45%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 2         | 0.45%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2         | 0.45%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 209       | 53.45%  |
| NVMe | 120       | 30.69%  |
| RAID | 30        | 7.67%   |
| IDE  | 26        | 6.65%   |
| SAS  | 6         | 1.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 227       | 74.92%  |
| AMD    | 69        | 22.77%  |
| ARM    | 7         | 2.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 9         | 2.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 7         | 2.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 7         | 2.31%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 6         | 1.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 6         | 1.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 1.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 5         | 1.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 5         | 1.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 1.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 4         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 4         | 1.32%   |
| ARM Processor                                   | 4         | 1.32%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 4         | 1.32%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 4         | 1.32%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 3         | 0.99%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 3         | 0.99%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 3         | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 3         | 0.99%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 3         | 0.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 0.99%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 3         | 0.99%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 3         | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 2         | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 2         | 0.66%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 2         | 0.66%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 2         | 0.66%   |
| Intel Core i7-3537U CPU @ 2.00GHz               | 2         | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 0.66%   |
| Intel Core i7-10710U CPU @ 1.10GHz              | 2         | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 0.66%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 2         | 0.66%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 2         | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2         | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 2         | 0.66%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 2         | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 0.66%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 2         | 0.66%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 0.66%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 2         | 0.66%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 0.66%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 2         | 0.66%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz            | 2         | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2         | 0.66%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 0.66%   |
| Intel Celeron M processor 900MHz                | 2         | 0.66%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 0.66%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 2         | 0.66%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2         | 0.66%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 2         | 0.66%   |
| Intel Xeon W-2145 CPU @ 3.70GHz                 | 1         | 0.33%   |
| Intel Xeon Silver 4215R CPU @ 3.20GHz           | 1         | 0.33%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                | 1         | 0.33%   |
| Intel Xeon CPU W3503 @ 2.40GHz                  | 1         | 0.33%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz             | 1         | 0.33%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz             | 1         | 0.33%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz             | 1         | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 84        | 27.72%  |
| Intel Core i7          | 65        | 21.45%  |
| AMD Ryzen 5            | 25        | 8.25%   |
| Other                  | 19        | 6.27%   |
| AMD Ryzen 7            | 14        | 4.62%   |
| Intel Core i3          | 13        | 4.29%   |
| Intel Xeon             | 12        | 3.96%   |
| Intel Celeron          | 12        | 3.96%   |
| Intel Pentium          | 7         | 2.31%   |
| Intel Core 2 Duo       | 7         | 2.31%   |
| AMD Ryzen 7 PRO        | 6         | 1.98%   |
| AMD Ryzen 9            | 5         | 1.65%   |
| AMD Ryzen 3            | 4         | 1.32%   |
| Intel Atom             | 3         | 0.99%   |
| Intel Core 2 Quad      | 2         | 0.66%   |
| Intel Celeron M        | 2         | 0.66%   |
| AMD Ryzen Threadripper | 2         | 0.66%   |
| AMD Phenom II X4       | 2         | 0.66%   |
| AMD FX                 | 2         | 0.66%   |
| Intel Xeon Silver      | 1         | 0.33%   |
| Intel Pentium M        | 1         | 0.33%   |
| Intel Pentium 4        | 1         | 0.33%   |
| Intel Core m7          | 1         | 0.33%   |
| Intel Core i9          | 1         | 0.33%   |
| Intel Core 2           | 1         | 0.33%   |
| ARM BCM                | 1         | 0.33%   |
| ARM Allwinner          | 1         | 0.33%   |
| ARM AArch64            | 1         | 0.33%   |
| AMD C-30               | 1         | 0.33%   |
| AMD Athlon XP          | 1         | 0.33%   |
| AMD Athlon X4          | 1         | 0.33%   |
| AMD Athlon II Neo      | 1         | 0.33%   |
| AMD A8                 | 1         | 0.33%   |
| AMD A6                 | 1         | 0.33%   |
| AMD A12                | 1         | 0.33%   |
| AMD A10                | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 125       | 41.25%  |
| 2      | 94        | 31.02%  |
| 6      | 39        | 12.87%  |
| 8      | 24        | 7.92%   |
| 1      | 9         | 2.97%   |
| 12     | 6         | 1.98%   |
| 16     | 3         | 0.99%   |
| 44     | 1         | 0.33%   |
| 32     | 1         | 0.33%   |
| 28     | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 297       | 98.02%  |
| 2      | 6         | 1.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 222       | 73.27%  |
| 1      | 81        | 26.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 293       | 96.7%   |
| 32-bit         | 6         | 1.98%   |
| 64-bit         | 2         | 0.66%   |
| Unknown        | 2         | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 21.24%  |
| 0x306a9    | 24        | 7.84%   |
| 0x206a7    | 16        | 5.23%   |
| 0x08701021 | 14        | 4.58%   |
| 0x306c3    | 13        | 4.25%   |
| 0x806c1    | 11        | 3.59%   |
| 0x406e3    | 9         | 2.94%   |
| 0x806ec    | 8         | 2.61%   |
| 0x806ea    | 8         | 2.61%   |
| 0x306d4    | 8         | 2.61%   |
| 0x906ea    | 7         | 2.29%   |
| 0x706e5    | 7         | 2.29%   |
| 0x906e9    | 6         | 1.96%   |
| 0x806e9    | 6         | 1.96%   |
| 0x506e3    | 6         | 1.96%   |
| 0x08108109 | 6         | 1.96%   |
| 0x806eb    | 5         | 1.63%   |
| 0x506c9    | 5         | 1.63%   |
| 0x206d7    | 5         | 1.63%   |
| 0x08600106 | 5         | 1.63%   |
| 0xa0652    | 4         | 1.31%   |
| 0x40651    | 4         | 1.31%   |
| 0x306f2    | 3         | 0.98%   |
| 0x20655    | 3         | 0.98%   |
| 0x1067a    | 3         | 0.98%   |
| 0x0800820d | 3         | 0.98%   |
| 0x08001138 | 3         | 0.98%   |
| 0x06003106 | 3         | 0.98%   |
| 0xa0660    | 2         | 0.65%   |
| 0x706a8    | 2         | 0.65%   |
| 0x6fb      | 2         | 0.65%   |
| 0x6d8      | 2         | 0.65%   |
| 0x406c4    | 2         | 0.65%   |
| 0x0a201009 | 2         | 0.65%   |
| 0x08701013 | 2         | 0.65%   |
| 0x010000c8 | 2         | 0.65%   |
| 0xf29      | 1         | 0.33%   |
| 0xa0671    | 1         | 0.33%   |
| 0xa0653    | 1         | 0.33%   |
| 0x906ed    | 1         | 0.33%   |
| 0x906ec    | 1         | 0.33%   |
| 0x706a1    | 1         | 0.33%   |
| 0x6f6      | 1         | 0.33%   |
| 0x695      | 1         | 0.33%   |
| 0x50657    | 1         | 0.33%   |
| 0x50654    | 1         | 0.33%   |
| 0x406f1    | 1         | 0.33%   |
| 0x406d8    | 1         | 0.33%   |
| 0x406c3    | 1         | 0.33%   |
| 0x40661    | 1         | 0.33%   |
| 0x106e5    | 1         | 0.33%   |
| 0x106c2    | 1         | 0.33%   |
| 0x106a5    | 1         | 0.33%   |
| 0x10661    | 1         | 0.33%   |
| 0x0a50000b | 1         | 0.33%   |
| 0x0a201016 | 1         | 0.33%   |
| 0x08608103 | 1         | 0.33%   |
| 0x08600104 | 1         | 0.33%   |
| 0x08108102 | 1         | 0.33%   |
| 0x0810100b | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 55        | 18.15%  |
| Zen 2         | 29        | 9.57%   |
| IvyBridge     | 29        | 9.57%   |
| Haswell       | 26        | 8.58%   |
| Skylake       | 23        | 7.59%   |
| SandyBridge   | 21        | 6.93%   |
| Zen+          | 16        | 5.28%   |
| TigerLake     | 13        | 4.29%   |
| Broadwell     | 9         | 2.97%   |
| Unknown       | 9         | 2.97%   |
| CometLake     | 8         | 2.64%   |
| IceLake       | 7         | 2.31%   |
| Core          | 6         | 1.98%   |
| Zen 3         | 5         | 1.65%   |
| Zen           | 5         | 1.65%   |
| Westmere      | 5         | 1.65%   |
| Penryn        | 5         | 1.65%   |
| Goldmont      | 5         | 1.65%   |
| Steamroller   | 4         | 1.32%   |
| Silvermont    | 4         | 1.32%   |
| P6            | 3         | 0.99%   |
| K10           | 3         | 0.99%   |
| Goldmont plus | 3         | 0.99%   |
| Nehalem       | 2         | 0.66%   |
| Excavator     | 2         | 0.66%   |
| Piledriver    | 1         | 0.33%   |
| NetBurst      | 1         | 0.33%   |
| K6            | 1         | 0.33%   |
| Bulldozer     | 1         | 0.33%   |
| Bonnell       | 1         | 0.33%   |
| Bobcat        | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 181       | 52.77%  |
| Nvidia                     | 86        | 25.07%  |
| AMD                        | 71        | 20.7%   |
| Matrox Electronics Systems | 3         | 0.87%   |
| ASPEED Technology          | 2         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 5.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 4%      |
| Intel UHD Graphics 620                                                                   | 13        | 3.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 13        | 3.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.86%   |
| AMD Picasso                                                                              | 9         | 2.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 2.29%   |
| Intel HD Graphics 5500                                                                   | 8         | 2.29%   |
| AMD Renoir                                                                               | 8         | 2.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 2%      |
| Intel HD Graphics 620                                                                    | 6         | 1.71%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 6         | 1.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 1.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.43%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.14%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 1.14%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.14%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.14%   |
| Intel HD Graphics 530                                                                    | 4         | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 1.14%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.14%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.86%   |
| Intel HD Graphics 630                                                                    | 3         | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.86%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.57%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.57%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.57%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 2         | 0.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.57%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 2         | 0.57%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 0.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.57%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.57%   |
| Intel HD Graphics 515                                                                    | 2         | 0.57%   |
| Intel HD Graphics 500                                                                    | 2         | 0.57%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.57%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.57%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.57%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.57%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 0.57%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.29%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.29%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 137       | 44.92%  |
| 1 x AMD         | 58        | 19.02%  |
| 1 x Nvidia      | 48        | 15.74%  |
| Intel + Nvidia  | 36        | 11.8%   |
| Other           | 8         | 2.62%   |
| Intel + AMD     | 8         | 2.62%   |
| 2 x AMD         | 3         | 0.98%   |
| 1 x Matrox      | 2         | 0.66%   |
| 1 x ASPEED      | 2         | 0.66%   |
| AMD + Nvidia    | 2         | 0.66%   |
| Nvidia + Matrox | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 259       | 85.2%   |
| Proprietary | 33        | 10.86%  |
| Unknown     | 12        | 3.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 202       | 65.8%   |
| 1.01-2.0   | 25        | 8.14%   |
| 0.51-1.0   | 18        | 5.86%   |
| 0.01-0.5   | 18        | 5.86%   |
| 7.01-8.0   | 17        | 5.54%   |
| 3.01-4.0   | 15        | 4.89%   |
| 5.01-6.0   | 7         | 2.28%   |
| 2.01-3.0   | 2         | 0.65%   |
| 24.01-32.0 | 1         | 0.33%   |
| 16.01-24.0 | 1         | 0.33%   |
| 8.01-16.0  | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 46        | 13.57%  |
| Samsung Electronics  | 36        | 10.62%  |
| Chimei Innolux       | 33        | 9.73%   |
| BOE                  | 29        | 8.55%   |
| LG Display           | 27        | 7.96%   |
| Dell                 | 26        | 7.67%   |
| Goldstar             | 23        | 6.78%   |
| Ancor Communications | 14        | 4.13%   |
| Acer                 | 13        | 3.83%   |
| BenQ                 | 11        | 3.24%   |
| Philips              | 10        | 2.95%   |
| Hewlett-Packard      | 10        | 2.95%   |
| Sharp                | 9         | 2.65%   |
| Lenovo               | 6         | 1.77%   |
| AOC                  | 6         | 1.77%   |
| ASUSTek Computer     | 4         | 1.18%   |
| Apple                | 4         | 1.18%   |
| Unknown              | 3         | 0.88%   |
| Iiyama               | 3         | 0.88%   |
| LG Electronics       | 2         | 0.59%   |
| CPT                  | 2         | 0.59%   |
| ___                  | 1         | 0.29%   |
| ViewSonic            | 1         | 0.29%   |
| Vestel Elektronik    | 1         | 0.29%   |
| TEO                  | 1         | 0.29%   |
| Sony                 | 1         | 0.29%   |
| PANDA                | 1         | 0.29%   |
| ODH                  | 1         | 0.29%   |
| NCS                  | 1         | 0.29%   |
| MIT                  | 1         | 0.29%   |
| Mi                   | 1         | 0.29%   |
| Medion               | 1         | 0.29%   |
| JXG                  | 1         | 0.29%   |
| JVC                  | 1         | 0.29%   |
| JRY                  | 1         | 0.29%   |
| InfoVision           | 1         | 0.29%   |
| INFOTRONIC           | 1         | 0.29%   |
| Idek Iiyama          | 1         | 0.29%   |
| Hitachi              | 1         | 0.29%   |
| HannStar             | 1         | 0.29%   |
| Eizo                 | 1         | 0.29%   |
| CSO                  | 1         | 0.29%   |
| Belinea              | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 4         | 1.14%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 3         | 0.86%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3         | 0.86%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch          | 3         | 0.86%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3         | 0.86%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.57%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 0.57%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 2         | 0.57%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2         | 0.57%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2         | 0.57%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch             | 2         | 0.57%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 0.57%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.57%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2         | 0.57%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2         | 0.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.57%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 2         | 0.57%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.57%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 2         | 0.57%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.57%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 0.57%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 0.57%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch          | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 0.57%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2         | 0.57%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2         | 0.57%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                     | 1         | 0.29%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1         | 0.29%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.29%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 1         | 0.29%   |
| TEO TL565 TEO5550 1024x768 304x228mm 15.0-inch                         | 1         | 0.29%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1         | 0.29%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.29%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP14E2 1920x1080 309x174mm 14.0-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 1         | 0.29%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1         | 0.29%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 143       | 43.47%  |
| 1366x768 (WXGA)    | 51        | 15.5%   |
| 3840x2160 (4K)     | 24        | 7.29%   |
| 2560x1440 (QHD)    | 22        | 6.69%   |
| 1600x900 (HD+)     | 17        | 5.17%   |
| 1920x1200 (WUXGA)  | 12        | 3.65%   |
| 1280x1024 (SXGA)   | 12        | 3.65%   |
| 1680x1050 (WSXGA+) | 9         | 2.74%   |
| 1440x900 (WXGA+)   | 6         | 1.82%   |
| 1280x800 (WXGA)    | 5         | 1.52%   |
| Unknown            | 4         | 1.22%   |
| 2560x1600          | 3         | 0.91%   |
| 2560x1080          | 3         | 0.91%   |
| 3440x1440          | 2         | 0.61%   |
| 2288x1287          | 2         | 0.61%   |
| 1600x1200          | 2         | 0.61%   |
| 1024x768 (XGA)     | 2         | 0.61%   |
| 7680x4320          | 1         | 0.3%    |
| 5760x1080          | 1         | 0.3%    |
| 4480x1440          | 1         | 0.3%    |
| 3840x2400          | 1         | 0.3%    |
| 3360x1080          | 1         | 0.3%    |
| 2880x1800          | 1         | 0.3%    |
| 2160x1440          | 1         | 0.3%    |
| 1920x540           | 1         | 0.3%    |
| 1792x768           | 1         | 0.3%    |
| 1024x600           | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 60        | 17.75%  |
| 13      | 46        | 13.61%  |
| 24      | 35        | 10.36%  |
| 14      | 31        | 9.17%   |
| 27      | 26        | 7.69%   |
| 23      | 24        | 7.1%    |
| 17      | 16        | 4.73%   |
| 21      | 15        | 4.44%   |
| 12      | 12        | 3.55%   |
| Unknown | 11        | 3.25%   |
| 31      | 9         | 2.66%   |
| 19      | 8         | 2.37%   |
| 18      | 7         | 2.07%   |
| 11      | 7         | 2.07%   |
| 34      | 5         | 1.48%   |
| 20      | 4         | 1.18%   |
| 22      | 3         | 0.89%   |
| 142     | 2         | 0.59%   |
| 84      | 2         | 0.59%   |
| 47      | 2         | 0.59%   |
| 29      | 2         | 0.59%   |
| 28      | 2         | 0.59%   |
| 25      | 2         | 0.59%   |
| 72      | 1         | 0.3%    |
| 55      | 1         | 0.3%    |
| 48      | 1         | 0.3%    |
| 40      | 1         | 0.3%    |
| 33      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 10      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 126       | 38.18%  |
| 501-600        | 74        | 22.42%  |
| 201-300        | 39        | 11.82%  |
| 401-500        | 35        | 10.61%  |
| 601-700        | 17        | 5.15%   |
| 351-400        | 12        | 3.64%   |
| Unknown        | 11        | 3.33%   |
| 701-800        | 6         | 1.82%   |
| 1001-1500      | 4         | 1.21%   |
| 1501-2000      | 3         | 0.91%   |
| More than 2000 | 2         | 0.61%   |
| 801-900        | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 235       | 76.05%  |
| 16/10   | 31        | 10.03%  |
| 5/4     | 11        | 3.56%   |
| Unknown | 10        | 3.24%   |
| 4/3     | 6         | 1.94%   |
| 3/2     | 6         | 1.94%   |
| 21/9    | 6         | 1.94%   |
| 1.00    | 2         | 0.65%   |
| 6/5     | 1         | 0.32%   |
| 1.96    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 60        | 18.07%  |
| 81-90          | 59        | 17.77%  |
| 201-250        | 56        | 16.87%  |
| 301-350        | 26        | 7.83%   |
| 71-80          | 19        | 5.72%   |
| 351-500        | 19        | 5.72%   |
| 151-200        | 18        | 5.42%   |
| 251-300        | 13        | 3.92%   |
| 141-150        | 12        | 3.61%   |
| 61-70          | 11        | 3.31%   |
| Unknown        | 11        | 3.31%   |
| 121-130        | 8         | 2.41%   |
| 51-60          | 7         | 2.11%   |
| More than 1000 | 6         | 1.81%   |
| 501-1000       | 4         | 1.2%    |
| 131-140        | 2         | 0.6%    |
| 41-50          | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 110       | 34.27%  |
| 51-100        | 103       | 32.09%  |
| 101-120       | 61        | 19%     |
| 161-240       | 24        | 7.48%   |
| Unknown       | 11        | 3.43%   |
| More than 240 | 6         | 1.87%   |
| 1-50          | 6         | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 226       | 74.1%   |
| 2     | 55        | 18.03%  |
| 0     | 16        | 5.25%   |
| 3     | 7         | 2.3%    |
| 4     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 178       | 42.89%  |
| Realtek Semiconductor             | 142       | 34.22%  |
| Qualcomm Atheros                  | 41        | 9.88%   |
| Broadcom                          | 16        | 3.86%   |
| Marvell Technology Group          | 4         | 0.96%   |
| Broadcom Limited                  | 4         | 0.96%   |
| Ralink Technology                 | 3         | 0.72%   |
| Ralink                            | 3         | 0.72%   |
| Microchip Technology              | 2         | 0.48%   |
| Ericsson Business Mobile Networks | 2         | 0.48%   |
| Edimax Technology                 | 2         | 0.48%   |
| Dell                              | 2         | 0.48%   |
| Cypress Semiconductor             | 2         | 0.48%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.24%   |
| Xiaomi                            | 1         | 0.24%   |
| TP-Link                           | 1         | 0.24%   |
| Sierra Wireless                   | 1         | 0.24%   |
| Qualcomm                          | 1         | 0.24%   |
| Microsoft                         | 1         | 0.24%   |
| Mellanox Technologies             | 1         | 0.24%   |
| IBM                               | 1         | 0.24%   |
| Huawei Technologies               | 1         | 0.24%   |
| Hewlett-Packard                   | 1         | 0.24%   |
| Fibocom                           | 1         | 0.24%   |
| DisplayLink                       | 1         | 0.24%   |
| D-Link                            | 1         | 0.24%   |
| Attansic Technology               | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 97        | 19.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 23        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                     | 18        | 3.56%   |
| Intel Wireless 8260                                                     | 13        | 2.57%   |
| Intel I211 Gigabit Network Connection                                   | 12        | 2.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 1.98%   |
| Intel Wireless 8265 / 8275                                              | 9         | 1.78%   |
| Intel Ethernet Connection (2) I219-V                                    | 9         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.58%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                       | 7         | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.99%   |
| Intel Wireless 7265                                                     | 5         | 0.99%   |
| Intel Wireless 7260                                                     | 5         | 0.99%   |
| Intel Wireless 3165                                                     | 5         | 0.99%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.79%   |
| Intel Wireless 3160                                                     | 4         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.59%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.59%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.59%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.59%   |
| Intel Ethernet Connection (2) I218-V                                    | 3         | 0.59%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.4%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.4%    |
| Intel I210 Gigabit Network Connection                                   | 2         | 0.4%    |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.4%    |
| Intel Ethernet Connection I217-V                                        | 2         | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.4%    |
| Intel Ethernet Connection (13) I219-V                                   | 2         | 0.4%    |
| Intel Ethernet Connection (10) I219-V                                   | 2         | 0.4%    |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.4%    |
| Intel 82574L Gigabit Network Connection                                 | 2         | 0.4%    |
| Intel 82567LM-3 Gigabit Network Connection                              | 2         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 132       | 60.27%  |
| Qualcomm Atheros      | 32        | 14.61%  |
| Realtek Semiconductor | 31        | 14.16%  |
| Broadcom              | 8         | 3.65%   |
| Ralink Technology     | 3         | 1.37%   |
| Ralink                | 3         | 1.37%   |
| Edimax Technology     | 2         | 0.91%   |
| Broadcom Limited      | 2         | 0.91%   |
| TP-Link               | 1         | 0.46%   |
| Sierra Wireless       | 1         | 0.46%   |
| Qualcomm              | 1         | 0.46%   |
| Microsoft             | 1         | 0.46%   |
| Fibocom               | 1         | 0.46%   |
| D-Link                | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 18        | 8.18%   |
| Intel Wireless 8260                                                     | 13        | 5.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 4.55%   |
| Intel Wireless 8265 / 8275                                              | 9         | 4.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.64%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 2.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 2.27%   |
| Intel Wireless 7265                                                     | 5         | 2.27%   |
| Intel Wireless 7260                                                     | 5         | 2.27%   |
| Intel Wireless 3165                                                     | 5         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.82%   |
| Intel Wireless 3160                                                     | 4         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.82%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.36%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.36%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.36%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.36%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.91%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 0.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.91%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.45%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.45%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.45%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.45%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.45%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.45%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.45%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1         | 0.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.45%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.45%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.45%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 0.45%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.45%   |
| Intel Wireless Gigabit 17265                                            | 1         | 0.45%   |
| Intel WiFi Link 5100                                                    | 1         | 0.45%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                         | 1         | 0.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.45%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 125       | 46.3%   |
| Intel                    | 102       | 37.78%  |
| Qualcomm Atheros         | 14        | 5.19%   |
| Broadcom                 | 12        | 4.44%   |
| Marvell Technology Group | 4         | 1.48%   |
| Broadcom Limited         | 3         | 1.11%   |
| Microchip Technology     | 2         | 0.74%   |
| Cypress Semiconductor    | 2         | 0.74%   |
| Xiaomi                   | 1         | 0.37%   |
| Mellanox Technologies    | 1         | 0.37%   |
| IBM                      | 1         | 0.37%   |
| Huawei Technologies      | 1         | 0.37%   |
| DisplayLink              | 1         | 0.37%   |
| Attansic Technology      | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 97        | 34.77%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 8.24%   |
| Intel I211 Gigabit Network Connection                             | 12        | 4.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.94%   |
| Intel Ethernet Connection (2) I219-V                              | 9         | 3.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 2.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.15%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.79%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.43%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.08%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.08%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.72%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.72%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.72%   |
| Cypress K38231_03                                                 | 2         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.72%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.36%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.36%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.36%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.36%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.36%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.36%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.36%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.36%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 0.36%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1         | 0.36%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.36%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 0.36%   |
| Intel Ethernet Connection I354                                    | 1         | 0.36%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.36%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.36%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 253       | 53.49%  |
| WiFi     | 213       | 45.03%  |
| Modem    | 7         | 1.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 197       | 50.77%  |
| WiFi     | 190       | 48.97%  |
| Modem    | 1         | 0.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 161       | 53.14%  |
| 1     | 118       | 38.94%  |
| 3     | 11        | 3.63%   |
| 0     | 9         | 2.97%   |
| 13    | 1         | 0.33%   |
| 6     | 1         | 0.33%   |
| 5     | 1         | 0.33%   |
| 4     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 236       | 77.63%  |
| Yes  | 68        | 22.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 102       | 57.63%  |
| Realtek Semiconductor           | 15        | 8.47%   |
| Qualcomm Atheros Communications | 12        | 6.78%   |
| Cambridge Silicon Radio         | 10        | 5.65%   |
| Broadcom                        | 10        | 5.65%   |
| Lite-On Technology              | 6         | 3.39%   |
| ASUSTek Computer                | 4         | 2.26%   |
| Realtek                         | 3         | 1.69%   |
| IMC Networks                    | 3         | 1.69%   |
| Foxconn / Hon Hai               | 3         | 1.69%   |
| Apple                           | 3         | 1.69%   |
| Toshiba                         | 2         | 1.13%   |
| Dell                            | 2         | 1.13%   |
| Ralink                          | 1         | 0.56%   |
| Hewlett-Packard                 | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 21.47%  |
| Intel Bluetooth Device                              | 20        | 11.3%   |
| Intel AX200 Bluetooth                               | 18        | 10.17%  |
| Realtek Bluetooth Radio                             | 12        | 6.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 6.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 5.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 4.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 3.39%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 2.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 2.26%   |
| Realtek Bluetooth Radio                             | 3         | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.69%   |
| Toshiba Bluetooth Device                            | 2         | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.13%   |
| Lite-On Bluetooth Device                            | 2         | 1.13%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.13%   |
| Apple Bluetooth Host Controller                     | 2         | 1.13%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.56%   |
| Realtek CSR BS8510                                  | 1         | 0.56%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.56%   |
| IMC Networks Bluetooth Device                       | 1         | 0.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.56%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.56%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.56%   |
| Dell BCM20702A0                                     | 1         | 0.56%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.56%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 0.56%   |
| ASUS Bluetooth Radio                                | 1         | 0.56%   |
| ASUS Bluetooth Adapter                              | 1         | 0.56%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 218       | 52.28%  |
| AMD                        | 79        | 18.94%  |
| Nvidia                     | 65        | 15.59%  |
| C-Media Electronics        | 13        | 3.12%   |
| Generalplus Technology     | 6         | 1.44%   |
| Logitech                   | 5         | 1.2%    |
| GYROCOM C&C                | 4         | 0.96%   |
| Creative Labs              | 4         | 0.96%   |
| Texas Instruments          | 3         | 0.72%   |
| GN Netcom                  | 3         | 0.72%   |
| Samson Technologies        | 2         | 0.48%   |
| BEHRINGER International    | 2         | 0.48%   |
| XMOS                       | 1         | 0.24%   |
| VIA Technologies           | 1         | 0.24%   |
| RODE Microphones           | 1         | 0.24%   |
| ROCCAT                     | 1         | 0.24%   |
| Razer USA                  | 1         | 0.24%   |
| PreSonus Audio Electronics | 1         | 0.24%   |
| Plantronics                | 1         | 0.24%   |
| Hewlett-Packard            | 1         | 0.24%   |
| Hangzhou Worlde            | 1         | 0.24%   |
| Creative Technology        | 1         | 0.24%   |
| Blue Microphones           | 1         | 0.24%   |
| AXELVOX                    | 1         | 0.24%   |
| Alesis                     | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 31        | 6.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 5.98%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 23        | 4.74%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 20        | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 3.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 2.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 13        | 2.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 2.06%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 2.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 2.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.65%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.65%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 1.44%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.24%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.24%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.24%   |
| Generalplus Technology USB Audio Device                                                           | 6         | 1.24%   |
| AMD Navi 10 HDMI Audio                                                                            | 6         | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 0.82%   |
| AMD FCH Azalia Controller                                                                         | 4         | 0.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.62%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.62%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 0.62%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.62%   |
| GYROCOM C&C Fiio E10                                                                              | 3         | 0.62%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 3         | 0.62%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.62%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.41%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.41%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.41%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.41%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.41%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.41%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.41%   |
| Logitech G430 Surround Sound Gaming Headset                                                       | 2         | 0.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.41%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 61        | 19.12%  |
| Samsung Electronics | 59        | 18.5%   |
| Kingston            | 43        | 13.48%  |
| Crucial             | 28        | 8.78%   |
| Unknown             | 26        | 8.15%   |
| Micron Technology   | 26        | 8.15%   |
| Corsair             | 21        | 6.58%   |
| G.Skill             | 12        | 3.76%   |
| A-DATA Technology   | 12        | 3.76%   |
| Ramaxel Technology  | 6         | 1.88%   |
| Elpida              | 5         | 1.57%   |
| Team                | 4         | 1.25%   |
| Kllisre             | 3         | 0.94%   |
| Unknown (ABCD)      | 2         | 0.63%   |
| Nanya Technology    | 2         | 0.63%   |
| GOODRAM             | 2         | 0.63%   |
| V-Color             | 1         | 0.31%   |
| Unifosa             | 1         | 0.31%   |
| SMART Brazil        | 1         | 0.31%   |
| Smart               | 1         | 0.31%   |
| PNY                 | 1         | 0.31%   |
| Patriot             | 1         | 0.31%   |
| GeIL                | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 4         | 1.16%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.87%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.87%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.87%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 0.87%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 0.87%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 3         | 0.87%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.58%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.58%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.58%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.58%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.58%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.58%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.58%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 0.58%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.58%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.58%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.58%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.58%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s               | 2         | 0.58%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 2         | 0.58%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                | 2         | 0.58%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 2         | 0.58%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s              | 2         | 0.58%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2         | 0.58%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s              | 2         | 0.58%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 2         | 0.58%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s           | 2         | 0.58%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.58%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 2         | 0.58%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s                 | 1         | 0.29%   |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                           | 1         | 0.29%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.29%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.29%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s       | 1         | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.29%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM 800MT/s                              | 1         | 0.29%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.29%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                       | 1         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.29%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.29%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.29%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 144       | 53.53%  |
| DDR3    | 92        | 34.2%   |
| DDR2    | 9         | 3.35%   |
| LPDDR3  | 8         | 2.97%   |
| LPDDR4  | 7         | 2.6%    |
| Unknown | 5         | 1.86%   |
| SDRAM   | 4         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 147       | 54.85%  |
| DIMM         | 101       | 37.69%  |
| Row Of Chips | 17        | 6.34%   |
| Chip         | 2         | 0.75%   |
| RIMM         | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 116       | 39.73%  |
| 4096  | 82        | 28.08%  |
| 16384 | 44        | 15.07%  |
| 2048  | 24        | 8.22%   |
| 32768 | 13        | 4.45%   |
| 1024  | 8         | 2.74%   |
| 512   | 3         | 1.03%   |
| 65536 | 1         | 0.34%   |
| 256   | 1         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 66        | 21.85%  |
| 2667    | 54        | 17.88%  |
| 3200    | 40        | 13.25%  |
| 2400    | 28        | 9.27%   |
| 1333    | 26        | 8.61%   |
| 2133    | 20        | 6.62%   |
| 3600    | 9         | 2.98%   |
| 1334    | 9         | 2.98%   |
| 1867    | 6         | 1.99%   |
| 2933    | 5         | 1.66%   |
| 800     | 4         | 1.32%   |
| 4267    | 3         | 0.99%   |
| 3466    | 3         | 0.99%   |
| 2666    | 3         | 0.99%   |
| 400     | 3         | 0.99%   |
| 3000    | 2         | 0.66%   |
| 1866    | 2         | 0.66%   |
| 1067    | 2         | 0.66%   |
| 667     | 2         | 0.66%   |
| 533     | 2         | 0.66%   |
| Unknown | 2         | 0.66%   |
| 4266    | 1         | 0.33%   |
| 4199    | 1         | 0.33%   |
| 3533    | 1         | 0.33%   |
| 3500    | 1         | 0.33%   |
| 3400    | 1         | 0.33%   |
| 3066    | 1         | 0.33%   |
| 2465    | 1         | 0.33%   |
| 2000    | 1         | 0.33%   |
| 1800    | 1         | 0.33%   |
| 1066    | 1         | 0.33%   |
| 975     | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 57.14%  |
| Canon               | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 14.29%  |
| HP LaserJet P1006      | 1         | 14.29%  |
| HP LaserJet M101-M106  | 1         | 14.29%  |
| HP LaserJet 1200       | 1         | 14.29%  |
| HP ENVY 4520 series    | 1         | 14.29%  |
| Canon LiDE 400         | 1         | 14.29%  |
| Canon iP2700 series    | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 30        | 16.67%  |
| Chicony Electronics                    | 30        | 16.67%  |
| Microdia                               | 19        | 10.56%  |
| Acer                                   | 19        | 10.56%  |
| Logitech                               | 13        | 7.22%   |
| Realtek Semiconductor                  | 12        | 6.67%   |
| Lite-On Technology                     | 10        | 5.56%   |
| Sunplus Innovation Technology          | 7         | 3.89%   |
| Quanta                                 | 7         | 3.89%   |
| Suyin                                  | 4         | 2.22%   |
| Apple                                  | 4         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.67%   |
| Syntek                                 | 2         | 1.11%   |
| Samsung Electronics                    | 2         | 1.11%   |
| Generalplus Technology                 | 2         | 1.11%   |
| eMPIA Technology                       | 2         | 1.11%   |
| Z-Star Microelectronics                | 1         | 0.56%   |
| Xiongmai                               | 1         | 0.56%   |
| Razer USA                              | 1         | 0.56%   |
| Pixart Imaging                         | 1         | 0.56%   |
| Lenovo                                 | 1         | 0.56%   |
| Huawei Technologies                    | 1         | 0.56%   |
| Hewlett-Packard                        | 1         | 0.56%   |
| Genesys Logic                          | 1         | 0.56%   |
| DJKCVA19IE3NE8                         | 1         | 0.56%   |
| AVerMedia Technologies                 | 1         | 0.56%   |
| ARC International                      | 1         | 0.56%   |
| ALi                                    | 1         | 0.56%   |
| Alcor Micro                            | 1         | 0.56%   |
| A4Tech                                 | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera           | 11        | 6.11%   |
| Chicony integrated camera                | 9         | 5%      |
| Microdia Integrated_Webcam_HD            | 8         | 4.44%   |
| Acer Integrated Camera                   | 8         | 4.44%   |
| IMC Networks USB2.0 HD UVC WebCam        | 7         | 3.89%   |
| Realtek Integrated_Webcam_HD             | 6         | 3.33%   |
| Chicony HP HD Camera                     | 5         | 2.78%   |
| Acer SunplusIT Integrated Camera         | 5         | 2.78%   |
| Lite-On Integrated Camera                | 4         | 2.22%   |
| Microdia Webcam Vitade AF                | 3         | 1.67%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 3         | 1.67%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 3         | 1.67%   |
| Chicony HD WebCam                        | 3         | 1.67%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.11%   |
| Samsung Galaxy (MTP)                     | 2         | 1.11%   |
| Realtek EasyCamera                       | 2         | 1.11%   |
| Quanta HD Webcam                         | 2         | 1.11%   |
| Microdia USB Live camera                 | 2         | 1.11%   |
| Microdia Integrated Webcam HD            | 2         | 1.11%   |
| Logitech HD Webcam C615                  | 2         | 1.11%   |
| Logitech HD Pro Webcam C920              | 2         | 1.11%   |
| Logitech C505 HD Webcam                  | 2         | 1.11%   |
| Lite-On HP HD Camera                     | 2         | 1.11%   |
| IMC Networks ov9734_azurewave_camera     | 2         | 1.11%   |
| IMC Networks Lenovo EasyCamera           | 2         | 1.11%   |
| Chicony Lenovo EasyCamera                | 2         | 1.11%   |
| Chicony HP HD Webcam                     | 2         | 1.11%   |
| Apple FaceTime HD Camera                 | 2         | 1.11%   |
| Acer EasyCamera                          | 2         | 1.11%   |
| Z-Star Venus USB2.0 Camera               | 1         | 0.56%   |
| Xiongmai web camera                      | 1         | 0.56%   |
| Syntek USB 2.0 UVC PC Camera             | 1         | 0.56%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.56%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 0.56%   |
| Suyin HP TrueVision HD Integrated Webcam | 1         | 0.56%   |
| Suyin HP TrueVision Full HD              | 1         | 0.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 0.56%   |
| Sunplus Laptop Integrated Webcam FHD     | 1         | 0.56%   |
| Sunplus Dell E5570 integrated webcam     | 1         | 0.56%   |
| Sunplus 1.3M HD WebCam                   | 1         | 0.56%   |
| Realtek Lenovo EasyCamera                | 1         | 0.56%   |
| Realtek Integrated Webcam                | 1         | 0.56%   |
| Realtek HD WebCam                        | 1         | 0.56%   |
| Realtek Acer 640 x 480 laptop camera     | 1         | 0.56%   |
| Razer USA Razer Kiyo                     | 1         | 0.56%   |
| Quanta VGA WebCam                        | 1         | 0.56%   |
| Quanta ov9734_techfront_camera           | 1         | 0.56%   |
| Quanta HP Webcam                         | 1         | 0.56%   |
| Quanta HP TrueVision HD Camera           | 1         | 0.56%   |
| Quanta HP HD Camera                      | 1         | 0.56%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 1         | 0.56%   |
| Microdia Laptop_Integrated_Webcam_E4HD   | 1         | 0.56%   |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 0.56%   |
| Microdia Integrated Camera               | 1         | 0.56%   |
| Microdia 1.3 MPixel Integrated Webcam    | 1         | 0.56%   |
| Logitech Webcam C930e                    | 1         | 0.56%   |
| Logitech Webcam C270                     | 1         | 0.56%   |
| Logitech Webcam C260                     | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 40.54%  |
| Shenzhen Goodix Technology | 9         | 24.32%  |
| Validity Sensors           | 7         | 18.92%  |
| Elan Microelectronics      | 3         | 8.11%   |
| Upek                       | 2         | 5.41%   |
| AuthenTec                  | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 16.22%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 13.51%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 10.81%  |
| Shenzhen Goodix FingerPrint                                                | 4         | 10.81%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 8.11%   |
| Elan ELAN:Fingerprint                                                      | 3         | 8.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 5.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 5.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 5.41%   |
| Synaptics  WBDI                                                            | 1         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.7%    |
| Unknown                                                                    | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 7         | 30.43%  |
| Alcor Micro           | 7         | 30.43%  |
| Lenovo                | 4         | 17.39%  |
| Upek                  | 3         | 13.04%  |
| O2 Micro              | 1         | 4.35%   |
| Gemalto (was Gemplus) | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 30.43%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 17.39%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 13.04%  |
| Broadcom 58200                                                               | 3         | 13.04%  |
| Broadcom 5880                                                                | 2         | 8.7%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.35%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 228       | 74.51%  |
| 1     | 53        | 17.32%  |
| 2     | 21        | 6.86%   |
| 5     | 2         | 0.65%   |
| 4     | 1         | 0.33%   |
| 3     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 36.63%  |
| Graphics card            | 18        | 17.82%  |
| Chipcard                 | 18        | 17.82%  |
| Multimedia controller    | 7         | 6.93%   |
| Net/wireless             | 5         | 4.95%   |
| Communication controller | 5         | 4.95%   |
| Unassigned class         | 4         | 3.96%   |
| Storage                  | 2         | 1.98%   |
| Sound                    | 1         | 0.99%   |
| Modem                    | 1         | 0.99%   |
| Firewire controller      | 1         | 0.99%   |
| Card reader              | 1         | 0.99%   |
| Bluetooth                | 1         | 0.99%   |

