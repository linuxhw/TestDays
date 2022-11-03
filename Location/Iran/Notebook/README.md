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

Total: 532

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Modern 15 A10RBS            | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| HP            | G62                         | [a7b5ac8e19](https://linux-hardware.org/?probe=a7b5ac8e19) | Oct 20, 2022 |
| MSI           | Modern 15 A5M               | [6459e3fedb](https://linux-hardware.org/?probe=6459e3fedb) | Oct 16, 2022 |
| MSI           | Modern 15 A5M               | [5192a80499](https://linux-hardware.org/?probe=5192a80499) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | G62                         | [dbe9a778bb](https://linux-hardware.org/?probe=dbe9a778bb) | Oct 12, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| HP            | EliteBook Revolve 810 G3    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| ASUSTek       | UX490UA                     | [e953c29d50](https://linux-hardware.org/?probe=e953c29d50) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0737d49df2](https://linux-hardware.org/?probe=0737d49df2) | Sep 15, 2022 |
| ASUSTek       | K56CB                       | [8718c2bb09](https://linux-hardware.org/?probe=8718c2bb09) | Sep 12, 2022 |
| Acer          | Aspire V3-571G              | [33c08b8aef](https://linux-hardware.org/?probe=33c08b8aef) | Sep 09, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [c803fe67f3](https://linux-hardware.org/?probe=c803fe67f3) | Sep 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c98348c9a3](https://linux-hardware.org/?probe=c98348c9a3) | Sep 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [68b6da5fe1](https://linux-hardware.org/?probe=68b6da5fe1) | Sep 04, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/Iran/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 70        | 18.72%  |
| Ubuntu 18.04                 | 55        | 14.71%  |
| Ubuntu 22.04                 | 14        | 3.74%   |
| Fedora 33                    | 13        | 3.48%   |
| Arch                         | 13        | 3.48%   |
| Ubuntu 19.04                 | 10        | 2.67%   |
| Arch Rolling                 | 10        | 2.67%   |
| Fedora 34                    | 8         | 2.14%   |
| Ubuntu 21.10                 | 7         | 1.87%   |
| Ubuntu 20.10                 | 7         | 1.87%   |
| KDE neon 20.04               | 7         | 1.87%   |
| Ubuntu 19.10                 | 6         | 1.6%    |
| Manjaro                      | 6         | 1.6%    |
| Xubuntu 18.04                | 5         | 1.34%   |
| Ubuntu 21.04                 | 5         | 1.34%   |
| OpenMandriva 4.2             | 5         | 1.34%   |
| Fedora 35                    | 5         | 1.34%   |
| Ubuntu 18.10                 | 4         | 1.07%   |
| Debian 11                    | 4         | 1.07%   |
| Ubuntu Budgie 20.04          | 3         | 0.8%    |
| Linux Mint 20.2              | 3         | 0.8%    |
| Linux Mint 19.3              | 3         | 0.8%    |
| Kubuntu 20.04                | 3         | 0.8%    |
| Kali 2021.2                  | 3         | 0.8%    |
| Fedora 31                    | 3         | 0.8%    |
| ArcoLinux Rolling            | 3         | 0.8%    |
| Zorin 15                     | 2         | 0.53%   |
| Xubuntu 22.04                | 2         | 0.53%   |
| Xubuntu 20.04                | 2         | 0.53%   |
| Ubuntu Unity 20.04           | 2         | 0.53%   |
| Ubuntu 17.10                 | 2         | 0.53%   |
| ROSA R11                     | 2         | 0.53%   |
| Pop!_OS 21.10                | 2         | 0.53%   |
| Pop!_OS 20.04                | 2         | 0.53%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.53%   |
| OpenMandriva 4.3             | 2         | 0.53%   |
| Manjaro 20.2.1               | 2         | 0.53%   |
| Manjaro 20.2                 | 2         | 0.53%   |
| Linux Mint 20.3              | 2         | 0.53%   |
| Kubuntu 19.10                | 2         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 175       | 48.88%  |
| Fedora        | 31        | 8.66%   |
| Arch          | 21        | 5.87%   |
| Manjaro       | 17        | 4.75%   |
| Endless       | 14        | 3.91%   |
| Linux Mint    | 11        | 3.07%   |
| Kali          | 10        | 2.79%   |
| Xubuntu       | 9         | 2.51%   |
| Kubuntu       | 9         | 2.51%   |
| KDE neon      | 9         | 2.51%   |
| OpenMandriva  | 8         | 2.23%   |
| Pop!_OS       | 6         | 1.68%   |
| Debian        | 6         | 1.68%   |
| Zorin         | 3         | 0.84%   |
| Ubuntu Unity  | 3         | 0.84%   |
| Ubuntu Budgie | 3         | 0.84%   |
| ROSA          | 3         | 0.84%   |
| openSUSE      | 3         | 0.84%   |
| ArcoLinux     | 3         | 0.84%   |
| Gentoo        | 2         | 0.56%   |
| Elementary    | 2         | 0.56%   |
| Ubuntu MATE   | 1         | 0.28%   |
| Solus         | 1         | 0.28%   |
| Sabayon       | 1         | 0.28%   |
| PureOS        | 1         | 0.28%   |
| NixOS         | 1         | 0.28%   |
| Lubuntu       | 1         | 0.28%   |
| Linux Lite    | 1         | 0.28%   |
| Deepin        | 1         | 0.28%   |
| Clear Linux   | 1         | 0.28%   |
| CentOS        | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 3.04%   |
| 5.3.0-46-generic         | 7         | 1.77%   |
| 5.4.0-26-generic         | 6         | 1.52%   |
| 5.8.0-63-generic         | 5         | 1.27%   |
| 5.4.0-52-generic         | 5         | 1.27%   |
| 5.15.0-47-generic        | 5         | 1.27%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.27%   |
| 5.0.0-13-generic         | 5         | 1.27%   |
| 5.8.0-48-generic         | 4         | 1.01%   |
| 5.4.0-58-generic         | 4         | 1.01%   |
| 5.3.0-40-generic         | 4         | 1.01%   |
| 5.11.0-41-generic        | 4         | 1.01%   |
| 5.11.0-27-generic        | 4         | 1.01%   |
| 5.0.0-23-generic         | 4         | 1.01%   |
| 4.18.0-25-generic        | 4         | 1.01%   |
| 4.18.0-15-generic        | 4         | 1.01%   |
| 5.8.0-59-generic         | 3         | 0.76%   |
| 5.4.0-40-generic         | 3         | 0.76%   |
| 5.3.0-51-generic         | 3         | 0.76%   |
| 5.15.0-46-generic        | 3         | 0.76%   |
| 5.15.0-33-generic        | 3         | 0.76%   |
| 5.13.0-22-generic        | 3         | 0.76%   |
| 5.0.0-37-generic         | 3         | 0.76%   |
| 5.0.0-25-generic         | 3         | 0.76%   |
| 4.18.0-16-generic        | 3         | 0.76%   |
| 4.15.0-15-generic        | 3         | 0.76%   |
| 5.9.16-1-MANJARO         | 2         | 0.51%   |
| 5.8.18-1-MANJARO         | 2         | 0.51%   |
| 5.8.0-50-generic         | 2         | 0.51%   |
| 5.8.0-43-generic         | 2         | 0.51%   |
| 5.8.0-14-generic         | 2         | 0.51%   |
| 5.6.0-7-generic          | 2         | 0.51%   |
| 5.4.0-91-generic         | 2         | 0.51%   |
| 5.4.0-73-generic         | 2         | 0.51%   |
| 5.4.0-72-generic         | 2         | 0.51%   |
| 5.4.0-65-generic         | 2         | 0.51%   |
| 5.4.0-59-generic         | 2         | 0.51%   |
| 5.4.0-54-generic         | 2         | 0.51%   |
| 5.4.0-51-generic         | 2         | 0.51%   |
| 5.4.0-48-generic         | 2         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 70        | 18.47%  |
| 5.0.0   | 26        | 6.86%   |
| 5.3.0   | 24        | 6.33%   |
| 5.8.0   | 23        | 6.07%   |
| 5.11.0  | 23        | 6.07%   |
| 4.15.0  | 23        | 6.07%   |
| 5.15.0  | 22        | 5.8%    |
| 5.13.0  | 18        | 4.75%   |
| 4.18.0  | 18        | 4.75%   |
| 5.10.0  | 9         | 2.37%   |
| 5.10.14 | 5         | 1.32%   |
| 5.11.11 | 4         | 1.06%   |
| 4.13.0  | 4         | 1.06%   |
| 5.9.16  | 3         | 0.79%   |
| 5.8.18  | 3         | 0.79%   |
| 5.6.0   | 3         | 0.79%   |
| 5.16.7  | 3         | 0.79%   |
| 5.16.15 | 3         | 0.79%   |
| 5.14.16 | 3         | 0.79%   |
| 5.13.19 | 3         | 0.79%   |
| 5.7.0   | 2         | 0.53%   |
| 5.16.0  | 2         | 0.53%   |
| 5.15.4  | 2         | 0.53%   |
| 5.13.7  | 2         | 0.53%   |
| 5.13.13 | 2         | 0.53%   |
| 5.12.8  | 2         | 0.53%   |
| 5.9.14  | 1         | 0.26%   |
| 5.9.11  | 1         | 0.26%   |
| 5.8.4   | 1         | 0.26%   |
| 5.8.16  | 1         | 0.26%   |
| 5.8.15  | 1         | 0.26%   |
| 5.8.14  | 1         | 0.26%   |
| 5.8.13  | 1         | 0.26%   |
| 5.7.6   | 1         | 0.26%   |
| 5.6.17  | 1         | 0.26%   |
| 5.6.14  | 1         | 0.26%   |
| 5.6.12  | 1         | 0.26%   |
| 5.6.10  | 1         | 0.26%   |
| 5.5.8   | 1         | 0.26%   |
| 5.5.13  | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 75        | 19.95%  |
| 5.8     | 31        | 8.24%   |
| 5.11    | 31        | 8.24%   |
| 5.15    | 30        | 7.98%   |
| 5.0     | 28        | 7.45%   |
| 5.13    | 26        | 6.91%   |
| 5.3     | 25        | 6.65%   |
| 5.10    | 23        | 6.12%   |
| 4.15    | 23        | 6.12%   |
| 4.18    | 18        | 4.79%   |
| 5.16    | 12        | 3.19%   |
| 5.14    | 10        | 2.66%   |
| 5.6     | 6         | 1.6%    |
| 5.12    | 6         | 1.6%    |
| 5.9     | 5         | 1.33%   |
| 5.18    | 5         | 1.33%   |
| 4.13    | 4         | 1.06%   |
| 5.7     | 3         | 0.8%    |
| 4.19    | 3         | 0.8%    |
| 5.5     | 2         | 0.53%   |
| 5.17    | 2         | 0.53%   |
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
| x86_64 | 347       | 98.3%   |
| i686   | 6         | 1.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 189       | 52.21%  |
| Unknown         | 72        | 19.89%  |
| KDE5            | 28        | 7.73%   |
| XFCE            | 25        | 6.91%   |
| KDE             | 16        | 4.42%   |
| X-Cinnamon      | 7         | 1.93%   |
| MATE            | 5         | 1.38%   |
| i3              | 4         | 1.1%    |
| Unity           | 3         | 0.83%   |
| Budgie          | 3         | 0.83%   |
| Pantheon        | 2         | 0.55%   |
| LXQt            | 2         | 0.55%   |
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
| X11     | 266       | 73.28%  |
| Unknown | 49        | 13.5%   |
| Wayland | 45        | 12.4%   |
| Tty     | 3         | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 213       | 58.04%  |
| GDM     | 62        | 16.89%  |
| GDM3    | 30        | 8.17%   |
| SDDM    | 27        | 7.36%   |
| LightDM | 21        | 5.72%   |
| TDM     | 10        | 2.72%   |
| Ly      | 2         | 0.54%   |
| XDM     | 1         | 0.27%   |
| KDM     | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 264       | 73.54%  |
| Unknown | 69        | 19.22%  |
| en_GB   | 7         | 1.95%   |
| fa_IR   | 6         | 1.67%   |
| C       | 5         | 1.39%   |
| en_CA   | 3         | 0.84%   |
| POSIX   | 1         | 0.28%   |
| ja_JP   | 1         | 0.28%   |
| en_AG   | 1         | 0.28%   |
| de_DE   | 1         | 0.28%   |
| az_IR   | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 201       | 55.37%  |
| EFI  | 162       | 44.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 290       | 81.23%  |
| Btrfs   | 27        | 7.56%   |
| Overlay | 15        | 4.2%    |
| Unknown | 14        | 3.92%   |
| Zfs     | 5         | 1.4%    |
| Xfs     | 4         | 1.12%   |
| Ext3    | 1         | 0.28%   |
| Ext2    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 235       | 66.01%  |
| GPT     | 92        | 25.84%  |
| MBR     | 29        | 8.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 305       | 85.43%  |
| Yes       | 52        | 14.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 191       | 53.95%  |
| Yes       | 163       | 46.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 106       | 30.03%  |
| Lenovo           | 91        | 25.78%  |
| Hewlett-Packard  | 48        | 13.6%   |
| Dell             | 36        | 10.2%   |
| Acer             | 35        | 9.92%   |
| MSI              | 13        | 3.68%   |
| Sony             | 10        | 2.83%   |
| Toshiba          | 3         | 0.85%   |
| Fujitsu          | 3         | 0.85%   |
| Apple            | 2         | 0.57%   |
| Timi             | 1         | 0.28%   |
| Razer            | 1         | 0.28%   |
| Packard Bell     | 1         | 0.28%   |
| LG Electronics   | 1         | 0.28%   |
| Alienware        | 1         | 0.28%   |
| Unknown          | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad 330-15IKB 81DE              | 6         | 1.7%    |
| HP ProBook 4540s                           | 6         | 1.7%    |
| Acer Aspire V3-571G                        | 6         | 1.7%    |
| Lenovo IdeaPad Z510 20287                  | 4         | 1.13%   |
| HP Pavilion g6                             | 3         | 0.85%   |
| HP EliteBook 840 G2                        | 3         | 0.85%   |
| ASUS X580VD                                | 3         | 0.85%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 3         | 0.85%   |
| MSI Prestige 14 A10RB                      | 2         | 0.57%   |
| Lenovo Z50-70 20354                        | 2         | 0.57%   |
| Lenovo ThinkPad X250 20CM002XUS            | 2         | 0.57%   |
| Lenovo Legion 5 15ARH05H 82B1              | 2         | 0.57%   |
| Lenovo IdeaPad S540-15IWL GTX 81SW         | 2         | 0.57%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 2         | 0.57%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 2         | 0.57%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 2         | 0.57%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 2         | 0.57%   |
| Lenovo G50-80 80E5                         | 2         | 0.57%   |
| Lenovo G50-70 20351                        | 2         | 0.57%   |
| Lenovo Flex 2-15 20405                     | 2         | 0.57%   |
| Lenovo B570e HuronRiver Platform           | 2         | 0.57%   |
| HP ProBook 450 G4                          | 2         | 0.57%   |
| HP Pavilion dv6                            | 2         | 0.57%   |
| HP Laptop 15-bs0xx                         | 2         | 0.57%   |
| HP EliteBook Revolve 810 G3                | 2         | 0.57%   |
| HP EliteBook 8470p                         | 2         | 0.57%   |
| Dell Vostro 1510                           | 2         | 0.57%   |
| Dell Vostro 1015                           | 2         | 0.57%   |
| Dell Latitude E7470                        | 2         | 0.57%   |
| Dell Latitude E6530                        | 2         | 0.57%   |
| Dell Inspiron N5110                        | 2         | 0.57%   |
| ASUS X550IU                                | 2         | 0.57%   |
| ASUS X542UN                                | 2         | 0.57%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD     | 2         | 0.57%   |
| ASUS VivoBook_ASUSLaptop X571GT_K571GT     | 2         | 0.57%   |
| ASUS VivoBook_ASUSLaptop X521EQ_S533EQ     | 2         | 0.57%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ     | 2         | 0.57%   |
| ASUS VivoBook 15_ASUS Laptop X540MB_X540MB | 2         | 0.57%   |
| ASUS VivoBook 15 ASUS Laptop X570UD        | 2         | 0.57%   |
| ASUS N501VW                                | 2         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 35        | 9.92%   |
| Acer Aspire       | 30        | 8.5%    |
| Lenovo ThinkPad   | 27        | 7.65%   |
| ASUS VivoBook     | 27        | 7.65%   |
| HP EliteBook      | 18        | 5.1%    |
| Dell Inspiron     | 14        | 3.97%   |
| HP ProBook        | 13        | 3.68%   |
| Dell Latitude     | 11        | 3.12%   |
| HP Pavilion       | 8         | 2.27%   |
| Dell Vostro       | 8         | 2.27%   |
| ASUS ASUS         | 6         | 1.7%    |
| Lenovo Legion     | 4         | 1.13%   |
| MSI Modern        | 3         | 0.85%   |
| Fujitsu LIFEBOOK  | 3         | 0.85%   |
| ASUS X580VD       | 3         | 0.85%   |
| ASUS ROG          | 3         | 0.85%   |
| Acer TravelMate   | 3         | 0.85%   |
| Toshiba Satellite | 2         | 0.57%   |
| MSI Prestige      | 2         | 0.57%   |
| MSI GE60          | 2         | 0.57%   |
| Lenovo Z50-70     | 2         | 0.57%   |
| Lenovo ThinkBook  | 2         | 0.57%   |
| Lenovo G580       | 2         | 0.57%   |
| Lenovo G50-80     | 2         | 0.57%   |
| Lenovo G50-70     | 2         | 0.57%   |
| Lenovo Flex       | 2         | 0.57%   |
| Lenovo B570e      | 2         | 0.57%   |
| HP ZBook          | 2         | 0.57%   |
| HP Laptop         | 2         | 0.57%   |
| ASUS X550IU       | 2         | 0.57%   |
| ASUS X542UN       | 2         | 0.57%   |
| ASUS N501VW       | 2         | 0.57%   |
| ASUS K55VD        | 2         | 0.57%   |
| Toshiba PORTEGE   | 1         | 0.28%   |
| Timi RedmiBook    | 1         | 0.28%   |
| Sony VPCZ126GG    | 1         | 0.28%   |
| Sony VPCSB36FG    | 1         | 0.28%   |
| Sony VPCSB19GG    | 1         | 0.28%   |
| Sony VPCSA25GX    | 1         | 0.28%   |
| Sony VPCEH36EG    | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 37        | 10.48%  |
| 2013 | 36        | 10.2%   |
| 2012 | 35        | 9.92%   |
| 2019 | 32        | 9.07%   |
| 2010 | 31        | 8.78%   |
| 2015 | 28        | 7.93%   |
| 2011 | 26        | 7.37%   |
| 2018 | 25        | 7.08%   |
| 2020 | 23        | 6.52%   |
| 2016 | 23        | 6.52%   |
| 2014 | 21        | 5.95%   |
| 2021 | 13        | 3.68%   |
| 2009 | 10        | 2.83%   |
| 2008 | 7         | 1.98%   |
| 2022 | 2         | 0.57%   |
| 2007 | 2         | 0.57%   |
| 2006 | 2         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 353       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 333       | 94.33%  |
| Enabled  | 20        | 5.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 353       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 126       | 35.49%  |
| 3.01-4.0   | 75        | 21.13%  |
| 8.01-16.0  | 72        | 20.28%  |
| 16.01-24.0 | 56        | 15.77%  |
| 1.01-2.0   | 9         | 2.54%   |
| 32.01-64.0 | 8         | 2.25%   |
| 2.01-3.0   | 4         | 1.13%   |
| 0.51-1.0   | 3         | 0.85%   |
| 24.01-32.0 | 2         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 128       | 33.6%   |
| 2.01-3.0   | 117       | 30.71%  |
| 3.01-4.0   | 61        | 16.01%  |
| 4.01-8.0   | 46        | 12.07%  |
| 0.51-1.0   | 19        | 4.99%   |
| 8.01-16.0  | 8         | 2.1%    |
| 16.01-24.0 | 1         | 0.26%   |
| 0.01-0.5   | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 252       | 70.19%  |
| 2      | 98        | 27.3%   |
| 3      | 7         | 1.95%   |
| 0      | 2         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 185       | 52.11%  |
| Yes       | 170       | 47.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 302       | 85.55%  |
| No        | 51        | 14.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 349       | 98.87%  |
| No        | 4         | 1.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 288       | 81.13%  |
| No        | 67        | 18.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Iran    | 353       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Tehran                         | 202       | 54.74%  |
| TehrДЃn                      | 34        | 9.21%   |
| Mashhad                        | 20        | 5.42%   |
| Isfahan                        | 12        | 3.25%   |
| Tajrīsh                       | 6         | 1.63%   |
| Khorramshahr                   | 6         | 1.63%   |
| Tabriz                         | 5         | 1.36%   |
| Rasht                          | 5         | 1.36%   |
| Qom                            | 4         | 1.08%   |
| Karaj                          | 4         | 1.08%   |
| Babol                          | 4         | 1.08%   |
| TajrД«sh                     | 3         | 0.81%   |
| Zanjan                         | 2         | 0.54%   |
| Yazd                           | 2         | 0.54%   |
| Shiraz                         | 2         | 0.54%   |
| Shahre Jadide Andisheh         | 2         | 0.54%   |
| Shahr-e Qods                   | 2         | 0.54%   |
| Sanandij                       | 2         | 0.54%   |
| Qazvin                         | 2         | 0.54%   |
| Kerman                         | 2         | 0.54%   |
| Gorgan                         | 2         | 0.54%   |
| ДЂstДЃneh-ye AshrafД«yeh | 1         | 0.27%   |
| Şowmeeh Sarā                 | 1         | 0.27%   |
| ShДЃhД«n Shahr             | 1         | 0.27%   |
| Shirvan                        | 1         | 0.27%   |
| ShahrД«ДЃr                 | 1         | 0.27%   |
| Shahr-e Kord                   | 1         | 0.27%   |
| SemÄ«rom                     | 1         | 0.27%   |
| Sari                           | 1         | 0.27%   |
| SalmДЃs                      | 1         | 0.27%   |
| Rūdsar                        | 1         | 0.27%   |
| Robat Karim                    | 1         | 0.27%   |
| Rey                            | 1         | 0.27%   |
| RÅ«dÄn                    | 1         | 0.27%   |
| RafsanjДЃn                   | 1         | 0.27%   |
| Qaleh Ganj                     | 1         | 0.27%   |
| NashtДЃrЕ«d                | 1         | 0.27%   |
| NajafДЃbДЃd                | 1         | 0.27%   |
| MДЃmЕ«nД«yeh             | 1         | 0.27%   |
| MД«ДЃneh                   | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 86        | 104    | 19.28%  |
| WDC                       | 84        | 97     | 18.83%  |
| Toshiba                   | 67        | 77     | 15.02%  |
| Samsung Electronics       | 56        | 62     | 12.56%  |
| Micron Technology         | 18        | 20     | 4.04%   |
| HGST                      | 18        | 22     | 4.04%   |
| SanDisk                   | 17        | 21     | 3.81%   |
| A-DATA Technology         | 16        | 21     | 3.59%   |
| Intel                     | 11        | 11     | 2.47%   |
| Unknown                   | 9         | 10     | 2.02%   |
| SK hynix                  | 7         | 8      | 1.57%   |
| Kingston                  | 7         | 10     | 1.57%   |
| Lexar                     | 6         | 7      | 1.35%   |
| Hitachi                   | 6         | 6      | 1.35%   |
| Plextor                   | 3         | 3      | 0.67%   |
| Apacer                    | 3         | 3      | 0.67%   |
| LITEON                    | 2         | 3      | 0.45%   |
| Kingmax                   | 2         | 2      | 0.45%   |
| Gigabyte Technology       | 2         | 2      | 0.45%   |
| Biostar                   | 2         | 3      | 0.45%   |
| Apple                     | 2         | 2      | 0.45%   |
| XPG                       | 1         | 1      | 0.22%   |
| VC-500                    | 1         | 1      | 0.22%   |
| ValueTech                 | 1         | 2      | 0.22%   |
| USB3.0                    | 1         | 1      | 0.22%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.22%   |
| Union Memory              | 1         | 1      | 0.22%   |
| UMIS                      | 1         | 1      | 0.22%   |
| Transcend                 | 1         | 1      | 0.22%   |
| SPCC                      | 1         | 1      | 0.22%   |
| Silicon Motion            | 1         | 1      | 0.22%   |
| PNY                       | 1         | 1      | 0.22%   |
| Phison                    | 1         | 1      | 0.22%   |
| OCZ                       | 1         | 1      | 0.22%   |
| Micron/Crucial Technology | 1         | 1      | 0.22%   |
| Mass                      | 1         | 2      | 0.22%   |
| LITEONIT                  | 1         | 2      | 0.22%   |
| KODAK                     | 1         | 1      | 0.22%   |
| KingFast                  | 1         | 1      | 0.22%   |
| GeIL                      | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 32        | 7.1%    |
| Toshiba MQ01ABD100 1TB              | 17        | 3.77%   |
| Toshiba MQ04ABF100 1TB              | 12        | 2.66%   |
| Seagate ST9500325AS 500GB           | 10        | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 10        | 2.22%   |
| WDC WD10SPZX-24Z10 1TB              | 8         | 1.77%   |
| WDC WD10SPZX-08Z10 1TB              | 7         | 1.55%   |
| WDC WD10JPCX-24UE4T0 1TB            | 7         | 1.55%   |
| Toshiba MQ01ABF050 500GB            | 7         | 1.55%   |
| Samsung SSD 860 EVO 500GB           | 7         | 1.55%   |
| Samsung SSD 860 EVO 250GB           | 6         | 1.33%   |
| Micron 2210_MTFDHBA512QFD 512GB     | 5         | 1.11%   |
| A-DATA SU650 120GB SSD              | 5         | 1.11%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 4         | 0.89%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 4         | 0.89%   |
| Toshiba MQ01ABD050V 500GB           | 4         | 0.89%   |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 0.89%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 4         | 0.89%   |
| Intel NVMe SSD Drive 512GB          | 4         | 0.89%   |
| HGST HTS721010A9E630 1TB            | 4         | 0.89%   |
| HGST HTS541010B7E610 1TB            | 4         | 0.89%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.89%   |
| WDC WD10SPZX-80Z10T2 1TB            | 3         | 0.67%   |
| Unknown MMC Card  32GB              | 3         | 0.67%   |
| Toshiba MQ01ABD075 752GB            | 3         | 0.67%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.67%   |
| Seagate ST9500420AS 500GB           | 3         | 0.67%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 0.67%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.67%   |
| Samsung NVMe SSD Drive 1024GB       | 3         | 0.67%   |
| Lexar 128GB SSD                     | 3         | 0.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 2         | 0.44%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 2         | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.44%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 2         | 0.44%   |
| WDC WD3200BEVT-75ZCT2 320GB         | 2         | 0.44%   |
| WDC WD10SPZX-75Z10T0 1TB            | 2         | 0.44%   |
| WDC WD10SPCX-08S8TT0 1TB            | 2         | 0.44%   |
| WDC WD10JPVX-08JC3T5 1TB            | 2         | 0.44%   |
| WDC WD10JPVX-00JC3T0 1TB            | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 86        | 104    | 35.25%  |
| WDC                 | 68        | 75     | 27.87%  |
| Toshiba             | 61        | 67     | 25%     |
| HGST                | 18        | 22     | 7.38%   |
| Hitachi             | 6         | 6      | 2.46%   |
| USB3.0              | 1         | 1      | 0.41%   |
| Unknown             | 1         | 1      | 0.41%   |
| Samsung Electronics | 1         | 1      | 0.41%   |
| Fujitsu             | 1         | 1      | 0.41%   |
| Apple               | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 42     | 27.21%  |
| WDC                 | 16        | 19     | 11.76%  |
| A-DATA Technology   | 16        | 21     | 11.76%  |
| SanDisk             | 13        | 16     | 9.56%   |
| Micron Technology   | 9         | 9      | 6.62%   |
| Lexar               | 6         | 7      | 4.41%   |
| Kingston            | 5         | 7      | 3.68%   |
| Toshiba             | 4         | 8      | 2.94%   |
| SK hynix            | 4         | 4      | 2.94%   |
| Plextor             | 3         | 3      | 2.21%   |
| Intel               | 3         | 3      | 2.21%   |
| Apacer              | 3         | 3      | 2.21%   |
| LITEON              | 2         | 3      | 1.47%   |
| Gigabyte Technology | 2         | 2      | 1.47%   |
| Biostar             | 2         | 3      | 1.47%   |
| ValueTech           | 1         | 2      | 0.74%   |
| Transcend           | 1         | 1      | 0.74%   |
| SPCC                | 1         | 1      | 0.74%   |
| PNY                 | 1         | 1      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| LITEONIT            | 1         | 2      | 0.74%   |
| KODAK               | 1         | 1      | 0.74%   |
| GeIL                | 1         | 1      | 0.74%   |
| Crucial             | 1         | 1      | 0.74%   |
| China               | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 242       | 279    | 54.88%  |
| SSD     | 133       | 163    | 30.16%  |
| NVMe    | 56        | 65     | 12.7%   |
| MMC     | 6         | 7      | 1.36%   |
| Unknown | 4         | 5      | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 317       | 440    | 82.55%  |
| NVMe | 56        | 65     | 14.58%  |
| MMC  | 6         | 7      | 1.56%   |
| SAS  | 5         | 7      | 1.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 196       | 246    | 54.44%  |
| 0.51-1.0   | 156       | 187    | 43.33%  |
| 1.01-2.0   | 8         | 9      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 102       | 27.95%  |
| 251-500        | 74        | 20.27%  |
| 501-1000       | 67        | 18.36%  |
| 51-100         | 34        | 9.32%   |
| 1001-2000      | 31        | 8.49%   |
| 1-20           | 25        | 6.85%   |
| 21-50          | 19        | 5.21%   |
| Unknown        | 9         | 2.47%   |
| More than 3000 | 2         | 0.55%   |
| 2001-3000      | 2         | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 137       | 36.53%  |
| 21-50          | 63        | 16.8%   |
| 51-100         | 51        | 13.6%   |
| 101-250        | 46        | 12.27%  |
| 501-1000       | 33        | 8.8%    |
| 251-500        | 31        | 8.27%   |
| Unknown        | 9         | 2.4%    |
| 2001-3000      | 2         | 0.53%   |
| 1001-2000      | 2         | 0.53%   |
| More than 3000 | 1         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 3         | 3      | 10.34%  |
| Toshiba MQ01ABD050 500GB                       | 2         | 2      | 6.9%    |
| Seagate ST9500325AS 500GB                      | 2         | 2      | 6.9%    |
| Seagate ST1000LM035-1RK172 1TB                 | 2         | 2      | 6.9%    |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1         | 1      | 3.45%   |
| WDC WD5000LPVX-80V0TT0 500GB                   | 1         | 1      | 3.45%   |
| WDC WD3200BPVT-75ZEST0 320GB                   | 1         | 1      | 3.45%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 3.45%   |
| WDC WD10SPZX-08Z10 1TB                         | 1         | 1      | 3.45%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 1         | 1      | 3.45%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 3.45%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 3.45%   |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 3.45%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 3.45%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 3.45%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 1      | 3.45%   |
| Seagate ST1000LM014-SSHD-8GB                   | 1         | 1      | 3.45%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 3.45%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 3.45%   |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 3.45%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 3.45%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 3.45%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 9         | 9      | 31.03%  |
| Seagate           | 8         | 8      | 27.59%  |
| WDC               | 6         | 6      | 20.69%  |
| Hitachi           | 3         | 3      | 10.34%  |
| HGST              | 2         | 2      | 6.9%    |
| Micron Technology | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 9         | 9      | 33.33%  |
| Seagate | 8         | 8      | 29.63%  |
| WDC     | 5         | 5      | 18.52%  |
| Hitachi | 3         | 3      | 11.11%  |
| HGST    | 2         | 2      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 27     | 92.86%  |
| SSD  | 2         | 2      | 7.14%   |

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
| Detected | 241       | 352    | 65.49%  |
| Works    | 99        | 137    | 26.9%   |
| Malfunc  | 27        | 29     | 7.34%   |
| Failed   | 1         | 1      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 308       | 79.18%  |
| AMD                          | 28        | 7.2%    |
| Samsung Electronics          | 19        | 4.88%   |
| Micron Technology            | 9         | 2.31%   |
| SanDisk                      | 7         | 1.8%    |
| Union Memory (Shenzhen)      | 4         | 1.03%   |
| SK hynix                     | 3         | 0.77%   |
| Phison Electronics           | 3         | 0.77%   |
| Toshiba America Info Systems | 2         | 0.51%   |
| Kingston Technology Company  | 2         | 0.51%   |
| Silicon Motion               | 1         | 0.26%   |
| Nvidia                       | 1         | 0.26%   |
| Micron/Crucial Technology    | 1         | 0.26%   |
| ADATA Technology             | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 48        | 11.68%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 34        | 8.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 29        | 7.06%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 28        | 6.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 22        | 5.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 21        | 5.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 19        | 4.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 19        | 4.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 18        | 4.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 15        | 3.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 11        | 2.68%   |
| Samsung NVMe SSD Controller 980                                                        | 10        | 2.43%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 10        | 2.43%   |
| Micron Non-Volatile memory controller                                                  | 9         | 2.19%   |
| Intel SSD 660P Series                                                                  | 8         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 8         | 1.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 1.46%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 6         | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 1.46%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 5         | 1.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.22%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 4         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 4         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 4         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 4         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 0.97%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 3         | 0.73%   |
| SanDisk Non-Volatile memory controller                                                 | 3         | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 0.73%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.49%   |
| Phison PS5013 E13 NVMe Controller                                                      | 2         | 0.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.49%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.49%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.24%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 0.24%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.24%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 290       | 72.68%  |
| NVMe | 56        | 14.04%  |
| RAID | 39        | 9.77%   |
| IDE  | 14        | 3.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 322       | 91.22%  |
| AMD    | 31        | 8.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 20        | 5.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 14        | 3.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 3.12%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 2.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 9         | 2.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 2.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 2.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 1.98%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 7         | 1.98%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.98%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 1.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.42%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 1.42%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 5         | 1.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 1.42%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.42%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 4         | 1.13%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 1.13%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 1.13%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 1.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.13%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 4         | 1.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.85%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 3         | 0.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.85%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.85%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 0.85%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz          | 3         | 0.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.85%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.85%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.85%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.57%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.57%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 135       | 38.24%  |
| Intel Core i5           | 109       | 30.88%  |
| Intel Core i3           | 19        | 5.38%   |
| Other                   | 16        | 4.53%   |
| Intel Core 2 Duo        | 13        | 3.68%   |
| Intel Pentium           | 10        | 2.83%   |
| Intel Celeron           | 7         | 1.98%   |
| AMD Ryzen 7             | 7         | 1.98%   |
| Intel Atom              | 5         | 1.42%   |
| AMD FX                  | 4         | 1.13%   |
| Intel Pentium Dual-Core | 3         | 0.85%   |
| Intel Genuine           | 3         | 0.85%   |
| AMD Ryzen 5             | 3         | 0.85%   |
| AMD Ryzen 3             | 3         | 0.85%   |
| AMD A4                  | 3         | 0.85%   |
| AMD A10                 | 3         | 0.85%   |
| Intel Pentium Silver    | 2         | 0.57%   |
| AMD E1                  | 2         | 0.57%   |
| Intel Core M            | 1         | 0.28%   |
| AMD Ryzen 9             | 1         | 0.28%   |
| AMD PRO A8              | 1         | 0.28%   |
| AMD PRO A10             | 1         | 0.28%   |
| AMD E2                  | 1         | 0.28%   |
| AMD A6                  | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 201       | 56.94%  |
| 4      | 121       | 34.28%  |
| 6      | 14        | 3.97%   |
| 8      | 12        | 3.4%    |
| 1      | 3         | 0.85%   |
| 14     | 2         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 353       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 305       | 86.4%   |
| 1      | 48        | 13.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 342       | 96.61%  |
| Unknown        | 9         | 2.54%   |
| 32-bit         | 3         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 17.53%  |
| 0x306a9    | 33        | 9.04%   |
| 0x806ea    | 25        | 6.85%   |
| 0x306d4    | 23        | 6.3%    |
| 0x206a7    | 22        | 6.03%   |
| 0x20655    | 19        | 5.21%   |
| 0x306c3    | 16        | 4.38%   |
| 0x806e9    | 15        | 4.11%   |
| 0x806ec    | 13        | 3.56%   |
| 0x906e9    | 11        | 3.01%   |
| 0x40651    | 11        | 3.01%   |
| 0x1067a    | 10        | 2.74%   |
| 0x906ea    | 9         | 2.47%   |
| 0x406e3    | 9         | 2.47%   |
| 0x806c1    | 7         | 1.92%   |
| 0x506e3    | 7         | 1.92%   |
| 0x20652    | 6         | 1.64%   |
| 0xa0652    | 5         | 1.37%   |
| 0x106e5    | 5         | 1.37%   |
| 0x706e5    | 4         | 1.1%    |
| 0x706a1    | 4         | 1.1%    |
| 0x806d1    | 3         | 0.82%   |
| 0x6fd      | 3         | 0.82%   |
| 0x106ca    | 3         | 0.82%   |
| 0x0700010f | 3         | 0.82%   |
| 0x0600611a | 3         | 0.82%   |
| 0x906a3    | 2         | 0.55%   |
| 0x6e8      | 2         | 0.55%   |
| 0x30678    | 2         | 0.55%   |
| 0x10676    | 2         | 0.55%   |
| 0x08600104 | 2         | 0.55%   |
| 0x08108109 | 2         | 0.55%   |
| 0x06003109 | 2         | 0.55%   |
| 0x06003106 | 2         | 0.55%   |
| 0xa0660    | 1         | 0.27%   |
| 0x806eb    | 1         | 0.27%   |
| 0x6fb      | 1         | 0.27%   |
| 0x6fa      | 1         | 0.27%   |
| 0x506c9    | 1         | 0.27%   |
| 0x406c4    | 1         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 88        | 24.93%  |
| IvyBridge        | 39        | 11.05%  |
| Haswell          | 37        | 10.48%  |
| Westmere         | 27        | 7.65%   |
| SandyBridge      | 23        | 6.52%   |
| Broadwell        | 23        | 6.52%   |
| Skylake          | 19        | 5.38%   |
| Penryn           | 12        | 3.4%    |
| TigerLake        | 9         | 2.55%   |
| Icelake          | 7         | 1.98%   |
| Excavator        | 7         | 1.98%   |
| CometLake        | 7         | 1.98%   |
| Goldmont plus    | 6         | 1.7%    |
| Nehalem          | 5         | 1.42%   |
| Core             | 5         | 1.42%   |
| Unknown          | 5         | 1.42%   |
| Zen+             | 4         | 1.13%   |
| Zen 2            | 4         | 1.13%   |
| Steamroller      | 4         | 1.13%   |
| Silvermont       | 4         | 1.13%   |
| Bonnell          | 4         | 1.13%   |
| Jaguar           | 3         | 0.85%   |
| Zen 3            | 2         | 0.57%   |
| P6               | 2         | 0.57%   |
| Goldmont         | 2         | 0.57%   |
| Alderlake Hybrid | 2         | 0.57%   |
| Puma             | 1         | 0.28%   |
| K10 Llano        | 1         | 0.28%   |
| Bobcat           | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 291       | 51.05%  |
| Nvidia           | 185       | 32.46%  |
| AMD              | 93        | 16.32%  |
| ATI Technologies | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 36        | 6.21%   |
| Intel UHD Graphics 620                                                                | 28        | 4.83%   |
| Intel HD Graphics 5500                                                                | 21        | 3.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 21        | 3.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 21        | 3.62%   |
| Intel HD Graphics 620                                                                 | 19        | 3.28%   |
| Intel Core Processor Integrated Graphics Controller                                   | 17        | 2.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 15        | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 15        | 2.59%   |
| Intel HD Graphics 630                                                                 | 13        | 2.24%   |
| Nvidia GP108M [GeForce MX150]                                                         | 12        | 2.07%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 11        | 1.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 10        | 1.72%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 9         | 1.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 9         | 1.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 9         | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 9         | 1.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 1.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 1.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 8         | 1.38%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 8         | 1.38%   |
| Nvidia GP107M [GeForce MX350]                                                         | 7         | 1.21%   |
| Nvidia GM108M [GeForce MX110]                                                         | 7         | 1.21%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 7         | 1.21%   |
| Intel HD Graphics 530                                                                 | 7         | 1.21%   |
| Nvidia GM108M [GeForce 840M]                                                          | 6         | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 6         | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 0.86%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 5         | 0.86%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 5         | 0.86%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 5         | 0.86%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 5         | 0.86%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 5         | 0.86%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 0.69%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                     | 4         | 0.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 0.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 0.69%   |
| AMD Lucienne                                                                          | 4         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 159       | 45.04%  |
| 1 x Intel      | 81        | 22.95%  |
| Intel + AMD    | 50        | 14.16%  |
| 1 x AMD        | 30        | 8.5%    |
| 1 x Nvidia     | 19        | 5.38%   |
| 2 x AMD        | 7         | 1.98%   |
| AMD + Nvidia   | 7         | 1.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 270       | 75.42%  |
| Proprietary | 80        | 22.35%  |
| Unknown     | 8         | 2.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 161       | 44.6%   |
| 1.01-2.0   | 78        | 21.61%  |
| 3.01-4.0   | 51        | 14.13%  |
| 0.51-1.0   | 41        | 11.36%  |
| 0.01-0.5   | 24        | 6.65%   |
| 5.01-6.0   | 4         | 1.11%   |
| 7.01-8.0   | 1         | 0.28%   |
| 2.01-3.0   | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 76        | 20.6%   |
| LG Display              | 72        | 19.51%  |
| BOE                     | 54        | 14.63%  |
| Chimei Innolux          | 51        | 13.82%  |
| Samsung Electronics     | 43        | 11.65%  |
| Goldstar                | 15        | 4.07%   |
| Chi Mei Optoelectronics | 11        | 2.98%   |
| PANDA                   | 9         | 2.44%   |
| HannStar                | 5         | 1.36%   |
| BenQ                    | 4         | 1.08%   |
| Lenovo                  | 3         | 0.81%   |
| Sharp                   | 2         | 0.54%   |
| InnoLux Display         | 2         | 0.54%   |
| InfoVision              | 2         | 0.54%   |
| CHD                     | 2         | 0.54%   |
| Apple                   | 2         | 0.54%   |
| TMX                     | 1         | 0.27%   |
| Sony                    | 1         | 0.27%   |
| Seiko/Epson             | 1         | 0.27%   |
| Quanta Display          | 1         | 0.27%   |
| PAR                     | 1         | 0.27%   |
| Nvidia                  | 1         | 0.27%   |
| LGD                     | 1         | 0.27%   |
| LG Philips              | 1         | 0.27%   |
| KDC                     | 1         | 0.27%   |
| Hewlett-Packard         | 1         | 0.27%   |
| cPATH                   | 1         | 0.27%   |
| CHI                     | 1         | 0.27%   |
| AUS                     | 1         | 0.27%   |
| ASUSTek Computer        | 1         | 0.27%   |
| AOC                     | 1         | 0.27%   |
| Ancor Communications    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 2.97%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 8         | 2.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 7         | 1.89%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 7         | 1.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 1.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 5         | 1.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 1.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.35%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 4         | 1.08%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 4         | 1.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 1.08%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 1.08%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.81%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 3         | 0.81%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 3         | 0.81%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 3         | 0.81%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 3         | 0.81%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 3         | 0.81%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 3         | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 3         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.54%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.54%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.54%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 2         | 0.54%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 2         | 0.54%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 2         | 0.54%   |
| LG Display LCD Monitor LGD03E6 1366x768 345x194mm 15.6-inch              | 2         | 0.54%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 156       | 43.33%  |
| 1366x768 (WXGA)    | 143       | 39.72%  |
| 3840x2160 (4K)     | 13        | 3.61%   |
| 1600x900 (HD+)     | 11        | 3.06%   |
| 1440x900 (WXGA+)   | 10        | 2.78%   |
| 1280x800 (WXGA)    | 10        | 2.78%   |
| 1024x600           | 4         | 1.11%   |
| Unknown            | 3         | 0.83%   |
| 1680x1050 (WSXGA+) | 2         | 0.56%   |
| 5760x2160          | 1         | 0.28%   |
| 3840x2400          | 1         | 0.28%   |
| 3840x1080          | 1         | 0.28%   |
| 2944x1080          | 1         | 0.28%   |
| 2560x1440 (QHD)    | 1         | 0.28%   |
| 1920x1200 (WUXGA)  | 1         | 0.28%   |
| 1680x945           | 1         | 0.28%   |
| 1280x1024 (SXGA)   | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 233       | 63.66%  |
| 14      | 36        | 9.84%   |
| 13      | 30        | 8.2%    |
| 21      | 11        | 3.01%   |
| 12      | 11        | 3.01%   |
| 23      | 5         | 1.37%   |
| 17      | 5         | 1.37%   |
| 11      | 5         | 1.37%   |
| 10      | 5         | 1.37%   |
| Unknown | 5         | 1.37%   |
| 20      | 4         | 1.09%   |
| 18      | 4         | 1.09%   |
| 24      | 3         | 0.82%   |
| 27      | 2         | 0.55%   |
| 19      | 2         | 0.55%   |
| 16      | 2         | 0.55%   |
| 84      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| 22      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 291       | 79.51%  |
| 201-300     | 27        | 7.38%   |
| 401-500     | 22        | 6.01%   |
| 501-600     | 9         | 2.46%   |
| 351-400     | 9         | 2.46%   |
| Unknown     | 5         | 1.37%   |
| 701-800     | 1         | 0.27%   |
| 601-700     | 1         | 0.27%   |
| 1501-2000   | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 313       | 91.79%  |
| 16/10   | 21        | 6.16%   |
| Unknown | 5         | 1.47%   |
| 4/3     | 1         | 0.29%   |
| 3/2     | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 234       | 63.93%  |
| 81-90          | 60        | 16.39%  |
| 201-250        | 20        | 5.46%   |
| 61-70          | 11        | 3.01%   |
| 151-200        | 7         | 1.91%   |
| 51-60          | 5         | 1.37%   |
| 41-50          | 5         | 1.37%   |
| Unknown        | 5         | 1.37%   |
| 71-80          | 4         | 1.09%   |
| 121-130        | 4         | 1.09%   |
| 141-150        | 3         | 0.82%   |
| 301-350        | 2         | 0.55%   |
| 131-140        | 2         | 0.55%   |
| 91-100         | 2         | 0.55%   |
| More than 1000 | 1         | 0.27%   |
| 351-500        | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 164       | 45.56%  |
| 101-120       | 131       | 36.39%  |
| 51-100        | 47        | 13.06%  |
| More than 240 | 10        | 2.78%   |
| Unknown       | 5         | 1.39%   |
| 161-240       | 3         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 312       | 87.39%  |
| 2     | 35        | 9.8%    |
| 0     | 9         | 2.52%   |
| 3     | 1         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 212       | 35.45%  |
| Intel                    | 163       | 27.26%  |
| Qualcomm Atheros         | 95        | 15.89%  |
| Broadcom                 | 45        | 7.53%   |
| Broadcom Limited         | 15        | 2.51%   |
| Ralink                   | 13        | 2.17%   |
| Xiaomi                   | 9         | 1.51%   |
| Samsung Electronics      | 8         | 1.34%   |
| MediaTek                 | 7         | 1.17%   |
| Marvell Technology Group | 4         | 0.67%   |
| Huawei Technologies      | 4         | 0.67%   |
| JMicron Technology       | 3         | 0.5%    |
| HTC (High Tech Computer) | 3         | 0.5%    |
| Hewlett-Packard          | 3         | 0.5%    |
| TP-Link                  | 2         | 0.33%   |
| D-Link                   | 2         | 0.33%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 161       | 23.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 4.38%   |
| Intel Wireless 7265                                               | 22        | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 21        | 3.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 1.9%    |
| Intel Wireless 7260                                               | 13        | 1.9%    |
| Intel Wireless 8265 / 8275                                        | 12        | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 11        | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 8         | 1.17%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 1.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 1.02%   |
| Intel Wireless 8260                                               | 7         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 1.02%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.88%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.73%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.58%   |
| Intel Wireless 3165                                               | 4         | 0.58%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.58%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 161       | 45.1%   |
| Qualcomm Atheros      | 81        | 22.69%  |
| Realtek Semiconductor | 46        | 12.89%  |
| Broadcom              | 30        | 8.4%    |
| Ralink                | 13        | 3.64%   |
| Broadcom Limited      | 12        | 3.36%   |
| MediaTek              | 6         | 1.68%   |
| Hewlett-Packard       | 2         | 0.56%   |
| Xiaomi                | 1         | 0.28%   |
| TP-Link               | 1         | 0.28%   |
| Sierra Wireless       | 1         | 0.28%   |
| Ralink Technology     | 1         | 0.28%   |
| D-Link                | 1         | 0.28%   |
| BUFFALO               | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 22        | 6.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 21        | 5.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 4.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 3.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 3.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 3.62%   |
| Intel Wireless 7260                                            | 13        | 3.62%   |
| Intel Wireless 8265 / 8275                                     | 12        | 3.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 3.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 11        | 3.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 2.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 9         | 2.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.51%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 2.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 8         | 2.23%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 1.95%   |
| Intel Wireless 8260                                            | 7         | 1.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.95%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.39%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.11%   |
| Intel Wireless 3165                                            | 4         | 1.11%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.11%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.11%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.11%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 0.84%   |
| Intel Wireless 3160                                            | 3         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 0.84%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 3         | 0.84%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 193       | 59.57%  |
| Intel                    | 37        | 11.42%  |
| Qualcomm Atheros         | 28        | 8.64%   |
| Broadcom                 | 23        | 7.1%    |
| Xiaomi                   | 8         | 2.47%   |
| Samsung Electronics      | 8         | 2.47%   |
| Marvell Technology Group | 4         | 1.23%   |
| Huawei Technologies      | 4         | 1.23%   |
| JMicron Technology       | 3         | 0.93%   |
| HTC (High Tech Computer) | 3         | 0.93%   |
| Broadcom Limited         | 3         | 0.93%   |
| TP-Link                  | 1         | 0.31%   |
| Qualcomm                 | 1         | 0.31%   |
| MediaTek                 | 1         | 0.31%   |
| LG Electronics           | 1         | 0.31%   |
| Lenovo                   | 1         | 0.31%   |
| ICS Advent               | 1         | 0.31%   |
| Hewlett-Packard          | 1         | 0.31%   |
| D-Link                   | 1         | 0.31%   |
| Attansic Technology      | 1         | 0.31%   |
| ASIX Electronics         | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 161       | 49.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 30        | 9.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 3.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 8         | 2.46%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 7         | 2.15%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.54%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 1.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.23%   |
| Huawei LYA-L09                                                                 | 4         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 3         | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.92%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.92%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.92%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.92%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.62%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.62%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.62%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.62%   |
| Intel Ethernet Connection (16) I219-LM                                         | 2         | 0.62%   |
| HTC (High Tech Computer) HTC                                                   | 2         | 0.62%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.62%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.31%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.31%   |
| Qualcomm SDM845-BERYLLIUM _SN:CD5379A7                                         | 1         | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.31%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.31%   |
| MediaTek TECNO Pouvoir 3 Air                                                   | 1         | 0.31%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.31%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                            | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 349       | 53.69%  |
| Ethernet | 300       | 46.15%  |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 296       | 85.06%  |
| Ethernet | 51        | 14.66%  |
| Unknown  | 1         | 0.29%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 287       | 81.3%   |
| 1     | 65        | 18.41%  |
| 0     | 1         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 329       | 92.16%  |
| Yes  | 28        | 7.84%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 41.03%  |
| IMC Networks                    | 39        | 13.45%  |
| Qualcomm Atheros Communications | 24        | 8.28%   |
| Realtek Semiconductor           | 23        | 7.93%   |
| Broadcom                        | 15        | 5.17%   |
| Lite-On Technology              | 14        | 4.83%   |
| Foxconn / Hon Hai               | 14        | 4.83%   |
| Dell                            | 9         | 3.1%    |
| Ralink                          | 8         | 2.76%   |
| ASUSTek Computer                | 7         | 2.41%   |
| Foxconn International           | 4         | 1.38%   |
| Ralink Technology               | 3         | 1.03%   |
| Hewlett-Packard                 | 2         | 0.69%   |
| Cambridge Silicon Radio         | 2         | 0.69%   |
| Askey Computer                  | 2         | 0.69%   |
| Apple                           | 2         | 0.69%   |
| Realtek                         | 1         | 0.34%   |
| Micro Star International        | 1         | 0.34%   |
| MediaTek                        | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 65        | 22.41%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 19        | 6.55%   |
| Intel AX201 Bluetooth                                                               | 18        | 6.21%   |
| IMC Networks Bluetooth Radio                                                        | 18        | 6.21%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 4.48%   |
| Realtek Bluetooth Radio                                                             | 12        | 4.14%   |
| IMC Networks Bluetooth Device                                                       | 10        | 3.45%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 2.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.07%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 6         | 2.07%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.72%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.72%   |
| Intel AX200 Bluetooth                                                               | 5         | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.72%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 1.38%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 1.38%   |
| Broadcom BCM20702A0                                                                 | 4         | 1.38%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.03%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.03%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 1.03%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.03%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 1.03%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 1.03%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.69%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.69%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.69%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.69%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.69%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.69%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.69%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.69%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.69%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.69%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 320       | 75.12%  |
| Nvidia           | 57        | 13.38%  |
| AMD              | 45        | 10.56%  |
| ASUSTek Computer | 2         | 0.47%   |
| Yamaha           | 1         | 0.23%   |
| CMX Systems      | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 58        | 11.33%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 7.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 32        | 6.25%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 4.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 22        | 4.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 4.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20        | 3.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 2.93%   |
| Intel CM238 HD Audio Controller                                            | 15        | 2.93%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 2.93%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 2.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 2.34%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 2.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 1.95%   |
| AMD FCH Azalia Controller                                                  | 10        | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 1.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 1.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 1.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 7         | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 1.17%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 1.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 5         | 0.98%   |
| Nvidia GT216 HDMI Audio Controller                                         | 4         | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.78%   |
| Nvidia Audio device                                                        | 4         | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 0.78%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 4         | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.59%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 70        | 33.65%  |
| SK hynix            | 44        | 21.15%  |
| Micron Technology   | 29        | 13.94%  |
| Kingston            | 13        | 6.25%   |
| Crucial             | 13        | 6.25%   |
| Unknown             | 9         | 4.33%   |
| Ramaxel Technology  | 9         | 4.33%   |
| Elpida              | 9         | 4.33%   |
| A-DATA Technology   | 7         | 3.37%   |
| Transcend           | 1         | 0.48%   |
| Neo Forza           | 1         | 0.48%   |
| Nanya Technology    | 1         | 0.48%   |
| Kingmax             | 1         | 0.48%   |
| ASint Technology    | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 8         | 3.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 2.7%    |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s        | 6         | 2.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 5         | 2.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 2.25%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 5         | 2.25%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 5         | 2.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 4         | 1.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.8%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 4         | 1.8%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 4         | 1.8%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 1.35%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 1.35%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s    | 3         | 1.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 1.35%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 3         | 1.35%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 3         | 1.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.9%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 0.9%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.9%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 0.9%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2         | 0.9%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.9%    |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.9%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 2         | 0.9%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 2         | 0.9%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s    | 2         | 0.9%    |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.9%    |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s        | 2         | 0.9%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s        | 2         | 0.9%    |
| Kingston RAM ACR21D4S15HAG/8G 8192MB SODIMM DDR4 2133MT/s    | 2         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 77        | 46.67%  |
| DDR3    | 71        | 43.03%  |
| DDR2    | 6         | 3.64%   |
| SDRAM   | 4         | 2.42%   |
| LPDDR4  | 2         | 1.21%   |
| LPDDR3  | 2         | 1.21%   |
| DDR5    | 2         | 1.21%   |
| Unknown | 1         | 0.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 153       | 95.63%  |
| Row Of Chips | 6         | 3.75%   |
| Chip         | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 82        | 43.16%  |
| 8192  | 60        | 31.58%  |
| 2048  | 24        | 12.63%  |
| 16384 | 19        | 10%     |
| 1024  | 5         | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 53        | 28.34%  |
| 2667    | 41        | 21.93%  |
| 1334    | 20        | 10.7%   |
| 3200    | 16        | 8.56%   |
| 2400    | 12        | 6.42%   |
| 2133    | 11        | 5.88%   |
| 3266    | 8         | 4.28%   |
| 1333    | 5         | 2.67%   |
| 667     | 5         | 2.67%   |
| 4199    | 4         | 2.14%   |
| Unknown | 4         | 2.14%   |
| 8400    | 2         | 1.07%   |
| 4800    | 2         | 1.07%   |
| 1067    | 2         | 1.07%   |
| 1867    | 1         | 0.53%   |
| 800     | 1         | 0.53%   |

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
| Chicony Electronics                    | 75        | 22.73%  |
| IMC Networks                           | 73        | 22.12%  |
| Acer                                   | 34        | 10.3%   |
| Realtek Semiconductor                  | 27        | 8.18%   |
| Microdia                               | 22        | 6.67%   |
| Syntek                                 | 16        | 4.85%   |
| Sunplus Innovation Technology          | 14        | 4.24%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 3.64%   |
| Suyin                                  | 9         | 2.73%   |
| Lite-On Technology                     | 8         | 2.42%   |
| Sonix Technology                       | 6         | 1.82%   |
| Apple                                  | 6         | 1.82%   |
| Ricoh                                  | 5         | 1.52%   |
| Quanta                                 | 5         | 1.52%   |
| Samsung Electronics                    | 3         | 0.91%   |
| Lenovo                                 | 3         | 0.91%   |
| ALi                                    | 3         | 0.91%   |
| Pixart Imaging                         | 2         | 0.61%   |
| Alcor Micro                            | 2         | 0.61%   |
| Primax Electronics                     | 1         | 0.3%    |
| OmniVision Technologies                | 1         | 0.3%    |
| Luxvisions Innotech Limited            | 1         | 0.3%    |
| LG Electronics                         | 1         | 0.3%    |
| Importek                               | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                       | 30        | 9.09%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 14        | 4.24%   |
| IMC Networks Integrated Camera                                           | 11        | 3.33%   |
| Acer Lenovo EasyCamera                                                   | 11        | 3.33%   |
| Chicony integrated camera                                                | 9         | 2.73%   |
| Chicony HD WebCam                                                        | 8         | 2.42%   |
| Chicony EasyCamera                                                       | 8         | 2.42%   |
| Chicony USB2.0 HD UVC WebCam                                             | 7         | 2.12%   |
| Syntek EasyCamera                                                        | 6         | 1.82%   |
| Realtek USB Camera                                                       | 6         | 1.82%   |
| IMC Networks Lenovo EasyCamera                                           | 6         | 1.82%   |
| Acer Integrated Camera                                                   | 6         | 1.82%   |
| Syntek Lenovo EasyCamera                                                 | 5         | 1.52%   |
| Sunplus HD WebCam                                                        | 5         | 1.52%   |
| Sonix USB2.0 HD UVC WebCam                                               | 5         | 1.52%   |
| Chicony HP HD Webcam                                                     | 5         | 1.52%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 5         | 1.52%   |
| Syntek Integrated Camera                                                 | 4         | 1.21%   |
| Sunplus Asus Webcam                                                      | 4         | 1.21%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 4         | 1.21%   |
| Realtek USB2.0 HD UVC WebCam                                             | 4         | 1.21%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 4         | 1.21%   |
| Microdia Integrated_Webcam_HD                                            | 4         | 1.21%   |
| Lite-On Integrated Camera                                                | 4         | 1.21%   |
| Chicony Integrated HP HD Webcam                                          | 4         | 1.21%   |
| Chicony HP HD Webcam [Fixed]                                             | 4         | 1.21%   |
| Acer Lenovo Integrated Webcam                                            | 4         | 1.21%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 3         | 0.91%   |
| Microdia Sonix Integrated Webcam                                         | 3         | 0.91%   |
| Microdia Integrated Webcam                                               | 3         | 0.91%   |
| Lite-On HP HD Camera                                                     | 3         | 0.91%   |
| IMC Networks VGA UVC WebCam                                              | 3         | 0.91%   |
| IMC Networks Integrated Webcam                                           | 3         | 0.91%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 3         | 0.91%   |
| Chicony 1.3M HD WebCam                                                   | 3         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 3         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 3         | 0.91%   |
| ALi Gateway Webcam                                                       | 3         | 0.91%   |
| Acer SunplusIT Integrated Camera                                         | 3         | 0.91%   |
| Acer HD Webcam                                                           | 3         | 0.91%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 32        | 39.51%  |
| Shenzhen Goodix Technology | 13        | 16.05%  |
| Elan Microelectronics      | 10        | 12.35%  |
| Upek                       | 9         | 11.11%  |
| Synaptics                  | 9         | 11.11%  |
| AuthenTec                  | 4         | 4.94%   |
| LighTuning Technology      | 3         | 3.7%    |
| STMicroelectronics         | 1         | 1.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 14        | 17.28%  |
| Elan ELAN:Fingerprint                                  | 10        | 12.35%  |
| Validity Sensors VFS491                                | 9         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                    | 9         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 8         | 9.88%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 3.7%    |
| Synaptics  WBDI                                        | 3         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 3.7%    |
| Unknown                                                | 3         | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 2.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 2.47%   |
| LighTuning EgisTec_ES603                               | 2         | 2.47%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 2.47%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 1.23%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 1.23%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 1.23%   |
| Validity Sensors Fingerprint scanner                   | 1         | 1.23%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 1.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 1.23%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 1.23%   |
| Shenzhen Goodix FingerPrint                            | 1         | 1.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 1.23%   |
| AuthenTec Fingerprint Sensor                           | 1         | 1.23%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 1.23%   |

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
| 0     | 210       | 58.01%  |
| 1     | 112       | 30.94%  |
| 2     | 33        | 9.12%   |
| 3     | 4         | 1.1%    |
| 7     | 1         | 0.28%   |
| 5     | 1         | 0.28%   |
| 4     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 81        | 41.33%  |
| Graphics card            | 54        | 27.55%  |
| Bluetooth                | 14        | 7.14%   |
| Chipcard                 | 13        | 6.63%   |
| Net/wireless             | 12        | 6.12%   |
| Camera                   | 6         | 3.06%   |
| Communication controller | 5         | 2.55%   |
| Storage                  | 4         | 2.04%   |
| Sound                    | 2         | 1.02%   |
| Card reader              | 2         | 1.02%   |
| Wireless                 | 1         | 0.51%   |
| Net/ethernet             | 1         | 0.51%   |
| Multimedia controller    | 1         | 0.51%   |

