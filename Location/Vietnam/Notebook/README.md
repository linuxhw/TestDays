Linux in Vietnam - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Vietnam.

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

Total: 390

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T430 2349A17       | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e09dc41124](https://linux-hardware.org/?probe=e09dc41124) | Mar 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| Chuwi         | CoreBook X                  | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| Acer          | Aspire A715-42G             | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Dell          | Latitude 7290               | [576b8aa32a](https://linux-hardware.org/?probe=576b8aa32a) | Mar 13, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [315750ea63](https://linux-hardware.org/?probe=315750ea63) | Mar 11, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [c45a0f2220](https://linux-hardware.org/?probe=c45a0f2220) | Mar 11, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| Acer          | Nitro AN515-58              | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [3cec8a7abc](https://linux-hardware.org/?probe=3cec8a7abc) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [219f16372b](https://linux-hardware.org/?probe=219f16372b) | Mar 03, 2023 |
| Samsung       | 930XDA                      | [684b448b3a](https://linux-hardware.org/?probe=684b448b3a) | Mar 03, 2023 |
| Dell          | Latitude E6510              | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [4ead3fc236](https://linux-hardware.org/?probe=4ead3fc236) | Mar 03, 2023 |
| Dell          | Latitude 3400               | [2936e7f368](https://linux-hardware.org/?probe=2936e7f368) | Feb 28, 2023 |
| Dell          | Precision M4600             | [901a8de667](https://linux-hardware.org/?probe=901a8de667) | Feb 24, 2023 |
| Dell          | Precision M4600             | [2bdbf753b0](https://linux-hardware.org/?probe=2bdbf753b0) | Feb 21, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [12bb4f91ae](https://linux-hardware.org/?probe=12bb4f91ae) | Feb 20, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [a4404180b7](https://linux-hardware.org/?probe=a4404180b7) | Feb 20, 2023 |
| HP            | 245 G8 Notebook PC          | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| HP            | 245 G8 Notebook PC          | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| Dell          | Inspiron 3558               | [420ccdfca6](https://linux-hardware.org/?probe=420ccdfca6) | Feb 07, 2023 |
| Apple         | MacBookPro11,4              | [cfcea0a331](https://linux-hardware.org/?probe=cfcea0a331) | Feb 05, 2023 |
| MSI           | Modern 14 B11SBU            | [50538fe8fd](https://linux-hardware.org/?probe=50538fe8fd) | Feb 05, 2023 |
| Dell          | Inspiron 3585               | [8da4ffdd5c](https://linux-hardware.org/?probe=8da4ffdd5c) | Feb 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b660fd4859](https://linux-hardware.org/?probe=b660fd4859) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Acer          | Aspire A715-42G             | [a169951063](https://linux-hardware.org/?probe=a169951063) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | [45890fca78](https://linux-hardware.org/?probe=45890fca78) | Feb 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S3PV00    | [08f4e80cb9](https://linux-hardware.org/?probe=08f4e80cb9) | Feb 02, 2023 |
| Timi          | RedmiBook Pro 15S           | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| Acer          | Aspire A715-42G             | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Lenovo        | ThinkPad T470s 20HF0015U... | [1ece644fe1](https://linux-hardware.org/?probe=1ece644fe1) | Jan 04, 2023 |
| Dell          | Precision 3560              | [8cb8a3f5cf](https://linux-hardware.org/?probe=8cb8a3f5cf) | Jan 04, 2023 |
| Anbernic      | Win600                      | [db576ded28](https://linux-hardware.org/?probe=db576ded28) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c82ebf8b80](https://linux-hardware.org/?probe=c82ebf8b80) | Dec 26, 2022 |
| Anbernic      | Win600                      | [f7759a13d8](https://linux-hardware.org/?probe=f7759a13d8) | Dec 25, 2022 |
| Dell          | Latitude E6440              | [3b6ac9ce59](https://linux-hardware.org/?probe=3b6ac9ce59) | Dec 19, 2022 |
| Lenovo        | ThinkPad T470s 20HF0015U... | [3fd30db5e1](https://linux-hardware.org/?probe=3fd30db5e1) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [f82368713d](https://linux-hardware.org/?probe=f82368713d) | Dec 17, 2022 |
| Dell          | Inspiron 5502               | [66635e6315](https://linux-hardware.org/?probe=66635e6315) | Dec 16, 2022 |
| HP            | 350 G1                      | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Dell          | Latitude E7240              | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Dell          | Latitude 7390               | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [33113bb27d](https://linux-hardware.org/?probe=33113bb27d) | Nov 17, 2022 |
| Dell          | Vostro 5490                 | [b19387a8f3](https://linux-hardware.org/?probe=b19387a8f3) | Nov 16, 2022 |
| Apple         | MacBookPro11,4              | [91268b9919](https://linux-hardware.org/?probe=91268b9919) | Nov 16, 2022 |
| Dell          | Latitude E6530              | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [4b0ce24e6e](https://linux-hardware.org/?probe=4b0ce24e6e) | Nov 11, 2022 |
| Google        | Drallion                    | [7cb5922896](https://linux-hardware.org/?probe=7cb5922896) | Nov 10, 2022 |
| Dell          | G15 5511                    | [8a3246caed](https://linux-hardware.org/?probe=8a3246caed) | Nov 10, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [86f71fb0e6](https://linux-hardware.org/?probe=86f71fb0e6) | Nov 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| Acer          | Aspire 4739Z                | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Dell          | Inspiron 13 5310            | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Vostro 3500                 | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [403aa5af3e](https://linux-hardware.org/?probe=403aa5af3e) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Lenovo        | ThinkPad T450s 20BX005GU... | [5c41d03119](https://linux-hardware.org/?probe=5c41d03119) | Sep 15, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [c07c5b31f6](https://linux-hardware.org/?probe=c07c5b31f6) | Sep 13, 2022 |
| Dell          | XPS 17 9710                 | [4b728bc447](https://linux-hardware.org/?probe=4b728bc447) | Sep 12, 2022 |
| Acer          | Aspire E5-575               | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Dell          | Latitude E5540              | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| ASUSTek       | GL552VX                     | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Lenovo        | ThinkPad P50 20EQS4QM00     | [9779cc7396](https://linux-hardware.org/?probe=9779cc7396) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| ASUSTek       | K55A                        | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Dell          | G3 3500                     | [69f594bb80](https://linux-hardware.org/?probe=69f594bb80) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| Toshiba       | dynabook Satellite B35/R    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| TENKU         | SB14                        | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6eb841aab1](https://linux-hardware.org/?probe=6eb841aab1) | Jun 21, 2022 |
| Acer          | Aspire 5738                 | [58b312c382](https://linux-hardware.org/?probe=58b312c382) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [a8c7fc9c3a](https://linux-hardware.org/?probe=a8c7fc9c3a) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| MSI           | Bravo 15 B5DD               | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [63bc3a2ce5](https://linux-hardware.org/?probe=63bc3a2ce5) | May 27, 2022 |
| Acer          | Aspire A315-57G             | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [9df127ec26](https://linux-hardware.org/?probe=9df127ec26) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb2ffeb78a](https://linux-hardware.org/?probe=bb2ffeb78a) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb73f6aa37](https://linux-hardware.org/?probe=bb73f6aa37) | May 04, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [51625474b7](https://linux-hardware.org/?probe=51625474b7) | Apr 30, 2022 |
| ASUSTek       | E402SA                      | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Dell          | Inspiron 3537               | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| MSI           | GF63 8RD                    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| HP            | EliteBook 840 G5            | [7499dbd303](https://linux-hardware.org/?probe=7499dbd303) | Apr 15, 2022 |
| Dell          | System Vostro 3450          | [78750d86f5](https://linux-hardware.org/?probe=78750d86f5) | Mar 19, 2022 |
| Dell          | Vostro 3400                 | [5dcc8e2cee](https://linux-hardware.org/?probe=5dcc8e2cee) | Mar 14, 2022 |
| Dell          | Latitude E5540              | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| Dell          | System XPS L702X            | [e1d4821ec2](https://linux-hardware.org/?probe=e1d4821ec2) | Feb 19, 2022 |
| Dell          | Inspiron N4050              | [0619812e27](https://linux-hardware.org/?probe=0619812e27) | Feb 11, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [4834a3fe2e](https://linux-hardware.org/?probe=4834a3fe2e) | Feb 09, 2022 |
| Dell          | G3 3500                     | [9001ccacbc](https://linux-hardware.org/?probe=9001ccacbc) | Feb 09, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [2621c151ec](https://linux-hardware.org/?probe=2621c151ec) | Feb 01, 2022 |
| Dell          | Vostro 3578                 | [a95dfa8bc8](https://linux-hardware.org/?probe=a95dfa8bc8) | Jan 26, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | [872bc057f0](https://linux-hardware.org/?probe=872bc057f0) | Jan 10, 2022 |
| HP            | EliteBook 840 G2            | [5588a84fcf](https://linux-hardware.org/?probe=5588a84fcf) | Jan 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [d65648c445](https://linux-hardware.org/?probe=d65648c445) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | [3b97b65258](https://linux-hardware.org/?probe=3b97b65258) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [65c9a87d51](https://linux-hardware.org/?probe=65c9a87d51) | Jan 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [48cfc7d185](https://linux-hardware.org/?probe=48cfc7d185) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [b64750f465](https://linux-hardware.org/?probe=b64750f465) | Dec 26, 2021 |
| Dell          | XPS 15 9500                 | [717b9f1dd0](https://linux-hardware.org/?probe=717b9f1dd0) | Dec 16, 2021 |
| Apple         | MacBookPro9,2               | [21d85302a2](https://linux-hardware.org/?probe=21d85302a2) | Dec 05, 2021 |
| Dell          | Vostro 3500                 | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [70c63b2fb6](https://linux-hardware.org/?probe=70c63b2fb6) | Dec 02, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [c5d4bf5c62](https://linux-hardware.org/?probe=c5d4bf5c62) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| Timi          | A35S                        | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| HP            | Laptop 15s-du1xxx           | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Dell          | XPS 15 9500                 | [10455f4980](https://linux-hardware.org/?probe=10455f4980) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [17781cb457](https://linux-hardware.org/?probe=17781cb457) | Nov 20, 2021 |
| ASUSTek       | X550LD                      | [f4a646d1f8](https://linux-hardware.org/?probe=f4a646d1f8) | Nov 18, 2021 |
| HP            | EliteBook 840 G5            | [5471ce2e2f](https://linux-hardware.org/?probe=5471ce2e2f) | Nov 16, 2021 |
| HP            | EliteBook 8470p             | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| Dell          | Inspiron 5420               | [a471ac5d59](https://linux-hardware.org/?probe=a471ac5d59) | Nov 07, 2021 |
| Dell          | Vostro 3478                 | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Dell          | Precision 7510              | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| HP            | ZBook Firefly 14 inch G8... | [603ccdfb84](https://linux-hardware.org/?probe=603ccdfb84) | Oct 19, 2021 |
| Dell          | Precision 7510              | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| HP            | Notebook                    | [6ac2c09585](https://linux-hardware.org/?probe=6ac2c09585) | Oct 09, 2021 |
| HP            | Laptop 15-bs1xx             | [c9fd6887d4](https://linux-hardware.org/?probe=c9fd6887d4) | Oct 06, 2021 |
| Acer          | Predator PH315-51           | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b1fb3d4e88](https://linux-hardware.org/?probe=b1fb3d4e88) | Oct 04, 2021 |
| Dell          | Latitude E7440              | [fe4153e816](https://linux-hardware.org/?probe=fe4153e816) | Oct 04, 2021 |
| HP            | EliteBook Folio 9470m       | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| Dell          | XPS 13 9350                 | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [52fe5aa259](https://linux-hardware.org/?probe=52fe5aa259) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [d8cde7951e](https://linux-hardware.org/?probe=d8cde7951e) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [db7c214214](https://linux-hardware.org/?probe=db7c214214) | Sep 28, 2021 |
| Dell          | Latitude 3520               | [2fb41f5f08](https://linux-hardware.org/?probe=2fb41f5f08) | Sep 24, 2021 |
| HP            | 15                          | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Sony          | SVE14A15FGW                 | [f1049f7db1](https://linux-hardware.org/?probe=f1049f7db1) | Sep 21, 2021 |
| Panasonic     | CFSX4-1                     | [d474bc1b91](https://linux-hardware.org/?probe=d474bc1b91) | Sep 03, 2021 |
| Panasonic     | CFSX4-1                     | [bee71431a0](https://linux-hardware.org/?probe=bee71431a0) | Sep 03, 2021 |
| HP            | Laptop 15s-fq2xxx           | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | GF62 7RD                    | [5a35b145a9](https://linux-hardware.org/?probe=5a35b145a9) | Aug 19, 2021 |
| MSI           | GE66 Raider 11UH            | [df3d4bfff1](https://linux-hardware.org/?probe=df3d4bfff1) | Aug 18, 2021 |
| MSI           | GE66 Raider 11UH            | [dde539e1b1](https://linux-hardware.org/?probe=dde539e1b1) | Aug 18, 2021 |
| HP            | ProBook 4430s               | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| HP            | EliteBook 745 G6            | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f77c5c4c48](https://linux-hardware.org/?probe=f77c5c4c48) | Aug 10, 2021 |
| Dell          | Inspiron 5502               | [57bf64ac4b](https://linux-hardware.org/?probe=57bf64ac4b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| Acer          | Aspire E5-572G              | [76e0c19c46](https://linux-hardware.org/?probe=76e0c19c46) | Aug 02, 2021 |
| Dell          | Vostro 15-3568              | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Dell          | Vostro 5568                 | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Vostro 15-3568              | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | [e6cb486cfd](https://linux-hardware.org/?probe=e6cb486cfd) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | [58ad5d25b9](https://linux-hardware.org/?probe=58ad5d25b9) | Jul 07, 2021 |
| Dell          | Latitude E6410              | [9a4002aa3d](https://linux-hardware.org/?probe=9a4002aa3d) | Jul 07, 2021 |
| HP            | Compaq 510                  | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| Dell          | Vostro 5568                 | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| ASUSTek       | K46CA                       | [85b912e99c](https://linux-hardware.org/?probe=85b912e99c) | Jun 22, 2021 |
| Acer          | Aspire 4315                 | [ac56c24f68](https://linux-hardware.org/?probe=ac56c24f68) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | [4527ee70c7](https://linux-hardware.org/?probe=4527ee70c7) | Jun 13, 2021 |
| Lenovo        | ThinkPad L520 5015A76       | [84b62cbde9](https://linux-hardware.org/?probe=84b62cbde9) | Jun 10, 2021 |
| Dell          | Vostro 15-3568              | [de3596a9a3](https://linux-hardware.org/?probe=de3596a9a3) | Jun 05, 2021 |
| Dell          | Latitude 7420               | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| Lenovo        | V130-14IKB 81HQ             | [8995f3c1ad](https://linux-hardware.org/?probe=8995f3c1ad) | Jun 01, 2021 |
| Lenovo        | Z40-70 20366                | [b1b8196f26](https://linux-hardware.org/?probe=b1b8196f26) | May 31, 2021 |
| Lenovo        | ThinkPad X250 20CLCTO1WW    | [a5d677976f](https://linux-hardware.org/?probe=a5d677976f) | May 29, 2021 |
| Acer          | Swift SF314-59              | [b70a62225d](https://linux-hardware.org/?probe=b70a62225d) | May 22, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [ddfb904938](https://linux-hardware.org/?probe=ddfb904938) | May 19, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [35324d2388](https://linux-hardware.org/?probe=35324d2388) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1abefab68f](https://linux-hardware.org/?probe=1abefab68f) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c4ea8f1bab](https://linux-hardware.org/?probe=c4ea8f1bab) | May 19, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2ce7106efb](https://linux-hardware.org/?probe=2ce7106efb) | May 15, 2021 |
| HP            | ProBook 450 G4              | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| Dell          | Inspiron 3443               | [c84fc5c646](https://linux-hardware.org/?probe=c84fc5c646) | May 12, 2021 |
| Acer          | Predator G9-793             | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| HP            | Pavilion 15                 | [1ddb966308](https://linux-hardware.org/?probe=1ddb966308) | Apr 28, 2021 |
| Sony          | VPCCW13FX                   | [82e9a1f82a](https://linux-hardware.org/?probe=82e9a1f82a) | Apr 25, 2021 |
| Dell          | Precision 3520              | [fc2d295c0e](https://linux-hardware.org/?probe=fc2d295c0e) | Apr 24, 2021 |
| HP            | ProBook 445 G7              | [76defcf2f7](https://linux-hardware.org/?probe=76defcf2f7) | Apr 22, 2021 |
| MSI           | Prestige 15 A11SCX          | [007ae7cca0](https://linux-hardware.org/?probe=007ae7cca0) | Apr 18, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [07736896f9](https://linux-hardware.org/?probe=07736896f9) | Apr 18, 2021 |
| HP            | Unknown                     | [2465109965](https://linux-hardware.org/?probe=2465109965) | Apr 13, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [698d0ca8cc](https://linux-hardware.org/?probe=698d0ca8cc) | Apr 08, 2021 |
| Dell          | G3 3579                     | [d5d191947e](https://linux-hardware.org/?probe=d5d191947e) | Apr 06, 2021 |
| Dell          | G3 3579                     | [07fd740efe](https://linux-hardware.org/?probe=07fd740efe) | Apr 06, 2021 |
| Chuwi         | LapBook SE                  | [0e9a03cc48](https://linux-hardware.org/?probe=0e9a03cc48) | Apr 06, 2021 |
| MSI           | Prestige 15 A11SCX          | [d20d2b755f](https://linux-hardware.org/?probe=d20d2b755f) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | [e8c59a070a](https://linux-hardware.org/?probe=e8c59a070a) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | [b9324b1b4d](https://linux-hardware.org/?probe=b9324b1b4d) | Apr 04, 2021 |
| Gigabyte      | AERO 15-X9                  | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| MSI           | GS40 6QE Phantom            | [adbf080ab7](https://linux-hardware.org/?probe=adbf080ab7) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| Acer          | Aspire A315-42              | [43f33bc8e0](https://linux-hardware.org/?probe=43f33bc8e0) | Mar 21, 2021 |
| Acer          | Aspire A315-42              | [c377f57ac8](https://linux-hardware.org/?probe=c377f57ac8) | Mar 21, 2021 |
| Dell          | XPS 15 9500                 | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| Dell          | Inspiron 3537               | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| Dell          | Vostro 3460                 | [a8e1128b26](https://linux-hardware.org/?probe=a8e1128b26) | Mar 13, 2021 |
| Dell          | Inspiron 3537               | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| ASUSTek       | X202E                       | [cc089d4ddb](https://linux-hardware.org/?probe=cc089d4ddb) | Mar 08, 2021 |
| Dell          | XPS 15 9500                 | [647b5fbb43](https://linux-hardware.org/?probe=647b5fbb43) | Mar 06, 2021 |
| Acer          | Aspire A515-53              | [637c3ebf75](https://linux-hardware.org/?probe=637c3ebf75) | Feb 28, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [05ad71d3d8](https://linux-hardware.org/?probe=05ad71d3d8) | Feb 24, 2021 |
| Gateway       | LT40                        | [90ae93da93](https://linux-hardware.org/?probe=90ae93da93) | Feb 24, 2021 |
| Gateway       | LT40                        | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| Acer          | Aspire E5-572G              | [4a441fe0c9](https://linux-hardware.org/?probe=4a441fe0c9) | Feb 21, 2021 |
| Acer          | Aspire A315-42              | [bfb791c2fb](https://linux-hardware.org/?probe=bfb791c2fb) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| Dell          | Inspiron 5570               | [a79c837a9b](https://linux-hardware.org/?probe=a79c837a9b) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | [5cb0f77327](https://linux-hardware.org/?probe=5cb0f77327) | Feb 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0c70deaac1](https://linux-hardware.org/?probe=0c70deaac1) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0441228ba8](https://linux-hardware.org/?probe=0441228ba8) | Feb 07, 2021 |
| Dell          | Latitude E7450              | [94b0fc1fc8](https://linux-hardware.org/?probe=94b0fc1fc8) | Feb 06, 2021 |
| Acer          | Swift SF315-52              | [b2b00b4390](https://linux-hardware.org/?probe=b2b00b4390) | Jan 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d7f2ee4a81](https://linux-hardware.org/?probe=d7f2ee4a81) | Jan 25, 2021 |
| Toshiba       | Satellite L840              | [82f5ebd486](https://linux-hardware.org/?probe=82f5ebd486) | Jan 18, 2021 |
| ASUSTek       | X550CC                      | [6eaddc8157](https://linux-hardware.org/?probe=6eaddc8157) | Dec 21, 2020 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [fb16534a29](https://linux-hardware.org/?probe=fb16534a29) | Dec 17, 2020 |
| Sony          | VGN-NW270F                  | [d8989e5c40](https://linux-hardware.org/?probe=d8989e5c40) | Dec 16, 2020 |
| Apple         | MacBookPro11,4              | [e880800d6f](https://linux-hardware.org/?probe=e880800d6f) | Dec 13, 2020 |
| Dell          | G3 3579                     | [99724b8bd6](https://linux-hardware.org/?probe=99724b8bd6) | Dec 12, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fa10ea29e8](https://linux-hardware.org/?probe=fa10ea29e8) | Dec 11, 2020 |
| Acer          | Predator PH315-51           | [c9539f5932](https://linux-hardware.org/?probe=c9539f5932) | Dec 09, 2020 |
| HP            | EliteBook 840 G2            | [ea2bf23a76](https://linux-hardware.org/?probe=ea2bf23a76) | Dec 03, 2020 |
| HP            | Compaq Presario CQ45        | [2a4ce919e5](https://linux-hardware.org/?probe=2a4ce919e5) | Dec 03, 2020 |
| Acer          | Aspire V5-431P              | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | [4e39668b71](https://linux-hardware.org/?probe=4e39668b71) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | [dbff453f7e](https://linux-hardware.org/?probe=dbff453f7e) | Dec 02, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [80f3a03fc2](https://linux-hardware.org/?probe=80f3a03fc2) | Nov 22, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [471b375bb8](https://linux-hardware.org/?probe=471b375bb8) | Nov 22, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Dell          | XPS 15 9570                 | [7fb140838e](https://linux-hardware.org/?probe=7fb140838e) | Nov 12, 2020 |
| Dell          | XPS 15 9570                 | [ac263c6ad6](https://linux-hardware.org/?probe=ac263c6ad6) | Nov 10, 2020 |
| HP            | Compaq Presario CQ45        | [f2a745943a](https://linux-hardware.org/?probe=f2a745943a) | Nov 04, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [bfa10fd887](https://linux-hardware.org/?probe=bfa10fd887) | Nov 04, 2020 |
| Dell          | Latitude 7490               | [8f0ec25c05](https://linux-hardware.org/?probe=8f0ec25c05) | Oct 29, 2020 |
| Dell          | Latitude E6530              | [1a16aeb4dd](https://linux-hardware.org/?probe=1a16aeb4dd) | Oct 28, 2020 |
| HP            | EliteBook 840 G2            | [070dae158a](https://linux-hardware.org/?probe=070dae158a) | Oct 24, 2020 |
| Toshiba       | Satellite L840              | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | [fa061b6d7e](https://linux-hardware.org/?probe=fa061b6d7e) | Oct 13, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | [dc9b667685](https://linux-hardware.org/?probe=dc9b667685) | Oct 13, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| HP            | EliteBook 840 G5            | [125dd87b84](https://linux-hardware.org/?probe=125dd87b84) | Oct 03, 2020 |
| Acer          | Aspire E5-575G              | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Lenovo        | ThinkPad T420 4236C95       | [8cf52f76c0](https://linux-hardware.org/?probe=8cf52f76c0) | Oct 02, 2020 |
| HP            | ProBook 440 G5              | [6753d2054d](https://linux-hardware.org/?probe=6753d2054d) | Oct 01, 2020 |
| HP            | ProBook 440 G5              | [6c568247ff](https://linux-hardware.org/?probe=6c568247ff) | Oct 01, 2020 |
| ASUSTek       | X411UA                      | [15bcec7549](https://linux-hardware.org/?probe=15bcec7549) | Sep 28, 2020 |
| Dell          | Vostro 3578                 | [5ff5b89d5e](https://linux-hardware.org/?probe=5ff5b89d5e) | Sep 22, 2020 |
| Dell          | Inspiron 5559               | [3a8b43fc2f](https://linux-hardware.org/?probe=3a8b43fc2f) | Sep 16, 2020 |
| ASUSTek       | X411UA                      | [8adea7b2b3](https://linux-hardware.org/?probe=8adea7b2b3) | Sep 15, 2020 |
| Dell          | Vostro 1450                 | [444ddb1aa9](https://linux-hardware.org/?probe=444ddb1aa9) | Sep 15, 2020 |
| Dell          | Precision 3520              | [e8f520c4fa](https://linux-hardware.org/?probe=e8f520c4fa) | Sep 09, 2020 |
| MASSCOM VI... | L133                        | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| HP            | ProBook 440 G6              | [11a8a7e166](https://linux-hardware.org/?probe=11a8a7e166) | Sep 07, 2020 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [42cdde5346](https://linux-hardware.org/?probe=42cdde5346) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [6b4eeecb26](https://linux-hardware.org/?probe=6b4eeecb26) | Sep 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [a9ced30680](https://linux-hardware.org/?probe=a9ced30680) | Aug 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [17c4f51c75](https://linux-hardware.org/?probe=17c4f51c75) | Aug 29, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [08d8dc8d6e](https://linux-hardware.org/?probe=08d8dc8d6e) | Aug 28, 2020 |
| Lenovo        | ThinkPad L430 2465CTO       | [e5371d9b58](https://linux-hardware.org/?probe=e5371d9b58) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ff005e6d9](https://linux-hardware.org/?probe=4ff005e6d9) | Aug 21, 2020 |
| Lenovo        | ThinkPad T580 20L9001MUS    | [92c940e8c2](https://linux-hardware.org/?probe=92c940e8c2) | Aug 21, 2020 |
| Dell          | Inspiron 3537               | [e7702e2ce8](https://linux-hardware.org/?probe=e7702e2ce8) | Aug 20, 2020 |
| Dell          | G3 3579                     | [8e341b94ae](https://linux-hardware.org/?probe=8e341b94ae) | Aug 18, 2020 |
| Dell          | G3 3579                     | [9a1078144d](https://linux-hardware.org/?probe=9a1078144d) | Aug 18, 2020 |
| HP            | EliteBook 840 G5            | [52f08d8242](https://linux-hardware.org/?probe=52f08d8242) | Aug 12, 2020 |
| Lenovo        | ThinkPad E480 20KN005GVA    | [f77c6858ad](https://linux-hardware.org/?probe=f77c6858ad) | Jul 24, 2020 |
| HP            | EliteBook 840 G5            | [a58d188243](https://linux-hardware.org/?probe=a58d188243) | Jul 19, 2020 |
| Dell          | XPS 15 9570                 | [ab4eff4438](https://linux-hardware.org/?probe=ab4eff4438) | Jul 16, 2020 |
| Dell          | Latitude E5470              | [777b8955c3](https://linux-hardware.org/?probe=777b8955c3) | Jul 12, 2020 |
| Apple         | MacBookPro8,1               | [d0dff5e971](https://linux-hardware.org/?probe=d0dff5e971) | Jul 09, 2020 |
| Dell          | Vostro 3590                 | [4f8fb0d621](https://linux-hardware.org/?probe=4f8fb0d621) | Jul 09, 2020 |
| Dell          | XPS 15 9570                 | [4e1f771d23](https://linux-hardware.org/?probe=4e1f771d23) | Jun 29, 2020 |
| Dell          | Vostro 3460                 | [2338ae0fde](https://linux-hardware.org/?probe=2338ae0fde) | Jun 28, 2020 |
| HP            | ZBook 17 G2                 | [467e55d0db](https://linux-hardware.org/?probe=467e55d0db) | Jun 20, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [652d0e5648](https://linux-hardware.org/?probe=652d0e5648) | Jun 18, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [3b5f86f3d4](https://linux-hardware.org/?probe=3b5f86f3d4) | Jun 18, 2020 |
| Dell          | Inspiron 5548               | [60a6140ac2](https://linux-hardware.org/?probe=60a6140ac2) | Jun 14, 2020 |
| Dell          | Inspiron 5548               | [ac70aa8a8d](https://linux-hardware.org/?probe=ac70aa8a8d) | Jun 14, 2020 |
| Dell          | Vostro 3590                 | [faca1b4063](https://linux-hardware.org/?probe=faca1b4063) | Jun 14, 2020 |
| HP            | ZBook Studio G3             | [91a0ff7707](https://linux-hardware.org/?probe=91a0ff7707) | Jun 10, 2020 |
| Dell          | Inspiron 5570               | [be05348be2](https://linux-hardware.org/?probe=be05348be2) | May 29, 2020 |
| Dell          | Inspiron 5570               | [945550a204](https://linux-hardware.org/?probe=945550a204) | May 29, 2020 |
| Dell          | Latitude E7440              | [26b5908778](https://linux-hardware.org/?probe=26b5908778) | May 20, 2020 |
| HP            | EliteBook 8570w             | [849bf107d8](https://linux-hardware.org/?probe=849bf107d8) | May 18, 2020 |
| HP            | EliteBook 8570w             | [5a938c4186](https://linux-hardware.org/?probe=5a938c4186) | May 17, 2020 |
| Dell          | Inspiron 7520               | [f400730782](https://linux-hardware.org/?probe=f400730782) | May 15, 2020 |
| HP            | ProBook 440 G6              | [272430b55d](https://linux-hardware.org/?probe=272430b55d) | May 12, 2020 |
| Toshiba       | PORTEGE T110                | [8c8ec8db54](https://linux-hardware.org/?probe=8c8ec8db54) | May 10, 2020 |
| Acer          | Aspire R3-131T              | [7e7b980d96](https://linux-hardware.org/?probe=7e7b980d96) | May 09, 2020 |
| Dell          | Vostro 14-5480              | [3edae78003](https://linux-hardware.org/?probe=3edae78003) | Apr 28, 2020 |
| Dell          | Inspiron 3558               | [8e17ac8b14](https://linux-hardware.org/?probe=8e17ac8b14) | Apr 27, 2020 |
| Acer          | Swift SF315-52              | [a41dc8c7b3](https://linux-hardware.org/?probe=a41dc8c7b3) | Apr 24, 2020 |
| Dell          | Vostro 3478                 | [65a16b0f00](https://linux-hardware.org/?probe=65a16b0f00) | Apr 22, 2020 |
| HP            | EliteBook 8560w             | [985dd25740](https://linux-hardware.org/?probe=985dd25740) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [8b6c1d10a4](https://linux-hardware.org/?probe=8b6c1d10a4) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [9cb006b675](https://linux-hardware.org/?probe=9cb006b675) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [e670bd004a](https://linux-hardware.org/?probe=e670bd004a) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [ed1d4fbd62](https://linux-hardware.org/?probe=ed1d4fbd62) | Apr 19, 2020 |
| Acer          | Aspire E5-575               | [c51238bbe1](https://linux-hardware.org/?probe=c51238bbe1) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | [e421f3a586](https://linux-hardware.org/?probe=e421f3a586) | Apr 10, 2020 |
| Dell          | XPS 13 9360                 | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Dell          | Precision 5530              | [805db6810c](https://linux-hardware.org/?probe=805db6810c) | Mar 31, 2020 |
| HP            | EliteBook 8540w             | [6093f50362](https://linux-hardware.org/?probe=6093f50362) | Mar 30, 2020 |
| Sony          | VPCEB42EG                   | [d2586cdd17](https://linux-hardware.org/?probe=d2586cdd17) | Mar 25, 2020 |
| Sony          | VPCEB42EG                   | [424402e2b1](https://linux-hardware.org/?probe=424402e2b1) | Mar 25, 2020 |
| ASUSTek       | GL553VE                     | [1238bea224](https://linux-hardware.org/?probe=1238bea224) | Mar 21, 2020 |
| HP            | Compaq Presario CQ45        | [72a39494c1](https://linux-hardware.org/?probe=72a39494c1) | Mar 18, 2020 |
| HP            | Laptop 14-bs0xx             | [7dddec34d1](https://linux-hardware.org/?probe=7dddec34d1) | Mar 02, 2020 |
| HP            | Compaq Presario CQ45        | [f1e468eec0](https://linux-hardware.org/?probe=f1e468eec0) | Feb 29, 2020 |
| HP            | Laptop 14-bs0xx             | [3740504388](https://linux-hardware.org/?probe=3740504388) | Feb 28, 2020 |
| ASUSTek       | X411UA                      | [284484a6b6](https://linux-hardware.org/?probe=284484a6b6) | Feb 15, 2020 |
| Koompi        | Unknown                     | [46e5e1375d](https://linux-hardware.org/?probe=46e5e1375d) | Feb 12, 2020 |
| MSI           | GF63 8RD                    | [6eae1d7ba9](https://linux-hardware.org/?probe=6eae1d7ba9) | Feb 01, 2020 |
| MSI           | GF63 8RD                    | [b7087b6ba5](https://linux-hardware.org/?probe=b7087b6ba5) | Jan 31, 2020 |
| ASUSTek       | K501UX                      | [46c0e495c1](https://linux-hardware.org/?probe=46c0e495c1) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | [b2bc63b818](https://linux-hardware.org/?probe=b2bc63b818) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4ea2e33944](https://linux-hardware.org/?probe=4ea2e33944) | Jan 07, 2020 |
| AMI           | Cherry Trail FFD            | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| Jumper        | EZpad                       | [6dfb4e2274](https://linux-hardware.org/?probe=6dfb4e2274) | Oct 31, 2019 |
| Dell          | System Vostro 3450          | [2017fd9a25](https://linux-hardware.org/?probe=2017fd9a25) | Oct 29, 2019 |
| Dell          | System Vostro 3450          | [90391fe6fe](https://linux-hardware.org/?probe=90391fe6fe) | Sep 19, 2019 |
| Samsung       | NC208/NC108                 | [a99fe6de20](https://linux-hardware.org/?probe=a99fe6de20) | Sep 16, 2019 |
| Dell          | Inspiron 3421               | [46a7955491](https://linux-hardware.org/?probe=46a7955491) | Sep 04, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | [35dfb93d51](https://linux-hardware.org/?probe=35dfb93d51) | Sep 02, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | [635d10113c](https://linux-hardware.org/?probe=635d10113c) | Sep 02, 2019 |
| HP            | ProBook 450 G1              | [f9ed638fe3](https://linux-hardware.org/?probe=f9ed638fe3) | Aug 27, 2019 |
| Dell          | System Inspiron N4110       | [1923c8603b](https://linux-hardware.org/?probe=1923c8603b) | Aug 13, 2019 |
| Dell          | Inspiron 3537               | [96b08c73b2](https://linux-hardware.org/?probe=96b08c73b2) | Jul 03, 2019 |
| Dell          | Inspiron 7559               | [9662a59bb6](https://linux-hardware.org/?probe=9662a59bb6) | Jun 19, 2019 |
| ASUSTek       | K46CM                       | [f695a76e03](https://linux-hardware.org/?probe=f695a76e03) | Jun 16, 2019 |
| Lenovo        | ThinkPad X230 2325BK0       | [e3cbad71df](https://linux-hardware.org/?probe=e3cbad71df) | Jun 06, 2019 |
| Dell          | Precision M4800             | [87cd78dbb8](https://linux-hardware.org/?probe=87cd78dbb8) | Jun 06, 2019 |
| Dell          | Inspiron 7559               | [2b022f3e6e](https://linux-hardware.org/?probe=2b022f3e6e) | Jun 06, 2019 |
| HP            | Unknown                     | [5a84e64836](https://linux-hardware.org/?probe=5a84e64836) | Jun 05, 2019 |
| Lenovo        | Unknown                     | [bb521ffe81](https://linux-hardware.org/?probe=bb521ffe81) | May 29, 2019 |
| Lenovo        | Unknown                     | [ded7e33a30](https://linux-hardware.org/?probe=ded7e33a30) | May 29, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | [11b1a757e3](https://linux-hardware.org/?probe=11b1a757e3) | May 07, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | [48a1bab21b](https://linux-hardware.org/?probe=48a1bab21b) | May 06, 2019 |
| Dell          | Inspiron 3420               | [97669e6bac](https://linux-hardware.org/?probe=97669e6bac) | Apr 28, 2019 |
| Lenovo        | ThinkPad X240 20AMA01LVA    | [60e3dddb8e](https://linux-hardware.org/?probe=60e3dddb8e) | Apr 18, 2019 |
| Lenovo        | ThinkPad X230 2325VEN       | [7de9f34ff3](https://linux-hardware.org/?probe=7de9f34ff3) | Apr 08, 2019 |
| Lenovo        | ThinkPad T61 7661C54        | [f98ce96fd7](https://linux-hardware.org/?probe=f98ce96fd7) | Dec 14, 2018 |
| Lenovo        | ThinkPad T61 7661C54        | [3b2f20eb21](https://linux-hardware.org/?probe=3b2f20eb21) | Dec 14, 2018 |
| Lenovo        | ThinkPad X230 2325BK0       | [eb181d9db4](https://linux-hardware.org/?probe=eb181d9db4) | Nov 17, 2018 |
| MSI           | GP62 6QE                    | [0befde2891](https://linux-hardware.org/?probe=0befde2891) | Oct 29, 2018 |
| MSI           | GP62 6QE                    | [6d5cda0177](https://linux-hardware.org/?probe=6d5cda0177) | Oct 29, 2018 |
| ASUSTek       | FX503VM                     | [c3eafeed41](https://linux-hardware.org/?probe=c3eafeed41) | May 23, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | [b73b24ff47](https://linux-hardware.org/?probe=b73b24ff47) | May 16, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | [4ced3a8a3c](https://linux-hardware.org/?probe=4ced3a8a3c) | Feb 04, 2018 |
| HP            | Notebook                    | [8f94426008](https://linux-hardware.org/?probe=8f94426008) | Dec 21, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [96a6c5cbab](https://linux-hardware.org/?probe=96a6c5cbab) | Dec 17, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [f59b817feb](https://linux-hardware.org/?probe=f59b817feb) | Dec 12, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [06a39a2c60](https://linux-hardware.org/?probe=06a39a2c60) | Dec 12, 2017 |
| Dell          | Precision M4600             | [dbbeb2486e](https://linux-hardware.org/?probe=dbbeb2486e) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [7ee7ca743b](https://linux-hardware.org/?probe=7ee7ca743b) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [28ae3d12b8](https://linux-hardware.org/?probe=28ae3d12b8) | Dec 03, 2017 |
| ASUSTek       | GL552JX                     | [c3e4792075](https://linux-hardware.org/?probe=c3e4792075) | Dec 10, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 58        | 19.59%  |
| Ubuntu 18.04        | 20        | 6.76%   |
| Ubuntu 22.04        | 15        | 5.07%   |
| Arch Rolling        | 14        | 4.73%   |
| Arch                | 12        | 4.05%   |
| Pop!_OS 22.04       | 6         | 2.03%   |
| Pop!_OS 20.04       | 6         | 2.03%   |
| Ubuntu 21.04        | 5         | 1.69%   |
| Fedora 37           | 5         | 1.69%   |
| Debian 10           | 5         | 1.69%   |
| Ubuntu 21.10        | 4         | 1.35%   |
| Ubuntu 19.10        | 4         | 1.35%   |
| Ubuntu 16.04        | 4         | 1.35%   |
| Pop!_OS 21.04       | 4         | 1.35%   |
| OpenMandriva 4.2    | 4         | 1.35%   |
| KDE neon 20.04      | 4         | 1.35%   |
| Fedora 34           | 4         | 1.35%   |
| ArcoLinux Rolling   | 4         | 1.35%   |
| Zorin 16            | 3         | 1.01%   |
| Ubuntu 22.10        | 3         | 1.01%   |
| OpenMandriva 4.3    | 3         | 1.01%   |
| Manjaro 22.0.0      | 3         | 1.01%   |
| Manjaro 20.2        | 3         | 1.01%   |
| Linux Mint 21.1     | 3         | 1.01%   |
| Fedora 33           | 3         | 1.01%   |
| EndeavourOS Rolling | 3         | 1.01%   |
| Zorin 15            | 2         | 0.68%   |
| Ubuntu Unity 20.04  | 2         | 0.68%   |
| Ubuntu MATE 20.04   | 2         | 0.68%   |
| Ubuntu 20.10        | 2         | 0.68%   |
| Ubuntu 19.04        | 2         | 0.68%   |
| Pop!_OS 21.10       | 2         | 0.68%   |
| Pop!_OS 20.10       | 2         | 0.68%   |
| Nobara 36           | 2         | 0.68%   |
| Manjaro 18.0.4      | 2         | 0.68%   |
| Manjaro             | 2         | 0.68%   |
| Lubuntu 22.04       | 2         | 0.68%   |
| Lubuntu 20.04       | 2         | 0.68%   |
| Linux Mint 21       | 2         | 0.68%   |
| Linux Mint 20.3     | 2         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 116       | 40.28%  |
| Arch         | 26        | 9.03%   |
| Pop!_OS      | 20        | 6.94%   |
| Fedora       | 17        | 5.9%    |
| Linux Mint   | 14        | 4.86%   |
| Manjaro      | 12        | 4.17%   |
| OpenMandriva | 8         | 2.78%   |
| Endless      | 7         | 2.43%   |
| Debian       | 7         | 2.43%   |
| Zorin        | 5         | 1.74%   |
| Ubuntu Unity | 5         | 1.74%   |
| Kubuntu      | 5         | 1.74%   |
| Xubuntu      | 4         | 1.39%   |
| Lubuntu      | 4         | 1.39%   |
| KDE neon     | 4         | 1.39%   |
| ArcoLinux    | 4         | 1.39%   |
| EndeavourOS  | 3         | 1.04%   |
| Clear Linux  | 3         | 1.04%   |
| Ubuntu MATE  | 2         | 0.69%   |
| openSUSE     | 2         | 0.69%   |
| Nobara       | 2         | 0.69%   |
| MX           | 2         | 0.69%   |
| Kali         | 2         | 0.69%   |
| Gentoo       | 2         | 0.69%   |
| Elementary   | 2         | 0.69%   |
| Xero         | 1         | 0.35%   |
| Void Linux   | 1         | 0.35%   |
| SteamOS      | 1         | 0.35%   |
| Solus        | 1         | 0.35%   |
| ROSA         | 1         | 0.35%   |
| LMDE         | 1         | 0.35%   |
| Lilidog      | 1         | 0.35%   |
| Devuan       | 1         | 0.35%   |
| CentOS       | 1         | 0.35%   |
| Artix        | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 2.21%   |
| 5.4.0-52-generic         | 5         | 1.58%   |
| 5.4.0-48-generic         | 5         | 1.58%   |
| 5.4.0-40-generic         | 5         | 1.58%   |
| 5.4.0-37-generic         | 5         | 1.58%   |
| 5.15.0-56-generic        | 5         | 1.58%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.26%   |
| 5.8.0-55-generic         | 3         | 0.95%   |
| 5.8.0-53-generic         | 3         | 0.95%   |
| 5.8.0-48-generic         | 3         | 0.95%   |
| 5.8.0-43-generic         | 3         | 0.95%   |
| 5.15.0-48-generic        | 3         | 0.95%   |
| 5.11.0-41-generic        | 3         | 0.95%   |
| 5.11.0-37-generic        | 3         | 0.95%   |
| 4.10.0-28-generic        | 3         | 0.95%   |
| 6.2.1-arch1-1            | 2         | 0.63%   |
| 6.2.0-76060200-generic   | 2         | 0.63%   |
| 6.1.9-arch1-1            | 2         | 0.63%   |
| 6.1.8-200.fc37.x86_64    | 2         | 0.63%   |
| 5.9.14-200.fc33.x86_64   | 2         | 0.63%   |
| 5.8.0-7642-generic       | 2         | 0.63%   |
| 5.8.0-50-generic         | 2         | 0.63%   |
| 5.8.0-44-generic         | 2         | 0.63%   |
| 5.8.0-25-generic         | 2         | 0.63%   |
| 5.4.0-7642-generic       | 2         | 0.63%   |
| 5.4.0-74-generic         | 2         | 0.63%   |
| 5.4.0-72-generic         | 2         | 0.63%   |
| 5.4.0-70-generic         | 2         | 0.63%   |
| 5.4.0-58-generic         | 2         | 0.63%   |
| 5.4.0-47-generic         | 2         | 0.63%   |
| 5.4.0-45-generic         | 2         | 0.63%   |
| 5.4.0-39-generic         | 2         | 0.63%   |
| 5.4.0-29-generic         | 2         | 0.63%   |
| 5.4.0-19-generic         | 2         | 0.63%   |
| 5.3.0-46-generic         | 2         | 0.63%   |
| 5.3.0-28-generic         | 2         | 0.63%   |
| 5.3.0-18-generic         | 2         | 0.63%   |
| 5.19.12-200.fc36.x86_64  | 2         | 0.63%   |
| 5.18.10-76051810-generic | 2         | 0.63%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 17.06%  |
| 5.15.0  | 27        | 9.03%   |
| 5.8.0   | 24        | 8.03%   |
| 5.11.0  | 21        | 7.02%   |
| 5.3.0   | 11        | 3.68%   |
| 5.13.0  | 10        | 3.34%   |
| 4.15.0  | 8         | 2.68%   |
| 5.10.0  | 7         | 2.34%   |
| 5.0.0   | 7         | 2.34%   |
| 4.18.0  | 6         | 2.01%   |
| 5.19.0  | 5         | 1.67%   |
| 4.19.0  | 5         | 1.67%   |
| 5.10.14 | 4         | 1.34%   |
| 4.10.0  | 4         | 1.34%   |
| 6.0.8   | 3         | 1%      |
| 5.16.7  | 3         | 1%      |
| 6.2.1   | 2         | 0.67%   |
| 6.2.0   | 2         | 0.67%   |
| 6.1.9   | 2         | 0.67%   |
| 6.1.8   | 2         | 0.67%   |
| 6.1.1   | 2         | 0.67%   |
| 5.9.14  | 2         | 0.67%   |
| 5.19.12 | 2         | 0.67%   |
| 5.18.16 | 2         | 0.67%   |
| 5.18.10 | 2         | 0.67%   |
| 5.15.55 | 2         | 0.67%   |
| 5.13.16 | 2         | 0.67%   |
| 4.13.0  | 2         | 0.67%   |
| 6.1.21  | 1         | 0.33%   |
| 6.1.18  | 1         | 0.33%   |
| 6.1.14  | 1         | 0.33%   |
| 6.1.11  | 1         | 0.33%   |
| 6.1.10  | 1         | 0.33%   |
| 6.0.9   | 1         | 0.33%   |
| 6.0.7   | 1         | 0.33%   |
| 6.0.5   | 1         | 0.33%   |
| 6.0.16  | 1         | 0.33%   |
| 6.0.12  | 1         | 0.33%   |
| 6.0.10  | 1         | 0.33%   |
| 5.9.3   | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 58        | 19.59%  |
| 5.15    | 39        | 13.18%  |
| 5.8     | 27        | 9.12%   |
| 5.11    | 22        | 7.43%   |
| 5.13    | 16        | 5.41%   |
| 5.10    | 15        | 5.07%   |
| 6.1     | 11        | 3.72%   |
| 5.3     | 11        | 3.72%   |
| 5.0     | 10        | 3.38%   |
| 6.0     | 9         | 3.04%   |
| 5.19    | 9         | 3.04%   |
| 4.15    | 8         | 2.7%    |
| 5.18    | 7         | 2.36%   |
| 5.16    | 7         | 2.36%   |
| 5.9     | 6         | 2.03%   |
| 4.19    | 6         | 2.03%   |
| 4.18    | 6         | 2.03%   |
| 6.2     | 4         | 1.35%   |
| 5.14    | 4         | 1.35%   |
| 5.12    | 4         | 1.35%   |
| 4.10    | 4         | 1.35%   |
| 5.7     | 3         | 1.01%   |
| 5.17    | 3         | 1.01%   |
| 5.5     | 2         | 0.68%   |
| 4.13    | 2         | 0.68%   |
| 4.4     | 1         | 0.34%   |
| 4.12    | 1         | 0.34%   |
| 4.1     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 278       | 99.64%  |
| i686   | 1         | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 153       | 52.76%  |
| KDE5             | 36        | 12.41%  |
| Unknown          | 35        | 12.07%  |
| XFCE             | 22        | 7.59%   |
| X-Cinnamon       | 9         | 3.1%    |
| KDE              | 8         | 2.76%   |
| Unity            | 5         | 1.72%   |
| LXQt             | 4         | 1.38%   |
| Cinnamon         | 3         | 1.03%   |
| Pantheon         | 2         | 0.69%   |
| MATE             | 2         | 0.69%   |
| bspwm            | 2         | 0.69%   |
| X-Generic        | 1         | 0.34%   |
| sway             | 1         | 0.34%   |
| Openbox          | 1         | 0.34%   |
| lightdm-xsession | 1         | 0.34%   |
| LeftWM           | 1         | 0.34%   |
| KDE4             | 1         | 0.34%   |
| Deepin           | 1         | 0.34%   |
| Budgie           | 1         | 0.34%   |
| awesome          | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 223       | 76.63%  |
| Wayland | 45        | 15.46%  |
| Unknown | 20        | 6.87%   |
| Tty     | 3         | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 140       | 48.61%  |
| GDM     | 48        | 16.67%  |
| SDDM    | 35        | 12.15%  |
| LightDM | 27        | 9.38%   |
| GDM3    | 25        | 8.68%   |
| TDM     | 10        | 3.47%   |
| XDM     | 1         | 0.35%   |
| SLiM    | 1         | 0.35%   |
| KDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 216       | 77.42%  |
| Unknown | 35        | 12.54%  |
| vi_VN   | 14        | 5.02%   |
| C       | 7         | 2.51%   |
| en_AU   | 3         | 1.08%   |
| en_GB   | 2         | 0.72%   |
| ru_RU   | 1         | 0.36%   |
| fr_FR   | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 187       | 65.38%  |
| BIOS | 99        | 34.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 228       | 80.28%  |
| Btrfs    | 26        | 9.15%   |
| Unknown  | 12        | 4.23%   |
| Overlay  | 11        | 3.87%   |
| Zfs      | 2         | 0.7%    |
| Xfs      | 2         | 0.7%    |
| Reiserfs | 1         | 0.35%   |
| F2fs     | 1         | 0.35%   |
| Ext3     | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 135       | 48.04%  |
| GPT     | 129       | 45.91%  |
| MBR     | 17        | 6.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 256       | 90.46%  |
| Yes       | 27        | 9.54%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 163       | 56.99%  |
| Yes       | 123       | 43.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 78        | 27.96%  |
| Lenovo              | 60        | 21.51%  |
| Hewlett-Packard     | 40        | 14.34%  |
| ASUSTek Computer    | 36        | 12.9%   |
| Acer                | 22        | 7.89%   |
| MSI                 | 9         | 3.23%   |
| Toshiba             | 5         | 1.79%   |
| Apple               | 5         | 1.79%   |
| Sony                | 4         | 1.43%   |
| Chuwi               | 4         | 1.43%   |
| Samsung Electronics | 3         | 1.08%   |
| Timi                | 2         | 0.72%   |
| TENKU               | 1         | 0.36%   |
| Panasonic           | 1         | 0.36%   |
| MASSCOM VIETNAM     | 1         | 0.36%   |
| LG Electronics      | 1         | 0.36%   |
| Koompi              | 1         | 0.36%   |
| Jumper              | 1         | 0.36%   |
| Google              | 1         | 0.36%   |
| Gigabyte Technology | 1         | 0.36%   |
| Gateway             | 1         | 0.36%   |
| Anbernic            | 1         | 0.36%   |
| AMI                 | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Inspiron 3537                   | 4         | 1.43%   |
| Unknown                              | 4         | 1.43%   |
| Lenovo ThinkPad E14 20RAS0KX00       | 3         | 1.08%   |
| Lenovo Legion 5 15ARH05 82B5         | 3         | 1.08%   |
| ASUS X411UA                          | 3         | 1.08%   |
| Toshiba Satellite L840               | 2         | 0.72%   |
| MSI GF63 8RD                         | 2         | 0.72%   |
| Lenovo ThinkPad W530 2447EJ9         | 2         | 0.72%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0     | 2         | 0.72%   |
| Lenovo Legion 5 15ACH6H 82JU         | 2         | 0.72%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4 | 2         | 0.72%   |
| HP Notebook                          | 2         | 0.72%   |
| HP Laptop 14-bs0xx                   | 2         | 0.72%   |
| HP EliteBook 8470p                   | 2         | 0.72%   |
| HP EliteBook 840 G2                  | 2         | 0.72%   |
| Dell XPS 15 9570                     | 2         | 0.72%   |
| Dell Vostro 5568                     | 2         | 0.72%   |
| Dell Vostro 3590                     | 2         | 0.72%   |
| Dell Vostro 3578                     | 2         | 0.72%   |
| Dell Vostro 3478                     | 2         | 0.72%   |
| Dell Vostro 3460                     | 2         | 0.72%   |
| Dell Vostro 15-3568                  | 2         | 0.72%   |
| Dell System Vostro 3450              | 2         | 0.72%   |
| Dell Precision M4600                 | 2         | 0.72%   |
| Dell Latitude E7440                  | 2         | 0.72%   |
| Dell Latitude E7240                  | 2         | 0.72%   |
| Dell Latitude E6530                  | 2         | 0.72%   |
| Dell Inspiron 5570                   | 2         | 0.72%   |
| Dell Inspiron 3558                   | 2         | 0.72%   |
| Dell G3 3579                         | 2         | 0.72%   |
| Dell G3 3500                         | 2         | 0.72%   |
| Chuwi GemiBook Pro                   | 2         | 0.72%   |
| Apple MacBookPro11,4                 | 2         | 0.72%   |
| Acer Swift SF315-52                  | 2         | 0.72%   |
| Acer Predator PH315-51               | 2         | 0.72%   |
| Acer Aspire E5-575                   | 2         | 0.72%   |
| Acer Aspire A715-42G                 | 2         | 0.72%   |
| Acer Aspire A315-42                  | 2         | 0.72%   |
| Toshiba Satellite E45-B              | 1         | 0.36%   |
| Toshiba PORTEGE T110                 | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 31        | 11.11%  |
| Dell Inspiron      | 20        | 7.17%   |
| Dell Latitude      | 19        | 6.81%   |
| Dell Vostro        | 17        | 6.09%   |
| Acer Aspire        | 15        | 5.38%   |
| Lenovo IdeaPad     | 11        | 3.94%   |
| HP EliteBook       | 11        | 3.94%   |
| ASUS VivoBook      | 8         | 2.87%   |
| Lenovo Legion      | 7         | 2.51%   |
| HP ProBook         | 7         | 2.51%   |
| Dell Precision     | 7         | 2.51%   |
| Lenovo ThinkBook   | 6         | 2.15%   |
| Dell XPS           | 6         | 2.15%   |
| HP Laptop          | 5         | 1.79%   |
| ASUS ROG           | 5         | 1.79%   |
| HP ZBook           | 4         | 1.43%   |
| Dell System        | 4         | 1.43%   |
| Dell G3            | 4         | 1.43%   |
| ASUS ASUS          | 4         | 1.43%   |
| Unknown            | 4         | 1.43%   |
| Toshiba Satellite  | 3         | 1.08%   |
| HP Pavilion        | 3         | 1.08%   |
| ASUS X411UA        | 3         | 1.08%   |
| Acer Swift         | 3         | 1.08%   |
| Acer Predator      | 3         | 1.08%   |
| MSI GF63           | 2         | 0.72%   |
| HP Notebook        | 2         | 0.72%   |
| HP Compaq          | 2         | 0.72%   |
| Chuwi GemiBook     | 2         | 0.72%   |
| Apple MacBookPro11 | 2         | 0.72%   |
| Toshiba PORTEGE    | 1         | 0.36%   |
| Toshiba dynabook   | 1         | 0.36%   |
| Timi RedmiBook     | 1         | 0.36%   |
| Timi A35S          | 1         | 0.36%   |
| TENKU SB14         | 1         | 0.36%   |
| Sony VPCEB42EG     | 1         | 0.36%   |
| Sony VPCCW13FX     | 1         | 0.36%   |
| Sony VGN-NW270F    | 1         | 0.36%   |
| Sony SVE14A15FGW   | 1         | 0.36%   |
| Samsung NC208      | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 38        | 13.62%  |
| 2020 | 34        | 12.19%  |
| 2012 | 28        | 10.04%  |
| 2019 | 26        | 9.32%   |
| 2021 | 25        | 8.96%   |
| 2015 | 22        | 7.89%   |
| 2017 | 20        | 7.17%   |
| 2013 | 18        | 6.45%   |
| 2011 | 18        | 6.45%   |
| 2016 | 17        | 6.09%   |
| 2022 | 9         | 3.23%   |
| 2014 | 9         | 3.23%   |
| 2009 | 7         | 2.51%   |
| 2010 | 6         | 2.15%   |
| 2007 | 2         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 279       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 253       | 89.4%   |
| Enabled  | 30        | 10.6%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 278       | 99.64%  |
| Yes  | 1         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 92        | 32.62%  |
| 16.01-24.0 | 61        | 21.63%  |
| 8.01-16.0  | 52        | 18.44%  |
| 3.01-4.0   | 47        | 16.67%  |
| 32.01-64.0 | 16        | 5.67%   |
| 1.01-2.0   | 8         | 2.84%   |
| 24.01-32.0 | 4         | 1.42%   |
| 2.01-3.0   | 1         | 0.35%   |
| 0.51-1.0   | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 106       | 35.1%   |
| 1.01-2.0   | 70        | 23.18%  |
| 4.01-8.0   | 57        | 18.87%  |
| 3.01-4.0   | 46        | 15.23%  |
| 8.01-16.0  | 13        | 4.3%    |
| 0.51-1.0   | 7         | 2.32%   |
| 16.01-24.0 | 2         | 0.66%   |
| 0.01-0.5   | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 191       | 67.49%  |
| 2      | 81        | 28.62%  |
| 3      | 9         | 3.18%   |
| 4      | 1         | 0.35%   |
| 0      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 218       | 78.14%  |
| Yes       | 61        | 21.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 229       | 81.21%  |
| No        | 53        | 18.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 278       | 99.64%  |
| No        | 1         | 0.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 244       | 87.14%  |
| No        | 36        | 12.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Vietnam | 279       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Ho Chi Minh City | 122       | 41.08%  |
| Hanoi            | 101       | 34.01%  |
| Da Nang          | 6         | 2.02%   |
| Can Tho          | 6         | 2.02%   |
| Bien Hoa         | 6         | 2.02%   |
| Thuan An         | 4         | 1.35%   |
| Nha Trang        | 4         | 1.35%   |
| Huế            | 3         | 1.01%   |
| Buon Ma Thuot    | 3         | 1.01%   |
| Vũng Tàu       | 2         | 0.67%   |
| Vinh Phuc        | 2         | 0.67%   |
| Vinh             | 2         | 0.67%   |
| Thu Duc          | 2         | 0.67%   |
| Thai Nguyen      | 2         | 0.67%   |
| Tay Ninh         | 2         | 0.67%   |
| Quảng Ngai     | 2         | 0.67%   |
| Nam Định      | 2         | 0.67%   |
| Hoa Binh         | 2         | 0.67%   |
| Binh Hoa         | 2         | 0.67%   |
| Bao Loc          | 2         | 0.67%   |
| Bac Giang        | 2         | 0.67%   |
| Viet Tri         | 1         | 0.34%   |
| Tra Vinh         | 1         | 0.34%   |
| Tinh Quang Binh  | 1         | 0.34%   |
| Tinh GJong Nai   | 1         | 0.34%   |
| Thanh Hóa       | 1         | 0.34%   |
| Tan An           | 1         | 0.34%   |
| Quang Trung      | 1         | 0.34%   |
| Quan Muoi Mot    | 1         | 0.34%   |
| Quan Muoi        | 1         | 0.34%   |
| Quan Binh Thanh  | 1         | 0.34%   |
| Nga Bay          | 1         | 0.34%   |
| Lien Chieu       | 1         | 0.34%   |
| Haiphong         | 1         | 0.34%   |
| Go Vap           | 1         | 0.34%   |
| Do Son           | 1         | 0.34%   |
| Dien Ban         | 1         | 0.34%   |
| Can Duoc         | 1         | 0.34%   |
| Bến Tre        | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 50        | 62     | 13.44%  |
| WDC                 | 48        | 57     | 12.9%   |
| Toshiba             | 31        | 36     | 8.33%   |
| Seagate             | 29        | 34     | 7.8%    |
| SK hynix            | 26        | 30     | 6.99%   |
| HGST                | 21        | 22     | 5.65%   |
| Intel               | 18        | 19     | 4.84%   |
| Micron Technology   | 16        | 18     | 4.3%    |
| Unknown             | 14        | 14     | 3.76%   |
| Kingston            | 13        | 15     | 3.49%   |
| Hitachi             | 10        | 14     | 2.69%   |
| Crucial             | 10        | 10     | 2.69%   |
| SanDisk             | 9         | 12     | 2.42%   |
| Plextor             | 7         | 7      | 1.88%   |
| OSCOO               | 6         | 7      | 1.61%   |
| KIOXIA              | 5         | 7      | 1.34%   |
| TO Exter            | 4         | 6      | 1.08%   |
| Transcend           | 3         | 3      | 0.81%   |
| LITEON              | 3         | 3      | 0.81%   |
| KingSpec            | 3         | 3      | 0.81%   |
| Colorful            | 3         | 3      | 0.81%   |
| UMIS                | 2         | 2      | 0.54%   |
| SPCC                | 2         | 2      | 0.54%   |
| Netac               | 2         | 2      | 0.54%   |
| Lexar               | 2         | 2      | 0.54%   |
| KingFast            | 2         | 2      | 0.54%   |
| KingDian            | 2         | 3      | 0.54%   |
| Hikvision           | 2         | 2      | 0.54%   |
| Gigabyte Technology | 2         | 2      | 0.54%   |
| FORESEE             | 2         | 2      | 0.54%   |
| Apple               | 2         | 2      | 0.54%   |
| W800S               | 1         | 1      | 0.27%   |
| SSSTC               | 1         | 1      | 0.27%   |
| Silicon Motion      | 1         | 3      | 0.27%   |
| SAM                 | 1         | 1      | 0.27%   |
| Phison              | 1         | 1      | 0.27%   |
| OSC                 | 1         | 1      | 0.27%   |
| NGFF                | 1         | 1      | 0.27%   |
| Maxtor              | 1         | 3      | 0.27%   |
| LITEONIT            | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                    | 8         | 2.1%    |
| Seagate ST1000LM035-1RK172 1TB              | 7         | 1.84%   |
| Toshiba MQ04ABF100 1TB                      | 5         | 1.31%   |
| Toshiba MQ01ABF050 500GB                    | 5         | 1.31%   |
| Samsung NVMe SSD Drive 512GB                | 5         | 1.31%   |
| Crucial CT240BX500SSD1 240GB                | 5         | 1.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 4         | 1.05%   |
| TO Exter nal USB 3.0 1TB                    | 4         | 1.05%   |
| SK hynix NVMe SSD Drive 256GB               | 4         | 1.05%   |
| Seagate ST1000LM049-2GH172 1TB              | 4         | 1.05%   |
| Samsung MZALQ512HALU-000L2 512GB            | 4         | 1.05%   |
| WDC WD5000LPLX-08ZNTT0 500GB                | 3         | 0.79%   |
| Toshiba MQ01ABD100 1TB                      | 3         | 0.79%   |
| SK hynix NVMe SSD Drive 512GB               | 3         | 0.79%   |
| Seagate ST9500325AS 500GB                   | 3         | 0.79%   |
| Seagate ST500LT012-9WS142 500GB             | 3         | 0.79%   |
| Samsung SSD 860 EVO 500GB                   | 3         | 0.79%   |
| Samsung SSD 860 EVO 250GB                   | 3         | 0.79%   |
| OSCOO OSC SSD 128GB                         | 3         | 0.79%   |
| Kingston SA400S37120G 120GB SSD             | 3         | 0.79%   |
| Kingston NVMe SSD Drive 256GB               | 3         | 0.79%   |
| Hitachi HTS545050A7E380 500GB               | 3         | 0.79%   |
| HGST HTS545050A7E680 500GB                  | 3         | 0.79%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD            | 2         | 0.52%   |
| WDC WD5000LPLX-60ZNTT1 500GB                | 2         | 0.52%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 2         | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB                    | 2         | 0.52%   |
| WDC WD10JPVX-75JC3T0 1TB                    | 2         | 0.52%   |
| WDC PC SN720 SDAPNTW-256G-1006 256GB        | 2         | 0.52%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB        | 2         | 0.52%   |
| Unknown NVMe SSD Drive 256GB                | 2         | 0.52%   |
| Unknown MMC Card  32GB                      | 2         | 0.52%   |
| Unknown MMC Card  16GB                      | 2         | 0.52%   |
| Toshiba NVMe SSD Drive 256GB                | 2         | 0.52%   |
| Toshiba MK2035GSS 200GB                     | 2         | 0.52%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB   | 2         | 0.52%   |
| SK hynix HFM256GDJTNG-8310A 256GB           | 2         | 0.52%   |
| SK hynix BC711 NVMe 256GB                   | 2         | 0.52%   |
| SK hynix BC511 NVMe 512GB                   | 2         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 29        | 34     | 26.36%  |
| WDC     | 28        | 36     | 25.45%  |
| Toshiba | 22        | 22     | 20%     |
| HGST    | 21        | 22     | 19.09%  |
| Hitachi | 10        | 14     | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 18     | 13.82%  |
| WDC                 | 10        | 10     | 8.13%   |
| Crucial             | 10        | 10     | 8.13%   |
| Intel               | 8         | 9      | 6.5%    |
| Plextor             | 7         | 7      | 5.69%   |
| SanDisk             | 5         | 6      | 4.07%   |
| Kingston            | 5         | 6      | 4.07%   |
| TO Exter            | 4         | 6      | 3.25%   |
| SK hynix            | 4         | 4      | 3.25%   |
| OSCOO               | 4         | 4      | 3.25%   |
| Transcend           | 3         | 3      | 2.44%   |
| Micron Technology   | 3         | 3      | 2.44%   |
| LITEON              | 3         | 3      | 2.44%   |
| KingSpec            | 3         | 3      | 2.44%   |
| Toshiba             | 2         | 3      | 1.63%   |
| SPCC                | 2         | 2      | 1.63%   |
| Netac               | 2         | 2      | 1.63%   |
| Lexar               | 2         | 2      | 1.63%   |
| KingDian            | 2         | 3      | 1.63%   |
| Hikvision           | 2         | 2      | 1.63%   |
| FORESEE             | 2         | 2      | 1.63%   |
| Colorful            | 2         | 2      | 1.63%   |
| Apple               | 2         | 2      | 1.63%   |
| W800S               | 1         | 1      | 0.81%   |
| Unknown             | 1         | 1      | 0.81%   |
| SAM                 | 1         | 1      | 0.81%   |
| OSC                 | 1         | 1      | 0.81%   |
| NGFF                | 1         | 1      | 0.81%   |
| Maxtor              | 1         | 3      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| KLEVV               | 1         | 1      | 0.81%   |
| KIOXIA-EXCERIA      | 1         | 2      | 0.81%   |
| Kingmax             | 1         | 1      | 0.81%   |
| KingFast            | 1         | 1      | 0.81%   |
| KimMiDi             | 1         | 1      | 0.81%   |
| Indilinx            | 1         | 1      | 0.81%   |
| HXY                 | 1         | 2      | 0.81%   |
| Hewlett-Packard     | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |
| China               | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 121       | 156    | 34.28%  |
| SSD     | 112       | 135    | 31.73%  |
| HDD     | 105       | 128    | 29.75%  |
| MMC     | 10        | 10     | 2.83%   |
| Unknown | 5         | 5      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 182       | 257    | 56.7%   |
| NVMe | 121       | 156    | 37.69%  |
| MMC  | 10        | 10     | 3.12%   |
| SAS  | 8         | 11     | 2.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 152       | 200    | 73.43%  |
| 0.51-1.0   | 54        | 62     | 26.09%  |
| 1.01-2.0   | 1         | 1      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 106       | 36.43%  |
| 251-500        | 73        | 25.09%  |
| 51-100         | 30        | 10.31%  |
| 501-1000       | 22        | 7.56%   |
| 1001-2000      | 17        | 5.84%   |
| 21-50          | 14        | 4.81%   |
| 1-20           | 13        | 4.47%   |
| Unknown        | 10        | 3.44%   |
| 2001-3000      | 5         | 1.72%   |
| More than 3000 | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 126       | 42.57%  |
| 21-50          | 59        | 19.93%  |
| 51-100         | 40        | 13.51%  |
| 101-250        | 31        | 10.47%  |
| 251-500        | 17        | 5.74%   |
| 501-1000       | 11        | 3.72%   |
| Unknown        | 10        | 3.38%   |
| More than 3000 | 1         | 0.34%   |
| 1001-2000      | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 7.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1      | 3.7%    |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 3.7%    |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 3.7%    |
| WDC WD32 00BEVT-24A23 320GB                  | 1         | 1      | 3.7%    |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 3.7%    |
| Unknown Bamba-240GB SSD                      | 1         | 1      | 3.7%    |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 3.7%    |
| Toshiba MK8046GSX 80GB                       | 1         | 1      | 3.7%    |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 3.7%    |
| Toshiba HDWK105 500GB                        | 1         | 1      | 3.7%    |
| SK hynix HFS032G34MNC-2200A 32GB SSD         | 1         | 1      | 3.7%    |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 3.7%    |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 3.7%    |
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 3.7%    |
| LITEON LCH-256V2S 256GB SSD                  | 1         | 1      | 3.7%    |
| KingFast SSD 32GB                            | 1         | 1      | 3.7%    |
| Hitachi HTS725050A7E635 500GB                | 1         | 1      | 3.7%    |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 3.7%    |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 3.7%    |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.7%    |
| HGST HTS725032A7E630 320GB                   | 1         | 1      | 3.7%    |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 3.7%    |
| HGST HTS545050A7 500GB                       | 1         | 1      | 3.7%    |
| HGST HTS541010A7E630 1TB                     | 1         | 1      | 3.7%    |
| Crucial CT525MX300SSD1 528GB                 | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 18.52%  |
| HGST                | 5         | 6      | 18.52%  |
| Toshiba             | 4         | 4      | 14.81%  |
| Seagate             | 4         | 4      | 14.81%  |
| Hitachi             | 3         | 3      | 11.11%  |
| Unknown             | 1         | 1      | 3.7%    |
| SK hynix            | 1         | 1      | 3.7%    |
| Samsung Electronics | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| KingFast            | 1         | 1      | 3.7%    |
| Crucial             | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 5         | 6      | 25%     |
| WDC     | 4         | 4      | 20%     |
| Toshiba | 4         | 4      | 20%     |
| Seagate | 4         | 4      | 20%     |
| Hitachi | 3         | 3      | 15%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 21     | 74.07%  |
| SSD  | 6         | 6      | 22.22%  |
| NVMe | 1         | 1      | 3.7%    |

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
| Detected | 153       | 227    | 50%     |
| Works    | 127       | 179    | 41.5%   |
| Malfunc  | 26        | 28     | 8.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 219       | 60.5%   |
| Samsung Electronics            | 38        | 10.5%   |
| AMD                            | 23        | 6.35%   |
| SK hynix                       | 22        | 6.08%   |
| SanDisk                        | 14        | 3.87%   |
| Micron Technology              | 13        | 3.59%   |
| Kingston Technology Company    | 8         | 2.21%   |
| Toshiba America Info Systems   | 7         | 1.93%   |
| KIOXIA                         | 6         | 1.66%   |
| Solid State Storage Technology | 3         | 0.83%   |
| Phison Electronics             | 3         | 0.83%   |
| Union Memory (Shenzhen)        | 2         | 0.55%   |
| Silicon Motion                 | 2         | 0.55%   |
| Lite-On Technology             | 1         | 0.28%   |
| Lenovo                         | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 33        | 8.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 30        | 8.04%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 6.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 3.75%   |
| Samsung NVMe SSD Controller 980                                                | 14        | 3.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 3.75%   |
| Micron NVMe Storage Controller                                                 | 13        | 3.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 13        | 3.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 3.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 3.49%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 2.95%   |
| Intel Comet Lake SATA AHCI Controller                                          | 10        | 2.68%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 9         | 2.41%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 8         | 2.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 8         | 2.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 7         | 1.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.34%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.34%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 1.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.34%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 4         | 1.07%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.07%   |
| Solid State Storage Non-Volatile memory controller                             | 3         | 0.8%    |
| SK hynix BC511                                                                 | 3         | 0.8%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.8%    |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 0.8%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.8%    |
| Intel SSD 660P Series                                                          | 3         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.8%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.54%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.54%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 214       | 58.63%  |
| NVMe | 122       | 33.42%  |
| RAID | 25        | 6.85%   |
| IDE  | 4         | 1.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 244       | 87.46%  |
| AMD    | 35        | 12.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 5.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 3.23%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 3.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 2.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 2.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 2.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 1.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.43%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 1.43%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.43%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 1.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.43%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.43%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.43%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.43%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 1.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.08%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.08%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.08%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.08%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 1.08%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.08%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.08%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.72%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 2         | 0.72%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.72%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 105       | 37.63%  |
| Intel Core i7    | 59        | 21.15%  |
| Intel Core i3    | 28        | 10.04%  |
| Other            | 26        | 9.32%   |
| AMD Ryzen 5      | 16        | 5.73%   |
| AMD Ryzen 7      | 11        | 3.94%   |
| Intel Celeron    | 10        | 3.58%   |
| Intel Core 2 Duo | 7         | 2.51%   |
| Intel Atom       | 4         | 1.43%   |
| AMD Ryzen 3      | 3         | 1.08%   |
| Intel Pentium    | 2         | 0.72%   |
| Intel Genuine    | 2         | 0.72%   |
| Intel Xeon       | 1         | 0.36%   |
| AMD Ryzen 9      | 1         | 0.36%   |
| AMD Ryzen 7 PRO  | 1         | 0.36%   |
| AMD Ryzen 5 PRO  | 1         | 0.36%   |
| AMD Athlon       | 1         | 0.36%   |
| AMD A8           | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 122       | 43.73%  |
| 4      | 107       | 38.35%  |
| 6      | 27        | 9.68%   |
| 8      | 17        | 6.09%   |
| 14     | 2         | 0.72%   |
| 12     | 2         | 0.72%   |
| 1      | 2         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 279       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 250       | 89.61%  |
| 1      | 29        | 10.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 275       | 98.21%  |
| Unknown        | 5         | 1.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 19.44%  |
| 0x306a9    | 25        | 8.68%   |
| 0x806ea    | 22        | 7.64%   |
| 0x806ec    | 15        | 5.21%   |
| 0x40651    | 15        | 5.21%   |
| 0x806c1    | 14        | 4.86%   |
| 0x206a7    | 14        | 4.86%   |
| 0x306d4    | 13        | 4.51%   |
| 0x806e9    | 11        | 3.82%   |
| 0x906ea    | 9         | 3.13%   |
| 0x406e3    | 8         | 2.78%   |
| 0x306c3    | 7         | 2.43%   |
| 0x906e9    | 6         | 2.08%   |
| 0x506e3    | 6         | 2.08%   |
| 0xa0652    | 5         | 1.74%   |
| 0x806d1    | 4         | 1.39%   |
| 0x6fd      | 4         | 1.39%   |
| 0x0a50000c | 4         | 1.39%   |
| 0x08600106 | 4         | 1.39%   |
| 0x08108102 | 4         | 1.39%   |
| 0x906a3    | 3         | 1.04%   |
| 0x706e5    | 3         | 1.04%   |
| 0x20655    | 3         | 1.04%   |
| 0x1067a    | 3         | 1.04%   |
| 0x08608103 | 3         | 1.04%   |
| 0x08600104 | 3         | 1.04%   |
| 0x906ed    | 2         | 0.69%   |
| 0x906c0    | 2         | 0.69%   |
| 0x706a1    | 2         | 0.69%   |
| 0x406c4    | 2         | 0.69%   |
| 0x40661    | 2         | 0.69%   |
| 0x0a404102 | 2         | 0.69%   |
| 0x806eb    | 1         | 0.35%   |
| 0x806c2    | 1         | 0.35%   |
| 0x406c3    | 1         | 0.35%   |
| 0x30661    | 1         | 0.35%   |
| 0x20652    | 1         | 0.35%   |
| 0x106e5    | 1         | 0.35%   |
| 0x106ca    | 1         | 0.35%   |
| 0x0a50000d | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 77        | 27.6%   |
| IvyBridge        | 29        | 10.39%  |
| Haswell          | 26        | 9.32%   |
| TigerLake        | 18        | 6.45%   |
| Skylake          | 17        | 6.09%   |
| SandyBridge      | 16        | 5.73%   |
| Broadwell        | 15        | 5.38%   |
| Zen 2            | 11        | 3.94%   |
| Unknown          | 9         | 3.23%   |
| Zen 3            | 8         | 2.87%   |
| IceLake          | 7         | 2.51%   |
| Zen+             | 6         | 2.15%   |
| CometLake        | 6         | 2.15%   |
| Westmere         | 5         | 1.79%   |
| Core             | 5         | 1.79%   |
| Silvermont       | 4         | 1.43%   |
| Penryn           | 4         | 1.43%   |
| Goldmont plus    | 4         | 1.43%   |
| Alderlake Hybrid | 3         | 1.08%   |
| Zen              | 2         | 0.72%   |
| Tremont          | 2         | 0.72%   |
| Bonnell          | 2         | 0.72%   |
| Puma             | 1         | 0.36%   |
| Nehalem          | 1         | 0.36%   |
| Goldmont         | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 231       | 60%     |
| Nvidia | 100       | 25.97%  |
| AMD    | 54        | 14.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 6.94%   |
| Intel UHD Graphics 620                                                                   | 24        | 6.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 4.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 4.11%   |
| Intel HD Graphics 5500                                                                   | 14        | 3.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 3.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 3.34%   |
| Intel HD Graphics 620                                                                    | 11        | 2.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.57%   |
| AMD Renoir                                                                               | 10        | 2.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 1.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.54%   |
| Intel HD Graphics 530                                                                    | 6         | 1.54%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 1.29%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 1.29%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.29%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 5         | 1.29%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.03%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.03%   |
| Intel HD Graphics 630                                                                    | 4         | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.03%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.03%   |
| AMD Lucienne                                                                             | 4         | 1.03%   |
| Nvidia TU117M                                                                            | 3         | 0.77%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.77%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 138       | 49.46%  |
| Intel + Nvidia | 72        | 25.81%  |
| Intel + AMD    | 21        | 7.53%   |
| 1 x AMD        | 19        | 6.81%   |
| 1 x Nvidia     | 15        | 5.38%   |
| AMD + Nvidia   | 12        | 4.3%    |
| 2 x AMD        | 2         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 217       | 76.68%  |
| Proprietary | 65        | 22.97%  |
| Unknown     | 1         | 0.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 184       | 64.79%  |
| 1.01-2.0   | 39        | 13.73%  |
| 3.01-4.0   | 25        | 8.8%    |
| 0.51-1.0   | 15        | 5.28%   |
| 0.01-0.5   | 14        | 4.93%   |
| 5.01-6.0   | 3         | 1.06%   |
| 2.01-3.0   | 2         | 0.7%    |
| 7.01-8.0   | 1         | 0.35%   |
| 8.01-16.0  | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 61        | 19.55%  |
| Chimei Innolux          | 49        | 15.71%  |
| AU Optronics            | 47        | 15.06%  |
| LG Display              | 44        | 14.1%   |
| Samsung Electronics     | 27        | 8.65%   |
| Dell                    | 16        | 5.13%   |
| PANDA                   | 11        | 3.53%   |
| Sharp                   | 9         | 2.88%   |
| Lenovo                  | 6         | 1.92%   |
| LGD                     | 5         | 1.6%    |
| InfoVision              | 5         | 1.6%    |
| Goldstar                | 5         | 1.6%    |
| Apple                   | 5         | 1.6%    |
| ViewSonic               | 4         | 1.28%   |
| Chi Mei Optoelectronics | 3         | 0.96%   |
| ASUSTek Computer        | 3         | 0.96%   |
| RTK                     | 2         | 0.64%   |
| AOC                     | 2         | 0.64%   |
| TMX                     | 1         | 0.32%   |
| Sony                    | 1         | 0.32%   |
| Philips                 | 1         | 0.32%   |
| MStar                   | 1         | 0.32%   |
| LG Philips              | 1         | 0.32%   |
| HKC                     | 1         | 0.32%   |
| Hewlett-Packard         | 1         | 0.32%   |
| CSO                     | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LGD LCD Monitor 1920x1080                                             | 5         | 1.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 1.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 1.28%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 3         | 0.96%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.96%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 3         | 0.96%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 3         | 0.96%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 3         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.96%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.96%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.64%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.64%   |
| RTK LCD Monitor RTK2A3B 1200x1920 114x184mm 8.5-inch                  | 2         | 0.64%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 2         | 0.64%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 2         | 0.64%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.64%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.64%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 2         | 0.64%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.64%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 2         | 0.64%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch       | 2         | 0.64%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 2         | 0.64%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                 | 2         | 0.64%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 2         | 0.64%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                 | 2         | 0.64%   |
| BOE LCD Monitor BOE070D 1366x768 309x173mm 13.9-inch                  | 2         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 163       | 54.88%  |
| 1366x768 (WXGA)   | 82        | 27.61%  |
| 2560x1440 (QHD)   | 9         | 3.03%   |
| 3840x2160 (4K)    | 7         | 2.36%   |
| 1920x1200 (WUXGA) | 6         | 2.02%   |
| 1280x800 (WXGA)   | 6         | 2.02%   |
| 2880x1800         | 5         | 1.68%   |
| 1600x900 (HD+)    | 5         | 1.68%   |
| 2560x1600         | 3         | 1.01%   |
| 2160x1440         | 3         | 1.01%   |
| 1440x900 (WXGA+)  | 2         | 0.67%   |
| 3456x2160         | 1         | 0.34%   |
| 3440x1440         | 1         | 0.34%   |
| 3200x2000         | 1         | 0.34%   |
| 3200x1800 (QHD+)  | 1         | 0.34%   |
| 2560x1080         | 1         | 0.34%   |
| 1024x600          | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 120       | 38.71%  |
| 14      | 60        | 19.35%  |
| 13      | 57        | 18.39%  |
| 12      | 10        | 3.23%   |
| 21      | 9         | 2.9%    |
| 23      | 8         | 2.58%   |
| 17      | 7         | 2.26%   |
| 24      | 6         | 1.94%   |
| 18      | 6         | 1.94%   |
| Unknown | 6         | 1.94%   |
| 27      | 5         | 1.61%   |
| 31      | 4         | 1.29%   |
| 57      | 2         | 0.65%   |
| 11      | 2         | 0.65%   |
| 54      | 1         | 0.32%   |
| 52      | 1         | 0.32%   |
| 34      | 1         | 0.32%   |
| 28      | 1         | 0.32%   |
| 25      | 1         | 0.32%   |
| 19      | 1         | 0.32%   |
| 16      | 1         | 0.32%   |
| 10      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 219       | 70.65%  |
| 201-300     | 30        | 9.68%   |
| 501-600     | 19        | 6.13%   |
| 401-500     | 16        | 5.16%   |
| 351-400     | 9         | 2.9%    |
| 601-700     | 6         | 1.94%   |
| Unknown     | 6         | 1.94%   |
| 701-800     | 3         | 0.97%   |
| 1001-1500   | 2         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 242       | 86.74%  |
| 16/10   | 24        | 8.6%    |
| Unknown | 6         | 2.15%   |
| 3/2     | 3         | 1.08%   |
| 21/9    | 2         | 0.72%   |
| 0.56    | 2         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 119       | 38.14%  |
| 81-90          | 105       | 33.65%  |
| 201-250        | 22        | 7.05%   |
| 71-80          | 12        | 3.85%   |
| 61-70          | 10        | 3.21%   |
| 121-130        | 7         | 2.24%   |
| Unknown        | 6         | 1.92%   |
| 351-500        | 5         | 1.6%    |
| 301-350        | 5         | 1.6%    |
| 141-150        | 5         | 1.6%    |
| More than 1000 | 4         | 1.28%   |
| 251-300        | 4         | 1.28%   |
| 151-200        | 3         | 0.96%   |
| 51-60          | 2         | 0.64%   |
| 41-50          | 1         | 0.32%   |
| 111-120        | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 150       | 49.02%  |
| 101-120       | 87        | 28.43%  |
| 51-100        | 30        | 9.8%    |
| 161-240       | 21        | 6.86%   |
| More than 240 | 8         | 2.61%   |
| Unknown       | 6         | 1.96%   |
| 1-50          | 4         | 1.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 239       | 84.45%  |
| 2     | 37        | 13.07%  |
| 3     | 4         | 1.41%   |
| 0     | 3         | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 167       | 37.36%  |
| Realtek Semiconductor                  | 158       | 35.35%  |
| Qualcomm Atheros                       | 58        | 12.98%  |
| Broadcom                               | 22        | 4.92%   |
| MediaTek                               | 9         | 2.01%   |
| Broadcom Limited                       | 9         | 2.01%   |
| Marvell Technology Group               | 5         | 1.12%   |
| Samsung Electronics                    | 4         | 0.89%   |
| TP-Link                                | 2         | 0.45%   |
| Hewlett-Packard                        | 2         | 0.45%   |
| Xiaomi                                 | 1         | 0.22%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.22%   |
| Sierra Wireless                        | 1         | 0.22%   |
| SEGGER                                 | 1         | 0.22%   |
| Ralink Technology                      | 1         | 0.22%   |
| Ralink                                 | 1         | 0.22%   |
| Qualcomm                               | 1         | 0.22%   |
| Huawei Technologies                    | 1         | 0.22%   |
| Foxconn / Hon Hai                      | 1         | 0.22%   |
| D-Link                                 | 1         | 0.22%   |
| ASUSTek Computer                       | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 108       | 20.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 4.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 3.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 3.01%   |
| Intel Wireless 3165                                               | 15        | 2.82%   |
| Intel Wireless 8265 / 8275                                        | 14        | 2.64%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 2.64%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.26%   |
| Intel Wireless 7265                                               | 11        | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 9         | 1.69%   |
| Intel Wireless 7260                                               | 9         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 1.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 1.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.51%   |
| Intel Centrino Ultimate-N 6300                                    | 8         | 1.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.32%   |
| Intel Wireless 8260                                               | 7         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.94%   |
| Intel Wireless 3160                                               | 5         | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 4         | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 155       | 54.01%  |
| Qualcomm Atheros      | 50        | 17.42%  |
| Realtek Semiconductor | 36        | 12.54%  |
| Broadcom              | 20        | 6.97%   |
| MediaTek              | 9         | 3.14%   |
| Broadcom Limited      | 9         | 3.14%   |
| TP-Link               | 2         | 0.7%    |
| Xiaomi                | 1         | 0.35%   |
| Sierra Wireless       | 1         | 0.35%   |
| Ralink Technology     | 1         | 0.35%   |
| Ralink                | 1         | 0.35%   |
| D-Link                | 1         | 0.35%   |
| ASUSTek Computer      | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 5.54%   |
| Intel Wireless 3165                                            | 15        | 5.19%   |
| Intel Wireless 8265 / 8275                                     | 14        | 4.84%   |
| Intel Wi-Fi 6 AX201                                            | 14        | 4.84%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 4.15%   |
| Intel Wireless 7265                                            | 11        | 3.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 11        | 3.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 3.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 9         | 3.11%   |
| Intel Wireless 7260                                            | 9         | 3.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 9         | 3.11%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 3.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 2.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 8         | 2.77%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 2.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 2.42%   |
| Intel Wireless 8260                                            | 7         | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.73%   |
| Intel Wireless 3160                                            | 5         | 1.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 1.38%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 4         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 1.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.04%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.04%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 3         | 1.04%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 1.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.69%   |
| Intel Wireless-AC 9260                                         | 2         | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 145       | 61.44%  |
| Intel                                  | 59        | 25%     |
| Qualcomm Atheros                       | 14        | 5.93%   |
| Marvell Technology Group               | 5         | 2.12%   |
| Samsung Electronics                    | 4         | 1.69%   |
| Broadcom                               | 4         | 1.69%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.42%   |
| Qualcomm                               | 1         | 0.42%   |
| Huawei Technologies                    | 1         | 0.42%   |
| Hewlett-Packard                        | 1         | 0.42%   |
| Foxconn / Hon Hai                      | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 108       | 45%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 25        | 10.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.67%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 2.92%   |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 2.5%    |
| Intel Ethernet Connection I218-LM                                              | 5         | 2.08%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 1.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 4         | 1.67%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.67%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.83%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.83%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.83%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.83%   |
| Sony Ericsson Mobile AB D6503                                                  | 1         | 0.42%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.42%   |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.42%   |
| Qualcomm Fairphone 4 5G                                                        | 1         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.42%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.42%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1         | 0.42%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.42%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.42%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.42%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.42%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.42%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 278       | 54.72%  |
| Ethernet | 228       | 44.88%  |
| Modem    | 2         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 242       | 82.03%  |
| Ethernet | 53        | 17.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 219       | 78.49%  |
| 1     | 58        | 20.79%  |
| 3     | 1         | 0.36%   |
| 0     | 1         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 223       | 77.7%   |
| Yes  | 64        | 22.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 128       | 52.03%  |
| Qualcomm Atheros Communications | 27        | 10.98%  |
| Realtek Semiconductor           | 24        | 9.76%   |
| Broadcom                        | 19        | 7.72%   |
| IMC Networks                    | 13        | 5.28%   |
| Lite-On Technology              | 12        | 4.88%   |
| Apple                           | 5         | 2.03%   |
| Hewlett-Packard                 | 4         | 1.63%   |
| Foxconn / Hon Hai               | 4         | 1.63%   |
| Dell                            | 4         | 1.63%   |
| Toshiba                         | 1         | 0.41%   |
| Ralink                          | 1         | 0.41%   |
| Opticis                         | 1         | 0.41%   |
| MediaTek                        | 1         | 0.41%   |
| Cambridge Silicon Radio         | 1         | 0.41%   |
| Alps Electric                   | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 56        | 22.67%  |
| Intel AX201 Bluetooth                             | 25        | 10.12%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 24        | 9.72%   |
| Qualcomm Atheros  Bluetooth Device                | 17        | 6.88%   |
| Realtek Bluetooth Radio                           | 15        | 6.07%   |
| Intel AX200 Bluetooth                             | 12        | 4.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 2.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 6         | 2.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 4         | 1.62%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 1.62%   |
| IMC Networks Wireless_Device                      | 4         | 1.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 4         | 1.62%   |
| Apple Bluetooth Host Controller                   | 4         | 1.62%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 3         | 1.21%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 3         | 1.21%   |
| IMC Networks Bluetooth Radio                      | 3         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                  | 3         | 1.21%   |
| Broadcom HP Portable SoftSailing                  | 3         | 1.21%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 3         | 1.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 0.81%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 2         | 0.81%   |
| Lite-On Wireless_Device                           | 2         | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 2         | 0.81%   |
| Intel Bluetooth Device                            | 2         | 0.81%   |
| Intel AX210 Bluetooth                             | 2         | 0.81%   |
| IMC Networks Bluetooth Device                     | 2         | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                 | 2         | 0.81%   |
| Dell DW375 Bluetooth Module                       | 2         | 0.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 2         | 0.81%   |
| Toshiba Bluetooth USB Host Controller             | 1         | 0.4%    |
| Realtek RTL8723B Bluetooth                        | 1         | 0.4%    |
| Ralink RT3290 Bluetooth                           | 1         | 0.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.4%    |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.4%    |
| Opticis Bluetooth Radio                           | 1         | 0.4%    |
| MediaTek Wireless_Device                          | 1         | 0.4%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 1         | 0.4%    |
| Lite-On Bluetooth Radio                           | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 242       | 72.24%  |
| Nvidia                 | 49        | 14.63%  |
| AMD                    | 35        | 10.45%  |
| Realtek Semiconductor  | 2         | 0.6%    |
| Plantronics            | 1         | 0.3%    |
| OPPO Electronics       | 1         | 0.3%    |
| JMTek                  | 1         | 0.3%    |
| GN Netcom              | 1         | 0.3%    |
| Generalplus Technology | 1         | 0.3%    |
| Apple                  | 1         | 0.3%    |
| Unknown                | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 47        | 11.6%   |
| AMD Family 17h/19h HD Audio Controller                                     | 34        | 8.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 31        | 7.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 4.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 4.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 3.95%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 3.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 3.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 3.7%    |
| Intel Broadwell-U Audio Controller                                         | 15        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 3.46%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.48%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.48%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.48%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.99%   |
| Nvidia Audio device                                                        | 4         | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.99%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 0.99%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.74%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.49%   |
| Nvidia GF106 High Definition Audio Controller                              | 2         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 62        | 28.97%  |
| SK hynix              | 46        | 21.5%   |
| Kingston              | 34        | 15.89%  |
| Micron Technology     | 32        | 14.95%  |
| Crucial               | 8         | 3.74%   |
| Unknown               | 6         | 2.8%    |
| Ramaxel Technology    | 6         | 2.8%    |
| G.Skill               | 4         | 1.87%   |
| Corsair               | 4         | 1.87%   |
| Elpida                | 3         | 1.4%    |
| A-DATA Technology     | 3         | 1.4%    |
| Apacer                | 2         | 0.93%   |
| Unknown (7FE0)        | 1         | 0.47%   |
| Team                  | 1         | 0.47%   |
| Kingmax Semiconductor | 1         | 0.47%   |
| Kingmax               | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.16%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 2.16%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 1.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.72%   |
| Kingston RAM LV32D4S2S8HD-8 8192MB SODIMM DDR4 3200MT/s          | 4         | 1.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.29%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 1.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.29%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 3         | 1.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.86%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.86%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.86%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.86%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.86%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.86%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 2         | 0.86%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.86%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.86%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.86%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.86%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.86%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Micron RAM 53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s   | 2         | 0.86%   |
| Kingston RAM 99U5428-040.A01LF 4096MB SODIMM DDR3 1334MT/s       | 2         | 0.86%   |
| G.Skill RAM F4-2666C19-8GRS 8GB SODIMM DDR4 2667MT/s             | 2         | 0.86%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 0.86%   |
| Crucial RAM CT4G4SFS824A.C8FF 4GB SODIMM DDR4 2400MT/s           | 2         | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 100       | 59.17%  |
| DDR3   | 51        | 30.18%  |
| LPDDR4 | 8         | 4.73%   |
| LPDDR3 | 3         | 1.78%   |
| LPDDR5 | 2         | 1.18%   |
| DDR5   | 2         | 1.18%   |
| DDR2   | 2         | 1.18%   |
| SDRAM  | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 155       | 91.18%  |
| Row Of Chips | 15        | 8.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 74        | 40.44%  |
| 4096  | 69        | 37.7%   |
| 16384 | 25        | 13.66%  |
| 2048  | 13        | 7.1%    |
| 32768 | 1         | 0.55%   |
| 1024  | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 50        | 26.74%  |
| 3200    | 41        | 21.93%  |
| 1600    | 39        | 20.86%  |
| 2400    | 17        | 9.09%   |
| 2133    | 7         | 3.74%   |
| 1334    | 6         | 3.21%   |
| 1333    | 5         | 2.67%   |
| 1867    | 4         | 2.14%   |
| 8400    | 3         | 1.6%    |
| 4267    | 3         | 1.6%    |
| 6400    | 2         | 1.07%   |
| 4800    | 2         | 1.07%   |
| 667     | 2         | 1.07%   |
| 4266    | 1         | 0.53%   |
| 4199    | 1         | 0.53%   |
| 3266    | 1         | 0.53%   |
| 2933    | 1         | 0.53%   |
| 1067    | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| MIIIW  | 1         | 50%     |
| Canon  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| MIIIW MW Keyboard Air Mini | 1         | 50%     |
| Canon LBP6030w/6018w       | 1         | 50%     |

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
| Chicony Electronics                    | 56        | 22.49%  |
| Microdia                               | 40        | 16.06%  |
| IMC Networks                           | 35        | 14.06%  |
| Sunplus Innovation Technology          | 26        | 10.44%  |
| Realtek Semiconductor                  | 18        | 7.23%   |
| Quanta                                 | 11        | 4.42%   |
| Acer                                   | 11        | 4.42%   |
| Syntek                                 | 9         | 3.61%   |
| Lite-On Technology                     | 7         | 2.81%   |
| Suyin                                  | 5         | 2.01%   |
| Bison Electronics                      | 5         | 2.01%   |
| Apple                                  | 5         | 2.01%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.61%   |
| Luxvisions Innotech Limited            | 3         | 1.2%    |
| Logitech                               | 3         | 1.2%    |
| Silicon Motion                         | 2         | 0.8%    |
| Ricoh                                  | 2         | 0.8%    |
| Alcor Micro                            | 2         | 0.8%    |
| Sonix Technology                       | 1         | 0.4%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| Denron                                 | 1         | 0.4%    |
| ALi                                    | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 20        | 8.03%   |
| Chicony Integrated Camera                     | 16        | 6.43%   |
| Sunplus Integrated_Webcam_HD                  | 13        | 5.22%   |
| Realtek Integrated_Webcam_HD                  | 10        | 4.02%   |
| IMC Networks Integrated Camera                | 10        | 4.02%   |
| Syntek Integrated Camera                      | 7         | 2.81%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 2.81%   |
| Chicony HD WebCam                             | 7         | 2.81%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 6         | 2.41%   |
| Microdia Laptop_Integrated_Webcam_HD          | 5         | 2.01%   |
| Microdia Integrated Webcam                    | 5         | 2.01%   |
| Chicony HP HD Camera                          | 5         | 2.01%   |
| Acer Integrated Camera                        | 5         | 2.01%   |
| Realtek Integrated Webcam                     | 4         | 1.61%   |
| Chicony HP TrueVision HD Camera               | 4         | 1.61%   |
| Bison ThinkPad Integrated Camera              | 4         | 1.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 3         | 1.2%    |
| Quanta VGA WebCam                             | 3         | 1.2%    |
| Quanta HP TrueVision HD Camera                | 3         | 1.2%    |
| Lite-On Integrated Camera                     | 3         | 1.2%    |
| IMC Networks VGA UVC WebCam                   | 3         | 1.2%    |
| IMC Networks USB2.0 UVC HD Webcam             | 3         | 1.2%    |
| Chicony Integrated HP HD Webcam               | 3         | 1.2%    |
| Chicony HP HD Webcam                          | 3         | 1.2%    |
| Chicony HD User Facing                        | 3         | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 3         | 1.2%    |
| Acer SunplusIT Integrated Camera              | 3         | 1.2%    |
| Syntek Lenovo EasyCamera                      | 2         | 0.8%    |
| Suyin Laptop_Integrated_Webcam_HD             | 2         | 0.8%    |
| Sunplus Asus Webcam                           | 2         | 0.8%    |
| Quanta HP HD Camera                           | 2         | 0.8%    |
| Microdia Webcam Vitade AF                     | 2         | 0.8%    |
| Microdia USB 2.0 Camera                       | 2         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_E4HD        | 2         | 0.8%    |
| Microdia Integrated Webcam HD                 | 2         | 0.8%    |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.8%    |
| Lite-On HP HD Camera                          | 2         | 0.8%    |
| IMC Networks USB Camera                       | 2         | 0.8%    |
| Chicony TOSHIBA Web Camera - HD               | 2         | 0.8%    |
| Apple FaceTime HD Camera                      | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 33        | 52.38%  |
| Synaptics                  | 12        | 19.05%  |
| Shenzhen Goodix Technology | 11        | 17.46%  |
| LighTuning Technology      | 2         | 3.17%   |
| Elan Microelectronics      | 2         | 3.17%   |
| Upek                       | 1         | 1.59%   |
| STMicroelectronics         | 1         | 1.59%   |
| Samsung Electronics        | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 12.7%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 6.35%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 6.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 6.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 6.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.17%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 3.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.17%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.59%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.59%   |
| Synaptics UWP WBDI                                                         | 1         | 1.59%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.59%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.59%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.59%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 81.82%  |
| Upek        | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 45.45%  |
| Broadcom 5880                                                                | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 58200                                                               | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 173       | 60.49%  |
| 1     | 95        | 33.22%  |
| 2     | 15        | 5.24%   |
| 3     | 2         | 0.7%    |
| 5     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 47.33%  |
| Graphics card            | 20        | 15.27%  |
| Net/wireless             | 11        | 8.4%    |
| Chipcard                 | 11        | 8.4%    |
| Multimedia controller    | 7         | 5.34%   |
| Net/ethernet             | 4         | 3.05%   |
| Camera                   | 4         | 3.05%   |
| Bluetooth                | 4         | 3.05%   |
| Communication controller | 3         | 2.29%   |
| Storage                  | 2         | 1.53%   |
| Card reader              | 2         | 1.53%   |
| Sound                    | 1         | 0.76%   |

