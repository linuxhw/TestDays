Linux in Iran - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Iran.

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

Total: 518

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G50-80 80E5                 | [ec5bb450ff](https://linux-hardware.org/?probe=ec5bb450ff) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASUSTek       | E202SA                      | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| ASUSTek       | N61Jv                       | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [fa12e95e32](https://linux-hardware.org/?probe=fa12e95e32) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a36a32eb0e](https://linux-hardware.org/?probe=a36a32eb0e) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [759c9dee6b](https://linux-hardware.org/?probe=759c9dee6b) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [114ada270e](https://linux-hardware.org/?probe=114ada270e) | Aug 08, 2022 |
| ASUSTek       | 1015CX                      | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Timi          | RedmiBook 14                | [10c33f11cf](https://linux-hardware.org/?probe=10c33f11cf) | Aug 02, 2022 |
| Dell          | Latitude E7470              | [0851479f6b](https://linux-hardware.org/?probe=0851479f6b) | Aug 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [9996781aa7](https://linux-hardware.org/?probe=9996781aa7) | Jul 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb442470d4](https://linux-hardware.org/?probe=fb442470d4) | Jul 24, 2022 |
| ASUSTek       | X555LD                      | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | G62                         | [bcb07d1cc9](https://linux-hardware.org/?probe=bcb07d1cc9) | Jul 16, 2022 |
| HP            | G62                         | [020a13b927](https://linux-hardware.org/?probe=020a13b927) | Jul 16, 2022 |
| Acer          | Nitro AN515-55              | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| ASUSTek       | N43JQ                       | [d73f714472](https://linux-hardware.org/?probe=d73f714472) | Jul 01, 2022 |
| ASUSTek       | X542UN                      | [56e348118b](https://linux-hardware.org/?probe=56e348118b) | Jun 26, 2022 |
| ASUSTek       | X542UN                      | [e1d53a776f](https://linux-hardware.org/?probe=e1d53a776f) | Jun 22, 2022 |
| HP            | EliteBook 8440p             | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| ASUSTek       | X542UN                      | [83a04b4dc4](https://linux-hardware.org/?probe=83a04b4dc4) | Jun 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2893254eb3](https://linux-hardware.org/?probe=2893254eb3) | Jun 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e64a2a0eeb](https://linux-hardware.org/?probe=e64a2a0eeb) | Jun 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b0e13d9a94](https://linux-hardware.org/?probe=b0e13d9a94) | Jun 05, 2022 |
| ASUSTek       | X550JX                      | [05094a5491](https://linux-hardware.org/?probe=05094a5491) | Jun 05, 2022 |
| Lenovo        | ThinkPad E420 1141E9G       | [48b5588cbd](https://linux-hardware.org/?probe=48b5588cbd) | Jun 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [27dffb7089](https://linux-hardware.org/?probe=27dffb7089) | May 29, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8a4d6e798d](https://linux-hardware.org/?probe=8a4d6e798d) | May 26, 2022 |
| Toshiba       | Satellite Pro T130          | [2771a53784](https://linux-hardware.org/?probe=2771a53784) | May 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [232b74e86b](https://linux-hardware.org/?probe=232b74e86b) | May 17, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [1bce5b14e3](https://linux-hardware.org/?probe=1bce5b14e3) | May 17, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [247fc8ed78](https://linux-hardware.org/?probe=247fc8ed78) | May 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8a9646dc78](https://linux-hardware.org/?probe=8a9646dc78) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [b6cb96e1d0](https://linux-hardware.org/?probe=b6cb96e1d0) | May 13, 2022 |
| ASUSTek       | X580VD                      | [1d71c877c7](https://linux-hardware.org/?probe=1d71c877c7) | May 13, 2022 |
| Lenovo        | ThinkPad X230 23253QU       | [fde2b81a1c](https://linux-hardware.org/?probe=fde2b81a1c) | May 11, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [b53c2836e9](https://linux-hardware.org/?probe=b53c2836e9) | Apr 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [cb2bc8f53e](https://linux-hardware.org/?probe=cb2bc8f53e) | Apr 21, 2022 |
| Lenovo        | ThinkPad SL 2743X12         | [ad56efc5ff](https://linux-hardware.org/?probe=ad56efc5ff) | Apr 19, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [020929c7b4](https://linux-hardware.org/?probe=020929c7b4) | Apr 17, 2022 |
| HP            | ProBook 450 G4              | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Acer          | Aspire VX5-591G             | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | X550CC                      | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| MSI           | Katana GF66 11UE            | [36c4b80dbb](https://linux-hardware.org/?probe=36c4b80dbb) | Apr 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000RAD     | [6f4db41ef5](https://linux-hardware.org/?probe=6f4db41ef5) | Apr 06, 2022 |
| Acer          | Aspire xxxx                 | [c389f4acb2](https://linux-hardware.org/?probe=c389f4acb2) | Apr 06, 2022 |
| Dell          | Latitude E7240              | [242cae44a5](https://linux-hardware.org/?probe=242cae44a5) | Apr 04, 2022 |
| HP            | Pavilion Notebook           | [c0dd92f23c](https://linux-hardware.org/?probe=c0dd92f23c) | Apr 03, 2022 |
| Packard Be... | EasyNote TK85               | [bfc20224d0](https://linux-hardware.org/?probe=bfc20224d0) | Mar 28, 2022 |
| Apple         | MacBookPro7,1               | [6e0eef7b54](https://linux-hardware.org/?probe=6e0eef7b54) | Mar 25, 2022 |
| ASUSTek       | N550JK                      | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [08a511ac81](https://linux-hardware.org/?probe=08a511ac81) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [61b36dcd42](https://linux-hardware.org/?probe=61b36dcd42) | Mar 18, 2022 |
| ASUSTek       | N501VW                      | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Dell          | Latitude E7470              | [2eca1925d5](https://linux-hardware.org/?probe=2eca1925d5) | Mar 16, 2022 |
| Dell          | Latitude E7470              | [b10d8b3a00](https://linux-hardware.org/?probe=b10d8b3a00) | Mar 16, 2022 |
| Dell          | Latitude E6530              | [2c3bfeff1d](https://linux-hardware.org/?probe=2c3bfeff1d) | Mar 13, 2022 |
| Unknown       | Unknown                     | [472d23c4f4](https://linux-hardware.org/?probe=472d23c4f4) | Mar 13, 2022 |
| ASUSTek       | X550VX                      | [91eafd1ed4](https://linux-hardware.org/?probe=91eafd1ed4) | Mar 04, 2022 |
| HP            | Pavilion dv6                | [dad6067f40](https://linux-hardware.org/?probe=dad6067f40) | Mar 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [29926fb03b](https://linux-hardware.org/?probe=29926fb03b) | Mar 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [071f146979](https://linux-hardware.org/?probe=071f146979) | Feb 24, 2022 |
| Dell          | Inspiron 5520               | [fa0603a25d](https://linux-hardware.org/?probe=fa0603a25d) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4d49233d4b](https://linux-hardware.org/?probe=4d49233d4b) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [93ca64d766](https://linux-hardware.org/?probe=93ca64d766) | Jan 28, 2022 |
| ASUSTek       | UX303UB                     | [c48fbc97e2](https://linux-hardware.org/?probe=c48fbc97e2) | Jan 22, 2022 |
| Alienware     | 17 R3                       | [032772ad42](https://linux-hardware.org/?probe=032772ad42) | Jan 20, 2022 |
| ASUSTek       | N55SF                       | [e800e249d1](https://linux-hardware.org/?probe=e800e249d1) | Jan 19, 2022 |
| ASUSTek       | N55SF                       | [104263a808](https://linux-hardware.org/?probe=104263a808) | Jan 19, 2022 |
| Dell          | Inspiron 7577               | [6875440733](https://linux-hardware.org/?probe=6875440733) | Jan 10, 2022 |
| ASUSTek       | X450LC                      | [8228658808](https://linux-hardware.org/?probe=8228658808) | Jan 09, 2022 |
| ASUSTek       | 1001PX                      | [ba7acc9c68](https://linux-hardware.org/?probe=ba7acc9c68) | Jan 01, 2022 |
| ASUSTek       | 1001PX                      | [a175657549](https://linux-hardware.org/?probe=a175657549) | Dec 31, 2021 |
| ASUSTek       | 1001PX                      | [48423d0bef](https://linux-hardware.org/?probe=48423d0bef) | Dec 31, 2021 |
| Lenovo        | G50-80 80E5                 | [71a50bcb50](https://linux-hardware.org/?probe=71a50bcb50) | Dec 30, 2021 |
| Lenovo        | G50-80 80E5                 | [d8d81e5c50](https://linux-hardware.org/?probe=d8d81e5c50) | Dec 30, 2021 |
| Lenovo        | G580 20150                  | [71135c1724](https://linux-hardware.org/?probe=71135c1724) | Dec 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [9f22de7369](https://linux-hardware.org/?probe=9f22de7369) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [dcbbdb5fc5](https://linux-hardware.org/?probe=dcbbdb5fc5) | Dec 23, 2021 |
| Acer          | Aspire E1-572G              | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | [5408a1a82b](https://linux-hardware.org/?probe=5408a1a82b) | Dec 21, 2021 |
| ASUSTek       | UX430UNR                    | [8e802c50ad](https://linux-hardware.org/?probe=8e802c50ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [7b6f9acbf8](https://linux-hardware.org/?probe=7b6f9acbf8) | Dec 15, 2021 |
| HP            | ZBook 15 G3                 | [2c739999fa](https://linux-hardware.org/?probe=2c739999fa) | Dec 10, 2021 |
| ASUSTek       | X580VD                      | [8473dd1cc0](https://linux-hardware.org/?probe=8473dd1cc0) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | [68820e21d2](https://linux-hardware.org/?probe=68820e21d2) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | [c7e180ab84](https://linux-hardware.org/?probe=c7e180ab84) | Dec 08, 2021 |
| Dell          | Latitude E7470              | [06666f541b](https://linux-hardware.org/?probe=06666f541b) | Dec 07, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [7eed1618fe](https://linux-hardware.org/?probe=7eed1618fe) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | [01c7adcf94](https://linux-hardware.org/?probe=01c7adcf94) | Nov 28, 2021 |
| HP            | EliteBook 840 G1            | [6eff02505f](https://linux-hardware.org/?probe=6eff02505f) | Nov 27, 2021 |
| HP            | EliteBook 745 G3            | [92968d4a23](https://linux-hardware.org/?probe=92968d4a23) | Nov 27, 2021 |
| ASUSTek       | GL702VMK                    | [ff58d2a76e](https://linux-hardware.org/?probe=ff58d2a76e) | Nov 21, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [81a7c19597](https://linux-hardware.org/?probe=81a7c19597) | Nov 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [f119e55cf9](https://linux-hardware.org/?probe=f119e55cf9) | Nov 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| Dell          | Latitude E7240              | [366228fab6](https://linux-hardware.org/?probe=366228fab6) | Nov 05, 2021 |
| HP            | ProBook 640 G2              | [d098305f2a](https://linux-hardware.org/?probe=d098305f2a) | Oct 30, 2021 |
| HP            | ProBook 640 G2              | [d99bdece1d](https://linux-hardware.org/?probe=d99bdece1d) | Oct 30, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8db63e7a74](https://linux-hardware.org/?probe=8db63e7a74) | Oct 28, 2021 |
| Sony          | VPCSA25GX                   | [be4db20b0e](https://linux-hardware.org/?probe=be4db20b0e) | Oct 25, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | [6ab1ce41db](https://linux-hardware.org/?probe=6ab1ce41db) | Oct 25, 2021 |
| Dell          | Inspiron N5010              | [6547cded19](https://linux-hardware.org/?probe=6547cded19) | Oct 22, 2021 |
| Dell          | Inspiron N5010              | [30c1b322ad](https://linux-hardware.org/?probe=30c1b322ad) | Oct 22, 2021 |
| ASUSTek       | U56E                        | [a610876405](https://linux-hardware.org/?probe=a610876405) | Oct 20, 2021 |
| HP            | Laptop 15-ef2xxx            | [4e6bceb431](https://linux-hardware.org/?probe=4e6bceb431) | Oct 18, 2021 |
| Acer          | Aspire A715-75G             | [87c7c24dcc](https://linux-hardware.org/?probe=87c7c24dcc) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | [0d9ad64b08](https://linux-hardware.org/?probe=0d9ad64b08) | Oct 15, 2021 |
| ASUSTek       | K55VD                       | [cce3e9bd74](https://linux-hardware.org/?probe=cce3e9bd74) | Oct 12, 2021 |
| HP            | EliteBook 840 G2            | [24efeaacb7](https://linux-hardware.org/?probe=24efeaacb7) | Oct 07, 2021 |
| HP            | ProBook 440 G2              | [cc83275513](https://linux-hardware.org/?probe=cc83275513) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [325655d6c5](https://linux-hardware.org/?probe=325655d6c5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [6cfb3f0c44](https://linux-hardware.org/?probe=6cfb3f0c44) | Sep 28, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0e614dfffe](https://linux-hardware.org/?probe=0e614dfffe) | Sep 27, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [3c4378f506](https://linux-hardware.org/?probe=3c4378f506) | Sep 25, 2021 |
| HP            | EliteBook 745 G2            | [2b74c7b1ff](https://linux-hardware.org/?probe=2b74c7b1ff) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | [2b132c74b6](https://linux-hardware.org/?probe=2b132c74b6) | Sep 16, 2021 |
| Acer          | Aspire V3-571G              | [ca2bc77aa5](https://linux-hardware.org/?probe=ca2bc77aa5) | Sep 16, 2021 |
| HP            | EliteBook 840 G2            | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | [ec0cd5d69b](https://linux-hardware.org/?probe=ec0cd5d69b) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | [7797008e19](https://linux-hardware.org/?probe=7797008e19) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | [07d1890920](https://linux-hardware.org/?probe=07d1890920) | Sep 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [a6221df8f8](https://linux-hardware.org/?probe=a6221df8f8) | Sep 10, 2021 |
| ASUSTek       | X540UV                      | [b0a231831a](https://linux-hardware.org/?probe=b0a231831a) | Sep 09, 2021 |
| Acer          | Aspire F5-573G              | [d47d63a84f](https://linux-hardware.org/?probe=d47d63a84f) | Sep 07, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [453f65a5e7](https://linux-hardware.org/?probe=453f65a5e7) | Sep 07, 2021 |
| Acer          | Aspire A715-71G             | [b915ae27b7](https://linux-hardware.org/?probe=b915ae27b7) | Sep 06, 2021 |
| Acer          | Aspire F5-573G              | [62fc103f71](https://linux-hardware.org/?probe=62fc103f71) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [b011298d66](https://linux-hardware.org/?probe=b011298d66) | Sep 01, 2021 |
| MSI           | Prestige 14 A10RB           | [2aaa6d05d2](https://linux-hardware.org/?probe=2aaa6d05d2) | Sep 01, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [9f01a4629a](https://linux-hardware.org/?probe=9f01a4629a) | Aug 28, 2021 |
| ASUSTek       | X550EA                      | [19a7dfc92a](https://linux-hardware.org/?probe=19a7dfc92a) | Aug 22, 2021 |
| ASUSTek       | K55VD                       | [bfe60273f6](https://linux-hardware.org/?probe=bfe60273f6) | Aug 09, 2021 |
| HP            | ZBook 15                    | [1a67896055](https://linux-hardware.org/?probe=1a67896055) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [31891cbc13](https://linux-hardware.org/?probe=31891cbc13) | Aug 08, 2021 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [fe27de6bbc](https://linux-hardware.org/?probe=fe27de6bbc) | Aug 07, 2021 |
| HP            | ENVY Laptop 13-aq0xxx       | [407501f166](https://linux-hardware.org/?probe=407501f166) | Aug 05, 2021 |
| ASUSTek       | N53SV                       | [1e165352ad](https://linux-hardware.org/?probe=1e165352ad) | Aug 04, 2021 |
| Acer          | Aspire 5749Z                | [a5c472e082](https://linux-hardware.org/?probe=a5c472e082) | Aug 01, 2021 |
| Acer          | Aspire 5749Z                | [538eb1efa0](https://linux-hardware.org/?probe=538eb1efa0) | Aug 01, 2021 |
| ASUSTek       | N53SV                       | [13e3cf7a5f](https://linux-hardware.org/?probe=13e3cf7a5f) | Jul 29, 2021 |
| Acer          | Aspire E5-475G              | [063facd29a](https://linux-hardware.org/?probe=063facd29a) | Jul 28, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [4b49f7026f](https://linux-hardware.org/?probe=4b49f7026f) | Jul 27, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [2bd8f0dd2e](https://linux-hardware.org/?probe=2bd8f0dd2e) | Jul 27, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [afb9cb6674](https://linux-hardware.org/?probe=afb9cb6674) | Jul 27, 2021 |
| Lenovo        | Z50-75 80EC                 | [5d118fd4cc](https://linux-hardware.org/?probe=5d118fd4cc) | Jul 26, 2021 |
| Dell          | Inspiron N4030              | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | ProBook 4540s               | [719b37c9ac](https://linux-hardware.org/?probe=719b37c9ac) | Jul 20, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | [0ae43f5015](https://linux-hardware.org/?probe=0ae43f5015) | Jul 20, 2021 |
| ASUSTek       | K55VD                       | [b26638f586](https://linux-hardware.org/?probe=b26638f586) | Jul 17, 2021 |
| ASUSTek       | K55VD                       | [8a28a4f7f5](https://linux-hardware.org/?probe=8a28a4f7f5) | Jul 17, 2021 |
| HP            | ProBook 450 G0              | [08f5207ee6](https://linux-hardware.org/?probe=08f5207ee6) | Jul 17, 2021 |
| ASUSTek       | X550LD                      | [b3bb7e1295](https://linux-hardware.org/?probe=b3bb7e1295) | Jul 17, 2021 |
| HP            | Notebook                    | [3fc4cb2f55](https://linux-hardware.org/?probe=3fc4cb2f55) | Jul 09, 2021 |
| Lenovo        | ThinkPad E560 20EV0005AD    | [fab11e73ee](https://linux-hardware.org/?probe=fab11e73ee) | Jun 29, 2021 |
| Acer          | Aspire 4736Z                | [6a5d92699d](https://linux-hardware.org/?probe=6a5d92699d) | Jun 23, 2021 |
| Dell          | Latitude D420               | [5f0d609bef](https://linux-hardware.org/?probe=5f0d609bef) | Jun 21, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [4af988fc2f](https://linux-hardware.org/?probe=4af988fc2f) | Jun 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [1fd8a9e8c8](https://linux-hardware.org/?probe=1fd8a9e8c8) | Jun 16, 2021 |
| Acer          | TravelMate P446-M           | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| ASUSTek       | N53SV                       | [28e717743a](https://linux-hardware.org/?probe=28e717743a) | Jun 06, 2021 |
| Acer          | Aspire R3-131T              | [35b68a0b4a](https://linux-hardware.org/?probe=35b68a0b4a) | Jun 06, 2021 |
| HP            | ProBook 4520s               | [b0a9a196db](https://linux-hardware.org/?probe=b0a9a196db) | Jun 03, 2021 |
| ASUSTek       | N56VM                       | [b3206cba40](https://linux-hardware.org/?probe=b3206cba40) | Jun 03, 2021 |
| Sony          | VGN-CS38GD_B                | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [74d1da4b68](https://linux-hardware.org/?probe=74d1da4b68) | May 28, 2021 |
| ASUSTek       | X550MJ                      | [208fc3f30f](https://linux-hardware.org/?probe=208fc3f30f) | May 25, 2021 |
| Acer          | Aspire R3-131T              | [28d19f1a59](https://linux-hardware.org/?probe=28d19f1a59) | May 25, 2021 |
| Acer          | Aspire R3-131T              | [512cc44d82](https://linux-hardware.org/?probe=512cc44d82) | May 21, 2021 |
| ASUSTek       | K53SM                       | [f0199bc53d](https://linux-hardware.org/?probe=f0199bc53d) | May 20, 2021 |
| ASUSTek       | T100TA                      | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| ASUSTek       | N56VM                       | [1417eccc8b](https://linux-hardware.org/?probe=1417eccc8b) | May 15, 2021 |
| HP            | EliteBook 725 G2            | [5dddeca3e8](https://linux-hardware.org/?probe=5dddeca3e8) | May 09, 2021 |
| Acer          | Aspire V3-574G              | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Dell          | XPS 15 9500                 | [2d12301b1c](https://linux-hardware.org/?probe=2d12301b1c) | May 05, 2021 |
| HP            | Laptop 15-bs0xx             | [57540cdfa4](https://linux-hardware.org/?probe=57540cdfa4) | May 03, 2021 |
| HP            | Laptop 15-bs0xx             | [8f0e9df209](https://linux-hardware.org/?probe=8f0e9df209) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [940758b420](https://linux-hardware.org/?probe=940758b420) | Apr 27, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | [ced3a1165d](https://linux-hardware.org/?probe=ced3a1165d) | Apr 24, 2021 |
| ASUSTek       | X555LF                      | [eb9637ae4a](https://linux-hardware.org/?probe=eb9637ae4a) | Apr 19, 2021 |
| Lenovo        | ThinkPad E590 20NB0057AD    | [d06cfc6dee](https://linux-hardware.org/?probe=d06cfc6dee) | Apr 18, 2021 |
| Acer          | AOD260                      | [97f6b98307](https://linux-hardware.org/?probe=97f6b98307) | Apr 16, 2021 |
| Lenovo        | ThinkPad T470p 20J6S08M0... | [84619b1b45](https://linux-hardware.org/?probe=84619b1b45) | Apr 15, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [1dcb2a173e](https://linux-hardware.org/?probe=1dcb2a173e) | Apr 14, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [28d13bbb26](https://linux-hardware.org/?probe=28d13bbb26) | Apr 14, 2021 |
| Acer          | Aspire E1-571G              | [7713767fa6](https://linux-hardware.org/?probe=7713767fa6) | Apr 10, 2021 |
| HP            | EliteBook 840 G2            | [9c00d55213](https://linux-hardware.org/?probe=9c00d55213) | Apr 10, 2021 |
| HP            | Laptop 15-bs0xx             | [9a9c3c8d26](https://linux-hardware.org/?probe=9a9c3c8d26) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| ASUSTek       | X542UQ                      | [5b0c97ade1](https://linux-hardware.org/?probe=5b0c97ade1) | Apr 09, 2021 |
| MSI           | CR610M                      | [e2e00880a3](https://linux-hardware.org/?probe=e2e00880a3) | Apr 08, 2021 |
| HP            | Laptop 15-bs0xx             | [60168d5b6d](https://linux-hardware.org/?probe=60168d5b6d) | Apr 07, 2021 |
| MSI           | CX62 6QL                    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire 4741                 | [ddda7566c5](https://linux-hardware.org/?probe=ddda7566c5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | [5fb915669a](https://linux-hardware.org/?probe=5fb915669a) | Apr 03, 2021 |
| Acer          | Aspire E1-571G              | [c5e7e65164](https://linux-hardware.org/?probe=c5e7e65164) | Apr 01, 2021 |
| HP            | EliteBook 745 G4            | [a5888bbded](https://linux-hardware.org/?probe=a5888bbded) | Apr 01, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | [9a4a054203](https://linux-hardware.org/?probe=9a4a054203) | Apr 01, 2021 |
| Acer          | Aspire E5-573G              | [bacb9e5030](https://linux-hardware.org/?probe=bacb9e5030) | Mar 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [344eec241a](https://linux-hardware.org/?probe=344eec241a) | Mar 21, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | [ca815648fc](https://linux-hardware.org/?probe=ca815648fc) | Mar 17, 2021 |
| Sony          | VGN-CS38GD_B                | [d5d788f2f3](https://linux-hardware.org/?probe=d5d788f2f3) | Mar 15, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | [75ba14ee94](https://linux-hardware.org/?probe=75ba14ee94) | Mar 14, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | [be98339598](https://linux-hardware.org/?probe=be98339598) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | [b7e39a92a0](https://linux-hardware.org/?probe=b7e39a92a0) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | [7ca6ad9361](https://linux-hardware.org/?probe=7ca6ad9361) | Mar 06, 2021 |
| ASUSTek       | K42JK                       | [bae11d222f](https://linux-hardware.org/?probe=bae11d222f) | Mar 04, 2021 |
| ASUSTek       | K42JK                       | [3ae670828a](https://linux-hardware.org/?probe=3ae670828a) | Mar 03, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | [fd21e67a3c](https://linux-hardware.org/?probe=fd21e67a3c) | Feb 28, 2021 |
| HP            | Pavilion g6                 | [2ce61d58bf](https://linux-hardware.org/?probe=2ce61d58bf) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [dda65f86ac](https://linux-hardware.org/?probe=dda65f86ac) | Feb 24, 2021 |
| HP            | ProBook 4540s               | [e3ff93ab0a](https://linux-hardware.org/?probe=e3ff93ab0a) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [ab787a4172](https://linux-hardware.org/?probe=ab787a4172) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [7ba0b6a17d](https://linux-hardware.org/?probe=7ba0b6a17d) | Feb 21, 2021 |
| Lenovo        | G580 20150                  | [d45ed4ad08](https://linux-hardware.org/?probe=d45ed4ad08) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | [520780b02d](https://linux-hardware.org/?probe=520780b02d) | Feb 18, 2021 |
| MSI           | Modern 14 A10M              | [62c9e819cd](https://linux-hardware.org/?probe=62c9e819cd) | Feb 17, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [8070e672a7](https://linux-hardware.org/?probe=8070e672a7) | Feb 15, 2021 |
| Lenovo        | Flex 2-15 20405             | [ee986e1fdd](https://linux-hardware.org/?probe=ee986e1fdd) | Feb 11, 2021 |
| Lenovo        | Flex 2-15 20405             | [b661aa21f1](https://linux-hardware.org/?probe=b661aa21f1) | Feb 09, 2021 |
| Acer          | Aspire E5-553G              | [0c9067579c](https://linux-hardware.org/?probe=0c9067579c) | Feb 09, 2021 |
| Lenovo        | Z50-70 20354                | [ab4bc22a87](https://linux-hardware.org/?probe=ab4bc22a87) | Feb 06, 2021 |
| Acer          | Aspire E5-553G              | [5e9aa1c3de](https://linux-hardware.org/?probe=5e9aa1c3de) | Feb 06, 2021 |
| ASUSTek       | X456URK                     | [6c3b5bdfb1](https://linux-hardware.org/?probe=6c3b5bdfb1) | Feb 05, 2021 |
| Dell          | Inspiron N4010              | [d383b4a5e7](https://linux-hardware.org/?probe=d383b4a5e7) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | [2bd7b5699d](https://linux-hardware.org/?probe=2bd7b5699d) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | [82920966cf](https://linux-hardware.org/?probe=82920966cf) | Feb 01, 2021 |
| Lenovo        | Flex 2-15 20405             | [d82031935e](https://linux-hardware.org/?probe=d82031935e) | Feb 01, 2021 |
| ASUSTek       | N56JR                       | [29ad612f88](https://linux-hardware.org/?probe=29ad612f88) | Jan 28, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [2960ce1b31](https://linux-hardware.org/?probe=2960ce1b31) | Jan 27, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [b97b822412](https://linux-hardware.org/?probe=b97b822412) | Jan 27, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | [a0eb5fc713](https://linux-hardware.org/?probe=a0eb5fc713) | Jan 20, 2021 |
| Dell          | Vostro 5470                 | [2fa2f12de6](https://linux-hardware.org/?probe=2fa2f12de6) | Jan 19, 2021 |
| Sony          | VPCZ126GG                   | [537d05799c](https://linux-hardware.org/?probe=537d05799c) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | [66598d3f69](https://linux-hardware.org/?probe=66598d3f69) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | [113406e67d](https://linux-hardware.org/?probe=113406e67d) | Jan 15, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [703dd398d1](https://linux-hardware.org/?probe=703dd398d1) | Jan 14, 2021 |
| ASUSTek       | X542UN                      | [44633c4ff2](https://linux-hardware.org/?probe=44633c4ff2) | Jan 13, 2021 |
| Sony          | SVF15N12SGB                 | [3ff592b868](https://linux-hardware.org/?probe=3ff592b868) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34483... | [4e6cc9fdc4](https://linux-hardware.org/?probe=4e6cc9fdc4) | Jan 03, 2021 |
| HP            | Laptop 15-bs0xx             | [96280026fb](https://linux-hardware.org/?probe=96280026fb) | Jan 03, 2021 |
| Dell          | Vostro 1015                 | [7243a2df4f](https://linux-hardware.org/?probe=7243a2df4f) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Acer          | Aspire 5755G                | [5577ccef28](https://linux-hardware.org/?probe=5577ccef28) | Dec 28, 2020 |
| HP            | ProBook 4540s               | [86bd405fac](https://linux-hardware.org/?probe=86bd405fac) | Dec 27, 2020 |
| HP            | ProBook 4540s               | [7a93e1b05a](https://linux-hardware.org/?probe=7a93e1b05a) | Dec 27, 2020 |
| Dell          | Vostro 1015                 | [9be1d69693](https://linux-hardware.org/?probe=9be1d69693) | Dec 26, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [f7f32358db](https://linux-hardware.org/?probe=f7f32358db) | Dec 24, 2020 |
| HP            | Laptop 15-bs0xx             | [ec5fac5f1d](https://linux-hardware.org/?probe=ec5fac5f1d) | Dec 24, 2020 |
| MSI           | GE60 2PC                    | [46af0a2d84](https://linux-hardware.org/?probe=46af0a2d84) | Dec 22, 2020 |
| MSI           | GE60 2PC                    | [c659f6a910](https://linux-hardware.org/?probe=c659f6a910) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T10... | [d5a85767cd](https://linux-hardware.org/?probe=d5a85767cd) | Dec 18, 2020 |
| Dell          | Inspiron N5110              | [a6bf272580](https://linux-hardware.org/?probe=a6bf272580) | Dec 18, 2020 |
| HP            | ProBook 450 G4              | [fe5ef27982](https://linux-hardware.org/?probe=fe5ef27982) | Dec 17, 2020 |
| Acer          | Aspire A715-74G             | [03f5d24d56](https://linux-hardware.org/?probe=03f5d24d56) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | [886054e929](https://linux-hardware.org/?probe=886054e929) | Dec 15, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [67aa2554c3](https://linux-hardware.org/?probe=67aa2554c3) | Dec 10, 2020 |
| MSI           | CX62 6QL                    | [90a60a1e78](https://linux-hardware.org/?probe=90a60a1e78) | Dec 06, 2020 |
| MSI           | CX62 6QL                    | [9b4aaf5856](https://linux-hardware.org/?probe=9b4aaf5856) | Dec 06, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [47835d66f6](https://linux-hardware.org/?probe=47835d66f6) | Dec 01, 2020 |
| Sony          | VPCEH11FX                   | [d3ff8db043](https://linux-hardware.org/?probe=d3ff8db043) | Nov 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8e0bc13a31](https://linux-hardware.org/?probe=8e0bc13a31) | Nov 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [c099ac62d5](https://linux-hardware.org/?probe=c099ac62d5) | Nov 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [7787345258](https://linux-hardware.org/?probe=7787345258) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Acer          | TravelMate 5742Z            | [be124397e2](https://linux-hardware.org/?probe=be124397e2) | Nov 13, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3bc3e0823a](https://linux-hardware.org/?probe=3bc3e0823a) | Nov 09, 2020 |
| HP            | ProBook 4540s               | [4864704e84](https://linux-hardware.org/?probe=4864704e84) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [adbb505553](https://linux-hardware.org/?probe=adbb505553) | Nov 08, 2020 |
| ASUSTek       | X550IU                      | [543559dfac](https://linux-hardware.org/?probe=543559dfac) | Nov 07, 2020 |
| ASUSTek       | X550IU                      | [c7b7b29a68](https://linux-hardware.org/?probe=c7b7b29a68) | Nov 07, 2020 |
| Lenovo        | E5                          | [3b7111b4a2](https://linux-hardware.org/?probe=3b7111b4a2) | Nov 07, 2020 |
| Lenovo        | E5                          | [cb3bf5a3df](https://linux-hardware.org/?probe=cb3bf5a3df) | Nov 07, 2020 |
| ASUSTek       | X550VXK                     | [5f95436c09](https://linux-hardware.org/?probe=5f95436c09) | Nov 06, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [42ef7e253c](https://linux-hardware.org/?probe=42ef7e253c) | Nov 01, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [cba527dd9f](https://linux-hardware.org/?probe=cba527dd9f) | Nov 01, 2020 |
| Acer          | Aspire 5741G                | [75bacf18a7](https://linux-hardware.org/?probe=75bacf18a7) | Oct 31, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [f6c5e1d108](https://linux-hardware.org/?probe=f6c5e1d108) | Oct 28, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [11db584122](https://linux-hardware.org/?probe=11db584122) | Oct 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [7525ff1dde](https://linux-hardware.org/?probe=7525ff1dde) | Oct 23, 2020 |
| ASUSTek       | N552VW                      | [6893d4927d](https://linux-hardware.org/?probe=6893d4927d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| Lenovo        | B50-80 80EW                 | [c6bf9e5376](https://linux-hardware.org/?probe=c6bf9e5376) | Oct 17, 2020 |
| ASUSTek       | X505BA                      | [6f5c254a9f](https://linux-hardware.org/?probe=6f5c254a9f) | Oct 15, 2020 |
| Sony          | VPCSB36FG                   | [2763c330eb](https://linux-hardware.org/?probe=2763c330eb) | Oct 09, 2020 |
| ASUSTek       | UX430UA                     | [d6586b9bb8](https://linux-hardware.org/?probe=d6586b9bb8) | Oct 05, 2020 |
| Sony          | VPCEB1SFX                   | [01b67b1979](https://linux-hardware.org/?probe=01b67b1979) | Sep 27, 2020 |
| Sony          | VPCEB1SFX                   | [616d06a0b0](https://linux-hardware.org/?probe=616d06a0b0) | Sep 26, 2020 |
| HP            | EliteBook 725 G2            | [6f184c4bc8](https://linux-hardware.org/?probe=6f184c4bc8) | Sep 26, 2020 |
| ASUSTek       | K42Jc                       | [9808a6bb0c](https://linux-hardware.org/?probe=9808a6bb0c) | Sep 25, 2020 |
| Sony          | VPCSB36FG                   | [5ea9c0eca9](https://linux-hardware.org/?probe=5ea9c0eca9) | Sep 24, 2020 |
| HP            | EliteBook 725 G2            | [9456172087](https://linux-hardware.org/?probe=9456172087) | Sep 18, 2020 |
| ASUSTek       | N501VW                      | [36d0455f5f](https://linux-hardware.org/?probe=36d0455f5f) | Sep 15, 2020 |
| Sony          | VPCSB36FG                   | [5ed2d21f85](https://linux-hardware.org/?probe=5ed2d21f85) | Sep 05, 2020 |
| ASUSTek       | K52F                        | [1658b8903d](https://linux-hardware.org/?probe=1658b8903d) | Sep 04, 2020 |
| ASUSTek       | K52F                        | [b7a5d27a01](https://linux-hardware.org/?probe=b7a5d27a01) | Sep 04, 2020 |
| ASUSTek       | K42Jc                       | [79d7ee2e74](https://linux-hardware.org/?probe=79d7ee2e74) | Sep 04, 2020 |
| Sony          | VPCSB36FG                   | [61bc69e87c](https://linux-hardware.org/?probe=61bc69e87c) | Sep 04, 2020 |
| Dell          | Latitude E6530              | [c026f89bd8](https://linux-hardware.org/?probe=c026f89bd8) | Aug 31, 2020 |
| MSI           | Prestige 14 A10RB           | [b7fff5e5cc](https://linux-hardware.org/?probe=b7fff5e5cc) | Aug 28, 2020 |
| HP            | EliteBook 8570w             | [c172701a56](https://linux-hardware.org/?probe=c172701a56) | Aug 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [af595ebfde](https://linux-hardware.org/?probe=af595ebfde) | Aug 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [c03d58914c](https://linux-hardware.org/?probe=c03d58914c) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [55c0c83149](https://linux-hardware.org/?probe=55c0c83149) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [e97f7b8582](https://linux-hardware.org/?probe=e97f7b8582) | Aug 02, 2020 |
| MSI           | GF63 Thin 9RC               | [f7eff6d78e](https://linux-hardware.org/?probe=f7eff6d78e) | Jul 28, 2020 |
| MSI           | GF63 Thin 9RC               | [7b12eabb3e](https://linux-hardware.org/?probe=7b12eabb3e) | Jul 28, 2020 |
| Lenovo        | ThinkPad E490 20N8000JUE    | [66d2ca1186](https://linux-hardware.org/?probe=66d2ca1186) | Jul 22, 2020 |
| ASUSTek       | N53Jq                       | [4d04d4ee3a](https://linux-hardware.org/?probe=4d04d4ee3a) | Jul 19, 2020 |
| Acer          | Aspire V3-571G              | [d7789565b7](https://linux-hardware.org/?probe=d7789565b7) | Jul 18, 2020 |
| ASUSTek       | N56JN                       | [43c91be0b3](https://linux-hardware.org/?probe=43c91be0b3) | Jul 16, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [e9a3474bde](https://linux-hardware.org/?probe=e9a3474bde) | Jul 09, 2020 |
| Acer          | TravelMate 5742Z            | [de25d26410](https://linux-hardware.org/?probe=de25d26410) | Jul 05, 2020 |
| Acer          | Aspire V5-561G              | [81b19839f7](https://linux-hardware.org/?probe=81b19839f7) | Jul 02, 2020 |
| ASUSTek       | N56JN                       | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| ASUSTek       | X580VD                      | [1ad8491ca0](https://linux-hardware.org/?probe=1ad8491ca0) | Jun 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [376ebf1819](https://linux-hardware.org/?probe=376ebf1819) | Jun 14, 2020 |
| Acer          | Aspire F5-573G              | [56a1c895ee](https://linux-hardware.org/?probe=56a1c895ee) | Jun 07, 2020 |
| Acer          | Aspire V5-572G              | [4a67c5fabb](https://linux-hardware.org/?probe=4a67c5fabb) | Jun 03, 2020 |
| ASUSTek       | X510UQR                     | [8fd66dd600](https://linux-hardware.org/?probe=8fd66dd600) | Jun 01, 2020 |
| ASUSTek       | X510UQR                     | [fbd9ae49c7](https://linux-hardware.org/?probe=fbd9ae49c7) | Jun 01, 2020 |
| Dell          | Inspiron N5110              | [d059aa2096](https://linux-hardware.org/?probe=d059aa2096) | May 29, 2020 |
| Sony          | VGN-SR165E                  | [ee7e382325](https://linux-hardware.org/?probe=ee7e382325) | May 27, 2020 |
| Lenovo        | G580 20157                  | [639a8b36be](https://linux-hardware.org/?probe=639a8b36be) | May 23, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [870f5869a0](https://linux-hardware.org/?probe=870f5869a0) | May 22, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [842fbba95c](https://linux-hardware.org/?probe=842fbba95c) | May 22, 2020 |
| Lenovo        | G580 20157                  | [c9967bfff4](https://linux-hardware.org/?probe=c9967bfff4) | May 22, 2020 |
| Fujitsu       | LIFEBOOK NH570              | [58dbbb5f10](https://linux-hardware.org/?probe=58dbbb5f10) | May 22, 2020 |
| Acer          | Aspire V5-572G              | [d919340bf8](https://linux-hardware.org/?probe=d919340bf8) | May 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91908a3d7e](https://linux-hardware.org/?probe=91908a3d7e) | May 15, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3448fe759e](https://linux-hardware.org/?probe=3448fe759e) | May 13, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [d27ef604e7](https://linux-hardware.org/?probe=d27ef604e7) | May 10, 2020 |
| HP            | EliteBook 8470p             | [cc84ca4df1](https://linux-hardware.org/?probe=cc84ca4df1) | May 08, 2020 |
| HP            | EliteBook 8470p             | [150b4cbfba](https://linux-hardware.org/?probe=150b4cbfba) | May 08, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [efe32a1257](https://linux-hardware.org/?probe=efe32a1257) | May 07, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [3cac051446](https://linux-hardware.org/?probe=3cac051446) | May 07, 2020 |
| HP            | EliteBook 8470p             | [543fb035d1](https://linux-hardware.org/?probe=543fb035d1) | May 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7d8b34f96f](https://linux-hardware.org/?probe=7d8b34f96f) | May 03, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96005fbb6f](https://linux-hardware.org/?probe=96005fbb6f) | Apr 28, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [3405972303](https://linux-hardware.org/?probe=3405972303) | Apr 27, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [2950c5ee7f](https://linux-hardware.org/?probe=2950c5ee7f) | Apr 27, 2020 |
| HP            | EliteBook 8470p             | [f82980ac2c](https://linux-hardware.org/?probe=f82980ac2c) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| HP            | EliteBook 8470p             | [abfe333fb8](https://linux-hardware.org/?probe=abfe333fb8) | Apr 25, 2020 |
| HP            | EliteBook 8470p             | [9e8575f75a](https://linux-hardware.org/?probe=9e8575f75a) | Apr 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5ec8b8b3b7](https://linux-hardware.org/?probe=5ec8b8b3b7) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| Apple         | MacBookAir7,2               | [680bbeabad](https://linux-hardware.org/?probe=680bbeabad) | Apr 24, 2020 |
| HP            | Pavilion g6                 | [66ba3bc59b](https://linux-hardware.org/?probe=66ba3bc59b) | Apr 23, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [82f761db09](https://linux-hardware.org/?probe=82f761db09) | Apr 23, 2020 |
| Lenovo        | ThinkPad E480 20KN007XAD    | [8310d15c91](https://linux-hardware.org/?probe=8310d15c91) | Apr 18, 2020 |
| Lenovo        | IdeaPad Z510 20287          | [74699b5097](https://linux-hardware.org/?probe=74699b5097) | Apr 16, 2020 |
| Lenovo        | G505 20240                  | [93a89841fd](https://linux-hardware.org/?probe=93a89841fd) | Apr 12, 2020 |
| ASUSTek       | X550IU                      | [943b36ee80](https://linux-hardware.org/?probe=943b36ee80) | Apr 10, 2020 |
| Sony          | VPCEH11FX                   | [e0ef96682b](https://linux-hardware.org/?probe=e0ef96682b) | Apr 09, 2020 |
| ASUSTek       | G750JH                      | [45a70fa311](https://linux-hardware.org/?probe=45a70fa311) | Apr 08, 2020 |
| ASUSTek       | G750JH                      | [3314aa590e](https://linux-hardware.org/?probe=3314aa590e) | Apr 08, 2020 |
| Dell          | Latitude D630               | [98199f8421](https://linux-hardware.org/?probe=98199f8421) | Apr 07, 2020 |
| Lenovo        | Z50-70 20354                | [839c8344be](https://linux-hardware.org/?probe=839c8344be) | Apr 07, 2020 |
| ASUSTek       | 1015CX                      | [c98f5bcee3](https://linux-hardware.org/?probe=c98f5bcee3) | Apr 05, 2020 |
| ASUSTek       | 1015CX                      | [216b680d21](https://linux-hardware.org/?probe=216b680d21) | Apr 05, 2020 |
| Dell          | Latitude 7350               | [3ecdea8fcc](https://linux-hardware.org/?probe=3ecdea8fcc) | Apr 03, 2020 |
| Toshiba       | PORTEGE R930                | [0dbe97d54b](https://linux-hardware.org/?probe=0dbe97d54b) | Mar 30, 2020 |
| Dell          | Inspiron 1545               | [ffeee579db](https://linux-hardware.org/?probe=ffeee579db) | Mar 28, 2020 |
| Dell          | Inspiron 3443               | [0a21a54858](https://linux-hardware.org/?probe=0a21a54858) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | [aa94d9ab9b](https://linux-hardware.org/?probe=aa94d9ab9b) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | [96f26b673c](https://linux-hardware.org/?probe=96f26b673c) | Mar 28, 2020 |
| Dell          | Vostro 3578                 | [21b92f29e5](https://linux-hardware.org/?probe=21b92f29e5) | Mar 28, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e7effd8e19](https://linux-hardware.org/?probe=e7effd8e19) | Mar 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [aa7093b56c](https://linux-hardware.org/?probe=aa7093b56c) | Mar 23, 2020 |
| Dell          | Inspiron 5570               | [a79912cfdf](https://linux-hardware.org/?probe=a79912cfdf) | Mar 22, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | [409951a0dd](https://linux-hardware.org/?probe=409951a0dd) | Mar 20, 2020 |
| Dell          | Studio 1558                 | [06b0f26f6a](https://linux-hardware.org/?probe=06b0f26f6a) | Mar 12, 2020 |
| Dell          | Studio 1558                 | [57fddb1856](https://linux-hardware.org/?probe=57fddb1856) | Mar 12, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [b224a48803](https://linux-hardware.org/?probe=b224a48803) | Mar 04, 2020 |
| ASUSTek       | N82JQ                       | [b1b698b060](https://linux-hardware.org/?probe=b1b698b060) | Mar 02, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [910ec05246](https://linux-hardware.org/?probe=910ec05246) | Feb 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [ddb0fad848](https://linux-hardware.org/?probe=ddb0fad848) | Feb 29, 2020 |
| Dell          | Vostro 1015                 | [091443df09](https://linux-hardware.org/?probe=091443df09) | Feb 20, 2020 |
| Toshiba       | Satellite L655              | [c04cf86240](https://linux-hardware.org/?probe=c04cf86240) | Feb 15, 2020 |
| Toshiba       | Satellite L655              | [00e7d3f0b6](https://linux-hardware.org/?probe=00e7d3f0b6) | Feb 15, 2020 |
| Lenovo        | V580c 20160                 | [7e02c8c738](https://linux-hardware.org/?probe=7e02c8c738) | Feb 11, 2020 |
| Sony          | VPCSB19GG                   | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [759e13afc4](https://linux-hardware.org/?probe=759e13afc4) | Feb 02, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [32f19ab04d](https://linux-hardware.org/?probe=32f19ab04d) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | [dccdce5101](https://linux-hardware.org/?probe=dccdce5101) | Jan 23, 2020 |
| Dell          | Vostro 1510                 | [51fbe1ce5b](https://linux-hardware.org/?probe=51fbe1ce5b) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | [664116ebbf](https://linux-hardware.org/?probe=664116ebbf) | Jan 22, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [f77d00b6ce](https://linux-hardware.org/?probe=f77d00b6ce) | Jan 10, 2020 |
| Dell          | Precision M4800             | [cc63357309](https://linux-hardware.org/?probe=cc63357309) | Jan 09, 2020 |
| Lenovo        | ThinkPad X131e 33711T4      | [f06e98b417](https://linux-hardware.org/?probe=f06e98b417) | Jan 08, 2020 |
| HP            | ProBook 4540s               | [9ef64f7487](https://linux-hardware.org/?probe=9ef64f7487) | Jan 03, 2020 |
| Lenovo        | G510 20238                  | [63fd9a500f](https://linux-hardware.org/?probe=63fd9a500f) | Dec 27, 2019 |
| Lenovo        | G510 20238                  | [8543221f24](https://linux-hardware.org/?probe=8543221f24) | Dec 27, 2019 |
| HP            | EliteBook 2740p             | [82cb2d5e90](https://linux-hardware.org/?probe=82cb2d5e90) | Dec 26, 2019 |
| Dell          | Inspiron N5040              | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| ASUSTek       | X542UN                      | [4b7f71d936](https://linux-hardware.org/?probe=4b7f71d936) | Dec 14, 2019 |
| Lenovo        | G50-70 20351                | [f30b5e8075](https://linux-hardware.org/?probe=f30b5e8075) | Dec 09, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [15babe41d0](https://linux-hardware.org/?probe=15babe41d0) | Nov 26, 2019 |
| ASUSTek       | B9440UA                     | [ed7fb8cbb9](https://linux-hardware.org/?probe=ed7fb8cbb9) | Nov 15, 2019 |
| ASUSTek       | B9440UA                     | [5e184acc59](https://linux-hardware.org/?probe=5e184acc59) | Nov 15, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [f13de25d56](https://linux-hardware.org/?probe=f13de25d56) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dda0a53712](https://linux-hardware.org/?probe=dda0a53712) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b86e3d7141](https://linux-hardware.org/?probe=b86e3d7141) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| HP            | Pavilion 15                 | [57540edaa7](https://linux-hardware.org/?probe=57540edaa7) | Nov 12, 2019 |
| ASUSTek       | B9440UA                     | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| Dell          | Vostro 1520                 | [247d9e9c2f](https://linux-hardware.org/?probe=247d9e9c2f) | Nov 01, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [797965c573](https://linux-hardware.org/?probe=797965c573) | Oct 30, 2019 |
| Dell          | Vostro 1015                 | [400532e714](https://linux-hardware.org/?probe=400532e714) | Oct 24, 2019 |
| Dell          | Vostro 1015                 | [df8815e747](https://linux-hardware.org/?probe=df8815e747) | Oct 24, 2019 |
| ASUSTek       | N501VW                      | [4d2a1a9add](https://linux-hardware.org/?probe=4d2a1a9add) | Oct 16, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [d1394d6252](https://linux-hardware.org/?probe=d1394d6252) | Oct 11, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [c4f25ea846](https://linux-hardware.org/?probe=c4f25ea846) | Oct 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c8223df556](https://linux-hardware.org/?probe=c8223df556) | Oct 03, 2019 |
| Dell          | Inspiron N4050              | [153db5ae1b](https://linux-hardware.org/?probe=153db5ae1b) | Oct 01, 2019 |
| Lenovo        | G50-45 80E3                 | [a814f0be14](https://linux-hardware.org/?probe=a814f0be14) | Sep 26, 2019 |
| Lenovo        | G50-45 80E3                 | [4c39be72b3](https://linux-hardware.org/?probe=4c39be72b3) | Sep 26, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [fbbabc5836](https://linux-hardware.org/?probe=fbbabc5836) | Sep 23, 2019 |
| Lenovo        | G50-70 20351                | [0143228659](https://linux-hardware.org/?probe=0143228659) | Sep 20, 2019 |
| Lenovo        | G50-70 20351                | [6e13970f68](https://linux-hardware.org/?probe=6e13970f68) | Sep 18, 2019 |
| ASUSTek       | X556UQK                     | [cd4ce4d624](https://linux-hardware.org/?probe=cd4ce4d624) | Sep 12, 2019 |
| HP            | Pavilion 15                 | [c56817e0e4](https://linux-hardware.org/?probe=c56817e0e4) | Sep 10, 2019 |
| HP            | Pavilion g6                 | [81b3b2667e](https://linux-hardware.org/?probe=81b3b2667e) | Sep 03, 2019 |
| Acer          | Aspire V3-571G              | [a4f33fd40a](https://linux-hardware.org/?probe=a4f33fd40a) | Sep 03, 2019 |
| HP            | ProBook 4540s               | [1349a15c0f](https://linux-hardware.org/?probe=1349a15c0f) | Sep 01, 2019 |
| Lenovo        | ThinkPad E470 20H1002DAD    | [75804928d2](https://linux-hardware.org/?probe=75804928d2) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [579809b8b0](https://linux-hardware.org/?probe=579809b8b0) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [81e015523a](https://linux-hardware.org/?probe=81e015523a) | Aug 30, 2019 |
| HP            | EliteBook 2540p             | [72437e888c](https://linux-hardware.org/?probe=72437e888c) | Aug 29, 2019 |
| ASUSTek       | X102BA                      | [8365a8b9d6](https://linux-hardware.org/?probe=8365a8b9d6) | Aug 27, 2019 |
| ASUSTek       | X102BA                      | [43b9931c92](https://linux-hardware.org/?probe=43b9931c92) | Aug 26, 2019 |
| MSI           | MS-1454                     | [b03f58cc28](https://linux-hardware.org/?probe=b03f58cc28) | Aug 23, 2019 |
| MSI           | MS-1454                     | [94bfc26599](https://linux-hardware.org/?probe=94bfc26599) | Aug 23, 2019 |
| ASUSTek       | X540UPR                     | [2f40c492db](https://linux-hardware.org/?probe=2f40c492db) | Aug 12, 2019 |
| Lenovo        | ThinkPad X201 3249CTO       | [24c83ab728](https://linux-hardware.org/?probe=24c83ab728) | Aug 09, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | [2507713bd4](https://linux-hardware.org/?probe=2507713bd4) | Aug 06, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | [0ad209e005](https://linux-hardware.org/?probe=0ad209e005) | Aug 06, 2019 |
| ASUSTek       | X555LJ                      | [541fb4f240](https://linux-hardware.org/?probe=541fb4f240) | Aug 06, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [2ab556fd2e](https://linux-hardware.org/?probe=2ab556fd2e) | Aug 03, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [3ff8ae9e18](https://linux-hardware.org/?probe=3ff8ae9e18) | Aug 01, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [9518b70a0d](https://linux-hardware.org/?probe=9518b70a0d) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [9c80796306](https://linux-hardware.org/?probe=9c80796306) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [66cc9aa111](https://linux-hardware.org/?probe=66cc9aa111) | Jul 31, 2019 |
| HP            | Pavilion dv6                | [38f37f78c5](https://linux-hardware.org/?probe=38f37f78c5) | Jul 29, 2019 |
| ASUSTek       | FX503VD                     | [c53df5f083](https://linux-hardware.org/?probe=c53df5f083) | Jul 27, 2019 |
| ASUSTek       | FX503VD                     | [051b4df60a](https://linux-hardware.org/?probe=051b4df60a) | Jul 27, 2019 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [b6b40de397](https://linux-hardware.org/?probe=b6b40de397) | Jul 26, 2019 |
| ASUSTek       | GL553VD                     | [1a816e6ebb](https://linux-hardware.org/?probe=1a816e6ebb) | Jul 23, 2019 |
| Acer          | Aspire V3-571G              | [6478022b75](https://linux-hardware.org/?probe=6478022b75) | Jul 21, 2019 |
| Acer          | Aspire V3-571G              | [22e01f3d1f](https://linux-hardware.org/?probe=22e01f3d1f) | Jul 21, 2019 |
| ASUSTek       | X542UN                      | [0120b3a78b](https://linux-hardware.org/?probe=0120b3a78b) | Jul 19, 2019 |
| HP            | ProBook 450 G1              | [ce6df77b4c](https://linux-hardware.org/?probe=ce6df77b4c) | Jul 18, 2019 |
| HP            | ProBook 450 G1              | [997a4ec1c4](https://linux-hardware.org/?probe=997a4ec1c4) | Jul 18, 2019 |
| ASUSTek       | X411UNV                     | [ca77267e34](https://linux-hardware.org/?probe=ca77267e34) | Jul 17, 2019 |
| HP            | EliteBook Revolve 810 G3    | [46408abbb6](https://linux-hardware.org/?probe=46408abbb6) | Jul 12, 2019 |
| Lenovo        | AILZx                       | [3673023593](https://linux-hardware.org/?probe=3673023593) | Jun 27, 2019 |
| Lenovo        | AILZx                       | [e4c012a605](https://linux-hardware.org/?probe=e4c012a605) | Jun 27, 2019 |
| ASUSTek       | UX550VD                     | [b4ed65654c](https://linux-hardware.org/?probe=b4ed65654c) | Jun 26, 2019 |
| ASUSTek       | UX550VD                     | [dfc972293d](https://linux-hardware.org/?probe=dfc972293d) | Jun 25, 2019 |
| Dell          | Latitude E6500              | [5d172397d7](https://linux-hardware.org/?probe=5d172397d7) | Jun 10, 2019 |
| ASUSTek       | X556URK                     | [1ac09da8a9](https://linux-hardware.org/?probe=1ac09da8a9) | Jun 07, 2019 |
| Dell          | Inspiron MM061              | [586a6a9f8a](https://linux-hardware.org/?probe=586a6a9f8a) | Jun 07, 2019 |
| Dell          | Inspiron MM061              | [3633557547](https://linux-hardware.org/?probe=3633557547) | Jun 06, 2019 |
| Acer          | Aspire V3-571G              | [116b742db8](https://linux-hardware.org/?probe=116b742db8) | Jun 05, 2019 |
| Dell          | Latitude E6410              | [91ff183bf0](https://linux-hardware.org/?probe=91ff183bf0) | Jun 02, 2019 |
| Dell          | Latitude E6410              | [3029853366](https://linux-hardware.org/?probe=3029853366) | Jun 02, 2019 |
| ASUSTek       | 1005PX                      | [33f338599d](https://linux-hardware.org/?probe=33f338599d) | May 29, 2019 |
| ASUSTek       | X541NA                      | [b8a49028c8](https://linux-hardware.org/?probe=b8a49028c8) | May 27, 2019 |
| ASUSTek       | N550JV                      | [1f0902bced](https://linux-hardware.org/?probe=1f0902bced) | May 17, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [89b4ae088c](https://linux-hardware.org/?probe=89b4ae088c) | May 16, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [4626315623](https://linux-hardware.org/?probe=4626315623) | May 14, 2019 |
| Dell          | Vostro 1500                 | [7008fbfa25](https://linux-hardware.org/?probe=7008fbfa25) | May 13, 2019 |
| HP            | EliteBook 8460w             | [2e2a41395d](https://linux-hardware.org/?probe=2e2a41395d) | May 07, 2019 |
| HP            | EliteBook Revolve 810 G3    | [e50b27ba1a](https://linux-hardware.org/?probe=e50b27ba1a) | Apr 27, 2019 |
| ASUSTek       | N501VW                      | [976a879300](https://linux-hardware.org/?probe=976a879300) | Apr 27, 2019 |
| Acer          | Aspire 5738                 | [9b6046b160](https://linux-hardware.org/?probe=9b6046b160) | Apr 22, 2019 |
| Fujitsu       | LIFEBOOK AH530/HD6          | [7c65853191](https://linux-hardware.org/?probe=7c65853191) | Apr 21, 2019 |
| Dell          | Inspiron 5567               | [cc9157e4bd](https://linux-hardware.org/?probe=cc9157e4bd) | Apr 14, 2019 |
| Lenovo        | V330-15IKB 81AX             | [1218f381aa](https://linux-hardware.org/?probe=1218f381aa) | Apr 11, 2019 |
| Lenovo        | IdeaPad Z510 20287          | [b9f44fe73b](https://linux-hardware.org/?probe=b9f44fe73b) | Apr 11, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ea6eec5a29](https://linux-hardware.org/?probe=ea6eec5a29) | Apr 03, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f7854f2bb7](https://linux-hardware.org/?probe=f7854f2bb7) | Apr 03, 2019 |
| Lenovo        | G500 20236                  | [2dd89e3983](https://linux-hardware.org/?probe=2dd89e3983) | Apr 03, 2019 |
| Lenovo        | G500 20236                  | [9e505ea7e9](https://linux-hardware.org/?probe=9e505ea7e9) | Apr 03, 2019 |
| HP            | EliteBook 8470p             | [2d5727bd09](https://linux-hardware.org/?probe=2d5727bd09) | Apr 02, 2019 |
| HP            | EliteBook 8570p             | [fd1396f058](https://linux-hardware.org/?probe=fd1396f058) | Mar 29, 2019 |
| Lenovo        | V330-15IKB 81AX             | [ec89277577](https://linux-hardware.org/?probe=ec89277577) | Mar 09, 2019 |
| Acer          | Aspire A715-71G             | [b01e1626a7](https://linux-hardware.org/?probe=b01e1626a7) | Oct 31, 2018 |
| ASUSTek       | GL553VE                     | [3cdb244ea4](https://linux-hardware.org/?probe=3cdb244ea4) | Mar 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 71        | 19.61%  |
| Ubuntu 18.04                 | 54        | 14.92%  |
| Fedora 33                    | 13        | 3.59%   |
| Arch                         | 13        | 3.59%   |
| Ubuntu 19.04                 | 10        | 2.76%   |
| Arch Rolling                 | 10        | 2.76%   |
| Ubuntu 22.04                 | 8         | 2.21%   |
| Fedora 34                    | 8         | 2.21%   |
| Ubuntu 21.10                 | 7         | 1.93%   |
| Ubuntu 20.10                 | 7         | 1.93%   |
| KDE neon 20.04               | 7         | 1.93%   |
| Ubuntu 19.10                 | 6         | 1.66%   |
| Manjaro                      | 6         | 1.66%   |
| Xubuntu 18.04                | 5         | 1.38%   |
| Ubuntu 21.04                 | 5         | 1.38%   |
| OpenMandriva 4.2             | 5         | 1.38%   |
| Fedora 35                    | 5         | 1.38%   |
| Ubuntu 18.10                 | 4         | 1.1%    |
| Ubuntu Budgie 20.04          | 3         | 0.83%   |
| Linux Mint 20.2              | 3         | 0.83%   |
| Linux Mint 19.3              | 3         | 0.83%   |
| Kubuntu 20.04                | 3         | 0.83%   |
| Kali 2021.2                  | 3         | 0.83%   |
| Fedora 31                    | 3         | 0.83%   |
| Debian 11                    | 3         | 0.83%   |
| ArcoLinux Rolling            | 3         | 0.83%   |
| Zorin 15                     | 2         | 0.55%   |
| Xubuntu 20.04                | 2         | 0.55%   |
| Ubuntu 17.10                 | 2         | 0.55%   |
| ROSA R11                     | 2         | 0.55%   |
| Pop!_OS 21.10                | 2         | 0.55%   |
| Pop!_OS 20.04                | 2         | 0.55%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.55%   |
| OpenMandriva 4.3             | 2         | 0.55%   |
| Manjaro 20.2.1               | 2         | 0.55%   |
| Manjaro 20.2                 | 2         | 0.55%   |
| Linux Mint 20.3              | 2         | 0.55%   |
| Kubuntu 19.10                | 2         | 0.55%   |
| KDE neon 18.04               | 2         | 0.55%   |
| Kali 2022.2                  | 2         | 0.55%   |
| Kali 2022.1                  | 2         | 0.55%   |
| Kali 2021.3                  | 2         | 0.55%   |
| Gentoo 2.6                   | 2         | 0.55%   |
| Fedora 36                    | 2         | 0.55%   |
| Endless 3.8.3-nexthw1        | 2         | 0.55%   |
| Endless 3.8.0                | 2         | 0.55%   |
| Endless 3.3.20-nexthw1       | 2         | 0.55%   |
| Endless 3.3.19               | 2         | 0.55%   |
| Debian 10                    | 2         | 0.55%   |
| Ubuntu MATE 18.04            | 1         | 0.28%   |
| Ubuntu 16.04                 | 1         | 0.28%   |
| Solus 4.0                    | 1         | 0.28%   |
| Sabayon                      | 1         | 0.28%   |
| ROSA R10                     | 1         | 0.28%   |
| PureOS 10.0                  | 1         | 0.28%   |
| Pop!_OS 22.04                | 1         | 0.28%   |
| Pop!_OS 21.04                | 1         | 0.28%   |
| Pop!_OS 20.10                | 1         | 0.28%   |
| openSUSE Leap-15.1           | 1         | 0.28%   |
| OpenMandriva 4.50            | 1         | 0.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 171       | 49.28%  |
| Fedora        | 31        | 8.93%   |
| Arch          | 21        | 6.05%   |
| Manjaro       | 17        | 4.9%    |
| Endless       | 14        | 4.03%   |
| Linux Mint    | 11        | 3.17%   |
| Kali          | 10        | 2.88%   |
| Kubuntu       | 9         | 2.59%   |
| KDE neon      | 9         | 2.59%   |
| OpenMandriva  | 8         | 2.31%   |
| Xubuntu       | 7         | 2.02%   |
| Pop!_OS       | 6         | 1.73%   |
| Debian        | 5         | 1.44%   |
| Ubuntu Budgie | 3         | 0.86%   |
| ROSA          | 3         | 0.86%   |
| openSUSE      | 3         | 0.86%   |
| ArcoLinux     | 3         | 0.86%   |
| Zorin         | 2         | 0.58%   |
| Gentoo        | 2         | 0.58%   |
| Elementary    | 2         | 0.58%   |
| Ubuntu MATE   | 1         | 0.29%   |
| Solus         | 1         | 0.29%   |
| Sabayon       | 1         | 0.29%   |
| PureOS        | 1         | 0.29%   |
| NixOS         | 1         | 0.29%   |
| Lubuntu       | 1         | 0.29%   |
| Linux Lite    | 1         | 0.29%   |
| Deepin        | 1         | 0.29%   |
| Clear Linux   | 1         | 0.29%   |
| CentOS        | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 3.14%   |
| 5.3.0-46-generic         | 7         | 1.83%   |
| 5.4.0-26-generic         | 6         | 1.57%   |
| 5.8.0-63-generic         | 5         | 1.31%   |
| 5.4.0-52-generic         | 5         | 1.31%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.31%   |
| 5.0.0-13-generic         | 5         | 1.31%   |
| 5.8.0-48-generic         | 4         | 1.05%   |
| 5.4.0-58-generic         | 4         | 1.05%   |
| 5.3.0-40-generic         | 4         | 1.05%   |
| 5.11.0-41-generic        | 4         | 1.05%   |
| 5.11.0-27-generic        | 4         | 1.05%   |
| 5.0.0-23-generic         | 4         | 1.05%   |
| 4.18.0-25-generic        | 4         | 1.05%   |
| 4.18.0-15-generic        | 4         | 1.05%   |
| 5.8.0-59-generic         | 3         | 0.79%   |
| 5.4.0-40-generic         | 3         | 0.79%   |
| 5.3.0-51-generic         | 3         | 0.79%   |
| 5.15.0-33-generic        | 3         | 0.79%   |
| 5.13.0-22-generic        | 3         | 0.79%   |
| 5.0.0-37-generic         | 3         | 0.79%   |
| 5.0.0-25-generic         | 3         | 0.79%   |
| 4.18.0-16-generic        | 3         | 0.79%   |
| 4.15.0-15-generic        | 3         | 0.79%   |
| 5.9.16-1-MANJARO         | 2         | 0.52%   |
| 5.8.18-1-MANJARO         | 2         | 0.52%   |
| 5.8.0-50-generic         | 2         | 0.52%   |
| 5.8.0-43-generic         | 2         | 0.52%   |
| 5.8.0-14-generic         | 2         | 0.52%   |
| 5.6.0-7-generic          | 2         | 0.52%   |
| 5.4.0-91-generic         | 2         | 0.52%   |
| 5.4.0-73-generic         | 2         | 0.52%   |
| 5.4.0-72-generic         | 2         | 0.52%   |
| 5.4.0-65-generic         | 2         | 0.52%   |
| 5.4.0-59-generic         | 2         | 0.52%   |
| 5.4.0-54-generic         | 2         | 0.52%   |
| 5.4.0-51-generic         | 2         | 0.52%   |
| 5.4.0-48-generic         | 2         | 0.52%   |
| 5.4.0-31-generic         | 2         | 0.52%   |
| 5.4.0-29-generic         | 2         | 0.52%   |
| 5.4.0-19-generic         | 2         | 0.52%   |
| 5.3.0-42-generic         | 2         | 0.52%   |
| 5.3.0-28-generic         | 2         | 0.52%   |
| 5.3.0-18-generic         | 2         | 0.52%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.52%   |
| 5.15.0-46-generic        | 2         | 0.52%   |
| 5.15.0-43-generic        | 2         | 0.52%   |
| 5.15.0-41-generic        | 2         | 0.52%   |
| 5.14.16-arch1-1          | 2         | 0.52%   |
| 5.13.19-2-MANJARO        | 2         | 0.52%   |
| 5.13.0-52-generic        | 2         | 0.52%   |
| 5.13.0-44-generic        | 2         | 0.52%   |
| 5.13.0-41-generic        | 2         | 0.52%   |
| 5.13.0-39-generic        | 2         | 0.52%   |
| 5.13.0-30-generic        | 2         | 0.52%   |
| 5.11.11-200.fc33.x86_64  | 2         | 0.52%   |
| 5.11.0-43-generic        | 2         | 0.52%   |
| 5.11.0-38-generic        | 2         | 0.52%   |
| 5.11.0-35-generic        | 2         | 0.52%   |
| 5.10.0-kali9-amd64       | 2         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 69        | 18.8%   |
| 5.0.0   | 26        | 7.08%   |
| 5.3.0   | 24        | 6.54%   |
| 5.8.0   | 23        | 6.27%   |
| 5.11.0  | 23        | 6.27%   |
| 4.15.0  | 23        | 6.27%   |
| 5.13.0  | 18        | 4.9%    |
| 4.18.0  | 18        | 4.9%    |
| 5.15.0  | 12        | 3.27%   |
| 5.10.0  | 8         | 2.18%   |
| 5.10.14 | 5         | 1.36%   |
| 5.11.11 | 4         | 1.09%   |
| 4.13.0  | 4         | 1.09%   |
| 5.9.16  | 3         | 0.82%   |
| 5.8.18  | 3         | 0.82%   |
| 5.6.0   | 3         | 0.82%   |
| 5.16.7  | 3         | 0.82%   |
| 5.16.15 | 3         | 0.82%   |
| 5.14.16 | 3         | 0.82%   |
| 5.13.19 | 3         | 0.82%   |
| 5.7.0   | 2         | 0.54%   |
| 5.16.0  | 2         | 0.54%   |
| 5.15.4  | 2         | 0.54%   |
| 5.13.7  | 2         | 0.54%   |
| 5.13.13 | 2         | 0.54%   |
| 5.12.8  | 2         | 0.54%   |
| 5.9.14  | 1         | 0.27%   |
| 5.9.11  | 1         | 0.27%   |
| 5.8.4   | 1         | 0.27%   |
| 5.8.16  | 1         | 0.27%   |
| 5.8.15  | 1         | 0.27%   |
| 5.8.14  | 1         | 0.27%   |
| 5.8.13  | 1         | 0.27%   |
| 5.7.6   | 1         | 0.27%   |
| 5.6.17  | 1         | 0.27%   |
| 5.6.14  | 1         | 0.27%   |
| 5.6.12  | 1         | 0.27%   |
| 5.6.10  | 1         | 0.27%   |
| 5.5.8   | 1         | 0.27%   |
| 5.5.13  | 1         | 0.27%   |
| 5.4.8   | 1         | 0.27%   |
| 5.4.28  | 1         | 0.27%   |
| 5.4.23  | 1         | 0.27%   |
| 5.4.2   | 1         | 0.27%   |
| 5.4.17  | 1         | 0.27%   |
| 5.4.12  | 1         | 0.27%   |
| 5.3.7   | 1         | 0.27%   |
| 5.2.2   | 1         | 0.27%   |
| 5.19.4  | 1         | 0.27%   |
| 5.18.2  | 1         | 0.27%   |
| 5.18.19 | 1         | 0.27%   |
| 5.18.12 | 1         | 0.27%   |
| 5.18.10 | 1         | 0.27%   |
| 5.18.1  | 1         | 0.27%   |
| 5.17.5  | 1         | 0.27%   |
| 5.17.0  | 1         | 0.27%   |
| 5.16.18 | 1         | 0.27%   |
| 5.16.14 | 1         | 0.27%   |
| 5.16.11 | 1         | 0.27%   |
| 5.16.1  | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 20.33%  |
| 5.8     | 31        | 8.52%   |
| 5.11    | 31        | 8.52%   |
| 5.0     | 28        | 7.69%   |
| 5.13    | 26        | 7.14%   |
| 5.3     | 25        | 6.87%   |
| 4.15    | 23        | 6.32%   |
| 5.10    | 22        | 6.04%   |
| 5.15    | 20        | 5.49%   |
| 4.18    | 18        | 4.95%   |
| 5.16    | 12        | 3.3%    |
| 5.14    | 10        | 2.75%   |
| 5.6     | 6         | 1.65%   |
| 5.12    | 6         | 1.65%   |
| 5.9     | 5         | 1.37%   |
| 5.18    | 5         | 1.37%   |
| 4.13    | 4         | 1.1%    |
| 5.7     | 3         | 0.82%   |
| 4.19    | 3         | 0.82%   |
| 5.5     | 2         | 0.55%   |
| 5.17    | 2         | 0.55%   |
| 5.2     | 1         | 0.27%   |
| 5.19    | 1         | 0.27%   |
| 4.9     | 1         | 0.27%   |
| 4.5     | 1         | 0.27%   |
| 4.20    | 1         | 0.27%   |
| 4.14    | 1         | 0.27%   |
| 4.12    | 1         | 0.27%   |
| 3.10    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 336       | 98.25%  |
| i686   | 6         | 1.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 180       | 51.28%  |
| Unknown         | 72        | 20.51%  |
| KDE5            | 28        | 7.98%   |
| XFCE            | 23        | 6.55%   |
| KDE             | 16        | 4.56%   |
| X-Cinnamon      | 7         | 1.99%   |
| MATE            | 5         | 1.42%   |
| i3              | 4         | 1.14%   |
| Unity           | 3         | 0.85%   |
| Budgie          | 3         | 0.85%   |
| Pantheon        | 2         | 0.57%   |
| LXQt            | 2         | 0.57%   |
| Trinity         | 1         | 0.28%   |
| sway            | 1         | 0.28%   |
| KDE4            | 1         | 0.28%   |
| GNOME Flashback | 1         | 0.28%   |
| Cinnamon        | 1         | 0.28%   |
| bspwm           | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 259       | 73.58%  |
| Unknown | 49        | 13.92%  |
| Wayland | 41        | 11.65%  |
| Tty     | 3         | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 212       | 59.55%  |
| GDM     | 60        | 16.85%  |
| SDDM    | 27        | 7.58%   |
| GDM3    | 24        | 6.74%   |
| LightDM | 19        | 5.34%   |
| TDM     | 10        | 2.81%   |
| Ly      | 2         | 0.56%   |
| XDM     | 1         | 0.28%   |
| KDM     | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 253       | 72.7%   |
| Unknown | 69        | 19.83%  |
| en_GB   | 7         | 2.01%   |
| fa_IR   | 6         | 1.72%   |
| C       | 5         | 1.44%   |
| en_CA   | 3         | 0.86%   |
| POSIX   | 1         | 0.29%   |
| ja_JP   | 1         | 0.29%   |
| en_AG   | 1         | 0.29%   |
| de_DE   | 1         | 0.29%   |
| az_IR   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 195       | 55.4%   |
| EFI  | 157       | 44.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 279       | 80.64%  |
| Btrfs   | 27        | 7.8%    |
| Overlay | 15        | 4.34%   |
| Unknown | 14        | 4.05%   |
| Zfs     | 5         | 1.45%   |
| Xfs     | 4         | 1.16%   |
| Ext3    | 1         | 0.29%   |
| Ext2    | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 230       | 66.67%  |
| GPT     | 86        | 24.93%  |
| MBR     | 29        | 8.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 296       | 85.55%  |
| Yes       | 50        | 14.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 186       | 54.23%  |
| Yes       | 157       | 45.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 102       | 29.82%  |
| Lenovo           | 88        | 25.73%  |
| Hewlett-Packard  | 47        | 13.74%  |
| Dell             | 36        | 10.53%  |
| Acer             | 34        | 9.94%   |
| MSI              | 11        | 3.22%   |
| Sony             | 10        | 2.92%   |
| Toshiba          | 3         | 0.88%   |
| Fujitsu          | 3         | 0.88%   |
| Apple            | 2         | 0.58%   |
| Timi             | 1         | 0.29%   |
| Razer            | 1         | 0.29%   |
| Packard Bell     | 1         | 0.29%   |
| LG Electronics   | 1         | 0.29%   |
| Alienware        | 1         | 0.29%   |
| Unknown          | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo IdeaPad 330-15IKB 81DE                         | 6         | 1.75%   |
| HP ProBook 4540s                                      | 6         | 1.75%   |
| Acer Aspire V3-571G                                   | 5         | 1.46%   |
| Lenovo IdeaPad Z510 20287                             | 4         | 1.17%   |
| HP Pavilion g6                                        | 3         | 0.88%   |
| HP EliteBook 840 G2                                   | 3         | 0.88%   |
| ASUS X580VD                                           | 3         | 0.88%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR                  | 3         | 0.88%   |
| MSI Prestige 14 A10RB                                 | 2         | 0.58%   |
| Lenovo Z50-70 20354                                   | 2         | 0.58%   |
| Lenovo ThinkPad X250 20CM002XUS                       | 2         | 0.58%   |
| Lenovo Legion 5 15ARH05H 82B1                         | 2         | 0.58%   |
| Lenovo IdeaPad S540-15IWL GTX 81SW                    | 2         | 0.58%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                 | 2         | 0.58%   |
| Lenovo IdeaPad 520-15IKB 81BF                         | 2         | 0.58%   |
| Lenovo IdeaPad 5 15ITL05 82FG                         | 2         | 0.58%   |
| Lenovo IdeaPad 5 14ALC05 82LM                         | 2         | 0.58%   |
| Lenovo G50-80 80E5                                    | 2         | 0.58%   |
| Lenovo G50-70 20351                                   | 2         | 0.58%   |
| Lenovo Flex 2-15 20405                                | 2         | 0.58%   |
| HP ProBook 450 G4                                     | 2         | 0.58%   |
| HP Pavilion dv6                                       | 2         | 0.58%   |
| HP Laptop 15-bs0xx                                    | 2         | 0.58%   |
| HP EliteBook 8470p                                    | 2         | 0.58%   |
| Dell Vostro 1510                                      | 2         | 0.58%   |
| Dell Vostro 1015                                      | 2         | 0.58%   |
| Dell Latitude E7470                                   | 2         | 0.58%   |
| Dell Latitude E6530                                   | 2         | 0.58%   |
| Dell Inspiron N5110                                   | 2         | 0.58%   |
| ASUS X550IU                                           | 2         | 0.58%   |
| ASUS X542UN                                           | 2         | 0.58%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD                | 2         | 0.58%   |
| ASUS VivoBook_ASUSLaptop X571GT_K571GT                | 2         | 0.58%   |
| ASUS VivoBook_ASUSLaptop X521EQ_S533EQ                | 2         | 0.58%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ                | 2         | 0.58%   |
| ASUS VivoBook 15_ASUS Laptop X540MB_X540MB            | 2         | 0.58%   |
| ASUS VivoBook 15 ASUS Laptop X570UD                   | 2         | 0.58%   |
| ASUS N501VW                                           | 2         | 0.58%   |
| ASUS K55VD                                            | 2         | 0.58%   |
| Acer TravelMate P446-M                                | 2         | 0.58%   |
| Acer Aspire F5-573G                                   | 2         | 0.58%   |
| Acer Aspire A715-71G                                  | 2         | 0.58%   |
| Toshiba Satellite Pro T130                            | 1         | 0.29%   |
| Toshiba Satellite L655                                | 1         | 0.29%   |
| Toshiba PORTEGE R930                                  | 1         | 0.29%   |
| Timi RedmiBook 14                                     | 1         | 0.29%   |
| Sony VPCZ126GG                                        | 1         | 0.29%   |
| Sony VPCSB36FG                                        | 1         | 0.29%   |
| Sony VPCSB19GG                                        | 1         | 0.29%   |
| Sony VPCSA25GX                                        | 1         | 0.29%   |
| Sony VPCEH36EG                                        | 1         | 0.29%   |
| Sony VPCEH11FX                                        | 1         | 0.29%   |
| Sony VPCEB1SFX                                        | 1         | 0.29%   |
| Sony VGN-SR165E                                       | 1         | 0.29%   |
| Sony VGN-CS38GD_B                                     | 1         | 0.29%   |
| Sony SVF15N12SGB                                      | 1         | 0.29%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.29%   |
| Packard Bell EasyNote TK85                            | 1         | 0.29%   |
| MSI MS-1454                                           | 1         | 0.29%   |
| MSI Modern 14 A10M                                    | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 35        | 10.23%  |
| Acer Aspire           | 29        | 8.48%   |
| Lenovo ThinkPad       | 26        | 7.6%    |
| ASUS VivoBook         | 25        | 7.31%   |
| HP EliteBook          | 17        | 4.97%   |
| Dell Inspiron         | 14        | 4.09%   |
| HP ProBook            | 13        | 3.8%    |
| Dell Latitude         | 11        | 3.22%   |
| HP Pavilion           | 8         | 2.34%   |
| Dell Vostro           | 8         | 2.34%   |
| ASUS ASUS             | 6         | 1.75%   |
| Lenovo Legion         | 3         | 0.88%   |
| Fujitsu LIFEBOOK      | 3         | 0.88%   |
| ASUS X580VD           | 3         | 0.88%   |
| ASUS ROG              | 3         | 0.88%   |
| Acer TravelMate       | 3         | 0.88%   |
| Toshiba Satellite     | 2         | 0.58%   |
| MSI Prestige          | 2         | 0.58%   |
| MSI GE60              | 2         | 0.58%   |
| Lenovo Z50-70         | 2         | 0.58%   |
| Lenovo ThinkBook      | 2         | 0.58%   |
| Lenovo G580           | 2         | 0.58%   |
| Lenovo G50-80         | 2         | 0.58%   |
| Lenovo G50-70         | 2         | 0.58%   |
| Lenovo Flex           | 2         | 0.58%   |
| HP ZBook              | 2         | 0.58%   |
| HP Laptop             | 2         | 0.58%   |
| ASUS X550IU           | 2         | 0.58%   |
| ASUS X542UN           | 2         | 0.58%   |
| ASUS N501VW           | 2         | 0.58%   |
| ASUS K55VD            | 2         | 0.58%   |
| Toshiba PORTEGE       | 1         | 0.29%   |
| Timi RedmiBook        | 1         | 0.29%   |
| Sony VPCZ126GG        | 1         | 0.29%   |
| Sony VPCSB36FG        | 1         | 0.29%   |
| Sony VPCSB19GG        | 1         | 0.29%   |
| Sony VPCSA25GX        | 1         | 0.29%   |
| Sony VPCEH36EG        | 1         | 0.29%   |
| Sony VPCEH11FX        | 1         | 0.29%   |
| Sony VPCEB1SFX        | 1         | 0.29%   |
| Sony VGN-SR165E       | 1         | 0.29%   |
| Sony VGN-CS38GD       | 1         | 0.29%   |
| Sony SVF15N12SGB      | 1         | 0.29%   |
| Razer Blade           | 1         | 0.29%   |
| Packard Bell EasyNote | 1         | 0.29%   |
| MSI MS-1454           | 1         | 0.29%   |
| MSI Modern            | 1         | 0.29%   |
| MSI Katana            | 1         | 0.29%   |
| MSI GF63              | 1         | 0.29%   |
| MSI GE620             | 1         | 0.29%   |
| MSI CX62              | 1         | 0.29%   |
| MSI CR610M            | 1         | 0.29%   |
| LG RD590-K.ADJCRE6    | 1         | 0.29%   |
| Lenovo Z50-75         | 1         | 0.29%   |
| Lenovo V580c          | 1         | 0.29%   |
| Lenovo V330-15IKB     | 1         | 0.29%   |
| Lenovo V310-15IKB     | 1         | 0.29%   |
| Lenovo G510           | 1         | 0.29%   |
| Lenovo G505           | 1         | 0.29%   |
| Lenovo G500           | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 36        | 10.53%  |
| 2013 | 35        | 10.23%  |
| 2012 | 34        | 9.94%   |
| 2019 | 31        | 9.06%   |
| 2010 | 31        | 9.06%   |
| 2018 | 26        | 7.6%    |
| 2015 | 26        | 7.6%    |
| 2016 | 24        | 7.02%   |
| 2011 | 24        | 7.02%   |
| 2020 | 21        | 6.14%   |
| 2014 | 20        | 5.85%   |
| 2021 | 11        | 3.22%   |
| 2009 | 10        | 2.92%   |
| 2008 | 7         | 2.05%   |
| 2022 | 2         | 0.58%   |
| 2007 | 2         | 0.58%   |
| 2006 | 2         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 342       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 322       | 94.15%  |
| Enabled  | 20        | 5.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 342       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 120       | 34.88%  |
| 3.01-4.0   | 74        | 21.51%  |
| 8.01-16.0  | 71        | 20.64%  |
| 16.01-24.0 | 53        | 15.41%  |
| 1.01-2.0   | 9         | 2.62%   |
| 32.01-64.0 | 8         | 2.33%   |
| 2.01-3.0   | 4         | 1.16%   |
| 0.51-1.0   | 3         | 0.87%   |
| 24.01-32.0 | 2         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 126       | 34.15%  |
| 2.01-3.0   | 111       | 30.08%  |
| 3.01-4.0   | 61        | 16.53%  |
| 4.01-8.0   | 43        | 11.65%  |
| 0.51-1.0   | 18        | 4.88%   |
| 8.01-16.0  | 8         | 2.17%   |
| 16.01-24.0 | 1         | 0.27%   |
| 0.01-0.5   | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 243       | 69.83%  |
| 2      | 96        | 27.59%  |
| 3      | 7         | 2.01%   |
| 0      | 2         | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 175       | 50.87%  |
| Yes       | 169       | 49.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 85.67%  |
| No        | 49        | 14.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 338       | 98.83%  |
| No        | 4         | 1.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 278       | 80.81%  |
| No        | 66        | 19.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Iran    | 342       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Tehran                         | 198       | 55.31%  |
| TehrДЃn                      | 34        | 9.5%    |
| Mashhad                        | 20        | 5.59%   |
| Isfahan                        | 11        | 3.07%   |
| Khorramshahr                   | 6         | 1.68%   |
| Tajrīsh                       | 5         | 1.4%    |
| Tabriz                         | 5         | 1.4%    |
| Rasht                          | 5         | 1.4%    |
| Qom                            | 4         | 1.12%   |
| Karaj                          | 4         | 1.12%   |
| Babol                          | 4         | 1.12%   |
| TajrД«sh                     | 3         | 0.84%   |
| Zanjan                         | 2         | 0.56%   |
| Yazd                           | 2         | 0.56%   |
| Shiraz                         | 2         | 0.56%   |
| Shahre Jadide Andisheh         | 2         | 0.56%   |
| Shahr-e Qods                   | 2         | 0.56%   |
| Sanandij                       | 2         | 0.56%   |
| Qazvin                         | 2         | 0.56%   |
| Kerman                         | 2         | 0.56%   |
| Gorgan                         | 2         | 0.56%   |
| ДЂstДЃneh-ye AshrafД«yeh | 1         | 0.28%   |
| Şowmeeh Sarā                 | 1         | 0.28%   |
| ShДЃhД«n Shahr             | 1         | 0.28%   |
| Shirvan                        | 1         | 0.28%   |
| ShahrД«ДЃr                 | 1         | 0.28%   |
| Shahr-e Kord                   | 1         | 0.28%   |
| SemÄ«rom                     | 1         | 0.28%   |
| SalmДЃs                      | 1         | 0.28%   |
| Rūdsar                        | 1         | 0.28%   |
| Robat Karim                    | 1         | 0.28%   |
| Rey                            | 1         | 0.28%   |
| RÅ«dÄn                    | 1         | 0.28%   |
| RafsanjДЃn                   | 1         | 0.28%   |
| Qaleh Ganj                     | 1         | 0.28%   |
| NashtДЃrЕ«d                | 1         | 0.28%   |
| NajafДЃbДЃd                | 1         | 0.28%   |
| MДЃmЕ«nД«yeh             | 1         | 0.28%   |
| MД«ДЃneh                   | 1         | 0.28%   |
| Maragheh                       | 1         | 0.28%   |
| MalДЃrd                      | 1         | 0.28%   |
| Langarūd                      | 1         | 0.28%   |
| KahrÄ«z                      | 1         | 0.28%   |
| FÄ«rÅ«zkÅ«h              | 1         | 0.28%   |
| FÄmenÄ«n                  | 1         | 0.28%   |
| DДЃmghДЃn                  | 1         | 0.28%   |
| DamДЃvand                    | 1         | 0.28%   |
| DamÄvand                    | 1         | 0.28%   |
| BЕ«kДЃn                    | 1         | 0.28%   |
| BorЕ«jerd                    | 1         | 0.28%   |
| Borazjan                       | 1         | 0.28%   |
| Birjand                        | 1         | 0.28%   |
| Behshahr                       | 1         | 0.28%   |
| Bandar-e Lengeh                | 1         | 0.28%   |
| Bandar-e Asalūyeh             | 1         | 0.28%   |
| Bandar Abbas                   | 1         | 0.28%   |
| BajestДЃn                    | 1         | 0.28%   |
| BahДЃr                       | 1         | 0.28%   |
| AsadÄbÄd                 | 1         | 0.28%   |
| Arak                           | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 85        | 102    | 19.63%  |
| WDC                       | 81        | 94     | 18.71%  |
| Toshiba                   | 66        | 76     | 15.24%  |
| Samsung Electronics       | 54        | 60     | 12.47%  |
| HGST                      | 18        | 22     | 4.16%   |
| SanDisk                   | 16        | 20     | 3.7%    |
| A-DATA Technology         | 16        | 21     | 3.7%    |
| Micron Technology         | 15        | 17     | 3.46%   |
| Intel                     | 10        | 10     | 2.31%   |
| Unknown                   | 9         | 10     | 2.08%   |
| SK hynix                  | 7         | 8      | 1.62%   |
| Lexar                     | 6         | 6      | 1.39%   |
| Kingston                  | 6         | 8      | 1.39%   |
| Hitachi                   | 6         | 6      | 1.39%   |
| Plextor                   | 3         | 3      | 0.69%   |
| Apacer                    | 3         | 3      | 0.69%   |
| LITEON                    | 2         | 3      | 0.46%   |
| Kingmax                   | 2         | 2      | 0.46%   |
| Gigabyte Technology       | 2         | 2      | 0.46%   |
| Biostar                   | 2         | 3      | 0.46%   |
| Apple                     | 2         | 2      | 0.46%   |
| XPG                       | 1         | 1      | 0.23%   |
| VC-500                    | 1         | 1      | 0.23%   |
| ValueTech                 | 1         | 2      | 0.23%   |
| USB3.0                    | 1         | 1      | 0.23%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.23%   |
| Union Memory              | 1         | 1      | 0.23%   |
| UMIS                      | 1         | 1      | 0.23%   |
| Transcend                 | 1         | 1      | 0.23%   |
| SPCC                      | 1         | 1      | 0.23%   |
| Silicon Motion            | 1         | 1      | 0.23%   |
| PNY                       | 1         | 1      | 0.23%   |
| Phison                    | 1         | 1      | 0.23%   |
| OCZ                       | 1         | 1      | 0.23%   |
| Micron/Crucial Technology | 1         | 1      | 0.23%   |
| Mass                      | 1         | 2      | 0.23%   |
| LITEONIT                  | 1         | 2      | 0.23%   |
| KODAK                     | 1         | 1      | 0.23%   |
| KingFast                  | 1         | 1      | 0.23%   |
| GeIL                      | 1         | 1      | 0.23%   |
| Fujitsu                   | 1         | 1      | 0.23%   |
| Crucial                   | 1         | 1      | 0.23%   |
| China                     | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 32        | 7.31%   |
| Toshiba MQ01ABD100 1TB                  | 16        | 3.65%   |
| Toshiba MQ04ABF100 1TB                  | 12        | 2.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 10        | 2.28%   |
| Seagate ST9500325AS 500GB               | 9         | 2.05%   |
| WDC WD10SPZX-24Z10 1TB                  | 8         | 1.83%   |
| WDC WD10SPZX-08Z10 1TB                  | 7         | 1.6%    |
| WDC WD10JPCX-24UE4T0 1TB                | 7         | 1.6%    |
| Toshiba MQ01ABF050 500GB                | 7         | 1.6%    |
| Samsung SSD 860 EVO 500GB               | 7         | 1.6%    |
| Samsung SSD 860 EVO 250GB               | 6         | 1.37%   |
| A-DATA SU650 120GB SSD                  | 5         | 1.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 4         | 0.91%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 4         | 0.91%   |
| Toshiba MQ01ABD050V 500GB               | 4         | 0.91%   |
| Seagate ST2000LM007-1R8174 2TB          | 4         | 0.91%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 4         | 0.91%   |
| Intel NVMe SSD Drive 512GB              | 4         | 0.91%   |
| HGST HTS721010A9E630 1TB                | 4         | 0.91%   |
| HGST HTS541010B7E610 1TB                | 4         | 0.91%   |
| HGST HTS541010A9E680 1TB                | 4         | 0.91%   |
| WDC WD10SPZX-80Z10T2 1TB                | 3         | 0.68%   |
| Unknown MMC Card  32GB                  | 3         | 0.68%   |
| Toshiba MQ01ABD075 752GB                | 3         | 0.68%   |
| Toshiba MQ01ABD050 500GB                | 3         | 0.68%   |
| Seagate ST9500420AS 500GB               | 3         | 0.68%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 0.68%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.68%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 3         | 0.68%   |
| Micron 2210_MTFDHBA512QFD 512GB         | 3         | 0.68%   |
| Lexar 128GB SSD                         | 3         | 0.68%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 2         | 0.46%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD        | 2         | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 2         | 0.46%   |
| WDC WD5000LPVX-80V0TT0 500GB            | 2         | 0.46%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 2         | 0.46%   |
| WDC WD10SPZX-75Z10T0 1TB                | 2         | 0.46%   |
| WDC WD10SPCX-08S8TT0 1TB                | 2         | 0.46%   |
| WDC WD10JPVX-08JC3T5 1TB                | 2         | 0.46%   |
| WDC WD10JPVX-00JC3T0 1TB                | 2         | 0.46%   |
| Toshiba THNSNC128GMMJ 128GB SSD         | 2         | 0.46%   |
| Toshiba MK7559GSXP 752GB                | 2         | 0.46%   |
| SK hynix NVMe SSD Drive 256GB           | 2         | 0.46%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD   | 2         | 0.46%   |
| Seagate ST95005620AS 500GB              | 2         | 0.46%   |
| Seagate ST9250315AS 250GB               | 2         | 0.46%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 0.46%   |
| Seagate ST320LT020-9YG142 320GB         | 2         | 0.46%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 2         | 0.46%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 0.46%   |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 0.46%   |
| SanDisk SSD U110 16GB                   | 2         | 0.46%   |
| SanDisk SD8SNAT128G1002 128GB SSD       | 2         | 0.46%   |
| Samsung SSD 870 EVO 500GB               | 2         | 0.46%   |
| Samsung NVMe SSD Drive 512GB            | 2         | 0.46%   |
| Samsung MZVLQ512HALU-00000 512GB        | 2         | 0.46%   |
| Samsung MZVLQ1T0HBLB-00B00 1TB          | 2         | 0.46%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD    | 2         | 0.46%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD     | 2         | 0.46%   |
| Lexar 512GB SSD                         | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 102    | 35.42%  |
| WDC                 | 66        | 73     | 27.5%   |
| Toshiba             | 60        | 66     | 25%     |
| HGST                | 18        | 22     | 7.5%    |
| Hitachi             | 6         | 6      | 2.5%    |
| USB3.0              | 1         | 1      | 0.42%   |
| Unknown             | 1         | 1      | 0.42%   |
| Samsung Electronics | 1         | 1      | 0.42%   |
| Fujitsu             | 1         | 1      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 42     | 27.82%  |
| A-DATA Technology   | 16        | 21     | 12.03%  |
| WDC                 | 15        | 18     | 11.28%  |
| SanDisk             | 13        | 16     | 9.77%   |
| Micron Technology   | 8         | 8      | 6.02%   |
| Lexar               | 6         | 6      | 4.51%   |
| Toshiba             | 4         | 8      | 3.01%   |
| SK hynix            | 4         | 4      | 3.01%   |
| Kingston            | 4         | 5      | 3.01%   |
| Plextor             | 3         | 3      | 2.26%   |
| Intel               | 3         | 3      | 2.26%   |
| Apacer              | 3         | 3      | 2.26%   |
| LITEON              | 2         | 3      | 1.5%    |
| Gigabyte Technology | 2         | 2      | 1.5%    |
| Biostar             | 2         | 3      | 1.5%    |
| ValueTech           | 1         | 2      | 0.75%   |
| Transcend           | 1         | 1      | 0.75%   |
| SPCC                | 1         | 1      | 0.75%   |
| PNY                 | 1         | 1      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 2      | 0.75%   |
| KODAK               | 1         | 1      | 0.75%   |
| GeIL                | 1         | 1      | 0.75%   |
| Crucial             | 1         | 1      | 0.75%   |
| China               | 1         | 1      | 0.75%   |
| Apple               | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 238       | 274    | 55.61%  |
| SSD     | 130       | 158    | 30.37%  |
| NVMe    | 50        | 59     | 11.68%  |
| MMC     | 6         | 7      | 1.4%    |
| Unknown | 4         | 5      | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 311       | 430    | 83.6%   |
| NVMe | 50        | 59     | 13.44%  |
| MMC  | 6         | 7      | 1.61%   |
| SAS  | 5         | 7      | 1.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 193       | 242    | 54.83%  |
| 0.51-1.0   | 151       | 181    | 42.9%   |
| 1.01-2.0   | 8         | 9      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 100       | 28.25%  |
| 251-500        | 69        | 19.49%  |
| 501-1000       | 67        | 18.93%  |
| 51-100         | 33        | 9.32%   |
| 1001-2000      | 31        | 8.76%   |
| 1-20           | 24        | 6.78%   |
| 21-50          | 18        | 5.08%   |
| Unknown        | 9         | 2.54%   |
| More than 3000 | 2         | 0.56%   |
| 2001-3000      | 1         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 131       | 36.09%  |
| 21-50          | 60        | 16.53%  |
| 51-100         | 49        | 13.5%   |
| 101-250        | 46        | 12.67%  |
| 501-1000       | 33        | 9.09%   |
| 251-500        | 31        | 8.54%   |
| Unknown        | 9         | 2.48%   |
| 1001-2000      | 2         | 0.55%   |
| More than 3000 | 1         | 0.28%   |
| 2001-3000      | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 7.14%   |
| Toshiba MQ01ABD050 500GB                       | 2         | 2      | 7.14%   |
| Seagate ST9500325AS 500GB                      | 2         | 2      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB                 | 2         | 2      | 7.14%   |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1         | 1      | 3.57%   |
| WDC WD5000LPVX-80V0TT0 500GB                   | 1         | 1      | 3.57%   |
| WDC WD3200BPVT-75ZEST0 320GB                   | 1         | 1      | 3.57%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 3.57%   |
| WDC WD10SPZX-08Z10 1TB                         | 1         | 1      | 3.57%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 1         | 1      | 3.57%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 3.57%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 3.57%   |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 3.57%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 3.57%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 3.57%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 1      | 3.57%   |
| Seagate ST1000LM014-SSHD-8GB                   | 1         | 1      | 3.57%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 3.57%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 3.57%   |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 3.57%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 3.57%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 3.57%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 8         | 8      | 28.57%  |
| Seagate           | 8         | 8      | 28.57%  |
| WDC               | 6         | 6      | 21.43%  |
| Hitachi           | 3         | 3      | 10.71%  |
| HGST              | 2         | 2      | 7.14%   |
| Micron Technology | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 8      | 30.77%  |
| Seagate | 8         | 8      | 30.77%  |
| WDC     | 5         | 5      | 19.23%  |
| Hitachi | 3         | 3      | 11.54%  |
| HGST    | 2         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 26     | 92.59%  |
| SSD  | 2         | 2      | 7.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 234       | 341    | 65.73%  |
| Works    | 95        | 133    | 26.69%  |
| Malfunc  | 26        | 28     | 7.3%    |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 301       | 80.05%  |
| AMD                          | 27        | 7.18%   |
| Samsung Electronics          | 17        | 4.52%   |
| Micron Technology            | 7         | 1.86%   |
| SanDisk                      | 6         | 1.6%    |
| Union Memory (Shenzhen)      | 4         | 1.06%   |
| SK hynix                     | 3         | 0.8%    |
| Phison Electronics           | 3         | 0.8%    |
| Toshiba America Info Systems | 2         | 0.53%   |
| Kingston Technology Company  | 2         | 0.53%   |
| Silicon Motion               | 1         | 0.27%   |
| Nvidia                       | 1         | 0.27%   |
| Micron/Crucial Technology    | 1         | 0.27%   |
| ADATA Technology             | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 48        | 12.15%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 32        | 8.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 29        | 7.34%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 27        | 6.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 21        | 5.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 21        | 5.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 19        | 4.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 18        | 4.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 18        | 4.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 15        | 3.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 11        | 2.78%   |
| Samsung NVMe SSD Controller 980                                                        | 10        | 2.53%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 9         | 2.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 8         | 2.03%   |
| Micron Non-Volatile memory controller                                                  | 7         | 1.77%   |
| Intel SSD 660P Series                                                                  | 7         | 1.77%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 6         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 1.27%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 4         | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 4         | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 4         | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 1.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 3         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 0.76%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.51%   |
| SanDisk Non-Volatile memory controller                                                 | 2         | 0.51%   |
| Phison PS5013 E13 NVMe Controller                                                      | 2         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 0.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.51%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.25%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 0.25%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.25%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.25%   |
| Samsung Electronics SATA controller                                                    | 1         | 0.25%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.25%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.25%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.25%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.25%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.25%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.25%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 0.25%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 0.25%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.25%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.25%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 283       | 73.7%   |
| NVMe | 50        | 13.02%  |
| RAID | 38        | 9.9%    |
| IDE  | 13        | 3.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 313       | 91.52%  |
| AMD    | 29        | 8.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 20        | 5.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 14        | 4.09%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 2.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 2.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 9         | 2.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 2.34%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 2.34%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 2.05%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 7         | 2.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 2.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 1.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.46%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 1.46%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 5         | 1.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 1.46%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.46%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 4         | 1.17%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 1.17%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 1.17%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 1.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.17%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 4         | 1.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.88%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 3         | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.88%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.88%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.88%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 0.88%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz          | 3         | 0.88%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.88%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.88%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.88%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.58%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.58%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.58%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.58%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.58%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.58%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.58%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 2         | 0.58%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.58%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.58%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.58%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 2         | 0.58%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 2         | 0.58%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.58%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.58%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 0.58%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 0.58%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.58%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.58%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 130       | 38.01%  |
| Intel Core i5           | 106       | 30.99%  |
| Intel Core i3           | 19        | 5.56%   |
| Other                   | 15        | 4.39%   |
| Intel Core 2 Duo        | 13        | 3.8%    |
| Intel Pentium           | 10        | 2.92%   |
| Intel Celeron           | 7         | 2.05%   |
| AMD Ryzen 7             | 7         | 2.05%   |
| Intel Atom              | 5         | 1.46%   |
| AMD FX                  | 4         | 1.17%   |
| Intel Pentium Dual-Core | 3         | 0.88%   |
| Intel Genuine           | 3         | 0.88%   |
| AMD Ryzen 3             | 3         | 0.88%   |
| AMD A4                  | 3         | 0.88%   |
| AMD A10                 | 3         | 0.88%   |
| Intel Pentium Silver    | 2         | 0.58%   |
| AMD E1                  | 2         | 0.58%   |
| Intel Core M            | 1         | 0.29%   |
| AMD Ryzen 9             | 1         | 0.29%   |
| AMD Ryzen 5             | 1         | 0.29%   |
| AMD PRO A8              | 1         | 0.29%   |
| AMD PRO A10             | 1         | 0.29%   |
| AMD E2                  | 1         | 0.29%   |
| AMD A6                  | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 196       | 57.31%  |
| 4      | 118       | 34.5%   |
| 8      | 12        | 3.51%   |
| 6      | 11        | 3.22%   |
| 1      | 3         | 0.88%   |
| 14     | 2         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 342       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 294       | 85.96%  |
| 1      | 48        | 14.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 331       | 96.5%   |
| Unknown        | 9         | 2.62%   |
| 32-bit         | 3         | 0.87%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 16.67%  |
| 0x306a9    | 32        | 9.04%   |
| 0x806ea    | 25        | 7.06%   |
| 0x306d4    | 22        | 6.21%   |
| 0x206a7    | 20        | 5.65%   |
| 0x20655    | 19        | 5.37%   |
| 0x306c3    | 16        | 4.52%   |
| 0x806e9    | 15        | 4.24%   |
| 0x806ec    | 13        | 3.67%   |
| 0x906e9    | 11        | 3.11%   |
| 0x40651    | 11        | 3.11%   |
| 0x1067a    | 10        | 2.82%   |
| 0x906ea    | 9         | 2.54%   |
| 0x406e3    | 9         | 2.54%   |
| 0x506e3    | 7         | 1.98%   |
| 0x806c1    | 6         | 1.69%   |
| 0x20652    | 6         | 1.69%   |
| 0xa0652    | 5         | 1.41%   |
| 0x106e5    | 5         | 1.41%   |
| 0x706e5    | 4         | 1.13%   |
| 0x706a1    | 4         | 1.13%   |
| 0x806d1    | 3         | 0.85%   |
| 0x6fd      | 3         | 0.85%   |
| 0x106ca    | 3         | 0.85%   |
| 0x0700010f | 3         | 0.85%   |
| 0x0600611a | 3         | 0.85%   |
| 0x906a3    | 2         | 0.56%   |
| 0x6e8      | 2         | 0.56%   |
| 0x30678    | 2         | 0.56%   |
| 0x10676    | 2         | 0.56%   |
| 0x08600104 | 2         | 0.56%   |
| 0x08108109 | 2         | 0.56%   |
| 0x06003109 | 2         | 0.56%   |
| 0x06003106 | 2         | 0.56%   |
| 0x806eb    | 1         | 0.28%   |
| 0x6fb      | 1         | 0.28%   |
| 0x6fa      | 1         | 0.28%   |
| 0x506c9    | 1         | 0.28%   |
| 0x406c4    | 1         | 0.28%   |
| 0x406c3    | 1         | 0.28%   |
| 0x30661    | 1         | 0.28%   |
| 0x0a50000c | 1         | 0.28%   |
| 0x08608103 | 1         | 0.28%   |
| 0x08608102 | 1         | 0.28%   |
| 0x08108102 | 1         | 0.28%   |
| 0x07030105 | 1         | 0.28%   |
| 0x06006705 | 1         | 0.28%   |
| 0x05000119 | 1         | 0.28%   |
| 0x03000027 | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 86        | 25.15%  |
| IvyBridge        | 37        | 10.82%  |
| Haswell          | 37        | 10.82%  |
| Westmere         | 27        | 7.89%   |
| Broadwell        | 22        | 6.43%   |
| SandyBridge      | 21        | 6.14%   |
| Skylake          | 19        | 5.56%   |
| Penryn           | 12        | 3.51%   |
| TigerLake        | 8         | 2.34%   |
| Icelake          | 7         | 2.05%   |
| Excavator        | 7         | 2.05%   |
| Goldmont plus    | 6         | 1.75%   |
| CometLake        | 6         | 1.75%   |
| Nehalem          | 5         | 1.46%   |
| Core             | 5         | 1.46%   |
| Zen+             | 4         | 1.17%   |
| Steamroller      | 4         | 1.17%   |
| Silvermont       | 4         | 1.17%   |
| Bonnell          | 4         | 1.17%   |
| Unknown          | 4         | 1.17%   |
| Zen 2            | 3         | 0.88%   |
| Jaguar           | 3         | 0.88%   |
| Zen 3            | 2         | 0.58%   |
| P6               | 2         | 0.58%   |
| Goldmont         | 2         | 0.58%   |
| Alderlake Hybrid | 2         | 0.58%   |
| Puma             | 1         | 0.29%   |
| K10 Llano        | 1         | 0.29%   |
| Bobcat           | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 281       | 50.81%  |
| Nvidia           | 179       | 32.37%  |
| AMD              | 92        | 16.64%  |
| ATI Technologies | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 34        | 6.04%   |
| Intel UHD Graphics 620                                                                | 28        | 4.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 21        | 3.73%   |
| Intel HD Graphics 5500                                                                | 20        | 3.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 19        | 3.37%   |
| Intel HD Graphics 620                                                                 | 18        | 3.2%    |
| Intel Core Processor Integrated Graphics Controller                                   | 16        | 2.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 15        | 2.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 15        | 2.66%   |
| Intel HD Graphics 630                                                                 | 13        | 2.31%   |
| Nvidia GP108M [GeForce MX150]                                                         | 12        | 2.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 11        | 1.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 10        | 1.78%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 9         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 9         | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 9         | 1.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 1.6%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 1.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 8         | 1.42%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 8         | 1.42%   |
| Nvidia GM108M [GeForce MX110]                                                         | 7         | 1.24%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 7         | 1.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 1.24%   |
| Intel HD Graphics 530                                                                 | 7         | 1.24%   |
| Nvidia GM108M [GeForce 840M]                                                          | 6         | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 6         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 0.89%   |
| Nvidia GP107M [GeForce MX350]                                                         | 5         | 0.89%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 5         | 0.89%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 5         | 0.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 5         | 0.89%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 5         | 0.89%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 5         | 0.89%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 0.71%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                     | 4         | 0.71%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 0.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 0.71%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                          | 4         | 0.71%   |
| Nvidia TU117M [GeForce MX450]                                                         | 3         | 0.53%   |
| Nvidia TU117M                                                                         | 3         | 0.53%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.53%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 3         | 0.53%   |
| Nvidia GM107 [GeForce 940MX]                                                          | 3         | 0.53%   |
| Nvidia GK107M [GeForce GT 750M]                                                       | 3         | 0.53%   |
| Nvidia GF119M [GeForce 610M]                                                          | 3         | 0.53%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 0.53%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 3         | 0.53%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller               | 3         | 0.53%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 3         | 0.53%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 3         | 0.53%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 3         | 0.53%   |
| AMD Renoir                                                                            | 3         | 0.53%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 3         | 0.53%   |
| AMD Opal PRO [Radeon R7 M260X]                                                        | 3         | 0.53%   |
| AMD Lucienne                                                                          | 3         | 0.53%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                                    | 3         | 0.53%   |
| Nvidia GT218M [GeForce 310M]                                                          | 2         | 0.36%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 2         | 0.36%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 154       | 45.03%  |
| 1 x Intel      | 77        | 22.51%  |
| Intel + AMD    | 50        | 14.62%  |
| 1 x AMD        | 29        | 8.48%   |
| 1 x Nvidia     | 18        | 5.26%   |
| 2 x AMD        | 7         | 2.05%   |
| AMD + Nvidia   | 7         | 2.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 260       | 74.93%  |
| Proprietary | 79        | 22.77%  |
| Unknown     | 8         | 2.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 44%     |
| 1.01-2.0   | 75        | 21.43%  |
| 3.01-4.0   | 51        | 14.57%  |
| 0.51-1.0   | 40        | 11.43%  |
| 0.01-0.5   | 24        | 6.86%   |
| 5.01-6.0   | 4         | 1.14%   |
| 7.01-8.0   | 1         | 0.29%   |
| 2.01-3.0   | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 70        | 19.66%  |
| AU Optronics            | 70        | 19.66%  |
| BOE                     | 52        | 14.61%  |
| Chimei Innolux          | 49        | 13.76%  |
| Samsung Electronics     | 43        | 12.08%  |
| Goldstar                | 14        | 3.93%   |
| Chi Mei Optoelectronics | 11        | 3.09%   |
| PANDA                   | 9         | 2.53%   |
| HannStar                | 5         | 1.4%    |
| BenQ                    | 4         | 1.12%   |
| Lenovo                  | 3         | 0.84%   |
| Sharp                   | 2         | 0.56%   |
| InnoLux Display         | 2         | 0.56%   |
| InfoVision              | 2         | 0.56%   |
| CHD                     | 2         | 0.56%   |
| Apple                   | 2         | 0.56%   |
| TMX                     | 1         | 0.28%   |
| Sony                    | 1         | 0.28%   |
| Seiko/Epson             | 1         | 0.28%   |
| Quanta Display          | 1         | 0.28%   |
| PAR                     | 1         | 0.28%   |
| Nvidia                  | 1         | 0.28%   |
| LGD                     | 1         | 0.28%   |
| LG Philips              | 1         | 0.28%   |
| KDC                     | 1         | 0.28%   |
| Hewlett-Packard         | 1         | 0.28%   |
| cPATH                   | 1         | 0.28%   |
| CHI                     | 1         | 0.28%   |
| AUS                     | 1         | 0.28%   |
| ASUSTek Computer        | 1         | 0.28%   |
| AOC                     | 1         | 0.28%   |
| Ancor Communications    | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 3.08%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 8         | 2.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 7         | 1.96%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 7         | 1.96%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.4%    |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 4         | 1.12%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.12%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch               | 4         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 1.12%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 4         | 1.12%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 1.12%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 1.12%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 1.12%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.84%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 3         | 0.84%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 3         | 0.84%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 3         | 0.84%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 3         | 0.84%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 3         | 0.84%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 3         | 0.84%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.56%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.56%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.56%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 0.56%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.56%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 2         | 0.56%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD03E6 1366x768 345x194mm 15.6-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 2         | 0.56%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch              | 2         | 0.56%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.56%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE0703 1920x1080 344x194mm 15.5-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.56%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.28%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.28%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 1         | 0.28%   |
| Sharp LCD Monitor SHP141F 1920x1080 294x165mm 13.3-inch                  | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 150       | 43.23%  |
| 1366x768 (WXGA)    | 138       | 39.77%  |
| 3840x2160 (4K)     | 12        | 3.46%   |
| 1600x900 (HD+)     | 10        | 2.88%   |
| 1440x900 (WXGA+)   | 10        | 2.88%   |
| 1280x800 (WXGA)    | 10        | 2.88%   |
| 1024x600           | 4         | 1.15%   |
| Unknown            | 3         | 0.86%   |
| 1680x1050 (WSXGA+) | 2         | 0.58%   |
| 5760x2160          | 1         | 0.29%   |
| 3840x2400          | 1         | 0.29%   |
| 3840x1080          | 1         | 0.29%   |
| 2944x1080          | 1         | 0.29%   |
| 2560x1440 (QHD)    | 1         | 0.29%   |
| 1920x1200 (WUXGA)  | 1         | 0.29%   |
| 1680x945           | 1         | 0.29%   |
| 1280x1024 (SXGA)   | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 225       | 63.74%  |
| 14      | 34        | 9.63%   |
| 13      | 30        | 8.5%    |
| 21      | 10        | 2.83%   |
| 12      | 10        | 2.83%   |
| 23      | 5         | 1.42%   |
| 17      | 5         | 1.42%   |
| 10      | 5         | 1.42%   |
| Unknown | 5         | 1.42%   |
| 20      | 4         | 1.13%   |
| 18      | 4         | 1.13%   |
| 11      | 4         | 1.13%   |
| 24      | 3         | 0.85%   |
| 27      | 2         | 0.57%   |
| 19      | 2         | 0.57%   |
| 16      | 2         | 0.57%   |
| 84      | 1         | 0.28%   |
| 32      | 1         | 0.28%   |
| 22      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 281       | 79.6%   |
| 201-300     | 25        | 7.08%   |
| 401-500     | 21        | 5.95%   |
| 501-600     | 9         | 2.55%   |
| 351-400     | 9         | 2.55%   |
| Unknown     | 5         | 1.42%   |
| 701-800     | 1         | 0.28%   |
| 601-700     | 1         | 0.28%   |
| 1501-2000   | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 301       | 91.49%  |
| 16/10   | 21        | 6.38%   |
| Unknown | 5         | 1.52%   |
| 4/3     | 1         | 0.3%    |
| 3/2     | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 226       | 64.02%  |
| 81-90          | 58        | 16.43%  |
| 201-250        | 19        | 5.38%   |
| 61-70          | 10        | 2.83%   |
| 151-200        | 7         | 1.98%   |
| 41-50          | 5         | 1.42%   |
| Unknown        | 5         | 1.42%   |
| 71-80          | 4         | 1.13%   |
| 51-60          | 4         | 1.13%   |
| 121-130        | 4         | 1.13%   |
| 141-150        | 3         | 0.85%   |
| 301-350        | 2         | 0.57%   |
| 131-140        | 2         | 0.57%   |
| 91-100         | 2         | 0.57%   |
| More than 1000 | 1         | 0.28%   |
| 351-500        | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 155       | 44.67%  |
| 101-120       | 127       | 36.6%   |
| 51-100        | 47        | 13.54%  |
| More than 240 | 10        | 2.88%   |
| Unknown       | 5         | 1.44%   |
| 161-240       | 3         | 0.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 302       | 87.28%  |
| 2     | 34        | 9.83%   |
| 0     | 9         | 2.6%    |
| 3     | 1         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 208       | 35.99%  |
| Intel                    | 156       | 26.99%  |
| Qualcomm Atheros         | 93        | 16.09%  |
| Broadcom                 | 43        | 7.44%   |
| Broadcom Limited         | 15        | 2.6%    |
| Ralink                   | 13        | 2.25%   |
| Xiaomi                   | 8         | 1.38%   |
| Samsung Electronics      | 8         | 1.38%   |
| MediaTek                 | 6         | 1.04%   |
| Marvell Technology Group | 4         | 0.69%   |
| JMicron Technology       | 3         | 0.52%   |
| Huawei Technologies      | 3         | 0.52%   |
| HTC (High Tech Computer) | 3         | 0.52%   |
| Hewlett-Packard          | 2         | 0.35%   |
| D-Link                   | 2         | 0.35%   |
| TP-Link                  | 1         | 0.17%   |
| Sierra Wireless          | 1         | 0.17%   |
| Ralink Technology        | 1         | 0.17%   |
| Qualcomm                 | 1         | 0.17%   |
| LG Electronics           | 1         | 0.17%   |
| Lenovo                   | 1         | 0.17%   |
| ICS Advent               | 1         | 0.17%   |
| BUFFALO                  | 1         | 0.17%   |
| Attansic Technology      | 1         | 0.17%   |
| ASUSTek Computer         | 1         | 0.17%   |
| ASIX Electronics         | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 158       | 23.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 4.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 21        | 3.17%   |
| Intel Wireless 7265                                               | 21        | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 1.96%   |
| Intel Wireless 7260                                               | 13        | 1.96%   |
| Intel Wireless 8265 / 8275                                        | 12        | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 1.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 11        | 1.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 1.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 8         | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 1.06%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.9%    |
| Intel Wireless 8260                                               | 6         | 0.9%    |
| Intel Centrino Advanced-N 6200                                    | 6         | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.6%    |
| Intel Wireless 3165                                               | 4         | 0.6%    |
| Intel Wi-Fi 6 AX200                                               | 4         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.6%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.6%    |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.6%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.45%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.45%   |
| Intel Wireless 3160                                               | 3         | 0.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.45%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.45%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.45%   |
| Huawei JNY-LX1                                                    | 3         | 0.45%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 3         | 0.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 3         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 154       | 44.77%  |
| Qualcomm Atheros      | 79        | 22.97%  |
| Realtek Semiconductor | 45        | 13.08%  |
| Broadcom              | 29        | 8.43%   |
| Ralink                | 13        | 3.78%   |
| Broadcom Limited      | 12        | 3.49%   |
| MediaTek              | 5         | 1.45%   |
| Hewlett-Packard       | 2         | 0.58%   |
| Xiaomi                | 1         | 0.29%   |
| TP-Link               | 1         | 0.29%   |
| Ralink Technology     | 1         | 0.29%   |
| D-Link                | 1         | 0.29%   |
| BUFFALO               | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 6.07%   |
| Intel Wireless 7265                                                     | 21        | 6.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 4.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 4.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 3.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.76%   |
| Intel Wireless 7260                                                     | 13        | 3.76%   |
| Intel Wireless 8265 / 8275                                              | 12        | 3.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 3.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 3.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 2.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.31%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 2.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.73%   |
| Intel Wireless 8260                                                     | 6         | 1.73%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.16%   |
| Intel Wireless 3165                                                     | 4         | 1.16%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.16%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.16%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.16%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.87%   |
| Intel Wireless 3160                                                     | 3         | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.87%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.87%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.58%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 2         | 0.58%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.58%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.58%   |
| Intel WiFi Link 5100                                                    | 2         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.58%   |
| Intel Centrino Wireless-N 135                                           | 2         | 0.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.58%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 0.58%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.58%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 2         | 0.58%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.58%   |
| Broadcom BCM43227 802.11b/g/n                                           | 2         | 0.58%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.58%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.29%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.29%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.29%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.29%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.29%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 190       | 60.32%  |
| Intel                    | 35        | 11.11%  |
| Qualcomm Atheros         | 28        | 8.89%   |
| Broadcom                 | 22        | 6.98%   |
| Samsung Electronics      | 8         | 2.54%   |
| Xiaomi                   | 7         | 2.22%   |
| Marvell Technology Group | 4         | 1.27%   |
| JMicron Technology       | 3         | 0.95%   |
| Huawei Technologies      | 3         | 0.95%   |
| HTC (High Tech Computer) | 3         | 0.95%   |
| Broadcom Limited         | 3         | 0.95%   |
| Sierra Wireless          | 1         | 0.32%   |
| Qualcomm                 | 1         | 0.32%   |
| MediaTek                 | 1         | 0.32%   |
| LG Electronics           | 1         | 0.32%   |
| Lenovo                   | 1         | 0.32%   |
| ICS Advent               | 1         | 0.32%   |
| D-Link                   | 1         | 0.32%   |
| Attansic Technology      | 1         | 0.32%   |
| ASIX Electronics         | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 158       | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 30        | 9.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 3.16%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 7         | 2.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 7         | 2.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 1.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 1.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 3         | 0.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.95%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.95%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.95%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.95%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.95%   |
| Huawei JNY-LX1                                                                 | 3         | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.63%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.63%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.63%   |
| Intel Ethernet Connection (16) I219-LM                                         | 2         | 0.63%   |
| HTC (High Tech Computer) HTC                                                   | 2         | 0.63%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.63%   |
| Sierra Wireless EM7345 4G LTE                                                  | 1         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.32%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.32%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.32%   |
| Qualcomm Redmi 5 Plus                                                          | 1         | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.32%   |
| MediaTek moto e6s                                                              | 1         | 0.32%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.32%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                            | 1         | 0.32%   |
| Lenovo Android Phone                                                           | 1         | 0.32%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.32%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.32%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.32%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.32%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.32%   |
| HTC (High Tech Computer) Desire 626 dual sim                                   | 1         | 0.32%   |
| D-Link DUB-1312                                                                | 1         | 0.32%   |
| Broadcom Pirelli Remote NDIS Device                                            | 1         | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.32%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 1         | 0.32%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.32%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.32%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.32%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.32%   |
| Broadcom Limited NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1         | 0.32%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.32%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.32%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.32%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 338       | 53.65%  |
| Ethernet | 291       | 46.19%  |
| Unknown  | 1         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 288       | 85.97%  |
| Ethernet | 46        | 13.73%  |
| Unknown  | 1         | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 281       | 82.16%  |
| 1     | 60        | 17.54%  |
| 0     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 318       | 92.17%  |
| Yes  | 27        | 7.83%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 40.36%  |
| IMC Networks                    | 38        | 13.57%  |
| Qualcomm Atheros Communications | 24        | 8.57%   |
| Realtek Semiconductor           | 23        | 8.21%   |
| Broadcom                        | 15        | 5.36%   |
| Lite-On Technology              | 14        | 5%      |
| Foxconn / Hon Hai               | 12        | 4.29%   |
| Dell                            | 9         | 3.21%   |
| Ralink                          | 8         | 2.86%   |
| ASUSTek Computer                | 7         | 2.5%    |
| Foxconn International           | 4         | 1.43%   |
| Ralink Technology               | 3         | 1.07%   |
| Hewlett-Packard                 | 2         | 0.71%   |
| Cambridge Silicon Radio         | 2         | 0.71%   |
| Askey Computer                  | 2         | 0.71%   |
| Apple                           | 2         | 0.71%   |
| Realtek                         | 1         | 0.36%   |
| Micro Star International        | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 63        | 22.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 6.43%   |
| Intel AX201 Bluetooth                                                               | 17        | 6.07%   |
| IMC Networks Bluetooth Radio                                                        | 17        | 6.07%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 4.64%   |
| Realtek Bluetooth Radio                                                             | 12        | 4.29%   |
| IMC Networks Bluetooth Device                                                       | 10        | 3.57%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 2.86%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 6         | 2.14%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.79%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.79%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 1.43%   |
| Intel AX200 Bluetooth                                                               | 4         | 1.43%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.43%   |
| Broadcom BCM20702A0                                                                 | 4         | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.07%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.07%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.07%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 1.07%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.07%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 1.07%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 1.07%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.71%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.71%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.71%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.71%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.71%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.71%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.71%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.71%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.71%   |
| Askey Bluetooth Device                                                              | 2         | 0.71%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.36%   |
| Ralink CSR BS8510                                                                   | 1         | 0.36%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.36%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.36%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.36%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.36%   |
| IMC Networks Bluetooth                                                              | 1         | 0.36%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.36%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.36%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.36%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.36%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.36%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.36%   |
| Broadcom Bluetooth                                                                  | 1         | 0.36%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.36%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.36%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 311       | 75.3%   |
| Nvidia           | 55        | 13.32%  |
| AMD              | 43        | 10.41%  |
| ASUSTek Computer | 2         | 0.48%   |
| Yamaha           | 1         | 0.24%   |
| CMX Systems      | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 57        | 11.47%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 37        | 7.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 32        | 6.44%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 4.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 4.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 4.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 4.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 3.02%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 3.02%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 3.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 2.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 2.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 2.21%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.21%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.21%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 1.01%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.8%    |
| Nvidia Audio device                                                                               | 4         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.8%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4         | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.6%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.6%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.6%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.4%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.4%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.4%    |
| ASUSTek Computer C-Media Audio                                                                    | 2         | 0.4%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.4%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.4%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.4%    |
| AMD High Definition Audio Controller                                                              | 2         | 0.4%    |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.2%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.2%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.2%    |
| Nvidia stereo controller                                                                          | 1         | 0.2%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.2%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.2%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 66        | 33.17%  |
| SK hynix            | 41        | 20.6%   |
| Micron Technology   | 29        | 14.57%  |
| Kingston            | 13        | 6.53%   |
| Crucial             | 12        | 6.03%   |
| Unknown             | 9         | 4.52%   |
| Ramaxel Technology  | 9         | 4.52%   |
| Elpida              | 8         | 4.02%   |
| A-DATA Technology   | 7         | 3.52%   |
| Transcend           | 1         | 0.5%    |
| Neo Forza           | 1         | 0.5%    |
| Nanya Technology    | 1         | 0.5%    |
| Kingmax             | 1         | 0.5%    |
| ASint Technology    | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 8         | 3.76%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 6         | 2.82%   |
| Crucial RAM CB16GS2666.C8ET 16384MB SODIMM DDR4 2667MT/s     | 6         | 2.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 2.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 5         | 2.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 5         | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 4         | 1.88%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.88%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 4         | 1.88%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 4         | 1.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 3         | 1.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 1.41%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 1.41%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 3         | 1.41%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 3         | 1.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 1.41%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 3         | 1.41%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 3         | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.94%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.94%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.94%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s    | 2         | 0.94%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 0.94%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s     | 2         | 0.94%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 0.94%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2         | 0.94%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.94%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.94%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.94%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 2         | 0.94%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s           | 2         | 0.94%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s    | 2         | 0.94%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.94%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s        | 2         | 0.94%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 2         | 0.94%   |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s        | 2         | 0.94%   |
| Kingston RAM ACR21D4S15HAG/8G 8192MB SODIMM DDR4 2133MT/s    | 2         | 0.94%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 1600MT/s       | 2         | 0.94%   |
| Crucial RAM CB8GS2400.C8JT 8GB SODIMM DDR4 2400MT/s          | 2         | 0.94%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s            | 2         | 0.94%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                  | 1         | 0.47%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM                                | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM                             | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3                        | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 1         | 0.47%   |
| Transcend RAM TS512MSK64W6H 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.47%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.47%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s       | 1         | 0.47%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 0.47%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 46.88%  |
| DDR3    | 68        | 42.5%   |
| DDR2    | 6         | 3.75%   |
| SDRAM   | 4         | 2.5%    |
| LPDDR4  | 2         | 1.25%   |
| LPDDR3  | 2         | 1.25%   |
| DDR5    | 2         | 1.25%   |
| Unknown | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 148       | 95.48%  |
| Row Of Chips | 6         | 3.87%   |
| Chip         | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 80        | 43.48%  |
| 8192  | 61        | 33.15%  |
| 2048  | 23        | 12.5%   |
| 16384 | 15        | 8.15%   |
| 1024  | 5         | 2.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 51        | 28.18%  |
| 2667    | 40        | 22.1%   |
| 1334    | 18        | 9.94%   |
| 3200    | 15        | 8.29%   |
| 2400    | 12        | 6.63%   |
| 2133    | 11        | 6.08%   |
| 3266    | 8         | 4.42%   |
| 1333    | 5         | 2.76%   |
| 667     | 5         | 2.76%   |
| 4199    | 4         | 2.21%   |
| Unknown | 4         | 2.21%   |
| 8400    | 2         | 1.1%    |
| 4800    | 2         | 1.1%    |
| 1067    | 2         | 1.1%    |
| 1867    | 1         | 0.55%   |
| 800     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP LaserJet P1102      | 1         | 50%     |
| HP DeskJet 2130 series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 50%     |
| Canon CanoScan 4400F    | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 72        | 22.57%  |
| IMC Networks                           | 70        | 21.94%  |
| Acer                                   | 30        | 9.4%    |
| Realtek Semiconductor                  | 27        | 8.46%   |
| Microdia                               | 22        | 6.9%    |
| Syntek                                 | 16        | 5.02%   |
| Sunplus Innovation Technology          | 14        | 4.39%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 3.76%   |
| Suyin                                  | 9         | 2.82%   |
| Lite-On Technology                     | 8         | 2.51%   |
| Sonix Technology                       | 6         | 1.88%   |
| Apple                                  | 6         | 1.88%   |
| Ricoh                                  | 5         | 1.57%   |
| Quanta                                 | 4         | 1.25%   |
| Samsung Electronics                    | 3         | 0.94%   |
| Lenovo                                 | 3         | 0.94%   |
| ALi                                    | 3         | 0.94%   |
| Pixart Imaging                         | 2         | 0.63%   |
| Vimicro                                | 1         | 0.31%   |
| Primax Electronics                     | 1         | 0.31%   |
| OmniVision Technologies                | 1         | 0.31%   |
| Luxvisions Innotech Limited            | 1         | 0.31%   |
| LG Electronics                         | 1         | 0.31%   |
| Importek                               | 1         | 0.31%   |
| Alcor Micro                            | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                       | 28        | 8.78%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 14        | 4.39%   |
| IMC Networks Integrated Camera                                           | 11        | 3.45%   |
| Acer Lenovo EasyCamera                                                   | 11        | 3.45%   |
| Chicony Integrated Camera                                                | 8         | 2.51%   |
| Chicony HD WebCam                                                        | 8         | 2.51%   |
| Chicony EasyCamera                                                       | 8         | 2.51%   |
| Realtek USB Camera                                                       | 7         | 2.19%   |
| Chicony USB2.0 HD UVC WebCam                                             | 7         | 2.19%   |
| Syntek EasyCamera                                                        | 6         | 1.88%   |
| IMC Networks Lenovo EasyCamera                                           | 6         | 1.88%   |
| Syntek Lenovo EasyCamera                                                 | 5         | 1.57%   |
| Sunplus HD WebCam                                                        | 5         | 1.57%   |
| Sonix USB2.0 HD UVC WebCam                                               | 5         | 1.57%   |
| Realtek USB2.0 HD UVC WebCam                                             | 5         | 1.57%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 5         | 1.57%   |
| Acer Integrated Camera                                                   | 5         | 1.57%   |
| Syntek Integrated Camera                                                 | 4         | 1.25%   |
| Sunplus ASUS USB2.0 Webcam                                               | 4         | 1.25%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 4         | 1.25%   |
| Microdia Integrated_Webcam_HD                                            | 4         | 1.25%   |
| Lite-On Integrated Camera                                                | 4         | 1.25%   |
| Chicony Integrated HP HD Webcam                                          | 4         | 1.25%   |
| Chicony HP HD Webcam [Fixed]                                             | 4         | 1.25%   |
| Chicony HP HD Webcam                                                     | 4         | 1.25%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 3         | 0.94%   |
| Microdia Sonix Integrated Webcam                                         | 3         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 0.94%   |
| Microdia Integrated Webcam                                               | 3         | 0.94%   |
| Lite-On HP HD Camera                                                     | 3         | 0.94%   |
| IMC Networks VGA UVC WebCam                                              | 3         | 0.94%   |
| IMC Networks Integrated Webcam                                           | 3         | 0.94%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 3         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 3         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 3         | 0.94%   |
| ALi Gateway Webcam                                                       | 3         | 0.94%   |
| Acer SunplusIT Integrated Camera                                         | 3         | 0.94%   |
| Acer Lenovo Integrated Webcam                                            | 3         | 0.94%   |
| Sunplus Dell E5570 integrated webcam                                     | 2         | 0.63%   |
| Realtek Integrated_Webcam_HD                                             | 2         | 0.63%   |
| Realtek HD WebCam                                                        | 2         | 0.63%   |
| Realtek EasyCamera                                                       | 2         | 0.63%   |
| Quanta HD User Facing                                                    | 2         | 0.63%   |
| Pixart Imaging USB_2.0_Webcam                                            | 2         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 2         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M    | 2         | 0.63%   |
| Lenovo CNF7237&CNF7238                                                   | 2         | 0.63%   |
| Chicony Lenovo EasyCamera                                                | 2         | 0.63%   |
| Chicony HP Webcam [2 MP Macro]                                           | 2         | 0.63%   |
| Chicony HP Truevision HD                                                 | 2         | 0.63%   |
| Chicony HP HD Camera                                                     | 2         | 0.63%   |
| Chicony 2.0M UVC WebCam                                                  | 2         | 0.63%   |
| Chicony 1.3M HD WebCam                                                   | 2         | 0.63%   |
| Acer EasyCamera                                                          | 2         | 0.63%   |
| Acer BisonCam, NB Pro                                                    | 2         | 0.63%   |
| Vimicro Integrated Camera                                                | 1         | 0.31%   |
| Syntek USB Video Device                                                  | 1         | 0.31%   |
| Suyin Sony Visual Communication Camera                                   | 1         | 0.31%   |
| Suyin LG Webcam                                                          | 1         | 0.31%   |
| Suyin Laptop_Integrated_Webcam_2HDM                                      | 1         | 0.31%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 32        | 40.51%  |
| Shenzhen Goodix Technology | 13        | 16.46%  |
| Synaptics                  | 9         | 11.39%  |
| Elan Microelectronics      | 9         | 11.39%  |
| Upek                       | 8         | 10.13%  |
| AuthenTec                  | 4         | 5.06%   |
| LighTuning Technology      | 3         | 3.8%    |
| STMicroelectronics         | 1         | 1.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 14        | 17.72%  |
| Validity Sensors VFS491                                | 9         | 11.39%  |
| Shenzhen Goodix  FingerPrint Device                    | 9         | 11.39%  |
| Elan ELAN:Fingerprint                                  | 9         | 11.39%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 7         | 8.86%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 3.8%    |
| Synaptics  WBDI                                        | 3         | 3.8%    |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 3.8%    |
| Unknown                                                | 3         | 3.8%    |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 2.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 2.53%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 2         | 2.53%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 2.53%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 1.27%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 1.27%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 1.27%   |
| Validity Sensors Fingerprint scanner                   | 1         | 1.27%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 1.27%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 1.27%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 1.27%   |
| Shenzhen Goodix FingerPrint                            | 1         | 1.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 1.27%   |
| AuthenTec Fingerprint Sensor                           | 1         | 1.27%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 1.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 42.86%  |
| Alcor Micro | 4         | 28.57%  |
| Upek        | 2         | 14.29%  |
| O2 Micro    | 2         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 14.29%  |
| Broadcom 5880                                                                | 2         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 205       | 58.57%  |
| 1     | 105       | 30%     |
| 2     | 32        | 9.14%   |
| 3     | 5         | 1.43%   |
| 7     | 1         | 0.29%   |
| 5     | 1         | 0.29%   |
| 4     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 79        | 41.58%  |
| Graphics card            | 50        | 26.32%  |
| Bluetooth                | 14        | 7.37%   |
| Chipcard                 | 13        | 6.84%   |
| Net/wireless             | 12        | 6.32%   |
| Camera                   | 6         | 3.16%   |
| Communication controller | 5         | 2.63%   |
| Storage                  | 4         | 2.11%   |
| Sound                    | 2         | 1.05%   |
| Card reader              | 2         | 1.05%   |
| Wireless                 | 1         | 0.53%   |
| Net/ethernet             | 1         | 0.53%   |
| Multimedia controller    | 1         | 0.53%   |

