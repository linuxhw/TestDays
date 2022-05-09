Linux in New Zealand - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

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

Total: 366

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba   | Satellite C660              | [2b4d9cbd0c](https://linux-hardware.org/?probe=2b4d9cbd0c) | May 03, 2022 |
| Lenovo    | B50-30 20382                | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| Toshiba   | Satellite C660              | [c3bb583347](https://linux-hardware.org/?probe=c3bb583347) | Apr 24, 2022 |
| Lenovo    | B50-70 20384                | [35cf0f09e4](https://linux-hardware.org/?probe=35cf0f09e4) | Apr 22, 2022 |
| Dell      | XPS 13 9360                 | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell      | XPS 15 9510                 | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| Dell      | Inspiron 5415               | [5ad4aa0994](https://linux-hardware.org/?probe=5ad4aa0994) | Apr 13, 2022 |
| HP        | ProBook 650 G1              | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| Dell      | Latitude 7480               | [ccc8107d39](https://linux-hardware.org/?probe=ccc8107d39) | Apr 01, 2022 |
| Lenovo    | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung   | 530U3C/530U4C/532U3C        | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| eMachines | eM350                       | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20UDS... | [9b194b03b4](https://linux-hardware.org/?probe=9b194b03b4) | Mar 25, 2022 |
| HP        | Laptop 15-bs0xx             | [e12f0f1eed](https://linux-hardware.org/?probe=e12f0f1eed) | Mar 23, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| ASUSTek   | G75VX                       | [4673f4edd8](https://linux-hardware.org/?probe=4673f4edd8) | Mar 21, 2022 |
| HP        | EliteBook 8460p             | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Dell      | Inspiron 5770               | [fc12718113](https://linux-hardware.org/?probe=fc12718113) | Mar 13, 2022 |
| Dell      | Inspiron 5770               | [8a7c1daf70](https://linux-hardware.org/?probe=8a7c1daf70) | Mar 13, 2022 |
| Dell      | XPS 15 9550                 | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| Lenovo    | IdeaPad 3 14IML05 81WA      | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Acer      | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer      | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| HP        | Pavilion Laptop 15-cs3xx... | [96aa797713](https://linux-hardware.org/?probe=96aa797713) | Feb 21, 2022 |
| Toshiba   | Satellite Pro R50-C         | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| Dell      | Inspiron 5415               | [3324e66890](https://linux-hardware.org/?probe=3324e66890) | Feb 15, 2022 |
| Dell      | Inspiron 5415               | [c2bd021f7e](https://linux-hardware.org/?probe=c2bd021f7e) | Feb 13, 2022 |
| ASUSTek   | K55A                        | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| System76  | Lemur Pro                   | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| Acer      | Aspire ES1-411              | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo    | ThinkPad T470 20HES23B0U    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| ASUSTek   | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Acer      | Aspire A715-42G             | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| Lenovo    | ThinkPad P51 20HJS2JJ01     | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| Toshiba   | PORTEGE R930                | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| HP        | ProBook 450 G2              | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Star Labs | LabTop                      | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| HP        | Pavilion Laptop 15-cs0xx... | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| Apple     | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Acer      | Swift SF314-41              | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| ASUSTek   | UX303LAB                    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| Google    | Kip                         | [8c60d949d0](https://linux-hardware.org/?probe=8c60d949d0) | Dec 20, 2021 |
| Acer      | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer      | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Acer      | Aspire 4830T                | [205025f3c7](https://linux-hardware.org/?probe=205025f3c7) | Nov 27, 2021 |
| Acer      | Aspire 4830T                | [757863f7de](https://linux-hardware.org/?probe=757863f7de) | Nov 25, 2021 |
| Dell      | System XPS L702X            | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple     | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| HP        | Laptop 15-bs0xx             | [d33bc4ef7c](https://linux-hardware.org/?probe=d33bc4ef7c) | Nov 16, 2021 |
| HP        | Laptop 15-bs0xx             | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| Dell      | System XPS L702X            | [12957f0a7d](https://linux-hardware.org/?probe=12957f0a7d) | Nov 15, 2021 |
| Acer      | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| ASUSTek   | ASUS TUF Dash F15 FX516P... | [9fc484d01e](https://linux-hardware.org/?probe=9fc484d01e) | Nov 11, 2021 |
| ASUSTek   | ASUS TUF Dash F15 FX516P... | [edc363bc59](https://linux-hardware.org/?probe=edc363bc59) | Nov 11, 2021 |
| Timi      | A30                         | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| Lenovo    | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76  | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek   | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| Dell      | Vostro 14 5410              | [b6966ebc42](https://linux-hardware.org/?probe=b6966ebc42) | Oct 30, 2021 |
| Lenovo    | ThinkPad P1 Gen 3 20TJS0... | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| HP        | Spectre x2 Detachable       | [d20c059f3d](https://linux-hardware.org/?probe=d20c059f3d) | Oct 24, 2021 |
| ASUSTek   | ASUS EXPERTBOOK P2451FA_... | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| Dell      | System XPS L702X            | [f9932d7565](https://linux-hardware.org/?probe=f9932d7565) | Oct 18, 2021 |
| Dell      | Latitude 7490               | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| HP        | Pavilion tx2500             | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP        | Pavilion tx2500             | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Acer      | Aspire VN7-593G             | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| HP        | Pavilion g6                 | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer      | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer      | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| Dell      | System XPS L702X            | [7a3c6c76f8](https://linux-hardware.org/?probe=7a3c6c76f8) | Oct 03, 2021 |
| Acer      | Aspire 4830T                | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Toshiba   | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| HP        | EliteBook 2170p             | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP        | EliteBook 2170p             | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| MSI       | GE66 Raider 10SF            | [9d11ef435a](https://linux-hardware.org/?probe=9d11ef435a) | Sep 16, 2021 |
| Lenovo    | ThinkPad T460p 20FW0005A... | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| Acer      | TravelMate 5760             | [eb8b4b37a4](https://linux-hardware.org/?probe=eb8b4b37a4) | Sep 13, 2021 |
| Acer      | TravelMate 5760             | [a0376eeefc](https://linux-hardware.org/?probe=a0376eeefc) | Sep 13, 2021 |
| Dell      | XPS 15 9500                 | [83bf40cb1d](https://linux-hardware.org/?probe=83bf40cb1d) | Sep 12, 2021 |
| Dell      | XPS 15 9500                 | [65102530f5](https://linux-hardware.org/?probe=65102530f5) | Sep 12, 2021 |
| HP        | EliteBook 8560p             | [48828ad0d3](https://linux-hardware.org/?probe=48828ad0d3) | Sep 10, 2021 |
| Dell      | System XPS L702X            | [e0ff0245fb](https://linux-hardware.org/?probe=e0ff0245fb) | Sep 10, 2021 |
| Toshiba   | Satellite C50D-C            | [af1933f8ad](https://linux-hardware.org/?probe=af1933f8ad) | Sep 09, 2021 |
| Acer      | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Lenovo    | ThinkPad X1 Carbon 3rd 2... | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| Lenovo    | B50-30 20382                | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Medion    | P6815                       | [e3e586bafe](https://linux-hardware.org/?probe=e3e586bafe) | Aug 29, 2021 |
| Medion    | P6815                       | [46b6aaf8c5](https://linux-hardware.org/?probe=46b6aaf8c5) | Aug 29, 2021 |
| ASUSTek   | Strix GL703GM_GL703GM       | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| HP        | Pavilion dv6                | [c1ad958c3f](https://linux-hardware.org/?probe=c1ad958c3f) | Aug 28, 2021 |
| Lenovo    | B50-30 20382                | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| Sony      | VPCEB43FG                   | [4a81e892f0](https://linux-hardware.org/?probe=4a81e892f0) | Aug 26, 2021 |
| Dell      | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Lenovo    | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [efeb81eaea](https://linux-hardware.org/?probe=efeb81eaea) | Aug 21, 2021 |
| Dell      | XPS 15 9500                 | [1216df6214](https://linux-hardware.org/?probe=1216df6214) | Aug 19, 2021 |
| TWG       | E2017                       | [3f335e736c](https://linux-hardware.org/?probe=3f335e736c) | Aug 18, 2021 |
| Dell      | Latitude 7490               | [6ca174eba8](https://linux-hardware.org/?probe=6ca174eba8) | Aug 14, 2021 |
| Dell      | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| ASUSTek   | ROG Zephyrus G14 GA401QM... | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek   | ROG Zephyrus G14 GA401QM... | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Toshiba   | Satellite C50D-C            | [dda3acac30](https://linux-hardware.org/?probe=dda3acac30) | Aug 08, 2021 |
| Lenovo    | ThinkPad T460p 20FW0005A... | [bf942f5a10](https://linux-hardware.org/?probe=bf942f5a10) | Aug 05, 2021 |
| Samsung   | RC410/RC510/RC710           | [4e03a59c3f](https://linux-hardware.org/?probe=4e03a59c3f) | Aug 03, 2021 |
| Samsung   | RC410/RC510/RC710           | [37550654db](https://linux-hardware.org/?probe=37550654db) | Aug 03, 2021 |
| Lenovo    | V15-IIL 82C5                | [20007580cb](https://linux-hardware.org/?probe=20007580cb) | Aug 01, 2021 |
| Lenovo    | V15-IIL 82C5                | [359e3c40ca](https://linux-hardware.org/?probe=359e3c40ca) | Aug 01, 2021 |
| HP        | Pavilion Laptop 15-eh0xx... | [812ba32a31](https://linux-hardware.org/?probe=812ba32a31) | Aug 01, 2021 |
| HP        | Pavilion g6                 | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Lenovo    | ThinkPad T460 20FMS2FR00    | [cc238ca2aa](https://linux-hardware.org/?probe=cc238ca2aa) | Jul 30, 2021 |
| HP        | Spectre x2 Detachable       | [7b96d53aa9](https://linux-hardware.org/?probe=7b96d53aa9) | Jul 29, 2021 |
| Lenovo    | ThinkPad T460p 20FW0005A... | [2a54318c46](https://linux-hardware.org/?probe=2a54318c46) | Jul 27, 2021 |
| Samsung   | 3570R/370R/470R/450R/510... | [c499631e7e](https://linux-hardware.org/?probe=c499631e7e) | Jul 19, 2021 |
| HP        | Laptop 14s-dk0xxx           | [0acaedd30c](https://linux-hardware.org/?probe=0acaedd30c) | Jul 13, 2021 |
| HP        | Laptop 14s-dk0xxx           | [f655e1ca50](https://linux-hardware.org/?probe=f655e1ca50) | Jul 12, 2021 |
| eMachines | eM350                       | [5b174d8cab](https://linux-hardware.org/?probe=5b174d8cab) | Jul 03, 2021 |
| Lenovo    | ThinkPad T490 20N2S04200    | [331968a8d9](https://linux-hardware.org/?probe=331968a8d9) | Jul 03, 2021 |
| Lenovo    | ThinkPad T490 20N2S04200    | [59e9a66bff](https://linux-hardware.org/?probe=59e9a66bff) | Jul 03, 2021 |
| Lenovo    | ThinkPad T490 20N2S04200    | [e20b747527](https://linux-hardware.org/?probe=e20b747527) | Jul 03, 2021 |
| Sony      | SVE14A15FGS                 | [adb8d0cc94](https://linux-hardware.org/?probe=adb8d0cc94) | Jun 14, 2021 |
| Acer      | Aspire A715-71G             | [cb59081351](https://linux-hardware.org/?probe=cb59081351) | Jun 14, 2021 |
| Samsung   | 3570R/370R/470R/450R/510... | [e82b7b36f2](https://linux-hardware.org/?probe=e82b7b36f2) | Jun 12, 2021 |
| ASUSTek   | K52Jc                       | [4b93dc4ee8](https://linux-hardware.org/?probe=4b93dc4ee8) | Jun 07, 2021 |
| HP        | ProBook 650 G1              | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| HP        | EliteBook 8560p             | [ea1bd5e314](https://linux-hardware.org/?probe=ea1bd5e314) | May 30, 2021 |
| Sony      | SVE11126CGB                 | [b7ee22588d](https://linux-hardware.org/?probe=b7ee22588d) | May 29, 2021 |
| Toshiba   | Satellite S70t-B            | [33d64c7a69](https://linux-hardware.org/?probe=33d64c7a69) | May 26, 2021 |
| Toshiba   | Satellite S70t-B            | [60c1bab5d9](https://linux-hardware.org/?probe=60c1bab5d9) | May 26, 2021 |
| HP        | Pavilion Notebook           | [37695077ba](https://linux-hardware.org/?probe=37695077ba) | May 21, 2021 |
| HP        | ENVY 15                     | [2a23609955](https://linux-hardware.org/?probe=2a23609955) | May 15, 2021 |
| Lenovo    | ThinkPad T460p 20FW0005A... | [b799d8a59b](https://linux-hardware.org/?probe=b799d8a59b) | May 10, 2021 |
| Acer      | E5-571-551U                 | [152105400d](https://linux-hardware.org/?probe=152105400d) | May 05, 2021 |
| IBM       | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Lenovo    | ThinkPad T460p 20FW0005A... | [efe93be14e](https://linux-hardware.org/?probe=efe93be14e) | May 01, 2021 |
| Lenovo    | V110-15IAP 80TG             | [76ac42ca9c](https://linux-hardware.org/?probe=76ac42ca9c) | Apr 30, 2021 |
| MSI       | GS63VR 7RF                  | [4a7125aec0](https://linux-hardware.org/?probe=4a7125aec0) | Apr 18, 2021 |
| MSI       | GS63VR 7RF                  | [76126cd5fd](https://linux-hardware.org/?probe=76126cd5fd) | Apr 18, 2021 |
| Toshiba   | PORTEGE M930                | [aac37423e5](https://linux-hardware.org/?probe=aac37423e5) | Apr 13, 2021 |
| Samsung   | 300E4A/300E5A/300E7A/343... | [d65bc55ad0](https://linux-hardware.org/?probe=d65bc55ad0) | Apr 11, 2021 |
| Apple     | MacBook7,1                  | [9b4e89202e](https://linux-hardware.org/?probe=9b4e89202e) | Apr 09, 2021 |
| HP        | ProBook 650 G1              | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP        | EliteBook 2560p             | [ecdecf72ec](https://linux-hardware.org/?probe=ecdecf72ec) | Mar 30, 2021 |
| HP        | ProBook 650 G1              | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| HP        | ZBook Firefly 15 G7 Mobi... | [0653cc5343](https://linux-hardware.org/?probe=0653cc5343) | Mar 29, 2021 |
| Metabox   | X170SM                      | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox   | X170SM                      | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| HP        | ProBook 4540s               | [4fe9e650c2](https://linux-hardware.org/?probe=4fe9e650c2) | Mar 13, 2021 |
| HP        | ProBook 4540s               | [d2c0c69a0d](https://linux-hardware.org/?probe=d2c0c69a0d) | Mar 13, 2021 |
| Acer      | Aspire 5750                 | [6aaf201a58](https://linux-hardware.org/?probe=6aaf201a58) | Mar 10, 2021 |
| Toshiba   | Satellite U920t             | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| HP        | OMEN by HP Laptop 17-an0... | [b1088bed99](https://linux-hardware.org/?probe=b1088bed99) | Feb 26, 2021 |
| Dell      | XPS 13 9360                 | [7de34c9abe](https://linux-hardware.org/?probe=7de34c9abe) | Feb 26, 2021 |
| HP        | ZBook 14                    | [042b4b4a48](https://linux-hardware.org/?probe=042b4b4a48) | Feb 26, 2021 |
| Dell      | Latitude E6430s             | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| Lenovo    | ThinkPad E490 20N8CTO1WW    | [d20e5c1f85](https://linux-hardware.org/?probe=d20e5c1f85) | Feb 15, 2021 |
| HP        | EliteBook 820 G3            | [e1a72b607e](https://linux-hardware.org/?probe=e1a72b607e) | Feb 14, 2021 |
| Dell      | Latitude E4300              | [a09ca20174](https://linux-hardware.org/?probe=a09ca20174) | Feb 14, 2021 |
| HP        | Notebook                    | [e5bc3a0317](https://linux-hardware.org/?probe=e5bc3a0317) | Feb 12, 2021 |
| MSI       | GE66 Raider 10SF            | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| HP        | 355 G2                      | [ac856a41b8](https://linux-hardware.org/?probe=ac856a41b8) | Feb 03, 2021 |
| Acer      | ES1-512-P8NA                | [c393cb6ad4](https://linux-hardware.org/?probe=c393cb6ad4) | Jan 24, 2021 |
| HP        | ProBook 450 G3              | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
| Toshiba   | Satellite U920t             | [35e0de41d7](https://linux-hardware.org/?probe=35e0de41d7) | Jan 17, 2021 |
| Toshiba   | Satellite U920t             | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Lenovo    | ThinkPad T460p 20FW0005A... | [ecc872dc4a](https://linux-hardware.org/?probe=ecc872dc4a) | Jan 16, 2021 |
| Lenovo    | ThinkPad T460 20FMS2FR00    | [3c308a7199](https://linux-hardware.org/?probe=3c308a7199) | Jan 15, 2021 |
| Acer      | ConceptD CN315-71P          | [7d1c394d7a](https://linux-hardware.org/?probe=7d1c394d7a) | Dec 26, 2020 |
| Lenovo    | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| Lenovo    | ThinkPad P52 20M9000KUS     | [ed51fc90e5](https://linux-hardware.org/?probe=ed51fc90e5) | Dec 19, 2020 |
| HP        | ZBook Studio G5             | [af0417cef5](https://linux-hardware.org/?probe=af0417cef5) | Dec 10, 2020 |
| Dell      | Precision 7530              | [c82b4c0f51](https://linux-hardware.org/?probe=c82b4c0f51) | Dec 03, 2020 |
| HP        | Pavilion dv6                | [2c1cf2da53](https://linux-hardware.org/?probe=2c1cf2da53) | Nov 30, 2020 |
| eMachines | eM350                       | [0ba740f085](https://linux-hardware.org/?probe=0ba740f085) | Nov 28, 2020 |
| Dell      | XPS 15 9560                 | [463c0c961e](https://linux-hardware.org/?probe=463c0c961e) | Nov 15, 2020 |
| Dell      | Latitude D630               | [4b5f3f19ae](https://linux-hardware.org/?probe=4b5f3f19ae) | Nov 14, 2020 |
| Toshiba   | Satellite Pro L830          | [97a68dd7c5](https://linux-hardware.org/?probe=97a68dd7c5) | Nov 14, 2020 |
| Lenovo    | ThinkPad T460p 20FWA023C... | [3ffb0e062e](https://linux-hardware.org/?probe=3ffb0e062e) | Nov 13, 2020 |
| Lenovo    | ThinkPad T520 424229U       | [7e7b6fe785](https://linux-hardware.org/?probe=7e7b6fe785) | Nov 13, 2020 |
| Lenovo    | ThinkPad T460p 20FW0044A... | [0001b76ceb](https://linux-hardware.org/?probe=0001b76ceb) | Nov 10, 2020 |
| Acer      | Aspire ES1-511              | [13485ce10c](https://linux-hardware.org/?probe=13485ce10c) | Nov 08, 2020 |
| Acer      | Aspire ES1-511              | [903c4d5729](https://linux-hardware.org/?probe=903c4d5729) | Nov 08, 2020 |
| Lenovo    | ThinkPad T460p 20FWA023C... | [c4d3f6f37d](https://linux-hardware.org/?probe=c4d3f6f37d) | Nov 07, 2020 |
| Lenovo    | ThinkPad T460p 20FW0044A... | [150a3fe622](https://linux-hardware.org/?probe=150a3fe622) | Nov 05, 2020 |
| Lenovo    | ThinkPad T460p 20FWA023C... | [841d75822e](https://linux-hardware.org/?probe=841d75822e) | Nov 04, 2020 |
| Lenovo    | ThinkPad T510 4349P91       | [41c93bb503](https://linux-hardware.org/?probe=41c93bb503) | Oct 29, 2020 |
| Lenovo    | ThinkPad T510 4349P91       | [7678291690](https://linux-hardware.org/?probe=7678291690) | Oct 28, 2020 |
| Lenovo    | ThinkPad T520 42406BG       | [bacac44e9d](https://linux-hardware.org/?probe=bacac44e9d) | Oct 26, 2020 |
| HP        | ProBook 6550b               | [d93b3bfeac](https://linux-hardware.org/?probe=d93b3bfeac) | Oct 22, 2020 |
| Toshiba   | Satellite C660              | [d8ac831c61](https://linux-hardware.org/?probe=d8ac831c61) | Oct 20, 2020 |
| Lenovo    | ThinkPad T460p 20FW0044A... | [8720432e33](https://linux-hardware.org/?probe=8720432e33) | Oct 16, 2020 |
| ASUSTek   | X550EP                      | [f13a8d8d9b](https://linux-hardware.org/?probe=f13a8d8d9b) | Oct 15, 2020 |
| Dell      | XPS 13 9360                 | [8cf28e044c](https://linux-hardware.org/?probe=8cf28e044c) | Oct 11, 2020 |
| HP        | Compaq Presario A900        | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| HP        | Laptop 15s-fq1xxx           | [b3ae2a4d2c](https://linux-hardware.org/?probe=b3ae2a4d2c) | Oct 06, 2020 |
| ASUSTek   | 1015PX                      | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer      | Swift SF314-41              | [26350d0806](https://linux-hardware.org/?probe=26350d0806) | Oct 04, 2020 |
| HP        | Compaq CQ45                 | [ea61076771](https://linux-hardware.org/?probe=ea61076771) | Sep 30, 2020 |
| MSI       | GP75 Leopard 9SD            | [9c152a1117](https://linux-hardware.org/?probe=9c152a1117) | Sep 30, 2020 |
| HP        | Compaq CQ45                 | [f62190e31d](https://linux-hardware.org/?probe=f62190e31d) | Sep 29, 2020 |
| HP        | EliteBook 850 G5            | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Apple     | MacBook5,1                  | [fb2f9dd279](https://linux-hardware.org/?probe=fb2f9dd279) | Sep 24, 2020 |
| HP        | EliteBook Folio 1040 G1     | [0848bad0d4](https://linux-hardware.org/?probe=0848bad0d4) | Sep 23, 2020 |
| Apple     | MacBook5,1                  | [ad39052e7a](https://linux-hardware.org/?probe=ad39052e7a) | Sep 22, 2020 |
| Lenovo    | ThinkPad T460p 20FW0044A... | [616e26ca49](https://linux-hardware.org/?probe=616e26ca49) | Sep 20, 2020 |
| HP        | ProBook 450 G5              | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| HP        | ProBook 6560b               | [109cd57459](https://linux-hardware.org/?probe=109cd57459) | Sep 12, 2020 |
| Dell      | Latitude E6430s             | [bd8ab4dd1c](https://linux-hardware.org/?probe=bd8ab4dd1c) | Sep 08, 2020 |
| HP        | Pavilion Laptop 15-cw1xx... | [b673064c0f](https://linux-hardware.org/?probe=b673064c0f) | Sep 08, 2020 |
| Acer      | Aspire 5750                 | [b65a1db938](https://linux-hardware.org/?probe=b65a1db938) | Sep 07, 2020 |
| Toshiba   | Satellite C50-B             | [167e9daeb7](https://linux-hardware.org/?probe=167e9daeb7) | Sep 05, 2020 |
| HP        | Pavilion dv6                | [4c2298d7bb](https://linux-hardware.org/?probe=4c2298d7bb) | Sep 05, 2020 |
| Dell      | Latitude E7440              | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| HP        | Laptop 15-db0xxx            | [3949b5f183](https://linux-hardware.org/?probe=3949b5f183) | Sep 04, 2020 |
| Dell      | Inspiron 5567               | [ab299d27a4](https://linux-hardware.org/?probe=ab299d27a4) | Sep 04, 2020 |
| Lenovo    | Legion Y540-17IRH 81Q4      | [9c1bd6b943](https://linux-hardware.org/?probe=9c1bd6b943) | Sep 03, 2020 |
| MSI       | GT80S 6QD                   | [e14f86e038](https://linux-hardware.org/?probe=e14f86e038) | Sep 03, 2020 |
| Acer      | Aspire 5750                 | [6c84136b17](https://linux-hardware.org/?probe=6c84136b17) | Sep 03, 2020 |
| Lenovo    | ThinkPad E15 20RDCTO1WW     | [c9cf3aef22](https://linux-hardware.org/?probe=c9cf3aef22) | Sep 03, 2020 |
| Lenovo    | ThinkPad E15 20RDCTO1WW     | [65612b9b8f](https://linux-hardware.org/?probe=65612b9b8f) | Sep 03, 2020 |
| Toshiba   | Satellite C660              | [fe8b200f4f](https://linux-hardware.org/?probe=fe8b200f4f) | Sep 02, 2020 |
| Toshiba   | Satellite C660              | [e7791768a3](https://linux-hardware.org/?probe=e7791768a3) | Sep 02, 2020 |
| Toshiba   | Satellite C50-B             | [186e22ea8c](https://linux-hardware.org/?probe=186e22ea8c) | Sep 01, 2020 |
| Dell      | XPS 15 9570                 | [cb17688de8](https://linux-hardware.org/?probe=cb17688de8) | Sep 01, 2020 |
| Lenovo    | ThinkPad T460p 20FW0044A... | [67c184a6e0](https://linux-hardware.org/?probe=67c184a6e0) | Aug 27, 2020 |
| Lenovo    | ThinkPad T460p 20FW0044A... | [4d92725c5a](https://linux-hardware.org/?probe=4d92725c5a) | Aug 26, 2020 |
| Lenovo    | ThinkPad T460 20FMS2FR00    | [1707834024](https://linux-hardware.org/?probe=1707834024) | Aug 26, 2020 |
| Lenovo    | ThinkPad T460 20FMS2FR00    | [db76b91e62](https://linux-hardware.org/?probe=db76b91e62) | Aug 21, 2020 |
| HP        | Pavilion dv6                | [65033f4392](https://linux-hardware.org/?probe=65033f4392) | Aug 19, 2020 |
| MSI       | GE66 Raider 10SF            | [3bcf471b04](https://linux-hardware.org/?probe=3bcf471b04) | Aug 15, 2020 |
| Dell      | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| System76  | Lemur Pro                   | [c2619f1014](https://linux-hardware.org/?probe=c2619f1014) | Aug 14, 2020 |
| MSI       | GT72 2PC                    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Lenovo    | ThinkPad T520 42406BG       | [fb69c1f324](https://linux-hardware.org/?probe=fb69c1f324) | Aug 10, 2020 |
| Apple     | MacBookPro5,5               | [37d32b3bac](https://linux-hardware.org/?probe=37d32b3bac) | Aug 03, 2020 |
| Apple     | MacBookPro5,5               | [6aee03b649](https://linux-hardware.org/?probe=6aee03b649) | Jul 31, 2020 |
| Lenovo    | ThinkPad T520 424229U       | [5f432cfe59](https://linux-hardware.org/?probe=5f432cfe59) | Jul 27, 2020 |
| HP        | Pavilion dv4                | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| MSI       | GE66 Raider 10SF            | [3dcde22239](https://linux-hardware.org/?probe=3dcde22239) | Jul 25, 2020 |
| HP        | Laptop 15-dy0xxx            | [cad2dbb88f](https://linux-hardware.org/?probe=cad2dbb88f) | Jul 25, 2020 |
| HP        | ProBook 450 G5              | [a8dfd5a806](https://linux-hardware.org/?probe=a8dfd5a806) | Jul 21, 2020 |
| HP        | Laptop 15-dy0xxx            | [e471bc69b2](https://linux-hardware.org/?probe=e471bc69b2) | Jul 21, 2020 |
| Dell      | Latitude E5570              | [6408e82f4f](https://linux-hardware.org/?probe=6408e82f4f) | Jul 20, 2020 |
| Lenovo    | ThinkPad T520 424229U       | [5ce8e0018c](https://linux-hardware.org/?probe=5ce8e0018c) | Jul 05, 2020 |
| HP        | EliteBook 840 G1            | [75a2e58b47](https://linux-hardware.org/?probe=75a2e58b47) | Jun 30, 2020 |
| HP        | EliteBook 8560p             | [e83d7e33f2](https://linux-hardware.org/?probe=e83d7e33f2) | Jun 29, 2020 |
| HP        | EliteBook 840 G6            | [9fccdcc42f](https://linux-hardware.org/?probe=9fccdcc42f) | Jun 25, 2020 |
| HP        | ProBook 650 G1              | [d8e10f56ec](https://linux-hardware.org/?probe=d8e10f56ec) | Jun 24, 2020 |
| MSI       | GE66 Raider 10SF            | [ca5d80f8f9](https://linux-hardware.org/?probe=ca5d80f8f9) | Jun 16, 2020 |
| MSI       | GE66 Raider 10SF            | [220b2a94c8](https://linux-hardware.org/?probe=220b2a94c8) | Jun 10, 2020 |
| HP        | ProBook 4540s               | [b28f2f3b8a](https://linux-hardware.org/?probe=b28f2f3b8a) | Jun 05, 2020 |
| HP        | Presario CQ56               | [4eed3fc6f6](https://linux-hardware.org/?probe=4eed3fc6f6) | Jun 05, 2020 |
| MSI       | GE66 Raider 10SF            | [8c0b76c629](https://linux-hardware.org/?probe=8c0b76c629) | Jun 01, 2020 |
| Acer      | Aspire E1-571               | [25ca966875](https://linux-hardware.org/?probe=25ca966875) | Jun 01, 2020 |
| HP        | ProBook 650 G1              | [79cf630852](https://linux-hardware.org/?probe=79cf630852) | May 25, 2020 |
| MSI       | GE66 Raider 10SF            | [1cb7bb7ad9](https://linux-hardware.org/?probe=1cb7bb7ad9) | May 23, 2020 |
| MSI       | GE66 Raider 10SF            | [afec91ff4d](https://linux-hardware.org/?probe=afec91ff4d) | May 23, 2020 |
| Lenovo    | ThinkPad X1 Extreme 2nd ... | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| HP        | EliteBook 8560p             | [5439d2f06b](https://linux-hardware.org/?probe=5439d2f06b) | May 22, 2020 |
| Dell      | Latitude E6430s             | [891fd84ed1](https://linux-hardware.org/?probe=891fd84ed1) | May 21, 2020 |
| Dell      | Latitude E6430s             | [b2f67f2744](https://linux-hardware.org/?probe=b2f67f2744) | May 20, 2020 |
| Sony      | VPCEH28FG                   | [f241603946](https://linux-hardware.org/?probe=f241603946) | May 17, 2020 |
| Lenovo    | ThinkPad E590 20NBS0SC00    | [50ca962181](https://linux-hardware.org/?probe=50ca962181) | May 14, 2020 |
| HP        | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP        | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| HP        | EliteBook 8560p             | [605660fceb](https://linux-hardware.org/?probe=605660fceb) | May 11, 2020 |
| Lenovo    | ThinkPad E520 1143CTO       | [d1258905c6](https://linux-hardware.org/?probe=d1258905c6) | May 10, 2020 |
| Lenovo    | ThinkPad E520 1143CTO       | [51adfc765c](https://linux-hardware.org/?probe=51adfc765c) | May 10, 2020 |
| Lenovo    | ThinkPad T520 42406BG       | [8ca322cd11](https://linux-hardware.org/?probe=8ca322cd11) | May 06, 2020 |
| Lenovo    | ThinkPad T520 42406BG       | [f1e3dd647d](https://linux-hardware.org/?probe=f1e3dd647d) | May 06, 2020 |
| Lenovo    | ThinkPad T520 42406BG       | [92b3b97e96](https://linux-hardware.org/?probe=92b3b97e96) | May 05, 2020 |
| Lenovo    | ThinkPad T520 42406BG       | [e0d0592e34](https://linux-hardware.org/?probe=e0d0592e34) | May 05, 2020 |
| HP        | ProBook 650 G1              | [ed42eb842d](https://linux-hardware.org/?probe=ed42eb842d) | May 04, 2020 |
| HP        | ProBook 650 G1              | [d29d76cb5c](https://linux-hardware.org/?probe=d29d76cb5c) | May 04, 2020 |
| HP        | Presario CQ57               | [df09ee9161](https://linux-hardware.org/?probe=df09ee9161) | Apr 26, 2020 |
| Toshiba   | TECRA Z50-A                 | [ff5b768627](https://linux-hardware.org/?probe=ff5b768627) | Apr 21, 2020 |
| Acer      | Aspire A315-21G             | [7f9e52f0dd](https://linux-hardware.org/?probe=7f9e52f0dd) | Apr 20, 2020 |
| Acer      | Aspire A315-21G             | [4409c8dae5](https://linux-hardware.org/?probe=4409c8dae5) | Apr 20, 2020 |
| MSI       | GT72 2PC                    | [25fcea9dec](https://linux-hardware.org/?probe=25fcea9dec) | Apr 18, 2020 |
| HP        | Pavilion g6                 | [15ad84ee0f](https://linux-hardware.org/?probe=15ad84ee0f) | Apr 15, 2020 |
| Dell      | XPS 13 9360                 | [89cce1b8b6](https://linux-hardware.org/?probe=89cce1b8b6) | Apr 06, 2020 |
| ASUSTek   | VivoBook_ASUSLaptop X530... | [e4ed30a655](https://linux-hardware.org/?probe=e4ed30a655) | Apr 04, 2020 |
| Toshiba   | Satellite L750              | [391a50ded4](https://linux-hardware.org/?probe=391a50ded4) | Apr 03, 2020 |
| ASUSTek   | N56VZ                       | [04666ab26e](https://linux-hardware.org/?probe=04666ab26e) | Apr 01, 2020 |
| HP        | Pavilion 10 TS              | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| Lenovo    | ThinkPad X1 Carbon 3rd 2... | [0c505fcd69](https://linux-hardware.org/?probe=0c505fcd69) | Mar 25, 2020 |
| Lenovo    | ThinkPad X1 Carbon 3rd 2... | [fc12fa3a4d](https://linux-hardware.org/?probe=fc12fa3a4d) | Mar 25, 2020 |
| Dell      | Precision M6800             | [adb3b768f7](https://linux-hardware.org/?probe=adb3b768f7) | Mar 24, 2020 |
| ASUSTek   | TAICHI21                    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| HP        | EliteBook 840 G6            | [a26150e202](https://linux-hardware.org/?probe=a26150e202) | Mar 07, 2020 |
| HP        | EliteBook 840 G6            | [0d6d26562c](https://linux-hardware.org/?probe=0d6d26562c) | Mar 07, 2020 |
| Lenovo    | ThinkPad T520 424229U       | [f49a66ef1e](https://linux-hardware.org/?probe=f49a66ef1e) | Feb 25, 2020 |
| HP        | Pavilion 15                 | [72784962fe](https://linux-hardware.org/?probe=72784962fe) | Feb 25, 2020 |
| HP        | Pavilion 15                 | [a1e89aa309](https://linux-hardware.org/?probe=a1e89aa309) | Feb 25, 2020 |
| Dell      | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| MSI       | GT72 2PC                    | [2314176c88](https://linux-hardware.org/?probe=2314176c88) | Feb 22, 2020 |
| HP        | EliteBook x360 1040 G6      | [a838427772](https://linux-hardware.org/?probe=a838427772) | Feb 12, 2020 |
| Lenovo    | ThinkPad T520 424229U       | [5f61d3d553](https://linux-hardware.org/?probe=5f61d3d553) | Feb 09, 2020 |
| HUAWEI    | BOHK-WAX9X                  | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| HP        | ProBook 650 G1              | [b5d441afe1](https://linux-hardware.org/?probe=b5d441afe1) | Feb 01, 2020 |
| Lenovo    | V110-14IAP 80TF             | [85b3202273](https://linux-hardware.org/?probe=85b3202273) | Jan 30, 2020 |
| Dell      | XPS 13 9360                 | [c770de6326](https://linux-hardware.org/?probe=c770de6326) | Jan 25, 2020 |
| Lenovo    | ThinkPad X131e 33691A4      | [a30712cd7d](https://linux-hardware.org/?probe=a30712cd7d) | Jan 22, 2020 |
| HP        | Notebook                    | [8f2fc8e2ec](https://linux-hardware.org/?probe=8f2fc8e2ec) | Jan 09, 2020 |
| ASUSTek   | K46CB                       | [45b756e92d](https://linux-hardware.org/?probe=45b756e92d) | Jan 04, 2020 |
| ASUSTek   | K46CB                       | [1a25890709](https://linux-hardware.org/?probe=1a25890709) | Jan 04, 2020 |
| HP        | ProBook 650 G1              | [0763c1c109](https://linux-hardware.org/?probe=0763c1c109) | Jan 02, 2020 |
| HP        | ProBook 650 G1              | [023556890d](https://linux-hardware.org/?probe=023556890d) | Jan 02, 2020 |
| Acer      | Aspire F5-573G              | [ead658852a](https://linux-hardware.org/?probe=ead658852a) | Jan 01, 2020 |
| Acer      | Aspire F5-573G              | [e19db7603d](https://linux-hardware.org/?probe=e19db7603d) | Jan 01, 2020 |
| HP        | ProBook 6550b               | [65a8d66fb9](https://linux-hardware.org/?probe=65a8d66fb9) | Dec 31, 2019 |
| HP        | ProBook 650 G1              | [0085227124](https://linux-hardware.org/?probe=0085227124) | Dec 30, 2019 |
| HP        | EliteBook 850 G5            | [65b1eb0ca1](https://linux-hardware.org/?probe=65b1eb0ca1) | Dec 26, 2019 |
| Lenovo    | ThinkPad T420 4180AQ3       | [4da7aff7a2](https://linux-hardware.org/?probe=4da7aff7a2) | Dec 23, 2019 |
| ASUSTek   | UL50Ag                      | [ba1e7f648c](https://linux-hardware.org/?probe=ba1e7f648c) | Dec 19, 2019 |
| MSI       | GT72 2PC                    | [dbe1269ea7](https://linux-hardware.org/?probe=dbe1269ea7) | Dec 11, 2019 |
| HP        | Pavilion g6                 | [3acb153d5d](https://linux-hardware.org/?probe=3acb153d5d) | Dec 06, 2019 |
| HP        | EliteBook 6930p             | [94af8c86b1](https://linux-hardware.org/?probe=94af8c86b1) | Dec 03, 2019 |
| HP        | Pavilion g6                 | [034500d792](https://linux-hardware.org/?probe=034500d792) | Nov 26, 2019 |
| HP        | Notebook                    | [31d1bef6c1](https://linux-hardware.org/?probe=31d1bef6c1) | Nov 11, 2019 |
| HP        | ProBook 4540s               | [5cc8316a85](https://linux-hardware.org/?probe=5cc8316a85) | Nov 08, 2019 |
| HP        | ProBook 4730s               | [ed03fd8077](https://linux-hardware.org/?probe=ed03fd8077) | Oct 29, 2019 |
| HP        | ProBook 4730s               | [cd284908ca](https://linux-hardware.org/?probe=cd284908ca) | Oct 28, 2019 |
| HP        | Notebook                    | [1bccff3cda](https://linux-hardware.org/?probe=1bccff3cda) | Sep 25, 2019 |
| Toshiba   | PORTEGE M780                | [64824e5a04](https://linux-hardware.org/?probe=64824e5a04) | Sep 21, 2019 |
| MSI       | GE60 0NC/GE60 0ND           | [8e78a0ebf5](https://linux-hardware.org/?probe=8e78a0ebf5) | Sep 11, 2019 |
| MSI       | GE60 0NC/GE60 0ND           | [fd27e8c70f](https://linux-hardware.org/?probe=fd27e8c70f) | Sep 11, 2019 |
| HP        | Notebook                    | [776ffefbc2](https://linux-hardware.org/?probe=776ffefbc2) | Sep 11, 2019 |
| MSI       | GE60 0NC/GE60 0ND           | [f5b3521c55](https://linux-hardware.org/?probe=f5b3521c55) | Sep 11, 2019 |
| HP        | Notebook                    | [cf646ad1f2](https://linux-hardware.org/?probe=cf646ad1f2) | Sep 11, 2019 |
| ASUSTek   | TUF Gaming FX505DD_FX505... | [873e28fce7](https://linux-hardware.org/?probe=873e28fce7) | Sep 02, 2019 |
| HP        | Compaq 6910p (GM903PA#AB... | [2724623348](https://linux-hardware.org/?probe=2724623348) | Aug 12, 2019 |
| ASUSTek   | X542UQ                      | [7a4797b166](https://linux-hardware.org/?probe=7a4797b166) | Aug 11, 2019 |
| HP        | ProBook 6570b               | [4f80f9ba3c](https://linux-hardware.org/?probe=4f80f9ba3c) | Aug 04, 2019 |
| Lenovo    | ThinkPad T440p 20AWS1J00... | [31bcd5a103](https://linux-hardware.org/?probe=31bcd5a103) | Jul 31, 2019 |
| HP        | ProBook 450 G3              | [b9e21a89da](https://linux-hardware.org/?probe=b9e21a89da) | Jul 23, 2019 |
| HP        | ProBook 650 G1              | [6d584d5dab](https://linux-hardware.org/?probe=6d584d5dab) | Jul 22, 2019 |
| HP        | ProBook 450 G3              | [10b8987b19](https://linux-hardware.org/?probe=10b8987b19) | Jul 17, 2019 |
| HP        | ProBook 6550b               | [801f83247c](https://linux-hardware.org/?probe=801f83247c) | Jul 06, 2019 |
| HP        | ProBook 4730s               | [ed98a45d81](https://linux-hardware.org/?probe=ed98a45d81) | Jul 01, 2019 |
| Acer      | Aspire 5100                 | [a28f7b2623](https://linux-hardware.org/?probe=a28f7b2623) | Jun 27, 2019 |
| Acer      | Aspire 5100                 | [e76b718b4a](https://linux-hardware.org/?probe=e76b718b4a) | Jun 12, 2019 |
| Acer      | Aspire 5100                 | [da3b674d14](https://linux-hardware.org/?probe=da3b674d14) | Jun 11, 2019 |
| Acer      | Aspire 5100                 | [cbefba08bb](https://linux-hardware.org/?probe=cbefba08bb) | Jun 11, 2019 |
| Acer      | Aspire 5100                 | [aa61fb2b9c](https://linux-hardware.org/?probe=aa61fb2b9c) | Jun 11, 2019 |
| YJKC      | vBOOK Plus                  | [80eae9ed5f](https://linux-hardware.org/?probe=80eae9ed5f) | Jun 09, 2019 |
| HP        | Unknown                     | [ef6ea82cf5](https://linux-hardware.org/?probe=ef6ea82cf5) | May 20, 2019 |
| ASUSTek   | K84L                        | [231a7d9bc6](https://linux-hardware.org/?probe=231a7d9bc6) | Apr 18, 2019 |
| HP        | ProBook 6570b               | [42129ed417](https://linux-hardware.org/?probe=42129ed417) | Mar 23, 2019 |
| HP        | ProBook 6570b               | [25a7d4cca8](https://linux-hardware.org/?probe=25a7d4cca8) | Mar 03, 2019 |
| Acer      | Aspire E5-721               | [e6dca4d6fd](https://linux-hardware.org/?probe=e6dca4d6fd) | Feb 28, 2019 |
| HP        | Mini 110-1100               | [1ba5e0d0b2](https://linux-hardware.org/?probe=1ba5e0d0b2) | Feb 23, 2019 |
| HP        | ProBook 6570b               | [82e153050f](https://linux-hardware.org/?probe=82e153050f) | Jan 28, 2019 |
| HP        | ProBook 650 G1              | [2756a314e5](https://linux-hardware.org/?probe=2756a314e5) | Jan 14, 2019 |
| HP        | ProBook 650 G1              | [f81c16faea](https://linux-hardware.org/?probe=f81c16faea) | Jan 14, 2019 |
| Lenovo    | B590 20208                  | [7c06278f98](https://linux-hardware.org/?probe=7c06278f98) | Dec 28, 2018 |
| Lenovo    | B590 20208                  | [d4897cc9d7](https://linux-hardware.org/?probe=d4897cc9d7) | Dec 28, 2018 |
| HP        | Pavilion 15                 | [5407e9ab05](https://linux-hardware.org/?probe=5407e9ab05) | Dec 22, 2018 |
| HP        | Pavilion 15                 | [a47a651328](https://linux-hardware.org/?probe=a47a651328) | Dec 22, 2018 |
| HP        | 14                          | [553085d233](https://linux-hardware.org/?probe=553085d233) | Jul 06, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 32        | 13.45%  |
| Ubuntu 18.04                 | 14        | 5.88%   |
| Zorin 15                     | 9         | 3.78%   |
| OpenMandriva 4.2             | 8         | 3.36%   |
| Arch                         | 8         | 3.36%   |
| Ubuntu 21.10                 | 6         | 2.52%   |
| Ubuntu 20.10                 | 6         | 2.52%   |
| Pop!_OS 20.04                | 6         | 2.52%   |
| Fedora 31                    | 6         | 2.52%   |
| Debian 10                    | 6         | 2.52%   |
| Arch Rolling                 | 6         | 2.52%   |
| Pop!_OS 20.10                | 5         | 2.1%    |
| OpenMandriva 4.3             | 5         | 2.1%    |
| Linux Mint 20.2              | 5         | 2.1%    |
| Fedora 35                    | 5         | 2.1%    |
| Zorin 16                     | 4         | 1.68%   |
| Ubuntu 21.04                 | 4         | 1.68%   |
| Pop!_OS 21.04                | 4         | 1.68%   |
| Manjaro                      | 4         | 1.68%   |
| Linux Mint 19.2              | 4         | 1.68%   |
| Kubuntu 20.04                | 4         | 1.68%   |
| Fedora 34                    | 4         | 1.68%   |
| Fedora 33                    | 4         | 1.68%   |
| Ubuntu 19.10                 | 3         | 1.26%   |
| Linux Mint 20                | 3         | 1.26%   |
| Linux Mint 19.3              | 3         | 1.26%   |
| Linux Mint 19.1              | 3         | 1.26%   |
| Fedora 32                    | 3         | 1.26%   |
| EndeavourOS Rolling          | 3         | 1.26%   |
| Ubuntu 19.04                 | 2         | 0.84%   |
| ROSA R10                     | 2         | 0.84%   |
| Pop!_OS 21.10                | 2         | 0.84%   |
| Linux Mint 20.3              | 2         | 0.84%   |
| Linux Mint 20.1              | 2         | 0.84%   |
| KDE neon 20.04               | 2         | 0.84%   |
| Endless 3.7.8                | 2         | 0.84%   |
| Endless 3.6.1                | 2         | 0.84%   |
| Endless 3.5.4                | 2         | 0.84%   |
| Elementary 6.1               | 2         | 0.84%   |
| Debian Unstable              | 2         | 0.84%   |
| Debian 11                    | 2         | 0.84%   |
| Xubuntu 20.04                | 1         | 0.42%   |
| Xubuntu 19.04                | 1         | 0.42%   |
| Xubuntu 18.04                | 1         | 0.42%   |
| Void Linux                   | 1         | 0.42%   |
| Ubuntu MATE 20.10            | 1         | 0.42%   |
| Ubuntu MATE 20.04            | 1         | 0.42%   |
| Ubuntu 22.04                 | 1         | 0.42%   |
| Ubuntu 18.10                 | 1         | 0.42%   |
| Ubuntu 16.04                 | 1         | 0.42%   |
| Solus 4.2                    | 1         | 0.42%   |
| Solus 4.1                    | 1         | 0.42%   |
| Parrot 4.10                  | 1         | 0.42%   |
| openSUSE Tumbleweed-20200416 | 1         | 0.42%   |
| Manjaro 21.2.5               | 1         | 0.42%   |
| Manjaro 21.2.1               | 1         | 0.42%   |
| Manjaro 21.1.0               | 1         | 0.42%   |
| Manjaro 21.0.5               | 1         | 0.42%   |
| Manjaro 20.2.1               | 1         | 0.42%   |
| Lubuntu 21.10                | 1         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 68        | 30.22%  |
| Fedora       | 22        | 9.78%   |
| Linux Mint   | 21        | 9.33%   |
| Pop!_OS      | 16        | 7.11%   |
| Arch         | 14        | 6.22%   |
| Zorin        | 13        | 5.78%   |
| OpenMandriva | 13        | 5.78%   |
| Debian       | 10        | 4.44%   |
| Manjaro      | 9         | 4%      |
| Endless      | 5         | 2.22%   |
| Kubuntu      | 4         | 1.78%   |
| EndeavourOS  | 4         | 1.78%   |
| Elementary   | 4         | 1.78%   |
| Xubuntu      | 3         | 1.33%   |
| Ubuntu MATE  | 2         | 0.89%   |
| Solus        | 2         | 0.89%   |
| ROSA         | 2         | 0.89%   |
| Lubuntu      | 2         | 0.89%   |
| KDE neon     | 2         | 0.89%   |
| Gentoo       | 2         | 0.89%   |
| Void Linux   | 1         | 0.44%   |
| Parrot       | 1         | 0.44%   |
| openSUSE     | 1         | 0.44%   |
| LMDE         | 1         | 0.44%   |
| BlackPanther | 1         | 0.44%   |
| ArcoLinux    | 1         | 0.44%   |
| Archman      | 1         | 0.44%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 4.43%   |
| 5.10.14-desktop-1omv4002 | 8         | 2.95%   |
| 5.4.0-48-generic         | 5         | 1.85%   |
| 5.3.0-28-generic         | 5         | 1.85%   |
| 5.16.7-desktop-1omv4003  | 5         | 1.85%   |
| 5.3.16-300.fc31.x86_64   | 4         | 1.48%   |
| 5.11.0-7620-generic      | 4         | 1.48%   |
| 5.11.0-27-generic        | 4         | 1.48%   |
| 5.8.0-53-generic         | 3         | 1.11%   |
| 5.4.0-81-generic         | 3         | 1.11%   |
| 5.4.0-7642-generic       | 3         | 1.11%   |
| 5.4.0-74-generic         | 3         | 1.11%   |
| 5.4.0-45-generic         | 3         | 1.11%   |
| 5.4.0-26-generic         | 3         | 1.11%   |
| 5.3.0-40-generic         | 3         | 1.11%   |
| 5.0.0-37-generic         | 3         | 1.11%   |
| 4.19.0-9-amd64           | 3         | 1.11%   |
| 5.8.11-1-MANJARO         | 2         | 0.74%   |
| 5.8.0-7630-generic       | 2         | 0.74%   |
| 5.8.0-48-generic         | 2         | 0.74%   |
| 5.8.0-43-generic         | 2         | 0.74%   |
| 5.4.0-91-generic         | 2         | 0.74%   |
| 5.4.0-72-generic         | 2         | 0.74%   |
| 5.4.0-65-generic         | 2         | 0.74%   |
| 5.4.0-40-generic         | 2         | 0.74%   |
| 5.4.0-39-generic         | 2         | 0.74%   |
| 5.4.0-29-generic         | 2         | 0.74%   |
| 5.3.0-46-generic         | 2         | 0.74%   |
| 5.3.0-26-generic         | 2         | 0.74%   |
| 5.15.4-arch1-1           | 2         | 0.74%   |
| 5.15.12-arch1-1          | 2         | 0.74%   |
| 5.14.15-300.fc35.x86_64  | 2         | 0.74%   |
| 5.13.0-7614-generic      | 2         | 0.74%   |
| 5.13.0-39-generic        | 2         | 0.74%   |
| 5.13.0-37-generic        | 2         | 0.74%   |
| 5.13.0-19-generic        | 2         | 0.74%   |
| 5.11.0-7612-generic      | 2         | 0.74%   |
| 5.11.0-36-generic        | 2         | 0.74%   |
| 5.0.0-23-generic         | 2         | 0.74%   |
| 5.0.0-17-generic         | 2         | 0.74%   |
| 5.0.0-15-generic         | 2         | 0.74%   |
| 4.19.0-10-amd64          | 2         | 0.74%   |
| 4.18.0-21-generic        | 2         | 0.74%   |
| 4.18.0-12-generic        | 2         | 0.74%   |
| 5.9.8-arch1-1            | 1         | 0.37%   |
| 5.9.3-arch1-1            | 1         | 0.37%   |
| 5.9.16-1-MANJARO         | 1         | 0.37%   |
| 5.9.11-zen2-1-zen        | 1         | 0.37%   |
| 5.8.3-arch1-1            | 1         | 0.37%   |
| 5.8.16-200.fc32.x86_64   | 1         | 0.37%   |
| 5.8.15-201.fc32.x86_64   | 1         | 0.37%   |
| 5.8.14-arch1-1           | 1         | 0.37%   |
| 5.8.10-arch1-1           | 1         | 0.37%   |
| 5.8.1-arch1-1            | 1         | 0.37%   |
| 5.8.0-7625-generic       | 1         | 0.37%   |
| 5.8.0-63-generic         | 1         | 0.37%   |
| 5.8.0-50-generic         | 1         | 0.37%   |
| 5.8.0-44-generic         | 1         | 0.37%   |
| 5.8.0-38-generic         | 1         | 0.37%   |
| 5.8.0-25-generic         | 1         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 20%     |
| 5.3.0   | 17        | 6.67%   |
| 5.11.0  | 17        | 6.67%   |
| 5.13.0  | 16        | 6.27%   |
| 5.8.0   | 15        | 5.88%   |
| 4.15.0  | 13        | 5.1%    |
| 5.0.0   | 12        | 4.71%   |
| 5.10.14 | 9         | 3.53%   |
| 4.19.0  | 7         | 2.75%   |
| 4.18.0  | 6         | 2.35%   |
| 5.16.7  | 5         | 1.96%   |
| 5.3.16  | 4         | 1.57%   |
| 5.15.4  | 3         | 1.18%   |
| 5.8.11  | 2         | 0.78%   |
| 5.7.0   | 2         | 0.78%   |
| 5.6.8   | 2         | 0.78%   |
| 5.6.19  | 2         | 0.78%   |
| 5.3.8   | 2         | 0.78%   |
| 5.16.11 | 2         | 0.78%   |
| 5.15.15 | 2         | 0.78%   |
| 5.15.12 | 2         | 0.78%   |
| 5.14.15 | 2         | 0.78%   |
| 5.13.5  | 2         | 0.78%   |
| 5.11.12 | 2         | 0.78%   |
| 5.10.0  | 2         | 0.78%   |
| 5.9.8   | 1         | 0.39%   |
| 5.9.3   | 1         | 0.39%   |
| 5.9.16  | 1         | 0.39%   |
| 5.9.11  | 1         | 0.39%   |
| 5.8.3   | 1         | 0.39%   |
| 5.8.16  | 1         | 0.39%   |
| 5.8.15  | 1         | 0.39%   |
| 5.8.14  | 1         | 0.39%   |
| 5.8.10  | 1         | 0.39%   |
| 5.8.1   | 1         | 0.39%   |
| 5.7.8   | 1         | 0.39%   |
| 5.7.5   | 1         | 0.39%   |
| 5.7.12  | 1         | 0.39%   |
| 5.6.4   | 1         | 0.39%   |
| 5.6.11  | 1         | 0.39%   |
| 5.6.0   | 1         | 0.39%   |
| 5.5.8   | 1         | 0.39%   |
| 5.5.10  | 1         | 0.39%   |
| 5.4.72  | 1         | 0.39%   |
| 5.4.32  | 1         | 0.39%   |
| 5.4.21  | 1         | 0.39%   |
| 5.4.15  | 1         | 0.39%   |
| 5.4.14  | 1         | 0.39%   |
| 5.2.11  | 1         | 0.39%   |
| 5.16.3  | 1         | 0.39%   |
| 5.16.18 | 1         | 0.39%   |
| 5.16.14 | 1         | 0.39%   |
| 5.16.13 | 1         | 0.39%   |
| 5.16.1  | 1         | 0.39%   |
| 5.15.7  | 1         | 0.39%   |
| 5.15.28 | 1         | 0.39%   |
| 5.15.0  | 1         | 0.39%   |
| 5.14.2  | 1         | 0.39%   |
| 5.14.18 | 1         | 0.39%   |
| 5.14.13 | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 56        | 22.49%  |
| 5.11    | 23        | 9.24%   |
| 5.3     | 22        | 8.84%   |
| 5.8     | 21        | 8.43%   |
| 5.13    | 19        | 7.63%   |
| 5.10    | 17        | 6.83%   |
| 4.15    | 13        | 5.22%   |
| 5.16    | 12        | 4.82%   |
| 5.0     | 12        | 4.82%   |
| 5.15    | 10        | 4.02%   |
| 4.19    | 7         | 2.81%   |
| 4.18    | 7         | 2.81%   |
| 5.6     | 6         | 2.41%   |
| 5.14    | 6         | 2.41%   |
| 5.7     | 5         | 2.01%   |
| 5.9     | 4         | 1.61%   |
| 5.5     | 2         | 0.8%    |
| 4.9     | 2         | 0.8%    |
| 4.20    | 2         | 0.8%    |
| 5.2     | 1         | 0.4%    |
| 4.13    | 1         | 0.4%    |
| 4.11    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 208       | 96.3%   |
| i686   | 8         | 3.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 99        | 43.81%  |
| Unknown          | 32        | 14.16%  |
| KDE5             | 27        | 11.95%  |
| X-Cinnamon       | 15        | 6.64%   |
| XFCE             | 13        | 5.75%   |
| KDE              | 10        | 4.42%   |
| MATE             | 8         | 3.54%   |
| Pantheon         | 4         | 1.77%   |
| Cinnamon         | 4         | 1.77%   |
| LXDE             | 3         | 1.33%   |
| i3               | 3         | 1.33%   |
| Unity            | 2         | 0.88%   |
| Budgie           | 2         | 0.88%   |
| LXQt             | 1         | 0.44%   |
| lightdm-xsession | 1         | 0.44%   |
| KDE4             | 1         | 0.44%   |
| Deepin           | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 174       | 77.33%  |
| Wayland | 33        | 14.67%  |
| Unknown | 16        | 7.11%   |
| Tty     | 2         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 139       | 61.23%  |
| SDDM    | 25        | 11.01%  |
| GDM     | 25        | 11.01%  |
| LightDM | 13        | 5.73%   |
| TDM     | 11        | 4.85%   |
| GDM3    | 8         | 3.52%   |
| Ly      | 2         | 0.88%   |
| LXDM    | 2         | 0.88%   |
| XDM     | 1         | 0.44%   |
| KDM     | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_NZ   | 128       | 56.64%  |
| en_US   | 42        | 18.58%  |
| Unknown | 27        | 11.95%  |
| en_GB   | 12        | 5.31%   |
| C       | 9         | 3.98%   |
| en_AU   | 6         | 2.65%   |
| zh_CN   | 1         | 0.44%   |
| de_DE   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 111       | 50.23%  |
| EFI  | 110       | 49.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 171       | 76.34%  |
| Overlay | 18        | 8.04%   |
| Btrfs   | 16        | 7.14%   |
| Unknown | 14        | 6.25%   |
| Xfs     | 2         | 0.89%   |
| Ext2    | 2         | 0.89%   |
| Zfs     | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 141       | 63.51%  |
| GPT     | 58        | 26.13%  |
| MBR     | 23        | 10.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 195       | 88.24%  |
| Yes       | 26        | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 170       | 77.27%  |
| Yes       | 50        | 22.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 64        | 29.63%  |
| Lenovo              | 37        | 17.13%  |
| Dell                | 28        | 12.96%  |
| ASUSTek Computer    | 22        | 10.19%  |
| Acer                | 20        | 9.26%   |
| Toshiba             | 13        | 6.02%   |
| MSI                 | 7         | 3.24%   |
| Apple               | 5         | 2.31%   |
| Sony                | 4         | 1.85%   |
| Samsung Electronics | 4         | 1.85%   |
| System76            | 2         | 0.93%   |
| YJKC                | 1         | 0.46%   |
| TWG                 | 1         | 0.46%   |
| Timi                | 1         | 0.46%   |
| Star Labs           | 1         | 0.46%   |
| Metabox             | 1         | 0.46%   |
| Medion              | 1         | 0.46%   |
| IBM                 | 1         | 0.46%   |
| HUAWEI              | 1         | 0.46%   |
| Google              | 1         | 0.46%   |
| eMachines           | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell XPS 13 9360                           | 5         | 2.31%   |
| HP ProBook 4540s                           | 3         | 1.39%   |
| HP EliteBook 8560p                         | 3         | 1.39%   |
| MSI GE66 Raider 10SF                       | 2         | 0.93%   |
| Lenovo ThinkPad T460 20FMS2FR00            | 2         | 0.93%   |
| HP ProBook 6550b                           | 2         | 0.93%   |
| HP ProBook 450 G5                          | 2         | 0.93%   |
| HP ProBook 450 G3                          | 2         | 0.93%   |
| HP Pavilion dv6                            | 2         | 0.93%   |
| HP Pavilion 15                             | 2         | 0.93%   |
| HP Notebook                                | 2         | 0.93%   |
| Dell XPS 15 9500                           | 2         | 0.93%   |
| Dell Latitude E4300                        | 2         | 0.93%   |
| Dell Latitude 7490                         | 2         | 0.93%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR      | 2         | 0.93%   |
| ASUS K52Jc                                 | 2         | 0.93%   |
| Acer Swift SF314-41                        | 2         | 0.93%   |
| YJKC vBOOK Plus                            | 1         | 0.46%   |
| TWG E2017                                  | 1         | 0.46%   |
| Toshiba TECRA Z50-A                        | 1         | 0.46%   |
| Toshiba Satellite U920t                    | 1         | 0.46%   |
| Toshiba Satellite S70t-B                   | 1         | 0.46%   |
| Toshiba Satellite Pro R50-C                | 1         | 0.46%   |
| Toshiba Satellite Pro L830                 | 1         | 0.46%   |
| Toshiba Satellite L750                     | 1         | 0.46%   |
| Toshiba Satellite C660                     | 1         | 0.46%   |
| Toshiba Satellite C50D-C                   | 1         | 0.46%   |
| Toshiba Satellite C50-B                    | 1         | 0.46%   |
| Toshiba PORTEGE R930                       | 1         | 0.46%   |
| Toshiba PORTEGE R700                       | 1         | 0.46%   |
| Toshiba PORTEGE M930                       | 1         | 0.46%   |
| Toshiba PORTEGE M780                       | 1         | 0.46%   |
| Timi A30                                   | 1         | 0.46%   |
| System76 Pangolin                          | 1         | 0.46%   |
| System76 Lemur Pro                         | 1         | 0.46%   |
| Star Labs LabTop                           | 1         | 0.46%   |
| Sony VPCEH28FG                             | 1         | 0.46%   |
| Sony VPCEB43FG                             | 1         | 0.46%   |
| Sony SVE14A15FGS                           | 1         | 0.46%   |
| Sony SVE11126CGB                           | 1         | 0.46%   |
| Samsung RC410/RC510/RC710                  | 1         | 0.46%   |
| Samsung 530U3C/530U4C/532U3C               | 1         | 0.46%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV   | 1         | 0.46%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.46%   |
| MSI GT80S 6QD                              | 1         | 0.46%   |
| MSI GT72 2PC                               | 1         | 0.46%   |
| MSI GS63VR 7RF                             | 1         | 0.46%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.46%   |
| MSI GE60 0NC/GE60 0ND                      | 1         | 0.46%   |
| Metabox X170SM                             | 1         | 0.46%   |
| Medion P6815                               | 1         | 0.46%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.46%   |
| Lenovo V15-IIL 82C5                        | 1         | 0.46%   |
| Lenovo V110-15IAP 80TG                     | 1         | 0.46%   |
| Lenovo V110-14IAP 80TF                     | 1         | 0.46%   |
| Lenovo ThinkPad X131e 33691A4              | 1         | 0.46%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QV001GPB  | 1         | 0.46%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS3GL00   | 1         | 0.46%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0H200   | 1         | 0.46%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTA0MJNZ   | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 27        | 12.5%   |
| HP ProBook        | 14        | 6.48%   |
| HP Pavilion       | 14        | 6.48%   |
| HP EliteBook      | 14        | 6.48%   |
| Acer Aspire       | 13        | 6.02%   |
| Dell XPS          | 11        | 5.09%   |
| Dell Latitude     | 10        | 4.63%   |
| Toshiba Satellite | 8         | 3.7%    |
| HP Laptop         | 5         | 2.31%   |
| Toshiba PORTEGE   | 4         | 1.85%   |
| ASUS ROG          | 4         | 1.85%   |
| HP ZBook          | 3         | 1.39%   |
| HP Compaq         | 3         | 1.39%   |
| Dell Inspiron     | 3         | 1.39%   |
| MSI GE66          | 2         | 0.93%   |
| Lenovo IdeaPad    | 2         | 0.93%   |
| HP Presario       | 2         | 0.93%   |
| HP Notebook       | 2         | 0.93%   |
| Dell Precision    | 2         | 0.93%   |
| ASUS K52Jc        | 2         | 0.93%   |
| ASUS ASUS         | 2         | 0.93%   |
| Apple MacBookPro5 | 2         | 0.93%   |
| Acer TravelMate   | 2         | 0.93%   |
| Acer Swift        | 2         | 0.93%   |
| YJKC vBOOK        | 1         | 0.46%   |
| TWG E2017         | 1         | 0.46%   |
| Toshiba TECRA     | 1         | 0.46%   |
| Timi A30          | 1         | 0.46%   |
| System76 Pangolin | 1         | 0.46%   |
| System76 Lemur    | 1         | 0.46%   |
| Star Labs LabTop  | 1         | 0.46%   |
| Sony VPCEH28FG    | 1         | 0.46%   |
| Sony VPCEB43FG    | 1         | 0.46%   |
| Sony SVE14A15FGS  | 1         | 0.46%   |
| Sony SVE11126CGB  | 1         | 0.46%   |
| Samsung RC410     | 1         | 0.46%   |
| Samsung 530U3C    | 1         | 0.46%   |
| Samsung 3570R     | 1         | 0.46%   |
| Samsung 300E4A    | 1         | 0.46%   |
| MSI GT80S         | 1         | 0.46%   |
| MSI GT72          | 1         | 0.46%   |
| MSI GS63VR        | 1         | 0.46%   |
| MSI GP75          | 1         | 0.46%   |
| MSI GE60          | 1         | 0.46%   |
| Metabox X170SM    | 1         | 0.46%   |
| Medion P6815      | 1         | 0.46%   |
| Lenovo Yoga       | 1         | 0.46%   |
| Lenovo V15-IIL    | 1         | 0.46%   |
| Lenovo V110-15IAP | 1         | 0.46%   |
| Lenovo V110-14IAP | 1         | 0.46%   |
| Lenovo Legion     | 1         | 0.46%   |
| Lenovo B590       | 1         | 0.46%   |
| Lenovo B50-70     | 1         | 0.46%   |
| Lenovo B50-30     | 1         | 0.46%   |
| IBM ThinkPad      | 1         | 0.46%   |
| HUAWEI BOHK-WAX9X | 1         | 0.46%   |
| HP Spectre        | 1         | 0.46%   |
| HP OMEN           | 1         | 0.46%   |
| HP Mini           | 1         | 0.46%   |
| HP ENVY           | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 25        | 11.57%  |
| 2011 | 24        | 11.11%  |
| 2019 | 20        | 9.26%   |
| 2016 | 19        | 8.8%    |
| 2020 | 16        | 7.41%   |
| 2017 | 16        | 7.41%   |
| 2014 | 16        | 7.41%   |
| 2018 | 14        | 6.48%   |
| 2013 | 13        | 6.02%   |
| 2021 | 12        | 5.56%   |
| 2015 | 11        | 5.09%   |
| 2010 | 11        | 5.09%   |
| 2008 | 9         | 4.17%   |
| 2009 | 5         | 2.31%   |
| 2007 | 2         | 0.93%   |
| 2006 | 2         | 0.93%   |
| 2005 | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 216       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 192       | 88.07%  |
| Enabled  | 26        | 11.93%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 213       | 98.61%  |
| Yes  | 3         | 1.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 26.13%  |
| 16.01-24.0  | 43        | 19.37%  |
| 3.01-4.0    | 42        | 18.92%  |
| 8.01-16.0   | 41        | 18.47%  |
| 32.01-64.0  | 19        | 8.56%   |
| 1.01-2.0    | 6         | 2.7%    |
| 2.01-3.0    | 4         | 1.8%    |
| 64.01-256.0 | 4         | 1.8%    |
| 0.51-1.0    | 3         | 1.35%   |
| 24.01-32.0  | 2         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 80        | 32.52%  |
| 2.01-3.0   | 64        | 26.02%  |
| 3.01-4.0   | 40        | 16.26%  |
| 4.01-8.0   | 34        | 13.82%  |
| 0.51-1.0   | 17        | 6.91%   |
| 8.01-16.0  | 7         | 2.85%   |
| 16.01-24.0 | 2         | 0.81%   |
| 24.01-32.0 | 1         | 0.41%   |
| 0.01-0.5   | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 170       | 76.58%  |
| 2      | 44        | 19.82%  |
| 3      | 6         | 2.7%    |
| 0      | 2         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 118       | 54.38%  |
| Yes       | 99        | 45.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 84.86%  |
| No        | 33        | 15.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 99.07%  |
| No        | 2         | 0.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 79.09%  |
| No        | 46        | 20.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| New Zealand | 216       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Auckland         | 106       | 47.32%  |
| Wellington       | 29        | 12.95%  |
| Christchurch     | 20        | 8.93%   |
| Hamilton         | 8         | 3.57%   |
| Whangarei        | 7         | 3.13%   |
| Dunedin          | 6         | 2.68%   |
| New Plymouth     | 5         | 2.23%   |
| Tauranga         | 4         | 1.79%   |
| Nelson           | 4         | 1.79%   |
| Invercargill     | 4         | 1.79%   |
| Tokoroa          | 3         | 1.34%   |
| Porirua          | 3         | 1.34%   |
| Palmerston North | 2         | 0.89%   |
| Napier City      | 2         | 0.89%   |
| Mangawhai        | 2         | 0.89%   |
| Hastings         | 2         | 0.89%   |
| Grafton          | 2         | 0.89%   |
| Whanganui        | 1         | 0.45%   |
| Te Puke          | 1         | 0.45%   |
| Queenstown       | 1         | 0.45%   |
| Paraparaumu      | 1         | 0.45%   |
| Pakuranga        | 1         | 0.45%   |
| Oxford           | 1         | 0.45%   |
| Oamaru           | 1         | 0.45%   |
| Murchison        | 1         | 0.45%   |
| Lower Hutt       | 1         | 0.45%   |
| Levin            | 1         | 0.45%   |
| Huntly           | 1         | 0.45%   |
| Gordonton        | 1         | 0.45%   |
| Dannevirke       | 1         | 0.45%   |
| Cust             | 1         | 0.45%   |
| Cambridge        | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 46        | 61     | 17.9%   |
| Seagate                   | 37        | 41     | 14.4%   |
| WDC                       | 28        | 48     | 10.89%  |
| Toshiba                   | 23        | 29     | 8.95%   |
| Crucial                   | 19        | 34     | 7.39%   |
| Sandisk                   | 15        | 17     | 5.84%   |
| SK Hynix                  | 13        | 13     | 5.06%   |
| Intel                     | 11        | 13     | 4.28%   |
| Unknown                   | 8         | 12     | 3.11%   |
| Kingston                  | 7         | 10     | 2.72%   |
| HGST                      | 7         | 7      | 2.72%   |
| Hitachi                   | 6         | 8      | 2.33%   |
| Micron Technology         | 5         | 8      | 1.95%   |
| KingSpec                  | 4         | 4      | 1.56%   |
| ASMT                      | 3         | 3      | 1.17%   |
| A-DATA Technology         | 3         | 3      | 1.17%   |
| Team                      | 2         | 2      | 0.78%   |
| Micron/Crucial Technology | 2         | 2      | 0.78%   |
| KIOXIA                    | 2         | 3      | 0.78%   |
| China                     | 2         | 2      | 0.78%   |
| Apple                     | 2         | 2      | 0.78%   |
| XPG                       | 1         | 1      | 0.39%   |
| Transcend                 | 1         | 1      | 0.39%   |
| TO Exter                  | 1         | 1      | 0.39%   |
| Star Drive                | 1         | 1      | 0.39%   |
| Silicon Motion            | 1         | 2      | 0.39%   |
| ROG                       | 1         | 1      | 0.39%   |
| Phison                    | 1         | 1      | 0.39%   |
| LITEONIT                  | 1         | 3      | 0.39%   |
| LITEON                    | 1         | 1      | 0.39%   |
| KINGBANK                  | 1         | 1      | 0.39%   |
| Hewlett-Packard           | 1         | 3      | 0.39%   |
| Fujitsu                   | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel NVMe SSD Drive 512GB           | 6         | 2.24%   |
| Samsung SSD 850 EVO 500GB            | 5         | 1.87%   |
| Samsung NVMe SSD Drive 512GB         | 5         | 1.87%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.49%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 1.12%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.12%   |
| Seagate ST9500420AS 500GB            | 3         | 1.12%   |
| Samsung SSD 860 EVO 500GB            | 3         | 1.12%   |
| Samsung SSD 850 EVO 1TB              | 3         | 1.12%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 1.12%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.12%   |
| Crucial CT240BX200SSD1 240GB         | 3         | 1.12%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.75%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.75%   |
| WDC WD10SPZX-22Z10T1 1TB             | 2         | 0.75%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 0.75%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.75%   |
| Unknown MMC Card  64GB               | 2         | 0.75%   |
| Unknown MMC Card  2GB                | 2         | 0.75%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.75%   |
| Toshiba NVMe SSD Drive 256GB         | 2         | 0.75%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.75%   |
| SK Hynix NVMe SSD Drive 256GB        | 2         | 0.75%   |
| Seagate ST9500325AS 500GB            | 2         | 0.75%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.75%   |
| Seagate Expansion+ 2TB               | 2         | 0.75%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.75%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 0.75%   |
| Sandisk NVMe SSD Drive 1024GB        | 2         | 0.75%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.75%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.75%   |
| Samsung MZVL21T0HCLR-00B00 1TB       | 2         | 0.75%   |
| Micron/Crucial NVMe SSD Drive 500GB  | 2         | 0.75%   |
| Kingston SV300S37A240G 240GB SSD     | 2         | 0.75%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.75%   |
| KingSpec Q-180 180GB                 | 2         | 0.75%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.75%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 0.75%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.75%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.75%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.75%   |
| XPG NVMe SSD Drive 1024GB            | 1         | 0.37%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.37%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.37%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.37%   |
| WDC WD3200BEKX-75B7WT0 320GB         | 1         | 0.37%   |
| WDC WD2500BEVT-80A23T0 250GB         | 1         | 0.37%   |
| WDC WD20SPZX-21UA7T0 2TB             | 1         | 0.37%   |
| WDC WD20SPZX-08UA7 2TB               | 1         | 0.37%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.37%   |
| WDC WD10SPZX-21Z 1TB                 | 1         | 0.37%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.37%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.37%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.37%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 0.37%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB   | 1         | 0.37%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 39     | 41.18%  |
| WDC                 | 22        | 33     | 25.88%  |
| Toshiba             | 10        | 15     | 11.76%  |
| HGST                | 7         | 7      | 8.24%   |
| Hitachi             | 6         | 8      | 7.06%   |
| Samsung Electronics | 2         | 2      | 2.35%   |
| Fujitsu             | 1         | 1      | 1.18%   |
| ASMT                | 1         | 1      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 30     | 25%     |
| Crucial             | 17        | 32     | 18.48%  |
| SanDisk             | 11        | 11     | 11.96%  |
| Kingston            | 6         | 9      | 6.52%   |
| Micron Technology   | 5         | 8      | 5.43%   |
| KingSpec            | 4         | 4      | 4.35%   |
| WDC                 | 3         | 10     | 3.26%   |
| Toshiba             | 3         | 4      | 3.26%   |
| SK Hynix            | 3         | 3      | 3.26%   |
| A-DATA Technology   | 3         | 3      | 3.26%   |
| Team                | 2         | 2      | 2.17%   |
| Seagate             | 2         | 2      | 2.17%   |
| China               | 2         | 2      | 2.17%   |
| Transcend           | 1         | 1      | 1.09%   |
| TO Exter            | 1         | 1      | 1.09%   |
| LITEONIT            | 1         | 3      | 1.09%   |
| LITEON              | 1         | 1      | 1.09%   |
| Intel               | 1         | 2      | 1.09%   |
| Hewlett-Packard     | 1         | 3      | 1.09%   |
| ASMT                | 1         | 1      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 87        | 133    | 35.51%  |
| HDD     | 81        | 107    | 33.06%  |
| NVMe    | 67        | 84     | 27.35%  |
| MMC     | 8         | 12     | 3.27%   |
| Unknown | 2         | 3      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 156       | 232    | 65%     |
| NVMe | 67        | 84     | 27.92%  |
| SAS  | 9         | 11     | 3.75%   |
| MMC  | 8         | 12     | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 113       | 167    | 66.47%  |
| 0.51-1.0   | 48        | 63     | 28.24%  |
| 1.01-2.0   | 8         | 9      | 4.71%   |
| 2.01-3.0   | 1         | 1      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 28.83%  |
| 251-500        | 59        | 26.58%  |
| 501-1000       | 33        | 14.86%  |
| 1001-2000      | 16        | 7.21%   |
| 1-20           | 14        | 6.31%   |
| 51-100         | 14        | 6.31%   |
| 21-50          | 7         | 3.15%   |
| Unknown        | 7         | 3.15%   |
| More than 3000 | 4         | 1.8%    |
| 2001-3000      | 4         | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 92        | 38.82%  |
| 21-50          | 49        | 20.68%  |
| 101-250        | 33        | 13.92%  |
| 51-100         | 25        | 10.55%  |
| 251-500        | 14        | 5.91%   |
| 501-1000       | 13        | 5.49%   |
| Unknown        | 7         | 2.95%   |
| More than 3000 | 2         | 0.84%   |
| 2001-3000      | 1         | 0.42%   |
| 1001-2000      | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKX-00HPJT0 752GB                        | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 6.67%   |
| SK Hynix SC308 SATA 128GB SSD                       | 1         | 1      | 6.67%   |
| SK Hynix BC501 HFM512GDJTNG-8310A 512GB             | 1         | 1      | 6.67%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 6.67%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 6.67%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 6.67%   |
| Hitachi HTS545032B9SA00 320GB                       | 1         | 1      | 6.67%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 6.67%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 6.67%   |
| Crucial CT275MX300SSD1 275GB                        | 1         | 1      | 6.67%   |
| ASMT ASM105x 240GB SSD                              | 1         | 1      | 6.67%   |
| Apple HDD HTS547550A9E384 500GB                     | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 3      | 20%     |
| SK Hynix          | 2         | 2      | 13.33%  |
| Hitachi           | 2         | 2      | 13.33%  |
| HGST              | 2         | 2      | 13.33%  |
| WDC               | 1         | 1      | 6.67%   |
| Toshiba           | 1         | 1      | 6.67%   |
| Micron Technology | 1         | 1      | 6.67%   |
| Crucial           | 1         | 1      | 6.67%   |
| ASMT              | 1         | 1      | 6.67%   |
| Apple             | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| Hitachi | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| Toshiba | 1         | 1      | 10%     |
| Apple   | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 66.67%  |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 1         | 1      | 6.67%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 147       | 237    | 64.76%  |
| Works    | 65        | 87     | 28.63%  |
| Malfunc  | 15        | 15     | 6.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 161       | 64.4%   |
| Samsung Electronics          | 23        | 9.2%    |
| AMD                          | 23        | 9.2%    |
| Toshiba America Info Systems | 11        | 4.4%    |
| SK Hynix                     | 10        | 4%      |
| Sandisk                      | 7         | 2.8%    |
| Nvidia                       | 4         | 1.6%    |
| Micron/Crucial Technology    | 4         | 1.6%    |
| Phison Electronics           | 2         | 0.8%    |
| KIOXIA                       | 2         | 0.8%    |
| Silicon Motion               | 1         | 0.4%    |
| Kingston Technology Company  | 1         | 0.4%    |
| ADATA Technology             | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 24        | 9.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 20        | 7.6%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 20        | 7.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 18        | 6.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 15        | 5.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 9         | 3.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 3.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 3.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 7         | 2.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 6         | 2.28%   |
| Intel SSD 660P Series                                                                  | 6         | 2.28%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 6         | 2.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 2.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 6         | 2.28%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 4         | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 1.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 1.14%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 3         | 1.14%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 1.14%   |
| SK Hynix Non-Volatile memory controller                                                | 3         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 3         | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 1.14%   |
| Nvidia MCP79 AHCI Controller                                                           | 3         | 1.14%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 3         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 1.14%   |
| Intel Non-Volatile memory controller                                                   | 3         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 1.14%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 2         | 0.76%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                            | 2         | 0.76%   |
| SK Hynix Gold P31 SSD                                                                  | 2         | 0.76%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.76%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 0.76%   |
| Phison E12 NVMe Controller                                                             | 2         | 0.76%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 0.76%   |
| SK Hynix BC511                                                                         | 1         | 0.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.38%   |
| Sandisk WD Black NVMe SSD                                                              | 1         | 0.38%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.38%   |
| Samsung Electronics SATA controller                                                    | 1         | 0.38%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.38%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.38%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.38%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.38%   |
| Intel SATA Controller [RAID mode]                                                      | 1         | 0.38%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 1         | 0.38%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.38%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 0.38%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 1         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 162       | 63.78%  |
| NVMe | 68        | 26.77%  |
| RAID | 13        | 5.12%   |
| IDE  | 11        | 4.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 185       | 85.65%  |
| AMD    | 31        | 14.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 2.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 2.31%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 2.31%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 1.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.85%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.39%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.39%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.39%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 1.39%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 1.39%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 1.39%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.39%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.39%   |
| Intel Pentium M processor 2.00GHz             | 2         | 0.93%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 0.93%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.93%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 2         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.93%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.93%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 0.93%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.93%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.93%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 2         | 0.93%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 0.93%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 2         | 0.93%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.93%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 0.93%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.46%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.46%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.46%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.46%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.46%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.46%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.46%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.46%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.46%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 71        | 32.87%  |
| Intel Core i7                  | 61        | 28.24%  |
| Intel Core i3                  | 12        | 5.56%   |
| Intel Core 2 Duo               | 12        | 5.56%   |
| Intel Celeron                  | 11        | 5.09%   |
| Other                          | 8         | 3.7%    |
| AMD Ryzen 5                    | 7         | 3.24%   |
| AMD A6                         | 4         | 1.85%   |
| Intel Atom                     | 3         | 1.39%   |
| AMD Ryzen 7                    | 3         | 1.39%   |
| AMD E2                         | 3         | 1.39%   |
| AMD A8                         | 3         | 1.39%   |
| Intel Pentium M                | 2         | 0.93%   |
| Intel Core i9                  | 2         | 0.93%   |
| AMD Ryzen 9                    | 2         | 0.93%   |
| Intel Pentium                  | 1         | 0.46%   |
| Intel Genuine                  | 1         | 0.46%   |
| Intel Core m7                  | 1         | 0.46%   |
| Intel Celeron Dual-Core        | 1         | 0.46%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.46%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.46%   |
| AMD Ryzen 7 PRO                | 1         | 0.46%   |
| AMD Ryzen 3                    | 1         | 0.46%   |
| AMD E1                         | 1         | 0.46%   |
| AMD E                          | 1         | 0.46%   |
| AMD A4                         | 1         | 0.46%   |
| AMD A10                        | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 120       | 55.56%  |
| 4      | 65        | 30.09%  |
| 6      | 15        | 6.94%   |
| 8      | 10        | 4.63%   |
| 1      | 5         | 2.31%   |
| 10     | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 216       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 167       | 77.31%  |
| 1      | 49        | 22.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 207       | 94.09%  |
| Unknown        | 10        | 4.55%   |
| 32-bit         | 3         | 1.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 23.77%  |
| 0x206a7    | 23        | 10.31%  |
| 0x306a9    | 18        | 8.07%   |
| 0x406e3    | 10        | 4.48%   |
| 0x806ec    | 9         | 4.04%   |
| 0x806ea    | 9         | 4.04%   |
| 0x40651    | 6         | 2.69%   |
| 0x30678    | 6         | 2.69%   |
| 0x20655    | 6         | 2.69%   |
| 0x10676    | 6         | 2.69%   |
| 0x806e9    | 5         | 2.24%   |
| 0x306d4    | 5         | 2.24%   |
| 0x306c3    | 5         | 2.24%   |
| 0xa0652    | 4         | 1.79%   |
| 0x906ea    | 4         | 1.79%   |
| 0x1067a    | 4         | 1.79%   |
| 0x07030105 | 4         | 1.79%   |
| 0x906e9    | 3         | 1.35%   |
| 0x806d1    | 3         | 1.35%   |
| 0x506e3    | 3         | 1.35%   |
| 0x08108102 | 3         | 1.35%   |
| 0x6fd      | 2         | 0.9%    |
| 0x6d8      | 2         | 0.9%    |
| 0x506c9    | 2         | 0.9%    |
| 0x106ca    | 2         | 0.9%    |
| 0x0a50000c | 2         | 0.9%    |
| 0x08608103 | 2         | 0.9%    |
| 0x08600106 | 2         | 0.9%    |
| 0x08108109 | 2         | 0.9%    |
| 0x0700010f | 2         | 0.9%    |
| 0x06006705 | 2         | 0.9%    |
| 0x05000119 | 2         | 0.9%    |
| 0x806eb    | 1         | 0.45%   |
| 0x806c2    | 1         | 0.45%   |
| 0x806c1    | 1         | 0.45%   |
| 0x706e5    | 1         | 0.45%   |
| 0x6fb      | 1         | 0.45%   |
| 0x106e5    | 1         | 0.45%   |
| 0x106c2    | 1         | 0.45%   |
| 0x08608102 | 1         | 0.45%   |
| 0x07030104 | 1         | 0.45%   |
| 0x06006118 | 1         | 0.45%   |
| 0x06001119 | 1         | 0.45%   |
| 0x02000032 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 43        | 19.91%  |
| SandyBridge     | 26        | 12.04%  |
| IvyBridge       | 22        | 10.19%  |
| Skylake         | 17        | 7.87%   |
| Haswell         | 13        | 6.02%   |
| Penryn          | 11        | 5.09%   |
| Westmere        | 9         | 4.17%   |
| Silvermont      | 8         | 3.7%    |
| CometLake       | 7         | 3.24%   |
| Broadwell       | 7         | 3.24%   |
| Zen+            | 6         | 2.78%   |
| Puma            | 6         | 2.78%   |
| IceLake         | 6         | 2.78%   |
| Excavator       | 4         | 1.85%   |
| Zen 3           | 3         | 1.39%   |
| TigerLake       | 3         | 1.39%   |
| Goldmont        | 3         | 1.39%   |
| Core            | 3         | 1.39%   |
| Bonnell         | 3         | 1.39%   |
| Unknown         | 3         | 1.39%   |
| Zen 2           | 2         | 0.93%   |
| P6              | 2         | 0.93%   |
| Nehalem         | 2         | 0.93%   |
| Jaguar          | 2         | 0.93%   |
| Bobcat          | 2         | 0.93%   |
| Piledriver      | 1         | 0.46%   |
| K8 Hammer       | 1         | 0.46%   |
| K8 & K10 hybrid | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 163       | 59.93%  |
| Nvidia | 55        | 20.22%  |
| AMD    | 54        | 19.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 22        | 7.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 19        | 6.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 11        | 3.85%   |
| Intel UHD Graphics 620                                                                | 10        | 3.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 8         | 2.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 8         | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                   | 8         | 2.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 2.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 7         | 2.45%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 7         | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 2.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 1.75%   |
| Intel HD Graphics 630                                                                 | 5         | 1.75%   |
| Intel HD Graphics 5500                                                                | 5         | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 5         | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 5         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.4%    |
| Intel HD Graphics 620                                                                 | 4         | 1.4%    |
| Intel HD Graphics 530                                                                 | 4         | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 1.4%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 4         | 1.4%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 4         | 1.4%    |
| Nvidia GK107M [GeForce GT 650M]                                                       | 3         | 1.05%   |
| Nvidia C79 [GeForce 9400M]                                                            | 3         | 1.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 3         | 1.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 1.05%   |
| Intel HD Graphics 500                                                                 | 3         | 1.05%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 3         | 1.05%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 3         | 1.05%   |
| AMD Lucienne                                                                          | 3         | 1.05%   |
| AMD Cezanne                                                                           | 3         | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 0.7%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 2         | 0.7%    |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 0.7%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 2         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.7%    |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 2         | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 0.7%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 0.7%    |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.7%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller               | 2         | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 0.7%    |
| AMD Renoir                                                                            | 2         | 0.7%    |
| AMD Mullins [Radeon R2 Graphics]                                                      | 2         | 0.7%    |
| AMD Mars [Radeon HD 8730M]                                                            | 2         | 0.7%    |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 2         | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.35%   |
| Nvidia TU117M                                                                         | 1         | 0.35%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.35%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                 | 1         | 0.35%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                | 1         | 0.35%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 1         | 0.35%   |
| Nvidia GT218M [NVS 3100M]                                                             | 1         | 0.35%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 0.35%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 0.35%   |
| Nvidia GP108GLM [Quadro P520]                                                         | 1         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 51.39%  |
| Intel + Nvidia | 38        | 17.59%  |
| 1 x AMD        | 28        | 12.96%  |
| Intel + AMD    | 14        | 6.48%   |
| 1 x Nvidia     | 12        | 5.56%   |
| 2 x AMD        | 8         | 3.7%    |
| AMD + Nvidia   | 4         | 1.85%   |
| 2 x Nvidia     | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 180       | 82.95%  |
| Proprietary | 30        | 13.82%  |
| Unknown     | 7         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 62.44%  |
| 0.01-0.5   | 24        | 10.86%  |
| 1.01-2.0   | 23        | 10.41%  |
| 0.51-1.0   | 15        | 6.79%   |
| 3.01-4.0   | 8         | 3.62%   |
| 7.01-8.0   | 5         | 2.26%   |
| 5.01-6.0   | 5         | 2.26%   |
| 2.01-3.0   | 2         | 0.9%    |
| 8.01-16.0  | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 17.6%   |
| LG Display              | 39        | 15.6%   |
| Chimei Innolux          | 32        | 12.8%   |
| Samsung Electronics     | 28        | 11.2%   |
| BOE                     | 16        | 6.4%    |
| Sharp                   | 13        | 5.2%    |
| Dell                    | 12        | 4.8%    |
| Chi Mei Optoelectronics | 12        | 4.8%    |
| AOC                     | 9         | 3.6%    |
| Goldstar                | 8         | 3.2%    |
| PANDA                   | 4         | 1.6%    |
| Apple                   | 4         | 1.6%    |
| InfoVision              | 3         | 1.2%    |
| Hewlett-Packard         | 3         | 1.2%    |
| ViewSonic               | 2         | 0.8%    |
| Quanta Display          | 2         | 0.8%    |
| Philips                 | 2         | 0.8%    |
| InnoLux Display         | 2         | 0.8%    |
| Acer                    | 2         | 0.8%    |
| TMX                     | 1         | 0.4%    |
| Sony                    | 1         | 0.4%    |
| PRISM+                  | 1         | 0.4%    |
| MiTAC                   | 1         | 0.4%    |
| Mi                      | 1         | 0.4%    |
| LG Philips              | 1         | 0.4%    |
| Lenovo                  | 1         | 0.4%    |
| IBM                     | 1         | 0.4%    |
| HYD                     | 1         | 0.4%    |
| HannStar                | 1         | 0.4%    |
| Denver                  | 1         | 0.4%    |
| CPT                     | 1         | 0.4%    |
| Ancor Communications    | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 1.56%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 1.56%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 1.17%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 1.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.17%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 1.17%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.17%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.78%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.78%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch              | 2         | 0.78%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 2         | 0.78%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 0.78%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 2         | 0.78%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 2         | 0.78%   |
| Dell U3818DW DELA0F3 3840x1600 880x367mm 37.5-inch                       | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.78%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO41ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.78%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                         | 2         | 0.78%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 2         | 0.78%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch            | 1         | 0.39%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch             | 1         | 0.39%   |
| TMX TL140BDXP02-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.39%   |
| Sony TV SNYA401 1920x1080 1600x900mm 72.3-inch                           | 1         | 0.39%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                  | 1         | 0.39%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 610x350mm 27.7-inch        | 1         | 0.39%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch    | 1         | 0.39%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch        | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3157 1440x900 303x190mm 14.1-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC304B 1440x900 367x230mm 17.1-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4A51 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88        | 37.77%  |
| 1366x768 (WXGA)    | 73        | 31.33%  |
| 1600x900 (HD+)     | 14        | 6.01%   |
| 1280x800 (WXGA)    | 12        | 5.15%   |
| 3840x2160 (4K)     | 9         | 3.86%   |
| 2560x1440 (QHD)    | 8         | 3.43%   |
| 3440x1440          | 6         | 2.58%   |
| 3200x1800 (QHD+)   | 4         | 1.72%   |
| 1440x900 (WXGA+)   | 4         | 1.72%   |
| 1024x600           | 3         | 1.29%   |
| 3840x1600          | 2         | 0.86%   |
| 3456x2160          | 2         | 0.86%   |
| 2560x1600          | 2         | 0.86%   |
| 1280x1024 (SXGA)   | 2         | 0.86%   |
| 3840x2400          | 1         | 0.43%   |
| 1920x1280          | 1         | 0.43%   |
| 1920x1200 (WUXGA)  | 1         | 0.43%   |
| 1680x1050 (WSXGA+) | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 105       | 42%     |
| 13      | 35        | 14%     |
| 14      | 28        | 11.2%   |
| 17      | 15        | 6%      |
| 27      | 14        | 5.6%    |
| 23      | 7         | 2.8%    |
| 21      | 5         | 2%      |
| 11      | 5         | 2%      |
| 10      | 5         | 2%      |
| 34      | 4         | 1.6%    |
| 18      | 3         | 1.2%    |
| 16      | 3         | 1.2%    |
| 12      | 3         | 1.2%    |
| 72      | 2         | 0.8%    |
| 37      | 2         | 0.8%    |
| 33      | 2         | 0.8%    |
| 24      | 2         | 0.8%    |
| 22      | 2         | 0.8%    |
| 19      | 2         | 0.8%    |
| Unknown | 2         | 0.8%    |
| 84      | 1         | 0.4%    |
| 31      | 1         | 0.4%    |
| 25      | 1         | 0.4%    |
| 20      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 153       | 61.69%  |
| 201-300     | 28        | 11.29%  |
| 501-600     | 21        | 8.47%   |
| 351-400     | 20        | 8.06%   |
| 401-500     | 11        | 4.44%   |
| 701-800     | 6         | 2.42%   |
| 1501-2000   | 3         | 1.21%   |
| 801-900     | 2         | 0.81%   |
| 601-700     | 2         | 0.81%   |
| Unknown     | 2         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 181       | 83.03%  |
| 16/10   | 23        | 10.55%  |
| 21/9    | 8         | 3.67%   |
| 5/4     | 2         | 0.92%   |
| 3/2     | 2         | 0.92%   |
| Unknown | 2         | 0.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 103       | 40.87%  |
| 81-90          | 52        | 20.63%  |
| 301-350        | 14        | 5.56%   |
| 201-250        | 14        | 5.56%   |
| 121-130        | 14        | 5.56%   |
| 71-80          | 13        | 5.16%   |
| 351-500        | 7         | 2.78%   |
| 51-60          | 5         | 1.98%   |
| 41-50          | 5         | 1.98%   |
| 151-200        | 5         | 1.98%   |
| 111-120        | 4         | 1.59%   |
| More than 1000 | 3         | 1.19%   |
| 61-70          | 3         | 1.19%   |
| 141-150        | 3         | 1.19%   |
| 501-1000       | 2         | 0.79%   |
| Unknown        | 2         | 0.79%   |
| 251-300        | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 92        | 37.4%   |
| 121-160       | 88        | 35.77%  |
| 51-100        | 39        | 15.85%  |
| 161-240       | 12        | 4.88%   |
| More than 240 | 11        | 4.47%   |
| 1-50          | 2         | 0.81%   |
| Unknown       | 2         | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 174       | 77.33%  |
| 2     | 38        | 16.89%  |
| 0     | 7         | 3.11%   |
| 3     | 5         | 2.22%   |
| 4     | 1         | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 126       | 36.42%  |
| Realtek Semiconductor             | 107       | 30.92%  |
| Qualcomm Atheros                  | 49        | 14.16%  |
| Broadcom                          | 19        | 5.49%   |
| Ralink                            | 6         | 1.73%   |
| Hewlett-Packard                   | 6         | 1.73%   |
| Broadcom Limited                  | 5         | 1.45%   |
| Nvidia                            | 4         | 1.16%   |
| TP-Link                           | 3         | 0.87%   |
| Lenovo                            | 3         | 0.87%   |
| DisplayLink                       | 3         | 0.87%   |
| Sierra Wireless                   | 2         | 0.58%   |
| MEDIATEK                          | 2         | 0.58%   |
| JMicron Technology                | 2         | 0.58%   |
| Samsung Electronics               | 1         | 0.29%   |
| OPPO Electronics                  | 1         | 0.29%   |
| Marvell Technology Group          | 1         | 0.29%   |
| Lite-On Technology                | 1         | 0.29%   |
| ICS Advent                        | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| Dell                              | 1         | 0.29%   |
| Attansic Technology               | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 16.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 3.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 3.27%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 3.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 2.34%   |
| Intel Wireless 7260                                               | 10        | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.1%    |
| Intel Wireless 8260                                               | 9         | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.87%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.87%   |
| Intel Wireless 3165                                               | 7         | 1.64%   |
| Intel Wireless 7265                                               | 6         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.17%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.17%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 1.17%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.17%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.17%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.93%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 4         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.7%    |
| Nvidia MCP79 Ethernet                                             | 3         | 0.7%    |
| Intel Wireless-AC 9260                                            | 3         | 0.7%    |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.7%    |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.7%    |
| HP lt4112 Gobi 4G Module Network Device                           | 3         | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.7%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 2         | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.47%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.47%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.47%   |
| Intel Ethernet controller                                         | 2         | 0.47%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.47%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 122       | 53.74%  |
| Qualcomm Atheros      | 43        | 18.94%  |
| Realtek Semiconductor | 24        | 10.57%  |
| Broadcom              | 16        | 7.05%   |
| Ralink                | 6         | 2.64%   |
| Broadcom Limited      | 5         | 2.2%    |
| TP-Link               | 3         | 1.32%   |
| Hewlett-Packard       | 3         | 1.32%   |
| MEDIATEK              | 2         | 0.88%   |
| Sierra Wireless       | 1         | 0.44%   |
| Lite-On Technology    | 1         | 0.44%   |
| Dell                  | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14        | 6.14%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 5.7%    |
| Intel Wireless 7260                                            | 10        | 4.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 3.95%   |
| Intel Wireless 8260                                            | 9         | 3.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 3.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 3.51%   |
| Intel Wireless 8265 / 8275                                     | 8         | 3.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 3.51%   |
| Intel Wireless 3165                                            | 7         | 3.07%   |
| Intel Wireless 7265                                            | 6         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.19%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 2.19%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 2.19%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 2.19%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.32%   |
| Intel Wireless-AC 9260                                         | 3         | 1.32%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.32%   |
| HP lt4112 Gobi 4G Module Network Device                        | 3         | 1.32%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 2         | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.88%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.88%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.44%   |
| Sierra Wireless EM7305                                         | 1         | 0.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.44%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.44%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1         | 0.44%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 0.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.44%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 0.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.44%   |
| Lite-On BCM4318 [AirForce One 54g] 802.11g WLAN Controller     | 1         | 0.44%   |
| Intel Wireless 3160                                            | 1         | 0.44%   |
| Intel WiFi Link 5100                                           | 1         | 0.44%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.44%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 0.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 0.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.44%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection      | 1         | 0.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 98        | 50.52%  |
| Intel                    | 58        | 29.9%   |
| Qualcomm Atheros         | 13        | 6.7%    |
| Broadcom                 | 6         | 3.09%   |
| Nvidia                   | 4         | 2.06%   |
| Lenovo                   | 3         | 1.55%   |
| DisplayLink              | 3         | 1.55%   |
| JMicron Technology       | 2         | 1.03%   |
| Sierra Wireless          | 1         | 0.52%   |
| Samsung Electronics      | 1         | 0.52%   |
| OPPO Electronics         | 1         | 0.52%   |
| Marvell Technology Group | 1         | 0.52%   |
| ICS Advent               | 1         | 0.52%   |
| Attansic Technology      | 1         | 0.52%   |
| ASIX Electronics         | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 69        | 35.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 16        | 8.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 6.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 5.13%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 2.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 2.05%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 2.05%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 2.05%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 1.54%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.54%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 1.54%   |
| Intel 82577LC Gigabit Network Connection                                       | 3         | 1.54%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.03%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 1.03%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 1.03%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.03%   |
| Intel Ethernet controller                                                      | 2         | 1.03%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.03%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 1.03%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.03%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 1.03%   |
| Sierra Wireless EM7345 4G LTE                                                  | 1         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.51%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.51%   |
| OPPO SDM665-IDP _SN:18689828                                                   | 1         | 0.51%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.51%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]                    | 1         | 0.51%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.51%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.51%   |
| ICS Advent USB 10/100 LAN                                                      | 1         | 0.51%   |
| DisplayLink Targus USB3.0 DV2K Dock w Power                                    | 1         | 0.51%   |
| DisplayLink Plugable UD-3900                                                   | 1         | 0.51%   |
| DisplayLink Dell Universal Dock D6000                                          | 1         | 0.51%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.51%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 1         | 0.51%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.51%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 1         | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 213       | 52.85%  |
| Ethernet | 185       | 45.91%  |
| Modem    | 5         | 1.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 192       | 66.44%  |
| Ethernet | 97        | 33.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 168       | 77.78%  |
| 1     | 44        | 20.37%  |
| 3     | 2         | 0.93%   |
| 0     | 2         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 192       | 87.67%  |
| Yes  | 27        | 12.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 90        | 51.43%  |
| Qualcomm Atheros Communications | 17        | 9.71%   |
| Realtek Semiconductor           | 10        | 5.71%   |
| Lite-On Technology              | 9         | 5.14%   |
| Hewlett-Packard                 | 9         | 5.14%   |
| Foxconn / Hon Hai               | 9         | 5.14%   |
| Broadcom                        | 7         | 4%      |
| IMC Networks                    | 6         | 3.43%   |
| Apple                           | 5         | 2.86%   |
| Toshiba                         | 3         | 1.71%   |
| Ralink Technology               | 3         | 1.71%   |
| Dell                            | 2         | 1.14%   |
| ASUSTek Computer                | 2         | 1.14%   |
| Realtek                         | 1         | 0.57%   |
| Ralink                          | 1         | 0.57%   |
| Edimax Technology               | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 39        | 22.29%  |
| Intel AX200 Bluetooth                                                               | 13        | 7.43%   |
| Intel AX201 Bluetooth                                                               | 12        | 6.86%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 11        | 6.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 5.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 4%      |
| Realtek Bluetooth Radio                                                             | 5         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 2.86%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 2.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.29%   |
| Lite-On Bluetooth Device                                                            | 4         | 2.29%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.29%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.71%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.71%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.14%   |
| Intel Bluetooth Device                                                              | 2         | 1.14%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.14%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.14%   |
| Foxconn / Hon Hai Acer Module                                                       | 2         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.14%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.57%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.57%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.57%   |
| Realtek 802.11n WLAN Adapter                                                        | 1         | 0.57%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.57%   |
| Ralink CSR BS8510                                                                   | 1         | 0.57%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.57%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.57%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.57%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.57%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.57%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.57%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.57%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.57%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter                             | 1         | 0.57%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.57%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.57%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.57%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.57%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.57%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.57%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 0.57%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.57%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 181       | 65.58%  |
| AMD                       | 41        | 14.86%  |
| Nvidia                    | 34        | 12.32%  |
| Realtek Semiconductor     | 3         | 1.09%   |
| Logitech                  | 3         | 1.09%   |
| Lenovo                    | 3         | 1.09%   |
| Texas Instruments         | 1         | 0.36%   |
| SteelSeries ApS           | 1         | 0.36%   |
| Sennheiser Communications | 1         | 0.36%   |
| Plantronics               | 1         | 0.36%   |
| Micro Star International  | 1         | 0.36%   |
| Hewlett-Packard           | 1         | 0.36%   |
| GYROCOM C&C               | 1         | 0.36%   |
| Google                    | 1         | 0.36%   |
| CMX Systems               | 1         | 0.36%   |
| ClearOne Communications   | 1         | 0.36%   |
| Belkin Components         | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 27        | 8.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 26        | 8.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 22        | 6.81%   |
| AMD Family 17h/19h HD Audio Controller                                            | 14        | 4.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 11        | 3.41%   |
| AMD FCH Azalia Controller                                                         | 10        | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                        | 9         | 2.79%   |
| AMD Kabini HDMI/DP Audio                                                          | 9         | 2.79%   |
| Intel Haswell-ULT HD Audio Controller                                             | 8         | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 8         | 2.48%   |
| Intel 8 Series HD Audio Controller                                                | 8         | 2.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 7         | 2.17%   |
| Intel Broadwell-U Audio Controller                                                | 7         | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 7         | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 7         | 2.17%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 6         | 1.86%   |
| Intel Comet Lake PCH cAVS                                                         | 6         | 1.86%   |
| Intel CM238 HD Audio Controller                                                   | 6         | 1.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6         | 1.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5         | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5         | 1.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5         | 1.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4         | 1.24%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 4         | 1.24%   |
| Realtek Semiconductor USB Audio                                                   | 3         | 0.93%   |
| Nvidia MCP79 High Definition Audio                                                | 3         | 0.93%   |
| Nvidia Audio device                                                               | 3         | 0.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 3         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 3         | 0.93%   |
| AMD High Definition Audio Controller                                              | 3         | 0.93%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 0.62%   |
| Nvidia High Definition Audio Controller                                           | 2         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2         | 0.62%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 0.62%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 2         | 0.62%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 0.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 0.62%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 2         | 0.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.62%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.31%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                     | 1         | 0.31%   |
| Sennheiser Communications SC60 for Lync                                           | 1         | 0.31%   |
| Plantronics C510                                                                  | 1         | 0.31%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.31%   |
| Nvidia stereo controller                                                          | 1         | 0.31%   |
| Nvidia MCP89 High Definition Audio                                                | 1         | 0.31%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 0.31%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.31%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1         | 0.31%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1         | 0.31%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.31%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 35        | 25.93%  |
| Samsung Electronics | 35        | 25.93%  |
| Micron Technology   | 19        | 14.07%  |
| Crucial             | 14        | 10.37%  |
| Kingston            | 9         | 6.67%   |
| Unknown             | 4         | 2.96%   |
| A-DATA Technology   | 4         | 2.96%   |
| ELPIDA              | 3         | 2.22%   |
| Team                | 2         | 1.48%   |
| Shenzhen Mic        | 2         | 1.48%   |
| Ramaxel Technology  | 2         | 1.48%   |
| Transcend           | 1         | 0.74%   |
| Strontium           | 1         | 0.74%   |
| Neo Forza           | 1         | 0.74%   |
| Nanya Technology    | 1         | 0.74%   |
| Corsair             | 1         | 0.74%   |
| Apacer              | 1         | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 2.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 2.84%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 2.13%   |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s       | 3         | 2.13%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 1.42%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 2         | 1.42%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.42%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1.42%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.42%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 1.42%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s      | 2         | 1.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.42%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.42%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 1.42%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s          | 2         | 1.42%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.42%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.42%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s         | 2         | 1.42%   |
| Unknown RAM Module 8192MB SODIMM DDR3                            | 1         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.71%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.71%   |
| Transcend RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.71%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.71%   |
| Team RAM TEAMGROUP-SD4-2400 8192MB SODIMM DDR4 8400MT/s          | 1         | 0.71%   |
| Team RAM TEAMGROUP-SD4-2400 16GB Chip DDR4 2133MT/s              | 1         | 0.71%   |
| Strontium RAM SRT4G86S1-H9H 4GB SODIMM DDR3 1333MT/s             | 1         | 0.71%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.71%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.71%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.71%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 0.71%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 0.71%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR2 667MT/s         | 1         | 0.71%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 1         | 0.71%   |
| SK Hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.71%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1334MT/s        | 1         | 0.71%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB Row Of Chips DDR4 2667MT/s  | 1         | 0.71%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.71%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.71%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 0.71%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.71%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.71%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 0.71%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1067MT/s                   | 1         | 0.71%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.71%   |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM DDR3 1067MT/s         | 1         | 0.71%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 45.54%  |
| DDR3   | 42        | 41.58%  |
| DDR2   | 5         | 4.95%   |
| LPDDR3 | 4         | 3.96%   |
| SDRAM  | 3         | 2.97%   |
| LPDDR4 | 1         | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 93.2%   |
| Row Of Chips | 5         | 4.85%   |
| Chip         | 2         | 1.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 40        | 37.38%  |
| 4096  | 35        | 32.71%  |
| 16384 | 17        | 15.89%  |
| 2048  | 12        | 11.21%  |
| 32768 | 3         | 2.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 27        | 24.11%  |
| 3200    | 19        | 16.96%  |
| 2667    | 19        | 16.96%  |
| 1334    | 11        | 9.82%   |
| 2133    | 7         | 6.25%   |
| 2400    | 6         | 5.36%   |
| Unknown | 4         | 3.57%   |
| 1867    | 3         | 2.68%   |
| 1333    | 3         | 2.68%   |
| 1067    | 3         | 2.68%   |
| 667     | 3         | 2.68%   |
| 800     | 2         | 1.79%   |
| 8400    | 1         | 0.89%   |
| 4267    | 1         | 0.89%   |
| 4199    | 1         | 0.89%   |
| 2048    | 1         | 0.89%   |
| 975     | 1         | 0.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 59        | 30.26%  |
| Sunplus Innovation Technology          | 18        | 9.23%   |
| IMC Networks                           | 15        | 7.69%   |
| Realtek Semiconductor                  | 14        | 7.18%   |
| Microdia                               | 14        | 7.18%   |
| Acer                                   | 14        | 7.18%   |
| Quanta                                 | 10        | 5.13%   |
| Lite-On Technology                     | 9         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.59%   |
| Suyin                                  | 6         | 3.08%   |
| Apple                                  | 5         | 2.56%   |
| Logitech                               | 4         | 2.05%   |
| Alcor Micro                            | 4         | 2.05%   |
| Syntek                                 | 3         | 1.54%   |
| Silicon Motion                         | 3         | 1.54%   |
| Primax Electronics                     | 3         | 1.54%   |
| Z-Star Microelectronics                | 1         | 0.51%   |
| Samsung Electronics                    | 1         | 0.51%   |
| Intel                                  | 1         | 0.51%   |
| Importek                               | 1         | 0.51%   |
| DigiTech                               | 1         | 0.51%   |
| AVer Information                       | 1         | 0.51%   |
| ALi                                    | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 12        | 6.15%   |
| Chicony HD WebCam                                               | 7         | 3.59%   |
| Sunplus Integrated_Webcam_HD                                    | 6         | 3.08%   |
| Sunplus HP HD Webcam [Fixed]                                    | 6         | 3.08%   |
| Microdia Integrated Webcam HD                                   | 5         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 2.56%   |
| Realtek Integrated_Webcam_HD                                    | 4         | 2.05%   |
| Realtek HP Truevision HD                                        | 4         | 2.05%   |
| IMC Networks Integrated Camera                                  | 4         | 2.05%   |
| Chicony HP HD Webcam                                            | 4         | 2.05%   |
| Chicony HP HD Camera                                            | 4         | 2.05%   |
| Apple Built-in iSight                                           | 4         | 2.05%   |
| Acer Integrated Camera                                          | 4         | 2.05%   |
| Quanta HP TrueVision HD Camera                                  | 3         | 1.54%   |
| Lite-On Integrated Camera                                       | 3         | 1.54%   |
| Chicony VGA Webcam                                              | 3         | 1.54%   |
| Chicony TOSHIBA Web Camera - HD                                 | 3         | 1.54%   |
| Suyin HP Webcam                                                 | 2         | 1.03%   |
| Realtek Integrated Webcam_HD                                    | 2         | 1.03%   |
| Primax HP HD Webcam [Fixed]                                     | 2         | 1.03%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 1.03%   |
| Lite-On HP HD Camera                                            | 2         | 1.03%   |
| Chicony USB2.0 Camera                                           | 2         | 1.03%   |
| Chicony USB2.0 0.3M UVC WebCam                                  | 2         | 1.03%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 2         | 1.03%   |
| Chicony Integrated HP HD Webcam                                 | 2         | 1.03%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.03%   |
| Alcor Micro USB 2.0 Camera                                      | 2         | 1.03%   |
| Alcor Micro Asus Integrated Webcam                              | 2         | 1.03%   |
| Acer SunplusIT Integrated Camera                                | 2         | 1.03%   |
| Acer Lenovo EasyCamera                                          | 2         | 1.03%   |
| Z-Star WebCam SC-03FFL11739P                                    | 1         | 0.51%   |
| Syntek USB 2.0 UVC PC Camera                                    | 1         | 0.51%   |
| Syntek Integrated Camera                                        | 1         | 0.51%   |
| Syntek EasyCamera                                               | 1         | 0.51%   |
| Suyin USB 2.0 Webcam Device                                     | 1         | 0.51%   |
| Suyin HP TrueVision HD                                          | 1         | 0.51%   |
| Suyin Asus Integrated Webcam                                    | 1         | 0.51%   |
| Suyin 1.3M HD WebCam                                            | 1         | 0.51%   |
| Sunplus Integrated Webcam                                       | 1         | 0.51%   |
| Sunplus HP TrueVision HD Camera                                 | 1         | 0.51%   |
| Sunplus HP Truevision HD                                        | 1         | 0.51%   |
| Sunplus ASUS Webcam                                             | 1         | 0.51%   |
| Sunplus ASUS USB2.0 Webcam                                      | 1         | 0.51%   |
| Sunplus 1.3M HD WebCam                                          | 1         | 0.51%   |
| Silicon Motion WebCam SC-13HDL12131N                            | 1         | 0.51%   |
| Silicon Motion HP Webcam-101 Integrated Camera                  | 1         | 0.51%   |
| Silicon Motion HP Webcam                                        | 1         | 0.51%   |
| Samsung Galaxy A5 (MTP)                                         | 1         | 0.51%   |
| Realtek USB Camera                                              | 1         | 0.51%   |
| Realtek Integrated Webcam                                       | 1         | 0.51%   |
| Realtek HP "Truevision HD" laptop camera                        | 1         | 0.51%   |
| Realtek HD WebCam                                               | 1         | 0.51%   |
| Quanta VGA WebCam                                               | 1         | 0.51%   |
| Quanta Laptop_Integrated_Webcam_2HDM                            | 1         | 0.51%   |
| Quanta HP Webcam                                                | 1         | 0.51%   |
| Quanta HP TrueVision HD Webcam                                  | 1         | 0.51%   |
| Quanta HP HD Camera                                             | 1         | 0.51%   |
| Quanta HD Webcam                                                | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 55.56%  |
| Synaptics                  | 11        | 17.46%  |
| AuthenTec                  | 5         | 7.94%   |
| Shenzhen Goodix Technology | 4         | 6.35%   |
| Elan Microelectronics      | 3         | 4.76%   |
| Upek                       | 2         | 3.17%   |
| LighTuning Technology      | 2         | 3.17%   |
| STMicroelectronics         | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 14.29%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 9.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 6.35%   |
| Validity Sensors VFS491                                                    | 4         | 6.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 6.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 6.35%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 3.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 3.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.17%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 3.17%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 3.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.17%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.17%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 3.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.59%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.59%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.59%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.59%   |
| AuthenTec AES2810                                                          | 1         | 1.59%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.59%   |
| AuthenTec AES1600                                                          | 1         | 1.59%   |
| Unknown                                                                    | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 50%     |
| Alcor Micro | 3         | 30%     |
| O2 Micro    | 1         | 10%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 30%     |
| Alcor Micro AU9540 Smartcard Reader            | 3         | 30%     |
| Broadcom 5880                                  | 2         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 10%     |
| Lenovo Integrated Smart Card Reader            | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 126       | 56.76%  |
| 1     | 78        | 35.14%  |
| 2     | 15        | 6.76%   |
| 6     | 2         | 0.9%    |
| 3     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 52.54%  |
| Graphics card            | 14        | 11.86%  |
| Net/wireless             | 13        | 11.02%  |
| Chipcard                 | 9         | 7.63%   |
| Multimedia controller    | 5         | 4.24%   |
| Net/ethernet             | 4         | 3.39%   |
| Communication controller | 2         | 1.69%   |
| Card reader              | 2         | 1.69%   |
| Camera                   | 2         | 1.69%   |
| Bluetooth                | 2         | 1.69%   |
| Sound                    | 1         | 0.85%   |
| Modem                    | 1         | 0.85%   |
| Flash memory             | 1         | 0.85%   |

