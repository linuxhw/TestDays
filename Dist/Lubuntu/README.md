Lubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

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

Total: 1881

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Positivo      | C4128B-1                    | Convertible | [ef67e885dc](https://linux-hardware.org/?probe=ef67e885dc) | Aug 11, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [0028486d9d](https://linux-hardware.org/?probe=0028486d9d) | Aug 10, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Toshiba       | Satellite L875D             | Notebook    | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [3e037493db](https://linux-hardware.org/?probe=3e037493db) | Aug 06, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Unknown       | SCHNEIDER                   | Desktop     | [6ab609f07e](https://linux-hardware.org/?probe=6ab609f07e) | Jul 27, 2023 |
| Dell          | Inspiron 1520               | Notebook    | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | Notebook    | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4fe4e8b639](https://linux-hardware.org/?probe=4fe4e8b639) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [742d3b24c8](https://linux-hardware.org/?probe=742d3b24c8) | Jul 24, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | Notebook    | [c7dd142af9](https://linux-hardware.org/?probe=c7dd142af9) | Jul 24, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| HP            | 2187 A01                    | Desktop     | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| HP            | 3646h                       | Desktop     | [01f2207fe0](https://linux-hardware.org/?probe=01f2207fe0) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| Dell          | Latitude 5290               | Notebook    | [66860827b9](https://linux-hardware.org/?probe=66860827b9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Fujitsu       | FMVNC4BC4                   | Notebook    | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | Notebook    | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | Notebook    | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [07809870aa](https://linux-hardware.org/?probe=07809870aa) | Jul 19, 2023 |
| LG Electro... | 15Z90N-U.ARS5U1             | Notebook    | [54b03a096b](https://linux-hardware.org/?probe=54b03a096b) | Jul 19, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [2d896167d8](https://linux-hardware.org/?probe=2d896167d8) | Jul 16, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [493d7a5ab7](https://linux-hardware.org/?probe=493d7a5ab7) | Jul 12, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d0035bb703](https://linux-hardware.org/?probe=d0035bb703) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [8fb942eccd](https://linux-hardware.org/?probe=8fb942eccd) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [ff650dc0df](https://linux-hardware.org/?probe=ff650dc0df) | Jul 10, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f1b70e168](https://linux-hardware.org/?probe=2f1b70e168) | Jul 08, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [6535e7c6d1](https://linux-hardware.org/?probe=6535e7c6d1) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [282c9db256](https://linux-hardware.org/?probe=282c9db256) | Jul 08, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [8337bfbb61](https://linux-hardware.org/?probe=8337bfbb61) | Jul 08, 2023 |
| Acer          | Swift SFE16-42              | Notebook    | [c8b8a7d737](https://linux-hardware.org/?probe=c8b8a7d737) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | Notebook    | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Unknown       | Unknown                     | Other       | [f49e789b52](https://linux-hardware.org/?probe=f49e789b52) | Jul 04, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Google        | Pyro                        | Notebook    | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| eMachines     | eME443                      | Notebook    | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [7c6c7cff66](https://linux-hardware.org/?probe=7c6c7cff66) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f0268ac6a8](https://linux-hardware.org/?probe=f0268ac6a8) | Jun 26, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [e094f469bc](https://linux-hardware.org/?probe=e094f469bc) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| Pencents      | U50 Standard                | Mini pc     | [96db8365b1](https://linux-hardware.org/?probe=96db8365b1) | Jun 20, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| ASUSTek       | 1011CX                      | Notebook    | [0fa6b0b3dc](https://linux-hardware.org/?probe=0fa6b0b3dc) | Jun 19, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [b4c617c995](https://linux-hardware.org/?probe=b4c617c995) | Jun 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [009fdf15c4](https://linux-hardware.org/?probe=009fdf15c4) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e4c0eeb007](https://linux-hardware.org/?probe=e4c0eeb007) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [af1a5cda08](https://linux-hardware.org/?probe=af1a5cda08) | Jun 16, 2023 |
| Dell          | Precision 3570              | Notebook    | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | 21B4 A01                    | Desktop     | [16b576ebea](https://linux-hardware.org/?probe=16b576ebea) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| HP            | 3646h                       | Desktop     | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | Notebook    | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 3646h                       | Desktop     | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [b6411e69f3](https://linux-hardware.org/?probe=b6411e69f3) | Jun 04, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [1375d36b0f](https://linux-hardware.org/?probe=1375d36b0f) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [88c6b12404](https://linux-hardware.org/?probe=88c6b12404) | May 27, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [84953a504d](https://linux-hardware.org/?probe=84953a504d) | May 26, 2023 |
| Dell          | Latitude E6430              | Notebook    | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [f19d94af88](https://linux-hardware.org/?probe=f19d94af88) | May 18, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [a75df73ade](https://linux-hardware.org/?probe=a75df73ade) | May 18, 2023 |
| Lenovo        | ThinkPad T400 276522G       | Notebook    | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | Notebook    | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | Notebook    | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | Notebook    | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Acer          | EQ45M                       | Desktop     | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [9709c9cf35](https://linux-hardware.org/?probe=9709c9cf35) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| HP            | Notebook                    | Notebook    | [70ee3adf89](https://linux-hardware.org/?probe=70ee3adf89) | May 08, 2023 |
| Samsung       | 530XBB                      | Notebook    | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| Sony          | SVF1521C6EW                 | Notebook    | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| HP            | Laptop 15-bs2xx             | Notebook    | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Google        | Chell                       | Notebook    | [1d1b263f21](https://linux-hardware.org/?probe=1d1b263f21) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| ASUSTek       | F1A55-M LK R2.0             | Desktop     | [234e0d0738](https://linux-hardware.org/?probe=234e0d0738) | Apr 23, 2023 |
| Dell          | Latitude 5290               | Notebook    | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [f79af9bad0](https://linux-hardware.org/?probe=f79af9bad0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [70a0b986fa](https://linux-hardware.org/?probe=70a0b986fa) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| Intel         | W7650                       | Notebook    | [3e4c54a5f0](https://linux-hardware.org/?probe=3e4c54a5f0) | Apr 11, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b16afcac8b](https://linux-hardware.org/?probe=b16afcac8b) | Apr 03, 2023 |
| ASRock        | G31M-S                      | Desktop     | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| ASRock        | G31M-S                      | Desktop     | [4ad324790c](https://linux-hardware.org/?probe=4ad324790c) | Mar 28, 2023 |
| ASRock        | G31M-S                      | Desktop     | [225f122e05](https://linux-hardware.org/?probe=225f122e05) | Mar 28, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| Packard Be... | EasyNote SB65               | Notebook    | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| ASRock        | N68-GS4/USB3 FX             | Desktop     | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| Samsung       | 530XBB                      | Notebook    | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| HP            | 89DC 0100                   | All in one  | [d8afbb81f9](https://linux-hardware.org/?probe=d8afbb81f9) | Mar 21, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | Notebook    | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Dell          | Latitude 5290               | Notebook    | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [309d95f00f](https://linux-hardware.org/?probe=309d95f00f) | Mar 11, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [256a8abb58](https://linux-hardware.org/?probe=256a8abb58) | Mar 06, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [dbe64de6bd](https://linux-hardware.org/?probe=dbe64de6bd) | Mar 06, 2023 |
| ASUSTek       | A7N8X-E                     | Desktop     | [d0847fb118](https://linux-hardware.org/?probe=d0847fb118) | Mar 06, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f4e7268671](https://linux-hardware.org/?probe=f4e7268671) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [1eef9edf97](https://linux-hardware.org/?probe=1eef9edf97) | Mar 04, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b492e1c092](https://linux-hardware.org/?probe=b492e1c092) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| DEXP          | Aquilon C15                 | Notebook    | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Google        | Celes                       | Notebook    | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | Notebook    | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Acer          | Aspire Z5101                | All in one  | [ec55f791bb](https://linux-hardware.org/?probe=ec55f791bb) | Feb 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | Aspire Z5101                | All in one  | [3dd821cc61](https://linux-hardware.org/?probe=3dd821cc61) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [9c3a1f5cd5](https://linux-hardware.org/?probe=9c3a1f5cd5) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [4b440b2084](https://linux-hardware.org/?probe=4b440b2084) | Feb 22, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [11739ccfa1](https://linux-hardware.org/?probe=11739ccfa1) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [1c2d1949fd](https://linux-hardware.org/?probe=1c2d1949fd) | Feb 19, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [edfa765236](https://linux-hardware.org/?probe=edfa765236) | Feb 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [41a31b6bd1](https://linux-hardware.org/?probe=41a31b6bd1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2420c1fb57](https://linux-hardware.org/?probe=2420c1fb57) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [d159971f77](https://linux-hardware.org/?probe=d159971f77) | Feb 18, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [72b29b5f80](https://linux-hardware.org/?probe=72b29b5f80) | Feb 16, 2023 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [1fbc4cea88](https://linux-hardware.org/?probe=1fbc4cea88) | Feb 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [49d1ea8b3e](https://linux-hardware.org/?probe=49d1ea8b3e) | Feb 11, 2023 |
| Dell          | 0FPP7F A00                  | Desktop     | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [db3d49fa06](https://linux-hardware.org/?probe=db3d49fa06) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| Toshiba       | Satellite C55D-A            | Notebook    | [38083cc2a4](https://linux-hardware.org/?probe=38083cc2a4) | Feb 05, 2023 |
| Acer          | TravelMate P253             | Notebook    | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Acer          | AO756                       | Notebook    | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [be66e9073f](https://linux-hardware.org/?probe=be66e9073f) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [3a8aced1b7](https://linux-hardware.org/?probe=3a8aced1b7) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [11964c6701](https://linux-hardware.org/?probe=11964c6701) | Jan 16, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| Google        | Candy                       | Notebook    | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [5b907b07e4](https://linux-hardware.org/?probe=5b907b07e4) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| Dell          | 05KX61 A00                  | Server      | [9f365307f3](https://linux-hardware.org/?probe=9f365307f3) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Google        | Edgar                       | Notebook    | [738a0d9324](https://linux-hardware.org/?probe=738a0d9324) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [252a51f201](https://linux-hardware.org/?probe=252a51f201) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | Desktop     | [1505706e04](https://linux-hardware.org/?probe=1505706e04) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | Desktop     | [1c996d8122](https://linux-hardware.org/?probe=1c996d8122) | Dec 25, 2022 |
| HP            | Stream Notebook PC 11       | Notebook    | [f33ebabb99](https://linux-hardware.org/?probe=f33ebabb99) | Dec 24, 2022 |
| HP            | Stream 8 Tablet             | Tablet      | [752a0b9007](https://linux-hardware.org/?probe=752a0b9007) | Dec 23, 2022 |
| Positivo      | C14CR21                     | Notebook    | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | Notebook    | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| Google        | Coral                       | Notebook    | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | Notebook    | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| ASUSTek       | ET1610PT                    | Desktop     | [d8b1840336](https://linux-hardware.org/?probe=d8b1840336) | Dec 03, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| HP            | 620                         | Notebook    | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [03a1a706d1](https://linux-hardware.org/?probe=03a1a706d1) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [63487a2957](https://linux-hardware.org/?probe=63487a2957) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [0b632b7ae8](https://linux-hardware.org/?probe=0b632b7ae8) | Nov 27, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [ba7b5c7748](https://linux-hardware.org/?probe=ba7b5c7748) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [f8e0414c84](https://linux-hardware.org/?probe=f8e0414c84) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | 620                         | Notebook    | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| HP            | 3048h                       | Desktop     | [33ced86304](https://linux-hardware.org/?probe=33ced86304) | Nov 19, 2022 |
| HP            | 3048h                       | Desktop     | [e5fdb1f67a](https://linux-hardware.org/?probe=e5fdb1f67a) | Nov 19, 2022 |
| ASUSTek       | K55A                        | Notebook    | [d09b309d4d](https://linux-hardware.org/?probe=d09b309d4d) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [4825e06bd4](https://linux-hardware.org/?probe=4825e06bd4) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [57bcd4363a](https://linux-hardware.org/?probe=57bcd4363a) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8a149b06a1](https://linux-hardware.org/?probe=8a149b06a1) | Nov 12, 2022 |
| Acer          | AOD255E                     | Notebook    | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Toshiba       | Satellite L15-B             | Notebook    | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Lenovo        | NOK                         | Desktop     | [8c9f8ff505](https://linux-hardware.org/?probe=8c9f8ff505) | Nov 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [027cfb43c4](https://linux-hardware.org/?probe=027cfb43c4) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [113930496e](https://linux-hardware.org/?probe=113930496e) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2934bab108](https://linux-hardware.org/?probe=2934bab108) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [4b4c00b0a9](https://linux-hardware.org/?probe=4b4c00b0a9) | Oct 28, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [9c7127a256](https://linux-hardware.org/?probe=9c7127a256) | Oct 27, 2022 |
| Acer          | Extensa 2509                | Notebook    | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | Desktop     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| Acer          | Aspire one                  | Notebook    | [fced25613a](https://linux-hardware.org/?probe=fced25613a) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| HP            | 431 Notebook                | Notebook    | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| AOpen         | D1007 0BBA                  | Desktop     | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Toshiba       | Satellite C655D             | Notebook    | [80ec8503c0](https://linux-hardware.org/?probe=80ec8503c0) | Oct 05, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [1ad22cf7a8](https://linux-hardware.org/?probe=1ad22cf7a8) | Sep 28, 2022 |
| Dell          | 0PU052                      | Desktop     | [2890a8407e](https://linux-hardware.org/?probe=2890a8407e) | Sep 28, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [cf8128637b](https://linux-hardware.org/?probe=cf8128637b) | Sep 24, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e63b24acc3](https://linux-hardware.org/?probe=e63b24acc3) | Sep 24, 2022 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3468d8c911](https://linux-hardware.org/?probe=3468d8c911) | Sep 24, 2022 |
| Dell          | 0PU052                      | Desktop     | [6ca93366df](https://linux-hardware.org/?probe=6ca93366df) | Sep 23, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| ASUSTek       | X451CA                      | Notebook    | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Star Labs     | Lite                        | Notebook    | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Acer          | AOA150                      | Notebook    | [3146707963](https://linux-hardware.org/?probe=3146707963) | Sep 02, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Standard      | AHV                         | Notebook    | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| ASRock        | A520M-HVS                   | Desktop     | [842ad7d4d2](https://linux-hardware.org/?probe=842ad7d4d2) | Aug 22, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [df6dff3fa3](https://linux-hardware.org/?probe=df6dff3fa3) | Aug 19, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [98c601bb55](https://linux-hardware.org/?probe=98c601bb55) | Aug 08, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [01e4feaac6](https://linux-hardware.org/?probe=01e4feaac6) | Aug 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [49ba856687](https://linux-hardware.org/?probe=49ba856687) | Aug 03, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Toshiba       | NB250                       | Notebook    | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | Presario CQ56               | Notebook    | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | Desktop     | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | 900                         | Notebook    | [ae42d40b7a](https://linux-hardware.org/?probe=ae42d40b7a) | Jul 25, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Samsung       | N130                        | Notebook    | [4874e0173d](https://linux-hardware.org/?probe=4874e0173d) | Jul 17, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [21b83125d8](https://linux-hardware.org/?probe=21b83125d8) | Jul 14, 2022 |
| Standard      | AHV                         | Notebook    | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [08b1b304ae](https://linux-hardware.org/?probe=08b1b304ae) | Jul 11, 2022 |
| Foxconn       | 2ACA                        | Desktop     | [92681ef1e5](https://linux-hardware.org/?probe=92681ef1e5) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [dd80f74e85](https://linux-hardware.org/?probe=dd80f74e85) | Jul 05, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [69e4341e99](https://linux-hardware.org/?probe=69e4341e99) | Jul 05, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [92c11e77c4](https://linux-hardware.org/?probe=92c11e77c4) | Jul 03, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| MSI           | VR630                       | Notebook    | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [357e062693](https://linux-hardware.org/?probe=357e062693) | Jun 25, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [f6f825d83a](https://linux-hardware.org/?probe=f6f825d83a) | Jun 22, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [14ed78a258](https://linux-hardware.org/?probe=14ed78a258) | Jun 11, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| MSI           | MS-AA1511                   | All in one  | [80c9ccb7c7](https://linux-hardware.org/?probe=80c9ccb7c7) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | 3397                        | Desktop     | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| HP            | Berknip                     | Notebook    | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| ASUSTek       | X402CA                      | Notebook    | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [7807aa5ed4](https://linux-hardware.org/?probe=7807aa5ed4) | May 16, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Dell          | 0CRH6C A00                  | Desktop     | [fe2648c1f7](https://linux-hardware.org/?probe=fe2648c1f7) | May 14, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [68ee4b094a](https://linux-hardware.org/?probe=68ee4b094a) | May 13, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5774e3f483](https://linux-hardware.org/?probe=5774e3f483) | May 12, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [f3bd3e55aa](https://linux-hardware.org/?probe=f3bd3e55aa) | May 12, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [3a09364bb2](https://linux-hardware.org/?probe=3a09364bb2) | May 12, 2022 |
| Toshiba       | Satellite P20               | Notebook    | [923779da79](https://linux-hardware.org/?probe=923779da79) | May 11, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Positivo      | AT300b                      | Notebook    | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| ASUSTek       | Rampage III GENE            | Desktop     | [798c1f07f6](https://linux-hardware.org/?probe=798c1f07f6) | May 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| ASUSTek       | 900                         | Notebook    | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | Notebook    | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [4682643304](https://linux-hardware.org/?probe=4682643304) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf9f724f45](https://linux-hardware.org/?probe=bf9f724f45) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [05585fedf4](https://linux-hardware.org/?probe=05585fedf4) | May 04, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| Acer          | Aspire XC100A               | Desktop     | [dbad5c417d](https://linux-hardware.org/?probe=dbad5c417d) | May 04, 2022 |
| ASUSTek       | 900                         | Notebook    | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [dd1df3c77d](https://linux-hardware.org/?probe=dd1df3c77d) | May 02, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| Gigabyte      | M912                        | Notebook    | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [b921f6fbae](https://linux-hardware.org/?probe=b921f6fbae) | Apr 24, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| Mediacom      | GTZS                        | Notebook    | [41939828a4](https://linux-hardware.org/?probe=41939828a4) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [12d817136f](https://linux-hardware.org/?probe=12d817136f) | Apr 22, 2022 |
| Google        | Droid                       | Notebook    | [b7b4dc6117](https://linux-hardware.org/?probe=b7b4dc6117) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| Mediacom      | GTZS                        | Notebook    | [edc22ef82a](https://linux-hardware.org/?probe=edc22ef82a) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| Dell          | Latitude E6410              | Notebook    | [e5e350a4a8](https://linux-hardware.org/?probe=e5e350a4a8) | Apr 13, 2022 |
| Google        | Kip                         | Notebook    | [4641a94428](https://linux-hardware.org/?probe=4641a94428) | Apr 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [1a369ad73a](https://linux-hardware.org/?probe=1a369ad73a) | Apr 12, 2022 |
| ASRock        | G31M-S                      | Desktop     | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Samsung       | 950QDB                      | Convertible | [41d1bb5ecf](https://linux-hardware.org/?probe=41d1bb5ecf) | Apr 08, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Gigabyte      | Q77M-D2H                    | Desktop     | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Samsung       | N100SP                      | Notebook    | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Acer          | AOA150                      | Notebook    | [a59a005250](https://linux-hardware.org/?probe=a59a005250) | Mar 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| Intel         | W7650                       | Notebook    | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | Desktop     | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [abdf251dcf](https://linux-hardware.org/?probe=abdf251dcf) | Mar 25, 2022 |
| Haier         | U1520EM                     | Notebook    | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| HP            | Pavilion g7                 | Notebook    | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| IBM           | Unknown                     | Notebook    | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [d4c7ecbc5e](https://linux-hardware.org/?probe=d4c7ecbc5e) | Mar 20, 2022 |
| Acer          | AO751h                      | Notebook    | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Google        | Celes                       | Notebook    | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [eb7071ed13](https://linux-hardware.org/?probe=eb7071ed13) | Mar 12, 2022 |
| Nvidia        | Tegra                       | Soc         | [3f369fa012](https://linux-hardware.org/?probe=3f369fa012) | Mar 11, 2022 |
| ASRock        | Q1900M                      | Desktop     | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | Notebook    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| ASUSTek       | M2N-SLI                     | Desktop     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [9c8ac31778](https://linux-hardware.org/?probe=9c8ac31778) | Mar 07, 2022 |
| HP            | 3647h                       | Desktop     | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [96416af97f](https://linux-hardware.org/?probe=96416af97f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| HP            | 339A                        | Desktop     | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| Insyde        | N116                        | Notebook    | [a6dd43dfb4](https://linux-hardware.org/?probe=a6dd43dfb4) | Feb 21, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Dell          | 0DR845                      | Desktop     | [73ab1563bc](https://linux-hardware.org/?probe=73ab1563bc) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Alienware     | M17                         | Notebook    | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| Pegatron      | Narra6                      | Desktop     | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [1f9694d47d](https://linux-hardware.org/?probe=1f9694d47d) | Feb 12, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [677d24e366](https://linux-hardware.org/?probe=677d24e366) | Feb 11, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [3731e90788](https://linux-hardware.org/?probe=3731e90788) | Feb 11, 2022 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [b3977cd496](https://linux-hardware.org/?probe=b3977cd496) | Feb 10, 2022 |
| Positivo      | N600                        | Notebook    | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | Notebook    | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| ASUSTek       | Puffer                      | Desktop     | [a14c8ed9ad](https://linux-hardware.org/?probe=a14c8ed9ad) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | Desktop     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [695855f143](https://linux-hardware.org/?probe=695855f143) | Feb 05, 2022 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [661ffedd80](https://linux-hardware.org/?probe=661ffedd80) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4c355aa7c2](https://linux-hardware.org/?probe=4c355aa7c2) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [61fc6b2cb0](https://linux-hardware.org/?probe=61fc6b2cb0) | Feb 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| HP            | 0A80h                       | Desktop     | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Toshiba       | Satellite C875              | Notebook    | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Insyde        | i101c                       | Notebook    | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| Dell          | 0FJM8V A03                  | Server      | [398f8f6326](https://linux-hardware.org/?probe=398f8f6326) | Feb 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Google        | Peppy                       | Notebook    | [15cd563f21](https://linux-hardware.org/?probe=15cd563f21) | Jan 27, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| ASUSTek       | GL553VW                     | Notebook    | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [1aa2cd2e8f](https://linux-hardware.org/?probe=1aa2cd2e8f) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | Notebook    | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [804b4adedc](https://linux-hardware.org/?probe=804b4adedc) | Jan 15, 2022 |
| Unknown       | K8Upgrade-1689              | Desktop     | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| Dell          | 07N90W A01                  | Desktop     | [c8db7d01bd](https://linux-hardware.org/?probe=c8db7d01bd) | Jan 15, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Nvidia        | Tegra                       | Soc         | [143a4e3c60](https://linux-hardware.org/?probe=143a4e3c60) | Jan 13, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [79e8f681f1](https://linux-hardware.org/?probe=79e8f681f1) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [847afd8ac5](https://linux-hardware.org/?probe=847afd8ac5) | Jan 12, 2022 |
| Acer          | WG43M                       | Desktop     | [af76e9bcfe](https://linux-hardware.org/?probe=af76e9bcfe) | Jan 12, 2022 |
| Acer          | WG43M                       | Desktop     | [5784b66aee](https://linux-hardware.org/?probe=5784b66aee) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4c24369bb7](https://linux-hardware.org/?probe=4c24369bb7) | Jan 11, 2022 |
| System76      | Lemur Pro                   | Notebook    | [fa22d4610e](https://linux-hardware.org/?probe=fa22d4610e) | Jan 11, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | Notebook    | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Alienware     | m15                         | Notebook    | [a0d4f93250](https://linux-hardware.org/?probe=a0d4f93250) | Jan 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [eaf2e708d9](https://linux-hardware.org/?probe=eaf2e708d9) | Jan 03, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Dell          | Latitude 7480               | Notebook    | [a338b67d45](https://linux-hardware.org/?probe=a338b67d45) | Dec 30, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Dell          | Inspiron 15 3515            | Notebook    | [8d130910ab](https://linux-hardware.org/?probe=8d130910ab) | Dec 26, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [f5924cb8b4](https://linux-hardware.org/?probe=f5924cb8b4) | Dec 25, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | Desktop     | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ea7740294a](https://linux-hardware.org/?probe=ea7740294a) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | AOA150                      | Notebook    | [47cae573c1](https://linux-hardware.org/?probe=47cae573c1) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| Dell          | Latitude E6520              | Notebook    | [c7edb79be7](https://linux-hardware.org/?probe=c7edb79be7) | Dec 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b956646608](https://linux-hardware.org/?probe=b956646608) | Dec 12, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [7cf21876b0](https://linux-hardware.org/?probe=7cf21876b0) | Dec 12, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [950da990e7](https://linux-hardware.org/?probe=950da990e7) | Dec 12, 2021 |
| ASUSTek       | 1015BXO                     | Notebook    | [f9eb963d74](https://linux-hardware.org/?probe=f9eb963d74) | Dec 12, 2021 |
| MSI           | Katana GF76 11UC            | Notebook    | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| Positivo      | AT300b                      | Notebook    | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| HP            | Compaq 6510b (GR691EA#AB... | Notebook    | [4d657211eb](https://linux-hardware.org/?probe=4d657211eb) | Dec 04, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ddafe324b7](https://linux-hardware.org/?probe=ddafe324b7) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [e9b454a745](https://linux-hardware.org/?probe=e9b454a745) | Dec 04, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| HP            | 1497                        | Desktop     | [f848ad29cd](https://linux-hardware.org/?probe=f848ad29cd) | Dec 04, 2021 |
| Acer          | AOD255E                     | Notebook    | [390afd35cb](https://linux-hardware.org/?probe=390afd35cb) | Dec 03, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [b096d0494e](https://linux-hardware.org/?probe=b096d0494e) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [edce40927f](https://linux-hardware.org/?probe=edce40927f) | Dec 01, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| ASUSTek       | CM1435                      | Desktop     | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| HP            | Compaq 6720s                | Notebook    | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [0598f63a64](https://linux-hardware.org/?probe=0598f63a64) | Nov 25, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [4528ddf31d](https://linux-hardware.org/?probe=4528ddf31d) | Nov 25, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Dell          | Latitude 3330               | Notebook    | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [2f1bc07165](https://linux-hardware.org/?probe=2f1bc07165) | Nov 17, 2021 |
| Medion        | P6630                       | Notebook    | [edc09031bd](https://linux-hardware.org/?probe=edc09031bd) | Nov 16, 2021 |
| HP            | Pavilion dv6                | Notebook    | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | Notebook    | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| Intel         | S1200BTL E98681-307         | Server      | [13f02631fe](https://linux-hardware.org/?probe=13f02631fe) | Nov 12, 2021 |
| Acer          | Aspire X1700                | Desktop     | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| Acer          | AO751h                      | Notebook    | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [03bba840c5](https://linux-hardware.org/?probe=03bba840c5) | Nov 07, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [25f858c7b1](https://linux-hardware.org/?probe=25f858c7b1) | Nov 05, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| Mediacom      | GTZS                        | Notebook    | [a2a881793d](https://linux-hardware.org/?probe=a2a881793d) | Nov 03, 2021 |
| Foxconn       | 2AA9h                       | Desktop     | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Medion        | MS-7728                     | Desktop     | [564ffdab3d](https://linux-hardware.org/?probe=564ffdab3d) | Nov 02, 2021 |
| HP            | ProBook 4540s               | Notebook    | [fca622f4c4](https://linux-hardware.org/?probe=fca622f4c4) | Nov 01, 2021 |
| Samsung       | R40/R41                     | Notebook    | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [2c6c86b1fb](https://linux-hardware.org/?probe=2c6c86b1fb) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e12d7e47e6](https://linux-hardware.org/?probe=e12d7e47e6) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f86520f5a7](https://linux-hardware.org/?probe=f86520f5a7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | 2000                        | Notebook    | [65ec913842](https://linux-hardware.org/?probe=65ec913842) | Oct 27, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [45ba0657f1](https://linux-hardware.org/?probe=45ba0657f1) | Oct 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| Samsung       | N100SP                      | Notebook    | [7e4ef50289](https://linux-hardware.org/?probe=7e4ef50289) | Oct 26, 2021 |
| MSI           | MS-7309                     | Desktop     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| Acer          | TravelMate P253             | Notebook    | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Samsung       | N100SP                      | Notebook    | [4d8eadf806](https://linux-hardware.org/?probe=4d8eadf806) | Oct 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Acer          | Aspire ES1-131              | Notebook    | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| Intel         | W7650                       | Notebook    | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [15969208ae](https://linux-hardware.org/?probe=15969208ae) | Oct 18, 2021 |
| Unknown       | X99-D8                      | Desktop     | [e335225bdb](https://linux-hardware.org/?probe=e335225bdb) | Oct 17, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | Notebook    | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| NOBLEX        | E11IS2                      | Notebook    | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | 2000                        | Notebook    | [d84546de1b](https://linux-hardware.org/?probe=d84546de1b) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| MSI           | B350 TOMAHAWK PLUS          | Desktop     | [acbc75f1b8](https://linux-hardware.org/?probe=acbc75f1b8) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | Desktop     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2f7c2f51f8](https://linux-hardware.org/?probe=2f7c2f51f8) | Oct 01, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Sony          | VPCSA2FGX                   | Notebook    | [60cfbaebef](https://linux-hardware.org/?probe=60cfbaebef) | Sep 29, 2021 |
| Pegatron      | Acacia                      | Desktop     | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| ZOTAC         | NM10                        | Desktop     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [29a6b45091](https://linux-hardware.org/?probe=29a6b45091) | Sep 26, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [5ed9f083e1](https://linux-hardware.org/?probe=5ed9f083e1) | Sep 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | Desktop     | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [c45de8d3b1](https://linux-hardware.org/?probe=c45de8d3b1) | Sep 21, 2021 |
| Toshiba       | Satellite L20               | Notebook    | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [64604612b2](https://linux-hardware.org/?probe=64604612b2) | Sep 19, 2021 |
| ASUSTek       | P8C WS                      | Desktop     | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| Foxconn       | 2AAF                        | Desktop     | [be2ce05253](https://linux-hardware.org/?probe=be2ce05253) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [b50449f73f](https://linux-hardware.org/?probe=b50449f73f) | Sep 14, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [be96e8a7e1](https://linux-hardware.org/?probe=be96e8a7e1) | Sep 13, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [f1414fdf7b](https://linux-hardware.org/?probe=f1414fdf7b) | Sep 13, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Dell          | 01V648 A03                  | Server      | [f46a021c88](https://linux-hardware.org/?probe=f46a021c88) | Sep 02, 2021 |
| Toshiba       | Satellite A215              | Notebook    | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| Notebook      | NL40_50GU                   | Notebook    | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| Google        | Careena                     | Notebook    | [ab1bafda25](https://linux-hardware.org/?probe=ab1bafda25) | Aug 27, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [50f9ce0180](https://linux-hardware.org/?probe=50f9ce0180) | Aug 26, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [6e1f484406](https://linux-hardware.org/?probe=6e1f484406) | Aug 24, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0fa53c65bb](https://linux-hardware.org/?probe=0fa53c65bb) | Aug 24, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [63b870739f](https://linux-hardware.org/?probe=63b870739f) | Aug 19, 2021 |
| MSI           | 760GM-E51                   | Desktop     | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| Nvidia        | Tegra                       | Soc         | [369b72f0fd](https://linux-hardware.org/?probe=369b72f0fd) | Aug 18, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [bc09a1e988](https://linux-hardware.org/?probe=bc09a1e988) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | Notebook    | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| HP            | Pavilion g4                 | Notebook    | [f1d3ddf197](https://linux-hardware.org/?probe=f1d3ddf197) | Aug 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [239b740235](https://linux-hardware.org/?probe=239b740235) | Aug 03, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| Dell          | Latitude E5450              | Notebook    | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | 8299                        | Desktop     | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [db933e0ebd](https://linux-hardware.org/?probe=db933e0ebd) | Jul 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [51a121d461](https://linux-hardware.org/?probe=51a121d461) | Jul 24, 2021 |
| Intel         | DG965SS AAD41678-307        | Desktop     | [d3f38dbf63](https://linux-hardware.org/?probe=d3f38dbf63) | Jul 24, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Lubuntu 20.04    | 444       | 33.33%  |
| Lubuntu 22.04    | 298       | 22.37%  |
| Lubuntu 18.04    | 213       | 15.99%  |
| Lubuntu 21.10    | 80        | 6.01%   |
| Lubuntu 19.10    | 62        | 4.65%   |
| Lubuntu 21.04    | 52        | 3.9%    |
| Lubuntu 20.10    | 48        | 3.6%    |
| Lubuntu 22.10    | 43        | 3.23%   |
| Lubuntu 16.04    | 30        | 2.25%   |
| Lubuntu 23.04    | 24        | 1.8%    |
| Lubuntu 19.04    | 14        | 1.05%   |
| Lubuntu 18.10    | 13        | 0.98%   |
| Lubuntu          | 3         | 0.23%   |
| Lubuntu 16.10    | 2         | 0.15%   |
| Lubuntu 20.04.1  | 1         | 0.08%   |
| Lubuntu 18.04.05 | 1         | 0.08%   |
| Lubuntu 17.10    | 1         | 0.08%   |
| Lubuntu 17.04    | 1         | 0.08%   |
| Lubuntu 13.04    | 1         | 0.08%   |
| Lubuntu 12.04    | 1         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 1289      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 38        | 2.6%    |
| 5.15.0-43-generic | 36        | 2.46%   |
| 5.4.0-52-generic  | 24        | 1.64%   |
| 5.15.0-56-generic | 21        | 1.44%   |
| 5.13.0-19-generic | 18        | 1.23%   |
| 5.15.0-25-generic | 17        | 1.16%   |
| 5.15.0-60-generic | 16        | 1.1%    |
| 5.13.0-40-generic | 16        | 1.1%    |
| 5.13.0-28-generic | 16        | 1.1%    |
| 5.4.0-48-generic  | 14        | 0.96%   |
| 5.4.0-47-generic  | 14        | 0.96%   |
| 5.3.0-46-generic  | 14        | 0.96%   |
| 5.15.0-46-generic | 14        | 0.96%   |
| 5.15.0-41-generic | 14        | 0.96%   |
| 5.11.0-16-generic | 14        | 0.96%   |
| 5.19.0-32-generic | 13        | 0.89%   |
| 5.11.0-27-generic | 13        | 0.89%   |
| 5.4.0-54-generic  | 12        | 0.82%   |
| 5.4.0-26-generic  | 12        | 0.82%   |
| 5.19.0-41-generic | 12        | 0.82%   |
| 5.19.0-35-generic | 12        | 0.82%   |
| 5.15.0-58-generic | 12        | 0.82%   |
| 5.15.0-47-generic | 12        | 0.82%   |
| 5.13.0-30-generic | 12        | 0.82%   |
| 5.8.0-50-generic  | 11        | 0.75%   |
| 5.4.0-73-generic  | 11        | 0.75%   |
| 5.4.0-40-generic  | 11        | 0.75%   |
| 5.15.0-53-generic | 11        | 0.75%   |
| 5.15.0-52-generic | 11        | 0.75%   |
| 5.15.0-30-generic | 11        | 0.75%   |
| 5.13.0-35-generic | 11        | 0.75%   |
| 5.4.0-29-generic  | 10        | 0.68%   |
| 5.3.0-18-generic  | 10        | 0.68%   |
| 5.19.0-46-generic | 10        | 0.68%   |
| 4.15.0-91-generic | 10        | 0.68%   |
| 5.8.0-63-generic  | 9         | 0.62%   |
| 5.4.0-72-generic  | 9         | 0.62%   |
| 5.4.0-65-generic  | 9         | 0.62%   |
| 5.4.0-33-generic  | 9         | 0.62%   |
| 5.3.0-51-generic  | 9         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 324       | 24%     |
| 5.15.0  | 254       | 18.81%  |
| 4.15.0  | 142       | 10.52%  |
| 5.13.0  | 118       | 8.74%   |
| 5.19.0  | 107       | 7.93%   |
| 5.11.0  | 101       | 7.48%   |
| 5.8.0   | 99        | 7.33%   |
| 5.3.0   | 86        | 6.37%   |
| 6.2.0   | 25        | 1.85%   |
| 5.0.0   | 22        | 1.63%   |
| 4.18.0  | 13        | 0.96%   |
| 4.4.0   | 8         | 0.59%   |
| 6.1.0   | 3         | 0.22%   |
| 5.6.0   | 2         | 0.15%   |
| 5.14.0  | 2         | 0.15%   |
| 4.9.253 | 2         | 0.15%   |
| 4.8.0   | 2         | 0.15%   |
| 4.13.0  | 2         | 0.15%   |
| 4.10.0  | 2         | 0.15%   |
| 6.3.3   | 1         | 0.07%   |
| 6.2.8   | 1         | 0.07%   |
| 6.2.6   | 1         | 0.07%   |
| 6.1.6   | 1         | 0.07%   |
| 6.1.3   | 1         | 0.07%   |
| 6.1.26  | 1         | 0.07%   |
| 6.1.12  | 1         | 0.07%   |
| 6.0.9   | 1         | 0.07%   |
| 6.0.8   | 1         | 0.07%   |
| 6.0.14  | 1         | 0.07%   |
| 6.0.12  | 1         | 0.07%   |
| 6.0.10  | 1         | 0.07%   |
| 6.0.0   | 1         | 0.07%   |
| 5.9.0   | 1         | 0.07%   |
| 5.7.9   | 1         | 0.07%   |
| 5.7.0   | 1         | 0.07%   |
| 5.6.15  | 1         | 0.07%   |
| 5.5.2   | 1         | 0.07%   |
| 5.4.30  | 1         | 0.07%   |
| 5.3.18  | 1         | 0.07%   |
| 5.19.8  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 325       | 24.07%  |
| 5.15    | 255       | 18.89%  |
| 4.15    | 143       | 10.59%  |
| 5.13    | 118       | 8.74%   |
| 5.19    | 109       | 8.07%   |
| 5.11    | 101       | 7.48%   |
| 5.8     | 99        | 7.33%   |
| 5.3     | 87        | 6.44%   |
| 6.2     | 27        | 2%      |
| 5.0     | 22        | 1.63%   |
| 4.18    | 13        | 0.96%   |
| 4.4     | 8         | 0.59%   |
| 6.1     | 7         | 0.52%   |
| 6.0     | 6         | 0.44%   |
| 5.6     | 3         | 0.22%   |
| 4.9     | 3         | 0.22%   |
| 4.13    | 3         | 0.22%   |
| 5.7     | 2         | 0.15%   |
| 5.16    | 2         | 0.15%   |
| 5.14    | 2         | 0.15%   |
| 5.10    | 2         | 0.15%   |
| 4.8     | 2         | 0.15%   |
| 4.10    | 2         | 0.15%   |
| 6.3     | 1         | 0.07%   |
| 5.9     | 1         | 0.07%   |
| 5.5     | 1         | 0.07%   |
| 5.18    | 1         | 0.07%   |
| 5.12    | 1         | 0.07%   |
| 4.20    | 1         | 0.07%   |
| 4.14    | 1         | 0.07%   |
| 3.13    | 1         | 0.07%   |
| 3.1     | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1150      | 89.22%  |
| i686    | 126       | 9.78%   |
| aarch64 | 10        | 0.78%   |
| armv7l  | 2         | 0.16%   |
| ppc64   | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| LXQt            | 995       | 76.77%  |
| LXDE            | 231       | 17.82%  |
| Unknown         | 22        | 1.7%    |
| GNOME           | 17        | 1.31%   |
| Openbox         | 7         | 0.54%   |
| X-Cinnamon      | 5         | 0.39%   |
| KDE5            | 4         | 0.31%   |
| Lubuntu         | 3         | 0.23%   |
| XFCE            | 2         | 0.15%   |
| i3              | 2         | 0.15%   |
| GNOME Flashback | 2         | 0.15%   |
| Cinnamon        | 2         | 0.15%   |
| Budgie          | 2         | 0.15%   |
| MATE            | 1         | 0.08%   |
| KDE             | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1248      | 96.3%   |
| Tty         | 36        | 2.78%   |
| Wayland     | 9         | 0.69%   |
| Unknown     | 2         | 0.15%   |
| Unspecified | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 672       | 51.26%  |
| Unknown | 386       | 29.44%  |
| LightDM | 128       | 9.76%   |
| TDM     | 68        | 5.19%   |
| GDM     | 38        | 2.9%    |
| GDM3    | 13        | 0.99%   |
| XDM     | 3         | 0.23%   |
| LXDM    | 2         | 0.15%   |
| SLiM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 375       | 28.91%  |
| fr_FR   | 116       | 8.94%   |
| pt_BR   | 93        | 7.17%   |
| de_DE   | 80        | 6.17%   |
| it_IT   | 77        | 5.94%   |
| en_GB   | 76        | 5.86%   |
| C       | 59        | 4.55%   |
| ru_RU   | 45        | 3.47%   |
| pl_PL   | 31        | 2.39%   |
| Unknown | 31        | 2.39%   |
| es_ES   | 29        | 2.24%   |
| en_CA   | 26        | 2%      |
| en_AU   | 24        | 1.85%   |
| es_AR   | 18        | 1.39%   |
| cs_CZ   | 15        | 1.16%   |
| es_MX   | 13        | 1%      |
| tr_TR   | 12        | 0.93%   |
| hu_HU   | 12        | 0.93%   |
| en_IN   | 11        | 0.85%   |
| nl_NL   | 10        | 0.77%   |
| en_AG   | 9         | 0.69%   |
| ja_JP   | 8         | 0.62%   |
| es_CR   | 8         | 0.62%   |
| es_CO   | 7         | 0.54%   |
| nl_BE   | 6         | 0.46%   |
| es_CL   | 6         | 0.46%   |
| el_GR   | 6         | 0.46%   |
| fr_BE   | 5         | 0.39%   |
| fi_FI   | 5         | 0.39%   |
| es_PE   | 5         | 0.39%   |
| en_IE   | 5         | 0.39%   |
| fr_CA   | 4         | 0.31%   |
| es_UY   | 4         | 0.31%   |
| en_ZA   | 4         | 0.31%   |
| en_NZ   | 4         | 0.31%   |
| zh_TW   | 3         | 0.23%   |
| pt_PT   | 3         | 0.23%   |
| fr_CH   | 3         | 0.23%   |
| en_SG   | 3         | 0.23%   |
| en_PH   | 3         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 843       | 64.8%   |
| EFI  | 458       | 35.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1173      | 90.44%  |
| Overlay | 61        | 4.7%    |
| Tmpfs   | 23        | 1.77%   |
| Btrfs   | 16        | 1.23%   |
| Xfs     | 6         | 0.46%   |
| Aufs    | 5         | 0.39%   |
| Unknown | 5         | 0.39%   |
| Ext3    | 3         | 0.23%   |
| Ext2    | 2         | 0.15%   |
| Zfs     | 1         | 0.08%   |
| XXX4    | 1         | 0.08%   |
| F2fs    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 519       | 39.86%  |
| GPT     | 444       | 34.1%   |
| MBR     | 339       | 26.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1144      | 87.93%  |
| Yes       | 157       | 12.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 939       | 72.34%  |
| Yes       | 359       | 27.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 217       | 16.83%  |
| ASUSTek Computer        | 161       | 12.49%  |
| Lenovo                  | 132       | 10.24%  |
| Dell                    | 129       | 10.01%  |
| Acer                    | 91        | 7.06%   |
| MSI                     | 54        | 4.19%   |
| Gigabyte Technology     | 49        | 3.8%    |
| Toshiba                 | 47        | 3.65%   |
| ASRock                  | 39        | 3.03%   |
| Samsung Electronics     | 29        | 2.25%   |
| Intel                   | 29        | 2.25%   |
| Apple                   | 27        | 2.09%   |
| Unknown                 | 27        | 2.09%   |
| Sony                    | 20        | 1.55%   |
| Google                  | 20        | 1.55%   |
| Positivo                | 19        | 1.47%   |
| Fujitsu                 | 14        | 1.09%   |
| Pegatron                | 11        | 0.85%   |
| AMI                     | 10        | 0.78%   |
| Fujitsu Siemens         | 9         | 0.7%    |
| Foxconn                 | 9         | 0.7%    |
| Packard Bell            | 8         | 0.62%   |
| Mediacom                | 7         | 0.54%   |
| Raspberry Pi Foundation | 6         | 0.47%   |
| Notebook                | 5         | 0.39%   |
| IBM                     | 5         | 0.39%   |
| Gateway                 | 5         | 0.39%   |
| Biostar                 | 5         | 0.39%   |
| AAEON                   | 5         | 0.39%   |
| Alienware               | 4         | 0.31%   |
| TrekStor                | 3         | 0.23%   |
| OEM                     | 3         | 0.23%   |
| Nvidia                  | 3         | 0.23%   |
| Medion                  | 3         | 0.23%   |
| LG Electronics          | 3         | 0.23%   |
| HUAWEI                  | 3         | 0.23%   |
| GPU Company             | 3         | 0.23%   |
| eMachines               | 3         | 0.23%   |
| ZOTAC                   | 2         | 0.16%   |
| YASHI                   | 2         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 36        | 2.79%   |
| HP Notebook                           | 9         | 0.7%    |
| HP Pavilion 15                        | 6         | 0.47%   |
| Apple MacBookPro8,1                   | 6         | 0.47%   |
| HP Pavilion g6                        | 5         | 0.39%   |
| HP Pavilion dv6                       | 5         | 0.39%   |
| AAEON MF-001                          | 5         | 0.39%   |
| MSI MS-7C37                           | 4         | 0.31%   |
| HP t620 Quad Core TC                  | 4         | 0.31%   |
| Dell Latitude D630                    | 4         | 0.31%   |
| Nvidia Tegra                          | 3         | 0.23%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 3         | 0.23%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS   | 3         | 0.23%   |
| Lenovo IdeaPad 320-15AST 80XV         | 3         | 0.23%   |
| Lenovo IdeaPad 100-15IBD 80QQ         | 3         | 0.23%   |
| Lenovo G50-30 80G0                    | 3         | 0.23%   |
| HP ProBook 440 G7                     | 3         | 0.23%   |
| HP Laptop 15-da0xxx                   | 3         | 0.23%   |
| Dell OptiPlex 790                     | 3         | 0.23%   |
| Dell OptiPlex 7010                    | 3         | 0.23%   |
| Dell Inspiron N5010                   | 3         | 0.23%   |
| ASUS V-P8H67E                         | 3         | 0.23%   |
| ASUS All Series                       | 3         | 0.23%   |
| ASUS 1000H                            | 3         | 0.23%   |
| ASRock FM2A85X Extreme6               | 3         | 0.23%   |
| Apple MacBook4,1                      | 3         | 0.23%   |
| Apple iMac7,1                         | 3         | 0.23%   |
| Acer Aspire 5742G                     | 3         | 0.23%   |
| Acer Aspire 5735                      | 3         | 0.23%   |
| YASHI MYBOOK 360                      | 2         | 0.16%   |
| Toshiba Satellite L40                 | 2         | 0.16%   |
| Toshiba Satellite A205                | 2         | 0.16%   |
| Samsung RV415/RV515                   | 2         | 0.16%   |
| Samsung 275E4E/275E5E                 | 2         | 0.16%   |
| RPi Raspberry Pi                      | 2         | 0.16%   |
| Prestigio PSB141C01BFH                | 2         | 0.16%   |
| Positivo Mobile                       | 2         | 0.16%   |
| Positivo H14BT58                      | 2         | 0.16%   |
| Pegatron NC689AA-ABA s3700y           | 2         | 0.16%   |
| Pegatron Compaq dx2400 Microtower PC  | 2         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 67        | 5.2%    |
| Lenovo IdeaPad        | 43        | 3.34%   |
| Toshiba Satellite     | 42        | 3.26%   |
| HP Pavilion           | 42        | 3.26%   |
| Dell Inspiron         | 42        | 3.26%   |
| Lenovo ThinkPad       | 41        | 3.18%   |
| HP Compaq             | 38        | 2.95%   |
| Unknown               | 36        | 2.79%   |
| HP ProBook            | 29        | 2.25%   |
| Dell Latitude         | 29        | 2.25%   |
| HP EliteBook          | 18        | 1.4%    |
| Dell OptiPlex         | 17        | 1.32%   |
| HP Laptop             | 15        | 1.16%   |
| Lenovo ThinkCentre    | 13        | 1.01%   |
| HP Notebook           | 9         | 0.7%    |
| Dell Vostro           | 9         | 0.7%    |
| Fujitsu Siemens AMILO | 8         | 0.62%   |
| Dell XPS              | 8         | 0.62%   |
| ASUS VivoBook         | 8         | 0.62%   |
| Fujitsu LIFEBOOK      | 7         | 0.54%   |
| RPi Raspberry         | 6         | 0.47%   |
| Packard Bell EasyNote | 6         | 0.47%   |
| HP t620               | 6         | 0.47%   |
| HP Stream             | 6         | 0.47%   |
| Dell Precision        | 6         | 0.47%   |
| ASUS PRIME            | 6         | 0.47%   |
| Apple MacBookPro8     | 6         | 0.47%   |
| HP Spectre            | 5         | 0.39%   |
| HP Presario           | 5         | 0.39%   |
| Dell Studio           | 5         | 0.39%   |
| Acer Extensa          | 5         | 0.39%   |
| AAEON MF-001          | 5         | 0.39%   |
| MSI MS-7C37           | 4         | 0.31%   |
| Dell PowerEdge        | 4         | 0.31%   |
| Dell Dimension        | 4         | 0.31%   |
| ASUS ROG              | 4         | 0.31%   |
| Acer Swift            | 4         | 0.31%   |
| Nvidia Tegra          | 3         | 0.23%   |
| Mediacom SmartBook    | 3         | 0.23%   |
| Lenovo Yoga           | 3         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 119       | 9.23%   |
| 2012    | 105       | 8.15%   |
| 2008    | 104       | 8.07%   |
| 2010    | 101       | 7.84%   |
| 2013    | 92        | 7.14%   |
| 2007    | 88        | 6.83%   |
| 2009    | 75        | 5.82%   |
| 2019    | 72        | 5.59%   |
| 2014    | 65        | 5.04%   |
| 2020    | 62        | 4.81%   |
| 2017    | 62        | 4.81%   |
| 2015    | 62        | 4.81%   |
| 2021    | 57        | 4.42%   |
| 2016    | 57        | 4.42%   |
| 2018    | 51        | 3.96%   |
| 2006    | 45        | 3.49%   |
| 2022    | 25        | 1.94%   |
| 2005    | 18        | 1.4%    |
| Unknown | 13        | 1.01%   |
| 2004    | 6         | 0.47%   |
| 2023    | 3         | 0.23%   |
| 2002    | 3         | 0.23%   |
| 2001    | 2         | 0.16%   |
| 2003    | 1         | 0.08%   |
| 2000    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 794       | 61.6%   |
| Desktop        | 419       | 32.51%  |
| Convertible    | 18        | 1.4%    |
| Mini pc        | 16        | 1.24%   |
| All in one     | 13        | 1.01%   |
| System on chip | 11        | 0.85%   |
| Tablet         | 9         | 0.7%    |
| Server         | 8         | 0.62%   |
| Other          | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1228      | 94.9%   |
| Enabled  | 66        | 5.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1266      | 98.14%  |
| Yes  | 24        | 1.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 386       | 29.51%  |
| 4.01-8.0        | 272       | 20.8%   |
| 1.01-2.0        | 221       | 16.9%   |
| 8.01-16.0       | 147       | 11.24%  |
| 16.01-24.0      | 107       | 8.18%   |
| 2.01-3.0        | 63        | 4.82%   |
| 0.51-1.0        | 42        | 3.21%   |
| 32.01-64.0      | 41        | 3.13%   |
| 24.01-32.0      | 11        | 0.84%   |
| 64.01-256.0     | 8         | 0.61%   |
| 0.01-0.5        | 8         | 0.61%   |
| More than 256.0 | 2         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 604       | 43.74%  |
| 0.51-1.0   | 334       | 24.19%  |
| 2.01-3.0   | 207       | 14.99%  |
| 4.01-8.0   | 87        | 6.3%    |
| 0.01-0.5   | 67        | 4.85%   |
| 3.01-4.0   | 65        | 4.71%   |
| 8.01-16.0  | 12        | 0.87%   |
| 16.01-24.0 | 2         | 0.14%   |
| Unknown    | 2         | 0.14%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 887       | 68.23%  |
| 2      | 296       | 22.77%  |
| 3      | 42        | 3.23%   |
| 4      | 26        | 2%      |
| 0      | 21        | 1.62%   |
| 5      | 15        | 1.15%   |
| 6      | 5         | 0.38%   |
| 7      | 3         | 0.23%   |
| 17     | 1         | 0.08%   |
| 14     | 1         | 0.08%   |
| 12     | 1         | 0.08%   |
| 10     | 1         | 0.08%   |
| 8      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 672       | 51.85%  |
| Yes       | 624       | 48.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1116      | 86.38%  |
| No        | 176       | 13.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 968       | 74.92%  |
| No        | 324       | 25.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 702       | 53.75%  |
| Yes       | 604       | 46.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 198       | 15.31%  |
| France       | 120       | 9.28%   |
| Brazil       | 113       | 8.74%   |
| Germany      | 106       | 8.2%    |
| Italy        | 96        | 7.42%   |
| Russia       | 65        | 5.03%   |
| UK           | 57        | 4.41%   |
| Canada       | 38        | 2.94%   |
| Poland       | 37        | 2.86%   |
| Spain        | 32        | 2.47%   |
| Netherlands  | 26        | 2.01%   |
| Australia    | 22        | 1.7%    |
| Czechia      | 20        | 1.55%   |
| Argentina    | 20        | 1.55%   |
| Indonesia    | 18        | 1.39%   |
| Belgium      | 18        | 1.39%   |
| Turkey       | 17        | 1.31%   |
| Mexico       | 17        | 1.31%   |
| Hungary      | 17        | 1.31%   |
| Switzerland  | 15        | 1.16%   |
| Finland      | 15        | 1.16%   |
| India        | 13        | 1.01%   |
| Ukraine      | 12        | 0.93%   |
| Costa Rica   | 9         | 0.7%    |
| Colombia     | 9         | 0.7%    |
| Ireland      | 8         | 0.62%   |
| Sweden       | 7         | 0.54%   |
| South Africa | 7         | 0.54%   |
| Malaysia     | 7         | 0.54%   |
| Japan        | 7         | 0.54%   |
| Greece       | 7         | 0.54%   |
| Bulgaria     | 7         | 0.54%   |
| Portugal     | 6         | 0.46%   |
| Chile        | 6         | 0.46%   |
| Romania      | 5         | 0.39%   |
| Peru         | 5         | 0.39%   |
| New Zealand  | 5         | 0.39%   |
| Lithuania    | 5         | 0.39%   |
| Austria      | 5         | 0.39%   |
| Vietnam      | 4         | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 17        | 1.25%   |
| Rome              | 15        | 1.1%    |
| Milan             | 14        | 1.03%   |
| Moscow            | 12        | 0.88%   |
| Melbourne         | 12        | 0.88%   |
| Sao Paulo         | 8         | 0.59%   |
| Prague            | 7         | 0.51%   |
| Oshawa            | 7         | 0.51%   |
| Heredia           | 7         | 0.51%   |
| Zurich            | 6         | 0.44%   |
| Warsaw            | 6         | 0.44%   |
| Rio de Janeiro    | 6         | 0.44%   |
| New York          | 6         | 0.44%   |
| Kyiv              | 6         | 0.44%   |
| Istanbul          | 6         | 0.44%   |
| Helsinki          | 6         | 0.44%   |
| Brasília         | 6         | 0.44%   |
| Bengaluru         | 6         | 0.44%   |
| Wellington        | 5         | 0.37%   |
| Porto Alegre      | 5         | 0.37%   |
| Munich            | 5         | 0.37%   |
| Mexico City       | 5         | 0.37%   |
| Madrid            | 5         | 0.37%   |
| Lyon              | 5         | 0.37%   |
| Kuala Lumpur      | 5         | 0.37%   |
| Frankfurt am Main | 5         | 0.37%   |
| Budapest          | 5         | 0.37%   |
| Bogotá           | 5         | 0.37%   |
| Berlin            | 5         | 0.37%   |
| Athens            | 5         | 0.37%   |
| Yekaterinburg     | 4         | 0.29%   |
| Winnipeg          | 4         | 0.29%   |
| Tampere           | 4         | 0.29%   |
| Stuttgart         | 4         | 0.29%   |
| St Petersburg     | 4         | 0.29%   |
| Rio Segundo       | 4         | 0.29%   |
| Houston           | 4         | 0.29%   |
| Hamburg           | 4         | 0.29%   |
| Ghent             | 4         | 0.29%   |
| Dublin            | 4         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 280       | 368    | 17.24%  |
| WDC                       | 264       | 353    | 16.26%  |
| Samsung Electronics       | 157       | 236    | 9.67%   |
| Unknown                   | 133       | 178    | 8.19%   |
| Toshiba                   | 114       | 129    | 7.02%   |
| Hitachi                   | 103       | 130    | 6.34%   |
| Kingston                  | 80        | 91     | 4.93%   |
| SanDisk                   | 51        | 57     | 3.14%   |
| Crucial                   | 51        | 68     | 3.14%   |
| HGST                      | 31        | 37     | 1.91%   |
| Intel                     | 28        | 38     | 1.72%   |
| Fujitsu                   | 24        | 25     | 1.48%   |
| A-DATA Technology         | 20        | 22     | 1.23%   |
| SK hynix                  | 18        | 18     | 1.11%   |
| Maxtor                    | 18        | 20     | 1.11%   |
| China                     | 16        | 18     | 0.99%   |
| Micron Technology         | 15        | 16     | 0.92%   |
| Apacer                    | 12        | 12     | 0.74%   |
| Unknown                   | 12        | 13     | 0.74%   |
| Transcend                 | 8         | 10     | 0.49%   |
| SPCC                      | 8         | 11     | 0.49%   |
| PNY                       | 8         | 8      | 0.49%   |
| Patriot                   | 8         | 8      | 0.49%   |
| OCZ                       | 7         | 8      | 0.43%   |
| KIOXIA                    | 7         | 7      | 0.43%   |
| Apple                     | 6         | 13     | 0.37%   |
| Silicon Motion            | 5         | 6      | 0.31%   |
| LITEONIT                  | 5         | 5      | 0.31%   |
| LDLC                      | 5         | 6      | 0.31%   |
| Intenso                   | 5         | 5      | 0.31%   |
| GOODRAM                   | 5         | 5      | 0.31%   |
| Team                      | 4         | 4      | 0.25%   |
| LITEON                    | 4         | 5      | 0.25%   |
| Lexar                     | 4         | 4      | 0.25%   |
| JMicron Technology        | 4         | 4      | 0.25%   |
| Corsair                   | 4         | 4      | 0.25%   |
| TO Exter                  | 3         | 3      | 0.18%   |
| Plextor                   | 3         | 5      | 0.18%   |
| Micron/Crucial Technology | 3         | 4      | 0.18%   |
| KingSpec                  | 3         | 5      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 29        | 1.65%   |
| Kingston SA400S37240G 240GB SSD     | 23        | 1.31%   |
| Unknown MMC Card  64GB              | 18        | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 16        | 0.91%   |
| Seagate ST9500325AS 500GB           | 13        | 0.74%   |
| Seagate ST500LT012-1DG142 500GB     | 13        | 0.74%   |
| Seagate ST500DM002-1BD142 500GB     | 13        | 0.74%   |
| Unknown                             | 12        | 0.68%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.63%   |
| Toshiba MQ01ABD100 1TB              | 11        | 0.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 11        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB      | 11        | 0.63%   |
| Unknown MMC Card  16GB              | 10        | 0.57%   |
| Samsung SSD 850 EVO 250GB           | 9         | 0.51%   |
| Kingston SA400S37120G 120GB SSD     | 9         | 0.51%   |
| Crucial CT240BX500SSD1 240GB        | 9         | 0.51%   |
| Unknown SD/MMC/MS PRO 128GB         | 8         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 7         | 0.4%    |
| WDC WD3200BPVT-22JJ5T0 320GB        | 7         | 0.4%    |
| Unknown NCard  32GB                 | 7         | 0.4%    |
| Unknown DA4064  64GB                | 7         | 0.4%    |
| Seagate ST1000DM010-2EP102 1TB      | 7         | 0.4%    |
| SanDisk DF4032  32GB                | 7         | 0.4%    |
| Kingston SA400S37480G 480GB SSD     | 7         | 0.4%    |
| Toshiba MQ01ABD050 500GB            | 6         | 0.34%   |
| Seagate ST9250315AS 250GB           | 6         | 0.34%   |
| Seagate ST3500418AS 500GB           | 6         | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB      | 6         | 0.34%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 0.28%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 5         | 0.28%   |
| Toshiba MQ04ABF100 1TB              | 5         | 0.28%   |
| Seagate ST9320325AS 320GB           | 5         | 0.28%   |
| Seagate ST3250310AS 250GB           | 5         | 0.28%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 5         | 0.28%   |
| Seagate Expansion 1TB               | 5         | 0.28%   |
| Samsung SSD 860 EVO 500GB           | 5         | 0.28%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.28%   |
| Samsung HD103SJ 1TB                 | 5         | 0.28%   |
| Kingston SV300S37A120G 120GB SSD    | 5         | 0.28%   |
| HGST HTS545050A7E680 500GB          | 5         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 279       | 366    | 32.37%  |
| WDC                 | 232       | 308    | 26.91%  |
| Hitachi             | 103       | 130    | 11.95%  |
| Toshiba             | 96        | 106    | 11.14%  |
| Samsung Electronics | 54        | 79     | 6.26%   |
| HGST                | 31        | 37     | 3.6%    |
| Fujitsu             | 24        | 25     | 2.78%   |
| Maxtor              | 17        | 19     | 1.97%   |
| Unknown             | 8         | 10     | 0.93%   |
| IBM/Hitachi         | 3         | 4      | 0.35%   |
| Apple               | 3         | 3      | 0.35%   |
| USB                 | 2         | 2      | 0.23%   |
| JMicron Technology  | 2         | 2      | 0.23%   |
| External            | 2         | 2      | 0.23%   |
| WD MediaMax         | 1         | 1      | 0.12%   |
| RSH-319             | 1         | 1      | 0.12%   |
| LaCie               | 1         | 1      | 0.12%   |
| Hewlett-Packard     | 1         | 1      | 0.12%   |
| ASMT                | 1         | 2      | 0.12%   |
| Apricorn            | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 100    | 15.17%  |
| Kingston            | 70        | 80     | 14.96%  |
| Crucial             | 44        | 61     | 9.4%    |
| SanDisk             | 34        | 40     | 7.26%   |
| WDC                 | 24        | 30     | 5.13%   |
| Intel               | 22        | 31     | 4.7%    |
| A-DATA Technology   | 17        | 19     | 3.63%   |
| China               | 14        | 16     | 2.99%   |
| Apacer              | 12        | 12     | 2.56%   |
| Toshiba             | 11        | 13     | 2.35%   |
| Micron Technology   | 9         | 9      | 1.92%   |
| Transcend           | 8         | 10     | 1.71%   |
| PNY                 | 8         | 8      | 1.71%   |
| Patriot             | 8         | 8      | 1.71%   |
| OCZ                 | 7         | 8      | 1.5%    |
| SPCC                | 6         | 7      | 1.28%   |
| LITEONIT            | 5         | 5      | 1.07%   |
| GOODRAM             | 5         | 5      | 1.07%   |
| Team                | 4         | 4      | 0.85%   |
| LITEON              | 4         | 5      | 0.85%   |
| Lexar               | 4         | 4      | 0.85%   |
| Intenso             | 4         | 4      | 0.85%   |
| Corsair             | 4         | 4      | 0.85%   |
| TO Exter            | 3         | 3      | 0.64%   |
| SK hynix            | 3         | 3      | 0.64%   |
| Plextor             | 3         | 5      | 0.64%   |
| LDLC                | 3         | 3      | 0.64%   |
| KingSpec            | 3         | 5      | 0.64%   |
| Unknown             | 2         | 2      | 0.43%   |
| Teclast             | 2         | 2      | 0.43%   |
| NGFF                | 2         | 2      | 0.43%   |
| Mushkin             | 2         | 2      | 0.43%   |
| Londisk             | 2         | 2      | 0.43%   |
| KingDian            | 2         | 2      | 0.43%   |
| Hewlett-Packard     | 2         | 7      | 0.43%   |
| Gigabyte Technology | 2         | 2      | 0.43%   |
| Dogfish             | 2         | 2      | 0.43%   |
| Apple               | 2         | 8      | 0.43%   |
| XrayDisk            | 1         | 1      | 0.21%   |
| WDC WDS2            | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 757       | 1100   | 50.57%  |
| SSD     | 444       | 577    | 29.66%  |
| MMC     | 148       | 193    | 9.89%   |
| NVMe    | 129       | 174    | 8.62%   |
| Unknown | 19        | 25     | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1065      | 1633   | 76.45%  |
| MMC  | 148       | 193    | 10.62%  |
| NVMe | 129       | 174    | 9.26%   |
| SAS  | 51        | 69     | 3.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 880       | 1184   | 72.25%  |
| 0.51-1.0   | 241       | 350    | 19.79%  |
| 1.01-2.0   | 53        | 72     | 4.35%   |
| 3.01-4.0   | 18        | 37     | 1.48%   |
| 4.01-10.0  | 14        | 18     | 1.15%   |
| 2.01-3.0   | 12        | 16     | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 401       | 30.52%  |
| 251-500        | 295       | 22.45%  |
| 51-100         | 143       | 10.88%  |
| 501-1000       | 127       | 9.67%   |
| 21-50          | 105       | 7.99%   |
| 1-20           | 105       | 7.99%   |
| 1001-2000      | 63        | 4.79%   |
| More than 3000 | 42        | 3.2%    |
| 2001-3000      | 27        | 2.05%   |
| Unknown        | 6         | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 676       | 50.04%  |
| 21-50          | 251       | 18.58%  |
| 101-250        | 143       | 10.58%  |
| 51-100         | 111       | 8.22%   |
| 251-500        | 55        | 4.07%   |
| 501-1000       | 49        | 3.63%   |
| 1001-2000      | 30        | 2.22%   |
| More than 3000 | 21        | 1.55%   |
| 2001-3000      | 9         | 0.67%   |
| Unknown        | 6         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 8         | 9      | 4.6%    |
| Seagate ST9500325AS 500GB          | 4         | 4      | 2.3%    |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 2.3%    |
| Seagate ST9320325AS 320GB          | 3         | 3      | 1.72%   |
| Seagate ST1000DM003-9YN162 1TB     | 3         | 3      | 1.72%   |
| Hitachi HTS545032B9A300 320GB      | 3         | 3      | 1.72%   |
| Apacer 16GB SATA Flash Drive SSD   | 3         | 3      | 1.72%   |
| Seagate ST9250315AS 250GB          | 2         | 2      | 1.15%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 2      | 1.15%   |
| Samsung Electronics HD502IJ 500GB  | 2         | 2      | 1.15%   |
| Hitachi HTS542512K9SA00 120GB      | 2         | 2      | 1.15%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 1      | 0.57%   |
| WDC WD800BEVS-60RST0 80GB          | 1         | 1      | 0.57%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1         | 2      | 0.57%   |
| WDC WD5000LUCT-62C26Y0 500GB       | 1         | 1      | 0.57%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 0.57%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 0.57%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 1      | 0.57%   |
| WDC WD5000AAKX-003CA0 500GB        | 1         | 1      | 0.57%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1         | 1      | 0.57%   |
| WDC WD400EB-00CPF0 40GB            | 1         | 1      | 0.57%   |
| WDC WD400BB-75CAA0 40GB            | 1         | 1      | 0.57%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.57%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 0.57%   |
| WDC WD3200BEVT-75A23T0 320GB       | 1         | 1      | 0.57%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.57%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1         | 1      | 0.57%   |
| WDC WD3200AACS-00M6B0 320GB        | 1         | 1      | 0.57%   |
| WDC WD2500HHTZ-04N21V0 250GB       | 1         | 1      | 0.57%   |
| WDC WD2500BEVT-80A23T0 250GB       | 1         | 2      | 0.57%   |
| WDC WD2500AAJS-75M0A0 249GB        | 1         | 1      | 0.57%   |
| WDC WD2003FYYS-02W0B0 2TB          | 1         | 1      | 0.57%   |
| WDC WD1600AAJS-60B4A0 160GB        | 1         | 2      | 0.57%   |
| WDC WD1200BEVS-60UST0 120GB        | 1         | 1      | 0.57%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 1      | 0.57%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 0.57%   |
| WDC WD10SPZX-08Z10 1TB             | 1         | 1      | 0.57%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 0.57%   |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 59     | 29.59%  |
| WDC                 | 33        | 39     | 19.53%  |
| Hitachi             | 19        | 21     | 11.24%  |
| Toshiba             | 9         | 9      | 5.33%   |
| Samsung Electronics | 7         | 15     | 4.14%   |
| HGST                | 6         | 6      | 3.55%   |
| Kingston            | 5         | 5      | 2.96%   |
| Intel               | 5         | 6      | 2.96%   |
| Crucial             | 5         | 5      | 2.96%   |
| Maxtor              | 4         | 4      | 2.37%   |
| Fujitsu             | 4         | 4      | 2.37%   |
| Apacer              | 3         | 3      | 1.78%   |
| SK hynix            | 2         | 2      | 1.18%   |
| OCZ                 | 2         | 3      | 1.18%   |
| LITEON              | 2         | 2      | 1.18%   |
| KingSpec            | 2         | 4      | 1.18%   |
| A-DATA Technology   | 2         | 2      | 1.18%   |
| Transcend           | 1         | 1      | 0.59%   |
| TCSUNBOW            | 1         | 1      | 0.59%   |
| SanDisk             | 1         | 1      | 0.59%   |
| Plextor             | 1         | 1      | 0.59%   |
| NGFF                | 1         | 1      | 0.59%   |
| Mushkin             | 1         | 1      | 0.59%   |
| Micron Technology   | 1         | 1      | 0.59%   |
| LDLC                | 1         | 1      | 0.59%   |
| Apple               | 1         | 1      | 0.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 59     | 38.46%  |
| WDC                 | 31        | 37     | 23.85%  |
| Hitachi             | 19        | 21     | 14.62%  |
| Toshiba             | 9         | 9      | 6.92%   |
| Samsung Electronics | 6         | 14     | 4.62%   |
| HGST                | 6         | 6      | 4.62%   |
| Maxtor              | 4         | 4      | 3.08%   |
| Fujitsu             | 4         | 4      | 3.08%   |
| Apple               | 1         | 1      | 0.77%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 126       | 155    | 76.36%  |
| SSD  | 38        | 42     | 23.03%  |
| NVMe | 1         | 1      | 0.61%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1      | 9.09%   |
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 9.09%   |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 9.09%   |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 9.09%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 850 250GB | 1         | 1      | 9.09%   |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 9.09%   |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 9.09%   |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 9.09%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 36.36%  |
| Samsung Electronics | 4         | 4      | 36.36%  |
| Seagate             | 1         | 1      | 9.09%   |
| Intel               | 1         | 1      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 710       | 1123   | 51.82%  |
| Works    | 487       | 736    | 35.55%  |
| Malfunc  | 162       | 198    | 11.82%  |
| Failed   | 11        | 12     | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 835       | 62.22%  |
| AMD                              | 228       | 16.99%  |
| Nvidia                           | 61        | 4.55%   |
| Samsung Electronics              | 38        | 2.83%   |
| JMicron Technology               | 19        | 1.42%   |
| SanDisk                          | 18        | 1.34%   |
| ASMedia Technology               | 15        | 1.12%   |
| VIA Technologies                 | 13        | 0.97%   |
| Marvell Technology Group         | 13        | 0.97%   |
| Kingston Technology Company      | 11        | 0.82%   |
| SK hynix                         | 10        | 0.75%   |
| Micron/Crucial Technology        | 10        | 0.75%   |
| Silicon Motion                   | 9         | 0.67%   |
| Silicon Integrated Systems [SiS] | 9         | 0.67%   |
| Toshiba America Info Systems     | 7         | 0.52%   |
| Micron Technology                | 7         | 0.52%   |
| KIOXIA                           | 7         | 0.52%   |
| Silicon Image                    | 5         | 0.37%   |
| LSI Logic / Symbios Logic        | 5         | 0.37%   |
| Phison Electronics               | 4         | 0.3%    |
| ADATA Technology                 | 3         | 0.22%   |
| Union Memory (Shenzhen)          | 2         | 0.15%   |
| ULi Electronics                  | 2         | 0.15%   |
| Solid State Storage Technology   | 2         | 0.15%   |
| Broadcom / LSI                   | 2         | 0.15%   |
| Zhaoxin                          | 1         | 0.07%   |
| Yangtze Memory Technologies      | 1         | 0.07%   |
| Shenzhen Longsys Electronics     | 1         | 0.07%   |
| Seagate Technology               | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Broadcom                         | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 131       | 7.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 71        | 4.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 60        | 3.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 49        | 2.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 48        | 2.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 46        | 2.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 45        | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 45        | 2.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 41        | 2.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 41        | 2.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 35        | 2.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 34        | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 34        | 2.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 31        | 1.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 27        | 1.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 26        | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 25        | 1.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 21        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21        | 1.26%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 20        | 1.2%    |
| Nvidia MCP61 SATA Controller                                                            | 19        | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18        | 1.08%   |
| Nvidia MCP61 IDE                                                                        | 16        | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 16        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16        | 0.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 15        | 0.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 14        | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 14        | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 14        | 0.84%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 13        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 13        | 0.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 13        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 0.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12        | 0.72%   |
| Samsung NVMe SSD Controller 980                                                         | 11        | 0.66%   |
| Intel SATA Controller [RAID mode]                                                       | 11        | 0.66%   |
| AMD SB600 IDE                                                                           | 11        | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 10        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 858       | 60.13%  |
| IDE  | 373       | 26.14%  |
| NVMe | 127       | 8.9%    |
| RAID | 64        | 4.48%   |
| SCSI | 3         | 0.21%   |
| SAS  | 2         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 987       | 76.57%  |
| AMD          | 288       | 22.34%  |
| ARM          | 11        | 0.85%   |
| PowerMac7,2  | 1         | 0.08%   |
| CentaurHauls | 1         | 0.08%   |
| Unknown      | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 26        | 2.02%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 14        | 1.09%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 13        | 1.01%   |
| Intel Atom CPU N270 @ 1.60GHz               | 13        | 1.01%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 10        | 0.78%   |
| ARM Processor                               | 10        | 0.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 9         | 0.7%    |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 9         | 0.7%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 9         | 0.7%    |
| Intel Celeron CPU N2840 @ 2.16GHz           | 9         | 0.7%    |
| Intel Atom CPU N455 @ 1.66GHz               | 9         | 0.7%    |
| AMD E-450 APU with Radeon HD Graphics       | 9         | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 8         | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 8         | 0.62%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 8         | 0.62%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 8         | 0.62%   |
| Intel Atom CPU N450 @ 1.66GHz               | 8         | 0.62%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 7         | 0.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.54%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 7         | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 7         | 0.54%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 6         | 0.47%   |
| Intel Pentium 4 CPU 2.80GHz                 | 6         | 0.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 0.47%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 6         | 0.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6         | 0.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 6         | 0.47%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 6         | 0.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 6         | 0.47%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 6         | 0.47%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 6         | 0.47%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 6         | 0.47%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 6         | 0.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 0.47%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 6         | 0.47%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 5         | 0.39%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 5         | 0.39%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 5         | 0.39%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 5         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 192       | 14.9%   |
| Intel Celeron           | 135       | 10.47%  |
| Intel Atom              | 119       | 9.23%   |
| Intel Core i7           | 109       | 8.46%   |
| Intel Core 2 Duo        | 98        | 7.6%    |
| Intel Core i3           | 92        | 7.14%   |
| Intel Pentium           | 38        | 2.95%   |
| Other                   | 35        | 2.72%   |
| Intel Pentium Dual      | 34        | 2.64%   |
| Intel Pentium Dual-Core | 31        | 2.4%    |
| AMD Ryzen 7             | 25        | 1.94%   |
| AMD Ryzen 5             | 25        | 1.94%   |
| AMD Athlon 64 X2        | 23        | 1.78%   |
| Intel Core 2            | 21        | 1.63%   |
| Intel Xeon              | 20        | 1.55%   |
| AMD E                   | 20        | 1.55%   |
| Intel Pentium 4         | 17        | 1.32%   |
| AMD A6                  | 16        | 1.24%   |
| Intel Core 2 Quad       | 14        | 1.09%   |
| AMD E1                  | 14        | 1.09%   |
| AMD A4                  | 14        | 1.09%   |
| AMD A10                 | 12        | 0.93%   |
| Intel Genuine           | 11        | 0.85%   |
| AMD FX                  | 11        | 0.85%   |
| AMD Athlon II X2        | 11        | 0.85%   |
| AMD A8                  | 10        | 0.78%   |
| AMD E2                  | 8         | 0.62%   |
| AMD Athlon 64           | 8         | 0.62%   |
| AMD Ryzen 3             | 7         | 0.54%   |
| Intel Celeron M         | 6         | 0.47%   |
| Intel Celeron Dual-Core | 6         | 0.47%   |
| AMD GX                  | 6         | 0.47%   |
| AMD Athlon              | 6         | 0.47%   |
| Intel Pentium Silver    | 5         | 0.39%   |
| Intel Pentium M         | 5         | 0.39%   |
| Intel Pentium D         | 5         | 0.39%   |
| AMD Phenom II X4        | 5         | 0.39%   |
| AMD C-50                | 5         | 0.39%   |
| AMD Turion 64 X2 Mobile | 4         | 0.31%   |
| AMD Ryzen 9             | 4         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 748       | 58.03%  |
| 4       | 334       | 25.91%  |
| 1       | 113       | 8.77%   |
| 8       | 36        | 2.79%   |
| 6       | 34        | 2.64%   |
| 3       | 8         | 0.62%   |
| 12      | 4         | 0.31%   |
| 10      | 4         | 0.31%   |
| Unknown | 3         | 0.23%   |
| 16      | 2         | 0.16%   |
| 64      | 1         | 0.08%   |
| 40      | 1         | 0.08%   |
| 20      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1277      | 99.07%  |
| 2       | 8         | 0.62%   |
| Unknown | 3         | 0.23%   |
| 4       | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 737       | 57.18%  |
| 2       | 548       | 42.51%  |
| Unknown | 3         | 0.23%   |
| 8       | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1223      | 94.88%  |
| 32-bit         | 56        | 4.34%   |
| Unknown        | 9         | 0.7%    |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 316       | 24.03%  |
| 0x206a7    | 79        | 6.01%   |
| 0x1067a    | 63        | 4.79%   |
| 0x306a9    | 60        | 4.56%   |
| 0x6fd      | 52        | 3.95%   |
| 0x406c4    | 33        | 2.51%   |
| 0x20655    | 31        | 2.36%   |
| 0x30678    | 29        | 2.21%   |
| 0x40651    | 28        | 2.13%   |
| 0x306c3    | 28        | 2.13%   |
| 0x106ca    | 27        | 2.05%   |
| 0x05000119 | 26        | 1.98%   |
| 0x406c3    | 22        | 1.67%   |
| 0x406e3    | 19        | 1.44%   |
| 0x6fb      | 18        | 1.37%   |
| 0x806ec    | 17        | 1.29%   |
| 0x106c2    | 17        | 1.29%   |
| 0x10676    | 16        | 1.22%   |
| 0x706a8    | 15        | 1.14%   |
| 0x706a1    | 15        | 1.14%   |
| 0x6f6      | 13        | 0.99%   |
| 0x20652    | 13        | 0.99%   |
| 0x0700010f | 13        | 0.99%   |
| 0x06006705 | 13        | 0.99%   |
| 0x806ea    | 12        | 0.91%   |
| 0x806e9    | 12        | 0.91%   |
| 0x06001119 | 12        | 0.91%   |
| 0x010000c8 | 11        | 0.84%   |
| 0x906ea    | 10        | 0.76%   |
| 0x506c9    | 10        | 0.76%   |
| 0x306d4    | 10        | 0.76%   |
| 0x05000029 | 10        | 0.76%   |
| 0x806c1    | 9         | 0.68%   |
| 0x6e8      | 9         | 0.68%   |
| 0x6d8      | 9         | 0.68%   |
| 0x706e5    | 8         | 0.61%   |
| 0x10661    | 8         | 0.61%   |
| 0x06000852 | 8         | 0.61%   |
| 0x30661    | 7         | 0.53%   |
| 0x0a50000c | 7         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Core             | 117       | 9.08%   |
| Silvermont       | 116       | 9%      |
| SandyBridge      | 102       | 7.91%   |
| Penryn           | 101       | 7.84%   |
| IvyBridge        | 80        | 6.21%   |
| Haswell          | 77        | 5.97%   |
| KabyLake         | 76        | 5.9%    |
| Westmere         | 59        | 4.58%   |
| Bonnell          | 58        | 4.5%    |
| K8 Hammer        | 45        | 3.49%   |
| Bobcat           | 40        | 3.1%    |
| Goldmont plus    | 36        | 2.79%   |
| Skylake          | 34        | 2.64%   |
| K10              | 33        | 2.56%   |
| Excavator        | 30        | 2.33%   |
| NetBurst         | 27        | 2.09%   |
| Piledriver       | 25        | 1.94%   |
| P6               | 24        | 1.86%   |
| Zen 2            | 22        | 1.71%   |
| Unknown          | 20        | 1.55%   |
| Zen 3            | 18        | 1.4%    |
| Jaguar           | 18        | 1.4%    |
| Zen+             | 16        | 1.24%   |
| Goldmont         | 16        | 1.24%   |
| Broadwell        | 15        | 1.16%   |
| IceLake          | 12        | 0.93%   |
| TigerLake        | 11        | 0.85%   |
| Zen              | 10        | 0.78%   |
| Puma             | 9         | 0.7%    |
| CometLake        | 9         | 0.7%    |
| Tremont          | 7         | 0.54%   |
| Nehalem          | 7         | 0.54%   |
| K8 & K10 hybrid  | 6         | 0.47%   |
| Steamroller      | 5         | 0.39%   |
| K10 Llano        | 4         | 0.31%   |
| Alderlake Hybrid | 2         | 0.16%   |
| K6               | 1         | 0.08%   |
| Bulldozer        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 770       | 54.88%  |
| AMD                              | 338       | 24.09%  |
| Nvidia                           | 272       | 19.39%  |
| Matrox Electronics Systems       | 8         | 0.57%   |
| Silicon Integrated Systems [SiS] | 7         | 0.5%    |
| VIA Technologies                 | 6         | 0.43%   |
| Zhaoxin                          | 1         | 0.07%   |
| S3 Graphics                      | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 81        | 5.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 4.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 54        | 3.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 48        | 3.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 48        | 3.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 48        | 3.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 38        | 2.51%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 35        | 2.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 2.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 32        | 2.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 28        | 1.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 27        | 1.79%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 24        | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 17        | 1.13%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 15        | 0.99%   |
| Intel HD Graphics 500                                                                    | 15        | 0.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 0.93%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 13        | 0.86%   |
| Intel HD Graphics 620                                                                    | 13        | 0.86%   |
| Nvidia GT218 [GeForce 210]                                                               | 12        | 0.79%   |
| Intel UHD Graphics 620                                                                   | 12        | 0.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 12        | 0.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 0.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 0.73%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 11        | 0.73%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.73%   |
| AMD Renoir                                                                               | 11        | 0.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 0.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 0.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 0.66%   |
| Intel HD Graphics 5500                                                                   | 10        | 0.66%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 10        | 0.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.66%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10        | 0.66%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 9         | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.53%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8         | 0.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 0.53%   |
| Intel Iris Plus Graphics G7                                                              | 8         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 653       | 50.5%   |
| 1 x AMD            | 268       | 20.73%  |
| 1 x Nvidia         | 189       | 14.62%  |
| Intel + Nvidia     | 68        | 5.26%   |
| Intel + AMD        | 34        | 2.63%   |
| 2 x AMD            | 26        | 2.01%   |
| Other              | 16        | 1.24%   |
| AMD + Nvidia       | 9         | 0.7%    |
| 1 x SiS            | 7         | 0.54%   |
| 1 x Matrox         | 7         | 0.54%   |
| 1 x VIA            | 6         | 0.46%   |
| 2 x Intel          | 3         | 0.23%   |
| 2 x Nvidia         | 2         | 0.15%   |
| 1 x Zhaoxin        | 1         | 0.08%   |
| 1 x S3 Graphics    | 1         | 0.08%   |
| Nvidia + Matrox    | 1         | 0.08%   |
| Intel + 2 x Nvidia | 1         | 0.08%   |
| Intel + 2 x AMD    | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1131      | 87.34%  |
| Proprietary | 105       | 8.11%   |
| Unknown     | 59        | 4.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 761       | 58.45%  |
| 0.01-0.5   | 289       | 22.2%   |
| 1.01-2.0   | 104       | 7.99%   |
| 0.51-1.0   | 84        | 6.45%   |
| 3.01-4.0   | 33        | 2.53%   |
| 7.01-8.0   | 12        | 0.92%   |
| 2.01-3.0   | 7         | 0.54%   |
| 5.01-6.0   | 6         | 0.46%   |
| 8.01-16.0  | 6         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 182       | 14.58%  |
| AU Optronics            | 157       | 12.58%  |
| LG Display              | 117       | 9.38%   |
| BOE                     | 94        | 7.53%   |
| Chimei Innolux          | 93        | 7.45%   |
| Dell                    | 59        | 4.73%   |
| Goldstar                | 43        | 3.45%   |
| Acer                    | 41        | 3.29%   |
| Hewlett-Packard         | 38        | 3.04%   |
| Chi Mei Optoelectronics | 37        | 2.96%   |
| Apple                   | 27        | 2.16%   |
| Philips                 | 26        | 2.08%   |
| LG Philips              | 25        | 2%      |
| Lenovo                  | 25        | 2%      |
| HannStar                | 23        | 1.84%   |
| AOC                     | 22        | 1.76%   |
| BenQ                    | 19        | 1.52%   |
| Iiyama                  | 14        | 1.12%   |
| CPT                     | 14        | 1.12%   |
| InfoVision              | 13        | 1.04%   |
| Ancor Communications    | 13        | 1.04%   |
| Sharp                   | 11        | 0.88%   |
| Unknown                 | 9         | 0.72%   |
| Vizio                   | 8         | 0.64%   |
| Sony                    | 8         | 0.64%   |
| NEC Computers           | 8         | 0.64%   |
| Toshiba                 | 6         | 0.48%   |
| PANDA                   | 6         | 0.48%   |
| LG Electronics          | 5         | 0.4%    |
| Eizo                    | 5         | 0.4%    |
| ViewSonic               | 4         | 0.32%   |
| Sceptre Tech            | 4         | 0.32%   |
| Positivo                | 3         | 0.24%   |
| MSI                     | 3         | 0.24%   |
| InnoLux Display         | 3         | 0.24%   |
| Fujitsu Siemens         | 3         | 0.24%   |
| Belinea                 | 3         | 0.24%   |
| ASUSTek Computer        | 3         | 0.24%   |
| ___                     | 2         | 0.16%   |
| Videoseven              | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.79%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 8         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 8         | 0.63%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.63%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 7         | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.55%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.48%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch                  | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 5         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 4         | 0.32%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                     | 4         | 0.32%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 4         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 3         | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 3         | 0.24%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 3         | 0.24%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch              | 3         | 0.24%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 0.24%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.24%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch              | 3         | 0.24%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.24%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch              | 3         | 0.24%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch                | 3         | 0.24%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 3         | 0.24%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 3         | 0.24%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 3         | 0.24%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                        | 3         | 0.24%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 3         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 392       | 31.79%  |
| 1920x1080 (FHD)    | 329       | 26.68%  |
| 1280x800 (WXGA)    | 103       | 8.35%   |
| 1280x1024 (SXGA)   | 70        | 5.68%   |
| 1600x900 (HD+)     | 60        | 4.87%   |
| 1680x1050 (WSXGA+) | 47        | 3.81%   |
| 1440x900 (WXGA+)   | 36        | 2.92%   |
| 1024x600           | 32        | 2.6%    |
| 3840x2160 (4K)     | 27        | 2.19%   |
| 2560x1440 (QHD)    | 26        | 2.11%   |
| 1920x1200 (WUXGA)  | 24        | 1.95%   |
| 1024x768 (XGA)     | 15        | 1.22%   |
| 1360x768           | 11        | 0.89%   |
| Unknown            | 9         | 0.73%   |
| 2288x1287          | 5         | 0.41%   |
| 3840x2400          | 4         | 0.32%   |
| 2560x1600          | 4         | 0.32%   |
| 1280x720 (HD)      | 4         | 0.32%   |
| 3200x1800 (QHD+)   | 3         | 0.24%   |
| 2560x1080          | 3         | 0.24%   |
| 1920x540           | 3         | 0.24%   |
| 1280x768           | 3         | 0.24%   |
| 3600x1200          | 2         | 0.16%   |
| 3440x1440          | 2         | 0.16%   |
| 3200x1080          | 2         | 0.16%   |
| 2880x1800          | 2         | 0.16%   |
| 2160x1440          | 2         | 0.16%   |
| 2048x1536          | 2         | 0.16%   |
| 1600x1200          | 2         | 0.16%   |
| 800x600            | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2160x1200          | 1         | 0.08%   |
| 2048x1152          | 1         | 0.08%   |
| 1528x1222          | 1         | 0.08%   |
| 1360x765           | 1         | 0.08%   |
| 1152x864           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 350       | 28.16%  |
| 14      | 118       | 9.49%   |
| 13      | 114       | 9.17%   |
| 17      | 84        | 6.76%   |
| 11      | 57        | 4.59%   |
| 24      | 55        | 4.42%   |
| 23      | 51        | 4.1%    |
| 19      | 50        | 4.02%   |
| Unknown | 49        | 3.94%   |
| 21      | 44        | 3.54%   |
| 27      | 42        | 3.38%   |
| 10      | 35        | 2.82%   |
| 18      | 34        | 2.74%   |
| 22      | 29        | 2.33%   |
| 20      | 28        | 2.25%   |
| 12      | 28        | 2.25%   |
| 72      | 9         | 0.72%   |
| 84      | 6         | 0.48%   |
| 31      | 6         | 0.48%   |
| 47      | 4         | 0.32%   |
| 40      | 4         | 0.32%   |
| 34      | 4         | 0.32%   |
| 8       | 4         | 0.32%   |
| 26      | 3         | 0.24%   |
| 9       | 3         | 0.24%   |
| 142     | 2         | 0.16%   |
| 52      | 2         | 0.16%   |
| 48      | 2         | 0.16%   |
| 39      | 2         | 0.16%   |
| 38      | 2         | 0.16%   |
| 29      | 2         | 0.16%   |
| 25      | 2         | 0.16%   |
| 16      | 2         | 0.16%   |
| 7       | 2         | 0.16%   |
| 65      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 60      | 1         | 0.08%   |
| 54      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 44      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 548       | 44.41%  |
| 201-300        | 176       | 14.26%  |
| 501-600        | 149       | 12.07%  |
| 401-500        | 148       | 11.99%  |
| 351-400        | 95        | 7.7%    |
| Unknown        | 49        | 3.97%   |
| 1501-2000      | 15        | 1.22%   |
| 1001-1500      | 13        | 1.05%   |
| 601-700        | 12        | 0.97%   |
| 801-900        | 9         | 0.73%   |
| 101-200        | 8         | 0.65%   |
| 701-800        | 6         | 0.49%   |
| 901-1000       | 4         | 0.32%   |
| More than 2000 | 2         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 822       | 69.72%  |
| 16/10   | 209       | 17.73%  |
| 5/4     | 65        | 5.51%   |
| Unknown | 38        | 3.22%   |
| 4/3     | 27        | 2.29%   |
| 3/2     | 9         | 0.76%   |
| 21/9    | 5         | 0.42%   |
| 6/5     | 2         | 0.17%   |
| 1.00    | 2         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 346       | 27.97%  |
| 81-90          | 194       | 15.68%  |
| 201-250        | 149       | 12.05%  |
| 151-200        | 96        | 7.76%   |
| 141-150        | 58        | 4.69%   |
| 51-60          | 57        | 4.61%   |
| Unknown        | 49        | 3.96%   |
| 301-350        | 44        | 3.56%   |
| 71-80          | 39        | 3.15%   |
| 41-50          | 38        | 3.07%   |
| 121-130        | 38        | 3.07%   |
| More than 1000 | 26        | 2.1%    |
| 61-70          | 25        | 2.02%   |
| 251-300        | 22        | 1.78%   |
| 501-1000       | 18        | 1.46%   |
| 351-500        | 12        | 0.97%   |
| 131-140        | 12        | 0.97%   |
| 1-40           | 7         | 0.57%   |
| 111-120        | 5         | 0.4%    |
| 91-100         | 2         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 427       | 34.97%  |
| 51-100        | 424       | 34.73%  |
| 121-160       | 238       | 19.49%  |
| Unknown       | 49        | 4.01%   |
| 161-240       | 40        | 3.28%   |
| 1-50          | 31        | 2.54%   |
| More than 240 | 12        | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1143      | 87.52%  |
| 2     | 111       | 8.5%    |
| 0     | 43        | 3.29%   |
| 3     | 8         | 0.61%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 681       | 34.5%   |
| Intel                             | 435       | 22.04%  |
| Qualcomm Atheros                  | 284       | 14.39%  |
| Broadcom                          | 145       | 7.35%   |
| Nvidia                            | 52        | 2.63%   |
| Marvell Technology Group          | 52        | 2.63%   |
| Ralink Technology                 | 48        | 2.43%   |
| Broadcom Limited                  | 40        | 2.03%   |
| Ralink                            | 35        | 1.77%   |
| TP-Link                           | 22        | 1.11%   |
| Samsung Electronics               | 17        | 0.86%   |
| ASIX Electronics                  | 13        | 0.66%   |
| VIA Technologies                  | 11        | 0.56%   |
| Attansic Technology               | 11        | 0.56%   |
| Xiaomi                            | 9         | 0.46%   |
| Qualcomm Atheros Communications   | 8         | 0.41%   |
| MediaTek                          | 8         | 0.41%   |
| NetGear                           | 7         | 0.35%   |
| JMicron Technology                | 7         | 0.35%   |
| Huawei Technologies               | 7         | 0.35%   |
| Belkin Components                 | 6         | 0.3%    |
| Silicon Integrated Systems [SiS]  | 5         | 0.25%   |
| ICS Advent                        | 4         | 0.2%    |
| D-Link System                     | 4         | 0.2%    |
| AMD                               | 4         | 0.2%    |
| Hewlett-Packard                   | 3         | 0.15%   |
| Dell                              | 3         | 0.15%   |
| D-Link                            | 3         | 0.15%   |
| ASUSTek Computer                  | 3         | 0.15%   |
| 3Com                              | 3         | 0.15%   |
| ULi Electronics                   | 2         | 0.1%    |
| Qualcomm                          | 2         | 0.1%    |
| Motorola PCS                      | 2         | 0.1%    |
| Intersil                          | 2         | 0.1%    |
| Fibocom                           | 2         | 0.1%    |
| Ericsson Business Mobile Networks | 2         | 0.1%    |
| ZyXEL Communications              | 1         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |
| Yulong                            | 1         | 0.05%   |
| U-Blox                            | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 390       | 17.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 136       | 6%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 54        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 42        | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 39        | 1.72%   |
| Intel Wireless 7260                                                     | 35        | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 32        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 31        | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 29        | 1.28%   |
| Intel Wireless 7265                                                     | 24        | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 21        | 0.93%   |
| Ralink MT7601U Wireless Adapter                                         | 20        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 17        | 0.75%   |
| Nvidia MCP61 Ethernet                                                   | 17        | 0.75%   |
| Intel Wireless 3165                                                     | 17        | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 16        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 15        | 0.66%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                                | 15        | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 0.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 13        | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 13        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 13        | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 12        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 11        | 0.49%   |
| Realtek 802.11ac NIC                                                    | 11        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 11        | 0.49%   |
| Intel Wireless 8265 / 8275                                              | 11        | 0.49%   |
| Intel Wireless 3160                                                     | 11        | 0.49%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 11        | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 10        | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 10        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 325       | 31.8%   |
| Qualcomm Atheros                  | 232       | 22.7%   |
| Realtek Semiconductor             | 196       | 19.18%  |
| Broadcom                          | 91        | 8.9%    |
| Ralink Technology                 | 48        | 4.7%    |
| Ralink                            | 35        | 3.42%   |
| Broadcom Limited                  | 22        | 2.15%   |
| TP-Link                           | 21        | 2.05%   |
| Qualcomm Atheros Communications   | 8         | 0.78%   |
| MediaTek                          | 7         | 0.68%   |
| NetGear                           | 6         | 0.59%   |
| Belkin Components                 | 6         | 0.59%   |
| Marvell Technology Group          | 3         | 0.29%   |
| ASUSTek Computer                  | 3         | 0.29%   |
| Fibocom                           | 2         | 0.2%    |
| Dell                              | 2         | 0.2%    |
| D-Link System                     | 2         | 0.2%    |
| D-Link                            | 2         | 0.2%    |
| ZyXEL Communications              | 1         | 0.1%    |
| Sitecom Europe                    | 1         | 0.1%    |
| Sierra Wireless                   | 1         | 0.1%    |
| Samsung Electronics               | 1         | 0.1%    |
| Microsoft                         | 1         | 0.1%    |
| Micro Star International          | 1         | 0.1%    |
| Logitec                           | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| IMC Networks                      | 1         | 0.1%    |
| Ericsson Business Mobile Networks | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 54        | 5.25%   |
| Intel Wireless 7260                                                     | 35        | 3.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 3.21%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 32        | 3.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 31        | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 2.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 29        | 2.82%   |
| Intel Wireless 7265                                                     | 24        | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.14%   |
| Ralink MT7601U Wireless Adapter                                         | 20        | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 17        | 1.65%   |
| Intel Wireless 3165                                                     | 17        | 1.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 16        | 1.55%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 15        | 1.46%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 1.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 1.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 1.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 13        | 1.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 13        | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.17%   |
| Realtek 802.11ac NIC                                                    | 11        | 1.07%   |
| Intel Wireless 8265 / 8275                                              | 11        | 1.07%   |
| Intel Wireless 3160                                                     | 11        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.97%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 9         | 0.87%   |
| Realtek 802.11n WLAN Adapter                                            | 9         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                          | 9         | 0.87%   |
| Intel Wireless 8260                                                     | 9         | 0.87%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 9         | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 9         | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 8         | 0.78%   |
| Intel WiFi Link 5100                                                    | 8         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 8         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 601       | 50.42%  |
| Intel                            | 201       | 16.86%  |
| Qualcomm Atheros                 | 90        | 7.55%   |
| Broadcom                         | 72        | 6.04%   |
| Nvidia                           | 52        | 4.36%   |
| Marvell Technology Group         | 49        | 4.11%   |
| Broadcom Limited                 | 18        | 1.51%   |
| ASIX Electronics                 | 13        | 1.09%   |
| Samsung Electronics              | 12        | 1.01%   |
| VIA Technologies                 | 11        | 0.92%   |
| Attansic Technology              | 11        | 0.92%   |
| Xiaomi                           | 9         | 0.76%   |
| JMicron Technology               | 7         | 0.59%   |
| Silicon Integrated Systems [SiS] | 5         | 0.42%   |
| Huawei Technologies              | 5         | 0.42%   |
| ICS Advent                       | 4         | 0.34%   |
| 3Com                             | 3         | 0.25%   |
| ULi Electronics                  | 2         | 0.17%   |
| Qualcomm                         | 2         | 0.17%   |
| Motorola PCS                     | 2         | 0.17%   |
| D-Link System                    | 2         | 0.17%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.08%   |
| Yulong                           | 1         | 0.08%   |
| Trident Microsystems             | 1         | 0.08%   |
| TP-Link                          | 1         | 0.08%   |
| Tenda                            | 1         | 0.08%   |
| T & A Mobile Phones              | 1         | 0.08%   |
| Research In Motion               | 1         | 0.08%   |
| OPPO Electronics                 | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.08%   |
| NetGear                          | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| MediaTek                         | 1         | 0.08%   |
| LG Electronics                   | 1         | 0.08%   |
| Lab126                           | 1         | 0.08%   |
| Intersil                         | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |
| D-Link                           | 1         | 0.08%   |
| Aquantia                         | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 390       | 32.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 136       | 11.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 42        | 3.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 39        | 3.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 1.74%   |
| Nvidia MCP61 Ethernet                                             | 17        | 1.41%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 1.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 1.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 12        | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.91%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 11        | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.83%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 10        | 0.83%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 10        | 0.83%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 9         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 7         | 0.58%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 7         | 0.58%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.58%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 7         | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.5%    |
| Nvidia CK804 Ethernet Controller                                  | 6         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 6         | 0.5%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 6         | 0.5%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 6         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 5         | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5         | 0.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1113      | 52.65%  |
| WiFi     | 970       | 45.88%  |
| Modem    | 30        | 1.42%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 749       | 57.93%  |
| Ethernet | 544       | 42.07%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 714       | 55.35%  |
| 1     | 477       | 36.98%  |
| 0     | 75        | 5.81%   |
| 3     | 19        | 1.47%   |
| 4     | 4         | 0.31%   |
| 6     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1076      | 82.52%  |
| Yes  | 228       | 17.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 205       | 33.5%   |
| Realtek Semiconductor           | 63        | 10.29%  |
| Qualcomm Atheros Communications | 58        | 9.48%   |
| Broadcom                        | 48        | 7.84%   |
| Cambridge Silicon Radio         | 43        | 7.03%   |
| Apple                           | 26        | 4.25%   |
| Lite-On Technology              | 23        | 3.76%   |
| Foxconn / Hon Hai               | 22        | 3.59%   |
| IMC Networks                    | 21        | 3.43%   |
| Hewlett-Packard                 | 20        | 3.27%   |
| Dell                            | 17        | 2.78%   |
| Ralink                          | 13        | 2.12%   |
| Toshiba                         | 12        | 1.96%   |
| ASUSTek Computer                | 10        | 1.63%   |
| Alps Electric                   | 8         | 1.31%   |
| MediaTek                        | 3         | 0.49%   |
| TP-Link                         | 2         | 0.33%   |
| Ralink Technology               | 2         | 0.33%   |
| Micro Star International        | 2         | 0.33%   |
| Marvell Semiconductor           | 2         | 0.33%   |
| Logitech                        | 2         | 0.33%   |
| Askey Computer                  | 2         | 0.33%   |
| Syntek                          | 1         | 0.16%   |
| Smart Modular Technologies      | 1         | 0.16%   |
| Qcom                            | 1         | 0.16%   |
| Integrated System Solution      | 1         | 0.16%   |
| HTC (High Tech Computer)        | 1         | 0.16%   |
| Fujitsu                         | 1         | 0.16%   |
| Dynex                           | 1         | 0.16%   |
| Chicony Electronics             | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 110       | 17.92%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 43        | 7%      |
| Realtek Bluetooth Radio                                                             | 39        | 6.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 32        | 5.21%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 25        | 4.07%   |
| Intel AX201 Bluetooth                                                               | 16        | 2.61%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 14        | 2.28%   |
| Intel AX200 Bluetooth                                                               | 14        | 2.28%   |
| Ralink RT3290 Bluetooth                                                             | 13        | 2.12%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 1.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 1.79%   |
| Apple Bluetooth Host Controller                                                     | 11        | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 10        | 1.63%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 1.47%   |
| Apple Bluetooth HCI                                                                 | 9         | 1.47%   |
| Realtek RTL8723B Bluetooth                                                          | 8         | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 8         | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 1.14%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 7         | 1.14%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 1.14%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.98%   |
| Intel AX210 Bluetooth                                                               | 6         | 0.98%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.81%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 0.81%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.81%   |
| IMC Networks Bluetooth module                                                       | 5         | 0.81%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.81%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.81%   |
| Dell Wireless 365 Bluetooth                                                         | 5         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 5         | 0.81%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 0.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 4         | 0.65%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.49%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 3         | 0.49%   |
| Dell Wireless 350 Bluetooth                                                         | 3         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 865       | 58.41%  |
| AMD                                          | 303       | 20.46%  |
| Nvidia                                       | 197       | 13.3%   |
| C-Media Electronics                          | 22        | 1.49%   |
| VIA Technologies                             | 14        | 0.95%   |
| Creative Labs                                | 10        | 0.68%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.54%   |
| Logitech                                     | 8         | 0.54%   |
| GN Netcom                                    | 6         | 0.41%   |
| Texas Instruments                            | 5         | 0.34%   |
| ASUSTek Computer                             | 4         | 0.27%   |
| XMOS                                         | 3         | 0.2%    |
| Plantronics                                  | 3         | 0.2%    |
| Generalplus Technology                       | 3         | 0.2%    |
| ULi Electronics                              | 2         | 0.14%   |
| Realtek Semiconductor                        | 2         | 0.14%   |
| Razer USA                                    | 2         | 0.14%   |
| Creative Technology                          | 2         | 0.14%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.07%   |
| Zhaoxin                                      | 1         | 0.07%   |
| Sony                                         | 1         | 0.07%   |
| Setek Elektronik                             | 1         | 0.07%   |
| Scarlett                                     | 1         | 0.07%   |
| QinHeng Electronics                          | 1         | 0.07%   |
| Nordic Semiconductor ASA                     | 1         | 0.07%   |
| MosArt Semiconductor                         | 1         | 0.07%   |
| Micro Star International                     | 1         | 0.07%   |
| KORG                                         | 1         | 0.07%   |
| JMTek                                        | 1         | 0.07%   |
| Hewlett-Packard                              | 1         | 0.07%   |
| Guillemot                                    | 1         | 0.07%   |
| Focusrite-Novation                           | 1         | 0.07%   |
| ESI                                          | 1         | 0.07%   |
| Ensoniq                                      | 1         | 0.07%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.07%   |
| Elgato Systems                               | 1         | 0.07%   |
| EGO SYStems                                  | 1         | 0.07%   |
| Dell                                         | 1         | 0.07%   |
| Cirrus Logic                                 | 1         | 0.07%   |
| Asahi Kasei Microsystems                     | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 110       | 6.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 94        | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 77        | 4.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 72        | 4.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 72        | 4.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 59        | 3.38%   |
| AMD FCH Azalia Controller                                                                         | 59        | 3.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 56        | 3.21%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 2.98%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 45        | 2.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 36        | 2.06%   |
| Intel 8 Series HD Audio Controller                                                                | 36        | 2.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 35        | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 34        | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 33        | 1.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 33        | 1.89%   |
| Nvidia High Definition Audio Controller                                                           | 31        | 1.78%   |
| AMD Wrestler HDMI Audio                                                                           | 31        | 1.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 29        | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 1.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 27        | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 1.38%   |
| AMD High Definition Audio Controller                                                              | 24        | 1.38%   |
| Nvidia MCP61 High Definition Audio                                                                | 19        | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 17        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 16        | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 0.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 0.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 0.8%    |
| Intel Broadwell-U Audio Controller                                                                | 14        | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 14        | 0.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 0.74%   |
| AMD Trinity HDMI Audio Controller                                                                 | 13        | 0.74%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12        | 0.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 12        | 0.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 0.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 0.63%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 11        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 185       | 20.07%  |
| Unknown             | 183       | 19.85%  |
| SK hynix            | 151       | 16.38%  |
| Micron Technology   | 75        | 8.13%   |
| Kingston            | 67        | 7.27%   |
| Crucial             | 34        | 3.69%   |
| Corsair             | 31        | 3.36%   |
| Unknown (ABCD)      | 24        | 2.6%    |
| Nanya Technology    | 24        | 2.6%    |
| A-DATA Technology   | 22        | 2.39%   |
| G.Skill             | 20        | 2.17%   |
| Elpida              | 20        | 2.17%   |
| Smart               | 10        | 1.08%   |
| Ramaxel Technology  | 8         | 0.87%   |
| Unknown             | 8         | 0.87%   |
| Patriot             | 6         | 0.65%   |
| Transcend           | 5         | 0.54%   |
| Teikon              | 4         | 0.43%   |
| Team                | 4         | 0.43%   |
| Qimonda             | 3         | 0.33%   |
| PNY                 | 3         | 0.33%   |
| Apacer              | 3         | 0.33%   |
| Toshiba             | 2         | 0.22%   |
| Timetec             | 2         | 0.22%   |
| GOODRAM             | 2         | 0.22%   |
| ASint Technology    | 2         | 0.22%   |
| Unknown (07FB)      | 1         | 0.11%   |
| Unifosa             | 1         | 0.11%   |
| Smart Brazil        | 1         | 0.11%   |
| Silicon Power       | 1         | 0.11%   |
| Sesame              | 1         | 0.11%   |
| Princeton           | 1         | 0.11%   |
| Novatech            | 1         | 0.11%   |
| Neo Forza           | 1         | 0.11%   |
| Multilaser          | 1         | 0.11%   |
| Kllisre             | 1         | 0.11%   |
| Kingmax             | 1         | 0.11%   |
| KINGBANK            | 1         | 0.11%   |
| Infineon            | 1         | 0.11%   |
| HMD                 | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 17        | 1.7%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 12        | 1.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 12        | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 10        | 1%      |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                     | 9         | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 9         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 9         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s             | 8         | 0.8%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s              | 8         | 0.8%    |
| Unknown                                                           | 8         | 0.8%    |
| Unknown RAM Module 1024MB SODIMM DDR2                             | 7         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 7         | 0.7%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                  | 7         | 0.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 6         | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s          | 6         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DRAM                             | 5         | 0.5%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 5         | 0.5%    |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s          | 5         | 0.5%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 5         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3                                | 4         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                       | 4         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 4         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 4         | 0.4%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                        | 4         | 0.4%    |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                     | 4         | 0.4%    |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                     | 4         | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 4         | 0.4%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s            | 4         | 0.4%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s             | 4         | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 4         | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 4         | 0.4%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 4         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 3         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 3         | 0.3%    |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 3         | 0.3%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                    | 3         | 0.3%    |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 3         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 359       | 44.43%  |
| DDR4    | 185       | 22.9%   |
| DDR2    | 105       | 13%     |
| SDRAM   | 44        | 5.45%   |
| LPDDR4  | 41        | 5.07%   |
| Unknown | 30        | 3.71%   |
| DDR     | 16        | 1.98%   |
| LPDDR3  | 15        | 1.86%   |
| DRAM    | 9         | 1.11%   |
| LPDDR5  | 2         | 0.25%   |
| DDR5    | 2         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 514       | 64.74%  |
| DIMM         | 240       | 30.23%  |
| Row Of Chips | 33        | 4.16%   |
| Unknown      | 6         | 0.76%   |
| Chip         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 263       | 29.09%  |
| 2048  | 243       | 26.88%  |
| 8192  | 220       | 24.34%  |
| 1024  | 94        | 10.4%   |
| 16384 | 52        | 5.75%   |
| 512   | 17        | 1.88%   |
| 32768 | 7         | 0.77%   |
| 256   | 5         | 0.55%   |
| 128   | 2         | 0.22%   |
| 65536 | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 206       | 23.76%  |
| 1333    | 70        | 8.07%   |
| 2400    | 64        | 7.38%   |
| 3200    | 60        | 6.92%   |
| 2667    | 56        | 6.46%   |
| 667     | 51        | 5.88%   |
| Unknown | 51        | 5.88%   |
| 1334    | 48        | 5.54%   |
| 800     | 35        | 4.04%   |
| 1066    | 29        | 3.34%   |
| 2133    | 28        | 3.23%   |
| 533     | 22        | 2.54%   |
| 1067    | 21        | 2.42%   |
| 1867    | 16        | 1.85%   |
| 1866    | 14        | 1.61%   |
| 2048    | 13        | 1.5%    |
| 400     | 10        | 1.15%   |
| 3266    | 9         | 1.04%   |
| 4267    | 8         | 0.92%   |
| 333     | 5         | 0.58%   |
| 4199    | 4         | 0.46%   |
| 3600    | 4         | 0.46%   |
| 3400    | 4         | 0.46%   |
| 975     | 4         | 0.46%   |
| 49926   | 3         | 0.35%   |
| 266     | 3         | 0.35%   |
| 4800    | 2         | 0.23%   |
| 3933    | 2         | 0.23%   |
| 3866    | 2         | 0.23%   |
| 3066    | 2         | 0.23%   |
| 3000    | 2         | 0.23%   |
| 2800    | 2         | 0.23%   |
| 1639    | 2         | 0.23%   |
| 41632   | 1         | 0.12%   |
| 8400    | 1         | 0.12%   |
| 6400    | 1         | 0.12%   |
| 5500    | 1         | 0.12%   |
| 3733    | 1         | 0.12%   |
| 3666    | 1         | 0.12%   |
| 3534    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 31.03%  |
| Samsung Electronics   | 6         | 20.69%  |
| Brother Industries    | 5         | 17.24%  |
| Canon                 | 4         | 13.79%  |
| Lexmark International | 2         | 6.9%    |
| STMicroelectronics    | 1         | 3.45%   |
| Seiko Epson           | 1         | 3.45%   |
| Dymo-CoStar           | 1         | 3.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SCX-4200 series                 | 2         | 6.9%    |
| Brother DCP-7055W                       | 2         | 6.9%    |
| STMicroelectronics USB Printing Support | 1         | 3.45%   |
| Seiko Epson TM-T20X                     | 1         | 3.45%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 3.45%   |
| Samsung SCX-3400 Series                 | 1         | 3.45%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 3.45%   |
| Samsung M2020 Series                    | 1         | 3.45%   |
| Lexmark International Z33 Printer       | 1         | 3.45%   |
| Lexmark International MS610de           | 1         | 3.45%   |
| HP PSC 1500 series                      | 1         | 3.45%   |
| HP OfficeJet 4650 series                | 1         | 3.45%   |
| HP LaserJet P2015 series                | 1         | 3.45%   |
| HP LaserJet P1102                       | 1         | 3.45%   |
| HP LaserJet 1200                        | 1         | 3.45%   |
| HP DeskJet D2460                        | 1         | 3.45%   |
| HP DeskJet 3630 series                  | 1         | 3.45%   |
| HP Deskjet 3520 series                  | 1         | 3.45%   |
| HP Deskjet 1050 J410                    | 1         | 3.45%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo  | 1         | 3.45%   |
| Canon TS5100 series                     | 1         | 3.45%   |
| Canon PIXMA MP250                       | 1         | 3.45%   |
| Canon MF3110                            | 1         | 3.45%   |
| Canon CanoScan LiDE 300                 | 1         | 3.45%   |
| Brother PTUSB Printing                  | 1         | 3.45%   |
| Brother PT-2450DX                       | 1         | 3.45%   |
| Brother Printer                         | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 42.86%  |
| Canon           | 3         | 42.86%  |
| Seiko Epson     | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 14.29%  |
| HP scanjet 8270                                               | 1         | 14.29%  |
| HP ScanJet 2400c                                              | 1         | 14.29%  |
| HP HP4470C                                                    | 1         | 14.29%  |
| Canon CanoScan LiDE 500F                                      | 1         | 14.29%  |
| Canon CanoScan LiDE 220                                       | 1         | 14.29%  |
| Canon CanoScan LiDE 200                                       | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 178       | 25.04%  |
| Realtek Semiconductor                  | 61        | 8.58%   |
| Microdia                               | 51        | 7.17%   |
| IMC Networks                           | 50        | 7.03%   |
| Suyin                                  | 34        | 4.78%   |
| Sunplus Innovation Technology          | 29        | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 3.8%    |
| Apple                                  | 27        | 3.8%    |
| Alcor Micro                            | 26        | 3.66%   |
| Quanta                                 | 24        | 3.38%   |
| Bison Electronics                      | 24        | 3.38%   |
| Silicon Motion                         | 21        | 2.95%   |
| Logitech                               | 16        | 2.25%   |
| Syntek                                 | 15        | 2.11%   |
| Lite-On Technology                     | 15        | 2.11%   |
| Acer                                   | 12        | 1.69%   |
| Ricoh                                  | 9         | 1.27%   |
| Lenovo                                 | 9         | 1.27%   |
| ALi                                    | 7         | 0.98%   |
| Z-Star Microelectronics                | 6         | 0.84%   |
| GEMBIRD                                | 6         | 0.84%   |
| Importek                               | 5         | 0.7%    |
| icSpring                               | 5         | 0.7%    |
| Samsung Electronics                    | 4         | 0.56%   |
| Microsoft                              | 4         | 0.56%   |
| Luxvisions Innotech Limited            | 4         | 0.56%   |
| Genesys Logic                          | 4         | 0.56%   |
| Generalplus Technology                 | 4         | 0.56%   |
| Y Media                                | 2         | 0.28%   |
| SunplusIT                              | 2         | 0.28%   |
| Sunplus IT                             | 2         | 0.28%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.28%   |
| OmniVision Technologies                | 2         | 0.28%   |
| LG Electronics                         | 2         | 0.28%   |
| KYE Systems (Mouse Systems)            | 2         | 0.28%   |
| ARC International                      | 2         | 0.28%   |
| WCM_USB                                | 1         | 0.14%   |
| WaveRider Communications               | 1         | 0.14%   |
| USB Camera CS                          | 1         | 0.14%   |
| Toshiba                                | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 19        | 2.66%   |
| Alcor Micro USB 2.0 Camera                           | 19        | 2.66%   |
| Realtek Integrated_Webcam_HD                         | 17        | 2.38%   |
| Chicony HD WebCam                                    | 12        | 1.68%   |
| Chicony HP TrueVision HD                             | 11        | 1.54%   |
| Sunplus HD WebCam                                    | 9         | 1.26%   |
| Chicony USB 2.0 camera                               | 9         | 1.26%   |
| Chicony EasyCamera                                   | 9         | 1.26%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 8         | 1.12%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 7         | 0.98%   |
| IMC Networks USB 2.0 UVC VGA WebCam                  | 7         | 0.98%   |
| Chicony TOSHIBA Web Camera - HD                      | 7         | 0.98%   |
| Chicony HP HD Webcam                                 | 7         | 0.98%   |
| Chicony 2.0M UVC Webcam / CNF7129                    | 7         | 0.98%   |
| Apple FaceTime HD Camera                             | 7         | 0.98%   |
| Microdia Integrated_Webcam_HD                        | 6         | 0.84%   |
| Microdia 1.3 MPixel Integrated Webcam                | 6         | 0.84%   |
| IMC Networks UVC VGA Webcam                          | 6         | 0.84%   |
| Chicony HP Webcam                                    | 6         | 0.84%   |
| Chicony HP TrueVision HD Camera                      | 6         | 0.84%   |
| Apple Built-in iSight                                | 6         | 0.84%   |
| Silicon Motion WebCam SC-0311139N                    | 5         | 0.7%    |
| Realtek USB Camera                                   | 5         | 0.7%    |
| Realtek Integrated Webcam HD                         | 5         | 0.7%    |
| Microdia Integrated Webcam                           | 5         | 0.7%    |
| Lite-On HP HD Camera                                 | 5         | 0.7%    |
| Lenovo Integrated Webcam [R5U877]                    | 5         | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                   | 5         | 0.7%    |
| icSpring camera                                      | 5         | 0.7%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]    | 5         | 0.7%    |
| Chicony Lenovo EasyCamera                            | 5         | 0.7%    |
| Chicony HP HD Camera                                 | 5         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 5         | 0.7%    |
| Z-Star Webcam                                        | 4         | 0.56%   |
| Syntek Integrated Camera                             | 4         | 0.56%   |
| Suyin Acer CrystalEye Webcam                         | 4         | 0.56%   |
| Samsung Galaxy series, misc. (MTP mode)              | 4         | 0.56%   |
| Realtek Lenovo EasyCamera                            | 4         | 0.56%   |
| Realtek HD WebCam                                    | 4         | 0.56%   |
| Realtek 2SF022                                       | 4         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 33        | 38.37%  |
| AuthenTec                  | 16        | 18.6%   |
| Upek                       | 11        | 12.79%  |
| Synaptics                  | 7         | 8.14%   |
| STMicroelectronics         | 7         | 8.14%   |
| Shenzhen Goodix Technology | 6         | 6.98%   |
| Samsung Electronics        | 2         | 2.33%   |
| LighTuning Technology      | 2         | 2.33%   |
| Elan Microelectronics      | 2         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 10        | 11.63%  |
| Validity Sensors VFS495 Fingerprint Reader                | 7         | 8.14%   |
| STMicroelectronics Fingerprint Reader                     | 7         | 8.14%   |
| Validity Sensors VFS471 Fingerprint Reader                | 5         | 5.81%   |
| AuthenTec AES2810                                         | 5         | 5.81%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 5         | 5.81%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 3         | 3.49%   |
| Validity Sensors VFS491                                   | 3         | 3.49%   |
| Validity Sensors VFS451 Fingerprint Reader                | 3         | 3.49%   |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 3.49%   |
| AuthenTec AES1600                                         | 3         | 3.49%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 2         | 2.33%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 2.33%   |
| Validity Sensors Fingerprint scanner                      | 2         | 2.33%   |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 2.33%   |
| Shenzhen Goodix FingerPrint                               | 2         | 2.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 2.33%   |
| Elan ELAN:Fingerprint                                     | 2         | 2.33%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 2.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 1.16%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 1.16%   |
| Validity Sensors VFS300 Fingerprint Reader                | 1         | 1.16%   |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 1.16%   |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 1.16%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.16%   |
| Upek TCS5B Fingerprint sensor                             | 1         | 1.16%   |
| Synaptics WBDI                                            | 1         | 1.16%   |
| Synaptics UWP WBDI                                        | 1         | 1.16%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.16%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 1.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 1.16%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 1.16%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 1.16%   |
| Samsung Fingerprint Device                                | 1         | 1.16%   |
| AuthenTec Fingerprint Sensor                              | 1         | 1.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 12        | 34.29%  |
| Alcor Micro           | 10        | 28.57%  |
| O2 Micro              | 7         | 20%     |
| Upek                  | 1         | 2.86%   |
| Realtek Semiconductor | 1         | 2.86%   |
| OmniKey               | 1         | 2.86%   |
| Lenovo                | 1         | 2.86%   |
| Gemalto (was Gemplus) | 1         | 2.86%   |
| Cherry                | 1         | 2.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 25.71%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 14.29%  |
| Broadcom 5880                                                                | 5         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 5.71%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.86%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.86%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 2.86%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.86%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.86%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 2.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.86%   |
| Broadcom 58200                                                               | 1         | 2.86%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 988       | 75.94%  |
| 1     | 258       | 19.83%  |
| 2     | 45        | 3.46%   |
| 3     | 7         | 0.54%   |
| 4     | 2         | 0.15%   |
| 5     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 94        | 25.2%   |
| Fingerprint reader       | 85        | 22.79%  |
| Net/wireless             | 50        | 13.4%   |
| Chipcard                 | 31        | 8.31%   |
| Bluetooth                | 22        | 5.9%    |
| Communication controller | 14        | 3.75%   |
| Camera                   | 14        | 3.75%   |
| Multimedia controller    | 12        | 3.22%   |
| Sound                    | 9         | 2.41%   |
| Modem                    | 9         | 2.41%   |
| Net/ethernet             | 8         | 2.14%   |
| Storage                  | 7         | 1.88%   |
| Unassigned class         | 5         | 1.34%   |
| Flash memory             | 4         | 1.07%   |
| Dvb card                 | 4         | 1.07%   |
| Network                  | 3         | 0.8%    |
| Card reader              | 2         | 0.54%   |

