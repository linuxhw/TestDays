Linux in Uruguay - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Uruguay.

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

Total: 154

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | H81M-H                      | [a775bc4b08](https://linux-hardware.org/?probe=a775bc4b08) | Oct 05, 2023 |
| MSI        | B85M-E45                    | [d454b67226](https://linux-hardware.org/?probe=d454b67226) | Sep 13, 2023 |
| Gigabyte   | Z87X-UD4H-CF                | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| Dell       | 0V8WGR A01                  | [9e5ed52b45](https://linux-hardware.org/?probe=9e5ed52b45) | Aug 29, 2023 |
| Gigabyte   | Z790 AORUS ELITE AX DDR4    | [025bd1edae](https://linux-hardware.org/?probe=025bd1edae) | Aug 04, 2023 |
| ASUSTek    | PRIME A320M-K               | [a4d7919584](https://linux-hardware.org/?probe=a4d7919584) | Jul 29, 2023 |
| HP         | 1497                        | [370799b635](https://linux-hardware.org/?probe=370799b635) | Jul 26, 2023 |
| Gigabyte   | Z370 AORUS Gaming 7         | [01cfac81b4](https://linux-hardware.org/?probe=01cfac81b4) | Jul 24, 2023 |
| ASRock     | H510M-HDV R2.0              | [cacf2d88c9](https://linux-hardware.org/?probe=cacf2d88c9) | Jul 19, 2023 |
| ASUSTek    | PRIME A320M-K               | [6776e11ac9](https://linux-hardware.org/?probe=6776e11ac9) | Jul 14, 2023 |
| Dell       | 0K240Y A02                  | [7d1d71b0fe](https://linux-hardware.org/?probe=7d1d71b0fe) | Jul 06, 2023 |
| Intel      | H61                         | [ac2b137243](https://linux-hardware.org/?probe=ac2b137243) | Jun 15, 2023 |
| Dell       | 0V8WGR A02                  | [448fd1711d](https://linux-hardware.org/?probe=448fd1711d) | Jun 12, 2023 |
| HP         | 0A60h                       | [f0498c1a54](https://linux-hardware.org/?probe=f0498c1a54) | Jun 07, 2023 |
| Lenovo     | 30D2 SDK0J40697 WIN 3305... | [624a84a2fc](https://linux-hardware.org/?probe=624a84a2fc) | Jun 06, 2023 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| MSI        | 760GM-P23                   | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| ASRock     | N68-S3 UCC                  | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Lenovo     | MAHOBAY                     | [97cc4e0a84](https://linux-hardware.org/?probe=97cc4e0a84) | May 01, 2023 |
| Gigabyte   | A320M-S2H V2-CF             | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock     | H61M-DGS                    | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Gigabyte   | H61M-S1                     | [9af85c78cb](https://linux-hardware.org/?probe=9af85c78cb) | Mar 28, 2023 |
| MSI        | A68HM-E33 V2                | [1531761af6](https://linux-hardware.org/?probe=1531761af6) | Mar 26, 2023 |
| ASUSTek    | PRIME A320M-K               | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| MSI        | H310M PRO-VDH PLUS          | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| Gigabyte   | B450M DS3H WIFI-CF          | [b94932937e](https://linux-hardware.org/?probe=b94932937e) | Mar 14, 2023 |
| AZW        | MINI S                      | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| MSI        | H61M-P31/W8                 | [163991dfae](https://linux-hardware.org/?probe=163991dfae) | Feb 03, 2023 |
| MSI        | H61M-P31/W8                 | [a08e60bb31](https://linux-hardware.org/?probe=a08e60bb31) | Feb 03, 2023 |
| MSI        | H61M-P31/W8                 | [d6829621d7](https://linux-hardware.org/?probe=d6829621d7) | Feb 03, 2023 |
| HP         | 339A                        | [5d86fd4411](https://linux-hardware.org/?probe=5d86fd4411) | Jan 20, 2023 |
| ASUSTek    | H170 PRO GAMING             | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| MSI        | 2A9C                        | [57c14b82bd](https://linux-hardware.org/?probe=57c14b82bd) | Nov 23, 2022 |
| ASUSTek    | Z97-C                       | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| ASRock     | H310CM-HDV                  | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek    | H170 PRO GAMING             | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock     | H310CM-HDV                  | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| Dell       | 0XFWHV A00                  | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| MSI        | 2A9C                        | [74482fb396](https://linux-hardware.org/?probe=74482fb396) | Oct 16, 2022 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| MSI        | 2A9C                        | [1c1d20a1ac](https://linux-hardware.org/?probe=1c1d20a1ac) | Oct 09, 2022 |
| MSI        | 2A9C                        | [98ff35e2a7](https://linux-hardware.org/?probe=98ff35e2a7) | Oct 09, 2022 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [adde8098e4](https://linux-hardware.org/?probe=adde8098e4) | Oct 04, 2022 |
| Huanan     | X79 (INTEL Xeon E5/Corei... | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Biostar    | H410MH S2                   | [b03e32f37d](https://linux-hardware.org/?probe=b03e32f37d) | Sep 29, 2022 |
| Biostar    | H410MH S2                   | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| HP         | 8265                        | [2b74e032bd](https://linux-hardware.org/?probe=2b74e032bd) | Sep 06, 2022 |
| HP         | 8265                        | [f7f460fb43](https://linux-hardware.org/?probe=f7f460fb43) | Sep 05, 2022 |
| Gigabyte   | Z87X-UD4H-CF                | [8ffe312747](https://linux-hardware.org/?probe=8ffe312747) | Sep 04, 2022 |
| ASRock     | N68-S                       | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASRock     | N68-S                       | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASRock     | FM2A58M-VG3+ R2.0           | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock     | N68-S                       | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| HP         | 3048h                       | [34e0bbc168](https://linux-hardware.org/?probe=34e0bbc168) | Aug 20, 2022 |
| Gigabyte   | B460M DS3H                  | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| Biostar    | B550MH                      | [228a44e3f0](https://linux-hardware.org/?probe=228a44e3f0) | Aug 06, 2022 |
| ASRock     | B75M                        | [78fbdcd0f7](https://linux-hardware.org/?probe=78fbdcd0f7) | Aug 05, 2022 |
| MACHINIST  | X79 (INTEL Xeon E5/Corei... | [e83fe522d7](https://linux-hardware.org/?probe=e83fe522d7) | Jul 31, 2022 |
| Gigabyte   | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| ASRock     | FM2A58M-VG3+ R2.0           | [04affeedf7](https://linux-hardware.org/?probe=04affeedf7) | Jul 18, 2022 |
| HP         | 1632                        | [d2582aff1d](https://linux-hardware.org/?probe=d2582aff1d) | Jul 12, 2022 |
| Gigabyte   | H410M H V3                  | [0d26f198ff](https://linux-hardware.org/?probe=0d26f198ff) | Jul 06, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [5fa355f7ec](https://linux-hardware.org/?probe=5fa355f7ec) | Jun 26, 2022 |
| Gigabyte   | B450 GAMING X               | [34e884bb50](https://linux-hardware.org/?probe=34e884bb50) | Jun 08, 2022 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [95ac26b654](https://linux-hardware.org/?probe=95ac26b654) | May 19, 2022 |
| Foxconn    | G31MX Series                | [911987151a](https://linux-hardware.org/?probe=911987151a) | Mar 23, 2022 |
| Foxconn    | G31MX Series                | [7d9cc6ac07](https://linux-hardware.org/?probe=7d9cc6ac07) | Mar 22, 2022 |
| Gigabyte   | Z370 AORUS Gaming 7         | [9699b8889c](https://linux-hardware.org/?probe=9699b8889c) | Feb 27, 2022 |
| ASUSTek    | TUF Gaming B460M-PLUS       | [37231251ed](https://linux-hardware.org/?probe=37231251ed) | Feb 21, 2022 |
| ASRock     | FM2A55M-HD+                 | [52ca8c0d7c](https://linux-hardware.org/?probe=52ca8c0d7c) | Feb 13, 2022 |
| HP         | 3047h                       | [ee6260c5f4](https://linux-hardware.org/?probe=ee6260c5f4) | Feb 10, 2022 |
| Gigabyte   | GA-970A-D3                  | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| HP         | 0AA8h                       | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| HP         | 0AA8h                       | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Biostar    | Z490A-SILVER                | [b5e7622be0](https://linux-hardware.org/?probe=b5e7622be0) | Jan 02, 2022 |
| Dell       | 06D7TR A00                  | [90f509fc24](https://linux-hardware.org/?probe=90f509fc24) | Dec 09, 2021 |
| Gigabyte   | H81M-DS2                    | [44b341f68d](https://linux-hardware.org/?probe=44b341f68d) | Nov 10, 2021 |
| ASRock     | N68-S                       | [eac798f714](https://linux-hardware.org/?probe=eac798f714) | Nov 01, 2021 |
| Gigabyte   | X570 GAMING X               | [174875a3d4](https://linux-hardware.org/?probe=174875a3d4) | Oct 25, 2021 |
| MSI        | X570-A PRO                  | [357ea9ab5d](https://linux-hardware.org/?probe=357ea9ab5d) | Oct 22, 2021 |
| ASRock     | B450M Steel Legend          | [fea193c839](https://linux-hardware.org/?probe=fea193c839) | Sep 10, 2021 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [dbeb8785e6](https://linux-hardware.org/?probe=dbeb8785e6) | Sep 01, 2021 |
| ASRock     | FM2A55M-VG3+                | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| ASUSTek    | M5A99X EVO R2.0             | [b6c401b55e](https://linux-hardware.org/?probe=b6c401b55e) | Jul 15, 2021 |
| ASUSTek    | TUF Gaming B550-PLUS        | [38ee95b416](https://linux-hardware.org/?probe=38ee95b416) | Jun 02, 2021 |
| ASUSTek    | PRIME B450M-A II            | [ab4b1b7a15](https://linux-hardware.org/?probe=ab4b1b7a15) | May 31, 2021 |
| ASRock     | FM2A55M-VG3+                | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| ASRock     | A320M-HDV R3.0              | [0ed78505e8](https://linux-hardware.org/?probe=0ed78505e8) | May 19, 2021 |
| ASRock     | FM2A55M-VG3+                | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| ASRock     | FM2A55M-VG3+                | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| ASRock     | N68-VS3 FX                  | [bcee870f79](https://linux-hardware.org/?probe=bcee870f79) | Apr 24, 2021 |
| ASRock     | N68-VS3 FX                  | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| ASUSTek    | M5A78L-M/USB3               | [7d28bb0ba2](https://linux-hardware.org/?probe=7d28bb0ba2) | Apr 23, 2021 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [5042e6d421](https://linux-hardware.org/?probe=5042e6d421) | Apr 20, 2021 |
| ASUSTek    | P8H77-V                     | [9b0d9c1623](https://linux-hardware.org/?probe=9b0d9c1623) | Apr 05, 2021 |
| Supermicro | P4DMS                       | [34867ad122](https://linux-hardware.org/?probe=34867ad122) | Mar 22, 2021 |
| Supermicro | P4DMS                       | [9de21bc6ec](https://linux-hardware.org/?probe=9de21bc6ec) | Mar 14, 2021 |
| Lenovo     | MAHOBAY NOK                 | [901fd74eaa](https://linux-hardware.org/?probe=901fd74eaa) | Feb 20, 2021 |
| ASUSTek    | PRIME B450M-A II            | [7f1fc20897](https://linux-hardware.org/?probe=7f1fc20897) | Feb 19, 2021 |
| ASUSTek    | PRIME B450M-A II            | [9527a6802e](https://linux-hardware.org/?probe=9527a6802e) | Feb 19, 2021 |
| Gigabyte   | H81M-DS2                    | [9473725930](https://linux-hardware.org/?probe=9473725930) | Feb 15, 2021 |
| Dell       | 0C522T A03                  | [0b52890aaf](https://linux-hardware.org/?probe=0b52890aaf) | Jan 29, 2021 |
| Dell       | 0C522T A03                  | [3a777180a1](https://linux-hardware.org/?probe=3a777180a1) | Jan 29, 2021 |
| Intel      | H61M-DS2                    | [930418d2da](https://linux-hardware.org/?probe=930418d2da) | Jan 23, 2021 |
| Gigabyte   | H81M-DS2                    | [4b7df9598e](https://linux-hardware.org/?probe=4b7df9598e) | Jan 20, 2021 |
| Intel      | H61M-DS2                    | [53bde98202](https://linux-hardware.org/?probe=53bde98202) | Jan 09, 2021 |
| MSI        | A55M-P33                    | [43267cc6f4](https://linux-hardware.org/?probe=43267cc6f4) | Dec 16, 2020 |
| ASRock     | H310CM-HDV                  | [729161e56a](https://linux-hardware.org/?probe=729161e56a) | Dec 08, 2020 |
| ASRock     | H310CM-HDV                  | [37f7b460d4](https://linux-hardware.org/?probe=37f7b460d4) | Dec 08, 2020 |
| ASRock     | A320M-HDV                   | [912852805f](https://linux-hardware.org/?probe=912852805f) | Oct 22, 2020 |
| Dell       | 0C27VV A00                  | [fd9547e219](https://linux-hardware.org/?probe=fd9547e219) | Oct 01, 2020 |
| Gigabyte   | H310M A-CF                  | [ff30e910c4](https://linux-hardware.org/?probe=ff30e910c4) | Aug 12, 2020 |
| Intel      | DP35DP AAD81073-208         | [0009968f3b](https://linux-hardware.org/?probe=0009968f3b) | Aug 05, 2020 |
| Gigabyte   | GA-78LMT-S2                 | [71c07410ee](https://linux-hardware.org/?probe=71c07410ee) | Jul 25, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [d4c35c226e](https://linux-hardware.org/?probe=d4c35c226e) | Jul 01, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [178da315d2](https://linux-hardware.org/?probe=178da315d2) | Jul 01, 2020 |
| Fujitsu    | D3064-A1 S26361-D3064-A1    | [6a4b069ed8](https://linux-hardware.org/?probe=6a4b069ed8) | Jun 30, 2020 |
| MSI        | H81M-E33                    | [9f2577531a](https://linux-hardware.org/?probe=9f2577531a) | Jun 10, 2020 |
| MSI        | B85-G43 GAMING              | [0a5437ade3](https://linux-hardware.org/?probe=0a5437ade3) | May 22, 2020 |
| ASUSTek    | P8H67-M LX                  | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| ASUSTek    | Rampage IV EXTREME          | [627fed813d](https://linux-hardware.org/?probe=627fed813d) | May 18, 2020 |
| Gigabyte   | H61M-S1                     | [493ce118d1](https://linux-hardware.org/?probe=493ce118d1) | May 16, 2020 |
| ASUSTek    | K8V-X SE                    | [154224ff78](https://linux-hardware.org/?probe=154224ff78) | May 16, 2020 |
| ASUSTek    | K8V-X SE                    | [173008c9ff](https://linux-hardware.org/?probe=173008c9ff) | May 16, 2020 |
| Gigabyte   | H61M-S1                     | [98a86c1397](https://linux-hardware.org/?probe=98a86c1397) | May 15, 2020 |
| ASUSTek    | Rampage IV EXTREME          | [1beb748dc0](https://linux-hardware.org/?probe=1beb748dc0) | May 12, 2020 |
| HP         | 090Ch                       | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP         | 090Ch                       | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| MSI        | B85-G43 GAMING              | [1532d55ba0](https://linux-hardware.org/?probe=1532d55ba0) | May 01, 2020 |
| MSI        | B85-G43 GAMING              | [c931341a8c](https://linux-hardware.org/?probe=c931341a8c) | May 01, 2020 |
| ASRock     | G41M-VS3                    | [e52c07ce77](https://linux-hardware.org/?probe=e52c07ce77) | May 01, 2020 |
| Gateway    | DX4375                      | [1470b063f3](https://linux-hardware.org/?probe=1470b063f3) | Apr 28, 2020 |
| ECS        | H310H5-M2                   | [b1aaebf57b](https://linux-hardware.org/?probe=b1aaebf57b) | Apr 19, 2020 |
| ASRock     | ALiveNF6P-VSTA              | [3036b319ab](https://linux-hardware.org/?probe=3036b319ab) | Apr 16, 2020 |
| ASRock     | ALiveNF6P-VSTA              | [ebd210c2af](https://linux-hardware.org/?probe=ebd210c2af) | Apr 16, 2020 |
| MSI        | G31M2                       | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| HP         | 1497                        | [973b170ac6](https://linux-hardware.org/?probe=973b170ac6) | Mar 23, 2020 |
| HP         | 1497                        | [26d8104c5e](https://linux-hardware.org/?probe=26d8104c5e) | Mar 02, 2020 |
| MSI        | A68HM-E33 V2                | [743f3ff81c](https://linux-hardware.org/?probe=743f3ff81c) | Dec 22, 2019 |
| MSI        | A68HM-E33 V2                | [1d3a9ef0d2](https://linux-hardware.org/?probe=1d3a9ef0d2) | Dec 22, 2019 |
| MSI        | A68HM-E33 V2                | [806c1e6d78](https://linux-hardware.org/?probe=806c1e6d78) | Dec 22, 2019 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [c28821415f](https://linux-hardware.org/?probe=c28821415f) | Nov 15, 2019 |
| Gigabyte   | H81M-DS2                    | [273463747b](https://linux-hardware.org/?probe=273463747b) | Oct 29, 2019 |
| Gigabyte   | H81M-DS2                    | [dfda14135d](https://linux-hardware.org/?probe=dfda14135d) | Oct 28, 2019 |
| Gigabyte   | H81M-DS2                    | [3418011c79](https://linux-hardware.org/?probe=3418011c79) | Oct 27, 2019 |
| Gigabyte   | H81M-DS2                    | [cb622d3902](https://linux-hardware.org/?probe=cb622d3902) | Oct 27, 2019 |
| ASUSTek    | M5A87                       | [cead36d312](https://linux-hardware.org/?probe=cead36d312) | May 18, 2019 |
| ASUSTek    | M5A87                       | [6dfdec0635](https://linux-hardware.org/?probe=6dfdec0635) | May 18, 2019 |
| HP         | 1998                        | [0ae1b2ac01](https://linux-hardware.org/?probe=0ae1b2ac01) | May 13, 2019 |
| Gigabyte   | AX370-Gaming 5              | [547801f07c](https://linux-hardware.org/?probe=547801f07c) | Apr 15, 2019 |
| Gigabyte   | AX370-Gaming 5              | [859c76fdf7](https://linux-hardware.org/?probe=859c76fdf7) | Mar 17, 2019 |
| ASRock     | ALiveNF6P-VSTA              | [4684e2d239](https://linux-hardware.org/?probe=4684e2d239) | Dec 04, 2018 |
| ASRock     | ALiveNF6P-VSTA              | [a26c805e14](https://linux-hardware.org/?probe=a26c805e14) | Dec 04, 2018 |
| MSI        | G41M-P26                    | [59c7d54670](https://linux-hardware.org/?probe=59c7d54670) | Nov 10, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 12       | 10.81%  |
| OpenMandriva 4.3   | 11       | 9.91%   |
| Manjaro            | 8        | 7.21%   |
| Ubuntu 18.04       | 7        | 6.31%   |
| ArcoLinux Rolling  | 5        | 4.5%    |
| Xubuntu 20.04      | 4        | 3.6%    |
| Ubuntu 22.04       | 4        | 3.6%    |
| OpenMandriva 23.01 | 3        | 2.7%    |
| Linux Mint 19.3    | 3        | 2.7%    |
| Debian 11          | 3        | 2.7%    |
| Ubuntu 18.10       | 2        | 1.8%    |
| ROSA R11.1         | 2        | 1.8%    |
| Pop!_OS 20.04      | 2        | 1.8%    |
| OpenMandriva 23.03 | 2        | 1.8%    |
| Linux Mint 20      | 2        | 1.8%    |
| Linux Mint 19.1    | 2        | 1.8%    |
| KDE neon 20.04     | 2        | 1.8%    |
| BlackPanther 18.1  | 2        | 1.8%    |
| Arch               | 2        | 1.8%    |
| Zorin 16           | 1        | 0.9%    |
| Zorin 15           | 1        | 0.9%    |
| Xubuntu 21.04      | 1        | 0.9%    |
| Xubuntu 18.04      | 1        | 0.9%    |
| Ubuntu 21.10       | 1        | 0.9%    |
| Ubuntu 19.04       | 1        | 0.9%    |
| ROSA 12.4          | 1        | 0.9%    |
| Pop!_OS 22.04      | 1        | 0.9%    |
| Pop!_OS 21.10      | 1        | 0.9%    |
| OpenMandriva 4.90  | 1        | 0.9%    |
| OpenMandriva 4.50  | 1        | 0.9%    |
| OpenMandriva 4.2   | 1        | 0.9%    |
| OpenMandriva 23.08 | 1        | 0.9%    |
| Lubuntu 18.04      | 1        | 0.9%    |
| Lubuntu 16.10      | 1        | 0.9%    |
| LMDE 4             | 1        | 0.9%    |
| LinuxFX 11.1       | 1        | 0.9%    |
| Linux Mint 21.2    | 1        | 0.9%    |
| Linux Mint 21.1    | 1        | 0.9%    |
| Linux Mint 21      | 1        | 0.9%    |
| Linux Mint 20.3    | 1        | 0.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 26       | 24.07%  |
| OpenMandriva | 19       | 17.59%  |
| Linux Mint   | 12       | 11.11%  |
| Manjaro      | 8        | 7.41%   |
| Xubuntu      | 6        | 5.56%   |
| Fedora       | 5        | 4.63%   |
| ArcoLinux    | 5        | 4.63%   |
| Pop!_OS      | 4        | 3.7%    |
| KDE neon     | 4        | 3.7%    |
| Debian       | 4        | 3.7%    |
| ROSA         | 3        | 2.78%   |
| Arch         | 3        | 2.78%   |
| Zorin        | 2        | 1.85%   |
| Lubuntu      | 2        | 1.85%   |
| BlackPanther | 2        | 1.85%   |
| LMDE         | 1        | 0.93%   |
| LinuxFX      | 1        | 0.93%   |
| Endless      | 1        | 0.93%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Desktops | Percent |
|-----------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003           | 11       | 9.4%    |
| 5.4.0-42-generic                  | 4        | 3.42%   |
| 6.1.1-desktop-1omv2290            | 3        | 2.56%   |
| 5.3.0-46-generic                  | 3        | 2.56%   |
| 6.2.6-desktop-1omv2390            | 2        | 1.71%   |
| 6.1.26-1-MANJARO                  | 2        | 1.71%   |
| 5.4.83-generic-2rosa-x86_64       | 2        | 1.71%   |
| 5.4.0-65-generic                  | 2        | 1.71%   |
| 5.15.60-1-MANJARO                 | 2        | 1.71%   |
| 5.15.0-67-generic                 | 2        | 1.71%   |
| 5.15.0-48-generic                 | 2        | 1.71%   |
| 5.11.0-38-generic                 | 2        | 1.71%   |
| 5.10.0-21-amd64                   | 2        | 1.71%   |
| 5.0.0-32-generic                  | 2        | 1.71%   |
| 4.18.16-desktop-1bP               | 2        | 1.71%   |
| 6.4.11-desktop-1omv2390           | 1        | 0.85%   |
| 6.4.11-arch2-1                    | 1        | 0.85%   |
| 6.3.8-arch1-1                     | 1        | 0.85%   |
| 6.3.7-arch1-1                     | 1        | 0.85%   |
| 6.2.16-10-pve                     | 1        | 0.85%   |
| 6.2.12-1-MANJARO                  | 1        | 0.85%   |
| 6.2.0-34-generic                  | 1        | 0.85%   |
| 6.1.20-generic-2rosa2021.1-x86_64 | 1        | 0.85%   |
| 6.1.11-arch1-1                    | 1        | 0.85%   |
| 6.0.18-300.fc37.x86_64            | 1        | 0.85%   |
| 6.0.0-1-MANJARO                   | 1        | 0.85%   |
| 5.6.0-2-amd64                     | 1        | 0.85%   |
| 5.4.0-92-lowlatency               | 1        | 0.85%   |
| 5.4.0-91-generic                  | 1        | 0.85%   |
| 5.4.0-72-generic                  | 1        | 0.85%   |
| 5.4.0-62-generic                  | 1        | 0.85%   |
| 5.4.0-56-generic                  | 1        | 0.85%   |
| 5.4.0-52-generic                  | 1        | 0.85%   |
| 5.4.0-39-generic                  | 1        | 0.85%   |
| 5.4.0-33-generic                  | 1        | 0.85%   |
| 5.4.0-29-generic                  | 1        | 0.85%   |
| 5.4.0-26-generic                  | 1        | 0.85%   |
| 5.4.0-150-generic                 | 1        | 0.85%   |
| 5.4.0-137-lowlatency              | 1        | 0.85%   |
| 5.4.0-0.bpo.4-amd64               | 1        | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 18       | 15.79%  |
| 5.16.7  | 11       | 9.65%   |
| 5.15.0  | 9        | 7.89%   |
| 4.15.0  | 8        | 7.02%   |
| 5.11.0  | 6        | 5.26%   |
| 5.3.0   | 5        | 4.39%   |
| 6.1.1   | 3        | 2.63%   |
| 5.13.0  | 3        | 2.63%   |
| 5.10.0  | 3        | 2.63%   |
| 5.0.0   | 3        | 2.63%   |
| 4.18.0  | 3        | 2.63%   |
| 6.4.11  | 2        | 1.75%   |
| 6.2.6   | 2        | 1.75%   |
| 6.1.26  | 2        | 1.75%   |
| 5.4.83  | 2        | 1.75%   |
| 5.19.0  | 2        | 1.75%   |
| 5.18.12 | 2        | 1.75%   |
| 5.15.60 | 2        | 1.75%   |
| 4.18.16 | 2        | 1.75%   |
| 6.3.8   | 1        | 0.88%   |
| 6.3.7   | 1        | 0.88%   |
| 6.2.16  | 1        | 0.88%   |
| 6.2.12  | 1        | 0.88%   |
| 6.2.0   | 1        | 0.88%   |
| 6.1.20  | 1        | 0.88%   |
| 6.1.11  | 1        | 0.88%   |
| 6.0.18  | 1        | 0.88%   |
| 6.0.0   | 1        | 0.88%   |
| 5.6.0   | 1        | 0.88%   |
| 5.19.16 | 1        | 0.88%   |
| 5.18.10 | 1        | 0.88%   |
| 5.17.5  | 1        | 0.88%   |
| 5.17.12 | 1        | 0.88%   |
| 5.15.74 | 1        | 0.88%   |
| 5.15.23 | 1        | 0.88%   |
| 5.13.12 | 1        | 0.88%   |
| 5.12.8  | 1        | 0.88%   |
| 5.12.4  | 1        | 0.88%   |
| 5.12.3  | 1        | 0.88%   |
| 5.12.15 | 1        | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 17.54%  |
| 5.15    | 13       | 11.4%   |
| 5.16    | 11       | 9.65%   |
| 5.11    | 8        | 7.02%   |
| 4.15    | 8        | 7.02%   |
| 6.1     | 7        | 6.14%   |
| 6.2     | 5        | 4.39%   |
| 5.3     | 5        | 4.39%   |
| 5.10    | 5        | 4.39%   |
| 4.18    | 5        | 4.39%   |
| 5.13    | 4        | 3.51%   |
| 5.12    | 4        | 3.51%   |
| 5.19    | 3        | 2.63%   |
| 5.18    | 3        | 2.63%   |
| 5.0     | 3        | 2.63%   |
| 6.4     | 2        | 1.75%   |
| 6.3     | 2        | 1.75%   |
| 6.0     | 2        | 1.75%   |
| 5.17    | 2        | 1.75%   |
| 5.6     | 1        | 0.88%   |
| 4.8     | 1        | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 101      | 97.12%  |
| i686   | 3        | 2.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 33       | 30.84%  |
| GNOME      | 31       | 28.97%  |
| XFCE       | 11       | 10.28%  |
| X-Cinnamon | 10       | 9.35%   |
| Unknown    | 8        | 7.48%   |
| LXDE       | 3        | 2.8%    |
| Cinnamon   | 3        | 2.8%    |
| MATE       | 2        | 1.87%   |
| KDE4       | 2        | 1.87%   |
| KDE        | 2        | 1.87%   |
| qtile      | 1        | 0.93%   |
| ICEWM      | 1        | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 91       | 84.26%  |
| Wayland | 11       | 10.19%  |
| Unknown | 4        | 3.7%    |
| Tty     | 2        | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 47.17%  |
| SDDM    | 28       | 26.42%  |
| LightDM | 14       | 13.21%  |
| GDM     | 6        | 5.66%   |
| GDM3    | 5        | 4.72%   |
| KDM     | 2        | 1.89%   |
| TDM     | 1        | 0.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| es_UY      | 60       | 55.56%  |
| en_US      | 19       | 17.59%  |
| es_ES      | 12       | 11.11%  |
| Unknown    | 8        | 7.41%   |
| es_AR      | 4        | 3.7%    |
| C          | 3        | 2.78%   |
| es_UY.UTF8 | 1        | 0.93%   |
| en_GB      | 1        | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 66       | 61.11%  |
| EFI  | 42       | 38.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 78       | 72.9%   |
| Overlay | 21       | 19.63%  |
| Tmpfs   | 3        | 2.8%    |
| Btrfs   | 3        | 2.8%    |
| Xfs     | 1        | 0.93%   |
| Unknown | 1        | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 48.6%   |
| GPT     | 40       | 37.38%  |
| MBR     | 15       | 14.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 75.96%  |
| Yes       | 25       | 24.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 59.43%  |
| Yes       | 43       | 40.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 21       | 20.19%  |
| ASRock              | 19       | 18.27%  |
| ASUSTek Computer    | 15       | 14.42%  |
| MSI                 | 14       | 13.46%  |
| Hewlett-Packard     | 11       | 10.58%  |
| Dell                | 7        | 6.73%   |
| Lenovo              | 3        | 2.88%   |
| Intel               | 3        | 2.88%   |
| Biostar             | 3        | 2.88%   |
| Supermicro          | 1        | 0.96%   |
| MACHINIST           | 1        | 0.96%   |
| Huanan              | 1        | 0.96%   |
| Gateway             | 1        | 0.96%   |
| Fujitsu             | 1        | 0.96%   |
| Foxconn             | 1        | 0.96%   |
| ECS                 | 1        | 0.96%   |
| AZW                 | 1        | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                             | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| MSI MS-7C37                                                      | 2        | 1.92%   |
| MSI MS-7817                                                      | 2        | 1.92%   |
| MSI MS-7721                                                      | 2        | 1.92%   |
| HP Compaq 6200 Pro SFF PC                                        | 2        | 1.92%   |
| Gigabyte Z390 AORUS ELITE                                        | 2        | 1.92%   |
| Gigabyte Z370 AORUS Gaming 7                                     | 2        | 1.92%   |
| Gigabyte H61M-S1                                                 | 2        | 1.92%   |
| Dell OptiPlex 7010                                               | 2        | 1.92%   |
| ASRock N68-S                                                     | 2        | 1.92%   |
| ASRock H310CM-HDV                                                | 2        | 1.92%   |
| ASRock FM2A58M-VG3+ R2.0                                         | 2        | 1.92%   |
| ASRock ALiveNF6P-VSTA                                            | 2        | 1.92%   |
| Supermicro P4DMS                                                 | 1        | 0.96%   |
| MSI Pro 3130 Microtower PC                                       | 1        | 0.96%   |
| MSI MS-7C09                                                      | 1        | 0.96%   |
| MSI MS-7816                                                      | 1        | 0.96%   |
| MSI MS-7788                                                      | 1        | 0.96%   |
| MSI MS-7786                                                      | 1        | 0.96%   |
| MSI MS-7641                                                      | 1        | 0.96%   |
| MSI MS-7592                                                      | 1        | 0.96%   |
| MSI MS-7383                                                      | 1        | 0.96%   |
| MACHINIST X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V309 | 1        | 0.96%   |
| Lenovo ThinkCentre M92p 3238BK7                                  | 1        | 0.96%   |
| Lenovo ThinkCentre M82 3392C4S                                   | 1        | 0.96%   |
| Lenovo ThinkCentre M700 10HYA06700                               | 1        | 0.96%   |
| Intel H61M-DS2                                                   | 1        | 0.96%   |
| Intel H61                                                        | 1        | 0.96%   |
| Intel DP35DP AAD81073-208                                        | 1        | 0.96%   |
| Huanan X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V3.3    | 1        | 0.96%   |
| HP rp5800                                                        | 1        | 0.96%   |
| HP EliteDesk 800 G1 SFF                                          | 1        | 0.96%   |
| HP EliteDesk 705 G3 SFF                                          | 1        | 0.96%   |
| HP dc5000 SFF(DX854AV)                                           | 1        | 0.96%   |
| HP Compaq Pro 6300 SFF                                           | 1        | 0.96%   |
| HP Compaq dc7800p Small Form Factor                              | 1        | 0.96%   |
| HP Compaq dc5700 Microtower                                      | 1        | 0.96%   |
| HP Compaq 6005 Pro MT PC                                         | 1        | 0.96%   |
| HP Compaq 6000 Pro SFF PC                                        | 1        | 0.96%   |
| Gigabyte Z87X-UD4H                                               | 1        | 0.96%   |
| Gigabyte Z790 AORUS ELITE AX DDR4                                | 1        | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 7        | 6.73%   |
| Dell OptiPlex         | 5        | 4.81%   |
| Lenovo ThinkCentre    | 3        | 2.88%   |
| ASUS PRIME            | 3        | 2.88%   |
| MSI MS-7C37           | 2        | 1.92%   |
| MSI MS-7817           | 2        | 1.92%   |
| MSI MS-7721           | 2        | 1.92%   |
| HP EliteDesk          | 2        | 1.92%   |
| Gigabyte Z390         | 2        | 1.92%   |
| Gigabyte Z370         | 2        | 1.92%   |
| Gigabyte H61M-S1      | 2        | 1.92%   |
| ASUS TUF              | 2        | 1.92%   |
| ASRock N68-S          | 2        | 1.92%   |
| ASRock H310CM-HDV     | 2        | 1.92%   |
| ASRock FM2A58M-VG3+   | 2        | 1.92%   |
| ASRock ALiveNF6P-VSTA | 2        | 1.92%   |
| ASRock A320M-HDV      | 2        | 1.92%   |
| Supermicro P4DMS      | 1        | 0.96%   |
| MSI Pro               | 1        | 0.96%   |
| MSI MS-7C09           | 1        | 0.96%   |
| MSI MS-7816           | 1        | 0.96%   |
| MSI MS-7788           | 1        | 0.96%   |
| MSI MS-7786           | 1        | 0.96%   |
| MSI MS-7641           | 1        | 0.96%   |
| MSI MS-7592           | 1        | 0.96%   |
| MSI MS-7383           | 1        | 0.96%   |
| MACHINIST X79         | 1        | 0.96%   |
| Intel H61M-DS2        | 1        | 0.96%   |
| Intel H61             | 1        | 0.96%   |
| Intel DP35DP          | 1        | 0.96%   |
| Huanan X79            | 1        | 0.96%   |
| HP rp5800             | 1        | 0.96%   |
| HP dc5000             | 1        | 0.96%   |
| Gigabyte Z87X-UD4H    | 1        | 0.96%   |
| Gigabyte Z790         | 1        | 0.96%   |
| Gigabyte Z170X-Gaming | 1        | 0.96%   |
| Gigabyte X570         | 1        | 0.96%   |
| Gigabyte H81M-H       | 1        | 0.96%   |
| Gigabyte H81M-DS2     | 1        | 0.96%   |
| Gigabyte H410M        | 1        | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 13       | 12.5%   |
| 2013 | 12       | 11.54%  |
| 2012 | 12       | 11.54%  |
| 2019 | 11       | 10.58%  |
| 2017 | 7        | 6.73%   |
| 2021 | 6        | 5.77%   |
| 2018 | 6        | 5.77%   |
| 2009 | 6        | 5.77%   |
| 2015 | 5        | 4.81%   |
| 2020 | 4        | 3.85%   |
| 2014 | 4        | 3.85%   |
| 2010 | 4        | 3.85%   |
| 2007 | 4        | 3.85%   |
| 2022 | 3        | 2.88%   |
| 2023 | 1        | 0.96%   |
| 2016 | 1        | 0.96%   |
| 2008 | 1        | 0.96%   |
| 2006 | 1        | 0.96%   |
| 2005 | 1        | 0.96%   |
| 2004 | 1        | 0.96%   |
| 2003 | 1        | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 104      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 104      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 104      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 27       | 25.23%  |
| 16.01-24.0  | 20       | 18.69%  |
| 8.01-16.0   | 19       | 17.76%  |
| 3.01-4.0    | 17       | 15.89%  |
| 32.01-64.0  | 8        | 7.48%   |
| 24.01-32.0  | 6        | 5.61%   |
| 1.01-2.0    | 5        | 4.67%   |
| 64.01-256.0 | 3        | 2.8%    |
| 0.51-1.0    | 1        | 0.93%   |
| 0.01-0.5    | 1        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 47       | 41.59%  |
| 2.01-3.0  | 27       | 23.89%  |
| 3.01-4.0  | 16       | 14.16%  |
| 4.01-8.0  | 7        | 6.19%   |
| 0.51-1.0  | 7        | 6.19%   |
| 8.01-16.0 | 5        | 4.42%   |
| 0.01-0.5  | 4        | 3.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 47.22%  |
| 2      | 30       | 27.78%  |
| 3      | 13       | 12.04%  |
| 4      | 10       | 9.26%   |
| 5      | 3        | 2.78%   |
| 7      | 1        | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 56.19%  |
| Yes       | 46       | 43.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 102      | 98.08%  |
| No        | 2        | 1.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 59.43%  |
| Yes       | 43       | 40.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 82.69%  |
| Yes       | 18       | 17.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Uruguay | 104      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Montevideo       | 86       | 80.37%  |
| Maldonado        | 4        | 3.74%   |
| Florida          | 3        | 2.8%    |
| San Jose de Mayo | 2        | 1.87%   |
| Las Piedras      | 2        | 1.87%   |
| Nuevo Paris      | 1        | 0.93%   |
| Nueva Helvecia   | 1        | 0.93%   |
| Minas            | 1        | 0.93%   |
| Melo             | 1        | 0.93%   |
| Malvin Norte     | 1        | 0.93%   |
| La Paz           | 1        | 0.93%   |
| Durazno          | 1        | 0.93%   |
| Ciudad del Plata | 1        | 0.93%   |
| Centro           | 1        | 0.93%   |
| Unknown          | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 49       | 64     | 27.07%  |
| Seagate                     | 31       | 43     | 17.13%  |
| Kingston                    | 24       | 27     | 13.26%  |
| Samsung Electronics         | 21       | 22     | 11.6%   |
| Toshiba                     | 17       | 23     | 9.39%   |
| Crucial                     | 6        | 9      | 3.31%   |
| Maxtor                      | 3        | 4      | 1.66%   |
| Hitachi                     | 3        | 6      | 1.66%   |
| Biostar                     | 3        | 4      | 1.66%   |
| Patriot                     | 2        | 2      | 1.1%    |
| Micron/Crucial Technology   | 2        | 3      | 1.1%    |
| HS-SSD-C100                 | 2        | 3      | 1.1%    |
| Hewlett-Packard             | 2        | 2      | 1.1%    |
| Unknown                     | 1        | 2      | 0.55%   |
| SK hynix                    | 1        | 1      | 0.55%   |
| Silicon Motion              | 1        | 1      | 0.55%   |
| SanDisk                     | 1        | 2      | 0.55%   |
| Realtek Semiconductor       | 1        | 1      | 0.55%   |
| Phison Electronics          | 1        | 1      | 0.55%   |
| Phison                      | 1        | 1      | 0.55%   |
| NGFF                        | 1        | 1      | 0.55%   |
| Netac                       | 1        | 2      | 0.55%   |
| Micron Technology           | 1        | 1      | 0.55%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.55%   |
| IBM-ESXS                    | 1        | 1      | 0.55%   |
| HGST                        | 1        | 1      | 0.55%   |
| Gigabyte Technology         | 1        | 1      | 0.55%   |
| ExcelStor                   | 1        | 1      | 0.55%   |
| A-DATA Technology           | 1        | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 7        | 3.52%   |
| Toshiba DT01ACA300 3TB           | 6        | 3.02%   |
| Toshiba DT01ACA100 1TB           | 6        | 3.02%   |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 2.51%   |
| Samsung HD161HJ 160GB            | 5        | 2.51%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 4        | 2.01%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 2.01%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.51%   |
| Kingston SV300S37A480G 480GB SSD | 3        | 1.51%   |
| Kingston SA400S37480G 480GB SSD  | 3        | 1.51%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 1.51%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 2        | 1.01%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 1.01%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 2        | 1.01%   |
| WDC WD10EFRX-68FYTN0 1TB         | 2        | 1.01%   |
| Seagate ST500DM005 HD502HJ 500GB | 2        | 1.01%   |
| Seagate ST3750640NS 752GB        | 2        | 1.01%   |
| Seagate ST3250312AS 250GB        | 2        | 1.01%   |
| Seagate ST3160318AS 160GB        | 2        | 1.01%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 1.01%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.01%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.01%   |
| Samsung HD103SJ 1TB              | 2        | 1.01%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 1.01%   |
| Kingston SNVS1000G 1TB           | 2        | 1.01%   |
| Kingston SA2000M81000G 1TB       | 2        | 1.01%   |
| Biostar S100-120GB               | 2        | 1.01%   |
| WDC WDS512G1X0C-00ENX0 512GB     | 1        | 0.5%    |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.5%    |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.5%    |
| WDC WDS250G2B0B-00YS70 250GB SSD | 1        | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.5%    |
| WDC WDS100T3X0C-00SJG0 1TB       | 1        | 0.5%    |
| WDC WD800JD-60LSA5 80GB          | 1        | 0.5%    |
| WDC WD5000LPVX-22V0TT0 500GB     | 1        | 0.5%    |
| WDC WD5000LPVT-24G33T1 500GB     | 1        | 0.5%    |
| WDC WD5000BEVT-22A0RT0 500GB     | 1        | 0.5%    |
| WDC WD5000BEKT-60KA9T0 500GB     | 1        | 0.5%    |
| WDC WD5000AZLX-00ZR6A0 500GB     | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 42       | 53     | 37.17%  |
| Seagate             | 31       | 43     | 27.43%  |
| Toshiba             | 17       | 23     | 15.04%  |
| Samsung Electronics | 15       | 15     | 13.27%  |
| Maxtor              | 3        | 4      | 2.65%   |
| Hitachi             | 3        | 6      | 2.65%   |
| HGST                | 1        | 1      | 0.88%   |
| ExcelStor           | 1        | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 20       | 22     | 44.44%  |
| WDC                 | 7        | 8      | 15.56%  |
| Crucial             | 5        | 6      | 11.11%  |
| Samsung Electronics | 3        | 4      | 6.67%   |
| Biostar             | 2        | 3      | 4.44%   |
| Patriot             | 1        | 1      | 2.22%   |
| NGFF                | 1        | 1      | 2.22%   |
| Netac               | 1        | 2      | 2.22%   |
| Micron Technology   | 1        | 1      | 2.22%   |
| HS-SSD-C100         | 1        | 1      | 2.22%   |
| Hewlett-Packard     | 1        | 1      | 2.22%   |
| Gigabyte Technology | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 83       | 146    | 55.7%   |
| SSD     | 44       | 52     | 29.53%  |
| NVMe    | 18       | 28     | 12.08%  |
| Unknown | 4        | 6      | 2.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 99       | 200    | 82.5%   |
| NVMe | 18       | 28     | 15%     |
| SAS  | 3        | 4      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 79       | 112    | 59.85%  |
| 0.51-1.0   | 37       | 66     | 28.03%  |
| 2.01-3.0   | 8        | 10     | 6.06%   |
| 1.01-2.0   | 5        | 6      | 3.79%   |
| 3.01-4.0   | 3        | 4      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 29       | 26.36%  |
| 251-500        | 22       | 20%     |
| 1-20           | 13       | 11.82%  |
| 501-1000       | 13       | 11.82%  |
| 1001-2000      | 12       | 10.91%  |
| 21-50          | 5        | 4.55%   |
| 2001-3000      | 5        | 4.55%   |
| Unknown        | 5        | 4.55%   |
| 51-100         | 4        | 3.64%   |
| More than 3000 | 2        | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 43       | 39.09%  |
| 21-50     | 17       | 15.45%  |
| 101-250   | 11       | 10%     |
| 51-100    | 10       | 9.09%   |
| 501-1000  | 9        | 8.18%   |
| 251-500   | 6        | 5.45%   |
| 1001-2000 | 6        | 5.45%   |
| Unknown   | 5        | 4.55%   |
| 2001-3000 | 3        | 2.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 2        | 2      | 9.52%   |
| Seagate ST3750640NS 752GB        | 2        | 7      | 9.52%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 2      | 9.52%   |
| WDC WD5000BEKT-60KA9T0 500GB     | 1        | 1      | 4.76%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 1      | 4.76%   |
| WDC WD5000AAJS-00A8B0 500GB      | 1        | 1      | 4.76%   |
| WDC WD10EARS-22Y5B1 1TB          | 1        | 1      | 4.76%   |
| Toshiba MQ01ABD075 752GB         | 1        | 1      | 4.76%   |
| Toshiba MK5059GSXP 500GB         | 1        | 1      | 4.76%   |
| Toshiba MK3276GSX 320GB          | 1        | 1      | 4.76%   |
| Toshiba DT01ACA100 1TB           | 1        | 1      | 4.76%   |
| Seagate ST500LM021-1KJ152 500GB  | 1        | 1      | 4.76%   |
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 4.76%   |
| Seagate ST3250310CS 250GB        | 1        | 1      | 4.76%   |
| Seagate ST3200827AS 200GB        | 1        | 1      | 4.76%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 1      | 4.76%   |
| Kingston SA400S37480G 480GB SSD  | 1        | 1      | 4.76%   |
| HS-SSD-C100 SSD 240G             | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 10       | 16     | 50%     |
| WDC         | 4        | 4      | 20%     |
| Toshiba     | 4        | 4      | 20%     |
| Kingston    | 1        | 1      | 5%      |
| HS-SSD-C100 | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 16     | 55.56%  |
| WDC     | 4        | 4      | 22.22%  |
| Toshiba | 4        | 4      | 22.22%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 24     | 90%     |
| SSD  | 2        | 2      | 10%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 59       | 128    | 49.17%  |
| Works    | 41       | 78     | 34.17%  |
| Malfunc  | 20       | 26     | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 65       | 48.51%  |
| AMD                         | 32       | 23.88%  |
| Nvidia                      | 6        | 4.48%   |
| ASMedia Technology          | 5        | 3.73%   |
| SanDisk                     | 4        | 2.99%   |
| Kingston Technology Company | 4        | 2.99%   |
| Silicon Motion              | 3        | 2.24%   |
| Samsung Electronics         | 3        | 2.24%   |
| Micron/Crucial Technology   | 3        | 2.24%   |
| Phison Electronics          | 2        | 1.49%   |
| Marvell Technology Group    | 2        | 1.49%   |
| VIA Technologies            | 1        | 0.75%   |
| SK hynix                    | 1        | 0.75%   |
| Realtek Semiconductor       | 1        | 0.75%   |
| MAXIO Technology (Hangzhou) | 1        | 0.75%   |
| Adaptec                     | 1        | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 10.29%  |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 4.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 4%      |
| Nvidia MCP61 SATA Controller                                                            | 6        | 3.43%   |
| Nvidia MCP61 IDE                                                                        | 5        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.86%   |
| AMD FCH IDE Controller                                                                  | 5        | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 2.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.71%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.71%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 1.14%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2        | 1.14%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 1.14%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                                  | 2        | 1.14%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2        | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.14%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.14%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.57%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 0.57%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                             | 1        | 0.57%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.57%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 0.57%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 81       | 58.27%  |
| IDE  | 35       | 25.18%  |
| NVMe | 18       | 12.95%  |
| RAID | 4        | 2.88%   |
| SCSI | 1        | 0.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 65       | 62.5%   |
| AMD    | 39       | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 3        | 2.88%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 3        | 2.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 2        | 1.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 2        | 1.92%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 2        | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 2        | 1.92%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 2        | 1.92%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 2        | 1.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 2        | 1.92%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 1.92%   |
| AMD Phenom II X6 1055T Processor                | 2        | 1.92%   |
| AMD Athlon II X2 250 Processor                  | 2        | 1.92%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 2        | 1.92%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 2        | 1.92%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz              | 1        | 0.96%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz              | 1        | 0.96%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1        | 0.96%   |
| Intel Xeon CPU 2.40GHz                          | 1        | 0.96%   |
| Intel Pentium CPU G870 @ 3.10GHz                | 1        | 0.96%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 0.96%   |
| Intel Pentium 4 CPU 2.80GHz                     | 1        | 0.96%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 1        | 0.96%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 0.96%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 0.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 0.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 0.96%   |
| Intel Core i7-4930K CPU @ 3.40GHz               | 1        | 0.96%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 0.96%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 0.96%   |
| Intel Core i7-10700F CPU @ 2.90GHz              | 1        | 0.96%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 0.96%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 0.96%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 0.96%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1        | 0.96%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 0.96%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1        | 0.96%   |
| Intel Core i5-3570S CPU @ 3.10GHz               | 1        | 0.96%   |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 0.96%   |
| Intel Core i5-2500S CPU @ 2.70GHz               | 1        | 0.96%   |
| Intel Core i5-2400S CPU @ 2.50GHz               | 1        | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 18       | 17.31%  |
| Intel Core i3     | 13       | 12.5%   |
| Intel Core i7     | 12       | 11.54%  |
| AMD Ryzen 5       | 7        | 6.73%   |
| Intel Core 2 Duo  | 6        | 5.77%   |
| AMD Ryzen 7       | 5        | 4.81%   |
| AMD Athlon II X2  | 5        | 4.81%   |
| Intel Xeon        | 4        | 3.85%   |
| Intel Celeron     | 4        | 3.85%   |
| Intel Core 2 Quad | 3        | 2.88%   |
| AMD Phenom II X6  | 3        | 2.88%   |
| AMD FX            | 3        | 2.88%   |
| AMD A10           | 3        | 2.88%   |
| Intel Pentium     | 2        | 1.92%   |
| AMD Ryzen 3       | 2        | 1.92%   |
| AMD Athlon        | 2        | 1.92%   |
| AMD A6            | 2        | 1.92%   |
| AMD A4            | 2        | 1.92%   |
| Other             | 1        | 0.96%   |
| Intel Pentium 4   | 1        | 0.96%   |
| Intel Core i9     | 1        | 0.96%   |
| AMD PRO A10       | 1        | 0.96%   |
| AMD Phenom        | 1        | 0.96%   |
| AMD Athlon 64 X2  | 1        | 0.96%   |
| AMD Athlon 64     | 1        | 0.96%   |
| AMD A8            | 1        | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 40       | 38.46%  |
| 4      | 30       | 28.85%  |
| 6      | 20       | 19.23%  |
| 8      | 9        | 8.65%   |
| 1      | 4        | 3.85%   |
| 14     | 1        | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 103      | 99.04%  |
| 2      | 1        | 0.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 59       | 56.73%  |
| 1      | 45       | 43.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 101      | 97.12%  |
| 32-bit         | 2        | 1.92%   |
| Unknown        | 1        | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 30.28%  |
| 0x206a7    | 7        | 6.42%   |
| 0x306c3    | 6        | 5.5%    |
| 0x306a9    | 6        | 5.5%    |
| 0x906ea    | 5        | 4.59%   |
| 0x1067a    | 5        | 4.59%   |
| 0x08701021 | 4        | 3.67%   |
| 0x06000852 | 3        | 2.75%   |
| 0xa0655    | 2        | 1.83%   |
| 0xa0653    | 2        | 1.83%   |
| 0x506e3    | 2        | 1.83%   |
| 0x206d7    | 2        | 1.83%   |
| 0x20655    | 2        | 1.83%   |
| 0x08108109 | 2        | 1.83%   |
| 0x08001138 | 2        | 1.83%   |
| 0x06003106 | 2        | 1.83%   |
| 0x06001119 | 2        | 1.83%   |
| 0x010000dc | 2        | 1.83%   |
| 0xf33      | 1        | 0.92%   |
| 0xf27      | 1        | 0.92%   |
| 0x906ed    | 1        | 0.92%   |
| 0x906ec    | 1        | 0.92%   |
| 0x906eb    | 1        | 0.92%   |
| 0x906c0    | 1        | 0.92%   |
| 0x6fd      | 1        | 0.92%   |
| 0x10677    | 1        | 0.92%   |
| 0x10676    | 1        | 0.92%   |
| 0x0a50000d | 1        | 0.92%   |
| 0x0a50000c | 1        | 0.92%   |
| 0x08108102 | 1        | 0.92%   |
| 0x0800820d | 1        | 0.92%   |
| 0x08001137 | 1        | 0.92%   |
| 0x0600611a | 1        | 0.92%   |
| 0x03000027 | 1        | 0.92%   |
| 0x010000c8 | 1        | 0.92%   |
| 0x010000b6 | 1        | 0.92%   |
| 0x01000083 | 1        | 0.92%   |
| 0x00000000 | 1        | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 12       | 11.54%  |
| SandyBridge | 11       | 10.58%  |
| KabyLake    | 9        | 8.65%   |
| K10         | 9        | 8.65%   |
| Haswell     | 9        | 8.65%   |
| Penryn      | 7        | 6.73%   |
| CometLake   | 6        | 5.77%   |
| Zen+        | 5        | 4.81%   |
| Piledriver  | 5        | 4.81%   |
| Zen 3       | 4        | 3.85%   |
| Zen 2       | 4        | 3.85%   |
| Steamroller | 4        | 3.85%   |
| Zen         | 3        | 2.88%   |
| Skylake     | 3        | 2.88%   |
| Westmere    | 2        | 1.92%   |
| NetBurst    | 2        | 1.92%   |
| K8 Hammer   | 2        | 1.92%   |
| Core        | 2        | 1.92%   |
| Tremont     | 1        | 0.96%   |
| K10 Llano   | 1        | 0.96%   |
| Jaguar      | 1        | 0.96%   |
| Excavator   | 1        | 0.96%   |
| Unknown     | 1        | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 46       | 41.44%  |
| Intel  | 37       | 33.33%  |
| AMD    | 28       | 25.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 7.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 4.42%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 3.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.54%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 3.54%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 2.65%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 2.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 2.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.77%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.77%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.77%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.77%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 1.77%   |
| Intel HD Graphics 530                                                       | 2        | 1.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.77%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.88%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.88%   |
| Nvidia NV34 [GeForce FX 5200]                                               | 1        | 0.88%   |
| Nvidia GT216 [GeForce 210]                                                  | 1        | 0.88%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.88%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.88%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.88%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.88%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.88%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.88%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.88%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 0.88%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 43       | 40.95%  |
| 1 x Intel      | 31       | 29.52%  |
| 1 x AMD        | 25       | 23.81%  |
| 2 x AMD        | 2        | 1.9%    |
| Intel + Nvidia | 2        | 1.9%    |
| Other          | 1        | 0.95%   |
| AMD + Nvidia   | 1        | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 81       | 76.42%  |
| Proprietary | 17       | 16.04%  |
| Unknown     | 8        | 7.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 43.52%  |
| 1.01-2.0   | 18       | 16.67%  |
| 0.51-1.0   | 15       | 13.89%  |
| 0.01-0.5   | 11       | 10.19%  |
| 3.01-4.0   | 9        | 8.33%   |
| 7.01-8.0   | 3        | 2.78%   |
| 5.01-6.0   | 3        | 2.78%   |
| 2.01-3.0   | 1        | 0.93%   |
| 8.01-16.0  | 1        | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AOC                     | 18       | 19.15%  |
| ViewSonic               | 14       | 14.89%  |
| Samsung Electronics     | 13       | 13.83%  |
| KTC                     | 8        | 8.51%   |
| Goldstar                | 8        | 8.51%   |
| Acer                    | 5        | 5.32%   |
| Unknown                 | 4        | 4.26%   |
| Hewlett-Packard         | 4        | 4.26%   |
| Lenovo                  | 3        | 3.19%   |
| Dell                    | 2        | 2.13%   |
| Ancor Communications    | 2        | 2.13%   |
| Sony                    | 1        | 1.06%   |
| RIS                     | 1        | 1.06%   |
| Philips                 | 1        | 1.06%   |
| Panasonic               | 1        | 1.06%   |
| LG Electronics          | 1        | 1.06%   |
| Lenovo Group Limited    | 1        | 1.06%   |
| KOA                     | 1        | 1.06%   |
| HKC                     | 1        | 1.06%   |
| Hitachi                 | 1        | 1.06%   |
| Envision                | 1        | 1.06%   |
| CVT                     | 1        | 1.06%   |
| Chi Mei Optoelectronics | 1        | 1.06%   |
| BenQ                    | 1        | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                  | 3        | 3%      |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch            | 2        | 2%      |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 2        | 2%      |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                      | 2        | 2%      |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch   | 2        | 2%      |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 2        | 2%      |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch              | 2        | 2%      |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                      | 2        | 2%      |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 2        | 2%      |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 2%      |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 2        | 2%      |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                        | 2        | 2%      |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch                | 1        | 1%      |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch         | 1        | 1%      |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1        | 1%      |
| ViewSonic VX2240w VSC6B20 1680x1050 495x291mm 22.6-inch               | 1        | 1%      |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch               | 1        | 1%      |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1        | 1%      |
| ViewSonic VA702b VSC231C 1280x1024 338x270mm 17.0-inch                | 1        | 1%      |
| ViewSonic VA2415-FHD VSC533C 1920x1080 527x296mm 23.8-inch            | 1        | 1%      |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch         | 1        | 1%      |
| ViewSonic VA1903a VSC8A31 1366x768 410x230mm 18.5-inch                | 1        | 1%      |
| ViewSonic LCD Monitor VX2240w 3600x1080                               | 1        | 1%      |
| ViewSonic LCD Monitor VA2261                                          | 1        | 1%      |
| Unknown LCD Monitor XXX AAA 1920x1080                                 | 1        | 1%      |
| Unknown LCD Monitor RTK 2944x1080                                     | 1        | 1%      |
| Sony LCD Monitor TV                                                   | 1        | 1%      |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch  | 1        | 1%      |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 1%      |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch    | 1        | 1%      |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 1%      |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1        | 1%      |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 410x230mm 18.5-inch | 1        | 1%      |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch     | 1        | 1%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1%      |
| RIS HD915L RIS0709 1360x768 410x230mm 18.5-inch                       | 1        | 1%      |
| Philips PHL 272V8 PHLC21A 1920x1080 598x336mm 27.0-inch               | 1        | 1%      |
| Panasonic LCD Monitor TV                                              | 1        | 1%      |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                     | 1        | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 36.96%  |
| 1366x768 (WXGA)    | 12       | 13.04%  |
| 1600x900 (HD+)     | 6        | 6.52%   |
| 1280x1024 (SXGA)   | 6        | 6.52%   |
| Unknown            | 5        | 5.43%   |
| 3840x2160 (4K)     | 4        | 4.35%   |
| 2560x1440 (QHD)    | 4        | 4.35%   |
| 1680x1050 (WSXGA+) | 4        | 4.35%   |
| 1440x900 (WXGA+)   | 4        | 4.35%   |
| 1360x768           | 4        | 4.35%   |
| 2960x900           | 2        | 2.17%   |
| 1280x720 (HD)      | 2        | 2.17%   |
| 3600x1080          | 1        | 1.09%   |
| 3440x1440          | 1        | 1.09%   |
| 2944x1080          | 1        | 1.09%   |
| 2560x1080          | 1        | 1.09%   |
| 1280x768           | 1        | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 14       | 15.05%  |
| 21      | 14       | 15.05%  |
| 18      | 11       | 11.83%  |
| Unknown | 10       | 10.75%  |
| 19      | 6        | 6.45%   |
| 15      | 6        | 6.45%   |
| 24      | 5        | 5.38%   |
| 17      | 5        | 5.38%   |
| 20      | 4        | 4.3%    |
| 32      | 3        | 3.23%   |
| 31      | 3        | 3.23%   |
| 84      | 2        | 2.15%   |
| 44      | 2        | 2.15%   |
| 34      | 2        | 2.15%   |
| 27      | 2        | 2.15%   |
| 22      | 2        | 2.15%   |
| 48      | 1        | 1.08%   |
| 16      | 1        | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 34       | 37.36%  |
| 501-600     | 19       | 20.88%  |
| Unknown     | 10       | 10.99%  |
| 301-350     | 9        | 9.89%   |
| 351-400     | 6        | 6.59%   |
| 701-800     | 5        | 5.49%   |
| 601-700     | 3        | 3.3%    |
| 1501-2000   | 2        | 2.2%    |
| 901-1000    | 2        | 2.2%    |
| 1001-1500   | 1        | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 60       | 69.77%  |
| Unknown | 10       | 11.63%  |
| 16/10   | 8        | 9.3%    |
| 5/4     | 6        | 6.98%   |
| 21/9    | 2        | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 30.34%  |
| 151-200        | 17       | 19.1%   |
| 141-150        | 11       | 12.36%  |
| Unknown        | 10       | 11.24%  |
| 351-500        | 7        | 7.87%   |
| 101-110        | 5        | 5.62%   |
| More than 1000 | 3        | 3.37%   |
| 301-350        | 2        | 2.25%   |
| 131-140        | 2        | 2.25%   |
| 501-1000       | 2        | 2.25%   |
| 251-300        | 1        | 1.12%   |
| 121-130        | 1        | 1.12%   |
| 91-100         | 1        | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 56       | 64.37%  |
| 101-120 | 14       | 16.09%  |
| Unknown | 10       | 11.49%  |
| 1-50    | 4        | 4.6%    |
| 121-160 | 2        | 2.3%    |
| 161-240 | 1        | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 79       | 73.83%  |
| 2     | 17       | 15.89%  |
| 0     | 10       | 9.35%   |
| 4     | 1        | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 62       | 42.18%  |
| Intel                 | 37       | 25.17%  |
| Qualcomm Atheros      | 12       | 8.16%   |
| Ralink Technology     | 7        | 4.76%   |
| TP-Link               | 6        | 4.08%   |
| Nvidia                | 6        | 4.08%   |
| Broadcom              | 4        | 2.72%   |
| Xiaomi                | 2        | 1.36%   |
| Mercucys              | 2        | 1.36%   |
| Huawei Technologies   | 2        | 1.36%   |
| Broadcom Limited      | 2        | 1.36%   |
| VIA Technologies      | 1        | 0.68%   |
| Texas Instruments     | 1        | 0.68%   |
| Samsung Electronics   | 1        | 0.68%   |
| Ralink                | 1        | 0.68%   |
| Qualcomm              | 1        | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 52       | 31.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 9        | 5.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 6        | 3.59%   |
| Nvidia MCP61 Ethernet                                                                         | 6        | 3.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                                          | 4        | 2.4%    |
| TP-Link 802.11ac NIC                                                                          | 3        | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                                             | 3        | 1.8%    |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 1.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 3        | 1.8%    |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 1.8%    |
| Intel Ethernet Connection (7) I219-V                                                          | 3        | 1.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.2%    |
| Realtek 802.11ac NIC                                                                          | 2        | 1.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 1.2%    |
| Mercucys 802.11n NIC                                                                          | 2        | 1.2%    |
| Intel I211 Gigabit Network Connection                                                         | 2        | 1.2%    |
| Intel Ethernet Connection I217-LM                                                             | 2        | 1.2%    |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 1.2%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                          | 2        | 1.2%    |
| Huawei E353/E3131                                                                             | 2        | 1.2%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 2        | 1.2%    |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 0.6%    |
| VIA AC'97 Modem Controller                                                                    | 1        | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.6%    |
| Texas Instruments CC2531 ZigBee                                                               | 1        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1        | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.6%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.6%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                      | 1        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1        | 0.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 1        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.6%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.6%    |
| Ralink RT2070 Wireless Adapter                                                                | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 39.58%  |
| Ralink Technology     | 7        | 14.58%  |
| Intel                 | 7        | 14.58%  |
| TP-Link               | 6        | 12.5%   |
| Qualcomm Atheros      | 4        | 8.33%   |
| Mercucys              | 2        | 4.17%   |
| Broadcom              | 2        | 4.17%   |
| Ralink                | 1        | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 6        | 12.5%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 8.33%   |
| TP-Link 802.11ac NIC                                                                          | 3        | 6.25%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 6.25%   |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 6.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 4.17%   |
| Realtek 802.11ac NIC                                                                          | 2        | 4.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 4.17%   |
| Mercucys 802.11n NIC                                                                          | 2        | 4.17%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 2        | 4.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 2.08%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.08%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 2.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 2.08%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 2.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 2.08%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                      | 1        | 2.08%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.08%   |
| Ralink RT2070 Wireless Adapter                                                                | 1        | 2.08%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 2.08%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 2.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 2.08%   |
| Intel Wireless 8260                                                                           | 1        | 2.08%   |
| Intel Wireless 3165                                                                           | 1        | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 2.08%   |
| Intel 700 Series Chipset Family Wi-Fi                                                         | 1        | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 57       | 49.57%  |
| Intel                 | 33       | 28.7%   |
| Qualcomm Atheros      | 8        | 6.96%   |
| Nvidia                | 6        | 5.22%   |
| Xiaomi                | 2        | 1.74%   |
| Huawei Technologies   | 2        | 1.74%   |
| Broadcom Limited      | 2        | 1.74%   |
| Broadcom              | 2        | 1.74%   |
| VIA Technologies      | 1        | 0.87%   |
| Samsung Electronics   | 1        | 0.87%   |
| Qualcomm              | 1        | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 44.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 7.69%   |
| Nvidia MCP61 Ethernet                                             | 6        | 5.13%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 3.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 2.56%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.71%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.71%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.71%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 1.71%   |
| Huawei E353/E3131                                                 | 2        | 1.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.85%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 1        | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.85%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.85%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.85%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.85%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.85%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.85%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.85%   |
| Intel 82544GC Gigabit Ethernet Controller (LOM)                   | 1        | 0.85%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.85%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 1        | 0.85%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 102      | 69.39%  |
| WiFi     | 43       | 29.25%  |
| Modem    | 2        | 1.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 73.08%  |
| WiFi     | 28       | 26.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 76.92%  |
| 2     | 20       | 19.23%  |
| 3     | 2        | 1.92%   |
| 0     | 2        | 1.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 63.21%  |
| Yes  | 39       | 36.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 38.89%  |
| Cambridge Silicon Radio         | 7        | 38.89%  |
| Realtek Semiconductor           | 2        | 11.11%  |
| TP-Link                         | 1        | 5.56%   |
| Qualcomm Atheros Communications | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 38.89%  |
| Intel AX200 Bluetooth                               | 3        | 16.67%  |
| Realtek Bluetooth Radio                             | 2        | 11.11%  |
| Intel Bluetooth wireless interface                  | 2        | 11.11%  |
| TP-Link UB500 Adapter                               | 1        | 5.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.56%   |
| Intel Bluetooth Device                              | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 64       | 39.26%  |
| Nvidia                 | 43       | 26.38%  |
| AMD                    | 35       | 21.47%  |
| Logitech               | 4        | 2.45%   |
| VIA Technologies       | 2        | 1.23%   |
| Samson Technologies    | 2        | 1.23%   |
| Focusrite-Novation     | 2        | 1.23%   |
| Creative Labs          | 2        | 1.23%   |
| C-Media Electronics    | 2        | 1.23%   |
| Texas Instruments      | 1        | 0.61%   |
| Rockwell International | 1        | 0.61%   |
| KTMicro                | 1        | 0.61%   |
| Kingston Technology    | 1        | 0.61%   |
| JMTek                  | 1        | 0.61%   |
| Elgato Systems         | 1        | 0.61%   |
| Creative Technology    | 1        | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 13       | 6.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 9        | 4.69%   |
| AMD FCH Azalia Controller                                                                       | 8        | 4.17%   |
| Nvidia High Definition Audio Controller                                                         | 7        | 3.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 7        | 3.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 7        | 3.65%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 7        | 3.65%   |
| Nvidia MCP61 High Definition Audio                                                              | 6        | 3.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 5        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 5        | 2.6%    |
| Intel 200 Series PCH HD Audio                                                                   | 5        | 2.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 4        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                      | 4        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 4        | 2.08%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 3        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 3        | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 3        | 1.56%   |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 3        | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 3        | 1.56%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 3        | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3        | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 3        | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 3        | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 2        | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 2        | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 2        | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 2        | 1.04%   |
| Nvidia GA106 High Definition Audio Controller                                                   | 2        | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 2        | 1.04%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 2        | 1.04%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 2        | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 2        | 1.04%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2        | 1.04%   |
| AMD Navi 10 HDMI Audio                                                                          | 2        | 1.04%   |
| AMD Kaveri HDMI/DP Audio Controller                                                             | 2        | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                                        | 2        | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 2        | 1.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 2        | 1.04%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                       | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 16       | 20.51%  |
| Crucial                      | 13       | 16.67%  |
| Unknown                      | 9        | 11.54%  |
| Samsung Electronics          | 6        | 7.69%   |
| Micron Technology            | 5        | 6.41%   |
| SK hynix                     | 4        | 5.13%   |
| Hikvision                    | 3        | 3.85%   |
| Team                         | 2        | 2.56%   |
| Patriot                      | 2        | 2.56%   |
| Nanya Technology             | 2        | 2.56%   |
| Corsair                      | 2        | 2.56%   |
| A-DATA Technology            | 2        | 2.56%   |
| Unknown (89F7)               | 1        | 1.28%   |
| Unknown (2C0B)               | 1        | 1.28%   |
| Unknown (0x5846)             | 1        | 1.28%   |
| Smart                        | 1        | 1.28%   |
| Patriot Memory (PDP Systems) | 1        | 1.28%   |
| Netac                        | 1        | 1.28%   |
| KLEVV                        | 1        | 1.28%   |
| Infineon                     | 1        | 1.28%   |
| GeIL                         | 1        | 1.28%   |
| Elpida                       | 1        | 1.28%   |
| Avant                        | 1        | 1.28%   |
| Unknown                      | 1        | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s               | 3        | 3.61%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s                | 3        | 3.61%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s                  | 2        | 2.41%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                            | 1        | 1.2%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                            | 1        | 1.2%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                                 | 1        | 1.2%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                                 | 1        | 1.2%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                         | 1        | 1.2%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                              | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                         | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                              | 1        | 1.2%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                             | 1        | 1.2%    |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s               | 1        | 1.2%    |
| Unknown (89F7) RAM Module 8GB DIMM DDR3 1600MT/s                     | 1        | 1.2%    |
| Unknown (2C0B) RAM Module 8GB DIMM DDR4 2400MT/s                     | 1        | 1.2%    |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s        | 1        | 1.2%    |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s                | 1        | 1.2%    |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                           | 1        | 1.2%    |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s                  | 1        | 1.2%    |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                           | 1        | 1.2%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s            | 1        | 1.2%    |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s                 | 1        | 1.2%    |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s                 | 1        | 1.2%    |
| Samsung RAM Module 4GB DIMM DDR3 1066MT/s                            | 1        | 1.2%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                | 1        | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                | 1        | 1.2%    |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s                      | 1        | 1.2%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                  | 1        | 1.2%    |
| Samsung RAM M378B5673EH1-CF8 2GB DIMM DDR3 1067MT/s                  | 1        | 1.2%    |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                  | 1        | 1.2%    |
| Patriot RAM PSD48G320081 8GB DIMM DDR4 3200MT/s                      | 1        | 1.2%    |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s                     | 1        | 1.2%    |
| Patriot Memory (PDP Systems) RAM PSD48G266681 8GB DIMM DDR4 2667MT/s | 1        | 1.2%    |
| Netac RAM Module 16GB DIMM DDR4 2667MT/s                             | 1        | 1.2%    |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                   | 1        | 1.2%    |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1600MT/s                   | 1        | 1.2%    |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                             | 1        | 1.2%    |
| Micron RAM 8KTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s                  | 1        | 1.2%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                  | 1        | 1.2%    |
| KLEVV RAM KD48GU880-32A160U 8GB DIMM DDR4 3800MT/s                   | 1        | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 29       | 49.15%  |
| DDR4    | 24       | 40.68%  |
| Unknown | 3        | 5.08%   |
| SDRAM   | 1        | 1.69%   |
| DDR2    | 1        | 1.69%   |
| DDR     | 1        | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 54       | 93.1%   |
| SODIMM | 3        | 5.17%   |
| RIMM   | 1        | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 24       | 32.43%  |
| 4096  | 19       | 25.68%  |
| 16384 | 15       | 20.27%  |
| 2048  | 11       | 14.86%  |
| 32768 | 3        | 4.05%   |
| 1024  | 1        | 1.35%   |
| 256   | 1        | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 15       | 21.74%  |
| 1333  | 14       | 20.29%  |
| 2667  | 9        | 13.04%  |
| 3600  | 4        | 5.8%    |
| 3200  | 3        | 4.35%   |
| 2133  | 3        | 4.35%   |
| 3800  | 2        | 2.9%    |
| 3000  | 2        | 2.9%    |
| 2400  | 2        | 2.9%    |
| 3733  | 1        | 1.45%   |
| 3500  | 1        | 1.45%   |
| 3466  | 1        | 1.45%   |
| 3400  | 1        | 1.45%   |
| 2666  | 1        | 1.45%   |
| 2473  | 1        | 1.45%   |
| 2176  | 1        | 1.45%   |
| 1867  | 1        | 1.45%   |
| 1866  | 1        | 1.45%   |
| 1800  | 1        | 1.45%   |
| 1067  | 1        | 1.45%   |
| 1066  | 1        | 1.45%   |
| 533   | 1        | 1.45%   |
| 333   | 1        | 1.45%   |
| 266   | 1        | 1.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Xerox              | 1        | 33.33%  |
| Hewlett-Packard    | 1        | 33.33%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Xerox Phaser 3040 | 1        | 25%     |
| HP Laser 107a     | 1        | 25%     |
| Brother DCP-T500W | 1        | 25%     |
| Brother DCP-T420W | 1        | 25%     |

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
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 8        | 44.44%  |
| Apple                                  | 2        | 11.11%  |
| Unknown                                | 1        | 5.56%   |
| Sony                                   | 1        | 5.56%   |
| Samsung Electronics                    | 1        | 5.56%   |
| Microdia                               | 1        | 5.56%   |
| GEMBIRD                                | 1        | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 5.56%   |
| Aveo Technology                        | 1        | 5.56%   |
| A4Tech                                 | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 2        | 11.11%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 2        | 11.11%  |
| Unknown HD camera                                 | 1        | 5.56%   |
| Sony CEVCECM                                      | 1        | 5.56%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1        | 5.56%   |
| Microdia USB 2.0 Camera                           | 1        | 5.56%   |
| Logitech Webcam C930e                             | 1        | 5.56%   |
| Logitech Webcam C925e                             | 1        | 5.56%   |
| Logitech Webcam C170                              | 1        | 5.56%   |
| Logitech Webcam C110                              | 1        | 5.56%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 5.56%   |
| Logitech C505e HD Webcam                          | 1        | 5.56%   |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) FS13FF-183 | 1        | 5.56%   |
| Aveo USB2.0 Camera                                | 1        | 5.56%   |
| A4Tech HD 720P PC Camera                          | 1        | 5.56%   |

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
| 0     | 87       | 81.31%  |
| 1     | 17       | 15.89%  |
| 2     | 2        | 1.87%   |
| 3     | 1        | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 9        | 40.91%  |
| Net/wireless             | 8        | 36.36%  |
| Unassigned class         | 2        | 9.09%   |
| Sound                    | 2        | 9.09%   |
| Communication controller | 1        | 4.55%   |

