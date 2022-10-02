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

Total: 157

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 12       | 10%     |
| Ubuntu 18.04       | 10       | 8.33%   |
| Debian 11          | 10       | 8.33%   |
| OpenMandriva 4.3   | 8        | 6.67%   |
| OpenMandriva 4.2   | 6        | 5%      |
| ROSA R11           | 4        | 3.33%   |
| Xubuntu 18.04      | 3        | 2.5%    |
| Linux Mint 20      | 3        | 2.5%    |
| Linux Mint 19.3    | 3        | 2.5%    |
| KDE neon 20.04     | 3        | 2.5%    |
| Debian 10          | 3        | 2.5%    |
| Arch Rolling       | 3        | 2.5%    |
| Zorin 16           | 2        | 1.67%   |
| Xubuntu 16.04      | 2        | 1.67%   |
| Ubuntu 22.04       | 2        | 1.67%   |
| Ubuntu 20.10       | 2        | 1.67%   |
| ROSA R9            | 2        | 1.67%   |
| OpenMandriva 4.50  | 2        | 1.67%   |
| Linux Mint 20.3    | 2        | 1.67%   |
| Linux Mint 20.1    | 2        | 1.67%   |
| Kubuntu 20.04      | 2        | 1.67%   |
| Zorin 15           | 1        | 0.83%   |
| Xubuntu 20.04      | 1        | 0.83%   |
| Ubuntu Unity 18.04 | 1        | 0.83%   |
| Ubuntu MATE 19.10  | 1        | 0.83%   |
| Ubuntu 19.10       | 1        | 0.83%   |
| Ubuntu 19.04       | 1        | 0.83%   |
| Sparky 5.12        | 1        | 0.83%   |
| Solus 4.3          | 1        | 0.83%   |
| ROSA R8            | 1        | 0.83%   |
| ROSA R11.1         | 1        | 0.83%   |
| ROSA 12.1          | 1        | 0.83%   |
| ROSA 12            | 1        | 0.83%   |
| Pop!_OS 20.04      | 1        | 0.83%   |
| PCLinuxOS 2022     | 1        | 0.83%   |
| MX 21              | 1        | 0.83%   |
| Manjaro 20.2.1     | 1        | 0.83%   |
| Manjaro            | 1        | 0.83%   |
| LMDE 5             | 1        | 0.83%   |
| Linux Mint 21      | 1        | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 27       | 23.08%  |
| OpenMandriva | 16       | 13.68%  |
| Debian       | 15       | 12.82%  |
| Linux Mint   | 12       | 10.26%  |
| ROSA         | 10       | 8.55%   |
| Xubuntu      | 5        | 4.27%   |
| KDE neon     | 4        | 3.42%   |
| Arch         | 4        | 3.42%   |
| Zorin        | 3        | 2.56%   |
| Fedora       | 3        | 2.56%   |
| Manjaro      | 2        | 1.71%   |
| Kubuntu      | 2        | 1.71%   |
| Elementary   | 2        | 1.71%   |
| Ubuntu Unity | 1        | 0.85%   |
| Ubuntu MATE  | 1        | 0.85%   |
| Sparky       | 1        | 0.85%   |
| Solus        | 1        | 0.85%   |
| Pop!_OS      | 1        | 0.85%   |
| PCLinuxOS    | 1        | 0.85%   |
| MX           | 1        | 0.85%   |
| LMDE         | 1        | 0.85%   |
| Kali         | 1        | 0.85%   |
| Garuda Linux | 1        | 0.85%   |
| Feren OS     | 1        | 0.85%   |
| Endless      | 1        | 0.85%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 8        | 6.3%    |
| 5.10.14-desktop-1omv4002       | 6        | 4.72%   |
| 5.4.0-42-generic               | 4        | 3.15%   |
| 5.8.0-55-generic               | 2        | 1.57%   |
| 5.4.0-77-generic               | 2        | 1.57%   |
| 5.4.0-74-generic               | 2        | 1.57%   |
| 5.4.0-54-generic               | 2        | 1.57%   |
| 5.4.0-26-generic               | 2        | 1.57%   |
| 5.3.0-40-generic               | 2        | 1.57%   |
| 5.15.0-46-generic              | 2        | 1.57%   |
| 5.13.0-27-generic              | 2        | 1.57%   |
| 5.10.0-8-amd64                 | 2        | 1.57%   |
| 5.10.0-16-amd64                | 2        | 1.57%   |
| 5.10.0-14-amd64                | 2        | 1.57%   |
| 5.10.0-11-amd64                | 2        | 1.57%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 1.57%   |
| 4.15.0-48-generic              | 2        | 1.57%   |
| 4.15.0-112-generic             | 2        | 1.57%   |
| 5.9.16-1-MANJARO               | 1        | 0.79%   |
| 5.8.11-arch1-1                 | 1        | 0.79%   |
| 5.8.10-17-tkg-bmq              | 1        | 0.79%   |
| 5.8.0-63-generic               | 1        | 0.79%   |
| 5.8.0-59-generic               | 1        | 0.79%   |
| 5.8.0-44-generic               | 1        | 0.79%   |
| 5.8.0-40-generic               | 1        | 0.79%   |
| 5.6.0-1-amd64                  | 1        | 0.79%   |
| 5.4.0-96-generic               | 1        | 0.79%   |
| 5.4.0-88-generic               | 1        | 0.79%   |
| 5.4.0-7634-generic             | 1        | 0.79%   |
| 5.4.0-72-generic               | 1        | 0.79%   |
| 5.4.0-66-generic               | 1        | 0.79%   |
| 5.4.0-47-generic               | 1        | 0.79%   |
| 5.4.0-42-lowlatency            | 1        | 0.79%   |
| 5.4.0-31-generic               | 1        | 0.79%   |
| 5.4.0-29-generic               | 1        | 0.79%   |
| 5.4.0-122-generic              | 1        | 0.79%   |
| 5.4.0-113-generic              | 1        | 0.79%   |
| 5.4.0-109-generic              | 1        | 0.79%   |
| 5.3.0-42-generic               | 1        | 0.79%   |
| 5.3.0-29-generic               | 1        | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 22       | 18.18%  |
| 4.15.0  | 18       | 14.88%  |
| 5.10.0  | 12       | 9.92%   |
| 5.16.7  | 8        | 6.61%   |
| 5.8.0   | 6        | 4.96%   |
| 5.10.14 | 6        | 4.96%   |
| 5.3.0   | 5        | 4.13%   |
| 5.13.0  | 5        | 4.13%   |
| 5.15.0  | 4        | 3.31%   |
| 5.11.0  | 3        | 2.48%   |
| 5.0.0   | 3        | 2.48%   |
| 4.19.0  | 3        | 2.48%   |
| 4.9.20  | 2        | 1.65%   |
| 4.9.0   | 2        | 1.65%   |
| 5.9.16  | 1        | 0.83%   |
| 5.8.11  | 1        | 0.83%   |
| 5.8.10  | 1        | 0.83%   |
| 5.6.0   | 1        | 0.83%   |
| 5.19.9  | 1        | 0.83%   |
| 5.19.5  | 1        | 0.83%   |
| 5.18.7  | 1        | 0.83%   |
| 5.16.14 | 1        | 0.83%   |
| 5.15.6  | 1        | 0.83%   |
| 5.15.57 | 1        | 0.83%   |
| 5.15.48 | 1        | 0.83%   |
| 5.14.10 | 1        | 0.83%   |
| 5.13.16 | 1        | 0.83%   |
| 5.13.1  | 1        | 0.83%   |
| 5.12.4  | 1        | 0.83%   |
| 5.10.74 | 1        | 0.83%   |
| 5.10.71 | 1        | 0.83%   |
| 5.10.3  | 1        | 0.83%   |
| 4.4.0   | 1        | 0.83%   |
| 4.18.0  | 1        | 0.83%   |
| 4.13.0  | 1        | 0.83%   |
| 4.1.15  | 1        | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 22       | 18.33%  |
| 5.10    | 21       | 17.5%   |
| 4.15    | 18       | 15%     |
| 5.16    | 9        | 7.5%    |
| 5.8     | 8        | 6.67%   |
| 5.13    | 7        | 5.83%   |
| 5.15    | 6        | 5%      |
| 5.3     | 5        | 4.17%   |
| 4.9     | 4        | 3.33%   |
| 5.11    | 3        | 2.5%    |
| 5.0     | 3        | 2.5%    |
| 4.19    | 3        | 2.5%    |
| 5.19    | 2        | 1.67%   |
| 5.9     | 1        | 0.83%   |
| 5.6     | 1        | 0.83%   |
| 5.18    | 1        | 0.83%   |
| 5.14    | 1        | 0.83%   |
| 5.12    | 1        | 0.83%   |
| 4.4     | 1        | 0.83%   |
| 4.18    | 1        | 0.83%   |
| 4.13    | 1        | 0.83%   |
| 4.1     | 1        | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 101      | 87.07%  |
| i686   | 15       | 12.93%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 31       | 25.83%  |
| GNOME           | 31       | 25.83%  |
| Unknown         | 15       | 12.5%   |
| XFCE            | 12       | 10%     |
| X-Cinnamon      | 5        | 4.17%   |
| MATE            | 5        | 4.17%   |
| KDE             | 5        | 4.17%   |
| LXDE            | 4        | 3.33%   |
| KDE4            | 4        | 3.33%   |
| Cinnamon        | 2        | 1.67%   |
| xmonad          | 1        | 0.83%   |
| Unity           | 1        | 0.83%   |
| Pantheon        | 1        | 0.83%   |
| LXQt            | 1        | 0.83%   |
| GNOME Flashback | 1        | 0.83%   |
| Budgie          | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 100      | 86.96%  |
| Wayland | 10       | 8.7%    |
| Unknown | 4        | 3.48%   |
| Tty     | 1        | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 42.74%  |
| SDDM    | 30       | 25.64%  |
| GDM     | 12       | 10.26%  |
| LightDM | 11       | 9.4%    |
| TDM     | 6        | 5.13%   |
| KDM     | 4        | 3.42%   |
| GDM3    | 3        | 2.56%   |
| SLiM    | 1        | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_VE   | 67       | 57.76%  |
| en_US   | 22       | 18.97%  |
| Unknown | 17       | 14.66%  |
| es_ES   | 5        | 4.31%   |
| es_US   | 2        | 1.72%   |
| C       | 2        | 1.72%   |
| de_DE   | 1        | 0.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 102      | 89.47%  |
| EFI  | 12       | 10.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 88       | 75.86%  |
| Overlay | 16       | 13.79%  |
| Btrfs   | 5        | 4.31%   |
| Unknown | 5        | 4.31%   |
| Xfs     | 1        | 0.86%   |
| Ext2    | 1        | 0.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 49.57%  |
| MBR     | 43       | 37.39%  |
| GPT     | 15       | 13.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 90       | 78.26%  |
| Yes       | 25       | 21.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 55.65%  |
| Yes       | 51       | 44.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 22       | 19.3%   |
| ECS                 | 12       | 10.53%  |
| Pegatron            | 10       | 8.77%   |
| Lenovo              | 10       | 8.77%   |
| Intel               | 10       | 8.77%   |
| ASUSTek Computer    | 9        | 7.89%   |
| Hewlett-Packard     | 7        | 6.14%   |
| Biostar             | 7        | 6.14%   |
| Gigabyte Technology | 6        | 5.26%   |
| Dell                | 5        | 4.39%   |
| MSI                 | 4        | 3.51%   |
| langchao            | 4        | 3.51%   |
| Foxconn             | 4        | 3.51%   |
| IP3 Tech            | 1        | 0.88%   |
| Inspur              | 1        | 0.88%   |
| IBM                 | 1        | 0.88%   |
| Unknown             | 1        | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ECS H61H2-CM                         | 7        | 6.14%   |
| ASRock G41M-VS3                      | 6        | 5.26%   |
| langchao 12345                       | 4        | 3.51%   |
| Pegatron Compaq dx2400 Microtower    | 2        | 1.75%   |
| ASRock N68C-S UCC                    | 2        | 1.75%   |
| ASRock N68-VS3 UCC                   | 2        | 1.75%   |
| Pegatron PEGATRON                    | 1        | 0.88%   |
| Pegatron IPPEL-DB                    | 1        | 0.88%   |
| Pegatron IPM41-D3                    | 1        | 0.88%   |
| Pegatron CQ1507LA                    | 1        | 0.88%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.88%   |
| Pegatron BM411AA-ABA CQ5600F         | 1        | 0.88%   |
| Pegatron 20-b010                     | 1        | 0.88%   |
| Pegatron 100-5010la                  | 1        | 0.88%   |
| MSI Pro 3000 Microtower PC           | 1        | 0.88%   |
| MSI MS-7817                          | 1        | 0.88%   |
| MSI MS-7721                          | 1        | 0.88%   |
| MSI MS-7375                          | 1        | 0.88%   |
| Lenovo ThinkCentre XXXX 8705A84      | 1        | 0.88%   |
| Lenovo ThinkCentre M91 7516AD1       | 1        | 0.88%   |
| Lenovo ThinkCentre M71e 3157G6S      | 1        | 0.88%   |
| Lenovo ThinkCentre M55E 9645BN2      | 1        | 0.88%   |
| Lenovo ThinkCentre M55E 9632BU8      | 1        | 0.88%   |
| Lenovo ThinkCentre A58 7515A33       | 1        | 0.88%   |
| Lenovo ThinkCentre A55 8705AV4       | 1        | 0.88%   |
| Lenovo H220 10028                    | 1        | 0.88%   |
| Lenovo 70A4000HUX ThinkServer TS140  | 1        | 0.88%   |
| Lenovo 11051CS ThinkServer TS130     | 1        | 0.88%   |
| IP3 Tech TB20                        | 1        | 0.88%   |
| Intel MAHOBAY                        | 1        | 0.88%   |
| Intel H61                            | 1        | 0.88%   |
| Intel DH77EB AAG39073-304            | 1        | 0.88%   |
| Intel DG41TY AAE47335-203            | 1        | 0.88%   |
| Intel DG41TX AAE78178-303            | 1        | 0.88%   |
| Intel DG35EC AAE29266-205            | 1        | 0.88%   |
| Intel DG33BU AAD79951-407            | 1        | 0.88%   |
| Intel DG31PR AAD97573-302            | 1        | 0.88%   |
| Intel D946GZIS AAD66165-302          | 1        | 0.88%   |
| Intel D945GCCR AAD78647-300          | 1        | 0.88%   |
| Inspur                               | 1        | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Lenovo ThinkCentre    | 7        | 6.14%   |
| HP Compaq             | 7        | 6.14%   |
| ECS H61H2-CM          | 7        | 6.14%   |
| ASRock G41M-VS3       | 6        | 5.26%   |
| langchao 12345        | 4        | 3.51%   |
| Pegatron Compaq       | 3        | 2.63%   |
| Dell Vostro           | 2        | 1.75%   |
| Dell OptiPlex         | 2        | 1.75%   |
| ASUS P5G41T-M         | 2        | 1.75%   |
| ASRock N68C-S         | 2        | 1.75%   |
| ASRock N68-VS3        | 2        | 1.75%   |
| Pegatron PEGATRON     | 1        | 0.88%   |
| Pegatron IPPEL-DB     | 1        | 0.88%   |
| Pegatron IPM41-D3     | 1        | 0.88%   |
| Pegatron CQ1507LA     | 1        | 0.88%   |
| Pegatron BM411AA-ABA  | 1        | 0.88%   |
| Pegatron 20-b010      | 1        | 0.88%   |
| Pegatron 100-5010la   | 1        | 0.88%   |
| MSI Pro               | 1        | 0.88%   |
| MSI MS-7817           | 1        | 0.88%   |
| MSI MS-7721           | 1        | 0.88%   |
| MSI MS-7375           | 1        | 0.88%   |
| Lenovo H220           | 1        | 0.88%   |
| Lenovo 70A4000HUX     | 1        | 0.88%   |
| Lenovo 11051CS        | 1        | 0.88%   |
| IP3 Tech TB20         | 1        | 0.88%   |
| Intel MAHOBAY         | 1        | 0.88%   |
| Intel H61             | 1        | 0.88%   |
| Intel DH77EB          | 1        | 0.88%   |
| Intel DG41TY          | 1        | 0.88%   |
| Intel DG41TX          | 1        | 0.88%   |
| Intel DG35EC          | 1        | 0.88%   |
| Intel DG33BU          | 1        | 0.88%   |
| Intel DG31PR          | 1        | 0.88%   |
| Intel D946GZIS        | 1        | 0.88%   |
| Intel D945GCCR        | 1        | 0.88%   |
| Inspur                | 1        | 0.88%   |
| IBM 8188LS4           | 1        | 0.88%   |
| Gigabyte Z97N-WIFI    | 1        | 0.88%   |
| Gigabyte Z68X-UD3H-B3 | 1        | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 27       | 23.68%  |
| 2011 | 26       | 22.81%  |
| 2012 | 14       | 12.28%  |
| 2008 | 13       | 11.4%   |
| 2007 | 10       | 8.77%   |
| 2006 | 7        | 6.14%   |
| 2014 | 4        | 3.51%   |
| 2013 | 3        | 2.63%   |
| 2017 | 2        | 1.75%   |
| 2009 | 2        | 1.75%   |
| 2021 | 1        | 0.88%   |
| 2020 | 1        | 0.88%   |
| 2019 | 1        | 0.88%   |
| 2016 | 1        | 0.88%   |
| 2015 | 1        | 0.88%   |
| 2005 | 1        | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 114      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 114      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 114      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 34       | 29.06%  |
| 4.01-8.0   | 26       | 22.22%  |
| 1.01-2.0   | 19       | 16.24%  |
| 8.01-16.0  | 17       | 14.53%  |
| 16.01-24.0 | 10       | 8.55%   |
| 2.01-3.0   | 4        | 3.42%   |
| 24.01-32.0 | 3        | 2.56%   |
| 32.01-64.0 | 2        | 1.71%   |
| 0.51-1.0   | 2        | 1.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 49       | 39.52%  |
| 2.01-3.0 | 31       | 25%     |
| 0.51-1.0 | 19       | 15.32%  |
| 4.01-8.0 | 13       | 10.48%  |
| 3.01-4.0 | 8        | 6.45%   |
| 0.01-0.5 | 4        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 68       | 57.63%  |
| 2      | 36       | 30.51%  |
| 3      | 12       | 10.17%  |
| 4      | 2        | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 55.08%  |
| Yes       | 53       | 44.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 112      | 98.25%  |
| No        | 2        | 1.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 50.43%  |
| Yes       | 57       | 49.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 89.57%  |
| Yes       | 12       | 10.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Venezuela | 114      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Caracas                  | 59       | 48.36%  |
| Maracay                  | 7        | 5.74%   |
| Valencia                 | 5        | 4.1%    |
| San Cristóbal           | 5        | 4.1%    |
| Maracaibo                | 4        | 3.28%   |
| San Carlos del Zulia     | 3        | 2.46%   |
| Maturín                 | 3        | 2.46%   |
| Carrizal                 | 3        | 2.46%   |
| Barquisimeto             | 3        | 2.46%   |
| Barcelona                | 3        | 2.46%   |
| San Antonio de Los Altos | 2        | 1.64%   |
| Mérida                  | 2        | 1.64%   |
| Los Teques               | 2        | 1.64%   |
| Ciudad Bolívar          | 2        | 1.64%   |
| Barinas                  | 2        | 1.64%   |
| Valle de La Pascua       | 1        | 0.82%   |
| Tucupita                 | 1        | 0.82%   |
| San Juan Bautista        | 1        | 0.82%   |
| San Francisco            | 1        | 0.82%   |
| Porlamar                 | 1        | 0.82%   |
| Parroquia El Recreo      | 1        | 0.82%   |
| Los Palos Grandes        | 1        | 0.82%   |
| Lecherias                | 1        | 0.82%   |
| Las Vegas                | 1        | 0.82%   |
| Guatire                  | 1        | 0.82%   |
| Guarenas                 | 1        | 0.82%   |
| Cua                      | 1        | 0.82%   |
| Ciudad Guayana           | 1        | 0.82%   |
| Carora                   | 1        | 0.82%   |
| Cabimas                  | 1        | 0.82%   |
| Baruta                   | 1        | 0.82%   |
| Acarigua                 | 1        | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 52       | 71     | 32.91%  |
| Seagate             | 37       | 54     | 23.42%  |
| Hitachi             | 25       | 29     | 15.82%  |
| Samsung Electronics | 12       | 15     | 7.59%   |
| Toshiba             | 10       | 11     | 6.33%   |
| Kingston            | 7        | 7      | 4.43%   |
| Maxtor              | 4        | 4      | 2.53%   |
| PNY                 | 2        | 2      | 1.27%   |
| Patriot             | 2        | 2      | 1.27%   |
| Unknown             | 1        | 1      | 0.63%   |
| Team                | 1        | 1      | 0.63%   |
| SPCC                | 1        | 1      | 0.63%   |
| HGST                | 1        | 1      | 0.63%   |
| Fujitsu             | 1        | 1      | 0.63%   |
| ExcelStor           | 1        | 1      | 0.63%   |
| Dogfish             | 1        | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 9        | 5%      |
| Toshiba DT01ACA050 500GB            | 6        | 3.33%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 4        | 2.22%   |
| Seagate ST500DM002-1BD142 500GB     | 4        | 2.22%   |
| Seagate ST3320418AS 320GB           | 4        | 2.22%   |
| WDC WD5000AAKX-221CA1 500GB         | 3        | 1.67%   |
| WDC WD5000AAKX-001CA0 500GB         | 3        | 1.67%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3        | 1.67%   |
| WDC WD3200AAJS-08L7A0 320GB         | 3        | 1.67%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3        | 1.67%   |
| Seagate ST320LM000 HM321HI 320GB    | 3        | 1.67%   |
| Samsung HD502HJ 500GB               | 3        | 1.67%   |
| Samsung HD161HJ 160GB               | 3        | 1.67%   |
| Kingston SA400S37240G 240GB SSD     | 3        | 1.67%   |
| Hitachi HTS542580K9SA00 80GB        | 3        | 1.67%   |
| WDC WD800BD-22MRA1 80GB             | 2        | 1.11%   |
| WDC WD800BB-22JHC0 80GB             | 2        | 1.11%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2        | 1.11%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 2        | 1.11%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2        | 1.11%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2        | 1.11%   |
| Seagate ST3250310AS 250GB           | 2        | 1.11%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 2        | 1.11%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 1.11%   |
| Hitachi HTS545032B9A300 320GB       | 2        | 1.11%   |
| Hitachi HDS728080PLA380 82GB        | 2        | 1.11%   |
| Hitachi HDS721616PLA380 160GB       | 2        | 1.11%   |
| Hitachi HDS721032CLA362 320GB       | 2        | 1.11%   |
| WDC WD800JD-60LSA5 80GB             | 1        | 0.56%   |
| WDC WD800BD-08MRA1 80GB             | 1        | 0.56%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 0.56%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 0.56%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1        | 0.56%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 0.56%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1        | 0.56%   |
| WDC WD5000AAJS-08A8B0 500GB         | 1        | 0.56%   |
| WDC WD5000AACS-61M6B2 500GB         | 1        | 0.56%   |
| WDC WD5000AACS-22ZUB0 500GB         | 1        | 0.56%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1        | 0.56%   |
| WDC WD3200BEKT-22F3T0 320GB         | 1        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 52       | 71     | 36.36%  |
| Seagate             | 37       | 54     | 25.87%  |
| Hitachi             | 25       | 29     | 17.48%  |
| Samsung Electronics | 12       | 15     | 8.39%   |
| Toshiba             | 10       | 11     | 6.99%   |
| Maxtor              | 4        | 4      | 2.8%    |
| HGST                | 1        | 1      | 0.7%    |
| Fujitsu             | 1        | 1      | 0.7%    |
| ExcelStor           | 1        | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Kingston | 7        | 7      | 50%     |
| PNY      | 2        | 2      | 14.29%  |
| Patriot  | 2        | 2      | 14.29%  |
| Team     | 1        | 1      | 7.14%   |
| SPCC     | 1        | 1      | 7.14%   |
| Dogfish  | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 103      | 187    | 88.03%  |
| SSD  | 13       | 14     | 11.11%  |
| NVMe | 1        | 1      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 113      | 201    | 99.12%  |
| NVMe | 1        | 1      | 0.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 108      | 176    | 81.82%  |
| 0.51-1.0   | 13       | 13     | 9.85%   |
| 1.01-2.0   | 7        | 7      | 5.3%    |
| 3.01-4.0   | 2        | 2      | 1.52%   |
| 2.01-3.0   | 2        | 3      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 42       | 34.43%  |
| 101-250        | 27       | 22.13%  |
| 501-1000       | 15       | 12.3%   |
| 1-20           | 14       | 11.48%  |
| 51-100         | 12       | 9.84%   |
| 1001-2000      | 4        | 3.28%   |
| 2001-3000      | 3        | 2.46%   |
| 21-50          | 2        | 1.64%   |
| Unknown        | 2        | 1.64%   |
| More than 3000 | 1        | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 55       | 45.45%  |
| 101-250        | 18       | 14.88%  |
| 21-50          | 17       | 14.05%  |
| 251-500        | 12       | 9.92%   |
| 51-100         | 9        | 7.44%   |
| 501-1000       | 4        | 3.31%   |
| 2001-3000      | 2        | 1.65%   |
| Unknown        | 2        | 1.65%   |
| More than 3000 | 1        | 0.83%   |
| 1001-2000      | 1        | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB         | 5        | 6      | 9.62%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 2        | 3      | 3.85%   |
| WDC WD5000AAKX-221CA1 500GB             | 2        | 2      | 3.85%   |
| WDC WD5000AAKS-00A7B0 500GB             | 2        | 2      | 3.85%   |
| Toshiba DT01ACA050 500GB                | 2        | 3      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB         | 2        | 2      | 3.85%   |
| Hitachi HDS721616PLA380 160GB           | 2        | 2      | 3.85%   |
| WDC WD800BD-08MRA1 80GB                 | 1        | 1      | 1.92%   |
| WDC WD800BB-22JHC0 80GB                 | 1        | 1      | 1.92%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1        | 1      | 1.92%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 1        | 1      | 1.92%   |
| WDC WD5000AAKX-08ERMA0 500GB            | 1        | 1      | 1.92%   |
| WDC WD5000AACS-00ZUB0 500GB             | 1        | 1      | 1.92%   |
| WDC WD3200BEKT-22F3T0 320GB             | 1        | 1      | 1.92%   |
| WDC WD3200AAJS-08L7A0 320GB             | 1        | 2      | 1.92%   |
| WDC WD2003FYPS-27Y2B0 2TB               | 1        | 1      | 1.92%   |
| WDC WD10EZEX-22RKKA0 1TB                | 1        | 1      | 1.92%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1        | 1      | 1.92%   |
| Seagate ST3500630AS 500GB               | 1        | 1      | 1.92%   |
| Seagate ST3500418AS 500GB               | 1        | 1      | 1.92%   |
| Seagate ST3500413AS 500GB               | 1        | 1      | 1.92%   |
| Seagate ST3500312CS 500GB               | 1        | 1      | 1.92%   |
| Seagate ST340014AS 40GB                 | 1        | 1      | 1.92%   |
| Seagate ST3320418AS 320GB               | 1        | 2      | 1.92%   |
| Seagate ST3250318AS 250GB               | 1        | 1      | 1.92%   |
| Seagate ST3250310AS 250GB               | 1        | 1      | 1.92%   |
| Seagate ST3160215ACE 160GB              | 1        | 1      | 1.92%   |
| Seagate ST3160212SCE 160GB              | 1        | 1      | 1.92%   |
| Seagate ST31000525SV 1TB                | 1        | 1      | 1.92%   |
| Samsung Electronics HM321HI 320GB       | 1        | 1      | 1.92%   |
| Samsung Electronics HD161HJ 160GB       | 1        | 2      | 1.92%   |
| Samsung Electronics HD155UI 1TB         | 1        | 1      | 1.92%   |
| Maxtor STM3250310AS 250GB               | 1        | 1      | 1.92%   |
| Maxtor STM3160215AS 160GB               | 1        | 1      | 1.92%   |
| Hitachi HUA722020ALA331 2TB             | 1        | 1      | 1.92%   |
| Hitachi HDT721016SLA380 160GB           | 1        | 1      | 1.92%   |
| Hitachi HDS728080PLA380 82GB            | 1        | 1      | 1.92%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB | 1        | 1      | 1.92%   |
| Hitachi HDS721050DLE630 500GB           | 1        | 1      | 1.92%   |
| Hitachi HDS721032CLA362 320GB           | 1        | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 36.96%  |
| WDC                 | 12       | 19     | 26.09%  |
| Hitachi             | 9        | 9      | 19.57%  |
| Samsung Electronics | 3        | 4      | 6.52%   |
| Toshiba             | 2        | 3      | 4.35%   |
| Maxtor              | 2        | 2      | 4.35%   |
| ExcelStor           | 1        | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 36.96%  |
| WDC                 | 12       | 19     | 26.09%  |
| Hitachi             | 9        | 9      | 19.57%  |
| Samsung Electronics | 3        | 4      | 6.52%   |
| Toshiba             | 2        | 3      | 4.35%   |
| Maxtor              | 2        | 2      | 4.35%   |
| ExcelStor           | 1        | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 58     | 100%    |

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
| Detected | 58       | 99     | 45.31%  |
| Malfunc  | 36       | 58     | 28.13%  |
| Works    | 32       | 43     | 25%     |
| Failed   | 2        | 2      | 1.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 88       | 69.29%  |
| Nvidia                   | 12       | 9.45%   |
| AMD                      | 11       | 8.66%   |
| Marvell Technology Group | 5        | 3.94%   |
| JMicron Technology       | 5        | 3.94%   |
| VIA Technologies         | 3        | 2.36%   |
| ASMedia Technology       | 1        | 0.79%   |
| Adaptec                  | 1        | 0.79%   |
| Unknown                  | 1        | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 32       | 16.08%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24       | 12.06%  |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13       | 6.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13       | 6.53%   |
| Nvidia MCP61 SATA Controller                                                            | 11       | 5.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 5.53%   |
| Nvidia MCP61 IDE                                                                        | 9        | 4.52%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 2.51%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 2.51%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 2.51%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 2.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 2.01%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 2.01%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 1.51%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 1.51%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 1.51%   |
| VIA Serial ATA Controller                                                               | 2        | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.01%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 1.01%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.01%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.01%   |
| AMD FCH IDE Controller                                                                  | 2        | 1.01%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.5%    |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 0.5%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.5%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.5%    |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.5%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.5%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.5%    |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.5%    |
| JMicron JMB368 IDE controller                                                           | 1        | 0.5%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 1        | 0.5%    |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.5%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 81       | 64.29%  |
| SATA | 40       | 31.75%  |
| RAID | 2        | 1.59%   |
| SAS  | 1        | 0.79%   |
| SCSI | 1        | 0.79%   |
| NVMe | 1        | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 91       | 79.82%  |
| AMD    | 23       | 20.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 6        | 5.26%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6        | 5.26%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4        | 3.51%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 3        | 2.63%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 3        | 2.63%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 2.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.63%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 2.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 2.63%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.63%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 2        | 1.75%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2        | 1.75%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 1.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.75%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 1.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.75%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.75%   |
| AMD Sempron 145 Processor                   | 2        | 1.75%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.88%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.88%   |
| Intel Xeon CPU E5-1607 0 @ 3.00GHz          | 1        | 0.88%   |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.88%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.88%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.88%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 0.88%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.88%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.88%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.88%   |
| Intel Pentium CPU E5800 @ 3.20GHz           | 1        | 0.88%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 0.88%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.88%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 0.88%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 0.88%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.88%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.88%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 0.88%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 0.88%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium Dual-Core | 21       | 18.42%  |
| Intel Core i5           | 13       | 11.4%   |
| Intel Pentium           | 9        | 7.89%   |
| Intel Core i3           | 8        | 7.02%   |
| Intel Core i7           | 7        | 6.14%   |
| Intel Core 2 Duo        | 7        | 6.14%   |
| Intel Pentium Dual      | 5        | 4.39%   |
| AMD Sempron             | 5        | 4.39%   |
| Intel Xeon              | 4        | 3.51%   |
| Intel Pentium 4         | 4        | 3.51%   |
| Intel Core 2 Quad       | 4        | 3.51%   |
| Intel Core 2            | 4        | 3.51%   |
| Intel Celeron           | 2        | 1.75%   |
| AMD Phenom II X4        | 2        | 1.75%   |
| AMD Phenom              | 2        | 1.75%   |
| AMD FX                  | 2        | 1.75%   |
| AMD Athlon II X2        | 2        | 1.75%   |
| AMD Athlon              | 2        | 1.75%   |
| Other                   | 1        | 0.88%   |
| Intel Pentium D         | 1        | 0.88%   |
| Intel Atom              | 1        | 0.88%   |
| AMD Phenom II X2        | 1        | 0.88%   |
| AMD E1                  | 1        | 0.88%   |
| AMD Athlon II X4        | 1        | 0.88%   |
| AMD Athlon II           | 1        | 0.88%   |
| AMD Athlon 64 X2        | 1        | 0.88%   |
| AMD A8                  | 1        | 0.88%   |
| AMD A6                  | 1        | 0.88%   |
| AMD A4                  | 1        | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 63       | 55.26%  |
| 4       | 35       | 30.7%   |
| 1       | 11       | 9.65%   |
| 3       | 3        | 2.63%   |
| Unknown | 2        | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 114      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 88       | 77.19%  |
| 2       | 24       | 21.05%  |
| Unknown | 2        | 1.75%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 110      | 96.49%  |
| 64-bit         | 2        | 1.75%   |
| 32-bit         | 1        | 0.88%   |
| Unknown        | 1        | 0.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 26       | 22.81%  |
| 0x206a7    | 15       | 13.16%  |
| Unknown    | 15       | 13.16%  |
| 0x306a9    | 8        | 7.02%   |
| 0x306c3    | 5        | 4.39%   |
| 0x6fd      | 4        | 3.51%   |
| 0x6fb      | 4        | 3.51%   |
| 0x010000c8 | 4        | 3.51%   |
| 0xf65      | 3        | 2.63%   |
| 0x6f2      | 3        | 2.63%   |
| 0x106a5    | 2        | 1.75%   |
| 0x10676    | 2        | 1.75%   |
| 0x010000c7 | 2        | 1.75%   |
| 0xf47      | 1        | 0.88%   |
| 0xf41      | 1        | 0.88%   |
| 0x906eb    | 1        | 0.88%   |
| 0x906e9    | 1        | 0.88%   |
| 0x806c1    | 1        | 0.88%   |
| 0x6f6      | 1        | 0.88%   |
| 0x206d7    | 1        | 0.88%   |
| 0x106ca    | 1        | 0.88%   |
| 0x10661    | 1        | 0.88%   |
| 0x0810100b | 1        | 0.88%   |
| 0x0700010b | 1        | 0.88%   |
| 0x06001119 | 1        | 0.88%   |
| 0x06000852 | 1        | 0.88%   |
| 0x0600063e | 1        | 0.88%   |
| 0x05000119 | 1        | 0.88%   |
| 0x03000027 | 1        | 0.88%   |
| 0x03000014 | 1        | 0.88%   |
| 0x010000db | 1        | 0.88%   |
| 0x010000b6 | 1        | 0.88%   |
| 0x01000095 | 1        | 0.88%   |
| 0x01000065 | 1        | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 30       | 26.32%  |
| SandyBridge | 19       | 16.67%  |
| Core        | 15       | 13.16%  |
| K10         | 12       | 10.53%  |
| IvyBridge   | 10       | 8.77%   |
| Haswell     | 6        | 5.26%   |
| NetBurst    | 5        | 4.39%   |
| K8 Hammer   | 3        | 2.63%   |
| Piledriver  | 2        | 1.75%   |
| Nehalem     | 2        | 1.75%   |
| KabyLake    | 2        | 1.75%   |
| K10 Llano   | 2        | 1.75%   |
| Zen         | 1        | 0.88%   |
| TigerLake   | 1        | 0.88%   |
| Jaguar      | 1        | 0.88%   |
| Bulldozer   | 1        | 0.88%   |
| Bonnell     | 1        | 0.88%   |
| Bobcat      | 1        | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 68       | 56.2%   |
| Nvidia           | 30       | 24.79%  |
| AMD              | 20       | 16.53%  |
| VIA Technologies | 3        | 2.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 16       | 13.22%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15       | 12.4%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7        | 5.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.13%   |
| Nvidia GF119 [GeForce GT 520]                                               | 4        | 3.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 3.31%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 3.31%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 4        | 3.31%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 3.31%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 3        | 2.48%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 2.48%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 2.48%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.65%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 2        | 1.65%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 1.65%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.65%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 1.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.65%   |
| Intel 82865G Integrated Graphics Controller                                 | 2        | 1.65%   |
| AMD RV670 [Radeon HD 3870]                                                  | 2        | 1.65%   |
| Nvidia NV44 [GeForce 7100 GS]                                               | 1        | 0.83%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.83%   |
| Nvidia GT218 [GeForce 405]                                                  | 1        | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.83%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.83%   |
| Nvidia GK104GL [Quadro K4200]                                               | 1        | 0.83%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.83%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.83%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.83%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.83%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 0.83%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 0.83%   |
| Intel Xeon E3-1200 Processor Family Integrated Graphics Controller          | 1        | 0.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1        | 0.83%   |
| Intel HD Graphics 630                                                       | 1        | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 0.83%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 0.83%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 0.83%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 0.83%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Intel    | 63       | 54.78%  |
| 1 x Nvidia   | 29       | 25.22%  |
| 1 x AMD      | 18       | 15.65%  |
| 1 x VIA      | 3        | 2.61%   |
| Intel + AMD  | 1        | 0.87%   |
| AMD + Nvidia | 1        | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 94       | 82.46%  |
| Proprietary | 11       | 9.65%   |
| Unknown     | 9        | 7.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 52.14%  |
| 0.51-1.0   | 22       | 18.8%   |
| 0.01-0.5   | 19       | 16.24%  |
| 1.01-2.0   | 12       | 10.26%  |
| 3.01-4.0   | 3        | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung Electronics                   | 32       | 30.48%  |
| Hewlett-Packard                       | 12       | 11.43%  |
| Goldstar                              | 11       | 10.48%  |
| Lenovo                                | 8        | 7.62%   |
| Toshiba                               | 7        | 6.67%   |
| Dell                                  | 7        | 6.67%   |
| AOC                                   | 5        | 4.76%   |
| BenQ                                  | 3        | 2.86%   |
| Acer                                  | 3        | 2.86%   |
| Sony                                  | 2        | 1.9%    |
| Envision                              | 2        | 1.9%    |
| Vita                                  | 1        | 0.95%   |
| ViewSonic                             | 1        | 0.95%   |
| Unknown (XXX)                         | 1        | 0.95%   |
| Toshiba Matsushita Display Technology | 1        | 0.95%   |
| TCL                                   | 1        | 0.95%   |
| Plain Tree Systems                    | 1        | 0.95%   |
| PEGA                                  | 1        | 0.95%   |
| Parker                                | 1        | 0.95%   |
| MStar                                 | 1        | 0.95%   |
| LSC                                   | 1        | 0.95%   |
| LG Electronics                        | 1        | 0.95%   |
| IBM                                   | 1        | 0.95%   |
| CVT                                   | 1        | 0.95%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 4        | 3.67%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 4        | 3.67%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                 | 4        | 3.67%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 3        | 2.75%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch  | 2        | 1.83%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 2        | 1.83%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch      | 2        | 1.83%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 2        | 1.83%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                    | 1        | 0.92%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch         | 1        | 0.92%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch            | 1        | 0.92%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch             | 1        | 0.92%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR         | 1        | 0.92%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                     | 1        | 0.92%   |
| Sony TV SNYEB01 1360x768                                              | 1        | 0.92%   |
| Sony TV SNYEA01 1920x1080                                             | 1        | 0.92%   |
| Sony TV SNYDC01 1360x768                                              | 1        | 0.92%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch     | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch  | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM03F5 1920x1200                      | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM03F4 1920x1200 518x324mm 24.1-inch  | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1        | 0.92%   |
| Samsung Electronics SMBX2050N SAM0719 1600x900 443x249mm 20.0-inch    | 1        | 0.92%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1        | 0.92%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 0.92%   |
| Samsung Electronics SA300/SA350 SAM0849 1920x1080 477x268mm 21.5-inch | 1        | 0.92%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1        | 0.92%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch     | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM02C8 1280x720                      | 1        | 0.92%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1        | 0.92%   |
| Samsung Electronics LCD Monitor C24F390                               | 1        | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1280x1024 (SXGA)   | 25       | 23.81%  |
| 1920x1080 (FHD)    | 22       | 20.95%  |
| 1366x768 (WXGA)    | 19       | 18.1%   |
| 1440x900 (WXGA+)   | 11       | 10.48%  |
| 1600x900 (HD+)     | 8        | 7.62%   |
| 1680x1050 (WSXGA+) | 4        | 3.81%   |
| 1360x768           | 4        | 3.81%   |
| 1280x720 (HD)      | 3        | 2.86%   |
| 1024x768 (XGA)     | 3        | 2.86%   |
| 1920x1200 (WUXGA)  | 2        | 1.9%    |
| Unknown            | 2        | 1.9%    |
| 3840x2160 (4K)     | 1        | 0.95%   |
| 3840x1080          | 1        | 0.95%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 24       | 22.86%  |
| 17      | 19       | 18.1%   |
| 21      | 12       | 11.43%  |
| 19      | 10       | 9.52%   |
| 20      | 7        | 6.67%   |
| 15      | 7        | 6.67%   |
| Unknown | 7        | 6.67%   |
| 23      | 5        | 4.76%   |
| 74      | 3        | 2.86%   |
| 16      | 3        | 2.86%   |
| 72      | 2        | 1.9%    |
| 22      | 2        | 1.9%    |
| 52      | 1        | 0.95%   |
| 39      | 1        | 0.95%   |
| 24      | 1        | 0.95%   |
| 13      | 1        | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 50       | 48.08%  |
| 301-350     | 26       | 25%     |
| 351-400     | 7        | 6.73%   |
| Unknown     | 7        | 6.73%   |
| 501-600     | 6        | 5.77%   |
| 1501-2000   | 5        | 4.81%   |
| 801-900     | 1        | 0.96%   |
| 201-300     | 1        | 0.96%   |
| 1001-1500   | 1        | 0.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 49       | 48.04%  |
| 5/4     | 23       | 22.55%  |
| 16/10   | 20       | 19.61%  |
| Unknown | 5        | 4.9%    |
| 4/3     | 4        | 3.92%   |
| 3/2     | 1        | 0.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 37       | 35.24%  |
| 151-200        | 26       | 24.76%  |
| 201-250        | 15       | 14.29%  |
| 101-110        | 7        | 6.67%   |
| Unknown        | 7        | 6.67%   |
| More than 1000 | 6        | 5.71%   |
| 121-130        | 3        | 2.86%   |
| 251-300        | 1        | 0.95%   |
| 131-140        | 1        | 0.95%   |
| 501-1000       | 1        | 0.95%   |
| 91-100         | 1        | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 75       | 72.12%  |
| 101-120 | 15       | 14.42%  |
| Unknown | 7        | 6.73%   |
| 1-50    | 6        | 5.77%   |
| 121-160 | 1        | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 97       | 85.09%  |
| 2     | 8        | 7.02%   |
| 0     | 8        | 7.02%   |
| 3     | 1        | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 64       | 35.36%  |
| Qualcomm Atheros                  | 28       | 15.47%  |
| Intel                             | 26       | 14.36%  |
| Nvidia                            | 12       | 6.63%   |
| Ralink                            | 11       | 6.08%   |
| Broadcom                          | 9        | 4.97%   |
| Ralink Technology                 | 6        | 3.31%   |
| Xiaomi                            | 4        | 2.21%   |
| Qualcomm Atheros Communications   | 4        | 2.21%   |
| VIA Technologies                  | 3        | 1.66%   |
| Sundance Technology Inc / IC Plus | 2        | 1.1%    |
| Mercucys                          | 2        | 1.1%    |
| ZTE WCDMA Technologies MSM        | 1        | 0.55%   |
| Trendchip Technologies            | 1        | 0.55%   |
| Samsung Electronics               | 1        | 0.55%   |
| National Semiconductor            | 1        | 0.55%   |
| Motorola PCS                      | 1        | 0.55%   |
| Motorola BCS                      | 1        | 0.55%   |
| Marvell Technology Group          | 1        | 0.55%   |
| ICS Advent                        | 1        | 0.55%   |
| D-Link System                     | 1        | 0.55%   |
| Broadcom Limited                  | 1        | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41       | 21.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12       | 6.25%   |
| Nvidia MCP61 Ethernet                                                          | 11       | 5.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8        | 4.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 7        | 3.65%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 6        | 3.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5        | 2.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 2.08%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4        | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3        | 1.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3        | 1.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 1.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3        | 1.56%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3        | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 1.56%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 1.56%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3        | 1.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 2        | 1.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 1.04%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 1.04%   |
| Ralink MT7601U Wireless Adapter                                                | 2        | 1.04%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 2        | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 1.04%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 1.04%   |
| Intel PRO/100 VE Network Connection                                            | 2        | 1.04%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.04%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 1.04%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 2        | 1.04%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 1.04%   |
| ZTE WCDMA MSM ZXIC Mobile Boardband                                            | 1        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1        | 0.52%   |
| Trendchip Ethernet controller                                                  | 1        | 0.52%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                          | 1        | 0.52%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 1        | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 18       | 29.51%  |
| Realtek Semiconductor           | 12       | 19.67%  |
| Ralink                          | 11       | 18.03%  |
| Ralink Technology               | 6        | 9.84%   |
| Qualcomm Atheros Communications | 4        | 6.56%   |
| Intel                           | 4        | 6.56%   |
| Broadcom                        | 3        | 4.92%   |
| Mercucys                        | 2        | 3.28%   |
| D-Link System                   | 1        | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 6        | 9.84%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5        | 8.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4        | 6.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3        | 4.92%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3        | 4.92%   |
| Qualcomm Atheros AR9271 802.11n                                                | 3        | 4.92%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 4.92%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3        | 4.92%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 2        | 3.28%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 3.28%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 3.28%   |
| Ralink MT7601U Wireless Adapter                                                | 2        | 3.28%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 2        | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 3.28%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2        | 3.28%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 3.28%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 1.64%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 1.64%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 1.64%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.64%   |
| Qualcomm Atheros AR5523                                                        | 1        | 1.64%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 1        | 1.64%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 1.64%   |
| Intel Wireless 7265                                                            | 1        | 1.64%   |
| Intel Wireless 7260                                                            | 1        | 1.64%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 1.64%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 1.64%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]           | 1        | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 1        | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 57       | 44.19%  |
| Intel                             | 23       | 17.83%  |
| Qualcomm Atheros                  | 14       | 10.85%  |
| Nvidia                            | 12       | 9.3%    |
| Broadcom                          | 6        | 4.65%   |
| Xiaomi                            | 4        | 3.1%    |
| VIA Technologies                  | 3        | 2.33%   |
| Sundance Technology Inc / IC Plus | 2        | 1.55%   |
| Trendchip Technologies            | 1        | 0.78%   |
| Samsung Electronics               | 1        | 0.78%   |
| National Semiconductor            | 1        | 0.78%   |
| Motorola PCS                      | 1        | 0.78%   |
| Motorola BCS                      | 1        | 0.78%   |
| Marvell Technology Group          | 1        | 0.78%   |
| ICS Advent                        | 1        | 0.78%   |
| Broadcom Limited                  | 1        | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 41       | 31.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 12       | 9.23%   |
| Nvidia MCP61 Ethernet                                                      | 11       | 8.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 8        | 6.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 7        | 5.38%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4        | 3.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 2.31%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3        | 2.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.54%   |
| Intel PRO/100 VE Network Connection                                        | 2        | 1.54%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.54%   |
| Intel Ethernet Connection I217-LM                                          | 2        | 1.54%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 2        | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.77%   |
| Trendchip Ethernet controller                                              | 1        | 0.77%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.77%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.77%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.77%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.77%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1        | 0.77%   |
| Motorola PCS Moto G (5) Plus                                               | 1        | 0.77%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1        | 0.77%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.77%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.77%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 0.77%   |
| Intel 82567V-4 Gigabit Network Connection                                  | 1        | 0.77%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 1        | 0.77%   |
| Intel 82566DC Gigabit Network Connection                                   | 1        | 0.77%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1        | 0.77%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1        | 0.77%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 1        | 0.77%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1        | 0.77%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 112      | 65.88%  |
| WiFi     | 57       | 33.53%  |
| Modem    | 1        | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 80       | 68.38%  |
| WiFi     | 37       | 31.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 73       | 63.48%  |
| 2     | 38       | 33.04%  |
| 3     | 3        | 2.61%   |
| 0     | 1        | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 114      | 100%    |

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
| Intel                  | 87       | 56.13%  |
| Nvidia                 | 27       | 17.42%  |
| AMD                    | 23       | 14.84%  |
| VIA Technologies       | 4        | 2.58%   |
| C-Media Electronics    | 4        | 2.58%   |
| Creative Labs          | 3        | 1.94%   |
| Logitech               | 2        | 1.29%   |
| JMTek                  | 2        | 1.29%   |
| Unknown                | 1        | 0.65%   |
| Microsoft              | 1        | 0.65%   |
| Generalplus Technology | 1        | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 34       | 20.12%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 23       | 13.61%  |
| Nvidia MCP61 High Definition Audio                                          | 10       | 5.92%   |
| Nvidia GF119 HDMI Audio Controller                                          | 7        | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 6        | 3.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 5        | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 5        | 2.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 5        | 2.96%   |
| AMD FCH Azalia Controller                                                   | 5        | 2.96%   |
| Nvidia High Definition Audio Controller                                     | 4        | 2.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 4        | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 4        | 2.37%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 4        | 2.37%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 3        | 1.78%   |
| Nvidia GF106 High Definition Audio Controller                               | 3        | 1.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 3        | 1.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 3        | 1.78%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                        | 2        | 1.18%   |
| C-Media Electronics CM108 Audio Controller                                  | 2        | 1.18%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                            | 2        | 1.18%   |
| AMD RV670/680 HDMI Audio [Radeon HD 3690/3800 Series]                       | 2        | 1.18%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]         | 2        | 1.18%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.59%   |
| Unknown Audio device                                                        | 1        | 0.59%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                   | 1        | 0.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 1        | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                          | 1        | 0.59%   |
| Nvidia GK104 HDMI Audio Controller                                          | 1        | 0.59%   |
| Nvidia GF116 High Definition Audio Controller                               | 1        | 0.59%   |
| Nvidia GF114 HDMI Audio Controller                                          | 1        | 0.59%   |
| Nvidia GF104 High Definition Audio Controller                               | 1        | 0.59%   |
| Microsoft LifeChat LX-6000 Headset                                          | 1        | 0.59%   |
| Logitech V20 portable speakers (USB powered)                                | 1        | 0.59%   |
| Logitech H600 [Wireless Headset]                                            | 1        | 0.59%   |
| JMTek USB PnP Audio Device                                                  | 1        | 0.59%   |
| JMTek audio controller                                                      | 1        | 0.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                 | 1        | 0.59%   |
| Intel Cannon Lake PCH cAVS                                                  | 1        | 0.59%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 1        | 0.59%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 1        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 36       | 37.11%  |
| Kingston            | 11       | 11.34%  |
| Samsung Electronics | 9        | 9.28%   |
| Corsair             | 7        | 7.22%   |
| SK hynix            | 6        | 6.19%   |
| Ramaxel Technology  | 5        | 5.15%   |
| Crucial             | 4        | 4.12%   |
| Nanya Technology    | 3        | 3.09%   |
| Micron Technology   | 3        | 3.09%   |
| Elpida              | 2        | 2.06%   |
| Avant               | 2        | 2.06%   |
| A-DATA Technology   | 2        | 2.06%   |
| Unknown (0x0CBA)    | 1        | 1.03%   |
| Team                | 1        | 1.03%   |
| Qimonda             | 1        | 1.03%   |
| PNY                 | 1        | 1.03%   |
| OCZ                 | 1        | 1.03%   |
| Kreton              | 1        | 1.03%   |
| Unknown             | 1        | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2                         | 3        | 2.7%    |
| Unknown RAM Module 1024MB DIMM DDR2                         | 3        | 2.7%    |
| Unknown RAM Module 4GB DIMM SDRAM                           | 2        | 1.8%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 2        | 1.8%    |
| Unknown RAM Module 4GB DIMM 400MT/s                         | 2        | 1.8%    |
| Unknown RAM Module 2GB DIMM SDRAM                           | 2        | 1.8%    |
| Unknown RAM Module 2GB DIMM DDR2                            | 2        | 1.8%    |
| Unknown RAM Module 2GB DIMM 400MT/s                         | 2        | 1.8%    |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 1.8%    |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 2        | 1.8%    |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                 | 2        | 1.8%    |
| Ramaxel RAM RMR5030ME68F9F1600 4096MB DIMM DDR3 1600MT/s    | 2        | 1.8%    |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s          | 2        | 1.8%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                        | 1        | 0.9%    |
| Unknown RAM Module 512MB DIMM DDR2                          | 1        | 0.9%    |
| Unknown RAM Module 4GB DIMM 667MT/s                         | 1        | 0.9%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                        | 1        | 0.9%    |
| Unknown RAM Module 4096MB DIMM SDRAM                        | 1        | 0.9%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                | 1        | 0.9%    |
| Unknown RAM Module 4096MB DIMM                              | 1        | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                   | 1        | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                     | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                 | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR2 1639MT/s                | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                  | 1        | 0.9%    |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 0.9%    |
| Unknown RAM Module 1GB DIMM DDR 133MT/s                     | 1        | 0.9%    |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                  | 1        | 0.9%    |
| Unknown (0x0CBA) RAM JC4S8GB26C03D 8GB SODIMM DDR4 2667MT/s | 1        | 0.9%    |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s          | 1        | 0.9%    |
| SK hynix RAM HYMP564U64EP8-Y5 512MB DIMM DDR2 667MT/s       | 1        | 0.9%    |
| SK hynix RAM HYMP112U64CP8-Y5 1024MB DIMM DDR2 1639MT/s     | 1        | 0.9%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s        | 1        | 0.9%    |
| SK hynix RAM HMT325U6CFR8C-H9 2048MB DIMM DDR3 1600MT/s     | 1        | 0.9%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 1        | 0.9%    |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1        | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 31       | 39.24%  |
| DDR2    | 22       | 27.85%  |
| SDRAM   | 11       | 13.92%  |
| Unknown | 8        | 10.13%  |
| DDR     | 4        | 5.06%   |
| DDR4    | 3        | 3.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 74       | 96.1%   |
| SODIMM | 3        | 3.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 38       | 40.86%  |
| 4096  | 26       | 27.96%  |
| 1024  | 16       | 17.2%   |
| 8192  | 9        | 9.68%   |
| 16384 | 2        | 2.15%   |
| 512   | 2        | 2.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 18       | 20.69%  |
| Unknown | 16       | 18.39%  |
| 1333    | 14       | 16.09%  |
| 800     | 6        | 6.9%    |
| 667     | 5        | 5.75%   |
| 1066    | 4        | 4.6%    |
| 533     | 4        | 4.6%    |
| 400     | 4        | 4.6%    |
| 1639    | 3        | 3.45%   |
| 133     | 3        | 3.45%   |
| 2048    | 2        | 2.3%    |
| 3200    | 1        | 1.15%   |
| 3000    | 1        | 1.15%   |
| 2667    | 1        | 1.15%   |
| 2400    | 1        | 1.15%   |
| 2133    | 1        | 1.15%   |
| 1867    | 1        | 1.15%   |
| 1067    | 1        | 1.15%   |
| 1024    | 1        | 1.15%   |

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
| Samsung Galaxy A5 (MTP)                               | 2        | 11.11%  |
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
| 0     | 90       | 78.95%  |
| 1     | 23       | 20.18%  |
| 2     | 1        | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 48%     |
| Communication controller | 9        | 36%     |
| Sound                    | 2        | 8%      |
| Net/wireless             | 2        | 8%      |

