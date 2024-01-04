Linux in Israel - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

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

Total: 570

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [94cf6bda69](https://linux-hardware.org/?probe=94cf6bda69) | Dec 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [69ec584b3a](https://linux-hardware.org/?probe=69ec584b3a) | Dec 25, 2023 |
| Lenovo        | Unknown                     | [9faf2278bb](https://linux-hardware.org/?probe=9faf2278bb) | Dec 24, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [5267b86c06](https://linux-hardware.org/?probe=5267b86c06) | Dec 24, 2023 |
| Lenovo        | M30-70 80H8                 | [8ec7db7a8a](https://linux-hardware.org/?probe=8ec7db7a8a) | Dec 22, 2023 |
| Dell          | Latitude 3520               | [7a4d520ba9](https://linux-hardware.org/?probe=7a4d520ba9) | Dec 20, 2023 |
| Dell          | Precision 3581              | [c20f7cf0e0](https://linux-hardware.org/?probe=c20f7cf0e0) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | [20edb747d9](https://linux-hardware.org/?probe=20edb747d9) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1c015093b2](https://linux-hardware.org/?probe=1c015093b2) | Dec 18, 2023 |
| Dell          | Inspiron 14 5420            | [22d7c1e77c](https://linux-hardware.org/?probe=22d7c1e77c) | Dec 16, 2023 |
| Chuwi         | HeroBook Pro                | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [eea00eb64c](https://linux-hardware.org/?probe=eea00eb64c) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5940ba1d2c](https://linux-hardware.org/?probe=5940ba1d2c) | Dec 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee3494fa57](https://linux-hardware.org/?probe=ee3494fa57) | Dec 06, 2023 |
| HP            | ProBook 430 G6              | [a7dd623bb6](https://linux-hardware.org/?probe=a7dd623bb6) | Dec 04, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [20e77986a2](https://linux-hardware.org/?probe=20e77986a2) | Dec 03, 2023 |
| Valve         | Jupiter                     | [ff8952a98c](https://linux-hardware.org/?probe=ff8952a98c) | Dec 01, 2023 |
| Unknown       | Unknown                     | [a719bb0ba3](https://linux-hardware.org/?probe=a719bb0ba3) | Nov 25, 2023 |
| Dell          | System XPS L502X            | [a59b920838](https://linux-hardware.org/?probe=a59b920838) | Nov 24, 2023 |
| HP            | Pavilion 15                 | [d188fc3095](https://linux-hardware.org/?probe=d188fc3095) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [ab7968d6da](https://linux-hardware.org/?probe=ab7968d6da) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [95f01d6e47](https://linux-hardware.org/?probe=95f01d6e47) | Nov 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [42a94f2f97](https://linux-hardware.org/?probe=42a94f2f97) | Oct 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [37e69bd8a8](https://linux-hardware.org/?probe=37e69bd8a8) | Oct 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [48b90d30be](https://linux-hardware.org/?probe=48b90d30be) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8c4e60d5ca](https://linux-hardware.org/?probe=8c4e60d5ca) | Oct 15, 2023 |
| Valve         | Jupiter                     | [9ed8384df0](https://linux-hardware.org/?probe=9ed8384df0) | Oct 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [5b710d03c5](https://linux-hardware.org/?probe=5b710d03c5) | Oct 09, 2023 |
| Dell          | Latitude 5411               | [48ecb46d24](https://linux-hardware.org/?probe=48ecb46d24) | Oct 09, 2023 |
| Dell          | Latitude 7400               | [1c4da154d8](https://linux-hardware.org/?probe=1c4da154d8) | Oct 07, 2023 |
| Dell          | Precision 5750              | [839fea4442](https://linux-hardware.org/?probe=839fea4442) | Oct 04, 2023 |
| ASUSTek       | S550CB                      | [9dc3e0f9f9](https://linux-hardware.org/?probe=9dc3e0f9f9) | Oct 04, 2023 |
| Valve         | Jupiter                     | [243f46cfa8](https://linux-hardware.org/?probe=243f46cfa8) | Sep 17, 2023 |
| Lenovo        | Flex 2-14 20404             | [139a93ab8b](https://linux-hardware.org/?probe=139a93ab8b) | Sep 09, 2023 |
| MSI           | P65 Creator 8RD             | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| Dell          | Vostro 3580                 | [5c165fd73b](https://linux-hardware.org/?probe=5c165fd73b) | Sep 06, 2023 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [dc7b90d27f](https://linux-hardware.org/?probe=dc7b90d27f) | Sep 01, 2023 |
| Chuwi         | CoreBook X                  | [c1a4e5d47f](https://linux-hardware.org/?probe=c1a4e5d47f) | Aug 30, 2023 |
| HP            | 255 G2                      | [23bf2dd515](https://linux-hardware.org/?probe=23bf2dd515) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [da73419cb5](https://linux-hardware.org/?probe=da73419cb5) | Aug 27, 2023 |
| Dell          | Inspiron 3593               | [1562efcaf2](https://linux-hardware.org/?probe=1562efcaf2) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [5d220003c1](https://linux-hardware.org/?probe=5d220003c1) | Aug 27, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [b2ad72336f](https://linux-hardware.org/?probe=b2ad72336f) | Aug 26, 2023 |
| Lenovo        | G560 0679                   | [71520ab551](https://linux-hardware.org/?probe=71520ab551) | Aug 22, 2023 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [3b1c4bacb9](https://linux-hardware.org/?probe=3b1c4bacb9) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [97ed27473e](https://linux-hardware.org/?probe=97ed27473e) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | [498c86055c](https://linux-hardware.org/?probe=498c86055c) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | [7a389ac976](https://linux-hardware.org/?probe=7a389ac976) | Aug 19, 2023 |
| Dell          | XPS 13 9343                 | [41bbf2a956](https://linux-hardware.org/?probe=41bbf2a956) | Aug 14, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [8ef1bbdcec](https://linux-hardware.org/?probe=8ef1bbdcec) | Aug 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d25ab08211](https://linux-hardware.org/?probe=d25ab08211) | Aug 12, 2023 |
| ASUSTek       | UL30A                       | [11f3b9cfad](https://linux-hardware.org/?probe=11f3b9cfad) | Aug 08, 2023 |
| HP            | Pavilion TS Sleekbook 15    | [8360dc045f](https://linux-hardware.org/?probe=8360dc045f) | Aug 06, 2023 |
| HP            | Pavilion TS Sleekbook 15    | [cad443cf78](https://linux-hardware.org/?probe=cad443cf78) | Aug 06, 2023 |
| Dell          | Latitude 5480               | [b682f988e8](https://linux-hardware.org/?probe=b682f988e8) | Aug 04, 2023 |
| Lenovo        | ThinkPad X280 20KES3D900    | [865dbfa247](https://linux-hardware.org/?probe=865dbfa247) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [da046587dc](https://linux-hardware.org/?probe=da046587dc) | Jul 25, 2023 |
| Valve         | Jupiter                     | [4172f7fd39](https://linux-hardware.org/?probe=4172f7fd39) | Jul 21, 2023 |
| HP            | EliteBook 745 G5            | [7b7cf50cba](https://linux-hardware.org/?probe=7b7cf50cba) | Jul 18, 2023 |
| Lenovo        | ThinkPad X240 20AMA04FIV    | [e16d9ae667](https://linux-hardware.org/?probe=e16d9ae667) | Jul 16, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [5ac5b565cd](https://linux-hardware.org/?probe=5ac5b565cd) | Jul 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f79821f2eb](https://linux-hardware.org/?probe=f79821f2eb) | Jul 09, 2023 |
| Dell          | Inspiron N5110              | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [f003f0aa32](https://linux-hardware.org/?probe=f003f0aa32) | Jul 06, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f3828ea18b](https://linux-hardware.org/?probe=f3828ea18b) | Jul 04, 2023 |
| Valve         | Jupiter                     | [a39f1dd1ad](https://linux-hardware.org/?probe=a39f1dd1ad) | Jul 04, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [7aed7e46ad](https://linux-hardware.org/?probe=7aed7e46ad) | Jul 03, 2023 |
| Valve         | Jupiter                     | [a4a8cc1e65](https://linux-hardware.org/?probe=a4a8cc1e65) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [4e40b350ca](https://linux-hardware.org/?probe=4e40b350ca) | Jun 28, 2023 |
| Dell          | Latitude 7420               | [d5cb3d4bfa](https://linux-hardware.org/?probe=d5cb3d4bfa) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L50-A         | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | [a2e5b66940](https://linux-hardware.org/?probe=a2e5b66940) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [6c260b1543](https://linux-hardware.org/?probe=6c260b1543) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7c906bbd1c](https://linux-hardware.org/?probe=7c906bbd1c) | Jun 20, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8e74890c4f](https://linux-hardware.org/?probe=8e74890c4f) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [98f052ad58](https://linux-hardware.org/?probe=98f052ad58) | Jun 19, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [65385cc189](https://linux-hardware.org/?probe=65385cc189) | Jun 19, 2023 |
| Framework     | Laptop                      | [7d010a367e](https://linux-hardware.org/?probe=7d010a367e) | Jun 19, 2023 |
| Razer         | Blade Stealth               | [f218e04a1c](https://linux-hardware.org/?probe=f218e04a1c) | Jun 14, 2023 |
| Google        | Atlas                       | [ecd53b626a](https://linux-hardware.org/?probe=ecd53b626a) | Jun 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [d183d47822](https://linux-hardware.org/?probe=d183d47822) | Jun 12, 2023 |
| Dell          | Latitude 7440               | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [9e3dfb25be](https://linux-hardware.org/?probe=9e3dfb25be) | Jun 09, 2023 |
| Lenovo        | ThinkPad P51 20HH0011US     | [4766608bc1](https://linux-hardware.org/?probe=4766608bc1) | Jun 06, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [bb29d15c61](https://linux-hardware.org/?probe=bb29d15c61) | Jun 05, 2023 |
| Acer          | Aspire A115-31              | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [9cba800830](https://linux-hardware.org/?probe=9cba800830) | May 26, 2023 |
| Dell          | Vostro 5402                 | [00e3bf6a3e](https://linux-hardware.org/?probe=00e3bf6a3e) | May 17, 2023 |
| Dell          | Latitude 5401               | [4304efbed6](https://linux-hardware.org/?probe=4304efbed6) | May 15, 2023 |
| Valve         | Jupiter                     | [0b26ce1a71](https://linux-hardware.org/?probe=0b26ce1a71) | May 12, 2023 |
| Dell          | Latitude E5530 non-vPro     | [c821704a04](https://linux-hardware.org/?probe=c821704a04) | May 10, 2023 |
| Apple         | MacBookPro11,3              | [9bd04974e8](https://linux-hardware.org/?probe=9bd04974e8) | May 09, 2023 |
| Razer         | Blade                       | [d90bda8f52](https://linux-hardware.org/?probe=d90bda8f52) | May 07, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [b577b4aa25](https://linux-hardware.org/?probe=b577b4aa25) | May 06, 2023 |
| Apple         | MacBook10,1                 | [b951048d8f](https://linux-hardware.org/?probe=b951048d8f) | May 05, 2023 |
| Apple         | MacBook10,1                 | [6796aa4cf0](https://linux-hardware.org/?probe=6796aa4cf0) | May 05, 2023 |
| Acer          | Aspire one                  | [90d59ac61a](https://linux-hardware.org/?probe=90d59ac61a) | May 04, 2023 |
| Acer          | Aspire one                  | [aeabc8c63c](https://linux-hardware.org/?probe=aeabc8c63c) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [18de5959b7](https://linux-hardware.org/?probe=18de5959b7) | May 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d8af950fd8](https://linux-hardware.org/?probe=d8af950fd8) | Apr 28, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [854cf327d8](https://linux-hardware.org/?probe=854cf327d8) | Apr 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d805c85a12](https://linux-hardware.org/?probe=d805c85a12) | Apr 24, 2023 |
| Lenovo        | ThinkPad T410 2522WZN       | [0baff3522f](https://linux-hardware.org/?probe=0baff3522f) | Apr 15, 2023 |
| Valve         | Jupiter                     | [56768ba5a6](https://linux-hardware.org/?probe=56768ba5a6) | Apr 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | [5a17f65715](https://linux-hardware.org/?probe=5a17f65715) | Apr 14, 2023 |
| Dell          | Latitude 5491               | [ef97e6890a](https://linux-hardware.org/?probe=ef97e6890a) | Apr 13, 2023 |
| Acer          | Aspire 5755G                | [917791ff47](https://linux-hardware.org/?probe=917791ff47) | Apr 12, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [e9790ea3b6](https://linux-hardware.org/?probe=e9790ea3b6) | Apr 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fc28f6d3f0](https://linux-hardware.org/?probe=fc28f6d3f0) | Apr 08, 2023 |
| HP            | ZBook 15 G5                 | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| Acer          | Aspire 5820                 | [3e0e45bc17](https://linux-hardware.org/?probe=3e0e45bc17) | Mar 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| Gigabyte      | AORUS 17G XC                | [fb998b9957](https://linux-hardware.org/?probe=fb998b9957) | Mar 12, 2023 |
| Acer          | Aspire A715-72G             | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| Timi          | RedmiBook 16                | [2d713931d2](https://linux-hardware.org/?probe=2d713931d2) | Feb 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| HP            | Pavilion TS 14              | [37296c42c3](https://linux-hardware.org/?probe=37296c42c3) | Feb 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [323b6463a9](https://linux-hardware.org/?probe=323b6463a9) | Feb 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Alienware     | 15 R2                       | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| HP            | Laptop 15-ef2xxx            | [6f8fadfe19](https://linux-hardware.org/?probe=6f8fadfe19) | Feb 15, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [26ea96167c](https://linux-hardware.org/?probe=26ea96167c) | Feb 12, 2023 |
| Dell          | Vostro 3558                 | [bb53ff2532](https://linux-hardware.org/?probe=bb53ff2532) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [ab928273ba](https://linux-hardware.org/?probe=ab928273ba) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [5995e0b36b](https://linux-hardware.org/?probe=5995e0b36b) | Feb 11, 2023 |
| Heptagon S... | HQ-BOX2 Server              | [476197a287](https://linux-hardware.org/?probe=476197a287) | Feb 09, 2023 |
| Lenovo        | V14-IIL 82C4                | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| HUAWEI        | HN-WX9X                     | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK U554               | [22bf4111de](https://linux-hardware.org/?probe=22bf4111de) | Jan 23, 2023 |
| Acer          | TravelMate P257-M           | [1345fa56c4](https://linux-hardware.org/?probe=1345fa56c4) | Jan 22, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Dell          | Vostro 14 5401              | [b56e81d82d](https://linux-hardware.org/?probe=b56e81d82d) | Jan 11, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [3965f2f9f4](https://linux-hardware.org/?probe=3965f2f9f4) | Jan 11, 2023 |
| Dell          | XPS 15 9550                 | [abe344877a](https://linux-hardware.org/?probe=abe344877a) | Jan 09, 2023 |
| Dell          | XPS 15 9550                 | [6a5da8e502](https://linux-hardware.org/?probe=6a5da8e502) | Jan 08, 2023 |
| Apple         | MacBookPro10,1              | [874b25fc88](https://linux-hardware.org/?probe=874b25fc88) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Apple         | MacBookPro8,1               | [4641833cab](https://linux-hardware.org/?probe=4641833cab) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Lenovo        | V14-IIL 82C4                | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Dell          | Vostro 15 5510              | [10f4ac5e13](https://linux-hardware.org/?probe=10f4ac5e13) | Dec 24, 2022 |
| Dell          | XPS 15 9520                 | [b9b1f8140b](https://linux-hardware.org/?probe=b9b1f8140b) | Dec 18, 2022 |
| MSI           | Summit E16FlipEvo A12MT     | [426289da4e](https://linux-hardware.org/?probe=426289da4e) | Dec 11, 2022 |
| Dell          | Latitude E6420              | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [dc13dde66a](https://linux-hardware.org/?probe=dc13dde66a) | Nov 29, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Dell          | Inspiron 1545               | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| Dell          | Inspiron 1545               | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| Dell          | Vostro 3300                 | [ae100dd7e2](https://linux-hardware.org/?probe=ae100dd7e2) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| ASUSTek       | UX430UNR                    | [f04bf95806](https://linux-hardware.org/?probe=f04bf95806) | Nov 08, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| HP            | Laptop 15-dw2xxx            | [66b04ff6f8](https://linux-hardware.org/?probe=66b04ff6f8) | Oct 20, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [989fe39fa7](https://linux-hardware.org/?probe=989fe39fa7) | Oct 10, 2022 |
| Dell          | Inspiron 5559               | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| HP            | ProBook 430 G6              | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [bc43cff31b](https://linux-hardware.org/?probe=bc43cff31b) | Sep 23, 2022 |
| Dell          | Inspiron 1545               | [cc3af3e194](https://linux-hardware.org/?probe=cc3af3e194) | Sep 16, 2022 |
| Dell          | Inspiron 1545               | [598341495c](https://linux-hardware.org/?probe=598341495c) | Sep 16, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Acer          | Aspire 5820                 | [1820ffa037](https://linux-hardware.org/?probe=1820ffa037) | Sep 09, 2022 |
| Acer          | Aspire 5820                 | [3f0d8d8ff5](https://linux-hardware.org/?probe=3f0d8d8ff5) | Sep 09, 2022 |
| Dell          | Latitude E4300              | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
| Apple         | MacBookPro8,1               | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| ASUSTek       | G75VX                       | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Dell          | XPS 15 7590                 | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| Lenovo        | G50-80 80L0                 | [eb58813044](https://linux-hardware.org/?probe=eb58813044) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Lenovo        | 3000 G530 4151/200          | [8e9bf5b1f9](https://linux-hardware.org/?probe=8e9bf5b1f9) | Aug 03, 2022 |
| Dell          | G7 7500                     | [f5e6475121](https://linux-hardware.org/?probe=f5e6475121) | Jul 22, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [8f556b89fc](https://linux-hardware.org/?probe=8f556b89fc) | Jul 16, 2022 |
| ASUSTek       | G53JW                       | [2090800f5c](https://linux-hardware.org/?probe=2090800f5c) | Jul 06, 2022 |
| HP            | ProBook 430 G6              | [4281fab7fd](https://linux-hardware.org/?probe=4281fab7fd) | Jul 05, 2022 |
| HP            | Mini 210-1100               | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| Dell          | Latitude 7300               | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [755c2fc534](https://linux-hardware.org/?probe=755c2fc534) | Jun 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| Purism        | Librem 14                   | [89d920a7d2](https://linux-hardware.org/?probe=89d920a7d2) | Jun 11, 2022 |
| Dell          | XPS 15 9570                 | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| Lenovo        | Unknown                     | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1c8e5b49d3](https://linux-hardware.org/?probe=1c8e5b49d3) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [00d3a71a00](https://linux-hardware.org/?probe=00d3a71a00) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| ASUSTek       | N550JV                      | [37af34e2e7](https://linux-hardware.org/?probe=37af34e2e7) | May 31, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| ASUSTek       | N550JV                      | [7b3acdb5ac](https://linux-hardware.org/?probe=7b3acdb5ac) | May 23, 2022 |
| ASUSTek       | N550JV                      | [286611f4de](https://linux-hardware.org/?probe=286611f4de) | May 20, 2022 |
| Dell          | Inspiron 5577               | [d14ee897f2](https://linux-hardware.org/?probe=d14ee897f2) | May 17, 2022 |
| Lenovo        | V14-IIL 82C4                | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| Dell          | Latitude 5421               | [3b2e352ea9](https://linux-hardware.org/?probe=3b2e352ea9) | May 11, 2022 |
| Dell          | Latitude 5421               | [105382c79b](https://linux-hardware.org/?probe=105382c79b) | May 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [f48ef1adaf](https://linux-hardware.org/?probe=f48ef1adaf) | May 09, 2022 |
| Dell          | Vostro 5402                 | [ff11e148fd](https://linux-hardware.org/?probe=ff11e148fd) | May 04, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a7fe3cb0f6](https://linux-hardware.org/?probe=a7fe3cb0f6) | Apr 30, 2022 |
| Dell          | Latitude 7400               | [7f20623ac0](https://linux-hardware.org/?probe=7f20623ac0) | Apr 28, 2022 |
| ASUSTek       | UX32VD                      | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Acer          | Aspire V7-482PG             | [40eb526de9](https://linux-hardware.org/?probe=40eb526de9) | Apr 18, 2022 |
| Acer          | Aspire 5755G                | [e13fc569ce](https://linux-hardware.org/?probe=e13fc569ce) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| HP            | 250 G4 Notebook PC          | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| Dell          | XPS 15 9570                 | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| Acer          | Aspire 5820                 | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| ASUSTek       | N550JV                      | [0d64cbab8e](https://linux-hardware.org/?probe=0d64cbab8e) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Dell          | Latitude 5411               | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [376b49560d](https://linux-hardware.org/?probe=376b49560d) | Feb 28, 2022 |
| Dell          | Studio 1555                 | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| ASUSTek       | S400CA                      | [56c75c35b6](https://linux-hardware.org/?probe=56c75c35b6) | Feb 19, 2022 |
| Dell          | Latitude E6330              | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [331b62c0e9](https://linux-hardware.org/?probe=331b62c0e9) | Feb 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| Dell          | Inspiron 3542               | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Dell          | Latitude 3350               | [682af42b93](https://linux-hardware.org/?probe=682af42b93) | Jan 18, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [8ab84f13d3](https://linux-hardware.org/?probe=8ab84f13d3) | Jan 14, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [50669a06d2](https://linux-hardware.org/?probe=50669a06d2) | Jan 14, 2022 |
| Lenovo        | V14-IIL 82C4                | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Dell          | Vostro 3560                 | [ffc754462f](https://linux-hardware.org/?probe=ffc754462f) | Dec 30, 2021 |
| Dell          | Vostro 3560                 | [cd630222d7](https://linux-hardware.org/?probe=cd630222d7) | Dec 30, 2021 |
| Acer          | Aspire 5755G                | [14f60e1eef](https://linux-hardware.org/?probe=14f60e1eef) | Dec 28, 2021 |
| Lenovo        | V14-IIL 82C4                | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | 240 G6 Notebook PC          | [0eee85762e](https://linux-hardware.org/?probe=0eee85762e) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | [f986757d36](https://linux-hardware.org/?probe=f986757d36) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | [8462457866](https://linux-hardware.org/?probe=8462457866) | Dec 14, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [df4d55c39b](https://linux-hardware.org/?probe=df4d55c39b) | Nov 26, 2021 |
| ASUSTek       | UX331UA                     | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [540612a510](https://linux-hardware.org/?probe=540612a510) | Nov 23, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ba96dd251c](https://linux-hardware.org/?probe=ba96dd251c) | Nov 17, 2021 |
| Dell          | Inspiron 3581               | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| ASUSTek       | BU403UAV                    | [cb7fcf5c15](https://linux-hardware.org/?probe=cb7fcf5c15) | Nov 15, 2021 |
| ASUSTek       | GL502VMK                    | [78bc4b00c0](https://linux-hardware.org/?probe=78bc4b00c0) | Nov 12, 2021 |
| Dell          | XPS 15 9510                 | [b95625ab23](https://linux-hardware.org/?probe=b95625ab23) | Nov 10, 2021 |
| Dell          | Latitude 5410               | [35fd3a8949](https://linux-hardware.org/?probe=35fd3a8949) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [c5e111be13](https://linux-hardware.org/?probe=c5e111be13) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [6cc81555db](https://linux-hardware.org/?probe=6cc81555db) | Nov 04, 2021 |
| Dell          | System Inspiron N7110       | [3f5d6aaab8](https://linux-hardware.org/?probe=3f5d6aaab8) | Oct 26, 2021 |
| Lenovo        | G40-70 20369                | [c8606a3a2a](https://linux-hardware.org/?probe=c8606a3a2a) | Oct 20, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [b8d00b123f](https://linux-hardware.org/?probe=b8d00b123f) | Oct 16, 2021 |
| Dell          | Inspiron 3593               | [28136dcca0](https://linux-hardware.org/?probe=28136dcca0) | Oct 13, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [267712392b](https://linux-hardware.org/?probe=267712392b) | Oct 11, 2021 |
| Notebook      | N2x0WU                      | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Dell          | Inspiron 3521               | [3e85c5d96f](https://linux-hardware.org/?probe=3e85c5d96f) | Sep 27, 2021 |
| Dell          | Latitude 5420               | [a31b3507c4](https://linux-hardware.org/?probe=a31b3507c4) | Sep 26, 2021 |
| Dell          | Latitude 5420               | [a077664ed2](https://linux-hardware.org/?probe=a077664ed2) | Sep 26, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [ab36263477](https://linux-hardware.org/?probe=ab36263477) | Sep 25, 2021 |
| Lenovo        | G40-70 20369                | [e79a9eb09d](https://linux-hardware.org/?probe=e79a9eb09d) | Sep 22, 2021 |
| Lenovo        | G50-80 80L0                 | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Dell          | Vostro 7590                 | [8f4e694845](https://linux-hardware.org/?probe=8f4e694845) | Sep 10, 2021 |
| Lenovo        | G50-80 80L0                 | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ProBook 4520s               | [4f947f1b22](https://linux-hardware.org/?probe=4f947f1b22) | Sep 06, 2021 |
| HP            | ProBook 4520s               | [fac0dbdf09](https://linux-hardware.org/?probe=fac0dbdf09) | Sep 06, 2021 |
| HP            | Spectre Notebook            | [6a3406a77f](https://linux-hardware.org/?probe=6a3406a77f) | Sep 02, 2021 |
| HP            | Spectre Notebook            | [9966ff0b8f](https://linux-hardware.org/?probe=9966ff0b8f) | Sep 02, 2021 |
| Apple         | MacBookPro12,1              | [79010f7e30](https://linux-hardware.org/?probe=79010f7e30) | Aug 31, 2021 |
| HP            | Compaq Presario CQ61        | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [17afc04962](https://linux-hardware.org/?probe=17afc04962) | Aug 16, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [0ca5c5faa2](https://linux-hardware.org/?probe=0ca5c5faa2) | Aug 11, 2021 |
| IP3 Tech      | AP1                         | [b27a94c64c](https://linux-hardware.org/?probe=b27a94c64c) | Aug 08, 2021 |
| Dell          | Latitude 5410               | [4f2e0ccb9f](https://linux-hardware.org/?probe=4f2e0ccb9f) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [37cbdcae11](https://linux-hardware.org/?probe=37cbdcae11) | Aug 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| Dell          | Latitude 5410               | [73c46f7a65](https://linux-hardware.org/?probe=73c46f7a65) | Aug 01, 2021 |
| Dell          | Latitude 5410               | [8357a0ce64](https://linux-hardware.org/?probe=8357a0ce64) | Aug 01, 2021 |
| HP            | Unknown                     | [f048334d4b](https://linux-hardware.org/?probe=f048334d4b) | Jul 21, 2021 |
| Dell          | Latitude E4300              | [3310bfe342](https://linux-hardware.org/?probe=3310bfe342) | Jul 20, 2021 |
| Apple         | MacBookAir4,2               | [d479a6fd61](https://linux-hardware.org/?probe=d479a6fd61) | Jun 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [13ed380099](https://linux-hardware.org/?probe=13ed380099) | Jun 24, 2021 |
| HP            | Notebook                    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [79f64eaadf](https://linux-hardware.org/?probe=79f64eaadf) | Jun 19, 2021 |
| HP            | Notebook                    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| Dell          | Vostro 5590                 | [debb5f4ac5](https://linux-hardware.org/?probe=debb5f4ac5) | Jun 07, 2021 |
| Acer          | Aspire 4333                 | [9f3738469d](https://linux-hardware.org/?probe=9f3738469d) | May 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [6fe368312c](https://linux-hardware.org/?probe=6fe368312c) | May 15, 2021 |
| Lenovo        | G510 20238                  | [9497cc9d85](https://linux-hardware.org/?probe=9497cc9d85) | May 15, 2021 |
| Dell          | Latitude E4300              | [7ed9015fd5](https://linux-hardware.org/?probe=7ed9015fd5) | May 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [ab559fd00d](https://linux-hardware.org/?probe=ab559fd00d) | May 09, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8bf60ca353](https://linux-hardware.org/?probe=8bf60ca353) | May 08, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c72aec456a](https://linux-hardware.org/?probe=c72aec456a) | May 06, 2021 |
| LG Electro... | 15Z980-A.AAS8U1             | [2a68dcd848](https://linux-hardware.org/?probe=2a68dcd848) | May 03, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [ca15c642d7](https://linux-hardware.org/?probe=ca15c642d7) | Apr 08, 2021 |
| Dell          | Inspiron 5755               | [fefe0c7d71](https://linux-hardware.org/?probe=fefe0c7d71) | Apr 01, 2021 |
| Dell          | Inspiron 3593               | [4cc755d1c2](https://linux-hardware.org/?probe=4cc755d1c2) | Mar 25, 2021 |
| HP            | Compaq Presario CQ61        | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Dell          | XPS 13 9370                 | [f71120521c](https://linux-hardware.org/?probe=f71120521c) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [edf6ab636e](https://linux-hardware.org/?probe=edf6ab636e) | Mar 19, 2021 |
| HP            | ZBook 15 G3                 | [fa7b8613f2](https://linux-hardware.org/?probe=fa7b8613f2) | Mar 16, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ff15d5b8ad](https://linux-hardware.org/?probe=ff15d5b8ad) | Mar 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a50f9abd26](https://linux-hardware.org/?probe=a50f9abd26) | Mar 11, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [77a787d158](https://linux-hardware.org/?probe=77a787d158) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a55964d5d9](https://linux-hardware.org/?probe=a55964d5d9) | Mar 06, 2021 |
| Lenovo        | G50-80 80E5                 | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HUAWEI        | HN-WX9X                     | [fb3d2fc3e9](https://linux-hardware.org/?probe=fb3d2fc3e9) | Mar 03, 2021 |
| HP            | ZBook 15 G6                 | [061392ad81](https://linux-hardware.org/?probe=061392ad81) | Mar 01, 2021 |
| ASUSTek       | GL503VD                     | [d03b00803b](https://linux-hardware.org/?probe=d03b00803b) | Feb 27, 2021 |
| Apple         | MacBookPro9,2               | [618d47c042](https://linux-hardware.org/?probe=618d47c042) | Feb 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2fff8b3674](https://linux-hardware.org/?probe=2fff8b3674) | Feb 24, 2021 |
| HUAWEI        | HN-WX9X                     | [2b4a74a520](https://linux-hardware.org/?probe=2b4a74a520) | Feb 16, 2021 |
| HUAWEI        | HN-WX9X                     | [f4c77fc7dc](https://linux-hardware.org/?probe=f4c77fc7dc) | Feb 16, 2021 |
| HP            | Compaq Presario CQ61        | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [a2ab510560](https://linux-hardware.org/?probe=a2ab510560) | Feb 14, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8711f89b6b](https://linux-hardware.org/?probe=8711f89b6b) | Feb 13, 2021 |
| HP            | Compaq Presario CQ61        | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [655d6c5817](https://linux-hardware.org/?probe=655d6c5817) | Feb 06, 2021 |
| Lenovo        | ThinkPad T580 20L9001YIV    | [799c676c40](https://linux-hardware.org/?probe=799c676c40) | Feb 04, 2021 |
| Lenovo        | ThinkPad E550 20DF004RIV    | [23140cf3f9](https://linux-hardware.org/?probe=23140cf3f9) | Jan 29, 2021 |
| Lenovo        | G40-70 20369                | [1763668816](https://linux-hardware.org/?probe=1763668816) | Jan 29, 2021 |
| Dell          | Latitude E6420              | [9aa53da922](https://linux-hardware.org/?probe=9aa53da922) | Jan 19, 2021 |
| Dell          | Latitude E6420              | [20a4b3769d](https://linux-hardware.org/?probe=20a4b3769d) | Jan 19, 2021 |
| Dell          | XPS 13 9370                 | [4df2203870](https://linux-hardware.org/?probe=4df2203870) | Jan 19, 2021 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [65724a4aa6](https://linux-hardware.org/?probe=65724a4aa6) | Jan 18, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [1883634f7b](https://linux-hardware.org/?probe=1883634f7b) | Jan 18, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [23a9e9c5f6](https://linux-hardware.org/?probe=23a9e9c5f6) | Jan 17, 2021 |
| HP            | Pavilion Notebook           | [750413cc61](https://linux-hardware.org/?probe=750413cc61) | Jan 16, 2021 |
| HP            | EliteBook 840 G5            | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Dell          | Inspiron 13-5378            | [94b70d7578](https://linux-hardware.org/?probe=94b70d7578) | Jan 12, 2021 |
| HP            | Pavilion Notebook           | [c1eeffc9d8](https://linux-hardware.org/?probe=c1eeffc9d8) | Jan 08, 2021 |
| Dell          | Inspiron 5567               | [0d62d918c5](https://linux-hardware.org/?probe=0d62d918c5) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | [5a3a67e5c3](https://linux-hardware.org/?probe=5a3a67e5c3) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | [f37800ed52](https://linux-hardware.org/?probe=f37800ed52) | Jan 07, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [b8bab31c57](https://linux-hardware.org/?probe=b8bab31c57) | Jan 06, 2021 |
| Dell          | Inspiron 13-5378            | [d55bf78096](https://linux-hardware.org/?probe=d55bf78096) | Jan 06, 2021 |
| Unknown       | Unknown                     | [b364724e53](https://linux-hardware.org/?probe=b364724e53) | Jan 02, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8d338ea73c](https://linux-hardware.org/?probe=8d338ea73c) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [ef84edb346](https://linux-hardware.org/?probe=ef84edb346) | Dec 31, 2020 |
| HP            | EliteBook 2570p             | [2ed921327b](https://linux-hardware.org/?probe=2ed921327b) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [9448ec4439](https://linux-hardware.org/?probe=9448ec4439) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [7cd92f4564](https://linux-hardware.org/?probe=7cd92f4564) | Dec 30, 2020 |
| Unknown       | Unknown                     | [749c45e229](https://linux-hardware.org/?probe=749c45e229) | Dec 29, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [01024cf86e](https://linux-hardware.org/?probe=01024cf86e) | Dec 27, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [66fd37cef4](https://linux-hardware.org/?probe=66fd37cef4) | Dec 27, 2020 |
| Dell          | Inspiron 3542               | [c79668f190](https://linux-hardware.org/?probe=c79668f190) | Dec 24, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [56b69fe95e](https://linux-hardware.org/?probe=56b69fe95e) | Dec 23, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [ddc1a4457d](https://linux-hardware.org/?probe=ddc1a4457d) | Dec 22, 2020 |
| HP            | Pavilion g6                 | [8d41f37972](https://linux-hardware.org/?probe=8d41f37972) | Dec 18, 2020 |
| Unknown       | Unknown                     | [e42b0f86e0](https://linux-hardware.org/?probe=e42b0f86e0) | Dec 14, 2020 |
| HUAWEI        | HN-WX9X                     | [5c1982b26c](https://linux-hardware.org/?probe=5c1982b26c) | Dec 08, 2020 |
| HUAWEI        | HN-WX9X                     | [5b58c4ff46](https://linux-hardware.org/?probe=5b58c4ff46) | Dec 08, 2020 |
| HP            | Laptop 15-da1xxx            | [df5f3d5a4d](https://linux-hardware.org/?probe=df5f3d5a4d) | Dec 07, 2020 |
| Dell          | XPS 13 9370                 | [4cbbe5b21a](https://linux-hardware.org/?probe=4cbbe5b21a) | Nov 26, 2020 |
| Lenovo        | Unknown                     | [40c892a262](https://linux-hardware.org/?probe=40c892a262) | Nov 26, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [46d30ce200](https://linux-hardware.org/?probe=46d30ce200) | Nov 20, 2020 |
| Toshiba       | Satellite L755              | [a6e2af6e5b](https://linux-hardware.org/?probe=a6e2af6e5b) | Nov 18, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2f9457bf32](https://linux-hardware.org/?probe=2f9457bf32) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f2e24821f4](https://linux-hardware.org/?probe=f2e24821f4) | Nov 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [e13999e22a](https://linux-hardware.org/?probe=e13999e22a) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | [e04b97eabe](https://linux-hardware.org/?probe=e04b97eabe) | Nov 11, 2020 |
| Acer          | Aspire A715-72G             | [90ef23a01c](https://linux-hardware.org/?probe=90ef23a01c) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | [4572167747](https://linux-hardware.org/?probe=4572167747) | Nov 10, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [21105809e4](https://linux-hardware.org/?probe=21105809e4) | Nov 08, 2020 |
| Lenovo        | Yoga 3 11 80J8              | [b4f083536f](https://linux-hardware.org/?probe=b4f083536f) | Nov 04, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [b94cef8d24](https://linux-hardware.org/?probe=b94cef8d24) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [c872f1d76f](https://linux-hardware.org/?probe=c872f1d76f) | Nov 03, 2020 |
| Dell          | Latitude E6330              | [f7e530a8c2](https://linux-hardware.org/?probe=f7e530a8c2) | Nov 02, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e8426a064f](https://linux-hardware.org/?probe=e8426a064f) | Nov 01, 2020 |
| Lenovo        | ThinkPad E480 20KN0062IV    | [fba2fb0e45](https://linux-hardware.org/?probe=fba2fb0e45) | Oct 30, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [1a691f72dc](https://linux-hardware.org/?probe=1a691f72dc) | Oct 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [990f9bb22f](https://linux-hardware.org/?probe=990f9bb22f) | Oct 29, 2020 |
| Dell          | Latitude 7490               | [2d61d426d5](https://linux-hardware.org/?probe=2d61d426d5) | Oct 28, 2020 |
| Dell          | Latitude 7300               | [ebf99bafc8](https://linux-hardware.org/?probe=ebf99bafc8) | Oct 27, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [36d289ce92](https://linux-hardware.org/?probe=36d289ce92) | Oct 20, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [e360fd1fa2](https://linux-hardware.org/?probe=e360fd1fa2) | Oct 18, 2020 |
| Dell          | Vostro 14 5401              | [89826d13da](https://linux-hardware.org/?probe=89826d13da) | Oct 13, 2020 |
| ASUSTek       | UX430UNR                    | [03dd6f184c](https://linux-hardware.org/?probe=03dd6f184c) | Oct 12, 2020 |
| Dell          | Vostro 14 5401              | [d3f66acd1b](https://linux-hardware.org/?probe=d3f66acd1b) | Oct 12, 2020 |
| HP            | Laptop 15-bs1xx             | [cab83dd9ff](https://linux-hardware.org/?probe=cab83dd9ff) | Oct 12, 2020 |
| Dell          | Vostro 5490                 | [b998e489c5](https://linux-hardware.org/?probe=b998e489c5) | Oct 07, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [a9d940dd83](https://linux-hardware.org/?probe=a9d940dd83) | Oct 04, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [c7e2a6001a](https://linux-hardware.org/?probe=c7e2a6001a) | Oct 04, 2020 |
| Dell          | Latitude 7400               | [6eac6cfa15](https://linux-hardware.org/?probe=6eac6cfa15) | Oct 04, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c4d11b04b5](https://linux-hardware.org/?probe=c4d11b04b5) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [b8c1686e69](https://linux-hardware.org/?probe=b8c1686e69) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [33801ffba1](https://linux-hardware.org/?probe=33801ffba1) | Sep 28, 2020 |
| Lenovo        | ThinkPad E14 20RA0036IV     | [d53e57ac10](https://linux-hardware.org/?probe=d53e57ac10) | Sep 25, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [9b2604c2e1](https://linux-hardware.org/?probe=9b2604c2e1) | Sep 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f8631e5f4a](https://linux-hardware.org/?probe=f8631e5f4a) | Sep 03, 2020 |
| Dell          | Latitude E5270              | [745e05ba12](https://linux-hardware.org/?probe=745e05ba12) | Aug 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [eee9972fdf](https://linux-hardware.org/?probe=eee9972fdf) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [cb7fda5c3f](https://linux-hardware.org/?probe=cb7fda5c3f) | Aug 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [99c5924655](https://linux-hardware.org/?probe=99c5924655) | Aug 23, 2020 |
| Lenovo        | ThinkPad L390 20NR001LIV    | [9fef5634b2](https://linux-hardware.org/?probe=9fef5634b2) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee5213ce49](https://linux-hardware.org/?probe=ee5213ce49) | Aug 19, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | [5f1ce912be](https://linux-hardware.org/?probe=5f1ce912be) | Aug 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [635a148f20](https://linux-hardware.org/?probe=635a148f20) | Aug 19, 2020 |
| Toshiba       | Satellite P50t-B-10T        | [0f41a5b6ec](https://linux-hardware.org/?probe=0f41a5b6ec) | Aug 13, 2020 |
| Lenovo        | ThinkPad T490 20N20073IV    | [3878e27014](https://linux-hardware.org/?probe=3878e27014) | Aug 10, 2020 |
| Dell          | Latitude 7390 2-in-1        | [fb785080a3](https://linux-hardware.org/?probe=fb785080a3) | Aug 02, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [38442a922b](https://linux-hardware.org/?probe=38442a922b) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | [e934fab850](https://linux-hardware.org/?probe=e934fab850) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | [38feef34d4](https://linux-hardware.org/?probe=38feef34d4) | Aug 01, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ef4f365d92](https://linux-hardware.org/?probe=ef4f365d92) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6126a00ffc](https://linux-hardware.org/?probe=6126a00ffc) | Jul 24, 2020 |
| Dell          | Latitude E6530              | [6e1b2fb388](https://linux-hardware.org/?probe=6e1b2fb388) | Jul 24, 2020 |
| Lenovo        | V510-15IKB 80WQ             | [3944aa1028](https://linux-hardware.org/?probe=3944aa1028) | Jul 20, 2020 |
| HP            | ProBook 640 G2              | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [6e6f80378d](https://linux-hardware.org/?probe=6e6f80378d) | Jul 11, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | [d0aacf7693](https://linux-hardware.org/?probe=d0aacf7693) | Jul 09, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | [868953dc99](https://linux-hardware.org/?probe=868953dc99) | Jul 09, 2020 |
| Dell          | Latitude 5400               | [ae1c2d9825](https://linux-hardware.org/?probe=ae1c2d9825) | Jul 08, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [52fad4367c](https://linux-hardware.org/?probe=52fad4367c) | Jul 01, 2020 |
| HP            | Pavilion dv6                | [39df31f4c6](https://linux-hardware.org/?probe=39df31f4c6) | Jun 27, 2020 |
| Lenovo        | ThinkPad E14 20RA0016IV     | [2878e88064](https://linux-hardware.org/?probe=2878e88064) | Jun 24, 2020 |
| HP            | Pavilion Notebook           | [866c72927a](https://linux-hardware.org/?probe=866c72927a) | Jun 22, 2020 |
| Dell          | Inspiron 5379               | [f7fe8744d9](https://linux-hardware.org/?probe=f7fe8744d9) | Jun 21, 2020 |
| ASUSTek       | UX331UA                     | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| HP            | EliteBook 840 G5            | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| ASUSTek       | UX331UA                     | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [1ce6e06069](https://linux-hardware.org/?probe=1ce6e06069) | May 30, 2020 |
| Dell          | Latitude 5490               | [2afe6adf1b](https://linux-hardware.org/?probe=2afe6adf1b) | May 18, 2020 |
| Dell          | Latitude 5490               | [c2b1c12105](https://linux-hardware.org/?probe=c2b1c12105) | May 17, 2020 |
| ASUSTek       | UX331UA                     | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| HP            | EliteBook 840 G5            | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| HP            | G42                         | [6d45062a76](https://linux-hardware.org/?probe=6d45062a76) | May 14, 2020 |
| Lenovo        | ThinkPad X200 74587DU       | [ba354beaa9](https://linux-hardware.org/?probe=ba354beaa9) | May 10, 2020 |
| ASUSTek       | K54C                        | [c2656ceae6](https://linux-hardware.org/?probe=c2656ceae6) | May 07, 2020 |
| HP            | Pavilion Laptop 14-bf1xx    | [6f86c55589](https://linux-hardware.org/?probe=6f86c55589) | May 04, 2020 |
| Acer          | Swift SF314-54G             | [e93143c6fd](https://linux-hardware.org/?probe=e93143c6fd) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | [4cc7a86795](https://linux-hardware.org/?probe=4cc7a86795) | Apr 26, 2020 |
| Toshiba       | Satellite A200              | [d9a55aeca2](https://linux-hardware.org/?probe=d9a55aeca2) | Apr 25, 2020 |
| Toshiba       | Satellite A200              | [1e6ea00cd0](https://linux-hardware.org/?probe=1e6ea00cd0) | Apr 25, 2020 |
| ASUSTek       | UX331UA                     | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [2516b70573](https://linux-hardware.org/?probe=2516b70573) | Apr 23, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [cdcce3c09c](https://linux-hardware.org/?probe=cdcce3c09c) | Apr 23, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [434a4a46f9](https://linux-hardware.org/?probe=434a4a46f9) | Apr 19, 2020 |
| Dell          | XPS 13 9350                 | [d718b985ec](https://linux-hardware.org/?probe=d718b985ec) | Apr 18, 2020 |
| HP            | Pavilion Notebook           | [cd641ec5c7](https://linux-hardware.org/?probe=cd641ec5c7) | Apr 17, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [28e6c33fec](https://linux-hardware.org/?probe=28e6c33fec) | Apr 17, 2020 |
| HP            | Pavilion Notebook           | [7e17ce97e9](https://linux-hardware.org/?probe=7e17ce97e9) | Apr 17, 2020 |
| ASUSTek       | X550CA                      | [d23cc368bb](https://linux-hardware.org/?probe=d23cc368bb) | Apr 10, 2020 |
| Dell          | Latitude 5490               | [6759b030d2](https://linux-hardware.org/?probe=6759b030d2) | Apr 10, 2020 |
| Dell          | Latitude 7300               | [4c263fc2d0](https://linux-hardware.org/?probe=4c263fc2d0) | Apr 01, 2020 |
| HP            | ZBook 15 G3                 | [254c1f48da](https://linux-hardware.org/?probe=254c1f48da) | Mar 31, 2020 |
| Dell          | Latitude 5490               | [03873fa787](https://linux-hardware.org/?probe=03873fa787) | Mar 30, 2020 |
| Dell          | Latitude 5490               | [d71d69d129](https://linux-hardware.org/?probe=d71d69d129) | Mar 30, 2020 |
| HP            | EliteBook 840 G5            | [2aab729aee](https://linux-hardware.org/?probe=2aab729aee) | Mar 30, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [9c1238b041](https://linux-hardware.org/?probe=9c1238b041) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5765e1a9f](https://linux-hardware.org/?probe=b5765e1a9f) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3c36d4bdc9](https://linux-hardware.org/?probe=3c36d4bdc9) | Mar 21, 2020 |
| Lenovo        | ThinkPad T480 20L5A063CD    | [ccd24104da](https://linux-hardware.org/?probe=ccd24104da) | Mar 08, 2020 |
| Dell          | Inspiron N5110              | [d13a02aacb](https://linux-hardware.org/?probe=d13a02aacb) | Mar 08, 2020 |
| Dell          | Inspiron 7548               | [ebce14c87e](https://linux-hardware.org/?probe=ebce14c87e) | Feb 22, 2020 |
| Dell          | Inspiron 7548               | [d4b3df5729](https://linux-hardware.org/?probe=d4b3df5729) | Feb 22, 2020 |
| ASUSTek       | X201EP                      | [75d7523e83](https://linux-hardware.org/?probe=75d7523e83) | Feb 13, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [239b2eba6d](https://linux-hardware.org/?probe=239b2eba6d) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [a3e9ca6d37](https://linux-hardware.org/?probe=a3e9ca6d37) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [60ba0e3d0f](https://linux-hardware.org/?probe=60ba0e3d0f) | Feb 08, 2020 |
| Dell          | Inspiron 13-5378            | [30e38a1812](https://linux-hardware.org/?probe=30e38a1812) | Feb 03, 2020 |
| HP            | Laptop 15-da1xxx            | [b4ef2a52c5](https://linux-hardware.org/?probe=b4ef2a52c5) | Jan 21, 2020 |
| HP            | Laptop 15-da1xxx            | [33d23400b4](https://linux-hardware.org/?probe=33d23400b4) | Jan 20, 2020 |
| LG Electro... | 15Z990-A.AAS7U1             | [afd7d4caf9](https://linux-hardware.org/?probe=afd7d4caf9) | Jan 15, 2020 |
| Lenovo        | G570 4334                   | [7bf153f618](https://linux-hardware.org/?probe=7bf153f618) | Jan 13, 2020 |
| Lenovo        | ThinkPad E595 20NF0018US    | [00d8e5ba33](https://linux-hardware.org/?probe=00d8e5ba33) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | [a423e910c6](https://linux-hardware.org/?probe=a423e910c6) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | [84fcfb4be2](https://linux-hardware.org/?probe=84fcfb4be2) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | [903ab151c8](https://linux-hardware.org/?probe=903ab151c8) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | [495c89d842](https://linux-hardware.org/?probe=495c89d842) | Jan 07, 2020 |
| Dell          | Latitude E7270              | [83f77407ab](https://linux-hardware.org/?probe=83f77407ab) | Jan 06, 2020 |
| Dell          | Latitude E7270              | [dc87d2cdee](https://linux-hardware.org/?probe=dc87d2cdee) | Jan 06, 2020 |
| Dell          | Inspiron MM061              | [3da92e4cab](https://linux-hardware.org/?probe=3da92e4cab) | Jan 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [992e2074ff](https://linux-hardware.org/?probe=992e2074ff) | Dec 25, 2019 |
| ASUSTek       | UL30A                       | [b7f84b8da0](https://linux-hardware.org/?probe=b7f84b8da0) | Dec 20, 2019 |
| ASUSTek       | X501A                       | [ce99670ceb](https://linux-hardware.org/?probe=ce99670ceb) | Dec 20, 2019 |
| ASUSTek       | X501A                       | [f7a367e32c](https://linux-hardware.org/?probe=f7a367e32c) | Dec 20, 2019 |
| LG Electro... | A310                        | [d2599d1470](https://linux-hardware.org/?probe=d2599d1470) | Nov 26, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [52db21c094](https://linux-hardware.org/?probe=52db21c094) | Nov 24, 2019 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [831c001466](https://linux-hardware.org/?probe=831c001466) | Nov 23, 2019 |
| HP            | G7000                       | [cb550f69f7](https://linux-hardware.org/?probe=cb550f69f7) | Nov 12, 2019 |
| HP            | G7000                       | [97ada3d9cf](https://linux-hardware.org/?probe=97ada3d9cf) | Nov 12, 2019 |
| HP            | G7000                       | [ca985e708a](https://linux-hardware.org/?probe=ca985e708a) | Nov 12, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [39c33a8d85](https://linux-hardware.org/?probe=39c33a8d85) | Oct 21, 2019 |
| Samsung       | 3570R/370R/470R/450R/510... | [a5e61f3a1a](https://linux-hardware.org/?probe=a5e61f3a1a) | Oct 18, 2019 |
| Dell          | Latitude E6320              | [276041713d](https://linux-hardware.org/?probe=276041713d) | Oct 18, 2019 |
| Dell          | Latitude E6320              | [a2002798ac](https://linux-hardware.org/?probe=a2002798ac) | Oct 18, 2019 |
| Lenovo        | E31-80 80MX                 | [4f5d1ae105](https://linux-hardware.org/?probe=4f5d1ae105) | Oct 17, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6bc1a600ee](https://linux-hardware.org/?probe=6bc1a600ee) | Oct 06, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [32944602dd](https://linux-hardware.org/?probe=32944602dd) | Oct 06, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [60e8599708](https://linux-hardware.org/?probe=60e8599708) | Sep 30, 2019 |
| Lenovo        | G560 0679                   | [403cb2c831](https://linux-hardware.org/?probe=403cb2c831) | Sep 19, 2019 |
| Lenovo        | G560 0679                   | [0552d32d91](https://linux-hardware.org/?probe=0552d32d91) | Sep 18, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [77a3bc0e11](https://linux-hardware.org/?probe=77a3bc0e11) | Sep 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eeaadaa0a3](https://linux-hardware.org/?probe=eeaadaa0a3) | Sep 17, 2019 |
| HP            | EliteBook 840 G6            | [4ada1a54ef](https://linux-hardware.org/?probe=4ada1a54ef) | Sep 13, 2019 |
| Lenovo        | Yoga 500-14ISK 80R5         | [b4f1b9249a](https://linux-hardware.org/?probe=b4f1b9249a) | Sep 10, 2019 |
| Dell          | Latitude E7450              | [cb374fcaff](https://linux-hardware.org/?probe=cb374fcaff) | Sep 05, 2019 |
| Dell          | XPS 13 9343                 | [ecb0cffd7b](https://linux-hardware.org/?probe=ecb0cffd7b) | Sep 04, 2019 |
| ASUSTek       | X302UJ                      | [d467007887](https://linux-hardware.org/?probe=d467007887) | Aug 24, 2019 |
| Acer          | Aspire 5730                 | [6e8c846d9b](https://linux-hardware.org/?probe=6e8c846d9b) | Aug 24, 2019 |
| Dell          | Latitude E5470              | [d01c149d9c](https://linux-hardware.org/?probe=d01c149d9c) | Aug 17, 2019 |
| Dell          | Latitude E5470              | [b0b32067b9](https://linux-hardware.org/?probe=b0b32067b9) | Aug 17, 2019 |
| Dell          | Inspiron 13-5378            | [afa245a5c3](https://linux-hardware.org/?probe=afa245a5c3) | Aug 13, 2019 |
| HP            | 255 G5 Notebook PC          | [2043a9b3c9](https://linux-hardware.org/?probe=2043a9b3c9) | Jul 18, 2019 |
| ASUSTek       | K54C                        | [4a89c5d895](https://linux-hardware.org/?probe=4a89c5d895) | Jul 06, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [93c1102eae](https://linux-hardware.org/?probe=93c1102eae) | May 30, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [89e100d874](https://linux-hardware.org/?probe=89e100d874) | May 17, 2019 |
| HP            | Pavilion dv6500             | [b185023357](https://linux-hardware.org/?probe=b185023357) | May 13, 2019 |
| ASUSTek       | K54C                        | [653d157e1a](https://linux-hardware.org/?probe=653d157e1a) | May 04, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | [a803a8593b](https://linux-hardware.org/?probe=a803a8593b) | Apr 11, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | [6be3c466e0](https://linux-hardware.org/?probe=6be3c466e0) | Apr 10, 2019 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f49f4bf7e3](https://linux-hardware.org/?probe=f49f4bf7e3) | Mar 30, 2019 |
| Fujitsu Si... | AMILO Li 2727               | [606743f06e](https://linux-hardware.org/?probe=606743f06e) | Mar 22, 2019 |
| System76      | Gazelle                     | [03387dc427](https://linux-hardware.org/?probe=03387dc427) | Mar 12, 2019 |
| HP            | G70                         | [d4f5ef99c5](https://linux-hardware.org/?probe=d4f5ef99c5) | Feb 14, 2019 |
| ASUSTek       | S551LN                      | [572227fb77](https://linux-hardware.org/?probe=572227fb77) | Jan 19, 2019 |
| ASUSTek       | S551LN                      | [f624b3c2eb](https://linux-hardware.org/?probe=f624b3c2eb) | Jan 18, 2019 |
| ASUSTek       | S551LN                      | [084947886f](https://linux-hardware.org/?probe=084947886f) | Jan 03, 2019 |
| Timi          | TM1701                      | [19f0b77769](https://linux-hardware.org/?probe=19f0b77769) | Dec 21, 2018 |
| Timi          | TM1701                      | [e0c4ee1fcb](https://linux-hardware.org/?probe=e0c4ee1fcb) | Dec 21, 2018 |
| ASUSTek       | S551LN                      | [4fef5b511a](https://linux-hardware.org/?probe=4fef5b511a) | Dec 15, 2018 |
| ASUSTek       | S551LN                      | [735db3cd91](https://linux-hardware.org/?probe=735db3cd91) | Dec 14, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [120d843ed3](https://linux-hardware.org/?probe=120d843ed3) | Nov 07, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d21daddd24](https://linux-hardware.org/?probe=d21daddd24) | Nov 07, 2018 |
| ASUSTek       | 1001PXD                     | [00e7c9c5fc](https://linux-hardware.org/?probe=00e7c9c5fc) | Aug 18, 2018 |
| ASUSTek       | 1001PXD                     | [80227a12a8](https://linux-hardware.org/?probe=80227a12a8) | Aug 18, 2018 |
| Lenovo        | ThinkPad T60 2613CTO        | [35edbff8b9](https://linux-hardware.org/?probe=35edbff8b9) | Feb 25, 2018 |
| Samsung       | N248P                       | [2b7782d6cb](https://linux-hardware.org/?probe=2b7782d6cb) | Aug 10, 2017 |
| HP            | Unknown                     | [551457fd6d](https://linux-hardware.org/?probe=551457fd6d) | Jul 10, 2017 |
| Acer          | Aspire 7520                 | [9132eeefdd](https://linux-hardware.org/?probe=9132eeefdd) | Nov 21, 2016 |
| ASUSTek       | 1001PXD                     | [6de0cbb74c](https://linux-hardware.org/?probe=6de0cbb74c) | Oct 29, 2016 |
| ASUSTek       | 1001PXD                     | [439684c718](https://linux-hardware.org/?probe=439684c718) | Oct 29, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Israel/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 79        | 19.13%  |
| Ubuntu 18.04      | 30        | 7.26%   |
| Ubuntu 22.04      | 26        | 6.3%    |
| Fedora 38         | 11        | 2.66%   |
| Fedora 37         | 9         | 2.18%   |
| Fedora 35         | 8         | 1.94%   |
| Ubuntu 21.04      | 7         | 1.69%   |
| Manjaro           | 7         | 1.69%   |
| Pop!_OS 22.04     | 6         | 1.45%   |
| Fedora 36         | 6         | 1.45%   |
| Arch              | 6         | 1.45%   |
| Zorin 15          | 5         | 1.21%   |
| Ubuntu 23.04      | 5         | 1.21%   |
| ROSA R11          | 5         | 1.21%   |
| Pop!_OS 21.04     | 5         | 1.21%   |
| Linux Mint 21.1   | 5         | 1.21%   |
| Linux Mint 21     | 5         | 1.21%   |
| Linux Mint 20.1   | 5         | 1.21%   |
| Ubuntu 22.10      | 4         | 0.97%   |
| Ubuntu 19.10      | 4         | 0.97%   |
| ROSA R10          | 4         | 0.97%   |
| OpenMandriva 4.3  | 4         | 0.97%   |
| Linux Mint 20.3   | 4         | 0.97%   |
| Fedora 34         | 4         | 0.97%   |
| Fedora 33         | 4         | 0.97%   |
| Arch Rolling      | 4         | 0.97%   |
| Zorin 16          | 3         | 0.73%   |
| Xubuntu 22.04     | 3         | 0.73%   |
| Ubuntu 20.10      | 3         | 0.73%   |
| Ubuntu 19.04      | 3         | 0.73%   |
| Pop!_OS 21.10     | 3         | 0.73%   |
| Pop!_OS 20.10     | 3         | 0.73%   |
| Manjaro 20.2      | 3         | 0.73%   |
| Linux Mint 20     | 3         | 0.73%   |
| Fedora 32         | 3         | 0.73%   |
| Debian 12         | 3         | 0.73%   |
| Debian 11         | 3         | 0.73%   |
| ArcoLinux Rolling | 3         | 0.73%   |
| Xubuntu 20.04     | 2         | 0.48%   |
| Xubuntu 18.04     | 2         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 159       | 41.84%  |
| Fedora        | 40        | 10.53%  |
| Linux Mint    | 31        | 8.16%   |
| Pop!_OS       | 19        | 5%      |
| Manjaro       | 15        | 3.95%   |
| ROSA          | 14        | 3.68%   |
| Zorin         | 10        | 2.63%   |
| OpenMandriva  | 10        | 2.63%   |
| Arch          | 10        | 2.63%   |
| Xubuntu       | 9         | 2.37%   |
| SteamOS       | 8         | 2.11%   |
| Debian        | 8         | 2.11%   |
| Endless       | 7         | 1.84%   |
| Kubuntu       | 5         | 1.32%   |
| Kali          | 4         | 1.05%   |
| Ubuntu MATE   | 3         | 0.79%   |
| Elementary    | 3         | 0.79%   |
| ArcoLinux     | 3         | 0.79%   |
| Lubuntu       | 2         | 0.53%   |
| KDE neon      | 2         | 0.53%   |
| CentOS        | 2         | 0.53%   |
| BlackPanther  | 2         | 0.53%   |
| Alpine        | 2         | 0.53%   |
| Ubuntu Budgie | 1         | 0.26%   |
| Siduction     | 1         | 0.26%   |
| Salix         | 1         | 0.26%   |
| RHEL          | 1         | 0.26%   |
| PureOS        | 1         | 0.26%   |
| openSUSE      | 1         | 0.26%   |
| Neptune OS    | 1         | 0.26%   |
| MX            | 1         | 0.26%   |
| EndeavourOS   | 1         | 0.26%   |
| Devuan        | 1         | 0.26%   |
| Clear Linux   | 1         | 0.26%   |
| Artix         | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.4.0-42-generic           | 10        | 2.23%   |
| 5.4.0-48-generic           | 8         | 1.79%   |
| 5.4.0-52-generic           | 5         | 1.12%   |
| 5.15.0-56-generic          | 5         | 1.12%   |
| 5.0.0-23-generic           | 5         | 1.12%   |
| 5.4.0-26-generic           | 4         | 0.89%   |
| 5.16.7-desktop-1omv4003    | 4         | 0.89%   |
| 5.15.0-91-generic          | 4         | 0.89%   |
| 5.13.0-valve36-1-neptune   | 4         | 0.89%   |
| 6.2.9-300.fc38.x86_64      | 3         | 0.67%   |
| 6.2.0-37-generic           | 3         | 0.67%   |
| 6.2.0-26-generic           | 3         | 0.67%   |
| 6.2.0-20-generic           | 3         | 0.67%   |
| 5.8.0-59-generic           | 3         | 0.67%   |
| 5.8.0-44-generic           | 3         | 0.67%   |
| 5.4.0-72-generic           | 3         | 0.67%   |
| 5.4.0-65-generic           | 3         | 0.67%   |
| 5.4.0-58-generic           | 3         | 0.67%   |
| 5.3.0-46-generic           | 3         | 0.67%   |
| 5.3.0-42-generic           | 3         | 0.67%   |
| 5.3.0-26-generic           | 3         | 0.67%   |
| 5.19.0-46-generic          | 3         | 0.67%   |
| 5.15.0-71-generic          | 3         | 0.67%   |
| 5.15.0-57-generic          | 3         | 0.67%   |
| 5.15.0-50-generic          | 3         | 0.67%   |
| 5.15.0-41-generic          | 3         | 0.67%   |
| 5.11.0-34-generic          | 3         | 0.67%   |
| 6.4.9-200.fc38.x86_64      | 2         | 0.45%   |
| 6.3.8-200.fc38.x86_64      | 2         | 0.45%   |
| 6.3.5-2-MANJARO            | 2         | 0.45%   |
| 6.1.52-valve9-1-neptune-61 | 2         | 0.45%   |
| 6.1.18-200.fc37.x86_64     | 2         | 0.45%   |
| 6.1.14-200.fc37.x86_64     | 2         | 0.45%   |
| 6.1.10-200.fc37.x86_64     | 2         | 0.45%   |
| 6.1.0-9-amd64              | 2         | 0.45%   |
| 6.0.8-300.fc37.x86_64      | 2         | 0.45%   |
| 6.0.0-kali3-amd64          | 2         | 0.45%   |
| 5.9.16-200.fc33.x86_64     | 2         | 0.45%   |
| 5.8.16-300.fc33.x86_64     | 2         | 0.45%   |
| 5.8.0-7642-generic         | 2         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 71        | 16.51%  |
| 5.15.0  | 39        | 9.07%   |
| 5.8.0   | 23        | 5.35%   |
| 5.11.0  | 21        | 4.88%   |
| 4.15.0  | 20        | 4.65%   |
| 5.3.0   | 18        | 4.19%   |
| 5.13.0  | 17        | 3.95%   |
| 5.19.0  | 16        | 3.72%   |
| 6.2.0   | 15        | 3.49%   |
| 5.0.0   | 12        | 2.79%   |
| 6.1.0   | 8         | 1.86%   |
| 4.18.0  | 6         | 1.4%    |
| 6.3.5   | 4         | 0.93%   |
| 6.2.9   | 4         | 0.93%   |
| 5.16.7  | 4         | 0.93%   |
| 5.10.0  | 4         | 0.93%   |
| 6.6.2   | 3         | 0.7%    |
| 6.1.52  | 3         | 0.7%    |
| 6.1.14  | 3         | 0.7%    |
| 4.9.60  | 3         | 0.7%    |
| 6.5.0   | 2         | 0.47%   |
| 6.4.9   | 2         | 0.47%   |
| 6.4.6   | 2         | 0.47%   |
| 6.3.8   | 2         | 0.47%   |
| 6.2.6   | 2         | 0.47%   |
| 6.2.11  | 2         | 0.47%   |
| 6.1.7   | 2         | 0.47%   |
| 6.1.34  | 2         | 0.47%   |
| 6.1.18  | 2         | 0.47%   |
| 6.1.12  | 2         | 0.47%   |
| 6.1.10  | 2         | 0.47%   |
| 6.0.8   | 2         | 0.47%   |
| 6.0.7   | 2         | 0.47%   |
| 6.0.2   | 2         | 0.47%   |
| 6.0.0   | 2         | 0.47%   |
| 5.9.16  | 2         | 0.47%   |
| 5.8.16  | 2         | 0.47%   |
| 5.7.10  | 2         | 0.47%   |
| 5.6.0   | 2         | 0.47%   |
| 5.4.2   | 2         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 17.75%  |
| 5.15    | 49        | 11.75%  |
| 5.8     | 27        | 6.47%   |
| 5.11    | 26        | 6.24%   |
| 6.2     | 24        | 5.76%   |
| 6.1     | 23        | 5.52%   |
| 5.3     | 20        | 4.8%    |
| 5.13    | 20        | 4.8%    |
| 4.15    | 20        | 4.8%    |
| 5.19    | 19        | 4.56%   |
| 5.16    | 13        | 3.12%   |
| 5.0     | 12        | 2.88%   |
| 5.10    | 11        | 2.64%   |
| 6.0     | 9         | 2.16%   |
| 6.4     | 8         | 1.92%   |
| 5.18    | 8         | 1.92%   |
| 4.18    | 8         | 1.92%   |
| 6.3     | 6         | 1.44%   |
| 4.9     | 6         | 1.44%   |
| 5.9     | 5         | 1.2%    |
| 6.5     | 4         | 0.96%   |
| 5.7     | 4         | 0.96%   |
| 5.14    | 4         | 0.96%   |
| 6.6     | 3         | 0.72%   |
| 5.6     | 3         | 0.72%   |
| 5.17    | 3         | 0.72%   |
| 4.19    | 3         | 0.72%   |
| 4.1     | 2         | 0.48%   |
| 5.5     | 1         | 0.24%   |
| 5.12    | 1         | 0.24%   |
| 4.4     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 364       | 97.07%  |
| i686   | 11        | 2.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 202       | 52.6%   |
| KDE5            | 58        | 15.1%   |
| Unknown         | 37        | 9.64%   |
| X-Cinnamon      | 26        | 6.77%   |
| XFCE            | 24        | 6.25%   |
| KDE4            | 11        | 2.86%   |
| MATE            | 5         | 1.3%    |
| Cinnamon        | 5         | 1.3%    |
| KDE             | 4         | 1.04%   |
| Pantheon        | 3         | 0.78%   |
| LXQt            | 3         | 0.78%   |
| LXDE            | 2         | 0.52%   |
| i3              | 2         | 0.52%   |
| Trinity         | 1         | 0.26%   |
| GNOME Flashback | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 289       | 75.06%  |
| Wayland | 68        | 17.66%  |
| Unknown | 25        | 6.49%   |
| Tty     | 3         | 0.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 179       | 46.37%  |
| GDM     | 66        | 17.1%   |
| GDM3    | 50        | 12.95%  |
| SDDM    | 39        | 10.1%   |
| LightDM | 31        | 8.03%   |
| KDM     | 11        | 2.85%   |
| TDM     | 10        | 2.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IL   | 152       | 39.38%  |
| en_US   | 131       | 33.94%  |
| Unknown | 45        | 11.66%  |
| ru_RU   | 24        | 6.22%   |
| he_IL   | 12        | 3.11%   |
| C       | 7         | 1.81%   |
| en_GB   | 4         | 1.04%   |
| fr_FR   | 3         | 0.78%   |
| en_AG   | 2         | 0.52%   |
| es_ES   | 1         | 0.26%   |
| en_NZ   | 1         | 0.26%   |
| en_IE   | 1         | 0.26%   |
| en_CA   | 1         | 0.26%   |
| en_AU   | 1         | 0.26%   |
| de_DE   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 229       | 59.17%  |
| BIOS | 158       | 40.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 287       | 75.53%  |
| Btrfs   | 38        | 10%     |
| Overlay | 16        | 4.21%   |
| Tmpfs   | 14        | 3.68%   |
| Unknown | 14        | 3.68%   |
| Xfs     | 8         | 2.11%   |
| Ext3    | 2         | 0.53%   |
| Ext2    | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 185       | 47.68%  |
| GPT     | 173       | 44.59%  |
| MBR     | 30        | 7.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 348       | 92.31%  |
| Yes       | 29        | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 288       | 76.39%  |
| Yes       | 89        | 23.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 102       | 27.2%   |
| Dell                | 85        | 22.67%  |
| ASUSTek Computer    | 66        | 17.6%   |
| Hewlett-Packard     | 54        | 14.4%   |
| Acer                | 12        | 3.2%    |
| Valve               | 8         | 2.13%   |
| Apple               | 7         | 1.87%   |
| Samsung Electronics | 6         | 1.6%    |
| Toshiba             | 5         | 1.33%   |
| Fujitsu             | 4         | 1.07%   |
| LG Electronics      | 3         | 0.8%    |
| Timi                | 2         | 0.53%   |
| Razer               | 2         | 0.53%   |
| MSI                 | 2         | 0.53%   |
| Fujitsu Siemens     | 2         | 0.53%   |
| Chuwi               | 2         | 0.53%   |
| Unknown             | 2         | 0.53%   |
| System76            | 1         | 0.27%   |
| Purism              | 1         | 0.27%   |
| Notebook            | 1         | 0.27%   |
| IP3 Tech            | 1         | 0.27%   |
| HUAWEI              | 1         | 0.27%   |
| Heptagon Systems    | 1         | 0.27%   |
| GPD                 | 1         | 0.27%   |
| Google              | 1         | 0.27%   |
| Gigabyte Technology | 1         | 0.27%   |
| Framework           | 1         | 0.27%   |
| Alienware           | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Valve Jupiter                         | 8         | 2.13%   |
| Unknown                               | 7         | 1.87%   |
| Lenovo IdeaPad 5 14ITL05 82FE         | 3         | 0.8%    |
| HP Pavilion Notebook                  | 3         | 0.8%    |
| HP Compaq Presario CQ61               | 3         | 0.8%    |
| Dell Latitude 7400                    | 3         | 0.8%    |
| Dell Inspiron 3593                    | 3         | 0.8%    |
| ASUS UX331UA                          | 3         | 0.8%    |
| Lenovo V14-IIL 82C4                   | 2         | 0.53%   |
| Lenovo Legion Y530-15ICH 81FV         | 2         | 0.53%   |
| Lenovo IdeaPad Y700-15ISK 80NV        | 2         | 0.53%   |
| Lenovo IdeaPad L340-15IWL 81LG        | 2         | 0.53%   |
| Lenovo G560 0679                      | 2         | 0.53%   |
| Lenovo G50-80 80L0                    | 2         | 0.53%   |
| HP ZBook 15 G3                        | 2         | 0.53%   |
| HP ProBook 430 G6                     | 2         | 0.53%   |
| HP EliteBook 840 G6                   | 2         | 0.53%   |
| HP EliteBook 840 G5                   | 2         | 0.53%   |
| Fujitsu LIFEBOOK AH530                | 2         | 0.53%   |
| Dell XPS 15 9570                      | 2         | 0.53%   |
| Dell XPS 13 9343                      | 2         | 0.53%   |
| Dell Vostro 5402                      | 2         | 0.53%   |
| Dell Vostro 3580                      | 2         | 0.53%   |
| Dell Latitude E6420                   | 2         | 0.53%   |
| Dell Latitude E6330                   | 2         | 0.53%   |
| Dell Latitude E4300                   | 2         | 0.53%   |
| Dell Latitude 5411                    | 2         | 0.53%   |
| Dell Latitude 5410                    | 2         | 0.53%   |
| Dell Inspiron N5110                   | 2         | 0.53%   |
| Dell Inspiron 3542                    | 2         | 0.53%   |
| Dell Inspiron 13-5378                 | 2         | 0.53%   |
| ASUS ZenBook UX425EA_UX425EA          | 2         | 0.53%   |
| ASUS VivoBook_ASUS Laptop X509UA      | 2         | 0.53%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR  | 2         | 0.53%   |
| ASUS UX430UNR                         | 2         | 0.53%   |
| ASUS UL30A                            | 2         | 0.53%   |
| ASUS ROG Zephyrus G15 GA503RW_GA503RW | 2         | 0.53%   |
| ASUS N550JV                           | 2         | 0.53%   |
| Acer Aspire A715-72G                  | 2         | 0.53%   |
| Toshiba Satellite Pro L50-A           | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 52        | 13.87%  |
| Dell Latitude     | 35        | 9.33%   |
| Dell Inspiron     | 22        | 5.87%   |
| Lenovo IdeaPad    | 21        | 5.6%    |
| ASUS VivoBook     | 20        | 5.33%   |
| HP Pavilion       | 12        | 3.2%    |
| Dell Vostro       | 12        | 3.2%    |
| Dell XPS          | 10        | 2.67%   |
| Acer Aspire       | 10        | 2.67%   |
| ASUS ROG          | 9         | 2.4%    |
| Valve Jupiter     | 8         | 2.13%   |
| Lenovo Legion     | 7         | 1.87%   |
| HP ZBook          | 7         | 1.87%   |
| HP EliteBook      | 7         | 1.87%   |
| Unknown           | 7         | 1.87%   |
| HP ProBook        | 6         | 1.6%    |
| ASUS ZenBook      | 5         | 1.33%   |
| ASUS ASUS         | 5         | 1.33%   |
| Toshiba Satellite | 4         | 1.07%   |
| HP Laptop         | 4         | 1.07%   |
| Fujitsu LIFEBOOK  | 4         | 1.07%   |
| Lenovo Yoga       | 3         | 0.8%    |
| Lenovo G50-80     | 3         | 0.8%    |
| HP Compaq         | 3         | 0.8%    |
| ASUS UX331UA      | 3         | 0.8%    |
| Razer Blade       | 2         | 0.53%   |
| Lenovo V14-IIL    | 2         | 0.53%   |
| Lenovo G560       | 2         | 0.53%   |
| HP ENVY           | 2         | 0.53%   |
| HP 255            | 2         | 0.53%   |
| HP 250            | 2         | 0.53%   |
| Dell System       | 2         | 0.53%   |
| Dell Precision    | 2         | 0.53%   |
| ASUS UX430UNR     | 2         | 0.53%   |
| ASUS UL30A        | 2         | 0.53%   |
| ASUS N550JV       | 2         | 0.53%   |
| Toshiba PORTEGE   | 1         | 0.27%   |
| Timi TM1701       | 1         | 0.27%   |
| Timi RedmiBook    | 1         | 0.27%   |
| System76 Gazelle  | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 53        | 14.13%  |
| 2020 | 44        | 11.73%  |
| 2018 | 41        | 10.93%  |
| 2021 | 26        | 6.93%   |
| 2017 | 24        | 6.4%    |
| 2015 | 22        | 5.87%   |
| 2022 | 21        | 5.6%    |
| 2012 | 21        | 5.6%    |
| 2016 | 20        | 5.33%   |
| 2011 | 19        | 5.07%   |
| 2013 | 18        | 4.8%    |
| 2014 | 17        | 4.53%   |
| 2010 | 13        | 3.47%   |
| 2008 | 11        | 2.93%   |
| 2009 | 9         | 2.4%    |
| 2023 | 8         | 2.13%   |
| 2007 | 6         | 1.6%    |
| 2006 | 2         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 375       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 331       | 87.57%  |
| Enabled  | 47        | 12.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 373       | 99.47%  |
| Yes  | 2         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 94        | 24.87%  |
| 16.01-24.0  | 88        | 23.28%  |
| 32.01-64.0  | 62        | 16.4%   |
| 8.01-16.0   | 56        | 14.81%  |
| 3.01-4.0    | 43        | 11.38%  |
| 1.01-2.0    | 16        | 4.23%   |
| 64.01-256.0 | 7         | 1.85%   |
| 24.01-32.0  | 5         | 1.32%   |
| 2.01-3.0    | 4         | 1.06%   |
| 0.51-1.0    | 3         | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 98        | 23.79%  |
| 1.01-2.0   | 96        | 23.3%   |
| 3.01-4.0   | 75        | 18.2%   |
| 4.01-8.0   | 72        | 17.48%  |
| 8.01-16.0  | 44        | 10.68%  |
| 0.51-1.0   | 17        | 4.13%   |
| 16.01-24.0 | 7         | 1.7%    |
| 0.01-0.5   | 3         | 0.73%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 306       | 80.95%  |
| 2      | 63        | 16.67%  |
| 3      | 5         | 1.32%   |
| 0      | 3         | 0.79%   |
| 4      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 270       | 72%     |
| Yes       | 105       | 28%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 77.72%  |
| No        | 84        | 22.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 368       | 98.13%  |
| No        | 7         | 1.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 313       | 82.59%  |
| No        | 66        | 17.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Israel  | 375       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Tel Aviv         | 166       | 40.39%  |
| Ramat Gan        | 37        | 9%      |
| Jerusalem        | 22        | 5.35%   |
| Haifa            | 13        | 3.16%   |
| Petaẖ Tiqwa    | 11        | 2.68%   |
| Givatayim        | 11        | 2.68%   |
| Herzliya         | 10        | 2.43%   |
| Rishon LeZiyyon  | 9         | 2.19%   |
| Rishon LeTsiyyon | 9         | 2.19%   |
| Petah Tikva      | 9         | 2.19%   |
| Netanya          | 8         | 1.95%   |
| Holon            | 8         | 1.95%   |
| Rehovot          | 7         | 1.7%    |
| Ramat HaSharon   | 5         | 1.22%   |
| Raanana          | 5         | 1.22%   |
| Nahariya         | 5         | 1.22%   |
| Kiryat Ono       | 5         | 1.22%   |
| Ashquelon        | 4         | 0.97%   |
| Lod              | 3         | 0.73%   |
| Kfar Saba        | 3         | 0.73%   |
| Givat Shmuel     | 3         | 0.73%   |
| Bet Shemesh      | 3         | 0.73%   |
| Beersheba        | 3         | 0.73%   |
| Yavne            | 2         | 0.49%   |
| Tel Mond         | 2         | 0.49%   |
| Rosh HaAyin      | 2         | 0.49%   |
| Ramla            | 2         | 0.49%   |
| Qiryat Yam       | 2         | 0.49%   |
| Qiryat Bialik    | 2         | 0.49%   |
| Ness Ziona       | 2         | 0.49%   |
| Hod HaSharon     | 2         | 0.49%   |
| Hadera           | 2         | 0.49%   |
| Bat Yam          | 2         | 0.49%   |
| Ashdod           | 2         | 0.49%   |
| Yehud            | 1         | 0.24%   |
| Yaqum            | 1         | 0.24%   |
| Tsor`a           | 1         | 0.24%   |
| Tirat Carmel     | 1         | 0.24%   |
| Tiberias         | 1         | 0.24%   |
| Shelomi          | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 74        | 110    | 17.09%  |
| WDC                       | 43        | 45     | 9.93%   |
| SanDisk                   | 41        | 50     | 9.47%   |
| Seagate                   | 37        | 44     | 8.55%   |
| Toshiba                   | 32        | 34     | 7.39%   |
| SK hynix                  | 31        | 45     | 7.16%   |
| Intel                     | 25        | 39     | 5.77%   |
| Kingston                  | 19        | 22     | 4.39%   |
| Micron Technology         | 18        | 22     | 4.16%   |
| HGST                      | 18        | 19     | 4.16%   |
| Unknown                   | 11        | 11     | 2.54%   |
| Hitachi                   | 11        | 11     | 2.54%   |
| Crucial                   | 10        | 19     | 2.31%   |
| KIOXIA                    | 9         | 9      | 2.08%   |
| StoreJet                  | 5         | 6      | 1.15%   |
| Apple                     | 5         | 8      | 1.15%   |
| Transcend                 | 4         | 6      | 0.92%   |
| JMicron Technology        | 4         | 4      | 0.92%   |
| A-DATA Technology         | 4         | 5      | 0.92%   |
| Phison Electronics        | 3         | 3      | 0.69%   |
| LITEONIT                  | 3         | 3      | 0.69%   |
| Fujitsu                   | 3         | 3      | 0.69%   |
| Unknown                   | 3         | 4      | 0.69%   |
| SSSTC                     | 2         | 2      | 0.46%   |
| O2 Micro                  | 2         | 2      | 0.46%   |
| LITEON                    | 2         | 2      | 0.46%   |
| faspeed                   | 2         | 3      | 0.46%   |
| China                     | 2         | 3      | 0.46%   |
| Apacer                    | 2         | 2      | 0.46%   |
| USB3.0                    | 1         | 1      | 0.23%   |
| SPCC                      | 1         | 1      | 0.23%   |
| Realtek Semiconductor     | 1         | 1      | 0.23%   |
| OCZ                       | 1         | 1      | 0.23%   |
| Micron/Crucial Technology | 1         | 1      | 0.23%   |
| Mass                      | 1         | 1      | 0.23%   |
| Lexar                     | 1         | 1      | 0.23%   |
| ADATA Technology          | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                        | 9         | 1.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 9         | 1.98%   |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 1.76%   |
| SK hynix NVMe SSD Drive 256GB                       | 5         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 1.1%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 5         | 1.1%    |
| SanDisk NVMe SSD Drive 512GB                        | 5         | 1.1%    |
| Intel SSDPEKNU512GZ 512GB                           | 5         | 1.1%    |
| HGST HTS541010A9E680 1TB                            | 5         | 1.1%    |
| SanDisk SSD PLUS 240GB                              | 4         | 0.88%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 0.88%   |
| Intel NVMe SSD Drive 512GB                          | 4         | 0.88%   |
| HGST HTS721010A9E630 1TB                            | 4         | 0.88%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 0.88%   |
| WDC WD5000BPKT-75PK4T0 500GB                        | 3         | 0.66%   |
| Toshiba NVMe SSD Drive 512GB                        | 3         | 0.66%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.66%   |
| StoreJet Transcend 752GB                            | 3         | 0.66%   |
| SK hynix PC401 NVMe 512GB                           | 3         | 0.66%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 0.66%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.66%   |
| SanDisk NVMe SSD Drive 1TB                          | 3         | 0.66%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.66%   |
| Samsung SSD 850 EVO 500GB                           | 3         | 0.66%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 3         | 0.66%   |
| Intel NVMe SSD Drive 256GB                          | 3         | 0.66%   |
| HGST HTS545050A7E380 500GB                          | 3         | 0.66%   |
| Unknown                                             | 3         | 0.66%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 2         | 0.44%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 2         | 0.44%   |
| WDC PC SN730 NVMe 512GB                             | 2         | 0.44%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                  | 2         | 0.44%   |
| WDC PC SN530 NVMe 256GB                             | 2         | 0.44%   |
| Unknown MMC Card  64GB                              | 2         | 0.44%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.44%   |
| Toshiba KXG6AZNV1T02 1TB                            | 2         | 0.44%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB             | 2         | 0.44%   |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 0.44%   |
| Seagate ST9500423AS 500GB                           | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 44     | 32.17%  |
| WDC                 | 22        | 22     | 19.13%  |
| Toshiba             | 18        | 18     | 15.65%  |
| HGST                | 18        | 19     | 15.65%  |
| Hitachi             | 11        | 11     | 9.57%   |
| StoreJet            | 3         | 3      | 2.61%   |
| Fujitsu             | 3         | 3      | 2.61%   |
| USB3.0              | 1         | 1      | 0.87%   |
| Unknown             | 1         | 1      | 0.87%   |
| Samsung Electronics | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 24     | 20%     |
| SanDisk             | 19        | 23     | 16.52%  |
| Kingston            | 12        | 15     | 10.43%  |
| Crucial             | 10        | 19     | 8.7%    |
| SK hynix            | 9         | 20     | 7.83%   |
| Micron Technology   | 8         | 8      | 6.96%   |
| WDC                 | 4         | 4      | 3.48%   |
| Toshiba             | 4         | 4      | 3.48%   |
| Apple               | 4         | 4      | 3.48%   |
| Transcend           | 3         | 5      | 2.61%   |
| LITEONIT            | 3         | 3      | 2.61%   |
| Intel               | 3         | 3      | 2.61%   |
| A-DATA Technology   | 3         | 4      | 2.61%   |
| LITEON              | 2         | 2      | 1.74%   |
| JMicron Technology  | 2         | 2      | 1.74%   |
| China               | 2         | 3      | 1.74%   |
| Apacer              | 2         | 2      | 1.74%   |
| OCZ                 | 1         | 1      | 0.87%   |
| faspeed             | 1         | 1      | 0.87%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 182       | 253    | 43.13%  |
| SSD     | 111       | 147    | 26.3%   |
| HDD     | 110       | 123    | 26.07%  |
| MMC     | 12        | 13     | 2.84%   |
| Unknown | 7         | 8      | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 200       | 257    | 48.31%  |
| NVMe | 182       | 253    | 43.96%  |
| SAS  | 20        | 21     | 4.83%   |
| MMC  | 12        | 13     | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 146       | 179    | 65.77%  |
| 0.51-1.0   | 69        | 84     | 31.08%  |
| 1.01-2.0   | 7         | 7      | 3.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 117       | 30.15%  |
| 101-250        | 107       | 27.58%  |
| 501-1000       | 67        | 17.27%  |
| 51-100         | 25        | 6.44%   |
| 1-20           | 20        | 5.15%   |
| 1001-2000      | 19        | 4.9%    |
| Unknown        | 12        | 3.09%   |
| 21-50          | 11        | 2.84%   |
| 2001-3000      | 7         | 1.8%    |
| More than 3000 | 3         | 0.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 142       | 35.5%   |
| 21-50     | 76        | 19%     |
| 101-250   | 70        | 17.5%   |
| 51-100    | 49        | 12.25%  |
| 251-500   | 35        | 8.75%   |
| 501-1000  | 12        | 3%      |
| Unknown   | 12        | 3%      |
| 1001-2000 | 4         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9A300 250GB         | 2         | 2      | 6.9%    |
| HGST HTS545050A7E380 500GB            | 2         | 2      | 6.9%    |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 1      | 3.45%   |
| WDC WD5000BPVT-75HXZT1 500GB          | 1         | 1      | 3.45%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 3.45%   |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 3.45%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 3.45%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 3.45%   |
| Toshiba MK5075GSX 500GB               | 1         | 1      | 3.45%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 3.45%   |
| Toshiba MK1646GSX 160GB               | 1         | 1      | 3.45%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 5      | 3.45%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 3.45%   |
| Seagate ST9500423AS 500GB             | 1         | 1      | 3.45%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 3.45%   |
| Seagate ST9120817AS 120GB             | 1         | 1      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 3.45%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 3.45%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 1      | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 2      | 3.45%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 3.45%   |
| Intel SSDSCKKF256H6 SATA 256GB        | 1         | 1      | 3.45%   |
| Hitachi HTS542516K9SA00 160GB         | 1         | 1      | 3.45%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 3.45%   |
| HGST HCC545050A7E380 500GB            | 1         | 1      | 3.45%   |
| Fujitsu MHY2160BH 160GB               | 1         | 1      | 3.45%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 8      | 21.43%  |
| Toshiba  | 5         | 5      | 17.86%  |
| WDC      | 4         | 4      | 14.29%  |
| HGST     | 4         | 4      | 14.29%  |
| Hitachi  | 3         | 3      | 10.71%  |
| SK hynix | 2         | 6      | 7.14%   |
| SanDisk  | 1         | 1      | 3.57%   |
| Intel    | 1         | 1      | 3.57%   |
| Fujitsu  | 1         | 1      | 3.57%   |
| Crucial  | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 8      | 26.09%  |
| Toshiba | 5         | 5      | 21.74%  |
| WDC     | 4         | 4      | 17.39%  |
| HGST    | 4         | 4      | 17.39%  |
| Hitachi | 3         | 3      | 13.04%  |
| Fujitsu | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 25     | 80%     |
| SSD  | 5         | 9      | 20%     |

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
| Detected | 210       | 288    | 52.9%   |
| Works    | 162       | 222    | 40.81%  |
| Malfunc  | 25        | 34     | 6.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 273       | 60.26%  |
| Samsung Electronics            | 54        | 11.92%  |
| SanDisk                        | 38        | 8.39%   |
| SK hynix                       | 22        | 4.86%   |
| Toshiba America Info Systems   | 11        | 2.43%   |
| AMD                            | 11        | 2.43%   |
| Micron Technology              | 10        | 2.21%   |
| KIOXIA                         | 8         | 1.77%   |
| Kingston Technology Company    | 7         | 1.55%   |
| Phison Electronics             | 3         | 0.66%   |
| Solid State Storage Technology | 2         | 0.44%   |
| Realtek Semiconductor          | 2         | 0.44%   |
| O2 Micro                       | 2         | 0.44%   |
| Nvidia                         | 2         | 0.44%   |
| ADATA Technology               | 2         | 0.44%   |
| VIA Technologies               | 1         | 0.22%   |
| Union Memory (Shenzhen)        | 1         | 0.22%   |
| Transcend                      | 1         | 0.22%   |
| Shenzhen Longsys Electronics   | 1         | 0.22%   |
| Micron/Crucial Technology      | 1         | 0.22%   |
| Apple                          | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 44        | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27        | 5.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 4.96%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 3.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 3.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 17        | 3.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 16        | 3.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 2.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 2.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 12        | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 2.48%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 2.27%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 10        | 2.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 10        | 2.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 1.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 1.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 1.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 1.65%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 8         | 1.65%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 1.45%   |
| Intel SSD 660P Series                                                          | 7         | 1.45%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 1.24%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 6         | 1.24%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 5         | 1.03%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 1.03%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 5         | 1.03%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.03%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.03%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 4         | 0.83%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 4         | 0.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.83%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 3         | 0.62%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.62%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 3         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 235       | 49.58%  |
| NVMe | 182       | 38.4%   |
| RAID | 44        | 9.28%   |
| IDE  | 13        | 2.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 346       | 92.27%  |
| AMD          | 28        | 7.47%   |
| CentaurHauls | 1         | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 18        | 4.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 13        | 3.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 10        | 2.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 9         | 2.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 9         | 2.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 8         | 2.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 8         | 2.13%   |
| AMD Custom APU 0405                         | 8         | 2.13%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 7         | 1.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 7         | 1.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7         | 1.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 7         | 1.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 6         | 1.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 1.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 5         | 1.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 5         | 1.33%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 5         | 1.33%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 4         | 1.07%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 4         | 1.07%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 4         | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 4         | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 4         | 1.07%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 4         | 1.07%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 4         | 1.07%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 3         | 0.8%    |
| Intel Core i7-9850H CPU @ 2.60GHz           | 3         | 0.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.8%    |
| Intel Core i3-8145U CPU @ 2.10GHz           | 3         | 0.8%    |
| Intel Atom CPU N455 @ 1.66GHz               | 3         | 0.8%    |
| Intel 12th Gen Core i7-1255U                | 3         | 0.8%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 0.8%    |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 0.53%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 2         | 0.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 0.53%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 119       | 31.73%  |
| Intel Core i5           | 94        | 25.07%  |
| Other                   | 61        | 16.27%  |
| Intel Core i3           | 31        | 8.27%   |
| Intel Core 2 Duo        | 9         | 2.4%    |
| Intel Celeron           | 7         | 1.87%   |
| Intel Core i9           | 6         | 1.6%    |
| Intel Pentium Dual-Core | 5         | 1.33%   |
| Intel Atom              | 5         | 1.33%   |
| Intel Pentium           | 4         | 1.07%   |
| AMD Ryzen 9             | 4         | 1.07%   |
| AMD Ryzen 5             | 4         | 1.07%   |
| Intel Pentium Dual      | 3         | 0.8%    |
| Intel Genuine           | 3         | 0.8%    |
| AMD Ryzen 7             | 3         | 0.8%    |
| Intel Xeon              | 2         | 0.53%   |
| Intel Core m3           | 2         | 0.53%   |
| AMD Ryzen 7 PRO         | 2         | 0.53%   |
| AMD A6                  | 2         | 0.53%   |
| Intel Core M            | 1         | 0.27%   |
| Intel Core 2            | 1         | 0.27%   |
| Intel Celeron Dual-Core | 1         | 0.27%   |
| CentaurHauls VIA C7     | 1         | 0.27%   |
| AMD Turion 64 X2 Mobile | 1         | 0.27%   |
| AMD Ryzen 5 PRO         | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD A8                  | 1         | 0.27%   |
| AMD A10                 | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 154       | 41.07%  |
| 2       | 148       | 39.47%  |
| 6       | 27        | 7.2%    |
| 8       | 21        | 5.6%    |
| 10      | 9         | 2.4%    |
| 1       | 8         | 2.13%   |
| 14      | 4         | 1.07%   |
| 12      | 2         | 0.53%   |
| 16      | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 374       | 99.73%  |
| Unknown | 1         | 0.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 330       | 87.77%  |
| 1       | 45        | 11.97%  |
| Unknown | 1         | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 365       | 97.33%  |
| Unknown        | 7         | 1.87%   |
| 32-bit         | 3         | 0.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 31.3%   |
| 0x806ea    | 23        | 5.85%   |
| 0x806c1    | 22        | 5.6%    |
| 0x806ec    | 21        | 5.34%   |
| 0x206a7    | 17        | 4.33%   |
| 0x406e3    | 16        | 4.07%   |
| 0x306a9    | 13        | 3.31%   |
| 0x806e9    | 11        | 2.8%    |
| 0x706e5    | 11        | 2.8%    |
| 0x306d4    | 11        | 2.8%    |
| 0xa0652    | 9         | 2.29%   |
| 0x506e3    | 9         | 2.29%   |
| 0x20655    | 9         | 2.29%   |
| 0x40651    | 8         | 2.04%   |
| 0x1067a    | 8         | 2.04%   |
| 0x906ea    | 7         | 1.78%   |
| 0x306c3    | 7         | 1.78%   |
| 0x906ed    | 6         | 1.53%   |
| 0x806eb    | 6         | 1.53%   |
| 0x6fd      | 5         | 1.27%   |
| 0x906a3    | 4         | 1.02%   |
| 0x906a4    | 3         | 0.76%   |
| 0x806d1    | 3         | 0.76%   |
| 0x106ca    | 3         | 0.76%   |
| 0xb06a3    | 2         | 0.51%   |
| 0x906e9    | 2         | 0.51%   |
| 0x706a1    | 2         | 0.51%   |
| 0x6fa      | 2         | 0.51%   |
| 0x106c2    | 2         | 0.51%   |
| 0x10676    | 2         | 0.51%   |
| 0x0a50000c | 2         | 0.51%   |
| 0x0a404101 | 2         | 0.51%   |
| 0x08600104 | 2         | 0.51%   |
| 0x08108109 | 2         | 0.51%   |
| 0x08108102 | 2         | 0.51%   |
| 0xb06a2    | 1         | 0.25%   |
| 0xa0660    | 1         | 0.25%   |
| 0x90672    | 1         | 0.25%   |
| 0x806c2    | 1         | 0.25%   |
| 0x706a8    | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 111       | 29.52%  |
| TigerLake        | 32        | 8.51%   |
| Skylake          | 29        | 7.71%   |
| Haswell          | 24        | 6.38%   |
| IvyBridge        | 21        | 5.59%   |
| Unknown          | 20        | 5.32%   |
| SandyBridge      | 19        | 5.05%   |
| IceLake          | 16        | 4.26%   |
| Broadwell        | 16        | 4.26%   |
| CometLake        | 15        | 3.99%   |
| Penryn           | 14        | 3.72%   |
| Alderlake Hybrid | 13        | 3.46%   |
| Westmere         | 11        | 2.93%   |
| Core             | 9         | 2.39%   |
| Zen+             | 4         | 1.06%   |
| Bonnell          | 4         | 1.06%   |
| Zen 2            | 3         | 0.8%    |
| Goldmont plus    | 3         | 0.8%    |
| Zen 3            | 2         | 0.53%   |
| Puma             | 2         | 0.53%   |
| Piledriver       | 2         | 0.53%   |
| Zen              | 1         | 0.27%   |
| Silvermont       | 1         | 0.27%   |
| Nehalem          | 1         | 0.27%   |
| K8 Hammer        | 1         | 0.27%   |
| Jaguar           | 1         | 0.27%   |
| Goldmont         | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 334       | 68.02%  |
| Nvidia            | 118       | 24.03%  |
| AMD               | 37        | 7.54%   |
| VIA Technologies  | 1         | 0.2%    |
| ASPEED Technology | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 31        | 6.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 29        | 5.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 24        | 4.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 21        | 4.2%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 20        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 17        | 3.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 15        | 3%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 15        | 3%      |
| Intel Haswell-ULT Integrated Graphics Controller                          | 14        | 2.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 14        | 2.8%    |
| Intel HD Graphics 5500                                                    | 13        | 2.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 13        | 2.6%    |
| Intel HD Graphics 620                                                     | 12        | 2.4%    |
| Intel Core Processor Integrated Graphics Controller                       | 11        | 2.2%    |
| Nvidia GP108M [GeForce MX150]                                             | 9         | 1.8%    |
| Intel HD Graphics 530                                                     | 9         | 1.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 9         | 1.8%    |
| AMD VanGogh [AMD Custom GPU 0405]                                         | 8         | 1.6%    |
| Intel Iris Plus Graphics G7                                               | 7         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 6         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 5         | 1%      |
| Nvidia GM107M [GeForce GTX 960M]                                          | 5         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 5         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 5         | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 5         | 1%      |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 5         | 1%      |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 5         | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 0.8%    |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 4         | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 0.6%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 3         | 0.6%    |
| Nvidia GP108M [GeForce MX250]                                             | 3         | 0.6%    |
| Nvidia GP108M [GeForce MX230]                                             | 3         | 0.6%    |
| Nvidia GK107M [GeForce GT 750M]                                           | 3         | 0.6%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 0.6%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 3         | 0.6%    |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 3         | 0.6%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 0.6%    |
| Intel HD Graphics 630                                                     | 3         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 223       | 59.31%  |
| Intel + Nvidia | 101       | 26.86%  |
| 1 x AMD        | 22        | 5.85%   |
| 1 x Nvidia     | 11        | 2.93%   |
| Intel + AMD    | 8         | 2.13%   |
| AMD + Nvidia   | 6         | 1.6%    |
| 2 x Intel      | 2         | 0.53%   |
| 2 x AMD        | 1         | 0.27%   |
| 1 x VIA        | 1         | 0.27%   |
| 1 x ASPEED     | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 307       | 81.22%  |
| Proprietary | 62        | 16.4%   |
| Unknown     | 9         | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 285       | 74.8%   |
| 1.01-2.0   | 29        | 7.61%   |
| 3.01-4.0   | 28        | 7.35%   |
| 0.01-0.5   | 17        | 4.46%   |
| 0.51-1.0   | 8         | 2.1%    |
| 5.01-6.0   | 7         | 1.84%   |
| 7.01-8.0   | 6         | 1.57%   |
| 2.01-3.0   | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 81        | 17.88%  |
| Chimei Innolux          | 63        | 13.91%  |
| LG Display              | 60        | 13.25%  |
| BOE                     | 58        | 12.8%   |
| Samsung Electronics     | 42        | 9.27%   |
| Dell                    | 37        | 8.17%   |
| Lenovo                  | 18        | 3.97%   |
| Sharp                   | 15        | 3.31%   |
| Goldstar                | 9         | 1.99%   |
| InfoVision              | 8         | 1.77%   |
| Chi Mei Optoelectronics | 8         | 1.77%   |
| Valve                   | 7         | 1.55%   |
| Hewlett-Packard         | 6         | 1.32%   |
| Apple                   | 6         | 1.32%   |
| LG Philips              | 5         | 1.1%    |
| Philips                 | 4         | 0.88%   |
| PANDA                   | 4         | 0.88%   |
| Toshiba                 | 3         | 0.66%   |
| CSO                     | 3         | 0.66%   |
| ASUSTek Computer        | 3         | 0.66%   |
| VOR                     | 1         | 0.22%   |
| STD                     | 1         | 0.22%   |
| Seiko/Epson             | 1         | 0.22%   |
| RIS                     | 1         | 0.22%   |
| Panasonic               | 1         | 0.22%   |
| LGD                     | 1         | 0.22%   |
| JDI                     | 1         | 0.22%   |
| Gigabyte Technology     | 1         | 0.22%   |
| CPT                     | 1         | 0.22%   |
| BOE Technology Group    | 1         | 0.22%   |
| AOC                     | 1         | 0.22%   |
| Ancor Communications    | 1         | 0.22%   |
| Acer                    | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 7         | 1.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 7         | 1.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 6         | 1.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 6         | 1.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 4         | 0.86%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 4         | 0.86%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 4         | 0.86%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 3         | 0.65%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 3         | 0.65%   |
| Lenovo E27q-20 LEN62D0 2560x1440 597x336mm 27.0-inch                 | 3         | 0.65%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 3         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO633D 1920x1080 309x174mm 14.0-inch       | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch       | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO102D 1920x1080 293x165mm 13.2-inch       | 3         | 0.65%   |
| Toshiba LCD Monitor LCD2207 1280x800 287x180mm 13.3-inch             | 2         | 0.43%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 2         | 0.43%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch              | 2         | 0.43%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch    | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch | 2         | 0.43%   |
| Samsung Electronics LC34G55T SAM7119 3440x1440 798x334mm 34.1-inch   | 2         | 0.43%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2         | 0.43%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.43%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch          | 2         | 0.43%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch        | 2         | 0.43%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch         | 2         | 0.43%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch         | 2         | 0.43%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch          | 2         | 0.43%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch         | 2         | 0.43%   |
| InfoVision LCD Monitor IVO8C69 1920x1080 309x174mm 14.0-inch         | 2         | 0.43%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 0.43%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch          | 2         | 0.43%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                 | 2         | 0.43%   |
| Dell U2720Q DEL41B5 3840x2160 597x336mm 27.0-inch                    | 2         | 0.43%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                    | 2         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 201       | 49.02%  |
| 1366x768 (WXGA)    | 87        | 21.22%  |
| 3840x2160 (4K)     | 29        | 7.07%   |
| 2560x1440 (QHD)    | 20        | 4.88%   |
| 1280x800 (WXGA)    | 13        | 3.17%   |
| 1920x1200 (WUXGA)  | 10        | 2.44%   |
| 800x1280           | 7         | 1.71%   |
| 1600x900 (HD+)     | 6         | 1.46%   |
| 3200x1800 (QHD+)   | 4         | 0.98%   |
| 3440x1440          | 3         | 0.73%   |
| 2880x1800          | 3         | 0.73%   |
| 2560x1600          | 3         | 0.73%   |
| 1440x900 (WXGA+)   | 3         | 0.73%   |
| 2880x1620          | 2         | 0.49%   |
| 2560x1080          | 2         | 0.49%   |
| 2160x1440          | 2         | 0.49%   |
| 1680x1050 (WSXGA+) | 2         | 0.49%   |
| 1024x768 (XGA)     | 2         | 0.49%   |
| 1024x600           | 2         | 0.49%   |
| 3840x2400          | 1         | 0.24%   |
| 3840x1080          | 1         | 0.24%   |
| 3456x2160          | 1         | 0.24%   |
| 3000x2000          | 1         | 0.24%   |
| 2304x1440          | 1         | 0.24%   |
| 2256x1504          | 1         | 0.24%   |
| 1280x768           | 1         | 0.24%   |
| 1280x1024 (SXGA)   | 1         | 0.24%   |
| Unknown            | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 170       | 37.53%  |
| 13      | 81        | 17.88%  |
| 14      | 58        | 12.8%   |
| 24      | 31        | 6.84%   |
| 27      | 27        | 5.96%   |
| 23      | 13        | 2.87%   |
| 17      | 13        | 2.87%   |
| 12      | 11        | 2.43%   |
| 21      | 8         | 1.77%   |
| 7       | 7         | 1.55%   |
| 34      | 4         | 0.88%   |
| 16      | 4         | 0.88%   |
| 40      | 3         | 0.66%   |
| 31      | 3         | 0.66%   |
| 26      | 3         | 0.66%   |
| 11      | 3         | 0.66%   |
| Unknown | 3         | 0.66%   |
| 22      | 2         | 0.44%   |
| 19      | 2         | 0.44%   |
| 10      | 2         | 0.44%   |
| 86      | 1         | 0.22%   |
| 84      | 1         | 0.22%   |
| 25      | 1         | 0.22%   |
| 18      | 1         | 0.22%   |
| 8       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 267       | 59.47%  |
| 501-600     | 66        | 14.7%   |
| 201-300     | 58        | 12.92%  |
| 351-400     | 19        | 4.23%   |
| 401-500     | 11        | 2.45%   |
| 601-700     | 8         | 1.78%   |
| 1-100       | 7         | 1.56%   |
| 701-800     | 4         | 0.89%   |
| 801-900     | 3         | 0.67%   |
| Unknown     | 3         | 0.67%   |
| 1501-2000   | 1         | 0.22%   |
| 101-200     | 1         | 0.22%   |
| 1001-1500   | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 319       | 83.73%  |
| 16/10   | 37        | 9.71%   |
| 0.67    | 7         | 1.84%   |
| 3/2     | 6         | 1.57%   |
| 21/9    | 4         | 1.05%   |
| Unknown | 3         | 0.79%   |
| 5/4     | 2         | 0.52%   |
| 4/3     | 2         | 0.52%   |
| 0.56    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 170       | 37.69%  |
| 81-90          | 103       | 22.84%  |
| 201-250        | 47        | 10.42%  |
| 71-80          | 35        | 7.76%   |
| 301-350        | 30        | 6.65%   |
| 61-70          | 11        | 2.44%   |
| 121-130        | 10        | 2.22%   |
| 1-40           | 8         | 1.77%   |
| 351-500        | 7         | 1.55%   |
| 251-300        | 5         | 1.11%   |
| 111-120        | 4         | 0.89%   |
| 51-60          | 3         | 0.67%   |
| 151-200        | 3         | 0.67%   |
| 131-140        | 3         | 0.67%   |
| 501-1000       | 3         | 0.67%   |
| Unknown        | 3         | 0.67%   |
| More than 1000 | 2         | 0.44%   |
| 41-50          | 2         | 0.44%   |
| 141-150        | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 186       | 41.99%  |
| 101-120       | 105       | 23.7%   |
| 51-100        | 76        | 17.16%  |
| 161-240       | 46        | 10.38%  |
| More than 240 | 26        | 5.87%   |
| Unknown       | 3         | 0.68%   |
| 1-50          | 1         | 0.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 281       | 73.75%  |
| 2     | 77        | 20.21%  |
| 3     | 13        | 3.41%   |
| 0     | 9         | 2.36%   |
| 4     | 1         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 220       | 36.61%  |
| Realtek Semiconductor           | 193       | 32.11%  |
| Qualcomm Atheros                | 71        | 11.81%  |
| Broadcom                        | 27        | 4.49%   |
| Broadcom Limited                | 15        | 2.5%    |
| MediaTek                        | 12        | 2%      |
| Lenovo                          | 12        | 2%      |
| DisplayLink                     | 5         | 0.83%   |
| ASIX Electronics                | 5         | 0.83%   |
| Xiaomi                          | 3         | 0.5%    |
| Samsung Electronics             | 3         | 0.5%    |
| Qualcomm Atheros Communications | 3         | 0.5%    |
| Marvell Technology Group        | 3         | 0.5%    |
| Edimax Technology               | 3         | 0.5%    |
| TP-Link                         | 2         | 0.33%   |
| Ralink Technology               | 2         | 0.33%   |
| ICS Advent                      | 2         | 0.33%   |
| Huawei Technologies             | 2         | 0.33%   |
| Google                          | 2         | 0.33%   |
| U-Blox                          | 1         | 0.17%   |
| Toshiba                         | 1         | 0.17%   |
| Sierra Wireless                 | 1         | 0.17%   |
| Qualcomm                        | 1         | 0.17%   |
| PEAK-System Technik             | 1         | 0.17%   |
| Nvidia                          | 1         | 0.17%   |
| Nokia Mobile Phones             | 1         | 0.17%   |
| Linksys                         | 1         | 0.17%   |
| LG Electronics                  | 1         | 0.17%   |
| HMD Global                      | 1         | 0.17%   |
| Hewlett-Packard                 | 1         | 0.17%   |
| Dell                            | 1         | 0.17%   |
| Comneon                         | 1         | 0.17%   |
| Bose                            | 1         | 0.17%   |
| Attansic Technology             | 1         | 0.17%   |
| ASUSTek Computer                | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 108       | 14.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 39        | 5.37%   |
| Intel Wireless 8265 / 8275                                              | 25        | 3.44%   |
| Intel Wi-Fi 6 AX201                                                     | 24        | 3.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 20        | 2.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 2.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.52%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.38%   |
| Intel Wireless 8260                                                     | 10        | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.24%   |
| Intel Wireless 7265                                                     | 9         | 1.24%   |
| Intel Wireless 3160                                                     | 9         | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.24%   |
| Intel Wireless 3165                                                     | 8         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.96%   |
| Intel Ethernet Connection (13) I219-V                                   | 7         | 0.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 0.96%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 6         | 0.83%   |
| Intel Wireless 7260                                                     | 6         | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                   | 6         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                       | 5         | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 0.69%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                    | 5         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                    | 5         | 0.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 210       | 54.83%  |
| Qualcomm Atheros                | 66        | 17.23%  |
| Realtek Semiconductor           | 46        | 12.01%  |
| Broadcom                        | 25        | 6.53%   |
| MediaTek                        | 12        | 3.13%   |
| Broadcom Limited                | 12        | 3.13%   |
| Qualcomm Atheros Communications | 3         | 0.78%   |
| TP-Link                         | 2         | 0.52%   |
| Ralink Technology               | 2         | 0.52%   |
| Sierra Wireless                 | 1         | 0.26%   |
| Qualcomm                        | 1         | 0.26%   |
| Edimax Technology               | 1         | 0.26%   |
| Dell                            | 1         | 0.26%   |
| ASUSTek Computer                | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 25        | 6.49%   |
| Intel Wi-Fi 6 AX201                                                     | 24        | 6.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 3.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 3.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 3.38%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 3.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 3.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 2.86%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.6%    |
| Intel Wireless 8260                                                     | 10        | 2.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 2.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 2.34%   |
| Intel Wireless 7265                                                     | 9         | 2.34%   |
| Intel Wireless 3160                                                     | 9         | 2.34%   |
| Intel Wireless 3165                                                     | 8         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 1.82%   |
| Intel Wireless 7260                                                     | 6         | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 1.3%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.04%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter    | 4         | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.78%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.78%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 173       | 53.23%  |
| Intel                    | 85        | 26.15%  |
| Qualcomm Atheros         | 14        | 4.31%   |
| Lenovo                   | 12        | 3.69%   |
| Broadcom                 | 8         | 2.46%   |
| DisplayLink              | 5         | 1.54%   |
| ASIX Electronics         | 5         | 1.54%   |
| Broadcom Limited         | 4         | 1.23%   |
| Xiaomi                   | 3         | 0.92%   |
| Marvell Technology Group | 3         | 0.92%   |
| Samsung Electronics      | 2         | 0.62%   |
| ICS Advent               | 2         | 0.62%   |
| Google                   | 2         | 0.62%   |
| Edimax Technology        | 2         | 0.62%   |
| Nvidia                   | 1         | 0.31%   |
| Linksys                  | 1         | 0.31%   |
| Huawei Technologies      | 1         | 0.31%   |
| HMD Global               | 1         | 0.31%   |
| Attansic Technology      | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 108       | 32.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 11.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 6.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.72%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 2.11%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 1.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 1.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.51%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.51%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 1.51%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.51%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 1.21%   |
| Intel Ethernet Connection (11) I219-LM                            | 4         | 1.21%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.21%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.91%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.91%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.91%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 3         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.6%    |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.6%    |
| ICS Advent 10/100M LAN                                            | 2         | 0.6%    |
| Edimax AC600 USB                                                  | 2         | 0.6%    |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.3%    |
| Realtek PCIe GbE Family Controller                                | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 368       | 54.84%  |
| Ethernet | 293       | 43.67%  |
| Modem    | 9         | 1.34%   |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 295       | 74.12%  |
| Ethernet | 102       | 25.63%  |
| Modem    | 1         | 0.25%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 260       | 69.15%  |
| 1     | 111       | 29.52%  |
| 3     | 3         | 0.8%    |
| 7     | 1         | 0.27%   |
| 0     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 306       | 80.53%  |
| Yes  | 74        | 19.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 183       | 58.1%   |
| IMC Networks                    | 29        | 9.21%   |
| Qualcomm Atheros Communications | 28        | 8.89%   |
| Realtek Semiconductor           | 23        | 7.3%    |
| Broadcom                        | 12        | 3.81%   |
| Foxconn / Hon Hai               | 8         | 2.54%   |
| Lite-On Technology              | 6         | 1.9%    |
| Dell                            | 6         | 1.9%    |
| Apple                           | 6         | 1.9%    |
| Toshiba                         | 2         | 0.63%   |
| Realtek                         | 2         | 0.63%   |
| Hewlett-Packard                 | 2         | 0.63%   |
| Cambridge Silicon Radio         | 2         | 0.63%   |
| ASUSTek Computer                | 2         | 0.63%   |
| Askey Computer                  | 2         | 0.63%   |
| MediaTek                        | 1         | 0.32%   |
| Actions                         | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 67        | 21.27%  |
| Intel Bluetooth Device                              | 60        | 19.05%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 9.52%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 4.76%   |
| Realtek Bluetooth Radio                             | 11        | 3.49%   |
| Intel AX200 Bluetooth                               | 10        | 3.17%   |
| IMC Networks Wireless_Device                        | 9         | 2.86%   |
| IMC Networks 802.11ac WLAN Adapter                  | 8         | 2.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 2.22%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.59%   |
| Lite-On Bluetooth Device                            | 5         | 1.59%   |
| Intel AX210 Bluetooth                               | 5         | 1.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 1.27%   |
| IMC Networks Bluetooth Device                       | 4         | 1.27%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 1.27%   |
| Apple Bluetooth Host Controller                     | 4         | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.95%   |
| IMC Networks Bluetooth Radio                        | 3         | 0.95%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.95%   |
| Realtek Bluetooth Radio                             | 2         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.63%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.63%   |
| Foxconn / Hon Hai BT                                | 2         | 0.63%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 2         | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.63%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.63%   |
| Broadcom BCM20702A0                                 | 2         | 0.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.63%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.63%   |
| ASUS BT-253 Bluetooth Adapter                       | 2         | 0.63%   |
| Askey Bluetooth Device                              | 2         | 0.63%   |
| Toshiba Bluetooth Device                            | 1         | 0.32%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.32%   |
| MediaTek BT                                         | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 344       | 72.88%  |
| Nvidia                     | 55        | 11.65%  |
| AMD                        | 28        | 5.93%   |
| Lenovo                     | 13        | 2.75%   |
| Logitech                   | 6         | 1.27%   |
| Realtek Semiconductor      | 5         | 1.06%   |
| Microsoft                  | 3         | 0.64%   |
| Hewlett-Packard            | 3         | 0.64%   |
| GN Netcom                  | 2         | 0.42%   |
| XMOS                       | 1         | 0.21%   |
| VIA Technologies           | 1         | 0.21%   |
| Texas Instruments          | 1         | 0.21%   |
| Sennheiser Communications  | 1         | 0.21%   |
| Razer USA                  | 1         | 0.21%   |
| PreSonus Audio Electronics | 1         | 0.21%   |
| Plantronics                | 1         | 0.21%   |
| HiBy                       | 1         | 0.21%   |
| FIFINE Microphones         | 1         | 0.21%   |
| Dell                       | 1         | 0.21%   |
| Creative Technology        | 1         | 0.21%   |
| C-Media Electronics        | 1         | 0.21%   |
| ASUSTek Computer           | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 65        | 12.26%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 32        | 6.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 25        | 4.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 4.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17        | 3.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 16        | 3.02%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 3.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16        | 3.02%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 2.83%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 2.64%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 2.64%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 2.64%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 2.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 13        | 2.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 2.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 2.08%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 11        | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.32%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.13%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 6         | 1.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 1.13%   |
| Realtek Semiconductor USB Audio                                            | 5         | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 0.94%   |
| AMD FCH Azalia Controller                                                  | 5         | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.75%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 4         | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.75%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 4         | 0.75%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.75%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 74        | 27.41%  |
| SK hynix            | 68        | 25.19%  |
| Micron Technology   | 49        | 18.15%  |
| Kingston            | 20        | 7.41%   |
| Unknown             | 15        | 5.56%   |
| Crucial             | 14        | 5.19%   |
| Ramaxel Technology  | 8         | 2.96%   |
| Nanya Technology    | 4         | 1.48%   |
| G.Skill             | 4         | 1.48%   |
| Elpida              | 4         | 1.48%   |
| Transcend           | 2         | 0.74%   |
| A-DATA Technology   | 2         | 0.74%   |
| V-Color             | 1         | 0.37%   |
| Corsair             | 1         | 0.37%   |
| Avant               | 1         | 0.37%   |
| ASint Technology    | 1         | 0.37%   |
| 48spaces            | 1         | 0.37%   |
| Unknown             | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s       | 5         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 4         | 1.43%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s       | 4         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 4         | 1.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 4         | 1.43%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s        | 4         | 1.43%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 4         | 1.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.08%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 3         | 1.08%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s     | 3         | 1.08%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 3         | 1.08%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 3         | 1.08%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s       | 3         | 1.08%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s   | 3         | 1.08%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 2         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 2         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 2         | 0.72%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s               | 2         | 0.72%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s        | 2         | 0.72%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 2         | 0.72%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.72%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 2         | 0.72%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 2         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.72%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 2         | 0.72%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.72%   |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM 1067MT/s            | 2         | 0.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.72%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 2         | 0.72%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.72%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.72%   |
| Samsung RAM M471A1G43DB0-CPB 2GB SODIMM 3200MT/s               | 2         | 0.72%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.72%   |
| Ramaxel RAM RMSA3320ME88HBF-3200 16GB SODIMM DDR4 3200MT/s     | 2         | 0.72%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 2         | 0.72%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s  | 2         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 122       | 54.95%  |
| DDR3    | 53        | 23.87%  |
| LPDDR3  | 15        | 6.76%   |
| DDR2    | 10        | 4.5%    |
| DDR5    | 8         | 3.6%    |
| LPDDR5  | 4         | 1.8%    |
| Unknown | 4         | 1.8%    |
| LPDDR4  | 3         | 1.35%   |
| DDR     | 3         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 194       | 87.78%  |
| Row Of Chips | 23        | 10.41%  |
| Chip         | 2         | 0.9%    |
| DIMM         | 1         | 0.45%   |
| Unknown      | 1         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 83        | 34.3%   |
| 4096  | 58        | 23.97%  |
| 16384 | 57        | 23.55%  |
| 2048  | 22        | 9.09%   |
| 32768 | 13        | 5.37%   |
| 1024  | 9         | 3.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 56        | 23.53%  |
| 3200    | 49        | 20.59%  |
| 1600    | 39        | 16.39%  |
| 2133    | 19        | 7.98%   |
| 2400    | 17        | 7.14%   |
| 4800    | 8         | 3.36%   |
| 1334    | 7         | 2.94%   |
| 667     | 7         | 2.94%   |
| 6400    | 5         | 2.1%    |
| 1867    | 5         | 2.1%    |
| 1067    | 5         | 2.1%    |
| 3266    | 4         | 1.68%   |
| 1333    | 4         | 1.68%   |
| 4267    | 3         | 1.26%   |
| 800     | 3         | 1.26%   |
| Unknown | 3         | 1.26%   |
| 533     | 2         | 0.84%   |
| 8400    | 1         | 0.42%   |
| 1066    | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 66.67%  |
| BIXOLON             | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 33.33%  |
| Samsung M288x Series               | 1         | 33.33%  |
| BIXOLON BIXOLON_SLP-T400           | 1         | 33.33%  |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 64        | 18.77%  |
| Chicony Electronics                    | 60        | 17.6%   |
| Realtek Semiconductor                  | 46        | 13.49%  |
| Microdia                               | 33        | 9.68%   |
| Sunplus Innovation Technology          | 26        | 7.62%   |
| Bison Electronics                      | 20        | 5.87%   |
| Lite-On Technology                     | 9         | 2.64%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 2.64%   |
| Suyin                                  | 8         | 2.35%   |
| Quanta                                 | 8         | 2.35%   |
| Logitech                               | 8         | 2.35%   |
| Apple                                  | 8         | 2.35%   |
| Silicon Motion                         | 5         | 1.47%   |
| Acer                                   | 5         | 1.47%   |
| Syntek                                 | 4         | 1.17%   |
| Microsoft                              | 4         | 1.17%   |
| Luxvisions Innotech Limited            | 3         | 0.88%   |
| 8SSC20F27114V1SR0BK1X4S                | 3         | 0.88%   |
| Lenovo                                 | 2         | 0.59%   |
| Cubeternet                             | 2         | 0.59%   |
| ALi                                    | 2         | 0.59%   |
| Alcor Micro                            | 2         | 0.59%   |
| Z-Star Microelectronics                | 1         | 0.29%   |
| YGTek                                  | 1         | 0.29%   |
| Sonix Technology                       | 1         | 0.29%   |
| Samsung Electronics                    | 1         | 0.29%   |
| Ricoh                                  | 1         | 0.29%   |
| Primax Electronics                     | 1         | 0.29%   |
| Jieli Technology                       | 1         | 0.29%   |
| Generalplus Technology                 | 1         | 0.29%   |
| eMPIA Technology                       | 1         | 0.29%   |
| Unknown                                | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam         | 24        | 7.02%   |
| Realtek Integrated_Webcam_HD              | 23        | 6.73%   |
| Chicony Integrated Camera                 | 23        | 6.73%   |
| Microdia Integrated_Webcam_HD             | 17        | 4.97%   |
| IMC Networks Integrated Camera            | 16        | 4.68%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 13        | 3.8%    |
| Sunplus Integrated_Webcam_HD              | 8         | 2.34%   |
| Bison Integrated Camera                   | 7         | 2.05%   |
| Chicony Lenovo EasyCamera                 | 5         | 1.46%   |
| Chicony HP HD Camera                      | 5         | 1.46%   |
| Realtek USB Camera                        | 4         | 1.17%   |
| Lite-On HP HD Camera                      | 4         | 1.17%   |
| Bison SunplusIT Integrated Camera         | 4         | 1.17%   |
| Bison Lenovo EasyCamera                   | 4         | 1.17%   |
| Apple iPhone 5/5C/5S/6/SE                 | 4         | 1.17%   |
| Syntek Integrated Camera                  | 3         | 0.88%   |
| Realtek Lenovo EasyCamera                 | 3         | 0.88%   |
| Realtek Integrated Webcam HD              | 3         | 0.88%   |
| Microdia Integrated Webcam                | 3         | 0.88%   |
| IMC Networks USB2.0 UVC HD Webcam         | 3         | 0.88%   |
| IMC Networks USB2.0 HD IR UVC WebCam      | 3         | 0.88%   |
| Chicony Integrated Camera (1280x720@30)   | 3         | 0.88%   |
| Chicony HP Truevision HD camera           | 3         | 0.88%   |
| 8SSC20F27114V1SR0BK1X4S Integrated Camera | 3         | 0.88%   |
| Suyin Integrated_Webcam_HD                | 2         | 0.58%   |
| Suyin Asus Integrated Webcam [CN031B]     | 2         | 0.58%   |
| Sunplus Lenovo EasyCamera                 | 2         | 0.58%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 2         | 0.58%   |
| Sunplus HD WebCam                         | 2         | 0.58%   |
| Sunplus Dell HD Webcam                    | 2         | 0.58%   |
| Realtek USB2.0 HD UVC WebCam              | 2         | 0.58%   |
| Realtek HP Wide Vision HD Camera          | 2         | 0.58%   |
| Quanta USB Webcam                         | 2         | 0.58%   |
| Quanta HP TrueVision HD Camera            | 2         | 0.58%   |
| Microsoft LifeCam NX-6000                 | 2         | 0.58%   |
| Microdia Integrated_Webcam_FHD            | 2         | 0.58%   |
| Microdia Dell Integrated HD Webcam        | 2         | 0.58%   |
| Luxvisions Innotech Limited HP HD Camera  | 2         | 0.58%   |
| Logitech HD Pro Webcam C920               | 2         | 0.58%   |
| Logitech BRIO Ultra HD Webcam             | 2         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 30        | 38.96%  |
| Validity Sensors                   | 22        | 28.57%  |
| Shenzhen Goodix Technology         | 11        | 14.29%  |
| Elan Microelectronics              | 6         | 7.79%   |
| AuthenTec                          | 3         | 3.9%    |
| STMicroelectronics                 | 2         | 2.6%    |
| Upek                               | 1         | 1.3%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.3%    |
| LighTuning Technology              | 1         | 1.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 20.78%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 7.79%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 7.79%   |
| Elan ELAN:Fingerprint                                                      | 5         | 6.49%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 5.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 5.19%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 3.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.9%    |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 3.9%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.6%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 2.6%    |
| STMicroelectronics Fingerprint Reader                                      | 2         | 2.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.3%    |
| Validity Sensors VFS491                                                    | 1         | 1.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.3%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.3%    |
| Synaptics WBDI                                                             | 1         | 1.3%    |
| Synaptics UWP WBDI                                                         | 1         | 1.3%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 1.3%    |
| Synaptics  WBDI                                                            | 1         | 1.3%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.3%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.3%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.3%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.3%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.3%    |
| Elan ELAN:ARM-M4                                                           | 1         | 1.3%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.3%    |
| AuthenTec AES2810                                                          | 1         | 1.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 28        | 66.67%  |
| Alcor Micro | 14        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 33.33%  |
| Broadcom 58200                                                               | 11        | 26.19%  |
| Broadcom 5880                                                                | 8         | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 214       | 55.44%  |
| 1     | 131       | 33.94%  |
| 2     | 32        | 8.29%   |
| 3     | 6         | 1.55%   |
| 4     | 2         | 0.52%   |
| 7     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 76        | 34.86%  |
| Graphics card            | 42        | 19.27%  |
| Chipcard                 | 37        | 16.97%  |
| Net/wireless             | 26        | 11.93%  |
| Camera                   | 10        | 4.59%   |
| Multimedia controller    | 8         | 3.67%   |
| Bluetooth                | 4         | 1.83%   |
| Communication controller | 3         | 1.38%   |
| Card reader              | 3         | 1.38%   |
| Unassigned class         | 2         | 0.92%   |
| Storage                  | 2         | 0.92%   |
| Sound                    | 2         | 0.92%   |
| Net/ethernet             | 2         | 0.92%   |
| Network                  | 1         | 0.46%   |

