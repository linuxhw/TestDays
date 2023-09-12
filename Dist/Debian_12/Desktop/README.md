Debian 12 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 12.

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

Total: 596

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z790 UD                     | [3f67617c93](https://linux-hardware.org/?probe=3f67617c93) | Sep 07, 2023 |
| ASRock        | Z97 Killer                  | [a1537a06ee](https://linux-hardware.org/?probe=a1537a06ee) | Sep 07, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [602bfb550f](https://linux-hardware.org/?probe=602bfb550f) | Sep 06, 2023 |
| ASRock        | Z97M OC Formula             | [1f2c20e8cf](https://linux-hardware.org/?probe=1f2c20e8cf) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [19dc657d04](https://linux-hardware.org/?probe=19dc657d04) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [f20b630cf8](https://linux-hardware.org/?probe=f20b630cf8) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [2b9d42ccc9](https://linux-hardware.org/?probe=2b9d42ccc9) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [8415f054e5](https://linux-hardware.org/?probe=8415f054e5) | Sep 05, 2023 |
| Techvision    | TVI7309X B0                 | [846d8027c3](https://linux-hardware.org/?probe=846d8027c3) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [85e1b123db](https://linux-hardware.org/?probe=85e1b123db) | Sep 04, 2023 |
| MSI           | Z370-A PRO                  | [b670e69634](https://linux-hardware.org/?probe=b670e69634) | Sep 04, 2023 |
| MSI           | PRO X670-P WIFI             | [326596a962](https://linux-hardware.org/?probe=326596a962) | Sep 04, 2023 |
| Dell          | 0CU409                      | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [2292824064](https://linux-hardware.org/?probe=2292824064) | Sep 04, 2023 |
| Gigabyte      | B85M-D3H                    | [9d4d9e6ffa](https://linux-hardware.org/?probe=9d4d9e6ffa) | Sep 03, 2023 |
| HP            | 1825                        | [38d038d2ad](https://linux-hardware.org/?probe=38d038d2ad) | Sep 03, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [c3dc3fd84b](https://linux-hardware.org/?probe=c3dc3fd84b) | Sep 02, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [3ea725d275](https://linux-hardware.org/?probe=3ea725d275) | Sep 02, 2023 |
| ASRock        | B650M PG Riptide            | [0f1a250c7f](https://linux-hardware.org/?probe=0f1a250c7f) | Sep 02, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [0075af1992](https://linux-hardware.org/?probe=0075af1992) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | [ec5d9509f6](https://linux-hardware.org/?probe=ec5d9509f6) | Sep 01, 2023 |
| ASUSTek       | P8Q77-M                     | [0192700365](https://linux-hardware.org/?probe=0192700365) | Sep 01, 2023 |
| Dell          | 0GM819                      | [8144006f85](https://linux-hardware.org/?probe=8144006f85) | Aug 31, 2023 |
| Dell          | 0GM819                      | [f7c99aa51b](https://linux-hardware.org/?probe=f7c99aa51b) | Aug 31, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [1cea30e36a](https://linux-hardware.org/?probe=1cea30e36a) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [20b35a5d4f](https://linux-hardware.org/?probe=20b35a5d4f) | Aug 30, 2023 |
| Lenovo        | 102F SDK0Q40081 WIN 3305... | [b6478eb429](https://linux-hardware.org/?probe=b6478eb429) | Aug 29, 2023 |
| HP            | 82A2                        | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| BESSTAR Te... | TH50                        | [816347743d](https://linux-hardware.org/?probe=816347743d) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Gigabyte      | H410M S2H V3                | [c772f3df30](https://linux-hardware.org/?probe=c772f3df30) | Aug 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eef69bf730](https://linux-hardware.org/?probe=eef69bf730) | Aug 28, 2023 |
| langchao      | IPM41-D3                    | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| Essentiel ... | MS-7848                     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [3067310cf8](https://linux-hardware.org/?probe=3067310cf8) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0cc7a0f138](https://linux-hardware.org/?probe=0cc7a0f138) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| Unknown       | Unknown                     | [7e6d5fa7bc](https://linux-hardware.org/?probe=7e6d5fa7bc) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [241fead3e6](https://linux-hardware.org/?probe=241fead3e6) | Aug 25, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [815a77392c](https://linux-hardware.org/?probe=815a77392c) | Aug 25, 2023 |
| HP            | 18E4                        | [e209d700ef](https://linux-hardware.org/?probe=e209d700ef) | Aug 25, 2023 |
| Unknown       | Unknown                     | [0e86c5864d](https://linux-hardware.org/?probe=0e86c5864d) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| Intel         | DN2820FYK H24582-201        | [bb1402894c](https://linux-hardware.org/?probe=bb1402894c) | Aug 24, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [eeff109a12](https://linux-hardware.org/?probe=eeff109a12) | Aug 24, 2023 |
| HC Technol... | HCAR357-NR                  | [3cd017db11](https://linux-hardware.org/?probe=3cd017db11) | Aug 24, 2023 |
| MSI           | MAG B560 TORPEDO            | [a3ec958f0c](https://linux-hardware.org/?probe=a3ec958f0c) | Aug 23, 2023 |
| MSI           | MAG B560 TORPEDO            | [79db65495a](https://linux-hardware.org/?probe=79db65495a) | Aug 23, 2023 |
| HP            | 8835                        | [6d48f6a632](https://linux-hardware.org/?probe=6d48f6a632) | Aug 23, 2023 |
| HP            | 8835                        | [01d495ff7c](https://linux-hardware.org/?probe=01d495ff7c) | Aug 23, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [78bfc9060d](https://linux-hardware.org/?probe=78bfc9060d) | Aug 23, 2023 |
| Supermicro    | H12SSL-i                    | [0981b40b5c](https://linux-hardware.org/?probe=0981b40b5c) | Aug 22, 2023 |
| ASUSTek       | E35M1-M                     | [5b3a30e3bc](https://linux-hardware.org/?probe=5b3a30e3bc) | Aug 22, 2023 |
| Inspur        | H110H4-EM                   | [75ce94f0f9](https://linux-hardware.org/?probe=75ce94f0f9) | Aug 21, 2023 |
| ASUSTek       | E35M1-M                     | [c3207e25fd](https://linux-hardware.org/?probe=c3207e25fd) | Aug 21, 2023 |
| Unknown       | Unknown                     | [4d4fcc02f3](https://linux-hardware.org/?probe=4d4fcc02f3) | Aug 21, 2023 |
| Dell          | 06X1TJ A00                  | [85ba56b138](https://linux-hardware.org/?probe=85ba56b138) | Aug 20, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [109c0dbb17](https://linux-hardware.org/?probe=109c0dbb17) | Aug 20, 2023 |
| MSI           | B450M BAZOOKA               | [569655b0f2](https://linux-hardware.org/?probe=569655b0f2) | Aug 20, 2023 |
| ASRockRack    | EP2C612D16C-4L              | [61802adf5b](https://linux-hardware.org/?probe=61802adf5b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | [8b6ec2d9e2](https://linux-hardware.org/?probe=8b6ec2d9e2) | Aug 19, 2023 |
| ASRockRack    | EP2C612D16C-4L              | [52d818cdbd](https://linux-hardware.org/?probe=52d818cdbd) | Aug 19, 2023 |
| MSI           | KA790GX-M                   | [050157c33b](https://linux-hardware.org/?probe=050157c33b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | [cf83ce90b0](https://linux-hardware.org/?probe=cf83ce90b0) | Aug 19, 2023 |
| Dell          | 06X1TJ A00                  | [9580f6451c](https://linux-hardware.org/?probe=9580f6451c) | Aug 19, 2023 |
| HP            | 8266                        | [22a06599a1](https://linux-hardware.org/?probe=22a06599a1) | Aug 19, 2023 |
| Dell          | 0PU052                      | [2b5816a194](https://linux-hardware.org/?probe=2b5816a194) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [c3d45a0b50](https://linux-hardware.org/?probe=c3d45a0b50) | Aug 18, 2023 |
| HP            | 3047h                       | [a6a9afac2a](https://linux-hardware.org/?probe=a6a9afac2a) | Aug 18, 2023 |
| HP            | 3047h                       | [762697d775](https://linux-hardware.org/?probe=762697d775) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5f5f5280d8](https://linux-hardware.org/?probe=5f5f5280d8) | Aug 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [097825338b](https://linux-hardware.org/?probe=097825338b) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [7911ff1df6](https://linux-hardware.org/?probe=7911ff1df6) | Aug 18, 2023 |
| ASUSTek       | CM1630                      | [c1fd29e307](https://linux-hardware.org/?probe=c1fd29e307) | Aug 18, 2023 |
| Intel         | X99H                        | [ee1fff7602](https://linux-hardware.org/?probe=ee1fff7602) | Aug 17, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [1742c682fc](https://linux-hardware.org/?probe=1742c682fc) | Aug 16, 2023 |
| Apple         | Mac-F221BEC8                | [2db998a2ca](https://linux-hardware.org/?probe=2db998a2ca) | Aug 16, 2023 |
| Lenovo        | 1036 NO DPK                 | [61eb0b10f6](https://linux-hardware.org/?probe=61eb0b10f6) | Aug 16, 2023 |
| ASUSTek       | PRIME A320M-R               | [0e1d37c108](https://linux-hardware.org/?probe=0e1d37c108) | Aug 16, 2023 |
| PCWare        | IPMH110G                    | [c07caba6a9](https://linux-hardware.org/?probe=c07caba6a9) | Aug 16, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [a247bcbeb2](https://linux-hardware.org/?probe=a247bcbeb2) | Aug 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ec0576c5aa](https://linux-hardware.org/?probe=ec0576c5aa) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c5ad691377](https://linux-hardware.org/?probe=c5ad691377) | Aug 14, 2023 |
| Lenovo        | ThinkCentre M58p 7220AR1    | [2bc1532fb7](https://linux-hardware.org/?probe=2bc1532fb7) | Aug 14, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | [448534f935](https://linux-hardware.org/?probe=448534f935) | Aug 13, 2023 |
| ASRock        | B550M PG Riptide            | [642c45af5d](https://linux-hardware.org/?probe=642c45af5d) | Aug 13, 2023 |
| ASRock        | B85M Pro4                   | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| CWWK          | CW-J6-6L                    | [8321dcc5ea](https://linux-hardware.org/?probe=8321dcc5ea) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f6d84a4dd](https://linux-hardware.org/?probe=4f6d84a4dd) | Aug 12, 2023 |
| MSI           | G33M                        | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| Dell          | 06X1TJ A00                  | [91ecb8253e](https://linux-hardware.org/?probe=91ecb8253e) | Aug 11, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a0350a164c](https://linux-hardware.org/?probe=a0350a164c) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| ASUSTek       | Pro WS 565-ACE              | [3d9112e038](https://linux-hardware.org/?probe=3d9112e038) | Aug 09, 2023 |
| Unknown       | AB07H                       | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| Gigabyte      | H81M-S2H                    | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| ASRock        | B460M Pro4                  | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| Foxconn       | 2ADA                        | [17d44b6d2c](https://linux-hardware.org/?probe=17d44b6d2c) | Aug 06, 2023 |
| ASRock        | Q1900M                      | [51f69dffd5](https://linux-hardware.org/?probe=51f69dffd5) | Aug 06, 2023 |
| Lenovo        | 1036 NO DPK                 | [d039bb9d5c](https://linux-hardware.org/?probe=d039bb9d5c) | Aug 06, 2023 |
| Gigabyte      | B85M-D3H                    | [ed642341d8](https://linux-hardware.org/?probe=ed642341d8) | Aug 06, 2023 |
| MSI           | B450M MORTAR MAX            | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| Shenzhen M... | HX90G                       | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| ASRockRack    | X470D4U                     | [3c7626751d](https://linux-hardware.org/?probe=3c7626751d) | Aug 04, 2023 |
| Acer          | Veriton M2632G V:1.0        | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Gigabyte      | B85M-D3H                    | [5157c58f81](https://linux-hardware.org/?probe=5157c58f81) | Aug 04, 2023 |
| ASUSTek       | H81M-C                      | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| Dell          | 06X1TJ A00                  | [ac23fbd687](https://linux-hardware.org/?probe=ac23fbd687) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| Lenovo        | 1036 NO DPK                 | [a3f6a98176](https://linux-hardware.org/?probe=a3f6a98176) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | [3aa878541c](https://linux-hardware.org/?probe=3aa878541c) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [909896213c](https://linux-hardware.org/?probe=909896213c) | Aug 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [fd259f2acd](https://linux-hardware.org/?probe=fd259f2acd) | Aug 02, 2023 |
| Gigabyte      | B85M-D3H                    | [4e092275e4](https://linux-hardware.org/?probe=4e092275e4) | Aug 02, 2023 |
| Dell          | 06X1TJ A00                  | [5f9df619f5](https://linux-hardware.org/?probe=5f9df619f5) | Aug 02, 2023 |
| ASUSTek       | Z170-A                      | [3367a6e149](https://linux-hardware.org/?probe=3367a6e149) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Unknown       | Unknown                     | [a15a3cfa70](https://linux-hardware.org/?probe=a15a3cfa70) | Jul 30, 2023 |
| Dell          | 0Y5DDC A00                  | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| MSI           | B250 PC MATE                | [9163341ff4](https://linux-hardware.org/?probe=9163341ff4) | Jul 30, 2023 |
| ASRock        | A620M-HDV/M.2+              | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| Dell          | 05GD68 A00                  | [47759e14b4](https://linux-hardware.org/?probe=47759e14b4) | Jul 28, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| AZW           | MINI S 10                   | [3501ec2e9a](https://linux-hardware.org/?probe=3501ec2e9a) | Jul 28, 2023 |
| ASUSTek       | PRIME B350M-A               | [d52776a0a8](https://linux-hardware.org/?probe=d52776a0a8) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| ASRock        | H470M-HVS                   | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| Intel         | X99H                        | [1e85498a86](https://linux-hardware.org/?probe=1e85498a86) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [a375e21964](https://linux-hardware.org/?probe=a375e21964) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [d0e6321772](https://linux-hardware.org/?probe=d0e6321772) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [28ea1c85d1](https://linux-hardware.org/?probe=28ea1c85d1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [3fd18c9a77](https://linux-hardware.org/?probe=3fd18c9a77) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [d974298840](https://linux-hardware.org/?probe=d974298840) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [b06f493001](https://linux-hardware.org/?probe=b06f493001) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [894bb319dc](https://linux-hardware.org/?probe=894bb319dc) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [7ec6d64d2f](https://linux-hardware.org/?probe=7ec6d64d2f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [09662b0f5d](https://linux-hardware.org/?probe=09662b0f5d) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [3c8721254c](https://linux-hardware.org/?probe=3c8721254c) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [7dfa96789f](https://linux-hardware.org/?probe=7dfa96789f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [c538742db7](https://linux-hardware.org/?probe=c538742db7) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [9da53986f9](https://linux-hardware.org/?probe=9da53986f9) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [c950f7dbc1](https://linux-hardware.org/?probe=c950f7dbc1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [dcf4ead958](https://linux-hardware.org/?probe=dcf4ead958) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [759b0f997f](https://linux-hardware.org/?probe=759b0f997f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [a1ef57fb8e](https://linux-hardware.org/?probe=a1ef57fb8e) | Jul 26, 2023 |
| ASRock        | A320M Pro4                  | [9ecdd1e4d3](https://linux-hardware.org/?probe=9ecdd1e4d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [f45c4baaa3](https://linux-hardware.org/?probe=f45c4baaa3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [7abbda5ed3](https://linux-hardware.org/?probe=7abbda5ed3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [67036356d3](https://linux-hardware.org/?probe=67036356d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [5a134aede2](https://linux-hardware.org/?probe=5a134aede2) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [28c92b6f8d](https://linux-hardware.org/?probe=28c92b6f8d) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | [808dae186a](https://linux-hardware.org/?probe=808dae186a) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | [b45586c5cf](https://linux-hardware.org/?probe=b45586c5cf) | Jul 26, 2023 |
| Lenovo        | 1036 NO DPK                 | [725aae77c4](https://linux-hardware.org/?probe=725aae77c4) | Jul 26, 2023 |
| Gigabyte      | X570 GAMING X               | [f67be57cba](https://linux-hardware.org/?probe=f67be57cba) | Jul 26, 2023 |
| Gigabyte      | Z77X-UD3H                   | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [d60f3de4c7](https://linux-hardware.org/?probe=d60f3de4c7) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Lenovo        | ThinkServer TS140           | [24b688cbfd](https://linux-hardware.org/?probe=24b688cbfd) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| MSI           | H110M PRO-VD                | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| Lenovo        | 1036 NO DPK                 | [15c9141aa3](https://linux-hardware.org/?probe=15c9141aa3) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| Lenovo        | ThinkServer TS140           | [8c41263814](https://linux-hardware.org/?probe=8c41263814) | Jul 23, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [8dbf2477d3](https://linux-hardware.org/?probe=8dbf2477d3) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4bd62a58b8](https://linux-hardware.org/?probe=4bd62a58b8) | Jul 22, 2023 |
| ASUSTek       | P5Q-PRO                     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [cb0ad6375e](https://linux-hardware.org/?probe=cb0ad6375e) | Jul 20, 2023 |
| Unknown       | Unknown                     | [ce80e4d17f](https://linux-hardware.org/?probe=ce80e4d17f) | Jul 18, 2023 |
| ASUSTek       | H81M-K                      | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| ASUSTek       | B85M-E/BR                   | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| ASRockRack    | X470D4U                     | [9bd188ee9b](https://linux-hardware.org/?probe=9bd188ee9b) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Foxconn       | 2A8C                        | [539fb9855b](https://linux-hardware.org/?probe=539fb9855b) | Jul 18, 2023 |
| ASUSTek       | H81M-C                      | [d75cfffdca](https://linux-hardware.org/?probe=d75cfffdca) | Jul 17, 2023 |
| MSI           | 2A9C                        | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| ASUSTek       | B85M-G                      | [fc5b33ac00](https://linux-hardware.org/?probe=fc5b33ac00) | Jul 17, 2023 |
| MSI           | 2A9C                        | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| Unknown       | Unknown                     | [29ed3e238d](https://linux-hardware.org/?probe=29ed3e238d) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [151797320d](https://linux-hardware.org/?probe=151797320d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e760f4570f](https://linux-hardware.org/?probe=e760f4570f) | Jul 16, 2023 |
| Google        | Guado                       | [4216aa46a6](https://linux-hardware.org/?probe=4216aa46a6) | Jul 16, 2023 |
| Google        | Guado                       | [9a3e217e78](https://linux-hardware.org/?probe=9a3e217e78) | Jul 15, 2023 |
| Gigabyte      | X79-UD3                     | [ce378ce93b](https://linux-hardware.org/?probe=ce378ce93b) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| Biostar       | FX9830M                     | [db3c95d18d](https://linux-hardware.org/?probe=db3c95d18d) | Jul 15, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| Dell          | 0NDYHG A01                  | [f3723937e1](https://linux-hardware.org/?probe=f3723937e1) | Jul 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [9404c94281](https://linux-hardware.org/?probe=9404c94281) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a63f044df1](https://linux-hardware.org/?probe=a63f044df1) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| ASUSTek       | H110M-R                     | [b52ebf4fc9](https://linux-hardware.org/?probe=b52ebf4fc9) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| HP            | 8643 SMVB                   | [1d6544e56b](https://linux-hardware.org/?probe=1d6544e56b) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| Gigabyte      | X570 AORUS PRO              | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| ASRock        | 4Core1600-GLAN              | [3e733151f2](https://linux-hardware.org/?probe=3e733151f2) | Jul 11, 2023 |
| Foxconn       | G33M03                      | [487435e6e7](https://linux-hardware.org/?probe=487435e6e7) | Jul 11, 2023 |
| ASUSTek       | Z170-A                      | [cbcf43d3dd](https://linux-hardware.org/?probe=cbcf43d3dd) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| ASUSTek       | H81M-K                      | [6593286092](https://linux-hardware.org/?probe=6593286092) | Jul 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [ce682089cb](https://linux-hardware.org/?probe=ce682089cb) | Jul 10, 2023 |
| HP            | 2B38                        | [94e5178425](https://linux-hardware.org/?probe=94e5178425) | Jul 10, 2023 |
| Gigabyte      | B650 GAMING X AX            | [64e129ec04](https://linux-hardware.org/?probe=64e129ec04) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1e27d93bb4](https://linux-hardware.org/?probe=1e27d93bb4) | Jul 09, 2023 |
| Dell          | 0V8WGR A00                  | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| Dell          | 0CU409                      | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| ASRock        | B550 Taichi Razer Editio... | [c5578cae9e](https://linux-hardware.org/?probe=c5578cae9e) | Jul 07, 2023 |
| HP            | 2B4B                        | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| HP            | 2B4B                        | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| MSI           | B250M PRO-VDH               | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f99a1ccf8f](https://linux-hardware.org/?probe=f99a1ccf8f) | Jul 06, 2023 |
| HP            | 8860 A                      | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [7e3ad6f5a7](https://linux-hardware.org/?probe=7e3ad6f5a7) | Jul 05, 2023 |
| Gigabyte      | MZBSWAP-00                  | [4e61ff196e](https://linux-hardware.org/?probe=4e61ff196e) | Jul 05, 2023 |
| ASRock        | 990FX Killer                | [696e4c24d1](https://linux-hardware.org/?probe=696e4c24d1) | Jul 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [3707ca3e1d](https://linux-hardware.org/?probe=3707ca3e1d) | Jul 05, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [8c224974f3](https://linux-hardware.org/?probe=8c224974f3) | Jul 04, 2023 |
| MSI           | Z170A GAMING M3             | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| iEi           | SAT3 V1.03                  | [fa5767b5f5](https://linux-hardware.org/?probe=fa5767b5f5) | Jul 03, 2023 |
| HP            | 0AECh D                     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| Unknown       | AB07H                       | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| Shenzhen M... | F6BFC                       | [61bc4ee589](https://linux-hardware.org/?probe=61bc4ee589) | Jul 02, 2023 |
| Lenovo        | 1036 NO DPK                 | [12a82e799d](https://linux-hardware.org/?probe=12a82e799d) | Jul 01, 2023 |
| MSI           | Z490-A PRO                  | [eb4b65c767](https://linux-hardware.org/?probe=eb4b65c767) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [91e094e5c8](https://linux-hardware.org/?probe=91e094e5c8) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [f1eddf9437](https://linux-hardware.org/?probe=f1eddf9437) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| Dell          | 0PU052                      | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a996f391dc](https://linux-hardware.org/?probe=a996f391dc) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [d6823d5ec7](https://linux-hardware.org/?probe=d6823d5ec7) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| OEM           | Unknown                     | [0448bbee67](https://linux-hardware.org/?probe=0448bbee67) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| Lenovo        | 1048 SDK0K17763 WIN 1801... | [d903758323](https://linux-hardware.org/?probe=d903758323) | Jun 27, 2023 |
| Dell          | 0PU052                      | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Gigabyte      | H310MD2P-CF                 | [1ad319cfc7](https://linux-hardware.org/?probe=1ad319cfc7) | Jun 26, 2023 |
| BESSTAR Te... | B550                        | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| JINGSHA       | Unknown                     | [2ae6ac9599](https://linux-hardware.org/?probe=2ae6ac9599) | Jun 25, 2023 |
| Biostar       | X370GTN                     | [80b2b1d180](https://linux-hardware.org/?probe=80b2b1d180) | Jun 25, 2023 |
| Intel         | H55                         | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Gigabyte      | EP45C-DS3R                  | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| ASUSTek       | K30BF_M32BF                 | [46a7aaf9f1](https://linux-hardware.org/?probe=46a7aaf9f1) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [51b5eb0fa2](https://linux-hardware.org/?probe=51b5eb0fa2) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | [655b20a34b](https://linux-hardware.org/?probe=655b20a34b) | Jun 23, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| Acer          | Aspire X1700                | [aac17ef2f2](https://linux-hardware.org/?probe=aac17ef2f2) | Jun 22, 2023 |
| AMI           | Intel                       | [1a4a632d56](https://linux-hardware.org/?probe=1a4a632d56) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | X670E PG Lightning          | [b8e19a16f9](https://linux-hardware.org/?probe=b8e19a16f9) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| MSI           | H110M PRO-D                 | [b652abc634](https://linux-hardware.org/?probe=b652abc634) | Jun 21, 2023 |
| HP            | 1588h                       | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| ASRock        | B760 Pro RS/D4              | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| Dell          | 0RW203                      | [6872d8e6c5](https://linux-hardware.org/?probe=6872d8e6c5) | Jun 20, 2023 |
| ASUSTek       | P8H67-M                     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| MSI           | B550-A PRO                  | [b0f066ab7e](https://linux-hardware.org/?probe=b0f066ab7e) | Jun 18, 2023 |
| Intel         | H81                         | [5cda43eb30](https://linux-hardware.org/?probe=5cda43eb30) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| HP            | 2B38                        | [b84e03e083](https://linux-hardware.org/?probe=b84e03e083) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| ASRock        | B760 Pro RS/D4              | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| ASUSTek       | PRIME B450M-A               | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| HP            | 2820h                       | [77b54a0343](https://linux-hardware.org/?probe=77b54a0343) | Jun 14, 2023 |
| HP            | 2820h                       | [40e65d7a30](https://linux-hardware.org/?probe=40e65d7a30) | Jun 14, 2023 |
| Intel         | DG41TY AAE47335-203         | [4f1d844d48](https://linux-hardware.org/?probe=4f1d844d48) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3117d89b20](https://linux-hardware.org/?probe=3117d89b20) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3feaf0bd19](https://linux-hardware.org/?probe=3feaf0bd19) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [5fc5be3367](https://linux-hardware.org/?probe=5fc5be3367) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [aba284328c](https://linux-hardware.org/?probe=aba284328c) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [b899120507](https://linux-hardware.org/?probe=b899120507) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [051cebacd1](https://linux-hardware.org/?probe=051cebacd1) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [221a4431e2](https://linux-hardware.org/?probe=221a4431e2) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [85abf9e475](https://linux-hardware.org/?probe=85abf9e475) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [40df819ebb](https://linux-hardware.org/?probe=40df819ebb) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9ed186ba56](https://linux-hardware.org/?probe=9ed186ba56) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [2a4d82175c](https://linux-hardware.org/?probe=2a4d82175c) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [1df32db310](https://linux-hardware.org/?probe=1df32db310) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9949220d98](https://linux-hardware.org/?probe=9949220d98) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [d801927769](https://linux-hardware.org/?probe=d801927769) | Jun 13, 2023 |
| Shuttle       | FM10 V10                    | [f1396e2cce](https://linux-hardware.org/?probe=f1396e2cce) | Jun 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [d85ad203ff](https://linux-hardware.org/?probe=d85ad203ff) | Jun 13, 2023 |
| Gigabyte      | H61M-DS2                    | [06c6c417c9](https://linux-hardware.org/?probe=06c6c417c9) | Jun 13, 2023 |
| ECS           | G31T-M9                     | [ba2a738c96](https://linux-hardware.org/?probe=ba2a738c96) | Jun 13, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [86ab821b84](https://linux-hardware.org/?probe=86ab821b84) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [8943f697bc](https://linux-hardware.org/?probe=8943f697bc) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-K               | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| ASRock        | H310CM-HDV                  | [a810b267ef](https://linux-hardware.org/?probe=a810b267ef) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| ASUSTek       | A68HM-PLUS                  | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | [756a317dd6](https://linux-hardware.org/?probe=756a317dd6) | Jun 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0aeb6a400a](https://linux-hardware.org/?probe=0aeb6a400a) | Jun 11, 2023 |
| ASUSTek       | P7H55D-M PRO                | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| ECS           | G31T-M9                     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| ASUSTek       | M4A78T-E                    | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| Gigabyte      | GA-M56S-S3                  | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| Gigabyte      | M68MT-S2                    | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| ECS           | G31T-M9                     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Gigabyte      | GA-M56S-S3                  | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| HC Technol... | HCAR357-NR                  | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [853bd25ca5](https://linux-hardware.org/?probe=853bd25ca5) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [3a9fb692f1](https://linux-hardware.org/?probe=3a9fb692f1) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [9b549fe65a](https://linux-hardware.org/?probe=9b549fe65a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [db685837d0](https://linux-hardware.org/?probe=db685837d0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [968b38e0b9](https://linux-hardware.org/?probe=968b38e0b9) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [c9a04d8da0](https://linux-hardware.org/?probe=c9a04d8da0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [238931757a](https://linux-hardware.org/?probe=238931757a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [e190e991a6](https://linux-hardware.org/?probe=e190e991a6) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [0816e77499](https://linux-hardware.org/?probe=0816e77499) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [ff143ac918](https://linux-hardware.org/?probe=ff143ac918) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| Gigabyte      | H61M-DS2                    | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| ASRock        | H110M-HDV R3.0              | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| ECS           | G31T-M9                     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| Gigabyte      | M68MT-S2                    | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [80c2e03e4e](https://linux-hardware.org/?probe=80c2e03e4e) | May 29, 2023 |
| ECS           | G31T-M9                     | [8f4cd5b132](https://linux-hardware.org/?probe=8f4cd5b132) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [ffe8469edc](https://linux-hardware.org/?probe=ffe8469edc) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [e9f274ad89](https://linux-hardware.org/?probe=e9f274ad89) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [62a5559050](https://linux-hardware.org/?probe=62a5559050) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a9c147d701](https://linux-hardware.org/?probe=a9c147d701) | May 29, 2023 |
| ASRock        | J4105-ITX                   | [570bc894da](https://linux-hardware.org/?probe=570bc894da) | May 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9e0fc265de](https://linux-hardware.org/?probe=9e0fc265de) | May 29, 2023 |
| Gigabyte      | Z690 AERO G                 | [5d4d7c7ef4](https://linux-hardware.org/?probe=5d4d7c7ef4) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [bcdfc5a2bf](https://linux-hardware.org/?probe=bcdfc5a2bf) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [68cb8bdf49](https://linux-hardware.org/?probe=68cb8bdf49) | May 27, 2023 |
| Biostar       | A10N-8800E                  | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [4862d28e3f](https://linux-hardware.org/?probe=4862d28e3f) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [92836191e9](https://linux-hardware.org/?probe=92836191e9) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [0d449702e3](https://linux-hardware.org/?probe=0d449702e3) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [a5fbe0c1ba](https://linux-hardware.org/?probe=a5fbe0c1ba) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [f9fd99a8b7](https://linux-hardware.org/?probe=f9fd99a8b7) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [6c87853f8c](https://linux-hardware.org/?probe=6c87853f8c) | May 26, 2023 |
| ASUSTek       | H81M-C                      | [138348e6eb](https://linux-hardware.org/?probe=138348e6eb) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [388eed2f8e](https://linux-hardware.org/?probe=388eed2f8e) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [1bc02afebc](https://linux-hardware.org/?probe=1bc02afebc) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [485617123a](https://linux-hardware.org/?probe=485617123a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [d1933e40f4](https://linux-hardware.org/?probe=d1933e40f4) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [db84f366d0](https://linux-hardware.org/?probe=db84f366d0) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [4d7f19ec5b](https://linux-hardware.org/?probe=4d7f19ec5b) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [adb7acad13](https://linux-hardware.org/?probe=adb7acad13) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [897503110a](https://linux-hardware.org/?probe=897503110a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [7ddbfedd32](https://linux-hardware.org/?probe=7ddbfedd32) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [96202d100a](https://linux-hardware.org/?probe=96202d100a) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [faa830a26c](https://linux-hardware.org/?probe=faa830a26c) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [03d0e0d8d7](https://linux-hardware.org/?probe=03d0e0d8d7) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [f76e433d68](https://linux-hardware.org/?probe=f76e433d68) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [610a5f2bb3](https://linux-hardware.org/?probe=610a5f2bb3) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [f10a5bd0f9](https://linux-hardware.org/?probe=f10a5bd0f9) | May 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | [7a40f97a17](https://linux-hardware.org/?probe=7a40f97a17) | May 26, 2023 |
| MSI           | H110M PRO-VD                | [387793dfb2](https://linux-hardware.org/?probe=387793dfb2) | May 25, 2023 |
| ASUSTek       | P9X79                       | [142c9c4384](https://linux-hardware.org/?probe=142c9c4384) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [7b4b86c1ea](https://linux-hardware.org/?probe=7b4b86c1ea) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [15c2f741bf](https://linux-hardware.org/?probe=15c2f741bf) | May 25, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [ac28804681](https://linux-hardware.org/?probe=ac28804681) | May 25, 2023 |
| ASUSTek       | E35M1-M                     | [c62d813dd9](https://linux-hardware.org/?probe=c62d813dd9) | May 24, 2023 |
| Gigabyte      | GA-M56S-S3                  | [3898315bde](https://linux-hardware.org/?probe=3898315bde) | May 24, 2023 |
| Gigabyte      | M61PME-S2                   | [e147bb9d5e](https://linux-hardware.org/?probe=e147bb9d5e) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [17f5577d63](https://linux-hardware.org/?probe=17f5577d63) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [d06b734926](https://linux-hardware.org/?probe=d06b734926) | May 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [3ee24557f7](https://linux-hardware.org/?probe=3ee24557f7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| ASRock        | H270 Performance            | [b3f7fdc329](https://linux-hardware.org/?probe=b3f7fdc329) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [91aa0c376a](https://linux-hardware.org/?probe=91aa0c376a) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [98f94bccb6](https://linux-hardware.org/?probe=98f94bccb6) | May 22, 2023 |
| Gigabyte      | B250M-D2V-CF                | [71fc64d684](https://linux-hardware.org/?probe=71fc64d684) | May 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d4460792c6](https://linux-hardware.org/?probe=d4460792c6) | May 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| ASRock        | H470M-HVS                   | [919ed7f9e1](https://linux-hardware.org/?probe=919ed7f9e1) | May 20, 2023 |
| HP            | 1905                        | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [0f034f50a0](https://linux-hardware.org/?probe=0f034f50a0) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [cdb86f0326](https://linux-hardware.org/?probe=cdb86f0326) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | [8c80042f1e](https://linux-hardware.org/?probe=8c80042f1e) | May 19, 2023 |
| ASRock        | X370 Taichi                 | [94bf603662](https://linux-hardware.org/?probe=94bf603662) | May 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5e003a073d](https://linux-hardware.org/?probe=5e003a073d) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| ASUSTek       | P5B-VM SE                   | [dce4e8be7c](https://linux-hardware.org/?probe=dce4e8be7c) | May 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [b9410e67b1](https://linux-hardware.org/?probe=b9410e67b1) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [9505c6130c](https://linux-hardware.org/?probe=9505c6130c) | May 16, 2023 |
| Gigabyte      | B760 AORUS ELITE AX         | [b1ab3ebdd4](https://linux-hardware.org/?probe=b1ab3ebdd4) | May 15, 2023 |
| ASRock        | H470M-HVS                   | [36cb64f82a](https://linux-hardware.org/?probe=36cb64f82a) | May 15, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [878a94a7c7](https://linux-hardware.org/?probe=878a94a7c7) | May 13, 2023 |
| Gigabyte      | Z690 AERO G                 | [a199ff9b72](https://linux-hardware.org/?probe=a199ff9b72) | May 13, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a2a47b4c35](https://linux-hardware.org/?probe=a2a47b4c35) | May 12, 2023 |
| Gigabyte      | H61M-DS2                    | [de18c72638](https://linux-hardware.org/?probe=de18c72638) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [92a39a22a2](https://linux-hardware.org/?probe=92a39a22a2) | May 12, 2023 |
| ASRock        | H470M-HVS                   | [72aed73d34](https://linux-hardware.org/?probe=72aed73d34) | May 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [0625860f59](https://linux-hardware.org/?probe=0625860f59) | May 10, 2023 |
| ECS           | G31T-M9                     | [25fd5432f0](https://linux-hardware.org/?probe=25fd5432f0) | May 10, 2023 |
| MSI           | H81M-P33                    | [c3902a3649](https://linux-hardware.org/?probe=c3902a3649) | May 10, 2023 |
| ASRock        | H470M-HVS                   | [e61f99e96e](https://linux-hardware.org/?probe=e61f99e96e) | May 10, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [401db07b93](https://linux-hardware.org/?probe=401db07b93) | May 08, 2023 |
| ASRock        | B760 Pro RS/D4              | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| HP            | 1589                        | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [be7c8943ce](https://linux-hardware.org/?probe=be7c8943ce) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| MSI           | B450 TOMAHAWK               | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| Unknown       | Unknown                     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASRock        | A320M-HDV R3.0              | [d395c6168d](https://linux-hardware.org/?probe=d395c6168d) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| HP            | 8309                        | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| ASUSTek       | Z170-A                      | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| ASRock        | 960GC-GS FX                 | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c5f2fa1c5a](https://linux-hardware.org/?probe=c5f2fa1c5a) | Apr 25, 2023 |
| MSI           | X370 GAMING PLUS            | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [9c3e15de68](https://linux-hardware.org/?probe=9c3e15de68) | Apr 22, 2023 |
| ASUSTek       | P5N-D                       | [c1af2b9a2c](https://linux-hardware.org/?probe=c1af2b9a2c) | Apr 22, 2023 |
| HP            | ProLiant ML150 G6           | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e1da556a0b](https://linux-hardware.org/?probe=e1da556a0b) | Apr 19, 2023 |
| MSI           | H110M PRO-VD                | [d04a1b7f36](https://linux-hardware.org/?probe=d04a1b7f36) | Apr 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| Biostar       | A10N-8800E                  | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Acer          | WG43M                       | [a3a49836f9](https://linux-hardware.org/?probe=a3a49836f9) | Apr 15, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| Gigabyte      | H61M-DS2                    | [e0b6eda111](https://linux-hardware.org/?probe=e0b6eda111) | Apr 11, 2023 |
| ASUSTek       | P7H55                       | [8ee190d352](https://linux-hardware.org/?probe=8ee190d352) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| ASUSTek       | P7H55                       | [89966b216e](https://linux-hardware.org/?probe=89966b216e) | Apr 07, 2023 |
| QTQD          | Unknown                     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| MSI           | Z68A-GD65                   | [a8939164e7](https://linux-hardware.org/?probe=a8939164e7) | Apr 06, 2023 |
| Gigabyte      | B550 UD AC                  | [a639dfd228](https://linux-hardware.org/?probe=a639dfd228) | Apr 06, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [55ea8a957b](https://linux-hardware.org/?probe=55ea8a957b) | Apr 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| ASUSTek       | VM42                        | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5f9965b18e](https://linux-hardware.org/?probe=5f9965b18e) | Apr 05, 2023 |
| Gigabyte      | Z68A-D3-B3                  | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| Gigabyte      | H61M-DS2                    | [5a83d4ef1e](https://linux-hardware.org/?probe=5a83d4ef1e) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [1b35a0e9f7](https://linux-hardware.org/?probe=1b35a0e9f7) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [734efd13d3](https://linux-hardware.org/?probe=734efd13d3) | Apr 03, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Gigabyte      | H61M-DS2                    | [35e4f876ca](https://linux-hardware.org/?probe=35e4f876ca) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [fca09d31a2](https://linux-hardware.org/?probe=fca09d31a2) | Mar 31, 2023 |
| ASRock        | B760M Pro RS/D4             | [6a63402e9c](https://linux-hardware.org/?probe=6a63402e9c) | Mar 31, 2023 |
| ASUSTek       | P8H67-M                     | [3806b33cae](https://linux-hardware.org/?probe=3806b33cae) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f310910b0e](https://linux-hardware.org/?probe=f310910b0e) | Mar 30, 2023 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | [08af010307](https://linux-hardware.org/?probe=08af010307) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [82118905ba](https://linux-hardware.org/?probe=82118905ba) | Mar 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6cc34607d1](https://linux-hardware.org/?probe=6cc34607d1) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4fe0ddab4b](https://linux-hardware.org/?probe=4fe0ddab4b) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5969fea8f0](https://linux-hardware.org/?probe=5969fea8f0) | Mar 28, 2023 |
| Gigabyte      | H97M-HD3                    | [1b531d5ada](https://linux-hardware.org/?probe=1b531d5ada) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| HP            | 895D                        | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| ASUSTek       | PRIME X470-PRO              | [a05e768cca](https://linux-hardware.org/?probe=a05e768cca) | Mar 25, 2023 |
| Gigabyte      | H61M-DS2                    | [cea1787057](https://linux-hardware.org/?probe=cea1787057) | Mar 24, 2023 |
| ASUSTek       | PRIME Z690-P                | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ECS           | G31T-M9                     | [e314bf5403](https://linux-hardware.org/?probe=e314bf5403) | Mar 23, 2023 |
| Techvision    | TVI7309X B0                 | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [6b25c70b9f](https://linux-hardware.org/?probe=6b25c70b9f) | Mar 21, 2023 |
| Intel         | STK2M3W64CC H89289-506      | [5386cc221b](https://linux-hardware.org/?probe=5386cc221b) | Mar 19, 2023 |
| Techvision    | TVI7309X B0                 | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| Gigabyte      | M52L-S3P                    | [89660a09c2](https://linux-hardware.org/?probe=89660a09c2) | Mar 17, 2023 |
| ASUSTek       | M4A88T-M                    | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b843a727ce](https://linux-hardware.org/?probe=b843a727ce) | Mar 15, 2023 |
| Unknown       | Unknown                     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| MSI           | H110M PRO-VH PLUS           | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| HP            | 8076 MVB,A                  | [20150077f5](https://linux-hardware.org/?probe=20150077f5) | Mar 11, 2023 |
| Gigabyte      | B360M D2V                   | [dd67a26e98](https://linux-hardware.org/?probe=dd67a26e98) | Mar 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cfacdb386a](https://linux-hardware.org/?probe=cfacdb386a) | Mar 09, 2023 |
| ASUSTek       | PRIME X570-P                | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| HP            | 82B4                        | [47d445cfa6](https://linux-hardware.org/?probe=47d445cfa6) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ae03ade800](https://linux-hardware.org/?probe=ae03ade800) | Mar 04, 2023 |
| ASUSTek       | PRIME H510M-K               | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Intel         | D945GCPE AAD97209-201       | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| ASRock        | X370 Professional Gaming    | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| ASUSTek       | PRIME X399-A                | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Dell          | 0T065F A01                  | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [d442995b00](https://linux-hardware.org/?probe=d442995b00) | Feb 19, 2023 |
| Lenovo        | 3164 NOK                    | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B450M H                     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| HP            | 3648h                       | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| Unknown       | Unknown                     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| Unknown       | Unknown                     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [517a5a9e81](https://linux-hardware.org/?probe=517a5a9e81) | Feb 13, 2023 |
| Gigabyte      | B450M H                     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [4b19274da1](https://linux-hardware.org/?probe=4b19274da1) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| HP            | 2B36                        | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.1.0-4-amd64             | 135      | 28.72%  |
| 6.1.0-9-amd64             | 88       | 18.72%  |
| 6.1.0-10-amd64            | 77       | 16.38%  |
| 6.1.0-11-amd64            | 46       | 9.79%   |
| 6.1.0-7-amd64             | 29       | 6.17%   |
| 6.1.0-6-amd64             | 13       | 2.77%   |
| 6.1.0-3-amd64             | 12       | 2.55%   |
| 6.1.0-5-amd64             | 10       | 2.13%   |
| 6.1.0-8-amd64             | 6        | 1.28%   |
| 6.2.16-3-pve              | 5        | 1.06%   |
| 6.0.0-6-amd64             | 3        | 0.64%   |
| 6.4.0-0.deb12.2-amd64     | 2        | 0.43%   |
| 6.2.16-8-pve              | 2        | 0.43%   |
| 6.2.16-6-pve              | 2        | 0.43%   |
| 6.2.16-10-pve             | 2        | 0.43%   |
| 6.0.0-2-amd64             | 2        | 0.43%   |
| 6.4.6-1-liquorix-amd64    | 1        | 0.21%   |
| 6.4.11-1-liquorix-amd64   | 1        | 0.21%   |
| 6.4.10-3-liquorix-amd64   | 1        | 0.21%   |
| 6.4.0-01280-g7116cae43716 | 1        | 0.21%   |
| 6.3.9-i7                  | 1        | 0.21%   |
| 6.3.5-x64v3-xanmod1       | 1        | 0.21%   |
| 6.3.3-tkg-cfs             | 1        | 0.21%   |
| 6.3.0-1-amd64             | 1        | 0.21%   |
| 6.3.0-0-amd64             | 1        | 0.21%   |
| 6.2.8-x64v3-xanmod1       | 1        | 0.21%   |
| 6.2.16-5-pve              | 1        | 0.21%   |
| 6.2.16-4-pve              | 1        | 0.21%   |
| 6.2.16-2-pve              | 1        | 0.21%   |
| 6.2.16-12-pve             | 1        | 0.21%   |
| 6.2.11-3-liquorix-amd64   | 1        | 0.21%   |
| 6.1.9-x64v3-xanmod1       | 1        | 0.21%   |
| 6.1.38-i3                 | 1        | 0.21%   |
| 6.1.27-mab64              | 1        | 0.21%   |
| 6.1.13-x64v1-xanmod1      | 1        | 0.21%   |
| 6.1.0-9-rt-amd64          | 1        | 0.21%   |
| 6.1.0-7-rt-amd64          | 1        | 0.21%   |
| 6.1.0-6-rt-amd64          | 1        | 0.21%   |
| 6.1.0-6-powerpc64         | 1        | 0.21%   |
| 6.1.0-10-686-pae          | 1        | 0.21%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.0    | 414      | 89.42%  |
| 6.2.16   | 15       | 3.24%   |
| 6.0.0    | 7        | 1.51%   |
| 5.10.0   | 4        | 0.86%   |
| 6.4.0    | 3        | 0.65%   |
| 6.3.0    | 2        | 0.43%   |
| 6.4.6    | 1        | 0.22%   |
| 6.4.11   | 1        | 0.22%   |
| 6.4.10   | 1        | 0.22%   |
| 6.3.9    | 1        | 0.22%   |
| 6.3.5    | 1        | 0.22%   |
| 6.3.3    | 1        | 0.22%   |
| 6.2.8    | 1        | 0.22%   |
| 6.2.11   | 1        | 0.22%   |
| 6.1.9    | 1        | 0.22%   |
| 6.1.38   | 1        | 0.22%   |
| 6.1.27   | 1        | 0.22%   |
| 6.1.13   | 1        | 0.22%   |
| 5.15.90  | 1        | 0.22%   |
| 5.15.108 | 1        | 0.22%   |
| 5.15.0   | 1        | 0.22%   |
| 5.10.142 | 1        | 0.22%   |
| 4.19.0   | 1        | 0.22%   |
| 4.1.42   | 1        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 418      | 90.28%  |
| 6.2     | 17       | 3.67%   |
| 6.0     | 7        | 1.51%   |
| 6.4     | 6        | 1.3%    |
| 6.3     | 5        | 1.08%   |
| 5.10    | 5        | 1.08%   |
| 5.15    | 3        | 0.65%   |
| 4.19    | 1        | 0.22%   |
| 4.1     | 1        | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 456      | 99.13%  |
| i686        | 2        | 0.43%   |
| ppc64       | 1        | 0.22%   |
| loongarch64 | 1        | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 187      | 40.56%  |
| GNOME           | 102      | 22.13%  |
| KDE5            | 77       | 16.7%   |
| XFCE            | 29       | 6.29%   |
| MATE            | 21       | 4.56%   |
| X-Cinnamon      | 20       | 4.34%   |
| LXDE            | 7        | 1.52%   |
| LXQt            | 6        | 1.3%    |
| i3              | 5        | 1.08%   |
| Cinnamon        | 2        | 0.43%   |
| openbox         | 1        | 0.22%   |
| GNOME Flashback | 1        | 0.22%   |
| GNOME Classic   | 1        | 0.22%   |
| dwm             | 1        | 0.22%   |
| Cutefish        | 1        | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 173      | 37.61%  |
| Unknown | 165      | 35.87%  |
| Wayland | 95       | 20.65%  |
| Tty     | 27       | 5.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 271      | 58.79%  |
| LightDM | 69       | 14.97%  |
| GDM3    | 62       | 13.45%  |
| SDDM    | 53       | 11.5%   |
| XDM     | 2        | 0.43%   |
| SLiM    | 2        | 0.43%   |
| Ly      | 1        | 0.22%   |
| LXDM    | 1        | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 148      | 32.17%  |
| en_US   | 127      | 27.61%  |
| de_DE   | 42       | 9.13%   |
| en_GB   | 27       | 5.87%   |
| Unknown | 19       | 4.13%   |
| fr_FR   | 12       | 2.61%   |
| es_ES   | 12       | 2.61%   |
| pt_BR   | 11       | 2.39%   |
| en_CA   | 10       | 2.17%   |
| it_IT   | 5        | 1.09%   |
| es_AR   | 5        | 1.09%   |
| en_IN   | 5        | 1.09%   |
| zh_CN   | 4        | 0.87%   |
| pl_PL   | 4        | 0.87%   |
| en_ZA   | 4        | 0.87%   |
| ja_JP   | 2        | 0.43%   |
| fi_FI   | 2        | 0.43%   |
| es_VE   | 2        | 0.43%   |
| es_PE   | 2        | 0.43%   |
| en_AU   | 2        | 0.43%   |
| zh_TW   | 1        | 0.22%   |
| ko_KR   | 1        | 0.22%   |
| id_ID   | 1        | 0.22%   |
| es_EC   | 1        | 0.22%   |
| es_CU   | 1        | 0.22%   |
| es_CL   | 1        | 0.22%   |
| en_NZ   | 1        | 0.22%   |
| en_IL   | 1        | 0.22%   |
| en_IE   | 1        | 0.22%   |
| en_HK   | 1        | 0.22%   |
| en_DK   | 1        | 0.22%   |
| el_GR   | 1        | 0.22%   |
| de_CH   | 1        | 0.22%   |
| de_AT   | 1        | 0.22%   |
| ca_ES   | 1        | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 287      | 62.39%  |
| EFI  | 173      | 37.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 264      | 57.27%  |
| Overlay | 155      | 33.62%  |
| Btrfs   | 22       | 4.77%   |
| Xfs     | 7        | 1.52%   |
| Tmpfs   | 7        | 1.52%   |
| Zfs     | 5        | 1.08%   |
| Ext3    | 1        | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 212      | 46.09%  |
| MBR     | 167      | 36.3%   |
| Unknown | 81       | 17.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 391      | 85%     |
| Yes       | 69       | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 241      | 52.39%  |
| Yes       | 219      | 47.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 142      | 30.87%  |
| Gigabyte Technology                  | 80       | 17.39%  |
| ASRock                               | 51       | 11.09%  |
| MSI                                  | 45       | 9.78%   |
| Lenovo                               | 28       | 6.09%   |
| Hewlett-Packard                      | 24       | 5.22%   |
| Dell                                 | 16       | 3.48%   |
| Intel                                | 11       | 2.39%   |
| Unknown                              | 9        | 1.96%   |
| Fujitsu                              | 5        | 1.09%   |
| Foxconn                              | 5        | 1.09%   |
| ECS                                  | 4        | 0.87%   |
| Acer                                 | 4        | 0.87%   |
| Supermicro                           | 3        | 0.65%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.65%   |
| Biostar                              | 3        | 0.65%   |
| ASRockRack                           | 3        | 0.65%   |
| Techvision                           | 2        | 0.43%   |
| HC Technology.                       | 2        | 0.43%   |
| BESSTAR Tech                         | 2        | 0.43%   |
| Shuttle                              | 1        | 0.22%   |
| QTQD                                 | 1        | 0.22%   |
| PCWare                               | 1        | 0.22%   |
| OEM                                  | 1        | 0.22%   |
| Loongson                             | 1        | 0.22%   |
| langchao                             | 1        | 0.22%   |
| JINGSHA                              | 1        | 0.22%   |
| JGINYUE                              | 1        | 0.22%   |
| Inspur                               | 1        | 0.22%   |
| iEi                                  | 1        | 0.22%   |
| Huanan                               | 1        | 0.22%   |
| Google                               | 1        | 0.22%   |
| Fujitsu Siemens                      | 1        | 0.22%   |
| Essentiel B                          | 1        | 0.22%   |
| CWWK                                 | 1        | 0.22%   |
| AZW                                  | 1        | 0.22%   |
| Apple                                | 1        | 0.22%   |
| AMI                                  | 1        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 28       | 6.09%   |
| ASRock H470M-HVS                     | 20       | 4.35%   |
| Lenovo ThinkCentre M55p 8808D8U      | 12       | 2.61%   |
| Unknown                              | 12       | 2.61%   |
| ASUS PRIME B450M-K                   | 10       | 2.17%   |
| Gigabyte H81M-S2V                    | 8        | 1.74%   |
| Gigabyte A320M-S2H V2                | 7        | 1.52%   |
| MSI MS-7996                          | 6        | 1.3%    |
| ASUS S20 K29                         | 6        | 1.3%    |
| ASUS ProArt X670E-CREATOR WIFI       | 5        | 1.09%   |
| ECS G31T-M9                          | 4        | 0.87%   |
| Lenovo ThinkStation P520 30BFS44D00  | 3        | 0.65%   |
| Gigabyte M56S-S3                     | 3        | 0.65%   |
| Gigabyte B450 AORUS ELITE            | 3        | 0.65%   |
| ASUS ROG STRIX X570-E GAMING         | 3        | 0.65%   |
| ASUS PRIME B450M-A                   | 3        | 0.65%   |
| Techvision TVI7309X                  | 2        | 0.43%   |
| Supermicro X8ST3                     | 2        | 0.43%   |
| MSI MS-7C37                          | 2        | 0.43%   |
| MSI MS-7C02                          | 2        | 0.43%   |
| Intel X99                            | 2        | 0.43%   |
| HP Compaq 6005 Pro MT PC             | 2        | 0.43%   |
| HC Technology. HCAR357-NR            | 2        | 0.43%   |
| Gigabyte X570 GAMING X               | 2        | 0.43%   |
| Gigabyte M68MT-S2                    | 2        | 0.43%   |
| Gigabyte H61M-DS2 REV 1.2            | 2        | 0.43%   |
| Gigabyte GA-MA78GM-S2H               | 2        | 0.43%   |
| Gigabyte B550M DS3H                  | 2        | 0.43%   |
| Gigabyte B450M H                     | 2        | 0.43%   |
| Gigabyte B250M-DS3H                  | 2        | 0.43%   |
| Dell OptiPlex 755                    | 2        | 0.43%   |
| ASUS Z170-A                          | 2        | 0.43%   |
| ASUS TUF Gaming B550M-PLUS           | 2        | 0.43%   |
| ASUS TUF Gaming B550-PLUS            | 2        | 0.43%   |
| ASUS STRIX H270F GAMING              | 2        | 0.43%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 2        | 0.43%   |
| ASUS Pro WS X570-ACE                 | 2        | 0.43%   |
| ASUS PRIME X470-PRO                  | 2        | 0.43%   |
| ASUS PRIME B550M-A                   | 2        | 0.43%   |
| ASUS P8H67-M                         | 2        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 37       | 8.04%   |
| ASUS All                  | 28       | 6.09%   |
| Lenovo ThinkCentre        | 20       | 4.35%   |
| ASRock H470M-HVS          | 20       | 4.35%   |
| ASUS ROG                  | 14       | 3.04%   |
| Unknown                   | 12       | 2.61%   |
| Dell OptiPlex             | 9        | 1.96%   |
| ASUS TUF                  | 9        | 1.96%   |
| Gigabyte H81M-S2V         | 8        | 1.74%   |
| Gigabyte A320M-S2H        | 7        | 1.52%   |
| MSI MS-7996               | 6        | 1.3%    |
| ASUS S20                  | 6        | 1.3%    |
| Lenovo ThinkStation       | 5        | 1.09%   |
| Gigabyte B450M            | 5        | 1.09%   |
| Gigabyte B450             | 5        | 1.09%   |
| ASUS ProArt               | 5        | 1.09%   |
| HP ProDesk                | 4        | 0.87%   |
| HP Compaq                 | 4        | 0.87%   |
| Gigabyte X570             | 4        | 0.87%   |
| Gigabyte B550M            | 4        | 0.87%   |
| ECS G31T-M9               | 4        | 0.87%   |
| HP EliteDesk              | 3        | 0.65%   |
| Gigabyte M56S-S3          | 3        | 0.65%   |
| Fujitsu ESPRIMO           | 3        | 0.65%   |
| ASUS Pro                  | 3        | 0.65%   |
| ASUS P5G41T-M             | 3        | 0.65%   |
| Acer Aspire               | 3        | 0.65%   |
| Techvision TVI7309X       | 2        | 0.43%   |
| Supermicro X8ST3          | 2        | 0.43%   |
| MSI MS-7C37               | 2        | 0.43%   |
| MSI MS-7C02               | 2        | 0.43%   |
| Intel X99                 | 2        | 0.43%   |
| HC Technology. HCAR357-NR | 2        | 0.43%   |
| Gigabyte M68MT-S2         | 2        | 0.43%   |
| Gigabyte H61M-DS2         | 2        | 0.43%   |
| Gigabyte GA-MA78GM-S2H    | 2        | 0.43%   |
| Gigabyte B250M-DS3H       | 2        | 0.43%   |
| Fujitsu FUTRO             | 2        | 0.43%   |
| Dell Vostro               | 2        | 0.43%   |
| Dell Precision            | 2        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 49       | 10.65%  |
| 2021    | 46       | 10%     |
| 2022    | 43       | 9.35%   |
| 2020    | 38       | 8.26%   |
| 2014    | 31       | 6.74%   |
| 2012    | 28       | 6.09%   |
| 2019    | 27       | 5.87%   |
| 2009    | 24       | 5.22%   |
| 2007    | 23       | 5%      |
| 2016    | 22       | 4.78%   |
| 2013    | 22       | 4.78%   |
| 2023    | 19       | 4.13%   |
| 2008    | 19       | 4.13%   |
| 2010    | 17       | 3.7%    |
| 2017    | 16       | 3.48%   |
| 2015    | 16       | 3.48%   |
| 2011    | 16       | 3.48%   |
| Unknown | 3        | 0.65%   |
| 2002    | 1        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 460      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 444      | 96.52%  |
| Enabled  | 16       | 3.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 459      | 99.78%  |
| Yes  | 1        | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 101      | 21.86%  |
| 4.01-8.0        | 75       | 16.23%  |
| 16.01-24.0      | 73       | 15.8%   |
| 3.01-4.0        | 65       | 14.07%  |
| 8.01-16.0       | 64       | 13.85%  |
| 64.01-256.0     | 39       | 8.44%   |
| 24.01-32.0      | 17       | 3.68%   |
| 1.01-2.0        | 16       | 3.46%   |
| 2.01-3.0        | 5        | 1.08%   |
| More than 256.0 | 3        | 0.65%   |
| 0.51-1.0        | 3        | 0.65%   |
| Unknown         | 1        | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 121      | 25.8%   |
| 4.01-8.0    | 99       | 21.11%  |
| 1.01-2.0    | 99       | 21.11%  |
| 2.01-3.0    | 69       | 14.71%  |
| 3.01-4.0    | 38       | 8.1%    |
| 8.01-16.0   | 21       | 4.48%   |
| 0.01-0.5    | 9        | 1.92%   |
| 16.01-24.0  | 6        | 1.28%   |
| 24.01-32.0  | 3        | 0.64%   |
| 32.01-64.0  | 2        | 0.43%   |
| 64.01-256.0 | 1        | 0.21%   |
| Unknown     | 1        | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 233      | 50.43%  |
| 2      | 102      | 22.08%  |
| 3      | 58       | 12.55%  |
| 4      | 32       | 6.93%   |
| 6      | 11       | 2.38%   |
| 5      | 10       | 2.16%   |
| 0      | 4        | 0.87%   |
| 8      | 3        | 0.65%   |
| 7      | 3        | 0.65%   |
| 10     | 2        | 0.43%   |
| 32     | 1        | 0.22%   |
| 29     | 1        | 0.22%   |
| 27     | 1        | 0.22%   |
| 19     | 1        | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 329      | 71.37%  |
| Yes       | 132      | 28.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 456      | 99.13%  |
| No        | 4        | 0.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 298      | 64.78%  |
| Yes       | 162      | 35.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 324      | 69.83%  |
| Yes       | 140      | 30.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 155      | 33.62%  |
| USA          | 72       | 15.62%  |
| Germany      | 55       | 11.93%  |
| UK           | 16       | 3.47%   |
| Spain        | 15       | 3.25%   |
| Brazil       | 13       | 2.82%   |
| France       | 12       | 2.6%    |
| Canada       | 12       | 2.6%    |
| Italy        | 10       | 2.17%   |
| Poland       | 8        | 1.74%   |
| India        | 6        | 1.3%    |
| Finland      | 6        | 1.3%    |
| Argentina    | 6        | 1.3%    |
| Slovakia     | 5        | 1.08%   |
| Switzerland  | 4        | 0.87%   |
| China        | 4        | 0.87%   |
| Australia    | 4        | 0.87%   |
| South Africa | 3        | 0.65%   |
| Portugal     | 3        | 0.65%   |
| Mexico       | 3        | 0.65%   |
| Japan        | 3        | 0.65%   |
| Austria      | 3        | 0.65%   |
| Venezuela    | 2        | 0.43%   |
| Sweden       | 2        | 0.43%   |
| Singapore    | 2        | 0.43%   |
| Peru         | 2        | 0.43%   |
| Norway       | 2        | 0.43%   |
| Netherlands  | 2        | 0.43%   |
| Morocco      | 2        | 0.43%   |
| Israel       | 2        | 0.43%   |
| Ireland      | 2        | 0.43%   |
| Indonesia    | 2        | 0.43%   |
| Hong Kong    | 2        | 0.43%   |
| Denmark      | 2        | 0.43%   |
| Vietnam      | 1        | 0.22%   |
| Uruguay      | 1        | 0.22%   |
| Turkey       | 1        | 0.22%   |
| South Korea  | 1        | 0.22%   |
| Romania      | 1        | 0.22%   |
| New Zealand  | 1        | 0.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 134      | 28.94%  |
| Bangor            | 17       | 3.67%   |
| Moscow            | 7        | 1.51%   |
| Manchester        | 5        | 1.08%   |
| Frankfurt am Main | 5        | 1.08%   |
| Vienna            | 4        | 0.86%   |
| Toronto           | 4        | 0.86%   |
| St Petersburg     | 4        | 0.86%   |
| Rozhanovce        | 4        | 0.86%   |
| Madrid            | 4        | 0.86%   |
| Gladbeck          | 4        | 0.86%   |
| Berlin            | 4        | 0.86%   |
| Paris             | 3        | 0.65%   |
| Hamburg           | 3        | 0.65%   |
| Bonn              | 3        | 0.65%   |
| Tsukuba           | 2        | 0.43%   |
| Tel Aviv          | 2        | 0.43%   |
| Stockholm         | 2        | 0.43%   |
| Singapore         | 2        | 0.43%   |
| Richmond          | 2        | 0.43%   |
| Ottawa            | 2        | 0.43%   |
| Milan             | 2        | 0.43%   |
| Lüneburg         | 2        | 0.43%   |
| Lima              | 2        | 0.43%   |
| Hounslow          | 2        | 0.43%   |
| Hofheim am Taunus | 2        | 0.43%   |
| Helsinki          | 2        | 0.43%   |
| Gilbert           | 2        | 0.43%   |
| Espoo             | 2        | 0.43%   |
| Dublin            | 2        | 0.43%   |
| Delhi             | 2        | 0.43%   |
| Cologne           | 2        | 0.43%   |
| Casablanca        | 2        | 0.43%   |
| Bedford           | 2        | 0.43%   |
| Austin            | 2        | 0.43%   |
| Zurich            | 1        | 0.22%   |
| Zhangzhou         | 1        | 0.22%   |
| Zaraysk           | 1        | 0.22%   |
| Wroclaw           | 1        | 0.22%   |
| Wittenbach        | 1        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 156      | 272    | 19.97%  |
| Samsung Electronics         | 110      | 164    | 14.08%  |
| Seagate                     | 104      | 162    | 13.32%  |
| Crucial                     | 62       | 75     | 7.94%   |
| Toshiba                     | 49       | 63     | 6.27%   |
| Kingston                    | 46       | 51     | 5.89%   |
| SanDisk                     | 36       | 42     | 4.61%   |
| Hitachi                     | 25       | 27     | 3.2%    |
| Netac                       | 24       | 25     | 3.07%   |
| Intel                       | 12       | 14     | 1.54%   |
| Transcend                   | 9        | 11     | 1.15%   |
| HGST                        | 9        | 43     | 1.15%   |
| Unknown                     | 8        | 11     | 1.02%   |
| SPCC                        | 8        | 9      | 1.02%   |
| Kingston Technology Company | 8        | 12     | 1.02%   |
| China                       | 7        | 7      | 0.9%    |
| PNY                         | 5        | 6      | 0.64%   |
| Plextor                     | 5        | 5      | 0.64%   |
| Phison Electronics          | 5        | 11     | 0.64%   |
| KIOXIA-EXCERIA              | 5        | 5      | 0.64%   |
| Hewlett-Packard             | 5        | 7      | 0.64%   |
| A-DATA Technology           | 5        | 5      | 0.64%   |
| Silicon Motion              | 4        | 4      | 0.51%   |
| Phison                      | 4        | 4      | 0.51%   |
| Micron/Crucial Technology   | 4        | 5      | 0.51%   |
| Micron Technology           | 4        | 4      | 0.51%   |
| Maxtor                      | 3        | 3      | 0.38%   |
| GOODRAM                     | 3        | 4      | 0.38%   |
| ZHITAI                      | 2        | 3      | 0.26%   |
| XPG                         | 2        | 5      | 0.26%   |
| SK hynix                    | 2        | 2      | 0.26%   |
| SABRENT                     | 2        | 2      | 0.26%   |
| Patriot                     | 2        | 2      | 0.26%   |
| OCZ                         | 2        | 2      | 0.26%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.26%   |
| LITEON                      | 2        | 2      | 0.26%   |
| KIOXIA                      | 2        | 2      | 0.26%   |
| JMicron Technology          | 2        | 2      | 0.26%   |
| Intenso                     | 2        | 2      | 0.26%   |
| Corsair                     | 2        | 3      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Netac SSD 240GB                                       | 19       | 2.06%   |
| Crucial CT480BX500SSD1 480GB                          | 19       | 2.06%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 15       | 1.63%   |
| Toshiba HDWD110 1TB                                   | 14       | 1.52%   |
| Kingston SA400S37240G 240GB SSD                       | 12       | 1.3%    |
| Crucial CT240BX500SSD1 240GB                          | 12       | 1.3%    |
| Seagate ST1000DM003-1ER162 1TB                        | 9        | 0.98%   |
| Samsung SSD 980 PRO 1TB                               | 9        | 0.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 9        | 0.98%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 8        | 0.87%   |
| Samsung SSD 870 EVO 500GB                             | 8        | 0.87%   |
| Crucial CT1000MX500SSD1 1TB                           | 8        | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB                        | 7        | 0.76%   |
| Samsung SSD 850 EVO 500GB                             | 7        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 7        | 0.76%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB               | 7        | 0.76%   |
| Crucial CT500MX500SSD1 500GB                          | 7        | 0.76%   |
| Samsung SSD 980 500GB                                 | 6        | 0.65%   |
| Samsung SSD 970 EVO Plus 500GB                        | 6        | 0.65%   |
| Kingston SA400S37480G 480GB SSD                       | 6        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                       | 6        | 0.65%   |
| Toshiba DT01ACA100 1TB                                | 5        | 0.54%   |
| Toshiba DT01ACA050 500GB                              | 5        | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB                        | 5        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5        | 0.54%   |
| Seagate ST2000DM006-2DM164 2TB                        | 5        | 0.54%   |
| Samsung SSD 980 1TB                                   | 5        | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB                          | 5        | 0.54%   |
| Samsung SSD 860 EVO 500GB                             | 5        | 0.54%   |
| Samsung SSD 860 EVO 1TB                               | 5        | 0.54%   |
| Kingston SV300S37A120G 120GB SSD                      | 5        | 0.54%   |
| WDC WD40EFRX-68WT0N0 4TB                              | 4        | 0.43%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 4        | 0.43%   |
| Unknown SD/MMC/MS PRO 1GB                             | 4        | 0.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4        | 0.43%   |
| Seagate ST3250410AS 250GB                             | 4        | 0.43%   |
| Seagate ST1000DM003-1SB102 1TB                        | 4        | 0.43%   |
| Seagate Expansion Desk 2TB                            | 4        | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                            | 4        | 0.43%   |
| Samsung SSD 860 EVO 250GB                             | 4        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 134      | 234    | 40.12%  |
| Seagate             | 101      | 159    | 30.24%  |
| Toshiba             | 48       | 62     | 14.37%  |
| Hitachi             | 25       | 27     | 7.49%   |
| HGST                | 9        | 43     | 2.69%   |
| Unknown             | 4        | 4      | 1.2%    |
| Samsung Electronics | 3        | 4      | 0.9%    |
| Maxtor              | 3        | 3      | 0.9%    |
| SABRENT             | 2        | 2      | 0.6%    |
| Hewlett-Packard     | 2        | 3      | 0.6%    |
| USB                 | 1        | 1      | 0.3%    |
| External            | 1        | 1      | 0.3%    |
| Unknown             | 1        | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 57       | 72     | 20.07%  |
| Crucial             | 53       | 60     | 18.66%  |
| Kingston            | 36       | 40     | 12.68%  |
| Netac               | 23       | 24     | 8.1%    |
| WDC                 | 19       | 28     | 6.69%   |
| SanDisk             | 16       | 17     | 5.63%   |
| Intel               | 9        | 10     | 3.17%   |
| Transcend           | 7        | 9      | 2.46%   |
| SPCC                | 7        | 7      | 2.46%   |
| China               | 7        | 7      | 2.46%   |
| PNY                 | 5        | 6      | 1.76%   |
| Plextor             | 4        | 4      | 1.41%   |
| GOODRAM             | 3        | 4      | 1.06%   |
| Seagate             | 2        | 2      | 0.7%    |
| Patriot             | 2        | 2      | 0.7%    |
| OCZ                 | 2        | 2      | 0.7%    |
| Micron Technology   | 2        | 2      | 0.7%    |
| LITEON              | 2        | 2      | 0.7%    |
| JMicron Technology  | 2        | 2      | 0.7%    |
| Intenso             | 2        | 2      | 0.7%    |
| Hewlett-Packard     | 2        | 2      | 0.7%    |
| A-DATA Technology   | 2        | 2      | 0.7%    |
| TrekStor            | 1        | 1      | 0.35%   |
| TO Exter            | 1        | 1      | 0.35%   |
| Timetec             | 1        | 2      | 0.35%   |
| T-FORCE             | 1        | 2      | 0.35%   |
| SSSTC               | 1        | 1      | 0.35%   |
| Rogueware           | 1        | 1      | 0.35%   |
| OCZ-VERTEX3         | 1        | 1      | 0.35%   |
| MSI                 | 1        | 1      | 0.35%   |
| KOWIN               | 1        | 1      | 0.35%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.35%   |
| KingSpec            | 1        | 1      | 0.35%   |
| Innodisk            | 1        | 1      | 0.35%   |
| Gigabyte Technology | 1        | 1      | 0.35%   |
| Fanxiang            | 1        | 1      | 0.35%   |
| Emtec               | 1        | 1      | 0.35%   |
| Dogfish             | 1        | 1      | 0.35%   |
| Colorful            | 1        | 1      | 0.35%   |
| Apacer              | 1        | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 281      | 544    | 41.57%  |
| SSD     | 240      | 328    | 35.5%   |
| NVMe    | 149      | 235    | 22.04%  |
| Unknown | 4        | 6      | 0.59%   |
| MMC     | 2        | 3      | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 398      | 790    | 68.62%  |
| NVMe | 149      | 234    | 25.69%  |
| SAS  | 31       | 89     | 5.34%   |
| MMC  | 2        | 3      | 0.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 299      | 388    | 52%     |
| 0.51-1.0   | 140      | 191    | 24.35%  |
| 1.01-2.0   | 58       | 98     | 10.09%  |
| 3.01-4.0   | 32       | 66     | 5.57%   |
| 4.01-10.0  | 22       | 94     | 3.83%   |
| 2.01-3.0   | 19       | 25     | 3.3%    |
| 10.01-20.0 | 5        | 10     | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 152      | 32.76%  |
| 101-250        | 61       | 13.15%  |
| More than 3000 | 60       | 12.93%  |
| 501-1000       | 56       | 12.07%  |
| 251-500        | 47       | 10.13%  |
| 1001-2000      | 32       | 6.9%    |
| 2001-3000      | 23       | 4.96%   |
| 1-20           | 14       | 3.02%   |
| 21-50          | 10       | 2.16%   |
| 51-100         | 9        | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 152      | 32.48%  |
| 1-20           | 105      | 22.44%  |
| 101-250        | 41       | 8.76%   |
| 21-50          | 36       | 7.69%   |
| 501-1000       | 30       | 6.41%   |
| 1001-2000      | 29       | 6.2%    |
| 251-500        | 26       | 5.56%   |
| More than 3000 | 20       | 4.27%   |
| 51-100         | 19       | 4.06%   |
| 2001-3000      | 10       | 2.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 12       | 12     | 12.37%  |
| WDC WD3200AAJS-00L7A0 320GB      | 3        | 3      | 3.09%   |
| Seagate ST3250410AS 250GB        | 3        | 3      | 3.09%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 2      | 2.06%   |
| Seagate ST2000DX001-1CM164 2TB   | 2        | 3      | 2.06%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 2      | 2.06%   |
| Maxtor STM3160815AS 160GB        | 2        | 2      | 2.06%   |
| Hitachi HDS721050CLA362 500GB    | 2        | 3      | 2.06%   |
| Hitachi HDS721010CLA332 1TB      | 2        | 2      | 2.06%   |
| ZHITAI TiPlus5000 512GB          | 1        | 1      | 1.03%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 2      | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1      | 1.03%   |
| WDC WD80EMAZ-00WJTA0 8TB         | 1        | 11     | 1.03%   |
| WDC WD800AAJS-60WAA0 80GB        | 1        | 1      | 1.03%   |
| WDC WD7500BPKX-80HPJT0 752GB     | 1        | 1      | 1.03%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1        | 1      | 1.03%   |
| WDC WD5000AAKS-00A7B0 500GB      | 1        | 1      | 1.03%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 1      | 1.03%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 3      | 1.03%   |
| WDC WD400BD-60LRA0 40GB          | 1        | 1      | 1.03%   |
| WDC WD400BB-75CAA0 40GB          | 1        | 1      | 1.03%   |
| WDC WD3200AAJS-56M0A0 320GB      | 1        | 1      | 1.03%   |
| WDC WD2500AAKX-001CA0 250GB      | 1        | 1      | 1.03%   |
| WDC WD2500AAKS-00VSA0 250GB      | 1        | 2      | 1.03%   |
| WDC WD2500AAJS-00YZCA0 250GB     | 1        | 1      | 1.03%   |
| WDC WD2500AAJS-00B4A0 250GB      | 1        | 1      | 1.03%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 1      | 1.03%   |
| WDC WD1600AAJS-00B4A0 160GB      | 1        | 1      | 1.03%   |
| WDC WD10JPVX-08JC3T5 1TB         | 1        | 1      | 1.03%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1        | 1      | 1.03%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 1      | 1.03%   |
| WDC WD10EARS-00MVWB0 1TB         | 1        | 1      | 1.03%   |
| WDC WD10EALX-009BA0 1TB          | 1        | 1      | 1.03%   |
| WDC WD10EADS-00L5B1 1TB          | 1        | 1      | 1.03%   |
| WDC WD1000DHTZ-04N21V0 1TB       | 1        | 1      | 1.03%   |
| WDC WD Blue SA510 2.5 1000GB     | 1        | 1      | 1.03%   |
| Toshiba MK3263GSX 320GB          | 1        | 1      | 1.03%   |
| Toshiba DT01ACA200 2TB           | 1        | 1      | 1.03%   |
| SSSTC CVB-8D128-HP 128GB         | 1        | 1      | 1.03%   |
| Seagate ST9500325AS 500GB        | 1        | 1      | 1.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 42       | 57     | 44.21%  |
| Seagate             | 20       | 23     | 21.05%  |
| Samsung Electronics | 7        | 8      | 7.37%   |
| Hitachi             | 7        | 8      | 7.37%   |
| Kingston            | 3        | 3      | 3.16%   |
| Toshiba             | 2        | 2      | 2.11%   |
| SanDisk             | 2        | 2      | 2.11%   |
| Maxtor              | 2        | 2      | 2.11%   |
| Intel               | 2        | 2      | 2.11%   |
| Crucial             | 2        | 2      | 2.11%   |
| ZHITAI              | 1        | 1      | 1.05%   |
| SSSTC               | 1        | 1      | 1.05%   |
| Mushkin             | 1        | 1      | 1.05%   |
| LITEON              | 1        | 1      | 1.05%   |
| KingSpec            | 1        | 1      | 1.05%   |
| A-DATA Technology   | 1        | 1      | 1.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 39       | 53     | 54.17%  |
| Seagate             | 20       | 23     | 27.78%  |
| Hitachi             | 7        | 8      | 9.72%   |
| Toshiba             | 2        | 2      | 2.78%   |
| Samsung Electronics | 2        | 3      | 2.78%   |
| Maxtor              | 2        | 2      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 65       | 91     | 73.86%  |
| SSD  | 20       | 21     | 22.73%  |
| NVMe | 3        | 3      | 3.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB | 1        | 1      | 100%    |

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
| Works    | 316      | 679    | 60.77%  |
| Detected | 116      | 320    | 22.31%  |
| Malfunc  | 86       | 115    | 16.54%  |
| Failed   | 1        | 1      | 0.19%   |
| Limited  | 1        | 1      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 295      | 43%     |
| AMD                            | 146      | 21.28%  |
| Samsung Electronics            | 62       | 9.04%   |
| SanDisk                        | 28       | 4.08%   |
| ASMedia Technology             | 26       | 3.79%   |
| Kingston Technology Company    | 19       | 2.77%   |
| Micron/Crucial Technology      | 15       | 2.19%   |
| Phison Electronics             | 13       | 1.9%    |
| JMicron Technology             | 12       | 1.75%   |
| Nvidia                         | 10       | 1.46%   |
| Marvell Technology Group       | 9        | 1.31%   |
| Silicon Motion                 | 6        | 0.87%   |
| KIOXIA                         | 5        | 0.73%   |
| ADATA Technology               | 5        | 0.73%   |
| LSI Logic / Symbios Logic      | 3        | 0.44%   |
| Yangtze Memory Technologies    | 2        | 0.29%   |
| VIA Technologies               | 2        | 0.29%   |
| Transcend                      | 2        | 0.29%   |
| Toshiba America Info Systems   | 2        | 0.29%   |
| SK hynix                       | 2        | 0.29%   |
| Silicon Image                  | 2        | 0.29%   |
| Micron Technology              | 2        | 0.29%   |
| MAXIO Technology (Hangzhou)    | 2        | 0.29%   |
| Broadcom / LSI                 | 2        | 0.29%   |
| Adaptec                        | 2        | 0.29%   |
| Solid State Storage Technology | 1        | 0.15%   |
| Seagate Technology             | 1        | 0.15%   |
| Realtek Semiconductor          | 1        | 0.15%   |
| Radian Memory Systems          | 1        | 0.15%   |
| Netac Technology               | 1        | 0.15%   |
| Loongson Technology            | 1        | 0.15%   |
| INNOGRIT                       | 1        | 0.15%   |
| IBM                            | 1        | 0.15%   |
| HighPoint Technologies         | 1        | 0.15%   |
| Hewlett-Packard                | 1        | 0.15%   |
| Biwin Storage Technology       | 1        | 0.15%   |
| Artop Electronic               | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 94       | 11.19%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 51       | 6.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 41       | 4.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 30       | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 26       | 3.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 26       | 3.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 25       | 2.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 25       | 2.98%   |
| AMD 500 Series Chipset SATA Controller                                                  | 20       | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 2.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 2.02%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 15       | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 1.55%   |
| Samsung NVMe SSD Controller 980                                                         | 12       | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12       | 1.43%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 11       | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 1.31%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10       | 1.19%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 10       | 1.19%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 1.19%   |
| Intel 82Q963/Q965 PT IDER Controller                                                    | 9        | 1.07%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 8        | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 0.95%   |
| Kingston Company Company Non-Volatile memory controller                                 | 7        | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6        | 0.71%   |
| Phison E12 NVMe Controller                                                              | 6        | 0.71%   |
| JMicron JMB368 IDE controller                                                           | 6        | 0.71%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 6        | 0.71%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6        | 0.71%   |
| AMD FCH SATA Controller D                                                               | 6        | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 5        | 0.6%    |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 5        | 0.6%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 5        | 0.6%    |
| Kingston Company NVMe Controller                                                        | 5        | 0.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 387      | 58.73%  |
| NVMe | 147      | 22.31%  |
| IDE  | 89       | 13.51%  |
| RAID | 30       | 4.55%   |
| SAS  | 4        | 0.61%   |
| SCSI | 2        | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 299      | 65%     |
| AMD               | 159      | 34.57%  |
| Loongson          | 1        | 0.22%   |
| CHRP IBM,8233-E8B | 1        | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz           | 21       | 4.56%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 16       | 3.47%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 12       | 2.6%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 10       | 2.17%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 10       | 2.17%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 9        | 1.95%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 7        | 1.52%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 7        | 1.52%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 7        | 1.52%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 6        | 1.3%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 6        | 1.3%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 1.3%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 1.08%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.08%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 5        | 1.08%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 4        | 0.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 0.87%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.87%   |
| Intel 13th Gen Core i7-13700K               | 4        | 0.87%   |
| Intel 12th Gen Core i5-12400F               | 4        | 0.87%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 4        | 0.87%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 0.87%   |
| Intel Xeon W-2135 CPU @ 3.70GHz             | 3        | 0.65%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 3        | 0.65%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 3        | 0.65%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.65%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.65%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 3        | 0.65%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.65%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.65%   |
| Intel Celeron N5105 @ 2.00GHz               | 3        | 0.65%   |
| Intel 12th Gen Core i7-12700K               | 3        | 0.65%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 3        | 0.65%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.65%   |
| AMD Ryzen 7 7730U with Radeon Graphics      | 3        | 0.65%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 3        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 58       | 12.61%  |
| Intel Core i7           | 56       | 12.17%  |
| AMD Ryzen 5             | 39       | 8.48%   |
| Other                   | 38       | 8.26%   |
| AMD Ryzen 7             | 38       | 8.26%   |
| Intel Pentium           | 36       | 7.83%   |
| Intel Xeon              | 24       | 5.22%   |
| AMD Ryzen 9             | 24       | 5.22%   |
| Intel Core i3           | 23       | 5%      |
| Intel Celeron           | 17       | 3.7%    |
| Intel Core 2            | 13       | 2.83%   |
| AMD Ryzen 3             | 13       | 2.83%   |
| Intel Core 2 Duo        | 12       | 2.61%   |
| Intel Pentium Dual-Core | 11       | 2.39%   |
| AMD FX                  | 7        | 1.52%   |
| Intel Core 2 Quad       | 6        | 1.3%    |
| AMD Ryzen 5 PRO         | 6        | 1.3%    |
| AMD Athlon 64 X2        | 4        | 0.87%   |
| AMD Athlon              | 4        | 0.87%   |
| AMD Phenom II X3        | 3        | 0.65%   |
| AMD Athlon II X3        | 3        | 0.65%   |
| Intel Pentium Gold      | 2        | 0.43%   |
| Intel Pentium 4         | 2        | 0.43%   |
| AMD Phenom II X4        | 2        | 0.43%   |
| AMD GX                  | 2        | 0.43%   |
| AMD EPYC                | 2        | 0.43%   |
| AMD Athlon II X2        | 2        | 0.43%   |
| AMD A6                  | 2        | 0.43%   |
| Intel Pentium Silver    | 1        | 0.22%   |
| Intel Core m3           | 1        | 0.22%   |
| Intel Core i9           | 1        | 0.22%   |
| AMD Ryzen Threadripper  | 1        | 0.22%   |
| AMD PRO A10             | 1        | 0.22%   |
| AMD Phenom II X6        | 1        | 0.22%   |
| AMD Phenom              | 1        | 0.22%   |
| AMD E                   | 1        | 0.22%   |
| AMD Athlon II X4        | 1        | 0.22%   |
| AMD A8                  | 1        | 0.22%   |
| AMD A10                 | 1        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 137      | 29.78%  |
| 2      | 129      | 28.04%  |
| 8      | 70       | 15.22%  |
| 6      | 58       | 12.61%  |
| 12     | 21       | 4.57%   |
| 16     | 16       | 3.48%   |
| 1      | 8        | 1.74%   |
| 3      | 7        | 1.52%   |
| 24     | 5        | 1.09%   |
| 10     | 5        | 1.09%   |
| 14     | 3        | 0.65%   |
| 22     | 1        | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 454      | 98.7%   |
| 2      | 6        | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 273      | 59.35%  |
| 1      | 186      | 40.43%  |
| 4      | 1        | 0.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 458      | 99.57%  |
| 32-bit         | 1        | 0.22%   |
| Unknown        | 1        | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 112      | 24.3%   |
| 0x306c3    | 51       | 11.06%  |
| 0xa0655    | 22       | 4.77%   |
| 0x1067a    | 20       | 4.34%   |
| 0x08108109 | 17       | 3.69%   |
| 0x506e3    | 16       | 3.47%   |
| 0x0a601203 | 13       | 2.82%   |
| 0x6f2      | 12       | 2.6%    |
| 0x90672    | 10       | 2.17%   |
| 0x306a9    | 10       | 2.17%   |
| 0x0a50000d | 10       | 2.17%   |
| 0x206a7    | 9        | 1.95%   |
| 0x0a20120a | 9        | 1.95%   |
| 0x906e9    | 8        | 1.74%   |
| 0x906ea    | 7        | 1.52%   |
| 0x0800820d | 7        | 1.52%   |
| 0xb0671    | 6        | 1.3%    |
| 0x08701021 | 6        | 1.3%    |
| 0x0810100b | 6        | 1.3%    |
| 0x08101016 | 5        | 1.08%   |
| 0xa0653    | 4        | 0.87%   |
| 0x406f1    | 4        | 0.87%   |
| 0x10676    | 4        | 0.87%   |
| 0x0a201016 | 4        | 0.87%   |
| 0x08600106 | 4        | 0.87%   |
| 0x08001138 | 4        | 0.87%   |
| 0x06000852 | 4        | 0.87%   |
| 0x906c0    | 3        | 0.65%   |
| 0x90675    | 3        | 0.65%   |
| 0x50654    | 3        | 0.65%   |
| 0x20655    | 3        | 0.65%   |
| 0x106a5    | 3        | 0.65%   |
| 0x0600611a | 3        | 0.65%   |
| 0x010000c6 | 3        | 0.65%   |
| 0x806c2    | 2        | 0.43%   |
| 0x6fd      | 2        | 0.43%   |
| 0x6fb      | 2        | 0.43%   |
| 0x40651    | 2        | 0.43%   |
| 0x30678    | 2        | 0.43%   |
| 0x206d7    | 2        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 67       | 14.53%  |
| Zen 3            | 39       | 8.46%   |
| CometLake        | 31       | 6.72%   |
| Zen+             | 30       | 6.51%   |
| Penryn           | 30       | 6.51%   |
| KabyLake         | 28       | 6.07%   |
| Unknown          | 28       | 6.07%   |
| Skylake          | 27       | 5.86%   |
| Zen 2            | 23       | 4.99%   |
| Alderlake Hybrid | 21       | 4.56%   |
| Core             | 18       | 3.9%    |
| Zen              | 17       | 3.69%   |
| SandyBridge      | 15       | 3.25%   |
| IvyBridge        | 15       | 3.25%   |
| K10              | 14       | 3.04%   |
| Westmere         | 7        | 1.52%   |
| Piledriver       | 7        | 1.52%   |
| Nehalem          | 6        | 1.3%    |
| Broadwell        | 6        | 1.3%    |
| Tremont          | 5        | 1.08%   |
| TigerLake        | 4        | 0.87%   |
| Silvermont       | 4        | 0.87%   |
| K8 Hammer        | 4        | 0.87%   |
| Excavator        | 4        | 0.87%   |
| NetBurst         | 2        | 0.43%   |
| Jaguar           | 2        | 0.43%   |
| Goldmont plus    | 2        | 0.43%   |
| Steamroller      | 1        | 0.22%   |
| Icelake          | 1        | 0.22%   |
| Gracemont        | 1        | 0.22%   |
| Goldmont         | 1        | 0.22%   |
| Bobcat           | 1        | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 165      | 33.6%   |
| Nvidia                     | 159      | 32.38%  |
| AMD                        | 155      | 31.57%  |
| ASPEED Technology          | 7        | 1.43%   |
| Matrox Electronics Systems | 4        | 0.81%   |
| Loongson Technology        | 1        | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 31       | 6.18%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 21       | 4.18%   |
| Nvidia GF108 [GeForce GT 730]                                               | 18       | 3.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 18       | 3.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 17       | 3.39%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 13       | 2.59%   |
| AMD Raphael                                                                 | 13       | 2.59%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 13       | 2.59%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 12       | 2.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 11       | 2.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 1.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 1.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 8        | 1.59%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.39%   |
| Intel HD Graphics 630                                                       | 7        | 1.39%   |
| Intel HD Graphics 530                                                       | 7        | 1.39%   |
| ASPEED Technology ASPEED Graphics Family                                    | 7        | 1.39%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 1.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 1.2%    |
| Intel HD Graphics 510                                                       | 6        | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.2%    |
| Intel AlderLake-S GT1                                                       | 6        | 1.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.2%    |
| AMD Renoir                                                                  | 6        | 1.2%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 6        | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1%      |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 5        | 1%      |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 1%      |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 0.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4        | 0.8%    |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 4        | 0.8%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 4        | 0.8%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 0.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 0.8%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 0.8%    |
| AMD Barcelo                                                                 | 4        | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 140      | 30.3%   |
| 1 x Nvidia              | 136      | 29.44%  |
| 1 x AMD                 | 133      | 28.79%  |
| Intel + Nvidia          | 16       | 3.46%   |
| 2 x AMD                 | 10       | 2.16%   |
| 1 x ASPEED              | 6        | 1.3%    |
| AMD + Nvidia            | 6        | 1.3%    |
| 1 x Matrox              | 4        | 0.87%   |
| Other                   | 3        | 0.65%   |
| Intel + AMD             | 3        | 0.65%   |
| 2 x Intel               | 2        | 0.43%   |
| 1 x Loongson Technology | 1        | 0.22%   |
| AMD + Matrox            | 1        | 0.22%   |
| AMD + ASPEED            | 1        | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 256      | 55.65%  |
| Unknown     | 147      | 31.96%  |
| Proprietary | 57       | 12.39%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 313      | 67.9%   |
| 7.01-8.0   | 34       | 7.38%   |
| 1.01-2.0   | 26       | 5.64%   |
| 0.01-0.5   | 24       | 5.21%   |
| 3.01-4.0   | 23       | 4.99%   |
| 0.51-1.0   | 13       | 2.82%   |
| 8.01-16.0  | 12       | 2.6%    |
| 5.01-6.0   | 6        | 1.3%    |
| 16.01-24.0 | 6        | 1.3%    |
| 2.01-3.0   | 3        | 0.65%   |
| 4.01-5.0   | 1        | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 49       | 14.2%   |
| Dell                 | 35       | 10.14%  |
| Goldstar             | 34       | 9.86%   |
| Hewlett-Packard      | 25       | 7.25%   |
| Ancor Communications | 24       | 6.96%   |
| BenQ                 | 21       | 6.09%   |
| Acer                 | 19       | 5.51%   |
| AOC                  | 17       | 4.93%   |
| Philips              | 11       | 3.19%   |
| Lenovo               | 11       | 3.19%   |
| ASUSTek Computer     | 8        | 2.32%   |
| LG Electronics       | 7        | 2.03%   |
| Iiyama               | 7        | 2.03%   |
| Sceptre Tech         | 6        | 1.74%   |
| Unknown              | 5        | 1.45%   |
| ViewSonic            | 4        | 1.16%   |
| Unknown              | 4        | 1.16%   |
| Vizio                | 3        | 0.87%   |
| Sony                 | 3        | 0.87%   |
| RTK                  | 3        | 0.87%   |
| Mi                   | 3        | 0.87%   |
| HKC                  | 3        | 0.87%   |
| Fujitsu Siemens      | 3        | 0.87%   |
| Panasonic            | 2        | 0.58%   |
| MStar                | 2        | 0.58%   |
| MiTAC                | 2        | 0.58%   |
| HannStar             | 2        | 0.58%   |
| Gigabyte Technology  | 2        | 0.58%   |
| CHR                  | 2        | 0.58%   |
| YSD                  | 1        | 0.29%   |
| Vita                 | 1        | 0.29%   |
| TCL                  | 1        | 0.29%   |
| SAC                  | 1        | 0.29%   |
| Plain Tree Systems   | 1        | 0.29%   |
| Pixio                | 1        | 0.29%   |
| PCT                  | 1        | 0.29%   |
| Orion                | 1        | 0.29%   |
| NEC Computers        | 1        | 0.29%   |
| MSI                  | 1        | 0.29%   |
| MSD                  | 1        | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 15       | 4.1%    |
| Unknown                                                               | 5        | 1.37%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3        | 0.82%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                | 3        | 0.82%   |
| Hewlett-Packard 23xi HWP3032 1920x1080 509x286mm 23.0-inch            | 3        | 0.82%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 3        | 0.82%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 3        | 0.82%   |
| Sceptre Tech Sceptre Y32 SPT0CAD 2560x1440 697x392mm 31.5-inch        | 2        | 0.55%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 2        | 0.55%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.55%   |
| RTK FHD HDR RTK3B3A 1920x1080 344x195mm 15.6-inch                     | 2        | 0.55%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 2        | 0.55%   |
| MStar Demo MST0030 2288x1430 708x398mm 32.0-inch                      | 2        | 0.55%   |
| LG Electronics LCD Monitor LG FULL HD                                 | 2        | 0.55%   |
| Lenovo T27hv-20 LEN62A9 2560x1440 597x336mm 27.0-inch                 | 2        | 0.55%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 2        | 0.55%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2        | 0.55%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2        | 0.55%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2        | 0.55%   |
| Dell G3223Q DEL428C 3840x2160 710x400mm 32.1-inch                     | 2        | 0.55%   |
| Dell E2414H DEL4091 1920x1080 531x299mm 24.0-inch                     | 2        | 0.55%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                     | 2        | 0.55%   |
| BenQ G2222HDL BNQ785A 1920x1080 477x268mm 21.5-inch                   | 2        | 0.55%   |
| AOC 22B2WG5 AOC2202 1920x1080 477x268mm 21.5-inch                     | 2        | 0.55%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2        | 0.55%   |
| YSD HDMI YSD0190 1440x900 368x207mm 16.6-inch                         | 1        | 0.27%   |
| Vizio E421VA VIZ0072 1920x1080 930x523mm 42.0-inch                    | 1        | 0.27%   |
| Vizio E231-B1 VIZ0095 1360x768 534x311mm 24.3-inch                    | 1        | 0.27%   |
| Vizio D40f-G9 VIZ1027 1920x1080 477x268mm 21.5-inch                   | 1        | 0.27%   |
| Vita V195EW-W VIT1950 1600x900 430x240mm 19.4-inch                    | 1        | 0.27%   |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch         | 1        | 0.27%   |
| ViewSonic VG2755-2K VSC4E37 2560x1440 597x336mm 27.0-inch             | 1        | 0.27%   |
| ViewSonic VG175 VSCDD00 1280x1024 345x276mm 17.4-inch                 | 1        | 0.27%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1        | 0.27%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.27%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1        | 0.27%   |
| Sony TV SNYFF00 1360x768                                              | 1        | 0.27%   |
| Sony TV *30 SNYB905 3840x2160 1439x809mm 65.0-inch                    | 1        | 0.27%   |
| Sony SDM-HS75 SNY2400 1280x1024 338x270mm 17.0-inch                   | 1        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 146      | 43.2%   |
| 3840x2160 (4K)     | 46       | 13.61%  |
| 2560x1440 (QHD)    | 34       | 10.06%  |
| Unknown            | 15       | 4.44%   |
| 1600x900 (HD+)     | 11       | 3.25%   |
| 1920x1200 (WUXGA)  | 10       | 2.96%   |
| 1680x1050 (WSXGA+) | 10       | 2.96%   |
| 1366x768 (WXGA)    | 10       | 2.96%   |
| 1280x1024 (SXGA)   | 9        | 2.66%   |
| 3440x1440          | 7        | 2.07%   |
| 1440x900 (WXGA+)   | 7        | 2.07%   |
| 2560x1080          | 5        | 1.48%   |
| 1360x768           | 5        | 1.48%   |
| 4480x1440          | 4        | 1.18%   |
| 2288x1287          | 3        | 0.89%   |
| 1920x540           | 3        | 0.89%   |
| 7680x2160          | 2        | 0.59%   |
| 3840x1600          | 2        | 0.59%   |
| 3840x1200          | 2        | 0.59%   |
| 7280x2160          | 1        | 0.3%    |
| 6400x2160          | 1        | 0.3%    |
| 6400x1440          | 1        | 0.3%    |
| 5760x2160          | 1        | 0.3%    |
| 3840x1080          | 1        | 0.3%    |
| 3286x1080          | 1        | 0.3%    |
| 1600x1200          | 1        | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 53       | 15.68%  |
| 21      | 53       | 15.68%  |
| 24      | 48       | 14.2%   |
| 23      | 35       | 10.36%  |
| Unknown | 33       | 9.76%   |
| 31      | 16       | 4.73%   |
| 18      | 13       | 3.85%   |
| 20      | 11       | 3.25%   |
| 19      | 11       | 3.25%   |
| 34      | 10       | 2.96%   |
| 32      | 6        | 1.78%   |
| 22      | 6        | 1.78%   |
| 17      | 5        | 1.48%   |
| 84      | 4        | 1.18%   |
| 142     | 3        | 0.89%   |
| 52      | 3        | 0.89%   |
| 40      | 3        | 0.89%   |
| 15      | 3        | 0.89%   |
| 72      | 2        | 0.59%   |
| 54      | 2        | 0.59%   |
| 46      | 2        | 0.59%   |
| 28      | 2        | 0.59%   |
| 26      | 2        | 0.59%   |
| 85      | 1        | 0.3%    |
| 49      | 1        | 0.3%    |
| 48      | 1        | 0.3%    |
| 43      | 1        | 0.3%    |
| 42      | 1        | 0.3%    |
| 39      | 1        | 0.3%    |
| 38      | 1        | 0.3%    |
| 37      | 1        | 0.3%    |
| 35      | 1        | 0.3%    |
| 33      | 1        | 0.3%    |
| 16      | 1        | 0.3%    |
| 14      | 1        | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 126      | 38.53%  |
| 401-500        | 87       | 26.61%  |
| Unknown        | 33       | 10.09%  |
| 601-700        | 22       | 6.73%   |
| 701-800        | 17       | 5.2%    |
| 1001-1500      | 9        | 2.75%   |
| 301-350        | 8        | 2.45%   |
| 801-900        | 7        | 2.14%   |
| 1501-2000      | 7        | 2.14%   |
| 351-400        | 5        | 1.53%   |
| More than 2000 | 3        | 0.92%   |
| 901-1000       | 2        | 0.61%   |
| 201-300        | 1        | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 220      | 71.2%   |
| 16/10   | 30       | 9.71%   |
| Unknown | 29       | 9.39%   |
| 21/9    | 13       | 4.21%   |
| 5/4     | 9        | 2.91%   |
| 1.00    | 3        | 0.97%   |
| 4/3     | 2        | 0.65%   |
| 32/9    | 2        | 0.65%   |
| 3/2     | 1        | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 112      | 33.14%  |
| 301-350        | 54       | 15.98%  |
| 351-500        | 36       | 10.65%  |
| Unknown        | 33       | 9.76%   |
| 151-200        | 32       | 9.47%   |
| 251-300        | 22       | 6.51%   |
| More than 1000 | 17       | 5.03%   |
| 141-150        | 16       | 4.73%   |
| 501-1000       | 10       | 2.96%   |
| 101-110        | 4        | 1.18%   |
| 131-140        | 1        | 0.3%    |
| 111-120        | 1        | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 163      | 50.62%  |
| 101-120 | 78       | 24.22%  |
| Unknown | 33       | 10.25%  |
| 121-160 | 21       | 6.52%   |
| 161-240 | 15       | 4.66%   |
| 1-50    | 12       | 3.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 244      | 52.81%  |
| 0     | 161      | 34.85%  |
| 2     | 48       | 10.39%  |
| 3     | 9        | 1.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 315      | 49.53%  |
| Intel                           | 172      | 27.04%  |
| Qualcomm Atheros                | 27       | 4.25%   |
| MediaTek                        | 21       | 3.3%    |
| Broadcom                        | 15       | 2.36%   |
| Nvidia                          | 10       | 1.57%   |
| TP-Link                         | 8        | 1.26%   |
| Ralink Technology               | 8        | 1.26%   |
| Aquantia                        | 8        | 1.26%   |
| Marvell Technology Group        | 5        | 0.79%   |
| ASUSTek Computer                | 4        | 0.63%   |
| ASIX Electronics                | 4        | 0.63%   |
| Samsung Electronics             | 3        | 0.47%   |
| Qualcomm Atheros Communications | 2        | 0.31%   |
| Mellanox Technologies           | 2        | 0.31%   |
| D-Link                          | 2        | 0.31%   |
| Broadcom Limited                | 2        | 0.31%   |
| American Megatrends             | 2        | 0.31%   |
| 3Com                            | 2        | 0.31%   |
| Texas Instruments               | 1        | 0.16%   |
| SysKonnect                      | 1        | 0.16%   |
| Solarflare Communications       | 1        | 0.16%   |
| Raspberry Pi                    | 1        | 0.16%   |
| Ralink                          | 1        | 0.16%   |
| Qualcomm                        | 1        | 0.16%   |
| QinHeng Electronics             | 1        | 0.16%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.16%   |
| NetGear                         | 1        | 0.16%   |
| Motorola PCS                    | 1        | 0.16%   |
| Microsoft                       | 1        | 0.16%   |
| MCS                             | 1        | 0.16%   |
| Loongson Technology             | 1        | 0.16%   |
| Linksys                         | 1        | 0.16%   |
| Insyde Software                 | 1        | 0.16%   |
| IBM                             | 1        | 0.16%   |
| Google                          | 1        | 0.16%   |
| Emulex                          | 1        | 0.16%   |
| Edimax Technology               | 1        | 0.16%   |
| DisplayLink                     | 1        | 0.16%   |
| D-Link System                   | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 240      | 33.33%  |
| Realtek RTL8125 2.5GbE Controller                                   | 40       | 5.56%   |
| Intel Ethernet Controller I225-V                                    | 25       | 3.47%   |
| Intel Wi-Fi 6 AX200                                                 | 24       | 3.33%   |
| Intel I211 Gigabit Network Connection                               | 19       | 2.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 15       | 2.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 12       | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                | 12       | 1.67%   |
| Intel 82566DM Gigabit Network Connection                            | 12       | 1.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 11       | 1.53%   |
| Intel Ethernet Connection I217-LM                                   | 11       | 1.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 10       | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 8        | 1.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller         | 7        | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 7        | 0.97%   |
| Intel I210 Gigabit Network Connection                               | 7        | 0.97%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 7        | 0.97%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 6        | 0.83%   |
| Intel 700 Series Chipset Family Wi-Fi                               | 6        | 0.83%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5        | 0.69%   |
| Realtek 802.11ac NIC                                                | 5        | 0.69%   |
| Intel Wireless 7260                                                 | 5        | 0.69%   |
| Intel Ethernet Connection I217-V                                    | 5        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 4        | 0.56%   |
| Nvidia MCP61 Ethernet                                               | 4        | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 4        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4        | 0.56%   |
| Intel 82579V Gigabit Network Connection                             | 4        | 0.56%   |
| Intel 82574L Gigabit Network Connection                             | 4        | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 3        | 0.42%   |
| TP-Link 802.11ac WLAN Adapter                                       | 3        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 3        | 0.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 3        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 3        | 0.42%   |
| Nvidia MCP65 Ethernet                                               | 3        | 0.42%   |
| Intel Wireless-AC 9260                                              | 3        | 0.42%   |
| Intel Ethernet Controller I226-V                                    | 3        | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                               | 3        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 72       | 40.22%  |
| Realtek Semiconductor           | 35       | 19.55%  |
| MediaTek                        | 20       | 11.17%  |
| Qualcomm Atheros                | 13       | 7.26%   |
| TP-Link                         | 8        | 4.47%   |
| Ralink Technology               | 8        | 4.47%   |
| Broadcom                        | 6        | 3.35%   |
| ASUSTek Computer                | 4        | 2.23%   |
| Qualcomm Atheros Communications | 2        | 1.12%   |
| D-Link                          | 2        | 1.12%   |
| Broadcom Limited                | 2        | 1.12%   |
| Ralink                          | 1        | 0.56%   |
| NetGear                         | 1        | 0.56%   |
| Microsoft                       | 1        | 0.56%   |
| Marvell Technology Group        | 1        | 0.56%   |
| Linksys                         | 1        | 0.56%   |
| Edimax Technology               | 1        | 0.56%   |
| Belkin Components               | 1        | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 24       | 13.26%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12       | 6.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11       | 6.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 7        | 3.87%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 7        | 3.87%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 3.31%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 6        | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5        | 2.76%   |
| Realtek 802.11ac NIC                                           | 5        | 2.76%   |
| Intel Wireless 7260                                            | 5        | 2.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4        | 2.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4        | 2.21%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3        | 1.66%   |
| TP-Link 802.11ac WLAN Adapter                                  | 3        | 1.66%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 3        | 1.66%   |
| Intel Wireless-AC 9260                                         | 3        | 1.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 1.1%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2        | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 2        | 1.1%    |
| Ralink RT5572 Wireless Adapter                                 | 2        | 1.1%    |
| Ralink RT5370 Wireless Adapter                                 | 2        | 1.1%    |
| Ralink MT7601U Wireless Adapter                                | 2        | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 1.1%    |
| Intel Wireless 8260                                            | 2        | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2        | 1.1%    |
| ASUS 802.11ac NIC                                              | 2        | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 0.55%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 1        | 0.55%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 0.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.55%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 0.55%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 0.55%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1        | 0.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 311      | 59.92%  |
| Intel                     | 136      | 26.2%   |
| Qualcomm Atheros          | 15       | 2.89%   |
| Nvidia                    | 10       | 1.93%   |
| Broadcom                  | 9        | 1.73%   |
| Aquantia                  | 8        | 1.54%   |
| Marvell Technology Group  | 4        | 0.77%   |
| ASIX Electronics          | 4        | 0.77%   |
| Samsung Electronics       | 3        | 0.58%   |
| Mellanox Technologies     | 2        | 0.39%   |
| American Megatrends       | 2        | 0.39%   |
| 3Com                      | 2        | 0.39%   |
| SysKonnect                | 1        | 0.19%   |
| Solarflare Communications | 1        | 0.19%   |
| Qualcomm                  | 1        | 0.19%   |
| Motorola PCS              | 1        | 0.19%   |
| MediaTek                  | 1        | 0.19%   |
| Loongson Technology       | 1        | 0.19%   |
| Insyde Software           | 1        | 0.19%   |
| IBM                       | 1        | 0.19%   |
| Google                    | 1        | 0.19%   |
| Emulex                    | 1        | 0.19%   |
| DisplayLink               | 1        | 0.19%   |
| D-Link System             | 1        | 0.19%   |
| Accton Technology         | 1        | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 240      | 45.03%  |
| Realtek RTL8125 2.5GbE Controller                                   | 40       | 7.5%    |
| Intel Ethernet Controller I225-V                                    | 25       | 4.69%   |
| Intel I211 Gigabit Network Connection                               | 19       | 3.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 15       | 2.81%   |
| Intel Ethernet Connection (2) I219-V                                | 12       | 2.25%   |
| Intel 82566DM Gigabit Network Connection                            | 12       | 2.25%   |
| Intel Ethernet Connection I217-LM                                   | 11       | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 10       | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 8        | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 7        | 1.31%   |
| Intel I210 Gigabit Network Connection                               | 7        | 1.31%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 1.13%   |
| Intel Ethernet Connection I217-V                                    | 5        | 0.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.75%   |
| Nvidia MCP61 Ethernet                                               | 4        | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 4        | 0.75%   |
| Intel 82579V Gigabit Network Connection                             | 4        | 0.75%   |
| Intel 82574L Gigabit Network Connection                             | 4        | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 3        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 3        | 0.56%   |
| Nvidia MCP65 Ethernet                                               | 3        | 0.56%   |
| Intel Ethernet Controller I226-V                                    | 3        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                               | 3        | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 3        | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                       | 3        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 2        | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2        | 0.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                       | 2        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 2        | 0.38%   |
| Intel Ethernet Connection (5) I219-LM                               | 2        | 0.38%   |
| Intel Ethernet Connection (12) I219-V                               | 2        | 0.38%   |
| Intel Ethernet Connection (11) I219-LM                              | 2        | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 2        | 0.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express             | 2        | 0.38%   |
| American Megatrends Virtual Ethernet.                               | 2        | 0.38%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                       | 2        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 456      | 73.19%  |
| WiFi     | 162      | 26%     |
| Modem    | 3        | 0.48%   |
| Unknown  | 2        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 393      | 83.62%  |
| WiFi     | 77       | 16.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 297      | 64.15%  |
| 2     | 130      | 28.08%  |
| 3     | 24       | 5.18%   |
| 4     | 7        | 1.51%   |
| 6     | 3        | 0.65%   |
| 9     | 1        | 0.22%   |
| 0     | 1        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 366      | 79.39%  |
| Yes  | 95       | 20.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 61       | 42.66%  |
| Realtek Semiconductor           | 21       | 14.69%  |
| Cambridge Silicon Radio         | 18       | 12.59%  |
| MediaTek                        | 11       | 7.69%   |
| ASUSTek Computer                | 7        | 4.9%    |
| Broadcom                        | 5        | 3.5%    |
| TP-Link                         | 4        | 2.8%    |
| Foxconn / Hon Hai               | 4        | 2.8%    |
| IMC Networks                    | 3        | 2.1%    |
| Apple                           | 2        | 1.4%    |
| Realtek                         | 1        | 0.7%    |
| Qualcomm Atheros Communications | 1        | 0.7%    |
| Lite-On Technology              | 1        | 0.7%    |
| Integrated System Solution      | 1        | 0.7%    |
| HTC (High Tech Computer)        | 1        | 0.7%    |
| Edimax Technology               | 1        | 0.7%    |
| Dynex                           | 1        | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 20       | 13.99%  |
| Realtek Bluetooth Radio                                              | 19       | 13.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 18       | 12.59%  |
| MediaTek Wireless_Device                                             | 11       | 7.69%   |
| Intel AX201 Bluetooth                                                | 10       | 6.99%   |
| Intel Bluetooth wireless interface                                   | 9        | 6.29%   |
| Intel Bluetooth Device                                               | 9        | 6.29%   |
| Intel AX210 Bluetooth                                                | 9        | 6.29%   |
| TP-Link UB5A Adapter                                                 | 4        | 2.8%    |
| Foxconn / Hon Hai Wireless_Device                                    | 4        | 2.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 2.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 4        | 2.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3        | 2.1%    |
| IMC Networks Bluetooth Radio                                         | 3        | 2.1%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.4%    |
| Realtek Bluetooth Radio                                              | 1        | 0.7%    |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 0.7%    |
| Lite-On Bluetooth Device                                             | 1        | 0.7%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.7%    |
| Integrated System Solution Bluetooth Device                          | 1        | 0.7%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.7%    |
| Edimax Bluetooth Adapter                                             | 1        | 0.7%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.7%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                    | 1        | 0.7%    |
| ASUS Bluetooth Radio                                                 | 1        | 0.7%    |
| ASUS BCM20702A0                                                      | 1        | 0.7%    |
| ASUS ASUS USB-BT500                                                  | 1        | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 0.7%    |
| Apple Bluetooth Host Controller                                      | 1        | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 283      | 38.82%  |
| AMD                                          | 182      | 24.97%  |
| Nvidia                                       | 156      | 21.4%   |
| C-Media Electronics                          | 20       | 2.74%   |
| Logitech                                     | 9        | 1.23%   |
| Creative Labs                                | 8        | 1.1%    |
| Micro Star International                     | 6        | 0.82%   |
| ASUSTek Computer                             | 6        | 0.82%   |
| Realtek Semiconductor                        | 5        | 0.69%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.55%   |
| GN Netcom                                    | 4        | 0.55%   |
| Texas Instruments                            | 3        | 0.41%   |
| Kingston Technology                          | 3        | 0.41%   |
| JMTek                                        | 3        | 0.41%   |
| Generalplus Technology                       | 3        | 0.41%   |
| Focusrite-Novation                           | 3        | 0.41%   |
| Blue Microphones                             | 3        | 0.41%   |
| SteelSeries ApS                              | 2        | 0.27%   |
| Razer USA                                    | 2        | 0.27%   |
| Jieli Technology                             | 2        | 0.27%   |
| Yamaha                                       | 1        | 0.14%   |
| VIA Technologies                             | 1        | 0.14%   |
| USB MICROPHONE                               | 1        | 0.14%   |
| Tdlasunnic                                   | 1        | 0.14%   |
| Schiit Audio                                 | 1        | 0.14%   |
| Samson Technologies                          | 1        | 0.14%   |
| OPPO Electronics                             | 1        | 0.14%   |
| Loongson Technology                          | 1        | 0.14%   |
| Hewlett-Packard                              | 1        | 0.14%   |
| Global Sun Technology                        | 1        | 0.14%   |
| Giga-Byte Technology                         | 1        | 0.14%   |
| Dell                                         | 1        | 0.14%   |
| DCMT Technology                              | 1        | 0.14%   |
| D&M Holdings (Denon/Marantz)                 | 1        | 0.14%   |
| Creative Technology                          | 1        | 0.14%   |
| Corsair                                      | 1        | 0.14%   |
| Cayin                                        | 1        | 0.14%   |
| Bose                                         | 1        | 0.14%   |
| BlackWeb                                     | 1        | 0.14%   |
| BEHRINGER International                      | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 66       | 7.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 56       | 6.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 42       | 4.72%   |
| AMD Starship/Matisse HD Audio Controller                                   | 37       | 4.16%   |
| Intel 200 Series PCH HD Audio                                              | 30       | 3.37%   |
| Intel Comet Lake PCH cAVS                                                  | 25       | 2.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 24       | 2.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 24       | 2.7%    |
| Nvidia TU106 High Definition Audio Controller                              | 22       | 2.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 20       | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19       | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18       | 2.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 17       | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16       | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15       | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15       | 1.69%   |
| Intel Alder Lake-S HD Audio Controller                                     | 14       | 1.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 14       | 1.57%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 14       | 1.57%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 10       | 1.12%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 10       | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 9        | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9        | 1.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 1.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9        | 1.01%   |
| Nvidia High Definition Audio Controller                                    | 8        | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 0.9%    |
| Nvidia GA102 High Definition Audio Controller                              | 8        | 0.9%    |
| Nvidia GP108 High Definition Audio Controller                              | 7        | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 0.79%   |
| Micro Star International USB Audio                                         | 6        | 0.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 0.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 0.67%   |
| AMD Navi 10 HDMI Audio                                                     | 6        | 0.67%   |
| AMD Kabini HDMI/DP Audio                                                   | 6        | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 91       | 22.58%  |
| Unknown                                 | 59       | 14.64%  |
| Crucial                                 | 47       | 11.66%  |
| Samsung Electronics                     | 46       | 11.41%  |
| Corsair                                 | 25       | 6.2%    |
| SK hynix                                | 23       | 5.71%   |
| G.Skill                                 | 22       | 5.46%   |
| Hikvision                               | 18       | 4.47%   |
| A-DATA Technology                       | 12       | 2.98%   |
| Micron Technology                       | 11       | 2.73%   |
| Unknown                                 | 9        | 2.23%   |
| Patriot                                 | 8        | 1.99%   |
| Micro Memory Bank                       | 8        | 1.99%   |
| Team                                    | 5        | 1.24%   |
| AMD                                     | 3        | 0.74%   |
| Toshiba                                 | 2        | 0.5%    |
| V-Color                                 | 1        | 0.25%   |
| Unknown (ABCD)                          | 1        | 0.25%   |
| Unknown (0x7FFF)                        | 1        | 0.25%   |
| Unknown (0x0E9D)                        | 1        | 0.25%   |
| Transcend                               | 1        | 0.25%   |
| Smart                                   | 1        | 0.25%   |
| Silicon Power Computer & Communications | 1        | 0.25%   |
| Shenzhen Mic                            | 1        | 0.25%   |
| Patriot Memory (PDP Systems)            | 1        | 0.25%   |
| Nanya Technology                        | 1        | 0.25%   |
| KLEVV                                   | 1        | 0.25%   |
| GeIL                                    | 1        | 0.25%   |
| Elpida                                  | 1        | 0.25%   |
| 48spaces                                | 1        | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s                          | 18       | 4.15%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s                            | 15       | 3.46%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                              | 10       | 2.3%    |
| Unknown                                                                          | 9        | 2.07%   |
| Micro Memory Bank RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 2GB DIMM DDR2 667MT/s | 8        | 1.84%   |
| Unknown RAM Module 2GB DIMM SDRAM                                                | 7        | 1.61%   |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s                                   | 6        | 1.38%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                            | 6        | 1.38%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s                           | 6        | 1.38%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                             | 5        | 1.15%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3266MT/s                           | 5        | 1.15%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s                          | 5        | 1.15%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                             | 4        | 0.92%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                             | 4        | 0.92%   |
| Unknown RAM Module 1GB DIMM SDRAM                                                | 4        | 0.92%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                            | 4        | 0.92%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                         | 3        | 0.69%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                              | 3        | 0.69%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                              | 3        | 0.69%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                              | 3        | 0.69%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s                          | 3        | 0.69%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s                              | 3        | 0.69%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s                             | 3        | 0.69%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s                             | 3        | 0.69%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s                            | 3        | 0.69%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s                             | 3        | 0.69%   |
| Crucial RAM 524D313238363441413636372E384648FFFF 1GB DIMM DDR2 667MT/s           | 3        | 0.69%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                        | 2        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                                         | 2        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                         | 2        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                         | 2        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                         | 2        | 0.46%   |
| Unknown RAM Module 1GB DIMM 800MT/s                                              | 2        | 0.46%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s                                       | 2        | 0.46%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s                              | 2        | 0.46%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s                             | 2        | 0.46%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s                            | 2        | 0.46%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s                              | 2        | 0.46%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                              | 2        | 0.46%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                              | 2        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 183      | 48.28%  |
| DDR3    | 88       | 23.22%  |
| DDR2    | 29       | 7.65%   |
| DDR5    | 25       | 6.6%    |
| Unknown | 24       | 6.33%   |
| SDRAM   | 20       | 5.28%   |
| DDR     | 5        | 1.32%   |
| LPDDR4  | 4        | 1.06%   |
| LPDDR3  | 1        | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 337      | 89.87%  |
| SODIMM       | 32       | 8.53%   |
| Row Of Chips | 3        | 0.8%    |
| RIMM         | 2        | 0.53%   |
| FB-DIMM      | 1        | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 126      | 31.11%  |
| 16384 | 78       | 19.26%  |
| 4096  | 73       | 18.02%  |
| 2048  | 63       | 15.56%  |
| 32768 | 35       | 8.64%   |
| 1024  | 21       | 5.19%   |
| 512   | 7        | 1.73%   |
| 65536 | 1        | 0.25%   |
| 64    | 1        | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 45       | 11.19%  |
| 3200    | 44       | 10.95%  |
| 2667    | 41       | 10.2%   |
| 1333    | 31       | 7.71%   |
| 3600    | 27       | 6.72%   |
| 667     | 23       | 5.72%   |
| 2133    | 21       | 5.22%   |
| 2400    | 18       | 4.48%   |
| 1866    | 17       | 4.23%   |
| Unknown | 14       | 3.48%   |
| 800     | 13       | 3.23%   |
| 4333    | 10       | 2.49%   |
| 4800    | 9        | 2.24%   |
| 1066    | 8        | 1.99%   |
| 6000    | 6        | 1.49%   |
| 2666    | 6        | 1.49%   |
| 1867    | 6        | 1.49%   |
| 5200    | 5        | 1.24%   |
| 3266    | 5        | 1.24%   |
| 3000    | 5        | 1.24%   |
| 3733    | 3        | 0.75%   |
| 3400    | 3        | 0.75%   |
| 2866    | 3        | 0.75%   |
| 1067    | 3        | 0.75%   |
| 3933    | 2        | 0.5%    |
| 3800    | 2        | 0.5%    |
| 3534    | 2        | 0.5%    |
| 3334    | 2        | 0.5%    |
| 2933    | 2        | 0.5%    |
| 2800    | 2        | 0.5%    |
| 1800    | 2        | 0.5%    |
| 1639    | 2        | 0.5%    |
| 7000    | 1        | 0.25%   |
| 6800    | 1        | 0.25%   |
| 6400    | 1        | 0.25%   |
| 5800    | 1        | 0.25%   |
| 5600    | 1        | 0.25%   |
| 5354    | 1        | 0.25%   |
| 4199    | 1        | 0.25%   |
| 3666    | 1        | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 5        | 25%     |
| Brother Industries  | 5        | 25%     |
| Hewlett-Packard     | 3        | 15%     |
| Samsung Electronics | 2        | 10%     |
| Dymo-CoStar         | 2        | 10%     |
| Zebra               | 1        | 5%      |
| Seiko Epson         | 1        | 5%      |
| Pantum              | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon MF3010                           | 2        | 10%     |
| Zebra Printer                          | 1        | 5%      |
| Seiko Epson ET-4850 Series             | 1        | 5%      |
| Samsung M2070 Series                   | 1        | 5%      |
| Samsung M2020 Series                   | 1        | 5%      |
| Pantum P2500W series                   | 1        | 5%      |
| HP Officejet 4500 G510a-f              | 1        | 5%      |
| HP LaserJet P2035                      | 1        | 5%      |
| HP ENVY 5540 series                    | 1        | 5%      |
| Dymo-CoStar DYMO LabelWriter DUO       | 1        | 5%      |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 5%      |
| Canon PIXMA iP4300 Printer             | 1        | 5%      |
| Canon MF4010 series                    | 1        | 5%      |
| Canon LiDE 400                         | 1        | 5%      |
| Brother HL-L2390DW                     | 1        | 5%      |
| Brother HL-3040CN series               | 1        | 5%      |
| Brother HL-1110 series                 | 1        | 5%      |
| Brother DCP-L8450CDW                   | 1        | 5%      |
| Brother DCP-7030                       | 1        | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 40%     |
| Seiko Epson     | 1        | 20%     |
| Plustek         | 1        | 20%     |
| Hewlett-Packard | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1        | 20%     |
| Plustek 1200dpi USB Scanner                       | 1        | 20%     |
| HP ScanJet 82x0C                                  | 1        | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20                | 1        | 20%     |
| Canon CanoScan LiDE 210                           | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 29       | 45.31%  |
| Microsoft                     | 9        | 14.06%  |
| Microdia                      | 3        | 4.69%   |
| Generalplus Technology        | 3        | 4.69%   |
| Sunplus Innovation Technology | 2        | 3.13%   |
| Samsung Electronics           | 2        | 3.13%   |
| KYE Systems (Mouse Systems)   | 2        | 3.13%   |
| Jieli Technology              | 2        | 3.13%   |
| Z-Star Microelectronics       | 1        | 1.56%   |
| ValueHD                       | 1        | 1.56%   |
| Tobii Technology AB           | 1        | 1.56%   |
| Ruision                       | 1        | 1.56%   |
| Realtek Semiconductor         | 1        | 1.56%   |
| Quanta                        | 1        | 1.56%   |
| Magic Control Technology      | 1        | 1.56%   |
| IMC Networks                  | 1        | 1.56%   |
| GEMBIRD                       | 1        | 1.56%   |
| EVGA                          | 1        | 1.56%   |
| Creative Technology           | 1        | 1.56%   |
| Apple                         | 1        | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 9        | 14.06%  |
| Logitech HD Pro Webcam C920               | 9        | 14.06%  |
| Microsoft LifeCam HD-3000                 | 4        | 6.25%   |
| Logitech C922 Pro Stream Webcam           | 4        | 6.25%   |
| Generalplus CAMERA - UVC                  | 3        | 4.69%   |
| Samsung Galaxy series, misc. (MTP mode)   | 2        | 3.13%   |
| KYE Systems (Mouse Systems) Genius Webcam | 2        | 3.13%   |
| Jieli USB PHY 2.0                         | 2        | 3.13%   |
| Z-Star Venus USB2.0 Camera                | 1        | 1.56%   |
| ValueHD PTZOptics                         | 1        | 1.56%   |
| Tobii AB EyeChip                          | 1        | 1.56%   |
| Sunplus USB 2.0 Camera                    | 1        | 1.56%   |
| Sunplus FHD Camera Microphone             | 1        | 1.56%   |
| Ruision UVC Camera                        | 1        | 1.56%   |
| Realtek Full HD Webcam                    | 1        | 1.56%   |
| Quanta RGB-IR Camera                      | 1        | 1.56%   |
| Microsoft Modern Webcam                   | 1        | 1.56%   |
| Microsoft MicrosoftÂ LifeCam Studio      | 1        | 1.56%   |
| Microsoft MicrosoftÂ LifeCam Cinema      | 1        | 1.56%   |
| Microsoft LifeCam VX-800                  | 1        | 1.56%   |
| Microsoft LifeCam HD-5000                 | 1        | 1.56%   |
| Microdia Webcam Vitade AF                 | 1        | 1.56%   |
| Microdia USB Live camera                  | 1        | 1.56%   |
| Microdia Sonix USB 2.0 Camera             | 1        | 1.56%   |
| Magic Control j5 WebCam JVCU435           | 1        | 1.56%   |
| Logitech Webcam C170                      | 1        | 1.56%   |
| Logitech StreamCam                        | 1        | 1.56%   |
| Logitech HD Webcam C525                   | 1        | 1.56%   |
| Logitech CrystalCam                       | 1        | 1.56%   |
| Logitech C930c                            | 1        | 1.56%   |
| Logitech BRIO Ultra HD Webcam             | 1        | 1.56%   |
| Logitech B525 HD Webcam                   | 1        | 1.56%   |
| IMC Networks USB 2.0 Camera               | 1        | 1.56%   |
| GEMBIRD USB2.0 PC CAMERA                  | 1        | 1.56%   |
| EVGA XR1 Capture Box                      | 1        | 1.56%   |
| Creative Live! Cam Chat HD [VF0700]       | 1        | 1.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 1        | 1.56%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 50%     |
| SCM Microsystems      | 1        | 25%     |
| Cherry                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 50%     |
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 25%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC       | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 272      | 58.75%  |
| 1     | 170      | 36.72%  |
| 2     | 20       | 4.32%   |
| 5     | 1        | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 152      | 78.35%  |
| Net/wireless             | 18       | 9.28%   |
| Unassigned class         | 6        | 3.09%   |
| Bluetooth                | 4        | 2.06%   |
| Sound                    | 3        | 1.55%   |
| Communication controller | 3        | 1.55%   |
| Storage/raid             | 2        | 1.03%   |
| Camera                   | 2        | 1.03%   |
| Wireless                 | 1        | 0.52%   |
| Network                  | 1        | 0.52%   |
| Multimedia controller    | 1        | 0.52%   |
| Chipcard                 | 1        | 0.52%   |

