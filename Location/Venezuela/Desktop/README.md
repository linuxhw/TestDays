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

Total: 141

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 11       | 10.38%  |
| Ubuntu 18.04      | 11       | 10.38%  |
| Debian 11         | 7        | 6.6%    |
| OpenMandriva 4.3  | 6        | 5.66%   |
| OpenMandriva 4.2  | 6        | 5.66%   |
| ROSA R11          | 4        | 3.77%   |
| Xubuntu 18.04     | 3        | 2.83%   |
| Linux Mint 20     | 3        | 2.83%   |
| Linux Mint 19.3   | 3        | 2.83%   |
| KDE neon 20.04    | 3        | 2.83%   |
| Debian 10         | 3        | 2.83%   |
| Arch Rolling      | 3        | 2.83%   |
| Xubuntu 16.04     | 2        | 1.89%   |
| Ubuntu 20.10      | 2        | 1.89%   |
| ROSA R9           | 2        | 1.89%   |
| Linux Mint 20.3   | 2        | 1.89%   |
| Linux Mint 20.1   | 2        | 1.89%   |
| Kubuntu 20.04     | 2        | 1.89%   |
| Zorin 16          | 1        | 0.94%   |
| Zorin 15          | 1        | 0.94%   |
| Xubuntu 20.04     | 1        | 0.94%   |
| Ubuntu MATE 19.10 | 1        | 0.94%   |
| Ubuntu 19.10      | 1        | 0.94%   |
| Ubuntu 19.04      | 1        | 0.94%   |
| Sparky 5.12       | 1        | 0.94%   |
| Solus 4.3         | 1        | 0.94%   |
| ROSA R8           | 1        | 0.94%   |
| ROSA R11.1        | 1        | 0.94%   |
| ROSA 12.1         | 1        | 0.94%   |
| Pop!_OS 20.04     | 1        | 0.94%   |
| PCLinuxOS 2022    | 1        | 0.94%   |
| OpenMandriva 4.50 | 1        | 0.94%   |
| Manjaro 20.2.1    | 1        | 0.94%   |
| Manjaro           | 1        | 0.94%   |
| LMDE 5            | 1        | 0.94%   |
| Linux Mint 19     | 1        | 0.94%   |
| KDE neon 18.04    | 1        | 0.94%   |
| Kali 2021.4       | 1        | 0.94%   |
| Garuda Linux      | 1        | 0.94%   |
| Feren OS 20.04    | 1        | 0.94%   |
| Fedora 35         | 1        | 0.94%   |
| Fedora 34         | 1        | 0.94%   |
| Endless 3.3.19    | 1        | 0.94%   |
| Elementary 5.1.7  | 1        | 0.94%   |
| Elementary 5.1    | 1        | 0.94%   |
| Elementary 5.0    | 1        | 0.94%   |
| Debian 9          | 1        | 0.94%   |
| Debian 8          | 1        | 0.94%   |
| Arch              | 1        | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 25       | 24.27%  |
| OpenMandriva | 13       | 12.62%  |
| Debian       | 12       | 11.65%  |
| Linux Mint   | 11       | 10.68%  |
| ROSA         | 9        | 8.74%   |
| Xubuntu      | 5        | 4.85%   |
| KDE neon     | 4        | 3.88%   |
| Arch         | 4        | 3.88%   |
| Zorin        | 2        | 1.94%   |
| Manjaro      | 2        | 1.94%   |
| Kubuntu      | 2        | 1.94%   |
| Fedora       | 2        | 1.94%   |
| Elementary   | 2        | 1.94%   |
| Ubuntu MATE  | 1        | 0.97%   |
| Sparky       | 1        | 0.97%   |
| Solus        | 1        | 0.97%   |
| Pop!_OS      | 1        | 0.97%   |
| PCLinuxOS    | 1        | 0.97%   |
| LMDE         | 1        | 0.97%   |
| Kali         | 1        | 0.97%   |
| Garuda Linux | 1        | 0.97%   |
| Feren OS     | 1        | 0.97%   |
| Endless      | 1        | 0.97%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 6        | 5.36%   |
| 5.10.14-desktop-1omv4002           | 6        | 5.36%   |
| 5.4.0-42-generic                   | 4        | 3.57%   |
| 5.8.0-55-generic                   | 2        | 1.79%   |
| 5.4.0-77-generic                   | 2        | 1.79%   |
| 5.4.0-74-generic                   | 2        | 1.79%   |
| 5.4.0-54-generic                   | 2        | 1.79%   |
| 5.4.0-26-generic                   | 2        | 1.79%   |
| 5.3.0-40-generic                   | 2        | 1.79%   |
| 5.13.0-27-generic                  | 2        | 1.79%   |
| 5.10.0-8-amd64                     | 2        | 1.79%   |
| 5.10.0-14-amd64                    | 2        | 1.79%   |
| 5.10.0-11-amd64                    | 2        | 1.79%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 2        | 1.79%   |
| 4.15.0-48-generic                  | 2        | 1.79%   |
| 4.15.0-112-generic                 | 2        | 1.79%   |
| 5.9.16-1-MANJARO                   | 1        | 0.89%   |
| 5.8.11-arch1-1                     | 1        | 0.89%   |
| 5.8.10-17-tkg-bmq                  | 1        | 0.89%   |
| 5.8.0-63-generic                   | 1        | 0.89%   |
| 5.8.0-59-generic                   | 1        | 0.89%   |
| 5.8.0-44-generic                   | 1        | 0.89%   |
| 5.8.0-40-generic                   | 1        | 0.89%   |
| 5.6.0-1-amd64                      | 1        | 0.89%   |
| 5.4.0-96-generic                   | 1        | 0.89%   |
| 5.4.0-88-generic                   | 1        | 0.89%   |
| 5.4.0-7634-generic                 | 1        | 0.89%   |
| 5.4.0-72-generic                   | 1        | 0.89%   |
| 5.4.0-66-generic                   | 1        | 0.89%   |
| 5.4.0-47-generic                   | 1        | 0.89%   |
| 5.4.0-42-lowlatency                | 1        | 0.89%   |
| 5.4.0-31-generic                   | 1        | 0.89%   |
| 5.4.0-29-generic                   | 1        | 0.89%   |
| 5.4.0-113-generic                  | 1        | 0.89%   |
| 5.4.0-109-generic                  | 1        | 0.89%   |
| 5.3.0-42-generic                   | 1        | 0.89%   |
| 5.3.0-29-generic                   | 1        | 0.89%   |
| 5.3.0-26-generic                   | 1        | 0.89%   |
| 5.18.7-pclos1                      | 1        | 0.89%   |
| 5.16.14-arch1-1                    | 1        | 0.89%   |
| 5.15.6-lqx2-1-lqx                  | 1        | 0.89%   |
| 5.15.48-1-MANJARO                  | 1        | 0.89%   |
| 5.15.0-kali3-amd64                 | 1        | 0.89%   |
| 5.14.10-300.fc35.x86_64            | 1        | 0.89%   |
| 5.13.16-200.fc34.x86_64            | 1        | 0.89%   |
| 5.13.1-187.current                 | 1        | 0.89%   |
| 5.13.0-51-generic                  | 1        | 0.89%   |
| 5.13.0-39-generic                  | 1        | 0.89%   |
| 5.12.4-desktop-1omv4050            | 1        | 0.89%   |
| 5.11.0-41-generic                  | 1        | 0.89%   |
| 5.11.0-37-generic                  | 1        | 0.89%   |
| 5.11.0-051100rc4-generic           | 1        | 0.89%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 1        | 0.89%   |
| 5.10.3-zen1-1-zen                  | 1        | 0.89%   |
| 5.10.0-13-amd64                    | 1        | 0.89%   |
| 5.10.0-12-amd64                    | 1        | 0.89%   |
| 5.0.0-37-generic                   | 1        | 0.89%   |
| 5.0.0-31-generic                   | 1        | 0.89%   |
| 5.0.0-23-generic                   | 1        | 0.89%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 1        | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 21       | 19.81%  |
| 4.15.0  | 18       | 16.98%  |
| 5.10.0  | 8        | 7.55%   |
| 5.8.0   | 6        | 5.66%   |
| 5.16.7  | 6        | 5.66%   |
| 5.10.14 | 6        | 5.66%   |
| 5.3.0   | 5        | 4.72%   |
| 5.13.0  | 4        | 3.77%   |
| 5.11.0  | 3        | 2.83%   |
| 5.0.0   | 3        | 2.83%   |
| 4.19.0  | 3        | 2.83%   |
| 4.9.20  | 2        | 1.89%   |
| 4.9.0   | 2        | 1.89%   |
| 5.9.16  | 1        | 0.94%   |
| 5.8.11  | 1        | 0.94%   |
| 5.8.10  | 1        | 0.94%   |
| 5.6.0   | 1        | 0.94%   |
| 5.18.7  | 1        | 0.94%   |
| 5.16.14 | 1        | 0.94%   |
| 5.15.6  | 1        | 0.94%   |
| 5.15.48 | 1        | 0.94%   |
| 5.15.0  | 1        | 0.94%   |
| 5.14.10 | 1        | 0.94%   |
| 5.13.16 | 1        | 0.94%   |
| 5.13.1  | 1        | 0.94%   |
| 5.12.4  | 1        | 0.94%   |
| 5.10.74 | 1        | 0.94%   |
| 5.10.3  | 1        | 0.94%   |
| 4.4.0   | 1        | 0.94%   |
| 4.18.0  | 1        | 0.94%   |
| 4.13.0  | 1        | 0.94%   |
| 4.1.15  | 1        | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 21       | 19.81%  |
| 4.15    | 18       | 16.98%  |
| 5.10    | 16       | 15.09%  |
| 5.8     | 8        | 7.55%   |
| 5.16    | 7        | 6.6%    |
| 5.13    | 6        | 5.66%   |
| 5.3     | 5        | 4.72%   |
| 4.9     | 4        | 3.77%   |
| 5.15    | 3        | 2.83%   |
| 5.11    | 3        | 2.83%   |
| 5.0     | 3        | 2.83%   |
| 4.19    | 3        | 2.83%   |
| 5.9     | 1        | 0.94%   |
| 5.6     | 1        | 0.94%   |
| 5.18    | 1        | 0.94%   |
| 5.14    | 1        | 0.94%   |
| 5.12    | 1        | 0.94%   |
| 4.4     | 1        | 0.94%   |
| 4.18    | 1        | 0.94%   |
| 4.13    | 1        | 0.94%   |
| 4.1     | 1        | 0.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 88       | 86.27%  |
| i686   | 14       | 13.73%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 28       | 26.42%  |
| GNOME           | 24       | 22.64%  |
| Unknown         | 14       | 13.21%  |
| XFCE            | 11       | 10.38%  |
| MATE            | 5        | 4.72%   |
| KDE             | 5        | 4.72%   |
| X-Cinnamon      | 4        | 3.77%   |
| KDE4            | 4        | 3.77%   |
| LXDE            | 3        | 2.83%   |
| Cinnamon        | 2        | 1.89%   |
| xmonad          | 1        | 0.94%   |
| Unity           | 1        | 0.94%   |
| Pantheon        | 1        | 0.94%   |
| LXQt            | 1        | 0.94%   |
| GNOME Flashback | 1        | 0.94%   |
| Budgie          | 1        | 0.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 90       | 89.11%  |
| Wayland | 6        | 5.94%   |
| Unknown | 4        | 3.96%   |
| Tty     | 1        | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 47       | 45.63%  |
| SDDM    | 27       | 26.21%  |
| LightDM | 9        | 8.74%   |
| GDM     | 8        | 7.77%   |
| TDM     | 6        | 5.83%   |
| KDM     | 4        | 3.88%   |
| SLiM    | 1        | 0.97%   |
| GDM3    | 1        | 0.97%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_VE   | 58       | 56.86%  |
| en_US   | 19       | 18.63%  |
| Unknown | 17       | 16.67%  |
| es_ES   | 3        | 2.94%   |
| es_US   | 2        | 1.96%   |
| C       | 2        | 1.96%   |
| de_DE   | 1        | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 89       | 89%     |
| EFI  | 11       | 11%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 78       | 76.47%  |
| Overlay | 13       | 12.75%  |
| Unknown | 5        | 4.9%    |
| Btrfs   | 4        | 3.92%   |
| Xfs     | 1        | 0.98%   |
| Ext2    | 1        | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 51.49%  |
| MBR     | 35       | 34.65%  |
| GPT     | 14       | 13.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 80.2%   |
| Yes       | 20       | 19.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 55.45%  |
| Yes       | 45       | 44.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 17       | 17%     |
| ECS                 | 11       | 11%     |
| Pegatron            | 10       | 10%     |
| Intel               | 10       | 10%     |
| Lenovo              | 9        | 9%      |
| ASUSTek Computer    | 7        | 7%      |
| Biostar             | 6        | 6%      |
| Gigabyte Technology | 5        | 5%      |
| Dell                | 5        | 5%      |
| MSI                 | 4        | 4%      |
| langchao            | 4        | 4%      |
| Hewlett-Packard     | 4        | 4%      |
| Foxconn             | 4        | 4%      |
| IP3 Tech            | 1        | 1%      |
| Inspur              | 1        | 1%      |
| IBM                 | 1        | 1%      |
| Unknown             | 1        | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ECS H61H2-CM                         | 6        | 6%      |
| langchao 12345                       | 4        | 4%      |
| ASRock G41M-VS3                      | 4        | 4%      |
| Pegatron Compaq dx2400 Microtower    | 2        | 2%      |
| ASRock N68C-S UCC                    | 2        | 2%      |
| Pegatron PEGATRON                    | 1        | 1%      |
| Pegatron IPPEL-DB                    | 1        | 1%      |
| Pegatron IPM41-D3                    | 1        | 1%      |
| Pegatron CQ1507LA                    | 1        | 1%      |
| Pegatron Compaq dx2400 Microtower PC | 1        | 1%      |
| Pegatron BM411AA-ABA CQ5600F         | 1        | 1%      |
| Pegatron 20-b010                     | 1        | 1%      |
| Pegatron 100-5010la                  | 1        | 1%      |
| MSI Pro 3000 Microtower PC           | 1        | 1%      |
| MSI MS-7817                          | 1        | 1%      |
| MSI MS-7721                          | 1        | 1%      |
| MSI MS-7375                          | 1        | 1%      |
| Lenovo ThinkCentre XXXX 8705A84      | 1        | 1%      |
| Lenovo ThinkCentre M71e 3157G6S      | 1        | 1%      |
| Lenovo ThinkCentre M55E 9645BN2      | 1        | 1%      |
| Lenovo ThinkCentre M55E 9632BU8      | 1        | 1%      |
| Lenovo ThinkCentre A58 7515A33       | 1        | 1%      |
| Lenovo ThinkCentre A55 8705AV4       | 1        | 1%      |
| Lenovo H220 10028                    | 1        | 1%      |
| Lenovo 70A4000HUX ThinkServer TS140  | 1        | 1%      |
| Lenovo 11051CS ThinkServer TS130     | 1        | 1%      |
| IP3 Tech TB20                        | 1        | 1%      |
| Intel MAHOBAY                        | 1        | 1%      |
| Intel H61                            | 1        | 1%      |
| Intel DH77EB AAG39073-304            | 1        | 1%      |
| Intel DG41TY AAE47335-203            | 1        | 1%      |
| Intel DG41TX AAE78178-303            | 1        | 1%      |
| Intel DG35EC AAE29266-205            | 1        | 1%      |
| Intel DG33BU AAD79951-407            | 1        | 1%      |
| Intel DG31PR AAD97573-302            | 1        | 1%      |
| Intel D946GZIS AAD66165-302          | 1        | 1%      |
| Intel D945GCCR AAD78647-300          | 1        | 1%      |
| Inspur                               | 1        | 1%      |
| IBM 8188LS4                          | 1        | 1%      |
| HP Compaq Elite 8300 USDT            | 1        | 1%      |
| HP Compaq Elite 8300 SFF             | 1        | 1%      |
| HP Compaq 8200 Elite SFF PC          | 1        | 1%      |
| HP Compaq 4000 Pro SFF PC            | 1        | 1%      |
| Gigabyte Z97N-WIFI                   | 1        | 1%      |
| Gigabyte Z68X-UD3H-B3                | 1        | 1%      |
| Gigabyte H110M-H                     | 1        | 1%      |
| Gigabyte G1.Sniper B5                | 1        | 1%      |
| Gigabyte 970A-DS3P                   | 1        | 1%      |
| Foxconn MCP61M05                     | 1        | 1%      |
| Foxconn M61PMV                       | 1        | 1%      |
| Foxconn ELA01                        | 1        | 1%      |
| Foxconn 8657MF-series                | 1        | 1%      |
| ECS RZ452AA-ABM SR5003LS             | 1        | 1%      |
| ECS KAM1-I                           | 1        | 1%      |
| ECS H61H2-MV                         | 1        | 1%      |
| ECS H61H2-M12                        | 1        | 1%      |
| ECS G31T-M7                          | 1        | 1%      |
| Dell Vostro 260                      | 1        | 1%      |
| Dell Vostro 200                      | 1        | 1%      |
| Dell Precision T3600                 | 1        | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Lenovo ThinkCentre    | 6        | 6%      |
| ECS H61H2-CM          | 6        | 6%      |
| langchao 12345        | 4        | 4%      |
| HP Compaq             | 4        | 4%      |
| ASRock G41M-VS3       | 4        | 4%      |
| Pegatron Compaq       | 3        | 3%      |
| Dell Vostro           | 2        | 2%      |
| Dell OptiPlex         | 2        | 2%      |
| ASRock N68C-S         | 2        | 2%      |
| Pegatron PEGATRON     | 1        | 1%      |
| Pegatron IPPEL-DB     | 1        | 1%      |
| Pegatron IPM41-D3     | 1        | 1%      |
| Pegatron CQ1507LA     | 1        | 1%      |
| Pegatron BM411AA-ABA  | 1        | 1%      |
| Pegatron 20-b010      | 1        | 1%      |
| Pegatron 100-5010la   | 1        | 1%      |
| MSI Pro               | 1        | 1%      |
| MSI MS-7817           | 1        | 1%      |
| MSI MS-7721           | 1        | 1%      |
| MSI MS-7375           | 1        | 1%      |
| Lenovo H220           | 1        | 1%      |
| Lenovo 70A4000HUX     | 1        | 1%      |
| Lenovo 11051CS        | 1        | 1%      |
| IP3 Tech TB20         | 1        | 1%      |
| Intel MAHOBAY         | 1        | 1%      |
| Intel H61             | 1        | 1%      |
| Intel DH77EB          | 1        | 1%      |
| Intel DG41TY          | 1        | 1%      |
| Intel DG41TX          | 1        | 1%      |
| Intel DG35EC          | 1        | 1%      |
| Intel DG33BU          | 1        | 1%      |
| Intel DG31PR          | 1        | 1%      |
| Intel D946GZIS        | 1        | 1%      |
| Intel D945GCCR        | 1        | 1%      |
| Inspur                | 1        | 1%      |
| IBM 8188LS4           | 1        | 1%      |
| Gigabyte Z97N-WIFI    | 1        | 1%      |
| Gigabyte Z68X-UD3H-B3 | 1        | 1%      |
| Gigabyte H110M-H      | 1        | 1%      |
| Gigabyte G1.Sniper    | 1        | 1%      |
| Gigabyte 970A-DS3P    | 1        | 1%      |
| Foxconn MCP61M05      | 1        | 1%      |
| Foxconn M61PMV        | 1        | 1%      |
| Foxconn ELA01         | 1        | 1%      |
| Foxconn 8657MF-series | 1        | 1%      |
| ECS RZ452AA-ABM       | 1        | 1%      |
| ECS KAM1-I            | 1        | 1%      |
| ECS H61H2-MV          | 1        | 1%      |
| ECS H61H2-M12         | 1        | 1%      |
| ECS G31T-M7           | 1        | 1%      |
| Dell Precision        | 1        | 1%      |
| Biostar P4M900-M7     | 1        | 1%      |
| Biostar P4M90-M7A     | 1        | 1%      |
| Biostar N68S3B        | 1        | 1%      |
| Biostar G41D3C        | 1        | 1%      |
| Biostar G41D3         | 1        | 1%      |
| Biostar A55MLC2       | 1        | 1%      |
| ASUS Rampage          | 1        | 1%      |
| ASUS P8H61-M          | 1        | 1%      |
| ASUS P6X58-E          | 1        | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 23       | 23%     |
| 2011 | 22       | 22%     |
| 2008 | 13       | 13%     |
| 2007 | 10       | 10%     |
| 2012 | 9        | 9%      |
| 2006 | 6        | 6%      |
| 2014 | 4        | 4%      |
| 2013 | 3        | 3%      |
| 2017 | 2        | 2%      |
| 2009 | 2        | 2%      |
| 2021 | 1        | 1%      |
| 2020 | 1        | 1%      |
| 2019 | 1        | 1%      |
| 2016 | 1        | 1%      |
| 2015 | 1        | 1%      |
| 2005 | 1        | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 100      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 100      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 100      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 29       | 28.16%  |
| 4.01-8.0   | 23       | 22.33%  |
| 1.01-2.0   | 18       | 17.48%  |
| 8.01-16.0  | 14       | 13.59%  |
| 16.01-24.0 | 9        | 8.74%   |
| 2.01-3.0   | 4        | 3.88%   |
| 24.01-32.0 | 3        | 2.91%   |
| 0.51-1.0   | 2        | 1.94%   |
| 32.01-64.0 | 1        | 0.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 43       | 39.09%  |
| 2.01-3.0 | 28       | 25.45%  |
| 0.51-1.0 | 17       | 15.45%  |
| 4.01-8.0 | 11       | 10%     |
| 3.01-4.0 | 7        | 6.36%   |
| 0.01-0.5 | 4        | 3.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 59.62%  |
| 2      | 32       | 30.77%  |
| 3      | 8        | 7.69%   |
| 4      | 2        | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 53.85%  |
| Yes       | 48       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 99       | 99%     |
| No        | 1        | 1%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 51.49%  |
| Yes       | 49       | 48.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 88.12%  |
| Yes       | 12       | 11.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Venezuela | 100      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Caracas                  | 53       | 49.07%  |
| Maracay                  | 6        | 5.56%   |
| San Cristóbal           | 5        | 4.63%   |
| Maracaibo                | 4        | 3.7%    |
| Valencia                 | 3        | 2.78%   |
| San Carlos del Zulia     | 3        | 2.78%   |
| Maturín                 | 3        | 2.78%   |
| Carrizal                 | 3        | 2.78%   |
| Barquisimeto             | 3        | 2.78%   |
| San Antonio de Los Altos | 2        | 1.85%   |
| Mérida                  | 2        | 1.85%   |
| Los Teques               | 2        | 1.85%   |
| Ciudad Bolívar          | 2        | 1.85%   |
| Barinas                  | 2        | 1.85%   |
| Barcelona                | 2        | 1.85%   |
| Valle de La Pascua       | 1        | 0.93%   |
| San Juan Bautista        | 1        | 0.93%   |
| San Francisco            | 1        | 0.93%   |
| Parroquia El Recreo      | 1        | 0.93%   |
| Los Palos Grandes        | 1        | 0.93%   |
| Lecherias                | 1        | 0.93%   |
| Guatire                  | 1        | 0.93%   |
| Guarenas                 | 1        | 0.93%   |
| Ciudad Guayana           | 1        | 0.93%   |
| Carora                   | 1        | 0.93%   |
| Cabimas                  | 1        | 0.93%   |
| Baruta                   | 1        | 0.93%   |
| Acarigua                 | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 44       | 59     | 31.88%  |
| Seagate             | 32       | 45     | 23.19%  |
| Hitachi             | 19       | 23     | 13.77%  |
| Samsung Electronics | 12       | 15     | 8.7%    |
| Toshiba             | 9        | 10     | 6.52%   |
| Kingston            | 7        | 7      | 5.07%   |
| Maxtor              | 4        | 4      | 2.9%    |
| PNY                 | 2        | 2      | 1.45%   |
| Patriot             | 2        | 2      | 1.45%   |
| Unknown             | 1        | 1      | 0.72%   |
| Team                | 1        | 1      | 0.72%   |
| SPCC                | 1        | 1      | 0.72%   |
| HGST                | 1        | 1      | 0.72%   |
| Fujitsu             | 1        | 1      | 0.72%   |
| ExcelStor           | 1        | 1      | 0.72%   |
| Dogfish             | 1        | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST320LT012-1DG14C 320GB  | 7        | 4.49%   |
| Toshiba DT01ACA050 500GB         | 5        | 3.21%   |
| Seagate ST3320418AS 320GB        | 4        | 2.56%   |
| WDC WD5000AAKS-00A7B0 500GB      | 3        | 1.92%   |
| WDC WD3200AAJS-08L7A0 320GB      | 3        | 1.92%   |
| WDC WD3200AAJS-00L7A0 320GB      | 3        | 1.92%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.92%   |
| Samsung HD502HJ 500GB            | 3        | 1.92%   |
| Samsung HD161HJ 160GB            | 3        | 1.92%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.92%   |
| Hitachi HTS542580K9SA00 80GB     | 3        | 1.92%   |
| WDC WD800BD-22MRA1 80GB          | 2        | 1.28%   |
| WDC WD800BB-22JHC0 80GB          | 2        | 1.28%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2        | 1.28%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 1.28%   |
| WDC WD5000AAKX-221CA1 500GB      | 2        | 1.28%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 1.28%   |
| WDC WD5000AAKS-00UU3A0 500GB     | 2        | 1.28%   |
| WDC WD2500AAJS-60B4A0 250GB      | 2        | 1.28%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 2        | 1.28%   |
| Seagate ST3250310AS 250GB        | 2        | 1.28%   |
| Seagate ST320LM000 HM321HI 320GB | 2        | 1.28%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 1.28%   |
| Hitachi HDS721616PLA380 160GB    | 2        | 1.28%   |
| Hitachi HDS721032CLA362 320GB    | 2        | 1.28%   |
| WDC WD800JD-60LSA5 80GB          | 1        | 0.64%   |
| WDC WD800BD-08MRA1 80GB          | 1        | 0.64%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 0.64%   |
| WDC WD5000AAKX-753CA1 500GB      | 1        | 0.64%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1        | 0.64%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.64%   |
| WDC WD5000AAJS-08A8B0 500GB      | 1        | 0.64%   |
| WDC WD5000AACS-61M6B2 500GB      | 1        | 0.64%   |
| WDC WD5000AACS-00ZUB0 500GB      | 1        | 0.64%   |
| WDC WD3200BEKT-22F3T0 320GB      | 1        | 0.64%   |
| WDC WD3200AAJS-65M0A0 320GB      | 1        | 0.64%   |
| WDC WD3200AAJS-55B4A0 320GB      | 1        | 0.64%   |
| WDC WD2500BEVS-60UST0 250GB      | 1        | 0.64%   |
| WDC WD2500AAJS-08L7A0 250GB      | 1        | 0.64%   |
| WDC WD20PURX-64P6ZY0 2TB         | 1        | 0.64%   |
| WDC WD2003FYPS-27Y2B0 2TB        | 1        | 0.64%   |
| WDC WD1600JS-00NCB1 160GB        | 1        | 0.64%   |
| WDC WD1600AAJS-75B4A0 160GB      | 1        | 0.64%   |
| WDC WD1600AAJS-08WAA0 160GB      | 1        | 0.64%   |
| WDC WD1600AAJS-07M0A0 160GB      | 1        | 0.64%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 0.64%   |
| WDC WD10EZEX-22RKKA0 1TB         | 1        | 0.64%   |
| WDC WD10EZEX-21M2NA0 1TB         | 1        | 0.64%   |
| WDC WD10EZEX-00RKKA0 1TB         | 1        | 0.64%   |
| WDC WD10EARX-00N0YB0 1TB         | 1        | 0.64%   |
| WDC WD10EALX-009BA0 1TB          | 1        | 0.64%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 1        | 0.64%   |
| Unknown NVMe SSD Drive 256GB     | 1        | 0.64%   |
| Toshiba MK8034GSX 80GB           | 1        | 0.64%   |
| Toshiba MK3263GSX 320GB          | 1        | 0.64%   |
| Toshiba MK2565GSX 250GB          | 1        | 0.64%   |
| Toshiba HDWD110 1TB              | 1        | 0.64%   |
| Team T253X1240G 240GB SSD        | 1        | 0.64%   |
| SPCC Solid State Disk 128GB      | 1        | 0.64%   |
| Seagate ST9160314AS 160GB        | 1        | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 44       | 59     | 35.77%  |
| Seagate             | 32       | 45     | 26.02%  |
| Hitachi             | 19       | 23     | 15.45%  |
| Samsung Electronics | 12       | 15     | 9.76%   |
| Toshiba             | 9        | 10     | 7.32%   |
| Maxtor              | 4        | 4      | 3.25%   |
| HGST                | 1        | 1      | 0.81%   |
| Fujitsu             | 1        | 1      | 0.81%   |
| ExcelStor           | 1        | 1      | 0.81%   |

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
| HDD  | 89       | 159    | 86.41%  |
| SSD  | 13       | 14     | 12.62%  |
| NVMe | 1        | 1      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 99       | 173    | 99%     |
| NVMe | 1        | 1      | 1%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 95       | 152    | 82.61%  |
| 0.51-1.0   | 11       | 11     | 9.57%   |
| 1.01-2.0   | 5        | 5      | 4.35%   |
| 3.01-4.0   | 2        | 2      | 1.74%   |
| 2.01-3.0   | 2        | 3      | 1.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 34       | 31.48%  |
| 101-250        | 27       | 25%     |
| 501-1000       | 13       | 12.04%  |
| 51-100         | 12       | 11.11%  |
| 1-20           | 11       | 10.19%  |
| 2001-3000      | 3        | 2.78%   |
| 1001-2000      | 3        | 2.78%   |
| 21-50          | 2        | 1.85%   |
| Unknown        | 2        | 1.85%   |
| More than 3000 | 1        | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 49       | 45.79%  |
| 21-50          | 15       | 14.02%  |
| 101-250        | 14       | 13.08%  |
| 251-500        | 10       | 9.35%   |
| 51-100         | 9        | 8.41%   |
| 501-1000       | 4        | 3.74%   |
| 2001-3000      | 2        | 1.87%   |
| Unknown        | 2        | 1.87%   |
| More than 3000 | 1        | 0.93%   |
| 1001-2000      | 1        | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB         | 3        | 3      | 7.14%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 2        | 3      | 4.76%   |
| WDC WD5000AAKS-00A7B0 500GB             | 2        | 2      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB         | 2        | 2      | 4.76%   |
| Hitachi HDS721616PLA380 160GB           | 2        | 2      | 4.76%   |
| WDC WD800BD-08MRA1 80GB                 | 1        | 1      | 2.38%   |
| WDC WD800BB-22JHC0 80GB                 | 1        | 1      | 2.38%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1        | 1      | 2.38%   |
| WDC WD5000AAKX-221CA1 500GB             | 1        | 1      | 2.38%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 1        | 1      | 2.38%   |
| WDC WD5000AACS-00ZUB0 500GB             | 1        | 1      | 2.38%   |
| WDC WD3200BEKT-22F3T0 320GB             | 1        | 1      | 2.38%   |
| WDC WD3200AAJS-08L7A0 320GB             | 1        | 2      | 2.38%   |
| WDC WD2003FYPS-27Y2B0 2TB               | 1        | 1      | 2.38%   |
| WDC WD10EZEX-22RKKA0 1TB                | 1        | 1      | 2.38%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1        | 1      | 2.38%   |
| Toshiba DT01ACA050 500GB                | 1        | 2      | 2.38%   |
| Seagate ST3500630AS 500GB               | 1        | 1      | 2.38%   |
| Seagate ST3500418AS 500GB               | 1        | 1      | 2.38%   |
| Seagate ST3500413AS 500GB               | 1        | 1      | 2.38%   |
| Seagate ST340014AS 40GB                 | 1        | 1      | 2.38%   |
| Seagate ST3320418AS 320GB               | 1        | 2      | 2.38%   |
| Seagate ST3250318AS 250GB               | 1        | 1      | 2.38%   |
| Seagate ST3250310AS 250GB               | 1        | 1      | 2.38%   |
| Seagate ST3160215ACE 160GB              | 1        | 1      | 2.38%   |
| Seagate ST3160212SCE 160GB              | 1        | 1      | 2.38%   |
| Samsung Electronics HM321HI 320GB       | 1        | 1      | 2.38%   |
| Samsung Electronics HD161HJ 160GB       | 1        | 2      | 2.38%   |
| Samsung Electronics HD155UI 1TB         | 1        | 1      | 2.38%   |
| Maxtor STM3250310AS 250GB               | 1        | 1      | 2.38%   |
| Maxtor STM3160215AS 160GB               | 1        | 1      | 2.38%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB | 1        | 1      | 2.38%   |
| Hitachi HDS721050DLE630 500GB           | 1        | 1      | 2.38%   |
| Hitachi HDS721032CLA362 320GB           | 1        | 1      | 2.38%   |
| Hitachi HDP725025GLA380 250GB           | 1        | 1      | 2.38%   |
| ExcelStor Technology J880S 82GB         | 1        | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 15     | 36.11%  |
| WDC                 | 10       | 17     | 27.78%  |
| Hitachi             | 6        | 6      | 16.67%  |
| Samsung Electronics | 3        | 4      | 8.33%   |
| Maxtor              | 2        | 2      | 5.56%   |
| Toshiba             | 1        | 2      | 2.78%   |
| ExcelStor           | 1        | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 15     | 36.11%  |
| WDC                 | 10       | 17     | 27.78%  |
| Hitachi             | 6        | 6      | 16.67%  |
| Samsung Electronics | 3        | 4      | 8.33%   |
| Maxtor              | 2        | 2      | 5.56%   |
| Toshiba             | 1        | 2      | 2.78%   |
| ExcelStor           | 1        | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 47     | 100%    |

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
| Detected | 53       | 87     | 47.75%  |
| Malfunc  | 28       | 47     | 25.23%  |
| Works    | 28       | 38     | 25.23%  |
| Failed   | 2        | 2      | 1.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 78       | 69.03%  |
| Nvidia                   | 10       | 8.85%   |
| AMD                      | 9        | 7.96%   |
| Marvell Technology Group | 5        | 4.42%   |
| JMicron Technology       | 5        | 4.42%   |
| VIA Technologies         | 3        | 2.65%   |
| ASMedia Technology       | 1        | 0.88%   |
| Adaptec                  | 1        | 0.88%   |
| Unknown                  | 1        | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 29       | 16.57%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 12%     |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11       | 6.29%   |
| Nvidia MCP61 SATA Controller                                                            | 9        | 5.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 5.14%   |
| Nvidia MCP61 IDE                                                                        | 8        | 4.57%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 2.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 2.86%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 2.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 2.29%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 2.29%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 1.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.71%   |
| VIA Serial ATA Controller                                                               | 2        | 1.14%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.14%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 1.14%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 1.14%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1.14%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2        | 1.14%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.14%   |
| AMD FCH IDE Controller                                                                  | 2        | 1.14%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 1        | 0.57%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 0.57%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.57%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.57%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.57%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.57%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.57%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.57%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.57%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1        | 0.57%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.57%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.57%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.57%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1        | 0.57%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 1        | 0.57%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 0.57%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.57%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 1        | 0.57%   |
| Unknown                                                                                 | 1        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 70       | 63.64%  |
| SATA | 34       | 30.91%  |
| RAID | 3        | 2.73%   |
| SAS  | 1        | 0.91%   |
| SCSI | 1        | 0.91%   |
| NVMe | 1        | 0.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 81       | 81%     |
| AMD    | 19       | 19%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6        | 6%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 5%      |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 3        | 3%      |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 3%      |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 3%      |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 3%      |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 3%      |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 2%      |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 2        | 2%      |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2        | 2%      |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 2%      |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 2%      |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2%      |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 2%      |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 2%      |
| AMD Sempron 145 Processor                   | 2        | 2%      |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 1%      |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1%      |
| Intel Xeon CPU E5-1607 0 @ 3.00GHz          | 1        | 1%      |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1        | 1%      |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1%      |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1%      |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 1%      |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 1%      |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1%      |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1%      |
| Intel Pentium CPU E5800 @ 3.20GHz           | 1        | 1%      |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 1%      |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1%      |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1%      |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 1%      |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 1%      |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1%      |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1%      |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1%      |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1%      |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 1%      |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1%      |
| Intel Core i3-8100T CPU @ 3.10GHz           | 1        | 1%      |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1%      |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 1%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E8200 @ 2.66GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1%      |
| Intel Core 2 Duo CPU E4400 @ 2.00GHz        | 1        | 1%      |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 1        | 1%      |
| Intel Core 2 CPU 4400 @ 2.00GHz             | 1        | 1%      |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1        | 1%      |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1%      |
| Intel Celeron CPU 430 @ 1.80GHz             | 1        | 1%      |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1        | 1%      |
| AMD Sempron Processor 3000+                 | 1        | 1%      |
| AMD Sempron 2650 APU with Radeon R3         | 1        | 1%      |
| AMD Sempron 140 Processor                   | 1        | 1%      |
| AMD Phenom 9950 Quad-Core Processor         | 1        | 1%      |
| AMD Phenom 8450 Triple-Core Processor       | 1        | 1%      |
| AMD FX-6300 Six-Core Processor              | 1        | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium Dual-Core | 19       | 19%     |
| Intel Core i5           | 10       | 10%     |
| Intel Core i3           | 8        | 8%      |
| Intel Pentium           | 7        | 7%      |
| Intel Core 2 Duo        | 7        | 7%      |
| Intel Core i7           | 6        | 6%      |
| AMD Sempron             | 5        | 5%      |
| Intel Xeon              | 4        | 4%      |
| Intel Pentium Dual      | 4        | 4%      |
| Intel Pentium 4         | 4        | 4%      |
| Intel Core 2 Quad       | 4        | 4%      |
| Intel Core 2            | 3        | 3%      |
| Intel Celeron           | 2        | 2%      |
| AMD Phenom              | 2        | 2%      |
| AMD FX                  | 2        | 2%      |
| AMD Athlon              | 2        | 2%      |
| Other                   | 1        | 1%      |
| Intel Pentium D         | 1        | 1%      |
| Intel Atom              | 1        | 1%      |
| AMD E1                  | 1        | 1%      |
| AMD Athlon II X4        | 1        | 1%      |
| AMD Athlon II X2        | 1        | 1%      |
| AMD Athlon II           | 1        | 1%      |
| AMD Athlon 64 X2        | 1        | 1%      |
| AMD A8                  | 1        | 1%      |
| AMD A6                  | 1        | 1%      |
| AMD A4                  | 1        | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 55       | 55%     |
| 4       | 29       | 29%     |
| 1       | 11       | 11%     |
| 3       | 3        | 3%      |
| Unknown | 2        | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 100      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 75       | 75%     |
| 2       | 23       | 23%     |
| Unknown | 2        | 2%      |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 96       | 96%     |
| 64-bit         | 2        | 2%      |
| 32-bit         | 1        | 1%      |
| Unknown        | 1        | 1%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 24       | 24%     |
| 0x206a7    | 12       | 12%     |
| Unknown    | 11       | 11%     |
| 0x306a9    | 7        | 7%      |
| 0x306c3    | 5        | 5%      |
| 0x6fd      | 4        | 4%      |
| 0x6fb      | 4        | 4%      |
| 0xf65      | 3        | 3%      |
| 0x6f2      | 3        | 3%      |
| 0x010000c8 | 3        | 3%      |
| 0x106a5    | 2        | 2%      |
| 0x10676    | 2        | 2%      |
| 0x010000c7 | 2        | 2%      |
| 0xf47      | 1        | 1%      |
| 0xf41      | 1        | 1%      |
| 0x906eb    | 1        | 1%      |
| 0x906e9    | 1        | 1%      |
| 0x806c1    | 1        | 1%      |
| 0x206d7    | 1        | 1%      |
| 0x106ca    | 1        | 1%      |
| 0x10661    | 1        | 1%      |
| 0x0810100b | 1        | 1%      |
| 0x0700010b | 1        | 1%      |
| 0x06001119 | 1        | 1%      |
| 0x06000852 | 1        | 1%      |
| 0x0600063e | 1        | 1%      |
| 0x05000119 | 1        | 1%      |
| 0x03000027 | 1        | 1%      |
| 0x03000014 | 1        | 1%      |
| 0x01000095 | 1        | 1%      |
| 0x01000065 | 1        | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 28       | 28%     |
| SandyBridge | 14       | 14%     |
| Core        | 13       | 13%     |
| IvyBridge   | 9        | 9%      |
| K10         | 8        | 8%      |
| Haswell     | 6        | 6%      |
| NetBurst    | 5        | 5%      |
| K8 Hammer   | 3        | 3%      |
| Piledriver  | 2        | 2%      |
| Nehalem     | 2        | 2%      |
| KabyLake    | 2        | 2%      |
| K10 Llano   | 2        | 2%      |
| Zen         | 1        | 1%      |
| TigerLake   | 1        | 1%      |
| Jaguar      | 1        | 1%      |
| Bulldozer   | 1        | 1%      |
| Bonnell     | 1        | 1%      |
| Bobcat      | 1        | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 59       | 55.66%  |
| Nvidia           | 26       | 24.53%  |
| AMD              | 18       | 16.98%  |
| VIA Technologies | 3        | 2.83%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 13       | 12.26%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 10.38%  |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7        | 6.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.72%   |
| Nvidia GF119 [GeForce GT 520]                                               | 4        | 3.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 3.77%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 4        | 3.77%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 3.77%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 3        | 2.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.83%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.89%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.89%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 1.89%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 2        | 1.89%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 1.89%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.89%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.89%   |
| Intel 82865G Integrated Graphics Controller                                 | 2        | 1.89%   |
| AMD RV670 [Radeon HD 3870]                                                  | 2        | 1.89%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.94%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.94%   |
| Nvidia GK104GL [Quadro K4200]                                               | 1        | 0.94%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 0.94%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.94%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.94%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.94%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 0.94%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 0.94%   |
| Intel Xeon E3-1200 Processor Family Integrated Graphics Controller          | 1        | 0.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1        | 0.94%   |
| Intel HD Graphics 630                                                       | 1        | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 0.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 0.94%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 0.94%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 0.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 0.94%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 0.94%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 0.94%   |
| AMD SuperSumo [Radeon HD 6410D]                                             | 1        | 0.94%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 1        | 0.94%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 0.94%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 0.94%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                   | 1        | 0.94%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 0.94%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 0.94%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 0.94%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Intel    | 55       | 54.46%  |
| 1 x Nvidia   | 25       | 24.75%  |
| 1 x AMD      | 16       | 15.84%  |
| 1 x VIA      | 3        | 2.97%   |
| Intel + AMD  | 1        | 0.99%   |
| AMD + Nvidia | 1        | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 81       | 81%     |
| Proprietary | 10       | 10%     |
| Unknown     | 9        | 9%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 49.51%  |
| 0.51-1.0   | 19       | 18.45%  |
| 0.01-0.5   | 18       | 17.48%  |
| 1.01-2.0   | 12       | 11.65%  |
| 3.01-4.0   | 3        | 2.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung Electronics                   | 26       | 27.96%  |
| Hewlett-Packard                       | 12       | 12.9%   |
| Goldstar                              | 11       | 11.83%  |
| Lenovo                                | 8        | 8.6%    |
| Toshiba                               | 5        | 5.38%   |
| Dell                                  | 5        | 5.38%   |
| AOC                                   | 4        | 4.3%    |
| BenQ                                  | 3        | 3.23%   |
| Acer                                  | 3        | 3.23%   |
| Sony                                  | 2        | 2.15%   |
| Envision                              | 2        | 2.15%   |
| Vita                                  | 1        | 1.08%   |
| ViewSonic                             | 1        | 1.08%   |
| Unknown (XXX)                         | 1        | 1.08%   |
| Toshiba Matsushita Display Technology | 1        | 1.08%   |
| TCL                                   | 1        | 1.08%   |
| PEGA                                  | 1        | 1.08%   |
| Parker                                | 1        | 1.08%   |
| MStar                                 | 1        | 1.08%   |
| LSC                                   | 1        | 1.08%   |
| LG Electronics                        | 1        | 1.08%   |
| IBM                                   | 1        | 1.08%   |
| CVT                                   | 1        | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 4        | 4.21%   |
| Toshiba TV TSB0206 1920x1080                                         | 3        | 3.16%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 3        | 3.16%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 2        | 2.11%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2        | 2.11%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2        | 2.11%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 2        | 2.11%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 1        | 1.05%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 1        | 1.05%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch           | 1        | 1.05%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR        | 1        | 1.05%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                    | 1        | 1.05%   |
| Sony TV SNYEB01 1360x768                                             | 1        | 1.05%   |
| Sony TV SNYEA01 1920x1080                                            | 1        | 1.05%   |
| Sony TV SNYDC01 1360x768                                             | 1        | 1.05%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch  | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM03F5 1920x1200                     | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM03F4 1920x1200 518x324mm 24.1-inch | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch  | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 1.05%   |
| Samsung Electronics SMBX2050N SAM0719 1600x900 443x249mm 20.0-inch   | 1        | 1.05%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 1.05%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 1        | 1.05%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch | 1        | 1.05%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 1        | 1.05%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch    | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                 | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM02C8 1280x720                     | 1        | 1.05%   |
| PEGA 20 PEG00D0 1920x1080 480x270mm 21.7-inch                        | 1        | 1.05%   |
| Parker ML1715 PKR1EB2 1280x720 372x210mm 16.8-inch                   | 1        | 1.05%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                     | 1        | 1.05%   |
| LSC IPPSB-DB LSC282B 1920x1080 479x269mm 21.6-inch                   | 1        | 1.05%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.05%   |
| Lenovo LEN LS1922wA LEN0A14 1366x768 410x230mm 18.5-inch             | 1        | 1.05%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                | 1        | 1.05%   |
| Lenovo LEN L151 LEN23CD 1024x768 304x228mm 15.0-inch                 | 1        | 1.05%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 1        | 1.05%   |
| IBM LCD Monitor L171 1280x1024                                       | 1        | 1.05%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch          | 1        | 1.05%   |
| Hewlett-Packard w185e HWP292F 1366x768 410x230mm 18.5-inch           | 1        | 1.05%   |
| Hewlett-Packard TouchSmart HWP4218 1600x900 443x249mm 20.0-inch      | 1        | 1.05%   |
| Hewlett-Packard S1933 HWP2933 1366x768 413x234mm 18.7-inch           | 1        | 1.05%   |
| Hewlett-Packard Omni/Pro HWP410C 1600x900 443x249mm 20.0-inch        | 1        | 1.05%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch           | 1        | 1.05%   |
| Hewlett-Packard Compaq S2022 HWP290E 1600x900 442x249mm 20.0-inch    | 1        | 1.05%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch    | 1        | 1.05%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch           | 1        | 1.05%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch            | 1        | 1.05%   |
| Goldstar W2240 GSM57A0 1920x1080 477x268mm 21.5-inch                 | 1        | 1.05%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1        | 1.05%   |
| Goldstar L1950S GSM4AA1 1280x1024 376x301mm 19.0-inch                | 1        | 1.05%   |
| Goldstar L194W GSM4B6A 1440x900 408x255mm 18.9-inch                  | 1        | 1.05%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 1        | 1.05%   |
| Goldstar IPS234 GSM58DA 1920x1080 510x290mm 23.1-inch                | 1        | 1.05%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1280x1024 (SXGA)   | 22       | 23.91%  |
| 1920x1080 (FHD)    | 20       | 21.74%  |
| 1366x768 (WXGA)    | 18       | 19.57%  |
| 1440x900 (WXGA+)   | 8        | 8.7%    |
| 1600x900 (HD+)     | 7        | 7.61%   |
| 1680x1050 (WSXGA+) | 4        | 4.35%   |
| 1360x768           | 4        | 4.35%   |
| 1024x768 (XGA)     | 3        | 3.26%   |
| 1920x1200 (WUXGA)  | 2        | 2.17%   |
| 1280x720 (HD)      | 2        | 2.17%   |
| 3840x2160 (4K)     | 1        | 1.09%   |
| Unknown            | 1        | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 21       | 22.58%  |
| 17      | 16       | 17.2%   |
| 21      | 10       | 10.75%  |
| 19      | 9        | 9.68%   |
| 15      | 7        | 7.53%   |
| 20      | 6        | 6.45%   |
| Unknown | 6        | 6.45%   |
| 23      | 5        | 5.38%   |
| 74      | 3        | 3.23%   |
| 72      | 2        | 2.15%   |
| 22      | 2        | 2.15%   |
| 16      | 2        | 2.15%   |
| 52      | 1        | 1.08%   |
| 39      | 1        | 1.08%   |
| 24      | 1        | 1.08%   |
| 13      | 1        | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 43       | 46.74%  |
| 301-350     | 23       | 25%     |
| 501-600     | 6        | 6.52%   |
| 351-400     | 6        | 6.52%   |
| Unknown     | 6        | 6.52%   |
| 1501-2000   | 5        | 5.43%   |
| 801-900     | 1        | 1.09%   |
| 201-300     | 1        | 1.09%   |
| 1001-1500   | 1        | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 44       | 48.89%  |
| 5/4     | 20       | 22.22%  |
| 16/10   | 17       | 18.89%  |
| 4/3     | 4        | 4.44%   |
| Unknown | 4        | 4.44%   |
| 3/2     | 1        | 1.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 33       | 35.48%  |
| 151-200        | 21       | 22.58%  |
| 201-250        | 14       | 15.05%  |
| 101-110        | 7        | 7.53%   |
| More than 1000 | 6        | 6.45%   |
| Unknown        | 6        | 6.45%   |
| 121-130        | 2        | 2.15%   |
| 251-300        | 1        | 1.08%   |
| 131-140        | 1        | 1.08%   |
| 501-1000       | 1        | 1.08%   |
| 91-100         | 1        | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 66       | 71.74%  |
| 101-120 | 13       | 14.13%  |
| 1-50    | 6        | 6.52%   |
| Unknown | 6        | 6.52%   |
| 121-160 | 1        | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 84       | 84%     |
| 0     | 8        | 8%      |
| 2     | 7        | 7%      |
| 3     | 1        | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 57       | 35.85%  |
| Qualcomm Atheros                  | 26       | 16.35%  |
| Intel                             | 23       | 14.47%  |
| Ralink                            | 11       | 6.92%   |
| Nvidia                            | 10       | 6.29%   |
| Broadcom                          | 9        | 5.66%   |
| Ralink Technology                 | 4        | 2.52%   |
| Xiaomi                            | 3        | 1.89%   |
| VIA Technologies                  | 3        | 1.89%   |
| Qualcomm Atheros Communications   | 3        | 1.89%   |
| Sundance Technology Inc / IC Plus | 2        | 1.26%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.63%   |
| Trendchip Technologies            | 1        | 0.63%   |
| National Semiconductor            | 1        | 0.63%   |
| Motorola PCS                      | 1        | 0.63%   |
| Motorola BCS                      | 1        | 0.63%   |
| Mercucys                          | 1        | 0.63%   |
| Marvell Technology Group          | 1        | 0.63%   |
| ICS Advent                        | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 37       | 21.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11       | 6.51%   |
| Nvidia MCP61 Ethernet                                                          | 9        | 5.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 6        | 3.55%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 6        | 3.55%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5        | 2.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5        | 2.96%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4        | 2.37%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3        | 1.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 1.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3        | 1.78%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 1.78%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3        | 1.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2        | 1.18%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 2        | 1.18%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 1.18%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2        | 1.18%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2        | 1.18%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 2        | 1.18%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2        | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 1.18%   |
| Intel PRO/100 VE Network Connection                                            | 2        | 1.18%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.18%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 1.18%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 2        | 1.18%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 1.18%   |
| ZTE WCDMA MSM ZXIC Mobile Boardband                                            | 1        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1        | 0.59%   |
| Trendchip Ethernet controller                                                  | 1        | 0.59%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                          | 1        | 0.59%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 1        | 0.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 0.59%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 0.59%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 0.59%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 0.59%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 0.59%   |
| Qualcomm Atheros AR5523                                                        | 1        | 0.59%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1        | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 0.59%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 0.59%   |
| Nvidia MCP77 Ethernet                                                          | 1        | 0.59%   |
| National DP83815 (MacPhyter) Ethernet Controller                               | 1        | 0.59%   |
| Motorola PCS moto g stylus                                                     | 1        | 0.59%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                      | 1        | 0.59%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 1        | 0.59%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1        | 0.59%   |
| Intel Wireless 7265                                                            | 1        | 0.59%   |
| Intel Wireless 7260                                                            | 1        | 0.59%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 0.59%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.59%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 0.59%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 17       | 32.08%  |
| Ralink                          | 11       | 20.75%  |
| Realtek Semiconductor           | 10       | 18.87%  |
| Ralink Technology               | 4        | 7.55%   |
| Intel                           | 4        | 7.55%   |
| Qualcomm Atheros Communications | 3        | 5.66%   |
| Broadcom                        | 3        | 5.66%   |
| Mercucys                        | 1        | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 6        | 11.32%  |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5        | 9.43%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3        | 5.66%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3        | 5.66%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3        | 5.66%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 2        | 3.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2        | 3.77%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 3.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2        | 3.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2        | 3.77%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 2        | 3.77%   |
| Qualcomm Atheros AR9271 802.11n                                                | 2        | 3.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 3.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2        | 3.77%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2        | 3.77%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 1.89%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1        | 1.89%   |
| Ralink RT5372 Wireless Adapter                                                 | 1        | 1.89%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 1.89%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.89%   |
| Qualcomm Atheros AR5523                                                        | 1        | 1.89%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]            | 1        | 1.89%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 1        | 1.89%   |
| Intel Wireless 7265                                                            | 1        | 1.89%   |
| Intel Wireless 7260                                                            | 1        | 1.89%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 1.89%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 1        | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 52       | 45.61%  |
| Intel                             | 20       | 17.54%  |
| Qualcomm Atheros                  | 12       | 10.53%  |
| Nvidia                            | 10       | 8.77%   |
| Broadcom                          | 6        | 5.26%   |
| Xiaomi                            | 3        | 2.63%   |
| VIA Technologies                  | 3        | 2.63%   |
| Sundance Technology Inc / IC Plus | 2        | 1.75%   |
| Trendchip Technologies            | 1        | 0.88%   |
| National Semiconductor            | 1        | 0.88%   |
| Motorola PCS                      | 1        | 0.88%   |
| Motorola BCS                      | 1        | 0.88%   |
| Marvell Technology Group          | 1        | 0.88%   |
| ICS Advent                        | 1        | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 37       | 32.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 11       | 9.57%   |
| Nvidia MCP61 Ethernet                                                      | 9        | 7.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 6        | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 5        | 4.35%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4        | 3.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3        | 2.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 1.74%   |
| Intel PRO/100 VE Network Connection                                        | 2        | 1.74%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.74%   |
| Intel Ethernet Connection I217-LM                                          | 2        | 1.74%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 2        | 1.74%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.87%   |
| Trendchip Ethernet controller                                              | 1        | 0.87%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.87%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.87%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.87%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.87%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1        | 0.87%   |
| Motorola PCS moto g stylus                                                 | 1        | 0.87%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1        | 0.87%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.87%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 1        | 0.87%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 0.87%   |
| Intel 82567V-4 Gigabit Network Connection                                  | 1        | 0.87%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 1        | 0.87%   |
| Intel 82566DC Gigabit Network Connection                                   | 1        | 0.87%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1        | 0.87%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1        | 0.87%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 1        | 0.87%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1        | 0.87%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                            | 1        | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 99       | 66.44%  |
| WiFi     | 49       | 32.89%  |
| Modem    | 1        | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 70.19%  |
| WiFi     | 31       | 29.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 61       | 60.4%   |
| 2     | 37       | 36.63%  |
| 3     | 3        | 2.97%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 100      | 100%    |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 77       | 57.46%  |
| Nvidia              | 22       | 16.42%  |
| AMD                 | 20       | 14.93%  |
| VIA Technologies    | 4        | 2.99%   |
| C-Media Electronics | 4        | 2.99%   |
| Creative Labs       | 3        | 2.24%   |
| JMTek               | 2        | 1.49%   |
| Unknown             | 1        | 0.75%   |
| Logitech            | 1        | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 31       | 20.95%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 19       | 12.84%  |
| Nvidia MCP61 High Definition Audio                                          | 8        | 5.41%   |
| Nvidia GF119 HDMI Audio Controller                                          | 7        | 4.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 6        | 4.05%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 5        | 3.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 5        | 3.38%   |
| AMD FCH Azalia Controller                                                   | 5        | 3.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 4        | 2.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 4        | 2.7%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 3        | 2.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 3        | 2.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 3        | 2.03%   |
| Nvidia High Definition Audio Controller                                     | 2        | 1.35%   |
| Nvidia GF106 High Definition Audio Controller                               | 2        | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 2        | 1.35%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                        | 2        | 1.35%   |
| C-Media Electronics CM108 Audio Controller                                  | 2        | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 2        | 1.35%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                            | 2        | 1.35%   |
| AMD RV670/680 HDMI Audio [Radeon HD 3690/3800 Series]                       | 2        | 1.35%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]         | 2        | 1.35%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.68%   |
| Unknown Audio device                                                        | 1        | 0.68%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                   | 1        | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 1        | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                          | 1        | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                          | 1        | 0.68%   |
| Nvidia GF116 High Definition Audio Controller                               | 1        | 0.68%   |
| Nvidia GF114 HDMI Audio Controller                                          | 1        | 0.68%   |
| Nvidia GF104 High Definition Audio Controller                               | 1        | 0.68%   |
| Logitech H600 [Wireless Headset]                                            | 1        | 0.68%   |
| JMTek USB PnP Audio Device                                                  | 1        | 0.68%   |
| JMTek audio controller                                                      | 1        | 0.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                 | 1        | 0.68%   |
| Intel Cannon Lake PCH cAVS                                                  | 1        | 0.68%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 1        | 0.68%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 1        | 0.68%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 1        | 0.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 1        | 0.68%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                  | 1        | 0.68%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]   | 1        | 0.68%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                      | 1        | 0.68%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                               | 1        | 0.68%   |
| C-Media Electronics Audio Adapter                                           | 1        | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                   | 1        | 0.68%   |
| AMD Trinity HDMI Audio Controller                                           | 1        | 0.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 1        | 0.68%   |
| AMD Family 17h/19h HD Audio Controller                                      | 1        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 32       | 37.21%  |
| Kingston            | 10       | 11.63%  |
| Samsung Electronics | 8        | 9.3%    |
| Corsair             | 7        | 8.14%   |
| SK hynix            | 5        | 5.81%   |
| Crucial             | 4        | 4.65%   |
| Ramaxel Technology  | 3        | 3.49%   |
| Nanya Technology    | 3        | 3.49%   |
| Micron Technology   | 3        | 3.49%   |
| Avant               | 2        | 2.33%   |
| A-DATA Technology   | 2        | 2.33%   |
| Unknown (0x0CBA)    | 1        | 1.16%   |
| Team                | 1        | 1.16%   |
| PNY                 | 1        | 1.16%   |
| OCZ                 | 1        | 1.16%   |
| Kreton              | 1        | 1.16%   |
| Elpida              | 1        | 1.16%   |
| Unknown             | 1        | 1.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2                         | 3        | 3.13%   |
| Unknown RAM Module 1024MB DIMM DDR2                         | 3        | 3.13%   |
| Unknown RAM Module 4GB DIMM SDRAM                           | 2        | 2.08%   |
| Unknown RAM Module 2GB DIMM DDR2                            | 2        | 2.08%   |
| Unknown RAM Module 2GB DIMM 400MT/s                         | 2        | 2.08%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 2.08%   |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 2        | 2.08%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                 | 2        | 2.08%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s           | 2        | 2.08%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                        | 1        | 1.04%   |
| Unknown RAM Module 512MB DIMM DDR2                          | 1        | 1.04%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 1        | 1.04%   |
| Unknown RAM Module 4GB DIMM 400MT/s                         | 1        | 1.04%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                        | 1        | 1.04%   |
| Unknown RAM Module 4096MB DIMM SDRAM                        | 1        | 1.04%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                | 1        | 1.04%   |
| Unknown RAM Module 4096MB DIMM                              | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                   | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                     | 1        | 1.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                | 1        | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                 | 1        | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR2 1639MT/s                | 1        | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1        | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                  | 1        | 1.04%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 1        | 1.04%   |
| Unknown RAM Module 1GB DIMM DDR 133MT/s                     | 1        | 1.04%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                  | 1        | 1.04%   |
| Unknown (0x0CBA) RAM JC4S8GB26C03D 8GB SODIMM DDR4 2667MT/s | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s          | 1        | 1.04%   |
| SK hynix RAM HYMP112U64CP8-Y5 1024MB DIMM DDR2 1639MT/s     | 1        | 1.04%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s        | 1        | 1.04%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s        | 1        | 1.04%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 1        | 1.04%   |
| SK hynix RAM HMT125U6TFR8C-H9 2048MB DIMM DDR3              | 1        | 1.04%   |
| Samsung RAM Module 4096MB DIMM DDR3 1600MT/s                | 1        | 1.04%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s                | 1        | 1.04%   |
| Samsung RAM Module 1024MB DIMM DDR2 533MT/s                 | 1        | 1.04%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1        | 1.04%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s         | 1        | 1.04%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s      | 1        | 1.04%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s         | 1        | 1.04%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s         | 1        | 1.04%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.04%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s        | 1        | 1.04%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s         | 1        | 1.04%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s       | 1        | 1.04%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s       | 1        | 1.04%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s    | 1        | 1.04%   |
| PNY RAM Module 4096MB DIMM DDR3 1333MT/s                    | 1        | 1.04%   |
| OCZ RAM OCZ2P8002G 2GB DIMM DDR2 1024MT/s                   | 1        | 1.04%   |
| Nanya RAM Module 1024MB DIMM DDR2 800MT/s                   | 1        | 1.04%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1067MT/s         | 1        | 1.04%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB DIMM DDR3 1066MT/s      | 1        | 1.04%   |
| Micron RAM 16HTF25664AZ-800J1 2GB DIMM DDR2 800MT/s         | 1        | 1.04%   |
| Kreton RAM 51623010G681451465 2048MB DIMM DDR2 400MT/s      | 1        | 1.04%   |
| Kingston RAM Module 2048MB DIMM DDR3 1333MT/s               | 1        | 1.04%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 26       | 37.14%  |
| DDR2    | 21       | 30%     |
| SDRAM   | 10       | 14.29%  |
| Unknown | 6        | 8.57%   |
| DDR     | 4        | 5.71%   |
| DDR4    | 3        | 4.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 65       | 95.59%  |
| SODIMM | 3        | 4.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 35       | 42.68%  |
| 4096  | 20       | 24.39%  |
| 1024  | 15       | 18.29%  |
| 8192  | 9        | 10.98%  |
| 16384 | 2        | 2.44%   |
| 512   | 1        | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 20.51%  |
| Unknown | 15       | 19.23%  |
| 1333    | 11       | 14.1%   |
| 800     | 6        | 7.69%   |
| 1066    | 4        | 5.13%   |
| 533     | 4        | 5.13%   |
| 1639    | 3        | 3.85%   |
| 667     | 3        | 3.85%   |
| 400     | 3        | 3.85%   |
| 133     | 3        | 3.85%   |
| 2048    | 2        | 2.56%   |
| 3200    | 1        | 1.28%   |
| 3000    | 1        | 1.28%   |
| 2667    | 1        | 1.28%   |
| 2400    | 1        | 1.28%   |
| 2133    | 1        | 1.28%   |
| 1867    | 1        | 1.28%   |
| 1067    | 1        | 1.28%   |
| 1024    | 1        | 1.28%   |

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
| Logitech                    | 5        | 29.41%  |
| Microsoft                   | 2        | 11.76%  |
| KYE Systems (Mouse Systems) | 2        | 11.76%  |
| IMC Networks                | 2        | 11.76%  |
| Suyin                       | 1        | 5.88%   |
| SiGma Micro                 | 1        | 5.88%   |
| Samsung Electronics         | 1        | 5.88%   |
| Realtek Semiconductor       | 1        | 5.88%   |
| LG Electronics              | 1        | 5.88%   |
| Aveo Technology             | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 3        | 17.65%  |
| Suyin HP Webcam                                       | 1        | 5.88%   |
| SiGma Micro WebCam SiGma Micro                        | 1        | 5.88%   |
| Samsung Galaxy series, misc. (MTP mode)               | 1        | 5.88%   |
| Realtek HP 1.0MP High Definition Webcam               | 1        | 5.88%   |
| Microsoft LifeCam VX-5000                             | 1        | 5.88%   |
| Microsoft LifeCam Studio                              | 1        | 5.88%   |
| Logitech QuickCam Communicate MP/S5500                | 1        | 5.88%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 5.88%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 5.88%   |
| KYE Systems (Mouse Systems) FaceCam 1320              | 1        | 5.88%   |
| KYE Systems (Mouse Systems) eFace 2025                | 1        | 5.88%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                   | 1        | 5.88%   |
| IMC Networks USB 2.0 Camera                           | 1        | 5.88%   |
| Aveo USB2.0 Camera                                    | 1        | 5.88%   |

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
| 0     | 79       | 79%     |
| 1     | 20       | 20%     |
| 2     | 1        | 1%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 45.45%  |
| Communication controller | 9        | 40.91%  |
| Sound                    | 2        | 9.09%   |
| Net/wireless             | 1        | 4.55%   |

