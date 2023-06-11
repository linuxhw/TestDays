Xubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_22.04/Notebook/README.md).

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

Total: 605

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite C650              | Notebook    | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| MSI           | A55M-E35                    | Desktop     | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Dell          | Precision 5510              | Notebook    | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| HP            | 8768 A                      | Desktop     | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Unknown       | Unknown                     | Notebook    | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Acer          | Veriton N4620G              | Desktop     | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Dell          | Latitude E4200              | Notebook    | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Unknown       | 1.0                         | Desktop     | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0b802ad297](https://linux-hardware.org/?probe=0b802ad297) | May 19, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| Pegatron      | Benicia                     | Desktop     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| HP            | 09F8h                       | Desktop     | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0b0b5e02cc](https://linux-hardware.org/?probe=0b0b5e02cc) | May 13, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2d3692d380](https://linux-hardware.org/?probe=2d3692d380) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [3c43bfe7bc](https://linux-hardware.org/?probe=3c43bfe7bc) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Dell          | Latitude E4310              | Notebook    | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Unknown       | Kontron BL i.MX8MM OSM-S... | Soc         | [958fed11ae](https://linux-hardware.org/?probe=958fed11ae) | May 10, 2023 |
| Google        | Edgar                       | Notebook    | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [1c37df2d10](https://linux-hardware.org/?probe=1c37df2d10) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [52836871bb](https://linux-hardware.org/?probe=52836871bb) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [a026aff306](https://linux-hardware.org/?probe=a026aff306) | May 09, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0f322b6e3f](https://linux-hardware.org/?probe=0f322b6e3f) | May 08, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ebafddb3f1](https://linux-hardware.org/?probe=ebafddb3f1) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bbac197d5d](https://linux-hardware.org/?probe=bbac197d5d) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [b735e1019b](https://linux-hardware.org/?probe=b735e1019b) | May 03, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | Notebook    | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | Notebook    | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [4382f0cce7](https://linux-hardware.org/?probe=4382f0cce7) | Apr 27, 2023 |
| HP            | 1632                        | Desktop     | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | Notebook    | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | 0AECh D                     | Desktop     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [9f2a1a2c93](https://linux-hardware.org/?probe=9f2a1a2c93) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | Desktop     | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [93fae77e6c](https://linux-hardware.org/?probe=93fae77e6c) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Medion        | MS-7848                     | Desktop     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [71ee0575d4](https://linux-hardware.org/?probe=71ee0575d4) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [f7cdc4223d](https://linux-hardware.org/?probe=f7cdc4223d) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Medion        | S321X                       | Notebook    | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | Desktop     | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | Notebook    | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | Notebook    | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Google        | Kefka                       | Notebook    | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ac565d5d7d](https://linux-hardware.org/?probe=ac565d5d7d) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ad41e0e370](https://linux-hardware.org/?probe=ad41e0e370) | Mar 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec9c2f21a5](https://linux-hardware.org/?probe=ec9c2f21a5) | Mar 05, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [e513434675](https://linux-hardware.org/?probe=e513434675) | Mar 04, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [5c3d9047bd](https://linux-hardware.org/?probe=5c3d9047bd) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| OEM           | Unknown                     | Desktop     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e367c45f3b](https://linux-hardware.org/?probe=e367c45f3b) | Mar 03, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| Google        | Nautilus                    | Convertible | [5aff7271ac](https://linux-hardware.org/?probe=5aff7271ac) | Mar 02, 2023 |
| AZW           | GTR V01                     | Mini pc     | [09e66839c3](https://linux-hardware.org/?probe=09e66839c3) | Mar 01, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 44        | 8.73%   |
| 5.15.0-52-generic    | 35        | 6.94%   |
| 5.15.0-47-generic    | 31        | 6.15%   |
| 5.15.0-58-generic    | 27        | 5.36%   |
| 5.15.0-48-generic    | 25        | 4.96%   |
| 5.15.0-60-generic    | 23        | 4.56%   |
| 5.15.0-67-generic    | 20        | 3.97%   |
| 5.15.0-25-generic    | 20        | 3.97%   |
| 5.15.0-46-generic    | 17        | 3.37%   |
| 5.15.0-53-generic    | 14        | 2.78%   |
| 5.15.0-27-generic    | 14        | 2.78%   |
| 5.19.0-41-generic    | 13        | 2.58%   |
| 5.19.0-35-generic    | 13        | 2.58%   |
| 5.15.0-71-generic    | 12        | 2.38%   |
| 5.19.0-38-generic    | 10        | 1.98%   |
| 5.15.0-69-generic    | 10        | 1.98%   |
| 5.15.0-57-generic    | 10        | 1.98%   |
| 5.15.0-43-generic    | 10        | 1.98%   |
| 5.15.0-50-generic    | 9         | 1.79%   |
| 5.15.0-41-generic    | 9         | 1.79%   |
| 5.15.0-40-generic    | 9         | 1.79%   |
| 5.15.0-70-generic    | 7         | 1.39%   |
| 5.19.0-32-generic    | 6         | 1.19%   |
| 5.15.0-71-lowlatency | 6         | 1.19%   |
| 5.15.0-39-generic    | 6         | 1.19%   |
| 5.19.0-43-generic    | 5         | 0.99%   |
| 5.19.0-42-generic    | 5         | 0.99%   |
| 5.15.0-37-generic    | 5         | 0.99%   |
| 5.15.0-35-generic    | 5         | 0.99%   |
| 5.15.0-33-generic    | 4         | 0.79%   |
| 5.15.0-30-generic    | 4         | 0.79%   |
| 5.17.0-1020-oem      | 3         | 0.6%    |
| 6.2.7-060207-generic | 2         | 0.4%    |
| 6.1.0-1006-oem       | 2         | 0.4%    |
| 5.17.0-1013-oem      | 2         | 0.4%    |
| 5.15.0-72-generic    | 2         | 0.4%    |
| 5.15.0-60-lowlatency | 2         | 0.4%    |
| 5.15.0-54-generic    | 2         | 0.4%    |
| 5.15.0-50-lowlatency | 2         | 0.4%    |
| 5.15.0-48-lowlatency | 2         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 370       | 77.57%  |
| 5.19.0   | 56        | 11.74%  |
| 5.17.0   | 11        | 2.31%   |
| 6.1.0    | 5         | 1.05%   |
| 6.2.7    | 2         | 0.42%   |
| 6.0.0    | 2         | 0.42%   |
| 5.4.0    | 2         | 0.42%   |
| 5.18.0   | 2         | 0.42%   |
| 5.15.93  | 2         | 0.42%   |
| 6.3.3    | 1         | 0.21%   |
| 6.2.9    | 1         | 0.21%   |
| 6.2.2    | 1         | 0.21%   |
| 6.2.10   | 1         | 0.21%   |
| 6.2.0    | 1         | 0.21%   |
| 6.1.6    | 1         | 0.21%   |
| 6.1.10   | 1         | 0.21%   |
| 6.0.9    | 1         | 0.21%   |
| 6.0.7    | 1         | 0.21%   |
| 5.19.5   | 1         | 0.21%   |
| 5.19.13  | 1         | 0.21%   |
| 5.19.1   | 1         | 0.21%   |
| 5.18.12  | 1         | 0.21%   |
| 5.17.3   | 1         | 0.21%   |
| 5.16.9   | 1         | 0.21%   |
| 5.15.89  | 1         | 0.21%   |
| 5.15.74  | 1         | 0.21%   |
| 5.15.68  | 1         | 0.21%   |
| 5.15.61  | 1         | 0.21%   |
| 5.15.59  | 1         | 0.21%   |
| 5.15.48  | 1         | 0.21%   |
| 5.15.23  | 1         | 0.21%   |
| 5.13.0   | 1         | 0.21%   |
| 5.10.110 | 1         | 0.21%   |
| 4.19.241 | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 379       | 79.45%  |
| 5.19    | 59        | 12.37%  |
| 5.17    | 12        | 2.52%   |
| 6.1     | 7         | 1.47%   |
| 6.2     | 6         | 1.26%   |
| 6.0     | 4         | 0.84%   |
| 5.18    | 3         | 0.63%   |
| 5.4     | 2         | 0.42%   |
| 6.3     | 1         | 0.21%   |
| 5.16    | 1         | 0.21%   |
| 5.13    | 1         | 0.21%   |
| 5.10    | 1         | 0.21%   |
| 4.19    | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 460       | 97.66%  |
| aarch64 | 8         | 1.7%    |
| armv7l  | 3         | 0.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 457       | 97.03%  |
| GNOME           | 11        | 2.34%   |
| KDE5            | 1         | 0.21%   |
| i3              | 1         | 0.21%   |
| GNOME Flashback | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 454       | 95.98%  |
| Tty     | 12        | 2.54%   |
| Wayland | 7         | 1.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 413       | 87.69%  |
| Unknown | 28        | 5.94%   |
| GDM3    | 23        | 4.88%   |
| SDDM    | 4         | 0.85%   |
| SLiM    | 2         | 0.42%   |
| GDM     | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 186       | 39.49%  |
| de_DE | 63        | 13.38%  |
| fr_FR | 54        | 11.46%  |
| it_IT | 27        | 5.73%   |
| en_GB | 20        | 4.25%   |
| pt_BR | 16        | 3.4%    |
| ru_RU | 14        | 2.97%   |
| en_CA | 13        | 2.76%   |
| es_ES | 7         | 1.49%   |
| cs_CZ | 7         | 1.49%   |
| en_AU | 6         | 1.27%   |
| nl_NL | 5         | 1.06%   |
| pl_PL | 4         | 0.85%   |
| en_IN | 4         | 0.85%   |
| C     | 4         | 0.85%   |
| tr_TR | 3         | 0.64%   |
| ja_JP | 3         | 0.64%   |
| hu_HU | 3         | 0.64%   |
| es_VE | 3         | 0.64%   |
| ru_UA | 2         | 0.42%   |
| fr_BE | 2         | 0.42%   |
| es_MX | 2         | 0.42%   |
| es_CO | 2         | 0.42%   |
| es_AR | 2         | 0.42%   |
| de_CH | 2         | 0.42%   |
| zh_CN | 1         | 0.21%   |
| sv_SE | 1         | 0.21%   |
| ro_RO | 1         | 0.21%   |
| pt_PT | 1         | 0.21%   |
| nl_BE | 1         | 0.21%   |
| lt_LT | 1         | 0.21%   |
| ko_KR | 1         | 0.21%   |
| fr_CH | 1         | 0.21%   |
| fr_CA | 1         | 0.21%   |
| fi_FI | 1         | 0.21%   |
| es_CL | 1         | 0.21%   |
| en_ZA | 1         | 0.21%   |
| en_IL | 1         | 0.21%   |
| en_IE | 1         | 0.21%   |
| el_GR | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 244       | 51.37%  |
| BIOS | 231       | 48.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 417       | 87.06%  |
| Tmpfs   | 21        | 4.38%   |
| Overlay | 16        | 3.34%   |
| Zfs     | 12        | 2.51%   |
| Btrfs   | 12        | 2.51%   |
| Ext3    | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 333       | 68.94%  |
| MBR     | 77        | 15.94%  |
| Unknown | 73        | 15.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 410       | 85.95%  |
| Yes       | 67        | 14.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 331       | 69.83%  |
| Yes       | 143       | 30.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 70        | 14.86%  |
| Hewlett-Packard         | 70        | 14.86%  |
| ASUSTek Computer        | 65        | 13.8%   |
| Dell                    | 53        | 11.25%  |
| MSI                     | 31        | 6.58%   |
| Gigabyte Technology     | 28        | 5.94%   |
| Acer                    | 28        | 5.94%   |
| ASRock                  | 13        | 2.76%   |
| Google                  | 12        | 2.55%   |
| Apple                   | 8         | 1.7%    |
| Toshiba                 | 7         | 1.49%   |
| Unknown                 | 7         | 1.49%   |
| Intel                   | 5         | 1.06%   |
| Supermicro              | 4         | 0.85%   |
| Sony                    | 4         | 0.85%   |
| GPU Company             | 4         | 0.85%   |
| Samsung Electronics     | 3         | 0.64%   |
| Rockchip                | 3         | 0.64%   |
| Medion                  | 3         | 0.64%   |
| HUAWEI                  | 3         | 0.64%   |
| Fujitsu                 | 3         | 0.64%   |
| sunxi                   | 2         | 0.42%   |
| Radxa                   | 2         | 0.42%   |
| PCWare                  | 2         | 0.42%   |
| Packard Bell            | 2         | 0.42%   |
| Notebook                | 2         | 0.42%   |
| HONOR                   | 2         | 0.42%   |
| Foxconn                 | 2         | 0.42%   |
| Chuwi                   | 2         | 0.42%   |
| Xunlong                 | 1         | 0.21%   |
| VIT                     | 1         | 0.21%   |
| Tactus                  | 1         | 0.21%   |
| Standard                | 1         | 0.21%   |
| SGIN                    | 1         | 0.21%   |
| Schenker                | 1         | 0.21%   |
| Raspberry Pi Foundation | 1         | 0.21%   |
| Pine Microsystems       | 1         | 0.21%   |
| Pegatron                | 1         | 0.21%   |
| Panasonic               | 1         | 0.21%   |
| OEM                     | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 9         | 1.91%   |
| HP EliteBook 840 G3                      | 4         | 0.85%   |
| Dell OptiPlex 7010                       | 4         | 0.85%   |
| ASUS All Series                          | 4         | 0.85%   |
| MSI MS-7D43                              | 3         | 0.64%   |
| Google Snappy                            | 3         | 0.64%   |
| Rockchip RK3318 BOX                      | 2         | 0.42%   |
| MSI MS-7D46                              | 2         | 0.42%   |
| MSI MS-7D25                              | 2         | 0.42%   |
| MSI MS-7C52                              | 2         | 0.42%   |
| MSI MS-7817                              | 2         | 0.42%   |
| MSI MS-7721                              | 2         | 0.42%   |
| Lenovo ThinkPad P50 20EN0013US           | 2         | 0.42%   |
| HP Pavilion Notebook                     | 2         | 0.42%   |
| HP Pavilion g6                           | 2         | 0.42%   |
| HP Pavilion 15                           | 2         | 0.42%   |
| HP Laptop 15s-fq2xxx                     | 2         | 0.42%   |
| HP 255 G8 Notebook PC                    | 2         | 0.42%   |
| GPU Company GWTN116-3                    | 2         | 0.42%   |
| Google Auron_Yuna                        | 2         | 0.42%   |
| Dell Latitude E5450                      | 2         | 0.42%   |
| Dell Latitude 7420                       | 2         | 0.42%   |
| ASUS K30AD_M31AD_M51AD                   | 2         | 0.42%   |
| ASUS ASUS TUF Gaming A15 FA507RE_FA507RE | 2         | 0.42%   |
| Apple MacBookPro8,1                      | 2         | 0.42%   |
| Acer Switch SW312-31                     | 2         | 0.42%   |
| Xunlong Orange Pi PC Plus                | 1         | 0.21%   |
| VIT Aptio CRB                            | 1         | 0.21%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.21%   |
| Toshiba Satellite Pro R50-B              | 1         | 0.21%   |
| Toshiba Satellite L750D                  | 1         | 0.21%   |
| Toshiba Satellite C650                   | 1         | 0.21%   |
| Toshiba Satellite C55D-B                 | 1         | 0.21%   |
| Toshiba PT10F                            | 1         | 0.21%   |
| Toshiba EQUIUM P200                      | 1         | 0.21%   |
| Tactus GeoBook 140                       | 1         | 0.21%   |
| Supermicro X10SRA                        | 1         | 0.21%   |
| Supermicro Super Server                  | 1         | 0.21%   |
| Supermicro M12SWA-TF                     | 1         | 0.21%   |
| Supermicro AS -5014A-TT                  | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 38        | 8.07%   |
| Acer Aspire        | 17        | 3.61%   |
| HP Pavilion        | 16        | 3.4%    |
| Dell Latitude      | 15        | 3.18%   |
| HP EliteBook       | 10        | 2.12%   |
| Dell OptiPlex      | 10        | 2.12%   |
| ASUS PRIME         | 10        | 2.12%   |
| Dell Inspiron      | 9         | 1.91%   |
| Unknown            | 9         | 1.91%   |
| Lenovo IdeaPad     | 8         | 1.7%    |
| Lenovo ThinkCentre | 7         | 1.49%   |
| HP Laptop          | 7         | 1.49%   |
| HP Compaq          | 7         | 1.49%   |
| ASUS VivoBook      | 6         | 1.27%   |
| Toshiba Satellite  | 5         | 1.06%   |
| Dell XPS           | 5         | 1.06%   |
| HP ProBook         | 4         | 0.85%   |
| Dell Precision     | 4         | 0.85%   |
| ASUS ROG           | 4         | 0.85%   |
| ASUS All           | 4         | 0.85%   |
| Acer Veriton       | 4         | 0.85%   |
| MSI MS-7D43        | 3         | 0.64%   |
| HP EliteDesk       | 3         | 0.64%   |
| HP 255             | 3         | 0.64%   |
| Google Snappy      | 3         | 0.64%   |
| Dell Vostro        | 3         | 0.64%   |
| Dell PowerEdge     | 3         | 0.64%   |
| ASUS TUF           | 3         | 0.64%   |
| ASUS ASUS          | 3         | 0.64%   |
| Rockchip RK3318    | 2         | 0.42%   |
| Radxa ROCK         | 2         | 0.42%   |
| MSI MS-7D46        | 2         | 0.42%   |
| MSI MS-7D25        | 2         | 0.42%   |
| MSI MS-7C52        | 2         | 0.42%   |
| MSI MS-7817        | 2         | 0.42%   |
| MSI MS-7721        | 2         | 0.42%   |
| Lenovo Yoga        | 2         | 0.42%   |
| Lenovo ThinkBook   | 2         | 0.42%   |
| HP Stream          | 2         | 0.42%   |
| HP 250             | 2         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 46        | 9.77%   |
| 2020    | 39        | 8.28%   |
| 2014    | 37        | 7.86%   |
| 2022    | 34        | 7.22%   |
| 2018    | 31        | 6.58%   |
| 2016    | 31        | 6.58%   |
| 2013    | 31        | 6.58%   |
| 2017    | 30        | 6.37%   |
| 2012    | 27        | 5.73%   |
| 2015    | 26        | 5.52%   |
| 2011    | 26        | 5.52%   |
| 2010    | 25        | 5.31%   |
| 2019    | 23        | 4.88%   |
| 2009    | 18        | 3.82%   |
| 2007    | 14        | 2.97%   |
| 2008    | 13        | 2.76%   |
| Unknown | 10        | 2.12%   |
| 2023    | 4         | 0.85%   |
| 2006    | 4         | 0.85%   |
| 2005    | 2         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 261       | 55.41%  |
| Desktop        | 164       | 34.82%  |
| System on chip | 11        | 2.34%   |
| Mini pc        | 8         | 1.7%    |
| All in one     | 8         | 1.7%    |
| Server         | 8         | 1.7%    |
| Convertible    | 7         | 1.49%   |
| Tablet         | 4         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 435       | 92.36%  |
| Enabled  | 36        | 7.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 459       | 97.45%  |
| Yes  | 12        | 2.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 125       | 26.48%  |
| 4.01-8.0        | 116       | 24.58%  |
| 16.01-24.0      | 79        | 16.74%  |
| 8.01-16.0       | 58        | 12.29%  |
| 32.01-64.0      | 39        | 8.26%   |
| 1.01-2.0        | 20        | 4.24%   |
| 64.01-256.0     | 13        | 2.75%   |
| 24.01-32.0      | 9         | 1.91%   |
| 2.01-3.0        | 8         | 1.69%   |
| 0.51-1.0        | 4         | 0.85%   |
| More than 256.0 | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 206       | 41.87%  |
| 2.01-3.0   | 123       | 25%     |
| 3.01-4.0   | 51        | 10.37%  |
| 4.01-8.0   | 48        | 9.76%   |
| 0.51-1.0   | 38        | 7.72%   |
| 8.01-16.0  | 20        | 4.07%   |
| 0.01-0.5   | 3         | 0.61%   |
| 16.01-24.0 | 2         | 0.41%   |
| 24.01-32.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 293       | 61.55%  |
| 2      | 112       | 23.53%  |
| 3      | 34        | 7.14%   |
| 4      | 18        | 3.78%   |
| 5      | 7         | 1.47%   |
| 6      | 6         | 1.26%   |
| 7      | 2         | 0.42%   |
| 0      | 2         | 0.42%   |
| 10     | 1         | 0.21%   |
| 9      | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 286       | 60.59%  |
| Yes       | 186       | 39.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 389       | 82.59%  |
| No        | 82        | 17.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 350       | 74.15%  |
| No        | 122       | 25.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 58.47%  |
| No        | 196       | 41.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 77        | 16.28%  |
| Germany     | 76        | 16.07%  |
| France      | 58        | 12.26%  |
| Italy       | 31        | 6.55%   |
| Brazil      | 19        | 4.02%   |
| Russia      | 17        | 3.59%   |
| UK          | 16        | 3.38%   |
| Canada      | 14        | 2.96%   |
| Netherlands | 12        | 2.54%   |
| Sweden      | 11        | 2.33%   |
| Poland      | 11        | 2.33%   |
| Czechia     | 9         | 1.9%    |
| Spain       | 8         | 1.69%   |
| Mexico      | 7         | 1.48%   |
| India       | 7         | 1.48%   |
| Belgium     | 6         | 1.27%   |
| Australia   | 6         | 1.27%   |
| Switzerland | 5         | 1.06%   |
| Argentina   | 5         | 1.06%   |
| Turkey      | 4         | 0.85%   |
| Iran        | 4         | 0.85%   |
| Colombia    | 4         | 0.85%   |
| Belarus     | 4         | 0.85%   |
| Venezuela   | 3         | 0.63%   |
| Portugal    | 3         | 0.63%   |
| Malaysia    | 3         | 0.63%   |
| Japan       | 3         | 0.63%   |
| Indonesia   | 3         | 0.63%   |
| Hungary     | 3         | 0.63%   |
| Greece      | 3         | 0.63%   |
| Denmark     | 3         | 0.63%   |
| China       | 3         | 0.63%   |
| Austria     | 3         | 0.63%   |
| Vietnam     | 2         | 0.42%   |
| Taiwan      | 2         | 0.42%   |
| Slovenia    | 2         | 0.42%   |
| Romania     | 2         | 0.42%   |
| Norway      | 2         | 0.42%   |
| Israel      | 2         | 0.42%   |
| Finland     | 2         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 9         | 1.86%   |
| Munich           | 7         | 1.45%   |
| Berlin           | 7         | 1.45%   |
| Milan            | 6         | 1.24%   |
| Stuttgart        | 5         | 1.03%   |
| Melbourne        | 5         | 1.03%   |
| Warsaw           | 4         | 0.83%   |
| Hamburg          | 4         | 0.83%   |
| Uppsala          | 3         | 0.62%   |
| St Petersburg    | 3         | 0.62%   |
| Springfield      | 3         | 0.62%   |
| Nykvarn          | 3         | 0.62%   |
| North Hills      | 3         | 0.62%   |
| Moscow           | 3         | 0.62%   |
| Kuala Lumpur     | 3         | 0.62%   |
| Hanover          | 3         | 0.62%   |
| Copenhagen       | 3         | 0.62%   |
| Bordeaux         | 3         | 0.62%   |
| Biella           | 3         | 0.62%   |
| Ankara           | 3         | 0.62%   |
| Washington       | 2         | 0.41%   |
| Vicenza          | 2         | 0.41%   |
| Västerås       | 2         | 0.41%   |
| Toronto          | 2         | 0.41%   |
| Tehran           | 2         | 0.41%   |
| Schwerte         | 2         | 0.41%   |
| Santiago de Cali | 2         | 0.41%   |
| Rochester        | 2         | 0.41%   |
| Rio de Janeiro   | 2         | 0.41%   |
| Puebla City      | 2         | 0.41%   |
| Pilsen           | 2         | 0.41%   |
| Oklahoma City    | 2         | 0.41%   |
| Oberhausen       | 2         | 0.41%   |
| Muncie           | 2         | 0.41%   |
| Mumbai           | 2         | 0.41%   |
| Minsk            | 2         | 0.41%   |
| Mexico City      | 2         | 0.41%   |
| London           | 2         | 0.41%   |
| Leipzig          | 2         | 0.41%   |
| Lavras           | 2         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 105       | 130    | 15.46%  |
| WDC                         | 95        | 135    | 13.99%  |
| Seagate                     | 76        | 99     | 11.19%  |
| Unknown                     | 51        | 60     | 7.51%   |
| Kingston                    | 38        | 46     | 5.6%    |
| SanDisk                     | 35        | 42     | 5.15%   |
| Toshiba                     | 32        | 35     | 4.71%   |
| Hitachi                     | 25        | 34     | 3.68%   |
| Crucial                     | 25        | 31     | 3.68%   |
| SK hynix                    | 19        | 21     | 2.8%    |
| Intel                       | 16        | 16     | 2.36%   |
| HGST                        | 14        | 19     | 2.06%   |
| China                       | 11        | 12     | 1.62%   |
| A-DATA Technology           | 11        | 14     | 1.62%   |
| PNY                         | 10        | 10     | 1.47%   |
| Micron Technology           | 8         | 9      | 1.18%   |
| Unknown                     | 7         | 7      | 1.03%   |
| Phison                      | 6         | 13     | 0.88%   |
| SPCC                        | 5         | 5      | 0.74%   |
| ASMT                        | 5         | 11     | 0.74%   |
| Transcend                   | 4         | 5      | 0.59%   |
| Patriot                     | 4         | 4      | 0.59%   |
| TO Exter                    | 3         | 4      | 0.44%   |
| Silicon Motion              | 3         | 3      | 0.44%   |
| Kingston Technology Company | 3         | 5      | 0.44%   |
| Intenso                     | 3         | 3      | 0.44%   |
| Fujitsu                     | 3         | 3      | 0.44%   |
| USB3.0                      | 2         | 4      | 0.29%   |
| TEXTORM                     | 2         | 2      | 0.29%   |
| Realtek Semiconductor       | 2         | 2      | 0.29%   |
| Phison Electronics          | 2         | 4      | 0.29%   |
| OCZ                         | 2         | 2      | 0.29%   |
| Netac                       | 2         | 2      | 0.29%   |
| Maxtor                      | 2         | 2      | 0.29%   |
| LITEON                      | 2         | 2      | 0.29%   |
| KIOXIA                      | 2         | 2      | 0.29%   |
| Hewlett-Packard             | 2         | 4      | 0.29%   |
| Gigabyte Technology         | 2         | 2      | 0.29%   |
| FORESEE                     | 2         | 3      | 0.29%   |
| Corsair                     | 2         | 2      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 11        | 1.47%   |
| Kingston SA400S37480G 480GB SSD                     | 8         | 1.07%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.93%   |
| Kingston SA400S37240G 240GB SSD                     | 7         | 0.93%   |
| Crucial CT480BX500SSD1 480GB                        | 7         | 0.93%   |
| Unknown                                             | 7         | 0.93%   |
| Unknown MMC Card  32GB                              | 6         | 0.8%    |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 0.67%   |
| Crucial CT500MX500SSD1 500GB                        | 5         | 0.67%   |
| Toshiba DT01ACA200 2TB                              | 4         | 0.53%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 0.53%   |
| Seagate ST1000LM048-2E7172 1TB                      | 4         | 0.53%   |
| SanDisk DF4064  64GB                                | 4         | 0.53%   |
| Unknown SD/MMC/MS PRO 64GB                          | 3         | 0.4%    |
| Unknown MMC Card  128GB                             | 3         | 0.4%    |
| Unknown DF4016  16GB                                | 3         | 0.4%    |
| Toshiba MQ04ABF100 1TB                              | 3         | 0.4%    |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.4%    |
| Toshiba HDWD110 1TB                                 | 3         | 0.4%    |
| Toshiba DT01ACA100 1TB                              | 3         | 0.4%    |
| TO Exter nal USB 3.0 1TB                            | 3         | 0.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 0.4%    |
| Seagate ST500LM000-1EJ162 500GB                     | 3         | 0.4%    |
| Seagate ST4000DM004-2CV104 4TB                      | 3         | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB                      | 3         | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB                      | 3         | 0.4%    |
| SanDisk SDSSDA240G 240GB                            | 3         | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.4%    |
| Samsung SSD 870 QVO 1TB                             | 3         | 0.4%    |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.4%    |
| Samsung SSD 840 Series 120GB                        | 3         | 0.4%    |
| Samsung NVMe SSD Drive 256GB                        | 3         | 0.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 0.4%    |
| Samsung HM321HI 320GB                               | 3         | 0.4%    |
| PNY CS900 120GB SSD                                 | 3         | 0.4%    |
| Hitachi HDS721050CLA362 500GB                       | 3         | 0.4%    |
| HGST HTS541010A9E680 1TB                            | 3         | 0.4%    |
| China SATA SSD 120GB                                | 3         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 76        | 113    | 30.65%  |
| Seagate             | 76        | 97     | 30.65%  |
| Toshiba             | 28        | 31     | 11.29%  |
| Hitachi             | 25        | 34     | 10.08%  |
| HGST                | 14        | 19     | 5.65%   |
| Samsung Electronics | 11        | 15     | 4.44%   |
| ASMT                | 4         | 7      | 1.61%   |
| Unknown             | 3         | 4      | 1.21%   |
| Fujitsu             | 3         | 3      | 1.21%   |
| USB3.0              | 2         | 4      | 0.81%   |
| SSK                 | 1         | 1      | 0.4%    |
| PHD 3.0             | 1         | 1      | 0.4%    |
| Maxtor              | 1         | 1      | 0.4%    |
| LaCie               | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.4%    |
| ASMedia             | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 67     | 22.98%  |
| Kingston            | 32        | 37     | 13.62%  |
| Crucial             | 23        | 29     | 9.79%   |
| SanDisk             | 19        | 24     | 8.09%   |
| WDC                 | 11        | 12     | 4.68%   |
| China               | 11        | 12     | 4.68%   |
| A-DATA Technology   | 11        | 14     | 4.68%   |
| PNY                 | 9         | 9      | 3.83%   |
| Intel               | 6         | 6      | 2.55%   |
| SPCC                | 5         | 5      | 2.13%   |
| Transcend           | 4         | 4      | 1.7%    |
| Patriot             | 4         | 4      | 1.7%    |
| Micron Technology   | 4         | 5      | 1.7%    |
| Toshiba             | 3         | 3      | 1.28%   |
| TO Exter            | 3         | 4      | 1.28%   |
| Intenso             | 3         | 3      | 1.28%   |
| TEXTORM             | 2         | 2      | 0.85%   |
| SK hynix            | 2         | 2      | 0.85%   |
| OCZ                 | 2         | 2      | 0.85%   |
| Netac               | 2         | 2      | 0.85%   |
| LITEON              | 2         | 2      | 0.85%   |
| FORESEE             | 2         | 3      | 0.85%   |
| Apacer              | 2         | 2      | 0.85%   |
| Veno                | 1         | 1      | 0.43%   |
| Vaseky              | 1         | 1      | 0.43%   |
| Team                | 1         | 2      | 0.43%   |
| SSSTC               | 1         | 1      | 0.43%   |
| ShiJi               | 1         | 1      | 0.43%   |
| Maxtor              | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| Linux               | 1         | 1      | 0.43%   |
| KingSpec            | 1         | 1      | 0.43%   |
| KingFast            | 1         | 1      | 0.43%   |
| KingDian            | 1         | 1      | 0.43%   |
| Kimtigo             | 1         | 1      | 0.43%   |
| JMicron Technology  | 1         | 1      | 0.43%   |
| INNOVATION IT       | 1         | 1      | 0.43%   |
| EVM                 | 1         | 1      | 0.43%   |
| Corsair             | 1         | 1      | 0.43%   |
| ASMT                | 1         | 4      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 206       | 276    | 33.88%  |
| HDD     | 205       | 333    | 33.72%  |
| NVMe    | 130       | 161    | 21.38%  |
| MMC     | 58        | 68     | 9.54%   |
| Unknown | 9         | 10     | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 337       | 570    | 60.61%  |
| NVMe | 130       | 161    | 23.38%  |
| MMC  | 58        | 68     | 10.43%  |
| SAS  | 31        | 49     | 5.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 265       | 376    | 59.28%  |
| 0.51-1.0   | 113       | 139    | 25.28%  |
| 1.01-2.0   | 39        | 50     | 8.72%   |
| 3.01-4.0   | 18        | 29     | 4.03%   |
| 2.01-3.0   | 5         | 6      | 1.12%   |
| 4.01-10.0  | 5         | 6      | 1.12%   |
| 10.01-20.0 | 2         | 3      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 130       | 27.2%   |
| 251-500        | 113       | 23.64%  |
| 501-1000       | 61        | 12.76%  |
| 1001-2000      | 42        | 8.79%   |
| 1-20           | 36        | 7.53%   |
| 51-100         | 35        | 7.32%   |
| 21-50          | 24        | 5.02%   |
| More than 3000 | 23        | 4.81%   |
| 2001-3000      | 13        | 2.72%   |
| Unknown        | 1         | 0.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 176       | 36.36%  |
| 21-50          | 89        | 18.39%  |
| 101-250        | 68        | 14.05%  |
| 51-100         | 52        | 10.74%  |
| 251-500        | 42        | 8.68%   |
| 501-1000       | 26        | 5.37%   |
| 1001-2000      | 14        | 2.89%   |
| More than 3000 | 8         | 1.65%   |
| 2001-3000      | 8         | 1.65%   |
| Unknown        | 1         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB                           | 2         | 2      | 2.78%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 2      | 2.78%   |
| Seagate ST1000DM003-1ER162 1TB                   | 2         | 2      | 2.78%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 1.39%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                 | 1         | 1      | 1.39%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 1         | 1      | 1.39%   |
| WDC WD3200AAKS-00L9A0 320GB                      | 1         | 1      | 1.39%   |
| WDC WD2500AAKS-00VSA0 250GB                      | 1         | 1      | 1.39%   |
| WDC WD20EFRX-68AX9N0 2TB                         | 1         | 1      | 1.39%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 1.39%   |
| WDC WD2002FYPS-02W3B0 2TB                        | 1         | 1      | 1.39%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.39%   |
| WDC WD10EZEX-60ZF5A0 1TB                         | 1         | 1      | 1.39%   |
| WDC WD10EAVS-00D7B1 1TB                          | 1         | 1      | 1.39%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1         | 1      | 1.39%   |
| WDC WD1003FBYX-01Y7B1 1TB                        | 1         | 1      | 1.39%   |
| WDC WD1001FALS-40Y6A0 1TB                        | 1         | 2      | 1.39%   |
| Toshiba MK1246GSX 120GB                          | 1         | 1      | 1.39%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 1.39%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 1.39%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 1.39%   |
| Seagate ST9250410AS 250GB                        | 1         | 1      | 1.39%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 1.39%   |
| Seagate ST3750840AS 752GB                        | 1         | 1      | 1.39%   |
| Seagate ST3250318AS 250GB                        | 1         | 2      | 1.39%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.39%   |
| Seagate ST2000DM001-1CH164 2TB                   | 1         | 1      | 1.39%   |
| Seagate ST1000LM 035-1RK172 1TB                  | 1         | 1      | 1.39%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 1.39%   |
| Samsung Electronics SSD PM810 FDE 2.5 128GB      | 1         | 1      | 1.39%   |
| Samsung Electronics SP2514N 250GB                | 1         | 1      | 1.39%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 1.39%   |
| Samsung Electronics HM321HI 320GB                | 1         | 2      | 1.39%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 1.39%   |
| Samsung Electronics HD250HJ 250GB                | 1         | 1      | 1.39%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 1.39%   |
| PNY 69D03094-T 40GB SSD                          | 1         | 1      | 1.39%   |
| Maxtor STM3160215AS 160GB                        | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 24.29%  |
| WDC                 | 13        | 15     | 18.57%  |
| Hitachi             | 8         | 9      | 11.43%  |
| Samsung Electronics | 6         | 8      | 8.57%   |
| Toshiba             | 3         | 3      | 4.29%   |
| Kingston            | 3         | 4      | 4.29%   |
| Intel               | 3         | 3      | 4.29%   |
| HGST                | 3         | 5      | 4.29%   |
| Fujitsu             | 3         | 3      | 4.29%   |
| SSSTC               | 1         | 1      | 1.43%   |
| SanDisk             | 1         | 1      | 1.43%   |
| PNY                 | 1         | 1      | 1.43%   |
| Maxtor              | 1         | 1      | 1.43%   |
| LITEON              | 1         | 1      | 1.43%   |
| JMicron Technology  | 1         | 1      | 1.43%   |
| Hewlett-Packard     | 1         | 1      | 1.43%   |
| Crucial             | 1         | 1      | 1.43%   |
| China               | 1         | 1      | 1.43%   |
| ASMT                | 1         | 4      | 1.43%   |
| Unknown             | 1         | 1      | 1.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 32.69%  |
| WDC                 | 11        | 13     | 21.15%  |
| Hitachi             | 8         | 9      | 15.38%  |
| Samsung Electronics | 4         | 6      | 7.69%   |
| Toshiba             | 3         | 3      | 5.77%   |
| HGST                | 3         | 5      | 5.77%   |
| Fujitsu             | 3         | 3      | 5.77%   |
| Maxtor              | 1         | 1      | 1.92%   |
| Hewlett-Packard     | 1         | 1      | 1.92%   |
| ASMT                | 1         | 4      | 1.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 63     | 74.24%  |
| SSD  | 17        | 19     | 25.76%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 253       | 388    | 48.37%  |
| Detected | 206       | 378    | 39.39%  |
| Malfunc  | 64        | 82     | 12.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 313       | 56.19%  |
| AMD                          | 88        | 15.8%   |
| Samsung Electronics          | 46        | 8.26%   |
| SanDisk                      | 18        | 3.23%   |
| SK hynix                     | 17        | 3.05%   |
| Kingston Technology Company  | 11        | 1.97%   |
| Phison Electronics           | 10        | 1.8%    |
| ASMedia Technology           | 7         | 1.26%   |
| Silicon Motion               | 6         | 1.08%   |
| JMicron Technology           | 6         | 1.08%   |
| Nvidia                       | 4         | 0.72%   |
| VIA Technologies             | 3         | 0.54%   |
| Silicon Image                | 3         | 0.54%   |
| Realtek Semiconductor        | 3         | 0.54%   |
| Micron/Crucial Technology    | 3         | 0.54%   |
| Micron Technology            | 3         | 0.54%   |
| Marvell Technology Group     | 3         | 0.54%   |
| KIOXIA                       | 2         | 0.36%   |
| Union Memory (Shenzhen)      | 1         | 0.18%   |
| Toshiba America Info Systems | 1         | 0.18%   |
| Shenzhen Longsys Electronics | 1         | 0.18%   |
| LSI Logic / Symbios Logic    | 1         | 0.18%   |
| Lenovo                       | 1         | 0.18%   |
| INNOGRIT                     | 1         | 0.18%   |
| Broadcom / LSI               | 1         | 0.18%   |
| Biwin Storage Technology     | 1         | 0.18%   |
| Apple                        | 1         | 0.18%   |
| ADATA Technology             | 1         | 0.18%   |
| Adaptec                      | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 66        | 10.28%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 3.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 19        | 2.96%   |
| Samsung NVMe SSD Controller 980                                                  | 17        | 2.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 2.18%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 13        | 2.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 1.87%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 11        | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 1.71%   |
| AMD 400 Series Chipset SATA Controller                                           | 11        | 1.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 10        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 10        | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 1.25%   |
| Intel SATA Controller [RAID mode]                                                | 8         | 1.25%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 8         | 1.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8         | 1.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 7         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 7         | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                           | 7         | 1.09%   |
| Intel Tiger Lake-LP SATA Controller                                              | 6         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 0.93%   |
| AMD FCH SATA Controller D                                                        | 6         | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                  | 5         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 344       | 60.56%  |
| NVMe | 130       | 22.89%  |
| IDE  | 55        | 9.68%   |
| RAID | 37        | 6.51%   |
| SAS  | 1         | 0.18%   |
| SCSI | 1         | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 353       | 74.95%  |
| AMD    | 107       | 22.72%  |
| ARM    | 11        | 2.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz           | 8         | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 8         | 1.69%   |
| ARM Processor                               | 8         | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 1.27%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 6         | 1.27%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5         | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 0.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 0.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 0.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 0.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 4         | 0.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 0.85%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 4         | 0.85%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 0.85%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 0.85%   |
| Intel 12th Gen Core i7-1260P                | 4         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 0.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3         | 0.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3         | 0.64%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 3         | 0.64%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 0.64%   |
| Intel Celeron CPU N3160 @ 1.60GHz           | 3         | 0.64%   |
| Intel Celeron 3205U @ 1.50GHz               | 3         | 0.64%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 0.64%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 3         | 0.64%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 0.64%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3         | 0.64%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 3         | 0.64%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3         | 0.64%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 3         | 0.64%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 2         | 0.42%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 2         | 0.42%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 2         | 0.42%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2         | 0.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.42%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 95        | 20.13%  |
| Intel Celeron           | 60        | 12.71%  |
| Other                   | 49        | 10.38%  |
| Intel Core i7           | 47        | 9.96%   |
| Intel Core i3           | 35        | 7.42%   |
| AMD Ryzen 5             | 30        | 6.36%   |
| Intel Core 2 Duo        | 18        | 3.81%   |
| AMD Ryzen 7             | 15        | 3.18%   |
| Intel Xeon              | 11        | 2.33%   |
| Intel Pentium           | 10        | 2.12%   |
| Intel Atom              | 9         | 1.91%   |
| AMD A8                  | 9         | 1.91%   |
| Intel Core 2 Quad       | 5         | 1.06%   |
| Intel Core 2            | 5         | 1.06%   |
| AMD Ryzen 9             | 5         | 1.06%   |
| AMD A6                  | 5         | 1.06%   |
| Intel Pentium Dual-Core | 4         | 0.85%   |
| AMD Ryzen 3             | 4         | 0.85%   |
| AMD FX                  | 4         | 0.85%   |
| Intel Pentium Dual      | 3         | 0.64%   |
| Intel Genuine           | 3         | 0.64%   |
| ARM Allwinner           | 3         | 0.64%   |
| AMD Ryzen 7 PRO         | 3         | 0.64%   |
| AMD Ryzen 5 PRO         | 3         | 0.64%   |
| AMD Phenom II X4        | 3         | 0.64%   |
| AMD E1                  | 3         | 0.64%   |
| AMD Athlon II X2        | 3         | 0.64%   |
| AMD A10                 | 3         | 0.64%   |
| Intel Pentium Silver    | 2         | 0.42%   |
| Intel Pentium 4         | 2         | 0.42%   |
| AMD Ryzen Threadripper  | 2         | 0.42%   |
| AMD E2                  | 2         | 0.42%   |
| AMD Athlon 64 X2        | 2         | 0.42%   |
| AMD Athlon              | 2         | 0.42%   |
| AMD A4                  | 2         | 0.42%   |
| Intel Xeon Gold         | 1         | 0.21%   |
| Intel Core m3           | 1         | 0.21%   |
| Intel Core 2 Extreme    | 1         | 0.21%   |
| Intel Celeron Dual-Core | 1         | 0.21%   |
| AMD Turion II Neo       | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 209       | 44.19%  |
| 4       | 162       | 34.25%  |
| 6       | 41        | 8.67%   |
| 8       | 27        | 5.71%   |
| 12      | 10        | 2.11%   |
| 1       | 6         | 1.27%   |
| 10      | 4         | 0.85%   |
| Unknown | 4         | 0.85%   |
| 16      | 3         | 0.63%   |
| 64      | 2         | 0.42%   |
| 14      | 2         | 0.42%   |
| 3       | 2         | 0.42%   |
| 24      | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 464       | 98.51%  |
| Unknown | 4         | 0.85%   |
| 2       | 3         | 0.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 273       | 57.96%  |
| 1       | 194       | 41.19%  |
| Unknown | 4         | 0.85%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 466       | 98.94%  |
| Unknown        | 4         | 0.85%   |
| 64-bit         | 1         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 167       | 35.16%  |
| 0x806c1    | 17        | 3.58%   |
| 0x306c3    | 16        | 3.37%   |
| 0x306a9    | 15        | 3.16%   |
| 0x406e3    | 11        | 2.32%   |
| 0x206a7    | 11        | 2.32%   |
| 0x506c9    | 10        | 2.11%   |
| 0x1067a    | 9         | 1.89%   |
| 0x506e3    | 8         | 1.68%   |
| 0x406c4    | 8         | 1.68%   |
| 0x306d4    | 8         | 1.68%   |
| 0x706a8    | 7         | 1.47%   |
| 0x08608103 | 7         | 1.47%   |
| 0x906ea    | 6         | 1.26%   |
| 0x806ec    | 6         | 1.26%   |
| 0x806e9    | 6         | 1.26%   |
| 0x406c3    | 6         | 1.26%   |
| 0x20655    | 6         | 1.26%   |
| 0x106e5    | 6         | 1.26%   |
| 0x706a1    | 5         | 1.05%   |
| 0x30678    | 5         | 1.05%   |
| 0x0800820d | 5         | 1.05%   |
| 0xa0652    | 4         | 0.84%   |
| 0x906a3    | 4         | 0.84%   |
| 0x806ea    | 4         | 0.84%   |
| 0x6fd      | 4         | 0.84%   |
| 0x6fb      | 4         | 0.84%   |
| 0x6f6      | 4         | 0.84%   |
| 0x40651    | 4         | 0.84%   |
| 0x10676    | 4         | 0.84%   |
| 0x08701021 | 4         | 0.84%   |
| 0x08108109 | 4         | 0.84%   |
| 0x07030105 | 4         | 0.84%   |
| 0x010000c8 | 4         | 0.84%   |
| 0xb0671    | 3         | 0.63%   |
| 0x906e9    | 3         | 0.63%   |
| 0x90672    | 3         | 0.63%   |
| 0x20652    | 3         | 0.63%   |
| 0x0a50000c | 3         | 0.63%   |
| 0x05000119 | 3         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 44        | 9.32%   |
| Haswell          | 34        | 7.2%    |
| Unknown          | 34        | 7.2%    |
| SandyBridge      | 31        | 6.57%   |
| Skylake          | 29        | 6.14%   |
| Silvermont       | 29        | 6.14%   |
| IvyBridge        | 27        | 5.72%   |
| Penryn           | 25        | 5.3%    |
| TigerLake        | 21        | 4.45%   |
| Zen 2            | 19        | 4.03%   |
| Core             | 16        | 3.39%   |
| Westmere         | 14        | 2.97%   |
| Goldmont plus    | 14        | 2.97%   |
| Zen+             | 13        | 2.75%   |
| Zen 3            | 13        | 2.75%   |
| Goldmont         | 13        | 2.75%   |
| Broadwell        | 11        | 2.33%   |
| CometLake        | 10        | 2.12%   |
| K10              | 9         | 1.91%   |
| Alderlake Hybrid | 9         | 1.91%   |
| Nehalem          | 8         | 1.69%   |
| Puma             | 7         | 1.48%   |
| Piledriver       | 7         | 1.48%   |
| Excavator        | 6         | 1.27%   |
| Zen              | 5         | 1.06%   |
| Icelake          | 4         | 0.85%   |
| Bobcat           | 4         | 0.85%   |
| Steamroller      | 3         | 0.64%   |
| K10 Llano        | 3         | 0.64%   |
| Bonnell          | 3         | 0.64%   |
| NetBurst         | 2         | 0.42%   |
| K8 Hammer        | 2         | 0.42%   |
| Jaguar           | 2         | 0.42%   |
| Tremont          | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 286       | 54.89%  |
| Nvidia                     | 115       | 22.07%  |
| AMD                        | 113       | 21.69%  |
| ASPEED Technology          | 4         | 0.77%   |
| Matrox Electronics Systems | 3         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 4.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 3.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 3.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 2.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 2.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 2.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.05%   |
| Intel HD Graphics 500                                                                    | 11        | 2.05%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 9         | 1.68%   |
| Intel HD Graphics 530                                                                    | 9         | 1.68%   |
| AMD Lucienne                                                                             | 9         | 1.68%   |
| Intel HD Graphics 620                                                                    | 8         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.49%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.12%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 6         | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.93%   |
| AMD Renoir                                                                               | 5         | 0.93%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.75%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.75%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 0.75%   |
| Intel UHD Graphics 620                                                                   | 4         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.75%   |
| Intel HD Graphics 630                                                                    | 4         | 0.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.75%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 0.75%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.56%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.56%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 234       | 49.68%  |
| 1 x AMD         | 88        | 18.68%  |
| 1 x Nvidia      | 71        | 15.07%  |
| Intel + Nvidia  | 33        | 7.01%   |
| Other           | 14        | 2.97%   |
| Intel + AMD     | 9         | 1.91%   |
| AMD + Nvidia    | 8         | 1.7%    |
| 2 x AMD         | 7         | 1.49%   |
| Nvidia + ASPEED | 3         | 0.64%   |
| 1 x Matrox      | 2         | 0.42%   |
| 1 x ASPEED      | 1         | 0.21%   |
| AMD + Matrox    | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 383       | 81.14%  |
| Proprietary | 65        | 13.77%  |
| Unknown     | 24        | 5.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 331       | 69.68%  |
| 0.01-0.5   | 48        | 10.11%  |
| 0.51-1.0   | 31        | 6.53%   |
| 1.01-2.0   | 30        | 6.32%   |
| 3.01-4.0   | 16        | 3.37%   |
| 7.01-8.0   | 8         | 1.68%   |
| 8.01-16.0  | 5         | 1.05%   |
| 5.01-6.0   | 3         | 0.63%   |
| 2.01-3.0   | 2         | 0.42%   |
| 32.01-64.0 | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 66        | 13.55%  |
| Samsung Electronics     | 52        | 10.68%  |
| BOE                     | 46        | 9.45%   |
| LG Display              | 44        | 9.03%   |
| Dell                    | 40        | 8.21%   |
| Chimei Innolux          | 38        | 7.8%    |
| Hewlett-Packard         | 17        | 3.49%   |
| Goldstar                | 17        | 3.49%   |
| Acer                    | 14        | 2.87%   |
| AOC                     | 12        | 2.46%   |
| Lenovo                  | 11        | 2.26%   |
| ViewSonic               | 9         | 1.85%   |
| Iiyama                  | 8         | 1.64%   |
| Chi Mei Optoelectronics | 8         | 1.64%   |
| Apple                   | 8         | 1.64%   |
| Philips                 | 7         | 1.44%   |
| BenQ                    | 7         | 1.44%   |
| Ancor Communications    | 7         | 1.44%   |
| PANDA                   | 5         | 1.03%   |
| InfoVision              | 5         | 1.03%   |
| Sharp                   | 4         | 0.82%   |
| RTK                     | 4         | 0.82%   |
| LG Philips              | 4         | 0.82%   |
| Sony                    | 3         | 0.62%   |
| KDC                     | 3         | 0.62%   |
| Fujitsu Siemens         | 3         | 0.62%   |
| Vizio                   | 2         | 0.41%   |
| Unknown                 | 2         | 0.41%   |
| Toshiba                 | 2         | 0.41%   |
| Envision Peripherals    | 2         | 0.41%   |
| Eizo                    | 2         | 0.41%   |
| ASUSTek Computer        | 2         | 0.41%   |
| Unknown                 | 2         | 0.41%   |
| ___                     | 1         | 0.21%   |
| Vita                    | 1         | 0.21%   |
| Vestel Elektronik       | 1         | 0.21%   |
| UGD                     | 1         | 0.21%   |
| TEO                     | 1         | 0.21%   |
| Tech Concepts           | 1         | 0.21%   |
| TCL                     | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.6%    |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 2         | 0.4%    |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 2         | 0.4%    |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                     | 2         | 0.4%    |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                       | 2         | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.4%    |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.4%    |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.4%    |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.4%    |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 2         | 0.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.4%    |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 2         | 0.4%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.4%    |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 0.4%    |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                      | 2         | 0.4%    |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch               | 2         | 0.4%    |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch         | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.4%    |
| BOE LCD Monitor BOE092E 1920x1080 310x173mm 14.0-inch                    | 2         | 0.4%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.4%    |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.4%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch            | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.4%    |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                      | 2         | 0.4%    |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2         | 0.4%    |
| Unknown                                                                  | 2         | 0.4%    |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                       | 1         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 204       | 43.22%  |
| 1366x768 (WXGA)    | 94        | 19.92%  |
| 1600x900 (HD+)     | 29        | 6.14%   |
| 2560x1440 (QHD)    | 19        | 4.03%   |
| 3840x2160 (4K)     | 17        | 3.6%    |
| 1280x1024 (SXGA)   | 17        | 3.6%    |
| 1920x1200 (WUXGA)  | 16        | 3.39%   |
| 1280x800 (WXGA)    | 15        | 3.18%   |
| 1440x900 (WXGA+)   | 14        | 2.97%   |
| 1680x1050 (WSXGA+) | 8         | 1.69%   |
| 1024x768 (XGA)     | 5         | 1.06%   |
| 1360x768           | 4         | 0.85%   |
| 3840x1080          | 3         | 0.64%   |
| 3440x1440          | 3         | 0.64%   |
| 2560x1600          | 3         | 0.64%   |
| 2160x1440          | 3         | 0.64%   |
| 1600x1200          | 3         | 0.64%   |
| 3840x1600          | 2         | 0.42%   |
| 2560x1080          | 2         | 0.42%   |
| 1024x600           | 2         | 0.42%   |
| Unknown            | 2         | 0.42%   |
| 2880x1800          | 1         | 0.21%   |
| 2288x1287          | 1         | 0.21%   |
| 2048x1152          | 1         | 0.21%   |
| 1920x540           | 1         | 0.21%   |
| 1920x515           | 1         | 0.21%   |
| 1366x912           | 1         | 0.21%   |
| 1280x720 (HD)      | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 118       | 23.98%  |
| 14      | 49        | 9.96%   |
| 13      | 42        | 8.54%   |
| 23      | 38        | 7.72%   |
| 27      | 33        | 6.71%   |
| 24      | 31        | 6.3%    |
| 17      | 30        | 6.1%    |
| 21      | 23        | 4.67%   |
| Unknown | 17        | 3.46%   |
| 19      | 16        | 3.25%   |
| 18      | 12        | 2.44%   |
| 12      | 12        | 2.44%   |
| 20      | 11        | 2.24%   |
| 11      | 11        | 2.24%   |
| 31      | 7         | 1.42%   |
| 16      | 6         | 1.22%   |
| 26      | 5         | 1.02%   |
| 34      | 4         | 0.81%   |
| 22      | 4         | 0.81%   |
| 25      | 3         | 0.61%   |
| 84      | 2         | 0.41%   |
| 72      | 2         | 0.41%   |
| 54      | 2         | 0.41%   |
| 40      | 2         | 0.41%   |
| 37      | 2         | 0.41%   |
| 32      | 2         | 0.41%   |
| 10      | 2         | 0.41%   |
| 142     | 1         | 0.2%    |
| 49      | 1         | 0.2%    |
| 42      | 1         | 0.2%    |
| 30      | 1         | 0.2%    |
| 29      | 1         | 0.2%    |
| 6       | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 203       | 42.03%  |
| 501-600        | 99        | 20.5%   |
| 401-500        | 60        | 12.42%  |
| 201-300        | 42        | 8.7%    |
| 351-400        | 29        | 6%      |
| Unknown        | 17        | 3.52%   |
| 601-700        | 13        | 2.69%   |
| 701-800        | 6         | 1.24%   |
| 801-900        | 4         | 0.83%   |
| 1501-2000      | 4         | 0.83%   |
| 1001-1500      | 3         | 0.62%   |
| More than 2000 | 1         | 0.21%   |
| 101-200        | 1         | 0.21%   |
| 901-1000       | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 346       | 76.55%  |
| 16/10   | 58        | 12.83%  |
| 5/4     | 13        | 2.88%   |
| Unknown | 11        | 2.43%   |
| 4/3     | 9         | 1.99%   |
| 21/9    | 6         | 1.33%   |
| 3/2     | 5         | 1.11%   |
| 6/5     | 1         | 0.22%   |
| 32/9    | 1         | 0.22%   |
| 3.73    | 1         | 0.22%   |
| 1.00    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 117       | 24.02%  |
| 81-90          | 78        | 16.02%  |
| 201-250        | 78        | 16.02%  |
| 151-200        | 37        | 7.6%    |
| 301-350        | 36        | 7.39%   |
| 141-150        | 18        | 3.7%    |
| Unknown        | 17        | 3.49%   |
| 121-130        | 16        | 3.29%   |
| 351-500        | 15        | 3.08%   |
| 71-80          | 13        | 2.67%   |
| 251-300        | 12        | 2.46%   |
| 61-70          | 11        | 2.26%   |
| 51-60          | 11        | 2.26%   |
| More than 1000 | 7         | 1.44%   |
| 131-140        | 7         | 1.44%   |
| 501-1000       | 5         | 1.03%   |
| 111-120        | 4         | 0.82%   |
| 41-50          | 2         | 0.41%   |
| 91-100         | 2         | 0.41%   |
| 1-40           | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 162       | 34.11%  |
| 121-160       | 142       | 29.89%  |
| 101-120       | 127       | 26.74%  |
| 161-240       | 17        | 3.58%   |
| Unknown       | 17        | 3.58%   |
| 1-50          | 6         | 1.26%   |
| More than 240 | 4         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 393       | 83.26%  |
| 2     | 55        | 11.65%  |
| 0     | 17        | 3.6%    |
| 3     | 7         | 1.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 254       | 37.24%  |
| Intel                             | 230       | 33.72%  |
| Qualcomm Atheros                  | 64        | 9.38%   |
| Broadcom                          | 34        | 4.99%   |
| MediaTek                          | 9         | 1.32%   |
| Marvell Technology Group          | 9         | 1.32%   |
| Ralink Technology                 | 8         | 1.17%   |
| Broadcom Limited                  | 6         | 0.88%   |
| TP-Link                           | 5         | 0.73%   |
| Dell                              | 5         | 0.73%   |
| Sierra Wireless                   | 4         | 0.59%   |
| Ralink                            | 4         | 0.59%   |
| Qualcomm                          | 4         | 0.59%   |
| Nvidia                            | 4         | 0.59%   |
| Microchip Technology              | 3         | 0.44%   |
| Huawei Technologies               | 3         | 0.44%   |
| ASIX Electronics                  | 3         | 0.44%   |
| Aquantia                          | 3         | 0.44%   |
| Xiaomi                            | 2         | 0.29%   |
| Samsung Electronics               | 2         | 0.29%   |
| Qualcomm Atheros Communications   | 2         | 0.29%   |
| OPPO Electronics                  | 2         | 0.29%   |
| Insyde Software                   | 2         | 0.29%   |
| Hewlett-Packard                   | 2         | 0.29%   |
| D-Link System                     | 2         | 0.29%   |
| ZyDAS                             | 1         | 0.15%   |
| Zoom Telephonics                  | 1         | 0.15%   |
| TRENDnet                          | 1         | 0.15%   |
| NetGear                           | 1         | 0.15%   |
| Microsoft                         | 1         | 0.15%   |
| Mellanox Technologies             | 1         | 0.15%   |
| LG Electronics                    | 1         | 0.15%   |
| Fibocom                           | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |
| D-Link                            | 1         | 0.15%   |
| BUFFALO                           | 1         | 0.15%   |
| Belkin Components                 | 1         | 0.15%   |
| Attansic Technology               | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |
| Arduino SA                        | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 169       | 20.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 3.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17        | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 2.1%    |
| Intel Wireless 8260                                               | 16        | 1.98%   |
| Intel Wi-Fi 6 AX200                                               | 16        | 1.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 15        | 1.85%   |
| Intel Wireless 7265                                               | 14        | 1.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.36%   |
| Intel Wireless 7260                                               | 11        | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.23%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 1.23%   |
| Intel Wireless 3165                                               | 9         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9         | 1.11%   |
| Intel I211 Gigabit Network Connection                             | 9         | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.99%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 0.86%   |
| Realtek 802.11ac NIC                                              | 6         | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.74%   |
| Intel Wireless 3160                                               | 6         | 0.74%   |
| Intel Ethernet Controller I225-V                                  | 6         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 0.62%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.49%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.49%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 173       | 46.38%  |
| Realtek Semiconductor           | 73        | 19.57%  |
| Qualcomm Atheros                | 59        | 15.82%  |
| Broadcom                        | 18        | 4.83%   |
| MediaTek                        | 9         | 2.41%   |
| Ralink Technology               | 8         | 2.14%   |
| Sierra Wireless                 | 4         | 1.07%   |
| Ralink                          | 4         | 1.07%   |
| Qualcomm                        | 4         | 1.07%   |
| TP-Link                         | 3         | 0.8%    |
| Dell                            | 3         | 0.8%    |
| Qualcomm Atheros Communications | 2         | 0.54%   |
| Broadcom Limited                | 2         | 0.54%   |
| ZyDAS                           | 1         | 0.27%   |
| TRENDnet                        | 1         | 0.27%   |
| NetGear                         | 1         | 0.27%   |
| Microsoft                       | 1         | 0.27%   |
| Marvell Technology Group        | 1         | 0.27%   |
| Fibocom                         | 1         | 0.27%   |
| D-Link System                   | 1         | 0.27%   |
| D-Link                          | 1         | 0.27%   |
| BUFFALO                         | 1         | 0.27%   |
| Belkin Components               | 1         | 0.27%   |
| ASUSTek Computer                | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17        | 4.49%   |
| Intel Wireless 8260                                            | 16        | 4.22%   |
| Intel Wi-Fi 6 AX200                                            | 16        | 4.22%   |
| Intel Wi-Fi 6 AX201                                            | 15        | 3.96%   |
| Intel Wireless 7265                                            | 14        | 3.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 2.9%    |
| Intel Wireless 7260                                            | 11        | 2.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 2.64%   |
| Intel Wireless 3165                                            | 9         | 2.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 9         | 2.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 2.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 2.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 1.85%   |
| Realtek 802.11ac NIC                                           | 6         | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 1.58%   |
| Intel Wireless 3160                                            | 6         | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 1.58%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 1.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 1.32%   |
| Intel Wireless 8265 / 8275                                     | 5         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.06%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.06%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.06%   |
| Intel Ultimate N WiFi Link 5300                                | 4         | 1.06%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.06%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 1.06%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.06%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.06%   |
| Sierra Wireless EM7455                                         | 3         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 220       | 53.14%  |
| Intel                    | 121       | 29.23%  |
| Broadcom                 | 19        | 4.59%   |
| Qualcomm Atheros         | 12        | 2.9%    |
| Marvell Technology Group | 8         | 1.93%   |
| Nvidia                   | 4         | 0.97%   |
| Broadcom Limited         | 4         | 0.97%   |
| Huawei Technologies      | 3         | 0.72%   |
| ASIX Electronics         | 3         | 0.72%   |
| Aquantia                 | 3         | 0.72%   |
| Xiaomi                   | 2         | 0.48%   |
| TP-Link                  | 2         | 0.48%   |
| OPPO Electronics         | 2         | 0.48%   |
| Microchip Technology     | 2         | 0.48%   |
| Insyde Software          | 2         | 0.48%   |
| Hewlett-Packard          | 2         | 0.48%   |
| Samsung Electronics      | 1         | 0.24%   |
| LG Electronics           | 1         | 0.24%   |
| D-Link System            | 1         | 0.24%   |
| Attansic Technology      | 1         | 0.24%   |
| Apple                    | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 169       | 39.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 28        | 6.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 4.02%   |
| Realtek RTL8125 2.5GbE Controller                                              | 15        | 3.55%   |
| Intel Ethernet Connection (2) I219-V                                           | 10        | 2.36%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 1.89%   |
| Intel Ethernet Connection I219-LM                                              | 8         | 1.89%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 1.65%   |
| Intel Ethernet Controller I225-V                                               | 6         | 1.42%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.18%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 0.95%   |
| Nvidia MCP61 Ethernet                                                          | 4         | 0.95%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 0.95%   |
| Intel Ethernet Connection I217-V                                               | 4         | 0.95%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 0.95%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 0.71%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.71%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.71%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 0.71%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.71%   |
| Huawei ANE-LX1                                                                 | 3         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.71%   |
| OPPO SM8350-MTP _SN:1518BD09                                                   | 2         | 0.47%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 2         | 0.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.47%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 2         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.47%   |
| Intel Ethernet Connection (17) I219-V                                          | 2         | 0.47%   |
| Intel Ethernet Connection (16) I219-V                                          | 2         | 0.47%   |
| Intel Ethernet Connection (14) I219-V                                          | 2         | 0.47%   |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 0.47%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.47%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 388       | 52.08%  |
| WiFi     | 349       | 46.85%  |
| Modem    | 7         | 0.94%   |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 284       | 58.8%   |
| Ethernet | 199       | 41.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 252       | 53.39%  |
| 1     | 189       | 40.04%  |
| 0     | 20        | 4.24%   |
| 3     | 8         | 1.69%   |
| 4     | 3         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 315       | 66.18%  |
| Yes  | 161       | 33.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 47.31%  |
| Realtek Semiconductor           | 34        | 12.19%  |
| Broadcom                        | 19        | 6.81%   |
| Cambridge Silicon Radio         | 18        | 6.45%   |
| Qualcomm Atheros Communications | 13        | 4.66%   |
| IMC Networks                    | 11        | 3.94%   |
| Foxconn / Hon Hai               | 11        | 3.94%   |
| Lite-On Technology              | 10        | 3.58%   |
| Apple                           | 7         | 2.51%   |
| Hewlett-Packard                 | 4         | 1.43%   |
| Dell                            | 4         | 1.43%   |
| Realtek                         | 3         | 1.08%   |
| MediaTek                        | 2         | 0.72%   |
| ASUSTek Computer                | 2         | 0.72%   |
| USI                             | 1         | 0.36%   |
| Toshiba                         | 1         | 0.36%   |
| Taiyo Yuden                     | 1         | 0.36%   |
| Ralink                          | 1         | 0.36%   |
| Marvell Semiconductor           | 1         | 0.36%   |
| Fujitsu                         | 1         | 0.36%   |
| Foxconn International           | 1         | 0.36%   |
| Chicony Electronics             | 1         | 0.36%   |
| Alps Electric                   | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 60        | 21.43%  |
| Realtek Bluetooth Radio                                                             | 24        | 8.57%   |
| Intel AX201 Bluetooth                                                               | 23        | 8.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 18        | 6.43%   |
| Intel AX200 Bluetooth                                                               | 16        | 5.71%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 2.86%   |
| Intel AX210 Bluetooth                                                               | 8         | 2.86%   |
| Intel Bluetooth Device                                                              | 7         | 2.5%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 2.14%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.43%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.07%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.07%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.07%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.07%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.07%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.71%   |
| MediaTek Wireless_Device                                                            | 2         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 0.71%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.71%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.71%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.71%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.71%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.71%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.71%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.71%   |
| USI Bluetooth Device                                                                | 1         | 0.36%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.36%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.36%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.36%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.36%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 342       | 58.06%  |
| AMD                        | 118       | 20.03%  |
| Nvidia                     | 82        | 13.92%  |
| C-Media Electronics        | 6         | 1.02%   |
| Texas Instruments          | 4         | 0.68%   |
| Generalplus Technology     | 3         | 0.51%   |
| Creative Labs              | 3         | 0.51%   |
| ASUSTek Computer           | 3         | 0.51%   |
| SAVITECH                   | 2         | 0.34%   |
| Logitech                   | 2         | 0.34%   |
| JMTek                      | 2         | 0.34%   |
| GN Netcom                  | 2         | 0.34%   |
| Creative Technology        | 2         | 0.34%   |
| VIA Technologies           | 1         | 0.17%   |
| Trust International        | 1         | 0.17%   |
| Tenx Technology            | 1         | 0.17%   |
| STMicroelectronics         | 1         | 0.17%   |
| Samson Technologies        | 1         | 0.17%   |
| Realtek Semiconductor      | 1         | 0.17%   |
| PreSonus Audio Electronics | 1         | 0.17%   |
| Plantronics                | 1         | 0.17%   |
| Micro Star International   | 1         | 0.17%   |
| Medeli Electronics         | 1         | 0.17%   |
| MAG Technology             | 1         | 0.17%   |
| Lenovo                     | 1         | 0.17%   |
| Kingston Technology        | 1         | 0.17%   |
| Hewlett-Packard            | 1         | 0.17%   |
| Guangzhou FiiO Electronics | 1         | 0.17%   |
| Corsair                    | 1         | 0.17%   |
| Conexant Systems           | 1         | 0.17%   |
| BEHRINGER International    | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 33        | 4.73%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 31        | 4.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 4.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 3.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 23        | 3.3%    |
| AMD FCH Azalia Controller                                                                         | 23        | 3.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 3.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 3.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 2.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 16        | 2.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 2.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 2.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 1.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 1.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 1.43%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 1.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 1.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1%      |
| Intel Alder Lake-S HD Audio Controller                                                            | 7         | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 1%      |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.72%   |
| Nvidia Audio device                                                                               | 5         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 97        | 24.74%  |
| Unknown                    | 57        | 14.54%  |
| SK hynix                   | 55        | 14.03%  |
| Kingston                   | 43        | 10.97%  |
| Micron Technology          | 29        | 7.4%    |
| Crucial                    | 29        | 7.4%    |
| G.Skill                    | 13        | 3.32%   |
| Unknown (ABCD)             | 12        | 3.06%   |
| Ramaxel Technology         | 12        | 3.06%   |
| Corsair                    | 10        | 2.55%   |
| Nanya Technology           | 5         | 1.28%   |
| Elpida                     | 5         | 1.28%   |
| Transcend                  | 3         | 0.77%   |
| fef5                       | 3         | 0.77%   |
| Smart                      | 2         | 0.51%   |
| A-DATA Technology          | 2         | 0.51%   |
| Unknown                    | 2         | 0.51%   |
| V-Color                    | 1         | 0.26%   |
| Unknown (AB)               | 1         | 0.26%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.26%   |
| Timetec                    | 1         | 0.26%   |
| Qumo                       | 1         | 0.26%   |
| Qimonda                    | 1         | 0.26%   |
| GLOWAY                     | 1         | 0.26%   |
| GIGA-BYTE                  | 1         | 0.26%   |
| Foxline                    | 1         | 0.26%   |
| Essencore                  | 1         | 0.26%   |
| Daten Tecnologia           | 1         | 0.26%   |
| Avant                      | 1         | 0.26%   |
| ASint Technology           | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 1.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 4         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.98%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.98%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 3         | 0.74%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 3         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.74%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.74%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.74%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.74%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 3         | 0.74%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                            | 3         | 0.74%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.49%   |
| Unknown RAM Module 1GB SODIMM LPDDR3 1600MT/s                    | 2         | 0.49%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.49%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.49%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.49%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 2         | 0.49%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.49%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.49%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.49%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.49%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 2         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 135       | 39.94%  |
| DDR3    | 117       | 34.62%  |
| LPDDR4  | 27        | 7.99%   |
| DDR2    | 19        | 5.62%   |
| Unknown | 11        | 3.25%   |
| SDRAM   | 10        | 2.96%   |
| LPDDR3  | 9         | 2.66%   |
| LPDDR5  | 4         | 1.18%   |
| DDR5    | 4         | 1.18%   |
| DRAM    | 1         | 0.3%    |
| DDR     | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 186       | 55.52%  |
| DIMM         | 117       | 34.93%  |
| Row Of Chips | 22        | 6.57%   |
| Unknown      | 7         | 2.09%   |
| Chip         | 3         | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 111       | 30.83%  |
| 4096  | 105       | 29.17%  |
| 2048  | 63        | 17.5%   |
| 16384 | 55        | 15.28%  |
| 1024  | 17        | 4.72%   |
| 32768 | 6         | 1.67%   |
| 65536 | 1         | 0.28%   |
| 1536  | 1         | 0.28%   |
| 512   | 1         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 80        | 22.6%   |
| 3200    | 55        | 15.54%  |
| 2667    | 35        | 9.89%   |
| 2400    | 32        | 9.04%   |
| 1333    | 26        | 7.34%   |
| 2133    | 18        | 5.08%   |
| 667     | 11        | 3.11%   |
| 1334    | 9         | 2.54%   |
| 3600    | 7         | 1.98%   |
| 4267    | 6         | 1.69%   |
| 1067    | 6         | 1.69%   |
| 1066    | 6         | 1.69%   |
| 1867    | 5         | 1.41%   |
| Unknown | 5         | 1.41%   |
| 3000    | 4         | 1.13%   |
| 6400    | 3         | 0.85%   |
| 4800    | 3         | 0.85%   |
| 4199    | 3         | 0.85%   |
| 3466    | 3         | 0.85%   |
| 3266    | 3         | 0.85%   |
| 2666    | 3         | 0.85%   |
| 800     | 3         | 0.85%   |
| 4266    | 2         | 0.56%   |
| 2048    | 2         | 0.56%   |
| 1866    | 2         | 0.56%   |
| 975     | 2         | 0.56%   |
| 533     | 2         | 0.56%   |
| 6000    | 1         | 0.28%   |
| 5500    | 1         | 0.28%   |
| 5354    | 1         | 0.28%   |
| 4000    | 1         | 0.28%   |
| 3866    | 1         | 0.28%   |
| 3733    | 1         | 0.28%   |
| 3400    | 1         | 0.28%   |
| 3333    | 1         | 0.28%   |
| 3020    | 1         | 0.28%   |
| 2800    | 1         | 0.28%   |
| 2134    | 1         | 0.28%   |
| 2000    | 1         | 0.28%   |
| 1800    | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 45.45%  |
| Brother Industries  | 3         | 27.27%  |
| Samsung Electronics | 1         | 9.09%   |
| Minolta             | 1         | 9.09%   |
| Canon               | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SF-760 Series         | 1         | 9.09%   |
| Minolta PagePro 1300W         | 1         | 9.09%   |
| HP ENVY Pro 6400 series       | 1         | 9.09%   |
| HP DeskJet D1360              | 1         | 9.09%   |
| HP DeskJet 840c               | 1         | 9.09%   |
| HP DeskJet 810c/812c          | 1         | 9.09%   |
| HP Deskjet 3070 B611 series   | 1         | 9.09%   |
| Canon TS3500 series           | 1         | 9.09%   |
| Brother QL-560 Label Printer  | 1         | 9.09%   |
| Brother HL-2030 Laser Printer | 1         | 9.09%   |
| Brother DCP-7040              | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 71.43%  |
| Seiko Epson     | 1         | 14.29%  |
| Hewlett-Packard | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                | 3         | 42.86%  |
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 14.29%  |
| HP ScanJet 7400c                       | 1         | 14.29%  |
| Canon CanoScan LiDE 110                | 1         | 14.29%  |
| Canon CanoScan 4400F                   | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 69        | 24.04%  |
| Realtek Semiconductor                  | 23        | 8.01%   |
| Microdia                               | 23        | 8.01%   |
| Quanta                                 | 19        | 6.62%   |
| IMC Networks                           | 18        | 6.27%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 5.92%   |
| Sunplus Innovation Technology          | 16        | 5.57%   |
| Suyin                                  | 14        | 4.88%   |
| Logitech                               | 11        | 3.83%   |
| Bison Electronics                      | 7         | 2.44%   |
| Apple                                  | 6         | 2.09%   |
| Z-Star Microelectronics                | 5         | 1.74%   |
| Luxvisions Innotech Limited            | 5         | 1.74%   |
| Syntek                                 | 4         | 1.39%   |
| Silicon Motion                         | 4         | 1.39%   |
| Lite-On Technology                     | 4         | 1.39%   |
| Alcor Micro                            | 4         | 1.39%   |
| Acer                                   | 4         | 1.39%   |
| Microsoft                              | 3         | 1.05%   |
| Lenovo                                 | 3         | 1.05%   |
| icSpring                               | 3         | 1.05%   |
| USB Camera CS                          | 2         | 0.7%    |
| Sonix Technology                       | 2         | 0.7%    |
| Ricoh                                  | 2         | 0.7%    |
| KYE Systems (Mouse Systems)            | 2         | 0.7%    |
| Xiongmai                               | 1         | 0.35%   |
| Xiaomi                                 | 1         | 0.35%   |
| ValueHD                                | 1         | 0.35%   |
| SunplusIT                              | 1         | 0.35%   |
| Sunplus Technology                     | 1         | 0.35%   |
| Samsung Electronics                    | 1         | 0.35%   |
| Primax Electronics                     | 1         | 0.35%   |
| OYT Tech                               | 1         | 0.35%   |
| OmniVision Technologies                | 1         | 0.35%   |
| MacroSilicon                           | 1         | 0.35%   |
| Importek                               | 1         | 0.35%   |
| Guillemot                              | 1         | 0.35%   |
| Generalplus Technology                 | 1         | 0.35%   |
| Creative Technology                    | 1         | 0.35%   |
| ARC International                      | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 24        | 8.3%    |
| Sunplus Integrated_Webcam_HD                        | 6         | 2.08%   |
| Chicony HD Webcam                                   | 6         | 2.08%   |
| Quanta HD User Facing                               | 5         | 1.73%   |
| Microdia Integrated_Webcam_HD                       | 5         | 1.73%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 1.73%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.38%   |
| Logitech C922 Pro Stream Webcam                     | 4         | 1.38%   |
| IMC Networks Integrated Camera                      | 4         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 1.38%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 1.04%   |
| Sunplus Integrated_Webcam_FHD                       | 3         | 1.04%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 1.04%   |
| Quanta HP Webcam                                    | 3         | 1.04%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.04%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 1.04%   |
| icSpring camera                                     | 3         | 1.04%   |
| Chicony USB2.0 Camera                               | 3         | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 1.04%   |
| Chicony HP TrueVision HD Camera                     | 3         | 1.04%   |
| Chicony EasyCamera                                  | 3         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.04%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 1.04%   |
| Acer Integrated Camera                              | 3         | 1.04%   |
| USB Camera CS USB Camera CS                         | 2         | 0.69%   |
| Syntek Integrated Camera                            | 2         | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.69%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 0.69%   |
| Realtek USB Camera                                  | 2         | 0.69%   |
| Realtek Lenovo EasyCamera                           | 2         | 0.69%   |
| Realtek HP Truevision HD                            | 2         | 0.69%   |
| Realtek HD WebCam                                   | 2         | 0.69%   |
| Realtek FULL HD 1080P Webcam                        | 2         | 0.69%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 0.69%   |
| Quanta HP HD Camera                                 | 2         | 0.69%   |
| Microdia Webcam Vitade AF                           | 2         | 0.69%   |
| Microdia Lenovo EasyCamera                          | 2         | 0.69%   |
| Microdia CameraA                                    | 2         | 0.69%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 33.33%  |
| Shenzhen Goodix Technology | 10        | 20.83%  |
| Upek                       | 7         | 14.58%  |
| Synaptics                  | 6         | 12.5%   |
| STMicroelectronics         | 2         | 4.17%   |
| Elan Microelectronics      | 2         | 4.17%   |
| AuthenTec                  | 2         | 4.17%   |
| LighTuning Technology      | 1         | 2.08%   |
| Gingytech                  | 1         | 2.08%   |
| Focal-systems.Corp         | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 7         | 14.58%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 6         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 6         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 8.33%   |
| Validity Sensors Synaptics WBDI                        | 3         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 4.17%   |
| Synaptics UWP WBDI Device                              | 2         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 4.17%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 4.17%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 2.08%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 2.08%   |
| Synaptics  WBDI                                        | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.08%   |
| LighTuning Fingerprint Sensor                          | 1         | 2.08%   |
| Gingytech Fingerprint sensor                           | 1         | 2.08%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 2.08%   |
| Elan ELAN:Fingerprint                                  | 1         | 2.08%   |
| Elan ELAN:ARM-M4                                       | 1         | 2.08%   |
| AuthenTec AES2810                                      | 1         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 12        | 41.38%  |
| Alcor Micro              | 9         | 31.03%  |
| O2 Micro                 | 3         | 10.34%  |
| Lenovo                   | 3         | 10.34%  |
| Reiner SCT Kartensysteme | 1         | 3.45%   |
| In Focus Systems         | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 31.03%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 13.79%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 10.34%  |
| Broadcom 5880                                                                | 3         | 10.34%  |
| Broadcom 58200                                                               | 3         | 10.34%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.9%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.9%    |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 3.45%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.45%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 343       | 72.21%  |
| 1     | 104       | 21.89%  |
| 2     | 22        | 4.63%   |
| 3     | 5         | 1.05%   |
| 5     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 28.75%  |
| Graphics card            | 28        | 17.5%   |
| Chipcard                 | 28        | 17.5%   |
| Camera                   | 14        | 8.75%   |
| Net/wireless             | 10        | 6.25%   |
| Multimedia controller    | 7         | 4.38%   |
| Bluetooth                | 5         | 3.13%   |
| Unassigned class         | 4         | 2.5%    |
| Communication controller | 4         | 2.5%    |
| Card reader              | 4         | 2.5%    |
| Network                  | 3         | 1.88%   |
| Storage                  | 2         | 1.25%   |
| Sound                    | 2         | 1.25%   |
| Net/ethernet             | 2         | 1.25%   |
| Dvb card                 | 1         | 0.63%   |

