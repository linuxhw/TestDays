Linux in Venezuela - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

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

Total: 162

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Intel    | H61                         | [326fa40958](https://linux-hardware.org/?probe=326fa40958) | Nov 01, 2022 |
| ECS      | H61H2-CM                    | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASRock   | N68-VS3 UCC                 | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell     | 0200DY A02                  | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ECS      | A890GXM-A2                  | [d6f77b12c2](https://linux-hardware.org/?probe=d6f77b12c2) | Oct 09, 2022 |
| ECS      | H61H2-CM                    | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| ASRock   | G41M-VS3                    | [21cfcdcbdd](https://linux-hardware.org/?probe=21cfcdcbdd) | Sep 23, 2022 |
| ASRock   | 960GM-VGS3 FX               | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| ASRock   | H61M-DGS                    | [51b15f6d34](https://linux-hardware.org/?probe=51b15f6d34) | Sep 06, 2022 |
| Gigabyte | M68MT-S2                    | [b3b173a476](https://linux-hardware.org/?probe=b3b173a476) | Sep 04, 2022 |
| ASRock   | N68-VS3 UCC                 | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock   | N68-VS3 UCC                 | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| HP       | 0A60h                       | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| ASUSTek  | P5G41T-M LX V2              | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| HP       | 1497                        | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek  | P8H77-V LE                  | [4bd2fabdc7](https://linux-hardware.org/?probe=4bd2fabdc7) | Aug 26, 2022 |
| ASRock   | G41M-VS3                    | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Biostar  | A780L3B                     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| ECS      | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| HP       | 339A                        | [c19f3d1361](https://linux-hardware.org/?probe=c19f3d1361) | Jul 29, 2022 |
| Lenovo   | ThinkCentre M91 7516AD1     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| MSI      | H81M-E33                    | [737e14fea7](https://linux-hardware.org/?probe=737e14fea7) | Jul 01, 2022 |
| Pegatron | IPPSB-DB                    | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| ECS      | H61H2-MV                    | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| ASRock   | H370M-HDV                   | [4d6a88cd74](https://linux-hardware.org/?probe=4d6a88cd74) | Jun 16, 2022 |
| langchao | IPM41-D3                    | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Dell     | 0N4YC8 A00                  | [5d8aa17afc](https://linux-hardware.org/?probe=5d8aa17afc) | Jun 10, 2022 |
| Dell     | 0N4YC8 A00                  | [a502ed154f](https://linux-hardware.org/?probe=a502ed154f) | Jun 10, 2022 |
| Lenovo   | 11051CS ThinkServer TS13... | [48e6a5501d](https://linux-hardware.org/?probe=48e6a5501d) | May 26, 2022 |
| ECS      | H61H2-MV                    | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| IP3 Tech | TB20                        | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Intel    | H61                         | [28277b5d5a](https://linux-hardware.org/?probe=28277b5d5a) | May 10, 2022 |
| ECS      | H61H2-CM                    | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| ASRock   | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock   | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Intel    | MAHOBAY                     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| ASRock   | G31M-S                      | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| Intel    | D945GCCR AAD78647-300       | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| ASRock   | H370M-HDV                   | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| Inspur   | Computer All in one PC V... | [5c419895c5](https://linux-hardware.org/?probe=5c419895c5) | Mar 18, 2022 |
| MSI      | 3664h                       | [e5eaec6553](https://linux-hardware.org/?probe=e5eaec6553) | Mar 08, 2022 |
| Pegatron | IPM41-D3                    | [0e8fbc26f1](https://linux-hardware.org/?probe=0e8fbc26f1) | Mar 01, 2022 |
| Pegatron | 2ACC                        | [c1127626c5](https://linux-hardware.org/?probe=c1127626c5) | Mar 01, 2022 |
| Dell     | 0PTTT9 A01                  | [89cecb62bc](https://linux-hardware.org/?probe=89cecb62bc) | Feb 17, 2022 |
| ECS      | KAM1-I                      | [be38f855ff](https://linux-hardware.org/?probe=be38f855ff) | Feb 10, 2022 |
| ASRock   | A55M-HVS                    | [c4c68e7dd1](https://linux-hardware.org/?probe=c4c68e7dd1) | Feb 08, 2022 |
| ASUSTek  | P6X58-E PRO                 | [9ee8e1ecdf](https://linux-hardware.org/?probe=9ee8e1ecdf) | Jan 30, 2022 |
| Intel    | DG41TY AAE47335-203         | [01ec1ff569](https://linux-hardware.org/?probe=01ec1ff569) | Jan 26, 2022 |
| Dell     | 0GDG8Y A00                  | [8700fd1193](https://linux-hardware.org/?probe=8700fd1193) | Jan 11, 2022 |
| ASRock   | N68-VS3 UCC                 | [b6cffe86a0](https://linux-hardware.org/?probe=b6cffe86a0) | Dec 23, 2021 |
| Gigabyte | H110M-H-CF                  | [8d19cd079a](https://linux-hardware.org/?probe=8d19cd079a) | Dec 09, 2021 |
| Gigabyte | H110M-H-CF                  | [ecd0add9b3](https://linux-hardware.org/?probe=ecd0add9b3) | Dec 09, 2021 |
| HP       | 3398                        | [5ae73e1468](https://linux-hardware.org/?probe=5ae73e1468) | Dec 07, 2021 |
| ECS      | H61H2-CM                    | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Intel    | DG35EC AAE29266-205         | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel    | DG35EC AAE29266-205         | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| Biostar  | P4M90-M7A Ver:1.0           | [d8875918ac](https://linux-hardware.org/?probe=d8875918ac) | Oct 16, 2021 |
| Gigabyte | Z97N-WIFI                   | [1ec421714e](https://linux-hardware.org/?probe=1ec421714e) | Oct 02, 2021 |
| HP       | 1495                        | [64cbb112e2](https://linux-hardware.org/?probe=64cbb112e2) | Oct 01, 2021 |
| ECS      | H61H2-CM                    | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| Foxconn  | M61PMV FAB                  | [290d3e0fd5](https://linux-hardware.org/?probe=290d3e0fd5) | Sep 14, 2021 |
| ASRock   | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| ECS      | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Foxconn  | ELA01                       | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Foxconn  | ELA01                       | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| ASUSTek  | Rampage III GENE            | [ab44db5647](https://linux-hardware.org/?probe=ab44db5647) | Jul 18, 2021 |
| Lenovo   | ThinkCentre M71e 3157G6S    | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| ASUSTek  | Rampage III GENE            | [60c62c33f8](https://linux-hardware.org/?probe=60c62c33f8) | Jul 14, 2021 |
| Biostar  | G41D3                       | [673d4faa98](https://linux-hardware.org/?probe=673d4faa98) | Jul 12, 2021 |
| HP       | 3397                        | [f1a6d10d78](https://linux-hardware.org/?probe=f1a6d10d78) | Jul 08, 2021 |
| HP       | 3397                        | [e087e03e0b](https://linux-hardware.org/?probe=e087e03e0b) | Jul 08, 2021 |
| ASRock   | G41M-S3                     | [a57f28921c](https://linux-hardware.org/?probe=a57f28921c) | Jul 05, 2021 |
| ECS      | Livermore                   | [b471a4666c](https://linux-hardware.org/?probe=b471a4666c) | Jun 30, 2021 |
| Biostar  | P4M900-M7 FE Ver:1.0        | [a82bafec08](https://linux-hardware.org/?probe=a82bafec08) | Jun 29, 2021 |
| ECS      | Livermore                   | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| ASRock   | H61M-VS                     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| langchao | IPM41-D3                    | [512537c402](https://linux-hardware.org/?probe=512537c402) | Jun 17, 2021 |
| langchao | IPM41-D3                    | [9773736b0f](https://linux-hardware.org/?probe=9773736b0f) | Jun 17, 2021 |
| ECS      | G31T-M7                     | [01ed8410e9](https://linux-hardware.org/?probe=01ed8410e9) | Jun 15, 2021 |
| Lenovo   | ThinkCentre M55E 9645BN2    | [ef91279611](https://linux-hardware.org/?probe=ef91279611) | Jun 15, 2021 |
| Biostar  | G41D3C                      | [263491c02a](https://linux-hardware.org/?probe=263491c02a) | Jun 07, 2021 |
| ECS      | H61H2-CM                    | [42960896cb](https://linux-hardware.org/?probe=42960896cb) | May 20, 2021 |
| ECS      | H61H2-CM                    | [4856303cbe](https://linux-hardware.org/?probe=4856303cbe) | May 20, 2021 |
| ASRock   | H61M-VS                     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock   | H61M-VS                     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Pegatron | 2A73h                       | [8d84f6dc9e](https://linux-hardware.org/?probe=8d84f6dc9e) | Apr 25, 2021 |
| ASUSTek  | P5Q                         | [db04624ac3](https://linux-hardware.org/?probe=db04624ac3) | Apr 20, 2021 |
| Intel    | DG31PR AAD97573-302         | [330f034c61](https://linux-hardware.org/?probe=330f034c61) | Apr 04, 2021 |
| Intel    | DG31PR AAD97573-302         | [4cf71fac35](https://linux-hardware.org/?probe=4cf71fac35) | Apr 04, 2021 |
| Gigabyte | Z68X-UD3H-B3                | [7f2618efb7](https://linux-hardware.org/?probe=7f2618efb7) | Mar 12, 2021 |
| HP       | 1495                        | [248af9611e](https://linux-hardware.org/?probe=248af9611e) | Mar 11, 2021 |
| Dell     | 0GX297                      | [6ac3da669a](https://linux-hardware.org/?probe=6ac3da669a) | Mar 09, 2021 |
| langchao | IPM41-D3                    | [543e8d3501](https://linux-hardware.org/?probe=543e8d3501) | Mar 07, 2021 |
| langchao | IPM41-D3                    | [892f3e6658](https://linux-hardware.org/?probe=892f3e6658) | Mar 07, 2021 |
| Pegatron | NARRA5                      | [e7550259a4](https://linux-hardware.org/?probe=e7550259a4) | Mar 06, 2021 |
| Pegatron | NARRA5                      | [294b1c19fb](https://linux-hardware.org/?probe=294b1c19fb) | Feb 20, 2021 |
| ASRock   | G41M-VS3                    | [9e6a12d9e1](https://linux-hardware.org/?probe=9e6a12d9e1) | Feb 15, 2021 |
| Gigabyte | G1.Sniper B5-CF             | [e4d1cc65bc](https://linux-hardware.org/?probe=e4d1cc65bc) | Jan 27, 2021 |
| HP       | 1493                        | [febb5aee31](https://linux-hardware.org/?probe=febb5aee31) | Jan 15, 2021 |
| ASRock   | G41M-VS3                    | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Pegatron | IPM41-D3                    | [4e0489bdb0](https://linux-hardware.org/?probe=4e0489bdb0) | Dec 05, 2020 |
| ASRock   | AM2NF6G-VSTA                | [5751926628](https://linux-hardware.org/?probe=5751926628) | Nov 23, 2020 |
| ASRock   | AM2NF6G-VSTA                | [812b2188d4](https://linux-hardware.org/?probe=812b2188d4) | Nov 23, 2020 |
| Biostar  | A55MLC2                     | [e195f622e4](https://linux-hardware.org/?probe=e195f622e4) | Nov 22, 2020 |
| Biostar  | A55MLC2                     | [a0456b9ad3](https://linux-hardware.org/?probe=a0456b9ad3) | Nov 22, 2020 |
| HP       | 1495                        | [72bdee2784](https://linux-hardware.org/?probe=72bdee2784) | Nov 19, 2020 |
| Foxconn  | M61PMV FAB A1               | [cb7568786f](https://linux-hardware.org/?probe=cb7568786f) | Oct 05, 2020 |
| ASUSTek  | P5G41T-M LX                 | [db328c3c01](https://linux-hardware.org/?probe=db328c3c01) | Sep 29, 2020 |
| ECS      | H61H2-CM                    | [8ae7ffac0b](https://linux-hardware.org/?probe=8ae7ffac0b) | Sep 28, 2020 |
| Unknown  | 4CoreDX90-VSTA              | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Pegatron | 2A73h                       | [5f5f0bd2cf](https://linux-hardware.org/?probe=5f5f0bd2cf) | Aug 29, 2020 |
| Biostar  | N68S3B                      | [1e4d89cafe](https://linux-hardware.org/?probe=1e4d89cafe) | Aug 27, 2020 |
| MSI      | FM2-A75MA-E35               | [7f40a96159](https://linux-hardware.org/?probe=7f40a96159) | Aug 20, 2020 |
| Gigabyte | 970A-DS3P                   | [8445b18759](https://linux-hardware.org/?probe=8445b18759) | Aug 20, 2020 |
| ECS      | H61H2-CM                    | [43d0144f0a](https://linux-hardware.org/?probe=43d0144f0a) | Aug 06, 2020 |
| MSI      | K9N2 Diamond                | [07a001660f](https://linux-hardware.org/?probe=07a001660f) | Aug 04, 2020 |
| Intel    | DG31PR AAD97573-302         | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| ASRock   | G41M-VS3                    | [a2e742ec36](https://linux-hardware.org/?probe=a2e742ec36) | Jul 27, 2020 |
| ASRock   | G41M-VS3                    | [6786c103d7](https://linux-hardware.org/?probe=6786c103d7) | Jul 27, 2020 |
| Intel    | DG31PR AAD97573-302         | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| ASRock   | G41M-VS3                    | [39510acc74](https://linux-hardware.org/?probe=39510acc74) | Jul 06, 2020 |
| ASRock   | G41M-VS3                    | [eff9ad2c7d](https://linux-hardware.org/?probe=eff9ad2c7d) | Jul 05, 2020 |
| langchao | IPM41-D3                    | [a1e610807e](https://linux-hardware.org/?probe=a1e610807e) | Jun 30, 2020 |
| langchao | IPM41-D3                    | [e8c521f7e8](https://linux-hardware.org/?probe=e8c521f7e8) | Jun 25, 2020 |
| Intel    | DG33BU AAD79951-407         | [cd52689b0a](https://linux-hardware.org/?probe=cd52689b0a) | May 25, 2020 |
| Intel    | DG33BU AAD79951-407         | [d48d360c14](https://linux-hardware.org/?probe=d48d360c14) | May 25, 2020 |
| Lenovo   | ThinkCentre A55 8705AV4     | [18c81b7e8b](https://linux-hardware.org/?probe=18c81b7e8b) | May 19, 2020 |
| Lenovo   | ThinkCentre A55 8705AV4     | [cce631f67b](https://linux-hardware.org/?probe=cce631f67b) | May 19, 2020 |
| Intel    | DG41TX AAE78178-303         | [084641dbc1](https://linux-hardware.org/?probe=084641dbc1) | May 17, 2020 |
| Gigabyte | 970A-DS3P                   | [97e5a8c8da](https://linux-hardware.org/?probe=97e5a8c8da) | Apr 26, 2020 |
| Pegatron | 2A73h                       | [b3436f0ec6](https://linux-hardware.org/?probe=b3436f0ec6) | Apr 11, 2020 |
| langchao | IPM41-D3                    | [841ded939f](https://linux-hardware.org/?probe=841ded939f) | Mar 31, 2020 |
| Lenovo   | ThinkCentre A58 7515A33     | [75be0ab7ac](https://linux-hardware.org/?probe=75be0ab7ac) | Mar 26, 2020 |
| Pegatron | 2A73h                       | [1d140aa76c](https://linux-hardware.org/?probe=1d140aa76c) | Mar 07, 2020 |
| ASUSTek  | M5A99X EVO                  | [2859756e56](https://linux-hardware.org/?probe=2859756e56) | Feb 29, 2020 |
| Lenovo   | ThinkCentre XXXX 8705A84    | [b824441963](https://linux-hardware.org/?probe=b824441963) | Feb 23, 2020 |
| Lenovo   | ThinkServer TS140           | [33fc6022df](https://linux-hardware.org/?probe=33fc6022df) | Feb 06, 2020 |
| ASUSTek  | Leonite2                    | [d0d56d5609](https://linux-hardware.org/?probe=d0d56d5609) | Jan 23, 2020 |
| Lenovo   | ThinkCentre M55E 9632BU8    | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| Pegatron | 2A73h                       | [2371d130d0](https://linux-hardware.org/?probe=2371d130d0) | Nov 30, 2019 |
| IBM      | 8188LS4                     | [3d775f418d](https://linux-hardware.org/?probe=3d775f418d) | Oct 08, 2019 |
| Foxconn  | 8657MF-series               | [8ce7f69a15](https://linux-hardware.org/?probe=8ce7f69a15) | Oct 05, 2019 |
| IBM      | 8188LS4                     | [3fc14db446](https://linux-hardware.org/?probe=3fc14db446) | Oct 05, 2019 |
| IBM      | 8188LS4                     | [af840eb366](https://linux-hardware.org/?probe=af840eb366) | Oct 04, 2019 |
| Pegatron | 2AAE                        | [f80cb4a7f2](https://linux-hardware.org/?probe=f80cb4a7f2) | Aug 17, 2019 |
| Dell     | 0RK936                      | [060c60558b](https://linux-hardware.org/?probe=060c60558b) | Aug 08, 2019 |
| ASUSTek  | P8H61-M PRO                 | [e107cafe33](https://linux-hardware.org/?probe=e107cafe33) | Jun 07, 2019 |
| ASRock   | H67M-GE                     | [65dd091a6f](https://linux-hardware.org/?probe=65dd091a6f) | May 13, 2019 |
| Pegatron | 2AF0                        | [bebc187dbd](https://linux-hardware.org/?probe=bebc187dbd) | May 05, 2019 |
| Intel    | DG35EC AAE29266-205         | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Pegatron | IPPEL-DB                    | [c73b25ed21](https://linux-hardware.org/?probe=c73b25ed21) | Apr 24, 2019 |
| Pegatron | IPPEL-DB                    | [d1941d4619](https://linux-hardware.org/?probe=d1941d4619) | Apr 24, 2019 |
| Lenovo   | H220 10028                  | [9b6593e8c6](https://linux-hardware.org/?probe=9b6593e8c6) | Apr 21, 2019 |
| ASRock   | N68C-S UCC                  | [ac39e69311](https://linux-hardware.org/?probe=ac39e69311) | Apr 21, 2019 |
| ASRock   | H67M-GE                     | [282ee52768](https://linux-hardware.org/?probe=282ee52768) | Apr 19, 2019 |
| Intel    | DH77EB AAG39073-304         | [e054fab57c](https://linux-hardware.org/?probe=e054fab57c) | Nov 24, 2018 |
| Intel    | DH77EB AAG39073-304         | [d3d5ff2e54](https://linux-hardware.org/?probe=d3d5ff2e54) | Nov 24, 2018 |
| Intel    | D946GZIS AAD66165-302       | [8d884b92fa](https://linux-hardware.org/?probe=8d884b92fa) | Sep 16, 2017 |
| Intel    | D946GZIS AAD66165-302       | [17af4fce47](https://linux-hardware.org/?probe=17af4fce47) | Sep 03, 2017 |
| Intel    | D946GZIS AAD66165-302       | [c501aaa553](https://linux-hardware.org/?probe=c501aaa553) | Sep 01, 2017 |
| ASRock   | 945GCM-S                    | [009791bef2](https://linux-hardware.org/?probe=009791bef2) | Jun 25, 2017 |
| ASRock   | ALiveNF6P-VSTA              | [270499b92c](https://linux-hardware.org/?probe=270499b92c) | Dec 29, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 12       | 9.6%    |
| Ubuntu 18.04       | 10       | 8%      |
| Debian 11          | 10       | 8%      |
| OpenMandriva 4.3   | 9        | 7.2%    |
| OpenMandriva 4.2   | 6        | 4.8%    |
| ROSA R11           | 4        | 3.2%    |
| Zorin 16           | 3        | 2.4%    |
| Xubuntu 18.04      | 3        | 2.4%    |
| Linux Mint 20.3    | 3        | 2.4%    |
| Linux Mint 20      | 3        | 2.4%    |
| Linux Mint 19.3    | 3        | 2.4%    |
| KDE neon 20.04     | 3        | 2.4%    |
| Debian 10          | 3        | 2.4%    |
| Arch Rolling       | 3        | 2.4%    |
| Xubuntu 16.04      | 2        | 1.6%    |
| Ubuntu 22.04       | 2        | 1.6%    |
| Ubuntu 20.10       | 2        | 1.6%    |
| ROSA R9            | 2        | 1.6%    |
| OpenMandriva 4.50  | 2        | 1.6%    |
| Linux Mint 20.1    | 2        | 1.6%    |
| Kubuntu 20.04      | 2        | 1.6%    |
| Zorin 15           | 1        | 0.8%    |
| Xubuntu 20.04      | 1        | 0.8%    |
| Ubuntu Unity 18.04 | 1        | 0.8%    |
| Ubuntu MATE 19.10  | 1        | 0.8%    |
| Ubuntu 21.10       | 1        | 0.8%    |
| Ubuntu 19.10       | 1        | 0.8%    |
| Ubuntu 19.04       | 1        | 0.8%    |
| Sparky 5.12        | 1        | 0.8%    |
| Solus 4.3          | 1        | 0.8%    |
| ROSA R8            | 1        | 0.8%    |
| ROSA R11.1         | 1        | 0.8%    |
| ROSA 12.1          | 1        | 0.8%    |
| ROSA 12            | 1        | 0.8%    |
| Pop!_OS 20.04      | 1        | 0.8%    |
| PCLinuxOS 2022     | 1        | 0.8%    |
| Nobara 36          | 1        | 0.8%    |
| MX 21              | 1        | 0.8%    |
| Manjaro 20.2.1     | 1        | 0.8%    |
| Manjaro            | 1        | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 28       | 22.95%  |
| OpenMandriva | 17       | 13.93%  |
| Debian       | 15       | 12.3%   |
| Linux Mint   | 13       | 10.66%  |
| ROSA         | 10       | 8.2%    |
| Xubuntu      | 5        | 4.1%    |
| Zorin        | 4        | 3.28%   |
| KDE neon     | 4        | 3.28%   |
| Arch         | 4        | 3.28%   |
| Fedora       | 3        | 2.46%   |
| Manjaro      | 2        | 1.64%   |
| Kubuntu      | 2        | 1.64%   |
| Elementary   | 2        | 1.64%   |
| Ubuntu Unity | 1        | 0.82%   |
| Ubuntu MATE  | 1        | 0.82%   |
| Sparky       | 1        | 0.82%   |
| Solus        | 1        | 0.82%   |
| Pop!_OS      | 1        | 0.82%   |
| PCLinuxOS    | 1        | 0.82%   |
| Nobara       | 1        | 0.82%   |
| MX           | 1        | 0.82%   |
| LMDE         | 1        | 0.82%   |
| Kali         | 1        | 0.82%   |
| Garuda Linux | 1        | 0.82%   |
| Feren OS     | 1        | 0.82%   |
| Endless      | 1        | 0.82%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 9        | 6.82%   |
| 5.10.14-desktop-1omv4002       | 6        | 4.55%   |
| 5.4.0-42-generic               | 4        | 3.03%   |
| 5.8.0-55-generic               | 2        | 1.52%   |
| 5.4.0-77-generic               | 2        | 1.52%   |
| 5.4.0-74-generic               | 2        | 1.52%   |
| 5.4.0-54-generic               | 2        | 1.52%   |
| 5.4.0-26-generic               | 2        | 1.52%   |
| 5.3.0-40-generic               | 2        | 1.52%   |
| 5.15.0-46-generic              | 2        | 1.52%   |
| 5.13.0-27-generic              | 2        | 1.52%   |
| 5.10.0-8-amd64                 | 2        | 1.52%   |
| 5.10.0-16-amd64                | 2        | 1.52%   |
| 5.10.0-14-amd64                | 2        | 1.52%   |
| 5.10.0-11-amd64                | 2        | 1.52%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 1.52%   |
| 4.15.0-48-generic              | 2        | 1.52%   |
| 4.15.0-112-generic             | 2        | 1.52%   |
| 6.0.5-201.fsync.fc36.x86_64    | 1        | 0.76%   |
| 5.9.16-1-MANJARO               | 1        | 0.76%   |
| 5.8.11-arch1-1                 | 1        | 0.76%   |
| 5.8.10-17-tkg-bmq              | 1        | 0.76%   |
| 5.8.0-63-generic               | 1        | 0.76%   |
| 5.8.0-59-generic               | 1        | 0.76%   |
| 5.8.0-44-generic               | 1        | 0.76%   |
| 5.8.0-40-generic               | 1        | 0.76%   |
| 5.6.0-1-amd64                  | 1        | 0.76%   |
| 5.4.0-96-generic               | 1        | 0.76%   |
| 5.4.0-88-generic               | 1        | 0.76%   |
| 5.4.0-7634-generic             | 1        | 0.76%   |
| 5.4.0-72-generic               | 1        | 0.76%   |
| 5.4.0-66-generic               | 1        | 0.76%   |
| 5.4.0-47-generic               | 1        | 0.76%   |
| 5.4.0-42-lowlatency            | 1        | 0.76%   |
| 5.4.0-31-generic               | 1        | 0.76%   |
| 5.4.0-29-generic               | 1        | 0.76%   |
| 5.4.0-126-generic              | 1        | 0.76%   |
| 5.4.0-122-generic              | 1        | 0.76%   |
| 5.4.0-113-generic              | 1        | 0.76%   |
| 5.4.0-109-generic              | 1        | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 18.25%  |
| 4.15.0  | 18       | 14.29%  |
| 5.10.0  | 12       | 9.52%   |
| 5.16.7  | 9        | 7.14%   |
| 5.8.0   | 6        | 4.76%   |
| 5.13.0  | 6        | 4.76%   |
| 5.10.14 | 6        | 4.76%   |
| 5.3.0   | 5        | 3.97%   |
| 5.15.0  | 5        | 3.97%   |
| 5.11.0  | 3        | 2.38%   |
| 5.0.0   | 3        | 2.38%   |
| 4.19.0  | 3        | 2.38%   |
| 4.9.20  | 2        | 1.59%   |
| 4.9.0   | 2        | 1.59%   |
| 6.0.5   | 1        | 0.79%   |
| 5.9.16  | 1        | 0.79%   |
| 5.8.11  | 1        | 0.79%   |
| 5.8.10  | 1        | 0.79%   |
| 5.6.0   | 1        | 0.79%   |
| 5.19.9  | 1        | 0.79%   |
| 5.19.5  | 1        | 0.79%   |
| 5.18.7  | 1        | 0.79%   |
| 5.16.14 | 1        | 0.79%   |
| 5.15.6  | 1        | 0.79%   |
| 5.15.57 | 1        | 0.79%   |
| 5.15.48 | 1        | 0.79%   |
| 5.14.10 | 1        | 0.79%   |
| 5.13.16 | 1        | 0.79%   |
| 5.13.1  | 1        | 0.79%   |
| 5.12.4  | 1        | 0.79%   |
| 5.10.74 | 1        | 0.79%   |
| 5.10.71 | 1        | 0.79%   |
| 5.10.3  | 1        | 0.79%   |
| 4.4.0   | 1        | 0.79%   |
| 4.18.0  | 1        | 0.79%   |
| 4.13.0  | 1        | 0.79%   |
| 4.1.15  | 1        | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 23       | 18.4%   |
| 5.10    | 21       | 16.8%   |
| 4.15    | 18       | 14.4%   |
| 5.16    | 10       | 8%      |
| 5.8     | 8        | 6.4%    |
| 5.13    | 8        | 6.4%    |
| 5.15    | 7        | 5.6%    |
| 5.3     | 5        | 4%      |
| 4.9     | 4        | 3.2%    |
| 5.11    | 3        | 2.4%    |
| 5.0     | 3        | 2.4%    |
| 4.19    | 3        | 2.4%    |
| 5.19    | 2        | 1.6%    |
| 6.0     | 1        | 0.8%    |
| 5.9     | 1        | 0.8%    |
| 5.6     | 1        | 0.8%    |
| 5.18    | 1        | 0.8%    |
| 5.14    | 1        | 0.8%    |
| 5.12    | 1        | 0.8%    |
| 4.4     | 1        | 0.8%    |
| 4.18    | 1        | 0.8%    |
| 4.13    | 1        | 0.8%    |
| 4.1     | 1        | 0.8%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 106      | 87.6%   |
| i686   | 15       | 12.4%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 34       | 27.2%   |
| KDE5            | 32       | 25.6%   |
| Unknown         | 15       | 12%     |
| XFCE            | 12       | 9.6%    |
| X-Cinnamon      | 6        | 4.8%    |
| MATE            | 5        | 4%      |
| KDE             | 5        | 4%      |
| LXDE            | 4        | 3.2%    |
| KDE4            | 4        | 3.2%    |
| Cinnamon        | 2        | 1.6%    |
| xmonad          | 1        | 0.8%    |
| Unity           | 1        | 0.8%    |
| Pantheon        | 1        | 0.8%    |
| LXQt            | 1        | 0.8%    |
| GNOME Flashback | 1        | 0.8%    |
| Budgie          | 1        | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 103      | 85.83%  |
| Wayland | 12       | 10%     |
| Unknown | 4        | 3.33%   |
| Tty     | 1        | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 42.62%  |
| SDDM    | 31       | 25.41%  |
| LightDM | 12       | 9.84%   |
| GDM     | 12       | 9.84%   |
| TDM     | 6        | 4.92%   |
| KDM     | 4        | 3.28%   |
| GDM3    | 4        | 3.28%   |
| SLiM    | 1        | 0.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_VE   | 69       | 57.02%  |
| en_US   | 24       | 19.83%  |
| Unknown | 17       | 14.05%  |
| es_ES   | 6        | 4.96%   |
| es_US   | 2        | 1.65%   |
| C       | 2        | 1.65%   |
| de_DE   | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 107      | 89.92%  |
| EFI  | 12       | 10.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 91       | 75.21%  |
| Overlay | 17       | 14.05%  |
| Btrfs   | 6        | 4.96%   |
| Unknown | 5        | 4.13%   |
| Xfs     | 1        | 0.83%   |
| Ext2    | 1        | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 59       | 49.17%  |
| MBR     | 45       | 37.5%   |
| GPT     | 16       | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 78.33%  |
| Yes       | 26       | 21.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 56.67%  |
| Yes       | 52       | 43.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 23       | 19.33%  |
| ECS                 | 14       | 11.76%  |
| Intel               | 11       | 9.24%   |
| Pegatron            | 10       | 8.4%    |
| Lenovo              | 10       | 8.4%    |
| ASUSTek Computer    | 9        | 7.56%   |
| Hewlett-Packard     | 7        | 5.88%   |
| Biostar             | 7        | 5.88%   |
| Gigabyte Technology | 6        | 5.04%   |
| Dell                | 6        | 5.04%   |
| MSI                 | 4        | 3.36%   |
| langchao            | 4        | 3.36%   |
| Foxconn             | 4        | 3.36%   |
| IP3 Tech            | 1        | 0.84%   |
| Inspur              | 1        | 0.84%   |
| IBM                 | 1        | 0.84%   |
| Unknown             | 1        | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ECS H61H2-CM                         | 8        | 6.72%   |
| ASRock G41M-VS3                      | 6        | 5.04%   |
| langchao 12345                       | 4        | 3.36%   |
| ASRock N68-VS3 UCC                   | 3        | 2.52%   |
| Pegatron Compaq dx2400 Microtower    | 2        | 1.68%   |
| Intel H61                            | 2        | 1.68%   |
| ASRock N68C-S UCC                    | 2        | 1.68%   |
| Pegatron PEGATRON                    | 1        | 0.84%   |
| Pegatron IPPEL-DB                    | 1        | 0.84%   |
| Pegatron IPM41-D3                    | 1        | 0.84%   |
| Pegatron CQ1507LA                    | 1        | 0.84%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.84%   |
| Pegatron BM411AA-ABA CQ5600F         | 1        | 0.84%   |
| Pegatron 20-b010                     | 1        | 0.84%   |
| Pegatron 100-5010la                  | 1        | 0.84%   |
| MSI Pro 3000 Microtower PC           | 1        | 0.84%   |
| MSI MS-7817                          | 1        | 0.84%   |
| MSI MS-7721                          | 1        | 0.84%   |
| MSI MS-7375                          | 1        | 0.84%   |
| Lenovo ThinkCentre XXXX 8705A84      | 1        | 0.84%   |
| Lenovo ThinkCentre M91 7516AD1       | 1        | 0.84%   |
| Lenovo ThinkCentre M71e 3157G6S      | 1        | 0.84%   |
| Lenovo ThinkCentre M55E 9645BN2      | 1        | 0.84%   |
| Lenovo ThinkCentre M55E 9632BU8      | 1        | 0.84%   |
| Lenovo ThinkCentre A58 7515A33       | 1        | 0.84%   |
| Lenovo ThinkCentre A55 8705AV4       | 1        | 0.84%   |
| Lenovo H220 10028                    | 1        | 0.84%   |
| Lenovo 70A4000HUX ThinkServer TS140  | 1        | 0.84%   |
| Lenovo 11051CS ThinkServer TS130     | 1        | 0.84%   |
| IP3 Tech TB20                        | 1        | 0.84%   |
| Intel MAHOBAY                        | 1        | 0.84%   |
| Intel DH77EB AAG39073-304            | 1        | 0.84%   |
| Intel DG41TY AAE47335-203            | 1        | 0.84%   |
| Intel DG41TX AAE78178-303            | 1        | 0.84%   |
| Intel DG35EC AAE29266-205            | 1        | 0.84%   |
| Intel DG33BU AAD79951-407            | 1        | 0.84%   |
| Intel DG31PR AAD97573-302            | 1        | 0.84%   |
| Intel D946GZIS AAD66165-302          | 1        | 0.84%   |
| Intel D945GCCR AAD78647-300          | 1        | 0.84%   |
| Inspur                               | 1        | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ECS H61H2-CM          | 8        | 6.72%   |
| Lenovo ThinkCentre    | 7        | 5.88%   |
| HP Compaq             | 7        | 5.88%   |
| ASRock G41M-VS3       | 6        | 5.04%   |
| langchao 12345        | 4        | 3.36%   |
| Pegatron Compaq       | 3        | 2.52%   |
| Dell OptiPlex         | 3        | 2.52%   |
| ASRock N68-VS3        | 3        | 2.52%   |
| Intel H61             | 2        | 1.68%   |
| Dell Vostro           | 2        | 1.68%   |
| ASUS P5G41T-M         | 2        | 1.68%   |
| ASRock N68C-S         | 2        | 1.68%   |
| Pegatron PEGATRON     | 1        | 0.84%   |
| Pegatron IPPEL-DB     | 1        | 0.84%   |
| Pegatron IPM41-D3     | 1        | 0.84%   |
| Pegatron CQ1507LA     | 1        | 0.84%   |
| Pegatron BM411AA-ABA  | 1        | 0.84%   |
| Pegatron 20-b010      | 1        | 0.84%   |
| Pegatron 100-5010la   | 1        | 0.84%   |
| MSI Pro               | 1        | 0.84%   |
| MSI MS-7817           | 1        | 0.84%   |
| MSI MS-7721           | 1        | 0.84%   |
| MSI MS-7375           | 1        | 0.84%   |
| Lenovo H220           | 1        | 0.84%   |
| Lenovo 70A4000HUX     | 1        | 0.84%   |
| Lenovo 11051CS        | 1        | 0.84%   |
| IP3 Tech TB20         | 1        | 0.84%   |
| Intel MAHOBAY         | 1        | 0.84%   |
| Intel DH77EB          | 1        | 0.84%   |
| Intel DG41TY          | 1        | 0.84%   |
| Intel DG41TX          | 1        | 0.84%   |
| Intel DG35EC          | 1        | 0.84%   |
| Intel DG33BU          | 1        | 0.84%   |
| Intel DG31PR          | 1        | 0.84%   |
| Intel D946GZIS        | 1        | 0.84%   |
| Intel D945GCCR        | 1        | 0.84%   |
| Inspur                | 1        | 0.84%   |
| IBM 8188LS4           | 1        | 0.84%   |
| Gigabyte Z97N-WIFI    | 1        | 0.84%   |
| Gigabyte Z68X-UD3H-B3 | 1        | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 29       | 24.37%  |
| 2010 | 28       | 23.53%  |
| 2012 | 14       | 11.76%  |
| 2008 | 13       | 10.92%  |
| 2007 | 10       | 8.4%    |
| 2006 | 7        | 5.88%   |
| 2014 | 4        | 3.36%   |
| 2017 | 3        | 2.52%   |
| 2013 | 3        | 2.52%   |
| 2009 | 2        | 1.68%   |
| 2021 | 1        | 0.84%   |
| 2020 | 1        | 0.84%   |
| 2019 | 1        | 0.84%   |
| 2016 | 1        | 0.84%   |
| 2015 | 1        | 0.84%   |
| 2005 | 1        | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 119      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 119      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 119      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 37       | 30.33%  |
| 4.01-8.0   | 27       | 22.13%  |
| 1.01-2.0   | 19       | 15.57%  |
| 8.01-16.0  | 18       | 14.75%  |
| 16.01-24.0 | 10       | 8.2%    |
| 2.01-3.0   | 4        | 3.28%   |
| 24.01-32.0 | 3        | 2.46%   |
| 32.01-64.0 | 2        | 1.64%   |
| 0.51-1.0   | 2        | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 51       | 39.53%  |
| 2.01-3.0 | 32       | 24.81%  |
| 0.51-1.0 | 20       | 15.5%   |
| 4.01-8.0 | 13       | 10.08%  |
| 3.01-4.0 | 9        | 6.98%   |
| 0.01-0.5 | 4        | 3.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 71       | 57.72%  |
| 2      | 38       | 30.89%  |
| 3      | 12       | 9.76%   |
| 4      | 2        | 1.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 52.85%  |
| Yes       | 58       | 47.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 117      | 98.32%  |
| No        | 2        | 1.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 50.83%  |
| Yes       | 59       | 49.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 90%     |
| Yes       | 12       | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Venezuela | 119      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Caracas                  | 60       | 47.24%  |
| Maracay                  | 8        | 6.3%    |
| Valencia                 | 6        | 4.72%   |
| San Cristóbal           | 5        | 3.94%   |
| Maracaibo                | 4        | 3.15%   |
| Barquisimeto             | 4        | 3.15%   |
| San Carlos del Zulia     | 3        | 2.36%   |
| Maturín                 | 3        | 2.36%   |
| Carrizal                 | 3        | 2.36%   |
| Barcelona                | 3        | 2.36%   |
| San Antonio de Los Altos | 2        | 1.57%   |
| Mérida                  | 2        | 1.57%   |
| Los Teques               | 2        | 1.57%   |
| Ciudad Bolívar          | 2        | 1.57%   |
| Barinas                  | 2        | 1.57%   |
| Acarigua                 | 2        | 1.57%   |
| Valle de La Pascua       | 1        | 0.79%   |
| Tucupita                 | 1        | 0.79%   |
| San Juan Bautista        | 1        | 0.79%   |
| San Francisco            | 1        | 0.79%   |
| Porlamar                 | 1        | 0.79%   |
| Parroquia El Recreo      | 1        | 0.79%   |
| Los Palos Grandes        | 1        | 0.79%   |
| Lecherias                | 1        | 0.79%   |
| Las Vegas                | 1        | 0.79%   |
| Guatire                  | 1        | 0.79%   |
| Guarenas                 | 1        | 0.79%   |
| Cua                      | 1        | 0.79%   |
| Ciudad Guayana           | 1        | 0.79%   |
| Carora                   | 1        | 0.79%   |
| Cabimas                  | 1        | 0.79%   |
| Baruta                   | 1        | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 54       | 74     | 33.13%  |
| Seagate             | 37       | 54     | 22.7%   |
| Hitachi             | 26       | 30     | 15.95%  |
| Samsung Electronics | 13       | 16     | 7.98%   |
| Toshiba             | 10       | 11     | 6.13%   |
| Kingston            | 7        | 7      | 4.29%   |
| Maxtor              | 4        | 4      | 2.45%   |
| PNY                 | 3        | 4      | 1.84%   |
| Patriot             | 2        | 2      | 1.23%   |
| Unknown             | 1        | 1      | 0.61%   |
| Team                | 1        | 1      | 0.61%   |
| SPCC                | 1        | 1      | 0.61%   |
| HGST                | 1        | 1      | 0.61%   |
| Fujitsu             | 1        | 1      | 0.61%   |
| ExcelStor           | 1        | 1      | 0.61%   |
| Dogfish             | 1        | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 9        | 4.84%   |
| Toshiba DT01ACA050 500GB            | 6        | 3.23%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 4        | 2.15%   |
| Seagate ST500DM002-1BD142 500GB     | 4        | 2.15%   |
| Seagate ST3320418AS 320GB           | 4        | 2.15%   |
| WDC WD5000AAKX-221CA1 500GB         | 3        | 1.61%   |
| WDC WD5000AAKX-001CA0 500GB         | 3        | 1.61%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3        | 1.61%   |
| WDC WD3200AAJS-08L7A0 320GB         | 3        | 1.61%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3        | 1.61%   |
| Seagate ST320LM000 HM321HI 320GB    | 3        | 1.61%   |
| Samsung HD502HJ 500GB               | 3        | 1.61%   |
| Samsung HD161HJ 160GB               | 3        | 1.61%   |
| Kingston SA400S37240G 240GB SSD     | 3        | 1.61%   |
| Hitachi HTS542580K9SA00 80GB        | 3        | 1.61%   |
| Hitachi HDS728080PLA380 82GB        | 3        | 1.61%   |
| WDC WD800BD-22MRA1 80GB             | 2        | 1.08%   |
| WDC WD800BB-22JHC0 80GB             | 2        | 1.08%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2        | 1.08%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 2        | 1.08%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2        | 1.08%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2        | 1.08%   |
| Seagate ST3250310AS 250GB           | 2        | 1.08%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 2        | 1.08%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 1.08%   |
| Hitachi HTS545032B9A300 320GB       | 2        | 1.08%   |
| Hitachi HDS721616PLA380 160GB       | 2        | 1.08%   |
| Hitachi HDS721032CLA362 320GB       | 2        | 1.08%   |
| WDC WD800JD-60LSA5 80GB             | 1        | 0.54%   |
| WDC WD800BD-08MRA1 80GB             | 1        | 0.54%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 0.54%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.54%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1        | 0.54%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 0.54%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1        | 0.54%   |
| WDC WD5000AAJS-08A8B0 500GB         | 1        | 0.54%   |
| WDC WD5000AACS-61M6B2 500GB         | 1        | 0.54%   |
| WDC WD5000AACS-22ZUB0 500GB         | 1        | 0.54%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1        | 0.54%   |
| WDC WD3200BEKT-22F3T0 320GB         | 1        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 54       | 74     | 36.73%  |
| Seagate             | 37       | 54     | 25.17%  |
| Hitachi             | 26       | 30     | 17.69%  |
| Samsung Electronics | 13       | 16     | 8.84%   |
| Toshiba             | 10       | 11     | 6.8%    |
| Maxtor              | 4        | 4      | 2.72%   |
| HGST                | 1        | 1      | 0.68%   |
| Fujitsu             | 1        | 1      | 0.68%   |
| ExcelStor           | 1        | 1      | 0.68%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Kingston | 7        | 7      | 46.67%  |
| PNY      | 3        | 4      | 20%     |
| Patriot  | 2        | 2      | 13.33%  |
| Team     | 1        | 1      | 6.67%   |
| SPCC     | 1        | 1      | 6.67%   |
| Dogfish  | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 107      | 192    | 87.7%   |
| SSD  | 14       | 16     | 11.48%  |
| NVMe | 1        | 1      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 118      | 208    | 99.16%  |
| NVMe | 1        | 1      | 0.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 112      | 182    | 81.75%  |
| 0.51-1.0   | 14       | 14     | 10.22%  |
| 1.01-2.0   | 7        | 7      | 5.11%   |
| 3.01-4.0   | 2        | 2      | 1.46%   |
| 2.01-3.0   | 2        | 3      | 1.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 43       | 33.86%  |
| 101-250        | 29       | 22.83%  |
| 1-20           | 15       | 11.81%  |
| 501-1000       | 15       | 11.81%  |
| 51-100         | 12       | 9.45%   |
| 1001-2000      | 4        | 3.15%   |
| 21-50          | 3        | 2.36%   |
| 2001-3000      | 3        | 2.36%   |
| Unknown        | 2        | 1.57%   |
| More than 3000 | 1        | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 57       | 45.24%  |
| 21-50          | 18       | 14.29%  |
| 101-250        | 18       | 14.29%  |
| 251-500        | 13       | 10.32%  |
| 51-100         | 10       | 7.94%   |
| 501-1000       | 4        | 3.17%   |
| 2001-3000      | 2        | 1.59%   |
| Unknown        | 2        | 1.59%   |
| More than 3000 | 1        | 0.79%   |
| 1001-2000      | 1        | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB         | 5        | 6      | 9.26%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 2        | 3      | 3.7%    |
| WDC WD5000AAKX-221CA1 500GB             | 2        | 2      | 3.7%    |
| WDC WD5000AAKS-00A7B0 500GB             | 2        | 2      | 3.7%    |
| Toshiba DT01ACA050 500GB                | 2        | 3      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB         | 2        | 2      | 3.7%    |
| Hitachi HDS728080PLA380 82GB            | 2        | 2      | 3.7%    |
| Hitachi HDS721616PLA380 160GB           | 2        | 2      | 3.7%    |
| WDC WD800BD-08MRA1 80GB                 | 1        | 1      | 1.85%   |
| WDC WD800BB-22JHC0 80GB                 | 1        | 1      | 1.85%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1        | 1      | 1.85%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 1        | 1      | 1.85%   |
| WDC WD5000AAKX-08ERMA0 500GB            | 1        | 1      | 1.85%   |
| WDC WD5000AACS-00ZUB0 500GB             | 1        | 1      | 1.85%   |
| WDC WD3200BEKT-22F3T0 320GB             | 1        | 1      | 1.85%   |
| WDC WD3200AAJS-08L7A0 320GB             | 1        | 2      | 1.85%   |
| WDC WD2003FYPS-27Y2B0 2TB               | 1        | 1      | 1.85%   |
| WDC WD10EZEX-22RKKA0 1TB                | 1        | 1      | 1.85%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1        | 1      | 1.85%   |
| Seagate ST3500630AS 500GB               | 1        | 1      | 1.85%   |
| Seagate ST3500418AS 500GB               | 1        | 1      | 1.85%   |
| Seagate ST3500413AS 500GB               | 1        | 1      | 1.85%   |
| Seagate ST3500312CS 500GB               | 1        | 1      | 1.85%   |
| Seagate ST340014AS 40GB                 | 1        | 1      | 1.85%   |
| Seagate ST3320418AS 320GB               | 1        | 2      | 1.85%   |
| Seagate ST3250318AS 250GB               | 1        | 1      | 1.85%   |
| Seagate ST3250310AS 250GB               | 1        | 1      | 1.85%   |
| Seagate ST3160215ACE 160GB              | 1        | 1      | 1.85%   |
| Seagate ST3160212SCE 160GB              | 1        | 1      | 1.85%   |
| Seagate ST31000525SV 1TB                | 1        | 1      | 1.85%   |
| Samsung Electronics HM321HI 320GB       | 1        | 1      | 1.85%   |
| Samsung Electronics HD161HJ 160GB       | 1        | 2      | 1.85%   |
| Samsung Electronics HD161GJ 160GB       | 1        | 1      | 1.85%   |
| Samsung Electronics HD155UI 1TB         | 1        | 1      | 1.85%   |
| Maxtor STM3250310AS 250GB               | 1        | 1      | 1.85%   |
| Maxtor STM3160215AS 160GB               | 1        | 1      | 1.85%   |
| Hitachi HUA722020ALA331 2TB             | 1        | 1      | 1.85%   |
| Hitachi HDT721016SLA380 160GB           | 1        | 1      | 1.85%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB | 1        | 1      | 1.85%   |
| Hitachi HDS721050DLE630 500GB           | 1        | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 35.42%  |
| WDC                 | 12       | 19     | 25%     |
| Hitachi             | 10       | 10     | 20.83%  |
| Samsung Electronics | 4        | 5      | 8.33%   |
| Toshiba             | 2        | 3      | 4.17%   |
| Maxtor              | 2        | 2      | 4.17%   |
| ExcelStor           | 1        | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 35.42%  |
| WDC                 | 12       | 19     | 25%     |
| Hitachi             | 10       | 10     | 20.83%  |
| Samsung Electronics | 4        | 5      | 8.33%   |
| Toshiba             | 2        | 3      | 4.17%   |
| Maxtor              | 2        | 2      | 4.17%   |
| ExcelStor           | 1        | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 60     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Toshiba DT01ACA050 500GB | 2        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 61       | 104    | 45.86%  |
| Malfunc  | 38       | 60     | 28.57%  |
| Works    | 32       | 43     | 24.06%  |
| Failed   | 2        | 2      | 1.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 91       | 68.94%  |
| Nvidia                   | 13       | 9.85%   |
| AMD                      | 12       | 9.09%   |
| Marvell Technology Group | 5        | 3.79%   |
| JMicron Technology       | 5        | 3.79%   |
| VIA Technologies         | 3        | 2.27%   |
| ASMedia Technology       | 1        | 0.76%   |
| Adaptec                  | 1        | 0.76%   |
| Unknown                  | 1        | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 32       | 15.46%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24       | 11.59%  |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13       | 6.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13       | 6.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 6.28%   |
| Nvidia MCP61 SATA Controller                                                            | 12       | 5.8%    |
| Nvidia MCP61 IDE                                                                        | 10       | 4.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 2.42%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 2.42%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 2.42%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 2.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 1.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.93%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 1.93%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 1.45%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 1.45%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.45%   |
| VIA Serial ATA Controller                                                               | 2        | 0.97%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.97%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.97%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.97%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.97%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.97%   |
| AMD FCH IDE Controller                                                                  | 2        | 0.97%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.48%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 0.48%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.48%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.48%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.48%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.48%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.48%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.48%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.48%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1        | 0.48%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.48%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 84       | 63.64%  |
| SATA | 43       | 32.58%  |
| RAID | 2        | 1.52%   |
| SAS  | 1        | 0.76%   |
| SCSI | 1        | 0.76%   |
| NVMe | 1        | 0.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 94       | 78.99%  |
| AMD    | 25       | 21.01%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 6        | 5.04%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6        | 5.04%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4        | 3.36%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 3        | 2.52%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 3        | 2.52%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 2.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 2.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 2.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.52%   |
| AMD Sempron 145 Processor                   | 3        | 2.52%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 2        | 1.68%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2        | 1.68%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 1.68%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 2        | 1.68%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.68%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 1.68%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 1.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.68%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 1.68%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.68%   |
| AMD FX-6100 Six-Core Processor              | 2        | 1.68%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.84%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.84%   |
| Intel Xeon CPU E5-1607 0 @ 3.00GHz          | 1        | 0.84%   |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1        | 0.84%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.84%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.84%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.84%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.84%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.84%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.84%   |
| Intel Pentium CPU E5800 @ 3.20GHz           | 1        | 0.84%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 0.84%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.84%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 0.84%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 0.84%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.84%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium Dual-Core | 21       | 17.65%  |
| Intel Core i5           | 14       | 11.76%  |
| Intel Pentium           | 10       | 8.4%    |
| Intel Core i3           | 8        | 6.72%   |
| Intel Core i7           | 7        | 5.88%   |
| Intel Core 2 Duo        | 7        | 5.88%   |
| AMD Sempron             | 6        | 5.04%   |
| Intel Pentium Dual      | 5        | 4.2%    |
| Intel Core 2 Quad       | 5        | 4.2%    |
| Intel Xeon              | 4        | 3.36%   |
| Intel Pentium 4         | 4        | 3.36%   |
| Intel Core 2            | 4        | 3.36%   |
| AMD FX                  | 3        | 2.52%   |
| Intel Celeron           | 2        | 1.68%   |
| AMD Phenom II X4        | 2        | 1.68%   |
| AMD Phenom              | 2        | 1.68%   |
| AMD Athlon II X2        | 2        | 1.68%   |
| AMD Athlon              | 2        | 1.68%   |
| Other                   | 1        | 0.84%   |
| Intel Pentium D         | 1        | 0.84%   |
| Intel Atom              | 1        | 0.84%   |
| AMD Phenom II X2        | 1        | 0.84%   |
| AMD E1                  | 1        | 0.84%   |
| AMD Athlon II X4        | 1        | 0.84%   |
| AMD Athlon II           | 1        | 0.84%   |
| AMD Athlon 64 X2        | 1        | 0.84%   |
| AMD A8                  | 1        | 0.84%   |
| AMD A6                  | 1        | 0.84%   |
| AMD A4                  | 1        | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 64       | 53.78%  |
| 4       | 37       | 31.09%  |
| 1       | 12       | 10.08%  |
| 3       | 4        | 3.36%   |
| Unknown | 2        | 1.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 119      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 92       | 77.31%  |
| 2       | 25       | 21.01%  |
| Unknown | 2        | 1.68%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 115      | 96.64%  |
| 64-bit         | 2        | 1.68%   |
| 32-bit         | 1        | 0.84%   |
| Unknown        | 1        | 0.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 27       | 22.69%  |
| Unknown    | 17       | 14.29%  |
| 0x206a7    | 15       | 12.61%  |
| 0x306a9    | 8        | 6.72%   |
| 0x306c3    | 5        | 4.2%    |
| 0x6fd      | 4        | 3.36%   |
| 0x6fb      | 4        | 3.36%   |
| 0x010000c8 | 4        | 3.36%   |
| 0xf65      | 3        | 2.52%   |
| 0x6f2      | 3        | 2.52%   |
| 0x106a5    | 2        | 1.68%   |
| 0x10676    | 2        | 1.68%   |
| 0x0600063e | 2        | 1.68%   |
| 0x010000c7 | 2        | 1.68%   |
| 0x010000b6 | 2        | 1.68%   |
| 0xf47      | 1        | 0.84%   |
| 0xf41      | 1        | 0.84%   |
| 0x906eb    | 1        | 0.84%   |
| 0x906e9    | 1        | 0.84%   |
| 0x806c1    | 1        | 0.84%   |
| 0x6f6      | 1        | 0.84%   |
| 0x206d7    | 1        | 0.84%   |
| 0x106ca    | 1        | 0.84%   |
| 0x10661    | 1        | 0.84%   |
| 0x0810100b | 1        | 0.84%   |
| 0x0700010b | 1        | 0.84%   |
| 0x06001119 | 1        | 0.84%   |
| 0x06000852 | 1        | 0.84%   |
| 0x05000119 | 1        | 0.84%   |
| 0x03000027 | 1        | 0.84%   |
| 0x03000014 | 1        | 0.84%   |
| 0x010000db | 1        | 0.84%   |
| 0x01000095 | 1        | 0.84%   |
| 0x01000065 | 1        | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 31       | 26.05%  |
| SandyBridge | 20       | 16.81%  |
| Core        | 15       | 12.61%  |
| K10         | 13       | 10.92%  |
| IvyBridge   | 11       | 9.24%   |
| Haswell     | 6        | 5.04%   |
| NetBurst    | 5        | 4.2%    |
| K8 Hammer   | 3        | 2.52%   |
| Piledriver  | 2        | 1.68%   |
| Nehalem     | 2        | 1.68%   |
| KabyLake    | 2        | 1.68%   |
| K10 Llano   | 2        | 1.68%   |
| Bulldozer   | 2        | 1.68%   |
| Zen         | 1        | 0.84%   |
| TigerLake   | 1        | 0.84%   |
| Jaguar      | 1        | 0.84%   |
| Bonnell     | 1        | 0.84%   |
| Bobcat      | 1        | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 69       | 54.76%  |
| Nvidia           | 32       | 25.4%   |
| AMD              | 22       | 17.46%  |
| VIA Technologies | 3        | 2.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 16       | 12.7%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16       | 12.7%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 3.97%   |
| Nvidia GF119 [GeForce GT 520]                                               | 4        | 3.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 3.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 3.17%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 4        | 3.17%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 3        | 2.38%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 2.38%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 2.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.59%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.59%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 2        | 1.59%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 1.59%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.59%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 1.59%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.59%   |
| Intel 82865G Integrated Graphics Controller                                 | 2        | 1.59%   |
| AMD RV670 [Radeon HD 3870]                                                  | 2        | 1.59%   |
| Nvidia NV44 [GeForce 7100 GS]                                               | 1        | 0.79%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.79%   |
| Nvidia GT218 [GeForce 405]                                                  | 1        | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.79%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.79%   |
| Nvidia GK104GL [Quadro K4200]                                               | 1        | 0.79%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.79%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.79%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.79%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.79%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 0.79%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 0.79%   |
| Intel Xeon E3-1200 Processor Family Integrated Graphics Controller          | 1        | 0.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1        | 0.79%   |
| Intel HD Graphics 630                                                       | 1        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 0.79%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 0.79%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Intel    | 64       | 53.33%  |
| 1 x Nvidia   | 31       | 25.83%  |
| 1 x AMD      | 20       | 16.67%  |
| 1 x VIA      | 3        | 2.5%    |
| Intel + AMD  | 1        | 0.83%   |
| AMD + Nvidia | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 98       | 82.35%  |
| Proprietary | 12       | 10.08%  |
| Unknown     | 9        | 7.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 51.64%  |
| 0.51-1.0   | 22       | 18.03%  |
| 0.01-0.5   | 20       | 16.39%  |
| 1.01-2.0   | 13       | 10.66%  |
| 3.01-4.0   | 4        | 3.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung Electronics                   | 32       | 29.63%  |
| Hewlett-Packard                       | 12       | 11.11%  |
| Goldstar                              | 12       | 11.11%  |
| Toshiba                               | 8        | 7.41%   |
| Lenovo                                | 8        | 7.41%   |
| Dell                                  | 7        | 6.48%   |
| AOC                                   | 6        | 5.56%   |
| BenQ                                  | 3        | 2.78%   |
| Acer                                  | 3        | 2.78%   |
| Sony                                  | 2        | 1.85%   |
| Envision                              | 2        | 1.85%   |
| Vita                                  | 1        | 0.93%   |
| ViewSonic                             | 1        | 0.93%   |
| Unknown (XXX)                         | 1        | 0.93%   |
| Toshiba Matsushita Display Technology | 1        | 0.93%   |
| TCL                                   | 1        | 0.93%   |
| Plain Tree Systems                    | 1        | 0.93%   |
| PEGA                                  | 1        | 0.93%   |
| Parker                                | 1        | 0.93%   |
| MStar                                 | 1        | 0.93%   |
| LSC                                   | 1        | 0.93%   |
| LG Electronics                        | 1        | 0.93%   |
| IBM                                   | 1        | 0.93%   |
| CVT                                   | 1        | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 5        | 4.46%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch  | 4        | 3.57%   |
| Lenovo LEN L171 LEN240B 1280x1024 337x270mm 17.0-inch                 | 4        | 3.57%   |
| Toshiba TV TSB0206 1920x1080                                          | 3        | 2.68%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch  | 2        | 1.79%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 2        | 1.79%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch      | 2        | 1.79%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 2        | 1.79%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                    | 1        | 0.89%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch         | 1        | 0.89%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch            | 1        | 0.89%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch             | 1        | 0.89%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR         | 1        | 0.89%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                     | 1        | 0.89%   |
| Sony TV SNYEB01 1360x768                                              | 1        | 0.89%   |
| Sony TV SNYEA01 1920x1080                                             | 1        | 0.89%   |
| Sony TV SNYDC01 1360x768                                              | 1        | 0.89%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch  | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch   | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM03F5 1920x1200                      | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM03F4 1920x1200 518x324mm 24.1-inch  | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch   | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1        | 0.89%   |
| Samsung Electronics SMBX2050N SAM0719 1600x900 443x249mm 20.0-inch    | 1        | 0.89%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1        | 0.89%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 0.89%   |
| Samsung Electronics SA300/SA350 SAM0849 1920x1080 477x268mm 21.5-inch | 1        | 0.89%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1        | 0.89%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch     | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SAM02C8 1280x720                      | 1        | 0.89%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1        | 0.89%   |
| Samsung Electronics LCD Monitor C24F390                               | 1        | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1280x1024 (SXGA)   | 25       | 23.15%  |
| 1920x1080 (FHD)    | 23       | 21.3%   |
| 1366x768 (WXGA)    | 20       | 18.52%  |
| 1440x900 (WXGA+)   | 12       | 11.11%  |
| 1600x900 (HD+)     | 8        | 7.41%   |
| 1680x1050 (WSXGA+) | 4        | 3.7%    |
| 1360x768           | 4        | 3.7%    |
| 1280x720 (HD)      | 3        | 2.78%   |
| 1024x768 (XGA)     | 3        | 2.78%   |
| 1920x1200 (WUXGA)  | 2        | 1.85%   |
| Unknown            | 2        | 1.85%   |
| 3840x2160 (4K)     | 1        | 0.93%   |
| 3840x1080          | 1        | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 25       | 23.15%  |
| 17      | 19       | 17.59%  |
| 21      | 13       | 12.04%  |
| 19      | 10       | 9.26%   |
| Unknown | 8        | 7.41%   |
| 20      | 7        | 6.48%   |
| 15      | 7        | 6.48%   |
| 23      | 5        | 4.63%   |
| 74      | 3        | 2.78%   |
| 16      | 3        | 2.78%   |
| 72      | 2        | 1.85%   |
| 22      | 2        | 1.85%   |
| 52      | 1        | 0.93%   |
| 39      | 1        | 0.93%   |
| 24      | 1        | 0.93%   |
| 13      | 1        | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 52       | 48.6%   |
| 301-350     | 26       | 24.3%   |
| Unknown     | 8        | 7.48%   |
| 351-400     | 7        | 6.54%   |
| 501-600     | 6        | 5.61%   |
| 1501-2000   | 5        | 4.67%   |
| 801-900     | 1        | 0.93%   |
| 201-300     | 1        | 0.93%   |
| 1001-1500   | 1        | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 50       | 47.62%  |
| 5/4     | 23       | 21.9%   |
| 16/10   | 21       | 20%     |
| Unknown | 6        | 5.71%   |
| 4/3     | 4        | 3.81%   |
| 3/2     | 1        | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 37       | 34.26%  |
| 151-200        | 27       | 25%     |
| 201-250        | 16       | 14.81%  |
| Unknown        | 8        | 7.41%   |
| 101-110        | 7        | 6.48%   |
| More than 1000 | 6        | 5.56%   |
| 121-130        | 3        | 2.78%   |
| 251-300        | 1        | 0.93%   |
| 131-140        | 1        | 0.93%   |
| 501-1000       | 1        | 0.93%   |
| 91-100         | 1        | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 76       | 71.03%  |
| 101-120 | 16       | 14.95%  |
| Unknown | 8        | 7.48%   |
| 1-50    | 6        | 5.61%   |
| 121-160 | 1        | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 102      | 85.71%  |
| 2     | 8        | 6.72%   |
| 0     | 8        | 6.72%   |
| 3     | 1        | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 68       | 36.17%  |
| Qualcomm Atheros                  | 28       | 14.89%  |
| Intel                             | 27       | 14.36%  |
| Nvidia                            | 13       | 6.91%   |
| Ralink                            | 12       | 6.38%   |
| Broadcom                          | 9        | 4.79%   |
| Ralink Technology                 | 6        | 3.19%   |
| Xiaomi                            | 4        | 2.13%   |
| Qualcomm Atheros Communications   | 4        | 2.13%   |
| VIA Technologies                  | 3        | 1.6%    |
| Sundance Technology Inc / IC Plus | 2        | 1.06%   |
| Mercucys                          | 2        | 1.06%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.53%   |
| Trendchip Technologies            | 1        | 0.53%   |
| Samsung Electronics               | 1        | 0.53%   |
| National Semiconductor            | 1        | 0.53%   |
| Motorola PCS                      | 1        | 0.53%   |
| Motorola BCS                      | 1        | 0.53%   |
| Marvell Technology Group          | 1        | 0.53%   |
| ICS Advent                        | 1        | 0.53%   |
| D-Link System                     | 1        | 0.53%   |
| Broadcom Limited                  | 1        | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 43       | 21.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 13       | 6.53%   |
| Nvidia MCP61 Ethernet                                                          | 12       | 6.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8        | 4.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 7        | 3.52%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 6        | 3.02%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5        | 2.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 2.01%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4        | 2.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3        | 1.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3        | 1.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3        | 1.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 1.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3        | 1.51%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3        | 1.51%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3        | 1.51%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 1.51%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 1.51%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3        | 1.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 1.01%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 1.01%   |
| Ralink MT7601U Wireless Adapter                                                | 2        | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 1.01%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 1.01%   |
| Intel PRO/100 VE Network Connection                                            | 2        | 1.01%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.01%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 1.01%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 2        | 1.01%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 1.01%   |
| ZTE WCDMA MSM ZXIC Mobile Boardband                                            | 1        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1        | 0.5%    |
| Trendchip Ethernet controller                                                  | 1        | 0.5%    |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                          | 1        | 0.5%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 1        | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 18       | 28.57%  |
| Realtek Semiconductor           | 13       | 20.63%  |
| Ralink                          | 12       | 19.05%  |
| Ralink Technology               | 6        | 9.52%   |
| Qualcomm Atheros Communications | 4        | 6.35%   |
| Intel                           | 4        | 6.35%   |
| Broadcom                        | 3        | 4.76%   |
| Mercucys                        | 2        | 3.17%   |
| D-Link System                   | 1        | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 6        | 9.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5        | 7.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 6.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 3        | 4.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3        | 4.76%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3        | 4.76%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3        | 4.76%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 4.76%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 4.76%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3        | 4.76%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 3.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 3.17%   |
| Ralink MT7601U Wireless Adapter                                                | 2        | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 3.17%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 3.17%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 3.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 1.59%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 1.59%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 1.59%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.59%   |
| Qualcomm Atheros AR5523                                                        | 1        | 1.59%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 1        | 1.59%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 1.59%   |
| Intel Wireless 7265                                                            | 1        | 1.59%   |
| Intel Wireless 7260                                                            | 1        | 1.59%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 1.59%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 1.59%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]           | 1        | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 1        | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 60       | 44.78%  |
| Intel                             | 24       | 17.91%  |
| Qualcomm Atheros                  | 14       | 10.45%  |
| Nvidia                            | 13       | 9.7%    |
| Broadcom                          | 6        | 4.48%   |
| Xiaomi                            | 4        | 2.99%   |
| VIA Technologies                  | 3        | 2.24%   |
| Sundance Technology Inc / IC Plus | 2        | 1.49%   |
| Trendchip Technologies            | 1        | 0.75%   |
| Samsung Electronics               | 1        | 0.75%   |
| National Semiconductor            | 1        | 0.75%   |
| Motorola PCS                      | 1        | 0.75%   |
| Motorola BCS                      | 1        | 0.75%   |
| Marvell Technology Group          | 1        | 0.75%   |
| ICS Advent                        | 1        | 0.75%   |
| Broadcom Limited                  | 1        | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 43       | 31.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 13       | 9.63%   |
| Nvidia MCP61 Ethernet                                                      | 12       | 8.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 8        | 5.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 7        | 5.19%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4        | 2.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 2.22%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3        | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.48%   |
| Intel PRO/100 VE Network Connection                                        | 2        | 1.48%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.48%   |
| Intel Ethernet Connection I217-LM                                          | 2        | 1.48%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 2        | 1.48%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.74%   |
| Trendchip Ethernet controller                                              | 1        | 0.74%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.74%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.74%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.74%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.74%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1        | 0.74%   |
| Motorola PCS moto g(6) plus                                                | 1        | 0.74%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1        | 0.74%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.74%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 0.74%   |
| Intel 82567V-4 Gigabit Network Connection                                  | 1        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 1        | 0.74%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 1        | 0.74%   |
| Intel 82566DC Gigabit Network Connection                                   | 1        | 0.74%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1        | 0.74%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1        | 0.74%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 1        | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 117      | 66.1%   |
| WiFi     | 59       | 33.33%  |
| Modem    | 1        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 84       | 68.85%  |
| WiFi     | 38       | 31.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 63.33%  |
| 2     | 40       | 33.33%  |
| 3     | 3        | 2.5%    |
| 0     | 1        | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 119      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 4        | 33.33%  |
| Intel                   | 2        | 16.67%  |
| IMC Networks            | 2        | 16.67%  |
| Broadcom                | 2        | 16.67%  |
| ASUSTek Computer        | 2        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 33.33%  |
| IMC Networks Bluetooth Module                       | 2        | 16.67%  |
| Intel Bluetooth wireless interface                  | 1        | 8.33%   |
| Intel AX200 Bluetooth                               | 1        | 8.33%   |
| Broadcom BCM2070 Bluetooth Device                   | 1        | 8.33%   |
| Broadcom BCM2035B3 Bluetooth Adapter                | 1        | 8.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 8.33%   |
| ASUS Bluetooth Adapter                              | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 90       | 55.21%  |
| Nvidia                 | 30       | 18.4%   |
| AMD                    | 25       | 15.34%  |
| VIA Technologies       | 4        | 2.45%   |
| C-Media Electronics    | 4        | 2.45%   |
| Creative Labs          | 3        | 1.84%   |
| Logitech               | 2        | 1.23%   |
| JMTek                  | 2        | 1.23%   |
| Unknown                | 1        | 0.61%   |
| Microsoft              | 1        | 0.61%   |
| Generalplus Technology | 1        | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 34       | 19.21%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 25       | 14.12%  |
| Nvidia MCP61 High Definition Audio                                          | 11       | 6.21%   |
| Nvidia GF119 HDMI Audio Controller                                          | 7        | 3.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 6        | 3.39%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 5        | 2.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 5        | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 5        | 2.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 5        | 2.82%   |
| AMD FCH Azalia Controller                                                   | 5        | 2.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 5        | 2.82%   |
| Nvidia High Definition Audio Controller                                     | 4        | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 4        | 2.26%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 3        | 1.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 3        | 1.69%   |
| Nvidia GF106 High Definition Audio Controller                               | 3        | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 3        | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 3        | 1.69%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 1.13%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                        | 2        | 1.13%   |
| C-Media Electronics CM108 Audio Controller                                  | 2        | 1.13%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                            | 2        | 1.13%   |
| AMD RV670/680 HDMI Audio [Radeon HD 3690/3800 Series]                       | 2        | 1.13%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]         | 2        | 1.13%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.56%   |
| Unknown Audio device                                                        | 1        | 0.56%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                   | 1        | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                          | 1        | 0.56%   |
| Nvidia GK104 HDMI Audio Controller                                          | 1        | 0.56%   |
| Nvidia GF116 High Definition Audio Controller                               | 1        | 0.56%   |
| Nvidia GF114 HDMI Audio Controller                                          | 1        | 0.56%   |
| Nvidia GF104 High Definition Audio Controller                               | 1        | 0.56%   |
| Microsoft LifeChat LX-6000 Headset                                          | 1        | 0.56%   |
| Logitech V20 portable speakers (USB powered)                                | 1        | 0.56%   |
| Logitech H600 [Wireless Headset]                                            | 1        | 0.56%   |
| JMTek USB PnP Audio Device                                                  | 1        | 0.56%   |
| JMTek audio controller                                                      | 1        | 0.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                 | 1        | 0.56%   |
| Intel Cannon Lake PCH cAVS                                                  | 1        | 0.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 1        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 38       | 38%     |
| Kingston            | 11       | 11%     |
| Samsung Electronics | 9        | 9%      |
| Corsair             | 7        | 7%      |
| SK hynix            | 6        | 6%      |
| Ramaxel Technology  | 6        | 6%      |
| Crucial             | 4        | 4%      |
| Nanya Technology    | 3        | 3%      |
| Micron Technology   | 3        | 3%      |
| Elpida              | 2        | 2%      |
| Avant               | 2        | 2%      |
| A-DATA Technology   | 2        | 2%      |
| Unknown (0x0CBA)    | 1        | 1%      |
| Team                | 1        | 1%      |
| Qimonda             | 1        | 1%      |
| PNY                 | 1        | 1%      |
| OCZ                 | 1        | 1%      |
| Kreton              | 1        | 1%      |
| Unknown             | 1        | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 400MT/s                         | 3        | 2.63%   |
| Unknown RAM Module 2048MB DIMM DDR2                         | 3        | 2.63%   |
| Unknown RAM Module 1024MB DIMM DDR2                         | 3        | 2.63%   |
| Unknown RAM Module 4GB DIMM SDRAM                           | 2        | 1.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 2        | 1.75%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 2        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                   | 2        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2                            | 2        | 1.75%   |
| Unknown RAM Module 2GB DIMM 400MT/s                         | 2        | 1.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 1.75%   |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 2        | 1.75%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                 | 2        | 1.75%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s       | 2        | 1.75%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s       | 2        | 1.75%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s           | 2        | 1.75%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                        | 1        | 0.88%   |
| Unknown RAM Module 512MB DIMM DDR2                          | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM 667MT/s                         | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                        | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM SDRAM                        | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM                              | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                     | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                 | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR2 1639MT/s                | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                  | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR 133MT/s                     | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                  | 1        | 0.88%   |
| Unknown (0x0CBA) RAM JC4S8GB26C03D 8GB SODIMM DDR4 2667MT/s | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s          | 1        | 0.88%   |
| SK hynix RAM HYMP564U64EP8-Y5 512MB DIMM DDR2 667MT/s       | 1        | 0.88%   |
| SK hynix RAM HYMP112U64CP8-Y5 1024MB DIMM DDR2 1639MT/s     | 1        | 0.88%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 1        | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 32       | 39.51%  |
| DDR2    | 22       | 27.16%  |
| SDRAM   | 11       | 13.58%  |
| Unknown | 9        | 11.11%  |
| DDR     | 4        | 4.94%   |
| DDR4    | 3        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 76       | 96.2%   |
| SODIMM | 3        | 3.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 39       | 41.05%  |
| 4096  | 27       | 28.42%  |
| 1024  | 16       | 16.84%  |
| 8192  | 9        | 9.47%   |
| 16384 | 2        | 2.11%   |
| 512   | 2        | 2.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 21.11%  |
| Unknown | 16       | 17.78%  |
| 1333    | 15       | 16.67%  |
| 800     | 6        | 6.67%   |
| 667     | 5        | 5.56%   |
| 400     | 5        | 5.56%   |
| 1066    | 4        | 4.44%   |
| 533     | 4        | 4.44%   |
| 1639    | 3        | 3.33%   |
| 133     | 3        | 3.33%   |
| 2048    | 2        | 2.22%   |
| 3200    | 1        | 1.11%   |
| 3000    | 1        | 1.11%   |
| 2667    | 1        | 1.11%   |
| 2400    | 1        | 1.11%   |
| 2133    | 1        | 1.11%   |
| 1867    | 1        | 1.11%   |
| 1067    | 1        | 1.11%   |
| 1024    | 1        | 1.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 50%     |
| Seiko Epson         | 2        | 33.33%  |
| Samsung Electronics | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 16.67%  |
| Seiko Epson L210 Series                      | 1        | 16.67%  |
| Samsung ML-216x Series Laser Printer         | 1        | 16.67%  |
| HP LaserJet P1006                            | 1        | 16.67%  |
| HP LaserJet P1005                            | 1        | 16.67%  |
| HP Color LaserJet CP1215                     | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP Scanjet 200          | 1        | 50%     |
| Canon CanoScan LiDE 110 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 5        | 27.78%  |
| Samsung Electronics         | 2        | 11.11%  |
| Microsoft                   | 2        | 11.11%  |
| KYE Systems (Mouse Systems) | 2        | 11.11%  |
| IMC Networks                | 2        | 11.11%  |
| Suyin                       | 1        | 5.56%   |
| SiGma Micro                 | 1        | 5.56%   |
| Realtek Semiconductor       | 1        | 5.56%   |
| LG Electronics              | 1        | 5.56%   |
| Aveo Technology             | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 3        | 16.67%  |
| Samsung Galaxy series, misc. (MTP mode)               | 2        | 11.11%  |
| Suyin HP Webcam                                       | 1        | 5.56%   |
| SiGma Micro WebCam SiGma Micro                        | 1        | 5.56%   |
| Realtek HP 1.0MP High Definition Webcam               | 1        | 5.56%   |
| Microsoft LifeCam VX-5000                             | 1        | 5.56%   |
| Microsoft LifeCam Studio                              | 1        | 5.56%   |
| Logitech QuickCam Communicate MP/S5500                | 1        | 5.56%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 5.56%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 5.56%   |
| KYE Systems (Mouse Systems) FaceCam 1320              | 1        | 5.56%   |
| KYE Systems (Mouse Systems) eFace 2025                | 1        | 5.56%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                   | 1        | 5.56%   |
| IMC Networks USB 2.0 Camera                           | 1        | 5.56%   |
| Aveo USB2.0 Camera                                    | 1        | 5.56%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 94       | 78.99%  |
| 1     | 24       | 20.17%  |
| 2     | 1        | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 46.15%  |
| Communication controller | 10       | 38.46%  |
| Sound                    | 2        | 7.69%   |
| Net/wireless             | 2        | 7.69%   |

