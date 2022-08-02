Linux in Iran - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Linux in Iran.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Iran/Desktop/README.md) and [notebooks](/Location/Iran/Notebook/README.md).

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

Total: 707

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E7470              | Notebook    | [0851479f6b](https://linux-hardware.org/?probe=0851479f6b) | Aug 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [9996781aa7](https://linux-hardware.org/?probe=9996781aa7) | Jul 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [117f3d3969](https://linux-hardware.org/?probe=117f3d3969) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb442470d4](https://linux-hardware.org/?probe=fb442470d4) | Jul 24, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [6f2adb5629](https://linux-hardware.org/?probe=6f2adb5629) | Jul 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [bcb07d1cc9](https://linux-hardware.org/?probe=bcb07d1cc9) | Jul 16, 2022 |
| HP            | G62                         | Notebook    | [020a13b927](https://linux-hardware.org/?probe=020a13b927) | Jul 16, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4e8aa38fb4](https://linux-hardware.org/?probe=4e8aa38fb4) | Jul 11, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| ASUSTek       | N43JQ                       | Notebook    | [d73f714472](https://linux-hardware.org/?probe=d73f714472) | Jul 01, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [56e348118b](https://linux-hardware.org/?probe=56e348118b) | Jun 26, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [e1d53a776f](https://linux-hardware.org/?probe=e1d53a776f) | Jun 22, 2022 |
| HP            | 3397                        | Desktop     | [337e956c95](https://linux-hardware.org/?probe=337e956c95) | Jun 22, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [43cf14bdd7](https://linux-hardware.org/?probe=43cf14bdd7) | Jun 22, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [83a04b4dc4](https://linux-hardware.org/?probe=83a04b4dc4) | Jun 17, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2893254eb3](https://linux-hardware.org/?probe=2893254eb3) | Jun 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e64a2a0eeb](https://linux-hardware.org/?probe=e64a2a0eeb) | Jun 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b0e13d9a94](https://linux-hardware.org/?probe=b0e13d9a94) | Jun 05, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [05094a5491](https://linux-hardware.org/?probe=05094a5491) | Jun 05, 2022 |
| Lenovo        | ThinkPad E420 1141E9G       | Notebook    | [48b5588cbd](https://linux-hardware.org/?probe=48b5588cbd) | Jun 01, 2022 |
| ASUSTek       | Maximus II Formula          | Desktop     | [84df720c51](https://linux-hardware.org/?probe=84df720c51) | May 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [27dffb7089](https://linux-hardware.org/?probe=27dffb7089) | May 29, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a4d6e798d](https://linux-hardware.org/?probe=8a4d6e798d) | May 26, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [2771a53784](https://linux-hardware.org/?probe=2771a53784) | May 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [232b74e86b](https://linux-hardware.org/?probe=232b74e86b) | May 17, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [1bce5b14e3](https://linux-hardware.org/?probe=1bce5b14e3) | May 17, 2022 |
| MSI           | 760GM-P33                   | Desktop     | [d37fca6b00](https://linux-hardware.org/?probe=d37fca6b00) | May 17, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [247fc8ed78](https://linux-hardware.org/?probe=247fc8ed78) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a9646dc78](https://linux-hardware.org/?probe=8a9646dc78) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b6cb96e1d0](https://linux-hardware.org/?probe=b6cb96e1d0) | May 13, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [1d71c877c7](https://linux-hardware.org/?probe=1d71c877c7) | May 13, 2022 |
| Lenovo        | ThinkPad X230 23253QU       | Notebook    | [fde2b81a1c](https://linux-hardware.org/?probe=fde2b81a1c) | May 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [b53c2836e9](https://linux-hardware.org/?probe=b53c2836e9) | Apr 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [cb2bc8f53e](https://linux-hardware.org/?probe=cb2bc8f53e) | Apr 21, 2022 |
| Lenovo        | ThinkPad SL 2743X12         | Notebook    | [ad56efc5ff](https://linux-hardware.org/?probe=ad56efc5ff) | Apr 19, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [020929c7b4](https://linux-hardware.org/?probe=020929c7b4) | Apr 17, 2022 |
| HP            | 3048h                       | Desktop     | [2d19799047](https://linux-hardware.org/?probe=2d19799047) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [a7da4b6ee0](https://linux-hardware.org/?probe=a7da4b6ee0) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [a0ab75ee00](https://linux-hardware.org/?probe=a0ab75ee00) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36c4b80dbb](https://linux-hardware.org/?probe=36c4b80dbb) | Apr 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000RAD     | Notebook    | [6f4db41ef5](https://linux-hardware.org/?probe=6f4db41ef5) | Apr 06, 2022 |
| Acer          | Aspire xxxx                 | Notebook    | [c389f4acb2](https://linux-hardware.org/?probe=c389f4acb2) | Apr 06, 2022 |
| Dell          | Latitude E7240              | Notebook    | [242cae44a5](https://linux-hardware.org/?probe=242cae44a5) | Apr 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [c0dd92f23c](https://linux-hardware.org/?probe=c0dd92f23c) | Apr 03, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [bfc20224d0](https://linux-hardware.org/?probe=bfc20224d0) | Mar 28, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [6e0eef7b54](https://linux-hardware.org/?probe=6e0eef7b54) | Mar 25, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [08a511ac81](https://linux-hardware.org/?probe=08a511ac81) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [61b36dcd42](https://linux-hardware.org/?probe=61b36dcd42) | Mar 18, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Dell          | Latitude E7470              | Notebook    | [2eca1925d5](https://linux-hardware.org/?probe=2eca1925d5) | Mar 16, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b10d8b3a00](https://linux-hardware.org/?probe=b10d8b3a00) | Mar 16, 2022 |
| Dell          | Latitude E6530              | Notebook    | [2c3bfeff1d](https://linux-hardware.org/?probe=2c3bfeff1d) | Mar 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [472d23c4f4](https://linux-hardware.org/?probe=472d23c4f4) | Mar 13, 2022 |
| Gigabyte      | G1.Sniper 5                 | Desktop     | [1ee0fc40a2](https://linux-hardware.org/?probe=1ee0fc40a2) | Mar 12, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [0d2de64455](https://linux-hardware.org/?probe=0d2de64455) | Mar 06, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [76da8a616f](https://linux-hardware.org/?probe=76da8a616f) | Mar 05, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [91eafd1ed4](https://linux-hardware.org/?probe=91eafd1ed4) | Mar 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [dad6067f40](https://linux-hardware.org/?probe=dad6067f40) | Mar 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [29926fb03b](https://linux-hardware.org/?probe=29926fb03b) | Mar 03, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [071f146979](https://linux-hardware.org/?probe=071f146979) | Feb 24, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [fa0603a25d](https://linux-hardware.org/?probe=fa0603a25d) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4d49233d4b](https://linux-hardware.org/?probe=4d49233d4b) | Feb 11, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [8294f013e8](https://linux-hardware.org/?probe=8294f013e8) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [93ca64d766](https://linux-hardware.org/?probe=93ca64d766) | Jan 28, 2022 |
| HP            | 8054                        | Desktop     | [332217129d](https://linux-hardware.org/?probe=332217129d) | Jan 26, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [c48fbc97e2](https://linux-hardware.org/?probe=c48fbc97e2) | Jan 22, 2022 |
| ECS           | H61H2-A                     | Desktop     | [90c26876b2](https://linux-hardware.org/?probe=90c26876b2) | Jan 21, 2022 |
| Alienware     | 17 R3                       | Notebook    | [032772ad42](https://linux-hardware.org/?probe=032772ad42) | Jan 20, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [e800e249d1](https://linux-hardware.org/?probe=e800e249d1) | Jan 19, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [104263a808](https://linux-hardware.org/?probe=104263a808) | Jan 19, 2022 |
| ECS           | H61H2-A                     | Desktop     | [518e31fcb0](https://linux-hardware.org/?probe=518e31fcb0) | Jan 13, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [6875440733](https://linux-hardware.org/?probe=6875440733) | Jan 10, 2022 |
| ASUSTek       | X450LC                      | Notebook    | [8228658808](https://linux-hardware.org/?probe=8228658808) | Jan 09, 2022 |
| ECS           | H61H2-A                     | Desktop     | [47fb5347c0](https://linux-hardware.org/?probe=47fb5347c0) | Jan 06, 2022 |
| ECS           | H61H2-A                     | Desktop     | [fa589d8ed4](https://linux-hardware.org/?probe=fa589d8ed4) | Jan 06, 2022 |
| HP            | 806A                        | Desktop     | [d7519db95a](https://linux-hardware.org/?probe=d7519db95a) | Jan 02, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [ba7acc9c68](https://linux-hardware.org/?probe=ba7acc9c68) | Jan 01, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [a175657549](https://linux-hardware.org/?probe=a175657549) | Dec 31, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [48423d0bef](https://linux-hardware.org/?probe=48423d0bef) | Dec 31, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [71a50bcb50](https://linux-hardware.org/?probe=71a50bcb50) | Dec 30, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d8d81e5c50](https://linux-hardware.org/?probe=d8d81e5c50) | Dec 30, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [71135c1724](https://linux-hardware.org/?probe=71135c1724) | Dec 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [9f22de7369](https://linux-hardware.org/?probe=9f22de7369) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [dcbbdb5fc5](https://linux-hardware.org/?probe=dcbbdb5fc5) | Dec 23, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [5408a1a82b](https://linux-hardware.org/?probe=5408a1a82b) | Dec 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [261f98a324](https://linux-hardware.org/?probe=261f98a324) | Dec 19, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [8e802c50ad](https://linux-hardware.org/?probe=8e802c50ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [7b6f9acbf8](https://linux-hardware.org/?probe=7b6f9acbf8) | Dec 15, 2021 |
| HP            | 3397                        | Desktop     | [83d7b8fe86](https://linux-hardware.org/?probe=83d7b8fe86) | Dec 12, 2021 |
| HP            | 3397                        | Desktop     | [469adb677f](https://linux-hardware.org/?probe=469adb677f) | Dec 12, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [b4a346e899](https://linux-hardware.org/?probe=b4a346e899) | Dec 11, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [2c739999fa](https://linux-hardware.org/?probe=2c739999fa) | Dec 10, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [8473dd1cc0](https://linux-hardware.org/?probe=8473dd1cc0) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [68820e21d2](https://linux-hardware.org/?probe=68820e21d2) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [c7e180ab84](https://linux-hardware.org/?probe=c7e180ab84) | Dec 08, 2021 |
| Dell          | Latitude E7470              | Notebook    | [06666f541b](https://linux-hardware.org/?probe=06666f541b) | Dec 07, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [7eed1618fe](https://linux-hardware.org/?probe=7eed1618fe) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [01c7adcf94](https://linux-hardware.org/?probe=01c7adcf94) | Nov 28, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6eff02505f](https://linux-hardware.org/?probe=6eff02505f) | Nov 27, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [92968d4a23](https://linux-hardware.org/?probe=92968d4a23) | Nov 27, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [005b267983](https://linux-hardware.org/?probe=005b267983) | Nov 22, 2021 |
| ASUSTek       | GL702VMK                    | Notebook    | [ff58d2a76e](https://linux-hardware.org/?probe=ff58d2a76e) | Nov 21, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [81a7c19597](https://linux-hardware.org/?probe=81a7c19597) | Nov 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [f119e55cf9](https://linux-hardware.org/?probe=f119e55cf9) | Nov 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Gigabyte      | P41T-D3P                    | Desktop     | [54a25af09a](https://linux-hardware.org/?probe=54a25af09a) | Nov 11, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [20aa404ab6](https://linux-hardware.org/?probe=20aa404ab6) | Nov 10, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [cfafa7735b](https://linux-hardware.org/?probe=cfafa7735b) | Nov 08, 2021 |
| Dell          | Latitude E7240              | Notebook    | [366228fab6](https://linux-hardware.org/?probe=366228fab6) | Nov 05, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [1e136c311c](https://linux-hardware.org/?probe=1e136c311c) | Nov 03, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d098305f2a](https://linux-hardware.org/?probe=d098305f2a) | Oct 30, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d99bdece1d](https://linux-hardware.org/?probe=d99bdece1d) | Oct 30, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8db63e7a74](https://linux-hardware.org/?probe=8db63e7a74) | Oct 28, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [75b53e8d45](https://linux-hardware.org/?probe=75b53e8d45) | Oct 27, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [19cdc9b391](https://linux-hardware.org/?probe=19cdc9b391) | Oct 26, 2021 |
| Sony          | VPCSA25GX                   | Notebook    | [be4db20b0e](https://linux-hardware.org/?probe=be4db20b0e) | Oct 25, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [6ab1ce41db](https://linux-hardware.org/?probe=6ab1ce41db) | Oct 25, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [6547cded19](https://linux-hardware.org/?probe=6547cded19) | Oct 22, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [30c1b322ad](https://linux-hardware.org/?probe=30c1b322ad) | Oct 22, 2021 |
| ASUSTek       | U56E                        | Notebook    | [a610876405](https://linux-hardware.org/?probe=a610876405) | Oct 20, 2021 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [4e6bceb431](https://linux-hardware.org/?probe=4e6bceb431) | Oct 18, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [783eeaaa01](https://linux-hardware.org/?probe=783eeaaa01) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [87c7c24dcc](https://linux-hardware.org/?probe=87c7c24dcc) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [0d9ad64b08](https://linux-hardware.org/?probe=0d9ad64b08) | Oct 15, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [cce3e9bd74](https://linux-hardware.org/?probe=cce3e9bd74) | Oct 12, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [398dedabb8](https://linux-hardware.org/?probe=398dedabb8) | Oct 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [24efeaacb7](https://linux-hardware.org/?probe=24efeaacb7) | Oct 07, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [23d2e1a73d](https://linux-hardware.org/?probe=23d2e1a73d) | Oct 06, 2021 |
| HP            | ProBook 440 G2              | Notebook    | [cc83275513](https://linux-hardware.org/?probe=cc83275513) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325655d6c5](https://linux-hardware.org/?probe=325655d6c5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6cfb3f0c44](https://linux-hardware.org/?probe=6cfb3f0c44) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b633c9e1d1](https://linux-hardware.org/?probe=b633c9e1d1) | Sep 28, 2021 |
| ASUSTek       | T103HAF                     | Tablet      | [b2d1b00b0a](https://linux-hardware.org/?probe=b2d1b00b0a) | Sep 28, 2021 |
| ASRock        | B85M                        | Desktop     | [566089bd43](https://linux-hardware.org/?probe=566089bd43) | Sep 27, 2021 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [eec5db351d](https://linux-hardware.org/?probe=eec5db351d) | Sep 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0e614dfffe](https://linux-hardware.org/?probe=0e614dfffe) | Sep 27, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [3c4378f506](https://linux-hardware.org/?probe=3c4378f506) | Sep 25, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9b27471e86](https://linux-hardware.org/?probe=9b27471e86) | Sep 23, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [2b74c7b1ff](https://linux-hardware.org/?probe=2b74c7b1ff) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [2b132c74b6](https://linux-hardware.org/?probe=2b132c74b6) | Sep 16, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [ca2bc77aa5](https://linux-hardware.org/?probe=ca2bc77aa5) | Sep 16, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | Notebook    | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [ec0cd5d69b](https://linux-hardware.org/?probe=ec0cd5d69b) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [7797008e19](https://linux-hardware.org/?probe=7797008e19) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [07d1890920](https://linux-hardware.org/?probe=07d1890920) | Sep 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [a6221df8f8](https://linux-hardware.org/?probe=a6221df8f8) | Sep 10, 2021 |
| ASUSTek       | X540UV                      | Notebook    | [b0a231831a](https://linux-hardware.org/?probe=b0a231831a) | Sep 09, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [d47d63a84f](https://linux-hardware.org/?probe=d47d63a84f) | Sep 07, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [453f65a5e7](https://linux-hardware.org/?probe=453f65a5e7) | Sep 07, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [b915ae27b7](https://linux-hardware.org/?probe=b915ae27b7) | Sep 06, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [62fc103f71](https://linux-hardware.org/?probe=62fc103f71) | Sep 06, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [016672b182](https://linux-hardware.org/?probe=016672b182) | Sep 03, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [b011298d66](https://linux-hardware.org/?probe=b011298d66) | Sep 01, 2021 |
| MSI           | Prestige 14 A10RB           | Notebook    | [2aaa6d05d2](https://linux-hardware.org/?probe=2aaa6d05d2) | Sep 01, 2021 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [2044660bb8](https://linux-hardware.org/?probe=2044660bb8) | Aug 30, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | Desktop     | [0e5100e716](https://linux-hardware.org/?probe=0e5100e716) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | Desktop     | [0bf997753c](https://linux-hardware.org/?probe=0bf997753c) | Aug 29, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [9f01a4629a](https://linux-hardware.org/?probe=9f01a4629a) | Aug 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [de74046226](https://linux-hardware.org/?probe=de74046226) | Aug 23, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [19a7dfc92a](https://linux-hardware.org/?probe=19a7dfc92a) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [bfe60273f6](https://linux-hardware.org/?probe=bfe60273f6) | Aug 09, 2021 |
| HP            | ZBook 15                    | Notebook    | [1a67896055](https://linux-hardware.org/?probe=1a67896055) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | Notebook    | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [31891cbc13](https://linux-hardware.org/?probe=31891cbc13) | Aug 08, 2021 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [fe27de6bbc](https://linux-hardware.org/?probe=fe27de6bbc) | Aug 07, 2021 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [407501f166](https://linux-hardware.org/?probe=407501f166) | Aug 05, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [1e165352ad](https://linux-hardware.org/?probe=1e165352ad) | Aug 04, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [a5c472e082](https://linux-hardware.org/?probe=a5c472e082) | Aug 01, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [538eb1efa0](https://linux-hardware.org/?probe=538eb1efa0) | Aug 01, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [13e3cf7a5f](https://linux-hardware.org/?probe=13e3cf7a5f) | Jul 29, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [063facd29a](https://linux-hardware.org/?probe=063facd29a) | Jul 28, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [4b49f7026f](https://linux-hardware.org/?probe=4b49f7026f) | Jul 27, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [2bd8f0dd2e](https://linux-hardware.org/?probe=2bd8f0dd2e) | Jul 27, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [afb9cb6674](https://linux-hardware.org/?probe=afb9cb6674) | Jul 27, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [5d118fd4cc](https://linux-hardware.org/?probe=5d118fd4cc) | Jul 26, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | ProBook 4540s               | Notebook    | [719b37c9ac](https://linux-hardware.org/?probe=719b37c9ac) | Jul 20, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [0ae43f5015](https://linux-hardware.org/?probe=0ae43f5015) | Jul 20, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [b26638f586](https://linux-hardware.org/?probe=b26638f586) | Jul 17, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [8a28a4f7f5](https://linux-hardware.org/?probe=8a28a4f7f5) | Jul 17, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [08f5207ee6](https://linux-hardware.org/?probe=08f5207ee6) | Jul 17, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [b3bb7e1295](https://linux-hardware.org/?probe=b3bb7e1295) | Jul 17, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [01b8cc373f](https://linux-hardware.org/?probe=01b8cc373f) | Jul 13, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| HP            | Notebook                    | Notebook    | [3fc4cb2f55](https://linux-hardware.org/?probe=3fc4cb2f55) | Jul 09, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [90a20b185b](https://linux-hardware.org/?probe=90a20b185b) | Jul 03, 2021 |
| Gigabyte      | 8IPE1000-G/L                | Desktop     | [0301b9707b](https://linux-hardware.org/?probe=0301b9707b) | Jun 29, 2021 |
| Lenovo        | ThinkPad E560 20EV0005AD    | Notebook    | [fab11e73ee](https://linux-hardware.org/?probe=fab11e73ee) | Jun 29, 2021 |
| Acer          | Aspire 4736Z                | Notebook    | [6a5d92699d](https://linux-hardware.org/?probe=6a5d92699d) | Jun 23, 2021 |
| Dell          | Latitude D420               | Notebook    | [5f0d609bef](https://linux-hardware.org/?probe=5f0d609bef) | Jun 21, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [7026c20c97](https://linux-hardware.org/?probe=7026c20c97) | Jun 20, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [f34a1bbe5a](https://linux-hardware.org/?probe=f34a1bbe5a) | Jun 20, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [1343b5bb5d](https://linux-hardware.org/?probe=1343b5bb5d) | Jun 20, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [5963dd2256](https://linux-hardware.org/?probe=5963dd2256) | Jun 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [4af988fc2f](https://linux-hardware.org/?probe=4af988fc2f) | Jun 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [1fd8a9e8c8](https://linux-hardware.org/?probe=1fd8a9e8c8) | Jun 16, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| ASUSTek       | Z11PG-D24 Series            | Server      | [e4be3f2344](https://linux-hardware.org/?probe=e4be3f2344) | Jun 12, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [28e717743a](https://linux-hardware.org/?probe=28e717743a) | Jun 06, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [35b68a0b4a](https://linux-hardware.org/?probe=35b68a0b4a) | Jun 06, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [4b5debd7a6](https://linux-hardware.org/?probe=4b5debd7a6) | Jun 04, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [4333473e1e](https://linux-hardware.org/?probe=4333473e1e) | Jun 03, 2021 |
| HP            | ProBook 4520s               | Notebook    | [b0a9a196db](https://linux-hardware.org/?probe=b0a9a196db) | Jun 03, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [b3206cba40](https://linux-hardware.org/?probe=b3206cba40) | Jun 03, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [043730ad50](https://linux-hardware.org/?probe=043730ad50) | Jun 01, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [1023832c74](https://linux-hardware.org/?probe=1023832c74) | Jun 01, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [2ff6c9500b](https://linux-hardware.org/?probe=2ff6c9500b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [74d1da4b68](https://linux-hardware.org/?probe=74d1da4b68) | May 28, 2021 |
| ASUSTek       | X550MJ                      | Notebook    | [208fc3f30f](https://linux-hardware.org/?probe=208fc3f30f) | May 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [28d19f1a59](https://linux-hardware.org/?probe=28d19f1a59) | May 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [512cc44d82](https://linux-hardware.org/?probe=512cc44d82) | May 21, 2021 |
| ASUSTek       | K53SM                       | Notebook    | [f0199bc53d](https://linux-hardware.org/?probe=f0199bc53d) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [1417eccc8b](https://linux-hardware.org/?probe=1417eccc8b) | May 15, 2021 |
| HP            | EliteBook 725 G2            | Notebook    | [5dddeca3e8](https://linux-hardware.org/?probe=5dddeca3e8) | May 09, 2021 |
| MSI           | PH67A-C43                   | Desktop     | [8e818ce79a](https://linux-hardware.org/?probe=8e818ce79a) | May 05, 2021 |
| Acer          | Aspire V3-574G              | Notebook    | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [2d12301b1c](https://linux-hardware.org/?probe=2d12301b1c) | May 05, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [57540cdfa4](https://linux-hardware.org/?probe=57540cdfa4) | May 03, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8f0e9df209](https://linux-hardware.org/?probe=8f0e9df209) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [940758b420](https://linux-hardware.org/?probe=940758b420) | Apr 27, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [ced3a1165d](https://linux-hardware.org/?probe=ced3a1165d) | Apr 24, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [eeb73d1c4a](https://linux-hardware.org/?probe=eeb73d1c4a) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [93671f3ecc](https://linux-hardware.org/?probe=93671f3ecc) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [9fbf2707b0](https://linux-hardware.org/?probe=9fbf2707b0) | Apr 19, 2021 |
| ASUSTek       | X555LF                      | Notebook    | [eb9637ae4a](https://linux-hardware.org/?probe=eb9637ae4a) | Apr 19, 2021 |
| Lenovo        | ThinkPad E590 20NB0057AD    | Notebook    | [d06cfc6dee](https://linux-hardware.org/?probe=d06cfc6dee) | Apr 18, 2021 |
| Acer          | AOD260                      | Notebook    | [97f6b98307](https://linux-hardware.org/?probe=97f6b98307) | Apr 16, 2021 |
| Lenovo        | ThinkPad T470p 20J6S08M0... | Notebook    | [84619b1b45](https://linux-hardware.org/?probe=84619b1b45) | Apr 15, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [1dcb2a173e](https://linux-hardware.org/?probe=1dcb2a173e) | Apr 14, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [28d13bbb26](https://linux-hardware.org/?probe=28d13bbb26) | Apr 14, 2021 |
| Gigabyte      | M52S-S3P                    | Desktop     | [494ac8b449](https://linux-hardware.org/?probe=494ac8b449) | Apr 11, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [29e4ff83db](https://linux-hardware.org/?probe=29e4ff83db) | Apr 10, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [7713767fa6](https://linux-hardware.org/?probe=7713767fa6) | Apr 10, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [9c00d55213](https://linux-hardware.org/?probe=9c00d55213) | Apr 10, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9a9c3c8d26](https://linux-hardware.org/?probe=9a9c3c8d26) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [5b0c97ade1](https://linux-hardware.org/?probe=5b0c97ade1) | Apr 09, 2021 |
| MSI           | CR610M                      | Notebook    | [e2e00880a3](https://linux-hardware.org/?probe=e2e00880a3) | Apr 08, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [60168d5b6d](https://linux-hardware.org/?probe=60168d5b6d) | Apr 07, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [ddda7566c5](https://linux-hardware.org/?probe=ddda7566c5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [5fb915669a](https://linux-hardware.org/?probe=5fb915669a) | Apr 03, 2021 |
| ASUSTek       | H61M-C                      | Desktop     | [c39fc169bf](https://linux-hardware.org/?probe=c39fc169bf) | Apr 02, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [c5e7e65164](https://linux-hardware.org/?probe=c5e7e65164) | Apr 01, 2021 |
| HP            | EliteBook 745 G4            | Notebook    | [a5888bbded](https://linux-hardware.org/?probe=a5888bbded) | Apr 01, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [9a4a054203](https://linux-hardware.org/?probe=9a4a054203) | Apr 01, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [9c2661508e](https://linux-hardware.org/?probe=9c2661508e) | Mar 30, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [bacb9e5030](https://linux-hardware.org/?probe=bacb9e5030) | Mar 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [344eec241a](https://linux-hardware.org/?probe=344eec241a) | Mar 21, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | Notebook    | [ca815648fc](https://linux-hardware.org/?probe=ca815648fc) | Mar 17, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [d5d788f2f3](https://linux-hardware.org/?probe=d5d788f2f3) | Mar 15, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [89b0451670](https://linux-hardware.org/?probe=89b0451670) | Mar 14, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [ed8b926f53](https://linux-hardware.org/?probe=ed8b926f53) | Mar 14, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | Notebook    | [75ba14ee94](https://linux-hardware.org/?probe=75ba14ee94) | Mar 14, 2021 |
| HP            | 3397                        | Desktop     | [13a7f8c4c2](https://linux-hardware.org/?probe=13a7f8c4c2) | Mar 08, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [be98339598](https://linux-hardware.org/?probe=be98339598) | Mar 07, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [eb31b2ffb6](https://linux-hardware.org/?probe=eb31b2ffb6) | Mar 07, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [fd19b6b1c8](https://linux-hardware.org/?probe=fd19b6b1c8) | Mar 07, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [502ef11b75](https://linux-hardware.org/?probe=502ef11b75) | Mar 07, 2021 |
| Gigabyte      | GA-M55SLI-S4                | Desktop     | [43d0cb9ac1](https://linux-hardware.org/?probe=43d0cb9ac1) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [b7e39a92a0](https://linux-hardware.org/?probe=b7e39a92a0) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [7ca6ad9361](https://linux-hardware.org/?probe=7ca6ad9361) | Mar 06, 2021 |
| ASUSTek       | P5E                         | Desktop     | [5681b93aaf](https://linux-hardware.org/?probe=5681b93aaf) | Mar 06, 2021 |
| ASUSTek       | P5E                         | Desktop     | [9f858aaf27](https://linux-hardware.org/?probe=9f858aaf27) | Mar 05, 2021 |
| ASUSTek       | K42JK                       | Notebook    | [bae11d222f](https://linux-hardware.org/?probe=bae11d222f) | Mar 04, 2021 |
| ASUSTek       | K42JK                       | Notebook    | [3ae670828a](https://linux-hardware.org/?probe=3ae670828a) | Mar 03, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [fd21e67a3c](https://linux-hardware.org/?probe=fd21e67a3c) | Feb 28, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [429c09a059](https://linux-hardware.org/?probe=429c09a059) | Feb 28, 2021 |
| HP            | Pavilion g6                 | Notebook    | [2ce61d58bf](https://linux-hardware.org/?probe=2ce61d58bf) | Feb 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [dda65f86ac](https://linux-hardware.org/?probe=dda65f86ac) | Feb 24, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e3ff93ab0a](https://linux-hardware.org/?probe=e3ff93ab0a) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [ab787a4172](https://linux-hardware.org/?probe=ab787a4172) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [7ba0b6a17d](https://linux-hardware.org/?probe=7ba0b6a17d) | Feb 21, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [b1b8587cdb](https://linux-hardware.org/?probe=b1b8587cdb) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [d45ed4ad08](https://linux-hardware.org/?probe=d45ed4ad08) | Feb 19, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [b6a8851986](https://linux-hardware.org/?probe=b6a8851986) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [520780b02d](https://linux-hardware.org/?probe=520780b02d) | Feb 18, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [62c9e819cd](https://linux-hardware.org/?probe=62c9e819cd) | Feb 17, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [8070e672a7](https://linux-hardware.org/?probe=8070e672a7) | Feb 15, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ee986e1fdd](https://linux-hardware.org/?probe=ee986e1fdd) | Feb 11, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b661aa21f1](https://linux-hardware.org/?probe=b661aa21f1) | Feb 09, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [0c9067579c](https://linux-hardware.org/?probe=0c9067579c) | Feb 09, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [ab4bc22a87](https://linux-hardware.org/?probe=ab4bc22a87) | Feb 06, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [5e9aa1c3de](https://linux-hardware.org/?probe=5e9aa1c3de) | Feb 06, 2021 |
| ASUSTek       | X456URK                     | Notebook    | [6c3b5bdfb1](https://linux-hardware.org/?probe=6c3b5bdfb1) | Feb 05, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [9de86c8038](https://linux-hardware.org/?probe=9de86c8038) | Feb 05, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [d383b4a5e7](https://linux-hardware.org/?probe=d383b4a5e7) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [2bd7b5699d](https://linux-hardware.org/?probe=2bd7b5699d) | Feb 05, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [f1f4fbad09](https://linux-hardware.org/?probe=f1f4fbad09) | Feb 03, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [0df26493a8](https://linux-hardware.org/?probe=0df26493a8) | Feb 03, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [82920966cf](https://linux-hardware.org/?probe=82920966cf) | Feb 01, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d82031935e](https://linux-hardware.org/?probe=d82031935e) | Feb 01, 2021 |
| ASUSTek       | N56JR                       | Notebook    | [29ad612f88](https://linux-hardware.org/?probe=29ad612f88) | Jan 28, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [2960ce1b31](https://linux-hardware.org/?probe=2960ce1b31) | Jan 27, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [b97b822412](https://linux-hardware.org/?probe=b97b822412) | Jan 27, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [a0eb5fc713](https://linux-hardware.org/?probe=a0eb5fc713) | Jan 20, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [2fa2f12de6](https://linux-hardware.org/?probe=2fa2f12de6) | Jan 19, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [537d05799c](https://linux-hardware.org/?probe=537d05799c) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [66598d3f69](https://linux-hardware.org/?probe=66598d3f69) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [113406e67d](https://linux-hardware.org/?probe=113406e67d) | Jan 15, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [703dd398d1](https://linux-hardware.org/?probe=703dd398d1) | Jan 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [85c5454ed1](https://linux-hardware.org/?probe=85c5454ed1) | Jan 14, 2021 |
| ASUSTek       | X542UN                      | Notebook    | [44633c4ff2](https://linux-hardware.org/?probe=44633c4ff2) | Jan 13, 2021 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [d8aafdef30](https://linux-hardware.org/?probe=d8aafdef30) | Jan 10, 2021 |
| Sony          | SVF15N12SGB                 | Notebook    | [3ff592b868](https://linux-hardware.org/?probe=3ff592b868) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34483... | Notebook    | [4e6cc9fdc4](https://linux-hardware.org/?probe=4e6cc9fdc4) | Jan 03, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [96280026fb](https://linux-hardware.org/?probe=96280026fb) | Jan 03, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [7243a2df4f](https://linux-hardware.org/?probe=7243a2df4f) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [4d96f1db71](https://linux-hardware.org/?probe=4d96f1db71) | Dec 31, 2020 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [be00a7c4e5](https://linux-hardware.org/?probe=be00a7c4e5) | Dec 28, 2020 |
| Acer          | Aspire 5755G                | Notebook    | [5577ccef28](https://linux-hardware.org/?probe=5577ccef28) | Dec 28, 2020 |
| HP            | ProBook 4540s               | Notebook    | [86bd405fac](https://linux-hardware.org/?probe=86bd405fac) | Dec 27, 2020 |
| HP            | ProBook 4540s               | Notebook    | [7a93e1b05a](https://linux-hardware.org/?probe=7a93e1b05a) | Dec 27, 2020 |
| Dell          | Vostro 1015                 | Notebook    | [9be1d69693](https://linux-hardware.org/?probe=9be1d69693) | Dec 26, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [9582155494](https://linux-hardware.org/?probe=9582155494) | Dec 25, 2020 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [f7f32358db](https://linux-hardware.org/?probe=f7f32358db) | Dec 24, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ec5fac5f1d](https://linux-hardware.org/?probe=ec5fac5f1d) | Dec 24, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [3071d9e517](https://linux-hardware.org/?probe=3071d9e517) | Dec 23, 2020 |
| MSI           | GE60 2PC                    | Notebook    | [46af0a2d84](https://linux-hardware.org/?probe=46af0a2d84) | Dec 22, 2020 |
| MSI           | GE60 2PC                    | Notebook    | [c659f6a910](https://linux-hardware.org/?probe=c659f6a910) | Dec 21, 2020 |
| HP            | 3397                        | Desktop     | [1b81310dbf](https://linux-hardware.org/?probe=1b81310dbf) | Dec 20, 2020 |
| HP            | 3397                        | Desktop     | [086227e446](https://linux-hardware.org/?probe=086227e446) | Dec 20, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T10... | Notebook    | [d5a85767cd](https://linux-hardware.org/?probe=d5a85767cd) | Dec 18, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [a6bf272580](https://linux-hardware.org/?probe=a6bf272580) | Dec 18, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [fe5ef27982](https://linux-hardware.org/?probe=fe5ef27982) | Dec 17, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [ccdd9fbe6b](https://linux-hardware.org/?probe=ccdd9fbe6b) | Dec 16, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e7e6ad670b](https://linux-hardware.org/?probe=e7e6ad670b) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | Notebook    | [03f5d24d56](https://linux-hardware.org/?probe=03f5d24d56) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | Notebook    | [886054e929](https://linux-hardware.org/?probe=886054e929) | Dec 15, 2020 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [e39c3e59b5](https://linux-hardware.org/?probe=e39c3e59b5) | Dec 13, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [67aa2554c3](https://linux-hardware.org/?probe=67aa2554c3) | Dec 10, 2020 |
| MSI           | CX62 6QL                    | Notebook    | [90a60a1e78](https://linux-hardware.org/?probe=90a60a1e78) | Dec 06, 2020 |
| MSI           | CX62 6QL                    | Notebook    | [9b4aaf5856](https://linux-hardware.org/?probe=9b4aaf5856) | Dec 06, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [d93fb9ef4a](https://linux-hardware.org/?probe=d93fb9ef4a) | Dec 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [47835d66f6](https://linux-hardware.org/?probe=47835d66f6) | Dec 01, 2020 |
| Gigabyte      | P55A-UD3P                   | Desktop     | [9f5052c50b](https://linux-hardware.org/?probe=9f5052c50b) | Nov 30, 2020 |
| Gigabyte      | P55A-UD3P                   | Desktop     | [03db05b217](https://linux-hardware.org/?probe=03db05b217) | Nov 30, 2020 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [c9c25216a4](https://linux-hardware.org/?probe=c9c25216a4) | Nov 25, 2020 |
| Sony          | VPCEH11FX                   | Notebook    | [d3ff8db043](https://linux-hardware.org/?probe=d3ff8db043) | Nov 22, 2020 |
| HP            | 2AF3                        | Desktop     | [3c07a68022](https://linux-hardware.org/?probe=3c07a68022) | Nov 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8e0bc13a31](https://linux-hardware.org/?probe=8e0bc13a31) | Nov 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [c099ac62d5](https://linux-hardware.org/?probe=c099ac62d5) | Nov 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [7787345258](https://linux-hardware.org/?probe=7787345258) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Acer          | TravelMate 5742Z            | Notebook    | [be124397e2](https://linux-hardware.org/?probe=be124397e2) | Nov 13, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3bc3e0823a](https://linux-hardware.org/?probe=3bc3e0823a) | Nov 09, 2020 |
| HP            | ProBook 4540s               | Notebook    | [4864704e84](https://linux-hardware.org/?probe=4864704e84) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [adbb505553](https://linux-hardware.org/?probe=adbb505553) | Nov 08, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [543559dfac](https://linux-hardware.org/?probe=543559dfac) | Nov 07, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [c7b7b29a68](https://linux-hardware.org/?probe=c7b7b29a68) | Nov 07, 2020 |
| Lenovo        | E5                          | Notebook    | [3b7111b4a2](https://linux-hardware.org/?probe=3b7111b4a2) | Nov 07, 2020 |
| Lenovo        | E5                          | Notebook    | [cb3bf5a3df](https://linux-hardware.org/?probe=cb3bf5a3df) | Nov 07, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [6a88e646aa](https://linux-hardware.org/?probe=6a88e646aa) | Nov 07, 2020 |
| ASUSTek       | X550VXK                     | Notebook    | [5f95436c09](https://linux-hardware.org/?probe=5f95436c09) | Nov 06, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [42ef7e253c](https://linux-hardware.org/?probe=42ef7e253c) | Nov 01, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [cba527dd9f](https://linux-hardware.org/?probe=cba527dd9f) | Nov 01, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [75bacf18a7](https://linux-hardware.org/?probe=75bacf18a7) | Oct 31, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [f6c5e1d108](https://linux-hardware.org/?probe=f6c5e1d108) | Oct 28, 2020 |
| Foxconn       | A8G-i                       | Desktop     | [b4675cde03](https://linux-hardware.org/?probe=b4675cde03) | Oct 27, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [c3cd0fcf33](https://linux-hardware.org/?probe=c3cd0fcf33) | Oct 24, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [11db584122](https://linux-hardware.org/?probe=11db584122) | Oct 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [7525ff1dde](https://linux-hardware.org/?probe=7525ff1dde) | Oct 23, 2020 |
| ASUSTek       | N552VW                      | Notebook    | [6893d4927d](https://linux-hardware.org/?probe=6893d4927d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | Notebook    | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| Lenovo        | B50-80 80EW                 | Notebook    | [c6bf9e5376](https://linux-hardware.org/?probe=c6bf9e5376) | Oct 17, 2020 |
| ASUSTek       | X505BA                      | Notebook    | [6f5c254a9f](https://linux-hardware.org/?probe=6f5c254a9f) | Oct 15, 2020 |
| Intel         | P61-S3                      | Desktop     | [efee9af681](https://linux-hardware.org/?probe=efee9af681) | Oct 13, 2020 |
| Intel         | P61-S3                      | Desktop     | [36f0f58223](https://linux-hardware.org/?probe=36f0f58223) | Oct 12, 2020 |
| Gigabyte      | 8S648FX-RZ                  | Desktop     | [c00289e6ed](https://linux-hardware.org/?probe=c00289e6ed) | Oct 11, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [2763c330eb](https://linux-hardware.org/?probe=2763c330eb) | Oct 09, 2020 |
| ASRock        | P5B-DE                      | Desktop     | [ef1c17dd39](https://linux-hardware.org/?probe=ef1c17dd39) | Oct 08, 2020 |
| ASUSTek       | UX430UA                     | Notebook    | [d6586b9bb8](https://linux-hardware.org/?probe=d6586b9bb8) | Oct 05, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [bbf7ae1125](https://linux-hardware.org/?probe=bbf7ae1125) | Oct 05, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [5996a3b895](https://linux-hardware.org/?probe=5996a3b895) | Sep 29, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [60156a645b](https://linux-hardware.org/?probe=60156a645b) | Sep 29, 2020 |
| Sony          | VPCEB1SFX                   | Notebook    | [01b67b1979](https://linux-hardware.org/?probe=01b67b1979) | Sep 27, 2020 |
| Sony          | VPCEB1SFX                   | Notebook    | [616d06a0b0](https://linux-hardware.org/?probe=616d06a0b0) | Sep 26, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [6f184c4bc8](https://linux-hardware.org/?probe=6f184c4bc8) | Sep 26, 2020 |
| ASUSTek       | K42Jc                       | Notebook    | [9808a6bb0c](https://linux-hardware.org/?probe=9808a6bb0c) | Sep 25, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [5ea9c0eca9](https://linux-hardware.org/?probe=5ea9c0eca9) | Sep 24, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [59f1e93325](https://linux-hardware.org/?probe=59f1e93325) | Sep 18, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [a91b502a98](https://linux-hardware.org/?probe=a91b502a98) | Sep 18, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [9456172087](https://linux-hardware.org/?probe=9456172087) | Sep 18, 2020 |
| Gigabyte      | B75M-D3V                    | Desktop     | [32e15ba2b5](https://linux-hardware.org/?probe=32e15ba2b5) | Sep 18, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [36d0455f5f](https://linux-hardware.org/?probe=36d0455f5f) | Sep 15, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7ad450ddd7](https://linux-hardware.org/?probe=7ad450ddd7) | Sep 14, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [5ed2d21f85](https://linux-hardware.org/?probe=5ed2d21f85) | Sep 05, 2020 |
| ASUSTek       | K52F                        | Notebook    | [1658b8903d](https://linux-hardware.org/?probe=1658b8903d) | Sep 04, 2020 |
| ASUSTek       | K52F                        | Notebook    | [b7a5d27a01](https://linux-hardware.org/?probe=b7a5d27a01) | Sep 04, 2020 |
| ASUSTek       | K42Jc                       | Notebook    | [79d7ee2e74](https://linux-hardware.org/?probe=79d7ee2e74) | Sep 04, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [61bc69e87c](https://linux-hardware.org/?probe=61bc69e87c) | Sep 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [c026f89bd8](https://linux-hardware.org/?probe=c026f89bd8) | Aug 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0ab2905b28](https://linux-hardware.org/?probe=0ab2905b28) | Aug 29, 2020 |
| MSI           | Prestige 14 A10RB           | Notebook    | [b7fff5e5cc](https://linux-hardware.org/?probe=b7fff5e5cc) | Aug 28, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [c172701a56](https://linux-hardware.org/?probe=c172701a56) | Aug 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [af595ebfde](https://linux-hardware.org/?probe=af595ebfde) | Aug 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c03d58914c](https://linux-hardware.org/?probe=c03d58914c) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [55c0c83149](https://linux-hardware.org/?probe=55c0c83149) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [e97f7b8582](https://linux-hardware.org/?probe=e97f7b8582) | Aug 02, 2020 |
| MSI           | GF63 Thin 9RC               | Notebook    | [f7eff6d78e](https://linux-hardware.org/?probe=f7eff6d78e) | Jul 28, 2020 |
| MSI           | GF63 Thin 9RC               | Notebook    | [7b12eabb3e](https://linux-hardware.org/?probe=7b12eabb3e) | Jul 28, 2020 |
| HP            | 3397                        | Desktop     | [e4e6951a4f](https://linux-hardware.org/?probe=e4e6951a4f) | Jul 25, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [2c268bdb51](https://linux-hardware.org/?probe=2c268bdb51) | Jul 24, 2020 |
| Lenovo        | ThinkCentre M58 8910ASU     | Desktop     | [d29d396ad0](https://linux-hardware.org/?probe=d29d396ad0) | Jul 23, 2020 |
| Lenovo        | ThinkPad E490 20N8000JUE    | Notebook    | [66d2ca1186](https://linux-hardware.org/?probe=66d2ca1186) | Jul 22, 2020 |
| ASUSTek       | N53Jq                       | Notebook    | [4d04d4ee3a](https://linux-hardware.org/?probe=4d04d4ee3a) | Jul 19, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [d7789565b7](https://linux-hardware.org/?probe=d7789565b7) | Jul 18, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [43c91be0b3](https://linux-hardware.org/?probe=43c91be0b3) | Jul 16, 2020 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [eb9ea3a7af](https://linux-hardware.org/?probe=eb9ea3a7af) | Jul 12, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [e9a3474bde](https://linux-hardware.org/?probe=e9a3474bde) | Jul 09, 2020 |
| HP            | 212B                        | Desktop     | [4a3583e0db](https://linux-hardware.org/?probe=4a3583e0db) | Jul 06, 2020 |
| Acer          | TravelMate 5742Z            | Notebook    | [de25d26410](https://linux-hardware.org/?probe=de25d26410) | Jul 05, 2020 |
| ECS           | G31T-M                      | Desktop     | [614dcd20e7](https://linux-hardware.org/?probe=614dcd20e7) | Jul 05, 2020 |
| Acer          | Aspire V5-561G              | Notebook    | [81b19839f7](https://linux-hardware.org/?probe=81b19839f7) | Jul 02, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [a35de97ee5](https://linux-hardware.org/?probe=a35de97ee5) | Jun 27, 2020 |
| ASUSTek       | H110M-C                     | Desktop     | [5656016c57](https://linux-hardware.org/?probe=5656016c57) | Jun 27, 2020 |
| ASRock        | P5B-DE                      | Desktop     | [304331fe41](https://linux-hardware.org/?probe=304331fe41) | Jun 24, 2020 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [d0f33583b0](https://linux-hardware.org/?probe=d0f33583b0) | Jun 21, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [7554759bac](https://linux-hardware.org/?probe=7554759bac) | Jun 18, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| ASUSTek       | X580VD                      | Notebook    | [1ad8491ca0](https://linux-hardware.org/?probe=1ad8491ca0) | Jun 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [376ebf1819](https://linux-hardware.org/?probe=376ebf1819) | Jun 14, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [56a1c895ee](https://linux-hardware.org/?probe=56a1c895ee) | Jun 07, 2020 |
| Acer          | Aspire V5-572G              | Notebook    | [4a67c5fabb](https://linux-hardware.org/?probe=4a67c5fabb) | Jun 03, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [8fd66dd600](https://linux-hardware.org/?probe=8fd66dd600) | Jun 01, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [fbd9ae49c7](https://linux-hardware.org/?probe=fbd9ae49c7) | Jun 01, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [d059aa2096](https://linux-hardware.org/?probe=d059aa2096) | May 29, 2020 |
| Sony          | VGN-SR165E                  | Notebook    | [ee7e382325](https://linux-hardware.org/?probe=ee7e382325) | May 27, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [0ff458cc64](https://linux-hardware.org/?probe=0ff458cc64) | May 23, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [639a8b36be](https://linux-hardware.org/?probe=639a8b36be) | May 23, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [870f5869a0](https://linux-hardware.org/?probe=870f5869a0) | May 22, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [842fbba95c](https://linux-hardware.org/?probe=842fbba95c) | May 22, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [c9967bfff4](https://linux-hardware.org/?probe=c9967bfff4) | May 22, 2020 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [58dbbb5f10](https://linux-hardware.org/?probe=58dbbb5f10) | May 22, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| HP            | 3397                        | Desktop     | [6d3acf04fa](https://linux-hardware.org/?probe=6d3acf04fa) | May 18, 2020 |
| Acer          | Aspire V5-572G              | Notebook    | [d919340bf8](https://linux-hardware.org/?probe=d919340bf8) | May 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [91908a3d7e](https://linux-hardware.org/?probe=91908a3d7e) | May 15, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [d064b573d0](https://linux-hardware.org/?probe=d064b573d0) | May 14, 2020 |
| ECS           | G41T-M13                    | Desktop     | [7f8c6dbb44](https://linux-hardware.org/?probe=7f8c6dbb44) | May 14, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3448fe759e](https://linux-hardware.org/?probe=3448fe759e) | May 13, 2020 |
| ECS           | G41T-M13                    | Desktop     | [b2c5f54483](https://linux-hardware.org/?probe=b2c5f54483) | May 10, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [d27ef604e7](https://linux-hardware.org/?probe=d27ef604e7) | May 10, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [cc84ca4df1](https://linux-hardware.org/?probe=cc84ca4df1) | May 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [150b4cbfba](https://linux-hardware.org/?probe=150b4cbfba) | May 08, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [efe32a1257](https://linux-hardware.org/?probe=efe32a1257) | May 07, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [3cac051446](https://linux-hardware.org/?probe=3cac051446) | May 07, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [543fb035d1](https://linux-hardware.org/?probe=543fb035d1) | May 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7d8b34f96f](https://linux-hardware.org/?probe=7d8b34f96f) | May 03, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [a214d8fa2f](https://linux-hardware.org/?probe=a214d8fa2f) | May 02, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [a6f251843f](https://linux-hardware.org/?probe=a6f251843f) | May 01, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96005fbb6f](https://linux-hardware.org/?probe=96005fbb6f) | Apr 28, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [3405972303](https://linux-hardware.org/?probe=3405972303) | Apr 27, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [2950c5ee7f](https://linux-hardware.org/?probe=2950c5ee7f) | Apr 27, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [f82980ac2c](https://linux-hardware.org/?probe=f82980ac2c) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [abfe333fb8](https://linux-hardware.org/?probe=abfe333fb8) | Apr 25, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [9e8575f75a](https://linux-hardware.org/?probe=9e8575f75a) | Apr 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5ec8b8b3b7](https://linux-hardware.org/?probe=5ec8b8b3b7) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [680bbeabad](https://linux-hardware.org/?probe=680bbeabad) | Apr 24, 2020 |
| HP            | Pavilion g6                 | Notebook    | [66ba3bc59b](https://linux-hardware.org/?probe=66ba3bc59b) | Apr 23, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [82f761db09](https://linux-hardware.org/?probe=82f761db09) | Apr 23, 2020 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [409a40b72d](https://linux-hardware.org/?probe=409a40b72d) | Apr 20, 2020 |
| Lenovo        | ThinkPad E480 20KN007XAD    | Notebook    | [8310d15c91](https://linux-hardware.org/?probe=8310d15c91) | Apr 18, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [74699b5097](https://linux-hardware.org/?probe=74699b5097) | Apr 16, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [93a89841fd](https://linux-hardware.org/?probe=93a89841fd) | Apr 12, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [943b36ee80](https://linux-hardware.org/?probe=943b36ee80) | Apr 10, 2020 |
| Sony          | VPCEH11FX                   | Notebook    | [e0ef96682b](https://linux-hardware.org/?probe=e0ef96682b) | Apr 09, 2020 |
| ASUSTek       | G750JH                      | Notebook    | [45a70fa311](https://linux-hardware.org/?probe=45a70fa311) | Apr 08, 2020 |
| ASUSTek       | G750JH                      | Notebook    | [3314aa590e](https://linux-hardware.org/?probe=3314aa590e) | Apr 08, 2020 |
| ASUSTek       | Z97-C                       | Desktop     | [53462bc3ec](https://linux-hardware.org/?probe=53462bc3ec) | Apr 07, 2020 |
| Dell          | Latitude D630               | Notebook    | [98199f8421](https://linux-hardware.org/?probe=98199f8421) | Apr 07, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [839c8344be](https://linux-hardware.org/?probe=839c8344be) | Apr 07, 2020 |
| ASUSTek       | 1015CX                      | Notebook    | [c98f5bcee3](https://linux-hardware.org/?probe=c98f5bcee3) | Apr 05, 2020 |
| ASUSTek       | 1015CX                      | Notebook    | [216b680d21](https://linux-hardware.org/?probe=216b680d21) | Apr 05, 2020 |
| Dell          | Latitude 7350               | Notebook    | [3ecdea8fcc](https://linux-hardware.org/?probe=3ecdea8fcc) | Apr 03, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [0dbe97d54b](https://linux-hardware.org/?probe=0dbe97d54b) | Mar 30, 2020 |
| HP            | 3397                        | Desktop     | [f2d1e62e57](https://linux-hardware.org/?probe=f2d1e62e57) | Mar 29, 2020 |
| HP            | 3646h                       | Desktop     | [63c3bf2b90](https://linux-hardware.org/?probe=63c3bf2b90) | Mar 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ffeee579db](https://linux-hardware.org/?probe=ffeee579db) | Mar 28, 2020 |
| Dell          | Inspiron 3443               | Notebook    | [0a21a54858](https://linux-hardware.org/?probe=0a21a54858) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [aa94d9ab9b](https://linux-hardware.org/?probe=aa94d9ab9b) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [96f26b673c](https://linux-hardware.org/?probe=96f26b673c) | Mar 28, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [21b92f29e5](https://linux-hardware.org/?probe=21b92f29e5) | Mar 28, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e7effd8e19](https://linux-hardware.org/?probe=e7effd8e19) | Mar 23, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [ec35befc4a](https://linux-hardware.org/?probe=ec35befc4a) | Mar 23, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [6f1f96e7fc](https://linux-hardware.org/?probe=6f1f96e7fc) | Mar 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [aa7093b56c](https://linux-hardware.org/?probe=aa7093b56c) | Mar 23, 2020 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [b7d3805ba6](https://linux-hardware.org/?probe=b7d3805ba6) | Mar 23, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [a79912cfdf](https://linux-hardware.org/?probe=a79912cfdf) | Mar 22, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [409951a0dd](https://linux-hardware.org/?probe=409951a0dd) | Mar 20, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| Dell          | Studio 1558                 | Notebook    | [06b0f26f6a](https://linux-hardware.org/?probe=06b0f26f6a) | Mar 12, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| Dell          | Studio 1558                 | Notebook    | [57fddb1856](https://linux-hardware.org/?probe=57fddb1856) | Mar 12, 2020 |
| MSI           | B250M PRO-VH                | Desktop     | [1eb2d76730](https://linux-hardware.org/?probe=1eb2d76730) | Mar 10, 2020 |
| ECS           | 945GCT-M                    | Desktop     | [069450c325](https://linux-hardware.org/?probe=069450c325) | Mar 08, 2020 |
| Gigabyte      | M1689D                      | Desktop     | [9f48604ff2](https://linux-hardware.org/?probe=9f48604ff2) | Mar 07, 2020 |
| Gigabyte      | M1689D                      | Desktop     | [43f9f0167a](https://linux-hardware.org/?probe=43f9f0167a) | Mar 07, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [b224a48803](https://linux-hardware.org/?probe=b224a48803) | Mar 04, 2020 |
| ASUSTek       | N82JQ                       | Notebook    | [b1b698b060](https://linux-hardware.org/?probe=b1b698b060) | Mar 02, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [80b614b253](https://linux-hardware.org/?probe=80b614b253) | Mar 02, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [910ec05246](https://linux-hardware.org/?probe=910ec05246) | Feb 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [ddb0fad848](https://linux-hardware.org/?probe=ddb0fad848) | Feb 29, 2020 |
| Lenovo        | ThinkCentre M58 7360EHU     | Desktop     | [7067a56ae2](https://linux-hardware.org/?probe=7067a56ae2) | Feb 27, 2020 |
| ASUSTek       | UX360UAK                    | Convertible | [e378eda49c](https://linux-hardware.org/?probe=e378eda49c) | Feb 21, 2020 |
| ASUSTek       | UX360UAK                    | Convertible | [8063e9ef93](https://linux-hardware.org/?probe=8063e9ef93) | Feb 21, 2020 |
| Dell          | Vostro 1015                 | Notebook    | [091443df09](https://linux-hardware.org/?probe=091443df09) | Feb 20, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [98cee968eb](https://linux-hardware.org/?probe=98cee968eb) | Feb 18, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [c04cf86240](https://linux-hardware.org/?probe=c04cf86240) | Feb 15, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [00e7d3f0b6](https://linux-hardware.org/?probe=00e7d3f0b6) | Feb 15, 2020 |
| Lenovo        | V580c 20160                 | Notebook    | [7e02c8c738](https://linux-hardware.org/?probe=7e02c8c738) | Feb 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [0061763167](https://linux-hardware.org/?probe=0061763167) | Feb 11, 2020 |
| Sony          | VPCSB19GG                   | Notebook    | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [759e13afc4](https://linux-hardware.org/?probe=759e13afc4) | Feb 02, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [32f19ab04d](https://linux-hardware.org/?probe=32f19ab04d) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | Notebook    | [dccdce5101](https://linux-hardware.org/?probe=dccdce5101) | Jan 23, 2020 |
| Dell          | Vostro 1510                 | Notebook    | [51fbe1ce5b](https://linux-hardware.org/?probe=51fbe1ce5b) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | Notebook    | [664116ebbf](https://linux-hardware.org/?probe=664116ebbf) | Jan 22, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [f77d00b6ce](https://linux-hardware.org/?probe=f77d00b6ce) | Jan 10, 2020 |
| Dell          | Precision M4800             | Notebook    | [cc63357309](https://linux-hardware.org/?probe=cc63357309) | Jan 09, 2020 |
| Lenovo        | ThinkPad X131e 33711T4      | Notebook    | [f06e98b417](https://linux-hardware.org/?probe=f06e98b417) | Jan 08, 2020 |
| HP            | 8054                        | Desktop     | [b9f8081fe1](https://linux-hardware.org/?probe=b9f8081fe1) | Jan 06, 2020 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [9d6c061d8b](https://linux-hardware.org/?probe=9d6c061d8b) | Jan 04, 2020 |
| HP            | ProBook 4540s               | Notebook    | [9ef64f7487](https://linux-hardware.org/?probe=9ef64f7487) | Jan 03, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [63fd9a500f](https://linux-hardware.org/?probe=63fd9a500f) | Dec 27, 2019 |
| Lenovo        | G510 20238                  | Notebook    | [8543221f24](https://linux-hardware.org/?probe=8543221f24) | Dec 27, 2019 |
| HP            | EliteBook 2740p             | Notebook    | [82cb2d5e90](https://linux-hardware.org/?probe=82cb2d5e90) | Dec 26, 2019 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [61d0162de0](https://linux-hardware.org/?probe=61d0162de0) | Dec 21, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| ASUSTek       | X542UN                      | Notebook    | [4b7f71d936](https://linux-hardware.org/?probe=4b7f71d936) | Dec 14, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [f30b5e8075](https://linux-hardware.org/?probe=f30b5e8075) | Dec 09, 2019 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [130e16c2b6](https://linux-hardware.org/?probe=130e16c2b6) | Dec 08, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [a68627d7eb](https://linux-hardware.org/?probe=a68627d7eb) | Nov 28, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [15babe41d0](https://linux-hardware.org/?probe=15babe41d0) | Nov 26, 2019 |
| HP            | 18E7                        | Desktop     | [f728a63212](https://linux-hardware.org/?probe=f728a63212) | Nov 26, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [ed7fb8cbb9](https://linux-hardware.org/?probe=ed7fb8cbb9) | Nov 15, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [5e184acc59](https://linux-hardware.org/?probe=5e184acc59) | Nov 15, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [f13de25d56](https://linux-hardware.org/?probe=f13de25d56) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dda0a53712](https://linux-hardware.org/?probe=dda0a53712) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [b86e3d7141](https://linux-hardware.org/?probe=b86e3d7141) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| HP            | Pavilion 15                 | Notebook    | [57540edaa7](https://linux-hardware.org/?probe=57540edaa7) | Nov 12, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [380140eb8d](https://linux-hardware.org/?probe=380140eb8d) | Nov 06, 2019 |
| Dell          | Vostro 1520                 | Notebook    | [247d9e9c2f](https://linux-hardware.org/?probe=247d9e9c2f) | Nov 01, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [89e9d28a32](https://linux-hardware.org/?probe=89e9d28a32) | Nov 01, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [797965c573](https://linux-hardware.org/?probe=797965c573) | Oct 30, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [63dc09b54e](https://linux-hardware.org/?probe=63dc09b54e) | Oct 28, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cf9411c533](https://linux-hardware.org/?probe=cf9411c533) | Oct 28, 2019 |
| Dell          | Vostro 1015                 | Notebook    | [400532e714](https://linux-hardware.org/?probe=400532e714) | Oct 24, 2019 |
| Dell          | Vostro 1015                 | Notebook    | [df8815e747](https://linux-hardware.org/?probe=df8815e747) | Oct 24, 2019 |
| ASUSTek       | N501VW                      | Notebook    | [4d2a1a9add](https://linux-hardware.org/?probe=4d2a1a9add) | Oct 16, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [d1394d6252](https://linux-hardware.org/?probe=d1394d6252) | Oct 11, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [c4f25ea846](https://linux-hardware.org/?probe=c4f25ea846) | Oct 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c8223df556](https://linux-hardware.org/?probe=c8223df556) | Oct 03, 2019 |
| Dell          | Inspiron N4050              | Notebook    | [153db5ae1b](https://linux-hardware.org/?probe=153db5ae1b) | Oct 01, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a814f0be14](https://linux-hardware.org/?probe=a814f0be14) | Sep 26, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [4c39be72b3](https://linux-hardware.org/?probe=4c39be72b3) | Sep 26, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [fbbabc5836](https://linux-hardware.org/?probe=fbbabc5836) | Sep 23, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [0143228659](https://linux-hardware.org/?probe=0143228659) | Sep 20, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [6e13970f68](https://linux-hardware.org/?probe=6e13970f68) | Sep 18, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [22d2f0f13e](https://linux-hardware.org/?probe=22d2f0f13e) | Sep 12, 2019 |
| ASUSTek       | X556UQK                     | Notebook    | [cd4ce4d624](https://linux-hardware.org/?probe=cd4ce4d624) | Sep 12, 2019 |
| ASUSTek       | B85-PLUS                    | Desktop     | [2665a9b231](https://linux-hardware.org/?probe=2665a9b231) | Sep 11, 2019 |
| ECS           | 945PT-A2                    | Desktop     | [e73a14a3e7](https://linux-hardware.org/?probe=e73a14a3e7) | Sep 10, 2019 |
| HP            | Pavilion 15                 | Notebook    | [c56817e0e4](https://linux-hardware.org/?probe=c56817e0e4) | Sep 10, 2019 |
| ASUSTek       | M3N78-EH                    | Desktop     | [0ded7435b9](https://linux-hardware.org/?probe=0ded7435b9) | Sep 04, 2019 |
| HP            | Pavilion g6                 | Notebook    | [81b3b2667e](https://linux-hardware.org/?probe=81b3b2667e) | Sep 03, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [a4f33fd40a](https://linux-hardware.org/?probe=a4f33fd40a) | Sep 03, 2019 |
| HP            | ProBook 4540s               | Notebook    | [1349a15c0f](https://linux-hardware.org/?probe=1349a15c0f) | Sep 01, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [eaf9b72412](https://linux-hardware.org/?probe=eaf9b72412) | Aug 31, 2019 |
| Lenovo        | ThinkPad E470 20H1002DAD    | Notebook    | [75804928d2](https://linux-hardware.org/?probe=75804928d2) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [579809b8b0](https://linux-hardware.org/?probe=579809b8b0) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [81e015523a](https://linux-hardware.org/?probe=81e015523a) | Aug 30, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [72437e888c](https://linux-hardware.org/?probe=72437e888c) | Aug 29, 2019 |
| ASUSTek       | X102BA                      | Notebook    | [8365a8b9d6](https://linux-hardware.org/?probe=8365a8b9d6) | Aug 27, 2019 |
| ASUSTek       | X102BA                      | Notebook    | [43b9931c92](https://linux-hardware.org/?probe=43b9931c92) | Aug 26, 2019 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [be649fc45f](https://linux-hardware.org/?probe=be649fc45f) | Aug 25, 2019 |
| MSI           | MS-1454                     | Notebook    | [b03f58cc28](https://linux-hardware.org/?probe=b03f58cc28) | Aug 23, 2019 |
| MSI           | MS-1454                     | Notebook    | [94bfc26599](https://linux-hardware.org/?probe=94bfc26599) | Aug 23, 2019 |
| ASUSTek       | X540UPR                     | Notebook    | [2f40c492db](https://linux-hardware.org/?probe=2f40c492db) | Aug 12, 2019 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [24c83ab728](https://linux-hardware.org/?probe=24c83ab728) | Aug 09, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | Notebook    | [2507713bd4](https://linux-hardware.org/?probe=2507713bd4) | Aug 06, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | Notebook    | [0ad209e005](https://linux-hardware.org/?probe=0ad209e005) | Aug 06, 2019 |
| ASUSTek       | X555LJ                      | Notebook    | [541fb4f240](https://linux-hardware.org/?probe=541fb4f240) | Aug 06, 2019 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [d0ac33919a](https://linux-hardware.org/?probe=d0ac33919a) | Aug 05, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [2ab556fd2e](https://linux-hardware.org/?probe=2ab556fd2e) | Aug 03, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [3ff8ae9e18](https://linux-hardware.org/?probe=3ff8ae9e18) | Aug 01, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [9518b70a0d](https://linux-hardware.org/?probe=9518b70a0d) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [9c80796306](https://linux-hardware.org/?probe=9c80796306) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [66cc9aa111](https://linux-hardware.org/?probe=66cc9aa111) | Jul 31, 2019 |
| HP            | Pavilion dv6                | Notebook    | [38f37f78c5](https://linux-hardware.org/?probe=38f37f78c5) | Jul 29, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [c53df5f083](https://linux-hardware.org/?probe=c53df5f083) | Jul 27, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [051b4df60a](https://linux-hardware.org/?probe=051b4df60a) | Jul 27, 2019 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [b6b40de397](https://linux-hardware.org/?probe=b6b40de397) | Jul 26, 2019 |
| ASUSTek       | GL553VD                     | Notebook    | [1a816e6ebb](https://linux-hardware.org/?probe=1a816e6ebb) | Jul 23, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [6478022b75](https://linux-hardware.org/?probe=6478022b75) | Jul 21, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [22e01f3d1f](https://linux-hardware.org/?probe=22e01f3d1f) | Jul 21, 2019 |
| ASUSTek       | X542UN                      | Notebook    | [0120b3a78b](https://linux-hardware.org/?probe=0120b3a78b) | Jul 19, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [ce6df77b4c](https://linux-hardware.org/?probe=ce6df77b4c) | Jul 18, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [997a4ec1c4](https://linux-hardware.org/?probe=997a4ec1c4) | Jul 18, 2019 |
| ASUSTek       | X411UNV                     | Notebook    | [ca77267e34](https://linux-hardware.org/?probe=ca77267e34) | Jul 17, 2019 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [46408abbb6](https://linux-hardware.org/?probe=46408abbb6) | Jul 12, 2019 |
| Lenovo        | AILZx                       | Notebook    | [3673023593](https://linux-hardware.org/?probe=3673023593) | Jun 27, 2019 |
| Lenovo        | AILZx                       | Notebook    | [e4c012a605](https://linux-hardware.org/?probe=e4c012a605) | Jun 27, 2019 |
| ASUSTek       | All Series                  | Desktop     | [383d32f068](https://linux-hardware.org/?probe=383d32f068) | Jun 27, 2019 |
| ASUSTek       | UX550VD                     | Notebook    | [b4ed65654c](https://linux-hardware.org/?probe=b4ed65654c) | Jun 26, 2019 |
| ASUSTek       | UX550VD                     | Notebook    | [dfc972293d](https://linux-hardware.org/?probe=dfc972293d) | Jun 25, 2019 |
| Dell          | Latitude E6500              | Notebook    | [5d172397d7](https://linux-hardware.org/?probe=5d172397d7) | Jun 10, 2019 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [b974503bc3](https://linux-hardware.org/?probe=b974503bc3) | Jun 07, 2019 |
| ASUSTek       | X556URK                     | Notebook    | [1ac09da8a9](https://linux-hardware.org/?probe=1ac09da8a9) | Jun 07, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [586a6a9f8a](https://linux-hardware.org/?probe=586a6a9f8a) | Jun 07, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [3633557547](https://linux-hardware.org/?probe=3633557547) | Jun 06, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [116b742db8](https://linux-hardware.org/?probe=116b742db8) | Jun 05, 2019 |
| ASUSTek       | P9X79 LE                    | Desktop     | [7cb5494874](https://linux-hardware.org/?probe=7cb5494874) | Jun 03, 2019 |
| ASUSTek       | P9X79 LE                    | Desktop     | [77dc13fea3](https://linux-hardware.org/?probe=77dc13fea3) | Jun 03, 2019 |
| Dell          | Latitude E6410              | Notebook    | [91ff183bf0](https://linux-hardware.org/?probe=91ff183bf0) | Jun 02, 2019 |
| Dell          | Latitude E6410              | Notebook    | [3029853366](https://linux-hardware.org/?probe=3029853366) | Jun 02, 2019 |
| ASUSTek       | 1005PX                      | Notebook    | [33f338599d](https://linux-hardware.org/?probe=33f338599d) | May 29, 2019 |
| ASUSTek       | X541NA                      | Notebook    | [b8a49028c8](https://linux-hardware.org/?probe=b8a49028c8) | May 27, 2019 |
| ASUSTek       | H81-PLUS                    | Desktop     | [7ce9462b77](https://linux-hardware.org/?probe=7ce9462b77) | May 25, 2019 |
| ASUSTek       | H81-PLUS                    | Desktop     | [4f2a9b31b5](https://linux-hardware.org/?probe=4f2a9b31b5) | May 19, 2019 |
| HP            | ProLiant DL360 G6           | Server      | [b4ad542a11](https://linux-hardware.org/?probe=b4ad542a11) | May 17, 2019 |
| ASUSTek       | N550JV                      | Notebook    | [1f0902bced](https://linux-hardware.org/?probe=1f0902bced) | May 17, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [89b4ae088c](https://linux-hardware.org/?probe=89b4ae088c) | May 16, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [4626315623](https://linux-hardware.org/?probe=4626315623) | May 14, 2019 |
| Dell          | Vostro 1500                 | Notebook    | [7008fbfa25](https://linux-hardware.org/?probe=7008fbfa25) | May 13, 2019 |
| Gigabyte      | P75-D3                      | Desktop     | [80e0cb37ad](https://linux-hardware.org/?probe=80e0cb37ad) | May 08, 2019 |
| Gigabyte      | P75-D3                      | Desktop     | [af7b263534](https://linux-hardware.org/?probe=af7b263534) | May 08, 2019 |
| HP            | EliteBook 8460w             | Notebook    | [2e2a41395d](https://linux-hardware.org/?probe=2e2a41395d) | May 07, 2019 |
| Gigabyte      | P75-D3                      | Desktop     | [341ae19874](https://linux-hardware.org/?probe=341ae19874) | May 07, 2019 |
| ASUSTek       | P7H57D-V EVO                | Desktop     | [8083f1c192](https://linux-hardware.org/?probe=8083f1c192) | May 02, 2019 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [e50b27ba1a](https://linux-hardware.org/?probe=e50b27ba1a) | Apr 27, 2019 |
| ASUSTek       | N501VW                      | Notebook    | [976a879300](https://linux-hardware.org/?probe=976a879300) | Apr 27, 2019 |
| HP            | 18E7                        | Desktop     | [314a0e2775](https://linux-hardware.org/?probe=314a0e2775) | Apr 24, 2019 |
| Acer          | Aspire 5738                 | Notebook    | [9b6046b160](https://linux-hardware.org/?probe=9b6046b160) | Apr 22, 2019 |
| Fujitsu       | LIFEBOOK AH530/HD6          | Notebook    | [7c65853191](https://linux-hardware.org/?probe=7c65853191) | Apr 21, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [cc9157e4bd](https://linux-hardware.org/?probe=cc9157e4bd) | Apr 14, 2019 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [1218f381aa](https://linux-hardware.org/?probe=1218f381aa) | Apr 11, 2019 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [b9f44fe73b](https://linux-hardware.org/?probe=b9f44fe73b) | Apr 11, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [ea6eec5a29](https://linux-hardware.org/?probe=ea6eec5a29) | Apr 03, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f7854f2bb7](https://linux-hardware.org/?probe=f7854f2bb7) | Apr 03, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [2dd89e3983](https://linux-hardware.org/?probe=2dd89e3983) | Apr 03, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [9e505ea7e9](https://linux-hardware.org/?probe=9e505ea7e9) | Apr 03, 2019 |
| HP            | EliteBook 8470p             | Notebook    | [2d5727bd09](https://linux-hardware.org/?probe=2d5727bd09) | Apr 02, 2019 |
| HP            | EliteBook 8570p             | Notebook    | [fd1396f058](https://linux-hardware.org/?probe=fd1396f058) | Mar 29, 2019 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [ec89277577](https://linux-hardware.org/?probe=ec89277577) | Mar 09, 2019 |
| HP            | 18E7                        | Desktop     | [74ff68d1e2](https://linux-hardware.org/?probe=74ff68d1e2) | Feb 28, 2019 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [078ded72a8](https://linux-hardware.org/?probe=078ded72a8) | Dec 10, 2018 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [7ee24f399a](https://linux-hardware.org/?probe=7ee24f399a) | Dec 10, 2018 |
| Gigabyte      | H61M-S2P                    | Desktop     | [bdd9f59ab7](https://linux-hardware.org/?probe=bdd9f59ab7) | Dec 09, 2018 |
| Gigabyte      | H61M-S2P                    | Desktop     | [3e29d905ef](https://linux-hardware.org/?probe=3e29d905ef) | Dec 09, 2018 |
| ECS           | 945GZ/CT-M                  | Desktop     | [86754f87d7](https://linux-hardware.org/?probe=86754f87d7) | Dec 07, 2018 |
| ECS           | 945GZ/CT-M                  | Desktop     | [0c8259eea0](https://linux-hardware.org/?probe=0c8259eea0) | Dec 07, 2018 |
| Acer          | Aspire A715-71G             | Notebook    | [b01e1626a7](https://linux-hardware.org/?probe=b01e1626a7) | Oct 31, 2018 |
| ASUSTek       | GL553VE                     | Notebook    | [3cdb244ea4](https://linux-hardware.org/?probe=3cdb244ea4) | Mar 31, 2018 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [504bfb59ec](https://linux-hardware.org/?probe=504bfb59ec) | Jan 08, 2018 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6976c096dc](https://linux-hardware.org/?probe=6976c096dc) | Jan 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 105       | 21.26%  |
| Ubuntu 18.04                 | 82        | 16.6%   |
| Arch                         | 18        | 3.64%   |
| Ubuntu 19.04                 | 16        | 3.24%   |
| Fedora 33                    | 14        | 2.83%   |
| Arch Rolling                 | 11        | 2.23%   |
| Ubuntu 20.10                 | 10        | 2.02%   |
| KDE neon 20.04               | 10        | 2.02%   |
| Xubuntu 18.04                | 9         | 1.82%   |
| Ubuntu 21.10                 | 9         | 1.82%   |
| Fedora 34                    | 9         | 1.82%   |
| Ubuntu 19.10                 | 8         | 1.62%   |
| OpenMandriva 4.2             | 8         | 1.62%   |
| Ubuntu 22.04                 | 7         | 1.42%   |
| Ubuntu 21.04                 | 6         | 1.21%   |
| Manjaro                      | 6         | 1.21%   |
| Linux Mint 20.3              | 5         | 1.01%   |
| Fedora 35                    | 5         | 1.01%   |
| Zorin 15                     | 4         | 0.81%   |
| Ubuntu 18.10                 | 4         | 0.81%   |
| Kali 2021.2                  | 4         | 0.81%   |
| Fedora 31                    | 4         | 0.81%   |
| Debian 11                    | 4         | 0.81%   |
| Ubuntu Budgie 20.04          | 3         | 0.61%   |
| Ubuntu 16.04                 | 3         | 0.61%   |
| Pop!_OS 20.04                | 3         | 0.61%   |
| Linux Mint 20.2              | 3         | 0.61%   |
| Linux Mint 20                | 3         | 0.61%   |
| Linux Mint 19.3              | 3         | 0.61%   |
| Kubuntu 20.04                | 3         | 0.61%   |
| Kali 2022.2                  | 3         | 0.61%   |
| Kali 2022.1                  | 3         | 0.61%   |
| Elementary 6.1               | 3         | 0.61%   |
| Debian 10                    | 3         | 0.61%   |
| ArcoLinux Rolling            | 3         | 0.61%   |
| Xubuntu 20.04                | 2         | 0.4%    |
| Ubuntu 17.10                 | 2         | 0.4%    |
| ROSA R11                     | 2         | 0.4%    |
| ROSA R10                     | 2         | 0.4%    |
| Pop!_OS 21.10                | 2         | 0.4%    |
| Pop!_OS 21.04                | 2         | 0.4%    |
| Pop!_OS 20.10                | 2         | 0.4%    |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.4%    |
| OpenMandriva 4.3             | 2         | 0.4%    |
| Manjaro 20.2.1               | 2         | 0.4%    |
| Manjaro 20.2                 | 2         | 0.4%    |
| Linux Mint 20.1              | 2         | 0.4%    |
| Kubuntu 19.10                | 2         | 0.4%    |
| KDE neon 18.04               | 2         | 0.4%    |
| Kali 2021.3                  | 2         | 0.4%    |
| Gentoo 2.6                   | 2         | 0.4%    |
| Fedora 32                    | 2         | 0.4%    |
| Fedora 30                    | 2         | 0.4%    |
| Fedora 29                    | 2         | 0.4%    |
| Endless 3.8.3-nexthw1        | 2         | 0.4%    |
| Endless 3.8.0                | 2         | 0.4%    |
| Endless 3.6.0                | 2         | 0.4%    |
| Endless 3.3.20-nexthw1       | 2         | 0.4%    |
| Endless 3.3.19               | 2         | 0.4%    |
| Zorin 12                     | 1         | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 247       | 51.89%  |
| Fedora        | 36        | 7.56%   |
| Arch          | 27        | 5.67%   |
| Manjaro       | 20        | 4.2%    |
| Linux Mint    | 18        | 3.78%   |
| Endless       | 16        | 3.36%   |
| KDE neon      | 12        | 2.52%   |
| Kali          | 12        | 2.52%   |
| Xubuntu       | 11        | 2.31%   |
| OpenMandriva  | 11        | 2.31%   |
| Kubuntu       | 10        | 2.1%    |
| Pop!_OS       | 9         | 1.89%   |
| Debian        | 7         | 1.47%   |
| Zorin         | 5         | 1.05%   |
| ROSA          | 4         | 0.84%   |
| Elementary    | 4         | 0.84%   |
| Ubuntu Budgie | 3         | 0.63%   |
| openSUSE      | 3         | 0.63%   |
| ArcoLinux     | 3         | 0.63%   |
| Solus         | 2         | 0.42%   |
| Lubuntu       | 2         | 0.42%   |
| Gentoo        | 2         | 0.42%   |
| Clear Linux   | 2         | 0.42%   |
| CentOS        | 2         | 0.42%   |
| Ubuntu MATE   | 1         | 0.21%   |
| Sabayon       | 1         | 0.21%   |
| Raspbian      | 1         | 0.21%   |
| PureOS        | 1         | 0.21%   |
| NixOS         | 1         | 0.21%   |
| Linux Lite    | 1         | 0.21%   |
| Deepin        | 1         | 0.21%   |
| Artix         | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 2.88%   |
| 5.4.0-26-generic         | 9         | 1.73%   |
| 5.3.0-46-generic         | 8         | 1.54%   |
| 5.10.14-desktop-1omv4002 | 8         | 1.54%   |
| 5.4.0-58-generic         | 7         | 1.34%   |
| 5.4.0-52-generic         | 7         | 1.34%   |
| 5.3.0-40-generic         | 7         | 1.34%   |
| 5.4.0-48-generic         | 6         | 1.15%   |
| 5.11.0-41-generic        | 6         | 1.15%   |
| 5.11.0-27-generic        | 6         | 1.15%   |
| 5.0.0-23-generic         | 6         | 1.15%   |
| 5.8.0-63-generic         | 5         | 0.96%   |
| 5.8.0-48-generic         | 5         | 0.96%   |
| 5.0.0-37-generic         | 5         | 0.96%   |
| 5.0.0-25-generic         | 5         | 0.96%   |
| 5.0.0-13-generic         | 5         | 0.96%   |
| 4.18.0-15-generic        | 5         | 0.96%   |
| 5.8.0-50-generic         | 4         | 0.77%   |
| 5.3.0-51-generic         | 4         | 0.77%   |
| 5.13.0-30-generic        | 4         | 0.77%   |
| 4.18.0-25-generic        | 4         | 0.77%   |
| 4.18.0-18-generic        | 4         | 0.77%   |
| 4.15.0-29-generic        | 4         | 0.77%   |
| 5.8.0-59-generic         | 3         | 0.58%   |
| 5.8.0-44-generic         | 3         | 0.58%   |
| 5.8.0-43-generic         | 3         | 0.58%   |
| 5.4.0-91-generic         | 3         | 0.58%   |
| 5.4.0-65-generic         | 3         | 0.58%   |
| 5.4.0-59-generic         | 3         | 0.58%   |
| 5.4.0-54-generic         | 3         | 0.58%   |
| 5.4.0-40-generic         | 3         | 0.58%   |
| 5.4.0-37-generic         | 3         | 0.58%   |
| 5.4.0-29-generic         | 3         | 0.58%   |
| 5.3.0-42-generic         | 3         | 0.58%   |
| 5.15.0-33-generic        | 3         | 0.58%   |
| 5.13.0-52-generic        | 3         | 0.58%   |
| 5.13.0-41-generic        | 3         | 0.58%   |
| 5.13.0-39-generic        | 3         | 0.58%   |
| 5.13.0-22-generic        | 3         | 0.58%   |
| 5.11.0-43-generic        | 3         | 0.58%   |
| 5.11.0-38-generic        | 3         | 0.58%   |
| 5.0.0-38-generic         | 3         | 0.58%   |
| 5.0.0-32-generic         | 3         | 0.58%   |
| 5.0.0-27-generic         | 3         | 0.58%   |
| 4.18.0-16-generic        | 3         | 0.58%   |
| 4.15.0-88-generic        | 3         | 0.58%   |
| 4.15.0-50-generic        | 3         | 0.58%   |
| 4.15.0-15-generic        | 3         | 0.58%   |
| 5.9.16-1-MANJARO         | 2         | 0.38%   |
| 5.9.14-arch1-1           | 2         | 0.38%   |
| 5.8.18-300.fc33.x86_64   | 2         | 0.38%   |
| 5.8.18-1-MANJARO         | 2         | 0.38%   |
| 5.8.0-53-generic         | 2         | 0.38%   |
| 5.8.0-25-generic         | 2         | 0.38%   |
| 5.8.0-14-generic         | 2         | 0.38%   |
| 5.7.6-arch1-1            | 2         | 0.38%   |
| 5.6.0-7-generic          | 2         | 0.38%   |
| 5.4.0-92-generic         | 2         | 0.38%   |
| 5.4.0-74-generic         | 2         | 0.38%   |
| 5.4.0-73-generic         | 2         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 102       | 20.32%  |
| 5.0.0   | 38        | 7.57%   |
| 4.15.0  | 38        | 7.57%   |
| 5.8.0   | 34        | 6.77%   |
| 5.11.0  | 34        | 6.77%   |
| 5.3.0   | 33        | 6.57%   |
| 5.13.0  | 27        | 5.38%   |
| 4.18.0  | 24        | 4.78%   |
| 5.15.0  | 10        | 1.99%   |
| 5.10.0  | 10        | 1.99%   |
| 5.10.14 | 8         | 1.59%   |
| 4.13.0  | 6         | 1.2%    |
| 5.8.18  | 4         | 0.8%    |
| 5.11.11 | 4         | 0.8%    |
| 5.9.16  | 3         | 0.6%    |
| 5.6.0   | 3         | 0.6%    |
| 5.16.7  | 3         | 0.6%    |
| 5.16.15 | 3         | 0.6%    |
| 5.16.0  | 3         | 0.6%    |
| 5.14.16 | 3         | 0.6%    |
| 5.13.19 | 3         | 0.6%    |
| 5.9.14  | 2         | 0.4%    |
| 5.7.6   | 2         | 0.4%    |
| 5.7.0   | 2         | 0.4%    |
| 5.17.0  | 2         | 0.4%    |
| 5.15.4  | 2         | 0.4%    |
| 5.13.7  | 2         | 0.4%    |
| 5.13.13 | 2         | 0.4%    |
| 5.12.8  | 2         | 0.4%    |
| 5.10.13 | 2         | 0.4%    |
| 4.9.60  | 2         | 0.4%    |
| 4.19.0  | 2         | 0.4%    |
| 5.9.4   | 1         | 0.2%    |
| 5.9.12  | 1         | 0.2%    |
| 5.9.11  | 1         | 0.2%    |
| 5.8.9   | 1         | 0.2%    |
| 5.8.8   | 1         | 0.2%    |
| 5.8.4   | 1         | 0.2%    |
| 5.8.16  | 1         | 0.2%    |
| 5.8.15  | 1         | 0.2%    |
| 5.8.14  | 1         | 0.2%    |
| 5.8.13  | 1         | 0.2%    |
| 5.8.12  | 1         | 0.2%    |
| 5.7.7   | 1         | 0.2%    |
| 5.6.17  | 1         | 0.2%    |
| 5.6.14  | 1         | 0.2%    |
| 5.6.13  | 1         | 0.2%    |
| 5.6.12  | 1         | 0.2%    |
| 5.6.10  | 1         | 0.2%    |
| 5.5.8   | 1         | 0.2%    |
| 5.5.13  | 1         | 0.2%    |
| 5.4.8   | 1         | 0.2%    |
| 5.4.28  | 1         | 0.2%    |
| 5.4.23  | 1         | 0.2%    |
| 5.4.2   | 1         | 0.2%    |
| 5.4.18  | 1         | 0.2%    |
| 5.4.17  | 1         | 0.2%    |
| 5.4.12  | 1         | 0.2%    |
| 5.3.7   | 1         | 0.2%    |
| 5.2.2   | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 108       | 21.69%  |
| 5.8     | 46        | 9.24%   |
| 5.11    | 42        | 8.43%   |
| 5.0     | 41        | 8.23%   |
| 4.15    | 38        | 7.63%   |
| 5.13    | 36        | 7.23%   |
| 5.3     | 34        | 6.83%   |
| 5.10    | 29        | 5.82%   |
| 4.18    | 24        | 4.82%   |
| 5.15    | 21        | 4.22%   |
| 5.16    | 14        | 2.81%   |
| 5.14    | 11        | 2.21%   |
| 5.9     | 8         | 1.61%   |
| 5.6     | 7         | 1.41%   |
| 5.12    | 7         | 1.41%   |
| 4.13    | 6         | 1.2%    |
| 5.7     | 5         | 1%      |
| 4.19    | 5         | 1%      |
| 5.17    | 3         | 0.6%    |
| 5.5     | 2         | 0.4%    |
| 5.18    | 2         | 0.4%    |
| 4.9     | 2         | 0.4%    |
| 4.14    | 2         | 0.4%    |
| 5.2     | 1         | 0.2%    |
| 4.5     | 1         | 0.2%    |
| 4.20    | 1         | 0.2%    |
| 4.12    | 1         | 0.2%    |
| 3.10    | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 452       | 96.58%  |
| i686    | 14        | 2.99%   |
| aarch64 | 2         | 0.43%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 255       | 52.9%   |
| Unknown         | 93        | 19.29%  |
| KDE5            | 38        | 7.88%   |
| XFCE            | 31        | 6.43%   |
| KDE             | 17        | 3.53%   |
| X-Cinnamon      | 12        | 2.49%   |
| i3              | 7         | 1.45%   |
| Unity           | 5         | 1.04%   |
| MATE            | 5         | 1.04%   |
| Pantheon        | 4         | 0.83%   |
| Budgie          | 4         | 0.83%   |
| LXQt            | 3         | 0.62%   |
| Cinnamon        | 2         | 0.41%   |
| Trinity         | 1         | 0.21%   |
| sway            | 1         | 0.21%   |
| LXDE            | 1         | 0.21%   |
| KDE4            | 1         | 0.21%   |
| GNOME Flashback | 1         | 0.21%   |
| bspwm           | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 363       | 75.31%  |
| Unknown | 64        | 13.28%  |
| Wayland | 50        | 10.37%  |
| Tty     | 5         | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 301       | 62.19%  |
| GDM     | 75        | 15.5%   |
| SDDM    | 33        | 6.82%   |
| GDM3    | 32        | 6.61%   |
| LightDM | 26        | 5.37%   |
| TDM     | 14        | 2.89%   |
| XDM     | 1         | 0.21%   |
| Ly      | 1         | 0.21%   |
| KDM     | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 350       | 73.53%  |
| Unknown | 90        | 18.91%  |
| fa_IR   | 11        | 2.31%   |
| en_GB   | 11        | 2.31%   |
| en_CA   | 5         | 1.05%   |
| C       | 5         | 1.05%   |
| POSIX   | 1         | 0.21%   |
| ja_JP   | 1         | 0.21%   |
| de_DE   | 1         | 0.21%   |
| az_IR   | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 274       | 57.32%  |
| EFI  | 204       | 42.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 398       | 84.14%  |
| Btrfs   | 26        | 5.5%    |
| Overlay | 19        | 4.02%   |
| Unknown | 18        | 3.81%   |
| Zfs     | 5         | 1.06%   |
| Xfs     | 5         | 1.06%   |
| Ext3    | 1         | 0.21%   |
| Ext2    | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 331       | 70.13%  |
| GPT     | 100       | 21.19%  |
| MBR     | 41        | 8.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 407       | 86.05%  |
| Yes       | 66        | 13.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 257       | 54.56%  |
| Yes       | 214       | 45.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 156       | 33.33%  |
| Lenovo                  | 88        | 18.8%   |
| Hewlett-Packard         | 63        | 13.46%  |
| Dell                    | 37        | 7.91%   |
| Acer                    | 34        | 7.26%   |
| Gigabyte Technology     | 28        | 5.98%   |
| MSI                     | 16        | 3.42%   |
| Sony                    | 10        | 2.14%   |
| ECS                     | 6         | 1.28%   |
| ASRock                  | 5         | 1.07%   |
| Toshiba                 | 3         | 0.64%   |
| Fujitsu                 | 3         | 0.64%   |
| Unknown                 | 3         | 0.64%   |
| Raspberry Pi Foundation | 2         | 0.43%   |
| Microsoft               | 2         | 0.43%   |
| Biostar                 | 2         | 0.43%   |
| Apple                   | 2         | 0.43%   |
| YANYU                   | 1         | 0.21%   |
| Supermicro              | 1         | 0.21%   |
| Razer                   | 1         | 0.21%   |
| Packard Bell            | 1         | 0.21%   |
| LG Electronics          | 1         | 0.21%   |
| Intel                   | 1         | 0.21%   |
| Foxconn                 | 1         | 0.21%   |
| Alienware               | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 12        | 2.56%   |
| HP ProBook 4540s                           | 6         | 1.28%   |
| HP Compaq Elite 8300 SFF                   | 6         | 1.28%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 5         | 1.07%   |
| Acer Aspire V3-571G                        | 5         | 1.07%   |
| Lenovo IdeaPad Z510 20287                  | 4         | 0.85%   |
| HP Pavilion g6                             | 3         | 0.64%   |
| HP EliteBook 840 G2                        | 3         | 0.64%   |
| ASUS X580VD                                | 3         | 0.64%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 3         | 0.64%   |
| ASUS P5P41T-LE                             | 3         | 0.64%   |
| Unknown                                    | 3         | 0.64%   |
| MSI Prestige 14 A10RB                      | 2         | 0.43%   |
| Microsoft Surface Book 2                   | 2         | 0.43%   |
| Lenovo Z50-70 20354                        | 2         | 0.43%   |
| Lenovo ThinkPad X250 20CM002XUS            | 2         | 0.43%   |
| Lenovo Legion 5 15ARH05H 82B1              | 2         | 0.43%   |
| Lenovo IdeaPad S540-15IWL GTX 81SW         | 2         | 0.43%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 2         | 0.43%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 2         | 0.43%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 2         | 0.43%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 2         | 0.43%   |
| Lenovo G50-70 20351                        | 2         | 0.43%   |
| Lenovo Flex 2-15 20405                     | 2         | 0.43%   |
| HP ProLiant DL360 G6                       | 2         | 0.43%   |
| HP ProBook 450 G4                          | 2         | 0.43%   |
| HP Pavilion dv6                            | 2         | 0.43%   |
| HP Laptop 15-bs0xx                         | 2         | 0.43%   |
| HP EliteDesk 800 G2 SFF                    | 2         | 0.43%   |
| HP EliteBook 8470p                         | 2         | 0.43%   |
| Gigabyte H81M-S2PV                         | 2         | 0.43%   |
| Dell Vostro 1510                           | 2         | 0.43%   |
| Dell Vostro 1015                           | 2         | 0.43%   |
| Dell Latitude E7470                        | 2         | 0.43%   |
| Dell Latitude E6530                        | 2         | 0.43%   |
| Dell Inspiron N5110                        | 2         | 0.43%   |
| ASUS X550IU                                | 2         | 0.43%   |
| ASUS X542UN                                | 2         | 0.43%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD     | 2         | 0.43%   |
| ASUS VivoBook_ASUSLaptop X571GT_K571GT     | 2         | 0.43%   |
| ASUS VivoBook_ASUSLaptop X521EQ_S533EQ     | 2         | 0.43%   |
| ASUS VivoBook 15_ASUS Laptop X540MB_X540MB | 2         | 0.43%   |
| ASUS VivoBook 15 ASUS Laptop X570UD        | 2         | 0.43%   |
| ASUS PRIME Z390-P                          | 2         | 0.43%   |
| ASUS PRIME H310-PLUS R2.0                  | 2         | 0.43%   |
| ASUS PRIME H310-PLUS                       | 2         | 0.43%   |
| ASUS P9X79 LE                              | 2         | 0.43%   |
| ASUS P8H61                                 | 2         | 0.43%   |
| ASUS N501VW                                | 2         | 0.43%   |
| ASUS K55VD                                 | 2         | 0.43%   |
| Acer TravelMate P446-M                     | 2         | 0.43%   |
| Acer Aspire F5-573G                        | 2         | 0.43%   |
| Acer Aspire A715-71G                       | 2         | 0.43%   |
| YANYU M9F baytrail                         | 1         | 0.21%   |
| Toshiba Satellite Pro T130                 | 1         | 0.21%   |
| Toshiba Satellite L655                     | 1         | 0.21%   |
| Toshiba PORTEGE R930                       | 1         | 0.21%   |
| Supermicro Super Server                    | 1         | 0.21%   |
| Sony VPCZ126GG                             | 1         | 0.21%   |
| Sony VPCSB36FG                             | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 32        | 6.84%   |
| Acer Aspire           | 29        | 6.2%    |
| Lenovo ThinkPad       | 26        | 5.56%   |
| ASUS VivoBook         | 24        | 5.13%   |
| HP EliteBook          | 17        | 3.63%   |
| Dell Inspiron         | 14        | 2.99%   |
| HP ProBook            | 13        | 2.78%   |
| ASUS PRIME            | 12        | 2.56%   |
| ASUS All              | 12        | 2.56%   |
| Dell Latitude         | 11        | 2.35%   |
| HP Pavilion           | 8         | 1.71%   |
| HP Compaq             | 8         | 1.71%   |
| Dell Vostro           | 8         | 1.71%   |
| ASUS ASUS             | 6         | 1.28%   |
| Lenovo ThinkBook      | 3         | 0.64%   |
| Lenovo Legion         | 3         | 0.64%   |
| HP ProLiant           | 3         | 0.64%   |
| Fujitsu LIFEBOOK      | 3         | 0.64%   |
| ASUS X580VD           | 3         | 0.64%   |
| ASUS ROG              | 3         | 0.64%   |
| ASUS P5P41T-LE        | 3         | 0.64%   |
| Acer TravelMate       | 3         | 0.64%   |
| Unknown               | 3         | 0.64%   |
| Toshiba Satellite     | 2         | 0.43%   |
| RPi Raspberry         | 2         | 0.43%   |
| MSI Prestige          | 2         | 0.43%   |
| MSI GE60              | 2         | 0.43%   |
| Microsoft Surface     | 2         | 0.43%   |
| Lenovo Z50-70         | 2         | 0.43%   |
| Lenovo ThinkCentre    | 2         | 0.43%   |
| Lenovo G580           | 2         | 0.43%   |
| Lenovo G50-70         | 2         | 0.43%   |
| Lenovo Flex           | 2         | 0.43%   |
| HP ZBook              | 2         | 0.43%   |
| HP ProDesk            | 2         | 0.43%   |
| HP Laptop             | 2         | 0.43%   |
| HP EliteDesk          | 2         | 0.43%   |
| Gigabyte H81M-S2PV    | 2         | 0.43%   |
| ASUS X550IU           | 2         | 0.43%   |
| ASUS X542UN           | 2         | 0.43%   |
| ASUS TUF              | 2         | 0.43%   |
| ASUS P9X79            | 2         | 0.43%   |
| ASUS P8H61            | 2         | 0.43%   |
| ASUS N501VW           | 2         | 0.43%   |
| ASUS K55VD            | 2         | 0.43%   |
| YANYU M9F             | 1         | 0.21%   |
| Toshiba PORTEGE       | 1         | 0.21%   |
| Supermicro Super      | 1         | 0.21%   |
| Sony VPCZ126GG        | 1         | 0.21%   |
| Sony VPCSB36FG        | 1         | 0.21%   |
| Sony VPCSB19GG        | 1         | 0.21%   |
| Sony VPCSA25GX        | 1         | 0.21%   |
| Sony VPCEH36EG        | 1         | 0.21%   |
| Sony VPCEH11FX        | 1         | 0.21%   |
| Sony VPCEB1SFX        | 1         | 0.21%   |
| Sony VGN-SR165E       | 1         | 0.21%   |
| Sony VGN-CS38GD       | 1         | 0.21%   |
| Sony SVF15N12SGB      | 1         | 0.21%   |
| Razer Blade           | 1         | 0.21%   |
| Packard Bell EasyNote | 1         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 52        | 11.11%  |
| 2012    | 48        | 10.26%  |
| 2017    | 44        | 9.4%    |
| 2018    | 37        | 7.91%   |
| 2011    | 36        | 7.69%   |
| 2010    | 35        | 7.48%   |
| 2015    | 31        | 6.62%   |
| 2019    | 29        | 6.2%    |
| 2016    | 29        | 6.2%    |
| 2020    | 28        | 5.98%   |
| 2014    | 28        | 5.98%   |
| 2009    | 26        | 5.56%   |
| 2008    | 13        | 2.78%   |
| 2021    | 10        | 2.14%   |
| 2007    | 9         | 1.92%   |
| 2006    | 6         | 1.28%   |
| 2022    | 2         | 0.43%   |
| 2005    | 2         | 0.43%   |
| Unknown | 2         | 0.43%   |
| 2004    | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 331       | 70.73%  |
| Desktop        | 124       | 26.5%   |
| Server         | 5         | 1.07%   |
| Tablet         | 3         | 0.64%   |
| Convertible    | 3         | 0.64%   |
| System on chip | 2         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 444       | 94.87%  |
| Enabled  | 24        | 5.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 468       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 144       | 30.57%  |
| 3.01-4.0        | 99        | 21.02%  |
| 8.01-16.0       | 95        | 20.17%  |
| 16.01-24.0      | 83        | 17.62%  |
| 1.01-2.0        | 16        | 3.4%    |
| 32.01-64.0      | 15        | 3.18%   |
| 2.01-3.0        | 8         | 1.7%    |
| 64.01-256.0     | 4         | 0.85%   |
| 0.51-1.0        | 4         | 0.85%   |
| 24.01-32.0      | 2         | 0.42%   |
| More than 256.0 | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 187       | 37.1%   |
| 2.01-3.0   | 152       | 30.16%  |
| 3.01-4.0   | 70        | 13.89%  |
| 4.01-8.0   | 51        | 10.12%  |
| 0.51-1.0   | 26        | 5.16%   |
| 8.01-16.0  | 13        | 2.58%   |
| 0.01-0.5   | 4         | 0.79%   |
| 16.01-24.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 306       | 64.15%  |
| 2       | 138       | 28.93%  |
| 3       | 22        | 4.61%   |
| 4       | 5         | 1.05%   |
| 0       | 3         | 0.63%   |
| 5       | 2         | 0.42%   |
| Unknown | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 238       | 50.21%  |
| No        | 236       | 49.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 417       | 89.1%   |
| No        | 51        | 10.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 385       | 81.57%  |
| No        | 87        | 18.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 286       | 60.85%  |
| No        | 184       | 39.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Iran    | 468       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Tehran                         | 268       | 54.47%  |
| TehrДЃn                      | 46        | 9.35%   |
| Mashhad                        | 24        | 4.88%   |
| Isfahan                        | 15        | 3.05%   |
| Karaj                          | 7         | 1.42%   |
| Shiraz                         | 6         | 1.22%   |
| Qom                            | 6         | 1.22%   |
| Khorramshahr                   | 6         | 1.22%   |
| Tajrīsh                       | 5         | 1.02%   |
| Tabriz                         | 5         | 1.02%   |
| Rasht                          | 5         | 1.02%   |
| Sanandij                       | 4         | 0.81%   |
| Kerman                         | 4         | 0.81%   |
| Babol                          | 4         | 0.81%   |
| Yazd                           | 3         | 0.61%   |
| TajrД«sh                     | 3         | 0.61%   |
| Rey                            | 3         | 0.61%   |
| Arak                           | 3         | 0.61%   |
| Zanjan                         | 2         | 0.41%   |
| Shahre Jadide Andisheh         | 2         | 0.41%   |
| Shahr-e Qods                   | 2         | 0.41%   |
| Qazvin                         | 2         | 0.41%   |
| Hamadan                        | 2         | 0.41%   |
| Gorgan                         | 2         | 0.41%   |
| DamДЃvand                    | 2         | 0.41%   |
| BorЕ«jerd                    | 2         | 0.41%   |
| Behshahr                       | 2         | 0.41%   |
| Ahvaz                          | 2         | 0.41%   |
| ДЂstДЃneh-ye AshrafД«yeh | 1         | 0.2%    |
| Şowmeeh Sarā                 | 1         | 0.2%    |
| Siakhdekhan                    | 1         | 0.2%    |
| ShДЃhД«n Shahr             | 1         | 0.2%    |
| Shirvan                        | 1         | 0.2%    |
| ShahrД«ДЃr                 | 1         | 0.2%    |
| Shahrak-e KÅ«lÅ«rÄ«      | 1         | 0.2%    |
| Shahr-e Kord                   | 1         | 0.2%    |
| Shaft                          | 1         | 0.2%    |
| SemÄ«rom                     | 1         | 0.2%    |
| SalmДЃs                      | 1         | 0.2%    |
| Rūdsar                        | 1         | 0.2%    |
| Robat Karim                    | 1         | 0.2%    |
| RÅ«dÄn                    | 1         | 0.2%    |
| Razan                          | 1         | 0.2%    |
| RafsanjДЃn                   | 1         | 0.2%    |
| Qaleh Ganj                     | 1         | 0.2%    |
| PДЃkdasht                    | 1         | 0.2%    |
| Naz̧arābād                  | 1         | 0.2%    |
| NashtДЃrЕ«d                | 1         | 0.2%    |
| NajafДЃbДЃd                | 1         | 0.2%    |
| NajafÄbÄd                | 1         | 0.2%    |
| MДЃmЕ«nД«yeh             | 1         | 0.2%    |
| MД«ДЃneh                   | 1         | 0.2%    |
| Maragheh                       | 1         | 0.2%    |
| MalДЃrd                      | 1         | 0.2%    |
| Langarūd                      | 1         | 0.2%    |
| Khorramabad                    | 1         | 0.2%    |
| Khonj                          | 1         | 0.2%    |
| KhondДЃb                     | 1         | 0.2%    |
| Kermanshah                     | 1         | 0.2%    |
| Kāshān                       | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 131       | 164    | 21.44%  |
| Seagate                   | 119       | 140    | 19.48%  |
| Toshiba                   | 77        | 89     | 12.6%   |
| Samsung Electronics       | 73        | 92     | 11.95%  |
| A-DATA Technology         | 27        | 34     | 4.42%   |
| Maxtor                    | 19        | 26     | 3.11%   |
| HGST                      | 18        | 22     | 2.95%   |
| SanDisk                   | 17        | 21     | 2.78%   |
| Micron Technology         | 16        | 18     | 2.62%   |
| Unknown                   | 14        | 15     | 2.29%   |
| Kingston                  | 11        | 15     | 1.8%    |
| Lexar                     | 10        | 10     | 1.64%   |
| Intel                     | 10        | 10     | 1.64%   |
| Hitachi                   | 10        | 10     | 1.64%   |
| SK hynix                  | 8         | 9      | 1.31%   |
| SPCC                      | 6         | 7      | 0.98%   |
| Plextor                   | 4         | 4      | 0.65%   |
| Silicon Motion            | 3         | 3      | 0.49%   |
| Apacer                    | 3         | 3      | 0.49%   |
| OCZ                       | 2         | 2      | 0.33%   |
| LITEON                    | 2         | 3      | 0.33%   |
| Kingmax                   | 2         | 2      | 0.33%   |
| Gigabyte Technology       | 2         | 2      | 0.33%   |
| Biostar                   | 2         | 3      | 0.33%   |
| XPG                       | 1         | 1      | 0.16%   |
| VC-500                    | 1         | 1      | 0.16%   |
| ValueTech                 | 1         | 2      | 0.16%   |
| USB3.0                    | 1         | 1      | 0.16%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.16%   |
| Union Memory              | 1         | 1      | 0.16%   |
| UMIS                      | 1         | 1      | 0.16%   |
| Transcend                 | 1         | 1      | 0.16%   |
| Team                      | 1         | 1      | 0.16%   |
| Realtek Semiconductor     | 1         | 1      | 0.16%   |
| Pioneer                   | 1         | 1      | 0.16%   |
| Phison                    | 1         | 1      | 0.16%   |
| Patriot                   | 1         | 1      | 0.16%   |
| OSCOO                     | 1         | 2      | 0.16%   |
| Micron/Crucial Technology | 1         | 1      | 0.16%   |
| Mass                      | 1         | 2      | 0.16%   |
| LITEONIT                  | 1         | 2      | 0.16%   |
| KODAK                     | 1         | 1      | 0.16%   |
| KingFast                  | 1         | 1      | 0.16%   |
| HPE                       | 1         | 1      | 0.16%   |
| GeIL                      | 1         | 1      | 0.16%   |
| Fujitsu                   | 1         | 1      | 0.16%   |
| Crucial                   | 1         | 1      | 0.16%   |
| China                     | 1         | 1      | 0.16%   |
| Apple                     | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 31        | 4.87%   |
| Toshiba MQ01ABD100 1TB               | 16        | 2.52%   |
| Toshiba MQ04ABF100 1TB               | 12        | 1.89%   |
| WDC WD10EZEX-08WN4A0 1TB             | 11        | 1.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 10        | 1.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 9         | 1.42%   |
| Seagate ST9500325AS 500GB            | 9         | 1.42%   |
| WDC WD10SPZX-24Z10 1TB               | 8         | 1.26%   |
| Samsung SSD 860 EVO 500GB            | 8         | 1.26%   |
| WDC WD10SPZX-08Z10 1TB               | 7         | 1.1%    |
| Toshiba MQ01ABF050 500GB             | 7         | 1.1%    |
| Samsung SSD 860 EVO 250GB            | 7         | 1.1%    |
| A-DATA SU650 120GB SSD               | 7         | 1.1%    |
| WDC WD10JPCX-24UE4T0 1TB             | 6         | 0.94%   |
| Seagate ST500DM002-1BD142 500GB      | 6         | 0.94%   |
| Maxtor STM3250310AS 250GB            | 6         | 0.94%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 5         | 0.79%   |
| Toshiba MQ01ABD050V 500GB            | 5         | 0.79%   |
| Samsung SSD 850 EVO 250GB            | 5         | 0.79%   |
| Toshiba MQ01ABD050 500GB             | 4         | 0.63%   |
| Seagate ST9500420AS 500GB            | 4         | 0.63%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 0.63%   |
| Seagate ST2000LM007-1R8174 2TB       | 4         | 0.63%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 4         | 0.63%   |
| Lexar 256GB SSD                      | 4         | 0.63%   |
| Lexar 128GB SSD                      | 4         | 0.63%   |
| Intel NVMe SSD Drive 512GB           | 4         | 0.63%   |
| HGST HTS721010A9E630 1TB             | 4         | 0.63%   |
| HGST HTS541010B7E610 1TB             | 4         | 0.63%   |
| HGST HTS541010A9E680 1TB             | 4         | 0.63%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 3         | 0.47%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD     | 3         | 0.47%   |
| WDC WD10EARS-00MVWB0 1TB             | 3         | 0.47%   |
| Unknown MMC Card  32GB               | 3         | 0.47%   |
| Toshiba MQ01ABD075 752GB             | 3         | 0.47%   |
| Toshiba DT01ACA100 1TB               | 3         | 0.47%   |
| Toshiba DT01ACA050 500GB             | 3         | 0.47%   |
| SPCC Solid State Disk 128GB          | 3         | 0.47%   |
| Seagate ST500LM021-1KJ152 500GB      | 3         | 0.47%   |
| Seagate ST3500413AS 500GB            | 3         | 0.47%   |
| Samsung NVMe SSD Drive 512GB         | 3         | 0.47%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 0.47%   |
| Samsung NVMe SSD Drive 1024GB        | 3         | 0.47%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD | 3         | 0.47%   |
| Micron 2210_MTFDHBA512QFD 512GB      | 3         | 0.47%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD  | 3         | 0.47%   |
| Maxtor 6Y080L0 82GB                  | 3         | 0.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.31%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 2         | 0.31%   |
| WDC WD5000AZRX-00L4HB0 500GB         | 2         | 0.31%   |
| WDC WD5000AZRX-00A8LB0 500GB         | 2         | 0.31%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 2         | 0.31%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 2         | 0.31%   |
| WDC WD10SPZX-80Z10T2 1TB             | 2         | 0.31%   |
| WDC WD10SPZX-75Z10T0 1TB             | 2         | 0.31%   |
| WDC WD10SPCX-08S8TT0 1TB             | 2         | 0.31%   |
| WDC WD10JPVX-08JC3T5 1TB             | 2         | 0.31%   |
| WDC WD10JPVX-00JC3T0 1TB             | 2         | 0.31%   |
| WDC WD10EZRX-00L4HB0 1TB             | 2         | 0.31%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 119       | 140    | 33.06%  |
| WDC                 | 113       | 136    | 31.39%  |
| Toshiba             | 71        | 79     | 19.72%  |
| Maxtor              | 19        | 26     | 5.28%   |
| HGST                | 18        | 22     | 5%      |
| Hitachi             | 10        | 10     | 2.78%   |
| Samsung Electronics | 6         | 10     | 1.67%   |
| Unknown             | 2         | 2      | 0.56%   |
| HPE                 | 1         | 1      | 0.28%   |
| Fujitsu             | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 50        | 61     | 26.46%  |
| A-DATA Technology   | 27        | 34     | 14.29%  |
| WDC                 | 23        | 26     | 12.17%  |
| SanDisk             | 14        | 17     | 7.41%   |
| Lexar               | 10        | 10     | 5.29%   |
| Micron Technology   | 9         | 9      | 4.76%   |
| Kingston            | 9         | 12     | 4.76%   |
| SPCC                | 6         | 7      | 3.17%   |
| SK hynix            | 5         | 5      | 2.65%   |
| Toshiba             | 4         | 8      | 2.12%   |
| Plextor             | 4         | 4      | 2.12%   |
| Intel               | 3         | 3      | 1.59%   |
| Apacer              | 3         | 3      | 1.59%   |
| OCZ                 | 2         | 2      | 1.06%   |
| LITEON              | 2         | 3      | 1.06%   |
| Gigabyte Technology | 2         | 2      | 1.06%   |
| Biostar             | 2         | 3      | 1.06%   |
| ValueTech           | 1         | 2      | 0.53%   |
| USB3.0              | 1         | 1      | 0.53%   |
| Transcend           | 1         | 1      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| Pioneer             | 1         | 1      | 0.53%   |
| Patriot             | 1         | 1      | 0.53%   |
| OSCOO               | 1         | 2      | 0.53%   |
| LITEONIT            | 1         | 2      | 0.53%   |
| KODAK               | 1         | 1      | 0.53%   |
| Kingmax             | 1         | 1      | 0.53%   |
| GeIL                | 1         | 1      | 0.53%   |
| Crucial             | 1         | 1      | 0.53%   |
| China               | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 340       | 427    | 57.72%  |
| SSD     | 181       | 226    | 30.73%  |
| NVMe    | 55        | 65     | 9.34%   |
| MMC     | 8         | 9      | 1.36%   |
| Unknown | 5         | 6      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 430       | 647    | 85.49%  |
| NVMe | 55        | 65     | 10.93%  |
| SAS  | 10        | 12     | 1.99%   |
| MMC  | 8         | 9      | 1.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 284       | 378    | 56.13%  |
| 0.51-1.0   | 200       | 248    | 39.53%  |
| 1.01-2.0   | 14        | 16     | 2.77%   |
| 2.01-3.0   | 4         | 5      | 0.79%   |
| 3.01-4.0   | 3         | 3      | 0.59%   |
| 10.01-20.0 | 1         | 3      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 138       | 28.45%  |
| 501-1000       | 94        | 19.38%  |
| 251-500        | 88        | 18.14%  |
| 51-100         | 47        | 9.69%   |
| 1001-2000      | 42        | 8.66%   |
| 1-20           | 27        | 5.57%   |
| 21-50          | 25        | 5.15%   |
| Unknown        | 11        | 2.27%   |
| 2001-3000      | 7         | 1.44%   |
| More than 3000 | 6         | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 186       | 37.27%  |
| 21-50          | 80        | 16.03%  |
| 101-250        | 63        | 12.63%  |
| 51-100         | 62        | 12.42%  |
| 501-1000       | 42        | 8.42%   |
| 251-500        | 41        | 8.22%   |
| Unknown        | 11        | 2.2%    |
| 1001-2000      | 7         | 1.4%    |
| More than 3000 | 5         | 1%      |
| 2001-3000      | 2         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 4.88%   |
| Toshiba MQ01ABD050 500GB                       | 2         | 2      | 4.88%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 4.88%   |
| Seagate ST9500325AS 500GB                      | 2         | 2      | 4.88%   |
| Seagate ST1000LM035-1RK172 1TB                 | 2         | 2      | 4.88%   |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1         | 1      | 2.44%   |
| WDC WD5000LPVX-80V0TT0 500GB                   | 1         | 1      | 2.44%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 1         | 2      | 2.44%   |
| WDC WD3200BPVT-75ZEST0 320GB                   | 1         | 1      | 2.44%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 2.44%   |
| WDC WD10SPZX-08Z10 1TB                         | 1         | 1      | 2.44%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 1      | 2.44%   |
| WDC WD10EARS-00MVWB0 1TB                       | 1         | 1      | 2.44%   |
| WDC WD1002FBYS-18A6B0 1TB                      | 1         | 1      | 2.44%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 2.44%   |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 2.44%   |
| Toshiba HDWD105 500GB                          | 1         | 1      | 2.44%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.44%   |
| Seagate ST3500413AS 500GB                      | 1         | 1      | 2.44%   |
| Seagate ST3320613AS 320GB                      | 1         | 1      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 1      | 2.44%   |
| Seagate ST1000LM014-SSHD-8GB                   | 1         | 1      | 2.44%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 2      | 2.44%   |
| Samsung Electronics HD502HI 500GB              | 1         | 2      | 2.44%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 2.44%   |
| Maxtor 6Y080M0 81GB                            | 1         | 1      | 2.44%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 2.44%   |
| Hitachi HDS721010KLA330 1TB                    | 1         | 1      | 2.44%   |
| Hitachi HCT721010SLA360 1TB                    | 1         | 1      | 2.44%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 2.44%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 29.27%  |
| WDC                 | 9         | 10     | 21.95%  |
| Toshiba             | 9         | 9      | 21.95%  |
| Hitachi             | 5         | 5      | 12.2%   |
| Samsung Electronics | 2         | 4      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| Maxtor              | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 31.58%  |
| Toshiba             | 9         | 9      | 23.68%  |
| WDC                 | 8         | 9      | 21.05%  |
| Hitachi             | 5         | 5      | 13.16%  |
| HGST                | 2         | 2      | 5.26%   |
| Samsung Electronics | 1         | 2      | 2.63%   |
| Maxtor              | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 40     | 92.31%  |
| SSD  | 3         | 4      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 330       | 511    | 67.76%  |
| Works    | 118       | 177    | 24.23%  |
| Malfunc  | 38        | 44     | 7.8%    |
| Failed   | 1         | 1      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 410       | 79.46%  |
| AMD                              | 32        | 6.2%    |
| Samsung Electronics              | 21        | 4.07%   |
| Micron Technology                | 7         | 1.36%   |
| SanDisk                          | 5         | 0.97%   |
| Nvidia                           | 5         | 0.97%   |
| Union Memory (Shenzhen)          | 4         | 0.78%   |
| VIA Technologies                 | 3         | 0.58%   |
| SK hynix                         | 3         | 0.58%   |
| Silicon Motion                   | 3         | 0.58%   |
| Marvell Technology Group         | 3         | 0.58%   |
| Hewlett-Packard                  | 3         | 0.58%   |
| ASMedia Technology               | 3         | 0.58%   |
| Toshiba America Info Systems     | 2         | 0.39%   |
| Phison Electronics               | 2         | 0.39%   |
| Kingston Technology Company      | 2         | 0.39%   |
| JMicron Technology               | 2         | 0.39%   |
| ADATA Technology                 | 2         | 0.39%   |
| ULi Electronics                  | 1         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Realtek Semiconductor            | 1         | 0.19%   |
| Micron/Crucial Technology        | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 49        | 8.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 35        | 5.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 32        | 5.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 29        | 4.92%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 29        | 4.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 20        | 3.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 19        | 3.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 18        | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 18        | 3.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 18        | 3.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 15        | 2.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 1.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 11        | 1.87%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10        | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 1.7%    |
| Samsung NVMe SSD Controller 980                                                         | 9         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 1.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 1.36%   |
| Micron Non-Volatile memory controller                                                   | 7         | 1.19%   |
| Intel SSD 660P Series                                                                   | 7         | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 5         | 0.85%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 4         | 0.68%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 0.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.68%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4         | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 0.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 0.68%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 0.51%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3         | 0.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 0.51%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3         | 0.51%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3         | 0.51%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 0.51%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 0.51%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2         | 0.34%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 0.34%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.34%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.34%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.34%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.34%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.34%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2         | 0.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 0.34%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 0.34%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 351       | 67.11%  |
| IDE  | 70        | 13.38%  |
| NVMe | 56        | 10.71%  |
| RAID | 46        | 8.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 428       | 91.45%  |
| AMD    | 38        | 8.12%   |
| ARM    | 2         | 0.43%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 19        | 4.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 14        | 2.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 11        | 2.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 9         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 9         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 8         | 1.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 8         | 1.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 7         | 1.5%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 7         | 1.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 6         | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 1.28%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 6         | 1.28%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 5         | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 1.07%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 5         | 1.07%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 5         | 1.07%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 1.07%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 5         | 1.07%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5         | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 1.07%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4         | 0.85%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 4         | 0.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 4         | 0.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 4         | 0.85%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4         | 0.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 4         | 0.85%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4         | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 4         | 0.85%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 4         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 0.64%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3         | 0.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3         | 0.64%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz           | 3         | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 0.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 3         | 0.64%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 3         | 0.64%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 3         | 0.64%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 3         | 0.64%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 3         | 0.64%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz        | 3         | 0.64%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3         | 0.64%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 0.64%   |
| Intel Atom CPU N450 @ 1.66GHz               | 3         | 0.64%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 2         | 0.43%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 0.43%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2         | 0.43%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2         | 0.43%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2         | 0.43%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2         | 0.43%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2         | 0.43%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2         | 0.43%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 2         | 0.43%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2         | 0.43%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 2         | 0.43%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 0.43%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.43%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 0.43%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 2         | 0.43%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 0.43%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 151       | 32.26%  |
| Intel Core i5           | 132       | 28.21%  |
| Intel Core i3           | 34        | 7.26%   |
| Intel Core 2 Duo        | 25        | 5.34%   |
| Intel Pentium           | 22        | 4.7%    |
| Other                   | 16        | 3.42%   |
| Intel Celeron           | 11        | 2.35%   |
| Intel Pentium Dual-Core | 9         | 1.92%   |
| AMD Ryzen 7             | 9         | 1.92%   |
| Intel Atom              | 7         | 1.5%    |
| Intel Xeon              | 5         | 1.07%   |
| AMD FX                  | 5         | 1.07%   |
| Intel Core 2 Quad       | 4         | 0.85%   |
| Intel Pentium Dual      | 3         | 0.64%   |
| Intel Genuine           | 3         | 0.64%   |
| AMD E1                  | 3         | 0.64%   |
| AMD A4                  | 3         | 0.64%   |
| Intel Xeon Gold         | 2         | 0.43%   |
| Intel Pentium Silver    | 2         | 0.43%   |
| Intel Pentium 4         | 2         | 0.43%   |
| AMD Ryzen 5             | 2         | 0.43%   |
| AMD Ryzen 3             | 2         | 0.43%   |
| AMD Athlon 64           | 2         | 0.43%   |
| AMD A10                 | 2         | 0.43%   |
| Intel Core M            | 1         | 0.21%   |
| Intel Core i9           | 1         | 0.21%   |
| ARM BCM                 | 1         | 0.21%   |
| AMD PRO A8              | 1         | 0.21%   |
| AMD PRO A10             | 1         | 0.21%   |
| AMD Phenom II X4        | 1         | 0.21%   |
| AMD E2                  | 1         | 0.21%   |
| AMD Athlon II X3        | 1         | 0.21%   |
| AMD Athlon II X2        | 1         | 0.21%   |
| AMD Athlon 64 X2        | 1         | 0.21%   |
| AMD Athlon              | 1         | 0.21%   |
| AMD A6                  | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 244       | 52.14%  |
| 4      | 168       | 35.9%   |
| 8      | 20        | 4.27%   |
| 6      | 18        | 3.85%   |
| 1      | 10        | 2.14%   |
| 24     | 2         | 0.43%   |
| 14     | 2         | 0.43%   |
| 3      | 2         | 0.43%   |
| 52     | 1         | 0.21%   |
| 44     | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 462       | 98.72%  |
| 2      | 6         | 1.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 335       | 71.43%  |
| 1      | 134       | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 452       | 96.17%  |
| Unknown        | 13        | 2.77%   |
| 32-bit         | 5         | 1.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 16.25%  |
| 0x306a9    | 46        | 9.58%   |
| 0x306c3    | 32        | 6.67%   |
| 0x206a7    | 28        | 5.83%   |
| 0x806ea    | 27        | 5.63%   |
| 0x1067a    | 25        | 5.21%   |
| 0x306d4    | 21        | 4.38%   |
| 0x20655    | 19        | 3.96%   |
| 0x806e9    | 16        | 3.33%   |
| 0x506e3    | 15        | 3.13%   |
| 0x906e9    | 14        | 2.92%   |
| 0x806ec    | 13        | 2.71%   |
| 0x906ea    | 12        | 2.5%    |
| 0x40651    | 11        | 2.29%   |
| 0x406e3    | 9         | 1.88%   |
| 0x6fd      | 7         | 1.46%   |
| 0x20652    | 7         | 1.46%   |
| 0x806c1    | 6         | 1.25%   |
| 0x106e5    | 6         | 1.25%   |
| 0xa0652    | 5         | 1.04%   |
| 0x706e5    | 4         | 0.83%   |
| 0x706a1    | 4         | 0.83%   |
| 0x6fb      | 4         | 0.83%   |
| 0x906ed    | 3         | 0.63%   |
| 0x806d1    | 3         | 0.63%   |
| 0x30678    | 3         | 0.63%   |
| 0x106ca    | 3         | 0.63%   |
| 0x10676    | 3         | 0.63%   |
| 0x0700010f | 3         | 0.63%   |
| 0x0600611a | 3         | 0.63%   |
| 0xa0653    | 2         | 0.42%   |
| 0x906eb    | 2         | 0.42%   |
| 0x906a3    | 2         | 0.42%   |
| 0x6e8      | 2         | 0.42%   |
| 0x306f2    | 2         | 0.42%   |
| 0x306e4    | 2         | 0.42%   |
| 0x30661    | 2         | 0.42%   |
| 0x08600104 | 2         | 0.42%   |
| 0x06003109 | 2         | 0.42%   |
| 0x010000c8 | 2         | 0.42%   |
| 0xf4a      | 1         | 0.21%   |
| 0xf49      | 1         | 0.21%   |
| 0xf41      | 1         | 0.21%   |
| 0xf33      | 1         | 0.21%   |
| 0xa0655    | 1         | 0.21%   |
| 0x906ec    | 1         | 0.21%   |
| 0x806eb    | 1         | 0.21%   |
| 0x6fa      | 1         | 0.21%   |
| 0x506c9    | 1         | 0.21%   |
| 0x50657    | 1         | 0.21%   |
| 0x50654    | 1         | 0.21%   |
| 0x406c4    | 1         | 0.21%   |
| 0x406c3    | 1         | 0.21%   |
| 0x206c2    | 1         | 0.21%   |
| 0x106a5    | 1         | 0.21%   |
| 0x10661    | 1         | 0.21%   |
| 0x08608102 | 1         | 0.21%   |
| 0x08108109 | 1         | 0.21%   |
| 0x08108102 | 1         | 0.21%   |
| 0x0800820d | 1         | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 102       | 21.79%  |
| Haswell          | 59        | 12.61%  |
| IvyBridge        | 55        | 11.75%  |
| Skylake          | 30        | 6.41%   |
| SandyBridge      | 30        | 6.41%   |
| Penryn           | 30        | 6.41%   |
| Westmere         | 29        | 6.2%    |
| Broadwell        | 21        | 4.49%   |
| Core             | 13        | 2.78%   |
| CometLake        | 9         | 1.92%   |
| Nehalem          | 8         | 1.71%   |
| TigerLake        | 7         | 1.5%    |
| Icelake          | 7         | 1.5%    |
| Excavator        | 7         | 1.5%    |
| Goldmont plus    | 6         | 1.28%   |
| Unknown          | 6         | 1.28%   |
| Zen+             | 5         | 1.07%   |
| Silvermont       | 5         | 1.07%   |
| Bonnell          | 5         | 1.07%   |
| NetBurst         | 4         | 0.85%   |
| K10              | 4         | 0.85%   |
| Zen 2            | 3         | 0.64%   |
| Steamroller      | 3         | 0.64%   |
| K8 Hammer        | 3         | 0.64%   |
| Jaguar           | 3         | 0.64%   |
| Zen              | 2         | 0.43%   |
| Puma             | 2         | 0.43%   |
| P6               | 2         | 0.43%   |
| Goldmont         | 2         | 0.43%   |
| Alderlake Hybrid | 2         | 0.43%   |
| Zen 3            | 1         | 0.21%   |
| K10 Llano        | 1         | 0.21%   |
| Bulldozer        | 1         | 0.21%   |
| Bobcat           | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 333       | 48.83%  |
| Nvidia                     | 229       | 33.58%  |
| AMD                        | 113       | 16.57%  |
| ASPEED Technology          | 3         | 0.44%   |
| VIA Technologies           | 1         | 0.15%   |
| Trident Microsystems       | 1         | 0.15%   |
| Matrox Electronics Systems | 1         | 0.15%   |
| ATI Technologies           | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 34        | 4.91%   |
| Intel UHD Graphics 620                                                                | 29        | 4.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 21        | 3.03%   |
| Intel HD Graphics 620                                                                 | 20        | 2.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 20        | 2.89%   |
| Intel HD Graphics 5500                                                                | 19        | 2.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 15        | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 15        | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                   | 15        | 2.17%   |
| Intel HD Graphics 630                                                                 | 14        | 2.02%   |
| Intel HD Graphics 530                                                                 | 12        | 1.73%   |
| Nvidia GP108M [GeForce MX150]                                                         | 11        | 1.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 11        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 10        | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 10        | 1.45%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 9         | 1.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 9         | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 1.3%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 1.3%    |
| Nvidia GM108M [GeForce 940MX]                                                         | 8         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 8         | 1.16%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 8         | 1.16%   |
| Nvidia GT218 [GeForce 210]                                                            | 7         | 1.01%   |
| Nvidia GM108M [GeForce MX110]                                                         | 7         | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 7         | 1.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 1.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 1.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 7         | 1.01%   |
| Nvidia GM108M [GeForce 840M]                                                          | 6         | 0.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 6         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 0.72%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 5         | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 5         | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 5         | 0.72%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 5         | 0.72%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 5         | 0.72%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 5         | 0.72%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 5         | 0.72%   |
| Nvidia GP107M [GeForce MX350]                                                         | 4         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 0.58%   |
| Nvidia GF119 [GeForce GT 610]                                                         | 4         | 0.58%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                     | 4         | 0.58%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 0.58%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 0.58%   |
| Nvidia TU117M                                                                         | 3         | 0.43%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.43%   |
| Nvidia GP108M [GeForce MX250]                                                         | 3         | 0.43%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 3         | 0.43%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 3         | 0.43%   |
| Nvidia GM107 [GeForce 940MX]                                                          | 3         | 0.43%   |
| Nvidia GK107M [GeForce GT 750M]                                                       | 3         | 0.43%   |
| Nvidia GF119M [GeForce 610M]                                                          | 3         | 0.43%   |
| Nvidia GF119 [GeForce GT 520]                                                         | 3         | 0.43%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 3         | 0.43%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 0.43%   |
| Nvidia G96C [GeForce 9500 GT]                                                         | 3         | 0.43%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 3         | 0.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 0.43%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller               | 3         | 0.43%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                | 3         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Intel + Nvidia           | 155       | 33.05%  |
| 1 x Intel                | 127       | 27.08%  |
| 1 x Nvidia               | 65        | 13.86%  |
| Intel + AMD              | 51        | 10.87%  |
| 1 x AMD                  | 50        | 10.66%  |
| AMD + Nvidia             | 7         | 1.49%   |
| 2 x AMD                  | 6         | 1.28%   |
| Other                    | 2         | 0.43%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.21%   |
| 1 x VIA                  | 1         | 0.21%   |
| 1 x Trident Microsystems | 1         | 0.21%   |
| Nvidia + ASPEED          | 1         | 0.21%   |
| 1 x Matrox               | 1         | 0.21%   |
| 1 x ASPEED               | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 354       | 74.53%  |
| Proprietary | 104       | 21.89%  |
| Unknown     | 17        | 3.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 218       | 45.61%  |
| 1.01-2.0   | 98        | 20.5%   |
| 3.01-4.0   | 57        | 11.92%  |
| 0.51-1.0   | 53        | 11.09%  |
| 0.01-0.5   | 36        | 7.53%   |
| 5.01-6.0   | 8         | 1.67%   |
| 7.01-8.0   | 6         | 1.26%   |
| 2.01-3.0   | 1         | 0.21%   |
| 8.01-16.0  | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 72        | 15.48%  |
| LG Display              | 72        | 15.48%  |
| AU Optronics            | 67        | 14.41%  |
| Goldstar                | 50        | 10.75%  |
| BOE                     | 50        | 10.75%  |
| Chimei Innolux          | 49        | 10.54%  |
| Chi Mei Optoelectronics | 11        | 2.37%   |
| Hewlett-Packard         | 9         | 1.94%   |
| PANDA                   | 8         | 1.72%   |
| Ancor Communications    | 8         | 1.72%   |
| AOC                     | 7         | 1.51%   |
| CHD                     | 6         | 1.29%   |
| BenQ                    | 6         | 1.29%   |
| LG Electronics          | 5         | 1.08%   |
| Lenovo                  | 5         | 1.08%   |
| Sony                    | 4         | 0.86%   |
| HannStar                | 4         | 0.86%   |
| Dell                    | 4         | 0.86%   |
| Unknown                 | 3         | 0.65%   |
| RTK                     | 3         | 0.65%   |
| Sharp                   | 2         | 0.43%   |
| InnoLux Display         | 2         | 0.43%   |
| InfoVision              | 2         | 0.43%   |
| Apple                   | 2         | 0.43%   |
| XVision                 | 1         | 0.22%   |
| Seiko/Epson             | 1         | 0.22%   |
| Quanta Display          | 1         | 0.22%   |
| PAR                     | 1         | 0.22%   |
| Nvidia                  | 1         | 0.22%   |
| MSI                     | 1         | 0.22%   |
| LGD                     | 1         | 0.22%   |
| LG Philips              | 1         | 0.22%   |
| KDC                     | 1         | 0.22%   |
| cPATH                   | 1         | 0.22%   |
| CHI                     | 1         | 0.22%   |
| AUS                     | 1         | 0.22%   |
| ASUSTek Computer        | 1         | 0.22%   |
| Acer                    | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 2.32%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 8         | 1.68%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 7         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 1.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.05%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 440x250mm 19.9-inch         | 4         | 0.84%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 4         | 0.84%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.84%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch                  | 4         | 0.84%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.84%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 4         | 0.84%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.84%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.84%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.84%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch        | 3         | 0.63%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch         | 3         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.63%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 3         | 0.63%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                   | 3         | 0.63%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 3         | 0.63%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 3         | 0.63%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 3         | 0.63%   |
| LG Display LCD Monitor LGD044F 1920x1080 344x194mm 15.5-inch             | 3         | 0.63%   |
| Goldstar W2053 GSM4E9F 1600x900 443x249mm 20.0-inch                      | 3         | 0.63%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 3         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 3         | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.63%   |
| CHD PMOS240-IFC-1 CHD0240 1920x1080 368x207mm 16.6-inch                  | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 3         | 0.63%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.42%   |
| Samsung Electronics C27FG70 SAM0DC9 1920x1080 598x337mm 27.0-inch        | 2         | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.42%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.42%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.42%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD0554 3240x2160 317x211mm 15.0-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD03E6 1366x768 345x194mm 15.6-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 2         | 0.42%   |
| Lenovo LCD Monitor LEN0BD0 1920x1080 510x290mm 23.1-inch                 | 2         | 0.42%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch              | 2         | 0.42%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 470x300mm 22.0-inch             | 2         | 0.42%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 0.42%   |
| Goldstar T730BH GSM43C2 1152x864 310x230mm 15.2-inch                     | 2         | 0.42%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch                | 2         | 0.42%   |
| Goldstar F700B GSM4344 1280x1024 315x230mm 15.4-inch                     | 2         | 0.42%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                      | 2         | 0.42%   |
| Goldstar 19M45 GSM4C27 1366x768 410x230mm 18.5-inch                      | 2         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 196       | 43.08%  |
| 1366x768 (WXGA)    | 145       | 31.87%  |
| 1600x900 (HD+)     | 25        | 5.49%   |
| 1440x900 (WXGA+)   | 19        | 4.18%   |
| 3840x2160 (4K)     | 13        | 2.86%   |
| 1280x800 (WXGA)    | 10        | 2.2%    |
| 1680x1050 (WSXGA+) | 8         | 1.76%   |
| 1360x768           | 7         | 1.54%   |
| 1280x1024 (SXGA)   | 7         | 1.54%   |
| Unknown            | 5         | 1.1%    |
| 1024x600           | 4         | 0.88%   |
| 3240x2160          | 2         | 0.44%   |
| 2560x1080          | 2         | 0.44%   |
| 1920x1200 (WUXGA)  | 2         | 0.44%   |
| 1280x960           | 2         | 0.44%   |
| 5760x2160          | 1         | 0.22%   |
| 3840x2400          | 1         | 0.22%   |
| 3840x1080          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 2944x1080          | 1         | 0.22%   |
| 2720x768           | 1         | 0.22%   |
| 2560x1440 (QHD)    | 1         | 0.22%   |
| 1680x945           | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 224       | 48.28%  |
| 21      | 33        | 7.11%   |
| 13      | 32        | 6.9%    |
| 14      | 31        | 6.68%   |
| Unknown | 20        | 4.31%   |
| 20      | 16        | 3.45%   |
| 18      | 16        | 3.45%   |
| 23      | 14        | 3.02%   |
| 19      | 13        | 2.8%    |
| 12      | 10        | 2.16%   |
| 24      | 8         | 1.72%   |
| 17      | 8         | 1.72%   |
| 27      | 7         | 1.51%   |
| 22      | 7         | 1.51%   |
| 10      | 5         | 1.08%   |
| 16      | 4         | 0.86%   |
| 46      | 3         | 0.65%   |
| 11      | 3         | 0.65%   |
| 72      | 2         | 0.43%   |
| 32      | 2         | 0.43%   |
| 84      | 1         | 0.22%   |
| 65      | 1         | 0.22%   |
| 47      | 1         | 0.22%   |
| 40      | 1         | 0.22%   |
| 31      | 1         | 0.22%   |
| 29      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 283       | 61.26%  |
| 401-500     | 83        | 17.97%  |
| 501-600     | 28        | 6.06%   |
| 201-300     | 25        | 5.41%   |
| Unknown     | 20        | 4.33%   |
| 351-400     | 9         | 1.95%   |
| 1001-1500   | 5         | 1.08%   |
| 601-700     | 3         | 0.65%   |
| 1501-2000   | 3         | 0.65%   |
| 701-800     | 2         | 0.43%   |
| 801-900     | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 372       | 85.52%  |
| 16/10   | 34        | 7.82%   |
| Unknown | 18        | 4.14%   |
| 4/3     | 5         | 1.15%   |
| 3/2     | 3         | 0.69%   |
| 5/4     | 2         | 0.46%   |
| 21/9    | 1         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 223       | 48.06%  |
| 201-250        | 57        | 12.28%  |
| 81-90          | 56        | 12.07%  |
| 151-200        | 34        | 7.33%   |
| Unknown        | 20        | 4.31%   |
| 141-150        | 17        | 3.66%   |
| 61-70          | 10        | 2.16%   |
| 301-350        | 8         | 1.72%   |
| 121-130        | 7         | 1.51%   |
| 71-80          | 5         | 1.08%   |
| 41-50          | 5         | 1.08%   |
| 501-1000       | 5         | 1.08%   |
| More than 1000 | 4         | 0.86%   |
| 51-60          | 3         | 0.65%   |
| 351-500        | 3         | 0.65%   |
| 131-140        | 3         | 0.65%   |
| 91-100         | 2         | 0.43%   |
| 251-300        | 1         | 0.22%   |
| 111-120        | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 154       | 33.62%  |
| 121-160       | 149       | 32.53%  |
| 51-100        | 114       | 24.89%  |
| Unknown       | 20        | 4.37%   |
| More than 240 | 13        | 2.84%   |
| 1-50          | 6         | 1.31%   |
| 161-240       | 2         | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 404       | 85.41%  |
| 2     | 48        | 10.15%  |
| 0     | 20        | 4.23%   |
| 3     | 1         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 282       | 37.01%  |
| Intel                            | 186       | 24.41%  |
| Qualcomm Atheros                 | 106       | 13.91%  |
| Broadcom                         | 47        | 6.17%   |
| Ralink Technology                | 17        | 2.23%   |
| Ralink                           | 17        | 2.23%   |
| Samsung Electronics              | 16        | 2.1%    |
| Broadcom Limited                 | 16        | 2.1%    |
| D-Link                           | 10        | 1.31%   |
| Xiaomi                           | 9         | 1.18%   |
| Marvell Technology Group         | 7         | 0.92%   |
| VIA Technologies                 | 5         | 0.66%   |
| MediaTek                         | 5         | 0.66%   |
| TP-Link                          | 4         | 0.52%   |
| Huawei Technologies              | 4         | 0.52%   |
| Nvidia                           | 3         | 0.39%   |
| JMicron Technology               | 3         | 0.39%   |
| HTC (High Tech Computer)         | 3         | 0.39%   |
| D-Link System                    | 3         | 0.39%   |
| Qualcomm Atheros Communications  | 2         | 0.26%   |
| Microsoft                        | 2         | 0.26%   |
| Hewlett-Packard                  | 2         | 0.26%   |
| ASUSTek Computer                 | 2         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |
| Sierra Wireless                  | 1         | 0.13%   |
| Qualcomm                         | 1         | 0.13%   |
| LG Electronics                   | 1         | 0.13%   |
| Lenovo                           | 1         | 0.13%   |
| ICS Advent                       | 1         | 0.13%   |
| BUFFALO                          | 1         | 0.13%   |
| Attansic Technology              | 1         | 0.13%   |
| ASIX Electronics                 | 1         | 0.13%   |
| Aquantia                         | 1         | 0.13%   |
| AboCom Systems                   | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 224       | 26.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 3.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 2.56%   |
| Intel Wireless 7265                                               | 21        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.51%   |
| Ralink MT7601U Wireless Adapter                                   | 13        | 1.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 1.51%   |
| Intel Wireless 7260                                               | 13        | 1.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 12        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 1.28%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 10        | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 8         | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.81%   |
| Intel Wireless 8260                                               | 7         | 0.81%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.7%    |
| Intel Centrino Advanced-N 6200                                    | 6         | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.58%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 5         | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 0.47%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 4         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.47%   |
| Ralink RT5370 Wireless Adapter                                    | 4         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.47%   |
| Intel Wireless 3165                                               | 4         | 0.47%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 0.47%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.47%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.47%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.47%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 3         | 0.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.35%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3         | 0.35%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 153       | 38.73%  |
| Qualcomm Atheros                | 83        | 21.01%  |
| Realtek Semiconductor           | 54        | 13.67%  |
| Broadcom                        | 30        | 7.59%   |
| Ralink Technology               | 17        | 4.3%    |
| Ralink                          | 17        | 4.3%    |
| Broadcom Limited                | 13        | 3.29%   |
| D-Link                          | 9         | 2.28%   |
| TP-Link                         | 4         | 1.01%   |
| MediaTek                        | 4         | 1.01%   |
| Qualcomm Atheros Communications | 2         | 0.51%   |
| Hewlett-Packard                 | 2         | 0.51%   |
| D-Link System                   | 2         | 0.51%   |
| Xiaomi                          | 1         | 0.25%   |
| Sierra Wireless                 | 1         | 0.25%   |
| Marvell Technology Group        | 1         | 0.25%   |
| BUFFALO                         | 1         | 0.25%   |
| AboCom Systems                  | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 5.54%   |
| Intel Wireless 7265                                                     | 21        | 5.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 3.27%   |
| Ralink MT7601U Wireless Adapter                                         | 13        | 3.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 3.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 3.27%   |
| Intel Wireless 7260                                                     | 13        | 3.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 3.02%   |
| Intel Wireless 8265 / 8275                                              | 12        | 3.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 2.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 2.52%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 1.76%   |
| Intel Wireless 8260                                                     | 7         | 1.76%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.51%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 1.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.26%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                          | 5         | 1.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.01%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 1.01%   |
| Intel Wireless 3165                                                     | 4         | 1.01%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.01%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.01%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 3         | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.76%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.76%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 0.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.76%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                    | 2         | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 2         | 0.5%    |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 2         | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.5%    |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.5%    |
| Intel Wireless-AC 9260                                                  | 2         | 0.5%    |
| Intel Wireless 3160                                                     | 2         | 0.5%    |
| Intel WiFi Link 5100                                                    | 2         | 0.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.5%    |
| Intel Centrino Wireless-N 135                                           | 2         | 0.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.5%    |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 0.5%    |
| D-Link WLAN controller                                                  | 2         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 264       | 57.64%  |
| Intel                            | 67        | 14.63%  |
| Qualcomm Atheros                 | 37        | 8.08%   |
| Broadcom                         | 25        | 5.46%   |
| Samsung Electronics              | 16        | 3.49%   |
| Xiaomi                           | 8         | 1.75%   |
| Marvell Technology Group         | 6         | 1.31%   |
| VIA Technologies                 | 5         | 1.09%   |
| Huawei Technologies              | 4         | 0.87%   |
| Nvidia                           | 3         | 0.66%   |
| JMicron Technology               | 3         | 0.66%   |
| HTC (High Tech Computer)         | 3         | 0.66%   |
| Broadcom Limited                 | 3         | 0.66%   |
| Microsoft                        | 2         | 0.44%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Qualcomm                         | 1         | 0.22%   |
| MediaTek                         | 1         | 0.22%   |
| LG Electronics                   | 1         | 0.22%   |
| Lenovo                           | 1         | 0.22%   |
| ICS Advent                       | 1         | 0.22%   |
| D-Link System                    | 1         | 0.22%   |
| D-Link                           | 1         | 0.22%   |
| Attansic Technology              | 1         | 0.22%   |
| ASUSTek Computer                 | 1         | 0.22%   |
| ASIX Electronics                 | 1         | 0.22%   |
| Aquantia                         | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 224       | 48.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 33        | 7.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 3.47%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 10        | 2.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 7         | 1.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 7         | 1.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 6         | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 5         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 5         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 4         | 0.87%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 4         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 4         | 0.87%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 0.87%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4         | 0.87%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.65%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.65%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.65%   |
| Huawei LYA-L09                                                                 | 3         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.43%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.43%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                              | 2         | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2         | 0.43%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.43%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.43%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.43%   |
| Intel Ethernet Connection (16) I219-LM                                         | 2         | 0.43%   |
| HTC (High Tech Computer) HTC                                                   | 2         | 0.43%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 2         | 0.43%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.22%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.22%   |
| Qualcomm Android                                                               | 1         | 0.22%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.22%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.22%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 0.22%   |
| MediaTek moto e(6) plus                                                        | 1         | 0.22%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.22%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.22%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                            | 1         | 0.22%   |
| Lenovo Android Phone                                                           | 1         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 415       | 51.81%  |
| WiFi     | 385       | 48.06%  |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 322       | 71.4%   |
| Ethernet | 128       | 28.38%  |
| Unknown  | 1         | 0.22%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 301       | 64.32%  |
| 1     | 157       | 33.55%  |
| 0     | 5         | 1.07%   |
| 3     | 3         | 0.64%   |
| 4     | 2         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 439       | 93.21%  |
| Yes  | 32        | 6.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 112       | 38.89%  |
| IMC Networks                    | 35        | 12.15%  |
| Qualcomm Atheros Communications | 25        | 8.68%   |
| Realtek Semiconductor           | 20        | 6.94%   |
| Broadcom                        | 16        | 5.56%   |
| Lite-On Technology              | 14        | 4.86%   |
| Cambridge Silicon Radio         | 14        | 4.86%   |
| Foxconn / Hon Hai               | 12        | 4.17%   |
| Dell                            | 9         | 3.13%   |
| Ralink                          | 8         | 2.78%   |
| ASUSTek Computer                | 6         | 2.08%   |
| Foxconn International           | 4         | 1.39%   |
| Ralink Technology               | 3         | 1.04%   |
| Hewlett-Packard                 | 2         | 0.69%   |
| Askey Computer                  | 2         | 0.69%   |
| Apple                           | 2         | 0.69%   |
| Realtek                         | 1         | 0.35%   |
| Micro Star International        | 1         | 0.35%   |
| Marvell Semiconductor           | 1         | 0.35%   |
| Integrated System Solution      | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 62        | 21.53%  |
| Intel AX201 Bluetooth                                                               | 19        | 6.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 5.56%   |
| IMC Networks Bluetooth Radio                                                        | 16        | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 4.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 14        | 4.86%   |
| Realtek Bluetooth Radio                                                             | 10        | 3.47%   |
| IMC Networks Bluetooth Device                                                       | 10        | 3.47%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 2.78%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 6         | 2.08%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.74%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.74%   |
| Intel Bluetooth Device                                                              | 4         | 1.39%   |
| Intel AX200 Bluetooth                                                               | 4         | 1.39%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 1.39%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.39%   |
| Broadcom BCM20702A0                                                                 | 4         | 1.39%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.04%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 1.04%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.04%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 1.04%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 1.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.69%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.69%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.69%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.69%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.69%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.69%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.69%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.69%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.69%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.69%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.69%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.69%   |
| Askey Bluetooth Device                                                              | 2         | 0.69%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.35%   |
| Ralink CSR BS8510                                                                   | 1         | 0.35%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.35%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.35%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.35%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.35%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.35%   |
| Integrated System Solution Bluetooth Device                                         | 1         | 0.35%   |
| IMC Networks Bluetooth                                                              | 1         | 0.35%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.35%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.35%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.35%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.35%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.35%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.35%   |
| Broadcom Bluetooth                                                                  | 1         | 0.35%   |
| Broadcom BCM92045B3 ROM                                                             | 1         | 0.35%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.35%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 414       | 69.81%  |
| Nvidia                           | 96        | 16.19%  |
| AMD                              | 66        | 11.13%  |
| C-Media Electronics              | 4         | 0.67%   |
| Generalplus Technology           | 3         | 0.51%   |
| ASUSTek Computer                 | 2         | 0.34%   |
| Yamaha                           | 1         | 0.17%   |
| VIA Technologies                 | 1         | 0.17%   |
| ULi Electronics                  | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| Focusrite-Novation               | 1         | 0.17%   |
| ESS Technology                   | 1         | 0.17%   |
| Creative Labs                    | 1         | 0.17%   |
| C&T                              | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 60        | 8.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 47        | 6.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 38        | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 35        | 5.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 34        | 4.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 28        | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 25        | 3.64%   |
| Intel Broadwell-U Audio Controller                                                | 21        | 3.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 20        | 2.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 18        | 2.62%   |
| Nvidia GF108 High Definition Audio Controller                                     | 17        | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                        | 17        | 2.48%   |
| Intel Haswell-ULT HD Audio Controller                                             | 15        | 2.19%   |
| Intel CM238 HD Audio Controller                                                   | 15        | 2.19%   |
| Intel 8 Series HD Audio Controller                                                | 15        | 2.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 13        | 1.9%    |
| Nvidia High Definition Audio Controller                                           | 11        | 1.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 11        | 1.6%    |
| AMD Kabini HDMI/DP Audio                                                          | 10        | 1.46%   |
| AMD FCH Azalia Controller                                                         | 10        | 1.46%   |
| AMD Family 17h/19h HD Audio Controller                                            | 9         | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 8         | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 7         | 1.02%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7         | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 7         | 1.02%   |
| Intel Comet Lake PCH cAVS                                                         | 7         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 7         | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 7         | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6         | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 6         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6         | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5         | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5         | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 5         | 0.73%   |
| Intel 200 Series PCH HD Audio                                                     | 5         | 0.73%   |
| Nvidia GT216 HDMI Audio Controller                                                | 4         | 0.58%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4         | 0.58%   |
| Nvidia Audio device                                                               | 4         | 0.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 4         | 0.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4         | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4         | 0.58%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4         | 0.58%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 4         | 0.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 0.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3         | 0.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3         | 0.44%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3         | 0.44%   |
| Nvidia GA106 High Definition Audio Controller                                     | 3         | 0.44%   |
| Generalplus Technology USB Audio Device                                           | 3         | 0.44%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 3         | 0.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3         | 0.44%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 3         | 0.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 0.44%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 3         | 0.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3         | 0.44%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 0.44%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.29%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.29%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 68        | 28.81%  |
| SK hynix            | 38        | 16.1%   |
| Micron Technology   | 32        | 13.56%  |
| Kingston            | 21        | 8.9%    |
| Unknown             | 20        | 8.47%   |
| Crucial             | 14        | 5.93%   |
| Ramaxel Technology  | 10        | 4.24%   |
| Elpida              | 8         | 3.39%   |
| A-DATA Technology   | 7         | 2.97%   |
| GeIL                | 3         | 1.27%   |
| G.Skill             | 3         | 1.27%   |
| Corsair             | 3         | 1.27%   |
| Ramos Technology    | 2         | 0.85%   |
| Kingmax             | 2         | 0.85%   |
| TwinMOS             | 1         | 0.42%   |
| Transcend           | 1         | 0.42%   |
| Neo Forza           | 1         | 0.42%   |
| Nanya Technology    | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s    | 7         | 2.73%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s       | 6         | 2.34%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 1.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 5         | 1.95%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 5         | 1.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 4         | 1.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 1.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 1.56%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s   | 4         | 1.56%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s       | 4         | 1.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 3         | 1.17%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s   | 3         | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 1.17%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 1.17%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 3         | 1.17%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 3         | 1.17%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s        | 3         | 1.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.78%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.78%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 2         | 0.78%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 2         | 0.78%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 0.78%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 0.78%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s       | 2         | 0.78%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s       | 2         | 0.78%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 2         | 0.78%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.78%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 2         | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.78%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s          | 2         | 0.78%   |
| Ramos RAM EWB4GB681PAE-16IC 4096MB DIMM DDR3 1600MT/s       | 2         | 0.78%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 2         | 0.78%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s               | 2         | 0.78%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s    | 2         | 0.78%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s      | 2         | 0.78%   |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s       | 2         | 0.78%   |
| Kingston RAM ACR21D4S15HAG/8G 8192MB SODIMM DDR4 2133MT/s   | 2         | 0.78%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 1600MT/s      | 2         | 0.78%   |
| GeIL RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s      | 2         | 0.78%   |
| Crucial RAM CB8GS2400.C8JT 8GB SODIMM DDR4 2400MT/s         | 2         | 0.78%   |
| Corsair RAM CMX8GX3M1A1600C11 8192MB DIMM DDR3 1600MT/s     | 2         | 0.78%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s           | 2         | 0.78%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                 | 1         | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s              | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM                               | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM                                 | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM                            | 1         | 0.39%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                | 1         | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                     | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 400MT/s                         | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 85        | 44.04%  |
| DDR3    | 84        | 43.52%  |
| Unknown | 9         | 4.66%   |
| DDR2    | 7         | 3.63%   |
| SDRAM   | 3         | 1.55%   |
| LPDDR4  | 2         | 1.04%   |
| LPDDR3  | 2         | 1.04%   |
| DDR     | 1         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 143       | 75.26%  |
| DIMM         | 40        | 21.05%  |
| Row Of Chips | 6         | 3.16%   |
| Chip         | 1         | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 89        | 40.09%  |
| 8192  | 74        | 33.33%  |
| 2048  | 32        | 14.41%  |
| 16384 | 18        | 8.11%   |
| 1024  | 6         | 2.7%    |
| 32768 | 2         | 0.9%    |
| 65536 | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 57        | 26.39%  |
| 2667    | 41        | 18.98%  |
| 2400    | 19        | 8.8%    |
| 1334    | 18        | 8.33%   |
| 2133    | 15        | 6.94%   |
| 3200    | 13        | 6.02%   |
| 1333    | 12        | 5.56%   |
| 3266    | 7         | 3.24%   |
| 667     | 5         | 2.31%   |
| Unknown | 5         | 2.31%   |
| 800     | 4         | 1.85%   |
| 4199    | 3         | 1.39%   |
| 8400    | 2         | 0.93%   |
| 4800    | 2         | 0.93%   |
| 1867    | 2         | 0.93%   |
| 1067    | 2         | 0.93%   |
| 3600    | 1         | 0.46%   |
| 3066    | 1         | 0.46%   |
| 2933    | 1         | 0.46%   |
| 2448    | 1         | 0.46%   |
| 1800    | 1         | 0.46%   |
| 1400    | 1         | 0.46%   |
| 1328    | 1         | 0.46%   |
| 533     | 1         | 0.46%   |
| 400     | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 3         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| HP LaserJet P1102          | 1         | 16.67%  |
| HP LaserJet 1018           | 1         | 16.67%  |
| HP DeskJet 2130 series     | 1         | 16.67%  |
| Canon MG5600 series        | 1         | 16.67%  |
| Canon LBP6300              | 1         | 16.67%  |
| Canon iR2004/2204 UFRII LT | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 120            | 1         | 33.33%  |
| Canon CanoScan 4400F               | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 71        | 22.05%  |
| IMC Networks                           | 68        | 21.12%  |
| Acer                                   | 31        | 9.63%   |
| Realtek Semiconductor                  | 26        | 8.07%   |
| Microdia                               | 22        | 6.83%   |
| Syntek                                 | 16        | 4.97%   |
| Sunplus Innovation Technology          | 14        | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 3.73%   |
| Apple                                  | 10        | 3.11%   |
| Suyin                                  | 9         | 2.8%    |
| Lite-On Technology                     | 8         | 2.48%   |
| Sonix Technology                       | 6         | 1.86%   |
| Ricoh                                  | 5         | 1.55%   |
| Samsung Electronics                    | 3         | 0.93%   |
| Quanta                                 | 3         | 0.93%   |
| Pixart Imaging                         | 3         | 0.93%   |
| Lenovo                                 | 3         | 0.93%   |
| ALi                                    | 3         | 0.93%   |
| Primax Electronics                     | 1         | 0.31%   |
| OmniVision Technologies                | 1         | 0.31%   |
| MacroSilicon                           | 1         | 0.31%   |
| Luxvisions Innotech Limited            | 1         | 0.31%   |
| LG Electronics                         | 1         | 0.31%   |
| KYE Systems (Mouse Systems)            | 1         | 0.31%   |
| Importek                               | 1         | 0.31%   |
| Generalplus Technology                 | 1         | 0.31%   |
| Alcor Micro                            | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                       | 27        | 8.39%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 14        | 4.35%   |
| IMC Networks Integrated Camera                                           | 11        | 3.42%   |
| Acer Lenovo EasyCamera                                                   | 11        | 3.42%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 9         | 2.8%    |
| Chicony USB2.0 HD UVC WebCam                                             | 8         | 2.48%   |
| Chicony HD WebCam                                                        | 8         | 2.48%   |
| Chicony EasyCamera                                                       | 8         | 2.48%   |
| Chicony Integrated Camera                                                | 7         | 2.17%   |
| Syntek EasyCamera                                                        | 6         | 1.86%   |
| Syntek Lenovo EasyCamera                                                 | 5         | 1.55%   |
| Sunplus HD Webcam                                                        | 5         | 1.55%   |
| Sonix USB2.0 HD UVC WebCam                                               | 5         | 1.55%   |
| Realtek USB2.0 HD UVC WebCam                                             | 5         | 1.55%   |
| Realtek USB Camera                                                       | 5         | 1.55%   |
| IMC Networks Lenovo EasyCamera                                           | 5         | 1.55%   |
| Acer Integrated Camera                                                   | 5         | 1.55%   |
| Syntek Integrated Camera                                                 | 4         | 1.24%   |
| Sunplus ASUS USB2.0 Webcam                                               | 4         | 1.24%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 4         | 1.24%   |
| Microdia Integrated_Webcam_HD                                            | 4         | 1.24%   |
| Lite-On Integrated Camera                                                | 4         | 1.24%   |
| Chicony Integrated HP HD Webcam                                          | 4         | 1.24%   |
| Chicony HP HD Webcam [Fixed]                                             | 4         | 1.24%   |
| Chicony HP HD Webcam                                                     | 4         | 1.24%   |
| Acer Lenovo Integrated Webcam                                            | 4         | 1.24%   |
| Samsung Galaxy A5 (MTP)                                                  | 3         | 0.93%   |
| Microdia Sonix Integrated Webcam                                         | 3         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 0.93%   |
| Microdia Integrated Webcam                                               | 3         | 0.93%   |
| Lite-On HP HD Camera                                                     | 3         | 0.93%   |
| IMC Networks VGA UVC WebCam                                              | 3         | 0.93%   |
| IMC Networks Integrated Webcam                                           | 3         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 3         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 3         | 0.93%   |
| ALi Gateway Webcam                                                       | 3         | 0.93%   |
| Acer SunplusIT Integrated Camera                                         | 3         | 0.93%   |
| Sunplus Dell E5570 integrated webcam                                     | 2         | 0.62%   |
| Realtek Integrated_Webcam_HD                                             | 2         | 0.62%   |
| Realtek HD WebCam                                                        | 2         | 0.62%   |
| Quanta HD User Facing                                                    | 2         | 0.62%   |
| Pixart Imaging USB_2.0_Webcam                                            | 2         | 0.62%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 2         | 0.62%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M    | 2         | 0.62%   |
| Lenovo CNF7237&CNF7238                                                   | 2         | 0.62%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 0.62%   |
| Chicony Lenovo EasyCamera                                                | 2         | 0.62%   |
| Chicony HP Webcam [2 MP Macro]                                           | 2         | 0.62%   |
| Chicony HP Truevision HD                                                 | 2         | 0.62%   |
| Chicony HP HD Camera                                                     | 2         | 0.62%   |
| Chicony 2.0M UVC WebCam                                                  | 2         | 0.62%   |
| Chicony 1.3M HD WebCam                                                   | 2         | 0.62%   |
| Acer EasyCamera                                                          | 2         | 0.62%   |
| Acer BisonCam, NB Pro                                                    | 2         | 0.62%   |
| Syntek USB Video Device                                                  | 1         | 0.31%   |
| Suyin Sony Visual Communication Camera                                   | 1         | 0.31%   |
| Suyin LG Webcam                                                          | 1         | 0.31%   |
| Suyin Laptop_Integrated_Webcam_2HDM                                      | 1         | 0.31%   |
| Suyin Integrated_Webcam_2M                                               | 1         | 0.31%   |
| Suyin Integrated Webcam                                                  | 1         | 0.31%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 33        | 40.74%  |
| Shenzhen Goodix Technology | 13        | 16.05%  |
| Synaptics                  | 9         | 11.11%  |
| Elan Microelectronics      | 9         | 11.11%  |
| Upek                       | 8         | 9.88%   |
| AuthenTec                  | 4         | 4.94%   |
| LighTuning Technology      | 3         | 3.7%    |
| Suprema                    | 1         | 1.23%   |
| STMicroelectronics         | 1         | 1.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 14        | 17.28%  |
| Validity Sensors VFS491                                | 9         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                    | 9         | 11.11%  |
| Elan ELAN:Fingerprint                                  | 9         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 7         | 8.64%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 3.7%    |
| Synaptics  WBDI                                        | 3         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 3.7%    |
| Unknown                                                | 3         | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 2.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 2.47%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 2         | 2.47%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 2.47%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 1.23%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 1.23%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 1.23%   |
| Validity Sensors Synaptics WBDI                        | 1         | 1.23%   |
| Validity Sensors Fingerprint scanner                   | 1         | 1.23%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 1.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 1.23%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader       | 1         | 1.23%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 1.23%   |
| Shenzhen Goodix FingerPrint                            | 1         | 1.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 1.23%   |
| AuthenTec Fingerprint Sensor                           | 1         | 1.23%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 1.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 42.86%  |
| Alcor Micro | 4         | 28.57%  |
| Upek        | 2         | 14.29%  |
| O2 Micro    | 2         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 299       | 62.42%  |
| 1     | 132       | 27.56%  |
| 2     | 36        | 7.52%   |
| 3     | 8         | 1.67%   |
| 4     | 2         | 0.42%   |
| 8     | 1         | 0.21%   |
| 5     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 81        | 34.91%  |
| Graphics card            | 64        | 27.59%  |
| Net/wireless             | 20        | 8.62%   |
| Communication controller | 14        | 6.03%   |
| Bluetooth                | 14        | 6.03%   |
| Chipcard                 | 13        | 5.6%    |
| Camera                   | 6         | 2.59%   |
| Unassigned class         | 4         | 1.72%   |
| Storage                  | 4         | 1.72%   |
| Multimedia controller    | 4         | 1.72%   |
| Sound                    | 3         | 1.29%   |
| Card reader              | 2         | 0.86%   |
| Wireless                 | 1         | 0.43%   |
| Network                  | 1         | 0.43%   |
| Net/ethernet             | 1         | 0.43%   |

