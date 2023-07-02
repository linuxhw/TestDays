Xubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Xubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu/Desktop/README.md) and [notebooks](/Dist/Xubuntu/Notebook/README.md).

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

Total: 6232

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| Google        | Fleex                       | Notebook    | [7e3eb2d4f9](https://linux-hardware.org/?probe=7e3eb2d4f9) | Jun 30, 2023 |
| HP            | Unknown                     | Notebook    | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [e46c7340d7](https://linux-hardware.org/?probe=e46c7340d7) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| ASUSTek       | H61M-CS                     | Desktop     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| HP            | Unknown                     | Notebook    | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| HP            | 339A                        | Desktop     | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a39abe1278](https://linux-hardware.org/?probe=a39abe1278) | Jun 24, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [89116ab6be](https://linux-hardware.org/?probe=89116ab6be) | Jun 24, 2023 |
| Alienware     | 18                          | Notebook    | [047bc74541](https://linux-hardware.org/?probe=047bc74541) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| Google        | Link                        | Notebook    | [b8284753ca](https://linux-hardware.org/?probe=b8284753ca) | Jun 22, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [2e4e948549](https://linux-hardware.org/?probe=2e4e948549) | Jun 22, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [8f879f5566](https://linux-hardware.org/?probe=8f879f5566) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| HP            | Unknown                     | Notebook    | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| HP            | 18E7                        | Desktop     | [3b872d2a88](https://linux-hardware.org/?probe=3b872d2a88) | Jun 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [c2313cf371](https://linux-hardware.org/?probe=c2313cf371) | Jun 20, 2023 |
| Lenovo        | 1057 SDK0T76530 WIN 3556... | Desktop     | [0502b8f756](https://linux-hardware.org/?probe=0502b8f756) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [a7238c71a7](https://linux-hardware.org/?probe=a7238c71a7) | Jun 20, 2023 |
| TUXEDO        | P65xRP                      | Notebook    | [cfefc9c13a](https://linux-hardware.org/?probe=cfefc9c13a) | Jun 20, 2023 |
| Intel         | H61                         | Desktop     | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| Standard      | Unknown                     | Desktop     | [4956d7fc21](https://linux-hardware.org/?probe=4956d7fc21) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [154f9809e6](https://linux-hardware.org/?probe=154f9809e6) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [66ce1a98a8](https://linux-hardware.org/?probe=66ce1a98a8) | Jun 18, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [10b3b517f3](https://linux-hardware.org/?probe=10b3b517f3) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [4f0ec49165](https://linux-hardware.org/?probe=4f0ec49165) | Jun 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [601d7611be](https://linux-hardware.org/?probe=601d7611be) | Jun 17, 2023 |
| Unknown       | Minix Neo U9-H              | Soc         | [7b845b4b0b](https://linux-hardware.org/?probe=7b845b4b0b) | Jun 16, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [53a0b2f173](https://linux-hardware.org/?probe=53a0b2f173) | Jun 15, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [5a31ac8b21](https://linux-hardware.org/?probe=5a31ac8b21) | Jun 15, 2023 |
| HP            | Unknown                     | Notebook    | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Samsung       | 760XDA                      | Notebook    | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [04f1fdc3c9](https://linux-hardware.org/?probe=04f1fdc3c9) | Jun 14, 2023 |
| Dell          | Latitude E5270              | Notebook    | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [b0afd2fa7b](https://linux-hardware.org/?probe=b0afd2fa7b) | Jun 13, 2023 |
| Dell          | Latitude 5411               | Notebook    | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| Unknown       | Unknown                     | Other       | [00ad49fe2f](https://linux-hardware.org/?probe=00ad49fe2f) | Jun 12, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [61e759f7db](https://linux-hardware.org/?probe=61e759f7db) | Jun 11, 2023 |
| Biostar       | TPower I45                  | Desktop     | [b88767bce0](https://linux-hardware.org/?probe=b88767bce0) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| TYAN Compu... | S7010                       | Server      | [a8b96e89f2](https://linux-hardware.org/?probe=a8b96e89f2) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [2c8c27897b](https://linux-hardware.org/?probe=2c8c27897b) | Jun 09, 2023 |
| MSI           | A55M-E35                    | Desktop     | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| Acer          | AO722                       | Notebook    | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Acer          | AO722                       | Notebook    | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Dell          | Precision 5510              | Notebook    | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| LORD ELECT... | I915 Series V1.0            | Desktop     | [d693b7baec](https://linux-hardware.org/?probe=d693b7baec) | Jun 05, 2023 |
| HP            | 8768 A                      | Desktop     | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [741e39b142](https://linux-hardware.org/?probe=741e39b142) | Jun 05, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| Lenovo        | V560                        | Notebook    | [b2564e07cc](https://linux-hardware.org/?probe=b2564e07cc) | Jun 03, 2023 |
| SK hynix      | HyBook                      | Notebook    | [c25f19e040](https://linux-hardware.org/?probe=c25f19e040) | Jun 03, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [1d9f5bc60f](https://linux-hardware.org/?probe=1d9f5bc60f) | Jun 02, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1383313bbb](https://linux-hardware.org/?probe=1383313bbb) | May 31, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [88f3c7f5e5](https://linux-hardware.org/?probe=88f3c7f5e5) | May 29, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [33eb5df96b](https://linux-hardware.org/?probe=33eb5df96b) | May 26, 2023 |
| Acer          | Veriton N4620G              | Desktop     | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Dell          | Latitude 7390               | Notebook    | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [10adda3362](https://linux-hardware.org/?probe=10adda3362) | May 25, 2023 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [7788147663](https://linux-hardware.org/?probe=7788147663) | May 24, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [2dfed39533](https://linux-hardware.org/?probe=2dfed39533) | May 24, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Lenovo        | ThinkPad W500 40626NG       | Notebook    | [9466f83af8](https://linux-hardware.org/?probe=9466f83af8) | May 22, 2023 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [91bb4c8e5d](https://linux-hardware.org/?probe=91bb4c8e5d) | May 22, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [50b46e4d8c](https://linux-hardware.org/?probe=50b46e4d8c) | May 22, 2023 |
| Dell          | Latitude E4200              | Notebook    | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Unknown       | 1.0                         | Desktop     | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [bfaa8e099f](https://linux-hardware.org/?probe=bfaa8e099f) | May 21, 2023 |
| HP            | 0A08h                       | Desktop     | [9d159d2637](https://linux-hardware.org/?probe=9d159d2637) | May 21, 2023 |
| Dell          | G3 3500                     | Notebook    | [cbe9c2f010](https://linux-hardware.org/?probe=cbe9c2f010) | May 21, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0b802ad297](https://linux-hardware.org/?probe=0b802ad297) | May 19, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| Pegatron      | Benicia                     | Desktop     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [84bd50bc27](https://linux-hardware.org/?probe=84bd50bc27) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| HP            | 09F8h                       | Desktop     | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7661V3L        | Notebook    | [5714171d2a](https://linux-hardware.org/?probe=5714171d2a) | May 14, 2023 |
| Acer          | Aspire V5-552G              | Notebook    | [4384294484](https://linux-hardware.org/?probe=4384294484) | May 14, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [7e178a2a32](https://linux-hardware.org/?probe=7e178a2a32) | May 13, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0b0b5e02cc](https://linux-hardware.org/?probe=0b0b5e02cc) | May 13, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [3191d9fca4](https://linux-hardware.org/?probe=3191d9fca4) | May 11, 2023 |
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
| Lenovo        | MAHOBAY                     | Desktop     | [9726453f00](https://linux-hardware.org/?probe=9726453f00) | May 09, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0f322b6e3f](https://linux-hardware.org/?probe=0f322b6e3f) | May 08, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7ac436d763](https://linux-hardware.org/?probe=7ac436d763) | May 08, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [a915e84a9a](https://linux-hardware.org/?probe=a915e84a9a) | May 08, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ebafddb3f1](https://linux-hardware.org/?probe=ebafddb3f1) | May 06, 2023 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | Desktop     | [e34348c1b5](https://linux-hardware.org/?probe=e34348c1b5) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d41ef08f2](https://linux-hardware.org/?probe=2d41ef08f2) | May 05, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f5f0edbac8](https://linux-hardware.org/?probe=f5f0edbac8) | May 05, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bbac197d5d](https://linux-hardware.org/?probe=bbac197d5d) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| HP            | ENVY 4                      | Notebook    | [20395a1739](https://linux-hardware.org/?probe=20395a1739) | May 04, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [b735e1019b](https://linux-hardware.org/?probe=b735e1019b) | May 03, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [2f6fd9e5b0](https://linux-hardware.org/?probe=2f6fd9e5b0) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6cbfaabd66](https://linux-hardware.org/?probe=6cbfaabd66) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [4762d9bb4e](https://linux-hardware.org/?probe=4762d9bb4e) | May 03, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | Notebook    | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Acer          | Peppy                       | Notebook    | [dcac703c46](https://linux-hardware.org/?probe=dcac703c46) | Apr 30, 2023 |
| Acer          | Extensa 5620                | Notebook    | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| HP            | 158A                        | Desktop     | [fb7aef7883](https://linux-hardware.org/?probe=fb7aef7883) | Apr 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [6daa7002c8](https://linux-hardware.org/?probe=6daa7002c8) | Apr 27, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | Notebook    | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [4382f0cce7](https://linux-hardware.org/?probe=4382f0cce7) | Apr 27, 2023 |
| HP            | 1632                        | Desktop     | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 158A                        | Desktop     | [c3189bccb1](https://linux-hardware.org/?probe=c3189bccb1) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [98ed5e9a2e](https://linux-hardware.org/?probe=98ed5e9a2e) | Apr 25, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [76c4edb7f3](https://linux-hardware.org/?probe=76c4edb7f3) | Apr 23, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | Notebook    | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | 0AECh D                     | Desktop     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| OrangePi      | 4 (DT)                      | Soc         | [a1c0a82172](https://linux-hardware.org/?probe=a1c0a82172) | Apr 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [9ff4edba5b](https://linux-hardware.org/?probe=9ff4edba5b) | Apr 20, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [e062ca363c](https://linux-hardware.org/?probe=e062ca363c) | Apr 20, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [704778a577](https://linux-hardware.org/?probe=704778a577) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [9f2a1a2c93](https://linux-hardware.org/?probe=9f2a1a2c93) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [9539ccfd4d](https://linux-hardware.org/?probe=9539ccfd4d) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | Desktop     | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [4cb39d1136](https://linux-hardware.org/?probe=4cb39d1136) | Apr 15, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [93fae77e6c](https://linux-hardware.org/?probe=93fae77e6c) | Apr 13, 2023 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [ae144ff4c8](https://linux-hardware.org/?probe=ae144ff4c8) | Apr 12, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Dell          | 060K5C A04                  | Server      | [962b265260](https://linux-hardware.org/?probe=962b265260) | Apr 11, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [7f718ab68f](https://linux-hardware.org/?probe=7f718ab68f) | Apr 10, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e99e4b1fac](https://linux-hardware.org/?probe=e99e4b1fac) | Apr 10, 2023 |
| Medion        | MS-7848                     | Desktop     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [71ee0575d4](https://linux-hardware.org/?probe=71ee0575d4) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9dde876e9](https://linux-hardware.org/?probe=e9dde876e9) | Apr 08, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [9f0d854259](https://linux-hardware.org/?probe=9f0d854259) | Apr 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [1b8983e24d](https://linux-hardware.org/?probe=1b8983e24d) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Nvidia        | Tegra                       | Soc         | [d57318f254](https://linux-hardware.org/?probe=d57318f254) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [25c3fdc9f7](https://linux-hardware.org/?probe=25c3fdc9f7) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [8b4f79808a](https://linux-hardware.org/?probe=8b4f79808a) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [f7cdc4223d](https://linux-hardware.org/?probe=f7cdc4223d) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [deedee079c](https://linux-hardware.org/?probe=deedee079c) | Mar 31, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Medion        | S321X                       | Notebook    | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| Gateway       | LT27                        | Notebook    | [4697cead5f](https://linux-hardware.org/?probe=4697cead5f) | Mar 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [94cd15664b](https://linux-hardware.org/?probe=94cd15664b) | Mar 27, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| MSI           | MEG B550 UNIFY              | Desktop     | [492a70f1c3](https://linux-hardware.org/?probe=492a70f1c3) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a7ff24abc4](https://linux-hardware.org/?probe=a7ff24abc4) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [8d5a135264](https://linux-hardware.org/?probe=8d5a135264) | Mar 26, 2023 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [0fc1609d81](https://linux-hardware.org/?probe=0fc1609d81) | Mar 26, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [5f5efa7edc](https://linux-hardware.org/?probe=5f5efa7edc) | Mar 25, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [cce3fdd054](https://linux-hardware.org/?probe=cce3fdd054) | Mar 25, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | Desktop     | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| HP            | 158A                        | Desktop     | [9ed0f8f65f](https://linux-hardware.org/?probe=9ed0f8f65f) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [f97f90f7ce](https://linux-hardware.org/?probe=f97f90f7ce) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | Notebook    | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | Notebook    | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| Biostar       | TZ77A                       | Desktop     | [9484c73494](https://linux-hardware.org/?probe=9484c73494) | Mar 21, 2023 |
| HP            | 158A                        | Desktop     | [033f7a5abd](https://linux-hardware.org/?probe=033f7a5abd) | Mar 21, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [62d90f07ba](https://linux-hardware.org/?probe=62d90f07ba) | Mar 20, 2023 |
| Lenovo        | ThinkPad T530 2429LT7       | Notebook    | [ebb127610b](https://linux-hardware.org/?probe=ebb127610b) | Mar 20, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [653b1820fe](https://linux-hardware.org/?probe=653b1820fe) | Mar 20, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [a174d9ea53](https://linux-hardware.org/?probe=a174d9ea53) | Mar 17, 2023 |
| Amlogic       | Meson8B                     | Soc         | [c564829ae4](https://linux-hardware.org/?probe=c564829ae4) | Mar 17, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [4efa1b8600](https://linux-hardware.org/?probe=4efa1b8600) | Mar 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | Notebook    | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [406ea57f9c](https://linux-hardware.org/?probe=406ea57f9c) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Gigabyte      | 8IR533                      | Desktop     | [ee9bb6485a](https://linux-hardware.org/?probe=ee9bb6485a) | Mar 12, 2023 |
| Gigabyte      | 8IR533                      | Desktop     | [9e5837ddaf](https://linux-hardware.org/?probe=9e5837ddaf) | Mar 12, 2023 |
| Google        | Kefka                       | Notebook    | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [b7de8d093d](https://linux-hardware.org/?probe=b7de8d093d) | Mar 11, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ac565d5d7d](https://linux-hardware.org/?probe=ac565d5d7d) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Apple         | MacBookPro1,1               | Notebook    | [105d39532f](https://linux-hardware.org/?probe=105d39532f) | Mar 10, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ad41e0e370](https://linux-hardware.org/?probe=ad41e0e370) | Mar 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82551d929c](https://linux-hardware.org/?probe=82551d929c) | Mar 09, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [a35bb278ba](https://linux-hardware.org/?probe=a35bb278ba) | Mar 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [13418c9605](https://linux-hardware.org/?probe=13418c9605) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [66f6a0491e](https://linux-hardware.org/?probe=66f6a0491e) | Mar 07, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [c0f8008427](https://linux-hardware.org/?probe=c0f8008427) | Mar 07, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Toshiba       | Satellite L775              | Notebook    | [75a1948a64](https://linux-hardware.org/?probe=75a1948a64) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| Microtech     | ebookPro                    | Notebook    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
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
| Dell          | 0NW6H5 A00                  | Desktop     | [aeb7d7a9f4](https://linux-hardware.org/?probe=aeb7d7a9f4) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [83e6da010b](https://linux-hardware.org/?probe=83e6da010b) | Feb 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a407f82b9](https://linux-hardware.org/?probe=1a407f82b9) | Feb 27, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e538527e6c](https://linux-hardware.org/?probe=e538527e6c) | Feb 26, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| Alienware     | 17 R4                       | Notebook    | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [b574c32b53](https://linux-hardware.org/?probe=b574c32b53) | Feb 24, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [2645328f34](https://linux-hardware.org/?probe=2645328f34) | Feb 23, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [43b2cca281](https://linux-hardware.org/?probe=43b2cca281) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | Notebook    | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| Acer          | Aspire 7736                 | Notebook    | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [656629ffba](https://linux-hardware.org/?probe=656629ffba) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| HP            | 158A                        | Desktop     | [ce217224ba](https://linux-hardware.org/?probe=ce217224ba) | Feb 19, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [e85ff6e5c3](https://linux-hardware.org/?probe=e85ff6e5c3) | Feb 18, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [8cd6645d36](https://linux-hardware.org/?probe=8cd6645d36) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Pegatron      | EVE                         | Desktop     | [0bde64bb64](https://linux-hardware.org/?probe=0bde64bb64) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [6e1d13cecb](https://linux-hardware.org/?probe=6e1d13cecb) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [33e3d93b19](https://linux-hardware.org/?probe=33e3d93b19) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [bb037d75a7](https://linux-hardware.org/?probe=bb037d75a7) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [dd2d87798a](https://linux-hardware.org/?probe=dd2d87798a) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Sony          | VPCX11Z6R                   | Notebook    | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [74013e0688](https://linux-hardware.org/?probe=74013e0688) | Feb 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| HP            | Compaq Presario A900        | Notebook    | [d3c4a9e1e6](https://linux-hardware.org/?probe=d3c4a9e1e6) | Feb 09, 2023 |
| Lenovo        | ThinkPad T430s 23562Z3      | Notebook    | [7338d8375a](https://linux-hardware.org/?probe=7338d8375a) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [e3bd76eeaf](https://linux-hardware.org/?probe=e3bd76eeaf) | Feb 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feeed093c0](https://linux-hardware.org/?probe=feeed093c0) | Feb 07, 2023 |
| Dell          | Latitude D430               | Notebook    | [0c1ad39f32](https://linux-hardware.org/?probe=0c1ad39f32) | Feb 06, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [cb02cfc77c](https://linux-hardware.org/?probe=cb02cfc77c) | Feb 05, 2023 |
| MSI           | MS-7309                     | Desktop     | [46995d58eb](https://linux-hardware.org/?probe=46995d58eb) | Feb 05, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [99dc5ad30d](https://linux-hardware.org/?probe=99dc5ad30d) | Feb 05, 2023 |
| ASUSTek       | P5V-VM DH                   | Desktop     | [9d090675b1](https://linux-hardware.org/?probe=9d090675b1) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Intel         | Unknown                     | Notebook    | [f12482330f](https://linux-hardware.org/?probe=f12482330f) | Feb 05, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [163991dfae](https://linux-hardware.org/?probe=163991dfae) | Feb 03, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [7cd66ad148](https://linux-hardware.org/?probe=7cd66ad148) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [a08e60bb31](https://linux-hardware.org/?probe=a08e60bb31) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [d6829621d7](https://linux-hardware.org/?probe=d6829621d7) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [8641149603](https://linux-hardware.org/?probe=8641149603) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| HP            | 0A08h                       | Desktop     | [f9b0168de1](https://linux-hardware.org/?probe=f9b0168de1) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [e9d671848c](https://linux-hardware.org/?probe=e9d671848c) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [f409b1df0b](https://linux-hardware.org/?probe=f409b1df0b) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [6aa78b855a](https://linux-hardware.org/?probe=6aa78b855a) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [28effc69e6](https://linux-hardware.org/?probe=28effc69e6) | Jan 25, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [4867533043](https://linux-hardware.org/?probe=4867533043) | Jan 25, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [12d8081c29](https://linux-hardware.org/?probe=12d8081c29) | Jan 23, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [8d876754f3](https://linux-hardware.org/?probe=8d876754f3) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [f1f61785e5](https://linux-hardware.org/?probe=f1f61785e5) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [ec7d450cb0](https://linux-hardware.org/?probe=ec7d450cb0) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [d55b2b9507](https://linux-hardware.org/?probe=d55b2b9507) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [8716ca07da](https://linux-hardware.org/?probe=8716ca07da) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [21e1d557cc](https://linux-hardware.org/?probe=21e1d557cc) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [33c845f3a4](https://linux-hardware.org/?probe=33c845f3a4) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [24d2721a00](https://linux-hardware.org/?probe=24d2721a00) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [1e1066bd8b](https://linux-hardware.org/?probe=1e1066bd8b) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [7e636906b9](https://linux-hardware.org/?probe=7e636906b9) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [5aa076d0a5](https://linux-hardware.org/?probe=5aa076d0a5) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c4a17a3cf](https://linux-hardware.org/?probe=4c4a17a3cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | Notebook    | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [bc8c82ca9a](https://linux-hardware.org/?probe=bc8c82ca9a) | Jan 21, 2023 |
| Dell          | Inspiron 5391               | Notebook    | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| Dell          | Latitude E6440              | Notebook    | [f2b34c7c46](https://linux-hardware.org/?probe=f2b34c7c46) | Jan 17, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [c32c7f2d35](https://linux-hardware.org/?probe=c32c7f2d35) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [2b7ce8a40b](https://linux-hardware.org/?probe=2b7ce8a40b) | Jan 17, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [5f3e7922cd](https://linux-hardware.org/?probe=5f3e7922cd) | Jan 16, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [7d03111ac0](https://linux-hardware.org/?probe=7d03111ac0) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [b4bc427969](https://linux-hardware.org/?probe=b4bc427969) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [22c3999607](https://linux-hardware.org/?probe=22c3999607) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| ASUSTek       | A7K                         | Notebook    | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f2d7914ecc](https://linux-hardware.org/?probe=f2d7914ecc) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | Notebook    | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [dc397ff7f7](https://linux-hardware.org/?probe=dc397ff7f7) | Jan 09, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | Notebook    | [2f9ff5256a](https://linux-hardware.org/?probe=2f9ff5256a) | Jan 08, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | Notebook    | [b952438f2c](https://linux-hardware.org/?probe=b952438f2c) | Jan 08, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Toshiba       | NB205                       | Notebook    | [3d6ba0d0b3](https://linux-hardware.org/?probe=3d6ba0d0b3) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b11276e9d3](https://linux-hardware.org/?probe=b11276e9d3) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [51bbf252db](https://linux-hardware.org/?probe=51bbf252db) | Jan 06, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Dell          | Latitude 5590               | Notebook    | [f32e1efdef](https://linux-hardware.org/?probe=f32e1efdef) | Jan 05, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [0ac727d853](https://linux-hardware.org/?probe=0ac727d853) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| HP            | 339A                        | Desktop     | [c35711cb53](https://linux-hardware.org/?probe=c35711cb53) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| MSI           | MS-7142                     | Desktop     | [b267479470](https://linux-hardware.org/?probe=b267479470) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| MSI           | MS-7142                     | Desktop     | [ad19259a27](https://linux-hardware.org/?probe=ad19259a27) | Jan 01, 2023 |
| ASUSTek       | P5GD2-VM                    | Desktop     | [13ccd15493](https://linux-hardware.org/?probe=13ccd15493) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| TrekStor      | Primebook C11B              | Convertible | [e96819bd00](https://linux-hardware.org/?probe=e96819bd00) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [23dc9112a8](https://linux-hardware.org/?probe=23dc9112a8) | Dec 27, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [2041ed5cba](https://linux-hardware.org/?probe=2041ed5cba) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [01466a6701](https://linux-hardware.org/?probe=01466a6701) | Dec 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | Notebook    | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Khadas        | VIM2                        | Soc         | [2ead7fb94b](https://linux-hardware.org/?probe=2ead7fb94b) | Dec 23, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| Clevo         | P170EM                      | Notebook    | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f78b9b1a90](https://linux-hardware.org/?probe=f78b9b1a90) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| HP            | Pavilion dv7                | Notebook    | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [643c90d5e1](https://linux-hardware.org/?probe=643c90d5e1) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [ba280c7787](https://linux-hardware.org/?probe=ba280c7787) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8862992776](https://linux-hardware.org/?probe=8862992776) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [6ea891850f](https://linux-hardware.org/?probe=6ea891850f) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [0679db84af](https://linux-hardware.org/?probe=0679db84af) | Dec 14, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [51acd303f0](https://linux-hardware.org/?probe=51acd303f0) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| HP            | 350 G1                      | Notebook    | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [7968282240](https://linux-hardware.org/?probe=7968282240) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| HP            | 2B34                        | Desktop     | [18ec4a2e66](https://linux-hardware.org/?probe=18ec4a2e66) | Dec 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6bb91c588](https://linux-hardware.org/?probe=f6bb91c588) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [db5a886817](https://linux-hardware.org/?probe=db5a886817) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | Notebook    | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | Notebook    | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| Positivo      | Mobile                      | Notebook    | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | Notebook    | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| HP            | 8540w                       | Notebook    | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | Notebook    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a5cfd24a43](https://linux-hardware.org/?probe=a5cfd24a43) | Nov 18, 2022 |
| Dell          | Latitude 5490               | Notebook    | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | K53U                        | Notebook    | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| MSI           | MS-7309                     | Desktop     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | Notebook    | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [27af8e61c5](https://linux-hardware.org/?probe=27af8e61c5) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | Desktop     | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [640298162b](https://linux-hardware.org/?probe=640298162b) | Nov 07, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| MSI           | CSM-H87M-G43                | Desktop     | [43ffdafb80](https://linux-hardware.org/?probe=43ffdafb80) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [48d6ba4c24](https://linux-hardware.org/?probe=48d6ba4c24) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [1acbe713b6](https://linux-hardware.org/?probe=1acbe713b6) | Nov 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [428b353c2c](https://linux-hardware.org/?probe=428b353c2c) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | Desktop     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [caefae88bf](https://linux-hardware.org/?probe=caefae88bf) | Oct 30, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | Notebook    | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fad928e72](https://linux-hardware.org/?probe=8fad928e72) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fef5f08978](https://linux-hardware.org/?probe=fef5f08978) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [275bc51aaf](https://linux-hardware.org/?probe=275bc51aaf) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Dell          | 500                         | Notebook    | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | Notebook    | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Samsung       | NC10                        | Notebook    | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Dell          | 0N36HY A09                  | Server      | [464fda30a8](https://linux-hardware.org/?probe=464fda30a8) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| HP            | 255 G1                      | Notebook    | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | 0WF810                      | Desktop     | [dd24119965](https://linux-hardware.org/?probe=dd24119965) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fc4e415fe4](https://linux-hardware.org/?probe=fc4e415fe4) | Oct 02, 2022 |
| Dell          | 500                         | Notebook    | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [1001ccbbaf](https://linux-hardware.org/?probe=1001ccbbaf) | Sep 30, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| Gigabyte      | H81M-D2W                    | Desktop     | [467845e1c1](https://linux-hardware.org/?probe=467845e1c1) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| ASRock        | 775Dual-VSTA                | Desktop     | [9509fb65dd](https://linux-hardware.org/?probe=9509fb65dd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [3f6203e550](https://linux-hardware.org/?probe=3f6203e550) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| ASUSTek       | P6T                         | Desktop     | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | Notebook    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| Dell          | Precision 7750              | Notebook    | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d852f09d43](https://linux-hardware.org/?probe=d852f09d43) | Sep 15, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a0bdfffa04](https://linux-hardware.org/?probe=a0bdfffa04) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [196e6b048b](https://linux-hardware.org/?probe=196e6b048b) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [8e95a850da](https://linux-hardware.org/?probe=8e95a850da) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [499d354033](https://linux-hardware.org/?probe=499d354033) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a830a7b6e5](https://linux-hardware.org/?probe=a830a7b6e5) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [19ba71f923](https://linux-hardware.org/?probe=19ba71f923) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ad888e4455](https://linux-hardware.org/?probe=ad888e4455) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d35bf4c513](https://linux-hardware.org/?probe=d35bf4c513) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [dce51bb6d6](https://linux-hardware.org/?probe=dce51bb6d6) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [3bc232858d](https://linux-hardware.org/?probe=3bc232858d) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ca79460771](https://linux-hardware.org/?probe=ca79460771) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [1e24243624](https://linux-hardware.org/?probe=1e24243624) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b0625e01e3](https://linux-hardware.org/?probe=b0625e01e3) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [f97cd53683](https://linux-hardware.org/?probe=f97cd53683) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [cd3fc03204](https://linux-hardware.org/?probe=cd3fc03204) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| HP            | 1000                        | Notebook    | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0R092H                      | Desktop     | [a22af2bad5](https://linux-hardware.org/?probe=a22af2bad5) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| Nvidia        | Tegra                       | Soc         | [bf3fee013b](https://linux-hardware.org/?probe=bf3fee013b) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [31fdd16d2f](https://linux-hardware.org/?probe=31fdd16d2f) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [24647846ee](https://linux-hardware.org/?probe=24647846ee) | Sep 06, 2022 |
| MSI           | MS-7387                     | Desktop     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| Dell          | Latitude 9520               | Notebook    | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [c3212ee5a3](https://linux-hardware.org/?probe=c3212ee5a3) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [673b33ac0c](https://linux-hardware.org/?probe=673b33ac0c) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [18a2d69632](https://linux-hardware.org/?probe=18a2d69632) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [965107cf86](https://linux-hardware.org/?probe=965107cf86) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [d8f5734dd8](https://linux-hardware.org/?probe=d8f5734dd8) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [b2f37a3080](https://linux-hardware.org/?probe=b2f37a3080) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [91857942dd](https://linux-hardware.org/?probe=91857942dd) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [940fb9c208](https://linux-hardware.org/?probe=940fb9c208) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [10315fa577](https://linux-hardware.org/?probe=10315fa577) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [aedc37e8e4](https://linux-hardware.org/?probe=aedc37e8e4) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| DNI           | SNDTP-1513N 5508015890      | Desktop     | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [b54e74887f](https://linux-hardware.org/?probe=b54e74887f) | Aug 29, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Intel         | H61                         | Desktop     | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
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
| HP            | 844C                        | Desktop     | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [3f06afc812](https://linux-hardware.org/?probe=3f06afc812) | Aug 21, 2022 |
| Acer          | Unknown                     | Notebook    | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [38fd87d37c](https://linux-hardware.org/?probe=38fd87d37c) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | Notebook    | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [d6c22de1e9](https://linux-hardware.org/?probe=d6c22de1e9) | Aug 18, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c4336ae88d](https://linux-hardware.org/?probe=c4336ae88d) | Aug 17, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| Dell          | 0RY007                      | Desktop     | [a863b6949c](https://linux-hardware.org/?probe=a863b6949c) | Aug 16, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| ASUSTek       | K84C                        | Notebook    | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Dell          | 0RY007                      | Desktop     | [592206f3e1](https://linux-hardware.org/?probe=592206f3e1) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | Notebook    | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Dell          | 0RY007                      | Desktop     | [05edd2876d](https://linux-hardware.org/?probe=05edd2876d) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Xubuntu 20.04        | 1963      | 46.76%  |
| Xubuntu 18.04        | 1041      | 24.8%   |
| Xubuntu 22.04        | 494       | 11.77%  |
| Xubuntu 19.10        | 199       | 4.74%   |
| Xubuntu 16.04        | 97        | 2.31%   |
| Xubuntu 21.10        | 96        | 2.29%   |
| Xubuntu 20.10        | 93        | 2.22%   |
| Xubuntu 21.04        | 80        | 1.91%   |
| Xubuntu 22.10        | 53        | 1.26%   |
| Xubuntu 23.04        | 27        | 0.64%   |
| Xubuntu 19.04        | 26        | 0.62%   |
| Xubuntu 18.10        | 11        | 0.26%   |
| Xubuntu 17.10        | 6         | 0.14%   |
| Xubuntu              | 6         | 0.14%   |
| Xubuntu 14.04        | 3         | 0.07%   |
| Xubuntu 17.04        | 2         | 0.05%   |
| Xubuntu 2023.1-beta5 | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Xubuntu | 4046      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 156       | 3.26%   |
| 5.4.0-48-generic    | 65        | 1.36%   |
| 5.4.0-58-generic    | 60        | 1.25%   |
| 5.4.0-52-generic    | 59        | 1.23%   |
| 5.3.0-46-generic    | 59        | 1.23%   |
| 5.15.0-56-generic   | 51        | 1.06%   |
| 5.11.0-27-generic   | 50        | 1.04%   |
| 5.4.0-65-generic    | 48        | 1%      |
| 5.3.0-40-generic    | 48        | 1%      |
| 5.4.0-29-generic    | 46        | 0.96%   |
| 5.4.0-54-generic    | 45        | 0.94%   |
| 5.15.0-52-generic   | 44        | 0.92%   |
| 5.4.0-47-generic    | 42        | 0.88%   |
| 5.4.0-42-lowlatency | 40        | 0.83%   |
| 5.4.0-26-generic    | 38        | 0.79%   |
| 5.3.0-42-generic    | 38        | 0.79%   |
| 5.3.0-28-generic    | 36        | 0.75%   |
| 5.4.0-40-generic    | 35        | 0.73%   |
| 5.0.0-37-generic    | 35        | 0.73%   |
| 5.3.0-51-generic    | 34        | 0.71%   |
| 5.4.0-37-generic    | 33        | 0.69%   |
| 5.4.0-66-generic    | 31        | 0.65%   |
| 5.15.0-47-generic   | 31        | 0.65%   |
| 4.15.0-99-generic   | 31        | 0.65%   |
| 5.4.0-89-generic    | 30        | 0.63%   |
| 5.4.0-31-generic    | 30        | 0.63%   |
| 5.15.0-58-generic   | 30        | 0.63%   |
| 5.15.0-48-generic   | 30        | 0.63%   |
| 5.15.0-46-generic   | 29        | 0.61%   |
| 5.4.0-72-generic    | 28        | 0.58%   |
| 5.3.0-53-generic    | 28        | 0.58%   |
| 5.4.0-29-lowlatency | 27        | 0.56%   |
| 5.4.0-91-generic    | 26        | 0.54%   |
| 5.4.0-81-generic    | 26        | 0.54%   |
| 5.13.0-39-generic   | 26        | 0.54%   |
| 5.8.0-53-generic    | 25        | 0.52%   |
| 5.4.0-33-generic    | 25        | 0.52%   |
| 5.15.0-60-generic   | 25        | 0.52%   |
| 5.8.0-43-generic    | 24        | 0.5%    |
| 5.4.0-56-generic    | 24        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1599      | 37.39%  |
| 4.15.0  | 484       | 11.32%  |
| 5.15.0  | 461       | 10.78%  |
| 5.3.0   | 438       | 10.24%  |
| 5.11.0  | 275       | 6.43%   |
| 5.8.0   | 255       | 5.96%   |
| 5.13.0  | 223       | 5.21%   |
| 5.19.0  | 119       | 2.78%   |
| 5.0.0   | 107       | 2.5%    |
| 4.4.0   | 47        | 1.1%    |
| 6.2.0   | 27        | 0.63%   |
| 4.18.0  | 26        | 0.61%   |
| 5.17.0  | 12        | 0.28%   |
| 4.13.0  | 9         | 0.21%   |
| 6.1.0   | 6         | 0.14%   |
| 4.10.0  | 6         | 0.14%   |
| 5.6.0   | 5         | 0.12%   |
| 5.14.0  | 5         | 0.12%   |
| 5.10.0  | 5         | 0.12%   |
| 5.18.0  | 4         | 0.09%   |
| 6.0.0   | 3         | 0.07%   |
| 5.9.8   | 3         | 0.07%   |
| 5.9.16  | 3         | 0.07%   |
| 5.4.217 | 3         | 0.07%   |
| 5.15.1  | 3         | 0.07%   |
| 5.11.16 | 3         | 0.07%   |
| 4.8.0   | 3         | 0.07%   |
| 6.2.7   | 2         | 0.05%   |
| 6.2.2   | 2         | 0.05%   |
| 6.1.30  | 2         | 0.05%   |
| 6.0.9   | 2         | 0.05%   |
| 5.9.0   | 2         | 0.05%   |
| 5.7.7   | 2         | 0.05%   |
| 5.7.6   | 2         | 0.05%   |
| 5.7.1   | 2         | 0.05%   |
| 5.7.0   | 2         | 0.05%   |
| 5.6.19  | 2         | 0.05%   |
| 5.5.19  | 2         | 0.05%   |
| 5.16.9  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1609      | 37.66%  |
| 4.15    | 484       | 11.33%  |
| 5.15    | 476       | 11.14%  |
| 5.3     | 440       | 10.3%   |
| 5.11    | 282       | 6.6%    |
| 5.8     | 260       | 6.08%   |
| 5.13    | 227       | 5.31%   |
| 5.19    | 122       | 2.86%   |
| 5.0     | 109       | 2.55%   |
| 4.4     | 52        | 1.22%   |
| 6.2     | 33        | 0.77%   |
| 4.18    | 26        | 0.61%   |
| 5.10    | 16        | 0.37%   |
| 5.17    | 13        | 0.3%    |
| 6.1     | 11        | 0.26%   |
| 5.9     | 11        | 0.26%   |
| 5.7     | 10        | 0.23%   |
| 5.6     | 10        | 0.23%   |
| 5.14    | 10        | 0.23%   |
| 4.13    | 9         | 0.21%   |
| 5.12    | 8         | 0.19%   |
| 4.19    | 7         | 0.16%   |
| 6.0     | 6         | 0.14%   |
| 5.18    | 6         | 0.14%   |
| 4.10    | 6         | 0.14%   |
| 5.16    | 5         | 0.12%   |
| 4.9     | 5         | 0.12%   |
| 6.3     | 4         | 0.09%   |
| 5.5     | 3         | 0.07%   |
| 4.8     | 3         | 0.07%   |
| 5.2     | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.11    | 2         | 0.05%   |
| 4.20    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |
| 3.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3495      | 86.25%  |
| i686    | 509       | 12.56%  |
| aarch64 | 36        | 0.89%   |
| armv7l  | 12        | 0.3%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 3901      | 96.23%  |
| GNOME           | 106       | 2.61%   |
| KDE5            | 9         | 0.22%   |
| i3              | 9         | 0.22%   |
| Cinnamon        | 8         | 0.2%    |
| Unity           | 4         | 0.1%    |
| GNOME Flashback | 4         | 0.1%    |
| X-Cinnamon      | 3         | 0.07%   |
| MATE            | 2         | 0.05%   |
| LXQt            | 2         | 0.05%   |
| GNUstep         | 2         | 0.05%   |
| xmonad          | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |
| Unknown         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3972      | 98.03%  |
| Tty     | 55        | 1.36%   |
| Wayland | 20        | 0.49%   |
| Web     | 3         | 0.07%   |
| Unknown | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2104      | 50.31%  |
| LightDM | 1445      | 34.55%  |
| TDM     | 508       | 12.15%  |
| GDM3    | 57        | 1.36%   |
| GDM     | 48        | 1.15%   |
| SDDM    | 13        | 0.31%   |
| XDM     | 4         | 0.1%    |
| SLiM    | 2         | 0.05%   |
| NODM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1332      | 32.74%  |
| de_DE   | 424       | 10.42%  |
| fr_FR   | 355       | 8.73%   |
| it_IT   | 267       | 6.56%   |
| ru_RU   | 202       | 4.97%   |
| pt_BR   | 199       | 4.89%   |
| en_GB   | 152       | 3.74%   |
| C       | 135       | 3.32%   |
| es_ES   | 106       | 2.61%   |
| en_CA   | 97        | 2.38%   |
| Unknown | 82        | 2.02%   |
| en_AU   | 70        | 1.72%   |
| pl_PL   | 61        | 1.5%    |
| es_AR   | 42        | 1.03%   |
| nl_NL   | 38        | 0.93%   |
| hu_HU   | 38        | 0.93%   |
| ja_JP   | 37        | 0.91%   |
| cs_CZ   | 34        | 0.84%   |
| en_IN   | 26        | 0.64%   |
| es_MX   | 23        | 0.57%   |
| pt_PT   | 17        | 0.42%   |
| fr_BE   | 17        | 0.42%   |
| ru_UA   | 16        | 0.39%   |
| fi_FI   | 16        | 0.39%   |
| sv_SE   | 15        | 0.37%   |
| en_ZA   | 15        | 0.37%   |
| tr_TR   | 14        | 0.34%   |
| sk_SK   | 14        | 0.34%   |
| es_CO   | 14        | 0.34%   |
| de_CH   | 14        | 0.34%   |
| el_GR   | 13        | 0.32%   |
| de_AT   | 13        | 0.32%   |
| zh_TW   | 11        | 0.27%   |
| fr_CA   | 11        | 0.27%   |
| es_VE   | 11        | 0.27%   |
| zh_CN   | 10        | 0.25%   |
| nl_BE   | 10        | 0.25%   |
| en_IL   | 7         | 0.17%   |
| ca_ES   | 7         | 0.17%   |
| bg_BG   | 7         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2665      | 65.11%  |
| EFI  | 1428      | 34.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3700      | 90.86%  |
| Overlay | 154       | 3.78%   |
| Btrfs   | 72        | 1.77%   |
| Tmpfs   | 46        | 1.13%   |
| Zfs     | 40        | 0.98%   |
| Unknown | 24        | 0.59%   |
| Xfs     | 16        | 0.39%   |
| Ext2    | 11        | 0.27%   |
| Ext3    | 7         | 0.17%   |
| Ufs     | 1         | 0.02%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2503      | 60.96%  |
| GPT     | 1054      | 25.67%  |
| MBR     | 549       | 13.37%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3454      | 83.57%  |
| Yes       | 679       | 16.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2729      | 66.24%  |
| Yes       | 1391      | 33.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 624       | 15.42%  |
| ASUSTek Computer        | 605       | 14.95%  |
| Dell                    | 492       | 12.16%  |
| Lenovo                  | 479       | 11.84%  |
| Acer                    | 269       | 6.65%   |
| Gigabyte Technology     | 233       | 5.76%   |
| MSI                     | 187       | 4.62%   |
| ASRock                  | 152       | 3.76%   |
| Toshiba                 | 101       | 2.5%    |
| Apple                   | 73        | 1.8%    |
| Intel                   | 68        | 1.68%   |
| Samsung Electronics     | 60        | 1.48%   |
| Sony                    | 50        | 1.24%   |
| Unknown                 | 46        | 1.14%   |
| Medion                  | 45        | 1.11%   |
| Fujitsu Siemens         | 33        | 0.82%   |
| Fujitsu                 | 33        | 0.82%   |
| ECS                     | 29        | 0.72%   |
| Packard Bell            | 28        | 0.69%   |
| Google                  | 23        | 0.57%   |
| Foxconn                 | 22        | 0.54%   |
| Pegatron                | 17        | 0.42%   |
| Notebook                | 17        | 0.42%   |
| Positivo                | 16        | 0.4%    |
| Raspberry Pi Foundation | 15        | 0.37%   |
| Clevo                   | 15        | 0.37%   |
| eMachines               | 14        | 0.35%   |
| IBM                     | 12        | 0.3%    |
| HUAWEI                  | 11        | 0.27%   |
| Supermicro              | 10        | 0.25%   |
| Gateway                 | 10        | 0.25%   |
| Biostar                 | 10        | 0.25%   |
| GPU Company             | 9         | 0.22%   |
| AMI                     | 9         | 0.22%   |
| LG Electronics          | 8         | 0.2%    |
| ZOTAC                   | 7         | 0.17%   |
| Alienware               | 7         | 0.17%   |
| OEM                     | 6         | 0.15%   |
| NEC Computers           | 6         | 0.15%   |
| TUXEDO                  | 5         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 70        | 1.73%   |
| ASUS All Series                        | 35        | 0.87%   |
| HP Pavilion dv6                        | 18        | 0.44%   |
| HP Notebook                            | 17        | 0.42%   |
| Gigabyte H410M S2H                     | 15        | 0.37%   |
| Dell OptiPlex 7010                     | 15        | 0.37%   |
| Dell OptiPlex 755                      | 11        | 0.27%   |
| Dell Latitude D630                     | 11        | 0.27%   |
| HP Pavilion 15                         | 10        | 0.25%   |
| HP 15                                  | 10        | 0.25%   |
| ECS G31T-M9                            | 9         | 0.22%   |
| Dell Latitude E6430                    | 9         | 0.22%   |
| ASRock N68C-S UCC                      | 9         | 0.22%   |
| Dell OptiPlex 780                      | 8         | 0.2%    |
| Dell OptiPlex 760                      | 8         | 0.2%    |
| Dell OptiPlex 390                      | 8         | 0.2%    |
| HP Pavilion g6                         | 7         | 0.17%   |
| HP Pavilion dv7                        | 7         | 0.17%   |
| HP Pavilion dv6500                     | 7         | 0.17%   |
| Dell OptiPlex 3020                     | 7         | 0.17%   |
| ASUS TUF Gaming X570-PLUS              | 7         | 0.17%   |
| MSI MS-7C37                            | 6         | 0.15%   |
| MSI MS-7817                            | 6         | 0.15%   |
| MSI MS-7721                            | 6         | 0.15%   |
| HP EliteDesk 800 G1 SFF                | 6         | 0.15%   |
| Dell OptiPlex 9020                     | 6         | 0.15%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.15%   |
| MSI MS-7C02                            | 5         | 0.12%   |
| MSI MS-7B89                            | 5         | 0.12%   |
| MSI MS-7B79                            | 5         | 0.12%   |
| MSI MS-7A38                            | 5         | 0.12%   |
| Intel H61                              | 5         | 0.12%   |
| HP EliteBook 840 G3                    | 5         | 0.12%   |
| HP Compaq Pro 6300 SFF                 | 5         | 0.12%   |
| HP Compaq Elite 8300 SFF               | 5         | 0.12%   |
| HP Compaq dc7600 Small Form Factor     | 5         | 0.12%   |
| Gigabyte 945GZM-S2                     | 5         | 0.12%   |
| Dell OptiPlex GX620                    | 5         | 0.12%   |
| Dell Latitude E6520                    | 5         | 0.12%   |
| Dell Latitude E6400                    | 5         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 241       | 5.96%   |
| Acer Aspire           | 169       | 4.18%   |
| Dell Inspiron         | 131       | 3.24%   |
| Dell Latitude         | 124       | 3.06%   |
| HP Pavilion           | 115       | 2.84%   |
| HP Compaq             | 113       | 2.79%   |
| Dell OptiPlex         | 102       | 2.52%   |
| Toshiba Satellite     | 85        | 2.1%    |
| Lenovo IdeaPad        | 70        | 1.73%   |
| Unknown               | 70        | 1.73%   |
| HP EliteBook          | 59        | 1.46%   |
| ASUS PRIME            | 49        | 1.21%   |
| HP ProBook            | 44        | 1.09%   |
| Lenovo ThinkCentre    | 42        | 1.04%   |
| HP Laptop             | 41        | 1.01%   |
| Dell Precision        | 37        | 0.91%   |
| ASUS VivoBook         | 37        | 0.91%   |
| ASUS All              | 35        | 0.87%   |
| Dell XPS              | 22        | 0.54%   |
| Dell Vostro           | 22        | 0.54%   |
| ASUS TUF              | 21        | 0.52%   |
| HP ProDesk            | 18        | 0.44%   |
| HP Notebook           | 18        | 0.44%   |
| Acer Veriton          | 18        | 0.44%   |
| Acer Extensa          | 18        | 0.44%   |
| ASUS ROG              | 17        | 0.42%   |
| Gigabyte H410M        | 16        | 0.4%    |
| RPi Raspberry         | 15        | 0.37%   |
| Fujitsu Siemens AMILO | 15        | 0.37%   |
| Dell PowerEdge        | 15        | 0.37%   |
| Packard Bell EasyNote | 14        | 0.35%   |
| HP ENVY               | 14        | 0.35%   |
| HP EliteDesk          | 14        | 0.35%   |
| Fujitsu LIFEBOOK      | 14        | 0.35%   |
| Fujitsu ESPRIMO       | 12        | 0.3%    |
| Dell Studio           | 12        | 0.3%    |
| Lenovo IdeaCentre     | 11        | 0.27%   |
| HP Presario           | 11        | 0.27%   |
| HP Mini               | 11        | 0.27%   |
| HP 255                | 11        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 342       | 8.45%   |
| 2011    | 337       | 8.33%   |
| 2010    | 304       | 7.51%   |
| 2008    | 295       | 7.29%   |
| 2013    | 294       | 7.27%   |
| 2009    | 278       | 6.87%   |
| 2007    | 269       | 6.65%   |
| 2019    | 239       | 5.91%   |
| 2014    | 229       | 5.66%   |
| 2018    | 224       | 5.54%   |
| 2020    | 208       | 5.14%   |
| 2017    | 207       | 5.12%   |
| 2015    | 163       | 4.03%   |
| 2016    | 160       | 3.95%   |
| 2006    | 146       | 3.61%   |
| 2021    | 144       | 3.56%   |
| 2005    | 71        | 1.75%   |
| 2022    | 45        | 1.11%   |
| Unknown | 44        | 1.09%   |
| 2004    | 16        | 0.4%    |
| 2003    | 16        | 0.4%    |
| 2023    | 7         | 0.17%   |
| 2002    | 4         | 0.1%    |
| 2001    | 4         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2202      | 54.42%  |
| Desktop        | 1607      | 39.72%  |
| Mini pc        | 54        | 1.33%   |
| System on chip | 45        | 1.11%   |
| All in one     | 45        | 1.11%   |
| Convertible    | 41        | 1.01%   |
| Server         | 34        | 0.84%   |
| Tablet         | 16        | 0.4%    |
| Other          | 1         | 0.02%   |
| Firewall       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3842      | 94.54%  |
| Enabled  | 222       | 5.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4021      | 99.38%  |
| Yes  | 25        | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1094      | 26.65%  |
| 4.01-8.0        | 780       | 19%     |
| 8.01-16.0       | 551       | 13.42%  |
| 16.01-24.0      | 523       | 12.74%  |
| 1.01-2.0        | 471       | 11.47%  |
| 32.01-64.0      | 226       | 5.51%   |
| 2.01-3.0        | 155       | 3.78%   |
| 0.51-1.0        | 154       | 3.75%   |
| 64.01-256.0     | 90        | 2.19%   |
| 24.01-32.0      | 47        | 1.14%   |
| 0.01-0.5        | 12        | 0.29%   |
| More than 256.0 | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1861      | 41.56%  |
| 0.51-1.0   | 870       | 19.43%  |
| 2.01-3.0   | 819       | 18.29%  |
| 4.01-8.0   | 364       | 8.13%   |
| 3.01-4.0   | 307       | 6.86%   |
| 0.01-0.5   | 123       | 2.75%   |
| 8.01-16.0  | 106       | 2.37%   |
| 16.01-24.0 | 16        | 0.36%   |
| 24.01-32.0 | 8         | 0.18%   |
| 32.01-64.0 | 2         | 0.04%   |
| Unknown    | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2583      | 62.08%  |
| 2      | 995       | 23.91%  |
| 3      | 315       | 7.57%   |
| 4      | 118       | 2.84%   |
| 5      | 56        | 1.35%   |
| 0      | 47        | 1.13%   |
| 6      | 22        | 0.53%   |
| 7      | 14        | 0.34%   |
| 10     | 4         | 0.1%    |
| 9      | 3         | 0.07%   |
| 8      | 3         | 0.07%   |
| 11     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2100      | 51.55%  |
| No        | 1974      | 48.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3660      | 90.39%  |
| No        | 389       | 9.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2926      | 71.8%   |
| No        | 1149      | 28.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2292      | 55.94%  |
| Yes       | 1805      | 44.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 642       | 15.78%  |
| Germany      | 515       | 12.66%  |
| France       | 375       | 9.22%   |
| Italy        | 300       | 7.37%   |
| Russia       | 257       | 6.32%   |
| Brazil       | 229       | 5.63%   |
| Canada       | 152       | 3.74%   |
| UK           | 148       | 3.64%   |
| Spain        | 129       | 3.17%   |
| Netherlands  | 98        | 2.41%   |
| Australia    | 82        | 2.02%   |
| Poland       | 78        | 1.92%   |
| Argentina    | 58        | 1.43%   |
| Ukraine      | 55        | 1.35%   |
| Belgium      | 51        | 1.25%   |
| Mexico       | 46        | 1.13%   |
| Czechia      | 46        | 1.13%   |
| Hungary      | 44        | 1.08%   |
| Japan        | 43        | 1.06%   |
| Sweden       | 42        | 1.03%   |
| Finland      | 39        | 0.96%   |
| India        | 36        | 0.88%   |
| Portugal     | 35        | 0.86%   |
| Greece       | 34        | 0.84%   |
| Austria      | 29        | 0.71%   |
| Indonesia    | 27        | 0.66%   |
| Bulgaria     | 27        | 0.66%   |
| Turkey       | 23        | 0.57%   |
| Switzerland  | 22        | 0.54%   |
| Romania      | 22        | 0.54%   |
| Slovakia     | 18        | 0.44%   |
| Iran         | 18        | 0.44%   |
| Colombia     | 18        | 0.44%   |
| Norway       | 16        | 0.39%   |
| Taiwan       | 15        | 0.37%   |
| South Africa | 15        | 0.37%   |
| Venezuela    | 14        | 0.34%   |
| Israel       | 13        | 0.32%   |
| Denmark      | 13        | 0.32%   |
| China        | 12        | 0.29%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 53        | 1.23%   |
| Berlin            | 48        | 1.12%   |
| Moscow            | 44        | 1.02%   |
| Voronezh          | 37        | 0.86%   |
| Milan             | 36        | 0.84%   |
| Rome              | 35        | 0.81%   |
| Sydney            | 26        | 0.6%    |
| Warsaw            | 25        | 0.58%   |
| Sao Paulo         | 25        | 0.58%   |
| Amsterdam         | 25        | 0.58%   |
| Munich            | 24        | 0.56%   |
| Athens            | 24        | 0.56%   |
| Madrid            | 23        | 0.54%   |
| St Petersburg     | 22        | 0.51%   |
| Hamburg           | 22        | 0.51%   |
| Budapest          | 20        | 0.47%   |
| Québec           | 19        | 0.44%   |
| Rio de Janeiro    | 18        | 0.42%   |
| Helsinki          | 17        | 0.4%    |
| Melbourne         | 16        | 0.37%   |
| Genoa             | 16        | 0.37%   |
| Barcelona         | 16        | 0.37%   |
| Oryol             | 15        | 0.35%   |
| Montreal          | 15        | 0.35%   |
| Kyiv              | 15        | 0.35%   |
| Buenos Aires      | 15        | 0.35%   |
| Turin             | 14        | 0.33%   |
| Vancouver         | 13        | 0.3%    |
| Tehran            | 13        | 0.3%    |
| Stuttgart         | 13        | 0.3%    |
| Sofia             | 13        | 0.3%    |
| Prague            | 13        | 0.3%    |
| Frankfurt am Main | 13        | 0.3%    |
| Vienna            | 12        | 0.28%   |
| Toronto           | 12        | 0.28%   |
| Leipzig           | 12        | 0.28%   |
| Cologne           | 11        | 0.26%   |
| Chicago           | 11        | 0.26%   |
| Belo Horizonte    | 11        | 0.26%   |
| Yokohama          | 10        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1003      | 1472   | 17.93%  |
| WDC                 | 958       | 1393   | 17.13%  |
| Samsung Electronics | 752       | 1058   | 13.45%  |
| Toshiba             | 385       | 483    | 6.88%   |
| Hitachi             | 321       | 423    | 5.74%   |
| Unknown             | 283       | 360    | 5.06%   |
| Kingston            | 254       | 323    | 4.54%   |
| SanDisk             | 199       | 251    | 3.56%   |
| Crucial             | 153       | 203    | 2.74%   |
| HGST                | 111       | 134    | 1.98%   |
| Intel               | 103       | 145    | 1.84%   |
| SK hynix            | 83        | 99     | 1.48%   |
| A-DATA Technology   | 76        | 98     | 1.36%   |
| Fujitsu             | 70        | 87     | 1.25%   |
| China               | 63        | 73     | 1.13%   |
| Maxtor              | 60        | 85     | 1.07%   |
| Micron Technology   | 46        | 51     | 0.82%   |
| PNY                 | 38        | 50     | 0.68%   |
| Patriot             | 32        | 37     | 0.57%   |
| Transcend           | 27        | 29     | 0.48%   |
| Phison              | 27        | 43     | 0.48%   |
| OCZ                 | 27        | 35     | 0.48%   |
| Intenso             | 27        | 34     | 0.48%   |
| SPCC                | 23        | 35     | 0.41%   |
| KIOXIA              | 22        | 28     | 0.39%   |
| Apple               | 19        | 27     | 0.34%   |
| Unknown             | 19        | 19     | 0.34%   |
| LITEONIT            | 16        | 19     | 0.29%   |
| LITEON              | 16        | 18     | 0.29%   |
| Apacer              | 16        | 22     | 0.29%   |
| Silicon Motion      | 15        | 16     | 0.27%   |
| ASMT                | 15        | 24     | 0.27%   |
| JMicron Technology  | 13        | 13     | 0.23%   |
| KingDian            | 12        | 18     | 0.21%   |
| Hewlett-Packard     | 12        | 19     | 0.21%   |
| Lexar               | 9         | 9      | 0.16%   |
| KingSpec            | 9         | 11     | 0.16%   |
| USB3.0              | 7         | 10     | 0.13%   |
| Smartbuy            | 7         | 7      | 0.13%   |
| Plextor             | 7         | 12     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 67        | 1.1%    |
| Unknown MMC Card  32GB              | 54        | 0.88%   |
| Seagate ST500DM002-1BD142 500GB     | 53        | 0.87%   |
| Samsung SSD 860 EVO 500GB           | 46        | 0.75%   |
| Kingston SA400S37480G 480GB SSD     | 40        | 0.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 35        | 0.57%   |
| Samsung SSD 850 EVO 250GB           | 34        | 0.56%   |
| Unknown MMC Card  64GB              | 32        | 0.52%   |
| Seagate ST500LT012-1DG142 500GB     | 32        | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB      | 31        | 0.51%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 30        | 0.49%   |
| Samsung SSD 850 EVO 500GB           | 30        | 0.49%   |
| Toshiba MQ01ABF050 500GB            | 27        | 0.44%   |
| Toshiba MQ01ABD100 1TB              | 27        | 0.44%   |
| Seagate Expansion 1TB               | 26        | 0.42%   |
| Kingston SA400S37120G 120GB SSD     | 26        | 0.42%   |
| Seagate ST3500418AS 500GB           | 25        | 0.41%   |
| Seagate ST1000LM035-1RK172 1TB      | 25        | 0.41%   |
| Unknown SD/MMC/MS PRO 250GB         | 24        | 0.39%   |
| Toshiba DT01ACA100 1TB              | 24        | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB      | 22        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD    | 22        | 0.36%   |
| Unknown MMC Card  128GB             | 21        | 0.34%   |
| HGST HTS721010A9E630 1TB            | 21        | 0.34%   |
| HGST HTS541010A9E680 1TB            | 21        | 0.34%   |
| Unknown MMC Card  16GB              | 20        | 0.33%   |
| Seagate ST9500325AS 500GB           | 20        | 0.33%   |
| Seagate ST2000DM001-1CH164 2TB      | 20        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB      | 20        | 0.33%   |
| Seagate ST31000528AS 1TB            | 19        | 0.31%   |
| Samsung SSD 860 EVO 250GB           | 19        | 0.31%   |
| Samsung SSD 860 EVO 1TB             | 19        | 0.31%   |
| Crucial CT500MX500SSD1 500GB        | 19        | 0.31%   |
| Unknown                             | 19        | 0.31%   |
| Seagate ST9320325AS 320GB           | 18        | 0.29%   |
| Crucial CT240BX500SSD1 240GB        | 18        | 0.29%   |
| Seagate ST500LT012-9WS142 500GB     | 17        | 0.28%   |
| Seagate ST4000DM004-2CV104 4TB      | 17        | 0.28%   |
| WDC WD10JPVX-22JC3T0 1TB            | 16        | 0.26%   |
| Samsung NVMe SSD Drive 256GB        | 16        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 986       | 1444   | 32.97%  |
| WDC                 | 838       | 1219   | 28.02%  |
| Toshiba             | 328       | 416    | 10.97%  |
| Hitachi             | 321       | 423    | 10.73%  |
| Samsung Electronics | 192       | 267    | 6.42%   |
| HGST                | 111       | 134    | 3.71%   |
| Fujitsu             | 68        | 85     | 2.27%   |
| Maxtor              | 58        | 83     | 1.94%   |
| Unknown             | 25        | 29     | 0.84%   |
| USB3.0              | 7         | 10     | 0.23%   |
| IBM/Hitachi         | 7         | 7      | 0.23%   |
| ASMT                | 7         | 13     | 0.23%   |
| Intenso             | 5         | 6      | 0.17%   |
| SSK                 | 4         | 4      | 0.13%   |
| Hewlett-Packard     | 4         | 7      | 0.13%   |
| Pioneer             | 3         | 3      | 0.1%    |
| Apple               | 3         | 4      | 0.1%    |
| WD MediaMax         | 2         | 2      | 0.07%   |
| PHD 3.0             | 2         | 2      | 0.07%   |
| Inateck             | 2         | 2      | 0.07%   |
| HPE                 | 2         | 5      | 0.07%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| ExcelStor           | 2         | 2      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| Apricorn            | 2         | 3      | 0.07%   |
| Super Talent        | 1         | 1      | 0.03%   |
| SAGE                | 1         | 1      | 0.03%   |
| LaCie               | 1         | 5      | 0.03%   |
| ICY BOX             | 1         | 1      | 0.03%   |
| Ext Hard            | 1         | 1      | 0.03%   |
| CLOVER              | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 386       | 527    | 23.11%  |
| Kingston            | 226       | 285    | 13.53%  |
| SanDisk             | 150       | 196    | 8.98%   |
| Crucial             | 140       | 190    | 8.38%   |
| WDC                 | 81        | 104    | 4.85%   |
| A-DATA Technology   | 65        | 86     | 3.89%   |
| China               | 63        | 73     | 3.77%   |
| Intel               | 54        | 78     | 3.23%   |
| PNY                 | 37        | 49     | 2.22%   |
| Patriot             | 32        | 37     | 1.92%   |
| Toshiba             | 30        | 37     | 1.8%    |
| Micron Technology   | 30        | 34     | 1.8%    |
| OCZ                 | 26        | 33     | 1.56%   |
| Transcend           | 25        | 25     | 1.5%    |
| SPCC                | 23        | 35     | 1.38%   |
| SK hynix            | 23        | 24     | 1.38%   |
| Intenso             | 20        | 22     | 1.2%    |
| LITEONIT            | 16        | 19     | 0.96%   |
| LITEON              | 16        | 18     | 0.96%   |
| Apacer              | 15        | 21     | 0.9%    |
| KingDian            | 12        | 18     | 0.72%   |
| Apple               | 10        | 14     | 0.6%    |
| Unknown             | 8         | 9      | 0.48%   |
| Lexar               | 8         | 8      | 0.48%   |
| KingSpec            | 8         | 10     | 0.48%   |
| ASMT                | 8         | 11     | 0.48%   |
| Smartbuy            | 7         | 7      | 0.42%   |
| Plextor             | 7         | 12     | 0.42%   |
| GOODRAM             | 7         | 9      | 0.42%   |
| TO Exter            | 6         | 8      | 0.36%   |
| Team                | 6         | 12     | 0.36%   |
| Hewlett-Packard     | 6         | 9      | 0.36%   |
| Corsair             | 6         | 7      | 0.36%   |
| Netac               | 5         | 9      | 0.3%    |
| Mushkin             | 5         | 5      | 0.3%    |
| FORESEE             | 5         | 8      | 0.3%    |
| Dogfish             | 5         | 8      | 0.3%    |
| Drevo               | 4         | 4      | 0.24%   |
| Vaseky              | 3         | 4      | 0.18%   |
| Seagate             | 3         | 3      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2525      | 4186   | 50.62%  |
| SSD     | 1501      | 2163   | 30.09%  |
| NVMe    | 620       | 810    | 12.43%  |
| MMC     | 264       | 339    | 5.29%   |
| Unknown | 78        | 99     | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3439      | 6137   | 75.6%   |
| NVMe | 611       | 799    | 13.43%  |
| MMC  | 264       | 339    | 5.8%    |
| SAS  | 235       | 322    | 5.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2822      | 4258   | 67.03%  |
| 0.51-1.0        | 944       | 1355   | 22.42%  |
| 1.01-2.0        | 244       | 396    | 5.8%    |
| 3.01-4.0        | 77        | 136    | 1.83%   |
| 4.01-10.0       | 59        | 93     | 1.4%    |
| 2.01-3.0        | 58        | 103    | 1.38%   |
| 10.01-20.0      | 4         | 6      | 0.1%    |
| More than 100.0 | 1         | 1      | 0.02%   |
| 0               | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1309      | 31.04%  |
| 251-500        | 951       | 22.55%  |
| 501-1000       | 538       | 12.76%  |
| 51-100         | 382       | 9.06%   |
| 21-50          | 278       | 6.59%   |
| 1001-2000      | 276       | 6.54%   |
| 1-20           | 198       | 4.7%    |
| More than 3000 | 157       | 3.72%   |
| 2001-3000      | 101       | 2.4%    |
| Unknown        | 27        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1782      | 40.69%  |
| 21-50          | 756       | 17.26%  |
| 101-250        | 550       | 12.56%  |
| 51-100         | 514       | 11.74%  |
| 251-500        | 298       | 6.81%   |
| 501-1000       | 226       | 5.16%   |
| 1001-2000      | 114       | 2.6%    |
| More than 3000 | 67        | 1.53%   |
| 2001-3000      | 45        | 1.03%   |
| Unknown        | 27        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 9      | 2.69%   |
| Seagate ST500DM002-1BD142 500GB     | 7         | 7      | 2.1%    |
| Seagate ST9500325AS 500GB           | 6         | 8      | 1.8%    |
| Toshiba MQ01ABD100 1TB              | 5         | 6      | 1.5%    |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 1.5%    |
| Seagate ST2000DM001-1CH164 2TB      | 4         | 6      | 1.2%    |
| Samsung Electronics HM321HI 320GB   | 4         | 5      | 1.2%    |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 0.9%    |
| Seagate ST3500418AS 500GB           | 3         | 4      | 0.9%    |
| Maxtor STM3160215AS 160GB           | 3         | 3      | 0.9%    |
| Hitachi HDS721050CLA362 500GB       | 3         | 3      | 0.9%    |
| HGST HTS545050A7E680 500GB          | 3         | 3      | 0.9%    |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 0.9%    |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 2         | 2      | 0.6%    |
| WDC WD7500BPKX-00HPJT0 752GB        | 2         | 2      | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.6%    |
| WDC WD4000FYYZ-01UL1B1 4TB          | 2         | 3      | 0.6%    |
| WDC WD3200AAKS-00L9A0 320GB         | 2         | 2      | 0.6%    |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 2      | 0.6%    |
| Toshiba MQ01ABD050 500GB            | 2         | 2      | 0.6%    |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 0.6%    |
| Toshiba DT01ACA100 1TB              | 2         | 2      | 0.6%    |
| Seagate ST9500423AS 500GB           | 2         | 2      | 0.6%    |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.6%    |
| Seagate ST9320325AS 320GB           | 2         | 2      | 0.6%    |
| Seagate ST9250410AS 250GB           | 2         | 2      | 0.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.6%    |
| Seagate ST3250318AS 250GB           | 2         | 4      | 0.6%    |
| Seagate ST320LT007-9ZV142 320GB     | 2         | 2      | 0.6%    |
| Seagate ST31000528AS 1TB            | 2         | 2      | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 2      | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB      | 2         | 2      | 0.6%    |
| Seagate ST1000DL002-9TT153 1TB      | 2         | 2      | 0.6%    |
| Samsung Electronics HD753LJ 752GB   | 2         | 3      | 0.6%    |
| Samsung Electronics HD103SJ 1TB     | 2         | 3      | 0.6%    |
| Samsung Electronics HD103SI 1TB     | 2         | 2      | 0.6%    |
| Samsung Electronics HD081GJ 80GB    | 2         | 2      | 0.6%    |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2      | 0.6%    |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 0.6%    |
| KingDian S100 32GB SSD              | 2         | 4      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 108    | 28.83%  |
| WDC                 | 64        | 74     | 19.63%  |
| Toshiba             | 32        | 38     | 9.82%   |
| Hitachi             | 29        | 36     | 8.9%    |
| Samsung Electronics | 26        | 33     | 7.98%   |
| HGST                | 10        | 13     | 3.07%   |
| Kingston            | 8         | 10     | 2.45%   |
| Fujitsu             | 8         | 9      | 2.45%   |
| Maxtor              | 7         | 7      | 2.15%   |
| Intel               | 6         | 7      | 1.84%   |
| SK hynix            | 5         | 6      | 1.53%   |
| SanDisk             | 3         | 3      | 0.92%   |
| Crucial             | 3         | 3      | 0.92%   |
| A-DATA Technology   | 3         | 4      | 0.92%   |
| OCZ                 | 2         | 2      | 0.61%   |
| Micron Technology   | 2         | 2      | 0.61%   |
| KingDian            | 2         | 4      | 0.61%   |
| China               | 2         | 2      | 0.61%   |
| Unknown             | 1         | 1      | 0.31%   |
| SSSTC               | 1         | 1      | 0.31%   |
| SPCC                | 1         | 1      | 0.31%   |
| PNY                 | 1         | 1      | 0.31%   |
| Netac               | 1         | 1      | 0.31%   |
| Neo Forza           | 1         | 1      | 0.31%   |
| Mushkin             | 1         | 1      | 0.31%   |
| LITEON              | 1         | 1      | 0.31%   |
| LDLC                | 1         | 1      | 0.31%   |
| JMicron Technology  | 1         | 1      | 0.31%   |
| ICY BOX             | 1         | 1      | 0.31%   |
| Hewlett-Packard     | 1         | 1      | 0.31%   |
| FORESEE             | 1         | 1      | 0.31%   |
| Drevo               | 1         | 1      | 0.31%   |
| Corsair             | 1         | 1      | 0.31%   |
| Avant               | 1         | 1      | 0.31%   |
| ASMT                | 1         | 4      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |
| Apacer              | 1         | 1      | 0.31%   |
| Unknown             | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 108    | 35.74%  |
| WDC                 | 61        | 71     | 23.19%  |
| Toshiba             | 31        | 37     | 11.79%  |
| Hitachi             | 29        | 36     | 11.03%  |
| Samsung Electronics | 20        | 26     | 7.6%    |
| HGST                | 10        | 13     | 3.8%    |
| Fujitsu             | 8         | 9      | 3.04%   |
| Maxtor              | 7         | 7      | 2.66%   |
| ICY BOX             | 1         | 1      | 0.38%   |
| Hewlett-Packard     | 1         | 1      | 0.38%   |
| ASMT                | 1         | 4      | 0.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 249       | 313    | 80.32%  |
| SSD  | 58        | 68     | 18.71%  |
| NVMe | 3         | 3      | 0.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00J99B0 2TB         | 1         | 2      | 25%     |
| Toshiba DT01ACA200 2TB           | 1         | 1      | 25%     |
| Seagate ST500DM002-1BC142 500GB  | 1         | 1      | 25%     |
| A-DATA Technology SP800 32GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 2      | 25%     |
| Toshiba           | 1         | 1      | 25%     |
| Seagate           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2787      | 5238   | 65.21%  |
| Works    | 1180      | 1970   | 27.61%  |
| Malfunc  | 303       | 384    | 7.09%   |
| Failed   | 4         | 5      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2813      | 61.49%  |
| AMD                              | 683       | 14.93%  |
| Samsung Electronics              | 221       | 4.83%   |
| Nvidia                           | 144       | 3.15%   |
| SanDisk                          | 93        | 2.03%   |
| JMicron Technology               | 66        | 1.44%   |
| ASMedia Technology               | 65        | 1.42%   |
| VIA Technologies                 | 55        | 1.2%    |
| SK hynix                         | 53        | 1.16%   |
| Marvell Technology Group         | 49        | 1.07%   |
| Silicon Integrated Systems [SiS] | 40        | 0.87%   |
| Kingston Technology Company      | 37        | 0.81%   |
| Phison Electronics               | 34        | 0.74%   |
| Toshiba America Info Systems     | 26        | 0.57%   |
| KIOXIA                           | 23        | 0.5%    |
| Silicon Motion                   | 21        | 0.46%   |
| Micron Technology                | 17        | 0.37%   |
| Micron/Crucial Technology        | 16        | 0.35%   |
| ADATA Technology                 | 16        | 0.35%   |
| LSI Logic / Symbios Logic        | 15        | 0.33%   |
| Broadcom / LSI                   | 11        | 0.24%   |
| Silicon Image                    | 10        | 0.22%   |
| Realtek Semiconductor            | 10        | 0.22%   |
| Adaptec                          | 7         | 0.15%   |
| ULi Electronics                  | 6         | 0.13%   |
| Hewlett-Packard                  | 6         | 0.13%   |
| Union Memory (Shenzhen)          | 5         | 0.11%   |
| Integrated Technology Express    | 5         | 0.11%   |
| Apple                            | 5         | 0.11%   |
| Promise Technology               | 4         | 0.09%   |
| Seagate Technology               | 3         | 0.07%   |
| Lite-On Technology               | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Solid State Storage Technology   | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 408       | 7.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 182       | 3.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 176       | 3.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 156       | 2.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 156       | 2.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 136       | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 135       | 2.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 125       | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 121       | 2.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 117       | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 112       | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 109       | 1.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 103       | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 96        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 92        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 80        | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 77        | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 72        | 1.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 66        | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 66        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 64        | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 63        | 1.1%    |
| AMD 400 Series Chipset SATA Controller                                                  | 63        | 1.1%    |
| Nvidia MCP61 SATA Controller                                                            | 62        | 1.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 61        | 1.07%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 61        | 1.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 60        | 1.05%   |
| Intel SATA Controller [RAID mode]                                                       | 59        | 1.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 54        | 0.94%   |
| Nvidia MCP61 IDE                                                                        | 49        | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 47        | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 47        | 0.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 45        | 0.79%   |
| Samsung NVMe SSD Controller 980                                                         | 44        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 44        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 44        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 43        | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 41        | 0.72%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 40        | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 40        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2733      | 56.26%  |
| IDE  | 1216      | 25.03%  |
| NVMe | 606       | 12.47%  |
| RAID | 276       | 5.68%   |
| SAS  | 14        | 0.29%   |
| SCSI | 13        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3135      | 77.48%  |
| AMD          | 859       | 21.23%  |
| ARM          | 47        | 1.16%   |
| CentaurHauls | 4         | 0.1%    |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Processor                           | 36        | 0.89%   |
| Intel Atom CPU N270 @ 1.60GHz           | 32        | 0.79%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 27        | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 26        | 0.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 25        | 0.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 24        | 0.59%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 24        | 0.59%   |
| Intel Pentium 4 CPU 3.00GHz             | 23        | 0.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 22        | 0.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 22        | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 22        | 0.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 21        | 0.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 21        | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 21        | 0.52%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 21        | 0.52%   |
| Intel Atom CPU N450 @ 1.66GHz           | 21        | 0.52%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 20        | 0.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 19        | 0.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 19        | 0.47%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 19        | 0.47%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 19        | 0.47%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 18        | 0.44%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 18        | 0.44%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 18        | 0.44%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 18        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 17        | 0.42%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 17        | 0.42%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 17        | 0.42%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 17        | 0.42%   |
| AMD Ryzen 5 3600 6-Core Processor       | 16        | 0.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 15        | 0.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 15        | 0.37%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 15        | 0.37%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 15        | 0.37%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 15        | 0.37%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 15        | 0.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 14        | 0.34%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 14        | 0.34%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 14        | 0.34%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 14        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 687       | 16.92%  |
| Intel Core i7           | 506       | 12.46%  |
| Intel Core 2 Duo        | 322       | 7.93%   |
| Intel Core i3           | 311       | 7.66%   |
| Intel Celeron           | 287       | 7.07%   |
| Intel Atom              | 181       | 4.46%   |
| Other                   | 150       | 3.69%   |
| Intel Pentium           | 125       | 3.08%   |
| AMD Ryzen 5             | 125       | 3.08%   |
| Intel Xeon              | 101       | 2.49%   |
| Intel Pentium Dual-Core | 89        | 2.19%   |
| AMD Ryzen 7             | 87        | 2.14%   |
| Intel Pentium Dual      | 67        | 1.65%   |
| Intel Pentium 4         | 65        | 1.6%    |
| Intel Genuine           | 59        | 1.45%   |
| Intel Core 2            | 58        | 1.43%   |
| Intel Core 2 Quad       | 54        | 1.33%   |
| AMD FX                  | 51        | 1.26%   |
| AMD A8                  | 50        | 1.23%   |
| AMD Athlon 64 X2        | 42        | 1.03%   |
| AMD E1                  | 32        | 0.79%   |
| AMD A6                  | 32        | 0.79%   |
| AMD Ryzen 9             | 30        | 0.74%   |
| AMD Ryzen 3             | 30        | 0.74%   |
| Intel Pentium M         | 28        | 0.69%   |
| AMD Phenom II X4        | 28        | 0.69%   |
| AMD Athlon II X2        | 28        | 0.69%   |
| Intel Celeron M         | 24        | 0.59%   |
| AMD A4                  | 22        | 0.54%   |
| AMD A10                 | 22        | 0.54%   |
| AMD Turion 64 X2 Mobile | 20        | 0.49%   |
| AMD Sempron             | 20        | 0.49%   |
| AMD E                   | 20        | 0.49%   |
| AMD Athlon              | 19        | 0.47%   |
| Intel Pentium D         | 17        | 0.42%   |
| AMD Ryzen 7 PRO         | 17        | 0.42%   |
| AMD E2                  | 16        | 0.39%   |
| AMD Athlon 64           | 16        | 0.39%   |
| Intel Core i9           | 15        | 0.37%   |
| Intel Pentium Silver    | 13        | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1986      | 48.95%  |
| 4       | 1247      | 30.74%  |
| 1       | 349       | 8.6%    |
| 6       | 211       | 5.2%    |
| 8       | 161       | 3.97%   |
| 12      | 39        | 0.96%   |
| 16      | 20        | 0.49%   |
| 3       | 17        | 0.42%   |
| 10      | 9         | 0.22%   |
| Unknown | 6         | 0.15%   |
| 24      | 4         | 0.1%    |
| 20      | 3         | 0.07%   |
| 14      | 3         | 0.07%   |
| 64      | 2         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3995      | 98.74%  |
| 2       | 46        | 1.14%   |
| Unknown | 5         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2032      | 50.16%  |
| 2       | 2012      | 49.67%  |
| Unknown | 6         | 0.15%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3820      | 94.39%  |
| 32-bit         | 195       | 4.82%   |
| Unknown        | 30        | 0.74%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 769       | 18.47%  |
| 0x206a7    | 267       | 6.41%   |
| 0x306a9    | 248       | 5.96%   |
| 0x1067a    | 241       | 5.79%   |
| 0x306c3    | 160       | 3.84%   |
| 0x6fd      | 145       | 3.48%   |
| 0x20655    | 90        | 2.16%   |
| 0x10676    | 84        | 2.02%   |
| 0x40651    | 68        | 1.63%   |
| 0x506e3    | 67        | 1.61%   |
| 0x906ea    | 61        | 1.47%   |
| 0x406c4    | 60        | 1.44%   |
| 0x30678    | 60        | 1.44%   |
| 0x406e3    | 56        | 1.35%   |
| 0x6fb      | 54        | 1.3%    |
| 0x106ca    | 54        | 1.3%    |
| 0x010000c8 | 53        | 1.27%   |
| 0x6f6      | 52        | 1.25%   |
| 0x806ea    | 49        | 1.18%   |
| 0x106c2    | 48        | 1.15%   |
| 0x806ec    | 46        | 1.1%    |
| 0x20652    | 46        | 1.1%    |
| 0x806c1    | 45        | 1.08%   |
| 0x806e9    | 43        | 1.03%   |
| 0x306d4    | 43        | 1.03%   |
| 0x906e9    | 40        | 0.96%   |
| 0x06000852 | 37        | 0.89%   |
| 0x08108109 | 36        | 0.86%   |
| 0x6e8      | 35        | 0.84%   |
| 0x6d8      | 34        | 0.82%   |
| 0x406c3    | 34        | 0.82%   |
| 0x106e5    | 33        | 0.79%   |
| 0x05000119 | 33        | 0.79%   |
| 0x08701021 | 31        | 0.74%   |
| 0x0800820d | 31        | 0.74%   |
| 0x07030105 | 30        | 0.72%   |
| 0x706a1    | 26        | 0.62%   |
| 0x506c9    | 26        | 0.62%   |
| 0x0700010f | 26        | 0.62%   |
| 0x06001119 | 26        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 369       | 9.1%    |
| KabyLake         | 344       | 8.48%   |
| SandyBridge      | 321       | 7.91%   |
| Core             | 308       | 7.59%   |
| IvyBridge        | 296       | 7.3%    |
| Haswell          | 282       | 6.95%   |
| Silvermont       | 189       | 4.66%   |
| Westmere         | 175       | 4.31%   |
| Skylake          | 155       | 3.82%   |
| Bonnell          | 128       | 3.16%   |
| K8 Hammer        | 127       | 3.13%   |
| K10              | 114       | 2.81%   |
| Zen 2            | 102       | 2.51%   |
| P6               | 100       | 2.47%   |
| Zen+             | 94        | 2.32%   |
| Unknown          | 93        | 2.29%   |
| NetBurst         | 92        | 2.27%   |
| Piledriver       | 73        | 1.8%    |
| CometLake        | 62        | 1.53%   |
| TigerLake        | 59        | 1.45%   |
| Broadwell        | 56        | 1.38%   |
| Zen              | 54        | 1.33%   |
| Nehalem          | 51        | 1.26%   |
| Goldmont plus    | 50        | 1.23%   |
| Bobcat           | 49        | 1.21%   |
| Zen 3            | 46        | 1.13%   |
| Puma             | 39        | 0.96%   |
| Excavator        | 39        | 0.96%   |
| Goldmont         | 38        | 0.94%   |
| IceLake          | 34        | 0.84%   |
| Jaguar           | 31        | 0.76%   |
| K10 Llano        | 28        | 0.69%   |
| Steamroller      | 14        | 0.35%   |
| Alderlake Hybrid | 14        | 0.35%   |
| K8 & K10 hybrid  | 11        | 0.27%   |
| Bulldozer        | 10        | 0.25%   |
| K6               | 6         | 0.15%   |
| Tremont          | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2285      | 50.97%  |
| Nvidia                           | 1131      | 25.23%  |
| AMD                              | 990       | 22.08%  |
| Silicon Integrated Systems [SiS] | 26        | 0.58%   |
| Matrox Electronics Systems       | 22        | 0.49%   |
| VIA Technologies                 | 19        | 0.42%   |
| ASPEED Technology                | 8         | 0.18%   |
| S3 Graphics                      | 1         | 0.02%   |
| Alliance Semiconductor           | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 238       | 4.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 156       | 3.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 125       | 2.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 107       | 2.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 104       | 2.18%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 91        | 1.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 86        | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 86        | 1.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 84        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 81        | 1.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 75        | 1.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 63        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 62        | 1.3%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 61        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 58        | 1.22%   |
| Intel UHD Graphics 620                                                                   | 56        | 1.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 55        | 1.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 54        | 1.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 52        | 1.09%   |
| Intel HD Graphics 620                                                                    | 51        | 1.07%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 49        | 1.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 49        | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 0.96%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 43        | 0.9%    |
| Intel HD Graphics 530                                                                    | 42        | 0.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 42        | 0.88%   |
| Intel HD Graphics 5500                                                                   | 39        | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 39        | 0.82%   |
| AMD Renoir                                                                               | 39        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 35        | 0.73%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 34        | 0.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 0.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 0.67%   |
| Nvidia GT218 [GeForce 210]                                                               | 31        | 0.65%   |
| Intel HD Graphics 500                                                                    | 31        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 29        | 0.61%   |
| Intel HD Graphics 630                                                                    | 28        | 0.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 26        | 0.54%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 25        | 0.52%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 24        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 1861      | 45.72%  |
| 1 x Nvidia                           | 795       | 19.53%  |
| 1 x AMD                              | 791       | 19.43%  |
| Intel + Nvidia                       | 288       | 7.08%   |
| Intel + AMD                          | 90        | 2.21%   |
| 2 x AMD                              | 70        | 1.72%   |
| Other                                | 57        | 1.4%    |
| AMD + Nvidia                         | 30        | 0.74%   |
| 1 x SiS                              | 26        | 0.64%   |
| 1 x VIA                              | 19        | 0.47%   |
| 1 x Matrox                           | 16        | 0.39%   |
| 2 x Nvidia                           | 5         | 0.12%   |
| Nvidia + ASPEED                      | 5         | 0.12%   |
| Nvidia + Matrox                      | 3         | 0.07%   |
| 2 x Intel                            | 2         | 0.05%   |
| 1 x ASPEED                           | 2         | 0.05%   |
| AMD + Matrox                         | 2         | 0.05%   |
| 3 x AMD                              | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia                 | 1         | 0.02%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.02%   |
| 1 x S3 Graphics                      | 1         | 0.02%   |
| Intel + 2 x AMD                      | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia             | 1         | 0.02%   |
| AMD + ASPEED                         | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3269      | 80.14%  |
| Proprietary | 607       | 14.88%  |
| Unknown     | 203       | 4.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2121      | 51.28%  |
| 0.01-0.5   | 805       | 19.46%  |
| 1.01-2.0   | 466       | 11.27%  |
| 0.51-1.0   | 370       | 8.95%   |
| 3.01-4.0   | 202       | 4.88%   |
| 7.01-8.0   | 79        | 1.91%   |
| 5.01-6.0   | 50        | 1.21%   |
| 8.01-16.0  | 21        | 0.51%   |
| 2.01-3.0   | 17        | 0.41%   |
| 4.01-5.0   | 2         | 0.05%   |
| 16.01-24.0 | 2         | 0.05%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 599       | 14.47%  |
| AU Optronics            | 454       | 10.97%  |
| LG Display              | 355       | 8.58%   |
| Chimei Innolux          | 238       | 5.75%   |
| Dell                    | 230       | 5.56%   |
| BOE                     | 228       | 5.51%   |
| Goldstar                | 193       | 4.66%   |
| Hewlett-Packard         | 157       | 3.79%   |
| Acer                    | 149       | 3.6%    |
| AOC                     | 107       | 2.59%   |
| Philips                 | 102       | 2.46%   |
| Lenovo                  | 100       | 2.42%   |
| Chi Mei Optoelectronics | 100       | 2.42%   |
| Ancor Communications    | 86        | 2.08%   |
| BenQ                    | 74        | 1.79%   |
| LG Philips              | 73        | 1.76%   |
| Apple                   | 59        | 1.43%   |
| ViewSonic               | 54        | 1.3%    |
| HannStar                | 50        | 1.21%   |
| Iiyama                  | 43        | 1.04%   |
| Unknown                 | 39        | 0.94%   |
| Sony                    | 39        | 0.94%   |
| LG Electronics          | 36        | 0.87%   |
| Sharp                   | 33        | 0.8%    |
| InfoVision              | 33        | 0.8%    |
| Fujitsu Siemens         | 27        | 0.65%   |
| CPT                     | 24        | 0.58%   |
| NEC Computers           | 23        | 0.56%   |
| Panasonic               | 22        | 0.53%   |
| PANDA                   | 19        | 0.46%   |
| Eizo                    | 18        | 0.43%   |
| Toshiba                 | 17        | 0.41%   |
| ASUSTek Computer        | 16        | 0.39%   |
| Vizio                   | 14        | 0.34%   |
| Medion                  | 14        | 0.34%   |
| Quanta Display          | 11        | 0.27%   |
| RTK                     | 10        | 0.24%   |
| Vestel Elektronik       | 9         | 0.22%   |
| Lenovo Group Limited    | 9         | 0.22%   |
| IBM                     | 8         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 21        | 0.49%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 20        | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.4%    |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 16        | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.26%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 10        | 0.23%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.23%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 10        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.23%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 9         | 0.21%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.21%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.19%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 8         | 0.19%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch     | 8         | 0.19%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 7         | 0.16%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.16%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.16%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 7         | 0.16%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.16%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.16%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 7         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 7         | 0.16%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 7         | 0.16%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 7         | 0.16%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 7         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1358      | 33.57%  |
| 1366x768 (WXGA)    | 890       | 22%     |
| 1280x800 (WXGA)    | 258       | 6.38%   |
| 1280x1024 (SXGA)   | 233       | 5.76%   |
| 1600x900 (HD+)     | 202       | 4.99%   |
| 1440x900 (WXGA+)   | 181       | 4.47%   |
| 1680x1050 (WSXGA+) | 151       | 3.73%   |
| 3840x2160 (4K)     | 147       | 3.63%   |
| 2560x1440 (QHD)    | 109       | 2.69%   |
| 1920x1200 (WUXGA)  | 96        | 2.37%   |
| 1024x600           | 69        | 1.71%   |
| Unknown            | 61        | 1.51%   |
| 1024x768 (XGA)     | 46        | 1.14%   |
| 1360x768           | 42        | 1.04%   |
| 3840x1080          | 24        | 0.59%   |
| 1920x540           | 17        | 0.42%   |
| 1600x1200          | 16        | 0.4%    |
| 3440x1440          | 14        | 0.35%   |
| 2560x1600          | 13        | 0.32%   |
| 2560x1080          | 13        | 0.32%   |
| 1280x720 (HD)      | 10        | 0.25%   |
| 2288x1287          | 8         | 0.2%    |
| 3200x1080          | 6         | 0.15%   |
| 2160x1440          | 5         | 0.12%   |
| 2048x1152          | 5         | 0.12%   |
| 1400x1050          | 5         | 0.12%   |
| 5120x1440          | 4         | 0.1%    |
| 3840x1200          | 4         | 0.1%    |
| 3200x1800 (QHD+)   | 4         | 0.1%    |
| 2880x1800          | 4         | 0.1%    |
| 4480x1440          | 2         | 0.05%   |
| 3840x2400          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3600x1080          | 2         | 0.05%   |
| 3286x1080          | 2         | 0.05%   |
| 3200x900           | 2         | 0.05%   |
| 2960x1050          | 2         | 0.05%   |
| 2048x1536          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 800x600            | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 994       | 24.1%   |
| 14      | 315       | 7.64%   |
| 17      | 308       | 7.47%   |
| Unknown | 297       | 7.2%    |
| 13      | 277       | 6.72%   |
| 23      | 251       | 6.08%   |
| 24      | 223       | 5.41%   |
| 21      | 222       | 5.38%   |
| 19      | 193       | 4.68%   |
| 27      | 173       | 4.19%   |
| 18      | 133       | 3.22%   |
| 20      | 99        | 2.4%    |
| 12      | 83        | 2.01%   |
| 22      | 82        | 1.99%   |
| 10      | 76        | 1.84%   |
| 11      | 74        | 1.79%   |
| 31      | 72        | 1.75%   |
| 84      | 31        | 0.75%   |
| 72      | 22        | 0.53%   |
| 54      | 20        | 0.48%   |
| 16      | 20        | 0.48%   |
| 40      | 18        | 0.44%   |
| 34      | 18        | 0.44%   |
| 32      | 17        | 0.41%   |
| 26      | 17        | 0.41%   |
| 25      | 14        | 0.34%   |
| 52      | 10        | 0.24%   |
| 28      | 8         | 0.19%   |
| 48      | 7         | 0.17%   |
| 37      | 7         | 0.17%   |
| 46      | 5         | 0.12%   |
| 49      | 4         | 0.1%    |
| 8       | 4         | 0.1%    |
| 142     | 3         | 0.07%   |
| 47      | 3         | 0.07%   |
| 29      | 3         | 0.07%   |
| 74      | 2         | 0.05%   |
| 65      | 2         | 0.05%   |
| 60      | 2         | 0.05%   |
| 57      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1537      | 37.73%  |
| 501-600        | 622       | 15.27%  |
| 401-500        | 603       | 14.8%   |
| 201-300        | 375       | 9.2%    |
| 351-400        | 345       | 8.47%   |
| Unknown        | 297       | 7.29%   |
| 601-700        | 107       | 2.63%   |
| 1501-2000      | 56        | 1.37%   |
| 1001-1500      | 55        | 1.35%   |
| 701-800        | 37        | 0.91%   |
| 801-900        | 29        | 0.71%   |
| 101-200        | 5         | 0.12%   |
| More than 2000 | 3         | 0.07%   |
| 901-1000       | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2544      | 66.23%  |
| 16/10   | 657       | 17.1%   |
| Unknown | 270       | 7.03%   |
| 5/4     | 216       | 5.62%   |
| 4/3     | 81        | 2.11%   |
| 3/2     | 26        | 0.68%   |
| 21/9    | 23        | 0.6%    |
| 6/5     | 11        | 0.29%   |
| 1.00    | 5         | 0.13%   |
| 32/9    | 4         | 0.1%    |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 992       | 24.21%  |
| 201-250        | 628       | 15.32%  |
| 81-90          | 475       | 11.59%  |
| 151-200        | 381       | 9.3%    |
| Unknown        | 297       | 7.25%   |
| 141-150        | 214       | 5.22%   |
| 301-350        | 182       | 4.44%   |
| 121-130        | 146       | 3.56%   |
| 351-500        | 115       | 2.81%   |
| More than 1000 | 103       | 2.51%   |
| 71-80          | 101       | 2.46%   |
| 251-300        | 98        | 2.39%   |
| 61-70          | 77        | 1.88%   |
| 51-60          | 75        | 1.83%   |
| 41-50          | 75        | 1.83%   |
| 131-140        | 52        | 1.27%   |
| 501-1000       | 44        | 1.07%   |
| 91-100         | 24        | 0.59%   |
| 111-120        | 14        | 0.34%   |
| 1-40           | 5         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1549      | 38.97%  |
| 101-120       | 1142      | 28.73%  |
| 121-160       | 760       | 19.12%  |
| Unknown       | 297       | 7.47%   |
| 161-240       | 105       | 2.64%   |
| 1-50          | 92        | 2.31%   |
| More than 240 | 30        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3407      | 82.67%  |
| 2     | 490       | 11.89%  |
| 0     | 184       | 4.46%   |
| 3     | 36        | 0.87%   |
| 4     | 4         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2094      | 33.79%  |
| Intel                             | 1660      | 26.78%  |
| Qualcomm Atheros                  | 782       | 12.62%  |
| Broadcom                          | 443       | 7.15%   |
| Marvell Technology Group          | 148       | 2.39%   |
| Broadcom Limited                  | 119       | 1.92%   |
| Nvidia                            | 117       | 1.89%   |
| Ralink Technology                 | 92        | 1.48%   |
| Ralink                            | 87        | 1.4%    |
| TP-Link                           | 72        | 1.16%   |
| VIA Technologies                  | 42        | 0.68%   |
| Qualcomm Atheros Communications   | 37        | 0.6%    |
| MediaTek                          | 37        | 0.6%    |
| Silicon Integrated Systems [SiS]  | 33        | 0.53%   |
| Samsung Electronics               | 32        | 0.52%   |
| Huawei Technologies               | 29        | 0.47%   |
| D-Link System                     | 26        | 0.42%   |
| JMicron Technology                | 23        | 0.37%   |
| NetGear                           | 22        | 0.35%   |
| Sierra Wireless                   | 18        | 0.29%   |
| D-Link                            | 17        | 0.27%   |
| ASIX Electronics                  | 16        | 0.26%   |
| Ericsson Business Mobile Networks | 15        | 0.24%   |
| Attansic Technology               | 15        | 0.24%   |
| Dell                              | 12        | 0.19%   |
| ASUSTek Computer                  | 12        | 0.19%   |
| Xiaomi                            | 11        | 0.18%   |
| Edimax Technology                 | 10        | 0.16%   |
| DisplayLink                       | 10        | 0.16%   |
| Aquantia                          | 10        | 0.16%   |
| Qualcomm                          | 9         | 0.15%   |
| Lenovo                            | 9         | 0.15%   |
| Belkin Components                 | 9         | 0.15%   |
| AMD                               | 8         | 0.13%   |
| Fibocom                           | 7         | 0.11%   |
| Microsoft                         | 6         | 0.1%    |
| Linksys                           | 6         | 0.1%    |
| ZyDAS                             | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.08%   |
| ULi Electronics                   | 5         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1329      | 18.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 335       | 4.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 179       | 2.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 120       | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 98        | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 96        | 1.33%   |
| Intel Wi-Fi 6 AX200                                                     | 95        | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 93        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 92        | 1.28%   |
| Intel Wireless 7260                                                     | 76        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 75        | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 66        | 0.92%   |
| Intel Wireless 7265                                                     | 64        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 0.88%   |
| Intel Ethernet Connection I217-LM                                       | 62        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 61        | 0.85%   |
| Intel Wireless 8265 / 8275                                              | 59        | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 57        | 0.79%   |
| Nvidia MCP61 Ethernet                                                   | 55        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 52        | 0.72%   |
| Intel Wireless 3165                                                     | 52        | 0.72%   |
| Intel Wireless 8260                                                     | 50        | 0.7%    |
| Intel I211 Gigabit Network Connection                                   | 49        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 44        | 0.61%   |
| Intel Wi-Fi 6 AX201                                                     | 44        | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 43        | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 41        | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                       | 39        | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                    | 39        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                 | 39        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 38        | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 37        | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 37        | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                         | 35        | 0.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 34        | 0.47%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 34        | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 0.46%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 0.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1143      | 36.65%  |
| Qualcomm Atheros                      | 637       | 20.42%  |
| Realtek Semiconductor                 | 531       | 17.02%  |
| Broadcom                              | 265       | 8.5%    |
| Ralink Technology                     | 92        | 2.95%   |
| Ralink                                | 87        | 2.79%   |
| TP-Link                               | 67        | 2.15%   |
| Broadcom Limited                      | 57        | 1.83%   |
| Qualcomm Atheros Communications       | 37        | 1.19%   |
| MediaTek                              | 27        | 0.87%   |
| NetGear                               | 22        | 0.71%   |
| Sierra Wireless                       | 18        | 0.58%   |
| D-Link System                         | 18        | 0.58%   |
| D-Link                                | 16        | 0.51%   |
| ASUSTek Computer                      | 11        | 0.35%   |
| Edimax Technology                     | 10        | 0.32%   |
| Belkin Components                     | 9         | 0.29%   |
| Fibocom                               | 7         | 0.22%   |
| Dell                                  | 7         | 0.22%   |
| Qualcomm                              | 6         | 0.19%   |
| Microsoft                             | 6         | 0.19%   |
| Linksys                               | 6         | 0.19%   |
| ZyDAS                                 | 5         | 0.16%   |
| Sitecom Europe                        | 5         | 0.16%   |
| Marvell Technology Group              | 4         | 0.13%   |
| IMC Networks                          | 4         | 0.13%   |
| AVM                                   | 4         | 0.13%   |
| TRENDnet                              | 3         | 0.1%    |
| Hewlett-Packard                       | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Toshiba                               | 1         | 0.03%   |
| Texas Instruments                     | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| AboCom Systems                        | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 120       | 3.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 98        | 3.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 96        | 3.04%   |
| Intel Wi-Fi 6 AX200                                                     | 95        | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 92        | 2.92%   |
| Intel Wireless 7260                                                     | 76        | 2.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 75        | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 66        | 2.09%   |
| Intel Wireless 7265                                                     | 64        | 2.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 61        | 1.93%   |
| Intel Wireless 8265 / 8275                                              | 59        | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 57        | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 52        | 1.65%   |
| Intel Wireless 3165                                                     | 52        | 1.65%   |
| Intel Wireless 8260                                                     | 50        | 1.59%   |
| Intel Wi-Fi 6 AX201                                                     | 44        | 1.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 43        | 1.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 41        | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 37        | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 37        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 1.11%   |
| Ralink MT7601U Wireless Adapter                                         | 35        | 1.11%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 34        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 0.98%   |
| Intel Centrino Advanced-N 6200                                          | 30        | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 29        | 0.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 29        | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 28        | 0.89%   |
| Intel Wireless 3160                                                     | 28        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 28        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 0.89%   |
| Intel Wireless-AC 9260                                                  | 26        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                          | 26        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 26        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 24        | 0.76%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 24        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1856      | 48.07%  |
| Intel                            | 944       | 24.45%  |
| Qualcomm Atheros                 | 239       | 6.19%   |
| Broadcom                         | 222       | 5.75%   |
| Marvell Technology Group         | 144       | 3.73%   |
| Nvidia                           | 116       | 3%      |
| Broadcom Limited                 | 63        | 1.63%   |
| VIA Technologies                 | 42        | 1.09%   |
| Silicon Integrated Systems [SiS] | 31        | 0.8%    |
| JMicron Technology               | 23        | 0.6%    |
| Samsung Electronics              | 21        | 0.54%   |
| Huawei Technologies              | 18        | 0.47%   |
| ASIX Electronics                 | 16        | 0.41%   |
| Attansic Technology              | 15        | 0.39%   |
| MediaTek                         | 11        | 0.28%   |
| Xiaomi                           | 10        | 0.26%   |
| DisplayLink                      | 10        | 0.26%   |
| Aquantia                         | 10        | 0.26%   |
| Lenovo                           | 9         | 0.23%   |
| D-Link System                    | 8         | 0.21%   |
| TP-Link                          | 5         | 0.13%   |
| HTC (High Tech Computer)         | 5         | 0.13%   |
| LG Electronics                   | 4         | 0.1%    |
| Qualcomm                         | 3         | 0.08%   |
| IBM                              | 3         | 0.08%   |
| Apple                            | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.05%   |
| Spreadtrum Communications        | 2         | 0.05%   |
| OPPO Electronics                 | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| Motorola PCS                     | 2         | 0.05%   |
| Microchip Technology             | 2         | 0.05%   |
| Insyde Software                  | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| Accton Technology                | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| ULi Electronics                  | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Mellanox Technologies            | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1329      | 33.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 335       | 8.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 179       | 4.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 93        | 2.37%   |
| Intel Ethernet Connection I217-LM                                 | 62        | 1.58%   |
| Nvidia MCP61 Ethernet                                             | 55        | 1.4%    |
| Intel I211 Gigabit Network Connection                             | 49        | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 44        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 39        | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 39        | 1%      |
| Intel 82579V Gigabit Network Connection                           | 39        | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 0.97%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 34        | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 30        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 29        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28        | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 28        | 0.71%   |
| Intel 82567LM Gigabit Network Connection                          | 28        | 0.71%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 27        | 0.69%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 27        | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 27        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 21        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 20        | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 19        | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.48%   |
| Intel 82566MM Gigabit Network Connection                          | 19        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 19        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 18        | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 18        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 17        | 0.43%   |
| Intel PRO/100 VE Network Connection                               | 17        | 0.43%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.43%   |
| Intel 82573L Gigabit Ethernet Controller                          | 17        | 0.43%   |
| Nvidia MCP79 Ethernet                                             | 16        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3654      | 54.58%  |
| WiFi     | 2920      | 43.61%  |
| Modem    | 114       | 1.7%    |
| Unknown  | 7         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2317      | 55.5%   |
| Ethernet | 1856      | 44.46%  |
| Modem    | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2256      | 55.53%  |
| 1     | 1600      | 39.38%  |
| 0     | 120       | 2.95%   |
| 3     | 61        | 1.5%    |
| 4     | 19        | 0.47%   |
| 5     | 4         | 0.1%    |
| 10    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3460      | 84.23%  |
| Yes  | 648       | 15.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 706       | 38.56%  |
| Broadcom                        | 176       | 9.61%   |
| Realtek Semiconductor           | 167       | 9.12%   |
| Qualcomm Atheros Communications | 160       | 8.74%   |
| Cambridge Silicon Radio         | 121       | 6.61%   |
| Apple                           | 65        | 3.55%   |
| Lite-On Technology              | 62        | 3.39%   |
| IMC Networks                    | 61        | 3.33%   |
| Foxconn / Hon Hai               | 60        | 3.28%   |
| Dell                            | 56        | 3.06%   |
| Hewlett-Packard                 | 51        | 2.79%   |
| ASUSTek Computer                | 30        | 1.64%   |
| Toshiba                         | 20        | 1.09%   |
| Ralink                          | 17        | 0.93%   |
| Alps Electric                   | 14        | 0.76%   |
| MediaTek                        | 8         | 0.44%   |
| Integrated System Solution      | 8         | 0.44%   |
| Realtek                         | 7         | 0.38%   |
| Ralink Technology               | 6         | 0.33%   |
| Foxconn International           | 6         | 0.33%   |
| TP-Link                         | 5         | 0.27%   |
| Chicony Electronics             | 4         | 0.22%   |
| Taiyo Yuden                     | 3         | 0.16%   |
| Edimax Technology               | 3         | 0.16%   |
| Qcom                            | 2         | 0.11%   |
| Fujitsu                         | 2         | 0.11%   |
| USI                             | 1         | 0.05%   |
| Syntek                          | 1         | 0.05%   |
| Sitecom Europe                  | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Marvell Semiconductor           | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| ISSC                            | 1         | 0.05%   |
| Conwise Technology              | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |
| Actions                         | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 313       | 17.08%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 121       | 6.6%    |
| Realtek Bluetooth Radio                                                             | 100       | 5.46%   |
| Intel AX201 Bluetooth                                                               | 97        | 5.29%   |
| Intel AX200 Bluetooth                                                               | 95        | 5.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 75        | 4.09%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 64        | 3.49%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 45        | 2.45%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 34        | 1.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 33        | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 32        | 1.75%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 31        | 1.69%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 27        | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 24        | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 23        | 1.25%   |
| Apple Bluetooth HCI                                                                 | 21        | 1.15%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 20        | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 20        | 1.09%   |
| Lite-On Bluetooth Device                                                            | 19        | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 19        | 1.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 18        | 0.98%   |
| Intel AX210 Bluetooth                                                               | 18        | 0.98%   |
| Apple Bluetooth Host Controller                                                     | 18        | 0.98%   |
| Ralink RT3290 Bluetooth                                                             | 17        | 0.93%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 17        | 0.93%   |
| IMC Networks Bluetooth Device                                                       | 17        | 0.93%   |
| Broadcom BCM2045 Bluetooth                                                          | 17        | 0.93%   |
| IMC Networks Bluetooth Radio                                                        | 16        | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 0.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 15        | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 14        | 0.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 13        | 0.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 13        | 0.71%   |
| Dell DW375 Bluetooth Module                                                         | 13        | 0.71%   |
| Realtek RTL8723B Bluetooth                                                          | 12        | 0.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 12        | 0.65%   |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.6%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.6%    |
| Apple Bluetooth USB Host Controller                                                 | 11        | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2911      | 55.62%  |
| AMD                              | 946       | 18.07%  |
| Nvidia                           | 818       | 15.63%  |
| C-Media Electronics              | 77        | 1.47%   |
| Creative Labs                    | 57        | 1.09%   |
| VIA Technologies                 | 50        | 0.96%   |
| Silicon Integrated Systems [SiS] | 40        | 0.76%   |
| Texas Instruments                | 28        | 0.53%   |
| Logitech                         | 28        | 0.53%   |
| GN Netcom                        | 18        | 0.34%   |
| Focusrite-Novation               | 13        | 0.25%   |
| Creative Technology              | 13        | 0.25%   |
| M-Audio                          | 12        | 0.23%   |
| Plantronics                      | 11        | 0.21%   |
| JMTek                            | 11        | 0.21%   |
| Generalplus Technology           | 11        | 0.21%   |
| Yamaha                           | 10        | 0.19%   |
| Lenovo                           | 9         | 0.17%   |
| Realtek Semiconductor            | 8         | 0.15%   |
| BEHRINGER International          | 8         | 0.15%   |
| ULi Electronics                  | 6         | 0.11%   |
| ASUSTek Computer                 | 6         | 0.11%   |
| Sennheiser Communications        | 4         | 0.08%   |
| SAVITECH                         | 4         | 0.08%   |
| Ensoniq                          | 4         | 0.08%   |
| DigiTech                         | 4         | 0.08%   |
| Corsair                          | 4         | 0.08%   |
| AKAI Professional M.I.           | 4         | 0.08%   |
| XMOS                             | 3         | 0.06%   |
| Xilinx                           | 3         | 0.06%   |
| Tenx Technology                  | 3         | 0.06%   |
| TEAC                             | 3         | 0.06%   |
| Roland                           | 3         | 0.06%   |
| PreSonus Audio Electronics       | 3         | 0.06%   |
| Micro Star International         | 3         | 0.06%   |
| Kingston Technology              | 3         | 0.06%   |
| Elite Silicon                    | 3         | 0.06%   |
| EGO SYStems                      | 3         | 0.06%   |
| DSEA A/S                         | 3         | 0.06%   |
| Digidesign                       | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 339       | 5.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 297       | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 280       | 4.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 218       | 3.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 191       | 3.17%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 187       | 3.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 183       | 3.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 178       | 2.95%   |
| AMD FCH Azalia Controller                                                                         | 167       | 2.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 165       | 2.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 156       | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 131       | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 84        | 1.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 82        | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 81        | 1.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 81        | 1.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 80        | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 78        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 77        | 1.28%   |
| Intel 8 Series HD Audio Controller                                                                | 77        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 73        | 1.21%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 72        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 71        | 1.18%   |
| Nvidia High Definition Audio Controller                                                           | 70        | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 67        | 1.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 59        | 0.98%   |
| Nvidia MCP61 High Definition Audio                                                                | 58        | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 54        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 51        | 0.85%   |
| Intel Broadwell-U Audio Controller                                                                | 51        | 0.85%   |
| Intel 200 Series PCH HD Audio                                                                     | 51        | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 51        | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 50        | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 50        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 45        | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 42        | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 41        | 0.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 39        | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 39        | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 38        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 443       | 21.15%  |
| SK hynix                     | 351       | 16.75%  |
| Unknown                      | 331       | 15.8%   |
| Kingston                     | 241       | 11.5%   |
| Micron Technology            | 161       | 7.68%   |
| Crucial                      | 125       | 5.97%   |
| Corsair                      | 78        | 3.72%   |
| G.Skill                      | 57        | 2.72%   |
| Elpida                       | 46        | 2.2%    |
| Ramaxel Technology           | 38        | 1.81%   |
| Nanya Technology             | 32        | 1.53%   |
| Unknown (ABCD)               | 28        | 1.34%   |
| A-DATA Technology            | 27        | 1.29%   |
| Smart                        | 14        | 0.67%   |
| Transcend                    | 13        | 0.62%   |
| Team                         | 10        | 0.48%   |
| GOODRAM                      | 9         | 0.43%   |
| Unknown                      | 6         | 0.29%   |
| Qimonda                      | 5         | 0.24%   |
| Avant                        | 5         | 0.24%   |
| Apacer                       | 5         | 0.24%   |
| Patriot                      | 4         | 0.19%   |
| Unifosa                      | 3         | 0.14%   |
| Timetec                      | 3         | 0.14%   |
| GeIL                         | 3         | 0.14%   |
| fef5                         | 3         | 0.14%   |
| 48spaces                     | 3         | 0.14%   |
| Teikon                       | 2         | 0.1%    |
| Super Talent                 | 2         | 0.1%    |
| PNY                          | 2         | 0.1%    |
| Neo Forza                    | 2         | 0.1%    |
| High Bridge                  | 2         | 0.1%    |
| CSX                          | 2         | 0.1%    |
| ASint Technology             | 2         | 0.1%    |
| Walton Chaintech             | 1         | 0.05%   |
| V-GeN                        | 1         | 0.05%   |
| V-Color                      | 1         | 0.05%   |
| Unknown (AB)                 | 1         | 0.05%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.05%   |
| Unknown (0x7FA8000000000000) | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 22        | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.67%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 15        | 0.67%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 0.58%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 12        | 0.53%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 12        | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.53%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 11        | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 10        | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 10        | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 9         | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.4%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 9         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 8         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 8         | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 8         | 0.36%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 8         | 0.36%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 7         | 0.31%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 7         | 0.31%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.31%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.31%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.31%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 7         | 0.31%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.27%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 6         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 718       | 39.19%  |
| DDR4    | 633       | 34.55%  |
| DDR2    | 185       | 10.1%   |
| SDRAM   | 86        | 4.69%   |
| LPDDR4  | 67        | 3.66%   |
| Unknown | 62        | 3.38%   |
| LPDDR3  | 36        | 1.97%   |
| DDR     | 24        | 1.31%   |
| DRAM    | 8         | 0.44%   |
| DDR5    | 7         | 0.38%   |
| LPDDR5  | 5         | 0.27%   |
| EEPROM  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1049      | 58.38%  |
| DIMM         | 653       | 36.34%  |
| Row Of Chips | 70        | 3.9%    |
| Chip         | 11        | 0.61%   |
| Unknown      | 10        | 0.56%   |
| FB-DIMM      | 4         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 596       | 30.16%  |
| 8192    | 555       | 28.09%  |
| 2048    | 410       | 20.75%  |
| 16384   | 232       | 11.74%  |
| 1024    | 127       | 6.43%   |
| 32768   | 35        | 1.77%   |
| 512     | 15        | 0.76%   |
| 1536    | 2         | 0.1%    |
| 65536   | 1         | 0.05%   |
| 256     | 1         | 0.05%   |
| 1       | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 446       | 22.94%  |
| 2667    | 251       | 12.91%  |
| 3200    | 179       | 9.21%   |
| 1333    | 150       | 7.72%   |
| 2400    | 131       | 6.74%   |
| 667     | 98        | 5.04%   |
| 800     | 79        | 4.06%   |
| Unknown | 78        | 4.01%   |
| 2133    | 71        | 3.65%   |
| 1334    | 67        | 3.45%   |
| 3600    | 32        | 1.65%   |
| 1066    | 32        | 1.65%   |
| 1067    | 31        | 1.59%   |
| 1867    | 30        | 1.54%   |
| 3266    | 20        | 1.03%   |
| 1866    | 20        | 1.03%   |
| 533     | 20        | 1.03%   |
| 4199    | 19        | 0.98%   |
| 4267    | 15        | 0.77%   |
| 2048    | 15        | 0.77%   |
| 1800    | 15        | 0.77%   |
| 3000    | 13        | 0.67%   |
| 2666    | 13        | 0.67%   |
| 975     | 10        | 0.51%   |
| 400     | 8         | 0.41%   |
| 4800    | 7         | 0.36%   |
| 3800    | 5         | 0.26%   |
| 3733    | 5         | 0.26%   |
| 2733    | 5         | 0.26%   |
| 2000    | 5         | 0.26%   |
| 333     | 5         | 0.26%   |
| 49926   | 4         | 0.21%   |
| 6400    | 4         | 0.21%   |
| 4266    | 4         | 0.21%   |
| 3400    | 4         | 0.21%   |
| 2800    | 4         | 0.21%   |
| 2200    | 4         | 0.21%   |
| 3466    | 3         | 0.15%   |
| 2448    | 3         | 0.15%   |
| 1639    | 3         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 55        | 40.74%  |
| Brother Industries    | 27        | 20%     |
| Canon                 | 24        | 17.78%  |
| Samsung Electronics   | 10        | 7.41%   |
| Seiko Epson           | 5         | 3.7%    |
| Zebra                 | 4         | 2.96%   |
| QinHeng Electronics   | 2         | 1.48%   |
| Prolific Technology   | 2         | 1.48%   |
| STMicroelectronics    | 1         | 0.74%   |
| Pantum                | 1         | 0.74%   |
| Minolta               | 1         | 0.74%   |
| Lexmark International | 1         | 0.74%   |
| Kyocera               | 1         | 0.74%   |
| Dymo-CoStar           | 1         | 0.74%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet P1005                                                     | 4         | 2.94%   |
| HP LaserJet 400 M401a                                                 | 4         | 2.94%   |
| Zebra ZP 450 Printer                                                  | 3         | 2.21%   |
| HP ENVY 4520 series                                                   | 3         | 2.21%   |
| HP DeskJet 3700 series                                                | 3         | 2.21%   |
| Brother HL-5370DW series                                              | 3         | 2.21%   |
| Seiko Epson L220 Series                                               | 2         | 1.47%   |
| QinHeng CH340S                                                        | 2         | 1.47%   |
| Prolific PL2305 Parallel Port                                         | 2         | 1.47%   |
| HP OfficeJet Pro 7730 series                                          | 2         | 1.47%   |
| HP LaserJet P1006                                                     | 2         | 1.47%   |
| HP LaserJet 1320                                                      | 2         | 1.47%   |
| HP LaserJet 1020                                                      | 2         | 1.47%   |
| HP LaserJet 1018                                                      | 2         | 1.47%   |
| HP LaserJet 1015                                                      | 2         | 1.47%   |
| HP Deskjet 3050A                                                      | 2         | 1.47%   |
| Canon TS3100 series                                                   | 2         | 1.47%   |
| Canon PIXMA MX530 Series                                              | 2         | 1.47%   |
| Canon LBP6000                                                         | 2         | 1.47%   |
| Brother HL-L2320D series                                              | 2         | 1.47%   |
| Brother HL-5340 series                                                | 2         | 1.47%   |
| Brother HL-2270DW Laser Printer                                       | 2         | 1.47%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.74%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.74%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.74%   |
| Seiko Epson L396 Series                                               | 1         | 0.74%   |
| Seiko Epson ET-2720 Series                                            | 1         | 0.74%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 0.74%   |
| Samsung SF-760 Series                                                 | 1         | 0.74%   |
| Samsung SCX-4200 series                                               | 1         | 0.74%   |
| Samsung SCX-4100 Scanner                                              | 1         | 0.74%   |
| Samsung SCX-3400 Series                                               | 1         | 0.74%   |
| Samsung ML-2525W Series                                               | 1         | 0.74%   |
| Samsung ML-1740 Printer                                               | 1         | 0.74%   |
| Samsung M2070 Series                                                  | 1         | 0.74%   |
| Samsung M2020 Series                                                  | 1         | 0.74%   |
| Samsung C48x Series                                                   | 1         | 0.74%   |
| Pantum P2000                                                          | 1         | 0.74%   |
| Minolta PagePro 1300W                                                 | 1         | 0.74%   |
| Lexmark International E360d                                           | 1         | 0.74%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 27        | 71.05%  |
| Hewlett-Packard | 6         | 15.79%  |
| Seiko Epson     | 5         | 13.16%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                     | 5         | 13.16%  |
| Canon CanoScan LiDE 100                                     | 4         | 10.53%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3         | 7.89%   |
| Canon CanoScan LIDE 25                                      | 3         | 7.89%   |
| Canon CanoScan N650U/N656U                                  | 2         | 5.26%   |
| Canon CanoScan LiDE 220                                     | 2         | 5.26%   |
| Canon CanoScan LiDE 210                                     | 2         | 5.26%   |
| Canon CanoScan LiDE 120                                     | 2         | 5.26%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 2.63%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 2.63%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1         | 2.63%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 2.63%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 2.63%   |
| HP ScanJet 82x0C                                            | 1         | 2.63%   |
| HP ScanJet 7400c                                            | 1         | 2.63%   |
| HP ScanJet 5590                                             | 1         | 2.63%   |
| HP ScanJet 3570c                                            | 1         | 2.63%   |
| HP Scanjet 200                                              | 1         | 2.63%   |
| HP PSC 1200                                                 | 1         | 2.63%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 2.63%   |
| Canon CanoScan LiDE 90                                      | 1         | 2.63%   |
| Canon CanoScan LiDE 200                                     | 1         | 2.63%   |
| Canon CanoScan 4400F                                        | 1         | 2.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 523       | 24.63%  |
| Microdia                               | 171       | 8.05%   |
| Realtek Semiconductor                  | 136       | 6.41%   |
| IMC Networks                           | 132       | 6.22%   |
| Suyin                                  | 121       | 5.7%    |
| Logitech                               | 110       | 5.18%   |
| Sunplus Innovation Technology          | 102       | 4.8%    |
| Bison Electronics                      | 77        | 3.63%   |
| Quanta                                 | 74        | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 69        | 3.25%   |
| Acer                                   | 58        | 2.73%   |
| Apple                                  | 53        | 2.5%    |
| Silicon Motion                         | 47        | 2.21%   |
| Alcor Micro                            | 47        | 2.21%   |
| Syntek                                 | 44        | 2.07%   |
| Ricoh                                  | 41        | 1.93%   |
| Lite-On Technology                     | 35        | 1.65%   |
| Samsung Electronics                    | 25        | 1.18%   |
| Z-Star Microelectronics                | 24        | 1.13%   |
| Microsoft                              | 22        | 1.04%   |
| Lenovo                                 | 17        | 0.8%    |
| Luxvisions Innotech Limited            | 16        | 0.75%   |
| ALi                                    | 16        | 0.75%   |
| Importek                               | 10        | 0.47%   |
| Primax Electronics                     | 9         | 0.42%   |
| Generalplus Technology                 | 8         | 0.38%   |
| GEMBIRD                                | 8         | 0.38%   |
| USB Camera                             | 7         | 0.33%   |
| OmniVision Technologies                | 7         | 0.33%   |
| MacroSilicon                           | 7         | 0.33%   |
| KYE Systems (Mouse Systems)            | 6         | 0.28%   |
| Jieli Technology                       | 6         | 0.28%   |
| DigiTech                               | 6         | 0.28%   |
| Cubeternet                             | 6         | 0.28%   |
| ARC International                      | 6         | 0.28%   |
| Sonix Technology                       | 5         | 0.24%   |
| Creative Technology                    | 5         | 0.24%   |
| Sunplus Technology                     | 4         | 0.19%   |
| USB Camera CS                          | 3         | 0.14%   |
| Trust                                  | 3         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 83        | 3.89%   |
| Microdia Integrated_Webcam_HD                    | 35        | 1.64%   |
| Realtek Integrated_Webcam_HD                     | 34        | 1.6%    |
| Chicony HD WebCam                                | 33        | 1.55%   |
| Chicony USB 2.0 Camera                           | 28        | 1.31%   |
| Logitech Webcam C270                             | 26        | 1.22%   |
| IMC Networks USB2.0 HD UVC WebCam                | 26        | 1.22%   |
| Sunplus Integrated_Webcam_HD                     | 24        | 1.13%   |
| Samsung Galaxy A5 (MTP)                          | 24        | 1.13%   |
| IMC Networks Integrated Camera                   | 22        | 1.03%   |
| Alcor Micro USB 2.0 Camera                       | 22        | 1.03%   |
| Microdia Sonix USB 2.0 Camera                    | 20        | 0.94%   |
| Chicony TOSHIBA Web Camera - HD                  | 20        | 0.94%   |
| Logitech HD Pro Webcam C920                      | 19        | 0.89%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 18        | 0.84%   |
| Chicony Lenovo EasyCamera                        | 18        | 0.84%   |
| Chicony HP Truevision HD                         | 18        | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 18        | 0.84%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 18        | 0.84%   |
| Apple Built-in iSight                            | 18        | 0.84%   |
| Suyin HP TrueVision HD                           | 17        | 0.8%    |
| Microdia Integrated Webcam                       | 16        | 0.75%   |
| Bison Integrated Camera                          | 16        | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.7%    |
| Syntek Integrated Camera                         | 14        | 0.66%   |
| Suyin Acer CrystalEye Webcam                     | 14        | 0.66%   |
| Lite-On Integrated Camera                        | 14        | 0.66%   |
| Sunplus HD WebCam                                | 13        | 0.61%   |
| Quanta HP Webcam                                 | 13        | 0.61%   |
| IMC Networks UVC VGA Webcam                      | 13        | 0.61%   |
| Bison SunplusIT Integrated Camera                | 13        | 0.61%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.56%   |
| Realtek USB Camera                               | 12        | 0.56%   |
| Chicony HP TrueVision HD Camera                  | 12        | 0.56%   |
| Acer Lenovo EasyCamera                           | 12        | 0.56%   |
| Quanta HP TrueVision HD Camera                   | 11        | 0.52%   |
| Logitech C922 Pro Stream Webcam                  | 11        | 0.52%   |
| Lite-On HP HD Camera                             | 11        | 0.52%   |
| Chicony USB2.0 Camera                            | 11        | 0.52%   |
| Chicony HP HD Camera                             | 11        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 128       | 35.85%  |
| Synaptics                          | 67        | 18.77%  |
| AuthenTec                          | 55        | 15.41%  |
| Upek                               | 32        | 8.96%   |
| Shenzhen Goodix Technology         | 25        | 7%      |
| STMicroelectronics                 | 20        | 5.6%    |
| LighTuning Technology              | 14        | 3.92%   |
| Elan Microelectronics              | 9         | 2.52%   |
| Samsung Electronics                | 3         | 0.84%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.28%   |
| Gingytech                          | 1         | 0.28%   |
| Focal-systems.Corp                 | 1         | 0.28%   |
| DigitalPersona                     | 1         | 0.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 8.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 7.84%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 7.84%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 23        | 6.44%   |
| STMicroelectronics Fingerprint Reader                                      | 20        | 5.6%    |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 4.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 4.2%    |
| AuthenTec AES2810                                                          | 15        | 4.2%    |
| Validity Sensors Fingerprint scanner                                       | 13        | 3.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.08%   |
| Validity Sensors VFS491                                                    | 11        | 3.08%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 2.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 2.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.24%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.24%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.24%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 2.24%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.24%   |
| AuthenTec AES1600                                                          | 7         | 1.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.68%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.4%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.12%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.12%   |
| Synaptics UWP WBDI                                                         | 4         | 1.12%   |
| Synaptics  WBDI                                                            | 4         | 1.12%   |
| LighTuning Fingerprint Reader                                              | 4         | 1.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.12%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.84%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.84%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.84%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.56%   |
| Synaptics WBDI Device                                                      | 2         | 0.56%   |
| Synaptics WBDI                                                             | 2         | 0.56%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.56%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.56%   |
| Unknown                                                                    | 2         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 71        | 34.98%  |
| Alcor Micro                       | 51        | 25.12%  |
| O2 Micro                          | 29        | 14.29%  |
| Upek                              | 17        | 8.37%   |
| Lenovo                            | 17        | 8.37%   |
| OmniKey                           | 3         | 1.48%   |
| Gemalto (was Gemplus)             | 3         | 1.48%   |
| Reiner SCT Kartensysteme          | 2         | 0.99%   |
| Yubico.com                        | 1         | 0.49%   |
| VASCO Data Security International | 1         | 0.49%   |
| In Focus Systems                  | 1         | 0.49%   |
| Fujitsu Siemens Computers         | 1         | 0.49%   |
| Clay Logic                        | 1         | 0.49%   |
| Chicony Electronics               | 1         | 0.49%   |
| Cherry                            | 1         | 0.49%   |
| C3PO                              | 1         | 0.49%   |
| Aktiv                             | 1         | 0.49%   |
| Advanced Card Systems             | 1         | 0.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 51        | 25.12%  |
| Broadcom BCM5880 Secure Applications Processor                               | 33        | 16.26%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 11.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 8.37%   |
| Broadcom 5880                                                                | 17        | 8.37%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 7.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.42%   |
| Broadcom 58200                                                               | 9         | 4.43%   |
| O2 Micro Oz776 SmartCard Reader                                              | 6         | 2.96%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.99%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.99%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.49%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.49%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.49%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 0.49%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.49%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.49%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.49%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.49%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.49%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.49%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.49%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.49%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.49%   |
| Aktiv Rutoken lite                                                           | 1         | 0.49%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3001      | 72.98%  |
| 1     | 880       | 21.4%   |
| 2     | 184       | 4.47%   |
| 3     | 30        | 0.73%   |
| 4     | 10        | 0.24%   |
| 5     | 4         | 0.1%    |
| 10    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 355       | 26.61%  |
| Graphics card            | 287       | 21.51%  |
| Chipcard                 | 192       | 14.39%  |
| Net/wireless             | 144       | 10.79%  |
| Communication controller | 58        | 4.35%   |
| Modem                    | 47        | 3.52%   |
| Camera                   | 46        | 3.45%   |
| Multimedia controller    | 36        | 2.7%    |
| Unassigned class         | 28        | 2.1%    |
| Bluetooth                | 28        | 2.1%    |
| Storage                  | 25        | 1.87%   |
| Sound                    | 23        | 1.72%   |
| Card reader              | 22        | 1.65%   |
| Flash memory             | 16        | 1.2%    |
| Network                  | 9         | 0.67%   |
| Net/ethernet             | 8         | 0.6%    |
| Dvb card                 | 4         | 0.3%    |
| Storage/raid             | 2         | 0.15%   |
| Storage/ide              | 2         | 0.15%   |
| Video                    | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

