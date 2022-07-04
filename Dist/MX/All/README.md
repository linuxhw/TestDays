MX - Tested Hardware & Statistics
---------------------------------

A project to collect tested hardware configurations for MX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX/Desktop/README.md) and [notebooks](/Dist/MX/Notebook/README.md).

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

Total: 428

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [77c632ea8e](https://linux-hardware.org/?probe=77c632ea8e) | Jul 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | Desktop     | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c21cd1f8f3](https://linux-hardware.org/?probe=c21cd1f8f3) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [03878be4ec](https://linux-hardware.org/?probe=03878be4ec) | Apr 20, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Gigabyte      | P35-DS3P                    | Desktop     | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Acer          | Extensa 5630                | Notebook    | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [ecc5ad7332](https://linux-hardware.org/?probe=ecc5ad7332) | Feb 25, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [d0ba3786b2](https://linux-hardware.org/?probe=d0ba3786b2) | Feb 03, 2022 |
| HP            | ProBook 6460b               | Notebook    | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Intel         | H81                         | Desktop     | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Acer          | Spin SP111-31               | Convertible | [21bfc2a904](https://linux-hardware.org/?probe=21bfc2a904) | Jan 16, 2022 |
| IBM           | 8183B2U                     | Desktop     | [d070680dfb](https://linux-hardware.org/?probe=d070680dfb) | Jan 14, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [52e09bab91](https://linux-hardware.org/?probe=52e09bab91) | Jan 02, 2022 |
| HP            | 2000                        | Notebook    | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Toshiba       | Satellite L850-CJK          | Notebook    | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | Unknown                     | Notebook    | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| ECS           | A55F-M3                     | Desktop     | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| Google        | Akemi                       | Notebook    | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| MSI           | B460M PRO                   | Desktop     | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                     | Desktop     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Dell          | Latitude E7450              | Notebook    | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Dell          | Latitude 3190               | Notebook    | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Lenovo        | ThinkPad L520 78595VG       | Notebook    | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [08e803937e](https://linux-hardware.org/?probe=08e803937e) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| HP            | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Sony          | SVT13115FBS                 | Notebook    | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| GreatWall     | U320                        | Desktop     | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                        | Desktop     | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | Notebook    | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [536f6d67e3](https://linux-hardware.org/?probe=536f6d67e3) | Oct 02, 2021 |
| Intel         | Unknown                     | Desktop     | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [8699437e9e](https://linux-hardware.org/?probe=8699437e9e) | Oct 01, 2021 |
| Lenovo        | ThinkPad L490 20Q5S0PR00    | Notebook    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer          | Aspire 4820T                | Notebook    | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Lenovo        | ThinkPad P51 20HJS0TP00     | Notebook    | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo        | B40-45 20394                | Notebook    | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| GTZS          | Unknown                     | Notebook    | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Pixus         | Rise                        | Notebook    | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | Notebook    | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [3c5ac88729](https://linux-hardware.org/?probe=3c5ac88729) | Aug 08, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [6949bed845](https://linux-hardware.org/?probe=6949bed845) | Aug 05, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [e94701caeb](https://linux-hardware.org/?probe=e94701caeb) | Aug 03, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| Acer          | Aspire E5-574G              | Notebook    | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| Dell          | Vostro 5515                 | Notebook    | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3340               | Notebook    | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Acer          | Aspire one                  | Notebook    | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [b85b636b73](https://linux-hardware.org/?probe=b85b636b73) | Jun 26, 2021 |
| Medion        | P6669 MD60147               | Notebook    | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | Notebook    | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| Irbis         | TW94                        | Notebook    | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Dell          | Latitude E6320              | Notebook    | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [506efba999](https://linux-hardware.org/?probe=506efba999) | May 02, 2021 |
| Acer          | Extensa 5620                | Notebook    | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | Notebook    | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | Notebook    | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | Notebook    | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Intel         | ChiefRiver                  | Notebook    | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | Notebook    | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [6d6b869b27](https://linux-hardware.org/?probe=6d6b869b27) | Apr 08, 2021 |
| HP            | Falco                       | Notebook    | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | Notebook    | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| ASUSTek       | P5K-E                       | Desktop     | [f0c435ead1](https://linux-hardware.org/?probe=f0c435ead1) | Apr 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| Dell          | 0W7H8C A02                  | Server      | [1a32b081a7](https://linux-hardware.org/?probe=1a32b081a7) | Mar 30, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [04145c0b36](https://linux-hardware.org/?probe=04145c0b36) | Mar 29, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| MSI           | MS-7210 100                 | Desktop     | [e8723eb58b](https://linux-hardware.org/?probe=e8723eb58b) | Mar 17, 2021 |
| HP            | ZBook 17 G6                 | Notebook    | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [dcc5bdef7d](https://linux-hardware.org/?probe=dcc5bdef7d) | Mar 12, 2021 |
| Dell          | Latitude E5470              | Notebook    | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | Notebook    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | Notebook    | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | Notebook    | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | Notebook    | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | Notebook    | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Lenovo        | ThinkPad E425 1198CTO       | Notebook    | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Medion        | E1235T MD99743              | Tablet      | [314aa4d200](https://linux-hardware.org/?probe=314aa4d200) | Feb 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | Mini 110-3500               | Notebook    | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP            | Notebook                    | Notebook    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| HP            | 15                          | Notebook    | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo         | P170EM                      | Notebook    | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| Dell          | Latitude D430               | Notebook    | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Dell          | Latitude E5520              | Notebook    | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | Notebook    | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | Notebook    | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [98c8e4f3a6](https://linux-hardware.org/?probe=98c8e4f3a6) | Dec 20, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [5783b64146](https://linux-hardware.org/?probe=5783b64146) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 4291WMQ       | Notebook    | [165b895e27](https://linux-hardware.org/?probe=165b895e27) | Dec 01, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [d3e3aa3011](https://linux-hardware.org/?probe=d3e3aa3011) | Nov 28, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [b51d9808ea](https://linux-hardware.org/?probe=b51d9808ea) | Nov 28, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6a65eeffd1](https://linux-hardware.org/?probe=6a65eeffd1) | Nov 27, 2020 |
| HP            | 1905                        | Desktop     | [03a91e7ecc](https://linux-hardware.org/?probe=03a91e7ecc) | Nov 27, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4f8648d28](https://linux-hardware.org/?probe=d4f8648d28) | Nov 24, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [282590eccb](https://linux-hardware.org/?probe=282590eccb) | Nov 24, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| ASRock        | H110M-ITX                   | Desktop     | [e3ca7996d2](https://linux-hardware.org/?probe=e3ca7996d2) | Nov 13, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7bb20fa67](https://linux-hardware.org/?probe=a7bb20fa67) | Nov 08, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [c4f4df2ec5](https://linux-hardware.org/?probe=c4f4df2ec5) | Oct 31, 2020 |
| Dell          | 0D28YY A00                  | Desktop     | [584335af3e](https://linux-hardware.org/?probe=584335af3e) | Oct 29, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| Dell          | Latitude 5175               | Tablet      | [5144248c79](https://linux-hardware.org/?probe=5144248c79) | Oct 19, 2020 |
| HP            | Compaq 8510p (KM229AV)      | Notebook    | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| HP            | Pavilion 15                 | Notebook    | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| Hometech      | Wi11T                       | Tablet      | [78d63aeadc](https://linux-hardware.org/?probe=78d63aeadc) | Sep 30, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Dell          | 0M9KCM A02                  | Desktop     | [3e66c830f8](https://linux-hardware.org/?probe=3e66c830f8) | Sep 22, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [a5f308c899](https://linux-hardware.org/?probe=a5f308c899) | Sep 21, 2020 |
| Lenovo        | ThinkPad T60 20085TG        | Notebook    | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| HP            | 838B 0100                   | All in one  | [c3133d1a1c](https://linux-hardware.org/?probe=c3133d1a1c) | Sep 09, 2020 |
| HP            | 8265                        | Desktop     | [38f924e8f9](https://linux-hardware.org/?probe=38f924e8f9) | Sep 07, 2020 |
| Teclast       | F5                          | Convertible | [1003072bc5](https://linux-hardware.org/?probe=1003072bc5) | Sep 06, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire A114-32              | Notebook    | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [f138fd7e0c](https://linux-hardware.org/?probe=f138fd7e0c) | Aug 09, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [e01126d9bd](https://linux-hardware.org/?probe=e01126d9bd) | Aug 06, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [7a48a3ced3](https://linux-hardware.org/?probe=7a48a3ced3) | Aug 06, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2f71e9b242](https://linux-hardware.org/?probe=2f71e9b242) | Aug 03, 2020 |
| HP            | 3031h                       | Desktop     | [205dd10b09](https://linux-hardware.org/?probe=205dd10b09) | Jul 29, 2020 |
| HP            | 3031h                       | Desktop     | [22ebc88fac](https://linux-hardware.org/?probe=22ebc88fac) | Jul 29, 2020 |
| HP            | Pavilion dv7                | Notebook    | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| Sony          | VPCF23P1E                   | Notebook    | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | Notebook    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | Notebook    | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| MSI           | 970A-G43                    | Desktop     | [ada20a047e](https://linux-hardware.org/?probe=ada20a047e) | May 27, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo        | B590 20206                  | Notebook    | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [901dfafdbf](https://linux-hardware.org/?probe=901dfafdbf) | May 21, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | Notebook    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [34335c5fb5](https://linux-hardware.org/?probe=34335c5fb5) | Apr 24, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Samsung       | R780/R778                   | Notebook    | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [0357ef50d4](https://linux-hardware.org/?probe=0357ef50d4) | Apr 05, 2020 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [60ae29c5ac](https://linux-hardware.org/?probe=60ae29c5ac) | Apr 04, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | Z97-E                       | Desktop     | [42c2810369](https://linux-hardware.org/?probe=42c2810369) | Apr 03, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| MSI           | 760GM-P23                   | Desktop     | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [67d9f2023b](https://linux-hardware.org/?probe=67d9f2023b) | Apr 01, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [104b035076](https://linux-hardware.org/?probe=104b035076) | Apr 01, 2020 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [617031b37d](https://linux-hardware.org/?probe=617031b37d) | Mar 28, 2020 |
| Clevo         | P150HMx                     | Notebook    | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [73690787f9](https://linux-hardware.org/?probe=73690787f9) | Mar 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| Dell          | 0F373D A00                  | Desktop     | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | X455LAB                     | Notebook    | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook      | W65_W67RZ1                  | Notebook    | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | Notebook    | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1243c4a0d9](https://linux-hardware.org/?probe=1243c4a0d9) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | Notebook    | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| HP            | 1790                        | Desktop     | [68a167efd3](https://linux-hardware.org/?probe=68a167efd3) | Mar 24, 2020 |
| Medion        | Akoya E1318T                | Notebook    | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |
| Dell          | Latitude 3190               | Notebook    | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [296f21e934](https://linux-hardware.org/?probe=296f21e934) | Mar 03, 2020 |
| Acer          | Aspire 8943G                | Notebook    | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| ASUSTek       | M4A77T                      | Desktop     | [75d0b42f08](https://linux-hardware.org/?probe=75d0b42f08) | Mar 01, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [370f5d5063](https://linux-hardware.org/?probe=370f5d5063) | Feb 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T11... | Notebook    | [9c888bfdde](https://linux-hardware.org/?probe=9c888bfdde) | Feb 11, 2020 |
| Lenovo        | ThinkPad X201 3680MY9       | Notebook    | [26a7c0e493](https://linux-hardware.org/?probe=26a7c0e493) | Feb 09, 2020 |
| Google        | Gnawty                      | Notebook    | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | Notebook    | [8865e9546b](https://linux-hardware.org/?probe=8865e9546b) | Feb 03, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | Notebook    | [f4779c95ce](https://linux-hardware.org/?probe=f4779c95ce) | Feb 03, 2020 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ed464b4172](https://linux-hardware.org/?probe=ed464b4172) | Jan 23, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [f703814098](https://linux-hardware.org/?probe=f703814098) | Jan 23, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [48912b8dc6](https://linux-hardware.org/?probe=48912b8dc6) | Jan 19, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASUSTek       | TUF Gaming FX505GT_TUF50... | Notebook    | [0abd5b1d73](https://linux-hardware.org/?probe=0abd5b1d73) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| Toshiba       | Satellite P875              | Notebook    | [b267e93d40](https://linux-hardware.org/?probe=b267e93d40) | Jan 15, 2020 |
| Toshiba       | Satellite P875              | Notebook    | [7e579fcba2](https://linux-hardware.org/?probe=7e579fcba2) | Jan 15, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [811669dbdd](https://linux-hardware.org/?probe=811669dbdd) | Jan 13, 2020 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [8a0171b4b0](https://linux-hardware.org/?probe=8a0171b4b0) | Jan 13, 2020 |
| Gateway       | SX2185                      | Desktop     | [74f9db3262](https://linux-hardware.org/?probe=74f9db3262) | Jan 13, 2020 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [0a8865c437](https://linux-hardware.org/?probe=0a8865c437) | Jan 13, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [f10553e785](https://linux-hardware.org/?probe=f10553e785) | Jan 13, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [aa52528043](https://linux-hardware.org/?probe=aa52528043) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [3c957a3758](https://linux-hardware.org/?probe=3c957a3758) | Dec 23, 2019 |
| HP            | Pavilion g6                 | Notebook    | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [2a979257ab](https://linux-hardware.org/?probe=2a979257ab) | Dec 21, 2019 |
| MSI           | MS-7199                     | Desktop     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [b7165ade10](https://linux-hardware.org/?probe=b7165ade10) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | Notebook    | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| Dell          | G3 3579                     | Notebook    | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | Notebook    | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [c96e6bc37c](https://linux-hardware.org/?probe=c96e6bc37c) | Dec 02, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [02ae0c5f5b](https://linux-hardware.org/?probe=02ae0c5f5b) | Dec 02, 2019 |
| MSI           | MS-N033                     | Notebook    | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| ASUSTek       | 1005HA                      | Notebook    | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| MSI           | B75MA-E33                   | Desktop     | [a08cc9782c](https://linux-hardware.org/?probe=a08cc9782c) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | Notebook    | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | Notebook    | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| Gigabyte      | P43-ES3G                    | Desktop     | [96fa353482](https://linux-hardware.org/?probe=96fa353482) | Nov 07, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [585b07ffaf](https://linux-hardware.org/?probe=585b07ffaf) | Nov 04, 2019 |
| ASUSTek       | X101CH                      | Notebook    | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | Notebook    | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | Notebook    | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | Notebook    | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| Dell          | 0F8096                      | Desktop     | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| ZOTAC         | ZBOX-ID18                   | Mini pc     | [4c4d77145b](https://linux-hardware.org/?probe=4c4d77145b) | Oct 20, 2019 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [71373d2071](https://linux-hardware.org/?probe=71373d2071) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| HP            | Pavilion g6                 | Notebook    | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [13dbc6f66d](https://linux-hardware.org/?probe=13dbc6f66d) | Oct 06, 2019 |
| Lenovo        | ThinkPad X220 4291F52       | Notebook    | [e024139431](https://linux-hardware.org/?probe=e024139431) | Aug 29, 2019 |
| Lenovo        | ThinkPad X201s 5413A19      | Notebook    | [673c3629dc](https://linux-hardware.org/?probe=673c3629dc) | Aug 22, 2019 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [acbec08287](https://linux-hardware.org/?probe=acbec08287) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [6a9aa2dd84](https://linux-hardware.org/?probe=6a9aa2dd84) | Jul 22, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [bf82fba8fd](https://linux-hardware.org/?probe=bf82fba8fd) | Apr 29, 2019 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [e42fd626b2](https://linux-hardware.org/?probe=e42fd626b2) | Apr 23, 2019 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [8469904453](https://linux-hardware.org/?probe=8469904453) | Apr 17, 2019 |
| ASUSTek       | K55VM                       | Notebook    | [e967dd6404](https://linux-hardware.org/?probe=e967dd6404) | Mar 27, 2019 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [c68bd6bce7](https://linux-hardware.org/?probe=c68bd6bce7) | Feb 23, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [67b484c4a0](https://linux-hardware.org/?probe=67b484c4a0) | Jan 19, 2019 |
| Acer          | Aspire C22-760              | All in one  | [ff0b5db4bf](https://linux-hardware.org/?probe=ff0b5db4bf) | Dec 18, 2018 |
| Acer          | Aspire C22-760              | All in one  | [7909d2b661](https://linux-hardware.org/?probe=7909d2b661) | Nov 09, 2018 |
| Toshiba       | Satellite C70-B             | Notebook    | [9b54677f2e](https://linux-hardware.org/?probe=9b54677f2e) | Oct 27, 2018 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [ec89febb0c](https://linux-hardware.org/?probe=ec89febb0c) | Oct 27, 2018 |
| Dell          | Inspiron ME051              | Notebook    | [f789720dc4](https://linux-hardware.org/?probe=f789720dc4) | Nov 26, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| MX 19          | 137       | 40.77%  |
| MX 21          | 94        | 27.98%  |
| MX 20          | 72        | 21.43%  |
| MX 18          | 27        | 8.04%   |
| MX 17          | 4         | 1.19%   |
| MX 16-migrated | 1         | 0.3%    |
| MX 16          | 1         | 0.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MX   | 325       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 55        | 15.36%  |
| 5.10.0-5mx-amd64           | 20        | 5.59%   |
| 5.10.0-9-amd64             | 18        | 5.03%   |
| 5.6.0-2-amd64              | 15        | 4.19%   |
| 5.10.0-13-amd64            | 15        | 4.19%   |
| 5.8.0-3-amd64              | 14        | 3.91%   |
| 5.14.0-4mx-amd64           | 12        | 3.35%   |
| 4.19.0-14-amd64            | 10        | 2.79%   |
| 4.19.0-17-amd64            | 9         | 2.51%   |
| 4.19.0-13-amd64            | 9         | 2.51%   |
| 5.10.0-11-amd64            | 8         | 2.23%   |
| 4.19.0-16-amd64            | 8         | 2.23%   |
| 4.19.0-5-amd64             | 7         | 1.96%   |
| 4.19.0-1-amd64             | 6         | 1.68%   |
| 5.16.0-5mx-amd64           | 5         | 1.4%    |
| 5.10.0-8mx-amd64           | 5         | 1.4%    |
| 5.10.0-15-amd64            | 5         | 1.4%    |
| 5.10.0-14-amd64            | 5         | 1.4%    |
| 4.19.0-18-amd64            | 5         | 1.4%    |
| 4.19.0-12-amd64            | 5         | 1.4%    |
| 5.8.16-antix.1-amd64-smp   | 4         | 1.12%   |
| 5.4.0-3-amd64              | 4         | 1.12%   |
| 5.10.0-10-amd64            | 4         | 1.12%   |
| 4.19.0-11-amd64            | 4         | 1.12%   |
| 4.15.0-1-amd64             | 4         | 1.12%   |
| 5.2.21-antix.2-amd64-smp   | 3         | 0.84%   |
| 4.19.0-9-amd64             | 3         | 0.84%   |
| 5.6.10-antix.1-amd64-smp   | 2         | 0.56%   |
| 5.5.0-9.1-liquorix-amd64   | 2         | 0.56%   |
| 5.4.7-antix.1-amd64-smp    | 2         | 0.56%   |
| 5.3.0-10.1-liquorix-amd64  | 2         | 0.56%   |
| 5.16.0-6mx-amd64           | 2         | 0.56%   |
| 5.16.0-4mx-amd64           | 2         | 0.56%   |
| 5.15.0-1mx-amd64           | 2         | 0.56%   |
| 5.14.0-3mx-amd64           | 2         | 0.56%   |
| 5.10.0-9mx-amd64           | 2         | 0.56%   |
| 5.10.0-8-amd64             | 2         | 0.56%   |
| 5.10.0-13-686-pae          | 2         | 0.56%   |
| 5.10.0-11-686-pae          | 2         | 0.56%   |
| 4.19.0-8-amd64             | 2         | 0.56%   |
| 4.19.0-16-686-pae          | 2         | 0.56%   |
| 4.19.0-10-amd64            | 2         | 0.56%   |
| 4.19.0-10-686-pae          | 2         | 0.56%   |
| 4.15.0-1-686-pae           | 2         | 0.56%   |
| 5.9.1-rt20avl1             | 1         | 0.28%   |
| 5.7.0-19.1-liquorix-amd64  | 1         | 0.28%   |
| 5.6.10-antix.1-686-smp-pae | 1         | 0.28%   |
| 5.6.0-15.2-liquorix-amd64  | 1         | 0.28%   |
| 5.6.0-12.1-liquorix-amd64  | 1         | 0.28%   |
| 5.5.0-7.1-liquorix-amd64   | 1         | 0.28%   |
| 5.5.0-5.1-liquorix-amd64   | 1         | 0.28%   |
| 5.5.0-10.2-liquorix-amd64  | 1         | 0.28%   |
| 5.5.0-050500rc1-lowlatency | 1         | 0.28%   |
| 5.4.10                     | 1         | 0.28%   |
| 5.4.0-antix.1-amd64-smp    | 1         | 0.28%   |
| 5.4.0-13.3-liquorix-amd64  | 1         | 0.28%   |
| 5.4.0-11.2-liquorix-amd64  | 1         | 0.28%   |
| 5.4.0-10.2-liquorix-amd64  | 1         | 0.28%   |
| 5.3.10-antix.1-amd64-smp   | 1         | 0.28%   |
| 5.3.0-2-amd64              | 1         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.19.0   | 127       | 36.81%  |
| 5.10.0   | 92        | 26.67%  |
| 5.6.0    | 17        | 4.93%   |
| 5.14.0   | 15        | 4.35%   |
| 5.8.0    | 14        | 4.06%   |
| 5.16.0   | 11        | 3.19%   |
| 5.4.0    | 8         | 2.32%   |
| 5.5.0    | 6         | 1.74%   |
| 4.15.0   | 6         | 1.74%   |
| 5.15.0   | 5         | 1.45%   |
| 5.8.16   | 4         | 1.16%   |
| 5.3.0    | 4         | 1.16%   |
| 5.2.21   | 4         | 1.16%   |
| 5.6.10   | 3         | 0.87%   |
| 5.17.0   | 3         | 0.87%   |
| 5.4.7    | 2         | 0.58%   |
| 5.11.0   | 2         | 0.58%   |
| 4.9.193  | 2         | 0.58%   |
| 4.18.0   | 2         | 0.58%   |
| 5.9.1    | 1         | 0.29%   |
| 5.7.0    | 1         | 0.29%   |
| 5.4.10   | 1         | 0.29%   |
| 5.3.10   | 1         | 0.29%   |
| 5.2.8    | 1         | 0.29%   |
| 5.2.15   | 1         | 0.29%   |
| 5.2.0    | 1         | 0.29%   |
| 5.13.0   | 1         | 0.29%   |
| 5.10.52  | 1         | 0.29%   |
| 5.10.111 | 1         | 0.29%   |
| 5.10.1   | 1         | 0.29%   |
| 5.1.2    | 1         | 0.29%   |
| 5.0.0    | 1         | 0.29%   |
| 4.9.91   | 1         | 0.29%   |
| 4.9.246  | 1         | 0.29%   |
| 4.9.189  | 1         | 0.29%   |
| 4.19.174 | 1         | 0.29%   |
| 3.16.0   | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 128       | 37.1%   |
| 5.10    | 95        | 27.54%  |
| 5.6     | 20        | 5.8%    |
| 5.8     | 18        | 5.22%   |
| 5.14    | 15        | 4.35%   |
| 5.4     | 11        | 3.19%   |
| 5.16    | 11        | 3.19%   |
| 5.2     | 7         | 2.03%   |
| 5.5     | 6         | 1.74%   |
| 4.15    | 6         | 1.74%   |
| 5.3     | 5         | 1.45%   |
| 5.15    | 5         | 1.45%   |
| 4.9     | 5         | 1.45%   |
| 5.17    | 3         | 0.87%   |
| 5.11    | 2         | 0.58%   |
| 4.18    | 2         | 0.58%   |
| 5.9     | 1         | 0.29%   |
| 5.7     | 1         | 0.29%   |
| 5.13    | 1         | 0.29%   |
| 5.1     | 1         | 0.29%   |
| 5.0     | 1         | 0.29%   |
| 3.16    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 306       | 93.87%  |
| i686   | 20        | 6.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 243       | 73.41%  |
| KDE5             | 50        | 15.11%  |
| Unknown          | 7         | 2.11%   |
| Budgie           | 5         | 1.51%   |
| MATE             | 4         | 1.21%   |
| i3               | 4         | 1.21%   |
| LXQt             | 3         | 0.91%   |
| GNOME            | 3         | 0.91%   |
| lightdm-xsession | 2         | 0.6%    |
| Cinnamon         | 2         | 0.6%    |
| X-Cinnamon       | 1         | 0.3%    |
| Trinity          | 1         | 0.3%    |
| spectrwm         | 1         | 0.3%    |
| LXDE             | 1         | 0.3%    |
| KDE4             | 1         | 0.3%    |
| KDE              | 1         | 0.3%    |
| GNOME Flashback  | 1         | 0.3%    |
| fluxbox          | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 323       | 99.38%  |
| Tty  | 2         | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 265       | 80.55%  |
| SDDM    | 42        | 12.77%  |
| TDM     | 13        | 3.95%   |
| SLiM    | 7         | 2.13%   |
| Unknown | 2         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 115       | 33.82%  |
| Unknown | 100       | 29.41%  |
| de_DE   | 26        | 7.65%   |
| en_GB   | 16        | 4.71%   |
| sk_SK   | 12        | 3.53%   |
| ru_RU   | 9         | 2.65%   |
| pt_BR   | 8         | 2.35%   |
| es_ES   | 8         | 2.35%   |
| it_IT   | 7         | 2.06%   |
| pl_PL   | 6         | 1.76%   |
| fr_FR   | 5         | 1.47%   |
| tr_TR   | 4         | 1.18%   |
| en_IE   | 3         | 0.88%   |
| en_AU   | 3         | 0.88%   |
| de_CH   | 3         | 0.88%   |
| uk_UA   | 2         | 0.59%   |
| es_MX   | 2         | 0.59%   |
| zh_CN   | 1         | 0.29%   |
| sv_SE   | 1         | 0.29%   |
| nl_NL   | 1         | 0.29%   |
| hu_HU   | 1         | 0.29%   |
| fr_CH   | 1         | 0.29%   |
| fr_BE   | 1         | 0.29%   |
| fi_FI   | 1         | 0.29%   |
| es_VE   | 1         | 0.29%   |
| es_PE   | 1         | 0.29%   |
| es_CO   | 1         | 0.29%   |
| cs_CZ   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 168       | 51.69%  |
| EFI  | 157       | 48.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 285       | 87.42%  |
| Overlay  | 26        | 7.98%   |
| Btrfs    | 9         | 2.76%   |
| Unknown  | 2         | 0.61%   |
| Xfs      | 1         | 0.31%   |
| Reiserfs | 1         | 0.31%   |
| F2fs     | 1         | 0.31%   |
| Ext3     | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 198       | 60.74%  |
| MBR     | 122       | 37.42%  |
| Unknown | 6         | 1.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 242       | 72.89%  |
| Yes       | 90        | 27.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 174       | 53.37%  |
| Yes       | 152       | 46.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 50        | 15.38%  |
| ASUSTek Computer    | 46        | 14.15%  |
| Hewlett-Packard     | 44        | 13.54%  |
| Dell                | 38        | 11.69%  |
| Gigabyte Technology | 21        | 6.46%   |
| Acer                | 20        | 6.15%   |
| MSI                 | 18        | 5.54%   |
| ASRock              | 11        | 3.38%   |
| Toshiba             | 8         | 2.46%   |
| Sony                | 8         | 2.46%   |
| Intel               | 7         | 2.15%   |
| Apple               | 7         | 2.15%   |
| Medion              | 5         | 1.54%   |
| Samsung Electronics | 4         | 1.23%   |
| Fujitsu Siemens     | 4         | 1.23%   |
| ZOTAC               | 3         | 0.92%   |
| Google              | 2         | 0.62%   |
| Clevo               | 2         | 0.62%   |
| Alienware           | 2         | 0.62%   |
| Unknown             | 2         | 0.62%   |
| TUXEDO              | 1         | 0.31%   |
| Teclast             | 1         | 0.31%   |
| Sun Microsystems    | 1         | 0.31%   |
| Radiant Systems     | 1         | 0.31%   |
| Pixus               | 1         | 0.31%   |
| Panasonic           | 1         | 0.31%   |
| Packard Bell        | 1         | 0.31%   |
| Notebook            | 1         | 0.31%   |
| Microsoft           | 1         | 0.31%   |
| Irbis               | 1         | 0.31%   |
| IBM                 | 1         | 0.31%   |
| Huanan              | 1         | 0.31%   |
| Hometech            | 1         | 0.31%   |
| GreatWall           | 1         | 0.31%   |
| Gateway             | 1         | 0.31%   |
| GALAX               | 1         | 0.31%   |
| Fujitsu             | 1         | 0.31%   |
| Framework           | 1         | 0.31%   |
| eMachines           | 1         | 0.31%   |
| efirstview          | 1         | 0.31%   |
| ECS                 | 1         | 0.31%   |
| Chuwi               | 1         | 0.31%   |
| AZW                 | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 5         | 1.54%   |
| ASUS All Series                              | 4         | 1.23%   |
| MSI MS-7A34                                  | 2         | 0.62%   |
| HP Stream Laptop 14-cb0XX                    | 2         | 0.62%   |
| HP ProBook 650 G1                            | 2         | 0.62%   |
| Dell Studio 540                              | 2         | 0.62%   |
| Dell OptiPlex 9010                           | 2         | 0.62%   |
| ASRock K8A780LM                              | 2         | 0.62%   |
| ZOTAC ZBOX-ID18                              | 1         | 0.31%   |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.31%   |
| ZOTAC ZBOX-BI320                             | 1         | 0.31%   |
| TUXEDO N7x0WU                                | 1         | 0.31%   |
| Toshiba Satellite P875                       | 1         | 0.31%   |
| Toshiba Satellite L850-CJK                   | 1         | 0.31%   |
| Toshiba Satellite C845                       | 1         | 0.31%   |
| Toshiba Satellite C70-B                      | 1         | 0.31%   |
| Toshiba Satellite C660                       | 1         | 0.31%   |
| Toshiba Satellite C50-A-12K                  | 1         | 0.31%   |
| Toshiba Satellite A300                       | 1         | 0.31%   |
| Toshiba PORTEGE R705                         | 1         | 0.31%   |
| Teclast F5                                   | 1         | 0.31%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.31%   |
| Sony VPCSB1V9R                               | 1         | 0.31%   |
| Sony VPCF23P1E                               | 1         | 0.31%   |
| Sony VPCF119FX                               | 1         | 0.31%   |
| Sony VPCEH2N1E                               | 1         | 0.31%   |
| Sony VPCEC3S1E                               | 1         | 0.31%   |
| Sony VGN-NR310FH                             | 1         | 0.31%   |
| Sony SVT13115FBS                             | 1         | 0.31%   |
| Sony SVE1513Q1ESI                            | 1         | 0.31%   |
| Samsung R780/R778                            | 1         | 0.31%   |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 0.31%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.31%   |
| Samsung 305E4A/305E5A/305E7A                 | 1         | 0.31%   |
| Radiant Systems P845                         | 1         | 0.31%   |
| Pixus Rise                                   | 1         | 0.31%   |
| Panasonic CF-C1BT02EGE                       | 1         | 0.31%   |
| Packard Bell EasyNote TE11HC                 | 1         | 0.31%   |
| Notebook W65_W67RZ1                          | 1         | 0.31%   |
| MSI MS-N033                                  | 1         | 0.31%   |
| MSI MS-7C94                                  | 1         | 0.31%   |
| MSI MS-7C88                                  | 1         | 0.31%   |
| MSI MS-7C56                                  | 1         | 0.31%   |
| MSI MS-7B86                                  | 1         | 0.31%   |
| MSI MS-7917                                  | 1         | 0.31%   |
| MSI MS-7815                                  | 1         | 0.31%   |
| MSI MS-7808                                  | 1         | 0.31%   |
| MSI MS-7758                                  | 1         | 0.31%   |
| MSI MS-7693                                  | 1         | 0.31%   |
| MSI MS-7641                                  | 1         | 0.31%   |
| MSI MS-7199                                  | 1         | 0.31%   |
| MSI GV62 8RD                                 | 1         | 0.31%   |
| MSI GP63 Leopard 8RD                         | 1         | 0.31%   |
| MSI GEG                                      | 1         | 0.31%   |
| MSI Alpha 15 B5EEK                           | 1         | 0.31%   |
| Microsoft Surface Pro 7                      | 1         | 0.31%   |
| Medion P6669 MD60147                         | 1         | 0.31%   |
| Medion E6234                                 | 1         | 0.31%   |
| Medion E14304                                | 1         | 0.31%   |
| Medion E1235T MD99743                        | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 30        | 9.23%   |
| Acer Aspire             | 13        | 4%      |
| Dell Latitude           | 12        | 3.69%   |
| Dell OptiPlex           | 9         | 2.77%   |
| Dell Inspiron           | 8         | 2.46%   |
| Toshiba Satellite       | 7         | 2.15%   |
| HP ProBook              | 6         | 1.85%   |
| HP Pavilion             | 6         | 1.85%   |
| Lenovo IdeaPad          | 5         | 1.54%   |
| HP EliteBook            | 5         | 1.54%   |
| ASUS TUF                | 5         | 1.54%   |
| ASUS ROG                | 5         | 1.54%   |
| Unknown                 | 5         | 1.54%   |
| ASUS PRIME              | 4         | 1.23%   |
| ASUS All                | 4         | 1.23%   |
| HP Spectre              | 3         | 0.92%   |
| HP Compaq               | 3         | 0.92%   |
| MSI MS-7A34             | 2         | 0.62%   |
| Lenovo B590             | 2         | 0.62%   |
| HP ZBook                | 2         | 0.62%   |
| HP Stream               | 2         | 0.62%   |
| HP Laptop               | 2         | 0.62%   |
| HP ENVY                 | 2         | 0.62%   |
| Gigabyte Z390           | 2         | 0.62%   |
| Gigabyte B550M          | 2         | 0.62%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.62%   |
| Dell Vostro             | 2         | 0.62%   |
| Dell Studio             | 2         | 0.62%   |
| ASUS VivoBook           | 2         | 0.62%   |
| ASRock K8A780LM         | 2         | 0.62%   |
| Acer Extensa            | 2         | 0.62%   |
| ZOTAC ZBOX-ID18         | 1         | 0.31%   |
| ZOTAC ZBOX-ECM73070C    | 1         | 0.31%   |
| ZOTAC ZBOX-BI320        | 1         | 0.31%   |
| TUXEDO N7x0WU           | 1         | 0.31%   |
| Toshiba PORTEGE         | 1         | 0.31%   |
| Teclast F5              | 1         | 0.31%   |
| Sun Microsystems Sun    | 1         | 0.31%   |
| Sony VPCSB1V9R          | 1         | 0.31%   |
| Sony VPCF23P1E          | 1         | 0.31%   |
| Sony VPCF119FX          | 1         | 0.31%   |
| Sony VPCEH2N1E          | 1         | 0.31%   |
| Sony VPCEC3S1E          | 1         | 0.31%   |
| Sony VGN-NR310FH        | 1         | 0.31%   |
| Sony SVT13115FBS        | 1         | 0.31%   |
| Sony SVE1513Q1ESI       | 1         | 0.31%   |
| Samsung R780            | 1         | 0.31%   |
| Samsung 350V5C          | 1         | 0.31%   |
| Samsung 340XAA          | 1         | 0.31%   |
| Samsung 305E4A          | 1         | 0.31%   |
| Radiant Systems P845    | 1         | 0.31%   |
| Pixus Rise              | 1         | 0.31%   |
| Panasonic CF-C1BT02EGE  | 1         | 0.31%   |
| Packard Bell EasyNote   | 1         | 0.31%   |
| Notebook W65            | 1         | 0.31%   |
| MSI MS-N033             | 1         | 0.31%   |
| MSI MS-7C94             | 1         | 0.31%   |
| MSI MS-7C88             | 1         | 0.31%   |
| MSI MS-7C56             | 1         | 0.31%   |
| MSI MS-7B86             | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 31        | 9.54%   |
| 2012    | 29        | 8.92%   |
| 2011    | 28        | 8.62%   |
| 2010    | 26        | 8%      |
| 2013    | 25        | 7.69%   |
| 2014    | 22        | 6.77%   |
| 2020    | 21        | 6.46%   |
| 2021    | 20        | 6.15%   |
| 2019    | 20        | 6.15%   |
| 2016    | 19        | 5.85%   |
| 2017    | 18        | 5.54%   |
| 2015    | 16        | 4.92%   |
| 2008    | 16        | 4.92%   |
| 2009    | 11        | 3.38%   |
| 2007    | 10        | 3.08%   |
| 2006    | 6         | 1.85%   |
| 2005    | 4         | 1.23%   |
| 2022    | 2         | 0.62%   |
| Unknown | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 193       | 59.38%  |
| Desktop     | 102       | 31.38%  |
| Convertible | 8         | 2.46%   |
| Mini pc     | 8         | 2.46%   |
| Tablet      | 7         | 2.15%   |
| All in one  | 4         | 1.23%   |
| Server      | 3         | 0.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 324       | 99.69%  |
| Enabled  | 1         | 0.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 322       | 99.08%  |
| Yes  | 3         | 0.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 78        | 23.85%  |
| 8.01-16.0   | 69        | 21.1%   |
| 3.01-4.0    | 58        | 17.74%  |
| 16.01-24.0  | 54        | 16.51%  |
| 1.01-2.0    | 25        | 7.65%   |
| 32.01-64.0  | 22        | 6.73%   |
| 2.01-3.0    | 9         | 2.75%   |
| 0.51-1.0    | 6         | 1.83%   |
| 24.01-32.0  | 4         | 1.22%   |
| 64.01-256.0 | 2         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 130       | 37.79%  |
| 2.01-3.0   | 82        | 23.84%  |
| 3.01-4.0   | 44        | 12.79%  |
| 0.51-1.0   | 43        | 12.5%   |
| 4.01-8.0   | 31        | 9.01%   |
| 8.01-16.0  | 9         | 2.62%   |
| 0.01-0.5   | 4         | 1.16%   |
| 16.01-24.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 191       | 57.53%  |
| 2      | 88        | 26.51%  |
| 3      | 30        | 9.04%   |
| 4      | 10        | 3.01%   |
| 5      | 8         | 2.41%   |
| 0      | 4         | 1.2%    |
| 8      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 195       | 59.63%  |
| Yes       | 132       | 40.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 288       | 88.62%  |
| No        | 37        | 11.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 74.77%  |
| No        | 82        | 25.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 177       | 54.46%  |
| No        | 148       | 45.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 82        | 25.23%  |
| Germany     | 27        | 8.31%   |
| UK          | 18        | 5.54%   |
| Slovakia    | 16        | 4.92%   |
| Russia      | 13        | 4%      |
| Canada      | 13        | 4%      |
| Spain       | 12        | 3.69%   |
| Brazil      | 11        | 3.38%   |
| Italy       | 10        | 3.08%   |
| Poland      | 9         | 2.77%   |
| France      | 9         | 2.77%   |
| India       | 8         | 2.46%   |
| Netherlands | 7         | 2.15%   |
| Austria     | 7         | 2.15%   |
| Finland     | 6         | 1.85%   |
| Australia   | 6         | 1.85%   |
| Ukraine     | 5         | 1.54%   |
| Serbia      | 5         | 1.54%   |
| Mexico      | 5         | 1.54%   |
| Turkey      | 4         | 1.23%   |
| Switzerland | 4         | 1.23%   |
| Sweden      | 4         | 1.23%   |
| Thailand    | 3         | 0.92%   |
| Czechia     | 3         | 0.92%   |
| Belgium     | 3         | 0.92%   |
| Romania     | 2         | 0.62%   |
| Portugal    | 2         | 0.62%   |
| Philippines | 2         | 0.62%   |
| Indonesia   | 2         | 0.62%   |
| Hungary     | 2         | 0.62%   |
| Greece      | 2         | 0.62%   |
| Denmark     | 2         | 0.62%   |
| Colombia    | 2         | 0.62%   |
| China       | 2         | 0.62%   |
| Chile       | 2         | 0.62%   |
| Belarus     | 2         | 0.62%   |
| Vietnam     | 1         | 0.31%   |
| Venezuela   | 1         | 0.31%   |
| Syria       | 1         | 0.31%   |
| Peru        | 1         | 0.31%   |
| Norway      | 1         | 0.31%   |
| Nigeria     | 1         | 0.31%   |
| Malaysia    | 1         | 0.31%   |
| Latvia      | 1         | 0.31%   |
| Ireland     | 1         | 0.31%   |
| Estonia     | 1         | 0.31%   |
| Azerbaijan  | 1         | 0.31%   |
| Angola      | 1         | 0.31%   |
| Algeria     | 1         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Bratislava               | 16        | 4.79%   |
| Vienna                   | 7         | 2.1%    |
| Berlin                   | 4         | 1.2%    |
| Warsaw                   | 3         | 0.9%    |
| St Petersburg            | 3         | 0.9%    |
| Patna                    | 3         | 0.9%    |
| Oxford                   | 3         | 0.9%    |
| Munich                   | 3         | 0.9%    |
| Montreal                 | 3         | 0.9%    |
| Madrid                   | 3         | 0.9%    |
| Los Angeles              | 3         | 0.9%    |
| Belgrade                 | 3         | 0.9%    |
| Valencia                 | 2         | 0.6%    |
| Tacoma                   | 2         | 0.6%    |
| Prague                   | 2         | 0.6%    |
| Portland                 | 2         | 0.6%    |
| Orange                   | 2         | 0.6%    |
| Nashville                | 2         | 0.6%    |
| Moscow                   | 2         | 0.6%    |
| Minsk                    | 2         | 0.6%    |
| Melbourne                | 2         | 0.6%    |
| Istanbul                 | 2         | 0.6%    |
| Helsinki                 | 2         | 0.6%    |
| Ettingen                 | 2         | 0.6%    |
| Dnipro                   | 2         | 0.6%    |
| Centreville              | 2         | 0.6%    |
| Calgary                  | 2         | 0.6%    |
| Buffalo                  | 2         | 0.6%    |
| Bogotá                  | 2         | 0.6%    |
| Birmingham               | 2         | 0.6%    |
| Bengaluru                | 2         | 0.6%    |
| Bayreuth                 | 2         | 0.6%    |
| Barcelona                | 2         | 0.6%    |
| Artannes-sur-Indre       | 2         | 0.6%    |
| Ankara                   | 2         | 0.6%    |
| Amsterdam                | 2         | 0.6%    |
| Albertslund Municipality | 2         | 0.6%    |
| Zurich                   | 1         | 0.3%    |
| Yuzhno-Sakhalinsk        | 1         | 0.3%    |
| Xalapa                   | 1         | 0.3%    |
| Williamsburg             | 1         | 0.3%    |
| Wentzville               | 1         | 0.3%    |
| Waycross                 | 1         | 0.3%    |
| Warren                   | 1         | 0.3%    |
| Wadsworth                | 1         | 0.3%    |
| Volos                    | 1         | 0.3%    |
| Vitacura                 | 1         | 0.3%    |
| Virginia Beach           | 1         | 0.3%    |
| Vilhelmina               | 1         | 0.3%    |
| Vancouver                | 1         | 0.3%    |
| Vaidasoo                 | 1         | 0.3%    |
| Uelzen                   | 1         | 0.3%    |
| Tver                     | 1         | 0.3%    |
| Tupelo                   | 1         | 0.3%    |
| Trzebinia                | 1         | 0.3%    |
| Trivandrum               | 1         | 0.3%    |
| Titusville               | 1         | 0.3%    |
| Tilburg                  | 1         | 0.3%    |
| Tampa                    | 1         | 0.3%    |
| Taggia                   | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 77        | 90     | 15.78%  |
| Seagate                   | 66        | 85     | 13.52%  |
| Samsung Electronics       | 66        | 91     | 13.52%  |
| Kingston                  | 34        | 35     | 6.97%   |
| Crucial                   | 28        | 39     | 5.74%   |
| Toshiba                   | 25        | 29     | 5.12%   |
| SanDisk                   | 24        | 26     | 4.92%   |
| Unknown                   | 22        | 28     | 4.51%   |
| Hitachi                   | 22        | 26     | 4.51%   |
| SK hynix                  | 12        | 13     | 2.46%   |
| A-DATA Technology         | 11        | 13     | 2.25%   |
| Intel                     | 10        | 15     | 2.05%   |
| HGST                      | 8         | 13     | 1.64%   |
| PNY                       | 6         | 7      | 1.23%   |
| Goodram                   | 6         | 7      | 1.23%   |
| Transcend                 | 5         | 5      | 1.02%   |
| SPCC                      | 4         | 4      | 0.82%   |
| Maxtor                    | 4         | 5      | 0.82%   |
| LITEON                    | 4         | 4      | 0.82%   |
| Corsair                   | 4         | 4      | 0.82%   |
| Micron Technology         | 3         | 7      | 0.61%   |
| Fujitsu                   | 3         | 3      | 0.61%   |
| Dogfish                   | 3         | 3      | 0.61%   |
| Phison                    | 2         | 2      | 0.41%   |
| OCZ                       | 2         | 2      | 0.41%   |
| Mushkin                   | 2         | 2      | 0.41%   |
| KingSpec                  | 2         | 2      | 0.41%   |
| KingFast                  | 2         | 2      | 0.41%   |
| KingDian                  | 2         | 2      | 0.41%   |
| Gigabyte Technology       | 2         | 2      | 0.41%   |
| Apple                     | 2         | 3      | 0.41%   |
| ZTC                       | 1         | 1      | 0.2%    |
| Yeyian                    | 1         | 1      | 0.2%    |
| WDC WDS1                  | 1         | 1      | 0.2%    |
| Teclast                   | 1         | 1      | 0.2%    |
| Team                      | 1         | 1      | 0.2%    |
| Smart                     | 1         | 1      | 0.2%    |
| Silicon Motion            | 1         | 1      | 0.2%    |
| SABRENT                   | 1         | 1      | 0.2%    |
| Phison Electronics        | 1         | 2      | 0.2%    |
| Patriot                   | 1         | 1      | 0.2%    |
| Netac                     | 1         | 1      | 0.2%    |
| Micron/Crucial Technology | 1         | 1      | 0.2%    |
| LITEONIT                  | 1         | 1      | 0.2%    |
| Lexar                     | 1         | 1      | 0.2%    |
| Lenovo                    | 1         | 1      | 0.2%    |
| Intenso                   | 1         | 1      | 0.2%    |
| Indilinx                  | 1         | 3      | 0.2%    |
| IBM/Hitachi               | 1         | 1      | 0.2%    |
| HUAWEI                    | 1         | 1      | 0.2%    |
| HS-SSD-C100               | 1         | 1      | 0.2%    |
| GeIL                      | 1         | 1      | 0.2%    |
| Avant                     | 1         | 1      | 0.2%    |
| ASMT                      | 1         | 3      | 0.2%    |
| Acer                      | 1         | 1      | 0.2%    |
| Unknown                   | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 9         | 1.69%   |
| Kingston SA400S37240G 240GB SSD    | 7         | 1.31%   |
| Kingston SA400S37480G 480GB SSD    | 6         | 1.13%   |
| Seagate ST2000DM008-2FR102 2TB     | 5         | 0.94%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 0.94%   |
| Kingston SV300S37A120G 120GB SSD   | 5         | 0.94%   |
| Seagate ST4000DM004-2CV104 4TB     | 4         | 0.75%   |
| Seagate ST1000LM048-2E7172 1TB     | 4         | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB     | 4         | 0.75%   |
| Samsung SSD 970 EVO Plus 1TB       | 4         | 0.75%   |
| Samsung SSD 850 EVO 250GB          | 4         | 0.75%   |
| Kingston SA400S37120G 120GB SSD    | 4         | 0.75%   |
| Hitachi HTS543232A7A384 320GB      | 4         | 0.75%   |
| Crucial CT120BX500SSD1 120GB       | 4         | 0.75%   |
| A-DATA SP600 32GB SSD              | 4         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB           | 3         | 0.56%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 3         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 0.56%   |
| Samsung SSD 860 EVO 1TB            | 3         | 0.56%   |
| Samsung SSD 850 EVO 500GB          | 3         | 0.56%   |
| Samsung SSD 840 EVO 250GB          | 3         | 0.56%   |
| HGST HTS541010A9E680 1TB           | 3         | 0.56%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 0.56%   |
| Crucial CT1000MX500SSD1 1TB        | 3         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 2         | 0.38%   |
| WDC WD60EZRZ-00RWYB1 6TB           | 2         | 0.38%   |
| WDC WD60EFRX-68L0BN1 6TB           | 2         | 0.38%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 2         | 0.38%   |
| WDC WD30EZRX-00D8PB0 3TB           | 2         | 0.38%   |
| WDC WD30EFRX-68AX9N0 3TB           | 2         | 0.38%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 2         | 0.38%   |
| WDC WD15EARX-00PASB0 1TB           | 2         | 0.38%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB | 2         | 0.38%   |
| Unknown SDW32G  32GB               | 2         | 0.38%   |
| Unknown SD32G  32GB                | 2         | 0.38%   |
| Unknown BJTD4R  32GB               | 2         | 0.38%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.38%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.38%   |
| Toshiba MK7575GSX 752GB            | 2         | 0.38%   |
| Toshiba MK5065GSX 500GB            | 2         | 0.38%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.38%   |
| SK hynix SC311 SATA 256GB SSD      | 2         | 0.38%   |
| SK hynix HFM512GDJTNI-82A0A 512GB  | 2         | 0.38%   |
| Seagate ST3500413AS 500GB          | 2         | 0.38%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2         | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.38%   |
| SanDisk SSD PLUS 1000GB            | 2         | 0.38%   |
| SanDisk SDSSDP128G 128GB           | 2         | 0.38%   |
| SanDisk SDSSDA120G 120GB           | 2         | 0.38%   |
| Samsung SSD 980 PRO 1TB            | 2         | 0.38%   |
| Samsung SSD 970 EVO 1TB            | 2         | 0.38%   |
| Samsung SSD 960 EVO 250GB          | 2         | 0.38%   |
| Samsung SSD 870 EVO 500GB          | 2         | 0.38%   |
| Samsung SSD 860 QVO 1TB            | 2         | 0.38%   |
| Samsung SSD 860 EVO M.2 250GB      | 2         | 0.38%   |
| Samsung SSD 860 EVO 250GB          | 2         | 0.38%   |
| Samsung SSD 850 EVO 1TB            | 2         | 0.38%   |
| Samsung SSD 850 EVO 120GB          | 2         | 0.38%   |
| Samsung SSD 830 Series 128GB       | 2         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 84     | 34.74%  |
| WDC                 | 57        | 68     | 30%     |
| Hitachi             | 22        | 26     | 11.58%  |
| Toshiba             | 19        | 23     | 10%     |
| HGST                | 8         | 13     | 4.21%   |
| Samsung Electronics | 7         | 9      | 3.68%   |
| Maxtor              | 4         | 5      | 2.11%   |
| Fujitsu             | 3         | 3      | 1.58%   |
| Unknown             | 1         | 1      | 0.53%   |
| IBM/Hitachi         | 1         | 1      | 0.53%   |
| ASMT                | 1         | 3      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 54     | 19.62%  |
| Kingston            | 30        | 31     | 14.35%  |
| Crucial             | 25        | 30     | 11.96%  |
| SanDisk             | 22        | 23     | 10.53%  |
| WDC                 | 10        | 11     | 4.78%   |
| A-DATA Technology   | 10        | 12     | 4.78%   |
| Goodram             | 6         | 7      | 2.87%   |
| Transcend           | 5         | 5      | 2.39%   |
| PNY                 | 5         | 5      | 2.39%   |
| Intel               | 5         | 9      | 2.39%   |
| SPCC                | 4         | 4      | 1.91%   |
| SK hynix            | 4         | 4      | 1.91%   |
| LITEON              | 4         | 4      | 1.91%   |
| Micron Technology   | 3         | 7      | 1.44%   |
| Dogfish             | 3         | 3      | 1.44%   |
| Toshiba             | 2         | 2      | 0.96%   |
| OCZ                 | 2         | 2      | 0.96%   |
| KingSpec            | 2         | 2      | 0.96%   |
| KingFast            | 2         | 2      | 0.96%   |
| KingDian            | 2         | 2      | 0.96%   |
| Gigabyte Technology | 2         | 2      | 0.96%   |
| Apple               | 2         | 2      | 0.96%   |
| ZTC                 | 1         | 1      | 0.48%   |
| Yeyian              | 1         | 1      | 0.48%   |
| WDC WDS1            | 1         | 1      | 0.48%   |
| Teclast             | 1         | 1      | 0.48%   |
| Team                | 1         | 1      | 0.48%   |
| Smart               | 1         | 1      | 0.48%   |
| Phison              | 1         | 1      | 0.48%   |
| Patriot             | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| Mushkin             | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| Indilinx            | 1         | 3      | 0.48%   |
| HS-SSD-C100         | 1         | 1      | 0.48%   |
| GeIL                | 1         | 1      | 0.48%   |
| Corsair             | 1         | 1      | 0.48%   |
| Avant               | 1         | 1      | 0.48%   |
| Acer                | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 177       | 243    | 41.36%  |
| HDD     | 161       | 237    | 37.62%  |
| NVMe    | 64        | 85     | 14.95%  |
| MMC     | 24        | 32     | 5.61%   |
| Unknown | 2         | 2      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 265       | 471    | 73.41%  |
| NVMe | 64        | 84     | 17.73%  |
| MMC  | 24        | 32     | 6.65%   |
| SAS  | 8         | 12     | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 223       | 318    | 64.08%  |
| 0.51-1.0   | 88        | 115    | 25.29%  |
| 1.01-2.0   | 19        | 23     | 5.46%   |
| 3.01-4.0   | 7         | 8      | 2.01%   |
| 2.01-3.0   | 7         | 8      | 2.01%   |
| 4.01-10.0  | 4         | 8      | 1.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 27.38%  |
| 251-500        | 61        | 18.15%  |
| 501-1000       | 51        | 15.18%  |
| 51-100         | 41        | 12.2%   |
| 21-50          | 27        | 8.04%   |
| 1001-2000      | 23        | 6.85%   |
| More than 3000 | 18        | 5.36%   |
| 1-20           | 14        | 4.17%   |
| 2001-3000      | 7         | 2.08%   |
| Unknown        | 2         | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 127       | 37.46%  |
| 21-50          | 53        | 15.63%  |
| 101-250        | 46        | 13.57%  |
| 51-100         | 42        | 12.39%  |
| 251-500        | 32        | 9.44%   |
| 501-1000       | 16        | 4.72%   |
| 1001-2000      | 10        | 2.95%   |
| More than 3000 | 6         | 1.77%   |
| 2001-3000      | 5         | 1.47%   |
| Unknown        | 2         | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 4%      |
| Toshiba MK7575GSX 752GB                      | 2         | 3      | 2.67%   |
| A-DATA Technology SU650 240GB SSD            | 2         | 2      | 2.67%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 1.33%   |
| WDC WD5003ABYX-01WERA1 500GB                 | 1         | 1      | 1.33%   |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 1.33%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 1.33%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 1.33%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 1.33%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 1.33%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 1         | 1      | 1.33%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.33%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 1.33%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 1.33%   |
| WDC WD1600AVVS-63L2B0 160GB                  | 1         | 1      | 1.33%   |
| WDC WD15EADS-11P8B2 1TB                      | 1         | 1      | 1.33%   |
| WDC WD10EZEX-75WN4A0 1TB                     | 1         | 1      | 1.33%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1         | 1      | 1.33%   |
| WDC WD10EAVS-00D7B1 1TB                      | 1         | 1      | 1.33%   |
| WDC WD10EADS-00M2B0 1TB                      | 1         | 1      | 1.33%   |
| Toshiba MK6465GSX 640GB                      | 1         | 1      | 1.33%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 1.33%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 1.33%   |
| SPCC Solid State Disk 512GB                  | 1         | 1      | 1.33%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 1.33%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 1.33%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 1.33%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 1.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 1.33%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.33%   |
| Seagate ST3750330NS 752GB                    | 1         | 1      | 1.33%   |
| Seagate ST3500820AS 500GB                    | 1         | 1      | 1.33%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 1.33%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 1.33%   |
| Seagate ST3320413CS 320GB                    | 1         | 1      | 1.33%   |
| Seagate ST33000651NS 3TB                     | 1         | 1      | 1.33%   |
| Seagate ST31500341AS 1TB                     | 1         | 1      | 1.33%   |
| Seagate ST31000524AS 1TB                     | 1         | 1      | 1.33%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.33%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1      | 1.33%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 1.33%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 1.33%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 2      | 1.33%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 1.33%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 1.33%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 1.33%   |
| Samsung Electronics HD322GJ 320GB            | 1         | 2      | 1.33%   |
| Maxtor 6Y120M0 122GB                         | 1         | 1      | 1.33%   |
| Maxtor 6L200M0 208GB                         | 1         | 1      | 1.33%   |
| Maxtor 4K040H2 40GB                          | 1         | 1      | 1.33%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 1.33%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 3      | 1.33%   |
| IBM/Hitachi IC25N030ATCS04-0 32GB            | 1         | 1      | 1.33%   |
| Hitachi HUA722020ALA331 2TB                  | 1         | 1      | 1.33%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 1.33%   |
| Hitachi HTS545032B9SA00 320GB                | 1         | 1      | 1.33%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 1.33%   |
| Hitachi HTS543216L9SA02 160GB                | 1         | 1      | 1.33%   |
| Hitachi HTS542516K9SA00 160GB                | 1         | 1      | 1.33%   |
| Hitachi HDT721010SLA360 1TB                  | 1         | 1      | 1.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 24.32%  |
| WDC                 | 17        | 17     | 22.97%  |
| Hitachi             | 8         | 8      | 10.81%  |
| Samsung Electronics | 6         | 9      | 8.11%   |
| Toshiba             | 5         | 6      | 6.76%   |
| Crucial             | 4         | 9      | 5.41%   |
| Maxtor              | 3         | 3      | 4.05%   |
| HGST                | 3         | 4      | 4.05%   |
| Fujitsu             | 2         | 2      | 2.7%    |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| SPCC                | 1         | 1      | 1.35%   |
| SanDisk             | 1         | 1      | 1.35%   |
| Kingston            | 1         | 1      | 1.35%   |
| Indilinx            | 1         | 3      | 1.35%   |
| IBM/Hitachi         | 1         | 1      | 1.35%   |
| Goodram             | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 31.03%  |
| WDC                 | 16        | 16     | 27.59%  |
| Hitachi             | 8         | 8      | 13.79%  |
| Toshiba             | 5         | 6      | 8.62%   |
| Maxtor              | 3         | 3      | 5.17%   |
| HGST                | 3         | 4      | 5.17%   |
| Samsung Electronics | 2         | 4      | 3.45%   |
| Fujitsu             | 2         | 2      | 3.45%   |
| IBM/Hitachi         | 1         | 1      | 1.72%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 63     | 77.46%  |
| SSD  | 15        | 18     | 21.13%  |
| NVMe | 1         | 6      | 1.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB   | 2         | 2      | 66.67%  |
| Seagate ST3500418AS 500GB | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 264       | 455    | 70.4%   |
| Malfunc  | 68        | 87     | 18.13%  |
| Detected | 40        | 53     | 10.67%  |
| Failed   | 3         | 4      | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 228       | 60.64%  |
| AMD                          | 53        | 14.1%   |
| Samsung Electronics          | 25        | 6.65%   |
| SanDisk                      | 11        | 2.93%   |
| Nvidia                       | 8         | 2.13%   |
| SK hynix                     | 7         | 1.86%   |
| ASMedia Technology           | 7         | 1.86%   |
| Phison Electronics           | 6         | 1.6%    |
| JMicron Technology           | 6         | 1.6%    |
| Micron/Crucial Technology    | 4         | 1.06%   |
| Kingston Technology Company  | 4         | 1.06%   |
| Silicon Motion               | 3         | 0.8%    |
| Marvell Technology Group     | 3         | 0.8%    |
| Toshiba America Info Systems | 2         | 0.53%   |
| KIOXIA                       | 2         | 0.53%   |
| VIA Technologies             | 1         | 0.27%   |
| ULi Electronics              | 1         | 0.27%   |
| Silicon Image                | 1         | 0.27%   |
| Lenovo                       | 1         | 0.27%   |
| Hewlett-Packard              | 1         | 0.27%   |
| Broadcom / LSI               | 1         | 0.27%   |
| ADATA Technology             | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 34        | 7.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 24        | 5.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 3.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 3.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 2.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 2.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 10        | 2.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 9         | 2.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 1.61%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 7         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 7         | 1.61%   |
| Phison E12 NVMe Controller                                                       | 6         | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 6         | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.38%   |
| AMD 500 Series Chipset SATA Controller                                           | 6         | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 1.38%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 5         | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5         | 1.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.92%   |
| JMicron JMB363 SATA/IDE Controller                                               | 4         | 0.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 0.92%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.92%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 4         | 0.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 4         | 0.92%   |
| SK hynix BC511                                                                   | 3         | 0.69%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 0.69%   |
| Intel SSD 660P Series                                                            | 3         | 0.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3         | 0.69%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 0.69%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 0.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3         | 0.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3         | 0.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 3         | 0.69%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 3         | 0.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.69%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3         | 0.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.69%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 0.69%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.46%   |
| SK hynix Gold P31 SSD                                                            | 2         | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 240       | 62.66%  |
| NVMe | 63        | 16.45%  |
| IDE  | 55        | 14.36%  |
| RAID | 24        | 6.27%   |
| SCSI | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 258       | 79.38%  |
| AMD          | 66        | 20.31%  |
| CentaurHauls | 1         | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.92%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 3         | 0.92%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.92%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 0.92%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.92%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 0.92%   |
| AMD Ryzen 5 1600X Six-Core Processor          | 3         | 0.92%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 2         | 0.62%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.62%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 0.62%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.62%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.62%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.62%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.62%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.62%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.62%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.62%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 0.62%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.62%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.62%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.62%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.62%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.62%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2         | 0.62%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.62%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.62%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 0.62%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.62%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.62%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 0.62%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 0.62%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 0.62%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 2         | 0.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.62%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 0.62%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 0.62%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.62%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 0.62%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 0.62%   |
| Intel Xeon CPU X5550 @ 2.67GHz                | 1         | 0.31%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.31%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.31%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz            | 1         | 0.31%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz           | 1         | 0.31%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 73        | 22.46%  |
| Intel Core i7           | 63        | 19.38%  |
| Intel Celeron           | 25        | 7.69%   |
| Intel Core i3           | 21        | 6.46%   |
| Intel Core 2 Duo        | 16        | 4.92%   |
| Intel Atom              | 16        | 4.92%   |
| AMD Ryzen 7             | 16        | 4.92%   |
| AMD Ryzen 5             | 13        | 4%      |
| Other                   | 11        | 3.38%   |
| Intel Pentium           | 7         | 2.15%   |
| Intel Xeon              | 5         | 1.54%   |
| Intel Core 2 Quad       | 5         | 1.54%   |
| AMD Sempron             | 3         | 0.92%   |
| AMD Ryzen 3             | 3         | 0.92%   |
| AMD E1                  | 3         | 0.92%   |
| AMD Athlon II X2        | 3         | 0.92%   |
| AMD A6                  | 3         | 0.92%   |
| AMD A4                  | 3         | 0.92%   |
| Intel Pentium Dual-Core | 2         | 0.62%   |
| Intel Pentium 4         | 2         | 0.62%   |
| Intel Celeron M         | 2         | 0.62%   |
| AMD Turion 64 X2 Mobile | 2         | 0.62%   |
| AMD Ryzen 9             | 2         | 0.62%   |
| AMD Phenom II X4        | 2         | 0.62%   |
| AMD E                   | 2         | 0.62%   |
| AMD Athlon 64 X2        | 2         | 0.62%   |
| AMD A8                  | 2         | 0.62%   |
| Intel Pentium Silver    | 1         | 0.31%   |
| Intel Pentium M         | 1         | 0.31%   |
| Intel Pentium Gold      | 1         | 0.31%   |
| Intel Pentium D         | 1         | 0.31%   |
| Intel Genuine           | 1         | 0.31%   |
| Intel Core m5           | 1         | 0.31%   |
| Intel Core i9           | 1         | 0.31%   |
| Intel Core Duo          | 1         | 0.31%   |
| Intel Core 2 Extreme    | 1         | 0.31%   |
| Intel Core 2            | 1         | 0.31%   |
| Intel Celeron D         | 1         | 0.31%   |
| CentaurHauls VIA Esther | 1         | 0.31%   |
| AMD Ryzen Threadripper  | 1         | 0.31%   |
| AMD Phenom II X6        | 1         | 0.31%   |
| AMD FX                  | 1         | 0.31%   |
| AMD Athlon X4           | 1         | 0.31%   |
| AMD Athlon              | 1         | 0.31%   |
| AMD A10                 | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 152       | 46.77%  |
| 4      | 107       | 32.92%  |
| 6      | 24        | 7.38%   |
| 8      | 20        | 6.15%   |
| 1      | 17        | 5.23%   |
| 12     | 3         | 0.92%   |
| 14     | 1         | 0.31%   |
| 10     | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 323       | 99.38%  |
| 2      | 2         | 0.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 198       | 60.92%  |
| 1      | 127       | 39.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 313       | 96.01%  |
| 32-bit         | 13        | 3.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 11.31%  |
| 0x306a9    | 25        | 7.65%   |
| 0x206a7    | 25        | 7.65%   |
| 0x306c3    | 17        | 5.2%    |
| 0x406e3    | 10        | 3.06%   |
| 0x20655    | 10        | 3.06%   |
| 0x1067a    | 9         | 2.75%   |
| 0x40651    | 8         | 2.45%   |
| 0x806ea    | 7         | 2.14%   |
| 0x806e9    | 6         | 1.83%   |
| 0x806c1    | 6         | 1.83%   |
| 0x406c4    | 6         | 1.83%   |
| 0x30678    | 6         | 1.83%   |
| 0x08701021 | 6         | 1.83%   |
| 0x906ea    | 5         | 1.53%   |
| 0x706a1    | 5         | 1.53%   |
| 0x20652    | 5         | 1.53%   |
| 0x0800820d | 5         | 1.53%   |
| 0xa0653    | 4         | 1.22%   |
| 0x906ed    | 4         | 1.22%   |
| 0x906e9    | 4         | 1.22%   |
| 0x506e3    | 4         | 1.22%   |
| 0x306d4    | 4         | 1.22%   |
| 0x106c2    | 4         | 1.22%   |
| 0x10676    | 4         | 1.22%   |
| 0x03000027 | 4         | 1.22%   |
| 0xa0652    | 3         | 0.92%   |
| 0x806ec    | 3         | 0.92%   |
| 0x706e5    | 3         | 0.92%   |
| 0x6fd      | 3         | 0.92%   |
| 0x6fb      | 3         | 0.92%   |
| 0x506c9    | 3         | 0.92%   |
| 0x406c3    | 3         | 0.92%   |
| 0x30661    | 3         | 0.92%   |
| 0x106e5    | 3         | 0.92%   |
| 0x0a50000c | 3         | 0.92%   |
| 0x0810100b | 3         | 0.92%   |
| 0x0700010f | 3         | 0.92%   |
| 0x010000c8 | 3         | 0.92%   |
| 0xa0671    | 2         | 0.61%   |
| 0x6d8      | 2         | 0.61%   |
| 0x306f2    | 2         | 0.61%   |
| 0x206d7    | 2         | 0.61%   |
| 0x106ca    | 2         | 0.61%   |
| 0x10677    | 2         | 0.61%   |
| 0x08608103 | 2         | 0.61%   |
| 0x08600106 | 2         | 0.61%   |
| 0x08108102 | 2         | 0.61%   |
| 0x07030105 | 2         | 0.61%   |
| 0xf65      | 1         | 0.31%   |
| 0xf64      | 1         | 0.31%   |
| 0xf4a      | 1         | 0.31%   |
| 0xf29      | 1         | 0.31%   |
| 0xa0655    | 1         | 0.31%   |
| 0x906eb    | 1         | 0.31%   |
| 0x906a3    | 1         | 0.31%   |
| 0x806eb    | 1         | 0.31%   |
| 0x806d1    | 1         | 0.31%   |
| 0x706a8    | 1         | 0.31%   |
| 0x6f2      | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 10.77%  |
| SandyBridge      | 31        | 9.54%   |
| Haswell          | 30        | 9.23%   |
| IvyBridge        | 29        | 8.92%   |
| Penryn           | 18        | 5.54%   |
| Silvermont       | 17        | 5.23%   |
| Westmere         | 16        | 4.92%   |
| Skylake          | 15        | 4.62%   |
| Zen+             | 10        | 3.08%   |
| Zen 2            | 10        | 3.08%   |
| Bonnell          | 9         | 2.77%   |
| Core             | 8         | 2.46%   |
| CometLake        | 8         | 2.46%   |
| Zen              | 7         | 2.15%   |
| K8 Hammer        | 7         | 2.15%   |
| K10              | 7         | 2.15%   |
| Zen 3            | 6         | 1.85%   |
| TigerLake        | 6         | 1.85%   |
| Icelake          | 6         | 1.85%   |
| Goldmont plus    | 6         | 1.85%   |
| P6               | 5         | 1.54%   |
| Nehalem          | 5         | 1.54%   |
| Broadwell        | 5         | 1.54%   |
| NetBurst         | 4         | 1.23%   |
| K10 Llano        | 4         | 1.23%   |
| Unknown          | 4         | 1.23%   |
| Puma             | 3         | 0.92%   |
| Jaguar           | 3         | 0.92%   |
| Goldmont         | 3         | 0.92%   |
| Excavator        | 2         | 0.62%   |
| Bobcat           | 2         | 0.62%   |
| Steamroller      | 1         | 0.31%   |
| K8 & K10 hybrid  | 1         | 0.31%   |
| Bulldozer        | 1         | 0.31%   |
| Alderlake Hybrid | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 201       | 52.34%  |
| Nvidia           | 97        | 25.26%  |
| AMD              | 85        | 22.14%  |
| VIA Technologies | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 6.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 4.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 2.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.24%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.49%   |
| Intel HD Graphics 620                                                                    | 6         | 1.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.24%   |
| Intel HD Graphics 630                                                                    | 5         | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.24%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1%      |
| Intel HD Graphics 5500                                                                   | 4         | 1%      |
| Intel HD Graphics 530                                                                    | 4         | 1%      |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.75%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.75%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 3         | 0.75%   |
| AMD Renoir                                                                               | 3         | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.75%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 3         | 0.75%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 3         | 0.75%   |
| AMD Cezanne                                                                              | 3         | 0.75%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.5%    |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.5%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.5%    |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.5%    |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.5%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2         | 0.5%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.5%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.5%    |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2         | 0.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.5%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.5%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.5%    |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.5%    |
| Intel HD Graphics 500                                                                    | 2         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 148       | 45.12%  |
| 1 x AMD        | 64        | 19.51%  |
| 1 x Nvidia     | 59        | 17.99%  |
| Intel + Nvidia | 34        | 10.37%  |
| Intel + AMD    | 11        | 3.35%   |
| 2 x AMD        | 6         | 1.83%   |
| AMD + Nvidia   | 4         | 1.22%   |
| 3 x AMD        | 1         | 0.3%    |
| 1 x VIA        | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 271       | 82.62%  |
| Proprietary | 47        | 14.33%  |
| Unknown     | 10        | 3.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 194       | 58.79%  |
| 0.01-0.5   | 40        | 12.12%  |
| 0.51-1.0   | 31        | 9.39%   |
| 1.01-2.0   | 29        | 8.79%   |
| 3.01-4.0   | 16        | 4.85%   |
| 7.01-8.0   | 13        | 3.94%   |
| 5.01-6.0   | 4         | 1.21%   |
| 8.01-16.0  | 2         | 0.61%   |
| 2.01-3.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 48        | 13.83%  |
| AU Optronics            | 42        | 12.1%   |
| LG Display              | 34        | 9.8%    |
| Chimei Innolux          | 31        | 8.93%   |
| BOE                     | 22        | 6.34%   |
| Goldstar                | 20        | 5.76%   |
| Dell                    | 17        | 4.9%    |
| Acer                    | 12        | 3.46%   |
| Lenovo                  | 11        | 3.17%   |
| Hewlett-Packard         | 11        | 3.17%   |
| Chi Mei Optoelectronics | 9         | 2.59%   |
| Ancor Communications    | 8         | 2.31%   |
| Philips                 | 6         | 1.73%   |
| PANDA                   | 5         | 1.44%   |
| ViewSonic               | 4         | 1.15%   |
| InfoVision              | 4         | 1.15%   |
| HannStar                | 4         | 1.15%   |
| Apple                   | 4         | 1.15%   |
| AOC                     | 4         | 1.15%   |
| Vizio                   | 3         | 0.86%   |
| Sony                    | 3         | 0.86%   |
| Sharp                   | 3         | 0.86%   |
| LG Philips              | 3         | 0.86%   |
| Iiyama                  | 3         | 0.86%   |
| Fujitsu Siemens         | 3         | 0.86%   |
| BenQ                    | 3         | 0.86%   |
| ASUSTek Computer        | 3         | 0.86%   |
| Vestel Elektronik       | 2         | 0.58%   |
| Sceptre Tech            | 2         | 0.58%   |
| Medion                  | 2         | 0.58%   |
| Eizo                    | 2         | 0.58%   |
| CPT                     | 2         | 0.58%   |
| Videoseven              | 1         | 0.29%   |
| Sunplus                 | 1         | 0.29%   |
| SANYO                   | 1         | 0.29%   |
| SAC                     | 1         | 0.29%   |
| RIS                     | 1         | 0.29%   |
| Panasonic               | 1         | 0.29%   |
| NEC Computers           | 1         | 0.29%   |
| MSI                     | 1         | 0.29%   |
| InnoLux Display         | 1         | 0.29%   |
| IBM                     | 1         | 0.29%   |
| HYO                     | 1         | 0.29%   |
| Hitachi                 | 1         | 0.29%   |
| Grundig                 | 1         | 0.29%   |
| Gigabyte Technology     | 1         | 0.29%   |
| DTV                     | 1         | 0.29%   |
| CHR                     | 1         | 0.29%   |
| Arnos Instruments       | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 8         | 2.29%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.86%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 3         | 0.86%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                            | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.57%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.57%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.57%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.57%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.57%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.57%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                    | 2         | 0.57%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.57%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.57%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                    | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.57%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.57%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                    | 2         | 0.57%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 340x190mm 15.3-inch            | 2         | 0.57%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                       | 1         | 0.29%   |
| Vizio E400i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                     | 1         | 0.29%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                        | 1         | 0.29%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                   | 1         | 0.29%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                   | 1         | 0.29%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch            | 1         | 0.29%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch               | 1         | 0.29%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                  | 1         | 0.29%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 0.29%   |
| Sony TV SNY0801 1360x768                                                 | 1         | 0.29%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.29%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.29%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.29%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.29%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.29%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                   | 1         | 0.29%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                   | 1         | 0.29%   |
| SANYO LCD MONITOR SAN2213 1920x1080 474x296mm 22.0-inch                  | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM04E6 1920x1080 477x268mm 21.5-inch     | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch     | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch     | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch     | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch     | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch     | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM0059 1280x1024 312x234mm 15.4-inch     | 1         | 0.29%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch       | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 137       | 40.65%  |
| 1366x768 (WXGA)    | 79        | 23.44%  |
| 3840x2160 (4K)     | 17        | 5.04%   |
| 1600x900 (HD+)     | 14        | 4.15%   |
| 2560x1440 (QHD)    | 13        | 3.86%   |
| 1280x1024 (SXGA)   | 11        | 3.26%   |
| 1680x1050 (WSXGA+) | 10        | 2.97%   |
| 1280x800 (WXGA)    | 10        | 2.97%   |
| 1600x1200          | 9         | 2.67%   |
| 1440x900 (WXGA+)   | 9         | 2.67%   |
| 1024x600           | 6         | 1.78%   |
| 1920x1200 (WUXGA)  | 4         | 1.19%   |
| 3440x1440          | 3         | 0.89%   |
| 2560x1080          | 3         | 0.89%   |
| 1360x768           | 3         | 0.89%   |
| 1400x1050          | 2         | 0.59%   |
| 3840x2400          | 1         | 0.3%    |
| 3000x2000          | 1         | 0.3%    |
| 2736x1824          | 1         | 0.3%    |
| 2256x1504          | 1         | 0.3%    |
| 2160x1440          | 1         | 0.3%    |
| 2048x1536          | 1         | 0.3%    |
| 1024x768 (XGA)     | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 94        | 27.25%  |
| 13      | 32        | 9.28%   |
| 14      | 26        | 7.54%   |
| 27      | 24        | 6.96%   |
| 21      | 23        | 6.67%   |
| 24      | 21        | 6.09%   |
| 23      | 21        | 6.09%   |
| 17      | 16        | 4.64%   |
| 19      | 12        | 3.48%   |
| 18      | 9         | 2.61%   |
| 12      | 8         | 2.32%   |
| 11      | 8         | 2.32%   |
| 31      | 7         | 2.03%   |
| 10      | 7         | 2.03%   |
| 34      | 6         | 1.74%   |
| 22      | 6         | 1.74%   |
| 20      | 6         | 1.74%   |
| 84      | 5         | 1.45%   |
| 65      | 2         | 0.58%   |
| 72      | 1         | 0.29%   |
| 54      | 1         | 0.29%   |
| 49      | 1         | 0.29%   |
| 43      | 1         | 0.29%   |
| 42      | 1         | 0.29%   |
| 39      | 1         | 0.29%   |
| 37      | 1         | 0.29%   |
| 32      | 1         | 0.29%   |
| 26      | 1         | 0.29%   |
| 25      | 1         | 0.29%   |
| 16      | 1         | 0.29%   |
| Unknown | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 134       | 39.41%  |
| 501-600     | 63        | 18.53%  |
| 401-500     | 46        | 13.53%  |
| 201-300     | 39        | 11.47%  |
| 351-400     | 28        | 8.24%   |
| 601-700     | 8         | 2.35%   |
| 701-800     | 7         | 2.06%   |
| 1501-2000   | 6         | 1.76%   |
| 1001-1500   | 4         | 1.18%   |
| 801-900     | 2         | 0.59%   |
| 901-1000    | 2         | 0.59%   |
| Unknown     | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 251       | 77.95%  |
| 16/10 | 35        | 10.87%  |
| 5/4   | 12        | 3.73%   |
| 4/3   | 12        | 3.73%   |
| 3/2   | 6         | 1.86%   |
| 21/9  | 6         | 1.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 27.19%  |
| 201-250        | 62        | 18.13%  |
| 81-90          | 47        | 13.74%  |
| 301-350        | 24        | 7.02%   |
| 151-200        | 22        | 6.43%   |
| 351-500        | 14        | 4.09%   |
| 71-80          | 12        | 3.51%   |
| 121-130        | 12        | 3.51%   |
| More than 1000 | 10        | 2.92%   |
| 141-150        | 9         | 2.63%   |
| 51-60          | 8         | 2.34%   |
| 61-70          | 7         | 2.05%   |
| 41-50          | 7         | 2.05%   |
| 251-300        | 7         | 2.05%   |
| 501-1000       | 4         | 1.17%   |
| 111-120        | 2         | 0.58%   |
| 131-140        | 1         | 0.29%   |
| Unknown        | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 126       | 37.95%  |
| 101-120       | 101       | 30.42%  |
| 121-160       | 80        | 24.1%   |
| 161-240       | 13        | 3.92%   |
| More than 240 | 6         | 1.81%   |
| 1-50          | 5         | 1.51%   |
| Unknown       | 1         | 0.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 273       | 83.49%  |
| 2     | 45        | 13.76%  |
| 0     | 6         | 1.83%   |
| 3     | 3         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 162       | 33.26%  |
| Intel                             | 157       | 32.24%  |
| Qualcomm Atheros                  | 69        | 14.17%  |
| Broadcom                          | 30        | 6.16%   |
| Marvell Technology Group          | 8         | 1.64%   |
| TP-Link                           | 7         | 1.44%   |
| Nvidia                            | 7         | 1.44%   |
| Ralink Technology                 | 5         | 1.03%   |
| Ralink                            | 5         | 1.03%   |
| Broadcom Limited                  | 5         | 1.03%   |
| MediaTek                          | 4         | 0.82%   |
| Huawei Technologies               | 3         | 0.62%   |
| ASIX Electronics                  | 3         | 0.62%   |
| Sierra Wireless                   | 2         | 0.41%   |
| Ericsson Business Mobile Networks | 2         | 0.41%   |
| Edimax Technology                 | 2         | 0.41%   |
| Attansic Technology               | 2         | 0.41%   |
| ASUSTek Computer                  | 2         | 0.41%   |
| VIA Technologies                  | 1         | 0.21%   |
| U-Blox                            | 1         | 0.21%   |
| Samsung Electronics               | 1         | 0.21%   |
| Qualcomm                          | 1         | 0.21%   |
| NetGear                           | 1         | 0.21%   |
| Microsoft                         | 1         | 0.21%   |
| JMicron Technology                | 1         | 0.21%   |
| Hewlett-Packard                   | 1         | 0.21%   |
| Google                            | 1         | 0.21%   |
| Dell                              | 1         | 0.21%   |
| D-Link System                     | 1         | 0.21%   |
| Aquantia                          | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 115       | 20.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 21        | 3.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 16        | 2.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 13        | 2.28%   |
| Intel Wireless 7260                                                                           | 12        | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 9         | 1.58%   |
| Intel Wireless 8265 / 8275                                                                    | 9         | 1.58%   |
| Intel Wireless 8260                                                                           | 9         | 1.58%   |
| Intel Wi-Fi 6 AX200                                                                           | 9         | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 8         | 1.4%    |
| Intel Ethernet Connection I217-LM                                                             | 8         | 1.4%    |
| Intel 82577LM Gigabit Network Connection                                                      | 8         | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 7         | 1.23%   |
| Intel Wireless 3165                                                                           | 7         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 7         | 1.23%   |
| Intel Centrino Advanced-N 6200                                                                | 7         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 6         | 1.05%   |
| Intel Wireless 7265                                                                           | 6         | 1.05%   |
| Intel I211 Gigabit Network Connection                                                         | 6         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5         | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 4         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 4         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 4         | 0.7%    |
| Intel Wi-Fi 6 AX201                                                                           | 4         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 4         | 0.7%    |
| Intel Ethernet Connection I219-V                                                              | 4         | 0.7%    |
| Intel Ethernet Connection I218-LM                                                             | 4         | 0.7%    |
| Intel Ethernet Connection (2) I218-V                                                          | 4         | 0.7%    |
| Intel Centrino Wireless-N 2230                                                                | 4         | 0.7%    |
| Intel Centrino Advanced-N 6235                                                                | 4         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 0.7%    |
| Intel 82579V Gigabit Network Connection                                                       | 4         | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 4         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3         | 0.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 3         | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 3         | 0.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 3         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 3         | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 0.53%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3         | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 3         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                             | 3         | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 0.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 3         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2         | 0.35%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 0.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                        | 2         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 2         | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 2         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2         | 0.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 0.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2         | 0.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                                         | 2         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 117       | 45.7%   |
| Qualcomm Atheros      | 53        | 20.7%   |
| Realtek Semiconductor | 39        | 15.23%  |
| Broadcom              | 17        | 6.64%   |
| TP-Link               | 6         | 2.34%   |
| Ralink Technology     | 5         | 1.95%   |
| Ralink                | 5         | 1.95%   |
| MediaTek              | 3         | 1.17%   |
| Broadcom Limited      | 3         | 1.17%   |
| Sierra Wireless       | 2         | 0.78%   |
| Edimax Technology     | 2         | 0.78%   |
| ASUSTek Computer      | 2         | 0.78%   |
| NetGear               | 1         | 0.39%   |
| Hewlett-Packard       | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 16        | 6.23%   |
| Intel Wireless 7260                                                                           | 12        | 4.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 9         | 3.5%    |
| Intel Wireless 8265 / 8275                                                                    | 9         | 3.5%    |
| Intel Wireless 8260                                                                           | 9         | 3.5%    |
| Intel Wi-Fi 6 AX200                                                                           | 9         | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 8         | 3.11%   |
| Intel Wireless 3165                                                                           | 7         | 2.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 7         | 2.72%   |
| Intel Centrino Advanced-N 6200                                                                | 7         | 2.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 6         | 2.33%   |
| Intel Wireless 7265                                                                           | 6         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5         | 1.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 4         | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4         | 1.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 4         | 1.56%   |
| Intel Wi-Fi 6 AX201                                                                           | 4         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 4         | 1.56%   |
| Intel Centrino Wireless-N 2230                                                                | 4         | 1.56%   |
| Intel Centrino Advanced-N 6235                                                                | 4         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 3         | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 3         | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 3         | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 3         | 1.17%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2         | 0.78%   |
| Intel Wireless-AC 9260                                                                        | 2         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 2         | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 2         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2         | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 2         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 2         | 0.78%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2         | 0.78%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 2         | 0.78%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1         | 0.39%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1         | 0.39%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                                           | 1         | 0.39%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.39%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.39%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1         | 0.39%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 0.39%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.39%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.39%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 146       | 48.67%  |
| Intel                    | 83        | 27.67%  |
| Qualcomm Atheros         | 24        | 8%      |
| Broadcom                 | 15        | 5%      |
| Marvell Technology Group | 8         | 2.67%   |
| Nvidia                   | 7         | 2.33%   |
| ASIX Electronics         | 3         | 1%      |
| Broadcom Limited         | 2         | 0.67%   |
| Attansic Technology      | 2         | 0.67%   |
| VIA Technologies         | 1         | 0.33%   |
| TP-Link                  | 1         | 0.33%   |
| Samsung Electronics      | 1         | 0.33%   |
| Qualcomm                 | 1         | 0.33%   |
| Microsoft                | 1         | 0.33%   |
| MediaTek                 | 1         | 0.33%   |
| JMicron Technology       | 1         | 0.33%   |
| Huawei Technologies      | 1         | 0.33%   |
| D-Link System            | 1         | 0.33%   |
| Aquantia                 | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 115       | 37.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 6.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13        | 4.23%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 2.61%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 2.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 2.28%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 1.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.3%    |
| Intel Ethernet Connection I219-V                                               | 4         | 1.3%    |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.3%    |
| Intel Ethernet Connection (2) I218-V                                           | 4         | 1.3%    |
| Intel 82579V Gigabit Network Connection                                        | 4         | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4         | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.65%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.65%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.65%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.65%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.65%   |
| Intel Ethernet Connection (14) I219-V                                          | 2         | 0.65%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.65%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.65%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.33%   |
| Qualcomm Redmi 9T                                                              | 1         | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.33%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.33%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.33%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.33%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.33%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.33%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.33%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                              | 1         | 0.33%   |
| MediaTek TECNO SPARK 6 Go                                                      | 1         | 0.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.33%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.33%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 288       | 53.53%  |
| WiFi     | 243       | 45.17%  |
| Modem    | 6         | 1.12%   |
| Unknown  | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 196       | 58.51%  |
| Ethernet | 138       | 41.19%  |
| Unknown  | 1         | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 188       | 57.85%  |
| 1     | 124       | 38.15%  |
| 0     | 7         | 2.15%   |
| 3     | 5         | 1.54%   |
| 12    | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 287       | 87.77%  |
| Yes  | 40        | 12.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 44.2%   |
| Realtek Semiconductor           | 16        | 8.84%   |
| Qualcomm Atheros Communications | 16        | 8.84%   |
| Broadcom                        | 14        | 7.73%   |
| Cambridge Silicon Radio         | 10        | 5.52%   |
| IMC Networks                    | 9         | 4.97%   |
| Apple                           | 8         | 4.42%   |
| Lite-On Technology              | 6         | 3.31%   |
| Hewlett-Packard                 | 5         | 2.76%   |
| Foxconn / Hon Hai               | 5         | 2.76%   |
| ASUSTek Computer                | 4         | 2.21%   |
| Toshiba                         | 3         | 1.66%   |
| Dell                            | 3         | 1.66%   |
| Ralink                          | 1         | 0.55%   |
| Alps Electric                   | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 42        | 23.2%   |
| Intel Bluetooth Device                                                              | 12        | 6.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 5.52%   |
| Intel AX200 Bluetooth                                                               | 9         | 4.97%   |
| Realtek Bluetooth Radio                                                             | 8         | 4.42%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 3.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 3.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 2.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.21%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.21%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 2.21%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.66%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.66%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.1%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.1%    |
| Intel AX210 Bluetooth                                                               | 2         | 1.1%    |
| IMC Networks Wireless_Device                                                        | 2         | 1.1%    |
| IMC Networks Bluetooth Device                                                       | 2         | 1.1%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.1%    |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.1%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.1%    |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.55%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.55%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.55%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.55%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.55%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.55%   |
| Lite-On Wireless_Device                                                             | 1         | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.55%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.55%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.55%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.55%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.55%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.55%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.55%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.55%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.55%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.55%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.55%   |
| ASUS BCM20702A0                                                                     | 1         | 0.55%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.55%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.55%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 243       | 54.36%  |
| AMD                        | 84        | 18.79%  |
| Nvidia                     | 77        | 17.23%  |
| Creative Labs              | 7         | 1.57%   |
| C-Media Electronics        | 7         | 1.57%   |
| GN Netcom                  | 3         | 0.67%   |
| Texas Instruments          | 2         | 0.45%   |
| ROCCAT                     | 2         | 0.45%   |
| JMTek                      | 2         | 0.45%   |
| Focusrite-Novation         | 2         | 0.45%   |
| VIA Technologies           | 1         | 0.22%   |
| Unknown                    | 1         | 0.22%   |
| ULi Electronics            | 1         | 0.22%   |
| TerraTec Electronic        | 1         | 0.22%   |
| Tenx Technology            | 1         | 0.22%   |
| SteelSeries ApS            | 1         | 0.22%   |
| Shenzhen Riitek Technology | 1         | 0.22%   |
| Schiit Audio               | 1         | 0.22%   |
| Realtek Semiconductor      | 1         | 0.22%   |
| Razer USA                  | 1         | 0.22%   |
| Plantronics                | 1         | 0.22%   |
| Microsoft                  | 1         | 0.22%   |
| Mark of the Unicorn        | 1         | 0.22%   |
| Logitech                   | 1         | 0.22%   |
| LG Electronics             | 1         | 0.22%   |
| Kingston Technology        | 1         | 0.22%   |
| Fortemedia                 | 1         | 0.22%   |
| Unknown                    | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 35        | 6.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 4.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 3.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 3.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 2.51%   |
| AMD FCH Azalia Controller                                                                         | 12        | 2.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 2.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 9         | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.55%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 1.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.35%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.16%   |
| Nvidia Audio device                                                                               | 6         | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.16%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.97%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 0.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.77%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.77%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.58%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.58%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.58%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.58%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.58%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 3         | 0.58%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 3         | 0.58%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.58%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 0.58%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 3         | 0.58%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 71        | 18.83%  |
| SK hynix                     | 59        | 15.65%  |
| Unknown                      | 58        | 15.38%  |
| Kingston                     | 45        | 11.94%  |
| Micron Technology            | 34        | 9.02%   |
| Corsair                      | 22        | 5.84%   |
| Crucial                      | 18        | 4.77%   |
| G.Skill                      | 14        | 3.71%   |
| Ramaxel Technology           | 6         | 1.59%   |
| A-DATA Technology            | 6         | 1.59%   |
| Unknown (ABCD)               | 5         | 1.33%   |
| Smart                        | 5         | 1.33%   |
| Nanya Technology             | 5         | 1.33%   |
| Elpida                       | 5         | 1.33%   |
| Transcend                    | 3         | 0.8%    |
| Patriot                      | 3         | 0.8%    |
| Unknown                      | 3         | 0.8%    |
| Teikon                       | 2         | 0.53%   |
| PNY                          | 2         | 0.53%   |
| Apacer                       | 2         | 0.53%   |
| Unknown (F301)               | 1         | 0.27%   |
| TRS STAR                     | 1         | 0.27%   |
| Team                         | 1         | 0.27%   |
| RZX                          | 1         | 0.27%   |
| Patriot Memory (PDP Systems) | 1         | 0.27%   |
| OCZ                          | 1         | 0.27%   |
| High Bridge                  | 1         | 0.27%   |
| Axiom                        | 1         | 0.27%   |
| Avant                        | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 1.2%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 5         | 1.2%    |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 4         | 0.96%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 0.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 0.96%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 4         | 0.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 4         | 0.96%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                             | 3         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 3         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 3         | 0.72%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                              | 3         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.72%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 3         | 0.72%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 0.72%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 3         | 0.72%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s            | 3         | 0.72%   |
| Unknown                                                             | 3         | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 2         | 0.48%   |
| Unknown RAM Module 4GB DIMM SDRAM                                   | 2         | 0.48%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 2         | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 2         | 0.48%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 2         | 0.48%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                          | 2         | 0.48%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s              | 2         | 0.48%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s               | 2         | 0.48%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 2         | 0.48%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 2         | 0.48%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 2         | 0.48%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 2         | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 0.48%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 2         | 0.48%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 0.48%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 0.48%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s               | 2         | 0.48%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.48%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.48%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.48%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s               | 2         | 0.48%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.48%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s                | 2         | 0.48%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 0.48%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.48%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                 | 2         | 0.48%   |
| Kingston RAM HP16D3LS1KEGR/4G 4GB SODIMM DDR3 1600MT/s              | 2         | 0.48%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s              | 2         | 0.48%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM 3000MT/s                    | 2         | 0.48%   |
| Apacer RAM 76.A302G.C4D0B 2048MB SODIMM DDR3 1600MT/s               | 2         | 0.48%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.24%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.24%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                        | 1         | 0.24%   |
| Unknown RAM Module 512MB DIMM SDRAM                                 | 1         | 0.24%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                           | 1         | 0.24%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                           | 1         | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 150       | 46.15%  |
| DDR4    | 102       | 31.38%  |
| DDR2    | 26        | 8%      |
| Unknown | 11        | 3.38%   |
| DDR     | 10        | 3.08%   |
| SDRAM   | 9         | 2.77%   |
| LPDDR4  | 9         | 2.77%   |
| LPDDR3  | 5         | 1.54%   |
| DRAM    | 3         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 211       | 65.12%  |
| DIMM         | 101       | 31.17%  |
| Row Of Chips | 9         | 2.78%   |
| Chip         | 3         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 140       | 38.67%  |
| 8192  | 102       | 28.18%  |
| 2048  | 66        | 18.23%  |
| 16384 | 23        | 6.35%   |
| 1024  | 23        | 6.35%   |
| 32768 | 5         | 1.38%   |
| 512   | 3         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 91        | 25.42%  |
| 1333    | 36        | 10.06%  |
| 2667    | 30        | 8.38%   |
| 3200    | 27        | 7.54%   |
| 2400    | 21        | 5.87%   |
| 1334    | 21        | 5.87%   |
| Unknown | 20        | 5.59%   |
| 2133    | 17        | 4.75%   |
| 667     | 14        | 3.91%   |
| 800     | 10        | 2.79%   |
| 3600    | 7         | 1.96%   |
| 1067    | 7         | 1.96%   |
| 3000    | 6         | 1.68%   |
| 1867    | 6         | 1.68%   |
| 3466    | 4         | 1.12%   |
| 3266    | 4         | 1.12%   |
| 4199    | 3         | 0.84%   |
| 2933    | 3         | 0.84%   |
| 1639    | 3         | 0.84%   |
| 533     | 3         | 0.84%   |
| 333     | 3         | 0.84%   |
| 49926   | 2         | 0.56%   |
| 3400    | 2         | 0.56%   |
| 2666    | 2         | 0.56%   |
| 2048    | 2         | 0.56%   |
| 1800    | 2         | 0.56%   |
| 400     | 2         | 0.56%   |
| 8400    | 1         | 0.28%   |
| 4800    | 1         | 0.28%   |
| 4267    | 1         | 0.28%   |
| 3733    | 1         | 0.28%   |
| 3100    | 1         | 0.28%   |
| 1777    | 1         | 0.28%   |
| 1400    | 1         | 0.28%   |
| 1066    | 1         | 0.28%   |
| 200     | 1         | 0.28%   |
| 166     | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 25%     |
| Seiko Epson           | 1         | 12.5%   |
| Samsung Electronics   | 1         | 12.5%   |
| Lexmark International | 1         | 12.5%   |
| Konica Minolta        | 1         | 12.5%   |
| Canon                 | 1         | 12.5%   |
| Brother Industries    | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L380 Series            | 1         | 12.5%   |
| Samsung ML-1610 Mono Laser Printer | 1         | 12.5%   |
| Lexmark International CS417dn      | 1         | 12.5%   |
| Konica Minolta 206                 | 1         | 12.5%   |
| HP LaserJet P2055 series           | 1         | 12.5%   |
| HP LaserJet M101-M106              | 1         | 12.5%   |
| Canon MF641C                       | 1         | 12.5%   |
| Brother DCP-L2540DW                | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 25%     |
| Canon CanoScan LiDE 700F           | 1         | 25%     |
| Canon CanoScan LIDE 25             | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 44        | 23.53%  |
| Realtek Semiconductor                  | 17        | 9.09%   |
| Acer                                   | 17        | 9.09%   |
| Sunplus Innovation Technology          | 13        | 6.95%   |
| Microdia                               | 10        | 5.35%   |
| Logitech                               | 10        | 5.35%   |
| IMC Networks                           | 9         | 4.81%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 4.81%   |
| Lite-On Technology                     | 7         | 3.74%   |
| Suyin                                  | 6         | 3.21%   |
| Quanta                                 | 6         | 3.21%   |
| Lenovo                                 | 5         | 2.67%   |
| Z-Star Microelectronics                | 3         | 1.6%    |
| Syntek                                 | 3         | 1.6%    |
| Microsoft                              | 3         | 1.6%    |
| Apple                                  | 3         | 1.6%    |
| Silicon Motion                         | 2         | 1.07%   |
| Ricoh                                  | 2         | 1.07%   |
| Generalplus Technology                 | 2         | 1.07%   |
| Alcor Micro                            | 2         | 1.07%   |
| Y Media                                | 1         | 0.53%   |
| Xiongmai                               | 1         | 0.53%   |
| WaveRider Communications               | 1         | 0.53%   |
| Sunplus Technology                     | 1         | 0.53%   |
| Samsung Electronics                    | 1         | 0.53%   |
| Primax Electronics                     | 1         | 0.53%   |
| Luxvisions Innotech Limited            | 1         | 0.53%   |
| LG Electronics                         | 1         | 0.53%   |
| Importek                               | 1         | 0.53%   |
| Huawei Technologies                    | 1         | 0.53%   |
| Goodong Industry                       | 1         | 0.53%   |
| GEMBIRD                                | 1         | 0.53%   |
| Cubeternet                             | 1         | 0.53%   |
| 8SSC20F27145V1SR1BX02P8                | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 4.81%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 2.67%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.14%   |
| Lite-On Integrated Camera                                   | 4         | 2.14%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 2.14%   |
| Chicony USB 2.0 Camera                                      | 4         | 2.14%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 2.14%   |
| Syntek EasyCamera                                           | 3         | 1.6%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 1.6%    |
| Microsoft LifeCam HD-3000                                   | 3         | 1.6%    |
| Chicony HP Truevision HD camera                             | 3         | 1.6%    |
| Chicony HD WebCam                                           | 3         | 1.6%    |
| Acer Integrated Camera                                      | 3         | 1.6%    |
| Acer BisonCam, NB Pro                                       | 3         | 1.6%    |
| Sunplus HD WebCam                                           | 2         | 1.07%   |
| Sunplus Asus Webcam                                         | 2         | 1.07%   |
| Ricoh USB2.0 Camera                                         | 2         | 1.07%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.07%   |
| Realtek USB2.0 camera                                       | 2         | 1.07%   |
| Realtek USB Camera                                          | 2         | 1.07%   |
| Quanta VGA WebCam                                           | 2         | 1.07%   |
| Microdia USB 2.0 Camera                                     | 2         | 1.07%   |
| Microdia Integrated Webcam                                  | 2         | 1.07%   |
| Logitech Webcam C930e                                       | 2         | 1.07%   |
| Logitech Webcam C270                                        | 2         | 1.07%   |
| Logitech Webcam C200                                        | 2         | 1.07%   |
| Lite-On HP HD Camera                                        | 2         | 1.07%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 1.07%   |
| Lenovo Integrated Webcam                                    | 2         | 1.07%   |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 1.07%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.07%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 1.07%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 1.07%   |
| Apple Built-in iSight                                       | 2         | 1.07%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.07%   |
| Acer SunplusIT INC. Integrated Camera                       | 2         | 1.07%   |
| Acer Lenovo Integrated Webcam                               | 2         | 1.07%   |
| Acer Lenovo EasyCamera                                      | 2         | 1.07%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 0.53%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.53%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.53%   |
| Y Media USB Camera                                          | 1         | 0.53%   |
| Xiongmai web camera                                         | 1         | 0.53%   |
| WaveRider USB 2.0 Camera                                    | 1         | 0.53%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.53%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.53%   |
| Suyin 1.3M HD WebCam                                        | 1         | 0.53%   |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode)     | 1         | 0.53%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.53%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.53%   |
| Sunplus Full HD webcam                                      | 1         | 0.53%   |
| Sunplus Dell Integrated Webcam                              | 1         | 0.53%   |
| Silicon Motion Web Camera                                   | 1         | 0.53%   |
| Silicon Motion Silicon Motion Camera                        | 1         | 0.53%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.53%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 0.53%   |
| Realtek Lenovo EasyCamera                                   | 1         | 0.53%   |
| Realtek Integrated Webcam                                   | 1         | 0.53%   |
| Realtek HD Webcam - Realtek                                 | 1         | 0.53%   |
| Realtek HD WebCam                                           | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 40%     |
| Upek                       | 5         | 14.29%  |
| Synaptics                  | 5         | 14.29%  |
| Shenzhen Goodix Technology | 4         | 11.43%  |
| AuthenTec                  | 3         | 8.57%   |
| LighTuning Technology      | 2         | 5.71%   |
| STMicroelectronics         | 1         | 2.86%   |
| Elan Microelectronics      | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 11.43%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 8.57%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 3         | 8.57%   |
| Validity Sensors Synaptics WBDI                            | 3         | 8.57%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 5.71%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 5.71%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 5.71%   |
| Unknown                                                    | 2         | 5.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.86%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.86%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.86%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 2.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.86%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.86%   |
| LighTuning Fingerprint Reader                              | 1         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2.86%   |
| Elan ELAN:Fingerprint                                      | 1         | 2.86%   |
| AuthenTec AES2810                                          | 1         | 2.86%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.86%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 36.36%  |
| Lenovo      | 3         | 27.27%  |
| Broadcom    | 3         | 27.27%  |
| O2 Micro    | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 36.36%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 18.18%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 239       | 72.42%  |
| 1     | 70        | 21.21%  |
| 2     | 18        | 5.45%   |
| 3     | 3         | 0.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 41        | 37.61%  |
| Fingerprint reader       | 35        | 32.11%  |
| Chipcard                 | 10        | 9.17%   |
| Multimedia controller    | 7         | 6.42%   |
| Communication controller | 5         | 4.59%   |
| Unassigned class         | 3         | 2.75%   |
| Storage                  | 3         | 2.75%   |
| Net/wireless             | 3         | 2.75%   |
| Camera                   | 1         | 0.92%   |
| Bluetooth                | 1         | 0.92%   |

