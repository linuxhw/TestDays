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

Total: 133

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 11       | 12.09%  |
| OpenMandriva 4.3   | 11       | 12.09%  |
| Ubuntu 18.04       | 6        | 6.59%   |
| Manjaro            | 5        | 5.49%   |
| Xubuntu 20.04      | 4        | 4.4%    |
| Linux Mint 19.3    | 3        | 3.3%    |
| Ubuntu 22.04       | 2        | 2.2%    |
| Ubuntu 18.10       | 2        | 2.2%    |
| ROSA R11.1         | 2        | 2.2%    |
| Pop!_OS 20.04      | 2        | 2.2%    |
| OpenMandriva 23.01 | 2        | 2.2%    |
| Linux Mint 20      | 2        | 2.2%    |
| KDE neon 20.04     | 2        | 2.2%    |
| Debian 11          | 2        | 2.2%    |
| BlackPanther 18.1  | 2        | 2.2%    |
| ArcoLinux Rolling  | 2        | 2.2%    |
| Arch               | 2        | 2.2%    |
| Zorin 16           | 1        | 1.1%    |
| Zorin 15           | 1        | 1.1%    |
| Xubuntu 21.04      | 1        | 1.1%    |
| Xubuntu 18.04      | 1        | 1.1%    |
| Ubuntu 21.10       | 1        | 1.1%    |
| Ubuntu 19.04       | 1        | 1.1%    |
| Pop!_OS 22.04      | 1        | 1.1%    |
| Pop!_OS 21.10      | 1        | 1.1%    |
| OpenMandriva 4.90  | 1        | 1.1%    |
| OpenMandriva 4.50  | 1        | 1.1%    |
| OpenMandriva 4.2   | 1        | 1.1%    |
| Lubuntu 18.04      | 1        | 1.1%    |
| Lubuntu 16.10      | 1        | 1.1%    |
| LMDE 4             | 1        | 1.1%    |
| LinuxFX 11.1       | 1        | 1.1%    |
| Linux Mint 21.1    | 1        | 1.1%    |
| Linux Mint 21      | 1        | 1.1%    |
| Linux Mint 20.3    | 1        | 1.1%    |
| Linux Mint 20.2    | 1        | 1.1%    |
| Linux Mint 19.1    | 1        | 1.1%    |
| KDE neon 18.04     | 1        | 1.1%    |
| Fedora 37          | 1        | 1.1%    |
| Fedora 36          | 1        | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 22       | 24.44%  |
| OpenMandriva | 16       | 17.78%  |
| Linux Mint   | 10       | 11.11%  |
| Xubuntu      | 6        | 6.67%   |
| Manjaro      | 5        | 5.56%   |
| Fedora       | 5        | 5.56%   |
| Pop!_OS      | 4        | 4.44%   |
| KDE neon     | 3        | 3.33%   |
| Debian       | 3        | 3.33%   |
| Arch         | 3        | 3.33%   |
| Zorin        | 2        | 2.22%   |
| ROSA         | 2        | 2.22%   |
| Lubuntu      | 2        | 2.22%   |
| BlackPanther | 2        | 2.22%   |
| ArcoLinux    | 2        | 2.22%   |
| LMDE         | 1        | 1.11%   |
| LinuxFX      | 1        | 1.11%   |
| Endless      | 1        | 1.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.16.7-desktop-1omv4003     | 11       | 11.34%  |
| 5.4.0-42-generic            | 4        | 4.12%   |
| 5.3.0-46-generic            | 3        | 3.09%   |
| 6.1.1-desktop-1omv2290      | 2        | 2.06%   |
| 5.4.83-generic-2rosa-x86_64 | 2        | 2.06%   |
| 5.4.0-65-generic            | 2        | 2.06%   |
| 5.15.60-1-MANJARO           | 2        | 2.06%   |
| 5.15.0-67-generic           | 2        | 2.06%   |
| 5.15.0-48-generic           | 2        | 2.06%   |
| 5.11.0-38-generic           | 2        | 2.06%   |
| 5.0.0-32-generic            | 2        | 2.06%   |
| 4.18.16-desktop-1bP         | 2        | 2.06%   |
| 6.1.11-arch1-1              | 1        | 1.03%   |
| 6.0.18-300.fc37.x86_64      | 1        | 1.03%   |
| 6.0.0-1-MANJARO             | 1        | 1.03%   |
| 5.6.0-2-amd64               | 1        | 1.03%   |
| 5.4.0-92-lowlatency         | 1        | 1.03%   |
| 5.4.0-91-generic            | 1        | 1.03%   |
| 5.4.0-72-generic            | 1        | 1.03%   |
| 5.4.0-62-generic            | 1        | 1.03%   |
| 5.4.0-56-generic            | 1        | 1.03%   |
| 5.4.0-52-generic            | 1        | 1.03%   |
| 5.4.0-39-generic            | 1        | 1.03%   |
| 5.4.0-33-generic            | 1        | 1.03%   |
| 5.4.0-29-generic            | 1        | 1.03%   |
| 5.4.0-26-generic            | 1        | 1.03%   |
| 5.4.0-137-lowlatency        | 1        | 1.03%   |
| 5.4.0-0.bpo.4-amd64         | 1        | 1.03%   |
| 5.3.0-51-generic            | 1        | 1.03%   |
| 5.3.0-40-generic            | 1        | 1.03%   |
| 5.19.16-2-MANJARO           | 1        | 1.03%   |
| 5.18.12-desktop-3omv4090    | 1        | 1.03%   |
| 5.18.12-arch1-1             | 1        | 1.03%   |
| 5.18.10-76051810-generic    | 1        | 1.03%   |
| 5.17.5-300.fc36.x86_64      | 1        | 1.03%   |
| 5.17.12-200.fc35.x86_64     | 1        | 1.03%   |
| 5.15.74-3-MANJARO           | 1        | 1.03%   |
| 5.15.23-76051523-generic    | 1        | 1.03%   |
| 5.15.0-53-generic           | 1        | 1.03%   |
| 5.15.0-47-generic           | 1        | 1.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 17       | 18.09%  |
| 5.16.7  | 11       | 11.7%   |
| 5.15.0  | 7        | 7.45%   |
| 4.15.0  | 7        | 7.45%   |
| 5.11.0  | 6        | 6.38%   |
| 5.3.0   | 5        | 5.32%   |
| 5.13.0  | 3        | 3.19%   |
| 5.0.0   | 3        | 3.19%   |
| 4.18.0  | 3        | 3.19%   |
| 6.1.1   | 2        | 2.13%   |
| 5.4.83  | 2        | 2.13%   |
| 5.18.12 | 2        | 2.13%   |
| 5.15.60 | 2        | 2.13%   |
| 5.10.0  | 2        | 2.13%   |
| 4.18.16 | 2        | 2.13%   |
| 6.1.11  | 1        | 1.06%   |
| 6.0.18  | 1        | 1.06%   |
| 6.0.0   | 1        | 1.06%   |
| 5.6.0   | 1        | 1.06%   |
| 5.19.16 | 1        | 1.06%   |
| 5.18.10 | 1        | 1.06%   |
| 5.17.5  | 1        | 1.06%   |
| 5.17.12 | 1        | 1.06%   |
| 5.15.74 | 1        | 1.06%   |
| 5.15.23 | 1        | 1.06%   |
| 5.13.12 | 1        | 1.06%   |
| 5.12.8  | 1        | 1.06%   |
| 5.12.4  | 1        | 1.06%   |
| 5.12.3  | 1        | 1.06%   |
| 5.12.15 | 1        | 1.06%   |
| 5.11.18 | 1        | 1.06%   |
| 5.11.15 | 1        | 1.06%   |
| 5.10.16 | 1        | 1.06%   |
| 5.10.14 | 1        | 1.06%   |
| 4.8.0   | 1        | 1.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 19       | 20.21%  |
| 5.16    | 11       | 11.7%   |
| 5.15    | 11       | 11.7%   |
| 5.11    | 8        | 8.51%   |
| 4.15    | 7        | 7.45%   |
| 5.3     | 5        | 5.32%   |
| 4.18    | 5        | 5.32%   |
| 5.13    | 4        | 4.26%   |
| 5.12    | 4        | 4.26%   |
| 5.10    | 4        | 4.26%   |
| 6.1     | 3        | 3.19%   |
| 5.18    | 3        | 3.19%   |
| 5.0     | 3        | 3.19%   |
| 6.0     | 2        | 2.13%   |
| 5.17    | 2        | 2.13%   |
| 5.6     | 1        | 1.06%   |
| 5.19    | 1        | 1.06%   |
| 4.8     | 1        | 1.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 84       | 96.55%  |
| i686   | 3        | 3.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 28       | 31.11%  |
| KDE5       | 27       | 30%     |
| X-Cinnamon | 8        | 8.89%   |
| Unknown    | 8        | 8.89%   |
| XFCE       | 7        | 7.78%   |
| LXDE       | 3        | 3.33%   |
| MATE       | 2        | 2.22%   |
| KDE4       | 2        | 2.22%   |
| KDE        | 2        | 2.22%   |
| qtile      | 1        | 1.11%   |
| ICEWM      | 1        | 1.11%   |
| Cinnamon   | 1        | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 77       | 85.56%  |
| Wayland | 7        | 7.78%   |
| Unknown | 4        | 4.44%   |
| Tty     | 2        | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 51.14%  |
| SDDM    | 23       | 26.14%  |
| LightDM | 10       | 11.36%  |
| GDM     | 5        | 5.68%   |
| KDM     | 2        | 2.27%   |
| GDM3    | 2        | 2.27%   |
| TDM     | 1        | 1.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_UY   | 47       | 52.22%  |
| en_US   | 18       | 20%     |
| es_ES   | 10       | 11.11%  |
| Unknown | 8        | 8.89%   |
| es_AR   | 4        | 4.44%   |
| C       | 3        | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 55       | 61.8%   |
| EFI  | 34       | 38.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 66       | 74.16%  |
| Overlay | 18       | 20.22%  |
| Btrfs   | 3        | 3.37%   |
| Xfs     | 1        | 1.12%   |
| Unknown | 1        | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 47       | 53.41%  |
| GPT     | 30       | 34.09%  |
| MBR     | 11       | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 75.86%  |
| Yes       | 21       | 24.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 56.82%  |
| Yes       | 38       | 43.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 17       | 19.54%  |
| ASRock              | 16       | 18.39%  |
| ASUSTek Computer    | 15       | 17.24%  |
| MSI                 | 12       | 13.79%  |
| Hewlett-Packard     | 9        | 10.34%  |
| Dell                | 4        | 4.6%    |
| Biostar             | 3        | 3.45%   |
| Intel               | 2        | 2.3%    |
| Supermicro          | 1        | 1.15%   |
| MACHINIST           | 1        | 1.15%   |
| Lenovo              | 1        | 1.15%   |
| Huanan              | 1        | 1.15%   |
| Gateway             | 1        | 1.15%   |
| Fujitsu             | 1        | 1.15%   |
| Foxconn             | 1        | 1.15%   |
| ECS                 | 1        | 1.15%   |
| AZW                 | 1        | 1.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                             | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| MSI MS-7C37                                                      | 2        | 2.3%    |
| MSI MS-7721                                                      | 2        | 2.3%    |
| Gigabyte Z390 AORUS ELITE                                        | 2        | 2.3%    |
| Gigabyte H61M-S1                                                 | 2        | 2.3%    |
| ASRock N68-S                                                     | 2        | 2.3%    |
| ASRock H310CM-HDV                                                | 2        | 2.3%    |
| ASRock FM2A58M-VG3+ R2.0                                         | 2        | 2.3%    |
| ASRock ALiveNF6P-VSTA                                            | 2        | 2.3%    |
| Supermicro P4DMS                                                 | 1        | 1.15%   |
| MSI Pro 3130 Microtower PC                                       | 1        | 1.15%   |
| MSI MS-7C09                                                      | 1        | 1.15%   |
| MSI MS-7817                                                      | 1        | 1.15%   |
| MSI MS-7816                                                      | 1        | 1.15%   |
| MSI MS-7788                                                      | 1        | 1.15%   |
| MSI MS-7786                                                      | 1        | 1.15%   |
| MSI MS-7592                                                      | 1        | 1.15%   |
| MSI MS-7383                                                      | 1        | 1.15%   |
| MACHINIST X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V309 | 1        | 1.15%   |
| Lenovo ThinkCentre M92p 3238BK7                                  | 1        | 1.15%   |
| Intel H61M-DS2                                                   | 1        | 1.15%   |
| Intel DP35DP AAD81073-208                                        | 1        | 1.15%   |
| Huanan X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V3.3    | 1        | 1.15%   |
| HP rp5800                                                        | 1        | 1.15%   |
| HP EliteDesk 800 G1 SFF                                          | 1        | 1.15%   |
| HP EliteDesk 705 G3 SFF                                          | 1        | 1.15%   |
| HP dc5000 SFF(DX854AV)                                           | 1        | 1.15%   |
| HP Compaq Pro 6300 SFF                                           | 1        | 1.15%   |
| HP Compaq dc7800p Small Form Factor                              | 1        | 1.15%   |
| HP Compaq 6200 Pro SFF PC                                        | 1        | 1.15%   |
| HP Compaq 6005 Pro MT PC                                         | 1        | 1.15%   |
| HP Compaq 6000 Pro SFF PC                                        | 1        | 1.15%   |
| Gigabyte Z87X-UD4H                                               | 1        | 1.15%   |
| Gigabyte Z370 AORUS Gaming 7                                     | 1        | 1.15%   |
| Gigabyte Z170X-Gaming 3                                          | 1        | 1.15%   |
| Gigabyte X570 GAMING X                                           | 1        | 1.15%   |
| Gigabyte H81M-DS2                                                | 1        | 1.15%   |
| Gigabyte H410M H V3                                              | 1        | 1.15%   |
| Gigabyte H310M A                                                 | 1        | 1.15%   |
| Gigabyte GA-970A-D3                                              | 1        | 1.15%   |
| Gigabyte GA-78LMT-S2                                             | 1        | 1.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 5        | 5.75%   |
| Dell OptiPlex         | 3        | 3.45%   |
| ASUS PRIME            | 3        | 3.45%   |
| MSI MS-7C37           | 2        | 2.3%    |
| MSI MS-7721           | 2        | 2.3%    |
| HP EliteDesk          | 2        | 2.3%    |
| Gigabyte Z390         | 2        | 2.3%    |
| Gigabyte H61M-S1      | 2        | 2.3%    |
| ASUS TUF              | 2        | 2.3%    |
| ASRock N68-S          | 2        | 2.3%    |
| ASRock H310CM-HDV     | 2        | 2.3%    |
| ASRock FM2A58M-VG3+   | 2        | 2.3%    |
| ASRock ALiveNF6P-VSTA | 2        | 2.3%    |
| ASRock A320M-HDV      | 2        | 2.3%    |
| Supermicro P4DMS      | 1        | 1.15%   |
| MSI Pro               | 1        | 1.15%   |
| MSI MS-7C09           | 1        | 1.15%   |
| MSI MS-7817           | 1        | 1.15%   |
| MSI MS-7816           | 1        | 1.15%   |
| MSI MS-7788           | 1        | 1.15%   |
| MSI MS-7786           | 1        | 1.15%   |
| MSI MS-7592           | 1        | 1.15%   |
| MSI MS-7383           | 1        | 1.15%   |
| MACHINIST X79         | 1        | 1.15%   |
| Lenovo ThinkCentre    | 1        | 1.15%   |
| Intel H61M-DS2        | 1        | 1.15%   |
| Intel DP35DP          | 1        | 1.15%   |
| Huanan X79            | 1        | 1.15%   |
| HP rp5800             | 1        | 1.15%   |
| HP dc5000             | 1        | 1.15%   |
| Gigabyte Z87X-UD4H    | 1        | 1.15%   |
| Gigabyte Z370         | 1        | 1.15%   |
| Gigabyte Z170X-Gaming | 1        | 1.15%   |
| Gigabyte X570         | 1        | 1.15%   |
| Gigabyte H81M-DS2     | 1        | 1.15%   |
| Gigabyte H410M        | 1        | 1.15%   |
| Gigabyte H310M        | 1        | 1.15%   |
| Gigabyte GA-970A-D3   | 1        | 1.15%   |
| Gigabyte GA-78LMT-S2  | 1        | 1.15%   |
| Gigabyte B460MDS3H    | 1        | 1.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 11       | 12.64%  |
| 2011 | 11       | 12.64%  |
| 2013 | 9        | 10.34%  |
| 2012 | 9        | 10.34%  |
| 2009 | 6        | 6.9%    |
| 2018 | 5        | 5.75%   |
| 2017 | 5        | 5.75%   |
| 2021 | 4        | 4.6%    |
| 2020 | 4        | 4.6%    |
| 2015 | 4        | 4.6%    |
| 2014 | 4        | 4.6%    |
| 2007 | 4        | 4.6%    |
| 2022 | 3        | 3.45%   |
| 2010 | 3        | 3.45%   |
| 2016 | 1        | 1.15%   |
| 2008 | 1        | 1.15%   |
| 2005 | 1        | 1.15%   |
| 2004 | 1        | 1.15%   |
| 2003 | 1        | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 87       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 87       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 87       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 21       | 23.33%  |
| 8.01-16.0   | 17       | 18.89%  |
| 16.01-24.0  | 16       | 17.78%  |
| 3.01-4.0    | 15       | 16.67%  |
| 32.01-64.0  | 7        | 7.78%   |
| 24.01-32.0  | 5        | 5.56%   |
| 1.01-2.0    | 4        | 4.44%   |
| 64.01-256.0 | 3        | 3.33%   |
| 0.51-1.0    | 1        | 1.11%   |
| 0.01-0.5    | 1        | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 38       | 40.43%  |
| 2.01-3.0  | 22       | 23.4%   |
| 3.01-4.0  | 13       | 13.83%  |
| 0.51-1.0  | 7        | 7.45%   |
| 4.01-8.0  | 6        | 6.38%   |
| 8.01-16.0 | 4        | 4.26%   |
| 0.01-0.5  | 4        | 4.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 41       | 45.05%  |
| 2      | 25       | 27.47%  |
| 3      | 13       | 14.29%  |
| 4      | 10       | 10.99%  |
| 5      | 2        | 2.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 54.55%  |
| Yes       | 40       | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 85       | 97.7%   |
| No        | 2        | 2.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 57.3%   |
| Yes       | 38       | 42.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 81.61%  |
| Yes       | 16       | 18.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Uruguay | 87       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Montevideo       | 69       | 76.67%  |
| Maldonado        | 3        | 3.33%   |
| Florida          | 3        | 3.33%   |
| San Jose de Mayo | 2        | 2.22%   |
| Las Piedras      | 2        | 2.22%   |
| Paysandú        | 1        | 1.11%   |
| Nuevo Paris      | 1        | 1.11%   |
| Nueva Helvecia   | 1        | 1.11%   |
| Melo             | 1        | 1.11%   |
| Malvin Norte     | 1        | 1.11%   |
| Libertad         | 1        | 1.11%   |
| La Paz           | 1        | 1.11%   |
| Durazno          | 1        | 1.11%   |
| Ciudad del Plata | 1        | 1.11%   |
| Centro           | 1        | 1.11%   |
| Unknown          | 1        | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 45       | 58     | 29.22%  |
| Seagate                   | 28       | 37     | 18.18%  |
| Kingston                  | 20       | 23     | 12.99%  |
| Samsung Electronics       | 19       | 20     | 12.34%  |
| Toshiba                   | 13       | 18     | 8.44%   |
| Crucial                   | 5        | 7      | 3.25%   |
| Hitachi                   | 3        | 6      | 1.95%   |
| Micron/Crucial Technology | 2        | 3      | 1.3%    |
| Maxtor                    | 2        | 3      | 1.3%    |
| Hewlett-Packard           | 2        | 2      | 1.3%    |
| Biostar                   | 2        | 3      | 1.3%    |
| SK hynix                  | 1        | 1      | 0.65%   |
| Silicon Motion            | 1        | 1      | 0.65%   |
| Sandisk                   | 1        | 2      | 0.65%   |
| Phison                    | 1        | 1      | 0.65%   |
| Patriot                   | 1        | 1      | 0.65%   |
| NGFF                      | 1        | 1      | 0.65%   |
| Micron Technology         | 1        | 1      | 0.65%   |
| IBM-ESXS                  | 1        | 1      | 0.65%   |
| HS-SSD-C100               | 1        | 1      | 0.65%   |
| HGST                      | 1        | 1      | 0.65%   |
| Gigabyte Technology       | 1        | 1      | 0.65%   |
| ExcelStor                 | 1        | 1      | 0.65%   |
| A-DATA Technology         | 1        | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 6        | 3.55%   |
| Toshiba DT01ACA100 1TB           | 5        | 2.96%   |
| Samsung HD161HJ 160GB            | 5        | 2.96%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 4        | 2.37%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 2.37%   |
| Toshiba DT01ACA300 3TB           | 4        | 2.37%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 2.37%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.78%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 1.78%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 2        | 1.18%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 2        | 1.18%   |
| WDC WD10EFRX-68FYTN0 1TB         | 2        | 1.18%   |
| Seagate ST3750640NS 752GB        | 2        | 1.18%   |
| Seagate ST3250312AS 250GB        | 2        | 1.18%   |
| Seagate ST3160318AS 160GB        | 2        | 1.18%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 1.18%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.18%   |
| Samsung HD103SJ 1TB              | 2        | 1.18%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 1.18%   |
| Kingston SNVS1000G 1TB           | 2        | 1.18%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 1.18%   |
| Kingston SA2000M81000G 1TB       | 2        | 1.18%   |
| WDC WDS512G1X0C-00ENX0 512GB     | 1        | 0.59%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.59%   |
| WDC WDS250G2B0B-00YS70 250GB SSD | 1        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.59%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 1        | 0.59%   |
| WDC WD800JD-60LSA5 80GB          | 1        | 0.59%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 1        | 0.59%   |
| WDC WD5000LPVT-24G33T1 500GB     | 1        | 0.59%   |
| WDC WD5000BEVT-22A0RT0 500GB     | 1        | 0.59%   |
| WDC WD5000BEKT-60KA9T0 500GB     | 1        | 0.59%   |
| WDC WD5000AZLX-00ZR6A0 500GB     | 1        | 0.59%   |
| WDC WD5000AVVS-63ZWB0 500GB      | 1        | 0.59%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.59%   |
| WDC WD5000AAJS-00A8B0 500GB      | 1        | 0.59%   |
| WDC WD5000AADS-56S9B1 500GB      | 1        | 0.59%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 39       | 49     | 38.61%  |
| Seagate             | 28       | 37     | 27.72%  |
| Samsung Electronics | 14       | 14     | 13.86%  |
| Toshiba             | 13       | 18     | 12.87%  |
| Hitachi             | 3        | 6      | 2.97%   |
| Maxtor              | 2        | 3      | 1.98%   |
| HGST                | 1        | 1      | 0.99%   |
| ExcelStor           | 1        | 1      | 0.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 16       | 18     | 47.06%  |
| WDC                 | 6        | 6      | 17.65%  |
| Crucial             | 4        | 5      | 11.76%  |
| Samsung Electronics | 2        | 3      | 5.88%   |
| NGFF                | 1        | 1      | 2.94%   |
| Micron Technology   | 1        | 1      | 2.94%   |
| Hewlett-Packard     | 1        | 1      | 2.94%   |
| Gigabyte Technology | 1        | 1      | 2.94%   |
| Biostar             | 1        | 2      | 2.94%   |
| A-DATA Technology   | 1        | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 72       | 129    | 58.06%  |
| SSD     | 33       | 39     | 26.61%  |
| NVMe    | 16       | 23     | 12.9%   |
| Unknown | 3        | 3      | 2.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 83       | 169    | 82.18%  |
| NVMe | 16       | 23     | 15.84%  |
| SAS  | 2        | 2      | 1.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 67       | 97     | 60.36%  |
| 0.51-1.0   | 34       | 59     | 30.63%  |
| 2.01-3.0   | 5        | 6      | 4.5%    |
| 1.01-2.0   | 3        | 3      | 2.7%    |
| 3.01-4.0   | 2        | 3      | 1.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 23       | 25.27%  |
| 251-500        | 20       | 21.98%  |
| 501-1000       | 13       | 14.29%  |
| 1-20           | 11       | 12.09%  |
| 1001-2000      | 10       | 10.99%  |
| 21-50          | 4        | 4.4%    |
| Unknown        | 4        | 4.4%    |
| 51-100         | 3        | 3.3%    |
| 2001-3000      | 2        | 2.2%    |
| More than 3000 | 1        | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 38       | 41.76%  |
| 21-50     | 14       | 15.38%  |
| 101-250   | 9        | 9.89%   |
| 501-1000  | 9        | 9.89%   |
| 51-100    | 8        | 8.79%   |
| 251-500   | 5        | 5.49%   |
| Unknown   | 4        | 4.4%    |
| 1001-2000 | 3        | 3.3%    |
| 2001-3000 | 1        | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 2        | 2      | 11.11%  |
| Seagate ST3750640NS 752GB        | 2        | 7      | 11.11%  |
| Seagate ST250DM000-1BD141 250GB  | 2        | 2      | 11.11%  |
| WDC WD5000BEKT-60KA9T0 500GB     | 1        | 1      | 5.56%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 1      | 5.56%   |
| WDC WD5000AAJS-00A8B0 500GB      | 1        | 1      | 5.56%   |
| WDC WD10EARS-22Y5B1 1TB          | 1        | 1      | 5.56%   |
| Toshiba MQ01ABD075 752GB         | 1        | 1      | 5.56%   |
| Toshiba MK5059GSXP 500GB         | 1        | 1      | 5.56%   |
| Toshiba MK3276GSX 320GB          | 1        | 1      | 5.56%   |
| Toshiba DT01ACA100 1TB           | 1        | 1      | 5.56%   |
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 5.56%   |
| Seagate ST3250310CS 250GB        | 1        | 1      | 5.56%   |
| Seagate ST3200827AS 200GB        | 1        | 1      | 5.56%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 15     | 52.94%  |
| WDC     | 4        | 4      | 23.53%  |
| Toshiba | 4        | 4      | 23.53%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 15     | 52.94%  |
| WDC     | 4        | 4      | 23.53%  |
| Toshiba | 4        | 4      | 23.53%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 23     | 100%    |

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
| Detected | 50       | 107    | 50%     |
| Works    | 33       | 64     | 33%     |
| Malfunc  | 17       | 23     | 17%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 51       | 44.74%  |
| AMD                         | 30       | 26.32%  |
| Nvidia                      | 5        | 4.39%   |
| ASMedia Technology          | 5        | 4.39%   |
| SanDisk                     | 4        | 3.51%   |
| Kingston Technology Company | 4        | 3.51%   |
| Silicon Motion              | 3        | 2.63%   |
| Samsung Electronics         | 3        | 2.63%   |
| Micron/Crucial Technology   | 3        | 2.63%   |
| Marvell Technology Group    | 2        | 1.75%   |
| VIA Technologies            | 1        | 0.88%   |
| SK hynix                    | 1        | 0.88%   |
| Phison Electronics          | 1        | 0.88%   |
| Adaptec                     | 1        | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 11.92%  |
| Nvidia MCP61 SATA Controller                                                            | 5        | 3.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 3.31%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 3.31%   |
| AMD FCH IDE Controller                                                                  | 5        | 3.31%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 3.31%   |
| Nvidia MCP61 IDE                                                                        | 4        | 2.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 2.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 2.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 2.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.65%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.99%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 1.32%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 1.32%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.32%   |
| Kingston Company NVMe Controller                                                        | 2        | 1.32%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.32%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.32%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.32%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.66%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.66%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.66%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.66%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.66%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.66%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 66       | 55.46%  |
| IDE  | 32       | 26.89%  |
| NVMe | 16       | 13.45%  |
| RAID | 4        | 3.36%   |
| SCSI | 1        | 0.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 51       | 58.62%  |
| AMD    | 36       | 41.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 3        | 3.45%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 3        | 3.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 2        | 2.3%    |
| Intel Core i5-8400 CPU @ 2.80GHz                | 2        | 2.3%    |
| Intel Core i5-10400 CPU @ 2.90GHz               | 2        | 2.3%    |
| Intel Core i3-2120 CPU @ 3.30GHz                | 2        | 2.3%    |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 2.3%    |
| AMD Athlon 3000G with Radeon Vega Graphics      | 2        | 2.3%    |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 2        | 2.3%    |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz              | 1        | 1.15%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz              | 1        | 1.15%   |
| Intel Xeon CPU 2.40GHz                          | 1        | 1.15%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 1.15%   |
| Intel Pentium 4 CPU 2.80GHz                     | 1        | 1.15%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 1        | 1.15%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 1.15%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 1.15%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 1.15%   |
| Intel Core i7-4930K CPU @ 3.40GHz               | 1        | 1.15%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.15%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 1.15%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 1.15%   |
| Intel Core i7-10700F CPU @ 2.90GHz              | 1        | 1.15%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 1.15%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 1.15%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.15%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1        | 1.15%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1.15%   |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 1.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.15%   |
| Intel Core i5-2500S CPU @ 2.70GHz               | 1        | 1.15%   |
| Intel Core i5-2400S CPU @ 2.50GHz               | 1        | 1.15%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 1.15%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 1        | 1.15%   |
| Intel Core i3-9100 CPU @ 3.60GHz                | 1        | 1.15%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 1        | 1.15%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 1.15%   |
| Intel Core i3-3250 CPU @ 3.50GHz                | 1        | 1.15%   |
| Intel Core i3-3240 CPU @ 3.40GHz                | 1        | 1.15%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 15       | 17.24%  |
| Intel Core i7     | 10       | 11.49%  |
| Intel Core i3     | 10       | 11.49%  |
| AMD Ryzen 5       | 7        | 8.05%   |
| Intel Core 2 Duo  | 5        | 5.75%   |
| AMD Ryzen 7       | 5        | 5.75%   |
| AMD Athlon II X2  | 4        | 4.6%    |
| Intel Xeon        | 3        | 3.45%   |
| Intel Core 2 Quad | 3        | 3.45%   |
| AMD FX            | 3        | 3.45%   |
| AMD A10           | 3        | 3.45%   |
| Intel Celeron     | 2        | 2.3%    |
| AMD Phenom II X6  | 2        | 2.3%    |
| AMD Athlon        | 2        | 2.3%    |
| AMD A6            | 2        | 2.3%    |
| AMD A4            | 2        | 2.3%    |
| Intel Pentium 4   | 1        | 1.15%   |
| Intel Pentium     | 1        | 1.15%   |
| Intel Core i9     | 1        | 1.15%   |
| AMD Ryzen 3       | 1        | 1.15%   |
| AMD PRO A10       | 1        | 1.15%   |
| AMD Phenom        | 1        | 1.15%   |
| AMD Athlon 64 X2  | 1        | 1.15%   |
| AMD Athlon 64     | 1        | 1.15%   |
| AMD A8            | 1        | 1.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 36.78%  |
| 4      | 24       | 27.59%  |
| 6      | 18       | 20.69%  |
| 8      | 9        | 10.34%  |
| 1      | 4        | 4.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 86       | 98.85%  |
| 2      | 1        | 1.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 52       | 59.77%  |
| 1      | 35       | 40.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 84       | 96.55%  |
| 32-bit         | 2        | 2.3%    |
| Unknown        | 1        | 1.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 20.22%  |
| 0x306c3    | 6        | 6.74%   |
| 0x206a7    | 6        | 6.74%   |
| 0x306a9    | 5        | 5.62%   |
| 0x1067a    | 5        | 5.62%   |
| 0x906ea    | 4        | 4.49%   |
| 0x08701021 | 4        | 4.49%   |
| 0x06000852 | 3        | 3.37%   |
| 0xa0655    | 2        | 2.25%   |
| 0xa0653    | 2        | 2.25%   |
| 0x206d7    | 2        | 2.25%   |
| 0x20655    | 2        | 2.25%   |
| 0x08108109 | 2        | 2.25%   |
| 0x08001138 | 2        | 2.25%   |
| 0x06003106 | 2        | 2.25%   |
| 0x06001119 | 2        | 2.25%   |
| 0x010000dc | 2        | 2.25%   |
| 0xf33      | 1        | 1.12%   |
| 0xf27      | 1        | 1.12%   |
| 0x906ed    | 1        | 1.12%   |
| 0x906ec    | 1        | 1.12%   |
| 0x906eb    | 1        | 1.12%   |
| 0x906c0    | 1        | 1.12%   |
| 0x506e3    | 1        | 1.12%   |
| 0x10677    | 1        | 1.12%   |
| 0x10676    | 1        | 1.12%   |
| 0x0a50000d | 1        | 1.12%   |
| 0x0a50000c | 1        | 1.12%   |
| 0x08108102 | 1        | 1.12%   |
| 0x0800820d | 1        | 1.12%   |
| 0x08001137 | 1        | 1.12%   |
| 0x0600611a | 1        | 1.12%   |
| 0x03000027 | 1        | 1.12%   |
| 0x010000c8 | 1        | 1.12%   |
| 0x010000b6 | 1        | 1.12%   |
| 0x01000083 | 1        | 1.12%   |
| 0x00000000 | 1        | 1.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 10       | 11.49%  |
| KabyLake    | 8        | 9.2%    |
| Penryn      | 7        | 8.05%   |
| K10         | 7        | 8.05%   |
| IvyBridge   | 7        | 8.05%   |
| Haswell     | 6        | 6.9%    |
| Piledriver  | 5        | 5.75%   |
| CometLake   | 5        | 5.75%   |
| Zen+        | 4        | 4.6%    |
| Zen 3       | 4        | 4.6%    |
| Zen 2       | 4        | 4.6%    |
| Steamroller | 4        | 4.6%    |
| Zen         | 3        | 3.45%   |
| Westmere    | 2        | 2.3%    |
| Skylake     | 2        | 2.3%    |
| NetBurst    | 2        | 2.3%    |
| K8 Hammer   | 2        | 2.3%    |
| Tremont     | 1        | 1.15%   |
| K10 Llano   | 1        | 1.15%   |
| Jaguar      | 1        | 1.15%   |
| Excavator   | 1        | 1.15%   |
| Core        | 1        | 1.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 39       | 41.94%  |
| AMD    | 28       | 30.11%  |
| Intel  | 26       | 27.96%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 5.26%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 4.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 4.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 4.21%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 4.21%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 3.16%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 3.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 3.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 3.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.16%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 2.11%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 2.11%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 2.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.11%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.05%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.05%   |
| Nvidia NV34 [GeForce FX 5200]                                               | 1        | 1.05%   |
| Nvidia GT216 [GeForce 210]                                                  | 1        | 1.05%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.05%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.05%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.05%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.05%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.05%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.05%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.05%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 1.05%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.05%   |
| Nvidia GF100 [GeForce GTX 470]                                              | 1        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 1.05%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.05%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 1.05%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.05%   |
| Intel HD Graphics 530                                                       | 1        | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 37       | 42.53%  |
| 1 x AMD        | 25       | 28.74%  |
| 1 x Intel      | 21       | 24.14%  |
| 2 x AMD        | 2        | 2.3%    |
| Intel + Nvidia | 1        | 1.15%   |
| AMD + Nvidia   | 1        | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 69       | 78.41%  |
| Proprietary | 13       | 14.77%  |
| Unknown     | 6        | 6.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 38.89%  |
| 1.01-2.0   | 16       | 17.78%  |
| 0.51-1.0   | 14       | 15.56%  |
| 0.01-0.5   | 10       | 11.11%  |
| 3.01-4.0   | 8        | 8.89%   |
| 7.01-8.0   | 3        | 3.33%   |
| 5.01-6.0   | 3        | 3.33%   |
| 8.01-16.0  | 1        | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AOC                     | 14       | 17.28%  |
| ViewSonic               | 13       | 16.05%  |
| Samsung Electronics     | 11       | 13.58%  |
| KTC                     | 7        | 8.64%   |
| Goldstar                | 7        | 8.64%   |
| Acer                    | 5        | 6.17%   |
| Lenovo                  | 3        | 3.7%    |
| Hewlett-Packard         | 3        | 3.7%    |
| Unknown                 | 2        | 2.47%   |
| Dell                    | 2        | 2.47%   |
| Sony                    | 1        | 1.23%   |
| RIS                     | 1        | 1.23%   |
| Philips                 | 1        | 1.23%   |
| Panasonic               | 1        | 1.23%   |
| LG Electronics          | 1        | 1.23%   |
| Lenovo Group Limited    | 1        | 1.23%   |
| KOA                     | 1        | 1.23%   |
| HKC                     | 1        | 1.23%   |
| Hitachi                 | 1        | 1.23%   |
| Envision                | 1        | 1.23%   |
| CVT                     | 1        | 1.23%   |
| Chi Mei Optoelectronics | 1        | 1.23%   |
| BenQ                    | 1        | 1.23%   |
| Ancor Communications    | 1        | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch             | 2        | 2.35%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 2        | 2.35%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch    | 2        | 2.35%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch               | 2        | 2.35%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                       | 2        | 2.35%   |
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                   | 2        | 2.35%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 2        | 2.35%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                         | 2        | 2.35%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                         | 2        | 2.35%   |
| AOC 1621Wb AOC1621 1366x768 344x194mm 15.5-inch                        | 2        | 2.35%   |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch                 | 1        | 1.18%   |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch          | 1        | 1.18%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch          | 1        | 1.18%   |
| ViewSonic VX2240w VSC6B20 1680x1050 495x291mm 22.6-inch                | 1        | 1.18%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch                | 1        | 1.18%   |
| ViewSonic VA702 SERIES VSC231C 1280x1024 338x270mm 17.0-inch           | 1        | 1.18%   |
| ViewSonic VA2415-FHD VSC533C 1920x1080 527x296mm 23.8-inch             | 1        | 1.18%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch          | 1        | 1.18%   |
| ViewSonic VA1903a VSC8A31 1366x768 410x230mm 18.5-inch                 | 1        | 1.18%   |
| ViewSonic LCD Monitor VX2240w 3600x1080                                | 1        | 1.18%   |
| ViewSonic LCD Monitor VA2261                                           | 1        | 1.18%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                       | 1        | 1.18%   |
| Unknown LCD Monitor RTK 2944x1080                                      | 1        | 1.18%   |
| Sony LCD Monitor TV                                                    | 1        | 1.18%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch   | 1        | 1.18%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch    | 1        | 1.18%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch     | 1        | 1.18%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch   | 1        | 1.18%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch      | 1        | 1.18%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch       | 1        | 1.18%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1        | 1.18%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 1.18%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 1.18%   |
| RIS HD915L RIS0709 1360x768 410x230mm 18.5-inch                        | 1        | 1.18%   |
| Philips PHL 272V8 PHLC21A 1920x1080 598x336mm 27.0-inch                | 1        | 1.18%   |
| Panasonic LCD Monitor TV                                               | 1        | 1.18%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1        | 1.18%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch               | 1        | 1.18%   |
| Lenovo Group Limited LCD Monitor LEN T2254pC 1680x1050                 | 1        | 1.18%   |
| KTC W5006L KTC1542 1280x768 331x207mm 15.4-inch                        | 1        | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 28       | 36.36%  |
| 1366x768 (WXGA)    | 11       | 14.29%  |
| 1600x900 (HD+)     | 6        | 7.79%   |
| 3840x2160 (4K)     | 4        | 5.19%   |
| 2560x1440 (QHD)    | 4        | 5.19%   |
| 1440x900 (WXGA+)   | 4        | 5.19%   |
| 1360x768           | 4        | 5.19%   |
| 1280x1024 (SXGA)   | 4        | 5.19%   |
| 1680x1050 (WSXGA+) | 3        | 3.9%    |
| Unknown            | 3        | 3.9%    |
| 1280x720 (HD)      | 2        | 2.6%    |
| 3600x1080          | 1        | 1.3%    |
| 2944x1080          | 1        | 1.3%    |
| 2560x1080          | 1        | 1.3%    |
| 1280x768           | 1        | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 14       | 17.5%   |
| 21      | 12       | 15%     |
| 18      | 10       | 12.5%   |
| Unknown | 7        | 8.75%   |
| 19      | 6        | 7.5%    |
| 15      | 6        | 7.5%    |
| 24      | 4        | 5%      |
| 31      | 3        | 3.75%   |
| 20      | 3        | 3.75%   |
| 17      | 3        | 3.75%   |
| 84      | 2        | 2.5%    |
| 44      | 2        | 2.5%    |
| 32      | 2        | 2.5%    |
| 27      | 2        | 2.5%    |
| 22      | 2        | 2.5%    |
| 34      | 1        | 1.25%   |
| 16      | 1        | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 30       | 38.46%  |
| 501-600     | 18       | 23.08%  |
| 301-350     | 7        | 8.97%   |
| Unknown     | 7        | 8.97%   |
| 351-400     | 6        | 7.69%   |
| 701-800     | 3        | 3.85%   |
| 601-700     | 3        | 3.85%   |
| 1501-2000   | 2        | 2.56%   |
| 901-1000    | 2        | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 54       | 73.97%  |
| 16/10   | 7        | 9.59%   |
| Unknown | 7        | 9.59%   |
| 5/4     | 4        | 5.48%   |
| 21/9    | 1        | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 30.26%  |
| 151-200        | 17       | 22.37%  |
| 141-150        | 8        | 10.53%  |
| Unknown        | 7        | 9.21%   |
| 351-500        | 5        | 6.58%   |
| 101-110        | 5        | 6.58%   |
| More than 1000 | 2        | 2.63%   |
| 301-350        | 2        | 2.63%   |
| 131-140        | 2        | 2.63%   |
| 501-1000       | 2        | 2.63%   |
| 251-300        | 1        | 1.32%   |
| 121-130        | 1        | 1.32%   |
| 91-100         | 1        | 1.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 50       | 67.57%  |
| 101-120 | 11       | 14.86%  |
| Unknown | 7        | 9.46%   |
| 1-50    | 3        | 4.05%   |
| 121-160 | 2        | 2.7%    |
| 161-240 | 1        | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 66       | 74.16%  |
| 2     | 14       | 15.73%  |
| 0     | 8        | 8.99%   |
| 4     | 1        | 1.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 52       | 41.6%   |
| Intel                 | 29       | 23.2%   |
| Qualcomm Atheros      | 11       | 8.8%    |
| TP-Link               | 6        | 4.8%    |
| Ralink Technology     | 6        | 4.8%    |
| Nvidia                | 5        | 4%      |
| Broadcom              | 4        | 3.2%    |
| Xiaomi                | 2        | 1.6%    |
| Mercucys              | 2        | 1.6%    |
| Huawei Technologies   | 2        | 1.6%    |
| VIA Technologies      | 1        | 0.8%    |
| Texas Instruments     | 1        | 0.8%    |
| Samsung Electronics   | 1        | 0.8%    |
| Ralink                | 1        | 0.8%    |
| Qualcomm              | 1        | 0.8%    |
| Broadcom Limited      | 1        | 0.8%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 31.69%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 3.52%   |
| Nvidia MCP61 Ethernet                                             | 5        | 3.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 3.52%   |
| TP-Link 802.11ac NIC                                              | 3        | 2.11%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3        | 2.11%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 2.11%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.41%   |
| Realtek 802.11ac NIC                                              | 2        | 1.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 1.41%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 1.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.41%   |
| Mercucys 802.11n NIC                                              | 2        | 1.41%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.41%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.41%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.41%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 1.41%   |
| Huawei E353/E3131                                                 | 2        | 1.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.7%    |
| VIA AC'97 Modem Controller                                        | 1        | 0.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.7%    |
| Texas Instruments CC2531 ZigBee                                   | 1        | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.7%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.7%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1        | 0.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.7%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1        | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.7%    |
| Realtek 802.11ac WLAN Adapter                                     | 1        | 0.7%    |
| Ralink RT2070 Wireless Adapter                                    | 1        | 0.7%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.7%    |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 0.7%    |
| Qualcomm Fairphone 4 5G                                           | 1        | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 39.53%  |
| TP-Link               | 6        | 13.95%  |
| Ralink Technology     | 6        | 13.95%  |
| Intel                 | 5        | 11.63%  |
| Qualcomm Atheros      | 4        | 9.3%    |
| Mercucys              | 2        | 4.65%   |
| Broadcom              | 2        | 4.65%   |
| Ralink                | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 11.63%  |
| TP-Link 802.11ac NIC                                           | 3        | 6.98%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 3        | 6.98%   |
| Intel Wi-Fi 6 AX200                                            | 3        | 6.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 4.65%   |
| Realtek 802.11ac NIC                                           | 2        | 4.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 4.65%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 4.65%   |
| Mercucys 802.11n NIC                                           | 2        | 4.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2        | 4.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 2.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 2.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 2.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 2.33%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1        | 2.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 2.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1        | 2.33%   |
| Realtek 802.11ac WLAN Adapter                                  | 1        | 2.33%   |
| Ralink RT2070 Wireless Adapter                                 | 1        | 2.33%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 2.33%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 2.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 2.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 2.33%   |
| Intel Wireless 3165                                            | 1        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 48       | 50%     |
| Intel                 | 26       | 27.08%  |
| Qualcomm Atheros      | 7        | 7.29%   |
| Nvidia                | 5        | 5.21%   |
| Xiaomi                | 2        | 2.08%   |
| Huawei Technologies   | 2        | 2.08%   |
| Broadcom              | 2        | 2.08%   |
| VIA Technologies      | 1        | 1.04%   |
| Samsung Electronics   | 1        | 1.04%   |
| Qualcomm              | 1        | 1.04%   |
| Broadcom Limited      | 1        | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 46.39%  |
| Nvidia MCP61 Ethernet                                             | 5        | 5.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 5.15%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 3.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 2.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2.06%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.06%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.06%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.06%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 2.06%   |
| Huawei E353/E3131                                                 | 2        | 2.06%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.03%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.03%   |
| Qualcomm Fairphone 4 5G                                           | 1        | 1.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.03%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.03%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.03%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.03%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.03%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.03%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.03%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.03%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.03%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.03%   |
| Intel 82544GC Gigabit Ethernet Controller (LOM)                   | 1        | 1.03%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.03%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.03%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 1        | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 85       | 68%     |
| WiFi     | 38       | 30.4%   |
| Modem    | 2        | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 72.41%  |
| WiFi     | 24       | 27.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 67       | 77.01%  |
| 2     | 16       | 18.39%  |
| 3     | 2        | 2.3%    |
| 0     | 2        | 2.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 67.42%  |
| Yes  | 29       | 32.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 7        | 43.75%  |
| Intel                           | 5        | 31.25%  |
| Realtek Semiconductor           | 2        | 12.5%   |
| TP-Link                         | 1        | 6.25%   |
| Qualcomm Atheros Communications | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 43.75%  |
| Intel AX200 Bluetooth                               | 3        | 18.75%  |
| Realtek Bluetooth Radio                             | 2        | 12.5%   |
| TP-Link UB500 Adapter                               | 1        | 6.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.25%   |
| Intel Bluetooth wireless interface                  | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 50       | 36.23%  |
| Nvidia                 | 36       | 26.09%  |
| AMD                    | 33       | 23.91%  |
| Logitech               | 3        | 2.17%   |
| VIA Technologies       | 2        | 1.45%   |
| Samson Technologies    | 2        | 1.45%   |
| Creative Labs          | 2        | 1.45%   |
| C-Media Electronics    | 2        | 1.45%   |
| Texas Instruments      | 1        | 0.72%   |
| Rockwell International | 1        | 0.72%   |
| KTMicro                | 1        | 0.72%   |
| Kingston Technology    | 1        | 0.72%   |
| JMTek                  | 1        | 0.72%   |
| Focusrite-Novation     | 1        | 0.72%   |
| Elgato Systems         | 1        | 0.72%   |
| Creative Technology    | 1        | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 10       | 6.06%   |
| AMD FCH Azalia Controller                                                                       | 8        | 4.85%   |
| Nvidia High Definition Audio Controller                                                         | 7        | 4.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 6        | 3.64%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 6        | 3.64%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 6        | 3.64%   |
| Nvidia MCP61 High Definition Audio                                                              | 5        | 3.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 5        | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 5        | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 4        | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 4        | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                                      | 4        | 2.42%   |
| Intel 200 Series PCH HD Audio                                                                   | 4        | 2.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 4        | 2.42%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 3        | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 3        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3        | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 3        | 1.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 3        | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 2        | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 2        | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 2        | 1.21%   |
| Nvidia GA106 High Definition Audio Controller                                                   | 2        | 1.21%   |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 2        | 1.21%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 2        | 1.21%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 2        | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 2        | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 1.21%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2        | 1.21%   |
| AMD Navi 10 HDMI Audio                                                                          | 2        | 1.21%   |
| AMD Kaveri HDMI/DP Audio Controller                                                             | 2        | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                                        | 2        | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 2        | 1.21%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 2        | 1.21%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                       | 1        | 0.61%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                     | 1        | 0.61%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1        | 0.61%   |
| Samson Technologies Meteor condenser microphone                                                 | 1        | 0.61%   |
| Samson Technologies C03U multi-pattern microphone                                               | 1        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 15       | 23.08%  |
| Unknown             | 9        | 13.85%  |
| Crucial             | 9        | 13.85%  |
| Samsung Electronics | 5        | 7.69%   |
| Micron Technology   | 4        | 6.15%   |
| SK hynix            | 3        | 4.62%   |
| Team                | 2        | 3.08%   |
| Patriot             | 2        | 3.08%   |
| Hikvision           | 2        | 3.08%   |
| Corsair             | 2        | 3.08%   |
| A-DATA Technology   | 2        | 3.08%   |
| Unknown (2C0B)      | 1        | 1.54%   |
| Unknown (0x5846)    | 1        | 1.54%   |
| Smart               | 1        | 1.54%   |
| Netac               | 1        | 1.54%   |
| Nanya Technology    | 1        | 1.54%   |
| KLEVV               | 1        | 1.54%   |
| Infineon            | 1        | 1.54%   |
| GeIL                | 1        | 1.54%   |
| Elpida              | 1        | 1.54%   |
| Avant               | 1        | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s        | 3        | 4.29%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s           | 2        | 2.86%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s         | 2        | 2.86%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                     | 1        | 1.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 1        | 1.43%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                          | 1        | 1.43%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 1        | 1.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 1.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 1        | 1.43%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 1        | 1.43%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                       | 1        | 1.43%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                      | 1        | 1.43%   |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s        | 1        | 1.43%   |
| Unknown (2C0B) RAM Module 8GB DIMM DDR4 2400MT/s              | 1        | 1.43%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1        | 1.43%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s            | 1        | 1.43%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                         | 1        | 1.43%   |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s           | 1        | 1.43%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1        | 1.43%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s          | 1        | 1.43%   |
| Samsung RAM Module 4GB DIMM DDR3 1066MT/s                     | 1        | 1.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1        | 1.43%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s               | 1        | 1.43%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s           | 1        | 1.43%   |
| Samsung RAM M378B5673EH1-CF8 2GB DIMM DDR3 1067MT/s           | 1        | 1.43%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s           | 1        | 1.43%   |
| Patriot RAM PSD48G320081 8GB DIMM DDR4 3200MT/s               | 1        | 1.43%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s              | 1        | 1.43%   |
| Netac RAM Module 16GB DIMM DDR4 2667MT/s                      | 1        | 1.43%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1600MT/s            | 1        | 1.43%   |
| Micron RAM 8KTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s           | 1        | 1.43%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s           | 1        | 1.43%   |
| KLEVV RAM KD48GU880-32A160U 8GB DIMM DDR4 3800MT/s            | 1        | 1.43%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s             | 1        | 1.43%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s             | 1        | 1.43%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s           | 1        | 1.43%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s           | 1        | 1.43%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1600MT/s           | 1        | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 24       | 48%     |
| DDR4    | 20       | 40%     |
| Unknown | 3        | 6%      |
| SDRAM   | 1        | 2%      |
| DDR2    | 1        | 2%      |
| DDR     | 1        | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 47       | 95.92%  |
| SODIMM | 2        | 4.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 30.16%  |
| 4096  | 16       | 25.4%   |
| 16384 | 13       | 20.63%  |
| 2048  | 10       | 15.87%  |
| 32768 | 3        | 4.76%   |
| 1024  | 1        | 1.59%   |
| 256   | 1        | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 13       | 21.67%  |
| 1600  | 12       | 20%     |
| 2667  | 7        | 11.67%  |
| 3600  | 3        | 5%      |
| 3200  | 3        | 5%      |
| 3800  | 2        | 3.33%   |
| 3400  | 2        | 3.33%   |
| 3000  | 2        | 3.33%   |
| 2400  | 2        | 3.33%   |
| 2133  | 2        | 3.33%   |
| 3733  | 1        | 1.67%   |
| 3500  | 1        | 1.67%   |
| 3466  | 1        | 1.67%   |
| 2666  | 1        | 1.67%   |
| 2176  | 1        | 1.67%   |
| 1867  | 1        | 1.67%   |
| 1866  | 1        | 1.67%   |
| 1067  | 1        | 1.67%   |
| 1066  | 1        | 1.67%   |
| 533   | 1        | 1.67%   |
| 333   | 1        | 1.67%   |
| 266   | 1        | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Xerox              | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Xerox Phaser 3040 | 1        | 33.33%  |
| Brother DCP-T500W | 1        | 33.33%  |
| Brother DCP-T420W | 1        | 33.33%  |

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
| Logitech                               | 7        | 43.75%  |
| Apple                                  | 2        | 12.5%   |
| Unknown                                | 1        | 6.25%   |
| Sony                                   | 1        | 6.25%   |
| Samsung Electronics                    | 1        | 6.25%   |
| GEMBIRD                                | 1        | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 6.25%   |
| Aveo Technology                        | 1        | 6.25%   |
| A4Tech                                 | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Logitech Webcam C270                                | 2        | 12.5%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 2        | 12.5%   |
| Unknown HD camera                                   | 1        | 6.25%   |
| Sony CEVCECM                                        | 1        | 6.25%   |
| Samsung Galaxy A5 (MTP)                             | 1        | 6.25%   |
| Logitech Webcam C930e                               | 1        | 6.25%   |
| Logitech Webcam C925e                               | 1        | 6.25%   |
| Logitech Webcam C110                                | 1        | 6.25%   |
| Logitech C922 Pro Stream Webcam                     | 1        | 6.25%   |
| Logitech C505e HD Webcam                            | 1        | 6.25%   |
| GEMBIRD USB2.0 PC CAMERA                            | 1        | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) FS13FF-183-2 | 1        | 6.25%   |
| Aveo USB2.0 Camera                                  | 1        | 6.25%   |
| A4Tech USB Live camera                              | 1        | 6.25%   |

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
| 0     | 72       | 80.9%   |
| 1     | 15       | 16.85%  |
| 3     | 1        | 1.12%   |
| 2     | 1        | 1.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 8        | 42.11%  |
| Graphics card            | 8        | 42.11%  |
| Unassigned class         | 1        | 5.26%   |
| Sound                    | 1        | 5.26%   |
| Communication controller | 1        | 5.26%   |

