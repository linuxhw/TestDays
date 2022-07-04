Linux in China - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in China.

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

Total: 365

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z87P-D3                     | [2ae62ac227](https://linux-hardware.org/?probe=2ae62ac227) | Jun 30, 2022 |
| MSI           | Z68A-GD80                   | [2e2ca703b0](https://linux-hardware.org/?probe=2e2ca703b0) | Jun 30, 2022 |
| Gigabyte      | EP45-UD3                    | [bb62363ad2](https://linux-hardware.org/?probe=bb62363ad2) | Jun 29, 2022 |
| MSI           | B360M MORTAR                | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| Unknown       | Unknown                     | [b3def4c8ad](https://linux-hardware.org/?probe=b3def4c8ad) | Jun 25, 2022 |
| MSI           | MAG B550M MORTAR            | [209001317a](https://linux-hardware.org/?probe=209001317a) | Jun 23, 2022 |
| MAINBRD       | OPS62A-SHA                  | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| Unknown       | Unknown                     | [2a25ea86fc](https://linux-hardware.org/?probe=2a25ea86fc) | Jun 05, 2022 |
| Unknown       | Unknown                     | [4c36218f66](https://linux-hardware.org/?probe=4c36218f66) | Jun 04, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [a9c714d138](https://linux-hardware.org/?probe=a9c714d138) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| Unknown       | Unknown                     | [24a7b3121f](https://linux-hardware.org/?probe=24a7b3121f) | May 29, 2022 |
| Gigabyte      | X570 GAMING X               | [3ddc17645b](https://linux-hardware.org/?probe=3ddc17645b) | May 29, 2022 |
| Unknown       | Unknown                     | [1da299e36e](https://linux-hardware.org/?probe=1da299e36e) | May 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [91306ce19f](https://linux-hardware.org/?probe=91306ce19f) | May 29, 2022 |
| Intel         | D54250WYK H13922-303        | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| MSI           | H97M-P35                    | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| Intel         | HURONRIVER                  | [1ebb900517](https://linux-hardware.org/?probe=1ebb900517) | May 22, 2022 |
| MSI           | B450M-A PRO MAX             | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| Lenovo        | NOK                         | [567c167a97](https://linux-hardware.org/?probe=567c167a97) | May 20, 2022 |
| MAXSUN        | MS-M3A78EL                  | [98d8c5a6ee](https://linux-hardware.org/?probe=98d8c5a6ee) | May 14, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [a83103153b](https://linux-hardware.org/?probe=a83103153b) | May 12, 2022 |
| TSINGHUA T... | B460M-HDV                   | [3c126b8a1d](https://linux-hardware.org/?probe=3c126b8a1d) | May 10, 2022 |
| Lenovo        | NO DPK                      | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Lenovo        | NO DPK                      | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| OEM           | V1.0                        | [167ee50568](https://linux-hardware.org/?probe=167ee50568) | Apr 29, 2022 |
| ASRock        | Z170 Gaming K4              | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| ASRock        | Z170 Gaming K4              | [81e06a1dcb](https://linux-hardware.org/?probe=81e06a1dcb) | Apr 18, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [c4561b1073](https://linux-hardware.org/?probe=c4561b1073) | Apr 18, 2022 |
| J&W           | J1900T                      | [7c87f17ed7](https://linux-hardware.org/?probe=7c87f17ed7) | Apr 17, 2022 |
| ASRock        | H110M-DVS R2.0              | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| Lenovo        | MAHOBAY 31900005 STD        | [d82d73ba0a](https://linux-hardware.org/?probe=d82d73ba0a) | Apr 12, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [a8e2ef2c76](https://linux-hardware.org/?probe=a8e2ef2c76) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [686ef53bc5](https://linux-hardware.org/?probe=686ef53bc5) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [aad4b24a04](https://linux-hardware.org/?probe=aad4b24a04) | Apr 06, 2022 |
| ASUSTek       | X99-DELUXE II               | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| Unknown       | Unknown                     | [aac8a6f7e4](https://linux-hardware.org/?probe=aac8a6f7e4) | Apr 03, 2022 |
| Lenovo        | 32E9 SDK0T76479 WIN 3423... | [d8dbd14b3e](https://linux-hardware.org/?probe=d8dbd14b3e) | Apr 02, 2022 |
| Lenovo        | QiTianM7150                 | [a6a37565b7](https://linux-hardware.org/?probe=a6a37565b7) | Apr 02, 2022 |
| Inspur        | NF5270M3                    | [053fcd58fc](https://linux-hardware.org/?probe=053fcd58fc) | Mar 26, 2022 |
| ASUSTek       | B360M-D3H                   | [bf6e46cd01](https://linux-hardware.org/?probe=bf6e46cd01) | Mar 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [847b9e1fbb](https://linux-hardware.org/?probe=847b9e1fbb) | Mar 23, 2022 |
| MSI           | B450M MORTAR                | [4c4039754c](https://linux-hardware.org/?probe=4c4039754c) | Mar 13, 2022 |
| Lenovo        | 3187 SDK0L77769 WIN 3423... | [545b878c51](https://linux-hardware.org/?probe=545b878c51) | Mar 10, 2022 |
| ASUSTek       | PRIME H510M-K               | [3edcfcdf53](https://linux-hardware.org/?probe=3edcfcdf53) | Mar 08, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Lenovo        | MAHOBAY                     | [cd7e96054b](https://linux-hardware.org/?probe=cd7e96054b) | Mar 01, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Lenovo        | NOK                         | [05c2b02bd3](https://linux-hardware.org/?probe=05c2b02bd3) | Feb 26, 2022 |
| MSI           | B350 TOMAHAWK               | [a07d445338](https://linux-hardware.org/?probe=a07d445338) | Feb 21, 2022 |
| Lenovo        | NOK                         | [3936474618](https://linux-hardware.org/?probe=3936474618) | Feb 18, 2022 |
| Lenovo        | NOK                         | [1236b9a36b](https://linux-hardware.org/?probe=1236b9a36b) | Feb 17, 2022 |
| MSI           | A88XM-E45                   | [b58bd64798](https://linux-hardware.org/?probe=b58bd64798) | Feb 17, 2022 |
| ECS           | BSWI-DA                     | [2b3dda83e5](https://linux-hardware.org/?probe=2b3dda83e5) | Feb 04, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [0bef76b548](https://linux-hardware.org/?probe=0bef76b548) | Jan 28, 2022 |
| ASUSTek       | PRIME Z370-A                | [53b2c696ff](https://linux-hardware.org/?probe=53b2c696ff) | Jan 26, 2022 |
| ASUSTek       | PRIME Z370-A                | [7b2482036e](https://linux-hardware.org/?probe=7b2482036e) | Jan 26, 2022 |
| Intel         | G41 V1.0                    | [e1f1c99851](https://linux-hardware.org/?probe=e1f1c99851) | Jan 22, 2022 |
| MSI           | H310M-S03                   | [8c009a1259](https://linux-hardware.org/?probe=8c009a1259) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| Dell          | 0MWYPT A02                  | [08d5ba6a97](https://linux-hardware.org/?probe=08d5ba6a97) | Dec 30, 2021 |
| ASRock        | Z170 Gaming K4              | [590ae02fdb](https://linux-hardware.org/?probe=590ae02fdb) | Dec 29, 2021 |
| TSINGHUA T... | B460M-HDV                   | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [50d0f206e1](https://linux-hardware.org/?probe=50d0f206e1) | Dec 21, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [1564f2f5ea](https://linux-hardware.org/?probe=1564f2f5ea) | Dec 18, 2021 |
| Lenovo        | Unknown                     | [64951d70ab](https://linux-hardware.org/?probe=64951d70ab) | Dec 16, 2021 |
| TSINGHUA T... | B460M-HDV                   | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| ASUSTek       | B85M-F                      | [04b3b165f6](https://linux-hardware.org/?probe=04b3b165f6) | Dec 14, 2021 |
| ASRock        | Z170 Gaming K4              | [4f8e294d95](https://linux-hardware.org/?probe=4f8e294d95) | Dec 13, 2021 |
| Lenovo        | 3141 NOK                    | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| MSI           | B450I GAMING PLUS AC        | [fe97757850](https://linux-hardware.org/?probe=fe97757850) | Dec 10, 2021 |
| ASUSTek       | PRO B460M-C                 | [ff8706d7ac](https://linux-hardware.org/?probe=ff8706d7ac) | Dec 07, 2021 |
| OEM           | TOP77D Ver1.0               | [5747ccfcd4](https://linux-hardware.org/?probe=5747ccfcd4) | Dec 07, 2021 |
| ASRock        | B360M-ITX/ac                | [2490a94114](https://linux-hardware.org/?probe=2490a94114) | Dec 07, 2021 |
| AOC           | A815HB                      | [b1aec8b16c](https://linux-hardware.org/?probe=b1aec8b16c) | Dec 04, 2021 |
| OEM           | TOP77D Ver1.0               | [6b91b58b81](https://linux-hardware.org/?probe=6b91b58b81) | Nov 30, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [69a76fd0b6](https://linux-hardware.org/?probe=69a76fd0b6) | Nov 29, 2021 |
| ASUSTek       | PRO B460M-C                 | [b316c12d03](https://linux-hardware.org/?probe=b316c12d03) | Nov 27, 2021 |
| Gigabyte      | H61M-DS2                    | [c487bf6a9c](https://linux-hardware.org/?probe=c487bf6a9c) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [fa956800a1](https://linux-hardware.org/?probe=fa956800a1) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3d27077285](https://linux-hardware.org/?probe=3d27077285) | Nov 24, 2021 |
| ASUSTek       | B85M-G PLUS                 | [e198df930c](https://linux-hardware.org/?probe=e198df930c) | Nov 23, 2021 |
| ASUSTek       | B85M-G PLUS                 | [023ab776cd](https://linux-hardware.org/?probe=023ab776cd) | Nov 23, 2021 |
| Google        | Panther                     | [5e5d9936ec](https://linux-hardware.org/?probe=5e5d9936ec) | Nov 23, 2021 |
| ASRock        | Z170 Gaming K4              | [6a0bda5a7d](https://linux-hardware.org/?probe=6a0bda5a7d) | Nov 22, 2021 |
| Dell          | 0R790T A00                  | [af9a5a76c3](https://linux-hardware.org/?probe=af9a5a76c3) | Nov 22, 2021 |
| Gigabyte      | B85M-D3V-A                  | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| ASRock        | TRX40 Creator               | [bdd3471fa2](https://linux-hardware.org/?probe=bdd3471fa2) | Nov 17, 2021 |
| AOC           | A815HB                      | [e56b509a5a](https://linux-hardware.org/?probe=e56b509a5a) | Nov 16, 2021 |
| ASUSTek       | PRIME Z370-A                | [01b7731b34](https://linux-hardware.org/?probe=01b7731b34) | Nov 14, 2021 |
| Shanghai Z... | EA170_ TBD                  | [edc1846e0f](https://linux-hardware.org/?probe=edc1846e0f) | Nov 10, 2021 |
| Shanghai Z... | EA170_ TBD                  | [9f839630ac](https://linux-hardware.org/?probe=9f839630ac) | Nov 10, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [74d845aae1](https://linux-hardware.org/?probe=74d845aae1) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [cafc4421b2](https://linux-hardware.org/?probe=cafc4421b2) | Oct 29, 2021 |
| Lenovo        | 3107 SDK0L77769 WIN 3423... | [6a7a621271](https://linux-hardware.org/?probe=6a7a621271) | Oct 22, 2021 |
| Unknown       | Unknown                     | [2fb1797d3d](https://linux-hardware.org/?probe=2fb1797d3d) | Oct 19, 2021 |
| ASRock        | B85M Pro4                   | [bf91ce9da1](https://linux-hardware.org/?probe=bf91ce9da1) | Oct 14, 2021 |
| Dell          | 0C96W1 A02                  | [edb83b3d2f](https://linux-hardware.org/?probe=edb83b3d2f) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [3eb7a24e5a](https://linux-hardware.org/?probe=3eb7a24e5a) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [38bb1cfdc4](https://linux-hardware.org/?probe=38bb1cfdc4) | Oct 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [5e8e9aea62](https://linux-hardware.org/?probe=5e8e9aea62) | Oct 12, 2021 |
| ASUSTek       | A55BM-E                     | [970153a68c](https://linux-hardware.org/?probe=970153a68c) | Oct 03, 2021 |
| Lenovo        | MAHOBAY                     | [f1420c5af0](https://linux-hardware.org/?probe=f1420c5af0) | Sep 29, 2021 |
| ASRock        | TRX40 Creator               | [c7b8fcc312](https://linux-hardware.org/?probe=c7b8fcc312) | Sep 29, 2021 |
| Unknown       | Unknown                     | [4c18e17d7d](https://linux-hardware.org/?probe=4c18e17d7d) | Sep 29, 2021 |
| MSI           | B450M MORTAR MAX            | [8adcff21a2](https://linux-hardware.org/?probe=8adcff21a2) | Sep 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | [10ce8f4e5e](https://linux-hardware.org/?probe=10ce8f4e5e) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b62637ba85](https://linux-hardware.org/?probe=b62637ba85) | Sep 25, 2021 |
| ASUSTek       | H87-PRO                     | [508bab38ae](https://linux-hardware.org/?probe=508bab38ae) | Sep 20, 2021 |
| ASUSTek       | H87-PRO                     | [8b09747789](https://linux-hardware.org/?probe=8b09747789) | Sep 20, 2021 |
| Sapphire      | Pure Platinum 970A-PLUS     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| TSINGHUA T... | B460M-HDV                   | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | B360M-BASALT                | [f1783ce369](https://linux-hardware.org/?probe=f1783ce369) | Sep 18, 2021 |
| Lenovo        | NOK                         | [61a15d9531](https://linux-hardware.org/?probe=61a15d9531) | Sep 14, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [a48ec730b7](https://linux-hardware.org/?probe=a48ec730b7) | Sep 13, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [db46242eec](https://linux-hardware.org/?probe=db46242eec) | Sep 13, 2021 |
| ASUSTek       | Z170-A                      | [2d0a7ed28d](https://linux-hardware.org/?probe=2d0a7ed28d) | Aug 28, 2021 |
| ASUSTek       | Z170-A                      | [fc294326ce](https://linux-hardware.org/?probe=fc294326ce) | Aug 28, 2021 |
| Dell          | 0R790T A00                  | [03b37f86b2](https://linux-hardware.org/?probe=03b37f86b2) | Aug 27, 2021 |
| Lenovo        | SHARKBAY NOK                | [33cc1aba5f](https://linux-hardware.org/?probe=33cc1aba5f) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e0e805180d](https://linux-hardware.org/?probe=e0e805180d) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [ce37ed52aa](https://linux-hardware.org/?probe=ce37ed52aa) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [18f0785e64](https://linux-hardware.org/?probe=18f0785e64) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [753b5b706d](https://linux-hardware.org/?probe=753b5b706d) | Aug 18, 2021 |
| Yanling       | YL-KBRL2 Series Ver:1.01    | [ad2f5f75d8](https://linux-hardware.org/?probe=ad2f5f75d8) | Aug 10, 2021 |
| TSINGHUA T... | B460-N2                     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| ASUSTek       | Z97-PRO                     | [a0e65d5ee7](https://linux-hardware.org/?probe=a0e65d5ee7) | Aug 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [07e9ee8610](https://linux-hardware.org/?probe=07e9ee8610) | Aug 02, 2021 |
| Dell          | 0R790T A00                  | [474dfcb3e3](https://linux-hardware.org/?probe=474dfcb3e3) | Jul 26, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [d84332d50b](https://linux-hardware.org/?probe=d84332d50b) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [f68b508049](https://linux-hardware.org/?probe=f68b508049) | Jul 14, 2021 |
| AMD           | BL2 V2.3                    | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| MSI           | Z590-A PRO                  | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| Dell          | 0GX297                      | [f4debf994a](https://linux-hardware.org/?probe=f4debf994a) | Jun 30, 2021 |
| HP            | 18E7                        | [5f0e216922](https://linux-hardware.org/?probe=5f0e216922) | Jun 28, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | [61460e5cfc](https://linux-hardware.org/?probe=61460e5cfc) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | [c916e64b0d](https://linux-hardware.org/?probe=c916e64b0d) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| ASUSTek       | P5QL PRO                    | [c76462e732](https://linux-hardware.org/?probe=c76462e732) | Jun 20, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [c0ecdee03e](https://linux-hardware.org/?probe=c0ecdee03e) | Jun 20, 2021 |
| ASUSTek       | P5QL PRO                    | [8b9f25c98b](https://linux-hardware.org/?probe=8b9f25c98b) | Jun 19, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Lenovo        | H310                        | [309031a039](https://linux-hardware.org/?probe=309031a039) | Jun 12, 2021 |
| Advantech     | DMS-BC30 A101-2             | [e9ee5e90e8](https://linux-hardware.org/?probe=e9ee5e90e8) | Jun 08, 2021 |
| Advantech     | DMS-BC30 A101-2             | [2fd059f38d](https://linux-hardware.org/?probe=2fd059f38d) | Jun 08, 2021 |
| Lenovo        | H310                        | [f36653c4fb](https://linux-hardware.org/?probe=f36653c4fb) | Jun 06, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | [2a8b1a08bc](https://linux-hardware.org/?probe=2a8b1a08bc) | Jun 04, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | [ead2c4250e](https://linux-hardware.org/?probe=ead2c4250e) | Jun 04, 2021 |
| Huanghe       | PRO H410M-C                 | [37534d085b](https://linux-hardware.org/?probe=37534d085b) | Jun 04, 2021 |
| Huanghe       | PRO H410M-C                 | [1c92e63940](https://linux-hardware.org/?probe=1c92e63940) | May 31, 2021 |
| Huanan        | X79 VAA1                    | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [a22fbcde28](https://linux-hardware.org/?probe=a22fbcde28) | May 26, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [59f94e4db6](https://linux-hardware.org/?probe=59f94e4db6) | May 25, 2021 |
| Centerm       | C92                         | [fe4761d2b2](https://linux-hardware.org/?probe=fe4761d2b2) | May 25, 2021 |
| Acer          | Aspire TC-606               | [db910234a6](https://linux-hardware.org/?probe=db910234a6) | May 25, 2021 |
| Soyo          | SY-I5GC2-L                  | [02a90f300e](https://linux-hardware.org/?probe=02a90f300e) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | [91bdc4a9a0](https://linux-hardware.org/?probe=91bdc4a9a0) | May 24, 2021 |
| MSI           | Z590-A PRO                  | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Dell          | 0HN7XN A01                  | [fa2352afac](https://linux-hardware.org/?probe=fa2352afac) | May 19, 2021 |
| Gigabyte      | B365M D2V                   | [887f18105e](https://linux-hardware.org/?probe=887f18105e) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | [644431aa47](https://linux-hardware.org/?probe=644431aa47) | May 17, 2021 |
| Gigabyte      | Z170X-UD3-CF                | [41fbd83170](https://linux-hardware.org/?probe=41fbd83170) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | [d418b8e0e9](https://linux-hardware.org/?probe=d418b8e0e9) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | [b04d956c6e](https://linux-hardware.org/?probe=b04d956c6e) | May 17, 2021 |
| MSI           | Z590-A PRO                  | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| Gigabyte      | B460M AORUS PRO             | [ef3422dd2d](https://linux-hardware.org/?probe=ef3422dd2d) | May 14, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [321f62efb9](https://linux-hardware.org/?probe=321f62efb9) | May 04, 2021 |
| MSI           | B450M MORTAR                | [586195f9e8](https://linux-hardware.org/?probe=586195f9e8) | May 03, 2021 |
| MSI           | B450M MORTAR                | [0f71a5127c](https://linux-hardware.org/?probe=0f71a5127c) | May 01, 2021 |
| Lenovo        | No DPK                      | [15a0f7dbe3](https://linux-hardware.org/?probe=15a0f7dbe3) | Apr 27, 2021 |
| ELSKY         | M219F-6C                    | [85ce077799](https://linux-hardware.org/?probe=85ce077799) | Apr 22, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [c557439d9f](https://linux-hardware.org/?probe=c557439d9f) | Apr 03, 2021 |
| MSI           | B450M MORTAR                | [8406dee7f4](https://linux-hardware.org/?probe=8406dee7f4) | Apr 02, 2021 |
| MSI           | B450M MORTAR                | [6e403bbf50](https://linux-hardware.org/?probe=6e403bbf50) | Apr 02, 2021 |
| SYWZ          | S210H Series                | [2e8183b6eb](https://linux-hardware.org/?probe=2e8183b6eb) | Mar 14, 2021 |
| SYWZ          | S210H Series                | [d0f36756ab](https://linux-hardware.org/?probe=d0f36756ab) | Mar 14, 2021 |
| Dell          | 03CPWF A00                  | [126a2e8974](https://linux-hardware.org/?probe=126a2e8974) | Feb 22, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [0ac46a588c](https://linux-hardware.org/?probe=0ac46a588c) | Feb 21, 2021 |
| Gigabyte      | B85M-D2V-SI                 | [a0779807a2](https://linux-hardware.org/?probe=a0779807a2) | Feb 15, 2021 |
| Dell          | 04VF8V A01                  | [14d2de53c9](https://linux-hardware.org/?probe=14d2de53c9) | Feb 14, 2021 |
| ASRock        | A320M-HDV                   | [d844c4f50e](https://linux-hardware.org/?probe=d844c4f50e) | Feb 05, 2021 |
| ASRock        | A320M-HDV                   | [5c23d11a52](https://linux-hardware.org/?probe=5c23d11a52) | Feb 05, 2021 |
| HUAWEI        | SP1PGUM M1020               | [bd05c84564](https://linux-hardware.org/?probe=bd05c84564) | Feb 04, 2021 |
| Dell          | 06JWJY A00                  | [1f2099e9d3](https://linux-hardware.org/?probe=1f2099e9d3) | Feb 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | [5b274af228](https://linux-hardware.org/?probe=5b274af228) | Feb 02, 2021 |
| ASUSTek       | PRIME Z270-A                | [9c21c30887](https://linux-hardware.org/?probe=9c21c30887) | Jan 30, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | [35d97e2d21](https://linux-hardware.org/?probe=35d97e2d21) | Jan 28, 2021 |
| MSI           | B450I GAMING PLUS AC        | [a1c263681f](https://linux-hardware.org/?probe=a1c263681f) | Jan 26, 2021 |
| ASUSTek       | PRIME H310M-F R2.0          | [3c4d584c27](https://linux-hardware.org/?probe=3c4d584c27) | Jan 26, 2021 |
| ASUSTek       | PRIME H410M-E               | [1b100a591d](https://linux-hardware.org/?probe=1b100a591d) | Jan 19, 2021 |
| Lenovo        | 317E SDK0L77767 WIN 3423... | [6e82572f07](https://linux-hardware.org/?probe=6e82572f07) | Jan 17, 2021 |
| MSI           | B450 TOMAHAWK               | [edbfbb65b8](https://linux-hardware.org/?probe=edbfbb65b8) | Jan 15, 2021 |
| Lenovo        | 3107 NOK                    | [902ea74b31](https://linux-hardware.org/?probe=902ea74b31) | Jan 08, 2021 |
| Google        | Zako                        | [d8df4eefd6](https://linux-hardware.org/?probe=d8df4eefd6) | Jan 01, 2021 |
| Google        | Zako                        | [6bedd150e9](https://linux-hardware.org/?probe=6bedd150e9) | Jan 01, 2021 |
| HP            | 82A4                        | [bf686ef745](https://linux-hardware.org/?probe=bf686ef745) | Jan 01, 2021 |
| Lenovo        | 1.0                         | [897523f5fd](https://linux-hardware.org/?probe=897523f5fd) | Dec 27, 2020 |
| Lenovo        | 1.0                         | [53a763dc24](https://linux-hardware.org/?probe=53a763dc24) | Dec 27, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | [fd025ae38b](https://linux-hardware.org/?probe=fd025ae38b) | Dec 23, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | [a141f2ed51](https://linux-hardware.org/?probe=a141f2ed51) | Dec 22, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [224c36cf4d](https://linux-hardware.org/?probe=224c36cf4d) | Dec 15, 2020 |
| ASRock        | Z170 Gaming K4              | [a246612b17](https://linux-hardware.org/?probe=a246612b17) | Dec 13, 2020 |
| ASUSTek       | PRIME H270-PLUS             | [0c0911cd7b](https://linux-hardware.org/?probe=0c0911cd7b) | Dec 11, 2020 |
| ASUSTek       | PRIME B450M-A               | [b20c8c639e](https://linux-hardware.org/?probe=b20c8c639e) | Dec 08, 2020 |
| HUAWEI        | Kunpeng Desktop             | [cbd268b858](https://linux-hardware.org/?probe=cbd268b858) | Dec 04, 2020 |
| HUAWEI        | Kunpeng Desktop             | [da163e34c7](https://linux-hardware.org/?probe=da163e34c7) | Dec 04, 2020 |
| ASUSTek       | PRIME A520M-K               | [7eb641e51d](https://linux-hardware.org/?probe=7eb641e51d) | Dec 01, 2020 |
| ASUSTek       | B85M-G                      | [216a0f765e](https://linux-hardware.org/?probe=216a0f765e) | Dec 01, 2020 |
| Gigabyte      | B250-D3A-CF                 | [907d35d953](https://linux-hardware.org/?probe=907d35d953) | Nov 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | [d1c0a8df13](https://linux-hardware.org/?probe=d1c0a8df13) | Nov 23, 2020 |
| Gigabyte      | B250-HD3-CF                 | [7975ba3888](https://linux-hardware.org/?probe=7975ba3888) | Nov 23, 2020 |
| Unknown       | Unknown                     | [d58e8b793e](https://linux-hardware.org/?probe=d58e8b793e) | Nov 22, 2020 |
| Unknown       | Unknown                     | [c0e8909067](https://linux-hardware.org/?probe=c0e8909067) | Nov 22, 2020 |
| Unknown       | Unknown                     | [c0d7c657b1](https://linux-hardware.org/?probe=c0d7c657b1) | Nov 22, 2020 |
| Gigabyte      | 970-GAMING                  | [44f42f7676](https://linux-hardware.org/?probe=44f42f7676) | Nov 21, 2020 |
| Colorful T... | C.H110M-K PRO V21           | [c8211ace73](https://linux-hardware.org/?probe=c8211ace73) | Nov 20, 2020 |
| ASUSTek       | PRIME X570-P                | [0999a52054](https://linux-hardware.org/?probe=0999a52054) | Nov 18, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | 8455                        | [8fbf07649a](https://linux-hardware.org/?probe=8fbf07649a) | Nov 03, 2020 |
| Intel         | SKYBAY                      | [ebc35582c8](https://linux-hardware.org/?probe=ebc35582c8) | Oct 23, 2020 |
| Intel         | SKYBAY                      | [ce89df6806](https://linux-hardware.org/?probe=ce89df6806) | Oct 23, 2020 |
| MSI           | X99A XPOWER GAMING TITAN... | [6faf6514f5](https://linux-hardware.org/?probe=6faf6514f5) | Oct 15, 2020 |
| Gigabyte      | B85M-D2V                    | [3393bfd809](https://linux-hardware.org/?probe=3393bfd809) | Sep 25, 2020 |
| Gigabyte      | B85M-D2V                    | [4ef60f3d1d](https://linux-hardware.org/?probe=4ef60f3d1d) | Sep 25, 2020 |
| ASRock        | FM2A85M-DG3                 | [8516ddc869](https://linux-hardware.org/?probe=8516ddc869) | Sep 24, 2020 |
| AEWIN         | SCB-1711A                   | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| RBQ           | RongBotQiu X79.810          | [71e839ea6f](https://linux-hardware.org/?probe=71e839ea6f) | Sep 03, 2020 |
| Lenovo        | 36EF SDK0L77767 WIN 3423... | [a01c93c314](https://linux-hardware.org/?probe=a01c93c314) | Sep 01, 2020 |
| Lenovo        | 36EF SDK0L77767 WIN 3423... | [2800d63edf](https://linux-hardware.org/?probe=2800d63edf) | Aug 30, 2020 |
| Gigabyte      | B450 AORUS M                | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [e32815911a](https://linux-hardware.org/?probe=e32815911a) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [36a4789e67](https://linux-hardware.org/?probe=36a4789e67) | Aug 10, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Lenovo        | NOK                         | [99cea2b8c1](https://linux-hardware.org/?probe=99cea2b8c1) | Jul 22, 2020 |
| Lenovo        | Unknown                     | [9e428d8ef9](https://linux-hardware.org/?probe=9e428d8ef9) | Jul 16, 2020 |
| MSI           | 880GM-E41                   | [620e8dbc2c](https://linux-hardware.org/?probe=620e8dbc2c) | Jul 13, 2020 |
| Gigabyte      | AB350M-DS2-CF               | [014b2718ae](https://linux-hardware.org/?probe=014b2718ae) | Jul 13, 2020 |
| Gigabyte      | AB350M-DS2-CF               | [6ea3c86837](https://linux-hardware.org/?probe=6ea3c86837) | Jul 13, 2020 |
| Gigabyte      | Z77M-D3H                    | [ce5f57a42d](https://linux-hardware.org/?probe=ce5f57a42d) | Jul 09, 2020 |
| Intel         | H81C                        | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [176c1bcb0a](https://linux-hardware.org/?probe=176c1bcb0a) | Jun 24, 2020 |
| MSI           | Z370-OC PRO                 | [a37abc19ef](https://linux-hardware.org/?probe=a37abc19ef) | Jun 08, 2020 |
| ASUSTek       | Z97-PRO                     | [c534bc4bc6](https://linux-hardware.org/?probe=c534bc4bc6) | Jun 04, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [29eb8f828b](https://linux-hardware.org/?probe=29eb8f828b) | May 30, 2020 |
| HP            | 82A1                        | [ddd727fd22](https://linux-hardware.org/?probe=ddd727fd22) | May 25, 2020 |
| HP            | 807D                        | [0523c549d5](https://linux-hardware.org/?probe=0523c549d5) | May 25, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [220e504029](https://linux-hardware.org/?probe=220e504029) | May 23, 2020 |
| HP            | 807D                        | [d82ca940de](https://linux-hardware.org/?probe=d82ca940de) | May 22, 2020 |
| Biostar       | H110MLC                     | [70e9170fa4](https://linux-hardware.org/?probe=70e9170fa4) | May 15, 2020 |
| Dell          | 09PR9H A02                  | [a0f6d2eac4](https://linux-hardware.org/?probe=a0f6d2eac4) | May 11, 2020 |
| ASUSTek       | Z97-C                       | [6eb7ec99eb](https://linux-hardware.org/?probe=6eb7ec99eb) | May 08, 2020 |
| Gigabyte      | X58A-UD3R                   | [a244f111f8](https://linux-hardware.org/?probe=a244f111f8) | May 05, 2020 |
| Gigabyte      | X58A-UD3R                   | [69210022d8](https://linux-hardware.org/?probe=69210022d8) | May 05, 2020 |
| Gigabyte      | F2A88XM-DS2-TE              | [2b96fc655b](https://linux-hardware.org/?probe=2b96fc655b) | Apr 28, 2020 |
| Gigabyte      | F2A88XM-DS2-TE              | [c53b21972a](https://linux-hardware.org/?probe=c53b21972a) | Apr 28, 2020 |
| ASUSTek       | B85M-G                      | [1339b47680](https://linux-hardware.org/?probe=1339b47680) | Apr 22, 2020 |
| Dell          | 042P49 A02                  | [bd064eace3](https://linux-hardware.org/?probe=bd064eace3) | Apr 21, 2020 |
| Lenovo        | Tiger Hill                  | [7f92e05b46](https://linux-hardware.org/?probe=7f92e05b46) | Apr 14, 2020 |
| Dell          | 040DDP A01                  | [ab41c29212](https://linux-hardware.org/?probe=ab41c29212) | Mar 31, 2020 |
| ECS           | H61H2-TAIO                  | [e6f8d21b5a](https://linux-hardware.org/?probe=e6f8d21b5a) | Mar 24, 2020 |
| ASUSTek       | Z170-A                      | [4629800e33](https://linux-hardware.org/?probe=4629800e33) | Mar 19, 2020 |
| Gigabyte      | B85-HD3                     | [fb4cdf6f1a](https://linux-hardware.org/?probe=fb4cdf6f1a) | Mar 09, 2020 |
| ECS           | H61H2-TAIO                  | [6ee3574f22](https://linux-hardware.org/?probe=6ee3574f22) | Feb 26, 2020 |
| ECS           | H61H2-TAIO                  | [32a0959f61](https://linux-hardware.org/?probe=32a0959f61) | Feb 25, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [73afca4618](https://linux-hardware.org/?probe=73afca4618) | Feb 17, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [81586acd13](https://linux-hardware.org/?probe=81586acd13) | Jan 27, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [a9cada02fe](https://linux-hardware.org/?probe=a9cada02fe) | Jan 27, 2020 |
| Colorful T... | C.Q1900M PRO V20            | [17664b4797](https://linux-hardware.org/?probe=17664b4797) | Jan 25, 2020 |
| Colorful T... | C.Q1900M PRO V20            | [8bc2fe0d86](https://linux-hardware.org/?probe=8bc2fe0d86) | Jan 25, 2020 |
| MSI           | B450M MORTAR                | [eb4106d83f](https://linux-hardware.org/?probe=eb4106d83f) | Jan 10, 2020 |
| ASUSTek       | Z97-PRO                     | [e814486254](https://linux-hardware.org/?probe=e814486254) | Jan 07, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [34f134e5b0](https://linux-hardware.org/?probe=34f134e5b0) | Jan 06, 2020 |
| ASUSTek       | H110M-E/M.2                 | [df17ba12c1](https://linux-hardware.org/?probe=df17ba12c1) | Jan 05, 2020 |
| Intel         | MAHOBAY                     | [30a583066a](https://linux-hardware.org/?probe=30a583066a) | Dec 29, 2019 |
| ONDA          | B320-IPC Ver:1.02           | [06286179c2](https://linux-hardware.org/?probe=06286179c2) | Dec 09, 2019 |
| MSI           | X99A XPOWER GAMING TITAN... | [65df5317a4](https://linux-hardware.org/?probe=65df5317a4) | Dec 06, 2019 |
| Dell          | 0XR1GT A00                  | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| ASUSTek       | M5A97                       | [ac3e990070](https://linux-hardware.org/?probe=ac3e990070) | Nov 20, 2019 |
| ASUSTek       | M5A97                       | [742601efb5](https://linux-hardware.org/?probe=742601efb5) | Nov 20, 2019 |
| Gigabyte      | Z87P-D3                     | [db5a6d60dd](https://linux-hardware.org/?probe=db5a6d60dd) | Nov 17, 2019 |
| ASUSTek       | B75M-A                      | [bba74ed5a2](https://linux-hardware.org/?probe=bba74ed5a2) | Nov 15, 2019 |
| HP            | 843C                        | [e5e15df58d](https://linux-hardware.org/?probe=e5e15df58d) | Nov 14, 2019 |
| MSI           | X99A XPOWER GAMING TITAN... | [bda577e787](https://linux-hardware.org/?probe=bda577e787) | Nov 12, 2019 |
| Lenovo        | 3107 NOK                    | [8545691fd8](https://linux-hardware.org/?probe=8545691fd8) | Oct 24, 2019 |
| MSI           | Z370 GAMING PRO CARBON A... | [30939907c1](https://linux-hardware.org/?probe=30939907c1) | Oct 13, 2019 |
| MSI           | Z370 GAMING PRO CARBON A... | [6b0db76cfd](https://linux-hardware.org/?probe=6b0db76cfd) | Oct 12, 2019 |
| ASUSTek       | Z8NA-D6                     | [5eab0577d3](https://linux-hardware.org/?probe=5eab0577d3) | Sep 28, 2019 |
| ASUSTek       | B85M-G PLUS/USB             | [174aed26d5](https://linux-hardware.org/?probe=174aed26d5) | Sep 27, 2019 |
| Lenovo        | QiTianM6900                 | [670fee2c10](https://linux-hardware.org/?probe=670fee2c10) | Sep 20, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [9f0b99fb29](https://linux-hardware.org/?probe=9f0b99fb29) | Sep 03, 2019 |
| Lenovo        | 36EB SDK0L77769 WIN 3423... | [5697eebc76](https://linux-hardware.org/?probe=5697eebc76) | Sep 02, 2019 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5652e9e755](https://linux-hardware.org/?probe=5652e9e755) | Aug 31, 2019 |
| Gigabyte      | Z270-HD3-CF                 | [1245fd6da5](https://linux-hardware.org/?probe=1245fd6da5) | Aug 30, 2019 |
| HP            | 81C7 MVB 0C                 | [931ea9a398](https://linux-hardware.org/?probe=931ea9a398) | Aug 27, 2019 |
| Dell          | 0GDG8Y A00                  | [a055c74af6](https://linux-hardware.org/?probe=a055c74af6) | Aug 18, 2019 |
| Gigabyte      | M68M-S2P                    | [0decbcaa1f](https://linux-hardware.org/?probe=0decbcaa1f) | Aug 16, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [ee8b6a4998](https://linux-hardware.org/?probe=ee8b6a4998) | Aug 14, 2019 |
| ASRock        | X470 Gaming-ITX/ac          | [641383210d](https://linux-hardware.org/?probe=641383210d) | Aug 12, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [e87b327f29](https://linux-hardware.org/?probe=e87b327f29) | Aug 11, 2019 |
| AMI           | PB_1900A                    | [2c3f429517](https://linux-hardware.org/?probe=2c3f429517) | Aug 10, 2019 |
| ASUSTek       | Z97-AR                      | [510b031ce9](https://linux-hardware.org/?probe=510b031ce9) | Aug 09, 2019 |
| Lenovo        | 36E7 SDK0L77769 WIN 3423... | [69d10d1093](https://linux-hardware.org/?probe=69d10d1093) | Aug 02, 2019 |
| Dell          | 0N9Y46 A00                  | [3548830389](https://linux-hardware.org/?probe=3548830389) | Jul 23, 2019 |
| Gigabyte      | B250M-D3V-CF                | [cba535c695](https://linux-hardware.org/?probe=cba535c695) | Jul 18, 2019 |
| HP            | 0B10H                       | [758924e4f2](https://linux-hardware.org/?probe=758924e4f2) | Jul 08, 2019 |
| Lenovo        | MAHOBAY NOK                 | [74dfe126d0](https://linux-hardware.org/?probe=74dfe126d0) | Jul 04, 2019 |
| Dell          | 0DNKMN A00                  | [24870345d1](https://linux-hardware.org/?probe=24870345d1) | Jun 25, 2019 |
| Dell          | 0DNKMN A00                  | [44e012b7fb](https://linux-hardware.org/?probe=44e012b7fb) | Jun 25, 2019 |
| Dell          | 0C96W1 A03                  | [3d80eacdfc](https://linux-hardware.org/?probe=3d80eacdfc) | Jun 18, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [579eebbcea](https://linux-hardware.org/?probe=579eebbcea) | Jun 07, 2019 |
| ASUSTek       | P8P67 LE                    | [63f1b6d26c](https://linux-hardware.org/?probe=63f1b6d26c) | Jun 06, 2019 |
| ASUSTek       | P8P67 LE                    | [928d66c1a0](https://linux-hardware.org/?probe=928d66c1a0) | Jun 06, 2019 |
| ASUSTek       | P8P67 LE                    | [7ece60be1d](https://linux-hardware.org/?probe=7ece60be1d) | Jun 05, 2019 |
| ASUSTek       | P8P67 LE                    | [83a1805c76](https://linux-hardware.org/?probe=83a1805c76) | Jun 05, 2019 |
| Lenovo        | ZHENGJIUZHE REN7000-28IC... | [1b85d8db4e](https://linux-hardware.org/?probe=1b85d8db4e) | Jun 04, 2019 |
| Gigabyte      | B85M-D2V-SI                 | [6be6da3a8e](https://linux-hardware.org/?probe=6be6da3a8e) | May 31, 2019 |
| Gigabyte      | B85M-D2V-SI                 | [900bc7e93c](https://linux-hardware.org/?probe=900bc7e93c) | May 31, 2019 |
| ASUSTek       | PRIME H310T                 | [851b9539e3](https://linux-hardware.org/?probe=851b9539e3) | May 24, 2019 |
| Dell          | 0XFWHV A00                  | [6dac78db97](https://linux-hardware.org/?probe=6dac78db97) | May 23, 2019 |
| Dell          | 0XFWHV A00                  | [82e6a2d735](https://linux-hardware.org/?probe=82e6a2d735) | May 19, 2019 |
| ASUSTek       | P6X58D PREMIUM              | [e9440445bc](https://linux-hardware.org/?probe=e9440445bc) | May 09, 2019 |
| Gigabyte      | B85N PHOENIX-CF             | [734eb3795e](https://linux-hardware.org/?probe=734eb3795e) | May 08, 2019 |
| ASUSTek       | M2A-VM                      | [3a02e6759d](https://linux-hardware.org/?probe=3a02e6759d) | May 08, 2019 |
| ASUSTek       | H61M-E                      | [6f9f39bbb6](https://linux-hardware.org/?probe=6f9f39bbb6) | May 07, 2019 |
| ASUSTek       | M2A-VM                      | [ac318056f7](https://linux-hardware.org/?probe=ac318056f7) | May 07, 2019 |
| Acer          | Aspire TC-606               | [5de5deb65e](https://linux-hardware.org/?probe=5de5deb65e) | May 06, 2019 |
| Lenovo        | SHARKBAY NOK                | [8df3c6b792](https://linux-hardware.org/?probe=8df3c6b792) | May 06, 2019 |
| Acer          | Aspire TC-606               | [1900e5ff06](https://linux-hardware.org/?probe=1900e5ff06) | May 06, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [61bd5624bb](https://linux-hardware.org/?probe=61bd5624bb) | Apr 30, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [b0a660db1e](https://linux-hardware.org/?probe=b0a660db1e) | Apr 23, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [3fd02cfa82](https://linux-hardware.org/?probe=3fd02cfa82) | Apr 23, 2019 |
| ASUSTek       | B85M-G PLUS/USB             | [8f686df361](https://linux-hardware.org/?probe=8f686df361) | Apr 15, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [6a9582e524](https://linux-hardware.org/?probe=6a9582e524) | Apr 10, 2019 |
| ASRock        | B360M-HDV                   | [59151791cf](https://linux-hardware.org/?probe=59151791cf) | Apr 09, 2019 |
| Gigabyte      | B150M-Power2-EC-CF          | [68b2380c53](https://linux-hardware.org/?probe=68b2380c53) | Apr 05, 2019 |
| Gigabyte      | Z170X-Gaming 5              | [4efc7fbdc6](https://linux-hardware.org/?probe=4efc7fbdc6) | Apr 01, 2019 |
| Lenovo        | SHARKBAY NOK                | [14cba25e3e](https://linux-hardware.org/?probe=14cba25e3e) | Apr 01, 2019 |
| Lenovo        | 1030 SBB0J05441 WIN 3305... | [92262238c3](https://linux-hardware.org/?probe=92262238c3) | Mar 28, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [175525d48c](https://linux-hardware.org/?probe=175525d48c) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [dccca67c2e](https://linux-hardware.org/?probe=dccca67c2e) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [d0787d5045](https://linux-hardware.org/?probe=d0787d5045) | Mar 25, 2019 |
| Lenovo        | 36E7 SDK0L77767 WIN 3423... | [80816fc39e](https://linux-hardware.org/?probe=80816fc39e) | Mar 25, 2019 |
| Gigabyte      | Z87-HD3                     | [050c0abdc8](https://linux-hardware.org/?probe=050c0abdc8) | Mar 18, 2019 |
| ASUSTek       | PRIME Z370-P II             | [0b6eea7daa](https://linux-hardware.org/?probe=0b6eea7daa) | Mar 15, 2019 |
| Yeston Dig... | YESTON A78L Policeman V3... | [3a74ed7842](https://linux-hardware.org/?probe=3a74ed7842) | Mar 12, 2019 |
| Yeston Dig... | YESTON A78L Policeman V3... | [3c900dd5ac](https://linux-hardware.org/?probe=3c900dd5ac) | Mar 12, 2019 |
| Gigabyte      | Z87-HD3                     | [a4ad17d97c](https://linux-hardware.org/?probe=a4ad17d97c) | Mar 02, 2019 |
| ASUSTek       | PRIME Z370-A                | [a9e837c9eb](https://linux-hardware.org/?probe=a9e837c9eb) | Feb 08, 2019 |
| Lenovo        | 36E7 SDK0L77769 WIN 3423... | [1b722df896](https://linux-hardware.org/?probe=1b722df896) | Jan 21, 2019 |
| ASUSTek       | PRIME B450M-A               | [e077ae4d59](https://linux-hardware.org/?probe=e077ae4d59) | Jan 20, 2019 |
| HP            | 2B4F                        | [188b0e90bc](https://linux-hardware.org/?probe=188b0e90bc) | Jan 08, 2019 |
| Dell          | 077RRV A00                  | [c7b9c0beb8](https://linux-hardware.org/?probe=c7b9c0beb8) | Dec 29, 2018 |
| Dell          | 077RRV A00                  | [88d3983de4](https://linux-hardware.org/?probe=88d3983de4) | Dec 29, 2018 |
| ASUSTek       | B85M-G PLUS/USB             | [cbb464c414](https://linux-hardware.org/?probe=cbb464c414) | Dec 04, 2018 |
| Lenovo        | 3102 SDK0L77769 WIN 3423... | [2143ae0253](https://linux-hardware.org/?probe=2143ae0253) | Nov 13, 2018 |
| Huanan        | X79 PLUS V6.11              | [0a36000504](https://linux-hardware.org/?probe=0a36000504) | Nov 05, 2018 |
| Huanan        | X79 V1.4                    | [1204ed863a](https://linux-hardware.org/?probe=1204ed863a) | Oct 29, 2018 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | [73b72b86b8](https://linux-hardware.org/?probe=73b72b86b8) | Oct 29, 2018 |
| Gigabyte      | F2A88XM-D3H                 | [94d087771b](https://linux-hardware.org/?probe=94d087771b) | Sep 24, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 18.04                 | 45       | 16.67%  |
| Ubuntu 20.04                 | 42       | 15.56%  |
| Arch                         | 16       | 5.93%   |
| Ubuntu 19.04                 | 11       | 4.07%   |
| Ubuntu 16.04                 | 9        | 3.33%   |
| Ubuntu 21.04                 | 8        | 2.96%   |
| UOS 20                       | 6        | 2.22%   |
| Ubuntu 19.10                 | 6        | 2.22%   |
| OpenMandriva 4.3             | 6        | 2.22%   |
| Arch Rolling                 | 6        | 2.22%   |
| Ubuntu 21.10                 | 5        | 1.85%   |
| OpenMandriva 4.2             | 5        | 1.85%   |
| Manjaro                      | 5        | 1.85%   |
| Ubuntu 18.10                 | 4        | 1.48%   |
| Fedora 32                    | 4        | 1.48%   |
| Ubuntu 22.04                 | 3        | 1.11%   |
| Ubuntu 20.10                 | 3        | 1.11%   |
| OpenMandriva 4.50            | 3        | 1.11%   |
| Linux Mint 20.3              | 3        | 1.11%   |
| Linux Mint 20.2              | 3        | 1.11%   |
| KDE neon 20.04               | 3        | 1.11%   |
| Gentoo 2.7                   | 3        | 1.11%   |
| Debian 9                     | 3        | 1.11%   |
| Debian 11                    | 3        | 1.11%   |
| Debian 10                    | 3        | 1.11%   |
| CentOS 7                     | 3        | 1.11%   |
| Zorin 16                     | 2        | 0.74%   |
| Pop!_OS 21.04                | 2        | 0.74%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.74%   |
| Linux Mint 20.1              | 2        | 0.74%   |
| Gentoo 2.6                   | 2        | 0.74%   |
| Fedora 36                    | 2        | 0.74%   |
| Fedora 33                    | 2        | 0.74%   |
| Debian Unstable              | 2        | 0.74%   |
| Debian 8                     | 2        | 0.74%   |
| CentOS 8                     | 2        | 0.74%   |
| Atz 11.3                     | 2        | 0.74%   |
| Xubuntu 18.04                | 1        | 0.37%   |
| Ubuntu Kylin 22.04           | 1        | 0.37%   |
| ROSA R9                      | 1        | 0.37%   |
| ROSA R11.1                   | 1        | 0.37%   |
| ROSA R10                     | 1        | 0.37%   |
| ROSA 12.1                    | 1        | 0.37%   |
| RHEL 8                       | 1        | 0.37%   |
| RedFlag 11.0                 | 1        | 0.37%   |
| RED X4                       | 1        | 0.37%   |
| Pop!_OS 20.04                | 1        | 0.37%   |
| NFS Desktop 5.0              | 1        | 0.37%   |
| NFS Desktop 3.1              | 1        | 0.37%   |
| MOS 10                       | 1        | 0.37%   |
| Manjaro 21.1.2               | 1        | 0.37%   |
| Manjaro 20.2.1               | 1        | 0.37%   |
| Manjaro 20.0                 | 1        | 0.37%   |
| Manjaro 19.0.2               | 1        | 0.37%   |
| Manjaro 18.1.5               | 1        | 0.37%   |
| Linux Mint 19.3              | 1        | 0.37%   |
| Linux Mint 19.2              | 1        | 0.37%   |
| Linux Mint 18.3              | 1        | 0.37%   |
| Kubuntu 20.04                | 1        | 0.37%   |
| KDE neon 18.04               | 1        | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 132      | 49.62%  |
| Arch         | 22       | 8.27%   |
| OpenMandriva | 14       | 5.26%   |
| Debian       | 14       | 5.26%   |
| Linux Mint   | 11       | 4.14%   |
| Manjaro      | 10       | 3.76%   |
| Fedora       | 10       | 3.76%   |
| Deepin       | 8        | 3.01%   |
| Gentoo       | 5        | 1.88%   |
| CentOS       | 5        | 1.88%   |
| ROSA         | 4        | 1.5%    |
| KDE neon     | 4        | 1.5%    |
| Pop!_OS      | 3        | 1.13%   |
| Clear Linux  | 3        | 1.13%   |
| Zorin        | 2        | 0.75%   |
| openSUSE     | 2        | 0.75%   |
| NFS Desktop  | 2        | 0.75%   |
| Elementary   | 2        | 0.75%   |
| Atz          | 2        | 0.75%   |
| Xubuntu      | 1        | 0.38%   |
| Ubuntu Kylin | 1        | 0.38%   |
| RHEL         | 1        | 0.38%   |
| RedFlag      | 1        | 0.38%   |
| RED          | 1        | 0.38%   |
| Kubuntu      | 1        | 0.38%   |
| Endless      | 1        | 0.38%   |
| BlackPanther | 1        | 0.38%   |
| ArcoLinux    | 1        | 0.38%   |
| AOSC OS      | 1        | 0.38%   |
| ALT Linux    | 1        | 0.38%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.0.0-23-generic         | 6        | 2.11%   |
| 5.16.7-desktop-1omv4003  | 5        | 1.76%   |
| 5.13.0-22-generic        | 5        | 1.76%   |
| 5.10.14-desktop-1omv4002 | 5        | 1.76%   |
| 5.4.0-58-generic         | 4        | 1.41%   |
| 5.11.0-43-generic        | 4        | 1.41%   |
| 5.0.0-25-generic         | 4        | 1.41%   |
| 4.18.0-16-generic        | 4        | 1.41%   |
| 5.8.0-50-generic         | 3        | 1.06%   |
| 5.4.0-74-generic         | 3        | 1.06%   |
| 5.13.0-30-generic        | 3        | 1.06%   |
| 5.12.4-desktop-1omv4050  | 3        | 1.06%   |
| 5.11.0-41-generic        | 3        | 1.06%   |
| 5.10.35-gentoo           | 3        | 1.06%   |
| 4.18.0-10-generic        | 3        | 1.06%   |
| 4.15.0-58-generic        | 3        | 1.06%   |
| 4.1.42-rivoreo-powerpc64 | 3        | 1.06%   |
| 5.8.0-63-generic         | 2        | 0.7%    |
| 5.8.0-43-generic         | 2        | 0.7%    |
| 5.4.0-73-generic         | 2        | 0.7%    |
| 5.4.0-54-generic         | 2        | 0.7%    |
| 5.4.0-49-generic         | 2        | 0.7%    |
| 5.4.0-42-generic         | 2        | 0.7%    |
| 5.4.0-40-generic         | 2        | 0.7%    |
| 5.4.0-33-generic         | 2        | 0.7%    |
| 5.4.0-29-generic         | 2        | 0.7%    |
| 5.3.0-28-generic         | 2        | 0.7%    |
| 5.13.0-44-generic        | 2        | 0.7%    |
| 5.13.0-27-generic        | 2        | 0.7%    |
| 5.11.0-40-generic        | 2        | 0.7%    |
| 5.11.0-37-generic        | 2        | 0.7%    |
| 5.1.4-050104-generic     | 2        | 0.7%    |
| 5.0.0-37-generic         | 2        | 0.7%    |
| 5.0.0-36-generic         | 2        | 0.7%    |
| 5.0.0-29-generic         | 2        | 0.7%    |
| 5.0.0-13-generic         | 2        | 0.7%    |
| 4.9.0-8-amd64            | 2        | 0.7%    |
| 4.19.0-amd64-desktop     | 2        | 0.7%    |
| 4.18.0-25-generic        | 2        | 0.7%    |
| 4.18.0-15-generic        | 2        | 0.7%    |
| 4.15.0-74-generic        | 2        | 0.7%    |
| 4.15.0-50-generic        | 2        | 0.7%    |
| 4.15.0-43-generic        | 2        | 0.7%    |
| 4.13.0-36-generic        | 2        | 0.7%    |
| 5.9.9-arch1-1            | 1        | 0.35%   |
| 5.9.8-xanmod1-cachy      | 1        | 0.35%   |
| 5.9.8-200.fc33.x86_64    | 1        | 0.35%   |
| 5.9.2-arch1-1            | 1        | 0.35%   |
| 5.9.14-arch1-1           | 1        | 0.35%   |
| 5.9.11-arch2-1           | 1        | 0.35%   |
| 5.9.10-arch1-1           | 1        | 0.35%   |
| 5.9.10-050910-generic    | 1        | 0.35%   |
| 5.8.16-2-MANJARO         | 1        | 0.35%   |
| 5.8.0-41-generic         | 1        | 0.35%   |
| 5.8.0-40-generic         | 1        | 0.35%   |
| 5.8.0-39-generic         | 1        | 0.35%   |
| 5.8.0-38-generic         | 1        | 0.35%   |
| 5.8.0-36-generic         | 1        | 0.35%   |
| 5.8.0-31-generic         | 1        | 0.35%   |
| 5.7.8-200.fc32.x86_64    | 1        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 35       | 12.73%  |
| 5.0.0   | 23       | 8.36%   |
| 4.15.0  | 23       | 8.36%   |
| 5.11.0  | 19       | 6.91%   |
| 4.18.0  | 18       | 6.55%   |
| 5.13.0  | 15       | 5.45%   |
| 5.8.0   | 13       | 4.73%   |
| 5.3.0   | 7        | 2.55%   |
| 4.19.0  | 7        | 2.55%   |
| 5.16.7  | 5        | 1.82%   |
| 5.10.14 | 5        | 1.82%   |
| 5.10.0  | 4        | 1.45%   |
| 5.12.4  | 3        | 1.09%   |
| 5.10.35 | 3        | 1.09%   |
| 4.9.0   | 3        | 1.09%   |
| 4.1.42  | 3        | 1.09%   |
| 5.9.8   | 2        | 0.73%   |
| 5.9.10  | 2        | 0.73%   |
| 5.7.7   | 2        | 0.73%   |
| 5.6.14  | 2        | 0.73%   |
| 5.17.0  | 2        | 0.73%   |
| 5.16.13 | 2        | 0.73%   |
| 5.16.0  | 2        | 0.73%   |
| 5.15.0  | 2        | 0.73%   |
| 5.13.13 | 2        | 0.73%   |
| 5.10.36 | 2        | 0.73%   |
| 5.10.19 | 2        | 0.73%   |
| 5.1.4   | 2        | 0.73%   |
| 4.4.0   | 2        | 0.73%   |
| 4.13.0  | 2        | 0.73%   |
| 3.10.0  | 2        | 0.73%   |
| 5.9.9   | 1        | 0.36%   |
| 5.9.2   | 1        | 0.36%   |
| 5.9.14  | 1        | 0.36%   |
| 5.9.11  | 1        | 0.36%   |
| 5.8.16  | 1        | 0.36%   |
| 5.7.8   | 1        | 0.36%   |
| 5.7.2   | 1        | 0.36%   |
| 5.6.8   | 1        | 0.36%   |
| 5.6.7   | 1        | 0.36%   |
| 5.6.0   | 1        | 0.36%   |
| 5.5.3   | 1        | 0.36%   |
| 5.4.92  | 1        | 0.36%   |
| 5.4.72  | 1        | 0.36%   |
| 5.4.6   | 1        | 0.36%   |
| 5.4.50  | 1        | 0.36%   |
| 5.4.32  | 1        | 0.36%   |
| 5.4.27  | 1        | 0.36%   |
| 5.4.2   | 1        | 0.36%   |
| 5.4.109 | 1        | 0.36%   |
| 5.2.0   | 1        | 0.36%   |
| 5.18.7  | 1        | 0.36%   |
| 5.18.5  | 1        | 0.36%   |
| 5.17.9  | 1        | 0.36%   |
| 5.17.8  | 1        | 0.36%   |
| 5.17.7  | 1        | 0.36%   |
| 5.17.4  | 1        | 0.36%   |
| 5.17.1  | 1        | 0.36%   |
| 5.15.5  | 1        | 0.36%   |
| 5.15.41 | 1        | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 43       | 15.75%  |
| 5.0     | 25       | 9.16%   |
| 5.10    | 23       | 8.42%   |
| 4.15    | 23       | 8.42%   |
| 5.11    | 21       | 7.69%   |
| 4.18    | 18       | 6.59%   |
| 5.13    | 17       | 6.23%   |
| 5.8     | 14       | 5.13%   |
| 5.16    | 9        | 3.3%    |
| 5.9     | 8        | 2.93%   |
| 5.15    | 8        | 2.93%   |
| 4.19    | 8        | 2.93%   |
| 5.3     | 7        | 2.56%   |
| 5.17    | 7        | 2.56%   |
| 5.12    | 7        | 2.56%   |
| 5.6     | 5        | 1.83%   |
| 4.9     | 5        | 1.83%   |
| 5.7     | 4        | 1.47%   |
| 5.14    | 4        | 1.47%   |
| 4.1     | 3        | 1.1%    |
| 5.18    | 2        | 0.73%   |
| 5.1     | 2        | 0.73%   |
| 4.4     | 2        | 0.73%   |
| 4.13    | 2        | 0.73%   |
| 3.10    | 2        | 0.73%   |
| 5.5     | 1        | 0.37%   |
| 5.2     | 1        | 0.37%   |
| 4.20    | 1        | 0.37%   |
| 4.14    | 1        | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 252      | 95.45%  |
| riscv64 | 3        | 1.14%   |
| ppc64   | 3        | 1.14%   |
| aarch64 | 3        | 1.14%   |
| i686    | 2        | 0.76%   |
| mips64  | 1        | 0.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 109      | 41.13%  |
| Unknown    | 71       | 26.79%  |
| KDE5       | 30       | 11.32%  |
| XFCE       | 15       | 5.66%   |
| KDE        | 8        | 3.02%   |
| X-Cinnamon | 6        | 2.26%   |
| Unity      | 6        | 2.26%   |
| Deepin     | 6        | 2.26%   |
| Pantheon   | 2        | 0.75%   |
| MATE       | 2        | 0.75%   |
| KDE4       | 2        | 0.75%   |
| i3         | 2        | 0.75%   |
| Cinnamon   | 2        | 0.75%   |
| UKUI       | 1        | 0.38%   |
| sway       | 1        | 0.38%   |
| LXDE       | 1        | 0.38%   |
| Budgie     | 1        | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 185      | 70.08%  |
| Unknown | 32       | 12.12%  |
| Wayland | 31       | 11.74%  |
| Tty     | 16       | 6.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 154      | 57.89%  |
| GDM     | 34       | 12.78%  |
| SDDM    | 29       | 10.9%   |
| GDM3    | 20       | 7.52%   |
| LightDM | 19       | 7.14%   |
| TDM     | 7        | 2.63%   |
| KDM     | 2        | 0.75%   |
| LXDM    | 1        | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| zh_CN       | 114      | 42.7%   |
| en_US       | 79       | 29.59%  |
| Unknown     | 59       | 22.1%   |
| C           | 7        | 2.62%   |
| en_GB       | 2        | 0.75%   |
| ru_RU       | 1        | 0.37%   |
| ja_JP       | 1        | 0.37%   |
| en_US.utf-8 | 1        | 0.37%   |
| en_SG       | 1        | 0.37%   |
| en_HK       | 1        | 0.37%   |
| en_AU       | 1        | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 135      | 50.94%  |
| BIOS | 130      | 49.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 215      | 80.52%  |
| Overlay    | 14       | 5.24%   |
| Btrfs      | 13       | 4.87%   |
| Xfs        | 12       | 4.49%   |
| Unknown    | 8        | 3%      |
| Zfs        | 3        | 1.12%   |
| Reiserfs   | 1        | 0.37%   |
| Fuse.sshfs | 1        | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 154      | 58.33%  |
| GPT     | 77       | 29.17%  |
| MBR     | 33       | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 219      | 82.33%  |
| Yes       | 47       | 17.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 161      | 60.53%  |
| Yes       | 105      | 39.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUSTek Computer               | 63       | 23.86%  |
| Lenovo                         | 39       | 14.77%  |
| Gigabyte Technology            | 39       | 14.77%  |
| MSI                            | 27       | 10.23%  |
| Dell                           | 18       | 6.82%   |
| ASRock                         | 10       | 3.79%   |
| Hewlett-Packard                | 9        | 3.41%   |
| Unknown                        | 9        | 3.41%   |
| Intel                          | 7        | 2.65%   |
| TSINGHUA TONGFANG COMPUTER     | 5        | 1.89%   |
| Huanan                         | 3        | 1.14%   |
| OEM                            | 2        | 0.76%   |
| HUAWEI                         | 2        | 0.76%   |
| Google                         | 2        | 0.76%   |
| ECS                            | 2        | 0.76%   |
| Colorful Technology            | 2        | 0.76%   |
| Acer                           | 2        | 0.76%   |
| Yeston Digital Technology      | 1        | 0.38%   |
| Yanling                        | 1        | 0.38%   |
| SYWZ                           | 1        | 0.38%   |
| Soyo                           | 1        | 0.38%   |
| Shanghai Zhaoxin Semiconductor | 1        | 0.38%   |
| Sapphire                       | 1        | 0.38%   |
| RBQ                            | 1        | 0.38%   |
| ONDA                           | 1        | 0.38%   |
| MAXSUN                         | 1        | 0.38%   |
| MAINBRD                        | 1        | 0.38%   |
| LORD ELECTRONICS               | 1        | 0.38%   |
| Loongson                       | 1        | 0.38%   |
| J&W                            | 1        | 0.38%   |
| Inspur                         | 1        | 0.38%   |
| Huanghe                        | 1        | 0.38%   |
| ELSKY                          | 1        | 0.38%   |
| Centerm                        | 1        | 0.38%   |
| Biostar                        | 1        | 0.38%   |
| AOC                            | 1        | 0.38%   |
| AMI                            | 1        | 0.38%   |
| AMD                            | 1        | 0.38%   |
| AEWIN                          | 1        | 0.38%   |
| Advantech                      | 1        | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 11       | 4.17%   |
| ASUS All Series                                   | 10       | 3.79%   |
| TSINGHUA TONGFANG COMPUTER E500                   | 5        | 1.89%   |
| MSI MS-7B89                                       | 5        | 1.89%   |
| MSI MS-7C94                                       | 3        | 1.14%   |
| ASUS TUF Gaming B550M-PLUS                        | 3        | 1.14%   |
| ASUS M5A78L-M LX3 PLUS                            | 3        | 1.14%   |
| MSI MS-7A40                                       | 2        | 0.76%   |
| Lenovo YangTianT4900c-00 90ETCTO1WW               | 2        | 0.76%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW          | 2        | 0.76%   |
| Gigabyte Z87P-D3                                  | 2        | 0.76%   |
| Gigabyte B85M-D2V-SI                              | 2        | 0.76%   |
| Dell OptiPlex 9020                                | 2        | 0.76%   |
| Dell OptiPlex 7060                                | 2        | 0.76%   |
| ASUS Z170-A                                       | 2        | 0.76%   |
| ASUS TUF Gaming Z590-PLUS WIFI                    | 2        | 0.76%   |
| ASUS TUF B450M-PLUS GAMING                        | 2        | 0.76%   |
| ASUS PRIME Z370-A                                 | 2        | 0.76%   |
| ASUS PRIME B450M-A                                | 2        | 0.76%   |
| ASRock Z170 Gaming K4                             | 2        | 0.76%   |
| Acer Aspire TC-606                                | 2        | 0.76%   |
| Yeston Digital YESTON A78L Policeman V3.1         | 1        | 0.38%   |
| Yanling YL-KBRL2 Series                           | 1        | 0.38%   |
| SYWZ S210H Series                                 | 1        | 0.38%   |
| Soyo SY-I5GC2-L                                   | 1        | 0.38%   |
| Shanghai Zhaoxin ZXE CRB                          | 1        | 0.38%   |
| Sapphire Pure Platinum 970A-PLUS                  | 1        | 0.38%   |
| RBQ RongBotQiu                                    | 1        | 0.38%   |
| ONDA ONDA B320-IPC                                | 1        | 0.38%   |
| OEM V1.0                                          | 1        | 0.38%   |
| OEM TOP77D                                        | 1        | 0.38%   |
| MSI MS-7D09                                       | 1        | 0.38%   |
| MSI MS-7C95                                       | 1        | 0.38%   |
| MSI MS-7C82                                       | 1        | 0.38%   |
| MSI MS-7C52                                       | 1        | 0.38%   |
| MSI MS-7C37                                       | 1        | 0.38%   |
| MSI MS-7C18                                       | 1        | 0.38%   |
| MSI MS-7C02                                       | 1        | 0.38%   |
| MSI MS-7B93                                       | 1        | 0.38%   |
| MSI MS-7B48                                       | 1        | 0.38%   |
| MSI MS-7B45                                       | 1        | 0.38%   |
| MSI MS-7B23                                       | 1        | 0.38%   |
| MSI MS-7A34                                       | 1        | 0.38%   |
| MSI MS-7A21                                       | 1        | 0.38%   |
| MSI MS-7817                                       | 1        | 0.38%   |
| MSI MS-7721                                       | 1        | 0.38%   |
| MSI MS-7672                                       | 1        | 0.38%   |
| MSI MS-7623                                       | 1        | 0.38%   |
| MAXSUN MS-M3A78EL                                 | 1        | 0.38%   |
| MAINBRD OPS62A-SHA                                | 1        | 0.38%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 0.38%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev              | 1        | 0.38%   |
| Lenovo ZHENGJIUZHE REN7000-28ICB 90K2000PCP       | 1        | 0.38%   |
| Lenovo ZHENGJIUZHE REN7000-28ICB 90K2000DCP       | 1        | 0.38%   |
| Lenovo ZHENGJIUZHE REN7000-28ICB 90K2000ACP       | 1        | 0.38%   |
| Lenovo ZHENGJIUZHE REN7000-25ICZ 90JC0000CP       | 1        | 0.38%   |
| Lenovo YangTianT4900v-00 90MCCTO1WW               | 1        | 0.38%   |
| Lenovo YangTianT4900v-00                          | 1        | 0.38%   |
| Lenovo YangTianT4900d-00 90GKCTO1WW               | 1        | 0.38%   |
| Lenovo XINYUANMENGH520r56 Product                 | 1        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS PRIME                           | 15       | 5.68%   |
| Dell OptiPlex                        | 12       | 4.55%   |
| ASUS TUF                             | 11       | 4.17%   |
| Unknown                              | 11       | 4.17%   |
| ASUS All                             | 10       | 3.79%   |
| Lenovo ThinkCentre                   | 9        | 3.41%   |
| ASUS ROG                             | 6        | 2.27%   |
| TSINGHUA TONGFANG COMPUTER E500      | 5        | 1.89%   |
| MSI MS-7B89                          | 5        | 1.89%   |
| Lenovo ZHENGJIUZHE                   | 4        | 1.52%   |
| Lenovo ThinkStation                  | 4        | 1.52%   |
| MSI MS-7C94                          | 3        | 1.14%   |
| Huanan X79                           | 3        | 1.14%   |
| HP ProDesk                           | 3        | 1.14%   |
| Dell Inspiron                        | 3        | 1.14%   |
| ASUS M5A78L-M                        | 3        | 1.14%   |
| MSI MS-7A40                          | 2        | 0.76%   |
| Lenovo YangTianT4900v-00             | 2        | 0.76%   |
| Lenovo YangTianT4900c-00             | 2        | 0.76%   |
| Gigabyte Z87P-D3                     | 2        | 0.76%   |
| Gigabyte X570                        | 2        | 0.76%   |
| Gigabyte B85M-D2V-SI                 | 2        | 0.76%   |
| Gigabyte B450                        | 2        | 0.76%   |
| Dell Precision                       | 2        | 0.76%   |
| ASUS Z170-A                          | 2        | 0.76%   |
| ASUS M5A97                           | 2        | 0.76%   |
| ASRock Z170                          | 2        | 0.76%   |
| Acer Aspire                          | 2        | 0.76%   |
| Yeston Digital YESTON                | 1        | 0.38%   |
| Yanling YL-KBRL2                     | 1        | 0.38%   |
| SYWZ S210H                           | 1        | 0.38%   |
| Soyo SY-I5GC2-L                      | 1        | 0.38%   |
| Shanghai Zhaoxin ZXE                 | 1        | 0.38%   |
| Sapphire Pure                        | 1        | 0.38%   |
| RBQ RongBotQiu                       | 1        | 0.38%   |
| ONDA ONDA                            | 1        | 0.38%   |
| OEM V1.0                             | 1        | 0.38%   |
| OEM TOP77D                           | 1        | 0.38%   |
| MSI MS-7D09                          | 1        | 0.38%   |
| MSI MS-7C95                          | 1        | 0.38%   |
| MSI MS-7C82                          | 1        | 0.38%   |
| MSI MS-7C52                          | 1        | 0.38%   |
| MSI MS-7C37                          | 1        | 0.38%   |
| MSI MS-7C18                          | 1        | 0.38%   |
| MSI MS-7C02                          | 1        | 0.38%   |
| MSI MS-7B93                          | 1        | 0.38%   |
| MSI MS-7B48                          | 1        | 0.38%   |
| MSI MS-7B45                          | 1        | 0.38%   |
| MSI MS-7B23                          | 1        | 0.38%   |
| MSI MS-7A34                          | 1        | 0.38%   |
| MSI MS-7A21                          | 1        | 0.38%   |
| MSI MS-7817                          | 1        | 0.38%   |
| MSI MS-7721                          | 1        | 0.38%   |
| MSI MS-7672                          | 1        | 0.38%   |
| MSI MS-7623                          | 1        | 0.38%   |
| MAXSUN MS-M3A78EL                    | 1        | 0.38%   |
| MAINBRD OPS62A-SHA                   | 1        | 0.38%   |
| LORD ELECTRONICS LORD                | 1        | 0.38%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev | 1        | 0.38%   |
| Lenovo YangTianT4900d-00             | 1        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 52       | 19.7%   |
| 2020    | 33       | 12.5%   |
| 2015    | 23       | 8.71%   |
| 2013    | 22       | 8.33%   |
| 2017    | 21       | 7.95%   |
| 2019    | 20       | 7.58%   |
| 2014    | 16       | 6.06%   |
| 2021    | 15       | 5.68%   |
| 2016    | 15       | 5.68%   |
| 2012    | 13       | 4.92%   |
| 2011    | 9        | 3.41%   |
| Unknown | 7        | 2.65%   |
| 2009    | 6        | 2.27%   |
| 2010    | 5        | 1.89%   |
| 2008    | 3        | 1.14%   |
| 2007    | 3        | 1.14%   |
| 2022    | 1        | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 264      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 257      | 97.35%  |
| Enabled  | 7        | 2.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 262      | 99.24%  |
| Yes  | 2        | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 75       | 28.2%   |
| 8.01-16.0   | 49       | 18.42%  |
| 4.01-8.0    | 45       | 16.92%  |
| 32.01-64.0  | 38       | 14.29%  |
| 3.01-4.0    | 28       | 10.53%  |
| 64.01-256.0 | 14       | 5.26%   |
| 24.01-32.0  | 6        | 2.26%   |
| 1.01-2.0    | 5        | 1.88%   |
| Unknown     | 3        | 1.13%   |
| 0.51-1.0    | 2        | 0.75%   |
| 2.01-3.0    | 1        | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 95       | 34.05%  |
| 2.01-3.0   | 67       | 24.01%  |
| 4.01-8.0   | 40       | 14.34%  |
| 3.01-4.0   | 36       | 12.9%   |
| 8.01-16.0  | 13       | 4.66%   |
| 0.01-0.5   | 11       | 3.94%   |
| 0.51-1.0   | 9        | 3.23%   |
| Unknown    | 3        | 1.08%   |
| 32.01-64.0 | 2        | 0.72%   |
| 16.01-24.0 | 2        | 0.72%   |
| 24.01-32.0 | 1        | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 113      | 42.01%  |
| 2      | 86       | 31.97%  |
| 3      | 34       | 12.64%  |
| 4      | 18       | 6.69%   |
| 5      | 8        | 2.97%   |
| 0      | 4        | 1.49%   |
| 6      | 3        | 1.12%   |
| 11     | 1        | 0.37%   |
| 10     | 1        | 0.37%   |
| 9      | 1        | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 210      | 78.95%  |
| Yes       | 56       | 21.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 260      | 98.48%  |
| No        | 4        | 1.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 144      | 54.14%  |
| Yes       | 122      | 45.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 67.41%  |
| Yes       | 88       | 32.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| China   | 264      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Beijing          | 58       | 21.56%  |
| Shanghai         | 23       | 8.55%   |
| Shenzhen         | 19       | 7.06%   |
| Guangzhou        | 16       | 5.95%   |
| Wuhan            | 11       | 4.09%   |
| Nanjing          | 7        | 2.6%    |
| Xi'an            | 6        | 2.23%   |
| Tianjin          | 6        | 2.23%   |
| Chengdu          | 6        | 2.23%   |
| Hangzhou         | 5        | 1.86%   |
| Xuhui            | 4        | 1.49%   |
| Haidian          | 4        | 1.49%   |
| Foshan           | 4        | 1.49%   |
| Zhengzhou        | 3        | 1.12%   |
| Xiamen           | 3        | 1.12%   |
| Qingdao          | 3        | 1.12%   |
| Putuo            | 3        | 1.12%   |
| Jinan            | 3        | 1.12%   |
| Chongqing        | 3        | 1.12%   |
| Xicheng District | 2        | 0.74%   |
| Wuxi             | 2        | 0.74%   |
| Suzhou           | 2        | 0.74%   |
| Nanning          | 2        | 0.74%   |
| Kunming          | 2        | 0.74%   |
| Huangpu          | 2        | 0.74%   |
| Hongkou          | 2        | 0.74%   |
| Hohhot           | 2        | 0.74%   |
| Hefei            | 2        | 0.74%   |
| Guiyang          | 2        | 0.74%   |
| Geleshan         | 2        | 0.74%   |
| Chenzhou         | 2        | 0.74%   |
| Changsha         | 2        | 0.74%   |
| Zibo             | 1        | 0.37%   |
| Zhongba          | 1        | 0.37%   |
| Zhejiang         | 1        | 0.37%   |
| Zhaoqing         | 1        | 0.37%   |
| Zhanjiang        | 1        | 0.37%   |
| Yulin            | 1        | 0.37%   |
| Yongjiawan       | 1        | 0.37%   |
| Xinchengcun      | 1        | 0.37%   |
| Xianghe          | 1        | 0.37%   |
| Xiangfan         | 1        | 0.37%   |
| Wulipu           | 1        | 0.37%   |
| Wuhu             | 1        | 0.37%   |
| Songjiang        | 1        | 0.37%   |
| Shenyang         | 1        | 0.37%   |
| Shaoxing         | 1        | 0.37%   |
| Shahekou         | 1        | 0.37%   |
| Qinzhou          | 1        | 0.37%   |
| Qinnan           | 1        | 0.37%   |
| Qingxiucun       | 1        | 0.37%   |
| Qikeshu          | 1        | 0.37%   |
| Qidongcun        | 1        | 0.37%   |
| Panjin           | 1        | 0.37%   |
| Ninghai          | 1        | 0.37%   |
| Nanping          | 1        | 0.37%   |
| Nanchang Shi     | 1        | 0.37%   |
| Nanchang         | 1        | 0.37%   |
| Nada             | 1        | 0.37%   |
| Lipu             | 1        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| Seagate                        | 97       | 142    | 20.91%  |
| WDC                            | 90       | 120    | 19.4%   |
| Samsung Electronics            | 52       | 67     | 11.21%  |
| Toshiba                        | 24       | 34     | 5.17%   |
| SanDisk                        | 16       | 19     | 3.45%   |
| Kingston                       | 16       | 18     | 3.45%   |
| Intel                          | 15       | 18     | 3.23%   |
| Unknown                        | 10       | 16     | 2.16%   |
| Silicon Motion                 | 10       | 12     | 2.16%   |
| Plextor                        | 9        | 11     | 1.94%   |
| Hitachi                        | 7        | 12     | 1.51%   |
| HGST                           | 7        | 12     | 1.51%   |
| Phison                         | 6        | 8      | 1.29%   |
| GALAX                          | 5        | 5      | 1.08%   |
| FORESEE                        | 5        | 5      | 1.08%   |
| Lite-On                        | 4        | 6      | 0.86%   |
| Lenovo                         | 4        | 4      | 0.86%   |
| Colorful                       | 4        | 4      | 0.86%   |
| Teclast                        | 3        | 3      | 0.65%   |
| KIOXIA-EXCERIA                 | 3        | 3      | 0.65%   |
| GLOWAY                         | 3        | 3      | 0.65%   |
| Fujitsu                        | 3        | 3      | 0.65%   |
| Faspeed                        | 3        | 3      | 0.65%   |
| Crucial                        | 3        | 3      | 0.65%   |
| ZHITAI                         | 2        | 2      | 0.43%   |
| tigo                           | 2        | 2      | 0.43%   |
| SK hynix                       | 2        | 2      | 0.43%   |
| OCZ                            | 2        | 2      | 0.43%   |
| Netac                          | 2        | 3      | 0.43%   |
| Micron Technology              | 2        | 2      | 0.43%   |
| LITEON                         | 2        | 4      | 0.43%   |
| KingShare                      | 2        | 2      | 0.43%   |
| KINGBANK                       | 2        | 2      | 0.43%   |
| JMicron Technology             | 2        | 2      | 0.43%   |
| Hewlett-Packard                | 2        | 2      | 0.43%   |
| China                          | 2        | 2      | 0.43%   |
| A-DATA Technology              | 2        | 2      | 0.43%   |
| Unknown                        | 2        | 2      | 0.43%   |
| Yangtze Memory Technologies    | 1        | 1      | 0.22%   |
| XPG                            | 1        | 1      | 0.22%   |
| Vaseky                         | 1        | 1      | 0.22%   |
| UMIS                           | 1        | 1      | 0.22%   |
| StoreJet                       | 1        | 1      | 0.22%   |
| Solid State Storage Technology | 1        | 4      | 0.22%   |
| ShineDisk                      | 1        | 1      | 0.22%   |
| Q200                           | 1        | 4      | 0.22%   |
| Phi                            | 1        | 1      | 0.22%   |
| Pear 2TB                       | 1        | 1      | 0.22%   |
| Pear                           | 1        | 1      | 0.22%   |
| NGFF                           | 1        | 1      | 0.22%   |
| MX                             | 1        | 1      | 0.22%   |
| MAXSUN                         | 1        | 1      | 0.22%   |
| Maxmemroy                      | 1        | 1      | 0.22%   |
| MAXIO Technology (Hangzhou)    | 1        | 1      | 0.22%   |
| MAXIO                          | 1        | 1      | 0.22%   |
| Lexar                          | 1        | 1      | 0.22%   |
| LB                             | 1        | 1      | 0.22%   |
| Kingchuxing                    | 1        | 1      | 0.22%   |
| KDATA                          | 1        | 1      | 0.22%   |
| IBM H0                         | 1        | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB               | 15       | 2.92%   |
| Seagate ST1000DM003-1SB102 1TB         | 11       | 2.14%   |
| Seagate ST1000DM010-2EP102 1TB         | 10       | 1.95%   |
| Seagate ST500DM002-1BD142 500GB        | 7        | 1.36%   |
| WDC WD10EZEX-08M2NA0 1TB               | 6        | 1.17%   |
| Seagate ST3500418AS 500GB              | 6        | 1.17%   |
| WDC WDS100T2B0C-00PXH0 1TB             | 4        | 0.78%   |
| WDC WD10EZEX-22MFCA0 1TB               | 4        | 0.78%   |
| Toshiba TR200 480GB SSD                | 4        | 0.78%   |
| Toshiba DT01ACA200 2TB                 | 4        | 0.78%   |
| Seagate ST3000DM008-2DM166 3TB         | 4        | 0.78%   |
| Seagate ST3000DM001-1ER166 3TB         | 4        | 0.78%   |
| Seagate ST2000DM006-2DM164 2TB         | 4        | 0.78%   |
| Seagate ST1000DM003-1ER162 1TB         | 4        | 0.78%   |
| SanDisk NVMe SSD Drive 1TB             | 4        | 0.78%   |
| Toshiba DT01ACA300 3TB                 | 3        | 0.58%   |
| Silicon Motion NVMe SSD Drive 1024GB   | 3        | 0.58%   |
| Seagate ST2000DM001-1ER164 2TB         | 3        | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB         | 3        | 0.58%   |
| SanDisk NVMe SSD Drive 2TB             | 3        | 0.58%   |
| Samsung SSD 860 EVO 500GB              | 3        | 0.58%   |
| Samsung SSD 860 EVO 250GB              | 3        | 0.58%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 3        | 0.58%   |
| Samsung SM963 2.5" NVMe PCIe SSD 128GB | 3        | 0.58%   |
| Samsung NVMe SSD Drive 256GB           | 3        | 0.58%   |
| Samsung NVMe SSD Drive 250GB           | 3        | 0.58%   |
| Lite-On NVMe SSD Drive 1024GB          | 3        | 0.58%   |
| Kingston SA400S37480G 480GB SSD        | 3        | 0.58%   |
| GALAX TA1D0240A 240GB                  | 3        | 0.58%   |
| FORESEE P900F256GBH                    | 3        | 0.58%   |
| WDC WD7500BPKT-00PK4T0 752GB           | 2        | 0.39%   |
| WDC WD5000AAKX-22ERMA0 500GB           | 2        | 0.39%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 2        | 0.39%   |
| WDC WD5000AAKX-08ERMA0 500GB           | 2        | 0.39%   |
| WDC WD5000AAKX-001CA0 500GB            | 2        | 0.39%   |
| WDC WD5000AAKX-0 500GB                 | 2        | 0.39%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2        | 0.39%   |
| WDC WD10EZEX-60WN4A0 1TB               | 2        | 0.39%   |
| WDC WD10EZEX-21WN4A0 1TB               | 2        | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB               | 2        | 0.39%   |
| Unknown SD64G  64GB                    | 2        | 0.39%   |
| Unknown NVMe SSD Drive 256GB           | 2        | 0.39%   |
| Toshiba MQ01ACF050 500GB               | 2        | 0.39%   |
| Toshiba MQ01ABD100 1TB                 | 2        | 0.39%   |
| Toshiba DT01ACA100 LENOVO 1TB          | 2        | 0.39%   |
| tigo SSD 120GB                         | 2        | 0.39%   |
| SK hynix NVMe SSD Drive 128GB          | 2        | 0.39%   |
| Silicon Motion NVMe SSD Drive 512GB    | 2        | 0.39%   |
| Silicon Motion NVMe SSD Drive 1TB      | 2        | 0.39%   |
| Seagate ST500DM002-1SB10A 500GB        | 2        | 0.39%   |
| Seagate ST3500413AS 500GB              | 2        | 0.39%   |
| Seagate ST3250318AS 250GB              | 2        | 0.39%   |
| Seagate ST3250310AS 250GB              | 2        | 0.39%   |
| Seagate ST3160815AS 160GB              | 2        | 0.39%   |
| Seagate ST31000524AS 1TB               | 2        | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB         | 2        | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB         | 2        | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2        | 0.39%   |
| Seagate ST1000DM003-9YN162 1TB         | 2        | 0.39%   |
| SanDisk SDSSDA240G 240GB               | 2        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 96       | 141    | 43.64%  |
| WDC                 | 80       | 103    | 36.36%  |
| Toshiba             | 19       | 25     | 8.64%   |
| Hitachi             | 7        | 12     | 3.18%   |
| HGST                | 7        | 12     | 3.18%   |
| Samsung Electronics | 4        | 4      | 1.82%   |
| Fujitsu             | 3        | 3      | 1.36%   |
| Pear 2TB            | 1        | 1      | 0.45%   |
| JMicron Technology  | 1        | 1      | 0.45%   |
| IBM H0              | 1        | 1      | 0.45%   |
| ACASIS              | 1        | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 28       | 33     | 20.44%  |
| Kingston            | 11       | 13     | 8.03%   |
| Intel               | 9        | 12     | 6.57%   |
| Toshiba             | 8        | 8      | 5.84%   |
| Plextor             | 8        | 9      | 5.84%   |
| SanDisk             | 6        | 6      | 4.38%   |
| WDC                 | 5        | 6      | 3.65%   |
| GALAX               | 5        | 5      | 3.65%   |
| Teclast             | 3        | 3      | 2.19%   |
| Lenovo              | 3        | 3      | 2.19%   |
| Crucial             | 3        | 3      | 2.19%   |
| Unknown             | 2        | 3      | 1.46%   |
| tigo                | 2        | 2      | 1.46%   |
| OCZ                 | 2        | 2      | 1.46%   |
| Netac               | 2        | 3      | 1.46%   |
| Micron Technology   | 2        | 2      | 1.46%   |
| LITEON              | 2        | 4      | 1.46%   |
| KingShare           | 2        | 2      | 1.46%   |
| KINGBANK            | 2        | 2      | 1.46%   |
| GLOWAY              | 2        | 2      | 1.46%   |
| FORESEE             | 2        | 2      | 1.46%   |
| Faspeed             | 2        | 2      | 1.46%   |
| Colorful            | 2        | 2      | 1.46%   |
| China               | 2        | 2      | 1.46%   |
| A-DATA Technology   | 2        | 2      | 1.46%   |
| ZHITAI              | 1        | 1      | 0.73%   |
| Vaseky              | 1        | 1      | 0.73%   |
| StoreJet            | 1        | 1      | 0.73%   |
| ShineDisk           | 1        | 1      | 0.73%   |
| Q200                | 1        | 4      | 0.73%   |
| Pear                | 1        | 1      | 0.73%   |
| NGFF                | 1        | 1      | 0.73%   |
| MX                  | 1        | 1      | 0.73%   |
| Maxmemroy           | 1        | 1      | 0.73%   |
| MAXIO               | 1        | 1      | 0.73%   |
| Lexar               | 1        | 1      | 0.73%   |
| LB                  | 1        | 1      | 0.73%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.73%   |
| Kingchuxing         | 1        | 1      | 0.73%   |
| KDATA               | 1        | 1      | 0.73%   |
| Hoodisk             | 1        | 1      | 0.73%   |
| Gigabyte Technology | 1        | 3      | 0.73%   |
| Flash               | 1        | 2      | 0.73%   |
| ELSKY               | 1        | 1      | 0.73%   |
| Unknown             | 1        | 1      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 179      | 304    | 44.86%  |
| SSD     | 113      | 159    | 28.32%  |
| NVMe    | 88       | 122    | 22.06%  |
| Unknown | 16       | 19     | 4.01%   |
| MMC     | 3        | 4      | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 229      | 461    | 67.75%  |
| NVMe | 88       | 122    | 26.04%  |
| SAS  | 18       | 21     | 5.33%   |
| MMC  | 3        | 4      | 0.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 144      | 232    | 46.15%  |
| 0.51-1.0   | 113      | 136    | 36.22%  |
| 1.01-2.0   | 28       | 35     | 8.97%   |
| 2.01-3.0   | 12       | 21     | 3.85%   |
| 3.01-4.0   | 8        | 15     | 2.56%   |
| 4.01-10.0  | 5        | 21     | 1.6%    |
| 10.01-20.0 | 2        | 3      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 68       | 25.19%  |
| 251-500        | 49       | 18.15%  |
| 501-1000       | 46       | 17.04%  |
| 1001-2000      | 28       | 10.37%  |
| 51-100         | 23       | 8.52%   |
| More than 3000 | 19       | 7.04%   |
| 21-50          | 11       | 4.07%   |
| 2001-3000      | 11       | 4.07%   |
| 1-20           | 10       | 3.7%    |
| Unknown        | 5        | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 110      | 39.71%  |
| 101-250        | 43       | 15.52%  |
| 21-50          | 39       | 14.08%  |
| 51-100         | 26       | 9.39%   |
| 251-500        | 21       | 7.58%   |
| 1001-2000      | 11       | 3.97%   |
| 501-1000       | 11       | 3.97%   |
| More than 3000 | 6        | 2.17%   |
| 2001-3000      | 5        | 1.81%   |
| Unknown        | 5        | 1.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1      | 4.55%   |
| WDC WD5003ABYZ-011FA0 500GB           | 1        | 1      | 4.55%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 1        | 1      | 4.55%   |
| WDC WD5000AAKX-0 500GB                | 1        | 1      | 4.55%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 4.55%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1        | 1      | 4.55%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 4.55%   |
| Toshiba DT01ACA300 3TB                | 1        | 1      | 4.55%   |
| Seagate ST980811AS 80GB               | 1        | 1      | 4.55%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1        | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB       | 1        | 1      | 4.55%   |
| Seagate ST500DM009-2DM14C 500GB       | 1        | 1      | 4.55%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 4.55%   |
| Seagate ST5000AS0011-1L5178 5TB       | 1        | 1      | 4.55%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 4.55%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 4.55%   |
| Plextor PX-256M6S+ 256GB SSD          | 1        | 1      | 4.55%   |
| Intel SSDSC2KW240H6 240GB             | 1        | 1      | 4.55%   |
| Intel SSDSC2BW360H6 360GB             | 1        | 1      | 4.55%   |
| Fujitsu MJA2250BH G2 250GB            | 1        | 1      | 4.55%   |
| Crucial CT240M500SSD1 240GB           | 1        | 1      | 4.55%   |
| Colorful SL500 320GB SSD              | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 33.33%  |
| Seagate             | 6        | 7      | 28.57%  |
| Intel               | 2        | 2      | 9.52%   |
| Toshiba             | 1        | 1      | 4.76%   |
| Samsung Electronics | 1        | 1      | 4.76%   |
| Plextor             | 1        | 1      | 4.76%   |
| Fujitsu             | 1        | 1      | 4.76%   |
| Crucial             | 1        | 1      | 4.76%   |
| Colorful            | 1        | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 6      | 42.86%  |
| Seagate | 6        | 7      | 42.86%  |
| Toshiba | 1        | 1      | 7.14%   |
| Fujitsu | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 15     | 72.22%  |
| SSD  | 4        | 6      | 22.22%  |
| NVMe | 1        | 1      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST31500341AS 1TB          | 1        | 1      | 50%     |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 169      | 404    | 59.72%  |
| Works    | 96       | 180    | 33.92%  |
| Malfunc  | 16       | 22     | 5.65%   |
| Failed   | 2        | 2      | 0.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 187      | 50%     |
| AMD                              | 65       | 17.38%  |
| Samsung Electronics              | 23       | 6.15%   |
| SanDisk                          | 19       | 5.08%   |
| Silicon Motion                   | 14       | 3.74%   |
| Marvell Technology Group         | 7        | 1.87%   |
| Phison Electronics               | 6        | 1.6%    |
| ASMedia Technology               | 6        | 1.6%    |
| Kingston Technology Company      | 5        | 1.34%   |
| Lite-On Technology               | 4        | 1.07%   |
| JMicron Technology               | 4        | 1.07%   |
| Shenzhen Longsys Electronics     | 3        | 0.8%    |
| Huawei Technologies              | 3        | 0.8%    |
| Yangtze Memory Technologies      | 2        | 0.53%   |
| Solid State Storage Technology   | 2        | 0.53%   |
| SK hynix                         | 2        | 0.53%   |
| Mylex                            | 2        | 0.53%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.53%   |
| KIOXIA                           | 2        | 0.53%   |
| Broadcom / LSI                   | 2        | 0.53%   |
| Beijing Starblaze Technology     | 2        | 0.53%   |
| Zhaoxin                          | 1        | 0.27%   |
| Union Memory (Shenzhen)          | 1        | 0.27%   |
| Toshiba America Info Systems     | 1        | 0.27%   |
| Silicon Integrated Systems [SiS] | 1        | 0.27%   |
| Silicon Image                    | 1        | 0.27%   |
| Seagate Technology               | 1        | 0.27%   |
| Realtek Semiconductor            | 1        | 0.27%   |
| Nvidia                           | 1        | 0.27%   |
| Loongson Technology              | 1        | 0.27%   |
| IBM                              | 1        | 0.27%   |
| HighPoint Technologies           | 1        | 0.27%   |
| Hefei DATANG Storage Technology  | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 37       | 8.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 29       | 6.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24       | 5.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 21       | 4.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 3.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 15       | 3.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 3.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 2.44%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11       | 2.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10       | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 1.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 7        | 1.56%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 1.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 6        | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6        | 1.33%   |
| SanDisk Non-Volatile memory controller                                                  | 6        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 1.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 1.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 1.11%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.11%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4        | 0.89%   |
| Phison PS5013 E13 NVMe Controller                                                       | 4        | 0.89%   |
| Lite-On Non-Volatile memory controller                                                  | 4        | 0.89%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4        | 0.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.89%   |
| Shenzhen Longsys Non-Volatile memory controller                                         | 3        | 0.67%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 3        | 0.67%   |
| Intel SSD 600P Series                                                                   | 3        | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.67%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.67%   |
| Huawei HiSilicon SAS 3.0 HBA                                                            | 3        | 0.67%   |
| Huawei HiSilicon RDE Engine                                                             | 3        | 0.67%   |
| Huawei HiSilicon AHCI HBA                                                               | 3        | 0.67%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.67%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.67%   |
| Yangtze Memory Non-Volatile memory controller                                           | 2        | 0.44%   |
| Solid State Storage Non-Volatile memory controller                                      | 2        | 0.44%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2        | 0.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.44%   |
| Mylex AcceleRAID 600/500/400/Sapphire support Device                                    | 2        | 0.44%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 2        | 0.44%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2        | 0.44%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.44%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2        | 0.44%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 0.44%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.44%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.44%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 2        | 0.44%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 2        | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 226      | 59.79%  |
| NVMe | 89       | 23.54%  |
| IDE  | 42       | 11.11%  |
| RAID | 15       | 3.97%   |
| SAS  | 4        | 1.06%   |
| SCSI | 2        | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 186      | 70.45%  |
| AMD               | 67       | 25.38%  |
| Unknown           | 4        | 1.52%   |
| sifive,bullet0    | 2        | 0.76%   |
| CHRP IBM,9131-52A | 2        | 0.76%   |
| sifive,u74-mc     | 1        | 0.38%   |
| CHRP IBM,8233-E8B | 1        | 0.38%   |
| CentaurHauls      | 1        | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 10       | 3.77%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 8        | 3.02%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 7        | 2.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 7        | 2.64%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 6        | 2.26%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 5        | 1.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 4        | 1.51%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 1.51%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 4        | 1.51%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.51%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 4        | 1.51%   |
|                                             | 4        | 1.51%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 3        | 1.13%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 3        | 1.13%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 3        | 1.13%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 1.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 1.13%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.13%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 1.13%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.13%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 1.13%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.13%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.13%   |
| AMD Athlon II X2 240 Processor              | 3        | 1.13%   |
| sifive,bullet0 rv64imafdc                   | 2        | 0.75%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz         | 2        | 0.75%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 0.75%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2        | 0.75%   |
| Intel Core i7-10700KF CPU @ 3.80GHz         | 2        | 0.75%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.75%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.75%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.75%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 0.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.75%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.75%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 0.75%   |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz    | 2        | 0.75%   |
| CHRP IBM,9131-52A POWER5+ (gs)              | 2        | 0.75%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 0.75%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 0.75%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 0.75%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 0.75%   |
| AMD Athlon 200GE with Radeon Vega Graphics  | 2        | 0.75%   |
| sifive,u74-mc rv64imafdc                    | 1        | 0.38%   |
| Intel Xeon W-2245 CPU @ 3.90GHz             | 1        | 0.38%   |
| Intel Xeon E-2124G CPU @ 3.40GHz            | 1        | 0.38%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.38%   |
| Intel Xeon CPU E5645 @ 2.40GHz              | 1        | 0.38%   |
| Intel Xeon CPU E5-2695 v2 @ 2.40GHz         | 1        | 0.38%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.38%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.38%   |
| Intel Xeon CPU E5-2640 v2 @ 2.00GHz         | 1        | 0.38%   |
| Intel Xeon CPU E3-1283L v4 @ 2.90GHz        | 1        | 0.38%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.38%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 0.38%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.38%   |
| Intel Xeon CPU 2.80GHz                      | 1        | 0.38%   |
| Intel Xeon Bronze 3104 CPU @ 1.70GHz        | 1        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 59       | 22.35%  |
| Intel Core i5           | 48       | 18.18%  |
| Other                   | 21       | 7.95%   |
| AMD Ryzen 5             | 19       | 7.2%    |
| Intel Xeon              | 18       | 6.82%   |
| Intel Core i3           | 17       | 6.44%   |
| Intel Celeron           | 11       | 4.17%   |
| AMD Ryzen 7             | 11       | 4.17%   |
| Intel Pentium           | 8        | 3.03%   |
| AMD FX                  | 6        | 2.27%   |
| AMD Athlon II X2        | 6        | 2.27%   |
| Intel Core i9           | 5        | 1.89%   |
| Intel Core 2 Duo        | 4        | 1.52%   |
| AMD Ryzen 7 PRO         | 4        | 1.52%   |
| Intel Pentium Dual-Core | 3        | 1.14%   |
| AMD Ryzen 9             | 3        | 1.14%   |
| Intel Core 2 Quad       | 2        | 0.76%   |
| AMD Ryzen 5 PRO         | 2        | 0.76%   |
| AMD Athlon X4           | 2        | 0.76%   |
| AMD Athlon              | 2        | 0.76%   |
| AMD A8                  | 2        | 0.76%   |
| Intel Xeon Bronze       | 1        | 0.38%   |
| Intel Pentium Dual      | 1        | 0.38%   |
| Intel Genuine           | 1        | 0.38%   |
| Intel Core 2            | 1        | 0.38%   |
| Intel Atom              | 1        | 0.38%   |
| AMD Ryzen Threadripper  | 1        | 0.38%   |
| AMD Ryzen 3             | 1        | 0.38%   |
| AMD Phenom II X4        | 1        | 0.38%   |
| AMD Athlon 64 X2        | 1        | 0.38%   |
| AMD A6                  | 1        | 0.38%   |
| AMD A10                 | 1        | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 98       | 36.98%  |
| 2       | 60       | 22.64%  |
| 6       | 49       | 18.49%  |
| 8       | 32       | 12.08%  |
| 12      | 7        | 2.64%   |
| 10      | 6        | 2.26%   |
| 1       | 4        | 1.51%   |
| 24      | 3        | 1.13%   |
| Unknown | 3        | 1.13%   |
| 16      | 2        | 0.75%   |
| 3       | 1        | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 257      | 97.35%  |
| 2       | 3        | 1.14%   |
| Unknown | 3        | 1.14%   |
| 6       | 1        | 0.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 161      | 60.98%  |
| 1       | 99       | 37.5%   |
| Unknown | 3        | 1.14%   |
| 4       | 1        | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 252      | 95.45%  |
| Unknown        | 11       | 4.17%   |
| 64-bit         | 1        | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 68       | 25.28%  |
| 0x306c3    | 29       | 10.78%  |
| 0x906ea    | 16       | 5.95%   |
| 0x906e9    | 14       | 5.2%    |
| 0x206a7    | 12       | 4.46%   |
| 0x306a9    | 11       | 4.09%   |
| 0xa0655    | 9        | 3.35%   |
| 0x506e3    | 9        | 3.35%   |
| 0x1067a    | 7        | 2.6%    |
| 0x30678    | 4        | 1.49%   |
| 0x08701021 | 4        | 1.49%   |
| 0x08701013 | 4        | 1.49%   |
| 0x0810100b | 4        | 1.49%   |
| 0x010000c8 | 4        | 1.49%   |
| 0xa0671    | 3        | 1.12%   |
| 0xa0653    | 3        | 1.12%   |
| 0x08600106 | 3        | 1.12%   |
| 0x08001138 | 3        | 1.12%   |
| 0x06001119 | 3        | 1.12%   |
| 0x906ed    | 2        | 0.74%   |
| 0x906eb    | 2        | 0.74%   |
| 0x90672    | 2        | 0.74%   |
| 0x40651    | 2        | 0.74%   |
| 0x306e4    | 2        | 0.74%   |
| 0x206c2    | 2        | 0.74%   |
| 0x0a50000c | 2        | 0.74%   |
| 0x0a201009 | 2        | 0.74%   |
| 0x0800820d | 2        | 0.74%   |
| 0x0800820b | 2        | 0.74%   |
| 0x0600063e | 2        | 0.74%   |
| 0x010000c7 | 2        | 0.74%   |
| 0xf43      | 1        | 0.37%   |
| 0x806ea    | 1        | 0.37%   |
| 0x806e9    | 1        | 0.37%   |
| 0x806c1    | 1        | 0.37%   |
| 0x6fd      | 1        | 0.37%   |
| 0x6f6      | 1        | 0.37%   |
| 0x50657    | 1        | 0.37%   |
| 0x50654    | 1        | 0.37%   |
| 0x406f1    | 1        | 0.37%   |
| 0x40671    | 1        | 0.37%   |
| 0x306f2    | 1        | 0.37%   |
| 0x306f1    | 1        | 0.37%   |
| 0x30673    | 1        | 0.37%   |
| 0x30661    | 1        | 0.37%   |
| 0x206d7    | 1        | 0.37%   |
| 0x106a5    | 1        | 0.37%   |
| 0x10676    | 1        | 0.37%   |
| 0x0a201204 | 1        | 0.37%   |
| 0x08701012 | 1        | 0.37%   |
| 0x08701011 | 1        | 0.37%   |
| 0x08600103 | 1        | 0.37%   |
| 0x08301039 | 1        | 0.37%   |
| 0x08108109 | 1        | 0.37%   |
| 0x08101016 | 1        | 0.37%   |
| 0x08001137 | 1        | 0.37%   |
| 0x0800110e | 1        | 0.37%   |
| 0x07043001 | 1        | 0.37%   |
| 0x07026101 | 1        | 0.37%   |
| 0x0600611a | 1        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 48       | 18.18%  |
| Haswell          | 43       | 16.29%  |
| Zen 2            | 19       | 7.2%    |
| CometLake        | 19       | 7.2%    |
| IvyBridge        | 16       | 6.06%   |
| Skylake          | 15       | 5.68%   |
| Unknown          | 15       | 5.68%   |
| SandyBridge      | 13       | 4.92%   |
| Zen              | 11       | 4.17%   |
| Penryn           | 10       | 3.79%   |
| K10              | 8        | 3.03%   |
| Zen 3            | 7        | 2.65%   |
| Piledriver       | 7        | 2.65%   |
| Zen+             | 6        | 2.27%   |
| Silvermont       | 6        | 2.27%   |
| Core             | 3        | 1.14%   |
| Westmere         | 2        | 0.76%   |
| Steamroller      | 2        | 0.76%   |
| Bulldozer        | 2        | 0.76%   |
| Broadwell        | 2        | 0.76%   |
| Alderlake Hybrid | 2        | 0.76%   |
| TigerLake        | 1        | 0.38%   |
| Puma             | 1        | 0.38%   |
| NetBurst         | 1        | 0.38%   |
| Nehalem          | 1        | 0.38%   |
| K8 Hammer        | 1        | 0.38%   |
| Icelake          | 1        | 0.38%   |
| Excavator        | 1        | 0.38%   |
| Bonnell          | 1        | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 118      | 40.97%  |
| Nvidia                           | 82       | 28.47%  |
| AMD                              | 81       | 28.13%  |
| Matrox Electronics Systems       | 2        | 0.69%   |
| ASPEED Technology                | 2        | 0.69%   |
| Zhaoxin                          | 1        | 0.35%   |
| Silicon Integrated Systems [SiS] | 1        | 0.35%   |
| Loongson Technology              | 1        | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 6.48%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 5.8%    |
| Intel HD Graphics 630                                                       | 11       | 3.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 11       | 3.75%   |
| Intel HD Graphics 530                                                       | 10       | 3.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 3.41%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 9        | 3.07%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 2.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 2.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 2.05%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 5        | 1.71%   |
| AMD Renoir                                                                  | 5        | 1.71%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.37%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.37%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 1.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4        | 1.37%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.37%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 1.02%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 3        | 1.02%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.02%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.02%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 3        | 1.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.02%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.02%   |
| AMD Cezanne                                                                 | 3        | 1.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.02%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.68%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.68%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 2        | 0.68%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.68%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.68%   |
| Intel AlderLake-S GT1                                                       | 2        | 0.68%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 0.68%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 0.68%   |
| AMD RS690 [Radeon X1200]                                                    | 2        | 0.68%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 0.68%   |
| AMD Navi 21 GL-XL [Radeon PRO W6800]                                        | 2        | 0.68%   |
| AMD Hawaii XT / Grenada XT [Radeon R9 290X/390X]                            | 2        | 0.68%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 2        | 0.68%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 0.68%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 0.68%   |
| Zhaoxin ZX-E C-960 GPU                                                      | 1        | 0.34%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 0.34%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.34%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.34%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.34%   |
| Nvidia NV44 [GeForce 7100 GS]                                               | 1        | 0.34%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.34%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 0.34%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.34%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.34%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.34%   |
| Nvidia GP104GL [Quadro P4000]                                               | 1        | 0.34%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 96       | 36.09%  |
| 1 x AMD                 | 73       | 27.44%  |
| 1 x Nvidia              | 72       | 27.07%  |
| Intel + Nvidia          | 4        | 1.5%    |
| Intel + AMD             | 4        | 1.5%    |
| Other                   | 2        | 0.75%   |
| 2 x Nvidia              | 2        | 0.75%   |
| 1 x Matrox              | 2        | 0.75%   |
| AMD + Nvidia            | 2        | 0.75%   |
| 2 x Intel               | 1        | 0.38%   |
| 2 x AMD                 | 1        | 0.38%   |
| 1 x Zhaoxin             | 1        | 0.38%   |
| 1 x SiS                 | 1        | 0.38%   |
| Nvidia + ASPEED         | 1        | 0.38%   |
| 1 x Loongson Technology | 1        | 0.38%   |
| 1 x Intel + 3 x Nvidia  | 1        | 0.38%   |
| Intel + 2 x Nvidia      | 1        | 0.38%   |
| AMD + ASPEED            | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 195      | 73.31%  |
| Proprietary | 44       | 16.54%  |
| Unknown     | 27       | 10.15%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 137      | 51.31%  |
| 1.01-2.0   | 33       | 12.36%  |
| 0.01-0.5   | 21       | 7.87%   |
| 0.51-1.0   | 20       | 7.49%   |
| 3.01-4.0   | 18       | 6.74%   |
| 7.01-8.0   | 15       | 5.62%   |
| 5.01-6.0   | 8        | 3%      |
| 2.01-3.0   | 5        | 1.87%   |
| 8.01-16.0  | 5        | 1.87%   |
| 24.01-32.0 | 2        | 0.75%   |
| 16.01-24.0 | 2        | 0.75%   |
| 4.01-5.0   | 1        | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 42       | 16.67%  |
| AOC                  | 36       | 14.29%  |
| Lenovo               | 27       | 10.71%  |
| Samsung Electronics  | 17       | 6.75%   |
| Philips              | 15       | 5.95%   |
| Goldstar             | 11       | 4.37%   |
| ViewSonic            | 10       | 3.97%   |
| Hewlett-Packard      | 10       | 3.97%   |
| BenQ                 | 8        | 3.17%   |
| Acer                 | 8        | 3.17%   |
| HKC                  | 5        | 1.98%   |
| Unknown              | 3        | 1.19%   |
| Ancor Communications | 3        | 1.19%   |
| Xiaomi               | 2        | 0.79%   |
| TFC                  | 2        | 0.79%   |
| RTK                  | 2        | 0.79%   |
| LG Electronics       | 2        | 0.79%   |
| KOIOS                | 2        | 0.79%   |
| IPS                  | 2        | 0.79%   |
| HannStar             | 2        | 0.79%   |
| Envision Peripherals | 2        | 0.79%   |
| Eizo                 | 2        | 0.79%   |
| CHR                  | 2        | 0.79%   |
| CHD                  | 2        | 0.79%   |
| BOE                  | 2        | 0.79%   |
| AGO                  | 2        | 0.79%   |
| ZTY                  | 1        | 0.4%    |
| Unknown (AAA)        | 1        | 0.4%    |
| TUP                  | 1        | 0.4%    |
| TCL                  | 1        | 0.4%    |
| SUG                  | 1        | 0.4%    |
| Sony                 | 1        | 0.4%    |
| SLE                  | 1        | 0.4%    |
| SKY                  | 1        | 0.4%    |
| SGT                  | 1        | 0.4%    |
| SAC                  | 1        | 0.4%    |
| PDI                  | 1        | 0.4%    |
| NEC Computers        | 1        | 0.4%    |
| MOT                  | 1        | 0.4%    |
| Mi                   | 1        | 0.4%    |
| LRX                  | 1        | 0.4%    |
| LG Display           | 1        | 0.4%    |
| Lenovo Group Limited | 1        | 0.4%    |
| JRY                  | 1        | 0.4%    |
| HYN                  | 1        | 0.4%    |
| HWV                  | 1        | 0.4%    |
| Hugon                | 1        | 0.4%    |
| HUAWEI               | 1        | 0.4%    |
| HJW                  | 1        | 0.4%    |
| HIC                  | 1        | 0.4%    |
| DSC                  | 1        | 0.4%    |
| Daewoo               | 1        | 0.4%    |
| CVT                  | 1        | 0.4%    |
| AUS                  | 1        | 0.4%    |
| AMO                  | 1        | 0.4%    |
| Advantech            | 1        | 0.4%    |
| Unknown              | 1        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 4        | 1.5%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 3        | 1.13%   |
| Xiaomi Mi TV XMD004A 1920x1080 1110x620mm 50.1-inch                   | 2        | 0.75%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2        | 0.75%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch     | 2        | 0.75%   |
| Samsung Electronics LCD Monitor S19B360                               | 2        | 0.75%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.75%   |
| Lenovo X24q-10 LEN61A4 2560x1440 527x296mm 23.8-inch                  | 2        | 0.75%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch            | 2        | 0.75%   |
| Lenovo LEN LI2364 LEN65C7 1920x1080 509x286mm 23.0-inch               | 2        | 0.75%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                 | 2        | 0.75%   |
| HKC CH70 HKC27A9 1920x1080 597x336mm 27.0-inch                        | 2        | 0.75%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 0.75%   |
| Dell U2518D DEL413C 2560x1440 553x311mm 25.0-inch                     | 2        | 0.75%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                     | 2        | 0.75%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2        | 0.75%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 2        | 0.75%   |
| Dell E2316H DELF06A 1920x1080 509x286mm 23.0-inch                     | 2        | 0.75%   |
| Dell E2216HV DELF06F 1920x1080 476x268mm 21.5-inch                    | 2        | 0.75%   |
| CHD CHUD CHD0030 3840x2160 1394x784mm 63.0-inch                       | 2        | 0.75%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 2        | 0.75%   |
| AOC Q27P1B AOC2701 2560x1440 597x336mm 27.0-inch                      | 2        | 0.75%   |
| AOC 2490W1 AOC2490 1920x1080 530x300mm 24.0-inch                      | 2        | 0.75%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                      | 2        | 0.75%   |
| Ancor Communications LCD Monitor VG248 3360x1080                      | 2        | 0.75%   |
| ZTY LM1710 (VGA) ZTY1910 1280x1024 337x270mm 17.0-inch                | 1        | 0.38%   |
| Xiaomi Mi TV XMD0002 1920x1080 1440x810mm 65.0-inch                   | 1        | 0.38%   |
| ViewSonic VX3276 Series VSC6335 2560x1440 698x393mm 31.5-inch         | 1        | 0.38%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch             | 1        | 0.38%   |
| ViewSonic VA2730 Series VSCA539 1920x1080 598x336mm 27.0-inch         | 1        | 0.38%   |
| ViewSonic VA2616w-2 VSC3221 1920x1200 550x344mm 25.5-inch             | 1        | 0.38%   |
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch            | 1        | 0.38%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch            | 1        | 0.38%   |
| ViewSonic VA2261-3 VSC3483 1920x1080 480x270mm 21.7-inch              | 1        | 0.38%   |
| ViewSonic VA2206-LED VSCA02A 1920x1080 477x268mm 21.5-inch            | 1        | 0.38%   |
| ViewSonic LCD Monitor VX2376 Series 1920x1080                         | 1        | 0.38%   |
| ViewSonic C1907a VSC6530 1440x900 408x255mm 18.9-inch                 | 1        | 0.38%   |
| Unknown LCD Monitor Sanyo Electric Co.,Ltd. CE5129H1 3840x2160        | 1        | 0.38%   |
| Unknown (AAA) LCD Monitor AAA2BDC 3840x2160 620x340mm 27.8-inch       | 1        | 0.38%   |
| TUP D270H TUP2700 3840x2160 598x336mm 27.0-inch                       | 1        | 0.38%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                      | 1        | 0.38%   |
| TFC 21.5 monitor TFC0215 1920x1080 480x270mm 21.7-inch                | 1        | 0.38%   |
| TCL MST6M182 TCL3788 1360x768 808x454mm 36.5-inch                     | 1        | 0.38%   |
| SUG 21.5"monitor SUG00D7 1920x1080 476x268mm 21.5-inch                | 1        | 0.38%   |
| Sony TV SNY7702 1920x1080 886x498mm 40.0-inch                         | 1        | 0.38%   |
| SLE SLEN SLE2360 1920x1080 436x245mm 19.7-inch                        | 1        | 0.38%   |
| SKY 32E880 SKY0010 1366x768 700x390mm 31.5-inch                       | 1        | 0.38%   |
| SGT Monitor SGT2700 2560x1440 601x329mm 27.0-inch                     | 1        | 0.38%   |
| Samsung Electronics SyncMaster SAM0588 1920x1080 521x293mm 23.5-inch  | 1        | 0.38%   |
| Samsung Electronics SyncMaster SAM010C 1280x1024 338x270mm 17.0-inch  | 1        | 0.38%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 480x270mm 21.7-inch    | 1        | 0.38%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1        | 0.38%   |
| Samsung Electronics S27B350 SAM099F 1920x1080 598x336mm 27.0-inch     | 1        | 0.38%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch     | 1        | 0.38%   |
| Samsung Electronics S22B310 SAM0914 1920x1080 477x268mm 21.5-inch     | 1        | 0.38%   |
| Samsung Electronics S19C350 SAM0A2D 1440x900 408x255mm 18.9-inch      | 1        | 0.38%   |
| Samsung Electronics LS32R75 SAM0F92 3840x2160 697x392mm 31.5-inch     | 1        | 0.38%   |
| Samsung Electronics LS27A70 SAM71A0 3840x2160 597x336mm 27.0-inch     | 1        | 0.38%   |
| Samsung Electronics LCD Monitor SyncMaster 1440x900                   | 1        | 0.38%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1        | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 125      | 50%     |
| 2560x1440 (QHD)    | 30       | 12%     |
| 3840x2160 (4K)     | 28       | 11.2%   |
| 1440x900 (WXGA+)   | 13       | 5.2%    |
| 1280x1024 (SXGA)   | 10       | 4%      |
| 1600x900 (HD+)     | 8        | 3.2%    |
| Unknown            | 6        | 2.4%    |
| 1920x1200 (WUXGA)  | 5        | 2%      |
| 1680x1050 (WSXGA+) | 5        | 2%      |
| 3440x1440          | 4        | 1.6%    |
| 1366x768 (WXGA)    | 4        | 1.6%    |
| 3360x1080          | 2        | 0.8%    |
| 3286x1080          | 2        | 0.8%    |
| 2288x1287          | 2        | 0.8%    |
| 5206x1080          | 1        | 0.4%    |
| 3520x1080          | 1        | 0.4%    |
| 2560x1080          | 1        | 0.4%    |
| 2200x1650          | 1        | 0.4%    |
| 1400x1050          | 1        | 0.4%    |
| 1360x768           | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 46       | 18.33%  |
| 27      | 35       | 13.94%  |
| 21      | 34       | 13.55%  |
| 24      | 31       | 12.35%  |
| Unknown | 24       | 9.56%   |
| 31      | 12       | 4.78%   |
| 19      | 10       | 3.98%   |
| 18      | 8        | 3.19%   |
| 17      | 8        | 3.19%   |
| 20      | 7        | 2.79%   |
| 25      | 6        | 2.39%   |
| 22      | 5        | 1.99%   |
| 34      | 3        | 1.2%    |
| 12      | 3        | 1.2%    |
| 142     | 2        | 0.8%    |
| 65      | 2        | 0.8%    |
| 63      | 2        | 0.8%    |
| 15      | 2        | 0.8%    |
| 11      | 2        | 0.8%    |
| 46      | 1        | 0.4%    |
| 43      | 1        | 0.4%    |
| 42      | 1        | 0.4%    |
| 40      | 1        | 0.4%    |
| 37      | 1        | 0.4%    |
| 36      | 1        | 0.4%    |
| 26      | 1        | 0.4%    |
| 14      | 1        | 0.4%    |
| 13      | 1        | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 110      | 44.9%   |
| 401-500        | 61       | 24.9%   |
| Unknown        | 24       | 9.8%    |
| 601-700        | 16       | 6.53%   |
| 301-350        | 11       | 4.49%   |
| 201-300        | 6        | 2.45%   |
| 1001-1500      | 5        | 2.04%   |
| 801-900        | 3        | 1.22%   |
| 701-800        | 3        | 1.22%   |
| More than 2000 | 2        | 0.82%   |
| 351-400        | 2        | 0.82%   |
| 901-1000       | 2        | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 165      | 69.92%  |
| 16/10   | 31       | 13.14%  |
| Unknown | 23       | 9.75%   |
| 5/4     | 10       | 4.24%   |
| 21/9    | 3        | 1.27%   |
| 4/3     | 2        | 0.85%   |
| 1.00    | 2        | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 85       | 34.14%  |
| 151-200        | 43       | 17.27%  |
| 301-350        | 36       | 14.46%  |
| Unknown        | 24       | 9.64%   |
| 351-500        | 15       | 6.02%   |
| 251-300        | 15       | 6.02%   |
| 141-150        | 10       | 4.02%   |
| More than 1000 | 6        | 2.41%   |
| 501-1000       | 6        | 2.41%   |
| 71-80          | 3        | 1.2%    |
| 51-60          | 2        | 0.8%    |
| 101-110        | 2        | 0.8%    |
| 81-90          | 1        | 0.4%    |
| 61-70          | 1        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 141      | 56.4%   |
| 101-120 | 48       | 19.2%   |
| Unknown | 24       | 9.6%    |
| 161-240 | 15       | 6%      |
| 121-160 | 15       | 6%      |
| 1-50    | 7        | 2.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 206      | 77.15%  |
| 0     | 30       | 11.24%  |
| 2     | 28       | 10.49%  |
| 3     | 3        | 1.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 174      | 48.07%  |
| Intel                    | 111      | 30.66%  |
| Qualcomm Atheros         | 18       | 4.97%   |
| Ralink Technology        | 14       | 3.87%   |
| Broadcom                 | 7        | 1.93%   |
| MediaTek                 | 5        | 1.38%   |
| Huawei Technologies      | 4        | 1.1%    |
| Tenda                    | 3        | 0.83%   |
| Microsoft                | 3        | 0.83%   |
| Marvell Technology Group | 3        | 0.83%   |
| Xiaomi                   | 2        | 0.55%   |
| Samsung Electronics      | 2        | 0.55%   |
| NetGear                  | 2        | 0.55%   |
| D-Link                   | 2        | 0.55%   |
| Broadcom Limited         | 2        | 0.55%   |
| Aquantia                 | 2        | 0.55%   |
| TP-Link                  | 1        | 0.28%   |
| Oculus VR                | 1        | 0.28%   |
| Nvidia                   | 1        | 0.28%   |
| Loongson Technology      | 1        | 0.28%   |
| IBM                      | 1        | 0.28%   |
| Exar                     | 1        | 0.28%   |
| DisplayLink              | 1        | 0.28%   |
| D-Link System            | 1        | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133      | 31.44%  |
| Intel I211 Gigabit Network Connection                             | 14       | 3.31%   |
| Intel Ethernet Connection (2) I219-V                              | 14       | 3.31%   |
| Realtek 802.11ac NIC                                              | 13       | 3.07%   |
| Intel Wi-Fi 6 AX200                                               | 13       | 3.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 2.36%   |
| Ralink MT7601U Wireless Adapter                                   | 9        | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 1.65%   |
| Intel Ethernet Connection (12) I219-V                             | 7        | 1.65%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.42%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6        | 1.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 1.42%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 5        | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5        | 1.18%   |
| Intel Wireless 7260                                               | 5        | 1.18%   |
| Intel Ethernet Controller I225-V                                  | 5        | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 1.18%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.18%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 4        | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.95%   |
| Intel Wireless-AC 9260                                            | 4        | 0.95%   |
| Tenda U12                                                         | 3        | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.71%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 3        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.71%   |
| Huawei HNS GE/10GE/25GE RDMA Network Controller                   | 3        | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 0.47%   |
| MediaTek 802.11 n WLAN                                            | 2        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.47%   |
| Intel Wireless 8260                                               | 2        | 0.47%   |
| Intel Wireless 7265                                               | 2        | 0.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2        | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.47%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.47%   |
| Intel 82546GB Gigabit Ethernet Controller                         | 2        | 0.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2        | 0.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.24%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                 | 1        | 0.24%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                             | 1        | 0.24%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.24%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.24%   |
| Samsung Android USB Device                                        | 1        | 0.24%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.24%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 47       | 35.88%  |
| Realtek Semiconductor | 38       | 29.01%  |
| Ralink Technology     | 14       | 10.69%  |
| Qualcomm Atheros      | 9        | 6.87%   |
| MediaTek              | 5        | 3.82%   |
| Broadcom              | 4        | 3.05%   |
| Tenda                 | 3        | 2.29%   |
| NetGear               | 2        | 1.53%   |
| Microsoft             | 2        | 1.53%   |
| D-Link                | 2        | 1.53%   |
| Broadcom Limited      | 2        | 1.53%   |
| Xiaomi                | 1        | 0.76%   |
| TP-Link               | 1        | 0.76%   |
| D-Link System         | 1        | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                                 | 13       | 9.7%    |
| Intel Wi-Fi 6 AX200                                                  | 13       | 9.7%    |
| Ralink MT7601U Wireless Adapter                                      | 9        | 6.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 6        | 4.48%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)            | 5        | 3.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5        | 3.73%   |
| Intel Wireless 7260                                                  | 5        | 3.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 4        | 2.99%   |
| Intel Wireless-AC 9260                                               | 4        | 2.99%   |
| Tenda U12                                                            | 3        | 2.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 2.24%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3        | 2.24%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                   | 3        | 2.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 2.24%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3        | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 1.49%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2        | 1.49%   |
| MediaTek 802.11 n WLAN                                               | 2        | 1.49%   |
| Intel Wireless 8260                                                  | 2        | 1.49%   |
| Intel Wireless 7265                                                  | 2        | 1.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2        | 1.49%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2        | 1.49%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 2        | 1.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 2        | 1.49%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                    | 1        | 0.75%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                | 1        | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1        | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1        | 0.75%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 0.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 0.75%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1        | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 0.75%   |
| Realtek 802.11n WLAN Adapter                                         | 1        | 0.75%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 0.75%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 1        | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1        | 0.75%   |
| NetGear A6210                                                        | 1        | 0.75%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]          | 1        | 0.75%   |
| Microsoft XBOX ACC                                                   | 1        | 0.75%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 0.75%   |
| Intel Wireless 8265 / 8275                                           | 1        | 0.75%   |
| Intel Wireless 3165                                                  | 1        | 0.75%   |
| Intel Wireless 3160                                                  | 1        | 0.75%   |
| D-Link Wireless N Nano USB Adapter                                   | 1        | 0.75%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 0.75%   |
| D-Link 802.11n WLAN Adapter                                          | 1        | 0.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 1        | 0.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 158      | 57.66%  |
| Intel                    | 87       | 31.75%  |
| Qualcomm Atheros         | 9        | 3.28%   |
| Huawei Technologies      | 4        | 1.46%   |
| Marvell Technology Group | 3        | 1.09%   |
| Broadcom                 | 3        | 1.09%   |
| Samsung Electronics      | 2        | 0.73%   |
| Aquantia                 | 2        | 0.73%   |
| Xiaomi                   | 1        | 0.36%   |
| Nvidia                   | 1        | 0.36%   |
| Microsoft                | 1        | 0.36%   |
| Loongson Technology      | 1        | 0.36%   |
| IBM                      | 1        | 0.36%   |
| DisplayLink              | 1        | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 133      | 46.34%  |
| Intel I211 Gigabit Network Connection                                         | 14       | 4.88%   |
| Intel Ethernet Connection (2) I219-V                                          | 14       | 4.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11       | 3.83%   |
| Realtek RTL8125 2.5GbE Controller                                             | 10       | 3.48%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 2.44%   |
| Intel Ethernet Connection (12) I219-V                                         | 7        | 2.44%   |
| Intel Ethernet Connection (7) I219-V                                          | 6        | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 2.09%   |
| Intel Ethernet Controller I225-V                                              | 5        | 1.74%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.74%   |
| Intel Ethernet Connection (2) I218-V                                          | 5        | 1.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 1.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 3        | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3        | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 1.05%   |
| Huawei HNS GE/10GE/25GE RDMA Network Controller                               | 3        | 1.05%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 0.7%    |
| Intel I210 Gigabit Network Connection                                         | 2        | 0.7%    |
| Intel Ethernet Connection I217-V                                              | 2        | 0.7%    |
| Intel Ethernet Connection (11) I219-V                                         | 2        | 0.7%    |
| Intel 82546GB Gigabit Ethernet Controller                                     | 2        | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.35%   |
| Samsung Android USB Device                                                    | 1        | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 0.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1        | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.35%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.35%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                             | 1        | 0.35%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1        | 0.35%   |
| Loongson Gigabit Ethernet Controller                                          | 1        | 0.35%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 0.35%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 1        | 0.35%   |
| Intel Ethernet Connection X722                                                | 1        | 0.35%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.35%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.35%   |
| Intel Ethernet Connection (3) I219-LM                                         | 1        | 0.35%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 0.35%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.35%   |
| Intel Ethernet Connection (13) I219-V                                         | 1        | 0.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.35%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.35%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.35%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.35%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.35%   |
| IBM IBM                                                                       | 1        | 0.35%   |
| Huawei HNS GE/10GE/25GE Network Controller                                    | 1        | 0.35%   |
| Huawei COL-L29                                                                | 1        | 0.35%   |
| DisplayLink Dell D3100 Docking Station                                        | 1        | 0.35%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 0.35%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1        | 0.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 0.35%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 260      | 67.71%  |
| WiFi     | 122      | 31.77%  |
| Modem    | 2        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 192      | 72.18%  |
| WiFi     | 74       | 27.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 165      | 62.5%   |
| 2     | 81       | 30.68%  |
| 3     | 9        | 3.41%   |
| 0     | 5        | 1.89%   |
| 6     | 2        | 0.76%   |
| 8     | 1        | 0.38%   |
| 5     | 1        | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 240      | 90.23%  |
| Yes  | 26       | 9.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 50.56%  |
| Cambridge Silicon Radio         | 25       | 28.09%  |
| Realtek Semiconductor           | 8        | 8.99%   |
| ASUSTek Computer                | 4        | 4.49%   |
| Qualcomm Atheros Communications | 2        | 2.25%   |
| Broadcom                        | 2        | 2.25%   |
| Realtek                         | 1        | 1.12%   |
| Foxconn / Hon Hai               | 1        | 1.12%   |
| Apple                           | 1        | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 25       | 28.09%  |
| Intel Bluetooth wireless interface                    | 19       | 21.35%  |
| Intel AX200 Bluetooth                                 | 13       | 14.61%  |
| Realtek Bluetooth Radio                               | 7        | 7.87%   |
| Intel Bluetooth Device                                | 5        | 5.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 3.37%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 3.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 2.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 2.25%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 2.25%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.12%   |
| Realtek Bluetooth Radio                               | 1        | 1.12%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 1.12%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1        | 1.12%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 1.12%   |
| ASUS Bluetooth Radio                                  | 1        | 1.12%   |
| Apple Bluetooth Host Controller                       | 1        | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 178      | 47.09%  |
| AMD                              | 100      | 26.46%  |
| Nvidia                           | 74       | 19.58%  |
| Realtek Semiconductor            | 4        | 1.06%   |
| XMOS                             | 3        | 0.79%   |
| C-Media Electronics              | 3        | 0.79%   |
| Texas Instruments                | 2        | 0.53%   |
| Dell                             | 2        | 0.53%   |
| Creative Labs                    | 2        | 0.53%   |
| Zhaoxin                          | 1        | 0.26%   |
| Unknown                          | 1        | 0.26%   |
| TerraTec Electronic              | 1        | 0.26%   |
| Sony                             | 1        | 0.26%   |
| Silicon Integrated Systems [SiS] | 1        | 0.26%   |
| Sennheiser Communications        | 1        | 0.26%   |
| NXP Semiconductors               | 1        | 0.26%   |
| Loongson Technology              | 1        | 0.26%   |
| Generalplus Technology           | 1        | 0.26%   |
| Atmel                            | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 33       | 7.47%   |
| Intel 200 Series PCH HD Audio                                                     | 27       | 6.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 17       | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                        | 17       | 3.85%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17       | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                            | 16       | 3.62%   |
| Intel Comet Lake PCH-V cAVS                                                       | 15       | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15       | 3.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 15       | 3.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 13       | 2.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 13       | 2.94%   |
| Nvidia GP106 High Definition Audio Controller                                     | 12       | 2.71%   |
| Nvidia GP104 High Definition Audio Controller                                     | 10       | 2.26%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 10       | 2.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 2.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9        | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 9        | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 9        | 2.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9        | 2.04%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.58%   |
| AMD FCH Azalia Controller                                                         | 7        | 1.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 1.36%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 5        | 1.13%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 1.13%   |
| Realtek Semiconductor USB Audio                                                   | 4        | 0.9%    |
| Nvidia TU102 High Definition Audio Controller                                     | 4        | 0.9%    |
| Nvidia GP102 HDMI Audio Controller                                                | 4        | 0.9%    |
| Nvidia GK106 HDMI Audio Controller                                                | 4        | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                             | 4        | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 0.9%    |
| Intel 8 Series HD Audio Controller                                                | 4        | 0.9%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 0.9%    |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 0.68%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.68%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.68%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.68%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 0.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 3        | 0.68%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                             | 3        | 0.68%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 0.68%   |
| XMOS X1S USB DAC                                                                  | 2        | 0.45%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2        | 0.45%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.45%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2        | 0.45%   |
| Dell AC511 USB SoundBar                                                           | 2        | 0.45%   |
| Zhaoxin ZX-E High Definition Audio Controller                                     | 1        | 0.23%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                         | 1        | 0.23%   |
| XMOS USB HiRes Audio F-20                                                         | 1        | 0.23%   |
| Unknown USB Audio                                                                 | 1        | 0.23%   |
| Texas Instruments TMS320C6414 TMS320C6415 TMS320C6416                             | 1        | 0.23%   |
| Texas Instruments Audiolab M-DAC                                                  | 1        | 0.23%   |
| TerraTec Electronic Aureon Dual USB                                               | 1        | 0.23%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                      | 1        | 0.23%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                          | 1        | 0.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 51       | 37.23%  |
| Samsung Electronics | 17       | 12.41%  |
| A-DATA Technology   | 17       | 12.41%  |
| Unknown             | 14       | 10.22%  |
| SK hynix            | 8        | 5.84%   |
| Corsair             | 4        | 2.92%   |
| Unknown             | 4        | 2.92%   |
| Team                | 3        | 2.19%   |
| Micron Technology   | 3        | 2.19%   |
| Ramaxel Technology  | 2        | 1.46%   |
| Kingmax             | 2        | 1.46%   |
| G.Skill             | 2        | 1.46%   |
| Transcend           | 1        | 0.73%   |
| tigo                | 1        | 0.73%   |
| Thermaltake         | 1        | 0.73%   |
| Shenzhen Longsys    | 1        | 0.73%   |
| MAXSUN              | 1        | 0.73%   |
| KLEVV               | 1        | 0.73%   |
| KINGBANK            | 1        | 0.73%   |
| GLOWAY              | 1        | 0.73%   |
| GeIL                | 1        | 0.73%   |
| Apacer              | 1        | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 6        | 3.92%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 4        | 2.61%   |
| Unknown                                                      | 4        | 2.61%   |
| Kingston RAM TF32D4U2S1MEH-8 8GB DIMM DDR4 3200MT/s          | 3        | 1.96%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s      | 3        | 1.96%   |
| Kingston RAM 99P5471-033.A00LF 8GB DIMM DDR3 1600MT/s        | 3        | 1.96%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 2        | 1.31%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s          | 2        | 1.31%   |
| Kingston RAM 99P5474-014.A00LF 4GB DIMM DDR3 1333MT/s        | 2        | 1.31%   |
| Kingston RAM 99P5474-013.A00LF 4GB DIMM DDR3 1600MT/s        | 2        | 1.31%   |
| Kingston RAM 9905701-011.A00G 16GB DIMM DDR4 2400MT/s        | 2        | 1.31%   |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s                     | 2        | 1.31%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                  | 2        | 1.31%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1        | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                    | 1        | 0.65%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                       | 1        | 0.65%   |
| Unknown RAM Module 8192MB                                    | 1        | 0.65%   |
| Unknown RAM Module 512MB DIMM DDR2 333MT/s                   | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 0.65%   |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.65%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                 | 1        | 0.65%   |
| Unknown RAM Module 16384MB DIMM DDR3 1600MT/s                | 1        | 0.65%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 1        | 0.65%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s    | 1        | 0.65%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s             | 1        | 0.65%   |
| tigo RAM 2666Mhz-8G 8GB DIMM DDR4 2666MT/s                   | 1        | 0.65%   |
| Thermaltake RAM zp-4G2666 4GB DIMM DDR4 2666MT/s             | 1        | 0.65%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s           | 1        | 0.65%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s           | 1        | 0.65%   |
| Team RAM TEAMGROUP-UD3 8192MB DIMM DDR3 1600MT/s             | 1        | 0.65%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.65%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.65%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 0.65%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s         | 1        | 0.65%   |
| SK hynix RAM HMT31GR7BFR4C 8192MB DIMM DDR3 1866MT/s         | 1        | 0.65%   |
| SK hynix RAM HMT31GR7AFR4C 8192MB DIMM DDR3 1333MT/s         | 1        | 0.65%   |
| SK hynix RAM HMAA2GU6CJR8N-XN 16384MB DIMM DDR4 3200MT/s     | 1        | 0.65%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s         | 1        | 0.65%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s      | 1        | 0.65%   |
| Shenzhen Longsys RAM FD4AS3200C8GSE 8GB SODIMM DDR4 3200MT/s | 1        | 0.65%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                 | 1        | 0.65%   |
| Samsung RAM Module 32GB DIMM DDR3 800MT/s                    | 1        | 0.65%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s        | 1        | 0.65%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1333MT/s          | 1        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.65%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1        | 0.65%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1866MT/s             | 1        | 0.65%   |
| Samsung RAM M393A2K40CB2-CTD 16GB DIMM DDR4 2666MT/s         | 1        | 0.65%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s       | 1        | 0.65%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s          | 1        | 0.65%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 1        | 0.65%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s          | 1        | 0.65%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.65%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.65%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.65%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s          | 1        | 0.65%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s      | 1        | 0.65%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s     | 1        | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 58       | 46.4%   |
| DDR3    | 49       | 39.2%   |
| Unknown | 8        | 6.4%    |
| SDRAM   | 7        | 5.6%    |
| DDR2    | 3        | 2.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 116      | 92.8%   |
| SODIMM  | 8        | 6.4%    |
| Unknown | 1        | 0.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 53       | 40.15%  |
| 4096  | 33       | 25%     |
| 16384 | 27       | 20.45%  |
| 2048  | 10       | 7.58%   |
| 32768 | 7        | 5.3%    |
| 1024  | 1        | 0.76%   |
| 512   | 1        | 0.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 35       | 24.82%  |
| 1333    | 14       | 9.93%   |
| 3200    | 11       | 7.8%    |
| 2666    | 10       | 7.09%   |
| 2400    | 10       | 7.09%   |
| 3600    | 8        | 5.67%   |
| 800     | 6        | 4.26%   |
| 2667    | 5        | 3.55%   |
| 3466    | 4        | 2.84%   |
| 3533    | 3        | 2.13%   |
| 3400    | 3        | 2.13%   |
| 2933    | 3        | 2.13%   |
| 2133    | 3        | 2.13%   |
| 1866    | 3        | 2.13%   |
| Unknown | 3        | 2.13%   |
| 2800    | 2        | 1.42%   |
| 1800    | 2        | 1.42%   |
| 1066    | 2        | 1.42%   |
| 4800    | 1        | 0.71%   |
| 4199    | 1        | 0.71%   |
| 4133    | 1        | 0.71%   |
| 3800    | 1        | 0.71%   |
| 3733    | 1        | 0.71%   |
| 3500    | 1        | 0.71%   |
| 3000    | 1        | 0.71%   |
| 2200    | 1        | 0.71%   |
| 2187    | 1        | 0.71%   |
| 1867    | 1        | 0.71%   |
| 1067    | 1        | 0.71%   |
| 533     | 1        | 0.71%   |
| 400     | 1        | 0.71%   |
| 333     | 1        | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Hewlett-Packard                    | 1        | 25%     |
| Canon                              | 1        | 25%     |
| Brother Industries                 | 1        | 25%     |
| BeiJing LanXum Computer Technology | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                        | 1        | 25%     |
| Canon PIXMA MP280                                       | 1        | 25%     |
| Brother HL-5440D series                                 | 1        | 25%     |
| BeiJing LanXum Technology Black and White Laser Printer | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 120 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 29.41%  |
| Microdia                      | 2        | 11.76%  |
| Apple                         | 2        | 11.76%  |
| Alcor Micro                   | 2        | 11.76%  |
| Z-Star Microelectronics       | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| Silicon Motion                | 1        | 5.88%   |
| Realtek Semiconductor         | 1        | 5.88%   |
| MacroSilicon                  | 1        | 5.88%   |
| Google                        | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C310                    | 2        | 11.11%  |
| Logitech HD Pro Webcam C920             | 2        | 11.11%  |
| Apple iPhone 5/5C/5S/6/SE               | 2        | 11.11%  |
| Z-Star Venus USB2.0 Camera              | 1        | 5.56%   |
| Sunplus aoni webcam A30                 | 1        | 5.56%   |
| Silicon Motion 300k Pixel Camera        | 1        | 5.56%   |
| Realtek USB Camera                      | 1        | 5.56%   |
| Microdia Document Scanner               | 1        | 5.56%   |
| Microdia Camera                         | 1        | 5.56%   |
| MacroSilicon MiraBox Capture            | 1        | 5.56%   |
| Logitech Webcam C270                    | 1        | 5.56%   |
| Logitech Logitech Webcam C100           | 1        | 5.56%   |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 5.56%   |
| Alcor Micro USB 2.0 PC Camera           | 1        | 5.56%   |
| Alcor Micro USB 2.0 Camera              | 1        | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Shenzhen Goodix Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Shenzhen Goodix Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 210      | 77.49%  |
| 1     | 50       | 18.45%  |
| 2     | 6        | 2.21%   |
| 4     | 2        | 0.74%   |
| 8     | 1        | 0.37%   |
| 5     | 1        | 0.37%   |
| 3     | 1        | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 26       | 32.1%   |
| Net/wireless             | 24       | 29.63%  |
| Communication controller | 6        | 7.41%   |
| Unassigned class         | 5        | 6.17%   |
| Sound                    | 4        | 4.94%   |
| Network                  | 4        | 4.94%   |
| Bluetooth                | 4        | 4.94%   |
| Storage/raid             | 3        | 3.7%    |
| Net/ethernet             | 2        | 2.47%   |
| Fingerprint reader       | 1        | 1.23%   |
| Chipcard                 | 1        | 1.23%   |
| Camera                   | 1        | 1.23%   |

