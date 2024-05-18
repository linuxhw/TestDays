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

Total: 178

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock     | Z68 Pro3 Gen3               | [2e1897982e](https://linux-hardware.org/?probe=2e1897982e) | Apr 24, 2024 |
| ASRock     | Z68 Pro3 Gen3               | [2383a2962f](https://linux-hardware.org/?probe=2383a2962f) | Apr 24, 2024 |
| ASUSTek    | H81M-E                      | [7af65eace4](https://linux-hardware.org/?probe=7af65eace4) | Apr 13, 2024 |
| ASRock     | H510M-HDV R2.0              | [5b213df28c](https://linux-hardware.org/?probe=5b213df28c) | Apr 12, 2024 |
| ASUSTek    | TUF Gaming B650M-PLUS WI... | [75f2fd247a](https://linux-hardware.org/?probe=75f2fd247a) | Apr 08, 2024 |
| Dell       | 0V8WGR A02                  | [c8eb38c52c](https://linux-hardware.org/?probe=c8eb38c52c) | Apr 07, 2024 |
| Dell       | 0CU395                      | [0ba3773be8](https://linux-hardware.org/?probe=0ba3773be8) | Apr 03, 2024 |
| Dell       | 0XFWHV A00                  | [ea24de6920](https://linux-hardware.org/?probe=ea24de6920) | Apr 02, 2024 |
| ASRock     | B75M                        | [de41218e15](https://linux-hardware.org/?probe=de41218e15) | Mar 30, 2024 |
| Lenovo     | MAHOBAY                     | [e55de04b3d](https://linux-hardware.org/?probe=e55de04b3d) | Mar 28, 2024 |
| ASUSTek    | TUF Gaming B650M-PLUS WI... | [40f761e062](https://linux-hardware.org/?probe=40f761e062) | Mar 14, 2024 |
| Gigabyte   | B450M DS3H V2               | [d74df494d7](https://linux-hardware.org/?probe=d74df494d7) | Mar 12, 2024 |
| Gigabyte   | B450M DS3H V2               | [e31b3a8c12](https://linux-hardware.org/?probe=e31b3a8c12) | Mar 08, 2024 |
| ASUSTek    | TUF Gaming B650M-PLUS WI... | [cc638a70e5](https://linux-hardware.org/?probe=cc638a70e5) | Feb 21, 2024 |
| Gigabyte   | B450M DS3H V2               | [a78e0bbe6b](https://linux-hardware.org/?probe=a78e0bbe6b) | Feb 10, 2024 |
| Gigabyte   | B550M K                     | [39f7c51de0](https://linux-hardware.org/?probe=39f7c51de0) | Jan 05, 2024 |
| Gigabyte   | H310M A-CF                  | [cdf7a1ffd4](https://linux-hardware.org/?probe=cdf7a1ffd4) | Dec 15, 2023 |
| ASRock     | 760GM-HDV                   | [c1403f5d52](https://linux-hardware.org/?probe=c1403f5d52) | Dec 15, 2023 |
| ASUSTek    | PRIME A320M-K               | [58e1501577](https://linux-hardware.org/?probe=58e1501577) | Dec 06, 2023 |
| ASRock     | H110M-DVS R3.0              | [21e6cb8e9b](https://linux-hardware.org/?probe=21e6cb8e9b) | Dec 05, 2023 |
| Dell       | 0V8WGR A01                  | [b44e627796](https://linux-hardware.org/?probe=b44e627796) | Nov 26, 2023 |
| MSI        | H310M PRO-VDH PLUS          | [6cdf6e663e](https://linux-hardware.org/?probe=6cdf6e663e) | Nov 26, 2023 |
| HP         | 1495                        | [9f7eca2710](https://linux-hardware.org/?probe=9f7eca2710) | Nov 17, 2023 |
| HP         | 1495                        | [9a299e543d](https://linux-hardware.org/?probe=9a299e543d) | Nov 16, 2023 |
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
| ASRock     | Z68 Pro3 Gen3               | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
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
| Ubuntu 20.04       | 12       | 9.3%    |
| OpenMandriva 4.3   | 11       | 8.53%   |
| Manjaro            | 9        | 6.98%   |
| Ubuntu 18.04       | 7        | 5.43%   |
| ArcoLinux Rolling  | 7        | 5.43%   |
| Xubuntu 20.04      | 4        | 3.1%    |
| Ubuntu 22.04       | 4        | 3.1%    |
| Linux Mint 21.2    | 4        | 3.1%    |
| OpenMandriva 23.01 | 3        | 2.33%   |
| Linux Mint 19.3    | 3        | 2.33%   |
| Debian 11          | 3        | 2.33%   |
| Arch Rolling       | 3        | 2.33%   |
| Ubuntu 18.10       | 2        | 1.55%   |
| ROSA R11.1         | 2        | 1.55%   |
| Pop!_OS 20.04      | 2        | 1.55%   |
| OpenMandriva 5.0   | 2        | 1.55%   |
| OpenMandriva 23.08 | 2        | 1.55%   |
| OpenMandriva 23.03 | 2        | 1.55%   |
| Linux Mint 21.3    | 2        | 1.55%   |
| Linux Mint 20      | 2        | 1.55%   |
| Linux Mint 19.1    | 2        | 1.55%   |
| KDE neon 20.04     | 2        | 1.55%   |
| BlackPanther 18.1  | 2        | 1.55%   |
| Arch               | 2        | 1.55%   |
| Zorin 17           | 1        | 0.78%   |
| Zorin 16           | 1        | 0.78%   |
| Zorin 15           | 1        | 0.78%   |
| Xubuntu 21.04      | 1        | 0.78%   |
| Xubuntu 18.04      | 1        | 0.78%   |
| Ubuntu 21.10       | 1        | 0.78%   |
| Ubuntu 19.04       | 1        | 0.78%   |
| ROSA 12.4          | 1        | 0.78%   |
| Pop!_OS 22.04      | 1        | 0.78%   |
| Pop!_OS 21.10      | 1        | 0.78%   |
| OpenMandriva 4.90  | 1        | 0.78%   |
| OpenMandriva 4.50  | 1        | 0.78%   |
| OpenMandriva 4.2   | 1        | 0.78%   |
| OpenMandriva 24.03 | 1        | 0.78%   |
| Nobara 38          | 1        | 0.78%   |
| Lubuntu 18.04      | 1        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 26       | 21.49%  |
| OpenMandriva | 19       | 15.7%   |
| Linux Mint   | 16       | 13.22%  |
| Manjaro      | 9        | 7.44%   |
| ArcoLinux    | 7        | 5.79%   |
| Xubuntu      | 6        | 4.96%   |
| Fedora       | 6        | 4.96%   |
| Arch         | 5        | 4.13%   |
| Pop!_OS      | 4        | 3.31%   |
| KDE neon     | 4        | 3.31%   |
| Debian       | 4        | 3.31%   |
| Zorin        | 3        | 2.48%   |
| ROSA         | 3        | 2.48%   |
| Lubuntu      | 2        | 1.65%   |
| BlackPanther | 2        | 1.65%   |
| Nobara       | 1        | 0.83%   |
| LMDE         | 1        | 0.83%   |
| LinuxFX      | 1        | 0.83%   |
| Endless      | 1        | 0.83%   |
| Alpine       | 1        | 0.83%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                | Desktops | Percent |
|----------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003                | 11       | 8.09%   |
| 5.4.0-42-generic                       | 4        | 2.94%   |
| 6.1.1-desktop-1omv2290                 | 3        | 2.21%   |
| 5.3.0-46-generic                       | 3        | 2.21%   |
| 6.6.2-desktop-1omv2390                 | 2        | 1.47%   |
| 6.4.11-desktop-1omv2390                | 2        | 1.47%   |
| 6.2.6-desktop-1omv2390                 | 2        | 1.47%   |
| 6.1.26-1-MANJARO                       | 2        | 1.47%   |
| 5.4.83-generic-2rosa-x86_64            | 2        | 1.47%   |
| 5.4.0-65-generic                       | 2        | 1.47%   |
| 5.15.60-1-MANJARO                      | 2        | 1.47%   |
| 5.15.0-67-generic                      | 2        | 1.47%   |
| 5.15.0-48-generic                      | 2        | 1.47%   |
| 5.11.0-38-generic                      | 2        | 1.47%   |
| 5.10.0-21-amd64                        | 2        | 1.47%   |
| 5.0.0-32-generic                       | 2        | 1.47%   |
| 4.18.16-desktop-1bP                    | 2        | 1.47%   |
| 6.8.5-201.fc39.x86_64                  | 1        | 0.74%   |
| 6.8.1-desktop-3omv2490                 | 1        | 0.74%   |
| 6.6.9-arch1-1-drm-amd-issue-2991-patch | 1        | 0.74%   |
| 6.6.7-200.fsync.fc38.x86_64            | 1        | 0.74%   |
| 6.6.4-zen1-1-zen                       | 1        | 0.74%   |
| 6.6.25-1-lts                           | 1        | 0.74%   |
| 6.6.23-0-lts                           | 1        | 0.74%   |
| 6.6.14-2-lts                           | 1        | 0.74%   |
| 6.5.5-arch1-1                          | 1        | 0.74%   |
| 6.5.13-4-MANJARO                       | 1        | 0.74%   |
| 6.5.0-28-generic                       | 1        | 0.74%   |
| 6.5.0-26-generic                       | 1        | 0.74%   |
| 6.5.0-1004-nvidia                      | 1        | 0.74%   |
| 6.4.11-arch2-1                         | 1        | 0.74%   |
| 6.3.8-arch1-1                          | 1        | 0.74%   |
| 6.3.7-arch1-1                          | 1        | 0.74%   |
| 6.2.16-10-pve                          | 1        | 0.74%   |
| 6.2.12-1-MANJARO                       | 1        | 0.74%   |
| 6.2.0-34-generic                       | 1        | 0.74%   |
| 6.2.0-1010-nvidia                      | 1        | 0.74%   |
| 6.1.20-generic-2rosa2021.1-x86_64      | 1        | 0.74%   |
| 6.1.11-arch1-1                         | 1        | 0.74%   |
| 6.0.18-300.fc37.x86_64                 | 1        | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 18       | 13.64%  |
| 5.16.7  | 11       | 8.33%   |
| 5.15.0  | 10       | 7.58%   |
| 4.15.0  | 8        | 6.06%   |
| 5.11.0  | 6        | 4.55%   |
| 5.3.0   | 5        | 3.79%   |
| 6.5.0   | 3        | 2.27%   |
| 6.4.11  | 3        | 2.27%   |
| 6.1.1   | 3        | 2.27%   |
| 5.13.0  | 3        | 2.27%   |
| 5.10.0  | 3        | 2.27%   |
| 5.0.0   | 3        | 2.27%   |
| 4.18.0  | 3        | 2.27%   |
| 6.6.2   | 2        | 1.52%   |
| 6.2.6   | 2        | 1.52%   |
| 6.2.0   | 2        | 1.52%   |
| 6.1.26  | 2        | 1.52%   |
| 5.4.83  | 2        | 1.52%   |
| 5.19.0  | 2        | 1.52%   |
| 5.18.12 | 2        | 1.52%   |
| 5.15.60 | 2        | 1.52%   |
| 4.18.16 | 2        | 1.52%   |
| 6.8.5   | 1        | 0.76%   |
| 6.8.1   | 1        | 0.76%   |
| 6.6.9   | 1        | 0.76%   |
| 6.6.7   | 1        | 0.76%   |
| 6.6.4   | 1        | 0.76%   |
| 6.6.25  | 1        | 0.76%   |
| 6.6.23  | 1        | 0.76%   |
| 6.6.14  | 1        | 0.76%   |
| 6.5.5   | 1        | 0.76%   |
| 6.5.13  | 1        | 0.76%   |
| 6.3.8   | 1        | 0.76%   |
| 6.3.7   | 1        | 0.76%   |
| 6.2.16  | 1        | 0.76%   |
| 6.2.12  | 1        | 0.76%   |
| 6.1.20  | 1        | 0.76%   |
| 6.1.11  | 1        | 0.76%   |
| 6.0.18  | 1        | 0.76%   |
| 6.0.0   | 1        | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 15.15%  |
| 5.15    | 14       | 10.61%  |
| 5.16    | 11       | 8.33%   |
| 6.6     | 8        | 6.06%   |
| 5.11    | 8        | 6.06%   |
| 4.15    | 8        | 6.06%   |
| 6.1     | 7        | 5.3%    |
| 6.2     | 6        | 4.55%   |
| 6.5     | 5        | 3.79%   |
| 5.3     | 5        | 3.79%   |
| 5.10    | 5        | 3.79%   |
| 4.18    | 5        | 3.79%   |
| 5.13    | 4        | 3.03%   |
| 5.12    | 4        | 3.03%   |
| 6.4     | 3        | 2.27%   |
| 5.19    | 3        | 2.27%   |
| 5.18    | 3        | 2.27%   |
| 5.0     | 3        | 2.27%   |
| 6.8     | 2        | 1.52%   |
| 6.3     | 2        | 1.52%   |
| 6.0     | 2        | 1.52%   |
| 5.17    | 2        | 1.52%   |
| 5.6     | 1        | 0.76%   |
| 4.8     | 1        | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 112      | 97.39%  |
| i686   | 3        | 2.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 35       | 29.41%  |
| KDE5       | 34       | 28.57%  |
| X-Cinnamon | 13       | 10.92%  |
| XFCE       | 11       | 9.24%   |
| Unknown    | 10       | 8.4%    |
| LXDE       | 3        | 2.52%   |
| Cinnamon   | 3        | 2.52%   |
| MATE       | 2        | 1.68%   |
| KDE4       | 2        | 1.68%   |
| KDE        | 2        | 1.68%   |
| bspwm      | 2        | 1.68%   |
| qtile      | 1        | 0.84%   |
| ICEWM      | 1        | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 99       | 80.49%  |
| Wayland | 18       | 14.63%  |
| Unknown | 4        | 3.25%   |
| Tty     | 2        | 1.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 48.31%  |
| SDDM    | 29       | 24.58%  |
| LightDM | 16       | 13.56%  |
| GDM     | 6        | 5.08%   |
| GDM3    | 5        | 4.24%   |
| LY-DM   | 2        | 1.69%   |
| KDM     | 2        | 1.69%   |
| TDM     | 1        | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| es_UY      | 67       | 54.47%  |
| en_US      | 24       | 19.51%  |
| es_ES      | 13       | 10.57%  |
| Unknown    | 8        | 6.5%    |
| es_AR      | 5        | 4.07%   |
| C          | 4        | 3.25%   |
| es_UY.UTF8 | 1        | 0.81%   |
| en_GB      | 1        | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 71       | 59.17%  |
| EFI  | 49       | 40.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 86       | 71.67%  |
| Overlay | 21       | 17.5%   |
| Btrfs   | 7        | 5.83%   |
| Tmpfs   | 3        | 2.5%    |
| Xfs     | 2        | 1.67%   |
| Unknown | 1        | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 59       | 49.17%  |
| GPT     | 45       | 37.5%   |
| MBR     | 16       | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 76.07%  |
| Yes       | 28       | 23.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 63.03%  |
| Yes       | 44       | 36.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 24       | 20.87%  |
| ASRock              | 22       | 19.13%  |
| ASUSTek Computer    | 19       | 16.52%  |
| MSI                 | 13       | 11.3%   |
| Hewlett-Packard     | 12       | 10.43%  |
| Dell                | 8        | 6.96%   |
| Lenovo              | 3        | 2.61%   |
| Intel               | 3        | 2.61%   |
| Biostar             | 3        | 2.61%   |
| Supermicro          | 1        | 0.87%   |
| MACHINIST           | 1        | 0.87%   |
| Huanan              | 1        | 0.87%   |
| Gateway             | 1        | 0.87%   |
| Fujitsu             | 1        | 0.87%   |
| Foxconn             | 1        | 0.87%   |
| ECS                 | 1        | 0.87%   |
| AZW                 | 1        | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                             | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| MSI MS-7C37                                                      | 2        | 1.74%   |
| MSI MS-7817                                                      | 2        | 1.74%   |
| MSI MS-7721                                                      | 2        | 1.74%   |
| HP Compaq 6200 Pro SFF PC                                        | 2        | 1.74%   |
| Gigabyte Z390 AORUS ELITE                                        | 2        | 1.74%   |
| Gigabyte Z370 AORUS Gaming 7                                     | 2        | 1.74%   |
| Gigabyte H61M-S1                                                 | 2        | 1.74%   |
| Gigabyte H310M A                                                 | 2        | 1.74%   |
| Dell OptiPlex 7010                                               | 2        | 1.74%   |
| ASUS TUF Gaming B650M-PLUS WIFI                                  | 2        | 1.74%   |
| ASUS PRIME A320M-K                                               | 2        | 1.74%   |
| ASUS All Series                                                  | 2        | 1.74%   |
| ASRock N68-S                                                     | 2        | 1.74%   |
| ASRock H310CM-HDV                                                | 2        | 1.74%   |
| ASRock FM2A58M-VG3+ R2.0                                         | 2        | 1.74%   |
| ASRock ALiveNF6P-VSTA                                            | 2        | 1.74%   |
| Supermicro P4DMS                                                 | 1        | 0.87%   |
| MSI Pro 3130 Microtower PC                                       | 1        | 0.87%   |
| MSI MS-7C09                                                      | 1        | 0.87%   |
| MSI MS-7816                                                      | 1        | 0.87%   |
| MSI MS-7788                                                      | 1        | 0.87%   |
| MSI MS-7786                                                      | 1        | 0.87%   |
| MSI MS-7641                                                      | 1        | 0.87%   |
| MSI MS-7592                                                      | 1        | 0.87%   |
| MACHINIST X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V309 | 1        | 0.87%   |
| Lenovo ThinkCentre M92p 3238BK7                                  | 1        | 0.87%   |
| Lenovo ThinkCentre M82 3392C4S                                   | 1        | 0.87%   |
| Lenovo ThinkCentre M700 10HYA06700                               | 1        | 0.87%   |
| Intel H61M-DS2                                                   | 1        | 0.87%   |
| Intel H61                                                        | 1        | 0.87%   |
| Intel DP35DP AAD81073-208                                        | 1        | 0.87%   |
| Huanan X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V3.3    | 1        | 0.87%   |
| HP rp5800                                                        | 1        | 0.87%   |
| HP EliteDesk 800 G1 SFF                                          | 1        | 0.87%   |
| HP EliteDesk 705 G3 SFF                                          | 1        | 0.87%   |
| HP dc5000 SFF(DX854AV)                                           | 1        | 0.87%   |
| HP Compaq Pro 6300 SFF                                           | 1        | 0.87%   |
| HP Compaq dc7800p Small Form Factor                              | 1        | 0.87%   |
| HP Compaq dc5700 Microtower                                      | 1        | 0.87%   |
| HP Compaq 8200 Elite SFF PC                                      | 1        | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 8        | 6.96%   |
| Dell OptiPlex         | 6        | 5.22%   |
| ASUS TUF              | 4        | 3.48%   |
| ASUS PRIME            | 4        | 3.48%   |
| Lenovo ThinkCentre    | 3        | 2.61%   |
| MSI MS-7C37           | 2        | 1.74%   |
| MSI MS-7817           | 2        | 1.74%   |
| MSI MS-7721           | 2        | 1.74%   |
| HP EliteDesk          | 2        | 1.74%   |
| Gigabyte Z390         | 2        | 1.74%   |
| Gigabyte Z370         | 2        | 1.74%   |
| Gigabyte H61M-S1      | 2        | 1.74%   |
| Gigabyte H310M        | 2        | 1.74%   |
| Gigabyte B450M        | 2        | 1.74%   |
| ASUS All              | 2        | 1.74%   |
| ASRock N68-S          | 2        | 1.74%   |
| ASRock H310CM-HDV     | 2        | 1.74%   |
| ASRock FM2A58M-VG3+   | 2        | 1.74%   |
| ASRock ALiveNF6P-VSTA | 2        | 1.74%   |
| ASRock A320M-HDV      | 2        | 1.74%   |
| Supermicro P4DMS      | 1        | 0.87%   |
| MSI Pro               | 1        | 0.87%   |
| MSI MS-7C09           | 1        | 0.87%   |
| MSI MS-7816           | 1        | 0.87%   |
| MSI MS-7788           | 1        | 0.87%   |
| MSI MS-7786           | 1        | 0.87%   |
| MSI MS-7641           | 1        | 0.87%   |
| MSI MS-7592           | 1        | 0.87%   |
| MACHINIST X79         | 1        | 0.87%   |
| Intel H61M-DS2        | 1        | 0.87%   |
| Intel H61             | 1        | 0.87%   |
| Intel DP35DP          | 1        | 0.87%   |
| Huanan X79            | 1        | 0.87%   |
| HP rp5800             | 1        | 0.87%   |
| HP dc5000             | 1        | 0.87%   |
| Gigabyte Z87X-UD4H    | 1        | 0.87%   |
| Gigabyte Z790         | 1        | 0.87%   |
| Gigabyte Z170X-Gaming | 1        | 0.87%   |
| Gigabyte X570         | 1        | 0.87%   |
| Gigabyte H81M-H       | 1        | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 14       | 12.17%  |
| 2013 | 13       | 11.3%   |
| 2012 | 12       | 10.43%  |
| 2018 | 10       | 8.7%    |
| 2019 | 9        | 7.83%   |
| 2017 | 8        | 6.96%   |
| 2009 | 7        | 6.09%   |
| 2021 | 6        | 5.22%   |
| 2022 | 5        | 4.35%   |
| 2020 | 5        | 4.35%   |
| 2015 | 5        | 4.35%   |
| 2014 | 4        | 3.48%   |
| 2010 | 4        | 3.48%   |
| 2007 | 4        | 3.48%   |
| 2023 | 2        | 1.74%   |
| 2016 | 2        | 1.74%   |
| 2008 | 1        | 0.87%   |
| 2006 | 1        | 0.87%   |
| 2005 | 1        | 0.87%   |
| 2004 | 1        | 0.87%   |
| 2003 | 1        | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 115      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 115      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 115      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 27       | 22.13%  |
| 16.01-24.0  | 26       | 21.31%  |
| 8.01-16.0   | 21       | 17.21%  |
| 3.01-4.0    | 18       | 14.75%  |
| 32.01-64.0  | 13       | 10.66%  |
| 24.01-32.0  | 6        | 4.92%   |
| 1.01-2.0    | 6        | 4.92%   |
| 64.01-256.0 | 3        | 2.46%   |
| 0.51-1.0    | 1        | 0.82%   |
| 0.01-0.5    | 1        | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 48       | 37.5%   |
| 2.01-3.0  | 30       | 23.44%  |
| 3.01-4.0  | 19       | 14.84%  |
| 4.01-8.0  | 12       | 9.38%   |
| 8.01-16.0 | 7        | 5.47%   |
| 0.51-1.0  | 7        | 5.47%   |
| 0.01-0.5  | 5        | 3.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 44.63%  |
| 2      | 38       | 31.4%   |
| 3      | 14       | 11.57%  |
| 4      | 11       | 9.09%   |
| 5      | 3        | 2.48%   |
| 7      | 1        | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 59.66%  |
| Yes       | 48       | 40.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 113      | 98.26%  |
| No        | 2        | 1.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 60.17%  |
| Yes       | 47       | 39.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 81.03%  |
| Yes       | 22       | 18.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Uruguay | 115      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Montevideo       | 97       | 80.83%  |
| Maldonado        | 5        | 4.17%   |
| Florida          | 3        | 2.5%    |
| San Jose de Mayo | 2        | 1.67%   |
| Las Piedras      | 2        | 1.67%   |
| Punta del Este   | 1        | 0.83%   |
| Nuevo Paris      | 1        | 0.83%   |
| Nueva Helvecia   | 1        | 0.83%   |
| Minas            | 1        | 0.83%   |
| Melo             | 1        | 0.83%   |
| Malvin Norte     | 1        | 0.83%   |
| La Paz           | 1        | 0.83%   |
| Durazno          | 1        | 0.83%   |
| Ciudad del Plata | 1        | 0.83%   |
| Centro           | 1        | 0.83%   |
| Unknown          | 1        | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 57       | 77     | 28.08%  |
| Seagate                     | 32       | 45     | 15.76%  |
| Kingston                    | 28       | 36     | 13.79%  |
| Samsung Electronics         | 21       | 23     | 10.34%  |
| Toshiba                     | 19       | 25     | 9.36%   |
| Crucial                     | 6        | 10     | 2.96%   |
| Maxtor                      | 3        | 4      | 1.48%   |
| Hitachi                     | 3        | 6      | 1.48%   |
| Gigabyte Technology         | 3        | 4      | 1.48%   |
| Biostar                     | 3        | 4      | 1.48%   |
| SK hynix                    | 2        | 2      | 0.99%   |
| Realtek Semiconductor       | 2        | 2      | 0.99%   |
| Patriot                     | 2        | 3      | 0.99%   |
| Micron/Crucial Technology   | 2        | 3      | 0.99%   |
| HS-SSD-C100                 | 2        | 3      | 0.99%   |
| HGST                        | 2        | 2      | 0.99%   |
| Hewlett-Packard             | 2        | 2      | 0.99%   |
| Dahua                       | 2        | 2      | 0.99%   |
| Unknown                     | 1        | 3      | 0.49%   |
| Silicon Motion              | 1        | 1      | 0.49%   |
| SanDisk                     | 1        | 2      | 0.49%   |
| Phison Electronics          | 1        | 1      | 0.49%   |
| Phison                      | 1        | 1      | 0.49%   |
| NGFF                        | 1        | 1      | 0.49%   |
| Netac                       | 1        | 2      | 0.49%   |
| Micron Technology           | 1        | 1      | 0.49%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.49%   |
| IBM-ESXS                    | 1        | 1      | 0.49%   |
| ExcelStor                   | 1        | 1      | 0.49%   |
| A-DATA Technology           | 1        | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD    | 7        | 3.15%   |
| Toshiba DT01ACA300 3TB             | 6        | 2.7%    |
| Toshiba DT01ACA100 1TB             | 6        | 2.7%    |
| WDC WD10EZEX-08WN4A0 1TB           | 5        | 2.25%   |
| Samsung HD161HJ 160GB              | 5        | 2.25%   |
| Kingston SA400S37480G 480GB SSD    | 5        | 2.25%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 4        | 1.8%    |
| Seagate ST1000DM010-2EP102 1TB     | 4        | 1.8%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 3        | 1.35%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 1.35%   |
| Kingston SV300S37A480G 480GB SSD   | 3        | 1.35%   |
| Kingston SA400S37120G 120GB SSD    | 3        | 1.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 2        | 0.9%    |
| WDC WD5000AZLX-00ZR6A0 500GB       | 2        | 0.9%    |
| WDC WD5000AAKX-75U6AA0 500GB       | 2        | 0.9%    |
| WDC WD10EZEX-00BBHA0 1TB           | 2        | 0.9%    |
| WDC WD10EFRX-68FYTN0 1TB           | 2        | 0.9%    |
| Seagate ST500DM005 HD502HJ 500GB   | 2        | 0.9%    |
| Seagate ST3750640NS 752GB          | 2        | 0.9%    |
| Seagate ST3250312AS 250GB          | 2        | 0.9%    |
| Seagate ST3160318AS 160GB          | 2        | 0.9%    |
| Seagate ST250DM000-1BD141 250GB    | 2        | 0.9%    |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 0.9%    |
| Samsung SSD 860 EVO 500GB          | 2        | 0.9%    |
| Samsung HD103SJ 1TB                | 2        | 0.9%    |
| Kingston SV300S37A120G 120GB SSD   | 2        | 0.9%    |
| Kingston SNVS1000G 1TB             | 2        | 0.9%    |
| Kingston SFYRS1000G 1TB            | 2        | 0.9%    |
| Kingston SA2000M81000G 1TB         | 2        | 0.9%    |
| Gigabyte GP-GSTFS31480GNTD 480GB   | 2        | 0.9%    |
| Dahua C800 2.5 inch SATA 512GB SSD | 2        | 0.9%    |
| Biostar S100-120GB                 | 2        | 0.9%    |
| WDC WDS512G1X0C-00ENX0 512GB       | 1        | 0.45%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 1        | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.45%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1        | 0.45%   |
| WDC WDS250G2B0B-00YS70 250GB SSD   | 1        | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1        | 0.45%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1        | 0.45%   |
| WDC WD800JD-75MSA3 80GB            | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 49       | 64     | 39.52%  |
| Seagate             | 32       | 45     | 25.81%  |
| Toshiba             | 19       | 25     | 15.32%  |
| Samsung Electronics | 15       | 16     | 12.1%   |
| Maxtor              | 3        | 4      | 2.42%   |
| Hitachi             | 3        | 6      | 2.42%   |
| HGST                | 2        | 2      | 1.61%   |
| ExcelStor           | 1        | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 22       | 25     | 41.51%  |
| WDC                 | 8        | 9      | 15.09%  |
| Crucial             | 5        | 7      | 9.43%   |
| Samsung Electronics | 3        | 4      | 5.66%   |
| Gigabyte Technology | 3        | 4      | 5.66%   |
| Dahua               | 2        | 2      | 3.77%   |
| Biostar             | 2        | 3      | 3.77%   |
| SK hynix            | 1        | 1      | 1.89%   |
| Patriot             | 1        | 2      | 1.89%   |
| NGFF                | 1        | 1      | 1.89%   |
| Netac               | 1        | 2      | 1.89%   |
| Micron Technology   | 1        | 1      | 1.89%   |
| HS-SSD-C100         | 1        | 1      | 1.89%   |
| Hewlett-Packard     | 1        | 1      | 1.89%   |
| A-DATA Technology   | 1        | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 91       | 163    | 54.82%  |
| SSD     | 50       | 64     | 30.12%  |
| NVMe    | 21       | 36     | 12.65%  |
| Unknown | 4        | 7      | 2.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 108      | 229    | 81.82%  |
| NVMe | 21       | 36     | 15.91%  |
| SAS  | 3        | 5      | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 88       | 133    | 60.27%  |
| 0.51-1.0   | 42       | 74     | 28.77%  |
| 2.01-3.0   | 8        | 10     | 5.48%   |
| 1.01-2.0   | 5        | 6      | 3.42%   |
| 3.01-4.0   | 3        | 4      | 2.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 29       | 23.2%   |
| 251-500        | 25       | 20%     |
| 501-1000       | 19       | 15.2%   |
| 1001-2000      | 15       | 12%     |
| 1-20           | 13       | 10.4%   |
| 51-100         | 7        | 5.6%    |
| 21-50          | 5        | 4%      |
| 2001-3000      | 5        | 4%      |
| Unknown        | 5        | 4%      |
| More than 3000 | 2        | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 45       | 36%     |
| 21-50     | 20       | 16%     |
| 101-250   | 16       | 12.8%   |
| 501-1000  | 12       | 9.6%    |
| 51-100    | 11       | 8.8%    |
| 251-500   | 7        | 5.6%    |
| 1001-2000 | 6        | 4.8%    |
| Unknown   | 5        | 4%      |
| 2001-3000 | 3        | 2.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 2        | 2      | 9.09%   |
| Seagate ST3750640NS 752GB        | 2        | 7      | 9.09%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 2      | 9.09%   |
| WDC WD800BD-00LRA1 80GB          | 1        | 1      | 4.55%   |
| WDC WD5000BEKT-60KA9T0 500GB     | 1        | 1      | 4.55%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 2      | 4.55%   |
| WDC WD5000AAJS-00A8B0 500GB      | 1        | 1      | 4.55%   |
| WDC WD10EARS-22Y5B1 1TB          | 1        | 1      | 4.55%   |
| Toshiba MQ01ABD075 752GB         | 1        | 1      | 4.55%   |
| Toshiba MK5059GSXP 500GB         | 1        | 1      | 4.55%   |
| Toshiba MK3276GSX 320GB          | 1        | 1      | 4.55%   |
| Toshiba DT01ACA100 1TB           | 1        | 1      | 4.55%   |
| Seagate ST500LM021-1KJ152 500GB  | 1        | 1      | 4.55%   |
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 4.55%   |
| Seagate ST3250310CS 250GB        | 1        | 1      | 4.55%   |
| Seagate ST3200827AS 200GB        | 1        | 1      | 4.55%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 1      | 4.55%   |
| Kingston SA400S37480G 480GB SSD  | 1        | 2      | 4.55%   |
| HS-SSD-C100 SSD 240G             | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 10       | 16     | 47.62%  |
| WDC         | 5        | 6      | 23.81%  |
| Toshiba     | 4        | 4      | 19.05%  |
| Kingston    | 1        | 2      | 4.76%   |
| HS-SSD-C100 | 1        | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 16     | 52.63%  |
| WDC     | 5        | 6      | 26.32%  |
| Toshiba | 4        | 4      | 21.05%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 26     | 90.48%  |
| SSD  | 2        | 3      | 9.52%   |

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
| Detected | 65       | 146    | 49.24%  |
| Works    | 46       | 95     | 34.85%  |
| Malfunc  | 21       | 29     | 15.91%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 69       | 46.62%  |
| AMD                         | 39       | 26.35%  |
| Nvidia                      | 6        | 4.05%   |
| Kingston Technology Company | 6        | 4.05%   |
| ASMedia Technology          | 5        | 3.38%   |
| SanDisk                     | 4        | 2.7%    |
| Silicon Motion              | 3        | 2.03%   |
| Samsung Electronics         | 3        | 2.03%   |
| Micron/Crucial Technology   | 3        | 2.03%   |
| Realtek Semiconductor       | 2        | 1.35%   |
| Phison Electronics          | 2        | 1.35%   |
| Marvell Technology Group    | 2        | 1.35%   |
| VIA Technologies            | 1        | 0.68%   |
| SK hynix                    | 1        | 0.68%   |
| MAXIO Technology (Hangzhou) | 1        | 0.68%   |
| Adaptec                     | 1        | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20       | 10.26%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 4.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 4.1%    |
| Nvidia MCP61 SATA Controller                                                            | 6        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 3.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 3.08%   |
| Nvidia MCP61 IDE                                                                        | 5        | 2.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.56%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5        | 2.56%   |
| AMD FCH IDE Controller                                                                  | 5        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 2.05%   |
| AMD FCH SATA Controller D                                                               | 4        | 2.05%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.54%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.54%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 1.03%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2        | 1.03%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 1.03%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 2        | 1.03%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 2        | 1.03%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.03%   |
| AMD 600 Series Chipset SATA Controller                                                  | 2        | 1.03%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.03%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.51%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.51%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 0.51%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                             | 1        | 0.51%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 92       | 59.74%  |
| IDE  | 37       | 24.03%  |
| NVMe | 21       | 13.64%  |
| RAID | 3        | 1.95%   |
| SCSI | 1        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 70       | 60.87%  |
| AMD    | 45       | 39.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-8400 CPU @ 2.80GHz                | 3        | 2.59%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 3        | 2.59%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 3        | 2.59%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 3        | 2.59%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 3        | 2.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 2        | 1.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 2        | 1.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 2        | 1.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 2        | 1.72%   |
| AMD Ryzen 7 7800X3D 8-Core Processor            | 2        | 1.72%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 1.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 1.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 2        | 1.72%   |
| AMD Phenom II X6 1055T Processor                | 2        | 1.72%   |
| AMD Athlon II X2 250 Processor                  | 2        | 1.72%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 2        | 1.72%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 2        | 1.72%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz              | 1        | 0.86%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz              | 1        | 0.86%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1        | 0.86%   |
| Intel Xeon CPU 2.40GHz                          | 1        | 0.86%   |
| Intel Pentium CPU G870 @ 3.10GHz                | 1        | 0.86%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 1        | 0.86%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 0.86%   |
| Intel Pentium 4 CPU 2.80GHz                     | 1        | 0.86%   |
| Intel Genuine CPU 2140 @ 1.60GHz                | 1        | 0.86%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 1        | 0.86%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 0.86%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 0.86%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 0.86%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 0.86%   |
| Intel Core i7-4930K CPU @ 3.40GHz               | 1        | 0.86%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 0.86%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 0.86%   |
| Intel Core i7-10700F CPU @ 2.90GHz              | 1        | 0.86%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 0.86%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 0.86%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 0.86%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1        | 0.86%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 20       | 17.24%  |
| Intel Core i3     | 15       | 12.93%  |
| Intel Core i7     | 12       | 10.34%  |
| AMD Ryzen 5       | 9        | 7.76%   |
| AMD Ryzen 7       | 7        | 6.03%   |
| Intel Core 2 Duo  | 6        | 5.17%   |
| AMD Athlon II X2  | 5        | 4.31%   |
| Intel Xeon        | 4        | 3.45%   |
| Intel Celeron     | 4        | 3.45%   |
| AMD FX            | 4        | 3.45%   |
| Intel Pentium     | 3        | 2.59%   |
| Intel Core 2 Quad | 3        | 2.59%   |
| AMD Ryzen 3       | 3        | 2.59%   |
| AMD Phenom II X6  | 3        | 2.59%   |
| AMD A10           | 3        | 2.59%   |
| AMD Athlon        | 2        | 1.72%   |
| AMD A6            | 2        | 1.72%   |
| AMD A4            | 2        | 1.72%   |
| Other             | 1        | 0.86%   |
| Intel Pentium 4   | 1        | 0.86%   |
| Intel Genuine     | 1        | 0.86%   |
| Intel Core i9     | 1        | 0.86%   |
| AMD PRO A10       | 1        | 0.86%   |
| AMD Phenom        | 1        | 0.86%   |
| AMD Athlon 64 X2  | 1        | 0.86%   |
| AMD Athlon 64     | 1        | 0.86%   |
| AMD A8            | 1        | 0.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 44       | 37.93%  |
| 4      | 33       | 28.45%  |
| 6      | 23       | 19.83%  |
| 8      | 11       | 9.48%   |
| 1      | 4        | 3.45%   |
| 14     | 1        | 0.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 114      | 99.13%  |
| 2      | 1        | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 67       | 58.26%  |
| 1      | 48       | 41.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 111      | 96.52%  |
| 32-bit         | 2        | 1.74%   |
| Unknown        | 2        | 1.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 43       | 34.4%   |
| 0x206a7    | 7        | 5.6%    |
| 0x306c3    | 6        | 4.8%    |
| 0x306a9    | 6        | 4.8%    |
| 0x906ea    | 5        | 4%      |
| 0x1067a    | 5        | 4%      |
| 0x08701021 | 4        | 3.2%    |
| 0x08108109 | 3        | 2.4%    |
| 0x06000852 | 3        | 2.4%    |
| 0xa0655    | 2        | 1.6%    |
| 0xa0653    | 2        | 1.6%    |
| 0x506e3    | 2        | 1.6%    |
| 0x206d7    | 2        | 1.6%    |
| 0x20655    | 2        | 1.6%    |
| 0x0a50000d | 2        | 1.6%    |
| 0x0800820d | 2        | 1.6%    |
| 0x08001138 | 2        | 1.6%    |
| 0x06003106 | 2        | 1.6%    |
| 0x06001119 | 2        | 1.6%    |
| 0x010000dc | 2        | 1.6%    |
| 0xf33      | 1        | 0.8%    |
| 0xf27      | 1        | 0.8%    |
| 0x906ed    | 1        | 0.8%    |
| 0x906ec    | 1        | 0.8%    |
| 0x906eb    | 1        | 0.8%    |
| 0x906e9    | 1        | 0.8%    |
| 0x906c0    | 1        | 0.8%    |
| 0x6fd      | 1        | 0.8%    |
| 0x10677    | 1        | 0.8%    |
| 0x10676    | 1        | 0.8%    |
| 0x0a601206 | 1        | 0.8%    |
| 0x0a601201 | 1        | 0.8%    |
| 0x0a50000c | 1        | 0.8%    |
| 0x08108102 | 1        | 0.8%    |
| 0x08001137 | 1        | 0.8%    |
| 0x0600611a | 1        | 0.8%    |
| 0x03000027 | 1        | 0.8%    |
| 0x010000c8 | 1        | 0.8%    |
| 0x010000b6 | 1        | 0.8%    |
| 0x01000083 | 1        | 0.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 13       | 11.21%  |
| SandyBridge | 12       | 10.34%  |
| KabyLake    | 11       | 9.48%   |
| Haswell     | 10       | 8.62%   |
| K10         | 9        | 7.76%   |
| Zen+        | 7        | 6.03%   |
| Penryn      | 7        | 6.03%   |
| Piledriver  | 6        | 5.17%   |
| CometLake   | 6        | 5.17%   |
| Zen 3       | 5        | 4.31%   |
| Zen 2       | 4        | 3.45%   |
| Steamroller | 4        | 3.45%   |
| Zen         | 3        | 2.59%   |
| Skylake     | 3        | 2.59%   |
| Core        | 3        | 2.59%   |
| Unknown     | 3        | 2.59%   |
| Westmere    | 2        | 1.72%   |
| NetBurst    | 2        | 1.72%   |
| K8 Hammer   | 2        | 1.72%   |
| Tremont     | 1        | 0.86%   |
| K10 Llano   | 1        | 0.86%   |
| Jaguar      | 1        | 0.86%   |
| Excavator   | 1        | 0.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 50       | 40.32%  |
| Intel  | 39       | 31.45%  |
| AMD    | 35       | 28.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 7.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.91%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 3.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.13%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 3.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 3.13%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 2.34%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.34%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 2.34%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 2.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.34%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.56%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.56%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.56%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 1.56%   |
| Intel HD Graphics 530                                                       | 2        | 1.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.56%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.56%   |
| AMD Navi 21 [Radeon RX 6900 XT]                                             | 2        | 1.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.56%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.78%   |
| Nvidia NV34 [GeForce FX 5200]                                               | 1        | 0.78%   |
| Nvidia GT216 [GeForce 210]                                                  | 1        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.78%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.78%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.78%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.78%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.78%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 47       | 39.83%  |
| 1 x Intel      | 33       | 27.97%  |
| 1 x AMD        | 31       | 26.27%  |
| 2 x AMD        | 3        | 2.54%   |
| Intel + Nvidia | 2        | 1.69%   |
| Other          | 1        | 0.85%   |
| AMD + Nvidia   | 1        | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 89       | 75.42%  |
| Proprietary | 20       | 16.95%  |
| Unknown     | 9        | 7.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 41.8%   |
| 1.01-2.0   | 19       | 15.57%  |
| 0.51-1.0   | 15       | 12.3%   |
| 3.01-4.0   | 12       | 9.84%   |
| 0.01-0.5   | 12       | 9.84%   |
| 7.01-8.0   | 6        | 4.92%   |
| 5.01-6.0   | 3        | 2.46%   |
| 8.01-16.0  | 3        | 2.46%   |
| 2.01-3.0   | 1        | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AOC                     | 21       | 19.81%  |
| ViewSonic               | 17       | 16.04%  |
| Samsung Electronics     | 15       | 14.15%  |
| KTC                     | 8        | 7.55%   |
| Goldstar                | 8        | 7.55%   |
| Hewlett-Packard         | 5        | 4.72%   |
| Acer                    | 5        | 4.72%   |
| Unknown                 | 4        | 3.77%   |
| Lenovo                  | 3        | 2.83%   |
| JRY                     | 3        | 2.83%   |
| Dell                    | 2        | 1.89%   |
| Ancor Communications    | 2        | 1.89%   |
| Sony                    | 1        | 0.94%   |
| RIS                     | 1        | 0.94%   |
| Philips                 | 1        | 0.94%   |
| Panasonic               | 1        | 0.94%   |
| LG Electronics          | 1        | 0.94%   |
| Lenovo Group Limited    | 1        | 0.94%   |
| KOA                     | 1        | 0.94%   |
| HKC                     | 1        | 0.94%   |
| Hitachi                 | 1        | 0.94%   |
| Envision                | 1        | 0.94%   |
| CVT                     | 1        | 0.94%   |
| Chi Mei Optoelectronics | 1        | 0.94%   |
| BenQ                    | 1        | 0.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 4        | 3.57%   |
| ViewSonic VA2261 VSC0F30 1920x1080 480x270mm 21.7-inch                | 3        | 2.68%   |
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                  | 3        | 2.68%   |
| JRY HDMI JRY2700 1920x1080 600x330mm 27.0-inch                        | 3        | 2.68%   |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch            | 2        | 1.79%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                      | 2        | 1.79%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch   | 2        | 1.79%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 480x270mm 21.7-inch     | 2        | 1.79%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 1.79%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch              | 2        | 1.79%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                      | 2        | 1.79%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 2        | 1.79%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 1.79%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                        | 2        | 1.79%   |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch                | 1        | 0.89%   |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch         | 1        | 0.89%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1        | 0.89%   |
| ViewSonic VX2240w VSC6B20 1680x1050 495x291mm 22.6-inch               | 1        | 0.89%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch               | 1        | 0.89%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1        | 0.89%   |
| ViewSonic VA702b VSC231C 1280x1024 338x270mm 17.0-inch                | 1        | 0.89%   |
| ViewSonic VA2415-FHD VSC533C 1920x1080 527x296mm 23.8-inch            | 1        | 0.89%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch         | 1        | 0.89%   |
| ViewSonic VA2233-FHD VSCCD3E 1920x1080 479x260mm 21.5-inch            | 1        | 0.89%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch          | 1        | 0.89%   |
| ViewSonic VA1903a VSC8A31 1366x768 410x230mm 18.5-inch                | 1        | 0.89%   |
| ViewSonic LCD Monitor VX2240w 3600x1080                               | 1        | 0.89%   |
| ViewSonic LCD Monitor VA2261                                          | 1        | 0.89%   |
| Unknown LCD Monitor XXX AAA 1920x1080                                 | 1        | 0.89%   |
| Unknown LCD Monitor RTK 2944x1080                                     | 1        | 0.89%   |
| Sony LCD Monitor TV                                                   | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch  | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 0.89%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch    | 1        | 0.89%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 0.89%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch | 1        | 0.89%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch     | 1        | 0.89%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 38       | 36.54%  |
| 1366x768 (WXGA)    | 17       | 16.35%  |
| 3840x2160 (4K)     | 7        | 6.73%   |
| 1600x900 (HD+)     | 6        | 5.77%   |
| 1280x1024 (SXGA)   | 6        | 5.77%   |
| Unknown            | 5        | 4.81%   |
| 2560x1440 (QHD)    | 4        | 3.85%   |
| 1680x1050 (WSXGA+) | 4        | 3.85%   |
| 1440x900 (WXGA+)   | 4        | 3.85%   |
| 1360x768           | 4        | 3.85%   |
| 2960x900           | 2        | 1.92%   |
| 1280x720 (HD)      | 2        | 1.92%   |
| 3600x1080          | 1        | 0.96%   |
| 3440x1440          | 1        | 0.96%   |
| 2944x1080          | 1        | 0.96%   |
| 2560x1080          | 1        | 0.96%   |
| 1280x768           | 1        | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 16       | 15.24%  |
| 18      | 16       | 15.24%  |
| 23      | 14       | 13.33%  |
| Unknown | 10       | 9.52%   |
| 19      | 6        | 5.71%   |
| 15      | 6        | 5.71%   |
| 27      | 5        | 4.76%   |
| 24      | 5        | 4.76%   |
| 17      | 5        | 4.76%   |
| 20      | 4        | 3.81%   |
| 32      | 3        | 2.86%   |
| 31      | 3        | 2.86%   |
| 84      | 2        | 1.9%    |
| 44      | 2        | 1.9%    |
| 40      | 2        | 1.9%    |
| 34      | 2        | 1.9%    |
| 22      | 2        | 1.9%    |
| 48      | 1        | 0.95%   |
| 16      | 1        | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 41       | 39.81%  |
| 501-600     | 22       | 21.36%  |
| Unknown     | 10       | 9.71%   |
| 301-350     | 9        | 8.74%   |
| 351-400     | 6        | 5.83%   |
| 701-800     | 5        | 4.85%   |
| 601-700     | 3        | 2.91%   |
| 801-900     | 2        | 1.94%   |
| 1501-2000   | 2        | 1.94%   |
| 901-1000    | 2        | 1.94%   |
| 1001-1500   | 1        | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 70       | 72.92%  |
| Unknown | 10       | 10.42%  |
| 16/10   | 8        | 8.33%   |
| 5/4     | 6        | 6.25%   |
| 21/9    | 2        | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 27.72%  |
| 151-200        | 18       | 17.82%  |
| 141-150        | 16       | 15.84%  |
| Unknown        | 10       | 9.9%    |
| 351-500        | 7        | 6.93%   |
| 301-350        | 5        | 4.95%   |
| 101-110        | 5        | 4.95%   |
| 501-1000       | 4        | 3.96%   |
| More than 1000 | 3        | 2.97%   |
| 131-140        | 2        | 1.98%   |
| 251-300        | 1        | 0.99%   |
| 121-130        | 1        | 0.99%   |
| 91-100         | 1        | 0.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 63       | 63.64%  |
| 101-120 | 19       | 19.19%  |
| Unknown | 10       | 10.1%   |
| 1-50    | 4        | 4.04%   |
| 121-160 | 2        | 2.02%   |
| 161-240 | 1        | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 89       | 74.79%  |
| 2     | 17       | 14.29%  |
| 0     | 12       | 10.08%  |
| 4     | 1        | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 70       | 43.75%  |
| Intel                 | 39       | 24.38%  |
| Qualcomm Atheros      | 12       | 7.5%    |
| TP-Link               | 7        | 4.38%   |
| Ralink Technology     | 7        | 4.38%   |
| Nvidia                | 6        | 3.75%   |
| Broadcom              | 4        | 2.5%    |
| Broadcom Limited      | 3        | 1.88%   |
| Xiaomi                | 2        | 1.25%   |
| Mercucys              | 2        | 1.25%   |
| Huawei Technologies   | 2        | 1.25%   |
| VIA Technologies      | 1        | 0.63%   |
| Texas Instruments     | 1        | 0.63%   |
| Samsung Electronics   | 1        | 0.63%   |
| Ralink                | 1        | 0.63%   |
| Qualcomm              | 1        | 0.63%   |
| MediaTek              | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 58       | 31.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 10       | 5.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 7        | 3.85%   |
| Nvidia MCP61 Ethernet                                                                         | 6        | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                                             | 5        | 2.75%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 2.2%    |
| Intel Ethernet Connection (7) I219-V                                                          | 4        | 2.2%    |
| Intel Ethernet Connection (2) I219-V                                                          | 4        | 2.2%    |
| TP-Link 802.11ac NIC                                                                          | 3        | 1.65%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 1.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 3        | 1.65%   |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 1.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 1.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.1%    |
| Realtek 802.11ac NIC                                                                          | 2        | 1.1%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 1.1%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 1.1%    |
| Mercucys 802.11n NIC                                                                          | 2        | 1.1%    |
| Intel I211 Gigabit Network Connection                                                         | 2        | 1.1%    |
| Intel Ethernet Connection I217-LM                                                             | 2        | 1.1%    |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 1.1%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                          | 2        | 1.1%    |
| Huawei E353/E3131                                                                             | 2        | 1.1%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 2        | 1.1%    |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 0.55%   |
| VIA AC'97 Modem Controller                                                                    | 1        | 0.55%   |
| Texas Instruments CC2531 ZigBee                                                               | 1        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1        | 0.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 1        | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.55%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.55%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                      | 1        | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1        | 0.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 1        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.55%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 40.38%  |
| TP-Link               | 7        | 13.46%  |
| Ralink Technology     | 7        | 13.46%  |
| Intel                 | 7        | 13.46%  |
| Qualcomm Atheros      | 4        | 7.69%   |
| Mercucys              | 2        | 3.85%   |
| Broadcom              | 2        | 3.85%   |
| Ralink                | 1        | 1.92%   |
| MediaTek              | 1        | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 7        | 13.46%  |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 7.69%   |
| TP-Link 802.11ac NIC                                                                          | 3        | 5.77%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 5.77%   |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 5.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 3.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 3.85%   |
| Realtek 802.11ac NIC                                                                          | 2        | 3.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 3.85%   |
| Mercucys 802.11n NIC                                                                          | 2        | 3.85%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 2        | 3.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 1        | 1.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.92%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.92%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.92%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.92%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                      | 1        | 1.92%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.92%   |
| Ralink RT2070 Wireless Adapter                                                                | 1        | 1.92%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.92%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 1.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 1.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 1.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 1.92%   |
| Intel Wireless 8260                                                                           | 1        | 1.92%   |
| Intel Wireless 3165                                                                           | 1        | 1.92%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                             | 1        | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 65       | 51.59%  |
| Intel                 | 35       | 27.78%  |
| Qualcomm Atheros      | 8        | 6.35%   |
| Nvidia                | 6        | 4.76%   |
| Broadcom Limited      | 3        | 2.38%   |
| Xiaomi                | 2        | 1.59%   |
| Huawei Technologies   | 2        | 1.59%   |
| Broadcom              | 2        | 1.59%   |
| VIA Technologies      | 1        | 0.79%   |
| Samsung Electronics   | 1        | 0.79%   |
| Qualcomm              | 1        | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 58       | 45.31%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10       | 7.81%   |
| Nvidia MCP61 Ethernet                                                  | 6        | 4.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 3.91%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 3.13%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 3.13%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 3        | 2.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 1.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 1.56%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 1.56%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 1.56%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 1.56%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 2        | 1.56%   |
| Huawei E353/E3131                                                      | 2        | 1.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.78%   |
| Qualcomm Nokia G42 5G                                                  | 1        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1        | 0.78%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 0.78%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 0.78%   |
| Intel Ethernet Connection (12) I219-V                                  | 1        | 0.78%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 0.78%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 0.78%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 0.78%   |
| Intel 82544GC Gigabit Ethernet Controller (LOM)                        | 1        | 0.78%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 0.78%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                    | 1        | 0.78%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 1        | 0.78%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                 | 1        | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 113      | 69.75%  |
| WiFi     | 47       | 29.01%  |
| Modem    | 2        | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 84       | 73.04%  |
| WiFi     | 31       | 26.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 89       | 77.39%  |
| 2     | 22       | 19.13%  |
| 3     | 2        | 1.74%   |
| 0     | 2        | 1.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 57.63%  |
| Yes  | 50       | 42.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 8        | 36.36%  |
| Intel                           | 7        | 31.82%  |
| Realtek Semiconductor           | 3        | 13.64%  |
| IMC Networks                    | 2        | 9.09%   |
| TP-Link                         | 1        | 4.55%   |
| Qualcomm Atheros Communications | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 36.36%  |
| Realtek Bluetooth Radio                             | 3        | 13.64%  |
| Intel AX200 Bluetooth                               | 3        | 13.64%  |
| TP-Link UB500 Adapter                               | 1        | 4.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.55%   |
| Intel Bluetooth wireless interface                  | 1        | 4.55%   |
| Intel Bluetooth Device                              | 1        | 4.55%   |
| Intel AX211 Bluetooth                               | 1        | 4.55%   |
| IMC Networks Wireless_Device                        | 1        | 4.55%   |
| IMC Networks Bluetooth Radio                        | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 68       | 37.36%  |
| Nvidia                 | 47       | 25.82%  |
| AMD                    | 43       | 23.63%  |
| Logitech               | 4        | 2.2%    |
| C-Media Electronics    | 4        | 2.2%    |
| VIA Technologies       | 2        | 1.1%    |
| Samson Technologies    | 2        | 1.1%    |
| Focusrite-Novation     | 2        | 1.1%    |
| Creative Labs          | 2        | 1.1%    |
| Texas Instruments      | 1        | 0.55%   |
| Rockwell International | 1        | 0.55%   |
| KTMicro                | 1        | 0.55%   |
| Kingston Technology    | 1        | 0.55%   |
| JMTek                  | 1        | 0.55%   |
| Elgato Systems         | 1        | 0.55%   |
| Edifier Technology     | 1        | 0.55%   |
| Creative Technology    | 1        | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 15       | 6.82%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 11       | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 9        | 4.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 9        | 4.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 8        | 3.64%   |
| AMD FCH Azalia Controller                                                                       | 8        | 3.64%   |
| Nvidia High Definition Audio Controller                                                         | 7        | 3.18%   |
| Nvidia MCP61 High Definition Audio                                                              | 6        | 2.73%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 5        | 2.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 5        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 5        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                      | 5        | 2.27%   |
| Intel 200 Series PCH HD Audio                                                                   | 5        | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 5        | 2.27%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 4        | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 4        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 4        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 4        | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 4        | 1.82%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 3        | 1.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 3        | 1.36%   |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 3        | 1.36%   |
| C-Media Electronics USB Audio Device                                                            | 3        | 1.36%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 3        | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 3        | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 3        | 1.36%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3        | 1.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 2        | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 2        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 2        | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 2        | 0.91%   |
| Nvidia GA106 High Definition Audio Controller                                                   | 2        | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 2        | 0.91%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 2        | 0.91%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 2        | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 2        | 0.91%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2        | 0.91%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                          | 2        | 0.91%   |
| AMD Navi 10 HDMI Audio                                                                          | 2        | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 20       | 23.53%  |
| Crucial                      | 13       | 15.29%  |
| Unknown                      | 10       | 11.76%  |
| Samsung Electronics          | 6        | 7.06%   |
| Micron Technology            | 5        | 5.88%   |
| SK hynix                     | 4        | 4.71%   |
| Hikvision                    | 4        | 4.71%   |
| Team                         | 2        | 2.35%   |
| Patriot                      | 2        | 2.35%   |
| Nanya Technology             | 2        | 2.35%   |
| Corsair                      | 2        | 2.35%   |
| Avant                        | 2        | 2.35%   |
| A-DATA Technology            | 2        | 2.35%   |
| Unknown (89F7)               | 1        | 1.18%   |
| Unknown (2C0B)               | 1        | 1.18%   |
| Unknown (0x5846)             | 1        | 1.18%   |
| Smart                        | 1        | 1.18%   |
| Patriot Memory (PDP Systems) | 1        | 1.18%   |
| Netac                        | 1        | 1.18%   |
| KLEVV                        | 1        | 1.18%   |
| Infineon                     | 1        | 1.18%   |
| GeIL                         | 1        | 1.18%   |
| Elpida                       | 1        | 1.18%   |
| Unknown                      | 1        | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s               | 3        | 3.3%    |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s                | 3        | 3.3%    |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s                  | 2        | 2.2%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                    | 2        | 2.2%    |
| Kingston RAM KF552C40-16 16GB DIMM 5200MT/s                          | 2        | 2.2%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                            | 1        | 1.1%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                            | 1        | 1.1%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                                 | 1        | 1.1%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                                 | 1        | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                         | 1        | 1.1%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                              | 1        | 1.1%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                         | 1        | 1.1%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                              | 1        | 1.1%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                             | 1        | 1.1%    |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s                           | 1        | 1.1%    |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s               | 1        | 1.1%    |
| Unknown (89F7) RAM Module 8GB DIMM DDR3 1600MT/s                     | 1        | 1.1%    |
| Unknown (2C0B) RAM Module 8GB DIMM DDR4 2400MT/s                     | 1        | 1.1%    |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s        | 1        | 1.1%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s                  | 1        | 1.1%    |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s                           | 1        | 1.1%    |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s                  | 1        | 1.1%    |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                           | 1        | 1.1%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s               | 1        | 1.1%    |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s                 | 1        | 1.1%    |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s                 | 1        | 1.1%    |
| Samsung RAM Module 4GB DIMM DDR3 1066MT/s                            | 1        | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                | 1        | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                | 1        | 1.1%    |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s                      | 1        | 1.1%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                  | 1        | 1.1%    |
| Samsung RAM M378B5673EH1-CF8 2GB DIMM DDR3 1067MT/s                  | 1        | 1.1%    |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                  | 1        | 1.1%    |
| Patriot RAM PSD48G320081 8192MB DIMM DDR4 3200MT/s                   | 1        | 1.1%    |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s                     | 1        | 1.1%    |
| Patriot Memory (PDP Systems) RAM PSD48G266681 8GB DIMM DDR4 2667MT/s | 1        | 1.1%    |
| Netac RAM Module 16GB DIMM DDR4 2667MT/s                             | 1        | 1.1%    |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                   | 1        | 1.1%    |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1600MT/s                   | 1        | 1.1%    |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                             | 1        | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 29       | 44.62%  |
| DDR4    | 27       | 41.54%  |
| Unknown | 3        | 4.62%   |
| DDR5    | 2        | 3.08%   |
| DDR     | 2        | 3.08%   |
| SDRAM   | 1        | 1.54%   |
| DDR2    | 1        | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 60       | 93.75%  |
| SODIMM | 3        | 4.69%   |
| RIMM   | 1        | 1.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 26       | 32.1%   |
| 4096  | 20       | 24.69%  |
| 16384 | 18       | 22.22%  |
| 2048  | 12       | 14.81%  |
| 32768 | 3        | 3.7%    |
| 1024  | 1        | 1.23%   |
| 256   | 1        | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 15       | 19.74%  |
| 1333  | 14       | 18.42%  |
| 2667  | 9        | 11.84%  |
| 3600  | 4        | 5.26%   |
| 3200  | 4        | 5.26%   |
| 2400  | 3        | 3.95%   |
| 2133  | 3        | 3.95%   |
| 5200  | 2        | 2.63%   |
| 3800  | 2        | 2.63%   |
| 3466  | 2        | 2.63%   |
| 3000  | 2        | 2.63%   |
| 2666  | 2        | 2.63%   |
| 3733  | 1        | 1.32%   |
| 3500  | 1        | 1.32%   |
| 3400  | 1        | 1.32%   |
| 2473  | 1        | 1.32%   |
| 2176  | 1        | 1.32%   |
| 1867  | 1        | 1.32%   |
| 1866  | 1        | 1.32%   |
| 1800  | 1        | 1.32%   |
| 1067  | 1        | 1.32%   |
| 1066  | 1        | 1.32%   |
| 667   | 1        | 1.32%   |
| 533   | 1        | 1.32%   |
| 333   | 1        | 1.32%   |
| 266   | 1        | 1.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Xerox              | 1        | 25%     |
| Hewlett-Packard    | 1        | 25%     |
| Canon              | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Xerox Phaser 3040 | 1        | 20%     |
| HP Laser 107w     | 1        | 20%     |
| Canon PIXMA MP250 | 1        | 20%     |
| Brother DCP-T500W | 1        | 20%     |
| Brother DCP-T420W | 1        | 20%     |

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
| Logitech                               | 9        | 47.37%  |
| Apple                                  | 2        | 10.53%  |
| Unknown                                | 1        | 5.26%   |
| Sony                                   | 1        | 5.26%   |
| Samsung Electronics                    | 1        | 5.26%   |
| Microdia                               | 1        | 5.26%   |
| GEMBIRD                                | 1        | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 5.26%   |
| Aveo Technology                        | 1        | 5.26%   |
| A4Tech                                 | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 15.79%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 2        | 10.53%  |
| Unknown HD camera                                 | 1        | 5.26%   |
| Sony CEVCECM                                      | 1        | 5.26%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1        | 5.26%   |
| Microdia USB 2.0 Camera                           | 1        | 5.26%   |
| Logitech Webcam C930e                             | 1        | 5.26%   |
| Logitech Webcam C925e                             | 1        | 5.26%   |
| Logitech Webcam C170                              | 1        | 5.26%   |
| Logitech Webcam C110                              | 1        | 5.26%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 5.26%   |
| Logitech C505e HD Webcam                          | 1        | 5.26%   |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) FS13FF-183 | 1        | 5.26%   |
| Aveo USB2.0 Camera                                | 1        | 5.26%   |
| A4Tech REDRAGON Live Camera                       | 1        | 5.26%   |

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
| 0     | 98       | 82.35%  |
| 1     | 18       | 15.13%  |
| 2     | 2        | 1.68%   |
| 3     | 1        | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 43.48%  |
| Net/wireless             | 8        | 34.78%  |
| Unassigned class         | 2        | 8.7%    |
| Sound                    | 2        | 8.7%    |
| Communication controller | 1        | 4.35%   |

