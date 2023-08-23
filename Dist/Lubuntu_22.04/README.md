Lubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_22.04/Notebook/README.md).

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

Total: 405

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Samsung       | N150P/N210P/N220P           | Notebook    | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| Toshiba       | Satellite L875D             | Notebook    | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Dell          | Inspiron 1520               | Notebook    | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | Notebook    | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| HP            | 3646h                       | Desktop     | [01f2207fe0](https://linux-hardware.org/?probe=01f2207fe0) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | Notebook    | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | Notebook    | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| Gateway       | ZX4250                      | All in one  | [8fb942eccd](https://linux-hardware.org/?probe=8fb942eccd) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [ff650dc0df](https://linux-hardware.org/?probe=ff650dc0df) | Jul 10, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f1b70e168](https://linux-hardware.org/?probe=2f1b70e168) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [282c9db256](https://linux-hardware.org/?probe=282c9db256) | Jul 08, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | Notebook    | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Unknown       | Unknown                     | Other       | [f49e789b52](https://linux-hardware.org/?probe=f49e789b52) | Jul 04, 2023 |
| Google        | Pyro                        | Notebook    | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [7c6c7cff66](https://linux-hardware.org/?probe=7c6c7cff66) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f0268ac6a8](https://linux-hardware.org/?probe=f0268ac6a8) | Jun 26, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [e094f469bc](https://linux-hardware.org/?probe=e094f469bc) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [af1a5cda08](https://linux-hardware.org/?probe=af1a5cda08) | Jun 16, 2023 |
| Dell          | Precision 3570              | Notebook    | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| HP            | 3646h                       | Desktop     | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | Notebook    | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 3646h                       | Desktop     | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [88c6b12404](https://linux-hardware.org/?probe=88c6b12404) | May 27, 2023 |
| Dell          | Latitude E6430              | Notebook    | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | Notebook    | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | Notebook    | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Acer          | EQ45M                       | Desktop     | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [9709c9cf35](https://linux-hardware.org/?probe=9709c9cf35) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| HP            | Laptop 15-bs2xx             | Notebook    | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | Notebook    | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b16afcac8b](https://linux-hardware.org/?probe=b16afcac8b) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | Notebook    | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | Notebook    | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Google        | Celes                       | Notebook    | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | Notebook    | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [1fbc4cea88](https://linux-hardware.org/?probe=1fbc4cea88) | Feb 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Dell          | 0FPP7F A00                  | Desktop     | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Acer          | AO756                       | Notebook    | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-43-generic | 36        | 10.91%  |
| 5.15.0-56-generic | 19        | 5.76%   |
| 5.15.0-25-generic | 17        | 5.15%   |
| 5.15.0-60-generic | 14        | 4.24%   |
| 5.19.0-32-generic | 13        | 3.94%   |
| 5.15.0-58-generic | 12        | 3.64%   |
| 5.15.0-47-generic | 12        | 3.64%   |
| 5.15.0-30-generic | 10        | 3.03%   |
| 5.19.0-46-generic | 9         | 2.73%   |
| 5.19.0-41-generic | 9         | 2.73%   |
| 5.15.0-52-generic | 9         | 2.73%   |
| 5.15.0-46-generic | 9         | 2.73%   |
| 5.15.0-41-generic | 9         | 2.73%   |
| 5.15.0-27-generic | 9         | 2.73%   |
| 5.19.0-35-generic | 8         | 2.42%   |
| 5.15.0-53-generic | 8         | 2.42%   |
| 5.19.0-43-generic | 7         | 2.12%   |
| 5.19.0-50-generic | 6         | 1.82%   |
| 5.15.0-67-generic | 6         | 1.82%   |
| 5.15.0-50-generic | 6         | 1.82%   |
| 5.15.0-48-generic | 6         | 1.82%   |
| 5.15.0-40-generic | 6         | 1.82%   |
| 5.15.0-73-generic | 5         | 1.52%   |
| 5.15.0-71-generic | 5         | 1.52%   |
| 5.15.0-57-generic | 5         | 1.52%   |
| 5.15.0-35-generic | 5         | 1.52%   |
| 5.19.0-40-generic | 4         | 1.21%   |
| 5.19.0-38-generic | 4         | 1.21%   |
| 5.15.0-75-generic | 4         | 1.21%   |
| 5.15.0-39-generic | 4         | 1.21%   |
| 5.15.0-33-generic | 4         | 1.21%   |
| 6.2.0-26-generic  | 3         | 0.91%   |
| 5.19.0-45-generic | 3         | 0.91%   |
| 5.19.0-42-generic | 3         | 0.91%   |
| 5.15.0-76-generic | 2         | 0.61%   |
| 5.15.0-72-generic | 2         | 0.61%   |
| 5.15.0-70-generic | 2         | 0.61%   |
| 5.15.0-37-generic | 2         | 0.61%   |
| 5.15.0-23-generic | 2         | 0.61%   |
| 5.15.0-18-generic | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 222       | 72.31%  |
| 5.19.0  | 68        | 22.15%  |
| 6.2.0   | 3         | 0.98%   |
| 6.3.3   | 1         | 0.33%   |
| 6.2.8   | 1         | 0.33%   |
| 6.1.26  | 1         | 0.33%   |
| 6.1.12  | 1         | 0.33%   |
| 6.1.0   | 1         | 0.33%   |
| 6.0.8   | 1         | 0.33%   |
| 6.0.14  | 1         | 0.33%   |
| 6.0.12  | 1         | 0.33%   |
| 6.0.10  | 1         | 0.33%   |
| 5.4.0   | 1         | 0.33%   |
| 5.19.8  | 1         | 0.33%   |
| 5.19.11 | 1         | 0.33%   |
| 5.18.0  | 1         | 0.33%   |
| 5.14.0  | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 222       | 72.31%  |
| 5.19    | 70        | 22.8%   |
| 6.2     | 4         | 1.3%    |
| 6.0     | 4         | 1.3%    |
| 6.1     | 3         | 0.98%   |
| 6.3     | 1         | 0.33%   |
| 5.4     | 1         | 0.33%   |
| 5.18    | 1         | 0.33%   |
| 5.14    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 294       | 98.66%  |
| aarch64 | 4         | 1.34%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 285       | 95.32%  |
| LXDE       | 8         | 2.68%   |
| X-Cinnamon | 2         | 0.67%   |
| GNOME      | 2         | 0.67%   |
| XFCE       | 1         | 0.33%   |
| KDE5       | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 288       | 95.68%  |
| Tty         | 10        | 3.32%   |
| Wayland     | 2         | 0.66%   |
| Unspecified | 1         | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 257       | 85.38%  |
| LightDM | 17        | 5.65%   |
| Unknown | 16        | 5.32%   |
| GDM3    | 8         | 2.66%   |
| XDM     | 1         | 0.33%   |
| SLiM    | 1         | 0.33%   |
| LXDM    | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 96        | 32%     |
| fr_FR  | 28        | 9.33%   |
| de_DE  | 22        | 7.33%   |
| it_IT  | 18        | 6%      |
| en_GB  | 16        | 5.33%   |
| C      | 16        | 5.33%   |
| pt_BR  | 12        | 4%      |
| en_AG  | 9         | 3%      |
| ru_RU  | 8         | 2.67%   |
| pl_PL  | 8         | 2.67%   |
| es_ES  | 8         | 2.67%   |
| en_AU  | 7         | 2.33%   |
| es_MX  | 6         | 2%      |
| es_AR  | 6         | 2%      |
| nl_BE  | 4         | 1.33%   |
| es_CR  | 4         | 1.33%   |
| tr_TR  | 3         | 1%      |
| es_CO  | 3         | 1%      |
| en_CA  | 3         | 1%      |
| el_GR  | 2         | 0.67%   |
| cs_CZ  | 2         | 0.67%   |
| sv_SE  | 1         | 0.33%   |
| sk_SK  | 1         | 0.33%   |
| ru_UA  | 1         | 0.33%   |
| nl_NL  | 1         | 0.33%   |
| lzh_TW | 1         | 0.33%   |
| ja_JP  | 1         | 0.33%   |
| hu_HU  | 1         | 0.33%   |
| fr_CA  | 1         | 0.33%   |
| fi_FI  | 1         | 0.33%   |
| es_PE  | 1         | 0.33%   |
| es_EC  | 1         | 0.33%   |
| es_CL  | 1         | 0.33%   |
| en_ZA  | 1         | 0.33%   |
| en_PH  | 1         | 0.33%   |
| en_DE  | 1         | 0.33%   |
| de_CH  | 1         | 0.33%   |
| da_DK  | 1         | 0.33%   |
| cv_RU  | 1         | 0.33%   |
| aa_DJ  | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 187       | 62.54%  |
| EFI  | 112       | 37.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 265       | 87.17%  |
| Overlay | 18        | 5.92%   |
| Tmpfs   | 14        | 4.61%   |
| Btrfs   | 4         | 1.32%   |
| XXX4    | 1         | 0.33%   |
| Xfs     | 1         | 0.33%   |
| Ext2    | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 154       | 50.99%  |
| MBR     | 95        | 31.46%  |
| Unknown | 53        | 17.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 262       | 87.04%  |
| Yes       | 39        | 12.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 212       | 70.67%  |
| Yes       | 88        | 29.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 44        | 14.77%  |
| Hewlett-Packard         | 35        | 11.74%  |
| Dell                    | 35        | 11.74%  |
| ASUSTek Computer        | 29        | 9.73%   |
| Acer                    | 21        | 7.05%   |
| MSI                     | 16        | 5.37%   |
| Unknown                 | 11        | 3.69%   |
| Apple                   | 10        | 3.36%   |
| Google                  | 8         | 2.68%   |
| Toshiba                 | 6         | 2.01%   |
| Intel                   | 6         | 2.01%   |
| Gigabyte Technology     | 6         | 2.01%   |
| Fujitsu                 | 6         | 2.01%   |
| ASRock                  | 6         | 2.01%   |
| Sony                    | 4         | 1.34%   |
| Positivo                | 4         | 1.34%   |
| Pegatron                | 4         | 1.34%   |
| AMI                     | 4         | 1.34%   |
| Samsung Electronics     | 3         | 1.01%   |
| Mediacom                | 3         | 1.01%   |
| Gateway                 | 3         | 1.01%   |
| Raspberry Pi Foundation | 2         | 0.67%   |
| OEM                     | 2         | 0.67%   |
| HUAWEI                  | 2         | 0.67%   |
| GPU Company             | 2         | 0.67%   |
| ZOTAC                   | 1         | 0.34%   |
| YANYU                   | 1         | 0.34%   |
| TrekStor                | 1         | 0.34%   |
| Thomson                 | 1         | 0.34%   |
| Shuttle                 | 1         | 0.34%   |
| SGIN                    | 1         | 0.34%   |
| Rockchip                | 1         | 0.34%   |
| Pretech                 | 1         | 0.34%   |
| Prestigio               | 1         | 0.34%   |
| Packard Bell            | 1         | 0.34%   |
| NEC Computers           | 1         | 0.34%   |
| Microsoft               | 1         | 0.34%   |
| libre-computer          | 1         | 0.34%   |
| Kiano                   | 1         | 0.34%   |
| IFSA                    | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 12        | 4.03%   |
| MSI MS-7C37                                | 3         | 1.01%   |
| HP Pavilion 15                             | 3         | 1.01%   |
| Apple MacBookPro8,1                        | 3         | 1.01%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 0.67%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 0.67%   |
| Lenovo G50-30 80G0                         | 2         | 0.67%   |
| HP Pavilion g6                             | 2         | 0.67%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 0.67%   |
| Dell Dimension 9100                        | 2         | 0.67%   |
| Apple MacBook4,1                           | 2         | 0.67%   |
| Acer Aspire SW3-013                        | 2         | 0.67%   |
| ZOTAC NM10                                 | 1         | 0.34%   |
| YANYU ITX-S192                             | 1         | 0.34%   |
| TrekStor SurfTab wintron 7.0 ST70416-6     | 1         | 0.34%   |
| Toshiba Satellite Radius P55W-B            | 1         | 0.34%   |
| Toshiba Satellite Pro S500                 | 1         | 0.34%   |
| Toshiba Satellite P70-A                    | 1         | 0.34%   |
| Toshiba Satellite L875D                    | 1         | 0.34%   |
| Toshiba Satellite L40                      | 1         | 0.34%   |
| Toshiba Satellite C660                     | 1         | 0.34%   |
| Thomson N14C4WH64                          | 1         | 0.34%   |
| Sony VPCEH2E1R                             | 1         | 0.34%   |
| Sony VPCEB15FM                             | 1         | 0.34%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.34%   |
| Sony SVE14A2V1EW                           | 1         | 0.34%   |
| Shuttle XS35V3                             | 1         | 0.34%   |
| SGIN laptop                                | 1         | 0.34%   |
| Samsung N150P/N210P/N220P                  | 1         | 0.34%   |
| Samsung N150/N210/N220                     | 1         | 0.34%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.34%   |
| Rockchip RK3318 BOX                        | 1         | 0.34%   |
| RPi Raspberry Pi 4 Model B Rev 1.5         | 1         | 0.34%   |
| RPi Raspberry Pi                           | 1         | 0.34%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.34%   |
| Prestigio PSB141C01BFH                     | 1         | 0.34%   |
| Positivo Q232A                             | 1         | 0.34%   |
| Positivo POS-AG31AP                        | 1         | 0.34%   |
| Positivo P5VD2-MX                          | 1         | 0.34%   |
| Positivo i500pro                           | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 15        | 5.03%   |
| Lenovo ThinkPad    | 14        | 4.7%    |
| Acer Aspire        | 14        | 4.7%    |
| Unknown            | 12        | 4.03%   |
| Dell Latitude      | 10        | 3.36%   |
| HP Pavilion        | 8         | 2.68%   |
| Toshiba Satellite  | 6         | 2.01%   |
| Dell Inspiron      | 5         | 1.68%   |
| HP ProBook         | 4         | 1.34%   |
| Fujitsu LIFEBOOK   | 4         | 1.34%   |
| Dell Vostro        | 4         | 1.34%   |
| Dell Precision     | 4         | 1.34%   |
| Dell OptiPlex      | 4         | 1.34%   |
| MSI MS-7C37        | 3         | 1.01%   |
| HP Laptop          | 3         | 1.01%   |
| HP Compaq          | 3         | 1.01%   |
| Dell XPS           | 3         | 1.01%   |
| ASUS ROG           | 3         | 1.01%   |
| Apple MacBookPro8  | 3         | 1.01%   |
| RPi Raspberry      | 2         | 0.67%   |
| Mediacom WinPad    | 2         | 0.67%   |
| Lenovo ThinkCentre | 2         | 0.67%   |
| Lenovo G50-30      | 2         | 0.67%   |
| HP EliteBook       | 2         | 0.67%   |
| Dell Studio        | 2         | 0.67%   |
| Dell Dimension     | 2         | 0.67%   |
| ASUS PRIME         | 2         | 0.67%   |
| Apple MacBook4     | 2         | 0.67%   |
| ZOTAC NM10         | 1         | 0.34%   |
| YANYU ITX-S192     | 1         | 0.34%   |
| TrekStor SurfTab   | 1         | 0.34%   |
| Thomson N14C4WH64  | 1         | 0.34%   |
| Sony VPCEH2E1R     | 1         | 0.34%   |
| Sony VPCEB15FM     | 1         | 0.34%   |
| Sony VGN-SZ71WN    | 1         | 0.34%   |
| Sony SVE14A2V1EW   | 1         | 0.34%   |
| Shuttle XS35V3     | 1         | 0.34%   |
| SGIN laptop        | 1         | 0.34%   |
| Samsung N150P      | 1         | 0.34%   |
| Samsung N150       | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 25        | 8.39%   |
| 2011    | 25        | 8.39%   |
| 2012    | 24        | 8.05%   |
| 2021    | 22        | 7.38%   |
| 2015    | 22        | 7.38%   |
| 2010    | 22        | 7.38%   |
| 2019    | 20        | 6.71%   |
| 2008    | 20        | 6.71%   |
| 2014    | 16        | 5.37%   |
| 2022    | 15        | 5.03%   |
| 2016    | 15        | 5.03%   |
| 2009    | 15        | 5.03%   |
| 2020    | 14        | 4.7%    |
| 2017    | 13        | 4.36%   |
| 2007    | 12        | 4.03%   |
| 2018    | 10        | 3.36%   |
| Unknown | 3         | 1.01%   |
| 2023    | 2         | 0.67%   |
| 2006    | 2         | 0.67%   |
| 2001    | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 186       | 62.42%  |
| Desktop        | 87        | 29.19%  |
| Convertible    | 6         | 2.01%   |
| Mini pc        | 5         | 1.68%   |
| System on chip | 4         | 1.34%   |
| Tablet         | 4         | 1.34%   |
| All in one     | 4         | 1.34%   |
| Other          | 1         | 0.34%   |
| Server         | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 286       | 95.02%  |
| Enabled  | 15        | 4.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 289       | 96.98%  |
| Yes  | 9         | 3.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 92        | 30.56%  |
| 4.01-8.0    | 72        | 23.92%  |
| 1.01-2.0    | 41        | 13.62%  |
| 8.01-16.0   | 33        | 10.96%  |
| 16.01-24.0  | 28        | 9.3%    |
| 32.01-64.0  | 14        | 4.65%   |
| 2.01-3.0    | 11        | 3.65%   |
| 64.01-256.0 | 4         | 1.33%   |
| 0.51-1.0    | 4         | 1.33%   |
| 24.01-32.0  | 2         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 145       | 45.89%  |
| 0.51-1.0  | 71        | 22.47%  |
| 2.01-3.0  | 63        | 19.94%  |
| 4.01-8.0  | 20        | 6.33%   |
| 3.01-4.0  | 11        | 3.48%   |
| 8.01-16.0 | 3         | 0.95%   |
| 0.01-0.5  | 3         | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 209       | 69.44%  |
| 2      | 65        | 21.59%  |
| 3      | 14        | 4.65%   |
| 5      | 4         | 1.33%   |
| 0      | 4         | 1.33%   |
| 4      | 2         | 0.66%   |
| 12     | 1         | 0.33%   |
| 7      | 1         | 0.33%   |
| 6      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 177       | 59.2%   |
| Yes       | 122       | 40.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 240       | 80.27%  |
| No        | 59        | 19.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 75.5%   |
| No        | 73        | 24.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 52.81%  |
| No        | 143       | 47.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 52        | 17.45%  |
| Germany      | 33        | 11.07%  |
| France       | 30        | 10.07%  |
| Italy        | 22        | 7.38%   |
| Poland       | 13        | 4.36%   |
| Brazil       | 13        | 4.36%   |
| UK           | 11        | 3.69%   |
| Russia       | 11        | 3.69%   |
| Spain        | 10        | 3.36%   |
| Belgium      | 6         | 2.01%   |
| Australia    | 6         | 2.01%   |
| Argentina    | 6         | 2.01%   |
| Ukraine      | 5         | 1.68%   |
| Mexico       | 5         | 1.68%   |
| Indonesia    | 5         | 1.68%   |
| Costa Rica   | 5         | 1.68%   |
| Canada       | 5         | 1.68%   |
| Turkey       | 4         | 1.34%   |
| Sweden       | 3         | 1.01%   |
| Hungary      | 3         | 1.01%   |
| Finland      | 3         | 1.01%   |
| Czechia      | 3         | 1.01%   |
| Colombia     | 3         | 1.01%   |
| Vietnam      | 2         | 0.67%   |
| UAE          | 2         | 0.67%   |
| South Africa | 2         | 0.67%   |
| Portugal     | 2         | 0.67%   |
| Pakistan     | 2         | 0.67%   |
| Netherlands  | 2         | 0.67%   |
| Latvia       | 2         | 0.67%   |
| Greece       | 2         | 0.67%   |
| Venezuela    | 1         | 0.34%   |
| Thailand     | 1         | 0.34%   |
| Taiwan       | 1         | 0.34%   |
| Switzerland  | 1         | 0.34%   |
| Slovakia     | 1         | 0.34%   |
| Saudi Arabia | 1         | 0.34%   |
| Romania      | 1         | 0.34%   |
| Philippines  | 1         | 0.34%   |
| Peru         | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Paris                  | 8         | 2.57%   |
| Melbourne              | 4         | 1.29%   |
| Kyiv                   | 4         | 1.29%   |
| Heredia                | 4         | 1.29%   |
| Warsaw                 | 3         | 0.96%   |
| Moscow                 | 3         | 0.96%   |
| Ghent                  | 3         | 0.96%   |
| Bruhl                  | 3         | 0.96%   |
| Valencia               | 2         | 0.64%   |
| Sarospatak             | 2         | 0.64%   |
| Sao Paulo              | 2         | 0.64%   |
| Rome                   | 2         | 0.64%   |
| Prague                 | 2         | 0.64%   |
| Porto Alegre           | 2         | 0.64%   |
| Novo Gama              | 2         | 0.64%   |
| Monheim am Rhein       | 2         | 0.64%   |
| Milan                  | 2         | 0.64%   |
| Madrid                 | 2         | 0.64%   |
| Largo                  | 2         | 0.64%   |
| Lansing                | 2         | 0.64%   |
| Karlstad               | 2         | 0.64%   |
| Karachi                | 2         | 0.64%   |
| Jakarta                | 2         | 0.64%   |
| Eugene                 | 2         | 0.64%   |
| Dubai                  | 2         | 0.64%   |
| Columbus               | 2         | 0.64%   |
| Chicago                | 2         | 0.64%   |
| Bogotá                | 2         | 0.64%   |
| Belo Horizonte         | 2         | 0.64%   |
| Zizur Mayor            | 1         | 0.32%   |
| Zawiercie              | 1         | 0.32%   |
| Zagreb                 | 1         | 0.32%   |
| Yoshkar-Ola            | 1         | 0.32%   |
| Yorkville              | 1         | 0.32%   |
| Yerevan                | 1         | 0.32%   |
| Yekaterinburg          | 1         | 0.32%   |
| Wolfhagen              | 1         | 0.32%   |
| Wetteren               | 1         | 0.32%   |
| West Stockbridge       | 1         | 0.32%   |
| Wattignies-la-Victoire | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 54        | 71     | 14.36%  |
| WDC                       | 50        | 70     | 13.3%   |
| Unknown                   | 42        | 57     | 11.17%  |
| Samsung Electronics       | 40        | 56     | 10.64%  |
| Toshiba                   | 20        | 21     | 5.32%   |
| Hitachi                   | 20        | 27     | 5.32%   |
| Kingston                  | 19        | 22     | 5.05%   |
| SanDisk                   | 18        | 18     | 4.79%   |
| Crucial                   | 10        | 10     | 2.66%   |
| HGST                      | 8         | 9      | 2.13%   |
| A-DATA Technology         | 7         | 7      | 1.86%   |
| Transcend                 | 5         | 7      | 1.33%   |
| SK hynix                  | 5         | 5      | 1.33%   |
| Micron Technology         | 5         | 6      | 1.33%   |
| Intel                     | 5         | 6      | 1.33%   |
| GOODRAM                   | 4         | 4      | 1.06%   |
| China                     | 4         | 4      | 1.06%   |
| SPCC                      | 3         | 4      | 0.8%    |
| PNY                       | 3         | 3      | 0.8%    |
| Apacer                    | 3         | 3      | 0.8%    |
| Unknown                   | 3         | 3      | 0.8%    |
| UMIS                      | 2         | 2      | 0.53%   |
| Silicon Motion            | 2         | 2      | 0.53%   |
| Patriot                   | 2         | 2      | 0.53%   |
| Micron/Crucial Technology | 2         | 3      | 0.53%   |
| Maxtor                    | 2         | 2      | 0.53%   |
| Fujitsu                   | 2         | 2      | 0.53%   |
| Apple                     | 2         | 3      | 0.53%   |
| WDC WDS2                  | 1         | 1      | 0.27%   |
| WD MediaMax               | 1         | 1      | 0.27%   |
| W800S                     | 1         | 1      | 0.27%   |
| TO Exter                  | 1         | 1      | 0.27%   |
| Teclast                   | 1         | 1      | 0.27%   |
| Team                      | 1         | 1      | 0.27%   |
| T-FORCE                   | 1         | 1      | 0.27%   |
| RSH-319                   | 1         | 1      | 0.27%   |
| Rogueware                 | 1         | 1      | 0.27%   |
| Plextor                   | 1         | 1      | 0.27%   |
| Phison                    | 1         | 1      | 0.27%   |
| NGFF                      | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 8         | 1.93%   |
| Kingston SA400S37240G 240GB SSD    | 7         | 1.69%   |
| Unknown MMC Card  32GB             | 6         | 1.45%   |
| Seagate ST500DM002-1BD142 500GB    | 6         | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 1.45%   |
| SanDisk DF4032  32GB               | 6         | 1.45%   |
| Seagate ST9500325AS 500GB          | 5         | 1.21%   |
| Unknown NCard  32GB                | 4         | 0.97%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 0.72%   |
| Unknown MMC Card  16GB             | 3         | 0.72%   |
| Toshiba MQ01ABF050 500GB           | 3         | 0.72%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 0.72%   |
| Unknown                            | 3         | 0.72%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 2         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.48%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 2         | 0.48%   |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.48%   |
| Unknown SD/MMC/MS PRO 128GB        | 2         | 0.48%   |
| Unknown SC64G  64GB                | 2         | 0.48%   |
| Unknown SC256  256GB               | 2         | 0.48%   |
| Unknown MMC64G  64GB               | 2         | 0.48%   |
| Unknown DA4064  64GB               | 2         | 0.48%   |
| Unknown DA4032  32GB               | 2         | 0.48%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.48%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.48%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.48%   |
| SPCC Solid State Disk 120GB        | 2         | 0.48%   |
| SK hynix HBG4e  32GB               | 2         | 0.48%   |
| Seagate ST3120213AS 120GB          | 2         | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.48%   |
| SanDisk SDSSDA480G 480GB           | 2         | 0.48%   |
| SanDisk DF4064  64GB               | 2         | 0.48%   |
| Samsung SSD 970 EVO Plus 2TB       | 2         | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB       | 2         | 0.48%   |
| Samsung SSD 870 EVO 500GB          | 2         | 0.48%   |
| Samsung SSD 860 EVO 500GB          | 2         | 0.48%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.48%   |
| Samsung MZVLQ256HAJD-000H1 256GB   | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 70     | 33.75%  |
| WDC                 | 40        | 53     | 25%     |
| Hitachi             | 20        | 27     | 12.5%   |
| Toshiba             | 18        | 19     | 11.25%  |
| Samsung Electronics | 9         | 15     | 5.63%   |
| HGST                | 8         | 9      | 5%      |
| Unknown             | 2         | 2      | 1.25%   |
| Maxtor              | 2         | 2      | 1.25%   |
| Fujitsu             | 2         | 2      | 1.25%   |
| WD MediaMax         | 1         | 1      | 0.63%   |
| RSH-319             | 1         | 1      | 0.63%   |
| External            | 1         | 1      | 0.63%   |
| Apricorn            | 1         | 1      | 0.63%   |
| Apple               | 1         | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 26     | 16.95%  |
| Kingston            | 17        | 20     | 14.41%  |
| SanDisk             | 9         | 9      | 7.63%   |
| WDC                 | 8         | 10     | 6.78%   |
| A-DATA Technology   | 6         | 6      | 5.08%   |
| Transcend           | 5         | 7      | 4.24%   |
| Crucial             | 5         | 5      | 4.24%   |
| Intel               | 4         | 4      | 3.39%   |
| GOODRAM             | 4         | 4      | 3.39%   |
| SPCC                | 3         | 4      | 2.54%   |
| PNY                 | 3         | 3      | 2.54%   |
| Micron Technology   | 3         | 3      | 2.54%   |
| Apacer              | 3         | 3      | 2.54%   |
| Toshiba             | 2         | 2      | 1.69%   |
| Patriot             | 2         | 2      | 1.69%   |
| China               | 2         | 2      | 1.69%   |
| WDC WDS2            | 1         | 1      | 0.85%   |
| W800S               | 1         | 1      | 0.85%   |
| TO Exter            | 1         | 1      | 0.85%   |
| Teclast             | 1         | 1      | 0.85%   |
| Team                | 1         | 1      | 0.85%   |
| Rogueware           | 1         | 1      | 0.85%   |
| Plextor             | 1         | 1      | 0.85%   |
| NGFF                | 1         | 1      | 0.85%   |
| Netac               | 1         | 1      | 0.85%   |
| LITEONIT            | 1         | 1      | 0.85%   |
| LITEON              | 1         | 1      | 0.85%   |
| Lexar               | 1         | 1      | 0.85%   |
| Leqixiang           | 1         | 1      | 0.85%   |
| Lenovo              | 1         | 1      | 0.85%   |
| Kston               | 1         | 3      | 0.85%   |
| KINGPOWER           | 1         | 1      | 0.85%   |
| HUSKY               | 1         | 1      | 0.85%   |
| Hewlett-Packard     | 1         | 1      | 0.85%   |
| Gigabyte Technology | 1         | 1      | 0.85%   |
| Emtec               | 1         | 1      | 0.85%   |
| BR                  | 1         | 1      | 0.85%   |
| 2.5"                | 1         | 2      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 139       | 204    | 39.6%   |
| SSD     | 112       | 135    | 31.91%  |
| MMC     | 54        | 70     | 15.38%  |
| NVMe    | 41        | 51     | 11.68%  |
| Unknown | 5         | 8      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 225       | 333    | 67.98%  |
| MMC  | 54        | 70     | 16.31%  |
| NVMe | 41        | 51     | 12.39%  |
| SAS  | 11        | 14     | 3.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 181       | 232    | 69.88%  |
| 0.51-1.0   | 52        | 68     | 20.08%  |
| 1.01-2.0   | 16        | 23     | 6.18%   |
| 2.01-3.0   | 4         | 5      | 1.54%   |
| 4.01-10.0  | 4         | 7      | 1.54%   |
| 3.01-4.0   | 2         | 4      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 98        | 32.24%  |
| 251-500        | 65        | 21.38%  |
| 51-100         | 32        | 10.53%  |
| 1-20           | 28        | 9.21%   |
| 21-50          | 26        | 8.55%   |
| 501-1000       | 26        | 8.55%   |
| 1001-2000      | 13        | 4.28%   |
| More than 3000 | 10        | 3.29%   |
| 2001-3000      | 5         | 1.64%   |
| Unknown        | 1         | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 159       | 51.29%  |
| 21-50          | 56        | 18.06%  |
| 51-100         | 35        | 11.29%  |
| 101-250        | 28        | 9.03%   |
| 501-1000       | 9         | 2.9%    |
| 251-500        | 8         | 2.58%   |
| More than 3000 | 6         | 1.94%   |
| 1001-2000      | 6         | 1.94%   |
| 2001-3000      | 2         | 0.65%   |
| Unknown        | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB        | 5         | 6      | 9.43%   |
| Seagate ST9500325AS 500GB                 | 2         | 2      | 3.77%   |
| Seagate ST500LT012-1DG142 500GB           | 2         | 2      | 3.77%   |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 3.77%   |
| WDC WDS480G2G0A-00JH30 480GB SSD          | 1         | 1      | 1.89%   |
| WDC WD60EFRX-68L0BN1 6TB                  | 1         | 2      | 1.89%   |
| WDC WD5000LPCX-60VHAT1 500GB              | 1         | 1      | 1.89%   |
| WDC WD5000BPVT-75HXZT1 500GB              | 1         | 1      | 1.89%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1         | 1      | 1.89%   |
| WDC WD3200BPVT-22JJ5T0 320GB              | 1         | 1      | 1.89%   |
| WDC WD3200AACS-00M6B0 320GB               | 1         | 1      | 1.89%   |
| WDC WD2003FYYS-02W0B0 2TB                 | 1         | 1      | 1.89%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 1.89%   |
| WDC WD10SPZX-08Z10 1TB                    | 1         | 1      | 1.89%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 1.89%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 1.89%   |
| WDC WD10EACS-00D6B1 1TB                   | 1         | 1      | 1.89%   |
| Transcend TS256GSSD720 256GB              | 1         | 1      | 1.89%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 1.89%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 1.89%   |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 1.89%   |
| Toshiba MK2556GSY 250GB                   | 1         | 1      | 1.89%   |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 1.89%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 1.89%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 1.89%   |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 1.89%   |
| Seagate ST320LT012-9WS14C 320GB           | 1         | 1      | 1.89%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1      | 1.89%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 1      | 1.89%   |
| Samsung Electronics HM121HI 120GB         | 1         | 6      | 1.89%   |
| Samsung Electronics HD161HJ 160GB         | 1         | 1      | 1.89%   |
| Plextor PX-128M6M 128GB SSD               | 1         | 1      | 1.89%   |
| NGFF 2280 512GB SSD                       | 1         | 1      | 1.89%   |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.89%   |
| Maxtor 6L200M0 208GB                      | 1         | 1      | 1.89%   |
| Intel SSDSC2KW512G8 512GB                 | 1         | 1      | 1.89%   |
| Intel SSDSA2M080G2LE 80GB                 | 1         | 1      | 1.89%   |
| Hitachi HTS722080K9SA00 80GB              | 1         | 1      | 1.89%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 33.33%  |
| WDC                 | 11        | 14     | 21.57%  |
| Toshiba             | 4         | 4      | 7.84%   |
| Hitachi             | 4         | 4      | 7.84%   |
| Samsung Electronics | 2         | 7      | 3.92%   |
| Intel               | 2         | 2      | 3.92%   |
| Apacer              | 2         | 2      | 3.92%   |
| Transcend           | 1         | 1      | 1.96%   |
| Plextor             | 1         | 1      | 1.96%   |
| NGFF                | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| Maxtor              | 1         | 1      | 1.96%   |
| HGST                | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 41.46%  |
| WDC                 | 10        | 13     | 24.39%  |
| Toshiba             | 4         | 4      | 9.76%   |
| Hitachi             | 4         | 4      | 9.76%   |
| Samsung Electronics | 2         | 7      | 4.88%   |
| Maxtor              | 1         | 1      | 2.44%   |
| HGST                | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 50     | 80%     |
| SSD  | 10        | 10     | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB       | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1         | 1      | 33.33%  |
| HGST HTS725025A7 250GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 156       | 240    | 48.9%   |
| Works    | 110       | 165    | 34.48%  |
| Malfunc  | 50        | 60     | 15.67%  |
| Failed   | 3         | 3      | 0.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 189       | 61.56%  |
| AMD                              | 52        | 16.94%  |
| Samsung Electronics              | 12        | 3.91%   |
| Nvidia                           | 7         | 2.28%   |
| Micron/Crucial Technology        | 7         | 2.28%   |
| SanDisk                          | 6         | 1.95%   |
| ASMedia Technology               | 5         | 1.63%   |
| JMicron Technology               | 4         | 1.3%    |
| SK hynix                         | 3         | 0.98%   |
| Micron Technology                | 3         | 0.98%   |
| Kingston Technology Company      | 3         | 0.98%   |
| VIA Technologies                 | 2         | 0.65%   |
| Union Memory (Shenzhen)          | 2         | 0.65%   |
| Silicon Motion                   | 2         | 0.65%   |
| Marvell Technology Group         | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Silicon Image                    | 1         | 0.33%   |
| Seagate Technology               | 1         | 0.33%   |
| Phison Electronics               | 1         | 0.33%   |
| LSI Logic / Symbios Logic        | 1         | 0.33%   |
| KIOXIA                           | 1         | 0.33%   |
| Broadcom / LSI                   | 1         | 0.33%   |
| ADATA Technology                 | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 33        | 8.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 6.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 14        | 3.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 13        | 3.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 13        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 3.24%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 2.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 10        | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 2.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 9         | 2.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 2.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 2.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 1.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 6         | 1.62%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 1.35%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5         | 1.35%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 4         | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.08%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.08%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 4         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 4         | 1.08%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.81%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 3         | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.81%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2         | 0.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.54%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.54%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.54%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 209       | 65.52%  |
| IDE  | 56        | 17.55%  |
| NVMe | 40        | 12.54%  |
| RAID | 13        | 4.08%   |
| SAS  | 1         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 233       | 78.19%  |
| AMD    | 61        | 20.47%  |
| ARM    | 4         | 1.34%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 8         | 2.68%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 6         | 2.01%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz       | 6         | 2.01%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 5         | 1.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 4         | 1.34%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 4         | 1.34%   |
| ARM Processor                           | 4         | 1.34%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 3         | 1.01%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 3         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 1.01%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 3         | 1.01%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 3         | 1.01%   |
| Intel Celeron CPU N2830 @ 2.16GHz       | 3         | 1.01%   |
| Intel Atom CPU N450 @ 1.66GHz           | 3         | 1.01%   |
| Intel Atom CPU D525 @ 1.80GHz           | 3         | 1.01%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.01%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz  | 2         | 0.67%   |
| Intel Pentium D CPU 2.80GHz             | 2         | 0.67%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.67%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 2         | 0.67%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 2         | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 0.67%   |
| Intel Core i5-9300HF CPU @ 2.40GHz      | 2         | 0.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 0.67%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 2         | 0.67%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 2         | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 2         | 0.67%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 2         | 0.67%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 0.67%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 2         | 0.67%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 0.67%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 2         | 0.67%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz    | 2         | 0.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 0.67%   |
| Intel Celeron N5105 @ 2.00GHz           | 2         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 51        | 17.11%  |
| Intel Celeron           | 46        | 15.44%  |
| Intel Atom              | 31        | 10.4%   |
| Intel Core 2 Duo        | 26        | 8.72%   |
| Intel Core i7           | 23        | 7.72%   |
| Intel Core i3           | 19        | 6.38%   |
| Other                   | 9         | 3.02%   |
| Intel Pentium           | 9         | 3.02%   |
| AMD Ryzen 7             | 9         | 3.02%   |
| AMD Ryzen 5             | 7         | 2.35%   |
| Intel Pentium Dual      | 5         | 1.68%   |
| AMD A6                  | 5         | 1.68%   |
| Intel Xeon              | 4         | 1.34%   |
| Intel Pentium Dual-Core | 4         | 1.34%   |
| Intel Core 2 Quad       | 4         | 1.34%   |
| AMD Ryzen 9             | 4         | 1.34%   |
| AMD FX                  | 3         | 1.01%   |
| AMD E2                  | 3         | 1.01%   |
| AMD E1                  | 3         | 1.01%   |
| AMD E                   | 3         | 1.01%   |
| AMD Athlon 64 X2        | 3         | 1.01%   |
| AMD A8                  | 3         | 1.01%   |
| AMD A10                 | 3         | 1.01%   |
| Intel Pentium D         | 2         | 0.67%   |
| Intel Core 2            | 2         | 0.67%   |
| AMD Phenom II X4        | 2         | 0.67%   |
| AMD Athlon              | 2         | 0.67%   |
| Intel Core m3           | 1         | 0.34%   |
| Intel Core i9           | 1         | 0.34%   |
| Intel Celeron Dual-Core | 1         | 0.34%   |
| AMD Ryzen 7 PRO         | 1         | 0.34%   |
| AMD Ryzen 5 PRO         | 1         | 0.34%   |
| AMD Phenom II X6        | 1         | 0.34%   |
| AMD GX                  | 1         | 0.34%   |
| AMD G                   | 1         | 0.34%   |
| AMD C-60                | 1         | 0.34%   |
| AMD Athlon II X3        | 1         | 0.34%   |
| AMD Athlon II X2        | 1         | 0.34%   |
| AMD Athlon II           | 1         | 0.34%   |
| AMD A4                  | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 166       | 55.7%   |
| 4       | 89        | 29.87%  |
| 8       | 12        | 4.03%   |
| 6       | 11        | 3.69%   |
| 1       | 10        | 3.36%   |
| 3       | 3         | 1.01%   |
| Unknown | 3         | 1.01%   |
| 10      | 2         | 0.67%   |
| 16      | 1         | 0.34%   |
| 12      | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 295       | 98.99%  |
| Unknown | 3         | 1.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 163       | 54.7%   |
| 2       | 132       | 44.3%   |
| Unknown | 3         | 1.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 297       | 99.66%  |
| 64-bit         | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 39.6%   |
| 0x306a9    | 16        | 5.28%   |
| 0x206a7    | 13        | 4.29%   |
| 0x406c4    | 12        | 3.96%   |
| 0x1067a    | 11        | 3.63%   |
| 0x406c3    | 8         | 2.64%   |
| 0x706a8    | 6         | 1.98%   |
| 0x6fd      | 5         | 1.65%   |
| 0x30678    | 5         | 1.65%   |
| 0x906c0    | 4         | 1.32%   |
| 0x806ec    | 4         | 1.32%   |
| 0x706e5    | 4         | 1.32%   |
| 0x40651    | 4         | 1.32%   |
| 0x306c3    | 4         | 1.32%   |
| 0x20655    | 4         | 1.32%   |
| 0x106ca    | 4         | 1.32%   |
| 0x0a50000c | 4         | 1.32%   |
| 0x0700010f | 4         | 1.32%   |
| 0x05000119 | 4         | 1.32%   |
| 0x906ea    | 3         | 0.99%   |
| 0x806ea    | 3         | 0.99%   |
| 0x806c1    | 3         | 0.99%   |
| 0x706a1    | 3         | 0.99%   |
| 0x6fb      | 3         | 0.99%   |
| 0x506c9    | 3         | 0.99%   |
| 0x406e3    | 3         | 0.99%   |
| 0x06006705 | 3         | 0.99%   |
| 0x06001119 | 3         | 0.99%   |
| 0x806e9    | 2         | 0.66%   |
| 0x506e3    | 2         | 0.66%   |
| 0x30679    | 2         | 0.66%   |
| 0x10676    | 2         | 0.66%   |
| 0x0a50000d | 2         | 0.66%   |
| 0x0a50000b | 2         | 0.66%   |
| 0x06003106 | 2         | 0.66%   |
| 0x010000db | 2         | 0.66%   |
| 0xa0653    | 1         | 0.33%   |
| 0x906ed    | 1         | 0.33%   |
| 0x906a4    | 1         | 0.33%   |
| 0x806eb    | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 44        | 14.77%  |
| Penryn           | 25        | 8.39%   |
| IvyBridge        | 24        | 8.05%   |
| SandyBridge      | 21        | 7.05%   |
| Core             | 19        | 6.38%   |
| Haswell          | 17        | 5.7%    |
| KabyLake         | 16        | 5.37%   |
| Goldmont plus    | 13        | 4.36%   |
| Zen 3            | 11        | 3.69%   |
| Westmere         | 11        | 3.69%   |
| Bonnell          | 9         | 3.02%   |
| Unknown          | 8         | 2.68%   |
| Skylake          | 7         | 2.35%   |
| Piledriver       | 7         | 2.35%   |
| K10              | 6         | 2.01%   |
| Jaguar           | 5         | 1.68%   |
| Goldmont         | 5         | 1.68%   |
| Excavator        | 5         | 1.68%   |
| Bobcat           | 5         | 1.68%   |
| Tremont          | 4         | 1.34%   |
| K8 Hammer        | 4         | 1.34%   |
| IceLake          | 4         | 1.34%   |
| Broadwell        | 4         | 1.34%   |
| Zen+             | 3         | 1.01%   |
| Zen 2            | 3         | 1.01%   |
| Zen              | 3         | 1.01%   |
| TigerLake        | 3         | 1.01%   |
| Steamroller      | 2         | 0.67%   |
| NetBurst         | 2         | 0.67%   |
| Nehalem          | 2         | 0.67%   |
| CometLake        | 2         | 0.67%   |
| Puma             | 1         | 0.34%   |
| K10 Llano        | 1         | 0.34%   |
| Bulldozer        | 1         | 0.34%   |
| Alderlake Hybrid | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 192       | 59.08%  |
| AMD                        | 73        | 22.46%  |
| Nvidia                     | 59        | 18.15%  |
| Matrox Electronics Systems | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 28        | 8.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 5.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 5.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 4.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 3.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 2.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 2.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 2.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.74%   |
| Intel HD Graphics 500                                                                    | 5         | 1.45%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.45%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.16%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 1.16%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.16%   |
| Nvidia GT218 [ION]                                                                       | 3         | 0.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.87%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.87%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.87%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.87%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.87%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.58%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.58%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.58%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.58%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.58%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.58%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 162       | 54.36%  |
| 1 x AMD            | 52        | 17.45%  |
| 1 x Nvidia         | 39        | 13.09%  |
| Intel + Nvidia     | 15        | 5.03%   |
| 2 x AMD            | 8         | 2.68%   |
| Intel + AMD        | 8         | 2.68%   |
| Other              | 7         | 2.35%   |
| AMD + Nvidia       | 4         | 1.34%   |
| 1 x Matrox         | 1         | 0.34%   |
| Intel + 2 x Nvidia | 1         | 0.34%   |
| Intel + 2 x AMD    | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 267       | 89.6%   |
| Proprietary | 18        | 6.04%   |
| Unknown     | 13        | 4.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 228       | 76%     |
| 0.01-0.5   | 29        | 9.67%   |
| 1.01-2.0   | 15        | 5%      |
| 0.51-1.0   | 12        | 4%      |
| 7.01-8.0   | 5         | 1.67%   |
| 3.01-4.0   | 4         | 1.33%   |
| 2.01-3.0   | 3         | 1%      |
| 8.01-16.0  | 3         | 1%      |
| 5.01-6.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 40        | 14.04%  |
| Samsung Electronics     | 34        | 11.93%  |
| LG Display              | 34        | 11.93%  |
| BOE                     | 27        | 9.47%   |
| Chimei Innolux          | 23        | 8.07%   |
| Hewlett-Packard         | 11        | 3.86%   |
| Dell                    | 11        | 3.86%   |
| Goldstar                | 10        | 3.51%   |
| Apple                   | 10        | 3.51%   |
| Acer                    | 8         | 2.81%   |
| Philips                 | 6         | 2.11%   |
| Lenovo                  | 6         | 2.11%   |
| Sharp                   | 5         | 1.75%   |
| CPT                     | 5         | 1.75%   |
| Chi Mei Optoelectronics | 4         | 1.4%    |
| Ancor Communications    | 4         | 1.4%    |
| Toshiba                 | 3         | 1.05%   |
| Iiyama                  | 3         | 1.05%   |
| Eizo                    | 3         | 1.05%   |
| BenQ                    | 3         | 1.05%   |
| ViewSonic               | 2         | 0.7%    |
| Sony                    | 2         | 0.7%    |
| LG Philips              | 2         | 0.7%    |
| InfoVision              | 2         | 0.7%    |
| HannStar                | 2         | 0.7%    |
| AOC                     | 2         | 0.7%    |
| Westinghouse            | 1         | 0.35%   |
| Vizio                   | 1         | 0.35%   |
| VHT                     | 1         | 0.35%   |
| Unknown (ADA)           | 1         | 0.35%   |
| Unknown                 | 1         | 0.35%   |
| SNC                     | 1         | 0.35%   |
| Sampo                   | 1         | 0.35%   |
| RTK                     | 1         | 0.35%   |
| Positivo                | 1         | 0.35%   |
| MSI                     | 1         | 0.35%   |
| LLL                     | 1         | 0.35%   |
| LG Electronics          | 1         | 0.35%   |
| JVC                     | 1         | 0.35%   |
| Jean                    | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 5         | 1.74%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch          | 3         | 1.04%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 3         | 1.04%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 3         | 1.04%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 2         | 0.69%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 2         | 0.69%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch              | 2         | 0.69%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 2         | 0.69%   |
| Dell S2721HSX DEL4202 1920x1080 598x336mm 27.0-inch                  | 2         | 0.69%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                 | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 2         | 0.69%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                 | 2         | 0.69%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                 | 2         | 0.69%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch        | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch        | 2         | 0.69%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 2         | 0.69%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 2         | 0.69%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1         | 0.35%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                | 1         | 0.35%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1         | 0.35%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch        | 1         | 0.35%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1         | 0.35%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1         | 0.35%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch        | 1         | 0.35%   |
| Toshiba TV TSB0108 1360x768 930x523mm 42.0-inch                      | 1         | 0.35%   |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch             | 1         | 0.35%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch             | 1         | 0.35%   |
| Sony TV SNY9C01 1360x768                                             | 1         | 0.35%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1         | 0.35%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1         | 0.35%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch              | 1         | 0.35%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch              | 1         | 0.35%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch              | 1         | 0.35%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch              | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 98        | 34.88%  |
| 1920x1080 (FHD)    | 80        | 28.47%  |
| 1280x800 (WXGA)    | 24        | 8.54%   |
| 1600x900 (HD+)     | 19        | 6.76%   |
| 1680x1050 (WSXGA+) | 11        | 3.91%   |
| 1280x1024 (SXGA)   | 9         | 3.2%    |
| 1440x900 (WXGA+)   | 8         | 2.85%   |
| 2560x1440 (QHD)    | 7         | 2.49%   |
| 3840x2160 (4K)     | 5         | 1.78%   |
| 1360x768           | 4         | 1.42%   |
| 3200x1800 (QHD+)   | 2         | 0.71%   |
| 2160x1440          | 2         | 0.71%   |
| 1024x768 (XGA)     | 2         | 0.71%   |
| 800x600            | 1         | 0.36%   |
| 3000x2000          | 1         | 0.36%   |
| 2560x1600          | 1         | 0.36%   |
| 2560x1080          | 1         | 0.36%   |
| 1920x540           | 1         | 0.36%   |
| 1920x1200 (WUXGA)  | 1         | 0.36%   |
| 1528x1222          | 1         | 0.36%   |
| 1280x768           | 1         | 0.36%   |
| 1280x720 (HD)      | 1         | 0.36%   |
| 1024x600           | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 69        | 24.38%  |
| 14      | 33        | 11.66%  |
| 13      | 30        | 10.6%   |
| 11      | 18        | 6.36%   |
| 17      | 17        | 6.01%   |
| 27      | 14        | 4.95%   |
| 24      | 12        | 4.24%   |
| 23      | 11        | 3.89%   |
| 12      | 11        | 3.89%   |
| 19      | 10        | 3.53%   |
| 18      | 10        | 3.53%   |
| 22      | 9         | 3.18%   |
| 21      | 9         | 3.18%   |
| Unknown | 8         | 2.83%   |
| 20      | 5         | 1.77%   |
| 10      | 3         | 1.06%   |
| 72      | 2         | 0.71%   |
| 84      | 1         | 0.35%   |
| 52      | 1         | 0.35%   |
| 49      | 1         | 0.35%   |
| 47      | 1         | 0.35%   |
| 44      | 1         | 0.35%   |
| 43      | 1         | 0.35%   |
| 34      | 1         | 0.35%   |
| 28      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |
| 9       | 1         | 0.35%   |
| 8       | 1         | 0.35%   |
| 7       | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 117       | 41.34%  |
| 201-300     | 50        | 17.67%  |
| 401-500     | 39        | 13.78%  |
| 501-600     | 36        | 12.72%  |
| 351-400     | 19        | 6.71%   |
| Unknown     | 8         | 2.83%   |
| 1501-2000   | 3         | 1.06%   |
| 101-200     | 3         | 1.06%   |
| 1001-1500   | 3         | 1.06%   |
| 601-700     | 2         | 0.71%   |
| 901-1000    | 2         | 0.71%   |
| 701-800     | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 200       | 74.63%  |
| 16/10   | 43        | 16.04%  |
| 5/4     | 7         | 2.61%   |
| 3/2     | 6         | 2.24%   |
| Unknown | 6         | 2.24%   |
| 4/3     | 5         | 1.87%   |
| 21/9    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 68        | 24.11%  |
| 81-90          | 55        | 19.5%   |
| 201-250        | 34        | 12.06%  |
| 151-200        | 19        | 6.74%   |
| 51-60          | 18        | 6.38%   |
| 301-350        | 14        | 4.96%   |
| 121-130        | 13        | 4.61%   |
| 61-70          | 11        | 3.9%    |
| 141-150        | 11        | 3.9%    |
| 71-80          | 8         | 2.84%   |
| Unknown        | 8         | 2.84%   |
| More than 1000 | 5         | 1.77%   |
| 251-300        | 5         | 1.77%   |
| 41-50          | 4         | 1.42%   |
| 501-1000       | 4         | 1.42%   |
| 1-40           | 2         | 0.71%   |
| 131-140        | 2         | 0.71%   |
| 111-120        | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 104       | 37.41%  |
| 51-100        | 79        | 28.42%  |
| 121-160       | 61        | 21.94%  |
| 161-240       | 16        | 5.76%   |
| 1-50          | 8         | 2.88%   |
| Unknown       | 8         | 2.88%   |
| More than 240 | 2         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 262       | 87.63%  |
| 2     | 24        | 8.03%   |
| 0     | 12        | 4.01%   |
| 3     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 152       | 34.94%  |
| Intel                             | 106       | 24.37%  |
| Qualcomm Atheros                  | 61        | 14.02%  |
| Broadcom                          | 29        | 6.67%   |
| Marvell Technology Group          | 12        | 2.76%   |
| TP-Link                           | 7         | 1.61%   |
| Samsung Electronics               | 6         | 1.38%   |
| Ralink                            | 6         | 1.38%   |
| Qualcomm Atheros Communications   | 5         | 1.15%   |
| Nvidia                            | 5         | 1.15%   |
| MediaTek                          | 5         | 1.15%   |
| Broadcom Limited                  | 5         | 1.15%   |
| Xiaomi                            | 4         | 0.92%   |
| Ralink Technology                 | 4         | 0.92%   |
| NetGear                           | 4         | 0.92%   |
| ASIX Electronics                  | 3         | 0.69%   |
| VIA Technologies                  | 2         | 0.46%   |
| Qualcomm                          | 2         | 0.46%   |
| ICS Advent                        | 2         | 0.46%   |
| Belkin Components                 | 2         | 0.46%   |
| ASUSTek Computer                  | 2         | 0.46%   |
| Trident Microsystems              | 1         | 0.23%   |
| Texas Instruments                 | 1         | 0.23%   |
| Sierra Wireless                   | 1         | 0.23%   |
| OPPO Electronics                  | 1         | 0.23%   |
| Motorola PCS                      | 1         | 0.23%   |
| Microsoft                         | 1         | 0.23%   |
| JMicron Technology                | 1         | 0.23%   |
| Ericsson Business Mobile Networks | 1         | 0.23%   |
| Dresden Elektronik                | 1         | 0.23%   |
| Dell                              | 1         | 0.23%   |
| Accton Technology                 | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 18.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 4.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.96%   |
| Intel Wireless 7265                                               | 10        | 1.96%   |
| Intel Wireless 7260                                               | 10        | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 0.98%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.78%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.78%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.59%   |
| NetGear A6210                                                     | 3         | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.59%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.59%   |
| Intel Wireless 8260                                               | 3         | 0.59%   |
| Intel Wireless 3160                                               | 3         | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 83        | 34.02%  |
| Qualcomm Atheros                  | 51        | 20.9%   |
| Realtek Semiconductor             | 49        | 20.08%  |
| Broadcom                          | 20        | 8.2%    |
| TP-Link                           | 6         | 2.46%   |
| Ralink                            | 6         | 2.46%   |
| Qualcomm Atheros Communications   | 5         | 2.05%   |
| MediaTek                          | 5         | 2.05%   |
| Ralink Technology                 | 4         | 1.64%   |
| NetGear                           | 3         | 1.23%   |
| Broadcom Limited                  | 3         | 1.23%   |
| Belkin Components                 | 2         | 0.82%   |
| ASUSTek Computer                  | 2         | 0.82%   |
| Sierra Wireless                   | 1         | 0.41%   |
| Microsoft                         | 1         | 0.41%   |
| Marvell Technology Group          | 1         | 0.41%   |
| Ericsson Business Mobile Networks | 1         | 0.41%   |
| Dell                              | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 4.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 4.07%   |
| Intel Wireless 7265                                            | 10        | 4.07%   |
| Intel Wireless 7260                                            | 10        | 4.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 3.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 2.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 2.03%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 1.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.63%   |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 1.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.63%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 1.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 1.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.63%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.22%   |
| NetGear A6210                                                  | 3         | 1.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.22%   |
| Intel Wireless 8260                                            | 3         | 1.22%   |
| Intel Wireless 3160                                            | 3         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.22%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.22%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.22%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 133       | 51.35%  |
| Intel                    | 49        | 18.92%  |
| Qualcomm Atheros         | 20        | 7.72%   |
| Broadcom                 | 15        | 5.79%   |
| Marvell Technology Group | 11        | 4.25%   |
| Nvidia                   | 5         | 1.93%   |
| Xiaomi                   | 4         | 1.54%   |
| Samsung Electronics      | 4         | 1.54%   |
| ASIX Electronics         | 3         | 1.16%   |
| VIA Technologies         | 2         | 0.77%   |
| Qualcomm                 | 2         | 0.77%   |
| ICS Advent               | 2         | 0.77%   |
| Broadcom Limited         | 2         | 0.77%   |
| Trident Microsystems     | 1         | 0.39%   |
| TP-Link                  | 1         | 0.39%   |
| OPPO Electronics         | 1         | 0.39%   |
| NetGear                  | 1         | 0.39%   |
| Motorola PCS             | 1         | 0.39%   |
| JMicron Technology       | 1         | 0.39%   |
| Accton Technology        | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 36.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 9.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 4.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 2.68%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 1.53%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 1.15%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.15%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 1.15%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.15%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.15%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.77%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.77%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.77%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2         | 0.77%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.77%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.38%   |
| Trident Microsystems 4DWave DX                                    | 1         | 0.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.38%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.38%   |
| Qualcomm SM6150-IDP _SN:488AC473                                  | 1         | 0.38%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 240       | 51.06%  |
| WiFi     | 226       | 48.09%  |
| Modem    | 4         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 57.14%  |
| Ethernet | 126       | 42.86%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 154       | 51.68%  |
| 1     | 110       | 36.91%  |
| 0     | 29        | 9.73%   |
| 3     | 4         | 1.34%   |
| 4     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 224       | 74.67%  |
| Yes  | 76        | 25.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 35.4%   |
| Realtek Semiconductor           | 20        | 12.42%  |
| Qualcomm Atheros Communications | 17        | 10.56%  |
| Broadcom                        | 11        | 6.83%   |
| Apple                           | 9         | 5.59%   |
| Foxconn / Hon Hai               | 7         | 4.35%   |
| Cambridge Silicon Radio         | 7         | 4.35%   |
| Lite-On Technology              | 6         | 3.73%   |
| IMC Networks                    | 5         | 3.11%   |
| Ralink                          | 4         | 2.48%   |
| Hewlett-Packard                 | 4         | 2.48%   |
| Dell                            | 4         | 2.48%   |
| Toshiba                         | 2         | 1.24%   |
| MediaTek                        | 2         | 1.24%   |
| TP-Link                         | 1         | 0.62%   |
| Syntek                          | 1         | 0.62%   |
| Marvell Semiconductor           | 1         | 0.62%   |
| Logitech                        | 1         | 0.62%   |
| ASUSTek Computer                | 1         | 0.62%   |
| Alps Electric                   | 1         | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 18.52%  |
| Realtek Bluetooth Radio                                                             | 12        | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 4.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 4.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 3.7%    |
| Intel AX201 Bluetooth                                                               | 5         | 3.09%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 3.09%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 2.47%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 2.47%   |
| Intel AX200 Bluetooth                                                               | 4         | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.85%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.85%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.85%   |
| Apple Bluetooth HCI                                                                 | 3         | 1.85%   |
| MediaTek Wireless_Device                                                            | 2         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.23%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.23%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.23%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.23%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.62%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.62%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.62%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.62%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.62%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.62%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.62%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.62%   |
| Lite-On Wireless_Device                                                             | 1         | 0.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.62%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.62%   |
| Lite-On BCM20702A0                                                                  | 1         | 0.62%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.62%   |
| Intel Bluetooth Device                                                              | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 203       | 60.24%  |
| AMD                                          | 68        | 20.18%  |
| Nvidia                                       | 40        | 11.87%  |
| C-Media Electronics                          | 6         | 1.78%   |
| VIA Technologies                             | 3         | 0.89%   |
| GN Netcom                                    | 2         | 0.59%   |
| ASUSTek Computer                             | 2         | 0.59%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.3%    |
| Texas Instruments                            | 1         | 0.3%    |
| Sony                                         | 1         | 0.3%    |
| Razer USA                                    | 1         | 0.3%    |
| Plantronics                                  | 1         | 0.3%    |
| MosArt Semiconductor                         | 1         | 0.3%    |
| Micro Star International                     | 1         | 0.3%    |
| Logitech                                     | 1         | 0.3%    |
| JMTek                                        | 1         | 0.3%    |
| Focusrite-Novation                           | 1         | 0.3%    |
| Ensoniq                                      | 1         | 0.3%    |
| EGO SYStems                                  | 1         | 0.3%    |
| Creative Labs                                | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 7.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 22        | 5.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 3.51%   |
| AMD FCH Azalia Controller                                                                         | 14        | 3.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 3.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 3.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 3.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 3.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 2.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.51%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 2.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.26%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.26%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.25%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 1.25%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1%      |
| Intel Jasper Lake HD Audio                                                                        | 4         | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1%      |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 1%      |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 1%      |
| AMD High Definition Audio Controller                                                              | 4         | 1%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.75%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.75%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 40        | 18.43%  |
| Samsung Electronics | 40        | 18.43%  |
| Unknown             | 32        | 14.75%  |
| Micron Technology   | 26        | 11.98%  |
| Kingston            | 11        | 5.07%   |
| Corsair             | 8         | 3.69%   |
| Nanya Technology    | 7         | 3.23%   |
| Elpida              | 7         | 3.23%   |
| Unknown             | 7         | 3.23%   |
| Unknown (ABCD)      | 6         | 2.76%   |
| G.Skill             | 6         | 2.76%   |
| Crucial             | 6         | 2.76%   |
| Smart               | 3         | 1.38%   |
| Ramaxel Technology  | 3         | 1.38%   |
| A-DATA Technology   | 3         | 1.38%   |
| Patriot             | 2         | 0.92%   |
| Transcend           | 1         | 0.46%   |
| Toshiba             | 1         | 0.46%   |
| Novatech            | 1         | 0.46%   |
| Kllisre             | 1         | 0.46%   |
| Kingmax             | 1         | 0.46%   |
| HMD                 | 1         | 0.46%   |
| GOODRAM             | 1         | 0.46%   |
| fef5                | 1         | 0.46%   |
| Apacer              | 1         | 0.46%   |
| AMD                 | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 7         | 2.99%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 3         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.28%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 1.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.28%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 3         | 1.28%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 2         | 0.85%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.85%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 2         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 2         | 0.85%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 0.85%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 0.85%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 2         | 0.85%   |
| Elpida RAM EBJ20UF8BDU0-GN-F 2GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s         | 2         | 0.85%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.43%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 95        | 48.47%  |
| DDR4    | 53        | 27.04%  |
| DDR2    | 18        | 9.18%   |
| LPDDR4  | 13        | 6.63%   |
| SDRAM   | 6         | 3.06%   |
| Unknown | 5         | 2.55%   |
| LPDDR3  | 3         | 1.53%   |
| DDR5    | 2         | 1.02%   |
| LPDDR5  | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 129       | 66.49%  |
| DIMM         | 48        | 24.74%  |
| Row Of Chips | 13        | 6.7%    |
| Unknown      | 4         | 2.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 63        | 29.44%  |
| 8192  | 60        | 28.04%  |
| 2048  | 60        | 28.04%  |
| 16384 | 15        | 7.01%   |
| 1024  | 11        | 5.14%   |
| 32768 | 4         | 1.87%   |
| 512   | 1         | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 63        | 30.73%  |
| 3200    | 24        | 11.71%  |
| 1333    | 16        | 7.8%    |
| 2400    | 13        | 6.34%   |
| 2667    | 9         | 4.39%   |
| 1334    | 9         | 4.39%   |
| 667     | 9         | 4.39%   |
| 1066    | 8         | 3.9%    |
| 800     | 6         | 2.93%   |
| Unknown | 6         | 2.93%   |
| 1866    | 5         | 2.44%   |
| 3266    | 4         | 1.95%   |
| 2133    | 4         | 1.95%   |
| 1067    | 4         | 1.95%   |
| 4267    | 3         | 1.46%   |
| 4800    | 2         | 0.98%   |
| 3400    | 2         | 0.98%   |
| 2800    | 2         | 0.98%   |
| 2048    | 2         | 0.98%   |
| 1867    | 2         | 0.98%   |
| 975     | 2         | 0.98%   |
| 5500    | 1         | 0.49%   |
| 4199    | 1         | 0.49%   |
| 3933    | 1         | 0.49%   |
| 3733    | 1         | 0.49%   |
| 3666    | 1         | 0.49%   |
| 3534    | 1         | 0.49%   |
| 3066    | 1         | 0.49%   |
| 2666    | 1         | 0.49%   |
| 533     | 1         | 0.49%   |
| 333     | 1         | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 50%     |
| Samsung Electronics | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 16.67%  |
| HP LaserJet P1102       | 1         | 16.67%  |
| Canon PIXMA MP250       | 1         | 16.67%  |
| Canon MF3110            | 1         | 16.67%  |
| Canon CanoScan LiDE 300 | 1         | 16.67%  |
| Brother DCP-7055W       | 1         | 16.67%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 40        | 23.81%  |
| Realtek Semiconductor                  | 17        | 10.12%  |
| Microdia                               | 17        | 10.12%  |
| Sunplus Innovation Technology          | 11        | 6.55%   |
| Syntek                                 | 8         | 4.76%   |
| Apple                                  | 8         | 4.76%   |
| Logitech                               | 6         | 3.57%   |
| IMC Networks                           | 6         | 3.57%   |
| Quanta                                 | 5         | 2.98%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.98%   |
| Alcor Micro                            | 5         | 2.98%   |
| Acer                                   | 5         | 2.98%   |
| Suyin                                  | 4         | 2.38%   |
| Lite-On Technology                     | 4         | 2.38%   |
| Lenovo                                 | 3         | 1.79%   |
| Bison Electronics                      | 3         | 1.79%   |
| ALi                                    | 3         | 1.79%   |
| Z-Star Microelectronics                | 2         | 1.19%   |
| Silicon Motion                         | 2         | 1.19%   |
| icSpring                               | 2         | 1.19%   |
| Y Media                                | 1         | 0.6%    |
| WaveRider Communications               | 1         | 0.6%    |
| USB Camera CS                          | 1         | 0.6%    |
| SunplusIT                              | 1         | 0.6%    |
| Ricoh                                  | 1         | 0.6%    |
| Pixart Imaging                         | 1         | 0.6%    |
| Microsoft                              | 1         | 0.6%    |
| Generalplus Technology                 | 1         | 0.6%    |
| GEMBIRD                                | 1         | 0.6%    |
| Cubeternet                             | 1         | 0.6%    |
| BKX-Usb2.0 2MP Camera                  | 1         | 0.6%    |
| AVerMedia Technologies                 | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Chicony Integrated Camera         | 10        | 5.92%   |
| Alcor Micro USB 2.0 Camera        | 5         | 2.96%   |
| Sunplus HD WebCam                 | 4         | 2.37%   |
| Microdia Integrated Webcam        | 4         | 2.37%   |
| Chicony HP Truevision HD camera   | 4         | 2.37%   |
| Chicony HD WebCam                 | 4         | 2.37%   |
| Realtek Integrated_Webcam_HD      | 3         | 1.78%   |
| Microdia Integrated_Webcam_HD     | 3         | 1.78%   |
| Logitech Webcam C270              | 3         | 1.78%   |
| Apple FaceTime HD Camera          | 3         | 1.78%   |
| Acer Integrated Camera            | 3         | 1.78%   |
| Z-Star Webcam                     | 2         | 1.18%   |
| Syntek Lenovo EasyCamera          | 2         | 1.18%   |
| Syntek Integrated Camera          | 2         | 1.18%   |
| Sunplus Integrated_Webcam_HD      | 2         | 1.18%   |
| Realtek USB Camera                | 2         | 1.18%   |
| Realtek Lenovo EasyCamera         | 2         | 1.18%   |
| Realtek Integrated Webcam HD      | 2         | 1.18%   |
| Realtek HP Truevision HD          | 2         | 1.18%   |
| Microdia Lenovo EasyCamera        | 2         | 1.18%   |
| Microdia HP Webcam-50             | 2         | 1.18%   |
| Lenovo Integrated Webcam          | 2         | 1.18%   |
| IMC Networks USB2.0 HD UVC WebCam | 2         | 1.18%   |
| icSpring camera                   | 2         | 1.18%   |
| Chicony VGA Webcam                | 2         | 1.18%   |
| Chicony USB 2.0 camera            | 2         | 1.18%   |
| Chicony HP Truevision HD          | 2         | 1.18%   |
| Chicony FJ Camera                 | 2         | 1.18%   |
| Chicony EasyCamera                | 2         | 1.18%   |
| Chicony 2.0M UVC Webcam / CNF7129 | 2         | 1.18%   |
| Apple Built-in iSight             | 2         | 1.18%   |
| ALi WebCam                        | 2         | 1.18%   |
| Acer Lenovo EasyCamera            | 2         | 1.18%   |
| Y Media USB Camera                | 1         | 0.59%   |
| WaveRider USB 2.0 Camera          | 1         | 0.59%   |
| USB Camera CS USB Camera CS       | 1         | 0.59%   |
| Syntek USB2.0 Camera              | 1         | 0.59%   |
| Syntek USB Camera Device          | 1         | 0.59%   |
| Syntek Sonix USB 2.0 Camera       | 1         | 0.59%   |
| Syntek HD WebCam                  | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 22.73%  |
| Upek                       | 5         | 22.73%  |
| AuthenTec                  | 4         | 18.18%  |
| Synaptics                  | 2         | 9.09%   |
| STMicroelectronics         | 2         | 9.09%   |
| Shenzhen Goodix Technology | 2         | 9.09%   |
| LighTuning Technology      | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 22.73%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.55%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.55%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.55%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.55%   |
| Synaptics WBDI                                         | 1         | 4.55%   |
| Synaptics UWP WBDI                                     | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.55%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.55%   |
| AuthenTec AES2810                                      | 1         | 4.55%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.55%   |
| AuthenTec AES1600                                      | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 46.15%  |
| Alcor Micro           | 3         | 23.08%  |
| O2 Micro              | 1         | 7.69%   |
| Lenovo                | 1         | 7.69%   |
| Gemalto (was Gemplus) | 1         | 7.69%   |
| Cherry                | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Broadcom 5880                                    | 3         | 23.08%  |
| Broadcom BCM5880 Secure Applications Processor   | 2         | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader              | 2         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader             | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader              | 1         | 7.69%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1         | 7.69%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC      | 1         | 7.69%   |
| Broadcom 58200                                   | 1         | 7.69%   |
| Alcor Micro Watchdata W 1981                     | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 233       | 77.93%  |
| 1     | 56        | 18.73%  |
| 2     | 8         | 2.68%   |
| 4     | 1         | 0.33%   |
| 3     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 27.27%  |
| Graphics card            | 14        | 18.18%  |
| Chipcard                 | 11        | 14.29%  |
| Net/wireless             | 8         | 10.39%  |
| Bluetooth                | 7         | 9.09%   |
| Camera                   | 6         | 7.79%   |
| Network                  | 2         | 2.6%    |
| Dvb card                 | 2         | 2.6%    |
| Unassigned class         | 1         | 1.3%    |
| Storage                  | 1         | 1.3%    |
| Sound                    | 1         | 1.3%    |
| Net/ethernet             | 1         | 1.3%    |
| Multimedia controller    | 1         | 1.3%    |
| Communication controller | 1         | 1.3%    |

