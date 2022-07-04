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

Total: 370

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | ROG Strix G513QY_G513QY     | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| HP        | ZBook Firefly 15 G7 Mobi... | [36fdd87ff3](https://linux-hardware.org/?probe=36fdd87ff3) | Jun 21, 2022 |
| HP        | ProBook 450 G1              | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| HP        | 550                         | [1db816d0b2](https://linux-hardware.org/?probe=1db816d0b2) | Jun 19, 2022 |
| Dell      | Precision 3571              | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell      | Precision 3571              | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| HP        | EliteBook 830 G5            | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP        | EliteBook 830 G5            | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Lenovo    | ThinkPad T460p 20FW0005A... | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| HP        | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Lenovo    | ThinkPad T460p 20FW0005A... | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Toshiba   | Satellite Pro C665          | [23fd853a45](https://linux-hardware.org/?probe=23fd853a45) | May 24, 2022 |
| Acer      | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer      | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Lenovo    | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| MSI       | Katana GF76 12UGS           | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| MSI       | Katana GF76 12UGS           | [22776216d6](https://linux-hardware.org/?probe=22776216d6) | May 22, 2022 |
| HP        | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| MSI       | Katana GF76 12UGS           | [cd50fa44c3](https://linux-hardware.org/?probe=cd50fa44c3) | May 21, 2022 |
| MSI       | Katana GF76 12UGS           | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI       | Katana GF76 12UGS           | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| Toshiba   | Satellite L50D-C            | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X515... | [60d56e6b15](https://linux-hardware.org/?probe=60d56e6b15) | May 13, 2022 |
| Alienware | x17 R2                      | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X515... | [bd6e42ac60](https://linux-hardware.org/?probe=bd6e42ac60) | May 07, 2022 |
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
| Dell      | System XPS L702X            | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple     | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| HP        | Laptop 15-bs0xx             | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
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
| Dell      | Latitude 7490               | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| HP        | Pavilion tx2500             | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP        | Pavilion tx2500             | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Dell      | Latitude 7285               | [5097e0f8c8](https://linux-hardware.org/?probe=5097e0f8c8) | Oct 14, 2021 |
| Acer      | Aspire VN7-593G             | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| HP        | Pavilion g6                 | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer      | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer      | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
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
| Dell      | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| ASUSTek   | ROG Zephyrus G14 GA401QM... | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek   | ROG Zephyrus G14 GA401QM... | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Toshiba   | Satellite C50D-C            | [dda3acac30](https://linux-hardware.org/?probe=dda3acac30) | Aug 08, 2021 |
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
| Acer      | E5-571-551U                 | [152105400d](https://linux-hardware.org/?probe=152105400d) | May 05, 2021 |
| IBM       | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
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
| HP        | OMEN by Laptop 17-an0xx     | [b1088bed99](https://linux-hardware.org/?probe=b1088bed99) | Feb 26, 2021 |
| Dell      | XPS 13 9360                 | [7de34c9abe](https://linux-hardware.org/?probe=7de34c9abe) | Feb 26, 2021 |
| HP        | ZBook 14                    | [042b4b4a48](https://linux-hardware.org/?probe=042b4b4a48) | Feb 26, 2021 |
| Dell      | Latitude E6430s             | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| Dell      | Latitude 7285               | [844392cd2c](https://linux-hardware.org/?probe=844392cd2c) | Feb 21, 2021 |
| Lenovo    | ThinkPad E490 20N8CTO1WW    | [d20e5c1f85](https://linux-hardware.org/?probe=d20e5c1f85) | Feb 15, 2021 |
| HP        | EliteBook 820 G3            | [e1a72b607e](https://linux-hardware.org/?probe=e1a72b607e) | Feb 14, 2021 |
| Dell      | Latitude E4300              | [a09ca20174](https://linux-hardware.org/?probe=a09ca20174) | Feb 14, 2021 |
| HP        | Notebook                    | [e5bc3a0317](https://linux-hardware.org/?probe=e5bc3a0317) | Feb 12, 2021 |
| MSI       | GE66 Raider 10SF            | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| HP        | 355 G2                      | [ac856a41b8](https://linux-hardware.org/?probe=ac856a41b8) | Feb 03, 2021 |
| Acer      | ES1-512-P8NA                | [c393cb6ad4](https://linux-hardware.org/?probe=c393cb6ad4) | Jan 24, 2021 |
| HP        | ProBook 450 G3              | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
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
| Toshiba   | Satellite C660              | [e7791768a3](https://linux-hardware.org/?probe=e7791768a3) | Sep 02, 2020 |
| Toshiba   | Satellite C50-B             | [186e22ea8c](https://linux-hardware.org/?probe=186e22ea8c) | Sep 01, 2020 |
| Dell      | XPS 15 9570                 | [cb17688de8](https://linux-hardware.org/?probe=cb17688de8) | Sep 01, 2020 |
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
| HP        | Pavilion dv4                | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| MSI       | GE66 Raider 10SF            | [3dcde22239](https://linux-hardware.org/?probe=3dcde22239) | Jul 25, 2020 |
| HP        | Laptop 15-dy0xxx            | [cad2dbb88f](https://linux-hardware.org/?probe=cad2dbb88f) | Jul 25, 2020 |
| HP        | ProBook 450 G5              | [a8dfd5a806](https://linux-hardware.org/?probe=a8dfd5a806) | Jul 21, 2020 |
| HP        | Laptop 15-dy0xxx            | [e471bc69b2](https://linux-hardware.org/?probe=e471bc69b2) | Jul 21, 2020 |
| Dell      | Latitude E5570              | [6408e82f4f](https://linux-hardware.org/?probe=6408e82f4f) | Jul 20, 2020 |
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
| Lenovo    | ThinkPad T520 42406BG       | [e0d0592e34](https://linux-hardware.org/?probe=e0d0592e34) | May 05, 2020 |
| HP        | ProBook 650 G1              | [ed42eb842d](https://linux-hardware.org/?probe=ed42eb842d) | May 04, 2020 |
| HP        | ProBook 650 G1              | [d29d76cb5c](https://linux-hardware.org/?probe=d29d76cb5c) | May 04, 2020 |
| HP        | Presario CQ57               | [df09ee9161](https://linux-hardware.org/?probe=df09ee9161) | Apr 26, 2020 |
| Toshiba   | TECRA Z50-A                 | [ff5b768627](https://linux-hardware.org/?probe=ff5b768627) | Apr 21, 2020 |
| Acer      | Aspire A315-21G             | [7f9e52f0dd](https://linux-hardware.org/?probe=7f9e52f0dd) | Apr 20, 2020 |
| Acer      | Aspire A315-21G             | [4409c8dae5](https://linux-hardware.org/?probe=4409c8dae5) | Apr 20, 2020 |
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
| Dell      | Latitude 7285               | [87a44ef029](https://linux-hardware.org/?probe=87a44ef029) | Nov 22, 2019 |
| Dell      | Latitude 7285               | [34937530ea](https://linux-hardware.org/?probe=34937530ea) | Nov 21, 2019 |
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
| Ubuntu 20.04                 | 34        | 13.28%  |
| Ubuntu 18.04                 | 15        | 5.86%   |
| Zorin 15                     | 9         | 3.52%   |
| Arch                         | 9         | 3.52%   |
| Pop!_OS 20.04                | 8         | 3.13%   |
| OpenMandriva 4.2             | 8         | 3.13%   |
| Ubuntu 21.10                 | 6         | 2.34%   |
| Ubuntu 20.10                 | 6         | 2.34%   |
| Fedora 31                    | 6         | 2.34%   |
| Debian 10                    | 6         | 2.34%   |
| Arch Rolling                 | 6         | 2.34%   |
| Zorin 16                     | 5         | 1.95%   |
| Pop!_OS 20.10                | 5         | 1.95%   |
| OpenMandriva 4.3             | 5         | 1.95%   |
| Linux Mint 20.2              | 5         | 1.95%   |
| Fedora 35                    | 5         | 1.95%   |
| Ubuntu 21.04                 | 4         | 1.56%   |
| Pop!_OS 21.04                | 4         | 1.56%   |
| Manjaro                      | 4         | 1.56%   |
| Linux Mint 20.3              | 4         | 1.56%   |
| Linux Mint 19.2              | 4         | 1.56%   |
| Kubuntu 20.04                | 4         | 1.56%   |
| Fedora 34                    | 4         | 1.56%   |
| Fedora 33                    | 4         | 1.56%   |
| Ubuntu 22.04                 | 3         | 1.17%   |
| Ubuntu 19.10                 | 3         | 1.17%   |
| Pop!_OS 22.04                | 3         | 1.17%   |
| Linux Mint 20                | 3         | 1.17%   |
| Linux Mint 19.3              | 3         | 1.17%   |
| Linux Mint 19.1              | 3         | 1.17%   |
| Fedora 32                    | 3         | 1.17%   |
| EndeavourOS Rolling          | 3         | 1.17%   |
| Elementary 6.1               | 3         | 1.17%   |
| Debian 11                    | 3         | 1.17%   |
| Ubuntu 19.04                 | 2         | 0.78%   |
| ROSA R10                     | 2         | 0.78%   |
| Pop!_OS 21.10                | 2         | 0.78%   |
| Linux Mint 20.1              | 2         | 0.78%   |
| KDE neon 20.04               | 2         | 0.78%   |
| Endless 3.7.8                | 2         | 0.78%   |
| Endless 3.6.1                | 2         | 0.78%   |
| Endless 3.5.4                | 2         | 0.78%   |
| Debian Unstable              | 2         | 0.78%   |
| Xubuntu 20.04                | 1         | 0.39%   |
| Xubuntu 19.04                | 1         | 0.39%   |
| Xubuntu 18.04                | 1         | 0.39%   |
| Void Linux                   | 1         | 0.39%   |
| Ubuntu MATE 20.10            | 1         | 0.39%   |
| Ubuntu MATE 20.04            | 1         | 0.39%   |
| Ubuntu 18.10                 | 1         | 0.39%   |
| Ubuntu 16.04                 | 1         | 0.39%   |
| Solus 4.2                    | 1         | 0.39%   |
| Solus 4.1                    | 1         | 0.39%   |
| Parrot 4.10                  | 1         | 0.39%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.39%   |
| Manjaro 21.2.5               | 1         | 0.39%   |
| Manjaro 21.2.1               | 1         | 0.39%   |
| Manjaro 21.1.0               | 1         | 0.39%   |
| Manjaro 21.0.5               | 1         | 0.39%   |
| Manjaro 20.2.1               | 1         | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 72        | 29.75%  |
| Linux Mint   | 23        | 9.5%    |
| Fedora       | 23        | 9.5%    |
| Pop!_OS      | 21        | 8.68%   |
| Arch         | 15        | 6.2%    |
| Zorin        | 14        | 5.79%   |
| OpenMandriva | 13        | 5.37%   |
| Debian       | 11        | 4.55%   |
| Manjaro      | 9         | 3.72%   |
| Kubuntu      | 5         | 2.07%   |
| Endless      | 5         | 2.07%   |
| Elementary   | 5         | 2.07%   |
| EndeavourOS  | 4         | 1.65%   |
| Xubuntu      | 3         | 1.24%   |
| Ubuntu MATE  | 2         | 0.83%   |
| Solus        | 2         | 0.83%   |
| ROSA         | 2         | 0.83%   |
| Lubuntu      | 2         | 0.83%   |
| KDE neon     | 2         | 0.83%   |
| Gentoo       | 2         | 0.83%   |
| Void Linux   | 1         | 0.41%   |
| Parrot       | 1         | 0.41%   |
| openSUSE     | 1         | 0.41%   |
| LMDE         | 1         | 0.41%   |
| BlackPanther | 1         | 0.41%   |
| ArcoLinux    | 1         | 0.41%   |
| Archman      | 1         | 0.41%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 4.2%    |
| 5.10.14-desktop-1omv4002 | 8         | 2.8%    |
| 5.4.0-48-generic         | 5         | 1.75%   |
| 5.3.0-28-generic         | 5         | 1.75%   |
| 5.16.7-desktop-1omv4003  | 5         | 1.75%   |
| 5.3.16-300.fc31.x86_64   | 4         | 1.4%    |
| 5.17.5-76051705-generic  | 4         | 1.4%    |
| 5.11.0-7620-generic      | 4         | 1.4%    |
| 5.11.0-27-generic        | 4         | 1.4%    |
| 5.8.0-53-generic         | 3         | 1.05%   |
| 5.4.0-81-generic         | 3         | 1.05%   |
| 5.4.0-7642-generic       | 3         | 1.05%   |
| 5.4.0-74-generic         | 3         | 1.05%   |
| 5.4.0-65-generic         | 3         | 1.05%   |
| 5.4.0-45-generic         | 3         | 1.05%   |
| 5.4.0-26-generic         | 3         | 1.05%   |
| 5.13.0-37-generic        | 3         | 1.05%   |
| 5.0.0-37-generic         | 3         | 1.05%   |
| 4.19.0-9-amd64           | 3         | 1.05%   |
| 5.8.11-1-MANJARO         | 2         | 0.7%    |
| 5.8.0-7630-generic       | 2         | 0.7%    |
| 5.8.0-48-generic         | 2         | 0.7%    |
| 5.8.0-43-generic         | 2         | 0.7%    |
| 5.4.0-91-generic         | 2         | 0.7%    |
| 5.4.0-88-generic         | 2         | 0.7%    |
| 5.4.0-72-generic         | 2         | 0.7%    |
| 5.4.0-40-generic         | 2         | 0.7%    |
| 5.4.0-39-generic         | 2         | 0.7%    |
| 5.4.0-29-generic         | 2         | 0.7%    |
| 5.3.0-40-generic         | 2         | 0.7%    |
| 5.3.0-26-generic         | 2         | 0.7%    |
| 5.15.4-arch1-1           | 2         | 0.7%    |
| 5.15.12-arch1-1          | 2         | 0.7%    |
| 5.14.15-300.fc35.x86_64  | 2         | 0.7%    |
| 5.13.0-7614-generic      | 2         | 0.7%    |
| 5.13.0-39-generic        | 2         | 0.7%    |
| 5.13.0-30-generic        | 2         | 0.7%    |
| 5.13.0-19-generic        | 2         | 0.7%    |
| 5.11.0-7612-generic      | 2         | 0.7%    |
| 5.11.0-36-generic        | 2         | 0.7%    |
| 5.0.0-23-generic         | 2         | 0.7%    |
| 5.0.0-17-generic         | 2         | 0.7%    |
| 5.0.0-15-generic         | 2         | 0.7%    |
| 4.19.0-10-amd64          | 2         | 0.7%    |
| 4.18.0-21-generic        | 2         | 0.7%    |
| 4.18.0-12-generic        | 2         | 0.7%    |
| 4.15.0-70-generic        | 2         | 0.7%    |
| 5.9.8-arch1-1            | 1         | 0.35%   |
| 5.9.6-arch1-1            | 1         | 0.35%   |
| 5.9.16-1-MANJARO         | 1         | 0.35%   |
| 5.9.11-zen2-1-zen        | 1         | 0.35%   |
| 5.8.3-arch1-1            | 1         | 0.35%   |
| 5.8.16-200.fc32.x86_64   | 1         | 0.35%   |
| 5.8.15-201.fc32.x86_64   | 1         | 0.35%   |
| 5.8.14-arch1-1           | 1         | 0.35%   |
| 5.8.10-arch1-1           | 1         | 0.35%   |
| 5.8.1-arch1-1            | 1         | 0.35%   |
| 5.8.0-7625-generic       | 1         | 0.35%   |
| 5.8.0-63-generic         | 1         | 0.35%   |
| 5.8.0-50-generic         | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 55        | 20.22%  |
| 5.13.0  | 19        | 6.99%   |
| 5.11.0  | 17        | 6.25%   |
| 5.3.0   | 16        | 5.88%   |
| 5.8.0   | 15        | 5.51%   |
| 4.15.0  | 14        | 5.15%   |
| 5.0.0   | 12        | 4.41%   |
| 5.10.14 | 9         | 3.31%   |
| 4.19.0  | 7         | 2.57%   |
| 4.18.0  | 6         | 2.21%   |
| 5.16.7  | 5         | 1.84%   |
| 5.3.16  | 4         | 1.47%   |
| 5.17.5  | 4         | 1.47%   |
| 5.15.0  | 4         | 1.47%   |
| 5.15.4  | 3         | 1.1%    |
| 5.10.0  | 3         | 1.1%    |
| 5.8.11  | 2         | 0.74%   |
| 5.7.0   | 2         | 0.74%   |
| 5.6.8   | 2         | 0.74%   |
| 5.6.19  | 2         | 0.74%   |
| 5.3.8   | 2         | 0.74%   |
| 5.16.11 | 2         | 0.74%   |
| 5.15.15 | 2         | 0.74%   |
| 5.15.12 | 2         | 0.74%   |
| 5.14.15 | 2         | 0.74%   |
| 5.11.12 | 2         | 0.74%   |
| 5.9.8   | 1         | 0.37%   |
| 5.9.6   | 1         | 0.37%   |
| 5.9.16  | 1         | 0.37%   |
| 5.9.11  | 1         | 0.37%   |
| 5.8.3   | 1         | 0.37%   |
| 5.8.16  | 1         | 0.37%   |
| 5.8.15  | 1         | 0.37%   |
| 5.8.14  | 1         | 0.37%   |
| 5.8.10  | 1         | 0.37%   |
| 5.8.1   | 1         | 0.37%   |
| 5.7.8   | 1         | 0.37%   |
| 5.7.5   | 1         | 0.37%   |
| 5.7.12  | 1         | 0.37%   |
| 5.6.4   | 1         | 0.37%   |
| 5.6.11  | 1         | 0.37%   |
| 5.6.0   | 1         | 0.37%   |
| 5.5.8   | 1         | 0.37%   |
| 5.5.10  | 1         | 0.37%   |
| 5.4.72  | 1         | 0.37%   |
| 5.4.32  | 1         | 0.37%   |
| 5.4.21  | 1         | 0.37%   |
| 5.4.15  | 1         | 0.37%   |
| 5.4.14  | 1         | 0.37%   |
| 5.2.11  | 1         | 0.37%   |
| 5.18.6  | 1         | 0.37%   |
| 5.18.5  | 1         | 0.37%   |
| 5.18.1  | 1         | 0.37%   |
| 5.17.9  | 1         | 0.37%   |
| 5.16.3  | 1         | 0.37%   |
| 5.16.18 | 1         | 0.37%   |
| 5.16.14 | 1         | 0.37%   |
| 5.16.13 | 1         | 0.37%   |
| 5.16.1  | 1         | 0.37%   |
| 5.15.7  | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 60        | 22.47%  |
| 5.13    | 22        | 8.24%   |
| 5.11    | 22        | 8.24%   |
| 5.8     | 21        | 7.87%   |
| 5.3     | 21        | 7.87%   |
| 5.10    | 18        | 6.74%   |
| 4.15    | 14        | 5.24%   |
| 5.15    | 13        | 4.87%   |
| 5.16    | 12        | 4.49%   |
| 5.0     | 12        | 4.49%   |
| 4.19    | 7         | 2.62%   |
| 4.18    | 7         | 2.62%   |
| 5.6     | 6         | 2.25%   |
| 5.14    | 6         | 2.25%   |
| 5.7     | 5         | 1.87%   |
| 5.17    | 5         | 1.87%   |
| 5.9     | 4         | 1.5%    |
| 5.18    | 3         | 1.12%   |
| 5.5     | 2         | 0.75%   |
| 4.9     | 2         | 0.75%   |
| 4.20    | 2         | 0.75%   |
| 5.2     | 1         | 0.37%   |
| 4.13    | 1         | 0.37%   |
| 4.11    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 224       | 96.55%  |
| i686   | 8         | 3.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 111       | 45.87%  |
| Unknown          | 32        | 13.22%  |
| KDE5             | 28        | 11.57%  |
| X-Cinnamon       | 17        | 7.02%   |
| XFCE             | 13        | 5.37%   |
| KDE              | 10        | 4.13%   |
| MATE             | 8         | 3.31%   |
| Pantheon         | 5         | 2.07%   |
| Cinnamon         | 4         | 1.65%   |
| LXDE             | 3         | 1.24%   |
| i3               | 3         | 1.24%   |
| Unity            | 2         | 0.83%   |
| Budgie           | 2         | 0.83%   |
| LXQt             | 1         | 0.41%   |
| lightdm-xsession | 1         | 0.41%   |
| KDE4             | 1         | 0.41%   |
| Deepin           | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 187       | 77.27%  |
| Wayland | 37        | 15.29%  |
| Unknown | 16        | 6.61%   |
| Tty     | 2         | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 147       | 60%     |
| GDM     | 29        | 11.84%  |
| SDDM    | 26        | 10.61%  |
| LightDM | 14        | 5.71%   |
| GDM3    | 12        | 4.9%    |
| TDM     | 11        | 4.49%   |
| Ly      | 2         | 0.82%   |
| LXDM    | 2         | 0.82%   |
| XDM     | 1         | 0.41%   |
| KDM     | 1         | 0.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_NZ   | 139       | 57.2%   |
| en_US   | 47        | 19.34%  |
| Unknown | 27        | 11.11%  |
| en_GB   | 12        | 4.94%   |
| C       | 10        | 4.12%   |
| en_AU   | 6         | 2.47%   |
| zh_CN   | 1         | 0.41%   |
| de_DE   | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 120       | 50.63%  |
| BIOS | 117       | 49.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 186       | 77.18%  |
| Overlay | 19        | 7.88%   |
| Btrfs   | 17        | 7.05%   |
| Unknown | 14        | 5.81%   |
| Xfs     | 2         | 0.83%   |
| Ext2    | 2         | 0.83%   |
| Zfs     | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 149       | 62.61%  |
| GPT     | 64        | 26.89%  |
| MBR     | 25        | 10.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 210       | 88.61%  |
| Yes       | 27        | 11.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 183       | 77.22%  |
| Yes       | 54        | 22.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 70        | 30.17%  |
| Lenovo              | 38        | 16.38%  |
| Dell                | 30        | 12.93%  |
| ASUSTek Computer    | 24        | 10.34%  |
| Acer                | 21        | 9.05%   |
| Toshiba             | 15        | 6.47%   |
| MSI                 | 8         | 3.45%   |
| Apple               | 5         | 2.16%   |
| Sony                | 4         | 1.72%   |
| Samsung Electronics | 4         | 1.72%   |
| System76            | 2         | 0.86%   |
| YJKC                | 1         | 0.43%   |
| TWG                 | 1         | 0.43%   |
| Timi                | 1         | 0.43%   |
| Star Labs           | 1         | 0.43%   |
| Metabox             | 1         | 0.43%   |
| Medion              | 1         | 0.43%   |
| IBM                 | 1         | 0.43%   |
| HUAWEI              | 1         | 0.43%   |
| Google              | 1         | 0.43%   |
| eMachines           | 1         | 0.43%   |
| Alienware           | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell XPS 13 9360                           | 5         | 2.16%   |
| HP ProBook 6550b                           | 3         | 1.29%   |
| HP ProBook 4540s                           | 3         | 1.29%   |
| HP EliteBook 8560p                         | 3         | 1.29%   |
| MSI GE66 Raider 10SF                       | 2         | 0.86%   |
| Lenovo ThinkPad T460 20FMS2FR00            | 2         | 0.86%   |
| HP ZBook Firefly 15 G7 Mobile Workstation  | 2         | 0.86%   |
| HP ProBook 450 G5                          | 2         | 0.86%   |
| HP ProBook 450 G3                          | 2         | 0.86%   |
| HP Pavilion dv6                            | 2         | 0.86%   |
| HP Pavilion 15                             | 2         | 0.86%   |
| HP Notebook                                | 2         | 0.86%   |
| Dell XPS 15 9500                           | 2         | 0.86%   |
| Dell Latitude E4300                        | 2         | 0.86%   |
| Dell Latitude 7490                         | 2         | 0.86%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR      | 2         | 0.86%   |
| ASUS ROG Strix G513QY_G513QY               | 2         | 0.86%   |
| ASUS K52Jc                                 | 2         | 0.86%   |
| Acer Swift SF314-41                        | 2         | 0.86%   |
| YJKC vBOOK Plus                            | 1         | 0.43%   |
| TWG E2017                                  | 1         | 0.43%   |
| Toshiba TECRA Z50-A                        | 1         | 0.43%   |
| Toshiba Satellite U920t                    | 1         | 0.43%   |
| Toshiba Satellite S70t-B                   | 1         | 0.43%   |
| Toshiba Satellite Pro R50-C                | 1         | 0.43%   |
| Toshiba Satellite Pro L830                 | 1         | 0.43%   |
| Toshiba Satellite Pro C665                 | 1         | 0.43%   |
| Toshiba Satellite L750                     | 1         | 0.43%   |
| Toshiba Satellite L50D-C                   | 1         | 0.43%   |
| Toshiba Satellite C660                     | 1         | 0.43%   |
| Toshiba Satellite C50D-C                   | 1         | 0.43%   |
| Toshiba Satellite C50-B                    | 1         | 0.43%   |
| Toshiba PORTEGE R930                       | 1         | 0.43%   |
| Toshiba PORTEGE R700                       | 1         | 0.43%   |
| Toshiba PORTEGE M930                       | 1         | 0.43%   |
| Toshiba PORTEGE M780                       | 1         | 0.43%   |
| Timi A30                                   | 1         | 0.43%   |
| System76 Pangolin                          | 1         | 0.43%   |
| System76 Lemur Pro                         | 1         | 0.43%   |
| Star Labs LabTop                           | 1         | 0.43%   |
| Sony VPCEH28FG                             | 1         | 0.43%   |
| Sony VPCEB43FG                             | 1         | 0.43%   |
| Sony SVE14A15FGS                           | 1         | 0.43%   |
| Sony SVE11126CGB                           | 1         | 0.43%   |
| Samsung RC410/RC510/RC710                  | 1         | 0.43%   |
| Samsung 530U3C/530U4C/532U3C               | 1         | 0.43%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV   | 1         | 0.43%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.43%   |
| MSI Katana GF76 12UGS                      | 1         | 0.43%   |
| MSI GT80S 6QD                              | 1         | 0.43%   |
| MSI GT72 2PC                               | 1         | 0.43%   |
| MSI GS63VR 7RF                             | 1         | 0.43%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.43%   |
| MSI GE60 0NC/GE60 0ND                      | 1         | 0.43%   |
| Metabox X170SM                             | 1         | 0.43%   |
| Medion P6815                               | 1         | 0.43%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.43%   |
| Lenovo V15-IIL 82C5                        | 1         | 0.43%   |
| Lenovo V110-15IAP 80TG                     | 1         | 0.43%   |
| Lenovo V110-14IAP 80TF                     | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 28        | 12.07%  |
| HP ProBook        | 16        | 6.9%    |
| HP EliteBook      | 15        | 6.47%   |
| HP Pavilion       | 14        | 6.03%   |
| Acer Aspire       | 13        | 5.6%    |
| Dell XPS          | 11        | 4.74%   |
| Dell Latitude     | 11        | 4.74%   |
| Toshiba Satellite | 10        | 4.31%   |
| HP ZBook          | 5         | 2.16%   |
| HP Laptop         | 5         | 2.16%   |
| ASUS ROG          | 5         | 2.16%   |
| Toshiba PORTEGE   | 4         | 1.72%   |
| HP Compaq         | 3         | 1.29%   |
| Dell Precision    | 3         | 1.29%   |
| Dell Inspiron     | 3         | 1.29%   |
| Acer TravelMate   | 3         | 1.29%   |
| MSI GE66          | 2         | 0.86%   |
| Lenovo IdeaPad    | 2         | 0.86%   |
| HP Presario       | 2         | 0.86%   |
| HP Notebook       | 2         | 0.86%   |
| ASUS VivoBook     | 2         | 0.86%   |
| ASUS K52Jc        | 2         | 0.86%   |
| ASUS ASUS         | 2         | 0.86%   |
| Apple MacBookPro5 | 2         | 0.86%   |
| Acer Swift        | 2         | 0.86%   |
| YJKC vBOOK        | 1         | 0.43%   |
| TWG E2017         | 1         | 0.43%   |
| Toshiba TECRA     | 1         | 0.43%   |
| Timi A30          | 1         | 0.43%   |
| System76 Pangolin | 1         | 0.43%   |
| System76 Lemur    | 1         | 0.43%   |
| Star Labs LabTop  | 1         | 0.43%   |
| Sony VPCEH28FG    | 1         | 0.43%   |
| Sony VPCEB43FG    | 1         | 0.43%   |
| Sony SVE14A15FGS  | 1         | 0.43%   |
| Sony SVE11126CGB  | 1         | 0.43%   |
| Samsung RC410     | 1         | 0.43%   |
| Samsung 530U3C    | 1         | 0.43%   |
| Samsung 3570R     | 1         | 0.43%   |
| Samsung 300E4A    | 1         | 0.43%   |
| MSI Katana        | 1         | 0.43%   |
| MSI GT80S         | 1         | 0.43%   |
| MSI GT72          | 1         | 0.43%   |
| MSI GS63VR        | 1         | 0.43%   |
| MSI GP75          | 1         | 0.43%   |
| MSI GE60          | 1         | 0.43%   |
| Metabox X170SM    | 1         | 0.43%   |
| Medion P6815      | 1         | 0.43%   |
| Lenovo Yoga       | 1         | 0.43%   |
| Lenovo V15-IIL    | 1         | 0.43%   |
| Lenovo V110-15IAP | 1         | 0.43%   |
| Lenovo V110-14IAP | 1         | 0.43%   |
| Lenovo Legion     | 1         | 0.43%   |
| Lenovo B590       | 1         | 0.43%   |
| Lenovo B50-70     | 1         | 0.43%   |
| Lenovo B50-30     | 1         | 0.43%   |
| IBM ThinkPad      | 1         | 0.43%   |
| HUAWEI BOHK-WAX9X | 1         | 0.43%   |
| HP Spectre        | 1         | 0.43%   |
| HP OMEN           | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 27        | 11.64%  |
| 2012 | 25        | 10.78%  |
| 2019 | 20        | 8.62%   |
| 2016 | 19        | 8.19%   |
| 2020 | 18        | 7.76%   |
| 2018 | 17        | 7.33%   |
| 2017 | 16        | 6.9%    |
| 2014 | 16        | 6.9%    |
| 2021 | 15        | 6.47%   |
| 2013 | 13        | 5.6%    |
| 2015 | 12        | 5.17%   |
| 2010 | 12        | 5.17%   |
| 2008 | 10        | 4.31%   |
| 2009 | 5         | 2.16%   |
| 2022 | 2         | 0.86%   |
| 2007 | 2         | 0.86%   |
| 2006 | 2         | 0.86%   |
| 2005 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 232       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 206       | 88.03%  |
| Enabled  | 28        | 11.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 229       | 98.71%  |
| Yes  | 3         | 1.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 61        | 25.52%  |
| 16.01-24.0  | 48        | 20.08%  |
| 3.01-4.0    | 44        | 18.41%  |
| 8.01-16.0   | 43        | 17.99%  |
| 32.01-64.0  | 22        | 9.21%   |
| 1.01-2.0    | 7         | 2.93%   |
| 64.01-256.0 | 5         | 2.09%   |
| 2.01-3.0    | 4         | 1.67%   |
| 0.51-1.0    | 3         | 1.26%   |
| 24.01-32.0  | 2         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 86        | 32.95%  |
| 2.01-3.0   | 68        | 26.05%  |
| 3.01-4.0   | 43        | 16.48%  |
| 4.01-8.0   | 35        | 13.41%  |
| 0.51-1.0   | 17        | 6.51%   |
| 8.01-16.0  | 7         | 2.68%   |
| 24.01-32.0 | 2         | 0.77%   |
| 16.01-24.0 | 2         | 0.77%   |
| 0.01-0.5   | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 180       | 75.63%  |
| 2      | 49        | 20.59%  |
| 3      | 7         | 2.94%   |
| 0      | 2         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 56.22%  |
| Yes       | 102       | 43.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 85.11%  |
| No        | 35        | 14.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 230       | 99.14%  |
| No        | 2         | 0.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 78.9%   |
| No        | 50        | 21.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| New Zealand | 232       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Auckland         | 114       | 47.5%   |
| Wellington       | 29        | 12.08%  |
| Christchurch     | 23        | 9.58%   |
| Hamilton         | 12        | 5%      |
| Whangarei        | 7         | 2.92%   |
| Dunedin          | 7         | 2.92%   |
| Tauranga         | 5         | 2.08%   |
| New Plymouth     | 5         | 2.08%   |
| Nelson           | 4         | 1.67%   |
| Lower Hutt       | 4         | 1.67%   |
| Invercargill     | 4         | 1.67%   |
| Napier City      | 3         | 1.25%   |
| Whanganui        | 2         | 0.83%   |
| Palmerston North | 2         | 0.83%   |
| Otaki            | 2         | 0.83%   |
| Hastings         | 2         | 0.83%   |
| Grafton          | 2         | 0.83%   |
| Cambridge        | 2         | 0.83%   |
| Whatawhata       | 1         | 0.42%   |
| Tutukaka         | 1         | 0.42%   |
| Rotorua          | 1         | 0.42%   |
| Pakuranga        | 1         | 0.42%   |
| Masterton        | 1         | 0.42%   |
| Levin            | 1         | 0.42%   |
| Kerikeri         | 1         | 0.42%   |
| Katikati         | 1         | 0.42%   |
| Gordonton        | 1         | 0.42%   |
| Edgecumbe        | 1         | 0.42%   |
| Ashburton        | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 51        | 68     | 18.41%  |
| Seagate                   | 38        | 41     | 13.72%  |
| WDC                       | 30        | 46     | 10.83%  |
| Toshiba                   | 27        | 35     | 9.75%   |
| Crucial                   | 19        | 32     | 6.86%   |
| SK hynix                  | 15        | 15     | 5.42%   |
| SanDisk                   | 15        | 17     | 5.42%   |
| Intel                     | 12        | 14     | 4.33%   |
| Unknown                   | 9         | 15     | 3.25%   |
| Micron Technology         | 7         | 11     | 2.53%   |
| Kingston                  | 7         | 10     | 2.53%   |
| HGST                      | 7         | 7      | 2.53%   |
| Hitachi                   | 6         | 8      | 2.17%   |
| KingSpec                  | 4         | 4      | 1.44%   |
| ASMT                      | 3         | 3      | 1.08%   |
| A-DATA Technology         | 3         | 3      | 1.08%   |
| TO Exter                  | 2         | 2      | 0.72%   |
| Team                      | 2         | 2      | 0.72%   |
| Micron/Crucial Technology | 2         | 2      | 0.72%   |
| LITEON                    | 2         | 2      | 0.72%   |
| KIOXIA                    | 2         | 3      | 0.72%   |
| China                     | 2         | 2      | 0.72%   |
| Apple                     | 2         | 2      | 0.72%   |
| XPG                       | 1         | 1      | 0.36%   |
| Transcend                 | 1         | 1      | 0.36%   |
| Star Drive                | 1         | 1      | 0.36%   |
| Silicon Motion            | 1         | 2      | 0.36%   |
| ROG                       | 1         | 1      | 0.36%   |
| Phison                    | 1         | 1      | 0.36%   |
| LITEONIT                  | 1         | 3      | 0.36%   |
| KINGBANK                  | 1         | 1      | 0.36%   |
| Hewlett-Packard           | 1         | 3      | 0.36%   |
| Fujitsu                   | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Intel NVMe SSD Drive 512GB          | 7         | 2.42%   |
| Samsung NVMe SSD Drive 512GB        | 6         | 2.08%   |
| Samsung SSD 850 EVO 500GB           | 5         | 1.73%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 1.38%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 1.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 3         | 1.04%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 1.04%   |
| Toshiba NVMe SSD Drive 512GB        | 3         | 1.04%   |
| Toshiba MQ01ABF050 500GB            | 3         | 1.04%   |
| Seagate ST9500420AS 500GB           | 3         | 1.04%   |
| Samsung SSD 860 EVO 500GB           | 3         | 1.04%   |
| Samsung SSD 850 EVO 1TB             | 3         | 1.04%   |
| Samsung NVMe SSD Drive 256GB        | 3         | 1.04%   |
| Crucial CT500MX500SSD1 500GB        | 3         | 1.04%   |
| Crucial CT240BX200SSD1 240GB        | 3         | 1.04%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 2         | 0.69%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 2         | 0.69%   |
| WDC WD10SPZX-22Z10T1 1TB            | 2         | 0.69%   |
| WDC WD10SPZX-21Z10T0 1TB            | 2         | 0.69%   |
| WDC WD10JPVX-60JC3T0 1TB            | 2         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 0.69%   |
| Unknown MMC Card  64GB              | 2         | 0.69%   |
| Unknown MMC Card  2GB               | 2         | 0.69%   |
| Toshiba MQ01ABD075 752GB            | 2         | 0.69%   |
| Toshiba MK1652GSX 160GB             | 2         | 0.69%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 2         | 0.69%   |
| TO Exter nal USB 3.0 256GB          | 2         | 0.69%   |
| SK hynix NVMe SSD Drive 256GB       | 2         | 0.69%   |
| Seagate ST9500325AS 500GB           | 2         | 0.69%   |
| Seagate ST2000LM007-1R8174 2TB      | 2         | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.69%   |
| Seagate ST1000LM014-1EJ164 1TB      | 2         | 0.69%   |
| Seagate Expansion 1TB               | 2         | 0.69%   |
| SanDisk SDSSDA240G 240GB            | 2         | 0.69%   |
| SanDisk NVMe SSD Drive 512GB        | 2         | 0.69%   |
| SanDisk NVMe SSD Drive 1024GB       | 2         | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB        | 2         | 0.69%   |
| Samsung SSD 850 EVO 250GB           | 2         | 0.69%   |
| Samsung PM9A1 NVMe 1024GB           | 2         | 0.69%   |
| Samsung NVMe SSD Drive 1024GB       | 2         | 0.69%   |
| Samsung MZVLB512HBJQ-000L7 512GB    | 2         | 0.69%   |
| Samsung MZVL21T0HCLR-00B00 1TB      | 2         | 0.69%   |
| Micron/Crucial NVMe SSD Drive 500GB | 2         | 0.69%   |
| Kingston SV300S37A240G 240GB SSD    | 2         | 0.69%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 0.69%   |
| KingSpec Q-180 180GB                | 2         | 0.69%   |
| Intel SSDPEKNU512GZ 512GB           | 2         | 0.69%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 0.69%   |
| HGST HTS721010A9E630 1TB            | 2         | 0.69%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 0.69%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.69%   |
| XPG NVMe SSD Drive 1024GB           | 1         | 0.35%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 0.35%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 0.35%   |
| WDC WD3200BEKX-75B7WT0 320GB        | 1         | 0.35%   |
| WDC WD2500BEVT-80A23T0 250GB        | 1         | 0.35%   |
| WDC WD20SPZX-21UA7T0 2TB            | 1         | 0.35%   |
| WDC WD20SPZX-08UA7 2TB              | 1         | 0.35%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 0.35%   |
| WDC WD10SPZX-21Z 1TB                | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 39     | 39.13%  |
| WDC                 | 24        | 31     | 26.09%  |
| Toshiba             | 13        | 18     | 14.13%  |
| HGST                | 7         | 7      | 7.61%   |
| Hitachi             | 6         | 8      | 6.52%   |
| Samsung Electronics | 2         | 2      | 2.17%   |
| Unknown             | 1         | 3      | 1.09%   |
| Fujitsu             | 1         | 1      | 1.09%   |
| ASMT                | 1         | 1      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 30     | 24.21%  |
| Crucial             | 17        | 30     | 17.89%  |
| SanDisk             | 11        | 11     | 11.58%  |
| Micron Technology   | 6         | 9      | 6.32%   |
| Kingston            | 6         | 9      | 6.32%   |
| KingSpec            | 4         | 4      | 4.21%   |
| WDC                 | 3         | 10     | 3.16%   |
| Toshiba             | 3         | 4      | 3.16%   |
| SK hynix            | 3         | 3      | 3.16%   |
| A-DATA Technology   | 3         | 3      | 3.16%   |
| TO Exter            | 2         | 2      | 2.11%   |
| Team                | 2         | 2      | 2.11%   |
| Seagate             | 2         | 2      | 2.11%   |
| LITEON              | 2         | 2      | 2.11%   |
| China               | 2         | 2      | 2.11%   |
| Transcend           | 1         | 1      | 1.05%   |
| LITEONIT            | 1         | 3      | 1.05%   |
| Intel               | 1         | 2      | 1.05%   |
| Hewlett-Packard     | 1         | 3      | 1.05%   |
| ASMT                | 1         | 1      | 1.05%   |
| Apple               | 1         | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 90        | 134    | 34.09%  |
| HDD     | 88        | 111    | 33.33%  |
| NVMe    | 76        | 99     | 28.79%  |
| MMC     | 8         | 12     | 3.03%   |
| Unknown | 2         | 3      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 163       | 233    | 63.18%  |
| NVMe | 76        | 99     | 29.46%  |
| SAS  | 11        | 15     | 4.26%   |
| MMC  | 8         | 12     | 3.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 120       | 174    | 67.04%  |
| 0.51-1.0   | 51        | 63     | 28.49%  |
| 1.01-2.0   | 7         | 7      | 3.91%   |
| 3.01-4.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 67        | 28.03%  |
| 101-250        | 67        | 28.03%  |
| 501-1000       | 38        | 15.9%   |
| 1001-2000      | 16        | 6.69%   |
| 1-20           | 15        | 6.28%   |
| 51-100         | 14        | 5.86%   |
| 21-50          | 7         | 2.93%   |
| Unknown        | 7         | 2.93%   |
| More than 3000 | 4         | 1.67%   |
| 2001-3000      | 4         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 99        | 38.82%  |
| 21-50          | 52        | 20.39%  |
| 101-250        | 36        | 14.12%  |
| 51-100         | 29        | 11.37%  |
| 251-500        | 15        | 5.88%   |
| 501-1000       | 13        | 5.1%    |
| Unknown        | 7         | 2.75%   |
| More than 3000 | 2         | 0.78%   |
| 2001-3000      | 1         | 0.39%   |
| 1001-2000      | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKX-00HPJT0 752GB                        | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 5.88%   |
| Toshiba MK3256GSY 320GB                             | 1         | 1      | 5.88%   |
| SK hynix SC308 SATA 128GB SSD                       | 1         | 1      | 5.88%   |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB             | 1         | 1      | 5.88%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 5.88%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 5.88%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 5.88%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 5.88%   |
| Hitachi HTS545032B9SA00 320GB                       | 1         | 1      | 5.88%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 5.88%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 5.88%   |
| Crucial CT275MX300SSD1 275GB                        | 1         | 1      | 5.88%   |
| ASMT ASM105x 240GB                                  | 1         | 1      | 5.88%   |
| Apple HDD HTS547550A9E384 500GB                     | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 3      | 17.65%  |
| Toshiba           | 2         | 2      | 11.76%  |
| SK hynix          | 2         | 2      | 11.76%  |
| Micron Technology | 2         | 2      | 11.76%  |
| Hitachi           | 2         | 2      | 11.76%  |
| HGST              | 2         | 2      | 11.76%  |
| WDC               | 1         | 1      | 5.88%   |
| Crucial           | 1         | 1      | 5.88%   |
| ASMT              | 1         | 1      | 5.88%   |
| Apple             | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 27.27%  |
| Toshiba | 2         | 2      | 18.18%  |
| Hitachi | 2         | 2      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |
| Apple   | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 64.71%  |
| SSD  | 5         | 5      | 29.41%  |
| NVMe | 1         | 1      | 5.88%   |

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
| Detected | 155       | 245    | 63.27%  |
| Works    | 73        | 97     | 29.8%   |
| Malfunc  | 17        | 17     | 6.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 170       | 63.2%   |
| Samsung Electronics          | 28        | 10.41%  |
| AMD                          | 24        | 8.92%   |
| Toshiba America Info Systems | 12        | 4.46%   |
| SK hynix                     | 12        | 4.46%   |
| SanDisk                      | 7         | 2.6%    |
| Nvidia                       | 4         | 1.49%   |
| Micron/Crucial Technology    | 4         | 1.49%   |
| Phison Electronics           | 2         | 0.74%   |
| KIOXIA                       | 2         | 0.74%   |
| Silicon Motion               | 1         | 0.37%   |
| Micron Technology            | 1         | 0.37%   |
| Kingston Technology Company  | 1         | 0.37%   |
| ADATA Technology             | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 24        | 8.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 21        | 7.37%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 21        | 7.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 19        | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 17        | 5.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 9         | 3.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 3.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 2.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 7         | 2.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 6         | 2.11%   |
| Intel SSD 660P Series                                                                  | 6         | 2.11%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 6         | 2.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 2.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 6         | 2.11%   |
| SK hynix Non-Volatile memory controller                                                | 5         | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 1.75%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 4         | 1.4%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 1.4%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 1.4%    |
| Intel Non-Volatile memory controller                                                   | 4         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 4         | 1.4%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 1.05%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 3         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 3         | 1.05%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 1.05%   |
| Nvidia MCP79 AHCI Controller                                                           | 3         | 1.05%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 3         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 1.05%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 2         | 0.7%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 2         | 0.7%    |
| SK hynix Gold P31 SSD                                                                  | 2         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 0.7%    |
| Phison E12 NVMe Controller                                                             | 2         | 0.7%    |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.7%    |
| Intel Alder Lake-P SATA AHCI Controller                                                | 2         | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 0.7%    |
| SK hynix BC511                                                                         | 1         | 0.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.35%   |
| SanDisk WD Black NVMe SSD                                                              | 1         | 0.35%   |
| Samsung Electronics SATA controller                                                    | 1         | 0.35%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.35%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.35%   |
| Micron Non-Volatile memory controller                                                  | 1         | 0.35%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.35%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.35%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.35%   |
| Intel SATA Controller [RAID mode]                                                      | 1         | 0.35%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 1         | 0.35%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 172       | 62.55%  |
| NVMe | 77        | 28%     |
| RAID | 14        | 5.09%   |
| IDE  | 12        | 4.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 199       | 85.78%  |
| AMD    | 33        | 14.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 3.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 2.16%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 2.16%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 2.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.72%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 1.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.72%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 4         | 1.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.29%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.29%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.29%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.29%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.29%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 1.29%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 1.29%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.29%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.29%   |
| Intel Pentium M processor 2.00GHz             | 2         | 0.86%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 2         | 0.86%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.86%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.86%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.86%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 0.86%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.86%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.86%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.86%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.86%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.86%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 2         | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.86%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.86%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.86%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.86%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 0.86%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.86%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.86%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 2         | 0.86%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 0.86%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 2         | 0.86%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.86%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.86%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 0.86%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.43%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.43%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.43%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.43%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.43%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.43%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz              | 1         | 0.43%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 75        | 32.33%  |
| Intel Core i7                  | 64        | 27.59%  |
| Intel Core 2 Duo               | 14        | 6.03%   |
| Other                          | 12        | 5.17%   |
| Intel Core i3                  | 12        | 5.17%   |
| Intel Celeron                  | 11        | 4.74%   |
| AMD Ryzen 5                    | 7         | 3.02%   |
| AMD A6                         | 5         | 2.16%   |
| Intel Core i9                  | 3         | 1.29%   |
| Intel Atom                     | 3         | 1.29%   |
| AMD Ryzen 9                    | 3         | 1.29%   |
| AMD Ryzen 7                    | 3         | 1.29%   |
| AMD E2                         | 3         | 1.29%   |
| AMD A8                         | 3         | 1.29%   |
| Intel Pentium M                | 2         | 0.86%   |
| Intel Pentium                  | 1         | 0.43%   |
| Intel Genuine                  | 1         | 0.43%   |
| Intel Core m7                  | 1         | 0.43%   |
| Intel Celeron Dual-Core        | 1         | 0.43%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.43%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.43%   |
| AMD Ryzen 7 PRO                | 1         | 0.43%   |
| AMD Ryzen 3                    | 1         | 0.43%   |
| AMD E1                         | 1         | 0.43%   |
| AMD E                          | 1         | 0.43%   |
| AMD A4                         | 1         | 0.43%   |
| AMD A10                        | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 126       | 54.31%  |
| 4      | 69        | 29.74%  |
| 6      | 16        | 6.9%    |
| 8      | 12        | 5.17%   |
| 1      | 5         | 2.16%   |
| 14     | 3         | 1.29%   |
| 10     | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 232       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 180       | 77.59%  |
| 1      | 52        | 22.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 223       | 94.49%  |
| Unknown        | 10        | 4.24%   |
| 32-bit         | 3         | 1.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 24.27%  |
| 0x206a7    | 23        | 9.62%   |
| 0x306a9    | 18        | 7.53%   |
| 0x806ea    | 11        | 4.6%    |
| 0x406e3    | 10        | 4.18%   |
| 0x806ec    | 9         | 3.77%   |
| 0x20655    | 7         | 2.93%   |
| 0x806e9    | 6         | 2.51%   |
| 0x40651    | 6         | 2.51%   |
| 0x306c3    | 6         | 2.51%   |
| 0x30678    | 6         | 2.51%   |
| 0x10676    | 6         | 2.51%   |
| 0xa0652    | 5         | 2.09%   |
| 0x306d4    | 5         | 2.09%   |
| 0x1067a    | 5         | 2.09%   |
| 0x906ea    | 4         | 1.67%   |
| 0x07030105 | 4         | 1.67%   |
| 0x906e9    | 3         | 1.26%   |
| 0x806d1    | 3         | 1.26%   |
| 0x6fd      | 3         | 1.26%   |
| 0x506e3    | 3         | 1.26%   |
| 0x08108102 | 3         | 1.26%   |
| 0x806c1    | 2         | 0.84%   |
| 0x6d8      | 2         | 0.84%   |
| 0x506c9    | 2         | 0.84%   |
| 0x106ca    | 2         | 0.84%   |
| 0x0a50000c | 2         | 0.84%   |
| 0x08608103 | 2         | 0.84%   |
| 0x08600106 | 2         | 0.84%   |
| 0x08108109 | 2         | 0.84%   |
| 0x0700010f | 2         | 0.84%   |
| 0x06006705 | 2         | 0.84%   |
| 0x05000119 | 2         | 0.84%   |
| 0xa0660    | 1         | 0.42%   |
| 0x906a3    | 1         | 0.42%   |
| 0x806eb    | 1         | 0.42%   |
| 0x806c2    | 1         | 0.42%   |
| 0x706e5    | 1         | 0.42%   |
| 0x6fb      | 1         | 0.42%   |
| 0x106e5    | 1         | 0.42%   |
| 0x106c2    | 1         | 0.42%   |
| 0x08608102 | 1         | 0.42%   |
| 0x07030104 | 1         | 0.42%   |
| 0x06006118 | 1         | 0.42%   |
| 0x06001119 | 1         | 0.42%   |
| 0x02000032 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 46        | 19.83%  |
| SandyBridge      | 27        | 11.64%  |
| IvyBridge        | 22        | 9.48%   |
| Skylake          | 17        | 7.33%   |
| Haswell          | 14        | 6.03%   |
| Penryn           | 12        | 5.17%   |
| Westmere         | 10        | 4.31%   |
| CometLake        | 9         | 3.88%   |
| Silvermont       | 8         | 3.45%   |
| Puma             | 7         | 3.02%   |
| Broadwell        | 7         | 3.02%   |
| Zen+             | 6         | 2.59%   |
| IceLake          | 6         | 2.59%   |
| Unknown          | 5         | 2.16%   |
| Zen 3            | 4         | 1.72%   |
| TigerLake        | 4         | 1.72%   |
| Excavator        | 4         | 1.72%   |
| Core             | 4         | 1.72%   |
| Goldmont         | 3         | 1.29%   |
| Bonnell          | 3         | 1.29%   |
| Zen 2            | 2         | 0.86%   |
| P6               | 2         | 0.86%   |
| Nehalem          | 2         | 0.86%   |
| Jaguar           | 2         | 0.86%   |
| Bobcat           | 2         | 0.86%   |
| Piledriver       | 1         | 0.43%   |
| K8 Hammer        | 1         | 0.43%   |
| K8 & K10 hybrid  | 1         | 0.43%   |
| Alderlake Hybrid | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 176       | 60.07%  |
| Nvidia | 59        | 20.14%  |
| AMD    | 58        | 19.8%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 22        | 7.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 19        | 6.15%   |
| Intel UHD Graphics 620                                                                | 12        | 3.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 11        | 3.56%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 2.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 8         | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 8         | 2.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 7         | 2.27%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 7         | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 6         | 1.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 6         | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 1.94%   |
| Intel HD Graphics 630                                                                 | 5         | 1.62%   |
| Intel HD Graphics 5500                                                                | 5         | 1.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 5         | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 1.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 5         | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.29%   |
| Intel HD Graphics 620                                                                 | 4         | 1.29%   |
| Intel HD Graphics 530                                                                 | 4         | 1.29%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 4         | 1.29%   |
| AMD Cezanne                                                                           | 4         | 1.29%   |
| Nvidia GK107M [GeForce GT 650M]                                                       | 3         | 0.97%   |
| Nvidia C79 [GeForce 9400M]                                                            | 3         | 0.97%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 0.97%   |
| Intel HD Graphics 500                                                                 | 3         | 0.97%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 3         | 0.97%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 3         | 0.97%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 3         | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 3         | 0.97%   |
| AMD Lucienne                                                                          | 3         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 2         | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 0.65%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 2         | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.65%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.65%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 2         | 0.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 0.65%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 0.65%   |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.65%   |
| Intel Comet Lake UHD Graphics                                                         | 2         | 0.65%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller               | 2         | 0.65%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 2         | 0.65%   |
| AMD Renoir                                                                            | 2         | 0.65%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                  | 2         | 0.65%   |
| AMD Mullins [Radeon R2 Graphics]                                                      | 2         | 0.65%   |
| AMD Mars [Radeon HD 8730M]                                                            | 2         | 0.65%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 2         | 0.65%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 2         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.32%   |
| Nvidia TU117M                                                                         | 1         | 0.32%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.32%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                 | 1         | 0.32%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                      | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 119       | 51.29%  |
| Intel + Nvidia | 42        | 18.1%   |
| 1 x AMD        | 29        | 12.5%   |
| Intel + AMD    | 15        | 6.47%   |
| 1 x Nvidia     | 12        | 5.17%   |
| 2 x AMD        | 10        | 4.31%   |
| AMD + Nvidia   | 4         | 1.72%   |
| 2 x Nvidia     | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 192       | 82.4%   |
| Proprietary | 33        | 14.16%  |
| Unknown     | 8         | 3.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 153       | 64.29%  |
| 1.01-2.0   | 24        | 10.08%  |
| 0.01-0.5   | 24        | 10.08%  |
| 0.51-1.0   | 15        | 6.3%    |
| 3.01-4.0   | 9         | 3.78%   |
| 7.01-8.0   | 5         | 2.1%    |
| 5.01-6.0   | 5         | 2.1%    |
| 2.01-3.0   | 2         | 0.84%   |
| 8.01-16.0  | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 17.23%  |
| LG Display              | 42        | 15.73%  |
| Chimei Innolux          | 34        | 12.73%  |
| Samsung Electronics     | 31        | 11.61%  |
| BOE                     | 19        | 7.12%   |
| Sharp                   | 14        | 5.24%   |
| Dell                    | 12        | 4.49%   |
| Chi Mei Optoelectronics | 12        | 4.49%   |
| AOC                     | 9         | 3.37%   |
| Goldstar                | 8         | 3%      |
| PANDA                   | 4         | 1.5%    |
| Apple                   | 4         | 1.5%    |
| InfoVision              | 3         | 1.12%   |
| Hewlett-Packard         | 3         | 1.12%   |
| ViewSonic               | 2         | 0.75%   |
| Quanta Display          | 2         | 0.75%   |
| Philips                 | 2         | 0.75%   |
| Lenovo                  | 2         | 0.75%   |
| InnoLux Display         | 2         | 0.75%   |
| Denver                  | 2         | 0.75%   |
| Acer                    | 2         | 0.75%   |
| TMX                     | 1         | 0.37%   |
| Sony                    | 1         | 0.37%   |
| SANYO                   | 1         | 0.37%   |
| PRISM+                  | 1         | 0.37%   |
| MiTAC                   | 1         | 0.37%   |
| Mi                      | 1         | 0.37%   |
| LG Philips              | 1         | 0.37%   |
| IBM                     | 1         | 0.37%   |
| HYD                     | 1         | 0.37%   |
| HannStar                | 1         | 0.37%   |
| CPT                     | 1         | 0.37%   |
| Ancor Communications    | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 1.45%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 1.45%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 1.09%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.09%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.73%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.73%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 2         | 0.73%   |
| Dell U3818DW DELA0F3 3840x1600 880x367mm 37.5-inch                       | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.73%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO41ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch            | 2         | 0.73%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                         | 2         | 0.73%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 2         | 0.73%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch            | 1         | 0.36%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch             | 1         | 0.36%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.36%   |
| Sony TV SNYA401 1920x1080 1600x900mm 72.3-inch                           | 1         | 0.36%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                  | 1         | 0.36%   |
| SANYO TV SAN1040 1920x1080 819x460mm 37.0-inch                           | 1         | 0.36%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch        | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM00C8 1280x1024 338x270mm 17.0-inch     | 1         | 0.36%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch    | 1         | 0.36%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch        | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch    | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 261x163mm 12.1-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 94        | 37.45%  |
| 1366x768 (WXGA)    | 77        | 30.68%  |
| 1600x900 (HD+)     | 15        | 5.98%   |
| 1280x800 (WXGA)    | 13        | 5.18%   |
| 3840x2160 (4K)     | 10        | 3.98%   |
| 2560x1440 (QHD)    | 10        | 3.98%   |
| 3440x1440          | 7         | 2.79%   |
| 3200x1800 (QHD+)   | 4         | 1.59%   |
| 1440x900 (WXGA+)   | 4         | 1.59%   |
| 1280x1024 (SXGA)   | 3         | 1.2%    |
| 1024x600           | 3         | 1.2%    |
| 3840x1600          | 2         | 0.8%    |
| 3456x2160          | 2         | 0.8%    |
| 2560x1600          | 2         | 0.8%    |
| 3840x2400          | 1         | 0.4%    |
| 2880x1920          | 1         | 0.4%    |
| 1920x1280          | 1         | 0.4%    |
| 1920x1200 (WUXGA)  | 1         | 0.4%    |
| 1680x1050 (WSXGA+) | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 114       | 42.54%  |
| 13      | 37        | 13.81%  |
| 14      | 28        | 10.45%  |
| 17      | 18        | 6.72%   |
| 27      | 15        | 5.6%    |
| 23      | 7         | 2.61%   |
| 34      | 5         | 1.87%   |
| 21      | 5         | 1.87%   |
| 11      | 5         | 1.87%   |
| 10      | 5         | 1.87%   |
| 12      | 4         | 1.49%   |
| 37      | 3         | 1.12%   |
| 18      | 3         | 1.12%   |
| 16      | 3         | 1.12%   |
| 72      | 2         | 0.75%   |
| 24      | 2         | 0.75%   |
| 22      | 2         | 0.75%   |
| 19      | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 84      | 1         | 0.37%   |
| 35      | 1         | 0.37%   |
| 33      | 1         | 0.37%   |
| 31      | 1         | 0.37%   |
| 25      | 1         | 0.37%   |
| 20      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 163       | 61.51%  |
| 201-300     | 30        | 11.32%  |
| 501-600     | 22        | 8.3%    |
| 351-400     | 22        | 8.3%    |
| 401-500     | 11        | 4.15%   |
| 701-800     | 6         | 2.26%   |
| 801-900     | 4         | 1.51%   |
| 1501-2000   | 3         | 1.13%   |
| 601-700     | 2         | 0.75%   |
| Unknown     | 2         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 193       | 82.48%  |
| 16/10   | 24        | 10.26%  |
| 21/9    | 9         | 3.85%   |
| 5/4     | 3         | 1.28%   |
| 3/2     | 3         | 1.28%   |
| Unknown | 2         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 112       | 41.48%  |
| 81-90          | 53        | 19.63%  |
| 121-130        | 16        | 5.93%   |
| 301-350        | 15        | 5.56%   |
| 71-80          | 14        | 5.19%   |
| 201-250        | 14        | 5.19%   |
| 351-500        | 8         | 2.96%   |
| 51-60          | 5         | 1.85%   |
| 41-50          | 5         | 1.85%   |
| 151-200        | 5         | 1.85%   |
| 61-70          | 4         | 1.48%   |
| 141-150        | 4         | 1.48%   |
| 111-120        | 4         | 1.48%   |
| More than 1000 | 3         | 1.11%   |
| 501-1000       | 3         | 1.11%   |
| Unknown        | 2         | 0.74%   |
| 251-300        | 1         | 0.37%   |
| 131-140        | 1         | 0.37%   |
| 91-100         | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 98        | 37.12%  |
| 121-160       | 92        | 34.85%  |
| 51-100        | 43        | 16.29%  |
| 161-240       | 14        | 5.3%    |
| More than 240 | 13        | 4.92%   |
| 1-50          | 2         | 0.76%   |
| Unknown       | 2         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 185       | 76.76%  |
| 2     | 41        | 17.01%  |
| 0     | 9         | 3.73%   |
| 3     | 5         | 2.07%   |
| 4     | 1         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 136       | 36.66%  |
| Realtek Semiconductor             | 116       | 31.27%  |
| Qualcomm Atheros                  | 52        | 14.02%  |
| Broadcom                          | 20        | 5.39%   |
| Ralink                            | 6         | 1.62%   |
| Hewlett-Packard                   | 6         | 1.62%   |
| Broadcom Limited                  | 5         | 1.35%   |
| Nvidia                            | 4         | 1.08%   |
| TP-Link                           | 3         | 0.81%   |
| MediaTek                          | 3         | 0.81%   |
| Lenovo                            | 3         | 0.81%   |
| DisplayLink                       | 3         | 0.81%   |
| Sierra Wireless                   | 2         | 0.54%   |
| JMicron Technology                | 2         | 0.54%   |
| Dell                              | 2         | 0.54%   |
| Samsung Electronics               | 1         | 0.27%   |
| OPPO Electronics                  | 1         | 0.27%   |
| Marvell Technology Group          | 1         | 0.27%   |
| Lite-On Technology                | 1         | 0.27%   |
| ICS Advent                        | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| Attansic Technology               | 1         | 0.27%   |
| ASIX Electronics                  | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 15.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 3.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 3.04%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.6%    |
| Intel Wireless 8265 / 8275                                        | 11        | 2.39%   |
| Intel Wireless 7260                                               | 10        | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.95%   |
| Intel Wireless 8260                                               | 9         | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.74%   |
| Intel Wireless 3165                                               | 7         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.52%   |
| Intel Wireless 7265                                               | 6         | 1.3%    |
| Intel Centrino Advanced-N 6200                                    | 6         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.08%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.08%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.87%   |
| Intel 82577LC Gigabit Network Connection                          | 4         | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 4         | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.65%   |
| Intel Wireless-AC 9260                                            | 3         | 0.65%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.65%   |
| HP lt4112 Gobi 4G Module Network Device                           | 3         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.65%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2         | 0.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.43%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.43%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.43%   |
| Intel Ethernet controller                                         | 2         | 0.43%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.43%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 132       | 53.88%  |
| Qualcomm Atheros      | 45        | 18.37%  |
| Realtek Semiconductor | 26        | 10.61%  |
| Broadcom              | 17        | 6.94%   |
| Ralink                | 6         | 2.45%   |
| Broadcom Limited      | 5         | 2.04%   |
| TP-Link               | 3         | 1.22%   |
| MediaTek              | 3         | 1.22%   |
| Hewlett-Packard       | 3         | 1.22%   |
| Sierra Wireless       | 2         | 0.82%   |
| Dell                  | 2         | 0.82%   |
| Lite-On Technology    | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14        | 5.69%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 5.28%   |
| Intel Wireless 8265 / 8275                                     | 11        | 4.47%   |
| Intel Wireless 7260                                            | 10        | 4.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 3.66%   |
| Intel Wireless 8260                                            | 9         | 3.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 3.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 3.25%   |
| Intel Wireless 3165                                            | 7         | 2.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 2.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 2.85%   |
| Intel Wireless 7265                                            | 6         | 2.44%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.03%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 2.03%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 2.03%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 2.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 1.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.22%   |
| Intel Wireless-AC 9260                                         | 3         | 1.22%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.22%   |
| HP lt4112 Gobi 4G Module Network Device                        | 3         | 1.22%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2         | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.81%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.81%   |
| Dell DW5816e Snapdragonâ¢ X7 LTE                           | 2         | 0.81%   |
| Broadcom BCM43227 802.11b/g/n                                  | 2         | 0.81%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.41%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.41%   |
| Sierra Wireless EM7305                                         | 1         | 0.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.41%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.41%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1         | 0.41%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 0.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.41%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 0.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.41%   |
| Lite-On BCM4318 [AirForce One 54g] 802.11g WLAN Controller     | 1         | 0.41%   |
| Intel Wireless 3160                                            | 1         | 0.41%   |
| Intel WiFi Link 5100                                           | 1         | 0.41%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 107       | 51.2%   |
| Intel                    | 63        | 30.14%  |
| Qualcomm Atheros         | 15        | 7.18%   |
| Broadcom                 | 6         | 2.87%   |
| Nvidia                   | 4         | 1.91%   |
| Lenovo                   | 3         | 1.44%   |
| DisplayLink              | 3         | 1.44%   |
| JMicron Technology       | 2         | 0.96%   |
| Samsung Electronics      | 1         | 0.48%   |
| OPPO Electronics         | 1         | 0.48%   |
| Marvell Technology Group | 1         | 0.48%   |
| ICS Advent               | 1         | 0.48%   |
| Attansic Technology      | 1         | 0.48%   |
| ASIX Electronics         | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 72        | 34.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 8.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 5.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 2.38%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 2.38%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.9%    |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 1.9%    |
| Intel 82577LC Gigabit Network Connection                                       | 4         | 1.9%    |
| Nvidia MCP79 Ethernet                                                          | 3         | 1.43%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 1.43%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.43%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 1.43%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.95%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.95%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.95%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.95%   |
| Intel Ethernet controller                                                      | 2         | 0.95%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.95%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.95%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.95%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.95%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.48%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.48%   |
| OPPO Find X2 Lite                                                              | 1         | 0.48%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.48%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.48%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]                    | 1         | 0.48%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.48%   |
| Intel Ethernet Connection (16) I219-LM                                         | 1         | 0.48%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.48%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.48%   |
| ICS Advent USB 10/100 LAN                                                      | 1         | 0.48%   |
| DisplayLink Targus USB3.0 DV2K Dock w Power                                    | 1         | 0.48%   |
| DisplayLink Plugable UD-3900H                                                  | 1         | 0.48%   |
| DisplayLink Dell Universal Dock D6000                                          | 1         | 0.48%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.48%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 1         | 0.48%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.48%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 1         | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 229       | 52.76%  |
| Ethernet | 200       | 46.08%  |
| Modem    | 5         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 198       | 77.65%  |
| Ethernet | 57        | 22.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 180       | 77.59%  |
| 1     | 48        | 20.69%  |
| 3     | 2         | 0.86%   |
| 0     | 2         | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 203       | 86.75%  |
| Yes  | 31        | 13.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 51.6%   |
| Qualcomm Atheros Communications | 18        | 9.57%   |
| Realtek Semiconductor           | 10        | 5.32%   |
| Hewlett-Packard                 | 10        | 5.32%   |
| Foxconn / Hon Hai               | 10        | 5.32%   |
| Lite-On Technology              | 9         | 4.79%   |
| IMC Networks                    | 8         | 4.26%   |
| Broadcom                        | 7         | 3.72%   |
| Apple                           | 5         | 2.66%   |
| Toshiba                         | 4         | 2.13%   |
| Ralink Technology               | 3         | 1.6%    |
| Dell                            | 2         | 1.06%   |
| ASUSTek Computer                | 2         | 1.06%   |
| Realtek                         | 1         | 0.53%   |
| Ralink                          | 1         | 0.53%   |
| Edimax Technology               | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 42        | 22.34%  |
| Intel Bluetooth Device                                                              | 16        | 8.51%   |
| Intel AX200 Bluetooth                                                               | 13        | 6.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 11        | 5.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 4.79%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 3.72%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 3.19%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.66%   |
| Realtek Bluetooth Radio                                                             | 5         | 2.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 2.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.13%   |
| Lite-On Bluetooth Device                                                            | 4         | 2.13%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.13%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.6%    |
| IMC Networks Wireless_Device                                                        | 3         | 1.6%    |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.6%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.6%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.6%    |
| Foxconn / Hon Hai Acer Module                                                       | 3         | 1.6%    |
| Toshiba Bluetooth Radio                                                             | 2         | 1.06%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 1.06%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.06%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.06%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.06%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.06%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.53%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.53%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.53%   |
| Ralink CSR BS8510                                                                   | 1         | 0.53%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.53%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.53%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.53%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.53%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.53%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.53%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.53%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.53%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter                             | 1         | 0.53%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.53%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.53%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.53%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.53%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.53%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.53%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 0.53%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.53%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 195       | 65.22%  |
| AMD                       | 44        | 14.72%  |
| Nvidia                    | 37        | 12.37%  |
| Realtek Semiconductor     | 4         | 1.34%   |
| Logitech                  | 3         | 1%      |
| Lenovo                    | 3         | 1%      |
| Hewlett-Packard           | 3         | 1%      |
| Texas Instruments         | 1         | 0.33%   |
| SteelSeries ApS           | 1         | 0.33%   |
| Sennheiser Communications | 1         | 0.33%   |
| Plantronics               | 1         | 0.33%   |
| Micro Star International  | 1         | 0.33%   |
| GYROCOM C&C               | 1         | 0.33%   |
| Google                    | 1         | 0.33%   |
| ClearOne Communications   | 1         | 0.33%   |
| C&T                       | 1         | 0.33%   |
| Belkin Components         | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 30        | 8.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 26        | 7.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 23        | 6.57%   |
| AMD Family 17h/19h HD Audio Controller                                            | 15        | 4.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 12        | 3.43%   |
| AMD FCH Azalia Controller                                                         | 11        | 3.14%   |
| AMD Kabini HDMI/DP Audio                                                          | 10        | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                        | 9         | 2.57%   |
| Intel Haswell-ULT HD Audio Controller                                             | 8         | 2.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 8         | 2.29%   |
| Intel 8 Series HD Audio Controller                                                | 8         | 2.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 8         | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 7         | 2%      |
| Intel Comet Lake PCH-LP cAVS                                                      | 7         | 2%      |
| Intel Comet Lake PCH cAVS                                                         | 7         | 2%      |
| Intel Broadwell-U Audio Controller                                                | 7         | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 7         | 2%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7         | 2%      |
| Intel CM238 HD Audio Controller                                                   | 6         | 1.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6         | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5         | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 5         | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5         | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5         | 1.43%   |
| Realtek Semiconductor USB Audio                                                   | 4         | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 1.14%   |
| Nvidia Audio device                                                               | 4         | 1.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 4         | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3         | 0.86%   |
| Nvidia MCP79 High Definition Audio                                                | 3         | 0.86%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3         | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 3         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 3         | 0.86%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 3         | 0.86%   |
| Hewlett-Packard USB Audio                                                         | 3         | 0.86%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 3         | 0.86%   |
| AMD High Definition Audio Controller                                              | 3         | 0.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 0.57%   |
| Nvidia High Definition Audio Controller                                           | 2         | 0.57%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2         | 0.57%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 2         | 0.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 0.57%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 2         | 0.57%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2         | 0.57%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.29%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                     | 1         | 0.29%   |
| Sennheiser Communications SC60 for Lync                                           | 1         | 0.29%   |
| Plantronics C510                                                                  | 1         | 0.29%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.29%   |
| Nvidia stereo controller                                                          | 1         | 0.29%   |
| Nvidia MCP89 High Definition Audio                                                | 1         | 0.29%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 0.29%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.29%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 28.08%  |
| SK hynix            | 36        | 24.66%  |
| Micron Technology   | 22        | 15.07%  |
| Crucial             | 14        | 9.59%   |
| Kingston            | 9         | 6.16%   |
| Unknown             | 4         | 2.74%   |
| Elpida              | 4         | 2.74%   |
| A-DATA Technology   | 4         | 2.74%   |
| Team                | 2         | 1.37%   |
| Shenzhen Mic        | 2         | 1.37%   |
| Ramaxel Technology  | 2         | 1.37%   |
| Transcend           | 1         | 0.68%   |
| Strontium           | 1         | 0.68%   |
| Neo Forza           | 1         | 0.68%   |
| Nanya Technology    | 1         | 0.68%   |
| Corsair             | 1         | 0.68%   |
| Apacer              | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 3.29%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 2.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 2.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.97%   |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s       | 3         | 1.97%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 1.32%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 2         | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1.32%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s      | 2         | 1.32%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 2         | 1.32%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.32%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 2         | 1.32%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.32%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s          | 2         | 1.32%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.32%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s         | 2         | 1.32%   |
| Unknown RAM Module 8192MB SODIMM DDR3                            | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.66%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.66%   |
| Transcend RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.66%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 1         | 0.66%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 0.66%   |
| Team RAM TEAMGROUP-SD4-2400 16GB Chip DDR4 2133MT/s              | 1         | 0.66%   |
| Strontium RAM SRT4G86S1-H9H 4GB SODIMM DDR3 1333MT/s             | 1         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.66%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.66%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 0.66%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR2 667MT/s         | 1         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 1         | 0.66%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 1         | 0.66%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1334MT/s        | 1         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.66%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.66%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 0.66%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.66%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.66%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.66%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.66%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 0.66%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.66%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.66%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 0.66%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1067MT/s                   | 1         | 0.66%   |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM DDR3 1067MT/s         | 1         | 0.66%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 50        | 45.05%  |
| DDR3    | 44        | 39.64%  |
| DDR2    | 6         | 5.41%   |
| LPDDR3  | 5         | 4.5%    |
| SDRAM   | 3         | 2.7%    |
| Unknown | 2         | 1.8%    |
| LPDDR4  | 1         | 0.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 92.92%  |
| Row Of Chips | 6         | 5.31%   |
| Chip         | 2         | 1.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 44        | 37.61%  |
| 4096  | 36        | 30.77%  |
| 16384 | 19        | 16.24%  |
| 2048  | 13        | 11.11%  |
| 32768 | 5         | 4.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 23.77%  |
| 2667    | 21        | 17.21%  |
| 3200    | 20        | 16.39%  |
| 1334    | 12        | 9.84%   |
| 2400    | 7         | 5.74%   |
| 2133    | 6         | 4.92%   |
| 1867    | 4         | 3.28%   |
| 667     | 4         | 3.28%   |
| Unknown | 4         | 3.28%   |
| 1333    | 3         | 2.46%   |
| 1067    | 3         | 2.46%   |
| 4800    | 2         | 1.64%   |
| 800     | 2         | 1.64%   |
| 8400    | 1         | 0.82%   |
| 4267    | 1         | 0.82%   |
| 4199    | 1         | 0.82%   |
| 2048    | 1         | 0.82%   |
| 975     | 1         | 0.82%   |

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
| Chicony Electronics                    | 63        | 30.43%  |
| Sunplus Innovation Technology          | 18        | 8.7%    |
| Acer                                   | 16        | 7.73%   |
| Microdia                               | 15        | 7.25%   |
| IMC Networks                           | 15        | 7.25%   |
| Realtek Semiconductor                  | 14        | 6.76%   |
| Quanta                                 | 11        | 5.31%   |
| Lite-On Technology                     | 9         | 4.35%   |
| Suyin                                  | 7         | 3.38%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.38%   |
| Apple                                  | 5         | 2.42%   |
| Primax Electronics                     | 4         | 1.93%   |
| Logitech                               | 4         | 1.93%   |
| Alcor Micro                            | 4         | 1.93%   |
| Syntek                                 | 3         | 1.45%   |
| Silicon Motion                         | 3         | 1.45%   |
| Importek                               | 2         | 0.97%   |
| Z-Star Microelectronics                | 1         | 0.48%   |
| Sonix Technology                       | 1         | 0.48%   |
| Samsung Electronics                    | 1         | 0.48%   |
| Intel                                  | 1         | 0.48%   |
| DigiTech                               | 1         | 0.48%   |
| AVer Information                       | 1         | 0.48%   |
| ALi                                    | 1         | 0.48%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 12        | 5.8%    |
| Chicony HD WebCam                                               | 7         | 3.38%   |
| Sunplus Integrated_Webcam_HD                                    | 6         | 2.9%    |
| Sunplus HP HD Webcam [Fixed]                                    | 6         | 2.9%    |
| Chicony HP HD Camera                                            | 6         | 2.9%    |
| Microdia Integrated Webcam HD                                   | 5         | 2.42%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 2.42%   |
| Chicony HP HD Webcam                                            | 5         | 2.42%   |
| IMC Networks Integrated Camera                                  | 4         | 1.93%   |
| Chicony TOSHIBA Web Camera - HD                                 | 4         | 1.93%   |
| Apple Built-in iSight                                           | 4         | 1.93%   |
| Acer Integrated Camera                                          | 4         | 1.93%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 1.45%   |
| Realtek HP Truevision HD                                        | 3         | 1.45%   |
| Quanta HP TrueVision HD Camera                                  | 3         | 1.45%   |
| Microdia Integrated_Webcam_HD                                   | 3         | 1.45%   |
| Lite-On Integrated Camera                                       | 3         | 1.45%   |
| Chicony VGA Webcam                                              | 3         | 1.45%   |
| Acer SunplusIT Integrated Camera                                | 3         | 1.45%   |
| Suyin HP Webcam                                                 | 2         | 0.97%   |
| Suyin 1.3M HD WebCam                                            | 2         | 0.97%   |
| Sunplus ASUS Webcam                                             | 2         | 0.97%   |
| Realtek Integrated Webcam_HD                                    | 2         | 0.97%   |
| Quanta HP HD Camera                                             | 2         | 0.97%   |
| Primax Villem                                                   | 2         | 0.97%   |
| Primax HP HD Webcam [Fixed]                                     | 2         | 0.97%   |
| Lite-On HP HD Camera                                            | 2         | 0.97%   |
| Chicony USB2.0 Camera                                           | 2         | 0.97%   |
| Chicony USB2.0 0.3M UVC WebCam                                  | 2         | 0.97%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 2         | 0.97%   |
| Chicony Integrated HP HD Webcam                                 | 2         | 0.97%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 2         | 0.97%   |
| Alcor Micro USB 2.0 Camera                                      | 2         | 0.97%   |
| Alcor Micro Asus Integrated Webcam                              | 2         | 0.97%   |
| Acer Lenovo EasyCamera                                          | 2         | 0.97%   |
| Acer HD Webcam                                                  | 2         | 0.97%   |
| Z-Star WebCam SC-03FFL11739P                                    | 1         | 0.48%   |
| Syntek USB 2.0 UVC PC Camera                                    | 1         | 0.48%   |
| Syntek Integrated Camera                                        | 1         | 0.48%   |
| Syntek EasyCamera                                               | 1         | 0.48%   |
| Suyin USB 2.0 Webcam Device                                     | 1         | 0.48%   |
| Suyin HP TrueVision HD                                          | 1         | 0.48%   |
| Suyin Asus Integrated Webcam                                    | 1         | 0.48%   |
| Sunplus Integrated Webcam                                       | 1         | 0.48%   |
| Sunplus HP TrueVision HD Camera                                 | 1         | 0.48%   |
| Sunplus HP Truevision HD                                        | 1         | 0.48%   |
| Sunplus 1.3M HD WebCam                                          | 1         | 0.48%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 0.48%   |
| Silicon Motion WebCam SC-13HDL12131N                            | 1         | 0.48%   |
| Silicon Motion HP Webcam-101 Integrated Camera                  | 1         | 0.48%   |
| Silicon Motion HP Webcam                                        | 1         | 0.48%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 0.48%   |
| Realtek USB Camera                                              | 1         | 0.48%   |
| Realtek Integrated Webcam                                       | 1         | 0.48%   |
| Realtek HP Truevision HD integrated webcam                      | 1         | 0.48%   |
| Realtek HP "Truevision HD" laptop camera                        | 1         | 0.48%   |
| Realtek HD WebCam                                               | 1         | 0.48%   |
| Realtek 2SF001                                                  | 1         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 38        | 55.07%  |
| Synaptics                  | 14        | 20.29%  |
| AuthenTec                  | 5         | 7.25%   |
| Shenzhen Goodix Technology | 4         | 5.8%    |
| Elan Microelectronics      | 3         | 4.35%   |
| Upek                       | 2         | 2.9%    |
| LighTuning Technology      | 2         | 2.9%    |
| STMicroelectronics         | 1         | 1.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 14.49%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 8.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 5.8%    |
| Validity Sensors VFS491                                                    | 4         | 5.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.8%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 5.8%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 4.35%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.9%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.9%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 2.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.9%    |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 2.9%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 2.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.9%    |
| Elan ELAN:Fingerprint                                                      | 2         | 2.9%    |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.9%    |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.45%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.45%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.45%   |
| AuthenTec AES2810                                                          | 1         | 1.45%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.45%   |
| AuthenTec AES1600                                                          | 1         | 1.45%   |
| Unknown                                                                    | 1         | 1.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 54.55%  |
| Alcor Micro | 3         | 27.27%  |
| O2 Micro    | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 27.27%  |
| Alcor Micro AU9540 Smartcard Reader            | 3         | 27.27%  |
| Broadcom 5880                                  | 2         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader            | 1         | 9.09%   |
| Broadcom 58200                                 | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 134       | 55.83%  |
| 1     | 85        | 35.42%  |
| 2     | 17        | 7.08%   |
| 6     | 2         | 0.83%   |
| 5     | 1         | 0.42%   |
| 3     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 67        | 50.76%  |
| Graphics card            | 17        | 12.88%  |
| Net/wireless             | 15        | 11.36%  |
| Chipcard                 | 9         | 6.82%   |
| Multimedia controller    | 7         | 5.3%    |
| Net/ethernet             | 4         | 3.03%   |
| Communication controller | 3         | 2.27%   |
| Sound                    | 2         | 1.52%   |
| Card reader              | 2         | 1.52%   |
| Camera                   | 2         | 1.52%   |
| Bluetooth                | 2         | 1.52%   |
| Modem                    | 1         | 0.76%   |
| Flash memory             | 1         | 0.76%   |

