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

Total: 226

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | B760M DS3H DDR4             | [ef66edb387](https://linux-hardware.org/?probe=ef66edb387) | Dec 28, 2025 |
| Gigabyte   | A320M-HD2-CF                | [d2c6a6bd77](https://linux-hardware.org/?probe=d2c6a6bd77) | Dec 21, 2025 |
| ASRock     | B450 Steel Legend           | [5ae08ad5d8](https://linux-hardware.org/?probe=5ae08ad5d8) | Dec 06, 2025 |
| MSI        | MPG X570 GAMING PRO CARB... | [ecbf4fb3fc](https://linux-hardware.org/?probe=ecbf4fb3fc) | Nov 18, 2025 |
| Gigabyte   | H81M-S1                     | [d8c8a4f18b](https://linux-hardware.org/?probe=d8c8a4f18b) | Nov 06, 2025 |
| Dell       | 0HN7XN A01                  | [b78cbb506c](https://linux-hardware.org/?probe=b78cbb506c) | Nov 03, 2025 |
| ASRock     | H61M-VG3                    | [819b1bf9c1](https://linux-hardware.org/?probe=819b1bf9c1) | Oct 16, 2025 |
| Dell       | 07N90W A00                  | [5f2dd0fe56](https://linux-hardware.org/?probe=5f2dd0fe56) | Oct 15, 2025 |
| Foxconn    | G31MV/G31MV-K FAB           | [6d0a9115bc](https://linux-hardware.org/?probe=6d0a9115bc) | Oct 15, 2025 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [41b2f0a4f1](https://linux-hardware.org/?probe=41b2f0a4f1) | Oct 09, 2025 |
| Dell       | 0773VG A02                  | [28c4292b93](https://linux-hardware.org/?probe=28c4292b93) | Sep 18, 2025 |
| Dell       | 0KRC95 A00                  | [0307880310](https://linux-hardware.org/?probe=0307880310) | Sep 14, 2025 |
| Gigabyte   | B450M DS3H V2               | [5b51f1186c](https://linux-hardware.org/?probe=5b51f1186c) | Sep 11, 2025 |
| Gigabyte   | B450M DS3H V2               | [9c8f89fda5](https://linux-hardware.org/?probe=9c8f89fda5) | Sep 11, 2025 |
| MSI        | B550 GAMING GEN3            | [10eb009459](https://linux-hardware.org/?probe=10eb009459) | Sep 04, 2025 |
| ASRock     | B450M-HDV R4.0              | [645ece661c](https://linux-hardware.org/?probe=645ece661c) | Aug 19, 2025 |
| Gigabyte   | X670E AORUS PRO X           | [e65a3637c2](https://linux-hardware.org/?probe=e65a3637c2) | Aug 04, 2025 |
| ASRock     | B450M Steel Legend          | [be967feadb](https://linux-hardware.org/?probe=be967feadb) | Jun 28, 2025 |
| Gigabyte   | AB350-Gaming-CF             | [60ff5ee3c2](https://linux-hardware.org/?probe=60ff5ee3c2) | Jun 14, 2025 |
| Lenovo     | SHARKBAY SDK0E50510 WIN     | [bd4ae26f90](https://linux-hardware.org/?probe=bd4ae26f90) | Jun 07, 2025 |
| MSI        | A520M-A PRO                 | [3709a0cb69](https://linux-hardware.org/?probe=3709a0cb69) | May 31, 2025 |
| ASRock     | B450M Pro4 R2.0             | [3a9f8fff17](https://linux-hardware.org/?probe=3a9f8fff17) | May 04, 2025 |
| Dell       | 0D441T A01                  | [906db48198](https://linux-hardware.org/?probe=906db48198) | Apr 24, 2025 |
| ASUSTek    | PRIME H310M-E               | [491598da00](https://linux-hardware.org/?probe=491598da00) | Apr 23, 2025 |
| ASUSTek    | PRIME H310M-E               | [e94faac0f1](https://linux-hardware.org/?probe=e94faac0f1) | Apr 22, 2025 |
| Dell       | 042P49 A02                  | [748d6f2188](https://linux-hardware.org/?probe=748d6f2188) | Apr 19, 2025 |
| ASRock     | H510M-HVS R2.0              | [42b360015d](https://linux-hardware.org/?probe=42b360015d) | Apr 18, 2025 |
| Gigabyte   | B450M DS3H V2               | [8699e5c8bf](https://linux-hardware.org/?probe=8699e5c8bf) | Mar 29, 2025 |
| Gigabyte   | B450M DS3H V2               | [75b00e87a3](https://linux-hardware.org/?probe=75b00e87a3) | Mar 18, 2025 |
| Dell       | 0WR7PY A01                  | [0fb9d45e19](https://linux-hardware.org/?probe=0fb9d45e19) | Mar 14, 2025 |
| HP         | 339A                        | [97696fbb25](https://linux-hardware.org/?probe=97696fbb25) | Mar 13, 2025 |
| Dell       | 0WR7PY A01                  | [bc518988ab](https://linux-hardware.org/?probe=bc518988ab) | Mar 12, 2025 |
| ASUSTek    | TUF Gaming B650M-PLUS WI... | [4529bb2d21](https://linux-hardware.org/?probe=4529bb2d21) | Feb 27, 2025 |
| Dell       | 0V8WGR A02                  | [6e65bd3379](https://linux-hardware.org/?probe=6e65bd3379) | Feb 15, 2025 |
| ASRock     | H61M-VG4                    | [791ca65f8f](https://linux-hardware.org/?probe=791ca65f8f) | Feb 03, 2025 |
| Dell       | 0F6X5P A00                  | [95a1eef874](https://linux-hardware.org/?probe=95a1eef874) | Jan 25, 2025 |
| Lenovo     | MAHOBAY NOK                 | [d8587c000b](https://linux-hardware.org/?probe=d8587c000b) | Dec 14, 2024 |
| MSI        | 760GM-P23                   | [2729dc6c3e](https://linux-hardware.org/?probe=2729dc6c3e) | Nov 08, 2024 |
| MSI        | B350 PC MATE                | [768d4c8ec6](https://linux-hardware.org/?probe=768d4c8ec6) | Nov 03, 2024 |
| ASUSTek    | P8B75-M LX PLUS             | [84f8b8a516](https://linux-hardware.org/?probe=84f8b8a516) | Oct 19, 2024 |
| Pegatron   | JESSE                       | [1e3f996dc4](https://linux-hardware.org/?probe=1e3f996dc4) | Aug 30, 2024 |
| Gigabyte   | B450 GAMING X               | [587cdb384a](https://linux-hardware.org/?probe=587cdb384a) | Aug 25, 2024 |
| Dell       | 0V8WGR A02                  | [3799a88355](https://linux-hardware.org/?probe=3799a88355) | Jul 31, 2024 |
| ASRock     | A320M-HDV R4.0              | [0498a1fafd](https://linux-hardware.org/?probe=0498a1fafd) | Jul 18, 2024 |
| Dell       | 040DDP A01                  | [bf9438a172](https://linux-hardware.org/?probe=bf9438a172) | Jul 17, 2024 |
| Intel      | H81                         | [22d5bf41a9](https://linux-hardware.org/?probe=22d5bf41a9) | Jul 17, 2024 |
| ASRock     | A320M-HDV R4.0              | [e9ba7d256e](https://linux-hardware.org/?probe=e9ba7d256e) | Jul 05, 2024 |
| ASUSTek    | P8B75-M LX PLUS             | [fdb14858e0](https://linux-hardware.org/?probe=fdb14858e0) | Jun 05, 2024 |
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


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 13       | 7.65%   |
| OpenMandriva 4.3    | 11       | 6.47%   |
| Manjaro             | 9        | 5.29%   |
| ArcoLinux Rolling   | 8        | 4.71%   |
| Ubuntu 18.04        | 7        | 4.12%   |
| Ubuntu 22.04        | 6        | 3.53%   |
| Xubuntu 20.04       | 4        | 2.35%   |
| OpenMandriva 23.08  | 4        | 2.35%   |
| Linux Mint 21.2     | 4        | 2.35%   |
| Arch Rolling        | 4        | 2.35%   |
| OpenMandriva 5.0    | 3        | 1.76%   |
| OpenMandriva 23.01  | 3        | 1.76%   |
| Linux Mint 21.3     | 3        | 1.76%   |
| Linux Mint 19.3     | 3        | 1.76%   |
| Debian 11           | 3        | 1.76%   |
| Ubuntu 24.04        | 2        | 1.18%   |
| Ubuntu 18.10        | 2        | 1.18%   |
| ROSA R11.1          | 2        | 1.18%   |
| Pop!_OS 22.04       | 2        | 1.18%   |
| Pop!_OS 20.04       | 2        | 1.18%   |
| OpenMandriva 25.90  | 2        | 1.18%   |
| OpenMandriva 25.06  | 2        | 1.18%   |
| OpenMandriva 23.03  | 2        | 1.18%   |
| LMDE 6              | 2        | 1.18%   |
| Linux Mint 22.1     | 2        | 1.18%   |
| Linux Mint 20       | 2        | 1.18%   |
| Linux Mint 19.1     | 2        | 1.18%   |
| KDE neon 20.04      | 2        | 1.18%   |
| EndeavourOS Rolling | 2        | 1.18%   |
| Debian 12           | 2        | 1.18%   |
| BlackPanther 18.1   | 2        | 1.18%   |
| Arch                | 2        | 1.18%   |
| Zorin 18            | 1        | 0.59%   |
| Zorin 17            | 1        | 0.59%   |
| Zorin 16            | 1        | 0.59%   |
| Zorin 15            | 1        | 0.59%   |
| Xubuntu 21.04       | 1        | 0.59%   |
| Xubuntu 18.04       | 1        | 0.59%   |
| Ubuntu MATE 22.04   | 1        | 0.59%   |
| Ubuntu 21.10        | 1        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 31       | 19.25%  |
| OpenMandriva | 31       | 19.25%  |
| Linux Mint   | 20       | 12.42%  |
| Manjaro      | 9        | 5.59%   |
| Fedora       | 8        | 4.97%   |
| ArcoLinux    | 8        | 4.97%   |
| Xubuntu      | 6        | 3.73%   |
| Arch         | 6        | 3.73%   |
| Pop!_OS      | 5        | 3.11%   |
| KDE neon     | 5        | 3.11%   |
| Debian       | 5        | 3.11%   |
| Zorin        | 4        | 2.48%   |
| ROSA         | 4        | 2.48%   |
| LMDE         | 3        | 1.86%   |
| Lubuntu      | 2        | 1.24%   |
| EndeavourOS  | 2        | 1.24%   |
| BlackPanther | 2        | 1.24%   |
| Bazzite      | 2        | 1.24%   |
| Ubuntu MATE  | 1        | 0.62%   |
| SteamOS      | 1        | 0.62%   |
| openSUSE     | 1        | 0.62%   |
| Nobara       | 1        | 0.62%   |
| LinuxFX      | 1        | 0.62%   |
| Kubuntu      | 1        | 0.62%   |
| Endless      | 1        | 0.62%   |
| Alpine       | 1        | 0.62%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                | Desktops | Percent |
|----------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003                | 11       | 6.11%   |
| 6.14.2-desktop-3omv2590                | 4        | 2.22%   |
| 5.4.0-42-generic                       | 4        | 2.22%   |
| 6.6.2-desktop-1omv2390                 | 3        | 1.67%   |
| 6.4.8-desktop-2omv2390                 | 3        | 1.67%   |
| 6.1.1-desktop-1omv2290                 | 3        | 1.67%   |
| 5.3.0-46-generic                       | 3        | 1.67%   |
| 6.5.0-41-generic                       | 2        | 1.11%   |
| 6.4.11-desktop-1omv2390                | 2        | 1.11%   |
| 6.2.6-desktop-1omv2390                 | 2        | 1.11%   |
| 6.1.26-1-MANJARO                       | 2        | 1.11%   |
| 5.4.83-generic-2rosa-x86_64            | 2        | 1.11%   |
| 5.4.0-65-generic                       | 2        | 1.11%   |
| 5.15.60-1-MANJARO                      | 2        | 1.11%   |
| 5.15.0-67-generic                      | 2        | 1.11%   |
| 5.15.0-48-generic                      | 2        | 1.11%   |
| 5.11.0-38-generic                      | 2        | 1.11%   |
| 5.10.0-21-amd64                        | 2        | 1.11%   |
| 5.0.0-32-generic                       | 2        | 1.11%   |
| 4.18.16-desktop-1bP                    | 2        | 1.11%   |
| 6.8.5-201.fc39.x86_64                  | 1        | 0.56%   |
| 6.8.1-desktop-3omv2490                 | 1        | 0.56%   |
| 6.8.0-90-generic                       | 1        | 0.56%   |
| 6.8.0-88-generic                       | 1        | 0.56%   |
| 6.8.0-79-generic                       | 1        | 0.56%   |
| 6.8.0-58-generic                       | 1        | 0.56%   |
| 6.8.0-45-generic                       | 1        | 0.56%   |
| 6.8.0-38-generic                       | 1        | 0.56%   |
| 6.8.0-31-generic                       | 1        | 0.56%   |
| 6.7.9-arch1-1                          | 1        | 0.56%   |
| 6.6.9-arch1-1-drm-amd-issue-2991-patch | 1        | 0.56%   |
| 6.6.7-200.fsync.fc38.x86_64            | 1        | 0.56%   |
| 6.6.59-1-lts                           | 1        | 0.56%   |
| 6.6.47-generic-1rosa2021.1-x86_64      | 1        | 0.56%   |
| 6.6.4-zen1-1-zen                       | 1        | 0.56%   |
| 6.6.27-generic-3rosa2021.1-x86_64      | 1        | 0.56%   |
| 6.6.25-1-lts                           | 1        | 0.56%   |
| 6.6.23-0-lts                           | 1        | 0.56%   |
| 6.6.14-2-lts                           | 1        | 0.56%   |
| 6.5.5-arch1-1                          | 1        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 18       | 10.29%  |
| 5.15.0  | 12       | 6.86%   |
| 5.16.7  | 11       | 6.29%   |
| 4.15.0  | 8        | 4.57%   |
| 6.8.0   | 6        | 3.43%   |
| 6.5.0   | 6        | 3.43%   |
| 5.11.0  | 6        | 3.43%   |
| 5.3.0   | 5        | 2.86%   |
| 6.14.2  | 4        | 2.29%   |
| 6.6.2   | 3        | 1.71%   |
| 6.4.8   | 3        | 1.71%   |
| 6.4.11  | 3        | 1.71%   |
| 6.14.0  | 3        | 1.71%   |
| 6.1.1   | 3        | 1.71%   |
| 6.1.0   | 3        | 1.71%   |
| 5.13.0  | 3        | 1.71%   |
| 5.10.0  | 3        | 1.71%   |
| 5.0.0   | 3        | 1.71%   |
| 4.18.0  | 3        | 1.71%   |
| 6.2.6   | 2        | 1.14%   |
| 6.2.0   | 2        | 1.14%   |
| 6.1.26  | 2        | 1.14%   |
| 5.4.83  | 2        | 1.14%   |
| 5.19.0  | 2        | 1.14%   |
| 5.18.12 | 2        | 1.14%   |
| 5.15.60 | 2        | 1.14%   |
| 4.18.16 | 2        | 1.14%   |
| 6.8.5   | 1        | 0.57%   |
| 6.8.1   | 1        | 0.57%   |
| 6.7.9   | 1        | 0.57%   |
| 6.6.9   | 1        | 0.57%   |
| 6.6.7   | 1        | 0.57%   |
| 6.6.59  | 1        | 0.57%   |
| 6.6.47  | 1        | 0.57%   |
| 6.6.4   | 1        | 0.57%   |
| 6.6.27  | 1        | 0.57%   |
| 6.6.25  | 1        | 0.57%   |
| 6.6.23  | 1        | 0.57%   |
| 6.6.14  | 1        | 0.57%   |
| 6.5.5   | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 11.49%  |
| 5.15    | 16       | 9.2%    |
| 6.6     | 11       | 6.32%   |
| 5.16    | 11       | 6.32%   |
| 6.1     | 10       | 5.75%   |
| 6.14    | 9        | 5.17%   |
| 6.8     | 8        | 4.6%    |
| 6.5     | 8        | 4.6%    |
| 5.11    | 8        | 4.6%    |
| 4.15    | 8        | 4.6%    |
| 6.4     | 6        | 3.45%   |
| 6.2     | 6        | 3.45%   |
| 6.12    | 5        | 2.87%   |
| 5.3     | 5        | 2.87%   |
| 5.10    | 5        | 2.87%   |
| 4.18    | 5        | 2.87%   |
| 5.13    | 4        | 2.3%    |
| 5.12    | 4        | 2.3%    |
| 5.19    | 3        | 1.72%   |
| 5.18    | 3        | 1.72%   |
| 5.0     | 3        | 1.72%   |
| 6.3     | 2        | 1.15%   |
| 6.15    | 2        | 1.15%   |
| 6.0     | 2        | 1.15%   |
| 5.17    | 2        | 1.15%   |
| 6.7     | 1        | 0.57%   |
| 6.18    | 1        | 0.57%   |
| 6.17    | 1        | 0.57%   |
| 6.13    | 1        | 0.57%   |
| 6.11    | 1        | 0.57%   |
| 6.10    | 1        | 0.57%   |
| 5.6     | 1        | 0.57%   |
| 4.8     | 1        | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 148      | 98.01%  |
| i686   | 3        | 1.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 46       | 29.3%   |
| KDE5       | 41       | 26.11%  |
| X-Cinnamon | 17       | 10.83%  |
| XFCE       | 12       | 7.64%   |
| Unknown    | 11       | 7.01%   |
| KDE6       | 10       | 6.37%   |
| MATE       | 3        | 1.91%   |
| LXDE       | 3        | 1.91%   |
| Cinnamon   | 3        | 1.91%   |
| LXQt       | 2        | 1.27%   |
| KDE4       | 2        | 1.27%   |
| KDE        | 2        | 1.27%   |
| bspwm      | 2        | 1.27%   |
| qtile      | 1        | 0.64%   |
| ICEWM      | 1        | 0.64%   |
| i3         | 1        | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 115      | 71.43%  |
| Wayland | 39       | 24.22%  |
| Unknown | 5        | 3.11%   |
| Tty     | 2        | 1.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 70       | 45.16%  |
| SDDM    | 43       | 27.74%  |
| LightDM | 20       | 12.9%   |
| GDM3    | 9        | 5.81%   |
| GDM     | 8        | 5.16%   |
| LY-DM   | 2        | 1.29%   |
| KDM     | 2        | 1.29%   |
| TDM     | 1        | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| es_UY      | 85       | 52.8%   |
| en_US      | 35       | 21.74%  |
| es_ES      | 17       | 10.56%  |
| es_AR      | 9        | 5.59%   |
| Unknown    | 8        | 4.97%   |
| C          | 4        | 2.48%   |
| en_GB      | 2        | 1.24%   |
| es_UY.UTF8 | 1        | 0.62%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 102      | 64.97%  |
| EFI  | 55       | 35.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 109      | 68.55%  |
| Overlay | 25       | 15.72%  |
| Btrfs   | 14       | 8.81%   |
| Tmpfs   | 8        | 5.03%   |
| Xfs     | 2        | 1.26%   |
| Unknown | 1        | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 71       | 45.51%  |
| GPT     | 66       | 42.31%  |
| MBR     | 19       | 12.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 76.77%  |
| Yes       | 36       | 23.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 66.45%  |
| Yes       | 52       | 33.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 31       | 20.53%  |
| Gigabyte Technology | 30       | 19.87%  |
| ASUSTek Computer    | 22       | 14.57%  |
| MSI                 | 17       | 11.26%  |
| Dell                | 17       | 11.26%  |
| Hewlett-Packard     | 13       | 8.61%   |
| Lenovo              | 4        | 2.65%   |
| Intel               | 4        | 2.65%   |
| Biostar             | 3        | 1.99%   |
| Foxconn             | 2        | 1.32%   |
| Supermicro          | 1        | 0.66%   |
| Pegatron            | 1        | 0.66%   |
| MACHINIST           | 1        | 0.66%   |
| Huanan              | 1        | 0.66%   |
| Gateway             | 1        | 0.66%   |
| Fujitsu             | 1        | 0.66%   |
| ECS                 | 1        | 0.66%   |
| AZW                 | 1        | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                             | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Dell OptiPlex 7010                                               | 5        | 3.31%   |
| MSI MS-7C37                                                      | 2        | 1.32%   |
| MSI MS-7817                                                      | 2        | 1.32%   |
| MSI MS-7721                                                      | 2        | 1.32%   |
| HP Compaq Pro 6300 SFF                                           | 2        | 1.32%   |
| HP Compaq 6200 Pro SFF PC                                        | 2        | 1.32%   |
| Gigabyte Z390 AORUS ELITE                                        | 2        | 1.32%   |
| Gigabyte Z370 AORUS Gaming 7                                     | 2        | 1.32%   |
| Gigabyte H61M-S1                                                 | 2        | 1.32%   |
| Gigabyte H310M A                                                 | 2        | 1.32%   |
| Gigabyte B450 GAMING X                                           | 2        | 1.32%   |
| Dell OptiPlex 980                                                | 2        | 1.32%   |
| ASUS TUF Gaming B650M-PLUS WIFI                                  | 2        | 1.32%   |
| ASUS PRIME A320M-K                                               | 2        | 1.32%   |
| ASUS All Series                                                  | 2        | 1.32%   |
| ASRock N68-S                                                     | 2        | 1.32%   |
| ASRock H310CM-HDV                                                | 2        | 1.32%   |
| ASRock FM2A58M-VG3+ R2.0                                         | 2        | 1.32%   |
| ASRock B450M Steel Legend                                        | 2        | 1.32%   |
| ASRock ALiveNF6P-VSTA                                            | 2        | 1.32%   |
| ASRock A320M-HDV R4.0                                            | 2        | 1.32%   |
| Supermicro P4DMS                                                 | 1        | 0.66%   |
| Pegatron NY603AA-ABA 300-1007                                    | 1        | 0.66%   |
| MSI Pro 3130 Microtower PC                                       | 1        | 0.66%   |
| MSI MS-7C96                                                      | 1        | 0.66%   |
| MSI MS-7C09                                                      | 1        | 0.66%   |
| MSI MS-7B93                                                      | 1        | 0.66%   |
| MSI MS-7B86                                                      | 1        | 0.66%   |
| MSI MS-7A34                                                      | 1        | 0.66%   |
| MSI MS-7816                                                      | 1        | 0.66%   |
| MSI MS-7788                                                      | 1        | 0.66%   |
| MSI MS-7786                                                      | 1        | 0.66%   |
| MSI MS-7641                                                      | 1        | 0.66%   |
| MSI MS-7592                                                      | 1        | 0.66%   |
| MACHINIST X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V309 | 1        | 0.66%   |
| Lenovo ThinkCentre M93p 10A7003UUS                               | 1        | 0.66%   |
| Lenovo ThinkCentre M92p 3238BK7                                  | 1        | 0.66%   |
| Lenovo ThinkCentre M82 3392C4S                                   | 1        | 0.66%   |
| Lenovo ThinkCentre M700 10HYA06700                               | 1        | 0.66%   |
| Intel H81                                                        | 1        | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 14       | 9.27%   |
| HP Compaq             | 9        | 5.96%   |
| ASUS PRIME            | 5        | 3.31%   |
| Lenovo ThinkCentre    | 4        | 2.65%   |
| ASUS TUF              | 4        | 2.65%   |
| ASRock A320M-HDV      | 4        | 2.65%   |
| ASRock B450M          | 3        | 1.99%   |
| MSI MS-7C37           | 2        | 1.32%   |
| MSI MS-7817           | 2        | 1.32%   |
| MSI MS-7721           | 2        | 1.32%   |
| HP EliteDesk          | 2        | 1.32%   |
| Gigabyte Z390         | 2        | 1.32%   |
| Gigabyte Z370         | 2        | 1.32%   |
| Gigabyte H61M-S1      | 2        | 1.32%   |
| Gigabyte H310M        | 2        | 1.32%   |
| Gigabyte B450M        | 2        | 1.32%   |
| Gigabyte B450         | 2        | 1.32%   |
| Dell Vostro           | 2        | 1.32%   |
| ASUS ROG              | 2        | 1.32%   |
| ASUS All              | 2        | 1.32%   |
| ASRock N68-S          | 2        | 1.32%   |
| ASRock H310CM-HDV     | 2        | 1.32%   |
| ASRock FM2A58M-VG3+   | 2        | 1.32%   |
| ASRock ALiveNF6P-VSTA | 2        | 1.32%   |
| Supermicro P4DMS      | 1        | 0.66%   |
| Pegatron NY603AA-ABA  | 1        | 0.66%   |
| MSI Pro               | 1        | 0.66%   |
| MSI MS-7C96           | 1        | 0.66%   |
| MSI MS-7C09           | 1        | 0.66%   |
| MSI MS-7B93           | 1        | 0.66%   |
| MSI MS-7B86           | 1        | 0.66%   |
| MSI MS-7A34           | 1        | 0.66%   |
| MSI MS-7816           | 1        | 0.66%   |
| MSI MS-7788           | 1        | 0.66%   |
| MSI MS-7786           | 1        | 0.66%   |
| MSI MS-7641           | 1        | 0.66%   |
| MSI MS-7592           | 1        | 0.66%   |
| MACHINIST X79         | 1        | 0.66%   |
| Intel H81             | 1        | 0.66%   |
| Intel H61M-DS2        | 1        | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 17       | 11.26%  |
| 2013 | 16       | 10.6%   |
| 2011 | 15       | 9.93%   |
| 2019 | 14       | 9.27%   |
| 2018 | 14       | 9.27%   |
| 2009 | 10       | 6.62%   |
| 2017 | 9        | 5.96%   |
| 2022 | 8        | 5.3%    |
| 2020 | 7        | 4.64%   |
| 2015 | 7        | 4.64%   |
| 2014 | 7        | 4.64%   |
| 2021 | 6        | 3.97%   |
| 2010 | 6        | 3.97%   |
| 2007 | 4        | 2.65%   |
| 2023 | 3        | 1.99%   |
| 2016 | 2        | 1.32%   |
| 2008 | 2        | 1.32%   |
| 2006 | 1        | 0.66%   |
| 2005 | 1        | 0.66%   |
| 2004 | 1        | 0.66%   |
| 2003 | 1        | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 151      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 149      | 98.68%  |
| Enabled  | 2        | 1.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 151      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 36       | 22.78%  |
| 4.01-8.0    | 34       | 21.52%  |
| 8.01-16.0   | 28       | 17.72%  |
| 3.01-4.0    | 22       | 13.92%  |
| 32.01-64.0  | 20       | 12.66%  |
| 24.01-32.0  | 6        | 3.8%    |
| 1.01-2.0    | 6        | 3.8%    |
| 64.01-256.0 | 4        | 2.53%   |
| 0.51-1.0    | 1        | 0.63%   |
| 0.01-0.5    | 1        | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 57       | 34.13%  |
| 2.01-3.0   | 41       | 24.55%  |
| 3.01-4.0   | 25       | 14.97%  |
| 4.01-8.0   | 20       | 11.98%  |
| 0.51-1.0   | 9        | 5.39%   |
| 8.01-16.0  | 8        | 4.79%   |
| 0.01-0.5   | 6        | 3.59%   |
| 16.01-24.0 | 1        | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 69       | 43.4%   |
| 2      | 51       | 32.08%  |
| 3      | 19       | 11.95%  |
| 4      | 15       | 9.43%   |
| 5      | 3        | 1.89%   |
| 7      | 1        | 0.63%   |
| 6      | 1        | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 63.23%  |
| Yes       | 57       | 36.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 149      | 98.68%  |
| No        | 2        | 1.32%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 60.26%  |
| Yes       | 62       | 39.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 78.95%  |
| Yes       | 32       | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Uruguay | 151      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Montevideo       | 127      | 80.38%  |
| Maldonado        | 10       | 6.33%   |
| Florida          | 3        | 1.9%    |
| San Jose de Mayo | 2        | 1.27%   |
| Las Piedras      | 2        | 1.27%   |
| La Paz           | 2        | 1.27%   |
| Punta del Este   | 1        | 0.63%   |
| Paysandú        | 1        | 0.63%   |
| Nuevo Paris      | 1        | 0.63%   |
| Nueva Helvecia   | 1        | 0.63%   |
| Minas            | 1        | 0.63%   |
| Melo             | 1        | 0.63%   |
| Malvin Norte     | 1        | 0.63%   |
| Durazno          | 1        | 0.63%   |
| Cordon           | 1        | 0.63%   |
| Ciudad del Plata | 1        | 0.63%   |
| Centro           | 1        | 0.63%   |
| Unknown          | 1        | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 73       | 95     | 26.35%  |
| Seagate                     | 43       | 58     | 15.52%  |
| Kingston                    | 37       | 49     | 13.36%  |
| Toshiba                     | 24       | 32     | 8.66%   |
| Samsung Electronics         | 24       | 27     | 8.66%   |
| Crucial                     | 8        | 12     | 2.89%   |
| Biostar                     | 7        | 8      | 2.53%   |
| Kingston Technology Company | 4        | 4      | 1.44%   |
| HS-SSD-C100                 | 4        | 6      | 1.44%   |
| Hitachi                     | 4        | 8      | 1.44%   |
| HGST                        | 4        | 4      | 1.44%   |
| Realtek Semiconductor       | 3        | 3      | 1.08%   |
| Patriot                     | 3        | 4      | 1.08%   |
| Netac                       | 3        | 4      | 1.08%   |
| Maxtor                      | 3        | 4      | 1.08%   |
| MAXIO Technology (Hangzhou) | 3        | 4      | 1.08%   |
| Gigabyte Technology         | 3        | 5      | 1.08%   |
| Dahua                       | 3        | 4      | 1.08%   |
| SK hynix                    | 2        | 2      | 0.72%   |
| Phison Electronics          | 2        | 2      | 0.72%   |
| Micron/Crucial Technology   | 2        | 3      | 0.72%   |
| Hewlett-Packard             | 2        | 2      | 0.72%   |
| Unknown                     | 1        | 3      | 0.36%   |
| Team                        | 1        | 1      | 0.36%   |
| Silicon Motion              | 1        | 1      | 0.36%   |
| SanDisk                     | 1        | 2      | 0.36%   |
| Phison                      | 1        | 1      | 0.36%   |
| NGFF                        | 1        | 1      | 0.36%   |
| Micron Technology           | 1        | 2      | 0.36%   |
| Lexar                       | 1        | 1      | 0.36%   |
| IBM-ESXS                    | 1        | 1      | 0.36%   |
| HS-SSD-WAVE(S)              | 1        | 1      | 0.36%   |
| ExcelStor                   | 1        | 1      | 0.36%   |
| China                       | 1        | 1      | 0.36%   |
| ASMT                        | 1        | 1      | 0.36%   |
| ADATA Technology            | 1        | 1      | 0.36%   |
| Acer                        | 1        | 1      | 0.36%   |
| A-DATA Technology           | 1        | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 9        | 2.98%   |
| WDC WD10EZEX-08WN4A0 1TB         | 8        | 2.65%   |
| Kingston SA400S37240G 240GB SSD  | 8        | 2.65%   |
| Toshiba DT01ACA100 1TB           | 7        | 2.32%   |
| Toshiba DT01ACA300 3TB           | 6        | 1.99%   |
| Seagate ST500DM002-1BD142 500GB  | 5        | 1.66%   |
| Samsung HD161HJ 160GB            | 5        | 1.66%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 4        | 1.32%   |
| Seagate ST250DM000-1BD141 250GB  | 4        | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.32%   |
| Kingston SA400S37120G 120GB SSD  | 4        | 1.32%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 3        | 0.99%   |
| WDC WD10EZEX-21WN4A0 1TB         | 3        | 0.99%   |
| WDC WD10EZEX-00BBHA0 1TB         | 3        | 0.99%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.99%   |
| Kingston SV300S37A480G 480GB SSD | 3        | 0.99%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.99%   |
| Biostar S100-120GB SSD           | 3        | 0.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 0.66%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.66%   |
| WDC WD5000AZLX-00ZR6A0 500GB     | 2        | 0.66%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 2        | 0.66%   |
| WDC WD5000AADS-56S9B1 499GB      | 2        | 0.66%   |
| WDC WD10EZEX-75ZF5A0 1TB         | 2        | 0.66%   |
| WDC WD10EZEX-60WN4A1 1TB         | 2        | 0.66%   |
| WDC WD10EFRX-68FYTN0 1TB         | 2        | 0.66%   |
| Toshiba MQ04ABF100 1TB           | 2        | 0.66%   |
| Toshiba MQ01ABD050 500GB         | 2        | 0.66%   |
| Toshiba DT01ACA200 2TB           | 2        | 0.66%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.66%   |
| Seagate ST500DM005 HD502HJ 500GB | 2        | 0.66%   |
| Seagate ST3750640NS 752GB        | 2        | 0.66%   |
| Seagate ST3250312AS 250GB        | 2        | 0.66%   |
| Seagate ST3250310CS 250GB        | 2        | 0.66%   |
| Seagate ST3160318AS 160GB        | 2        | 0.66%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.66%   |
| Samsung HD103SJ 1TB              | 2        | 0.66%   |
| Kingston Company SNV2S1000G 1TB  | 2        | 0.66%   |
| Kingston SNVS1000G 1TB           | 2        | 0.66%   |
| Kingston SFYRS1000G 1TB          | 2        | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 63       | 80     | 39.87%  |
| Seagate             | 43       | 58     | 27.22%  |
| Toshiba             | 24       | 32     | 15.19%  |
| Samsung Electronics | 16       | 17     | 10.13%  |
| Hitachi             | 4        | 8      | 2.53%   |
| HGST                | 4        | 4      | 2.53%   |
| Maxtor              | 3        | 4      | 1.9%    |
| ExcelStor           | 1        | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 31       | 36     | 38.27%  |
| WDC                 | 10       | 11     | 12.35%  |
| Crucial             | 7        | 9      | 8.64%   |
| Biostar             | 7        | 8      | 8.64%   |
| Samsung Electronics | 5        | 6      | 6.17%   |
| Netac               | 3        | 4      | 3.7%    |
| Gigabyte Technology | 3        | 5      | 3.7%    |
| Dahua               | 3        | 4      | 3.7%    |
| Patriot             | 2        | 3      | 2.47%   |
| HS-SSD-C100         | 2        | 2      | 2.47%   |
| SK hynix            | 1        | 1      | 1.23%   |
| NGFF                | 1        | 1      | 1.23%   |
| Micron Technology   | 1        | 2      | 1.23%   |
| Hewlett-Packard     | 1        | 1      | 1.23%   |
| China               | 1        | 1      | 1.23%   |
| ASMT                | 1        | 1      | 1.23%   |
| Acer                | 1        | 1      | 1.23%   |
| A-DATA Technology   | 1        | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 115      | 204    | 51.11%  |
| SSD     | 73       | 97     | 32.44%  |
| NVMe    | 32       | 50     | 14.22%  |
| Unknown | 5        | 9      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 141      | 304    | 79.66%  |
| NVMe | 32       | 50     | 18.08%  |
| SAS  | 4        | 6      | 2.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 113      | 180    | 58.85%  |
| 0.51-1.0   | 57       | 95     | 29.69%  |
| 2.01-3.0   | 8        | 10     | 4.17%   |
| 1.01-2.0   | 7        | 8      | 3.65%   |
| 3.01-4.0   | 4        | 5      | 2.08%   |
| 4.01-10.0  | 3        | 3      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 36       | 21.95%  |
| 251-500        | 35       | 21.34%  |
| 501-1000       | 23       | 14.02%  |
| 1001-2000      | 21       | 12.8%   |
| 1-20           | 14       | 8.54%   |
| 51-100         | 10       | 6.1%    |
| More than 3000 | 7        | 4.27%   |
| Unknown        | 7        | 4.27%   |
| 2001-3000      | 6        | 3.66%   |
| 21-50          | 5        | 3.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 56       | 33.73%  |
| 21-50          | 23       | 13.86%  |
| 101-250        | 20       | 12.05%  |
| 51-100         | 18       | 10.84%  |
| 501-1000       | 15       | 9.04%   |
| 251-500        | 13       | 7.83%   |
| 1001-2000      | 10       | 6.02%   |
| Unknown        | 7        | 4.22%   |
| 2001-3000      | 3        | 1.81%   |
| More than 3000 | 1        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST250DM000-1BD141 250GB  | 3        | 3      | 11.54%  |
| Seagate ST500DM002-1BD142 500GB  | 2        | 2      | 7.69%   |
| Seagate ST3750640NS 752GB        | 2        | 7      | 7.69%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 1      | 3.85%   |
| WDC WD800BD-00LRA1 80GB          | 1        | 1      | 3.85%   |
| WDC WD5000BEKT-60KA9T0 500GB     | 1        | 1      | 3.85%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 2      | 3.85%   |
| WDC WD5000AAJS-00A8B0 500GB      | 1        | 1      | 3.85%   |
| WDC WD2500AVJS-63B6A0 250GB      | 1        | 1      | 3.85%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 1      | 3.85%   |
| WDC WD10EARS-22Y5B1 1TB          | 1        | 1      | 3.85%   |
| Toshiba MQ01ABD075 752GB         | 1        | 1      | 3.85%   |
| Toshiba MK5059GSXP 500GB         | 1        | 1      | 3.85%   |
| Toshiba MK3276GSX 320GB          | 1        | 1      | 3.85%   |
| Toshiba DT01ACA100 1TB           | 1        | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB  | 1        | 1      | 3.85%   |
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 3.85%   |
| Seagate ST3250310CS 250GB        | 1        | 1      | 3.85%   |
| Seagate ST3200827AS 200GB        | 1        | 1      | 3.85%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 1      | 3.85%   |
| Kingston SA400S37480G 480GB SSD  | 1        | 2      | 3.85%   |
| HS-SSD-C100 SSD 240G             | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 11       | 17     | 44%     |
| WDC         | 8        | 9      | 32%     |
| Toshiba     | 4        | 4      | 16%     |
| Kingston    | 1        | 2      | 4%      |
| HS-SSD-C100 | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 17     | 50%     |
| WDC     | 7        | 8      | 31.82%  |
| Toshiba | 4        | 4      | 18.18%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 29     | 87.5%   |
| SSD  | 3        | 4      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 83       | 197    | 48.82%  |
| Works    | 62       | 129    | 36.47%  |
| Malfunc  | 24       | 33     | 14.12%  |
| Failed   | 1        | 1      | 0.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 89       | 44.95%  |
| AMD                          | 55       | 27.78%  |
| Kingston Technology Company  | 10       | 5.05%   |
| ASMedia Technology           | 7        | 3.54%   |
| Nvidia                       | 6        | 3.03%   |
| SanDisk                      | 4        | 2.02%   |
| Samsung Electronics          | 4        | 2.02%   |
| Silicon Motion               | 3        | 1.52%   |
| Realtek Semiconductor        | 3        | 1.52%   |
| Phison Electronics           | 3        | 1.52%   |
| Micron/Crucial Technology    | 3        | 1.52%   |
| MAXIO Technology (Hangzhou)  | 3        | 1.52%   |
| Marvell Technology Group     | 2        | 1.01%   |
| VIA Technologies             | 1        | 0.51%   |
| SK hynix                     | 1        | 0.51%   |
| Shenzhen Longsys Electronics | 1        | 0.51%   |
| INNOGRIT                     | 1        | 0.51%   |
| ADATA Technology             | 1        | 0.51%   |
| Adaptec                      | 1        | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30       | 11.41%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 4.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 4.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 4.18%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 4.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 2.66%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 2.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 2.66%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 7        | 2.66%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 2.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.28%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 2.28%   |
| Nvidia MCP61 IDE                                                                        | 5        | 1.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.9%    |
| AMD FCH IDE Controller                                                                  | 5        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.52%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.52%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.52%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 3        | 1.14%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 3        | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.14%   |
| AMD 600 Series Chipset SATA Controller                                                  | 3        | 1.14%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.76%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2        | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.76%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 2        | 0.76%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 2        | 0.76%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 0.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                                | 2        | 0.76%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 2        | 0.76%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 2        | 0.76%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 2        | 0.76%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.76%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 120      | 59.11%  |
| IDE  | 46       | 22.66%  |
| NVMe | 32       | 15.76%  |
| RAID | 4        | 1.97%   |
| SCSI | 1        | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 90       | 59.6%   |
| AMD    | 61       | 40.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz                | 6        | 3.95%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 5        | 3.29%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 4        | 2.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 4        | 2.63%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 4        | 2.63%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 4        | 2.63%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 3        | 1.97%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 3        | 1.97%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 3        | 1.97%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 2        | 1.32%   |
| Intel Core i3-3240 CPU @ 3.40GHz                | 2        | 1.32%   |
| AMD Ryzen 7 7800X3D 8-Core Processor            | 2        | 1.32%   |
| AMD Ryzen 7 5700X 8-Core Processor              | 2        | 1.32%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 2        | 1.32%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 1.32%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 1.32%   |
| AMD Ryzen 5 4600G with Radeon Graphics          | 2        | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 2        | 1.32%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 2        | 1.32%   |
| AMD Phenom II X6 1055T Processor                | 2        | 1.32%   |
| AMD Athlon II X2 250 Processor                  | 2        | 1.32%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 2        | 1.32%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 2        | 1.32%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz              | 1        | 0.66%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz              | 1        | 0.66%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1        | 0.66%   |
| Intel Xeon CPU 2.40GHz                          | 1        | 0.66%   |
| Intel Pentium CPU G870 @ 3.10GHz                | 1        | 0.66%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 1        | 0.66%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1        | 0.66%   |
| Intel Pentium 4 CPU 2.80GHz                     | 1        | 0.66%   |
| Intel Genuine CPU 2140 @ 1.60GHz                | 1        | 0.66%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 1        | 0.66%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 0.66%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 0.66%   |
| Intel Core i7-4930K CPU @ 3.40GHz               | 1        | 0.66%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 30       | 19.74%  |
| Intel Core i3     | 17       | 11.18%  |
| Intel Core i7     | 16       | 10.53%  |
| AMD Ryzen 5       | 16       | 10.53%  |
| AMD Ryzen 7       | 11       | 7.24%   |
| Intel Core 2 Duo  | 9        | 5.92%   |
| AMD Athlon II X2  | 6        | 3.95%   |
| AMD Ryzen 3       | 5        | 3.29%   |
| Intel Xeon        | 4        | 2.63%   |
| Intel Celeron     | 4        | 2.63%   |
| AMD FX            | 4        | 2.63%   |
| Intel Pentium     | 3        | 1.97%   |
| Intel Core 2 Quad | 3        | 1.97%   |
| AMD Phenom II X6  | 3        | 1.97%   |
| AMD A10           | 3        | 1.97%   |
| Other             | 2        | 1.32%   |
| AMD Athlon        | 2        | 1.32%   |
| AMD A6            | 2        | 1.32%   |
| AMD A4            | 2        | 1.32%   |
| Intel Pentium 4   | 1        | 0.66%   |
| Intel Genuine     | 1        | 0.66%   |
| Intel Core i9     | 1        | 0.66%   |
| AMD Ryzen 9       | 1        | 0.66%   |
| AMD Ryzen 3 PRO   | 1        | 0.66%   |
| AMD PRO A10       | 1        | 0.66%   |
| AMD Phenom        | 1        | 0.66%   |
| AMD Athlon 64 X2  | 1        | 0.66%   |
| AMD Athlon 64     | 1        | 0.66%   |
| AMD A8            | 1        | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 51       | 33.55%  |
| 4      | 48       | 31.58%  |
| 6      | 31       | 20.39%  |
| 8      | 15       | 9.87%   |
| 1      | 4        | 2.63%   |
| 16     | 1        | 0.66%   |
| 14     | 1        | 0.66%   |
| 12     | 1        | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 150      | 99.34%  |
| 2      | 1        | 0.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 89       | 58.55%  |
| 1      | 63       | 41.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 147      | 97.35%  |
| 32-bit         | 2        | 1.32%   |
| Unknown        | 2        | 1.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 80       | 49.08%  |
| 0x206a7    | 7        | 4.29%   |
| 0x306c3    | 6        | 3.68%   |
| 0x306a9    | 6        | 3.68%   |
| 0x906ea    | 5        | 3.07%   |
| 0x1067a    | 5        | 3.07%   |
| 0x08701021 | 4        | 2.45%   |
| 0x08108109 | 3        | 1.84%   |
| 0x06000852 | 3        | 1.84%   |
| 0xa0655    | 2        | 1.23%   |
| 0xa0653    | 2        | 1.23%   |
| 0x506e3    | 2        | 1.23%   |
| 0x206d7    | 2        | 1.23%   |
| 0x20655    | 2        | 1.23%   |
| 0x0a50000d | 2        | 1.23%   |
| 0x0800820d | 2        | 1.23%   |
| 0x08001138 | 2        | 1.23%   |
| 0x06003106 | 2        | 1.23%   |
| 0x06001119 | 2        | 1.23%   |
| 0x010000dc | 2        | 1.23%   |
| 0xf33      | 1        | 0.61%   |
| 0xf27      | 1        | 0.61%   |
| 0x906ed    | 1        | 0.61%   |
| 0x906ec    | 1        | 0.61%   |
| 0x906eb    | 1        | 0.61%   |
| 0x906e9    | 1        | 0.61%   |
| 0x906c0    | 1        | 0.61%   |
| 0x6fd      | 1        | 0.61%   |
| 0x10677    | 1        | 0.61%   |
| 0x10676    | 1        | 0.61%   |
| 0x0a601206 | 1        | 0.61%   |
| 0x0a601201 | 1        | 0.61%   |
| 0x0a50000c | 1        | 0.61%   |
| 0x08600106 | 1        | 0.61%   |
| 0x08108102 | 1        | 0.61%   |
| 0x08001137 | 1        | 0.61%   |
| 0x0600611a | 1        | 0.61%   |
| 0x03000027 | 1        | 0.61%   |
| 0x010000c8 | 1        | 0.61%   |
| 0x010000b6 | 1        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 21       | 13.82%  |
| Haswell          | 14       | 9.21%   |
| SandyBridge      | 13       | 8.55%   |
| KabyLake         | 12       | 7.89%   |
| Zen 3            | 10       | 6.58%   |
| K10              | 10       | 6.58%   |
| Zen 2            | 9        | 5.92%   |
| Penryn           | 9        | 5.92%   |
| Zen+             | 8        | 5.26%   |
| CometLake        | 7        | 4.61%   |
| Zen              | 6        | 3.95%   |
| Piledriver       | 6        | 3.95%   |
| Steamroller      | 4        | 2.63%   |
| Core             | 4        | 2.63%   |
| Unknown          | 4        | 2.63%   |
| Westmere         | 3        | 1.97%   |
| Skylake          | 3        | 1.97%   |
| NetBurst         | 2        | 1.32%   |
| K8 Hammer        | 2        | 1.32%   |
| Tremont          | 1        | 0.66%   |
| K10 Llano        | 1        | 0.66%   |
| Jaguar           | 1        | 0.66%   |
| Excavator        | 1        | 0.66%   |
| Alderlake Hybrid | 1        | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 65       | 39.39%  |
| Intel  | 50       | 30.3%   |
| AMD    | 50       | 30.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 14       | 8.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 5.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 2.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 2.91%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 2.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 2.33%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.33%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 1.74%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.74%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.74%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 1.74%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 1.74%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.74%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 3        | 1.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.74%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.16%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.16%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 1.16%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 1.16%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 2        | 1.16%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.16%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.16%   |
| AMD Raphael                                                                 | 2        | 1.16%   |
| AMD Navi 21 [Radeon RX 6900 XT]                                             | 2        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.58%   |
| Nvidia NV34 [GeForce FX 5200]                                               | 1        | 0.58%   |
| Nvidia GT216 [GeForce 210]                                                  | 1        | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.58%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.58%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.58%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 60       | 38.71%  |
| 1 x AMD        | 44       | 28.39%  |
| 1 x Intel      | 39       | 25.16%  |
| 2 x AMD        | 5        | 3.23%   |
| Intel + Nvidia | 4        | 2.58%   |
| Other          | 1        | 0.65%   |
| 2 x Intel      | 1        | 0.65%   |
| AMD + Nvidia   | 1        | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 121      | 77.07%  |
| Proprietary | 24       | 15.29%  |
| Unknown     | 12       | 7.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 78       | 48.75%  |
| 1.01-2.0   | 21       | 13.13%  |
| 0.51-1.0   | 16       | 10%     |
| 3.01-4.0   | 15       | 9.38%   |
| 0.01-0.5   | 15       | 9.38%   |
| 7.01-8.0   | 7        | 4.38%   |
| 5.01-6.0   | 3        | 1.88%   |
| 8.01-16.0  | 3        | 1.88%   |
| 2.01-3.0   | 1        | 0.63%   |
| 16.01-24.0 | 1        | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| ViewSonic               | 24       | 16.55%  |
| AOC                     | 22       | 15.17%  |
| Samsung Electronics     | 21       | 14.48%  |
| Goldstar                | 12       | 8.28%   |
| KTC                     | 11       | 7.59%   |
| Hewlett-Packard         | 7        | 4.83%   |
| Acer                    | 7        | 4.83%   |
| Unknown                 | 5        | 3.45%   |
| Lenovo                  | 5        | 3.45%   |
| JRY                     | 3        | 2.07%   |
| MYS                     | 2        | 1.38%   |
| Mi                      | 2        | 1.38%   |
| Gigabyte Technology     | 2        | 1.38%   |
| Dell                    | 2        | 1.38%   |
| BenQ                    | 2        | 1.38%   |
| Ancor Communications    | 2        | 1.38%   |
| WSD                     | 1        | 0.69%   |
| VIZTA                   | 1        | 0.69%   |
| TXD                     | 1        | 0.69%   |
| Sony                    | 1        | 0.69%   |
| RIS                     | 1        | 0.69%   |
| Philips                 | 1        | 0.69%   |
| Panasonic               | 1        | 0.69%   |
| LG Electronics          | 1        | 0.69%   |
| Lenovo Group Limited    | 1        | 0.69%   |
| KOA                     | 1        | 0.69%   |
| HKC                     | 1        | 0.69%   |
| Hitachi                 | 1        | 0.69%   |
| Envision                | 1        | 0.69%   |
| Eizo                    | 1        | 0.69%   |
| CVT                     | 1        | 0.69%   |
| Chi Mei Optoelectronics | 1        | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch       | 4        | 2.65%   |
| KTC 23L13-H-AN KTC2302 1920x1080 510x287mm 23.0-inch                | 4        | 2.65%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                      | 4        | 2.65%   |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch          | 3        | 1.99%   |
| JRY VIZTA JRY2700 1920x1080 598x336mm 27.0-inch                     | 3        | 1.99%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                    | 2        | 1.32%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch | 2        | 1.32%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch   | 2        | 1.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch   | 2        | 1.32%   |
| MYS MYS1900 MYS1900 1440x900 400x270mm 19.0-inch                    | 2        | 1.32%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch            | 2        | 1.32%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                    | 2        | 1.32%   |
| KTC W7006S KTC1772 1440x900 410x256mm 19.0-inch                     | 2        | 1.32%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch            | 2        | 1.32%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                     | 2        | 1.32%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                      | 2        | 1.32%   |
| AOC 1943W AOC1943 1366x768 410x230mm 18.5-inch                      | 2        | 1.32%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                      | 2        | 1.32%   |
| WSD ACHIEVA 22 WSD2200 1920x1080 473x296mm 22.0-inch                | 1        | 0.66%   |
| VIZTA 27HQ CURVO JRY2700 1920x1080 698x393mm 31.5-inch              | 1        | 0.66%   |
| ViewSonic XG2405 VSC0D39 1920x1080 527x296mm 23.8-inch              | 1        | 0.66%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch          | 1        | 0.66%   |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch       | 1        | 0.66%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch       | 1        | 0.66%   |
| ViewSonic VX2416-FHD VSC423D 1920x1080 527x296mm 23.8-inch          | 1        | 0.66%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch       | 1        | 0.66%   |
| ViewSonic VX2240w VSC6B20 1680x1050 495x291mm 22.6-inch             | 1        | 0.66%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch             | 1        | 0.66%   |
| ViewSonic VX1932wm-3 VSCD41F 1440x900 410x256mm 19.0-inch           | 1        | 0.66%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch       | 1        | 0.66%   |
| ViewSonic VA702 SERIES VSC231C 1280x1024 338x270mm 17.0-inch        | 1        | 0.66%   |
| ViewSonic VA521 VSCF318 1024x768 304x228mm 15.0-inch                | 1        | 0.66%   |
| ViewSonic VA2415-FHD VSC533C 1920x1080 527x296mm 23.8-inch          | 1        | 0.66%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch       | 1        | 0.66%   |
| ViewSonic VA2233-FHD VSCCD3E 1920x1080 479x260mm 21.5-inch          | 1        | 0.66%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch        | 1        | 0.66%   |
| ViewSonic VA1903 Series VSC8A31 1366x768 410x230mm 18.5-inch        | 1        | 0.66%   |
| ViewSonic LCD Monitor VX2240w 3600x1080                             | 1        | 0.66%   |
| ViewSonic LCD Monitor VA2261                                        | 1        | 0.66%   |
| Unknown LCD Monitor XXX AAA 1920x1080                               | 1        | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 55       | 39.57%  |
| 1366x768 (WXGA)    | 21       | 15.11%  |
| 1440x900 (WXGA+)   | 10       | 7.19%   |
| 1600x900 (HD+)     | 9        | 6.47%   |
| 3840x2160 (4K)     | 7        | 5.04%   |
| 1280x1024 (SXGA)   | 6        | 4.32%   |
| 2560x1440 (QHD)    | 5        | 3.6%    |
| Unknown            | 5        | 3.6%    |
| 1680x1050 (WSXGA+) | 4        | 2.88%   |
| 1360x768           | 4        | 2.88%   |
| 2960x900           | 2        | 1.44%   |
| 1280x720 (HD)      | 2        | 1.44%   |
| 3840x1080          | 1        | 0.72%   |
| 3600x1080          | 1        | 0.72%   |
| 3440x1440          | 1        | 0.72%   |
| 2944x1080          | 1        | 0.72%   |
| 2560x1080          | 1        | 0.72%   |
| 2288x1287          | 1        | 0.72%   |
| 1920x1200 (WUXGA)  | 1        | 0.72%   |
| 1280x768           | 1        | 0.72%   |
| 1024x768 (XGA)     | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 20       | 14.18%  |
| 18      | 20       | 14.18%  |
| 23      | 19       | 13.48%  |
| 19      | 14       | 9.93%   |
| Unknown | 10       | 7.09%   |
| 27      | 9        | 6.38%   |
| 24      | 8        | 5.67%   |
| 15      | 7        | 4.96%   |
| 31      | 6        | 4.26%   |
| 20      | 5        | 3.55%   |
| 17      | 5        | 3.55%   |
| 32      | 3        | 2.13%   |
| 22      | 3        | 2.13%   |
| 84      | 2        | 1.42%   |
| 48      | 2        | 1.42%   |
| 44      | 2        | 1.42%   |
| 40      | 2        | 1.42%   |
| 34      | 2        | 1.42%   |
| 142     | 1        | 0.71%   |
| 16      | 1        | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 56       | 40.88%  |
| 501-600        | 33       | 24.09%  |
| 301-350        | 10       | 7.3%    |
| Unknown        | 10       | 7.3%    |
| 351-400        | 8        | 5.84%   |
| 601-700        | 6        | 4.38%   |
| 701-800        | 5        | 3.65%   |
| 801-900        | 2        | 1.46%   |
| 1501-2000      | 2        | 1.46%   |
| 1001-1500      | 2        | 1.46%   |
| 901-1000       | 2        | 1.46%   |
| More than 2000 | 1        | 0.73%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 93       | 71.54%  |
| 16/10   | 14       | 10.77%  |
| Unknown | 10       | 7.69%   |
| 5/4     | 6        | 4.62%   |
| 3/2     | 2        | 1.54%   |
| 21/9    | 2        | 1.54%   |
| 4/3     | 1        | 0.77%   |
| 32/9    | 1        | 0.77%   |
| 1.00    | 1        | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 27.01%  |
| 151-200        | 29       | 21.17%  |
| 141-150        | 20       | 14.6%   |
| 351-500        | 10       | 7.3%    |
| Unknown        | 10       | 7.3%    |
| 301-350        | 9        | 6.57%   |
| 101-110        | 6        | 4.38%   |
| 501-1000       | 5        | 3.65%   |
| More than 1000 | 4        | 2.92%   |
| 251-300        | 3        | 2.19%   |
| 131-140        | 2        | 1.46%   |
| 121-130        | 1        | 0.73%   |
| 91-100         | 1        | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 88       | 67.69%  |
| 101-120 | 24       | 18.46%  |
| Unknown | 10       | 7.69%   |
| 1-50    | 5        | 3.85%   |
| 121-160 | 2        | 1.54%   |
| 161-240 | 1        | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 116      | 73.89%  |
| 2     | 23       | 14.65%  |
| 0     | 15       | 9.55%   |
| 3     | 2        | 1.27%   |
| 4     | 1        | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 95       | 45.02%  |
| Intel                             | 49       | 23.22%  |
| Qualcomm Atheros                  | 13       | 6.16%   |
| TP-Link                           | 11       | 5.21%   |
| Ralink Technology                 | 10       | 4.74%   |
| Nvidia                            | 6        | 2.84%   |
| Broadcom                          | 6        | 2.84%   |
| Mercucys                          | 4        | 1.9%    |
| Broadcom Limited                  | 3        | 1.42%   |
| Xiaomi                            | 2        | 0.95%   |
| Samsung Electronics               | 2        | 0.95%   |
| Ralink                            | 2        | 0.95%   |
| Huawei Technologies               | 2        | 0.95%   |
| VIA Technologies                  | 1        | 0.47%   |
| Texas Instruments                 | 1        | 0.47%   |
| Sundance Technology Inc / IC Plus | 1        | 0.47%   |
| Qualcomm                          | 1        | 0.47%   |
| MediaTek                          | 1        | 0.47%   |
| Belkin Components                 | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 79       | 33.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 14       | 5.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 8        | 3.4%    |
| Realtek RTL8125 2.5GbE Controller                                          | 6        | 2.55%   |
| Nvidia MCP61 Ethernet                                                      | 6        | 2.55%   |
| Intel Wi-Fi 6 AX200                                                        | 5        | 2.13%   |
| TP-Link 802.11ac NIC                                                       | 4        | 1.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 4        | 1.7%    |
| Ralink MT7601U Wireless Adapter                                            | 4        | 1.7%    |
| Mercucys 802.11n NIC                                                       | 4        | 1.7%    |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 1.7%    |
| Intel Ethernet Connection (2) I219-V                                       | 4        | 1.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 3        | 1.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 3        | 1.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 3        | 1.28%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 1.28%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2        | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2        | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 2        | 0.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 0.85%   |
| Realtek 802.11ac NIC                                                       | 2        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2        | 0.85%   |
| Intel Ethernet Controller I225-V                                           | 2        | 0.85%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 0.85%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.85%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 2        | 0.85%   |
| Huawei E353/E3131                                                          | 2        | 0.85%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 2        | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.43%   |
| VIA AC'97 Modem Controller                                                 | 1        | 0.43%   |
| Texas Instruments CC2531 ZigBee                                            | 1        | 0.43%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1        | 0.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.43%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                            | 1        | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 0.43%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 23       | 33.82%  |
| TP-Link               | 11       | 16.18%  |
| Ralink Technology     | 10       | 14.71%  |
| Intel                 | 9        | 13.24%  |
| Qualcomm Atheros      | 5        | 7.35%   |
| Mercucys              | 4        | 5.88%   |
| Ralink                | 2        | 2.94%   |
| Broadcom              | 2        | 2.94%   |
| MediaTek              | 1        | 1.47%   |
| Belkin Components     | 1        | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 8        | 11.76%  |
| Intel Wi-Fi 6 AX200                                                                           | 5        | 7.35%   |
| TP-Link 802.11ac NIC                                                                          | 4        | 5.88%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 5.88%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 5.88%   |
| Mercucys 802.11n NIC                                                                          | 4        | 5.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 3        | 4.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 4.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 2.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 2.94%   |
| Realtek 802.11ac NIC                                                                          | 2        | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 2        | 2.94%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 2        | 2.94%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 1        | 1.47%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.47%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.47%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                      | 1        | 1.47%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 1.47%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.47%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 1.47%   |
| Ralink RT2070 Wireless Adapter                                                                | 1        | 1.47%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.47%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                                     | 1        | 1.47%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 1.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 1.47%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 1.47%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]                          | 1        | 1.47%   |
| Intel Wireless 8260                                                                           | 1        | 1.47%   |
| Intel Wireless 3165                                                                           | 1        | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.47%   |
| Intel 700 Series Chipset CNVi WiFi                                                            | 1        | 1.47%   |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU]     | 1        | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 89       | 54.6%   |
| Intel                             | 44       | 26.99%  |
| Qualcomm Atheros                  | 8        | 4.91%   |
| Nvidia                            | 6        | 3.68%   |
| Broadcom                          | 4        | 2.45%   |
| Broadcom Limited                  | 3        | 1.84%   |
| Xiaomi                            | 2        | 1.23%   |
| Samsung Electronics               | 2        | 1.23%   |
| Huawei Technologies               | 2        | 1.23%   |
| VIA Technologies                  | 1        | 0.61%   |
| Sundance Technology Inc / IC Plus | 1        | 0.61%   |
| Qualcomm                          | 1        | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 79       | 47.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 14       | 8.48%   |
| Realtek RTL8125 2.5GbE Controller                                          | 6        | 3.64%   |
| Nvidia MCP61 Ethernet                                                      | 6        | 3.64%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.42%   |
| Intel Ethernet Connection (2) I219-V                                       | 4        | 2.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 3        | 1.82%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 1.82%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 2        | 1.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 1.21%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.21%   |
| Intel Ethernet Controller I225-V                                           | 2        | 1.21%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.21%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 1.21%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 2        | 1.21%   |
| Huawei E353/E3131                                                          | 2        | 1.21%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.61%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.61%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 1        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.61%   |
| Qualcomm Nokia X30 5G                                                      | 1        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.61%   |
| Intel Ethernet Connection I217-V                                           | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.61%   |
| Intel Ethernet Connection (14) I219-V                                      | 1        | 0.61%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.61%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 1        | 0.61%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 1        | 0.61%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 1        | 0.61%   |
| Intel 82544GC Gigabit Ethernet Controller (LOM)                            | 1        | 0.61%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 1        | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 1        | 0.61%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                            | 1        | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 149      | 69.95%  |
| WiFi     | 62       | 29.11%  |
| Modem    | 2        | 0.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 113      | 73.38%  |
| WiFi     | 41       | 26.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 120      | 79.47%  |
| 2     | 27       | 17.88%  |
| 3     | 2        | 1.32%   |
| 0     | 2        | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 82       | 52.9%   |
| Yes  | 73       | 47.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 11       | 34.38%  |
| Intel                           | 9        | 28.13%  |
| Realtek Semiconductor           | 4        | 12.5%   |
| TP-Link                         | 3        | 9.38%   |
| IMC Networks                    | 2        | 6.25%   |
| Qualcomm Atheros Communications | 1        | 3.13%   |
| Foxconn / Hon Hai               | 1        | 3.13%   |
| ASUSTek Computer                | 1        | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 34.38%  |
| Intel AX200 Bluetooth                               | 5        | 15.63%  |
| Realtek Bluetooth Radio                             | 4        | 12.5%   |
| TP-Link TP-T@- UB500 Adapter                        | 3        | 9.38%   |
| Intel Bluetooth wireless interface                  | 2        | 6.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 3.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.13%   |
| Intel Bluetooth Device                              | 1        | 3.13%   |
| IMC Networks Wireless_Device                        | 1        | 3.13%   |
| IMC Networks Bluetooth Radio                        | 1        | 3.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 3.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 87       | 35.66%  |
| Nvidia                 | 62       | 25.41%  |
| AMD                    | 61       | 25%     |
| C-Media Electronics    | 7        | 2.87%   |
| Logitech               | 4        | 1.64%   |
| Razer USA              | 3        | 1.23%   |
| VIA Technologies       | 2        | 0.82%   |
| Texas Instruments      | 2        | 0.82%   |
| Samson Technologies    | 2        | 0.82%   |
| Kingston Technology    | 2        | 0.82%   |
| Focusrite-Novation     | 2        | 0.82%   |
| Creative Labs          | 2        | 0.82%   |
| SteelSeries ApS        | 1        | 0.41%   |
| Rockwell International | 1        | 0.41%   |
| KTMicro                | 1        | 0.41%   |
| JMTek                  | 1        | 0.41%   |
| Generalplus Technology | 1        | 0.41%   |
| Elgato Systems         | 1        | 0.41%   |
| Edifier Technology     | 1        | 0.41%   |
| Creative Technology    | 1        | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19       | 6.38%   |
| AMD Ryzen HD Audio Controller                                              | 18       | 6.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14       | 4.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 3.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 3.36%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 10       | 3.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 3.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 2.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 8        | 2.68%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 2.68%   |
| AMD FCH Azalia Controller                                                  | 8        | 2.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 2.68%   |
| Nvidia High Definition Audio Controller                                    | 7        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 2.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 2.35%   |
| Nvidia MCP61 High Definition Audio                                         | 6        | 2.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.01%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 1.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 1.34%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 4        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 1.34%   |
| C-Media Electronics USB Audio Device                                       | 4        | 1.34%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4        | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.01%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.01%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.67%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 0.67%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 0.67%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 0.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 26       | 23.42%  |
| Crucial                      | 15       | 13.51%  |
| Unknown                      | 10       | 9.01%   |
| Samsung Electronics          | 10       | 9.01%   |
| Micron Technology            | 7        | 6.31%   |
| Team                         | 6        | 5.41%   |
| SK hynix                     | 4        | 3.6%    |
| Nanya Technology             | 4        | 3.6%    |
| Hikvision                    | 4        | 3.6%    |
| Unknown (89F7)               | 3        | 2.7%    |
| Corsair                      | 3        | 2.7%    |
| Patriot                      | 2        | 1.8%    |
| Elpida                       | 2        | 1.8%    |
| Avant                        | 2        | 1.8%    |
| A-DATA Technology            | 2        | 1.8%    |
| Unknown                      | 2        | 1.8%    |
| Unknown (2C0B)               | 1        | 0.9%    |
| Unknown (0x5846)             | 1        | 0.9%    |
| Smart                        | 1        | 0.9%    |
| Ramaxel Technology           | 1        | 0.9%    |
| Patriot Memory (PDP Systems) | 1        | 0.9%    |
| Netac                        | 1        | 0.9%    |
| KLEVV                        | 1        | 0.9%    |
| Infineon                     | 1        | 0.9%    |
| GeIL                         | 1        | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown (89F7) RAM Module 8GB DIMM DDR3 1600MT/s              | 3        | 2.52%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s        | 3        | 2.52%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s         | 3        | 2.52%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s            | 2        | 1.68%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1866MT/s            | 2        | 1.68%   |
| Samsung RAM Module 4GB DIMM DDR3 1066MT/s                     | 2        | 1.68%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s            | 2        | 1.68%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s           | 2        | 1.68%   |
| Kingston RAM KHX2666C16/8G 8GiB DIMM DDR4 3466MT/s            | 2        | 1.68%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5400MT/s              | 2        | 1.68%   |
| Unknown                                                       | 2        | 1.68%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                     | 1        | 0.84%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 1        | 0.84%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                          | 1        | 0.84%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 1        | 0.84%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 0.84%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 1        | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 1        | 0.84%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                       | 1        | 0.84%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                      | 1        | 0.84%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s                    | 1        | 0.84%   |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s        | 1        | 0.84%   |
| Unknown (2C0B) RAM Module 8GB DIMM DDR4 2400MT/s              | 1        | 0.84%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1        | 0.84%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s           | 1        | 0.84%   |
| Team RAM Elite-1333 8GB DIMM DDR3 1333MT/s                    | 1        | 0.84%   |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s           | 1        | 0.84%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.84%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1        | 0.84%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s          | 1        | 0.84%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s          | 1        | 0.84%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM 1334MT/s              | 1        | 0.84%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1        | 0.84%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1        | 0.84%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s               | 1        | 0.84%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s           | 1        | 0.84%   |
| Samsung RAM M378B5673EH1-CF8 2GB DIMM DDR3 1067MT/s           | 1        | 0.84%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s           | 1        | 0.84%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s        | 1        | 0.84%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s           | 1        | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 38       | 44.71%  |
| DDR4    | 34       | 40%     |
| Unknown | 4        | 4.71%   |
| SDRAM   | 3        | 3.53%   |
| DDR5    | 3        | 3.53%   |
| DDR     | 2        | 2.35%   |
| DDR2    | 1        | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 79       | 94.05%  |
| SODIMM | 4        | 4.76%   |
| RIMM   | 1        | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 35       | 33.02%  |
| 4096  | 26       | 24.53%  |
| 16384 | 21       | 19.81%  |
| 2048  | 17       | 16.04%  |
| 32768 | 5        | 4.72%   |
| 1024  | 1        | 0.94%   |
| 256   | 1        | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 21       | 20.79%  |
| 1333  | 18       | 17.82%  |
| 3200  | 9        | 8.91%   |
| 2667  | 8        | 7.92%   |
| 2400  | 6        | 5.94%   |
| 3600  | 4        | 3.96%   |
| 2133  | 4        | 3.96%   |
| 1866  | 3        | 2.97%   |
| 5400  | 2        | 1.98%   |
| 3800  | 2        | 1.98%   |
| 3733  | 2        | 1.98%   |
| 3466  | 2        | 1.98%   |
| 3000  | 2        | 1.98%   |
| 2666  | 2        | 1.98%   |
| 1066  | 2        | 1.98%   |
| 50410 | 1        | 0.99%   |
| 6000  | 1        | 0.99%   |
| 3500  | 1        | 0.99%   |
| 3400  | 1        | 0.99%   |
| 3001  | 1        | 0.99%   |
| 2473  | 1        | 0.99%   |
| 1867  | 1        | 0.99%   |
| 1800  | 1        | 0.99%   |
| 1334  | 1        | 0.99%   |
| 1067  | 1        | 0.99%   |
| 667   | 1        | 0.99%   |
| 533   | 1        | 0.99%   |
| 333   | 1        | 0.99%   |
| 266   | 1        | 0.99%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 33.33%  |
| Xerox              | 1        | 16.67%  |
| Seiko Epson        | 1        | 16.67%  |
| Hewlett-Packard    | 1        | 16.67%  |
| Canon              | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Xerox Phaser 3320        | 1        | 14.29%  |
| Seiko Epson L3210 Series | 1        | 14.29%  |
| HP HP Laser 107w         | 1        | 14.29%  |
| Canon PIXMA MP250        | 1        | 14.29%  |
| Brother DCP-T500W        | 1        | 14.29%  |
| Brother DCP-T420W        | 1        | 14.29%  |
| Brother DCP-J152W        | 1        | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 2        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 10       | 40%     |
| Microdia                               | 2        | 8%      |
| Apple                                  | 2        | 8%      |
| Unknown                                | 1        | 4%      |
| Sony                                   | 1        | 4%      |
| Sonix Technology                       | 1        | 4%      |
| Samsung Electronics                    | 1        | 4%      |
| Microsoft                              | 1        | 4%      |
| MacroSilicon                           | 1        | 4%      |
| GEMBIRD                                | 1        | 4%      |
| Chicony Electronics                    | 1        | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 1        | 4%      |
| Aveo Technology                        | 1        | 4%      |
| A4Tech                                 | 1        | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 12%     |
| Microdia USB 2.0 Camera                           | 2        | 8%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 2        | 8%      |
| Unknown HD camera                                 | 1        | 4%      |
| Sony CEVCECM                                      | 1        | 4%      |
| Sonix GENERAL WEBCAM                              | 1        | 4%      |
| Samsung Galaxy series, misc. (MTP mode)           | 1        | 4%      |
| Microsoft LifeCam HD-3000                         | 1        | 4%      |
| MacroSilicon USB Video                            | 1        | 4%      |
| Logitech Webcam C930e                             | 1        | 4%      |
| Logitech Webcam C170                              | 1        | 4%      |
| Logitech Webcam C110                              | 1        | 4%      |
| Logitech StreamCam                                | 1        | 4%      |
| Logitech Logitech Webcam C925e                    | 1        | 4%      |
| Logitech C922 Pro Stream Webcam                   | 1        | 4%      |
| Logitech C505e HD Webcam                          | 1        | 4%      |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 4%      |
| Chicony CNF8050 Webcam                            | 1        | 4%      |
| Cheng Uei Precision Industry (Foxlink) FS13FF-183 | 1        | 4%      |
| Aveo USB2.0 Camera                                | 1        | 4%      |
| A4Tech PK-635G                                    | 1        | 4%      |

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
| 0     | 128      | 82.58%  |
| 1     | 23       | 14.84%  |
| 2     | 3        | 1.94%   |
| 3     | 1        | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 53.33%  |
| Net/wireless             | 9        | 30%     |
| Unassigned class         | 2        | 6.67%   |
| Sound                    | 2        | 6.67%   |
| Communication controller | 1        | 3.33%   |

