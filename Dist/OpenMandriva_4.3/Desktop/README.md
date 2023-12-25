OpenMandriva 4.3 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 2249

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | 965P-S3                     | [b73dd61ca5](https://linux-hardware.org/?probe=b73dd61ca5) | Dec 09, 2023 |
| HP            | 18E5                        | [7b54dc44b4](https://linux-hardware.org/?probe=7b54dc44b4) | Dec 06, 2023 |
| HP            | 8265                        | [1faa811cf0](https://linux-hardware.org/?probe=1faa811cf0) | Dec 03, 2023 |
| MSI           | A320M-A PRO MAX             | [40327ad292](https://linux-hardware.org/?probe=40327ad292) | Nov 20, 2023 |
| HP            | 1589                        | [3e5f417056](https://linux-hardware.org/?probe=3e5f417056) | Nov 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [68aadf1f9b](https://linux-hardware.org/?probe=68aadf1f9b) | Nov 17, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [199a544882](https://linux-hardware.org/?probe=199a544882) | Nov 16, 2023 |
| HP            | 1998                        | [eb9bb55c96](https://linux-hardware.org/?probe=eb9bb55c96) | Nov 16, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [fd1391a823](https://linux-hardware.org/?probe=fd1391a823) | Nov 15, 2023 |
| Foxconn       | 2A92                        | [6cd9ba6728](https://linux-hardware.org/?probe=6cd9ba6728) | Nov 15, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [780d61593a](https://linux-hardware.org/?probe=780d61593a) | Nov 14, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [0342a78240](https://linux-hardware.org/?probe=0342a78240) | Nov 13, 2023 |
| HP            | 1850                        | [10595f0ac3](https://linux-hardware.org/?probe=10595f0ac3) | Nov 10, 2023 |
| ASUSTek       | PRIME Q270M-C               | [0fcd993247](https://linux-hardware.org/?probe=0fcd993247) | Nov 10, 2023 |
| ASUSTek       | A68HM-K                     | [c3e5415128](https://linux-hardware.org/?probe=c3e5415128) | Nov 06, 2023 |
| ASRock        | FM2A68M-HD+                 | [2b5c984cd8](https://linux-hardware.org/?probe=2b5c984cd8) | Nov 04, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [09d5186c37](https://linux-hardware.org/?probe=09d5186c37) | Oct 30, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [0be3861a6a](https://linux-hardware.org/?probe=0be3861a6a) | Oct 29, 2023 |
| HP            | 8054                        | [3f9ecca91a](https://linux-hardware.org/?probe=3f9ecca91a) | Oct 26, 2023 |
| ASUSTek       | P8H77-M PRO                 | [968efc7996](https://linux-hardware.org/?probe=968efc7996) | Oct 20, 2023 |
| Lenovo        | 30D0 NOK                    | [e67eff74dc](https://linux-hardware.org/?probe=e67eff74dc) | Oct 20, 2023 |
| ASRock        | H110M-HDV R3.0              | [491538303f](https://linux-hardware.org/?probe=491538303f) | Oct 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [6e81d4f878](https://linux-hardware.org/?probe=6e81d4f878) | Oct 18, 2023 |
| Acer          | Aspire GX-281               | [17fad55365](https://linux-hardware.org/?probe=17fad55365) | Oct 16, 2023 |
| ACTION        | M5A78L-M lX V2              | [fe141a8a31](https://linux-hardware.org/?probe=fe141a8a31) | Oct 15, 2023 |
| HP            | 158A                        | [9e43d14a8e](https://linux-hardware.org/?probe=9e43d14a8e) | Oct 10, 2023 |
| MSI           | MS-7235                     | [afb00bf553](https://linux-hardware.org/?probe=afb00bf553) | Oct 07, 2023 |
| Gigabyte      | GA-K8NE                     | [8cb50a99b7](https://linux-hardware.org/?probe=8cb50a99b7) | Oct 07, 2023 |
| Gigabyte      | F2A55M-DS2                  | [75d90cf644](https://linux-hardware.org/?probe=75d90cf644) | Oct 07, 2023 |
| Pegatron      | Benicia                     | [b70dfb3fc8](https://linux-hardware.org/?probe=b70dfb3fc8) | Oct 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [a3ea9b4b56](https://linux-hardware.org/?probe=a3ea9b4b56) | Oct 04, 2023 |
| Gigabyte      | F2A88X-D3H                  | [6ea97d511f](https://linux-hardware.org/?probe=6ea97d511f) | Oct 04, 2023 |
| Lenovo        | ThinkCentre M58p 7484ANU    | [edc20561a3](https://linux-hardware.org/?probe=edc20561a3) | Oct 03, 2023 |
| MSI           | 970 GAMING                  | [c095e62997](https://linux-hardware.org/?probe=c095e62997) | Oct 02, 2023 |
| MSI           | B350M PRO-VD PLUS           | [a8c796cebf](https://linux-hardware.org/?probe=a8c796cebf) | Oct 01, 2023 |
| HP            | 3398                        | [13aa132a7d](https://linux-hardware.org/?probe=13aa132a7d) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | [b31e10d01b](https://linux-hardware.org/?probe=b31e10d01b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | [ba340393f7](https://linux-hardware.org/?probe=ba340393f7) | Sep 29, 2023 |
| Pegatron      | Benicia                     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| MSI           | B450M BAZOOKA V2            | [c815d636ce](https://linux-hardware.org/?probe=c815d636ce) | Sep 28, 2023 |
| MSI           | Z97-G45 GAMING              | [19c07d0fca](https://linux-hardware.org/?probe=19c07d0fca) | Sep 27, 2023 |
| Lenovo        | ThinkCentre A70z 0401B7P    | [21a635940f](https://linux-hardware.org/?probe=21a635940f) | Sep 24, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [3d3b14f0f9](https://linux-hardware.org/?probe=3d3b14f0f9) | Sep 21, 2023 |
| ASUSTek       | B150M-C D3                  | [179a66ec43](https://linux-hardware.org/?probe=179a66ec43) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | [b21eddb040](https://linux-hardware.org/?probe=b21eddb040) | Sep 19, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | [fa9b30f699](https://linux-hardware.org/?probe=fa9b30f699) | Sep 18, 2023 |
| Gigabyte      | A520M H                     | [24efefc447](https://linux-hardware.org/?probe=24efefc447) | Sep 17, 2023 |
| Dell          | 048DY8 A00                  | [3cc67a5e62](https://linux-hardware.org/?probe=3cc67a5e62) | Sep 15, 2023 |
| ASUSTek       | P5KPL-AM                    | [3f55a69040](https://linux-hardware.org/?probe=3f55a69040) | Sep 11, 2023 |
| Toshiba       | STI 006998G                 | [d34aadcc92](https://linux-hardware.org/?probe=d34aadcc92) | Sep 07, 2023 |
| ASRock        | Z68 Pro3                    | [757ebbe056](https://linux-hardware.org/?probe=757ebbe056) | Sep 06, 2023 |
| Foxconn       | G31MX Series                | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Acer          | Aspire XC-830               | [a3356b9a91](https://linux-hardware.org/?probe=a3356b9a91) | Sep 03, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [f11dacb362](https://linux-hardware.org/?probe=f11dacb362) | Sep 01, 2023 |
| ASRock        | AB350M Pro4                 | [0f9de0fdf4](https://linux-hardware.org/?probe=0f9de0fdf4) | Sep 01, 2023 |
| Foxconn       | A6VMX 0A                    | [338cdb7d40](https://linux-hardware.org/?probe=338cdb7d40) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Gigabyte      | X58A-UD3R                   | [8ee240ba0b](https://linux-hardware.org/?probe=8ee240ba0b) | Sep 01, 2023 |
| MSI           | PRO B660M-A DDR4            | [b6a24176aa](https://linux-hardware.org/?probe=b6a24176aa) | Aug 31, 2023 |
| HP            | 18E5                        | [75c3b34f87](https://linux-hardware.org/?probe=75c3b34f87) | Aug 31, 2023 |
| Gigabyte      | B450M K-CF                  | [2086d348b2](https://linux-hardware.org/?probe=2086d348b2) | Aug 31, 2023 |
| ASUSTek       | P8H61 EVO                   | [facd465366](https://linux-hardware.org/?probe=facd465366) | Aug 30, 2023 |
| MSI           | G41M-P33 Combo              | [23712e9380](https://linux-hardware.org/?probe=23712e9380) | Aug 28, 2023 |
| Positivo      | POS-PQ45AU                  | [aba45a4f14](https://linux-hardware.org/?probe=aba45a4f14) | Aug 27, 2023 |
| ASUSTek       | P8Z77-V LX                  | [9f1872b5e9](https://linux-hardware.org/?probe=9f1872b5e9) | Aug 26, 2023 |
| GEEKOM        | GM08i3T                     | [36ea06968d](https://linux-hardware.org/?probe=36ea06968d) | Aug 23, 2023 |
| ASRock        | 890GX Pro3                  | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| Gigabyte      | GA-N680SLI-DQ6              | [0838a31aaf](https://linux-hardware.org/?probe=0838a31aaf) | Aug 19, 2023 |
| Intel         | DE3815TYKH H26998-402       | [a2a8c567a3](https://linux-hardware.org/?probe=a2a8c567a3) | Aug 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [83e6c3323d](https://linux-hardware.org/?probe=83e6c3323d) | Aug 16, 2023 |
| HP            | 3031h                       | [2f9084013a](https://linux-hardware.org/?probe=2f9084013a) | Aug 13, 2023 |
| ASUSTek       | P7P55D DELUXE               | [f900ebabde](https://linux-hardware.org/?probe=f900ebabde) | Aug 13, 2023 |
| ASUSTek       | Rampage IV GENE             | [2a494a04b5](https://linux-hardware.org/?probe=2a494a04b5) | Aug 12, 2023 |
| HP            | 18E7                        | [ff27f888f0](https://linux-hardware.org/?probe=ff27f888f0) | Aug 10, 2023 |
| Dell          | 040DDP A00                  | [13d99d66da](https://linux-hardware.org/?probe=13d99d66da) | Aug 09, 2023 |
| Dell          | 0P301D A00                  | [e5091194fb](https://linux-hardware.org/?probe=e5091194fb) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c94a18b924](https://linux-hardware.org/?probe=c94a18b924) | Aug 02, 2023 |
| HP            | 18E7                        | [339050cd65](https://linux-hardware.org/?probe=339050cd65) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3a500cdb55](https://linux-hardware.org/?probe=3a500cdb55) | Aug 01, 2023 |
| Dell          | 0C27VV A03                  | [75ff82774b](https://linux-hardware.org/?probe=75ff82774b) | Jul 31, 2023 |
| PCWare        | IPX1800E2                   | [ee17cd82e7](https://linux-hardware.org/?probe=ee17cd82e7) | Jul 27, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [1d4e6c23cf](https://linux-hardware.org/?probe=1d4e6c23cf) | Jul 27, 2023 |
| HP            | 212B                        | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| Dell          | 0VD92X A00                  | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| Intel         | JSL MRD                     | [4c9c765884](https://linux-hardware.org/?probe=4c9c765884) | Jul 21, 2023 |
| Dell          | 0M863N A01                  | [682fc212b6](https://linux-hardware.org/?probe=682fc212b6) | Jul 20, 2023 |
| Intel X79     | Unknown                     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [87763ca861](https://linux-hardware.org/?probe=87763ca861) | Jul 16, 2023 |
| Foxconn       | 2ABF                        | [e302c823fc](https://linux-hardware.org/?probe=e302c823fc) | Jul 13, 2023 |
| HP            | 18E8                        | [b892f0dd28](https://linux-hardware.org/?probe=b892f0dd28) | Jul 12, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [7a8f3c985f](https://linux-hardware.org/?probe=7a8f3c985f) | Jul 11, 2023 |
| Gigabyte      | B450M DS3H-CF               | [144cb029ba](https://linux-hardware.org/?probe=144cb029ba) | Jul 08, 2023 |
| Dell          | 01TKCC A01                  | [b3ab41fd8f](https://linux-hardware.org/?probe=b3ab41fd8f) | Jul 08, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [c9ccceb765](https://linux-hardware.org/?probe=c9ccceb765) | Jul 07, 2023 |
| ASRock        | H510M-HDV R2.0              | [2cb98a7961](https://linux-hardware.org/?probe=2cb98a7961) | Jul 06, 2023 |
| ECS           | H55H-M2                     | [344ce5bb17](https://linux-hardware.org/?probe=344ce5bb17) | Jul 03, 2023 |
| ASUSTek       | UN45                        | [487845dd55](https://linux-hardware.org/?probe=487845dd55) | Jul 03, 2023 |
| Gigabyte      | 965P-S3                     | [7aa7550205](https://linux-hardware.org/?probe=7aa7550205) | Jul 02, 2023 |
| MSI           | PRO X670-P WIFI             | [7beeaf657d](https://linux-hardware.org/?probe=7beeaf657d) | Jul 02, 2023 |
| Gigabyte      | H61M-S1                     | [b6be2d7f9f](https://linux-hardware.org/?probe=b6be2d7f9f) | Jun 30, 2023 |
| Acer          | Aspire TC-705               | [326f873ac3](https://linux-hardware.org/?probe=326f873ac3) | Jun 29, 2023 |
| ASUSTek       | M5A97 PLUS                  | [2faeb24e37](https://linux-hardware.org/?probe=2faeb24e37) | Jun 27, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [90067b8232](https://linux-hardware.org/?probe=90067b8232) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [a31908b24b](https://linux-hardware.org/?probe=a31908b24b) | Jun 25, 2023 |
| Intel         | DH61WW AAG23116-204         | [4269ca2c0b](https://linux-hardware.org/?probe=4269ca2c0b) | Jun 25, 2023 |
| HP            | 8055                        | [7fac5a1354](https://linux-hardware.org/?probe=7fac5a1354) | Jun 24, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [9408842ffc](https://linux-hardware.org/?probe=9408842ffc) | Jun 24, 2023 |
| MSI           | MS-7360                     | [9a0d46b069](https://linux-hardware.org/?probe=9a0d46b069) | Jun 23, 2023 |
| Dell          | 0WMJ54 A01                  | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| ASUSTek       | PRIME B365M-A               | [4e877b9c8d](https://linux-hardware.org/?probe=4e877b9c8d) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [4560c6d34d](https://linux-hardware.org/?probe=4560c6d34d) | Jun 19, 2023 |
| ASUSTek       | P8H61-M LX                  | [35de204113](https://linux-hardware.org/?probe=35de204113) | Jun 19, 2023 |
| MSI           | 2AE0                        | [fdfc88e5da](https://linux-hardware.org/?probe=fdfc88e5da) | Jun 18, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3c45e54fd2](https://linux-hardware.org/?probe=3c45e54fd2) | Jun 17, 2023 |
| ASUSTek       | H97-PLUS                    | [adc38f998a](https://linux-hardware.org/?probe=adc38f998a) | Jun 17, 2023 |
| ASUSTek       | H61M-A/BR                   | [a587493314](https://linux-hardware.org/?probe=a587493314) | Jun 16, 2023 |
| Lenovo        | SDK0E50510 WIN              | [8571bdf994](https://linux-hardware.org/?probe=8571bdf994) | Jun 15, 2023 |
| Acer          | Veriton M6630G V:1.0        | [d58cd3aa7d](https://linux-hardware.org/?probe=d58cd3aa7d) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [922c598503](https://linux-hardware.org/?probe=922c598503) | Jun 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [26e6a1f816](https://linux-hardware.org/?probe=26e6a1f816) | Jun 13, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | [5c2eef3678](https://linux-hardware.org/?probe=5c2eef3678) | Jun 12, 2023 |
| ASUSTek       | P8Z77-V LX                  | [b5b264d1e8](https://linux-hardware.org/?probe=b5b264d1e8) | Jun 12, 2023 |
| ASRock        | G41M-VS3                    | [d592b19e9b](https://linux-hardware.org/?probe=d592b19e9b) | Jun 10, 2023 |
| Wistron       | ProLiant ML110 G5           | [eea1c44d94](https://linux-hardware.org/?probe=eea1c44d94) | Jun 10, 2023 |
| Biostar       | H610MH                      | [2cd4e157d4](https://linux-hardware.org/?probe=2cd4e157d4) | Jun 08, 2023 |
| HP            | 1850                        | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| HP            | 1495                        | [0cbf6bee1f](https://linux-hardware.org/?probe=0cbf6bee1f) | Jun 04, 2023 |
| MSI           | Boston                      | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| TPV-INVENT... | 2AC6 A01                    | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| Gigabyte      | H61M-DS2 x.x                | [e58b7bfc92](https://linux-hardware.org/?probe=e58b7bfc92) | May 29, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | [bf3b702d7a](https://linux-hardware.org/?probe=bf3b702d7a) | May 28, 2023 |
| MSI           | A520M-A PRO                 | [6f1a19d503](https://linux-hardware.org/?probe=6f1a19d503) | May 25, 2023 |
| Gigabyte      | B365M DS3H                  | [149a19eeeb](https://linux-hardware.org/?probe=149a19eeeb) | May 24, 2023 |
| ASUSTek       | H81M-K                      | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Gigabyte      | H510M H                     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| HP            | 0A54h                       | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| Gigabyte      | B450M H                     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| HP            | 18E5                        | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| ASRock        | G41M-GS3                    | [8859685e86](https://linux-hardware.org/?probe=8859685e86) | May 13, 2023 |
| Dell          | 09KPNV A01                  | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Dell          | 0W0CHX A00                  | [60defd2bfe](https://linux-hardware.org/?probe=60defd2bfe) | May 12, 2023 |
| Acer          | RS880M05                    | [5952c105f6](https://linux-hardware.org/?probe=5952c105f6) | May 12, 2023 |
| Gigabyte      | H61M-S1                     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [68afb54270](https://linux-hardware.org/?probe=68afb54270) | May 10, 2023 |
| ASUSTek       | M4A78L-M                    | [1a843c3a7f](https://linux-hardware.org/?probe=1a843c3a7f) | May 10, 2023 |
| ASUSTek       | P8H67                       | [eeb083abcd](https://linux-hardware.org/?probe=eeb083abcd) | May 07, 2023 |
| Shuttle       | FZ77                        | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| MSI           | 760GM-P34                   | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| MSI           | MS-7025                     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| MAXSUN        | MS-A86FX FS M.3             | [3ce20d3b05](https://linux-hardware.org/?probe=3ce20d3b05) | May 01, 2023 |
| DIEBOLD       | NM70-I                      | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| ASUSTek       | H81M-C/BR                   | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| AZW           | MINI S 10                   | [12ba32f977](https://linux-hardware.org/?probe=12ba32f977) | Apr 28, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| ASUSTek       | P8P67 LE                    | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| ASRock        | AB350M-HDV                  | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| ASUSTek       | A68HM-K                     | [ae90303c3a](https://linux-hardware.org/?probe=ae90303c3a) | Apr 25, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | [b1b8bf3df6](https://linux-hardware.org/?probe=b1b8bf3df6) | Apr 25, 2023 |
| HP            | 0AA8h                       | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Gigabyte      | H61M-S2PH                   | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Biostar       | A75MG                       | [50cb5c256e](https://linux-hardware.org/?probe=50cb5c256e) | Apr 22, 2023 |
| Intel         | DB65AL AAG12530-310         | [c625f3747a](https://linux-hardware.org/?probe=c625f3747a) | Apr 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| Foxconn       | 2ABF                        | [53d3a8d066](https://linux-hardware.org/?probe=53d3a8d066) | Apr 19, 2023 |
| Gigabyte      | G31M-ES2L                   | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| ASUSTek       | PRIME X570-P                | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [7ac461b735](https://linux-hardware.org/?probe=7ac461b735) | Apr 15, 2023 |
| Gigabyte      | P55-UD3R                    | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Dell          | 0GXM1W A00                  | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASRock        | M3N78D FX                   | [618073d9e9](https://linux-hardware.org/?probe=618073d9e9) | Apr 12, 2023 |
| Dell          | 0WR7PY A02                  | [2cec768fe1](https://linux-hardware.org/?probe=2cec768fe1) | Apr 11, 2023 |
| ASRock        | X570 Pro4                   | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [54fabc7712](https://linux-hardware.org/?probe=54fabc7712) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [2d355e87d7](https://linux-hardware.org/?probe=2d355e87d7) | Apr 07, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | [10c9b38ed6](https://linux-hardware.org/?probe=10c9b38ed6) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| ASRock        | H61M-DGS                    | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| Gigabyte      | F2A55M-DS2                  | [fea5792a8b](https://linux-hardware.org/?probe=fea5792a8b) | Apr 06, 2023 |
| ASUSTek       | H170-PRO                    | [8756f8891c](https://linux-hardware.org/?probe=8756f8891c) | Apr 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9e99b4150b](https://linux-hardware.org/?probe=9e99b4150b) | Apr 06, 2023 |
| ASRock        | A320M-DVS R4.0              | [6da0293a4b](https://linux-hardware.org/?probe=6da0293a4b) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [d8dc8a37b1](https://linux-hardware.org/?probe=d8dc8a37b1) | Apr 04, 2023 |
| ASRock        | 990FX Extreme3              | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [de861c6d3f](https://linux-hardware.org/?probe=de861c6d3f) | Apr 03, 2023 |
| Acer          | Veriton X2632G V:1.0        | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| ASUSTek       | PRIME X470-PRO              | [96fcc41161](https://linux-hardware.org/?probe=96fcc41161) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| HP            | 2AFA                        | [d177838277](https://linux-hardware.org/?probe=d177838277) | Mar 31, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [fc9a42e387](https://linux-hardware.org/?probe=fc9a42e387) | Mar 31, 2023 |
| HP            | 3047h                       | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Gigabyte      | GA-780T-D3L                 | [4f523c6409](https://linux-hardware.org/?probe=4f523c6409) | Mar 28, 2023 |
| Lenovo        | NO DPK                      | [220c640743](https://linux-hardware.org/?probe=220c640743) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | [0901eb1e27](https://linux-hardware.org/?probe=0901eb1e27) | Mar 27, 2023 |
| ASUSTek       | P8H77-M                     | [6fc56d2339](https://linux-hardware.org/?probe=6fc56d2339) | Mar 25, 2023 |
| MSI           | A520M PRO                   | [c27ea21be5](https://linux-hardware.org/?probe=c27ea21be5) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| MSI           | MS-7255                     | [7322068101](https://linux-hardware.org/?probe=7322068101) | Mar 23, 2023 |
| Gigabyte      | P43-ES3G                    | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [db3e17d5f1](https://linux-hardware.org/?probe=db3e17d5f1) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASRock        | 970A-G                      | [52b0aa69ba](https://linux-hardware.org/?probe=52b0aa69ba) | Mar 20, 2023 |
| HP            | 18E7                        | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| Gigabyte      | A520M H                     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | 990FXA-UD5                  | [0daa99f732](https://linux-hardware.org/?probe=0daa99f732) | Mar 19, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| MSI           | H55M-P31                    | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.217     | [1e1a430355](https://linux-hardware.org/?probe=1e1a430355) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Pegatron      | 2AB5                        | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| ASUSTek       | CG5290                      | [e0ab58dbfe](https://linux-hardware.org/?probe=e0ab58dbfe) | Mar 16, 2023 |
| ASUSTek       | VC62B                       | [9bf2d226a8](https://linux-hardware.org/?probe=9bf2d226a8) | Mar 15, 2023 |
| MSI           | H61M-P20                    | [8129a4f5a4](https://linux-hardware.org/?probe=8129a4f5a4) | Mar 15, 2023 |
| ASRock        | G31M-S                      | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Gigabyte      | B85M-D3H-A                  | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Dell          | 00V62H A01                  | [a45ebd1b85](https://linux-hardware.org/?probe=a45ebd1b85) | Mar 12, 2023 |
| Pegatron      | 2AC2                        | [a6084e8904](https://linux-hardware.org/?probe=a6084e8904) | Mar 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | [d2b402f3c0](https://linux-hardware.org/?probe=d2b402f3c0) | Mar 11, 2023 |
| HP            | 0AA0h                       | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| ASRock        | H61M-ITX                    | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| ECS           | MCP61PM-GM                  | [ac561937e3](https://linux-hardware.org/?probe=ac561937e3) | Mar 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| Gigabyte      | P35-DS3L                    | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9b72e94139](https://linux-hardware.org/?probe=9b72e94139) | Mar 06, 2023 |
| Gigabyte      | Z370M D3H-CF                | [d000dc6718](https://linux-hardware.org/?probe=d000dc6718) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | [84e37e870d](https://linux-hardware.org/?probe=84e37e870d) | Mar 03, 2023 |
| Intel         | DB75EN AAG39650-302         | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [1da5b61697](https://linux-hardware.org/?probe=1da5b61697) | Mar 02, 2023 |
| ASUSTek       | F2A85-V PRO                 | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [a6af4042ea](https://linux-hardware.org/?probe=a6af4042ea) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| MSI           | B450M MORTAR MAX            | [0335729036](https://linux-hardware.org/?probe=0335729036) | Feb 27, 2023 |
| Intel         | H61                         | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| MSI           | NF750-G55                   | [f279251ffa](https://linux-hardware.org/?probe=f279251ffa) | Feb 27, 2023 |
| Acer          | EG43M                       | [d533c457eb](https://linux-hardware.org/?probe=d533c457eb) | Feb 26, 2023 |
| ASUSTek       | PRIME Q270M-C               | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| Dell          | 0VHWTR A01                  | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| MSI           | B360M PRO-VH                | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| MSI           | G41M-P33 Combo              | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9171567db4](https://linux-hardware.org/?probe=9171567db4) | Feb 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [b410c9f493](https://linux-hardware.org/?probe=b410c9f493) | Feb 24, 2023 |
| HP            | 1998                        | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| ASUSTek       | M2N-MX SE Plus              | [21aa20cd64](https://linux-hardware.org/?probe=21aa20cd64) | Feb 24, 2023 |
| Gigabyte      | Z97-HD3                     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [cfe5ecec44](https://linux-hardware.org/?probe=cfe5ecec44) | Feb 23, 2023 |
| Biostar       | N68S3B                      | [4572b3d965](https://linux-hardware.org/?probe=4572b3d965) | Feb 23, 2023 |
| Foxconn       | 2ADA                        | [75b2eb9c1f](https://linux-hardware.org/?probe=75b2eb9c1f) | Feb 23, 2023 |
| Gigabyte      | H81M-S2PV                   | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Gigabyte      | X570 GAMING X               | [4803e8ee01](https://linux-hardware.org/?probe=4803e8ee01) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9523a0ccc2](https://linux-hardware.org/?probe=9523a0ccc2) | Feb 22, 2023 |
| ASUSTek       | M5A78L/USB3                 | [b4288b76ee](https://linux-hardware.org/?probe=b4288b76ee) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| ASUSTek       | PRIME Z390-P                | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| MSI           | G41M-P23                    | [04211b9202](https://linux-hardware.org/?probe=04211b9202) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASRock        | 880GM-LE FX                 | [db290cd703](https://linux-hardware.org/?probe=db290cd703) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| ASRock        | 880GM-LE FX                 | [1d45a444a3](https://linux-hardware.org/?probe=1d45a444a3) | Feb 18, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [3ed988e135](https://linux-hardware.org/?probe=3ed988e135) | Feb 17, 2023 |
| Gigabyte      | H87M-HD3                    | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| EVGA          | 151-IB-E699                 | [9e975c7966](https://linux-hardware.org/?probe=9e975c7966) | Feb 17, 2023 |
| Pegatron      | IPM31G                      | [42d112d7e0](https://linux-hardware.org/?probe=42d112d7e0) | Feb 17, 2023 |
| HP            | 2820h                       | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| MSI           | H61M-E33                    | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | B350M PRO-VD PLUS           | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M91 4518E4S     | [91b1fb7e03](https://linux-hardware.org/?probe=91b1fb7e03) | Feb 16, 2023 |
| Philco        | DTC-A55                     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| ASUSTek       | H81T                        | [51aa090e9a](https://linux-hardware.org/?probe=51aa090e9a) | Feb 16, 2023 |
| HP            | 3031h                       | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| MSI           | MS-7235                     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Gigabyte      | P43-ES3G                    | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| ASUSTek       | PRIME B365M-K               | [20b88dda19](https://linux-hardware.org/?probe=20b88dda19) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| MSI           | Z97-G45 GAMING              | [f9318d4390](https://linux-hardware.org/?probe=f9318d4390) | Feb 14, 2023 |
| ASRock        | E350M1                      | [ac69adceb6](https://linux-hardware.org/?probe=ac69adceb6) | Feb 13, 2023 |
| ASUSTek       | P7P55D-E EVO                | [f1ec250753](https://linux-hardware.org/?probe=f1ec250753) | Feb 13, 2023 |
| Dell          | 0YXT71 A01                  | [cdc2dedbcd](https://linux-hardware.org/?probe=cdc2dedbcd) | Feb 13, 2023 |
| HP            | 3031h                       | [f9a0848388](https://linux-hardware.org/?probe=f9a0848388) | Feb 11, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f0f4d31de2](https://linux-hardware.org/?probe=f0f4d31de2) | Feb 10, 2023 |
| Medion        | TJ4105                      | [cd654518c0](https://linux-hardware.org/?probe=cd654518c0) | Feb 09, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [8532f05156](https://linux-hardware.org/?probe=8532f05156) | Feb 09, 2023 |
| HP            | 1905                        | [a442e1de06](https://linux-hardware.org/?probe=a442e1de06) | Feb 07, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| Dell          | 084J0R A00                  | [7fe633b52f](https://linux-hardware.org/?probe=7fe633b52f) | Feb 05, 2023 |
| ASUSTek       | Z97-K                       | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| Dell          | 0773VG A00                  | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| HP            | 3048h                       | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| AZW           | U59                         | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| Gigabyte      | N3050ND3H                   | [1663928526](https://linux-hardware.org/?probe=1663928526) | Jan 21, 2023 |
| ASUSTek       | Z77-A                       | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| ASUSTek       | C60M1-I                     | [defd3912ae](https://linux-hardware.org/?probe=defd3912ae) | Jan 18, 2023 |
| Unknown       | HX90                        | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| Medion        | MS-7621                     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Gigabyte      | F2A55M-HD2                  | [74a62575d2](https://linux-hardware.org/?probe=74a62575d2) | Jan 17, 2023 |
| ASUSTek       | P8B75-V                     | [276102bb1a](https://linux-hardware.org/?probe=276102bb1a) | Jan 16, 2023 |
| Lenovo        | SDK0F82993 WIN              | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| HP            | 8054                        | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| HP            | 18E5                        | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [12f29d53ba](https://linux-hardware.org/?probe=12f29d53ba) | Jan 13, 2023 |
| Gigabyte      | H81M-S2PV                   | [72e7e2e1cf](https://linux-hardware.org/?probe=72e7e2e1cf) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| Gigabyte      | H170-D3H-CF                 | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| HP            | 0AA4h                       | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| HP            | 802F                        | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| HP            | 8265                        | [83897e98cf](https://linux-hardware.org/?probe=83897e98cf) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| Alienware     | 04VWF2 A02                  | [15f4ed4e31](https://linux-hardware.org/?probe=15f4ed4e31) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Pegatron      | 2AC3                        | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| Dell          | 0M5DCD A00                  | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| MSI           | A88X-G45 GAMING             | [1caf5c85d9](https://linux-hardware.org/?probe=1caf5c85d9) | Jan 04, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [55627fc077](https://linux-hardware.org/?probe=55627fc077) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Dell          | 0XCR8D A03                  | [faccba61cf](https://linux-hardware.org/?probe=faccba61cf) | Jan 03, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [afe5105302](https://linux-hardware.org/?probe=afe5105302) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| Dell          | 0MM599                      | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| ASRock        | B450M-HDV R4.0              | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| AZW           | MINI S                      | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Gigabyte      | B550M DS3H                  | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| OEM           | Intel H81                   | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | UN45                        | [bde2e2efb1](https://linux-hardware.org/?probe=bde2e2efb1) | Dec 31, 2022 |
| MSI           | MS-7502 Fab D               | [9126e1035f](https://linux-hardware.org/?probe=9126e1035f) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [3258ffa0c1](https://linux-hardware.org/?probe=3258ffa0c1) | Dec 29, 2022 |
| Gigabyte      | H61M-D2H                    | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | [3f0c89985c](https://linux-hardware.org/?probe=3f0c89985c) | Dec 29, 2022 |
| Gigabyte      | MJPLNBB-00                  | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Pegatron      | APX85-GS                    | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Acer          | Aspire TC-865 V:1.1         | [0c8add55fe](https://linux-hardware.org/?probe=0c8add55fe) | Dec 27, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Lenovo        | SHARKBAY NOK                | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | 2AF7                        | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Gigabyte      | B450M S2H                   | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| Dell          | 0J3C2F A00                  | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| MSI           | 880GM-E41                   | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [003ac98d7f](https://linux-hardware.org/?probe=003ac98d7f) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Dell          | 0VHWTR A01                  | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ECS           | G31T-M7                     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| MSI           | H81M-E34                    | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [71ebf721cc](https://linux-hardware.org/?probe=71ebf721cc) | Dec 17, 2022 |
| HP            | 8055                        | [6c7fa83dc9](https://linux-hardware.org/?probe=6c7fa83dc9) | Dec 17, 2022 |
| Dell          | 0RW203                      | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Gigabyte      | F2A85X-UP4                  | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Acer          | Veriton N2620G              | [a626bf668e](https://linux-hardware.org/?probe=a626bf668e) | Dec 15, 2022 |
| Toshiba       | STI 006998G                 | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| HP            | 2AFB                        | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0VD92X A00                  | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Datto         | SSD                         | [a9bff0a51c](https://linux-hardware.org/?probe=a9bff0a51c) | Dec 14, 2022 |
| HP            | 304Ah                       | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| ECS           | H61H2-M2                    | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| Dell          | 0T10XW A02                  | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| Gigabyte      | H310M S2V                   | [6895902fe7](https://linux-hardware.org/?probe=6895902fe7) | Dec 12, 2022 |
| ASUSTek       | AM1M-A                      | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [62f6fd5f8d](https://linux-hardware.org/?probe=62f6fd5f8d) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| Dell          | 0KG317                      | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| ASUSTek       | P8Z77-V LX                  | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Dell          | 01TKCC A01                  | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| HP            | 18E7                        | [9759493e06](https://linux-hardware.org/?probe=9759493e06) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| Dell          | 0P301D A02                  | [8ab7a916f1](https://linux-hardware.org/?probe=8ab7a916f1) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| ASRock        | B550 Taichi                 | [0203e79add](https://linux-hardware.org/?probe=0203e79add) | Dec 08, 2022 |
| Gigabyte      | Z370M D3H-CF                | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| Acer          | Aspire X3950                | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| ASUSTek       | H97-PLUS                    | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| HP            | 8648                        | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Medion        | MS-7800                     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ECS           | 945P/PL-A                   | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| ASRock        | B550M-ITX/ac                | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| MSI           | P55-CD53                    | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| HP            | 3397                        | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| HP            | 1589                        | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| HP            | 2215                        | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Wistron       | ProLiant ML110 G6           | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| Foxconn       | 2A92                        | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Intel         | DG41TY AAE47335-302         | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| HP            | 3399                        | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Shuttle       | FS61                        | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| ECS           | G41T-M7                     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| ASUSTek       | P5KPL/1600                  | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| HP            | 843B                        | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| AZW           | Gemini M                    | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| ASUSTek       | H81M-A                      | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| HP            | 22F8                        | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| HP            | 84FD                        | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| ASUSTek       | P5K SE/EPU                  | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Acer          | RS880M05                    | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire X1700                | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASRock        | Z170 Extreme4               | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| HP            | 2820h                       | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| VS Company    | MCP61M                      | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| ASUSTek       | H170I-PLUS D3               | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| ASUSTek       | PRIME B365M-K               | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Acer          | Aspire X1430                | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| MSI           | P45 Platinum                | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| Unknown       | Unknown                     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| ASUSTek       | P8B75-V                     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| Acer          | Veriton M275                | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| Dell          | 0GX297                      | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Dell          | 0HX555                      | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| MSI           | H61M-P20                    | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| HP            | 1825                        | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| HP            | 805D                        | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| Dell          | 02YYK5 A01                  | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| ASRock        | Z87 Pro3                    | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| HP            | 1850                        | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| ASUSTek       | PRIME H510M-A               | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A II            | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| HP            | 1497                        | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| AMD           | A88                         | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Dell          | 0T656F A01                  | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| Acer          | Aspire XC-230               | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| MSI           | A55M-P33                    | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| Medion        | MS-7797                     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | 18E4                        | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Dell          | 01TKCC A01                  | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Intel         | H55                         | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| MSI           | A75A-G35                    | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Biostar       | A75MG                       | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| MSI           | B75MA-E33                   | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| MSI           | MS-7235                     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| ASRock        | B450M Pro4-F                | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Acer          | Batman A01                  | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Acer          | Veriton M275                | [f871926a8e](https://linux-hardware.org/?probe=f871926a8e) | Sep 29, 2022 |
| Intel         | DQ67SW AAG12527-310         | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [5a7ad7dba9](https://linux-hardware.org/?probe=5a7ad7dba9) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| Dell          | 0NV0M7 A02                  | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0M5DCD A00                  | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| HP            | 2B34                        | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | 2B29                        | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| HP            | 1495                        | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Gigabyte      | X570 AORUS PRO              | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [0937dcb89c](https://linux-hardware.org/?probe=0937dcb89c) | Sep 12, 2022 |
| ASRock        | X99 Taichi                  | [2eb979e980](https://linux-hardware.org/?probe=2eb979e980) | Sep 12, 2022 |
| Dell          | 0H8052                      | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Gigabyte      | EX58-UD3R                   | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | 158B                        | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| HP            | 304Bh                       | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| MSI           | B560M PRO                   | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| MSI           | 0A48                        | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Dell          | 03NVJ6 A00                  | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Gigabyte      | Z68AP-D3                    | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Apple         | Mac-F221BEC8                | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Gigabyte      | A520M DS3H                  | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| ASRock        | Z170 Extreme4               | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| MSI           | A320M PRO-M2 V2             | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| MSI           | B350M PRO-VDH               | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| HP            | 8076                        | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Unknown       | Unknown                     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b36d7be7c1](https://linux-hardware.org/?probe=b36d7be7c1) | Sep 04, 2022 |
| HP            | 304Bh                       | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| Gigabyte      | H97N-WIFI                   | [fb64be85f1](https://linux-hardware.org/?probe=fb64be85f1) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [792cbc3418](https://linux-hardware.org/?probe=792cbc3418) | Sep 04, 2022 |
| HP            | 8767 A                      | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| Gigabyte      | B560 AORUS PRO AX           | [fbd2e39516](https://linux-hardware.org/?probe=fbd2e39516) | Sep 04, 2022 |
| ECS           | H61H-G11/7.0                | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| Unknown       | Intel X79                   | [9e666e1530](https://linux-hardware.org/?probe=9e666e1530) | Sep 02, 2022 |
| HP            | 8053                        | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| Dell          | 0TP412                      | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | [c9a801a4d2](https://linux-hardware.org/?probe=c9a801a4d2) | Sep 01, 2022 |
| ASRock        | X99 Taichi                  | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| ASRock        | B550M-ITX/ac                | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| MSI           | H510M-A PRO                 | [120400698e](https://linux-hardware.org/?probe=120400698e) | Aug 31, 2022 |
| Vorke         | V1 Plus                     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | Z97 GAMING 7                | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| ASRock        | N68C-S UCC                  | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| HP            | 0A60h                       | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [33aaa7baf4](https://linux-hardware.org/?probe=33aaa7baf4) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | [0099ab3432](https://linux-hardware.org/?probe=0099ab3432) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| ASUSTek       | A88XM-A                     | [d8a4e4d954](https://linux-hardware.org/?probe=d8a4e4d954) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | [a18db0fafd](https://linux-hardware.org/?probe=a18db0fafd) | Aug 27, 2022 |
| ASUSTek       | P8B WS                      | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [67712f11d9](https://linux-hardware.org/?probe=67712f11d9) | Aug 27, 2022 |
| ASUSTek       | PRIME Z390-A                | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| MSI           | G31TM-P21                   | [cf0bc232f5](https://linux-hardware.org/?probe=cf0bc232f5) | Aug 26, 2022 |
| ASRock        | FM2A68M-HD+                 | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| MSI           | 760GM-P21                   | [7e45cde899](https://linux-hardware.org/?probe=7e45cde899) | Aug 26, 2022 |
| HP            | 1497                        | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| Dell          | 0RJ290                      | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| ASRock        | N68C-GS4 FX                 | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| OEM           | A320                        | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| HP            | 21D0                        | [1bd58d519c](https://linux-hardware.org/?probe=1bd58d519c) | Aug 24, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Gigabyte      | F2A68HM-H                   | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Dell          | 08HPGT A01                  | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| ICP / iEi     | B217 V1.0                   | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Dell          | 0YJPT1 A00                  | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [fa5f1121d5](https://linux-hardware.org/?probe=fa5f1121d5) | Aug 22, 2022 |
| Intel         | H61                         | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| ASUSTek       | Z87-C                       | [8de83c544f](https://linux-hardware.org/?probe=8de83c544f) | Aug 21, 2022 |
| HP            | 1998                        | [69b6b04268](https://linux-hardware.org/?probe=69b6b04268) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| Gigabyte      | B365M DS3H WIFI             | [142e25352d](https://linux-hardware.org/?probe=142e25352d) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| AZW           | MII-V                       | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| OEM           | Intel H81                   | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| ASUSTek       | P5KPL-VM                    | [803031cd3b](https://linux-hardware.org/?probe=803031cd3b) | Aug 19, 2022 |
| Gigabyte      | B450M S2H                   | [a0a7a845e3](https://linux-hardware.org/?probe=a0a7a845e3) | Aug 18, 2022 |
| Gigabyte      | P43-ES3G                    | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Acer          | MRS600M                     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASUSTek       | PRIME B250-PRO              | [870d7102f5](https://linux-hardware.org/?probe=870d7102f5) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| Gigabyte      | H81M-S2PH                   | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H                  | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| Dell          | 0T656F A01                  | [ec4014a549](https://linux-hardware.org/?probe=ec4014a549) | Aug 16, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| HP            | 2AE2                        | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| Dell          | 0NC2VH A01                  | [170b178361](https://linux-hardware.org/?probe=170b178361) | Aug 15, 2022 |
| HP            | 18E7                        | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| ASRock        | 960GM-VGS3 FX               | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| MSI           | X570-A PRO                  | [30146876c6](https://linux-hardware.org/?probe=30146876c6) | Aug 14, 2022 |
| ASRock        | J3455-ITX                   | [4386fccad1](https://linux-hardware.org/?probe=4386fccad1) | Aug 14, 2022 |
| Lenovo        | SHARKBAY NOK                | [ee169e47b3](https://linux-hardware.org/?probe=ee169e47b3) | Aug 13, 2022 |
| Dell          | 08WKV3 A00                  | [4e57c20454](https://linux-hardware.org/?probe=4e57c20454) | Aug 13, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| HP            | 1850                        | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| ASRock        | H61M-DGS                    | [50b7221c5a](https://linux-hardware.org/?probe=50b7221c5a) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| Gigabyte      | EP35C-DS3R                  | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| ASRock        | Z97M Pro4                   | [245d189a61](https://linux-hardware.org/?probe=245d189a61) | Aug 11, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [73bf30c596](https://linux-hardware.org/?probe=73bf30c596) | Aug 11, 2022 |
| Gigabyte      | P35-DS3L                    | [c765f5b81c](https://linux-hardware.org/?probe=c765f5b81c) | Aug 11, 2022 |
| Foxconn       | 2ABF                        | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| Dell          | 07KY25 A00                  | [676025f81a](https://linux-hardware.org/?probe=676025f81a) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| MSI           | X470 GAMING M7 AC           | [58947090d5](https://linux-hardware.org/?probe=58947090d5) | Aug 09, 2022 |
| eMachines     | Veriton V2110               | [3492540d77](https://linux-hardware.org/?probe=3492540d77) | Aug 09, 2022 |
| ASRock        | AB350 Pro4                  | [2df31a9fbf](https://linux-hardware.org/?probe=2df31a9fbf) | Aug 09, 2022 |
| ASUSTek       | Z87-PRO                     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | [642e31466d](https://linux-hardware.org/?probe=642e31466d) | Aug 08, 2022 |
| Dell          | 0782GW A01                  | [b3ebc3aed3](https://linux-hardware.org/?probe=b3ebc3aed3) | Aug 08, 2022 |
| HP            | 304Bh                       | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| Intel         | H61                         | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| Gigabyte      | EP45-UD3R                   | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| ASUSTek       | M3A78 PRO                   | [0b63e92a55](https://linux-hardware.org/?probe=0b63e92a55) | Aug 07, 2022 |
| HP            | 2215                        | [75304ada6c](https://linux-hardware.org/?probe=75304ada6c) | Aug 06, 2022 |
| Toshiba       | STI 006998G                 | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| ASRock        | H110M-STX                   | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Gigabyte      | A320M-H-CF                  | [4015089c1e](https://linux-hardware.org/?probe=4015089c1e) | Aug 06, 2022 |
| MSI           | 2A9C                        | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| Dell          | 0NV0M7 A02                  | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | A520M S2H                   | [daa1f68f01](https://linux-hardware.org/?probe=daa1f68f01) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| MSI           | Z87-G43 GAMING              | [490239de9e](https://linux-hardware.org/?probe=490239de9e) | Aug 05, 2022 |
| Dell          | 0GY6Y8 A01                  | [1ad9e54625](https://linux-hardware.org/?probe=1ad9e54625) | Aug 05, 2022 |
| ASUSTek       | M2N68-AM SE2                | [b68c110fde](https://linux-hardware.org/?probe=b68c110fde) | Aug 05, 2022 |
| ASRock        | A300M-STX                   | [f6b820d15f](https://linux-hardware.org/?probe=f6b820d15f) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| Dell          | 0KG317                      | [65c105e2be](https://linux-hardware.org/?probe=65c105e2be) | Aug 04, 2022 |
| ASUSTek       | A68HM-K                     | [d5d981cf7b](https://linux-hardware.org/?probe=d5d981cf7b) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Unknown       | Unknown                     | [0725792da0](https://linux-hardware.org/?probe=0725792da0) | Aug 04, 2022 |
| Gigabyte      | B360M GAMING HD             | [95e1eb0fcb](https://linux-hardware.org/?probe=95e1eb0fcb) | Aug 03, 2022 |
| Lenovo        | 3102                        | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Gigabyte      | Z170X-UD3-CF                | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| HP            | 2B29                        | [5fcf3a8320](https://linux-hardware.org/?probe=5fcf3a8320) | Aug 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| Acer          | EM61SM/EM61PM               | [1a35a6d7dc](https://linux-hardware.org/?probe=1a35a6d7dc) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H61M-S2PH                   | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| Gigabyte      | H87-HD3                     | [daaf600950](https://linux-hardware.org/?probe=daaf600950) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| HP            | 339A                        | [251a764917](https://linux-hardware.org/?probe=251a764917) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| MSI           | Z590-A PRO                  | [7051f56dda](https://linux-hardware.org/?probe=7051f56dda) | Aug 01, 2022 |
| MSI           | Z77A-GD65                   | [fcadad42a5](https://linux-hardware.org/?probe=fcadad42a5) | Aug 01, 2022 |
| HP            | 843F                        | [eeba83fecb](https://linux-hardware.org/?probe=eeba83fecb) | Aug 01, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [7e6cd7bcb3](https://linux-hardware.org/?probe=7e6cd7bcb3) | Jul 31, 2022 |
| ASUSTek       | P8B75-M LX                  | [653f46c8e3](https://linux-hardware.org/?probe=653f46c8e3) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| MSI           | B85M-P33                    | [6e9af1d1e4](https://linux-hardware.org/?probe=6e9af1d1e4) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [cb7c9442d6](https://linux-hardware.org/?probe=cb7c9442d6) | Jul 31, 2022 |
| Unknown       | Unknown                     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| ASUSTek       | Z97-A-USB31                 | [25db3983fe](https://linux-hardware.org/?probe=25db3983fe) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| ASRock        | J5040-ITX                   | [2cc4fd5d75](https://linux-hardware.org/?probe=2cc4fd5d75) | Jul 30, 2022 |
| ASUSTek       | M3A78 PRO                   | [c30fca013c](https://linux-hardware.org/?probe=c30fca013c) | Jul 30, 2022 |
| HP            | 2ADC                        | [86608333bc](https://linux-hardware.org/?probe=86608333bc) | Jul 29, 2022 |
| PCWare        | IPMH61R2                    | [b3245af28d](https://linux-hardware.org/?probe=b3245af28d) | Jul 29, 2022 |
| HP            | 0AA0h                       | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| HP            | 18E4                        | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e1d666e84a](https://linux-hardware.org/?probe=e1d666e84a) | Jul 29, 2022 |
| Dell          | OptiPlex 780                | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| ASRock        | Z97 Anniversary             | [768b11cbe4](https://linux-hardware.org/?probe=768b11cbe4) | Jul 28, 2022 |
| MSI           | G31TM-P35                   | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| MSI           | AM1I                        | [63e6d4040e](https://linux-hardware.org/?probe=63e6d4040e) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| ASUSTek       | H110M-A/M.2                 | [93ad7b0efb](https://linux-hardware.org/?probe=93ad7b0efb) | Jul 28, 2022 |
| ASRock        | B450M Steel Legend          | [db492973ec](https://linux-hardware.org/?probe=db492973ec) | Jul 28, 2022 |
| ASRock        | A320M-HDV                   | [cc72c3c914](https://linux-hardware.org/?probe=cc72c3c914) | Jul 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [24e94dd87e](https://linux-hardware.org/?probe=24e94dd87e) | Jul 28, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [0068653ca3](https://linux-hardware.org/?probe=0068653ca3) | Jul 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [d64175b64b](https://linux-hardware.org/?probe=d64175b64b) | Jul 28, 2022 |
| ASRock        | A88M-ITX/ac                 | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| Acer          | Aspire X1930                | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d0ef6d20cf](https://linux-hardware.org/?probe=d0ef6d20cf) | Jul 27, 2022 |
| Foxconn       | A76ML-K 30                  | [7b118c6a6b](https://linux-hardware.org/?probe=7b118c6a6b) | Jul 27, 2022 |
| Dell          | 09KPNV A00                  | [610282a0e6](https://linux-hardware.org/?probe=610282a0e6) | Jul 27, 2022 |
| Dell          | 0YF8P5 A00                  | [04ebe8cd88](https://linux-hardware.org/?probe=04ebe8cd88) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| HP            | 1495                        | [61a8f473e2](https://linux-hardware.org/?probe=61a8f473e2) | Jul 27, 2022 |
| MSI           | B250M PRO-VDH               | [eb1ff40d2d](https://linux-hardware.org/?probe=eb1ff40d2d) | Jul 27, 2022 |
| ASUSTek       | Z97-P                       | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| Gigabyte      | H55M-S2H                    | [a9a6ab85ac](https://linux-hardware.org/?probe=a9a6ab85ac) | Jul 27, 2022 |
| Dell          | 0NW6H5 A00                  | [b76e9e02fa](https://linux-hardware.org/?probe=b76e9e02fa) | Jul 27, 2022 |
| Gigabyte      | H81M-HD3                    | [0cfb15d654](https://linux-hardware.org/?probe=0cfb15d654) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| Acer          | IPXHW-RL                    | [d99b7cb71e](https://linux-hardware.org/?probe=d99b7cb71e) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [e487b063ea](https://linux-hardware.org/?probe=e487b063ea) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| Dell          | 0C27VV A03                  | [c1c4edd1e5](https://linux-hardware.org/?probe=c1c4edd1e5) | Jul 26, 2022 |
| Dell          | 042P49 A01                  | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| Login Info... | LOG-H310M-G                 | [f02a0ed6dd](https://linux-hardware.org/?probe=f02a0ed6dd) | Jul 26, 2022 |
| Acer          | Aspire XC-830               | [02572035c8](https://linux-hardware.org/?probe=02572035c8) | Jul 26, 2022 |
| Dell          | 04YP6J A02                  | [8161693c82](https://linux-hardware.org/?probe=8161693c82) | Jul 26, 2022 |
| Pegatron      | 2AE2                        | [772ded1d83](https://linux-hardware.org/?probe=772ded1d83) | Jul 25, 2022 |
| Dell          | 0V8WGR A01                  | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Acer          | EM61SM/EM61PM               | [e470dff38f](https://linux-hardware.org/?probe=e470dff38f) | Jul 25, 2022 |
| Lenovo        | ThinkCentre M58p 6137B28    | [5473e97fa6](https://linux-hardware.org/?probe=5473e97fa6) | Jul 25, 2022 |
| Gigabyte      | H170M-D3H-GSM-CF            | [ace82a6273](https://linux-hardware.org/?probe=ace82a6273) | Jul 25, 2022 |
| Gigabyte      | G31M-S2L                    | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| Wistron       | ProLiant ML110 G5           | [fdb0300292](https://linux-hardware.org/?probe=fdb0300292) | Jul 24, 2022 |
| Dell          | 0VHWTR A01                  | [9796d6eca3](https://linux-hardware.org/?probe=9796d6eca3) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [7af6c5cebe](https://linux-hardware.org/?probe=7af6c5cebe) | Jul 24, 2022 |
| ASRock        | AB350 Pro4                  | [7bb0cce634](https://linux-hardware.org/?probe=7bb0cce634) | Jul 24, 2022 |
| MSI           | X470 GAMING PLUS            | [ea3f7e3b48](https://linux-hardware.org/?probe=ea3f7e3b48) | Jul 23, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| ASRock        | A300M-STX                   | [bad4adf823](https://linux-hardware.org/?probe=bad4adf823) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| Pegatron      | NARRA5                      | [368503425d](https://linux-hardware.org/?probe=368503425d) | Jul 23, 2022 |
| ASUSTek       | P7H55-M/USB3                | [7e7606e64d](https://linux-hardware.org/?probe=7e7606e64d) | Jul 23, 2022 |
| HP            | 0A68h                       | [cc4b39e6d0](https://linux-hardware.org/?probe=cc4b39e6d0) | Jul 22, 2022 |
| Lenovo        | MAHOBAY NOK                 | [8fc99169c3](https://linux-hardware.org/?probe=8fc99169c3) | Jul 22, 2022 |
| Gigabyte      | B75M-D3H                    | [80dcd8a0f7](https://linux-hardware.org/?probe=80dcd8a0f7) | Jul 22, 2022 |
| Gigabyte      | Z87-HD3                     | [e6bf6ea62f](https://linux-hardware.org/?probe=e6bf6ea62f) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| HP            | 1998                        | [82c8302941](https://linux-hardware.org/?probe=82c8302941) | Jul 21, 2022 |
| Lenovo        | 1.0                         | [e520e716cf](https://linux-hardware.org/?probe=e520e716cf) | Jul 21, 2022 |
| ASUSTek       | H110M-R                     | [34942a8abc](https://linux-hardware.org/?probe=34942a8abc) | Jul 20, 2022 |
| ECS           | H61H2-M2                    | [c1d1e739cf](https://linux-hardware.org/?probe=c1d1e739cf) | Jul 20, 2022 |
| Acer          | Veriton M290                | [647393aa0c](https://linux-hardware.org/?probe=647393aa0c) | Jul 20, 2022 |
| PCChips       | A15G                        | [4cdd689308](https://linux-hardware.org/?probe=4cdd689308) | Jul 20, 2022 |
| ASRock        | B450M-HDV                   | [e45f2cd5d8](https://linux-hardware.org/?probe=e45f2cd5d8) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [bece300d92](https://linux-hardware.org/?probe=bece300d92) | Jul 20, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [55fdb6713c](https://linux-hardware.org/?probe=55fdb6713c) | Jul 19, 2022 |
| Acer          | Veriton M2110G              | [060e101a26](https://linux-hardware.org/?probe=060e101a26) | Jul 19, 2022 |
| ASUSTek       | H110M-R                     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Gigabyte      | P31-DS3L                    | [3b8118fb89](https://linux-hardware.org/?probe=3b8118fb89) | Jul 19, 2022 |
| Gigabyte      | B365M H                     | [879d413452](https://linux-hardware.org/?probe=879d413452) | Jul 19, 2022 |
| Gigabyte      | Z590 GAMING X               | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| ASUSTek       | M4A78                       | [d04747e05b](https://linux-hardware.org/?probe=d04747e05b) | Jul 17, 2022 |
| HP            | 8906 SMVB                   | [3b89e3e952](https://linux-hardware.org/?probe=3b89e3e952) | Jul 17, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | [3e2c54f9f1](https://linux-hardware.org/?probe=3e2c54f9f1) | Jul 17, 2022 |
| Foxconn       | 2ABF                        | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [478e424482](https://linux-hardware.org/?probe=478e424482) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| ASUSTek       | P5QLD PRO                   | [fbf3a31304](https://linux-hardware.org/?probe=fbf3a31304) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| Intel         | DQ77MK AAG39642-500         | [7b6a43a9f1](https://linux-hardware.org/?probe=7b6a43a9f1) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [775050f5d9](https://linux-hardware.org/?probe=775050f5d9) | Jul 15, 2022 |
| MSI           | H110M PRO-VD PLUS           | [03eaa344c6](https://linux-hardware.org/?probe=03eaa344c6) | Jul 15, 2022 |
| MSI           | G41M-P28                    | [8bd39aa164](https://linux-hardware.org/?probe=8bd39aa164) | Jul 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [20ea8fab3f](https://linux-hardware.org/?probe=20ea8fab3f) | Jul 14, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [eebcfac8a3](https://linux-hardware.org/?probe=eebcfac8a3) | Jul 14, 2022 |
| MSI           | B250M PRO-VH                | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| Foxconn       | 945 7MD Series              | [30585b93f0](https://linux-hardware.org/?probe=30585b93f0) | Jul 13, 2022 |
| Dell          | 048DY8 A01                  | [aad36ba2cd](https://linux-hardware.org/?probe=aad36ba2cd) | Jul 13, 2022 |
| Intel         | DH55TC AAE70932-303         | [0005417882](https://linux-hardware.org/?probe=0005417882) | Jul 13, 2022 |
| Gigabyte      | A320M-H-CF                  | [9b24417251](https://linux-hardware.org/?probe=9b24417251) | Jul 12, 2022 |
| Gigabyte      | H310M S2H x.x               | [8dbe4d55a5](https://linux-hardware.org/?probe=8dbe4d55a5) | Jul 11, 2022 |
| Colorful T... | H310M-T PRO V21             | [b922e2142b](https://linux-hardware.org/?probe=b922e2142b) | Jul 11, 2022 |
| HP            | 339A                        | [a4606d9234](https://linux-hardware.org/?probe=a4606d9234) | Jul 10, 2022 |
| ASRock        | N68C-S UCC                  | [8c5338cc67](https://linux-hardware.org/?probe=8c5338cc67) | Jul 10, 2022 |
| ASRock        | AMCP7A-ION                  | [339f0e7944](https://linux-hardware.org/?probe=339f0e7944) | Jul 10, 2022 |
| Acer          | FMCP7AM                     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| ASUSTek       | A8N-VM CSM                  | [3cf6a895cd](https://linux-hardware.org/?probe=3cf6a895cd) | Jul 10, 2022 |
| Gigabyte      | GA-A75-UD4H                 | [eba82e4b87](https://linux-hardware.org/?probe=eba82e4b87) | Jul 10, 2022 |
| Gigabyte      | P35-DS3L                    | [67182580cc](https://linux-hardware.org/?probe=67182580cc) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ee629832da](https://linux-hardware.org/?probe=ee629832da) | Jul 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003       | 1993     | 91.3%   |
| 5.16.13-desktop-1omv4003      | 178      | 8.15%   |
| 5.17.1-desktop-2omv4050       | 2        | 0.09%   |
| 5.16.5-desktop-2omv4003       | 2        | 0.09%   |
| 5.16.3-desktop-2omv4050       | 2        | 0.09%   |
| 5.10.14-desktop-1omv4002      | 2        | 0.09%   |
| 5.17.7-desktop-1omv4090       | 1        | 0.05%   |
| 5.16.7-desktop-clang-1omv4003 | 1        | 0.05%   |
| 5.16.13-desktop-1omv4050      | 1        | 0.05%   |
| 5.11.12-desktop-1omv4002      | 1        | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.7  | 1994     | 91.34%  |
| 5.16.13 | 179      | 8.2%    |
| 5.17.1  | 2        | 0.09%   |
| 5.16.5  | 2        | 0.09%   |
| 5.16.3  | 2        | 0.09%   |
| 5.10.14 | 2        | 0.09%   |
| 5.17.7  | 1        | 0.05%   |
| 5.11.12 | 1        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 2141     | 99.72%  |
| 5.17    | 3        | 0.14%   |
| 5.10    | 2        | 0.09%   |
| 5.11    | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2147     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 2142     | 99.63%  |
| LXQt     | 3        | 0.14%   |
| Unknown  | 3        | 0.14%   |
| Cinnamon | 2        | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2124     | 98.93%  |
| Wayland | 23       | 1.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SDDM | 2147     | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 1169     | 54.02%  |
| de_DE | 196      | 9.06%   |
| ru_RU | 155      | 7.16%   |
| fr_FR | 105      | 4.85%   |
| pt_BR | 94       | 4.34%   |
| pl_PL | 67       | 3.1%    |
| it_IT | 48       | 2.22%   |
| es_ES | 41       | 1.89%   |
| en_GB | 39       | 1.8%    |
| es_AR | 30       | 1.39%   |
| es_MX | 21       | 0.97%   |
| cs_CZ | 19       | 0.88%   |
| de_AT | 18       | 0.83%   |
| en_IN | 16       | 0.74%   |
| hu_HU | 13       | 0.6%    |
| tr_TR | 10       | 0.46%   |
| en_CA | 10       | 0.46%   |
| fr_CA | 9        | 0.42%   |
| es_CO | 9        | 0.42%   |
| en_AU | 9        | 0.42%   |
| ru_UA | 8        | 0.37%   |
| pt_PT | 7        | 0.32%   |
| nl_NL | 6        | 0.28%   |
| de_CH | 6        | 0.28%   |
| da_DK | 6        | 0.28%   |
| fr_BE | 5        | 0.23%   |
| es_VE | 5        | 0.23%   |
| es_CL | 5        | 0.23%   |
| es_PE | 4        | 0.18%   |
| nb_NO | 3        | 0.14%   |
| es_CR | 3        | 0.14%   |
| uk_UA | 2        | 0.09%   |
| fr_CH | 2        | 0.09%   |
| es_UY | 2        | 0.09%   |
| es_SV | 2        | 0.09%   |
| es_DO | 2        | 0.09%   |
| en_ZA | 2        | 0.09%   |
| en_IL | 2        | 0.09%   |
| en_HK | 2        | 0.09%   |
| ar_SA | 2        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1195     | 55.56%  |
| EFI  | 956      | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 1759     | 80.43%  |
| Ext4     | 417      | 19.07%  |
| Xfs      | 3        | 0.14%   |
| Btrfs    | 3        | 0.14%   |
| F2fs     | 2        | 0.09%   |
| Reiserfs | 1        | 0.05%   |
| Jfs      | 1        | 0.05%   |
| Ext3     | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1337     | 61.9%   |
| MBR     | 805      | 37.27%  |
| Unknown | 18       | 0.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1333     | 61.57%  |
| No        | 832      | 38.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1214     | 56.36%  |
| No        | 940      | 43.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 480      | 22.36%  |
| Gigabyte Technology | 402      | 18.72%  |
| MSI                 | 240      | 11.18%  |
| ASRock              | 190      | 8.85%   |
| Hewlett-Packard     | 177      | 8.24%   |
| Dell                | 166      | 7.73%   |
| Lenovo              | 91       | 4.24%   |
| Intel               | 67       | 3.12%   |
| Acer                | 58       | 2.7%    |
| Fujitsu             | 32       | 1.49%   |
| Foxconn             | 28       | 1.3%    |
| Pegatron            | 26       | 1.21%   |
| Biostar             | 25       | 1.16%   |
| ECS                 | 17       | 0.79%   |
| Medion              | 14       | 0.65%   |
| Positivo            | 12       | 0.56%   |
| Unknown             | 11       | 0.51%   |
| AZW                 | 9        | 0.42%   |
| Shuttle             | 7        | 0.33%   |
| Fujitsu Siemens     | 6        | 0.28%   |
| Alienware           | 6        | 0.28%   |
| MACHINIST           | 5        | 0.23%   |
| BESSTAR Tech        | 5        | 0.23%   |
| PCWare              | 4        | 0.19%   |
| Packard Bell        | 4        | 0.19%   |
| OEM                 | 4        | 0.19%   |
| Apple               | 4        | 0.19%   |
| Wistron             | 3        | 0.14%   |
| WesternDigital      | 2        | 0.09%   |
| Supermicro          | 2        | 0.09%   |
| Semp Toshiba        | 2        | 0.09%   |
| Philco              | 2        | 0.09%   |
| MAXSUN              | 2        | 0.09%   |
| Login Informatica   | 2        | 0.09%   |
| Itautec             | 2        | 0.09%   |
| Huanan              | 2        | 0.09%   |
| Gateway             | 2        | 0.09%   |
| ACTION              | 2        | 0.09%   |
| VS Company          | 1        | 0.05%   |
| Vorke               | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 44       | 2.05%   |
| Gigabyte H410M H V3              | 27       | 1.26%   |
| ASUS SABERTOOTH Z77              | 19       | 0.88%   |
| Dell OptiPlex 7010               | 18       | 0.84%   |
| Unknown                          | 12       | 0.56%   |
| Intel H61                        | 10       | 0.47%   |
| Dell OptiPlex 780                | 10       | 0.47%   |
| MSI MS-7C91                      | 9        | 0.42%   |
| Gigabyte B450M DS3H              | 9        | 0.42%   |
| HP ProDesk 600 G1 SFF            | 8        | 0.37%   |
| Dell OptiPlex 9020               | 8        | 0.37%   |
| Dell OptiPlex 790                | 8        | 0.37%   |
| Dell OptiPlex 380                | 8        | 0.37%   |
| Dell OptiPlex 3020               | 8        | 0.37%   |
| ASUS PRIME B450M-A II            | 8        | 0.37%   |
| MSI MS-7A38                      | 7        | 0.33%   |
| HP EliteDesk 800 G1 SFF          | 7        | 0.33%   |
| MSI MS-7C37                      | 6        | 0.28%   |
| MSI MS-7C02                      | 6        | 0.28%   |
| MSI MS-7B79                      | 6        | 0.28%   |
| MSI MS-7721                      | 6        | 0.28%   |
| HP EliteDesk 800 G1 USDT         | 6        | 0.28%   |
| HP Compaq Pro 6300 SFF           | 6        | 0.28%   |
| Gigabyte 970A-DS3P               | 6        | 0.28%   |
| Dell OptiPlex 745                | 6        | 0.28%   |
| Dell OptiPlex 7020               | 6        | 0.28%   |
| ASUS TUF Gaming B550-PLUS        | 6        | 0.28%   |
| ASUS ROG STRIX B550-F GAMING     | 6        | 0.28%   |
| ASUS PRIME B450-PLUS             | 6        | 0.28%   |
| ASUS PRIME A320M-K               | 6        | 0.28%   |
| ASUS M5A78L-M/USB3               | 6        | 0.28%   |
| MSI MS-7C84                      | 5        | 0.23%   |
| MSI MS-7788                      | 5        | 0.23%   |
| MSI MS-7641                      | 5        | 0.23%   |
| HP Compaq 8200 Elite SFF PC      | 5        | 0.23%   |
| HP Compaq 8100 Elite CMT PC      | 5        | 0.23%   |
| Gigabyte B550M AORUS PRO-P       | 5        | 0.23%   |
| Gigabyte A320M-S2H               | 5        | 0.23%   |
| Dell Precision WorkStation T3500 | 5        | 0.23%   |
| Dell OptiPlex 760                | 5        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 113      | 5.26%   |
| ASUS PRIME             | 86       | 4.01%   |
| Lenovo ThinkCentre     | 61       | 2.84%   |
| HP Compaq              | 61       | 2.84%   |
| ASUS All               | 44       | 2.05%   |
| Acer Aspire            | 39       | 1.82%   |
| ASUS TUF               | 37       | 1.72%   |
| HP EliteDesk           | 33       | 1.54%   |
| ASUS ROG               | 33       | 1.54%   |
| Gigabyte H410M         | 31       | 1.44%   |
| Fujitsu ESPRIMO        | 28       | 1.3%    |
| HP ProDesk             | 26       | 1.21%   |
| ASUS SABERTOOTH        | 25       | 1.16%   |
| Gigabyte B450M         | 19       | 0.88%   |
| Dell Precision         | 19       | 0.88%   |
| ASUS M5A78L-M          | 19       | 0.88%   |
| Acer Veriton           | 14       | 0.65%   |
| Dell Vostro            | 13       | 0.61%   |
| Dell Inspiron          | 13       | 0.61%   |
| Unknown                | 12       | 0.56%   |
| Intel H61              | 11       | 0.51%   |
| Gigabyte X570          | 11       | 0.51%   |
| ASUS M5A97             | 11       | 0.51%   |
| Gigabyte Z390          | 10       | 0.47%   |
| Gigabyte GA-78LMT-USB3 | 10       | 0.47%   |
| ASUS P8H61-M           | 10       | 0.47%   |
| ASRock B450M           | 10       | 0.47%   |
| MSI MS-7C91            | 9        | 0.42%   |
| HP Pavilion            | 9        | 0.42%   |
| Gigabyte B550M         | 9        | 0.42%   |
| Gigabyte B450          | 9        | 0.42%   |
| Lenovo IdeaCentre      | 8        | 0.37%   |
| ASRock A320M-HDV       | 8        | 0.37%   |
| MSI MS-7A38            | 7        | 0.33%   |
| Lenovo ThinkStation    | 7        | 0.33%   |
| MSI MS-7C37            | 6        | 0.28%   |
| MSI MS-7C02            | 6        | 0.28%   |
| MSI MS-7B79            | 6        | 0.28%   |
| MSI MS-7721            | 6        | 0.28%   |
| HP Slim                | 6        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 241      | 11.22%  |
| 2013 | 200      | 9.32%   |
| 2018 | 189      | 8.8%    |
| 2011 | 173      | 8.06%   |
| 2014 | 164      | 7.64%   |
| 2021 | 142      | 6.61%   |
| 2020 | 141      | 6.57%   |
| 2010 | 140      | 6.52%   |
| 2009 | 126      | 5.87%   |
| 2019 | 118      | 5.5%    |
| 2008 | 99       | 4.61%   |
| 2017 | 96       | 4.47%   |
| 2016 | 90       | 4.19%   |
| 2015 | 82       | 3.82%   |
| 2007 | 67       | 3.12%   |
| 2006 | 48       | 2.24%   |
| 2022 | 23       | 1.07%   |
| 2005 | 6        | 0.28%   |
| 2023 | 2        | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2147     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2147     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2147     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 490      | 22.71%  |
| 16.01-24.0      | 455      | 21.08%  |
| 4.01-8.0        | 429      | 19.88%  |
| 3.01-4.0        | 385      | 17.84%  |
| 32.01-64.0      | 215      | 9.96%   |
| 1.01-2.0        | 61       | 2.83%   |
| 64.01-256.0     | 49       | 2.27%   |
| 24.01-32.0      | 47       | 2.18%   |
| 2.01-3.0        | 22       | 1.02%   |
| 0.51-1.0        | 3        | 0.14%   |
| More than 256.0 | 2        | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 1427     | 65.52%  |
| 0.51-1.0  | 487      | 22.36%  |
| 2.01-3.0  | 174      | 7.99%   |
| 0.01-0.5  | 52       | 2.39%   |
| 3.01-4.0  | 22       | 1.01%   |
| 4.01-8.0  | 10       | 0.46%   |
| 8.01-16.0 | 6        | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 928      | 42.78%  |
| 2      | 586      | 27.02%  |
| 3      | 289      | 13.32%  |
| 4      | 178      | 8.21%   |
| 5      | 76       | 3.5%    |
| 0      | 49       | 2.26%   |
| 6      | 31       | 1.43%   |
| 7      | 11       | 0.51%   |
| 8      | 7        | 0.32%   |
| 9      | 6        | 0.28%   |
| 13     | 2        | 0.09%   |
| 12     | 2        | 0.09%   |
| 11     | 2        | 0.09%   |
| 15     | 1        | 0.05%   |
| 10     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1235     | 57.36%  |
| No        | 918      | 42.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2130     | 99.21%  |
| No        | 17       | 0.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1401     | 65.07%  |
| Yes       | 752      | 34.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1686     | 78.42%  |
| Yes       | 464      | 21.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 270      | 12.56%  |
| USA          | 264      | 12.28%  |
| Russia       | 186      | 8.65%   |
| France       | 145      | 6.74%   |
| Brazil       | 145      | 6.74%   |
| Poland       | 120      | 5.58%   |
| Italy        | 84       | 3.91%   |
| Canada       | 57       | 2.65%   |
| UK           | 54       | 2.51%   |
| Spain        | 54       | 2.51%   |
| Australia    | 45       | 2.09%   |
| India        | 42       | 1.95%   |
| Mexico       | 37       | 1.72%   |
| Argentina    | 35       | 1.63%   |
| Ukraine      | 29       | 1.35%   |
| Japan        | 29       | 1.35%   |
| Czechia      | 28       | 1.3%    |
| Netherlands  | 27       | 1.26%   |
| Austria      | 26       | 1.21%   |
| Hungary      | 21       | 0.98%   |
| Romania      | 20       | 0.93%   |
| Indonesia    | 20       | 0.93%   |
| Turkey       | 18       | 0.84%   |
| Switzerland  | 18       | 0.84%   |
| Sweden       | 18       | 0.84%   |
| Serbia       | 17       | 0.79%   |
| Portugal     | 14       | 0.65%   |
| Colombia     | 14       | 0.65%   |
| Belgium      | 14       | 0.65%   |
| Egypt        | 13       | 0.6%    |
| Uruguay      | 11       | 0.51%   |
| Slovakia     | 11       | 0.51%   |
| Israel       | 11       | 0.51%   |
| Venezuela    | 10       | 0.47%   |
| Finland      | 10       | 0.47%   |
| China        | 10       | 0.47%   |
| Algeria      | 10       | 0.47%   |
| Thailand     | 9        | 0.42%   |
| Peru         | 9        | 0.42%   |
| South Africa | 8        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 32       | 1.46%   |
| Gonikoppal        | 22       | 1.01%   |
| Warsaw            | 18       | 0.82%   |
| Strzyzow          | 17       | 0.78%   |
| Sao Paulo         | 16       | 0.73%   |
| Berlin            | 15       | 0.69%   |
| Vienna            | 13       | 0.59%   |
| St Petersburg     | 13       | 0.59%   |
| Munich            | 13       | 0.59%   |
| Paris             | 12       | 0.55%   |
| Mexico City       | 12       | 0.55%   |
| Sydney            | 11       | 0.5%    |
| Rio de Janeiro    | 10       | 0.46%   |
| Milan             | 10       | 0.46%   |
| Istanbul          | 9        | 0.41%   |
| Cairo             | 9        | 0.41%   |
| Belgrade          | 9        | 0.41%   |
| Nizhniy Novgorod  | 8        | 0.37%   |
| Budapest          | 8        | 0.37%   |
| Brisbane          | 8        | 0.37%   |
| Braganca Paulista | 8        | 0.37%   |
| Yekaterinburg     | 7        | 0.32%   |
| Rome              | 7        | 0.32%   |
| Poznan            | 7        | 0.32%   |
| Montevideo        | 7        | 0.32%   |
| Marseille         | 7        | 0.32%   |
| Lima              | 7        | 0.32%   |
| Kyiv              | 7        | 0.32%   |
| Jakarta           | 7        | 0.32%   |
| Hamburg           | 7        | 0.32%   |
| Buenos Aires      | 7        | 0.32%   |
| Bucharest         | 7        | 0.32%   |
| Skopje            | 6        | 0.27%   |
| San Jose          | 6        | 0.27%   |
| Prague            | 6        | 0.27%   |
| Madrid            | 6        | 0.27%   |
| Gdansk            | 6        | 0.27%   |
| Chelyabinsk       | 6        | 0.27%   |
| Bratislava        | 6        | 0.27%   |
| Zagreb            | 5        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 735      | 989    | 19.75%  |
| Seagate             | 674      | 900    | 18.11%  |
| Samsung Electronics | 491      | 651    | 13.2%   |
| Kingston            | 224      | 256    | 6.02%   |
| Toshiba             | 210      | 242    | 5.64%   |
| Crucial             | 183      | 217    | 4.92%   |
| SanDisk             | 152      | 181    | 4.08%   |
| Hitachi             | 144      | 164    | 3.87%   |
| A-DATA Technology   | 103      | 111    | 2.77%   |
| China               | 47       | 55     | 1.26%   |
| Unknown             | 41       | 54     | 1.1%    |
| Maxtor              | 37       | 42     | 0.99%   |
| HGST                | 34       | 42     | 0.91%   |
| SPCC                | 29       | 33     | 0.78%   |
| Intel               | 29       | 30     | 0.78%   |
| PNY                 | 27       | 36     | 0.73%   |
| GOODRAM             | 27       | 29     | 0.73%   |
| Patriot             | 23       | 25     | 0.62%   |
| Gigabyte Technology | 23       | 23     | 0.62%   |
| Intenso             | 22       | 23     | 0.59%   |
| Apacer              | 22       | 23     | 0.59%   |
| OCZ                 | 21       | 21     | 0.56%   |
| Micron Technology   | 19       | 19     | 0.51%   |
| Corsair             | 18       | 19     | 0.48%   |
| Unknown             | 18       | 19     | 0.48%   |
| Team                | 17       | 17     | 0.46%   |
| Phison              | 17       | 20     | 0.46%   |
| Netac               | 17       | 19     | 0.46%   |
| JMicron Technology  | 15       | 16     | 0.4%    |
| Transcend           | 14       | 16     | 0.38%   |
| Hewlett-Packard     | 14       | 18     | 0.38%   |
| SK hynix            | 13       | 13     | 0.35%   |
| ASMT                | 13       | 15     | 0.35%   |
| XPG                 | 11       | 14     | 0.3%    |
| Silicon Motion      | 8        | 9      | 0.21%   |
| LITEON              | 8        | 8      | 0.21%   |
| KIOXIA-EXCERIA      | 8        | 8      | 0.21%   |
| KingSpec            | 8        | 8      | 0.21%   |
| Apple               | 8        | 8      | 0.21%   |
| KingFast            | 7        | 7      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 75       | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB   | 64       | 1.5%    |
| Kingston SA400S37240G 240GB SSD  | 52       | 1.22%   |
| WDC WD10EZEX-08WN4A0 1TB         | 40       | 0.94%   |
| Toshiba DT01ACA100 1TB           | 40       | 0.94%   |
| Seagate ST2000DM008-2FR102 2TB   | 34       | 0.79%   |
| Crucial CT500MX500SSD1 500GB     | 33       | 0.77%   |
| Kingston SA400S37480G 480GB SSD  | 32       | 0.75%   |
| Samsung SSD 860 EVO 500GB        | 31       | 0.72%   |
| Toshiba DT01ACA050 500GB         | 30       | 0.7%    |
| Samsung SSD 860 EVO 250GB        | 30       | 0.7%    |
| Samsung SSD 850 EVO 250GB        | 29       | 0.68%   |
| Kingston SA400S37120G 120GB SSD  | 28       | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB   | 27       | 0.63%   |
| Samsung HD502HJ 500GB            | 23       | 0.54%   |
| Kingston SV300S37A120G 120GB SSD | 23       | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 22       | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB   | 22       | 0.51%   |
| A-DATA SU750 256GB SSD           | 22       | 0.51%   |
| Crucial CT480BX500SSD1 480GB     | 21       | 0.49%   |
| Crucial CT240BX500SSD1 240GB     | 21       | 0.49%   |
| Crucial CT1000MX500SSD1 1TB      | 21       | 0.49%   |
| Seagate ST3500418AS 500GB        | 20       | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB   | 20       | 0.47%   |
| Unknown SD/MMC/MS PRO 128GB      | 19       | 0.44%   |
| Samsung SSD 850 EVO 500GB        | 19       | 0.44%   |
| Toshiba HDWD110 1TB              | 18       | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB   | 18       | 0.42%   |
| Seagate ST1000DM003-1SB102 1TB   | 18       | 0.42%   |
| Unknown                          | 18       | 0.42%   |
| Toshiba DT01ACA200 2TB           | 17       | 0.4%    |
| SanDisk SSD PLUS 240GB           | 17       | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB     | 17       | 0.4%    |
| Seagate ST3500413AS 500GB        | 16       | 0.37%   |
| Seagate ST31000528AS 1TB         | 15       | 0.35%   |
| SanDisk SSD PLUS 1000GB          | 15       | 0.35%   |
| SanDisk SDSSDA240G 240GB         | 15       | 0.35%   |
| Samsung HD322HJ 320GB            | 15       | 0.35%   |
| WDC WD10EZEX-00BN5A0 1TB         | 14       | 0.33%   |
| Seagate ST3500312CS 500GB        | 13       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 665      | 882    | 34.19%  |
| WDC                 | 639      | 822    | 32.85%  |
| Toshiba             | 192      | 223    | 9.87%   |
| Samsung Electronics | 158      | 188    | 8.12%   |
| Hitachi             | 144      | 164    | 7.4%    |
| Maxtor              | 36       | 41     | 1.85%   |
| HGST                | 34       | 42     | 1.75%   |
| Unknown             | 20       | 20     | 1.03%   |
| Apple               | 8        | 8      | 0.41%   |
| TO Exter            | 6        | 6      | 0.31%   |
| Fujitsu             | 5        | 5      | 0.26%   |
| USB3.0              | 4        | 4      | 0.21%   |
| Intenso             | 4        | 4      | 0.21%   |
| IBM/Hitachi         | 4        | 5      | 0.21%   |
| WD MediaMax         | 3        | 4      | 0.15%   |
| Hewlett-Packard     | 3        | 4      | 0.15%   |
| Magnetic Data       | 2        | 2      | 0.1%    |
| JMicron Technology  | 2        | 2      | 0.1%    |
| Initio              | 2        | 2      | 0.1%    |
| HPE                 | 2        | 3      | 0.1%    |
| ASMT                | 2        | 4      | 0.1%    |
| Unknown             | 2        | 2      | 0.1%    |
| RSH-339             | 1        | 1      | 0.05%   |
| QUANTUM             | 1        | 1      | 0.05%   |
| MARVELL             | 1        | 1      | 0.05%   |
| Inateck             | 1        | 1      | 0.05%   |
| External            | 1        | 1      | 0.05%   |
| ExcelStor           | 1        | 1      | 0.05%   |
| Config              | 1        | 1      | 0.05%   |
| China               | 1        | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 248      | 302    | 17.75%  |
| Kingston            | 190      | 214    | 13.6%   |
| Crucial             | 151      | 176    | 10.81%  |
| SanDisk             | 138      | 163    | 9.88%   |
| WDC                 | 89       | 108    | 6.37%   |
| A-DATA Technology   | 86       | 87     | 6.16%   |
| China               | 46       | 54     | 3.29%   |
| GOODRAM             | 25       | 25     | 1.79%   |
| PNY                 | 23       | 30     | 1.65%   |
| SPCC                | 21       | 24     | 1.5%    |
| OCZ                 | 21       | 21     | 1.5%    |
| Apacer              | 20       | 20     | 1.43%   |
| Intel               | 19       | 20     | 1.36%   |
| Patriot             | 18       | 20     | 1.29%   |
| Micron Technology   | 18       | 18     | 1.29%   |
| Team                | 17       | 17     | 1.22%   |
| Unknown             | 16       | 17     | 1.15%   |
| Gigabyte Technology | 15       | 15     | 1.07%   |
| Toshiba             | 14       | 15     | 1%      |
| Intenso             | 14       | 15     | 1%      |
| Netac               | 13       | 15     | 0.93%   |
| Transcend           | 12       | 13     | 0.86%   |
| ASMT                | 11       | 11     | 0.79%   |
| JMicron Technology  | 9        | 10     | 0.64%   |
| KingSpec            | 8        | 8      | 0.57%   |
| Hewlett-Packard     | 8        | 10     | 0.57%   |
| LITEON              | 7        | 7      | 0.5%    |
| KingFast            | 7        | 7      | 0.5%    |
| Corsair             | 7        | 7      | 0.5%    |
| KIOXIA-EXCERIA      | 6        | 6      | 0.43%   |
| Colorful            | 6        | 7      | 0.43%   |
| Emtec               | 5        | 5      | 0.36%   |
| SK hynix            | 4        | 4      | 0.29%   |
| Seagate             | 4        | 4      | 0.29%   |
| LITEONIT            | 4        | 4      | 0.29%   |
| Leven               | 4        | 4      | 0.29%   |
| KingDian            | 4        | 5      | 0.29%   |
| Zheino              | 3        | 4      | 0.21%   |
| Mushkin             | 3        | 3      | 0.21%   |
| Lexar               | 3        | 3      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1505     | 2445   | 49.31%  |
| SSD     | 1105     | 1579   | 36.21%  |
| NVMe    | 394      | 514    | 12.91%  |
| Unknown | 39       | 54     | 1.28%   |
| MMC     | 9        | 10     | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2003     | 3881   | 77.94%  |
| NVMe | 390      | 504    | 15.18%  |
| SAS  | 168      | 207    | 6.54%   |
| MMC  | 9        | 10     | 0.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1606     | 2418   | 57.38%  |
| 0.51-1.0   | 767      | 1041   | 27.4%   |
| 1.01-2.0   | 245      | 310    | 8.75%   |
| 2.01-3.0   | 63       | 82     | 2.25%   |
| 3.01-4.0   | 56       | 79     | 2%      |
| 4.01-10.0  | 53       | 85     | 1.89%   |
| 10.01-20.0 | 8        | 8      | 0.29%   |
| 20.01-50.0 | 1        | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1122     | 51.23%  |
| Unknown        | 287      | 13.11%  |
| 101-250        | 275      | 12.56%  |
| 251-500        | 169      | 7.72%   |
| 21-50          | 92       | 4.2%    |
| 501-1000       | 90       | 4.11%   |
| 51-100         | 79       | 3.61%   |
| 1001-2000      | 42       | 1.92%   |
| More than 3000 | 19       | 0.87%   |
| 2001-3000      | 15       | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1659     | 76.1%   |
| Unknown        | 287      | 13.17%  |
| 101-250        | 57       | 2.61%   |
| 21-50          | 49       | 2.25%   |
| 51-100         | 43       | 1.97%   |
| 251-500        | 35       | 1.61%   |
| 501-1000       | 29       | 1.33%   |
| 1001-2000      | 13       | 0.6%    |
| More than 3000 | 6        | 0.28%   |
| 2001-3000      | 2        | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 34       | 35     | 4.09%   |
| Samsung Electronics HD322HJ 320GB | 10       | 11     | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB    | 9        | 11     | 1.08%   |
| Seagate ST1000DM003-9YN162 1TB    | 9        | 9      | 1.08%   |
| Seagate ST3500413AS 500GB         | 8        | 8      | 0.96%   |
| Kingston SV300S37A120G 120GB SSD  | 8        | 8      | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 7        | 8      | 0.84%   |
| Seagate ST9500325AS 500GB         | 7        | 7      | 0.84%   |
| Seagate ST3500418AS 500GB         | 7        | 8      | 0.84%   |
| Samsung Electronics HD502HJ 500GB | 7        | 7      | 0.84%   |
| WDC WD5000AAKS-00V1A0 500GB       | 6        | 6      | 0.72%   |
| WDC WD10EARS-00Y5B1 1TB           | 6        | 7      | 0.72%   |
| WDC WD10EALX-009BA0 1TB           | 6        | 6      | 0.72%   |
| Toshiba DT01ACA050 500GB          | 6        | 7      | 0.72%   |
| Seagate ST31000524AS 1TB          | 6        | 7      | 0.72%   |
| Seagate ST2000DM001-1CH164 2TB    | 6        | 6      | 0.72%   |
| SanDisk SSD PLUS 240GB            | 6        | 6      | 0.72%   |
| Hitachi HDS721050CLA362 500GB     | 6        | 7      | 0.72%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 5        | 5      | 0.6%    |
| WDC WD5000AADS-00S9B0 500GB       | 5        | 5      | 0.6%    |
| WDC WD20EZRZ-00Z5HB0 2TB          | 5        | 5      | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB          | 5        | 5      | 0.6%    |
| Toshiba DT01ACA100 1TB            | 5        | 6      | 0.6%    |
| Seagate ST3320418AS 320GB         | 5        | 5      | 0.6%    |
| Seagate ST31000528AS 1TB          | 5        | 6      | 0.6%    |
| Seagate ST1000DM003-1SB102 1TB    | 5        | 5      | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB    | 5        | 6      | 0.6%    |
| Samsung Electronics HD502HI 500GB | 5        | 6      | 0.6%    |
| Maxtor STM3250310AS 250GB         | 5        | 5      | 0.6%    |
| GOODRAM SSD 120GB                 | 5        | 5      | 0.6%    |
| WDC WD5000AAKX-22ERMA0 500GB      | 4        | 4      | 0.48%   |
| WDC WD3200AAJS-00L7A0 320GB       | 4        | 4      | 0.48%   |
| WDC WD20EARS-00MVWB0 2TB          | 4        | 4      | 0.48%   |
| Seagate ST92505610AS 250GB        | 4        | 4      | 0.48%   |
| Seagate ST380013AS 80GB           | 4        | 4      | 0.48%   |
| Seagate ST250DM000-1BD141 250GB   | 4        | 4      | 0.48%   |
| SanDisk SSD PLUS 480GB            | 4        | 4      | 0.48%   |
| Samsung Electronics SP2504C 250GB | 4        | 4      | 0.48%   |
| Samsung Electronics HD753LJ 752GB | 4        | 4      | 0.48%   |
| Samsung Electronics HD161HJ 160GB | 4        | 4      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 241      | 275    | 30.28%  |
| WDC                 | 218      | 242    | 27.39%  |
| Samsung Electronics | 83       | 93     | 10.43%  |
| Hitachi             | 69       | 76     | 8.67%   |
| Toshiba             | 29       | 31     | 3.64%   |
| Maxtor              | 25       | 26     | 3.14%   |
| SanDisk             | 19       | 19     | 2.39%   |
| Kingston            | 19       | 20     | 2.39%   |
| HGST                | 12       | 13     | 1.51%   |
| A-DATA Technology   | 9        | 10     | 1.13%   |
| Crucial             | 8        | 9      | 1.01%   |
| Intel               | 6        | 6      | 0.75%   |
| Micron Technology   | 5        | 5      | 0.63%   |
| GOODRAM             | 5        | 5      | 0.63%   |
| IBM/Hitachi         | 4        | 5      | 0.5%    |
| ASMT                | 4        | 4      | 0.5%    |
| OCZ                 | 3        | 3      | 0.38%   |
| China               | 3        | 4      | 0.38%   |
| SPCC                | 2        | 2      | 0.25%   |
| Patriot             | 2        | 2      | 0.25%   |
| LITEON              | 2        | 2      | 0.25%   |
| Hewlett-Packard     | 2        | 3      | 0.25%   |
| Fujitsu             | 2        | 2      | 0.25%   |
| Unknown             | 2        | 2      | 0.25%   |
| WDC WDS2            | 1        | 1      | 0.13%   |
| WD MediaMax         | 1        | 1      | 0.13%   |
| USB3.0              | 1        | 1      | 0.13%   |
| Transcend           | 1        | 1      | 0.13%   |
| TO Exter            | 1        | 1      | 0.13%   |
| TEXTORM             | 1        | 1      | 0.13%   |
| TCSUNBOW            | 1        | 1      | 0.13%   |
| RSH-339             | 1        | 1      | 0.13%   |
| Neo                 | 1        | 1      | 0.13%   |
| LITEONIT            | 1        | 1      | 0.13%   |
| KingSpec            | 1        | 1      | 0.13%   |
| Kingmax             | 1        | 1      | 0.13%   |
| KingDian            | 1        | 1      | 0.13%   |
| INNOVATION IT       | 1        | 1      | 0.13%   |
| Initio              | 1        | 1      | 0.13%   |
| HPE                 | 1        | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 241      | 275    | 35.86%  |
| WDC                 | 207      | 228    | 30.8%   |
| Samsung Electronics | 74       | 83     | 11.01%  |
| Hitachi             | 69       | 76     | 10.27%  |
| Toshiba             | 29       | 31     | 4.32%   |
| Maxtor              | 25       | 26     | 3.72%   |
| HGST                | 12       | 13     | 1.79%   |
| IBM/Hitachi         | 4        | 5      | 0.6%    |
| Fujitsu             | 2        | 2      | 0.3%    |
| WD MediaMax         | 1        | 1      | 0.15%   |
| USB3.0              | 1        | 1      | 0.15%   |
| TO Exter            | 1        | 1      | 0.15%   |
| RSH-339             | 1        | 1      | 0.15%   |
| Initio              | 1        | 1      | 0.15%   |
| HPE                 | 1        | 1      | 0.15%   |
| Hewlett-Packard     | 1        | 2      | 0.15%   |
| ExcelStor           | 1        | 1      | 0.15%   |
| Unknown             | 1        | 1      | 0.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 586      | 749    | 82.77%  |
| SSD  | 117      | 127    | 16.53%  |
| NVMe | 5        | 6      | 0.71%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3        | 3      | 12.5%   |
| Apple HDD HTS541010A9E662 1TB                    | 3        | 3      | 12.5%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1        | 1      | 4.17%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 1      | 4.17%   |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 4.17%   |
| Toshiba MQ01ABD050 500GB                         | 1        | 1      | 4.17%   |
| Toshiba MK3256GSY 320GB                          | 1        | 1      | 4.17%   |
| Toshiba DT01ACA100 1TB                           | 1        | 1      | 4.17%   |
| Seagate STM31000528AS 1TB                        | 1        | 1      | 4.17%   |
| Seagate ST980811AS 80GB                          | 1        | 1      | 4.17%   |
| Seagate ST3250318AS 250GB                        | 1        | 1      | 4.17%   |
| Seagate ST3160215A 160GB                         | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 4.17%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 4.17%   |
| Samsung Electronics HM160HI 160GB                | 1        | 1      | 4.17%   |
| Samsung Electronics HD103UJ 1TB                  | 1        | 1      | 4.17%   |
| Hitachi HTS725050A7E630 500GB                    | 1        | 1      | 4.17%   |
| Hitachi HDS721010DLE630 1TB                      | 1        | 1      | 4.17%   |
| Hitachi HDP725050GLA360 500GB                    | 1        | 1      | 4.17%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1        | 1      | 4.17%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 7      | 29.17%  |
| Seagate             | 4        | 4      | 16.67%  |
| WDC                 | 3        | 3      | 12.5%   |
| Toshiba             | 3        | 3      | 12.5%   |
| Hitachi             | 3        | 3      | 12.5%   |
| Apple               | 3        | 3      | 12.5%   |
| GOODRAM             | 1        | 1      | 4.17%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1771     | 3496   | 66.91%  |
| Malfunc  | 687      | 882    | 25.95%  |
| Detected | 166      | 200    | 6.27%   |
| Failed   | 23       | 24     | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1417     | 49.44%  |
| AMD                              | 646      | 22.54%  |
| Samsung Electronics              | 134      | 4.68%   |
| JMicron Technology               | 93       | 3.24%   |
| ASMedia Technology               | 80       | 2.79%   |
| Marvell Technology Group         | 74       | 2.58%   |
| Nvidia                           | 70       | 2.44%   |
| SanDisk                          | 68       | 2.37%   |
| Phison Electronics               | 48       | 1.67%   |
| Kingston Technology Company      | 40       | 1.4%    |
| Micron/Crucial Technology        | 36       | 1.26%   |
| Silicon Motion                   | 34       | 1.19%   |
| VIA Technologies                 | 23       | 0.8%    |
| ADATA Technology                 | 18       | 0.63%   |
| Realtek Semiconductor            | 13       | 0.45%   |
| SK hynix                         | 8        | 0.28%   |
| Broadcom / LSI                   | 8        | 0.28%   |
| Seagate Technology               | 7        | 0.24%   |
| Integrated Technology Express    | 6        | 0.21%   |
| Toshiba America Info Systems     | 5        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 5        | 0.17%   |
| Micron Technology                | 4        | 0.14%   |
| Lite-On Technology               | 4        | 0.14%   |
| Adaptec                          | 4        | 0.14%   |
| LSI Logic / Symbios Logic        | 3        | 0.1%    |
| Union Memory (Shenzhen)          | 2        | 0.07%   |
| Silicon Image                    | 2        | 0.07%   |
| Shenzhen Longsys Electronics     | 2        | 0.07%   |
| Promise Technology               | 2        | 0.07%   |
| KIOXIA                           | 2        | 0.07%   |
| Yangtze Memory Technologies      | 1        | 0.03%   |
| Solid State Storage Technology   | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| Netac Technology                 | 1        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.03%   |
| INNOGRIT                         | 1        | 0.03%   |
| Hewlett-Packard                  | 1        | 0.03%   |
| 3ware                            | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 316      | 8.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 203      | 5.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 130      | 3.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 128      | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 119      | 3.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 118      | 3.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 105      | 2.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 96       | 2.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 92       | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 88       | 2.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 85       | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 78       | 2.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 77       | 2.09%   |
| AMD 500 Series Chipset SATA Controller                                                  | 77       | 2.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 74       | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 70       | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 70       | 1.9%    |
| Intel SATA Controller [RAID mode]                                                       | 67       | 1.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 66       | 1.79%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 64       | 1.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 59       | 1.6%    |
| Nvidia MCP61 SATA Controller                                                            | 40       | 1.09%   |
| AMD FCH SATA Controller D                                                               | 40       | 1.09%   |
| Nvidia MCP61 IDE                                                                        | 34       | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 34       | 0.92%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 34       | 0.92%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 33       | 0.9%    |
| AMD FCH IDE Controller                                                                  | 33       | 0.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 31       | 0.84%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 31       | 0.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 28       | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 26       | 0.71%   |
| Phison E12 NVMe Controller                                                              | 25       | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 25       | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 24       | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 24       | 0.65%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 24       | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 24       | 0.65%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 23       | 0.62%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 23       | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1639     | 57.87%  |
| IDE  | 680      | 24.01%  |
| NVMe | 387      | 13.67%  |
| RAID | 111      | 3.92%   |
| SAS  | 9        | 0.32%   |
| SCSI | 6        | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1440     | 67.07%  |
| AMD    | 707      | 32.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-10400 CPU @ 2.90GHz           | 41       | 1.91%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 33       | 1.53%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 30       | 1.39%   |
| AMD Ryzen 5 3600 6-Core Processor           | 29       | 1.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 27       | 1.25%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 26       | 1.21%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 24       | 1.12%   |
| AMD FX-8350 Eight-Core Processor            | 24       | 1.12%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 23       | 1.07%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 22       | 1.02%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 21       | 0.98%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 21       | 0.98%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 20       | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 19       | 0.88%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 19       | 0.88%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 19       | 0.88%   |
| AMD FX-6300 Six-Core Processor              | 19       | 0.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 18       | 0.84%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 18       | 0.84%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 16       | 0.74%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 16       | 0.74%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 16       | 0.74%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 16       | 0.74%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 15       | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 15       | 0.7%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 14       | 0.65%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 14       | 0.65%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 14       | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 13       | 0.6%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 13       | 0.6%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 13       | 0.6%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 12       | 0.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 12       | 0.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 12       | 0.56%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 12       | 0.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 12       | 0.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 11       | 0.51%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 11       | 0.51%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 11       | 0.51%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 11       | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 443      | 20.6%   |
| Intel Core i3           | 220      | 10.23%  |
| Intel Core i7           | 179      | 8.33%   |
| AMD Ryzen 5             | 143      | 6.65%   |
| Intel Core 2 Duo        | 97       | 4.51%   |
| AMD FX                  | 95       | 4.42%   |
| Intel Celeron           | 84       | 3.91%   |
| Intel Pentium           | 83       | 3.86%   |
| AMD Ryzen 7             | 81       | 3.77%   |
| Intel Xeon              | 79       | 3.67%   |
| Intel Core 2 Quad       | 63       | 2.93%   |
| Other                   | 49       | 2.28%   |
| Intel Pentium Dual-Core | 49       | 2.28%   |
| AMD Ryzen 3             | 40       | 1.86%   |
| AMD A8                  | 35       | 1.63%   |
| AMD Phenom II X4        | 33       | 1.53%   |
| AMD Athlon II X2        | 29       | 1.35%   |
| AMD Ryzen 9             | 24       | 1.12%   |
| AMD A10                 | 24       | 1.12%   |
| Intel Core 2            | 23       | 1.07%   |
| AMD A4                  | 23       | 1.07%   |
| AMD Athlon 64 X2        | 22       | 1.02%   |
| Intel Pentium Dual      | 20       | 0.93%   |
| AMD Athlon              | 20       | 0.93%   |
| AMD A6                  | 17       | 0.79%   |
| Intel Core i9           | 14       | 0.65%   |
| AMD Athlon II X4        | 12       | 0.56%   |
| Intel Pentium Gold      | 11       | 0.51%   |
| AMD Athlon X4           | 11       | 0.51%   |
| AMD Athlon II X3        | 11       | 0.51%   |
| Intel Atom              | 10       | 0.47%   |
| AMD Ryzen 5 PRO         | 10       | 0.47%   |
| AMD Phenom II X6        | 10       | 0.47%   |
| AMD Phenom              | 10       | 0.47%   |
| Intel Pentium D         | 9        | 0.42%   |
| AMD Sempron             | 9        | 0.42%   |
| Intel Pentium 4         | 6        | 0.28%   |
| AMD Phenom II X2        | 6        | 0.28%   |
| AMD Athlon 64           | 6        | 0.28%   |
| AMD Ryzen 3 PRO         | 5        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 817      | 38%     |
| 2      | 759      | 35.3%   |
| 6      | 291      | 13.53%  |
| 8      | 129      | 6%      |
| 1      | 54       | 2.51%   |
| 3      | 42       | 1.95%   |
| 12     | 27       | 1.26%   |
| 16     | 18       | 0.84%   |
| 10     | 7        | 0.33%   |
| 14     | 3        | 0.14%   |
| 44     | 1        | 0.05%   |
| 28     | 1        | 0.05%   |
| 20     | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2130     | 99.21%  |
| 2      | 17       | 0.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1086     | 50.54%  |
| 2      | 1061     | 49.37%  |
| 4      | 2        | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2147     | 99.95%  |
| Unknown        | 1        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 245      | 11.36%  |
| 0x306a9    | 168      | 7.79%   |
| 0x1067a    | 162      | 7.51%   |
| 0x206a7    | 151      | 7%      |
| 0x08701021 | 72       | 3.34%   |
| 0x506e3    | 71       | 3.29%   |
| 0x906ea    | 69       | 3.2%    |
| Unknown    | 54       | 2.5%    |
| 0x906e9    | 52       | 2.41%   |
| 0xa0655    | 47       | 2.18%   |
| 0xa0653    | 40       | 1.85%   |
| 0x0800820d | 39       | 1.81%   |
| 0x010000c8 | 39       | 1.81%   |
| 0x06001119 | 37       | 1.72%   |
| 0x6fb      | 36       | 1.67%   |
| 0x08108109 | 30       | 1.39%   |
| 0x06000822 | 30       | 1.39%   |
| 0x06003106 | 29       | 1.34%   |
| 0x0a50000c | 28       | 1.3%    |
| 0x106e5    | 26       | 1.21%   |
| 0x6fd      | 25       | 1.16%   |
| 0x10676    | 24       | 1.11%   |
| 0x20655    | 23       | 1.07%   |
| 0xa0671    | 22       | 1.02%   |
| 0x08101016 | 22       | 1.02%   |
| 0x906eb    | 20       | 0.93%   |
| 0x010000b6 | 20       | 0.93%   |
| 0x0a201016 | 18       | 0.83%   |
| 0x08001138 | 16       | 0.74%   |
| 0x90672    | 15       | 0.7%    |
| 0x106a5    | 14       | 0.65%   |
| 0x08600106 | 14       | 0.65%   |
| 0x06000852 | 14       | 0.65%   |
| 0x0600081c | 14       | 0.65%   |
| 0x03000027 | 14       | 0.65%   |
| 0x906ec    | 13       | 0.6%    |
| 0x20652    | 13       | 0.6%    |
| 0x6f2      | 12       | 0.56%   |
| 0x206d7    | 12       | 0.56%   |
| 0x6f6      | 11       | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 262      | 12.19%  |
| Penryn           | 196      | 9.12%   |
| IvyBridge        | 180      | 8.37%   |
| KabyLake         | 173      | 8.05%   |
| SandyBridge      | 166      | 7.72%   |
| Piledriver       | 118      | 5.49%   |
| K10              | 117      | 5.44%   |
| Zen 2            | 100      | 4.65%   |
| Core             | 88       | 4.09%   |
| CometLake        | 87       | 4.05%   |
| Zen+             | 79       | 3.67%   |
| Zen 3            | 76       | 3.53%   |
| Skylake          | 74       | 3.44%   |
| Zen              | 66       | 3.07%   |
| Westmere         | 45       | 2.09%   |
| Nehalem          | 42       | 1.95%   |
| Steamroller      | 34       | 1.58%   |
| K8 Hammer        | 33       | 1.53%   |
| Icelake          | 22       | 1.02%   |
| Alderlake Hybrid | 20       | 0.93%   |
| K10 Llano        | 19       | 0.88%   |
| Silvermont       | 18       | 0.84%   |
| NetBurst         | 18       | 0.84%   |
| Bulldozer        | 18       | 0.84%   |
| Excavator        | 17       | 0.79%   |
| Jaguar           | 14       | 0.65%   |
| Goldmont plus    | 14       | 0.65%   |
| Puma             | 11       | 0.51%   |
| Broadwell        | 10       | 0.47%   |
| Tremont          | 8        | 0.37%   |
| Goldmont         | 8        | 0.37%   |
| Bonnell          | 8        | 0.37%   |
| Bobcat           | 6        | 0.28%   |
| Unknown          | 2        | 0.09%   |
| TigerLake        | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 778      | 35.03%  |
| Nvidia                     | 776      | 34.94%  |
| AMD                        | 658      | 29.63%  |
| VIA Technologies           | 3        | 0.14%   |
| Matrox Electronics Systems | 3        | 0.14%   |
| Conexant Systems           | 1        | 0.05%   |
| ATI Technologies           | 1        | 0.05%   |
| ASPEED Technology          | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 134      | 5.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 94       | 4.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 81       | 3.58%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 73       | 3.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 62       | 2.74%   |
| Nvidia GK208B [GeForce GT 710]                                              | 60       | 2.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 56       | 2.48%   |
| Nvidia GT218 [GeForce 210]                                                  | 47       | 2.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 46       | 2.04%   |
| Intel HD Graphics 530                                                       | 41       | 1.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 41       | 1.81%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 38       | 1.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 32       | 1.42%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 31       | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 31       | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 31       | 1.37%   |
| Intel HD Graphics 630                                                       | 28       | 1.24%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 25       | 1.11%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 24       | 1.06%   |
| Nvidia GF108 [GeForce GT 630]                                               | 23       | 1.02%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 22       | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 21       | 0.93%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 20       | 0.88%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 19       | 0.84%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 19       | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                         | 18       | 0.8%    |
| AMD RS780L [Radeon 3000]                                                    | 18       | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 16       | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 16       | 0.71%   |
| Nvidia GF119 [GeForce GT 610]                                               | 16       | 0.71%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 16       | 0.71%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 16       | 0.71%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 16       | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 15       | 0.66%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 15       | 0.66%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 15       | 0.66%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 14       | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 14       | 0.62%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 12       | 0.53%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 11       | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 746      | 34.67%  |
| 1 x Intel                | 713      | 33.13%  |
| 1 x AMD                  | 618      | 28.72%  |
| 2 x AMD                  | 28       | 1.3%    |
| Intel + Nvidia           | 19       | 0.88%   |
| Intel + AMD              | 9        | 0.42%   |
| 2 x Nvidia               | 6        | 0.28%   |
| AMD + Nvidia             | 4        | 0.19%   |
| 1 x VIA                  | 3        | 0.14%   |
| 1 x Matrox               | 3        | 0.14%   |
| 3 x AMD                  | 1        | 0.05%   |
| Nvidia + ASPEED          | 1        | 0.05%   |
| Intel + Conexant Systems | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2063     | 96.04%  |
| Unknown     | 81       | 3.77%   |
| Proprietary | 4        | 0.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 790      | 36.73%  |
| 1.01-2.0   | 368      | 17.11%  |
| 0.51-1.0   | 329      | 15.3%   |
| 0.01-0.5   | 274      | 12.74%  |
| 3.01-4.0   | 147      | 6.83%   |
| 7.01-8.0   | 135      | 6.28%   |
| 5.01-6.0   | 55       | 2.56%   |
| 2.01-3.0   | 26       | 1.21%   |
| 8.01-16.0  | 22       | 1.02%   |
| 16.01-24.0 | 4        | 0.19%   |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 359      | 17.02%  |
| Goldstar             | 235      | 11.14%  |
| Dell                 | 204      | 9.67%   |
| Hewlett-Packard      | 193      | 9.15%   |
| Acer                 | 153      | 7.25%   |
| AOC                  | 140      | 6.64%   |
| Philips              | 131      | 6.21%   |
| BenQ                 | 90       | 4.27%   |
| Ancor Communications | 72       | 3.41%   |
| ViewSonic            | 63       | 2.99%   |
| Iiyama               | 38       | 1.8%    |
| Sony                 | 27       | 1.28%   |
| Lenovo               | 26       | 1.23%   |
| ASUSTek Computer     | 26       | 1.23%   |
| Eizo                 | 21       | 1%      |
| Fujitsu Siemens      | 19       | 0.9%    |
| NEC Computers        | 16       | 0.76%   |
| HannStar             | 14       | 0.66%   |
| Panasonic            | 11       | 0.52%   |
| Toshiba              | 9        | 0.43%   |
| Sceptre Tech         | 9        | 0.43%   |
| MSI                  | 9        | 0.43%   |
| Medion               | 9        | 0.43%   |
| Hitachi              | 8        | 0.38%   |
| Vestel Elektronik    | 7        | 0.33%   |
| Unknown              | 7        | 0.33%   |
| TCL                  | 7        | 0.33%   |
| ___                  | 6        | 0.28%   |
| Unknown (XXX)        | 6        | 0.28%   |
| Packard Bell         | 6        | 0.28%   |
| CHD                  | 6        | 0.28%   |
| Xiaomi               | 5        | 0.24%   |
| MStar                | 5        | 0.24%   |
| MiTAC                | 5        | 0.24%   |
| IOD                  | 5        | 0.24%   |
| GDH                  | 5        | 0.24%   |
| Belinea              | 5        | 0.24%   |
| Vizio                | 4        | 0.19%   |
| Mitsubishi           | 4        | 0.19%   |
| Gigabyte Technology  | 4        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 22       | 1.02%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 17       | 0.79%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                 | 14       | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9        | 0.42%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 9        | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 9        | 0.42%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 9        | 0.42%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 8        | 0.37%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 8        | 0.37%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 7        | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 7        | 0.32%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 7        | 0.32%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 7        | 0.32%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 7        | 0.32%   |
| AOC 2217 AOC2217 1680x1050 470x300mm 22.0-inch                        | 7        | 0.32%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 6        | 0.28%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch     | 6        | 0.28%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 6        | 0.28%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 6        | 0.28%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 6        | 0.28%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 6        | 0.28%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch  | 5        | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 0.23%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch  | 5        | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 0.23%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 5        | 0.23%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 5        | 0.23%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 5        | 0.23%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 5        | 0.23%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 5        | 0.23%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 5        | 0.23%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 4        | 0.19%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 4        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 4        | 0.19%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 4        | 0.19%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 4        | 0.19%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 4        | 0.19%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 4        | 0.19%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 4        | 0.19%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 4        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1004     | 48.34%  |
| 1280x1024 (SXGA)   | 188      | 9.05%   |
| 3840x2160 (4K)     | 158      | 7.61%   |
| 1680x1050 (WSXGA+) | 121      | 5.83%   |
| 1366x768 (WXGA)    | 120      | 5.78%   |
| 2560x1440 (QHD)    | 117      | 5.63%   |
| 1440x900 (WXGA+)   | 85       | 4.09%   |
| 1600x900 (HD+)     | 77       | 3.71%   |
| 1920x1200 (WUXGA)  | 64       | 3.08%   |
| 1360x768           | 39       | 1.88%   |
| 3440x1440          | 25       | 1.2%    |
| 2560x1080          | 18       | 0.87%   |
| 1920x540           | 13       | 0.63%   |
| 1024x768 (XGA)     | 12       | 0.58%   |
| 1600x1200          | 8        | 0.39%   |
| 1280x720 (HD)      | 6        | 0.29%   |
| 2288x1287          | 5        | 0.24%   |
| 2048x1152          | 4        | 0.19%   |
| 1280x960           | 4        | 0.19%   |
| 2560x1600          | 3        | 0.14%   |
| 1280x768           | 2        | 0.1%    |
| 3840x1600          | 1        | 0.05%   |
| 3840x1200          | 1        | 0.05%   |
| 3840x1080          | 1        | 0.05%   |
| Unknown            | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 303      | 14.33%  |
| 21      | 295      | 13.95%  |
| 27      | 272      | 12.87%  |
| 24      | 259      | 12.25%  |
| 19      | 185      | 8.75%   |
| 18      | 122      | 5.77%   |
| 22      | 97       | 4.59%   |
| 17      | 95       | 4.49%   |
| 31      | 87       | 4.12%   |
| 20      | 73       | 3.45%   |
| 84      | 38       | 1.8%    |
| 34      | 38       | 1.8%    |
| 15      | 31       | 1.47%   |
| 32      | 27       | 1.28%   |
| Unknown | 25       | 1.18%   |
| 40      | 21       | 0.99%   |
| 72      | 18       | 0.85%   |
| 54      | 15       | 0.71%   |
| 25      | 14       | 0.66%   |
| 26      | 11       | 0.52%   |
| 65      | 9        | 0.43%   |
| 52      | 9        | 0.43%   |
| 33      | 7        | 0.33%   |
| 12      | 7        | 0.33%   |
| 48      | 6        | 0.28%   |
| 46      | 6        | 0.28%   |
| 39      | 6        | 0.28%   |
| 28      | 5        | 0.24%   |
| 42      | 4        | 0.19%   |
| 35      | 4        | 0.19%   |
| 29      | 4        | 0.19%   |
| 142     | 3        | 0.14%   |
| 55      | 2        | 0.09%   |
| 43      | 2        | 0.09%   |
| 37      | 2        | 0.09%   |
| 14      | 2        | 0.09%   |
| 85      | 1        | 0.05%   |
| 60      | 1        | 0.05%   |
| 58      | 1        | 0.05%   |
| 57      | 1        | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 796      | 38.51%  |
| 401-500        | 671      | 32.46%  |
| 301-350        | 122      | 5.9%    |
| 601-700        | 116      | 5.61%   |
| 351-400        | 106      | 5.13%   |
| 701-800        | 71       | 3.43%   |
| 1501-2000      | 57       | 2.76%   |
| 1001-1500      | 53       | 2.56%   |
| 801-900        | 34       | 1.64%   |
| Unknown        | 25       | 1.21%   |
| 201-300        | 8        | 0.39%   |
| 901-1000       | 5        | 0.24%   |
| More than 2000 | 3        | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1449     | 71.24%  |
| 16/10   | 297      | 14.6%   |
| 5/4     | 182      | 8.95%   |
| 21/9    | 42       | 2.06%   |
| 4/3     | 37       | 1.82%   |
| 3/2     | 10       | 0.49%   |
| 6/5     | 6        | 0.29%   |
| 1.00    | 3        | 0.15%   |
| Unknown | 3        | 0.15%   |
| 32/9    | 2        | 0.1%    |
| 3.20    | 1        | 0.05%   |
| 2.00    | 1        | 0.05%   |
| 1.96    | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 771      | 36.98%  |
| 151-200        | 346      | 16.59%  |
| 301-350        | 280      | 13.43%  |
| 141-150        | 190      | 9.11%   |
| 351-500        | 164      | 7.87%   |
| 251-300        | 112      | 5.37%   |
| More than 1000 | 103      | 4.94%   |
| 501-1000       | 48       | 2.3%    |
| Unknown        | 25       | 1.2%    |
| 101-110        | 23       | 1.1%    |
| 111-120        | 8        | 0.38%   |
| 71-80          | 6        | 0.29%   |
| 81-90          | 3        | 0.14%   |
| 131-140        | 3        | 0.14%   |
| 61-70          | 1        | 0.05%   |
| 121-130        | 1        | 0.05%   |
| 91-100         | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1451     | 71.41%  |
| 101-120 | 384      | 18.9%   |
| 1-50    | 91       | 4.48%   |
| 121-160 | 59       | 2.9%    |
| Unknown | 25       | 1.23%   |
| 161-240 | 22       | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1922     | 89.4%   |
| 2     | 169      | 7.86%   |
| 0     | 42       | 1.95%   |
| 3     | 14       | 0.65%   |
| 4     | 2        | 0.09%   |
| 7     | 1        | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1404     | 49.63%  |
| Intel                           | 729      | 25.77%  |
| Qualcomm Atheros                | 182      | 6.43%   |
| Ralink Technology               | 83       | 2.93%   |
| Broadcom                        | 68       | 2.4%    |
| Nvidia                          | 57       | 2.01%   |
| TP-Link                         | 37       | 1.31%   |
| Ralink                          | 34       | 1.2%    |
| Marvell Technology Group        | 22       | 0.78%   |
| Broadcom Limited                | 21       | 0.74%   |
| Qualcomm Atheros Communications | 20       | 0.71%   |
| D-Link System                   | 15       | 0.53%   |
| NetGear                         | 12       | 0.42%   |
| Huawei Technologies             | 11       | 0.39%   |
| VIA Technologies                | 10       | 0.35%   |
| D-Link                          | 10       | 0.35%   |
| MediaTek                        | 9        | 0.32%   |
| Samsung Electronics             | 8        | 0.28%   |
| Motorola PCS                    | 8        | 0.28%   |
| Aquantia                        | 8        | 0.28%   |
| Microsoft                       | 7        | 0.25%   |
| IMC Networks                    | 6        | 0.21%   |
| Edimax Technology               | 6        | 0.21%   |
| Belkin Components               | 6        | 0.21%   |
| ASUSTek Computer                | 5        | 0.18%   |
| ASIX Electronics                | 4        | 0.14%   |
| Xiaomi                          | 3        | 0.11%   |
| AVM                             | 3        | 0.11%   |
| 3Com                            | 3        | 0.11%   |
| ZTE WCDMA Technologies MSM      | 2        | 0.07%   |
| Spreadtrum Communications       | 2        | 0.07%   |
| OnePlus Technology (Shenzhen)   | 2        | 0.07%   |
| Mercucys                        | 2        | 0.07%   |
| Mellanox Technologies           | 2        | 0.07%   |
| JMicron Technology              | 2        | 0.07%   |
| HTC (High Tech Computer)        | 2        | 0.07%   |
| Chu Yuen Enterprise             | 2        | 0.07%   |
| ZyXEL Communications            | 1        | 0.04%   |
| ZyDAS                           | 1        | 0.04%   |
| vivo                            | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1164     | 37.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80       | 2.56%   |
| Intel Ethernet Connection I217-LM                                 | 75       | 2.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 74       | 2.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 69       | 2.21%   |
| Intel I211 Gigabit Network Connection                             | 61       | 1.95%   |
| Intel Wi-Fi 6 AX200                                               | 57       | 1.82%   |
| Intel Ethernet Connection (2) I219-V                              | 54       | 1.73%   |
| Intel 82579V Gigabit Network Connection                           | 43       | 1.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 36       | 1.15%   |
| Ralink MT7601U Wireless Adapter                                   | 36       | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 35       | 1.12%   |
| Nvidia MCP61 Ethernet                                             | 34       | 1.09%   |
| Intel Ethernet Controller I225-V                                  | 30       | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 28       | 0.9%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 23       | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 23       | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20       | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 20       | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19       | 0.61%   |
| Intel Wireless-AC 9260                                            | 18       | 0.58%   |
| Intel Wireless 3165                                               | 17       | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16       | 0.51%   |
| Ralink RT5370 Wireless Adapter                                    | 16       | 0.51%   |
| Intel Wireless 7260                                               | 16       | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 15       | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 14       | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 14       | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                   | 14       | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 14       | 0.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14       | 0.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 13       | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 13       | 0.42%   |
| Intel Wireless 7265                                               | 13       | 0.42%   |
| Intel 82578DM Gigabit Network Connection                          | 12       | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 12       | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 11       | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 220      | 28.03%  |
| Realtek Semiconductor                 | 198      | 25.22%  |
| Qualcomm Atheros                      | 99       | 12.61%  |
| Ralink Technology                     | 83       | 10.57%  |
| TP-Link                               | 36       | 4.59%   |
| Ralink                                | 34       | 4.33%   |
| Qualcomm Atheros Communications       | 20       | 2.55%   |
| NetGear                               | 12       | 1.53%   |
| Broadcom                              | 11       | 1.4%    |
| D-Link                                | 10       | 1.27%   |
| Microsoft                             | 7        | 0.89%   |
| MediaTek                              | 7        | 0.89%   |
| IMC Networks                          | 6        | 0.76%   |
| Edimax Technology                     | 6        | 0.76%   |
| D-Link System                         | 6        | 0.76%   |
| Belkin Components                     | 6        | 0.76%   |
| ASUSTek Computer                      | 5        | 0.64%   |
| Broadcom Limited                      | 3        | 0.38%   |
| AVM                                   | 3        | 0.38%   |
| Mercucys                              | 2        | 0.25%   |
| Chu Yuen Enterprise                   | 2        | 0.25%   |
| ZyXEL Communications                  | 1        | 0.13%   |
| ZyDAS                                 | 1        | 0.13%   |
| TRENDnet                              | 1        | 0.13%   |
| Philips (or NXP)                      | 1        | 0.13%   |
| Logitec                               | 1        | 0.13%   |
| Linksys                               | 1        | 0.13%   |
| Gemtek                                | 1        | 0.13%   |
| BUFFALO                               | 1        | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 57       | 7.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 36       | 4.55%   |
| Ralink MT7601U Wireless Adapter                            | 36       | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 28       | 3.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 23       | 2.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 19       | 2.4%    |
| Intel Wireless-AC 9260                                     | 18       | 2.28%   |
| Intel Wireless 3165                                        | 17       | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 16       | 2.02%   |
| Ralink RT5370 Wireless Adapter                             | 16       | 2.02%   |
| Intel Wireless 7260                                        | 16       | 2.02%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 14       | 1.77%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 14       | 1.77%   |
| Qualcomm Atheros AR9271 802.11n                            | 14       | 1.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 13       | 1.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 13       | 1.64%   |
| Intel Wireless 7265                                        | 13       | 1.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 11       | 1.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 11       | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 11       | 1.39%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 10       | 1.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 10       | 1.26%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 10       | 1.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 10       | 1.26%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 9        | 1.14%   |
| Realtek 802.11ac NIC                                       | 9        | 1.14%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 9        | 1.14%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 8        | 1.01%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 7        | 0.88%   |
| Ralink RT2561/RT61 802.11g PCI                             | 7        | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 7        | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 7        | 0.88%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 6        | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 6        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 6        | 0.76%   |
| Microsoft Xbox 360 Wireless Adapter                        | 6        | 0.76%   |
| Intel Wireless 8260                                        | 6        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                             | 6        | 0.76%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 6        | 0.76%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 5        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1338     | 59.23%  |
| Intel                             | 592      | 26.21%  |
| Qualcomm Atheros                  | 90       | 3.98%   |
| Nvidia                            | 57       | 2.52%   |
| Broadcom                          | 57       | 2.52%   |
| Marvell Technology Group          | 22       | 0.97%   |
| Broadcom Limited                  | 18       | 0.8%    |
| VIA Technologies                  | 10       | 0.44%   |
| Huawei Technologies               | 10       | 0.44%   |
| D-Link System                     | 9        | 0.4%    |
| Samsung Electronics               | 8        | 0.35%   |
| Aquantia                          | 8        | 0.35%   |
| Motorola PCS                      | 4        | 0.18%   |
| ASIX Electronics                  | 4        | 0.18%   |
| Xiaomi                            | 3        | 0.13%   |
| 3Com                              | 3        | 0.13%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.09%   |
| Spreadtrum Communications         | 2        | 0.09%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.09%   |
| Mellanox Technologies             | 2        | 0.09%   |
| MediaTek                          | 2        | 0.09%   |
| JMicron Technology                | 2        | 0.09%   |
| HTC (High Tech Computer)          | 2        | 0.09%   |
| vivo                              | 1        | 0.04%   |
| TP-Link                           | 1        | 0.04%   |
| T & A Mobile Phones               | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.04%   |
| Qualcomm                          | 1        | 0.04%   |
| OPPO Electronics                  | 1        | 0.04%   |
| Netchip Technology                | 1        | 0.04%   |
| Emulex                            | 1        | 0.04%   |
| DisplayLink                       | 1        | 0.04%   |
| Davicom Semiconductor             | 1        | 0.04%   |
| Adnaco Technology                 | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1164     | 50.02%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80       | 3.44%   |
| Intel Ethernet Connection I217-LM                                 | 75       | 3.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 74       | 3.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 69       | 2.97%   |
| Intel I211 Gigabit Network Connection                             | 61       | 2.62%   |
| Intel Ethernet Connection (2) I219-V                              | 54       | 2.32%   |
| Intel 82579V Gigabit Network Connection                           | 43       | 1.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 1.68%   |
| Intel Ethernet Connection (7) I219-V                              | 35       | 1.5%    |
| Nvidia MCP61 Ethernet                                             | 34       | 1.46%   |
| Intel Ethernet Controller I225-V                                  | 30       | 1.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 23       | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20       | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 20       | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 15       | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 14       | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14       | 0.6%    |
| Intel 82578DM Gigabit Network Connection                          | 12       | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 12       | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 11       | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11       | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 11       | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11       | 0.47%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 10       | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10       | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9        | 0.39%   |
| Intel 82578DC Gigabit Network Connection                          | 9        | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8        | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 8        | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8        | 0.34%   |
| Intel Ethernet Connection (14) I219-V                             | 8        | 0.34%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 8        | 0.34%   |
| Nvidia MCP77 Ethernet                                             | 7        | 0.3%    |
| Intel Ethernet Connection (2) I218-LM                             | 7        | 0.3%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 7        | 0.3%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 6        | 0.26%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2130     | 73.73%  |
| WiFi     | 752      | 26.03%  |
| Unknown  | 5        | 0.17%   |
| Modem    | 2        | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1803     | 85.25%  |
| WiFi     | 312      | 14.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1516     | 70.54%  |
| 2     | 561      | 26.11%  |
| 3     | 48       | 2.23%   |
| 0     | 17       | 0.79%   |
| 4     | 6        | 0.28%   |
| 5     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1505     | 69.74%  |
| Yes  | 653      | 30.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 199      | 42.16%  |
| Cambridge Silicon Radio         | 133      | 28.18%  |
| Realtek Semiconductor           | 36       | 7.63%   |
| ASUSTek Computer                | 25       | 5.3%    |
| Broadcom                        | 20       | 4.24%   |
| Qualcomm Atheros Communications | 18       | 3.81%   |
| IMC Networks                    | 12       | 2.54%   |
| MediaTek                        | 4        | 0.85%   |
| Apple                           | 4        | 0.85%   |
| Lite-On Technology              | 3        | 0.64%   |
| Dynex                           | 3        | 0.64%   |
| TP-Link                         | 2        | 0.42%   |
| Integrated System Solution      | 2        | 0.42%   |
| Accel Semiconductor             | 2        | 0.42%   |
| Unknown                         | 2        | 0.42%   |
| SINO WEALTH                     | 1        | 0.21%   |
| Ralink                          | 1        | 0.21%   |
| Primax Electronics              | 1        | 0.21%   |
| Foxconn / Hon Hai               | 1        | 0.21%   |
| Edimax Technology               | 1        | 0.21%   |
| Dell                            | 1        | 0.21%   |
| Belkin Components               | 1        | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 133      | 28.18%  |
| Intel Bluetooth wireless interface                       | 57       | 12.08%  |
| Intel AX200 Bluetooth                                    | 53       | 11.23%  |
| Intel Wireless-AC 3168 Bluetooth                         | 25       | 5.3%    |
| Realtek Bluetooth Radio                                  | 22       | 4.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 17       | 3.6%    |
| Intel AX201 Bluetooth                                    | 17       | 3.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 13       | 2.75%   |
| Realtek  Bluetooth 4.2 Adapter                           | 11       | 2.33%   |
| Intel AX210 Bluetooth                                    | 11       | 2.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 11       | 2.33%   |
| IMC Networks Bluetooth Radio                             | 9        | 1.91%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 9        | 1.91%   |
| ASUS ASUS USB-BT500                                      | 8        | 1.69%   |
| Qualcomm Atheros  Bluetooth Device                       | 7        | 1.48%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 4        | 0.85%   |
| MediaTek Wireless_Device                                 | 4        | 0.85%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 4        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 3        | 0.64%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 3        | 0.64%   |
| TP-Link TP-Cdj+ UB5A Adapter                             | 2        | 0.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 2        | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 2        | 0.42%   |
| Intel Bluetooth Device                                   | 2        | 0.42%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 2        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 0.42%   |
| ASUS Bluetooth Radio                                     | 2        | 0.42%   |
| ASUS Bluetooth Adapter                                   | 2        | 0.42%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 2        | 0.42%   |
| Accel Bluetooth Device                                   | 2        | 0.42%   |
| Unknown                                                  | 2        | 0.42%   |
| SINO WEALTH RK Bluetooth Keyboar                         | 1        | 0.21%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1        | 0.21%   |
| Realtek Bluetooth 5.1 Radio                              | 1        | 0.21%   |
| Realtek 802.11ac WLAN Adapter                            | 1        | 0.21%   |
| Ralink RT3290 Bluetooth                                  | 1        | 0.21%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter            | 1        | 0.21%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1        | 0.21%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1385     | 41.94%  |
| AMD                                          | 864      | 26.17%  |
| Nvidia                                       | 721      | 21.84%  |
| C-Media Electronics                          | 79       | 2.39%   |
| Creative Labs                                | 50       | 1.51%   |
| Logitech                                     | 28       | 0.85%   |
| Texas Instruments                            | 18       | 0.55%   |
| Creative Technology                          | 11       | 0.33%   |
| ASUSTek Computer                             | 11       | 0.33%   |
| JMTek                                        | 10       | 0.3%    |
| Generalplus Technology                       | 8        | 0.24%   |
| VIA Technologies                             | 7        | 0.21%   |
| GN Netcom                                    | 7        | 0.21%   |
| Plantronics                                  | 6        | 0.18%   |
| XMOS                                         | 4        | 0.12%   |
| Tenx Technology                              | 4        | 0.12%   |
| Kingston Technology                          | 4        | 0.12%   |
| Blue Microphones                             | 4        | 0.12%   |
| SteelSeries ApS                              | 3        | 0.09%   |
| Sony                                         | 3        | 0.09%   |
| Samson Technologies                          | 3        | 0.09%   |
| Razer USA                                    | 3        | 0.09%   |
| KTMicro                                      | 3        | 0.09%   |
| Corsair                                      | 3        | 0.09%   |
| BEHRINGER International                      | 3        | 0.09%   |
| Trust                                        | 2        | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.06%   |
| ROCCAT                                       | 2        | 0.06%   |
| QinHeng Electronics                          | 2        | 0.06%   |
| PreSonus Audio Electronics                   | 2        | 0.06%   |
| Micro Star International                     | 2        | 0.06%   |
| Medeli Electronics                           | 2        | 0.06%   |
| Hewlett-Packard                              | 2        | 0.06%   |
| GYROCOM C&C                                  | 2        | 0.06%   |
| Giga-Byte Technology                         | 2        | 0.06%   |
| FiiO Electronics Technology                  | 2        | 0.06%   |
| Audient                                      | 2        | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.03%   |
| ZOOM                                         | 1        | 0.03%   |
| Xilinx                                       | 1        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 208      | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 190      | 4.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 186      | 4.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 160      | 4.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 134      | 3.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 124      | 3.19%   |
| AMD FCH Azalia Controller                                                         | 122      | 3.14%   |
| AMD Family 17h/19h HD Audio Controller                                            | 118      | 3.04%   |
| AMD Starship/Matisse HD Audio Controller                                          | 114      | 2.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 104      | 2.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 89       | 2.29%   |
| Intel 200 Series PCH HD Audio                                                     | 80       | 2.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 77       | 1.98%   |
| Nvidia High Definition Audio Controller                                           | 70       | 1.8%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 70       | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                        | 67       | 1.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 66       | 1.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 64       | 1.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 63       | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 61       | 1.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 59       | 1.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 54       | 1.39%   |
| Nvidia GF108 High Definition Audio Controller                                     | 51       | 1.31%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 50       | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 45       | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 41       | 1.06%   |
| Nvidia MCP61 High Definition Audio                                                | 39       | 1%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 37       | 0.95%   |
| Nvidia GF119 HDMI Audio Controller                                                | 36       | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 36       | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                                     | 34       | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 30       | 0.77%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 30       | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                                     | 29       | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                | 27       | 0.69%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 27       | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                                     | 25       | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                 | 25       | 0.64%   |
| AMD Kabini HDMI/DP Audio                                                          | 25       | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 23       | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 472      | 18.42%  |
| Kingston            | 457      | 17.83%  |
| Samsung Electronics | 256      | 9.99%   |
| Corsair             | 192      | 7.49%   |
| SK hynix            | 191      | 7.45%   |
| Crucial             | 186      | 7.26%   |
| G.Skill             | 162      | 6.32%   |
| Micron Technology   | 141      | 5.5%    |
| A-DATA Technology   | 56       | 2.18%   |
| Unknown             | 47       | 1.83%   |
| Patriot             | 37       | 1.44%   |
| Nanya Technology    | 36       | 1.4%    |
| Ramaxel Technology  | 31       | 1.21%   |
| Team                | 29       | 1.13%   |
| Elpida              | 22       | 0.86%   |
| GOODRAM             | 21       | 0.82%   |
| Transcend           | 19       | 0.74%   |
| Smart               | 19       | 0.74%   |
| AMD                 | 11       | 0.43%   |
| Silicon Power       | 10       | 0.39%   |
| Kingmax             | 9        | 0.35%   |
| GeIL                | 8        | 0.31%   |
| Apacer              | 8        | 0.31%   |
| Unknown (ABCD)      | 7        | 0.27%   |
| PNY                 | 7        | 0.27%   |
| Unifosa             | 6        | 0.23%   |
| CSX                 | 6        | 0.23%   |
| Teikon              | 5        | 0.2%    |
| Qimonda             | 5        | 0.2%    |
| Super Talent        | 4        | 0.16%   |
| OM Nanotech         | 4        | 0.16%   |
| Ramos Technology    | 3        | 0.12%   |
| Kllisre             | 3        | 0.12%   |
| KLEVV               | 3        | 0.12%   |
| Goldkey             | 3        | 0.12%   |
| Wilk Elektronik     | 2        | 0.08%   |
| V-GeN               | 2        | 0.08%   |
| Unknown (2C0B)      | 2        | 0.08%   |
| Unknown (0x0DD5)    | 2        | 0.08%   |
| Sesame              | 2        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown                                                  | 47       | 1.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 38       | 1.34%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 36       | 1.27%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 33       | 1.16%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 27       | 0.95%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 23       | 0.81%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 23       | 0.81%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 21       | 0.74%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 20       | 0.71%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                 | 18       | 0.64%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s    | 18       | 0.64%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 17       | 0.6%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 17       | 0.6%    |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1648MT/s      | 16       | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 15       | 0.53%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 15       | 0.53%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 15       | 0.53%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s      | 15       | 0.53%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 15       | 0.53%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 15       | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 14       | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 14       | 0.49%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 13       | 0.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 13       | 0.46%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 13       | 0.46%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 13       | 0.46%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 12       | 0.42%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 12       | 0.42%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 12       | 0.42%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 12       | 0.42%   |
| Kingston RAM 99U5471-054.A00LF 8192MB DIMM DDR3 1600MT/s | 12       | 0.42%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 11       | 0.39%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 11       | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 11       | 0.39%   |
| Samsung RAM M378B5773CH0-CH9 2048MB DIMM DDR3 1867MT/s   | 11       | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 11       | 0.39%   |
| Unknown RAM Module 1GB DIMM 800MT/s                      | 10       | 0.35%   |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 10       | 0.35%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s     | 10       | 0.35%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s    | 10       | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 907      | 41.51%  |
| DDR4    | 729      | 33.36%  |
| Unknown | 181      | 8.28%   |
| DDR2    | 170      | 7.78%   |
| SDRAM   | 151      | 6.91%   |
| DDR     | 32       | 1.46%   |
| LPDDR4  | 9        | 0.41%   |
| DDR5    | 5        | 0.23%   |
| DRAM    | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1993     | 93.57%  |
| SODIMM       | 130      | 6.1%    |
| RIMM         | 3        | 0.14%   |
| FB-DIMM      | 3        | 0.14%   |
| Row Of Chips | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 814      | 33.39%  |
| 4096  | 722      | 29.61%  |
| 2048  | 500      | 20.51%  |
| 16384 | 199      | 8.16%   |
| 1024  | 137      | 5.62%   |
| 32768 | 45       | 1.85%   |
| 512   | 21       | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 557      | 22.61%  |
| 1333    | 367      | 14.9%   |
| 800     | 140      | 5.68%   |
| 3200    | 132      | 5.36%   |
| 2400    | 132      | 5.36%   |
| 3600    | 112      | 4.55%   |
| 2667    | 104      | 4.22%   |
| 2133    | 103      | 4.18%   |
| Unknown | 83       | 3.37%   |
| 667     | 82       | 3.33%   |
| 1867    | 56       | 2.27%   |
| 2666    | 53       | 2.15%   |
| 1866    | 52       | 2.11%   |
| 3400    | 38       | 1.54%   |
| 1800    | 35       | 1.42%   |
| 3000    | 32       | 1.3%    |
| 1066    | 28       | 1.14%   |
| 2933    | 24       | 0.97%   |
| 400     | 24       | 0.97%   |
| 3733    | 22       | 0.89%   |
| 533     | 22       | 0.89%   |
| 1067    | 21       | 0.85%   |
| 3866    | 17       | 0.69%   |
| 2048    | 14       | 0.57%   |
| 3466    | 13       | 0.53%   |
| 1334    | 13       | 0.53%   |
| 3666    | 11       | 0.45%   |
| 2800    | 11       | 0.45%   |
| 3800    | 10       | 0.41%   |
| 2000    | 9        | 0.37%   |
| 49926   | 8        | 0.32%   |
| 3066    | 7        | 0.28%   |
| 1639    | 7        | 0.28%   |
| 333     | 7        | 0.28%   |
| 3533    | 6        | 0.24%   |
| 2200    | 6        | 0.24%   |
| 1648    | 6        | 0.24%   |
| 3334    | 5        | 0.2%    |
| 3333    | 5        | 0.2%    |
| 4800    | 4        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 54       | 39.13%  |
| Brother Industries    | 31       | 22.46%  |
| Canon                 | 17       | 12.32%  |
| Samsung Electronics   | 12       | 8.7%    |
| Seiko Epson           | 9        | 6.52%   |
| Lexmark International | 5        | 3.62%   |
| Xerox                 | 2        | 1.45%   |
| Kyocera               | 2        | 1.45%   |
| Zebra                 | 1        | 0.72%   |
| Ricoh                 | 1        | 0.72%   |
| QinHeng Electronics   | 1        | 0.72%   |
| NXP Semiconductors    | 1        | 0.72%   |
| Dymo-CoStar           | 1        | 0.72%   |
| Citizen               | 1        | 0.72%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Samsung M2070 Series                         | 3        | 2.17%   |
| HP LaserJet 1020                             | 3        | 2.17%   |
| HP LaserJet 1010                             | 3        | 2.17%   |
| HP ENVY 4520 series                          | 3        | 2.17%   |
| Seiko Epson ET-4760 Series                   | 2        | 1.45%   |
| Samsung SCX-3400 Series                      | 2        | 1.45%   |
| Samsung M2020 Series                         | 2        | 1.45%   |
| Samsung CLP-310 Color Laser Printer          | 2        | 1.45%   |
| HP LaserJet P1005                            | 2        | 1.45%   |
| HP LaserJet 1200                             | 2        | 1.45%   |
| HP LaserJet 1018                             | 2        | 1.45%   |
| HP Ink Tank Wireless 410 series              | 2        | 1.45%   |
| HP ENVY 4500 series                          | 2        | 1.45%   |
| HP DeskJet 5550                              | 2        | 1.45%   |
| HP DeskJet 2700 series                       | 2        | 1.45%   |
| HP Deskjet 1050 J410                         | 2        | 1.45%   |
| Canon TS5100 series                          | 2        | 1.45%   |
| Canon PIXMA MG3600 Series                    | 2        | 1.45%   |
| Brother MFC-L2710DW series                   | 2        | 1.45%   |
| Brother MFC-J470DW                           | 2        | 1.45%   |
| Brother DCP-T310                             | 2        | 1.45%   |
| Zebra LP2824                                 | 1        | 0.72%   |
| Xerox Phaser 6510                            | 1        | 0.72%   |
| Xerox Phaser 6010N                           | 1        | 0.72%   |
| Seiko Epson XP-2100 Series                   | 1        | 0.72%   |
| Seiko Epson WF-2510 Series                   | 1        | 0.72%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.72%   |
| Seiko Epson L6160 Series                     | 1        | 0.72%   |
| Seiko Epson L365 Series                      | 1        | 0.72%   |
| Seiko Epson L3150 Series                     | 1        | 0.72%   |
| Seiko Epson L120 Series                      | 1        | 0.72%   |
| Samsung ML-2850 Series                       | 1        | 0.72%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 0.72%   |
| Samsung M267x 287x Series                    | 1        | 0.72%   |
| Ricoh SP 211                                 | 1        | 0.72%   |
| QinHeng CH340S                               | 1        | 0.72%   |
| NXP Semiconductors Printer-80                | 1        | 0.72%   |
| Lexmark International X364dn                 | 1        | 0.72%   |
| Lexmark International MS710                  | 1        | 0.72%   |
| Lexmark International E360d                  | 1        | 0.72%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 13       | 72.22%  |
| Seiko Epson     | 2        | 11.11%  |
| Mustek Systems  | 2        | 11.11%  |
| Hewlett-Packard | 1        | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 2        | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20            | 2        | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                 | 2        | 11.11%  |
| Canon CanoScan LiDE 120                       | 2        | 11.11%  |
| Canon CanoScan LiDE 110                       | 2        | 11.11%  |
| Canon CanoScan LiDE 100                       | 2        | 11.11%  |
| Mustek Systems SNAPSCAN e22                   | 1        | 5.56%   |
| Mustek Systems ScanExpress 1200 CU            | 1        | 5.56%   |
| HP ScanJet 2400c                              | 1        | 5.56%   |
| Canon CanoScan LIDE 25                        | 1        | 5.56%   |
| Canon CanoScan LiDE 210                       | 1        | 5.56%   |
| Canon CanoScan 5200F                          | 1        | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 113      | 39.37%  |
| Microdia                      | 21       | 7.32%   |
| Microsoft                     | 19       | 6.62%   |
| Generalplus Technology        | 12       | 4.18%   |
| Realtek Semiconductor         | 9        | 3.14%   |
| KYE Systems (Mouse Systems)   | 9        | 3.14%   |
| Chicony Electronics           | 8        | 2.79%   |
| Aveo Technology               | 7        | 2.44%   |
| Z-Star Microelectronics       | 6        | 2.09%   |
| Cubeternet                    | 6        | 2.09%   |
| Sunplus Innovation Technology | 5        | 1.74%   |
| Samsung Electronics           | 5        | 1.74%   |
| Hewlett-Packard               | 5        | 1.74%   |
| Apple                         | 5        | 1.74%   |
| Trust                         | 4        | 1.39%   |
| ARC International             | 4        | 1.39%   |
| Unknown                       | 3        | 1.05%   |
| Jieli Technology              | 3        | 1.05%   |
| GEMBIRD                       | 3        | 1.05%   |
| Creative Technology           | 3        | 1.05%   |
| Pixart Imaging                | 2        | 0.7%    |
| MacroSilicon                  | 2        | 0.7%    |
| IMC Networks                  | 2        | 0.7%    |
| HDR webcam                    | 2        | 0.7%    |
| Genesys Logic                 | 2        | 0.7%    |
| AVerMedia Technologies        | 2        | 0.7%    |
| Alcor Micro                   | 2        | 0.7%    |
| YT-221117-J                   | 1        | 0.35%   |
| WCM_USB                       | 1        | 0.35%   |
| WaveRider Communications      | 1        | 0.35%   |
| Valve Software                | 1        | 0.35%   |
| USB3.0 HD Audio Capture       | 1        | 0.35%   |
| Tobii Technology AB           | 1        | 0.35%   |
| SunplusIT                     | 1        | 0.35%   |
| Sonix Technology              | 1        | 0.35%   |
| Silicon Motion                | 1        | 0.35%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 0.35%   |
| Remo Tech                     | 1        | 0.35%   |
| Razer USA                     | 1        | 0.35%   |
| OPPO Electronics              | 1        | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 29       | 10.03%  |
| Logitech HD Webcam C525                 | 14       | 4.84%   |
| Logitech HD Pro Webcam C920             | 12       | 4.15%   |
| Generalplus GENERAL WEBCAM              | 11       | 3.81%   |
| Microsoft LifeCam HD-3000               | 10       | 3.46%   |
| Logitech Webcam C170                    | 9        | 3.11%   |
| Logitech HD Webcam C615                 | 7        | 2.42%   |
| Logitech Webcam C310                    | 6        | 2.08%   |
| Aveo USB2.0 Camera                      | 6        | 2.08%   |
| Samsung Galaxy series, misc. (MTP mode) | 5        | 1.73%   |
| Microdia Camera                         | 5        | 1.73%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 5        | 1.73%   |
| Microdia USB Camera                     | 4        | 1.38%   |
| ARC International Camera                | 4        | 1.38%   |
| Unknown HD camera                       | 3        | 1.04%   |
| Microdia Webcam Vitade AF               | 3        | 1.04%   |
| Microdia Integrated Camera              | 3        | 1.04%   |
| Logitech Webcam Pro 9000                | 3        | 1.04%   |
| Logitech HD Webcam C510                 | 3        | 1.04%   |
| Logitech C922 Pro Stream Webcam         | 3        | 1.04%   |
| Jieli USB PHY 2.0                       | 3        | 1.04%   |
| HP Webcam HD 2300                       | 3        | 1.04%   |
| Cubeternet USB2.0 Camera                | 3        | 1.04%   |
| Z-Star A4 TECH USB2.0 PC Camera J       | 2        | 0.69%   |
| Trust WB-6250X Webcam                   | 2        | 0.69%   |
| Sunplus WEBCAM ESSENTIELB W1            | 2        | 0.69%   |
| Sunplus HD 720P webcam                  | 2        | 0.69%   |
| Realtek Thronmax Webcam Mic             | 2        | 0.69%   |
| Realtek Thronmax StreamGo Webcam        | 2        | 0.69%   |
| Realtek NexiGo N960E FHD Webcam         | 2        | 0.69%   |
| Realtek FULL HD 1080P Webcam            | 2        | 0.69%   |
| Microsoft LifeCam VX-800                | 2        | 0.69%   |
| Microsoft LifeCam Studio                | 2        | 0.69%   |
| Microsoft LifeCam Cinema                | 2        | 0.69%   |
| MacroSilicon USB Video                  | 2        | 0.69%   |
| Logitech Webcam C930e                   | 2        | 0.69%   |
| Logitech Webcam C250                    | 2        | 0.69%   |
| Logitech Webcam C110                    | 2        | 0.69%   |
| Logitech QuickCam Pro 9000              | 2        | 0.69%   |
| Logitech QuickCam E 3500                | 2        | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Validity Sensors      | 1        | 33.33%  |
| Upek                  | 1        | 33.33%  |
| LighTuning Technology | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 33.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 33.33%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 25%     |
| Gemalto (was Gemplus) | 2        | 25%     |
| BIT4ID                | 2        | 25%     |
| SCM Microsystems      | 1        | 12.5%   |
| Cherry                | 1        | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2        | 25%     |
| SCM Microsystems CLOUD 2700 F Smart Card Reader   | 1        | 12.5%   |
| Cherry Smart Terminal XX44                        | 1        | 12.5%   |
| Bit4id miniLector EVO                             | 1        | 12.5%   |
| BIT4ID miniLector AIR NFC v3                      | 1        | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1932     | 89.9%   |
| 1     | 201      | 9.35%   |
| 2     | 11       | 0.51%   |
| 3     | 3        | 0.14%   |
| 7     | 1        | 0.05%   |
| 4     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 109      | 47.6%   |
| Net/wireless             | 47       | 20.52%  |
| Unassigned class         | 16       | 6.99%   |
| Communication controller | 15       | 6.55%   |
| Multimedia controller    | 9        | 3.93%   |
| Bluetooth                | 8        | 3.49%   |
| Chipcard                 | 7        | 3.06%   |
| Wireless                 | 3        | 1.31%   |
| Network                  | 3        | 1.31%   |
| Fingerprint reader       | 3        | 1.31%   |
| Camera                   | 3        | 1.31%   |
| Storage/raid             | 2        | 0.87%   |
| Net/ethernet             | 2        | 0.87%   |
| Card reader              | 2        | 0.87%   |

