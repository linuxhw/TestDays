Xubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_22.04/Notebook/README.md).

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

Total: 702

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550M-K               | Desktop     | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| Unknown       | SEI Robotics SEI510         | Soc         | [09000d6461](https://linux-hardware.org/?probe=09000d6461) | Aug 10, 2023 |
| Dell          | Latitude 3540               | Notebook    | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| Unknown       | SEI Robotics SEI510         | Soc         | [c05973af65](https://linux-hardware.org/?probe=c05973af65) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [63f0153cfe](https://linux-hardware.org/?probe=63f0153cfe) | Aug 10, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [047ae922f7](https://linux-hardware.org/?probe=047ae922f7) | Aug 07, 2023 |
| Dell          | Latitude 5411               | Notebook    | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [341fecf811](https://linux-hardware.org/?probe=341fecf811) | Aug 06, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | Desktop     | [13f47a5399](https://linux-hardware.org/?probe=13f47a5399) | Aug 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [122ba504c1](https://linux-hardware.org/?probe=122ba504c1) | Aug 04, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [485793f801](https://linux-hardware.org/?probe=485793f801) | Aug 02, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [80558a1dcd](https://linux-hardware.org/?probe=80558a1dcd) | Aug 02, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [740da3bf14](https://linux-hardware.org/?probe=740da3bf14) | Jul 29, 2023 |
| Gateway       | NV57H                       | Notebook    | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [136cb11fa2](https://linux-hardware.org/?probe=136cb11fa2) | Jul 28, 2023 |
| Samsung       | N250P/N145P                 | Notebook    | [6b6e675a4c](https://linux-hardware.org/?probe=6b6e675a4c) | Jul 28, 2023 |
| Acer          | Extensa 2510                | Notebook    | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6a1aa5fbc8](https://linux-hardware.org/?probe=6a1aa5fbc8) | Jul 26, 2023 |
| Acer          | AOD255                      | Notebook    | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [e1db241198](https://linux-hardware.org/?probe=e1db241198) | Jul 24, 2023 |
| Acer          | AOD255                      | Notebook    | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| MSI           | MEGA BOOK GX620             | Notebook    | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [287298e199](https://linux-hardware.org/?probe=287298e199) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | Notebook    | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [94c330e355](https://linux-hardware.org/?probe=94c330e355) | Jul 19, 2023 |
| Thomson       | N15C8BK2T                   | Notebook    | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [08fc7fff38](https://linux-hardware.org/?probe=08fc7fff38) | Jul 17, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| MSI           | Modern 15 A10RBS            | Notebook    | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [0bd37865ac](https://linux-hardware.org/?probe=0bd37865ac) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [d18c64af74](https://linux-hardware.org/?probe=d18c64af74) | Jul 14, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [e3e2452c10](https://linux-hardware.org/?probe=e3e2452c10) | Jul 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | Notebook    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [5aacfb69aa](https://linux-hardware.org/?probe=5aacfb69aa) | Jul 12, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8807f705d0](https://linux-hardware.org/?probe=8807f705d0) | Jul 12, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [d4bc86a90a](https://linux-hardware.org/?probe=d4bc86a90a) | Jul 12, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [db2ec8adc8](https://linux-hardware.org/?probe=db2ec8adc8) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Dell          | Latitude 3540               | Notebook    | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| Google        | Snappy                      | Notebook    | [683d8bf80a](https://linux-hardware.org/?probe=683d8bf80a) | Jul 02, 2023 |
| Google        | Snappy                      | Notebook    | [d3502a53cc](https://linux-hardware.org/?probe=d3502a53cc) | Jul 02, 2023 |
| HP            | Pavilion 17                 | Notebook    | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [7c14851b62](https://linux-hardware.org/?probe=7c14851b62) | Jul 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| Google        | Fleex                       | Notebook    | [7e3eb2d4f9](https://linux-hardware.org/?probe=7e3eb2d4f9) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| ASUSTek       | H61M-CS                     | Desktop     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| HP            | 339A                        | Desktop     | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a39abe1278](https://linux-hardware.org/?probe=a39abe1278) | Jun 24, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [2e4e948549](https://linux-hardware.org/?probe=2e4e948549) | Jun 22, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [8f879f5566](https://linux-hardware.org/?probe=8f879f5566) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| Intel         | H61                         | Desktop     | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [154f9809e6](https://linux-hardware.org/?probe=154f9809e6) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [66ce1a98a8](https://linux-hardware.org/?probe=66ce1a98a8) | Jun 18, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [10b3b517f3](https://linux-hardware.org/?probe=10b3b517f3) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [4f0ec49165](https://linux-hardware.org/?probe=4f0ec49165) | Jun 17, 2023 |
| Unknown       | Minix Neo U9-H              | Soc         | [7b845b4b0b](https://linux-hardware.org/?probe=7b845b4b0b) | Jun 16, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [5a31ac8b21](https://linux-hardware.org/?probe=5a31ac8b21) | Jun 15, 2023 |
| Samsung       | 760XDA                      | Notebook    | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [b0afd2fa7b](https://linux-hardware.org/?probe=b0afd2fa7b) | Jun 13, 2023 |
| Dell          | Latitude 5411               | Notebook    | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Biostar       | TPower I45                  | Desktop     | [b88767bce0](https://linux-hardware.org/?probe=b88767bce0) | Jun 11, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| MSI           | A55M-E35                    | Desktop     | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Dell          | Precision 5510              | Notebook    | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| HP            | 8768 A                      | Desktop     | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Unknown       | Unknown                     | Notebook    | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Acer          | Veriton N4620G              | Desktop     | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Dell          | Latitude E4200              | Notebook    | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Unknown       | 1.0                         | Desktop     | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0b802ad297](https://linux-hardware.org/?probe=0b802ad297) | May 19, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| Pegatron      | Benicia                     | Desktop     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| HP            | 09F8h                       | Desktop     | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0b0b5e02cc](https://linux-hardware.org/?probe=0b0b5e02cc) | May 13, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2d3692d380](https://linux-hardware.org/?probe=2d3692d380) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [3c43bfe7bc](https://linux-hardware.org/?probe=3c43bfe7bc) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Dell          | Latitude E4310              | Notebook    | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Unknown       | Kontron BL i.MX8MM OSM-S... | Soc         | [958fed11ae](https://linux-hardware.org/?probe=958fed11ae) | May 10, 2023 |
| Google        | Edgar                       | Notebook    | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [1c37df2d10](https://linux-hardware.org/?probe=1c37df2d10) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [52836871bb](https://linux-hardware.org/?probe=52836871bb) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [a026aff306](https://linux-hardware.org/?probe=a026aff306) | May 09, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0f322b6e3f](https://linux-hardware.org/?probe=0f322b6e3f) | May 08, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ebafddb3f1](https://linux-hardware.org/?probe=ebafddb3f1) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bbac197d5d](https://linux-hardware.org/?probe=bbac197d5d) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [b735e1019b](https://linux-hardware.org/?probe=b735e1019b) | May 03, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | Notebook    | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | Notebook    | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [4382f0cce7](https://linux-hardware.org/?probe=4382f0cce7) | Apr 27, 2023 |
| HP            | 1632                        | Desktop     | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | Notebook    | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | 0AECh D                     | Desktop     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [9f2a1a2c93](https://linux-hardware.org/?probe=9f2a1a2c93) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | Desktop     | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [93fae77e6c](https://linux-hardware.org/?probe=93fae77e6c) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Medion        | MS-7848                     | Desktop     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [71ee0575d4](https://linux-hardware.org/?probe=71ee0575d4) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [f7cdc4223d](https://linux-hardware.org/?probe=f7cdc4223d) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Medion        | S321X                       | Notebook    | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | Desktop     | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | Notebook    | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | Notebook    | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Google        | Kefka                       | Notebook    | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ac565d5d7d](https://linux-hardware.org/?probe=ac565d5d7d) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ad41e0e370](https://linux-hardware.org/?probe=ad41e0e370) | Mar 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec9c2f21a5](https://linux-hardware.org/?probe=ec9c2f21a5) | Mar 05, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [e513434675](https://linux-hardware.org/?probe=e513434675) | Mar 04, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [5c3d9047bd](https://linux-hardware.org/?probe=5c3d9047bd) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| OEM           | Unknown                     | Desktop     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e367c45f3b](https://linux-hardware.org/?probe=e367c45f3b) | Mar 03, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| Google        | Nautilus                    | Convertible | [5aff7271ac](https://linux-hardware.org/?probe=5aff7271ac) | Mar 02, 2023 |
| AZW           | GTR V01                     | Mini pc     | [09e66839c3](https://linux-hardware.org/?probe=09e66839c3) | Mar 01, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 44        | 7.59%   |
| 5.15.0-52-generic    | 35        | 6.03%   |
| 5.15.0-47-generic    | 31        | 5.34%   |
| 5.15.0-58-generic    | 27        | 4.66%   |
| 5.15.0-48-generic    | 25        | 4.31%   |
| 5.15.0-60-generic    | 23        | 3.97%   |
| 5.15.0-67-generic    | 20        | 3.45%   |
| 5.15.0-25-generic    | 20        | 3.45%   |
| 5.15.0-46-generic    | 17        | 2.93%   |
| 5.15.0-53-generic    | 14        | 2.41%   |
| 5.15.0-27-generic    | 14        | 2.41%   |
| 5.19.0-41-generic    | 13        | 2.24%   |
| 5.19.0-35-generic    | 13        | 2.24%   |
| 5.15.0-71-generic    | 13        | 2.24%   |
| 5.19.0-46-generic    | 12        | 2.07%   |
| 5.19.0-45-generic    | 12        | 2.07%   |
| 5.15.0-69-generic    | 11        | 1.9%    |
| 5.19.0-38-generic    | 10        | 1.72%   |
| 5.15.0-57-generic    | 10        | 1.72%   |
| 5.15.0-43-generic    | 10        | 1.72%   |
| 5.19.0-43-generic    | 9         | 1.55%   |
| 5.15.0-50-generic    | 9         | 1.55%   |
| 5.15.0-41-generic    | 9         | 1.55%   |
| 5.15.0-40-generic    | 9         | 1.55%   |
| 5.15.0-76-generic    | 8         | 1.38%   |
| 5.19.0-50-generic    | 7         | 1.21%   |
| 5.19.0-32-generic    | 7         | 1.21%   |
| 5.15.0-78-generic    | 7         | 1.21%   |
| 5.15.0-70-generic    | 7         | 1.21%   |
| 5.15.0-71-lowlatency | 6         | 1.03%   |
| 5.15.0-39-generic    | 6         | 1.03%   |
| 5.19.0-42-generic    | 5         | 0.86%   |
| 5.15.0-73-generic    | 5         | 0.86%   |
| 5.15.0-37-generic    | 5         | 0.86%   |
| 5.15.0-35-generic    | 5         | 0.86%   |
| 6.2.0-26-generic     | 4         | 0.69%   |
| 5.15.0-33-generic    | 4         | 0.69%   |
| 5.15.0-30-generic    | 4         | 0.69%   |
| 5.17.0-1020-oem      | 3         | 0.52%   |
| 5.15.0-75-generic    | 3         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 389       | 71.9%   |
| 5.19.0   | 87        | 16.08%  |
| 5.17.0   | 11        | 2.03%   |
| 6.2.0    | 6         | 1.11%   |
| 6.1.0    | 6         | 1.11%   |
| 6.0.0    | 3         | 0.55%   |
| 5.13.0   | 3         | 0.55%   |
| 6.2.7    | 2         | 0.37%   |
| 6.1.30   | 2         | 0.37%   |
| 5.4.0    | 2         | 0.37%   |
| 5.18.0   | 2         | 0.37%   |
| 5.15.93  | 2         | 0.37%   |
| 6.4.8    | 1         | 0.18%   |
| 6.4.0    | 1         | 0.18%   |
| 6.3.3    | 1         | 0.18%   |
| 6.3.12   | 1         | 0.18%   |
| 6.2.9    | 1         | 0.18%   |
| 6.2.2    | 1         | 0.18%   |
| 6.2.10   | 1         | 0.18%   |
| 6.1.6    | 1         | 0.18%   |
| 6.1.10   | 1         | 0.18%   |
| 6.0.9    | 1         | 0.18%   |
| 6.0.7    | 1         | 0.18%   |
| 5.19.5   | 1         | 0.18%   |
| 5.19.13  | 1         | 0.18%   |
| 5.19.1   | 1         | 0.18%   |
| 5.18.12  | 1         | 0.18%   |
| 5.17.3   | 1         | 0.18%   |
| 5.16.9   | 1         | 0.18%   |
| 5.15.89  | 1         | 0.18%   |
| 5.15.74  | 1         | 0.18%   |
| 5.15.68  | 1         | 0.18%   |
| 5.15.61  | 1         | 0.18%   |
| 5.15.59  | 1         | 0.18%   |
| 5.15.48  | 1         | 0.18%   |
| 5.15.23  | 1         | 0.18%   |
| 5.10.110 | 1         | 0.18%   |
| 4.19.241 | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 398       | 73.57%  |
| 5.19    | 90        | 16.64%  |
| 5.17    | 12        | 2.22%   |
| 6.2     | 11        | 2.03%   |
| 6.1     | 10        | 1.85%   |
| 6.0     | 5         | 0.92%   |
| 5.18    | 3         | 0.55%   |
| 5.13    | 3         | 0.55%   |
| 6.4     | 2         | 0.37%   |
| 6.3     | 2         | 0.37%   |
| 5.4     | 2         | 0.37%   |
| 5.16    | 1         | 0.18%   |
| 5.10    | 1         | 0.18%   |
| 4.19    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 520       | 97.56%  |
| aarch64 | 9         | 1.69%   |
| armv7l  | 4         | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 518       | 97.19%  |
| GNOME           | 12        | 2.25%   |
| KDE5            | 1         | 0.19%   |
| i3              | 1         | 0.19%   |
| GNOME Flashback | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 511       | 95.34%  |
| Tty     | 18        | 3.36%   |
| Wayland | 7         | 1.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 463       | 86.87%  |
| Unknown | 34        | 6.38%   |
| GDM3    | 28        | 5.25%   |
| SDDM    | 5         | 0.94%   |
| SLiM    | 2         | 0.38%   |
| GDM     | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 208       | 39.02%  |
| de_DE | 69        | 12.95%  |
| fr_FR | 60        | 11.26%  |
| it_IT | 31        | 5.82%   |
| pt_BR | 22        | 4.13%   |
| en_GB | 21        | 3.94%   |
| en_CA | 17        | 3.19%   |
| ru_RU | 14        | 2.63%   |
| es_ES | 9         | 1.69%   |
| pl_PL | 8         | 1.5%    |
| en_AU | 7         | 1.31%   |
| cs_CZ | 7         | 1.31%   |
| en_IN | 6         | 1.13%   |
| nl_NL | 5         | 0.94%   |
| C     | 4         | 0.75%   |
| tr_TR | 3         | 0.56%   |
| ja_JP | 3         | 0.56%   |
| hu_HU | 3         | 0.56%   |
| es_VE | 3         | 0.56%   |
| es_AR | 3         | 0.56%   |
| ru_UA | 2         | 0.38%   |
| fr_BE | 2         | 0.38%   |
| fi_FI | 2         | 0.38%   |
| es_MX | 2         | 0.38%   |
| es_CO | 2         | 0.38%   |
| de_CH | 2         | 0.38%   |
| zh_CN | 1         | 0.19%   |
| sv_SE | 1         | 0.19%   |
| ro_RO | 1         | 0.19%   |
| pt_PT | 1         | 0.19%   |
| nl_BE | 1         | 0.19%   |
| lt_LT | 1         | 0.19%   |
| ko_KR | 1         | 0.19%   |
| fr_CH | 1         | 0.19%   |
| fr_CA | 1         | 0.19%   |
| es_CL | 1         | 0.19%   |
| en_ZA | 1         | 0.19%   |
| en_NZ | 1         | 0.19%   |
| en_IL | 1         | 0.19%   |
| en_IE | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 272       | 50.37%  |
| BIOS | 268       | 49.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 463       | 85.11%  |
| Tmpfs   | 38        | 6.99%   |
| Overlay | 17        | 3.13%   |
| Zfs     | 12        | 2.21%   |
| Btrfs   | 12        | 2.21%   |
| Xfs     | 1         | 0.18%   |
| Ext3    | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 383       | 70.28%  |
| MBR     | 85        | 15.6%   |
| Unknown | 77        | 14.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 465       | 85.95%  |
| Yes       | 76        | 14.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 377       | 70.34%  |
| Yes       | 159       | 29.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 77        | 14.45%  |
| Hewlett-Packard         | 76        | 14.26%  |
| ASUSTek Computer        | 72        | 13.51%  |
| Dell                    | 59        | 11.07%  |
| MSI                     | 36        | 6.75%   |
| Acer                    | 36        | 6.75%   |
| Gigabyte Technology     | 29        | 5.44%   |
| ASRock                  | 16        | 3%      |
| Google                  | 14        | 2.63%   |
| Apple                   | 9         | 1.69%   |
| Unknown                 | 8         | 1.5%    |
| Toshiba                 | 7         | 1.31%   |
| Samsung Electronics     | 6         | 1.13%   |
| Intel                   | 6         | 1.13%   |
| GPU Company             | 5         | 0.94%   |
| Supermicro              | 4         | 0.75%   |
| Sony                    | 4         | 0.75%   |
| Medion                  | 4         | 0.75%   |
| Rockchip                | 3         | 0.56%   |
| HUAWEI                  | 3         | 0.56%   |
| Fujitsu                 | 3         | 0.56%   |
| Foxconn                 | 3         | 0.56%   |
| Xunlong                 | 2         | 0.38%   |
| sunxi                   | 2         | 0.38%   |
| Radxa                   | 2         | 0.38%   |
| PCWare                  | 2         | 0.38%   |
| Packard Bell            | 2         | 0.38%   |
| Notebook                | 2         | 0.38%   |
| Itautec                 | 2         | 0.38%   |
| HONOR                   | 2         | 0.38%   |
| Gateway                 | 2         | 0.38%   |
| Chuwi                   | 2         | 0.38%   |
| VIT                     | 1         | 0.19%   |
| Thomson                 | 1         | 0.19%   |
| Tactus                  | 1         | 0.19%   |
| Standard                | 1         | 0.19%   |
| SGIN                    | 1         | 0.19%   |
| Semp Toshiba            | 1         | 0.19%   |
| Schenker                | 1         | 0.19%   |
| Raspberry Pi Foundation | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 10        | 1.88%   |
| ASUS All Series                          | 5         | 0.94%   |
| HP EliteBook 840 G3                      | 4         | 0.75%   |
| Google Snappy                            | 4         | 0.75%   |
| Dell OptiPlex 7010                       | 4         | 0.75%   |
| MSI MS-7D43                              | 3         | 0.56%   |
| MSI MS-7721                              | 3         | 0.56%   |
| HP Laptop 15s-fq2xxx                     | 3         | 0.56%   |
| Acer Switch SW312-31                     | 3         | 0.56%   |
| Rockchip RK3318 BOX                      | 2         | 0.38%   |
| MSI MS-7D46                              | 2         | 0.38%   |
| MSI MS-7D25                              | 2         | 0.38%   |
| MSI MS-7C52                              | 2         | 0.38%   |
| MSI MS-7817                              | 2         | 0.38%   |
| Lenovo V530S-07ICB 10TX0010PB            | 2         | 0.38%   |
| Lenovo ThinkPad P50 20EN0013US           | 2         | 0.38%   |
| HP Pavilion Notebook                     | 2         | 0.38%   |
| HP Pavilion g6                           | 2         | 0.38%   |
| HP Pavilion 17                           | 2         | 0.38%   |
| HP Pavilion 15                           | 2         | 0.38%   |
| HP 255 G8 Notebook PC                    | 2         | 0.38%   |
| GPU Company GWTN116-3                    | 2         | 0.38%   |
| Google Auron_Yuna                        | 2         | 0.38%   |
| Dell OptiPlex 9020                       | 2         | 0.38%   |
| Dell Latitude E5450                      | 2         | 0.38%   |
| Dell Latitude 7420                       | 2         | 0.38%   |
| ASUS K30AD_M31AD_M51AD                   | 2         | 0.38%   |
| ASUS ASUS TUF Gaming A15 FA507RE_FA507RE | 2         | 0.38%   |
| Apple MacBookPro8,1                      | 2         | 0.38%   |
| Xunlong Orange Pi PC Plus                | 1         | 0.19%   |
| Xunlong Orange Pi PC                     | 1         | 0.19%   |
| VIT Aptio CRB                            | 1         | 0.19%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.19%   |
| Toshiba Satellite Pro R50-B              | 1         | 0.19%   |
| Toshiba Satellite L750D                  | 1         | 0.19%   |
| Toshiba Satellite C650                   | 1         | 0.19%   |
| Toshiba Satellite C55D-B                 | 1         | 0.19%   |
| Toshiba PT10F                            | 1         | 0.19%   |
| Toshiba EQUIUM P200                      | 1         | 0.19%   |
| Thomson N15C8BK2T                        | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 39        | 7.32%   |
| Acer Aspire        | 23        | 4.32%   |
| HP Pavilion        | 17        | 3.19%   |
| Dell Latitude      | 17        | 3.19%   |
| ASUS PRIME         | 14        | 2.63%   |
| Lenovo IdeaPad     | 11        | 2.06%   |
| HP EliteBook       | 11        | 2.06%   |
| Dell OptiPlex      | 11        | 2.06%   |
| Dell Inspiron      | 11        | 2.06%   |
| Unknown            | 10        | 1.88%   |
| HP Laptop          | 9         | 1.69%   |
| HP Compaq          | 8         | 1.5%    |
| Lenovo ThinkCentre | 7         | 1.31%   |
| ASUS VivoBook      | 6         | 1.13%   |
| Toshiba Satellite  | 5         | 0.94%   |
| Dell XPS           | 5         | 0.94%   |
| Dell Precision     | 5         | 0.94%   |
| ASUS All           | 5         | 0.94%   |
| HP ProBook         | 4         | 0.75%   |
| Google Snappy      | 4         | 0.75%   |
| ASUS ROG           | 4         | 0.75%   |
| Acer Veriton       | 4         | 0.75%   |
| MSI MS-7D43        | 3         | 0.56%   |
| MSI MS-7721        | 3         | 0.56%   |
| HP Stream          | 3         | 0.56%   |
| HP EliteDesk       | 3         | 0.56%   |
| HP 255             | 3         | 0.56%   |
| Dell Vostro        | 3         | 0.56%   |
| Dell PowerEdge     | 3         | 0.56%   |
| ASUS TUF           | 3         | 0.56%   |
| ASUS ASUS          | 3         | 0.56%   |
| Acer Switch        | 3         | 0.56%   |
| Xunlong Orange     | 2         | 0.38%   |
| Rockchip RK3318    | 2         | 0.38%   |
| Radxa ROCK         | 2         | 0.38%   |
| MSI MS-7D46        | 2         | 0.38%   |
| MSI MS-7D25        | 2         | 0.38%   |
| MSI MS-7C52        | 2         | 0.38%   |
| MSI MS-7817        | 2         | 0.38%   |
| MSI GF63           | 2         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 54        | 10.13%  |
| 2020    | 46        | 8.63%   |
| 2014    | 41        | 7.69%   |
| 2022    | 38        | 7.13%   |
| 2013    | 37        | 6.94%   |
| 2018    | 36        | 6.75%   |
| 2017    | 33        | 6.19%   |
| 2016    | 32        | 6%      |
| 2015    | 30        | 5.63%   |
| 2011    | 30        | 5.63%   |
| 2012    | 29        | 5.44%   |
| 2010    | 28        | 5.25%   |
| 2019    | 26        | 4.88%   |
| 2009    | 20        | 3.75%   |
| 2008    | 14        | 2.63%   |
| 2007    | 14        | 2.63%   |
| Unknown | 12        | 2.25%   |
| 2023    | 6         | 1.13%   |
| 2006    | 5         | 0.94%   |
| 2005    | 2         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 296       | 55.53%  |
| Desktop        | 186       | 34.9%   |
| System on chip | 13        | 2.44%   |
| Mini pc        | 9         | 1.69%   |
| Convertible    | 8         | 1.5%    |
| All in one     | 8         | 1.5%    |
| Server         | 8         | 1.5%    |
| Tablet         | 5         | 0.94%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 495       | 92.35%  |
| Enabled  | 41        | 7.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 519       | 97.37%  |
| Yes  | 14        | 2.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 143       | 26.68%  |
| 4.01-8.0        | 127       | 23.69%  |
| 16.01-24.0      | 88        | 16.42%  |
| 8.01-16.0       | 70        | 13.06%  |
| 32.01-64.0      | 44        | 8.21%   |
| 1.01-2.0        | 24        | 4.48%   |
| 64.01-256.0     | 15        | 2.8%    |
| 24.01-32.0      | 10        | 1.87%   |
| 2.01-3.0        | 9         | 1.68%   |
| 0.51-1.0        | 5         | 0.93%   |
| More than 256.0 | 1         | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 233       | 41.39%  |
| 2.01-3.0   | 139       | 24.69%  |
| 3.01-4.0   | 59        | 10.48%  |
| 4.01-8.0   | 58        | 10.3%   |
| 0.51-1.0   | 45        | 7.99%   |
| 8.01-16.0  | 20        | 3.55%   |
| 16.01-24.0 | 4         | 0.71%   |
| 0.01-0.5   | 4         | 0.71%   |
| 24.01-32.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 339       | 62.78%  |
| 2      | 120       | 22.22%  |
| 3      | 40        | 7.41%   |
| 4      | 20        | 3.7%    |
| 5      | 9         | 1.67%   |
| 6      | 6         | 1.11%   |
| 7      | 2         | 0.37%   |
| 0      | 2         | 0.37%   |
| 10     | 1         | 0.19%   |
| 9      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 327       | 61.24%  |
| Yes       | 207       | 38.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 436       | 81.65%  |
| No        | 98        | 18.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 399       | 74.58%  |
| No        | 136       | 25.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 309       | 57.76%  |
| No        | 226       | 42.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 85        | 15.89%  |
| Germany     | 82        | 15.33%  |
| France      | 65        | 12.15%  |
| Italy       | 35        | 6.54%   |
| Brazil      | 25        | 4.67%   |
| UK          | 18        | 3.36%   |
| Canada      | 18        | 3.36%   |
| Russia      | 17        | 3.18%   |
| Poland      | 16        | 2.99%   |
| Sweden      | 12        | 2.24%   |
| Netherlands | 12        | 2.24%   |
| Spain       | 10        | 1.87%   |
| India       | 9         | 1.68%   |
| Czechia     | 9         | 1.68%   |
| Mexico      | 8         | 1.5%    |
| Australia   | 7         | 1.31%   |
| Belgium     | 6         | 1.12%   |
| Argentina   | 6         | 1.12%   |
| Switzerland | 5         | 0.93%   |
| Austria     | 5         | 0.93%   |
| Turkey      | 4         | 0.75%   |
| Japan       | 4         | 0.75%   |
| Iran        | 4         | 0.75%   |
| Greece      | 4         | 0.75%   |
| Colombia    | 4         | 0.75%   |
| Belarus     | 4         | 0.75%   |
| Venezuela   | 3         | 0.56%   |
| South Korea | 3         | 0.56%   |
| Portugal    | 3         | 0.56%   |
| Malaysia    | 3         | 0.56%   |
| Indonesia   | 3         | 0.56%   |
| Hungary     | 3         | 0.56%   |
| Finland     | 3         | 0.56%   |
| Denmark     | 3         | 0.56%   |
| China       | 3         | 0.56%   |
| Vietnam     | 2         | 0.37%   |
| Taiwan      | 2         | 0.37%   |
| Slovenia    | 2         | 0.37%   |
| Romania     | 2         | 0.37%   |
| Pakistan    | 2         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 10        | 1.82%   |
| Munich           | 7         | 1.27%   |
| Berlin           | 7         | 1.27%   |
| Warsaw           | 6         | 1.09%   |
| Milan            | 6         | 1.09%   |
| Stuttgart        | 5         | 0.91%   |
| Melbourne        | 5         | 0.91%   |
| Uppsala          | 4         | 0.73%   |
| Rho              | 4         | 0.73%   |
| Hamburg          | 4         | 0.73%   |
| Toronto          | 3         | 0.55%   |
| St Petersburg    | 3         | 0.55%   |
| Springfield      | 3         | 0.55%   |
| Rio de Janeiro   | 3         | 0.55%   |
| Nykvarn          | 3         | 0.55%   |
| North Hills      | 3         | 0.55%   |
| Moscow           | 3         | 0.55%   |
| Mexico City      | 3         | 0.55%   |
| London           | 3         | 0.55%   |
| Kuala Lumpur     | 3         | 0.55%   |
| Helsinki         | 3         | 0.55%   |
| Hanover          | 3         | 0.55%   |
| Copenhagen       | 3         | 0.55%   |
| Bordeaux         | 3         | 0.55%   |
| Biella           | 3         | 0.55%   |
| Athens           | 3         | 0.55%   |
| Ankara           | 3         | 0.55%   |
| Washington       | 2         | 0.36%   |
| Vicenza          | 2         | 0.36%   |
| Västerås       | 2         | 0.36%   |
| Tehran           | 2         | 0.36%   |
| Schwerte         | 2         | 0.36%   |
| Santiago de Cali | 2         | 0.36%   |
| Rochester        | 2         | 0.36%   |
| Puebla City      | 2         | 0.36%   |
| Pilsen           | 2         | 0.36%   |
| Oklahoma City    | 2         | 0.36%   |
| Oberhausen       | 2         | 0.36%   |
| Muncie           | 2         | 0.36%   |
| Mumbai           | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 117       | 144    | 15.25%  |
| WDC                         | 104       | 156    | 13.56%  |
| Seagate                     | 85        | 110    | 11.08%  |
| Unknown                     | 61        | 74     | 7.95%   |
| Kingston                    | 44        | 53     | 5.74%   |
| Sandisk                     | 40        | 48     | 5.22%   |
| Toshiba                     | 34        | 37     | 4.43%   |
| Hitachi                     | 33        | 43     | 4.3%    |
| Crucial                     | 28        | 34     | 3.65%   |
| SK hynix                    | 22        | 26     | 2.87%   |
| Intel                       | 19        | 21     | 2.48%   |
| HGST                        | 15        | 20     | 1.96%   |
| China                       | 12        | 13     | 1.56%   |
| PNY                         | 11        | 11     | 1.43%   |
| A-DATA Technology           | 11        | 15     | 1.43%   |
| Micron Technology           | 9         | 12     | 1.17%   |
| Unknown                     | 8         | 8      | 1.04%   |
| SPCC                        | 6         | 6      | 0.78%   |
| Phison                      | 6         | 13     | 0.78%   |
| ASMT                        | 5         | 11     | 0.65%   |
| Transcend                   | 4         | 6      | 0.52%   |
| Patriot                     | 4         | 4      | 0.52%   |
| Kingston Technology Company | 4         | 7      | 0.52%   |
| Fujitsu                     | 4         | 4      | 0.52%   |
| TO Exter                    | 3         | 4      | 0.39%   |
| Silicon Motion              | 3         | 3      | 0.39%   |
| Phison Electronics          | 3         | 5      | 0.39%   |
| KIOXIA                      | 3         | 3      | 0.39%   |
| Intenso                     | 3         | 3      | 0.39%   |
| Gigabyte Technology         | 3         | 4      | 0.39%   |
| USB3.0                      | 2         | 4      | 0.26%   |
| TEXTORM                     | 2         | 2      | 0.26%   |
| Realtek Semiconductor       | 2         | 2      | 0.26%   |
| PHD 3.0                     | 2         | 2      | 0.26%   |
| OCZ                         | 2         | 2      | 0.26%   |
| Netac                       | 2         | 2      | 0.26%   |
| Maxtor                      | 2         | 2      | 0.26%   |
| LITEON                      | 2         | 2      | 0.26%   |
| Lexar                       | 2         | 2      | 0.26%   |
| Lenovo                      | 2         | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 11        | 1.3%    |
| Kingston SA400S37480G 480GB SSD                     | 8         | 0.95%   |
| Unknown                                             | 8         | 0.95%   |
| Unknown MMC Card  32GB                              | 7         | 0.83%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.83%   |
| Kingston SA400S37240G 240GB SSD                     | 7         | 0.83%   |
| Crucial CT480BX500SSD1 480GB                        | 7         | 0.83%   |
| Unknown SD/MMC/MS PRO 128GB                         | 6         | 0.71%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 0.59%   |
| Seagate ST1000LM048-2E7172 1TB                      | 5         | 0.59%   |
| Samsung SSD 850 EVO 250GB                           | 5         | 0.59%   |
| Crucial CT500MX500SSD1 500GB                        | 5         | 0.59%   |
| Unknown MMC Card  128GB                             | 4         | 0.47%   |
| Toshiba DT01ACA200 2TB                              | 4         | 0.47%   |
| Toshiba DT01ACA100 1TB                              | 4         | 0.47%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB                      | 4         | 0.47%   |
| SanDisk DF4064  64GB                                | 4         | 0.47%   |
| Samsung SSD 870 QVO 1TB                             | 4         | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                    | 4         | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 0.36%   |
| Unknown MMC Card  64GB                              | 3         | 0.36%   |
| Unknown MMC Card  16GB                              | 3         | 0.36%   |
| Unknown DF4016  16GB                                | 3         | 0.36%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 0.36%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.36%   |
| Toshiba HDWD110 1TB                                 | 3         | 0.36%   |
| TO Exter nal USB 3.0 1TB                            | 3         | 0.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 0.36%   |
| Seagate ST500LM000-1EJ162 500GB                     | 3         | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3         | 0.36%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3         | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB                      | 3         | 0.36%   |
| SanDisk SDSSDA240G 240GB                            | 3         | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.36%   |
| Samsung SSD 870 QVO 4TB                             | 3         | 0.36%   |
| Samsung SSD 840 Series 120GB                        | 3         | 0.36%   |
| Samsung NVMe SSD Drive 256GB                        | 3         | 0.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 108    | 29.93%  |
| WDC                 | 84        | 132    | 29.58%  |
| Hitachi             | 33        | 43     | 11.62%  |
| Toshiba             | 30        | 33     | 10.56%  |
| HGST                | 15        | 20     | 5.28%   |
| Samsung Electronics | 12        | 16     | 4.23%   |
| Unknown             | 6         | 7      | 2.11%   |
| ASMT                | 5         | 11     | 1.76%   |
| Fujitsu             | 4         | 4      | 1.41%   |
| USB3.0              | 2         | 4      | 0.7%    |
| PHD 3.0             | 2         | 2      | 0.7%    |
| SSK                 | 1         | 1      | 0.35%   |
| Maxtor              | 1         | 1      | 0.35%   |
| LaCie               | 1         | 1      | 0.35%   |
| JMicron Technology  | 1         | 1      | 0.35%   |
| Hewlett-Packard     | 1         | 1      | 0.35%   |
| ASMedia             | 1         | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 76     | 23.83%  |
| Kingston            | 35        | 41     | 13.67%  |
| Crucial             | 25        | 31     | 9.77%   |
| SanDisk             | 21        | 27     | 8.2%    |
| WDC                 | 12        | 13     | 4.69%   |
| China               | 12        | 13     | 4.69%   |
| A-DATA Technology   | 11        | 15     | 4.3%    |
| PNY                 | 10        | 10     | 3.91%   |
| SPCC                | 6         | 6      | 2.34%   |
| Intel               | 6         | 6      | 2.34%   |
| Transcend           | 4         | 5      | 1.56%   |
| Patriot             | 4         | 4      | 1.56%   |
| Micron Technology   | 4         | 5      | 1.56%   |
| Toshiba             | 3         | 3      | 1.17%   |
| TO Exter            | 3         | 4      | 1.17%   |
| Intenso             | 3         | 3      | 1.17%   |
| TEXTORM             | 2         | 2      | 0.78%   |
| SK hynix            | 2         | 2      | 0.78%   |
| OCZ                 | 2         | 2      | 0.78%   |
| Netac               | 2         | 2      | 0.78%   |
| LITEON              | 2         | 2      | 0.78%   |
| KingDian            | 2         | 2      | 0.78%   |
| FORESEE             | 2         | 4      | 0.78%   |
| Apacer              | 2         | 2      | 0.78%   |
| Veno                | 1         | 1      | 0.39%   |
| Vaseky              | 1         | 1      | 0.39%   |
| Team                | 1         | 3      | 0.39%   |
| SSSTC               | 1         | 1      | 0.39%   |
| ShiJi               | 1         | 1      | 0.39%   |
| Maxtor              | 1         | 1      | 0.39%   |
| LITEONIT            | 1         | 1      | 0.39%   |
| Linux               | 1         | 1      | 0.39%   |
| Lexar               | 1         | 1      | 0.39%   |
| KingSpec            | 1         | 1      | 0.39%   |
| KingFast            | 1         | 1      | 0.39%   |
| Kimtigo             | 1         | 1      | 0.39%   |
| INNOVATION IT       | 1         | 1      | 0.39%   |
| Gigabyte Technology | 1         | 1      | 0.39%   |
| EVM                 | 1         | 1      | 0.39%   |
| Dogfish             | 1         | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 233       | 386    | 33.87%  |
| SSD     | 226       | 302    | 32.85%  |
| NVMe    | 154       | 192    | 22.38%  |
| MMC     | 66        | 81     | 9.59%   |
| Unknown | 9         | 10     | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 374       | 644    | 59.37%  |
| NVMe | 153       | 191    | 24.29%  |
| MMC  | 66        | 81     | 10.48%  |
| SAS  | 37        | 55     | 5.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 298       | 424    | 59.48%  |
| 0.51-1.0   | 125       | 157    | 24.95%  |
| 1.01-2.0   | 43        | 57     | 8.58%   |
| 3.01-4.0   | 23        | 34     | 4.59%   |
| 2.01-3.0   | 5         | 6      | 1%      |
| 4.01-10.0  | 5         | 7      | 1%      |
| 10.01-20.0 | 2         | 3      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 144       | 26.47%  |
| 251-500        | 131       | 24.08%  |
| 501-1000       | 69        | 12.68%  |
| 1001-2000      | 46        | 8.46%   |
| 51-100         | 41        | 7.54%   |
| 1-20           | 39        | 7.17%   |
| 21-50          | 29        | 5.33%   |
| More than 3000 | 28        | 5.15%   |
| 2001-3000      | 16        | 2.94%   |
| Unknown        | 1         | 0.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 199       | 35.79%  |
| 21-50          | 106       | 19.06%  |
| 101-250        | 76        | 13.67%  |
| 51-100         | 61        | 10.97%  |
| 251-500        | 45        | 8.09%   |
| 501-1000       | 29        | 5.22%   |
| 1001-2000      | 18        | 3.24%   |
| 2001-3000      | 11        | 1.98%   |
| More than 3000 | 10        | 1.8%    |
| Unknown        | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB                           | 2         | 2      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 2      | 2.5%    |
| Seagate ST1000DM003-1ER162 1TB                   | 2         | 2      | 2.5%    |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 1.25%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                 | 1         | 1      | 1.25%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 1         | 1      | 1.25%   |
| WDC WD3200AAKS-00L9A0 320GB                      | 1         | 1      | 1.25%   |
| WDC WD2500AAKS-00VSA0 250GB                      | 1         | 1      | 1.25%   |
| WDC WD20EFRX-68AX9N0 2TB                         | 1         | 1      | 1.25%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 1.25%   |
| WDC WD2002FYPS-02W3B0 2TB                        | 1         | 1      | 1.25%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.25%   |
| WDC WD10EZEX-60ZF5A0 1TB                         | 1         | 1      | 1.25%   |
| WDC WD10EAVS-00D7B1 1TB                          | 1         | 1      | 1.25%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1         | 1      | 1.25%   |
| WDC WD10EARS-003BB1 1TB                          | 1         | 1      | 1.25%   |
| WDC WD1003FBYX-01Y7B1 1TB                        | 1         | 1      | 1.25%   |
| WDC WD1001FALS-40Y6A0 1TB                        | 1         | 2      | 1.25%   |
| Toshiba MK1246GSX 120GB                          | 1         | 1      | 1.25%   |
| SSSTC CVB-8D128-HP 128GB SSD                     | 1         | 1      | 1.25%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 1.25%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 1.25%   |
| Seagate ST9250410AS 250GB                        | 1         | 1      | 1.25%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 1.25%   |
| Seagate ST4000DX001-1CE168 4TB                   | 1         | 1      | 1.25%   |
| Seagate ST3750840AS 752GB                        | 1         | 1      | 1.25%   |
| Seagate ST3500414CS 500GB                        | 1         | 1      | 1.25%   |
| Seagate ST3250318AS 250GB                        | 1         | 2      | 1.25%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.25%   |
| Seagate ST2000DM001-1CH164 2TB                   | 1         | 1      | 1.25%   |
| Seagate ST1000LM 035-1RK172 1TB                  | 1         | 1      | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB                   | 1         | 1      | 1.25%   |
| SanDisk SSD PLUS 480GB                           | 1         | 1      | 1.25%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 1.25%   |
| Samsung Electronics SSD PM810 FDE 2.5 128GB      | 1         | 1      | 1.25%   |
| Samsung Electronics SP2514N 250GB                | 1         | 1      | 1.25%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 1.25%   |
| Samsung Electronics HM321HI 320GB                | 1         | 2      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 21     | 25.64%  |
| WDC                 | 14        | 16     | 17.95%  |
| Hitachi             | 9         | 10     | 11.54%  |
| Samsung Electronics | 7         | 9      | 8.97%   |
| Fujitsu             | 4         | 4      | 5.13%   |
| Toshiba             | 3         | 3      | 3.85%   |
| Kingston            | 3         | 4      | 3.85%   |
| Intel               | 3         | 3      | 3.85%   |
| HGST                | 3         | 5      | 3.85%   |
| SanDisk             | 2         | 2      | 2.56%   |
| SSSTC               | 1         | 1      | 1.28%   |
| PNY                 | 1         | 1      | 1.28%   |
| Maxtor              | 1         | 1      | 1.28%   |
| LITEON              | 1         | 1      | 1.28%   |
| JMicron Technology  | 1         | 1      | 1.28%   |
| Hewlett-Packard     | 1         | 1      | 1.28%   |
| Crucial             | 1         | 1      | 1.28%   |
| China               | 1         | 1      | 1.28%   |
| ASMT                | 1         | 4      | 1.28%   |
| Unknown             | 1         | 1      | 1.28%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 21     | 33.33%  |
| WDC                 | 12        | 14     | 20%     |
| Hitachi             | 9         | 10     | 15%     |
| Samsung Electronics | 5         | 7      | 8.33%   |
| Fujitsu             | 4         | 4      | 6.67%   |
| Toshiba             | 3         | 3      | 5%      |
| HGST                | 3         | 5      | 5%      |
| Maxtor              | 1         | 1      | 1.67%   |
| JMicron Technology  | 1         | 1      | 1.67%   |
| Hewlett-Packard     | 1         | 1      | 1.67%   |
| ASMT                | 1         | 4      | 1.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 71     | 76.39%  |
| SSD  | 17        | 19     | 23.61%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 284       | 444    | 48.22%  |
| Detected | 234       | 437    | 39.73%  |
| Malfunc  | 71        | 90     | 12.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 348       | 55.33%  |
| AMD                          | 103       | 16.38%  |
| Samsung Electronics          | 50        | 7.95%   |
| SanDisk                      | 22        | 3.5%    |
| SK hynix                     | 19        | 3.02%   |
| Kingston Technology Company  | 15        | 2.38%   |
| Phison Electronics           | 12        | 1.91%   |
| ASMedia Technology           | 7         | 1.11%   |
| Silicon Motion               | 6         | 0.95%   |
| JMicron Technology           | 6         | 0.95%   |
| Nvidia                       | 5         | 0.79%   |
| Micron/Crucial Technology    | 4         | 0.64%   |
| Micron Technology            | 4         | 0.64%   |
| Marvell Technology Group     | 4         | 0.64%   |
| VIA Technologies             | 3         | 0.48%   |
| Silicon Image                | 3         | 0.48%   |
| Realtek Semiconductor        | 3         | 0.48%   |
| KIOXIA                       | 3         | 0.48%   |
| Lenovo                       | 2         | 0.32%   |
| Union Memory (Shenzhen)      | 1         | 0.16%   |
| Toshiba America Info Systems | 1         | 0.16%   |
| Shenzhen Longsys Electronics | 1         | 0.16%   |
| LSI Logic / Symbios Logic    | 1         | 0.16%   |
| INNOGRIT                     | 1         | 0.16%   |
| Broadcom / LSI               | 1         | 0.16%   |
| Biwin Storage Technology     | 1         | 0.16%   |
| Apple                        | 1         | 0.16%   |
| ADATA Technology             | 1         | 0.16%   |
| Adaptec                      | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 76        | 10.48%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 2.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 20        | 2.76%   |
| Samsung NVMe SSD Controller 980                                                  | 19        | 2.62%   |
| Intel Volume Management Device NVMe RAID Controller                              | 16        | 2.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 1.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 13        | 1.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 13        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 1.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 1.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 12        | 1.66%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 11        | 1.52%   |
| AMD 400 Series Chipset SATA Controller                                           | 11        | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 1.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 10        | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 1.24%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 9         | 1.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 9         | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 9         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 9         | 1.24%   |
| AMD 500 Series Chipset SATA Controller                                           | 9         | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 1.1%    |
| Intel SATA Controller [RAID mode]                                                | 8         | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 8         | 1.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 0.97%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 7         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 0.97%   |
| AMD FCH SATA Controller D                                                        | 7         | 0.97%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 6         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 388       | 59.97%  |
| NVMe | 153       | 23.65%  |
| IDE  | 60        | 9.27%   |
| RAID | 44        | 6.8%    |
| SAS  | 1         | 0.15%   |
| SCSI | 1         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 396       | 74.3%   |
| AMD    | 124       | 23.26%  |
| ARM    | 13        | 2.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz       | 10        | 1.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 10        | 1.87%   |
| ARM Processor                           | 9         | 1.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 8         | 1.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz       | 6         | 1.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 1.12%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 0.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 5         | 0.94%   |
| AMD Ryzen 5 3600 6-Core Processor       | 5         | 0.94%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 4         | 0.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 0.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 4         | 0.75%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 4         | 0.75%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 4         | 0.75%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 4         | 0.75%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 4         | 0.75%   |
| Intel Celeron CPU 847 @ 1.10GHz         | 4         | 0.75%   |
| Intel 12th Gen Core i7-1260P            | 4         | 0.75%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 4         | 0.75%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 3         | 0.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 0.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 0.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 3         | 0.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 3         | 0.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 0.56%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz    | 3         | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 3         | 0.56%   |
| Intel Core 2 CPU T7200 @ 2.00GHz        | 3         | 0.56%   |
| Intel Celeron J4105 CPU @ 1.50GHz       | 3         | 0.56%   |
| Intel Celeron CPU N3160 @ 1.60GHz       | 3         | 0.56%   |
| Intel Celeron CPU J1800 @ 2.41GHz       | 3         | 0.56%   |
| Intel Celeron 3205U @ 1.50GHz           | 3         | 0.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 3         | 0.56%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz | 3         | 0.56%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 3         | 0.56%   |
| AMD Ryzen 7 2700 Eight-Core Processor   | 3         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 105       | 19.66%  |
| Intel Celeron           | 68        | 12.73%  |
| Other                   | 58        | 10.86%  |
| Intel Core i7           | 52        | 9.74%   |
| Intel Core i3           | 38        | 7.12%   |
| AMD Ryzen 5             | 35        | 6.55%   |
| Intel Core 2 Duo        | 20        | 3.75%   |
| AMD Ryzen 7             | 17        | 3.18%   |
| Intel Xeon              | 13        | 2.43%   |
| Intel Pentium           | 11        | 2.06%   |
| Intel Atom              | 10        | 1.87%   |
| AMD A8                  | 10        | 1.87%   |
| Intel Pentium Dual-Core | 6         | 1.12%   |
| Intel Core 2            | 6         | 1.12%   |
| AMD A6                  | 6         | 1.12%   |
| Intel Core 2 Quad       | 5         | 0.94%   |
| AMD Ryzen 9             | 5         | 0.94%   |
| AMD FX                  | 5         | 0.94%   |
| AMD A4                  | 5         | 0.94%   |
| ARM Allwinner           | 4         | 0.75%   |
| AMD Ryzen 5 PRO         | 4         | 0.75%   |
| AMD Ryzen 3             | 4         | 0.75%   |
| AMD Phenom II X4        | 4         | 0.75%   |
| Intel Pentium Dual      | 3         | 0.56%   |
| Intel Genuine           | 3         | 0.56%   |
| AMD Ryzen 7 PRO         | 3         | 0.56%   |
| AMD E1                  | 3         | 0.56%   |
| AMD Athlon II X2        | 3         | 0.56%   |
| AMD A10                 | 3         | 0.56%   |
| Intel Pentium Silver    | 2         | 0.37%   |
| Intel Pentium 4         | 2         | 0.37%   |
| AMD Ryzen Threadripper  | 2         | 0.37%   |
| AMD GX                  | 2         | 0.37%   |
| AMD E2                  | 2         | 0.37%   |
| AMD Athlon 64 X2        | 2         | 0.37%   |
| AMD Athlon              | 2         | 0.37%   |
| Intel Xeon Gold         | 1         | 0.19%   |
| Intel Core m3           | 1         | 0.19%   |
| Intel Core 2 Extreme    | 1         | 0.19%   |
| Intel Celeron Dual-Core | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 232       | 43.36%  |
| 4       | 183       | 34.21%  |
| 6       | 48        | 8.97%   |
| 8       | 31        | 5.79%   |
| 12      | 10        | 1.87%   |
| 1       | 8         | 1.5%    |
| 10      | 6         | 1.12%   |
| Unknown | 5         | 0.93%   |
| 16      | 3         | 0.56%   |
| 14      | 3         | 0.56%   |
| 3       | 3         | 0.56%   |
| 64      | 2         | 0.37%   |
| 24      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 525       | 98.5%   |
| Unknown | 5         | 0.94%   |
| 2       | 3         | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 308       | 57.79%  |
| 1       | 220       | 41.28%  |
| Unknown | 5         | 0.94%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 527       | 98.87%  |
| Unknown        | 5         | 0.94%   |
| 64-bit         | 1         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 199       | 36.65%  |
| 0x806c1    | 19        | 3.5%    |
| 0x306c3    | 16        | 2.95%   |
| 0x306a9    | 16        | 2.95%   |
| 0x1067a    | 13        | 2.39%   |
| 0x206a7    | 12        | 2.21%   |
| 0x506c9    | 11        | 2.03%   |
| 0x406e3    | 11        | 2.03%   |
| 0x406c4    | 9         | 1.66%   |
| 0x08608103 | 9         | 1.66%   |
| 0x706a8    | 8         | 1.47%   |
| 0x506e3    | 8         | 1.47%   |
| 0x306d4    | 8         | 1.47%   |
| 0x906ea    | 7         | 1.29%   |
| 0x806ec    | 7         | 1.29%   |
| 0x30678    | 7         | 1.29%   |
| 0x806e9    | 6         | 1.1%    |
| 0x406c3    | 6         | 1.1%    |
| 0x20655    | 6         | 1.1%    |
| 0x106e5    | 6         | 1.1%    |
| 0x07030105 | 6         | 1.1%    |
| 0x806ea    | 5         | 0.92%   |
| 0x706a1    | 5         | 0.92%   |
| 0x6fd      | 5         | 0.92%   |
| 0x6f6      | 5         | 0.92%   |
| 0x40651    | 5         | 0.92%   |
| 0x10676    | 5         | 0.92%   |
| 0x0800820d | 5         | 0.92%   |
| 0x010000c8 | 5         | 0.92%   |
| 0xa0652    | 4         | 0.74%   |
| 0x906a3    | 4         | 0.74%   |
| 0x6fb      | 4         | 0.74%   |
| 0x08701021 | 4         | 0.74%   |
| 0x08108109 | 4         | 0.74%   |
| 0x06006705 | 4         | 0.74%   |
| 0xb0671    | 3         | 0.55%   |
| 0x906e9    | 3         | 0.55%   |
| 0x90672    | 3         | 0.55%   |
| 0x806d1    | 3         | 0.55%   |
| 0x20652    | 3         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 52        | 9.72%   |
| Unknown          | 44        | 8.22%   |
| Haswell          | 38        | 7.1%    |
| SandyBridge      | 34        | 6.36%   |
| Silvermont       | 32        | 5.98%   |
| Penryn           | 30        | 5.61%   |
| IvyBridge        | 30        | 5.61%   |
| Skylake          | 29        | 5.42%   |
| TigerLake        | 23        | 4.3%    |
| Zen 2            | 21        | 3.93%   |
| Core             | 17        | 3.18%   |
| Goldmont plus    | 16        | 2.99%   |
| Goldmont         | 16        | 2.99%   |
| Westmere         | 15        | 2.8%    |
| Zen+             | 13        | 2.43%   |
| Zen 3            | 13        | 2.43%   |
| Alderlake Hybrid | 12        | 2.24%   |
| CometLake        | 11        | 2.06%   |
| Broadwell        | 11        | 2.06%   |
| Piledriver       | 10        | 1.87%   |
| K10              | 10        | 1.87%   |
| Puma             | 9         | 1.68%   |
| Nehalem          | 8         | 1.5%    |
| Excavator        | 8         | 1.5%    |
| Zen              | 6         | 1.12%   |
| IceLake          | 5         | 0.93%   |
| K10 Llano        | 4         | 0.75%   |
| Bonnell          | 4         | 0.75%   |
| Bobcat           | 4         | 0.75%   |
| Steamroller      | 3         | 0.56%   |
| NetBurst         | 2         | 0.37%   |
| K8 Hammer        | 2         | 0.37%   |
| Jaguar           | 2         | 0.37%   |
| Tremont          | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 322       | 54.95%  |
| Nvidia                     | 129       | 22.01%  |
| AMD                        | 128       | 21.84%  |
| ASPEED Technology          | 4         | 0.68%   |
| Matrox Electronics Systems | 3         | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 4.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 3.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 3.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 2.49%   |
| Intel HD Graphics 500                                                                    | 14        | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 2.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 2.33%   |
| AMD Lucienne                                                                             | 13        | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 1.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.66%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 9         | 1.5%    |
| Intel HD Graphics 530                                                                    | 9         | 1.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 1.33%   |
| Intel HD Graphics 620                                                                    | 8         | 1.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.33%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.16%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 6         | 1%      |
| AMD Renoir                                                                               | 6         | 1%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1%      |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 1%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 0.83%   |
| Intel UHD Graphics 620                                                                   | 5         | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.83%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 0.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.66%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.66%   |
| Intel HD Graphics 630                                                                    | 4         | 0.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 265       | 49.72%  |
| 1 x AMD         | 102       | 19.14%  |
| 1 x Nvidia      | 80        | 15.01%  |
| Intel + Nvidia  | 37        | 6.94%   |
| Other           | 17        | 3.19%   |
| Intel + AMD     | 9         | 1.69%   |
| AMD + Nvidia    | 9         | 1.69%   |
| 2 x AMD         | 7         | 1.31%   |
| Nvidia + ASPEED | 3         | 0.56%   |
| 1 x Matrox      | 2         | 0.38%   |
| 1 x ASPEED      | 1         | 0.19%   |
| AMD + Matrox    | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 438       | 81.72%  |
| Proprietary | 71        | 13.25%  |
| Unknown     | 27        | 5.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 376       | 70.02%  |
| 0.01-0.5   | 56        | 10.43%  |
| 1.01-2.0   | 34        | 6.33%   |
| 0.51-1.0   | 33        | 6.15%   |
| 3.01-4.0   | 18        | 3.35%   |
| 7.01-8.0   | 8         | 1.49%   |
| 8.01-16.0  | 6         | 1.12%   |
| 5.01-6.0   | 3         | 0.56%   |
| 2.01-3.0   | 2         | 0.37%   |
| 32.01-64.0 | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 72        | 13.02%  |
| Samsung Electronics     | 61        | 11.03%  |
| BOE                     | 54        | 9.76%   |
| LG Display              | 48        | 8.68%   |
| Dell                    | 45        | 8.14%   |
| Chimei Innolux          | 45        | 8.14%   |
| Goldstar                | 21        | 3.8%    |
| Hewlett-Packard         | 20        | 3.62%   |
| AOC                     | 16        | 2.89%   |
| Acer                    | 15        | 2.71%   |
| Lenovo                  | 11        | 1.99%   |
| BenQ                    | 10        | 1.81%   |
| ViewSonic               | 9         | 1.63%   |
| Philips                 | 9         | 1.63%   |
| Iiyama                  | 9         | 1.63%   |
| Chi Mei Optoelectronics | 9         | 1.63%   |
| Apple                   | 9         | 1.63%   |
| InfoVision              | 7         | 1.27%   |
| Ancor Communications    | 7         | 1.27%   |
| PANDA                   | 6         | 1.08%   |
| LG Philips              | 5         | 0.9%    |
| Sharp                   | 4         | 0.72%   |
| RTK                     | 4         | 0.72%   |
| Fujitsu Siemens         | 4         | 0.72%   |
| Sony                    | 3         | 0.54%   |
| KDC                     | 3         | 0.54%   |
| Vizio                   | 2         | 0.36%   |
| Unknown                 | 2         | 0.36%   |
| Toshiba                 | 2         | 0.36%   |
| Envision Peripherals    | 2         | 0.36%   |
| Eizo                    | 2         | 0.36%   |
| ASUSTek Computer        | 2         | 0.36%   |
| Unknown                 | 2         | 0.36%   |
| ___                     | 1         | 0.18%   |
| Vita                    | 1         | 0.18%   |
| Vestel Elektronik       | 1         | 0.18%   |
| Unknown (AAA)           | 1         | 0.18%   |
| UGD                     | 1         | 0.18%   |
| TEO                     | 1         | 0.18%   |
| Tech Concepts           | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 3         | 0.53%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.53%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 2         | 0.35%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                    | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.35%   |
| RTK AIO PC RTK2136 1920x1080 473x296mm 22.0-inch                         | 2         | 0.35%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                       | 2         | 0.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.35%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 2         | 0.35%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.35%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.35%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 2         | 0.35%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.35%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                      | 2         | 0.35%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch               | 2         | 0.35%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch         | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.35%   |
| BOE LCD Monitor BOE092E 1920x1080 310x173mm 14.0-inch                    | 2         | 0.35%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.35%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 2         | 0.35%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.35%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.35%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                       | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 236       | 44.11%  |
| 1366x768 (WXGA)    | 110       | 20.56%  |
| 1600x900 (HD+)     | 33        | 6.17%   |
| 2560x1440 (QHD)    | 20        | 3.74%   |
| 3840x2160 (4K)     | 19        | 3.55%   |
| 1920x1200 (WUXGA)  | 17        | 3.18%   |
| 1280x800 (WXGA)    | 17        | 3.18%   |
| 1280x1024 (SXGA)   | 17        | 3.18%   |
| 1440x900 (WXGA+)   | 15        | 2.8%    |
| 1680x1050 (WSXGA+) | 9         | 1.68%   |
| 1360x768           | 5         | 0.93%   |
| 1024x768 (XGA)     | 5         | 0.93%   |
| 3440x1440          | 4         | 0.75%   |
| 3840x1080          | 3         | 0.56%   |
| 2560x1600          | 3         | 0.56%   |
| 2160x1440          | 3         | 0.56%   |
| 1600x1200          | 3         | 0.56%   |
| 1024x600           | 3         | 0.56%   |
| 3840x1600          | 2         | 0.37%   |
| 2560x1080          | 2         | 0.37%   |
| Unknown            | 2         | 0.37%   |
| 2880x1800          | 1         | 0.19%   |
| 2288x1287          | 1         | 0.19%   |
| 2048x1152          | 1         | 0.19%   |
| 1920x540           | 1         | 0.19%   |
| 1920x515           | 1         | 0.19%   |
| 1366x912           | 1         | 0.19%   |
| 1280x720 (HD)      | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 139       | 24.91%  |
| 14      | 55        | 9.86%   |
| 13      | 45        | 8.06%   |
| 23      | 43        | 7.71%   |
| 24      | 39        | 6.99%   |
| 27      | 34        | 6.09%   |
| 17      | 34        | 6.09%   |
| 21      | 28        | 5.02%   |
| 19      | 18        | 3.23%   |
| Unknown | 17        | 3.05%   |
| 18      | 15        | 2.69%   |
| 20      | 13        | 2.33%   |
| 11      | 13        | 2.33%   |
| 12      | 12        | 2.15%   |
| 31      | 8         | 1.43%   |
| 16      | 6         | 1.08%   |
| 34      | 5         | 0.9%    |
| 26      | 5         | 0.9%    |
| 22      | 4         | 0.72%   |
| 40      | 3         | 0.54%   |
| 25      | 3         | 0.54%   |
| 10      | 3         | 0.54%   |
| 84      | 2         | 0.36%   |
| 72      | 2         | 0.36%   |
| 54      | 2         | 0.36%   |
| 37      | 2         | 0.36%   |
| 32      | 2         | 0.36%   |
| 142     | 1         | 0.18%   |
| 49      | 1         | 0.18%   |
| 42      | 1         | 0.18%   |
| 30      | 1         | 0.18%   |
| 29      | 1         | 0.18%   |
| 6       | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 230       | 41.97%  |
| 501-600        | 112       | 20.44%  |
| 401-500        | 72        | 13.14%  |
| 201-300        | 46        | 8.39%   |
| 351-400        | 34        | 6.2%    |
| Unknown        | 17        | 3.1%    |
| 601-700        | 15        | 2.74%   |
| 701-800        | 7         | 1.28%   |
| 801-900        | 5         | 0.91%   |
| 1501-2000      | 4         | 0.73%   |
| 1001-1500      | 3         | 0.55%   |
| More than 2000 | 1         | 0.18%   |
| 101-200        | 1         | 0.18%   |
| 901-1000       | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 399       | 78.08%  |
| 16/10   | 63        | 12.33%  |
| 5/4     | 13        | 2.54%   |
| Unknown | 11        | 2.15%   |
| 4/3     | 9         | 1.76%   |
| 21/9    | 7         | 1.37%   |
| 3/2     | 5         | 0.98%   |
| 6/5     | 1         | 0.2%    |
| 32/9    | 1         | 0.2%    |
| 3.73    | 1         | 0.2%    |
| 1.00    | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 138       | 24.95%  |
| 201-250        | 93        | 16.82%  |
| 81-90          | 87        | 15.73%  |
| 151-200        | 43        | 7.78%   |
| 301-350        | 37        | 6.69%   |
| 141-150        | 21        | 3.8%    |
| 121-130        | 20        | 3.62%   |
| 351-500        | 17        | 3.07%   |
| Unknown        | 17        | 3.07%   |
| 71-80          | 13        | 2.35%   |
| 51-60          | 13        | 2.35%   |
| 251-300        | 13        | 2.35%   |
| 61-70          | 11        | 1.99%   |
| More than 1000 | 7         | 1.27%   |
| 131-140        | 7         | 1.27%   |
| 501-1000       | 6         | 1.08%   |
| 111-120        | 4         | 0.72%   |
| 41-50          | 3         | 0.54%   |
| 91-100         | 2         | 0.36%   |
| 1-40           | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 183       | 34.14%  |
| 121-160       | 157       | 29.29%  |
| 101-120       | 150       | 27.99%  |
| 161-240       | 18        | 3.36%   |
| Unknown       | 17        | 3.17%   |
| 1-50          | 7         | 1.31%   |
| More than 240 | 4         | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 444       | 83.15%  |
| 2     | 62        | 11.61%  |
| 0     | 20        | 3.75%   |
| 3     | 8         | 1.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 295       | 38.11%  |
| Intel                             | 258       | 33.33%  |
| Qualcomm Atheros                  | 71        | 9.17%   |
| Broadcom                          | 36        | 4.65%   |
| Ralink Technology                 | 10        | 1.29%   |
| MediaTek                          | 10        | 1.29%   |
| Marvell Technology Group          | 10        | 1.29%   |
| TP-Link                           | 8         | 1.03%   |
| Broadcom Limited                  | 7         | 0.9%    |
| Samsung Electronics               | 5         | 0.65%   |
| Dell                              | 5         | 0.65%   |
| Sierra Wireless                   | 4         | 0.52%   |
| Ralink                            | 4         | 0.52%   |
| Qualcomm                          | 4         | 0.52%   |
| Nvidia                            | 4         | 0.52%   |
| Microchip Technology              | 3         | 0.39%   |
| Huawei Technologies               | 3         | 0.39%   |
| ASIX Electronics                  | 3         | 0.39%   |
| Aquantia                          | 3         | 0.39%   |
| Xiaomi                            | 2         | 0.26%   |
| Qualcomm Atheros Communications   | 2         | 0.26%   |
| OPPO Electronics                  | 2         | 0.26%   |
| Insyde Software                   | 2         | 0.26%   |
| Hewlett-Packard                   | 2         | 0.26%   |
| D-Link System                     | 2         | 0.26%   |
| Belkin Components                 | 2         | 0.26%   |
| ZyDAS                             | 1         | 0.13%   |
| Zoom Telephonics                  | 1         | 0.13%   |
| TRENDnet                          | 1         | 0.13%   |
| NetGear                           | 1         | 0.13%   |
| Microsoft                         | 1         | 0.13%   |
| MicroPython                       | 1         | 0.13%   |
| Mellanox Technologies             | 1         | 0.13%   |
| LG Electronics                    | 1         | 0.13%   |
| JMicron Technology                | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| Ericsson Business Mobile Networks | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| BUFFALO                           | 1         | 0.13%   |
| Attansic Technology               | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 192       | 20.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 2.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 2.07%   |
| Intel Wi-Fi 6 AX200                                               | 18        | 1.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 1.86%   |
| Intel Wireless 8260                                               | 16        | 1.75%   |
| Intel Wireless 7265                                               | 16        | 1.75%   |
| Intel Wi-Fi 6 AX201                                               | 15        | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 1.31%   |
| Intel Wireless 7260                                               | 12        | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 11        | 1.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 10        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 0.98%   |
| Intel Wireless 3165                                               | 9         | 0.98%   |
| Intel I211 Gigabit Network Connection                             | 9         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9         | 0.98%   |
| Realtek 802.11ac NIC                                              | 8         | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.87%   |
| Intel Wireless 3160                                               | 8         | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 6         | 0.66%   |
| Intel Wireless 8265 / 8275                                        | 6         | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 0.66%   |
| Intel Ethernet Controller I225-V                                  | 6         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.55%   |
| Realtek 802.11n WLAN Adapter                                      | 5         | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.55%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 195       | 45.88%  |
| Realtek Semiconductor           | 88        | 20.71%  |
| Qualcomm Atheros                | 65        | 15.29%  |
| Broadcom                        | 19        | 4.47%   |
| Ralink Technology               | 10        | 2.35%   |
| MediaTek                        | 10        | 2.35%   |
| TP-Link                         | 7         | 1.65%   |
| Sierra Wireless                 | 4         | 0.94%   |
| Ralink                          | 4         | 0.94%   |
| Qualcomm                        | 4         | 0.94%   |
| Dell                            | 3         | 0.71%   |
| Qualcomm Atheros Communications | 2         | 0.47%   |
| Broadcom Limited                | 2         | 0.47%   |
| Belkin Components               | 2         | 0.47%   |
| ZyDAS                           | 1         | 0.24%   |
| TRENDnet                        | 1         | 0.24%   |
| NetGear                         | 1         | 0.24%   |
| Microsoft                       | 1         | 0.24%   |
| Marvell Technology Group        | 1         | 0.24%   |
| Fibocom                         | 1         | 0.24%   |
| D-Link System                   | 1         | 0.24%   |
| D-Link                          | 1         | 0.24%   |
| BUFFALO                         | 1         | 0.24%   |
| ASUSTek Computer                | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19        | 4.41%   |
| Intel Wi-Fi 6 AX200                                            | 18        | 4.18%   |
| Intel Wireless 8260                                            | 16        | 3.71%   |
| Intel Wireless 7265                                            | 16        | 3.71%   |
| Intel Wi-Fi 6 AX201                                            | 15        | 3.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 13        | 3.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 2.78%   |
| Intel Wireless 7260                                            | 12        | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10        | 2.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 2.09%   |
| Intel Wireless 3165                                            | 9         | 2.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 2.09%   |
| Realtek 802.11ac NIC                                           | 8         | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 1.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 1.86%   |
| Intel Wireless 3160                                            | 8         | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 1.62%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 1.39%   |
| Intel Wireless 8265 / 8275                                     | 6         | 1.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 6         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 1.16%   |
| Realtek 802.11n WLAN Adapter                                   | 5         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 1.16%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.93%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.93%   |
| Intel Ultimate N WiFi Link 5300                                | 4         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 252       | 54.19%  |
| Intel                    | 132       | 28.39%  |
| Broadcom                 | 21        | 4.52%   |
| Qualcomm Atheros         | 14        | 3.01%   |
| Marvell Technology Group | 9         | 1.94%   |
| Broadcom Limited         | 5         | 1.08%   |
| Nvidia                   | 4         | 0.86%   |
| Samsung Electronics      | 3         | 0.65%   |
| Huawei Technologies      | 3         | 0.65%   |
| ASIX Electronics         | 3         | 0.65%   |
| Aquantia                 | 3         | 0.65%   |
| Xiaomi                   | 2         | 0.43%   |
| OPPO Electronics         | 2         | 0.43%   |
| Microchip Technology     | 2         | 0.43%   |
| Insyde Software          | 2         | 0.43%   |
| Hewlett-Packard          | 2         | 0.43%   |
| TP-Link                  | 1         | 0.22%   |
| LG Electronics           | 1         | 0.22%   |
| JMicron Technology       | 1         | 0.22%   |
| D-Link System            | 1         | 0.22%   |
| Attansic Technology      | 1         | 0.22%   |
| Apple                    | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 192       | 40.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 31        | 6.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 4%      |
| Realtek RTL8125 2.5GbE Controller                                              | 17        | 3.58%   |
| Intel Ethernet Connection (2) I219-V                                           | 11        | 2.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 1.89%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 1.89%   |
| Intel Ethernet Connection I219-LM                                              | 8         | 1.68%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 1.68%   |
| Intel Ethernet Controller I225-V                                               | 6         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 1.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 0.84%   |
| Nvidia MCP61 Ethernet                                                          | 4         | 0.84%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 0.84%   |
| Intel Ethernet Connection I217-V                                               | 4         | 0.84%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.63%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.63%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.63%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.63%   |
| Intel Ethernet Connection (16) I219-V                                          | 3         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 0.63%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.63%   |
| Huawei WLZ-AN00                                                                | 3         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.42%   |
| OPPO SM6375-QRD _SN:F4A23F05                                                   | 2         | 0.42%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 2         | 0.42%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.42%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 2         | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.42%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.42%   |
| Intel Ethernet Connection (17) I219-V                                          | 2         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 435       | 51.54%  |
| WiFi     | 399       | 47.27%  |
| Modem    | 9         | 1.07%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 326       | 59.82%  |
| Ethernet | 219       | 40.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 279       | 52.25%  |
| 1     | 217       | 40.64%  |
| 0     | 26        | 4.87%   |
| 3     | 8         | 1.5%    |
| 4     | 4         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 360       | 66.79%  |
| Yes  | 179       | 33.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 146       | 46.79%  |
| Realtek Semiconductor           | 43        | 13.78%  |
| Cambridge Silicon Radio         | 20        | 6.41%   |
| Broadcom                        | 19        | 6.09%   |
| Qualcomm Atheros Communications | 14        | 4.49%   |
| Lite-On Technology              | 14        | 4.49%   |
| IMC Networks                    | 11        | 3.53%   |
| Foxconn / Hon Hai               | 11        | 3.53%   |
| Apple                           | 8         | 2.56%   |
| Hewlett-Packard                 | 4         | 1.28%   |
| Dell                            | 4         | 1.28%   |
| Realtek                         | 3         | 0.96%   |
| MediaTek                        | 2         | 0.64%   |
| ASUSTek Computer                | 2         | 0.64%   |
| USI                             | 1         | 0.32%   |
| TP-Link                         | 1         | 0.32%   |
| Toshiba                         | 1         | 0.32%   |
| Taiyo Yuden                     | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| Micro Star International        | 1         | 0.32%   |
| Marvell Semiconductor           | 1         | 0.32%   |
| Fujitsu                         | 1         | 0.32%   |
| Foxconn International           | 1         | 0.32%   |
| Chicony Electronics             | 1         | 0.32%   |
| Alps Electric                   | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 65        | 20.77%  |
| Realtek Bluetooth Radio                                                             | 32        | 10.22%  |
| Intel AX201 Bluetooth                                                               | 25        | 7.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 20        | 6.39%   |
| Intel AX200 Bluetooth                                                               | 17        | 5.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 3.51%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 2.88%   |
| Intel Bluetooth Device                                                              | 9         | 2.88%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 2.56%   |
| Intel AX210 Bluetooth                                                               | 8         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.92%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.28%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.28%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 0.96%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 0.96%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.96%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.96%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.96%   |
| Apple Bluetooth Host Controller                                                     | 3         | 0.96%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.64%   |
| MediaTek Wireless_Device                                                            | 2         | 0.64%   |
| Lite-On Wireless_Device                                                             | 2         | 0.64%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.64%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.64%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.64%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.64%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.64%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.64%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.64%   |
| USI Bluetooth Device                                                                | 1         | 0.32%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.32%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.32%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 384       | 57.66%  |
| AMD                         | 135       | 20.27%  |
| Nvidia                      | 90        | 13.51%  |
| C-Media Electronics         | 7         | 1.05%   |
| Texas Instruments           | 5         | 0.75%   |
| Creative Labs               | 4         | 0.6%    |
| Generalplus Technology      | 3         | 0.45%   |
| ASUSTek Computer            | 3         | 0.45%   |
| VIA Technologies            | 2         | 0.3%    |
| SAVITECH                    | 2         | 0.3%    |
| Medeli Electronics          | 2         | 0.3%    |
| Logitech                    | 2         | 0.3%    |
| JMTek                       | 2         | 0.3%    |
| GN Netcom                   | 2         | 0.3%    |
| Creative Technology         | 2         | 0.3%    |
| BEHRINGER International     | 2         | 0.3%    |
| Trust International         | 1         | 0.15%   |
| Textech International       | 1         | 0.15%   |
| Tenx Technology             | 1         | 0.15%   |
| STMicroelectronics          | 1         | 0.15%   |
| Sennheiser Communications   | 1         | 0.15%   |
| Samson Technologies         | 1         | 0.15%   |
| Roland                      | 1         | 0.15%   |
| Realtek Semiconductor       | 1         | 0.15%   |
| PreSonus Audio Electronics  | 1         | 0.15%   |
| Plantronics                 | 1         | 0.15%   |
| Micro Star International    | 1         | 0.15%   |
| MAG Technology              | 1         | 0.15%   |
| M-Audio                     | 1         | 0.15%   |
| Lenovo                      | 1         | 0.15%   |
| Kingston Technology         | 1         | 0.15%   |
| Hewlett-Packard             | 1         | 0.15%   |
| FiiO Electronics Technology | 1         | 0.15%   |
| Corsair                     | 1         | 0.15%   |
| Conexant Systems            | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 40        | 5.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 32        | 4.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 30        | 3.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 3.54%   |
| AMD FCH Azalia Controller                                                                         | 28        | 3.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 2.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 22        | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 2.15%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 17        | 2.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 2.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 16        | 2.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 2.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 1.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.14%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 1.14%   |
| Intel 200 Series PCH HD Audio                                                                     | 9         | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.01%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 8         | 1.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 8         | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.76%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 0.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 105       | 23.7%   |
| Unknown                    | 64        | 14.45%  |
| SK hynix                   | 64        | 14.45%  |
| Kingston                   | 49        | 11.06%  |
| Crucial                    | 32        | 7.22%   |
| Micron Technology          | 31        | 7%      |
| G.Skill                    | 15        | 3.39%   |
| Unknown (ABCD)             | 14        | 3.16%   |
| Ramaxel Technology         | 12        | 2.71%   |
| Corsair                    | 11        | 2.48%   |
| Nanya Technology           | 7         | 1.58%   |
| Elpida                     | 5         | 1.13%   |
| A-DATA Technology          | 5         | 1.13%   |
| Smart                      | 4         | 0.9%    |
| Transcend                  | 3         | 0.68%   |
| fef5                       | 3         | 0.68%   |
| Unknown                    | 3         | 0.68%   |
| V-Color                    | 2         | 0.45%   |
| Unknown (AB)               | 1         | 0.23%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.23%   |
| Unifosa                    | 1         | 0.23%   |
| Timetec                    | 1         | 0.23%   |
| Qumo                       | 1         | 0.23%   |
| Qimonda                    | 1         | 0.23%   |
| GLOWAY                     | 1         | 0.23%   |
| GIGA-BYTE                  | 1         | 0.23%   |
| Foxline                    | 1         | 0.23%   |
| Essencore                  | 1         | 0.23%   |
| Daten Tecnologia           | 1         | 0.23%   |
| Avant                      | 1         | 0.23%   |
| ASint Technology           | 1         | 0.23%   |
| 48spaces                   | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 10        | 2.16%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 6         | 1.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 1.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 5         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 4         | 0.86%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 4         | 0.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 4         | 0.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 4         | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 4         | 0.86%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 3         | 0.65%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                         | 3         | 0.65%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 3         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                        | 3         | 0.65%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 0.65%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s          | 3         | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 3         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 3         | 0.65%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s          | 3         | 0.65%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 3         | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.65%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                   | 3         | 0.65%   |
| Samsung RAM K3LKCKC0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s      | 3         | 0.65%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                             | 3         | 0.65%   |
| Unknown                                                           | 3         | 0.65%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 2         | 0.43%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                              | 2         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 1GB SODIMM LPDDR3 1600MT/s                     | 2         | 0.43%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.43%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.43%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s              | 2         | 0.43%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s            | 2         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 2         | 0.43%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 153       | 39.95%  |
| DDR3    | 132       | 34.46%  |
| LPDDR4  | 29        | 7.57%   |
| DDR2    | 24        | 6.27%   |
| Unknown | 13        | 3.39%   |
| SDRAM   | 12        | 3.13%   |
| LPDDR3  | 9         | 2.35%   |
| LPDDR5  | 5         | 1.31%   |
| DDR5    | 4         | 1.04%   |
| DRAM    | 1         | 0.26%   |
| DDR     | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 215       | 56.58%  |
| DIMM         | 131       | 34.47%  |
| Row Of Chips | 24        | 6.32%   |
| Unknown      | 7         | 1.84%   |
| Chip         | 3         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 134       | 32.76%  |
| 4096  | 114       | 27.87%  |
| 2048  | 73        | 17.85%  |
| 16384 | 60        | 14.67%  |
| 1024  | 18        | 4.4%    |
| 32768 | 7         | 1.71%   |
| 65536 | 1         | 0.24%   |
| 1536  | 1         | 0.24%   |
| 512   | 1         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 88        | 21.95%  |
| 3200    | 66        | 16.46%  |
| 2667    | 38        | 9.48%   |
| 2400    | 34        | 8.48%   |
| 1333    | 28        | 6.98%   |
| 2133    | 19        | 4.74%   |
| 667     | 12        | 2.99%   |
| 1334    | 11        | 2.74%   |
| Unknown | 10        | 2.49%   |
| 3600    | 9         | 2.24%   |
| 1067    | 7         | 1.75%   |
| 4267    | 6         | 1.5%    |
| 1066    | 6         | 1.5%    |
| 1867    | 5         | 1.25%   |
| 800     | 5         | 1.25%   |
| 6400    | 4         | 1%      |
| 3266    | 4         | 1%      |
| 3000    | 4         | 1%      |
| 2666    | 4         | 1%      |
| 1866    | 4         | 1%      |
| 4800    | 3         | 0.75%   |
| 4199    | 3         | 0.75%   |
| 3466    | 3         | 0.75%   |
| 4266    | 2         | 0.5%    |
| 2048    | 2         | 0.5%    |
| 1800    | 2         | 0.5%    |
| 975     | 2         | 0.5%    |
| 533     | 2         | 0.5%    |
| 52217   | 1         | 0.25%   |
| 6000    | 1         | 0.25%   |
| 5500    | 1         | 0.25%   |
| 5354    | 1         | 0.25%   |
| 4000    | 1         | 0.25%   |
| 3866    | 1         | 0.25%   |
| 3733    | 1         | 0.25%   |
| 3400    | 1         | 0.25%   |
| 3333    | 1         | 0.25%   |
| 3020    | 1         | 0.25%   |
| 2800    | 1         | 0.25%   |
| 2134    | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 41.67%  |
| Brother Industries  | 3         | 25%     |
| Samsung Electronics | 1         | 8.33%   |
| Minolta             | 1         | 8.33%   |
| Kyocera             | 1         | 8.33%   |
| Canon               | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SF-760 Series         | 1         | 8.33%   |
| Minolta PagePro 1300W         | 1         | 8.33%   |
| Kyocera FS-1300D              | 1         | 8.33%   |
| HP ENVY Pro 6400 series       | 1         | 8.33%   |
| HP DeskJet D1360              | 1         | 8.33%   |
| HP DeskJet 840c               | 1         | 8.33%   |
| HP DeskJet 810c/812c          | 1         | 8.33%   |
| HP Deskjet 3070 B611 series   | 1         | 8.33%   |
| Canon TS3500 series           | 1         | 8.33%   |
| Brother QL-560 Label Printer  | 1         | 8.33%   |
| Brother HL-2030 Laser Printer | 1         | 8.33%   |
| Brother DCP-7040              | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 75%     |
| Seiko Epson     | 1         | 12.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                | 3         | 37.5%   |
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 12.5%   |
| HP ScanJet 7400c                       | 1         | 12.5%   |
| Canon CanoScan LIDE 25                 | 1         | 12.5%   |
| Canon CanoScan LiDE 110                | 1         | 12.5%   |
| Canon CanoScan 4400F                   | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 74        | 22.63%  |
| Microdia                               | 26        | 7.95%   |
| Realtek Semiconductor                  | 24        | 7.34%   |
| Quanta                                 | 24        | 7.34%   |
| Sunplus Innovation Technology          | 19        | 5.81%   |
| IMC Networks                           | 18        | 5.5%    |
| Cheng Uei Precision Industry (Foxlink) | 18        | 5.5%    |
| Suyin                                  | 14        | 4.28%   |
| Logitech                               | 13        | 3.98%   |
| Bison Electronics                      | 10        | 3.06%   |
| Luxvisions Innotech Limited            | 7         | 2.14%   |
| Apple                                  | 7         | 2.14%   |
| Acer                                   | 6         | 1.83%   |
| Z-Star Microelectronics                | 5         | 1.53%   |
| Syntek                                 | 5         | 1.53%   |
| Silicon Motion                         | 5         | 1.53%   |
| Samsung Electronics                    | 4         | 1.22%   |
| Microsoft                              | 4         | 1.22%   |
| Lite-On Technology                     | 4         | 1.22%   |
| Alcor Micro                            | 4         | 1.22%   |
| Ricoh                                  | 3         | 0.92%   |
| Lenovo                                 | 3         | 0.92%   |
| icSpring                               | 3         | 0.92%   |
| USB Camera CS                          | 2         | 0.61%   |
| SunplusIT                              | 2         | 0.61%   |
| Sonix Technology                       | 2         | 0.61%   |
| KYE Systems (Mouse Systems)            | 2         | 0.61%   |
| ARC International                      | 2         | 0.61%   |
| Xiongmai                               | 1         | 0.31%   |
| Xiaomi                                 | 1         | 0.31%   |
| ValueHD                                | 1         | 0.31%   |
| Sunplus Technology                     | 1         | 0.31%   |
| Ruision                                | 1         | 0.31%   |
| Primax Electronics                     | 1         | 0.31%   |
| OYT Tech                               | 1         | 0.31%   |
| OmniVision Technologies                | 1         | 0.31%   |
| MacroSilicon                           | 1         | 0.31%   |
| Jieli Technology                       | 1         | 0.31%   |
| Importek                               | 1         | 0.31%   |
| Guillemot                              | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 24        | 7.29%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 2.13%   |
| Quanta HD User Facing                               | 7         | 2.13%   |
| Microdia Integrated_Webcam_HD                       | 7         | 2.13%   |
| Chicony HD WebCam                                   | 7         | 2.13%   |
| Logitech C922 Pro Stream Webcam                     | 5         | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 1.52%   |
| Sunplus Integrated_Webcam_FHD                       | 4         | 1.22%   |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 1.22%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 1.22%   |
| IMC Networks Integrated Camera                      | 4         | 1.22%   |
| Chicony TOSHIBA Web Camera - HD                     | 4         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 4         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 1.22%   |
| Acer Integrated Camera                              | 4         | 1.22%   |
| Syntek Integrated Camera                            | 3         | 0.91%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 0.91%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 0.91%   |
| Quanta HP Webcam                                    | 3         | 0.91%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.91%   |
| Quanta HP HD Camera                                 | 3         | 0.91%   |
| Microdia USB 2.0 Camera                             | 3         | 0.91%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 0.91%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 0.91%   |
| icSpring camera                                     | 3         | 0.91%   |
| Chicony USB2.0 Camera                               | 3         | 0.91%   |
| Chicony HP TrueVision HD Camera                     | 3         | 0.91%   |
| Chicony HP Truevision HD                            | 3         | 0.91%   |
| Chicony EasyCamera                                  | 3         | 0.91%   |
| Bison SunplusIT Integrated Camera                   | 3         | 0.91%   |
| Apple Built-in iSight                               | 3         | 0.91%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 0.91%   |
| USB Camera CS USB Camera CS                         | 2         | 0.61%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.61%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 0.61%   |
| Realtek USB Camera                                  | 2         | 0.61%   |
| Realtek Lenovo EasyCamera                           | 2         | 0.61%   |
| Realtek HP Truevision HD                            | 2         | 0.61%   |
| Realtek HD WebCam                                   | 2         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 16        | 30.77%  |
| Shenzhen Goodix Technology         | 10        | 19.23%  |
| Upek                               | 7         | 13.46%  |
| Synaptics                          | 7         | 13.46%  |
| Elan Microelectronics              | 4         | 7.69%   |
| STMicroelectronics                 | 2         | 3.85%   |
| AuthenTec                          | 2         | 3.85%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.92%   |
| LighTuning Technology              | 1         | 1.92%   |
| Gingytech                          | 1         | 1.92%   |
| Focal-systems.Corp                 | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 7         | 13.46%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 6         | 11.54%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 6         | 11.54%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 4         | 7.69%   |
| Validity Sensors Synaptics WBDI                                 | 3         | 5.77%   |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 5.77%   |
| Elan ELAN:ARM-M4                                                | 3         | 5.77%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 3.85%   |
| Synaptics UWP WBDI Device                                       | 2         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 3.85%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 3.85%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 1.92%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 1.92%   |
| Synaptics  WBDI                                                 | 1         | 1.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 1.92%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.92%   |
| LighTuning Fingerprint Sensor                                   | 1         | 1.92%   |
| Gingytech Fingerprint sensor                                    | 1         | 1.92%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.92%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.92%   |
| AuthenTec AES2810                                               | 1         | 1.92%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 13        | 41.94%  |
| Alcor Micro              | 10        | 32.26%  |
| O2 Micro                 | 3         | 9.68%   |
| Lenovo                   | 3         | 9.68%   |
| Reiner SCT Kartensysteme | 1         | 3.23%   |
| In Focus Systems         | 1         | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 32.26%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 16.13%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 9.68%   |
| Broadcom 5880                                                                | 3         | 9.68%   |
| Broadcom 58200                                                               | 3         | 9.68%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.45%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 3.23%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.23%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 389       | 72.17%  |
| 1     | 117       | 21.71%  |
| 2     | 26        | 4.82%   |
| 3     | 6         | 1.11%   |
| 5     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 50        | 27.47%  |
| Graphics card            | 37        | 20.33%  |
| Chipcard                 | 30        | 16.48%  |
| Camera                   | 16        | 8.79%   |
| Net/wireless             | 11        | 6.04%   |
| Multimedia controller    | 8         | 4.4%    |
| Unassigned class         | 5         | 2.75%   |
| Communication controller | 5         | 2.75%   |
| Bluetooth                | 5         | 2.75%   |
| Network                  | 4         | 2.2%    |
| Card reader              | 4         | 2.2%    |
| Storage                  | 2         | 1.1%    |
| Sound                    | 2         | 1.1%    |
| Net/ethernet             | 2         | 1.1%    |
| Dvb card                 | 1         | 0.55%   |

