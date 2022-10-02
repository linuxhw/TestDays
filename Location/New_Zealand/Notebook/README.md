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

Total: 408

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro14,3              | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| Toshiba       | Satellite C660              | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Google        | Snappy                      | [e428dec368](https://linux-hardware.org/?probe=e428dec368) | Sep 14, 2022 |
| HP            | Laptop 17-bs0xx             | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| HP            | Pavilion dv6                | [5877abaab3](https://linux-hardware.org/?probe=5877abaab3) | Sep 07, 2022 |
| Acer          | Aspire F5-573G              | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| The Wareho... | E2037                       | [e9599d1061](https://linux-hardware.org/?probe=e9599d1061) | Aug 31, 2022 |
| Lenovo        | V145-15AST 81MT             | [40b9d37c2a](https://linux-hardware.org/?probe=40b9d37c2a) | Aug 29, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [0a08f13779](https://linux-hardware.org/?probe=0a08f13779) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| ASUSTek       | P81IJ                       | [7ab324abea](https://linux-hardware.org/?probe=7ab324abea) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Acer          | Aspire M5-581TG             | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| Google        | Galtic                      | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | Latitude E6500              | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| Dell          | Vostro 7500                 | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [335eb52112](https://linux-hardware.org/?probe=335eb52112) | Aug 12, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| Dell          | Latitude E6430s             | [542db6380a](https://linux-hardware.org/?probe=542db6380a) | Aug 04, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| HP            | 2000                        | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| HP            | Notebook                    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| Lenovo        | 14w 81MQ0013AU              | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| Lenovo        | G40-30 80FY                 | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| ASUSTek       | GL703VD                     | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [36fdd87ff3](https://linux-hardware.org/?probe=36fdd87ff3) | Jun 21, 2022 |
| HP            | ProBook 450 G1              | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| HP            | 550                         | [1db816d0b2](https://linux-hardware.org/?probe=1db816d0b2) | Jun 19, 2022 |
| Dell          | Precision 3571              | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| HP            | EliteBook 830 G5            | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Toshiba       | Satellite Pro C665          | [23fd853a45](https://linux-hardware.org/?probe=23fd853a45) | May 24, 2022 |
| Acer          | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | [22776216d6](https://linux-hardware.org/?probe=22776216d6) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [cd50fa44c3](https://linux-hardware.org/?probe=cd50fa44c3) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| Toshiba       | Satellite L50D-C            | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [60d56e6b15](https://linux-hardware.org/?probe=60d56e6b15) | May 13, 2022 |
| Alienware     | x17 R2                      | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bd6e42ac60](https://linux-hardware.org/?probe=bd6e42ac60) | May 07, 2022 |
| Toshiba       | Satellite C660              | [2b4d9cbd0c](https://linux-hardware.org/?probe=2b4d9cbd0c) | May 03, 2022 |
| Lenovo        | B50-30 20382                | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| Toshiba       | Satellite C660              | [c3bb583347](https://linux-hardware.org/?probe=c3bb583347) | Apr 24, 2022 |
| Lenovo        | B50-70 20384                | [35cf0f09e4](https://linux-hardware.org/?probe=35cf0f09e4) | Apr 22, 2022 |
| Dell          | XPS 13 9360                 | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | [5ad4aa0994](https://linux-hardware.org/?probe=5ad4aa0994) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| Dell          | Latitude 7480               | [ccc8107d39](https://linux-hardware.org/?probe=ccc8107d39) | Apr 01, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| eMachines     | eM350                       | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [9b194b03b4](https://linux-hardware.org/?probe=9b194b03b4) | Mar 25, 2022 |
| HP            | Laptop 15-bs0xx             | [e12f0f1eed](https://linux-hardware.org/?probe=e12f0f1eed) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| ASUSTek       | G75VX                       | [4673f4edd8](https://linux-hardware.org/?probe=4673f4edd8) | Mar 21, 2022 |
| HP            | EliteBook 8460p             | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Dell          | Inspiron 5770               | [fc12718113](https://linux-hardware.org/?probe=fc12718113) | Mar 13, 2022 |
| Dell          | Inspiron 5770               | [8a7c1daf70](https://linux-hardware.org/?probe=8a7c1daf70) | Mar 13, 2022 |
| Dell          | XPS 15 9550                 | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Acer          | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [96aa797713](https://linux-hardware.org/?probe=96aa797713) | Feb 21, 2022 |
| Toshiba       | Satellite Pro R50-C         | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| Dell          | Inspiron 5415               | [3324e66890](https://linux-hardware.org/?probe=3324e66890) | Feb 15, 2022 |
| Dell          | Inspiron 5415               | [c2bd021f7e](https://linux-hardware.org/?probe=c2bd021f7e) | Feb 13, 2022 |
| ASUSTek       | K55A                        | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| System76      | Lemur Pro                   | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| Acer          | Aspire ES1-411              | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo        | ThinkPad T470 20HES23B0U    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Acer          | Aspire A715-42G             | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| Toshiba       | PORTEGE R930                | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| HP            | ProBook 450 G2              | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Star Labs     | LabTop                      | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Acer          | Swift SF314-41              | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| ASUSTek       | UX303LAB                    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| Google        | Kip                         | [8c60d949d0](https://linux-hardware.org/?probe=8c60d949d0) | Dec 20, 2021 |
| Acer          | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Dell          | System XPS L702X            | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| HP            | Laptop 15-bs0xx             | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| Acer          | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9fc484d01e](https://linux-hardware.org/?probe=9fc484d01e) | Nov 11, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [edc363bc59](https://linux-hardware.org/?probe=edc363bc59) | Nov 11, 2021 |
| Timi          | A30                         | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| Dell          | Vostro 14 5410              | [b6966ebc42](https://linux-hardware.org/?probe=b6966ebc42) | Oct 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| HP            | Spectre x2 Detachable       | [d20c059f3d](https://linux-hardware.org/?probe=d20c059f3d) | Oct 24, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| Dell          | Latitude 7490               | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| HP            | Pavilion tx2500             | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Dell          | Latitude 7285               | [5097e0f8c8](https://linux-hardware.org/?probe=5097e0f8c8) | Oct 14, 2021 |
| Acer          | Aspire VN7-593G             | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| HP            | Pavilion g6                 | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| HP            | EliteBook 2170p             | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| MSI           | GE66 Raider 10SF            | [9d11ef435a](https://linux-hardware.org/?probe=9d11ef435a) | Sep 16, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| Acer          | TravelMate 5760             | [eb8b4b37a4](https://linux-hardware.org/?probe=eb8b4b37a4) | Sep 13, 2021 |
| Acer          | TravelMate 5760             | [a0376eeefc](https://linux-hardware.org/?probe=a0376eeefc) | Sep 13, 2021 |
| Dell          | XPS 15 9500                 | [83bf40cb1d](https://linux-hardware.org/?probe=83bf40cb1d) | Sep 12, 2021 |
| Dell          | XPS 15 9500                 | [65102530f5](https://linux-hardware.org/?probe=65102530f5) | Sep 12, 2021 |
| HP            | EliteBook 8560p             | [48828ad0d3](https://linux-hardware.org/?probe=48828ad0d3) | Sep 10, 2021 |
| Dell          | System XPS L702X            | [e0ff0245fb](https://linux-hardware.org/?probe=e0ff0245fb) | Sep 10, 2021 |
| Toshiba       | Satellite C50D-C            | [af1933f8ad](https://linux-hardware.org/?probe=af1933f8ad) | Sep 09, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| Lenovo        | B50-30 20382                | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Medion        | P6815                       | [e3e586bafe](https://linux-hardware.org/?probe=e3e586bafe) | Aug 29, 2021 |
| Medion        | P6815                       | [46b6aaf8c5](https://linux-hardware.org/?probe=46b6aaf8c5) | Aug 29, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| HP            | Pavilion dv6                | [c1ad958c3f](https://linux-hardware.org/?probe=c1ad958c3f) | Aug 28, 2021 |
| Lenovo        | B50-30 20382                | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| Sony          | VPCEB43FG                   | [4a81e892f0](https://linux-hardware.org/?probe=4a81e892f0) | Aug 26, 2021 |
| Dell          | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [efeb81eaea](https://linux-hardware.org/?probe=efeb81eaea) | Aug 21, 2021 |
| Dell          | XPS 15 9500                 | [1216df6214](https://linux-hardware.org/?probe=1216df6214) | Aug 19, 2021 |
| TWG           | E2017                       | [3f335e736c](https://linux-hardware.org/?probe=3f335e736c) | Aug 18, 2021 |
| Dell          | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Toshiba       | Satellite C50D-C            | [dda3acac30](https://linux-hardware.org/?probe=dda3acac30) | Aug 08, 2021 |
| Samsung       | RC410/RC510/RC710           | [4e03a59c3f](https://linux-hardware.org/?probe=4e03a59c3f) | Aug 03, 2021 |
| Samsung       | RC410/RC510/RC710           | [37550654db](https://linux-hardware.org/?probe=37550654db) | Aug 03, 2021 |
| Lenovo        | V15-IIL 82C5                | [20007580cb](https://linux-hardware.org/?probe=20007580cb) | Aug 01, 2021 |
| Lenovo        | V15-IIL 82C5                | [359e3c40ca](https://linux-hardware.org/?probe=359e3c40ca) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [812ba32a31](https://linux-hardware.org/?probe=812ba32a31) | Aug 01, 2021 |
| HP            | Pavilion g6                 | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [cc238ca2aa](https://linux-hardware.org/?probe=cc238ca2aa) | Jul 30, 2021 |
| HP            | Spectre x2 Detachable       | [7b96d53aa9](https://linux-hardware.org/?probe=7b96d53aa9) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [2a54318c46](https://linux-hardware.org/?probe=2a54318c46) | Jul 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [c499631e7e](https://linux-hardware.org/?probe=c499631e7e) | Jul 19, 2021 |
| HP            | Laptop 14s-dk0xxx           | [0acaedd30c](https://linux-hardware.org/?probe=0acaedd30c) | Jul 13, 2021 |
| HP            | Laptop 14s-dk0xxx           | [f655e1ca50](https://linux-hardware.org/?probe=f655e1ca50) | Jul 12, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [331968a8d9](https://linux-hardware.org/?probe=331968a8d9) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [59e9a66bff](https://linux-hardware.org/?probe=59e9a66bff) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [e20b747527](https://linux-hardware.org/?probe=e20b747527) | Jul 03, 2021 |
| Sony          | SVE14A15FGS                 | [adb8d0cc94](https://linux-hardware.org/?probe=adb8d0cc94) | Jun 14, 2021 |
| Acer          | Aspire A715-71G             | [cb59081351](https://linux-hardware.org/?probe=cb59081351) | Jun 14, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [e82b7b36f2](https://linux-hardware.org/?probe=e82b7b36f2) | Jun 12, 2021 |
| ASUSTek       | K52Jc                       | [4b93dc4ee8](https://linux-hardware.org/?probe=4b93dc4ee8) | Jun 07, 2021 |
| HP            | ProBook 650 G1              | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| HP            | EliteBook 8560p             | [ea1bd5e314](https://linux-hardware.org/?probe=ea1bd5e314) | May 30, 2021 |
| Sony          | SVE11126CGB                 | [b7ee22588d](https://linux-hardware.org/?probe=b7ee22588d) | May 29, 2021 |
| Toshiba       | Satellite S70t-B            | [33d64c7a69](https://linux-hardware.org/?probe=33d64c7a69) | May 26, 2021 |
| Toshiba       | Satellite S70t-B            | [60c1bab5d9](https://linux-hardware.org/?probe=60c1bab5d9) | May 26, 2021 |
| HP            | Pavilion Notebook           | [37695077ba](https://linux-hardware.org/?probe=37695077ba) | May 21, 2021 |
| HP            | ENVY 15                     | [2a23609955](https://linux-hardware.org/?probe=2a23609955) | May 15, 2021 |
| Acer          | E5-571-551U                 | [152105400d](https://linux-hardware.org/?probe=152105400d) | May 05, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Lenovo        | V110-15IAP 80TG             | [76ac42ca9c](https://linux-hardware.org/?probe=76ac42ca9c) | Apr 30, 2021 |
| MSI           | GS63VR 7RF                  | [4a7125aec0](https://linux-hardware.org/?probe=4a7125aec0) | Apr 18, 2021 |
| MSI           | GS63VR 7RF                  | [76126cd5fd](https://linux-hardware.org/?probe=76126cd5fd) | Apr 18, 2021 |
| Toshiba       | PORTEGE M930                | [aac37423e5](https://linux-hardware.org/?probe=aac37423e5) | Apr 13, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d65bc55ad0](https://linux-hardware.org/?probe=d65bc55ad0) | Apr 11, 2021 |
| Apple         | MacBook7,1                  | [9b4e89202e](https://linux-hardware.org/?probe=9b4e89202e) | Apr 09, 2021 |
| HP            | ProBook 650 G1              | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | EliteBook 2560p             | [ecdecf72ec](https://linux-hardware.org/?probe=ecdecf72ec) | Mar 30, 2021 |
| HP            | ProBook 650 G1              | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| HP            | ZBook Firefly 15 G7 Mobi... | [0653cc5343](https://linux-hardware.org/?probe=0653cc5343) | Mar 29, 2021 |
| Metabox       | X170SM                      | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox       | X170SM                      | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| HP            | ProBook 4540s               | [4fe9e650c2](https://linux-hardware.org/?probe=4fe9e650c2) | Mar 13, 2021 |
| HP            | ProBook 4540s               | [d2c0c69a0d](https://linux-hardware.org/?probe=d2c0c69a0d) | Mar 13, 2021 |
| Acer          | Aspire 5750                 | [6aaf201a58](https://linux-hardware.org/?probe=6aaf201a58) | Mar 10, 2021 |
| Toshiba       | Satellite U920t             | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | [b1088bed99](https://linux-hardware.org/?probe=b1088bed99) | Feb 26, 2021 |
| Dell          | XPS 13 9360                 | [7de34c9abe](https://linux-hardware.org/?probe=7de34c9abe) | Feb 26, 2021 |
| HP            | ZBook 14                    | [042b4b4a48](https://linux-hardware.org/?probe=042b4b4a48) | Feb 26, 2021 |
| Dell          | Latitude E6430s             | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| Dell          | Latitude 7285               | [844392cd2c](https://linux-hardware.org/?probe=844392cd2c) | Feb 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [d20e5c1f85](https://linux-hardware.org/?probe=d20e5c1f85) | Feb 15, 2021 |
| HP            | EliteBook 820 G3            | [e1a72b607e](https://linux-hardware.org/?probe=e1a72b607e) | Feb 14, 2021 |
| Dell          | Latitude E4300              | [a09ca20174](https://linux-hardware.org/?probe=a09ca20174) | Feb 14, 2021 |
| HP            | Notebook                    | [e5bc3a0317](https://linux-hardware.org/?probe=e5bc3a0317) | Feb 12, 2021 |
| MSI           | GE66 Raider 10SF            | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| HP            | 355 G2                      | [ac856a41b8](https://linux-hardware.org/?probe=ac856a41b8) | Feb 03, 2021 |
| Acer          | ES1-512-P8NA                | [c393cb6ad4](https://linux-hardware.org/?probe=c393cb6ad4) | Jan 24, 2021 |
| HP            | ProBook 450 G3              | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
| Toshiba       | Satellite U920t             | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [ecc872dc4a](https://linux-hardware.org/?probe=ecc872dc4a) | Jan 16, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [3c308a7199](https://linux-hardware.org/?probe=3c308a7199) | Jan 15, 2021 |
| Acer          | ConceptD CN315-71P          | [7d1c394d7a](https://linux-hardware.org/?probe=7d1c394d7a) | Dec 26, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| Lenovo        | ThinkPad P52 20M9000KUS     | [ed51fc90e5](https://linux-hardware.org/?probe=ed51fc90e5) | Dec 19, 2020 |
| HP            | ZBook Studio G5             | [af0417cef5](https://linux-hardware.org/?probe=af0417cef5) | Dec 10, 2020 |
| Dell          | Precision 7530              | [c82b4c0f51](https://linux-hardware.org/?probe=c82b4c0f51) | Dec 03, 2020 |
| HP            | Pavilion dv6                | [2c1cf2da53](https://linux-hardware.org/?probe=2c1cf2da53) | Nov 30, 2020 |
| eMachines     | eM350                       | [0ba740f085](https://linux-hardware.org/?probe=0ba740f085) | Nov 28, 2020 |
| Dell          | XPS 15 9560                 | [463c0c961e](https://linux-hardware.org/?probe=463c0c961e) | Nov 15, 2020 |
| Dell          | Latitude D630               | [4b5f3f19ae](https://linux-hardware.org/?probe=4b5f3f19ae) | Nov 14, 2020 |
| Toshiba       | Satellite Pro L830          | [97a68dd7c5](https://linux-hardware.org/?probe=97a68dd7c5) | Nov 14, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [3ffb0e062e](https://linux-hardware.org/?probe=3ffb0e062e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [7e7b6fe785](https://linux-hardware.org/?probe=7e7b6fe785) | Nov 13, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [0001b76ceb](https://linux-hardware.org/?probe=0001b76ceb) | Nov 10, 2020 |
| Acer          | Aspire ES1-511              | [13485ce10c](https://linux-hardware.org/?probe=13485ce10c) | Nov 08, 2020 |
| Acer          | Aspire ES1-511              | [903c4d5729](https://linux-hardware.org/?probe=903c4d5729) | Nov 08, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [c4d3f6f37d](https://linux-hardware.org/?probe=c4d3f6f37d) | Nov 07, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [841d75822e](https://linux-hardware.org/?probe=841d75822e) | Nov 04, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | [41c93bb503](https://linux-hardware.org/?probe=41c93bb503) | Oct 29, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | [7678291690](https://linux-hardware.org/?probe=7678291690) | Oct 28, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [bacac44e9d](https://linux-hardware.org/?probe=bacac44e9d) | Oct 26, 2020 |
| HP            | ProBook 6550b               | [d93b3bfeac](https://linux-hardware.org/?probe=d93b3bfeac) | Oct 22, 2020 |
| Toshiba       | Satellite C660              | [d8ac831c61](https://linux-hardware.org/?probe=d8ac831c61) | Oct 20, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [8720432e33](https://linux-hardware.org/?probe=8720432e33) | Oct 16, 2020 |
| ASUSTek       | X550EP                      | [f13a8d8d9b](https://linux-hardware.org/?probe=f13a8d8d9b) | Oct 15, 2020 |
| Dell          | XPS 13 9360                 | [8cf28e044c](https://linux-hardware.org/?probe=8cf28e044c) | Oct 11, 2020 |
| HP            | Compaq Presario A900        | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| HP            | Laptop 15s-fq1xxx           | [b3ae2a4d2c](https://linux-hardware.org/?probe=b3ae2a4d2c) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | Swift SF314-41              | [26350d0806](https://linux-hardware.org/?probe=26350d0806) | Oct 04, 2020 |
| HP            | Compaq CQ45                 | [ea61076771](https://linux-hardware.org/?probe=ea61076771) | Sep 30, 2020 |
| MSI           | GP75 Leopard 9SD            | [9c152a1117](https://linux-hardware.org/?probe=9c152a1117) | Sep 30, 2020 |
| HP            | Compaq CQ45                 | [f62190e31d](https://linux-hardware.org/?probe=f62190e31d) | Sep 29, 2020 |
| HP            | EliteBook 850 G5            | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Apple         | MacBook5,1                  | [fb2f9dd279](https://linux-hardware.org/?probe=fb2f9dd279) | Sep 24, 2020 |
| HP            | EliteBook Folio 1040 G1     | [0848bad0d4](https://linux-hardware.org/?probe=0848bad0d4) | Sep 23, 2020 |
| Apple         | MacBook5,1                  | [ad39052e7a](https://linux-hardware.org/?probe=ad39052e7a) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [616e26ca49](https://linux-hardware.org/?probe=616e26ca49) | Sep 20, 2020 |
| HP            | ProBook 450 G5              | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| HP            | ProBook 6560b               | [109cd57459](https://linux-hardware.org/?probe=109cd57459) | Sep 12, 2020 |
| Dell          | Latitude E6430s             | [bd8ab4dd1c](https://linux-hardware.org/?probe=bd8ab4dd1c) | Sep 08, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [b673064c0f](https://linux-hardware.org/?probe=b673064c0f) | Sep 08, 2020 |
| Acer          | Aspire 5750                 | [b65a1db938](https://linux-hardware.org/?probe=b65a1db938) | Sep 07, 2020 |
| Toshiba       | Satellite C50-B             | [167e9daeb7](https://linux-hardware.org/?probe=167e9daeb7) | Sep 05, 2020 |
| HP            | Pavilion dv6                | [4c2298d7bb](https://linux-hardware.org/?probe=4c2298d7bb) | Sep 05, 2020 |
| Dell          | Latitude E7440              | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| HP            | Laptop 15-db0xxx            | [3949b5f183](https://linux-hardware.org/?probe=3949b5f183) | Sep 04, 2020 |
| Dell          | Inspiron 5567               | [ab299d27a4](https://linux-hardware.org/?probe=ab299d27a4) | Sep 04, 2020 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [9c1bd6b943](https://linux-hardware.org/?probe=9c1bd6b943) | Sep 03, 2020 |
| MSI           | GT80S 6QD                   | [e14f86e038](https://linux-hardware.org/?probe=e14f86e038) | Sep 03, 2020 |
| Acer          | Aspire 5750                 | [6c84136b17](https://linux-hardware.org/?probe=6c84136b17) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [c9cf3aef22](https://linux-hardware.org/?probe=c9cf3aef22) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [65612b9b8f](https://linux-hardware.org/?probe=65612b9b8f) | Sep 03, 2020 |
| Toshiba       | Satellite C660              | [e7791768a3](https://linux-hardware.org/?probe=e7791768a3) | Sep 02, 2020 |
| Toshiba       | Satellite C50-B             | [186e22ea8c](https://linux-hardware.org/?probe=186e22ea8c) | Sep 01, 2020 |
| Dell          | XPS 15 9570                 | [cb17688de8](https://linux-hardware.org/?probe=cb17688de8) | Sep 01, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [4d92725c5a](https://linux-hardware.org/?probe=4d92725c5a) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [1707834024](https://linux-hardware.org/?probe=1707834024) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [db76b91e62](https://linux-hardware.org/?probe=db76b91e62) | Aug 21, 2020 |
| HP            | Pavilion dv6                | [65033f4392](https://linux-hardware.org/?probe=65033f4392) | Aug 19, 2020 |
| MSI           | GE66 Raider 10SF            | [3bcf471b04](https://linux-hardware.org/?probe=3bcf471b04) | Aug 15, 2020 |
| Dell          | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| System76      | Lemur Pro                   | [c2619f1014](https://linux-hardware.org/?probe=c2619f1014) | Aug 14, 2020 |
| MSI           | GT72 2PC                    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [fb69c1f324](https://linux-hardware.org/?probe=fb69c1f324) | Aug 10, 2020 |
| Apple         | MacBookPro5,5               | [37d32b3bac](https://linux-hardware.org/?probe=37d32b3bac) | Aug 03, 2020 |
| Apple         | MacBookPro5,5               | [6aee03b649](https://linux-hardware.org/?probe=6aee03b649) | Jul 31, 2020 |
| HP            | Pavilion dv4                | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| MSI           | GE66 Raider 10SF            | [3dcde22239](https://linux-hardware.org/?probe=3dcde22239) | Jul 25, 2020 |
| HP            | Laptop 15-dy0xxx            | [cad2dbb88f](https://linux-hardware.org/?probe=cad2dbb88f) | Jul 25, 2020 |
| HP            | ProBook 450 G5              | [a8dfd5a806](https://linux-hardware.org/?probe=a8dfd5a806) | Jul 21, 2020 |
| HP            | Laptop 15-dy0xxx            | [e471bc69b2](https://linux-hardware.org/?probe=e471bc69b2) | Jul 21, 2020 |
| Dell          | Latitude E5570              | [6408e82f4f](https://linux-hardware.org/?probe=6408e82f4f) | Jul 20, 2020 |
| HP            | EliteBook 840 G1            | [75a2e58b47](https://linux-hardware.org/?probe=75a2e58b47) | Jun 30, 2020 |
| HP            | EliteBook 8560p             | [e83d7e33f2](https://linux-hardware.org/?probe=e83d7e33f2) | Jun 29, 2020 |
| HP            | EliteBook 840 G6            | [9fccdcc42f](https://linux-hardware.org/?probe=9fccdcc42f) | Jun 25, 2020 |
| HP            | ProBook 650 G1              | [d8e10f56ec](https://linux-hardware.org/?probe=d8e10f56ec) | Jun 24, 2020 |
| MSI           | GE66 Raider 10SF            | [ca5d80f8f9](https://linux-hardware.org/?probe=ca5d80f8f9) | Jun 16, 2020 |
| MSI           | GE66 Raider 10SF            | [220b2a94c8](https://linux-hardware.org/?probe=220b2a94c8) | Jun 10, 2020 |
| HP            | ProBook 4540s               | [b28f2f3b8a](https://linux-hardware.org/?probe=b28f2f3b8a) | Jun 05, 2020 |
| HP            | Presario CQ56               | [4eed3fc6f6](https://linux-hardware.org/?probe=4eed3fc6f6) | Jun 05, 2020 |
| MSI           | GE66 Raider 10SF            | [8c0b76c629](https://linux-hardware.org/?probe=8c0b76c629) | Jun 01, 2020 |
| Acer          | Aspire E1-571               | [25ca966875](https://linux-hardware.org/?probe=25ca966875) | Jun 01, 2020 |
| MSI           | GE66 Raider 10SF            | [1cb7bb7ad9](https://linux-hardware.org/?probe=1cb7bb7ad9) | May 23, 2020 |
| MSI           | GE66 Raider 10SF            | [afec91ff4d](https://linux-hardware.org/?probe=afec91ff4d) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| HP            | EliteBook 8560p             | [5439d2f06b](https://linux-hardware.org/?probe=5439d2f06b) | May 22, 2020 |
| Dell          | Latitude E6430s             | [891fd84ed1](https://linux-hardware.org/?probe=891fd84ed1) | May 21, 2020 |
| Dell          | Latitude E6430s             | [b2f67f2744](https://linux-hardware.org/?probe=b2f67f2744) | May 20, 2020 |
| Sony          | VPCEH28FG                   | [f241603946](https://linux-hardware.org/?probe=f241603946) | May 17, 2020 |
| Lenovo        | ThinkPad E590 20NBS0SC00    | [50ca962181](https://linux-hardware.org/?probe=50ca962181) | May 14, 2020 |
| HP            | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| HP            | EliteBook 8560p             | [605660fceb](https://linux-hardware.org/?probe=605660fceb) | May 11, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | [d1258905c6](https://linux-hardware.org/?probe=d1258905c6) | May 10, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | [51adfc765c](https://linux-hardware.org/?probe=51adfc765c) | May 10, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [8ca322cd11](https://linux-hardware.org/?probe=8ca322cd11) | May 06, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [e0d0592e34](https://linux-hardware.org/?probe=e0d0592e34) | May 05, 2020 |
| HP            | ProBook 650 G1              | [ed42eb842d](https://linux-hardware.org/?probe=ed42eb842d) | May 04, 2020 |
| HP            | ProBook 650 G1              | [d29d76cb5c](https://linux-hardware.org/?probe=d29d76cb5c) | May 04, 2020 |
| HP            | Presario CQ57               | [df09ee9161](https://linux-hardware.org/?probe=df09ee9161) | Apr 26, 2020 |
| Toshiba       | TECRA Z50-A                 | [ff5b768627](https://linux-hardware.org/?probe=ff5b768627) | Apr 21, 2020 |
| Acer          | Aspire A315-21G             | [7f9e52f0dd](https://linux-hardware.org/?probe=7f9e52f0dd) | Apr 20, 2020 |
| Acer          | Aspire A315-21G             | [4409c8dae5](https://linux-hardware.org/?probe=4409c8dae5) | Apr 20, 2020 |
| HP            | Pavilion g6                 | [15ad84ee0f](https://linux-hardware.org/?probe=15ad84ee0f) | Apr 15, 2020 |
| Dell          | XPS 13 9360                 | [89cce1b8b6](https://linux-hardware.org/?probe=89cce1b8b6) | Apr 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e4ed30a655](https://linux-hardware.org/?probe=e4ed30a655) | Apr 04, 2020 |
| Toshiba       | Satellite L750              | [391a50ded4](https://linux-hardware.org/?probe=391a50ded4) | Apr 03, 2020 |
| ASUSTek       | N56VZ                       | [04666ab26e](https://linux-hardware.org/?probe=04666ab26e) | Apr 01, 2020 |
| HP            | Pavilion 10 TS              | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0c505fcd69](https://linux-hardware.org/?probe=0c505fcd69) | Mar 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [fc12fa3a4d](https://linux-hardware.org/?probe=fc12fa3a4d) | Mar 25, 2020 |
| Dell          | Precision M6800             | [adb3b768f7](https://linux-hardware.org/?probe=adb3b768f7) | Mar 24, 2020 |
| ASUSTek       | TAICHI21                    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| HP            | EliteBook 840 G6            | [a26150e202](https://linux-hardware.org/?probe=a26150e202) | Mar 07, 2020 |
| HP            | EliteBook 840 G6            | [0d6d26562c](https://linux-hardware.org/?probe=0d6d26562c) | Mar 07, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [f49a66ef1e](https://linux-hardware.org/?probe=f49a66ef1e) | Feb 25, 2020 |
| HP            | Pavilion 15                 | [72784962fe](https://linux-hardware.org/?probe=72784962fe) | Feb 25, 2020 |
| HP            | Pavilion 15                 | [a1e89aa309](https://linux-hardware.org/?probe=a1e89aa309) | Feb 25, 2020 |
| Dell          | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| HP            | EliteBook x360 1040 G6      | [a838427772](https://linux-hardware.org/?probe=a838427772) | Feb 12, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [5f61d3d553](https://linux-hardware.org/?probe=5f61d3d553) | Feb 09, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| HP            | ProBook 650 G1              | [b5d441afe1](https://linux-hardware.org/?probe=b5d441afe1) | Feb 01, 2020 |
| Lenovo        | V110-14IAP 80TF             | [85b3202273](https://linux-hardware.org/?probe=85b3202273) | Jan 30, 2020 |
| Dell          | XPS 13 9360                 | [c770de6326](https://linux-hardware.org/?probe=c770de6326) | Jan 25, 2020 |
| Lenovo        | ThinkPad X131e 33691A4      | [a30712cd7d](https://linux-hardware.org/?probe=a30712cd7d) | Jan 22, 2020 |
| HP            | Notebook                    | [8f2fc8e2ec](https://linux-hardware.org/?probe=8f2fc8e2ec) | Jan 09, 2020 |
| ASUSTek       | K46CB                       | [45b756e92d](https://linux-hardware.org/?probe=45b756e92d) | Jan 04, 2020 |
| ASUSTek       | K46CB                       | [1a25890709](https://linux-hardware.org/?probe=1a25890709) | Jan 04, 2020 |
| HP            | ProBook 650 G1              | [0763c1c109](https://linux-hardware.org/?probe=0763c1c109) | Jan 02, 2020 |
| HP            | ProBook 650 G1              | [023556890d](https://linux-hardware.org/?probe=023556890d) | Jan 02, 2020 |
| Acer          | Aspire F5-573G              | [ead658852a](https://linux-hardware.org/?probe=ead658852a) | Jan 01, 2020 |
| Acer          | Aspire F5-573G              | [e19db7603d](https://linux-hardware.org/?probe=e19db7603d) | Jan 01, 2020 |
| HP            | ProBook 6550b               | [65a8d66fb9](https://linux-hardware.org/?probe=65a8d66fb9) | Dec 31, 2019 |
| HP            | ProBook 650 G1              | [0085227124](https://linux-hardware.org/?probe=0085227124) | Dec 30, 2019 |
| HP            | EliteBook 850 G5            | [65b1eb0ca1](https://linux-hardware.org/?probe=65b1eb0ca1) | Dec 26, 2019 |
| Lenovo        | ThinkPad T420 4180AQ3       | [4da7aff7a2](https://linux-hardware.org/?probe=4da7aff7a2) | Dec 23, 2019 |
| ASUSTek       | UL50Ag                      | [ba1e7f648c](https://linux-hardware.org/?probe=ba1e7f648c) | Dec 19, 2019 |
| MSI           | GT72 2PC                    | [dbe1269ea7](https://linux-hardware.org/?probe=dbe1269ea7) | Dec 11, 2019 |
| HP            | Pavilion g6                 | [3acb153d5d](https://linux-hardware.org/?probe=3acb153d5d) | Dec 06, 2019 |
| HP            | EliteBook 6930p             | [94af8c86b1](https://linux-hardware.org/?probe=94af8c86b1) | Dec 03, 2019 |
| HP            | Pavilion g6                 | [034500d792](https://linux-hardware.org/?probe=034500d792) | Nov 26, 2019 |
| Dell          | Latitude 7285               | [87a44ef029](https://linux-hardware.org/?probe=87a44ef029) | Nov 22, 2019 |
| Dell          | Latitude 7285               | [34937530ea](https://linux-hardware.org/?probe=34937530ea) | Nov 21, 2019 |
| HP            | Notebook                    | [31d1bef6c1](https://linux-hardware.org/?probe=31d1bef6c1) | Nov 11, 2019 |
| HP            | ProBook 4540s               | [5cc8316a85](https://linux-hardware.org/?probe=5cc8316a85) | Nov 08, 2019 |
| HP            | ProBook 4730s               | [ed03fd8077](https://linux-hardware.org/?probe=ed03fd8077) | Oct 29, 2019 |
| HP            | ProBook 4730s               | [cd284908ca](https://linux-hardware.org/?probe=cd284908ca) | Oct 28, 2019 |
| HP            | Notebook                    | [1bccff3cda](https://linux-hardware.org/?probe=1bccff3cda) | Sep 25, 2019 |
| Toshiba       | PORTEGE M780                | [64824e5a04](https://linux-hardware.org/?probe=64824e5a04) | Sep 21, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [8e78a0ebf5](https://linux-hardware.org/?probe=8e78a0ebf5) | Sep 11, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [fd27e8c70f](https://linux-hardware.org/?probe=fd27e8c70f) | Sep 11, 2019 |
| HP            | Notebook                    | [776ffefbc2](https://linux-hardware.org/?probe=776ffefbc2) | Sep 11, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [f5b3521c55](https://linux-hardware.org/?probe=f5b3521c55) | Sep 11, 2019 |
| HP            | Notebook                    | [cf646ad1f2](https://linux-hardware.org/?probe=cf646ad1f2) | Sep 11, 2019 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [873e28fce7](https://linux-hardware.org/?probe=873e28fce7) | Sep 02, 2019 |
| HP            | Compaq 6910p (GM903PA#AB... | [2724623348](https://linux-hardware.org/?probe=2724623348) | Aug 12, 2019 |
| ASUSTek       | X542UQ                      | [7a4797b166](https://linux-hardware.org/?probe=7a4797b166) | Aug 11, 2019 |
| HP            | ProBook 6570b               | [4f80f9ba3c](https://linux-hardware.org/?probe=4f80f9ba3c) | Aug 04, 2019 |
| Lenovo        | ThinkPad T440p 20AWS1J00... | [31bcd5a103](https://linux-hardware.org/?probe=31bcd5a103) | Jul 31, 2019 |
| HP            | ProBook 450 G3              | [b9e21a89da](https://linux-hardware.org/?probe=b9e21a89da) | Jul 23, 2019 |
| HP            | ProBook 650 G1              | [6d584d5dab](https://linux-hardware.org/?probe=6d584d5dab) | Jul 22, 2019 |
| HP            | ProBook 450 G3              | [10b8987b19](https://linux-hardware.org/?probe=10b8987b19) | Jul 17, 2019 |
| HP            | ProBook 6550b               | [801f83247c](https://linux-hardware.org/?probe=801f83247c) | Jul 06, 2019 |
| HP            | ProBook 4730s               | [ed98a45d81](https://linux-hardware.org/?probe=ed98a45d81) | Jul 01, 2019 |
| Acer          | Aspire 5100                 | [a28f7b2623](https://linux-hardware.org/?probe=a28f7b2623) | Jun 27, 2019 |
| Acer          | Aspire 5100                 | [aa61fb2b9c](https://linux-hardware.org/?probe=aa61fb2b9c) | Jun 11, 2019 |
| YJKC          | vBOOK Plus                  | [80eae9ed5f](https://linux-hardware.org/?probe=80eae9ed5f) | Jun 09, 2019 |
| HP            | Unknown                     | [ef6ea82cf5](https://linux-hardware.org/?probe=ef6ea82cf5) | May 20, 2019 |
| ASUSTek       | K84L                        | [231a7d9bc6](https://linux-hardware.org/?probe=231a7d9bc6) | Apr 18, 2019 |
| HP            | ProBook 6570b               | [42129ed417](https://linux-hardware.org/?probe=42129ed417) | Mar 23, 2019 |
| HP            | ProBook 6570b               | [25a7d4cca8](https://linux-hardware.org/?probe=25a7d4cca8) | Mar 03, 2019 |
| Acer          | Aspire E5-721               | [e6dca4d6fd](https://linux-hardware.org/?probe=e6dca4d6fd) | Feb 28, 2019 |
| HP            | Mini 110-1100               | [1ba5e0d0b2](https://linux-hardware.org/?probe=1ba5e0d0b2) | Feb 23, 2019 |
| HP            | ProBook 6570b               | [82e153050f](https://linux-hardware.org/?probe=82e153050f) | Jan 28, 2019 |
| HP            | ProBook 650 G1              | [2756a314e5](https://linux-hardware.org/?probe=2756a314e5) | Jan 14, 2019 |
| HP            | ProBook 650 G1              | [f81c16faea](https://linux-hardware.org/?probe=f81c16faea) | Jan 14, 2019 |
| Lenovo        | B590 20208                  | [7c06278f98](https://linux-hardware.org/?probe=7c06278f98) | Dec 28, 2018 |
| Lenovo        | B590 20208                  | [d4897cc9d7](https://linux-hardware.org/?probe=d4897cc9d7) | Dec 28, 2018 |
| HP            | Pavilion 15                 | [5407e9ab05](https://linux-hardware.org/?probe=5407e9ab05) | Dec 22, 2018 |
| HP            | Pavilion 15                 | [a47a651328](https://linux-hardware.org/?probe=a47a651328) | Dec 22, 2018 |
| HP            | 14                          | [553085d233](https://linux-hardware.org/?probe=553085d233) | Jul 06, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 34        | 11.68%  |
| Ubuntu 18.04        | 15        | 5.15%   |
| OpenMandriva 4.3    | 11        | 3.78%   |
| Arch                | 10        | 3.44%   |
| Zorin 15            | 9         | 3.09%   |
| Pop!_OS 20.04       | 8         | 2.75%   |
| OpenMandriva 4.2    | 8         | 2.75%   |
| Zorin 16            | 7         | 2.41%   |
| Ubuntu 22.04        | 7         | 2.41%   |
| Pop!_OS 22.04       | 7         | 2.41%   |
| Debian 11           | 7         | 2.41%   |
| Arch Rolling        | 7         | 2.41%   |
| Ubuntu 21.10        | 6         | 2.06%   |
| Ubuntu 20.10        | 6         | 2.06%   |
| Linux Mint 20.2     | 6         | 2.06%   |
| Fedora 31           | 6         | 2.06%   |
| Debian 10           | 6         | 2.06%   |
| Pop!_OS 20.10       | 5         | 1.72%   |
| Fedora 35           | 5         | 1.72%   |
| Ubuntu 21.04        | 4         | 1.37%   |
| Pop!_OS 21.04       | 4         | 1.37%   |
| Manjaro             | 4         | 1.37%   |
| Linux Mint 20.3     | 4         | 1.37%   |
| Linux Mint 19.2     | 4         | 1.37%   |
| Kubuntu 20.04       | 4         | 1.37%   |
| Fedora 34           | 4         | 1.37%   |
| Fedora 33           | 4         | 1.37%   |
| Ubuntu 19.10        | 3         | 1.03%   |
| Linux Mint 20       | 3         | 1.03%   |
| Linux Mint 19.3     | 3         | 1.03%   |
| Linux Mint 19.1     | 3         | 1.03%   |
| Fedora 36           | 3         | 1.03%   |
| Fedora 32           | 3         | 1.03%   |
| EndeavourOS Rolling | 3         | 1.03%   |
| Elementary 6.1      | 3         | 1.03%   |
| Ubuntu 19.04        | 2         | 0.69%   |
| ROSA R10            | 2         | 0.69%   |
| Pop!_OS 21.10       | 2         | 0.69%   |
| MX 21               | 2         | 0.69%   |
| Linux Mint 21       | 2         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 75        | 27.17%  |
| Linux Mint   | 26        | 9.42%   |
| Pop!_OS      | 25        | 9.06%   |
| Fedora       | 24        | 8.7%    |
| OpenMandriva | 19        | 6.88%   |
| Arch         | 17        | 6.16%   |
| Zorin        | 16        | 5.8%    |
| Debian       | 15        | 5.43%   |
| Manjaro      | 9         | 3.26%   |
| Kubuntu      | 6         | 2.17%   |
| Endless      | 5         | 1.81%   |
| Elementary   | 5         | 1.81%   |
| EndeavourOS  | 4         | 1.45%   |
| Xubuntu      | 3         | 1.09%   |
| Ubuntu Unity | 3         | 1.09%   |
| Ubuntu MATE  | 2         | 0.72%   |
| Solus        | 2         | 0.72%   |
| ROSA         | 2         | 0.72%   |
| MX           | 2         | 0.72%   |
| Lubuntu      | 2         | 0.72%   |
| LMDE         | 2         | 0.72%   |
| KDE neon     | 2         | 0.72%   |
| Gentoo       | 2         | 0.72%   |
| Void Linux   | 1         | 0.36%   |
| Peppermint   | 1         | 0.36%   |
| Parrot       | 1         | 0.36%   |
| openSUSE     | 1         | 0.36%   |
| Kali         | 1         | 0.36%   |
| BlackPanther | 1         | 0.36%   |
| ArcoLinux    | 1         | 0.36%   |
| Archman      | 1         | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 3.75%   |
| 5.16.7-desktop-1omv4003  | 10        | 3.13%   |
| 5.10.14-desktop-1omv4002 | 8         | 2.5%    |
| 5.15.0-46-generic        | 7         | 2.19%   |
| 5.4.0-48-generic         | 5         | 1.56%   |
| 5.3.0-28-generic         | 5         | 1.56%   |
| 5.3.16-300.fc31.x86_64   | 4         | 1.25%   |
| 5.17.5-76051705-generic  | 4         | 1.25%   |
| 5.11.0-7620-generic      | 4         | 1.25%   |
| 5.11.0-27-generic        | 4         | 1.25%   |
| 5.8.0-53-generic         | 3         | 0.94%   |
| 5.4.0-81-generic         | 3         | 0.94%   |
| 5.4.0-7642-generic       | 3         | 0.94%   |
| 5.4.0-74-generic         | 3         | 0.94%   |
| 5.4.0-65-generic         | 3         | 0.94%   |
| 5.4.0-45-generic         | 3         | 0.94%   |
| 5.4.0-26-generic         | 3         | 0.94%   |
| 5.13.0-37-generic        | 3         | 0.94%   |
| 5.0.0-37-generic         | 3         | 0.94%   |
| 4.19.0-9-amd64           | 3         | 0.94%   |
| 5.8.11-1-MANJARO         | 2         | 0.63%   |
| 5.8.0-7630-generic       | 2         | 0.63%   |
| 5.8.0-48-generic         | 2         | 0.63%   |
| 5.8.0-43-generic         | 2         | 0.63%   |
| 5.4.0-91-generic         | 2         | 0.63%   |
| 5.4.0-88-generic         | 2         | 0.63%   |
| 5.4.0-72-generic         | 2         | 0.63%   |
| 5.4.0-40-generic         | 2         | 0.63%   |
| 5.4.0-39-generic         | 2         | 0.63%   |
| 5.4.0-29-generic         | 2         | 0.63%   |
| 5.3.0-40-generic         | 2         | 0.63%   |
| 5.3.0-26-generic         | 2         | 0.63%   |
| 5.17.15-76051715-generic | 2         | 0.63%   |
| 5.15.4-arch1-1           | 2         | 0.63%   |
| 5.15.12-arch1-1          | 2         | 0.63%   |
| 5.15.0-43-generic        | 2         | 0.63%   |
| 5.14.15-300.fc35.x86_64  | 2         | 0.63%   |
| 5.13.0-7614-generic      | 2         | 0.63%   |
| 5.13.0-39-generic        | 2         | 0.63%   |
| 5.13.0-30-generic        | 2         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 56        | 18.3%   |
| 5.13.0  | 20        | 6.54%   |
| 5.11.0  | 17        | 5.56%   |
| 5.3.0   | 16        | 5.23%   |
| 5.8.0   | 15        | 4.9%    |
| 4.15.0  | 14        | 4.58%   |
| 5.15.0  | 13        | 4.25%   |
| 5.0.0   | 12        | 3.92%   |
| 5.16.7  | 10        | 3.27%   |
| 5.10.14 | 9         | 2.94%   |
| 5.10.0  | 9         | 2.94%   |
| 4.19.0  | 7         | 2.29%   |
| 4.18.0  | 6         | 1.96%   |
| 5.3.16  | 4         | 1.31%   |
| 5.17.5  | 4         | 1.31%   |
| 5.15.4  | 3         | 0.98%   |
| 5.8.11  | 2         | 0.65%   |
| 5.7.0   | 2         | 0.65%   |
| 5.6.8   | 2         | 0.65%   |
| 5.6.19  | 2         | 0.65%   |
| 5.3.8   | 2         | 0.65%   |
| 5.18.6  | 2         | 0.65%   |
| 5.18.10 | 2         | 0.65%   |
| 5.17.15 | 2         | 0.65%   |
| 5.16.11 | 2         | 0.65%   |
| 5.15.15 | 2         | 0.65%   |
| 5.15.12 | 2         | 0.65%   |
| 5.14.15 | 2         | 0.65%   |
| 5.11.12 | 2         | 0.65%   |
| 5.9.8   | 1         | 0.33%   |
| 5.9.6   | 1         | 0.33%   |
| 5.9.16  | 1         | 0.33%   |
| 5.9.11  | 1         | 0.33%   |
| 5.8.3   | 1         | 0.33%   |
| 5.8.16  | 1         | 0.33%   |
| 5.8.15  | 1         | 0.33%   |
| 5.8.14  | 1         | 0.33%   |
| 5.8.10  | 1         | 0.33%   |
| 5.8.1   | 1         | 0.33%   |
| 5.7.8   | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 61        | 20.27%  |
| 5.10    | 24        | 7.97%   |
| 5.15    | 23        | 7.64%   |
| 5.13    | 23        | 7.64%   |
| 5.11    | 22        | 7.31%   |
| 5.8     | 21        | 6.98%   |
| 5.3     | 21        | 6.98%   |
| 5.16    | 18        | 5.98%   |
| 4.15    | 14        | 4.65%   |
| 5.0     | 12        | 3.99%   |
| 5.18    | 8         | 2.66%   |
| 5.17    | 8         | 2.66%   |
| 4.19    | 7         | 2.33%   |
| 4.18    | 7         | 2.33%   |
| 5.6     | 6         | 1.99%   |
| 5.14    | 6         | 1.99%   |
| 5.7     | 5         | 1.66%   |
| 5.9     | 4         | 1.33%   |
| 5.5     | 2         | 0.66%   |
| 5.19    | 2         | 0.66%   |
| 4.9     | 2         | 0.66%   |
| 4.20    | 2         | 0.66%   |
| 5.2     | 1         | 0.33%   |
| 4.13    | 1         | 0.33%   |
| 4.11    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 257       | 96.98%  |
| i686   | 8         | 3.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 126       | 45.65%  |
| KDE5             | 35        | 12.68%  |
| Unknown          | 32        | 11.59%  |
| X-Cinnamon       | 21        | 7.61%   |
| XFCE             | 19        | 6.88%   |
| KDE              | 10        | 3.62%   |
| MATE             | 8         | 2.9%    |
| Pantheon         | 5         | 1.81%   |
| Cinnamon         | 4         | 1.45%   |
| Unity            | 3         | 1.09%   |
| LXDE             | 3         | 1.09%   |
| i3               | 3         | 1.09%   |
| LXQt             | 2         | 0.72%   |
| Budgie           | 2         | 0.72%   |
| lightdm-xsession | 1         | 0.36%   |
| KDE4             | 1         | 0.36%   |
| Deepin           | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 212       | 77.09%  |
| Wayland | 45        | 16.36%  |
| Unknown | 16        | 5.82%   |
| Tty     | 2         | 0.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 159       | 56.99%  |
| SDDM    | 33        | 11.83%  |
| GDM     | 33        | 11.83%  |
| LightDM | 19        | 6.81%   |
| GDM3    | 18        | 6.45%   |
| TDM     | 11        | 3.94%   |
| Ly      | 2         | 0.72%   |
| LXDM    | 2         | 0.72%   |
| XDM     | 1         | 0.36%   |
| KDM     | 1         | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_NZ   | 161       | 58.33%  |
| en_US   | 58        | 21.01%  |
| Unknown | 27        | 9.78%   |
| en_GB   | 12        | 4.35%   |
| C       | 10        | 3.62%   |
| en_AU   | 6         | 2.17%   |
| zh_CN   | 1         | 0.36%   |
| de_DE   | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 137       | 50.74%  |
| BIOS | 133       | 49.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 211       | 77.01%  |
| Overlay | 24        | 8.76%   |
| Btrfs   | 19        | 6.93%   |
| Unknown | 14        | 5.11%   |
| Xfs     | 2         | 0.73%   |
| Ext2    | 2         | 0.73%   |
| Zfs     | 1         | 0.36%   |
| Ext3    | 1         | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 164       | 60.52%  |
| GPT     | 75        | 27.68%  |
| MBR     | 32        | 11.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 237       | 87.78%  |
| Yes       | 33        | 12.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 208       | 77.04%  |
| Yes       | 62        | 22.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 79        | 29.81%  |
| Lenovo              | 45        | 16.98%  |
| Dell                | 35        | 13.21%  |
| ASUSTek Computer    | 28        | 10.57%  |
| Acer                | 23        | 8.68%   |
| Toshiba             | 15        | 5.66%   |
| MSI                 | 8         | 3.02%   |
| Apple               | 7         | 2.64%   |
| Sony                | 4         | 1.51%   |
| Samsung Electronics | 4         | 1.51%   |
| Google              | 3         | 1.13%   |
| System76            | 2         | 0.75%   |
| YJKC                | 1         | 0.38%   |
| TWG                 | 1         | 0.38%   |
| Timi                | 1         | 0.38%   |
| The Warehouse Group | 1         | 0.38%   |
| Star Labs           | 1         | 0.38%   |
| Metabox             | 1         | 0.38%   |
| Medion              | 1         | 0.38%   |
| Kogan               | 1         | 0.38%   |
| IBM                 | 1         | 0.38%   |
| HUAWEI              | 1         | 0.38%   |
| eMachines           | 1         | 0.38%   |
| Alienware           | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Dell XPS 13 9360                          | 5         | 1.89%   |
| HP ProBook 6550b                          | 3         | 1.13%   |
| HP ProBook 4540s                          | 3         | 1.13%   |
| HP Pavilion dv6                           | 3         | 1.13%   |
| HP Notebook                               | 3         | 1.13%   |
| HP EliteBook 8560p                        | 3         | 1.13%   |
| MSI GE66 Raider 10SF                      | 2         | 0.75%   |
| Lenovo ThinkPad T460 20FMS2FR00           | 2         | 0.75%   |
| HP ZBook Firefly 15 G7 Mobile Workstation | 2         | 0.75%   |
| HP ProBook 6570b                          | 2         | 0.75%   |
| HP ProBook 450 G5                         | 2         | 0.75%   |
| HP ProBook 450 G3                         | 2         | 0.75%   |
| HP Pavilion 15                            | 2         | 0.75%   |
| Dell XPS 15 9500                          | 2         | 0.75%   |
| Dell Latitude E6430s                      | 2         | 0.75%   |
| Dell Latitude E4300                       | 2         | 0.75%   |
| Dell Latitude 7490                        | 2         | 0.75%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR     | 2         | 0.75%   |
| ASUS ROG Strix G513QY_G513QY              | 2         | 0.75%   |
| ASUS K52Jc                                | 2         | 0.75%   |
| Acer Swift SF314-41                       | 2         | 0.75%   |
| Acer Aspire F5-573G                       | 2         | 0.75%   |
| YJKC vBOOK Plus                           | 1         | 0.38%   |
| TWG E2017                                 | 1         | 0.38%   |
| Toshiba TECRA Z50-A                       | 1         | 0.38%   |
| Toshiba Satellite U920t                   | 1         | 0.38%   |
| Toshiba Satellite S70t-B                  | 1         | 0.38%   |
| Toshiba Satellite Pro R50-C               | 1         | 0.38%   |
| Toshiba Satellite Pro L830                | 1         | 0.38%   |
| Toshiba Satellite Pro C665                | 1         | 0.38%   |
| Toshiba Satellite L750                    | 1         | 0.38%   |
| Toshiba Satellite L50D-C                  | 1         | 0.38%   |
| Toshiba Satellite C660                    | 1         | 0.38%   |
| Toshiba Satellite C50D-C                  | 1         | 0.38%   |
| Toshiba Satellite C50-B                   | 1         | 0.38%   |
| Toshiba PORTEGE R930                      | 1         | 0.38%   |
| Toshiba PORTEGE R700                      | 1         | 0.38%   |
| Toshiba PORTEGE M930                      | 1         | 0.38%   |
| Toshiba PORTEGE M780                      | 1         | 0.38%   |
| Timi A30                                  | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 30        | 11.32%  |
| HP ProBook                | 19        | 7.17%   |
| HP Pavilion               | 16        | 6.04%   |
| HP EliteBook              | 15        | 5.66%   |
| Dell Latitude             | 15        | 5.66%   |
| Acer Aspire               | 15        | 5.66%   |
| Dell XPS                  | 11        | 4.15%   |
| Toshiba Satellite         | 10        | 3.77%   |
| HP Laptop                 | 6         | 2.26%   |
| ASUS ROG                  | 6         | 2.26%   |
| HP ZBook                  | 5         | 1.89%   |
| Toshiba PORTEGE           | 4         | 1.51%   |
| HP Notebook               | 3         | 1.13%   |
| HP Compaq                 | 3         | 1.13%   |
| Dell Precision            | 3         | 1.13%   |
| Dell Inspiron             | 3         | 1.13%   |
| Acer TravelMate           | 3         | 1.13%   |
| MSI GE66                  | 2         | 0.75%   |
| Lenovo Yoga               | 2         | 0.75%   |
| Lenovo IdeaPad            | 2         | 0.75%   |
| HP Presario               | 2         | 0.75%   |
| Dell Vostro               | 2         | 0.75%   |
| ASUS VivoBook             | 2         | 0.75%   |
| ASUS K52Jc                | 2         | 0.75%   |
| ASUS ASUS                 | 2         | 0.75%   |
| Apple MacBookPro5         | 2         | 0.75%   |
| Apple MacBook5            | 2         | 0.75%   |
| Acer Swift                | 2         | 0.75%   |
| YJKC vBOOK                | 1         | 0.38%   |
| TWG E2017                 | 1         | 0.38%   |
| Toshiba TECRA             | 1         | 0.38%   |
| Timi A30                  | 1         | 0.38%   |
| The Warehouse Group E2037 | 1         | 0.38%   |
| System76 Pangolin         | 1         | 0.38%   |
| System76 Lemur            | 1         | 0.38%   |
| Star Labs LabTop          | 1         | 0.38%   |
| Sony VPCEH28FG            | 1         | 0.38%   |
| Sony VPCEB43FG            | 1         | 0.38%   |
| Sony SVE14A15FGS          | 1         | 0.38%   |
| Sony SVE11126CGB          | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 31        | 11.7%   |
| 2012 | 28        | 10.57%  |
| 2018 | 22        | 8.3%    |
| 2020 | 21        | 7.92%   |
| 2019 | 20        | 7.55%   |
| 2021 | 19        | 7.17%   |
| 2017 | 19        | 7.17%   |
| 2016 | 19        | 7.17%   |
| 2014 | 16        | 6.04%   |
| 2013 | 15        | 5.66%   |
| 2015 | 13        | 4.91%   |
| 2010 | 12        | 4.53%   |
| 2008 | 12        | 4.53%   |
| 2009 | 7         | 2.64%   |
| 2022 | 6         | 2.26%   |
| 2007 | 2         | 0.75%   |
| 2006 | 2         | 0.75%   |
| 2005 | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 265       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 236       | 88.39%  |
| Enabled  | 31        | 11.61%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 260       | 98.11%  |
| Yes  | 5         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 75        | 27.57%  |
| 16.01-24.0  | 55        | 20.22%  |
| 3.01-4.0    | 51        | 18.75%  |
| 8.01-16.0   | 45        | 16.54%  |
| 32.01-64.0  | 23        | 8.46%   |
| 1.01-2.0    | 8         | 2.94%   |
| 64.01-256.0 | 5         | 1.84%   |
| 2.01-3.0    | 4         | 1.47%   |
| 24.01-32.0  | 3         | 1.1%    |
| 0.51-1.0    | 3         | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 105       | 35.71%  |
| 2.01-3.0   | 77        | 26.19%  |
| 3.01-4.0   | 45        | 15.31%  |
| 4.01-8.0   | 36        | 12.24%  |
| 0.51-1.0   | 18        | 6.12%   |
| 8.01-16.0  | 8         | 2.72%   |
| 24.01-32.0 | 2         | 0.68%   |
| 16.01-24.0 | 2         | 0.68%   |
| 0.01-0.5   | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 207       | 76.38%  |
| 2      | 54        | 19.93%  |
| 3      | 8         | 2.95%   |
| 0      | 2         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 150       | 56.39%  |
| Yes       | 116       | 43.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 224       | 83.58%  |
| No        | 44        | 16.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 263       | 99.25%  |
| No        | 2         | 0.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 78.52%  |
| No        | 58        | 21.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| New Zealand | 265       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Auckland         | 129       | 47.25%  |
| Wellington       | 31        | 11.36%  |
| Christchurch     | 26        | 9.52%   |
| Hamilton         | 13        | 4.76%   |
| Dunedin          | 8         | 2.93%   |
| Whangarei        | 7         | 2.56%   |
| Cambridge        | 7         | 2.56%   |
| Tauranga         | 6         | 2.2%    |
| New Plymouth     | 6         | 2.2%    |
| Nelson           | 4         | 1.47%   |
| Napier City      | 4         | 1.47%   |
| Lower Hutt       | 4         | 1.47%   |
| Invercargill     | 4         | 1.47%   |
| Palmerston North | 3         | 1.1%    |
| Hastings         | 3         | 1.1%    |
| Whanganui        | 2         | 0.73%   |
| Otaki            | 2         | 0.73%   |
| Grafton          | 2         | 0.73%   |
| Whatawhata       | 1         | 0.37%   |
| Tutukaka         | 1         | 0.37%   |
| Saint Andrews    | 1         | 0.37%   |
| Rotorua          | 1         | 0.37%   |
| Pakuranga        | 1         | 0.37%   |
| Masterton        | 1         | 0.37%   |
| Levin            | 1         | 0.37%   |
| Kerikeri         | 1         | 0.37%   |
| Katikati         | 1         | 0.37%   |
| Gordonton        | 1         | 0.37%   |
| Edgecumbe        | 1         | 0.37%   |
| Ashburton        | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 61        | 79     | 19.3%   |
| Seagate                     | 43        | 46     | 13.61%  |
| WDC                         | 33        | 49     | 10.44%  |
| Toshiba                     | 30        | 38     | 9.49%   |
| Crucial                     | 19        | 33     | 6.01%   |
| SK hynix                    | 17        | 17     | 5.38%   |
| SanDisk                     | 17        | 19     | 5.38%   |
| Intel                       | 13        | 15     | 4.11%   |
| Unknown                     | 12        | 18     | 3.8%    |
| Kingston                    | 9         | 12     | 2.85%   |
| Hitachi                     | 9         | 11     | 2.85%   |
| Micron Technology           | 7         | 11     | 2.22%   |
| HGST                        | 7         | 7      | 2.22%   |
| KingSpec                    | 4         | 4      | 1.27%   |
| China                       | 3         | 3      | 0.95%   |
| ASMT                        | 3         | 3      | 0.95%   |
| A-DATA Technology           | 3         | 3      | 0.95%   |
| Transcend                   | 2         | 2      | 0.63%   |
| TO Exter                    | 2         | 2      | 0.63%   |
| Team                        | 2         | 2      | 0.63%   |
| Micron/Crucial Technology   | 2         | 2      | 0.63%   |
| LITEON                      | 2         | 2      | 0.63%   |
| KIOXIA                      | 2         | 3      | 0.63%   |
| Apple                       | 2         | 2      | 0.63%   |
| XPG                         | 1         | 1      | 0.32%   |
| Star Drive                  | 1         | 1      | 0.32%   |
| Silicon Motion              | 1         | 2      | 0.32%   |
| ROG                         | 1         | 1      | 0.32%   |
| Phison                      | 1         | 1      | 0.32%   |
| Netac                       | 1         | 1      | 0.32%   |
| LITEONIT                    | 1         | 3      | 0.32%   |
| Kingston Technology Company | 1         | 1      | 0.32%   |
| KINGBANK                    | 1         | 1      | 0.32%   |
| JMicron Technology          | 1         | 1      | 0.32%   |
| Hewlett-Packard             | 1         | 3      | 0.32%   |
| Fujitsu                     | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Intel NVMe SSD Drive 512GB         | 7         | 2.13%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 1.83%   |
| Samsung NVMe SSD Drive 512GB       | 6         | 1.83%   |
| Samsung SSD 850 EVO 500GB          | 5         | 1.52%   |
| Toshiba MQ01ABF050 500GB           | 4         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 1.22%   |
| Seagate Expansion 1TB              | 4         | 1.22%   |
| Samsung NVMe SSD Drive 256GB       | 4         | 1.22%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 3         | 0.91%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 3         | 0.91%   |
| Toshiba NVMe SSD Drive 512GB       | 3         | 0.91%   |
| Seagate ST9500420AS 500GB          | 3         | 0.91%   |
| SanDisk NVMe SSD Drive 512GB       | 3         | 0.91%   |
| Samsung SSD 860 EVO 500GB          | 3         | 0.91%   |
| Samsung SSD 850 EVO 1TB            | 3         | 0.91%   |
| Samsung MZVL21T0HCLR-00B00 1TB     | 3         | 0.91%   |
| Kingston SV300S37A240G 240GB SSD   | 3         | 0.91%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 0.91%   |
| Crucial CT240BX200SSD1 240GB       | 3         | 0.91%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 2         | 0.61%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 2         | 0.61%   |
| WDC WD10SPZX-22Z10T1 1TB           | 2         | 0.61%   |
| WDC WD10SPZX-21Z10T0 1TB           | 2         | 0.61%   |
| WDC WD10JPVX-60JC3T0 1TB           | 2         | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.61%   |
| Unknown MMC Card  64GB             | 2         | 0.61%   |
| Unknown MMC Card  2GB              | 2         | 0.61%   |
| Unknown MMC Card  128GB            | 2         | 0.61%   |
| Toshiba NVMe SSD Drive 256GB       | 2         | 0.61%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.61%   |
| Toshiba MK5076GSX 500GB            | 2         | 0.61%   |
| Toshiba MK1652GSX 160GB            | 2         | 0.61%   |
| TO Exter nal USB 3.0 180GB         | 2         | 0.61%   |
| SK hynix NVMe SSD Drive 256GB      | 2         | 0.61%   |
| Seagate ST9500325AS 500GB          | 2         | 0.61%   |
| Seagate ST2000LM007-1R8174 2TB     | 2         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.61%   |
| Seagate ST1000LM014-1EJ164 1TB     | 2         | 0.61%   |
| SanDisk SDSSDA240G 240GB           | 2         | 0.61%   |
| SanDisk NVMe SSD Drive 1024GB      | 2         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 44     | 39.05%  |
| WDC                 | 26        | 33     | 24.76%  |
| Toshiba             | 16        | 21     | 15.24%  |
| Hitachi             | 9         | 11     | 8.57%   |
| HGST                | 7         | 7      | 6.67%   |
| Samsung Electronics | 2         | 2      | 1.9%    |
| Unknown             | 1         | 3      | 0.95%   |
| Fujitsu             | 1         | 1      | 0.95%   |
| ASMT                | 1         | 1      | 0.95%   |
| Apple               | 1         | 1      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 34     | 25.71%  |
| Crucial             | 17        | 31     | 16.19%  |
| SanDisk             | 11        | 11     | 10.48%  |
| Kingston            | 8         | 11     | 7.62%   |
| Micron Technology   | 6         | 9      | 5.71%   |
| KingSpec            | 4         | 4      | 3.81%   |
| WDC                 | 3         | 10     | 2.86%   |
| Toshiba             | 3         | 4      | 2.86%   |
| SK hynix            | 3         | 3      | 2.86%   |
| China               | 3         | 3      | 2.86%   |
| A-DATA Technology   | 3         | 3      | 2.86%   |
| Transcend           | 2         | 2      | 1.9%    |
| TO Exter            | 2         | 2      | 1.9%    |
| Team                | 2         | 2      | 1.9%    |
| Seagate             | 2         | 2      | 1.9%    |
| LITEON              | 2         | 2      | 1.9%    |
| Intel               | 2         | 3      | 1.9%    |
| Netac               | 1         | 1      | 0.95%   |
| LITEONIT            | 1         | 3      | 0.95%   |
| Hewlett-Packard     | 1         | 3      | 0.95%   |
| ASMT                | 1         | 1      | 0.95%   |
| Apple               | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 100       | 124    | 33.22%  |
| SSD     | 99        | 145    | 32.89%  |
| NVMe    | 88        | 112    | 29.24%  |
| MMC     | 12        | 16     | 3.99%   |
| Unknown | 2         | 3      | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 182       | 255    | 61.9%   |
| NVMe | 87        | 111    | 29.59%  |
| SAS  | 13        | 18     | 4.42%   |
| MMC  | 12        | 16     | 4.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 138       | 194    | 69%     |
| 0.51-1.0   | 56        | 68     | 28%     |
| 1.01-2.0   | 6         | 7      | 3%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 77        | 28.21%  |
| 101-250        | 77        | 28.21%  |
| 501-1000       | 39        | 14.29%  |
| 1-20           | 21        | 7.69%   |
| 1001-2000      | 17        | 6.23%   |
| 51-100         | 16        | 5.86%   |
| 21-50          | 8         | 2.93%   |
| Unknown        | 8         | 2.93%   |
| More than 3000 | 6         | 2.2%    |
| 2001-3000      | 4         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 117       | 40.63%  |
| 21-50          | 58        | 20.14%  |
| 101-250        | 37        | 12.85%  |
| 51-100         | 32        | 11.11%  |
| 251-500        | 18        | 6.25%   |
| 501-1000       | 13        | 4.51%   |
| Unknown        | 8         | 2.78%   |
| More than 3000 | 2         | 0.69%   |
| 1001-2000      | 2         | 0.69%   |
| 2001-3000      | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKX-00HPJT0 752GB                        | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 5.56%   |
| Toshiba MK5076GSX 500GB                             | 1         | 1      | 5.56%   |
| Toshiba MK3256GSY 320GB                             | 1         | 1      | 5.56%   |
| SK hynix SC308 SATA 128GB SSD                       | 1         | 1      | 5.56%   |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB             | 1         | 1      | 5.56%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 5.56%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS545032B9SA00 320GB                       | 1         | 1      | 5.56%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 5.56%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 5.56%   |
| Crucial CT275MX300SSD1 275GB                        | 1         | 1      | 5.56%   |
| ASMT ASM105x 499GB                                  | 1         | 1      | 5.56%   |
| Apple HDD HTS547550A9E384 500GB                     | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 3         | 3      | 16.67%  |
| Seagate           | 3         | 3      | 16.67%  |
| SK hynix          | 2         | 2      | 11.11%  |
| Micron Technology | 2         | 2      | 11.11%  |
| Hitachi           | 2         | 2      | 11.11%  |
| HGST              | 2         | 2      | 11.11%  |
| WDC               | 1         | 1      | 5.56%   |
| Crucial           | 1         | 1      | 5.56%   |
| ASMT              | 1         | 1      | 5.56%   |
| Apple             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 25%     |
| Seagate | 3         | 3      | 25%     |
| Hitachi | 2         | 2      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |
| WDC     | 1         | 1      | 8.33%   |
| Apple   | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 66.67%  |
| SSD  | 5         | 5      | 27.78%  |
| NVMe | 1         | 1      | 5.56%   |

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
| Detected | 172       | 267    | 61.43%  |
| Works    | 90        | 115    | 32.14%  |
| Malfunc  | 18        | 18     | 6.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 191       | 62.42%  |
| Samsung Electronics          | 34        | 11.11%  |
| AMD                          | 28        | 9.15%   |
| SK hynix                     | 14        | 4.58%   |
| Toshiba America Info Systems | 12        | 3.92%   |
| SanDisk                      | 9         | 2.94%   |
| Nvidia                       | 5         | 1.63%   |
| Micron/Crucial Technology    | 4         | 1.31%   |
| Phison Electronics           | 2         | 0.65%   |
| KIOXIA                       | 2         | 0.65%   |
| Kingston Technology Company  | 2         | 0.65%   |
| Silicon Motion               | 1         | 0.33%   |
| Micron Technology            | 1         | 0.33%   |
| ADATA Technology             | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 8.98%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 7.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 23        | 7.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 6.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 19        | 5.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 3.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 9         | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 2.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.86%   |
| Intel SSD 660P Series                                                            | 6         | 1.86%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 1.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.86%   |
| SK hynix Non-Volatile memory controller                                          | 5         | 1.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 1.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.55%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 4         | 1.24%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.24%   |
| Intel Non-Volatile memory controller                                             | 4         | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 1.24%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.93%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 3         | 0.93%   |
| SK hynix Gold P31 SSD                                                            | 3         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.93%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.93%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 2         | 0.62%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.62%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 192       | 61.54%  |
| NVMe | 88        | 28.21%  |
| RAID | 19        | 6.09%   |
| IDE  | 13        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 227       | 85.66%  |
| AMD    | 38        | 14.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 2.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 2.26%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 1.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 1.89%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.51%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 1.51%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 1.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.51%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 4         | 1.51%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.51%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 4         | 1.51%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 1.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.13%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.13%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 1.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.13%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.13%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 1.13%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.13%   |
| Intel Pentium M processor 2.00GHz             | 2         | 0.75%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 2         | 0.75%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.75%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.75%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 0.75%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 2         | 0.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.75%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 81        | 30.57%  |
| Intel Core i7                  | 71        | 26.79%  |
| Intel Core 2 Duo               | 17        | 6.42%   |
| Other                          | 16        | 6.04%   |
| Intel Celeron                  | 16        | 6.04%   |
| Intel Core i3                  | 13        | 4.91%   |
| AMD Ryzen 5                    | 7         | 2.64%   |
| AMD A6                         | 6         | 2.26%   |
| AMD E2                         | 5         | 1.89%   |
| AMD Ryzen 9                    | 4         | 1.51%   |
| Intel Core i9                  | 3         | 1.13%   |
| Intel Atom                     | 3         | 1.13%   |
| AMD Ryzen 7                    | 3         | 1.13%   |
| AMD A8                         | 3         | 1.13%   |
| Intel Pentium M                | 2         | 0.75%   |
| Intel Pentium                  | 2         | 0.75%   |
| AMD A4                         | 2         | 0.75%   |
| Intel Pentium Silver           | 1         | 0.38%   |
| Intel Genuine                  | 1         | 0.38%   |
| Intel Core m7                  | 1         | 0.38%   |
| Intel Celeron Dual-Core        | 1         | 0.38%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.38%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.38%   |
| AMD Ryzen 7 PRO                | 1         | 0.38%   |
| AMD Ryzen 3                    | 1         | 0.38%   |
| AMD E1                         | 1         | 0.38%   |
| AMD E                          | 1         | 0.38%   |
| AMD A10                        | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 144       | 54.34%  |
| 4      | 80        | 30.19%  |
| 6      | 17        | 6.42%   |
| 8      | 13        | 4.91%   |
| 1      | 5         | 1.89%   |
| 14     | 4         | 1.51%   |
| 10     | 2         | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 265       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 199       | 75.09%  |
| 1      | 66        | 24.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 256       | 95.17%  |
| Unknown        | 10        | 3.72%   |
| 32-bit         | 3         | 1.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 23.16%  |
| 0x206a7    | 28        | 10.29%  |
| 0x306a9    | 20        | 7.35%   |
| 0x806ea    | 11        | 4.04%   |
| 0x806ec    | 10        | 3.68%   |
| 0x406e3    | 10        | 3.68%   |
| 0x806e9    | 8         | 2.94%   |
| 0x30678    | 7         | 2.57%   |
| 0x20655    | 7         | 2.57%   |
| 0x1067a    | 7         | 2.57%   |
| 0xa0652    | 6         | 2.21%   |
| 0x40651    | 6         | 2.21%   |
| 0x306c3    | 6         | 2.21%   |
| 0x10676    | 6         | 2.21%   |
| 0x906e9    | 5         | 1.84%   |
| 0x306d4    | 5         | 1.84%   |
| 0x07030105 | 5         | 1.84%   |
| 0x906ea    | 4         | 1.47%   |
| 0x806d1    | 3         | 1.1%    |
| 0x806c1    | 3         | 1.1%    |
| 0x6fd      | 3         | 1.1%    |
| 0x506e3    | 3         | 1.1%    |
| 0x506c9    | 3         | 1.1%    |
| 0x08108102 | 3         | 1.1%    |
| 0x06006705 | 3         | 1.1%    |
| 0x906a3    | 2         | 0.74%   |
| 0x706a8    | 2         | 0.74%   |
| 0x6d8      | 2         | 0.74%   |
| 0x106ca    | 2         | 0.74%   |
| 0x0a50000c | 2         | 0.74%   |
| 0x08608103 | 2         | 0.74%   |
| 0x08600106 | 2         | 0.74%   |
| 0x08108109 | 2         | 0.74%   |
| 0x0700010f | 2         | 0.74%   |
| 0x05000119 | 2         | 0.74%   |
| 0xa0660    | 1         | 0.37%   |
| 0x906c0    | 1         | 0.37%   |
| 0x906a4    | 1         | 0.37%   |
| 0x806eb    | 1         | 0.37%   |
| 0x806c2    | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 19.25%  |
| SandyBridge      | 32        | 12.08%  |
| IvyBridge        | 25        | 9.43%   |
| Skylake          | 18        | 6.79%   |
| Penryn           | 15        | 5.66%   |
| Haswell          | 14        | 5.28%   |
| Westmere         | 10        | 3.77%   |
| CometLake        | 10        | 3.77%   |
| Silvermont       | 9         | 3.4%    |
| Puma             | 9         | 3.4%    |
| Broadwell        | 7         | 2.64%   |
| Zen+             | 6         | 2.26%   |
| TigerLake        | 6         | 2.26%   |
| IceLake          | 6         | 2.26%   |
| Excavator        | 6         | 2.26%   |
| Unknown          | 6         | 2.26%   |
| Zen 3            | 4         | 1.51%   |
| Goldmont         | 4         | 1.51%   |
| Core             | 4         | 1.51%   |
| Goldmont plus    | 3         | 1.13%   |
| Bonnell          | 3         | 1.13%   |
| Alderlake Hybrid | 3         | 1.13%   |
| Zen 2            | 2         | 0.75%   |
| P6               | 2         | 0.75%   |
| Nehalem          | 2         | 0.75%   |
| Jaguar           | 2         | 0.75%   |
| Bobcat           | 2         | 0.75%   |
| Tremont          | 1         | 0.38%   |
| Piledriver       | 1         | 0.38%   |
| K8 Hammer        | 1         | 0.38%   |
| K8 & K10 hybrid  | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 201       | 60%     |
| Nvidia | 68        | 20.3%   |
| AMD    | 66        | 19.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 27        | 7.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 22        | 6.27%   |
| Intel UHD Graphics 620                                                                | 12        | 3.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 12        | 3.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 9         | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 8         | 2.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 8         | 2.28%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 2.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 7         | 1.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 1.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 1.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 1.71%   |
| Intel HD Graphics 630                                                                 | 6         | 1.71%   |
| Intel HD Graphics 620                                                                 | 6         | 1.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 1.71%   |
| Intel HD Graphics 5500                                                                | 5         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 5         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 5         | 1.42%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 5         | 1.42%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 5         | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.14%   |
| Intel HD Graphics 530                                                                 | 4         | 1.14%   |
| Intel HD Graphics 500                                                                 | 4         | 1.14%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 4         | 1.14%   |
| AMD Cezanne                                                                           | 4         | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 0.85%   |
| Nvidia GK107M [GeForce GT 650M]                                                       | 3         | 0.85%   |
| Nvidia C79 [GeForce 9400M]                                                            | 3         | 0.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 0.85%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 3         | 0.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 3         | 0.85%   |
| AMD Mullins [Radeon R2 Graphics]                                                      | 3         | 0.85%   |
| AMD Lucienne                                                                          | 3         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 2         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 135       | 50.94%  |
| Intel + Nvidia | 48        | 18.11%  |
| 1 x AMD        | 34        | 12.83%  |
| Intel + AMD    | 17        | 6.42%   |
| 1 x Nvidia     | 14        | 5.28%   |
| 2 x AMD        | 10        | 3.77%   |
| AMD + Nvidia   | 5         | 1.89%   |
| Other          | 1         | 0.38%   |
| 2 x Nvidia     | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 223       | 83.83%  |
| Proprietary | 35        | 13.16%  |
| Unknown     | 8         | 3.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 173       | 63.84%  |
| 0.01-0.5   | 28        | 10.33%  |
| 1.01-2.0   | 24        | 8.86%   |
| 0.51-1.0   | 20        | 7.38%   |
| 3.01-4.0   | 13        | 4.8%    |
| 7.01-8.0   | 5         | 1.85%   |
| 5.01-6.0   | 5         | 1.85%   |
| 2.01-3.0   | 2         | 0.74%   |
| 8.01-16.0  | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 16.89%  |
| LG Display              | 49        | 16.23%  |
| Chimei Innolux          | 38        | 12.58%  |
| Samsung Electronics     | 36        | 11.92%  |
| BOE                     | 27        | 8.94%   |
| Sharp                   | 14        | 4.64%   |
| Dell                    | 13        | 4.3%    |
| Chi Mei Optoelectronics | 12        | 3.97%   |
| Goldstar                | 9         | 2.98%   |
| AOC                     | 9         | 2.98%   |
| Apple                   | 6         | 1.99%   |
| PANDA                   | 4         | 1.32%   |
| InfoVision              | 3         | 0.99%   |
| Hewlett-Packard         | 3         | 0.99%   |
| ViewSonic               | 2         | 0.66%   |
| Quanta Display          | 2         | 0.66%   |
| Philips                 | 2         | 0.66%   |
| Lenovo                  | 2         | 0.66%   |
| InnoLux Display         | 2         | 0.66%   |
| HannStar                | 2         | 0.66%   |
| Denver                  | 2         | 0.66%   |
| Acer                    | 2         | 0.66%   |
| Wacom                   | 1         | 0.33%   |
| TMX                     | 1         | 0.33%   |
| Sony                    | 1         | 0.33%   |
| SANYO                   | 1         | 0.33%   |
| PRISM+                  | 1         | 0.33%   |
| MiTAC                   | 1         | 0.33%   |
| Mi                      | 1         | 0.33%   |
| LG Philips              | 1         | 0.33%   |
| IBM                     | 1         | 0.33%   |
| HYD                     | 1         | 0.33%   |
| CPT                     | 1         | 0.33%   |
| Ancor Communications    | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 1.3%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 1.3%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 0.97%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.97%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.65%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 2         | 0.65%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 2         | 0.65%   |
| Dell U3818DW DELA0F3 3840x1600 880x367mm 37.5-inch                       | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.65%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO41ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch            | 2         | 0.65%   |
| AOC G2790G4 AOC2790 1920x1080 598x336mm 27.0-inch                        | 2         | 0.65%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 2         | 0.65%   |
| Wacom Cintiq 16 WAC1071 1920x1080 344x193mm 15.5-inch                    | 1         | 0.32%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch            | 1         | 0.32%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch             | 1         | 0.32%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.32%   |
| Sony TV SNYA401 1920x1080                                                | 1         | 0.32%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch                  | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 106       | 37.19%  |
| 1366x768 (WXGA)    | 89        | 31.23%  |
| 1600x900 (HD+)     | 18        | 6.32%   |
| 1280x800 (WXGA)    | 14        | 4.91%   |
| 2560x1440 (QHD)    | 11        | 3.86%   |
| 3840x2160 (4K)     | 10        | 3.51%   |
| 3440x1440          | 7         | 2.46%   |
| 1440x900 (WXGA+)   | 5         | 1.75%   |
| 3200x1800 (QHD+)   | 4         | 1.4%    |
| 1280x1024 (SXGA)   | 3         | 1.05%   |
| 1024x600           | 3         | 1.05%   |
| 3840x1600          | 2         | 0.7%    |
| 3456x2160          | 2         | 0.7%    |
| 2880x1800          | 2         | 0.7%    |
| 2560x1600          | 2         | 0.7%    |
| 1920x1200 (WUXGA)  | 2         | 0.7%    |
| 1680x1050 (WSXGA+) | 2         | 0.7%    |
| 3840x2400          | 1         | 0.35%   |
| 2880x1920          | 1         | 0.35%   |
| 1920x1280          | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 128       | 42.24%  |
| 13      | 41        | 13.53%  |
| 14      | 36        | 11.88%  |
| 17      | 24        | 7.92%   |
| 27      | 15        | 4.95%   |
| 23      | 8         | 2.64%   |
| 34      | 5         | 1.65%   |
| 21      | 5         | 1.65%   |
| 12      | 5         | 1.65%   |
| 11      | 5         | 1.65%   |
| 10      | 5         | 1.65%   |
| 37      | 3         | 0.99%   |
| 24      | 3         | 0.99%   |
| 18      | 3         | 0.99%   |
| 16      | 3         | 0.99%   |
| 72      | 2         | 0.66%   |
| 22      | 2         | 0.66%   |
| 19      | 2         | 0.66%   |
| Unknown | 2         | 0.66%   |
| 84      | 1         | 0.33%   |
| 35      | 1         | 0.33%   |
| 33      | 1         | 0.33%   |
| 31      | 1         | 0.33%   |
| 25      | 1         | 0.33%   |
| 20      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 187       | 62.54%  |
| 201-300     | 32        | 10.7%   |
| 351-400     | 28        | 9.36%   |
| 501-600     | 24        | 8.03%   |
| 401-500     | 11        | 3.68%   |
| 701-800     | 6         | 2.01%   |
| 801-900     | 4         | 1.34%   |
| 1501-2000   | 3         | 1%      |
| 601-700     | 2         | 0.67%   |
| Unknown     | 2         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 221       | 83.08%  |
| 16/10   | 28        | 10.53%  |
| 21/9    | 9         | 3.38%   |
| 5/4     | 3         | 1.13%   |
| 3/2     | 3         | 1.13%   |
| Unknown | 2         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 126       | 41.58%  |
| 81-90          | 63        | 20.79%  |
| 121-130        | 21        | 6.93%   |
| 301-350        | 15        | 4.95%   |
| 201-250        | 15        | 4.95%   |
| 71-80          | 14        | 4.62%   |
| 351-500        | 8         | 2.64%   |
| 61-70          | 5         | 1.65%   |
| 51-60          | 5         | 1.65%   |
| 41-50          | 5         | 1.65%   |
| 151-200        | 5         | 1.65%   |
| 141-150        | 4         | 1.32%   |
| 111-120        | 4         | 1.32%   |
| More than 1000 | 3         | 0.99%   |
| 501-1000       | 3         | 0.99%   |
| 251-300        | 2         | 0.66%   |
| 131-140        | 2         | 0.66%   |
| Unknown        | 2         | 0.66%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 113       | 37.92%  |
| 121-160       | 105       | 35.23%  |
| 51-100        | 46        | 15.44%  |
| 161-240       | 16        | 5.37%   |
| More than 240 | 14        | 4.7%    |
| 1-50          | 2         | 0.67%   |
| Unknown       | 2         | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 215       | 78.47%  |
| 2     | 44        | 16.06%  |
| 0     | 9         | 3.28%   |
| 3     | 5         | 1.82%   |
| 4     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 155       | 36.73%  |
| Realtek Semiconductor             | 130       | 30.81%  |
| Qualcomm Atheros                  | 57        | 13.51%  |
| Broadcom                          | 27        | 6.4%    |
| Ralink                            | 7         | 1.66%   |
| Hewlett-Packard                   | 6         | 1.42%   |
| Nvidia                            | 5         | 1.18%   |
| MediaTek                          | 5         | 1.18%   |
| Broadcom Limited                  | 5         | 1.18%   |
| TP-Link                           | 4         | 0.95%   |
| Lenovo                            | 3         | 0.71%   |
| DisplayLink                       | 3         | 0.71%   |
| Sierra Wireless                   | 2         | 0.47%   |
| JMicron Technology                | 2         | 0.47%   |
| Dell                              | 2         | 0.47%   |
| Samsung Electronics               | 1         | 0.24%   |
| OPPO Electronics                  | 1         | 0.24%   |
| NetGear                           | 1         | 0.24%   |
| Marvell Technology Group          | 1         | 0.24%   |
| Lite-On Technology                | 1         | 0.24%   |
| ICS Advent                        | 1         | 0.24%   |
| Ericsson Business Mobile Networks | 1         | 0.24%   |
| Attansic Technology               | 1         | 0.24%   |
| ASIX Electronics                  | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80        | 15.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 4.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 2.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 15        | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.88%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.5%    |
| Intel Wireless 8265 / 8275                                        | 12        | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.92%   |
| Intel Wireless 8260                                               | 10        | 1.92%   |
| Intel Wireless 7260                                               | 10        | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 1.73%   |
| Intel Wireless 3165                                               | 8         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 1.54%   |
| Intel Wireless 7265                                               | 7         | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.15%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.96%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.96%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.96%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.96%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.77%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.77%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.77%   |
| Intel 82577LC Gigabit Network Connection                          | 4         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.58%   |
| Intel Wireless-AC 9260                                            | 3         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 149       | 53.21%  |
| Qualcomm Atheros      | 50        | 17.86%  |
| Realtek Semiconductor | 28        | 10%     |
| Broadcom              | 23        | 8.21%   |
| Ralink                | 7         | 2.5%    |
| MediaTek              | 5         | 1.79%   |
| Broadcom Limited      | 5         | 1.79%   |
| TP-Link               | 4         | 1.43%   |
| Hewlett-Packard       | 3         | 1.07%   |
| Sierra Wireless       | 2         | 0.71%   |
| Dell                  | 2         | 0.71%   |
| NetGear               | 1         | 0.36%   |
| Lite-On Technology    | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15        | 5.34%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 4.63%   |
| Intel Wireless 8265 / 8275                                     | 12        | 4.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 3.56%   |
| Intel Wireless 8260                                            | 10        | 3.56%   |
| Intel Wireless 7260                                            | 10        | 3.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 3.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 3.2%    |
| Intel Wireless 3165                                            | 8         | 2.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 2.85%   |
| Intel Wireless 7265                                            | 7         | 2.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 2.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 2.14%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 2.14%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 1.78%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.78%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.78%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 5         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.42%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.07%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.07%   |
| Intel Wireless-AC 9260                                         | 3         | 1.07%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.07%   |
| HP lt4112 Gobi 4G Module Network Device                        | 3         | 1.07%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.07%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2         | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.71%   |
| Realtek 802.11ac NIC                                           | 2         | 0.71%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.71%   |
| MediaTek WLAN controller                                       | 2         | 0.71%   |
| Intel Wireless 3160                                            | 2         | 0.71%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 121       | 51.93%  |
| Intel                    | 70        | 30.04%  |
| Qualcomm Atheros         | 16        | 6.87%   |
| Broadcom                 | 7         | 3%      |
| Nvidia                   | 5         | 2.15%   |
| Lenovo                   | 3         | 1.29%   |
| DisplayLink              | 3         | 1.29%   |
| JMicron Technology       | 2         | 0.86%   |
| Samsung Electronics      | 1         | 0.43%   |
| OPPO Electronics         | 1         | 0.43%   |
| Marvell Technology Group | 1         | 0.43%   |
| ICS Advent               | 1         | 0.43%   |
| Attansic Technology      | 1         | 0.43%   |
| ASIX Electronics         | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80        | 34.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 8.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 6.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 6.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 2.14%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.14%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.14%   |
| Nvidia MCP79 Ethernet                                             | 4         | 1.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.71%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.71%   |
| Intel 82577LC Gigabit Network Connection                          | 4         | 1.71%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.71%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.28%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.85%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.85%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.85%   |
| Intel Ethernet controller                                         | 2         | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.85%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.85%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.43%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.43%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.43%   |
| OPPO RMX2117                                                      | 1         | 0.43%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 262       | 53.36%  |
| Ethernet | 224       | 45.62%  |
| Modem    | 5         | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 228       | 78.62%  |
| Ethernet | 62        | 21.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 203       | 76.6%   |
| 1     | 58        | 21.89%  |
| 3     | 2         | 0.75%   |
| 0     | 2         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 235       | 88.01%  |
| Yes  | 32        | 11.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 52.11%  |
| Qualcomm Atheros Communications | 19        | 8.92%   |
| Realtek Semiconductor           | 12        | 5.63%   |
| Foxconn / Hon Hai               | 11        | 5.16%   |
| Lite-On Technology              | 10        | 4.69%   |
| IMC Networks                    | 10        | 4.69%   |
| Hewlett-Packard                 | 10        | 4.69%   |
| Broadcom                        | 10        | 4.69%   |
| Apple                           | 6         | 2.82%   |
| Toshiba                         | 4         | 1.88%   |
| Ralink Technology               | 3         | 1.41%   |
| Dell                            | 2         | 0.94%   |
| ASUSTek Computer                | 2         | 0.94%   |
| Realtek                         | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |
| Edimax Technology               | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 47        | 22.07%  |
| Intel AX201 Bluetooth                            | 18        | 8.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 13        | 6.1%    |
| Intel AX200 Bluetooth                            | 13        | 6.1%    |
| Intel Centrino Bluetooth Wireless Transceiver    | 11        | 5.16%   |
| Realtek Bluetooth Radio                          | 7         | 3.29%   |
| Qualcomm Atheros  Bluetooth Device               | 7         | 3.29%   |
| HP Broadcom 2070 Bluetooth Combo                 | 6         | 2.82%   |
| Realtek  Bluetooth 4.2 Adapter                   | 5         | 2.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 5         | 2.35%   |
| IMC Networks Wireless_Device                     | 5         | 2.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 4         | 1.88%   |
| Lite-On Bluetooth Device                         | 4         | 1.88%   |
| Foxconn / Hon Hai Bluetooth Device               | 4         | 1.88%   |
| Apple Bluetooth Host Controller                  | 4         | 1.88%   |
| Lite-On Atheros AR3012 Bluetooth                 | 3         | 1.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 3         | 1.41%   |
| IMC Networks Bluetooth Radio                     | 3         | 1.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 3         | 1.41%   |
| Foxconn / Hon Hai Acer Module                    | 3         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1)                      | 3         | 1.41%   |
| Toshiba Bluetooth Radio                          | 2         | 0.94%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter     | 2         | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                | 2         | 0.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 2         | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                 | 2         | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 2         | 0.94%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 2         | 0.94%   |
| Broadcom HP Portable SoftSailing                 | 2         | 0.94%   |
| Toshiba BRCM Bluetooth Controller BCM2070        | 1         | 0.47%   |
| Toshiba Bluetooth USB Host Controller            | 1         | 0.47%   |
| Realtek Bluetooth Radio                          | 1         | 0.47%   |
| Ralink CSR BS8510                                | 1         | 0.47%   |
| Ralink RT3290 Bluetooth                          | 1         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 0.47%   |
| Lite-On Atheros Bluetooth                        | 1         | 0.47%   |
| Intel Bluetooth Device                           | 1         | 0.47%   |
| Intel AX210 Bluetooth                            | 1         | 0.47%   |
| IMC Networks Bluetooth Device                    | 1         | 0.47%   |
| IMC Networks BCM20702A0                          | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 222       | 65.49%  |
| AMD                       | 50        | 14.75%  |
| Nvidia                    | 43        | 12.68%  |
| Realtek Semiconductor     | 4         | 1.18%   |
| Hewlett-Packard           | 4         | 1.18%   |
| Logitech                  | 3         | 0.88%   |
| Lenovo                    | 3         | 0.88%   |
| Texas Instruments         | 1         | 0.29%   |
| SteelSeries ApS           | 1         | 0.29%   |
| Sennheiser Communications | 1         | 0.29%   |
| Plantronics               | 1         | 0.29%   |
| Micro Star International  | 1         | 0.29%   |
| GYROCOM C&C               | 1         | 0.29%   |
| Google                    | 1         | 0.29%   |
| CMX Systems               | 1         | 0.29%   |
| ClearOne Communications   | 1         | 0.29%   |
| Belkin Components         | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 33        | 8.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 31        | 7.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26        | 6.58%   |
| AMD Family 17h/19h HD Audio Controller                                     | 16        | 4.05%   |
| AMD FCH Azalia Controller                                                  | 13        | 3.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 3.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 12        | 3.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 2.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 2.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 2.03%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 8         | 2.03%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 2.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.77%   |
| Intel CM238 HD Audio Controller                                            | 7         | 1.77%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.52%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 1.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.27%   |
| AMD High Definition Audio Controller                                       | 5         | 1.27%   |
| Realtek Semiconductor USB Audio                                            | 4         | 1.01%   |
| Nvidia MCP79 High Definition Audio                                         | 4         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 1.01%   |
| Hewlett-Packard USB Audio                                                  | 4         | 1.01%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 27.54%  |
| SK hynix            | 42        | 25.15%  |
| Micron Technology   | 26        | 15.57%  |
| Crucial             | 15        | 8.98%   |
| Kingston            | 11        | 6.59%   |
| Unknown             | 5         | 2.99%   |
| Elpida              | 4         | 2.4%    |
| A-DATA Technology   | 4         | 2.4%    |
| Team                | 2         | 1.2%    |
| Shenzhen Mic        | 2         | 1.2%    |
| Ramaxel Technology  | 2         | 1.2%    |
| Unknown (ABCD)      | 1         | 0.6%    |
| Transcend           | 1         | 0.6%    |
| Strontium           | 1         | 0.6%    |
| Neo Forza           | 1         | 0.6%    |
| Nanya Technology    | 1         | 0.6%    |
| fef5                | 1         | 0.6%    |
| Corsair             | 1         | 0.6%    |
| Apacer              | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 2.86%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 2.29%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 2.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.71%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.71%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s          | 3         | 1.71%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 1.14%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 2         | 1.14%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 2         | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1.14%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 1.14%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s      | 2         | 1.14%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 2         | 1.14%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.14%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.14%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.14%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.14%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.14%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 1.14%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Unknown RAM Module 8192MB SODIMM DDR3                            | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.57%   |
| Transcend RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.57%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.57%   |
| Team RAM TEAMGROUP-SD4-2400 16GB Chip DDR4 2133MT/s              | 1         | 0.57%   |
| Team RAM TEAMGROUP-SD4-2400 16384MB SODIMM DDR4 8400MT/s         | 1         | 0.57%   |
| Strontium RAM SRT4G86S1-H9H 4GB SODIMM DDR3 1333MT/s             | 1         | 0.57%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.57%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.57%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.57%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 56        | 43.08%  |
| DDR3    | 49        | 37.69%  |
| DDR2    | 8         | 6.15%   |
| LPDDR3  | 6         | 4.62%   |
| LPDDR4  | 4         | 3.08%   |
| SDRAM   | 3         | 2.31%   |
| Unknown | 2         | 1.54%   |
| LPDDR5  | 1         | 0.77%   |
| DDR5    | 1         | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 90.84%  |
| Row Of Chips | 8         | 6.11%   |
| Chip         | 2         | 1.53%   |
| Unknown      | 2         | 1.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 50        | 36.76%  |
| 4096  | 43        | 31.62%  |
| 16384 | 21        | 15.44%  |
| 2048  | 16        | 11.76%  |
| 32768 | 5         | 3.68%   |
| 1024  | 1         | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 33        | 23.4%   |
| 3200    | 23        | 16.31%  |
| 2667    | 22        | 15.6%   |
| 1334    | 12        | 8.51%   |
| 2400    | 10        | 7.09%   |
| 2133    | 7         | 4.96%   |
| 667     | 5         | 3.55%   |
| 1867    | 4         | 2.84%   |
| 1333    | 4         | 2.84%   |
| 1067    | 4         | 2.84%   |
| Unknown | 4         | 2.84%   |
| 8400    | 2         | 1.42%   |
| 4800    | 2         | 1.42%   |
| 975     | 2         | 1.42%   |
| 800     | 2         | 1.42%   |
| 6400    | 1         | 0.71%   |
| 4267    | 1         | 0.71%   |
| 4199    | 1         | 0.71%   |
| 3733    | 1         | 0.71%   |
| 2048    | 1         | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 50%     |
| HP DeskJet 2300 series        | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 69        | 28.75%  |
| IMC Networks                           | 21        | 8.75%   |
| Sunplus Innovation Technology          | 20        | 8.33%   |
| Microdia                               | 18        | 7.5%    |
| Realtek Semiconductor                  | 17        | 7.08%   |
| Acer                                   | 17        | 7.08%   |
| Quanta                                 | 12        | 5%      |
| Lite-On Technology                     | 10        | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.17%   |
| Suyin                                  | 9         | 3.75%   |
| Apple                                  | 6         | 2.5%    |
| Logitech                               | 5         | 2.08%   |
| Syntek                                 | 4         | 1.67%   |
| Primax Electronics                     | 4         | 1.67%   |
| Alcor Micro                            | 4         | 1.67%   |
| Silicon Motion                         | 3         | 1.25%   |
| Importek                               | 2         | 0.83%   |
| Z-Star Microelectronics                | 1         | 0.42%   |
| Sonix Technology                       | 1         | 0.42%   |
| Samsung Electronics                    | 1         | 0.42%   |
| Ricoh                                  | 1         | 0.42%   |
| Luxvisions Innotech Limited            | 1         | 0.42%   |
| Intel                                  | 1         | 0.42%   |
| DigiTech                               | 1         | 0.42%   |
| AVer Information                       | 1         | 0.42%   |
| ALi                                    | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                       | 15        | 6.25%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 9         | 3.75%   |
| Chicony HD WebCam                                               | 8         | 3.33%   |
| Sunplus Integrated_Webcam_HD                                    | 6         | 2.5%    |
| Sunplus HP HD Webcam [Fixed]                                    | 6         | 2.5%    |
| Realtek Integrated_Webcam_HD                                    | 6         | 2.5%    |
| Chicony HP HD Camera                                            | 6         | 2.5%    |
| Microdia Integrated Webcam HD                                   | 5         | 2.08%   |
| IMC Networks Integrated Camera                                  | 5         | 2.08%   |
| Chicony HP HD Webcam                                            | 5         | 2.08%   |
| Acer Integrated Camera                                          | 5         | 2.08%   |
| Quanta HP TrueVision HD Camera                                  | 4         | 1.67%   |
| Chicony TOSHIBA Web Camera - HD                                 | 4         | 1.67%   |
| Apple Built-in iSight                                           | 4         | 1.67%   |
| Realtek HP Truevision HD                                        | 3         | 1.25%   |
| Microdia Integrated_Webcam_HD                                   | 3         | 1.25%   |
| Lite-On Integrated Camera                                       | 3         | 1.25%   |
| Lite-On HP HD Camera                                            | 3         | 1.25%   |
| Chicony VGA Webcam                                              | 3         | 1.25%   |
| Chicony Integrated HP HD Webcam                                 | 3         | 1.25%   |
| Acer SunplusIT Integrated Camera                                | 3         | 1.25%   |
| Syntek EasyCamera                                               | 2         | 0.83%   |
| Suyin HP Webcam                                                 | 2         | 0.83%   |
| Suyin 1.3M HD WebCam                                            | 2         | 0.83%   |
| Realtek Integrated Webcam_HD                                    | 2         | 0.83%   |
| Quanta HP HD Camera                                             | 2         | 0.83%   |
| Primax Villem                                                   | 2         | 0.83%   |
| Primax HP HD Webcam [Fixed]                                     | 2         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_1.3M                          | 2         | 0.83%   |
| Chicony USB2.0 Camera                                           | 2         | 0.83%   |
| Chicony USB2.0 0.3M UVC WebCam                                  | 2         | 0.83%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 2         | 0.83%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 0.83%   |
| Chicony HP Truevision HD camera                                 | 2         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD         | 2         | 0.83%   |
| Alcor Micro SHUNCCM2MP                                          | 2         | 0.83%   |
| Alcor Micro Asus Integrated Webcam                              | 2         | 0.83%   |
| Acer Lenovo EasyCamera                                          | 2         | 0.83%   |
| Acer HD Webcam                                                  | 2         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 40        | 54.79%  |
| Synaptics                  | 15        | 20.55%  |
| Shenzhen Goodix Technology | 5         | 6.85%   |
| AuthenTec                  | 5         | 6.85%   |
| Elan Microelectronics      | 3         | 4.11%   |
| Upek                       | 2         | 2.74%   |
| LighTuning Technology      | 2         | 2.74%   |
| STMicroelectronics         | 1         | 1.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 13.7%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 8.22%   |
| Validity Sensors VFS491                                                    | 5         | 6.85%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 5.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 5.48%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 4.11%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 4.11%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.11%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.74%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.74%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.74%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 2.74%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.74%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.74%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.37%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.37%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.37%   |
| AuthenTec AES2810                                                          | 1         | 1.37%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.37%   |
| AuthenTec AES1600                                                          | 1         | 1.37%   |
| Unknown                                                                    | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 62.5%   |
| Alcor Micro | 3         | 18.75%  |
| Lenovo      | 2         | 12.5%   |
| O2 Micro    | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 6         | 37.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 3         | 18.75%  |
| Lenovo Integrated Smart Card Reader            | 2         | 12.5%   |
| Broadcom 5880                                  | 2         | 12.5%   |
| Broadcom 58200                                 | 2         | 12.5%   |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 157       | 57.51%  |
| 1     | 92        | 33.7%   |
| 2     | 19        | 6.96%   |
| 6     | 2         | 0.73%   |
| 3     | 2         | 0.73%   |
| 5     | 1         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 71        | 48.63%  |
| Net/wireless             | 18        | 12.33%  |
| Graphics card            | 17        | 11.64%  |
| Chipcard                 | 14        | 9.59%   |
| Multimedia controller    | 7         | 4.79%   |
| Net/ethernet             | 4         | 2.74%   |
| Communication controller | 3         | 2.05%   |
| Camera                   | 3         | 2.05%   |
| Sound                    | 2         | 1.37%   |
| Card reader              | 2         | 1.37%   |
| Bluetooth                | 2         | 1.37%   |
| Storage                  | 1         | 0.68%   |
| Modem                    | 1         | 0.68%   |
| Flash memory             | 1         | 0.68%   |

