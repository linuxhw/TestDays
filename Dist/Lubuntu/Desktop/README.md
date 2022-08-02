Lubuntu - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Lubuntu.

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

Total: 448

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X399 SLI PLUS               | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| Dell          | 0WR7PY A03                  | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Dell          | 0X8582                      | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| AMI           | Cherry Trail CR             | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | M5A78L LE                   | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| MSI           | H510I PRO WIFI              | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [21b83125d8](https://linux-hardware.org/?probe=21b83125d8) | Jul 14, 2022 |
| Foxconn       | 2ACA                        | [92681ef1e5](https://linux-hardware.org/?probe=92681ef1e5) | Jul 07, 2022 |
| HP            | 1495                        | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| MSI           | A88XM-E35                   | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| HP            | 1495                        | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Intel         | DQ57TM AAE70931-403         | [92c11e77c4](https://linux-hardware.org/?probe=92c11e77c4) | Jul 03, 2022 |
| MSI           | 760GM-P23                   | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| Intel         | DQ57TM AAE70931-403         | [357e062693](https://linux-hardware.org/?probe=357e062693) | Jun 25, 2022 |
| ASUSTek       | M4N78-AM                    | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| ASUSTek       | M4N78-AM                    | [8522c93ea3](https://linux-hardware.org/?probe=8522c93ea3) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [14ed78a258](https://linux-hardware.org/?probe=14ed78a258) | Jun 11, 2022 |
| ASUSTek       | PRIME X370-A                | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| HP            | 3397                        | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| Unknown       | Unknown                     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| ASRock        | FM2A85X Extreme6            | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| Unknown       | Unknown                     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| Lenovo        | NOK                         | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Unknown       | Unknown                     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Dell          | 0CRH6C A00                  | [fe2648c1f7](https://linux-hardware.org/?probe=fe2648c1f7) | May 14, 2022 |
| Pegatron      | VIOLET6                     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| ASUSTek       | Rampage III GENE            | [798c1f07f6](https://linux-hardware.org/?probe=798c1f07f6) | May 10, 2022 |
| Gigabyte      | G31M-ES2L                   | [bf9f724f45](https://linux-hardware.org/?probe=bf9f724f45) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | [05585fedf4](https://linux-hardware.org/?probe=05585fedf4) | May 04, 2022 |
| Acer          | Aspire XC100A               | [dbad5c417d](https://linux-hardware.org/?probe=dbad5c417d) | May 04, 2022 |
| Intel         | DQ57TM AAE70931-403         | [dd1df3c77d](https://linux-hardware.org/?probe=dd1df3c77d) | May 02, 2022 |
| Dell          | 02YYK5 A01                  | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Dell          | 08NPPY A00                  | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| Dell          | 018D1Y A00                  | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| ASRock        | G31M-S                      | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Gigabyte      | Q77M-D2H                    | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| MSI           | 990FXA-GD65                 | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Unknown       | Unknown                     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| ASUSTek       | M4N68T-M LE                 | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| ASRock        | Q1900M                      | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| ASUSTek       | M2N-SLI                     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Intel         | DH87RL AAG74240-403         | [9c8ac31778](https://linux-hardware.org/?probe=9c8ac31778) | Mar 07, 2022 |
| HP            | 3647h                       | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Dell          | 0HN7XN A00                  | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| ASRock        | H110M-HDV                   | [96416af97f](https://linux-hardware.org/?probe=96416af97f) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| HP            | 339A                        | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| HP            | 2AF7                        | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Dell          | 0DR845                      | [73ab1563bc](https://linux-hardware.org/?probe=73ab1563bc) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Pegatron      | Narra6                      | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| Biostar       | H81MHV3 5.0                 | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | G41M-Combo                  | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Intel         | D945GCLF2 AAE46416-103      | [b3977cd496](https://linux-hardware.org/?probe=b3977cd496) | Feb 10, 2022 |
| ASUSTek       | Puffer                      | [a14c8ed9ad](https://linux-hardware.org/?probe=a14c8ed9ad) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| Gigabyte      | B450M S2H                   | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| HP            | 0A80h                       | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Dell          | 0TW904 A01                  | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| HP            | 3048h                       | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| Unknown       | K8Upgrade-1689              | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| Dell          | 07N90W A01                  | [c8db7d01bd](https://linux-hardware.org/?probe=c8db7d01bd) | Jan 15, 2022 |
| ASRock        | B450M Pro4 R2.0             | [79e8f681f1](https://linux-hardware.org/?probe=79e8f681f1) | Jan 13, 2022 |
| Acer          | WG43M                       | [af76e9bcfe](https://linux-hardware.org/?probe=af76e9bcfe) | Jan 12, 2022 |
| Acer          | WG43M                       | [5784b66aee](https://linux-hardware.org/?probe=5784b66aee) | Jan 12, 2022 |
| Unknown       | Unknown                     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| Dell          | 02YYK5 A01                  | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | [4c24369bb7](https://linux-hardware.org/?probe=4c24369bb7) | Jan 11, 2022 |
| ASUSTek       | P8P67 DELUXE                | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| Dell          | 032W55 A03                  | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| Pegatron      | 2AD5                        | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| Biostar       | A68N-2100                   | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| ASUSTek       | A8N5X                       | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| HP            | 090Ch                       | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| AMI           | Cherry Trail Tablet         | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Dell          | 0J3C2F A02                  | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ddafe324b7](https://linux-hardware.org/?probe=ddafe324b7) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [e9b454a745](https://linux-hardware.org/?probe=e9b454a745) | Dec 04, 2021 |
| MSI           | Boston                      | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| HP            | 1497                        | [f848ad29cd](https://linux-hardware.org/?probe=f848ad29cd) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [b096d0494e](https://linux-hardware.org/?probe=b096d0494e) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| ASUSTek       | CM1435                      | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| Gigabyte      | G31M-S2C                    | [0598f63a64](https://linux-hardware.org/?probe=0598f63a64) | Nov 25, 2021 |
| Gigabyte      | G31M-S2C                    | [4528ddf31d](https://linux-hardware.org/?probe=4528ddf31d) | Nov 25, 2021 |
| Gigabyte      | A520I AC                    | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Acer          | Aspire XC600 v1.0           | [2f1bc07165](https://linux-hardware.org/?probe=2f1bc07165) | Nov 17, 2021 |
| Dell          | 0T568R A00                  | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Acer          | Aspire X1700                | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| Acer          | Aspire X1700                | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| Foxconn       | 2AA9h                       | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Medion        | MS-7728                     | [564ffdab3d](https://linux-hardware.org/?probe=564ffdab3d) | Nov 02, 2021 |
| ASUSTek       | PRIME H410M-E               | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| MSI           | MS-7309                     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| ASUSTek       | H170M-PLUS                  | [15969208ae](https://linux-hardware.org/?probe=15969208ae) | Oct 18, 2021 |
| Unknown       | X99-D8                      | [e335225bdb](https://linux-hardware.org/?probe=e335225bdb) | Oct 17, 2021 |
| AAEON         | MF-001 V1.0                 | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| Acer          | Aspire X1700                | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| MSI           | B350 TOMAHAWK PLUS          | [acbc75f1b8](https://linux-hardware.org/?probe=acbc75f1b8) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| Gigabyte      | P35-DS3L                    | [2f7c2f51f8](https://linux-hardware.org/?probe=2f7c2f51f8) | Oct 01, 2021 |
| Pegatron      | Acacia                      | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| ZOTAC         | NM10                        | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| Foxconn       | Priv                        | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | P8C WS                      | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| ASRock        | Z590M-ITX/ax                | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| Foxconn       | 2AAF                        | [be2ce05253](https://linux-hardware.org/?probe=be2ce05253) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| ASUSTek       | P6T SE                      | [b50449f73f](https://linux-hardware.org/?probe=b50449f73f) | Sep 14, 2021 |
| Dell          | 0M5DCD A00                  | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| MSI           | AMETHYST-M                  | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [0fa53c65bb](https://linux-hardware.org/?probe=0fa53c65bb) | Aug 24, 2021 |
| ASRock        | FM2A68M-DG3+                | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| HP            | 8299                        | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| Huanan        | X99-TF V2.0                 | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| Intel         | DG965SS AAD41678-307        | [d3f38dbf63](https://linux-hardware.org/?probe=d3f38dbf63) | Jul 24, 2021 |
| HP            | 1495                        | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| HP            | 0A1Ch E                     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| ASUSTek       | V-P8H67E                    | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Gigabyte      | Z77X-UD3H                   | [572b814c9a](https://linux-hardware.org/?probe=572b814c9a) | Jul 11, 2021 |
| HP            | 3397                        | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| Positivo      | POS-MI945AA                 | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| Hardkernel    | ODROID-H2                   | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| ASUSTek       | P5K                         | [11fed8f8ae](https://linux-hardware.org/?probe=11fed8f8ae) | Jul 03, 2021 |
| Biostar       | A68N-2100                   | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Dell          | 0TW904 A01                  | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Intel         | DG41WV AAE90316-102         | [c04c0fcc65](https://linux-hardware.org/?probe=c04c0fcc65) | Jun 25, 2021 |
| Gigabyte      | B550M AORUS PRO             | [5d8e8c301f](https://linux-hardware.org/?probe=5d8e8c301f) | Jun 24, 2021 |
| IBM           | 8183V6D                     | [d5c4e8c76b](https://linux-hardware.org/?probe=d5c4e8c76b) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| ASUSTek       | PRIME H410M-E               | [0eb8caf654](https://linux-hardware.org/?probe=0eb8caf654) | Jun 08, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [f4ce6e2f6a](https://linux-hardware.org/?probe=f4ce6e2f6a) | Jun 02, 2021 |
| MSI           | B350M GAMING PRO            | [52c67d407d](https://linux-hardware.org/?probe=52c67d407d) | May 31, 2021 |
| ASUSTek       | K8N                         | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| HP            | 09C4h                       | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| HP            | 21B4 A01                    | [b2a7cbbc72](https://linux-hardware.org/?probe=b2a7cbbc72) | May 23, 2021 |
| Dell          | 0HY175 A03                  | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| ASUSTek       | V-P8H67E                    | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| Dell          | 0D441T A03                  | [c23a919651](https://linux-hardware.org/?probe=c23a919651) | May 18, 2021 |
| MSI           | H61M-E33                    | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ASUSTek       | K8N                         | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| Unknown       | Unknown                     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| ASUSTek       | H110I-PLUS                  | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| ASUSTek       | H110I-PLUS                  | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| IBM           | 8183V6D                     | [0df40278d1](https://linux-hardware.org/?probe=0df40278d1) | May 02, 2021 |
| ASUSTek       | P5GC-MX/1333                | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| AAEON         | MF-001 V1.0                 | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | IMEDIA S1350                | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| ASRock        | FM2A88M Extreme4+           | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| Intel         | SHARKBAY                    | [cf6ec831df](https://linux-hardware.org/?probe=cf6ec831df) | Apr 25, 2021 |
| ASUSTek       | P5Q DELUXE                  | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Intel         | DX58SO AAE29331-404         | [e4f384c278](https://linux-hardware.org/?probe=e4f384c278) | Apr 24, 2021 |
| Intel         | D525MW AAE93082-401         | [aea7beb5c3](https://linux-hardware.org/?probe=aea7beb5c3) | Apr 12, 2021 |
| ASUSTek       | P7P55 LX                    | [219757d806](https://linux-hardware.org/?probe=219757d806) | Apr 11, 2021 |
| ASRock        | N68-VS3 UCC                 | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| MSI           | Boston                      | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| HP            | 1589                        | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| HP            | 8054                        | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| ASUSTek       | Z97-K                       | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Dell          | 09M8Y8 A01                  | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| ASRock        | N68C-S UCC                  | [8ae162d330](https://linux-hardware.org/?probe=8ae162d330) | Mar 16, 2021 |
| Lenovo        | SDK0E50510 WIN              | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| ASRock        | N68C-S UCC                  | [e099627755](https://linux-hardware.org/?probe=e099627755) | Mar 15, 2021 |
| ASRock        | N68C-S UCC                  | [2abee1f31e](https://linux-hardware.org/?probe=2abee1f31e) | Mar 14, 2021 |
| ASRock        | 775Dual-VSTA                | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| MSI           | Boston                      | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| Gigabyte      | H81M-DS2                    | [439d425d4b](https://linux-hardware.org/?probe=439d425d4b) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | [47d5daa739](https://linux-hardware.org/?probe=47d5daa739) | Feb 25, 2021 |
| ASRock        | 775VM800                    | [5b04151216](https://linux-hardware.org/?probe=5b04151216) | Feb 15, 2021 |
| ASRock        | 775VM800                    | [d292f6ac7b](https://linux-hardware.org/?probe=d292f6ac7b) | Feb 12, 2021 |
| Intel         | ChiefRiver                  | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| Intel         | D945GTP AAC97834-305        | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | M2A-MX                      | [1541b0dbe1](https://linux-hardware.org/?probe=1541b0dbe1) | Feb 09, 2021 |
| ASUSTek       | M2A-MX                      | [391d63e436](https://linux-hardware.org/?probe=391d63e436) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | [7c78d0efc3](https://linux-hardware.org/?probe=7c78d0efc3) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | [beddd7c01d](https://linux-hardware.org/?probe=beddd7c01d) | Feb 09, 2021 |
| ASUSTek       | P5G41T-M LE                 | [f08dd9c298](https://linux-hardware.org/?probe=f08dd9c298) | Feb 08, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | [a8af34d0ee](https://linux-hardware.org/?probe=a8af34d0ee) | Feb 08, 2021 |
| ASUSTek       | P5G41T-M LE                 | [32061cad93](https://linux-hardware.org/?probe=32061cad93) | Feb 08, 2021 |
| HP            | 3048h                       | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Dell          | 0TP406                      | [8d298a20d5](https://linux-hardware.org/?probe=8d298a20d5) | Jan 28, 2021 |
| Lenovo        | ThinkCentre XXXX 9632AU8    | [cdc139f77e](https://linux-hardware.org/?probe=cdc139f77e) | Jan 24, 2021 |
| MSI           | MS-7270                     | [9e5fa11934](https://linux-hardware.org/?probe=9e5fa11934) | Jan 24, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [fdc50253da](https://linux-hardware.org/?probe=fdc50253da) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | [3761191ef4](https://linux-hardware.org/?probe=3761191ef4) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | [5446971c89](https://linux-hardware.org/?probe=5446971c89) | Jan 20, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [71a9d08996](https://linux-hardware.org/?probe=71a9d08996) | Jan 14, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [55f1890303](https://linux-hardware.org/?probe=55f1890303) | Jan 11, 2021 |
| Pegatron      | NARRA3                      | [ebb1428c72](https://linux-hardware.org/?probe=ebb1428c72) | Jan 11, 2021 |
| ASUSTek       | P8Z68-V LX                  | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| Gigabyte      | Z77N-WIFI                   | [653ea393e6](https://linux-hardware.org/?probe=653ea393e6) | Jan 06, 2021 |
| MSI           | AMETHYST-M                  | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| AMI           | Cherry Trail CR             | [4fe52138ff](https://linux-hardware.org/?probe=4fe52138ff) | Jan 04, 2021 |
| AMI           | Cherry Trail CR             | [d86f56eaf3](https://linux-hardware.org/?probe=d86f56eaf3) | Jan 04, 2021 |
| MSI           | MS-7250                     | [72950b548d](https://linux-hardware.org/?probe=72950b548d) | Jan 04, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [48edae2fa9](https://linux-hardware.org/?probe=48edae2fa9) | Jan 04, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [73f8eb43d6](https://linux-hardware.org/?probe=73f8eb43d6) | Jan 01, 2021 |
| Gigabyte      | H81M-HD3                    | [5df1b1d371](https://linux-hardware.org/?probe=5df1b1d371) | Dec 30, 2020 |
| ASRock        | FM2A88X Pro3+               | [a57902b2df](https://linux-hardware.org/?probe=a57902b2df) | Dec 23, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Gigabyte      | B550M AORUS PRO             | [cdc016f9d1](https://linux-hardware.org/?probe=cdc016f9d1) | Dec 18, 2020 |
| HP            | 3031h                       | [b1c4657359](https://linux-hardware.org/?probe=b1c4657359) | Dec 16, 2020 |
| Gigabyte      | GA-78LMT-S2P                | [43ba858067](https://linux-hardware.org/?probe=43ba858067) | Dec 16, 2020 |
| Dell          | 0WG864                      | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gigabyte      | H77M-D3H                    | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| ASRock        | FM2A85X Extreme6            | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | [19e0a468d5](https://linux-hardware.org/?probe=19e0a468d5) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | [c76fe73c42](https://linux-hardware.org/?probe=c76fe73c42) | Dec 01, 2020 |
| Gigabyte      | 965P-DS3                    | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | [174de8e1d6](https://linux-hardware.org/?probe=174de8e1d6) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | [7b85d35e4d](https://linux-hardware.org/?probe=7b85d35e4d) | Nov 29, 2020 |
| MSI           | P55-GD80                    | [409cb71474](https://linux-hardware.org/?probe=409cb71474) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | 2820h                       | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | [63776843ec](https://linux-hardware.org/?probe=63776843ec) | Nov 21, 2020 |
| Pegatron      | Narra6                      | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| MSI           | MS-7250                     | [8f408a7fec](https://linux-hardware.org/?probe=8f408a7fec) | Nov 17, 2020 |
| HP            | 09F8h                       | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| Foxconn       | 2AA9                        | [dbe623f2ad](https://linux-hardware.org/?probe=dbe623f2ad) | Nov 14, 2020 |
| ECS           | Iris8                       | [1614d7d736](https://linux-hardware.org/?probe=1614d7d736) | Nov 14, 2020 |
| IBM           | 8183V6D                     | [7784e64311](https://linux-hardware.org/?probe=7784e64311) | Nov 14, 2020 |
| ECS           | Iris8                       | [c2d76cebd4](https://linux-hardware.org/?probe=c2d76cebd4) | Nov 14, 2020 |
| MSI           | G41M-P28                    | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| ASRock        | 4Core1600-GLAN              | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| IBM           | 8183V6D                     | [440a6a1057](https://linux-hardware.org/?probe=440a6a1057) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Dell          | 0J3C2F A02                  | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| ASRock        | G41M-GS3                    | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| ASUSTek       | P5S800-VM                   | [abb4e0e0c2](https://linux-hardware.org/?probe=abb4e0e0c2) | Oct 17, 2020 |
| ASUSTek       | PRIME H310M-K               | [706aa7bb74](https://linux-hardware.org/?probe=706aa7bb74) | Oct 13, 2020 |
| ASUSTek       | PRIME H310M-K               | [132e2b687c](https://linux-hardware.org/?probe=132e2b687c) | Oct 13, 2020 |
| Dell          | 0KRC95 A01                  | [a6576290b5](https://linux-hardware.org/?probe=a6576290b5) | Oct 10, 2020 |
| MSI           | H97M-E35                    | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| MSI           | H110M ECO                   | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [bcac6bcfaf](https://linux-hardware.org/?probe=bcac6bcfaf) | Oct 03, 2020 |
| Biostar       | N61PC-M2S                   | [f41fe9205d](https://linux-hardware.org/?probe=f41fe9205d) | Sep 30, 2020 |
| Gigabyte      | Z370P D3-CF                 | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [426bdc3586](https://linux-hardware.org/?probe=426bdc3586) | Sep 24, 2020 |
| Gateway       | SX2185                      | [7404f09683](https://linux-hardware.org/?probe=7404f09683) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Dell          | 0J3C2F A02                  | [c1cbfad587](https://linux-hardware.org/?probe=c1cbfad587) | Sep 20, 2020 |
| ASRock        | A320M-DGS                   | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| HP            | 0A50h                       | [ace0e3fed5](https://linux-hardware.org/?probe=ace0e3fed5) | Sep 13, 2020 |
| HP            | 0A50h                       | [f70b1ce07f](https://linux-hardware.org/?probe=f70b1ce07f) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| ASUSTek       | V-P8H67E                    | [a86b68e7e2](https://linux-hardware.org/?probe=a86b68e7e2) | Sep 05, 2020 |
| Dell          | 0CU409                      | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASRock        | A320M-HD                    | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| Biostar       | A68N-2100                   | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| PCChips       | A13G                        | [d3bc7edc49](https://linux-hardware.org/?probe=d3bc7edc49) | Aug 09, 2020 |
| Lenovo        | ThinkCentre M58p 7220W21    | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Philco        | 14F                         | [8fce6fc79b](https://linux-hardware.org/?probe=8fce6fc79b) | Jul 31, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [10a2f3c16b](https://linux-hardware.org/?probe=10a2f3c16b) | Jul 30, 2020 |
| Lenovo        | SDK0E50515 STD              | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| HP            | 085Ch                       | [c22eb5394a](https://linux-hardware.org/?probe=c22eb5394a) | Jul 22, 2020 |
| HP            | 085Ch                       | [a6b75813e8](https://linux-hardware.org/?probe=a6b75813e8) | Jul 20, 2020 |
| IBM           | eServer x3105 -[434722J]... | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| MSI           | B450M MORTAR MAX            | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Gigabyte      | H61M-S1                     | [03b6eef668](https://linux-hardware.org/?probe=03b6eef668) | Jul 16, 2020 |
| Gigabyte      | H61M-S1                     | [61727004f5](https://linux-hardware.org/?probe=61727004f5) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | [b97000d1d8](https://linux-hardware.org/?probe=b97000d1d8) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | [94cba10ae4](https://linux-hardware.org/?probe=94cba10ae4) | Jul 15, 2020 |
| ASUSTek       | P5S800-VM                   | [214ec41334](https://linux-hardware.org/?probe=214ec41334) | Jul 14, 2020 |
| Biostar       | A68N-2100                   | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | 3396                        | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | [66d4b86237](https://linux-hardware.org/?probe=66d4b86237) | Jul 01, 2020 |
| MSI           | X570-A PRO                  | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| HP            | 304Ah                       | [196b570551](https://linux-hardware.org/?probe=196b570551) | Jun 23, 2020 |
| HP            | 304Ah                       | [bfe838c10f](https://linux-hardware.org/?probe=bfe838c10f) | Jun 23, 2020 |
| Dell          | 0Y2MRG A00                  | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| Intel         | DG31PR AAE58249-306         | [ee1eb9d6fb](https://linux-hardware.org/?probe=ee1eb9d6fb) | Jun 18, 2020 |
| ASUSTek       | M2R-FVM                     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| HP            | 09E0h                       | [4979e74209](https://linux-hardware.org/?probe=4979e74209) | Jun 18, 2020 |
| MSI           | 0A48                        | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| HP            | 09E0h                       | [3fbd5af0ab](https://linux-hardware.org/?probe=3fbd5af0ab) | Jun 16, 2020 |
| Intel         | DG31PR AAE58249-306         | [9e786bc6e0](https://linux-hardware.org/?probe=9e786bc6e0) | Jun 12, 2020 |
| ASUSTek       | ET1612I                     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Qbex          | HDC-M                       | [5d547380f0](https://linux-hardware.org/?probe=5d547380f0) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| Biostar       | GF7025-M2                   | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| ASUSTek       | A8N-SLI                     | [5ccefc89ce](https://linux-hardware.org/?probe=5ccefc89ce) | May 23, 2020 |
| ASUSTek       | A8N-SLI                     | [2c0867a9ec](https://linux-hardware.org/?probe=2c0867a9ec) | May 23, 2020 |
| ASUSTek       | P8H67-M LX                  | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| Gigabyte      | GA-870A-UD3                 | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| HP            | 21B4 A01                    | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| Gigabyte      | 8I865G775-G                 | [f7d448edb4](https://linux-hardware.org/?probe=f7d448edb4) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [71f901a69f](https://linux-hardware.org/?probe=71f901a69f) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [bce5724752](https://linux-hardware.org/?probe=bce5724752) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [21d6bc116d](https://linux-hardware.org/?probe=21d6bc116d) | May 15, 2020 |
| VIA Techno... | P4X266-8233                 | [0bf3b29d80](https://linux-hardware.org/?probe=0bf3b29d80) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [597e6a2b14](https://linux-hardware.org/?probe=597e6a2b14) | May 14, 2020 |
| ASUSTek       | Berkeley                    | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| ASUSTek       | P5N-E SLI                   | [7af6f2c4d4](https://linux-hardware.org/?probe=7af6f2c4d4) | May 11, 2020 |
| ASUSTek       | P5S800-VM                   | [a4020f35b9](https://linux-hardware.org/?probe=a4020f35b9) | May 10, 2020 |
| ASUSTek       | P5B-Deluxe                  | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Acer          | Aspire XC-703G              | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | 090Ch                       | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP            | 090Ch                       | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| Gigabyte      | GA-K8NF-9                   | [70a90ff062](https://linux-hardware.org/?probe=70a90ff062) | May 04, 2020 |
| ASUSTek       | P5G41C-M LX                 | [180e7f281b](https://linux-hardware.org/?probe=180e7f281b) | May 03, 2020 |
| VIA Techno... | P4X266-8233                 | [069ba04b1c](https://linux-hardware.org/?probe=069ba04b1c) | May 02, 2020 |
| Intel         | DN2800MT AAG23738-801       | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| ASUSTek       | VM40B                       | [acf2922656](https://linux-hardware.org/?probe=acf2922656) | Apr 26, 2020 |
| ASUSTek       | VM40B                       | [2fc777ae6a](https://linux-hardware.org/?probe=2fc777ae6a) | Apr 26, 2020 |
| MSI           | Boston                      | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| Acer          | Aspire X1800                | [beb70c1fc5](https://linux-hardware.org/?probe=beb70c1fc5) | Apr 19, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [c263eac3e9](https://linux-hardware.org/?probe=c263eac3e9) | Apr 13, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [75fff2a0a6](https://linux-hardware.org/?probe=75fff2a0a6) | Apr 13, 2020 |
| eMachines     | EL1360G                     | [53d061d3b2](https://linux-hardware.org/?probe=53d061d3b2) | Apr 11, 2020 |
| Dell          | 0MM599                      | [19e2d2af44](https://linux-hardware.org/?probe=19e2d2af44) | Apr 11, 2020 |
| Intel         | DN2820FYK H24582-204        | [77cf46ddde](https://linux-hardware.org/?probe=77cf46ddde) | Apr 06, 2020 |
| Gigabyte      | nForce                      | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [7759201b72](https://linux-hardware.org/?probe=7759201b72) | Apr 03, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [8e8dbf13fb](https://linux-hardware.org/?probe=8e8dbf13fb) | Mar 30, 2020 |
| Dell          | 0WG864                      | [092ae3a8ca](https://linux-hardware.org/?probe=092ae3a8ca) | Mar 27, 2020 |
| Gigabyte      | 945GCM-S2L                  | [548577276f](https://linux-hardware.org/?probe=548577276f) | Mar 27, 2020 |
| ASUSTek       | A8V-MQ                      | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| ASRock        | FM2A85X Extreme6            | [e4588ca61a](https://linux-hardware.org/?probe=e4588ca61a) | Mar 21, 2020 |
| Dell          | 0T287N A03                  | [02ebc6d299](https://linux-hardware.org/?probe=02ebc6d299) | Mar 16, 2020 |
| ASRock        | ConRoe865GV                 | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| ASRock        | B450M Pro4                  | [d7eb29abd9](https://linux-hardware.org/?probe=d7eb29abd9) | Mar 13, 2020 |
| ASRock        | ConRoe865GV                 | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [3746f6db56](https://linux-hardware.org/?probe=3746f6db56) | Mar 12, 2020 |
| Gigabyte      | P67A-D3-B3                  | [c00f70d6a6](https://linux-hardware.org/?probe=c00f70d6a6) | Mar 10, 2020 |
| ASUSTek       | H81M-E                      | [709a2484bc](https://linux-hardware.org/?probe=709a2484bc) | Mar 09, 2020 |
| ASRock        | B450M Pro4                  | [168bd28370](https://linux-hardware.org/?probe=168bd28370) | Feb 27, 2020 |
| ASUSTek       | CUSL2-M                     | [a20a268bb5](https://linux-hardware.org/?probe=a20a268bb5) | Feb 23, 2020 |
| Dell          | 08HPGT A01                  | [64e6dd4ba1](https://linux-hardware.org/?probe=64e6dd4ba1) | Feb 20, 2020 |
| HP            | 0A64h                       | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| HP            | 0A64h                       | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| ASRock        | N73V-S                      | [80b08d6e38](https://linux-hardware.org/?probe=80b08d6e38) | Jan 27, 2020 |
| ASRock        | N73V-S                      | [1f67c1102b](https://linux-hardware.org/?probe=1f67c1102b) | Jan 26, 2020 |
| Gigabyte      | GA-K8NF-9                   | [2b8833407a](https://linux-hardware.org/?probe=2b8833407a) | Jan 25, 2020 |
| MSI           | MS-7369                     | [5c6d33ae36](https://linux-hardware.org/?probe=5c6d33ae36) | Jan 25, 2020 |
| ASUSTek       | P5G41C-M LX                 | [cc1a05b68f](https://linux-hardware.org/?probe=cc1a05b68f) | Jan 24, 2020 |
| Dell          | 0GY6Y8 A03                  | [88961c610a](https://linux-hardware.org/?probe=88961c610a) | Jan 23, 2020 |
| ASUSTek       | P5QD TURBO                  | [d96168ded2](https://linux-hardware.org/?probe=d96168ded2) | Jan 12, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [947354716f](https://linux-hardware.org/?probe=947354716f) | Jan 07, 2020 |
| HP            | 0AA8h                       | [77b5333591](https://linux-hardware.org/?probe=77b5333591) | Jan 04, 2020 |
| ASUSTek       | V-P8H67E                    | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| ASUSTek       | V-P8H67E                    | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| AAEON         | MF-001 V1.0                 | [08480474f8](https://linux-hardware.org/?probe=08480474f8) | Dec 08, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [36a930502d](https://linux-hardware.org/?probe=36a930502d) | Nov 30, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [3bf663653b](https://linux-hardware.org/?probe=3bf663653b) | Nov 23, 2019 |
| ASRock        | H55M                        | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| Acer          | Aspire XC-703               | [5e3493c08f](https://linux-hardware.org/?probe=5e3493c08f) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [d31b932863](https://linux-hardware.org/?probe=d31b932863) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [0a5f0a6adc](https://linux-hardware.org/?probe=0a5f0a6adc) | Nov 11, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [59fbd049bb](https://linux-hardware.org/?probe=59fbd049bb) | Aug 25, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [0b0497458b](https://linux-hardware.org/?probe=0b0497458b) | Aug 22, 2019 |
| ASUSTek       | Z97-A                       | [d85c2d26cb](https://linux-hardware.org/?probe=d85c2d26cb) | Jul 26, 2019 |
| ASRock        | AD525PV3                    | [682bc26535](https://linux-hardware.org/?probe=682bc26535) | Jul 03, 2019 |
| ASUSTek       | P5VD2-VM                    | [b99ee7c099](https://linux-hardware.org/?probe=b99ee7c099) | Apr 02, 2019 |
| ASUSTek       | M2N4-SLI                    | [84abf7384b](https://linux-hardware.org/?probe=84abf7384b) | Mar 24, 2019 |
| Unknown       | Unknown                     | [52b4b037a1](https://linux-hardware.org/?probe=52b4b037a1) | Feb 01, 2019 |
| Unknown       | Unknown                     | [f9908c15ca](https://linux-hardware.org/?probe=f9908c15ca) | Feb 01, 2019 |
| ASRock        | B75M-DGS R2.0               | [b54d9c9c47](https://linux-hardware.org/?probe=b54d9c9c47) | Dec 19, 2018 |
| PCWare        | IPX1800G2                   | [1721a635e2](https://linux-hardware.org/?probe=1721a635e2) | Nov 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Lubuntu 20.04 | 136      | 43.17%  |
| Lubuntu 18.04 | 65       | 20.63%  |
| Lubuntu 21.10 | 27       | 8.57%   |
| Lubuntu 22.04 | 20       | 6.35%   |
| Lubuntu 19.10 | 17       | 5.4%    |
| Lubuntu 20.10 | 15       | 4.76%   |
| Lubuntu 21.04 | 13       | 4.13%   |
| Lubuntu 16.04 | 12       | 3.81%   |
| Lubuntu 18.10 | 4        | 1.27%   |
| Lubuntu 19.04 | 2        | 0.63%   |
| Lubuntu 16.10 | 2        | 0.63%   |
| Lubuntu 22.10 | 1        | 0.32%   |
| Lubuntu 17.04 | 1        | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Lubuntu | 309      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.4.0-42-generic   | 10       | 2.94%   |
| 5.4.0-52-generic   | 8        | 2.35%   |
| 5.8.0-50-generic   | 7        | 2.06%   |
| 5.13.0-19-generic  | 7        | 2.06%   |
| 5.11.0-27-generic  | 7        | 2.06%   |
| 5.4.0-54-generic   | 5        | 1.47%   |
| 5.15.0-41-generic  | 5        | 1.47%   |
| 5.13.0-28-generic  | 5        | 1.47%   |
| 5.8.0-59-generic   | 4        | 1.18%   |
| 5.4.0-77-generic   | 4        | 1.18%   |
| 5.4.0-67-generic   | 4        | 1.18%   |
| 5.4.0-48-generic   | 4        | 1.18%   |
| 5.4.0-47-generic   | 4        | 1.18%   |
| 5.4.0-40-generic   | 4        | 1.18%   |
| 5.4.0-29-generic   | 4        | 1.18%   |
| 5.4.0-122-generic  | 4        | 1.18%   |
| 5.13.0-40-generic  | 4        | 1.18%   |
| 4.15.0-74-generic  | 4        | 1.18%   |
| 4.15.0-106-generic | 4        | 1.18%   |
| 5.8.0-63-generic   | 3        | 0.88%   |
| 5.8.0-49-generic   | 3        | 0.88%   |
| 5.8.0-41-generic   | 3        | 0.88%   |
| 5.4.0-96-generic   | 3        | 0.88%   |
| 5.4.0-91-generic   | 3        | 0.88%   |
| 5.4.0-73-generic   | 3        | 0.88%   |
| 5.4.0-72-generic   | 3        | 0.88%   |
| 5.4.0-66-generic   | 3        | 0.88%   |
| 5.4.0-60-generic   | 3        | 0.88%   |
| 5.4.0-53-generic   | 3        | 0.88%   |
| 5.4.0-37-generic   | 3        | 0.88%   |
| 5.4.0-33-generic   | 3        | 0.88%   |
| 5.4.0-26-generic   | 3        | 0.88%   |
| 5.3.0-42-generic   | 3        | 0.88%   |
| 5.3.0-40-generic   | 3        | 0.88%   |
| 5.15.0-39-generic  | 3        | 0.88%   |
| 5.15.0-30-generic  | 3        | 0.88%   |
| 5.15.0-25-generic  | 3        | 0.88%   |
| 5.13.0-30-generic  | 3        | 0.88%   |
| 5.13.0-27-generic  | 3        | 0.88%   |
| 5.11.0-16-generic  | 3        | 0.88%   |
| 4.18.0-10-generic  | 3        | 0.88%   |
| 4.15.0-96-generic  | 3        | 0.88%   |
| 4.15.0-91-generic  | 3        | 0.88%   |
| 4.15.0-88-generic  | 3        | 0.88%   |
| 4.15.0-58-generic  | 3        | 0.88%   |
| 5.8.0-53-generic   | 2        | 0.59%   |
| 5.8.0-45-generic   | 2        | 0.59%   |
| 5.8.0-43-generic   | 2        | 0.59%   |
| 5.4.0-90-generic   | 2        | 0.59%   |
| 5.4.0-59-generic   | 2        | 0.59%   |
| 5.4.0-58-generic   | 2        | 0.59%   |
| 5.4.0-109-generic  | 2        | 0.59%   |
| 5.3.0-51-generic   | 2        | 0.59%   |
| 5.3.0-46-generic   | 2        | 0.59%   |
| 5.3.0-18-generic   | 2        | 0.59%   |
| 5.15.0-40-generic  | 2        | 0.59%   |
| 5.15.0-27-generic  | 2        | 0.59%   |
| 5.13.0-39-generic  | 2        | 0.59%   |
| 5.13.0-35-generic  | 2        | 0.59%   |
| 5.13.0-25-generic  | 2        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 94       | 29.84%  |
| 4.15.0  | 50       | 15.87%  |
| 5.13.0  | 39       | 12.38%  |
| 5.8.0   | 36       | 11.43%  |
| 5.11.0  | 30       | 9.52%   |
| 5.15.0  | 21       | 6.67%   |
| 5.3.0   | 20       | 6.35%   |
| 5.0.0   | 5        | 1.59%   |
| 4.4.0   | 4        | 1.27%   |
| 4.18.0  | 4        | 1.27%   |
| 4.8.0   | 2        | 0.63%   |
| 5.6.15  | 1        | 0.32%   |
| 5.6.0   | 1        | 0.32%   |
| 5.4.30  | 1        | 0.32%   |
| 5.3.18  | 1        | 0.32%   |
| 5.16.5  | 1        | 0.32%   |
| 5.15.5  | 1        | 0.32%   |
| 5.14.0  | 1        | 0.32%   |
| 5.12.1  | 1        | 0.32%   |
| 4.15.18 | 1        | 0.32%   |
| 4.10.0  | 1        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 95       | 30.16%  |
| 4.15    | 51       | 16.19%  |
| 5.13    | 39       | 12.38%  |
| 5.8     | 36       | 11.43%  |
| 5.11    | 30       | 9.52%   |
| 5.15    | 22       | 6.98%   |
| 5.3     | 21       | 6.67%   |
| 5.0     | 5        | 1.59%   |
| 4.4     | 4        | 1.27%   |
| 4.18    | 4        | 1.27%   |
| 5.6     | 2        | 0.63%   |
| 4.8     | 2        | 0.63%   |
| 5.16    | 1        | 0.32%   |
| 5.14    | 1        | 0.32%   |
| 5.12    | 1        | 0.32%   |
| 4.10    | 1        | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 274      | 88.67%  |
| i686   | 34       | 11%     |
| ppc64  | 1        | 0.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| LXQt            | 219      | 70.19%  |
| LXDE            | 72       | 23.08%  |
| GNOME           | 8        | 2.56%   |
| Unknown         | 6        | 1.92%   |
| Openbox         | 2        | 0.64%   |
| XFCE            | 1        | 0.32%   |
| X-Cinnamon      | 1        | 0.32%   |
| KDE5            | 1        | 0.32%   |
| i3              | 1        | 0.32%   |
| GNOME Flashback | 1        | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 299      | 95.83%  |
| Tty         | 8        | 2.56%   |
| Wayland     | 2        | 0.64%   |
| Unknown     | 2        | 0.64%   |
| Unspecified | 1        | 0.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 126      | 40.13%  |
| Unknown | 120      | 38.22%  |
| LightDM | 28       | 8.92%   |
| TDM     | 24       | 7.64%   |
| GDM     | 11       | 3.5%    |
| XDM     | 2        | 0.64%   |
| LXDM    | 2        | 0.64%   |
| GDM3    | 1        | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 74       | 23.79%  |
| fr_FR   | 27       | 8.68%   |
| pt_BR   | 22       | 7.07%   |
| de_DE   | 22       | 7.07%   |
| it_IT   | 20       | 6.43%   |
| C       | 18       | 5.79%   |
| en_GB   | 15       | 4.82%   |
| ru_RU   | 14       | 4.5%    |
| Unknown | 13       | 4.18%   |
| en_CA   | 11       | 3.54%   |
| es_ES   | 6        | 1.93%   |
| en_AU   | 6        | 1.93%   |
| nl_NL   | 4        | 1.29%   |
| ja_JP   | 4        | 1.29%   |
| hu_HU   | 4        | 1.29%   |
| es_AR   | 4        | 1.29%   |
| cs_CZ   | 4        | 1.29%   |
| pl_PL   | 3        | 0.96%   |
| es_MX   | 3        | 0.96%   |
| tr_TR   | 2        | 0.64%   |
| pt_PT   | 2        | 0.64%   |
| fr_CA   | 2        | 0.64%   |
| fi_FI   | 2        | 0.64%   |
| es_UY   | 2        | 0.64%   |
| es_PE   | 2        | 0.64%   |
| es_CR   | 2        | 0.64%   |
| es_CO   | 2        | 0.64%   |
| en_ZA   | 2        | 0.64%   |
| en_IN   | 2        | 0.64%   |
| el_GR   | 2        | 0.64%   |
| de_CH   | 2        | 0.64%   |
| bg_BG   | 2        | 0.64%   |
| sv_SE   | 1        | 0.32%   |
| ru_UA   | 1        | 0.32%   |
| nl_BE   | 1        | 0.32%   |
| hr_HR   | 1        | 0.32%   |
| es_GT   | 1        | 0.32%   |
| es_EC   | 1        | 0.32%   |
| es_CL   | 1        | 0.32%   |
| en_SG   | 1        | 0.32%   |
| en_NZ   | 1        | 0.32%   |
| en_HK   | 1        | 0.32%   |
| cv_RU   | 1        | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 233      | 75.4%   |
| EFI  | 76       | 24.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 281      | 90.94%  |
| Overlay | 19       | 6.15%   |
| Xfs     | 3        | 0.97%   |
| Btrfs   | 2        | 0.65%   |
| Unknown | 2        | 0.65%   |
| Zfs     | 1        | 0.32%   |
| F2fs    | 1        | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 163      | 52.58%  |
| MBR     | 82       | 26.45%  |
| GPT     | 65       | 20.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 262      | 84.24%  |
| Yes       | 49       | 15.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 209      | 67.2%   |
| Yes       | 102      | 32.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 57       | 18.45%  |
| Gigabyte Technology | 37       | 11.97%  |
| Hewlett-Packard     | 33       | 10.68%  |
| Dell                | 30       | 9.71%   |
| ASRock              | 28       | 9.06%   |
| MSI                 | 27       | 8.74%   |
| Intel               | 17       | 5.5%    |
| Lenovo              | 13       | 4.21%   |
| Unknown             | 11       | 3.56%   |
| Acer                | 10       | 3.24%   |
| Pegatron            | 7        | 2.27%   |
| Foxconn             | 7        | 2.27%   |
| Biostar             | 5        | 1.62%   |
| AAEON               | 4        | 1.29%   |
| AMI                 | 3        | 0.97%   |
| Positivo            | 2        | 0.65%   |
| IBM                 | 2        | 0.65%   |
| eMachines           | 2        | 0.65%   |
| ZOTAC               | 1        | 0.32%   |
| VIA Technologies    | 1        | 0.32%   |
| Qbex                | 1        | 0.32%   |
| Philco              | 1        | 0.32%   |
| PCWare              | 1        | 0.32%   |
| PCChips             | 1        | 0.32%   |
| Packard Bell        | 1        | 0.32%   |
| Medion              | 1        | 0.32%   |
| Huanan              | 1        | 0.32%   |
| Hardkernel          | 1        | 0.32%   |
| Gateway             | 1        | 0.32%   |
| Fujitsu Siemens     | 1        | 0.32%   |
| Fujitsu             | 1        | 0.32%   |
| ECS                 | 1        | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 11       | 3.56%   |
| AAEON MF-001                        | 4        | 1.29%   |
| MSI MS-7C37                         | 3        | 0.97%   |
| Dell OptiPlex 790                   | 3        | 0.97%   |
| Dell OptiPlex 7010                  | 3        | 0.97%   |
| ASUS V-P8H67E                       | 3        | 0.97%   |
| ASUS All Series                     | 3        | 0.97%   |
| ASRock FM2A85X Extreme6             | 3        | 0.97%   |
| MSI MS-7B89                         | 2        | 0.65%   |
| HP t620 Quad Core TC                | 2        | 0.65%   |
| HP Compaq dc7800 Small Form Factor  | 2        | 0.65%   |
| HP Compaq 6000 Pro SFF PC           | 2        | 0.65%   |
| Gigabyte H81M-DS2                   | 2        | 0.65%   |
| Dell DM061                          | 2        | 0.65%   |
| Dell Dimension 9100                 | 2        | 0.65%   |
| ASUS PRIME H410M-E                  | 2        | 0.65%   |
| ASRock N68-VS3 UCC                  | 2        | 0.65%   |
| ASRock 775Dual-VSTA                 | 2        | 0.65%   |
| AMI Z83-V                           | 2        | 0.65%   |
| ZOTAC NM10                          | 1        | 0.32%   |
| VIA P4X266-8233                     | 1        | 0.32%   |
| Qbex HDC-M                          | 1        | 0.32%   |
| Positivo POS-MI945AA                | 1        | 0.32%   |
| Positivo POS-EIH61CE                | 1        | 0.32%   |
| Philco 14F                          | 1        | 0.32%   |
| Pegatron WE216AA-ABF CQ5335FR       | 1        | 0.32%   |
| Pegatron NC689AA-ABA s3700y         | 1        | 0.32%   |
| Pegatron FQ425AA-ABA a6655f         | 1        | 0.32%   |
| Pegatron FL308AA-ABD IQ512de        | 1        | 0.32%   |
| Pegatron AY748AA-ABA p6320y         | 1        | 0.32%   |
| Pegatron AY652AA-ABA s5310y         | 1        | 0.32%   |
| Pegatron 2AD5                       | 1        | 0.32%   |
| PCWare IPX1800G2                    | 1        | 0.32%   |
| PCChips A13G                        | 1        | 0.32%   |
| Packard Bell IMEDIA S1350           | 1        | 0.32%   |
| MSI MS-7D16                         | 1        | 0.32%   |
| MSI MS-7C82                         | 1        | 0.32%   |
| MSI MS-7C80                         | 1        | 0.32%   |
| MSI MS-7B86                         | 1        | 0.32%   |
| MSI MS-7B36                         | 1        | 0.32%   |
| MSI MS-7B09                         | 1        | 0.32%   |
| MSI MS-7A39                         | 1        | 0.32%   |
| MSI MS-7994                         | 1        | 0.32%   |
| MSI MS-7846                         | 1        | 0.32%   |
| MSI MS-7721                         | 1        | 0.32%   |
| MSI MS-7680                         | 1        | 0.32%   |
| MSI MS-7641                         | 1        | 0.32%   |
| MSI MS-7640                         | 1        | 0.32%   |
| MSI MS-7592                         | 1        | 0.32%   |
| MSI MS-7581                         | 1        | 0.32%   |
| MSI MS-7369                         | 1        | 0.32%   |
| MSI MS-7309                         | 1        | 0.32%   |
| MSI MS-7270                         | 1        | 0.32%   |
| MSI MS-7250                         | 1        | 0.32%   |
| MSI KT541AA-UUB a6528hk             | 1        | 0.32%   |
| MSI ER883AA-ABA M7470N              | 1        | 0.32%   |
| MSI Compaq dx2200 MT                | 1        | 0.32%   |
| Medion MS-7728                      | 1        | 0.32%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 0.32%   |
| Lenovo ThinkCentre XXXX 9632AU8     | 1        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 18       | 5.83%   |
| Dell OptiPlex        | 15       | 4.85%   |
| Unknown              | 11       | 3.56%   |
| Lenovo ThinkCentre   | 10       | 3.24%   |
| Acer Aspire          | 10       | 3.24%   |
| ASUS PRIME           | 6        | 1.94%   |
| AAEON MF-001         | 4        | 1.29%   |
| MSI MS-7C37          | 3        | 0.97%   |
| HP t620              | 3        | 0.97%   |
| Dell Precision       | 3        | 0.97%   |
| Dell Inspiron        | 3        | 0.97%   |
| Dell Dimension       | 3        | 0.97%   |
| ASUS V-P8H67E        | 3        | 0.97%   |
| ASUS All             | 3        | 0.97%   |
| ASRock FM2A85X       | 3        | 0.97%   |
| MSI MS-7B89          | 2        | 0.65%   |
| Intel DG31PR         | 2        | 0.65%   |
| HP EliteDesk         | 2        | 0.65%   |
| HP dc5000            | 2        | 0.65%   |
| Gigabyte H81M-DS2    | 2        | 0.65%   |
| Gigabyte B450M       | 2        | 0.65%   |
| Dell Vostro          | 2        | 0.65%   |
| Dell DM061           | 2        | 0.65%   |
| ASRock N68-VS3       | 2        | 0.65%   |
| ASRock B450M         | 2        | 0.65%   |
| ASRock 775Dual-VSTA  | 2        | 0.65%   |
| AMI Z83-V            | 2        | 0.65%   |
| ZOTAC NM10           | 1        | 0.32%   |
| VIA P4X266-8233      | 1        | 0.32%   |
| Qbex HDC-M           | 1        | 0.32%   |
| Positivo POS-MI945AA | 1        | 0.32%   |
| Positivo POS-EIH61CE | 1        | 0.32%   |
| Philco 14F           | 1        | 0.32%   |
| Pegatron WE216AA-ABF | 1        | 0.32%   |
| Pegatron NC689AA-ABA | 1        | 0.32%   |
| Pegatron FQ425AA-ABA | 1        | 0.32%   |
| Pegatron FL308AA-ABD | 1        | 0.32%   |
| Pegatron AY748AA-ABA | 1        | 0.32%   |
| Pegatron AY652AA-ABA | 1        | 0.32%   |
| Pegatron 2AD5        | 1        | 0.32%   |
| PCWare IPX1800G2     | 1        | 0.32%   |
| PCChips A13G         | 1        | 0.32%   |
| Packard Bell IMEDIA  | 1        | 0.32%   |
| MSI MS-7D16          | 1        | 0.32%   |
| MSI MS-7C82          | 1        | 0.32%   |
| MSI MS-7C80          | 1        | 0.32%   |
| MSI MS-7B86          | 1        | 0.32%   |
| MSI MS-7B36          | 1        | 0.32%   |
| MSI MS-7B09          | 1        | 0.32%   |
| MSI MS-7A39          | 1        | 0.32%   |
| MSI MS-7994          | 1        | 0.32%   |
| MSI MS-7846          | 1        | 0.32%   |
| MSI MS-7721          | 1        | 0.32%   |
| MSI MS-7680          | 1        | 0.32%   |
| MSI MS-7641          | 1        | 0.32%   |
| MSI MS-7640          | 1        | 0.32%   |
| MSI MS-7592          | 1        | 0.32%   |
| MSI MS-7581          | 1        | 0.32%   |
| MSI MS-7369          | 1        | 0.32%   |
| MSI MS-7309          | 1        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2011    | 30       | 9.71%   |
| 2007    | 30       | 9.71%   |
| 2009    | 27       | 8.74%   |
| 2012    | 25       | 8.09%   |
| 2008    | 23       | 7.44%   |
| 2013    | 22       | 7.12%   |
| 2017    | 19       | 6.15%   |
| 2010    | 19       | 6.15%   |
| 2006    | 19       | 6.15%   |
| 2014    | 16       | 5.18%   |
| 2005    | 13       | 4.21%   |
| 2020    | 12       | 3.88%   |
| 2019    | 11       | 3.56%   |
| 2015    | 11       | 3.56%   |
| 2018    | 9        | 2.91%   |
| 2021    | 8        | 2.59%   |
| 2016    | 5        | 1.62%   |
| 2004    | 4        | 1.29%   |
| Unknown | 2        | 0.65%   |
| 2022    | 1        | 0.32%   |
| 2003    | 1        | 0.32%   |
| 2001    | 1        | 0.32%   |
| 2000    | 1        | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 309      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 303      | 98.06%  |
| Enabled  | 6        | 1.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 309      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 80       | 25.4%   |
| 4.01-8.0        | 51       | 16.19%  |
| 1.01-2.0        | 45       | 14.29%  |
| 8.01-16.0       | 43       | 13.65%  |
| 16.01-24.0      | 41       | 13.02%  |
| 32.01-64.0      | 17       | 5.4%    |
| 2.01-3.0        | 13       | 4.13%   |
| 0.51-1.0        | 11       | 3.49%   |
| 24.01-32.0      | 5        | 1.59%   |
| 0.01-0.5        | 5        | 1.59%   |
| 64.01-256.0     | 3        | 0.95%   |
| More than 256.0 | 1        | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 139      | 42.38%  |
| 0.51-1.0   | 78       | 23.78%  |
| 2.01-3.0   | 51       | 15.55%  |
| 4.01-8.0   | 25       | 7.62%   |
| 0.01-0.5   | 19       | 5.79%   |
| 3.01-4.0   | 11       | 3.35%   |
| 8.01-16.0  | 3        | 0.91%   |
| 32.01-64.0 | 1        | 0.3%    |
| 16.01-24.0 | 1        | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 172      | 55.13%  |
| 2      | 85       | 27.24%  |
| 4      | 18       | 5.77%   |
| 3      | 17       | 5.45%   |
| 5      | 9        | 2.88%   |
| 0      | 5        | 1.6%    |
| 6      | 2        | 0.64%   |
| 17     | 1        | 0.32%   |
| 14     | 1        | 0.32%   |
| 10     | 1        | 0.32%   |
| 7      | 1        | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 163      | 52.41%  |
| No        | 148      | 47.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 303      | 98.06%  |
| No        | 6        | 1.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 193      | 61.86%  |
| Yes       | 119      | 38.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 263      | 84.84%  |
| Yes       | 47       | 15.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 44       | 14.15%  |
| Brazil                 | 28       | 9%      |
| France                 | 27       | 8.68%   |
| Germany                | 24       | 7.72%   |
| Italy                  | 23       | 7.4%    |
| Russia                 | 17       | 5.47%   |
| Canada                 | 15       | 4.82%   |
| Netherlands            | 9        | 2.89%   |
| UK                     | 8        | 2.57%   |
| Switzerland            | 7        | 2.25%   |
| Spain                  | 7        | 2.25%   |
| Hungary                | 7        | 2.25%   |
| Finland                | 6        | 1.93%   |
| Australia              | 6        | 1.93%   |
| Czechia                | 5        | 1.61%   |
| Poland                 | 4        | 1.29%   |
| Mexico                 | 4        | 1.29%   |
| Japan                  | 4        | 1.29%   |
| Bulgaria               | 4        | 1.29%   |
| Belgium                | 4        | 1.29%   |
| Argentina              | 4        | 1.29%   |
| Turkey                 | 3        | 0.96%   |
| South Africa           | 3        | 0.96%   |
| India                  | 3        | 0.96%   |
| Greece                 | 3        | 0.96%   |
| Colombia               | 3        | 0.96%   |
| Uruguay                | 2        | 0.64%   |
| Slovakia               | 2        | 0.64%   |
| Romania                | 2        | 0.64%   |
| Puerto Rico            | 2        | 0.64%   |
| Peru                   | 2        | 0.64%   |
| New Zealand            | 2        | 0.64%   |
| Malaysia               | 2        | 0.64%   |
| Costa Rica             | 2        | 0.64%   |
| Ukraine                | 1        | 0.32%   |
| Sweden                 | 1        | 0.32%   |
| South Korea            | 1        | 0.32%   |
| Slovenia               | 1        | 0.32%   |
| Singapore              | 1        | 0.32%   |
| Portugal               | 1        | 0.32%   |
| Morocco                | 1        | 0.32%   |
| Luxembourg             | 1        | 0.32%   |
| Latvia                 | 1        | 0.32%   |
| Kenya                  | 1        | 0.32%   |
| Kazakhstan             | 1        | 0.32%   |
| Ireland                | 1        | 0.32%   |
| Iran                   | 1        | 0.32%   |
| Indonesia              | 1        | 0.32%   |
| Hong Kong              | 1        | 0.32%   |
| Guatemala              | 1        | 0.32%   |
| Ecuador                | 1        | 0.32%   |
| Denmark                | 1        | 0.32%   |
| Croatia                | 1        | 0.32%   |
| Chile                  | 1        | 0.32%   |
| Bosnia and Herzegovina | 1        | 0.32%   |
| Belarus                | 1        | 0.32%   |
| Austria                | 1        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Rome              | 5        | 1.56%   |
| Oshawa            | 4        | 1.25%   |
| Milan             | 4        | 1.25%   |
| Melbourne         | 4        | 1.25%   |
| Zurich            | 3        | 0.94%   |
| Wellington        | 3        | 0.94%   |
| Voronezh          | 3        | 0.94%   |
| Tampere           | 3        | 0.94%   |
| Rio de Janeiro    | 3        | 0.94%   |
| Lyon              | 3        | 0.94%   |
| Toronto           | 2        | 0.63%   |
| St Petersburg     | 2        | 0.63%   |
| Sao Paulo         | 2        | 0.63%   |
| Prague            | 2        | 0.63%   |
| Pécs             | 2        | 0.63%   |
| Novo Gama         | 2        | 0.63%   |
| Nitra             | 2        | 0.63%   |
| New York          | 2        | 0.63%   |
| Moscow            | 2        | 0.63%   |
| Mason             | 2        | 0.63%   |
| Largo             | 2        | 0.63%   |
| Kuala Lumpur      | 2        | 0.63%   |
| Istanbul          | 2        | 0.63%   |
| Heredia           | 2        | 0.63%   |
| Hamburg           | 2        | 0.63%   |
| Frankfurt am Main | 2        | 0.63%   |
| Cuernavaca        | 2        | 0.63%   |
| Cayey             | 2        | 0.63%   |
| Cape Town         | 2        | 0.63%   |
| Campinas          | 2        | 0.63%   |
| Budapest          | 2        | 0.63%   |
| Birmingham        | 2        | 0.63%   |
| Bern              | 2        | 0.63%   |
| Atlanta           | 2        | 0.63%   |
| Athens            | 2        | 0.63%   |
| Angri             | 2        | 0.63%   |
| Zwolle            | 1        | 0.31%   |
| Zwevegem          | 1        | 0.31%   |
| Zeuthen           | 1        | 0.31%   |
| Zagreb            | 1        | 0.31%   |
| Yuzhno-Sakhalinsk | 1        | 0.31%   |
| Wraysbury         | 1        | 0.31%   |
| Wolfsburg         | 1        | 0.31%   |
| Winsen            | 1        | 0.31%   |
| Williams Lake     | 1        | 0.31%   |
| Wiesbaden         | 1        | 0.31%   |
| Wetteren          | 1        | 0.31%   |
| West Chester      | 1        | 0.31%   |
| Warsaw            | 1        | 0.31%   |
| Warendorf         | 1        | 0.31%   |
| Wanchai           | 1        | 0.31%   |
| Wakefield         | 1        | 0.31%   |
| Wahroonga         | 1        | 0.31%   |
| Voorschoten       | 1        | 0.31%   |
| Vinhedo           | 1        | 0.31%   |
| Viña del Mar     | 1        | 0.31%   |
| Vilyuchinsk       | 1        | 0.31%   |
| Villejuif         | 1        | 0.31%   |
| Vilabella         | 1        | 0.31%   |
| Vero Beach        | 1        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 109      | 146    | 23.85%  |
| WDC                 | 106      | 151    | 23.19%  |
| Samsung Electronics | 45       | 73     | 9.85%   |
| Hitachi             | 25       | 32     | 5.47%   |
| Kingston            | 23       | 24     | 5.03%   |
| Toshiba             | 19       | 19     | 4.16%   |
| Maxtor              | 15       | 16     | 3.28%   |
| Unknown             | 12       | 15     | 2.63%   |
| SanDisk             | 11       | 12     | 2.41%   |
| Crucial             | 11       | 23     | 2.41%   |
| Intel               | 6        | 6      | 1.31%   |
| HGST                | 6        | 8      | 1.31%   |
| A-DATA Technology   | 6        | 8      | 1.31%   |
| Micron Technology   | 4        | 4      | 0.88%   |
| Intenso             | 4        | 4      | 0.88%   |
| China               | 4        | 4      | 0.88%   |
| TO Exter            | 3        | 3      | 0.66%   |
| Team                | 3        | 3      | 0.66%   |
| SPCC                | 3        | 5      | 0.66%   |
| Silicon Motion      | 2        | 3      | 0.44%   |
| PNY                 | 2        | 2      | 0.44%   |
| Plextor             | 2        | 4      | 0.44%   |
| OCZ                 | 2        | 2      | 0.44%   |
| Lexar               | 2        | 2      | 0.44%   |
| LDLC                | 2        | 2      | 0.44%   |
| JMicron Technology  | 2        | 2      | 0.44%   |
| Fujitsu             | 2        | 2      | 0.44%   |
| Corsair             | 2        | 2      | 0.44%   |
| Verbatim            | 1        | 1      | 0.22%   |
| TSA                 | 1        | 1      | 0.22%   |
| Transcend           | 1        | 1      | 0.22%   |
| Smartbuy            | 1        | 1      | 0.22%   |
| ShiJi               | 1        | 1      | 0.22%   |
| PNY USB             | 1        | 1      | 0.22%   |
| Patriot             | 1        | 1      | 0.22%   |
| ORTIAL              | 1        | 1      | 0.22%   |
| Mushkin             | 1        | 1      | 0.22%   |
| MaxDigital          | 1        | 1      | 0.22%   |
| Londisk             | 1        | 1      | 0.22%   |
| LITEONIT            | 1        | 1      | 0.22%   |
| Leven               | 1        | 2      | 0.22%   |
| Kston               | 1        | 3      | 0.22%   |
| KLEVV               | 1        | 1      | 0.22%   |
| KingFast            | 1        | 1      | 0.22%   |
| HS-SSD-E100         | 1        | 1      | 0.22%   |
| Hikvision           | 1        | 1      | 0.22%   |
| Hewlett-Packard     | 1        | 6      | 0.22%   |
| GOODRAM             | 1        | 1      | 0.22%   |
| FORESEE             | 1        | 1      | 0.22%   |
| External            | 1        | 1      | 0.22%   |
| ASMT                | 1        | 1      | 0.22%   |
| Apricorn            | 1        | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 7        | 1.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 5        | 0.97%   |
| Seagate ST3500418AS 500GB           | 5        | 0.97%   |
| Kingston SA400S37240G 240GB SSD     | 5        | 0.97%   |
| Seagate ST2000DM008-2FR102 2TB      | 4        | 0.78%   |
| Samsung SSD 850 EVO 500GB           | 4        | 0.78%   |
| Kingston SA400S37120G 120GB SSD     | 4        | 0.78%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 3        | 0.58%   |
| Unknown M52516  16GB                | 3        | 0.58%   |
| TO Exter nal USB 3.0 1TB            | 3        | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB      | 3        | 0.58%   |
| Seagate ST3500312CS 500GB           | 3        | 0.58%   |
| Seagate ST3250410AS 250GB           | 3        | 0.58%   |
| Seagate ST3250310AS 250GB           | 3        | 0.58%   |
| Seagate ST3160318AS 160GB           | 3        | 0.58%   |
| Seagate ST31000528AS 1TB            | 3        | 0.58%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 0.58%   |
| Seagate ST2000DM001-1CH164 2TB      | 3        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB      | 3        | 0.58%   |
| Seagate ST1000DM003-9YN162 1TB      | 3        | 0.58%   |
| Seagate Expansion 1TB               | 3        | 0.58%   |
| Samsung HD502IJ 500GB               | 3        | 0.58%   |
| Samsung HD322HJ 320GB               | 3        | 0.58%   |
| Samsung HD161HJ 160GB               | 3        | 0.58%   |
| Samsung HD103SJ 1TB                 | 3        | 0.58%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 0.58%   |
| Crucial CT1000BX500SSD1 1TB         | 3        | 0.58%   |
| A-DATA SU650 240GB SSD              | 3        | 0.58%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.39%   |
| WDC WD800JD-60LSA5 80GB             | 2        | 0.39%   |
| WDC WD7500BPVX-55JC3T3 752GB        | 2        | 0.39%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 2        | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 0.39%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.39%   |
| WDC WD400BB-60DGA0 40GB             | 2        | 0.39%   |
| WDC WD3200AAJS-60Z0A0 320GB         | 2        | 0.39%   |
| WDC WD2500JS-75NCB3 250GB           | 2        | 0.39%   |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 0.39%   |
| WDC WD20EARX-00PASB0 2TB            | 2        | 0.39%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 0.39%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.39%   |
| WDC WD10EARX-00N0YB0 1TB            | 2        | 0.39%   |
| WDC WD10EADS-00L5B1 1TB             | 2        | 0.39%   |
| Unknown SD/MMC/MS PRO 64GB          | 2        | 0.39%   |
| Unknown MMC Card  32GB              | 2        | 0.39%   |
| Toshiba DT01ACA100 1TB              | 2        | 0.39%   |
| Toshiba DT01ACA050 500GB            | 2        | 0.39%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2        | 0.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.39%   |
| Seagate ST380815AS 80GB             | 2        | 0.39%   |
| Seagate ST380013AS 80GB             | 2        | 0.39%   |
| Seagate ST380011A 80GB              | 2        | 0.39%   |
| Seagate ST3360320AS 360GB           | 2        | 0.39%   |
| Seagate ST3320620AS 320GB           | 2        | 0.39%   |
| Seagate ST3250318AS 250GB           | 2        | 0.39%   |
| Seagate ST3200826AS 200GB           | 2        | 0.39%   |
| Seagate ST3160023AS 160GB           | 2        | 0.39%   |
| Seagate ST3120213AS 120GB           | 2        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 109      | 145    | 36.33%  |
| WDC                 | 97       | 137    | 32.33%  |
| Samsung Electronics | 28       | 37     | 9.33%   |
| Hitachi             | 25       | 32     | 8.33%   |
| Toshiba             | 16       | 16     | 5.33%   |
| Maxtor              | 14       | 15     | 4.67%   |
| HGST                | 6        | 8      | 2%      |
| Unknown             | 2        | 2      | 0.67%   |
| Fujitsu             | 2        | 2      | 0.67%   |
| Apricorn            | 1        | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 22       | 23     | 16.67%  |
| Samsung Electronics | 15       | 20     | 11.36%  |
| WDC                 | 11       | 13     | 8.33%   |
| Crucial             | 11       | 23     | 8.33%   |
| SanDisk             | 9        | 10     | 6.82%   |
| Intel               | 5        | 5      | 3.79%   |
| A-DATA Technology   | 5        | 7      | 3.79%   |
| Micron Technology   | 4        | 4      | 3.03%   |
| Intenso             | 4        | 4      | 3.03%   |
| China               | 4        | 4      | 3.03%   |
| Toshiba             | 3        | 3      | 2.27%   |
| TO Exter            | 3        | 3      | 2.27%   |
| Team                | 3        | 3      | 2.27%   |
| PNY                 | 2        | 2      | 1.52%   |
| Plextor             | 2        | 4      | 1.52%   |
| OCZ                 | 2        | 2      | 1.52%   |
| Lexar               | 2        | 2      | 1.52%   |
| Corsair             | 2        | 2      | 1.52%   |
| Verbatim            | 1        | 1      | 0.76%   |
| Unknown             | 1        | 1      | 0.76%   |
| TSA                 | 1        | 1      | 0.76%   |
| Transcend           | 1        | 1      | 0.76%   |
| SPCC                | 1        | 1      | 0.76%   |
| Smartbuy            | 1        | 1      | 0.76%   |
| PNY USB             | 1        | 1      | 0.76%   |
| Patriot             | 1        | 1      | 0.76%   |
| ORTIAL              | 1        | 1      | 0.76%   |
| Mushkin             | 1        | 1      | 0.76%   |
| Maxtor              | 1        | 1      | 0.76%   |
| Londisk             | 1        | 1      | 0.76%   |
| LITEONIT            | 1        | 1      | 0.76%   |
| Leven               | 1        | 2      | 0.76%   |
| LDLC                | 1        | 1      | 0.76%   |
| Kston               | 1        | 3      | 0.76%   |
| KLEVV               | 1        | 1      | 0.76%   |
| HS-SSD-E100         | 1        | 1      | 0.76%   |
| Hikvision           | 1        | 1      | 0.76%   |
| Hewlett-Packard     | 1        | 6      | 0.76%   |
| GOODRAM             | 1        | 1      | 0.76%   |
| FORESEE             | 1        | 1      | 0.76%   |
| ASMT                | 1        | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 231      | 395    | 60.31%  |
| SSD     | 121      | 165    | 31.59%  |
| NVMe    | 18       | 33     | 4.7%    |
| MMC     | 9        | 10     | 2.35%   |
| Unknown | 4        | 6      | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 290      | 543    | 87.35%  |
| SAS  | 17       | 25     | 5.12%   |
| NVMe | 16       | 31     | 4.82%   |
| MMC  | 9        | 10     | 2.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 245      | 366    | 66.4%   |
| 0.51-1.0   | 77       | 125    | 20.87%  |
| 1.01-2.0   | 25       | 32     | 6.78%   |
| 3.01-4.0   | 13       | 27     | 3.52%   |
| 2.01-3.0   | 7        | 7      | 1.9%    |
| 4.01-10.0  | 2        | 3      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 97       | 31.19%  |
| 251-500        | 61       | 19.61%  |
| 501-1000       | 33       | 10.61%  |
| 51-100         | 26       | 8.36%   |
| More than 3000 | 21       | 6.75%   |
| 1001-2000      | 21       | 6.75%   |
| 1-20           | 20       | 6.43%   |
| 21-50          | 15       | 4.82%   |
| 2001-3000      | 15       | 4.82%   |
| Unknown        | 2        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 142      | 44.1%   |
| 21-50          | 56       | 17.39%  |
| 101-250        | 36       | 11.18%  |
| 51-100         | 23       | 7.14%   |
| 251-500        | 17       | 5.28%   |
| 501-1000       | 17       | 5.28%   |
| 1001-2000      | 15       | 4.66%   |
| More than 3000 | 8        | 2.48%   |
| 2001-3000      | 6        | 1.86%   |
| Unknown        | 2        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB    | 3        | 3      | 6.67%   |
| WDC WD5000AAKX-003CA0 500GB       | 1        | 1      | 2.22%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 1      | 2.22%   |
| WDC WD400EB-00CPF0 40GB           | 1        | 1      | 2.22%   |
| WDC WD2500HHTZ-04N21V0 250GB      | 1        | 1      | 2.22%   |
| WDC WD2500AAJS-75M0A0 250GB       | 1        | 1      | 2.22%   |
| WDC WD1600AAJS-60B4A0 160GB       | 1        | 2      | 2.22%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 2.22%   |
| WDC WD10EADS-65M2B0 1TB           | 1        | 1      | 2.22%   |
| Toshiba MK6465GSX 640GB           | 1        | 1      | 2.22%   |
| Seagate ST9500420AS 500GB         | 1        | 1      | 2.22%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 2.22%   |
| Seagate ST9250315AS 250GB         | 1        | 1      | 2.22%   |
| Seagate ST9160310AS 160GB         | 1        | 1      | 2.22%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 2.22%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1      | 2.22%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 2.22%   |
| Seagate ST380011A 80GB            | 1        | 1      | 2.22%   |
| Seagate ST360012A 64GB            | 1        | 1      | 2.22%   |
| Seagate ST3360320AS 360GB         | 1        | 1      | 2.22%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 2.22%   |
| Seagate ST3160318AS 160GB         | 1        | 1      | 2.22%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 2.22%   |
| Seagate ST1000DX001-1CM162 1TB    | 1        | 1      | 2.22%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 1      | 2.22%   |
| SanDisk SSD PLUS 120GB            | 1        | 1      | 2.22%   |
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 2.22%   |
| Samsung Electronics HD253GJ 250GB | 1        | 1      | 2.22%   |
| Mushkin MKNSSDCR60GB-7 64GB       | 1        | 1      | 2.22%   |
| Maxtor STM3300622A 304GB          | 1        | 1      | 2.22%   |
| Maxtor 6Y080L0 82GB               | 1        | 1      | 2.22%   |
| Maxtor 6B200M0 208GB              | 1        | 1      | 2.22%   |
| LDLC SSD 120GB                    | 1        | 1      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 2.22%   |
| Kingston SHFS37A120G 120GB SSD    | 1        | 1      | 2.22%   |
| Kingston SA400S37240G 240GB SSD   | 1        | 1      | 2.22%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 2.22%   |
| Intel SSDSA1M160G2HP 160GB        | 1        | 1      | 2.22%   |
| Hitachi HTS722080K9A300 80GB      | 1        | 1      | 2.22%   |
| Hitachi HDS721075CLA332 752GB     | 1        | 1      | 2.22%   |
| Hitachi HDP725050GLA360 500GB     | 1        | 1      | 2.22%   |
| Hitachi HCP725050GLAT80 500GB     | 1        | 1      | 2.22%   |
| Fujitsu MHZ2160BH G2 160GB        | 1        | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 39.53%  |
| WDC                 | 8        | 9      | 18.6%   |
| Kingston            | 4        | 4      | 9.3%    |
| Maxtor              | 3        | 3      | 6.98%   |
| Hitachi             | 3        | 4      | 6.98%   |
| Samsung Electronics | 2        | 2      | 4.65%   |
| Toshiba             | 1        | 1      | 2.33%   |
| SanDisk             | 1        | 1      | 2.33%   |
| Mushkin             | 1        | 1      | 2.33%   |
| LDLC                | 1        | 1      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| Fujitsu             | 1        | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 48.57%  |
| WDC                 | 8        | 9      | 22.86%  |
| Maxtor              | 3        | 3      | 8.57%   |
| Hitachi             | 3        | 4      | 8.57%   |
| Samsung Electronics | 2        | 2      | 5.71%   |
| Toshiba             | 1        | 1      | 2.86%   |
| Fujitsu             | 1        | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 38     | 80%     |
| SSD  | 8        | 8      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD080HJ/ 80GB | 1        | 1      | 50%     |
| Intel SSDSA1M160G2HP 160GB        | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 50%     |
| Intel               | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 173      | 323    | 51.64%  |
| Works    | 123      | 238    | 36.72%  |
| Malfunc  | 37       | 46     | 11.04%  |
| Failed   | 2        | 2      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 184      | 52.12%  |
| AMD                              | 68       | 19.26%  |
| Nvidia                           | 36       | 10.2%   |
| JMicron Technology               | 14       | 3.97%   |
| Marvell Technology Group         | 11       | 3.12%   |
| VIA Technologies                 | 8        | 2.27%   |
| ASMedia Technology               | 7        | 1.98%   |
| Silicon Motion                   | 5        | 1.42%   |
| Samsung Electronics              | 5        | 1.42%   |
| ULi Electronics                  | 2        | 0.57%   |
| Silicon Image                    | 2        | 0.57%   |
| SanDisk                          | 2        | 0.57%   |
| LSI Logic / Symbios Logic        | 2        | 0.57%   |
| Silicon Integrated Systems [SiS] | 1        | 0.28%   |
| Seagate Technology               | 1        | 0.28%   |
| Phison Electronics               | 1        | 0.28%   |
| Kingston Technology Company      | 1        | 0.28%   |
| Broadcom                         | 1        | 0.28%   |
| ADATA Technology                 | 1        | 0.28%   |
| Adaptec                          | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 37       | 7.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28       | 5.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 3.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16       | 3.19%   |
| Nvidia MCP61 SATA Controller                                                            | 15       | 2.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 2.59%   |
| Nvidia MCP61 IDE                                                                        | 12       | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 2.2%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 10       | 2%      |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 10       | 2%      |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 8        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 1.6%    |
| Nvidia CK804 Serial ATA Controller                                                      | 7        | 1.4%    |
| Nvidia CK804 IDE                                                                        | 7        | 1.4%    |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.4%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 1.4%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7        | 1.4%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 1.2%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 1.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 1%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 1%      |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1%      |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 1%      |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 5        | 1%      |
| AMD SB600 Non-Raid-5 SATA                                                               | 5        | 1%      |
| AMD SB600 IDE                                                                           | 5        | 1%      |
| AMD FCH SATA Controller D                                                               | 5        | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 0.8%    |
| Nvidia MCP73 IDE Controller                                                             | 4        | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4        | 0.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.8%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 4        | 0.8%    |
| Intel 82801EB (ICH5) SATA Controller                                                    | 4        | 0.8%    |
| AMD FCH IDE Controller                                                                  | 4        | 0.8%    |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 0.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.6%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.6%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 0.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 0.6%    |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.6%    |
| VIA VT8237A SATA 2-Port Controller                                                      | 2        | 0.4%    |
| ULi M5229 IDE                                                                           | 2        | 0.4%    |
| Nvidia nForce3 Serial ATA Controller                                                    | 2        | 0.4%    |
| Nvidia MCP55 SATA Controller                                                            | 2        | 0.4%    |
| Nvidia MCP55 IDE                                                                        | 2        | 0.4%    |
| Nvidia MCP51 Serial ATA Controller                                                      | 2        | 0.4%    |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 2        | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 175      | 47.43%  |
| IDE  | 157      | 42.55%  |
| RAID | 17       | 4.61%   |
| NVMe | 16       | 4.34%   |
| SCSI | 3        | 0.81%   |
| SAS  | 1        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Intel       | 205      | 66.34%  |
| AMD         | 103      | 33.33%  |
| PowerMac7,2 | 1        | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 6        | 1.94%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 5        | 1.62%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 5        | 1.62%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 1.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 1.62%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 5        | 1.62%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 1.62%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 5        | 1.62%   |
| Intel Pentium 4 CPU 2.80GHz                 | 4        | 1.29%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.29%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.29%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 1.29%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.29%   |
| AMD Athlon II X2 250 Processor              | 4        | 1.29%   |
| AMD Athlon 64 Processor 3000+               | 4        | 1.29%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 3        | 0.97%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 3        | 0.97%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.97%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 0.97%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 3        | 0.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.97%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 0.97%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.97%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 0.97%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 3        | 0.97%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 0.97%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 0.97%   |
| AMD Athlon II X2 215 Processor              | 3        | 0.97%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 3        | 0.97%   |
| AMD Athlon 64 X2 Dual Core Processor 4000+  | 3        | 0.97%   |
| AMD A10-6800K APU with Radeon HD Graphics   | 3        | 0.97%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 2        | 0.65%   |
| Intel Pentium D CPU 2.80GHz                 | 2        | 0.65%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 0.65%   |
| Intel Pentium 4 CPU 3.40GHz                 | 2        | 0.65%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.65%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.65%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 0.65%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.65%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 2        | 0.65%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 0.65%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 0.65%   |
| Intel Celeron CPU 2.66GHz                   | 2        | 0.65%   |
| Intel Atom CPU D525 @ 1.80GHz               | 2        | 0.65%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 0.65%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.65%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 0.65%   |
| AMD Phenom II X4 965 Processor              | 2        | 0.65%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 2        | 0.65%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 0.65%   |
| AMD FX-6300 Six-Core Processor              | 2        | 0.65%   |
| AMD Athlon 64 X2 Dual Core Processor 6000+  | 2        | 0.65%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 0.65%   |
| AMD Athlon 64 Processor 3500+               | 2        | 0.65%   |
| AMD Athlon 64 Processor 3200+               | 2        | 0.65%   |
| PowerMac7,2 PPC970, altivec supported       | 1        | 0.32%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.32%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.32%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz          | 1        | 0.32%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 0.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 43       | 13.92%  |
| Intel Core 2 Duo        | 22       | 7.12%   |
| Intel Core i7           | 21       | 6.8%    |
| Intel Core i3           | 19       | 6.15%   |
| AMD Athlon 64 X2        | 17       | 5.5%    |
| Intel Celeron           | 16       | 5.18%   |
| Intel Atom              | 14       | 4.53%   |
| Intel Pentium 4         | 13       | 4.21%   |
| Intel Xeon              | 10       | 3.24%   |
| Intel Pentium Dual-Core | 10       | 3.24%   |
| AMD Ryzen 5             | 10       | 3.24%   |
| AMD Athlon II X2        | 10       | 3.24%   |
| Intel Core 2 Quad       | 9        | 2.91%   |
| Intel Pentium Dual      | 8        | 2.59%   |
| Intel Core 2            | 8        | 2.59%   |
| AMD Ryzen 7             | 8        | 2.59%   |
| AMD Athlon 64           | 8        | 2.59%   |
| AMD FX                  | 6        | 1.94%   |
| AMD A10                 | 6        | 1.94%   |
| Intel Pentium D         | 4        | 1.29%   |
| Intel Pentium           | 4        | 1.29%   |
| AMD Ryzen 3             | 4        | 1.29%   |
| AMD Phenom II X4        | 4        | 1.29%   |
| AMD GX                  | 3        | 0.97%   |
| AMD E1                  | 3        | 0.97%   |
| AMD E                   | 3        | 0.97%   |
| AMD Sempron             | 2        | 0.65%   |
| AMD Ryzen Threadripper  | 2        | 0.65%   |
| AMD Athlon X4           | 2        | 0.65%   |
| AMD A8                  | 2        | 0.65%   |
| Other                   | 1        | 0.32%   |
| Intel Pentium III       | 1        | 0.32%   |
| Intel Pentium Gold      | 1        | 0.32%   |
| Intel Genuine           | 1        | 0.32%   |
| Intel Core i9           | 1        | 0.32%   |
| AMD Ryzen 9             | 1        | 0.32%   |
| AMD Quad-Core Opteron   | 1        | 0.32%   |
| AMD Phenom II X3        | 1        | 0.32%   |
| AMD Phenom              | 1        | 0.32%   |
| AMD Opteron             | 1        | 0.32%   |
| AMD C-70                | 1        | 0.32%   |
| AMD C-50                | 1        | 0.32%   |
| AMD Athlon X2           | 1        | 0.32%   |
| AMD Athlon II X4        | 1        | 0.32%   |
| AMD Athlon II X3        | 1        | 0.32%   |
| AMD Athlon              | 1        | 0.32%   |
| AMD A4                  | 1        | 0.32%   |
| AMD A12                 | 1        | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 138      | 44.66%  |
| 4      | 100      | 32.36%  |
| 1      | 36       | 11.65%  |
| 6      | 14       | 4.53%   |
| 8      | 11       | 3.56%   |
| 3      | 5        | 1.62%   |
| 12     | 2        | 0.65%   |
| 64     | 1        | 0.32%   |
| 16     | 1        | 0.32%   |
| 10     | 1        | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 306      | 99.03%  |
| 2      | 3        | 0.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 203      | 65.7%   |
| 2      | 105      | 33.98%  |
| 8      | 1        | 0.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 299      | 96.76%  |
| 32-bit         | 8        | 2.59%   |
| Unknown        | 2        | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 82       | 26.45%  |
| 0x206a7    | 20       | 6.45%   |
| 0x1067a    | 20       | 6.45%   |
| 0x306c3    | 15       | 4.84%   |
| 0x306a9    | 12       | 3.87%   |
| 0x6fd      | 9        | 2.9%    |
| 0x6fb      | 8        | 2.58%   |
| 0x06001119 | 7        | 2.26%   |
| 0x406c4    | 6        | 1.94%   |
| 0x010000c8 | 6        | 1.94%   |
| 0x6f2      | 5        | 1.61%   |
| 0x30678    | 5        | 1.61%   |
| 0x08701021 | 5        | 1.61%   |
| 0x06000852 | 5        | 1.61%   |
| 0xf41      | 4        | 1.29%   |
| 0x906e9    | 4        | 1.29%   |
| 0x20655    | 4        | 1.29%   |
| 0x10676    | 4        | 1.29%   |
| 0x0700010f | 4        | 1.29%   |
| 0xf65      | 3        | 0.97%   |
| 0xf49      | 3        | 0.97%   |
| 0xa0653    | 3        | 0.97%   |
| 0x6f6      | 3        | 0.97%   |
| 0x206d7    | 3        | 0.97%   |
| 0x106ca    | 3        | 0.97%   |
| 0x0800820d | 3        | 0.97%   |
| 0x05000119 | 3        | 0.97%   |
| 0x010000db | 3        | 0.97%   |
| 0x010000c7 | 3        | 0.97%   |
| 0xf43      | 2        | 0.65%   |
| 0xf29      | 2        | 0.65%   |
| 0xa0655    | 2        | 0.65%   |
| 0x906ea    | 2        | 0.65%   |
| 0x706a8    | 2        | 0.65%   |
| 0x506e3    | 2        | 0.65%   |
| 0x306f2    | 2        | 0.65%   |
| 0x0a50000c | 2        | 0.65%   |
| 0x0a201009 | 2        | 0.65%   |
| 0x08701013 | 2        | 0.65%   |
| 0x06003106 | 2        | 0.65%   |
| 0x05000029 | 2        | 0.65%   |
| 0xf64      | 1        | 0.32%   |
| 0xf4a      | 1        | 0.32%   |
| 0xf34      | 1        | 0.32%   |
| 0xf33      | 1        | 0.32%   |
| 0xf12      | 1        | 0.32%   |
| 0x906eb    | 1        | 0.32%   |
| 0x806ea    | 1        | 0.32%   |
| 0x706a1    | 1        | 0.32%   |
| 0x6f7      | 1        | 0.32%   |
| 0x681      | 1        | 0.32%   |
| 0x406c3    | 1        | 0.32%   |
| 0x40651    | 1        | 0.32%   |
| 0x306e4    | 1        | 0.32%   |
| 0x30661    | 1        | 0.32%   |
| 0x206c2    | 1        | 0.32%   |
| 0x106e5    | 1        | 0.32%   |
| 0x106c2    | 1        | 0.32%   |
| 0x106a5    | 1        | 0.32%   |
| 0x106a4    | 1        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 29       | 9.39%   |
| Core          | 29       | 9.39%   |
| K8 Hammer     | 28       | 9.06%   |
| SandyBridge   | 27       | 8.74%   |
| Haswell       | 25       | 8.09%   |
| NetBurst      | 21       | 6.8%    |
| K10           | 21       | 6.8%    |
| IvyBridge     | 20       | 6.47%   |
| Silvermont    | 13       | 4.21%   |
| Piledriver    | 13       | 4.21%   |
| Zen 2         | 10       | 3.24%   |
| Zen+          | 9        | 2.91%   |
| KabyLake      | 8        | 2.59%   |
| Westmere      | 7        | 2.27%   |
| CometLake     | 7        | 2.27%   |
| Bonnell       | 6        | 1.94%   |
| Bobcat        | 6        | 1.94%   |
| Skylake       | 5        | 1.62%   |
| Jaguar        | 5        | 1.62%   |
| Zen 3         | 4        | 1.29%   |
| Nehalem       | 4        | 1.29%   |
| Goldmont plus | 3        | 0.97%   |
| Zen           | 2        | 0.65%   |
| Steamroller   | 2        | 0.65%   |
| Excavator     | 2        | 0.65%   |
| P6            | 1        | 0.32%   |
| K10 Llano     | 1        | 0.32%   |
| Unknown       | 1        | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 111      | 34.47%  |
| Intel                            | 106      | 32.92%  |
| AMD                              | 100      | 31.06%  |
| VIA Technologies                 | 3        | 0.93%   |
| Silicon Integrated Systems [SiS] | 1        | 0.31%   |
| Matrox Electronics Systems       | 1        | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15       | 4.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9        | 2.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9        | 2.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 8        | 2.36%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 8        | 2.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 2.36%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7        | 2.06%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7        | 2.06%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7        | 2.06%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7        | 2.06%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6        | 1.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 1.47%   |
| Intel 82865G Integrated Graphics Controller                                              | 5        | 1.47%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 5        | 1.47%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 1.47%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 4        | 1.18%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.18%   |
| Intel HD Graphics 530                                                                    | 4        | 1.18%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4        | 1.18%   |
| AMD RS780L [Radeon 3000]                                                                 | 4        | 1.18%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4        | 1.18%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 3        | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.88%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 3        | 0.88%   |
| AMD RV370 [Radeon X300]                                                                  | 3        | 0.88%   |
| AMD RV370 [Radeon X300 SE]                                                               | 3        | 0.88%   |
| AMD RS690 [Radeon X1200]                                                                 | 3        | 0.88%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 3        | 0.88%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]            | 2        | 0.59%   |
| Nvidia NV44A [GeForce 6200]                                                              | 2        | 0.59%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.59%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2        | 0.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 0.59%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2        | 0.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.59%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 0.59%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 2        | 0.59%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 0.59%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 2        | 0.59%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 2        | 0.59%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 2        | 0.59%   |
| Nvidia C73 [GeForce 7100 / nForce 620i]                                                  | 2        | 0.59%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2        | 0.59%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 0.59%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.59%   |
| Intel 82G965 Integrated Graphics Controller                                              | 2        | 0.59%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2        | 0.59%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.59%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 0.59%   |
| AMD RV770 [Radeon HD 4850]                                                               | 2        | 0.59%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                                       | 2        | 0.59%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 2        | 0.59%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 0.59%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 0.59%   |
| AMD RV350 [Radeon 9550/9600/X1050 Series]                                                | 2        | 0.59%   |
| AMD RV280 [Radeon 9200 SE] (Secondary)                                                   | 2        | 0.59%   |
| AMD RV280 [Radeon 9200 SE]                                                               | 2        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 103      | 33.12%  |
| 1 x Intel    | 101      | 32.48%  |
| 1 x AMD      | 83       | 26.69%  |
| 2 x AMD      | 14       | 4.5%    |
| 1 x VIA      | 3        | 0.96%   |
| AMD + Nvidia | 3        | 0.96%   |
| 2 x Nvidia   | 2        | 0.64%   |
| 1 x SiS      | 1        | 0.32%   |
| 1 x Matrox   | 1        | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 250      | 80.13%  |
| Proprietary | 45       | 14.42%  |
| Unknown     | 17       | 5.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 125      | 40.06%  |
| 0.01-0.5   | 86       | 27.56%  |
| 0.51-1.0   | 40       | 12.82%  |
| 1.01-2.0   | 33       | 10.58%  |
| 3.01-4.0   | 13       | 4.17%   |
| 7.01-8.0   | 7        | 2.24%   |
| 2.01-3.0   | 3        | 0.96%   |
| 8.01-16.0  | 3        | 0.96%   |
| 5.01-6.0   | 2        | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 54       | 18.49%  |
| Dell                    | 34       | 11.64%  |
| Goldstar                | 25       | 8.56%   |
| Hewlett-Packard         | 21       | 7.19%   |
| Acer                    | 20       | 6.85%   |
| AOC                     | 14       | 4.79%   |
| BenQ                    | 13       | 4.45%   |
| Philips                 | 12       | 4.11%   |
| Ancor Communications    | 12       | 4.11%   |
| Lenovo                  | 7        | 2.4%    |
| Vizio                   | 6        | 2.05%   |
| Unknown                 | 6        | 2.05%   |
| Iiyama                  | 6        | 2.05%   |
| Sony                    | 3        | 1.03%   |
| NEC Computers           | 3        | 1.03%   |
| LG Electronics          | 3        | 1.03%   |
| ___                     | 2        | 0.68%   |
| Sceptre Tech            | 2        | 0.68%   |
| Positivo                | 2        | 0.68%   |
| Plain Tree Systems      | 2        | 0.68%   |
| LG Display              | 2        | 0.68%   |
| IOD                     | 2        | 0.68%   |
| Fujitsu Siemens         | 2        | 0.68%   |
| FL_                     | 2        | 0.68%   |
| Elo Touch               | 2        | 0.68%   |
| Eizo                    | 2        | 0.68%   |
| ViewSonic               | 1        | 0.34%   |
| Videoseven              | 1        | 0.34%   |
| Vestel                  | 1        | 0.34%   |
| Unknown (ADA)           | 1        | 0.34%   |
| Toshiba                 | 1        | 0.34%   |
| STD                     | 1        | 0.34%   |
| SHD                     | 1        | 0.34%   |
| Proview                 | 1        | 0.34%   |
| Pioneer                 | 1        | 0.34%   |
| Panasonic               | 1        | 0.34%   |
| MSI                     | 1        | 0.34%   |
| MOT                     | 1        | 0.34%   |
| Lite-On                 | 1        | 0.34%   |
| Lenovo Group Limited    | 1        | 0.34%   |
| InfoVision              | 1        | 0.34%   |
| IBM                     | 1        | 0.34%   |
| HVR                     | 1        | 0.34%   |
| HPN                     | 1        | 0.34%   |
| Hitachi                 | 1        | 0.34%   |
| HannStar Display        | 1        | 0.34%   |
| HannStar                | 1        | 0.34%   |
| Gigabyte Technology     | 1        | 0.34%   |
| GDH                     | 1        | 0.34%   |
| Gateway                 | 1        | 0.34%   |
| Element                 | 1        | 0.34%   |
| DPL                     | 1        | 0.34%   |
| CVT                     | 1        | 0.34%   |
| Compaq Computer         | 1        | 0.34%   |
| Chi Mei Optoelectronics | 1        | 0.34%   |
| BLS                     | 1        | 0.34%   |
| ASUSTek Computer        | 1        | 0.34%   |
| Arnos Instruments       | 1        | 0.34%   |
| Apple                   | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 3        | 1%      |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 3        | 1%      |
| ___ LCD TV ___0101 1360x768                                           | 2        | 0.67%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                    | 2        | 0.67%   |
| Samsung Electronics SyncMaster SAM0119 1280x1024 352x264mm 17.3-inch  | 2        | 0.67%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 0.67%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.67%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 0.67%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 470x300mm 22.0-inch          | 2        | 0.67%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch             | 2        | 0.67%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2        | 0.67%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2        | 0.67%   |
| Elo Touch elotouch.com ELO1925 1280x1024 376x301mm 19.0-inch          | 2        | 0.67%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 0.67%   |
| Dell ST2410 DELA05D 1920x1080 531x299mm 24.0-inch                     | 2        | 0.67%   |
| Dell P190S DEL405A 1280x1024 376x301mm 19.0-inch                      | 2        | 0.67%   |
| Dell LCD Monitor DELA102 1920x1080 540x300mm 24.3-inch                | 2        | 0.67%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                     | 2        | 0.67%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 2        | 0.67%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 2        | 0.67%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                        | 2        | 0.67%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2        | 0.67%   |
| Acer AL1716 ACR06B4 1280x1024 338x271mm 17.1-inch                     | 2        | 0.67%   |
| ___ LCD TV ___9000 1360x768                                           | 1        | 0.33%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.33%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1        | 0.33%   |
| Vizio E371VL VIZ0090 1920x1080 820x460mm 37.0-inch                    | 1        | 0.33%   |
| Vizio D32h-F0 VIZ1028 1366x768 700x390mm 31.5-inch                    | 1        | 0.33%   |
| ViewSonic VX2035wm VSCAF1E 1680x1050 433x271mm 20.1-inch              | 1        | 0.33%   |
| Videoseven L19FM IGM0812 1280x1024 376x301mm 19.0-inch                | 1        | 0.33%   |
| Vestel LCD Monitor 49UHD_LCD_TV 3840x2160                             | 1        | 0.33%   |
| Unknown MYTV LED TV 0101 1360x768 1600x900mm 72.3-inch                | 1        | 0.33%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 1        | 0.33%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.33%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B1925S1W 1440x900                 | 1        | 0.33%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1        | 0.33%   |
| Unknown LCD Monitor DELL3007WFPHC 1280x800                            | 1        | 0.33%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                            | 1        | 0.33%   |
| Unknown LCD Monitor 2160 1920x1080 360x270mm 17.7-inch                | 1        | 0.33%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.33%   |
| Toshiba 32W_LCD_TV TSB3700 1920x1080 710x400mm 32.1-inch              | 1        | 0.33%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 1        | 0.33%   |
| Sony TV SNYAA01 1360x768                                              | 1        | 0.33%   |
| Sony TV SNY4803 1920x1080 1107x623mm 50.0-inch                        | 1        | 0.33%   |
| Sony SDM-S53 SNY2450 1024x768 304x228mm 15.0-inch                     | 1        | 0.33%   |
| SHD 701Lite SHD02BD 1920x1080 110x62mm 5.0-inch                       | 1        | 0.33%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1        | 0.33%   |
| Sceptre Tech E325BV-HDH SPT0C84 1360x768 700x390mm 31.5-inch          | 1        | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.33%   |
| Samsung Electronics T24C350 SAM0ABF 1920x1080 530x300mm 24.0-inch     | 1        | 0.33%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch     | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM058C 1600x900 443x249mm 20.0-inch   | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM04DD 1920x1080 477x268mm 21.5-inch  | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0427 1920x1200                      | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM03E1 1440x900 410x257mm 19.1-inch   | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch  | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM030C 1680x1050 474x296mm 22.0-inch  | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch   | 1        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 100      | 34.13%  |
| 1280x1024 (SXGA)   | 53       | 18.09%  |
| 1680x1050 (WSXGA+) | 26       | 8.87%   |
| 1366x768 (WXGA)    | 21       | 7.17%   |
| 1440x900 (WXGA+)   | 15       | 5.12%   |
| 2560x1440 (QHD)    | 14       | 4.78%   |
| 1600x900 (HD+)     | 14       | 4.78%   |
| 1024x768 (XGA)     | 9        | 3.07%   |
| 3840x2160 (4K)     | 7        | 2.39%   |
| 1920x1200 (WUXGA)  | 6        | 2.05%   |
| 1360x768           | 5        | 1.71%   |
| Unknown            | 3        | 1.02%   |
| 3600x1200          | 2        | 0.68%   |
| 3440x1440          | 2        | 0.68%   |
| 2560x1080          | 2        | 0.68%   |
| 2288x1287          | 2        | 0.68%   |
| 2048x1536          | 2        | 0.68%   |
| 1280x800 (WXGA)    | 2        | 0.68%   |
| 1280x720 (HD)      | 2        | 0.68%   |
| 5760x2160          | 1        | 0.34%   |
| 2560x1600          | 1        | 0.34%   |
| 2160x1200          | 1        | 0.34%   |
| 1600x1200          | 1        | 0.34%   |
| 1280x768           | 1        | 0.34%   |
| 1152x864           | 1        | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 34       | 11.64%  |
| 24      | 33       | 11.3%   |
| 19      | 32       | 10.96%  |
| 23      | 25       | 8.56%   |
| 21      | 25       | 8.56%   |
| Unknown | 24       | 8.22%   |
| 20      | 20       | 6.85%   |
| 27      | 17       | 5.82%   |
| 22      | 17       | 5.82%   |
| 15      | 16       | 5.48%   |
| 18      | 14       | 4.79%   |
| 31      | 5        | 1.71%   |
| 72      | 3        | 1.03%   |
| 34      | 3        | 1.03%   |
| 14      | 3        | 1.03%   |
| 41      | 2        | 0.68%   |
| 39      | 2        | 0.68%   |
| 38      | 2        | 0.68%   |
| 84      | 1        | 0.34%   |
| 65      | 1        | 0.34%   |
| 55      | 1        | 0.34%   |
| 52      | 1        | 0.34%   |
| 48      | 1        | 0.34%   |
| 47      | 1        | 0.34%   |
| 43      | 1        | 0.34%   |
| 42      | 1        | 0.34%   |
| 40      | 1        | 0.34%   |
| 29      | 1        | 0.34%   |
| 26      | 1        | 0.34%   |
| 13      | 1        | 0.34%   |
| 11      | 1        | 0.34%   |
| 7       | 1        | 0.34%   |
| 5       | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 80       | 27.87%  |
| 501-600     | 74       | 25.78%  |
| 301-350     | 46       | 16.03%  |
| 351-400     | 29       | 10.1%   |
| Unknown     | 24       | 8.36%   |
| 601-700     | 8        | 2.79%   |
| 801-900     | 5        | 1.74%   |
| 1001-1500   | 5        | 1.74%   |
| 1501-2000   | 4        | 1.39%   |
| 901-1000    | 4        | 1.39%   |
| 701-800     | 3        | 1.05%   |
| 201-300     | 3        | 1.05%   |
| 101-200     | 2        | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 143      | 51.25%  |
| 5/4     | 51       | 18.28%  |
| 16/10   | 43       | 15.41%  |
| Unknown | 20       | 7.17%   |
| 4/3     | 15       | 5.38%   |
| 21/9    | 4        | 1.43%   |
| 6/5     | 2        | 0.72%   |
| 3/2     | 1        | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 86       | 29.97%  |
| 151-200        | 60       | 20.91%  |
| 141-150        | 39       | 13.59%  |
| Unknown        | 24       | 8.36%   |
| 301-350        | 19       | 6.62%   |
| 101-110        | 16       | 5.57%   |
| 501-1000       | 10       | 3.48%   |
| More than 1000 | 8        | 2.79%   |
| 351-500        | 8        | 2.79%   |
| 251-300        | 7        | 2.44%   |
| 81-90          | 2        | 0.7%    |
| 1-40           | 2        | 0.7%    |
| 131-140        | 2        | 0.7%    |
| 51-60          | 1        | 0.35%   |
| 121-130        | 1        | 0.35%   |
| 111-120        | 1        | 0.35%   |
| 91-100         | 1        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 190      | 67.86%  |
| 101-120       | 40       | 14.29%  |
| Unknown       | 24       | 8.57%   |
| 1-50          | 12       | 4.29%   |
| 121-160       | 11       | 3.93%   |
| 161-240       | 2        | 0.71%   |
| More than 240 | 1        | 0.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 270      | 86.54%  |
| 2     | 22       | 7.05%   |
| 0     | 16       | 5.13%   |
| 3     | 3        | 0.96%   |
| 4     | 1        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 175      | 39.33%  |
| Intel                           | 90       | 20.22%  |
| Nvidia                          | 32       | 7.19%   |
| Qualcomm Atheros                | 28       | 6.29%   |
| Ralink Technology               | 27       | 6.07%   |
| Broadcom                        | 14       | 3.15%   |
| Samsung Electronics             | 8        | 1.8%    |
| Broadcom Limited                | 8        | 1.8%    |
| TP-Link                         | 7        | 1.57%   |
| VIA Technologies                | 6        | 1.35%   |
| Ralink                          | 6        | 1.35%   |
| Marvell Technology Group        | 5        | 1.12%   |
| D-Link System                   | 4        | 0.9%    |
| Qualcomm Atheros Communications | 3        | 0.67%   |
| Huawei Technologies             | 3        | 0.67%   |
| D-Link                          | 3        | 0.67%   |
| Belkin Components               | 3        | 0.67%   |
| ULi Electronics                 | 2        | 0.45%   |
| ASIX Electronics                | 2        | 0.45%   |
| 3Com                            | 2        | 0.45%   |
| ZyXEL Communications            | 1        | 0.22%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.22%   |
| U-Blox                          | 1        | 0.22%   |
| Trident Microsystems            | 1        | 0.22%   |
| T & A Mobile Phones             | 1        | 0.22%   |
| Sitecom Europe                  | 1        | 0.22%   |
| NetGear                         | 1        | 0.22%   |
| Motorola PCS                    | 1        | 0.22%   |
| MediaTek                        | 1        | 0.22%   |
| LSI                             | 1        | 0.22%   |
| Logitec                         | 1        | 0.22%   |
| JMicron Technology              | 1        | 0.22%   |
| Intersil                        | 1        | 0.22%   |
| ASUSTek Computer                | 1        | 0.22%   |
| Aquantia                        | 1        | 0.22%   |
| Apple                           | 1        | 0.22%   |
| ADMtek                          | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 127      | 26.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19       | 4.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15       | 3.18%   |
| Nvidia MCP61 Ethernet                                             | 14       | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 2.34%   |
| Ralink MT7601U Wireless Adapter                                   | 9        | 1.91%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 1.27%   |
| Ralink RT5370 Wireless Adapter                                    | 6        | 1.27%   |
| Nvidia CK804 Ethernet Controller                                  | 6        | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.27%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 5        | 1.06%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 0.85%   |
| Ralink RT5572 Wireless Adapter                                    | 4        | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 0.85%   |
| Nvidia MCP73 Ethernet                                             | 4        | 0.85%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 4        | 0.85%   |
| Intel Wireless 7260                                               | 4        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 0.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 0.64%   |
| Realtek RTL8187 Wireless Adapter                                  | 3        | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.64%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.64%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 3        | 0.64%   |
| Intel NM10/ICH7 Family LAN Controller                             | 3        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.64%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 3        | 0.64%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.42%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 2        | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.42%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2        | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.42%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2        | 0.42%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 2        | 0.42%   |
| Realtek 802.11ac NIC                                              | 2        | 0.42%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 2        | 0.42%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 2        | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 0.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 2        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.42%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.42%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.42%   |
| Nvidia CK8S Ethernet Controller                                   | 2        | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.42%   |
| Intel Wireless-AC 9260                                            | 2        | 0.42%   |
| Intel Wireless 7265                                               | 2        | 0.42%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 0.42%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 27       | 21.77%  |
| Realtek Semiconductor           | 25       | 20.16%  |
| Qualcomm Atheros                | 17       | 13.71%  |
| Intel                           | 17       | 13.71%  |
| TP-Link                         | 7        | 5.65%   |
| Ralink                          | 6        | 4.84%   |
| Broadcom                        | 6        | 4.84%   |
| Qualcomm Atheros Communications | 3        | 2.42%   |
| Belkin Components               | 3        | 2.42%   |
| D-Link System                   | 2        | 1.61%   |
| D-Link                          | 2        | 1.61%   |
| Broadcom Limited                | 2        | 1.61%   |
| ZyXEL Communications            | 1        | 0.81%   |
| Sitecom Europe                  | 1        | 0.81%   |
| Samsung Electronics             | 1        | 0.81%   |
| NetGear                         | 1        | 0.81%   |
| MediaTek                        | 1        | 0.81%   |
| Logitec                         | 1        | 0.81%   |
| ASUSTek Computer                | 1        | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                | 9        | 7.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 6        | 4.84%   |
| Ralink RT5370 Wireless Adapter                                                 | 6        | 4.84%   |
| Ralink RT5572 Wireless Adapter                                                 | 4        | 3.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 4        | 3.23%   |
| Intel Wireless 7260                                                            | 4        | 3.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 3        | 2.42%   |
| Realtek RTL8187 Wireless Adapter                                               | 3        | 2.42%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 2.42%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 3        | 2.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 2        | 1.61%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                            | 2        | 1.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2        | 1.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 2        | 1.61%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                        | 2        | 1.61%   |
| Realtek 802.11ac NIC                                                           | 2        | 1.61%   |
| Ralink RT2501/RT2573 Wireless Adapter                                          | 2        | 1.61%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 2        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2        | 1.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 2        | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 1.61%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 2        | 1.61%   |
| Intel Wireless-AC 9260                                                         | 2        | 1.61%   |
| Intel Wireless 7265                                                            | 2        | 1.61%   |
| Intel Wi-Fi 6 AX200                                                            | 2        | 1.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 2        | 1.61%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller            | 2        | 1.61%   |
| Belkin Components F7D1101 v1 Basic Wireless Adapter [Realtek RTL8188SU]        | 2        | 1.61%   |
| ZyXEL ZyAIR G-202 802.11bg                                                     | 1        | 0.81%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                          | 1        | 0.81%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 0.81%   |
| TP-Link 802.11ac NIC                                                           | 1        | 0.81%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                                | 1        | 0.81%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                               | 1        | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.81%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                | 1        | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1        | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1        | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 0.81%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 0.81%   |
| Ralink RT2070 Wireless Adapter                                                 | 1        | 0.81%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                    | 1        | 0.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1        | 0.81%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                           | 1        | 0.81%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1        | 0.81%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1        | 0.81%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 0.81%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                    | 1        | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 1        | 0.81%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                                      | 1        | 0.81%   |
| Intel Wireless 3165                                                            | 1        | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1        | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1        | 0.81%   |
| Intel Centrino Advanced-N 6235                                                 | 1        | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1        | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 163      | 48.37%  |
| Intel                      | 76       | 22.55%  |
| Nvidia                     | 32       | 9.5%    |
| Qualcomm Atheros           | 13       | 3.86%   |
| Broadcom                   | 9        | 2.67%   |
| Samsung Electronics        | 7        | 2.08%   |
| VIA Technologies           | 6        | 1.78%   |
| Broadcom Limited           | 6        | 1.78%   |
| Marvell Technology Group   | 5        | 1.48%   |
| Huawei Technologies        | 3        | 0.89%   |
| ULi Electronics            | 2        | 0.59%   |
| D-Link System              | 2        | 0.59%   |
| ASIX Electronics           | 2        | 0.59%   |
| 3Com                       | 2        | 0.59%   |
| ZTE WCDMA Technologies MSM | 1        | 0.3%    |
| Trident Microsystems       | 1        | 0.3%    |
| T & A Mobile Phones        | 1        | 0.3%    |
| Motorola PCS               | 1        | 0.3%    |
| JMicron Technology         | 1        | 0.3%    |
| D-Link                     | 1        | 0.3%    |
| Aquantia                   | 1        | 0.3%    |
| Apple                      | 1        | 0.3%    |
| ADMtek                     | 1        | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 127      | 36.92%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19       | 5.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15       | 4.36%   |
| Nvidia MCP61 Ethernet                                             | 14       | 4.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 3.2%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 2.03%   |
| Nvidia CK804 Ethernet Controller                                  | 6        | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.74%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.74%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 5        | 1.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 1.16%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.16%   |
| Nvidia MCP73 Ethernet                                             | 4        | 1.16%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 4        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.87%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.87%   |
| Intel NM10/ICH7 Family LAN Controller                             | 3        | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.87%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.87%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.87%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 3        | 0.87%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.58%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 2        | 0.58%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.58%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.58%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.58%   |
| Nvidia CK8S Ethernet Controller                                   | 2        | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.58%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.58%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.58%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.58%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.58%   |
| Intel 82566DM Gigabit Network Connection                          | 2        | 0.58%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.58%   |
| Huawei LYA-L09                                                    | 2        | 0.58%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 2        | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.58%   |
| ZTE WCDMA MSM Z6201V                                              | 1        | 0.29%   |
| Trident Microsystems 4DWave DX                                    | 1        | 0.29%   |
| T & A Mobile Phones 9010X                                         | 1        | 0.29%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.29%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.29%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.29%   |
| Motorola PCS moto g(9) play                                       | 1        | 0.29%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.29%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.29%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.29%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.29%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.29%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.29%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 303      | 71.29%  |
| WiFi     | 119      | 28%     |
| Modem    | 2        | 0.47%   |
| Unknown  | 1        | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 240      | 75.71%  |
| WiFi     | 77       | 24.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 229      | 74.11%  |
| 2     | 67       | 21.68%  |
| 3     | 7        | 2.27%   |
| 0     | 4        | 1.29%   |
| 6     | 1        | 0.32%   |
| 4     | 1        | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 264      | 85.16%  |
| Yes  | 46       | 14.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 16       | 34.04%  |
| Intel                           | 15       | 31.91%  |
| Broadcom                        | 4        | 8.51%   |
| Qualcomm Atheros Communications | 2        | 4.26%   |
| Ralink                          | 1        | 2.13%   |
| MediaTek                        | 1        | 2.13%   |
| Logitech                        | 1        | 2.13%   |
| Lite-On Technology              | 1        | 2.13%   |
| Integrated System Solution      | 1        | 2.13%   |
| HTC (High Tech Computer)        | 1        | 2.13%   |
| Hewlett-Packard                 | 1        | 2.13%   |
| Fujitsu                         | 1        | 2.13%   |
| Dynex                           | 1        | 2.13%   |
| ASUSTek Computer                | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 16       | 34.04%  |
| Intel Bluetooth wireless interface                                   | 6        | 12.77%  |
| Qualcomm Atheros AR3011 Bluetooth                                    | 2        | 4.26%   |
| Intel Bluetooth Device                                               | 2        | 4.26%   |
| Intel AX200 Bluetooth                                                | 2        | 4.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 4.26%   |
| Ralink RT3290 Bluetooth                                              | 1        | 2.13%   |
| MediaTek Wireless_Device                                             | 1        | 2.13%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 2.13%   |
| Lite-On Bluetooth Device                                             | 1        | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 2.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 2.13%   |
| Intel AX210 Bluetooth                                                | 1        | 2.13%   |
| Intel AX201 Bluetooth                                                | 1        | 2.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 2.13%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 1        | 2.13%   |
| Fujitsu Bluetooth Device                                             | 1        | 2.13%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 2.13%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 2.13%   |
| Broadcom Bluetooth Device                                            | 1        | 2.13%   |
| ASUS Bluetooth Radio                                                 | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 172      | 39.81%  |
| AMD                                          | 102      | 23.61%  |
| Nvidia                                       | 99       | 22.92%  |
| C-Media Electronics                          | 13       | 3.01%   |
| Creative Labs                                | 10       | 2.31%   |
| VIA Technologies                             | 8        | 1.85%   |
| XMOS                                         | 3        | 0.69%   |
| ULi Electronics                              | 2        | 0.46%   |
| Texas Instruments                            | 2        | 0.46%   |
| Logitech                                     | 2        | 0.46%   |
| Generalplus Technology                       | 2        | 0.46%   |
| Creative Technology                          | 2        | 0.46%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.23%   |
| Unknown                                      | 1        | 0.23%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.23%   |
| Razer USA                                    | 1        | 0.23%   |
| Nordic Semiconductor ASA                     | 1        | 0.23%   |
| KORG                                         | 1        | 0.23%   |
| Guillemot                                    | 1        | 0.23%   |
| GN Netcom                                    | 1        | 0.23%   |
| Focusrite-Novation                           | 1        | 0.23%   |
| ESI                                          | 1        | 0.23%   |
| Ensoniq                                      | 1        | 0.23%   |
| Elgato Systems                               | 1        | 0.23%   |
| Cirrus Logic                                 | 1        | 0.23%   |
| ASUSTek Computer                             | 1        | 0.23%   |
| Asahi Kasei Microsystems                     | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 29       | 5.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 24       | 4.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 22       | 4.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18       | 3.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 18       | 3.65%   |
| Nvidia High Definition Audio Controller                                           | 16       | 3.25%   |
| Nvidia MCP61 High Definition Audio                                                | 15       | 3.04%   |
| AMD FCH Azalia Controller                                                         | 15       | 3.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 2.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 10       | 2.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 10       | 2.03%   |
| AMD Starship/Matisse HD Audio Controller                                          | 10       | 2.03%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9        | 1.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 9        | 1.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 9        | 1.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8        | 1.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7        | 1.42%   |
| AMD Kabini HDMI/DP Audio                                                          | 7        | 1.42%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 1.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7        | 1.42%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.42%   |
| Nvidia GK107 HDMI Audio Controller                                                | 6        | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6        | 1.22%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 6        | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 1.22%   |
| Nvidia CK804 AC'97 Audio Controller                                               | 5        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 5        | 1.01%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 5        | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 1.01%   |
| AMD Wrestler HDMI Audio                                                           | 5        | 1.01%   |
| AMD Trinity HDMI Audio Controller                                                 | 5        | 1.01%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 5        | 1.01%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 4        | 0.81%   |
| Nvidia MCP73 High Definition Audio                                                | 4        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 0.81%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 0.81%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 0.81%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 4        | 0.81%   |
| XMOS Mayfield Audio                                                               | 3        | 0.61%   |
| Intel Comet Lake PCH-V cAVS                                                       | 3        | 0.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3        | 0.61%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 3        | 0.61%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                            | 3        | 0.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 0.61%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 2        | 0.41%   |
| Nvidia TU104 HD Audio Controller                                                  | 2        | 0.41%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 0.41%   |
| Nvidia MCP51 High Definition Audio                                                | 2        | 0.41%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 0.41%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.41%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.41%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.41%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.41%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.41%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 0.41%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 0.41%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 0.41%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.41%   |
| Intel Audio device                                                                | 2        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 51       | 24.88%  |
| Samsung Electronics | 29       | 14.15%  |
| Kingston            | 28       | 13.66%  |
| SK hynix            | 23       | 11.22%  |
| G.Skill             | 12       | 5.85%   |
| Corsair             | 11       | 5.37%   |
| Micron Technology   | 9        | 4.39%   |
| Crucial             | 9        | 4.39%   |
| Nanya Technology    | 6        | 2.93%   |
| Elpida              | 3        | 1.46%   |
| A-DATA Technology   | 3        | 1.46%   |
| Timetec             | 2        | 0.98%   |
| Patriot             | 2        | 0.98%   |
| Unknown             | 2        | 0.98%   |
| Unknown (ABCD)      | 1        | 0.49%   |
| Unknown (07FB)      | 1        | 0.49%   |
| Unifosa             | 1        | 0.49%   |
| Transcend           | 1        | 0.49%   |
| Teikon              | 1        | 0.49%   |
| Team                | 1        | 0.49%   |
| Smart               | 1        | 0.49%   |
| Ramaxel Technology  | 1        | 0.49%   |
| Qimonda             | 1        | 0.49%   |
| Princeton           | 1        | 0.49%   |
| Infineon            | 1        | 0.49%   |
| Golden Empire       | 1        | 0.49%   |
| e2e4                | 1        | 0.49%   |
| ASint Technology    | 1        | 0.49%   |
| 48spaces            | 1        | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s            | 4        | 1.78%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 3        | 1.33%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 2        | 0.89%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s               | 2        | 0.89%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s               | 2        | 0.89%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s    | 2        | 0.89%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 2        | 0.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 2        | 0.89%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s   | 2        | 0.89%   |
| Samsung RAM M3 78T6553EZS-CE6 512MB DIMM DDR 667MT/s     | 2        | 0.89%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s       | 2        | 0.89%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s             | 2        | 0.89%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s      | 2        | 0.89%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 2        | 0.89%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s      | 2        | 0.89%   |
| Corsair RAM CMK16GX4M2A2666C16 8192MB DIMM DDR4 3200MT/s | 2        | 0.89%   |
| Unknown                                                  | 2        | 0.89%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 0.44%   |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s             | 1        | 0.44%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                   | 1        | 0.44%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s               | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM 333MT/s                    | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s             | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM                           | 1        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 1333MT/s                | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                     | 1        | 0.44%   |
| Unknown RAM Module 256MB DIMM SDRAM                      | 1        | 0.44%   |
| Unknown RAM Module 256MB DIMM DRAM                       | 1        | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR3 800MT/s              | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s             | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s              | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s               | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 41632MT/s                 | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM                           | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM DDR 800MT/s                  | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM                              | 1        | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s            | 1        | 0.44%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s              | 1        | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s              | 1        | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR2                      | 1        | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR                       | 1        | 0.44%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 1        | 0.44%   |
| Unknown RAM Module 1024MB DIMM                           | 1        | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 62       | 34.44%  |
| DDR4    | 39       | 21.67%  |
| DDR2    | 29       | 16.11%  |
| Unknown | 21       | 11.67%  |
| SDRAM   | 17       | 9.44%   |
| DDR     | 10       | 5.56%   |
| LPDDR4  | 1        | 0.56%   |
| DRAM    | 1        | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 155      | 88.57%  |
| SODIMM | 20       | 11.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 62       | 31.63%  |
| 8192  | 45       | 22.96%  |
| 4096  | 39       | 19.9%   |
| 1024  | 22       | 11.22%  |
| 16384 | 13       | 6.63%   |
| 512   | 7        | 3.57%   |
| 256   | 4        | 2.04%   |
| 32768 | 2        | 1.02%   |
| 65536 | 1        | 0.51%   |
| 128   | 1        | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 37       | 19.07%  |
| 1333    | 20       | 10.31%  |
| 800     | 19       | 9.79%   |
| Unknown | 12       | 6.19%   |
| 3200    | 11       | 5.67%   |
| 667     | 11       | 5.67%   |
| 2133    | 10       | 5.15%   |
| 400     | 8        | 4.12%   |
| 2400    | 7        | 3.61%   |
| 2667    | 6        | 3.09%   |
| 1066    | 6        | 3.09%   |
| 3600    | 5        | 2.58%   |
| 533     | 5        | 2.58%   |
| 2048    | 4        | 2.06%   |
| 1867    | 4        | 2.06%   |
| 1866    | 4        | 2.06%   |
| 333     | 4        | 2.06%   |
| 49926   | 3        | 1.55%   |
| 1067    | 3        | 1.55%   |
| 3466    | 2        | 1.03%   |
| 3000    | 2        | 1.03%   |
| 266     | 2        | 1.03%   |
| 41632   | 1        | 0.52%   |
| 3151    | 1        | 0.52%   |
| 3066    | 1        | 0.52%   |
| 2800    | 1        | 0.52%   |
| 2733    | 1        | 0.52%   |
| 2666    | 1        | 0.52%   |
| 1800    | 1        | 0.52%   |
| 1639    | 1        | 0.52%   |
| 1334    | 1        | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 50%     |
| Samsung Electronics | 3        | 37.5%   |
| Brother Industries  | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Xerox Phaser 3117 Laser Printer | 1        | 12.5%   |
| Samsung SCX-3400 Series                 | 1        | 12.5%   |
| Samsung M2020 Series                    | 1        | 12.5%   |
| HP PSC 1500 series                      | 1        | 12.5%   |
| HP OfficeJet 4650 series                | 1        | 12.5%   |
| HP DeskJet D2460                        | 1        | 12.5%   |
| HP DeskJet 3630 series                  | 1        | 12.5%   |
| Brother Printer                         | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 75%     |
| Canon           | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP scanjet 8270         | 1        | 25%     |
| HP ScanJet 2400c        | 1        | 25%     |
| HP HP4470C              | 1        | 25%     |
| Canon CanoScan LiDE 220 | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 19.44%  |
| Microsoft                     | 3        | 8.33%   |
| Samsung Electronics           | 2        | 5.56%   |
| KYE Systems (Mouse Systems)   | 2        | 5.56%   |
| Generalplus Technology        | 2        | 5.56%   |
| GEMBIRD                       | 2        | 5.56%   |
| Chicony Electronics           | 2        | 5.56%   |
| ARC International             | 2        | 5.56%   |
| Apple                         | 2        | 5.56%   |
| Z-Star Microelectronics       | 1        | 2.78%   |
| Sunplus Innovation Technology | 1        | 2.78%   |
| SJ-180517-N                   | 1        | 2.78%   |
| Pixart Imaging                | 1        | 2.78%   |
| Microdia                      | 1        | 2.78%   |
| LG Electronics                | 1        | 2.78%   |
| Huawei Technologies           | 1        | 2.78%   |
| Guillemot                     | 1        | 2.78%   |
| GEO Semi                      | 1        | 2.78%   |
| Genesys Logic                 | 1        | 2.78%   |
| AVerMedia Technologies        | 1        | 2.78%   |
| Acer                          | 1        | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                             | 3        | 8.33%   |
| Samsung Galaxy A5 (MTP)                               | 2        | 5.56%   |
| Logitech Webcam C270                                  | 2        | 5.56%   |
| Logitech HD Webcam C525                               | 2        | 5.56%   |
| Generalplus WEB CAM                                   | 2        | 5.56%   |
| ARC International Camera                              | 2        | 5.56%   |
| Apple iPhone 5/5C/5S/6/SE                             | 2        | 5.56%   |
| Z-Star Sirius USB2.0 Camera                           | 1        | 2.78%   |
| Sunplus Full HD webcam                                | 1        | 2.78%   |
| SJ-180517-N 1080P Webcam                              | 1        | 2.78%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 1        | 2.78%   |
| Microdia Amcrest AWC2198 USB Webcam                   | 1        | 2.78%   |
| Logitech Webcam C300                                  | 1        | 2.78%   |
| Logitech QuickCam Zoom                                | 1        | 2.78%   |
| Logitech HD Webcam C615                               | 1        | 2.78%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 2.78%   |
| KYE Systems (Mouse Systems) Genius eFace 1325R        | 1        | 2.78%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 1        | 2.78%   |
| Huawei HiCamera                                       | 1        | 2.78%   |
| Guillemot Hercules HD Sunset                          | 1        | 2.78%   |
| GEO Semi Condor                                       | 1        | 2.78%   |
| Genesys Logic Camera                                  | 1        | 2.78%   |
| GEMBIRD USB2.0 PC CAMERA                              | 1        | 2.78%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 1        | 2.78%   |
| Chicony CNF7042                                       | 1        | 2.78%   |
| Chicony ASUS USB2.0 Webcam                            | 1        | 2.78%   |
| AVerMedia Live Streamer CAM 313                       | 1        | 2.78%   |
| Acer Integrated Camera                                | 1        | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| OmniKey     | 1        | 50%     |
| Alcor Micro | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121         | 1        | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 256      | 81.53%  |
| 1     | 50       | 15.92%  |
| 2     | 8        | 2.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 25       | 40.32%  |
| Net/wireless             | 10       | 16.13%  |
| Communication controller | 7        | 11.29%  |
| Sound                    | 4        | 6.45%   |
| Multimedia controller    | 4        | 6.45%   |
| Unassigned class         | 3        | 4.84%   |
| Net/ethernet             | 2        | 3.23%   |
| Chipcard                 | 2        | 3.23%   |
| Bluetooth                | 2        | 3.23%   |
| Modem                    | 1        | 1.61%   |
| Dvb card                 | 1        | 1.61%   |
| Camera                   | 1        | 1.61%   |

