Lubuntu 20.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_20.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_20.04/Notebook/README.md).

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

Total: 604

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| HP            | 21B4 A01                    | Desktop     | [16b576ebea](https://linux-hardware.org/?probe=16b576ebea) | Jun 15, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| Sony          | SVF1521C6EW                 | Notebook    | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| ASUSTek       | F1A55-M LK R2.0             | Desktop     | [234e0d0738](https://linux-hardware.org/?probe=234e0d0738) | Apr 23, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [1eef9edf97](https://linux-hardware.org/?probe=1eef9edf97) | Mar 04, 2023 |
| DEXP          | Aquilon C15                 | Notebook    | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [9c3a1f5cd5](https://linux-hardware.org/?probe=9c3a1f5cd5) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [4b440b2084](https://linux-hardware.org/?probe=4b440b2084) | Feb 22, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2420c1fb57](https://linux-hardware.org/?probe=2420c1fb57) | Feb 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [d159971f77](https://linux-hardware.org/?probe=d159971f77) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [72b29b5f80](https://linux-hardware.org/?probe=72b29b5f80) | Feb 16, 2023 |
| Toshiba       | Satellite C55D-A            | Notebook    | [38083cc2a4](https://linux-hardware.org/?probe=38083cc2a4) | Feb 05, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [be66e9073f](https://linux-hardware.org/?probe=be66e9073f) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [3a8aced1b7](https://linux-hardware.org/?probe=3a8aced1b7) | Jan 25, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| Dell          | 05KX61 A00                  | Server      | [9f365307f3](https://linux-hardware.org/?probe=9f365307f3) | Dec 30, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | Notebook    | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | Notebook    | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [63487a2957](https://linux-hardware.org/?probe=63487a2957) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [0b632b7ae8](https://linux-hardware.org/?probe=0b632b7ae8) | Nov 27, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| HP            | 3048h                       | Desktop     | [33ced86304](https://linux-hardware.org/?probe=33ced86304) | Nov 19, 2022 |
| HP            | 3048h                       | Desktop     | [e5fdb1f67a](https://linux-hardware.org/?probe=e5fdb1f67a) | Nov 19, 2022 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8a149b06a1](https://linux-hardware.org/?probe=8a149b06a1) | Nov 12, 2022 |
| Acer          | AOD255E                     | Notebook    | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| Toshiba       | Satellite L15-B             | Notebook    | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| HP            | 431 Notebook                | Notebook    | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| AOpen         | D1007 0BBA                  | Desktop     | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [cf8128637b](https://linux-hardware.org/?probe=cf8128637b) | Sep 24, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e63b24acc3](https://linux-hardware.org/?probe=e63b24acc3) | Sep 24, 2022 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3468d8c911](https://linux-hardware.org/?probe=3468d8c911) | Sep 24, 2022 |
| ASUSTek       | X451CA                      | Notebook    | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| Star Labs     | Lite                        | Notebook    | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| ASRock        | A520M-HVS                   | Desktop     | [842ad7d4d2](https://linux-hardware.org/?probe=842ad7d4d2) | Aug 22, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [49ba856687](https://linux-hardware.org/?probe=49ba856687) | Aug 03, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| HP            | Presario CQ56               | Notebook    | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | Desktop     | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| MSI           | MS-AA1511                   | All in one  | [80c9ccb7c7](https://linux-hardware.org/?probe=80c9ccb7c7) | Jun 06, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | 3397                        | Desktop     | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| HP            | Berknip                     | Notebook    | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| ASUSTek       | X402CA                      | Notebook    | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | Notebook    | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Samsung       | N100SP                      | Notebook    | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Intel         | W7650                       | Notebook    | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | Desktop     | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| Haier         | U1520EM                     | Notebook    | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Google        | Celes                       | Notebook    | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASRock        | Q1900M                      | Desktop     | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| HP            | 3647h                       | Desktop     | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Alienware     | M17                         | Notebook    | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| Pegatron      | Narra6                      | Desktop     | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Positivo      | N600                        | Notebook    | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | Notebook    | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Toshiba       | Satellite C875              | Notebook    | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Dell          | 0FJM8V A03                  | Server      | [398f8f6326](https://linux-hardware.org/?probe=398f8f6326) | Feb 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | Notebook    | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Sony          | VPCEJ1E1E                   | Notebook    | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | Desktop     | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ea7740294a](https://linux-hardware.org/?probe=ea7740294a) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| MSI           | Katana GF76 11UC            | Notebook    | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| ASUSTek       | CM1435                      | Desktop     | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Dell          | Latitude 3330               | Notebook    | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | Notebook    | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| Acer          | Aspire X1700                | Desktop     | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| Foxconn       | 2AA9h                       | Desktop     | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Samsung       | R40/R41                     | Notebook    | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| HP            | Presario CQ58               | Notebook    | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [45ba0657f1](https://linux-hardware.org/?probe=45ba0657f1) | Oct 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| MSI           | MS-7309                     | Desktop     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Intel         | W7650                       | Notebook    | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | Notebook    | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | Desktop     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Pegatron      | Acacia                      | Desktop     | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | Desktop     | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | P8C WS                      | Desktop     | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Dell          | 01V648 A03                  | Server      | [f46a021c88](https://linux-hardware.org/?probe=f46a021c88) | Sep 02, 2021 |
| Notebook      | NL40_50GU                   | Notebook    | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | Desktop     | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | Notebook    | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| Dell          | Latitude E5450              | Notebook    | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | 8299                        | Desktop     | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | Notebook    | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | 0CN7X8 A05                  | Server      | [e5766c8331](https://linux-hardware.org/?probe=e5766c8331) | Jul 22, 2021 |
| HP            | 0A1Ch E                     | Desktop     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | Desktop     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | Notebook    | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [2383fe9425](https://linux-hardware.org/?probe=2383fe9425) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| Notebook      | NHxxRZQ                     | Notebook    | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [5e9110ee62](https://linux-hardware.org/?probe=5e9110ee62) | Jun 18, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| Samsung       | RC512                       | Notebook    | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | Notebook    | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | Notebook    | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| Dell          | Latitude D630               | Notebook    | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| ASUSTek       | K8N                         | Desktop     | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | Desktop     | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| HP            | 09C4h                       | Desktop     | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Dell          | 0HY175 A03                  | Desktop     | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | Desktop     | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | Desktop     | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| MSI           | H61M-E33                    | Desktop     | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| ASUSTek       | K8N                         | Desktop     | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| HP            | Notebook                    | Notebook    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | IMEDIA S1350                | Desktop     | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Inspiron 7706 2n1           | Convertible | [82eb222c26](https://linux-hardware.org/?probe=82eb222c26) | Apr 23, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | Notebook    | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | Notebook    | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | Desktop     | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| Lenovo        | S10-3                       | Notebook    | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | System XPS 15Z              | Notebook    | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| ASUSTek       | P53E                        | Notebook    | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Toshiba       | Satellite A660              | Notebook    | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | Notebook    | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | Desktop     | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Itautec       | Infoway w7430               | Notebook    | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | Notebook    | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| Intel         | ChiefRiver                  | Desktop     | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | Notebook    | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | Notebook    | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| Supermicro    | X8DA3                       | Server      | [039bf2c96a](https://linux-hardware.org/?probe=039bf2c96a) | Feb 04, 2021 |
| Supermicro    | X8DA3                       | Server      | [3731f93e51](https://linux-hardware.org/?probe=3731f93e51) | Feb 04, 2021 |
| HP            | 3048h                       | Desktop     | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | Notebook    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | Notebook    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | Notebook    | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | Notebook    | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | Desktop     | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | Notebook    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | Notebook    | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | Notebook    | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Dell          | 0WG864                      | Desktop     | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | Notebook    | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | Desktop     | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Panasonic     | CF-52PGNBE2M                | Notebook    | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| HP            | 2820h                       | Desktop     | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | Notebook    | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Pegatron      | Narra6                      | Desktop     | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| Positivo      | S14BW01                     | Notebook    | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | 09F8h                       | Desktop     | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | Notebook    | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | Desktop     | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | Desktop     | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | Notebook    | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | Notebook    | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | Notebook    | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | Notebook    | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | Notebook    | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | Notebook    | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | Notebook    | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Dell          | 0J3C2F A02                  | Desktop     | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| Acer          | Extensa 4620                | Notebook    | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| ASRock        | G41M-GS3                    | Desktop     | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c1a4649fc7](https://linux-hardware.org/?probe=c1a4649fc7) | Oct 20, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [003da597cd](https://linux-hardware.org/?probe=003da597cd) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | Notebook    | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | Notebook    | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | Notebook    | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| MSI           | H97M-E35                    | Desktop     | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [53ecc0af0c](https://linux-hardware.org/?probe=53ecc0af0c) | Oct 07, 2020 |
| HP            | Unknown                     | Notebook    | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| MSI           | H110M ECO                   | Desktop     | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [9a5387bb3b](https://linux-hardware.org/?probe=9a5387bb3b) | Oct 04, 2020 |
| Dell          | Latitude D630               | Notebook    | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [5c305017e8](https://linux-hardware.org/?probe=5c305017e8) | Sep 13, 2020 |
| Acer          | Prespa M                    | Notebook    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| ASRock        | A320M-DGS                   | Desktop     | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| Acer          | Prespa M                    | Notebook    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | Notebook    | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | Notebook    | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | Notebook    | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | Notebook    | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Google        | Gandof                      | Notebook    | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| Acer          | Aspire ES1-522              | Notebook    | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| Dell          | 0CU409                      | Desktop     | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASRock        | A320M-HD                    | Desktop     | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| ASUSTek       | K50C                        | Notebook    | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| Lenovo        | ThinkCentre M58p 7220W21    | Desktop     | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Lenovo        | SDK0E50515 STD              | Desktop     | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| HP            | ProBook 445 G7              | Notebook    | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| Acer          | V5-171                      | Notebook    | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | Desktop     | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| Positivo      | H14BT58                     | Notebook    | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | Notebook    | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| IBM           | eServer x3105 -[434722J]... | Desktop     | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Dell          | Studio 1555                 | Notebook    | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| Dell          | Latitude D520               | Notebook    | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASUSTek       | Q302LA                      | Notebook    | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | Notebook    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | Notebook    | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| HP            | 3396                        | Desktop     | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| Acer          | Swift SF314-52G             | Notebook    | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | Notebook    | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | Notebook    | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | Notebook    | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | Notebook    | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| HP            | Compaq 615                  | Notebook    | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| MSI           | 0A48                        | Desktop     | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Acer          | Aspire 5734Z                | Notebook    | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| HP            | Pavilion 15                 | Notebook    | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| HP            | Pavilion dv5                | Notebook    | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [6e0b7c86d5](https://linux-hardware.org/?probe=6e0b7c86d5) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [9a4a664a94](https://linux-hardware.org/?probe=9a4a664a94) | May 30, 2020 |
| Positivo      | S14CT01                     | Notebook    | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| HP            | 21B4 A01                    | Desktop     | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| ASUSTek       | X201E                       | Notebook    | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| Packard Be... | EN Butterfly s              | Notebook    | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | Desktop     | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| Acer          | Aspire XC-703G              | Desktop     | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | Notebook                    | Notebook    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| HP            | 17E2                        | Mini pc     | [fe57173b3f](https://linux-hardware.org/?probe=fe57173b3f) | May 01, 2020 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu_20.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 32        | 6.69%   |
| 5.4.0-52-generic  | 22        | 4.6%    |
| 5.4.0-48-generic  | 13        | 2.72%   |
| 5.11.0-27-generic | 13        | 2.72%   |
| 5.4.0-47-generic  | 12        | 2.51%   |
| 5.4.0-26-generic  | 12        | 2.51%   |
| 5.4.0-54-generic  | 11        | 2.3%    |
| 5.4.0-40-generic  | 11        | 2.3%    |
| 5.13.0-28-generic | 11        | 2.3%    |
| 5.4.0-29-generic  | 10        | 2.09%   |
| 5.4.0-33-generic  | 9         | 1.88%   |
| 5.8.0-50-generic  | 8         | 1.67%   |
| 5.4.0-65-generic  | 8         | 1.67%   |
| 5.13.0-30-generic | 8         | 1.67%   |
| 5.11.0-38-generic | 8         | 1.67%   |
| 5.4.0-73-generic  | 7         | 1.46%   |
| 5.4.0-37-generic  | 7         | 1.46%   |
| 5.13.0-40-generic | 7         | 1.46%   |
| 5.8.0-53-generic  | 6         | 1.26%   |
| 5.8.0-41-generic  | 6         | 1.26%   |
| 5.4.0-91-generic  | 6         | 1.26%   |
| 5.4.0-72-generic  | 6         | 1.26%   |
| 5.4.0-67-generic  | 6         | 1.26%   |
| 5.11.0-43-generic | 6         | 1.26%   |
| 5.8.0-55-generic  | 5         | 1.05%   |
| 5.8.0-45-generic  | 5         | 1.05%   |
| 5.4.0-89-generic  | 5         | 1.05%   |
| 5.4.0-60-generic  | 5         | 1.05%   |
| 5.4.0-59-generic  | 5         | 1.05%   |
| 5.4.0-58-generic  | 5         | 1.05%   |
| 5.4.0-51-generic  | 5         | 1.05%   |
| 5.4.0-131-generic | 5         | 1.05%   |
| 5.4.0-122-generic | 5         | 1.05%   |
| 5.15.0-46-generic | 5         | 1.05%   |
| 5.15.0-41-generic | 5         | 1.05%   |
| 5.11.0-37-generic | 5         | 1.05%   |
| 5.8.0-63-generic  | 4         | 0.84%   |
| 5.8.0-59-generic  | 4         | 0.84%   |
| 5.4.0-81-generic  | 4         | 0.84%   |
| 5.4.0-77-generic  | 4         | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 266       | 59.51%  |
| 5.8.0   | 51        | 11.41%  |
| 5.11.0  | 49        | 10.96%  |
| 5.13.0  | 40        | 8.95%   |
| 5.15.0  | 30        | 6.71%   |
| 5.6.0   | 2         | 0.45%   |
| 5.9.0   | 1         | 0.22%   |
| 5.7.9   | 1         | 0.22%   |
| 5.6.15  | 1         | 0.22%   |
| 5.5.2   | 1         | 0.22%   |
| 5.4.30  | 1         | 0.22%   |
| 5.3.18  | 1         | 0.22%   |
| 5.16.5  | 1         | 0.22%   |
| 5.14.0  | 1         | 0.22%   |
| 5.10.0  | 1         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 267       | 59.73%  |
| 5.8     | 51        | 11.41%  |
| 5.11    | 49        | 10.96%  |
| 5.13    | 40        | 8.95%   |
| 5.15    | 30        | 6.71%   |
| 5.6     | 3         | 0.67%   |
| 5.9     | 1         | 0.22%   |
| 5.7     | 1         | 0.22%   |
| 5.5     | 1         | 0.22%   |
| 5.3     | 1         | 0.22%   |
| 5.16    | 1         | 0.22%   |
| 5.14    | 1         | 0.22%   |
| 5.10    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 440       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 416       | 94.12%  |
| LXDE       | 11        | 2.49%   |
| GNOME      | 6         | 1.36%   |
| i3         | 2         | 0.45%   |
| Cinnamon   | 2         | 0.45%   |
| XFCE       | 1         | 0.23%   |
| X-Cinnamon | 1         | 0.23%   |
| MATE       | 1         | 0.23%   |
| KDE5       | 1         | 0.23%   |
| KDE        | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 415       | 94.1%   |
| Tty     | 21        | 4.76%   |
| Wayland | 4         | 0.91%   |
| Unknown | 1         | 0.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 243       | 54.24%  |
| Unknown | 128       | 28.57%  |
| LightDM | 28        | 6.25%   |
| GDM     | 28        | 6.25%   |
| TDM     | 17        | 3.79%   |
| GDM3    | 3         | 0.67%   |
| LXDM    | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 139       | 31.59%  |
| fr_FR   | 58        | 13.18%  |
| pt_BR   | 35        | 7.95%   |
| de_DE   | 29        | 6.59%   |
| it_IT   | 25        | 5.68%   |
| en_GB   | 25        | 5.68%   |
| C       | 19        | 4.32%   |
| ru_RU   | 14        | 3.18%   |
| es_ES   | 10        | 2.27%   |
| en_AU   | 9         | 2.05%   |
| pl_PL   | 6         | 1.36%   |
| ja_JP   | 5         | 1.14%   |
| hu_HU   | 4         | 0.91%   |
| es_MX   | 4         | 0.91%   |
| en_CA   | 4         | 0.91%   |
| nl_NL   | 3         | 0.68%   |
| fr_CH   | 3         | 0.68%   |
| fi_FI   | 3         | 0.68%   |
| es_AR   | 3         | 0.68%   |
| en_ZA   | 3         | 0.68%   |
| en_IN   | 3         | 0.68%   |
| en_IE   | 3         | 0.68%   |
| cs_CZ   | 3         | 0.68%   |
| fr_BE   | 2         | 0.45%   |
| es_CR   | 2         | 0.45%   |
| es_CL   | 2         | 0.45%   |
| en_SG   | 2         | 0.45%   |
| en_PH   | 2         | 0.45%   |
| en_NZ   | 2         | 0.45%   |
| el_GR   | 2         | 0.45%   |
| de_CH   | 2         | 0.45%   |
| Unknown | 2         | 0.45%   |
| tr_TR   | 1         | 0.23%   |
| sv_SE   | 1         | 0.23%   |
| ru_UA   | 1         | 0.23%   |
| pt_PT   | 1         | 0.23%   |
| nl_BE   | 1         | 0.23%   |
| lt_LT   | 1         | 0.23%   |
| fr_CA   | 1         | 0.23%   |
| es_UY   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 255       | 57.82%  |
| EFI  | 186       | 42.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 405       | 91.84%  |
| Overlay | 21        | 4.76%   |
| Btrfs   | 7         | 1.59%   |
| Xfs     | 3         | 0.68%   |
| Zfs     | 1         | 0.23%   |
| Tmpfs   | 1         | 0.23%   |
| F2fs    | 1         | 0.23%   |
| Ext2    | 1         | 0.23%   |
| Aufs    | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 163       | 36.63%  |
| GPT     | 155       | 34.83%  |
| MBR     | 127       | 28.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 384       | 86.88%  |
| Yes       | 58        | 13.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 317       | 71.56%  |
| Yes       | 126       | 28.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 81        | 18.41%  |
| Lenovo                      | 56        | 12.73%  |
| Dell                        | 53        | 12.05%  |
| ASUSTek Computer            | 51        | 11.59%  |
| Acer                        | 25        | 5.68%   |
| MSI                         | 22        | 5%      |
| Toshiba                     | 15        | 3.41%   |
| Gigabyte Technology         | 15        | 3.41%   |
| ASRock                      | 15        | 3.41%   |
| Intel                       | 11        | 2.5%    |
| Samsung Electronics         | 10        | 2.27%   |
| Positivo                    | 7         | 1.59%   |
| Apple                       | 6         | 1.36%   |
| Sony                        | 5         | 1.14%   |
| Pegatron                    | 5         | 1.14%   |
| Notebook                    | 5         | 1.14%   |
| Fujitsu                     | 5         | 1.14%   |
| Packard Bell                | 4         | 0.91%   |
| Google                      | 4         | 0.91%   |
| Unknown                     | 4         | 0.91%   |
| AMI                         | 3         | 0.68%   |
| AAEON                       | 3         | 0.68%   |
| ZOTAC                       | 2         | 0.45%   |
| YASHI                       | 2         | 0.45%   |
| Fujitsu Siemens             | 2         | 0.45%   |
| Foxconn                     | 2         | 0.45%   |
| Biostar                     | 2         | 0.45%   |
| UNOWHY                      | 1         | 0.23%   |
| Timi                        | 1         | 0.23%   |
| Teclast                     | 1         | 0.23%   |
| Supermicro                  | 1         | 0.23%   |
| Star Labs                   | 1         | 0.23%   |
| Prestigio                   | 1         | 0.23%   |
| Panasonic                   | 1         | 0.23%   |
| Mediacom                    | 1         | 0.23%   |
| Lanix                       | 1         | 0.23%   |
| LAMINA                      | 1         | 0.23%   |
| Itautec                     | 1         | 0.23%   |
| IBM                         | 1         | 0.23%   |
| I-Life Digital Technologies | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 7         | 1.59%   |
| HP Notebook                   | 5         | 1.14%   |
| HP Pavilion dv6               | 4         | 0.91%   |
| Dell Latitude D630            | 3         | 0.68%   |
| AAEON MF-001                  | 3         | 0.68%   |
| YASHI MYBOOK 360              | 2         | 0.45%   |
| Positivo H14BT58              | 2         | 0.45%   |
| MSI MS-7C37                   | 2         | 0.45%   |
| MSI MS-7B89                   | 2         | 0.45%   |
| Lenovo IdeaPad 320-15AST 80XV | 2         | 0.45%   |
| HP t620 Quad Core TC          | 2         | 0.45%   |
| HP ProBook 450 G6             | 2         | 0.45%   |
| HP ProBook 440 G8 Notebook PC | 2         | 0.45%   |
| HP ProBook 440 G7             | 2         | 0.45%   |
| HP Pavilion x2 Detachable     | 2         | 0.45%   |
| HP Pavilion g7                | 2         | 0.45%   |
| HP Compaq 6000 Pro SFF PC     | 2         | 0.45%   |
| Dell OptiPlex 790             | 2         | 0.45%   |
| Dell Inspiron N5010           | 2         | 0.45%   |
| Dell Inspiron 15-3567         | 2         | 0.45%   |
| ASUS M5A97 R2.0               | 2         | 0.45%   |
| ASUS 1015BX                   | 2         | 0.45%   |
| ASRock N68-VS3 UCC            | 2         | 0.45%   |
| ASRock FM2A85X Extreme6       | 2         | 0.45%   |
| Apple MacBookPro8,1           | 2         | 0.45%   |
| ZOTAC ZBOX-CI323NANO          | 1         | 0.23%   |
| ZOTAC NM10                    | 1         | 0.23%   |
| UNOWHY Y13G010S4EI            | 1         | 0.23%   |
| Toshiba Satellite S55-B       | 1         | 0.23%   |
| Toshiba Satellite Pro U400    | 1         | 0.23%   |
| Toshiba Satellite P200        | 1         | 0.23%   |
| Toshiba Satellite L840        | 1         | 0.23%   |
| Toshiba Satellite L70-B       | 1         | 0.23%   |
| Toshiba Satellite L305        | 1         | 0.23%   |
| Toshiba Satellite L15-B       | 1         | 0.23%   |
| Toshiba Satellite C875        | 1         | 0.23%   |
| Toshiba Satellite C855D       | 1         | 0.23%   |
| Toshiba Satellite C70D-B      | 1         | 0.23%   |
| Toshiba Satellite C670D-12N   | 1         | 0.23%   |
| Toshiba Satellite C55D-A      | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 20        | 4.55%   |
| Acer Aspire           | 20        | 4.55%   |
| Lenovo ThinkPad       | 19        | 4.32%   |
| Lenovo IdeaPad        | 16        | 3.64%   |
| HP Compaq             | 16        | 3.64%   |
| Toshiba Satellite     | 14        | 3.18%   |
| HP Pavilion           | 14        | 3.18%   |
| HP ProBook            | 13        | 2.95%   |
| Dell Latitude         | 8         | 1.82%   |
| Unknown               | 7         | 1.59%   |
| Lenovo ThinkCentre    | 6         | 1.36%   |
| Dell OptiPlex         | 6         | 1.36%   |
| ASUS VivoBook         | 6         | 1.36%   |
| HP Notebook           | 5         | 1.14%   |
| HP EliteBook          | 5         | 1.14%   |
| Dell XPS              | 4         | 0.91%   |
| Dell Vostro           | 4         | 0.91%   |
| Dell PowerEdge        | 4         | 0.91%   |
| HP t620               | 3         | 0.68%   |
| HP Presario           | 3         | 0.68%   |
| HP Laptop             | 3         | 0.68%   |
| AAEON MF-001          | 3         | 0.68%   |
| YASHI MYBOOK          | 2         | 0.45%   |
| Positivo H14BT58      | 2         | 0.45%   |
| Packard Bell EasyNote | 2         | 0.45%   |
| Notebook W54          | 2         | 0.45%   |
| MSI MS-7C37           | 2         | 0.45%   |
| MSI MS-7B89           | 2         | 0.45%   |
| HP Spectre            | 2         | 0.45%   |
| Gigabyte B450M        | 2         | 0.45%   |
| Fujitsu LIFEBOOK      | 2         | 0.45%   |
| Dell Studio           | 2         | 0.45%   |
| ASUS M5A97            | 2         | 0.45%   |
| ASUS 1015BX           | 2         | 0.45%   |
| ASRock N68-VS3        | 2         | 0.45%   |
| ASRock FM2A85X        | 2         | 0.45%   |
| Apple MacBookPro8     | 2         | 0.45%   |
| ZOTAC ZBOX-CI323NANO  | 1         | 0.23%   |
| ZOTAC NM10            | 1         | 0.23%   |
| UNOWHY Y13G010S4EI    | 1         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 37        | 8.41%   |
| 2010 | 36        | 8.18%   |
| 2011 | 35        | 7.95%   |
| 2019 | 34        | 7.73%   |
| 2013 | 33        | 7.5%    |
| 2008 | 31        | 7.05%   |
| 2014 | 30        | 6.82%   |
| 2007 | 28        | 6.36%   |
| 2017 | 26        | 5.91%   |
| 2009 | 26        | 5.91%   |
| 2020 | 24        | 5.45%   |
| 2016 | 23        | 5.23%   |
| 2015 | 23        | 5.23%   |
| 2018 | 19        | 4.32%   |
| 2021 | 15        | 3.41%   |
| 2006 | 13        | 2.95%   |
| 2005 | 4         | 0.91%   |
| 2022 | 2         | 0.45%   |
| 2004 | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 268       | 60.91%  |
| Desktop     | 151       | 34.32%  |
| Mini pc     | 6         | 1.36%   |
| Server      | 6         | 1.36%   |
| Convertible | 5         | 1.14%   |
| Tablet      | 2         | 0.45%   |
| All in one  | 2         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 410       | 92.76%  |
| Enabled  | 32        | 7.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 435       | 98.86%  |
| Yes  | 5         | 1.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 132       | 29.73%  |
| 4.01-8.0        | 93        | 20.95%  |
| 1.01-2.0        | 73        | 16.44%  |
| 8.01-16.0       | 57        | 12.84%  |
| 16.01-24.0      | 44        | 9.91%   |
| 32.01-64.0      | 16        | 3.6%    |
| 2.01-3.0        | 13        | 2.93%   |
| 24.01-32.0      | 6         | 1.35%   |
| 64.01-256.0     | 4         | 0.9%    |
| 0.51-1.0        | 4         | 0.9%    |
| More than 256.0 | 2         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 225       | 48.39%  |
| 0.51-1.0   | 79        | 16.99%  |
| 2.01-3.0   | 69        | 14.84%  |
| 4.01-8.0   | 47        | 10.11%  |
| 3.01-4.0   | 29        | 6.24%   |
| 0.01-0.5   | 9         | 1.94%   |
| 8.01-16.0  | 5         | 1.08%   |
| 32.01-64.0 | 1         | 0.22%   |
| 16.01-24.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 291       | 65.54%  |
| 2      | 110       | 24.77%  |
| 4      | 14        | 3.15%   |
| 3      | 13        | 2.93%   |
| 5      | 7         | 1.58%   |
| 6      | 3         | 0.68%   |
| 7      | 2         | 0.45%   |
| 0      | 2         | 0.45%   |
| 17     | 1         | 0.23%   |
| 14     | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 229       | 51.58%  |
| No        | 215       | 48.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 394       | 89.34%  |
| No        | 47        | 10.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 331       | 75.23%  |
| No        | 109       | 24.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 240       | 53.93%  |
| Yes       | 205       | 46.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 71        | 16.03%  |
| France       | 61        | 13.77%  |
| Brazil       | 41        | 9.26%   |
| Germany      | 37        | 8.35%   |
| Italy        | 34        | 7.67%   |
| Russia       | 19        | 4.29%   |
| UK           | 15        | 3.39%   |
| Spain        | 12        | 2.71%   |
| Switzerland  | 11        | 2.48%   |
| Netherlands  | 10        | 2.26%   |
| Australia    | 10        | 2.26%   |
| Poland       | 8         | 1.81%   |
| Hungary      | 7         | 1.58%   |
| Finland      | 7         | 1.58%   |
| Mexico       | 6         | 1.35%   |
| Japan        | 5         | 1.13%   |
| Ireland      | 5         | 1.13%   |
| Czechia      | 5         | 1.13%   |
| Canada       | 5         | 1.13%   |
| Belgium      | 5         | 1.13%   |
| Ukraine      | 4         | 0.9%    |
| South Africa | 4         | 0.9%    |
| Indonesia    | 4         | 0.9%    |
| Romania      | 3         | 0.68%   |
| Norway       | 3         | 0.68%   |
| New Zealand  | 3         | 0.68%   |
| India        | 3         | 0.68%   |
| Greece       | 3         | 0.68%   |
| Argentina    | 3         | 0.68%   |
| Vietnam      | 2         | 0.45%   |
| Slovenia     | 2         | 0.45%   |
| Slovakia     | 2         | 0.45%   |
| Singapore    | 2         | 0.45%   |
| Puerto Rico  | 2         | 0.45%   |
| Philippines  | 2         | 0.45%   |
| Iran         | 2         | 0.45%   |
| Costa Rica   | 2         | 0.45%   |
| Colombia     | 2         | 0.45%   |
| Chile        | 2         | 0.45%   |
| Uruguay      | 1         | 0.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Rome              | 7         | 1.53%   |
| Paris             | 6         | 1.31%   |
| Milan             | 5         | 1.09%   |
| Melbourne         | 5         | 1.09%   |
| Helsinki          | 4         | 0.88%   |
| Zurich            | 3         | 0.66%   |
| Wellington        | 3         | 0.66%   |
| Sao Paulo         | 3         | 0.66%   |
| Salvador          | 3         | 0.66%   |
| Pécs             | 3         | 0.66%   |
| Munich            | 3         | 0.66%   |
| Moscow            | 3         | 0.66%   |
| Mexico City       | 3         | 0.66%   |
| Florence          | 3         | 0.66%   |
| Derry             | 3         | 0.66%   |
| Brasília         | 3         | 0.66%   |
| Athens            | 3         | 0.66%   |
| Yekaterinburg     | 2         | 0.44%   |
| Vicosa            | 2         | 0.44%   |
| Tehran            | 2         | 0.44%   |
| Stuttgart         | 2         | 0.44%   |
| Southampton       | 2         | 0.44%   |
| Raahe             | 2         | 0.44%   |
| Poznan            | 2         | 0.44%   |
| Porto Alegre      | 2         | 0.44%   |
| Oradea            | 2         | 0.44%   |
| Omsk              | 2         | 0.44%   |
| Mount Vernon      | 2         | 0.44%   |
| Krakow            | 2         | 0.44%   |
| Karlsruhe         | 2         | 0.44%   |
| Jurong West       | 2         | 0.44%   |
| Houston           | 2         | 0.44%   |
| Heredia           | 2         | 0.44%   |
| Hamburg           | 2         | 0.44%   |
| Frankfurt am Main | 2         | 0.44%   |
| Fortaleza         | 2         | 0.44%   |
| Figeac            | 2         | 0.44%   |
| Dublin            | 2         | 0.44%   |
| Curitiba          | 2         | 0.44%   |
| Cuernavaca        | 2         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 111       | 141    | 19.04%  |
| WDC                 | 101       | 143    | 17.32%  |
| Samsung Electronics | 66        | 93     | 11.32%  |
| Toshiba             | 39        | 42     | 6.69%   |
| Unknown             | 38        | 44     | 6.52%   |
| Hitachi             | 34        | 41     | 5.83%   |
| Kingston            | 27        | 30     | 4.63%   |
| Crucial             | 22        | 36     | 3.77%   |
| SanDisk             | 16        | 21     | 2.74%   |
| Intel               | 12        | 13     | 2.06%   |
| Fujitsu             | 9         | 9      | 1.54%   |
| China               | 9         | 9      | 1.54%   |
| A-DATA Technology   | 8         | 9      | 1.37%   |
| SK hynix            | 7         | 7      | 1.2%    |
| HGST                | 7         | 9      | 1.2%    |
| PNY                 | 5         | 5      | 0.86%   |
| Maxtor              | 4         | 4      | 0.69%   |
| Apacer              | 4         | 4      | 0.69%   |
| Team                | 3         | 3      | 0.51%   |
| Micron Technology   | 3         | 3      | 0.51%   |
| LITEONIT            | 3         | 3      | 0.51%   |
| LDLC                | 3         | 3      | 0.51%   |
| KIOXIA              | 3         | 3      | 0.51%   |
| JMicron Technology  | 3         | 3      | 0.51%   |
| Corsair             | 3         | 3      | 0.51%   |
| Unknown             | 3         | 4      | 0.51%   |
| USB                 | 2         | 2      | 0.34%   |
| Transcend           | 2         | 2      | 0.34%   |
| Patriot             | 2         | 2      | 0.34%   |
| OCZ                 | 2         | 2      | 0.34%   |
| Intenso             | 2         | 2      | 0.34%   |
| Hewlett-Packard     | 2         | 7      | 0.34%   |
| Apple               | 2         | 4      | 0.34%   |
| Vaseky              | 1         | 1      | 0.17%   |
| TO Exter            | 1         | 1      | 0.17%   |
| TCSUNBOW            | 1         | 1      | 0.17%   |
| Star                | 1         | 1      | 0.17%   |
| SPCC                | 1         | 1      | 0.17%   |
| QGEEM               | 1         | 1      | 0.17%   |
| PNY USB             | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 11        | 1.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 7         | 1.12%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 1.12%   |
| Toshiba MQ01ABF050 500GB             | 6         | 0.96%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 0.8%    |
| Toshiba MQ01ABD100 1TB               | 4         | 0.64%   |
| Seagate ST9500325AS 500GB            | 4         | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.64%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.64%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.64%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.64%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.64%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.64%   |
| A-DATA SU650 240GB SSD               | 4         | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 0.48%   |
| WDC WDS120G2G0A-00JH30 128GB SSD     | 3         | 0.48%   |
| WDC WD10SPZX-24Z10T0 1TB             | 3         | 0.48%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 3         | 0.48%   |
| Unknown SD/MMC/MS PRO 250GB          | 3         | 0.48%   |
| Seagate ST3250310AS 250GB            | 3         | 0.48%   |
| Seagate Backup+ Hub BK 6TB           | 3         | 0.48%   |
| Samsung HD502IJ 500GB                | 3         | 0.48%   |
| Samsung HD103SJ 1TB                  | 3         | 0.48%   |
| PNY CS900 240GB SSD                  | 3         | 0.48%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 0.48%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 0.48%   |
| Unknown                              | 3         | 0.48%   |
| WDC WD800JD-60LSA5 80GB              | 2         | 0.32%   |
| WDC WD7500BPVX-55JC3T3 752GB         | 2         | 0.32%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 2         | 0.32%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.32%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.32%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.32%   |
| WDC WD2500AAKX-07U6AA1 250GB         | 2         | 0.32%   |
| WDC WD2500AAJS-75M0A0 249GB          | 2         | 0.32%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2         | 0.32%   |
| WDC WD10EACS-00D6B0 1TB              | 2         | 0.32%   |
| USB 3.0 480GB                        | 2         | 0.32%   |
| Unknown MMC Card  64GB               | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 111       | 141    | 35.58%  |
| WDC                 | 86        | 123    | 27.56%  |
| Hitachi             | 34        | 41     | 10.9%   |
| Toshiba             | 31        | 34     | 9.94%   |
| Samsung Electronics | 23        | 28     | 7.37%   |
| Fujitsu             | 9         | 9      | 2.88%   |
| HGST                | 7         | 9      | 2.24%   |
| Unknown             | 3         | 3      | 0.96%   |
| Maxtor              | 3         | 3      | 0.96%   |
| USB                 | 2         | 2      | 0.64%   |
| LaCie               | 1         | 1      | 0.32%   |
| Hewlett-Packard     | 1         | 1      | 0.32%   |
| Apple               | 1         | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 38     | 16.67%  |
| Kingston            | 23        | 25     | 12.78%  |
| Crucial             | 22        | 36     | 12.22%  |
| WDC                 | 12        | 15     | 6.67%   |
| SanDisk             | 12        | 17     | 6.67%   |
| Intel               | 9         | 10     | 5%      |
| China               | 9         | 9      | 5%      |
| A-DATA Technology   | 6         | 7      | 3.33%   |
| Toshiba             | 5         | 5      | 2.78%   |
| PNY                 | 5         | 5      | 2.78%   |
| Apacer              | 4         | 4      | 2.22%   |
| Team                | 3         | 3      | 1.67%   |
| LITEONIT            | 3         | 3      | 1.67%   |
| Corsair             | 3         | 3      | 1.67%   |
| Transcend           | 2         | 2      | 1.11%   |
| SK hynix            | 2         | 2      | 1.11%   |
| Patriot             | 2         | 2      | 1.11%   |
| OCZ                 | 2         | 2      | 1.11%   |
| LDLC                | 2         | 2      | 1.11%   |
| Intenso             | 2         | 2      | 1.11%   |
| Vaseky              | 1         | 1      | 0.56%   |
| Unknown             | 1         | 1      | 0.56%   |
| TO Exter            | 1         | 1      | 0.56%   |
| TCSUNBOW            | 1         | 1      | 0.56%   |
| Star                | 1         | 1      | 0.56%   |
| SPCC                | 1         | 1      | 0.56%   |
| PNY USB             | 1         | 1      | 0.56%   |
| ORTIAL              | 1         | 1      | 0.56%   |
| Micron Technology   | 1         | 1      | 0.56%   |
| Maxtor              | 1         | 1      | 0.56%   |
| Londisk             | 1         | 1      | 0.56%   |
| LITEON              | 1         | 2      | 0.56%   |
| Lexar               | 1         | 1      | 0.56%   |
| Leven               | 1         | 2      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| KingDian            | 1         | 1      | 0.56%   |
| Integral            | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 6      | 0.56%   |
| GOODRAM             | 1         | 1      | 0.56%   |
| External            | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 270       | 396    | 50.94%  |
| SSD     | 170       | 223    | 32.08%  |
| NVMe    | 45        | 62     | 8.49%   |
| MMC     | 38        | 47     | 7.17%   |
| Unknown | 7         | 7      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 379       | 598    | 78.63%  |
| NVMe | 44        | 61     | 9.13%   |
| MMC  | 38        | 47     | 7.88%   |
| SAS  | 21        | 29     | 4.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 305       | 410    | 69.32%  |
| 0.51-1.0   | 101       | 158    | 22.95%  |
| 1.01-2.0   | 20        | 26     | 4.55%   |
| 3.01-4.0   | 6         | 15     | 1.36%   |
| 2.01-3.0   | 5         | 6      | 1.14%   |
| 4.01-10.0  | 3         | 4      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 123       | 27.39%  |
| 251-500        | 114       | 25.39%  |
| 501-1000       | 52        | 11.58%  |
| 51-100         | 44        | 9.8%    |
| 1-20           | 30        | 6.68%   |
| 1001-2000      | 29        | 6.46%   |
| More than 3000 | 23        | 5.12%   |
| 21-50          | 22        | 4.9%    |
| 2001-3000      | 9         | 2%      |
| Unknown        | 3         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 196       | 42.98%  |
| 21-50          | 82        | 17.98%  |
| 101-250        | 58        | 12.72%  |
| 51-100         | 39        | 8.55%   |
| 251-500        | 27        | 5.92%   |
| 501-1000       | 25        | 5.48%   |
| 1001-2000      | 12        | 2.63%   |
| More than 3000 | 9         | 1.97%   |
| 2001-3000      | 5         | 1.1%    |
| Unknown        | 3         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 2.99%   |
| Seagate ST1000DM003-9YN162 1TB        | 2         | 2      | 2.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.49%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 1      | 1.49%   |
| WDC WD5000LUCT-62C26Y0 500GB          | 1         | 1      | 1.49%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 1      | 1.49%   |
| WDC WD400EB-00CPF0 40GB               | 1         | 1      | 1.49%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 1.49%   |
| WDC WD3200BEVT-75A23T0 320GB          | 1         | 1      | 1.49%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1         | 1      | 1.49%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 2      | 1.49%   |
| WDC WD2500AAJS-75M0A0 249GB           | 1         | 1      | 1.49%   |
| WDC WD1600AAJS-60B4A0 160GB           | 1         | 2      | 1.49%   |
| WDC WD10EADS-65M2B0 1TB               | 1         | 1      | 1.49%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 1.49%   |
| TCSUNBOW X1 32GB SSD                  | 1         | 1      | 1.49%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 1.49%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.49%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.49%   |
| Seagate ST9250410AS 250GB             | 1         | 1      | 1.49%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.49%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.49%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 1.49%   |
| Seagate ST360012A 64GB                | 1         | 1      | 1.49%   |
| Seagate ST3360320AS 360GB             | 1         | 1      | 1.49%   |
| Seagate ST3250310AS 250GB             | 1         | 1      | 1.49%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.49%   |
| Seagate ST3200822AS 200GB             | 1         | 1      | 1.49%   |
| Seagate ST3160812AS 160GB             | 1         | 1      | 1.49%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 1.49%   |
| Seagate ST250DM000-1BD141 250GB       | 1         | 1      | 1.49%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 1      | 1.49%   |
| Seagate ST1000NM0095-2DC10C 1TB       | 1         | 6      | 1.49%   |
| Seagate ST1000DX001-1CM162 1TB        | 1         | 1      | 1.49%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 1      | 1.49%   |
| SanDisk SSD PLUS 120GB                | 1         | 1      | 1.49%   |
| Samsung Electronics HM160JI 160GB     | 1         | 1      | 1.49%   |
| Samsung Electronics HM121HI 120GB     | 1         | 2      | 1.49%   |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 1.49%   |
| Maxtor STM3300622A 304GB              | 1         | 1      | 1.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 31.82%  |
| WDC                 | 12        | 14     | 18.18%  |
| Hitachi             | 7         | 8      | 10.61%  |
| Samsung Electronics | 3         | 4      | 4.55%   |
| Maxtor              | 3         | 3      | 4.55%   |
| Kingston            | 3         | 3      | 4.55%   |
| HGST                | 3         | 3      | 4.55%   |
| Crucial             | 3         | 3      | 4.55%   |
| SK hynix            | 2         | 2      | 3.03%   |
| Toshiba             | 1         | 1      | 1.52%   |
| TCSUNBOW            | 1         | 1      | 1.52%   |
| SanDisk             | 1         | 1      | 1.52%   |
| LDLC                | 1         | 1      | 1.52%   |
| KingSpec            | 1         | 1      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| Fujitsu             | 1         | 1      | 1.52%   |
| Apacer              | 1         | 1      | 1.52%   |
| A-DATA Technology   | 1         | 1      | 1.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 42%     |
| WDC                 | 11        | 13     | 22%     |
| Hitachi             | 7         | 8      | 14%     |
| Samsung Electronics | 3         | 4      | 6%      |
| Maxtor              | 3         | 3      | 6%      |
| HGST                | 3         | 3      | 6%      |
| Toshiba             | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 59     | 74.6%   |
| SSD  | 16        | 16     | 25.4%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 20%     |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 20%     |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 20%     |
| Samsung Electronics SSD 850 250GB | 1         | 1      | 20%     |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 4      | 60%     |
| Samsung Electronics | 2         | 2      | 40%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 210       | 306    | 43.75%  |
| Detected | 204       | 348    | 42.5%   |
| Malfunc  | 61        | 75     | 12.71%  |
| Failed   | 5         | 6      | 1.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 299       | 63.62%  |
| AMD                              | 81        | 17.23%  |
| Nvidia                           | 22        | 4.68%   |
| Samsung Electronics              | 14        | 2.98%   |
| SanDisk                          | 7         | 1.49%   |
| JMicron Technology               | 7         | 1.49%   |
| Marvell Technology Group         | 5         | 1.06%   |
| LSI Logic / Symbios Logic        | 4         | 0.85%   |
| Kingston Technology Company      | 4         | 0.85%   |
| ASMedia Technology               | 4         | 0.85%   |
| Toshiba America Info Systems     | 3         | 0.64%   |
| SK hynix                         | 3         | 0.64%   |
| KIOXIA                           | 3         | 0.64%   |
| VIA Technologies                 | 2         | 0.43%   |
| Silicon Motion                   | 2         | 0.43%   |
| Micron Technology                | 2         | 0.43%   |
| ADATA Technology                 | 2         | 0.43%   |
| Solid State Storage Technology   | 1         | 0.21%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| Phison Electronics               | 1         | 0.21%   |
| Micron/Crucial Technology        | 1         | 0.21%   |
| Hewlett-Packard                  | 1         | 0.21%   |
| Broadcom / LSI                   | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 50        | 8.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 24        | 4.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 22        | 3.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 19        | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 3.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 2.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 15        | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 15        | 2.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 2.24%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 11        | 1.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 1.9%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 10        | 1.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 1.72%   |
| Nvidia MCP61 SATA Controller                                                     | 9         | 1.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 9         | 1.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 1.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8         | 1.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 1.38%   |
| Nvidia MCP61 IDE                                                                 | 7         | 1.21%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 7         | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.03%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.03%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 1.03%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 6         | 1.03%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 6         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 6         | 1.03%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 0.86%   |
| JMicron JMB363 SATA/IDE Controller                                               | 5         | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.86%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 5         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.86%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 0.86%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 0.69%   |
| Nvidia MCP51 Serial ATA Controller                                               | 4         | 0.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 318       | 63.35%  |
| IDE  | 110       | 21.91%  |
| NVMe | 43        | 8.57%   |
| RAID | 29        | 5.78%   |
| SCSI | 2         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 336       | 76.36%  |
| AMD    | 104       | 23.64%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 8         | 1.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 6         | 1.36%   |
| Intel Core i3-6006U CPU @ 2.00GHz            | 6         | 1.36%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 6         | 1.36%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz  | 5         | 1.14%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 5         | 1.14%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 5         | 1.14%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 4         | 0.91%   |
| Intel Celeron N4020 CPU @ 1.10GHz            | 4         | 0.91%   |
| Intel Celeron CPU 847 @ 1.10GHz              | 4         | 0.91%   |
| AMD E-300 APU with Radeon HD Graphics        | 4         | 0.91%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 3         | 0.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 3         | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 3         | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 0.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 3         | 0.68%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 3         | 0.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 3         | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 0.68%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 3         | 0.68%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 3         | 0.68%   |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 3         | 0.68%   |
| Intel Celeron CPU J1900 @ 1.99GHz            | 3         | 0.68%   |
| Intel Atom CPU Z3735F @ 1.33GHz              | 3         | 0.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 3         | 0.68%   |
| AMD Ryzen 7 4700U with Radeon Graphics       | 3         | 0.68%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 3         | 0.68%   |
| AMD Ryzen 5 3600 6-Core Processor            | 3         | 0.68%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 3         | 0.68%   |
| AMD A10-6800K APU with Radeon HD Graphics    | 3         | 0.68%   |
| Intel Xeon CPU E5620 @ 2.40GHz               | 2         | 0.45%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 2         | 0.45%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz  | 2         | 0.45%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 2         | 0.45%   |
| Intel Pentium Dual CPU T2310 @ 1.46GHz       | 2         | 0.45%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 0.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 2         | 0.45%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 2         | 0.45%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 2         | 0.45%   |
| Intel Core i7-3770K CPU @ 3.50GHz            | 2         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 71        | 16.14%  |
| Intel Core i3           | 44        | 10%     |
| Intel Core i7           | 38        | 8.64%   |
| Intel Celeron           | 38        | 8.64%   |
| Intel Core 2 Duo        | 36        | 8.18%   |
| Intel Atom              | 33        | 7.5%    |
| Intel Pentium Dual-Core | 13        | 2.95%   |
| Other                   | 11        | 2.5%    |
| Intel Pentium           | 11        | 2.5%    |
| Intel Xeon              | 10        | 2.27%   |
| Intel Core 2            | 9         | 2.05%   |
| AMD Ryzen 7             | 9         | 2.05%   |
| AMD Ryzen 5             | 9         | 2.05%   |
| AMD Athlon 64 X2        | 8         | 1.82%   |
| Intel Pentium Dual      | 7         | 1.59%   |
| AMD E                   | 6         | 1.36%   |
| AMD Athlon II X2        | 6         | 1.36%   |
| Intel Core 2 Quad       | 5         | 1.14%   |
| AMD A10                 | 5         | 1.14%   |
| AMD Ryzen 3             | 4         | 0.91%   |
| AMD E1                  | 4         | 0.91%   |
| AMD A6                  | 4         | 0.91%   |
| AMD A4                  | 4         | 0.91%   |
| Intel Pentium Silver    | 3         | 0.68%   |
| Intel Celeron Dual-Core | 3         | 0.68%   |
| AMD Turion 64 X2 Mobile | 3         | 0.68%   |
| AMD GX                  | 3         | 0.68%   |
| AMD FX                  | 3         | 0.68%   |
| AMD Athlon 64           | 3         | 0.68%   |
| AMD A8                  | 3         | 0.68%   |
| Intel Pentium 4         | 2         | 0.45%   |
| AMD Sempron             | 2         | 0.45%   |
| AMD Ryzen Threadripper  | 2         | 0.45%   |
| AMD Ryzen 7 PRO         | 2         | 0.45%   |
| AMD Phenom II           | 2         | 0.45%   |
| AMD Athlon X2           | 2         | 0.45%   |
| Intel Pentium Gold      | 1         | 0.23%   |
| Intel Genuine           | 1         | 0.23%   |
| Intel Core m3           | 1         | 0.23%   |
| Intel Core 2 Solo       | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 265       | 60.23%  |
| 4      | 118       | 26.82%  |
| 1      | 20        | 4.55%   |
| 8      | 15        | 3.41%   |
| 6      | 14        | 3.18%   |
| 12     | 2         | 0.45%   |
| 3      | 2         | 0.45%   |
| 64     | 1         | 0.23%   |
| 40     | 1         | 0.23%   |
| 20     | 1         | 0.23%   |
| 16     | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 434       | 98.64%  |
| 2      | 5         | 1.14%   |
| 4      | 1         | 0.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 242       | 55%     |
| 2      | 198       | 45%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 440       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 10.34%  |
| 0x206a7    | 36        | 8.09%   |
| 0x1067a    | 26        | 5.84%   |
| 0x306a9    | 20        | 4.49%   |
| 0x6fd      | 19        | 4.27%   |
| 0x306c3    | 17        | 3.82%   |
| 0x406c4    | 13        | 2.92%   |
| 0x40651    | 13        | 2.92%   |
| 0x20655    | 13        | 2.92%   |
| 0x406e3    | 12        | 2.7%    |
| 0x30678    | 12        | 2.7%    |
| 0x10676    | 11        | 2.47%   |
| 0x806ec    | 9         | 2.02%   |
| 0x406c3    | 9         | 2.02%   |
| 0x06006705 | 9         | 2.02%   |
| 0x05000119 | 9         | 2.02%   |
| 0x706a1    | 7         | 1.57%   |
| 0x106ca    | 7         | 1.57%   |
| 0x010000c8 | 7         | 1.57%   |
| 0x6fb      | 6         | 1.35%   |
| 0x6f6      | 6         | 1.35%   |
| 0x306d4    | 6         | 1.35%   |
| 0x20652    | 6         | 1.35%   |
| 0x06001119 | 6         | 1.35%   |
| 0x806e9    | 5         | 1.12%   |
| 0x806c1    | 5         | 1.12%   |
| 0x906ea    | 4         | 0.9%    |
| 0x906e9    | 4         | 0.9%    |
| 0x706a8    | 4         | 0.9%    |
| 0x30661    | 4         | 0.9%    |
| 0x806eb    | 3         | 0.67%   |
| 0x806ea    | 3         | 0.67%   |
| 0x10661    | 3         | 0.67%   |
| 0x08701021 | 3         | 0.67%   |
| 0x08600106 | 3         | 0.67%   |
| 0x0800820d | 3         | 0.67%   |
| 0x07030105 | 3         | 0.67%   |
| 0x0700010f | 3         | 0.67%   |
| 0x06000852 | 3         | 0.67%   |
| 0xa0653    | 2         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 40        | 9.09%   |
| Core            | 40        | 9.09%   |
| Penryn          | 39        | 8.86%   |
| Silvermont      | 37        | 8.41%   |
| Haswell         | 35        | 7.95%   |
| KabyLake        | 32        | 7.27%   |
| Westmere        | 23        | 5.23%   |
| IvyBridge       | 22        | 5%      |
| Skylake         | 17        | 3.86%   |
| K8 Hammer       | 17        | 3.86%   |
| K10             | 15        | 3.41%   |
| Zen 2           | 13        | 2.95%   |
| Bonnell         | 12        | 2.73%   |
| Goldmont plus   | 11        | 2.5%    |
| Bobcat          | 11        | 2.5%    |
| Zen+            | 10        | 2.27%   |
| Excavator       | 10        | 2.27%   |
| Piledriver      | 9         | 2.05%   |
| Broadwell       | 7         | 1.59%   |
| TigerLake       | 6         | 1.36%   |
| Puma            | 6         | 1.36%   |
| Jaguar          | 4         | 0.91%   |
| Icelake         | 4         | 0.91%   |
| Goldmont        | 4         | 0.91%   |
| CometLake       | 4         | 0.91%   |
| K8 & K10 hybrid | 3         | 0.68%   |
| Zen 3           | 2         | 0.45%   |
| Zen             | 2         | 0.45%   |
| NetBurst        | 2         | 0.45%   |
| Steamroller     | 1         | 0.23%   |
| Nehalem         | 1         | 0.23%   |
| K10 Llano       | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 268       | 55.26%  |
| AMD                              | 115       | 23.71%  |
| Nvidia                           | 96        | 19.79%  |
| Matrox Electronics Systems       | 5         | 1.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 6.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 4.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 3.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 3.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 2.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 15        | 2.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 2.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 2.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 2.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 2.14%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 10        | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 7         | 1.36%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.17%   |
| AMD Renoir                                                                               | 6         | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.17%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 5         | 0.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 0.97%   |
| Intel HD Graphics 5500                                                                   | 5         | 0.97%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.78%   |
| Intel HD Graphics 620                                                                    | 4         | 0.78%   |
| Intel HD Graphics 500                                                                    | 4         | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.78%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 0.78%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.78%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4         | 0.78%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4         | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.58%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 3         | 0.58%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3         | 0.58%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 228       | 51.7%   |
| 1 x AMD         | 95        | 21.54%  |
| 1 x Nvidia      | 66        | 14.97%  |
| Intel + Nvidia  | 25        | 5.67%   |
| Intel + AMD     | 13        | 2.95%   |
| 2 x AMD         | 5         | 1.13%   |
| 1 x Matrox      | 4         | 0.91%   |
| AMD + Nvidia    | 2         | 0.45%   |
| 2 x Nvidia      | 1         | 0.23%   |
| 1 x SiS         | 1         | 0.23%   |
| Nvidia + Matrox | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 389       | 88.01%  |
| Proprietary | 48        | 10.86%  |
| Unknown     | 5         | 1.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 252       | 56.88%  |
| 0.01-0.5   | 96        | 21.67%  |
| 0.51-1.0   | 40        | 9.03%   |
| 1.01-2.0   | 33        | 7.45%   |
| 3.01-4.0   | 13        | 2.93%   |
| 7.01-8.0   | 3         | 0.68%   |
| 2.01-3.0   | 3         | 0.68%   |
| 8.01-16.0  | 2         | 0.45%   |
| 5.01-6.0   | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 59        | 13.17%  |
| AU Optronics            | 53        | 11.83%  |
| LG Display              | 45        | 10.04%  |
| BOE                     | 37        | 8.26%   |
| Chimei Innolux          | 36        | 8.04%   |
| Dell                    | 28        | 6.25%   |
| Goldstar                | 20        | 4.46%   |
| Acer                    | 18        | 4.02%   |
| Hewlett-Packard         | 16        | 3.57%   |
| Lenovo                  | 13        | 2.9%    |
| Chi Mei Optoelectronics | 10        | 2.23%   |
| Philips                 | 8         | 1.79%   |
| Iiyama                  | 8         | 1.79%   |
| BenQ                    | 8         | 1.79%   |
| LG Philips              | 6         | 1.34%   |
| Apple                   | 6         | 1.34%   |
| Vizio                   | 5         | 1.12%   |
| AOC                     | 5         | 1.12%   |
| Sharp                   | 4         | 0.89%   |
| InfoVision              | 4         | 0.89%   |
| Ancor Communications    | 4         | 0.89%   |
| Unknown                 | 3         | 0.67%   |
| Sony                    | 3         | 0.67%   |
| PANDA                   | 3         | 0.67%   |
| NEC Computers           | 3         | 0.67%   |
| HannStar                | 3         | 0.67%   |
| LG Electronics          | 2         | 0.45%   |
| Lenovo Group Limited    | 2         | 0.45%   |
| KDC                     | 2         | 0.45%   |
| IOD                     | 2         | 0.45%   |
| InnoLux Display         | 2         | 0.45%   |
| FL_                     | 2         | 0.45%   |
| CVT                     | 2         | 0.45%   |
| CPT                     | 2         | 0.45%   |
| Compaq Computer         | 2         | 0.45%   |
| ___                     | 1         | 0.22%   |
| ViewSonic               | 1         | 0.22%   |
| Videoseven              | 1         | 0.22%   |
| Unknown (ADA)           | 1         | 0.22%   |
| SHD                     | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 1.1%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 3         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 3         | 0.66%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.66%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 3         | 0.66%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.66%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch        | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch     | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 2         | 0.44%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.44%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.44%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 2         | 0.44%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                 | 2         | 0.44%   |
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                    | 2         | 0.44%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 2         | 0.44%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch              | 2         | 0.44%   |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch                | 2         | 0.44%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                    | 2         | 0.44%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                         | 2         | 0.44%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                         | 2         | 0.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 2         | 0.44%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                        | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.44%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                     | 2         | 0.44%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.44%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.44%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 0.44%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                     | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 2         | 0.44%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 0.44%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 410x260mm 19.1-inch    | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 129       | 29.25%  |
| 1920x1080 (FHD)    | 125       | 28.34%  |
| 1280x1024 (SXGA)   | 31        | 7.03%   |
| 1280x800 (WXGA)    | 28        | 6.35%   |
| 1600x900 (HD+)     | 24        | 5.44%   |
| 1680x1050 (WSXGA+) | 23        | 5.22%   |
| 1440x900 (WXGA+)   | 16        | 3.63%   |
| 3840x2160 (4K)     | 15        | 3.4%    |
| 2560x1440 (QHD)    | 10        | 2.27%   |
| 1920x1200 (WUXGA)  | 10        | 2.27%   |
| 1024x768 (XGA)     | 7         | 1.59%   |
| 1024x600           | 5         | 1.13%   |
| 2560x1600          | 3         | 0.68%   |
| 3440x1440          | 2         | 0.45%   |
| 2560x1080          | 2         | 0.45%   |
| 1600x1200          | 2         | 0.45%   |
| 1360x768           | 2         | 0.45%   |
| 3840x2400          | 1         | 0.23%   |
| 3600x1200          | 1         | 0.23%   |
| 2288x1287          | 1         | 0.23%   |
| 2048x1152          | 1         | 0.23%   |
| 1280x768           | 1         | 0.23%   |
| 1280x720 (HD)      | 1         | 0.23%   |
| Unknown            | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 121       | 27.01%  |
| 13      | 43        | 9.6%    |
| 14      | 42        | 9.38%   |
| 17      | 40        | 8.93%   |
| 23      | 24        | 5.36%   |
| 21      | 19        | 4.24%   |
| 24      | 18        | 4.02%   |
| 19      | 18        | 4.02%   |
| 27      | 17        | 3.79%   |
| 11      | 16        | 3.57%   |
| Unknown | 15        | 3.35%   |
| 22      | 12        | 2.68%   |
| 20      | 12        | 2.68%   |
| 18      | 10        | 2.23%   |
| 10      | 8         | 1.79%   |
| 12      | 7         | 1.56%   |
| 84      | 3         | 0.67%   |
| 72      | 3         | 0.67%   |
| 34      | 3         | 0.67%   |
| 47      | 2         | 0.45%   |
| 39      | 2         | 0.45%   |
| 31      | 2         | 0.45%   |
| 52      | 1         | 0.22%   |
| 48      | 1         | 0.22%   |
| 41      | 1         | 0.22%   |
| 40      | 1         | 0.22%   |
| 38      | 1         | 0.22%   |
| 37      | 1         | 0.22%   |
| 33      | 1         | 0.22%   |
| 29      | 1         | 0.22%   |
| 26      | 1         | 0.22%   |
| 7       | 1         | 0.22%   |
| 5       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 200       | 45.05%  |
| 501-600     | 58        | 13.06%  |
| 401-500     | 58        | 13.06%  |
| 201-300     | 48        | 10.81%  |
| 351-400     | 39        | 8.78%   |
| Unknown     | 15        | 3.38%   |
| 1501-2000   | 6         | 1.35%   |
| 801-900     | 5         | 1.13%   |
| 701-800     | 4         | 0.9%    |
| 601-700     | 4         | 0.9%    |
| 1001-1500   | 4         | 0.9%    |
| 101-200     | 2         | 0.45%   |
| 901-1000    | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 292       | 69.86%  |
| 16/10   | 69        | 16.51%  |
| 5/4     | 28        | 6.7%    |
| Unknown | 12        | 2.87%   |
| 4/3     | 9         | 2.15%   |
| 21/9    | 4         | 0.96%   |
| 6/5     | 2         | 0.48%   |
| 3/2     | 2         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 119       | 26.74%  |
| 81-90          | 72        | 16.18%  |
| 201-250        | 62        | 13.93%  |
| 151-200        | 36        | 8.09%   |
| 141-150        | 23        | 5.17%   |
| 301-350        | 18        | 4.04%   |
| 121-130        | 17        | 3.82%   |
| 51-60          | 16        | 3.6%    |
| Unknown        | 15        | 3.37%   |
| 71-80          | 14        | 3.15%   |
| More than 1000 | 8         | 1.8%    |
| 41-50          | 8         | 1.8%    |
| 501-1000       | 8         | 1.8%    |
| 251-300        | 7         | 1.57%   |
| 61-70          | 6         | 1.35%   |
| 351-500        | 6         | 1.35%   |
| 131-140        | 6         | 1.35%   |
| 1-40           | 2         | 0.45%   |
| 111-120        | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 159       | 36.38%  |
| 101-120       | 152       | 34.78%  |
| 121-160       | 89        | 20.37%  |
| Unknown       | 15        | 3.43%   |
| 161-240       | 11        | 2.52%   |
| 1-50          | 7         | 1.6%    |
| More than 240 | 4         | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 382       | 86.04%  |
| 2     | 50        | 11.26%  |
| 0     | 8         | 1.8%    |
| 3     | 3         | 0.68%   |
| 4     | 1         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 246       | 36.77%  |
| Intel                             | 169       | 25.26%  |
| Qualcomm Atheros                  | 92        | 13.75%  |
| Broadcom                          | 48        | 7.17%   |
| Ralink Technology                 | 18        | 2.69%   |
| Nvidia                            | 18        | 2.69%   |
| Marvell Technology Group          | 18        | 2.69%   |
| Broadcom Limited                  | 13        | 1.94%   |
| Ralink                            | 8         | 1.2%    |
| TP-Link                           | 5         | 0.75%   |
| Samsung Electronics               | 4         | 0.6%    |
| ASIX Electronics                  | 4         | 0.6%    |
| NetGear                           | 2         | 0.3%    |
| Fibocom                           | 2         | 0.3%    |
| Ericsson Business Mobile Networks | 2         | 0.3%    |
| Dell                              | 2         | 0.3%    |
| Belkin Components                 | 2         | 0.3%    |
| Attansic Technology               | 2         | 0.3%    |
| ZyXEL Communications              | 1         | 0.15%   |
| Xiaomi                            | 1         | 0.15%   |
| VIA Technologies                  | 1         | 0.15%   |
| U-Blox                            | 1         | 0.15%   |
| Sitecom Europe                    | 1         | 0.15%   |
| Seeed                             | 1         | 0.15%   |
| Realtek                           | 1         | 0.15%   |
| QinHeng Electronics               | 1         | 0.15%   |
| MediaTek                          | 1         | 0.15%   |
| Logitec                           | 1         | 0.15%   |
| Huawei Technologies               | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| Aquantia                          | 1         | 0.15%   |
| ADMtek                            | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 142       | 18.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 49        | 6.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.81%   |
| Intel Wireless 7260                                                     | 14        | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 1.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 10        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 1.16%   |
| Nvidia MCP61 Ethernet                                                   | 9         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                         | 8         | 1.03%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.78%   |
| Intel Wireless 7265                                                     | 6         | 0.78%   |
| Intel Wireless 3165                                                     | 6         | 0.78%   |
| Intel Wireless 3160                                                     | 6         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 6         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.65%   |
| Intel Wireless 8260                                                     | 5         | 0.65%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.52%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.52%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 0.52%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 128       | 36.89%  |
| Qualcomm Atheros         | 76        | 21.9%   |
| Realtek Semiconductor    | 67        | 19.31%  |
| Broadcom                 | 28        | 8.07%   |
| Ralink Technology        | 18        | 5.19%   |
| Ralink                   | 8         | 2.31%   |
| TP-Link                  | 5         | 1.44%   |
| Broadcom Limited         | 5         | 1.44%   |
| NetGear                  | 2         | 0.58%   |
| Fibocom                  | 2         | 0.58%   |
| Belkin Components        | 2         | 0.58%   |
| ZyXEL Communications     | 1         | 0.29%   |
| Sitecom Europe           | 1         | 0.29%   |
| Realtek                  | 1         | 0.29%   |
| Marvell Technology Group | 1         | 0.29%   |
| Logitec                  | 1         | 0.29%   |
| Dell                     | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 5.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 4.01%   |
| Intel Wireless 7260                                                     | 14        | 4.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 3.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 3.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.58%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 2.58%   |
| Ralink MT7601U Wireless Adapter                                         | 8         | 2.29%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 2.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 2.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 2.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.72%   |
| Intel Wireless 7265                                                     | 6         | 1.72%   |
| Intel Wireless 3165                                                     | 6         | 1.72%   |
| Intel Wireless 3160                                                     | 6         | 1.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 1.72%   |
| Intel Wireless 8260                                                     | 5         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.43%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.15%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.15%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.15%   |
| Realtek RTL8187 Wireless Adapter                                        | 3         | 0.86%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.86%   |
| Ralink RT5572 Wireless Adapter                                          | 3         | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.86%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 3         | 0.86%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.86%   |
| Intel Wireless 8265 / 8275                                              | 3         | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 218       | 53.56%  |
| Intel                    | 75        | 18.43%  |
| Broadcom                 | 29        | 7.13%   |
| Qualcomm Atheros         | 27        | 6.63%   |
| Nvidia                   | 18        | 4.42%   |
| Marvell Technology Group | 17        | 4.18%   |
| Broadcom Limited         | 8         | 1.97%   |
| ASIX Electronics         | 4         | 0.98%   |
| Samsung Electronics      | 3         | 0.74%   |
| Attansic Technology      | 2         | 0.49%   |
| Xiaomi                   | 1         | 0.25%   |
| VIA Technologies         | 1         | 0.25%   |
| MediaTek                 | 1         | 0.25%   |
| Huawei Technologies      | 1         | 0.25%   |
| Aquantia                 | 1         | 0.25%   |
| ADMtek                   | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 142       | 34.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 49        | 11.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10        | 2.4%    |
| Nvidia MCP61 Ethernet                                             | 9         | 2.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 1.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.2%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.96%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.72%   |
| Nvidia MCP51 Ethernet Controller                                  | 3         | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.72%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 3         | 0.72%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 3         | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.48%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.48%   |
| Nvidia CK804 Ethernet Controller                                  | 2         | 0.48%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 394       | 53.68%  |
| WiFi     | 332       | 45.23%  |
| Modem    | 8         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 256       | 56.26%  |
| Ethernet | 199       | 43.74%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 247       | 56.14%  |
| 1     | 165       | 37.5%   |
| 0     | 17        | 3.86%   |
| 3     | 8         | 1.82%   |
| 4     | 3         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 366       | 81.88%  |
| Yes  | 81        | 18.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 41.23%  |
| Qualcomm Atheros Communications | 21        | 9.95%   |
| Broadcom                        | 19        | 9%      |
| Cambridge Silicon Radio         | 17        | 8.06%   |
| Realtek Semiconductor           | 16        | 7.58%   |
| Lite-On Technology              | 11        | 5.21%   |
| IMC Networks                    | 7         | 3.32%   |
| Apple                           | 6         | 2.84%   |
| Dell                            | 5         | 2.37%   |
| ASUSTek Computer                | 5         | 2.37%   |
| Hewlett-Packard                 | 4         | 1.9%    |
| Foxconn / Hon Hai               | 3         | 1.42%   |
| Toshiba                         | 2         | 0.95%   |
| Ralink Technology               | 2         | 0.95%   |
| Alps Electric                   | 2         | 0.95%   |
| TP-Link                         | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |
| Logitech                        | 1         | 0.47%   |
| Chicony Electronics             | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 43        | 20.38%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17        | 8.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 7.58%   |
| Realtek Bluetooth Radio                             | 11        | 5.21%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 5.21%   |
| Intel AX200 Bluetooth                               | 7         | 3.32%   |
| Intel AX201 Bluetooth                               | 6         | 2.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.9%    |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 1.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 1.9%    |
| IMC Networks Bluetooth Radio                        | 4         | 1.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.42%   |
| Apple Bluetooth Host Controller                     | 3         | 1.42%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.95%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.95%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 2         | 0.95%   |
| Lite-On Bluetooth Device                            | 2         | 0.95%   |
| IMC Networks Bluetooth Device                       | 2         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.95%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.95%   |
| Dell Wireless 365 Bluetooth                         | 2         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.95%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.95%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.95%   |
| ASUS ASUS USB-BT500                                 | 2         | 0.95%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.95%   |
| TP-Link UB500 Adapter                               | 1         | 0.47%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.47%   |
| Toshiba Bluetooth Radio                             | 1         | 0.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.47%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.47%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.47%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 303       | 58.49%  |
| AMD                               | 109       | 21.04%  |
| Nvidia                            | 76        | 14.67%  |
| C-Media Electronics               | 6         | 1.16%   |
| Creative Labs                     | 4         | 0.77%   |
| Logitech                          | 3         | 0.58%   |
| GN Netcom                         | 3         | 0.58%   |
| XMOS                              | 2         | 0.39%   |
| Texas Instruments                 | 2         | 0.39%   |
| VIA Technologies                  | 1         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.19%   |
| Setek Elektronik                  | 1         | 0.19%   |
| Scarlett                          | 1         | 0.19%   |
| Realtek Semiconductor             | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.19%   |
| Creative Technology               | 1         | 0.19%   |
| ASUSTek Computer                  | 1         | 0.19%   |
| Asahi Kasei Microsystems          | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 5.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 4.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 27        | 4.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 27        | 4.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 24        | 3.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 23        | 3.73%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 3.57%   |
| AMD FCH Azalia Controller                                                                         | 21        | 3.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.76%   |
| Nvidia High Definition Audio Controller                                                           | 14        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 2.27%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 2.27%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.62%   |
| AMD High Definition Audio Controller                                                              | 10        | 1.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 1.62%   |
| Nvidia MCP61 High Definition Audio                                                                | 9         | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.3%    |
| AMD Wrestler HDMI Audio                                                                           | 8         | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 0.97%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.97%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 6         | 0.97%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 0.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 0.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 0.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.65%   |
| Nvidia MCP51 High Definition Audio                                                                | 4         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 78        | 22.67%  |
| SK hynix            | 63        | 18.31%  |
| Unknown             | 57        | 16.57%  |
| Micron Technology   | 28        | 8.14%   |
| Kingston            | 19        | 5.52%   |
| Crucial             | 14        | 4.07%   |
| Nanya Technology    | 12        | 3.49%   |
| Corsair             | 10        | 2.91%   |
| G.Skill             | 9         | 2.62%   |
| A-DATA Technology   | 8         | 2.33%   |
| Unknown (ABCD)      | 7         | 2.03%   |
| Elpida              | 5         | 1.45%   |
| Smart               | 4         | 1.16%   |
| Patriot             | 4         | 1.16%   |
| Team                | 3         | 0.87%   |
| PNY                 | 3         | 0.87%   |
| Timetec             | 2         | 0.58%   |
| Ramaxel Technology  | 2         | 0.58%   |
| Qimonda             | 2         | 0.58%   |
| Unifosa             | 1         | 0.29%   |
| Transcend           | 1         | 0.29%   |
| Teikon              | 1         | 0.29%   |
| Sesame              | 1         | 0.29%   |
| Multilaser          | 1         | 0.29%   |
| GOODRAM             | 1         | 0.29%   |
| Goldkey             | 1         | 0.29%   |
| Goldenmars          | 1         | 0.29%   |
| e2e4                | 1         | 0.29%   |
| Digiboard           | 1         | 0.29%   |
| Avant               | 1         | 0.29%   |
| ASint Technology    | 1         | 0.29%   |
| Apacer              | 1         | 0.29%   |
| 48spaces            | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 5         | 1.36%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 5         | 1.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.36%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 1.36%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 1.09%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 4         | 1.09%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 3         | 0.82%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 3         | 0.82%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.82%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.82%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 3         | 0.82%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.82%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                   | 2         | 0.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 2         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 2         | 0.54%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 2         | 0.54%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 2         | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.54%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 2         | 0.54%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                    | 2         | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.54%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 2         | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.54%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.54%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s           | 2         | 0.54%   |
| PNY RAM Module 8192MB SODIMM DDR3 1600MT/s                       | 2         | 0.54%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.54%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s               | 2         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 136       | 45.48%  |
| DDR4    | 75        | 25.08%  |
| DDR2    | 39        | 13.04%  |
| SDRAM   | 19        | 6.35%   |
| LPDDR4  | 11        | 3.68%   |
| Unknown | 10        | 3.34%   |
| LPDDR3  | 6         | 2.01%   |
| DDR     | 3         | 1%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 190       | 65.07%  |
| DIMM         | 93        | 31.85%  |
| Row Of Chips | 7         | 2.4%    |
| Chip         | 1         | 0.34%   |
| Unknown      | 1         | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 103       | 31.31%  |
| 8192  | 85        | 25.84%  |
| 2048  | 85        | 25.84%  |
| 1024  | 31        | 9.42%   |
| 16384 | 17        | 5.17%   |
| 32768 | 4         | 1.22%   |
| 512   | 3         | 0.91%   |
| 65536 | 1         | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 77        | 23.62%  |
| 2400    | 28        | 8.59%   |
| 1333    | 27        | 8.28%   |
| 2667    | 24        | 7.36%   |
| 1334    | 24        | 7.36%   |
| 667     | 20        | 6.13%   |
| 3200    | 19        | 5.83%   |
| 800     | 17        | 5.21%   |
| 2133    | 14        | 4.29%   |
| 2048    | 9         | 2.76%   |
| 1867    | 9         | 2.76%   |
| 1066    | 9         | 2.76%   |
| Unknown | 8         | 2.45%   |
| 533     | 6         | 1.84%   |
| 400     | 6         | 1.84%   |
| 1866    | 5         | 1.53%   |
| 3266    | 3         | 0.92%   |
| 1067    | 3         | 0.92%   |
| 3600    | 2         | 0.61%   |
| 3000    | 2         | 0.61%   |
| 1639    | 2         | 0.61%   |
| 49926   | 1         | 0.31%   |
| 8400    | 1         | 0.31%   |
| 4267    | 1         | 0.31%   |
| 3933    | 1         | 0.31%   |
| 3866    | 1         | 0.31%   |
| 3066    | 1         | 0.31%   |
| 2933    | 1         | 0.31%   |
| 2733    | 1         | 0.31%   |
| 1200    | 1         | 0.31%   |
| 333     | 1         | 0.31%   |
| 2       | 1         | 0.31%   |
| 1       | 1         | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Brother Industries  | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |
| Dymo-CoStar         | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SCX-4200 series                | 1         | 14.29%  |
| HP DeskJet 3630 series                 | 1         | 14.29%  |
| HP Deskjet 3520 series                 | 1         | 14.29%  |
| HP Deskjet 1050 J410                   | 1         | 14.29%  |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 14.29%  |
| Brother PTUSB Printing                 | 1         | 14.29%  |
| Brother DCP-7055W                      | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 50%     |
| HP scanjet 8270                                               | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 26.48%  |
| Realtek Semiconductor                  | 20        | 7.91%   |
| IMC Networks                           | 17        | 6.72%   |
| Microdia                               | 15        | 5.93%   |
| Acer                                   | 11        | 4.35%   |
| Sunplus Innovation Technology          | 10        | 3.95%   |
| Bison Electronics                      | 10        | 3.95%   |
| Alcor Micro                            | 10        | 3.95%   |
| Suyin                                  | 9         | 3.56%   |
| Quanta                                 | 9         | 3.56%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.16%   |
| Silicon Motion                         | 6         | 2.37%   |
| Logitech                               | 5         | 1.98%   |
| Lite-On Technology                     | 5         | 1.98%   |
| Apple                                  | 5         | 1.98%   |
| Ricoh                                  | 4         | 1.58%   |
| Luxvisions Innotech Limited            | 4         | 1.58%   |
| Lenovo                                 | 4         | 1.58%   |
| Z-Star Microelectronics                | 3         | 1.19%   |
| Syntek                                 | 3         | 1.19%   |
| Samsung Electronics                    | 3         | 1.19%   |
| Importek                               | 3         | 1.19%   |
| Generalplus Technology                 | 3         | 1.19%   |
| ALi                                    | 3         | 1.19%   |
| Sunplus IT                             | 2         | 0.79%   |
| Y Media                                | 1         | 0.4%    |
| WCM_USB                                | 1         | 0.4%    |
| OmniVision Technologies                | 1         | 0.4%    |
| Nintendo                               | 1         | 0.4%    |
| Microsoft                              | 1         | 0.4%    |
| LG Electronics                         | 1         | 0.4%    |
| KYE Systems (Mouse Systems)            | 1         | 0.4%    |
| HYGD-220628-A                          | 1         | 0.4%    |
| HD USB Camera                          | 1         | 0.4%    |
| Guillemot                              | 1         | 0.4%    |
| Genesys Logic                          | 1         | 0.4%    |
| GEMBIRD                                | 1         | 0.4%    |
| DigiTech                               | 1         | 0.4%    |
| ARC International                      | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 9         | 3.53%   |
| Realtek Integrated_Webcam_HD                         | 7         | 2.75%   |
| Chicony TOSHIBA Web Camera - HD                      | 6         | 2.35%   |
| Alcor Micro USB 2.0 Camera                           | 6         | 2.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 4         | 1.57%   |
| Chicony HP HD Camera                                 | 4         | 1.57%   |
| Samsung Galaxy A5 (MTP)                              | 3         | 1.18%   |
| Realtek Integrated Webcam                            | 3         | 1.18%   |
| Quanta HP HD Camera                                  | 3         | 1.18%   |
| Luxvisions Innotech Limited HP HD Camera             | 3         | 1.18%   |
| Lite-On HP HD Camera                                 | 3         | 1.18%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 3         | 1.18%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 3         | 1.18%   |
| Chicony USB 2.0 Camera                               | 3         | 1.18%   |
| Chicony HD WebCam (Acer)                             | 3         | 1.18%   |
| Chicony HD WebCam                                    | 3         | 1.18%   |
| Chicony EasyCamera                                   | 3         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 3         | 1.18%   |
| Bison VGA WebCam                                     | 3         | 1.18%   |
| Apple FaceTime HD Camera                             | 3         | 1.18%   |
| Alcor Micro Asus Integrated Webcam                   | 3         | 1.18%   |
| Acer Lenovo EasyCamera                               | 3         | 1.18%   |
| Acer HD WebCam                                       | 3         | 1.18%   |
| Sunplus IT 1080P Webcam                              | 2         | 0.78%   |
| Sunplus Laptop Integrated Webcam HD                  | 2         | 0.78%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 0.78%   |
| Sunplus HD WebCam                                    | 2         | 0.78%   |
| Realtek Lenovo EasyCamera                            | 2         | 0.78%   |
| Realtek 2SF022                                       | 2         | 0.78%   |
| Quanta VGA WebCam                                    | 2         | 0.78%   |
| Quanta HP Webcam                                     | 2         | 0.78%   |
| Microdia Sonix USB 2.0 Camera                        | 2         | 0.78%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 2         | 0.78%   |
| Microdia Integrated Webcam                           | 2         | 0.78%   |
| Microdia 1.3 MPixel Integrated Webcam                | 2         | 0.78%   |
| Logitech Webcam C270                                 | 2         | 0.78%   |
| Lenovo Integrated Webcam                             | 2         | 0.78%   |
| Importek TOSHIBA Web Camera - HD                     | 2         | 0.78%   |
| IMC Networks USB 2.0 UVC VGA WebCam                  | 2         | 0.78%   |
| IMC Networks Integrated Camera                       | 2         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 37.5%   |
| AuthenTec                  | 8         | 25%     |
| Synaptics                  | 3         | 9.38%   |
| Shenzhen Goodix Technology | 3         | 9.38%   |
| Upek                       | 2         | 6.25%   |
| STMicroelectronics         | 2         | 6.25%   |
| LighTuning Technology      | 1         | 3.13%   |
| Elan Microelectronics      | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                       | 3         | 9.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 6.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.25%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 6.25%   |
| AuthenTec AES2810                                          | 2         | 6.25%   |
| AuthenTec AES1600                                          | 2         | 6.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 3.13%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 3.13%   |
| Validity Sensors VFS491                                    | 1         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 3.13%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 3.13%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 3.13%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 3.13%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.13%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.13%   |
| Shenzhen Goodix FingerPrint                                | 1         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.13%   |
| Elan ELAN:Fingerprint                                      | 1         | 3.13%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 40%     |
| O2 Micro    | 3         | 30%     |
| Broadcom    | 2         | 20%     |
| Upek        | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 30%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 353       | 79.5%   |
| 1     | 74        | 16.67%  |
| 2     | 16        | 3.6%    |
| 3     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 32        | 30.77%  |
| Graphics card            | 20        | 19.23%  |
| Net/wireless             | 16        | 15.38%  |
| Chipcard                 | 10        | 9.62%   |
| Communication controller | 5         | 4.81%   |
| Unassigned class         | 3         | 2.88%   |
| Sound                    | 3         | 2.88%   |
| Multimedia controller    | 3         | 2.88%   |
| Camera                   | 3         | 2.88%   |
| Storage                  | 2         | 1.92%   |
| Net/ethernet             | 2         | 1.92%   |
| Dvb card                 | 2         | 1.92%   |
| Bluetooth                | 2         | 1.92%   |
| Flash memory             | 1         | 0.96%   |

