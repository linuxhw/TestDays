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

Total: 510

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Acer          | Aspire F5-573G              | [5e41143d4b](https://linux-hardware.org/?probe=5e41143d4b) | Sep 07, 2021 |
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
| ASUSTek       | N53SV                       | [e26beeead1](https://linux-hardware.org/?probe=e26beeead1) | Jun 06, 2021 |
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
| Lenovo        | ThinkPad E15 20RD001SUE     | [0bee28efd1](https://linux-hardware.org/?probe=0bee28efd1) | Feb 12, 2021 |
| Lenovo        | Flex 2-15 20405             | [ee986e1fdd](https://linux-hardware.org/?probe=ee986e1fdd) | Feb 11, 2021 |
| Lenovo        | Flex 2-15 20405             | [b661aa21f1](https://linux-hardware.org/?probe=b661aa21f1) | Feb 09, 2021 |
| Acer          | Aspire E5-553G              | [0c9067579c](https://linux-hardware.org/?probe=0c9067579c) | Feb 09, 2021 |
| Lenovo        | Z50-70 20354                | [ab4bc22a87](https://linux-hardware.org/?probe=ab4bc22a87) | Feb 06, 2021 |
| Acer          | Aspire E5-553G              | [5e9aa1c3de](https://linux-hardware.org/?probe=5e9aa1c3de) | Feb 06, 2021 |
| Lenovo        | Flex 2-15 20405             | [6eb46ce36e](https://linux-hardware.org/?probe=6eb46ce36e) | Feb 06, 2021 |
| ASUSTek       | X456URK                     | [6c3b5bdfb1](https://linux-hardware.org/?probe=6c3b5bdfb1) | Feb 05, 2021 |
| Dell          | Inspiron N4010              | [d383b4a5e7](https://linux-hardware.org/?probe=d383b4a5e7) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | [2bd7b5699d](https://linux-hardware.org/?probe=2bd7b5699d) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | [82920966cf](https://linux-hardware.org/?probe=82920966cf) | Feb 01, 2021 |
| Lenovo        | Flex 2-15 20405             | [d82031935e](https://linux-hardware.org/?probe=d82031935e) | Feb 01, 2021 |
| ASUSTek       | N56JR                       | [29ad612f88](https://linux-hardware.org/?probe=29ad612f88) | Jan 28, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [2960ce1b31](https://linux-hardware.org/?probe=2960ce1b31) | Jan 27, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [b97b822412](https://linux-hardware.org/?probe=b97b822412) | Jan 27, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | [5db899a153](https://linux-hardware.org/?probe=5db899a153) | Jan 21, 2021 |
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
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [7db1dd5f36](https://linux-hardware.org/?probe=7db1dd5f36) | Nov 17, 2020 |
| Acer          | TravelMate 5742Z            | [be124397e2](https://linux-hardware.org/?probe=be124397e2) | Nov 13, 2020 |
| Acer          | TravelMate 5742Z            | [ecfcb44af2](https://linux-hardware.org/?probe=ecfcb44af2) | Nov 13, 2020 |
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
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [bd5a35063e](https://linux-hardware.org/?probe=bd5a35063e) | Oct 24, 2020 |
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
| HP            | EliteBook 725 G2            | [b46ffda49e](https://linux-hardware.org/?probe=b46ffda49e) | Sep 26, 2020 |
| ASUSTek       | K42Jc                       | [9808a6bb0c](https://linux-hardware.org/?probe=9808a6bb0c) | Sep 25, 2020 |
| Sony          | VPCSB36FG                   | [5ea9c0eca9](https://linux-hardware.org/?probe=5ea9c0eca9) | Sep 24, 2020 |
| HP            | EliteBook 725 G2            | [9456172087](https://linux-hardware.org/?probe=9456172087) | Sep 18, 2020 |
| ASUSTek       | N501VW                      | [36d0455f5f](https://linux-hardware.org/?probe=36d0455f5f) | Sep 15, 2020 |
| Sony          | VPCSB36FG                   | [5ed2d21f85](https://linux-hardware.org/?probe=5ed2d21f85) | Sep 05, 2020 |
| Sony          | VPCSB36FG                   | [d274f87a7c](https://linux-hardware.org/?probe=d274f87a7c) | Sep 05, 2020 |
| ASUSTek       | K52F                        | [1658b8903d](https://linux-hardware.org/?probe=1658b8903d) | Sep 04, 2020 |
| ASUSTek       | K52F                        | [b7a5d27a01](https://linux-hardware.org/?probe=b7a5d27a01) | Sep 04, 2020 |
| ASUSTek       | K42Jc                       | [79d7ee2e74](https://linux-hardware.org/?probe=79d7ee2e74) | Sep 04, 2020 |
| Sony          | VPCSB36FG                   | [e0f1342fa2](https://linux-hardware.org/?probe=e0f1342fa2) | Sep 04, 2020 |
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
| Acer          | TravelMate 5742Z            | [bd5a268ec9](https://linux-hardware.org/?probe=bd5a268ec9) | Jul 05, 2020 |
| Acer          | TravelMate 5742Z            | [de25d26410](https://linux-hardware.org/?probe=de25d26410) | Jul 05, 2020 |
| Acer          | Aspire V5-561G              | [81b19839f7](https://linux-hardware.org/?probe=81b19839f7) | Jul 02, 2020 |
| Acer          | Aspire 5755G                | [f70e4485bc](https://linux-hardware.org/?probe=f70e4485bc) | Jun 28, 2020 |
| ASUSTek       | N56JN                       | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| ASUSTek       | X580VD                      | [1ad8491ca0](https://linux-hardware.org/?probe=1ad8491ca0) | Jun 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [376ebf1819](https://linux-hardware.org/?probe=376ebf1819) | Jun 14, 2020 |
| Acer          | Aspire F5-573G              | [56a1c895ee](https://linux-hardware.org/?probe=56a1c895ee) | Jun 07, 2020 |
| Acer          | Aspire V5-572G              | [4a67c5fabb](https://linux-hardware.org/?probe=4a67c5fabb) | Jun 03, 2020 |
| ASUSTek       | X510UQR                     | [8fd66dd600](https://linux-hardware.org/?probe=8fd66dd600) | Jun 01, 2020 |
| ASUSTek       | X510UQR                     | [fbd9ae49c7](https://linux-hardware.org/?probe=fbd9ae49c7) | Jun 01, 2020 |
| Acer          | Aspire V5-572G              | [bc4f3efb0d](https://linux-hardware.org/?probe=bc4f3efb0d) | May 31, 2020 |
| Dell          | Inspiron N5110              | [d059aa2096](https://linux-hardware.org/?probe=d059aa2096) | May 29, 2020 |
| Sony          | VGN-SR165E                  | [ee7e382325](https://linux-hardware.org/?probe=ee7e382325) | May 27, 2020 |
| Lenovo        | G580 20157                  | [639a8b36be](https://linux-hardware.org/?probe=639a8b36be) | May 23, 2020 |
| Lenovo        | G580 20157                  | [bdb6ac04cd](https://linux-hardware.org/?probe=bdb6ac04cd) | May 23, 2020 |
| Lenovo        | G580 20157                  | [4dc19e43eb](https://linux-hardware.org/?probe=4dc19e43eb) | May 23, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [870f5869a0](https://linux-hardware.org/?probe=870f5869a0) | May 22, 2020 |
| Lenovo        | G580 20157                  | [99334e430e](https://linux-hardware.org/?probe=99334e430e) | May 22, 2020 |
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
| Lenovo        | ThinkPad SL400 2743A14      | [fb56e66f65](https://linux-hardware.org/?probe=fb56e66f65) | Apr 24, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| Apple         | MacBookAir7,2               | [680bbeabad](https://linux-hardware.org/?probe=680bbeabad) | Apr 24, 2020 |
| HP            | Pavilion g6                 | [66ba3bc59b](https://linux-hardware.org/?probe=66ba3bc59b) | Apr 23, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [82f761db09](https://linux-hardware.org/?probe=82f761db09) | Apr 23, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [6a497a24cf](https://linux-hardware.org/?probe=6a497a24cf) | Apr 22, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [ef022bd88d](https://linux-hardware.org/?probe=ef022bd88d) | Apr 22, 2020 |
| Lenovo        | ThinkPad E480 20KN007XAD    | [8310d15c91](https://linux-hardware.org/?probe=8310d15c91) | Apr 18, 2020 |
| Lenovo        | IdeaPad Z510 20287          | [74699b5097](https://linux-hardware.org/?probe=74699b5097) | Apr 16, 2020 |
| Lenovo        | G505 20240                  | [93a89841fd](https://linux-hardware.org/?probe=93a89841fd) | Apr 12, 2020 |
| ASUSTek       | X550IU                      | [943b36ee80](https://linux-hardware.org/?probe=943b36ee80) | Apr 10, 2020 |
| Sony          | VPCEH11FX                   | [0e78768f7e](https://linux-hardware.org/?probe=0e78768f7e) | Apr 09, 2020 |
| Sony          | VPCEH11FX                   | [e0ef96682b](https://linux-hardware.org/?probe=e0ef96682b) | Apr 09, 2020 |
| ASUSTek       | G750JH                      | [45a70fa311](https://linux-hardware.org/?probe=45a70fa311) | Apr 08, 2020 |
| ASUSTek       | G750JH                      | [3314aa590e](https://linux-hardware.org/?probe=3314aa590e) | Apr 08, 2020 |
| Dell          | Latitude D630               | [98199f8421](https://linux-hardware.org/?probe=98199f8421) | Apr 07, 2020 |
| Lenovo        | Z50-70 20354                | [839c8344be](https://linux-hardware.org/?probe=839c8344be) | Apr 07, 2020 |
| ASUSTek       | 1015CX                      | [c98f5bcee3](https://linux-hardware.org/?probe=c98f5bcee3) | Apr 05, 2020 |
| ASUSTek       | 1015CX                      | [9a8c75a874](https://linux-hardware.org/?probe=9a8c75a874) | Apr 05, 2020 |
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
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a5e0e391e6](https://linux-hardware.org/?probe=a5e0e391e6) | Mar 06, 2020 |
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
| Dell          | Inspiron N5040              | [31f9126345](https://linux-hardware.org/?probe=31f9126345) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| ASUSTek       | X542UN                      | [4b7f71d936](https://linux-hardware.org/?probe=4b7f71d936) | Dec 14, 2019 |
| Lenovo        | G50-70 20351                | [f30b5e8075](https://linux-hardware.org/?probe=f30b5e8075) | Dec 09, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [15babe41d0](https://linux-hardware.org/?probe=15babe41d0) | Nov 26, 2019 |
| ASUSTek       | B9440UA                     | [ed7fb8cbb9](https://linux-hardware.org/?probe=ed7fb8cbb9) | Nov 15, 2019 |
| ASUSTek       | B9440UA                     | [5e184acc59](https://linux-hardware.org/?probe=5e184acc59) | Nov 15, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [f13de25d56](https://linux-hardware.org/?probe=f13de25d56) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dda0a53712](https://linux-hardware.org/?probe=dda0a53712) | Nov 14, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [cc275f622e](https://linux-hardware.org/?probe=cc275f622e) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b86e3d7141](https://linux-hardware.org/?probe=b86e3d7141) | Nov 13, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5e5c671b90](https://linux-hardware.org/?probe=5e5c671b90) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| HP            | Pavilion 15                 | [57540edaa7](https://linux-hardware.org/?probe=57540edaa7) | Nov 12, 2019 |
| ASUSTek       | B9440UA                     | [b6aec97c45](https://linux-hardware.org/?probe=b6aec97c45) | Nov 11, 2019 |
| ASUSTek       | B9440UA                     | [2831200d03](https://linux-hardware.org/?probe=2831200d03) | Nov 11, 2019 |
| ASUSTek       | B9440UA                     | [e1c1659815](https://linux-hardware.org/?probe=e1c1659815) | Nov 11, 2019 |
| ASUSTek       | B9440UA                     | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [fa64448e42](https://linux-hardware.org/?probe=fa64448e42) | Nov 02, 2019 |
| Dell          | Vostro 1520                 | [247d9e9c2f](https://linux-hardware.org/?probe=247d9e9c2f) | Nov 01, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [797965c573](https://linux-hardware.org/?probe=797965c573) | Oct 30, 2019 |
| Dell          | Vostro 1015                 | [400532e714](https://linux-hardware.org/?probe=400532e714) | Oct 24, 2019 |
| Dell          | Vostro 1015                 | [69a361083a](https://linux-hardware.org/?probe=69a361083a) | Oct 24, 2019 |
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
| Lenovo        | G50-70 20351                | [626c154f14](https://linux-hardware.org/?probe=626c154f14) | Sep 20, 2019 |
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
| MSI           | MS-1454                     | [0b7cec4302](https://linux-hardware.org/?probe=0b7cec4302) | Aug 23, 2019 |
| MSI           | MS-1454                     | [94bfc26599](https://linux-hardware.org/?probe=94bfc26599) | Aug 23, 2019 |
| ASUSTek       | X540UPR                     | [2f40c492db](https://linux-hardware.org/?probe=2f40c492db) | Aug 12, 2019 |
| Lenovo        | ThinkPad X201 3249CTO       | [24c83ab728](https://linux-hardware.org/?probe=24c83ab728) | Aug 09, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | [2507713bd4](https://linux-hardware.org/?probe=2507713bd4) | Aug 06, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | [0ad209e005](https://linux-hardware.org/?probe=0ad209e005) | Aug 06, 2019 |
| ASUSTek       | X555LJ                      | [541fb4f240](https://linux-hardware.org/?probe=541fb4f240) | Aug 06, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [2ab556fd2e](https://linux-hardware.org/?probe=2ab556fd2e) | Aug 03, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [eeab344604](https://linux-hardware.org/?probe=eeab344604) | Aug 03, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [968eabb533](https://linux-hardware.org/?probe=968eabb533) | Aug 01, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [081a6a81f6](https://linux-hardware.org/?probe=081a6a81f6) | Aug 01, 2019 |
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
| Ubuntu 20.04                 | 65        | 19.76%  |
| Ubuntu 18.04                 | 54        | 16.41%  |
| Fedora 33                    | 13        | 3.95%   |
| Arch                         | 12        | 3.65%   |
| Ubuntu 19.04                 | 10        | 3.04%   |
| Fedora 34                    | 8         | 2.43%   |
| Arch Rolling                 | 8         | 2.43%   |
| Ubuntu 20.10                 | 7         | 2.13%   |
| Ubuntu 19.10                 | 6         | 1.82%   |
| KDE neon 20.04               | 6         | 1.82%   |
| Xubuntu 18.04                | 5         | 1.52%   |
| Ubuntu 21.10                 | 5         | 1.52%   |
| Ubuntu 21.04                 | 5         | 1.52%   |
| OpenMandriva 4.2             | 5         | 1.52%   |
| Ubuntu 18.10                 | 4         | 1.22%   |
| Manjaro                      | 4         | 1.22%   |
| Fedora 35                    | 4         | 1.22%   |
| Ubuntu Budgie 20.04          | 3         | 0.91%   |
| Linux Mint 20.2              | 3         | 0.91%   |
| Linux Mint 19.3              | 3         | 0.91%   |
| Kubuntu 20.04                | 3         | 0.91%   |
| Kali 2021.2                  | 3         | 0.91%   |
| Fedora 31                    | 3         | 0.91%   |
| Debian 11                    | 3         | 0.91%   |
| Zorin 15                     | 2         | 0.61%   |
| Xubuntu 20.04                | 2         | 0.61%   |
| Ubuntu 17.10                 | 2         | 0.61%   |
| ROSA R11                     | 2         | 0.61%   |
| Pop!_OS 21.10                | 2         | 0.61%   |
| Pop!_OS 20.04                | 2         | 0.61%   |
| Manjaro 20.2.1               | 2         | 0.61%   |
| Manjaro 20.2                 | 2         | 0.61%   |
| Linux Mint 20.3              | 2         | 0.61%   |
| Kubuntu 19.10                | 2         | 0.61%   |
| KDE neon 18.04               | 2         | 0.61%   |
| Kali 2022.1                  | 2         | 0.61%   |
| Kali 2021.3                  | 2         | 0.61%   |
| Gentoo 2.6                   | 2         | 0.61%   |
| Endless 3.8.3-nexthw1        | 2         | 0.61%   |
| Endless 3.8.0                | 2         | 0.61%   |
| Endless 3.3.20-nexthw1       | 2         | 0.61%   |
| Endless 3.3.19               | 2         | 0.61%   |
| Debian 10                    | 2         | 0.61%   |
| ArcoLinux Rolling            | 2         | 0.61%   |
| Ubuntu MATE 18.04            | 1         | 0.3%    |
| Ubuntu 16.04                 | 1         | 0.3%    |
| Solus 4.0                    | 1         | 0.3%    |
| Sabayon                      | 1         | 0.3%    |
| ROSA R10                     | 1         | 0.3%    |
| PureOS 10.0                  | 1         | 0.3%    |
| Pop!_OS 21.04                | 1         | 0.3%    |
| Pop!_OS 20.10                | 1         | 0.3%    |
| openSUSE Tumbleweed-20200528 | 1         | 0.3%    |
| openSUSE Tumbleweed-20200520 | 1         | 0.3%    |
| openSUSE Leap-15.1           | 1         | 0.3%    |
| openSUSE 20201012            | 1         | 0.3%    |
| OpenMandriva 4.50            | 1         | 0.3%    |
| OpenMandriva 4.3             | 1         | 0.3%    |
| NixOS 21.11                  | 1         | 0.3%    |
| Manjaro 21.2.1               | 1         | 0.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 155       | 49.21%  |
| Fedora        | 28        | 8.89%   |
| Arch          | 18        | 5.71%   |
| Manjaro       | 15        | 4.76%   |
| Endless       | 14        | 4.44%   |
| Linux Mint    | 11        | 3.49%   |
| Kubuntu       | 9         | 2.86%   |
| KDE neon      | 8         | 2.54%   |
| Kali          | 8         | 2.54%   |
| Xubuntu       | 7         | 2.22%   |
| OpenMandriva  | 7         | 2.22%   |
| Pop!_OS       | 5         | 1.59%   |
| Debian        | 5         | 1.59%   |
| Ubuntu Budgie | 3         | 0.95%   |
| ROSA          | 3         | 0.95%   |
| openSUSE      | 3         | 0.95%   |
| Zorin         | 2         | 0.63%   |
| Gentoo        | 2         | 0.63%   |
| ArcoLinux     | 2         | 0.63%   |
| Ubuntu MATE   | 1         | 0.32%   |
| Solus         | 1         | 0.32%   |
| Sabayon       | 1         | 0.32%   |
| PureOS        | 1         | 0.32%   |
| NixOS         | 1         | 0.32%   |
| Lubuntu       | 1         | 0.32%   |
| Elementary    | 1         | 0.32%   |
| Deepin        | 1         | 0.32%   |
| Clear Linux   | 1         | 0.32%   |
| CentOS        | 1         | 0.32%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 3.45%   |
| 5.3.0-46-generic         | 7         | 2.01%   |
| 5.4.0-26-generic         | 6         | 1.72%   |
| 5.8.0-63-generic         | 5         | 1.44%   |
| 5.4.0-52-generic         | 5         | 1.44%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.44%   |
| 5.0.0-13-generic         | 5         | 1.44%   |
| 5.8.0-48-generic         | 4         | 1.15%   |
| 5.4.0-58-generic         | 4         | 1.15%   |
| 5.3.0-40-generic         | 4         | 1.15%   |
| 5.11.0-41-generic        | 4         | 1.15%   |
| 5.11.0-27-generic        | 4         | 1.15%   |
| 5.0.0-23-generic         | 4         | 1.15%   |
| 4.18.0-25-generic        | 4         | 1.15%   |
| 4.18.0-15-generic        | 4         | 1.15%   |
| 5.8.0-59-generic         | 3         | 0.86%   |
| 5.4.0-40-generic         | 3         | 0.86%   |
| 5.3.0-51-generic         | 3         | 0.86%   |
| 5.13.0-22-generic        | 3         | 0.86%   |
| 5.0.0-37-generic         | 3         | 0.86%   |
| 5.0.0-25-generic         | 3         | 0.86%   |
| 4.18.0-16-generic        | 3         | 0.86%   |
| 4.15.0-15-generic        | 3         | 0.86%   |
| 5.9.16-1-MANJARO         | 2         | 0.57%   |
| 5.8.18-1-MANJARO         | 2         | 0.57%   |
| 5.8.0-50-generic         | 2         | 0.57%   |
| 5.8.0-43-generic         | 2         | 0.57%   |
| 5.8.0-41-generic         | 2         | 0.57%   |
| 5.8.0-14-generic         | 2         | 0.57%   |
| 5.6.0-7-generic          | 2         | 0.57%   |
| 5.4.0-91-generic         | 2         | 0.57%   |
| 5.4.0-73-generic         | 2         | 0.57%   |
| 5.4.0-72-generic         | 2         | 0.57%   |
| 5.4.0-65-generic         | 2         | 0.57%   |
| 5.4.0-59-generic         | 2         | 0.57%   |
| 5.4.0-54-generic         | 2         | 0.57%   |
| 5.4.0-51-generic         | 2         | 0.57%   |
| 5.4.0-31-generic         | 2         | 0.57%   |
| 5.4.0-29-generic         | 2         | 0.57%   |
| 5.4.0-19-generic         | 2         | 0.57%   |
| 5.3.0-42-generic         | 2         | 0.57%   |
| 5.3.0-28-generic         | 2         | 0.57%   |
| 5.3.0-18-generic         | 2         | 0.57%   |
| 5.14.16-arch1-1          | 2         | 0.57%   |
| 5.13.19-2-MANJARO        | 2         | 0.57%   |
| 5.13.0-39-generic        | 2         | 0.57%   |
| 5.13.0-30-generic        | 2         | 0.57%   |
| 5.11.11-200.fc33.x86_64  | 2         | 0.57%   |
| 5.11.0-43-generic        | 2         | 0.57%   |
| 5.11.0-38-generic        | 2         | 0.57%   |
| 5.10.0-kali9-amd64       | 2         | 0.57%   |
| 5.10.0-kali7-amd64       | 2         | 0.57%   |
| 5.0.0-32-generic         | 2         | 0.57%   |
| 5.0.0-31-generic         | 2         | 0.57%   |
| 5.0.0-27-generic         | 2         | 0.57%   |
| 5.0.0-21-generic         | 2         | 0.57%   |
| 4.18.0-21-generic        | 2         | 0.57%   |
| 4.18.0-18-generic        | 2         | 0.57%   |
| 4.18.0-17-generic        | 2         | 0.57%   |
| 4.15.0-58-generic        | 2         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 20.36%  |
| 5.0.0   | 26        | 7.78%   |
| 5.3.0   | 24        | 7.19%   |
| 5.8.0   | 23        | 6.89%   |
| 4.15.0  | 23        | 6.89%   |
| 5.11.0  | 22        | 6.59%   |
| 4.18.0  | 18        | 5.39%   |
| 5.13.0  | 11        | 3.29%   |
| 5.10.0  | 8         | 2.4%    |
| 5.10.14 | 5         | 1.5%    |
| 5.11.11 | 4         | 1.2%    |
| 4.13.0  | 4         | 1.2%    |
| 5.9.16  | 3         | 0.9%    |
| 5.8.18  | 3         | 0.9%    |
| 5.6.0   | 3         | 0.9%    |
| 5.16.15 | 3         | 0.9%    |
| 5.14.16 | 3         | 0.9%    |
| 5.13.19 | 3         | 0.9%    |
| 5.7.0   | 2         | 0.6%    |
| 5.3.7   | 2         | 0.6%    |
| 5.16.7  | 2         | 0.6%    |
| 5.15.4  | 2         | 0.6%    |
| 5.13.7  | 2         | 0.6%    |
| 5.13.13 | 2         | 0.6%    |
| 5.12.8  | 2         | 0.6%    |
| 5.9.14  | 1         | 0.3%    |
| 5.9.11  | 1         | 0.3%    |
| 5.8.4   | 1         | 0.3%    |
| 5.8.16  | 1         | 0.3%    |
| 5.8.15  | 1         | 0.3%    |
| 5.8.14  | 1         | 0.3%    |
| 5.8.13  | 1         | 0.3%    |
| 5.7.6   | 1         | 0.3%    |
| 5.6.17  | 1         | 0.3%    |
| 5.6.14  | 1         | 0.3%    |
| 5.6.12  | 1         | 0.3%    |
| 5.6.10  | 1         | 0.3%    |
| 5.5.8   | 1         | 0.3%    |
| 5.5.13  | 1         | 0.3%    |
| 5.4.8   | 1         | 0.3%    |
| 5.4.28  | 1         | 0.3%    |
| 5.4.23  | 1         | 0.3%    |
| 5.4.2   | 1         | 0.3%    |
| 5.4.17  | 1         | 0.3%    |
| 5.4.12  | 1         | 0.3%    |
| 5.2.2   | 1         | 0.3%    |
| 5.16.18 | 1         | 0.3%    |
| 5.16.14 | 1         | 0.3%    |
| 5.16.11 | 1         | 0.3%    |
| 5.16.1  | 1         | 0.3%    |
| 5.16.0  | 1         | 0.3%    |
| 5.15.8  | 1         | 0.3%    |
| 5.15.34 | 1         | 0.3%    |
| 5.15.32 | 1         | 0.3%    |
| 5.15.26 | 1         | 0.3%    |
| 5.14.9  | 1         | 0.3%    |
| 5.14.20 | 1         | 0.3%    |
| 5.14.15 | 1         | 0.3%    |
| 5.14.13 | 1         | 0.3%    |
| 5.14.12 | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 73        | 22.05%  |
| 5.8     | 31        | 9.37%   |
| 5.11    | 30        | 9.06%   |
| 5.0     | 28        | 8.46%   |
| 5.3     | 26        | 7.85%   |
| 4.15    | 23        | 6.95%   |
| 5.10    | 22        | 6.65%   |
| 5.13    | 19        | 5.74%   |
| 4.18    | 18        | 5.44%   |
| 5.16    | 10        | 3.02%   |
| 5.14    | 9         | 2.72%   |
| 5.6     | 6         | 1.81%   |
| 5.15    | 6         | 1.81%   |
| 5.12    | 6         | 1.81%   |
| 5.9     | 5         | 1.51%   |
| 4.13    | 4         | 1.21%   |
| 5.7     | 3         | 0.91%   |
| 4.19    | 3         | 0.91%   |
| 5.5     | 2         | 0.6%    |
| 5.2     | 1         | 0.3%    |
| 4.9     | 1         | 0.3%    |
| 4.5     | 1         | 0.3%    |
| 4.20    | 1         | 0.3%    |
| 4.14    | 1         | 0.3%    |
| 4.12    | 1         | 0.3%    |
| 3.10    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 304       | 98.06%  |
| i686   | 6         | 1.94%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 157       | 49.22%  |
| Unknown         | 71        | 22.26%  |
| KDE5            | 24        | 7.52%   |
| XFCE            | 20        | 6.27%   |
| KDE             | 17        | 5.33%   |
| X-Cinnamon      | 7         | 2.19%   |
| MATE            | 5         | 1.57%   |
| i3              | 4         | 1.25%   |
| Unity           | 3         | 0.94%   |
| Budgie          | 3         | 0.94%   |
| LXQt            | 2         | 0.63%   |
| Trinity         | 1         | 0.31%   |
| sway            | 1         | 0.31%   |
| Pantheon        | 1         | 0.31%   |
| KDE4            | 1         | 0.31%   |
| GNOME Flashback | 1         | 0.31%   |
| bspwm           | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 234       | 73.13%  |
| Unknown | 48        | 15%     |
| Wayland | 35        | 10.94%  |
| Tty     | 3         | 0.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 207       | 63.89%  |
| GDM     | 52        | 16.05%  |
| SDDM    | 25        | 7.72%   |
| LightDM | 15        | 4.63%   |
| TDM     | 11        | 3.4%    |
| GDM3    | 11        | 3.4%    |
| XDM     | 1         | 0.31%   |
| Ly      | 1         | 0.31%   |
| KDM     | 1         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 224       | 70.89%  |
| Unknown | 68        | 21.52%  |
| en_GB   | 7         | 2.22%   |
| fa_IR   | 6         | 1.9%    |
| C       | 4         | 1.27%   |
| en_CA   | 3         | 0.95%   |
| POSIX   | 1         | 0.32%   |
| ja_JP   | 1         | 0.32%   |
| de_DE   | 1         | 0.32%   |
| az_IR   | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 179       | 55.94%  |
| EFI  | 141       | 44.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 252       | 80.25%  |
| Btrfs   | 24        | 7.64%   |
| Unknown | 14        | 4.46%   |
| Overlay | 13        | 4.14%   |
| Zfs     | 5         | 1.59%   |
| Xfs     | 4         | 1.27%   |
| Ext3    | 1         | 0.32%   |
| Ext2    | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 218       | 69.65%  |
| GPT     | 69        | 22.04%  |
| MBR     | 26        | 8.31%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 268       | 85.9%   |
| Yes       | 44        | 14.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 172       | 55.31%  |
| Yes       | 139       | 44.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 86        | 27.74%  |
| Lenovo           | 78        | 25.16%  |
| Hewlett-Packard  | 44        | 14.19%  |
| Dell             | 36        | 11.61%  |
| Acer             | 33        | 10.65%  |
| MSI              | 11        | 3.55%   |
| Sony             | 10        | 3.23%   |
| Fujitsu          | 3         | 0.97%   |
| Toshiba          | 2         | 0.65%   |
| Apple            | 2         | 0.65%   |
| Razer            | 1         | 0.32%   |
| Packard Bell     | 1         | 0.32%   |
| LG Electronics   | 1         | 0.32%   |
| Alienware        | 1         | 0.32%   |
| Unknown          | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 4540s                                      | 6         | 1.94%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 5         | 1.61%   |
| Acer Aspire V3-571G                                   | 5         | 1.61%   |
| Lenovo IdeaPad Z510 20287                             | 3         | 0.97%   |
| HP Pavilion g6                                        | 3         | 0.97%   |
| HP EliteBook 840 G2                                   | 3         | 0.97%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR                  | 3         | 0.97%   |
| MSI Prestige 14 A10RB                                 | 2         | 0.65%   |
| Lenovo Z50-70 20354                                   | 2         | 0.65%   |
| Lenovo ThinkPad X250 20CM002XUS                       | 2         | 0.65%   |
| Lenovo Legion 5 15ARH05H 82B1                         | 2         | 0.65%   |
| Lenovo IdeaPad S540-15IWL GTX 81SW                    | 2         | 0.65%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                 | 2         | 0.65%   |
| Lenovo IdeaPad 520-15IKB 81BF                         | 2         | 0.65%   |
| Lenovo IdeaPad 5 15ITL05 82FG                         | 2         | 0.65%   |
| Lenovo G50-70 20351                                   | 2         | 0.65%   |
| Lenovo Flex 2-15 20405                                | 2         | 0.65%   |
| HP ProBook 450 G4                                     | 2         | 0.65%   |
| HP Pavilion dv6                                       | 2         | 0.65%   |
| HP Laptop 15-bs0xx                                    | 2         | 0.65%   |
| HP EliteBook 8470p                                    | 2         | 0.65%   |
| Dell Vostro 1510                                      | 2         | 0.65%   |
| Dell Vostro 1015                                      | 2         | 0.65%   |
| Dell Latitude E7470                                   | 2         | 0.65%   |
| Dell Latitude E6530                                   | 2         | 0.65%   |
| Dell Inspiron N5110                                   | 2         | 0.65%   |
| ASUS X580VD                                           | 2         | 0.65%   |
| ASUS X550IU                                           | 2         | 0.65%   |
| ASUS X542UN                                           | 2         | 0.65%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD                | 2         | 0.65%   |
| ASUS VivoBook_ASUSLaptop X571GT_K571GT                | 2         | 0.65%   |
| ASUS VivoBook_ASUSLaptop X521EQ_S533EQ                | 2         | 0.65%   |
| ASUS VivoBook 15_ASUS Laptop X540MB_X540MB            | 2         | 0.65%   |
| ASUS N501VW                                           | 2         | 0.65%   |
| ASUS K55VD                                            | 2         | 0.65%   |
| Acer TravelMate P446-M                                | 2         | 0.65%   |
| Acer Aspire F5-573G                                   | 2         | 0.65%   |
| Acer Aspire A715-71G                                  | 2         | 0.65%   |
| Toshiba Satellite L655                                | 1         | 0.32%   |
| Toshiba PORTEGE R930                                  | 1         | 0.32%   |
| Sony VPCZ126GG                                        | 1         | 0.32%   |
| Sony VPCSB36FG                                        | 1         | 0.32%   |
| Sony VPCSB19GG                                        | 1         | 0.32%   |
| Sony VPCSA25GX                                        | 1         | 0.32%   |
| Sony VPCEH36EG                                        | 1         | 0.32%   |
| Sony VPCEH11FX                                        | 1         | 0.32%   |
| Sony VPCEB1SFX                                        | 1         | 0.32%   |
| Sony VGN-SR165E                                       | 1         | 0.32%   |
| Sony VGN-CS38GD_B                                     | 1         | 0.32%   |
| Sony SVF15N12SGB                                      | 1         | 0.32%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.32%   |
| Packard Bell EasyNote TK85                            | 1         | 0.32%   |
| MSI MS-1454                                           | 1         | 0.32%   |
| MSI Modern 14 A10M                                    | 1         | 0.32%   |
| MSI Katana GF66 11UE                                  | 1         | 0.32%   |
| MSI GF63 Thin 9RC                                     | 1         | 0.32%   |
| MSI GE620/GE620DX/FX620DX/FX623                       | 1         | 0.32%   |
| MSI GE60 2PC                                          | 1         | 0.32%   |
| MSI GE60 2OC\2OD\2OE                                  | 1         | 0.32%   |
| MSI CX62 6QL                                          | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 30        | 9.68%   |
| Acer Aspire           | 29        | 9.35%   |
| Lenovo ThinkPad       | 23        | 7.42%   |
| ASUS VivoBook         | 20        | 6.45%   |
| HP EliteBook          | 16        | 5.16%   |
| Dell Inspiron         | 14        | 4.52%   |
| HP ProBook            | 13        | 4.19%   |
| Dell Latitude         | 11        | 3.55%   |
| HP Pavilion           | 8         | 2.58%   |
| Dell Vostro           | 8         | 2.58%   |
| Lenovo Legion         | 3         | 0.97%   |
| Fujitsu LIFEBOOK      | 3         | 0.97%   |
| ASUS ASUS             | 3         | 0.97%   |
| Acer TravelMate       | 3         | 0.97%   |
| MSI Prestige          | 2         | 0.65%   |
| MSI GE60              | 2         | 0.65%   |
| Lenovo Z50-70         | 2         | 0.65%   |
| Lenovo ThinkBook      | 2         | 0.65%   |
| Lenovo G580           | 2         | 0.65%   |
| Lenovo G50-70         | 2         | 0.65%   |
| Lenovo Flex           | 2         | 0.65%   |
| HP ZBook              | 2         | 0.65%   |
| HP Laptop             | 2         | 0.65%   |
| ASUS X580VD           | 2         | 0.65%   |
| ASUS X550IU           | 2         | 0.65%   |
| ASUS X542UN           | 2         | 0.65%   |
| ASUS ROG              | 2         | 0.65%   |
| ASUS N501VW           | 2         | 0.65%   |
| ASUS K55VD            | 2         | 0.65%   |
| Toshiba Satellite     | 1         | 0.32%   |
| Toshiba PORTEGE       | 1         | 0.32%   |
| Sony VPCZ126GG        | 1         | 0.32%   |
| Sony VPCSB36FG        | 1         | 0.32%   |
| Sony VPCSB19GG        | 1         | 0.32%   |
| Sony VPCSA25GX        | 1         | 0.32%   |
| Sony VPCEH36EG        | 1         | 0.32%   |
| Sony VPCEH11FX        | 1         | 0.32%   |
| Sony VPCEB1SFX        | 1         | 0.32%   |
| Sony VGN-SR165E       | 1         | 0.32%   |
| Sony VGN-CS38GD       | 1         | 0.32%   |
| Sony SVF15N12SGB      | 1         | 0.32%   |
| Razer Blade           | 1         | 0.32%   |
| Packard Bell EasyNote | 1         | 0.32%   |
| MSI MS-1454           | 1         | 0.32%   |
| MSI Modern            | 1         | 0.32%   |
| MSI Katana            | 1         | 0.32%   |
| MSI GF63              | 1         | 0.32%   |
| MSI GE620             | 1         | 0.32%   |
| MSI CX62              | 1         | 0.32%   |
| MSI CR610M            | 1         | 0.32%   |
| LG RD590-K.ADJCRE6    | 1         | 0.32%   |
| Lenovo Z50-75         | 1         | 0.32%   |
| Lenovo V580c          | 1         | 0.32%   |
| Lenovo V330-15IKB     | 1         | 0.32%   |
| Lenovo V310-15IKB     | 1         | 0.32%   |
| Lenovo G510           | 1         | 0.32%   |
| Lenovo G505           | 1         | 0.32%   |
| Lenovo G500           | 1         | 0.32%   |
| Lenovo G50-80         | 1         | 0.32%   |
| Lenovo G50-45         | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 36        | 11.61%  |
| 2013 | 34        | 10.97%  |
| 2012 | 33        | 10.65%  |
| 2019 | 27        | 8.71%   |
| 2010 | 26        | 8.39%   |
| 2018 | 24        | 7.74%   |
| 2016 | 23        | 7.42%   |
| 2015 | 23        | 7.42%   |
| 2011 | 22        | 7.1%    |
| 2020 | 18        | 5.81%   |
| 2014 | 18        | 5.81%   |
| 2009 | 10        | 3.23%   |
| 2008 | 7         | 2.26%   |
| 2021 | 5         | 1.61%   |
| 2007 | 2         | 0.65%   |
| 2006 | 2         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 310       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 292       | 94.19%  |
| Enabled  | 18        | 5.81%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 310       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 105       | 33.65%  |
| 3.01-4.0   | 70        | 22.44%  |
| 8.01-16.0  | 62        | 19.87%  |
| 16.01-24.0 | 50        | 16.03%  |
| 1.01-2.0   | 9         | 2.88%   |
| 32.01-64.0 | 7         | 2.24%   |
| 2.01-3.0   | 4         | 1.28%   |
| 0.51-1.0   | 3         | 0.96%   |
| 24.01-32.0 | 2         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 118       | 35.22%  |
| 2.01-3.0   | 101       | 30.15%  |
| 3.01-4.0   | 50        | 14.93%  |
| 4.01-8.0   | 38        | 11.34%  |
| 0.51-1.0   | 18        | 5.37%   |
| 8.01-16.0  | 8         | 2.39%   |
| 16.01-24.0 | 1         | 0.3%    |
| 0.01-0.5   | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 223       | 70.79%  |
| 2      | 85        | 26.98%  |
| 3      | 5         | 1.59%   |
| 0      | 2         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 52.41%  |
| No        | 148       | 47.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 86.77%  |
| No        | 41        | 13.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 307       | 99.03%  |
| No        | 3         | 0.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 80.32%  |
| No        | 61        | 19.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Iran    | 310       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Tehran                         | 175       | 53.85%  |
| TehrДЃn                      | 38        | 11.69%  |
| Mashhad                        | 18        | 5.54%   |
| Isfahan                        | 10        | 3.08%   |
| Rasht                          | 5         | 1.54%   |
| Khorramshahr                   | 5         | 1.54%   |
| Tabriz                         | 4         | 1.23%   |
| Qom                            | 4         | 1.23%   |
| Karaj                          | 4         | 1.23%   |
| TajrД«sh                     | 3         | 0.92%   |
| Tajrīsh                       | 3         | 0.92%   |
| Babol                          | 3         | 0.92%   |
| Yazd                           | 2         | 0.62%   |
| Shahre Jadide Andisheh         | 2         | 0.62%   |
| Shahr-e Qods                   | 2         | 0.62%   |
| Sanandij                       | 2         | 0.62%   |
| Qazvin                         | 2         | 0.62%   |
| Kerman                         | 2         | 0.62%   |
| ДЂstДЃneh-ye AshrafД«yeh | 1         | 0.31%   |
| Zanjan                         | 1         | 0.31%   |
| Şowmeeh Sarā                 | 1         | 0.31%   |
| ShДЃhД«n Shahr             | 1         | 0.31%   |
| Shirvan                        | 1         | 0.31%   |
| Shiraz                         | 1         | 0.31%   |
| ShahrД«ДЃr                 | 1         | 0.31%   |
| Shahr-e Kord                   | 1         | 0.31%   |
| SemÄ«rom                     | 1         | 0.31%   |
| SalmДЃs                      | 1         | 0.31%   |
| Robat Karim                    | 1         | 0.31%   |
| Rey                            | 1         | 0.31%   |
| RÅ«dÄn                    | 1         | 0.31%   |
| RafsanjДЃn                   | 1         | 0.31%   |
| Qaleh Ganj                     | 1         | 0.31%   |
| NashtДЃrЕ«d                | 1         | 0.31%   |
| NajafДЃbДЃd                | 1         | 0.31%   |
| MДЃmЕ«nД«yeh             | 1         | 0.31%   |
| MД«ДЃneh                   | 1         | 0.31%   |
| Maragheh                       | 1         | 0.31%   |
| MalДЃrd                      | 1         | 0.31%   |
| KahrÄ«z                      | 1         | 0.31%   |
| Gorgan                         | 1         | 0.31%   |
| FÄ«rÅ«zkÅ«h              | 1         | 0.31%   |
| FÄmenÄ«n                  | 1         | 0.31%   |
| DДЃmghДЃn                  | 1         | 0.31%   |
| DamДЃvand                    | 1         | 0.31%   |
| DamÄvand                    | 1         | 0.31%   |
| BЕ«kДЃn                    | 1         | 0.31%   |
| BorЕ«jerd                    | 1         | 0.31%   |
| Birjand                        | 1         | 0.31%   |
| Bandar-e Lengeh                | 1         | 0.31%   |
| Bandar-e Asalūyeh             | 1         | 0.31%   |
| Bandar Abbas                   | 1         | 0.31%   |
| BajestДЃn                    | 1         | 0.31%   |
| BahДЃr                       | 1         | 0.31%   |
| AsadÄbÄd                 | 1         | 0.31%   |
| Arak                           | 1         | 0.31%   |
| Aleshtar                       | 1         | 0.31%   |
| Ahvaz                          | 1         | 0.31%   |
| Abadan                         | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 77        | 93     | 19.85%  |
| WDC                       | 72        | 85     | 18.56%  |
| Toshiba                   | 61        | 71     | 15.72%  |
| Samsung Electronics       | 49        | 55     | 12.63%  |
| HGST                      | 18        | 21     | 4.64%   |
| SanDisk                   | 15        | 19     | 3.87%   |
| A-DATA Technology         | 14        | 18     | 3.61%   |
| Micron Technology         | 12        | 14     | 3.09%   |
| Intel                     | 10        | 10     | 2.58%   |
| Unknown                   | 9         | 9      | 2.32%   |
| SK Hynix                  | 6         | 6      | 1.55%   |
| Hitachi                   | 6         | 6      | 1.55%   |
| Kingston                  | 5         | 7      | 1.29%   |
| PLEXTOR                   | 3         | 3      | 0.77%   |
| Lexar                     | 3         | 3      | 0.77%   |
| LITEON                    | 2         | 3      | 0.52%   |
| Biostar                   | 2         | 3      | 0.52%   |
| Apacer                    | 2         | 2      | 0.52%   |
| VC-500                    | 1         | 1      | 0.26%   |
| ValueTech                 | 1         | 1      | 0.26%   |
| USB3.0                    | 1         | 1      | 0.26%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.26%   |
| Union Memory              | 1         | 1      | 0.26%   |
| UMIS                      | 1         | 1      | 0.26%   |
| Transcend                 | 1         | 1      | 0.26%   |
| SPCC                      | 1         | 1      | 0.26%   |
| Silicon Motion            | 1         | 1      | 0.26%   |
| Phison                    | 1         | 1      | 0.26%   |
| OCZ                       | 1         | 1      | 0.26%   |
| Micron/Crucial Technology | 1         | 1      | 0.26%   |
| Mass                      | 1         | 2      | 0.26%   |
| LITEONIT                  | 1         | 2      | 0.26%   |
| KODAK                     | 1         | 1      | 0.26%   |
| KingFast                  | 1         | 1      | 0.26%   |
| Gigabyte Technology       | 1         | 1      | 0.26%   |
| GeIL                      | 1         | 1      | 0.26%   |
| Fujitsu                   | 1         | 1      | 0.26%   |
| Crucial                   | 1         | 1      | 0.26%   |
| China                     | 1         | 1      | 0.26%   |
| Apple                     | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 29        | 7.38%   |
| Toshiba MQ01ABD100 1TB                | 16        | 4.07%   |
| Toshiba MQ04ABF100 1TB                | 10        | 2.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 9         | 2.29%   |
| WDC WD10SPZX-24Z10 1TB                | 8         | 2.04%   |
| Seagate ST9500325AS 500GB             | 8         | 2.04%   |
| WDC WD10SPZX-08Z10 1TB                | 7         | 1.78%   |
| Samsung SSD 860 EVO 500GB             | 7         | 1.78%   |
| Toshiba MQ01ABF050 500GB              | 6         | 1.53%   |
| Samsung SSD 860 EVO 250GB             | 6         | 1.53%   |
| WDC WD10JPCX-24UE4T0 1TB              | 5         | 1.27%   |
| A-DATA SU650 120GB SSD                | 5         | 1.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 4         | 1.02%   |
| Toshiba MQ01ABD050V 500GB             | 4         | 1.02%   |
| Intel NVMe SSD Drive 512GB            | 4         | 1.02%   |
| HGST HTS721010A9E630 1TB              | 4         | 1.02%   |
| HGST HTS541010B7E610 1TB              | 4         | 1.02%   |
| HGST HTS541010A9E680 1TB              | 4         | 1.02%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 3         | 0.76%   |
| Unknown MMC Card  32GB                | 3         | 0.76%   |
| Toshiba MQ01ABD075 752GB              | 3         | 0.76%   |
| Seagate ST9500420AS 500GB             | 3         | 0.76%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 0.76%   |
| Seagate ST2000LM007-1R8174 2TB        | 3         | 0.76%   |
| Samsung SSD 850 EVO 250GB             | 3         | 0.76%   |
| Micron 2210_MTFDHBA512QFD 512GB       | 3         | 0.76%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 3         | 0.76%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 2         | 0.51%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD      | 2         | 0.51%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 2         | 0.51%   |
| WDC WD3200BEVT-75ZCT2 320GB           | 2         | 0.51%   |
| WDC WD10SPZX-75Z10T0 1TB              | 2         | 0.51%   |
| WDC WD10SPCX-08S8TT0 1TB              | 2         | 0.51%   |
| WDC WD10JPVX-08JC3T5 1TB              | 2         | 0.51%   |
| WDC WD10JPVX-00JC3T0 1TB              | 2         | 0.51%   |
| Toshiba THNSNC128GMMJ 128GB SSD       | 2         | 0.51%   |
| Toshiba MQ01ABD050 500GB              | 2         | 0.51%   |
| Toshiba MK7559GSXP 752GB              | 2         | 0.51%   |
| SK Hynix NVMe SSD Drive 256GB         | 2         | 0.51%   |
| SK Hynix HFS256G3BTND-N210A 256GB SSD | 2         | 0.51%   |
| Seagate ST95005620AS 500GB            | 2         | 0.51%   |
| Seagate ST9250315AS 250GB             | 2         | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 0.51%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 2         | 0.51%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 0.51%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 0.51%   |
| SanDisk SSD U110 16GB                 | 2         | 0.51%   |
| SanDisk SD8SNAT128G1002 128GB SSD     | 2         | 0.51%   |
| Samsung SSD 870 EVO 500GB             | 2         | 0.51%   |
| Samsung NVMe SSD Drive 512GB          | 2         | 0.51%   |
| Samsung NVMe SSD Drive 1024GB         | 2         | 0.51%   |
| Samsung MZVLQ512HALU-00000 512GB      | 2         | 0.51%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD  | 2         | 0.51%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD   | 2         | 0.51%   |
| Intel SSDPEKNW010T8 1TB               | 2         | 0.51%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 0.51%   |
| HGST HTS725050A7E630 500GB            | 2         | 0.51%   |
| HGST HTS541075A9E680 752GB            | 2         | 0.51%   |
| Biostar S100-120GB                    | 2         | 0.51%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD      | 1         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 77        | 93     | 35.16%  |
| WDC                 | 60        | 67     | 27.4%   |
| Toshiba             | 55        | 61     | 25.11%  |
| HGST                | 18        | 21     | 8.22%   |
| Hitachi             | 6         | 6      | 2.74%   |
| Unknown             | 1         | 1      | 0.46%   |
| Samsung Electronics | 1         | 1      | 0.46%   |
| Fujitsu             | 1         | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 41     | 29.51%  |
| WDC                 | 14        | 17     | 11.48%  |
| A-DATA Technology   | 14        | 18     | 11.48%  |
| SanDisk             | 13        | 16     | 10.66%  |
| Micron Technology   | 7         | 7      | 5.74%   |
| Toshiba             | 4         | 8      | 3.28%   |
| SK Hynix            | 4         | 4      | 3.28%   |
| PLEXTOR             | 3         | 3      | 2.46%   |
| Lexar               | 3         | 3      | 2.46%   |
| Kingston            | 3         | 4      | 2.46%   |
| Intel               | 3         | 3      | 2.46%   |
| LITEON              | 2         | 3      | 1.64%   |
| Biostar             | 2         | 3      | 1.64%   |
| Apacer              | 2         | 2      | 1.64%   |
| ValueTech           | 1         | 1      | 0.82%   |
| USB3.0              | 1         | 1      | 0.82%   |
| Transcend           | 1         | 1      | 0.82%   |
| SPCC                | 1         | 1      | 0.82%   |
| OCZ                 | 1         | 1      | 0.82%   |
| LITEONIT            | 1         | 2      | 0.82%   |
| KODAK               | 1         | 1      | 0.82%   |
| Gigabyte Technology | 1         | 1      | 0.82%   |
| GeIL                | 1         | 1      | 0.82%   |
| Crucial             | 1         | 1      | 0.82%   |
| China               | 1         | 1      | 0.82%   |
| Apple               | 1         | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 217       | 251    | 56.36%  |
| SSD     | 119       | 145    | 30.91%  |
| NVMe    | 39        | 45     | 10.13%  |
| MMC     | 6         | 6      | 1.56%   |
| Unknown | 4         | 5      | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 287       | 394    | 85.16%  |
| NVMe | 39        | 45     | 11.57%  |
| MMC  | 6         | 6      | 1.78%   |
| SAS  | 5         | 7      | 1.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 176       | 220    | 54.49%  |
| 0.51-1.0   | 140       | 168    | 43.34%  |
| 1.01-2.0   | 7         | 8      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 85        | 26.48%  |
| 501-1000       | 64        | 19.94%  |
| 251-500        | 60        | 18.69%  |
| 51-100         | 32        | 9.97%   |
| 1001-2000      | 30        | 9.35%   |
| 1-20           | 22        | 6.85%   |
| 21-50          | 17        | 5.3%    |
| Unknown        | 9         | 2.8%    |
| More than 3000 | 1         | 0.31%   |
| 2001-3000      | 1         | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 120       | 36.47%  |
| 21-50          | 53        | 16.11%  |
| 51-100         | 43        | 13.07%  |
| 101-250        | 42        | 12.77%  |
| 501-1000       | 31        | 9.42%   |
| 251-500        | 28        | 8.51%   |
| Unknown        | 9         | 2.74%   |
| 1001-2000      | 2         | 0.61%   |
| More than 3000 | 1         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 10%     |
| WDC WD3200BPVT-75ZEST0 320GB                   | 1         | 1      | 5%      |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 5%      |
| WDC WD10SPZX-08Z10 1TB                         | 1         | 1      | 5%      |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 5%      |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 5%      |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 5%      |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 5%      |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 5%      |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 5%      |
| Seagate ST1000LM014-SSHD-8GB                   | 1         | 1      | 5%      |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 5%      |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 5%      |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 5%      |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 5%      |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 5%      |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 6         | 6      | 30%     |
| Seagate           | 5         | 5      | 25%     |
| WDC               | 3         | 3      | 15%     |
| Hitachi           | 3         | 3      | 15%     |
| HGST              | 2         | 2      | 10%     |
| Micron Technology | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 31.58%  |
| Seagate | 5         | 5      | 26.32%  |
| WDC     | 3         | 3      | 15.79%  |
| Hitachi | 3         | 3      | 15.79%  |
| HGST    | 2         | 2      | 10.53%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 19     | 94.74%  |
| SSD  | 1         | 1      | 5.26%   |

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
| Detected | 221       | 317    | 68.85%  |
| Works    | 80        | 114    | 24.92%  |
| Malfunc  | 19        | 20     | 5.92%   |
| Failed   | 1         | 1      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 278       | 82.99%  |
| AMD                          | 22        | 6.57%   |
| Samsung Electronics          | 13        | 3.88%   |
| Micron Technology            | 5         | 1.49%   |
| Union Memory (Shenzhen)      | 4         | 1.19%   |
| Sandisk                      | 3         | 0.9%    |
| Toshiba America Info Systems | 2         | 0.6%    |
| SK Hynix                     | 2         | 0.6%    |
| Kingston Technology Company  | 2         | 0.6%    |
| Silicon Motion               | 1         | 0.3%    |
| Phison Electronics           | 1         | 0.3%    |
| Nvidia                       | 1         | 0.3%    |
| Micron/Crucial Technology    | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 47        | 13.39%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 31        | 8.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 25        | 7.12%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 6.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 5.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 19        | 5.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 18        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 17        | 4.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 16        | 4.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 3.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 2.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 2.28%   |
| Intel SSD 660P Series                                                            | 7         | 1.99%   |
| Samsung NVMe SSD Controller 980                                                  | 6         | 1.71%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.42%   |
| Micron Non-Volatile memory controller                                            | 5         | 1.42%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.42%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 4         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 3         | 0.85%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.57%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.28%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.28%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.28%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.28%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.28%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.28%   |
| Samsung Electronics SATA controller                                              | 1         | 0.28%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.28%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.28%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.28%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.28%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.28%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 0.28%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.28%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 1         | 0.28%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 1         | 0.28%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.28%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 0.28%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 264       | 76.74%  |
| NVMe | 39        | 11.34%  |
| RAID | 30        | 8.72%   |
| IDE  | 11        | 3.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 288       | 92.9%   |
| AMD    | 22        | 7.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz              | 18        | 5.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 13        | 4.19%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 10        | 3.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 9         | 2.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz              | 8         | 2.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 8         | 2.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 8         | 2.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 7         | 2.26%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz             | 6         | 1.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 6         | 1.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 6         | 1.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz              | 6         | 1.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 5         | 1.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 5         | 1.61%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz             | 5         | 1.61%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 4         | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 4         | 1.29%   |
| Intel Core i7-5500U CPU @ 2.40GHz              | 4         | 1.29%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 4         | 1.29%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 4         | 1.29%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 4         | 1.29%   |
| Intel Core i5 CPU M 480 @ 2.67GHz              | 4         | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 4         | 1.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 3         | 0.97%   |
| Intel Core i7-2670QM CPU @ 2.20GHz             | 3         | 0.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 3         | 0.97%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz           | 3         | 0.97%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 3         | 0.97%   |
| Intel Atom CPU N450 @ 1.66GHz                  | 3         | 0.97%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 2         | 0.65%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 0.65%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 2         | 0.65%   |
| Intel Core i7-3632QM CPU @ 2.20GHz             | 2         | 0.65%   |
| Intel Core i7-3537U CPU @ 2.00GHz              | 2         | 0.65%   |
| Intel Core i7-2630QM CPU @ 2.00GHz             | 2         | 0.65%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 2         | 0.65%   |
| Intel Core i7-10875H CPU @ 2.30GHz             | 2         | 0.65%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz              | 2         | 0.65%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz              | 2         | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 2         | 0.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 2         | 0.65%   |
| Intel Core i5-4200M CPU @ 2.50GHz              | 2         | 0.65%   |
| Intel Core i5-2410M CPU @ 2.30GHz              | 2         | 0.65%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 2         | 0.65%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 2         | 0.65%   |
| Intel Core i5 CPU M 540 @ 2.53GHz              | 2         | 0.65%   |
| Intel Core i5 CPU M 520 @ 2.40GHz              | 2         | 0.65%   |
| Intel Core i5 CPU M 460 @ 2.53GHz              | 2         | 0.65%   |
| Intel Core i5 CPU M 430 @ 2.27GHz              | 2         | 0.65%   |
| Intel Core i3-8130U CPU @ 2.20GHz              | 2         | 0.65%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 2         | 0.65%   |
| Intel Core i3-10110U CPU @ 2.10GHz             | 2         | 0.65%   |
| Intel Core i3 CPU M 380 @ 2.53GHz              | 2         | 0.65%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 2         | 0.65%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 0.65%   |
| Intel Celeron CPU N3350 @ 1.10GHz              | 2         | 0.65%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 2         | 0.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 0.65%   |
| AMD FX-9830P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 0.65%   |
| AMD A10 PRO-7350B R6, 10 Compute Cores 4C+6G   | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 122       | 39.35%  |
| Intel Core i5           | 96        | 30.97%  |
| Intel Core i3           | 19        | 6.13%   |
| Intel Core 2 Duo        | 13        | 4.19%   |
| Other                   | 10        | 3.23%   |
| Intel Pentium           | 10        | 3.23%   |
| Intel Celeron           | 6         | 1.94%   |
| Intel Atom              | 5         | 1.61%   |
| AMD Ryzen 7             | 4         | 1.29%   |
| AMD FX                  | 4         | 1.29%   |
| Intel Pentium Dual-Core | 3         | 0.97%   |
| AMD A4                  | 3         | 0.97%   |
| Intel Pentium Silver    | 2         | 0.65%   |
| Intel Genuine           | 2         | 0.65%   |
| AMD E1                  | 2         | 0.65%   |
| AMD A10                 | 2         | 0.65%   |
| Intel Core M            | 1         | 0.32%   |
| AMD Ryzen 5             | 1         | 0.32%   |
| AMD Ryzen 3             | 1         | 0.32%   |
| AMD PRO A8              | 1         | 0.32%   |
| AMD PRO A10             | 1         | 0.32%   |
| AMD E2                  | 1         | 0.32%   |
| AMD A6                  | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 183       | 59.03%  |
| 4      | 106       | 34.19%  |
| 6      | 11        | 3.55%   |
| 8      | 7         | 2.26%   |
| 1      | 3         | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 310       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 264       | 85.16%  |
| 1      | 46        | 14.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 299       | 96.14%  |
| Unknown        | 9         | 2.89%   |
| 32-bit         | 3         | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 15.53%  |
| 0x306a9    | 31        | 9.63%   |
| 0x806ea    | 24        | 7.45%   |
| 0x306d4    | 21        | 6.52%   |
| 0x206a7    | 19        | 5.9%    |
| 0x306c3    | 16        | 4.97%   |
| 0x20655    | 16        | 4.97%   |
| 0x806e9    | 15        | 4.66%   |
| 0x806ec    | 12        | 3.73%   |
| 0x906e9    | 11        | 3.42%   |
| 0x40651    | 10        | 3.11%   |
| 0x906ea    | 9         | 2.8%    |
| 0x406e3    | 9         | 2.8%    |
| 0x1067a    | 9         | 2.8%    |
| 0x506e3    | 7         | 2.17%   |
| 0x20652    | 6         | 1.86%   |
| 0x806c1    | 5         | 1.55%   |
| 0xa0652    | 4         | 1.24%   |
| 0x706a1    | 4         | 1.24%   |
| 0x106e5    | 4         | 1.24%   |
| 0x706e5    | 3         | 0.93%   |
| 0x6fd      | 3         | 0.93%   |
| 0x106ca    | 3         | 0.93%   |
| 0x0700010f | 3         | 0.93%   |
| 0x0600611a | 3         | 0.93%   |
| 0x806d1    | 2         | 0.62%   |
| 0x6e8      | 2         | 0.62%   |
| 0x30678    | 2         | 0.62%   |
| 0x10676    | 2         | 0.62%   |
| 0x08600104 | 2         | 0.62%   |
| 0x06003109 | 2         | 0.62%   |
| 0x806eb    | 1         | 0.31%   |
| 0x6fb      | 1         | 0.31%   |
| 0x6fa      | 1         | 0.31%   |
| 0x506c9    | 1         | 0.31%   |
| 0x406c3    | 1         | 0.31%   |
| 0x30661    | 1         | 0.31%   |
| 0x08608102 | 1         | 0.31%   |
| 0x08108102 | 1         | 0.31%   |
| 0x07030105 | 1         | 0.31%   |
| 0x06006705 | 1         | 0.31%   |
| 0x06003106 | 1         | 0.31%   |
| 0x05000119 | 1         | 0.31%   |
| 0x03000027 | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 81        | 26.13%  |
| IvyBridge     | 36        | 11.61%  |
| Haswell       | 34        | 10.97%  |
| Westmere      | 24        | 7.74%   |
| Broadwell     | 21        | 6.77%   |
| Skylake       | 19        | 6.13%   |
| SandyBridge   | 19        | 6.13%   |
| Penryn        | 11        | 3.55%   |
| Excavator     | 7         | 2.26%   |
| TigerLake     | 6         | 1.94%   |
| Goldmont plus | 6         | 1.94%   |
| IceLake       | 5         | 1.61%   |
| Core          | 5         | 1.61%   |
| CometLake     | 5         | 1.61%   |
| Nehalem       | 4         | 1.29%   |
| Bonnell       | 4         | 1.29%   |
| Zen 2         | 3         | 0.97%   |
| Steamroller   | 3         | 0.97%   |
| Silvermont    | 3         | 0.97%   |
| Jaguar        | 3         | 0.97%   |
| Zen+          | 2         | 0.65%   |
| P6            | 2         | 0.65%   |
| Goldmont      | 2         | 0.65%   |
| Unknown       | 2         | 0.65%   |
| Puma          | 1         | 0.32%   |
| K10 Llano     | 1         | 0.32%   |
| Bobcat        | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 258       | 51.7%   |
| Nvidia           | 158       | 31.66%  |
| AMD              | 82        | 16.43%  |
| ATI Technologies | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 33        | 6.5%    |
| Intel UHD Graphics 620                                                                | 26        | 5.12%   |
| Intel HD Graphics 5500                                                                | 19        | 3.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 19        | 3.74%   |
| Intel HD Graphics 620                                                                 | 18        | 3.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 17        | 3.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 14        | 2.76%   |
| Intel Core Processor Integrated Graphics Controller                                   | 14        | 2.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 13        | 2.56%   |
| Intel HD Graphics 630                                                                 | 12        | 2.36%   |
| Nvidia GP108M [GeForce MX150]                                                         | 11        | 2.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 10        | 1.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 10        | 1.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 1.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 1.77%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 8         | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 8         | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 8         | 1.57%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 8         | 1.57%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 7         | 1.38%   |
| Intel HD Graphics 530                                                                 | 7         | 1.38%   |
| Nvidia GM108M [GeForce 840M]                                                          | 6         | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 1.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 0.98%   |
| Nvidia GM108M [GeForce MX110]                                                         | 5         | 0.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 5         | 0.98%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 5         | 0.98%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 5         | 0.98%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 5         | 0.98%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 5         | 0.98%   |
| Nvidia GP107M [GeForce MX350]                                                         | 4         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 0.79%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 4         | 0.79%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                     | 4         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.59%   |
| Nvidia GP108M [GeForce MX250]                                                         | 3         | 0.59%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 3         | 0.59%   |
| Nvidia GM107 [GeForce 940MX]                                                          | 3         | 0.59%   |
| Nvidia GK107M [GeForce GT 750M]                                                       | 3         | 0.59%   |
| Nvidia GF119M [GeForce 610M]                                                          | 3         | 0.59%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 0.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller               | 3         | 0.59%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 3         | 0.59%   |
| AMD Renoir                                                                            | 3         | 0.59%   |
| AMD Opal PRO [Radeon R7 M260X]                                                        | 3         | 0.59%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                                    | 3         | 0.59%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                          | 3         | 0.59%   |
| Nvidia TU117M [GeForce MX450]                                                         | 2         | 0.39%   |
| Nvidia TU117M                                                                         | 2         | 0.39%   |
| Nvidia GT218M [GeForce 310M]                                                          | 2         | 0.39%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 2         | 0.39%   |
| Nvidia GM108M [GeForce MX130]                                                         | 2         | 0.39%   |
| Nvidia GM108M [GeForce 940M]                                                          | 2         | 0.39%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 2         | 0.39%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 2         | 0.39%   |
| Nvidia GM107M [GeForce GTX 850M]                                                      | 2         | 0.39%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 2         | 0.39%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 2         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 137       | 44.19%  |
| 1 x Intel      | 73        | 23.55%  |
| Intel + AMD    | 48        | 15.48%  |
| 1 x AMD        | 25        | 8.06%   |
| 1 x Nvidia     | 17        | 5.48%   |
| 2 x AMD        | 6         | 1.94%   |
| AMD + Nvidia   | 4         | 1.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 240       | 76.43%  |
| Proprietary | 67        | 21.34%  |
| Unknown     | 7         | 2.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 136       | 42.9%   |
| 1.01-2.0   | 69        | 21.77%  |
| 3.01-4.0   | 48        | 15.14%  |
| 0.51-1.0   | 36        | 11.36%  |
| 0.01-0.5   | 22        | 6.94%   |
| 5.01-6.0   | 4         | 1.26%   |
| 7.01-8.0   | 1         | 0.32%   |
| 2.01-3.0   | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 66        | 20.31%  |
| AU Optronics            | 61        | 18.77%  |
| BOE                     | 48        | 14.77%  |
| Chimei Innolux          | 45        | 13.85%  |
| Samsung Electronics     | 40        | 12.31%  |
| Goldstar                | 13        | 4%      |
| Chi Mei Optoelectronics | 10        | 3.08%   |
| PANDA                   | 6         | 1.85%   |
| HannStar                | 4         | 1.23%   |
| BenQ                    | 4         | 1.23%   |
| Lenovo                  | 3         | 0.92%   |
| Sharp                   | 2         | 0.62%   |
| InnoLux Display         | 2         | 0.62%   |
| InfoVision              | 2         | 0.62%   |
| CHD                     | 2         | 0.62%   |
| Apple                   | 2         | 0.62%   |
| Sony                    | 1         | 0.31%   |
| Seiko/Epson             | 1         | 0.31%   |
| Quanta Display          | 1         | 0.31%   |
| PAR                     | 1         | 0.31%   |
| Nvidia                  | 1         | 0.31%   |
| LGD                     | 1         | 0.31%   |
| LG Philips              | 1         | 0.31%   |
| KDC                     | 1         | 0.31%   |
| Hewlett-Packard         | 1         | 0.31%   |
| cPATH                   | 1         | 0.31%   |
| CHI                     | 1         | 0.31%   |
| AUS                     | 1         | 0.31%   |
| ASUSTek Computer        | 1         | 0.31%   |
| AOC                     | 1         | 0.31%   |
| Ancor Communications    | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 3.37%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 8         | 2.45%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 7         | 2.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 1.84%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 4         | 1.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.23%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 4         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 1.23%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 1.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 1.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 3         | 0.92%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 3         | 0.92%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 3         | 0.92%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 3         | 0.92%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 3         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.92%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.61%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.61%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.61%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 0.61%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.61%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 2         | 0.61%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 2         | 0.61%   |
| LG Display LCD Monitor LGD03E6 1366x768 345x194mm 15.6-inch              | 2         | 0.61%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.61%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.61%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 2         | 0.61%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch              | 2         | 0.61%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch          | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.61%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 2         | 0.61%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 2         | 0.61%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 2         | 0.61%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.61%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x194mm 15.5-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.61%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.31%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 1         | 0.31%   |
| Sharp LCD Monitor SHP141F 1920x1080 294x165mm 13.3-inch                  | 1         | 0.31%   |
| Seiko/Epson LCD Monitor 5760x2160                                        | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM0560 1440x900 408x255mm 18.9-inch      | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch     | 1         | 0.31%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 477x268mm 21.5-inch       | 1         | 0.31%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch     | 1         | 0.31%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch     | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 134       | 42.41%  |
| 1366x768 (WXGA)    | 127       | 40.19%  |
| 1600x900 (HD+)     | 10        | 3.16%   |
| 1440x900 (WXGA+)   | 10        | 3.16%   |
| 1280x800 (WXGA)    | 10        | 3.16%   |
| 3840x2160 (4K)     | 9         | 2.85%   |
| 1024x600           | 4         | 1.27%   |
| Unknown            | 3         | 0.95%   |
| 1680x1050 (WSXGA+) | 2         | 0.63%   |
| 5760x2160          | 1         | 0.32%   |
| 3840x2400          | 1         | 0.32%   |
| 3840x1080          | 1         | 0.32%   |
| 2944x1080          | 1         | 0.32%   |
| 1920x1200 (WUXGA)  | 1         | 0.32%   |
| 1680x945           | 1         | 0.32%   |
| 1280x1024 (SXGA)   | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 207       | 64.29%  |
| 14      | 29        | 9.01%   |
| 13      | 27        | 8.39%   |
| 21      | 10        | 3.11%   |
| 12      | 9         | 2.8%    |
| 23      | 5         | 1.55%   |
| 10      | 5         | 1.55%   |
| Unknown | 5         | 1.55%   |
| 20      | 4         | 1.24%   |
| 18      | 4         | 1.24%   |
| 17      | 4         | 1.24%   |
| 11      | 3         | 0.93%   |
| 27      | 2         | 0.62%   |
| 24      | 2         | 0.62%   |
| 19      | 2         | 0.62%   |
| 84      | 1         | 0.31%   |
| 32      | 1         | 0.31%   |
| 22      | 1         | 0.31%   |
| 16      | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 256       | 79.5%   |
| 201-300     | 22        | 6.83%   |
| 401-500     | 21        | 6.52%   |
| 501-600     | 8         | 2.48%   |
| 351-400     | 7         | 2.17%   |
| Unknown     | 5         | 1.55%   |
| 701-800     | 1         | 0.31%   |
| 601-700     | 1         | 0.31%   |
| 1501-2000   | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 271       | 90.64%  |
| 16/10   | 21        | 7.02%   |
| Unknown | 5         | 1.67%   |
| 4/3     | 1         | 0.33%   |
| 3/2     | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 207       | 64.29%  |
| 81-90          | 51        | 15.84%  |
| 201-250        | 18        | 5.59%   |
| 61-70          | 9         | 2.8%    |
| 151-200        | 7         | 2.17%   |
| 41-50          | 5         | 1.55%   |
| Unknown        | 5         | 1.55%   |
| 71-80          | 3         | 0.93%   |
| 51-60          | 3         | 0.93%   |
| 141-150        | 3         | 0.93%   |
| 121-130        | 3         | 0.93%   |
| 301-350        | 2         | 0.62%   |
| 131-140        | 2         | 0.62%   |
| 91-100         | 2         | 0.62%   |
| More than 1000 | 1         | 0.31%   |
| 351-500        | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 138       | 43.67%  |
| 101-120       | 120       | 37.97%  |
| 51-100        | 43        | 13.61%  |
| More than 240 | 8         | 2.53%   |
| Unknown       | 5         | 1.58%   |
| 161-240       | 2         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 273       | 86.94%  |
| 2     | 32        | 10.19%  |
| 0     | 8         | 2.55%   |
| 3     | 1         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 188       | 35.54%  |
| Intel                    | 141       | 26.65%  |
| Qualcomm Atheros         | 89        | 16.82%  |
| Broadcom                 | 42        | 7.94%   |
| Broadcom Limited         | 14        | 2.65%   |
| Ralink                   | 12        | 2.27%   |
| Xiaomi                   | 7         | 1.32%   |
| Samsung Electronics      | 5         | 0.95%   |
| MEDIATEK                 | 4         | 0.76%   |
| Marvell Technology Group | 4         | 0.76%   |
| JMicron Technology       | 3         | 0.57%   |
| Huawei Technologies      | 3         | 0.57%   |
| HTC (High Tech Computer) | 3         | 0.57%   |
| Hewlett-Packard          | 2         | 0.38%   |
| D-Link                   | 2         | 0.38%   |
| TP-Link                  | 1         | 0.19%   |
| Sierra Wireless          | 1         | 0.19%   |
| Ralink Technology        | 1         | 0.19%   |
| LG Electronics           | 1         | 0.19%   |
| Lenovo                   | 1         | 0.19%   |
| ICS Advent               | 1         | 0.19%   |
| BUFFALO                  | 1         | 0.19%   |
| Attansic Technology      | 1         | 0.19%   |
| ASUSTek Computer         | 1         | 0.19%   |
| ASIX Electronics         | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 148       | 24.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 4.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 21        | 3.48%   |
| Intel Wireless 7265                                               | 21        | 3.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 2.15%   |
| Intel Wireless 7260                                               | 12        | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.82%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 10        | 1.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 8         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.16%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.99%   |
| Intel Wireless 8260                                               | 6         | 0.99%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.83%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.66%   |
| Intel Wireless 3165                                               | 4         | 0.66%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.66%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.66%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.5%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.5%    |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.5%    |
| Huawei JNY-LX1                                                    | 3         | 0.5%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 3         | 0.5%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 3         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 139       | 44.41%  |
| Qualcomm Atheros      | 76        | 24.28%  |
| Realtek Semiconductor | 37        | 11.82%  |
| Broadcom              | 28        | 8.95%   |
| Ralink                | 12        | 3.83%   |
| Broadcom Limited      | 11        | 3.51%   |
| MEDIATEK              | 3         | 0.96%   |
| Hewlett-Packard       | 2         | 0.64%   |
| Xiaomi                | 1         | 0.32%   |
| TP-Link               | 1         | 0.32%   |
| Ralink Technology     | 1         | 0.32%   |
| D-Link                | 1         | 0.32%   |
| BUFFALO               | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 6.69%   |
| Intel Wireless 7265                                                     | 21        | 6.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 4.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 4.14%   |
| Intel Wireless 7260                                                     | 12        | 3.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 3.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 3.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 3.5%    |
| Intel Wireless 8265 / 8275                                              | 11        | 3.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 3.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 2.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 2.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.91%   |
| Intel Wireless 8260                                                     | 6         | 1.91%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.59%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.27%   |
| Intel Wireless 3165                                                     | 4         | 1.27%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.96%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 0.96%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.64%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.64%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 2         | 0.64%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.64%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.64%   |
| Intel Wireless 3160                                                     | 2         | 0.64%   |
| Intel WiFi Link 5100                                                    | 2         | 0.64%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.64%   |
| Intel Centrino Wireless-N 135                                           | 2         | 0.64%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.64%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 0.64%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.64%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 2         | 0.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.64%   |
| Broadcom BCM43227 802.11b/g/n                                           | 2         | 0.64%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.64%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.32%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.32%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.32%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.32%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 176       | 61.11%  |
| Intel                    | 30        | 10.42%  |
| Qualcomm Atheros         | 25        | 8.68%   |
| Broadcom                 | 22        | 7.64%   |
| Xiaomi                   | 6         | 2.08%   |
| Samsung Electronics      | 5         | 1.74%   |
| Marvell Technology Group | 4         | 1.39%   |
| JMicron Technology       | 3         | 1.04%   |
| Huawei Technologies      | 3         | 1.04%   |
| HTC (High Tech Computer) | 3         | 1.04%   |
| Broadcom Limited         | 3         | 1.04%   |
| Sierra Wireless          | 1         | 0.35%   |
| MediaTek                 | 1         | 0.35%   |
| LG Electronics           | 1         | 0.35%   |
| Lenovo                   | 1         | 0.35%   |
| ICS Advent               | 1         | 0.35%   |
| D-Link                   | 1         | 0.35%   |
| Attansic Technology      | 1         | 0.35%   |
| ASIX Electronics         | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 148       | 51.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 27        | 9.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 3.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 7         | 2.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 1.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 1.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 1.38%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 1.38%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 1.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 1.04%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 1.04%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.04%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.04%   |
| Huawei JNY-LX1                                                                 | 3         | 1.04%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.69%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.69%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.69%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.69%   |
| HTC (High Tech Computer) HTC                                                   | 2         | 0.69%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.69%   |
| Sierra Wireless EM7345 4G LTE                                                  | 1         | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.35%   |
| MediaTek NOA N2                                                                | 1         | 0.35%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.35%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                            | 1         | 0.35%   |
| Lenovo Android Phone                                                           | 1         | 0.35%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.35%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.35%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.35%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.35%   |
| HTC (High Tech Computer) Desire 626 dual sim                                   | 1         | 0.35%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                       | 1         | 0.35%   |
| Broadcom Pirelli Remote NDIS Device                                            | 1         | 0.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.35%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 1         | 0.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.35%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.35%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.35%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.35%   |
| Broadcom Limited NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1         | 0.35%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.35%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.35%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.35%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 1         | 0.35%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 307       | 53.39%  |
| Ethernet | 267       | 46.43%  |
| Unknown  | 1         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 269       | 72.51%  |
| Ethernet | 101       | 27.22%  |
| Unknown  | 1         | 0.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 260       | 83.87%  |
| 1     | 49        | 15.81%  |
| 0     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 293       | 93.61%  |
| Yes  | 20        | 6.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 41.04%  |
| IMC Networks                    | 29        | 11.55%  |
| Qualcomm Atheros Communications | 24        | 9.56%   |
| Realtek Semiconductor           | 19        | 7.57%   |
| Broadcom                        | 14        | 5.58%   |
| Lite-On Technology              | 13        | 5.18%   |
| Foxconn / Hon Hai               | 12        | 4.78%   |
| Dell                            | 9         | 3.59%   |
| Ralink                          | 8         | 3.19%   |
| ASUSTek Computer                | 5         | 1.99%   |
| Foxconn International           | 4         | 1.59%   |
| Ralink Technology               | 2         | 0.8%    |
| Cambridge Silicon Radio         | 2         | 0.8%    |
| Askey Computer                  | 2         | 0.8%    |
| Apple                           | 2         | 0.8%    |
| Realtek                         | 1         | 0.4%    |
| Micro Star International        | 1         | 0.4%    |
| Hewlett-Packard                 | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 59        | 23.51%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 5.98%   |
| Intel AX201 Bluetooth                                                               | 14        | 5.58%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 5.18%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 5.18%   |
| Realtek Bluetooth Radio                                                             | 11        | 4.38%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 3.19%   |
| IMC Networks Bluetooth Device                                                       | 8         | 3.19%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.99%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.99%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.99%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 5         | 1.99%   |
| Intel AX200 Bluetooth                                                               | 4         | 1.59%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 1.59%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.59%   |
| Broadcom BCM20702A0                                                                 | 4         | 1.59%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.2%    |
| Intel Bluetooth Device                                                              | 3         | 1.2%    |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 1.2%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.2%    |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.8%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.8%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.8%    |
| Foxconn / Hon Hai BT                                                                | 2         | 0.8%    |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.8%    |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.8%    |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.8%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.8%    |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.8%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.8%    |
| Askey Bluetooth Device                                                              | 2         | 0.8%    |
| Realtek Bluetooth Radio                                                             | 1         | 0.4%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.4%    |
| Ralink CSR BS8510                                                                   | 1         | 0.4%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.4%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.4%    |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.4%    |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.4%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.4%    |
| IMC Networks Wireless_Device                                                        | 1         | 0.4%    |
| IMC Networks Bluetooth                                                              | 1         | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.4%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.4%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.4%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.4%    |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.4%    |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.4%    |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.4%    |
| Broadcom Bluetooth                                                                  | 1         | 0.4%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.4%    |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.4%    |
| Apple Bluetooth Host Controller                                                     | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 286       | 77.3%   |
| Nvidia      | 47        | 12.7%   |
| AMD         | 35        | 9.46%   |
| Yamaha      | 1         | 0.27%   |
| CMX Systems | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 55        | 12.42%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 36        | 8.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 28        | 6.32%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 4.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 4.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 4.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 4.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.16%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 3.16%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 3.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 2.48%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 2.03%   |
| AMD FCH Azalia Controller                                                                         | 9         | 2.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.13%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.68%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.68%   |
| Nvidia Audio device                                                                               | 3         | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.68%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.45%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.45%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.45%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.45%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.45%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.45%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.23%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.23%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.23%   |
| Nvidia stereo controller                                                                          | 1         | 0.23%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.23%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.23%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.23%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.23%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 55        | 31.98%  |
| SK Hynix            | 33        | 19.19%  |
| Micron Technology   | 27        | 15.7%   |
| Kingston            | 11        | 6.4%    |
| Crucial             | 11        | 6.4%    |
| Unknown             | 9         | 5.23%   |
| Ramaxel Technology  | 9         | 5.23%   |
| A-DATA Technology   | 7         | 4.07%   |
| Elpida              | 6         | 3.49%   |
| Transcend           | 1         | 0.58%   |
| Neo Forza           | 1         | 0.58%   |
| Nanya Technology    | 1         | 0.58%   |
| Kingmax             | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 6         | 3.26%   |
| Crucial RAM CB16GS2666.C8ET 16384MB SODIMM DDR4 2667MT/s     | 6         | 3.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 2.72%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 5         | 2.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 5         | 2.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 2.17%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 4         | 2.17%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 1.63%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 1.63%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 1.63%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 3         | 1.63%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 1.63%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 3         | 1.63%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s     | 3         | 1.63%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.09%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.09%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.09%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 2         | 1.09%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 2         | 1.09%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 1.09%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 1.09%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2         | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.09%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 2         | 1.09%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.09%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 1.09%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s    | 2         | 1.09%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 1.09%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s     | 2         | 1.09%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s      | 2         | 1.09%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.09%   |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s        | 2         | 1.09%   |
| Kingston RAM ACR21D4S15HAG/8G 8GB SODIMM DDR4 2133MT/s       | 2         | 1.09%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 1600MT/s       | 2         | 1.09%   |
| Crucial RAM CB8GS2400.C8JT 8GB SODIMM DDR4 2400MT/s          | 2         | 1.09%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                  | 1         | 0.54%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 0.54%   |
| Unknown RAM Module 4GB SODIMM                                | 1         | 0.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.54%   |
| Unknown RAM Module 4096MB SODIMM                             | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 1         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR3                        | 1         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 0.54%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 1         | 0.54%   |
| Transcend RAM TS512MSK64W6H 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.54%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.54%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.54%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 0.54%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 0.54%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.54%   |
| SK Hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1333MT/s       | 1         | 0.54%   |
| SK Hynix RAM HMT112S6BFR6C-H9 1GB SODIMM DDR3 1333MT/s       | 1         | 0.54%   |
| SK Hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s     | 1         | 0.54%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 0.54%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 1         | 0.54%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 67        | 48.2%   |
| DDR3    | 58        | 41.73%  |
| DDR2    | 6         | 4.32%   |
| SDRAM   | 3         | 2.16%   |
| LPDDR4  | 2         | 1.44%   |
| LPDDR3  | 2         | 1.44%   |
| Unknown | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 129       | 95.56%  |
| Row Of Chips | 5         | 3.7%    |
| Chip         | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 69        | 43.13%  |
| 8192  | 53        | 33.13%  |
| 2048  | 20        | 12.5%   |
| 16384 | 13        | 8.13%   |
| 1024  | 5         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 44        | 28.57%  |
| 2667    | 39        | 25.32%  |
| 1334    | 14        | 9.09%   |
| 2400    | 12        | 7.79%   |
| 2133    | 11        | 7.14%   |
| 3200    | 9         | 5.84%   |
| 3266    | 6         | 3.9%    |
| 667     | 5         | 3.25%   |
| 1333    | 4         | 2.6%    |
| Unknown | 4         | 2.6%    |
| 4199    | 3         | 1.95%   |
| 1867    | 1         | 0.65%   |
| 1067    | 1         | 0.65%   |
| 800     | 1         | 0.65%   |

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
| Chicony Electronics                    | 66        | 22.76%  |
| IMC Networks                           | 63        | 21.72%  |
| Acer                                   | 29        | 10%     |
| Microdia                               | 22        | 7.59%   |
| Realtek Semiconductor                  | 21        | 7.24%   |
| Syntek                                 | 15        | 5.17%   |
| Sunplus Innovation Technology          | 14        | 4.83%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 4.14%   |
| Suyin                                  | 9         | 3.1%    |
| Lite-On Technology                     | 8         | 2.76%   |
| Ricoh                                  | 5         | 1.72%   |
| Apple                                  | 4         | 1.38%   |
| Sonix Technology                       | 3         | 1.03%   |
| Samsung Electronics                    | 3         | 1.03%   |
| Lenovo                                 | 3         | 1.03%   |
| ALi                                    | 3         | 1.03%   |
| Quanta                                 | 2         | 0.69%   |
| Pixart Imaging                         | 2         | 0.69%   |
| Primax Electronics                     | 1         | 0.34%   |
| OmniVision Technologies                | 1         | 0.34%   |
| Luxvisions Innotech Limited            | 1         | 0.34%   |
| LG Electronics                         | 1         | 0.34%   |
| Importek                               | 1         | 0.34%   |
| Alcor Micro                            | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                       | 23        | 7.93%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 14        | 4.83%   |
| IMC Networks Integrated Camera                                           | 11        | 3.79%   |
| Acer Lenovo EasyCamera                                                   | 11        | 3.79%   |
| Chicony HD WebCam                                                        | 8         | 2.76%   |
| Chicony EasyCamera                                                       | 8         | 2.76%   |
| Syntek EasyCamera                                                        | 6         | 2.07%   |
| Chicony USB2.0 HD UVC WebCam                                             | 6         | 2.07%   |
| Chicony Integrated Camera                                                | 6         | 2.07%   |
| Syntek Lenovo EasyCamera                                                 | 5         | 1.72%   |
| Sunplus HD Webcam                                                        | 5         | 1.72%   |
| Realtek USB2.0 HD UVC WebCam                                             | 5         | 1.72%   |
| Sunplus ASUS USB2.0 Webcam                                               | 4         | 1.38%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 4         | 1.38%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 4         | 1.38%   |
| Microdia Integrated_Webcam_HD                                            | 4         | 1.38%   |
| Lite-On Integrated Camera                                                | 4         | 1.38%   |
| IMC Networks Lenovo EasyCamera                                           | 4         | 1.38%   |
| Chicony Integrated HP HD Webcam                                          | 4         | 1.38%   |
| Chicony HP HD Webcam [Fixed]                                             | 4         | 1.38%   |
| Chicony HP HD Webcam                                                     | 4         | 1.38%   |
| Acer Integrated Camera                                                   | 4         | 1.38%   |
| Syntek Integrated Camera                                                 | 3         | 1.03%   |
| Sunplus Integrated_Webcam_HD                                             | 3         | 1.03%   |
| Samsung Galaxy A5 (MTP)                                                  | 3         | 1.03%   |
| Realtek USB Camera                                                       | 3         | 1.03%   |
| Microdia Sonix Integrated Webcam                                         | 3         | 1.03%   |
| Microdia Integrated Webcam                                               | 3         | 1.03%   |
| Lite-On HP HD Camera                                                     | 3         | 1.03%   |
| IMC Networks VGA UVC WebCam                                              | 3         | 1.03%   |
| IMC Networks Integrated Webcam                                           | 3         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 3         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 3         | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 3         | 1.03%   |
| ALi Gateway Webcam                                                       | 3         | 1.03%   |
| Acer SunplusIT Integrated Camera                                         | 3         | 1.03%   |
| Acer Lenovo Integrated Webcam                                            | 3         | 1.03%   |
| Sonix USB2.0 HD UVC WebCam                                               | 2         | 0.69%   |
| Realtek HD WebCam                                                        | 2         | 0.69%   |
| Pixart Imaging USB_2.0_Webcam                                            | 2         | 0.69%   |
| Lenovo CNF7237&CNF7238                                                   | 2         | 0.69%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 0.69%   |
| Chicony Lenovo EasyCamera                                                | 2         | 0.69%   |
| Chicony HP Webcam [2 MP Macro]                                           | 2         | 0.69%   |
| Chicony HP Truevision HD                                                 | 2         | 0.69%   |
| Chicony HP HD Camera                                                     | 2         | 0.69%   |
| Chicony 1.3M HD WebCam                                                   | 2         | 0.69%   |
| Acer EasyCamera                                                          | 2         | 0.69%   |
| Acer BisonCam, NB Pro                                                    | 2         | 0.69%   |
| Syntek USB Video Device                                                  | 1         | 0.34%   |
| Suyin USB 2.0 UVC 1.3M WebCam                                            | 1         | 0.34%   |
| Suyin Sony Visual Communication Camera                                   | 1         | 0.34%   |
| Suyin Laptop_Integrated_Webcam_2HDM                                      | 1         | 0.34%   |
| Suyin Integrated_Webcam_2M                                               | 1         | 0.34%   |
| Suyin Integrated Webcam                                                  | 1         | 0.34%   |
| Suyin HD Video WebCam                                                    | 1         | 0.34%   |
| Suyin Asus Integrated Webcam                                             | 1         | 0.34%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 0.34%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)              | 1         | 0.34%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 31        | 42.47%  |
| Shenzhen Goodix Technology | 12        | 16.44%  |
| Synaptics                  | 8         | 10.96%  |
| Upek                       | 7         | 9.59%   |
| Elan Microelectronics      | 7         | 9.59%   |
| AuthenTec                  | 4         | 5.48%   |
| LighTuning Technology      | 3         | 4.11%   |
| STMicroelectronics         | 1         | 1.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 14        | 19.18%  |
| Validity Sensors VFS491                                | 9         | 12.33%  |
| Shenzhen Goodix  FingerPrint Device                    | 8         | 10.96%  |
| Elan ELAN:Fingerprint                                  | 7         | 9.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 6         | 8.22%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 4.11%   |
| Synaptics  WBDI                                        | 3         | 4.11%   |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 4.11%   |
| Unknown                                                | 3         | 4.11%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 2.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 2         | 2.74%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 2.74%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 1.37%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 1.37%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 1.37%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 1.37%   |
| Validity Sensors Fingerprint scanner                   | 1         | 1.37%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 1.37%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 1.37%   |
| Shenzhen Goodix FingerPrint                            | 1         | 1.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 1.37%   |
| AuthenTec Fingerprint Sensor                           | 1         | 1.37%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 46.15%  |
| Alcor Micro | 4         | 30.77%  |
| O2 Micro    | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 30.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 15.38%  |
| Broadcom 5880                                                                | 2         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 184       | 58.04%  |
| 1     | 97        | 30.6%   |
| 2     | 29        | 9.15%   |
| 3     | 4         | 1.26%   |
| 7     | 1         | 0.32%   |
| 5     | 1         | 0.32%   |
| 4     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 73        | 41.71%  |
| Graphics card            | 45        | 25.71%  |
| Bluetooth                | 14        | 8%      |
| Net/wireless             | 12        | 6.86%   |
| Chipcard                 | 12        | 6.86%   |
| Communication controller | 5         | 2.86%   |
| Camera                   | 5         | 2.86%   |
| Storage                  | 4         | 2.29%   |
| Sound                    | 2         | 1.14%   |
| Card reader              | 2         | 1.14%   |
| Net/ethernet             | 1         | 0.57%   |

